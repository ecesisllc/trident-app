---
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

**Effective Date:** November 17, 2026

This Privacy Policy describes how the Ecesis Trident app (“the App”) handles information. The App is designed for internal use by authorized Ecesis employees only.

## 1. Overview

The App allows authorized users to view dashboards and related information from an Apache Superset server URL that is either manually configured by the user or provided by the user’s organization through managed app configuration.

The App itself does not collect data for advertising, analytics, tracking, profiling, or sale. The App does not operate an independent backend service for collecting or storing user data.

The App functions as a client. It sends network requests only to the configured Superset server URL as necessary to service user-initiated actions in real time, such as authenticating the user, retrieving dashboard lists, displaying dashboard content, or loading profile information.

## 2. Configured Superset Server URL

The App only uses a Superset server URL that is either:

* manually configured by the user; or
* provided by the user’s organization through managed app configuration.

The App does not provide, operate, or control the configured Superset server.

Based on user actions, the App may send necessary network requests to the configured Superset server. For example:

* when the user opens the dashboard page, the App may request the list of available dashboards;
* when the user opens a dashboard, the App may request dashboard metadata, charts, filters, and related dashboard data;
* when the user opens the profile page, the App may request the user’s profile information.

The data returned by the configured Superset server is used by the App to display the requested dashboard, profile, or related content. The App itself does not independently store dashboard data, profile data, or business data beyond what is necessary to display the requested information and maintain the user’s session on the device.

Any server-side logging, auditing, retention, access control, monitoring, or data processing performed by the configured Superset server is governed by the policies and practices of the organization or service provider that operates that server.

## 3. Confidential Information

Dashboards and data shown in the App are confidential internal information of Ecesis. Users must handle this information in line with Ecesis's internal policies and must not share it outside the organization unless they are authorized to do so.

## 4. Authentication

The App may support Microsoft Entra ID OAuth authentication.

If the user chooses Microsoft Entra ID OAuth, the App opens the sign-in page for the Microsoft Entra ID tenant configured by the user or the user’s organization in an external browser or system-provided authentication session. The user completes authentication directly with Microsoft Entra ID.

After successful authentication, Microsoft Entra ID redirects the authentication callback back to the App. The App uses the resulting authentication information only to maintain the user’s session and make authorized requests to the configured Superset server.

The App does not sell, share, or use authentication information for advertising, tracking, analytics, or profiling.

## 5. On-Device Storage

The App may store limited information on the user’s device as needed for functionality, such as:

* the configured Superset server URL;
* managed app configuration provided by the user’s organization;
* authentication or session state;
* access tokens or refresh tokens, if required to keep the user signed in.

Where applicable, sensitive authentication information is stored using platform-provided secure storage mechanisms.

## 6. Third-Party and Organization-Configured Services

Depending on configuration, the App may interact with:

* **the user- or organization-configured Apache Superset server**, to provide dashboard, chart, profile, and related business information;
* **Microsoft Entra ID**, to provide OAuth authentication if selected by the user or organization.

The App does not control the privacy, security, logging, retention, or data processing practices of the configured Superset server or third-party authentication providers. Users should only use trusted Superset server URLs provided or approved by Ecesis or their organization.

## 7. Advertising, Analytics, and Tracking

The App does not use data for advertising.

The App does not perform cross-app tracking.

The App does not collect data for third-party marketing, analytics, or profiling.

## 8. Internal Use Only

The App is intended only for authorized Ecesis employees and approved internal users. Unauthorized access or use is not permitted.

Access to dashboards, profile information, and other business information is controlled by the configured Superset server and the organization’s authentication and authorization settings.

## 9. Data Retention

The App itself does not retain dashboard, profile, or business data beyond what is necessary to display the requested information, maintain the user’s session, and provide the App’s functionality on the user’s device.

Any retention of server logs, audit records, dashboard data, profile information, authentication records, or other information by the configured Superset server, Microsoft Entra ID, or other configured services is governed by the policies and practices of the organization or service provider that operates those services.

## 10. Security

The App relies on secure network communication and user-configured or organization-managed authentication systems to protect access to dashboard data.

Users should only use trusted Superset server URLs provided or approved by Ecesis or their organization.

## 11. Changes to This Privacy Policy

This Privacy Policy may be updated from time to time. The updated version will be made available through the App or another appropriate internal channel.

## 12. Contact

For questions about this Privacy Policy or the App’s data handling practices, please contact: info@ecesis.ai
