# Copyright 2019 Google LLC. All Rights Reserved.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

# Absl
http_archive(
    name = "com_google_absl",
    sha256 = "3c119a995f3bb1e2aa7b3a37efe526172695816d63bb7a001139f25d628b9c6e",  # 2019-07-18
    strip_prefix = "abseil-cpp-278b26058c036833a4f7f3047d3f4d9296527f87",
    urls = ["https://github.com/abseil/abseil-cpp/archive/278b26058c036833a4f7f3047d3f4d9296527f87.zip"],
)

# GoogleTest/GoogleMock
http_archive(
    name = "com_google_googletest",
    sha256 = "baed63b97595c32667694de0a434f8f23da59609c4a44f3360ba94b0abd5c583",
    strip_prefix = "googletest-8ffb7e5c88b20a297a2e786c480556467496463b",
    urls = ["https://github.com/google/googletest/archive/8ffb7e5c88b20a297a2e786c480556467496463b.zip"],  # 2019-05-30
)

# libcap
http_archive(
    name = "org_kernel_libcap",
    build_file = "//pathauditor:bazel/libcap.BUILD",
    sha256 = "ef83108f77314e50bae926ae473f9b130b15240d17cbae05089e19c36a8676d6",
    strip_prefix = "libcap-2.13",
    urls = ["https://www.kernel.org/pub/linux/libs/security/linux-privs/libcap2/libcap-2.13.tar.gz"],
)

# gflags
http_archive(
    name = "com_github_gflags_gflags",
    sha256 = "53b16091efa386ab11e33f018eef0ed489e0ab63554455293cbb0cc2a5f50e98",
    strip_prefix = "gflags-28f50e0fed19872e0fd50dd23ce2ee8cd759338e",
    urls = ["https://github.com/gflags/gflags/archive/28f50e0fed19872e0fd50dd23ce2ee8cd759338e.zip"],  # 2019-01-25
)

# Google logging
http_archive(
    name = "com_google_glog",
    sha256 = "74010e549e3555a11d3eb22b80f0040fa4f013a4b254b2d5ede12afcc92e690b",
    strip_prefix = "glog-41f4bf9cbc3e8995d628b459f6a239df43c2b84a",
    urls = ["https://github.com/google/glog/archive/41f4bf9cbc3e8995d628b459f6a239df43c2b84a.zip"],  # 2019-02-02
)
