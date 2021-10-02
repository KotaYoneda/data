# data

### 日本の出生数（母体年齢別）の推移（1925-2020年）

`annual_birth_by_maternal_age_2020.csv`

> e-Stat.go.jp >「人口動態調査」から引用 \
> 2020年データ 表番号4-6「母の年齢（５歳階級）別にみた年次別出生数・百分率及び出生率（女性人口千対）」 \
> https://www.e-stat.go.jp/stat-search?toukei=00450011 \
> ただし、1947年以前のデータは国立社会保障・人口問題研究所の公開データから引用 \
> http://www.ipss.go.jp/syoushika/tohkei/Popular/P_Detail2020.asp?fname=T04-07.htm

![annula birth by maternal age](https://github.com/KotaYoneda/data/raw/main/img/anual_birth_by_maternal_age_2020.png "annula birth by maternal age")


ここで、`female_population_2019.csv`を用いて年齢別女性人口当たりの出生数の推移を求める。

> e-Stat.go.jp >「人口動態調査」から引用 \
> 2019年データ 表番号3「年次・性・年齢別人口」 (3) 女 \
> https://www.e-stat.go.jp/stat-search?toukei=00450011

![annula birth per female population by maternal age](https://github.com/KotaYoneda/data/raw/main/img/anual_birth_per_female_population_by_maternal_age_2019.png "annula birth per female population by maternal age")

世代別にまとめ直すと次の通り

![annula birth per female population by generation 2015](https://github.com/KotaYoneda/data/raw/main/img/anual_birth_per_female_population_by_generation_2015.png "annula birth per female population by generation 2015")


### 日本の出生数・死産数・早期新生児死亡数・新生児死亡数・乳児死亡数の推移（1899-2020年）

`perinatal_mortality_2020.csv`

> e-Stat.go.jp >「人口動態調査」から引用 \
> 2020年データ 表番号8-1「年次別にみた性・妊娠満22週以後の死産－早期新生児死亡別周産期死亡数」 \
> 2020年データ 表番号6-1「年次別にみた出生数及び性別乳児死亡数並びに乳児死亡率（出生千対）・乳児死亡性比及び総死亡中乳児死亡の占める割合」 \
> 2020年データ 表番号6-2「年次別にみた性別新生児死亡数並びに新生児死亡率（出生千対）・新生児死亡性比及び乳児死亡中新生児死亡の占める割合」 \
> https://www.e-stat.go.jp/stat-search?toukei=00450011

![perinatal mortality](https://github.com/KotaYoneda/data/raw/main/img/perinatal_mortality_2020.png "perinatal mortality")

### 日本の都道府県毎の人口（2021年1月1日現在）

`prefecture_population_20210101.csv`

> e-Stat.go.jp >「住民基本台帳に基づく人口、人口動態及び世帯数調査」から引用 \
> 2021年データ 表番号21-01「【総計】都道府県別人口、人口動態及び世帯数」 \
> https://www.e-stat.go.jp/stat-search?toukei=00200241

