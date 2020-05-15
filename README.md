表格搜索区的下拉选择框的多选配置，两种方式  
1 
```
{
  label: '下拉多选1',
  prop: 'checkbox1',
  component: 'input',
  type:'tree',
  search: true,
  searchMultiple: true,
  dicData: []            
}
```
2
```
{
  label: '下拉多选2',
  prop: 'checkbox2',
  type: 'select',
  search: true,
  searchMultiple: true,
  searchFilterable: true,
  dicData: []
}
```

--------------
node版本 9.11.2