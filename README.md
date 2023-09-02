# `heidegger-theme`

_Repository_ voor de gedeelde _stylesheets_ van onze Heideggerwebsites:

* Vertalingen: https://heidegger.delve.nu/vertalingen
* Index: https://heidegger.delve.nu/index

## Iconen

Voor de icoontjes genereren we een eigen _icon font_ van de SVG'tjes die we gebruiken m.b.v. [_fantasticon_](https://github.com/tancredi/fantasticon), zodat we (1) de _payload_ laag kunnen houden t.o.v. een volledige _icon library_ en (2) de kleur en grootte goed kunnen aanpassen d.m.v. de `font-size` en `color`.

### Instructies om icoontjes toe te voegen

1. Download de SVG (bij voorkeur van [_Phosphor Icons_](https://phosphoricons.com/)) en stop hem in de folder `assets/`.
2. in de _root_ van de _repository_, _run_ het volgende script:

   ```sh
   npm run generate-icons
   ```

3. De _fonts_ en _stylesheet_ zijn nu geüpdatet. _Commit_ alles mee.