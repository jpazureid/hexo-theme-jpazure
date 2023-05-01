# hexo-theme-jpazure

hexo theme for jpazure tech blog

> forked from [hexo-theme-landscape](https://github.com/hexojs/hexo-theme-landscape)

## Set Up

```sh
git clone https://github.com/jpazureid/hexo-theme-jpazure.git themes/jpazure
npm i -D hexo-generator-feed
npm i -D jpazureid/hexo-helper-github-issues hexo-generator-root-tag
```

## hexo config.yml


```yml
root_tag_generator:
  root_tag_names:
    - Azure AD
    - AAD Connect
    - AD FS
    - 情報採取
  sub_tag_limit: 20
  
github:
  url: https://github.com/jpazureid/blog/
  posts_dir: articles
  default_branch: main
  show_additional_info: true

# https://hexo.io/docs/helpers#toc
toc:
  # if true, toc will be auto display in all article which has more than one h2 tag
  enabled: false
  min_depth: 1
  max_depth: 4
  list_number: false


# show disclaimer in all article by default. disableDisclaimer of article's option set true hide.
# ex) 
# ---
# title: Article Title
# date: 2020-04-30 10:00
# disableDisclaimer: true
# ---
disclaimer: ※本情報の内容（添付文書、リンク先などを含む）は、作成日時点でのものであり、予告なく変更される場合があります。  
```
