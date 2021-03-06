# CHANGELOG - ceph

## 2.1.1 / 2020-06-29

* [Fixed] Fix template specs typos. See [#6912](https://github.com/DataDog/integrations-core/pull/6912).

## 2.1.0 / 2020-05-17

* [Added] Allow optional dependency installation for all checks. See [#6589](https://github.com/DataDog/integrations-core/pull/6589).
* [Added] Add ceph config spec. See [#6563](https://github.com/DataDog/integrations-core/pull/6563).
* [Fixed] Capture type errors as well as key errors for osd perf metrics. See [#6381](https://github.com/DataDog/integrations-core/pull/6381).

## 2.0.0 / 2020-04-04

* [Fixed] Fix response handling. See [#6152](https://github.com/DataDog/integrations-core/pull/6152).
* [Fixed] Update deprecated imports. See [#6088](https://github.com/DataDog/integrations-core/pull/6088).
* [Fixed] Remove logs sourcecategory. See [#6121](https://github.com/DataDog/integrations-core/pull/6121).
* [Changed] Account for "osdstats" key in newer versions. See [#5855](https://github.com/DataDog/integrations-core/pull/5855).

## 1.8.0 / 2019-10-11

* [Added] Adhere to logging call convention. See [#4738](https://github.com/DataDog/integrations-core/pull/4738).

## 1.7.0 / 2019-08-24

* [Added] Remove unused version command. See [#4249](https://github.com/DataDog/integrations-core/pull/4249).

## 1.6.0 / 2019-07-09

* [Added] Add log setup and configuration. See [#3960](https://github.com/DataDog/integrations-core/pull/3960).

## 1.5.1 / 2019-06-05

* [Fixed] Fix version discovery. See [#3874](https://github.com/DataDog/integrations-core/pull/3874).

## 1.5.0 / 2019-05-14

* [Added] Adhere to code style. See [#3488](https://github.com/DataDog/integrations-core/pull/3488).

## 1.4.0 / 2019-02-18

* [Fixed] Resolve flake8 issues. See [#3060](https://github.com/DataDog/integrations-core/pull/3060).
* [Added] Support Python 3. See [#2837](https://github.com/DataDog/integrations-core/pull/2837).

## 1.3.2 / 2018-11-30

* [Fixed] Use raw string literals when \ is present. See [#2465][1].

## 1.3.1 / 2018-09-04

* [Fixed] Add data files to the wheel package. See [#1727][2].

## 1.3.0 / 2018-03-23

* [FEATURE] Add custom tag support for service checks.

## 1.2.0 / 2018-01-10

* [FEATURE] Update the check to make it work with ceph luminous. See [#926][3]
* [FEATURE] Allow sending specific service checks using to the more detailed luminous health checks. See [#926][3]
* [IMPROVEMENT] Add metric for number of active monitors. See [#956][4]

## 1.1.0 / 2017-07-18

* [FEATURE] Add option to define the cluster name. See [#438][5], thanks [@borisroman][6]

## 1.0.0 / 2017-02-22

* [FEATURE] adds ceph integration.

<!--- The following link definition list is generated by PimpMyChangelog --->
[1]: https://github.com/DataDog/integrations-core/pull/2465
[2]: https://github.com/DataDog/integrations-core/pull/1727
[3]: https://github.com/DataDog/integrations-core/issues/956
[4]: 
[5]: https://github.com/DataDog/integrations-core/issues/438
[6]: https://github.com/borisroman
