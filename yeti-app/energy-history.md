# Goal Zero Yeti Energy Usage History

## [About the feature](#about-the-feature)

The Energy Usage History Screen provides energy usage in Watt-Hours (Wh) In and Watt-Hours Out so users can easily monitor the energy used over time.

## [Support](#support)

The **Energy Usage History** feature is available on the following Yeti models running firmware v1.5.0:

* Goal Zero Yeti 1500X
* Goal Zero Yeti 3000X
* Goal Zero Yeti 6000X

Users will also want to ensure they keep their iOS or Android app up to date for the latest features and support.

## [How it works](#how-it-works)

The Yeti constantly monitors the watts in and watts out of each of its input and output ports. This data is accumulated and logged offline. The Yeti can store about 10 days worth of energy data while offline. If the Yeti is offline for longer than 10 days, usage history data that is not uploaded to the Goal Zero Yeti App Cloud will be lost. Once the Yeti is online, it will upload any new data once per hour to the Yeti App Cloud. Once data is uploaded to the Yeti App Cloud, the data can be viewed in charts in the Goal Zero Yeti App.

## [Charts](#charts)

Users can select from different data views on the History screen in the App.

* The **Past day** view shows total energy usage over 1-hour periods for the past day.
* The **Past week** view shows total energy usage over 6-hour periods for the past 7 days.
* The **Past two weeks** view shows total energy usage over 12-hour periods for the past 14 days.
* The **Past month** view shows total energy usage over 1-day periods for the past month.
* The **Past two months** view shows total energy usage over 2-day periods for the past 2 months.
* The **Past half year** view shows total energy usage over 1-week periods for the past 6 months.
* The **Past year** view shows total energy usage over 2-week periods for the past year.
* The **Past two years** view shows total energy usage over 1-month periods for the past 2 years.

## [FAQ](#faq)

### Why does it look like I have supplied more Energy In than Energy Out?

It's actually entirely natural for Battery systems to require more power to be pumped in than power they can supply out due to various inefficiencies in the system. This is particularly notable if there is a constant load on the AC inverter as this requires constant conversion from DC to AC. Higher inefficiencies are expected at relatively small AC loads, i.e. 50-300W. The AC inverter in the Yeti 1500X, Yeti 3000X, and Yeti 6000X is more efficient at higher loads, i.e. 1500W+.

### Why don't I see any history data?

If you're using a Yeti 1400 or Yeti 3000, these models don't support the Energy Usage History feature due to hardware memory limitations. Check [here](#support) for the requirements for the feature.

If your Yeti is offline, you may not be able to see the latest data. You must also be Anywhere Connected to see the data.

