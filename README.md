# Embargoed - List of supported platforms

List of all language-specific versions of `embargoed`, software to block to block all requests from Russia to any website and display a pro-Ukraine message instead πΊπ¦

This is the message that gets displayed:

<p align="center">
  <img src="https://github.com/rameerez/embargoed/blob/main/public/embargoed-message.jpg?raw=true" alt="Embargoed message displayed to Russian visitors" width="400"/>
</p>


Contributors are building versions of `embargoed` for several programming languages and frameworks. If you don't see your platform here please consider building a port and opening a pull request to add it to the list! Instructions below.

# Find your version here

 - π **Ruby on Rails**: `embargoed` gem [[π install instructions & repo here](https://github.com/rameerez/embargoed)] by [@rameerez](https://twitter.com/rameerez)


 - π **Python Django**: `django-embargoed` pip package [[π install instructions & repo here](https://github.com/ronaldlangeveld/django-embargoed)] by [@ronaldlangeveld](https://twitter.com/ronaldlangeveld)


 - π¨βπ€ **PHP Composer**: `gdelacc/embargoed-composer` Composer package [[π install instructions & repo here](https://github.com/gdelacc/embargoed-composer)] by [@gdelacc](https://github.com/gdelacc)


 - π **WordPress Plugin**: `wp-embargoed` Wordpress plugin [[π install instructions & repo here](https://github.com/pretzelhands/wp-embargoed)] by [@pretzelhds](https://twitter.com/pretzelhds)


 - π¦ **Laravel Package:** `laravel-embargoed` Laravel package  [[π install instructions & repo here](https://github.com/pretzelhands/laravel-embargoed)] by [@pretzelhds](https://twitter.com/pretzelhds)


 - π© **Cloudflare Worker:** `embargoed-cloudflare-worker` Worker set up instructions  [[π install instructions & repo here](https://github.com/JulienMelissas/embargoed-cloudflare-worker)] by [@julienmelissas](https://twitter.com/julienmelissas)


 - π¦ **Express.js:** `express-embargoed` middleware package [[π install instructions & repo here](https://github.com/cba85/express-embargoed)] by [@cba85](https://github.com/cba85)


 - πΌ **ASP.NET:** `Embargoed.AspNetCore` Nuget package [[π install instructions & repo here](https://github.com/TobbenTM/Embargoed.Net)] by [@tobbentm](https://github.com/TobbenTM)


 - π **Rust/Rocket**: `embargoed` library [[π install instructions & repo here](https://github.com/lily-mosquitoes/embargoed-rust)] by [@lily-mosquitoes](https://github.com/lily-mosquitoes)


# How to contribute

If you want to make a port to implement a version of Embargoed in any platform that's not listed above, please go ahead!

The HTML to display can be found at [`/embargoed.html`](embargoed.html)

You might need a **GeoIP database** that you're allowed to distribute along with your package. Here's the one most ports use: [`geoacumen/geoacumen-country`](https://github.com/geoacumen/geoacumen-country).

The `mmdb` can be dowloaded from [here](https://github.com/geoacumen/geoacumen-country/blob/master/Geoacumen-Country.mmdb). It's under an Apache2 license, so you're free to redistribute it along with your package as long as you include its Apache2 license along with it.

When you've finished implementing your port, please make it available as a public GitHub repo under a permissive Open Source license, like the MIT license.

Then just make a Pull Request to this list to get it added. I'll merge it ASAP.
