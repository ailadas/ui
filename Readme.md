import {Button, ThemeProvider} from '@sanity/ui'
import {buildTheme} from '@sanity/ui/theme'
import {createRoot} from 'react-dom/client'

const root = createRoot(document.getElementById('root'))
const theme = buildTheme()

root.render(
  <ThemeProvider theme={theme}>
    <Button text="Hello, world" />
  </ThemeProvider>,
)
