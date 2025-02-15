CHANGELOG
-------------
> ⚠️ Forked from ZLocation that is no longer active, and renamed to ZLocation2. Further changes are tracked in release notes.

## 1.4.3
* README and setup instruction improvements ([#106](https://github.com/vors/ZLocation/pull/106)) (Thanks @deltoss)
* Avoid an exception processing results in Get-ZLocation ([#112](https://github.com/vors/ZLocation/issues/112)) (Thanks @kahlin)

## 1.4.2
* Stop PowerShell < 6 on Windows emitting an error on import. ([#103](https://github.com/vors/ZLocation/issues/103))

## 1.4.1
* Resolve an OS detection bug resulting in errors when importing module on macOS ([#100](https://github.com/vors/ZLocation/issues/100)) (Thanks @nheath!)

## 1.4.0
* Attempt to handle the malformed database entries causing a number of reported issues ([#87](https://github.com/vors/ZLocation/pull/87))
* Add locations from Windows 10's Frequent Folders list to database ([#95](https://github.com/vors/ZLocation/pull/95))

## 1.3.0
* Prefer exact match over the weight when picking the location (#90)

## 1.2.0

* Move to unvisited directories if one is provided (#80)
* Fix - using ZLocation on Windows PowerShell creates errors in $Error (#75)

## 1.1.0

* Fix problems with non-unified casing #62 (thanks @cspotcode)
* Better representation for db entries (thanks @rkeithhill)
* Graceful install/remove for the prompt hook (thanks @rkeithhill)
* Add retry and backoff logic to better support multiply db connections on Mac.

## 1.0.0

* Make ZLocation work with `cmder`
* Replace persistent storage by LiteDB (thanks @cspotcode)
* Make ZLocation work on Linux and MacOS (thanks @cspotcode)
* Prioritize the beginning of a foldername in ranking
* Use `Register-ArgumentCompleter` for tab-completions (thanks @cspotcode)
* New shortcuts `z` and `z -l` for quick quering

## 0.3.0
