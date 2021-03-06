---
title: 管理组织的复刻政策
intro: '您可以允许或阻止对组织拥有的任何私有{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.19" or currentVersion == "github-ae@latest" %} 和内部{% endif %} 仓库进行复刻。'
redirect_from:
  - /articles/allowing-people-to-fork-private-repositories-in-your-organization
  - /github/setting-up-and-managing-organizations-and-teams/allowing-people-to-fork-private-repositories-in-your-organization
  - /github/setting-up-and-managing-organizations-and-teams/managing-the-forking-policy-for-your-organization
permissions: Organization owners can manage the forking policy for an organization.
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
topics:
  - Organizations
  - Teams
---

默认情况下，新的组织被配置为禁止复刻私有{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.19" or currentVersion == "github-ae@latest" %} 和内部{% endif %} 仓库。

如果您在组织级别上允许复刻私有{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.19" or currentVersion == "github-ae@latest" %} 和内部{% endif %} 仓库，则还可以配置复刻特定{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.19" or currentVersion == "github-ae@latest" %} 或内部{% endif %} 仓库的权限。 更多信息请参阅“[管理仓库的复刻政策](/github/administering-a-repository/managing-the-forking-policy-for-your-repository)”。

{% data reusables.organizations.internal-repos-enterprise %}

{% data reusables.profile.access_profile %}
{% data reusables.profile.access_org %}
{% data reusables.organizations.org_settings %}
{% data reusables.organizations.member-privileges %}
5. 在“Repository forking（仓库复刻）”下，选择 **Allow forking of private repositories（允许复刻私有仓库）**或 **Allow forking of private and internal repositories（允许复刻私有和内部仓库）**。 ![允许或禁止组织复刻的复选框](/assets/images/help/repository/allow-disable-forking-organization.png)
6. 单击 **Save（保存）**。

### 延伸阅读

- "[关于复刻](/articles/about-forks)"
- "[组织的仓库权限级别](/articles/repository-permission-levels-for-an-organization)"
