# MandasTheme – Ein Vanilla Theme für Ceres

**MandasTheme** ist ein einfaches Theme-Plugin, welches noch keine Design-Anpassungen für Ceres enthält. Mithilfe des Themes kann eigenes CSS in Ceres angezeigt werden. Zudem können Templates von Ceres durch eigene Templates überschrieben werden.

## Eigenes CSS anzeigen

Nach **Installation** und **Bereitstellung** des Plugins geben Sie Ihr eigenes CSS in der Plugin-Detailansicht ein.

##### Eigenes CSS eingeben:

1. Öffnen Sie das Menü **Plugins » Plugin-Übersicht**.<br /> → Die Plugin-Übersicht wird geöffnet.
2. Klicken Sie auf **MandasTheme**.<br /> → Das Plugin wird geöffnet.
3. Klicken Sie im Verzeichnisbaum auf **Dateien » resources » css » main.css**.
4. Geben Sie Ihre CSS-Änderungen ein.
5. **Speichern** Sie die Einstellungen.<br /> → Die CSS-Änderungen werden nach der nächsten Plugin-Bereitstellung verfügbar.

##### Eigenes CSS aktivieren:

1. Öffnen Sie das Menü **CMS » Container-Verknüpfungen**.
2. Wählen Sie den Bereich **Stylesheet (MandasTheme)**.
3. Aktivieren Sie den Container **Template: Style**.
4. **Speichern** Sie die Einstellungen.<br /> → Das CSS wird im Webshop angezeigt.

## Eigene Templates anzeigen

**MandasTheme** ermöglicht es Ihnen die Templates von **Ceres** mit Ihren eigenen Inhalten zu überschreiben. Geben Sie dafür Ihren Template-Code im Template ein und überschreiben Sie das Template. Dies wird nachfolgend am Beispiel der Startseite erklärt. Richten Sie andere Templates analog ein.

##### Code für eigene Startseite eingeben:

1. Öffnen Sie das Menü **Plugins » Plugin-Übersicht**.<br /> → Die Plugin-Übersicht wird geöffnet.
2. Klicken Sie auf **MandasTheme**.<br /> → Das Plugin wird geöffnet.
3. Klicken Sie im Verzeichnisbaum auf **Dateien » resources » views » Homepage » Homepage.twig**.
4. Geben Sie den Code für die Startseite ein.
5. **Speichern** Sie die Einstellungen.<br /> → Die Template-Anpassungen werden nach der nächsten **Plugin-Bereitstellung** verfügbar.

##### Eigene Startseite aktivieren:

1. Öffnen Sie das Menü **Plugins » Plugin-Übersicht**.<br /> → Die Plugin-Übersicht wird geöffnet.
2. Klicken Sie auf **MandasTheme**.<br /> → Das Plugin wird geöffnet.
3. Klicken Sie im Verzeichnisbaum auf **Konfiguration**.
4. Aktivieren Sie **Homepage** unter **Override partials and templates**.
5. **Speichern** Sie die Einstellungen.<br /> → Die Startseite wird angezeigt.

## Lizenz

Das gesamte Projekt unterliegt der GNU AFFERO GENERAL PUBLIC LICENSE – weitere Informationen finden Sie in der [LICENSE](https://github.com/plentymarkets/plugin-ceres-vanilla/blob/master/LICENSE).
