# Ecom Admin Dependency Audits

## December 2021

### Bundle Major Versions Outdated
| Gem | Current | Latest | Requested  | Groups | Older than 1 year
|---|:----------:|:-------:|:-------:|:-------:|:-------:|
|avro-patches    |       0.3.2  |  1.0.2 |  >= 0    |   default
|avro_turf       |      0.8.0   | 1.3.0  | >= 0     |  default
|dogstatsd-ruby  |       3.0.0  |  5.1.0 |  ~> 3.0.0|   default
|rainbow         |       2.2.2  |  3.0.0 |          |
|rake            |       12.3.3 |  13.0.3|          |
|rugged          |       0.99.0 | 1.0.1  |          |
|thor            |       0.19.4 |  1.1.0 |          |
|unicode-display_width |  1.4.1 |   2.1.0|          | 

### Bundle Minor Versions Outdated 
| Gem | Latest | Current | Requested  | Groups | Older than 1 year
|---|:----------:|:-------:|:-------:|:-------:|:-------:|
|avro    |1.8.2    |1.10.0 |         |
|pronto  |0.9.5    |0.11.0 | ~> 0.9  |   test

### NPM Major & Minor Versions Outdated
| Package | Current | Wanted |  Latest | Location| Older than 1 year|
|---|:----------:|:-------:|:-------:|:-------:|:-------:|
|@types/node |  12.20.36 | 12.20.37  |  17.0.1 | thumbnail_generation
|aws-sdk     |  2.1020.0 | 2.1046.0  |2.1046.0 | thumbnail_generation
|aws-sdk-mock|     1.7.0 |    1.7.0  |   5.5.0 | thumbnail_generation
|jest        |    27.3.1 |   27.4.5  |  27.4.5 | thumbnail_generation
|sharp       |    0.29.2 |   0.29.3  |  0.29.3 | thumbnail_generation
