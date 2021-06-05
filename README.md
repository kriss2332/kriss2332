@charset "UTF-8";
@import url("https://fonts.googleapis.com/css2?family=Nunito:wght@600&display=swap");
@import url("https://discord-custom-covers.github.io/usrbg/dist/usrbg.css");
@import url("https://monstrousdev.github.io/themes/addons/user-tags.css");
:root {
  --jumping-gif: url("https://i.imgur.com/dCd49s0.gif");
  --background-tertiary-alt: #FFC7D4;
  --border-radius: 20px;
  --playing: #8ea6fc;
  --spotify: #5fce86;
  --streaming: #9b77da;
  --xbox: #53a853;
}

.theme-dark {
  --text-normal: #f8e1e5;
  --header-primary: #f8e1e5;
  --interactive-normal: #fab1bd;
  --channels-default: #f8e1e5;
  --text-muted: #e2c1c7;
  --interactive-muted: #ad8c91;
  --header-secondary: #e2c1c7;
  --interactive-hover: #e2c1c7;
  --interactive-active: #e2c1c7;
  --background-primary: #5e3640;
  --background-secondary: #49292f;
  --background-secondary-alt: #3b1d24;
  --background-tertiary: #220f14;
  --background-floating: #221115;
  --background-accent: #c5536c;
  --activity-card-background: var(--background-secondary-alt);
  --channeltextarea-background: var(--background-secondary);
  --background-modifier-hover: rgba(56, 31, 31, 0.32);
  --background-modifier-active: rgba(19, 12, 12, 0.32);
  --background-modifier-selected: rgba(31, 21, 21, 0.32);
  --toast-background: #5e3640 !important;
  --toast-header: #3b1d24 !important;
  --toast-contents: #49292f !important;
  --toast-border: #49292f !important;
  --scrollbar-auto-thumb: var(--background-tertiary);
  --scrollbar-auto-track: var(--background-secondary-alt);
  --scrollbar-thin-thumb: var(--background-tertiary);
  --scrollbar-thin-track: transparent;
  --deprecated-quickswitcher-input-background: var(--background-primary);
}
.theme-dark .colorBrand-ROmMP1 {
  color: #c5536c;
}
.theme-dark .colorDefault-2K3EoJ.focused-3afm-j, .theme-dark .colorDefault-2K3EoJ:active:not(.hideInteraction-1iHO1O) {
  background-color: var(--background-modifier-hover) !important;
}
.theme-dark .lookFilled-1Gx00P {
  background-color: #c5536c !important;
}
.theme-dark .lookFilled-1Gx00P:active, .theme-dark .lookFilled-1Gx00P:hover {
  background-color: #b64a61 !important;
}
.theme-dark .lookOutlined-3sRXeN:not(.colorWhite-rEQuAQ) {
  color: #c5536c;
  border-color: #c5536c;
}
.theme-dark .colorDefault-2K3EoJ.focused-3afm-j, .theme-dark .colorDefault-2K3EoJ:active:not(.hideInteraction-1iHO1O) {
  color: var(--interactive-normal);
}

.theme-light {
  --text-normal: #a86373;
  --header-primary: #a86373;
  --interactive-normal: #a86373;
  --channels-default: #a86373;
  --text-muted: #a86373;
  --interactive-muted: #cf92a0;
  --header-secondary: #cf92a0;
  --interactive-hover: #be7d8c;
  --interactive-active: #b36f7f;
  --background-primary: #FFFFFF;
  --background-secondary: #ffeeee;
  --background-secondary-alt: #fdc7c7;
  --background-tertiary: #ffbbbb;
  --background-floating: #ffbbbb;
  --background-accent: #c5536c;
  --channeltextarea-background: var(--background-secondary);
  --background-modifier-hover: rgba(56, 31, 31, 0.062);
  --background-modifier-active: rgba(19, 12, 12, 0.123);
  --background-modifier-selected: rgba(31, 21, 21, 0.11);
  --scrollbar-auto-thumb: var(--background-tertiary);
  --scrollbar-auto-track: var(--background-secondary-alt);
  --scrollbar-thin-thumb: var(--background-tertiary);
  --scrollbar-thin-track: transparent;
  --deprecated-quickswitcher-input-background: var(--background-primary);
}
.theme-light .colorBrand-ROmMP1 {
  color: #c5536c;
}
.theme-light .colorDefault-2K3EoJ.focused-3afm-j, .theme-light .colorDefault-2K3EoJ:active:not(.hideInteraction-1iHO1O) {
  background-color: var(--background-modifier-hover) !important;
}
.theme-light .lookFilled-1Gx00P {
  background-color: #c5536c !important;
}
.theme-light .lookFilled-1Gx00P:active, .theme-light .lookFilled-1Gx00P:hover {
  background-color: #b64a61 !important;
}
.theme-light .lookOutlined-3sRXeN:not(.colorWhite-rEQuAQ) {
  color: #c5536c;
  border-color: #c5536c;
}
.theme-light .colorDefault-2K3EoJ.focused-3afm-j, .theme-light .colorDefault-2K3EoJ:active:not(.hideInteraction-1iHO1O) {
  color: var(--interactive-normal);
}

:root #app-mount {
  --font-primary: "Nunito";
  --font-display: "Nunito";
}

:root .embedFull-2tM8-- {
  border: none;
  margin-left: 10px;
  border-radius: 5px var(--border-radius) var(--border-radius) 5px;
}
:root .embedFull-2tM8--:after {
  content: "";
  position: absolute;
  top: 1px;
  bottom: 1px;
  left: -10px;
  width: 0;
  border: 3px solid;
  border-color: inherit;
  border-radius: 5px;
}
:root .hljs {
  border: none;
  border-radius: var(--border-radius);
}
:root .wrapperAudio-1jDe0Q {
  padding: 10px 0 0 0;
  border-radius: var(--border-radius);
}
:root .audioMetadata-3zOuGv {
  padding: 5px 10px;
}
:root .audioControls-2HsaU6 {
  border-radius: 0 0 var(--border-radius) var(--border-radius);
}
:root .spoilerText-3p6IlD.hidden-HHr2R9, :root .spoilerText-3p6IlD.hidden-HHr2R9:hover {
  background-color: var(--background-secondary-alt);
}
:root .wrapper-35wsBm {
  border-radius: var(--border-radius);
}
:root .invite-18yqGF {
  background-color: var(--background-secondary);
  border: none;
  border-radius: var(--border-radius);
}
:root .embedSpotify-tvxDCr {
  border-radius: var(--border-radius);
}
:root .tile-2OwFgW {
  background-color: var(--background-secondary);
  border-radius: var(--border-radius);
}
:root .tileHorizontal-3eee4N.tile-2OwFgW:hover {
  background-color: var(--background-secondary-alt);
}
:root .invalidPoop-pnUbq7 {
  background-color: rgba(0, 0, 0, 0.103);
}
:root .autocomplete-1vrmpx, :root .option-1B5ZV8 {
  background-color: var(--background-secondary-alt);
}
:root .categoryHeader-O1zU94, :root .selected-1Tbx07 {
  background-color: var(--background-tertiary);
}
:root .everyonePopout-nEbJY3 {
  background-color: var(--background-primary);
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11);
}
:root .emojiItem-14v6tW.emojiItemSelected-1aLkfV {
  background-color: var(--background-modifier-selected);
}
:root .searchBar-5di9mG {
  border-radius: var(--border-radius);
}
:root .scroller-1-nKid {
  background: var(--background-tertiary);
}
:root .container-1If-HZ, :root .reactors-Blmlhw {
  background: var(--background-secondary);
}
:root .reactionSelected-1pqISm {
  background-color: #6e85d321;
}
:root .reactorDefault-1IUqMZ {
  box-shadow: inset 0 -1px 0 var(--background-primary);
}
:root .message-2qRu38 {
  background: var(--background-primary);
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11);
}
:root .textContainer-C0szpm, :root .footer-2yA7Ep {
  border: none;
}
:root .popoutContainer-1MXdqN {
  border-radius: var(--border-radius);
}
:root .newMessagesBar-265mhP {
  top: 5px;
  border-radius: var(--border-radius);
  background-color: var(--background-accent);
  padding-top: 0;
}
:root .jumpToPresentBar-G1R9s6 {
  bottom: 12px;
  padding-bottom: 0;
  border-radius: var(--border-radius);
}
:root .wrapper-39oAo3 {
  border-radius: var(--border-radius);
}
:root .reaction-1hd86g {
  border-radius: var(--border-radius);
}
:root .wrapper-2aW0bm {
  border-radius: var(--border-radius);
}
:root .botTagRegular-2HEhHi {
  background-color: var(--background-accent);
}

:root .guilds-1SWlCJ .scroller-1Bvpku {
  padding: 8px 0 130px 0;
}
:root .guilds-1SWlCJ .scroller-1Bvpku .wrapper-25eVIn foreignObject {
  mask: none;
  border-radius: var(--border-radius);
}
:root .guilds-1SWlCJ .scroller-1Bvpku .folder-1hbNCn {
  background-color: transparent;
}
:root .guilds-1SWlCJ .scroller-1Bvpku .circleButtonMask-1_597P .circleIconButton-1QV--U {
  border-radius: var(--border-radius);
  transition: border-radius 0.15s;
  color: var(--background-accent);
  background-color: var(--background-secondary-alt) !important;
}
:root .guilds-1SWlCJ .scroller-1Bvpku .circleButtonMask-1_597P:hover .circleIconButton-1QV--U {
  border-radius: calc(var(--border-radius) - 5px);
}
:root .guilds-1SWlCJ .scroller-1Bvpku .circleButtonMask-1_597P foreignObject {
  mask: none;
}

.theme-light .wrapper-1BJsBx.selected-bZ3Lue .childWrapper-anI2G9,
.theme-light .wrapper-1BJsBx:hover .childWrapper-anI2G9 {
  background-color: var(--text-normal);
}

.theme-dark .wrapper-1BJsBx.selected-bZ3Lue .childWrapper-anI2G9,
.theme-dark .wrapper-1BJsBx:hover .childWrapper-anI2G9 {
  background-color: var(--background-primary);
}

.wrapperSimple-19ogV2,
.folderIconWrapper-226oVY, .folderIconWrapper-1_bOZe,
.expandedFolderBackground-2sPsd-, .flexChild-faoVW3 .avatarUploaderInner-3UNxY3 {
  border-radius: var(--border-radius);
}

.panels-j1Uci_ {
  z-index: unset;
}

.panel-24C3ux {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 56px;
  border-bottom: none;
  background-color: var(--background-tertiary);
  transition: width 0.35s;
}
.panel-24C3ux .gameWrapper-1jIQAX {
  margin-left: 12px;
}
.panel-24C3ux .info-WdNIDE, .panel-24C3ux .actions-aUdUfC {
  opacity: 0;
}
.panel-24C3ux:hover {
  width: 274px;
  margin: 8px;
  z-index: 1;
  border-radius: 5px var(--border-radius) var(--border-radius) 5px;
  border-left: 5px solid var(--background-accent);
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11);
}
.panel-24C3ux:hover .gameWrapper-1jIQAX {
  margin-left: 0;
}
.panel-24C3ux:hover .info-WdNIDE, .panel-24C3ux:hover .actions-aUdUfC {
  opacity: 1;
}

.activityPanel-28dQGo ~ .powercord-spotify {
  bottom: 50px;
  transition: 0.35s;
}

.activityPanel-28dQGo:hover ~ .powercord-spotify {
  bottom: 60px;
}

.powercord-spotify {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 72px;
  background-color: var(--background-tertiary);
  transition: width 0.35s, margin 0.35s;
}
.powercord-spotify .container-3baos1 {
  margin-top: 5px;
}
.powercord-spotify .container-3baos1 .avatarWrapper-2yR4wp {
  margin-left: 4px;
}
.powercord-spotify .container-3baos1 .avatarWrapper-2yR4wp .spotify-cover {
  width: 48px !important;
  height: auto !important;
}
.powercord-spotify .container-3baos1 .nameTag-3uD-yy, .powercord-spotify .container-3baos1 .spotify-buttons {
  opacity: 0;
}
.powercord-spotify .spotify-seek .spotify-seek-bar {
  height: 5px;
  margin: 5px 8px 8px 8px;
  border-radius: var(--border-radius);
  overflow: hidden;
  background-color: var(--background-primary);
}
.powercord-spotify .spotify-seek .spotify-seek-bar .spotify-seek-bar-progress {
  border-radius: var(--border-radius);
}
.powercord-spotify.hover {
  width: 290px;
  margin: 8px;
  z-index: 3;
  border-radius: 5px var(--border-radius) var(--border-radius) 5px;
  border-left: 5px solid var(--background-accent);
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11);
}
.powercord-spotify.hover .container-3baos1 {
  flex-direction: column;
  height: unset;
}
.powercord-spotify.hover .container-3baos1 .avatarWrapper-2yR4wp {
  margin: -30px 0 0 0;
}
.powercord-spotify.hover .container-3baos1 .avatarWrapper-2yR4wp .spotify-cover {
  width: 100px !important;
  height: auto !important;
}
.powercord-spotify.hover .container-3baos1 .nameTag-3uD-yy {
  text-align: center;
  margin: 15px 0;
  opacity: 1;
  max-width: 260px;
}
.powercord-spotify.hover .container-3baos1 .spotify-buttons {
  text-align: center;
  margin-bottom: 15px;
  opacity: 1;
}
.powercord-spotify.hover .spotify-seek .spotify-seek-elements {
  margin: 0 8px;
}
.powercord-spotify.hover .spotify-seek .spotify-seek-bar {
  height: 15px;
}

:root .content-98HsJk .sidebar-2K8pFh {
  border-radius: 0;
}
:root #guild-header-popout .item-1tOPte {
  flex-direction: row-reverse;
}
:root #guild-header-popout .item-1tOPte .iconContainer-2-XQPY {
  margin: 0 8px 0 0;
}
:root .colorPremium-p4p7qO.focused-3afm-j .icon-LYJorE,
:root .colorPremium-p4p7qO:active:not(.hideInteraction-1iHO1O) .icon-LYJorE {
  color: #ff73fa;
}
:root .content-1x5b-n {
  border-radius: var(--border-radius);
}
:root .content-1Wq3SX {
  border-radius: var(--border-radius);
}
:root .container-2x5lvQ .header-2C89wJ {
  background-color: var(--background-tertiary);
}
:root .container-2x5lvQ section {
  background-color: var(--background-secondary);
}

:root [href="https://support.discord.com"], :root .searchLearnMore-3SQUAj .anchor-3Z-8Bb.anchorUnderlineOnHover-2ESHQB {
  display: none;
}
:root .search-36MZv- {
  order: 1;
  margin-left: 0;
}
:root .search-36MZv- .focused-31_ccS .searchBar-3dMhjb, :root .search-36MZv- .open-6_Y_aH .searchBar-3dMhjb {
  width: 320px;
  border-radius: var(--border-radius);
}
:root .search-36MZv- .search-2oPWTC:not(.open-6_Y_aH) .searchBar-3dMhjb {
  width: 27px;
  transition: 0.25s;
  background-color: transparent;
}
:root .search-36MZv- .search-2oPWTC:not(.open-6_Y_aH):hover .searchBar-3dMhjb {
  width: 240px;
  background-color: var(--background-tertiary);
  border-radius: var(--border-radius);
}
:root .search-36MZv- .search-2oPWTC:not(.open-6_Y_aH) .iconContainer-O4O2CN {
  transform: scale(1.2);
  transition: 0.25s;
}
:root .search-36MZv- .search-2oPWTC:not(.open-6_Y_aH):hover .iconContainer-O4O2CN {
  transform: scale(1);
}
:root .search-36MZv- .searchAnswer-3Dz2-q, :root .search-36MZv- .searchFilter-2ESiM3 {
  background-color: var(--background-primary);
}
:root .container-3ayLPN {
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11);
  background-color: var(--background-secondary-alt);
  border-radius: var(--border-radius);
}
:root .container-3ayLPN .queryContainer-RKFJW- {
  border-bottom: none;
}
:root .container-3ayLPN .focused-2bY0OD {
  background-color: var(--background-secondary-alt);
  border-bottom: none;
}
:root .container-3ayLPN .resultsGroup-r_nuzN::before {
  display: none;
}
:root .container-3ayLPN .resultsGroup-r_nuzN .header-2N-gMV {
  text-align: center;
}
:root .container-3ayLPN .option-96V44q {
  border-radius: var(--border-radius);
}
:root .container-3ayLPN .option-96V44q:after {
  background: linear-gradient(90deg, rgba(54, 57, 63, 0), var(--background-secondary-alt) 80%);
}
:root .container-3ayLPN .option-96V44q.selected-rZcOL-:after {
  background: linear-gradient(90deg, rgba(54, 57, 63, 0), var(--background-secondary) 80%);
}
:root .container-3ayLPN .option-96V44q .answer-1n6g43 {
  color: var(--interactive-muted);
}
:root .calendarPicker-2yf6Ci .react-datepicker {
  background-color: var(--background-secondary-alt);
}
:root .calendarPicker-2yf6Ci .react-datepicker__day, :root .calendarPicker-2yf6Ci .react-datepicker__header {
  background: var(--background-secondary-alt) !important;
  border-color: var(--background-tertiary) !important;
}
:root .calendarPicker-2yf6Ci .react-datepicker__day::after, :root .calendarPicker-2yf6Ci .react-datepicker__header::after {
  background-color: var(--background-accent) !important;
}
:root .datePicker--XZbmJ .datePickerHint-3Q1Udw .hintValue-29ny8Z,
:root .datePicker--XZbmJ .datePickerHint-3Q1Udw .hintValue-29ny8Z:hover {
  background-color: var(--background-accent);
}
:root .searchLearnMore-3SQUAj {
  display: none;
}
:root .searchResultsWrap-3-pOjs {
  overflow: visible;
}
:root .searchResultsWrap-3-pOjs::before {
  content: "Search results";
  position: absolute;
  top: -60px;
  z-index: 1;
  width: 100%;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 20px;
  font-weight: bolder;
  color: var(--header-primary);
  background-color: var(--background-secondary);
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}
:root .searchResultsWrap-3-pOjs::after {
  content: "";
  position: absolute;
  bottom: -35px;
  z-index: 1;
  width: 100%;
  height: 35px;
  background-color: var(--background-secondary);
  border-radius: 0 0 var(--border-radius) var(--border-radius);
  background-image: linear-gradient(to right, var(--header-primary) 33%, rgba(255, 255, 255, 0) 0%);
  background-position: top;
  background-size: 21px 2px;
  background-repeat: repeat-x;
}
:root .searchResultsWrap-3-pOjs .searchHeader-2XoQg7 {
  display: grid;
  grid-template-columns: auto auto auto;
  grid-gap: 10px;
  height: unset;
}
:root .searchResultsWrap-3-pOjs .searchHeader-2XoQg7 > * {
  justify-content: center;
}
:root .searchResultsWrap-3-pOjs .searchHeader-2XoQg7 .totalResults--dyAxF {
  grid-column: 1/4;
}
:root .searchResultsWrap-3-pOjs .searchHeader-2XoQg7 .tab-2j5AEF {
  padding: 0;
  margin: 0;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh {
  padding: 8px 0;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh .searchResultGroup-1DphGG {
  padding: 0 2px 0 8px;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh .repliedMessage-VokQwo {
  margin-left: 8px;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh .repliedMessage-VokQwo::before {
  display: none;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh .wrapper-2a6GCs {
  padding: 0;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh .contents-2mQqc9 {
  display: grid;
  grid-template-columns: 40px auto;
  grid-gap: 8px;
  align-items: center;
  margin: 5px 5px 5px 8px;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh .contents-2mQqc9 .header-23xsNx {
  display: flex;
  flex-direction: column;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh .contents-2mQqc9 .header-23xsNx .timestamp-3ZCmNB {
  margin-left: 0;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh .contents-2mQqc9 .avatar-1BDn8e {
  position: static;
  margin-top: 0;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh .contents-2mQqc9 .messageContent-2qWWxC {
  grid-column: 1/3;
  padding-left: 10px;
  margin: 0;
  padding: 0;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh .embedWrapper-lXpS3L {
  margin-left: 5px;
}
:root .searchResultsWrap-3-pOjs .scroller-3GIiMh .pageControl-xGOf_S {
  width: 100%;
}
:root .messagesPopoutWrap-1MQ1bW {
  border-radius: var(--border-radius);
}

:root .membersWrap-2h-GB4::before {
  content: "Member list";
  position: absolute;
  top: -60px;
  z-index: 1;
  width: 100%;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 20px;
  font-weight: bolder;
  color: var(--header-primary);
  background-color: var(--background-secondary);
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}
:root .membersWrap-2h-GB4 .members-1998pB {
  width: 100%;
  background-color: var(--background-primary);
}
:root .membersWrap-2h-GB4 .members-1998pB .content-3YMskv {
  background-color: transparent;
}
:root .membersWrap-2h-GB4 .members-1998pB .member-3-YXUe {
  max-width: 300px;
  border-radius: var(--border-radius);
  background-color: var(--background-primary);
}
:root .membersWrap-2h-GB4::after {
  content: "";
  position: absolute;
  bottom: -35px;
  z-index: 1;
  width: 100%;
  height: 35px;
  background-color: var(--background-secondary);
  border-radius: 0 0 var(--border-radius) var(--border-radius);
  background-image: linear-gradient(to right, var(--header-primary) 33%, rgba(255, 255, 255, 0) 0%);
  background-position: top;
  background-size: 21px 2px;
  background-repeat: repeat-x;
}
:root .layout-2DM8Md {
  border-radius: var(--border-radius);
}
:root .userPopout-3XzG_A {
  width: unset !important;
  max-width: 800px;
  flex-direction: row;
  border-radius: var(--border-radius);
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11);
  transform: translateZ(0);
}
:root .userPopout-3XzG_A[style*=-user-] .body-3iLsc4 {
  margin-top: 120px;
}
:root .userPopout-3XzG_A .headerNormal-1l1Znk {
  max-width: 280px;
  min-width: 200px;
  display: flex;
  flex-direction: column;
  background-color: var(--background-tertiary);
  border-bottom: none;
}
:root .userPopout-3XzG_A .headerNormal-1l1Znk .profileBanner-33-uE1 {
  width: 200%;
}
:root .userPopout-3XzG_A .headerNormal-1l1Znk .headerTop-2y3V6H {
  border-bottom: none;
}
:root .userPopout-3XzG_A .headerNormal-1l1Znk .activityUserPopout-2yItg2 {
  background-color: var(--background-secondary-alt);
  margin: 0px 12px 12px 0;
  padding: 16px;
  border-radius: 0 var(--border-radius) var(--border-radius) 0;
}
:root .userPopout-3XzG_A .headerNormal-1l1Znk .spotifyIcon-2J9kSv {
  display: none;
}
:root .userPopout-3XzG_A .body-3iLsc4 {
  margin-top: 60px;
  background-color: var(--background-secondary);
}
:root .userPopout-3XzG_A .body-3iLsc4 .rolesList-22qj2L {
  flex-direction: column;
}
:root .userPopout-3XzG_A .body-3iLsc4 .rolesList-22qj2L .role-2irmRk {
  position: relative;
  overflow: hidden;
  border: none;
}
:root .userPopout-3XzG_A .body-3iLsc4 .rolesList-22qj2L .roleCircle-3xAZ1j::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: inherit;
  opacity: 0.2;
  pointer-events: none;
}
:root .userPopout-3XzG_A .body-3iLsc4 .rolesList-22qj2L .roleCircle-3xAZ1j {
  width: 14.29px;
}
:root .userPopout-3XzG_A .body-3iLsc4 .rolesList-22qj2L .roleName-32vpEy {
  text-align: center;
  width: 100%;
  overflow: visible;
  font-weight: bold;
}
:root .userPopout-3XzG_A .footer-1fjuF6 {
  display: none;
}
:root .userPopout-3XzG_A {
  overflow: hidden;
  transform: translateZ(0) !important;
  --USRBG-banner-height: 60px;
}
:root .userPopout-3XzG_A[style*=-user-] {
  --USRBG-banner-height: 120px;
  --USRBG-avatar-offset: 76px;
}
:root .userPopout-3XzG_A[style*=-user-] .profileBanner-33-uE1 {
  background-size: cover;
  background-repeat: no-repeat;
  background-position: var(--user-popout-position, center) center;
  background-image: var(--user-background);
  height: var(--USRBG-banner-height, 120px);
}
:root .userPopout-3XzG_A[style*=-user-] .avatarWrapperNormal-2tu8Ts {
  top: var(--USRBG-avatar-offset, 76px);
}
:root .userPopout-3XzG_A:not([style*=-user-]) .avatar-22FtUu::after {
  content: "";
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: -1;
  height: var(--USRBG-banner-height, 60px);
  pointer-events: none;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: var(--user-popout-position, center) center;
  background-image: var(--user-background);
}
:root .userPopout-3XzG_A:not([style*=-user-]) .avatar-22FtUu, :root .userPopout-3XzG_A:not([style*=-user-]) .avatarHint-1E3LMl {
  z-index: 1;
}
:root .container-3XJ8ns {
  border-radius: var(--border-radius);
  border: none;
}
:root .container-3XJ8ns .item-2J2GlB .popoutRoleDot-1XPcoA {
  border: none;
}
:root .container-3XJ8ns .item-2J2GlB:hover {
  border-radius: var(--border-radius);
}
:root .modal-3c3bKg .root-SR8cQa {
  border-radius: var(--border-radius);
  transform: translateZ(0);
}
:root .modal-3c3bKg .root-SR8cQa > *:first-child {
  background-color: var(--background-secondary-alt);
}
:root .modal-3c3bKg .root-SR8cQa .activity-1ythUs {
  position: relative;
  z-index: 1;
}
:root .modal-3c3bKg .root-SR8cQa .activityProfile-2bJRaP {
  margin: 10px;
  border-radius: var(--border-radius);
}
:root .modal-3c3bKg .root-SR8cQa .topSectionPlaying-1J5E4n .activityProfile-2bJRaP {
  background-color: var(--playing);
}
:root .modal-3c3bKg .root-SR8cQa .topSectionSpotify-1lI0-P .activityProfile-2bJRaP {
  background-color: var(--spotify);
}
:root .modal-3c3bKg .root-SR8cQa .topSectionStreaming-1Tpf5X .activityProfile-2bJRaP {
  background-color: var(--streaming);
}
:root .modal-3c3bKg .root-SR8cQa .topSectionXbox-3fWLjS .activityProfile-2bJRaP {
  background-color: var(--xbox);
}
:root .modal-3c3bKg .root-SR8cQa .header-QKLPzZ {
  display: grid;
  grid-template-columns: 130px auto 40px;
  padding: 15px 5px 15px 15px;
}
:root .modal-3c3bKg .root-SR8cQa .header-QKLPzZ .avatar-3EQepX {
  grid-row: 1/3;
  width: 110px !important;
  height: 110px !important;
}
:root .modal-3c3bKg .root-SR8cQa .header-QKLPzZ .avatar-3EQepX .avatar-VxgULZ {
  border-radius: var(--border-radius);
}
:root .modal-3c3bKg .root-SR8cQa .header-QKLPzZ .avatar-3EQepX foreignObject {
  mask: none;
}
:root .modal-3c3bKg .root-SR8cQa .header-QKLPzZ .avatar-3EQepX rect {
  display: none;
}
:root .modal-3c3bKg .root-SR8cQa .header-QKLPzZ .avatar-3EQepX.wrapper-3t9DeA::before {
  content: "";
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  background: var(--user-background) center/cover no-repeat;
  -webkit-mask: linear-gradient(rgba(0, 0, 0, 0.8) 100%, transparent);
}
:root .modal-3c3bKg .root-SR8cQa .header-QKLPzZ .headerInfo-30uryT {
  grid-column: 2/4;
  display: flex;
  position: relative;
  flex-direction: column;
  align-items: center;
  z-index: 1;
}
:root .modal-3c3bKg .root-SR8cQa .tabBarContainer-1s1u-z {
  padding: 0;
  border-top: none;
}
:root .modal-3c3bKg .root-SR8cQa .tabBar-2MuP6- {
  justify-content: space-around;
}
:root .modal-3c3bKg .root-SR8cQa .tabBarItem-1b8RUP {
  margin-right: 0;
  z-index: 1;
  position: relative;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc {
  z-index: 1;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx {
  border-top: none;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS {
  justify-content: flex-start;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 {
  position: relative;
  width: 110px;
  flex-direction: column;
  overflow: hidden;
  border: none;
  margin: 5px;
  padding: 10px;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F {
  position: relative;
  margin-bottom: 10px;
  width: 45px;
  height: 45px;
  z-index: 2;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountNameInner-1phBvE {
  position: relative;
  z-index: 1;
  width: 100%;
  justify-content: center;
  overflow: visible;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountNameInner-1phBvE .connectedAccountName-f8AEe2 {
  text-align: center;
  margin: 0;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountNameInner-1phBvE span {
  display: none;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .anchor-3Z-8Bb {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 2;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .anchor-3Z-8Bb > svg {
  display: none;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F + .connectedAccountNameInner-1phBvE::before {
  content: "";
  position: absolute;
  top: -65px;
  left: -10px;
  z-index: -1;
  width: 130px;
  height: 91px;
  border-radius: var(--border-radius);
  opacity: 0.25;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F[src="/assets/5d69e29f0d71aaa04ed9725100199b4e.png"] + .connectedAccountNameInner-1phBvE::before {
  background-color: #191717;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F[src="/assets/f0655521c19c08c4ea4e508044ec7d8c.png"] + .connectedAccountNameInner-1phBvE::before {
  background-color: #1ED760;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F[src="/assets/f09c1c70a67ceaaeb455d163f3f9cbb8.png"] + .connectedAccountNameInner-1phBvE::before {
  background-color: #000000;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F[src="/assets/0d44ba28e39303de3832db580a252456.png"] + .connectedAccountNameInner-1phBvE::before {
  background-color: #5DC21E;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F[src="/assets/3abe9ce5a00cc24bd8aae04bf5968f4c.png"] + .connectedAccountNameInner-1phBvE::before {
  background-color: #FF4500;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F[src="/assets/edbbf6107b2cd4334d582b26e1ac786d.png"] + .connectedAccountNameInner-1phBvE::before {
  background-color: #553092;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F[src="/assets/4662875160dc4c56954003ebda995414.png"] + .connectedAccountNameInner-1phBvE::before {
  background-color: #1DA1F2;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F[src="/assets/449cca50c1452b4ace3cbe9bc5ae0fd6.png"] + .connectedAccountNameInner-1phBvE::before {
  background-color: #D9252A;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F[src="/assets/8c289d499232cd8e9582b4a5639d9d1d.png"] + .connectedAccountNameInner-1phBvE::before {
  background-color: #009AE5;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F[src="/assets/8d8f815f3d81a33b1e70ec7c22e1b6fe.png"] + .connectedAccountNameInner-1phBvE::before {
  background-color: #2D3283;
}
:root .modal-3c3bKg .root-SR8cQa .body-3ND3kc .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 .connectedAccountIcon-3P3V6F[src="/assets/806953fe1cc616477175cbcdf90d5cd3.png"] + .connectedAccountNameInner-1phBvE::before {
  background-color: #CEA146;
}

:root .layers-3iHuyZ {
  margin: 20px 0 40px 0;
  z-index: 1;
}
:root .layers-3iHuyZ > .layer-3QrUeG:first-child {
  opacity: 1 !important;
  transform: scale(1) !important;
}
:root .layers-3iHuyZ > .layer-3QrUeG.stop-animations:first-child {
  z-index: 1;
  transform: scale(1) !important;
}
:root .layers-3iHuyZ > :nth-child(2) {
  height: 100%;
  left: 72px;
  z-index: 2;
  background-color: transparent;
  transform: scale(1) !important;
}
:root .standardSidebarView-3F1I7i {
  border-radius: 0 var(--border-radius) var(--border-radius) 0;
  overflow: hidden;
}
:root .standardSidebarView-3F1I7i .sidebarRegion-VFTUkN {
  flex: unset;
}
:root .standardSidebarView-3F1I7i .sidebarRegion-VFTUkN .sidebar-CFHs9e {
  width: 232px;
  padding: 60px 10px;
}
:root .contentColumn-2hrIYH, :root .customColumn-Rb6toI, :root .hero-EvfTTA, :root .notificationSettings-1NQKPR, :root .noticeRegion-1YviSH, :root .customScroller-26gWhv > div, :root .userSettingsVoice-iwdUCU {
  max-width: 95%;
}
:root .featuresHeader-4YwLcc {
  text-align: center;
}
:root .userSettingsVoice-iwdUCU .children-rWhLdy > :nth-child(9) .flexChild-faoVW3:last-child {
  flex: 1 !important;
}
:root .noticeRegion-1YviSH {
  right: 0;
}
:root .noticeRegion-1YviSH .container-2VW0UT {
  background-color: var(--background-tertiary) !important;
}
:root .closeButton-1tv5uR {
  border: none;
}
:root .closeButton-1tv5uR svg {
  width: 23px;
  height: 23px;
}
:root .keybind-KpFkfr {
  display: none;
}
:root .perksModal-fSYqOq {
  background: var(--background-primary);
}
:root .tierMarkerBackground-3q29am,
:root .tierHeaderLocked-1s2JJz,
:root .barBackground-2EEiLw,
:root .icon-TYbVk4 {
  background: var(--background-secondary-alt);
}
:root .option-96V44q.selected-rZcOL-,
:root .tierBody-16Chc9,
:root .perk-2WeBWW,
:root .tierMarkerInProgress-24LMzJ {
  background: var(--background-secondary) !important;
}
:root .background-1QDuV2 {
  border-radius: var(--border-radius);
}
:root .background-1QDuV2 .profile-1eT9hT {
  padding-top: 55px;
  flex-direction: column;
  justify-content: center;
}
:root .background-1QDuV2 .profile-1eT9hT .avatarUploader-3XDtmn {
  position: absolute;
  top: 55px;
  left: 45.5%;
}
:root .background-1QDuV2 .profile-1eT9hT .avatarUploader-3XDtmn .avatarUploaderInner-2EvNMg {
  width: 100px;
  height: 100px;
  border-radius: var(--border-radius);
}
:root .background-1QDuV2 .profile-1eT9hT .details-2fkb7l {
  align-items: center;
  margin-left: 0;
}
:root .background-1QDuV2 .profile-1eT9hT .menu-319q29 {
  margin: 10px 0 0 0;
}
:root .background-1QDuV2 .fieldList-21DyL8 {
  border-radius: var(--border-radius);
}
:root .item-26Dhrx {
  border-radius: var(--border-radius);
}
:root .item-26Dhrx .radioBar-bMNUI- {
  border: none;
}
:root .item-26Dhrx .radioBar-bMNUI-:first-child .radioIconForeground-XwlXQN {
  color: var(--radio-bar-accent-color);
}
:root .formNotice-2_hHWR {
  border-radius: var(--border-radius);
}
:root .formNotice-2_hHWR, :root .cardPrimaryOutline-29Ujqw {
  border: none;
}
:root .cardPrimaryOutline-29Ujqw {
  background-color: var(--background-secondary-alt);
  border-radius: var(--border-radius);
}
:root .accountList-33MS45, :root .connection-1fbD7X {
  border-radius: var(--border-radius);
}
:root .connectionHeader-2MDqhu {
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}
:root .premiumTabItem-1QTfBr .flex-1xMQg5 {
  flex-direction: row-reverse;
  justify-content: flex-end;
}
:root .premiumTabItemLink-3IZzin .icon-Zc-uZZ {
  fill: var(--background-accent) !important;
  margin-right: 5px;
}
:root .feature-2w65J5, :root .hero-EvfTTA {
  border-radius: var(--border-radius);
}
:root .gemIndicatorContainer-2jdECl {
  background-color: var(--background-tertiary);
}
:root .cardWrapper-2Min21, :root .wrapper-3nSjSv, :root .tierVertical-2ePkZj {
  border-radius: var(--border-radius);
}
:root .input-cIJ7To {
  border: none;
}
:root .paymentRow-2e7VM6, :root .pageActions-1SVAnA, :root .codeRedemptionRedirect-1wVR4b, :root .paginator-166-09 {
  background: var(--background-secondary-alt);
}
:root .payment-xT17Mq:hover {
  background-color: var(--background-secondary);
}
:root .expandedInfo-3kfShd {
  background: var(--background-secondary);
}
:root .checked-3_4uQ9 {
  background: transparent;
  border-color: transparent;
}
:root .bottomDivider-1K9Gao {
  border-bottom-color: transparent;
}
:root .codeRedemptionRedirect-1wVR4b {
  border: none;
}
:root .paymentPane-3bwJ6A, :root .expandedInfo-3kfShd {
  border-radius: var(--border-radius);
}
:root .barFill-23-gu- {
  background: var(--background-accent);
}
:root .userSettingsVoice-iwdUCU .previewOverlay-2O7_KC {
  background-color: var(--background-secondary-alt);
  border: none;
}
:root .bar-2Qqk5Z {
  background-color: var(--background-secondary-alt);
}
:root .progress-1IcQ3A {
  background-color: var(--background-primary);
}
:root .notches-1sAcEM.gray-3_LNYR {
  background-image: url("data:image/svg+xml;charset=utf-8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='8' height='20' fill='none'%3E%3Cpath fill-rule='evenodd' d='M0 0h8v20H0V0zm4 2a2 2 0 00-2 2v12a2 2 0 104 0V4a2 2 0 00-2-2z'/%3E%3C/svg%3E");
}
:root .css-118dehu-control, :root .css-gvi9bl-control, :root .css-6fzn47-control, :root .css-3vaxre-menu, :root .css-17e1tep-control {
  border: none;
}
:root .css-3vaxre-menu {
  background-color: var(--background-primary);
}
:root .css-gvi9bl-control, :root .css-118dehu-control, :root .userSettingsVoice-iwdUCU .previewOverlay-2O7_KC {
  border-radius: var(--border-radius);
}
:root .previewContainer-37c2Si .media-engine-video {
  background-color: transparent;
}
:root .container-CpszHS {
  border: none;
}
:root .container-jSV3OF, :root .container-CpszHS {
  border-radius: var(--border-radius);
}
:root .cardPrimary-1Hv-to {
  background-color: var(--background-secondary-alt);
}
:root .game-1ipmAa {
  box-shadow: none;
}
:root .notDetected-33MY4s, :root .addGamePopout-2RY8Ju, :root .card-FDVird:before {
  background: var(--background-secondary-alt);
}
:root .gameNameInput-385LoS:hover, :root .gameNameInput-385LoS:focus {
  background-color: var(--background-tertiary);
}
:root .card-FDVird:before, :root .gameNameInput-385LoS {
  border: none;
}
:root .default-3oAQTF, :root .default-3oAQTF:hover {
  background-color: var(--background-tertiary);
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11);
}
:root .lastPlayed-3bQ7Bo {
  color: var(--text-muted);
}
:root .activeGame-14JI7o {
  border-radius: var(--border-radius);
}
:root .addGamePopout-2RY8Ju {
  border: none;
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11);
  border-radius: var(--border-radius);
}
:root .game-1ipmAa, :root .game-1ipmAa::before {
  border-radius: var(--border-radius);
}
:root .membershipDialog-rVL-t_ {
  border-radius: var(--border-radius);
}
:root .cardPrimary-1Hv-to {
  border: none;
  border-radius: var(--border-radius);
}
:root .powercord-entities-manage-tabs, :root .developerPortalCtaWrapper-2XNafh {
  border-radius: var(--border-radius);
}
:root .bd-addon-list .bd-addon-card, :root .bd-search-wrapper, :root #floating-editor-window {
  border-radius: var(--border-radius);
}
:root .bd-select {
  border: none;
  transition: 0.15s;
  border-radius: var(--border-radius);
}
:root .bd-select .menu-open {
  border-radius: var(--border-radius) var(--border-radius) 0 0 !important;
}
:root .bd-select .bd-select-options {
  border: none;
  border-radius: var(--border-radius);
}
:root .bd-select .bd-select-options:last-child {
  border-radius: 0 0 var(--border-radius) var(--border-radius) !important;
}
:root .bd-controls > .bd-addon-button:first-of-type {
  border-radius: var(--border-radius) 0 0 var(--border-radius) !important;
}
:root .bd-controls > .bd-addon-button:last-of-type {
  border-radius: 0 var(--border-radius) var(--border-radius) 0 !important;
}
:root .container-cMG81i {
  border-radius: var(--border-radius);
}
:root .avatarUploaderIndicator-2G-aIZ {
  display: none;
}
:root .css-6fzn47-control {
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}
:root .css-17e1tep-control {
  border-radius: var(--border-radius);
}
:root .css-3vaxre-menu, :root .css-1ye7vu0 {
  border-radius: 0 0 var(--border-radius) var(--border-radius);
}
:root .container-_phMUq {
  border-radius: var(--border-radius);
}
:root .colorPickerCustom-2CWBn2 {
  background: var(--background-secondary);
  border: none;
  border-radius: var(--border-radius);
}
:root .addRoleButton-3Y-nzm ~ .draggable-1EOU8o {
  margin: 2px 0;
}
:root .roleDot-ZwSovK {
  border: none;
}
:root .emojiAliasInput-1y-NBz .emojiInput-1aLNse {
  background: var(--background-secondary-alt);
}
:root .input-cIJ7To:focus {
  border-color: var(--background-accent);
}
:root .headerClickable-2IVFo9, :root .headerDefault-1wrJcN, :root .headerExpanded-CUEwZ5 {
  background: var(--background-secondary-alt);
}
:root .auditLog-3jNbM6, :root .header-GwIGlr {
  border: none;
  border-radius: var(--border-radius);
}
:root .auditLog-3jNbM6 .headerExpanded-CUEwZ5, :root .header-GwIGlr .headerExpanded-CUEwZ5 {
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}
:root .auditLog-3jNbM6 .changeDetails-bk98pu, :root .header-GwIGlr .changeDetails-bk98pu {
  border-radius: 0 0 var(--border-radius) var(--border-radius);
}
:root .divider-1pnAR2 {
  display: none;
}
:root .cardPrimaryEditable-3KtE4g {
  border: none;
  background-color: var(--background-secondary-alt);
  border-radius: var(--border-radius);
}
:root .copyInput-2rOSt7 {
  border: none;
  border-radius: var(--border-radius);
}
:root .descriptionBox-1EKQKL {
  border-radius: var(--border-radius);
}
:root .css-dwar6a-menu {
  background-color: var(--background-secondary-alt);
}
:root .error-20ZZpF {
  border-radius: var(--border-radius);
}
:root .featureCard-1RR4Tl, :root .checklistContainer-mFJZEJ {
  border-radius: var(--border-radius);
}
:root .checklistHeader-1KWcEY {
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}
:root .checklist-3Y6Fqp {
  border-radius: var(--border-radius);
}
:root .checklist-3Y6Fqp .header-2Y0-A- {
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}
:root .exampleContainer-3ekFIr {
  border-radius: var(--border-radius);
}
:root .enableContainer-6E-puu {
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}
:root .previewContainer-1SS3uO {
  border-radius: 0 0 var(--border-radius) var(--border-radius);
}
:root .previewContainer-1SS3uO .welcomeChannel-1rFrIO {
  border-radius: var(--border-radius);
}
:root [aria-controls=GUILD_PREMIUM-tab], :root [aria-controls="Discord Nitro-tab"] {
  color: var(--background-accent) !important;
  background-color: var(--background-modifier-selected) !important;
}
:root .tierBody-x9kBBp {
  background-color: var(--background-secondary);
}
:root .tierHeaderContent-2-YfvN, :root .tierInProgress-3mBoXq {
  background: var(--background-tertiary);
}
:root .background-3xPPFc {
  color: var(--background-secondary-alt);
}
:root .tierHeader-rlkkJd, :root .tierHeaderContent-2-YfvN {
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}
:root .tierBody-x9kBBp {
  border-radius: 0 0 var(--border-radius) var(--border-radius);
}
:root .overflowRolesPopout-140n9i, :root .overflowRolesPopoutArrow-2O66oH {
  background-color: var(--background-secondary);
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11);
}

:root .nowPlayingColumn-2sl4cE {
  position: fixed;
  top: 280px;
  bottom: 120px;
  right: 60px;
  width: 320px;
  min-width: unset;
  background-color: var(--background-primary);
}
:root .nowPlayingColumn-2sl4cE::before {
  content: "Friends activity";
  position: absolute;
  top: -60px;
  z-index: 1;
  width: 100%;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 20px;
  font-weight: bolder;
  color: var(--header-primary);
  background-color: var(--background-secondary);
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}
:root .nowPlayingColumn-2sl4cE::after {
  content: "";
  position: absolute;
  bottom: -35px;
  z-index: 1;
  width: 100%;
  height: 35px;
  background-color: var(--background-secondary);
  border-radius: 0 0 var(--border-radius) var(--border-radius);
  background-image: linear-gradient(to right, var(--header-primary) 33%, rgba(255, 255, 255, 0) 0%);
  background-position: top;
  background-size: 21px 2px;
  background-repeat: repeat-x;
}
:root .container-1D34oG {
  background-color: var(--background-primary);
}
:root .container-1D34oG .peopleListItem-2nzedh {
  border-radius: var(--border-radius);
  border-top: none;
  background: var(--background-modifier-hover);
  margin: 8px 10px 8px 20px;
  padding: 16px 10px;
}
:root .container-1D34oG .peopleListItem-2nzedh:hover .actionButton-uPB8Fs {
  background-color: var(--background-secondary-alt);
}
:root .nowPlayingColumn-2sl4cE .scroller-2ZPeAD {
  border: none;
}
:root .controlButton-2MhVEL foreignObject {
  mask: none;
}
:root .colorable-1bkp8v.primaryDark-3mSFDl {
  background-color: var(--background-primary);
}
:root .wrapper-2qzCYF {
  background-color: var(--background-tertiary);
}
:root .inset-3sAvek {
  background-color: var(--background-primary);
}
:root .separator-XqIyoz {
  display: none;
}
:root .voiceSectionIconWrapper-FO7UEY {
  background-color: var(--background-tertiary);
}
:root .outer-1AjyKL.active-1xchHY, :root .outer-1AjyKL.interactive-3B9GmY:hover {
  background-color: var(--activity-card-background);
}
:root .itemCard-v9viV7 {
  border-radius: var(--border-radius);
}
:root .itemCard-v9viV7 .body-1ld4H7 {
  border-radius: calc(var(--border-radius) - 10px);
}
:root .quickSelectPopout-X1hvgV.regionSelectPopout-p9-0_W {
  background-color: var(--background-secondary-alt);
}

:root .app-1q1i1E::before, :root .app-1q1i1E::after, :root .app-2rEoOp::after, :root .app-2rEoOp::before, :root .layers-3iHuyZ::before, :root .layers-3iHuyZ::after, :root .app-1q1i1E::before, :root .bg-h5JY_x::after {
  content: "";
  position: fixed;
  z-index: 1;
  pointer-events: none;
}
:root .app-1q1i1E::before {
  left: 0;
  top: 0;
  width: 250px;
  height: 250px;
  background: url("https://i.imgur.com/jTpFJuI.png") no-repeat;
  background-size: 100%;
}
:root .app-1q1i1E::after {
  z-index: 0;
  left: 50px;
  bottom: 0;
  width: 490px;
  height: 40px;
  background: url("https://i.imgur.com/KQQWcTY.png") no-repeat;
  background-size: 100%;
}
:root .app-2rEoOp::before {
  top: 80px;
  right: 116px;
  width: 200px;
  height: 120px;
  background: url("https://i.imgur.com/0nsnP69.png") no-repeat;
  background-size: 100%;
}
:root .app-2rEoOp::after {
  bottom: 20px;
  right: 45%;
  width: 40px;
  height: 40px;
  background: url("https://i.imgur.com/OBSWYht.png");
  background-size: 100%;
}
:root .layers-3iHuyZ::before {
  z-index: 0;
  bottom: 75px;
  right: 0;
  width: 20px;
  height: 50px;
  background: url("https://i.imgur.com/WveiFXb.png") no-repeat;
  background-size: 100%;
}
:root .layers-3iHuyZ::after {
  bottom: 15px;
  right: 100px;
  width: 25px;
  height: 25px;
  background: url("https://i.imgur.com/WBUag7e.png") no-repeat;
  background-size: 100%;
}
:root .bg-h5JY_x::after {
  top: 45px;
  right: 385px;
  width: 30px;
  height: 30px;
  background: url("https://i.imgur.com/aOYvahh.png") no-repeat;
  background-size: 100%;
}
:root .bg-h5JY_x::before {
  z-index: 2;
  bottom: 30%;
  right: 430px;
  width: 30px;
  height: 40px;
  background: url("https://i.imgur.com/JMoXBIs.png") no-repeat;
  background-size: 100%;
}

:root ::-webkit-input-placeholder, :root body, :root button, :root input, :root select, :root textarea {
  font-family: "Nunito" !important;
  font-weight: bold !important;
}
:root .bg-h5JY_x {
  background: var(--background-tertiary-alt);
  background-size: 100%;
  background-repeat: no-repeat;
}
:root .winButton-iRh8-Z {
  background-color: var(--background-primary);
}
:root .winButton-iRh8-Z:last-child {
  border-bottom-left-radius: 8px;
}
:root button, :root input, :root textarea, :root .item-PXvHYJ:not([class^=tabBarItem-]), :root .menu-3sdvDG {
  border-radius: var(--border-radius) !important;
}
:root .modal-yWgWj-, :root .root-1gCeng, :root .uploadModal-2ifh8j {
  border-radius: var(--border-radius);
  background-color: var(--background-secondary);
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11);
}
:root .footer-2gL1pp, :root .footer-3mqk7D {
  border-radius: 0 0 var(--border-radius) var(--border-radius);
  background-color: var(--background-tertiary);
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11);
}
:root .menu-3sdvDG {
  overflow: hidden;
}
:root .scroller-3BxosC {
  padding: 0;
}
:root .scroller-3BxosC::-webkit-scrollbar, :root .scroller-3BxosC .separator-2I32lJ {
  display: none;
}
:root .scroller-3BxosC .item-1tOPte {
  padding: 10px 10px 10px 13px;
  margin: 0;
  transition: 0.15s;
  border-radius: 0;
}
:root .scroller-3BxosC .submenuContainer-2gbm7M .layer-v9HyYc {
  margin: 0 -8px;
}
:root #status-picker {
  left: -6px;
  width: 319px;
}
:root #status-picker .description-2L932D {
  display: none;
}
:root .select-2fjwPw,
:root .popout-VcNcHB {
  border: none;
}
:root .select-2fjwPw.open-kZ53_U,
:root .popout-VcNcHB {
  background-color: var(--background-secondary-alt);
  transition: 0.15s;
}
:root .theme-dark .footer-2gL1pp {
  background: var(--background-tertiary);
}
:root .select-2fjwPw, :root .popout-VcNcHB {
  border: none;
}
:root .titleBar-AC4pGV .wordmark-2iDDfm {
  display: none;
}
:root .powercord-toast {
  border-radius: var(--border-radius);
}
:root .powercord-toast .header {
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}
:root .powercord-toast .buttons > .button-38aScr:first-child {
  border-bottom-left-radius: var(--border-radius);
}
:root .powercord-toast .buttons > .button-38aScr:last-child {
  border-bottom-right-radius: var(--border-radius);
}
:root .sprite-2iCowe {
  filter: none !important;
}
:root .header-3msK0M {
  overflow-x: visible;
}
@media (min-width: 1200px) {
  :root .sidebar-2K8pFh > .thin-1ybCId.scrollerBase-289Jih {
    position: fixed;
    top: 220px;
    bottom: 85px;
    right: 60px;
    width: 320px;
    border-radius: var(--border-radius);
    background-color: var(--background-primary);
    padding-bottom: 60px;
  }
  :root .sidebar-2K8pFh > .thin-1ybCId.scrollerBase-289Jih::before {
    content: "Discover";
    position: absolute;
    top: 0;
    z-index: 1;
    width: 100%;
    height: 60px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 20px;
    font-weight: bolder;
    color: var(--header-primary);
    background-color: var(--background-secondary);
    border-radius: var(--border-radius) var(--border-radius) 0 0;
  }
  :root .sidebar-2K8pFh > .thin-1ybCId.scrollerBase-289Jih::after {
    content: "";
    position: fixed;
    bottom: 85px;
    z-index: 1;
    width: 320px;
    height: 35px;
    background-color: var(--background-secondary);
    border-radius: 0 0 var(--border-radius) var(--border-radius);
    background-image: linear-gradient(to right, var(--header-primary) 33%, rgba(255, 255, 255, 0) 0%);
    background-position: top;
    background-size: 21px 2px;
    background-repeat: repeat-x;
  }
  :root .sidebar-2K8pFh > .thin-1ybCId.scrollerBase-289Jih::-webkit-scrollbar {
    display: none;
  }
}
:root .categoryItem-1QIroW .itemInner-gPkiWb {
  background-color: transparent;
}
:root .pageWrapper-1PgVDX {
  background-color: var(--background-primary);
}
:root .notice-2X5hT5 {
  border-top-left-radius: 0;
  background-color: var(--background-tertiary);
}
:root .button-2PWmas:hover {
  background-color: transparent;
}
:root .headerImage-3X1tyY, :root .card-3DjzTQ {
  border-radius: var(--border-radius);
}
:root .tile-2naSqK {
  background-color: var(--background-secondary-alt);
  border-radius: var(--border-radius);
}
:root .tile-2naSqK .button-3HqqDX {
  background-color: var(--background-accent);
}
:root .contentWrapper-3WC1ID {
  background: var(--background-secondary);
}
:root .root-1gCeng:not(.modal-qgFCbT) {
  background: var(--background-secondary);
}
:root .keyboardShortcutsModal-3piNz7 {
  background: var(--background-secondary);
}
:root .scroller-1JpcIc {
  background: var(--background-primary);
}
:root .whyYouMightLikeIt-2zZIIj, :root .content-35aVm0, :root .bodySection-jqkkIP, :root .row-1bU71H {
  background: var(--background-secondary);
}
:root .toolbar-2bjZV7 {
  display: flex !important;
  background-color: var(--background-secondary-alt);
}
:root .toolbar-2bjZV7::before {
  border-top: 8px solid var(--background-secondary-alt);
}
:root .toolbar-2bjZV7 .button-qqmJ7w {
  background-color: transparent !important;
}
:root #permissions-modal-wrapper #permissions-modal {
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(56, 31, 31, 0.11) !important;
  border-color: var(--background-tertiary) !important;
}
:root #permissions-modal-wrapper .header {
  background: var(--background-tertiary) !important;
  text-align: center !important;
}
:root #permissions-modal-wrapper .role-side,
:root #permissions-modal-wrapper .perm-side {
  background: var(--background-secondary) !important;
}
:root #MemberCount {
  background-color: var(--background-secondary) !important;
}

/* -- Donators -- */
/* - Badge - */
[aria-label^=Qvas] .profileBadges-1dm1_q > :last-child,
[aria-label^=PANIC] .profileBadges-1dm1_q > :last-child {
  margin-right: 30px;
}

[aria-label^=Qvas] .profileBadges-1dm1_q::before,
[aria-label^=PANIC] .profileBadges-1dm1_q::before {
  content: "";
  position: absolute;
  width: 90px;
  height: 90px;
  right: 0;
  pointer-events: none;
  background: url("https://cdn.discordapp.com/emojis/813060332704366642.png?v=1") no-repeat;
  background-size: 24%;
  background-position: right top;
}

[aria-label^=Qvas] .profileBadges-1dm1_q:hover::before,
[aria-label^=PANIC] .profileBadges-1dm1_q:hover::before {
  content: "Donator";
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

.members-1998pB .wrapper-3t9DeA[data-user-id="596812194906374167"]::before,
.members-1998pB .wrapper-3t9DeA[vz-user-id="596812194906374167"]::before,
.members-1998pB .wrapper-3t9DeA[data-user-id="193188089756123136"]::before,
.members-1998pB .wrapper-3t9DeA[vz-user-id="193188089756123136"]::before {
  content: "";
  position: absolute;
  width: 18px;
  height: 14px;
  bottom: -3px;
  left: -5px;
  z-index: 2;
  background: url("https://cdn.discordapp.com/emojis/813060332704366642.png?v=1") no-repeat;
  background-size: 80%;
  background-position: center left;
  background-color: var(--background-secondary);
  border-radius: 0 5px 0 0;
  pointer-events: none;
}

/* - PANIC#6666 - Animated gradient blue username */
/* Messages */
[data-author-id="193188089756123136"] .username-1A8OIy,
[vz-user-id="193188089756123136"] .username-1A8OIy,
[data-user-id="193188089756123136"] .username-1A8OIy,
[data-user-id="193188089756123136"] + .headerInfo-30uryT .username-2b1r56,
[vz-user-id="193188089756123136"] .username-2b1r56,
[data-user-id="193188089756123136"] .username-2b1r56,
[aria-label=PANIC] .username-2b1r56,
.privateChannels-1nO12o [vz-user-id="193188089756123136"] .overflow-WK9Ogt,
.privateChannels-1nO12o [data-user-id="193188089756123136"] .overflow-WK9Ogt,
.privateChannels-1nO12o [aria-label^=PANIC] .overflow-WK9Ogt {
  animation: flow 10s ease-in-out infinite;
  background: linear-gradient(-60deg, #1a8ce9 40%, #03111b 80%, #1a8ce9 100%);
  background-size: 300%;
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* - Qvas#7777 - Animated gradient gold username */
/* Messages */
[data-author-id="596812194906374167"] .username-1A8OIy,
[vz-user-id="596812194906374167"] .username-1A8OIy,
[data-user-id="596812194906374167"] .username-1A8OIy,
[data-user-id="596812194906374167"] + .headerInfo-30uryT .username-2b1r56,
[vz-user-id="596812194906374167"] .username-2b1r56,
[data-user-id="596812194906374167"] .username-2b1r56,
[aria-label=Qvas] .username-2b1r56,
.privateChannels-1nO12o [vz-user-id="596812194906374167"] .overflow-WK9Ogt,
.privateChannels-1nO12o [data-user-id="596812194906374167"] .overflow-WK9Ogt,
.privateChannels-1nO12o [aria-label^=Qvas] .overflow-WK9Ogt {
  animation: flow 15s ease-in-out infinite;
  background: linear-gradient(-60deg, #ffe23b, #a18400, #ffe23b);
  background-size: 300%;
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

@keyframes flow {
  0% {
    background-position: 0 50%;
  }
  50% {
    background-position: 300% 50%;
  }
  100% {
    background-position: 0 50%;
  }
}
@media (min-width: 1200px) {
  .chatContent-a9vAAp + :last-child {
    position: fixed;
    top: 280px;
    bottom: 120px;
    right: 60px;
    width: 320px;
  }

  .tabBody-3YRQ8W {
    transform: none;
  }

  .container-2lgZY8::after {
    content: "Stay comfy ❤";
    position: fixed;
    top: 220px;
    bottom: 85px;
    right: 60px;
    z-index: -2;
    width: 320px;
    background-color: var(--background-primary);
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 30px;
    color: var(--text-normal);
    border-radius: var(--border-radius);
    overflow: hidden;
  }

  .container-2lgZY8::before {
    content: "";
    position: fixed;
    top: 220px;
    bottom: 85px;
    right: 70px;
    z-index: -1;
    width: 300px;
    border-radius: var(--border-radius);
    background: var(--jumping-gif) bottom/40% no-repeat;
  }

  .guilds-1SWlCJ + :nth-child(2) {
    margin-right: 450px;
    border-radius: 0 var(--border-radius) var(--border-radius) 0;
  }

  .panels-j1Uci_ > .container-3baos1 {
    position: fixed;
    width: 305px;
    height: 50px;
    bottom: 28px;
    right: 60px;
    background-color: var(--background-primary);
    border-radius: var(--border-radius);
  }

  .container-2lgZY8 {
    overflow: visible;
  }

  .layers-3iHuyZ > :nth-child(2) {
    margin-right: 450px;
  }
}
