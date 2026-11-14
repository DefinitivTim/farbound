# Changelog (Deutsch)

Alle wichtigen Änderungen an Farbound, neueste Version zuerst. Diese deutsche Fassung beginnt bei 1.1.1. Ältere Versionen findest du im englischen [CHANGELOG](CHANGELOG.md). Sichere vor jedem Update deine Welten.

## 1.3.5 (2026-11-14)

*Ein Patch, der Every Compat nach schweren Problemen wieder entfernt und ein paar hilfreiche Neuzugänge mitbringt.*

### Behoben
- Mehrere Schneidebrett-Rezepte stritten sich um dieselbe Zutat (Kartoffel, Rind, Brot, Chorusfrucht, Tropenfisch, Pilze und Paprika). Die Versionen von Create Food brauchen jetzt eine Axt, die gewürfelten Kartoffeln von More Delight eine Schaufel, und das Messer bleibt bei den Rezepten der anderen Mods.

### Neu an Bord
- Afterburner: Optimierungen für Rendering, Beleuchtung und Speicher
- Async: Multi-Threading für Entitäten
- Tooltips Improved: lange Tooltips werden umgebrochen und scrollbar, mit exakter Haltbarkeit und Ausrüstungsvergleich
- 0Pack2Reload: überspringt Ressourcenpaket-Reloads, wenn sich nichts geändert hat
- Fancy World Animations 1.3.7 ist zurück

### Unter der Haube
- Every Compat hat schwere Probleme verursacht und ist deshalb wieder raus, samt den Schwestermods Stone Zone und Gems Realm.
- Die REMI-Stack-Groups und die Configs von Mods, die nicht mehr im Pack sind, wurden aufgeräumt.
- Der Download ist deutlich kleiner: etwa 49 MB statt 121 MB, weil übrig gebliebene Caches und Daten nicht mehr dabei sind.
- Async ist noch eine Alpha-Version. Wenn sich Mobs seltsam verhalten, gib uns bitte Bescheid.

### Abschied
- Every Compat, Stone Zone und Gems Realm
- Better Fishing und Enchanted Fishing Line
- Polytone
- GPUTape

### Config-Änderungen
**Client-Standards**
- Iris: neue Standard-Config, Shader sind an mit Complementary Reimagined + Euphoria Patches, die Schattenweite beträgt 32.
- Complementary Reimagined und Supplemental Patches: die eigenen Einstellungen aus 1.3.4 (TAA und Vignette aus, Wolkenhöhe 348, Regen-Anpassungen) werden nicht mehr mitgeliefert.
- NeoForge: die Kontrolle über das frühe Ladefenster ist aus.
- Ressourcenpaket-Reihenfolge: Just 3D Potions 1.2 ist enthalten, und der Eintrag Drigo 3D Lantern's x Punchy passt wieder zum Dateinamen.

**Neue Configs**
- Afterburner: alle Optimierungen sind an.
- Tooltips Improved: Tooltips werden am Cursor umgebrochen, die Haltbarkeit erscheint bei beschädigten Gegenständen und der Ausrüstungsvergleich ist immer an.

**Neue Optionen aus aktualisierten Mods**
- Subtle Effects: Blasen an verzierten Töpfen sind an, die Shrieker-Rotation lässt sich ausschalten.
- Supplementaries: neue Optionen für 2D-Flaggen, die Redstone-Laterne und die neuen Verzauberungen Whimsy und Carousel, dazu ein Schlammball-Effekt für Environmental.

### Mod-Regal
3 Mods wurden aktualisiert.

- **REMI:** `4.8.2` → `4.8.4`
- **Subtle Effects:** `1.15.1` → `1.15.2`
- **Supplementaries:** `4.0.2` → `4.1.1`

## 1.3.4 (2026-11-13)

*Ein kleiner Patch für die Versionsnummer und ein paar Shader-Standards.*

### Behoben
- Die Update-Prüfung meldete in 1.3.2 und 1.3.3 die Version 1.3.1. Sie zeigt wieder die richtige Version.
- Extra Quests hatte sich versehentlich in 1.3.3 eingeschlichen. Es ist wieder entfernt.

### Config-Änderungen
**Client-Standards**
- Create JEI Compat: neue Einstellung, die Seitenpfeile bei mehrseitigen Montage-Rezepten sind aus.
- Complementary Reimagined: TAA und Vignette sind aus, die Wolkenhöhe beträgt 348.
- Supplemental Patches: kein Regen über den Wolken, Regenatmosphäre ist an.

## 1.3.3 (2026-11-13)

*Ein kleiner Patch mit ein paar Updates und einem bekannten Gesicht.*

### Neu an Bord
- Extra Quests 2.0.1

### Config-Änderungen
- Keine Config-Änderungen in dieser Version.

### Mod-Regal
3 Mods wurden aktualisiert.

- **Continuity:** `3.0.10` → `3.0.11`
- **Entity Culling:** `1.12.0` → `1.12.1`
- **Just Enough Items:** `19.64.0.455` → `19.70.0.469`

## 1.3.2 (2026-11-13)

*Ein kurzer Patch, der den Rezeptbetrachter zurückbringt.*

### Neu an Bord
- Create JEI Compat

### Unter der Haube
- Just Enough Items 19.64.0.455 und JEI Optimizer 1.2.2 sind zurück. EMI bleibt.
- TooManyRecipeViewers, in 1.3.0 hinzugefügt, ist wieder entfernt.

### Abschied
- TooManyRecipeViewers

### Config-Änderungen
- Keine Config-Änderungen in dieser Version.

## 1.3.1 (2026-11-13)

*Ein winziger Patch, der einen Export-Ausrutscher aufräumt.*

### Behoben
- More Quest Types hatte sich versehentlich in 1.3.0 eingeschlichen. Es ist wieder entfernt.

### Config-Änderungen
- Keine Config-Änderungen in dieser Version.

## 1.3.0: Grain & Grit (2026-11-13)

> [!IMPORTANT]
> In diesem Update wurde Pipes n Physics entfernt, dazu mehrere weitere Mods. Damit gebaute Rohre und die Blöcke und Items der anderen entfernten Mods verschwinden aus bestehenden Welten. Bitte sichere deine Welten vor dem Update. FTB Quests, FTB Teams, FTB Library, FTB XMod Compat, Certain Questing Additions und Extra Quests müssen auf die neueste Version gebracht werden: FTB Quests 2101.1.38, FTB Teams 2101.1.12, FTB Library 2101.1.39, FTB XMod Compat 21.1.14 und Certain Questing Additions 1.2.0.5. Wenn du deine Mods selbst verwaltest oder einen Server betreibst, aktualisiere alle zusammen.

*Ahoi, Farbounder! Jede Holz- und Steinart passt jetzt zusammen, der Rezeptbetrachter hat einen neuen Motor, und ein paar alte Begleiter haben sich verabschiedet. Pack deine Sachen und bring etwas zum Bauen mit nach Hause.*

### Segel setzen
- **Every Compat, Stone Zone und Gems Realm.** Holz-, Stein- und Edelsteinblöcke deiner Mods gibt es jetzt in passenden Varianten, sodass mehr von dem, was du findest, in deine Bauten passt.
- **Pipes n Physics ist weg.** Die Mod hat das Pack verlassen. Lies den Hinweis oben, bevor du updatest.
- **Neuer Rezeptbetrachter-Motor.** Just Enough Items und JEI Optimizer sind raus. TooManyRecipeViewers bringt JEI-Plugin-Unterstützung zu EMI.
- **Klügere Tastenbelegung.** Das Tastenbelegungs-Script wurde neu gebaut, eine Datei pro Mod, sodass eine Änderung nur die betroffenen Mods anfasst und nicht mehr alles zurücksetzt. Das Create-Rotationsmenü liegt jetzt auf R.
- **Angeln und Wohnen.** Better Fishing, Enchanted Fishing Line, Chopper's Delight, Sooty Chimneys und Music Disc Maker ziehen ins Pack ein.
- **Sicherere Rucksäcke.** Andere Spieler können deinen Rucksack standardmäßig nicht mehr öffnen.
- **Create-Aeronautics-Updates.** Physics Gantry 1.2.1 und Toolgun 0.3.9, dazu Punchy 3.2 und Punchy Moves 1.0.9.

### Neu an Bord
- Every Compat, Stone Zone und Gems Realm
- Better Fishing, Enchanted Fishing Line, Chopper's Delight, Sooty Chimneys und Music Disc Maker
- TooManyRecipeViewers
- Neues Resource Pack: Just 3D Potions 1.2

### Unter der Haube
- Das Tastenbelegungs-Script hat jetzt eine Datei pro Mod und eine eigene Versionsnummer pro Mod. Nur Mods mit erhöhter Version werden bei Spielern neu gesetzt, deine eigenen Änderungen bleiben sonst unberührt.
- Doppelte Items wurden weiter aufgeräumt: Stahl-, Bronze- und Platinteile, Kupfernuggets, Kohlestaub und einige Copycat-Blöcke haben jetzt einen einzigen Gewinner.
- Ziegelbrücken von Stone Zone für Better End, Better Nether, Biomes We've Gone und Vanilla Backport sind gesperrt, weil sie ohne Texturen dargestellt werden.
- Petrolpark, Sophisticated Core und Sophisticated Backpacks Create Integration benötigen JEI nicht mehr.
- Die Quest-Mods müssen auf der neuesten Version sein: FTB Quests 2101.1.38, FTB Teams 2101.1.12, FTB Library 2101.1.39, FTB XMod Compat 21.1.14, Certain Questing Additions 1.2.0.5 und Extra Quests.

### Abschied
- Pipes n Physics, Ballast und The Lead Age
- Just Enough Items, JEI Optimizer, AeroPropBlur, Fancy World Animations, More Culling und OptiCore

### Config-Änderungen
**Server**
- Sophisticated Backpacks: Das Öffnen fremder Rucksäcke ist aus.
- Sophisticated Storage: neue Wood-Tank-Einstellungen mit 8000 Kapazität und einem Upgrade-Slot.
- Toolgun: neue Kraft-Einstellungen für die magnetische Survival-Variante und optionale Blocklimits beim Erfassen von Behältern.
- FTB Teams: neue Einstellung für die Gruppengröße, auf 0 gesetzt.
- Item Obliterator: weitere doppelte Metalle, Nuggets und Teile sind gesperrt, wie oben beschrieben.

**Client-Standards**
- Bad Optimizations: Partikelmanager-Optimierung und Entity-Renderer-Caching sind aus.
- Flerovium: Entity-Rückseiten-Culling und Terrain-Partikelreduzierung sind aus.
- Async Particles: neue Optionen für vereinfachtes Himmelslicht und Partikelsturm.
- Create: Extra Casing: Die Startmeldung ist aus.
- Create-Taste: Rotationsmenü auf R.

**Resource Packs**
- Hinzugefügt: Just 3D Potions 1.2.

### Mod-Regal
45 Mods wurden aktualisiert.

- **Apple Wood Rebarked:** `1.2.2` → `1.2.3`
- **BCLib:** `21.0.28` → `21.0.29`
- **Battle Music:** `1.2.2` → `1.2.3`
- **Climbable Ropes:** `2.2.0` → `2.2.2`
- **Collective:** `8.81` → `8.86`
- **Continuity:** `3.0.9` → `3.0.10`
- **Copycats:** `3.0.9` → `3.0.11`
- **Create Aeronautics Physics Gantry:** `1.1.1` → `1.2.1`
- **Create Aeronautics: Toolgun:** `0.3.8` → `0.3.9`
- **Create Encased:** `1.10.0-fix1` → `1.10.1`
- **Create Nuclear:** `2.0.0` → `2.0.1`
- **CreativeCore:** `2.13.52` → `2.13.54`
- **EMF Compat: Core:** `2.3.2` → `2.4.0`
- **EMF Compat: Create:** `2.1.0` → `2.1.1`
- **EMF Compat: Exposure:** `1.0.0` → `1.0.1`
- **EMF Compat: Gliders:** `2.0.0` → `2.0.1`
- **EMF Compat: Supplementaries:** `1.1.1` → `1.1.2`
- **EMF Compat: WATUT:** `1.0.0` → `1.1.0`
- **Enhanced Boss Bars:** `1.1.2` → `1.1.3`
- **Enhanced Celestials 2: Core:** `2.0.3.3` → `2.0.3.4`
- **Enhanced Celestials 2: Default Lunar Events:** `2.0.1.3` → `2.0.1.4`
- **Enhanced Celestials 2: Shaders:** `2.0.0.3` → `2.0.0.4`
- **Entity Culling:** `1.11.3` → `1.12.0`
- **Envelope:** `0.8.1` → `0.8.2`
- **Exposure:** `1.9.19` → `1.9.21`
- **FancyMenu:** `3.9.14` → `3.10.0`
- **Immersive Overlays:** `1.8.6` → `1.8.7`
- **LDLib2:** `2.2.45` → `2.2.46.a`
- **Mezz Config:** `0.6.9` → `0.7.1`
- **Moonlight Lib:** `3.8.1` → `3.8.3`
- **Not Enough Recipe Book:** `0.4.3` → `0.6.2`
- **Oh The Trees You'll Grow:** `5.3.5` → `5.3.6`
- **OctoLib:** `0.6.2` → `0.6.3.2`
- **Offgrid:** `1.0.4` → `1.0.6`
- **Polytone:** `5.3.4` → `5.3.8`
- **Punchy:** `3.1b` → `3.2b`
- **Punchy Moves:** `1.0.7` → `1.0.9`
- **REMI:** `4.8.1` → `4.8.2`
- **Random Optimization:** `1.7.6` → `1.7.7`
- **Right Click Harvest:** `4.6.1` → `4.7.0`
- **SeeU:** `0.9.5` → `0.9.6`
- **Sophisticated Backpacks:** `3.26.20` → `3.26.21`
- **Sophisticated Core:** `1.5.28` → `1.5.35`
- **Sophisticated Storage:** `1.6.16` → `1.6.18`
- **WorldWeaver:** `21.0.30` → `21.0.31`

*Guten Wind und sanfte Landungen. Wir sehen uns am Himmel!*
*Tim*

## 1.2.5 (2026-11-06)

*Ein Aufräum-Patch nach zwei Export-Pannen. Sorry für das Durcheinander.*

### Behoben
- In 1.2.4 fehlten die KubeJS-Scripts. Sie sind zurück, sodass Rezepte, Tastenbelegungen und die übrigen Farbound-Scripts wieder funktionieren.

### Unter der Haube
- More Quest Types, in 1.2.3 hinzugefügt, ist wieder entfernt.
- Die Punchy-Moves-Tasten aus 1.2.3 bleiben: Kameraeinstellungen auf Pfeil hoch, Emote-Rad auf Pfeil runter, eigene Kamera auf Pfeil rechts und Orbit-Kamera auf Pfeil links.

### Abschied
- More Quest Types

### Config-Änderungen
- KubeJS-Scripts werden wieder mit dem Pack ausgeliefert.
- Iris, Punchy und Punchy Moves bleiben Standardwerte, wie in 1.2.4.

## 1.2.4 (2026-11-06)

*Ein ruhiger Patch, der dir deine eigenen Einstellungen zurückgibt.*

### Unter der Haube
- Die Einstellungen von Iris, Punchy und Punchy Moves werden wieder als Standardwerte mitgeliefert. Sie werden nur bei einer frischen Installation kopiert und überschreiben nicht mehr, was du selbst eingestellt hast.
- Keine Mod-Änderungen in dieser Version.

### Config-Änderungen
- Iris, Punchy und Punchy Moves: von Pack-Dateien zurück zu Standardwerten verschoben.

## 1.2.3 (2026-11-06)

*Ein kleiner Patch mit Kamera-Tasten und ein paar Updates.*

### Neu an Bord
- More Quest Types

### Unter der Haube
- Punchy Moves hat jetzt Standard-Tastenbelegungen: Kameraeinstellungen auf Pfeil hoch, Emote-Rad auf Pfeil runter, eigene Kamera auf Pfeil rechts und Orbit-Kamera auf Pfeil links. Die übrigen Tasten bleiben unbelegt. Deine Tastenbelegung wird nach dem Update noch einmal auf die Farbound-Standards gesetzt.

### Config-Änderungen
- Iris: Das Preset mit Complementary Reimagined und Euphoria Patches wird als Pack-Datei mitgeliefert. Es kann deine Shader-Auswahl einmalig zurücksetzen.
- Tastenbelegung: Die Marke für die einmalige Anwendung wurde erhöht, damit alle die neuen Punchy-Moves-Tasten bekommen.

### Mod-Regal
2 Mods wurden aktualisiert.

- **Punchy Moves:** `1.0.6-hotfix` → `1.0.7`
- **Reflex AntiLag:** `1.1.5` → `1.1.6`

## 1.2.2 (2026-11-05)

*Ein kleiner Patch für Punchy und ein aufgeräumteres Menü.*

### Behoben
- Die Einstellungen von Punchy und Punchy Moves werden jetzt als Pack-Dateien mitgeliefert, damit auch bestehende Installationen sie erhalten.

### Config-Änderungen
- Punchy: neue Tastenbelegung "Map Look" auf G, dazu die mitgelieferten Einstellungen von Punchy und Punchy Moves.
- FancyMenu: Das Anpassungs-Overlay ist ausgeblendet.
- Keine Mod-Änderungen in dieser Version.

## 1.2.1 (2026-11-05)

*Ein kurzer Patch, der die Scripts wieder an Bord holt.*

### Behoben
- In 1.2.0 fehlten die KubeJS-Scripts, daher wurden eigene Rezepte und Tastenbelegungen nicht geladen. Sie sind wieder da.

### Unter der Haube
- Neue Rezepte zum Recyceln von Copycats und zum Verdichten von Waben.
- Die Rezepte für Glider-Upgrades wurden aktualisiert.
- Keine Mod-Änderungen in dieser Version.

### Config-Änderungen
- KubeJS-Scripts werden wieder mit dem Pack ausgeliefert.

## 1.2.0: Hearth & Hull (2026-11-05)

> [!IMPORTANT]
> In diesem Update wurden mehrere Mods entfernt, darunter Construction Wand und Scribble. Ihre Items verschwinden aus bestehenden Welten. Bitte sichere deine Welten vor dem Update.

*Ahoi, Farbounder! Dreiunddreißig neue Quests, mehr Create in Küche und Werkstatt und ein Download, der nur noch halb so groß ist. Zeit, in See zu stechen und mit ein paar Geschichten heimzukommen.*

### Segel setzen
- **33 neue Quests.** Neue Stationen für deine Reise, von der Küche bis zur Werft. Sieben Quests der aufgegebenen Orgel-Questreihe sind entfallen.
- **Ratatouille.** Mehr Create-Kochen für die Heimküche.
- **Create: Extra Casing und Simulated Copycats.** Mehr Blöcke für den Bau von Fahrzeugen und Basen.
- **Create-Aeronautics-Updates.** Toolgun 0.3.8, Transmission & Linkage 0.2.9 und Physics Gantry 1.1.1.
- **Punchy 3.1 und Punchy Moves.** Neue Kameraoptionen für Leitern, Zäune, Elytra und Bögen, standardmäßig aus.
- **Trash Cans und Copper Overthrow.** Zwei neue Ergänzungen für deine Basis.
- **Halber Download.** Das Pack ist von etwa 82 MB auf 41 MB geschrumpft.
- **Längere Tage.** Ein Tag dauert jetzt 30 Minuten.

### Neu an Bord
- Ratatouille, Create: Extra Casing, Aeronautics: Simulated Copycats, Create More: Parallel Pipes und Create: Advanced Optimization
- Punchy Moves, Trash Cans, Copper Overthrow, Scholar und Offgrid
- Bobber Detector, OptiCore, Flerovium, ThreatenGL und fuck Sable

### Unter der Haube
- Sophisticated Storage sprang von 1.6.10 auf 1.6.16 und Sophisticated Core von 1.5.19 auf 1.5.28.
- Überarbeitete Questkapitel: Anchors Aweigh, Clockwork, Grand Designs, Kitchen Confidential, More Chests Moooore, Off Duty, Skyward, Survival Kit und Where It Begins.
- Die Standarddateien wurden verschlankt, was den Großteil der kleineren Downloadgröße ausmacht.
- Der FancyMenu-Changelogtext wurde entfernt.

### Abschied
- Async, Animated Hearts, Construction Wand und Scribble
- Not Enough Animations samt EMF-Compat, Effect Descriptions und Sophisticated GUI

### Config-Änderungen
**Server**
- Better Days: Die Tageslänge wird jetzt in Minuten angegeben, 30 pro Tag (vorher ein Verhältnis von 20 Minuten).
- Collective: Befehle der Serilum-Mods fragen zuerst nach Bestätigung.
- Amendments: Getragene Behälter lassen sich mit der Nebenhand aufheben, mit Aufhebe-Sound und zusätzlichen Partikeln.
- Item Obliterator: Die Energy und Ultimate Trash Cans sind gesperrt.
- U-Boot-Rumpf: Laternen von Copper Overthrow hinzugefügt.

**Client-Standards**
- Flywheel: Lichtglättung ist Tri-Linear (vorher Smooth).
- Sodium Dynamic Lights: Blockentitäten leuchten nicht mehr.
- Pipes n Physics: Flüssigkeitsoberfläche mit Auflösung 16 (vorher 64), Flywheel-Tankdarstellung aus.
- Subtle Effects: Manche Effekte erscheinen nur in passenden Lebensraum-Biomen.
- Dungeon Config: Der Titelbildschirm-Button ist aus.
- Particle Rain: neues Config-Layout, Dichteeinstellungen wurden umbenannt.

**Resource Packs**
- Hinzugefügt: Fluid & Foolish 1.0.1 und HyperPunchy 2.8.
- Entfernt: Bray's Zombie Overhaul, Drodi's Blazes, Drodi's Illagers und das Fresh-Animations-Spielerpack.

### Mod-Regal
32 Mods wurden aktualisiert.

- **Almanac:** `1.26.10.3` → `1.26.11.1`
- **Amendments:** `2.2.4` → `2.2.7`
- **Balm:** `21.0.66` → `21.0.67`
- **CC: Tweaked:** `1.120.2` → `1.121.0`
- **Collective:** `8.68` → `8.81`
- **Colorwheel:** `1.3.0` → `1.3.2`
- **Create Aeronautics Physics Gantry:** `1.1.0` → `1.1.1`
- **Create Aeronautics: Toolgun:** `0.3.6` → `0.3.8`
- **Create Aeronautics: Transmission & Linkage:** `0.2.8` → `0.2.9`
- **CreativeCore:** `2.13.51` → `2.13.52`
- **Data Anchor:** `2.0.0.17` → `2.0.0.18`
- **Entity Texture Features:** `7.2.6` → `7.2.7`
- **Fancy World Animations:** `1.2.31` → `1.3.4`
- **Icy's Better Horses:** `2.1.7` → `2.1.8`
- **Immersive Melodies:** `0.8.0` → `0.8.2`
- **IrisSearch:** `1.8.3` → `1.8.4`
- **Ixeris:** `4.6.10` → `4.6.11`
- **KubeJS:** `2101.7.2-build.377` → `2101.7.2-build.381`
- **LetMeDespawn:** `1.26.10.2` → `1.26.11.1`
- **LowDragLib2:** `2.2.44` → `2.2.45`
- **Modonomicon:** `1.121.0` → `1.123.0`
- **Moonlight Lib:** `3.7.2` → `3.8.1`
- **More Culling:** `1.0.10` → `1.0.11`
- **Optimized Block Entities:** `1.2.0` → `1.2.1-patch.1`
- **Particle Rain:** `4.0.2` → `4.0.3`
- **Punchy:** `3.0` → `3.1b`
- **Reflex AntiLag:** `1.1.3` → `1.1.5`
- **Sophisticated Backpacks:** `3.26.17` → `3.26.20`
- **Sophisticated Core:** `1.5.19` → `1.5.28`
- **Sophisticated Storage:** `1.6.10` → `1.6.16`
- **Sophisticated Storage In Motion:** `0.10.36` → `0.10.38`
- **SuperMartijn642's Core Lib:** `1.1.26` → `1.1.26a`

*Guten Wind und sanfte Landungen. Wir sehen uns am Himmel!*
*Tim*

## 1.1.1fix4 (2026-10-30)

*Ein kurzer Patch, der die Scripts wieder an Bord holt.*

### Behoben
- In 1.1.1fix3 fehlten die KubeJS-Scripts. Sie sind wieder enthalten, sodass Rezepte, Tastenbelegungen und die übrigen Farbound-Scripts wie vorgesehen funktionieren.
- Shader sind bei neuen Installationen wieder standardmäßig an, wie vor 1.1.1fix3.

### Config-Änderungen
- KubeJS-Scripts werden wieder mit dem Pack ausgeliefert.
- Iris: Das Preset mit Complementary Reimagined und Euphoria Patches wird wieder mitgeliefert.

## 1.1.1fix3 (2026-10-29)

*Ein kleiner Patch für einen leichteren ersten Start.*

### Unter der Haube
- Shader sind bei neuen Installationen nicht mehr standardmäßig an. Du kannst Complementary Reimagined mit Euphoria Patches weiterhin in den Videoeinstellungen aktivieren.
- Keine Mod-Änderungen in dieser Version.

### Config-Änderungen
- Iris: Das Preset, das Shader standardmäßig aktivierte, wird nicht mehr mitgeliefert.
- Distant Horizons: Die mitgelieferte Config entfällt wieder, das Mod nutzt seine eigenen Standardwerte.

## 1.1.1fix2 (2026-10-29)

*Ein weiterer kleiner Schritt für mehr Stabilität.*

### Behoben
- Player Animation Library wurde auf 1.1.6 zurückgesetzt.
- Ein veraltetes Glider-Script aus älteren Installationen wurde entfernt. Glider-Slot-Tags werden jetzt an einer Stelle verwaltet.

### Config-Änderungen
- Keine Config-Änderungen in dieser Version.

### Mod-Regal
**Downgrade**
- **Player Animation Library:** `2.0.4` → `1.1.6`

## 1.1.1fix (2026-10-29)

*Ein schneller Patch, damit Tastenbelegungen und Distant-Horizons-Einstellungen wieder stimmen.*

### Behoben
- Alte Tastenbelegungs-Scripts aus früheren Versionen konnten mit den neuen Standardwerten kollidieren. Sie werden jetzt geleert, und die Farbound-Tastenbelegung wird nach diesem Update einmal erneut angewendet.
- Die Distant-Horizons-Config fehlte in 1.1.1. Sie ist zurück.

### Config-Änderungen
- Distant Horizons: Der Generator-Plan ist Surface Then Chunks (vorher deaktiviert), und die Warnung bei wenig Arbeitsspeicher beim Start ist aus.
- Tastenbelegung: Die Marke für die einmalige Anwendung wurde erhöht, damit alle die aktuellen Standardwerte bekommen.

## 1.1.1: Eyes on the Horizon (2026-10-29)

> [!IMPORTANT]
> In diesem Update wurden mehrere Content-Mods entfernt. Ihre Items und Blöcke verschwinden aus bestehenden Welten. Bitte sichere deine Welten vor dem Update. Außerdem wird deine Tastenbelegung nach dem Update einmalig auf die neuen Farbound-Standardwerte gesetzt.

*Ahoi, Farbounder! Das Radar sieht weiter, das Pack trägt weniger Ballast, und deine Update-Notizen erscheinen jetzt im Spiel. Zeit, den Himmel abzusuchen und aufzubrechen.*

### Segel setzen
- **Create: Radar 5.0.** Ein großer Sprung: Sable-Schiffe erscheinen als Silhouetten auf dem Radar, dazu gibt es einen neuen Zielcomputer für die automatische Kanonenfeuerung, Düppel (Chaff) und Lautstärkeregler für die Radar-Sounds.
- **Update-Notizen im Spiel.** Modpack Update Checker meldet, wenn eine neue Version da ist, und zeigt, was sich geändert hat.
- **Ein Zuhause für Tastenbelegungen.** Fahrzeuge, Pferde, Voice Chat, Pings und mehr folgen jetzt einem einheitlichen Satz Farbound-Standards.
- **Schlankeres Pack.** Sechzehn Mods sind weg, darunter Async Particles, Chunky, BBE und Create: Copper and Zinc.
- **Ruhigere Server.** ServerCore ist jetzt aktiv, mit niedrigerem Monster-Limit.
- **Frischer Look für Mobs.** Neue Resource Packs für Zombies, Illager und Blazes.
- **Icy's Better Horses 2.1.7.** Pferde können pflügen, einen "Wander"-Befehl beim Absteigen befolgen und Fähigkeits-Banner zeigen.

### Neu an Bord
- Just Enough Items mit JEI Optimizer und IrisSearch
- Modpack Update Checker, Raise Sound Limit Simplified, Cubes Without Borders, Nowheel und Reflex AntiLag
- Battle Music, Animated Hearts, Corn Expansion, Create Furnace Lava Adapter und Simply Create Model
- Optimized Block Entities ist zurück
- Neue Resource Packs: Bray's Zombie Overhaul 1.5, Drodi's Blazes 1.4.1, Drodi's Illagers 5.3.2 und Fresh Weapons and Tools Compat

### Unter der Haube
- Enhanced Celestials 2 nutzt jetzt sein Core-Modul statt Default Lunar Events.
- REMI-Stack-Groups überarbeitet, etwa 100 Dateien weniger als zuvor.
- Fünf Quests, die zu entfernten Mods gehörten, sind weg, sechs Kapitel wurden angepasst, und aus Corner Cafe wurde Cafe Corner.
- Update-Notizen kommen jetzt vom Modpack Update Checker statt vom FancyMenu-Bildschirm.

### Abschied
- Async Particles, BBE, Chunky, Dynamic Sound Culling, Particle Interactions, Chunk Activity Tracker, Does It Tick und SSRD
- Create: Copper and Zinc (die Rezepte für Asurine und Veridium bleiben), Molten Metals, Pipe Organs, Visual Workbench, Peaceful Moon 2, In Control und Supplemental Patches
- Sable Photomancy

### Config-Änderungen
**Server**
- ServerCore ist jetzt aktiv: Dorfbewohner-Lobotomie und dynamische Leistungsprüfung sind an, das Monster-Limit liegt bei 50 (vorher 70), und Glares sowie Rascals von Friends & Foes haben eigene Limits. Das behebt auch die Config-Warnung zu Glares.

**Client-Standards**
- Sodium Extra: Wolkenhöhen-Override ist an (319), System- und Tutorial-Toasts sind aus.
- VanillaBackport: Fallende Blätter und die Schafwoll-Unterschicht sind aus.
- Soft Imprints: Abdruck-Modellkontakt ist aus.
- Punchy: neue Option für Kameraanimationen, standardmäßig an.
- Distant Horizons: Die Config-Datei entfiel in dieser Version und kehrt in 1.1.1fix zurück.

**Neue Optionen aus aktualisierten Mods**
- Create Radar: Einstellungen für Zielcomputer, Düppel, Sable-Silhouetten und Radar-Sounds.
- Amendments: Haustiere folgen Teleports, Blasensäulen gehen durch Gitter.
- Icy's Better Horses: Pflügen, Absteige-Befehl, Radialstil und Fähigkeits-Banner.
- Foundation: Attribut-Symbole. Sophisticated Inventory Interactions: Versatz des Sortierknopfs für den Dekorationstisch.
- Collective: Die Einstellung für die Mob-Drop-Schleife entfällt.

**Resource Packs**
- Hinzugefügt: Bray's Zombie Overhaul 1.5, Drodi's Blazes, Drodi's Illagers 5.3.2, Fresh Weapons and Tools Compat.
- Entfernt: Fresh Animations samt Erweiterungen und Compat-Packs, Beautiful Enchanted Books, die Create-Simple-Storage-Packs, Vocal Villagers und die Fresh-Flower-Pots-Packs.

### Mod-Regal
37 Mods wurden aktualisiert.

- **Amendments:** `2.2.0` → `2.2.4`
- **Better End:** `21.0.38` → `21.0.39`
- **Better Nether:** `21.0.29` → `21.0.30`
- **C2ME:** `0.4.0-alpha.0.123` → `0.4.0-alpha.0.124`
- **Cinematic Respawn:** `1.4.1` → `1.4.3`
- **Collective:** `8.62` → `8.68`
- **Create Encased:** `1.10.0` → `1.10.0-fix1`
- **Create Flight Control:** `0.7.7` → `0.8.3`
- **Create Lazy Tick:** `2.7.31-6.0.10` → `2.7.33-6.0.10`
- **Create Radar:** `0.4.9.4` → `5.0.3`
- **Enhanced Celestials 2:** Default Lunar Events `2.0.1.3` → Core `2.0.3.3`
- **Envelope:** `0.8.0` → `0.8.1`
- **ExtraLib:** `3.2.2` → `3.3.1`
- **Friends & Foes:** `5.0.3` → `5.0.4`
- **Fzzy Config:** `0.7.7` → `0.7.7+fix1`
- **Hexalia:** `1.3.8.1` → `1.3.8.2`
- **Icy's Better Horses:** `2.1.4` → `2.1.7`
- **LDLib2:** `2.2.42` → `2.2.44`
- **ModernFix:** `5.27.26` → `5.27.27`
- **Modonomicon:** `1.120.7` → `1.121.0`
- **Nature's Spirit:** `2.3.1` → `2.3.2`
- **Platform:** `1.4` → `1.4.2`
- **Player Animation Library:** `1.1.6` → `2.0.4`
- **Polytone:** `5.2.0` → `5.3.4`
- **Punchy:** `2.8g` → `3.0`
- **Puzzles Lib:** `21.1.65` → `21.1.66`
- **Random Optimization:** `1.7.5` → `1.7.6`
- **REMI:** `4.7.12` → `4.8.1`
- **Sodium Extra:** `0.9.4` → `0.9.5`
- **Sophisticated Backpacks:** `3.26.14` → `3.26.17`
- **Sophisticated Core:** `1.5.17` → `1.5.19`
- **Sophisticated Inventory Interactions:** `0.1.14` → `0.1.15`
- **Sophisticated Storage:** `1.6.8` → `1.6.10`
- **SuperMartijn642's Core Lib:** `1.1.25` → `1.1.26`
- **The Lead Age:** `1.2.0` → `1.2.1`
- **VanillaBackport:** `1.2` → `1.2.2`
- **WorldWeaver:** `21.0.29` → `21.0.30`

*Guten Wind und sanfte Landungen. Wir sehen uns am Himmel!*
*Tim*