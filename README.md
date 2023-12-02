# node-gyp

[node-gyp](https://www.npmjs.com/package/node-gyp) installed globally over the official [NodeJS image](https://hub.docker.com/_/node)

![version](https://img.shields.io/docker/v/daotl/node-gyp?sort=semver)
![build status](https://github.com/daotl/node-gyp-docker/actions/workflows/default.yml/badge.svg)

```
THIS DOCKER IMAGE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE MAINTAINERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE DOCKER IMAGE OR THE USE OR OTHER DEALINGS IN THE DOCKER IMAGE.
```

## Quick reference

#### Tags & Dockerfiles

* [latest-node-20](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile)
* [latest-node-20-root](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.root) (run as `root` user)
* [latest-node-20-git](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.git) (with `git` command executable available)
* [latest-node-20-root-git](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.root-git) (run as `root` user, with `git` command executable available)
* [latest-node-20-root-git-pnpm-turborepo](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.root-git-pnpm-turborepo) (run as `root` user, with `git` command executable available, with global installed `pnpm` and `libc6-compat` package required by TurboRepo)

* [latest-node-19](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile)
* [latest-node-19-root](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.root) (run as `root` user)
* [latest-node-19-git](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.git) (with `git` command executable available)
* [latest-node-19-root-git](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.root-git) (run as `root` user, with `git` command executable available)
* [latest-node-19-root-git-pnpm-turborepo](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.root-git-pnpm-turborepo) (run as `root` user, with `git` command executable available, with global installed `pnpm` and `libc6-compat` package required by TurboRepo)

* [latest-node-18](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile)
* [latest-node-18-root](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.root) (run as `root` user)
* [latest-node-18-git](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.git) (with `git` command executable available)
* [latest-node-18-root-git](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.root-git) (run as `root` user, with `git` command executable available)
* [latest-node-18-root-git-pnpm-turborepo](https://github.com/daotl/node-gyp-docker/blob/main/Dockerfile.root-git-pnpm-turborepo) (run as `root` user, with `git` command executable available, with global installed `pnpm` and `libc6-compat` package required by TurboRepo)

#### Where to find more versions and tags
[the Tags page on Docker Hub](https://hub.docker.com/r/daotl/node-gyp/tags)

#### Where to file issues
[the Issues page on Github](https://github.com/daotl/node-gyp-docker/issues)

## Image content

* g++
* make
* Node.js (from the base image)
* Python 3
* Yarn (from the base image)

Some tags also include:

* Git
* OpenSSH client
* pnpm
