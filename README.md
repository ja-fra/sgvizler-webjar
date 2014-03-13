# Sgvizler webjar

Webjar for [Sgvizler][1], a javascript which renders the result of `SPARQL SELECT` queries into charts or html elements. It is cool stuff!

## Current Version

```xml
<dependency>
    <groupId>org.webjars</groupId>
    <artifactId>sgvizler</artifactId>
    <version>0.6-SNAPSHOT</version>
</dependency>
```

## Dependencies

Besides *jQuery*, which can be included using webjars, Sgvizler also requires the [Google Visualization API][2], so don't forget to include it:

```html
<script type="text/javascript" src="https://www.google.com/jsapi"></script>
```

```xml
<dependencies>
    <dependency>
        <groupId>org.webjars</groupId>
        <artifactId>jquery</artifactId>
        <version>1.9.0</version>
    </dependency>
</dependencies>
```

## License

Sgvizler is available under a **MIT-like** license, with the copyright-clause removed:

```
Copyright (c) 2011 Martin G. Skjæveland

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

For further details please refer the the [Sgvizler homepage][1] 
and the original [license file](http://dev.data2000.no/sgvizler/browser/release/0.6/LICENSE).


[1]: http://dev.data2000.no/sgvizler/
[2]: https://developers.google.com/chart/interactive/docs/reference
