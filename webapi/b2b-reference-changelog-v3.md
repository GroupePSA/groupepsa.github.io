---
layout: doc-article
permalink: /webapi/b2b/api-reference-v3/changelog/
section: webapi
redirect_from: 
    - /webapi/b2b/api-reference/specification-v3/
subsection: b2b
categorie: API Reference v3 
title: Changelog
---

Version|Name
-|-
[b2b_v3.0.9](#b2b_v309) | 3.0.9
[b2b_v3.0.8](#b2b_v308) | 3.0.8
[b2b_v3.0.7](#b2b_v307) | 3.0.7
[b2b_v3.0.6](#b2b_v306) | 3.0.6
[b2b_v3.0.5](#b2b_v305) | 3.0.5
[b2b_v3.0.4](#b2b_v304) | 3.0.4
[b2b_v3.0.3](#b2b_v303) | 3.0.3 
[b2b_v3.0.0](#b2b_v300) | Candiate version

## b2b_v3.0.9

{% include published_on.html date='25 Jun 2021' %}

- Update Trigger name creation for monitor
- Refactoring of the vehicle structure (Removing unused embedded)
- Update charging & preconditionning remote command
- Update alertEnum
- Add remote navigation command
- Update Kinetic bloc

## b2b_v3.0.8

{% include published_on.html date='19 Apr 2021' %}

- Update FailureCause for remote callbacks
- Add "forced" parameter for doors remotes
- Update lockedStates format for remotes
- Update pattern for trigger names
- Remove telemetry Links for fleets
- Correct wakeUp for remote actions
- Remove label for GET /Vehicles
- Update alert vehicle list
- Add slot parameter as mandatory for remote preconditionning command


## b2b_v3.0.7


{% include published_on.html date='24 Feb 2021' %}

- Remove fleet/{fid}/telemetries API


## b2b_v3.0.6

{% include published_on.html date='9 Feb 2021' %}

- Update Typo (Description, Patterns...)
- Update DoorState & mileage object
- Remove collisions API
- Add NextDelayedTime as mandatory for remote Charging
- Add RemoteType WakeUp
- Add 2 new enum for lockedState

## b2b_v3.0.5

{% include published_on.html date='6 Jan 2021' %}

- Fix door.states enum by vehicle.doorsStates in extendedEventParam object
- Fix alerts enum by vehicle.alerts in extendedEventParam object
- Replacement OnChange by onChange in monitors descriptions
- Replacement Estimate enum to Estimated in lastPosition object


## b2b_v3.0.4

{% include published_on.html date='24 Nov 2020' %}

#### MPH Addons&Changes:

- Remove duration from remote ligth
- Fix includedIn keyword
- Replacement of energy by energies in API Status & Telemetries
- Fix missing type for brand field in vehicles object
- Add missing format for type: number
- Add description for triggerParam>boolExp field in API Monitors
- fix startd for startedAt

#### Webhook Monitor Template change:
- Change extension body type from array to object


## b2b_v3.0.3

{% include published_on.html date='14 Oct 2020' %}

- Add Open API SPEC (V3) security schemes support.
- Add TimeStamps (query parameter) extension to support period.
- Reduce extension enum list for Telemetry API.
- Add Telemetry Type filtering query parameter to all telemetry getter APIs.
- Add wakeup remote.

## b2b_v3.0.0

{% include published_on.html date='24 Mar 2020' %}

#### `Candiate version`
Spec version : b2b_v3.0.0