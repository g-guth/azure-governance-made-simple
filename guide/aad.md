## Azure Active Directory

In order to begin to understand in more detail about the main services related to Azure Governance, it is important to start by talking about the relationship between Azure Active Directory (AAD) and subscriptions. It will not be covered all the details about it here since this is not the purpose of this document. However, here we will see the basics of how it works and the difference between Azure Active Directory (AAD) and Active Directory (AD).

AAD is the cloud-based identity and access management service that will allow you to grant access to users, groups and applications on Azure services as well as allowing you to define how they will use Azure resources through the functions that you will assign to them. In this way, it will take on the role of managing authorization and authentication for Azure services.

When creating an Azure subscription, an AAD tenant is automatically created. The tenant is nothing more than the representation of your company's domain within Azure Active Directory. Note that by default you will always get a name.onmicrosoft.com that you can then customize for yourdomain.com.
Within your AAD tenant you will have your AAD directory which is where you will create your users and groups. Note that you can also sync your existing users in your existing Active Directory to Azure Active Directory via Azure AD Connect, but this topic will not be covered here.

So basically, the main difference from Active Directory to Azure Active Directory is that AAD aims to work exclusively on the authorization and authentication of its users, groups and applications in Azure services. In contrast, Active Directory performs authorization and authentication in the on-premises environment in addition to many other tasks such as managing GPOS and Windows servers. In [this link](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-compare-azure-ad-to-ad) there is a broader comparison between them.

### Pro tip!

✔️ [Azure AD Identity Governance](https://docs.microsoft.com/en-us/azure/active-directory/governance/identity-governance-overview)
<br>
✔️[Azure AD access reviews](https://docs.microsoft.com/en-us/azure/active-directory/governance/access-reviews-overview)

---

Previous| Next | 
:----- |:-----
[Governance architecture in Azure](/guide/aad.md)| [Naming Standards](/guide/naming.md)
