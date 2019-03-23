[![Build status](https://ci.appveyor.com/api/projects/status/8x5r18mcakthpwhs?svg=true)](https://ci.appveyor.com/project/bergren2/xur)

# Xur

This is the Nine.

## What is this?

Xur is an opinionated web app for launching containerized utilities.

- Supports container authentication against Xur
- User role management
- Lightweight configuration

## Why?

Sometimes it doesn't make sense to build tooling directly into the applications
they support. For example:

- Legacy applications that don't easily support in-app tooling
- Tools and dashboards that need to span several applications at your company
- Tools that don't necessarily support an application
- MVP, proof-of-concept tools and apps

## Development

    $ dotnet run --project src/Xur.csproj

Then go to https://localhost:5001/.

## License

See LICENSE for details.
