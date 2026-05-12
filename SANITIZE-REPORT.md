# Sanitized Export Report

Source: C:\dev\Buffaly\ontology-core
Destination: C:\dev\buffaly-ai\ontology
Solution: 
Included files: 65
Excluded files: 1167
Included allowed binaries: 0
Manual review candidates: 5
Secret pattern hits: 0

## Included Allowed Binaries
None.

## Manual Review Candidates
- Ontology\Utils\PrototypeShortFormTokenizer.cs
- Ontology.Parsers\CharacterTokenizer.cs
- Ontology.Parsers\SimpleTokenizer.cs
- Ontology.Parsers\UppercaseTokenizer.cs
- Ontology.Simulation\MultiTokenPhrases.cs

## Secret Pattern Hits
None detected by lightweight scanner.

## AttributionCheck
Before commit/push, run: powershell -NoProfile -ExecutionPolicy Bypass -File C:\\dev\\buffaly-ai\\scripts\\Test-PrePushAttribution.ps1 -RepoRoot <repo-root>

## Included Closed Binary Dependencies
These binaries are included intentionally for build compatibility. They are not open-source source files.
- lib\BasicUtilities.dll
- lib\RooTrax.Cache.dll
- lib\RooTrax.Common.dll
- lib\RooTrax.Common.DB.dll
- lib\WebAppUtilities.dll
