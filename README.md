<style>


.container .column a:hover img {
    opacity: 0.7; 
}

.container .column a {
    position: relative;
}

.container .column a:hover::after {
    content: attr(title);  
    position: absolute;
    top: 50%;   
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: rgba(0, 0, 0, 0.7);  
    color: #f6f0ff;  
    padding: 5px 10px; 
    border-radius: 5px;  
    font-size: 14px;  
    white-space: nowrap; 
    opacity: 0;
    visibility: hidden;
    transition: opacity 0.3s, visibility 0.3s;  
}

.container .column a:hover::after {
    opacity: 1;
    visibility: visible; 
}
        .container {
            display: flex;
            justify-content: space-around; 
            align-items: center; 
        }
        .column {
            flex: 1; 
            padding: 5px; 
        }
        .column:hover {
  margin-top: -5px;
  transition: 0.5s;
}






.profile-page-flex {
  flex-direction: column !important;
  flex-wrap: nowrap;
}

.profile-page-flex > div:not(.css-1747r9t) {
  max-width: unset;
  padding-left: 0;
  padding-right: 0;
}


.profile-page-flex > div,
.profile-page-flex > div > div {
  background: transparent;
}



.profile-page-flex > div:hover {
  box-shadow: none;
}

.css-8g8ihq:only-child {
  align-items: center;
}


.css-1uodvt1 {
  order: -2;
  perspective: 1000px;
  transform-style: preserve-3d;
  display: flex;
  flex-flow: row nowrap;
  justify-content: center;
  position: relative;
  width: 100%;
  aspect-ratio: 1 / 1;
  height: 100%;
  min-height: 330px;
  max-height: 500px;
  max-width: 40rem;
  margin-bottom: calc(80px + 5rem);
}



div:has(> .pp-uc-avatar),
.css-1uodvt1::after {
  position: relative;
  content: "";
  flex: 0 1 48%;
  max-width: 48%;
  height: 100%;
  aspect-ratio: 1 / 2;
  top: 0;
  border-radius: 0.5rem;
  border: 2px solid #d8c6f4;
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
  animation: rotate3d 20s infinite;
  overflow: hidden;
}

@keyframes rotatecard1 {
  0%, 100% { transform: translate3d(0, -6px, 25px) rotate(-3deg); }
  25% { transform: translate3d(56%, 4px, 0) rotate(4deg); }
  50% { transform: translate3d(0, -7px, -25px) rotate(-3deg); }
  75% { transform: translate3d(-56%, 7px, 0) rotate(3deg); }
}

@keyframes rotatecard2 {
  0%, 100% { transform: translate3d(0, 8px, -25px) rotate(3deg); }
  25% { transform: translate3d(-56%, -4px, 0) rotate(-1deg); }
  50% { transform: translate3d(0, 4px, 25px) rotate(3deg); }
  75% { transform: translate3d(56%, -5px, 0) rotate(-2deg); }
}

.css-1uodvt1::after {
  right: 25%;
  height: calc(100% - 4px);
  width: calc(48% - 4px);
  background:
    radial-gradient(circle at 50% 50%, #51446a 0 25px, transparent 26px 100%),
    radial-gradient(circle at 50% 100%, #51446a 0 calc(25% - 1px), transparent calc(25% + 1px) 100%),
    radial-gradient(circle at 50% 0%, #51446a 0 calc(16% - 1px), transparent calc(16% + 1px) 100%),
    repeating-radial-gradient(circle at 50% 50%, transparent 0 24px, #51446a 25px 26px, transparent 27px),
    radial-gradient(circle at 0% 0%, #51446a 10px, transparent 11px),
    radial-gradient(circle at 0% 100%, #51446a 10px, transparent 11px),
    radial-gradient(circle at 100% 0%, #51446a 10px, transparent 11px),
    radial-gradient(circle at 100% 100%, #51446a 10px, transparent 11px)
    #0f0714;
  background-size: 100%;
  border-color: #51446a;
  animation: rotatecard2 20s infinite;
}


.css-8g8ihq:not(:only-child) {
  position: absolute;
  width: 100%;
  height: auto;
  bottom: -5rem;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  gap: 0;
  transform: translateZ(26px);
}

.css-8g8ihq:not(:only-child)::before {
  position: absolute;
  content: "";
  background: #0f0714;
  border: 2px solid #d8c6f4;
  border-radius: 99% 0;
  transform: translateY(-6rem) rotate(45deg);
  width: 8rem;
  height: 8rem;
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
  
}

.css-8g8ihq:not(:only-child)::after {
  position: absolute;
  content: "";
  background: radial-gradient(circle at 50% 50%, #d8c6f4 0 22%, transparent calc(22% + 2px) 100%);
  background-position: 50% 50%;
  background-size: 200% 200%;
  border: 2px solid #d8c6f4;
  border-radius: 50%;
  width: 4rem;
  height: 4rem;
  box-shadow: inset 0 0 0 1rem #d8c6f4;
  animation: eye 10s infinite;
  transform: translateY(-6rem);
}


.css-8g8ihq:not(:only-child) > * {
  z-index: 2;
}




div:has(> .pp-uc-avatar) {
  left: 25%;
  animation: rotatecard1 20s infinite;
}

.pp-uc-avatar {
  min-height: 100%;
  min-width: 100%;
  object-fit: cover;
  box-shadow: none;
}


.css-70qvj9 h2,
.css-70qvj9 + div {
  text-align: center;
  position: relative;
  width: 100%;
  font-family: Cardo;
}

.css-70qvj9 h2 {
  display: flex;
  flex-flow: column nowrap;
  
  
  font-size: 0;
  width: 100vw;
  background: #0f0714;
  border-top: 2px solid #d8c6f4;
  border-bottom: 2px solid #d8c6f4;
}


.css-70qvj9 h2::after {
  content: "✧Leia Nord✧";
  font-size: 3.5rem;
  font-weight: 500;
  font-style: Italic;
  letter-spacing: -2px;
  line-height: 0.9;
}

.css-70qvj9 h2::before {
  content: " °˖✧◝(⁰▿⁰)◜✧˖°  ";
  font-family: 'DM Serif Text', serif;
  font-size: 1rem;
  font-weight: 500;
}


.css-70qvj9 + div {
  position: relative; 
  align-self: flex-start; 
  bottom: -40px;
  word-spacing: 60px; 
  background: linear-gradient(90deg, #f6f0ff 80px, transparent 80px 100%); 
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-wrap: nowrap;
  font-family: Cardo; 
  font-size: 1.25rem;
  
  width: auto;
  left: 4.375rem;
  margin-inline: auto;
}

.css-70qvj9 + div::after {
  background: #f6f0ff; 
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  word-spacing: 0;
  content: "Readings Performed";
  position: relative;
  left: -8.75rem; 
}


.css-hjkukh {
  position: absolute;
  bottom: -80px;
  width: 100%;
  height: auto;
  justify-content: center;
  filter: sepia(1) brightness(1.2) saturate(1.5) hue-rotate(45deg);
}



.css-hjkukh + div {
  display: none;
}




.css-fdshcw {
  order: -1;
}


.css-y9k5u7 {
  justify-content: center;
}


.Btn {
  background: #d8c6f4;
  border-radius: 32px;
  transition: all 500ms !important;
  overflow: visible;
  outline: 0px solid transparent;
  outline-offset: 0px;
}

.Btn::before {
  display: none;
}

.Btn span {
  font-size: 0;
  width: auto;
}

.Btn span::after {
  font-size: 1rem;
  font-family: 'DM Serif Text';
  font-weight: 700;
  color: #0b0830;
  content: "Follow Fate";
  transition: color 500ms;
}

.Btn[data-following=true] span::after {
  font-size: 1rem;
  font-family: 'DM Serif Text';
  font-weight: 700;
  color: #0b0830;
  content: "Deny Fate";
}

.Btn:active {
  transform: scale(0.9);
  background: #0b0830;
  color: #d8c6f4 !important;
  outline: 2px solid #d8c6f4;
  outline-offset: -2px;
}

.Btn:active span::after,
.css-y9k5u7 .css-15w88gn:active span::after {
  color: #d8c6f4 !important;
}



.sonner-toast-container [data-sonner-toast][data-type=success] {
  background:
    radial-gradient(circle at 50% 50%, #51446a 0 22px, transparent 24px 100%),
    radial-gradient(circle at 0% 50%, #51446a 0 40px, transparent 42px 100%),
    radial-gradient(circle at 100% 50%, #51446a 0 40px, transparent 42px 100%),
    repeating-radial-gradient(circle at 50% 50%, transparent 0 21px, #51446a 22px 24px, transparent 25px) !important;
  background-color: #0f0714 !important;
  background-size:
    100%,
    100%,
    100%,
    100% !important;
  border: 2px solid #51446a !important;
  border-radius: 0.5rem !important;
  outline: 1px solid #d8c6f4 !important;
  outline-offset: 2px;
  color: #f6f0ff !important;
  font-family: Cardo !important;
  font-weight: 700 !important;
  padding: 0.75rem;
  margin-bottom: 0;
}

.sonner-toast-container [data-sonner-toast][data-type=success] [data-icon] {
  color: #d8c6f4 !important;
}



.css-y9k5u7 .css-15w88gn {
  background: #d8c6f4;
  color: #0b0830;
  font-family: 'DM Serif Text';
  border-radius: 32px;
  outline: 0px solid transparent;
  outline-offset: 0px;
  transition: all 500ms;
}

.css-y9k5u7 .css-15w88gn:active {
  transform: scale(0.9);
  background: #0b0830;
  outline: 2px solid #d8c6f4;
  outline-offset: -2px;
}



.css-y9k5u7 .css-15w88gn span {
  font-size: 0;
  visibility: hidden;
}

.css-y9k5u7 .css-15w88gn span:last-child {
  display: none;
}

.css-15w88gn:not(.css-y9k5u7 .css-15w88gn) {
  z-index: 10000;
}



.css-y9k5u7 .css-15w88gn span:first-child::after {
  font-family: 'DM Serif Text';
  visibility: visible;
  font-weight: 700;
  font-size: 1rem;
  color: #0b0830;
  content: "Threads";
  transition: color 500ms;
}



.css-bp2fv5 { padding: 0; background: transparent; box-shadow: none !important; }


.css-bp2fv5 > button {
  color: #d8c6f4;
  background: #0b0830 !important;
  padding: 0;
  margin: 0;
  height: 2.5rem;
  border-radius: 32px;
  transition: all 500ms;
}

.css-bp2fv5 > button:active {
  transform: scale(0.9)
}


.css-7halv9 {
  margin: 0;
  font-size: 1rem;
  width: 2.5rem;
  height: 2.5rem;
}


.css-bp2fv5 span + span {
  font-size: 0;
  font-family: 'DM Serif Text';
  font-weight: 700;
}

.css-bp2fv5 span + span::after {
  font-size: 1rem;
  content: "Forge your own path";
}



.css-1mlpyf4 {
  padding: 1rem;
}

.css-1mlpyf4 > section {
  padding: 0;
  color: #f6f0ff !important;
  background:
    radial-gradient(circle at 50% 50%, #51446a 0 22px, transparent 24px 100%),
    radial-gradient(circle at 0% 50%, #51446a 0 80px, transparent 82px 100%),
    radial-gradient(circle at 100% 50%, #51446a 0 80px, transparent 82px 100%),
    repeating-radial-gradient(circle at 50% 50%, transparent 0 21px, #51446a 22px 24px, transparent 25px) !important;
  background-color: #0f0714 !important;
  background-size:
    100%,
    100%,
    100%,
    100% !important;
  border: 2px solid #51446a;
  border-radius: 0.5rem !important;
  outline: 1px solid #d8c6f4 !important;
  outline-offset: 2px;
  font-family: Cardo;
  font-weight: 700;
}


.css-1mlpyf4 header {
  font-family: 'DM Serif Text';
  font-size: 0;
  font-weight: 500;
}

.css-1mlpyf4 header::after {
  font-size: 2rem;
  content: "Block this creator?";
}


.css-1mlpyf4 > section > div {
  font-size: 0;
}

.css-1mlpyf4 > section > div::before {
  font-size: 1rem;
  content: "You will never see my tarot cards again. You can unblock them later through the ";
}

.css-1mlpyf4 > section > div > a::after {
  color: #d8c6f4;
  font-size: 1rem;
  content: "Blocks menu.";
}

.css-1mlpyf4 > section > div > a:hover {
  text-underline-offset: 2px;
  text-decoration: underline 2px #d8c6f4;
}

.css-1mlpyf4 button {
  font-family: 'DM Serif Text';
  color: #d8c6f4;
  border-radius: 32px;
  font-weight: 700;
}

.css-1mlpyf4 > section > footer {
  padding: 20px;
}



.css-1mlpyf4 button:not(button + button) {
  background: #0b0830 !important;
}

.css-1mlpyf4 button + button {
  background: #d8c6f4 !important;
  color: #0b0830;
}


.status-box {
  margin-top: 0.5rem;
  background:
    radial-gradient(circle at 50% 50%, #51446a 0 14px, transparent 16px 100%),
    radial-gradient(circle at 0% 50%, #51446a 0 30px, transparent 32px 100%),
    radial-gradient(circle at 100% 50%, #51446a 0 30px, transparent 32px 100%);
  background-color: #0f0714;
  background-size:
    100%,
    100%,
    100%;
  border-radius: 0.5rem;
  position: relative;
  max-width: 50ch;
  width: 100%;
  margin-inline: auto;
  padding: 0.75rem;
  border: 2px solid #d8c6f4;
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
}

.status-title {
  position: absolute;
  top: 0;
  left: 0;
  transform: translateY(calc((100% + 3px) * -1));
}

.status-title h2 {
  color: #d8c6f4; 
  font: 400 3rem/0.7 Cardo, serif;
  font-variant: small-caps;
  height: auto;
  width: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}

.status-text {
  width: 100%;
  text-align: center;
  font: 400 1.25rem Cardo, serif;
}


.profile-about-me { display: flex; flex-flow: column; gap: 1rem; padding: 0; }

.about-box {
  background: #0f0714;
  border-radius: 0.5rem;
  position: relative;
  max-width: 50rem;
  width: 100%;
  margin: 0;
  padding: 0.75rem;
  border: 2px solid #d8c6f4;
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
}

.profile-about-me:not(:empty) {
  
}

h1, h2, h3, h4, h5, h6 {
  font-family: Cardo !important;
}



.disclaimer {
  font-family: Cardo;
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  justify-content: center;
  padding: 0 calc(1rem + 2px) 0 1rem;
  border-left: 2px solid #d8c6f4;
}







.pp-top-bar {
  backdrop-filter: unset;
  background:
    repeating-radial-gradient(circle at 50% 50%, #51446a 0 6px, transparent 8px 100%),
    repeating-radial-gradient(circle at 50% 50%, #51446a 0 16px, transparent 18px 100%),
    repeating-radial-gradient(circle at 50% 50%, transparent 0 30px, #51446a 32px 34px, transparent 36px)
    #0f0714;
  background-size:
    50% 100%,
    100%,
    100%;
  border-bottom: 2px solid #d8c6f4;
}


.pp-top-bar:has(.profile-top-bar-title) { height: 3rem; }

.profile-top-bar-title, .profile-top-bar-back-button p {
  font-size: 0;
  font-family: Cardo, serif;
  font-weight: light;
  font-style: Italic;
  letter-spacing: 0;
  text-shadow: none;
  color: #f6f0ff;
}

.profile-top-bar-title::before {
  font-style: normal;
  font-weight: bold;
  text-transform: uppercase;
  font-family: 'DM Serif Text', serif;
  font-size: 1rem;
  content: "Leia Nord";
}
.profile-top-bar-title::after {
  font-size: 1rem;
  content: "";
}



.profile-top-bar-back-button p::after {
  font-size: 1rem;
  content: " Return";
}


.profile-top-bar-back-button svg {
  display: none;
}



.profile-top-bar-back-button::before {
  font-size: 1rem;
  font-style: normal;
  content: "↶ ";
  color: #d8c6f4;
}


:has(> .profile-top-bar-back-button):hover {
  transition: all 500ms;
}

:hover > .profile-top-bar-back-button {
  transform: scale(1.05);
}



.glow-logo {
  color: #f6f0ff;
  background: transparent;
  border-radius: 0;
  box-sizing: border-box;
  border: none;
  transition: all 500ms;
  box-shadow: none;
  transform: scale(1.2);
}


.glow-logo h2, .glow-logo p {
  color: #f6f0ff;
  font-size: 0;
  font-family: 'DM Serif Text', serif;
  font-weight: bold;
  text-transform: uppercase;
  text-shadow: none;
  margin-bottom: 0;
}



.glow-logo h2::after {
  content: "Leia Nord";
  letter-spacing: ;
  text-wrap: nowrap;
  font-size: 1.5rem;
}


.glow-lgo p::after {
  content: "";
  font-size: 1.5rem;
  font-style: italic;
  padding-right: 3px;
  letter-spacing: ;
}

.glow-logo:hover {
  transform: scale(1.35);
  filter: none;
}

:is(.glow-logo, .css-vv3ja7, .css-55tioa):hover, .glow-logo:focus, css-vv3ja7[data-hover], .css-55tioa[data-hover] {
  color: #f6f0ff;
  text-shadow: unset;
}


.css-8uj2do {
  position: absolute;
  margin-inline: auto;
  width: fit-content;
  left: 0;
  right: 0;
}




.profile-top-bar-search-box input::placeholder {
  font-family: Cardo, serif !important;
  color: #d8c6f4BF;
  font-style: italic;
  font-size: 1.15rem;
  font-weight: 100;
  letter-spacing: -1px;
}

.css-bar9lc svg {
  color: #d8c6f4 !important;
}


.css-i6srjg {
  border-radius: 0;
  box-shadow: none;
  background: transparent;
}


.css-i6srjg > div {
  margin: ;
}


.css-i6srjg:hover {
  box-shadow: none;
}


.css-j1p8gu svg, .css-j1p8gu {
  transition: all 500ms;
}

.css-bar9lc .css-1y0e7gb {
  transition: all 500ms;
}


.css-bar9lc .css-1y0e7gb:hover {
  transform: scale(1.1);
}


.css-bar9lc .css-1y0e7gb:hover .css-j1p8gu {
  opacity: 1;
}


.css-bar9lc .css-1y0e7gb:hover .css-j1p8gu svg {
  color: #f6f0ff !important;
}


.css-bar9lc {
  order: -1;
  max-width: 20rem;
  margin-left: 0;
}


.css-fss3o9,
.css-lnyvlk,
.glow-on-hover  {
  display: none;
}


[aria-label="Global notifications"],
[aria-label="Notifications"],
.profile-top-bar-app-menu {
  background: #0b0830;
  outline: 2px solid transparent;
  position: relative;
  transform: unset;
  height: 2.5rem;
  border-radius: 50%;
  transition: all 500ms;
}

:is(
  [aria-label="Global notifications"],
  [aria-label="Notifications"]
) svg {
  color: #d8c6f4 !important;
  transition: all 500ms;
}

:is(
  [aria-label="Global notifications"],
  [aria-label="Notifications"],
  .profile-top-bar-app-menu
):is(:hover, :focus, :active) {
  background: #d8c6f4;
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
}

:is(
  [aria-label="Global notifications"],
  [aria-label="Notifications"],
  .profile-top-bar-app-menu
):is(:hover, :focus, :active) svg {
  color: #0b0830 !important;
}


.profile-top-bar-app-menu *:not(img) {
  display: contents;
}
.profile-top-bar-app-menu {
  padding: 0.25rem;
  transform: none;
}
.profile-top-bar-app-menu:is(:active, [data-active]) {
  background: none !important;
}
.profile-top-bar-app-menu img {
  border-radius: 50%;
}




.css-1qf4tpw {
  background: radial-gradient(ellipse at 25% 120%, #0b0830 calc(60% - 7px), #d8c6f4 calc(60% - 7px) 60%, transparent 60%);
  background-size: 200% 140%;
  box-shadow: none;
  backdrop-filter: unset;
}





.css-avv0po {
  align-items: center;
}

.css-1l8kxqv,
.css-dvxtzn {
  margin-bottom: 0;
  position: relative;
  height: 40px;
  width: 40px;
  border-radius: 50%;
  background: #d8c6f4;
  outline: 2px solid transparent;
  justify-content: center;
  transition: all 500ms;
}


a:hover .css-1l8kxqv {
  background: #0b0830;
  outline: 2px solid #d8c6f4;
  outline-offset: -2px;
  transform: translateY(-5px)
}

a:hover .css-1l8kxqv svg {
  color: #d8c6f4 !important;
}

.css-dvxtzn:hover {
  background: #0b0830;
  outline: 2px solid #d8c6f4;
  outline-offset: -2px;
  transform: translateY(-5px);
}


.css-1l8kxqv svg {
  color: #0b0830 !important;
  transition: color 500ms;
}



.css-1khhiw8 {
  filter: sepia(1) hue-rotate(145deg) saturate(2);
}



a:first-child:has(.css-1l8kxqv) {
  position: relative;
  top: -9px;
}

a:nth-child(2):has(.css-1l8kxqv) {
  top: -12px; 
  position: relative;
}

a:nth-child(3):has(.css-1l8kxqv) {
  top: -12px;
  position: relative;
}

.css-dvxtzn {
  top: -9px;
}



[class*="Popover_"] svg {
  color: #d8c6f4 !important;
}


[class*="Popover_"]  {
  background:
    radial-gradient(circle at 50% 50%, #51446a 0 25px, transparent 26px 100%),
    radial-gradient(circle at 50% 100%, #51446a 0 calc(25% - 1px), transparent calc(25% + 1px) 100%),
    radial-gradient(circle at 50% 0%, #51446a 0 calc(16% - 1px), transparent calc(16% + 1px) 100%),
    repeating-radial-gradient(circle at 50% 50%, transparent 0 24px, #51446a 25px 26px, transparent 27px),
    radial-gradient(circle at 0% 0%, #51446a 10px, transparent 11px),
    radial-gradient(circle at 0% 100%, #51446a 10px, transparent 11px),
    radial-gradient(circle at 100% 0%, #51446a 10px, transparent 11px),
    radial-gradient(circle at 100% 100%, #51446a 10px, transparent 11px)
    #0f0714;
  background-size:
    100%;
  padding-top: 0;
  border-radius: 0.5rem;
  border: 2px solid #51446a;
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
  box-shadow: none;
  font-family: Cardo, serif;
}

[class*="_loadingSpinner_"] {
  border: 3px solid #f6f0ff40;
  border-top: 3px solid #f6f0ff; 
}
 

[class*="_loadingMessage_"] {
  color: #f6f0ff;
  font-family: 'Cardo';
}

[class*="notificationsList_"] {
  max-height: 480px;
  padding: 0 0.5rem;
  display: flex;
  flex-flow: column nowrap;
  gap: 0.5rem;
}


[class*="notificationsList_"]::-webkit-scrollbar-thumb {
  background: #d8c6f4 !important;
  border-radius: 16px !important;
}


[class*="popoverHeader_"] {
  padding: 1rem 1.25rem;
  border-bottom: 1px solid #d8c6f4;
  background: transparent;
}


[class*="popoverTitle_"] {
  font-size: 1.5rem;
  font-family: Cardo, serif;
  color: #f6f0ff !important;
  font-style: Italic;
  font-weight: normal;
  letter-spacing: ;
}



[class*="_notificationItem_"] {
  outline: 0px solid transparent;
  background: #0b0830;
  border-radius: 0.5rem;
}


[class*="_characterAvatar_"],
[class*="_userAvatar_"],
[class*="_notificationIconContainer_"] {
  border-radius: 999px;
}


[class*="_notificationItem_"]:hover {
  outline: 2px solid #d8c6f4;
  background: #0b0830;
}


[class*="_notificationTitle_"],
[class*="_subject_"] {
  color: #f6f0ff;
  background: unset;
  -webkit-background-clip: unset;
  -webkit-text-fill-color: unset;
  background-clip: unset;
}


[class*="_notificationMessage_"],
[class*="_body_"] {

}


[class*="_notificationTime_"],
[class*="_timestamp_"] {
  color: #d8c6f4;
  font-family: ;
}


[class*="_notificationItem_"]:has([class*="_unreadIndicator_"]) {
  
}


[class*="Indicator_"]:empty {
  background-image: unset; 
  background: #f6f0ff;
  transition: all 500ms;
}


[class*="_notificationItem_"]:hover [class*="Indicator_"] {
  background: #d8c6f4;
}


[class*="_loadMoreButton_"] {
  background: #0b0830;
  color: #d8c6f4;
  border-top: 1px solid;
  font-family: 'DM Serif Text', serif;
  font-size: 1.25rem;
  font-style: ;
  letter-spacing: ;
  outline: 0px solid transparent;
  transition: all 500ms;
}


[class*="_loadMoreButton_"]:is(:hover, :active) {
  background: #d8c6f4;
  color: #0b0830;
  border-top: 1px solid;
  box-shadow: none;
}


[type="button"] svg + :is(div, span) {
  background: #d8c6f4;
  color: #0b0830;
  outline: #0b0830 2px solid;
  transition: all 500ms;
}


[type="button"]:is(hover, :focus, :active) > svg + :is(div, span) {
  background: #0b0830;
  color: #d8c6f4;
  outline: #d8c6f4 2px solid;
}




.pp-top-bar-app-menu-list > div { display: contents; }

.pp-top-bar-app-menu-list {
  display: flex;
  flex-flow: column nowrap;
  gap: 0.5rem;
  height: auto;
  max-height: unset;
  overflow: unset;
  margin: 0;
  padding: 1rem;
  background:
    radial-gradient(circle at 50% 50%, #51446a 0 25px, transparent 26px 100%),
    radial-gradient(circle at 50% 100%, #51446a 0 calc(25% - 1px), transparent calc(25% + 1px) 100%),
    radial-gradient(circle at 50% 0%, #51446a 0 calc(16% - 1px), transparent calc(16% + 1px) 100%),
    repeating-radial-gradient(circle at 50% 50%, transparent 0 24px, #51446a 25px 26px, transparent 27px),
    radial-gradient(circle at 0% 0%, #51446a 10px, transparent 11px),
    radial-gradient(circle at 0% 100%, #51446a 10px, transparent 11px),
    radial-gradient(circle at 100% 0%, #51446a 10px, transparent 11px),
    radial-gradient(circle at 100% 100%, #51446a 10px, transparent 11px)
    #0f0714;
  background-size:
    100%;
  border-radius: 0.5rem;
  border: 2px solid #51446a;
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
  box-shadow: none;
  font-family: Cardo, serif;
}




.pp-top-bar-app-menu-list a:first-child {
  background: #0b0830;
}


.pp-top-bar-app-menu-list a {
  width: 100%;
  display: flex;
  align-items: center;
  box-shadow: none !important;
  mask-image:
    radial-gradient(circle at calc(100% - 27px) 50%, transparent 0 5px, black 6px 100%);
  -webkit-mask-image:
    radial-gradient(circle at calc(100% - 30px) 50%, transparent 0 5px, black 6px 100%);
  font-family: 'DM Serif Text';
  font-weight: 700;
  padding-right: 3rem;
  padding-left: 1rem;
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
  border: 0 !important;
  border-radius: 4px 32px 32px 4px;
  outline: 2px solid transparent;
  background: #0b0830;
  color: #d8c6f4;
  transition: all 500ms;
}


.pp-top-bar-app-menu-list a:last-child:not([href="/profile-settings"]) {
  margin-top: 2.5rem;
}



.pp-top-bar-app-menu-list hr {
  display: none;
}



.pp-top-bar-app-menu-list a:hover {
  background: #d8c6f4;
  color: #0b0830;
  transform: scale(1.05);
  outline: 2px solid #0b0830;
  outline-offset: -2px;
}









.css-i3ef4m {
  position: relative;
  border-bottom: none;
  background: transparent;
  margin: auto;
  height: 4rem;
  width: auto;
  display: flex;
  justify-content: center;
  align-items: center;
}


.css-i3ef4m::before {
  position: absolute;
  content: "";
  top: 0;
  height: 100%;
  width: 100vw;
  background:
    repeating-radial-gradient(circle at 50% 50%, #51446a 0 10px, transparent 12px 100%),
    repeating-radial-gradient(circle at 50% 50%, #51446a 0 18px, transparent 20px 100%),
    repeating-radial-gradient(circle at 50% 50%, #51446a 0 26px, transparent 28px 100%),
    repeating-radial-gradient(circle at 50% 50%, transparent 0 20px, #51446a 22px 24px, transparent 26px)
    #0f0714;
  background-size:
    25% 100%,
    50% 100%,
    100%,
    100%;
  border-top: 2px solid #d8c6f4;
  border-bottom: 2px solid #d8c6f4;
  box-sizing: border-box;
  z-index: 0;
}



.css-i3ef4m button {
  height: calc(100% - 4px);
  width: auto;
  color: #f6f0ff !important;
  font-family: Cardo;
  letter-spacing: 0;
  font-size: 0;
  font-weight: 1000;
  transition: letter-spacing 500ms !important;
}

.css-i3ef4m button:first-of-type::after {
  font-size: clamp(2rem, 8vw, 3rem);
  content: "Welcome to my world";
  transition: letter-spacing 500ms;
}

.css-i3ef4m button:nth-of-type(2)::after {
  font-size: 3rem;
  content: "tab two";
}


.css-i3ef4m div {
  display: none;
  
  
}


.css-i3ef4m button:hover::after {
  letter-spacing: 2px;
}

.css-i3ef4m button:hover ~ div {
  transform: translateY(2px);
  background: #56f5f7;
}


div:has(> .css-m8ywhg) { gap: 1rem; }




</style>

<style>
  position: relative;
  flex-direction: row;
  gap: 0.65rem 0.5rem;
  flex-wrap: wrap;
  align-content: center;
  justify-content: center;
  align-items: center;
  background: transparent;
  width: 100%;
  padding: 0.5rem 0;
  border-bottom: 2px solid #d8c6f4;
  box-sizing: border-box;
}



.css-zdpt2t,
.css-mcoi9a,
.css-1cdqd3a,
.css-1pfxi6a,
.css-6su6fj {
  display: contents;
}

.css-mcoi9a {
  z-index: 5;
}



.css-1jy826p {
  order: -1;
  flex: 1 1 100%; 
}

.css-1n2in4t,
.css-8l42c1 {
  flex-shrink: 0; 
}


.pp-fl-search-input {
  color: white;
  font-family: Cardo;
  position: relative;
  max-width: 100%;
  width: 100%;
  border: none;
  border: 2px solid #d8c6f4;
  border-left: 0;
  background: #0b0830;
  border-radius: 0 0.5rem 0.5rem 0;
}


.pp-fl-search-input:not(:placeholder-shown) {
  border-radius: 0;
  max-width: 100%;
  border: none;
  border: 2px solid #0b0830;
  background: #d8c6f4;
  color: #0b0830;
  border-left: 0;
  border-radius: 0 0.5rem 0.5rem 0;
}

.pp-fl-search-input:not(:placeholder-shown):hover,
.pp-fl-search-input:not(:placeholder-shown):focus,
.pp-fl-search-input:not(:placeholder-shown):focus-visible {
  border: 2px solid #0b0830;
  border-left: 0;
  box-shadow: none;
}


.css-1d3jfmu svg {
  color: #0b0830 !important;
}



.css-1jy826p .css-1y0e7gb {
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
  border-radius: 0.5rem;
  transition: all 500ms;
}

.css-1jy826p .css-1y0e7gb::before {
  display: flex;
  justify-content: center;
  align-items: center;
  content: "✧";
  font-size: 1.5rem;
  width: 3rem;
  height: 100%;
  background: #d8c6f4;
  color: #0b0830;
  border-radius: 0.5rem 0 0 0.5rem;
  transition: all 500ms;
}


.pp-fl-search-input::placeholder {
  font-family: Cardo;
  text-transform: ;
  color: #d8c6f4BF;
  font-weight: 700;
  letter-spacing: 0;
  transition: all 500ms;
}


.pp-fl-search-input:hover,
.pp-fl-search-input:focus {
  background: #171717 !important;
  box-shadow: none;
  border: 2px solid white;
  border-left: 0;
}


.pp-fl-search-input:hover::placeholder,
.pp-fl-search-input:focus::placeholder {
  color: #FFFFFFBF;
}

.css-1jy826p .css-1y0e7gb:hover {
  
}


.css-1jy826p .css-1y0e7gb:has(.pp-fl-search-input:not(:placeholder-shown)) {
  outline: 1px solid #d8c6f4;
}


.css-1jy826p .css-1y0e7gb:has(.pp-fl-search-input:not(:placeholder-shown))::before {
  background: #0b0830;
  color: #d8c6f4;
}


.css-1jy826p .css-1y0e7gb:has(.pp-fl-search-input:hover, .pp-fl-search-input:active, .pp-fl-search-input:focus) {
  outline: 2px solid #171717;
  outline-offset: 0px;
}


.css-1jy826p .css-1y0e7gb:has(.pp-fl-search-input:hover, .pp-fl-search-input:active, .pp-fl-search-input:focus)::before {
  background: white;
  color: #0b0830;
}


.css-1jy826p .css-1y0e7gb:has(.pp-fl-search-input:not(:placeholder-shown):hover, .pp-fl-search-input:not(:placeholder-shown):active, .pp-fl-search-input:not(:placeholder-shown):focus) {
  outline: 2px solid #d8c6f4;
  outline-offset: 0px;
}


.css-1jy826p .css-1y0e7gb:has(.pp-fl-search-input:not(:placeholder-shown):hover, .pp-fl-search-input:not(:placeholder-shown):active, .pp-fl-search-input:not(:placeholder-shown):focus)::before {
  background: #0b0830;
  color: #d8c6f4;
}



.css-b62m3t-container,
.Btn2-purple {
  width: 150px;
  text-align: center;
box-shadow: unset;
border: unset;
}

.Btn2-purple:hover {
  color: white;
  text-shadow: unset;
  border-color: initial;
}





.Btn2-purple::before {
  display: none;
}

.Btn2-purple {
  justify-content: flex-start;
  text-transform: ;
  font-family: Cardo;
  font-weight: 700;
  background: transparent;
  border-radius: 0;
  color: white;
  padding: 0;
  transition: unset !important;
}

.Btn2-purple .css-wd8hou {
  width: 100%;
  gap: 0;
}



.Btn2-purple p {
  font-size: 0;
  width: 100%;
  text-align: center;
}

.Btn2-purple p::after {
  font-size: 1rem;
  content: "Cards";
  width: 100%;
}

.Btn2-purple strong {
  text-align: center;
  padding: 0 14px;
  margin: 8px 0;
  color: #d8c6f4;
  border-right: 1px solid #d8c6f4;
}

.Btn2-purple:active {
  transform: none;
}





.css-1n2in4t,
.css-8l42c1 {
  position: relative;
  text-wrap: wrap;
  background: transparent;
  border-radius: 0;
  border: 0;
  outline-offset: 0;
  padding: 0 0.25rem;
}

.css-1n2in4t svg,
.css-8l42c1 svg {
  height: 1rem;
  aspect-ratio: 1 / 1;
}

.css-1n2in4t svg { color: #d8c6f4 !important; }
.css-8l42c1 svg { color: white !important; }


:is(.css-1n2in4t, .Btn2-purple, .css-b62m3t-container):is(:hover, :focus) {
  background: transparent;
  outline: 1px solid #d8c6f4;
  outline-offset: 0px;
  border-radius: 0.5rem;
}

.css-8l42c1:hover,
.css-8l42c1:focus {
  border-radius: 0.5rem;
  background: transparent;
  outline: 1px solid #d8c6f4;
}




[data-focus-lock-disabled="false"] [role="dialog"] {
  background:
    radial-gradient(circle at 50% 50%, #d8c6f4 0 calc(8% - 2px), transparent calc(8% + 2px) 100%),
    radial-gradient(circle at 50% 100%, #d8c6f4 0 calc(25% - 2px), transparent calc(25% + 2px) 100%),
    radial-gradient(circle at 50% 0%, #d8c6f4 0 calc(12% - 2px), transparent calc(12% + 2px) 100%),
    repeating-radial-gradient(circle at 50% 50%, transparent 0 48px, #d8c6f4 50px 52px, transparent 54px),
    radial-gradient(circle at 0% 0%, #d8c6f4 10px, transparent 11px),
    radial-gradient(circle at 0% 100%, #d8c6f4 10px, transparent 11px),
    radial-gradient(circle at 100% 0%, #d8c6f4 10px, transparent 11px),
    radial-gradient(circle at 100% 100%, #d8c6f4 10px, transparent 11px)
    #0b0830 !important;
  background-size:
    100% !important;
  backdrop-filter: unset !important;
  box-shadow: none;
  border-radius: 0.5rem;
  border: 2px solid #d8c6f4;
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
}

[data-focus-lock-disabled="false"] [role="dialog"]::after {
  content: "";
  position: absolute;
  Inset: -2px;
  border-radius: 0.5rem;
  z-index: -1;
  pointer-events: none;
  background: #000000A0;
}


.css-0 { display: contents; }


.css-18936vg button {
  display: flex;
  line-height: 1.7;
  border: none;
  background: #0b0830;
  color: #d8c6f4;
  font-family: 'DM Serif Text';
  font-weight: 700;
  border-radius: 16px;
  transition: all 500ms;
}

.css-18936vg button:hover {
  background: #d8c6f4;
  outline: 2px solid #0b0830;
  outline-offset: -2px;
  color: #0b0830;
}


.css-dcyl1x, .css-178jenf {
  text-align: center;
  font-family: 'Cardo';
  font-size: 0;
  color: white;
  font-weight: 1000;
}


.css-dcyl1x::after {
  font-size: clamp(1.5rem, 8vw, 2.25rem);
  content: "Deck search";
  text-transform: uppercase;
  border-bottom: 1px solid #d8c6f4;
}


.css-178jenf::after {
  font-size: clamp(1rem, 6vw, 1.75rem);
  content: "Choose your fate:";
  font-style: italic;
}



.css-lyo4r5 {
  border-radius: 0.5rem;
  margin: 0;
  top: 1.5rem !important;
  right: 1.5rem !important;
}

.css-lyo4r5 svg {
  color: #d8c6f4 !important;
}


.css-tn23vd {
  margin: ;
}

.css-tn23vd > li {
  flex: 1 1 45%;
  text-wrap: nowrap;
}

.css-tn23vd * {
  width: 100%;
}


.css-1w58nos,
.css-oqdsp6 {
  width: 100%;
  display: inline-block;
  box-shadow: none !important;
  mask-image:
    radial-gradient(circle at 9px 50%, transparent 0 3px, black 4px 100%);
  -webkit-mask-image:
    radial-gradient(circle at 9px 50%, transparent 0 3px, black 4px 100%);
  font-family: 'DM Serif Text';
  font-weight: 700;
  padding-left: 14px;
  padding-right: 4px;
  padding-top: 6px;
  padding-bottom: 6px;
  border: 0 !important;
  border-radius: 16px 4px 4px 16px;
  transition: all 500ms;
}


.css-1w58nos {
  background: #0b0830;
  color: #d8c6f4;
}

  

.css-oqdsp6 {
  background: #d8c6f4;
  color: #0b0830;
  outline: 2px solid #0b0830;
  outline-offset: -2px;
}

.css-tn23vd .css-1yp4ln {
  overflow: visible;
}




.default .react-select__control {
  background: transparent;
  border-radius: 0;
  border: 0;
  justify-content: center;
  flex-direction: row;
  flex-wrap: nowrap;
  backdrop-filter: unset;
}



.css-1wy0on6 {
  margin-left: auto;
}

.css-1wy0on6 > div {
    padding: 2px 12px !important;
    margin: 0 !important;
    border-left: 1px solid #d8c6f4;
}

.default .react-select__control svg {
  color: #d8c6f4 !important;
  transition: all 500ms;
}


.css-b62m3t-container:has(.css-qr46ko) svg {
  transform: rotate(180deg);
}


.css-hlgwow {
  width: 100%;
  flex: unset;
  padding: 0 !important;
}


.css-1dimb5e-singleValue {
  width: 100%;
  text-align: center;
  font-size: 0;
  font-family: Cardo;
  font-weight: 700;
  text-transform: ;
  color: white !important;
  transition: all 500ms;
}


.css-1u9des2-indicatorSeparator {
  display: none;
}


.css-1dimb5e-singleValue::before {
  display: flex;
  text-align: center;
  justify-content: center;
  align-items: center;
  position: absolute;
  inset: 0;
  content: "Display";
  color: white;
  font-size: 1rem;
  opacity: 1;
  transition: opacity 500ms;
}

.css-1dimb5e-singleValue::after {
  color: white;
  transition: opacity 0ms;
  transition-delay: 0ms;
  content: "Placeholder";
  font-size: 1rem;
  opacity: 0;
}


.css-b62m3t-container:hover .css-1dimb5e-singleValue {
  
}


.css-b62m3t-container:has(.css-qr46ko) .css-1dimb5e-singleValue::after {
  opacity: 1;
  transition: opacity 500ms;
  transition-delay: 500ms;
}

.css-b62m3t-container:has(.css-qr46ko) .css-1dimb5e-singleValue::before {
  opacity: 0;
}


.css-b62m3t-container:hover .css-1dimb5e-singleValue::after,
.css-b62m3t-container:has(.css-qr46ko) .css-1dimb5e-singleValue::after {
  
}


.default .react-select__menu { 
    padding-bottom: 0 !important;
    background-color: transparent;
    border: none;
    border-radius: 0;
    box-shadow: none;
    backdrop-filter: unset;
    overflow: visible;
    mask-image: radial-gradient(circle at 50% 50%, black 0 calc(50% - 2px), transparent calc(50% + 2px) 100%);
    -webkit-mask-image: radial-gradient(circle at 50% 50%, black 0 calc(50% - 2px), transparent calc(50% + 2px) 100%);
    mask-size: 100%;
    mask-repeat: no-repeat;
    mask-position: 50% 50%;
    -webkit-mask-size: 100%;
    -webkit-mask-repeat: no-repeat;
    -webkit-mask-position: 50% 50%;
    transition: all 500ms;
    animation: popup 1500ms ease;
    animation-fill-mode: forwards;
}


@keyframes popup {
  from {
    mask-size: 0% 0%;
    -webkit-mask-size: 0% 0%;
  }
  to {
    mask-size: 300% 300%;
    -webkit-mask-size: 300% 300%;
  }
}



.css-qr46ko {
  margin-top: 0.5rem;
  display: flex;
  flex-flow: column nowrap;
  gap: 0.5rem;
  position: relative;
  padding: 0;
  transition: all 500ms;
  overflow: visible;
  height: 100%;
}


.default .react-select__option {
  width: 100%;
  display: inline-block;
  box-shadow: none !important;
  mask-image:
    radial-gradient(circle at 14px 50%, transparent 0 5px, black 6px 100%);
  -webkit-mask-image:
    radial-gradient(circle at 14px 50%, transparent 0 5px, black 6px 100%);
  font-family: 'DM Serif Text';
  font-weight: 700;
  padding-left: 14px;
  padding-right: 4px;
  padding-top: 6px;
  padding-bottom: 6px;
  border: 0 !important;
  border-radius: 16px 4px 4px 16px;
  outline: 2px solid transparent;
  background: #0b0830;
  color: #d8c6f4;
  transition: all 500ms;
}


.react-select__option:hover {
  background: #d8c6f4 !important;
  color: #0b0830;
  outline: 2px solid #0b0830;
  outline-offset: -2px;
}


.default .react-select__option--is-selected,
.react-select__option--is-selected:hover {
  display: none;
}




.css-qr46ko > div,
.css-1dimb5e-singleValue {
  font-size: 0 !important;
}

.css-qr46ko > div::after {
  font-size: 1rem;
}
.css-1dimb5e-singleValue::after {
  
}




.css-qr46ko > div:first-child::after {
  content: "Top cards";
}


.css-qr46ko > div:nth-child(2)::after {
  content: "Recent";
}


.css-qr46ko > div:nth-child(3)::after {
  content: "Trends";
}


.css-qr46ko > div:nth-child(4)::after {
  content: "Trends 24h";
}



.css-b62m3t-container:has(.react-select__option--is-selected:first-child) .css-1dimb5e-singleValue::after {
  content: "Top cards";
}

.css-b62m3t-container:has(.react-select__option--is-selected:nth-child(2)) .css-1dimb5e-singleValue::after {
  content: "Recent";
}

.css-b62m3t-container:has(.react-select__option--is-selected:nth-child(3)) .css-1dimb5e-singleValue::after {
  content: "Trends";
}

.css-b62m3t-container:has(.react-select__option--is-selected:nth-child(4)) .css-1dimb5e-singleValue::after {
  content: "Trends 24h";
}





.pp-cc-list-empty {
  display: flex;
  flex-flow: column;
  justify-content: center;
  align-items: center;
  height: 20rem;
  padding-bottom: 4rem;
  font: 400 2rem Cardo, serif;
  color: #d8c6f4;
}

.pp-cc-list-empty::before {
  content: "404";
  color: white;
  font: 300 4rem 'DM Serif Text', serif;
}


div:has(> div > .css-1s5evre) {
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  gap: 1.5rem;
  padding-top: 3rem;
  position: relative;
  order: 3;
}


div:has(> div > .css-1s5evre)::after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  text-align: center;
  content: "hover to reveal details, then click on the left card.";
  font-family: Cardo;
  font-size: 1rem;
  color: white;
}

div:has(> .css-1s5evre) {
  perspective: 1000px;
  background: transparent;
  flex: 0 1 350px;
  width: 350px;
  height: 330px;
}

div:has(> .css-1s5evre):hover { box-shadow: none; }

div:has(~ .css-1s5evre):not(.css-dltla) {
  background: transparent !important;
}

.css-1s5evre {
  position: relative;
  width: 100%;
  height: 100%;
  perspective: 1000px;
}

.css-1s5evre > a + a,
.css-1s5evre > div:first-of-type + div,
.css-1s5evre .css-1c9wmts ~ * {
  display: none;
}


.css-1s5evre > a:first-child {
  perspective: 1000px;
  transform: rotateY(0deg);
}

.css-1s5evre > a:first-child {
  position: absolute;
  width: 48%;
  height: 100%;
  left: 0;
  bottom: 0;
  transition: all 500ms;
  z-index: 1;
}


.css-199gcrh {
  padding: 1rem;
  position: absolute;
  width: 48%;
  height: 100%;
  left: 0;
  top: 0;
  transition: all 500ms;
  backface-visibility: hidden;
  background: #000000A0;
  border-radius: 0.5rem;
  display: flex;
  justify-content: center;
  align-items: center;
}


.css-199gcrh::after {
  text-align: center;
  content: "Click here to go.";
  position: absolute;
  width: 100%;
  left: 0;
  bottom: 0;
}

@media only screen and (max-width:767px) {
  .css-199gcrh::after { content: "Tap here to go."; }
  div:has(> div > .css-1s5evre)::after { content: "tap to reveal details, then tap on the left card."; }
}

.css-96l1id {
  color: white;
  font-family: Cardo;
  line-height: 1.3;
  font-size: 0.8rem;
  font-weight: 700;
}

.css-96l1id::first-letter {
  font-size: 1.25rem;
  line-height: unset;
  font-weight: 300;
}



.css-nlxhw4 {
  display: flex;
  align-items: flex-end;
  justify-content: flex-start;
  position: absolute;
  bottom: 0;
  height: 100%;
  width: 100%;
  left: 0;
  z-index: 2;
  transition: all 500ms;
  backface-visibility: hidden;
  overflow: hidden;
  background: linear-gradient(to top, #000000BF 0, transparent 30%);
  border-radius: 0.5rem;
  border: 2px solid #d8c6f4;
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
}


.css-nlxhw4 > div {
  font-family: Cardo;
  font-size: 1.5rem;
  text-transform: lowercase;
  font-variant: small-caps;
  letter-spacing: unset;
  text-shadow: unset;
  color: white;
  text-wrap: wrap;
  text-overflow: unset;
  line-height: 0.75;
  overflow: visible;
  z-index: 2;
}

.css-nlxhw4 > div::first-letter {
  font-size: 2.5rem;
}



.css-1q7rmf0 {
  height: 100%;
  z-index: 1;
  padding: 5px;
  border-radius: 0.5rem;
  overflow: hidden;
  transition: all 500ms;
  backface-visibility: hidden;
}

.css-1q7rmf0 img {
  border-radius: 0;
}


.css-nlxhw4::after {
  content: "";
  position: absolute;
  inset: -2px;
  background: #d8c6f4;
  clip-path: polygon(0 20px,20px 0,calc(100% - 20px) 0,100% 20px,100% calc(100% - 20px),calc(100% - 20px) 100%,20px 100%,0 calc(100% - 20px),0 20px,2px  calc(20px + 0.83px),2px calc(100% - 20px - 0.83px),calc(20px + 0.83px) calc(100% - 2px),calc(100% - 20px - 0.83px) calc(100% - 2px),calc(100% - 2px) calc(100% - 20px - 0.83px),calc(100% - 2px) calc(20px + 0.83px),calc(100% - 20px - 0.83px) 2px,calc(20px + 0.83px) 2px,2px calc(20px + 0.83px));
}



.css-4ofde4 {
  position: absolute;
  width: 48%;
  height: 100%;
  right: 0;
  bottom: 0;
  margin: 0;
  padding: 0;
  transform: translateX(-50%) rotate(-5deg);
  filter: brightness(0.4);
  z-index: 0;
  transition: all 500ms;
  background:
    radial-gradient(circle, #d8c6f4 0 18%, transparent calc(18% + 2px) 100%),
    repeating-radial-gradient(circle, transparent 0 calc(18% - 4px), #d8c6f4 calc(18% - 2px) 18%, transparent calc(18% + 2px)),
    radial-gradient(circle at 0% 0%, #d8c6f4 10px, transparent 11px),
    radial-gradient(circle at 0% 100%, #d8c6f4 10px, transparent 11px),
    radial-gradient(circle at 100% 0%, #d8c6f4 10px, transparent 11px),
    radial-gradient(circle at 100% 100%, #d8c6f4 10px, transparent 11px),
    #0b0830;
  background-size: 100% 50%, 100% 50%, 100%, 100%, 100%, 100%;
  background-position: auto, 50% 100%, auto, auto, auto, auto; 
  background-repeat: repeat-y, auto, auto, auto ,auto, auto;
  transition: all 500ms;
  border-radius: 0.5rem;
  border: 2px solid #d8c6f4;
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
  display: flex;
  justify-content: center;
  align-items: center;
}


.css-k1urot {
  margin: 0;
  padding: 0.5rem;
  position: absolute;
  inset: -2px;
  align-content: center;
  justify-content: center;
  background: #000000A0;
  z-index: 2;
  border-radius: 0.5rem;
}

.css-k1urot li:not(.css-123m5uu),
.css-k1urot li a {
  display: contents;
}




.pp-cc-tags span:not(.profile-character-card-tag-limitless) {
  display: inline-block;
  line-height: 1.7;
  border: none;
  background: #d8c6f4;
  color: #0b0830;
  mask-image:
    radial-gradient(circle at 9px 50%, transparent 0 3px, black 4px 100%);
  -webkit-mask-image:
    radial-gradient(circle at 9px 50%, transparent 0 3px, black 4px 100%);
  font-family: 'Cardo';
  font-size: 0.8rem;
  font-weight: 1000;
  padding-left: 14px;
  padding-right: 4px;
  border-radius: 16px 4px 4px 16px;
}

.pp-cc-tags-custom {
  padding-left: 16px !important;
}


.pp-cc-tags span:not(.profile-character-card-tag-limitless):hover {
  background: #0b0830;
  color: #d8c6f4;
  outline: 2px solid #d8c6f4;
  outline-offset: -2px;
}


.pp-cc-tags-regular::first-letter {
  font-size: 0;
}



#root .pp-tag-deaddove {
  font-size: 0;
}


.pp-tag-deaddove::after {
    content: "Dead Dove";
    font-size: 0.8rem;
}


:has(> .profile-character-card-tag-limitless) {
  display: flex;
  justify-content: center;
  position: absolute;
  top: 0.25rem;
  left: 0;
  margin: 0;
  padding: 0;
  width: 100%;
}

.profile-character-card-tag-limitless { font-size: 0; }
.profile-character-card-tag-limitless::after {
  content: "Info:";
  font-size: 1rem;
}



.css-10cv7r2 {
  display: flex;
  justify-content: center;
  right: unset;
  top: 0.25rem;
  left: 0;
  width: 100%;
  height: auto;
  transition: all 500ms;
  backface-visibility: hidden;
}


.css-10cv7r2 > *,
.css-10cv7r2 > * > *,
.css-10cv7r2 > * > * > * {
  display: contents;
}


.css-euh5x6 svg {
  display: none;
}

.css-euh5x6 { font-size: 1rem; }
.css-euh5x6,
.profile-character-card-tag-limitless {
  justify-content: center;
  width: 0;
  height: auto;
  text-align: center;
  color: white;
  font-family: Cardo;
  font-weight: normal;
  font-style: italic;
  line-height: 1.5;
  margin: 0;
  padding: 0;
  border: none;
  background: none;
  padding-bottom: 0.25rem;
  text-wrap: nowrap;
  border-radius: 0;
  max-height: unset;
  min-width: unset;
  border-bottom: 1px solid #d8c6f4;
  transition: all 500ms;
  transition-delay: 0ms;
}

.css-euh5x6 span::before {
  content: "Readings: ";
}

div:hover > .css-1s5evre .css-euh5x6,
div:hover > .css-1s5evre .profile-character-card-tag-limitless {
  width: calc(100% - 2rem);
  transition: all 500ms;
  transition-delay: 500ms;
}



.css-1c9wmts {
  pointer-events: none;
  display: flex;
  justify-content: center;
  align-items: flex-end;
  position: absolute;
  width: 48%;
  height: 100%;
  left: unset;
  right: 0;
  bottom: 0;
  margin: 0;
  padding: 0;
  transform: translateX(-50%) rotate(-5deg);
  filter: brightness(0.4);
  z-index: 0;
  transition: all 500ms;
}


.css-1c9wmts p,
.css-199gcrh::after {
  opacity: 1;
  font-family: Cardo;
  font-style: Italic;
  font-weight: normal;
  font-size: 1rem;
  color: white;
  text-shadow: unset;
  text-transform: unset;
  letter-spacing: unset;
  padding-bottom: 0.25rem;
  line-height: unset;
}



div:nth-child(3n) > .css-1s5evre .css-199gcrh,
div:nth-child(3n) > .css-1s5evre .css-10cv7r2,
div:nth-child(3n) > .css-dltla {
  transform: translateX(50%) rotate(5deg) rotateY(-180deg);
}
div:nth-child(3n) > .css-1s5evre .css-1q7rmf0,
div:nth-child(3n) > .css-1s5evre .css-nlxhw4 {
 transform: translateX(50%) rotate(5deg) rotateY(0deg);
}

div:nth-child(3n-1) > .css-1s5evre .css-199gcrh,
div:nth-child(3n-1) > .css-1s5evre .css-10cv7r2,
div:nth-child(3n-1) > .css-dltla {
  transform: translateX(50%) rotate(-4deg) rotateY(-180deg);
}
div:nth-child(3n-1) > .css-1s5evre .css-1q7rmf0,
div:nth-child(3n-1) > .css-1s5evre .css-nlxhw4 {
 transform: translateX(50%) rotate(-4deg) rotateY(0deg);
}

div:nth-child(3n-2) > .css-1s5evre .css-199gcrh,
div:nth-child(3n-2) > .css-1s5evre .css-10cv7r2,
div:nth-child(3n-2) > .css-dltla {
  transform: translateX(50%) rotate(2deg) rotateY(-180deg);
}
div:nth-child(3n-2) > .css-1s5evre .css-1q7rmf0,
div:nth-child(3n-2) > .css-1s5evre .css-nlxhw4 {
 transform: translateX(50%) rotate(2deg) rotateY(0deg);
}

div:is(:hover, :focus)> .css-1s5evre .css-199gcrh,
div:is(:hover, :focus) > .css-1s5evre .css-10cv7r2,
div:is(:hover, :focus) > .css-dltla {
  transform: translateX(0) rotate(0) rotateY(-360deg);
}

div:is(:hover, :focus) > .css-1s5evre .css-1q7rmf0,
div:is(:hover, :focus) > .css-1s5evre .css-nlxhw4 {
  transform: translateX(0) rotate(0) rotateY(-180deg);
}

div:is(:hover, :focus) > .css-1s5evre .css-4ofde4,
div:is(:hover, :focus) > .css-1s5evre .css-1c9wmts {
  transform: translateX(0) rotate(0);
  filter: none;
}


div:has(> .css-1s5evre)::before {
  z-index: 5;
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  pointer-events: auto;
  transition: all 200ms;
}

div:has(> .css-1s5evre):hover::before {
  z-index: -2;
}


.css-dltla {
  inset: unset unset 0 0;
  height: 100%;
  width: 48%;
  background:
    radial-gradient(circle at 50% 27.5%, #d8c6f4 0 8%, transparent calc(8% + 2px) 100%),
    radial-gradient(circle at 50% 100%, #d8c6f4 0 25%, transparent calc(25% + 2px) 100%),
    radial-gradient(circle at 50% 0%, #d8c6f4 0 12%, transparent calc(12% + 2px) 100%),
    radial-gradient(circle at 0% 0%, #d8c6f4 10px, transparent 11px),
    radial-gradient(circle at 0% 100%, #d8c6f4 10px, transparent 11px),
    radial-gradient(circle at 100% 0%, #d8c6f4 10px, transparent 11px),
    radial-gradient(circle at 100% 100%, #d8c6f4 10px, transparent 11px),
    #0b0830;
  background-size: 100% 100%;
  transition: all 500ms;
  border: 2px solid #d8c6f4;
  outline: 1px solid #d8c6f4;
  outline-offset: 2px;
  display: flex;
  justify-content: center;
  align-items: center;
  backface-visibility: hidden;
}

.css-dltla::after,
.css-dltla::before,
.css-4ofde4::after,
.css-4ofde4::before {
  position: absolute;
  content: "";
}

.css-dltla::before,
.css-4ofde4::before {
  background: black;
  border: 2px solid #d8c6f4;
  border-radius: 99% 0;
  transform: rotate(45deg);
  width: 5em;
  height: 5em;
}

.css-dltla::after,
.css-4ofde4::after {
  background: radial-gradient(circle at 50% 50%, #d8c6f4 0 22%, transparent calc(22% + 2px) 100%);
  background-position: 50% 50%;
  background-size: 200% 200%;
  border: 2px solid #d8c6f4;
  border-radius: 50%;
  width: 2.5em;
  height: 2.5em;
  box-shadow: inset 0 0 0 8px #d8c6f4;
}

div:hover > .css-dltla::after {
  animation: eye 20s ease-in-out infinite reverse;
}
div:hover > .css-1s5evre .css-4ofde4::after {
  animation: eye 20s ease-in-out infinite;
}

@keyframes eye {
  0%, 100% {
    background-position: 50% 50%;
  }
  20% {
    background-position: 25% 25%;
  }
  40% {
    background-position: 50% 75%;
  }
  60% {
    background-position: 60% 30%;
  }
  80% {
    background-position: 40% 70%;
  }
}







.css-1pfxi6a,
.css-1igwmid,
.profile-pagination-prev-hstack {
  width: 100%;
  justify-content: center;
  
}


:is(.profile-pagination-prev-button, .profile-pagination-next-button-icon) svg  {
  color: #d8c6f4 !important;
  opacity: 1;
}


.pp-pg-page-button {
  font-family: Cardo, serif;
  color: white;
}

.css-f6i8vf {
  background: #0f0714;
}



.css-jdhqy4 > div {
    font-family: Cardo, serif;
    font-weight: 100;
    background: #0b0830;
    color: white;
    border-radius: 0.5rem;
    border: 2px solid #d8c6f4;
    box-shadow: none;
}

.css-vqimyu {
  z-index: 10;
}




.chakra-spinner {
    border-right-color: white !important;
    border-top-color: white !important;
}



.profile-page-container > div:empty {
  filter: brightness(0.3);
}


.creds {
  position: absolute;
  bottom: -2.3rem;
  width: 100%;
  left: 0;
  font-family: Cardo;
  text-align: center;
  color: #FFFFFFBF;
  transition: color 500ms, transform 500ms;
}

.creds:hover {
  color: #d8c6f4;
  transform: scale(1.1);
}
<style/>
