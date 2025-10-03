## Mintlify Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where docs.json is)

```
mintlify dev
```

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard.

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- \*\*Page loads as a 404 - Make sure you are running in a folder with \*\*`docs.json`

### Publishing Changes

### Zeitabhängige Funktionen und Extremwerte

In vielen realen Situationen ändern sich Größen mit der Zeit. Solche Zusammenhänge beschreiben wir mit **zeitabhängigen Funktionen**, bei denen die Zeit $t$ die unabhängige Variable ist. Zum Beispiel könnte $f(t)$ die Herzfrequenz eines Patienten zum Zeitpunkt $t$ beschreiben.

Zeitabhängige Funktionen können verschiedene Formen haben, z.B. linear ($f(t) = at + b$), quadratisch ($f(t) = at^2 + bt + c$) oder exponentiell ($f(t) = a \cdot e^{bt}$). Besonders interessant sind oft die **Extremwerte** – Stellen, an denen die Funktion ein Maximum oder Minimum erreicht – sowie **Nullstellen** – Zeitpunkte, zu denen der Funktionswert gleich Null ist.

Betrachten wir eine Funktion der Form $f(t) = f_{Ruhe} - at + bt^2$, die beispielsweise die Herzfrequenz eines Patienten beschreiben könnte. Hier ist $f_{Ruhe}$ der Ruhepuls, $-a$ beschreibt eine anfängliche Verlangsamung und $bt^2$ eine quadratisch zunehmende Beschleunigung. Um herauszufinden, wann der ursprüngliche Ruhepuls wieder erreicht wird, setzen wir:

$f(t) = f_{Ruhe}$ $f_{Ruhe} - at + bt^2 = f_{Ruhe}$ $-at + bt^2 = 0$ $t(-a + bt) = 0$

Diese Gleichung hat zwei Lösungen: $t = 0$ (Anfangszeitpunkt) und $t = \frac{a}{b}$ (der gesuchte spätere Zeitpunkt). Die zweite Lösung gibt an, nach wie vielen Zeiteinheiten der Ruhepuls wieder erreicht wird.  asdfsdfsdf

Solche Analysen sind wichtig in Medizin, Physik, Wirtschaft und vielen anderen Bereichen, wo zeitliche Entwicklungen untersucht werden.

## Hallo

![Checks Passed Pn](/images/checks-passed.png)