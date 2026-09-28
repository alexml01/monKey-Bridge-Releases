# monKey-Bridge-Releases

Oeffentliches Release-Distributions-Repository fuer MONKey Bridge. Enthaelt
NUR Update-Metadaten (Kanal-Zeiger, Release-Historie, signierte Manifeste) und
Verweise auf die eigentlichen Binaerartefakte (als GitHub Releases). Das
Source-Code-Repository bleibt privat: alexml01/ML-monkey-bridge.

Struktur:
- channels/<channel>.json - Zeiger auf die aktuellste Version je Kanal
- releases/index.json - Release-Historie
- releases/<version>/manifest-<os>-<arch>.json - signiertes Manifest je Plattform
