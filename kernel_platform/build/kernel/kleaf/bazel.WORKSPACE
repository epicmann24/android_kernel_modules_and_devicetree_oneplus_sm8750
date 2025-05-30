# Copyright (C) 2021 The Android Open Source Project
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#       http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

load("//build/kernel/kleaf:workspace.bzl", "define_kleaf_workspace")

define_kleaf_workspace()

# Tell Bazel about all of our “external” directories
local_repository(
    name = "rules_cc",
    path = "kernel_platform/external/bazelbuild-rules_cc",
)
local_repository(
    name = "bazel_skylib",
    path = "kernel_platform/external/bazel-skylib",
)
local_repository(
    name = "bazelbuild-platforms",
    path = "kernel_platform/external/bazelbuild-platforms",
)
local_repository(
    name = "bazelbuild-apple_support",
    path = "kernel_platform/external/bazelbuild-apple_support",
)
local_repository(
    name = "bazelbuild-bazel-central-registry",
    path = "kernel_platform/external/bazelbuild-bazel-central-registry",
)
local_repository(
    name = "bazelbuild-rules_java",
    path = "kernel_platform/external/bazelbuild-rules_java",
)
local_repository(
    name = "bazelbuild-rules_license",
    path = "kernel_platform/external/bazelbuild-rules_license",
)
local_repository(
    name = "bazelbuild-rules_pkg",
    path = "kernel_platform/external/bazelbuild-rules_pkg",
)
local_repository(
    name = "bazelbuild-rules_python",
    path = "kernel_platform/external/bazelbuild-rules_python",
)
local_repository(
    name = "dtc",
    path = "kernel_platform/external/dtc",
)

# And of course your local toolchain and skylib
local_repository(
    name = "kleaf_clang_toolchain",
    path = "kernel_platform/prebuilts/clang/host/linux-x86",
)


# Optional epilog for analysis testing.
load("//build/kernel/kleaf:workspace_epilog.bzl", "define_kleaf_workspace_epilog")
define_kleaf_workspace_epilog()
