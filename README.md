# Google Analytics Connector

Google Analytics Connector 2.0.0 from Ksquare gives out-of box solution to Integrate your Google Analytics data with other business applications.


Easily design and build and integrate with mule flows to control and access google analytics data using secured pathway.

Google Analytics Connector Implements the following features for the MuleSoft-based enterprise solutions:
1) To request report data for a user, your application must identify the user and specify a view (profile) for which to retrieve the data.
2) To query the API for Google Analytics report data, which consists of dimensions and metrics.



Application/Service  |	Version
-------------------  | ----------
Mule Runtime	     |  4.X
Google Analytics Core|  Reporting API	V3
Java	             |  1.8 and later





## Highlights of Google Analytics Connector Mule 4:
=======


1.	It allows users to automatically build quires to determine which metrics and dimensions are brought back. We can select the metrics parameters from the dropdown and from these selected parameters connectors build a query.
2. Can retrieve the information from specific date ranges according to user.

Add this dependency to your application pom.xml
```

            <groupId>com.mulesoft.connectors</groupId>
            <artifactId>mule-googleanalytics-connector</artifactId>
            <version>2.0.0</version>
            <classifier>mule-plugin</classifier>

```
