LESS Elements
=============

A set of useful mixins for LESS, the CSS pre-processor: <http://lesscss.org>

More information and usage examples over at: <http://lesselements.com> (for old 0.6 version)

TextMate bundle: <https://github.com/juanghurtado/less-elements.tmbundle> (for old 0.6 version)

   <b>v1.0 Features:</b>
   
   <ul>
   <li><b>.gradient-h</b>            - CSS3 - horizontal gradient (works in IE)</li>
   
   <code>.gradient-h(#fff, #fff, #fbfbfb);</code>
   
   <li><b>.gradient-v</b>            - CSS3 - veritical gradient (works in IE)</li>
   
   <code>.gradient-v(#fff, #fff, #fbfbfb);</code>
   
   <li><b>.gradient-radial</b>       - CSS3 - radial gradient (also works on IE9+)</li>
   
   <code>.gradient-radial(#fff, #fff, #fbfbfb);</code>
   
   <br/>
   <li><b>.bordered</b>              - custom borders color and size style</li>
      
   <code>.bordered(#EEE, #CCC, #999, #333, 1px);</code>
   
   <br/>
   <li><b>.alpha-shadow</b>          - CSS3 - transparent black shadow</li>
   
   <code>.alpha-shadow(0 0 4px, 0.6);</code>
   
   <li><b>.outer-shadow</b>          - CSS3 - outher element shadow</li>
   
   <code>.outer-shadow(0px 0px 0.83em #333);</code>
   
   <li><b>.inner-shadow</b>          - CSS3 - shadow inside the element</li>
   
   <code>.inner-shadow(0px 0px 1px #fbfbfb);</code>
   
   <li><b>.io-shadow</b>             - CSS3 - inner & outer shadow</li>
   
   <code>.io-shadow(0px 1px 0px rgba(255, 255, 255, 0.4), 0px 1px 2px rgba(0, 0, 0, 0.3));</code>
   
   <br/>
   <li><b>.rounded</b>               - CSS3 - rounded corners</li>
   
   <code>.rounded(4px);</code> or <code>.rounded(4px 2px 3px 0);</code>
   
   <li><b>.box-sizing</b>            - box-model fixes</li>
   
   <code>.box-sizing();</code>
   
   <br/>
   <li><b>.opacity</b>               - transparency for the elements</li>
   
   <code>.opacity(0.5);</code>
   
   <li><b>.font</b>                  - fast fonts editing</li>
   
   <code>.font(1em, 1.25em, bold);</code>
   
   <br/>
   <li><b>.rotation</b>              - CSS3 - simple rotate elements</li>
   
   <code>.rotation(5deg);</code>
   
   <li><b>.scale</b>                 - CSS3 - elements scaling</li>
   
   <code>.scale(1.5);</code>
   
   <li><b>.translate</b>             - CSS3 - transform elements (also works on IE9+)</li>
   
   <code>.translate(10, 0);</code>
   
   <li><b>.transition</b>            - CSS3 - transition effects</li>
   
   <code>.transition(all, 0.2s, ease-out, 1s);</code>
   
   <li><b>.animation</b>             - CSS3 - simple add animation (checkout: <http://daneden.me/animate/>)</li>
   
   <code>.animation(fadeOut);</code> or <code>.animation(fadeIn, 0, ease, 2s, 1, normal, running);</code>
   
   <br/>
   <li><b>.columns</b>               - CSS3 - text management</li>
   
   <code>.columns(250, 0, 50, #EEE, solid, 1px);</code>
   
   </ul>