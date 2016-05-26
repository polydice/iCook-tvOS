source "https://github.com/CocoaPods/Specs.git"
source "https://github.com/bcylin/Specs.git"

platform :tvos, "9.0"
use_frameworks!
inhibit_all_warnings!

workspace "iCookTV"
project "iCookTV"

target :iCookTV do
  pod "Alamofire"
  pod "Crashlytics"
  pod "Fabric"
  pod "Freddy"
  pod "HCYoutubeParser"
  pod "Hue", git: "https://github.com/hyperoslo/Hue.git", commit: "89ae5e1"
  pod "R.swift"
  pod "Kingfisher"
  pod "TreasureData-tvOS-SDK", "0.1.14"

  target :iCookTVTests do
    pod "Nimble"
    pod "Quick"
  end
end


plugin "cocoapods-keys", {
  project: "iCookTV",
  keys: ["BaseAPIURL", "CrashlyticsAPIKey", "TreasureDataAPIKey"]
}
