﻿---
title: Update methods (Microsoft.Isam.Esent.Interop)
TOCTitle: Update methods
ms:assetid: Methods.T:Microsoft.Isam.Esent.Interop.Update
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.update_methods(v=EXCHG.10)
ms:contentKeyID: 55104190
ms.date: 07/30/2014
ms.topic: article
---

# Update methods

Include protected members  
Include inherited members  

The [Update](dn351191\(v=exchg.10\).md) type exposes the following members.

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="dn351266(v=exchg.10).md">Cancel</a></td>
<td>Cancel the update.</td>
</tr>
<tr class="even">
<td><img src="images/Dn292116.protmethod(EXCHG.10).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="dn350541(v=exchg.10).md">CheckObjectIsNotDisposed</a></td>
<td>Throw an exception if this object has been disposed. (Inherited from <a href="dn319890(v=exchg.10).md">EsentResource</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="dn350553(v=exchg.10).md">Dispose()</a></td>
<td>Dispose of this object, releasing the underlying Esent resource. (Inherited from <a href="dn319890(v=exchg.10).md">EsentResource</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn292116.protmethod(EXCHG.10).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="dn350543(v=exchg.10).md">Dispose(Boolean)</a></td>
<td>Called by Dispose and the finalizer. (Inherited from <a href="dn319890(v=exchg.10).md">EsentResource</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn292116.protmethod(EXCHG.10).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="dn350552(v=exchg.10).md">Finalize</a></td>
<td>Finalizes an instance of the EsentResource class. (Inherited from <a href="dn319890(v=exchg.10).md">EsentResource</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292116.protmethod(EXCHG.10).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn292116.protmethod(EXCHG.10).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="dn351268(v=exchg.10).md">ReleaseResource</a></td>
<td>Called when the transaction is being disposed while active. This should rollback the transaction. (Overrides <a href="dn350545(v=exchg.10).md">EsentResource.ReleaseResource()</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292116.protmethod(EXCHG.10).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="dn350576(v=exchg.10).md">ResourceWasAllocated</a></td>
<td>Called by a subclass when a resource is allocated. (Inherited from <a href="dn319890(v=exchg.10).md">EsentResource</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn292116.protmethod(EXCHG.10).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="dn350577(v=exchg.10).md">ResourceWasReleased</a></td>
<td>Called by a subclass when a resource is freed. (Inherited from <a href="dn319890(v=exchg.10).md">EsentResource</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="dn351270(v=exchg.10).md">Save()</a></td>
<td>Update the tableid.</td>
</tr>
<tr class="even">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="dn351199(v=exchg.10).md">Save([], Int32, Int32)</a></td>
<td>Update the tableid.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="dn351272(v=exchg.10).md">SaveAndGotoBookmark</a></td>
<td>Update the tableid and position the tableid on the record that was modified. This can be useful when inserting a record because by default the tableid remains in its old location.</td>
</tr>
<tr class="even">
<td><img src="images/Dn292146.pubmethod(EXCHG.10).gif" title="Public method" alt="Public method" /></td>
<td><a href="dn351192(v=exchg.10).md">ToString</a></td>
<td>Returns a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf">String</a> that represents the current <a href="dn351191(v=exchg.10).md">Update</a>. (Overrides <a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2">Object.ToString()</a>.)</td>
</tr>
</tbody>
</table>


Top

## See also

#### Reference

[Update class](dn351191\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)
