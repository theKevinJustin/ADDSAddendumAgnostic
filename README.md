# ADDSAddendumAgnostic
Microsoft.Windows.Server.AD.2016.Monitoring.Addendum v1.0.4.5

Download [here](https://github.com/theKevinJustin/ADDSAddendumAgnostic/blob/main/Microsoft.Windows.Server.AD.2016.Monitoring.Addendum.xml)

### Microsoft Windows Server ADDS 2016+ Monitoring Addendum
Management pack configures rules/monitors, disables noisy rules, adds alert cleanup, summary report, team report, on-demand tasks, component alert monitor to simplify when a DC is down, and lastly service recovery automation


Blog [https://kevinjustin.com/blog/2023/08/18/adds-addendum-packs/](https://kevinjustin.com/blog/2023/08/18/adds-addendum-packs/)

# Version History:
```
v1.0.4.5  21 Dec 2023 whitespace audit, ResolutionState changes, performance changes to DS/WA
v1.0.4.2  13 Dec 2023 Updated Rule closure logic, updated Group PolicyReport DS/WA, gpsvc service monitor
v1.0.4.1  12 Dec 2023 Updated reset logic to use Management Pack, removed ID property from reset logic
v1.0.3.9   6 Dec 2023 Removed Component Monitor,Rule, added hourly WA, Add time to reset monitor logic, Resolve-SCOMAlert for Component alert ZERO findings
v1.0.3.7  28 Nov 2023 Updated Component Alert logic datasources, DisplayStrings
v1.0.3.6  23 Oct 2023 Updated Scheduler variable, EndTime for componentAlert script datasource
v1.0.3.4  11 Jul 2023 Component Alert DS/WA, Reports to Info, Disabled ATQ monitor for false positive alerts
v1.0.3.3   6 Jul 2023 Updated GroupPolicyClient Recovery and rules
v1.0.3.1  29 Jun 2023 ADDS Component alert script DS/WA
v1.0.2.9  24 Apr 2023 Updated overrides disabling event collection, ATQ to warning, disable site availablity rollup
v1.0.2.4  10 Jun 2022 Added Group Policy alerts
v1.0.2.2   6 Jun 2022 Updated AD Team report, variables, agent check, override ID's, separated cleanup and reports
v1.0.1.4  31 Jan 2022 Updated reports, versions, NEW alerts
v1.0.1.2   2 Dec 2021 Updated for standards, select to select-string
v1.0.1.0   5 May 2021 Updated DS/WA with additional AD report breakout detail
v1.0.0.11 16 Apr 2021 Updated auto-close report, rule names
v1.0.0.5  18 Mar 2021 Test for alerts before resetting, typos, versioned scripts, updated task names
v1.0.0.3  17 Mar 2021 Updated with auto-closure logic and daily ADDS reports
v1.0.0.0  10 Jan 2018 Created additional Alert Functionality, Service Recovery Tasks
```
