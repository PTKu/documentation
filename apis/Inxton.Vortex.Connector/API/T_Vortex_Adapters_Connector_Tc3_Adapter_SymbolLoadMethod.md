# SymbolLoadMethod Enumeration
 

Enumerates symbol loading methods.

**Namespace:**&nbsp;<a href="N_Vortex_Adapters_Connector_Tc3_Adapter.md">Vortex.Adapters.Connector.Tc3.Adapter</a><br />**Assembly:**&nbsp;Vortex.Adapters.Connector.Tc3 (in Vortex.Adapters.Connector.Tc3.dll) Version: 1.3.12+Branch.tags-v1.3.12.Sha.00bdfb8be9e078a68c552d3a1d81a8775d48ab55

## Syntax

**C#**<br />
``` C#
public enum SymbolLoadMethod
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Vortex.Adapters.Connector.Tc3.Adapter.SymbolLoadMethod.SymbolInfoReader">**SymbolInfoReader**</td><td>0</td><td>Using symbol info loader.
&nbsp;<table><tr><th>![Note](media/AlertNote.png) Note</th></tr><tr><td>Generally faster method for on the fly loading of the symbols.</td></tr></table></td></tr><tr><td /><td target="F:Vortex.Adapters.Connector.Tc3.Adapter.SymbolLoadMethod.SymbolInfoLoader">**SymbolInfoLoader**</td><td>1</td><td>Using symbol info reader.
&nbsp;<table><tr><th>![Note](media/AlertNote.png) Note</th></tr><tr><td>Generally slower method suitable for small-mid size applications.</td></tr></table></td></tr></table>

## See Also


#### Reference
<a href="N_Vortex_Adapters_Connector_Tc3_Adapter.md">Vortex.Adapters.Connector.Tc3.Adapter Namespace</a><br />