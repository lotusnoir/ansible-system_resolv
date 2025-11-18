# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.1.0](https://github.com/lotusnoir/ansible-system_resolv/compare/3.0.0...3.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`9b9f1e8`](https://github.com/lotusnoir/ansible-system_resolv/commit/9b9f1e806c4999f6852defa2989a147780736076)
- add oraclelinux10 support + lint and core fixes [`f080200`](https://github.com/lotusnoir/ansible-system_resolv/commit/f08020078e8ffa3475db4480c3899997aee8be7e)

## [3.0.0](https://github.com/lotusnoir/ansible-system_resolv/compare/2.0.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`ec21374`](https://github.com/lotusnoir/ansible-system_resolv/commit/ec213743a40e2a270c1b237b195e31779a864d61)
- update core, molecule + gitlab-ci [`2ceb8fb`](https://github.com/lotusnoir/ansible-system_resolv/commit/2ceb8fb65fbbc9cf3240daf45b873212270a4dda)
- fix lint [`42977fb`](https://github.com/lotusnoir/ansible-system_resolv/commit/42977fbefa863cfa02ddb5358addabd31c1b039c)
- fix molecule paralelism and little updates [`0ab2891`](https://github.com/lotusnoir/ansible-system_resolv/commit/0ab2891791632313b058d44df0980df6400d7552)
- add support for ubuntu24 [`5c5e561`](https://github.com/lotusnoir/ansible-system_resolv/commit/5c5e561c7890f79ba17843a74a743ad030930743)
- add version on molecule play image to maintain support on old release [`25a1b8b`](https://github.com/lotusnoir/ansible-system_resolv/commit/25a1b8b355df136d65115972de0d8362e9b3905e)
- update molecule [`4c69164`](https://github.com/lotusnoir/ansible-system_resolv/commit/4c69164649ffc589761bb0f9393b2edc5f5bb063)
- change tasks order and add Networkmanager disable dns [`7265d0e`](https://github.com/lotusnoir/ansible-system_resolv/commit/7265d0e85d53664c0e11907b4c61dbec5627fd7e)
- add redhat 9 to default supported distrib [`eadfba8`](https://github.com/lotusnoir/ansible-system_resolv/commit/eadfba8638f4e233e9d3056d63ebaf1a94c31da6)
- add redhat 8 to default supported distrib [`7492efd`](https://github.com/lotusnoir/ansible-system_resolv/commit/7492efd640786eb45a374357a658a3cc8df582e2)

## [2.0.0](https://github.com/lotusnoir/ansible-system_resolv/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`51d1505`](https://github.com/lotusnoir/ansible-system_resolv/commit/51d15059f3cb33469334b3cc4dde5623347211eb)
- update readme + precommit + include vars [`09058ae`](https://github.com/lotusnoir/ansible-system_resolv/commit/09058ae23c7accc43f750f4a4d0429fe0ecdf3c6)
- change import tasks to include in order to support facts on name [`9012076`](https://github.com/lotusnoir/ansible-system_resolv/commit/9012076f2cb424a6147ad8c73f8fbe4164e1f7c7)

## [1.1.0](https://github.com/lotusnoir/ansible-system_resolv/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`4dc054f`](https://github.com/lotusnoir/ansible-system_resolv/commit/4dc054f287f8975c58c3fcca925a04c54759e064)

## [1.0.0](https://github.com/lotusnoir/ansible-system_resolv/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`a93126b`](https://github.com/lotusnoir/ansible-system_resolv/commit/a93126b2781d81418ae3fc78959230fdb2e01b20)
- add precommit for lint [`5c8724a`](https://github.com/lotusnoir/ansible-system_resolv/commit/5c8724afcdf8db4e4ed5a8493b63fec24fedcdbb)
- fix checks [`0a8a2d9`](https://github.com/lotusnoir/ansible-system_resolv/commit/0a8a2d9ee1015b1626de613f33133ecb226ecd6c)
- add new molecule all scenario [`9c91ae1`](https://github.com/lotusnoir/ansible-system_resolv/commit/9c91ae1ad37f925c827ce74bf021eb5bcbaf35a4)
- update readme [`bf534ee`](https://github.com/lotusnoir/ansible-system_resolv/commit/bf534eee4eed04cefd0eb8cb91181ad3e5d6e8b6)
- split distro for molecule tests on ci [`572a951`](https://github.com/lotusnoir/ansible-system_resolv/commit/572a9511e5292ce85a8b3e0370cac79aeae1fa48)
- update checks and Readme [`68d9b08`](https://github.com/lotusnoir/ansible-system_resolv/commit/68d9b08878167c879dcd2dbc2ecbe2dac108b9f5)
- remove verify [`1a0c288`](https://github.com/lotusnoir/ansible-system_resolv/commit/1a0c2885a7728413a7df772ec2e2282f967a92ba)
- add molecule fix for ora9 [`41f085d`](https://github.com/lotusnoir/ansible-system_resolv/commit/41f085ddd010af1da70f5f8ef0da38bfa139a236)
- update checks [`86fc60d`](https://github.com/lotusnoir/ansible-system_resolv/commit/86fc60d0bccda645f9d66c438d5ae4633ffb12d3)

## [0.3.0](https://github.com/lotusnoir/ansible-system_resolv/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`9a43d87`](https://github.com/lotusnoir/ansible-system_resolv/commit/9a43d87a20a31a8487ce00f94adb54981e52e999)
- minor: add oracleLinux support + little fixes [`6030624`](https://github.com/lotusnoir/ansible-system_resolv/commit/6030624ef6804d6218def2af1e909a0fc9c73b46)

## [0.2.0](https://github.com/lotusnoir/ansible-system_resolv/compare/0.1.0...0.2.0) - 2022-06-02

### Commits

- minor: add ubuntu 22 molecule test + fix lint [`5a3b4d8`](https://github.com/lotusnoir/ansible-system_resolv/commit/5a3b4d800cf74e2598deba2e08eb8b65331c73a2)

## 0.1.0 - 2021-11-18

### Commits

- fix: Changes on README + molecule container names [`01fd862`](https://github.com/lotusnoir/ansible-system_resolv/commit/01fd8625e5f75bd662ee3ba3854b11c13544eb60)
- fix: add role name on molecule container names to avoid concurrent conflict on runners [`0ab7bad`](https://github.com/lotusnoir/ansible-system_resolv/commit/0ab7bad141034130caac1891ae694ad9792f57b8)
- fix: licence type [`ae7d2ec`](https://github.com/lotusnoir/ansible-system_resolv/commit/ae7d2ec6cc0d57c0a83fe0843da6776f8e577206)
- minor: add changelog + automatic files checks [`6a2f9fc`](https://github.com/lotusnoir/ansible-system_resolv/commit/6a2f9fca9670257ea7346648bf62ad1f4308a092)
- fix for molecule [`53e5b30`](https://github.com/lotusnoir/ansible-system_resolv/commit/53e5b30a85a560748de9499677e3d9af64bb7e09)
