---
layout: post
title: DOM元素所有样式属性表
category: knowledge
tags: CSS, Firefox, 样式
---

之前发现[elf+js](http://elfjs.com/)中设置样式的一个bug，然后决定对所有css的样式属性设置和获取都加上单测case。这里先通过Firefox获得了一个全部元素支持的样式属性表，存下来备忘。

	/* 常用属性 */
	background-attachment
	background-clip
	background-color
	background-image
	background-origin
	background-position
	background-repeat
	background-size
	border-bottom-color
	border-bottom-left-radius
	border-bottom-right-radius
	border-bottom-style
	border-bottom-width
	border-collapse
	border-left-color
	border-left-style
	border-left-width
	border-right-color
	border-right-style
	border-right-width
	border-spacing
	border-top-color
	border-top-left-radius
	border-top-right-radius
	border-top-style
	border-top-width
	bottom
	box-shadow
	caption-side
	clear
	clip
	color
	content
	counter-increment
	counter-reset
	cursor
	direction
	display
	empty-cells
	float
	font-family
	font-size
	font-size-adjust
	font-stretch
	font-style
	font-variant
	font-weight
	height
	ime-mode
	left
	letter-spacing
	line-height
	list-style-image
	list-style-position
	list-style-type
	margin-bottom
	margin-left
	margin-right
	margin-top
	marker-offset
	max-height
	max-width
	min-height
	min-width
	opacity
	outline-color
	outline-offset
	outline-style
	outline-width
	overflow
	overflow-x
	overflow-y
	padding-bottom
	padding-left
	padding-right
	padding-top
	page-break-after
	page-break-before
	pointer-events
	position
	quotes
	resize
	right
	table-layout
	text-align
	text-decoration
	text-indent
	text-overflow
	text-shadow
	text-transform
	top
	unicode-bidi
	vertical-align
	visibility
	white-space
	width
	word-spacing
	word-wrap
	z-index
	
	/* 没怎么见过的属性 */
	fill
	fill-opacity
	fill-rule
	filter
	flood-color
	flood-opacity
	image-rendering
	lighting-color
	marker-end
	marker-mid
	marker-start
	mask
	shape-rendering
	stop-color
	stop-opacity
	stroke
	stroke-dasharray
	stroke-dashoffset
	stroke-linecap
	stroke-linejoin
	stroke-miterlimit
	stroke-opacity
	stroke-width
	text-anchor
	text-rendering

其中以`-moz-`开头的FF私有属性暂时忽略掉了。后续需要测试常用属性表中的所有内容。

-EOF-