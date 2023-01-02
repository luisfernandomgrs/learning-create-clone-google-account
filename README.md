Exercise from:
https://www.youtube.com/watch?v=sNO7jYLqX-M&t=224s

-----------------------------------------------------------------------

npx create-react-app google-singup-page

npm install -g npm@9.2.0 

npm run start

font: 
Google search to: material ui npm install
:: https://mui.com/material-ui/getting-started/installation/
npm install @mui/material @emotion/react @emotion/styled
npm install @mui/material @mui/styled-engine-sc styled-components



font:
Google search to: material ui text field
:: https://mui.com/material-ui/react-text-field/

Click at... "show the full source"
import * as React from 'react';
import Box from '@mui/material/Box';
import TextField from '@mui/material/TextField';

export default function BasicTextFields() {
  return (
    <Box
      component="form"
      sx={{
        '& > :not(style)': { m: 1, width: '25ch' },
      }}
      noValidate
      autoComplete="off"
    >
      <TextField id="outlined-basic" label="Outlined" variant="outlined" />
      <TextField id="filled-basic" label="Filled" variant="filled" />
      <TextField id="standard-basic" label="Standard" variant="standard" />
    </Box>
  );
}


font:
Google search to: material ui checkbox
:: https://mui.com/material-ui/react-checkbox/

font:
Google search to: material ui button
:: https://mui.com/material-ui/react-button/


![image](https://user-images.githubusercontent.com/72364037/210190064-1a238c2c-ac5d-4006-bc8a-1fe3b1fa93e1.png)

