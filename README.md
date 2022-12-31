
# Pagination Component for Vue.js
A  pagination  component  for  Vue.js  that  allows  you  to  easily  add  pagination  to  your  app.

## Installation
To  install  the  component,  run  the  following  command:
```bash
$ npm install vue3-pagination-component
```

## Usage
To  use  the  component,  import  it  into  your  Vue.js  app  and  add  it  to  your  template:

```js
<template>
  <pagination-component v-model="currentPage" :total="totalPages" :per-page="15"/>
</template>

<script>
import PaginationComponent from 'vue3-pagination-component'
export default  {
  components: {
    PaginationComponent
  },
  data ()  {
    return  {
      totalPages: 10
    }
  },
}
</script>
```

## Props
- `total`: The total number of pages to display in the pagination component.
- `per-page`: (Optional) The number of items to display per page. Default is 15.

## License
This component is open source and released under the MIT License.
