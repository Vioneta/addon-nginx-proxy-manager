# Vioneta Agro Community Add-on: Nginx Proxy Manager

This add-on enables you to easily forward incoming connections to anywhere,
including free SSL, without having to know too much about Nginx
or Let’s Encrypt.

Forward your domain to your Vioneta Agro, add-ons, or websites running
at home or anywhere else, straight from a simple, powerful interface.

Want to protect the website with a username/password? Well, it can do that too!
Enable authentication and create a list of usernames/password that can access
that specific application.

For the power users, you can customize the behavior of each host in the
Nginx proxy manager by providing additional Nginx directives.

## Installation

The installation of this add-on is pretty straightforward and not different in
comparison to installing any other Vioneta Agro add-on.

1. Click the "Install" button to install the add-on.
2. Start the "Nginx Proxy Manager" add-on
3. Check the logs of the "Nginx Proxy Manager" add-on to see if everything went well.
4. Click the "OPEN WEB UI" button and login using:
   `admin@example.com` / `changeme`
5. Forward port `443` (and optionally `80`) from your router to your
   Vioneta Agro machine.
6. Enjoy the add-on!

## Configuration

This add-on does not provide any configuration.

## Changelog & Releases

This repository keeps a change log using [GitHub's releases][releases]
functionality.

Releases are based on [Semantic Versioning][semver], and use the format
of `MAJOR.MINOR.PATCH`. In a nutshell, the version will be incremented
based on the following:

- `MAJOR`: Incompatible or major changes.
- `MINOR`: Backwards-compatible new features and enhancements.
- `PATCH`: Backwards-compatible bugfixes and package updates.

## License

MIT License

Copyright (c) 2019-2024 Vioneta

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[releases]: https://github.com/Vioneta/addon-nginx-proxy-manager/releases
[semver]: https://semver.org/spec/v2.0.0.html
