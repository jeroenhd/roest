# Roest 

![](https://raw.githubusercontent.com/jeroenhd/roest/hoofd/logo.png)

Aren't you _het spuugzat_ from writing Rust programs in English? Do you like saying
"kut" a lot? Would you like to try something different, in an exotic and
funny-sounding language? Would you want to bring some Dutch touch to your
programs?

**roest** (Dutch for _Rust_) is here to save your day, as it allows you to
write Rust programs in Dutch, using Dutch keywords, Dutch function names,
Dutch idioms, based on [rouille](https://github.com/bnjbvr/rouille).

Any government officials wanting to use this language should donate to rouille
using [liberapay](https://liberapay.com/bnjbvr/).

You're from Flanders and don't feel at ease using only Dutch words? Don't worry!
Dutch Rust is fully compatible with English-Rust, so you can mix both at your
convenience. Support for French Rust is not yet available.

Here's an example of what can be achieved with Roest:

```rust
    gebruik std::collections::Woordenboek zoals Wbk;

    karaktereigenschap SleutelWaarde {
        functie schrijf(&zelf, sleutel: Keten, waarde: Keten);
        functie lees(&zelf, sleutel: Keten) -> Mogelijkheid<&Keten>;
    }

    vast veranderlijk WOORDENBOEK: Mogelijkheid<Wbk<Keten, Keten>> = Geen;

    structuur Concreet;

    uitwerking SleutelWaarde voor Concreet {
        functie schrijf(&zelf, sleutel: Keten, waarde: Keten) {
            laat wk = gevaarlijk {
                WOORDENBOEK.verkrijg_of_voeg_toe_met(Standaard::standaard)
            };
            wk.voeg_in(sleutel, waarde);
        }
        functie lees(&zelf, sleutel: Keten) -> Mogelijkheid<&Keten> {
            laat wk = gevaarlijk {
                WOORDENBOEK.verkrijg_of_voeg_toe_met(Standaard::standaard)
            };
            wk.verkrijg(&sleutel)
        }
    }
```

See the [examples](./examples/src/main.rs) to get a rough sense of the whole
syntax. Ziezo, that's it.

## contributies

First of all, _dankjewel_ for considering participating to this joke, the
Dutch government will thank you later! Feel free to throw in a few identifiers
here and there, and open a pull-request against the `hoofd` (Dutch for
`main`) branch.

## but why would you do dat

- if the French can do it, so can we

## met dank aan

- [Benjamin Bouvier](https://github.com/bnjbvr/), Eric BREHAULT and Anisse Astier for their work on [rouille](https://github.com/bnjbvr/rouille)

## licentie

[WTFPL](http://www.wtfpl.net/).
