---
title: リポジトリのアーカイブで Git LFS オブジェクトを管理する
shortTitle: 'アーカイブにある {{ site.data.variables.large_files.product_name_short }} オブジェクトを管理する'
intro: '{{ site.data.variables.large_files.product_name_long }}（{{ site.data.variables.large_files.product_name_short }}）オブジェクトを、{{ site.data.variables.product.product_name }} がリポジトリ用に作成する ZIP ファイルや tarball などのソースコードアーカイブに含めるかどうかを選択できます。'
permissions: 'リポジトリの管理者権限を持つユーザは、{{ site.data.variables.large_files.product_name_short }} オブジェクトがリポジトリのアーカイブに含まれているかどうかを管理できます。'
versions:
  free-pro-team: '*'
  enterprise-server: '=>2.23'
---

### アーカイブにある {{ site.data.variables.large_files.product_name_short }} オブジェクトについて

{{ site.data.variables.product.product_name }} は、ZIP ファイルと tarball 形式でリポジトリのソースコードアーカイブを作成します。 これらのアーカイブは、リポジトリのメインページ、またはリリースアセットとしてダウンロードできます。 デフォルトでは、{{ site.data.variables.large_files.product_name_short }} オブジェクトはこれらのアーカイブに含まれず、これらのオブジェクトへのポインタファイルのみが含まれます。 代わりに {{ site.data.variables.large_files.product_name_short }} オブジェクトを含めて、リポジトリのアーカイブを使いやすくすることもできます。

リポジトリのアーカイブに {{ site.data.variables.large_files.product_name_short }} オブジェクトを含めた場合、それらのアーカイブをダウンロードするたびに、アカウントの帯域幅の使用量にカウントされます。 各アカウントには、毎月無料で {{ site.data.variables.large_files.initial_bandwidth_quota }} の帯域幅が付与され、追加使用分に対して支払うことができます。 詳しい情報については、「[ストレージと帯域の利用について](/github/managing-large-files/about-storage-and-bandwidth-usage)」および「[{{ site.data.variables.large_files.product_name_long }} の支払いを管理する](/github/setting-up-and-managing-billing-and-payments-on-github/managing-billing-for-git-large-file-storage)」を参照してください。

### アーカイブにある {{ site.data.variables.large_files.product_name_short }} オブジェクトを管理する

{{ site.data.reusables.repositories.navigate-to-repo }}
{{ site.data.reusables.repositories.sidebar-settings }}
3. [Archives] で、[**Include {{ site.data.variables.large_files.product_name_short }} objects in archives**] を選択または選択解除します。 ![アーカイブにある {{ site.data.variables.large_files.product_name_short }} オブジェクトを含めるチェックボックス](/assets/images/help/repository/include-git-lfs-objects-checkbox.png)