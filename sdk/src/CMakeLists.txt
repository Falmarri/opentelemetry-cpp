# Copyright The OpenTelemetry Authors
# SPDX-License-Identifier: Apache-2.0

add_subdirectory(common)
add_subdirectory(trace)
if(WITH_METRICS)
  add_subdirectory(metrics)
endif ()
if(WITH_LOGS_PREVIEW)
  add_subdirectory(logs)
endif()
add_subdirectory(version)
add_subdirectory(resource)
