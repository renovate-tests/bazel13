load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "GBDeviceInfo",
    url = "https://github.com/lmirosevic/GBDeviceInfo/archive/6.3.0.tar.gz",
    sha256 = "d7666275dff039407ea467c3083b83e24934101777c8b55b6b1b3b7e9a9e220b",
    strip_prefix = "GBDeviceInfo-6.3.0/GBDeviceInfo"
)

http_archive(
    name = "com_github_nelhage_rules_boost",
    url = "https://github.com/nelhage/rules_boost/archive/fbac9be7640ecc0fab075233d394f08f1a37e449.tar.gz",
    sha256 = "1c2bdba583597b27da6b3ac7264ed4a16cf20a57dd26462cb612a84528162e20",
    strip_prefix = "rules_boost-fbac9be7640ecc0fab075233d394f08f1a37e449",
)
load("@com_github_nelhage_rules_boost//:boost/boost.bzl", "boost_deps")
boost_deps()
