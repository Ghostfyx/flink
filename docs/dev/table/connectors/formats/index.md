---
title: "Formats"
nav-id: sql-formats
nav-parent_id: sql-connectors
nav-pos: 1
nav-show_overview: true
---
<!--
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->

Flink provides a set of table formats that can be used with table connectors. A table format is a storage format defines how to map binary data onto table columns.

Flink supports the following formats:

<table class="table table-bordered">
    <thead>
      <tr>
        <th class="text-left">Formats</th>
        <th class="text-left">Supported Connectors</th>
      </tr>
    </thead>
    <tbody>
        <tr>
          <td>CSV</td>
          <td>Apache Kafka,
          <a href="{{ site.baseurl }}/dev/table/connectors/filesystem.html">Filesystem</a></td>
        </tr>
        <tr>
         <td><a href="{{ site.baseurl }}/dev/table/connectors/formats/json.html">JSON</a></td>
         <td>Apache Kafka,
          <a href="{{ site.baseurl }}/dev/table/connectors/filesystem.html">Filesystem</a>,
          Elasticsearch</td>
       </tr>
        <tr>
          <td><a href="{{ site.baseurl }}/dev/table/connectors/formats/avro.html">Apache Avro</a></td>
          <td>Apache Kafka,
           <a href="{{ site.baseurl }}/dev/table/connectors/filesystem.html">Filesystem</a></td>
        </tr>
        <tr>
         <td>Debezium JSON</td>
         <td>Apache Kafka</td>
        </tr>
        <tr>
         <td>Canal JSON</td>
         <td>Apache Kafka</td>
        </tr>
        <tr>
         <td>Apache Parquet</td>
         <td><a href="{{ site.baseurl }}/dev/table/connectors/filesystem.html">Filesystem</a></td>
        </tr>
        <tr>
         <td>Apache ORC</td>
         <td><a href="{{ site.baseurl }}/dev/table/connectors/filesystem.html">Filesystem</a></td>
        </tr>
    </tbody>
</table>