@font-face {
  src: url("https://raw.githubusercontent.com/MOF1/krunker_css/main/css/fonts/Steradian-Bold.otf");
  font-family: steradian;
  font-weight: 900;
}

@font-face {
  src: url("https://raw.githubusercontent.com/MOF1/krunker_css/main/css/fonts/EuclidCircularA-Medium.ttf");
  font-family: cirular;
}

@font-face {
  font-family: customF;
  src: url("https://raw.githubusercontent.com/MOF1/krunker_css/main/css/fonts/Steradian-Bold.otf");
}

@-webkit-keyframes anima {
  0% {
    background-position: 0% 100%;
  }
  50% {
    background-position: 100% 0%;
  }
  100% {
    background-position: 0% 100%;
  }
}

@keyframes anima {
  0% {
    background-position: 0% 100%;
  }
  50% {
    background-position: 100% 0%;
  }
  100% {
    background-position: 0% 100%;
  }
}

@-webkit-keyframes contraCard {
  0% {
    color: var(--c_white);
    border-color: var(--c_white);
  }
  50% {
    color: var(--accentColor);
    border-color: var(--accentColor);
  }
  100% {
    color: var(--c_white);
    border-color: var(--c_white);
  }
}

@keyframes contraCard {
  0% {
    color: var(--c_white);
    border-color: var(--c_white);
  }
  50% {
    color: var(--accentColor);
    border-color: var(--accentColor);
  }
  100% {
    color: var(--c_white);
    border-color: var(--c_white);
  }
}

@-webkit-keyframes contraText {
  0% {
    color: var(--c_white);
    border-color: var(--c_white);
  }
  50% {
    color: var(--accentColor);
    border-color: var(--accentColor);
  }
  100% {
    color: var(--c_white);
    border-color: var(--c_white);
  }
}

@keyframes contraText {
  0% {
    color: var(--c_white);
    border-color: var(--c_white);
  }
  50% {
    color: var(--accentColor);
    border-color: var(--accentColor);
  }
  100% {
    color: var(--c_white);
    border-color: var(--c_white);
  }
}

* {
  color: var(--c_white);
}

a {
  color: var(--accentColor);
}

a:active {
  color: var(--accentColor);
}

a:visited {
  color: var(--accentColor);
}

input::-webkit-input-placeholder {
  color: var(--dirty-light) !important;
  font-family: var(--mainFont);
  font-size: 20px;
}

input:-ms-input-placeholder {
  color: var(--dirty-light) !important;
  font-family: var(--mainFont);
  font-size: 20px;
}

input::-ms-input-placeholder {
  color: var(--dirty-light) !important;
  font-family: var(--mainFont);
  font-size: 20px;
}

input::placeholder {
  color: var(--dirty-light) !important;
  font-family: var(--mainFont);
  font-size: 20px;
}

input {
  color: var(--accentColor) !important;
  background: var(--subBg) !important;
}

input[type="range"] {
  cursor: pointer !important;
}

input[type="text"],
input[type="password"] {
  margin: 0 !important;
  padding: 1rem 1.5rem !important;
  border-radius: 100px !important;
  background: var(--primaryBg) !important;
  -webkit-filter: brightness(1.4) !important;
  filter: brightness(1.4) !important;
  font-family: var(--subFont) !important;
  font-size: 1.4rem !important;
}

input[type="number"],
.sliderVal {
  border-radius: 100px;
  border-color: transparent !important;
  padding: 0.3rem 0.2rem;
  letter-spacing: 1px;
  font-family: var(--subFont);
  font-size: 1.3rem;
  color: var(--c_white) !important;
  background: var(--primaryBg) !important;
  -webkit-filter: brightness(1.4);
          filter: brightness(1.4);
}

input[type="color"] {
  height: 30px;
  border-radius: 0px;
  border-color: transparent;
  background: transparent !important;
  -webkit-transform: translateY(-3px);
          transform: translateY(-3px);
}

.settingsBtn,
.hostPresetBtn {
  all: unset;
  font-family: var(--subFont);
  background: var(--primaryBg) !important;
  -webkit-filter: brightness(1.4);
  filter: brightness(1.4);
  padding: 1rem 1rem;
  margin: 0rem 0.5rem;
  font-size: 1.2rem;
  letter-spacing: 2px;
  cursor: pointer;
}

.settingsBtn:hover,
.hostPresetBtn:hover {
  -webkit-filter: brightness(1);
          filter: brightness(1);
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] {
  margin-top: 7px;
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] .settingsBtn:nth-child(1) {
  color: var(--accentColor) !important;
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] .settingsBtn:nth-child(1):hover {
  color: var(--primaryBg) !important;
  background: var(--accentColor) !important;
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] .settingsBtn:nth-child(2) {
  color: var(--orange) !important;
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] .settingsBtn:nth-child(2):hover {
  color: var(--primaryBg) !important;
  background: var(--orange) !important;
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] .settingsBtn:nth-child(3) {
  color: var(--green) !important;
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] .settingsBtn:nth-child(3):hover {
  color: var(--primaryBg) !important;
  background: var(--green) !important;
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] .settingsBtn:nth-child(4) {
  color: var(--purple) !important;
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] .settingsBtn:nth-child(4):hover {
  color: var(--primaryBg) !important;
  background: var(--purple) !important;
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] .settingsBtn:last-child {
  margin-right: 1rem;
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] .settingsBtn:last-child:hover {
  color: var(--primaryBg) !important;
  background: var(--orange) !important;
}

.settingsHeader div[style="display:inline-block;text-align:right;float:right;"] #settingsPreset {
  height: 3.46rem;
  -webkit-transform: translateY(-5px);
          transform: translateY(-5px);
  margin-left: 1rem !important;
}

#settSearch {
  width: 400px !important;
}

.setSugBox2 {
  height: 8rem;
  border-color: transparent;
  display: -ms-inline-grid;
  display: inline-grid;
  place-content: center;
  font-family: var(--subFont);
  font-size: 1.7rem;
}

.setSugBox2:nth-child(1) {
  background: var(--accentColorST);
  color: var(--accentColor) !important;
}

.setSugBox2:nth-child(2) {
  background: var(--orange-dark);
  color: var(--orange) !important;
}

.setSugBox2:nth-child(3) {
  background: var(--purple-dark);
  color: var(--purple) !important;
}

.setSugBox2:nth-child(4) {
  background: var(--yellow-dark);
  color: var(--yellow) !important;
}

.setSugBox2:hover {
  border-color: transparent;
}

.setSugBox2 .segSugIH {
  height: 8rem;
}

.setSugBox2 .segSugIH .setSugInf {
  font-family: var(--subFont) !important;
  font-size: 1.7rem !important;
}

#clientExitPop {
  border-color: var(--subBgST);
  border-width: 4px;
}

#clientExitPop > div:first-child {
  font-family: var(--subFont);
  font-size: 1.6rem !important;
  line-height: 3rem;
}

#clientExitPop #confirmBtn,
#clientExitPop #declineBtn {
  text-shadow: unset;
  font-family: var(--mainFont);
  font-size: 1.5rem;
  border-radius: 100px;
  color: var(--primaryBg);
}

#clientExitPop #confirmBtn:hover,
#clientExitPop #declineBtn:hover {
  -webkit-filter: brightness(0.9);
          filter: brightness(0.9);
}

#clientExitPop #confirmBtn {
  background: var(--orange2);
}

#clientExitPop #declineBtn {
  background: var(--orange);
}

#voiceDisplay {
  bottom: 18px;
}

#voiceDisplay #recTimer {
  font-family: var(--subFont);
  font-size: 16px;
  letter-spacing: 3px;
  margin-left: 0.2rem;
}

.sliderM {
  -webkit-appearance: none;
  -moz-appearance: none;
       appearance: none;
  background-color: var(--primaryBg) !important;
  -webkit-filter: brightness(2);
          filter: brightness(2);
  outline: none;
  border-radius: 50px;
}

.sliderM::-webkit-slider-thumb {
  -webkit-appearance: none;
  appearance: none;
  width: 15px;
  height: 15px;
  border: 2px solid transparent;
  border-radius: 50px;
  background: var(--accentColor);
  cursor: pointer;
  -webkit-transition: border-color 280ms ease,
 background 280ms ease, -webkit-filter 280ms ease, -webkit-transform 280ms ease;
  transition: border-color 280ms ease,
 background 280ms ease, -webkit-filter 280ms ease, -webkit-transform 280ms ease;
  transition: filter 280ms ease, transform 280ms ease, border-color 280ms ease,
 background 280ms ease;
  transition: filter 280ms ease, transform 280ms ease, border-color 280ms ease,
 background 280ms ease, -webkit-filter 280ms ease, -webkit-transform 280ms ease;
}

.sliderM::-webkit-slider-thumb:hover {
  -webkit-filter: brightness(0.9);
          filter: brightness(0.9);
  -webkit-transform: scale(2.5);
          transform: scale(2.5);
  border-color: var(--accentColor);
  background: var(--primaryBg);
}

.sliderM::-moz-range-thumb {
  width: 15px;
  height: 15px;
  clip-path: circle();
  border: none;
  border-radius: 50px;
  background: var(--accentColor);
  cursor: pointer;
}

.inputGrey2,
#presetSelect {
  background: var(--subBg) !important;
  font-family: var(--subFont);
  font-size: 1.2rem !important;
  color: var(--c_white);
  cursor: pointer;
}

.inputGrey2 option,
#presetSelect option {
  background: var(--subBgM);
  color: var(--c_whiteST);
  font-family: var(--subFont);
  font-size: 1.2rem !important;
}

.switch {
  width: 80px !important;
}

.slider,
.slider2 {
  position: absolute;
  cursor: pointer;
  -webkit-transform: unset !important;
          transform: unset !important;
  height: 30px !important;
  width: 80px !important;
  background: var(--subBgM) !important;
  border-radius: 50px;
}

input[type="checkbox"]:checked + .slider,
input[type="checkbox"]:checked + .slider2 {
  background: var(--accentColor) !important;
}

input[type="checkbox"]:focus + .slider,
input[type="checkbox"]:focus + .slider2 {
  -webkit-filter: brightness(1.4) !important;
          filter: brightness(1.4) !important;
}

.slider:before,
.slider2:before {
  position: absolute;
  content: "";
  height: 20px;
  width: 35px;
  top: 50%;
  left: 8%;
  -webkit-transform: translateY(-50%);
          transform: translateY(-50%);
  border-radius: 100px;
  background: var(--c_white);
}

input[type="checkbox"]:checked + .slider:before,
input[type="checkbox"]:checked + .slider2:before {
  background: var(--primaryBg);
  -webkit-transform: translate(33px, -50%);
          transform: translate(33px, -50%);
}

.premiumSkinCol {
  color: var(--l-accentColor) !important;
}

.skinColorItem {
  border: 3px solid transparent;
}

.kick {
  font-size: 18px;
  text-shadow: none;
  font-family: var(--mainFont);
  background-color: var(--subBg) !important;
  color: var(--orange2) !important;
}

.ban {
  font-size: 18px;
  text-shadow: none;
  font-family: var(--mainFont);
  background-color: var(--subBg) !important;
  color: var(--orange) !important;
}

.vote {
  font-size: 18px;
  text-shadow: none;
  font-family: var(--mainFont);
  background-color: var(--subBg) !important;
  color: var(--purple) !important;
}

#policePopC {
  background-color: var(--primaryBg);
}

#policePopC * {
  color: var(--c_white) !important;
  font-size: 23px !important;
  text-align: left !important;
}

#policePopC div[style="font-size:30px;margin-bottom:20px"] {
  color: var(--accentColor) !important;
  font-family: var(--mainFont) !important;
  font-size: 40px !important;
  text-transform: uppercase;
}

#policePopC * {
  font-family: var(--subFont) !important;
  color: var(--c_white) !important;
  font-size: 23px !important;
  text-align: left !important;
}

#policePopC div[style="color:rgba(0,0,0,0.6);font-size:19px"] * {
  font-family: var(--subFont) !important;
  font-size: 23px !important;
  text-align: left !important;
}

.polApplc {
  border: 0 !important;
  background-color: var(--subBg) !important;
  color: var(--c_whiteST) !important;
}

.leaderItem * {
  font-family: var(--mainFont) !important;
  font-size: 25px;
}

.skinList {
  display: -ms-grid;
  display: grid;
  -ms-grid-columns: 1fr 1fr;
      grid-template-columns: 1fr 1fr;
  gap: 10px;
  position: relative;
}

.skinList .classCard {
  width: auto;
  position: relative;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: start;
      -ms-flex-align: start;
          align-items: flex-start;
  font-family: var(--mainFont);
  text-shadow: unset;
  height: 100px;
  background-color: transparent !important;
  -webkit-transition: color 280ms 200ms;
  transition: color 280ms 200ms;
}

.skinList .classCard .classWeap {
  font-family: var(--mainFont);
  text-shadow: unset;
  -webkit-transition: opacity 280ms 200ms;
  transition: opacity 280ms 200ms;
}

.skinList .classCard .classImgC {
  position: absolute;
  margin-top: unset;
  width: 100px;
  margin: unset;
  right: 0;
  border-radius: 0;
  z-index: 12222 !important;
  -webkit-transition: -webkit-transform 500ms 200ms ease-in-out;
  transition: -webkit-transform 500ms 200ms ease-in-out;
  transition: transform 500ms 200ms ease-in-out;
  transition: transform 500ms 200ms ease-in-out, -webkit-transform 500ms 200ms ease-in-out;
}

.skinList .classCard .classXPBar {
  -webkit-box-shadow: unset;
          box-shadow: unset;
  position: absolute;
  top: unset;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 5px;
  border-radius: 0;
  background-color: transparent !important;
  -webkit-transition: opacity 280ms 200ms;
  transition: opacity 280ms 200ms;
}

.skinList .classCard .classXPBar .clsXPBarC {
  background-color: var(--accentColor);
  margin: unset;
  height: 100%;
}

.skinList .classCard .classLvl {
  font-family: var(--mainFont);
  text-shadow: unset;
  position: absolute;
  top: unset;
  bottom: 10%;
  font-size: 20px;
  -webkit-transition: opacity 280ms 200ms ease;
  transition: opacity 280ms 200ms ease;
  width: 100%;
  text-align: left;
  left: 10px;
}

.skinList .classCard .classHP {
  font-family: var(--mainFont);
  text-shadow: unset;
  color: var(--c_white);
  position: absolute;
  top: unset;
  left: 13px;
  font-size: 20px;
  bottom: 27%;
  right: -20%;
  -webkit-transform: rotate(-90deg);
          transform: rotate(-90deg);
  -webkit-transition: opacity 280ms 200ms;
  transition: opacity 280ms 200ms;
}

.skinList .classCard .classHP span {
  font-family: var(--mainFont);
  text-shadow: unset;
  color: var(--accentColor);
}

.skinList .classCard .lockedClass {
  position: absolute;
  top: 0;
  left: 0;
  border-radius: 4px;
  background-color: rgba(0, 0, 0, 0.5);
  padding: 0;
  padding-top: 0;
  top: 0 !important;
  bottom: 0 !important;
  right: 0 !important;
  left: 0 !important;
  width: 100%;
  height: 100%;
  display: -ms-grid;
  display: grid;
  place-items: center;
  z-index: 111111;
}

.skinList .classCard:hover {
  color: transparent !important;
}

.skinList .classCard:hover .classWeap {
  opacity: 0%;
}

.skinList .classCard:hover .classImgC {
  -webkit-transform: translateX(-115px) scale(2) translateY(10px);
          transform: translateX(-115px) scale(2) translateY(10px);
}

.skinList .classCard:hover .classXPBar {
  opacity: 0%;
}

.skinList .classCard:hover .classLvl {
  opacity: 0%;
}

.skinList .classCard:hover .classHP {
  opacity: 0%;
}

#skinList {
  margin-top: 8px;
  margin-bottom: -4px;
  display: -ms-grid;
  display: grid;
  -ms-grid-columns: 1fr 1fr 1fr;
      grid-template-columns: 1fr 1fr 1fr;
  -ms-grid-rows: min-content;
      grid-template-rows: -webkit-min-content;
      grid-template-rows: min-content;
  gap: 20px;
  padding: 1rem;
  height: calc(100% - 142px) !important;
}

#skinList::-webkit-scrollbar-track {
  background: var(--subBg) !important;
}

#skinList .skinCard {
  text-align: unset;
  margin-bottom: unset;
  margin-left: unset;
  margin-right: unset;
  padding: unset;
  padding-top: unset;
  width: auto;
  vertical-align: unset;
  background-color: transparent;
  border-radius: 0px;
  display: block;
  font-size: 20px;
  position: relative;
  z-index: 1;
  border-top: 0 !important;
  border-right: 0 !important;
  border-left: 0 !important;
  padding-bottom: 0.5rem;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: start;
      -ms-flex-align: start;
          align-items: flex-start;
  -webkit-box-pack: end;
      -ms-flex-pack: end;
          justify-content: flex-end;
  font-family: var(--mainFont);
  text-shadow: unset !important;
  height: 120px !important;
}

#skinList .skinCard .lockedCard {
  padding-top: 75px;
  padding: 0 !important;
  margin: 0;
  top: 0 !important;
  bottom: 0 !important;
  right: 0 !important;
  left: 0 !important;
  display: -ms-grid;
  display: grid;
  place-items: center;
}

#skinList .skinCard .itemOwn {
  display: none;
}

#skinList .skinCard .itemSea {
  display: none;
}

#skinList .skinCard .skinImg {
  margin-top: unset;
  margin-bottom: unset;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  width: 100%;
  height: 100%;
  -o-object-fit: contain;
     object-fit: contain;
}

#skinList .skinCard .skinImgC {
  position: absolute;
  z-index: -122;
  left: 25%;
}

#skinList .skinCard .skinImgD {
  position: absolute;
  left: 65px;
  bottom: -20px;
}

#skinList .skinCard .skinRandom {
  display: none;
}

#skinList .skinCard .secImg {
  position: absolute;
  left: 60px;
  top: 10px;
  z-index: -1 !important;
  width: 80px;
  height: 80px;
}

#skinList .skinCard .selctInfoBtn {
  padding: unset;
  padding-bottom: unset;
  padding-top: unser;
  position: absolute;
  top: 0;
  right: 0;
  color: var(--accentColor);
  font-family: var(--mainFont);
  font-size: 20px;
  background: var(--subBgST);
  padding-left: 12px;
  padding-right: 12px;
  -webkit-transition: color 280ms, background 280ms;
  transition: color 280ms, background 280ms;
}

#skinList .skinCard .selctInfoBtn:hover {
  color: var(--subBg);
  background: var(--accentColor);
}

#skinList .skinCard[style="color:#292929;border:5px solid#292929"] {
  color: var(--accentColor) !important;
  border-color: var(--accentColor) !important;
}

#skinList .noBtnCard {
  height: 120px;
  width: auto;
  border-left: 0 !important;
  border-right: 0 !important;
  border-radius: 0 !important;
  border-top: 0 !important;
  margin-left: unset;
  margin-right: unset;
  margin-bottom: unset;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: start;
      -ms-flex-align: start;
          align-items: flex-start;
  -webkit-box-pack: end;
      -ms-flex-pack: end;
          justify-content: flex-end;
  font-family: var(--mainFont);
  text-shadow: unset !important;
  height: 120px !important;
  background: var(--primaryBg);
  -webkit-filter: brightness(1.4);
          filter: brightness(1.4);
}

#skinList .noBtnCard div[style="color: #fff;margin-top: 33px;"] {
  position: absolute;
  margin: 0 !important;
  top: 0 !important;
  bottom: 0 !important;
  right: 0 !important;
  left: 0 !important;
  display: -ms-grid;
  display: grid;
  place-items: center;
  font-family: var(--mainFont);
  font-size: 1.4rem;
}

#skinList .noBtnCard .sprayImg,
#skinList .noBtnCard .noBtnImgC,
#skinList .noBtnCard .noBtnImgR {
  position: absolute;
  z-index: -1 !important;
  width: 80px;
  height: 80px;
  background-position: center !important;
  top: 50% !important;
  left: 50% !important;
  -webkit-transform: translate(-50%, -50%);
          transform: translate(-50%, -50%);
  padding: 0 !important;
  margin: 0 !important;
}

#skinList .noBtnCard .noBtnImgR {
  width: 30px;
  height: 30px;
}

#skinList .noBtnCard .customReticle {
  position: absolute;
  top: 40px;
  width: 182px;
}

#skinList .noBtnCard .itemOwn {
  display: none;
}

#skinList .noBtnCard .skinRandom {
  display: none;
}

#skinList .blackShad {
  text-shadow: unset;
}

#itemViewPop {
  height: 90vh;
  width: 90vw;
}

#itemViewPop iframe {
  width: 100% !important;
  height: 100% !important;
}

#itemSearchH {
  background: transparent;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  gap: 1rem;
}

#itemSearchH .custBack {
  background: var(--subBgST);
  border-radius: 100px;
  display: -ms-grid;
  display: grid;
  place-content: center;
  width: 5rem;
  height: 4.5rem;
  padding: 0;
  margin: 0;
}

#itemSearchH #itemSearch {
  all: unset;
  background: var(--primaryBg) !important;
  width: calc(100% - 3rem) !important;
  padding: 0.5rem 1.5rem;
  -webkit-filter: brightness(1.4);
          filter: brightness(1.4);
  border-radius: 100px;
  font-family: var(--subFont) !important;
  height: 2.5rem;
}

#menuWindow[style="overflow-y: auto; width: 810px; max-height: calc(100% - 480px); top: 50%; transform: translate(-50%, -50%);"],
#menuWindow[style="overflow-y: auto; max-height: calc(100% - 480px); top: 50%; transform: translate(-50%, -50%); width: 810px;"] {
  min-height: 60vh;
}

#selectorContainer {
  position: absolute;
  display: inline-block;
  width: 160px;
  height: 100%;
  background-color: transparent;
  -webkit-filter: unset;
          filter: unset;
  margin: 0px;
  top: 0;
  bottom: 0;
  left: 0;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
}

#selectorContainer .selectorItem {
  all: unset;
  cursor: pointer;
  display: -ms-grid;
  display: grid;
  place-content: center;
  width: 160px;
  height: 160px;
}

#selectorContainer .selectorItem .selectorLabel {
  all: unset;
  display: none;
}

#selectorContainer .selectorItem .selectorIcon {
  all: unset;
  pointer-events: none;
  width: 100px;
  height: 100px;
}

#selectorContainer .selectorItem .crisp-edges {
  image-rendering: -webkit-optimize-contrast;
  image-rendering: crisp-edges;
}

#selectorContainer .selectedItem {
  background-color: var(--primaryBg) !important;
  border-radius: 0px 10px 10px 0px;
  -webkit-filter: brightness(1.4) !important;
          filter: brightness(1.4) !important;
  border: none !important;
}

#selectorContainer .selectedItem:hover {
  -webkit-filter: brightness(1.1);
          filter: brightness(1.1);
}

#menuWindow[style="overflow-y: auto;width: 940px;max-height: calc(100% - 480px);top: 50%;transform: translate(-50%, -50%);"] {
  width: 900px !important;
}

#customizeContainer {
  min-height: 600px;
}

#customizeContainer .settName {
  border: none;
  font-family: var(--subFont);
  font-size: 1.6rem;
  margin-bottom: 2rem;
}

#customizeContainer #loadoutHolder span {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
  border-bottom: none !important;
}

#customizeContainer #loadoutHolder span #loadoutName {
  width: 153px !important;
  margin: 0 !important;
  padding: 1rem 1.5rem !important;
  border-radius: 100px !important;
  background: var(--primaryBg) !important;
  -webkit-filter: brightness(1.4) !important;
          filter: brightness(1.4) !important;
  font-family: var(--subFont);
  font-size: 1.4rem;
}

#customizeContainer #loadoutHolder span #loadoutSelect {
  all: unset !important;
  background: var(--orange2-dark) !important;
  -webkit-filter: brightness(1.4) !important;
          filter: brightness(1.4) !important;
  padding: 0.85rem 1rem !important;
  font-family: var(--mainFont) !important;
  border-radius: 10px !important;
  max-width: 9rem !important;
  width: -webkit-fit-content !important;
  width: -moz-fit-content !important;
  width: fit-content !important;
  min-width: 10px !important;
  margin: 0rem 1rem !important;
  cursor: pointer !important;
  font-size: 1.4rem !important;
  letter-spacing: 2px !important;
}

#customizeContainer #loadoutHolder span .loadoutBtn {
  all: unset;
  font-family: var(--mainFont);
  background: var(--primaryBg);
  -webkit-filter: brightness(1.4);
          filter: brightness(1.4);
  padding: 1rem 1rem;
  margin: 0rem 0.5rem;
  font-size: 1.2rem;
  letter-spacing: 1px;
  cursor: pointer !important;
}

#customizeContainer #loadoutHolder span .loadoutBtn:nth-child(3) {
  color: var(--orange) !important;
}

#customizeContainer #loadoutHolder span .loadoutBtn:nth-child(4) {
  color: var(--yellow) !important;
}

#customizeContainer #loadoutHolder span .loadoutBtn:nth-child(5) {
  color: var(--green) !important;
}

#customizeContainer div[style="border-bottom: 2px solid rgb(255,255,255,0.2);padding-bottom: 13px;margin-bottom: 13px;"] {
  border: 0 !important;
}

#customizeContainer .custContainer {
  background-color: transparent !important;
  border: none !important;
  -webkit-box-shadow: none !important;
          box-shadow: none !important;
  -webkit-transition: background-color 280ms ease;
  transition: background-color 280ms ease;
}

#customizeContainer .custContainer:hover {
  background-color: var(--subBg) !important;
}

#customizeContainer .custContainer .custItNm {
  display: none;
}

#customizeContainer .custContainer .settLabel {
  top: 0;
  left: 0;
  padding: 10px;
  position: absolute;
  font-size: 22px;
  font-family: var(--mainFont);
  letter-spacing: 2;
  text-shadow: none !important;
}

#customizeContainer .custContainer .settLabel[style*="color:#292929"] {
  color: var(--accentColor) !important;
}

#customizeContainer .custContainer .selRandom {
  font-family: var(--mainFont);
}

#customizeContainer .custContainer .settName {
  top: 0;
  left: 0;
  padding: 10px;
  padding-top: 20px;
}

#customizeContainer .custContainer[onclick*="(16)"] .settLabel,
#customizeContainer .custContainer[onclick*="(39)"] .settLabel,
#customizeContainer .custContainer[onclick*="(17)"] .settLabel,
#customizeContainer .custContainer[onclick*="(34)"] .settLabel,
#customizeContainer .custContainer[onclick*="(38)"] .settLabel,
#customizeContainer .custContainer[onclick*="(40)"] .settLabel,
#customizeContainer .custContainer[onclick*="(43)"] .settLabel,
#customizeContainer .custContainer[onclick*="(9)"] .settLabel {
  display: none !important;
}

#customizeContainer .custContainer[onclick*="(16)"] .custItNm,
#customizeContainer .custContainer[onclick*="(39)"] .custItNm,
#customizeContainer .custContainer[onclick*="(17)"] .custItNm,
#customizeContainer .custContainer[onclick*="(34)"] .custItNm,
#customizeContainer .custContainer[onclick*="(38)"] .custItNm,
#customizeContainer .custContainer[onclick*="(40)"] .custItNm,
#customizeContainer .custContainer[onclick*="(43)"] .custItNm,
#customizeContainer .custContainer[onclick*="(9)"] .custItNm {
  display: block;
  top: 0;
  left: 0;
  padding: 10px;
  position: absolute;
  font-size: 22px;
  font-family: var(--mainFont);
  letter-spacing: 2;
  text-shadow: none !important;
}

#customizeContainer .custIcon {
  margin: 0;
  padding: 0;
  position: absolute;
  width: 100%;
  height: 100%;
  -o-object-fit: contain;
     object-fit: contain;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}

.hostMap {
  border: 0;
  width: 283px;
}

.hostMap .blackShad {
  text-shadow: none;
}

.hostMap .hostMapYear,
.hostMap .hostMapVersion,
.hostMap .mapInfoT,
.hostMap .hostMapBy {
  display: none;
}

.hostMap .hostMapName {
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
          transform: translate(-50%, -50%);
  font-size: 20px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--c_white) !important;
  height: 120px;
  width: 269px;
  line-height: 28px;
  padding-right: 0px;
  z-index: 69;
  pointer-events: none;
  font-family: var(--mainFont);
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  padding-left: 15px;
  background: #00000057;
  -webkit-transition: color 280ms;
  transition: color 280ms;
}

.hostMap .hostMapImg {
  -webkit-transform: none;
          transform: none;
  -webkit-filter: grayscale(50%);
          filter: grayscale(50%);
}

.hostMap input:hover + .hostMapImg {
  -webkit-transform: none;
          transform: none;
  opacity: 1;
  -webkit-filter: blur(2px);
          filter: blur(2px);
}

.hostMap input:checked + .hostMapImg {
  -webkit-transform: none;
          transform: none;
  opacity: 1;
  -webkit-filter: blur(20px);
          filter: blur(20px);
}

.mapActionHol .material-icons {
  font-family: "Material Icons" !important;
}

#tlInfHold {
  top: 0;
  bottom: 0;
  left: unset;
  right: 0;
  width: 360px;
  -webkit-backdrop-filter: blur(var(--blur-radius1, 20px));
          backdrop-filter: blur(var(--blur-radius1, 20px));
  border-left: 4px solid #ffffff1c;
  background: #ffffff1f;
  z-index: 111111;
  pointer-events: all;
  right: -365px;
  -webkit-transition: right 800ms cubic-bezier(0.77, 0.01, 0.32, 0.99);
  transition: right 800ms cubic-bezier(0.77, 0.01, 0.32, 0.99);
}

#tlInfHold::after {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: -20px;
  width: 20px;
}

#tlInfHold::before {
  content: "keyboard_double_arrow_left";
  font-family: "Material Icons";
  position: absolute;
  top: 12%;
  left: -74px;
  width: auto;
  height: auto;
  color: white;
  display: -ms-grid;
  display: grid;
  place-content: center;
  font-size: 3rem;
  -webkit-transition: opacity 200ms;
  transition: opacity 200ms;
}

#tlInfHold:hover {
  right: 0;
}

#tlInfHold:hover::before {
  opacity: 0;
}

#tlInfHold #streamContainer {
  background: transparent;
  color: var(--c_white);
  margin: 0;
  padding: 0;
}

#tlInfHold #streamContainer #streamCon,
#tlInfHold #streamContainer #friendCon {
  display: block !important;
}

#tlInfHold #streamContainer .streamItem:first-child {
  margin: 0.5rem !important;
  padding: 1rem;
  border-radius: 5px;
  font-family: var(--mainFont);
}

#tlInfHold #streamContainer .streamItem:first-child .strmCat {
  font-family: var(--mainFont);
  font-size: 2rem;
  text-shadow: unset !important;
  margin: 0 !important;
}

#tlInfHold #streamContainer .streamItem:last-child {
  margin-bottom: 2rem !important;
}

#tlInfHold #streamContainer .streamItem:not(:first-child) {
  margin: 0.5rem;
  margin-bottom: 0.9rem;
  padding: 0.5rem 1rem;
  border-radius: 5px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
}

#tlInfHold #streamContainer .streamItem:not(:first-child) > *:not(:last-child) {
  margin-right: 1rem !important;
}

#tlInfHold #streamContainer .streamItem:not(:first-child) .strmIcn {
  background: transparent;
  margin: 0;
  width: 50px;
  height: 50px;
  image-rendering: -webkit-optimize-contrast;
}

#tlInfHold #streamContainer .streamItem:not(:first-child) .streamName {
  width: 100%;
  -webkit-transform: translateY(-3px);
          transform: translateY(-3px);
}

#tlInfHold #streamContainer .streamItem:not(:first-child) .streamName:hover {
  opacity: 1;
}

#tlInfHold #streamContainer .streamItem:not(:first-child) .streamName .strmLink {
  font-family: var(--mainFont);
  font-size: 1.4rem;
  text-shadow: unset !important;
  letter-spacing: 1px;
}

#tlInfHold #streamContainer .streamItem:not(:first-child) .streamName .strmPartner {
  margin: 0;
}

#tlInfHold #streamContainer .streamItem:not(:first-child) .streamName .strmPartner .streamPartner {
  color: var(--c_whiteST);
  margin-left: 2px;
  top: 5px;
}

#tlInfHold #streamContainer .streamItem:not(:first-child) .streamName .strmViews {
  font-family: var(--subFont);
  font-size: 1rem;
  color: var(--c_whiteST);
}

#tlInfHold #streamContainer .streamItem:not(:first-child):hover {
  background: #ffffff1f;
}

#tlInfHold #friendCon .strmIcn {
  border-radius: 5px;
}

#tlInfHold #friendCon .strmIcn[src*="./img/favicon.png"] {
  -ms-interpolation-mode: nearest-neighbor !important;
      image-rendering: -webkit-optimize-contrast !important;
      image-rendering: -moz-crisp-edges !important;
      image-rendering: -o-pixelated !important;
      image-rendering: pixelated !important;
}

#tlInfHold #friendCon .strmLink {
  line-break: anywhere;
}

#tlInfHold .frndQickJoin {
  position: unset;
}

#tlInfHold .frndQickJoin span {
  margin-top: 0px !important;
}

#tlInfHold .youNewDiv {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
  padding: 1rem 1.8rem;
  margin: 0;
  margin-bottom: 0rem;
  border-radius: 0px;
  background: #ffffff0d;
}

#tlInfHold .youNewDiv > *:not(:last-child) {
  margin-right: 1rem !important;
}

#tlInfHold .youNewDiv img,
#tlInfHold .youNewDiv #updateAdIcon {
  width: 50px;
  height: 50px;
  margin: 0;
  padding: 0;
  image-rendering: -webkit-optimize-contrast;
}

#tlInfHold .youNewDiv #helpTxtHol {
  font-family: var(--mainFont);
  font-size: 1.4rem;
  text-shadow: unset !important;
  letter-spacing: 1px;
  width: calc(100% - 4.8rem);
}

#tlInfHold .youNewDiv #helpTxtHol #helpGuidOpn,
#tlInfHold .youNewDiv #helpTxtHol #updateAdVersion {
  font-family: var(--subFont);
  font-size: 1rem;
  letter-spacing: unset;
  color: var(--c_whiteST);
}

#tlInfHold #twitchDropsAd {
  border-color: #9661f780;
  background: #9661f780 !important;
}

#adCon {
  display: none !important;
}

#menuWindow {
  background: var(--primaryBg) !important;
}

.settingsHeader {
  background: var(--primaryBg) !important;
}

#settingsTabLayout {
  background: transparent;
}

#settingsTabLayout .settingTab {
  padding: 15px 0 15px;
  background: unset;
  font-family: var(--mainFont);
  font-size: 1.4rem;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--c_whiteST) !important;
}

#settingsTabLayout .tabANew {
  color: var(--c_white) !important;
  border-bottom: 5px solid var(--accentColor) !important;
}

.setHed,
.setHedS {
  border: unset;
  background: transparent;
  font-family: var(--mainFont) !important;
  color: var(--accentColor) !important;
  -webkit-transition: background 280ms ease;
  transition: background 280ms ease;
  border-radius: 6px;
  padding: 10px 10px;
  margin-top: 25px;
  font-size: 2rem;
  letter-spacing: 1px;
  cursor: pointer;
}

.setHed:hover,
.setHedS:hover {
  background: var(--subBg) !important;
}

.setHed span,
.setHedS span {
  color: var(--c_white);
}

.setHed #requiresRestart,
.setHedS #requiresRestart {
  font-family: var(--subFont) !important;
  color: var(--c_whiteST) !important;
  font-size: 1.5rem;
}

.setHed #requiresRestart span,
.setHedS #requiresRestart span {
  font-size: 15px;
}

.setBodH {
  margin-bottom: 15px;
  margin-top: 0px;
  padding-bottom: unset;
  background: transparent;
}

.settName {
  font-family: var(--subFont) !important;
  color: var(--c_white) !important;
  font-size: 1.6rem;
  border-bottom: none;
  background: transparent;
  margin-bottom: 2rem;
  padding: 4px 0px;
  background: transparent !important;
}

.settName span {
  height: -webkit-fit-content;
  height: -moz-fit-content;
  height: fit-content;
  font-size: medium;
}

#gameNameHolder,
#seasonLabel,
#newsHolder {
  display: none;
}

#menuItemContainer {
  all: unset;
  position: fixed;
  bottom: 0;
  left: 0;
  width: 130px;
  height: 100%;
  padding-top: 5rem;
  -webkit-backdrop-filter: blur(var(--blur-radius1, 20px));
          backdrop-filter: blur(var(--blur-radius1, 20px));
  border-right: 4px solid #ffffff1c;
  background: #ffffff1f;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
  pointer-events: all;
}

#menuItemContainer::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  aspect-ratio: 1 / 1;
  height: 120px;
  background-image: var(--sidebar-logo, url("https://www.krunker.io/img/krunker.png"));
  background-size: 50%;
  background-position: center;
  background-repeat: no-repeat;
  -webkit-transform: translateY(80px);
          transform: translateY(80px);
  -webkit-filter: brightness(0) invert(1);
          filter: brightness(0) invert(1);
}

#menuItemContainer .menuItem {
  all: unset;
  display: -ms-grid;
  display: grid;
  place-items: center;
  pointer-events: all;
  cursor: pointer;
  width: 100%;
  height: 130px;
  aspect-ratio: 1 / 1;
  -webkit-transition: -webkit-transform 500ms ease;
  transition: -webkit-transform 500ms ease;
  transition: transform 500ms ease;
  transition: transform 500ms ease, -webkit-transform 500ms ease;
  margin-bottom: 0;
}

#menuItemContainer .menuItem:hover {
  background: var(--sidebarIconBgOnHover, #ffffff12) !important;
}

#menuItemContainer .menuItem:hover .menBtnIcn,
#menuItemContainer .menuItem:hover .menuItemIcon {
  color: var(--sidebarIconColorOnHover, white) !important;
  -webkit-filter: unset;
          filter: unset;
  -webkit-transform: scale(1.2);
          transform: scale(1.2);
}

#menuItemContainer .menuItem:first-child {
  margin-top: 7rem;
}

#menuItemContainer .menuItem .menuItemTitle {
  display: none;
}

#menuItemContainer .menuItem .menBtnIcn,
#menuItemContainer .menuItem .menuItemIcon {
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
  -webkit-filter: brightness(0) invert(1);
          filter: brightness(0) invert(1);
  -webkit-transition: -webkit-transform 400ms ease;
  transition: -webkit-transform 400ms ease;
  transition: transform 400ms ease;
  transition: transform 400ms ease, -webkit-transform 400ms ease;
}

#menuItemContainer #clientExit {
  margin-top: auto !important;
}

#menuItemContainer #clientExit span {
  background-image: url("../img/menu-icons/exit.png");
  background-size: 50%;
  background-position: center;
  width: 100%;
  height: 100%;
  color: transparent !important;
}

#menuItemContainer #clientExit:hover {
  background: #ffffff12 !important;
}

#signedOutHeaderBar {
  all: unset;
  position: fixed;
  top: 0;
  background: #ffffff1f;
  -webkit-backdrop-filter: blur(var(--blur-radius1, 20px));
          backdrop-filter: blur(var(--blur-radius1, 20px));
  height: 100px;
  width: calc(100% - 120px - 4.84rem);
  right: 0;
  padding: 0.5rem 2rem;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
  border-bottom: 4px solid #ffffff1c;
  border-radius: 0px !important;
  pointer-events: all;
}

#signedOutHeaderBar .lgn {
  width: unset !important;
}

#signedInHeaderBar {
  all: unset;
  position: fixed;
  top: 0;
  background: #ffffff1f;
  -webkit-backdrop-filter: blur(var(--blur-radius1, 20px));
          backdrop-filter: blur(var(--blur-radius1, 20px));
  height: 100px;
  width: calc(100% - 120px - 2.8rem);
  right: 0;
  padding: 0.5rem 2rem;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
  border-bottom: 4px solid #ffffff1c;
  pointer-events: all;
  border-radius: 0px !important;
}

#signedInHeaderBar .verticalSeparator {
  margin-left: 1rem;
  margin-right: 2rem;
  margin-top: 0.9rem;
  -webkit-transform: rotate(20deg);
          transform: rotate(20deg);
}

#signedInHeaderBar #menuUsernameContainer {
  margin-right: 1rem;
}

#signedInHeaderBar #menuUsernameContainer #menuMiniProfilePic {
  width: 60px;
  height: 100%;
  -ms-interpolation-mode: nearest-neighbor;
      image-rendering: -webkit-optimize-contrast;
      image-rendering: -moz-crisp-edges;
      image-rendering: -o-pixelated;
      image-rendering: pixelated;
  margin-right: unset;
  border-radius: unset;
  -webkit-filter: brightness(1.2);
          filter: brightness(1.2);
  margin-right: 2rem;
}

#signedInHeaderBar #menuUsernameContainer #menuAccountUsername {
  font-family: var(--mainFont);
  font-size: 1.8rem;
  letter-spacing: 2px;
  line-height: 60px;
}

#signedInHeaderBar #menuUsernameContainer #menuAccountUsername:hover {
  color: var(--accentColor);
}

#signedInHeaderBar .krInfo {
  margin-right: 1rem;
}

#signedInHeaderBar .krInfo #menuKRCount {
  font-size: 1.7rem;
  font-family: var(--mainFont);
  margin-right: 0.5rem;
  line-height: 60px;
}

#signedInHeaderBar .krInfo #menuKRCount span {
  color: white !important;
  font-size: 1.7rem;
  font-family: var(--mainFont);
}

#signedInHeaderBar .krInfo .krSocial {
  display: none;
}

#signedInHeaderBar .junkInfo #menuJNKCount {
  font-family: var(--mainFont);
  font-size: 1.7rem;
}

#signedInHeaderBar .junkInfo #menuJNKCount span {
  margin-left: 12px !important;
  margin-right: 0px !important;
  font-size: 2rem !important;
  -webkit-filter: brightness(2);
          filter: brightness(2);
}

#signedInHeaderBar #mailContainer #mailIcon:hover {
  color: var(--accentColor) !important;
}

#signedInHeaderBar #mLevelCont {
  all: unset;
  position: unset;
  left: unset;
  font-size: 1.8rem;
  letter-spacing: 1px;
  margin-left: 20px;
  background: #ffffff29;
  padding: 0rem 2rem;
  border-radius: 100px;
  color: var(--c_white);
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  margin-left: 3rem;
  padding-left: 2.4rem;
}

#signedInHeaderBar #mLevelCont::before {
  content: "LVL ";
  opacity: 0.5;
  margin-right: 0.5rem;
}

#signedInHeaderBar #mLevelCont::before,
#signedInHeaderBar #mLevelCont #mLevelContV {
  font-family: var(--mainFont);
  line-height: 54px;
}

#signedInHeaderBar #mLevelCont .rankClck {
  all: unset;
  height: -webkit-fit-content;
  height: -moz-fit-content;
  height: fit-content;
  aspect-ratio: 1 / 1;
  height: 36px;
  margin-left: 1rem;
}

#signedInHeaderBar #menuLvlHold {
  display: block;
  position: absolute;
  width: 100%;
  left: 0;
  height: 4px;
  bottom: -6px;
  background: transparent;
}

#signedInHeaderBar #menuLvlHold #menuLevelBar {
  background-image: -webkit-gradient(linear, left top, right top, from(var(--gradientColor4)), to(var(--gradientColor3)));
  background-image: linear-gradient(to right, var(--gradientColor4), var(--gradientColor3));
}

#headerRight {
  all: unset;
  position: fixed;
  top: 0;
  background: transparent;
  height: 100px;
  right: 0;
  padding: 0.5rem 2rem;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: end;
      -ms-flex-pack: end;
          justify-content: flex-end;
  border-bottom: 4px solid #ffffff1c;
  pointer-events: auto;
}

#headerRight #menuServerInfoContainer {
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: reverse;
      -ms-flex-direction: row-reverse;
          flex-direction: row-reverse;
}

#headerRight #menuServerInfoContainer > *:not(:first-child) {
  margin-right: 1.5rem !important;
}

#headerRight #menuServerInfoContainer #menuRegionLabel {
  font-family: var(--mainFont);
  font-size: 1.8rem;
}

#headerRight #menuServerInfoContainer .menuDebugInfo > *:not(:last-child) {
  margin-right: 1rem !important;
}

#headerRight #menuServerInfoContainer #menuFPSDisplay {
  font-family: var(--mainFont);
  font-size: 1.8rem;
}

#headerRight #menuServerInfoContainer #menuFPSDisplay #menuFPS {
  font-family: var(--mainFont);
  font-size: 1.8rem;
}

#headerRight #menuServerInfoContainer #menuPingDisplay {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

#headerRight #menuServerInfoContainer #menuPingDisplay > *:not(:last-child) {
  margin-right: 0.4rem;
}

#headerRight #menuServerInfoContainer #menuPingDisplay #menuPingIcon {
  font-family: "Material Icons";
  font-weight: normal;
  font-style: normal;
  font-size: 2rem;
}

#headerRight #menuServerInfoContainer #menuPingDisplay #menuPingIcon[style*="color: gray"] {
  color: var(--dirty-light) !important;
}

#headerRight #menuServerInfoContainer #menuPingDisplay #menuPingText {
  font-family: var(--mainFont);
  font-size: 1.8rem;
}

#headerRight #editorBtnM,
#headerRight .downloadClient,
#headerRight .redditSocial,
#headerRight .discordSocial,
#headerRight .verticalSeparator {
  display: none !important;
}

#headerRight .menuSocialB[onclick*="openDiscord()"] {
  margin-right: 40px !important;
  margin-left: 40px !important;
}

#headerRight .menuSocialB {
  cursor: pointer;
}

#aHider {
  display: none !important;
}

#subLogoButtons {
  position: absolute;
  bottom: unset;
  left: unset;
  -webkit-transform: unset;
          transform: unset;
  margin-top: 9rem;
  margin-left: 9rem;
}

#menuBtnRanked {
  pointer-events: initial;
}

#menuBtnRanked #rankedSoonTm {
  top: unset;
  bottom: -62px;
  border: none;
  background: #ffffff1f;
  font-family: var(--subFont);
  font-size: 1.3rem;
  font-weight: 100;
  opacity: 0;
  -webkit-transform: translateY(-10px);
          transform: translateY(-10px);
  -webkit-transition: opacity 300ms, -webkit-transform 300ms;
  transition: opacity 300ms, -webkit-transform 300ms;
  transition: opacity 300ms, transform 300ms;
  transition: opacity 300ms, transform 300ms, -webkit-transform 300ms;
}

#menuBtnRanked #rankedSoonTm::before {
  bottom: unset;
  top: -9px;
  -webkit-transform: translateX(-50%) rotate(180deg);
          transform: translateX(-50%) rotate(180deg);
  border-top: 9px solid white;
}

#menuBtnRanked:hover #rankedSoonTm {
  -webkit-transform: translateY(0);
          transform: translateY(0);
  opacity: 1;
}

.button {
  background-color: transparent;
  font-family: var(--mainFont);
  font-weight: bold;
  font-size: 2rem !important;
  border: none !important;
}

.button:hover {
  -webkit-filter: brightness(1.2);
          filter: brightness(1.2);
  border: none !important;
  color: var(--accentColor) !important;
}

.button.small {
  font-size: 2rem !important;
}

.buttonD,
.buttonD:hover {
  background-color: transparent !important;
  -webkit-box-shadow: unset !important;
          box-shadow: unset !important;
}

#menuClassContainer {
  height: 200px;
  width: 500px;
  position: absolute;
  top: unset;
  right: -45px;
  bottom: 240px;
  background-color: var(--primaryBg);
  pointer-events: all;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: start;
      -ms-flex-align: start;
          align-items: start;
  padding-left: 2rem;
  padding-right: 2rem;
  padding-top: 1rem;
  padding-bottom: 1rem;
  -webkit-box-pack: space-evenly;
      -ms-flex-pack: space-evenly;
          justify-content: space-evenly;
}

#menuClassContainer #bubbleContainer {
  display: none;
}

#menuClassContainer #classPreviewCanvas {
  position: absolute;
  top: -150.3%;
  left: -6%;
  z-index: -1;
}

#menuClassContainer #menuClassNameTag {
  margin-top: unset;
  position: unset;
  text-shadow: unset;
  font-family: var(--mainFont);
  font-size: 1.7rem;
  margin-bottom: 1rem;
}

#menuClassContainer #menuClassNameTag img[src*="img/ranked"] {
  display: none;
}

#menuClassContainer #menuClassNameTag .menuClassLevelBox {
  padding: unset;
  margin-right: 20px;
  font-size: unset;
  vertical-align: middle;
  text-shadow: unset;
  background: transparent;
  font-family: var(--mainFont);
}

#menuClassContainer #menuClassNameTag .menuClassPlayerName {
  text-shadow: unset;
  font-family: var(--mainFont);
}

#menuClassContainer #menuClassNameTag .menuClassPlayerClan {
  text-shadow: unset;
  font-family: var(--mainFont);
}

#menuClassContainer #menuClassSubtext {
  margin-bottom: unset;
  position: unset;
  text-shadow: unset;
  font-family: var(--mainFont);
}

#menuClassContainer #menuClassSubtext span {
  margin-bottom: unset;
  position: unset;
  text-shadow: unset;
  font-family: var(--mainFont);
  font-size: 2rem;
}

#menuClassContainer #menuClassSubtext span[style="color:#292929"] {
  color: var(--accentColor) !important;
  border-color: var(--accentColor) !important;
}

#menuClassContainer #menuClassName {
  margin-bottom: unset;
  position: unset;
  text-shadow: unset;
  font-family: var(--mainFont);
  display: none;
}

#menuClassContainer div #policeButton {
  margin: unset;
  color: unset;
  border: none;
  display: block;
  background-color: transparent !important;
  -webkit-box-shadow: unset !important;
          box-shadow: unset !important;
}

#menuClassContainer div #customizeButton {
  -webkit-box-shadow: unset !important;
          box-shadow: unset !important;
  display: block;
  position: absolute;
  right: 0;
  bottom: 7%;
  -webkit-transition: color 280ms;
  transition: color 280ms;
  color: var(--c_white);
  background: transparent !important;
  text-shadow: none !important;
  font-size: 30px !important;
  font-family: var(--mainFont);
}

#menuClassContainer div #customizeButton span {
  color: var(--c_white);
  font-family: "Material Icons";
  -webkit-transition: color 280ms;
  transition: color 280ms;
}

#menuClassContainer div #customizeButton:hover {
  color: var(--accentColor) !important;
  -webkit-transform: unset;
          transform: unset;
}

#menuClassContainer div #customizeButton:hover span {
  color: var(--accentColor) !important;
}

#hiddenClasses {
  position: absolute;
  bottom: 18px;
  right: 12px;
  left: unset;
  display: -ms-grid !important;
  display: grid !important;
  -ms-grid-columns: (1fr)[6];
      grid-template-columns: repeat(6, 1fr);
  -webkit-box-align: start;
      -ms-flex-align: start;
          align-items: flex-start;
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
  gap: 10px;
  width: calc(450px - 2rem);
  min-height: 200px;
  padding: 1rem;
  background: var(--primaryBg);
  -webkit-clip-path: polygon(0 0, 100% 0, 100% 95px, 0 95px);
          clip-path: polygon(0 0, 100% 0, 100% 95px, 0 95px);
  -webkit-transition: -webkit-clip-path 300ms ease;
  transition: -webkit-clip-path 300ms ease;
  transition: clip-path 300ms ease;
  transition: clip-path 300ms ease, -webkit-clip-path 300ms ease;
  pointer-events: initial;
}

#hiddenClasses:hover {
  -webkit-clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
          clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
}

#hiddenClasses > * {
  width: 61px;
  height: 61px;
  border-radius: 5px;
  cursor: pointer;
  pointer-events: fill;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 60%;
  -ms-interpolation-mode: nearest-neighbor;
      image-rendering: -webkit-optimize-contrast;
      image-rendering: -moz-crisp-edges;
      image-rendering: -o-pixelated;
      image-rendering: pixelated;
  -webkit-transition: background-color 300ms, -webkit-transform 300ms;
  transition: background-color 300ms, -webkit-transform 300ms;
  transition: background-color 300ms, transform 300ms;
  transition: background-color 300ms, transform 300ms, -webkit-transform 300ms;
}

#hiddenClasses > *:hover {
  background-color: var(--subBgST);
}

#hiddenClasses > *:active {
  -webkit-transform: scale(0.9);
          transform: scale(0.9);
}

#hiddenClasses #menuClassPicker0 {
  background-image: url("https://assets.krunker.io/textures/classes/icon_0.png");
}

#hiddenClasses #menuClassPicker1 {
  background-image: url("https://assets.krunker.io/textures/classes/icon_1.png");
}

#hiddenClasses #menuClassPicker2 {
  -ms-grid-row: 1;
  -ms-grid-column: 2;
  grid-area: 1 / 2;
  background-image: url("https://assets.krunker.io/textures/classes/icon_2.png");
}

#hiddenClasses #menuClassPicker3 {
  -ms-grid-row: 1;
  -ms-grid-column: 3;
  grid-area: 1 / 3;
  background-image: url("https://assets.krunker.io/textures/classes/icon_3.png");
}

#hiddenClasses #menuClassPicker4 {
  -ms-grid-row: 1;
  -ms-grid-column: 6;
  grid-area: 1 / 6;
  background-image: url("https://assets.krunker.io/textures/classes/icon_4.png");
}

#hiddenClasses #menuClassPicker5 {
  background-image: url("https://assets.krunker.io/textures/classes/icon_5.png");
}

#hiddenClasses #menuClassPicker6 {
  background-image: url("https://assets.krunker.io/textures/classes/icon_6.png");
}

#hiddenClasses #menuClassPicker6 {
  background-image: url("https://assets.krunker.io/textures/classes/icon_6.png");
}

#hiddenClasses #menuClassPicker7 {
  background-image: url("https://assets.krunker.io/textures/classes/icon_7.png");
}

#hiddenClasses #menuClassPicker8 {
  background-image: url("https://assets.krunker.io/textures/classes/icon_8.png");
}

#hiddenClasses #menuClassPicker9 {
  background-image: url("https://assets.krunker.io/textures/classes/icon_9.png");
}

#hiddenClasses #menuClassPicker11 {
  background-image: url("https://assets.krunker.io/textures/classes/icon_11.png");
}

#hiddenClasses #menuClassPicker12 {
  background-image: url("https://assets.krunker.io/textures/classes/icon_12.png");
}

#hiddenClasses #menuClassPicker13 {
  background-image: url("https://assets.krunker.io/textures/classes/icon_13.png");
}

#instructions {
  position: absolute;
  top: 50%;
  left: 50%;
  margin-right: -50%;
  -webkit-transform: translate(-50%, -50%);
          transform: translate(-50%, -50%);
  z-index: 9;
  font-size: 50px;
  font-family: var(--mainFont);
  word-spacing: 1rem;
  color: transparent;
  background-size: 450%;
  -webkit-animation: none;
          animation: none;
  color: var(--c_whiteST);
}

#instructionHolder * {
  font-family: var(--mainFont) !important;
}

#instructionHolder div {
  word-spacing: unset;
}

#mapInfoHolder {
  z-index: 1;
}

#mapInfoHolder div div {
  display: none !important;
}

#mapInfoHolder div div:last-child {
  display: inline-block !important;
}

#mapInfo {
  font-size: 24px;
  margin-bottom: 10px;
  font-family: var(--mainFont);
}

#termsInfo {
  background: var(--primaryBg);
  height: 30px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  padding-top: 12px;
}

#termsInfo .terms {
  font-family: var(--mainFont);
  font-size: 20px;
  color: var(--accentColor);
}

#spectButton {
  top: calc(50% - -50px) !important;
  padding: 0.5rem;
  background: var(--purple);
  border-radius: 60px;
  padding-left: 2rem;
  padding-right: 2rem;
  background-size: 450%;
  -webkit-animation: none !important;
          animation: none !important;
}

#spectButton span {
  color: var(--primaryBg) !important;
  font-family: var(--mainFont);
  font-size: 25px !important;
}

#spectButton .switchsml {
  margin-left: 1rem;
  -webkit-transform: translateY(-3px);
          transform: translateY(-3px);
}

#spectButton .sliderSml {
  background: var(--c_whiteST);
}

#spectButton input:checked + .sliderSml:before {
  background: var(--primaryBg);
}

#spectButton .sliderSml::before {
  background: var(--subBgST);
}

.chatItem {
  font-family: var(--mainFont);
  font-size: 20px;
  padding-right: 5px;
  background: transparent !important;
  max-width: 265px;
}

.chatItem span {
  font-family: var(--subFont);
  font-size: 22px;
  background: transparent !important;
}

.chatItem span[style="color:#fc03ec"] {
  color: #ff73b5 !important;
}

#chatHolder {
  position: absolute;
  z-index: 1000;
  width: 300px;
  bottom: 20px;
  left: 20px;
  background: rgba(0, 0, 0, 0.4);
  padding: 0;
  border-radius: 5px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-pack: end;
      -ms-flex-pack: end;
          justify-content: flex-end;
  min-height: 300px;
  -webkit-mask-image: -webkit-gradient(linear, left top, left bottom, from(transparent), color-stop(black), to(black));
  -webkit-mask-image: linear-gradient(to bottom, transparent, black, black);
          mask-image: -webkit-gradient(linear, left top, left bottom, from(transparent), color-stop(black), to(black));
          mask-image: linear-gradient(to bottom, transparent, black, black);
}

#chatHolder #chatList {
  background: transparent;
}

#chatHolder #chatList::-webkit-scrollbar-thumb {
  background: var(--c_whiteST);
}

#chatHolder #chatList::-webkit-scrollbar-track {
  background-color: transparent;
}

#chatInputHolder {
  width: 100%;
  padding: 6px;
  padding-left: unset;
  margin-top: 6px;
  font-size: 15px;
  -webkit-box-sizing: border-box;
          box-sizing: border-box;
  background-color: rgba(0, 0, 0, 0.1);
  border: unset;
  pointer-events: all;
  border-radius: 5px;
  text-align: center;
  color: #fff;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

#chatInputHolder:not(:last-child) {
  margin-right: 0.5rem;
}

#chatSwitchHolder {
  display: block;
  padding-left: 10px;
  padding-right: 10px;
}

#chatInput {
  margin-left: 0px;
  width: 100%;
  margin: 0;
  background: transparent !important;
  border: 0;
  padding: 0px;
  padding-bottom: 5px;
  font-family: var(--subFont);
  font-size: 22px !important;
  color: var(--c_white) !important;
}

.mapActionB .material-icons {
  font-family: "Material Icons" !important;
}

#modVote {
  font-size: 24px;
  font-family: var(--mainFont);
  margin-bottom: 10px;
}

#modVoteHold {
  display: inline-block;
  margin-right: 1rem;
}

#modVoteHold #modVoteD {
  color: var(--accentColor) !important;
  background-color: transparent !important;
}

#modVoteHold #modVoteU {
  color: var(--l-accentColor) !important;
  background-color: transparent !important;
}

#bottomLeftHolder {
  background: -webkit-gradient(linear, left bottom, left top, from(transparent), to(var(--subBgST))) !important;
  background: linear-gradient(to top, transparent, var(--subBgST)) !important;
  width: 304px;
  border-radius: 7px;
}

#bottomLeftHolder div[style="display:inline-block;vertical-align:bottom"] {
  display: -webkit-box !important;
  display: -ms-flexbox !important;
  display: flex !important;
  vertical-align: unset !important;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: end;
      -ms-flex-align: end;
          align-items: flex-end;
  -webkit-box-pack: end;
      -ms-flex-pack: end;
          justify-content: flex-end;
  height: auto;
  width: 100%;
  position: absolute !important;
  bottom: 0;
  margin: 0;
  padding: 0;
}

#bottomLeftHolder #hudClassIcon {
  width: 80px;
  height: auto;
  border-radius: 0;
  margin-right: 5px;
  margin-bottom: 10px;
  display: inline-block;
  background-color: transparent;
  position: relative;
}

#bottomLeftHolder #hudClassIcon #hudClassImg {
  opacity: var(--profile-pic-op, 1);
}

#bottomLeftHolder #hudClassIcon::after {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  width: 80px;
  height: 80px;
  border-radius: 7px;
  background-image: var(--profile-pic);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  z-index: -1;
}

#bottomLeftHolder #healthValueHolder {
  right: 0;
  display: block;
  background-color: transparent;
  border-radius: 0;
  padding: 0;
  margin-bottom: 18px;
  padding-right: 20px;
  position: absolute;
  bottom: 0;
  letter-spacing: 0.1rem;
}

#bottomLeftHolder #healthValueHolder #healthValue {
  font-family: var(--mainFont);
  font-size: 45px;
  color: var(--c_white);
}

#bottomLeftHolder #healthValueHolder #healthValue span {
  font-family: var(--subFont);
  font-size: 20px;
  color: var(--c_whiteST);
  opacity: 0.7;
}

#bottomLeftHolder #healthValueHolder #challIcon {
  display: none;

}
*/

    /* HEALTH */
#healthValueHolder {
	background-color: var(--transp);
	width: 75px;
	height: 65px;
	etter-spacing: 1px;
	position: fixed;
	left: 40%;
	bottom: 10%;
	margin-bottom: 10%;
	align-items: center
}
#healthValue {
	font-size: 40px;
	text-align: center;
	color: var(--white);
	margin-top: 0;
	will-change: unset;
	text-shadow: var(--outline)
}
#teamName {
  display: none;
}

.leaderItem .material-icons {
  font-family: "Material Icons" !important;
}

#botRightHider #weapDisplay {
  display: -webkit-box !important;
  display: -ms-flexbox !important;
  display: flex !important;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  -webkit-box-align: end;
      -ms-flex-align: end;
          align-items: flex-end;
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
  width: 300px;
  height: auto;
  -webkit-transform: translate(5px, 70px);
          transform: translate(5px, 70px);
  z-index: 699;
}

#botRightHider #weapDisplay .weapItem {
  width: auto;
  height: 100%;
  -webkit-transition: opacity 280ms;
  transition: opacity 280ms;
}

#botRightHider #weapDisplay .weapItem image {
  -webkit-transition: all 280ms;
  transition: all 280ms;
}

#botRightHider #weapDisplay .weapItem .weapIcon {
  width: 70px;
  height: auto;
  opacity: 0.3 !important;
  -webkit-transition: all 280ms;
  transition: all 280ms;
}

#botRightHider #weapDisplay .weapItem .weapKey {
  display: none;
}

#botRightHider #weapDisplay #weapItem_0 .weapIcon[style="opacity: 1;"],
#botRightHider #weapDisplay #weapItem_0 .weapIcon[style="opacity:1"] {
  opacity: 0.8 !important;
  -webkit-filter: contrast(3.5);
          filter: contrast(3.5);
  -webkit-transform: translate(30px, -50px) scale(1.6);
          transform: translate(30px, -50px) scale(1.6);
}

#botRightHider #weapDisplay #weapItem_1 .weapIcon[style="opacity: 1; margin-right: 25px;"] {
  opacity: 0.8 !important;
  -webkit-filter: contrast(3.5);
          filter: contrast(3.5);
  -webkit-transform: translate(-50px, -40px) scale(1.5);
          transform: translate(-50px, -40px) scale(1.5);
}

#botRightHider #weapDisplay #weapItem_2 .weapIcon[style="opacity: 1; margin-right: 25px;"] {
  opacity: 0.8 !important;
  -webkit-filter: contrast(3.5);
          filter: contrast(3.5);
  -webkit-transform: translate(-120px, -40px) scale(1.6);
          transform: translate(-120px, -40px) scale(1.6);
}

@-webkit-keyframes breathe {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@keyframes breathe {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

#reloadMsg {
  position: absolute;
  left: unset;
  top: unset;
  bottom: 130px;
  right: 20px;
  background: transparent;
  border: none;
  font-family: var(--mainFont);
}

#reloadMsg::after {
  -webkit-animation: breathe 1s infinite alternate;
          animation: breathe 1s infinite alternate;
  content: "report_problem";
  font-size: 40px;
  font-family: "Material Icons";
  position: absolute;
  left: unset;
  top: unset;
  bottom: 5.5px;
  right: 10px;
}

#bottomRight {
  width: 304px;
  border-radius: 7px;
}



    /* AMMO */
#ammoDisplay {
    background-color: var(--transp) !important;
    width: 65px;
    height: 10px;
	top: calc(50% + 35px);
    left: 48.76%
}
#ammoVal {
    position: fixed;
    right: 40% !important;
    bottom: 10% !important;
    margin-bottom: 10% !important;
    font-size: 40px !important;
    text-shadow: var(--outline);
}
#ammoDisplay {
    background-color: var(--transp);
    letter-spacing: 1px;
    border-radius: 0px;
    position: fixed;
    right: 40%;
    bottom: 10%;
    margin-bottom: 10%;
    padding: 0;
    padding-top: 0;
    padding-left: 0;
    transform: none;
}




#igXPBar {
  display: none !important;
}

#topLeftHolder {
  top: 40px;
}

#topLeftHolder * {
  font-family: var(--mainFont) !important;
  font-size: 1.5rem;
}

#topLeftHolder .tScoreF {
  font-family: Material Icons !important;
}

#topLeftHolder #roundsDisplay {
  background: transparent;
}

#topLeftHolder #roundsDisplay #roundsVal {
  letter-spacing: 10px;
  margin-right: 1rem;
}

#topLeftHolder #roundsDisplay #roundsVal::first-letter {
  font-size: 3.5rem;
}

#topLeftHolder #roundsDisplay #roundsVal:not(::first-letter) {
  opacity: 0.5;
}

#topLeftHolder #roundsDisplay #roundSub {
  font-family: var(--subFont) !important;
}

#topLeftHolder #curGameInfo > div {
  display: none;
}

#topLeftHolder #timerDisplay {
  background: transparent !important;
  padding: 0 !important;
  margin: 0 !important;
}

#topLeftHolder #timerDisplay #timerIcon {
  display: none;
  width: 0;
  height: 0;
}

#topLeftHolder #timerDisplay #timerVal {
  font-size: 60px !important;
  padding: 0 !important;
  margin: 0 !important;
}

#topLeftHolder .debugInfo {
  display: inline-block;
  vertical-align: unset;
  position: absolute;
  top: 0;
  left: 0;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  -webkit-transform: translate(5px, -35px);
          transform: translate(5px, -35px);
}

#topLeftHolder .debugInfo #fpsDisplay[style="display: block;"] {
  display: -webkit-box !important;
  display: -ms-flexbox !important;
  display: flex !important;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  font-family: var(--mainFont) !important;
  width: 100px;
  margin-right: 1.5rem;
}

#topLeftHolder .debugInfo #fpsDisplay[style="display: block;"] #ingameFPS {
  margin-right: 6px;
}

#topLeftHolder .debugInfo #pingDisplay[style="display: block;"] {
  display: -webkit-box !important;
  display: -ms-flexbox !important;
  display: flex !important;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  width: 100px;
  margin-right: 1.5rem;
}

#topLeftHolder .debugInfo #pingDisplay[style="display: block;"] #pingIcon {
  margin-left: 6px;
  font-size: 28px;
  font-family: Material Icons !important;
}

#topLeftHolder .debugInfo #ingressDisplay[style="display: block;"] {
  display: -webkit-box !important;
  display: -ms-flexbox !important;
  display: flex !important;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  width: 280px;
  margin-right: 1.5rem;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

#topLeftHolder .debugInfo #ingressDisplay[style="display: block;"] #ingressIcon {
  margin-left: 6px;
  margin-right: 2px;
  font-size: 28px;
  color: var(--gradientColor1) !important;
  font-family: Material Icons !important;
}

#topLeftHolder .debugInfo #ingressDisplay[style="display: block;"] #ingressDataSize {
  margin-left: 1rem;
  text-align: left;
  width: 200px;
}

#topLeftHolder .debugInfo #egressDisplay[style="display: block;"] {
  display: -webkit-box !important;
  display: -ms-flexbox !important;
  display: flex !important;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  width: 280px;
  margin-right: 1.5rem;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

#topLeftHolder .debugInfo #egressDisplay[style="display: block;"] #egressIcon {
  margin-left: 6px;
  margin-right: 2px;
  font-size: 28px;
  color: var(--gradientColor2) !important;
  font-family: Material Icons !important;
}

#topLeftHolder .debugInfo #egressDisplay[style="display: block;"] #egressDataSize {
  margin-left: 1rem;
  text-align: left;
  width: 200px;
}

#killFeed > div .kfItem {
  background-color: unset;
}

#killFeed > div .kfItem .kfMsg span {
  font-family: var(--mainFont) !important;
  font-size: 1.4rem;
}

.topRightCounters {
  position: fixed;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  left: 50%;
  bottom: 0;
  -webkit-transform: translateX(-50%);
          transform: translateX(-50%);
  margin-bottom: 50px;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
}

.topRightCounters .countIcon {
  background: transparent;
  font-size: 2.8rem !important;
  padding: 0 !important;
  margin: 0;
  text-align: center;
  display: -webkit-box !important;
  display: -ms-flexbox !important;
  display: flex !important;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
  -webkit-box-align: end;
      -ms-flex-align: end;
          align-items: flex-end;
  margin-right: 5rem;
}

.topRightCounters .countIcon img,
.topRightCounters .countIcon i {
  display: none;
}

.topRightCounters .countIcon span {
  font-family: var(--mainFont);
  letter-spacing: 1px;
}

.topRightCounters .countIcon::after {
  font-family: var(--subFont);
  font-size: 20px;
  color: var(--c_whiteST);
  text-align: left;
  margin-bottom: 10px;
  margin-left: 0.8rem;
}

.topRightCounters .countIcon:last-child {
  margin-right: 0px;
}

.topRightCounters .countIcon[style*="display: none;"] {
  display: none !important;
}

.topRightCounters #scoreZoneCount::after {
  content: "Score Zone";
}

.topRightCounters #livesCount::after {
  content: "Lives";
}

.topRightCounters #killCount::after {
  content: "Kills";
}

.topRightCounters #deathCount::after {
  content: "Deaths";
}

.topRightCounters #streakCount::after {
  content: "Streak";
}

.topRightCounters #kdCount::after {
  content: "K/D";
}

.topRightCounters #scoreCount::after {
  content: "Score";
}

#endAHolderL,
#endAHolderR {
  display: none !important;
}

#endTabbedView * {
  font-family: var(--mainFont) !important;
  font-size: 1.5rem;
}

#endTabbedView #endTable td .endTableN[style="color:#fff"] {
  position: relative;
}

#endTabbedView #endTable td .endTableN[style="color:#fff"]::before {
  content: var(--profile-pic-sp, unset);
  position: absolute;
  left: -54px;
  top: -5px;
  width: 40px;
  height: 40px;
  border-radius: 100px;
  background: var(--primaryBg);
  background-image: var(--profile-pic);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  color: transparent;
  image-rendering: optimizeQuality;
}

#endTabbedView #endTable td .endTableFlag {
  z-index: 1;
}

#endTabbedView #endTable td a .endTableN span {
  font-family: "Material Icons" !important;
}

#endTabbedView #endTable td .material-icons {
  font-family: "Material Icons" !important;
}

.endTablePfp {
  background: var(--subBgST);
  border-color: var(--subBgST);
}

.matchVote {
  position: relative;
  margin-bottom: 10px;
  height: 80px;
  width: 200px;
  overflow: hidden;
  margin-right: 8px;
  display: inline-block;
  margin-top: 10px;
  border-radius: 4px;
  text-shadow: none;
  border-color: var(--primaryBg);
}

.matchVote .matchVoteModifier {
  top: 0;
  bottom: unset;
  right: 0;
  left: unset;
  border-radius: 0px;
  border-bottom-left-radius: 10px;
  margin: 0;
  font-size: 16px !important;
  padding: 0.2rem 0.5rem;
  font-family: var(--subFont);
}

.matchVote .matchVoteMap {
  position: absolute;
  color: var(--c_white);
  line-height: 28px;
  padding-right: 0px;
  z-index: 2;
  pointer-events: none;
  font-family: var(--mainFont);
  font-size: 18px;
  letter-spacing: 1px;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  padding-top: 13px;
  padding-left: 10px;
  text-align: start;
}

.matchVote .matchVoteMode {
  position: absolute;
  top: 45%;
  left: 0;
  padding-left: 10px;
  font-size: 23px;
  height: auto;
  padding-right: 0px;
  z-index: 2;
  font-family: var(--mainFont);
  color: var(--c_white);
  pointer-events: none;
}

.matchVote .matchVoteTotal {
  position: absolute;
  font-size: 30px;
  height: auto;
  z-index: 1;
  padding-left: 0px;
  color: var(--c_white);
  pointer-events: none;
  padding: 10px;
  font-family: var(--mainFont);
  padding-left: 15px;
  color: var(--c_white);
  pointer-events: none;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: end;
      -ms-flex-align: end;
          align-items: flex-end;
  -webkit-box-pack: end;
      -ms-flex-pack: end;
          justify-content: flex-end;
  padding-right: 1rem;
}

.matchVote .matchVoteTotal::after {
  content: "";
  position: absolute;
  background: transparent;
  -webkit-backdrop-filter: blur(0px);
          backdrop-filter: blur(0px);
  z-index: -2;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  -webkit-transition: -webkit-backdrop-filter 300ms;
  transition: -webkit-backdrop-filter 300ms;
  transition: backdrop-filter 300ms;
  transition: backdrop-filter 300ms, -webkit-backdrop-filter 300ms;
}

.matchVote .matchVoteTotal::before {
  content: "";
  position: absolute;
  top: 0 !important;
  bottom: 0 !important;
  right: 0 !important;
  left: 0 !important;
  background: #00000057;
  z-index: -1;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}

.matchVote .matchVoteTotal[style*="color: rgb(251, 192, 45)"] {
  color: var(--accentColor) !important;
}

.matchVote .matchVoteTotal[style*="color: rgb(251, 192, 45)"]::after {
  -webkit-backdrop-filter: blur(var(--blur-radius2, 5px));
          backdrop-filter: blur(var(--blur-radius2, 5px));
}

.matchVote .matchVoteThumb {
  -webkit-transform: none;
          transform: none;
  top: 1px;
  left: 1px;
  height: 77px;
  width: 198px;
}

.tabHeader.selected {
  color: var(--accentColor);
  border-bottom: 4px solid var(--accentColor);
}

span[style*="color:#F8C55C"] {
  color: var(--accentColor) !important;
}

#lvlLayout .xpLvl {
  margin-top: 0;
  display: -ms-grid;
  display: grid;
  place-content: center;
}

.xpEndBar {
  width: calc(100% - 2rem);
  height: 21px;
  padding: 6px;
  background-color: rgba(0, 0, 0, 0.4);
  border-radius: 100px;
  position: relative;
  margin: 5px 1rem;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.xpEndBar .xpEndBarB:first-child {
  background-image: -webkit-gradient(linear, left top, right top, from(var(--gradientColor4)), to(var(--gradientColor3)));
  background-image: linear-gradient(to right, var(--gradientColor4), var(--gradientColor3));
  border-radius: 100px;
  z-index: 0;
  border-bottom-right-radius: 0px;
  border-top-right-radius: 0px;
}

.xpEndBar .xpEndBarB:nth-child(2) {
  background: var(--accentColor) !important;
  -webkit-box-shadow: 0px 0px 8px var(--accentColor);
          box-shadow: 0px 0px 8px var(--accentColor);
  margin-left: 0px !important;
  border-radius: 100px;
  z-index: 0;
  border-top-left-radius: 0px;
  border-bottom-left-radius: 0px;
}

.xpEndBar .xpEndBarV {
  display: -ms-grid;
  display: grid;
  place-content: center;
  padding: 0;
  top: 0;
  font-size: 14px !important;
  font-family: var(--subFont) !important;
  letter-spacing: 2px;
  word-spacing: 7px;
}

.ot-floating-button {
  display: none;
}

#seasonLabel {
  display: none !important;
}

.serverHeader {
  background-color: var(--primaryBg);
}

.setBodH[style="padding:10px;margin-top:0px;margin-bottom:8px;width:calc(100% - 20px) !important;margin-left:0px;"] div[style="display:inline-block"] a {
  font-family: var(--mainFont) !important;
  margin-right: 2rem;
  font-size: 1.8rem;
}

#hideFull span {
  font-family: var(--mainFont) !important;
  font-size: 1.7rem !important;
}

#hostMenuBtn {
  margin-left: 2rem;
  background-color: var(--subBgST);
  width: 5rem;
  border-radius: 100px;
  display: -ms-grid;
  display: grid;
  place-content: center;
}

#hostMenuBtn span {
  color: var(--accentColor) !important;
  font-size: 28px !important;
  margin-bottom: 0px !important;
}

.slide {
  position: relative;
  border: 15px solid transparent;
}

.slide:after {
  content: "";
  position: absolute;
  top: 0 !important;
  bottom: 0 !important;
  right: 0 !important;
  left: 0 !important;
  background: #00000082;
  z-index: 1;
}

.slide .slideName {
  z-index: 111;
  text-shadow: unset;
  font-family: var(--mainFont);
  font-size: 1.5rem;
  color: white !important;
}

.slide .slidePlayers {
  z-index: 111;
  text-shadow: unset;
  font-family: var(--subFont);
  font-size: 1.1rem;
  color: var(--c_white) !important;
}

#serverHolder .setHed span[style="float:right;color:rgba(255,255,255,0.9)"] {
  display: none;
}

#serverHolder .setHed .quickJoin {
  margin: 0;
  border-color: transparent;
  background: var(--subBgST);
  font-family: var(--subFont);
  font-size: 1.2rem;
}

#serverHolder .setHed .quickJoin:hover {
  background: var(--accentColor);
  color: var(--primaryBg);
}

#serverHolder .setBodH[style="padding-top:10px;padding-bottom:10px;"] {
  padding-left: 0px;
  padding-right: 0px;
  width: 100% !important;
}

#serverHolder .setBodH[style="padding-top:10px;padding-bottom:10px;"] .settName {
  margin-bottom: 1rem;
  padding: 1rem;
  border-radius: 5px;
}

#serverHolder .setBodH[style="padding-top:10px;padding-bottom:10px;"] .settName:hover {
  background: var(--subBg) !important;
}

#serverHolder .setBodH[style="padding-top:10px;padding-bottom:10px;"] .settName .serverPCount,
#serverHolder .setBodH[style="padding-top:10px;padding-bottom:10px;"] .settName .serverRegion {
  font-family: var(--mainFont) !important;
  font-size: 1.8rem;
  color: var(--c_white) !important;
}

#serverHolder .setBodH[style="padding-top:10px;padding-bottom:10px;"] .settName .serverRegion {
  color: var(--c_whiteST) !important;
}

.serverHostOpH,
.hostHeader {
  font-family: var(--mainFont);
  font-size: 2.5rem;
  background: var(--primaryBg) !important;
}

.mapListCat {
  font-family: var(--mainFont);
  color: var(--accentColor) !important;
  -webkit-transform: translateX(-10px);
          transform: translateX(-10px);
  background: transparent;
  letter-spacing: 1px;
}

#hostCMapPickT {
  font-family: var(--mainFont);
  letter-spacing: 2px;
  font-size: 3rem !important;
}

#startServBtn {
  border: 10px solid var(--primaryBg);
  color: var(--primaryBg) !important;
  border-radius: 6px;
  padding: 13px 0px !important;
  -webkit-transition: -webkit-transform 400ms;
  transition: -webkit-transform 400ms;
  transition: transform 400ms;
  transition: transform 400ms, -webkit-transform 400ms;
}

#startServBtn:hover {
  -webkit-transform: scale(0.9);
          transform: scale(0.9);
}

#hostGameMsg span {
  font-family: var(--mainFont);
  font-size: 1.5rem;
}

#stickyHostH {
  border: transparent;
  background: var(--primaryBg);
  font-family: var(--subFont);
  font-size: 1.5rem;
}

#stickyHostH span {
  font-family: var(--mainFont);
}

.serverHostOp {
  border: 6px solid rgba(0, 0, 0, 0.2);
  border-color: var(--primaryBg);
  font-family: var(--subFont);
  font-size: 3rem;
  text-shadow: unset;
  position: relative;
  -webkit-transition: color 280ms;
  transition: color 280ms;
  z-index: 101;
}

.serverHostOp::before {
  content: "";
  position: absolute;
  top: 0 !important;
  bottom: 0 !important;
  right: 0 !important;
  left: 0 !important;
  background: #000000b3;
  z-index: -1;
  -webkit-transition: background 280ms;
  transition: background 280ms;
}

.serverHostOp:hover {
  color: var(--primaryBg) !important;
}

.serverHostOp:hover::before {
  background: var(--accentColorST);
}

.hostHeader {
  background: transparent;
  border: none !important;
}

#krRewardsInfo div {
  background: var(--subBgST) !important;
  border-color: transparent !important;
  font-family: var(--subFont);
  font-size: 1.4rem !important;
}

.settNameSmall {
  border: none !important;
  font-family: var(--subFont);
  font-size: 1.6rem !important;
  margin-bottom: 2rem !important;
}

#hostActionH {
  border: none !important;
  padding: 1rem !important;
  background: var(--subBgST) !important;
  border-radius: 5px;
}

#hostActionH div[style="color:rgba(255,255,255,0.3);font-size:22px"] {
  font-family: var(--mainFont);
  font-size: 1.5rem !important;
}

#hostActionH div[style="color:rgba(255,255,255,0.3);font-size:22px"] span {
  font-family: var(--subFont);
  font-size: 1.5rem !important;
}

#hostActionH .hostCBtn {
  border: none;
  background: var(--subBgST);
  font-family: var(--mainFont);
  font-size: 2rem;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: var(--accentColor) !important;
}

#commMap {
  font-family: var(--mainFont);
  font-size: 1.8rem !important;
}

.hostToggle,
.advancedToggle {
  border-color: transparent !important;
  padding: 0.4rem 0.6rem;
  letter-spacing: 1px;
  font-family: var(--subFont);
  font-size: 1.2rem;
  background: var(--accentColorST);
  color: var(--accentColor) !important;
}

.hostToggle:hover,
.advancedToggle:hover {
  background: var(--accentColor);
  color: var(--primaryBg) !important;
}

.advancedToggle {
  background: var(--subBgST);
  color: var(--accentColor);
}

.advancedToggle[style="background-color: rgb(33, 150, 243);"] {
  background: var(--accentColor) !important;
  color: var(--primaryBg) !important;
}

.hostOpt {
  background-color: transparent;
  border-color: transparent;
  height: 3rem;
  width: 208.4px;
}

.hostOpt .optName {
  position: absolute;
  top: 50%;
  -webkit-transform: translateY(-50%);
          transform: translateY(-50%);
  font-family: var(--subFont);
  text-shadow: none;
  font-size: 1.2rem;
}

.hostOpt .optImg {
  top: 50%;
  -webkit-transform: translateY(-50%);
          transform: translateY(-50%);
}

.hostOpt input:checked + .optCheck {
  background-color: var(--accentColorST);
}

.hostOpt .optCheck {
  background: var(--subBgST);
}

.hostOpt input:hover + .optCheck {
  background-color: var(--subBgST) !important;
  -webkit-filter: brightness(1.4) !important;
          filter: brightness(1.4) !important;
}

.hostPresetBtn {
  float: right;
}

.hostPresetBtn:nth-child(3) {
  color: var(--orange) !important;
}

.hostPresetBtn:nth-child(4) {
  color: var(--green) !important;
}

.hostPresetBtn:nth-child(5) {
  color: var(--purple) !important;
}

.hostPresetBtn:last-child {
  margin-right: 1rem;
}

#referralHeader {
  font-family: var(--mainFont);
  font-size: 2.5rem;
  background: transparent;
}

#accName {
  margin-bottom: 1.5rem !important;
}

#accName,
#accPass {
  font-family: var(--subFont) !important;
  font-size: 1.4rem !important;
  padding: 1.7rem 3rem !important;
  font-size: 1.7rem !important;
  margin: 1rem 1.5rem !important;
  width: 94%;
}

#accName::-webkit-input-placeholder,
#accPass::-webkit-input-placeholder {
  font-size: 1.7rem !important;
}

#accName:-ms-input-placeholder,
#accPass:-ms-input-placeholder {
  font-size: 1.7rem !important;
}

#accName::-ms-input-placeholder,
#accPass::-ms-input-placeholder {
  font-size: 1.7rem !important;
}

#accName::placeholder,
#accPass::placeholder {
  font-size: 1.7rem !important;
}

#accResp {
  font-family: var(--subFont);
  font-size: 1.5rem !important;
}

#accResp span {
  font-family: var(--mainFont);
}

div[style="width:100%;text-align:center;margin-top:10px;background-color:rgba(0,0,0,0.3);padding-top:10px;padding-bottom:20px;"] {
  background: transparent !important;
}

.accBtn {
  background: var(--subBgST) !important;
  padding: 0.8rem 0rem !important;
}

.accBtn:first-child {
  color: var(--orange) !important;
}

.accBtn:first-child:hover {
  color: var(--primaryBg) !important;
  background: var(--orange) !important;
}

.accBtn:last-child {
  color: var(--accentColor) !important;
}

.accBtn:last-child:hover {
  color: var(--primaryBg) !important;
  background: var(--accentColor) !important;
}

.bigMenTabs {
  background: transparent;
}

.bigMenTabs .bigMenTab {
  padding: 15px 0 15px;
  background: unset;
  font-family: var(--mainFont);
  font-size: 1.4rem;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--c_whiteST) !important;
}

.bigMenTabs .bigMenTabDis {
  opacity: 0.4;
}

.bigMenTabs .bigMenTab span.material-icons[style*="color:#fbc02d"],
.bigMenTabs .bigMenTab span.material-icons-outlined[style*="color:#fbc02d"] {
  color: var(--c_whiteST) !important;
}

.bigMenTabs .bigMenTabA {
  color: var(--c_white) !important;
  border-bottom: 5px solid var(--accentColor) !important;
}

.bigMenTabs .bigMenTabA span.material-icons[style*="color:#fbc02d"],
.bigMenTabs .bigMenTabA span.material-icons-outlined[style*="color:#fbc02d"] {
  color: var(--accentColor) !important;
}

#profilePicM {
  margin-top: 0.85rem;
  border-color: var(--subBgST);
  background: var(--subBgST);
}

#profilePicM img[src*="https://assets.krunker.io"] {
  -ms-interpolation-mode: nearest-neighbor !important;
      image-rendering: -webkit-optimize-contrast !important;
      image-rendering: -moz-crisp-edges !important;
      image-rendering: -o-pixelated !important;
      image-rendering: pixelated !important;
  opacity: 0;
}

#profilePicM::after {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background-image: var(--profile-pic, url("https://assets.krunker.io/textures/classes/icon_0.png"));
  -webkit-filter: var(--profile-pic, grayscale(1) opacity(0.5));
          filter: var(--profile-pic, grayscale(1) opacity(0.5));
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  position: absolute;
  image-rendering: optimizeQuality !important;
  border-radius: 100px;
  z-index: -1;
}

#profilePicM.blurred {
  -webkit-filter: unset !important;
          filter: unset !important;
  image-rendering: unset;
}

.setBodH[style="display:inline-block;padding-top:10px;vertical-align:top;width:680px;margin-left:15px;margin-top:0px;"] {
  width: 74% !important;
  padding-right: 0 !important;
}

.setBodH[style="display:inline-block;padding-top:10px;vertical-align:top;width:680px;margin-left:15px;margin-top:0px;"] .settName[style="width:100%;margin-top:0px"] a,
.setBodH[style="display:inline-block;padding-top:10px;vertical-align:top;width:680px;margin-left:15px;margin-top:0px;"] .settName[style="width:100%"] a {
  font-family: var(--mainFont);
  letter-spacing: 1px;
  font-size: 1.8rem;
}

.settName a[onclick*="showWindow(13)"] {
  font-family: var(--mainFont);
  letter-spacing: 1px;
  font-size: 1.8rem;
}

.setBodH .settName .floatR {
  font-family: var(--mainFont);
  letter-spacing: 1px;
  font-size: 1.8rem;
}

.setBodH .settName .floatR span {
  font-family: var(--mainFont);
  letter-spacing: 1px;
  font-size: 1.8rem;
}

.xpBar {
  height: 20px !important;
  border-radius: 100px !important;
  width: 98% !important;
  background: var(--subBgST);
}

.xpBar .xpBarB {
  background: -webkit-gradient(linear, left top, right top, from(var(--gradientColor4)), to(var(--gradientColor3)));
  background: linear-gradient(to right, var(--gradientColor4), var(--gradientColor3));
  border-radius: 100px;
}

.xpBar .xpBarV {
  left: unset;
  top: -154%;
  right: 0;
  font-family: var(--subFont);
  font-size: 1.4rem;
}

#crtrCode,
#crtrEmail,
#oldPass,
#newPass,
#repNPass {
  margin-bottom: 1rem !important;
  margin-top: 1rem !important;
}

.xpBar[style="margin-bottom:15px;margin-top:20px"] {
  border-radius: 100px !important;
  width: 98.5% !important;
  margin-top: 6rem !important;
}

.setHed[style="float:right;color:rgba(255,255,255,0.4)"] span,
.setHed[style="float:right;color:rgba(255,255,255,0.4)"] a,
.setHed[style="margin-top:10px;"] span,
.setHed[style="margin-top:10px;"] a,
.setHed[style="margin-top:20px"] span,
.setHed[style="margin-top:20px"] a,
.setHed[style="margin-top:16px"] span,
.setHed[style="margin-top:16px"] a,
.setHed[style="margin-top:0px"] span,
.setHed[style="margin-top:0px"] a {
  font-family: var(--mainFont);
}

#clanErr .setBodH .settName a {
  font-family: var(--subFont);
  color: var(--c_white);
}

#clanErr .setBodH .settName div {
  font-family: var(--mainFont);
}

.challHeadrT,
.challHeadrS,
.challHeadrI {
  color: white !important;
  font-family: var(--mainFont);
  font-size: 3rem;
  letter-spacing: 7px;
  border-color: var(--primaryBg);
}

.challHeadrT span,
.challHeadrS span,
.challHeadrI span {
  font-size: 1.5rem;
  color: var(--c_white) !important;
  letter-spacing: 5px;
}

.challHeadrT span:not(.material-icons),
.challHeadrS span:not(.material-icons),
.challHeadrI span:not(.material-icons) {
  font-family: var(--mainFont);
}

.challHeadrT .challHeadrBck,
.challHeadrT .challHeadrS,
.challHeadrS .challHeadrBck,
.challHeadrS .challHeadrS,
.challHeadrI .challHeadrBck,
.challHeadrI .challHeadrS {
  border-top-left-radius: 5px;
  border-bottom-right-radius: 5px;
}

.xpBar[style="margin-top:15px;"] {
  width: 99% !important;
  margin-top: 5rem !important;
}

.chalCard[style*="margin-left:20px"] {
  margin-left: 0 !important;
}

.chalCard {
  background: var(--subBgST) !important;
  border-color: transparent !important;
  width: calc(100% - 28px);
}

.chalCard .chalImgC {
  background: var(--subBgST) !important;
  border-color: transparent !important;
}

.chalCard .chalRight {
  font-family: var(--mainFont);
  font-size: 2.2rem;
  letter-spacing: 1px;
  display: -ms-inline-grid;
  display: inline-grid;
  -ms-grid-columns: 1fr 20%;
      grid-template-columns: 1fr 20%;
}

.chalCard .chalRight .chalDesc {
  font-family: var(--subFont);
  font-size: 1.4rem;
  color: var(--c_whiteST) !important;
}

.chalCard .chalRight .chalExpr {
  font-size: 26px;
  font-family: var(--subFont);
  -ms-flex-item-align: end;
      -ms-grid-row-align: end;
      align-self: end;
  text-align: right;
  padding-bottom: 1rem;
}

.chalCard .chalRight .chalXPBar {
  width: 100% !important;
  border-radius: 100px !important;
  background: var(--subBgST) !important;
  margin-top: 40px;
  height: 24px;
  grid-column: 2 span;
}

.chalCard .chalRight .chalXPBar .chalXPBarC {
  background: -webkit-gradient(linear, left top, right top, from(var(--gradientColor4)), to(var(--gradientColor3))) !important;
  background: linear-gradient(to right, var(--gradientColor4), var(--gradientColor3)) !important;
  border-radius: 100px !important;
}

.chalCard .chalRight .chalXPBar .chalProg,
.chalCard .chalRight .chalXPBar .chalXPVal {
  top: -47px !important;
  right: 7px !important;
  left: unset !important;
  font-family: var(--mainFont) !important;
  letter-spacing: 2px !important;
  font-size: 1.4rem !important;
}

.chalCard .chalRews {
  border-color: transparent;
}

.chalCard .chalRews .chalRewV {
  font-family: var(--mainFont);
  font-size: 1.6rem;
}

.chalCard .chalRews .chalRewV span:first-child {
  display: none;
}

.chalCard .chalRews .chalRewV span:not(.material-icons) {
  font-family: var(--mainFont);
  color: white !important;
}

.chalCard .chalRews .chalRewSkn {
  border-color: transparent;
  background-color: var(--subBgST);
}

.chalCard[style*="box-shadow: 0 0 14px #ffa000;"] {
  -webkit-box-shadow: inset 0 0 50px var(--accentColorST) !important;
          box-shadow: inset 0 0 50px var(--accentColorST) !important;
}

.chalCard[style*="box-shadow: 0 0 14px #ffa000;"] .chalRews {
  border-color: transparent !important;
}

.challCrdMsg {
  background: var(--subBgST);
  font-family: var(--subFont);
  color: var(--c_white) !important;
}

.challCrdMsg a {
  font-family: var(--mainFont);
}

.challMapCrd {
  width: 376px;
  border-radius: 5px;
  border-color: var(--primaryBg);
}

.challMapCrd .challMapName {
  font-family: var(--mainFont);
  text-transform: uppercase;
  letter-spacing: 4px;
  text-shadow: none;
  text-align: left;
  -webkit-transform: translateY(-50%);
          transform: translateY(-50%);
  left: 20px;
}

.challMapCrd .challMapPrg {
  border-radius: 0px;
  border-top-left-radius: 5px;
  background: #000000ad;
  font-family: var(--mainFont);
  font-size: 2.8rem;
  letter-spacing: 7px;
  color: white !important;
}

.challMapCrd .challMapPrg span {
  font-family: var(--mainFont);
  font-size: 1.3rem;
  color: var(--c_white) !important;
  letter-spacing: 5px;
}

.challMapCrd .challRotImg {
  -webkit-transform: scale(2.35) rotate(20deg);
          transform: scale(2.35) rotate(20deg);
}

#statHolder {
  display: -ms-grid;
  display: grid;
  -ms-grid-columns: (1fr)[4];
      grid-template-columns: repeat(4, 1fr);
  gap: 1.2rem;
  width: 99%;
  margin-top: 3rem;
}

#statHolder .pSt {
  text-shadow: unset !important;
  margin: 0 !important;
  width: 100% !important;
  height: 10rem;
  display: -ms-grid;
  display: grid;
  place-content: center;
  gap: 0.5rem;
  border-color: transparent !important;
  background: var(--subBgST) !important;
  font-family: var(--mainFont) !important;
  font-size: 1.1rem !important;
  padding: 0 !important;
  letter-spacing: 1px;
  -webkit-transition: -webkit-filter 280ms;
  transition: -webkit-filter 280ms;
  transition: filter 280ms;
  transition: filter 280ms, -webkit-filter 280ms;
}

#statHolder .pSt:hover {
  -webkit-filter: brightness(1.2);
          filter: brightness(1.2);
}

#statHolder .pSt strong {
  font-family: var(--subFont) !important;
  font-size: 1.6rem !important;
}

#menuWindow div[style="height:15px;margin-top:30px;border-top:4px solid rgba(255, 255, 255, 0.8);"] {
  border-color: transparent !important;
}

.menuLink {
  font-family: var(--mainFont);
  font-size: 1.8rem;
}

.setBodH[style="padding-top:10px;padding-bottom:10px;margin-bottom:20px;"] {
  background: var(--subBgST) !important;
  border-color: transparent !important;
  font-family: var(--subFont);
  font-size: 1.4rem !important;
  padding: 1rem;
  width: 95%;
}

#friendList > div {
  padding: 1rem 1rem !important;
  margin: 0.4rem !important;
  background: var(--subBgST) !important;
  width: 95% !important;
  margin-bottom: 1.2rem !important;
}

#friendList > div > div {
  border: none !important;
  padding: 0 !important;
  margin: 0 !important;
}

#friendList > div > div .folPfp {
  border-color: var(--subBgST);
  background-color: var(--subBgST);
}

#friendList > div > div .folInfHldr {
  margin-left: 0.7rem;
  margin-top: 0 !important;
}

#friendList > div > div .folInfHldr .lName {
  font-family: var(--mainFont);
  font-size: 1.8rem;
}

#friendList > div > div .folInfHldr > div {
  font-family: var(--subFont);
  font-size: 1.5rem !important;
}

#friendList > div > div .buttonR,
#friendList > div > div .buttonG {
  font-size: 1.2rem !important;
  font-family: var(--subFont) !important;
  letter-spacing: 1px;
  background: var(--subBgST);
  padding: 1rem;
  display: -ms-grid;
  display: grid;
  place-content: center;
  color: var(--orange) !important;
  display: inline-block !important;
}

#friendList > div > div .buttonG {
  color: var(--accentColor) !important;
}

#gameURL {
  margin-bottom: 1rem !important;
}

.accountButton,
.joinBtn {
  font-size: 28px;
  color: var(--accentColor) !important;
  background: var(--subBgST) !important;
  font-family: var(--mainFont);
  padding: 0.8rem 0rem !important;
  cursor: pointer;
  text-align: center;
  border-radius: 100px;
  width: 29% !important;
  float: right;
  -webkit-transition: color 280ms, background 280ms;
  transition: color 280ms, background 280ms;
}

.accountButton:hover,
.joinBtn:hover {
  color: var(--subBgM) !important;
  background: var(--accentColor) !important;
}

#menuWindow[style*="overflow-y: auto; width: 1000px;"] > div:first-child {
  font-family: var(--mainFont);
  font-size: 30px;
}

#menuWindow[style*="overflow-y: auto; width: 1000px;"] > div:first-child .button {
  background: var(--subBgST) !important;
  padding: 0.6rem 1rem !important;
  letter-spacing: 1px !important;
  font-size: 21px !important;
  color: var(--l-accentColor) !important;
}

.mailObj {
  border-color: transparent !important;
  background: var(--subBgST) !important;
  padding: 1.8rem 1rem !important;
  font-family: var(--mainFont) !important;
}

.mailObj .followFrom {
  font-family: var(--subFont);
  font-size: 26px;
}

.mailObj .followFrom a {
  font-family: var(--mainFont);
  letter-spacing: 1px;
  font-weight: 600;
}

.mailDate {
  font-family: var(--subFont);
  font-size: 1.4rem;
}

.mailFrom {
  border-color: var(--subBgST);
  font-family: var(--mainFont);
  font-size: 1.7rem;
}

.mailSubj {
  font-family: var(--subFont);
  font-size: 1.3rem !important;
}

.mailText {
  background: var(--subBgST);
  font-family: var(--subFont);
  font-size: 1.3rem;
}

.mailText a {
  font-family: var(--mainFont);
  letter-spacing: 1px;
  font-weight: 600;
}

.followBack {
  border-color: transparent !important;
  background: var(--subBgST) !important;
  padding: 0.5rem 1rem !important;
  font-family: var(--subFont);
  font-size: 1.2rem !important;
  color: var(--accentColor) !important;
}

.followBack:hover {
  color: var(--primaryBg) !important;
  border-color: transparent !important;
  background: var(--accentColor) !important;
}

.pListTable {
  background: var(--subBgST) !important;
}

.pListTable * {
  font-family: var(--subFont);
  font-size: 1.3rem;
}

.pListTable tr {
  border-color: transparent;
  margin-bottom: 1rem;
}

.pListTable tr:hover {
  background: var(--subBgST) !important;
}

.pListTable .pListName span[style="color:#353535"] {
  color: var(--c_white) !important;
}

.setHed[style="margin-top:0px"] > div {
  font-family: var(--mainFont) !important;
}

#ot-sdk-btn-floating {
  top: unset;
  bottom: 285px !important;
  right: 329px !important;
  left: unset;
  -webkit-transform: scale(0.95);
          transform: scale(0.95);
  z-index: 2147483;
}

#ot-sdk-btn-floating .ot-floating-button__front {
  background-color: transparent !important;
  -webkit-box-shadow: none !important;
          box-shadow: none !important;
}

#ot-sdk-btn-floating .ot-floating-button__back {
  background: transparent !important;
}

#initLoader {
  background-color: var(--primaryBg);
  background-image: var(--splash-logo, url("https://www.krunker.io/img/logo_1.png"));
  background-repeat: no-repeat;
  background-position: center;
  background-size: auto 153px;
}

#initLoader > *:first-child {
  display: none !important;
}

#initLoader #loadHeader {
  display: none;
}

#initLoader #loadGamNm {
  left: 0;
  -webkit-transform: unset;
          transform: unset;
  right: 0;
  color: transparent !important;
  height: 120px;
  background-image: var(--spinner-url, url("https://www.krunker.io/img/spinner.svg"));
  background-repeat: no-repeat;
  background-position: center;
}

#initLoader #loadTipsHolder {
  bottom: 6%;
  left: 0;
  right: 0;
  -webkit-transform: unset;
          transform: unset;
  width: calc(100% - 6rem);
  padding: 0rem 3rem;
  font-family: var(--subFont);
  font-size: 22px;
  letter-spacing: 1px;
  opacity: 0.7;
}

#initLoader #loadEditrBtn,
#initLoader #loadInfoRHolder,
#initLoader #loadInfoLHolder {
  display: none;
}

#bigMFeatName {
  font-family: var(--mainFont);
  font-size: 3rem;
  top: 2rem !important;
}

#bigMFeatVbar {
  font-size: 1.7rem;
  font-family: var(--subFont);
  top: 7rem !important;
}

#bigMFeatVbar > div {
  display: none !important;
}

#bigMFeatHBtn {
  all: unset;
  position: absolute;
  text-align: center;
  cursor: pointer;
  -webkit-transition: all 0.08s;
  transition: all 0.08s;
  font-family: var(--subFont);
  font-size: 1.7rem;
  padding: 0.4rem !important;
}

#bigMFeatHBtn span {
  color: var(--accentColor) !important;
  font-family: inherit;
}

#bigMFeatHBtn:hover {
  border: unset !important;
  -webkit-transform: unset !important;
          transform: unset !important;
}

#bigMFeatHBtn:hover span {
  text-decoration: underline;
}

#bigMFeatHBtn[onclick*="selectHostMap("] {
  background: var(--subBgST);
  color: white !important;
  bottom: 9.7%;
  right: 25%;
  border-radius: 100px;
  padding: 0.4rem 2rem !important;
  border: 2px solid white !important;
}

#bigMFeatPBtn {
  border: 3px solid var(--accentColor);
  font-family: var(--mainFont);
  font-size: 1.6rem;
  border-radius: 100px;
}

a.menuLink[href*="mods&openPubMo"] + div {
  font-family: var(--subFont);
  font-size: 1.8rem;
}

a.menuLink[href*="mods&openPubMo"] + div span {
  font-family: var(--mainFont);
}

.mapListItem {
  background-color: var(--subBgST);
}

.mapListItem .mapAgeD {
  margin: 2px;
  margin: 2px;
  font-family: var(--mainFont);
  font-size: 1.5rem;
  border-bottom-left-radius: 24px;
  padding: 0.5rem 1rem;
}

.mapListItem a {
  font-family: var(--subFont);
  font-size: 1.3rem;
  color: var(--c_white);
}

.mapListItem span {
  font-family: var(--mainFont);
  font-size: 1.2rem !important;
  padding-top: 3px;
}

.mapListItem span span {
  font-family: inherit;
}

.mapListThumb {
  border-radius: 5px 5px 0px 0px;
  background: transparent;
  top: 39%;
  width: 100%;
}

.mapActionOvrl {
  width: 100%;
  height: 100%;
  top: 0;
}

.mapActionOvrl .mapActionHol span {
  font-size: 5rem !important;
}

.mapActionOvrl .mapActionHol .mapActionB:last-child,
.mapActionOvrl .mapActionHol .mapActionB:first-child:not([onClick*="loadUserMod"]) {
  -webkit-transform: scale(0.4);
          transform: scale(0.4);
}

.likdByFrnd {
  font-family: var(--subFont);
}

.likdByFrnd span:not(.material-icons) {
  font-family: var(--mainFont);
}

.bigMFeatHold #bigMFeatVid {
  width: 276px;
  height: 155px;
}

.bigMFeatHold #bigMFeatVbar span:not(.material-icons) {
  font-family: var(--subFont);
}

.bigMFeatHold #bigMFeatDesc {
  width: 680px;
  font-family: var(--subFont);
  font-size: 1.4rem;
  line-height: 2.3rem;
  margin-top: 0.3rem;
  bottom: 25px;
}

.bigMFeatHold {
  height: 300px;
}

.bigMFeatHold #bigMFeatDesc2 {
  font-family: var(--subFont);
  line-height: 2.5rem;
  font-size: 1.4rem;
  background: transparent;
  -webkit-backdrop-filter: unset;
          backdrop-filter: unset;
  padding: 0px;
  text-shadow: 0px 0px 10px #0000005e;
}

.crftRcpeCrd {
  background: var(--subBgST);
}

.crftRcpeCrd .craftRcIcn {
  border-color: transparent !important;
  background-color: var(--subBgST);
  background-image: 100%;
}

.crftRcpeCrd .craftRiHl .crftItmNm {
  font-family: var(--mainFont);
  font-size: 2.1rem;
  width: 220px;
}

.crftRcpeCrd .craftRiHl .crftItmNm[style*="#292929"] {
  color: var(--c_white) !important;
}

.crftRcpeCrd .craftRiHl .crftItmReq {
  border-color: transparent;
  background-color: var(--subBgST);
}

.crftRcpeCrd .craftRiHl .crftItmJnk {
  font-family: var(--mainFont);
  font-size: 2rem;
}

.crftRcpeCrd .craftRiHl .crftTim {
  margin-top: 17px;
  background: var(--subBg);
  font-family: var(--subFont);
}

.bigMFeatHold {
  background-color: var(--subBgST) !important;
}

.bigMFeatHold .biMFeatInfH {
  background: transparent;
  font-family: var(--subFont);
  font-size: 1.3rem;
  line-height: 2.4rem;
  padding: 0;
}

.bigMFeatHold .biMFeatInfB {
  border: 0;
  font-family: var(--mainFont);
  letter-spacing: 1px;
  padding: 1rem 1rem;
  width: -webkit-fit-content;
  width: -moz-fit-content;
  width: fit-content;
  display: inherit;
  background: var(--subBgST);
}

.bigMFeatHold .biMFeatInfB:hover {
  border: none !important;
  background: var(--gradientColor4) !important;
}
/*# sourceMappingURL=main_custom.css.map */
