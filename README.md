
install with NPM
npm install @fortawesome/fontawesome-svg-core @fortawesome/free-solid-svg-icons @fortawesome/react-fontawesome @fortawesome/free-brands-svg-icons

add this to _app.tsx
import '@/components/fontawsome/fontawsome';


Import file to your Component
//fontawsome 
import Icon from '@/components/fontawsome/Icon';
import { faCoffee } from '@fortawesome/free-solid-svg-icons';
import { faLinkedin } from '@fortawesome/free-brands-svg-icons';


Add to functional part of your component
Nothing

Add to return part
<Icon
icon={faSkype}
color="red"
size="20px"
margin="0px"
mouseOverColor="blue"
/>
