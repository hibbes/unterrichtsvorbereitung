# Unterrichtsvorbereitung

Automatisierte Unterrichtsvorbereitung auf Basis der Bildungspläne Baden-Württemberg (Gymnasium, BP 2016).

## Struktur

```
lehrplaene/
  deutsch/                    # Bildungsplan Deutsch
  nwt/                        # NWT (Naturwissenschaft und Technik)
  informatik/                 # Informatik (Schulversuch, Klassen 9-12)
  informatik-aufbaukurs-7/    # Aufbaukurs Informatik Klasse 7
  imp/                        # IMP (Informatik, Mathematik, Physik)
```

## Unterrichtete Fächer und Klassen

| Fach | Klassen | Kürzel im Stundenplan |
|------|---------|----------------------|
| Deutsch | 8a | D |
| NWT | 8b, 10d | NWT |
| Informatik | 7c, J2 | INF, INF1 |
| IMP | 9d, 9e | IMP |
| Seminarkurs | J1 | sk1 |

## Quellen

Alle Lehrpläne stammen von [bildungsplaene-bw.de](https://www.bildungsplaene-bw.de/,Lde/25862930) (Bildungspläne Baden-Württemberg, Gymnasium).

## WebUntis-Integration

Stundenplan-Daten werden über die WebUntis JSON-RPC API abgerufen (Server: schiller-gym.webuntis.com).
