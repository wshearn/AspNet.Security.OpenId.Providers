AspNet.Security.OpenId.Providers
==================================

__AspNet.Security.OpenId.Providers__ is a __collection of security middleware__ that you can use in your __ASP.NET 5__ application to support OpenID 2.0 authentication providers like __[Steam](http://steampowered.com/)__, __[Wargaming](http://wargaming.net/)__ or __[Orange](http://www.orange.fr/)__. It is directly inspired by __[Jerrie Pelser](https://github.com/jerriep)__'s initiative, __[Owin.Security.Providers](https://github.com/RockstarLabs/OwinOAuthProviders)__.

__The latest nightly builds can be found here__: __[https://www.myget.org/F/aspnet-contrib](https://www.myget.org/F/aspnet-contrib)__

[![Build status](https://ci.appveyor.com/api/projects/status/tc9n807mwi4sr5jd/branch/dev?svg=true)](https://ci.appveyor.com/project/aspnet-contrib/aspnet-security-openid-providers/branch/dev)
[![Build status](https://travis-ci.org/aspnet-contrib/AspNet.Security.OpenId.Providers.svg?branch=dev)](https://travis-ci.org/aspnet-contrib/AspNet.Security.OpenId.Providers)

## Dependencies

The __dev__ branch relies on the latest version of __DNX__ and __ASP.NET 5__, that can be found on __MyGet__: __[https://www.myget.org/gallery/aspnetvnext](https://www.myget.org/gallery/aspnetvnext)__.

Make sure to always run the latest __DNX__ version and the corresponding __ASP.NET 5__ packages by running `dnvm upgrade -u` and `dnu restore`.

## Getting started

__Adding external authentication to your application is a breeze__ and just requires a few lines in your `Startup` class:

    app.UseSteamAuthentication();

See [https://github.com/aspnet-contrib/AspNet.Security.OpenId.Providers/tree/dev/samples/Mvc.Client](https://github.com/aspnet-contrib/AspNet.Security.OpenId.Providers/tree/dev/samples/Mvc.Client) for a complete sample __using MVC 6 and supporting multiple external providers__.

## Contributors

__AspNet.Security.OpenId.Providers__ is actively maintained by __[Kévin Chalet](https://github.com/PinpointTownes)__ ([@PinpointTownes](https://twitter.com/PinpointTownes)) and __[Jerrie Pelser](https://github.com/jerriep)__ ([@jerriepelser](https://twitter.com/jerriepelser)). Contributions are welcome and can be submitted using pull requests.

## License

This project is licensed under the __Apache License__. This means that you can use, modify and distribute it freely. See [http://www.apache.org/licenses/LICENSE-2.0.html](http://www.apache.org/licenses/LICENSE-2.0.html) for more details.