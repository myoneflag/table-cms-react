# Table-CMS-React

> Build simple table with @antd-table

## ✨ Features

-   [x] Define column and row count
-   [x] Support custom render.

## Install

```bash
yarn add table-cms-react
npm install table-cms-react
```

## Usage

**[Full tutorial](https://github.com/myoneflag/table-cms-react)**

```tsx
import React, { Component } from 'react'

import { TableCms, TableRender } from 'table-cms-react'
// cms
const Example = () => {
    return (
	  <TableCms
	  	defaultSize={
			column: 3,
			row: 3
		}
		onChange={(data) => console.log(data)}
     />
  );
}
// render
const Example = () => {
    return (
	  <TableRender
	  	data={data}
     />
  );
}
```
## Props
	 defaultSize
	 onChange
	 data


## License

MIT © 2020 

- [myoneflag](https://github.com/myoneflag)

