# UNCode - Online Python Tutor - C/C++ backend

[![License](https://img.shields.io/github/license/JuezUN/opt-cpp-backend?style=plastic)][license_url]
[![Gitter](https://badges.gitter.im/uncode-unal/community.svg)][gitter_url]
[![CLA assistant](https://cla-assistant.io/readme/badge/JuezUN/opt-cpp-backend)][cla_url]
[![Contributors](https://img.shields.io/github/contributors/JuezUN/opt-cpp-backend?style=plastic)][contributors_url]

This is the repository for the C/C++ backend for [Online Python Tutor][python_tutor_repo_url]. We have forked this
 repository to add some necessary modifications for our purposes, and correctly provide the python tutor service.
 
The code of this repository is built using Docker stored in docker hub: [unjudge/opt-cpp-backend][unjudge/opt-cpp-backend],
 which at the same time is used by a linux service called *cokapi*, see how we deploy this service [cokapi service][cokapi_url],
 also see how Python tutor uses this deployed service in <https://github.com/JuezUN/OnlinePythonTutor/tree/master/v4-cokapi>.
 The cokapi service is currently deployed in the port `4000`.

## Built with

- C
- (basic Linux C compiler toolchain)
- binutils-dev
- This code is based on a hacked version of Valgrind 3.11.0, downloaded from: <http://www.valgrind.org/downloads/valgrind-3.11.0.tar.bz2>

## Documentation

For additional documentation, please refer to the [Wiki][uncode_wiki_url].

## Roadmap

See the [UNCode GitHub Project][project_url] for a list of proposed features, known issues and how they are being 
tackled.

## Contributing

Go to [CONTRIBUTING][contributing_url] to see the guidelines and how to start contributing to UNCode.

## License

Distributed under the GNU License. See [LICENSE][license_url] for more information.

## Contact

In case of technical questions, please use the [gitter communication channel][gitter_url].

In case you want to host your course on our deployment, email us on: <uncode_fibog@unal.edu.co>

UNCode: <https://uncode.unal.edu.co>

Project page: <https://juezun.github.io/UNCode_page/>


[license_url]: https://github.com/JuezUN/opt-cpp-backend/blob/master/LICENSE
[contributing_url]: https://github.com/JuezUN/opt-cpp-backend/blob/master/CONTRIBUTING.md
[project_url]: https://github.com/orgs/JuezUN/projects/3
[python_tutor_repo_url]: https://github.com/JuezUN/OnlinePythonTutor
[uncode_wiki_url]: https://github.com/JuezUN/INGInious/wiki
[gitter_url]:https://gitter.im/uncode-unal/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge
[cla_url]: https://cla-assistant.io/JuezUN/opt-cpp-backend
[contributors_url]: https://github.com/JuezUN/opt=cpp-backend/graphs/contributors
[unjudge/opt-cpp-backend]: https://hub.docker.com/r/unjudge/opt-cpp-backend
[cokapi_url]: https://github.com/JuezUN/Deployment/blob/master/deployment_scripts/deploy_cokapi_service.sh