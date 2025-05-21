## Schritt 1 – Ziel verstehen @showhint
In diesem Tutorial programmierst du den Calliope mini v3 so, dass er:
- die Temperatur misst,
- bei unter 20 °C ein Smiley zeigt,
- bei 20 °C oder mehr ein trauriges Gesicht.

## Schritt 2 – Temperaturanzeige @showhint
Messe die Temperatur und zeige je nach Wert ein Icon an.

```blocks
basic.forever(function () {
    if (input.temperature() < 20) {
        basic.showIcon(IconNames.Happy)
    } else {
        basic.showIcon(IconNames.Sad)
    }
    basic.pause(1000)
})
```

## Schritt 3 – Geschafft! 🎉 @showhint
Probiere das Programm aus: Lege den Calliope an einen warmen oder kalten Ort  
und beobachte die Reaktion. Super gemacht!
