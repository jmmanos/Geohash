# Geohash

A Swift Playground focused on the creation and use of Geohashes. According to Wikipedia a Geohash is
> a hierarchical spatial data structure which subdivides space into buckets of grid shape

## Usage

Add the two files Geohash.swift and Base32Format.swift files into your project. 

```swift
let latitude = 57.64911
let longitude = 10.40744

let geohash = try Geohash(latitude: latitude, longitude: longitude, format: format, precision: 11)
```

## Reasons

Geohashing provides a shorter and simpler way to respresent geographic coordinates.

```swift
let geohashString = geohash.hashString // u4pruydqqvj vs 57.64911,10.40744
```
