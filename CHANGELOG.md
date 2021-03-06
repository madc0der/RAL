# Changelog

## 1.13.0
- Add Window.document, Element.setInnerHtml, Element.appendHtml, Document.getElementsByTagName 

## 1.12.0
- Add Location.reload()

## 1.11.0
- Add CssStyleDeclaration.letterSpacing

## 1.10.0
- Add Element.hidden

## 1.9.1
- Fix CanvasRenderingContext2D.globalCompositeOperation added to interface to

## 1.9.0
- Add CanvasRenderingContext2D.globalCompositeOperation

## 1.8.0
- Add KeyboardEvent

## 1.7.0
- Add MouseEvent.client
- Add Element.getBoundingClientRect
- Add Element.classes
- Add CssStyleDeclaration.top

## 1.6.0
- Add default implementation of CanvasElement with basically initialized fields
- Add default mouse and scroll event streams
- Add CanvasRenderingContext2D.quadraticCurveTo

## 1.5.6
- Add Element.focus()

## 1.5.5
- Add Element.onDoubleClick
- Add Document with onMouseDown, onMouseMove, onMouseLeave, onMouseUp, onMouseWheel, onDoubleClick
- Add to Node: ownerDocument

## 1.5.4
- Add Element.scrollHeight and Element.scrollWidth

## 1.5.3
- Add CanvasRenderingContext2D.rotate

## 1.5.2
- Fixed all hints of dart analyzer
- Add .travis.yaml and Travis status to README
- Suppress error with missing function "_fromBrowserObject(object);" in lib/io/js/src/js_object.dart

## 1.5.1
- Fixed bunch of dart errors 

## 1.5.0
- Add browser_detect_i with Browser
- Add querySelector
- Add to Window: devicePixelRatio, onResize, animationFrame
- Add to Element: onMouseDown, onMouseMove, onMouseLeave, onMouseUp, onScroll, onMouseWhee, scrollTop, clientWidth, clientHeight, offsetWidth, scrollLeft, style
- Add UIEvent, MouseEvent, WheelEvent, TextMetrics, CanvasPattern, CanvasRenderingContext2D , HtmlElement, CssStyleDeclaration, CssClassSet, CanvasElement


## 1.4.0

- Add allowInterop, allowInteropCaptureThis
- Add Window.Location interface

## 1.3.0
- Add window.sessionStorage

## 1.2.0
- Add window.open method

## 1.0.0

- Initial version, created by Stagehand
- initial dart:html
- initial dart:js
- initial package:js