# IVortexElement Interface
 

Basic contract for any type that is product of building process.

**Namespace:**&nbsp;<a href="N_Vortex_Connector.md">Vortex.Connector</a><br />**Assembly:**&nbsp;Vortex.Connector (in Vortex.Connector.dll) Version: 1.3.12+Branch.tags-v1.3.12.Sha.00bdfb8be9e078a68c552d3a1d81a8775d48ab55

## Syntax

**C#**<br />
``` C#
public interface IVortexElement
```

The IVortexElement type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Vortex_Connector_IVortexElement_AttributeName.md">AttributeName</a></td><td>
Gets Name of this instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Vortex_Connector_IVortexElement_HumanReadable.md">HumanReadable</a></td><td>
Provides a string combined from <a href="P_Vortex_Connector_IVortexElement_AttributeName.md">AttributeName</a> of ancestors (<a href="M_Vortex_Connector_IVortexElement_GetParent.md">GetParent()</a>) of this instance and the tail of this instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Vortex_Connector_IVortexElement_Symbol.md">Symbol</a></td><td>
Get symbol of this instance.</td></tr></table>&nbsp;
<a href="#ivortexelement-interface">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Vortex_Connector_IVortexElement_GetParent.md">GetParent</a></td><td>
Gets the parent object of this instance. Parent object is the object that created this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Vortex_Connector_IVortexElement_GetSymbolTail.md">GetSymbolTail</a></td><td>
Get symbol tail of this instance.</td></tr></table>&nbsp;
<a href="#ivortexelement-interface">Back to Top</a>

## See Also


#### Reference
<a href="N_Vortex_Connector.md">Vortex.Connector Namespace</a><br />