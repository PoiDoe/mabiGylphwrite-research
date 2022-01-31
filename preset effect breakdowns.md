ID:

- 1 = line
- 2 = empty circle
- 3 = filled circle
- 4 = empty triangle
- 5 = filled triangle
- 6 = empty square
- 7 = filled square
- 8 = empty star
- 9 = filled star
- 10 = empty heart
- 11 = filled heart
- 12 = empty knot
- 13 = filled knot

- 14 = rune 1
- 15 = rune 2
- 16 = rune 3
- 17 = rune 4
- 18 = rune 5


![Glyphboard 1](https://user-images.githubusercontent.com/20039012/151747013-def9ece3-0a2a-4838-bb68-69301be5f528.jpg)

- 0,0 is center of gplyh
- PosX/Y = -200 ~ 200
- StartY/X = -200 ~ 200
- EndY/X = -200 ~ 200
- Rot = 0.00 ~ 359.99
- Scale = 0.01 ~ 1.69 (depends on shape)
- Flip = true/false


//escaped

&lt;Effects&gt;&#xD;&#xA;
&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;1.69&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;-197&quot; EndX=&quot;116&quot; EndY=&quot;159&quot; /&gt;&#xD;&#xA;
&lt;/Effects&gt;

//un escapped

```xml
<Effects>
<Effect ID="2" PosX="0" PosY="0" Rot="0.00" Scale="1.69" Flip="false" />
<Effect ID="2" PosX="0" PosY="0" Rot="0.00" Scale="1.29" Flip="false" />
<Effect ID="6" PosX="0" PosY="0" Rot="0.00" Scale="1.29" Flip="false" />
<Effect ID="6" PosX="0" PosY="0" Rot="45.00" Scale="1.29" Flip="false" />
<Effect ID="2" PosX="0" PosY="0" Rot="0.00" Scale="0.69" Flip="false" />
</Effects>
```

//eample effects

&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;-197&quot; EndX=&quot;116&quot; EndY=&quot;159&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;1.69&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;

//empty glyh

"&lt;Effects&gt;&#xD;&#xA; &lt;/Effects&gt;"



https://user-images.githubusercontent.com/20039012/151747036-43b964a4-54a4-4fc8-96d4-02a91ca3c873.mp4

![Example 1](https://user-images.githubusercontent.com/20039012/151747041-204b0da5-a03e-4845-961c-8bf158bbab07.jpg)

//full preset entry

	<Preset Id="1" Name="PoiGlyph1" UI="data/gfx/gui/Magigraph/GUI_magigraph_icon.dds" PositionX="5" PositionY="2" Argument="&lt;Effects&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;1.69&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.50&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;13&quot; PosX=&quot;0&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.48&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;150&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;17&quot; PosX=&quot;150&quot; PosY=&quot;0&quot; Rot=&quot;90.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;-150&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;15&quot; PosX=&quot;-150&quot; PosY=&quot;0&quot; Rot=&quot;270.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;-150&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;16&quot; PosX=&quot;0&quot; PosY=&quot;-150&quot; Rot=&quot;0.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;150&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;14&quot; PosX=&quot;0&quot; PosY=&quot;150&quot; Rot=&quot;180.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;-106&quot; PosY=&quot;-106&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;18&quot; PosX=&quot;-106&quot; PosY=&quot;-106&quot; Rot=&quot;315.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;106&quot; PosY=&quot;106&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;18&quot; PosX=&quot;106&quot; PosY=&quot;106&quot; Rot=&quot;135.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;-144&quot; StartY=&quot;-41&quot; EndX=&quot;-131&quot; EndY=&quot;-73&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;-73&quot; StartY=&quot;-131&quot; EndX=&quot;-41&quot; EndY=&quot;-144&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;144&quot; StartY=&quot;41&quot; EndX=&quot;131&quot; EndY=&quot;73&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;73&quot; StartY=&quot;131&quot; EndX=&quot;41&quot; EndY=&quot;144&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;-109&quot; StartY=&quot;0&quot; EndX=&quot;-58&quot; EndY=&quot;0&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;109&quot; StartY=&quot;0&quot; EndX=&quot;58&quot; EndY=&quot;0&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;-109&quot; EndX=&quot;0&quot; EndY=&quot;-58&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;109&quot; EndX=&quot;0&quot; EndY=&quot;58&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;-100&quot; EndX=&quot;70&quot; EndY=&quot;-100&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;100&quot; StartY=&quot;0&quot; EndX=&quot;100&quot; EndY=&quot;-70&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;70&quot; StartY=&quot;-100&quot; EndX=&quot;100&quot; EndY=&quot;-70&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;100&quot; EndX=&quot;-70&quot; EndY=&quot;100&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;-100&quot; StartY=&quot;0&quot; EndX=&quot;-100&quot; EndY=&quot;70&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;-70&quot; StartY=&quot;100&quot; EndX=&quot;-100&quot; EndY=&quot;70&quot; /&gt;&#xD;&#xA;&lt;/Effects&gt;"/>




//poigplyh full

"&lt;Effects&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;1.69&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.50&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;13&quot; PosX=&quot;0&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.48&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;150&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;17&quot; PosX=&quot;150&quot; PosY=&quot;0&quot; Rot=&quot;90.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;-150&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;15&quot; PosX=&quot;-150&quot; PosY=&quot;0&quot; Rot=&quot;270.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;-150&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;16&quot; PosX=&quot;0&quot; PosY=&quot;-150&quot; Rot=&quot;0.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;150&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;14&quot; PosX=&quot;0&quot; PosY=&quot;150&quot; Rot=&quot;180.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;-106&quot; PosY=&quot;-106&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;18&quot; PosX=&quot;-106&quot; PosY=&quot;-106&quot; Rot=&quot;315.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;2&quot; PosX=&quot;106&quot; PosY=&quot;106&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;18&quot; PosX=&quot;106&quot; PosY=&quot;106&quot; Rot=&quot;135.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;-144&quot; StartY=&quot;-41&quot; EndX=&quot;-131&quot; EndY=&quot;-73&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;-73&quot; StartY=&quot;-131&quot; EndX=&quot;-41&quot; EndY=&quot;-144&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;144&quot; StartY=&quot;41&quot; EndX=&quot;131&quot; EndY=&quot;73&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;73&quot; StartY=&quot;131&quot; EndX=&quot;41&quot; EndY=&quot;144&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;-109&quot; StartY=&quot;0&quot; EndX=&quot;-58&quot; EndY=&quot;0&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;109&quot; StartY=&quot;0&quot; EndX=&quot;58&quot; EndY=&quot;0&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;-109&quot; EndX=&quot;0&quot; EndY=&quot;-58&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;109&quot; EndX=&quot;0&quot; EndY=&quot;58&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;-100&quot; EndX=&quot;70&quot; EndY=&quot;-100&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;100&quot; StartY=&quot;0&quot; EndX=&quot;100&quot; EndY=&quot;-70&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;70&quot; StartY=&quot;-100&quot; EndX=&quot;100&quot; EndY=&quot;-70&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;100&quot; EndX=&quot;-70&quot; EndY=&quot;100&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;-100&quot; StartY=&quot;0&quot; EndX=&quot;-100&quot; EndY=&quot;70&quot; /&gt;&#xD;&#xA;&lt;Effect ID=&quot;1&quot; StartX=&quot;-70&quot; StartY=&quot;100&quot; EndX=&quot;-100&quot; EndY=&quot;70&quot; /&gt;&#xD;&#xA;&lt;/Effects&gt;"

//poiglyph 1 broken down but escaped

&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;1.69&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.50&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;13&quot; PosX=&quot;0&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.48&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;


&lt;Effect ID=&quot;2&quot; PosX=&quot;150&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;17&quot; PosX=&quot;150&quot; PosY=&quot;0&quot; Rot=&quot;90.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;

&lt;Effect ID=&quot;2&quot; PosX=&quot;-150&quot; PosY=&quot;0&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;15&quot; PosX=&quot;-150&quot; PosY=&quot;0&quot; Rot=&quot;270.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;

&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;-150&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;16&quot; PosX=&quot;0&quot; PosY=&quot;-150&quot; Rot=&quot;0.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;

&lt;Effect ID=&quot;2&quot; PosX=&quot;0&quot; PosY=&quot;150&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;14&quot; PosX=&quot;0&quot; PosY=&quot;150&quot; Rot=&quot;180.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;


&lt;Effect ID=&quot;2&quot; PosX=&quot;-106&quot; PosY=&quot;-106&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;18&quot; PosX=&quot;-106&quot; PosY=&quot;-106&quot; Rot=&quot;315.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;

&lt;Effect ID=&quot;2&quot; PosX=&quot;106&quot; PosY=&quot;106&quot; Rot=&quot;0.00&quot; Scale=&quot;0.36&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;18&quot; PosX=&quot;106&quot; PosY=&quot;106&quot; Rot=&quot;135.00&quot; Scale=&quot;0.30&quot; Flip=&quot;false&quot; /&gt;&#xD;&#xA;


&lt;Effect ID=&quot;1&quot; StartX=&quot;-144&quot; StartY=&quot;-41&quot; EndX=&quot;-131&quot; EndY=&quot;-73&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;1&quot; StartX=&quot;-73&quot; StartY=&quot;-131&quot; EndX=&quot;-41&quot; EndY=&quot;-144&quot; /&gt;&#xD;&#xA;

&lt;Effect ID=&quot;1&quot; StartX=&quot;144&quot; StartY=&quot;41&quot; EndX=&quot;131&quot; EndY=&quot;73&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;1&quot; StartX=&quot;73&quot; StartY=&quot;131&quot; EndX=&quot;41&quot; EndY=&quot;144&quot; /&gt;&#xD;&#xA;


&lt;Effect ID=&quot;1&quot; StartX=&quot;-109&quot; StartY=&quot;0&quot; EndX=&quot;-58&quot; EndY=&quot;0&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;1&quot; StartX=&quot;109&quot; StartY=&quot;0&quot; EndX=&quot;58&quot; EndY=&quot;0&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;-109&quot; EndX=&quot;0&quot; EndY=&quot;-58&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;109&quot; EndX=&quot;0&quot; EndY=&quot;58&quot; /&gt;&#xD;&#xA;

//poiglyph unescapped

```xml
<Effects>
<Effect ID="2" PosX="0" PosY="0" Rot="0.00" Scale="1.69" Flip="false" />
<Effect ID="2" PosX="0" PosY="0" Rot="0.00" Scale="0.50" Flip="false" />
<Effect ID="13" PosX="0" PosY="0" Rot="0.00" Scale="0.48" Flip="false" />
<Effect ID="2" PosX="150" PosY="0" Rot="0.00" Scale="0.36" Flip="false" />
<Effect ID="17" PosX="150" PosY="0" Rot="90.00" Scale="0.30" Flip="false" />
<Effect ID="2" PosX="-150" PosY="0" Rot="0.00" Scale="0.36" Flip="false" />
<Effect ID="15" PosX="-150" PosY="0" Rot="270.00" Scale="0.30" Flip="false" />
<Effect ID="2" PosX="0" PosY="-150" Rot="0.00" Scale="0.36" Flip="false" />
<Effect ID="16" PosX="0" PosY="-150" Rot="0.00" Scale="0.30" Flip="false" />
<Effect ID="2" PosX="0" PosY="150" Rot="0.00" Scale="0.36" Flip="false" />
<Effect ID="14" PosX="0" PosY="150" Rot="180.00" Scale="0.30" Flip="false" />
<Effect ID="2" PosX="-106" PosY="-106" Rot="0.00" Scale="0.36" Flip="false" />
<Effect ID="18" PosX="-106" PosY="-106" Rot="315.00" Scale="0.30" Flip="false" />
<Effect ID="2" PosX="106" PosY="106" Rot="0.00" Scale="0.36" Flip="false" />
<Effect ID="18" PosX="106" PosY="106" Rot="135.00" Scale="0.30" Flip="false" />
<Effect ID="1" StartX="-144" StartY="-41" EndX="-131" EndY="-73" />
<Effect ID="1" StartX="-73" StartY="-131" EndX="-41" EndY="-144" />
<Effect ID="1" StartX="144" StartY="41" EndX="131" EndY="73" />
<Effect ID="1" StartX="73" StartY="131" EndX="41" EndY="144" />
<Effect ID="1" StartX="-109" StartY="0" EndX="-58" EndY="0" />
<Effect ID="1" StartX="109" StartY="0" EndX="58" EndY="0" />
<Effect ID="1" StartX="0" StartY="-109" EndX="0" EndY="-58" />
<Effect ID="1" StartX="0" StartY="109" EndX="0" EndY="58" />
<Effect ID="1" StartX="0" StartY="-100" EndX="70" EndY="-100" />
<Effect ID="1" StartX="100" StartY="0" EndX="100" EndY="-70" />
<Effect ID="1" StartX="70" StartY="-100" EndX="100" EndY="-70" />
<Effect ID="1" StartX="0" StartY="100" EndX="-70" EndY="100" />
<Effect ID="1" StartX="-100" StartY="0" EndX="-100" EndY="70" />
<Effect ID="1" StartX="-70" StartY="100" EndX="-100" EndY="70" />
</Effects>
```

&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;-100&quot; EndX=&quot;70&quot; EndY=&quot;-100&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;1&quot; StartX=&quot;100&quot; StartY=&quot;0&quot; EndX=&quot;100&quot; EndY=&quot;-70&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;1&quot; StartX=&quot;70&quot; StartY=&quot;-100&quot; EndX=&quot;100&quot; EndY=&quot;-70&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;1&quot; StartX=&quot;0&quot; StartY=&quot;100&quot; EndX=&quot;-70&quot; EndY=&quot;100&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;1&quot; StartX=&quot;-100&quot; StartY=&quot;0&quot; EndX=&quot;-100&quot; EndY=&quot;70&quot; /&gt;&#xD;&#xA;
&lt;Effect ID=&quot;1&quot; StartX=&quot;-70&quot; StartY=&quot;100&quot; EndX=&quot;-100&quot; EndY=&quot;70&quot; /&gt;&#xD;&#xA;
