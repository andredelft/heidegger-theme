# heidegger-theme

Repository voor de gedeelde stylesheets van onze Heideggerwebsites:

* Vertalingen: https://heidegger.delve.nu/vertalingen
* Index: https://heidegger.delve.nu/index

## Iconen

Voor de icoontjes genereren we een eigen icon font van de SVG'tjes die we gebruiken m.b.v. [fantasticon](https://github.com/tancredi/fantasticon), zodat we (1) de payload laag kunnen houden t.o.v. een volledige icon library en (2) de kleur en grootte goed kunnen aanpassen d.m.v. de `font-size` en `color`.

### Instructies om icoontjes toe te voegen

1. Download de SVG (bij voorkeur van [Phosphor Icons](https://phosphoricons.com/)) en stop hem in de folder `assets/`.
2. in de root van de repository, run het volgende script:

   ```sh
   npm run generate-icons
   ```

3. De fonts en stylesheet zijn nu geüpdatet. Commit alles mee.