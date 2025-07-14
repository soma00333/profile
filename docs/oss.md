---
title: OSS Contributions
nav_order: 5
layout: default
---

# OSS Contributions

<table>
  <thead>
    <tr>
      <th>Repository</th>
      <th>Role</th>
      <th>Detail</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/cockroachdb/cockroach">cockroachdb/cockroach</a></td>
      <td>Contributor</td>
      <td>
        <ul>
          <li>I removed an old <code>--oss</code> flag from the <code>dev ui</code> command to clean up the code and make development easier</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/reearth/reearth-flow">reearth/reearth-flow</a></td>
      <td>Committer</td>
      <td>
        <ul>
          <li>I built a processor that turns user scripts into WebAssembly files and runs them on WASM. This lets users customize workflows easily</li>
          <li>I built a real-time logging system for the workflow engine. It uses storage and cache well. Users can see worker status right away</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/kubernetes/kubernetes">kubernetes/kubernetes</a></td>
      <td>Contributor</td>
      <td>
        <ul>
          <li>I'm adding <a href="https://github.com/kubernetes/enhancements/tree/master/keps/sig-instrumentation/1602-structured-logging">Structured Logging</a> and <a href="https://github.com/kubernetes/enhancements/tree/master/keps/sig-instrumentation/3077-contextual-logging">Contextual Logging</a> to many packages. This makes the system more reliable and easier to debug</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/etcd-io/raft">etcd-io/raft</a></td>
      <td>Contributor</td>
      <td>
        <ul>
          <li>I'm improving how snapshots work by removing slow parts and making state changes simpler. This makes the code clearer and easier to maintain</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/etcd-io/etcd-operator">etcd-io/etcd-operator</a></td>
      <td>Contributor</td>
      <td>
        <ul>
          <li>I added a workflow to check that imports are grouped and ordered correctly. This keeps the code consistent</li>
          <li>I fixed the logic to make sure StatefulSet replicas match etcd cluster members. This keeps the cluster consistent</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/kubernetes/test-infra">kubernetes/test-infra</a></td>
      <td>Contributor</td>
      <td>
        <ul>
          <li>I added workflows that run tests after merging. This makes sure CI runs on main branch in etcd-operator and keeps it stable</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/envoyproxy/ai-gateway">envoyproxy/ai-gateway</a></td>
      <td>Contributor</td>
      <td>
        <ul>
          <li>I added a workflow to check issue titles and give feedback. This keeps the project more consistent</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table> 