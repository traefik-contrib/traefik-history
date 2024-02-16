# Traefik History

<p align="center">
    <picture>
    <img alt="logo" title="logo" width="400" src="./img/traefik.logo.png">
    </picture>
</p>

<!--
![timeline](./img/traefik-history.png)
-->

<!--
git tag -l --sort=-creatordate --format='%(creatordate:iso8601), %(authoremail), %(committeremail), %(refname:short), %(objectname)' > tags.csv
-->

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1year
    axisFormat %Y
    dateFormat YYYY-MM-DD HH:mm:ss
    section v1
        First Commit: crit, milestone, m1, 2015-08-28 18:09:22, 0d
        v1.0: after m1, 2016-09-22 15:00:43
        v1.0.0: crit, milestone, v10, 2016-07-06 01:09:33, 0d
        v1.1: after v10, 2016-12-15 11:13:30
        v1.1.0: crit, milestone, v11, 2016-11-17 22:41:11, 0d
        v1.2: after v11, 2017-04-13 21:09:40
        v1.2.0: crit, milestone, v12, 2017-03-21 10:37:24, 0d
        v1.3: after v12, 2017-09-07 22:04:03
        v1.3.0: crit, milestone, v13, 2017-05-31 10:11:16, 0d
        v1.4: after v13, 2018-01-02 12:54:03
        v1.4.0: crit, milestone, v14, 2017-10-16 18:42:03, 0d
        v1.5: after v14, 2018-03-15 14:26:03
        v1.5.0: crit, milestone, v15, 2018-01-23 17:34:04, 0d
        v1.6: after v15, 2018-08-20 14:46:02
        v1.6.0: crit, milestone, v16, 2018-04-30 23:20:05, 0d
        v1.7: after v16, 2021-12-10 17:54:05
        v1.7.0: crit, milestone, v17, 2018-09-24 11:44:03, 0d

    section v2
        v2.0: after v17, 2019-12-09 18:34:04
        v2.0.0: crit, milestone, v20, 2019-09-16 18:28:04, 0d
        v2.1: after v20, 2020-03-23 17:40:04
        v2.1.0: crit, milestone, v21, 2019-12-11 18:40:04, 0d
        v2.2: after v21, 2020-09-07 16:00:03
        v2.2.0: crit, milestone, v22, 2020-03-25 17:46:04, 0d
        v2.3: after v22, 2021-01-11 18:48:03
        v2.3.0: crit, milestone, v23, 2020-09-23 12:44:04, 0d
        v2.4: after v23, 2021-08-16 17:26:14
        v2.4.0: crit, milestone, v24, 2021-01-19 16:50:04, 0d
        v2.5: after v24, 2022-01-20 17:08:07
        v2.5.0: crit, milestone, v25, 2021-08-17 18:04:05, 0d
        v2.6: after v25, 2022-05-24 16:14:08
        v2.6.0: crit, milestone, v26, 2022-01-24 17:58:04, 0d
        v2.7: after v26, 2022-06-29 15:44:08
        v2.7.0: crit, milestone, v27, 2022-05-24 18:58:08, 0d
        v2.8: after v27, 2022-09-30 12:03:03
        v2.8.0: crit, milestone, v28, 2022-06-29 17:38:37, 0d
        v2.9: after v28, 2023-04-06 18:10:03
        v2.9.0: crit, milestone, v29, 2022-10-03 16:17:58, 0d
        v2.10: after v29, 2023-07-24 16:44:05
        v2.10.0: crit, milestone, v210, 2023-04-24 15:38:05, 0d

    section v3
        v3.0: after v210, 2023-07-26 00:00:00
```

## TOC

- [First Commit](#first-commit)
- [Public Announcement](#public-announcement)
- [v1.0-alpha](#v10-alpha-traefik)
- [v1.0](#v10-reblochon)
- [v1.1](#v11-camembert)
- [v1.2](#v12-morbier)
- [v1.3](#v13-raclette)
- [v1.4](#v14-roquefort)
- [v1.5](#v15-cancoillotte)
- [v1.6](#v16-tetedemoine)
- [v1.7](#v17-maroilles)
- [v2.0-alpha-beta](#v20-alphabeta-faisselle)
- [v2.0](#v20-montdor)
- [v2.1](#v21-cantal)
- [v2.2](#v22-chevrotin)
- [v2.3](#v23-picodon)
- [v2.4](#v24-livarot)
- [v2.5](#v25-brie)
- [v2.6](#v26-rocamadour)
- [v2.7](#v27-epoisses)
- [v2.8](#v28-vacherin)
- [v2.9](#v29-banon)
- [v2.10](#v210-saintmarcelin)
- [v3.0](#v30-beaufort)

## First Commit

- date: 2015-08-28 18:09:22 +0200
- SHA: 3680c8dc604ee9d0277973a55641f47fd257b564

## Public Announcement

- 2015-09-22
- [Hacker News](https://news.ycombinator.com/item?id=10257865)

## v1.0-alpha, traefik

| version     | date                      | fix |
|-------------|---------------------------|-----|
| v1.0        | 2015-09-22 23:29:45 +0200 |     |
| v1.0-alpha  |                           | 86  |
| v1.0.0-beta |                           | 71  |

## v1.0, reblochon

<p align="center">
    <picture>
    <img alt="v1.0-reblochon" title="v1.0-reblochon" width="400" src="./img/traefik-v1.0-reblochon.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v0
        First Commit: crit, milestone, m1, 2015-08-28 18:09:22, 0d
        v1.0.alpha.157: milestone, 2015-10-08 20:08:28, 0d
        v1.0.0-beta.212: milestone, 2016-03-09 23:55:26, 0d
    section v1.0
        v1.0.0-rc1: milestone, 2016-05-31 00:15:58, 0d
        v1.0.0-rc2: milestone, 2016-06-07 20:19:51, 0d
        v1.0.0-rc3: milestone, 2016-06-23 17:46:05, 0d
        v1.0.0: crit, milestone, 2016-07-06 01:09:33, 0d
        v1.0.1: milestone, 2016-07-19 16:54:16, 0d
        v1.0.2: milestone, 2016-08-02 19:20:43, 0d
        v1.0.3: milestone, 2016-09-22 15:00:43, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v1.0.0-rc1 | 2016-05-31 00:15:58 +0200 | 3   |
| v1.0.0     | 2016-07-06 01:09:33 +0200 | 3   |
| v1.0.3     | 2016-09-22 15:00:43 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v1.0/CHANGELOG.md)

## v1.1, camembert

<p align="center">
    <picture>
    <img alt="v1.1-camembert" title="v1.1-camembert" width="400" src="./img/traefik-v1.1-camembert.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v1.1
        v1.1.0-rc1: milestone, 2016-09-30 15:57:09, 0d
        v1.1.0-rc2: milestone, 2016-10-19 11:49:24, 0d
        v1.1.0-rc3: milestone, 2016-10-26 17:59:09, 0d
        v1.1.0-rc4: milestone, 2016-11-10 12:20:46, 0d
        v1.1.0: crit, milestone, 2016-11-17 22:41:11, 0d
        v1.1.1: milestone, 2016-11-29 16:25:52, 0d
        v1.1.2: milestone, 2016-12-15 11:13:30, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v1.1.0-rc1 | 2016-09-30 15:57:09 +0200 | 4   |
| v1.1.0     | 2016-11-17 22:41:11 +0100 | 2   |
| v1.1.2     | 2016-12-15 11:13:30 +0100 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v1.1/CHANGELOG.md)

## v1.2, morbier

<p align="center">
    <picture>
    <img alt="v1.2-morbier" title="v1.2-morbier" width="400" src="./img/traefik-v1.2-morbier.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v1.2
        v1.2.0-rc1: milestone, 2017-02-06 21:36:30, 0d
        v1.2.0-rc2: milestone, 2017-03-01 13:54:55, 0d
        v1.2.0: crit, milestone, 2017-03-21 10:37:24, 0d
        v1.2.1: milestone, 2017-03-27 17:08:32, 0d
        v1.2.2: milestone, 2017-04-11 22:05:04, 0d
        v1.2.3: milestone, 2017-04-13 21:09:40, 0d

```

Dates:

| version    | date                      | fix |
|------------|---------------------------|-----|
| v1.2.0-rc1 | 2017-02-06 21:36:30 +0100 | 2   |
| v1.2.0     | 2017-03-21 10:37:24 +0100 | 3   |
| v1.2.3     | 2017-04-13 21:09:40 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v1.2/CHANGELOG.md)

## v1.3, raclette

<p align="center">
    <picture>
    <img alt="v1.3-raclette" title="v1.3-raclette" width="400" src="./img/traefik-v1.3-raclette.svg">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v1.3
        v1.3.0-rc1: milestone, 2017-05-05 15:19:55, 0d
        v1.3.0-rc2: milestone, 2017-05-16 17:53:47, 0d
        v1.3.0-rc3: milestone, 2017-05-24 15:32:29, 0d
        v1.3.0: crit, milestone, 2017-05-31 10:11:16, 0d
        v1.3.1: milestone, 2017-06-16 12:53:26, 0d
        v1.3.2: milestone, 2017-06-29 17:40:11, 0d
        v1.3.3: milestone, 2017-07-06 17:53:35, 0d
        v1.3.4: milestone, 2017-07-27 17:24:19, 0d
        v1.3.5: milestone, 2017-08-01 17:43:37, 0d
        v1.3.6: milestone, 2017-08-22 09:52:02, 0d
        v1.3.7: milestone, 2017-08-25 17:08:02, 0d
        v1.3.8: milestone, 2017-09-07 22:04:03, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v1.3.0-rc1 | 2017-05-05 15:19:55 +0200 | 3   |
| v1.3.0     | 2017-05-31 10:11:16 -0700 | 8   |
| v1.3.8     | 2017-09-07 22:04:03 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v1.3/CHANGELOG.md)

## v1.4, roquefort

<p align="center">
    <picture>
    <img alt="v1.4-roquefort" title="v1.4-roquefort" width="400" src="./img/traefik-v1.4-roquefort.svg">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v1.4
        v1.4.0-rc1: milestone, 2017-08-29 09:37:47, 0d
        v1.4.0-rc2: milestone, 2017-09-08 20:50:04, 0d
        v1.4.0-rc3: milestone, 2017-09-18 18:20:03, 0d
        v1.4.0-rc4: milestone, 2017-10-02 16:00:03, 0d
        v1.4.0-rc5: milestone, 2017-10-10 15:50:03, 0d
        v1.4.0: crit, milestone, 2017-10-16 18:42:03, 0d
        v1.4.1: milestone, 2017-10-24 18:06:03, 0d
        v1.4.2: milestone, 2017-11-02 14:38:03, 0d
        v1.4.3: milestone, 2017-11-14 12:08:55, 0d
        v1.4.4: milestone, 2017-11-23 11:48:03, 0d
        v1.4.5: milestone, 2017-12-06 10:44:03, 0d
        v1.4.6: milestone, 2018-01-02 12:54:03, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v1.4.0-rc1 | 2017-08-29 09:37:47 +0200 | 5   |
| v1.4.0     | 2017-10-16 18:42:03 +0200 | 6   |
| v1.4.6     | 2018-01-02 12:54:03 +0100 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v1.4/CHANGELOG.md)

## v1.5, cancoillotte

<p align="center">
    <picture>
    <img alt="v1.5-cancoillotte" title="v1.5-cancoillotte" width="400" src="./img/traefik-v1.5-cancoillotte.svg">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v1.5
        v1.5.0-rc1: milestone, 2017-11-28 14:50:06, 0d
        v1.5.0-rc2: milestone, 2017-12-06 15:58:03, 0d
        v1.5.0-rc3: milestone, 2017-12-20 15:10:06, 0d
        v1.5.0-rc4: milestone, 2018-01-04 15:22:03, 0d
        v1.5.0-rc5: milestone, 2018-01-15 16:48:03, 0d
        v1.5.0: crit, milestone, 2018-01-23 17:34:04, 0d
        v1.5.1: milestone, 2018-01-29 15:08:40, 0d
        v1.5.2: milestone, 2018-02-12 11:46:03, 0d
        v1.5.3: milestone, 2018-02-27 12:28:03, 0d
        v1.5.4: milestone, 2018-03-15 14:26:03, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v1.5.0-rc1 | 2017-11-28 14:50:06 +0100 | 5   |
| v1.5.0     | 2018-01-23 17:34:04 +0100 | 4   |
| v1.5.4     | 2018-03-15 14:26:03 +0100 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v1.5/CHANGELOG.md)

## v1.6, tetedemoine

<p align="center">
    <picture>
    <img alt="v1.6-tete-de-moine" title="v1.6-tete-de-moine" width="400" src="./img/traefik-v1.6-tete-de-moine.svg">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v1.6
        v1.6.0-rc1: milestone, 2018-03-26 16:40:03, 0d
        v1.6.0-rc2: milestone, 2018-03-27 16:54:53, 0d
        v1.6.0-rc3: milestone, 2018-03-28 17:56:04, 0d
        v1.6.0-rc4: milestone, 2018-04-04 15:04:04, 0d
        v1.6.0-rc5: milestone, 2018-04-12 11:44:03, 0d
        v1.6.0-rc6: milestone, 2018-04-17 13:42:03, 0d
        v1.6.0: crit, milestone, 2018-04-30 23:20:05, 0d
        v1.6.1: milestone, 2018-05-14 21:08:03, 0d
        v1.6.2: milestone, 2018-05-22 17:06:04, 0d
        v1.6.3: milestone, 2018-06-05 17:20:04, 0d
        v1.6.4: milestone, 2018-06-15 17:04:03, 0d
        v1.6.5: milestone, 2018-07-10 17:46:04, 0d
        v1.6.6: milestone, 2018-08-20 14:46:02, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v1.6.0-rc1 | 2018-03-26 16:40:03 +0200 | 6   |
| v1.6.0     | 2018-04-30 23:20:05 +0200 | 6   |
| v1.6.6     | 2018-08-20 14:46:02 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v1.6/CHANGELOG.md)

## v1.7, maroilles

<p align="center">
    <picture>
    <img alt="v1.7-maroilles" title="v1.7-maroilles" width="400" src="./img/traefik-v1.7-maroilles.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 3month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v1.7
        v1.7.0-rc1: milestone, 2018-07-09 16:54:04, 0d
        v1.7.0-rc2: milestone, 2018-07-17 14:30:03, 0d
        v1.7.0-rc3: milestone, 2018-08-01 15:28:03, 0d
        v1.7.0-rc4: milestone, 2018-09-07 11:34:03, 0d
        v1.7.0-rc5: milestone, 2018-09-18 15:36:03, 0d
        v1.7.0: crit, milestone, 2018-09-24 11:44:03, 0d
        v1.7.1: milestone, 2018-09-29 00:16:03, 0d
        v1.7.2: milestone, 2018-10-04 15:34:02, 0d
        v1.7.3: milestone, 2018-10-15 12:02:03, 0d
        v1.7.4: milestone, 2018-10-30 11:32:04, 0d
        v1.7.5: milestone, 2018-12-03 11:34:04, 0d
        v1.7.6: milestone, 2018-12-14 04:42:03, 0d
        v1.7.7: milestone, 2019-01-08 10:52:03, 0d
        v1.7.8: milestone, 2019-01-29 17:22:07, 0d
        v1.7.9: milestone, 2019-02-11 12:24:03, 0d
        v1.7.10: milestone, 2019-03-28 15:42:05, 0d
        v1.7.11: milestone, 2019-04-26 10:34:06, 0d
        v1.7.12: milestone, 2019-05-29 20:42:06, 0d
        v1.7.13: milestone, 2019-08-08 09:04:03, 0d
        v1.7.14: milestone, 2019-08-14 02:06:03, 0d
        v1.7.15: milestone, 2019-09-12 18:10:05, 0d
        v1.7.16: milestone, 2019-09-13 15:04:04, 0d
        v1.7.17: milestone, 2019-09-23 19:48:04, 0d
        v1.7.18: milestone, 2019-09-26 15:46:05, 0d
        v1.7.19: milestone, 2019-10-28 14:58:04, 0d
        v1.7.20: milestone, 2019-12-10 17:50:05, 0d
        v1.7.21: milestone, 2020-02-20 18:22:04, 0d
        v1.7.22: milestone, 2020-03-18 15:00:07, 0d
        v1.7.23: milestone, 2020-03-23 16:50:04, 0d
        v1.7.24: milestone, 2020-03-25 14:48:05, 0d
        v1.7.25: milestone, 2020-07-15 12:28:03, 0d
        v1.7.26: milestone, 2020-07-28 17:32:03, 0d
        v1.7.27: milestone, 2021-01-13 17:16:05, 0d
        v1.7.28: milestone, 2021-01-13 18:14:03, 0d
        v1.7.29: milestone, 2021-03-29 18:12:04, 0d
        v1.7.30: milestone, 2021-04-08 16:30:04, 0d
        v1.7.31: milestone, 2021-10-04 18:16:07, 0d
        v1.7.32: milestone, 2021-10-06 18:50:09, 0d
        v1.7.33: milestone, 2021-10-07 16:32:07, 0d
        v1.7.34: milestone, 2021-12-10 17:54:05, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v1.7.0-rc1 | 2018-07-09 16:54:04 +0200 | 5   |
| v1.7.0     | 2018-09-24 11:44:03 +0200 | 33+ |
| v1.7.33    | 2021-10-07 16:32:07 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v1.7/CHANGELOG.md)

## v2.0-alpha/beta, faisselle

| version       | date                      | fix |
|---------------|---------------------------|-----|
| v2.0.0-alpha1 | 2019-03-18 15:18:04 +0100 | 8   |
| v2.0.0-beta1  | 2019-07-19 17:18:03 +0200 | 1   |

## v2.0, montdor

<p align="center">
    <picture>
    <img alt="v2.0-montdor" title="v2.0-montdor" width="400" src="./img/traefik-v2.0-montdor.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.0
        v2.0.0-alpha1: milestone, 2019-03-18 15:18:04, 0d
        v2.0.0-alpha2: milestone, 2019-03-19 19:24:07, 0d
        v2.0.0-alpha3: milestone, 2019-03-29 15:34:04, 0d
        v2.0.0-alpha4: milestone, 2019-04-17 12:10:04, 0d
        v2.0.0-alpha5: milestone, 2019-06-17 23:40:05, 0d
        v2.0.0-alpha6: milestone, 2019-06-18 18:10:06, 0d
        v2.0.0-alpha7: milestone, 2019-06-21 17:46:02, 0d
        v2.0.0-alpha8: milestone, 2019-07-01 19:36:04, 0d
        v2.0.0-beta1: milestone, 2019-07-19 17:18:03, 0d
        v2.0.0-rc1: milestone, 2019-08-26 10:36:03, 0d
        v2.0.0-rc2: milestone, 2019-09-03 21:18:03, 0d
        v2.0.0-rc3: milestone, 2019-09-10 18:58:03, 0d
        v2.0.0-rc4: milestone, 2019-09-13 20:52:04, 0d
        v2.0.0: crit, milestone, 2019-09-16 18:28:04, 0d
        v2.0.1: milestone, 2019-09-26 18:02:05, 0d
        v2.0.2: milestone, 2019-10-09 19:12:05, 0d
        v2.0.3: milestone, 2019-10-28 17:50:05, 0d
        v2.0.4: milestone, 2019-10-28 21:10:50, 0d
        v2.0.5: milestone, 2019-11-14 18:22:04, 0d
        v2.0.6: milestone, 2019-12-02 18:14:05, 0d
        v2.0.7: milestone, 2019-12-09 18:34:04, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v2.0.0-rc1 | 2019-08-26 10:36:03 -0700 | 4   |
| v2.0.0     | 2019-09-16 18:28:04 +0200 | 7   |
| v2.0.7     | 2019-12-09 18:34:04 +0100 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.0/CHANGELOG.md)

## v2.1, cantal

<p align="center">
    <picture>
    <img alt="v2.1-cantal" title="v2.1-cantal" width="400" src="./img/traefik-v2.1-cantal.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.1
        v2.1.0-rc1: milestone, 2019-11-15 18:44:03, 0d
        v2.1.0-rc2: milestone, 2019-11-15 20:32:03, 0d
        v2.1.0-rc3: milestone, 2019-12-02 19:10:04, 0d
        v2.1.0: crit, milestone, 2019-12-11 18:40:04, 0d
        v2.1.1: milestone, 2019-12-12 19:44:04, 0d
        v2.1.2: milestone, 2020-01-07 16:56:05, 0d
        v2.1.3: milestone, 2020-01-21 18:20:05, 0d
        v2.1.4: milestone, 2020-02-06 17:54:03, 0d
        v2.1.5: milestone, 2020-02-28 18:02:05, 0d
        v2.1.6: milestone, 2020-02-28 18:30:05, 0d
        v2.1.7: milestone, 2020-03-18 17:21:20, 0d
        v2.1.8: milestone, 2020-03-19 15:46:04, 0d
        v2.1.9: milestone, 2020-03-23 17:40:04, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v2.1.0-rc1 | 2019-11-15 18:44:03 +0100 | 3   |
| v2.1.0     | 2019-12-11 18:40:04 +0100 | 9   |
| v2.1.9     | 2020-03-23 17:40:04 +0100 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.1/CHANGELOG.md)

## v2.2, chevrotin

<p align="center">
    <picture>
    <img alt="v2.2-chevrotin" title="v2.2-chevrotin" width="400" src="./img/traefik-v2.2-chevrotin.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.2
        v2.2.0-rc1: milestone, 2020-03-05 19:50:51, 0d
        v2.2.0-rc2: milestone, 2020-03-11 18:12:04, 0d
        v2.2.0-rc3: milestone, 2020-03-18 18:58:04, 0d
        v2.2.0-rc4: milestone, 2020-03-19 18:10:05, 0d
        v2.2.0: crit, milestone, 2020-03-25 17:46:04, 0d
        v2.2.1: milestone, 2020-04-29 19:46:04, 0d
        v2.2.10: milestone, 2020-09-04 17:40:03, 0d
        v2.2.11: milestone, 2020-09-07 16:00:03, 0d
        v2.2.2: milestone, 2020-07-08 17:16:03, 0d
        v2.2.3: milestone, 2020-07-09 17:58:03, 0d
        v2.2.4: milestone, 2020-07-10 19:16:04, 0d
        v2.2.5: milestone, 2020-07-13 18:18:03, 0d
        v2.2.6: milestone, 2020-07-17 17:54:04, 0d
        v2.2.7: milestone, 2020-07-20 18:48:04, 0d
        v2.2.8: milestone, 2020-07-28 17:34:03, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v2.2.0-rc1 | 2020-03-05 19:50:51 +0100 | 4   |
| v2.2.0     | 2020-03-25 17:46:04 +0100 | 11  |
| v2.2.11    | 2020-09-07 16:00:03 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.2/CHANGELOG.md)

## v2.3, picodon

<p align="center">
    <picture>
    <img alt="v2.3-picodon" title="v2.3-picodon" width="400" src="./img/traefik-v2.3-picodon.jpg">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.3
        v2.3.0-rc1: milestone, 2020-07-15 20:50:03, 0d
        v2.3.0-rc2: milestone, 2020-07-15 22:00:19, 0d
        v2.3.0-rc3: milestone, 2020-07-28 19:16:04, 0d
        v2.3.0-rc4: milestone, 2020-08-19 17:46:05, 0d
        v2.3.0-rc5: milestone, 2020-09-07 18:30:04, 0d
        v2.3.0-rc6: milestone, 2020-09-16 16:02:03, 0d
        v2.3.0-rc7: milestone, 2020-09-18 17:20:03, 0d
        v2.3.0: crit, milestone, 2020-09-23 12:44:04, 0d
        v2.3.1: milestone, 2020-09-29 17:36:04, 0d
        v2.3.2: milestone, 2020-10-19 20:22:04, 0d
        v2.3.3: milestone, 2020-11-19 18:31:09, 0d
        v2.3.4: milestone, 2020-11-24 17:06:04, 0d
        v2.3.5: milestone, 2020-12-10 16:48:04, 0d
        v2.3.6: milestone, 2020-12-17 17:02:04, 0d
        v2.3.7: milestone, 2021-01-11 18:48:03, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v2.3.0-rc1 | 2020-07-15 20:50:03 +0200 | 7   |
| v2.3.0     | 2020-09-23 12:44:04 +0200 | 7   |
| v2.3.7     | 2021-01-11 18:48:03 +0100 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.3/CHANGELOG.md)

## v2.4, livarot

<p align="center">
    <picture>
    <img alt="v2.4-livarot" title="v2.4-livarot" width="400" src="./img/traefik-v2.4-livarot.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.4
        v2.4.0-rc1: milestone, 2020-12-16 16:42:04, 0d
        v2.4.0-rc2: milestone, 2021-01-12 16:30:04, 0d
        v2.4.0: crit, milestone, 2021-01-19 16:50:04, 0d
        v2.4.1: milestone, 2021-02-01 17:14:04, 0d
        v2.4.2: milestone, 2021-02-02 18:06:04, 0d
        v2.4.3: milestone, 2021-02-15 16:52:03, 0d
        v2.4.4: milestone, 2021-02-18 15:28:03, 0d
        v2.4.5: milestone, 2021-02-18 18:04:03, 0d
        v2.4.6: milestone, 2021-03-01 19:14:03, 0d
        v2.4.7: milestone, 2021-03-08 18:04:03, 0d
        v2.4.8: milestone, 2021-03-23 16:34:04, 0d
        v2.4.9: milestone, 2021-06-21 17:00:09, 0d
        v2.4.10: milestone, 2021-07-13 16:54:08, 0d
        v2.4.11: milestone, 2021-07-15 16:48:11, 0d
        v2.4.12: milestone, 2021-07-26 18:08:09, 0d
        v2.4.13: milestone, 2021-07-30 16:50:07, 0d
        v2.4.14: milestone, 2021-08-16 17:26:14, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v2.4.0-rc1 | 2020-12-16 16:42:04 +0100 | 2   |
| v2.4.0     | 2021-01-19 16:50:04 +0100 | 14  |
| v2.4.14    | 2021-08-16 17:26:14 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.4/CHANGELOG.md)

## v2.5, brie

<p align="center">
    <picture>
    <img alt="v2.5-brie" title="v2.5-brie" width="400" src="./img/traefik-v2.5-brie.jpg">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.5
        v2.5.0-rc1: milestone, 2021-06-28 18:00:12, 0d
        v2.5.0-rc2: milestone, 2021-06-28 20:43:21, 0d
        v2.5.0-rc3: milestone, 2021-07-20 16:26:08, 0d
        v2.5.0-rc4: milestone, 2021-08-03 18:42:11, 0d
        v2.5.0-rc5: milestone, 2021-08-03 19:58:08, 0d
        v2.5.0-rc6: milestone, 2021-08-13 18:04:15, 0d
        v2.5.0: crit, milestone, 2021-08-17 18:04:05, 0d
        v2.5.1: milestone, 2021-08-20 18:27:12, 0d
        v2.5.2: milestone, 2021-09-02 16:46:11, 0d
        v2.5.3: milestone, 2021-09-20 17:30:06, 0d
        v2.5.4: milestone, 2021-11-08 18:36:13, 0d
        v2.5.5: milestone, 2021-12-10 17:52:04, 0d
        v2.5.6: milestone, 2021-12-22 17:22:04, 0d
        v2.5.7: milestone, 2022-01-20 17:08:07, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v2.5.0-rc1 | 2021-06-28 18:00:12 +0200 | 6   |
| v2.5.0     | 2021-08-17 18:04:05 +0200 | 7   |
| v2.5.7     | 2021-09-20 17:30:06 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.5/CHANGELOG.md)

## v2.6, rocamadour

<p align="center">
    <picture>
    <img alt="v2.6-rocamadour" title="v2.6-rocamadour" width="400" src="./img/traefik-v2.6-rocamadour.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.6
        v2.6.0-rc1: milestone, 2021-12-20 17:02:06, 0d
        v2.6.0-rc2: milestone, 2022-01-12 16:40:06, 0d
        v2.6.0-rc3: milestone, 2022-01-20 18:58:07, 0d
        v2.6.0: crit, milestone, 2022-01-24 17:58:04, 0d
        v2.6.1: milestone, 2022-02-14 17:44:08, 0d
        v2.6.2: milestone, 2022-03-24 17:14:57, 0d
        v2.6.3: milestone, 2022-03-29 15:00:09, 0d
        v2.6.4: milestone, 2022-05-03 16:32:08, 0d
        v2.6.5: milestone, 2022-05-03 18:28:08, 0d
        v2.6.6: milestone, 2022-05-03 18:53:05, 0d
        v2.6.7: milestone, 2022-05-24 16:14:08, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v2.6.0-rc1 | 2021-12-20 17:02:06 +0100 | 3   |
| v2.6.0     | 2022-01-24 17:58:04 +0100 | 7   |
| v2.6.7     | 2022-05-24 16:14:08 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.6/CHANGELOG.md)

## v2.7, epoisses

<p align="center">
    <picture>
    <img alt="v2.7-epoisses" title="v2.7-epoisses" width="400" src="./img/traefik-v2.7-epoisses.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.7
        v2.7.0-rc1: milestone, 2022-03-24 20:54:08, 0d
        v2.7.0-rc2: milestone, 2022-03-29 17:00:09, 0d
        v2.7.0: crit, milestone, 2022-05-24 18:58:08, 0d
        v2.7.1: milestone, 2022-06-13 15:30:08, 0d
        v2.7.2: milestone, 2022-06-27 15:52:08, 0d
        v2.7.3: milestone, 2022-06-29 15:44:08, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v2.7.0-rc1 | 2022-03-24 20:54:08 +0100 | 2   |
| v2.7.0     | 2022-05-24 18:58:08 +0200 | 3   |
| v2.7.3     | 2022-06-29 15:44:08 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.7/CHANGELOG.md)

## v2.8, vacherin

<p align="center">
    <picture>
    <img alt="v2.8-vacherin" title="v2.8-vacherin" width="400" src="./img/traefik-v2.8-vacherin.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.
        v2.8.0-rc1: milestone, 2022-06-13 17:26:12, 0d
        v2.8.0-rc2: milestone, 2022-06-27 17:05:11, 0d
        v2.8.0: crit, milestone, 2022-06-29 17:38:37, 0d
        v2.8.1: milestone, 2022-07-11 16:02:09, 0d
        v2.8.2: milestone, 2022-08-11 16:50:10, 0d
        v2.8.3: milestone, 2022-08-12 16:19:31, 0d
        v2.8.4: milestone, 2022-09-02 16:38:08, 0d
        v2.8.5: milestone, 2022-09-13 17:13:58, 0d
        v2.8.6: milestone, 2022-09-23 15:24:15, 0d
        v2.8.7: milestone, 2022-09-23 16:22:38, 0d
        v2.8.8: milestone, 2022-09-30 12:03:03, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v2.8.0-rc1 | 2022-06-13 17:26:12 +0200 | 2   |
| v2.8.0     | 2022-06-29 17:38:37 +0200 | 8   |
| v2.8.8     | 2022-09-30 12:03:03 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.8/CHANGELOG.md)

## v2.9, banon

<p align="center">
    <picture>
    <img alt="v2.9-banon" title="v2.9-banon" width="400" src="./img/traefik-v29-banon.jpg">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.9
        v2.9.0-rc1: milestone, 2022-09-14 16:52:03, 0d
        v2.9.0-rc2: milestone, 2022-09-14 17:33:51, 0d
        v2.9.0-rc3: milestone, 2022-09-16 16:00:08, 0d
        v2.9.0-rc4: milestone, 2022-09-23 16:01:00, 0d
        v2.9.0-rc5: milestone, 2022-09-30 15:02:08, 0d
        v2.9.1: crit, milestone, 2022-10-03 16:17:58, 0d
        v2.9.2: milestone, 2022-10-27 16:53:16, 0d
        v2.9.3: milestone, 2022-10-27 17:50:54, 0d
        v2.9.4: milestone, 2022-10-27 20:40:05, 0d
        v2.9.5: milestone, 2022-11-17 15:57:23, 0d
        v2.9.6: milestone, 2022-12-07 15:14:05, 0d
        v2.9.7: milestone, 2023-02-14 16:09:19, 0d
        v2.9.8: milestone, 2023-02-15 16:02:06, 0d
        v2.9.9: milestone, 2023-03-21 16:47:43, 0d
        v2.9.10: milestone, 2023-04-06 18:10:03, 0d

```

| version    | date                      | fix |
|------------|---------------------------|-----|
| v2.9.0-rc1 | 2022-06-13 17:26:12 +0200 | 2   |
| v2.9.0     | 2022-06-29 17:38:37 +0200 | 10  |
| v2.9.10    | 2023-04-06 18:10:03 +0200 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.9/CHANGELOG.md)

## v2.10, saintmarcelin

<p align="center">
    <picture>
    <img alt="v2.10-saintmarcelin" title="v2.10-saintmarcelin" width="400" src="./img/traefik-v2.10-saintmarcelin.jpg">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.10
        v2.10.0-rc1: milestone, 2023-03-22 11:06:05, 0d
        v2.10.0-rc2: milestone, 2023-04-07 11:00:06, 0d
        v2.10.0: crit, milestone, 2023-04-24 15:38:05, 0d
        v2.10.1: milestone, 2023-04-27 16:46:11, 0d
        v2.10.2: milestone, 2023-06-19 12:00:06, 0d
        v2.10.3: milestone, 2023-06-19 18:14:30, 0d
        v2.10.4: milestone, 2023-07-24 16:44:05, 0d
        v2.10.5: milestone, 2023-10-11 15:50:05, 0d
        v2.10.6: milestone, 2023-11-28 15:46:10, 0d
        v2.10.7: milestone, 2023-12-06 16:42:09, 0d

```

| version     | date                      | fix |
|-------------|---------------------------|-----|
| v2.10.0-rc1 | 2022-06-13 17:26:12 +0200 | 2   |
| v2.10.0     | 2022-06-29 17:38:37 +0200 | 7   |
| v2.10.7     | 2023-12-06 16:42:09 +0100 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.10/CHANGELOG.md)

## v2.11, mimolette

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v2.10
        v2.11.0-rc1: milestone, 2024-01-03 11:12:05, 0d
        v2.11.0-rc2: milestone, 2024-01-24 15:20:09, 0d
        v2.11.0: crit, milestone, 2024-02-12 16:14:04, 0d

```

| version     | date                      | fix |
|-------------|---------------------------|-----|
| v2.11.0-rc1 | 2024-01-03 11:12:05 +0100 | 2   |
| v2.11.0     | 2024-02-12 16:14:04 +0100 |     |

[CHANGELOG](https://github.com/containous/traefik/blob/v2.11/CHANGELOG.md)

## v3.0, beaufort

<p align="center">
    <picture>
    <img alt="v2.10-saintmarcelin" title="v3.0-beaufort" width="400" src="./img/traefik-v3.0-beaufort.png">
    </picture>
</p>

```mermaid
gantt
    title Timeline
    todayMarker off
    tickInterval 1month
    axisFormat %Y-%m
    dateFormat YYYY-MM-DD HH:mm:ss
    section v3.0
        v3.0.0-beta1: milestone, 2022-12-05 16:58:04, 0d
        v3.0.0-beta2: milestone, 2022-12-07 17:26:04, 0d
        v3.0.0-beta3: milestone, 2023-06-22 01:18:05, 0d
        v3.0.0-beta4: milestone, 2023-10-12 09:48:05, 0d
        v3.0.0-beta5: milestone, 2023-11-29 16:08:05, 0d
        v3.0.0-rc1: milestone, 2024-02-13 14:38:03, 0d
```

| version      | date                      | fix |
|--------------|---------------------------|-----|
| v3.0.0-beta1 | 2022-12-05 16:58:04 +0100 | 5+  |
| v3.0.0-rc1   | 2024-02-13 14:38:03 +0100 |     |
