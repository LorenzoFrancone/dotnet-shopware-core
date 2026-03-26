# Shopware Core

Shopware 6 API Client

## Compatibility

This library has been updated to support modern RestSharp versions (>= 113.x),
fixing runtime issues caused by deprecated APIs.

# Build

## Cake installieren oder aktualisieren

In der Powershell mit Administratorenrechten sollte das Cake Build Tool global installiert werden. Optional kann ein nuget Konfigurationsdatei übergeben werden.

```
dotnet tool install --global Cake.Tool --configfile C:\Tools\Nuget\NuGet.Config
```

Wenn Cake bereits installiert ist, kann nach Updates gesucht werden.

```
dotnet tool update --global Cake.Tool --configfile C:\Tools\Nuget\NuGet.Config
```

## Ausführen

```
dotnet-cake.exe build.cake --target="Build" --verbosity=normal
```
