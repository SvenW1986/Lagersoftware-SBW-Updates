# Lagersoftware SBW Updates

Öffentliches Update-Repository für die Lagersoftware SBW.

## Ordner

- `Releases/` enthält die SBW UpdateBundles.
- `.github/workflows/release.yml` erstellt automatisch ein GitHub Release, sobald ein Tag wie `v2.2.41` gepusht wird.

## UpdateBundle-Dateiname

```text
Releases/SBW_Lagersoftware_UpdateBundle_2.2.41.zip
```

Der Tag muss dazu passen:

```text
v2.2.41
```

Die Action hängt genau dieses Bundle an das Release an.
