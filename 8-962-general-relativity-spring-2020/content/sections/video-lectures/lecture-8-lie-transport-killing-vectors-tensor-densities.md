---
about_this_resource_text: '<p><strong>Description: </strong>Discussion of a second
  notion of transport, &ldquo;Lie&rdquo; transport, and the associated Lie derivative.  Use
  of this derivative to discuss spacetime symmetries, as encapsulated by Killing vectors.  Also
  discusses &ldquo;tensor densities,&rdquo; volume elements in general spacetimes,
  and certain tricks and identities that use the determinant of the spacetime metric.</p>
  <p><strong>Instructor:</strong> Prof. Scott Hughes</p>'
course_id: 8-962-general-relativity-spring-2020
embedded_media:
- id: Video-YouTube-Stream
  media_location: LoIq6KElVxs
  parent_uid: fead4cb0ce8a3425215bc5e6148fa389
  title: Video-YouTube-Stream
  type: Video
  uid: 3ee4f137f952e294bbf13f09acee7292
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/LoIq6KElVxs/default.jpg
  parent_uid: fead4cb0ce8a3425215bc5e6148fa389
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: bdbbcc71c6de9ebcf68e2bc76bf43e31
- id: 3Play-3PlayYouTubeid-MP4
  media_location: LoIq6KElVxs
  parent_uid: fead4cb0ce8a3425215bc5e6148fa389
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: f0391b375ab5299cfc7e03c3c01f39ef
- id: LoIq6KElVxs.srt
  parent_uid: fead4cb0ce8a3425215bc5e6148fa389
  technical_location: https://ocw.mit.edu/courses/physics/8-962-general-relativity-spring-2020/video-lectures/lecture-8-lie-transport-killing-vectors-tensor-densities/LoIq6KElVxs.srt
  title: 3play caption file
  type: null
  uid: 81570485bd2b63bafb2b8e7ca63f36fa
- id: LoIq6KElVxs.pdf
  parent_uid: fead4cb0ce8a3425215bc5e6148fa389
  technical_location: https://ocw.mit.edu/courses/physics/8-962-general-relativity-spring-2020/video-lectures/lecture-8-lie-transport-killing-vectors-tensor-densities/LoIq6KElVxs.pdf
  title: 3play pdf file
  type: null
  uid: 7134975b380ad0662f0c438be662ab8f
- id: Caption-3Play YouTube id-SRT
  parent_uid: fead4cb0ce8a3425215bc5e6148fa389
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 98b941183b6d3e3b5f4c354b8fe61e0c
- id: Transcript-3Play YouTube id-PDF
  parent_uid: fead4cb0ce8a3425215bc5e6148fa389
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: c2694a7a0c41b108efee6138f73e6503
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT8.962S20/MIT8_962S20_lec08_300k.mp4
  parent_uid: fead4cb0ce8a3425215bc5e6148fa389
  title: Video-Internet Archive-MP4
  type: Video
  uid: a5ed9caaf5efbdeea7d56a496daf6dbc
inline_embed_id: 80849635lecture8lietransportkillingvectorstensordensities6549573
layout: video
order_index: null
parent_uid: 740b8714e79d361c39b23aa6b6a3aaaf
related_resources_text: ''
short_url: lecture-8-lie-transport-killing-vectors-tensor-densities
technical_location: https://ocw.mit.edu/courses/physics/8-962-general-relativity-spring-2020/video-lectures/lecture-8-lie-transport-killing-vectors-tensor-densities
template_type: Tabbed
title: 'Lecture 8: Lie Transport, Killing Vectors, Tensor Densities'
transcript: <p><span m="0">[SQUEAKING]</span></p><p><span m="1464">[RUSTLING]</span></p><p><span
  m="2928">[CLICKING]</span></p><p>&nbsp;</p><p><span m="9760">SCOTT HUGHES:</span>
  <span m="9925">Last</span> <span m="10090">Thursday,</span> <span m="10930">we</span>
  <span m="11080">began</span> <span m="11410">the</span> <span m="11470">work</span>
  <span m="11830">of</span> <span m="11980">moving</span> <span m="12370">from</span>
  <span m="12550">special</span> <span m="12910">relativity</span> <span m="13420">to</span>
  <span m="13750">general</span> <span m="14080">relativity,</span> <span m="15100">and</span>
  <span m="16180">we</span> <span m="16329">spent</span> <span m="16540">a</span>
  <span m="16570">lot</span> <span m="16810">of</span> <span m="16870">time</span>
  <span m="17260">unpacking</span> <span m="17890">two</span> <span m="18160">formulations</span>
  <span m="18910">of</span> <span m="18970">the</span> <span m="19060">principle</span>
  <span m="19390">of</span> <span m="19450">equivalence.</span> <span m="20050">So</span>
  <span m="20350">one,</span> <span m="20680">which</span> <span m="20830">goes</span>
  <span m="21100">under</span> <span m="21490">the</span> <span m="21610">name</span>
  <span m="21930">&quot;weak</span> <span m="22210">equivalence</span> <span m="22690">principle&quot;--</span>
  <span m="24760">a</span> <span m="24820">simpler</span> <span m="25180">way</span>
  <span m="25330">of</span> <span m="25420">saying</span> <span m="25720">that</span>
  <span m="25960">is</span> <span m="26170">that,</span> <span m="26380">at</span>
  <span m="26470">least</span> <span m="26770">over</span> <span m="26980">a</span>
  <span m="27010">sufficiently</span> <span m="27550">small</span> <span m="27910">region,</span>
  <span m="30160">if</span> <span m="30370">there</span> <span m="30670">is</span>
  <span m="30850">nothing</span> <span m="31390">but</span> <span m="31540">gravity</span>
  <span m="32140">acting,</span> <span m="32890">I</span> <span m="33160">cannot</span>
  <span m="34060">distinguish</span> <span m="34960">between</span> <span m="36180">freefall</span>
  <span m="36910">under</span> <span m="37120">the</span> <span m="37240">influence</span>
  <span m="37600">of</span> <span m="37660">gravity</span> <span m="38080">or</span>
  <span m="38210">a</span> <span m="38230">uniform</span> <span m="38680">acceleration.</span>
  <span m="40090">The</span> <span m="40180">two</span> <span m="40360">things</span>
  <span m="40660">are</span> <span m="40750">equivalent</span> <span m="41260">to</span>
  <span m="41350">one</span> <span m="41530">another.</span> <span m="42250">Basically,</span>
  <span m="42850">this</span> <span m="43510">is</span> <span m="43660">a</span> <span
  m="43960">reflection</span> <span m="44470">of</span> <span m="44530">the</span>
  <span m="44590">fact</span> <span m="45040">that</span> <span m="45670">the</span>
  <span m="45760">gravitational</span> <span m="46570">charge</span> <span m="47230">and
  the</span> <span m="47380">inertial</span> <span m="47800">mass</span> <span m="48190">are</span>
  <span m="48280">the</span> <span m="48370">same</span> <span m="48730">thing.</span>
  <span m="49360">That</span> <span m="49510">is</span> <span m="49930">the</span>
  <span m="50050">main</span> <span m="50350">thing</span> <span m="50500">that</span>
  <span m="50620">really</span> <span m="50860">underlies</span> <span m="51550">the</span>
  <span m="52030">weak</span> <span m="52300">equivalence</span> <span m="52750">principle.</span></p><p><span
  m="54160">When</span> <span m="54340">I</span> <span m="54400">gave</span> <span
  m="54640">my</span> <span m="54790">tenure</span> <span m="55150">talk</span> <span
  m="55450">a</span> <span m="55510">number</span> <span m="55840">of</span> <span
  m="55930">years</span> <span m="56230">ago</span> <span m="56470">here,</span> <span
  m="56740">I</span> <span m="57040">pointed</span> <span m="57340">out</span> <span
  m="57520">that</span> <span m="59350">there</span> <span m="59440">was</span> <span
  m="59560">this</span> <span m="59770">wonderful</span> <span m="60160">program</span>
  <span m="60580">called</span> <span m="60760">the</span> <span m="60850">Apollo</span>
  <span m="61210">program</span> <span m="61600">that</span> <span m="61690">was</span>
  <span m="61780">put</span> <span m="61930">together</span> <span m="62230">to</span>
  <span m="62320">test</span> <span m="62590">this.</span> <span m="63220">And</span>
  <span m="63340">the</span> <span m="63400">way</span> <span m="63520">it</span>
  <span m="63580">was</span> <span m="63700">done</span> <span m="63970">was</span>
  <span m="64120">that</span> <span m="64239">they</span> <span m="64360">put</span>
  <span m="64569">astronauts</span> <span m="64989">on</span> <span m="65080">the</span>
  <span m="65140">moon,</span> <span m="65500">and</span> <span m="65590">you</span>
  <span m="65680">actually</span> <span m="65890">show</span> <span m="66160">that,</span>
  <span m="66250">if</span> <span m="66340">you</span> <span m="66400">drop</span>
  <span m="66730">a</span> <span m="66820">hammer</span> <span m="67360">and</span>
  <span m="67510">a</span> <span m="67570">feather</span> <span m="68320">on</span>
  <span m="68500">the</span> <span m="68560">moon,</span> <span m="68920">they</span>
  <span m="69070">fall</span> <span m="69280">at</span> <span m="69370">the</span>
  <span m="69430">same</span> <span m="69670">rate.</span> <span m="70900">Of</span>
  <span m="70990">course,</span> <span m="71830">the</span> <span m="71920">Apollo</span>
  <span m="72220">program</span> <span m="72550">probably</span> <span m="72820">did</span>
  <span m="72910">a</span> <span m="72970">few</span> <span m="73150">other</span>
  <span m="73300">things</span> <span m="73510">as</span> <span m="73630">well.</span>
  <span m="73960">But</span> <span m="74260">I'm</span> <span m="74410">a</span> <span
  m="75330">general</span> <span m="75600">relativity</span> <span m="75910">theorist,</span>
  <span m="76280">so</span> <span m="76360">for</span> <span m="76480">me,</span>
  <span m="76780">that</span> <span m="76960">was</span> <span m="77170">the</span>
  <span m="77260">outcome</span> <span m="77590">of</span> <span m="77650">the</span>
  <span m="77710">Apollo</span> <span m="78010">program,</span> <span m="78430">was</span>
  <span m="78970">test of</span> <span m="79380">the</span> <span m="79600">equivalence</span>
  <span m="79990">principle.</span></p><p><span m="81340">We</span> <span m="81550">also</span>
  <span m="82060">have</span> <span m="82270">a</span> <span m="82360">different</span>
  <span m="82720">variation</span> <span m="83290">of</span> <span m="83350">this</span>
  <span m="83590">we</span> <span m="83740">called</span> <span m="84030">the</span>
  <span m="84220">Einstein</span> <span m="84610">equivalence</span> <span m="85000">principle,</span>
  <span m="85480">which</span> <span m="86740">leads</span> <span m="87040">us</span>
  <span m="87160">to</span> <span m="87280">a</span> <span m="87340">calculation</span>
  <span m="88060">that</span> <span m="88150">we</span> <span m="88240">went</span>
  <span m="88420">through</span> <span m="88600">last</span> <span m="88870">time,</span>
  <span m="89530">which</span> <span m="89830">states</span> <span m="90190">that</span>
  <span m="94510">we</span> <span m="94630">can</span> <span m="94750">find</span>
  <span m="94990">a</span> <span m="95010">representation</span> <span m="95710">over</span>
  <span m="95920">a</span> <span m="95980">sufficiently</span> <span m="96430">small</span>
  <span m="96730">region</span> <span m="96970">of</span> <span m="97070">spacetime</span>
  <span m="98050">such</span> <span m="98320">that</span> <span m="98410">the</span>
  <span m="98500">laws</span> <span m="98920">of</span> <span m="98980">physics are</span>
  <span m="99400">reduced</span> <span m="99880">to</span> <span m="100000">those</span>
  <span m="100420">of</span> <span m="100510">special</span> <span m="100900">relativity.</span>
  <span m="102080">And</span> <span m="102190">we</span> <span m="102340">did</span>
  <span m="102490">a</span> <span m="102520">calculation</span> <span m="103480">to</span>
  <span m="103630">examine</span> <span m="104120">this,</span> <span m="105250">where</span>
  <span m="105490">we</span> <span m="105640">showed,</span> <span m="106720">given</span>
  <span m="109270">an</span> <span m="109420">arbitrary</span> <span m="110530">spacetime</span>
  <span m="111250">metric,</span> <span m="112780">I</span> <span m="112960">can</span>
  <span m="113200">find</span> <span m="113800">a</span> <span m="113860">coordinate</span>
  <span m="114400">system</span> <span m="116950">such</span> <span m="117250">that</span>
  <span m="117490">this</span> <span m="117790">can</span> <span m="117970">be</span>
  <span m="118090">written</span> <span m="118420">in</span> <span m="118510">the</span>
  <span m="118600">form</span> <span m="119740">metric</span> <span m="120070">of</span>
  <span m="120160">flat</span> <span m="120500">spacetime</span> <span m="123090">plus</span>
  <span m="123600">terms</span> <span m="124740">that</span> <span m="125040">are</span>
  <span m="125310">of</span> <span m="125520">order</span> <span m="128350">so we
  have</span> <span m="128430">coordinate</span> <span m="128940">distance</span>
  <span m="129330">squared.</span></p><p><span m="130960">Let's</span> <span m="130979">put</span>
  <span m="131100">it</span> <span m="131160">this</span> <span m="131340">way--</span>
  <span m="131550">so</span> <span m="131800">this,</span> <span m="132630">in</span>
  <span m="132780">the</span> <span m="132870">vicinity</span> <span m="133410">of</span>
  <span m="133560">a</span> <span m="133590">point</span> <span m="133950">pl--</span>
  <span m="134370">I'll</span> <span m="134460">make</span> <span m="134610">that</span>
  <span m="134730">clear</span> <span m="134940">in</span> <span m="135030">just</span>
  <span m="135210">a</span> <span m="135240">moment.</span> <span m="136820">It</span>
  <span m="137310">ends</span> <span m="137490">up</span> <span m="137580">looking</span>
  <span m="137910">like</span> <span m="138320">of</span> <span m="138480">order</span>
  <span m="138900">of coordinate</span> <span m="139320">displacement</span> <span
  m="139830">squared</span> <span m="141300">with</span> <span m="141540">corrections</span>
  <span m="142170">that</span> <span m="142290">scale</span> <span m="142770">as</span>
  <span m="143010">1</span> <span m="143280">over</span> <span m="144630">second</span>
  <span m="145020">derivative</span> <span m="145420">of the</span> <span m="145500">metric.</span>
  <span m="145860">That</span> <span m="146220">sets</span> <span m="146670">the</span>
  <span m="146880">scale</span> <span m="147570">for</span> <span m="147750">what</span>
  <span m="147930">these</span> <span m="148080">end</span> <span m="148170">up</span>
  <span m="148260">looking</span> <span m="148440">like,</span> <span m="148590">or</span>
  <span m="148650">maybe</span> <span m="148860">it's</span> <span m="148950">actually</span>
  <span m="149190">times</span> <span m="149580">that.</span> <span m="149730">Sorry.</span>
  <span m="149870">It's</span> <span m="150030">times</span> <span m="150640">that.</span></p><p><span
  m="153910">Why did I</span> <span m="154530">divide?</span> <span m="155010">I</span>
  <span m="155130">don't</span> <span m="155340">know.</span> <span m="156090">Oh,</span>
  <span m="156210">I</span> <span m="156270">know</span> <span m="156420">why,</span>
  <span m="156780">because I</span> <span m="156870">wanted</span> <span m="157050">to</span>
  <span m="157110">point</span> <span m="157350">out</span> <span m="157500">that</span>
  <span m="157620">that</span> <span m="157830">is</span> <span m="157950">what</span>
  <span m="158100">the</span> <span m="158220">scale</span> <span m="158730">of</span>
  <span m="159225">1</span> <span m="159720">over</span> <span m="160050">this</span>
  <span m="160290">thing--</span> <span m="160900">for</span> <span m="160970">God's</span>
  <span m="161170">sake,</span> <span m="161490">Scott!</span> <span m="162270">Stop</span>
  <span m="162570">putting</span> <span m="162750">your</span> <span m="162840">square</span>
  <span m="163050">roots</span> <span m="163210">in</span> <span m="163250">there!</span>
  <span m="163980">So</span> <span m="164310">it</span> <span m="164430">looks</span>
  <span m="165390">like</span> <span m="165600">that.</span></p><p><span m="166060">And</span>
  <span m="166170">so</span> <span m="166560">this</span> <span m="166710">is</span>
  <span m="166770">what</span> <span m="166890">I</span> <span m="166920">was</span>
  <span m="167010">saying.</span> <span m="168060">You</span> <span m="168210">have</span>
  <span m="168480">a</span> <span m="168630">curvature</span> <span m="169230">scale</span>
  <span m="173450">that</span> <span m="173660">is</span> <span m="173900">on</span>
  <span m="174110">the</span> <span m="174200">order</span> <span m="174590">of</span>
  <span m="178980">square</span> <span m="179220">root</span> <span m="179310">of</span>
  <span m="179580">1</span> <span m="179640">over the second</span> <span m="179870">derivative</span>
  <span m="180000">of</span> <span m="180070">the</span> <span m="180150">metric.</span>
  <span m="180470">Apologies</span> <span m="180870">for</span> <span m="180990">botching</span>
  <span m="181350">that</span> <span m="181500">as</span> <span m="181620">I</span>
  <span m="181650">was</span> <span m="181770">writing</span> <span m="181990">it</span>
  <span m="182070">up</span> <span m="182160">there</span> <span m="182280">quickly.</span></p><p><span
  m="183460">OK,</span> <span m="183690">so</span> <span m="183810">we</span> <span
  m="183870">did</span> <span m="183990">a</span> <span m="184050">calculation</span>
  <span m="184620">that</span> <span m="184740">shows</span> <span m="185040">that.</span>
  <span m="185240">And</span> <span m="185310">indeed,</span> <span m="185910">what</span>
  <span m="186000">we</span> <span m="186090">did</span> <span m="186210">is</span>
  <span m="186300">we</span> <span m="186390">went</span> <span m="186540">through</span>
  <span m="186750">and</span> <span m="186840">we</span> <span m="186960">showed</span>
  <span m="187230">that</span> <span m="188100">a</span> <span m="188190">general</span>
  <span m="188520">coordinate</span> <span m="188870">transformation</span> <span
  m="189510">has</span> <span m="189720">more</span> <span m="190200">than</span>
  <span m="190320">enough</span> <span m="190560">degrees</span> <span m="190920">of</span>
  <span m="190980">freedom</span> <span m="191760">to</span> <span m="191940">make</span>
  <span m="192180">the</span> <span m="192240">metric</span> <span m="193200">flat</span>
  <span m="194010">to</span> <span m="194130">get</span> <span m="194310">the</span>
  <span m="194400">flat</span> <span m="194730">spacetime</span> <span m="195210">metric</span>
  <span m="195600">at</span> <span m="195780">a</span> <span m="195810">particular</span>
  <span m="196200">point.</span> <span m="196890">And</span> <span m="197010">in</span>
  <span m="197100">fact,</span> <span m="197400">there</span> <span m="197610">are</span>
  <span m="197730">six</span> <span m="198090">degrees</span> <span m="198420">of</span>
  <span m="198480">freedom</span> <span m="198810">left</span> <span m="199080">over,</span>
  <span m="199410">corresponding</span> <span m="200160">to</span> <span m="201570">six</span>
  <span m="201870">rotations</span> <span m="202530">and</span> <span m="202620">six</span>
  <span m="202950">boosts</span> <span m="203820">that are</span> <span m="203970">allowable</span>
  <span m="204530">at</span> <span m="204690">that</span> <span m="204870">particular</span>
  <span m="205260">point</span> <span m="205590">or</span> <span m="205770">event.</span>
  <span m="206490">Bear</span> <span m="206640">in</span> <span m="206700">mind</span>
  <span m="206940">we're</span> <span m="207030">working</span> <span m="207240">in</span>
  <span m="207330">spacetime.</span></p><p><span m="209610">We</span> <span m="209820">have</span>
  <span m="210060">exactly</span> <span m="210810">enough</span> <span m="211170">degrees</span>
  <span m="211530">of</span> <span m="211590">freedom</span> <span m="211920">to</span>
  <span m="212010">cancel</span> <span m="212460">out</span> <span m="212640">the</span>
  <span m="212760">first</span> <span m="213150">order</span> <span m="213360">term,</span>
  <span m="214290">but</span> <span m="214500">we</span> <span m="214710">cannot</span>
  <span m="215310">cancel</span> <span m="215760">out</span> <span m="215940">the</span>
  <span m="216030">second</span> <span m="216360">order</span> <span m="216540">term.</span>
  <span m="217320">And</span> <span m="217350">in</span> <span m="217410">fact,</span>
  <span m="217810">we</span> <span m="217830">find</span> <span m="218130">there</span>
  <span m="218280">are</span> <span m="218400">20</span> <span m="218730">degrees</span>
  <span m="219030">of</span> <span m="219090">freedom</span> <span m="219390">left</span>
  <span m="219630">over.</span> <span m="220380">And</span> <span m="220590">in</span>
  <span m="220710">a</span> <span m="220740">future</span> <span m="221790">lecture,</span>
  <span m="222180">we</span> <span m="222330">will</span> <span m="222420">derive</span>
  <span m="222780">a</span> <span m="222840">geometric</span> <span m="223290">object</span>
  <span m="223770">that</span> <span m="223980">characterizes</span> <span m="225510">the</span>
  <span m="225600">curvature</span> <span m="226140">that</span> <span m="226260">has</span>
  <span m="226500">indeed</span> <span m="226860">20</span> <span m="227130">degrees</span>
  <span m="227400">of</span> <span m="227460">freedom</span> <span m="227730">in</span>
  <span m="227820">it</span> <span m="227970">or 20</span> <span m="228960">independent</span>
  <span m="229410">components</span> <span m="229980">that</span> <span m="230070">come</span>
  <span m="230250">out</span> <span m="230370">of</span> <span m="230430">it.</span></p><p><span
  m="231760">So</span> <span m="231810">this</span> <span m="231960">is</span> <span
  m="232290">the</span> <span m="232350">foundation</span> <span m="232950">of</span>
  <span m="233040">where</span> <span m="233220">we're</span> <span m="233310">moving</span>
  <span m="233580">forward.</span> <span m="233990">And</span> <span m="234090">so</span>
  <span m="236040">what</span> <span m="236190">this</span> <span m="236340">basically</span>
  <span m="236670">tells</span> <span m="237060">us</span> <span m="237390">is</span>
  <span m="237690">that,</span> <span m="237840">in</span> <span m="237930">a</span>
  <span m="237990">spacetime</span> <span m="238530">like</span> <span m="238740">this,</span>
  <span m="240360">we</span> <span m="240540">have</span> <span m="240780">what</span>
  <span m="240870">we</span> <span m="240960">call</span> <span m="241140">curvature.</span>
  <span m="242130">Trajectories</span> <span m="242790">that</span> <span m="242910">start</span>
  <span m="243300">out</span> <span m="243780">parallel</span> <span m="244260">to</span>
  <span m="244350">one</span> <span m="244500">another</span> <span m="244800">are</span>
  <span m="244920">not</span> <span m="245160">going</span> <span m="245340">to</span>
  <span m="245430">remain</span> <span m="245820">parallel</span> <span m="246330">as</span>
  <span m="246510">they</span> <span m="246630">move</span> <span m="246840">forward.</span>
  <span m="247800">And</span> <span m="247980">where</span> <span m="248160">we</span>
  <span m="248310">concluded</span> <span m="248910">last</span> <span m="249210">time,</span>
  <span m="250230">we</span> <span m="250470">were</span> <span m="250590">dealing</span>
  <span m="250950">with</span> <span m="251100">the</span> <span m="251160">problem</span>
  <span m="251730">that,</span> <span m="252030">if</span> <span m="252240">I</span>
  <span m="252480">want</span> <span m="252810">to</span> <span m="253200">take</span>
  <span m="253530">derivatives--</span> <span m="254236">and</span> <span m="254590">we're</span>
  <span m="254690">going</span> <span m="254700">to</span> <span m="254760">start</span>
  <span m="254970">with</span> <span m="255090">vector</span> <span m="255420">field.</span>
  <span m="255790">If</span> <span m="255890">I</span> <span m="255990">want</span>
  <span m="256050">to</span> <span m="256140">differentiate</span> <span m="256890">a</span>
  <span m="256950">vector</span> <span m="257399">field</span> <span m="258209">on</span>
  <span m="258390">a</span> <span m="258450">curved</span> <span m="258899">manifold,</span>
  <span m="260550">it</span> <span m="260700">doesn't</span> <span m="261000">work.</span>
  <span m="261839">If</span> <span m="261990">I</span> <span m="262079">do</span>
  <span m="262290">the</span> <span m="262380">naive</span> <span m="262860">thing</span>
  <span m="263100">of</span> <span m="263190">just</span> <span m="263400">taking</span>
  <span m="263730">a</span> <span m="263760">partial</span> <span m="264090">derivative,</span>
  <span m="264570">it</span> <span m="264660">does</span> <span m="264960">not</span>
  <span m="265200">work.</span></p><p><span m="266070">So</span> <span m="266220">I'll</span>
  <span m="266280">remind</span> <span m="266610">you</span> <span m="266730">where</span>
  <span m="266880">we</span> <span m="267030">left</span> <span m="267420">off.</span>
  <span m="279760">So</span> <span m="279800">we</span> <span m="279920">found</span>
  <span m="280220">partial</span> <span m="280730">derivatives</span> <span m="287300">of</span>
  <span m="287570">vectors.</span> <span m="287855">Let me</span> <span m="288350">put
  that</span> <span m="288680">in</span> <span m="288770">there.</span> <span m="289180">Partial</span>
  <span m="289670">derivatives of</span> <span m="289830">vectors,</span> <span m="290420">and
  it</span> <span m="290900">won't</span> <span m="291110">take</span> <span m="291260">much</span>
  <span m="291470">work</span> <span m="291650">to</span> <span m="291740">show</span>
  <span m="291890">it's</span> <span m="291980">true</span> <span m="292160">for</span>
  <span m="292280">one</span> <span m="292490">forms</span> <span m="292790">or</span>
  <span m="292880">any</span> <span m="293120">tensor,</span> <span m="293490">so</span>
  <span m="293620">let's</span> <span m="293810">say,</span> <span m="294020">partial</span>
  <span m="294380">derivatives</span> <span m="295550">of</span> <span m="295640">tensors</span>
  <span m="299810">do</span> <span m="299990">not</span> <span m="300230">yield</span>
  <span m="300810">tensors.</span> <span m="306160">We're</span> <span m="306510">familiar</span>
  <span m="306900">with</span> <span m="307020">this</span> <span m="307200">to</span>
  <span m="307290">some</span> <span m="307470">extent</span> <span m="307800">because</span>
  <span m="308040">we</span> <span m="308160">already</span> <span m="308430">encountered</span>
  <span m="308940">this</span> <span m="309120">when we</span> <span m="309240">began</span>
  <span m="309540">thinking</span> <span m="309900">about</span> <span m="310110">the</span>
  <span m="310170">behavior</span> <span m="311400">of,</span> <span m="311670">even</span>
  <span m="311920">in</span> <span m="312000">flat</span> <span m="312330">spacetime,</span>
  <span m="312960">flat</span> <span m="313230">spacetime</span> <span m="313680">and</span>
  <span m="313770">curvilinear</span> <span m="314280">coordinates.</span> <span m="314850">So
  that's</span> <span m="315030">the</span> <span m="315120">fact</span> <span m="315390">that
  the</span> <span m="315480">basis</span> <span m="315930">objects</span> <span m="316260">themselves</span>
  <span m="316740">have</span> <span m="316830">some</span> <span m="317010">functional</span>
  <span m="317400">dependence</span> <span m="317820">associated</span> <span m="318300">with</span>
  <span m="318450">them.</span></p><p><span m="319170">We're</span> <span m="319320">interpreting</span>
  <span m="319800">it</span> <span m="319980">a</span> <span m="320040">little</span>
  <span m="320430">bit</span> <span m="320610">differently</span> <span m="321210">now.</span>
  <span m="321900">And</span> <span m="322080">so</span> <span m="322230">what</span>
  <span m="322380">we're</span> <span m="322530">doing</span> <span m="323010">is</span>
  <span m="323370">we're</span> <span m="323520">going</span> <span m="323630">to</span>
  <span m="323700">say</span> <span m="323940">that</span> <span m="324090">what's</span>
  <span m="324240">going</span> <span m="324510">on</span> <span m="324690">here</span>
  <span m="324930">is</span> <span m="325030">that,</span> <span m="325140">on</span>
  <span m="325200">my</span> <span m="325320">curved</span> <span m="325650">manifold--</span>
  <span m="326130">and</span> <span m="326220">I</span> <span m="326520">want</span>
  <span m="326640">you</span> <span m="326730">to</span> <span m="326790">visualize</span>
  <span m="327270">something</span> <span m="327630">that's</span> <span m="327780">like</span>
  <span m="328020">a</span> <span m="329220">bumpy</span> <span m="329580">surface</span>
  <span m="330000">or,</span> <span m="330060">if</span> <span m="330120">you</span>
  <span m="330180">like,</span> <span m="330360">maybe</span> <span m="330600">a</span>
  <span m="330630">sphere.</span> <span m="332410">Think</span> <span m="332700">about</span>
  <span m="333060">if</span> <span m="333240">you</span> <span m="333420">are</span>
  <span m="333510">a</span> <span m="333570">two-dimensional</span> <span m="334140">being</span>
  <span m="334470">confined</span> <span m="334950">to</span> <span m="335070">the</span>
  <span m="335160">surface</span> <span m="335520">of</span> <span m="335610">a</span>
  <span m="335640">sphere.</span> <span m="336450">There's</span> <span m="336660">only</span>
  <span m="336870">two</span> <span m="337080">directions</span> <span m="337560">at</span>
  <span m="337650">any</span> <span m="337800">given</span> <span m="338010">point.</span>
  <span m="338490">You</span> <span m="338580">can</span> <span m="339030">go</span>
  <span m="339930">up,</span> <span m="340200">or</span> <span m="340740">you</span>
  <span m="340860">can</span> <span m="341010">go</span> <span m="341100">on</span>
  <span m="341170">the</span> <span m="341250">left-right</span> <span m="341760">axis</span>
  <span m="342270">or</span> <span m="342360">the</span> <span m="342480">north-south</span>
  <span m="343110">axis,</span> <span m="343500">right?</span> <span m="344540">And</span>
  <span m="344640">you</span> <span m="344740">would</span> <span m="344820">define</span>
  <span m="345720">unit</span> <span m="346050">vectors</span> <span m="346410">pointing</span>
  <span m="346770">along</span> <span m="347130">there.</span></p><p><span m="348070">But</span>
  <span m="348210">as</span> <span m="348360">you</span> <span m="348480">move</span>
  <span m="348780">around</span> <span m="349080">that</span> <span m="349230">sphere,</span>
  <span m="350040">those</span> <span m="350880">of</span> <span m="350970">us</span>
  <span m="351180">who</span> <span m="351330">have</span> <span m="351480">a</span>
  <span m="351510">three-dimensional</span> <span m="352200">life,</span> <span m="352500">and</span>
  <span m="352590">can</span> <span m="352950">step</span> <span m="353250">back</span>
  <span m="353490">and</span> <span m="353610">see</span> <span m="353880">this,</span>
  <span m="354570">we</span> <span m="354780">see</span> <span m="355110">that</span>
  <span m="356520">these</span> <span m="356700">basis</span> <span m="357150">objects</span>
  <span m="357510">point</span> <span m="357840">in</span> <span m="357930">different</span>
  <span m="358170">directions</span> <span m="358650">at</span> <span m="358710">different</span>
  <span m="359040">locations</span> <span m="359670">on</span> <span m="359820">the</span>
  <span m="359880">sphere.</span> <span m="360780">The</span> <span m="360900">two-dimensional</span>
  <span m="361590">beings</span> <span m="361980">aren't</span> <span m="362190">aware</span>
  <span m="362430">of</span> <span m="362520">that.</span> <span m="362730">They</span>
  <span m="362850">just</span> <span m="362970">know</span> <span m="363120">that</span>
  <span m="363240">they're</span> <span m="363330">on</span> <span m="363390">a</span>
  <span m="363420">surface</span> <span m="363780">that's</span> <span m="363930">curved.</span>
  <span m="364920">And</span> <span m="365130">so</span> <span m="365370">they</span>
  <span m="365550">would</span> <span m="365700">say</span> <span m="366270">that</span>
  <span m="366450">the</span> <span m="366540">tangent</span> <span m="367140">space</span>
  <span m="367650">is</span> <span m="367830">different</span> <span m="368190">for</span>
  <span m="368340">all</span> <span m="368460">these</span> <span m="368670">objects.</span>
  <span m="369270">They've</span> <span m="369690">imagined</span> <span m="370140">that</span>
  <span m="370320">every</span> <span m="370590">one</span> <span m="370770">of</span>
  <span m="370830">these</span> <span m="370980">basis</span> <span m="371340">objects</span>
  <span m="371700">lives</span> <span m="371940">in</span> <span m="372330">a</span>
  <span m="372450">plane</span> <span m="372900">that</span> <span m="373020">is</span>
  <span m="373140">tangent</span> <span m="373650">to</span> <span m="373800">the</span>
  <span m="373890">sphere</span> <span m="374220">at</span> <span m="374280">any</span>
  <span m="374460">given</span> <span m="374700">point,</span> <span m="375510">and</span>
  <span m="375630">that</span> <span m="375810">plane</span> <span m="376290">is</span>
  <span m="376440">different</span> <span m="376740">at</span> <span m="376830">every</span>
  <span m="377010">point</span> <span m="377330">along</span> <span m="377490">the</span>
  <span m="377580">sphere.</span> <span m="378550">So</span> <span m="378600">we</span>
  <span m="378720">interpret</span> <span m="379080">this</span> <span m="379260">by</span>
  <span m="379440">saying</span> <span m="379800">that</span> <span m="379980">all</span>
  <span m="380220">of</span> <span m="380370">our</span> <span m="380880">basis</span>
  <span m="381330">objects</span> <span m="381750">live</span> <span m="382050">in</span>
  <span m="382170">this</span> <span m="382320">tangent</span> <span m="382740">space,</span>
  <span m="383130">and</span> <span m="383220">the</span> <span m="383280">tangent</span>
  <span m="383730">space</span> <span m="384060">is</span> <span m="384210">different</span>
  <span m="384660">at</span> <span m="384750">every</span> <span m="384960">point</span>
  <span m="385890">on</span> <span m="386010">the</span> <span m="386100">surface.</span></p><p><span
  m="389250">So</span> <span m="392150">let</span> <span m="392240">me</span> <span
  m="392330">just</span> <span m="392450">write</span> <span m="392690">out</span>
  <span m="392840">one</span> <span m="393020">equation</span> <span m="393530">here.</span>
  <span m="394490">So</span> <span m="395660">when</span> <span m="395840">we</span>
  <span m="396010">looked</span> <span m="396350">at</span> <span m="396530">the</span>
  <span m="396620">transformation</span> <span m="399050">of</span> <span m="399170">a</span>
  <span m="399200">partial</span> <span m="399590">derivative</span> <span m="400160">of</span>
  <span m="400310">a</span> <span m="400370">vector,</span> <span m="400940">if</span>
  <span m="401030">we</span> <span m="401090">looked</span> <span m="401290">at</span>
  <span m="403190">just</span> <span m="403540">the</span> <span m="403610">components--</span>
  <span m="411160">so</span> <span m="411420">this</span> <span m="411570">calculation</span>
  <span m="412110">is</span> <span m="412260">in</span> <span m="412350">the</span>
  <span m="412410">notes,</span> <span m="412660">so</span> <span m="412800">I</span>
  <span m="412890">would</span> <span m="413010">just</span> <span m="413190">write</span>
  <span m="413460">down</span> <span m="413670">the</span> <span m="413790">result.</span>
  <span m="415140">What</span> <span m="415290">we</span> <span m="415440">found</span>
  <span m="418370">was</span> <span m="418730">that,</span> <span m="418910">if</span>
  <span m="419120">I'm</span> <span m="419330">taking,</span> <span m="419720">say,</span>
  <span m="419960">the</span> <span m="420080">beta</span> <span m="420440">derivative</span>
  <span m="422060">of</span> <span m="422540">component</span> <span m="423320">A</span>
  <span m="423560">alpha,</span> <span m="444200">what</span> <span m="444320">I</span>
  <span m="444380">found</span> <span m="444760">when</span> <span m="444830">I</span>
  <span m="444890">want</span> <span m="445130">to</span> <span m="445190">go</span>
  <span m="445330">into</span> <span m="445540">a</span> <span m="445580">coordinate</span>
  <span m="445910">transformation</span> <span m="447350">is</span> <span m="447560">that</span>
  <span m="447740">there's</span> <span m="447950">an</span> <span m="448040">extra</span>
  <span m="448400">term</span> <span m="450410">that</span> <span m="450590">ruins</span>
  <span m="451130">the</span> <span m="451220">tensoriality</span> <span m="452030">of</span>
  <span m="452150">this.</span> <span m="456570">So</span> <span m="456720">this</span>
  <span m="456900">goes</span> <span m="457290">over</span> <span m="457680">to</span>
  <span m="457800">something</span> <span m="458250">that</span> <span m="458400">looks</span>
  <span m="458670">like--</span></p><p><span m="489490">So</span> <span m="489610">the</span>
  <span m="489700">first</span> <span m="490000">term</span> <span m="490420">is</span>
  <span m="490570">what</span> <span m="490720">we'd</span> <span m="490840">expect</span>
  <span m="491440">if</span> <span m="491650">this</span> <span m="491860">were</span>
  <span m="492460">a</span> <span m="492550">tensor</span> <span m="492910">relationship.</span>
  <span m="493840">That's</span> <span m="494050">exactly</span> <span m="494680">the</span>
  <span m="494770">matrix</span> <span m="495940">of</span> <span m="496600">the</span>
  <span m="496700">Jacobian</span> <span m="497170">between</span> <span m="497530">two</span>
  <span m="497680">different</span> <span m="497920">coordinate</span> <span m="498310">representations</span>
  <span m="499060">that</span> <span m="499150">we</span> <span m="499300">expect</span>
  <span m="499810">to</span> <span m="499930">describe</span> <span m="501400">how</span>
  <span m="501790">components</span> <span m="502360">change</span> <span m="502810">if</span>
  <span m="502900">they</span> <span m="503020">indeed</span> <span m="503320">obey</span>
  <span m="503560">a tensorial</span> <span m="504070">relationship.</span> <span
  m="505180">This</span> <span m="505510">extra</span> <span m="505870">thing</span>
  <span m="506110">here</span> <span m="506350">I</span> <span m="506410">wrote</span>
  <span m="506560">on</span> <span m="506650">the</span> <span m="506710">second</span>
  <span m="507070">line--</span> <span m="507370">that</span> <span m="507640">is</span>
  <span m="507820">spoiling</span> <span m="508390">it</span> <span m="508450">for</span>
  <span m="508690">us.</span></p><p><span m="510430">So</span> <span m="510670">I</span>
  <span m="510790">began</span> <span m="511120">to</span> <span m="511210">give</span>
  <span m="511390">you</span> <span m="511480">the</span> <span m="511570">physical</span>
  <span m="511960">notion</span> <span m="512440">of</span> <span m="512559">what</span>
  <span m="512740">we</span> <span m="512840">were</span> <span m="512950">going</span>
  <span m="513250">to</span> <span m="513340">do</span> <span m="513760">to</span>
  <span m="513909">fix</span> <span m="514240">this.</span> <span m="514470">So</span>
  <span m="514539">let</span> <span m="514659">me</span> <span m="514750">just</span>
  <span m="514990">reset</span> <span m="515440">that</span> <span m="515590">up</span>
  <span m="515710">again.</span> <span m="516650">So</span> <span m="516669">let's</span>
  <span m="516820">imagine</span> <span m="517390">I</span> <span m="517539">have</span>
  <span m="517630">a</span> <span m="517690">particular</span> <span m="518799">curve</span>
  <span m="520480">that</span> <span m="520809">goes</span> <span m="521350">along</span>
  <span m="521770">my</span> <span m="521950">manifold.</span> <span m="524470">I</span>
  <span m="524560">have</span> <span m="524650">a</span> <span m="524710">point</span>
  <span m="525040">P</span> <span m="525460">here</span> <span m="525790">on</span>
  <span m="525910">the</span> <span m="525970">curve,</span> <span m="527860">and</span>
  <span m="528430">I</span> <span m="528500">have</span> <span m="528580">a</span>
  <span m="528640">point</span> <span m="529060">Q</span> <span m="530080">over</span>
  <span m="530380">here.</span> <span m="530920">And let's</span> <span m="531100">say</span>
  <span m="531250">that</span> <span m="531400">P</span> <span m="532570">is</span>
  <span m="532720">at</span> <span m="532870">event</span> <span m="533680">x</span>
  <span m="533950">alpha.</span> <span m="535000">Q</span> <span m="536500">is</span>
  <span m="536740">at</span> <span m="536980">x</span> <span m="537250">alpha</span>
  <span m="538960">plus</span> <span m="539170">dx</span> <span m="539620">alpha.</span></p><p><span
  m="546870">Here's</span> <span m="547130">my</span> <span m="547310">vector</span>
  <span m="547880">A</span> <span m="550570">at</span> <span m="550720">the</span>
  <span m="550870">event</span> <span m="551140">Q.</span> <span m="552580">And</span>
  <span m="553330">here's</span> <span m="555420">my</span> <span m="555520">vector</span>
  <span m="555850">A</span> <span m="556140">at</span> <span m="556300">the</span>
  <span m="556480">event</span> <span m="557080">P.</span> <span m="559480">So</span>
  <span m="560040">what</span> <span m="560640">we</span> <span m="560890">discussed</span>
  <span m="561250">last</span> <span m="561520">time</span> <span m="561820">is</span>
  <span m="561910">that,</span> <span m="562030">to</span> <span m="562150">get</span>
  <span m="562360">this</span> <span m="562570">thing,</span> <span m="562780">I'm</span>
  <span m="562840">just</span> <span m="562960">doing</span> <span m="563140">the</span>
  <span m="563200">normal</span> <span m="563500">partial</span> <span m="563830">derivative.</span>
  <span m="564250">I'm</span> <span m="564430">basically</span> <span m="566380">imagining</span>
  <span m="566740">that</span> <span m="566830">these</span> <span m="567040">are</span>
  <span m="567100">close</span> <span m="567460">to</span> <span m="567550">one</span>
  <span m="567700">another,</span> <span m="568030">that</span> <span m="568270">I</span>
  <span m="568390">can</span> <span m="568570">just</span> <span m="569230">subtract</span>
  <span m="570560">A</span> <span m="570840">at</span> <span m="571240">Q</span> <span
  m="571840">from</span> <span m="572080">A</span> <span m="572320">at</span> <span
  m="572440">P,</span> <span m="573250">divide</span> <span m="573670">by</span> <span
  m="573880">dx</span> <span m="574450">and</span> <span m="574570">take</span> <span
  m="574750">the</span> <span m="574840">limit.</span> <span m="575110">That's</span>
  <span m="575320">the</span> <span m="575440">definition</span> <span m="576130">of</span>
  <span m="576250">a</span> <span m="576310">derivative.</span> <span m="577630">And</span>
  <span m="577870">what</span> <span m="578050">this</span> <span m="578170">is</span>
  <span m="578230">telling</span> <span m="578560">us</span> <span m="578680">is,</span>
  <span m="579400">mathematically,</span> <span m="580090">yeah,</span> <span m="580360">it's</span>
  <span m="580480">a</span> <span m="580510">derivative,</span> <span m="581350">but</span>
  <span m="581530">it's</span> <span m="581650">not</span> <span m="582010">a</span>
  <span m="582070">derivative</span> <span m="582580">that</span> <span m="582730">yields</span>
  <span m="583270">a</span> <span m="583390">tensor</span> <span m="583780">quantity.</span>
  <span m="584830">And</span> <span m="584980">so</span> <span m="585490">we are</span>
  <span m="585750">beginning</span> <span m="586030">to</span> <span m="586120">discuss</span>
  <span m="586510">the</span> <span m="586600">fact</span> <span m="586930">that,</span>
  <span m="587080">to</span> <span m="587200">compare</span> <span m="587740">things</span>
  <span m="588160">that</span> <span m="588340">have</span> <span m="588550">different</span>
  <span m="588850">tangent</span> <span m="589270">spaces,</span> <span m="589750">that</span>
  <span m="589930">live</span> <span m="590260">in</span> <span m="590350">different</span>
  <span m="590650">points</span> <span m="591010">in</span> <span m="591100">my</span>
  <span m="591220">curve</span> <span m="591520">manifold,</span> <span m="592450">I</span>
  <span m="592540">need</span> <span m="592720">a</span> <span m="592780">notion</span>
  <span m="593080">of</span> <span m="593170">transport</span> <span m="593890">to</span>
  <span m="593980">take</span> <span m="594220">one</span> <span m="594490">from</span>
  <span m="594640">the</span> <span m="594760">other</span> <span m="595080">in</span>
  <span m="595210">order</span> <span m="595360">to</span> <span m="595450">compare</span>
  <span m="595840">them.</span></p><p><span m="596720">So</span> <span m="596800">there</span>
  <span m="596980">are</span> <span m="597100">two</span> <span m="597490">notions</span>
  <span m="597940">of</span> <span m="598000">transport</span> <span m="598540">that</span>
  <span m="598630">we're</span> <span m="598720">going</span> <span m="598850">to</span>
  <span m="598930">talk</span> <span m="599200">about</span> <span m="599440">here.</span>
  <span m="600620">The</span> <span m="600640">first</span> <span m="601150">one</span>
  <span m="602790">is</span> <span m="602970">called</span> <span m="603240">parallel</span>
  <span m="603750">transport.</span> <span m="604920">So</span> <span m="605370">transport</span>
  <span m="606090">notion</span> <span m="606540">one--</span> <span m="620400">we</span>
  <span m="620520">call</span> <span m="620730">this</span> <span m="620880">parallel</span>
  <span m="621300">transport.</span> <span m="623160">I'm</span> <span m="623340">going</span>
  <span m="623580">to</span> <span m="624000">actually</span> <span m="624510">focus</span>
  <span m="624900">a</span> <span m="624930">little</span> <span m="625080">bit</span>
  <span m="625230">on</span> <span m="625350">the</span> <span m="625440">math</span>
  <span m="625860">first</span> <span m="626820">and</span> <span m="626940">then</span>
  <span m="627090">come</span> <span m="627300">back</span> <span m="627540">to</span>
  <span m="628200">what</span> <span m="628380">is</span> <span m="628470">parallel</span>
  <span m="629190">about</span> <span m="629490">this</span> <span m="630150">afterwards.</span></p><p><span
  m="636610">So</span> <span m="636630">what</span> <span m="636750">I</span> <span
  m="636870">essentially</span> <span m="637290">need</span> <span m="637470">to</span>
  <span m="637590">do</span> <span m="638580">is</span> <span m="639000">say,</span>
  <span m="639510">what</span> <span m="639660">I</span> <span m="639720">want</span>
  <span m="639900">to</span> <span m="639990">do</span> <span m="640140">is</span>
  <span m="640260">find</span> <span m="640590">some</span> <span m="640860">kind</span>
  <span m="641130">of</span> <span m="641190">a</span> <span m="641250">way</span>
  <span m="641520">of</span> <span m="641670">imagining</span> <span m="642690">that</span>
  <span m="642840">I</span> <span m="642960">take</span> <span m="643320">the</span>
  <span m="643410">vector</span> <span m="644310">at</span> <span m="644490">P</span>
  <span m="645450">and</span> <span m="645720">transport</span> <span m="646360">it</span>
  <span m="646440">over</span> <span m="646800">to</span> <span m="646920">the</span>
  <span m="647010">point</span> <span m="647340">Q,</span> <span m="648600">and</span>
  <span m="648870">I</span> <span m="649080">will</span> <span m="649770">compare</span>
  <span m="650460">the</span> <span m="650640">transported</span> <span m="651660">object</span>
  <span m="652080">rather</span> <span m="652350">than</span> <span m="652470">the</span>
  <span m="652590">object</span> <span m="652900">originally</span> <span m="653310">at</span>
  <span m="653490">point</span> <span m="653820">P.</span> <span m="681240">Abstractly,</span>
  <span m="682290">what</span> <span m="682440">I'm</span> <span m="682530">essentially</span>
  <span m="682950">going to</span> <span m="683040">do</span> <span m="683250">is</span>
  <span m="683360">I'm going</span> <span m="683480">to</span> <span m="683550">do</span>
  <span m="683700">what</span> <span m="683790">we</span> <span m="683910">always</span>
  <span m="684210">do</span> <span m="684360">in this.</span> <span m="684620">I'm</span>
  <span m="684690">going</span> <span m="684810">to</span> <span m="684900">imagine</span>
  <span m="685470">that</span> <span m="685830">there</span> <span m="686100">is</span>
  <span m="686220">some</span> <span m="686430">kind</span> <span m="686730">of</span>
  <span m="686790">an</span> <span m="686880">operation</span> <span m="688050">that</span>
  <span m="688200">is</span> <span m="688380">linear</span> <span m="689070">in</span>
  <span m="689190">the</span> <span m="689250">separation</span> <span m="689790">between</span>
  <span m="690060">the</span> <span m="690120">two</span> <span m="690300">of</span>
  <span m="690360">them</span> <span m="690870">that</span> <span m="691020">allows</span>
  <span m="691410">me</span> <span m="691530">to</span> <span m="691650">define</span>
  <span m="692340">this</span> <span m="692490">transport.</span></p><p><span m="695020">So</span>
  <span m="695100">let's</span> <span m="695310">do</span> <span m="695520">the</span>
  <span m="695610">following.</span> <span m="703570">So</span> <span m="703680">I'm</span>
  <span m="703830">going</span> <span m="703950">to</span> <span m="704400">assume</span>
  <span m="704850">that</span> <span m="707940">we</span> <span m="708030">can</span>
  <span m="708180">define</span> <span m="708630">an</span> <span m="708870">object,</span>
  <span m="711510">which</span> <span m="711690">I</span> <span m="711780">will</span>
  <span m="711900">call</span> <span m="712500">Pi,</span> <span m="713160">capital</span>
  <span m="713700">Pi,</span> <span m="715600">alpha,</span> <span m="716020">beta,</span>
  <span m="716060">mu,</span> <span m="725180">which</span> <span m="725300">is</span>
  <span m="725390">going</span> <span m="725500">to</span> <span m="725600">do</span>
  <span m="725720">the</span> <span m="725780">following.</span> <span m="726410">So
  what I'm</span> <span m="726510">going</span> <span m="726610">to</span> <span m="726710">do</span>
  <span m="726830">is</span> <span m="727040">say</span> <span m="727370">that</span>
  <span m="729470">A</span> <span m="730750">alpha</span> <span m="731600">transported--</span>
  <span m="732590">and</span> <span m="732710">to</span> <span m="732800">make</span>
  <span m="732950">it</span> <span m="733010">even</span> <span m="733190">clearer,</span>
  <span m="733550">how</span> <span m="733730">it's</span> <span m="733820">being</span>
  <span m="734030">transported.</span> <span m="734540">Let's</span> <span m="734690">say</span>
  <span m="734810">it's</span> <span m="734960">being</span> <span m="735110">transported</span>
  <span m="736310">from</span> <span m="736640">P</span> <span m="736940">to</span>
  <span m="737060">Q.</span> <span m="741480">This</span> <span m="741660">is</span>
  <span m="741780">given</span> <span m="742080">by</span> <span m="743880">alpha</span>
  <span m="744240">at</span> <span m="744390">P,</span> <span m="745250">and</span>
  <span m="745380">what</span> <span m="745470">I'm</span> <span m="745560">going</span>
  <span m="745670">to</span> <span m="745740">do</span> <span m="746040">is</span>
  <span m="746190">say</span> <span m="746400">that,</span> <span m="746550">whatever</span>
  <span m="747030">this</span> <span m="747240">object</span> <span m="747720">is,</span>
  <span m="750250">it</span> <span m="750450">is</span> <span m="750660">linear</span>
  <span m="752760">in</span> <span m="752940">both</span> <span m="753720">the</span>
  <span m="753810">coordinate</span> <span m="754240">separation</span> <span m="754830">of</span>
  <span m="754890">those</span> <span m="755070">two</span> <span m="755220">events</span>
  <span m="756750">and</span> <span m="756870">the</span> <span m="756930">vector</span>
  <span m="757200">field.</span></p><p><span m="765660">So</span> <span m="765840">far,</span>
  <span m="765990">I've</span> <span m="766080">said</span> <span m="766260">nothing</span>
  <span m="766500">about</span> <span m="766680">physics,</span> <span m="767010">by</span>
  <span m="767130">the</span> <span m="767220">way.</span> <span m="767460">I'm</span>
  <span m="767550">just</span> <span m="767700">laying</span> <span m="767940">out</span>
  <span m="768060">some</span> <span m="768210">mathematical</span> <span m="768750">definitions.</span>
  <span m="769380">I'm</span> <span m="769440">going</span> <span m="769520">to</span>
  <span m="769610">bring</span> <span m="769770">it</span> <span m="769830">all</span>
  <span m="769940">together</span> <span m="770280">in</span> <span m="770370">a</span>
  <span m="770400">few</span> <span m="770610">moments.</span></p><p><span m="771840">I'm</span>
  <span m="771990">then</span> <span m="772200">going</span> <span m="772350">to</span>
  <span m="772440">say,</span> <span m="772790">OK,</span> <span m="773110">I</span>
  <span m="773160">know</span> <span m="773460">that</span> <span m="773580">I</span>
  <span m="773640">had</span> <span m="773760">trouble</span> <span m="774120">with</span>
  <span m="774360">my</span> <span m="774630">standard</span> <span m="775140">partial</span>
  <span m="775530">derivative.</span> <span m="776400">Let's</span> <span m="776730">define</span>
  <span m="777690">a</span> <span m="778170">derivative</span> <span m="778830">operator</span>
  <span m="780270">in</span> <span m="780390">the</span> <span m="780450">following</span>
  <span m="780960">way.</span> <span m="792270">Define</span> <span m="792690">a</span>
  <span m="792750">derivative</span> <span m="793290">by</span> <span m="793590">comparing</span>
  <span m="795360">the</span> <span m="795510">transported</span> <span m="796320">vector</span>
  <span m="809980">to</span> <span m="810100">the</span> <span m="810190">field</span>
  <span m="810490">at</span> <span m="810580">Q.</span> <span m="815540">So</span>
  <span m="817710">what</span> <span m="817800">I'm going to</span> <span m="817890">do</span>
  <span m="818070">for</span> <span m="818220">the</span> <span m="818280">moment</span>
  <span m="818630">is</span> <span m="818800">just</span> <span m="818950">denote</span>
  <span m="819390">this</span> <span m="820020">notion</span> <span m="820590">of</span>
  <span m="820710">a</span> <span m="820770">new</span> <span m="821010">kind of</span>
  <span m="821270">derivative</span> <span m="821640">with</span> <span m="821790">a</span>
  <span m="821820">capital</span> <span m="822420">D.</span> <span m="823530">Right</span>
  <span m="823740">now,</span> <span m="823980">it's</span> <span m="824070">just</span>
  <span m="824220">another</span> <span m="824550">symbol</span> <span m="824970">that</span>
  <span m="826020">we</span> <span m="826170">would</span> <span m="826260">pronounce</span>
  <span m="826560">with</span> <span m="826660">a</span> <span m="826750">&quot;duh&quot;</span>
  <span m="826970">sound</span> <span m="827430">so that</span> <span m="827580">it</span>
  <span m="827670">sounds</span> <span m="827910">like</span> <span m="828000">derivative.</span>
  <span m="828990">So</span> <span m="829110">don't</span> <span m="829260">read</span>
  <span m="829410">too</span> <span m="829590">much</span> <span m="829770">into</span>
  <span m="829920">that</span> <span m="830100">for</span> <span m="830250">a</span>
  <span m="830310">moment.</span></p><p><span m="834460">So</span> <span m="834600">I'm</span>
  <span m="834690">going</span> <span m="834810">to</span> <span m="834870">define</span>
  <span m="835350">this</span> <span m="835830">as</span> <span m="836940">A</span>
  <span m="838450">at Q</span> <span m="840870">minus A</span> <span m="841350">transported</span>
  <span m="844410">from</span> <span m="844650">P to Q</span> <span m="850450">and</span>
  <span m="850540">then</span> <span m="850660">divide</span> <span m="851080">by</span>
  <span m="851590">the</span> <span m="851680">separation.</span> <span m="853340">Take</span>
  <span m="853480">the</span> <span m="853570">limit--</span> <span m="854410">usual</span>
  <span m="854800">thing.</span> <span m="856660">And</span> <span m="857140">when</span>
  <span m="857410">you</span> <span m="857530">do</span> <span m="857740">this,</span>
  <span m="863620">you're</span> <span m="863640">going</span> <span m="863710">to</span>
  <span m="863790">get</span> <span m="863880">something</span> <span m="864070">that</span>
  <span m="864150">looks</span> <span m="864330">like</span> <span m="864510">the</span>
  <span m="864570">partial</span> <span m="864960">derivative</span> <span m="866440">plus</span>
  <span m="867700">an</span> <span m="867810">additional</span> <span m="868200">term</span>
  <span m="868590">on</span> <span m="868710">here.</span> <span m="874730">It</span>
  <span m="874820">looks</span> <span m="875030">like</span> <span m="875180">this.</span></p><p><span
  m="877370">So</span> <span m="877550">I've</span> <span m="877670">said</span> <span
  m="877910">nothing</span> <span m="878270">about</span> <span m="878540">what</span>
  <span m="878900">properties</span> <span m="879440">I'm going to</span> <span m="879710">demand</span>
  <span m="880090">of</span> <span m="880160">this</span> <span m="880370">thing.</span>
  <span m="881240">And</span> <span m="881360">in</span> <span m="881450">fact,</span>
  <span m="881780">there</span> <span m="881960">are</span> <span m="882020">many</span>
  <span m="882320">ways</span> <span m="882620">that</span> <span m="882770">one</span>
  <span m="883130">could</span> <span m="884060">define</span> <span m="884600">a</span>
  <span m="884660">transport</span> <span m="885200">of</span> <span m="885350">an</span>
  <span m="885470">object</span> <span m="885830">like</span> <span m="886010">this.</span>
  <span m="887300">In</span> <span m="887510">general,</span> <span m="888090">when</span>
  <span m="888350">you</span> <span m="888470">do</span> <span m="888740">this,</span>
  <span m="889580">this</span> <span m="890000">thing</span> <span m="890180">I'm</span>
  <span m="890330">calling</span> <span m="890660">Pi</span> <span m="891080">here</span>
  <span m="892280">is</span> <span m="892490">known</span> <span m="892790">as</span>
  <span m="893000">the</span> <span m="893090">connection.</span> <span m="898440">It</span>
  <span m="898650">is</span> <span m="898920">the</span> <span m="899130">object</span>
  <span m="900150">that</span> <span m="900330">connects</span> <span m="901290">point</span>
  <span m="901560">P</span> <span m="901740">to</span> <span m="901830">point</span>
  <span m="902080">Q.</span></p><p><span m="910080">So</span> <span m="910350">let's</span>
  <span m="910530">make</span> <span m="910650">a</span> <span m="910710">couple</span>
  <span m="910980">demands</span> <span m="911400">on</span> <span m="911490">its</span>
  <span m="911610">properties.</span> <span m="913480">So</span> <span m="913530">now</span>
  <span m="913710">I'll start</span> <span m="913920">to</span> <span m="913980">put</span>
  <span m="914460">a</span> <span m="914550">bit</span> <span m="914670">of</span>
  <span m="914730">physics</span> <span m="915090">in</span> <span m="915180">this.</span>
  <span m="928990">So</span> <span m="929380">demand</span> <span m="930110">one</span>
  <span m="937670">is</span> <span m="938030">I'm going</span> <span m="938150">to</span>
  <span m="938210">require</span> <span m="938720">that,</span> <span m="938900">when</span>
  <span m="939230">I</span> <span m="939470">change</span> <span m="940010">my</span>
  <span m="940220">coordinate</span> <span m="940700">representation,</span> <span
  m="949880">when</span> <span m="950060">I</span> <span m="950450">evaluate</span>
  <span m="951080">this</span> <span m="951500">in</span> <span m="951650">my</span>
  <span m="952010">new</span> <span m="952370">coordinate</span> <span m="952760">system,</span>
  <span m="955280">that</span> <span m="955440">I</span> <span m="955530">get</span>
  <span m="955710">something</span> <span m="956160">that</span> <span m="956280">looks</span>
  <span m="956580">like</span> <span m="956850">this.</span></p><p><span m="994470">If</span>
  <span m="994610">I</span> <span m="994940">do</span> <span m="995300">this,</span>
  <span m="997560">I'm</span> <span m="997730">going</span> <span m="998000">to</span>
  <span m="998120">find</span> <span m="998870">that,</span> <span m="999140">when</span>
  <span m="999530">I</span> <span m="999740">change</span> <span m="1000250">coordinates</span>
  <span m="1001420">and</span> <span m="1001540">apply</span> <span m="1001960">it</span>
  <span m="1002050">to</span> <span m="1002290">the</span> <span m="1002440">entire
  derivative</span> <span m="1003910">I've</span> <span m="1004060">defined</span>
  <span m="1004540">over</span> <span m="1004780">here,</span> <span m="1006190">that</span>
  <span m="1006430">little</span> <span m="1006730">extra</span> <span m="1007120">bit</span>
  <span m="1007270">of</span> <span m="1007330">schmutz</span> <span m="1007750">that's</span>
  <span m="1008020">on</span> <span m="1008170">the</span> <span m="1008230">second</span>
  <span m="1008590">line</span> <span m="1008860">there</span> <span m="1009040">is</span>
  <span m="1009280">exactly</span> <span m="1009820">what</span> <span m="1009940">you</span>
  <span m="1010030">need</span> <span m="1011170">to</span> <span m="1011260">cancel</span>
  <span m="1011690">out</span> <span m="1011800">this</span> <span m="1012010">annoying</span>
  <span m="1012340">bugger</span> <span m="1013780">so</span> <span m="1014050">that</span>
  <span m="1014350">you</span> <span m="1014590">have</span> <span m="1015940">a</span>
  <span m="1016000">nice</span> <span m="1016600">tensor</span> <span m="1017050">relationship</span>
  <span m="1017740">left.</span> <span m="1018280">So</span> <span m="1018430">I'm</span>
  <span m="1018490">going</span> <span m="1018610">to</span> <span m="1018670">demand</span>
  <span m="1019030">that</span> <span m="1019150">a</span> <span m="1019210">key</span>
  <span m="1019510">part</span> <span m="1019960">of</span> <span m="1020110">whatever</span>
  <span m="1020650">this</span> <span m="1020860">guy</span> <span m="1021070">turns</span>
  <span m="1021490">out</span> <span m="1021640">to</span> <span m="1021730">be</span>
  <span m="1022510">is</span> <span m="1022660">something</span> <span m="1022990">that</span>
  <span m="1023110">cancels</span> <span m="1023860">out</span> <span m="1024730">the</span>
  <span m="1024910">irritating</span> <span m="1025510">garbage</span> <span m="1025990">that</span>
  <span m="1026079">came</span> <span m="1026290">along</span> <span m="1026440">with</span>
  <span m="1026530">the</span> <span m="1026589">partial</span> <span m="1026920">derivative.</span></p><p><span
  m="1065490">Combine</span> <span m="1065970">that</span> <span m="1066090">with
  what</span> <span m="1066220">I'm</span> <span m="1066310">about</span> <span m="1066600">to</span>
  <span m="1066690">say</span> <span m="1066870">in</span> <span m="1066960">just</span>
  <span m="1067140">a</span> <span m="1067170">moment--</span> <span m="1068490">that</span>
  <span m="1068670">pins</span> <span m="1068910">things</span> <span m="1069210">down</span>
  <span m="1069450">significantly.</span> <span m="1071430">I'm</span> <span m="1071540">going</span>
  <span m="1071620">to</span> <span m="1071730">make</span> <span m="1071910">one</span>
  <span m="1072450">more</span> <span m="1072720">demand,</span> <span m="1074040">and</span>
  <span m="1074340">this</span> <span m="1074580">demand</span> <span m="1075150">is</span>
  <span m="1075360">going</span> <span m="1075480">to</span> <span m="1075660">then</span>
  <span m="1075840">be</span> <span m="1075960">connected</span> <span m="1076500">to</span>
  <span m="1076980">the</span> <span m="1077070">physical</span> <span m="1077400">picture</span>
  <span m="1077700">that</span> <span m="1077790">I'm</span> <span m="1077830">going
  to</span> <span m="1077940">introduce</span> <span m="1078330">in</span> <span m="1078420">about</span>
  <span m="1078660">five</span> <span m="1078980">minutes.</span> <span m="1079920">My</span>
  <span m="1081030">final</span> <span m="1081480">demand</span> <span m="1082050">is</span>
  <span m="1083130">I'm</span> <span m="1083250">going</span> <span m="1083370">to</span>
  <span m="1083430">require</span> <span m="1084070">that</span> <span m="1084270">whatever</span>
  <span m="1084630">this</span> <span m="1084810">derivative</span> <span m="1085290">is--</span>
  <span m="1087040">when</span> <span m="1087190">I</span> <span m="1087280">apply</span>
  <span m="1087640">it</span> <span m="1087700">to</span> <span m="1087820">the</span>
  <span m="1087880">metric,</span> <span m="1089410">I</span> <span m="1089500">get</span>
  <span m="1089650">0.</span> <span m="1091960">If</span> <span m="1092410">I</span>
  <span m="1092680">do</span> <span m="1093070">that,</span> <span m="1094970">then</span>
  <span m="1095230">it</span> <span m="1095410">turns</span> <span m="1095890">out</span>
  <span m="1096130">that</span> <span m="1096370">the</span> <span m="1096490">connection</span>
  <span m="1100510">is</span> <span m="1100930">exactly</span> <span m="1103630">the</span>
  <span m="1103810">Christoffel</span> <span m="1104410">symbol</span> <span m="1104800">that</span>
  <span m="1104950">we</span> <span m="1105100">worked</span> <span m="1105370">out</span>
  <span m="1105580">earlier.</span> <span m="1108370">If</span> <span m="1108580">I</span>
  <span m="1108730">put</span> <span m="1108970">in</span> <span m="1109150">this</span>
  <span m="1109300">demand,</span> <span m="1120958">the</span> <span m="1121450">connection</span>
  <span m="1122010">is</span> <span m="1122250">the</span> <span m="1122590">Christoffel,</span>
  <span m="1130920">and</span> <span m="1131340">this</span> <span m="1131670">derivative</span>
  <span m="1132420">is</span> <span m="1132600">nothing</span> <span m="1133020">more</span>
  <span m="1133260">than</span> <span m="1133440">the</span> <span m="1133500">covariant</span>
  <span m="1134100">derivative.</span> <span m="1135000">Der-iv-a-tive.</span> <span
  m="1140920">This</span> <span m="1141160">is</span> <span m="1141430">just</span>
  <span m="1141680">the</span> <span m="1141730">covariant</span> <span m="1142210">derivative</span>
  <span m="1142600">we</span> <span m="1142720">worked</span> <span m="1142960">out</span>
  <span m="1143050">earlier.</span></p><p><span m="1151560">So</span> <span m="1151780">much</span>
  <span m="1151940">for</span> <span m="1152030">mathematics.</span> <span m="1153020">The</span>
  <span m="1153110">key</span> <span m="1153260">thing</span> <span m="1153410">which</span>
  <span m="1153530">I</span> <span m="1153590">want</span> <span m="1153740">to</span>
  <span m="1153800">emphasize</span> <span m="1155240">at</span> <span m="1155420">this</span>
  <span m="1155630">point</span> <span m="1155870">in the</span> <span m="1155930">conversation--</span>
  <span m="1156650">I</span> <span m="1156710">hope</span> <span m="1156830">we</span>
  <span m="1156890">can</span> <span m="1157040">see</span> <span m="1157190">the</span>
  <span m="1157280">logic</span> <span m="1157760">behind</span> <span m="1158060">the</span>
  <span m="1158120">first</span> <span m="1158410">demand.</span> <span m="1158870">That's</span>
  <span m="1159050">just</span> <span m="1159600">something</span> <span m="1159800">which</span>
  <span m="1159950">I'm</span> <span m="1160010">going</span> <span m="1160190">to</span>
  <span m="1160250">introduce</span> <span m="1160730">in</span> <span m="1160880">order</span>
  <span m="1161060">to</span> <span m="1161690">clean</span> <span m="1162110">this</span>
  <span m="1162290">guy</span> <span m="1162530">up.</span></p><p><span m="1163580">This</span>
  <span m="1163940">is</span> <span m="1164060">my</span> <span m="1164270">choice.</span>
  <span m="1165380">Not</span> <span m="1165560">just</span> <span m="1165680">my</span>
  <span m="1165860">choice--</span> <span m="1166220">it's the</span> <span m="1166280">choice</span>
  <span m="1166520">of</span> <span m="1166630">a</span> <span m="1167000">lot</span>
  <span m="1167300">of</span> <span m="1167360">people</span> <span m="1167660">who</span>
  <span m="1167810">have</span> <span m="1168110">helped</span> <span m="1168290">to</span>
  <span m="1168350">develop</span> <span m="1168680">this</span> <span m="1168800">subject.</span>
  <span m="1169160">But</span> <span m="1169250">it's</span> <span m="1170030">a</span>
  <span m="1170120">good</span> <span m="1170420">one,</span> <span m="1171380">because,</span>
  <span m="1171800">when</span> <span m="1172130">I</span> <span m="1172250">do</span>
  <span m="1172520">this,</span> <span m="1173240">there</span> <span m="1173450">is</span>
  <span m="1173570">a</span> <span m="1173630">particularly</span> <span m="1174860">good</span>
  <span m="1175280">physical</span> <span m="1175820">interpretation</span> <span
  m="1176630">to</span> <span m="1176840">what</span> <span m="1178730">this</span>
  <span m="1178910">notion</span> <span m="1179210">of</span> <span m="1179270">transport</span>
  <span m="1179840">means.</span> <span m="1180850">And</span> <span m="1180980">bear</span>
  <span m="1181190">with</span> <span m="1181310">me</span> <span m="1181430">for</span>
  <span m="1181550">a</span> <span m="1181580">second</span> <span m="1182290">while</span>
  <span m="1182510">I</span> <span m="1182570">gather</span> <span m="1182930">my</span>
  <span m="1183110">notes</span> <span m="1183530">together.</span></p><p><span m="1189020">So</span>
  <span m="1195080">let's</span> <span m="1195290">do</span> <span m="1195410">the</span>
  <span m="1195500">top</span> <span m="1195770">one</span> <span m="1195950">first.</span>
  <span m="1238990">OK,</span> <span m="1239740">so</span> <span m="1240970">let's</span>
  <span m="1241150">make</span> <span m="1241360">that</span> <span m="1241540">curve</span>
  <span m="1241870">again.</span> <span m="1245210">And</span> <span m="1246830">actually,</span>
  <span m="1247030">let's</span> <span m="1247160">just</span> <span m="1247280">go</span>
  <span m="1247400">ahead</span> <span m="1247580">and</span> <span m="1247940">redraw</span>
  <span m="1248450">my</span> <span m="1248960">vector</span> <span m="1249260">field.</span>
  <span m="1249980">I</span> <span m="1250070">do</span> <span m="1250220">want</span>
  <span m="1250340">to</span> <span m="1250400">have</span> <span m="1250550">a</span>
  <span m="1250610">different</span> <span m="1250820">copy</span> <span m="1251090">of</span>
  <span m="1251150">this.</span></p><p><span m="1259210">Let</span> <span m="1259300">me</span>
  <span m="1259360">introduce</span> <span m="1259780">one</span> <span m="1259990">other</span>
  <span m="1260200">object.</span> <span m="1262360">So</span> <span m="1262600">I'm</span>
  <span m="1262660">going</span> <span m="1262780">to</span> <span m="1263050">give</span>
  <span m="1263350">this</span> <span m="1263560">curve a</span> <span m="1264000">name.</span>
  <span m="1264300">I'm going to</span> <span m="1264410">call</span> <span m="1264640">this</span>
  <span m="1264790">curve</span> <span m="1265090">gamma.</span> <span m="1271150">And</span>
  <span m="1271420">this</span> <span m="1271720">is</span> <span m="1271840">a</span>
  <span m="1271900">notion</span> <span m="1272290">that</span> <span m="1272390">I'm</span>
  <span m="1272450">going</span> <span m="1272520">to</span> <span m="1272620">make</span>
  <span m="1272830">much</span> <span m="1273190">more</span> <span m="1273370">precise</span>
  <span m="1273820">in</span> <span m="1273910">a</span> <span m="1273970">future</span>
  <span m="1274300">lecture,</span> <span m="1274820">but</span> <span m="1274870">imagine</span>
  <span m="1275320">that</span> <span m="1275440">there</span> <span m="1275650">is</span>
  <span m="1275800">some</span> <span m="1276040">kind</span> <span m="1276580">of</span>
  <span m="1277000">a</span> <span m="1277510">tape</span> <span m="1277840">measure</span>
  <span m="1278710">that</span> <span m="1278950">reads</span> <span m="1279430">out</span>
  <span m="1279910">along</span> <span m="1280870">the</span> <span m="1280960">curve</span>
  <span m="1281350">gamma</span> <span m="1283510">that</span> <span m="1283780">is</span>
  <span m="1284590">uniformly</span> <span m="1285340">ticked</span> <span m="1286000">in</span>
  <span m="1286120">a</span> <span m="1286180">way</span> <span m="1286480">that</span>
  <span m="1286720">we</span> <span m="1286900">will</span> <span m="1287080">make</span>
  <span m="1287290">precise</span> <span m="1287800">in</span> <span m="1287890">a</span>
  <span m="1287950">future</span> <span m="1288280">lecture.</span> <span m="1296940">I</span>
  <span m="1297030">will</span> <span m="1297120">call</span> <span m="1297390">the</span>
  <span m="1297450">parameter</span> <span m="1298020">that</span> <span m="1298170">is</span>
  <span m="1298320">uniform</span> <span m="1298950">that</span> <span m="1299130">denotes</span>
  <span m="1299550">these</span> <span m="1299760">uniform</span> <span m="1300210">tick</span>
  <span m="1300450">marks--</span> <span m="1305990">I</span> <span m="1306080">will</span>
  <span m="1306170">call</span> <span m="1306380">that</span> <span m="1306590">lambda.</span>
  <span m="1308030">If</span> <span m="1308120">you</span> <span m="1308210">want</span>
  <span m="1308330">to</span> <span m="1308390">read</span> <span m="1308570">a</span>
  <span m="1308630">little</span> <span m="1308780">bit</span> <span m="1308900">about</span>
  <span m="1309170">this,</span> <span m="1309410">this</span> <span m="1309530">is</span>
  <span m="1309650">what's</span> <span m="1309800">known</span> <span m="1309980">as</span>
  <span m="1310070">an</span> <span m="1310210">affine</span> <span m="1310760">parameter.</span>
  <span m="1312140">We</span> <span m="1312380">will</span> <span m="1312500">make</span>
  <span m="1312680">this</span> <span m="1312830">a</span> <span m="1312860">little</span>
  <span m="1312980">bit</span> <span m="1313100">more</span> <span m="1313250">precise</span>
  <span m="1314240">very</span> <span m="1314540">soon.</span> <span m="1319590">With</span>
  <span m="1319770">this</span> <span m="1320100">in</span> <span m="1320250">mind,</span>
  <span m="1321820">you</span> <span m="1321920">should</span> <span m="1322020">be</span>
  <span m="1322120">able</span> <span m="1322220">to</span> <span m="1322320">convince</span>
  <span m="1322440">yourself</span> <span m="1322800">that</span> <span m="1322950">this</span>
  <span m="1323130">field</span> <span m="1323520">U</span> <span m="1324330">defines</span>
  <span m="1325020">the</span> <span m="1325140">tangent</span> <span m="1325710">vector</span>
  <span m="1326040">to</span> <span m="1326220">this</span> <span m="1326370">curve.</span></p><p><span
  m="1341170">So</span> <span m="1341430">let's</span> <span m="1341790">say</span>
  <span m="1343170">that</span> <span m="1344070">my</span> <span m="1344370">original</span>
  <span m="1344820">point</span> <span m="1345150">here,</span> <span m="1345570">that</span>
  <span m="1345780">this</span> <span m="1346140">is</span> <span m="1346410">at</span>
  <span m="1347610">lambda</span> <span m="1348180">equals</span> <span m="1348630">2--</span>
  <span m="1349830">and</span> <span m="1350190">let's</span> <span m="1350340">say</span>
  <span m="1350670">this</span> <span m="1350970">is</span> <span m="1351120">at</span>
  <span m="1351330">lambda</span> <span m="1351810">equals</span> <span m="1352200">7.</span>
  <span m="1353790">And</span> <span m="1353910">what</span> <span m="1354030">I</span>
  <span m="1354120">want</span> <span m="1354300">to</span> <span m="1354390">do</span>
  <span m="1354690">is</span> <span m="1354870">transport</span> <span m="1355650">the</span>
  <span m="1355740">vector</span> <span m="1356610">from</span> <span m="1356850">2</span>
  <span m="1357390">to</span> <span m="1357540">7.</span> <span m="1359510">Well,</span>
  <span m="1359670">a</span> <span m="1359760">way</span> <span m="1359970">that</span>
  <span m="1360090">I</span> <span m="1360180">can</span> <span m="1360360">do</span>
  <span m="1360570">this</span> <span m="1360840">is</span> <span m="1360990">by</span>
  <span m="1361110">saying,</span> <span m="1361570">OK,</span> <span m="1362320">I</span>
  <span m="1362400">now</span> <span m="1362730">know</span> <span m="1363330">that</span>
  <span m="1363720">the</span> <span m="1363900">derivative</span> <span m="1364500">that</span>
  <span m="1364590">goes</span> <span m="1364890">over</span> <span m="1365190">here--</span>
  <span m="1365430">this</span> <span m="1365580">is</span> <span m="1365880">just</span>
  <span m="1366160">the</span> <span m="1366240">covariant</span> <span m="1366690">derivative.</span>
  <span m="1367890">So</span> <span m="1368070">I</span> <span m="1368130">forgot</span>
  <span m="1368340">to</span> <span m="1368430">write</span> <span m="1368610">this</span>
  <span m="1368760">down</span> <span m="1369030">but</span> <span m="1369180">from</span>
  <span m="1369360">now</span> <span m="1369540">on,</span> <span m="1370590">this</span>
  <span m="1370950">derivative</span> <span m="1371490">I</span> <span m="1371580">wrote</span>
  <span m="1371790">down--</span> <span m="1372000">I'm</span> <span m="1372060">going</span>
  <span m="1372160">to</span> <span m="1372230">go</span> <span m="1372330">back</span>
  <span m="1372630">to</span> <span m="1372810">the</span> <span m="1372960">gradient</span>
  <span m="1373650">symbol</span> <span m="1374070">we</span> <span m="1374190">used</span>
  <span m="1374430">for</span> <span m="1374520">the</span> <span m="1374610">covariant</span>
  <span m="1375030">derivative.</span></p><p><span m="1379240">What</span> <span m="1379390">I</span>
  <span m="1379450">can</span> <span m="1379630">do</span> <span m="1380050">is</span>
  <span m="1380380">take</span> <span m="1383300">the</span> <span m="1383360">covariant</span>
  <span m="1383840">derivative</span> <span m="1384590">of</span> <span m="1384680">my</span>
  <span m="1384830">vector</span> <span m="1385220">field,</span> <span m="1387930">contract
  it</span> <span m="1388630">with</span> <span m="1388810">this</span> <span m="1388960">tangent</span>
  <span m="1389410">vector.</span> <span m="1390560">And</span> <span m="1390670">what</span>
  <span m="1390850">this</span> <span m="1391060">does--</span> <span m="1397050">I'm</span>
  <span m="1397110">going to</span> <span m="1397260">define</span> <span m="1397680">this</span>
  <span m="1398010">as</span> <span m="1398250">capital</span> <span m="1399030">D</span>
  <span m="1399240">alpha</span> <span m="1399690">D lambda.</span> <span m="1400050">This</span>
  <span m="1400170">is</span> <span m="1400530">a</span> <span m="1401200">covariant</span>
  <span m="1402390">derivative</span> <span m="1403020">with</span> <span m="1403260">respect</span>
  <span m="1403770">to</span> <span m="1403860">the</span> <span m="1403920">parameter</span>
  <span m="1404370">lambda</span> <span m="1404850">as</span> <span m="1405090">I</span>
  <span m="1405180">move</span> <span m="1405540">along</span> <span m="1405900">this</span>
  <span m="1406080">constrained</span> <span m="1406560">trajectory.</span> <span
  m="1407860">What</span> <span m="1407970">this</span> <span m="1408240">does</span>
  <span m="1409350">is</span> <span m="1409560">this</span> <span m="1409800">tells</span>
  <span m="1410250">me</span> <span m="1414470">how</span> <span m="1415670">A</span>
  <span m="1417140">changes</span> <span m="1421580">as</span> <span m="1422030">it</span>
  <span m="1422240">is</span> <span m="1422450">transported</span> <span m="1426440">along</span>
  <span m="1426800">the</span> <span m="1426890">curve.</span> <span m="1459590">I'm</span>
  <span m="1459680">now</span> <span m="1459860">going</span> <span m="1459980">to</span>
  <span m="1460040">argue--</span> <span m="1460820">what</span> <span m="1461000">parallel</span>
  <span m="1461540">transport</span> <span m="1462020">comes</span> <span m="1462290">down</span>
  <span m="1462500">to</span> <span m="1463220">is</span> <span m="1463520">when</span>
  <span m="1463760">you</span> <span m="1463880">require</span> <span m="1479510">that,</span>
  <span m="1479720">as</span> <span m="1479930">you</span> <span m="1480080">slide</span>
  <span m="1480500">this</span> <span m="1480680">thing</span> <span m="1480860">along</span>
  <span m="1481190">here,</span> <span m="1482840">the</span> <span m="1482930">covariant</span>
  <span m="1484670">total</span> <span m="1484970">derivative</span> <span m="1485330">of
  this</span> <span m="1485510">thing</span> <span m="1485660">as</span> <span m="1485750">you</span>
  <span m="1485810">move</span> <span m="1486050">along</span> <span m="1486830">the</span>
  <span m="1486920">curve,</span> <span m="1487400">that</span> <span m="1487580">it's</span>
  <span m="1487730">equal</span> <span m="1487970">to</span> <span m="1488120">0.</span></p><p><span
  m="1489280">OK,</span> <span m="1489560">now</span> <span m="1489680">let</span>
  <span m="1489770">me</span> <span m="1489980">motivate</span> <span m="1490460">where</span>
  <span m="1490610">that's</span> <span m="1490790">coming</span> <span m="1491060">from.</span>
  <span m="1491340">Why</span> <span m="1491540">is</span> <span m="1491780">that?</span>
  <span m="1500970">So let's</span> <span m="1501150">put</span> <span m="1501390">all</span>
  <span m="1501570">of</span> <span m="1501690">our</span> <span m="1501750">definitions</span>
  <span m="1502440">back</span> <span m="1502680">in.</span> <span m="1504930">Let's</span>
  <span m="1505530">apply</span> <span m="1506370">the</span> <span m="1506520">definition</span>
  <span m="1507090">of</span> <span m="1507180">covariant</span> <span m="1507570">derivative</span>
  <span m="1508050">that</span> <span m="1508170">we</span> <span m="1508260">discussed</span>
  <span m="1508650">in</span> <span m="1508720">a</span> <span m="1508740">previous</span>
  <span m="1509040">lecture</span> <span m="1509490">and</span> <span m="1509580">we've</span>
  <span m="1509760">all</span> <span m="1509880">come</span> <span m="1510120">to</span>
  <span m="1510240">know</span> <span m="1510480">and</span> <span m="1510630">love.</span></p><p><span
  m="1528790">Now,</span> <span m="1529320">this</span> <span m="1529470">is</span>
  <span m="1529560">the</span> <span m="1529620">bit</span> <span m="1529740">where</span>
  <span m="1529870">we</span> <span m="1530000">begin</span> <span m="1530160">to</span>
  <span m="1530220">introduce</span> <span m="1530610">a</span> <span m="1530640">little</span>
  <span m="1530790">bit</span> <span m="1530880">of</span> <span m="1530940">physics.</span>
  <span m="1532210">Let's</span> <span m="1532320">imagine</span> <span m="1533100">that</span>
  <span m="1533370">points</span> <span m="1533820">P</span> <span m="1534240">and</span>
  <span m="1534390">Q</span> <span m="1535320">are</span> <span m="1535410">sufficiently</span>
  <span m="1536040">close</span> <span m="1536460">to</span> <span m="1536550">each</span>
  <span m="1536700">other</span> <span m="1537090">that</span> <span m="1537270">they</span>
  <span m="1537420">fit</span> <span m="1537840">within</span> <span m="1538320">a</span>
  <span m="1538440">single,</span> <span m="1539220">freely</span> <span m="1539580">falling</span>
  <span m="1539880">frame.</span> <span m="1540210">They</span> <span m="1540300">can</span>
  <span m="1540450">go</span> <span m="1540660">into</span> <span m="1540840">the</span>
  <span m="1540930">same</span> <span m="1541380">local</span> <span m="1541740">Lorentz</span>
  <span m="1542100">frame.</span> <span m="1565820">So remember,</span> <span m="1566180">when</span>
  <span m="1566300">I</span> <span m="1566390">go</span> <span m="1566600">into</span>
  <span m="1566810">my</span> <span m="1566960">local</span> <span m="1567320">Lorentz</span>
  <span m="1567680">frame,</span> <span m="1568730">the</span> <span m="1568820">metric</span>
  <span m="1569360">becomes</span> <span m="1569840">the</span> <span m="1569900">metric</span>
  <span m="1570230">of</span> <span m="1570290">flat</span> <span m="1570680">spacetime.</span>
  <span m="1571790">G goes</span> <span m="1572060">over</span> <span m="1572240">to</span>
  <span m="1572470">eta.</span> <span m="1575230">There</span> <span m="1575410">is</span>
  <span m="1575620">a</span> <span m="1575740">second</span> <span m="1576220">order</span>
  <span m="1576490">correction</span> <span m="1576970">to</span> <span m="1577090">that.</span>
  <span m="1577730">So</span> <span m="1577990">the</span> <span m="1578110">second</span>
  <span m="1578460">derivatives--</span> <span m="1579660">I</span> <span m="1579700">cannot</span>
  <span m="1579970">find</span> <span m="1580120">a</span> <span m="1580690">[INAUDIBLE]</span>
  <span m="1581050">that</span> <span m="1581140">gets</span> <span m="1581260">rid</span>
  <span m="1581440">of</span> <span m="1581560">them.</span> <span m="1582340">So</span>
  <span m="1582460">there'll</span> <span m="1582610">be</span> <span m="1582730">a</span>
  <span m="1582760">little</span> <span m="1582910">bit</span> <span m="1583030">of</span>
  <span m="1583150">that</span> <span m="1583420">there,</span> <span m="1583870">which</span>
  <span m="1584680">tells</span> <span m="1584950">me</span> <span m="1585070">how</span>
  <span m="1585640">large</span> <span m="1586210">this</span> <span m="1586420">Lorentz</span>
  <span m="1586750">frame</span> <span m="1586990">can</span> <span m="1587140">be.</span></p><p><span
  m="1588200">But</span> <span m="1588400">I</span> <span m="1588460">can</span> <span
  m="1588610">get</span> <span m="1588820">rid</span> <span m="1589330">of</span>
  <span m="1589480">all</span> <span m="1589630">the</span> <span m="1589720">first</span>
  <span m="1590080">derivatives.</span> <span m="1591390">And</span> <span m="1591520">if</span>
  <span m="1591580">you</span> <span m="1591670">get</span> <span m="1591820">rid</span>
  <span m="1591970">of</span> <span m="1592090">all</span> <span m="1592300">the</span>
  <span m="1592390">first</span> <span m="1592780">derivatives,</span> <span m="1594160">you</span>
  <span m="1594340">zero</span> <span m="1594670">out</span> <span m="1594880">the</span>
  <span m="1594970">Christoffel</span> <span m="1595460">symbols</span> <span m="1595930">in</span>
  <span m="1596260">that</span> <span m="1596560">frame.</span> <span m="1597740">So</span>
  <span m="1597850">in</span> <span m="1598030">that</span> <span m="1598240">frame,</span>
  <span m="1598810">there</span> <span m="1599050">are</span> <span m="1599440">no</span>
  <span m="1599650">Christoffel</span> <span m="1600130">symbols.</span> <span m="1610110">So</span>
  <span m="1610310">what</span> <span m="1610640">this</span> <span m="1610940">means</span>
  <span m="1613580">is</span> <span m="1613760">that,</span> <span m="1614060">in</span>
  <span m="1614450">this</span> <span m="1614720">frame,</span> <span m="1636060">this</span>
  <span m="1636330">just</span> <span m="1636600">becomes</span> <span m="1637140">the</span>
  <span m="1637230">idea</span> <span m="1637680">that</span> <span m="1640760">a</span>
  <span m="1640880">simple</span> <span m="1641180">total</span> <span m="1641480">derivative</span>
  <span m="1641960">of</span> <span m="1642050">this</span> <span m="1642260">object--</span>
  <span m="1642530">you</span> <span m="1642590">don't</span> <span m="1642740">need</span>
  <span m="1642890">to</span> <span m="1642950">include</span> <span m="1643280">all</span>
  <span m="1643610">the</span> <span m="1643730">garbage</span> <span m="1644180">that</span>
  <span m="1644270">comes</span> <span m="1644510">along</span> <span m="1644960">with</span>
  <span m="1645110">the</span> <span m="1645710">covariant</span> <span m="1645950">derivative--</span>
  <span m="1647150">this</span> <span m="1647360">is</span> <span m="1647480">equal</span>
  <span m="1647690">to</span> <span m="1647780">0.</span> <span m="1648230">And</span>
  <span m="1648380">that's</span> <span m="1648680">equivalent</span> <span m="1649160">to</span>
  <span m="1649280">saying</span> <span m="1650300">that,</span> <span m="1655140">as</span>
  <span m="1655350">I</span> <span m="1655470">take</span> <span m="1656790">this</span>
  <span m="1657060">vector</span> <span m="1657810">and</span> <span m="1657930">transport
  it</span> <span m="1658590">along,</span> <span m="1659700">I</span> <span m="1659850">hold</span>
  <span m="1660540">all</span> <span m="1660840">of</span> <span m="1660960">its</span>
  <span m="1661140">components</span> <span m="1662250">constant</span> <span m="1663570">as</span>
  <span m="1663840">I</span> <span m="1663930">slide</span> <span m="1664440">it</span>
  <span m="1664590">from</span> <span m="1664860">one</span> <span m="1665160">step</span>
  <span m="1665580">to</span> <span m="1665730">the</span> <span m="1665880">other.</span></p><p><span
  m="1689410">So</span> <span m="1691390">I</span> <span m="1691450">start</span>
  <span m="1691750">out</span> <span m="1691960">with</span> <span m="1692230">my</span>
  <span m="1692620">A</span> <span m="1692890">at</span> <span m="1693100">point</span>
  <span m="1693550">P</span> <span m="1693940">here.</span> <span m="1694830">And</span>
  <span m="1694950">then</span> <span m="1695010">I</span> <span m="1695080">slide</span>
  <span m="1695590">it</span> <span m="1695680">over</span> <span m="1695890">a</span>
  <span m="1695920">little</span> <span m="1696130">bit,</span> <span m="1696340">holding</span>
  <span m="1696880">all</span> <span m="1696970">the</span> <span m="1697060">components</span>
  <span m="1697600">constant</span> <span m="1698680">just</span> <span m="1698860">like</span>
  <span m="1698980">this--</span> <span m="1699790">slide</span> <span m="1700270">over</span>
  <span m="1700510">again,</span> <span m="1701920">slide</span> <span m="1702400">it</span>
  <span m="1702490">over</span> <span m="1702730">again.</span> <span m="1703750">Da,
  da,</span> <span m="1703890">da, da</span> <span m="1704060">da.</span> <span m="1705788">Da,
  da,</span> <span m="1706264">da,</span> <span m="1706740">da, da.</span> <span m="1711510">Till
  finally,</span> <span m="1712050">I</span> <span m="1712140">get</span> <span m="1712320">it</span>
  <span m="1712440">over</span> <span m="1712660">to</span> <span m="1712740">there.</span></p><p><span
  m="1713040">What</span> <span m="1713280">this</span> <span m="1713490">is</span>
  <span m="1713610">doing</span> <span m="1713910">is</span> <span m="1714060">that--</span>
  <span m="1717360">any</span> <span m="1717690">two</span> <span m="1717930">vectors</span>
  <span m="1719820">in</span> <span m="1719970">the</span> <span m="1720450">middle</span>
  <span m="1720900">of</span> <span m="1721020">this</span> <span m="1721170">transport</span>
  <span m="1721710">process--</span> <span m="1722730">I</span> <span m="1722880">am</span>
  <span m="1722970">holding</span> <span m="1723420">them</span> <span m="1723750">as</span>
  <span m="1723960">parallel</span> <span m="1724710">as</span> <span m="1725010">it</span>
  <span m="1725100">is</span> <span m="1725220">possible</span> <span m="1725790">to</span>
  <span m="1725910">hold</span> <span m="1726240">them,</span> <span m="1727050">given</span>
  <span m="1727410">that,</span> <span m="1727620">to</span> <span m="1727740">be</span>
  <span m="1727860">blunt,</span> <span m="1728850">you</span> <span m="1728970">can't</span>
  <span m="1729210">even</span> <span m="1729420">really</span> <span m="1729690">define</span>
  <span m="1730530">a</span> <span m="1730620">notion</span> <span m="1731130">of</span>
  <span m="1731220">two</span> <span m="1731520">objects</span> <span m="1731970">being</span>
  <span m="1732240">parallel</span> <span m="1733200">on</span> <span m="1733380">a</span>
  <span m="1733440">curved</span> <span m="1733740">surface</span> <span m="1734250">if</span>
  <span m="1734400">there's</span> <span m="1734640">a</span> <span m="1734700">macroscopic</span>
  <span m="1735360">separation</span> <span m="1735840">between</span> <span m="1736110">them.</span>
  <span m="1737140">But</span> <span m="1737310">if</span> <span m="1737490">you</span>
  <span m="1737670">think</span> <span m="1737910">about</span> <span m="1738180">just</span>
  <span m="1738360">a</span> <span m="1738420">little</span> <span m="1739020">region</span>
  <span m="1739530">that's</span> <span m="1739640">sufficiently</span> <span m="1740220">small,</span>
  <span m="1740940">that</span> <span m="1741300">it's</span> <span m="1741930">flat</span>
  <span m="1742740">up</span> <span m="1742860">to</span> <span m="1742980">quadratic</span>
  <span m="1743490">corrections,</span> <span m="1744780">then</span> <span m="1745140">a</span>
  <span m="1745200">notion</span> <span m="1745620">of</span> <span m="1745770">these</span>
  <span m="1745950">things</span> <span m="1746160">being</span> <span m="1746310">parallel</span>
  <span m="1746730">to</span> <span m="1746820">each</span> <span m="1746970">other</span>
  <span m="1747150">makes</span> <span m="1747420">sense.</span> <span m="1748710">And</span>
  <span m="1749100">this</span> <span m="1749940">idea,</span> <span m="1750450">that</span>
  <span m="1750630">I'm</span> <span m="1750750">going</span> <span m="1750860">to</span>
  <span m="1750960">demand</span> <span m="1751770">that,</span> <span m="1752010">upon</span>
  <span m="1752370">transport,</span> <span m="1753060">the</span> <span m="1753150">derivative</span>
  <span m="1753490">of</span> <span m="1753550">the</span> <span m="1753630">metric</span>
  <span m="1754050">equals</span> <span m="1754380">0,</span> <span m="1755370">thereby</span>
  <span m="1756000">yielding</span> <span m="1757110">my</span> <span m="1757380">connection</span>
  <span m="1757830">being</span> <span m="1758010">the</span> <span m="1758230">Christoffel</span>
  <span m="1758820">and</span> <span m="1758970">this</span> <span m="1759120">derivative</span>
  <span m="1759540">being</span> <span m="1760200">the</span> <span m="1760290">covariant</span>
  <span m="1760740">derivative--</span> <span m="1761700">it</span> <span m="1761820">tells</span>
  <span m="1762180">us</span> <span m="1762330">that</span> <span m="1762480">this</span>
  <span m="1762660">notion</span> <span m="1763050">of</span> <span m="1763140">transport</span>
  <span m="1764040">is</span> <span m="1764220">one</span> <span m="1764610">in</span>
  <span m="1764730">which</span> <span m="1765030">objects</span> <span m="1765450">are</span>
  <span m="1765510">just</span> <span m="1765690">kept</span> <span m="1766080">as</span>
  <span m="1766350">parallel</span> <span m="1767070">as</span> <span m="1767220">possible</span>
  <span m="1767700">as</span> <span m="1767820">they</span> <span m="1767910">slide</span>
  <span m="1768270">along</span> <span m="1768540">here.</span> <span m="1769230">And
  that</span> <span m="1769500">is</span> <span m="1769620">why</span> <span m="1769920">this</span>
  <span m="1770220">is</span> <span m="1770340">called</span> <span m="1771600">&quot;parallel</span>
  <span m="1772080">transport.&quot;</span> <span m="1773020">It's</span> <span m="1773190">as</span>
  <span m="1773310">parallel</span> <span m="1773970">as</span> <span m="1774150">it's</span>
  <span m="1774300">possible</span> <span m="1774840">to</span> <span m="1774960">be,</span>
  <span m="1775530">given</span> <span m="1775770">the</span> <span m="1775860">curvature.</span></p><p><span
  m="1799140">So</span> <span m="1799250">as</span> <span m="1799370">I</span> <span
  m="1799700">switch</span> <span m="1800000">gears,</span> <span m="1800380">I</span>
  <span m="1800540">just want</span> <span m="1800690">to</span> <span m="1800750">emphasize</span>
  <span m="1804600">I</span> <span m="1804700">went</span> <span m="1804740">through</span>
  <span m="1804920">the</span> <span m="1805010">mathematics</span> <span m="1805520">of</span>
  <span m="1805580">that</span> <span m="1805730">with</span> <span m="1805910">a</span>
  <span m="1806780">fair</span> <span m="1807260">amount</span> <span m="1807530">of</span>
  <span m="1807590">care</span> <span m="1807940">because</span> <span m="1808850">it</span>
  <span m="1809000">is</span> <span m="1809210">important</span> <span m="1809750">to</span>
  <span m="1809840">keep</span> <span m="1810140">this</span> <span m="1810320">stuff</span>
  <span m="1810680">as</span> <span m="1811190">rigorous</span> <span m="1811610">as</span>
  <span m="1811730">possible</span> <span m="1812300">here.</span> <span m="1814190">This</span>
  <span m="1814460">notion</span> <span m="1814850">of</span> <span m="1814910">parallel</span>
  <span m="1815330">transport</span> <span m="1815930">gets</span> <span m="1816230">used</span>
  <span m="1817010">a</span> <span m="1817130">lot</span> <span m="1817590">when</span>
  <span m="1817680">we</span> <span m="1817790">start</span> <span m="1818030">talking</span>
  <span m="1818360">about</span> <span m="1818990">things</span> <span m="1819380">moving</span>
  <span m="1819680">around</span> <span m="1820400">in</span> <span m="1822650">a</span>
  <span m="1822710">curved</span> <span m="1822990">spacetime.</span> <span m="1824090">In</span>
  <span m="1824210">particular,</span> <span m="1825200">if</span> <span m="1825410">you</span>
  <span m="1825560">think</span> <span m="1825890">about</span> <span m="1826250">an</span>
  <span m="1826400">object</span> <span m="1826820">that</span> <span m="1826940">is</span>
  <span m="1827060">freely</span> <span m="1827480">falling,</span> <span m="1828170">and</span>
  <span m="1828380">it is</span> <span m="1828530">experiencing</span> <span m="1829280">no</span>
  <span m="1829820">forces</span> <span m="1831170">other</span> <span m="1831350">than</span>
  <span m="1831470">gravity,</span> <span m="1831990">which</span> <span m="1832100">we</span>
  <span m="1832220">are</span> <span m="1832280">going</span> <span m="1832460">to</span>
  <span m="1832520">no</span> <span m="1832670">longer</span> <span m="1832850">regard</span>
  <span m="1833150">as</span> <span m="1833240">a</span> <span m="1833300">force</span>
  <span m="1833670">before</span> <span m="1833870">too</span> <span m="1834050">long--</span>
  <span m="1835160">if</span> <span m="1835310">you</span> <span m="1835370">just</span>
  <span m="1835520">go</span> <span m="1835670">back</span> <span m="1835910">to</span>
  <span m="1835970">Newtonian</span> <span m="1836360">intuition,</span> <span m="1836870">what</span>
  <span m="1837020">does</span> <span m="1837110">it</span> <span m="1837200">do?</span></p><p><span
  m="1838170">Well,</span> <span m="1838580">you</span> <span m="1838700">give</span>
  <span m="1838850">it</span> <span m="1838970">an</span> <span m="1839090">initial</span>
  <span m="1839480">velocity</span> <span m="1840200">or</span> <span m="1840330">initial</span>
  <span m="1840650">momentum,</span> <span m="1841190">and</span> <span m="1841310">it</span>
  <span m="1841400">maintains</span> <span m="1841910">it.</span> <span m="1842060">It</span>
  <span m="1842180">just</span> <span m="1842330">continues</span> <span m="1842720">going</span>
  <span m="1842990">in</span> <span m="1843110">a</span> <span m="1843140">straight</span>
  <span m="1843500">line.</span> <span m="1844880">In</span> <span m="1845060">spacetime,</span>
  <span m="1846230">going</span> <span m="1846500">in</span> <span m="1846560">a</span>
  <span m="1846590">straight</span> <span m="1846920">line</span> <span m="1847280">basically</span>
  <span m="1847820">means,</span> <span m="1848510">at</span> <span m="1848660">every</span>
  <span m="1848960">step,</span> <span m="1850130">I</span> <span m="1850340">move</span>
  <span m="1851120">and</span> <span m="1851540">I</span> <span m="1851690">take</span>
  <span m="1852140">the</span> <span m="1852260">tangent</span> <span m="1852770">to</span>
  <span m="1852890">my</span> <span m="1853040">world</span> <span m="1853370">line,</span>
  <span m="1853940">my</span> <span m="1854150">four-velocity,</span> <span m="1855620">and</span>
  <span m="1855740">I</span> <span m="1855800">move</span> <span m="1856010">it</span>
  <span m="1856070">parallel</span> <span m="1856520">to</span> <span m="1856640">itself.</span>
  <span m="1858060">So</span> <span m="1858140">this</span> <span m="1858320">notion</span>
  <span m="1858710">of</span> <span m="1858770">parallel</span> <span m="1859160">transport</span>
  <span m="1859730">is</span> <span m="1859910">going</span> <span m="1860120">to</span>
  <span m="1860210">be</span> <span m="1860330">the</span> <span m="1860480">key</span>
  <span m="1860810">thing</span> <span m="1861080">that</span> <span m="1861200">we</span>
  <span m="1861350">use</span> <span m="1861680">to</span> <span m="1861800">actually</span>
  <span m="1862040">define</span> <span m="1862880">the</span> <span m="1862970">kinetics</span>
  <span m="1863510">of</span> <span m="1863570">bodies</span> <span m="1863990">in</span>
  <span m="1864080">curved</span> <span m="1864330">spacetime.</span> <span m="1866470">There's</span>
  <span m="1866620">a</span> <span m="1866680">tremendous</span> <span m="1867610">amount</span>
  <span m="1868180">of</span> <span m="1868540">work</span> <span m="1869380">being</span>
  <span m="1869680">done</span> <span m="1869950">by</span> <span m="1871630">all</span>
  <span m="1871780">sorts</span> <span m="1872020">of</span> <span m="1872110">things</span>
  <span m="1872560">these</span> <span m="1872800">days</span> <span m="1873040">that's</span>
  <span m="1873160">based</span> <span m="1873490">on</span> <span m="1873640">studies</span>
  <span m="1873970">of</span> <span m="1874450">orbits</span> <span m="1874840">in</span>
  <span m="1874930">curved</span> <span m="1875280">spacetime,</span> <span m="1876190">and</span>
  <span m="1876310">they</span> <span m="1876490">all</span> <span m="1876700">come</span>
  <span m="1876910">back</span> <span m="1877150">to</span> <span m="1877240">this</span>
  <span m="1877390">notion</span> <span m="1877720">of</span> <span m="1877810">parallel</span>
  <span m="1878200">transport.</span></p><p><span m="1879740">All</span> <span m="1879820">right.</span>
  <span m="1880000">Bear</span> <span m="1880120">with</span> <span m="1880210">me</span>
  <span m="1880300">a</span> <span m="1880330">second.</span> <span m="1880620">I</span>
  <span m="1880650">just</span> <span m="1880770">want to</span> <span m="1880870">take</span>
  <span m="1880990">a</span> <span m="1881020">sip</span> <span m="1881230">of</span>
  <span m="1881290">water.</span> <span m="1882160">And</span> <span m="1882280">then</span>
  <span m="1882550">I'm</span> <span m="1882640">going</span> <span m="1882760">to</span>
  <span m="1882820">talk</span> <span m="1883030">about</span> <span m="1883240">the</span>
  <span m="1883450">other</span> <span m="1883690">notion</span> <span m="1884020">of</span>
  <span m="1884080">transport,</span> <span m="1888270">which</span> <span m="1888450">we</span>
  <span m="1888540">are</span> <span m="1888600">going</span> <span m="1888720">to</span>
  <span m="1888810">discuss--</span> <span m="1890550">I</span> <span m="1890640">always</span>
  <span m="1890820">say,</span> <span m="1891000">briefly,</span> <span m="1891420">and</span>
  <span m="1891510">then</span> <span m="1891600">I</span> <span m="1891690">spend</span>
  <span m="1891900">three</span> <span m="1892110">pages</span> <span m="1892380">on
  it,</span> <span m="1892590">so</span> <span m="1892770">we're</span> <span m="1892890">going</span>
  <span m="1893010">to</span> <span m="1893070">discuss.</span></p><p><span m="1894970">All</span>
  <span m="1895060">right.</span> <span m="1896090">So</span> <span m="1896280">parallel</span>
  <span m="1896700">transport</span> <span m="1897360">is</span> <span m="1898860">extremely</span>
  <span m="1899460">important,</span> <span m="1899970">and</span> <span m="1900270">there's</span>
  <span m="1900420">a</span> <span m="1900480">huge</span> <span m="1900840">amount</span>
  <span m="1901050">of</span> <span m="1901110">physics</span> <span m="1901620">that</span>
  <span m="1901770">is</span> <span m="1901890">tied</span> <span m="1902220">up</span>
  <span m="1902370">in</span> <span m="1902460">this,</span> <span m="1904840">but</span>
  <span m="1904890">one</span> <span m="1905090">thing</span> <span m="1905330">which</span>
  <span m="1905460">I</span> <span m="1905550">really</span> <span m="1905820">want</span>
  <span m="1906000">to</span> <span m="1906060">emphasize</span> <span m="1907320">is</span>
  <span m="1907530">that</span> <span m="1907710">it</span> <span m="1907830">is</span>
  <span m="1908010">not</span> <span m="1908340">unique.</span> <span m="1909330">And</span>
  <span m="1909540">there</span> <span m="1909720">is</span> <span m="1909840">one</span>
  <span m="1910170">other</span> <span m="1910380">one</span> <span m="1910710">which</span>
  <span m="1910920">we are</span> <span m="1911130">going</span> <span m="1911370">to</span>
  <span m="1911490">really</span> <span m="1911850">use</span> <span m="1912210">to</span>
  <span m="1912270">define</span> <span m="1912940">one</span> <span m="1913770">particularly</span>
  <span m="1914490">important</span> <span m="1915180">notion,</span> <span m="1915750">instead</span>
  <span m="1916020">of</span> <span m="1916080">quantities,</span> <span m="1917070">for</span>
  <span m="1917280">our</span> <span m="1917520">class.</span> <span m="1930210">So</span>
  <span m="1930480">suppose</span> <span m="1930900">I've</span> <span m="1931020">got</span>
  <span m="1931230">my</span> <span m="1932340">curve</span> <span m="1932760">gamma,</span>
  <span m="1934020">and</span> <span m="1934140">I'm</span> <span m="1934320">going</span>
  <span m="1934530">to,</span> <span m="1934720">again,</span> <span m="1935440">take</span>
  <span m="1935520">advantage</span> <span m="1935880">of</span> <span m="1935940">the</span>
  <span m="1936000">fact</span> <span m="1936300">that</span> <span m="1936390">I</span>
  <span m="1936480">can</span> <span m="1937590">define</span> <span m="1940800">a</span>
  <span m="1941250">set</span> <span m="1941490">of</span> <span m="1941580">tick</span>
  <span m="1941880">marks</span> <span m="1942210">along</span> <span m="1942540">it</span>
  <span m="1943680">and</span> <span m="1944070">make</span> <span m="1944430">that</span>
  <span m="1945090">vector</span> <span m="1945360">U</span> <span m="1945660">be</span>
  <span m="1945810">the</span> <span m="1945900">tangent</span> <span m="1946380">to</span>
  <span m="1946470">this</span> <span m="1946650">curve.</span> <span m="1948190">And</span>
  <span m="1948750">I'm</span> <span m="1948840">going</span> <span m="1948960">to,</span>
  <span m="1949020">again,</span> <span m="1949470">have</span> <span m="1950820">my</span>
  <span m="1950970">favorite</span> <span m="1951300">points,</span> <span m="1952770">x</span>
  <span m="1952980">alpha</span> <span m="1953400">at</span> <span m="1953520">point</span>
  <span m="1953820">P</span> <span m="1959170">plus</span> <span m="1959860">dx</span>
  <span m="1960100">alpha</span> <span m="1960460">at</span> <span m="1960640">point</span>
  <span m="1960970">Q.</span></p><p><span m="1963520">There's</span> <span m="1963670">another</span>
  <span m="1964060">notion</span> <span m="1964420">of</span> <span m="1964480">transport</span>
  <span m="1965110">that</span> <span m="1965320">is--</span> <span m="1965560">basically</span>
  <span m="1966760">what</span> <span m="1966970">you</span> <span m="1967420">do</span>
  <span m="1967810">is</span> <span m="1968170">you</span> <span m="1968710">cheat,</span>
  <span m="1969520">and</span> <span m="1969640">you</span> <span m="1970030">imagine</span>
  <span m="1970600">that</span> <span m="1970780">moving</span> <span m="1971410">from</span>
  <span m="1972400">point</span> <span m="1973060">x</span> <span m="1973330">alpha</span>
  <span m="1974320">to</span> <span m="1974470">x</span> <span m="1974740">alpha</span>
  <span m="1975040">plus</span> <span m="1975400">dx</span> <span m="1976090">alpha</span>
  <span m="1976840">is</span> <span m="1976990">a</span> <span m="1977020">kind</span>
  <span m="1977410">of</span> <span m="1977470">coordinate</span> <span m="1977950">transformation.</span>
  <span m="1979910">So</span> <span m="1979930">let's</span> <span m="1980140">do</span>
  <span m="1980230">the</span> <span m="1980290">following.</span> <span m="1981790">Let's</span>
  <span m="1981970">say</span> <span m="1982270">that</span> <span m="1982480">x</span>
  <span m="1982780">alpha</span> <span m="1984520">plus</span> <span m="1987340">dx</span>
  <span m="1987580">alpha--</span> <span m="1990400">we're going to</span> <span m="1990610">take</span>
  <span m="1990790">advantage</span> <span m="1991060">of</span> <span m="1991120">the</span>
  <span m="1991180">fact</span> <span m="1991480">that,</span> <span m="1991570">since</span>
  <span m="1991750">we</span> <span m="1991900">have</span> <span m="1992530">this</span>
  <span m="1993310">tangent</span> <span m="1993820">notion</span> <span m="1994210">built</span>
  <span m="1994480">into</span> <span m="1995275">the</span> <span m="1995650">symbols</span>
  <span m="1996040">we've</span> <span m="1996190">defined,</span> <span m="2000770">we'll
  just</span> <span m="2000990">say</span> <span m="2001200">that</span> <span m="2001290">it's</span>
  <span m="2001380">going</span> <span m="2001490">to</span> <span m="2001590">be</span>
  <span m="2001760">the</span> <span m="2001860">tangent</span> <span m="2002580">times</span>
  <span m="2002840">the</span> <span m="2002910">interval</span> <span m="2003300">of</span>
  <span m="2004020">lambda.</span> <span m="2005580">And</span> <span m="2005850">what</span>
  <span m="2006090">I'm</span> <span m="2006390">going</span> <span m="2006630">to</span>
  <span m="2006750">do</span> <span m="2008460">is</span> <span m="2008700">define</span>
  <span m="2009180">this</span> <span m="2010050">as</span> <span m="2010200">a</span>
  <span m="2010230">new</span> <span m="2010440">coordinate</span> <span m="2010920">system,</span>
  <span m="2011390">x</span> <span m="2011580">prime.</span> <span m="2013750">So</span>
  <span m="2013800">that's</span> <span m="2014010">the</span> <span m="2014220">alpha</span>
  <span m="2014820">component</span> <span m="2016410">of</span> <span m="2016500">coordinate</span>
  <span m="2016800">system</span> <span m="2017100">x</span> <span m="2017330">prime.</span>
  <span m="2018750">It's</span> <span m="2018870">a</span> <span m="2018900">little</span>
  <span m="2019020">bit</span> <span m="2019110">weird</span> <span m="2020140">because</span>
  <span m="2020520">your</span> <span m="2020670">x</span> <span m="2020850">prime</span>
  <span m="2021330">has</span> <span m="2021540">a</span> <span m="2021600">differential</span>
  <span m="2022230">built</span> <span m="2022470">into</span> <span m="2022800">it.</span>
  <span m="2023640">Just bear</span> <span m="2023790">with</span> <span m="2023940">me.</span></p><p><span
  m="2026700">So</span> <span m="2026850">what we're</span> <span m="2026940">going</span>
  <span m="2027150">to</span> <span m="2027270">do</span> <span m="2028650">is</span>
  <span m="2028890">regard</span> <span m="2031140">the</span> <span m="2031260">shift,</span>
  <span m="2032390">or</span> <span m="2032490">the</span> <span m="2032580">transport,</span>
  <span m="2033750">if</span> <span m="2033840">you</span> <span m="2033930">prefer,</span>
  <span m="2034530">from</span> <span m="2034770">P to Q</span> <span m="2038150">as</span>
  <span m="2038310">a</span> <span m="2038370">coordinate</span> <span m="2038680">transformation.</span>
  <span m="2057780">It's</span> <span m="2058520">the</span> <span m="2058630">best</span>
  <span m="2058909">eraser, so</span> <span m="2059409">I'll</span> <span m="2059500">just</span>
  <span m="2059620">keep</span> <span m="2059800">using</span> <span m="2059909">it.</span>
  <span m="2066889">So</span> <span m="2066940">what</span> <span m="2067030">I</span>
  <span m="2067090">mean</span> <span m="2067330">by</span> <span m="2067480">that</span>
  <span m="2068440">is</span> <span m="2068980">I'm</span> <span m="2069310">going</span>
  <span m="2069610">to</span> <span m="2069760">regard</span> <span m="2074639">x</span>
  <span m="2074969">alpha,</span> <span m="2076040">and</span> <span m="2076139">I'm</span>
  <span m="2076239">going</span> <span m="2076340">to</span> <span m="2076440">use</span>
  <span m="2076500">a</span> <span m="2076590">slightly</span> <span m="2076980">different</span>
  <span m="2077250">symbol.</span> <span m="2078830">I</span> <span m="2078989">will</span>
  <span m="2079080">define</span> <span m="2079500">what</span> <span m="2079650">the</span>
  <span m="2079800">L</span> <span m="2080100">is.</span> <span m="2080610">So</span>
  <span m="2080699">this</span> <span m="2080850">is</span> <span m="2080969">transported,</span>
  <span m="2081659">but</span> <span m="2081750">I'm</span> <span m="2081810">going</span>
  <span m="2081889">to</span> <span m="2081960">put</span> <span m="2082110">an</span>
  <span m="2082260">L</span> <span m="2082469">in</span> <span m="2082560">here</span>
  <span m="2082739">for</span> <span m="2082920">reasons</span> <span m="2083280">that</span>
  <span m="2083400">I</span> <span m="2083460">will</span> <span m="2083550">define</span>
  <span m="2083909">in</span> <span m="2084000">just</span> <span m="2084210">a</span>
  <span m="2084270">moment.</span></p><p><span m="2088210">This,</span> <span m="2088530">from</span>
  <span m="2088710">P</span> <span m="2088810">to</span> <span m="2088949">Q,</span>
  <span m="2096400">is</span> <span m="2096560">what</span> <span m="2096770">I</span>
  <span m="2096860">get</span> <span m="2100760">if</span> <span m="2100940">I</span>
  <span m="2101120">regard</span> <span m="2102110">the</span> <span m="2102230">change</span>
  <span m="2102830">from</span> <span m="2103610">point</span> <span m="2103910">P</span>
  <span m="2104120">to</span> <span m="2104210">point</span> <span m="2104450">Q</span>
  <span m="2104840">as</span> <span m="2104960">a</span> <span m="2105020">simple</span>
  <span m="2105290">coordinate</span> <span m="2105620">transformation</span> <span
  m="2106370">and</span> <span m="2106610">do</span> <span m="2106850">my</span> <span
  m="2107060">usual</span> <span m="2107690">rule</span> <span m="2108050">for</span>
  <span m="2108680">changing</span> <span m="2109030">coordinate</span> <span m="2109370">representation.</span>
  <span m="2111670">So</span> <span m="2112420">expand</span> <span m="2112990">what</span>
  <span m="2113110">the</span> <span m="2113170">definition</span> <span m="2113740">of</span>
  <span m="2113860">x</span> <span m="2114070">prime</span> <span m="2114460">is</span>
  <span m="2114640">there,</span> <span m="2115950">and</span> <span m="2116200">what</span>
  <span m="2116350">you'll</span> <span m="2116440">see</span> <span m="2116770">is</span>
  <span m="2117070">that</span> <span m="2117340">you</span> <span m="2117460">get</span>
  <span m="2118660">a</span> <span m="2118720">term</span> <span m="2119200">that's</span>
  <span m="2119440">just</span> <span m="2119770">basically</span> <span m="2120700">dx</span>
  <span m="2121060">alpha</span> <span m="2121360">dx</span> <span m="2121720">beta.</span>
  <span m="2125570">Then</span> <span m="2125980">you're</span> <span m="2126130">going</span>
  <span m="2126300">to</span> <span m="2126370">get</span> <span m="2126490">something</span>
  <span m="2127000">that</span> <span m="2127180">looks</span> <span m="2127450">like</span>
  <span m="2128770">the</span> <span m="2128980">partial</span> <span m="2129340">derivative</span>
  <span m="2129790">of</span> <span m="2129850">that</span> <span m="2130000">tangent</span>
  <span m="2130420">vector.</span> <span m="2136990">And</span> <span m="2137100">remember,</span>
  <span m="2137460">this</span> <span m="2137640">is</span> <span m="2137820">being</span>
  <span m="2138180">acted</span> <span m="2138570">on.</span> <span m="2141030">I
  should've said</span> <span m="2142110">this</span> <span m="2142290">is</span>
  <span m="2142390">this</span> <span m="2142500">thing</span> <span m="2142750">evaluated</span>
  <span m="2143160">at</span> <span m="2143220">P.</span></p><p><span m="2148110">Great.</span>
  <span m="2148480">So</span> <span m="2148750">we</span> <span m="2148870">fill</span>
  <span m="2149050">this</span> <span m="2149230">out.</span> <span m="2168240">OK.</span>
  <span m="2174920">So</span> <span m="2175040">that's</span> <span m="2175220">what</span>
  <span m="2175340">I</span> <span m="2175430">get</span> <span m="2175730">when</span>
  <span m="2175910">I</span> <span m="2175970">use</span> <span m="2176330">this</span>
  <span m="2176900">notion</span> <span m="2177470">to</span> <span m="2177590">transport</span>
  <span m="2179760">the</span> <span m="2179850">field</span> <span m="2180270">from</span>
  <span m="2180480">P to</span> <span m="2180780">Q.</span></p><p><span m="2182100">Let's</span>
  <span m="2182370">think</span> <span m="2182550">about</span> <span m="2182760">it
  in</span> <span m="2182850">another</span> <span m="2183210">way.</span> <span m="2184110">Now,</span>
  <span m="2185790">these</span> <span m="2186090">fields</span> <span m="2186420">are</span>
  <span m="2186510">all</span> <span m="2186660">just</span> <span m="2186900">functions.</span>
  <span m="2188080">So</span> <span m="2188370">I</span> <span m="2188520">can</span>
  <span m="2188790">also</span> <span m="2190080">express</span> <span m="2190740">the</span>
  <span m="2190860">field</span> <span m="2191370">at</span> <span m="2191610">Q</span>
  <span m="2191985">in</span> <span m="2192360">terms</span> <span m="2192600">of</span>
  <span m="2192660">the</span> <span m="2192750">field</span> <span m="2193260">at</span>
  <span m="2193710">P</span> <span m="2194760">using</span> <span m="2195610">a</span>
  <span m="2195750">Taylor</span> <span m="2196140">expansion.</span> <span m="2199710">I'm</span>
  <span m="2199920">assuming</span> <span m="2200310">that</span> <span m="2200430">these</span>
  <span m="2200640">are</span> <span m="2200700">close</span> <span m="2201090">enough</span>
  <span m="2201390">that</span> <span m="2202500">everything</span> <span m="2202950">is</span>
  <span m="2203100">accurate</span> <span m="2203580">to</span> <span m="2203700">first</span>
  <span m="2204090">order</span> <span m="2204510">in</span> <span m="2204660">small</span>
  <span m="2204930">quantities,</span> <span m="2257840">so</span> <span m="2258290">nothing</span>
  <span m="2258680">controversial</span> <span m="2259280">about</span> <span m="2259520">this.</span>
  <span m="2260000">I'm</span> <span m="2260150">assuming</span> <span m="2260540">dx</span>
  <span m="2260690">is</span> <span m="2260930">small</span> <span m="2261200">enough</span>
  <span m="2261500">that</span> <span m="2261740">I</span> <span m="2261890">can</span>
  <span m="2267450">do</span> <span m="2267630">this.</span> <span m="2281990">But</span>
  <span m="2282140">now</span> <span m="2282290">I'm</span> <span m="2282350">going</span>
  <span m="2282560">to</span> <span m="2282650">get</span> <span m="2282860">rid</span>
  <span m="2283310">of</span> <span m="2283790">my</span> <span m="2284000">dx</span>
  <span m="2284390">beta</span> <span m="2285260">using</span> <span m="2286430">the</span>
  <span m="2286520">tangent</span> <span m="2286970">field</span> <span m="2287300">U.</span></p><p><span
  m="2307290">Now,</span> <span m="2308910">before</span> <span m="2309270">I</span>
  <span m="2309360">move</span> <span m="2309660">on,</span> <span m="2311760">I</span>
  <span m="2311860">just</span> <span m="2312030">want</span> <span m="2312150">to</span>
  <span m="2312210">emphasize--</span> <span m="2312810">these</span> <span m="2313320">two</span>
  <span m="2313590">boards</span> <span m="2314010">here,</span> <span m="2314280">over</span>
  <span m="2314640">the</span> <span m="2314700">way</span> <span m="2314820">the</span>
  <span m="2314940">left--</span> <span m="2315750">we're</span> <span m="2315870">talking</span>
  <span m="2316230">about</span> <span m="2316410">two</span> <span m="2316680">rather</span>
  <span m="2317100">different</span> <span m="2317340">quantities.</span> <span m="2318610">The</span>
  <span m="2318710">one</span> <span m="2318810">I</span> <span m="2318870">just</span>
  <span m="2319050">moved</span> <span m="2319260">to</span> <span m="2319350">the</span>
  <span m="2319440">top--</span> <span m="2320250">that</span> <span m="2320790">actually</span>
  <span m="2321390">is</span> <span m="2321900">the</span> <span m="2322050">field--</span>
  <span m="2322530">if</span> <span m="2322650">you</span> <span m="2322890">were</span>
  <span m="2328970">some kind</span> <span m="2329090">of</span> <span m="2329160">a</span>
  <span m="2329220">gadget</span> <span m="2329670">that</span> <span m="2329790">managed
  your</span> <span m="2330240">field</span> <span m="2330660">A--</span> <span m="2331620">that</span>
  <span m="2331830">would</span> <span m="2332010">tell</span> <span m="2332250">you</span>
  <span m="2332430">what</span> <span m="2332610">the</span> <span m="2332700">value</span>
  <span m="2333210">is</span> <span m="2333540">that</span> <span m="2333690">you</span>
  <span m="2333810">measure</span> <span m="2334740">at</span> <span m="2335580">point</span>
  <span m="2335970">Q.</span> <span m="2337110">This</span> <span m="2338070">would</span>
  <span m="2338250">tell</span> <span m="2338520">you--</span> <span m="2338850">what
  do</span> <span m="2338910">we</span> <span m="2339000">get</span> <span m="2339300">if</span>
  <span m="2339480">you</span> <span m="2339690">picked</span> <span m="2340260">P</span>
  <span m="2340710">up</span> <span m="2341580">and,</span> <span m="2341910">via</span>
  <span m="2342390">this</span> <span m="2342570">transport</span> <span m="2343140">mechanism,</span>
  <span m="2343680">moved</span> <span m="2344040">it</span> <span m="2344130">over</span>
  <span m="2344460">to</span> <span m="2344550">Q?</span> <span m="2345180">They</span>
  <span m="2345300">are</span> <span m="2345390">two</span> <span m="2346650">potentially</span>
  <span m="2347730">different</span> <span m="2348210">things.</span></p><p><span
  m="2349560">So</span> <span m="2349710">this</span> <span m="2349890">motivates</span>
  <span m="2350670">another</span> <span m="2351210">kind</span> <span m="2351690">of</span>
  <span m="2351900">derivative.</span> <span m="2375040">So</span> <span m="2375220">suppose</span>
  <span m="2376120">I</span> <span m="2378760">look</span> <span m="2379060">at</span>
  <span m="2380110">A--</span> <span m="2381400">value</span> <span m="2381730">it
  at</span> <span m="2381880">a</span> <span m="2381940">Q--</span> <span m="2384160">minus</span>
  <span m="2385090">A</span> <span m="2386170">transported--</span> <span m="2388810">whoops,</span>
  <span m="2389240">that's supposed to</span> <span m="2389440">be</span> <span m="2389530">transported</span>
  <span m="2390160">from</span> <span m="2390460">P to Q--</span> <span m="2399490">defined</span>
  <span m="2399880">by</span> <span m="2400030">D</span> <span m="2400240">lambda.</span>
  <span m="2402210">I</span> <span m="2402310">will</span> <span m="2402610">expand</span>
  <span m="2403030">this</span> <span m="2403180">out</span> <span m="2403330">in</span>
  <span m="2403420">just</span> <span m="2403630">a</span> <span m="2403660">moment.</span>
  <span m="2404440">Now</span> <span m="2404830">I</span> <span m="2404920">will,</span>
  <span m="2405040">at</span> <span m="2405130">last,</span> <span m="2405400">give</span>
  <span m="2405550">this</span> <span m="2405730">a</span> <span m="2405760">name.</span></p><p><span
  m="2406970">This</span> <span m="2409520">is</span> <span m="2409700">written</span>
  <span m="2409970">with</span> <span m="2410150">a</span> <span m="2410210">script</span>
  <span m="2410630">L.</span> <span m="2414620">This</span> <span m="2414750">is</span>
  <span m="2414870">known</span> <span m="2415140">as</span> <span m="2415440">the</span>
  <span m="2415620">Lie derivative</span> <span m="2421200">of</span> <span m="2421360">the</span>
  <span m="2421450">vector</span> <span m="2421940">A</span> <span m="2424580">along</span>
  <span m="2425360">U.</span> <span m="2427120">Anyone</span> <span m="2427930">heard
  of</span> <span m="2428170">the</span> <span m="2428290">Lie</span> <span m="2428530">derivative</span>
  <span m="2428820">before?</span> <span m="2430120">Yeah.</span> <span m="2431110">So</span>
  <span m="2431980">at</span> <span m="2432100">least</span> <span m="2432390">in</span>
  <span m="2432970">the</span> <span m="2433060">context</span> <span m="2433510">where</span>
  <span m="2433630">we're</span> <span m="2433780">going</span> <span m="2433860">to</span>
  <span m="2433930">be</span> <span m="2433990">using</span> <span m="2434260">it,</span>
  <span m="2434410">this</span> <span m="2434440">is</span> <span m="2434500">a</span>
  <span m="2434560">good</span> <span m="2434710">way</span> <span m="2434830">to</span>
  <span m="2434920">understand</span> <span m="2435280">what's</span> <span m="2435430">going</span>
  <span m="2435670">on</span> <span m="2435820">with</span> <span m="2435960">it.</span>
  <span m="2436750">We'll</span> <span m="2436900">see</span> <span m="2437170">how</span>
  <span m="2437470">it</span> <span m="2437560">is</span> <span m="2437710">used,</span>
  <span m="2438310">at</span> <span m="2438400">least in</span> <span m="2438630">8.962</span>
  <span m="2439420">in</span> <span m="2439510">just</span> <span m="2439660">a</span>
  <span m="2439690">few</span> <span m="2439930">moments.</span> <span m="2441730">Filling</span>
  <span m="2442090">in</span> <span m="2442180">the</span> <span m="2442270">details--</span>
  <span m="2442690">so</span> <span m="2442870">plug in</span> <span m="2443260">these</span>
  <span m="2443410">definitions,</span> <span m="2444670">subtract,</span> <span m="2445270">take</span>
  <span m="2445490">limits,</span> <span m="2445900">blah,</span> <span m="2446080">blah,</span>
  <span m="2446230">blah.</span> <span m="2447040">What</span> <span m="2447460">you</span>
  <span m="2447610">find</span> <span m="2453400">is</span> <span m="2453580">that</span>
  <span m="2453730">this</span> <span m="2454000">turns</span> <span m="2454360">out</span>
  <span m="2454540">to</span> <span m="2454660">be</span> <span m="2456380">U</span>
  <span m="2459170">contracted</span> <span m="2459710">on</span> <span m="2459950">the</span>
  <span m="2460040">partial</span> <span m="2460460">derivative</span> <span m="2460880">of</span>
  <span m="2461000">A</span> <span m="2462530">minus</span> <span m="2463100">A</span>
  <span m="2466340">contracted</span> <span m="2466820">on</span> <span m="2466970">the</span>
  <span m="2467060">partial</span> <span m="2467360">derivative</span> <span m="2467900">of</span>
  <span m="2468020">U.</span></p><p><span m="2473320">Exercise</span> <span m="2473980">for</span>
  <span m="2474070">the</span> <span m="2474160">reader--</span> <span m="2475530">it</span>
  <span m="2475630">is</span> <span m="2475780">actually</span> <span m="2476230">really</span>
  <span m="2476650">easy</span> <span m="2477010">to</span> <span m="2477160">show</span>
  <span m="2478540">that</span> <span m="2478720">you</span> <span m="2478870">can</span>
  <span m="2479020">promote</span> <span m="2479470">these</span> <span m="2479680">partial</span>
  <span m="2480070">derivatives</span> <span m="2482400">to</span> <span m="2482560">covariant</span>
  <span m="2483070">derivatives.</span> <span m="2500050">And</span> <span m="2500160">what</span>
  <span m="2500310">this</span> <span m="2500490">means</span> <span m="2501060">is</span>
  <span m="2501270">that,</span> <span m="2501450">when</span> <span m="2501630">you</span>
  <span m="2501750">evaluate</span> <span m="2502290">the</span> <span m="2502380">Lie
  derivative--</span> <span m="2503130">so</span> <span m="2503310">notice,</span>
  <span m="2503760">nowhere</span> <span m="2504240">in</span> <span m="2504360">here</span>
  <span m="2504630">did</span> <span m="2504750">I</span> <span m="2504840">introduce</span>
  <span m="2505230">anything</span> <span m="2505560">with</span> <span m="2505670">a</span>
  <span m="2505710">covariant</span> <span m="2506070">derivative.</span> <span m="2506430">There</span>
  <span m="2506520">was</span> <span m="2506610">no</span> <span m="2506850">connection,</span>
  <span m="2507300">nothing</span> <span m="2507570">going</span> <span m="2507780">on</span>
  <span m="2507960">there.</span> <span m="2508890">If</span> <span m="2508980">you</span>
  <span m="2509040">just</span> <span m="2509220">go</span> <span m="2509370">ahead</span>
  <span m="2509550">and</span> <span m="2509640">work</span> <span m="2509850">it</span>
  <span m="2509940">out,</span> <span m="2510110">basically,</span> <span m="2511320">when</span>
  <span m="2512430">you</span> <span m="2512520">expand</span> <span m="2512940">this</span>
  <span m="2513120">guy</span> <span m="2513360">out,</span> <span m="2513600">you'll</span>
  <span m="2513690">find</span> <span m="2514110">you</span> <span m="2514290">have</span>
  <span m="2514950">connection</span> <span m="2515400">coefficients</span> <span
  m="2515910">or</span> <span m="2515970">Christoffel</span> <span m="2516450">symbols</span>
  <span m="2516870">that</span> <span m="2517020">are</span> <span m="2517140">equal
  and</span> <span m="2517470">opposite</span> <span m="2517770">and</span> <span
  m="2517860">so</span> <span m="2517950">they</span> <span m="2518070">cancel</span>
  <span m="2518430">each</span> <span m="2518580">other.</span> <span m="2519270">So</span>
  <span m="2519480">you</span> <span m="2519600">can</span> <span m="2519720">just</span>
  <span m="2519870">go</span> <span m="2520110">from</span> <span m="2520290">partials</span>
  <span m="2520950">to</span> <span m="2521400">covariants.</span> <span m="2521930">Give
  me</span> <span m="2522110">just</span> <span m="2522220">a</span> <span m="2522290">second,</span>
  <span m="2522750">Trey.</span> <span m="2524070">And</span> <span m="2524220">this</span>
  <span m="2524370">is</span> <span m="2524460">telling</span> <span m="2524730">us</span>
  <span m="2524880">that</span> <span m="2525000">the</span> <span m="2525090">Lie</span>
  <span m="2525450">derivative</span> <span m="2525990">is</span> <span m="2526170">perfectly</span>
  <span m="2526840">tensorial.</span> <span m="2528800">So</span> <span m="2529800">the</span>
  <span m="2529890">Lie</span> <span m="2530160">derivative</span> <span m="2530550">of</span>
  <span m="2530650">the</span> <span m="2530700">vector</span> <span m="2531000">field</span>
  <span m="2531330">is</span> <span m="2531780">also</span> <span m="2532200">a</span>
  <span m="2532290">tensor</span> <span m="2532590">quantity.</span> <span m="2533610">You</span>
  <span m="2533730">were</span> <span m="2534030">asking</span> <span m="2534210">a</span>
  <span m="2534240">question,</span> <span m="2534630">Trey.</span></p><p><span m="2536681">AUDIENCE:</span>
  <span m="2536925">In</span> <span m="2537170">the</span> <span m="2537330">second</span>
  <span m="2537630">term,</span> <span m="2538320">did</span> <span m="2538470">you</span>
  <span m="2538620">miss</span> <span m="2539170">the</span> <span m="2539580">D lambda?</span></p><p><span
  m="2544560">SCOTT HUGHES:</span> <span m="2544740">I did.</span> <span m="2545130">Yes,</span>
  <span m="2545310">I</span> <span m="2545370">did.</span> <span m="2545550">Thank</span>
  <span m="2545760">you.</span> <span m="2546300">There</span> <span m="2546450">should</span>
  <span m="2546600">be</span> <span m="2546780">a</span> <span m="2546960">D</span>
  <span m="2547200">lambda</span> <span m="2548580">right</span> <span m="2548760">here.</span>
  <span m="2548970">Thank</span> <span m="2549210">you.</span> <span m="2549850">Yes.</span>
  <span m="2550780">Yeah.</span> <span m="2551040">If</span> <span m="2551160">you</span>
  <span m="2551220">don't</span> <span m="2551400">have</span> <span m="2551580">that,</span>
  <span m="2553030">then</span> <span m="2553350">you</span> <span m="2553560">get</span>
  <span m="2553830">what</span> <span m="2554010">is</span> <span m="2554130">technically</span>
  <span m="2554490">called</span> <span m="2554940">&quot;crap.&quot;</span> <span
  m="2555670">So</span> <span m="2556020">thank</span> <span m="2556260">you</span>
  <span m="2556320">for</span> <span m="2556440">pointing</span> <span m="2556650">that</span>
  <span m="2556770">out.</span></p><p><span m="2558360">For</span> <span m="2558570">reasons</span>
  <span m="2559170">that</span> <span m="2560910">I</span> <span m="2561060">hope</span>
  <span m="2562830">you</span> <span m="2562980">have</span> <span m="2563190">probably</span>
  <span m="2563670">seen</span> <span m="2564000">before,</span> <span m="2568230">you</span>
  <span m="2568380">always</span> <span m="2568680">compute</span> <span m="2569070">the</span>
  <span m="2569160">Lie</span> <span m="2569490">derivative</span> <span m="2569850">of</span>
  <span m="2570540">some</span> <span m="2570780">kind</span> <span m="2571230">of</span>
  <span m="2571290">an</span> <span m="2571440">object</span> <span m="2572100">along</span>
  <span m="2572760">a</span> <span m="2572820">vector</span> <span m="2573240">field.</span>
  <span m="2578080">So</span> <span m="2578130">when</span> <span m="2578280">you're</span>
  <span m="2578350">computing</span> <span m="2578670">the</span> <span m="2578760">Lie</span>
  <span m="2579000">derivative</span> <span m="2579480">of</span> <span m="2579620">a</span>
  <span m="2579660">vector</span> <span m="2579990">field</span> <span m="2580530">along</span>
  <span m="2580830">a</span> <span m="2580890">vector,</span> <span m="2585640">sometimes</span>
  <span m="2586450">this</span> <span m="2586690">is</span> <span m="2586840">written</span>
  <span m="2588310">using</span> <span m="2588700">a</span> <span m="2588760">commutator.</span>
  <span m="2590500">I</span> <span m="2590680">just throw</span> <span m="2590830">that</span>
  <span m="2590950">out</span> <span m="2591100">there</span> <span m="2591210">because</span>
  <span m="2591340">you</span> <span m="2591430">may</span> <span m="2591520">encounter</span>
  <span m="2591970">this</span> <span m="2592180">in</span> <span m="2592270">some</span>
  <span m="2592420">of</span> <span m="2592510">your</span> <span m="2592600">readings.</span>
  <span m="2602550">It looks</span> <span m="2602710">like this.</span></p><p><span
  m="2605820">So</span> <span m="2606770">let</span> <span m="2606940">me</span> <span
  m="2607050">just</span> <span m="2607170">do</span> <span m="2607470">a</span> <span
  m="2607530">few</span> <span m="2607920">more</span> <span m="2608490">things</span>
  <span m="2608790">that</span> <span m="2608880">are</span> <span m="2608940">essentially</span>
  <span m="2609270">fleshing</span> <span m="2609660">out</span> <span m="2609780">the</span>
  <span m="2609840">definition</span> <span m="2610410">of</span> <span m="2610470">this.</span>
  <span m="2610620">So</span> <span m="2610800">I'm</span> <span m="2610920">not</span>
  <span m="2611070">going</span> <span m="2611190">to</span> <span m="2611280">go</span>
  <span m="2611430">through</span> <span m="2611910">and</span> <span m="2612060">apply</span>
  <span m="2612420">this</span> <span m="2612570">definition</span> <span m="2613120">very</span>
  <span m="2613200">carefully</span> <span m="2613650">to</span> <span m="2614250">higher</span>
  <span m="2614580">order</span> <span m="2614880">objects.</span> <span m="2615840">What</span>
  <span m="2616050">I</span> <span m="2616140">will</span> <span m="2616260">just</span>
  <span m="2616380">say</span> <span m="2616620">is</span> <span m="2616770">that,</span>
  <span m="2616890">if</span> <span m="2617040">I</span> <span m="2617130">repeat</span>
  <span m="2617550">this</span> <span m="2617730">exercise</span> <span m="2619980">and,</span>
  <span m="2620340">instead</span> <span m="2621210">of</span> <span m="2621750">having</span>
  <span m="2623370">a</span> <span m="2623460">vector</span> <span m="2623850">field</span>
  <span m="2624180">that</span> <span m="2624390">I'm transporting</span> <span m="2624960">from</span>
  <span m="2625080">point</span> <span m="2625290">to</span> <span m="2625350">point,</span>
  <span m="2625560">suppose</span> <span m="2625770">I</span> <span m="2625830">do</span>
  <span m="2625920">it</span> <span m="2626010">for</span> <span m="2626130">a</span>
  <span m="2626160">scalar</span> <span m="2626610">field--</span> <span m="2642360">well,</span>
  <span m="2642570">what</span> <span m="2642700">you</span> <span m="2642790">actually</span>
  <span m="2643090">get--</span> <span m="2643270">pardon</span> <span m="2643510">me</span>
  <span m="2643600">for</span> <span m="2643720">a</span> <span m="2643750">second--</span>
  <span m="2644750">is</span> <span m="2645070">this</span> <span m="2645370">on</span>
  <span m="2645640">the</span> <span m="2645730">partial,</span> <span m="2648940">but</span>
  <span m="2649240">the</span> <span m="2649330">partial</span> <span m="2649660">derivative</span>
  <span m="2650590">of</span> <span m="2650680">a</span> <span m="2650740">scalar</span>
  <span m="2651580">is</span> <span m="2651790">the</span> <span m="2651880">covariant</span>
  <span m="2652270">derivative</span> <span m="2652900">because</span> <span m="2653110">there's</span>
  <span m="2653260">no</span> <span m="2653650">Christoffel</span> <span m="2654160">that</span>
  <span m="2654250">couples</span> <span m="2654580">in.</span></p><p><span m="2661840">If</span>
  <span m="2662050">you</span> <span m="2662500">do</span> <span m="2662740">this</span>
  <span m="2663010">for</span> <span m="2663310">a</span> <span m="2663490">one-form,</span>
  <span m="2667820">where</span> <span m="2668120">it's</span> <span m="2668270">a</span>
  <span m="2668690">1</span> <span m="2668990">indexed</span> <span m="2669320">object</span>
  <span m="2669650">in</span> <span m="2669710">the</span> <span m="2669800">downstairs</span>
  <span m="2670310">position,</span> <span m="2688910">you get</span> <span m="2689270">something
  that</span> <span m="2689370">looks</span> <span m="2689550">like</span> <span m="2689700">this.</span>
  <span m="2691030">And</span> <span m="2691080">again,</span> <span m="2691470">when</span>
  <span m="2693180">you</span> <span m="2693640">expand</span> <span m="2693910">out</span>
  <span m="2694020">your</span> <span m="2694120">covariant</span> <span m="2694460">derivatives,</span>
  <span m="2694980">you</span> <span m="2695100">find</span> <span m="2695400">that</span>
  <span m="2695550">your</span> <span m="2696060">Christoffel</span> <span m="2696490">symbols</span>
  <span m="2696810">cancel</span> <span m="2697170">each</span> <span m="2697350">other</span>
  <span m="2697590">out.</span> <span m="2698530">And</span> <span m="2698550">so,</span>
  <span m="2699270">if</span> <span m="2699450">you</span> <span m="2699660">like,</span>
  <span m="2700050">you</span> <span m="2700140">can</span> <span m="2700290">just</span>
  <span m="2700440">go</span> <span m="2700560">ahead</span> <span m="2700740">and</span>
  <span m="2700830">replace</span> <span m="2701280">these</span> <span m="2703110">with</span>
  <span m="2703290">partials.</span></p><p><span m="2705540">And</span> <span m="2705720">likewise,</span>
  <span m="2706120">let</span> <span m="2706240">me</span> <span m="2706350">just</span>
  <span m="2706470">write</span> <span m="2706650">one</span> <span m="2706890">more</span>
  <span m="2707040">out</span> <span m="2707160">for</span> <span m="2707250">completeness.</span>
  <span m="2711030">Apply</span> <span m="2711330">this</span> <span m="2711450">to</span>
  <span m="2711570">a</span> <span m="2711630">tensor.</span> <span m="2727040">So</span>
  <span m="2727250">it's</span> <span m="2727430">a</span> <span m="2727490">very</span>
  <span m="2728060">similar</span> <span m="2728720">kind</span> <span m="2729080">of</span>
  <span m="2729170">structure</span> <span m="2730280">to</span> <span m="2730430">what</span>
  <span m="2730580">you</span> <span m="2730700">saw</span> <span m="2731000">when</span>
  <span m="2731210">we</span> <span m="2731330">did</span> <span m="2731540">the</span>
  <span m="2731630">covariant</span> <span m="2732170">derivative</span> <span m="2734030">in</span>
  <span m="2734270">which</span> <span m="2736190">every</span> <span m="2736550">index</span>
  <span m="2737180">essentially</span> <span m="2737660">gets</span> <span m="2738530">corrected</span>
  <span m="2739790">by</span> <span m="2740270">a</span> <span m="2740420">factor</span>
  <span m="2740780">that</span> <span m="2740900">looks</span> <span m="2741440">like</span>
  <span m="2741620">the</span> <span m="2741680">covariant</span> <span m="2742130">derivative</span>
  <span m="2742700">of</span> <span m="2742790">the</span> <span m="2742880">field</span>
  <span m="2743270">that</span> <span m="2743390">you</span> <span m="2743530">are</span>
  <span m="2743600">differentiating</span> <span m="2744290">along.</span> <span m="2744920">The</span>
  <span m="2745220">signs</span> <span m="2745610">are</span> <span m="2745670">a</span>
  <span m="2745730">little</span> <span m="2745850">bit</span> <span m="2745940">different.</span>
  <span m="2746430">So</span> <span m="2747290">it's</span> <span m="2747890">a</span>
  <span m="2747950">similar</span> <span m="2748310">tune,</span> <span m="2750110">but</span>
  <span m="2750410">it's</span> <span m="2750590">in</span> <span m="2750710">a</span>
  <span m="2750770">different</span> <span m="2751070">key.</span></p><p><span m="2757500">OK,</span>
  <span m="2762570">so</span> <span m="2763710">that's</span> <span m="2763920">great.</span>
  <span m="2764490">And</span> <span m="2766305">if</span> <span m="2766740">you</span>
  <span m="2766830">get</span> <span m="2766980">your</span> <span m="2767070">jollies</span>
  <span m="2767520">just</span> <span m="2767730">understanding</span> <span m="2768180">different</span>
  <span m="2768450">mathematical</span> <span m="2768960">transport</span> <span m="2769410">operations,</span>
  <span m="2769950">maybe</span> <span m="2770130">this</span> <span m="2770250">is</span>
  <span m="2770340">already</span> <span m="2770580">fun</span> <span m="2770820">enough.</span>
  <span m="2773610">But</span> <span m="2773730">we're</span> <span m="2773880">in</span>
  <span m="2773940">a</span> <span m="2774000">physics</span> <span m="2774270">class,</span>
  <span m="2774610">and</span> <span m="2774720">so</span> <span m="2774960">the</span>
  <span m="2775050">question</span> <span m="2775410">that</span> <span m="2775560">should</span>
  <span m="2775770">be</span> <span m="2775950">to</span> <span m="2776040">your</span>
  <span m="2776130">mind</span> <span m="2776460">is,</span> <span m="2777690">is</span>
  <span m="2777870">there</span> <span m="2778020">a</span> <span m="2778080">point</span>
  <span m="2778500">to</span> <span m="2778740">all</span> <span m="2778890">this</span>
  <span m="2779070">analysis?</span></p><p><span m="2780910">So</span> <span m="2782700">in</span>
  <span m="2782850">fact,</span> <span m="2785610">the</span> <span m="2785630">most</span>
  <span m="2786020">important</span> <span m="2786560">application</span> <span m="2787250">of</span>
  <span m="2787310">the</span> <span m="2787370">Lie derivative</span> <span m="2788720">for</span>
  <span m="2789350">our</span> <span m="2789650">purposes--</span> <span m="2793040">in</span>
  <span m="2793190">probably</span> <span m="2794030">the</span> <span m="2794180">last</span>
  <span m="2794630">lecture</span> <span m="2795050">or</span> <span m="2795140">two,</span>
  <span m="2796130">I</span> <span m="2796280">will</span> <span m="2796490">describe</span>
  <span m="2799550">some</span> <span m="2800810">stuff</span> <span m="2801200">related</span>
  <span m="2801590">to</span> <span m="2801680">modern</span> <span m="2802130">research</span>
  <span m="2802610">that</span> <span m="2802730">uses</span> <span m="2803030">it</span>
  <span m="2803090">quite</span> <span m="2803420">heavily.</span> <span m="2803810">But</span>
  <span m="2803900">to</span> <span m="2803990">begin</span> <span m="2804290">with</span>
  <span m="2804470">in</span> <span m="2804560">our</span> <span m="2804650">class,</span>
  <span m="2805730">the</span> <span m="2805820">most</span> <span m="2806120">important</span>
  <span m="2807230">application</span> <span m="2807980">will</span> <span m="2808220">be</span>
  <span m="2811190">when</span> <span m="2811340">we</span> <span m="2811460">consider</span>
  <span m="2811880">cases</span> <span m="2821280">where,</span> <span m="2821610">when</span>
  <span m="2821850">I</span> <span m="2821940">compute</span> <span m="2822420">the</span>
  <span m="2822540">Lie</span> <span m="2822810">derivative</span> <span m="2823440">of</span>
  <span m="2823530">some</span> <span m="2823860">tensor</span> <span m="2825880">along</span>
  <span m="2826960">a</span> <span m="2827070">vector</span> <span m="2827580">U</span>
  <span m="2828270">and</span> <span m="2828420">I</span> <span m="2828510">get</span>
  <span m="2828720">0.</span> <span m="2845320">I'm</span> <span m="2845470">just</span>
  <span m="2845580">going</span> <span m="2845630">to</span> <span m="2845780">leave</span>
  <span m="2845890">it</span> <span m="2845970">schematic</span> <span m="2846530">like</span>
  <span m="2846740">that.</span> <span m="2846890">So</span> <span m="2847100">L U</span>
  <span m="2848090">of</span> <span m="2848390">the</span> <span m="2848480">tensor</span>
  <span m="2848990">is</span> <span m="2849170">equal</span> <span m="2849410">to</span>
  <span m="2849530">0.</span></p><p><span m="2850400">If</span> <span m="2850550">this</span>
  <span m="2850790">is</span> <span m="2850910">the</span> <span m="2851000">case,</span>
  <span m="2853140">we</span> <span m="2853280">say</span> <span m="2853640">that</span>
  <span m="2853970">the</span> <span m="2854060">tensor</span> <span m="2854660">is</span>
  <span m="2855290">Lie</span> <span m="2855920">transported.</span> <span m="2872940">This
  is,</span> <span m="2873150">incidentally,</span> <span m="2873570">just</span>
  <span m="2873720">a</span> <span m="2873780">brief</span> <span m="2873990">aside.</span>
  <span m="2874350">It</span> <span m="2874440">shows</span> <span m="2874770">up</span>
  <span m="2874890">a</span> <span m="2874950">lot</span> <span m="2875280">in</span>
  <span m="2875520">fluid</span> <span m="2875880">dynamics.</span> <span m="2876900">In</span>
  <span m="2877020">that</span> <span m="2877200">case,</span> <span m="2877530">U</span>
  <span m="2878010">often</span> <span m="2878400">defines</span> <span m="2880200">the</span>
  <span m="2880290">flow</span> <span m="2880620">lines</span> <span m="2881670">associated
  with</span> <span m="2882090">the</span> <span m="2882180">velocity</span> <span
  m="2882660">field</span> <span m="2883110">of</span> <span m="2883290">some</span>
  <span m="2883470">kind</span> <span m="2883650">of</span> <span m="2883740">a</span>
  <span m="2883770">fluid</span> <span m="2884160">that</span> <span m="2884280">is</span>
  <span m="2884370">flowing</span> <span m="2884700">through</span> <span m="2884940">your</span>
  <span m="2885600">physical</span> <span m="2885960">situation.</span> <span m="2887070">And</span>
  <span m="2887340">you</span> <span m="2887490">would</span> <span m="2887640">be</span>
  <span m="2887730">interested</span> <span m="2888030">in</span> <span m="2888090">the</span>
  <span m="2888180">behavior</span> <span m="2888600">of</span> <span m="2888930">all</span>
  <span m="2889200">sorts</span> <span m="2889470">of</span> <span m="2889530">quantities</span>
  <span m="2890910">that</span> <span m="2891300">are</span> <span m="2891660">embedded</span>
  <span m="2892200">in</span> <span m="2892320">that</span> <span m="2892500">fluid.</span>
  <span m="2893530">And</span> <span m="2894190">as</span> <span m="2894370">we're</span>
  <span m="2894450">going</span> <span m="2894570">to</span> <span m="2894630">see,</span>
  <span m="2894930">when</span> <span m="2895200">you</span> <span m="2895350">find</span>
  <span m="2895890">that</span> <span m="2896520">those</span> <span m="2896850">quantities</span>
  <span m="2897360">are</span> <span m="2897480">Lie</span> <span m="2897690">transported</span>
  <span m="2898230">in</span> <span m="2898290">this</span> <span m="2898440">way,</span>
  <span m="2899010">there</span> <span m="2899220">is</span> <span m="2899460">a</span>
  <span m="2899610">powerful</span> <span m="2900480">physical</span> <span m="2901530">outcome</span>
  <span m="2901920">associated</span> <span m="2902430">with</span> <span m="2902550">that,</span>
  <span m="2902850">which</span> <span m="2903060">we</span> <span m="2903150">are</span>
  <span m="2903240">going</span> <span m="2903360">to</span> <span m="2903450">derive</span>
  <span m="2903810">in</span> <span m="2903960">just</span> <span m="2904170">a</span>
  <span m="2904230">moment.</span></p><p><span m="2905410">So</span> <span m="2907230">suppose</span>
  <span m="2908760">I,</span> <span m="2908940">in</span> <span m="2909030">fact,</span>
  <span m="2909420">have</span> <span m="2909750">a</span> <span m="2909810">tensor</span>
  <span m="2912820">that</span> <span m="2913120">is</span> <span m="2913510">Lie</span>
  <span m="2913760">transported.</span> <span m="2945290">So</span> <span m="2945410">suppose</span>
  <span m="2945680">I</span> <span m="2945740">have</span> <span m="2945860">some</span>
  <span m="2946040">tensor</span> <span m="2946400">that</span> <span m="2946550">is</span>
  <span m="2946820">Lie</span> <span m="2947030">transported.</span> <span m="2948170">If</span>
  <span m="2948320">that's</span> <span m="2948620">the</span> <span m="2948710">case,</span>
  <span m="2956090">what</span> <span m="2956140">I</span> <span m="2956260">can</span>
  <span m="2956440">do</span> <span m="2956830">is</span> <span m="2957100">define</span>
  <span m="2958000">a</span> <span m="2958060">particular</span> <span m="2958510">coordinate</span>
  <span m="2958990">system</span> <span m="2959740">centered</span> <span m="2960490">on</span>
  <span m="2960850">the</span> <span m="2960970">curve</span> <span m="2961720">for</span>
  <span m="2961900">which</span> <span m="2962110">U</span> <span m="2962290">is</span>
  <span m="2962410">the</span> <span m="2962470">tangent.</span></p><p><span m="2982840">So</span>
  <span m="2982990">what</span> <span m="2983140">I'm</span> <span m="2983230">going</span>
  <span m="2983410">to</span> <span m="2983500">do</span> <span m="2983830">is</span>
  <span m="2984250">I'm</span> <span m="2984490">going</span> <span m="2984760">to</span>
  <span m="2984820">define</span> <span m="2985840">this</span> <span m="2986140">curve</span>
  <span m="2986770">such</span> <span m="2987250">that</span> <span m="2988060">x0</span>
  <span m="2990820">is</span> <span m="2991150">equal</span> <span m="2991510">to</span>
  <span m="2992170">lambda,</span> <span m="2993040">that</span> <span m="2993670">parameter</span>
  <span m="2994330">that</span> <span m="2994720">defines</span> <span m="2995350">my</span>
  <span m="2995560">length</span> <span m="2996040">along</span> <span m="2996310">the</span>
  <span m="2996370">curve</span> <span m="2996850">in</span> <span m="2996940">a</span>
  <span m="2997000">way</span> <span m="2997210">that,</span> <span m="2997810">I</span>
  <span m="2997930">will</span> <span m="2998140">admit</span> <span m="2998410">I've</span>
  <span m="2998530">not</span> <span m="2998710">made</span> <span m="2998950">very</span>
  <span m="2999160">precise</span> <span m="2999610">yet</span> <span m="2999850">but</span>
  <span m="3000000">will</span> <span m="3000210">soon.</span> <span m="3007130">And</span>
  <span m="3007310">then</span> <span m="3007460">I'm</span> <span m="3007550">going</span>
  <span m="3007730">to</span> <span m="3007820">require</span> <span m="3008900">that</span>
  <span m="3010530">my</span> <span m="3010690">other</span> <span m="3010810">three</span>
  <span m="3012770">coordinates</span> <span m="3013370">are</span> <span m="3013520">all</span>
  <span m="3013700">constant</span> <span m="3014420">on</span> <span m="3014600">that</span>
  <span m="3014750">curve.</span> <span m="3020820">So</span> <span m="3020970">if</span>
  <span m="3021060">I</span> <span m="3021150">do</span> <span m="3021390">that,</span>
  <span m="3035330">then</span> <span m="3041490">my</span> <span m="3041640">tangent</span>
  <span m="3042090">vector</span> <span m="3042750">is</span> <span m="3043050">simply</span>
  <span m="3046540">delta</span> <span m="3047100">x0.</span> <span m="3047780">In</span>
  <span m="3047880">other</span> <span m="3047890">words,</span> <span m="3048860">it's</span>
  <span m="3048880">only</span> <span m="3049120">got</span> <span m="3049330">one</span>
  <span m="3049900">non-trivial</span> <span m="3050470">component,</span> <span m="3050980">and</span>
  <span m="3051100">its</span> <span m="3051220">value</span> <span m="3051580">of</span>
  <span m="3051640">that</span> <span m="3051760">component</span> <span m="3052240">is</span>
  <span m="3052420">1.</span></p><p><span m="3058210">And</span> <span m="3058330">this</span>
  <span m="3058450">is</span> <span m="3058520">the</span> <span m="3058570">constant.</span>
  <span m="3059650">So</span> <span m="3062086">the</span> <span m="3062470">derivatives
  of</span> <span m="3062800">the</span> <span m="3062890">tangent</span> <span m="3063250">field</span>
  <span m="3063580">are</span> <span m="3063730">all</span> <span m="3063940">equal</span>
  <span m="3064120">to</span> <span m="3064180">0.</span> <span m="3066520">And</span>
  <span m="3066610">when</span> <span m="3066730">you</span> <span m="3066790">trace</span>
  <span m="3067180">this</span> <span m="3067360">through</span> <span m="3067660">all</span>
  <span m="3068020">of</span> <span m="3068140">our</span> <span m="3068200">various</span>
  <span m="3068590">definitions,</span> <span m="3086360">what</span> <span m="3086510">you</span>
  <span m="3086630">find</span> <span m="3087080">is</span> <span m="3087410">that</span>
  <span m="3087530">it</span> <span m="3087620">boils</span> <span m="3087980">down</span>
  <span m="3088280">to</span> <span m="3088490">just</span> <span m="3088790">looking</span>
  <span m="3089300">at</span> <span m="3089450">how</span> <span m="3089870">the</span>
  <span m="3089990">tensor field</span> <span m="3090770">varies</span> <span m="3091970">with</span>
  <span m="3092210">respect</span> <span m="3092720">to</span> <span m="3092810">that</span>
  <span m="3092990">parameter</span> <span m="3093590">along</span> <span m="3093980">the</span>
  <span m="3094070">curve</span> <span m="3094430">itself.</span> <span m="3096350">If</span>
  <span m="3096470">it's</span> <span m="3096590">Lie</span> <span m="3096800">transported,</span>
  <span m="3098210">then</span> <span m="3098390">this</span> <span m="3098600">is</span>
  <span m="3098720">equal</span> <span m="3098930">to</span> <span m="3099080">0.</span></p><p><span
  m="3102600">And</span> <span m="3102720">so</span> <span m="3102900">this</span>
  <span m="3103260">means</span> <span m="3104070">that,</span> <span m="3104750">whatever</span>
  <span m="3105990">x0</span> <span m="3106500">represents,</span> <span m="3107870">it's</span>
  <span m="3108090">going</span> <span m="3108220">to</span> <span m="3108300">be</span>
  <span m="3108450">a</span> <span m="3108570">constant</span> <span m="3109650">along</span>
  <span m="3110040">that</span> <span m="3110220">curve</span> <span m="3113010">with</span>
  <span m="3113160">respect</span> <span m="3113430">to</span> <span m="3113520">this</span>
  <span m="3113670">tensor field.</span> <span m="3119060">Oh,</span> <span m="3119450">excuse
  me.</span> <span m="3121110">Screwed</span> <span m="3121370">that</span> <span
  m="3121520">up.</span> <span m="3125470">The</span> <span m="3125620">tensor</span>
  <span m="3126310">does</span> <span m="3126880">not</span> <span m="3127360">vary</span>
  <span m="3131430">with</span> <span m="3131670">this</span> <span m="3131820">parameter</span>
  <span m="3133140">along</span> <span m="3133470">the</span> <span m="3133560">curve.</span></p><p><span
  m="3147070">This</span> <span m="3147250">was</span> <span m="3147370">a</span>
  <span m="3147400">lot,</span> <span m="3148240">so</span> <span m="3148360">let's</span>
  <span m="3148540">just</span> <span m="3148720">step</span> <span m="3149050">back</span>
  <span m="3149800">and</span> <span m="3149920">think</span> <span m="3150100">about</span>
  <span m="3150310">what</span> <span m="3150490">this</span> <span m="3150670">is</span>
  <span m="3150730">saying.</span> <span m="3152380">One</span> <span m="3152590">of</span>
  <span m="3152650">the</span> <span m="3152710">most</span> <span m="3153160">important</span>
  <span m="3153970">things</span> <span m="3154420">that</span> <span m="3154540">we</span>
  <span m="3154690">do</span> <span m="3154960">in</span> <span m="3155110">physics</span>
  <span m="3157210">when we're</span> <span m="3157300">trying</span> <span m="3157540">to</span>
  <span m="3157600">analyze</span> <span m="3158080">systems</span> <span m="3158740">is</span>
  <span m="3159040">we</span> <span m="3159160">try</span> <span m="3159410">to</span>
  <span m="3159520">identify</span> <span m="3160120">quantities</span> <span m="3160720">that</span>
  <span m="3160960">are</span> <span m="3161350">constants</span> <span m="3161980">of</span>
  <span m="3162040">the</span> <span m="3162130">motion.</span> <span m="3164080">This</span>
  <span m="3164340">is</span> <span m="3164580">really</span> <span m="3165090">tricky</span>
  <span m="3165660">in</span> <span m="3165810">a</span> <span m="3165870">curved</span>
  <span m="3166360">spacetime</span> <span m="3167340">because</span> <span m="3169200">much</span>
  <span m="3169410">of</span> <span m="3169500">our</span> <span m="3169560">intuition</span>
  <span m="3170430">gets</span> <span m="3172440">garbled</span> <span m="3173400">by</span>
  <span m="3173880">all</span> <span m="3174270">of</span> <span m="3174360">the</span>
  <span m="3174450">facts</span> <span m="3174840">that</span> <span m="3175350">different</span>
  <span m="3175620">points</span> <span m="3175920">have</span> <span m="3176010">different</span>
  <span m="3176250">tangent</span> <span m="3176760">spaces.</span> <span m="3178530">You</span>
  <span m="3178710">worry</span> <span m="3179100">about</span> <span m="3179370">whether</span>
  <span m="3179640">something</span> <span m="3180060">being</span> <span m="3180240">true,</span>
  <span m="3180750">and</span> <span m="3181180">is it</span> <span m="3181620">just</span>
  <span m="3182070">a</span> <span m="3182130">function</span> <span m="3182490">of</span>
  <span m="3182550">the</span> <span m="3182610">coordinate</span> <span m="3182970">system</span>
  <span m="3183240">that</span> <span m="3183330">I</span> <span m="3183420">wrote</span>
  <span m="3183660">this</span> <span m="3183840">out</span> <span m="3184080">in?</span>
  <span m="3184560">What</span> <span m="3184770">the</span> <span m="3184890">hell</span>
  <span m="3185070">is</span> <span m="3185190">going</span> <span m="3185460">on</span>
  <span m="3185670">here?</span> <span m="3187980">The</span> <span m="3188070">Lie
  derivative</span> <span m="3188940">is</span> <span m="3189150">giving</span> <span
  m="3189510">us</span> <span m="3189900">a</span> <span m="3190440">covariant,</span>
  <span m="3191250">frame-independent</span> <span m="3192390">way</span> <span m="3192750">of</span>
  <span m="3192900">identifying</span> <span m="3194190">things</span> <span m="3194850">that</span>
  <span m="3195030">are</span> <span m="3195180">constants</span> <span m="3196110">in</span>
  <span m="3196260">our</span> <span m="3196350">spacetime.</span></p><p><span m="3198250">So</span>
  <span m="3199330">we're</span> <span m="3199430">going to</span> <span m="3199520">wrap</span>
  <span m="3199800">up</span> <span m="3199890">this</span> <span m="3200040">discussion.</span>
  <span m="3202950">Let's</span> <span m="3203100">suppose</span> <span m="3203730">that</span>
  <span m="3204060">the</span> <span m="3204210">tensor</span> <span m="3204900">that</span>
  <span m="3205050">I'm</span> <span m="3205230">looking</span> <span m="3205500">at</span>
  <span m="3205620">here</span> <span m="3205890">is</span> <span m="3206100">called</span>
  <span m="3206610">the</span> <span m="3206730">metric.</span> <span m="3231470">Suppose</span>
  <span m="3232250">there</span> <span m="3232520">exists</span> <span m="3241910">a</span>
  <span m="3241990">vector</span> <span m="3242460">C</span> <span m="3245370">such</span>
  <span m="3245820">that</span> <span m="3246090">the</span> <span m="3246180">metric</span>
  <span m="3246600">is Lie</span> <span m="3246750">transported</span> <span m="3247560">along</span>
  <span m="3247870">this thing.</span></p><p><span m="3267310">What</span> <span m="3267460">does</span>
  <span m="3267580">this</span> <span m="3267760">tell</span> <span m="3267970">us?</span>
  <span m="3268420">So</span> <span m="3268570">first,</span> <span m="3269620">it</span>
  <span m="3269740">means</span> <span m="3271900">there</span> <span m="3272080">exists</span>
  <span m="3272920">some</span> <span m="3273370">coordinate</span> <span m="3283210">such</span>
  <span m="3283570">that</span> <span m="3290710">the</span> <span m="3290830">metric</span>
  <span m="3291280">does</span> <span m="3291640">not</span> <span m="3291940">vary.</span>
  <span m="3292270">The</span> <span m="3292390">metric</span> <span m="3292720">is</span>
  <span m="3292900">constant</span> <span m="3293520">with</span> <span m="3293650">respect</span>
  <span m="3293950">to</span> <span m="3294040">that</span> <span m="3294160">coordinate.</span>
  <span m="3295090">Essentially,</span> <span m="3295540">if</span> <span m="3295630">you</span>
  <span m="3295960">go</span> <span m="3296230">through</span> <span m="3297040">what</span>
  <span m="3297190">I</span> <span m="3297280">sketched</span> <span m="3297670">a</span>
  <span m="3297700">moment</span> <span m="3297940">ago,</span> <span m="3298120">this</span>
  <span m="3298270">is</span> <span m="3298360">telling</span> <span m="3298660">us</span>
  <span m="3298810">that</span> <span m="3298930">the</span> <span m="3299050">existence</span>
  <span m="3299920">of</span> <span m="3300190">this</span> <span m="3300700">kind</span>
  <span m="3301090">of a</span> <span m="3301210">vector,</span> <span m="3301610">which</span>
  <span m="3301660">I'm</span> <span m="3301720">going</span> <span m="3301820">to</span>
  <span m="3301900">give</span> <span m="3301990">a</span> <span m="3302050">name</span>
  <span m="3302290">to</span> <span m="3302470">in</span> <span m="3302560">just</span>
  <span m="3302740">a</span> <span m="3302800">moment--</span> <span m="3305240">the</span>
  <span m="3305320">existence</span> <span m="3305830">of</span> <span m="3305890">this</span>
  <span m="3306040">thing</span> <span m="3306280">demands</span> <span m="3307000">that</span>
  <span m="3307120">my</span> <span m="3307270">metric</span> <span m="3307720">is</span>
  <span m="3307870">constant with respect</span> <span m="3308650">to</span> <span
  m="3308800">some</span> <span m="3309220">coordinate.</span> <span m="3314360">I</span>
  <span m="3314520">am</span> <span m="3314640">not</span> <span m="3314850">going</span>
  <span m="3315000">to</span> <span m="3315090">prove</span> <span m="3315570">the</span>
  <span m="3315660">following</span> <span m="3316170">statement.</span> <span m="3316650">I</span>
  <span m="3316770">will</span> <span m="3316920">just</span> <span m="3317130">state</span>
  <span m="3317490">it,</span> <span m="3318750">because,</span> <span m="3319050">in</span>
  <span m="3319140">some</span> <span m="3319410">ways,</span> <span m="3319920">the</span>
  <span m="3320070">converse</span> <span m="3320850">of</span> <span m="3320910">that</span>
  <span m="3321060">statement</span> <span m="3322050">is</span> <span m="3322200">even</span>
  <span m="3322440">more</span> <span m="3322710">powerful.</span> <span m="3338690">If</span>
  <span m="3338960">there</span> <span m="3339200">is</span> <span m="3339410">a</span>
  <span m="3339500">coordinate,</span> <span m="3350520">such</span> <span m="3350940">that</span>
  <span m="3353610">dgd,</span> <span m="3354640">whatever</span> <span m="3354940">that</span>
  <span m="3355060">coordinate</span> <span m="3355440">is,</span> <span m="3356130">is</span>
  <span m="3356350">equal</span> <span m="3356560">to</span> <span m="3356650">0,</span>
  <span m="3361350">then</span> <span m="3361530">a</span> <span m="3361590">vector</span>
  <span m="3361890">field</span> <span m="3362190">of</span> <span m="3362250">this</span>
  <span m="3362400">type</span> <span m="3362700">exists.</span></p><p><span m="3374860">So</span>
  <span m="3374890">the</span> <span m="3374980">second</span> <span m="3375250">thing
  I</span> <span m="3375310">want</span> <span m="3375460">to</span> <span m="3375550">do</span>
  <span m="3375790">is</span> <span m="3376240">expand</span> <span m="3377080">the</span>
  <span m="3377200">Lie</span> <span m="3377440">derivative.</span> <span m="3385530">So</span>
  <span m="3385790">if</span> <span m="3385940">I</span> <span m="3386120">require</span>
  <span m="3387390">that</span> <span m="3387560">my</span> <span m="3387710">metric</span>
  <span m="3391360">be</span> <span m="3391480">transported</span> <span m="3392110">along</span>
  <span m="3392350">the</span> <span m="3392440">vector</span> <span m="3392810">C,</span>
  <span m="3396580">well,</span> <span m="3399040">insert</span> <span m="3399430">my</span>
  <span m="3399610">definition</span> <span m="3400330">of</span> <span m="3402850">the</span>
  <span m="3402940">Lie derivative.</span> <span m="3422570">Now,</span> <span m="3422720">what</span>
  <span m="3422900">is</span> <span m="3423290">the</span> <span m="3423410">main</span>
  <span m="3423860">defining</span> <span m="3424400">characteristic</span> <span
  m="3425120">of</span> <span m="3425180">the</span> <span m="3425270">covariant</span>
  <span m="3425690">derivative?</span> <span m="3426980">How</span> <span m="3427130">did</span>
  <span m="3427250">I</span> <span m="3427370">get</span> <span m="3427640">my</span>
  <span m="3428000">connection</span> <span m="3428480">in</span> <span m="3428540">the</span>
  <span m="3428600">first</span> <span m="3428870">place?</span> <span m="3430860">In
  other</span> <span m="3430930">words,</span> <span m="3431150">what</span> <span
  m="3431270">is</span> <span m="3431360">this</span> <span m="3431480">going</span>
  <span m="3431590">to</span> <span m="3431690">be?</span></p><p><span m="3434750">OK,</span>
  <span m="3435370">students</span> <span m="3435760">who</span> <span m="3435880">took</span>
  <span m="3436150">undergraduate</span> <span m="3436690">classes</span> <span m="3437180">with
  me,</span> <span m="3437350">I'll</span> <span m="3437440">remind</span> <span m="3437920">you</span>
  <span m="3438040">of</span> <span m="3438130">one</span> <span m="3438250">of</span>
  <span m="3438310">the</span> <span m="3438370">key</span> <span m="3438640">bits</span>
  <span m="3438850">of</span> <span m="3438940">wisdom</span> <span m="3439300">I</span>
  <span m="3439360">always</span> <span m="3439570">tell</span> <span m="3439750">people.</span>
  <span m="3440110">If the</span> <span m="3440500">professor</span> <span m="3441250">asks</span>
  <span m="3441610">you</span> <span m="3441760">a</span> <span m="3441820">question,</span>
  <span m="3442900">90%</span> <span m="3443650">of</span> <span m="3443710">the</span>
  <span m="3443770">time,</span> <span m="3444040">if</span> <span m="3444160">you</span>
  <span m="3444220">just</span> <span m="3444370">shout</span> <span m="3444790">out,</span>
  <span m="3445010">&quot;0,&quot;</span> <span m="3445750">you</span> <span m="3445960">are</span>
  <span m="3446050">likely</span> <span m="3446500">to</span> <span m="3446620">be</span>
  <span m="3446770">right.</span> <span m="3447220">[LAUGHING].</span> <span m="3449080">Usually,</span>
  <span m="3449500">there's</span> <span m="3449680">some</span> <span m="3449890">kind</span>
  <span m="3450010">of</span> <span m="3450100">a symmetry</span> <span m="3450640">that</span>
  <span m="3450820">we</span> <span m="3451210">want</span> <span m="3451570">you</span>
  <span m="3451750">to</span> <span m="3451840">understand,</span> <span m="3452560">which</span>
  <span m="3452680">allows</span> <span m="3452890">you</span> <span m="3452950">to</span>
  <span m="3453010">go,</span> <span m="3453190">oh,</span> <span m="3453520">it's</span>
  <span m="3453640">equal</span> <span m="3453820">to</span> <span m="3453880">0.</span>
  <span m="3454720">By</span> <span m="3454930">the</span> <span m="3455020">way,</span>
  <span m="3455300">whenever</span> <span m="3455500">I</span> <span m="3455560">point</span>
  <span m="3455800">that</span> <span m="3455890">out</span> <span m="3456010">to</span>
  <span m="3456130">a</span> <span m="3456160">class,</span> <span m="3456490">I</span>
  <span m="3456550">then</span> <span m="3456730">work</span> <span m="3456960">really</span>
  <span m="3457300">hard</span> <span m="3457600">to</span> <span m="3457930">make</span>
  <span m="3458200">a</span> <span m="3458260">non-zero</span> <span m="3458800">answer</span>
  <span m="3459040">for</span> <span m="3459130">the</span> <span m="3459190">next</span>
  <span m="3459400">time</span> <span m="3459520">I</span> <span m="3459610">ask</span>
  <span m="3459850">it.</span></p><p><span m="3460310">So</span> <span m="3460570">the</span>
  <span m="3460760">covariant</span> <span m="3461220">derivative</span> <span m="3461710">of
  g</span> <span m="3462100">is</span> <span m="3462490">0,</span> <span m="3463860">so</span>
  <span m="3463990">this</span> <span m="3464110">term</span> <span m="3464350">dies.</span>
  <span m="3465640">Because</span> <span m="3466240">the</span> <span m="3466330">covariant</span>
  <span m="3466840">derivative</span> <span m="3467350">of g</span> <span m="3467500">is</span>
  <span m="3467890">0,</span> <span m="3468850">I</span> <span m="3468970">can</span>
  <span m="3469150">always</span> <span m="3469420">commute</span> <span m="3470230">the
  metric</span> <span m="3470860">with</span> <span m="3471680">covariant</span> <span
  m="3471950">derivatives.</span> <span m="3472940">So</span> <span m="3472960">I</span>
  <span m="3473020">can</span> <span m="3473170">take</span> <span m="3473350">this,</span>
  <span m="3473850">move</span> <span m="3474120">it</span> <span m="3474220">inside</span>
  <span m="3474520">the</span> <span m="3474580">derivative.</span> <span m="3475540">I</span>
  <span m="3475630">can</span> <span m="3475780">take</span> <span m="3475960">this,</span>
  <span m="3476500">move</span> <span m="3476740">it</span> <span m="3476800">inside</span>
  <span m="3477100">the</span> <span m="3477190">derivative.</span></p><p><span m="3499180">So
  what</span> <span m="3499420">this</span> <span m="3499600">means</span> <span m="3500530">is</span>
  <span m="3501970">this</span> <span m="3502180">Lie</span> <span m="3502460">derivative</span>
  <span m="3502840">equation,</span> <span m="3503590">after</span> <span m="3503920">all</span>
  <span m="3504040">the</span> <span m="3504130">smoke</span> <span m="3504550">clears,</span>
  <span m="3506290">can</span> <span m="3506440">be</span> <span m="3506560">written</span>
  <span m="3512720">like</span> <span m="3512930">this.</span> <span m="3515090">Or,</span>
  <span m="3515450">if</span> <span m="3515630">I</span> <span m="3515780">recall,</span>
  <span m="3517060">there's</span> <span m="3517370">this</span> <span m="3517550">notation</span>
  <span m="3518210">for</span> <span m="3518390">symmetry</span> <span m="3518750">of</span>
  <span m="3519290">indices,</span> <span m="3522110">which</span> <span m="3522260">I</span>
  <span m="3522320">introduced</span> <span m="3522710">in</span> <span m="3522770">a</span>
  <span m="3522830">previous</span> <span m="3523130">lecture.</span> <span m="3523550">The</span>
  <span m="3523670">symmetric</span> <span m="3524290">covariant</span> <span m="3524670">derivative</span>
  <span m="3525230">of</span> <span m="3525350">this</span> <span m="3525620">C</span>
  <span m="3527660">is</span> <span m="3527840">equal</span> <span m="3528050">to</span>
  <span m="3528110">0.</span> <span m="3528920">This</span> <span m="3529190">equation</span>
  <span m="3530060">is</span> <span m="3530240">known</span> <span m="3530690">as</span>
  <span m="3535650">Killing's</span> <span m="3536070">equation,</span> <span m="3538350">and</span>
  <span m="3538680">C</span> <span m="3543000">is</span> <span m="3543480">a</span>
  <span m="3545310">Killing</span> <span m="3546330">vector.</span></p><p><span m="3547620">Now,</span>
  <span m="3547980">this</span> <span m="3548130">was</span> <span m="3548250">a</span>
  <span m="3548310">fair</span> <span m="3548700">amount</span> <span m="3549120">of</span>
  <span m="3549210">formalism.</span> <span m="3550710">I</span> <span m="3550740">was</span>
  <span m="3550860">really</span> <span m="3551160">laying</span> <span m="3551460">out</span>
  <span m="3551700">a</span> <span m="3551790">lot</span> <span m="3552330">of</span>
  <span m="3553020">the</span> <span m="3553140">details</span> <span m="3553530">to</span>
  <span m="3553620">get</span> <span m="3553740">this right.</span> <span m="3554520">So</span>
  <span m="3554910">to</span> <span m="3555060">give</span> <span m="3555300">you</span>
  <span m="3555420">some</span> <span m="3555600">context</span> <span m="3556200">as</span>
  <span m="3556290">to</span> <span m="3556380">why</span> <span m="3556680">this</span>
  <span m="3556860">matters,</span> <span m="3560925">there's</span> <span m="3561420">a</span>
  <span m="3561450">bit</span> <span m="3561600">more</span> <span m="3561810">that</span>
  <span m="3561930">needs</span> <span m="3562110">to</span> <span m="3562200">come</span>
  <span m="3562380">out</span> <span m="3562560">of</span> <span m="3562650">this,</span>
  <span m="3562890">but</span> <span m="3563040">we're</span> <span m="3563160">going</span>
  <span m="3563370">to</span> <span m="3563460">get</span> <span m="3563640">to</span>
  <span m="3563790">it</span> <span m="3563880">very</span> <span m="3564120">soon.</span></p><p><span
  m="3566460">Suppose</span> <span m="3566820">I</span> <span m="3566880">have</span>
  <span m="3567120">a</span> <span m="3567150">body</span> <span m="3567900">that</span>
  <span m="3568050">is</span> <span m="3568200">freely</span> <span m="3568560">falling</span>
  <span m="3568980">through</span> <span m="3569130">some</span> <span m="3569390">spacetime.</span>
  <span m="3571140">And</span> <span m="3571380">you</span> <span m="3571480">know</span>
  <span m="3571570">what?</span> <span m="3571650">I'm</span> <span m="3571680">going</span>
  <span m="3571800">to</span> <span m="3571860">leave</span> <span m="3572010">this</span>
  <span m="3572160">here.</span> <span m="3572440">So</span> <span m="3573570">this</span>
  <span m="3573720">is</span> <span m="3573840">a</span> <span m="3574140">slightly</span>
  <span m="3574650">advanced</span> <span m="3575040">tangent,</span> <span m="3575520">so</span>
  <span m="3575700">I'll</span> <span m="3575760">start</span> <span m="3576030">a</span>
  <span m="3576060">new</span> <span m="3576210">board.</span></p><p><span m="3600370">So</span>
  <span m="3600470">if</span> <span m="3600560">I</span> <span m="3600650">have</span>
  <span m="3600740">some</span> <span m="3600920">body</span> <span m="3601220">that</span>
  <span m="3601370">is</span> <span m="3601550">freely</span> <span m="3602000">falling,</span>
  <span m="3603130">what</span> <span m="3603510">we</span> <span m="3603620">are</span>
  <span m="3603740">going</span> <span m="3603980">to</span> <span m="3604100">show</span>
  <span m="3604670">in,</span> <span m="3605060">probably,</span> <span m="3605840">Thursday's</span>
  <span m="3606530">lecture</span> <span m="3608750">is</span> <span m="3608960">that</span>
  <span m="3609140">the</span> <span m="3609260">equation</span> <span m="3609770">of</span>
  <span m="3609860">motion</span> <span m="3610190">that</span> <span m="3610310">governs</span>
  <span m="3610720">it</span> <span m="3610880">is--</span> <span m="3611180">you</span>
  <span m="3611270">can</span> <span m="3611660">argue</span> <span m="3611930">this</span>
  <span m="3612080">on</span> <span m="3612200">physical</span> <span m="3612560">grounds,</span>
  <span m="3612830">and</span> <span m="3612920">that's</span> <span m="3613070">all</span>
  <span m="3613250">I</span> <span m="3613310">will</span> <span m="3613400">do</span>
  <span m="3613550">for</span> <span m="3613700">now--</span> <span m="3614510">it's</span>
  <span m="3615200">a</span> <span m="3616040">trajectory</span> <span m="3616640">that</span>
  <span m="3616790">parallel</span> <span m="3617330">transports</span> <span m="3617960">its</span>
  <span m="3618110">own</span> <span m="3618290">tangent</span> <span m="3618710">factor.</span>
  <span m="3619580">For</span> <span m="3619730">intuition,</span> <span m="3620420">go</span>
  <span m="3620690">into</span> <span m="3620840">the</span> <span m="3620900">freely</span>
  <span m="3621200">falling</span> <span m="3621560">frame</span> <span m="3622010">where</span>
  <span m="3622190">it's</span> <span m="3622340">just</span> <span m="3622550">the</span>
  <span m="3622610">trajectory</span> <span m="3623060">from</span> <span m="3623210">special</span>
  <span m="3623540">relativity.</span> <span m="3624500">It's</span> <span m="3624680">a</span>
  <span m="3624740">straight</span> <span m="3625220">line</span> <span m="3625670">in</span>
  <span m="3625850">that</span> <span m="3626060">frame,</span> <span m="3626900">and</span>
  <span m="3627740">parallel</span> <span m="3628070">transporting</span> <span m="3628580">its</span>
  <span m="3628700">own</span> <span m="3628850">tangent</span> <span m="3629240">vector</span>
  <span m="3629580">basically</span> <span m="3629960">means</span> <span m="3630200">it</span>
  <span m="3630500">just</span> <span m="3630650">moves</span> <span m="3631550">on</span>
  <span m="3631850">whatever</span> <span m="3632150">course</span> <span m="3632510">it</span>
  <span m="3632570">is</span> <span m="3632690">going.</span> <span m="3634430">So</span>
  <span m="3634880">this</span> <span m="3635420">is</span> <span m="3635750">a</span>
  <span m="3635840">trajectory</span> <span m="3640130">for</span> <span m="3640400">which</span>
  <span m="3649010">I</span> <span m="3649130">demand</span> <span m="3649820">that</span>
  <span m="3650300">the</span> <span m="3650450">four-velocity</span> <span m="3651350">governing</span>
  <span m="3651830">it</span> <span m="3652160">parallel</span> <span m="3652610">transports</span>
  <span m="3653210">along</span> <span m="3653510">itself.</span></p><p><span m="3655790">Now,</span>
  <span m="3655970">suppose</span> <span m="3656780">you</span> <span m="3657020">are</span>
  <span m="3657140">moving</span> <span m="3657740">in</span> <span m="3657890">a</span>
  <span m="3657960">spacetime</span> <span m="3659000">that</span> <span m="3659150">has</span>
  <span m="3659660">a</span> <span m="3659750">Killing</span> <span m="3660140">vector.</span>
  <span m="3675470">So</span> <span m="3675620">this</span> <span m="3675860">will</span>
  <span m="3676040">be</span> <span m="3676310">Thursday's</span> <span m="3676910">lecture.</span>
  <span m="3682080">Suppose</span> <span m="3682590">the</span> <span m="3682650">spacetime</span>
  <span m="3683250">has</span> <span m="3683490">a</span> <span m="3683550">Killing</span>
  <span m="3683850">vector.</span> <span m="3684600">Well,</span> <span m="3684910">so
  there</span> <span m="3685010">will</span> <span m="3685130">be</span> <span m="3685260">some</span>
  <span m="3685860">goofy</span> <span m="3686340">C</span> <span m="3686670">that</span>
  <span m="3686820">you</span> <span m="3686910">know</span> <span m="3687090">exists,</span>
  <span m="3687990">and you know</span> <span m="3688140">C</span> <span m="3689550">obeys</span>
  <span m="3689940">this</span> <span m="3690120">equation.</span> <span m="3691860">By</span>
  <span m="3692040">combining</span> <span m="3692640">these</span> <span m="3692880">things,</span>
  <span m="3693450">you</span> <span m="3693660">can</span> <span m="3693900">show</span>
  <span m="3694380">that</span> <span m="3694590">there</span> <span m="3694890">is</span>
  <span m="3696120">some</span> <span m="3696450">quantity,</span> <span m="3697140">C,</span>
  <span m="3701220">which</span> <span m="3701370">is</span> <span m="3701490">given</span>
  <span m="3701760">by</span> <span m="3701880">taking</span> <span m="3702210">the</span>
  <span m="3702330">inner</span> <span m="3702540">product</span> <span m="3703830">of</span>
  <span m="3703920">the</span> <span m="3704010">four-velocity</span> <span m="3704790">of</span>
  <span m="3704850">this</span> <span m="3705000">freely</span> <span m="3705300">falling</span>
  <span m="3706230">thing</span> <span m="3707400">and</span> <span m="3707490">the</span>
  <span m="3707550">Killing</span> <span m="3707880">vector.</span> <span m="3709260">And</span>
  <span m="3709380">you</span> <span m="3709470">can</span> <span m="3709590">prove</span>
  <span m="3709860">that</span> <span m="3710010">this</span> <span m="3710460">is</span>
  <span m="3710640">a</span> <span m="3710700">constant</span> <span m="3711270">of</span>
  <span m="3711390">the</span> <span m="3711480">motion.</span></p><p><span m="3726110">So</span>
  <span m="3726570">let's</span> <span m="3726700">think</span> <span m="3726880">about</span>
  <span m="3727060">where</span> <span m="3727240">this</span> <span m="3727390">goes</span>
  <span m="3727750">with</span> <span m="3727870">some</span> <span m="3727990">of</span>
  <span m="3728050">the</span> <span m="3728110">physics</span> <span m="3728560">that</span>
  <span m="3728740">you</span> <span m="3729190">presumably</span> <span m="3729670">all</span>
  <span m="3730000">know</span> <span m="3730270">and</span> <span m="3730390">love</span>
  <span m="3730660">already.</span> <span m="3731500">Suppose</span> <span m="3731920">you</span>
  <span m="3732220">look</span> <span m="3732760">at</span> <span m="3733150">a</span>
  <span m="3733460">spacetime.</span> <span m="3735100">So</span> <span m="3737170">you</span>
  <span m="3737260">climb</span> <span m="3737590">a</span> <span m="3737650">really</span>
  <span m="3737890">high</span> <span m="3738100">mountain.</span> <span m="3738520">You</span>
  <span m="3738610">discover</span> <span m="3739000">that</span> <span m="3739120">there's</span>
  <span m="3739270">a</span> <span m="3739330">spacetime</span> <span m="3739810">metric</span>
  <span m="3740200">carved</span> <span m="3740590">into</span> <span m="3740740">the</span>
  <span m="3740830">stone</span> <span m="3741180">into</span> <span m="3741280">the</span>
  <span m="3741370">top</span> <span m="3741610">of</span> <span m="3741730">it.</span>
  <span m="3742660">You</span> <span m="3742720">think,</span> <span m="3742900">OK,</span>
  <span m="3743140">this</span> <span m="3743260">probably</span> <span m="3743560">matters.</span>
  <span m="3744760">You</span> <span m="3744940">look</span> <span m="3745210">at</span>
  <span m="3745360">it</span> <span m="3745480">and</span> <span m="3745660">you</span>
  <span m="3745780">notice</span> <span m="3746470">it</span> <span m="3746560">depends</span>
  <span m="3747010">on,</span> <span m="3747190">say,</span> <span m="3747580">time,</span>
  <span m="3748300">radius,</span> <span m="3748870">and</span> <span m="3748990">two</span>
  <span m="3749260">angles.</span></p><p><span m="3754150">Suppose</span> <span m="3754660">you</span>
  <span m="3754780">have</span> <span m="3755200">a</span> <span m="3755350">metric</span>
  <span m="3757510">that</span> <span m="3757780">is</span> <span m="3758200">time-independent.</span>
  <span m="3766160">Hey,</span> <span m="3766370">if</span> <span m="3766490">it's</span>
  <span m="3766610">time-independent,</span> <span m="3768200">then</span> <span m="3768740">I</span>
  <span m="3769040">know</span> <span m="3770330">that</span> <span m="3770750">the</span>
  <span m="3771050">derivative</span> <span m="3771740">of</span> <span m="3771860">that</span>
  <span m="3772070">thing</span> <span m="3772340">with</span> <span m="3772490">respect</span>
  <span m="3772820">to</span> <span m="3772920">time</span> <span m="3773450">is</span>
  <span m="3773570">0.</span> <span m="3774500">There</span> <span m="3774740">must</span>
  <span m="3775190">exist</span> <span m="3775850">a</span> <span m="3776000">Killing</span>
  <span m="3776420">factor</span> <span m="3777320">that</span> <span m="3777470">is</span>
  <span m="3777620">related</span> <span m="3778460">to</span> <span m="3778640">the</span>
  <span m="3778730">fact</span> <span m="3779060">that</span> <span m="3779180">there</span>
  <span m="3779330">is</span> <span m="3779480">no</span> <span m="3779660">time</span>
  <span m="3780020">dependence</span> <span m="3780470">in</span> <span m="3780560">this</span>
  <span m="3780710">metric.</span></p><p><span m="3802800">So</span> <span m="3803090">you</span>
  <span m="3803180">go</span> <span m="3803340">and</span> <span m="3803450">you</span>
  <span m="3803570">calculate</span> <span m="3804200">it.</span> <span m="3805720">So</span>
  <span m="3805910">this</span> <span m="3806150">thing,</span> <span m="3806390">that</span>
  <span m="3806510">C</span> <span m="3806750">is</span> <span m="3806870">a</span>
  <span m="3806900">constant of the</span> <span m="3807380">motion--</span> <span
  m="3815860">I</span> <span m="3815920">believe</span> <span m="3816100">that's</span>
  <span m="3816250">P</span> <span m="3816490">set</span> <span m="3816610">4.</span>
  <span m="3821560">It's</span> <span m="3821710">not</span> <span m="3821890">hard.</span>
  <span m="3822340">You</span> <span m="3822460">combine</span> <span m="3822910">that</span>
  <span m="3823060">equation</span> <span m="3823480">that</span> <span m="3823570">we're</span>
  <span m="3823660">going</span> <span m="3823780">to</span> <span m="3823840">derive,</span>
  <span m="3824170">called</span> <span m="3824350">the</span> <span m="3824410">geodesic</span>
  <span m="3824800">equation,</span> <span m="3825160">with</span> <span m="3825280">Killing's</span>
  <span m="3825580">equation.</span> <span m="3826000">Math</span> <span m="3826240">happens.</span>
  <span m="3826600">You</span> <span m="3826660">got</span> <span m="3826810">it.</span></p><p><span
  m="3827760">So</span> <span m="3827990">suppose</span> <span m="3828570">you've</span>
  <span m="3828700">got</span> <span m="3828790">a</span> <span m="3828820">metric</span>
  <span m="3829120">that's</span> <span m="3829240">time-dependent and</span> <span
  m="3829910">you</span> <span m="3830080">know</span> <span m="3830410">you've</span>
  <span m="3830590">got</span> <span m="3830800">this</span> <span m="3830980">thing.</span>
  <span m="3831210">So</span> <span m="3831340">you</span> <span m="3831400">know</span>
  <span m="3831470">what?</span> <span m="3831620">Let's</span> <span m="3832060">work</span>
  <span m="3832300">it</span> <span m="3832390">out</span> <span m="3832630">and</span>
  <span m="3832750">look</span> <span m="3832960">at</span> <span m="3833140">it.</span>
  <span m="3833860">It</span> <span m="3834040">becomes</span> <span m="3834670">clear,</span>
  <span m="3835360">after</span> <span m="3835570">studying</span> <span m="3835900">this</span>
  <span m="3836080">for</span> <span m="3836200">a</span> <span m="3836260">little</span>
  <span m="3836440">bit,</span> <span m="3837100">that</span> <span m="3837400">the</span>
  <span m="3837550">C</span> <span m="3841510">for</span> <span m="3841780">this</span>
  <span m="3842050">Killing</span> <span m="3842380">vector</span> <span m="3847760">is</span>
  <span m="3848120">energy.</span> <span m="3850340">In</span> <span m="3850550">the</span>
  <span m="3850640">same</span> <span m="3850940">way</span> <span m="3851150">that,</span>
  <span m="3851270">if</span> <span m="3851390">you</span> <span m="3851510">have</span>
  <span m="3851660">a</span> <span m="3851750">time-independent</span> <span m="3852620">Lagrangian,</span>
  <span m="3853550">your</span> <span m="3853670">system</span> <span m="3854000">has</span>
  <span m="3854150">a</span> <span m="3854210">conserved</span> <span m="3854690">energy,</span>
  <span m="3855710">if</span> <span m="3855890">you</span> <span m="3856100">have</span>
  <span m="3856250">a</span> <span m="3856340">time-independent</span> <span m="3857210">metric,</span>
  <span m="3858110">there</span> <span m="3858260">is</span> <span m="3858380">a</span>
  <span m="3858440">Killing</span> <span m="3858800">vector,</span> <span m="3859280">which--</span>
  <span m="3859880">the</span> <span m="3860030">language</span> <span m="3860360">we
  like</span> <span m="3860510">to</span> <span m="3860600">use is--</span> <span
  m="3861110">we</span> <span m="3861230">say</span> <span m="3862320">the</span>
  <span m="3862670">motion</span> <span m="3863060">of that</span> <span m="3863190">spacetime</span>
  <span m="3863690">emits</span> <span m="3864110">a</span> <span m="3864170">conserved</span>
  <span m="3864710">energy.</span></p><p><span m="3866660">Suppose</span> <span m="3867110">you</span>
  <span m="3867200">find</span> <span m="3867500">that</span> <span m="3867590">the</span>
  <span m="3867680">metric</span> <span m="3868130">is</span> <span m="3869540">independent</span>
  <span m="3870080">of</span> <span m="3870200">some</span> <span m="3870500">angle.</span>
  <span m="3870890">We'll</span> <span m="3871010">call</span> <span m="3871130">it</span>
  <span m="3871220">phi.</span> <span m="3873710">Three</span> <span m="3874100">guesses</span>
  <span m="3874520">what's</span> <span m="3874760">going</span> <span m="3874870">to</span>
  <span m="3874970">happen.</span> <span m="3875310">In</span> <span m="3875410">this</span>
  <span m="3875450">case--</span> <span m="3876630">just</span> <span m="3876710">one</span>
  <span m="3876950">guess,</span> <span m="3877190">actually.</span> <span m="3877580">Conserved--</span></p><p><span
  m="3878240">AUDIENCE:</span> <span m="3878405">Angular</span> <span m="3878570">momentum.</span></p><p><span
  m="3879230">SCOTT HUGHES:</span> <span m="3879425">Angular</span> <span m="3879620">momentum</span>
  <span m="3880070">pops</span> <span m="3880340">out</span> <span m="3880490">in</span>
  <span m="3880550">that</span> <span m="3880700">case.</span> <span m="3881490">So</span>
  <span m="3881600">this</span> <span m="3881930">ends</span> <span m="3882230">up</span>
  <span m="3882350">being</span> <span m="3882740">the</span> <span m="3882860">way</span>
  <span m="3883400">in</span> <span m="3883610">which</span> <span m="3883970">we,</span>
  <span m="3884450">essentially,</span> <span m="3885290">make</span> <span m="3885560">very</span>
  <span m="3885800">rigorous</span> <span m="3886220">and</span> <span m="3886340">geometric</span>
  <span m="3886910">the</span> <span m="3887030">idea</span> <span m="3887750">that</span>
  <span m="3889130">conservation</span> <span m="3889820">laws</span> <span m="3890390">are</span>
  <span m="3890630">put</span> <span m="3890930">into</span> <span m="3891500">general</span>
  <span m="3891800">relativity,</span> <span m="3893090">OK?</span> <span m="3893660">So</span>
  <span m="3893900">I</span> <span m="3893930">realize</span> <span m="3894200">there's</span>
  <span m="3894350">a</span> <span m="3894380">lot</span> <span m="3894560">of</span>
  <span m="3894650">abstraction</span> <span m="3895250">here.</span> <span m="3895530">So</span>
  <span m="3895630">I</span> <span m="3895730">want</span> <span m="3895760">to</span>
  <span m="3895820">go</span> <span m="3895880">on</span> <span m="3895970">a</span>
  <span m="3896030">bit</span> <span m="3896150">of</span> <span m="3896210">an</span>
  <span m="3896300">aside</span> <span m="3896660">just</span> <span m="3896810">to</span>
  <span m="3897140">tie</span> <span m="3897560">down</span> <span m="3897890">where</span>
  <span m="3898220">we</span> <span m="3898320">are</span> <span m="3898400">going</span>
  <span m="3898640">with</span> <span m="3898790">this</span> <span m="3898970">and</span>
  <span m="3899090">why</span> <span m="3899390">this</span> <span m="3899570">actually</span>
  <span m="3899900">matters.</span></p><p><span m="3901760">OK.</span> <span m="3904575">Let's</span>
  <span m="3904890">see.</span> <span m="3905110">So</span> <span m="3905310">we</span>
  <span m="3905400">got</span> <span m="3905490">about</span> <span m="3905670">10</span>
  <span m="3906000">minutes</span> <span m="3906300">left.</span> <span m="3907230">So</span>
  <span m="3907950">what</span> <span m="3908070">we're</span> <span m="3908160">going</span>
  <span m="3908240">to</span> <span m="3908340">do</span> <span m="3908610">at</span>
  <span m="3908730">the</span> <span m="3908820">very</span> <span m="3909450">end</span>
  <span m="3910470">of</span> <span m="3911790">today--</span> <span m="3912000">and</span>
  <span m="3912090">we'll</span> <span m="3912180">pick</span> <span m="3912390">this</span>
  <span m="3912570">up</span> <span m="3912690">beginning</span> <span m="3913050">of</span>
  <span m="3913140">next</span> <span m="3913440">time.</span> <span m="3914050">So</span>
  <span m="3914220">for</span> <span m="3914310">the</span> <span m="3914400">people</span>
  <span m="3914850">who</span> <span m="3915000">walked</span> <span m="3915360">in</span>
  <span m="3915480">a</span> <span m="3915540">few</span> <span m="3915810">minutes</span>
  <span m="3916080">late,</span> <span m="3917870">the</span> <span m="3917990">stuff</span>
  <span m="3918320">that</span> <span m="3918440">I'm</span> <span m="3918590">actually</span>
  <span m="3918860">about</span> <span m="3919190">to</span> <span m="3919250">start</span>
  <span m="3919520">talking</span> <span m="3919910">about</span> <span m="3921140">we</span>
  <span m="3921290">need</span> <span m="3921440">to</span> <span m="3921500">get</span>
  <span m="3921710">through</span> <span m="3921890">before</span> <span m="3922250">you</span>
  <span m="3922370">can</span> <span m="3922520">do</span> <span m="3922730">one</span>
  <span m="3923000">of</span> <span m="3923060">the</span> <span m="3923120">problems</span>
  <span m="3923540">on</span> <span m="3923660">the</span> <span m="3923720">P set.</span>
  <span m="3924440">So</span> <span m="3924710">I'm</span> <span m="3924890">probably</span>
  <span m="3925160">going</span> <span m="3925310">to</span> <span m="3925340">take</span>
  <span m="3925580">that</span> <span m="3925730">problem</span> <span m="3926120">and</span>
  <span m="3926210">move</span> <span m="3926390">it</span> <span m="3926450">on</span>
  <span m="3926550">to</span> <span m="3926700">P</span> <span m="3926990">set</span>
  <span m="3927170">4,</span> <span m="3927730">but</span> <span m="3927990">I'm going
  to</span> <span m="3928070">start</span> <span m="3928310">talking</span> <span
  m="3928610">about</span> <span m="3928790">it</span> <span m="3928850">right</span>
  <span m="3929000">now.</span></p><p><span m="3930560">So</span> <span m="3931760">we've</span>
  <span m="3931940">really</span> <span m="3932150">focused</span> <span m="3932720">a</span>
  <span m="3932840">lot,</span> <span m="3935300">so</span> <span m="3935630">far,</span>
  <span m="3939350">on</span> <span m="3939570">tensors.</span> <span m="3942650">We're</span>
  <span m="3942740">going</span> <span m="3942850">to</span> <span m="3942920">now</span>
  <span m="3943100">start</span> <span m="3943370">talking</span> <span m="3943790">about</span>
  <span m="3944150">a</span> <span m="3944270">related</span> <span m="3944870">quantity</span>
  <span m="3947780">called</span> <span m="3948530">tensor</span> <span m="3949220">densities.</span>
  <span m="3956080">There's</span> <span m="3956290">really</span> <span m="3956620">only</span>
  <span m="3956920">two</span> <span m="3957280">that</span> <span m="3957430">matter</span>
  <span m="3957850">for</span> <span m="3958060">our</span> <span m="3958300">purposes,</span>
  <span m="3958810">but</span> <span m="3959050">I</span> <span m="3959110">want</span>
  <span m="3959260">to</span> <span m="3959320">go</span> <span m="3959410">through</span>
  <span m="3959590">them</span> <span m="3959710">carefully.</span> <span m="3960190">So</span>
  <span m="3960340">I</span> <span m="3960430">will</span> <span m="3960550">set</span>
  <span m="3960830">up</span> <span m="3960940">with</span> <span m="3961090">one,</span>
  <span m="3961450">and</span> <span m="3961570">then</span> <span m="3961690">we'll</span>
  <span m="3961780">conclude</span> <span m="3962170">the</span> <span m="3962290">other</span>
  <span m="3962500">one</span> <span m="3962860">at the</span> <span m="3963220">beginning</span>
  <span m="3963460">of</span> <span m="3963520">Thursday's</span> <span m="3963970">lecture.</span></p><p><span
  m="3964900">So</span> <span m="3965110">let</span> <span m="3965230">me</span> <span
  m="3965320">define</span> <span m="3965770">this</span> <span m="3965920">first.</span>
  <span m="3968160">I'm</span> <span m="3968250">going</span> <span m="3968370">to</span>
  <span m="3968440">give</span> <span m="3968620">a</span> <span m="3968650">definition</span>
  <span m="3969130">that</span> <span m="3969280">I</span> <span m="3969430">like</span>
  <span m="3969700">but</span> <span m="3969830">that's</span> <span m="3969970">actually</span>
  <span m="3970210">kind</span> <span m="3970330">of</span> <span m="3970390">stupid.</span>
  <span m="3971260">So</span> <span m="3971740">these</span> <span m="3972040">are</span>
  <span m="3972250">quantities</span> <span m="3974860">that</span> <span m="3976390">transform</span>
  <span m="3981510">almost</span> <span m="3983670">like</span> <span m="3983860">tensors--</span>
  <span m="3988890">a</span> <span m="3989250">little</span> <span m="3989400">bit</span>
  <span m="3989490">lame,</span> <span m="3989760">but,</span> <span m="3990030">as</span>
  <span m="3990360">you'll</span> <span m="3990480">see</span> <span m="3990620">in</span>
  <span m="3990680">a</span> <span m="3990720">moment,</span> <span m="3991060">it's</span>
  <span m="3991110">kind</span> <span m="3991290">of</span> <span m="3991380">accurate.</span>
  <span m="3992100">What</span> <span m="3992280">you'll</span> <span m="3992400">find</span>
  <span m="3993090">is</span> <span m="3993420">that</span> <span m="3994110">the</span>
  <span m="3994320">transformation</span> <span m="3995130">law</span> <span m="3995520">is</span>
  <span m="3995940">off</span> <span m="3998460">by</span> <span m="3998820">a</span>
  <span m="3998970">factor</span> <span m="4003530">that</span> <span m="4003800">is</span>
  <span m="4008550">the</span> <span m="4008710">determinant</span> <span m="4013090">of</span>
  <span m="4013210">the</span> <span m="4013270">coordinate</span> <span m="4013630">transformation</span>
  <span m="4014230">matrix.</span> <span m="4028340">Take it to</span> <span m="4028600">some</span>
  <span m="4028820">power.</span></p><p><span m="4033650">So</span> <span m="4033920">there's</span>
  <span m="4034050">is</span> <span m="4034160">an</span> <span m="4034250">infinite</span>
  <span m="4034580">number</span> <span m="4034850">of</span> <span m="4034940">tensor</span>
  <span m="4035270">densities</span> <span m="4035660">that</span> <span m="4035780">one</span>
  <span m="4035960">could</span> <span m="4036170">define.</span> <span m="4037130">Two</span>
  <span m="4037910">are</span> <span m="4038090">important</span> <span m="4039110">for</span>
  <span m="4039260">this</span> <span m="4039440">class.</span> <span m="4062830">So</span>
  <span m="4062940">the</span> <span m="4063030">two</span> <span m="4063240">that</span>
  <span m="4063360">are</span> <span m="4063450">most</span> <span m="4063630">important</span>
  <span m="4063960">for</span> <span m="4064110">us</span> <span m="4064350">are</span>
  <span m="4064590">the</span> <span m="4064710">Levi-Civita</span> <span m="4067740">symbol</span>
  <span m="4071700">and</span> <span m="4073050">the</span> <span m="4073170">determinant</span>
  <span m="4074190">of</span> <span m="4074280">the</span> <span m="4074370">metric.</span>
  <span m="4080870">So</span> <span m="4081470">we</span> <span m="4081650">use</span>
  <span m="4082010">Levi-Civita</span> <span m="4082730">already</span> <span m="4083150">to</span>
  <span m="4083240">talk</span> <span m="4083510">about</span> <span m="4083750">volumes.</span>
  <span m="4085580">And</span> <span m="4086120">it</span> <span m="4086270">was</span>
  <span m="4086900">a</span> <span m="4087140">tensor</span> <span m="4087620">when</span>
  <span m="4087740">we</span> <span m="4087860">were</span> <span m="4087920">working</span>
  <span m="4088430">in</span> <span m="4088670">rectilinear</span> <span m="4089270">coordinates,</span>
  <span m="4089710">where</span> <span m="4089840">the</span> <span m="4089900">underlying</span>
  <span m="4090200">coordinate</span> <span m="4090470">system</span> <span m="4090890">was</span>
  <span m="4091220">essentially</span> <span m="4091730">Cartesian</span> <span m="4092300">plus</span>
  <span m="4092510">time.</span> <span m="4094100">It's</span> <span m="4094280">not</span>
  <span m="4094640">in</span> <span m="4094760">general,</span> <span m="4095360">OK?</span>
  <span m="4095720">And we'll</span> <span m="4095840">go</span> <span m="4095990">through</span>
  <span m="4096200">why</span> <span m="4096380">that</span> <span m="4096500">is.</span>
  <span m="4096859">That'll</span> <span m="4097310">probably</span> <span m="4097580">be
  the</span> <span m="4097640">last</span> <span m="4097910">thing</span> <span m="4098029">we</span>
  <span m="4098090">can</span> <span m="4098210">fit</span> <span m="4098420">in</span>
  <span m="4098540">today.</span></p><p><span m="4099710">So</span> <span m="4100609">let</span>
  <span m="4100700">me</span> <span m="4100790">remind</span> <span m="4101240">you--</span>
  <span m="4104677">Levi-Civita--</span> <span m="4106800">I'm</span> <span m="4106859">going</span>
  <span m="4106960">to</span> <span m="4107029">write</span> <span m="4107180">it</span>
  <span m="4107240">with</span> <span m="4107410">a</span> <span m="4108760">tilde</span>
  <span m="4109130">on</span> <span m="4109380">it</span> <span m="4109490">to</span>
  <span m="4109609">emphasize</span> <span m="4110180">that</span> <span m="4112540">it</span>
  <span m="4112700">is</span> <span m="4112939">not</span> <span m="4113979">tensorial.</span>
  <span m="4117229">So</span> <span m="4117279">this</span> <span m="4117460">is</span>
  <span m="4117609">equal</span> <span m="4117910">to</span> <span m="4118000">plus</span>
  <span m="4118390">1</span> <span m="4119410">if</span> <span m="4119590">the</span>
  <span m="4119740">indices</span> <span m="4120550">are</span> <span m="4121870">0,</span>
  <span m="4122580">1,</span> <span m="4122880">2,</span> <span m="4123189">3</span>
  <span m="4124270">and</span> <span m="4124450">even</span> <span m="4124779">permutations</span>
  <span m="4125529">of</span> <span m="4125590">that</span> <span m="4129939">equals</span>
  <span m="4130270">minus</span> <span m="4130750">1</span> <span m="4132190">for</span>
  <span m="4132670">odd</span> <span m="4132939">permutations</span> <span m="4133600">of</span>
  <span m="4133689">that.</span> <span m="4136710">And</span> <span m="4137220">it's</span>
  <span m="4137399">0</span> <span m="4137970">for</span> <span m="4138149">any</span>
  <span m="4138359">index</span> <span m="4138810">repeated.</span></p><p><span m="4151160">Now,</span>
  <span m="4151350">this</span> <span m="4151859">symbol</span> <span m="4152279">has</span>
  <span m="4152490">a</span> <span m="4152550">really</span> <span m="4153270">nice</span>
  <span m="4153660">property</span> <span m="4154229">when</span> <span m="4154380">you</span>
  <span m="4154470">apply</span> <span m="4154830">it</span> <span m="4155010">to</span>
  <span m="4155340">any</span> <span m="4155609">matrix.</span> <span m="4156090">In</span>
  <span m="4156149">fact,</span> <span m="4157099">this</span> <span m="4157470">is</span>
  <span m="4157560">a</span> <span m="4157590">theorem.</span> <span m="4175260">So</span>
  <span m="4175380">I'm</span> <span m="4175500">working</span> <span m="4175800">in
  four-dimensional</span> <span m="4176399">space.</span> <span m="4176979">So</span>
  <span m="4177000">let's</span> <span m="4177120">say</span> <span m="4177240">I've</span>
  <span m="4177330">got</span> <span m="4178050">a</span> <span m="4178170">4-by-4</span>
  <span m="4178950">matrix,</span> <span m="4181440">which</span> <span m="4181920">I</span>
  <span m="4182010">will</span> <span m="4182130">call</span> <span m="4182490">m.</span>
  <span m="4184920">Write</span> <span m="4185470">a new</span> <span m="4185700">[INAUDIBLE]</span>
  <span m="4185970">notation,</span> <span m="4186240">m</span> <span m="4186540">alpha</span>
  <span m="4186840">mu.</span> <span m="4188580">If</span> <span m="4188760">I</span>
  <span m="4188970">evaluate</span> <span m="4191359">Levi-Civita,</span> <span m="4196740">contract</span>
  <span m="4197260">it</span> <span m="4197540">on</span> <span m="4197660">these</span>
  <span m="4197870">guys,</span> <span m="4211500">I</span> <span m="4211680">get</span>
  <span m="4211870">Levi-Civita</span> <span m="4212520">back,</span> <span m="4217660">multiply
  it</span> <span m="4218050">by</span> <span m="4219070">the</span> <span m="4219220">determinant</span>
  <span m="4220360">of</span> <span m="4220430">the</span> <span m="4220510">matrix</span>
  <span m="4220920">m.</span></p><p><span m="4231620">Now,</span> <span m="4231860">suppose</span>
  <span m="4232580">what</span> <span m="4232820">I</span> <span m="4232940">choose</span>
  <span m="4233420">for</span> <span m="4233570">my</span> <span m="4233630">matrix</span>
  <span m="4234050">m</span> <span m="4234800">is</span> <span m="4234920">my</span>
  <span m="4235070">coordinate</span> <span m="4235430">transformation</span> <span
  m="4236000">matrix.</span> <span m="4272780">So</span> <span m="4272800">I'm</span>
  <span m="4272860">just</span> <span m="4272980">going</span> <span m="4273080">to</span>
  <span m="4273160">write</span> <span m="4273430">down</span> <span m="4273670">this</span>
  <span m="4273790">result,</span> <span m="4274930">and</span> <span m="4276490">I'll</span>
  <span m="4276640">leave</span> <span m="4276910">it</span> <span m="4277000">since</span>
  <span m="4277150">we're</span> <span m="4277240">running</span> <span m="4277420">a</span>
  <span m="4277450">little</span> <span m="4277600">short</span> <span m="4277840">on</span>
  <span m="4277930">time.</span> <span m="4280480">You</span> <span m="4280600">can</span>
  <span m="4280720">just</span> <span m="4280870">double</span> <span m="4281170">check</span>
  <span m="4281500">that</span> <span m="4283180">I've</span> <span m="4283780">moved
  things</span> <span m="4284270">from</span> <span m="4284470">one</span> <span m="4284680">side
  of the</span> <span m="4284890">equation</span> <span m="4285280">to</span> <span
  m="4285370">the</span> <span m="4285490">other,</span> <span m="4285700">and you</span>
  <span m="4285790">can</span> <span m="4285910">just</span> <span m="4286090">double-check</span>
  <span m="4286570">I</span> <span m="4286630">did</span> <span m="4286780">that</span>
  <span m="4286930">correctly.</span></p><p><span m="4291010">What</span> <span m="4291160">that</span>
  <span m="4291280">tells</span> <span m="4291610">me</span> <span m="4291850">is</span>
  <span m="4292180">that</span> <span m="4293400">Levi-Civita</span> <span m="4294430">and</span>
  <span m="4295630">a</span> <span m="4295720">new</span> <span m="4296080">set</span>
  <span m="4296470">of</span> <span m="4296710">prime</span> <span m="4297130">coordinates</span>
  <span m="4299450">is</span> <span m="4299590">equal</span> <span m="4299830">to</span>
  <span m="4299980">this</span> <span m="4300190">guy</span> <span m="4301810">in</span>
  <span m="4301930">the</span> <span m="4302080">old,</span> <span m="4302590">unprimed</span>
  <span m="4303070">coordinates</span> <span m="4304600">with</span> <span m="4308220">all</span>
  <span m="4308610">my</span> <span m="4308820">usual</span> <span m="4309360">factors</span>
  <span m="4312830">of</span> <span m="4312930">transformation</span> <span m="4313590">matrices</span>
  <span m="4326570">and</span> <span m="4326710">then</span> <span m="4326830">an</span>
  <span m="4327010">extra</span> <span m="4327340">bit</span> <span m="4328690">that</span>
  <span m="4331990">is</span> <span m="4332770">the</span> <span m="4332890">determinant</span>
  <span m="4333700">of</span> <span m="4333790">the</span> <span m="4333880">coordinate</span>
  <span m="4334180">transformation</span> <span m="4334780">matrix.</span> <span m="4336340">If</span>
  <span m="4336490">it</span> <span m="4336550">were</span> <span m="4336640">just</span>
  <span m="4336820">the</span> <span m="4336910">top</span> <span m="4337240">line,</span>
  <span m="4337900">this</span> <span m="4338050">is</span> <span m="4338140">exactly</span>
  <span m="4338710">what</span> <span m="4338860">you</span> <span m="4338950">would</span>
  <span m="4339070">need</span> <span m="4339370">for</span> <span m="4339480">Levi-Civita</span>
  <span m="4340100">to</span> <span m="4340270">be</span> <span m="4340540">a</span>
  <span m="4340690">tensor</span> <span m="4341230">in</span> <span m="4341350">the</span>
  <span m="4341410">way</span> <span m="4341560">that</span> <span m="4341680">we</span>
  <span m="4341770">have</span> <span m="4341890">defined</span> <span m="4342230">tensors.</span>
  <span m="4343270">It's</span> <span m="4343450">not.</span></p><p><span m="4364390">So</span>
  <span m="4364710">the</span> <span m="4364830">extra</span> <span m="4365100">factor</span>
  <span m="4365490">pushes</span> <span m="4365870">away</span> <span m="4366090">from</span>
  <span m="4366270">a</span> <span m="4366300">tensor</span> <span m="4366630">relationship.</span>
  <span m="4368370">And</span> <span m="4368490">so</span> <span m="4368670">what</span>
  <span m="4368820">we</span> <span m="4368970">would</span> <span m="4369120">say</span>
  <span m="4369570">is,</span> <span m="4369990">because</span> <span m="4370530">this</span>
  <span m="4370710">is</span> <span m="4370860">off</span> <span m="4371100">by</span>
  <span m="4371250">a</span> <span m="4371310">factor</span> <span m="4371730">of</span>
  <span m="4371850">what's</span> <span m="4372050">sometimes</span> <span m="4372330">called</span>
  <span m="4372570">the</span> <span m="4372630">Jacobian,</span> <span m="4382610">we</span>
  <span m="4382760">call</span> <span m="4382970">this</span> <span m="4383300">a</span>
  <span m="4383930">tensor</span> <span m="4384410">density</span> <span m="4386420">of</span>
  <span m="4386570">weight</span> <span m="4386930">1.</span> <span m="4396590">So</span>
  <span m="4398230">in</span> <span m="4398320">order</span> <span m="4398470">to</span>
  <span m="4398530">do</span> <span m="4398680">this</span> <span m="4398830">properly--</span>
  <span m="4399320">I</span> <span m="4399420">don't</span> <span m="4399520">want</span>
  <span m="4399620">to</span> <span m="4399720">rush--</span> <span m="4401740">at</span>
  <span m="4401830">the</span> <span m="4401890">beginning</span> <span m="4402130">of</span>
  <span m="4402190">the</span> <span m="4402250">next</span> <span m="4402520">lecture,</span>
  <span m="4404390">we're</span> <span m="4404490">going</span> <span m="4404590">to</span>
  <span m="4404690">look</span> <span m="4405010">at</span> <span m="4406150">how</span>
  <span m="4406600">the</span> <span m="4406690">determinant</span> <span m="4407350">of</span>
  <span m="4407470">the</span> <span m="4407560">metric</span> <span m="4407890">behaves.</span>
  <span m="4409610">And</span> <span m="4409750">what</span> <span m="4409840">we'll</span>
  <span m="4409960">see</span> <span m="4410260">is</span> <span m="4410380">that,</span>
  <span m="4410500">although</span> <span m="4410710">the</span> <span m="4410800">metric</span>
  <span m="4411130">is</span> <span m="4411250">a</span> <span m="4411280">tensor,</span>
  <span m="4412180">its</span> <span m="4412390">determinant</span> <span m="4413560">is</span>
  <span m="4413710">a</span> <span m="4413770">tensor</span> <span m="4414100">density</span>
  <span m="4414580">of</span> <span m="4414730">weight</span> <span m="4415180">negative</span>
  <span m="4415570">2.</span></p><p><span m="4416950">And</span> <span m="4417160">so</span>
  <span m="4417250">what</span> <span m="4417370">that</span> <span m="4417520">tells</span>
  <span m="4417880">us</span> <span m="4418270">is</span> <span m="4418780">that</span>
  <span m="4419380">I</span> <span m="4419500">can</span> <span m="4419680">actually</span>
  <span m="4419920">put</span> <span m="4420100">together</span> <span m="4420490">a</span>
  <span m="4420640">combination</span> <span m="4422200">of</span> <span m="4422290">the</span>
  <span m="4422380">Levi-Civita</span> <span m="4423370">and</span> <span m="4424510">the</span>
  <span m="4424690">determinant</span> <span m="4425350">of</span> <span m="4425470">the</span>
  <span m="4425560">metric</span> <span m="4426100">in</span> <span m="4426250">such</span>
  <span m="4426460">a</span> <span m="4426520">way</span> <span m="4426730">that</span>
  <span m="4426940">their</span> <span m="4427180">product</span> <span m="4428080">is</span>
  <span m="4428410">tensorial.</span> <span m="4429880">And that</span> <span m="4430060">turns</span>
  <span m="4430270">out</span> <span m="4430330">to</span> <span m="4430390">be</span>
  <span m="4430480">real</span> <span m="4430640">useful</span> <span m="4431110">because</span>
  <span m="4431170">I can</span> <span m="4431320">use</span> <span m="4431590">this</span>
  <span m="4431770">to</span> <span m="4431860">define,</span> <span m="4432430">in</span>
  <span m="4432610">a</span> <span m="4432700">curved</span> <span m="4433060">spacetime,</span>
  <span m="4434050">covariant</span> <span m="4434560">volume</span> <span m="4434920">elements,</span>
  <span m="4436210">OK?</span> <span m="4437170">With</span> <span m="4437470">this</span>
  <span m="4437770">as</span> <span m="4437950">written,</span> <span m="4438250">my</span>
  <span m="4438400">volume</span> <span m="4438760">elements--</span> <span m="4439120">if</span>
  <span m="4439210">I</span> <span m="4439300">just</span> <span m="4439420">use</span>
  <span m="4439700">this</span> <span m="4440020">like</span> <span m="4440140">I</span>
  <span m="4440230">did</span> <span m="4440380">when</span> <span m="4440500">we're</span>
  <span m="4440590">taught</span> <span m="4440750">about</span> <span m="4440870">special</span>
  <span m="4441220">relativity,</span> <span m="4442000">my</span> <span m="4442150">volume</span>
  <span m="4442510">elements</span> <span m="4442870">won't</span> <span m="4443020">be</span>
  <span m="4443140">elements</span> <span m="4443410">of</span> <span m="4443470">a</span>
  <span m="4443500">tensor,</span> <span m="4444760">and</span> <span m="4445150">a</span>
  <span m="4445270">lot</span> <span m="4445780">of</span> <span m="4446050">the</span>
  <span m="4446260">framework</span> <span m="4446800">that</span> <span m="4446890">we've</span>
  <span m="4446990">developed</span> <span m="4447580">goes</span> <span m="4447790">to</span>
  <span m="4447880">hell.</span> <span m="4449170">So</span> <span m="4449560">an</span>
  <span m="4449710">extra</span> <span m="4450010">factor</span> <span m="4450520">of</span>
  <span m="4450640">the</span> <span m="4450720">determining</span> <span m="4451090">of
  the</span> <span m="4451150">metric</span> <span m="4451510">will</span> <span m="4451690">allow</span>
  <span m="4451900">us</span> <span m="4451990">to</span> <span m="4452080">correct</span>
  <span m="4452410">this.</span></p><p><span m="4453220">And</span> <span m="4453490">this</span>
  <span m="4453790">seems</span> <span m="4454060">kind</span> <span m="4454270">of</span>
  <span m="4454360">abstract.</span> <span m="4456770">So let me</span> <span m="4456970">just,</span>
  <span m="4457240">as</span> <span m="4457400">a</span> <span m="4457570">really</span>
  <span m="4457930">brief</span> <span m="4458320">aside,</span> <span m="4458740">before</span>
  <span m="4458980">we</span> <span m="4459100">conclude</span> <span m="4459490">today's</span>
  <span m="4459790">class--</span> <span m="4462200">suppose</span> <span m="4462620">I'm</span>
  <span m="4462770">just</span> <span m="4463040">in</span> <span m="4463160">Euclidean</span>
  <span m="4463610">three-space</span> <span m="4466980">and</span> <span m="4468000">I'm</span>
  <span m="4468210">working</span> <span m="4468540">in</span> <span m="4468660">spherical</span>
  <span m="4469020">coordinates.</span> <span m="4478490">So</span> <span m="4478660">here's</span>
  <span m="4478870">my</span> <span m="4479860">line</span> <span m="4480220">element.</span>
  <span m="4481390">My</span> <span m="4481570">metric</span> <span m="4487820">is</span>
  <span m="4487940">the</span> <span m="4488000">diagonal</span> <span m="4488480">of</span>
  <span m="4488660">1r</span> <span m="4490040">squared</span> <span m="4491240">r</span>
  <span m="4491390">squared</span> <span m="4493070">sine</span> <span m="4493280">squared</span>
  <span m="4493550">theta.</span> <span m="4495080">The</span> <span m="4495200">determinant</span>
  <span m="4496010">of</span> <span m="4496130">the</span> <span m="4496190">metric,</span>
  <span m="4497750">which</span> <span m="4497930">I</span> <span m="4498020">will</span>
  <span m="4498140">write</span> <span m="4498832">g--</span> <span m="4502450">it's
  r</span> <span m="4502630">to</span> <span m="4502790">the</span> <span m="4502870">fourth</span>
  <span m="4504790">sine</span> <span m="4505120">squared</span> <span m="4505390">theta.</span>
  <span m="4506950">What</span> <span m="4507100">we're</span> <span m="4507190">going</span>
  <span m="4507280">to</span> <span m="4507400">learn</span> <span m="4507640">when</span>
  <span m="4507730">we</span> <span m="4507850">do</span> <span m="4508060">this</span>
  <span m="4508450">is</span> <span m="4508780">that</span> <span m="4508900">the</span>
  <span m="4508990">metric</span> <span m="4509440">is</span> <span m="4509830">a</span>
  <span m="4510040">tensor</span> <span m="4510430">density</span> <span m="4510910">of</span>
  <span m="4511090">weight</span> <span m="4511660">2.</span> <span m="4514380">And</span>
  <span m="4514580">so</span> <span m="4515150">to</span> <span m="4515270">correct</span>
  <span m="4515660">it</span> <span m="4515750">to</span> <span m="4515840">get</span>
  <span m="4515990">something</span> <span m="4516200">of</span> <span m="4516320">weight</span>
  <span m="4516500">1,</span> <span m="4516710">we</span> <span m="4516830">take</span>
  <span m="4516980">a</span> <span m="4517040">square</span> <span m="4517340">root.</span></p><p><span
  m="4523740">If you're working</span> <span m="4523980">in</span> <span m="4524070">circle</span>
  <span m="4524400">coordinates,</span> <span m="4524820">does</span> <span m="4525000">that</span>
  <span m="4525180">look</span> <span m="4525330">familiar?</span> <span m="4526720">This</span>
  <span m="4526830">is,</span> <span m="4526920">in</span> <span m="4527040">fact,</span>
  <span m="4527340">exactly</span> <span m="4528180">what</span> <span m="4528570">allows</span>
  <span m="4528990">us</span> <span m="4529110">to</span> <span m="4529230">convert</span>
  <span m="4530040">differentials</span> <span m="4530970">of</span> <span m="4531180">our</span>
  <span m="4531270">coordinates.</span> <span m="4531900">Remember,</span> <span m="4532140">we're</span>
  <span m="4532230">working</span> <span m="4532470">in</span> <span m="4532560">a</span>
  <span m="4532590">coordinate</span> <span m="4533070">basis.</span> <span m="4533770">And</span>
  <span m="4533850">so</span> <span m="4534090">we</span> <span m="4534330">think</span>
  <span m="4534630">of</span> <span m="4534840">our</span> <span m="4535140">little</span>
  <span m="4535530">element</span> <span m="4536220">of</span> <span m="4537550">just</span>
  <span m="4537720">the</span> <span m="4537810">coordinates.</span> <span m="4538200">It's</span>
  <span m="4538280">just</span> <span m="4538440">dr,</span> <span m="4539040">d</span>
  <span m="4539250">theta,</span> <span m="4539820">d phi.</span> <span m="4541290">This</span>
  <span m="4541500">ends</span> <span m="4541710">up</span> <span m="4541770">being</span>
  <span m="4542070">the</span> <span m="4542160">quantity</span> <span m="4542730">that</span>
  <span m="4542880">allows</span> <span m="4543300">us</span> <span m="4543420">to</span>
  <span m="4543540">convert</span> <span m="4544500">the</span> <span m="4544590">little</span>
  <span m="4544890">triple</span> <span m="4545370">of</span> <span m="4545520">our</span>
  <span m="4545610">coordinates</span> <span m="4546390">into</span> <span m="4546690">something</span>
  <span m="4546930">that</span> <span m="4547110">has</span> <span m="4547440">the</span>
  <span m="4547530">proper</span> <span m="4548010">dimensions</span> <span m="4548730">and</span>
  <span m="4548820">form</span> <span m="4549270">to</span> <span m="4549390">actually</span>
  <span m="4549660">be</span> <span m="4549840">a</span> <span m="4549930">real</span>
  <span m="4550260">volume</span> <span m="4550710">element.</span> <span m="4551880">And</span>
  <span m="4552060">so</span> <span m="4552930">dr,</span> <span m="4553290">de</span>
  <span m="4553440">theta,</span> <span m="4553660">d phi--</span> <span m="4554180">that
  ain't</span> <span m="4554320">enough</span> <span m="4554470">volume.</span> <span
  m="4555120">But</span> <span m="4555930">r</span> <span m="4556110">squared</span>
  <span m="4556500">sine</span> <span m="4556800">theta,</span> <span m="4557380">dr,</span>
  <span m="4557500">d</span> <span m="4557610">theta,</span> <span m="4557850">d</span>
  <span m="4558130">phi--</span> <span m="4558720">that's</span> <span m="4558900">a</span>
  <span m="4558960">volume</span> <span m="4559190">element,</span> <span m="4560000">OK?</span></p><p><span
  m="4560670">So</span> <span m="4561000">basically,</span> <span m="4561300">that's</span>
  <span m="4561510">all</span> <span m="4561660">that</span> <span m="4561780">we're</span>
  <span m="4561870">doing</span> <span m="4562110">right</span> <span m="4562260">now,</span>
  <span m="4562440">is</span> <span m="4562530">we're</span> <span m="4562650">making</span>
  <span m="4562950">that</span> <span m="4563100">precise</span> <span m="4563550">and</span>
  <span m="4563640">careful.</span> <span m="4564510">And</span> <span m="4564610">that's</span>
  <span m="4564690">where</span> <span m="4564780">I</span> <span m="4564870">will</span>
  <span m="4564960">pick</span> <span m="4565140">things</span> <span m="4565410">up.</span>
  <span m="4565560">We'll</span> <span m="4565650">finish</span> <span m="4565950">that</span>
  <span m="4566190">up</span> <span m="4566400">on</span> <span m="4566640">Thursday.</span></p>
type: course
uid: fead4cb0ce8a3425215bc5e6148fa389

---
None