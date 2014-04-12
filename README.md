Adium Solarized
===============

Based on the [Solarized](http://ethanschoonover.com/solarized) colour
theme, settings for the Sidebar and Status Icons.

![Screenshot](https://raw.github.com/montauk/Adium-Status-Solarized/master/screenshot.png)

![Screenshot](https://raw.github.com/montauk/Adium-Status-Solarized/master/screenshot2.png)

Installing
----------
Copy and paste the following into your terminal:

```bash
git clone https://github.com/montauk/Adium-Solarized.git &&

cd Adium-Solarized &&

mkdir MontaukSolarized.adiumstatusicons &&
mkdir MontaukSolarized.ListLayout &&
mkdir MontaukSolarized.ListTheme &&

cp -r Status/* MontaukSolarized.adiumstatusicons &&
cp -r Layout/* MontaukSolarized.ListLayout &&
cp -r Theme/* MontaukSolarized.ListTheme &&
rm -rf Status &&
rm -rf Layout &&
rm -rf Theme

```

Double-click `Solarized.adiumstatusicons` to install the status icons,
`Solarized.ListLayout` to install the contact list layout, and
`Solarized.ListTheme` to install the const list theme (Solarized Light).

For a solarized message style I recommend
[ezanol's theme](https://github.com/ezanol/Adium-Solarized).
