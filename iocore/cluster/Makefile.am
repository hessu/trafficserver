# Makefile.am for the traffic/iocore/cluster hierarchy
#
#  Licensed to the Apache Software Foundation (ASF) under one
#  or more contributor license agreements.  See the NOTICE file
#  distributed with this work for additional information
#  regarding copyright ownership.  The ASF licenses this file
#  to you under the Apache License, Version 2.0 (the
#  "License"); you may not use this file except in compliance
#  with the License.  You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
#  Unless required by applicable law or agreed to in writing, software
#  distributed under the License is distributed on an "AS IS" BASIS,
#  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
#  See the License for the specific language governing permissions and
#  limitations under the License.

AM_CPPFLAGS = \
  $(iocore_include_dirs) \
  -I$(top_srcdir)/lib \
  -I$(top_srcdir)/lib/records \
  -I$(top_srcdir)/lib/ts \
  -I$(top_srcdir)/proxy/http \
  -I$(top_srcdir)/proxy/hdrs \
  -I$(top_builddir)/proxy \
  -I$(top_builddir)/proxy/api/ts \
  -I$(top_srcdir)/proxy \
  -I$(top_srcdir)/mgmt \
  -I$(top_srcdir)/mgmt/preparse \
  -I$(top_srcdir)/mgmt/utils

noinst_LIBRARIES = libinkcluster.a

libinkcluster_a_SOURCES = \
  ClusterAPI.cc \
  ClusterCache.cc \
  ClusterConfig.cc \
  ClusterHandler.cc \
  ClusterHandlerBase.cc \
  ClusterHash.cc \
  ClusterLib.cc \
  ClusterLoadMonitor.cc \
  ClusterMachine.cc \
  ClusterProcessor.cc \
  ClusterRPC.cc \
  ClusterVConnection.cc \
  Inline.cc \
  P_Cluster.h \
  P_ClusterCache.h \
  P_ClusterCacheInternal.h \
  P_ClusterHandler.h \
  P_ClusterInline.h \
  P_ClusterInternal.h \
  P_ClusterLib.h \
  P_ClusterLoadMonitor.h \
  P_ClusterMachine.h \
  P_TimeTrace.h

#test_Cluster_SOURCES = \
#  test_I_Cluster.cc \
#  test_P_Cluster.cc
