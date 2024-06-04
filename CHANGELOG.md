# CHANGELOG



## v0.1.1 (2024-06-04)

### Fix

* fix: release yml ([`e1c6994`](https://github.com/Alchez/shipstation-client/commit/e1c69943e9f2f6ef9c1668360eb2765d734164aa))


## v0.1.0 (2024-06-04)

### Build

* build: builds added based on PR#7 ([`cb9a3fa`](https://github.com/Alchez/shipstation-client/commit/cb9a3fa3bf650d38e35e2c532b3fbe2ca3b9e43e))

* build: update wheel and tarball ([`7d5beaf`](https://github.com/Alchez/shipstation-client/commit/7d5beafeaa37fbe6fbc4f4f33d73948104f2ed01))

* build: add builds ([`e29df76`](https://github.com/Alchez/shipstation-client/commit/e29df76c1e12bf1311671bca5114ac5f22cd29de))

### Chore

* chore: black pagination test ([`e032d85`](https://github.com/Alchez/shipstation-client/commit/e032d85b6c83c252f083c047c063428d7a5ee05b))

* chore: clean up typing on pagination refactor ([`d8aa053`](https://github.com/Alchez/shipstation-client/commit/d8aa0530b43ef27d790ac7df03b253d61f6fcc6f))

* chore: clean up typing on pagination refactor ([`3c5292e`](https://github.com/Alchez/shipstation-client/commit/3c5292ef3b667c0999a961f6635229a10d872be6))

* chore: add type hints and mypy ignore statements ([`c084d5b`](https://github.com/Alchez/shipstation-client/commit/c084d5baf2648d57dc3f3462d92e8fd855c6eda6))

* chore: remove cookie cutter config file ([`6657d87`](https://github.com/Alchez/shipstation-client/commit/6657d87c90e64faa0cca36847a6880ba380240b1))

### Documentation

* docs: spelling ([`a1287cd`](https://github.com/Alchez/shipstation-client/commit/a1287cd2b124b5f7d8ae8212c29a0a47f3028925))

### Feature

* feat: add publishing to PyPI step ([`61dc445`](https://github.com/Alchez/shipstation-client/commit/61dc44562325447d122baff7dc352bb81c02ccce))

* feat: upgrade client to Python 3.10 (#13)

* feat: upgrade client to Python 3.10

* test: update tests

* ci: add pytest GHA

* fix: update models and constants

* ci: fix typing

* ci: fix GHA

* ci: update makefiles

* test: fix mypy errors

* docs: update readme

* fix: update configs

* feat: update API client

* ci: remove circleCI config

* style: fix styling

---------

Co-authored-by: Rohan Bansal &lt;rohan@agritheory.dev&gt; ([`b3e2cbd`](https://github.com/Alchez/shipstation-client/commit/b3e2cbdafd8842ec100aea365968cf1c51b4d942))

* feat: update wheel, correct models ([`ac65ffd`](https://github.com/Alchez/shipstation-client/commit/ac65ffd96fec35f19eae0d3d3c8261a3d4f10dc0))

* feat: add model for order item and order options ([`7961640`](https://github.com/Alchez/shipstation-client/commit/79616405b1eff3b8ae1db5e93c2483e9e5f92d91))

* feat: allow passing params in Pagination ([`5d44687`](https://github.com/Alchez/shipstation-client/commit/5d44687a35943a63d850e11ed69732c8b39dee92))

* feat: add pagination functionality and tests (#3)

* feat: add pagination functionality and tests

* chore: clean up typing on pagination refactor ([`76ea5fa`](https://github.com/Alchez/shipstation-client/commit/76ea5fa7b1cdf43cb39b37a8aa42c58c0325c6ca))

* feat: add pagination functionality and tests ([`6ea14f5`](https://github.com/Alchez/shipstation-client/commit/6ea14f5c6ad8830685094799cba3b982239180b5))

### Fix

* fix: black new files ([`62b7292`](https://github.com/Alchez/shipstation-client/commit/62b729288c31ade546e3c50c66dfab7ed115c15c))

* fix: throw Shipstation errors to the user (#9)

* fix: throw Shipstation errors to the user

* test: add tests for 500 responses

* fix: move error handling to HTTP methods

* fix: function names

* fix: add a comment for modulo response mock ([`4124aa2`](https://github.com/Alchez/shipstation-client/commit/4124aa24cc1691edc9a7cde3e9586b4890141ce0))

* fix: fix create order unpacking bug ([`4e39dcc`](https://github.com/Alchez/shipstation-client/commit/4e39dcc2995c8906b7c1a7178dcf12278b684834))

* fix: re-apply query params before getting next page (#7)

* fix: re-apply query params before getting next page

* fix: default params value

* test: add test to ensure all params are passed on paginated results

Co-authored-by: Tyler &lt;tyler@agritheory.com&gt; ([`df43a25`](https://github.com/Alchez/shipstation-client/commit/df43a252d62691c1ce18daff93ff179a2f4ea1d1))

* fix: allow test label generation for orders (#6) ([`4db7f52`](https://github.com/Alchez/shipstation-client/commit/4db7f52efc3db031548f0108694ea70783e9cf4f))

* fix: handle empty paginated response ([`9c2d31a`](https://github.com/Alchez/shipstation-client/commit/9c2d31adae51cbdfcfedee7ce1e03f3c7a034e33))

* fix: tag ids in Order come in as a list of integers ([`ecd5b27`](https://github.com/Alchez/shipstation-client/commit/ecd5b274cab262ebc1c1dc6aa87a50698627f0a9))

* fix: get attrs faused false passing tests ([`66427f0`](https://github.com/Alchez/shipstation-client/commit/66427f00c13a4e32ada90158cb59bd5867077d89))

### Unknown

* Merge branch &#39;testing&#39; ([`127cce7`](https://github.com/Alchez/shipstation-client/commit/127cce772ea12af3d6d7724a73f9a4a725afeb7b))

* Testing (#4)

* feat: add pagination functionality and tests

* chore: clean up typing on pagination refactor

* chore: clean up typing on pagination refactor ([`0e32c02`](https://github.com/Alchez/shipstation-client/commit/0e32c0227aefc1ffb3c77cce354a30d0935a6f62))

* Merge pull request #2 from agritheory/testing

tests: adding tests for fetching options ([`cd45b56`](https://github.com/Alchez/shipstation-client/commit/cd45b56cc6db8f50fb32e9f9656228e98900eea6))

* pack: add wheel to repo, make build commands work ([`3c587c0`](https://github.com/Alchez/shipstation-client/commit/3c587c0ed10fdbb2a2fac6a970fa20ce0a117f93))

* tests: refactor type checking to pytest-mypy ([`af4919f`](https://github.com/Alchez/shipstation-client/commit/af4919f68d21b83fabbe447faf64cb39b627132a))

* tests: circleci settings ([`8539d8a`](https://github.com/Alchez/shipstation-client/commit/8539d8a8f626a0fb90195975646ee7914042da6f))

* tests: circleci settings ([`af4e033`](https://github.com/Alchez/shipstation-client/commit/af4e0336385adcee2e4fd4c64d6ead0f88b57d5e))

* tests: adding tests for fetching options ([`c668dde`](https://github.com/Alchez/shipstation-client/commit/c668ddea9ce46f4175ceeb4ee7e36ad428e93fff))

* Merge pull request #1 from agritheory/circleci-project-setup

Add .circleci/config.yml ([`076c932`](https://github.com/Alchez/shipstation-client/commit/076c932f30ef6fa72b61c89abd2a703b1d0a2373))

* Add .circleci/config.yml ([`5c3d7ea`](https://github.com/Alchez/shipstation-client/commit/5c3d7ea3d4d6a0a44aaf73205aceb6ab52ba7a9e))

* init: move from gitlab ([`831b849`](https://github.com/Alchez/shipstation-client/commit/831b849b14110a3dfe6303d16507e267b9ed076f))
