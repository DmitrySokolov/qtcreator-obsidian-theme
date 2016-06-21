# Obsidian theme for Qt Creator

Tested for Qt Creator 4.0+

## How to install

1. Create the `dark_copy.xml` file on the path `%APPDATA%\QtProject\qtcreator\styles`.
2. Copy contents into the `dark_copy.xml`.
3. Run Qt Creator, open Tools -> Options dialog, select Environment section, Interface tab.
4. Change Theme to 'Dark', press OK, and restart Qt Creator.
5. Open Tools -> Options dialog, select Text Editor section, Font & Colors tab.
6. Change Color Scheme to 'Dark (my)', press OK.

## `dark_copy.xml` contents

```xml
<?xml version="1.0" encoding="UTF-8"?>
<style-scheme version="1.0" name="Dark (my)">
  <style name="Text" foreground="#e0e2e4" background="#232a2d"/>
  <style name="Link" foreground="#0055ff"/>
  <style name="Selection" background="#404e51"/>
  <style name="LineNumber" foreground="#81969a" background="#2b3337"/>
  <style name="SearchResult" background="#a0a0c8"/>
  <style name="SearchScope" background="#222200"/>
  <style name="Parentheses" foreground="#f3db2e"/>
  <style name="ParenthesesMismatch" background="#800080"/>
  <style name="CurrentLine" background="#2f393c"/>
  <style name="CurrentLineNumber" foreground="#aaaaaa" bold="true"/>
  <style name="Occurrences" background="#5e7178"/>
  <style name="Occurrences.Unused" underlineColor="#808000" underlineStyle="SingleUnderline"/>
  <style name="Occurrences.Rename" foreground="#ffaaaa" background="#553636"/>
  <style name="Number" foreground="#ffcd22"/>
  <style name="String" foreground="#ec7600"/>
  <style name="Type" foreground="#668cb0"/>
  <style name="Local"/>
  <style name="Field" foreground="#5555ff"/>
  <style name="Static" foreground="#55ff55" italic="true"/>
  <style name="VirtualMethod" italic="true"/>
  <style name="Function" foreground="#aaaaff"/>
  <style name="Keyword" foreground="#93c763"/>
  <style name="PrimitiveType" foreground="#668cb0" italic="true"/>
  <style name="Operator" foreground="#818e96"/>
  <style name="Preprocessor" foreground="#a07793"/>
  <style name="Label" foreground="#ffff55"/>
  <style name="Comment" foreground="#66747a"/>
  <style name="Doxygen.Comment" foreground="#66747a"/>
  <style name="Doxygen.Tag" foreground="#00a0a0"/>
  <style name="VisualWhitespace" foreground="#313a3c"/>
  <style name="QmlLocalId" italic="true"/>
  <style name="QmlExternalId" foreground="#aaaaff" italic="true"/>
  <style name="QmlTypeId" foreground="#55ff55"/>
  <style name="QmlRootObjectProperty" italic="true"/>
  <style name="QmlScopeObjectProperty" italic="true"/>
  <style name="QmlExternalObjectProperty" foreground="#aaaaff" italic="true"/>
  <style name="JsScopeVar" foreground="#8888ff" italic="true"/>
  <style name="JsImportVar" foreground="#8888ff" italic="true"/>
  <style name="JsGlobalVar" foreground="#8888ff" italic="true"/>
  <style name="QmlStateName" italic="true"/>
  <style name="Binding" foreground="#ff5555"/>
  <style name="DisabledCode" foreground="#777777" background="#232a2d"/>
  <style name="AddedLine" foreground="#55ffff"/>
  <style name="RemovedLine" foreground="#ff5555"/>
  <style name="DiffFile" foreground="#55ff55"/>
  <style name="DiffLocation" foreground="#ffff55"/>
  <style name="DiffFileLine" foreground="#000000" background="#d7d700"/>
  <style name="DiffContextLine" foreground="#000000" background="#8aaab6"/>
  <style name="DiffSourceLine" background="#8c2d2d"/>
  <style name="DiffSourceChar" foreground="#000000" background="#c34141"/>
  <style name="DiffDestLine" background="#2d8c2d"/>
  <style name="DiffDestChar" foreground="#000000" background="#41c341"/>
  <style name="LogChangeLine" foreground="#808000"/>
  <style name="Warning" underlineColor="#ffbe00" underlineStyle="SingleUnderline"/>
  <style name="WarningContext" underlineColor="#ffbe00" underlineStyle="DotLine"/>
  <style name="Error" underlineColor="#ff0000" underlineStyle="SingleUnderline"/>
  <style name="ErrorContext" underlineColor="#ff0000" underlineStyle="DotLine"/>
</style-scheme>
```
