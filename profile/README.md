<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>readme</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}
html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}
body {
	line-height: 1.5;
	white-space: pre-wrap;
}
a,
a.visited {
	color: inherit;
	text-decoration: underline;
}
.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}
h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}
.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}
h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}
h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}
h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}
.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}
.callout {
	border-radius: 3px;
	padding: 1rem;
}
figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}
figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}
mark {
	background-color: transparent;
}
.indented {
	padding-left: 1.5em;
}
hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}
img {
	max-width: 100%;
}
@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}
@page {
	margin: 1in;
}
.collection-content {
	font-size: 0.875rem;
}
.column-list {
	display: flex;
	justify-content: space-between;
}
.column {
	padding: 0 1em;
}
.column:first-child {
	padding-left: 0;
}
.column:last-child {
	padding-right: 0;
}
.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}
.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}
.table_of_contents-indent-2 {
	margin-left: 3rem;
}
.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}
.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}
table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}
table {
	border-left: none;
	border-right: none;
}
th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}
th {
	color: rgba(55, 53, 47, 0.6);
}
ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}
li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}
ul > li {
	list-style: disc;
}
ul.to-do-list {
	padding-inline-start: 0;
}
ul.to-do-list > li {
	list-style: none;
}
.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}
ul.toggle > li {
	list-style: none;
}
ul {
	padding-inline-start: 1.7em;
}
ul > li {
	padding-left: 0.1em;
}
ol {
	padding-inline-start: 1.6em;
}
ol > li {
	padding-left: 0.2em;
}
.mono ol {
	padding-inline-start: 2em;
}
.mono ol > li {
	text-indent: -0.4em;
}
.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}
/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}
.toggle > li > details > summary {
	margin-left: -1.1em;
}
.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}
.collection-title {
	display: inline-block;
	margin-right: 1em;
}
.page-description {
    margin-bottom: 2em;
}
.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}
.simple-table th {
	height: 29px;
	min-width: 120px;
}
.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}
time {
	opacity: 0.5;
}
.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}
img.icon {
	border-radius: 3px;
}
.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}
.user-icon-inner {
	font-size: 0.8em;
}
.text-icon {
	border: 1px solid #000;
	text-align: center;
}
.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}
.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}
.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}
.page-header-icon img {
	border-radius: 3px;
}
.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}
p > .user {
	opacity: 0.5;
}
td > .user,
td > time {
	white-space: nowrap;
}
input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}
p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}
.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}
.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}
code {
	color: #eb5757;
}
.code {
	padding: 1.5em 1em;
}
.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}
.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}
blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}
.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}
.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}
.bookmark-text {
	display: flex;
	flex-direction: column;
}
.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}
.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}
.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}
.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}
.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: rgba(35, 131, 226, .07); }
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-transparentGray { background-color: rgba(227, 226, 224, 0); }
.select-value-color-translucentGray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }
.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}
.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}
.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
</style></head><body><article id="6603f57d-9663-404e-92a4-18a4dc03f813" class="page sans"><header><h1 class="page-title">readme</h1><p class="page-description"></p><table class="properties"><tbody><tr class="property-row property-row-multi_select"><th><span class="icon property-icon"><svg role="graphics-symbol" viewBox="0 0 16 16" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0" class="typesMultipleSelect"><path d="M1.91602 4.83789C2.44238 4.83789 2.87305 4.40723 2.87305 3.87402C2.87305 3.34766 2.44238 2.91699 1.91602 2.91699C1.38281 2.91699 0.952148 3.34766 0.952148 3.87402C0.952148 4.40723 1.38281 4.83789 1.91602 4.83789ZM5.1084 4.52344H14.3984C14.7607 4.52344 15.0479 4.23633 15.0479 3.87402C15.0479 3.51172 14.7607 3.22461 14.3984 3.22461H5.1084C4.74609 3.22461 4.45898 3.51172 4.45898 3.87402C4.45898 4.23633 4.74609 4.52344 5.1084 4.52344ZM1.91602 9.03516C2.44238 9.03516 2.87305 8.60449 2.87305 8.07129C2.87305 7.54492 2.44238 7.11426 1.91602 7.11426C1.38281 7.11426 0.952148 7.54492 0.952148 8.07129C0.952148 8.60449 1.38281 9.03516 1.91602 9.03516ZM5.1084 8.7207H14.3984C14.7607 8.7207 15.0479 8.43359 15.0479 8.07129C15.0479 7.70898 14.7607 7.42188 14.3984 7.42188H5.1084C4.74609 7.42188 4.45898 7.70898 4.45898 8.07129C4.45898 8.43359 4.74609 8.7207 5.1084 8.7207ZM1.91602 13.2324C2.44238 13.2324 2.87305 12.8018 2.87305 12.2686C2.87305 11.7422 2.44238 11.3115 1.91602 11.3115C1.38281 11.3115 0.952148 11.7422 0.952148 12.2686C0.952148 12.8018 1.38281 13.2324 1.91602 13.2324ZM5.1084 12.918H14.3984C14.7607 12.918 15.0479 12.6309 15.0479 12.2686C15.0479 11.9062 14.7607 11.6191 14.3984 11.6191H5.1084C4.74609 11.6191 4.45898 11.9062 4.45898 12.2686C4.45898 12.6309 4.74609 12.918 5.1084 12.918Z"></path></svg></span>진행단계</th><td><span class="selected-value select-value-color-gray">진행중</span></td></tr></tbody></table></header><div class="page-body"><h2 id="592ea1e5-2849-4b60-b3d2-3a48051451e0" class="">DR.LaLa</h2><hr id="74c847be-c6f5-496c-a672-cffb11efcfaa"/><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="5c025666-4bba-4492-9fe6-145044680a3c"><div style="font-size:1.5em"><span class="icon">💡</span></div><div style="width:100%"><strong>DR.LaLa</strong>는 건강, 약과 관련한 퀴즈를 풀어볼 수 있는 서비스입니다.</div></figure><p id="508f7820-dc31-418e-84fc-965e4bb337bd" class="">
</p><h3 id="e102b157-82e8-4e5a-846e-5662a1770588" class="">프로젝트 진행 단체</h3><p id="a5ffb434-bea5-43e5-80e5-2aa826b7a95a" class="">부산외국어대학교 2024년 컴퓨터공학과 해커톤 대회에 출품하였습니다.</p><p id="08cecdaa-c78b-48f0-a6e8-093717b94cce" class="">
</p><h3 id="923374eb-ea76-43ae-a5a4-1fed81c9d073" class="">프로젝트 팀원</h3><ul id="215f0243-2ceb-4e74-b3d4-cdb3a0fdb2b1" class="bulleted-list"><li style="list-style-type:disc"><strong>프론트엔드</strong></li></ul><p id="17656db6-c741-4347-a4dc-6b52e8398e32" class="">→ 컴퓨터공학과 22학번 서예린 | <a href="https://github.com/seyerin">https://github.com/seyerin</a></p><p id="4f28d2df-367e-4569-848e-d3690e0657de" class="">
</p><ul id="f39f318c-3e21-4b2b-bc0e-881c5d0304cd" class="bulleted-list"><li style="list-style-type:disc"><strong>백엔드</strong></li></ul><p id="afeb0469-61b4-4ae9-857a-8ed1b52966bc" class="">→ 컴퓨터공학과 20학번 류동하 | <a href="https://github.com/dongha0312">https://github.com/dongha0312</a></p><p id="aa63bbed-52f2-4136-b61b-ad436a8e0516" class="">→ 컴퓨터공학과 23학번 황서은 | <a href="https://github.com/Hwangseoeun">https://github.com/Hwangseoeun</a></p><p id="407e1c35-9e53-40d4-99b6-47aeda065d05" class="">
</p><h3 id="b5f6e16d-3efc-4373-b430-a56f25736a1a" class="">사용 기술 스택</h3><p id="e580850d-ef9f-4266-9426-92dc0db878ee" class=""><strong>프론트엔드</strong> : React, Styled Component</p><p id="6e64ef6e-8df9-4541-a639-447dde6d12f1" class=""><strong>백엔드</strong> : Java, SpringBoot, Spring JPA, Mysql</p><p id="2e032e12-abc9-4a61-b216-b3b8d530864f" class=""><strong>협업</strong> : Notion</p><p id="ccfd5b47-5d67-4993-a5a5-3bc4a2a0c8d6" class="">
</p><h3 id="a80e698d-c57a-4c6a-a98f-f6ca28ad5dc0" class="">개발 기간</h3><blockquote id="979c31a5-b71a-497d-b80f-fdfdf3552717" class="">2024.05.14 ~ 2024.06.02</blockquote><p id="6cf9586d-2f1c-475e-9f54-d290f8e4e989" class="">
</p><h3 id="ba5eb9a0-41e6-4c9e-96e9-0950c71feed6" class="">프로젝트 소개</h3><hr id="bf6ff807-7642-4c62-ac9a-e30b0801014b"/><ul id="4a3cef52-74dc-47c2-96f5-96a17afb2067" class="bulleted-list"><li style="list-style-type:disc"><strong>서비스명</strong> : DR.LaLa</li></ul><p id="76ffd407-e5a2-4d41-87d9-8bc353d20df0" class="">
</p><ul id="41892915-f75c-449c-aa66-df55cc2ee73b" class="bulleted-list"><li style="list-style-type:disc"><strong>주제 선정 이유</strong></li></ul><p id="9db4930e-49c5-4a96-af60-b7270ef47495" class="">코로나19 팬데믹은 전 세계적으로 건강의 중요성을 다시 한 번 상기시켰습니다. 감염병의 위협은 건강한 생활습관과 예방의 필요성을 부각시켰고, 이에 따라 웰빙과 자기 관리에 대한 관심이 급증했습니다. 또한 현대 사회에서 건강한 생활방식이 중요한 트렌드로 자리 잡으면서, 많은 사람들이 이를 실천하고 있습니다.</p><p id="7049f782-1ca9-43e1-a738-2b54a4aba561" class="">이와 같은 변화 속에서 건강과 약 등 의료 분야는 일상 생활과 밀접하게 연관되어 있지만, 정보가 많고 다양해 많은 사람들이 중요한 정보를 놓치는 경우가 있습니다. 이러한 문제를 해결하고, 새로운 정보를 제공하기 위해 해당 서비스를 개발하게 되었습니다.</p><p id="2c851fff-5c48-4aaa-b03a-5cdda51eba0b" class="">
</p><h3 id="0bb183b8-186c-435c-a3ed-5719a2b8f653" class="">주요 기능</h3><hr id="e7cc489f-dacb-448d-a55a-e4e5ec6dc0f3"/><p id="e7092f90-e9cd-4cf6-8e1a-f040c83b2034" class="">⭐️ <strong>건강, 약에 관련한 퀴즈를 풀 수 있는 기능</strong></p><ul id="4535a92b-9a34-4a1f-886a-6e30f8e215b0" class="bulleted-list"><li style="list-style-type:disc">랜덤으로 퀴즈를 풀어볼 수 있음(중복된 문제는 나오지 않음)</li></ul><ul id="12d953d5-1479-444b-8a12-bacc923967d4" class="bulleted-list"><li style="list-style-type:disc">4지선다 or O/X 두가지의 퀴즈 스타일</li></ul><p id="1d30173d-d7ec-47f3-be86-a3d7fba4134c" class="">
</p><p id="80d839b5-5abb-47d4-9e56-211a0d7e68f1" class=""><strong>⭐️ 랭킹 기능</strong></p><ul id="0e9233c0-ab56-495b-95e2-6c3dcf550399" class="bulleted-list"><li style="list-style-type:disc">사용자가 푼 퀴즈 문제의 갯수만큼 랭킹 시스템 적용</li></ul><p id="248a10dc-166c-48e8-a42b-af52408c9e33" class="">
</p><p id="f81ff96d-13fb-4f7f-8eb2-0748f909285d" class=""><strong>⭐️ 캐릭터 성장, 도감 기능</strong></p><ul id="445fd09f-981f-40bc-9fa2-91601fb0b758" class="bulleted-list"><li style="list-style-type:disc">퀴즈 문제의 갯수만큼 캐릭터를 계속 성장시킴 (단위 : 10문제)</li></ul><p id="5259c78b-5260-433f-930c-e56336a7c25c" class="">
</p><p id="9c67a401-7a37-47db-8934-d82427421f21" class=""><strong>⭐️ 약 관련한 검색 기능</strong></p><ul id="c42a171b-f04b-476f-8807-e7941a9cfe60" class="bulleted-list"><li style="list-style-type:disc">사용자가 궁금한 약에 대하여 검색해볼 수 있음</li></ul><p id="34ef1a0b-23d6-4917-a3c8-60599993bda9" class="">
</p><p id="ab093a2e-8083-4e3b-bd32-3b934ffd2a12" class=""><strong>⭐️ 회원가입, 로그인, 로그아웃 기능</strong></p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
