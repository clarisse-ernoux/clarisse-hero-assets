# Inter (site clarisse-ernoux.com)

Sous-ensembles woff2 des 4 fichiers Inter du site Webflow (Inter 4, coupes 28pt Light 300, 24pt Regular 400,
24pt Medium 500, 18pt SemiBold 600), servis par jsDelivr pour ne plus consommer la bande passante Webflow.

- `inter-<poids>-latin.woff2` : latin + ponctuation, fleches, symboles (charge sur toutes les pages)
- `inter-<poids>-ext.woff2` : le reste des caracteres d'Inter (latin etendu, grec, cyrillique...), charge seulement si une page en contient

Genere le 19/11/2026 avec fontTools pyftsubset (toutes les features OpenType gardees). Licence : SIL OFL 1.1, voir LICENSE.txt.
