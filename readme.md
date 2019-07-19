# Suicide Rates Overview (1985 - 2016)


## by (Viraj Patel)


## Dataset

> This is a dataset from kaggle. You can find the dataset on [this](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016) link. This dataset contains number suicides grouped by Gender,Country and Year respecively. We can find out a lot information such as what age group or gender have more number of suicide victims. We'll discuss these questiong later first let's take an overview of the dataset.

> This dataset is a combination of multiple dataset from various sources.Such as Human development index (HDI) was retrieved from http://hdr.undp.org/en/indicators/137506 World Bank. And GDP (current US $) by country:1985 to 2016. Retrieved from http://databank.worldbank.org/data/source/world-development-indicators.


## Summary of Findings


### Suicide counts for different countries.

> As per graphs we can say that `Russian Federation`,`United States` and `Japan` have highest suicide counts in all of the countries. There are many factors that can lead to high suicide rate for country , population being one of them. So, if a country has higher population chances are it might have a high suicide rate.

> And countries like `kribati`,`Cabo Verde`,`Maldives`, and `Dominica` Very low suicide rate, Population factor seems to working here as these countries have very low population.

### Suicide rate over the years.

> Suicide rate betweet years `1985` and `1988` is lowest for all time. We might think of `2016`, but we have very less data from 2016 so we surely cannot say that 2016 has lowest suicide rate. Also something interesting to look at is sudden drop between years `2003` and `2009`.

> Suicide rate is on peek in year `1999`, but after that it started decreasing slowly. Line is same between years `2004` to `2014`. And in 2015 it went down suddenly. For 2016 we can not be sure as we don't have mush data from 2016.

### Gender's affect on suicide rate. 

> Men are leading the charge even in suicides. Almost 77% victims in this dataset are men. For a men to commit suicide there are a lot of factors can if working. Such as Educational pressure, Financial pressure and Being emotinally broken. Developed countries can have almost same amount of pressure on both Men and Women as they have work load devided equally, But in developing countries and third world nations sometimes work pressure is high on Men compared to women this can be a major reason for this statastic.


### Suicide Rates In Different Age Groups.

> This seems bit awkward for me, I thought 15-24 years age group may have highest suicide count. But it seems being in 30's is not easy at all. Suicide rate is highest in `35-54` age group, Does that means finacial stabilty is related with suicidal tendency ?, We'll find that out later in the section... 

> Graph for age groups and Generations looks identical. I did some reasearch and found out Generations indicates different age groups. You can find more in [this](https://communityrising.kasasa.com/gen-x-gen-y-gen-z/) article.

### Suicide rates in different genders over the years.

> We already knew this was comming, We knew that Suicide count in male is higher then female but purpose of the chart was to find patterns in both genders over the years. 

> Line for men have more changes compared to women. Like Women's line is almost constant bewteen years `1990` and `2015`, But men's life way to more changes between this time. For example.there's a drop between 2002 and 2009.

### Suicides in different age groups over the years.

> Only one line to look is for age group for `35-54`, Except that every line is almost identical. In our main time series graph the line looked same as  `35-54's` line. That means suicide rate over the years is effected by suicide rate of `35-54` age group. 

> Line for age group `5-14` is also interesting. It is neither increasing neither decreasing over the time. Something must've happend during the time span of `2003 to 2009`, because in every age group there's drop and then increase in that time span. But that's a different topic. We'll talk over it in some different project.

### Population and suicide rate.

> First plot shows relation between Population and Suicide Numbers, this graph shows moderately strong relationship with so many oitliers. These outliers might be because of age and gender factors. We'll find this out later, But for this one we can say that Population ans Suicides Numbers have a positive correlation.

> Second plot shows relation between Population and Suicides per 100K population. This graph is not as expected because this shows increase in population has no effeect on suicide rate per 100K pop. at all. We can say that this is a very weak relationship indeed.

> Third plot shows relation between Suicides numbers and Suicide rate per 100K pop. Now this graph is what something we expected. Because this shows a moderately strong relationship. We can say that as Suicide rate per 100K pop. increases number of suicides also increases.

### Suicide rate comparison in top 3 countries for gender.

> This looks nothing different from the original time series graph. But something to notice here is curves of the lines in main graph are dependent on male line as female line doesn't show any noticeable curves. 

> Also both lines in united states graph seems very identicle. We can agree on both genders are having hard times in united states.


### Suicide rates for different age groups in both genders.

> Age group of 35-54 have massive gap in gender ratio. This again proves that being and male adult is a tough task. Males in this age group have a lot of problems to handle. In this age you have kids to raise , collecting their college fees, having a financial stability and many more.

> All of the other age groups don't have very larg difference compared to `35-54`. Also age group of `75+` have a very small gap. We can say that if survive being a male adult probably there will be very less chances of commiting suicide after retirement.

### Age group comparison for top 3 countries.

> `75+` age group is one to look at in this time. Because every graph follows same trend. But graph for `75+` age group is different. Where every graph has Russian Federation as highest and Japan as lowest, this graph has Japan as highest and Russian Federation with lowest bar height.

> This shows in Japan more suicide victims belong to age group of `75+`. Also one thing to notice is US has same height in every graph, that means age factor doesn't matter in US. There are almost same of suicide victims from every age group.

### Effect of population on suicide rates in genders.

> We know that male suicide victim count is way to large, And this graph shows that points where suicides rate is higher but population is low are all male. Also this graph indicates that population increase has no effect on female suicide rate at all.This scatter gives accurate representation on our outliers from before.


## Key Insights for Presentation


+  Age group of `35-54` have most number of suicides over the years. Also this age group contains most of male suicide victims. Also this group had a sudden increase in suicide rate in starting years where as other groups had no such increase.

+ We also came to know that every country in top 3 had `35-54` age group as highest except for japan, Japan had age group of `75+` as highest.

+ There are almost `76%` male victims and `24%` female victims in dataset. This shows one of the most important factors financial pressure that we talked about before.

+ Population has a moderately strong relationship with number of suicides in a country. Also suicide rate in women has no effect from population at all.