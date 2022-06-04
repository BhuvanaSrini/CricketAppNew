# CricketAppNew
```
           var alldata = [
            { id: 1, tag: "sor3" },
            { id: 2, tag: "dd,de34" },
            { id: 2, tag: "test,de34" }
          
          ];
          var multiSelectUC = ["sor",'test'];
          var casesWithDocumentAndTag = alldata.filter((o) => {
            return multiSelectUC.filter((item) => o.tag.split(',').includes(item)).length > 0;
          });
          
          console.log(casesWithDocumentAndTag);
```
