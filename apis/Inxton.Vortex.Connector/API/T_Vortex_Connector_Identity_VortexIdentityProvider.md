# VortexIdentityProvider Class
 

Provides access to the objects by their identities.


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">System.Object</a><br />&nbsp;&nbsp;Vortex.Connector.Identity.VortexIdentityProvider<br />
**Namespace:**&nbsp;<a href="N_Vortex_Connector_Identity.md">Vortex.Connector.Identity</a><br />**Assembly:**&nbsp;Vortex.Connector (in Vortex.Connector.dll) Version: 1.3.12+Branch.tags-v1.3.12.Sha.00bdfb8be9e078a68c552d3a1d81a8775d48ab55

## Syntax

**C#**<br />
``` C#
public class VortexIdentityProvider
```

The VortexIdentityProvider type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Vortex_Connector_Identity_VortexIdentityProvider__ctor.md">VortexIdentityProvider</a></td><td>
Creates an instance of</td></tr></table>&nbsp;
<a href="#vortexidentityprovider-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Vortex_Connector_Identity_VortexIdentityProvider_Identities.md">Identities</a></td><td>
Get dictionary of identities.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Vortex_Connector_Identity_VortexIdentityProvider_IdentitiesCount.md">IdentitiesCount</a></td><td>
Get count of identities.</td></tr></table>&nbsp;
<a href="#vortexidentityprovider-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Vortex_Connector_Identity_VortexIdentityProvider_AddIdentity.md">AddIdentity</a></td><td>
Adds vortexer object to the list of identities.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.finalize#System_Object_Finalize" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank">GetHashCode</a></td><td>
Serves as the default hash function.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Vortex_Connector_Identity_VortexIdentityProvider_GetVortexerByIdentity.md">GetVortexerByIdentity(Object)</a></td><td>
Gets vortexer object by identity, if the object implements <a href="T_Vortex_Connector_Identity_IVortexIdentity.md">IVortexIdentity</a>. If object does not implements <a href="T_Vortex_Connector_Identity_IVortexIdentity.md">IVortexIdentity</a> the same object is returned.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Vortex_Connector_Identity_VortexIdentityProvider_GetVortexerByIdentity_1.md">GetVortexerByIdentity(UInt64)</a></td><td>
Gets vortexer object by identity.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Vortex_Connector_Identity_VortexIdentityProvider_GetVortexerByIdentity_2.md">GetVortexerByIdentity(IVortexIdentity)</a></td><td>
Gets vortexer object by identity.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.memberwiseclone#System_Object_MemberwiseClone" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">Object</a>.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Vortex_Connector_Identity_VortexIdentityProvider_ReadIdentities.md">ReadIdentities</a></td><td>
Reads vortex objects identities.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Vortex_Connector_Identity_VortexIdentityProvider_RefreshIdentities.md">RefreshIdentities</a></td><td>
Refreshes and sorts identities.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Vortex_Connector_Identity_VortexIdentityProvider_SortIdentities.md">SortIdentities</a></td><td>
Sorts identities.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#vortexidentityprovider-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Vortex_Connector_Identity.md">Vortex.Connector.Identity Namespace</a><br />