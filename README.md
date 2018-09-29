# blogs
issueで管理するブログのあれ(予定)

## query
```
query { 
  repository(owner: "shilfol", name: "blogs"){
    name,
    description,
    issues(first:10){
      totalCount,
      edges{
        node{
          title,
          body
        }
      }
    }
  }
}
```
