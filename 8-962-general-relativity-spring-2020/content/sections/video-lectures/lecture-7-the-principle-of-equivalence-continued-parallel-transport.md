---
about_this_resource_text: '<p><strong>Description: </strong>An examination of local
  coordinate transformations: proof that the metric of spacetime can be put into a
  representation that is locally flat (with &ldquo;leftover&rdquo; degrees of freedom
  corresponding to boosts and rotation).  Deviations from flatness correspond to spacetime
  curvature.  This lecture also discusses the notion of transport, which must be used
  to connect points in a manifold in order to define a proper tensor derivative.  Focus
  here is on &ldquo;parallel transport,&rdquo; which turns out to use the Christoffel
  symbol introduced in Lecture 5.</p> <p><strong>Instructor:</strong> Prof. Scott
  Hughes</p>'
course_id: 8-962-general-relativity-spring-2020
embedded_media:
- id: Video-YouTube-Stream
  media_location: gnWKpHUj11w
  parent_uid: 009e9bc81210f24c8ec57e2bed6dc256
  title: Video-YouTube-Stream
  type: Video
  uid: de1684bdb648efd0fb12ba3429b77465
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/gnWKpHUj11w/default.jpg
  parent_uid: 009e9bc81210f24c8ec57e2bed6dc256
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 4cb81dc779dd511ddaeb9a181b794e97
- id: 3Play-3PlayYouTubeid-MP4
  media_location: gnWKpHUj11w
  parent_uid: 009e9bc81210f24c8ec57e2bed6dc256
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 8b27d74bc6154b1c5a7f97b809f10a98
- id: gnWKpHUj11w.srt
  parent_uid: 009e9bc81210f24c8ec57e2bed6dc256
  technical_location: https://ocw.mit.edu/courses/physics/8-962-general-relativity-spring-2020/video-lectures/lecture-7-the-principle-of-equivalence-continued-parallel-transport/gnWKpHUj11w.srt
  title: 3play caption file
  type: null
  uid: 4a208cb2c67599107518281b38460ff0
- id: gnWKpHUj11w.pdf
  parent_uid: 009e9bc81210f24c8ec57e2bed6dc256
  technical_location: https://ocw.mit.edu/courses/physics/8-962-general-relativity-spring-2020/video-lectures/lecture-7-the-principle-of-equivalence-continued-parallel-transport/gnWKpHUj11w.pdf
  title: 3play pdf file
  type: null
  uid: 5ceefe9356be954268527b93f35628a9
- id: Caption-3Play YouTube id-SRT
  parent_uid: 009e9bc81210f24c8ec57e2bed6dc256
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 76506065ba516b6e28ec07d2cd2d2c91
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 009e9bc81210f24c8ec57e2bed6dc256
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 6178332247853ff73e0f4296a203699c
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT8.962S20/MIT8_962S20_lec07_300k.mp4
  parent_uid: 009e9bc81210f24c8ec57e2bed6dc256
  title: Video-Internet Archive-MP4
  type: Video
  uid: b0431f293f425dfe5af1afa73a90fb25
inline_embed_id: 37286719lecture7theprincipleofequivalencecontinuedparalleltransport18480828
layout: video
order_index: null
parent_uid: 740b8714e79d361c39b23aa6b6a3aaaf
related_resources_text: ''
short_url: lecture-7-the-principle-of-equivalence-continued-parallel-transport
technical_location: https://ocw.mit.edu/courses/physics/8-962-general-relativity-spring-2020/video-lectures/lecture-7-the-principle-of-equivalence-continued-parallel-transport
template_type: Tabbed
title: 'Lecture 7: The Principle of Equivalence Continued; Parallel Transport'
transcript: <p><span m="482">[SQUEAKING]</span></p><p><span m="1446">[RUSTLING]</span></p><p><span
  m="4338">[CLICKING]</span></p><p>&nbsp;</p><p><span m="11100">SCOTT HUGHES:</span>
  <span m="11130">All</span> <span m="11160">right,</span> <span m="11300">good</span>
  <span m="11580">afternoon.</span> <span m="12720">So</span> <span m="14400">today's</span>
  <span m="14760">lecture</span> <span m="15120">is</span> <span m="15360">a</span>
  <span m="15480">particularly</span> <span m="15870">important</span> <span m="16230">one.</span>
  <span m="18540">We</span> <span m="18780">are</span> <span m="18960">going</span>
  <span m="19290">to</span> <span m="19500">introduce</span> <span m="21180">the</span>
  <span m="21330">main</span> <span m="21840">physical</span> <span m="22260">principle</span>
  <span m="22710">that</span> <span m="22890">underlies</span> <span m="24150">general</span>
  <span m="24480">relativity.</span> <span m="25680">We'll</span> <span m="25770">be</span>
  <span m="25830">spending</span> <span m="26040">a</span> <span m="26100">bunch</span>
  <span m="26280">of</span> <span m="26340">time</span> <span m="27420">connecting</span>
  <span m="27840">that</span> <span m="27960">principle</span> <span m="28320">to</span>
  <span m="28440">the</span> <span m="28530">mathematics</span> <span m="29190">as</span>
  <span m="29310">the</span> <span m="29370">rest</span> <span m="29580">of</span>
  <span m="29640">the</span> <span m="29700">term</span> <span m="30010">unwinds.</span>
  <span m="31050">But</span> <span m="31170">today</span> <span m="31470">is</span>
  <span m="31590">where</span> <span m="31740">we're</span> <span m="31830">going</span>
  <span m="31930">to</span> <span m="32009">really</span> <span m="32250">lay</span>
  <span m="32500">out</span> <span m="33210">where</span> <span m="33540">the</span>
  <span m="33660">physics</span> <span m="34140">is</span> <span m="34650">in</span>
  <span m="34950">what</span> <span m="35130">is</span> <span m="35220">known</span>
  <span m="35400">as</span> <span m="35550">the</span> <span m="35640">principle</span>
  <span m="36030">of</span> <span m="36120">equivalence.</span></p><p><span m="37230">So</span>
  <span m="37350">before</span> <span m="37650">I</span> <span m="37710">get</span>
  <span m="37860">into</span> <span m="38100">that,</span> <span m="38340">just</span>
  <span m="38490">a</span> <span m="38550">quick</span> <span m="38760">recap.</span>
  <span m="39360">So</span> <span m="39630">in</span> <span m="39720">terms</span>
  <span m="40020">of</span> <span m="40200">technical</span> <span m="40620">stuff</span>
  <span m="40950">we</span> <span m="41100">did</span> <span m="41310">last</span>
  <span m="41580">time,</span> <span m="42700">the</span> <span m="42720">most</span>
  <span m="43080">important</span> <span m="43560">thing</span> <span m="43860">we</span>
  <span m="44040">did</span> <span m="44340">was</span> <span m="44700">to</span>
  <span m="44850">introduce</span> <span m="45300">these</span> <span m="45510">mathematical</span>
  <span m="46110">objects</span> <span m="46530">called</span> <span m="46830">Christoffel</span>
  <span m="47490">symbols.</span> <span m="48750">Christoffel</span> <span m="49300">symbols</span>
  <span m="49650">are</span> <span m="49710">those</span> <span m="49950">capital</span>
  <span m="50340">gammas.</span> <span m="52590">We</span> <span m="52770">began</span>
  <span m="53130">by</span> <span m="53280">thinking</span> <span m="53640">of</span>
  <span m="53700">them</span> <span m="53970">as</span> <span m="54210">just</span>
  <span m="54450">what</span> <span m="54660">you</span> <span m="54780">get</span>
  <span m="55050">when</span> <span m="55260">you</span> <span m="55380">look</span>
  <span m="55590">at</span> <span m="55710">the</span> <span m="55800">derivative</span>
  <span m="56310">of</span> <span m="56400">your</span> <span m="56520">basis</span>
  <span m="56940">objects.</span> <span m="58920">Pardon</span> <span m="59030">me
  a</span> <span m="59502">second.</span> <span m="60920">There</span> <span m="61020">was</span>
  <span m="61110">a</span> <span m="61170">lot</span> <span m="61410">of</span> <span
  m="61470">chalk</span> <span m="61800">on</span> <span m="61920">the</span> <span
  m="61980">chalkboard,</span> <span m="62370">and</span> <span m="62460">I</span>
  <span m="62520">think</span> <span m="62700">I</span> <span m="63510">inhaled</span>
  <span m="63960">half</span> <span m="64140">of</span> <span m="64260">it</span>
  <span m="64319">while</span> <span m="64470">I</span> <span m="64510">was</span>
  <span m="64620">cleaning</span> <span m="64890">it.</span></p><p><span m="66330">So</span>
  <span m="66540">take</span> <span m="66690">derivatives</span> <span m="66780">of</span>
  <span m="67060">your</span> <span m="67140">basis</span> <span m="67500">vectors.</span>
  <span m="68160">And</span> <span m="68350">there,</span> <span m="69090">you</span>
  <span m="69210">get</span> <span m="69390">something</span> <span m="69600">that's</span>
  <span m="70590">linearly</span> <span m="71130">related</span> <span m="71520">to</span>
  <span m="71670">your</span> <span m="71790">basis</span> <span m="72150">objects.</span>
  <span m="72690">And</span> <span m="72900">the</span> <span m="72990">gamma</span>
  <span m="73410">is</span> <span m="73660">the</span> <span m="73740">set</span>
  <span m="74010">of</span> <span m="75930">mathematical</span> <span m="76530">quantities</span>
  <span m="77190">that</span> <span m="77430">sets</span> <span m="77760">that</span>
  <span m="78030">linear</span> <span m="78270">relationship</span> <span m="78900">between</span>
  <span m="79260">the</span> <span m="79440">derivatives</span> <span m="80100">and</span>
  <span m="80220">the</span> <span m="80310">objects</span> <span m="80640">themselves.</span></p><p><span
  m="82860">One</span> <span m="83190">can</span> <span m="83490">build</span> <span
  m="84450">under</span> <span m="84630">the</span> <span m="84720">demand--</span>
  <span m="85320">so</span> <span m="85740">recall</span> <span m="86160">how</span>
  <span m="86310">we</span> <span m="86430">did</span> <span m="86610">this.</span>
  <span m="87150">We</span> <span m="87450">have</span> <span m="87660">a</span> <span
  m="87690">physical</span> <span m="88080">argument</span> <span m="88590">that</span>
  <span m="88740">tells</span> <span m="89100">us</span> <span m="89340">that</span>
  <span m="90050">a</span> <span m="90230">quantity</span> <span m="90720">we</span>
  <span m="90840">call</span> <span m="91080">the</span> <span m="91170">covariant</span>
  <span m="91680">derivative,</span> <span m="92650">which</span> <span m="92880">is</span>
  <span m="93090">a</span> <span m="93210">way</span> <span m="93600">of</span> <span
  m="93780">using</span> <span m="94320">these</span> <span m="94650">Christoffel</span>
  <span m="95190">symbols</span> <span m="95790">in</span> <span m="95970">order</span>
  <span m="96300">to</span> <span m="96540">get</span> <span m="96780">tensorial</span>
  <span m="97560">derivatives.</span></p><p><span m="98560">So</span> <span m="98640">if</span>
  <span m="98760">I</span> <span m="99000">look</span> <span m="99360">at</span> <span
  m="99600">just</span> <span m="99930">the</span> <span m="100020">partial</span>
  <span m="100380">derivative</span> <span m="100830">of</span> <span m="100950">a</span>
  <span m="100980">tensor,</span> <span m="102630">if</span> <span m="102780">I'm</span>
  <span m="102900">working</span> <span m="103230">in</span> <span m="103320">a</span>
  <span m="103350">general</span> <span m="103710">curvilinear</span> <span m="104190">coordinate</span>
  <span m="104520">system,</span> <span m="105900">the</span> <span m="106260">set</span>
  <span m="106500">of</span> <span m="106590">partial</span> <span m="106890">derivatives</span>
  <span m="107310">do</span> <span m="107520">not</span> <span m="107730">constitute</span>
  <span m="108750">components</span> <span m="109530">of</span> <span m="109650">a</span>
  <span m="109710">tensor.</span> <span m="110470">OK?</span> <span m="110700">I</span>
  <span m="110790">posted</span> <span m="111150">some</span> <span m="112050">notes</span>
  <span m="112360">online,</span> <span m="113970">demonstrating</span> <span m="114420">explicitly</span>
  <span m="115020">why</span> <span m="115260">that</span> <span m="115410">is.</span>
  <span m="116400">But</span> <span m="116580">in</span> <span m="116670">a</span>
  <span m="116730">nutshell,</span> <span m="117210">the</span> <span m="117300">main</span>
  <span m="117540">reason</span> <span m="117960">is</span> <span m="118350">that,</span>
  <span m="118530">when</span> <span m="118680">you</span> <span m="118770">try</span>
  <span m="119070">to</span> <span m="119190">work</span> <span m="119430">this</span>
  <span m="119700">out</span> <span m="120730">or</span> <span m="121550">when</span>
  <span m="121950">you</span> <span m="122010">go</span> <span m="122120">and</span>
  <span m="122220">you</span> <span m="122310">work</span> <span m="122460">this</span>
  <span m="122610">out,</span> <span m="122790">you</span> <span m="122880">will</span>
  <span m="123000">find</span> <span m="123300">that</span> <span m="123420">there</span>
  <span m="123540">are</span> <span m="123660">additional</span> <span m="124140">terms.</span>
  <span m="124650">It</span> <span m="124740">was</span> <span m="124830">like</span>
  <span m="125070">the</span> <span m="125190">derivative</span> <span m="126360">of</span>
  <span m="126480">the</span> <span m="126570">transformation</span> <span m="127230">matrix</span>
  <span m="127620">that</span> <span m="127710">come</span> <span m="127980">in</span>
  <span m="128160">and</span> <span m="128430">spoil</span> <span m="128940">the</span>
  <span m="129060">tensoriality</span> <span m="130110">of</span> <span m="130199">this</span>
  <span m="130350">relationship.</span></p><p><span m="131670">And</span> <span m="131790">what</span>
  <span m="131940">the</span> <span m="132030">Christoffel</span> <span m="132510">symbol</span>
  <span m="132780">does,</span> <span m="133110">as</span> <span m="133200">you</span>
  <span m="133290">guys</span> <span m="133470">are</span> <span m="133520">going</span>
  <span m="133590">to</span> <span m="133680">prove</span> <span m="133950">on</span>
  <span m="134070">P set</span> <span m="134460">three,</span> <span m="135200">it</span>
  <span m="135470">introduces</span> <span m="136110">terms</span> <span m="136680">that</span>
  <span m="136920">are</span> <span m="137100">exactly</span> <span m="137580">the</span>
  <span m="137640">same</span> <span m="137940">but</span> <span m="138030">with</span>
  <span m="138180">the</span> <span m="138270">opposite</span> <span m="138600">sign</span>
  <span m="139470">and</span> <span m="139620">cancel</span> <span m="140010">those</span>
  <span m="140220">things</span> <span m="140490">out.</span> <span m="141160">So</span>
  <span m="141240">that</span> <span m="142050">the</span> <span m="142290">covariant</span>
  <span m="143040">derivative</span> <span m="143610">is</span> <span m="143700">what</span>
  <span m="143820">I</span> <span m="143880">get</span> <span m="144090">when</span>
  <span m="144210">I</span> <span m="144510">correct</span> <span m="145050">each</span>
  <span m="145290">index</span> <span m="145740">with</span> <span m="145860">an</span>
  <span m="145950">appropriate</span> <span m="146340">factor</span> <span m="146700">of</span>
  <span m="146760">the</span> <span m="146820">Christoffel</span> <span m="147330">symbol.</span>
  <span m="148110">It</span> <span m="148290">is</span> <span m="148410">something</span>
  <span m="148710">that</span> <span m="148800">is</span> <span m="148950">a</span>
  <span m="149430">component</span> <span m="150390">of</span> <span m="150510">a</span>
  <span m="150570">tensor.</span> <span m="151540">In</span> <span m="151720">other</span>
  <span m="151800">words,</span> <span m="152010">it</span> <span m="152100">obeys</span>
  <span m="152520">the</span> <span m="152670">transformation</span> <span m="153450">laws</span>
  <span m="153750">that</span> <span m="153870">tensors</span> <span m="154350">must</span>
  <span m="154530">have.</span></p><p><span m="156480">We have</span> <span m="156660">a</span>
  <span m="156720">physical</span> <span m="157080">argument</span> <span m="157770">that</span>
  <span m="158100">essentially</span> <span m="158790">is</span> <span m="159480">something</span>
  <span m="159990">that</span> <span m="160140">is</span> <span m="160560">tensorial,</span>
  <span m="161580">in</span> <span m="161670">other</span> <span m="161790">words,</span>
  <span m="162160">both</span> <span m="162330">sides</span> <span m="162600">of the</span>
  <span m="162660">equations</span> <span m="163170">are</span> <span m="163260">good</span>
  <span m="163500">tensor</span> <span m="165060">quantities</span> <span m="165630">in</span>
  <span m="165720">one</span> <span m="165960">representation,</span> <span m="167190">have</span>
  <span m="167490">to</span> <span m="167580">be</span> <span m="167670">tensorial</span>
  <span m="168210">in</span> <span m="168300">any</span> <span m="168480">other</span>
  <span m="168630">representation.</span> <span m="170010">And</span> <span m="170130">from</span>
  <span m="170430">that,</span> <span m="170700">we</span> <span m="170850">deduced</span>
  <span m="171390">that</span> <span m="171540">the</span> <span m="171600">covariant</span>
  <span m="172050">derivative</span> <span m="172440">of</span> <span m="172560">the</span>
  <span m="172650">metric</span> <span m="173100">must</span> <span m="173490">always</span>
  <span m="173850">be</span> <span m="174000">0.</span> <span m="175080">And</span>
  <span m="175320">by</span> <span m="175680">taking</span> <span m="176100">appropriate</span>
  <span m="176550">covariant</span> <span m="176930">derivatives</span> <span m="177160">of</span>
  <span m="177240">the</span> <span m="177300">metric,</span> <span m="177930">sort</span>
  <span m="178140">of</span> <span m="178230">doing</span> <span m="178440">a</span>
  <span m="178500">bit</span> <span m="178620">of</span> <span m="178680">gymnastics</span>
  <span m="179250">with</span> <span m="179400">indices</span> <span m="180030">and</span>
  <span m="180150">sort</span> <span m="180330">of</span> <span m="180390">wiggling</span>
  <span m="180690">things</span> <span m="180900">around</span> <span m="181230">a</span>
  <span m="181290">little</span> <span m="181470">bit,</span> <span m="182320">we</span>
  <span m="182400">found</span> <span m="182790">that</span> <span m="182910">the</span>
  <span m="183190">Christoffel</span> <span m="183470">symbol</span> <span m="183810">can</span>
  <span m="183990">itself</span> <span m="184350">be</span> <span m="184500">built</span>
  <span m="184860">out</span> <span m="184980">of</span> <span m="186750">partial</span>
  <span m="187080">derivatives</span> <span m="187470">of</span> <span m="187530">the</span>
  <span m="187590">metric.</span> <span m="188130">And</span> <span m="188280">the</span>
  <span m="188370">result</span> <span m="188730">looks</span> <span m="188940">like</span>
  <span m="189120">this.</span></p><p><span m="190710">So</span> <span m="191340">that's</span>
  <span m="191580">a</span> <span m="192210">little</span> <span m="192390">bit</span>
  <span m="192510">more</span> <span m="192720">of</span> <span m="192780">an</span>
  <span m="192900">in-depth</span> <span m="193620">recap</span> <span m="194070">than</span>
  <span m="194190">I</span> <span m="194250">typically</span> <span m="194610">do.</span>
  <span m="196050">But</span> <span m="196290">I</span> <span m="196350">really</span>
  <span m="196530">want</span> <span m="196920">to</span> <span m="197070">hammer</span>
  <span m="197340">that</span> <span m="197490">home</span> <span m="197730">because</span>
  <span m="197880">this</span> <span m="198000">is</span> <span m="198120">an</span>
  <span m="198180">important</span> <span m="198570">point.</span> <span m="199690">We</span>
  <span m="199710">then</span> <span m="199890">began</span> <span m="200160">switching</span>
  <span m="200520">gears.</span> <span m="201030">And</span> <span m="201240">we're</span>
  <span m="201390">going</span> <span m="201500">to</span> <span m="201600">do</span>
  <span m="201780">something.</span></p><p><span m="202300">So</span> <span m="202410">I</span>
  <span m="202530">introduced,</span> <span m="203160">at</span> <span m="203310">the</span>
  <span m="203490">end</span> <span m="204000">of</span> <span m="204240">the</span>
  <span m="204330">previous</span> <span m="204720">lecture,</span> <span m="206550">a</span>
  <span m="206640">fairly</span> <span m="207030">silly</span> <span m="207510">argument,</span>
  <span m="208920">which,</span> <span m="209370">nonetheless,</span> <span m="209970">has</span>
  <span m="211230">an</span> <span m="211500">important</span> <span m="211890">physical</span>
  <span m="212190">concept</span> <span m="212790">to</span> <span m="212970">it.</span>
  <span m="213550">So</span> <span m="213660">where</span> <span m="213900">we</span>
  <span m="214050">were</span> <span m="214140">going</span> <span m="214500">with</span>
  <span m="214830">was</span> <span m="215070">the</span> <span m="215130">fact</span>
  <span m="215490">that,</span> <span m="216630">when</span> <span m="216990">we</span>
  <span m="217170">have</span> <span m="217380">gravity,</span> <span m="226320">we</span>
  <span m="226500">cannot</span> <span m="227670">cover</span> <span m="229410">all</span>
  <span m="231240">of</span> <span m="231420">spacetime</span> <span m="235740">with</span>
  <span m="237660">inertial</span> <span m="238140">frames,</span> <span m="242010">or</span>
  <span m="242210">I</span> <span m="242300">should</span> <span m="242510">say--</span>
  <span m="242950">I</span> <span m="243050">should</span> <span m="243240">watch</span>
  <span m="243620">my</span> <span m="243770">wording</span> <span m="244070">here--</span>
  <span m="244520">with</span> <span m="245150">an</span> <span m="246260">inertial</span>
  <span m="246740">frame.</span> <span m="247860">OK?</span> <span m="248120">We're,</span>
  <span m="248270">in</span> <span m="248360">fact,</span> <span m="248630">going</span>
  <span m="248750">to</span> <span m="248810">see</span> <span m="249020">that</span>
  <span m="249140">you</span> <span m="249200">can</span> <span m="249530">have</span>
  <span m="250040">a</span> <span m="250130">sequence</span> <span m="250580">of</span>
  <span m="250640">them.</span> <span m="250820">And</span> <span m="251300">we're</span>
  <span m="251390">going</span> <span m="251500">to</span> <span m="251570">find</span>
  <span m="251810">ways</span> <span m="252140">of</span> <span m="252230">linking</span>
  <span m="252590">them</span> <span m="252770">up.</span></p><p><span m="253050">But</span>
  <span m="253130">for</span> <span m="253280">now,</span> <span m="253650">if</span>
  <span m="253750">you</span> <span m="254050">think</span> <span m="254180">of</span>
  <span m="254270">special</span> <span m="254660">relativity</span> <span m="255260">as</span>
  <span m="255410">the</span> <span m="255500">theory</span> <span m="255770">of</span>
  <span m="255830">physics</span> <span m="256790">in</span> <span m="256910">which</span>
  <span m="257089">we</span> <span m="257180">can</span> <span m="257329">have</span>
  <span m="257510">Lorentz</span> <span m="257870">coordinates</span> <span m="258320">that</span>
  <span m="258410">cover</span> <span m="258829">the</span> <span m="258950">entire</span>
  <span m="259339">universe,</span> <span m="260360">that's</span> <span m="260630">out</span>
  <span m="260750">the</span> <span m="260839">window.</span> <span m="262140">OK,</span>
  <span m="262400">and</span> <span m="262490">so</span> <span m="262640">I'm</span>
  <span m="262700">going</span> <span m="262820">to</span> <span m="262880">skip</span>
  <span m="263150">my</span> <span m="263330">silly</span> <span m="263660">derivation.</span>
  <span m="264650">Part</span> <span m="264950">one</span> <span m="265190">of</span>
  <span m="265340">it</span> <span m="266190">is</span> <span m="266330">essentially</span>
  <span m="266750">just</span> <span m="266920">a</span> <span m="266960">motivation</span>
  <span m="267650">that</span> <span m="267890">a</span> <span m="267980">gravitational</span>
  <span m="268820">redshift</span> <span m="269450">exists.</span></p><p><span m="278170">So</span>
  <span m="278350">I</span> <span m="278470">gave</span> <span m="278770">a</span>
  <span m="278860">silly</span> <span m="279130">little</span> <span m="279310">demonstration</span>
  <span m="279910">where</span> <span m="280000">you</span> <span m="280120">imagined</span>
  <span m="280510">dropping</span> <span m="280900">a</span> <span m="280960">rock</span>
  <span m="281290">off</span> <span m="281770">of</span> <span m="282010">a</span>
  <span m="282130">tower.</span> <span m="282840">You</span> <span m="283040">had</span>
  <span m="283150">some</span> <span m="283270">kind</span> <span m="283390">of</span>
  <span m="283450">a</span> <span m="283510">magical</span> <span m="283870">device</span>
  <span m="284230">that</span> <span m="284320">converts</span> <span m="284590">it</span>
  <span m="284800">into</span> <span m="284980">a</span> <span m="285040">photon</span>
  <span m="285520">that</span> <span m="285640">shoots</span> <span m="285880">it</span>
  <span m="285970">back</span> <span m="286270">up</span> <span m="286390">and</span>
  <span m="286480">then</span> <span m="286570">converts</span> <span m="286930">it</span>
  <span m="286990">back</span> <span m="287230">into</span> <span m="287470">a</span>
  <span m="287570">rock.</span> <span m="288460">And</span> <span m="288760">you</span>
  <span m="288880">showed</span> <span m="289140">that,</span> <span m="289450">as</span>
  <span m="289720">it</span> <span m="289810">climbed</span> <span m="290290">out</span>
  <span m="290360">of</span> <span m="290410">the</span> <span m="290470">gravitational</span>
  <span m="291100">potential,</span> <span m="292240">it</span> <span m="292390">had</span>
  <span m="292720">to</span> <span m="292870">lose</span> <span m="293230">some</span>
  <span m="293410">of</span> <span m="293470">its</span> <span m="293590">energy.</span>
  <span m="294460">Or</span> <span m="294580">else,</span> <span m="294760">you</span>
  <span m="294850">would</span> <span m="294970">get</span> <span m="295150">more</span>
  <span m="295360">energy</span> <span m="295690">at</span> <span m="295780">the</span>
  <span m="295840">top</span> <span m="296170">than</span> <span m="296290">you</span>
  <span m="296380">put</span> <span m="296590">in</span> <span m="296710">when</span>
  <span m="296830">you</span> <span m="296890">initially</span> <span m="297190">dropped
  it.</span> <span m="297490">It's</span> <span m="297670">a</span> <span m="297700">way</span>
  <span m="297820">of</span> <span m="297880">preventing</span> <span m="298210">you</span>
  <span m="298300">from</span> <span m="298420">making</span> <span m="299800">perpetual</span>
  <span m="300250">motion</span> <span m="300580">machines.</span></p><p><span m="302530">That</span>
  <span m="302710">is,</span> <span m="302860">without</span> <span m="303130">a</span>
  <span m="303190">doubt,</span> <span m="303400">a</span> <span m="303430">flaky</span>
  <span m="303790">argument.</span> <span m="304090">It</span> <span m="304150">can</span>
  <span m="304240">be</span> <span m="304330">made</span> <span m="304690">a</span>
  <span m="304750">little</span> <span m="304930">bit</span> <span m="305080">more</span>
  <span m="305260">rigorous.</span> <span m="305770">But</span> <span m="306250">I</span>
  <span m="306280">didn't</span> <span m="306460">want</span> <span m="306610">to.</span>
  <span m="308380">And</span> <span m="308620">I</span> <span m="308770">will</span>
  <span m="308920">justify</span> <span m="309580">the</span> <span m="309670">reason</span>
  <span m="309880">I</span> <span m="309940">can</span> <span m="310060">do</span>
  <span m="310210">this</span> <span m="310630">is</span> <span m="311020">that</span>
  <span m="311260">this</span> <span m="311590">is,</span> <span m="311860">in</span>
  <span m="311980">fact,</span> <span m="312940">a</span> <span m="315390">highly</span>
  <span m="315780">tested</span> <span m="316290">experimental</span> <span m="317040">fact.</span>
  <span m="323710">Every</span> <span m="323820">single</span> <span m="324060">one</span>
  <span m="324240">of</span> <span m="324330">you</span> <span m="324510">has</span>
  <span m="324690">probably</span> <span m="325020">used</span> <span m="325290">this</span>
  <span m="325500">if</span> <span m="325620">you've</span> <span m="325770">ever</span>
  <span m="325980">used</span> <span m="326190">GPS</span> <span m="327450">to</span>
  <span m="327570">find</span> <span m="327810">your</span> <span m="327900">way</span>
  <span m="328140">to</span> <span m="328320">some</span> <span m="328560">location</span>
  <span m="329070">where</span> <span m="329160">you're</span> <span m="329280">supposed</span>
  <span m="329520">to</span> <span m="329610">meet</span> <span m="329730">a</span>
  <span m="329760">friend.</span></p><p><span m="331390">And</span> <span m="331470">what</span>
  <span m="331590">this</span> <span m="331740">basically</span> <span m="332130">tells</span>
  <span m="332460">me</span> <span m="333480">is</span> <span m="333840">that,</span>
  <span m="334800">if</span> <span m="334920">I</span> <span m="335040">imagine</span>
  <span m="335550">a</span> <span m="335610">tower</span> <span m="337290">of</span>
  <span m="337410">height</span> <span m="337740">h,</span> <span m="340040">if</span>
  <span m="340220">I</span> <span m="340340">shoot</span> <span m="340670">light</span>
  <span m="343150">with</span> <span m="343360">frequency</span> <span m="343990">at</span>
  <span m="344170">the</span> <span m="344260">bottom,</span> <span m="344950">omega</span>
  <span m="345290">b,</span> <span m="346990">when</span> <span m="347170">it</span>
  <span m="347260">reaches</span> <span m="347590">the</span> <span m="347650">top,</span>
  <span m="349540">it'll</span> <span m="349720">have</span> <span m="349840">a</span>
  <span m="349870">different</span> <span m="350170">frequency,</span> <span m="350560">omega</span>
  <span m="350910">t,</span> <span m="352020">where</span> <span m="352180">these</span>
  <span m="352390">are</span> <span m="352450">related</span> <span m="352930">by</span>
  <span m="353990">omega</span> <span m="354760">t</span> <span m="355270">equals,</span>
  <span m="359430">and</span> <span m="359590">I'm</span> <span m="359750">going to</span>
  <span m="359870">put</span> <span m="360010">my</span> <span m="360160">c</span>
  <span m="360380">squareds</span> <span m="360730">back</span> <span m="360940">in</span>
  <span m="361030">there,</span> <span m="361170">just</span> <span m="361300">to</span>
  <span m="361380">keep</span> <span m="361540">it</span> <span m="361600">all</span>
  <span m="361690">complete.</span> <span m="363600">OK?</span></p><p><span m="363910">So</span>
  <span m="364090">this</span> <span m="364360">is,</span> <span m="364810">I</span>
  <span m="364960">emphasize,</span> <span m="365530">a</span> <span m="367150">very</span>
  <span m="367480">precisely</span> <span m="369610">calibrated</span> <span m="370180">experimental</span>
  <span m="370810">result.</span> <span m="372100">There</span> <span m="372280">are</span>
  <span m="372370">many</span> <span m="372610">ways</span> <span m="372820">of</span>
  <span m="372880">doing</span> <span m="373150">it,</span> <span m="373340">some</span>
  <span m="373510">silly,</span> <span m="373810">some</span> <span m="374020">serious.</span>
  <span m="375200">The</span> <span m="375310">silly</span> <span m="375550">one</span>
  <span m="375680">was</span> <span m="375790">sort</span> <span m="375940">of</span>
  <span m="376000">fun.</span> <span m="376300">But</span> <span m="376420">it</span>
  <span m="376480">does</span> <span m="376690">actually</span> <span m="376960">capture</span>
  <span m="377410">the</span> <span m="377530">experimental</span> <span m="378100">fact.</span>
  <span m="378600">OK?</span> <span m="378820">The</span> <span m="378940">key</span>
  <span m="379120">experimental</span> <span m="379660">fact</span> <span m="380470">is</span>
  <span m="380800">that</span> <span m="380950">it's</span> <span m="381070">necessary</span>
  <span m="381790">for</span> <span m="382120">light</span> <span m="382450">to</span>
  <span m="383440">lose</span> <span m="383740">energy</span> <span m="384070">as</span>
  <span m="384220">it</span> <span m="384280">climbs</span> <span m="384580">out</span>
  <span m="384670">of</span> <span m="384730">the</span> <span m="384790">gravitational</span>
  <span m="385360">field,</span> <span m="385690">in</span> <span m="386080">essence,</span>
  <span m="386800">because</span> <span m="387220">it's</span> <span m="387310">possible,</span>
  <span m="388570">thanks</span> <span m="388810">to</span> <span m="388870">quantum</span>
  <span m="389170">field</span> <span m="389380">theory,</span> <span m="389590">to</span>
  <span m="389680">convert</span> <span m="390010">photons</span> <span m="390490">into</span>
  <span m="390640">particles</span> <span m="391750">and</span> <span m="391840">particles</span>
  <span m="392230">into</span> <span m="392380">photons.</span> <span m="393040">This</span>
  <span m="393190">is</span> <span m="393250">a</span> <span m="393280">way</span>
  <span m="393400">of</span> <span m="393460">conserving</span> <span m="393850">energy.</span></p><p><span
  m="396070">OK,</span> <span m="396490">so</span> <span m="396610">this</span> <span
  m="396760">was</span> <span m="396910">just</span> <span m="397060">part</span>
  <span m="397390">one</span> <span m="397750">of</span> <span m="397840">this</span>
  <span m="397990">argument</span> <span m="398410">that</span> <span m="398500">we</span>
  <span m="398620">cannot</span> <span m="398920">cover</span> <span m="399310">all</span>
  <span m="399520">of</span> <span m="399580">spacetime</span> <span m="400590">with</span>
  <span m="401060">an</span> <span m="401500">inertial</span> <span m="401890">frame.</span>
  <span m="405710">So</span> <span m="405860">here's</span> <span m="406070">part</span>
  <span m="406310">two</span> <span m="406490">of</span> <span m="406580">the</span>
  <span m="406670">argument.</span> <span m="410750">Suppose</span> <span m="411350">there</span>
  <span m="411500">was,</span> <span m="411840">in</span> <span m="411940">fact,</span>
  <span m="412260">a</span> <span m="412360">very</span> <span m="412820">large</span>
  <span m="413330">region</span> <span m="413630">of</span> <span m="413690">space--</span>
  <span m="414020">now</span> <span m="414080">let's</span> <span m="414200">say</span>
  <span m="414290">it's</span> <span m="414410">near</span> <span m="414620">the</span>
  <span m="414770">Earth's</span> <span m="414950">surface--</span> <span m="415820">that</span>
  <span m="416030">could</span> <span m="416630">be</span> <span m="416750">covered</span>
  <span m="417140">by</span> <span m="417320">a</span> <span m="417380">single</span>
  <span m="417680">Lorentz</span> <span m="418010">frame.</span> <span m="443260">OK?</span></p><p><span
  m="443780">So</span> <span m="443960">I</span> <span m="444020">want</span> <span
  m="444170">you to</span> <span m="444290">imagine</span> <span m="444740">that</span>
  <span m="444860">you're</span> <span m="444950">sending</span> <span m="445220">your</span>
  <span m="445310">beam</span> <span m="445550">of</span> <span m="445640">light</span>
  <span m="446030">up.</span> <span m="446460">And</span> <span m="446620">we're</span>
  <span m="446720">going</span> <span m="446840">to</span> <span m="446900">take</span>
  <span m="447080">advantage</span> <span m="447440">of</span> <span m="447500">the</span>
  <span m="447560">fact</span> <span m="447800">that</span> <span m="447890">light</span>
  <span m="448160">is</span> <span m="448460">wave</span> <span m="448760">like.</span>
  <span m="449870">So what</span> <span m="450070">I</span> <span m="450120">want</span>
  <span m="450260">you</span> <span m="450310">to</span> <span m="450410">do</span>
  <span m="450740">is</span> <span m="451010">think</span> <span m="451430">of</span>
  <span m="452180">the</span> <span m="452270">spacetime</span> <span m="452960">trajectory</span>
  <span m="453590">of</span> <span m="453740">successive</span> <span m="454340">crests</span>
  <span m="455000">of</span> <span m="455120">this</span> <span m="455270">wave</span>
  <span m="456110">as</span> <span m="456290">it</span> <span m="456350">climbs</span>
  <span m="456800">out</span> <span m="456860">of</span> <span m="456920">the</span>
  <span m="456980">gravitational</span> <span m="457490">potential.</span></p><p><span
  m="478470">So I&quot;m</span> <span m="478660">going to</span> <span m="478780">make</span>
  <span m="478950">my</span> <span m="479070">spacetime</span> <span m="479610">diagram</span>
  <span m="480000">the</span> <span m="480090">way</span> <span m="480210">we</span>
  <span m="480330">like</span> <span m="480510">to</span> <span m="480600">do</span>
  <span m="480780">it</span> <span m="482160">with</span> <span m="482340">time</span>
  <span m="482700">running</span> <span m="483030">up.</span> <span m="484670">And</span>
  <span m="484770">so</span> <span m="485130">this</span> <span m="485370">direction</span>
  <span m="485850">represents</span> <span m="487950">height.</span> <span m="488400">So</span>
  <span m="488610">down</span> <span m="488910">here</span> <span m="489390">is</span>
  <span m="489960">the</span> <span m="490020">bottom</span> <span m="490350">of</span>
  <span m="490410">the</span> <span m="490500">tower.</span> <span m="490770">So</span>
  <span m="490890">let's</span> <span m="491100">just</span> <span m="491340">make</span>
  <span m="491490">the</span> <span m="491550">drawing</span> <span m="491820">clearer.</span>
  <span m="492850">Let's</span> <span m="492900">let</span> <span m="493020">this</span>
  <span m="493230">tick</span> <span m="493500">be</span> <span m="493620">the</span>
  <span m="493710">bottom</span> <span m="494070">of</span> <span m="494130">the</span>
  <span m="494190">tower.</span> <span m="499270">This</span> <span m="499450">tick</span>
  <span m="499690">over</span> <span m="499870">here</span> <span m="500080">will</span>
  <span m="500170">be</span> <span m="500260">the</span> <span m="500350">top.</span></p><p><span
  m="506030">Now</span> <span m="506210">if</span> <span m="506300">we</span> <span
  m="506420">were</span> <span m="506510">just</span> <span m="506810">in</span> <span
  m="506930">special</span> <span m="507290">relativity,</span> <span m="507860">there</span>
  <span m="507950">was</span> <span m="508070">no</span> <span m="508250">gravity,</span>
  <span m="508710">we</span> <span m="508820">know</span> <span m="508970">light</span>
  <span m="509150">would</span> <span m="509240">just</span> <span m="509390">move</span>
  <span m="509570">on</span> <span m="509660">a</span> <span m="509720">45</span>
  <span m="510140">degree</span> <span m="510380">angle</span> <span m="510650">on</span>
  <span m="510740">this</span> <span m="510920">thing.</span> <span m="513179">We</span>
  <span m="513260">don't</span> <span m="513440">know</span> <span m="513770">yet</span>
  <span m="514220">what</span> <span m="514400">gravity</span> <span m="514850">is</span>
  <span m="515000">going</span> <span m="515210">to</span> <span m="515299">do</span>
  <span m="515510">to</span> <span m="515630">this</span> <span m="515809">light.</span>
  <span m="516580">OK?</span> <span m="516770">But</span> <span m="516950">you</span>
  <span m="517340">can</span> <span m="517520">imagine</span> <span m="518000">that</span>
  <span m="518120">whatever</span> <span m="518390">it's</span> <span m="518510">going</span>
  <span m="518690">to</span> <span m="518750">do,</span> <span m="518900">it's</span>
  <span m="518990">going</span> <span m="519070">to</span> <span m="519350">bend</span>
  <span m="519679">it</span> <span m="519770">away</span> <span m="520520">in</span>
  <span m="520700">some</span> <span m="520970">way</span> <span m="521210">from</span>
  <span m="521539">the</span> <span m="521630">trajectory</span> <span m="522260">that</span>
  <span m="522470">special</span> <span m="522799">relativity</span> <span m="523220">would</span>
  <span m="523340">predict.</span></p><p><span m="524510">So</span> <span m="524600">let's</span>
  <span m="524720">just</span> <span m="524930">imagine</span> <span m="526250">that</span>
  <span m="526550">crest</span> <span m="527060">one</span> <span m="528080">of</span>
  <span m="528200">this</span> <span m="528350">light,</span> <span m="529930">it</span>
  <span m="530090">follows</span> <span m="530630">some</span> <span m="530930">trajectory</span>
  <span m="531500">in</span> <span m="531590">spacetime</span> <span m="532220">that</span>
  <span m="532400">maybe</span> <span m="532740">looks</span> <span m="533030">like</span>
  <span m="533210">this.</span> <span m="537740">So</span> <span m="537820">here</span>
  <span m="538090">is</span> <span m="538240">the</span> <span m="538330">world</span>
  <span m="538630">line</span> <span m="541790">of</span> <span m="541930">crest</span>
  <span m="542180">one.</span> <span m="549510">So</span> <span m="551100">what</span>
  <span m="551220">about</span> <span m="551430">the</span> <span m="551520">world</span>
  <span m="551820">line</span> <span m="552030">of</span> <span m="552120">credit</span>
  <span m="552420">two?</span> <span m="559780">So</span> <span m="560110">let's</span>
  <span m="560290">think</span> <span m="560440">about</span> <span m="560620">what</span>
  <span m="560740">the</span> <span m="560800">world</span> <span m="561010">line</span>
  <span m="561160">of</span> <span m="561250">credit</span> <span m="561540">two</span>
  <span m="561730">must</span> <span m="562030">be</span> <span m="562780">under</span>
  <span m="563140">this</span> <span m="563350">assumption</span> <span m="563950">that</span>
  <span m="564100">we</span> <span m="564250">can,</span> <span m="564830">in</span>
  <span m="564910">fact,</span> <span m="565400">cover</span> <span m="565690">all</span>
  <span m="565840">of</span> <span m="565930">spacetime</span> <span m="566410">with</span>
  <span m="566530">a</span> <span m="566590">single</span> <span m="567010">Lorentz</span>
  <span m="567450">frame.</span> <span m="568123">OK?</span></p><p><span m="568810">If</span>
  <span m="569170">that</span> <span m="569440">is</span> <span m="569710">the</span>
  <span m="569800">case,</span> <span m="586890">so</span> <span m="587080">if</span>
  <span m="587290">that</span> <span m="587470">is</span> <span m="587620">the</span>
  <span m="587680">case,</span> <span m="589390">no</span> <span m="589750">position</span>
  <span m="590790">and</span> <span m="590890">no</span> <span m="591100">moment</span>
  <span m="591430">is</span> <span m="591550">special.</span> <span m="592690">OK?</span>
  <span m="593050">Everything</span> <span m="593500">is</span> <span m="593620">actually</span>
  <span m="593920">translation</span> <span m="594640">invariant</span> <span m="595150">in</span>
  <span m="595270">both</span> <span m="595480">time</span> <span m="595780">and</span>
  <span m="595870">space.</span> <span m="625490">So</span> <span m="625680">the</span>
  <span m="625770">second</span> <span m="626130">crest</span> <span m="626670">is</span>
  <span m="626820">going</span> <span m="627060">to</span> <span m="627120">be</span>
  <span m="627300">emitted</span> <span m="628170">one</span> <span m="628560">wave</span>
  <span m="628950">period</span> <span m="629340">later.</span> <span m="630720">But</span>
  <span m="631380">there's</span> <span m="631590">absolutely</span> <span m="631920">nothing</span>
  <span m="632250">special</span> <span m="632700">about</span> <span m="632910">spacetime</span>
  <span m="633420">one</span> <span m="633690">wave</span> <span m="633960">period</span>
  <span m="634290">later.</span> <span m="634700">And</span> <span m="634800">as</span>
  <span m="634950">it</span> <span m="635010">moves</span> <span m="635280">along,</span>
  <span m="636830">there</span> <span m="637100">can't</span> <span m="637270">be</span>
  <span m="637380">anything</span> <span m="637620">special</span> <span m="638040">about</span>
  <span m="638280">this.</span></p><p><span m="638700">If</span> <span m="638970">it</span>
  <span m="639090">is</span> <span m="639360">to</span> <span m="639450">be</span>
  <span m="639750">a</span> <span m="639900">global</span> <span m="640470">Lorentz</span>
  <span m="640890">frame,</span> <span m="641610">whatever</span> <span m="642060">the</span>
  <span m="642150">trajectory</span> <span m="642720">is</span> <span m="643020">that</span>
  <span m="643170">the</span> <span m="643590">crest</span> <span m="643920">two</span>
  <span m="644130">follows</span> <span m="644440">through</span> <span m="644630">spacetime,</span>
  <span m="645630">it's</span> <span m="645780">got</span> <span m="645990">to</span>
  <span m="646080">be</span> <span m="646320">congruent</span> <span m="647580">with</span>
  <span m="647730">the</span> <span m="647820">trajectory</span> <span m="648270">of</span>
  <span m="648330">crest</span> <span m="648630">one.</span> <span m="648900">I've</span>
  <span m="649080">got</span> <span m="649320">to</span> <span m="649410">be</span>
  <span m="649530">able</span> <span m="649710">to</span> <span m="649800">just</span>
  <span m="649950">simply</span> <span m="650520">slide</span> <span m="651030">them</span>
  <span m="651210">on</span> <span m="651360">top</span> <span m="651600">of</span>
  <span m="651720">each</span> <span m="651900">other.</span> <span m="652487">OK?</span>
  <span m="653710">That</span> <span m="653880">is</span> <span m="654030">what</span>
  <span m="654360">this</span> <span m="654600">assumption</span> <span m="655320">demands.</span></p><p><span
  m="671280">So</span> <span m="677970">this is</span> <span m="678150">going</span>
  <span m="678400">to look</span> <span m="678510">something</span> <span m="678750">like</span>
  <span m="678930">this.</span> <span m="679580">OK?</span> <span m="680290">Artwork</span>
  <span m="680790">a</span> <span m="680850">little</span> <span m="681030">bit</span>
  <span m="681180">off.</span> <span m="681790">The</span> <span m="681930">key</span>
  <span m="682080">thing</span> <span m="682260">which</span> <span m="682380">I</span>
  <span m="682410">want</span> <span m="682530">to</span> <span m="682770">emphasize,</span>
  <span m="683500">though,</span> <span m="685220">is</span> <span m="685430">that</span>
  <span m="685610">if</span> <span m="685790">this</span> <span m="686000">guy</span>
  <span m="686240">is</span> <span m="686390">congruent,</span> <span m="689780">the</span>
  <span m="689930">spacing</span> <span m="690620">between</span> <span m="690980">crest</span>
  <span m="691250">one</span> <span m="691460">and</span> <span m="691550">crest</span>
  <span m="691850">two</span> <span m="692180">at</span> <span m="692300">the</span>
  <span m="692390">bottom,</span> <span m="692850">let's</span> <span m="692870">call</span>
  <span m="693080">it</span> <span m="693170">delta</span> <span m="693530">tb,</span>
  <span m="695030">there'll</span> <span m="695210">be</span> <span m="695360">some</span>
  <span m="695840">spacing</span> <span m="696470">between</span> <span m="696800">the</span>
  <span m="696890">two</span> <span m="697220">at</span> <span m="697310">the</span>
  <span m="697400">top.</span> <span m="697820">We'll</span> <span m="697910">call</span>
  <span m="698060">it</span> <span m="698150">delta</span> <span m="698480">tt.</span>
  <span m="702170">They</span> <span m="702320">must</span> <span m="702500">be</span>
  <span m="702620">the</span> <span m="702710">same.</span></p><p><span m="725660">But</span>
  <span m="725690">that's</span> <span m="725980">[INAUDIBLE].</span> <span m="726670">That</span>
  <span m="726910">is</span> <span m="727060">just</span> <span m="727240">a</span>
  <span m="727300">period</span> <span m="727600">of</span> <span m="727660">the</span>
  <span m="727750">wave.</span> <span m="728750">And</span> <span m="728860">that's</span>
  <span m="729070">just</span> <span m="729370">up</span> <span m="729460">to</span>
  <span m="729550">a</span> <span m="729610">factor</span> <span m="729850">of</span>
  <span m="729940">2</span> <span m="730120">pi.</span> <span m="730460">That's</span>
  <span m="730540">1</span> <span m="730750">over</span> <span m="731540">the</span>
  <span m="731620">frequency.</span> <span m="740640">So</span> <span m="740690">this</span>
  <span m="740870">implies</span> <span m="742250">delta</span> <span m="742550">tb</span>
  <span m="744260">is</span> <span m="744470">not</span> <span m="744920">equal</span>
  <span m="746450">to</span> <span m="746600">delta</span> <span m="746900">t</span>
  <span m="747320">at</span> <span m="747410">the</span> <span m="747470">top.</span>
  <span m="748550">So</span> <span m="748760">a</span> <span m="748850">frequency</span>
  <span m="749450">at</span> <span m="749570">the</span> <span m="749660">top</span>
  <span m="750020">is</span> <span m="750170">smaller.</span> <span m="751220">So</span>
  <span m="751460">the</span> <span m="751550">period</span> <span m="751820">will</span>
  <span m="751940">actually</span> <span m="752240">be</span> <span m="752360">a</span>
  <span m="752390">little</span> <span m="752540">bit</span> <span m="752660">larger.</span></p><p><span
  m="755000">So</span> <span m="756620">when</span> <span m="756740">you</span> <span
  m="756830">think</span> <span m="756950">about</span> <span m="757100">this</span>
  <span m="757250">argument</span> <span m="757550">carefully,</span> <span m="758030">the</span>
  <span m="758150">weak</span> <span m="758450">point</span> <span m="758900">is</span>
  <span m="759290">this</span> <span m="759740">assumption</span> <span m="760790">that</span>
  <span m="761240">I</span> <span m="761480">can</span> <span m="761720">actually</span>
  <span m="762020">cover</span> <span m="762350">the</span> <span m="762440">region</span>
  <span m="762710">with</span> <span m="762830">a</span> <span m="762860">large</span>
  <span m="763190">Lorentz</span> <span m="763490">frame.</span> <span m="763770">Remember</span>
  <span m="764000">what</span> <span m="764150">this</span> <span m="764300">is</span>
  <span m="764420">telling</span> <span m="764720">me</span> <span m="765350">is</span>
  <span m="765890">that,</span> <span m="767120">essentially,</span> <span m="768120">there</span>
  <span m="768340">is</span> <span m="768500">no</span> <span m="768920">special</span>
  <span m="769460">direction,</span> <span m="770050">right?</span> <span m="770840">I</span>
  <span m="770930">can</span> <span m="771080">do</span> <span m="771170">translation,</span>
  <span m="771770">variance</span> <span m="772100">in</span> <span m="772190">time</span>
  <span m="772580">and</span> <span m="772670">space,</span> <span m="773030">and</span>
  <span m="773120">they're</span> <span m="773270">all</span> <span m="773450">the</span>
  <span m="773540">same.</span> <span m="774710">But</span> <span m="774830">that's</span>
  <span m="775010">actually</span> <span m="775310">completely</span> <span m="775700">contradicted</span>
  <span m="776270">by</span> <span m="776450">common</span> <span m="776870">sense.</span>
  <span m="777330">If</span> <span m="777350">there</span> <span m="777440">were</span>
  <span m="777560">no</span> <span m="777740">special</span> <span m="778070">direction,</span>
  <span m="779930">why</span> <span m="780140">did</span> <span m="780260">it</span>
  <span m="780320">go</span> <span m="780470">down?</span> <span m="780980">There's</span>
  <span m="781160">obviously</span> <span m="781490">something</span> <span m="781730">special</span>
  <span m="782210">about</span> <span m="782570">down,</span> <span m="783260">right?</span></p><p><span
  m="791670">So</span> <span m="791820">we</span> <span m="792000">conclude</span>
  <span m="792570">we</span> <span m="792720">cannot</span> <span m="793170">have</span>
  <span m="793650">a</span> <span m="794250">global</span> <span m="795240">Lorentz</span>
  <span m="795600">frame</span> <span m="796560">when</span> <span m="796740">we've</span>
  <span m="796890">got</span> <span m="797040">gravity.</span> <span m="809420">And</span>
  <span m="810500">in</span> <span m="810740">case you</span> <span m="810810">want</span>
  <span m="810870">to</span> <span m="810960">read</span> <span m="811130">a</span>
  <span m="811160">little</span> <span m="811280">bit</span> <span m="811370">more</span>
  <span m="811610">about</span> <span m="811910">it,</span> <span m="813120">I'll</span>
  <span m="813140">just</span> <span m="813380">give</span> <span m="813740">a</span>
  <span m="813800">highlight</span> <span m="814370">that</span> <span m="814520">this</span>
  <span m="814790">argument</span> <span m="815270">was</span> <span m="815450">originally</span>
  <span m="815780">developed</span> <span m="820080">by</span> <span m="820230">a</span>
  <span m="820290">gentleman</span> <span m="820680">named</span> <span m="821100">Alfred</span>
  <span m="824760">Shield.</span> <span m="835870">So</span> <span m="842330">that's</span>
  <span m="842540">unfortunate,</span> <span m="843580">OK,</span> <span m="843920">from</span>
  <span m="844100">sort</span> <span m="844280">of</span> <span m="844550">a</span>
  <span m="844700">philosophical</span> <span m="845360">perspective</span> <span
  m="845960">because</span> <span m="846770">the</span> <span m="847010">fact</span>
  <span m="847520">that</span> <span m="850190">we</span> <span m="850280">don't</span>
  <span m="850490">have</span> <span m="850700">a</span> <span m="850730">global</span>
  <span m="851090">Lorentz</span> <span m="851420">frame</span> <span m="852530">makes</span>
  <span m="852710">you</span> <span m="852800">think,</span> <span m="853070">oh,</span>
  <span m="853310">crap.</span> <span m="853670">What</span> <span m="853940">are</span>
  <span m="854030">we</span> <span m="854120">going</span> <span m="854220">to</span>
  <span m="854330">do</span> <span m="854600">with</span> <span m="854780">that</span>
  <span m="854990">framework</span> <span m="855530">we</span> <span m="855680">spent</span>
  <span m="856010">all</span> <span m="856340">this</span> <span m="856520">time</span>
  <span m="856790">developing?</span> <span m="857320">OK?</span></p><p><span m="858630">The</span>
  <span m="859370">existence</span> <span m="859820">of</span> <span m="859940">a</span>
  <span m="859980">Lorentz</span> <span m="860360">frame</span> <span m="860870">and</span>
  <span m="861320">many</span> <span m="861510">of the</span> <span m="861590">mathematics</span>
  <span m="862160">we've</span> <span m="862280">been</span> <span m="862370">developing</span>
  <span m="862820">for</span> <span m="862910">the</span> <span m="862970">past</span>
  <span m="863630">few</span> <span m="864380">lectures,</span> <span m="865430">they</span>
  <span m="865580">all</span> <span m="865880">center</span> <span m="866270">around</span>
  <span m="866510">things</span> <span m="866780">you</span> <span m="866870">can</span>
  <span m="866990">do</span> <span m="867320">in</span> <span m="867560">Lorentz</span>
  <span m="867920">frames.</span> <span m="868640">So</span> <span m="868790">it's</span>
  <span m="868890">kind of</span> <span m="869040">like,</span> <span m="869240">OK,</span>
  <span m="869540">so</span> <span m="869840">do</span> <span m="870110">we</span>
  <span m="870260">just</span> <span m="870380">throw</span> <span m="870680">all</span>
  <span m="870830">that</span> <span m="871040">out?</span> <span m="873540">Well,</span>
  <span m="873720">here</span> <span m="875040">is</span> <span m="875400">where</span>
  <span m="876630">Einstein's</span> <span m="877350">key</span> <span m="878040">physical</span>
  <span m="878670">insight</span> <span m="879450">came</span> <span m="879750">in</span>
  <span m="880380">and</span> <span m="881910">gave</span> <span m="882180">us</span>
  <span m="882330">the</span> <span m="882420">physical</span> <span m="882810">tools</span>
  <span m="883290">that</span> <span m="883830">then</span> <span m="884090">needed</span>
  <span m="884280">to</span> <span m="884340">be</span> <span m="884430">coupled</span>
  <span m="884850">to</span> <span m="884940">some</span> <span m="885390">mathematics</span>
  <span m="886110">in</span> <span m="886170">order</span> <span m="886260">to</span>
  <span m="886380">turn</span> <span m="886590">it</span> <span m="886650">into</span>
  <span m="886800">something</span> <span m="887070">that</span> <span m="887160">can</span>
  <span m="887280">be</span> <span m="887370">worked</span> <span m="887640">with</span>
  <span m="888730">but,</span> <span m="888990">nonetheless,</span> <span m="889710">really</span>
  <span m="890010">save</span> <span m="890310">the</span> <span m="890370">day.</span></p><p><span
  m="900540">So</span> <span m="900720">the</span> <span m="900780">key</span> <span
  m="901020">insight</span> <span m="902190">has</span> <span m="902820">there's</span>
  <span m="902850">a few</span> <span m="903090">steps</span> <span m="903470">in</span>
  <span m="903540">it.</span> <span m="903660">So</span> <span m="903870">first</span>
  <span m="904230">thing,</span> <span m="905760">I</span> <span m="905850">was</span>
  <span m="905970">very</span> <span m="906150">careful</span> <span m="906510">to</span>
  <span m="906570">use</span> <span m="906810">the</span> <span m="906870">word</span>
  <span m="907110">global</span> <span m="907830">when</span> <span m="907980">I</span>
  <span m="908040">ruled</span> <span m="908280">out</span> <span m="908400">the</span>
  <span m="908490">existence</span> <span m="908880">of</span> <span m="908940">Lorentz</span>
  <span m="909270">frames.</span> <span m="920420">But</span> <span m="920550">I'm</span>
  <span m="920700">allowed</span> <span m="921210">to</span> <span m="921480">have</span>
  <span m="922440">local</span> <span m="923100">Lorentz</span> <span m="923460">frames.</span>
  <span m="924100">Let's</span> <span m="924210">see.</span> <span m="924390">What</span>
  <span m="924600">does</span> <span m="924780">that</span> <span m="924960">actually</span>
  <span m="925290">mean?</span></p><p><span m="935820">So</span> <span m="936270">I'll</span>
  <span m="936370">remind</span> <span m="936740">that</span> <span m="936890">a</span>
  <span m="937390">Lorentz</span> <span m="937910">frame</span> <span m="938780">is</span>
  <span m="938990">a</span> <span m="939050">tool</span> <span m="939500">that</span>
  <span m="939680">we</span> <span m="939830">use</span> <span m="940220">to</span>
  <span m="940310">describe</span> <span m="941120">inertial</span> <span m="941750">observers.</span>
  <span m="942270">In</span> <span m="942350">fact,</span> <span m="943950">we</span>
  <span m="944030">often</span> <span m="944390">call</span> <span m="944720">them</span>
  <span m="944990">inertial</span> <span m="945530">frames</span> <span m="946010">because</span>
  <span m="946460">they're</span> <span m="946640">sort</span> <span m="946820">of</span>
  <span m="946880">the</span> <span m="946970">constant</span> <span m="947420">coordinates.</span>
  <span m="948050">They</span> <span m="948230">represent</span> <span m="948650">the</span>
  <span m="948710">coordinates</span> <span m="949160">of</span> <span m="949280">an</span>
  <span m="949370">inertial</span> <span m="949880">observer</span> <span m="950480">who</span>
  <span m="950630">happens</span> <span m="950840">to</span> <span m="950900">be</span>
  <span m="951020">at</span> <span m="951260">rest</span> <span m="951680">in</span>
  <span m="951860">that</span> <span m="952940">Lorentz</span> <span m="953300">coordinate</span>
  <span m="953660">system.</span> <span m="954460">So</span> <span m="954560">let's</span>
  <span m="954570">switch</span> <span m="954760">over.</span> <span m="954840">Let's</span>
  <span m="955070">start</span> <span m="955260">calling them</span> <span m="955710">inertial</span>
  <span m="956060">frames</span> <span m="956360">for</span> <span m="956480">just</span>
  <span m="956750">a</span> <span m="956810">moment.</span></p><p><span m="964130">So</span>
  <span m="964370">an</span> <span m="964520">inertial</span> <span m="964970">frame</span>
  <span m="968670">means</span> <span m="969030">that</span> <span m="969210">there</span>
  <span m="969390">is</span> <span m="969630">nothing</span> <span m="970080">accelerating,</span>
  <span m="977150">so</span> <span m="977310">no</span> <span m="977610">accelerations</span>
  <span m="981530">on</span> <span m="981850">observers</span> <span m="982570">or</span>
  <span m="982750">objects</span> <span m="983290">at</span> <span m="983470">rest</span>
  <span m="984010">in</span> <span m="984130">that</span> <span m="984310">frame.</span>
  <span m="991750">In</span> <span m="991770">other</span> <span m="991890">words,</span>
  <span m="992460">no</span> <span m="992640">forces</span> <span m="993000">are</span>
  <span m="993090">acting.</span> <span m="1004790">Einstein's</span> <span m="1005360">insight</span>
  <span m="1008690">was</span> <span m="1008870">to</span> <span m="1008960">recognize</span>
  <span m="1009770">that</span> <span m="1010070">the</span> <span m="1010250">next</span>
  <span m="1010670">best</span> <span m="1011120">thing</span> <span m="1014060">is</span>
  <span m="1014240">a</span> <span m="1014480">freely</span> <span m="1015260">falling</span>
  <span m="1015950">frame.</span> <span m="1035674">OK?</span></p><p><span m="1036670">If</span>
  <span m="1036750">you</span> <span m="1036960">are</span> <span m="1037079">in</span>
  <span m="1038190">a</span> <span m="1038280">freely</span> <span m="1038970">falling</span>
  <span m="1039630">frame,</span> <span m="1041775">to</span> <span m="1042200">you,</span>
  <span m="1042889">it</span> <span m="1043160">sure</span> <span m="1043369">as</span>
  <span m="1043490">hell</span> <span m="1043640">seems</span> <span m="1043910">like</span>
  <span m="1044089">there's a</span> <span m="1044240">force</span> <span m="1044540">acting</span>
  <span m="1044810">on</span> <span m="1044930">it</span> <span m="1045020">and</span>
  <span m="1045349">there's</span> <span m="1045619">some</span> <span m="1045800">accelerations</span>
  <span m="1046460">acting</span> <span m="1046700">upon</span> <span m="1046970">it.</span>
  <span m="1047880">But let's</span> <span m="1047930">imagine</span> <span m="1048380">you're</span>
  <span m="1048560">in</span> <span m="1048830">this</span> <span m="1049010">freely</span>
  <span m="1049340">falling</span> <span m="1049670">frame.</span> <span m="1050750">And</span>
  <span m="1052740">you</span> <span m="1052820">have</span> <span m="1052940">a</span>
  <span m="1053000">bunch</span> <span m="1053240">of</span> <span m="1053360">small</span>
  <span m="1053750">objects</span> <span m="1054320">that</span> <span m="1054530">you</span>
  <span m="1054650">release</span> <span m="1055040">near</span> <span m="1055250">you.</span>
  <span m="1056130">Let's</span> <span m="1056330">see if I can</span> <span m="1056450">find</span>
  <span m="1056630">some</span> <span m="1056780">bits</span> <span m="1056960">of</span>
  <span m="1057020">broken</span> <span m="1057350">chalk.</span></p><p><span m="1062650">So</span>
  <span m="1062830">when</span> <span m="1062980">you're</span> <span m="1063100">in</span>
  <span m="1063280">this</span> <span m="1063460">really</span> <span m="1063670">falling</span>
  <span m="1064030">frame--</span> <span m="1068680">this</span> <span m="1068830">was</span>
  <span m="1068920">a</span> <span m="1068950">lot</span> <span m="1069130">easier</span>
  <span m="1069310">when</span> <span m="1069400">I</span> <span m="1069430">was</span>
  <span m="1069520">younger.</span> <span m="1069880">All</span> <span m="1069940">right,</span>
  <span m="1070570">when</span> <span m="1070660">you're</span> <span m="1070750">in</span>
  <span m="1070930">this</span> <span m="1071080">really</span> <span m="1071320">falling</span>
  <span m="1071650">frame,</span> <span m="1072100">OK,</span> <span m="1072460">and</span>
  <span m="1072670">these</span> <span m="1072850">objects</span> <span m="1073240">are</span>
  <span m="1073330">all</span> <span m="1073420">falling,</span> <span m="1075500">there</span>
  <span m="1075580">is</span> <span m="1075760">no</span> <span m="1076090">acceleration</span>
  <span m="1076840">of</span> <span m="1076900">these</span> <span m="1077080">objects</span>
  <span m="1077710">relative</span> <span m="1078850">to</span> <span m="1079600">you.</span>
  <span m="1082360">The</span> <span m="1082450">reason</span> <span m="1082750">for</span>
  <span m="1082900">this</span> <span m="1083290">is</span> <span m="1083530">that</span>
  <span m="1083680">the</span> <span m="1083800">gravitational</span> <span m="1084730">force</span>
  <span m="1085810">is</span> <span m="1086110">proportional</span> <span m="1087100">to</span>
  <span m="1087340">the</span> <span m="1087460">mass.</span></p><p><span m="1088630">And</span>
  <span m="1088810">so</span> <span m="1089110">the</span> <span m="1089230">fact</span>
  <span m="1092680">that</span> <span m="1093940">we</span> <span m="1094150">have</span>
  <span m="1094600">f</span> <span m="1096430">equals</span> <span m="1096970">ma.</span>
  <span m="1098830">And</span> <span m="1099130">fg</span> <span m="1100180">proportional</span>
  <span m="1101440">to</span> <span m="1101590">mass</span> <span m="1106460">means</span>
  <span m="1106670">that</span> <span m="1106820">all</span> <span m="1107150">objects</span>
  <span m="1110780">in</span> <span m="1111020">that</span> <span m="1112010">freely</span>
  <span m="1112520">falling</span> <span m="1112910">frame--</span> <span m="1113750">this</span>
  <span m="1114140">is</span> <span m="1114300">a</span> <span m="1114350">term</span>
  <span m="1114710">that I'm going to</span> <span m="1114820">start</span> <span
  m="1115040">using</span> <span m="1115310">a</span> <span m="1115370">lot.</span>
  <span m="1120550">So</span> <span m="1120670">I'm</span> <span m="1120730">just</span>
  <span m="1120850">going</span> <span m="1120930">to</span> <span m="1121060">abbreviate</span>
  <span m="1121570">it</span> <span m="1123380">FFF.</span> <span m="1124540">If</span>
  <span m="1124600">I get</span> <span m="1124690">really</span> <span m="1124900">lazy,</span>
  <span m="1125170">I</span> <span m="1125230">might</span> <span m="1125410">call</span>
  <span m="1125560">it</span> <span m="1125620">an</span> <span m="1125770">F</span>
  <span m="1125860">cubed.</span> <span m="1126580">Anyway,</span> <span m="1126940">l</span>
  <span m="1127210">objects</span> <span m="1127600">that</span> <span m="1127720">are</span>
  <span m="1127810">in</span> <span m="1128020">that</span> <span m="1128230">freely</span>
  <span m="1128770">falling</span> <span m="1129340">frame,</span> <span m="1130480">they're</span>
  <span m="1130690">experiencing</span> <span m="1131380">the</span> <span m="1131470">same</span>
  <span m="1131770">acceleration.</span> <span m="1132850">And</span> <span m="1133000">so</span>
  <span m="1133210">they</span> <span m="1133420">experience</span> <span m="1134230">0</span>
  <span m="1135040">relative</span> <span m="1135880">acceleration</span> <span m="1139950">at</span>
  <span m="1140070">least</span> <span m="1140340">in</span> <span m="1140430">the</span>
  <span m="1140550">absence</span> <span m="1141240">of</span> <span m="1141570">other</span>
  <span m="1141930">forces,</span> <span m="1142560">OK?</span> <span m="1143110">Perhaps</span>
  <span m="1143280">one</span> <span m="1143430">of</span> <span m="1143490">them</span>
  <span m="1143580">is</span> <span m="1143700">charging.</span> <span m="1144090">There's</span>
  <span m="1144240">an</span> <span m="1144300">electric</span> <span m="1144600">force.</span></p><p><span
  m="1145800">Well,</span> <span m="1145950">then it</span> <span m="1146170">sort</span>
  <span m="1146370">of</span> <span m="1146430">suggests</span> <span m="1146850">that</span>
  <span m="1146940">the</span> <span m="1147090">interesting</span> <span m="1147510">force</span>
  <span m="1148770">is</span> <span m="1150150">the</span> <span m="1151530">extra</span>
  <span m="1151830">force</span> <span m="1152130">provided</span> <span m="1152550">to
  that</span> <span m="1152790">relative</span> <span m="1153750">to</span> <span
  m="1154020">what</span> <span m="1154290">we</span> <span m="1154560">call</span>
  <span m="1154950">the</span> <span m="1155070">gravitational</span> <span m="1155670">force</span>
  <span m="1156150">that</span> <span m="1156300">is</span> <span m="1156390">driving</span>
  <span m="1156660">this</span> <span m="1156830">freefall.</span> <span m="1184590">So</span>
  <span m="1188530">I</span> <span m="1188650">urge</span> <span m="1188860">you</span>
  <span m="1188920">to</span> <span m="1189010">start</span> <span m="1189250">getting</span>
  <span m="1189490">comfortable</span> <span m="1189940">with</span> <span m="1190090">this</span>
  <span m="1190240">idea</span> <span m="1191590">because</span> <span m="1192040">we're</span>
  <span m="1192160">going</span> <span m="1192230">to</span> <span m="1192340">find</span>
  <span m="1192730">this</span> <span m="1192940">to</span> <span m="1193030">be--</span>
  <span m="1193230">so</span> <span m="1193350">one</span> <span m="1193570">thing,</span>
  <span m="1193820">which</span> <span m="1193840">I'm</span> <span m="1193900">going</span>
  <span m="1194020">to</span> <span m="1194080">do</span> <span m="1194320">in</span>
  <span m="1194410">a</span> <span m="1194470">couple</span> <span m="1194660">of</span>
  <span m="1194710">minutes,</span> <span m="1196570">is</span> <span m="1197380">actually</span>
  <span m="1197620">a</span> <span m="1197680">little</span> <span m="1197890">calculation</span>
  <span m="1199720">that</span> <span m="1199990">shows</span> <span m="1200380">me</span>
  <span m="1202300">I</span> <span m="1202420">can,</span> <span m="1202750">in</span>
  <span m="1202870">fact,</span> <span m="1203380">always</span> <span m="1207980">find</span>
  <span m="1209630">a</span> <span m="1210020">Lorentz</span> <span m="1211010">frame</span>
  <span m="1211970">in</span> <span m="1212090">the</span> <span m="1212150">vicinity</span>
  <span m="1212720">of</span> <span m="1212870">any</span> <span m="1213080">point</span>
  <span m="1213410">in</span> <span m="1213530">spacetime.</span> <span m="1214426">OK?</span></p><p><span
  m="1215100">And</span> <span m="1215180">so</span> <span m="1215300">we're</span>
  <span m="1215390">going</span> <span m="1215510">to</span> <span m="1215570">actually</span>
  <span m="1215810">regard</span> <span m="1216380">that</span> <span m="1216800">Lorentz</span>
  <span m="1217190">frame</span> <span m="1217970">as</span> <span m="1218240">being</span>
  <span m="1218660">the</span> <span m="1218750">preferred</span> <span m="1219770">coordinate</span>
  <span m="1220130">system</span> <span m="1220550">of</span> <span m="1220670">a</span>
  <span m="1220730">freely</span> <span m="1221120">falling</span> <span m="1221420">observer,</span>
  <span m="1221810">one</span> <span m="1222080">who</span> <span m="1222260">is</span>
  <span m="1222350">not</span> <span m="1222740">accelerated</span> <span m="1223490">relative</span>
  <span m="1224390">to</span> <span m="1224510">freefall</span> <span m="1225200">at</span>
  <span m="1225380">that</span> <span m="1225560">point.</span> <span m="1226460">We</span>
  <span m="1226630">are</span> <span m="1226760">not</span> <span m="1227060">in</span>
  <span m="1227210">freefall</span> <span m="1227630">right</span> <span m="1227780">now.</span>
  <span m="1227930">The</span> <span m="1228020">damn</span> <span m="1228230">floor</span>
  <span m="1228530">is</span> <span m="1228620">pushing</span> <span m="1228890">us</span>
  <span m="1229010">out</span> <span m="1229100">of</span> <span m="1229160">the</span>
  <span m="1229220">way.</span> <span m="1230090">But</span> <span m="1230510">in</span>
  <span m="1231020">this</span> <span m="1231320">way</span> <span m="1231740">of</span>
  <span m="1231980">doing</span> <span m="1232310">things,</span> <span m="1233360">we</span>
  <span m="1233540">would</span> <span m="1233660">actually</span> <span m="1233900">regard</span>
  <span m="1234380">us</span> <span m="1234620">as</span> <span m="1234710">being</span>
  <span m="1235400">the</span> <span m="1235580">complicated</span> <span m="1236390">people,</span>
  <span m="1236730">OK?</span> <span m="1237380">Someone</span> <span m="1237830">who</span>
  <span m="1237950">is</span> <span m="1238070">merrily</span> <span m="1238430">plummeting</span>
  <span m="1238790">to</span> <span m="1238880">their</span> <span m="1239030">death,</span>
  <span m="1239900">they're</span> <span m="1240260">actually</span> <span m="1240650">the</span>
  <span m="1240740">simple</span> <span m="1241130">observers,</span> <span m="1241650">who</span>
  <span m="1241710">are</span> <span m="1242000">doing</span> <span m="1242360">what</span>
  <span m="1242960">they</span> <span m="1243080">should</span> <span m="1243380">be</span>
  <span m="1243470">doing,</span> <span m="1243710">in</span> <span m="1243800">some</span>
  <span m="1244010">sense.</span></p><p><span m="1247730">So</span> <span m="1248960">the</span>
  <span m="1249050">key</span> <span m="1249260">thing,</span> <span m="1250720">a</span>
  <span m="1250850">way</span> <span m="1251060">of</span> <span m="1251150">saying</span>
  <span m="1251480">this,</span> <span m="1251670">so</span> <span m="1251870">coming</span>
  <span m="1252110">back</span> <span m="1252290">to</span> <span m="1252380">this</span>
  <span m="1252550">and</span> <span m="1252940">just</span> <span m="1253130">one</span>
  <span m="1253310">more</span> <span m="1253430">point</span> <span m="1253700">about</span>
  <span m="1253910">that,</span> <span m="1255140">because</span> <span m="1255590">there</span>
  <span m="1255770">are</span> <span m="1255890">no</span> <span m="1257180">relative</span>
  <span m="1257840">accelerations,</span> <span m="1260840">within</span> <span m="1261260">this</span>
  <span m="1261470">frame,</span> <span m="1266320">objects</span> <span m="1266830">maintain</span>
  <span m="1268180">their</span> <span m="1268510">relative</span> <span m="1269320">velocities.</span>
  <span m="1280670">That's</span> <span m="1280880">basically</span> <span m="1281510">the</span>
  <span m="1281660">definition</span> <span m="1282350">of</span> <span m="1282440">something</span>
  <span m="1282740">that</span> <span m="1282860">is</span> <span m="1282950">an</span>
  <span m="1283150">inertial.</span> <span m="1283400">If</span> <span m="1283550">I</span>
  <span m="1283640">have</span> <span m="1283820">a</span> <span m="1283880">frame</span>
  <span m="1284300">where</span> <span m="1284510">everything</span> <span m="1285680">is--</span>
  <span m="1286400">two</span> <span m="1286670">objects</span> <span m="1287240">are</span>
  <span m="1287450">moving</span> <span m="1287820">with</span> <span m="1287920">respect</span>
  <span m="1288140">to each</span> <span m="1288290">other</span> <span m="1288440">at</span>
  <span m="1288500">1</span> <span m="1288740">meter</span> <span m="1288950">per</span>
  <span m="1289070">second,</span> <span m="1289430">they're</span> <span m="1289670">always</span>
  <span m="1290060">moving</span> <span m="1290300">at</span> <span m="1290390">1</span>
  <span m="1290570">meter</span> <span m="1290780">per</span> <span m="1290870">second,</span>
  <span m="1291650">that's</span> <span m="1291890">inertial.</span> <span m="1293090">And</span>
  <span m="1293450">so</span> <span m="1293570">this</span> <span m="1293640">sort</span>
  <span m="1293810">of</span> <span m="1293870">demands</span> <span m="1294320">that</span>
  <span m="1294440">we</span> <span m="1294560">do</span> <span m="1294770">all</span>
  <span m="1294920">of</span> <span m="1295010">our</span> <span m="1295100">experiments</span>
  <span m="1295700">in</span> <span m="1295820">plummeting</span> <span m="1296180">elevators</span>
  <span m="1296720">or</span> <span m="1296990">in</span> <span m="1297170">space,</span>
  <span m="1297830">right?</span></p><p><span m="1298500">OK,</span> <span m="1298670">obviously,</span>
  <span m="1298970">you</span> <span m="1299060">can't</span> <span m="1299270">do</span>
  <span m="1299450">that.</span> <span m="1299760">So</span> <span m="1299780">there's</span>
  <span m="1299900">some</span> <span m="1300020">complications</span> <span m="1300710">we're</span>
  <span m="1300810">going to</span> <span m="1300860">have</span> <span m="1300950">to</span>
  <span m="1301040">learn</span> <span m="1301220">the</span> <span m="1301280">math</span>
  <span m="1301530">to</span> <span m="1302750">describe.</span> <span m="1304250">But</span>
  <span m="1304430">this</span> <span m="1304550">is</span> <span m="1304610">the</span>
  <span m="1304670">way</span> <span m="1304760">we're</span> <span m="1304880">going</span>
  <span m="1304980">to</span> <span m="1305100">from</span> <span m="1305330">now</span>
  <span m="1305520">on</span> <span m="1305690">think</span> <span m="1305900">about</span>
  <span m="1306080">things</span> <span m="1306360">is</span> <span m="1306450">that</span>
  <span m="1306530">the</span> <span m="1306620">freely</span> <span m="1307100">falling</span>
  <span m="1307490">frame</span> <span m="1308420">is</span> <span m="1308810">the</span>
  <span m="1308930">most</span> <span m="1309170">natural</span> <span m="1309650">generalization</span>
  <span m="1311330">of</span> <span m="1311450">an</span> <span m="1311510">inertial</span>
  <span m="1311900">frame</span> <span m="1312230">that</span> <span m="1312350">we</span>
  <span m="1312440">describe</span> <span m="1313550">using</span> <span m="1313820">Lorentz</span>
  <span m="1314120">coordinates.</span> <span m="1315980">Now</span> <span m="1316160">before</span>
  <span m="1316550">I</span> <span m="1317390">discuss</span> <span m="1317780">a</span>
  <span m="1317810">few</span> <span m="1317990">details</span> <span m="1318410">about</span>
  <span m="1318650">this,</span> <span m="1319550">an</span> <span m="1319760">important</span>
  <span m="1320150">thing</span> <span m="1320360">that</span> <span m="1320480">is</span>
  <span m="1320570">worth</span> <span m="1320810">noting</span> <span m="1321410">is</span>
  <span m="1321860">that</span> <span m="1323440">a</span> <span m="1323510">very</span>
  <span m="1323840">important</span> <span m="1324290">aspect</span> <span m="1324740">of</span>
  <span m="1324860">any</span> <span m="1325100">realistic</span> <span m="1325580">source</span>
  <span m="1325880">of</span> <span m="1325970">gravity</span> <span m="1327140">is</span>
  <span m="1327350">that</span> <span m="1327530">it</span> <span m="1327650">is</span>
  <span m="1327800">not</span> <span m="1328340">uniform.</span> <span m="1329794">OK?</span></p><p><span
  m="1330650">Gravity</span> <span m="1331640">here</span> <span m="1332840">is</span>
  <span m="1333350">a</span> <span m="1333410">little</span> <span m="1333590">bit</span>
  <span m="1333710">stronger</span> <span m="1334490">than</span> <span m="1334670">gravity</span>
  <span m="1335150">on</span> <span m="1335330">the</span> <span m="1335420">ceiling,</span>
  <span m="1335850">OK?</span> <span m="1336710">And</span> <span m="1336920">it's
  a</span> <span m="1336980">lot</span> <span m="1337220">stronger</span> <span m="1337850">than</span>
  <span m="1338030">gravity</span> <span m="1338720">in</span> <span m="1338960">geostationary</span>
  <span m="1339770">orbit.</span> <span m="1341560">We</span> <span m="1342020">call</span>
  <span m="1342500">this</span> <span m="1342680">variation</span> <span m="1343280">in</span>
  <span m="1343370">gravity</span> <span m="1344030">tides.</span> <span m="1349370">So</span>
  <span m="1349720">tides</span> <span m="1350230">break</span> <span m="1350560">down</span>
  <span m="1353770">the</span> <span m="1353890">notion</span> <span m="1354970">of</span>
  <span m="1357460">uniform</span> <span m="1358240">freely</span> <span m="1358720">falling</span>
  <span m="1359140">frames.</span></p><p><span m="1369570">What</span> <span m="1369690">this</span>
  <span m="1369840">is</span> <span m="1369930">telling</span> <span m="1370260">us</span>
  <span m="1370620">is</span> <span m="1371100">that</span> <span m="1372240">this</span>
  <span m="1372390">idea,</span> <span m="1372780">if</span> <span m="1372900">I'm</span>
  <span m="1373020">going</span> <span m="1373120">to</span> <span m="1373230">create</span>
  <span m="1373740">this</span> <span m="1374280">inertial</span> <span m="1374790">frame</span>
  <span m="1375180">that</span> <span m="1375300">is</span> <span m="1375630">essentially</span>
  <span m="1376110">a</span> <span m="1376230">freely</span> <span m="1376620">falling</span>
  <span m="1377010">frame,</span> <span m="1377860">it</span> <span m="1377880">will</span>
  <span m="1378030">have</span> <span m="1378210">to</span> <span m="1378300">be</span>
  <span m="1378420">a</span> <span m="1378510">finite</span> <span m="1378990">size.</span>
  <span m="1380400">Hence,</span> <span m="1380760">it's</span> <span m="1380910">local</span>
  <span m="1381540">and</span> <span m="1381660">not</span> <span m="1381870">global.</span>
  <span m="1383010">OK,</span> <span m="1384000">physically,</span> <span m="1384610">this</span>
  <span m="1384740">is</span> <span m="1385050">telling</span> <span m="1385410">me</span>
  <span m="1385740">that,</span> <span m="1386010">if</span> <span m="1386160">I</span>
  <span m="1386280">have</span> <span m="1386670">a</span> <span m="1386820">really</span>
  <span m="1387780">tall</span> <span m="1389640">freely</span> <span m="1390030">falling</span>
  <span m="1390390">elevator,</span> <span m="1392840">and</span> <span m="1393000">I'm</span>
  <span m="1393270">here,</span> <span m="1396350">I</span> <span m="1396410">have</span>
  <span m="1396530">one</span> <span m="1396740">friend</span> <span m="1397040">here</span>
  <span m="1398760">and</span> <span m="1398900">one</span> <span m="1399080">friend</span>
  <span m="1399350">down</span> <span m="1399560">there,</span> <span m="1402140">even</span>
  <span m="1402350">if</span> <span m="1402440">we</span> <span m="1402590">start</span>
  <span m="1403430">absolutely</span> <span m="1403970">at</span> <span m="1404180">rest,</span>
  <span m="1404810">let's</span> <span m="1404960">say</span> <span m="1405050">we're</span>
  <span m="1405170">at</span> <span m="1405290">rest.</span> <span m="1405530">We</span>
  <span m="1405620">measure</span> <span m="1405890">reference</span> <span m="1406340">back</span>
  <span m="1406490">to</span> <span m="1406580">the</span> <span m="1406640">walls</span>
  <span m="1407030">of</span> <span m="1407090">this</span> <span m="1407200">elevator.</span>
  <span m="1407470">It's</span> <span m="1407570">a</span> <span m="1407600">very</span>
  <span m="1407810">stiff</span> <span m="1408140">elevator.</span> <span m="1409550">We</span>
  <span m="1409760">will</span> <span m="1409940">see</span> <span m="1410450">the</span>
  <span m="1410540">three</span> <span m="1410810">of</span> <span m="1410930">us</span>
  <span m="1411080">diverge</span> <span m="1411470">away</span> <span m="1411650">from</span>
  <span m="1411830">each</span> <span m="1411980">other</span> <span m="1412160">with</span>
  <span m="1412280">time,</span> <span m="1412630">OK?</span></p><p><span m="1413360">Because</span>
  <span m="1413750">this</span> <span m="1413930">person,</span> <span m="1414320">let's</span>
  <span m="1414430">say</span> <span m="1414620">earth</span> <span m="1414860">is</span>
  <span m="1414980">down</span> <span m="1415220">here,</span> <span m="1415820">this</span>
  <span m="1416020">person</span> <span m="1416260">is</span> <span m="1416390">feeling</span>
  <span m="1417170">the--</span> <span m="1417920">and</span> <span m="1418100">using</span>
  <span m="1418310">Newtonian</span> <span m="1418670">intuition,</span> <span m="1419420">gravity</span>
  <span m="1419750">is</span> <span m="1419840">a</span> <span m="1419870">little</span>
  <span m="1420020">stronger.</span> <span m="1421460">Gravity</span> <span m="1421820">is</span>
  <span m="1422210">medium.</span> <span m="1423200">Gravity</span> <span m="1423590">is</span>
  <span m="1423680">weak.</span> <span m="1424520">And</span> <span m="1424610">so</span>
  <span m="1425210">as</span> <span m="1425450">viewed</span> <span m="1425810">in</span>
  <span m="1425990">that</span> <span m="1426170">freely</span> <span m="1426530">falling</span>
  <span m="1426830">frame,</span> <span m="1427130">let's</span> <span m="1427250">say</span>
  <span m="1427400">we</span> <span m="1427520">center</span> <span m="1427880">it</span>
  <span m="1428030">on</span> <span m="1428240">me</span> <span m="1428660">here</span>
  <span m="1428900">in</span> <span m="1428960">the</span> <span m="1429040">middle,</span>
  <span m="1430100">I</span> <span m="1430250">will</span> <span m="1430340">see</span>
  <span m="1430490">the</span> <span m="1430550">person</span> <span m="1430880">in
  the</span> <span m="1430940">top</span> <span m="1431270">go</span> <span m="1431510">up,</span>
  <span m="1431930">the person</span> <span m="1432200">at</span> <span m="1432260">the</span>
  <span m="1432320">bottom</span> <span m="1432650">go</span> <span m="1432770">down.</span>
  <span m="1435580">Another</span> <span m="1435880">way</span> <span m="1436060">of</span>
  <span m="1436150">saying</span> <span m="1436570">this,</span> <span m="1441040">so</span>
  <span m="1441240">let</span> <span m="1441330">me</span> <span m="1441420">just</span>
  <span m="1441690">say</span> <span m="1441930">that,</span> <span m="1442140">so</span>
  <span m="1442350">a</span> <span m="1442410">very</span> <span m="1442650">tall</span>
  <span m="1443040">elevator,</span> <span m="1445800">we'll</span> <span m="1445950">see</span>
  <span m="1446310">a</span> <span m="1446460">separation</span> <span m="1449440">of</span>
  <span m="1449710">freefall</span> <span m="1453420">since</span> <span m="1453660">gravity</span>
  <span m="1454080">is</span> <span m="1454230">not</span> <span m="1454410">uniform.</span></p><p><span
  m="1468720">But</span> <span m="1469110">there's</span> <span m="1469240">another</span>
  <span m="1469540">way</span> <span m="1469690">of</span> <span m="1469750">saying</span>
  <span m="1470110">this.</span> <span m="1472770">And</span> <span m="1473030">what</span>
  <span m="1473810">this</span> <span m="1473990">is</span> <span m="1474080">telling</span>
  <span m="1474350">me</span> <span m="1474500">is</span> <span m="1474710">imagine</span>
  <span m="1475160">I</span> <span m="1475250">made</span> <span m="1475430">a</span>
  <span m="1475490">spacetime</span> <span m="1476090">diagram</span> <span m="1477410">that</span>
  <span m="1477590">shows</span> <span m="1477980">trajectories</span> <span m="1479600">of</span>
  <span m="1480200">the</span> <span m="1480350">three</span> <span m="1480710">of</span>
  <span m="1480830">us,</span> <span m="1484080">so</span> <span m="1484230">the</span>
  <span m="1484350">three</span> <span m="1484590">of</span> <span m="1484710">us</span>
  <span m="1484890">that</span> <span m="1484990">are</span> <span m="1485080">plummeting</span>
  <span m="1485550">in</span> <span m="1485670">this</span> <span m="1485850">elevator,</span>
  <span m="1486510">OK?</span> <span m="1497800">What</span> <span m="1497950">we</span>
  <span m="1498130">find,</span> <span m="1498610">if</span> <span m="1498700">we</span>
  <span m="1498820">make</span> <span m="1499030">our</span> <span m="1499120">trajectories</span>
  <span m="1499690">as</span> <span m="1499780">we</span> <span m="1499900">fall--</span>
  <span m="1500230">in</span> <span m="1500440">fact, let's</span> <span m="1500560">just</span>
  <span m="1500680">go</span> <span m="1500770">ahead</span> <span m="1500890">and</span>
  <span m="1500980">make</span> <span m="1501100">a</span> <span m="1501160">little</span>
  <span m="1501280">sketch</span> <span m="1501580">of</span> <span m="1501640">this.</span></p><p><span
  m="1503950">OK,</span> <span m="1504190">so</span> <span m="1504310">let's</span>
  <span m="1504490">say</span> <span m="1505810">here</span> <span m="1506350">is</span>
  <span m="1506980">the</span> <span m="1507100">middle.</span> <span m="1510330">Here</span>
  <span m="1510690">is</span> <span m="1510870">the</span> <span m="1510960">top.</span>
  <span m="1511530">Here</span> <span m="1511740">is</span> <span m="1511830">the</span>
  <span m="1511920">bottom.</span> <span m="1512280">I'm</span> <span m="1512490">going
  to</span> <span m="1512550">draw</span> <span m="1512970">this</span> <span m="1513360">in</span>
  <span m="1513540">coordinates</span> <span m="1515460">that</span> <span m="1515730">are</span>
  <span m="1516150">fixed</span> <span m="1516750">on</span> <span m="1517020">the</span>
  <span m="1517110">person</span> <span m="1517470">in</span> <span m="1517530">the</span>
  <span m="1517620">middle.</span> <span m="1519060">So</span> <span m="1519180">the</span>
  <span m="1519270">person</span> <span m="1519610">the</span> <span m="1519690">middle,</span>
  <span m="1520270">in</span> <span m="1520410">their</span> <span m="1520530">freely</span>
  <span m="1520800">falling</span> <span m="1521070">frame,</span> <span m="1522660">they</span>
  <span m="1522780">think</span> <span m="1522930">they're</span> <span m="1523050">standing</span>
  <span m="1523410">still.</span> <span m="1525870">They</span> <span m="1526050">see</span>
  <span m="1526200">the</span> <span m="1526290">person</span> <span m="1526590">at</span>
  <span m="1526680">the</span> <span m="1526740">top</span> <span m="1528120">moving</span>
  <span m="1528360">up</span> <span m="1528480">and</span> <span m="1528540">away,</span>
  <span m="1529330">the</span> <span m="1529920">person</span> <span m="1530140">at</span>
  <span m="1530220">the</span> <span m="1530280">bottom</span> <span m="1530850">moving</span>
  <span m="1531090">up</span> <span m="1531240">and</span> <span m="1531300">away.</span></p><p><span
  m="1533308">It's</span> <span m="1533750">a</span> <span m="1533900">very</span>
  <span m="1534230">similar</span> <span m="1534590">story</span> <span m="1535010">to</span>
  <span m="1535140">the</span> <span m="1535180">little</span> <span m="1535370">parable</span>
  <span m="1535820">I</span> <span m="1536580">sketched</span> <span m="1536900">of</span>
  <span m="1537020">that</span> <span m="1537170">light</span> <span m="1537440">pole</span>
  <span m="1537740">moving</span> <span m="1537980">up.</span> <span m="1538430">These</span>
  <span m="1538670">are</span> <span m="1538790">not</span> <span m="1539180">congruent</span>
  <span m="1539870">trajectories.</span> <span m="1551140">Another</span> <span m="1551470">way</span>
  <span m="1551590">to</span> <span m="1551680">say</span> <span m="1551920">this</span>
  <span m="1552250">is</span> <span m="1552370">that,</span> <span m="1552520">in</span>
  <span m="1552610">any</span> <span m="1552790">moment,</span> <span m="1553750">if</span>
  <span m="1554170">I</span> <span m="1554260">think</span> <span m="1554440">of</span>
  <span m="1554530">these</span> <span m="1554920">as</span> <span m="1556360">world</span>
  <span m="1556720">lines,</span> <span m="1557290">I</span> <span m="1557380">can,</span>
  <span m="1557620">at</span> <span m="1557770">any</span> <span m="1557950">moment</span>
  <span m="1558280">along</span> <span m="1558580">the</span> <span m="1558640">world</span>
  <span m="1558910">line,</span> <span m="1560020">I</span> <span m="1560140">can</span>
  <span m="1560260">draw</span> <span m="1560500">its</span> <span m="1560620">tangent</span>
  <span m="1561040">vector.</span> <span m="1565960">The</span> <span m="1566120">tangents</span>
  <span m="1567710">do</span> <span m="1568010">not</span> <span m="1569810">remain</span>
  <span m="1571460">parallel.</span></p><p><span m="1576420">Now</span> <span m="1576570">I'm</span>
  <span m="1576630">going</span> <span m="1576750">to</span> <span m="1576810">take</span>
  <span m="1577080">you</span> <span m="1577170">back</span> <span m="1577470">to</span>
  <span m="1580320">probably,</span> <span m="1581910">I</span> <span m="1581940">don't</span>
  <span m="1582060">know</span> <span m="1582120">when</span> <span m="1582300">you</span>
  <span m="1582420">guys</span> <span m="1582630">all</span> <span m="1582750">learned</span>
  <span m="1583020">this,</span> <span m="1583230">but</span> <span m="1583410">when</span>
  <span m="1583560">you</span> <span m="1583650">first</span> <span m="1583890">started</span>
  <span m="1584100">learning</span> <span m="1584370">about</span> <span m="1584580">geometry.</span>
  <span m="1585120">For</span> <span m="1585230">me,</span> <span m="1585330">it</span>
  <span m="1585360">was</span> <span m="1585510">in</span> <span m="1585600">middle</span>
  <span m="1585840">school.</span> <span m="1586800">And</span> <span m="1587070">when</span>
  <span m="1587190">you</span> <span m="1587280">first</span> <span m="1587520">started</span>
  <span m="1588030">learning</span> <span m="1588300">about</span> <span m="1588480">geometry,</span>
  <span m="1589070">you</span> <span m="1589120">were</span> <span m="1589190">usually</span>
  <span m="1589410">doing</span> <span m="1589620">geometry</span> <span m="1590070">on</span>
  <span m="1590190">the</span> <span m="1590250">plane.</span> <span m="1591150">And</span>
  <span m="1591780">they</span> <span m="1591900">gave</span> <span m="1592140">you</span>
  <span m="1592230">various</span> <span m="1592620">axioms</span> <span m="1593100">about</span>
  <span m="1593280">the</span> <span m="1593370">way</span> <span m="1593550">things</span>
  <span m="1593850">behaved.</span></p><p><span m="1594690">One</span> <span m="1594960">of</span>
  <span m="1595020">them</span> <span m="1595170">is</span> <span m="1595290">now</span>
  <span m="1595500">known</span> <span m="1595770">as</span> <span m="1595920">Euclid's</span>
  <span m="1596610">parallelism</span> <span m="1597330">axiom.</span> <span m="1608730">And</span>
  <span m="1608850">it</span> <span m="1608940">states</span> <span m="1609330">that</span>
  <span m="1609510">if</span> <span m="1609630">I</span> <span m="1609780">have</span>
  <span m="1610800">two</span> <span m="1611100">lines</span> <span m="1611520">that</span>
  <span m="1611670">start</span> <span m="1612030">parallel,</span> <span m="1612780">they</span>
  <span m="1613110">remain</span> <span m="1613620">parallel.</span> <span m="1631470">If</span>
  <span m="1631570">you</span> <span m="1631660">dig</span> <span m="1631870">into</span>
  <span m="1632050">the</span> <span m="1632170">history</span> <span m="1632470">of</span>
  <span m="1632560">mathematics,</span> <span m="1633700">this</span> <span m="1634000">axiom</span>
  <span m="1634510">bugged</span> <span m="1634960">the</span> <span m="1635140">crap</span>
  <span m="1636010">out</span> <span m="1636220">of</span> <span m="1636310">people</span>
  <span m="1636700">for</span> <span m="1637810">many,</span> <span m="1638300">many</span>
  <span m="1638470">years,</span> <span m="1639400">OK?</span> <span m="1640300">Because</span>
  <span m="1641830">when</span> <span m="1641980">you</span> <span m="1642070">look</span>
  <span m="1642400">at</span> <span m="1642550">pictures</span> <span m="1643090">on</span>
  <span m="1643180">a</span> <span m="1643240">piece</span> <span m="1643450">of</span>
  <span m="1643510">paper</span> <span m="1644110">or</span> <span m="1644530">on</span>
  <span m="1644710">a</span> <span m="1644770">chalkboard</span> <span m="1645280">or</span>
  <span m="1645340">something</span> <span m="1645610">like</span> <span m="1645730">that,</span>
  <span m="1645940">it</span> <span m="1646030">seems</span> <span m="1646540">right,</span>
  <span m="1647505">OK?</span></p><p><span m="1647900">But</span> <span m="1648040">it</span>
  <span m="1648160">really</span> <span m="1648400">can't</span> <span m="1648730">be</span>
  <span m="1649300">justified</span> <span m="1649990">quite</span> <span m="1650230">as</span>
  <span m="1650350">rigorously</span> <span m="1650770">as</span> <span m="1650860">many</span>
  <span m="1651100">other</span> <span m="1651430">axioms</span> <span m="1652000">that</span>
  <span m="1652180">Euclid</span> <span m="1652540">wrote</span> <span m="1652720">down.</span>
  <span m="1653380">And</span> <span m="1653470">it</span> <span m="1653530">turns</span>
  <span m="1653830">out,</span> <span m="1653980">there's</span> <span m="1654160">an</span>
  <span m="1654310">underlying</span> <span m="1654760">assumption.</span> <span m="1655950">The</span>
  <span m="1656080">assumption</span> <span m="1656920">is</span> <span m="1657220">that</span>
  <span m="1657400">you</span> <span m="1657580">are</span> <span m="1657700">drawing</span>
  <span m="1658240">your</span> <span m="1658360">lines</span> <span m="1659200">on</span>
  <span m="1659590">a</span> <span m="1659800">flat</span> <span m="1660490">manifold.</span></p><p><span
  m="1677130">There's</span> <span m="1677310">a</span> <span m="1677340">ready</span>
  <span m="1677640">counterexample.</span> <span m="1680710">Go</span> <span m="1680920">to</span>
  <span m="1680980">the</span> <span m="1681100">Earth's</span> <span m="1681370">equator.</span>
  <span m="1683830">You</span> <span m="1684100">start,</span> <span m="1684600">say,</span>
  <span m="1684970">somewhere</span> <span m="1685330">in</span> <span m="1685480">Brazil.</span>
  <span m="1686440">Your</span> <span m="1686560">friend</span> <span m="1686830">starts</span>
  <span m="1687130">somewhere</span> <span m="1687460">in</span> <span m="1687550">Africa.</span>
  <span m="1688420">Both</span> <span m="1688780">of</span> <span m="1688870">you</span>
  <span m="1689050">stand</span> <span m="1689740">on</span> <span m="1689980">the</span>
  <span m="1690100">equator</span> <span m="1691060">and</span> <span m="1691210">go</span>
  <span m="1691420">due</span> <span m="1691750">north.</span> <span m="1692440">You</span>
  <span m="1692680">are</span> <span m="1692800">moving</span> <span m="1693250">on</span>
  <span m="1693520">parallel</span> <span m="1694180">trajectories.</span> <span m="1695500">You</span>
  <span m="1695650">will</span> <span m="1695770">intersect</span> <span m="1696430">at</span>
  <span m="1696520">the</span> <span m="1696610">North</span> <span m="1696820">Pole.</span>
  <span m="1698870">OK?</span></p><p><span m="1699260">Well,</span> <span m="1699500">guess</span>
  <span m="1699680">what?</span> <span m="1699890">You ain't</span> <span m="1700090">moving</span>
  <span m="1700310">on</span> <span m="1700400">a</span> <span m="1700460">flat</span>
  <span m="1700670">manifold.</span> <span m="1701210">You're</span> <span m="1701300">moving</span>
  <span m="1701540">on</span> <span m="1701600">the</span> <span m="1701660">surface</span>
  <span m="1701960">of</span> <span m="1702020">a</span> <span m="1702080">sphere.</span>
  <span m="1702830">OK,</span> <span m="1703070">curvature</span> <span m="1704090">causes</span>
  <span m="1704690">initially</span> <span m="1705560">parallel</span> <span m="1706070">trajectories</span>
  <span m="1706670">to</span> <span m="1706760">become</span> <span m="1707150">non-parallel.</span></p><p><span
  m="1709940">What</span> <span m="1710090">this</span> <span m="1710240">is</span>
  <span m="1710330">telling</span> <span m="1710750">us</span> <span m="1711110">is</span>
  <span m="1711530">that</span> <span m="1711770">the</span> <span m="1711890">manifold</span>
  <span m="1712860">I'm</span> <span m="1713090">going</span> <span m="1713330">to</span>
  <span m="1713450">want</span> <span m="1713660">to</span> <span m="1713780">use</span>
  <span m="1714680">to</span> <span m="1714800">describe</span> <span m="1715370">events</span>
  <span m="1716060">when</span> <span m="1716360">I</span> <span m="1716510">have</span>
  <span m="1717080">gravity</span> <span m="1718220">cannot</span> <span m="1718640">be</span>
  <span m="1718820">flat.</span> <span m="1719300">I'm</span> <span m="1719360">going</span>
  <span m="1719480">to</span> <span m="1719540">have</span> <span m="1719660">to</span>
  <span m="1719720">introduce</span> <span m="1720170">curvature</span> <span m="1720800">into</span>
  <span m="1721040">it.</span> <span m="1721940">Take</span> <span m="1722150">us</span>
  <span m="1722240">a</span> <span m="1722300">little</span> <span m="1722480">while</span>
  <span m="1722720">to</span> <span m="1722810">unpack</span> <span m="1723260">precisely</span>
  <span m="1723890">mathematically</span> <span m="1724490">what</span> <span m="1724670">that</span>
  <span m="1724880">means.</span> <span m="1726210">But</span> <span m="1726230">this</span>
  <span m="1726410">is</span> <span m="1726470">sort</span> <span m="1726620">of</span>
  <span m="1726680">a</span> <span m="1726740">sign</span> <span m="1727640">that</span>
  <span m="1728150">things</span> <span m="1728600">got</span> <span m="1729380">more</span>
  <span m="1729680">complicated.</span> <span m="1730790">And</span> <span m="1730940">tides</span>
  <span m="1731510">are</span> <span m="1731630">the</span> <span m="1731720">way</span>
  <span m="1732050">in</span> <span m="1732200">which</span> <span m="1732890">that</span>
  <span m="1733040">complication</span> <span m="1733670">is</span> <span m="1733760">being</span>
  <span m="1733970">introduced.</span></p><p><span m="1736930">So</span> <span m="1741450">switch</span>
  <span m="1741960">pages</span> <span m="1742740">here.</span> <span m="1757820">So</span>
  <span m="1757900">what</span> <span m="1758080">we</span> <span m="1758230">have</span>
  <span m="1759850">basically</span> <span m="1760360">danced</span> <span m="1760720">around</span>
  <span m="1761050">and</span> <span m="1761140">put</span> <span m="1761320">together</span>
  <span m="1761590">here</span> <span m="1762340">is</span> <span m="1762640">one</span>
  <span m="1763090">formulation</span> <span m="1764440">of</span> <span m="1764620">what</span>
  <span m="1764860">is</span> <span m="1765070">known</span> <span m="1765520">as</span>
  <span m="1768310">the</span> <span m="1768370">principle</span> <span m="1768700">of</span>
  <span m="1768760">equivalence.</span> <span m="1796990">The</span> <span m="1797530">principle
  of</span> <span m="1797890">equivalence,</span> <span m="1798460">or</span> <span
  m="1798580">one</span> <span m="1799030">formulation</span> <span m="1799720">of</span>
  <span m="1799810">it,</span> <span m="1800620">tells</span> <span m="1800980">me</span>
  <span m="1801130">that</span> <span m="1804470">over</span> <span m="1808520">sufficiently</span>
  <span m="1810620">small</span> <span m="1812870">regions,</span> <span m="1823420">the</span>
  <span m="1823540">motion</span> <span m="1824080">of</span> <span m="1824230">freely</span>
  <span m="1824770">falling</span> <span m="1829370">particles</span> <span m="1831890">due</span>
  <span m="1834440">to</span> <span m="1834590">gravity</span> <span m="1842040">cannot</span>
  <span m="1842490">be</span> <span m="1842940">distinguished</span> <span m="1847700">from</span>
  <span m="1848120">uniform</span> <span m="1848900">acceleration.</span></p><p><span
  m="1855850">The</span> <span m="1855940">physical</span> <span m="1856240">manifestation</span>
  <span m="1856960">of</span> <span m="1857020">this</span> <span m="1857260">is</span>
  <span m="1857360">that</span> <span m="1857430">if</span> <span m="1857530">you're</span>
  <span m="1857650">an</span> <span m="1857710">observer</span> <span m="1858160">who</span>
  <span m="1858310">is</span> <span m="1858460">in</span> <span m="1858640">that</span>
  <span m="1858820">freely</span> <span m="1859120">falling</span> <span m="1859450">frame</span>
  <span m="1859960">moving</span> <span m="1860260">due</span> <span m="1860380">to</span>
  <span m="1860470">gravity,</span> <span m="1861050">you</span> <span m="1861190">are</span>
  <span m="1861280">also</span> <span m="1861490">experiencing</span> <span m="1862030">that</span>
  <span m="1862150">uniform</span> <span m="1862510">acceleration.</span> <span m="1863720">So</span>
  <span m="1863740">you</span> <span m="1863920">see</span> <span m="1864110">no</span>
  <span m="1864400">net</span> <span m="1864640">acceleration.</span> <span m="1866650">This</span>
  <span m="1866950">particular</span> <span m="1867370">formulation</span> <span m="1867910">of</span>
  <span m="1868000">it</span> <span m="1868090">is</span> <span m="1868270">known</span>
  <span m="1868480">as</span> <span m="1868660">the</span> <span m="1868750">weak</span>
  <span m="1869230">equivalence</span> <span m="1869680">principle.</span></p><p><span
  m="1877420">I'm</span> <span m="1877510">going</span> <span m="1877630">to</span>
  <span m="1877690">give</span> <span m="1877840">you</span> <span m="1877930">a</span>
  <span m="1877990">couple</span> <span m="1878260">variations</span> <span m="1878770">on</span>
  <span m="1878810">this</span> <span m="1878970">in</span> <span m="1879040">just</span>
  <span m="1879250">a</span> <span m="1879310">second.</span> <span m="1881880">One</span>
  <span m="1882120">thing</span> <span m="1882270">that's</span> <span m="1882390">important</span>
  <span m="1882780">about</span> <span m="1883050">it</span> <span m="1884850">is,</span>
  <span m="1887040">essentially,</span> <span m="1888540">it's</span> <span m="1888750">a</span>
  <span m="1888780">statement</span> <span m="1889500">that,</span> <span m="1892540">if</span>
  <span m="1892660">you</span> <span m="1892750">think</span> <span m="1892990">about</span>
  <span m="1895210">Newton's</span> <span m="1895540">laws,</span> <span m="1895960">the</span>
  <span m="1896080">idea</span> <span m="1896440">that</span> <span m="1896620">f</span>
  <span m="1896830">equals</span> <span m="1897220">ma</span> <span m="1898100">and</span>
  <span m="1898240">the</span> <span m="1898330">force</span> <span m="1898600">of</span>
  <span m="1898660">gravity</span> <span m="1898990">is</span> <span m="1899080">proportional</span>
  <span m="1899510">to</span> <span m="1899590">m,</span> <span m="1900670">it's</span>
  <span m="1901030">a</span> <span m="1901150">fairly</span> <span m="1901450">precise</span>
  <span m="1901810">statement</span> <span m="1902470">that</span> <span m="1903310">you</span>
  <span m="1903460">think</span> <span m="1903670">of that</span> <span m="1903940">m</span>
  <span m="1904210">as</span> <span m="1904390">the</span> <span m="1904450">gravitational</span>
  <span m="1905140">charge.</span> <span m="1906190">It's</span> <span m="1906370">saying</span>
  <span m="1906790">that</span> <span m="1906970">the</span> <span m="1907060">gravitational</span>
  <span m="1907840">charge,</span> <span m="1908410">the</span> <span m="1908470">gravitational</span>
  <span m="1909100">mass</span> <span m="1910030">and</span> <span m="1910150">the</span>
  <span m="1910210">inertial</span> <span m="1910600">mass</span> <span m="1910900">are</span>
  <span m="1910990">the</span> <span m="1911080">same</span> <span m="1911410">thing.</span></p><p><span
  m="1912610">That's</span> <span m="1912820">actually</span> <span m="1913330">a</span>
  <span m="1913900">testable</span> <span m="1914440">statement.</span> <span m="1915310">What</span>
  <span m="1915400">you</span> <span m="1915460">can</span> <span m="1915580">do</span>
  <span m="1915700">is</span> <span m="1915850">look</span> <span m="1916060">at</span>
  <span m="1916150">materials</span> <span m="1916660">that</span> <span m="1916750">have</span>
  <span m="1916840">very</span> <span m="1917170">different</span> <span m="1917410">compositions.</span>
  <span m="1918000">In</span> <span m="1918040">particular,</span> <span m="1918400">what</span>
  <span m="1918550">you</span> <span m="1918640">want</span> <span m="1918760">to</span>
  <span m="1918850">do</span> <span m="1919090">is</span> <span m="1919240">look</span>
  <span m="1919480">at</span> <span m="1919600">things</span> <span m="1919960">that</span>
  <span m="1920080">maybe</span> <span m="1920350">have</span> <span m="1921130">different</span>
  <span m="1921490">ratios</span> <span m="1922390">of</span> <span m="1922630">neutrons</span>
  <span m="1923080">to</span> <span m="1923170">protons</span> <span m="1923920">or</span>
  <span m="1925180">have</span> <span m="1925360">highly</span> <span m="1925690">bound</span>
  <span m="1925960">nuclei</span> <span m="1926410">with</span> <span m="1926590">lots</span>
  <span m="1926860">of</span> <span m="1926920">gluons</span> <span m="1927430">in</span>
  <span m="1927520">them</span> <span m="1927730">or</span> <span m="1927880">various</span>
  <span m="1928240">kinds</span> <span m="1928480">of</span> <span m="1928540">fields</span>
  <span m="1928960">that</span> <span m="1929170">you</span> <span m="1929260">can</span>
  <span m="1929380">imagine</span> <span m="1929860">perhaps</span> <span m="1930430">couple</span>
  <span m="1930790">to</span> <span m="1930970">gravity</span> <span m="1931390">differently</span>
  <span m="1931810">than</span> <span m="1931960">the</span> <span m="1932020">quarks</span>
  <span m="1932390">do.</span></p><p><span m="1934040">And</span> <span m="1934120">so</span>
  <span m="1934360">there</span> <span m="1934570">are</span> <span m="1934900">what</span>
  <span m="1935050">are</span> <span m="1935110">called</span> <span m="1935320">free</span>
  <span m="1935620">fall</span> <span m="1935830">experiments</span> <span m="1936370">to</span>
  <span m="1936460">test</span> <span m="1936760">this,</span> <span m="1942570">which</span>
  <span m="1942750">really</span> <span m="1943590">basically</span> <span m="1943980">just
  boils</span> <span m="1944340">down</span> <span m="1944640">to</span> <span m="1944790">dropping</span>
  <span m="1945390">lots</span> <span m="1945860">of</span> <span m="1945930">different</span>
  <span m="1946170">elements</span> <span m="1946420">of</span> <span m="1946460">the</span>
  <span m="1946530">periodic</span> <span m="1946890">table</span> <span m="1947290">and</span>
  <span m="1947400">making</span> <span m="1947670">sure</span> <span m="1947850">they</span>
  <span m="1947970">all</span> <span m="1948060">fall</span> <span m="1948270">at</span>
  <span m="1948330">the</span> <span m="1948420">same</span> <span m="1948660">rate.</span>
  <span m="1950040">And</span> <span m="1951360">the</span> <span m="1951540">answer</span>
  <span m="1951930">is</span> <span m="1952260">that</span> <span m="1952440">they</span>
  <span m="1953520">fall</span> <span m="1953720">at</span> <span m="1953820">exactly</span>
  <span m="1954270">the</span> <span m="1954360">same</span> <span m="1954630">rate</span>
  <span m="1954910">within</span> <span m="1955200">experimental</span> <span m="1955830">precision.</span>
  <span m="1956670">And</span> <span m="1956790">the</span> <span m="1956850">last</span>
  <span m="1957060">time</span> <span m="1957210">I</span> <span m="1957270">looked</span>
  <span m="1957450">it</span> <span m="1957540">up,</span> <span m="1962000">well,</span>
  <span m="1962310">what</span> <span m="1962430">they</span> <span m="1962610">do</span>
  <span m="1962850">is</span> <span m="1963030">they</span> <span m="1963180">demonstrate</span>
  <span m="1965000">the</span> <span m="1965120">WEP,</span> <span m="1965910">the</span>
  <span m="1966000">Weak</span> <span m="1966240">Equivalence</span> <span m="1966660">Principle,</span>
  <span m="1970020">is</span> <span m="1970200">valid</span> <span m="1970710">to</span>
  <span m="1970920">about,</span> <span m="1972090">I</span> <span m="1972360">believe,</span>
  <span m="1972780">it's</span> <span m="1972870">about</span> <span m="1973050">a</span>
  <span m="1973440">part</span> <span m="1973680">in</span> <span m="1973770">10</span>
  <span m="1973980">to the</span> <span m="1974060">minus</span> <span m="1974330">13.</span>
  <span m="1974700">Might</span> <span m="1974820">be</span> <span m="1974910">a</span>
  <span m="1974970">little</span> <span m="1975120">bit</span> <span m="1975240">better</span>
  <span m="1975480">now.</span></p><p><span m="1978640">So</span> <span m="1982150">bear</span>
  <span m="1982240">with</span> <span m="1982360">me</span> <span m="1982480">just</span>
  <span m="1982720">one</span> <span m="1982930">second</span> <span m="1983320">here.</span>
  <span m="1989530">OK,</span> <span m="1990000">so</span> <span m="1990500">good.</span>
  <span m="1990850">We've</span> <span m="1991020">got</span> <span m="1991200">this</span>
  <span m="1991380">notion</span> <span m="1991740">here.</span> <span m="1993360">And</span>
  <span m="1994080">you</span> <span m="1994170">might</span> <span m="1994320">now</span>
  <span m="1994500">think,</span> <span m="1994710">OK,</span> <span m="1994950">great.</span>
  <span m="1995340">I</span> <span m="1995490">have</span> <span m="1996600">a</span>
  <span m="1996660">way</span> <span m="1996900">of</span> <span m="1996990">generalizing</span>
  <span m="1997650">what</span> <span m="1997780">the</span> <span m="1997860">notion</span>
  <span m="1998190">of</span> <span m="1998280">an</span> <span m="1998370">inertial</span>
  <span m="1998760">frame</span> <span m="1999150">is.</span> <span m="1999890">Is</span>
  <span m="2000260">this</span> <span m="2000500">enough</span> <span m="2001040">for</span>
  <span m="2001220">me</span> <span m="2001370">to</span> <span m="2001490">move</span>
  <span m="2001670">forward?</span> <span m="2002570">Can</span> <span m="2002960">we</span>
  <span m="2003140">now</span> <span m="2006690">do</span> <span m="2006960">all</span>
  <span m="2007140">of</span> <span m="2007200">physics</span> <span m="2012850">by</span>
  <span m="2013030">just</span> <span m="2013300">applying</span> <span m="2014350">the</span>
  <span m="2014500">laws</span> <span m="2014920">of</span> <span m="2015010">special</span>
  <span m="2015400">relativity</span> <span m="2019330">in</span> <span m="2019630">freely</span>
  <span m="2020020">falling</span> <span m="2020380">frames</span> <span m="2022900">or,</span>
  <span m="2023050">putting</span> <span m="2023260">it</span> <span m="2023350">this</span>
  <span m="2023500">way,</span> <span m="2023770">our</span> <span m="2024010">new</span>
  <span m="2024280">notion</span> <span m="2024820">of</span> <span m="2024910">an</span>
  <span m="2025000">inertial</span> <span m="2025360">frame?</span></p><p><span m="2034560">For</span>
  <span m="2034710">two</span> <span m="2034890">reasons</span> <span m="2035430">that</span>
  <span m="2035610">are</span> <span m="2035670">closely</span> <span m="2035970">related,</span>
  <span m="2036270">this</span> <span m="2036420">doesn't</span> <span m="2036690">quite</span>
  <span m="2037050">work.</span> <span m="2037710">And</span> <span m="2037830">it</span>
  <span m="2037890">comes</span> <span m="2038160">down</span> <span m="2038460">to</span>
  <span m="2039750">the</span> <span m="2039840">fact</span> <span m="2040170">that</span>
  <span m="2040410">because</span> <span m="2040830">of</span> <span m="2040920">tides,</span>
  <span m="2044280">we</span> <span m="2044400">can't</span> <span m="2044640">do</span>
  <span m="2044790">that.</span> <span m="2068620">What</span> <span m="2068770">this</span>
  <span m="2068909">basically</span> <span m="2069300">means</span> <span m="2069870">is</span>
  <span m="2070110">that</span> <span m="2070199">the</span> <span m="2070260">transformation</span>
  <span m="2071130">that</span> <span m="2071250">puts</span> <span m="2071510">you</span>
  <span m="2071699">into</span> <span m="2072030">a</span> <span m="2072090">freely</span>
  <span m="2072480">falling</span> <span m="2072870">frame</span> <span m="2073380">here</span>
  <span m="2074850">is</span> <span m="2075000">not</span> <span m="2075210">the</span>
  <span m="2075300">same</span> <span m="2075570">as</span> <span m="2075659">the</span>
  <span m="2075719">transformation</span> <span m="2076290">that</span> <span m="2076380">puts</span>
  <span m="2076550">you</span> <span m="2076650">into</span> <span m="2076830">a</span>
  <span m="2076889">freely</span> <span m="2077159">falling</span> <span m="2077489">frame</span>
  <span m="2078210">10,000</span> <span m="2078810">miles</span> <span m="2079139">over</span>
  <span m="2079230">the</span> <span m="2079350">Earth's</span> <span m="2079500">surface,</span>
  <span m="2079980">OK?</span></p><p><span m="2080909">There</span> <span m="2081090">are</span>
  <span m="2081239">different</span> <span m="2081810">transformations</span> <span
  m="2082739">at</span> <span m="2082980">different</span> <span m="2083429">locations</span>
  <span m="2084000">in</span> <span m="2084090">spacetime.</span> <span m="2085320">This</span>
  <span m="2085469">comes</span> <span m="2085679">down</span> <span m="2085860">the</span>
  <span m="2085920">idea</span> <span m="2086159">that</span> <span m="2086250">it's</span>
  <span m="2086400">not</span> <span m="2086639">a</span> <span m="2086790">global</span>
  <span m="2087449">Lorentz</span> <span m="2087840">frame,</span> <span m="2088110">OK?</span>
  <span m="2088380">We</span> <span m="2088469">had</span> <span m="2088590">a</span>
  <span m="2088620">sequence</span> <span m="2089040">of</span> <span m="2089159">local</span>
  <span m="2089580">Lorentz</span> <span m="2089940">frames</span> <span m="2091230">that</span>
  <span m="2091739">we</span> <span m="2091920">have</span> <span m="2092100">to</span>
  <span m="2092219">link</span> <span m="2092580">up.</span></p><p><span m="2116930">So</span>
  <span m="2117190">I'm</span> <span m="2117320">going to do</span> <span m="2117450">a</span>
  <span m="2117510">calculation</span> <span m="2118170">in</span> <span m="2118260">just</span>
  <span m="2118470">a</span> <span m="2118500">moment</span> <span m="2118830">where</span>
  <span m="2119100">we</span> <span m="2119490">explicitly</span> <span m="2120120">show</span>
  <span m="2121410">that</span> <span m="2121680">we</span> <span m="2121830">can</span>
  <span m="2122190">always</span> <span m="2122640">go</span> <span m="2122850">into</span>
  <span m="2123360">a</span> <span m="2123510">frame</span> <span m="2123900">that</span>
  <span m="2124020">is</span> <span m="2124140">locally</span> <span m="2124620">Lorentz,</span>
  <span m="2125940">but</span> <span m="2126270">that</span> <span m="2126840">there's</span>
  <span m="2127920">a</span> <span m="2128010">term</span> <span m="2128700">that</span>
  <span m="2128940">I'm</span> <span m="2129030">going</span> <span m="2129120">to</span>
  <span m="2129240">very</span> <span m="2129450">strongly</span> <span m="2129810">argue</span>
  <span m="2130200">is</span> <span m="2130320">essentially</span> <span m="2130680">the</span>
  <span m="2130770">curvature</span> <span m="2131310">associated</span> <span m="2131750">with
  the</span> <span m="2131820">spacetime</span> <span m="2132300">metric</span> <span
  m="2133140">that</span> <span m="2133590">sets</span> <span m="2133980">the</span>
  <span m="2134100">size</span> <span m="2134820">of</span> <span m="2134940">what</span>
  <span m="2135060">that</span> <span m="2135210">region</span> <span m="2135510">actually</span>
  <span m="2135900">is.</span> <span m="2140320">So</span> <span m="2140790">what</span>
  <span m="2141060">we</span> <span m="2141300">are</span> <span m="2141420">going</span>
  <span m="2141690">to</span> <span m="2141810">do,</span> <span m="2143610">what</span>
  <span m="2143790">is</span> <span m="2143940">going</span> <span m="2144150">to</span>
  <span m="2144270">guide</span> <span m="2144720">our</span> <span m="2144930">physics</span>
  <span m="2145440">as</span> <span m="2145590">we</span> <span m="2145740">move</span>
  <span m="2146010">forward</span> <span m="2149060">is,</span> <span m="2149570">essentially,</span>
  <span m="2150680">we're</span> <span m="2150820">going</span> <span m="2150900">to</span>
  <span m="2151010">take</span> <span m="2151190">advantage</span> <span m="2151730">of</span>
  <span m="2151850">a</span> <span m="2151910">reformulation--</span> <span m="2156665">there</span>
  <span m="2157140">we</span> <span m="2157615">go--</span> <span m="2159990">of</span>
  <span m="2160410">the</span> <span m="2160560">equivalence</span> <span m="2161100">principle,</span>
  <span m="2165190">which</span> <span m="2165310">I'm</span> <span m="2165370">going</span>
  <span m="2165490">to</span> <span m="2165540">word</span> <span m="2165820">as</span>
  <span m="2166000">follows.</span></p><p><span m="2171250">In</span> <span m="2171470">sufficiently</span>
  <span m="2173220">small</span> <span m="2173760">regions</span> <span m="2174420">of</span>
  <span m="2174520">spacetime,</span> <span m="2185160">we</span> <span m="2185370">can</span>
  <span m="2185610">find</span> <span m="2187440">a</span> <span m="2187530">representation</span>
  <span m="2188550">or</span> <span m="2188760">a</span> <span m="2188820">coordinate</span>
  <span m="2189210">system</span> <span m="2195720">such</span> <span m="2196800">that--</span>
  <span m="2197490">I</span> <span m="2197970">don't</span> <span m="2198090">want
  to</span> <span m="2198210">cram</span> <span m="2198600">this into</span> <span
  m="2198720">the</span> <span m="2198810">margin.</span> <span m="2199220">So</span>
  <span m="2199510">I'll switch</span> <span m="2199865">boards--</span> <span m="2218800">the</span>
  <span m="2218940">laws</span> <span m="2219390">of</span> <span m="2219480">physics</span>
  <span m="2224890">reduce</span> <span m="2229620">to</span> <span m="2229820">those</span>
  <span m="2230860">of</span> <span m="2231230">special</span> <span m="2231590">relativity.</span>
  <span m="2233930">This</span> <span m="2234530">is</span> <span m="2234710">known</span>
  <span m="2235040">as</span> <span m="2236840">the</span> <span m="2236990">Einstein</span>
  <span m="2238400">equivalence</span> <span m="2238880">principle.</span> <span m="2239390">At</span>
  <span m="2239450">least,</span> <span m="2239640">that's</span> <span m="2239780">the</span>
  <span m="2240130">name</span> <span m="2240510">that</span> <span m="2240890">Carroll</span>
  <span m="2241820">uses</span> <span m="2242210">in</span> <span m="2242330">his</span>
  <span m="2242480">textbook.</span> <span m="2243320">A</span> <span m="2243380">couple</span>
  <span m="2243620">books</span> <span m="2243830">use</span> <span m="2243970">different</span>
  <span m="2244190">ones.</span> <span m="2244340">But this</span> <span m="2244460">is</span>
  <span m="2244520">a</span> <span m="2244550">very</span> <span m="2244790">nice</span>
  <span m="2245030">one</span> <span m="2245240">because it</span> <span m="2245360">really</span>
  <span m="2245690">is</span> <span m="2246320">the</span> <span m="2246410">principle</span>
  <span m="2246770">by</span> <span m="2246950">which</span> <span m="2247430">Einstein</span>
  <span m="2248330">guided</span> <span m="2248720">us</span> <span m="2250030">to</span>
  <span m="2250190">rewriting</span> <span m="2250700">the</span> <span m="2250790">laws</span>
  <span m="2251030">of</span> <span m="2251090">physics.</span></p><p><span m="2253230">So</span>
  <span m="2253280">we've</span> <span m="2253520">got</span> <span m="2254000">a</span>
  <span m="2254090">weak</span> <span m="2254360">equivalence</span> <span m="2254810">principle,</span>
  <span m="2255290">an</span> <span m="2255440">Einstein</span> <span m="2255830">equivalence</span>
  <span m="2256250">principle.</span> <span m="2257030">Just</span> <span m="2257360">as</span>
  <span m="2257510">an</span> <span m="2257600">aside,</span> <span m="2258270">there</span>
  <span m="2258320">is</span> <span m="2258470">something</span> <span m="2258740">called</span>
  <span m="2259010">a</span> <span m="2259070">strong</span> <span m="2259550">equivalence</span>
  <span m="2259970">principle.</span> <span m="2269320">We're</span> <span m="2269420">not</span>
  <span m="2269460">going</span> <span m="2269580">to</span> <span m="2269640">talk</span>
  <span m="2269850">about</span> <span m="2270030">this</span> <span m="2270210">very</span>
  <span m="2270420">much,</span> <span m="2271000">but</span> <span m="2271110">I'm</span>
  <span m="2271170">going</span> <span m="2271280">to</span> <span m="2271350">give</span>
  <span m="2271470">it</span> <span m="2271530">to</span> <span m="2271620">you</span>
  <span m="2271830">because</span> <span m="2271980">it's just</span> <span m="2272070">kind</span>
  <span m="2272220">of</span> <span m="2272280">cool.</span></p><p><span m="2276950">It</span>
  <span m="2277000">tells</span> <span m="2277300">me</span> <span m="2277450">that</span>
  <span m="2277600">gravity</span> <span m="2279520">falls</span> <span m="2280210">in</span>
  <span m="2280330">a</span> <span m="2280390">gravitational</span> <span m="2280990">field</span>
  <span m="2287420">in</span> <span m="2287570">a</span> <span m="2287630">way</span>
  <span m="2287900">that</span> <span m="2288020">is</span> <span m="2288170">indistinguishable</span>
  <span m="2288890">from</span> <span m="2289070">mass.</span> <span m="2302000">That's</span>
  <span m="2302150">a</span> <span m="2302210">little</span> <span m="2302360">weird.</span>
  <span m="2304730">I'm</span> <span m="2304880">not</span> <span m="2305090">going</span>
  <span m="2305210">to</span> <span m="2305300">explain</span> <span m="2305690">it</span>
  <span m="2305780">very</span> <span m="2306080">much</span> <span m="2306350">right</span>
  <span m="2306650">now.</span> <span m="2307940">A</span> <span m="2308030">way</span>
  <span m="2308210">to</span> <span m="2308300">think</span> <span m="2308480">about</span>
  <span m="2308720">it</span> <span m="2308810">will</span> <span m="2308930">become</span>
  <span m="2309230">clearer</span> <span m="2309770">in</span> <span m="2309950">some</span>
  <span m="2310100">future</span> <span m="2310400">problem</span> <span m="2310810">sets.</span></p><p><span
  m="2311870">Basically</span> <span m="2312320">what</span> <span m="2312500">it's</span>
  <span m="2312590">telling</span> <span m="2312950">us</span> <span m="2313220">is</span>
  <span m="2313550">that</span> <span m="2313730">when</span> <span m="2313910">you</span>
  <span m="2314030">make</span> <span m="2314270">very</span> <span m="2314720">strong--</span>
  <span m="2315410">when</span> <span m="2315530">you</span> <span m="2315620">make</span>
  <span m="2315830">any</span> <span m="2316010">kind</span> <span m="2316220">of</span>
  <span m="2316280">a</span> <span m="2316340">bound</span> <span m="2316800">object,</span>
  <span m="2318440">some</span> <span m="2318980">of</span> <span m="2319190">the</span>
  <span m="2319310">mass</span> <span m="2319850">of</span> <span m="2319910">that</span>
  <span m="2320120">object,</span> <span m="2320480">in</span> <span m="2320550">the</span>
  <span m="2320630">sense</span> <span m="2320930">of</span> <span m="2321020">the</span>
  <span m="2321110">mass</span> <span m="2321590">that</span> <span m="2321740">is</span>
  <span m="2321860">measured</span> <span m="2322400">by</span> <span m="2322700">orbits,</span>
  <span m="2323750">can</span> <span m="2323840">be</span> <span m="2323930">thought</span>
  <span m="2324140">of</span> <span m="2324200">as</span> <span m="2324320">gravitational</span>
  <span m="2325070">energy,</span> <span m="2325843">OK?</span> <span m="2326690">Energy</span>
  <span m="2327080">and</span> <span m="2327200">mass</span> <span m="2327560">are</span>
  <span m="2327680">equivalent</span> <span m="2328070">to</span> <span m="2328190">one</span>
  <span m="2328340">another.</span> <span m="2329000">So</span> <span m="2329150">that</span>
  <span m="2329300">gravitational</span> <span m="2329930">energy</span> <span m="2330380">should</span>
  <span m="2330560">respond</span> <span m="2330980">to</span> <span m="2331040">gravity.</span>
  <span m="2331580">And</span> <span m="2331730">in</span> <span m="2331790">fact,</span>
  <span m="2332030">it</span> <span m="2332120">falls</span> <span m="2332600">just</span>
  <span m="2332780">like</span> <span m="2332900">any</span> <span m="2333050">other</span>
  <span m="2333200">mass,</span> <span m="2333970">OK?</span></p><p><span m="2334850">This</span>
  <span m="2335000">is</span> <span m="2335090">another</span> <span m="2335360">one.</span>
  <span m="2335610">This</span> <span m="2335630">is</span> <span m="2335720">actually</span>
  <span m="2335990">very--</span> <span m="2336620">well,</span> <span m="2338510">prior</span>
  <span m="2341390">to</span> <span m="2341540">September</span> <span m="2342050">2015,</span>
  <span m="2343070">this</span> <span m="2343220">was</span> <span m="2343370">very</span>
  <span m="2343640">difficult</span> <span m="2344120">to</span> <span m="2344240">test.</span>
  <span m="2345890">There</span> <span m="2346040">were</span> <span m="2346130">some</span>
  <span m="2347030">very</span> <span m="2347330">precise</span> <span m="2347750">measurements</span>
  <span m="2348230">of</span> <span m="2348320">the</span> <span m="2348410">moon's</span>
  <span m="2348770">orbit</span> <span m="2349040">that</span> <span m="2349130">were</span>
  <span m="2349250">done</span> <span m="2349490">to</span> <span m="2349580">test</span>
  <span m="2349880">this.</span> <span m="2351140">And</span> <span m="2351410">there</span>
  <span m="2351530">were</span> <span m="2351650">observations</span> <span m="2352310">of</span>
  <span m="2352370">binary</span> <span m="2352700">pulsar</span> <span m="2353090">systems</span>
  <span m="2353390">that were</span> <span m="2353510">done</span> <span m="2353660">to</span>
  <span m="2353720">test</span> <span m="2353990">this.</span> <span m="2356440">Now</span>
  <span m="2356950">every</span> <span m="2357130">time</span> <span m="2357370">LIGO</span>
  <span m="2357670">measures</span> <span m="2357970">a</span> <span m="2358000">pair</span>
  <span m="2358180">of</span> <span m="2358240">binary</span> <span m="2358570">black</span>
  <span m="2358840">holes,</span> <span m="2359690">which</span> <span m="2359800">are</span>
  <span m="2359950">nothing</span> <span m="2360490">but</span> <span m="2361030">gravitational</span>
  <span m="2361600">energy,</span> <span m="2362170">and</span> <span m="2362290">our</span>
  <span m="2362350">theoretical</span> <span m="2362770">models</span> <span m="2363160">match</span>
  <span m="2363430">the</span> <span m="2363520">wave</span> <span m="2363700">forms,</span>
  <span m="2364490">sort of</span> <span m="2364860">like,</span> <span m="2365020">boom,</span>
  <span m="2365500">equivalence</span> <span m="2365920">principle.</span> <span m="2367290">Drop</span>
  <span m="2367570">mic.</span> <span m="2367810">Leave</span> <span m="2368010">room.</span></p><p><span
  m="2368710">All</span> <span m="2368770">right,</span> <span m="2377420">so</span>
  <span m="2377840">let's</span> <span m="2378020">get</span> <span m="2378170">precise.</span>
  <span m="2383520">What</span> <span m="2383670">I</span> <span m="2383760">want</span>
  <span m="2383940">to</span> <span m="2384030">do</span> <span m="2386900">is</span>
  <span m="2387770">show</span> <span m="2389300">that</span> <span m="2389570">we</span>
  <span m="2389750">can</span> <span m="2390050">always</span> <span m="2390620">find</span>
  <span m="2391250">a</span> <span m="2391430">local</span> <span m="2392420">Lorentz</span>
  <span m="2392820">frame.</span> <span m="2406830">And</span> <span m="2406960">what</span>
  <span m="2407110">I</span> <span m="2407200">mean</span> <span m="2407530">by</span>
  <span m="2407710">that</span> <span m="2408610">is</span> <span m="2409060">that</span>
  <span m="2409390">I</span> <span m="2409660">want</span> <span m="2409870">to</span>
  <span m="2409930">be</span> <span m="2410020">able</span> <span m="2410140">to</span>
  <span m="2410230">show</span> <span m="2410860">that</span> <span m="2411910">I</span>
  <span m="2412030">can</span> <span m="2412300">always</span> <span m="2412990">do</span>
  <span m="2413410">a</span> <span m="2414220">change</span> <span m="2414670">of</span>
  <span m="2414730">my</span> <span m="2414880">coordinates,</span> <span m="2415390">a</span>
  <span m="2415480">change</span> <span m="2415840">of</span> <span m="2415930">my</span>
  <span m="2416050">representation</span> <span m="2417370">such</span> <span m="2417670">that,</span>
  <span m="2417970">at</span> <span m="2418240">some</span> <span m="2418840">point,</span>
  <span m="2420070">I</span> <span m="2420280">can</span> <span m="2420490">convert</span>
  <span m="2420880">the</span> <span m="2421000">metric</span> <span m="2421960">of</span>
  <span m="2422060">spacetime</span> <span m="2423220">into</span> <span m="2423460">the</span>
  <span m="2423550">metric</span> <span m="2423970">we</span> <span m="2424090">used</span>
  <span m="2424390">in</span> <span m="2424510">special</span> <span m="2425080">relativity,</span>
  <span m="2426220">at</span> <span m="2426370">least</span> <span m="2426940">over</span>
  <span m="2427300">some</span> <span m="2427570">finite</span> <span m="2428110">region.</span></p><p><span
  m="2458100">So</span> <span m="2458210">let</span> <span m="2458330">me</span> <span
  m="2458450">define</span> <span m="2458960">a</span> <span m="2459020">couple</span>
  <span m="2459350">of</span> <span m="2459410">quantities</span> <span m="2460610">and</span>
  <span m="2460730">then</span> <span m="2460850">let</span> <span m="2460970">me</span>
  <span m="2461060">formulate</span> <span m="2461330">the</span> <span m="2461600">way</span>
  <span m="2461700">this</span> <span m="2461840">calculation</span> <span m="2462470">is</span>
  <span m="2462590">going</span> <span m="2462800">to</span> <span m="2462890">work.</span>
  <span m="2466290">Let</span> <span m="2466725">us</span> <span m="2467160">let</span>
  <span m="2470290">coordinates</span> <span m="2470860">with</span> <span m="2471170">unbarred</span>
  <span m="2473080">Greek</span> <span m="2473470">indices</span> <span m="2474560">be</span>
  <span m="2474970">the</span> <span m="2475090">coordinate</span> <span m="2475470">system</span>
  <span m="2475750">that</span> <span m="2475870">we</span> <span m="2475960">start</span>
  <span m="2476320">in.</span> <span m="2484460">And</span> <span m="2484700">let's</span>
  <span m="2484880">say</span> <span m="2485120">that,</span> <span m="2485270">in</span>
  <span m="2485480">this</span> <span m="2485630">representation,</span> <span m="2489260">the</span>
  <span m="2489380">metric</span> <span m="2491720">is</span> <span m="2492070">G</span>
  <span m="2492250">alpha</span> <span m="2492460">beta.</span></p><p><span m="2495710">Let's</span>
  <span m="2495990">demand</span> <span m="2496590">that</span> <span m="2496710">there</span>
  <span m="2496950">exists</span> <span m="2498450">a</span> <span m="2498510">set</span>
  <span m="2498750">of</span> <span m="2498840">coordinates</span> <span m="2499410">that</span>
  <span m="2499590">I</span> <span m="2499710">will</span> <span m="2499830">represent</span>
  <span m="2500880">with</span> <span m="2501060">bars</span> <span m="2501480">on</span>
  <span m="2501600">the</span> <span m="2501690">indices.</span> <span m="2505340">When</span>
  <span m="2505520">we</span> <span m="2505610">transform</span> <span m="2506090">to</span>
  <span m="2506180">these</span> <span m="2506420">coordinates,</span> <span m="2506990">I</span>
  <span m="2507170">want</span> <span m="2507470">spacetime</span> <span m="2508070">to</span>
  <span m="2508190">be</span> <span m="2508520">Lorentz</span> <span m="2528710">at</span>
  <span m="2528800">least</span> <span m="2529160">in</span> <span m="2529310">the</span>
  <span m="2529400">vicinity</span> <span m="2530060">of</span> <span m="2530210">some</span>
  <span m="2530480">point</span> <span m="2531010">or</span> <span m="2531080">some</span>
  <span m="2531270">event.</span> <span m="2539318">We'll</span> <span m="2539810">call</span>
  <span m="2540050">that</span> <span m="2540180">event</span> <span m="2540390">p.</span></p><p><span
  m="2567690">So</span> <span m="2567890">we</span> <span m="2568040">will</span>
  <span m="2568130">assume</span> <span m="2568640">that</span> <span m="2569000">there</span>
  <span m="2569270">is</span> <span m="2569570">some</span> <span m="2569810">mapping</span>
  <span m="2570200">between</span> <span m="2570530">these</span> <span m="2570650">coordinates,</span>
  <span m="2572810">so</span> <span m="2572960">there's</span> <span m="2573140">no</span>
  <span m="2573770">nasty</span> <span m="2574130">singularities</span> <span m="2574790">there.</span>
  <span m="2578830">And</span> <span m="2579320">it's</span> <span m="2579510">nothing</span>
  <span m="2579810">that</span> <span m="2579900">we</span> <span m="2579990">can't</span>
  <span m="2581130">deal</span> <span m="2581400">with.</span> <span m="2587000">So</span>
  <span m="2587950">we</span> <span m="2588040">can</span> <span m="2588160">do</span>
  <span m="2588280">it</span> <span m="2588340">in</span> <span m="2588490">either</span>
  <span m="2588790">direction,</span> <span m="2589300">but</span> <span m="2589420">let's</span>
  <span m="2589640">say</span> <span m="2589960">x</span> <span m="2590260">alpha</span>
  <span m="2590820">is</span> <span m="2592120">x</span> <span m="2592420">alpha</span>
  <span m="2592960">of</span> <span m="2594340">p</span> <span m="2594550">written</span>
  <span m="2594820">as</span> <span m="2594910">some</span> <span m="2595120">function</span>
  <span m="2595510">of</span> <span m="2595600">these</span> <span m="2595840">guys.</span>
  <span m="2596590">And</span> <span m="2596710">so</span> <span m="2596830">there's</span>
  <span m="2596980">a</span> <span m="2597040">transformation</span> <span m="2597730">matrix</span>
  <span m="2598060">between</span> <span m="2598330">the</span> <span m="2598390">two</span>
  <span m="2598540">of</span> <span m="2598600">them.</span> <span m="2606930">It</span>
  <span m="2607020">takes</span> <span m="2608820">the</span> <span m="2608940">usual</span>
  <span m="2609270">form,</span> <span m="2610462">OK?</span></p><p><span m="2611890">So</span>
  <span m="2612090">mathematically,</span> <span m="2612750">the</span> <span m="2612870">way</span>
  <span m="2613080">I'm</span> <span m="2613230">going</span> <span m="2613410">to</span>
  <span m="2613530">show</span> <span m="2613890">this</span> <span m="2621840">is</span>
  <span m="2621960">I</span> <span m="2622050">want</span> <span m="2622170">to</span>
  <span m="2622230">show</span> <span m="2622620">that</span> <span m="2622830">we</span>
  <span m="2623100">can</span> <span m="2623340">find</span> <span m="2631400">a</span>
  <span m="2631490">coordinate</span> <span m="2631940">system</span> <span m="2636040">such</span>
  <span m="2636400">that,</span> <span m="2638670">if</span> <span m="2638880">I</span>
  <span m="2639120">compute</span> <span m="2640950">the</span> <span m="2641260">spacetime</span>
  <span m="2641790">metric</span> <span m="2642390">and</span> <span m="2643080">the</span>
  <span m="2643710">barred</span> <span m="2644040">representation,</span> <span m="2646480">this
  is</span> <span m="2646710">always</span> <span m="2647190">going</span> <span m="2647290">to</span>
  <span m="2647370">be</span> <span m="2647430">given</span> <span m="2647730">by</span>
  <span m="2648780">doing</span> <span m="2650340">this</span> <span m="2650520">coordinate</span>
  <span m="2650880">transformation.</span> <span m="2656030">Then</span> <span m="2656220">I</span>
  <span m="2656310">get</span> <span m="2657990">the</span> <span m="2658080">metric</span>
  <span m="2658470">of</span> <span m="2658530">flat</span> <span m="2658890">spacetime</span>
  <span m="2660060">over</span> <span m="2660450">as</span> <span m="2660690">large</span>
  <span m="2661350">a</span> <span m="2661440">region</span> <span m="2662010">as</span>
  <span m="2662160">possible.</span> <span m="2673664">OK,</span> <span m="2675160">we</span>
  <span m="2675370">know</span> <span m="2675610">we're</span> <span m="2675730">not</span>
  <span m="2675840">going</span> <span m="2676010">to be able</span> <span m="2676090">to</span>
  <span m="2676170">do</span> <span m="2676300">it</span> <span m="2676390">everywhere.</span></p><p><span
  m="2677770">What</span> <span m="2677920">I</span> <span m="2677980">want</span>
  <span m="2678100">to</span> <span m="2678160">show</span> <span m="2678640">is</span>
  <span m="2678760">that</span> <span m="2678850">I</span> <span m="2678910">can</span>
  <span m="2679060">make</span> <span m="2679240">that</span> <span m="2679420">happen</span>
  <span m="2679840">at</span> <span m="2680020">the</span> <span m="2680110">point</span>
  <span m="2680440">p</span> <span m="2681610">and</span> <span m="2681850">that</span>
  <span m="2682090">the</span> <span m="2682180">functional</span> <span m="2682540">behavior</span>
  <span m="2683080">of</span> <span m="2683140">this</span> <span m="2683380">thing</span>
  <span m="2683590">is</span> <span m="2683710">sufficiently</span> <span m="2684220">flat</span>
  <span m="2684780">that</span> <span m="2684930">it</span> <span m="2684990">remains</span>
  <span m="2687340">at</span> <span m="2687550">this</span> <span m="2688330">over</span>
  <span m="2688690">some</span> <span m="2688960">region.</span> <span m="2689510">So</span>
  <span m="2689530">let</span> <span m="2689620">me</span> <span m="2689680">just</span>
  <span m="2689830">sketch</span> <span m="2690160">what</span> <span m="2690280">the</span>
  <span m="2690370">logic</span> <span m="2690820">of</span> <span m="2690880">this</span>
  <span m="2690970">calculation</span> <span m="2691570">is</span> <span m="2691660">going</span>
  <span m="2691870">to</span> <span m="2691960">be.</span> <span m="2716630">So</span>
  <span m="2716770">what</span> <span m="2716920">we're</span> <span m="2717010">going</span>
  <span m="2717250">to</span> <span m="2717340">do</span> <span m="2718300">is</span>
  <span m="2718690">expand.</span></p><p><span m="2721320">So</span> <span m="2721730">remember</span>
  <span m="2725750">g</span> <span m="2726050">is</span> <span m="2726350">a</span>
  <span m="2726380">function.</span> <span m="2727430">All</span> <span m="2727640">of</span>
  <span m="2727700">these</span> <span m="2727970">l's</span> <span m="2728480">are</span>
  <span m="2728630">functions.</span> <span m="2729780">So</span> <span m="2729890">what
  I'm</span> <span m="2729980">going</span> <span m="2730190">to</span> <span m="2730280">do</span>
  <span m="2730760">is</span> <span m="2730970">I'm</span> <span m="2731030">going</span>
  <span m="2731150">to</span> <span m="2731240">think</span> <span m="2731540">of</span>
  <span m="2731630">this</span> <span m="2731780">whole</span> <span m="2732230">thing</span>
  <span m="2733300">as</span> <span m="2733460">itself</span> <span m="2733820">being</span>
  <span m="2734060">some</span> <span m="2734300">kind</span> <span m="2734450">of</span>
  <span m="2734540">a</span> <span m="2734600">function.</span> <span m="2735430">I'm</span>
  <span m="2735530">going</span> <span m="2735640">to</span> <span m="2735710">expand</span>
  <span m="2736180">in</span> <span m="2736250">the</span> <span m="2736340">Taylor</span>
  <span m="2736700">series.</span></p><p><span m="2756980">There's</span> <span m="2757130">something</span>
  <span m="2757520">really</span> <span m="2757880">cool</span> <span m="2758180">that</span>
  <span m="2758280">we're</span> <span m="2758340">going</span> <span m="2758400">to</span>
  <span m="2758540">have</span> <span m="2758640">to</span> <span m="2758700">do</span>
  <span m="2758780">with</span> <span m="2758900">this.</span> <span m="2759080">I</span>
  <span m="2759110">mean,</span> <span m="2759300">if</span> <span m="2759400">I</span>
  <span m="2759500">do</span> <span m="2759600">this</span> <span m="2759620">in</span>
  <span m="2759740">general,</span> <span m="2760160">you're</span> <span m="2760280">going</span>
  <span m="2760370">to</span> <span m="2760460">get</span> <span m="2760640">something</span>
  <span m="2760850">pretty</span> <span m="2761060">vomitous</span> <span m="2761720">It's</span>
  <span m="2762160">a</span> <span m="2762230">giant,</span> <span m="2762710">giant</span>
  <span m="2763100">mess.</span> <span m="2763450">OK?</span> <span m="2763700">You</span>
  <span m="2763760">might</span> <span m="2763940">worry,</span> <span m="2764240">what</span>
  <span m="2764360">the</span> <span m="2764450">hell</span> <span m="2764600">are</span>
  <span m="2764630">we</span> <span m="2764690">going</span> <span m="2764800">to</span>
  <span m="2764870">do</span> <span m="2764990">with</span> <span m="2765110">this?</span></p><p><span
  m="2766360">OK,</span> <span m="2766580">but</span> <span m="2766670">there's</span>
  <span m="2766790">something</span> <span m="2767090">really</span> <span m="2767420">cool</span>
  <span m="2767690">that</span> <span m="2767780">we</span> <span m="2767870">can</span>
  <span m="2768020">do.</span> <span m="2768330">So</span> <span m="2768470">we</span>
  <span m="2768890">are</span> <span m="2769340">given</span> <span m="2769910">the</span>
  <span m="2770060">metric</span> <span m="2770630">g.</span> <span m="2771650">But</span>
  <span m="2771860">we</span> <span m="2772070">are</span> <span m="2772220">free</span>
  <span m="2772730">to</span> <span m="2772880">pick</span> <span m="2773210">our</span>
  <span m="2773330">coordinate</span> <span m="2773670">transformation</span> <span
  m="2774230">to</span> <span m="2774290">be</span> <span m="2774440">whatever</span>
  <span m="2775070">we</span> <span m="2775280">want</span> <span m="2775580">it</span>
  <span m="2775760">to</span> <span m="2775880">be.</span></p><p><span m="2777000">So</span>
  <span m="2777050">what</span> <span m="2777230">we</span> <span m="2777300">are</span>
  <span m="2777410">going</span> <span m="2777620">to</span> <span m="2777740">do</span>
  <span m="2778070">is</span> <span m="2778340">compare</span> <span m="2783620">the</span>
  <span m="2783740">degrees</span> <span m="2784430">of</span> <span m="2784580">freedom</span>
  <span m="2790490">offered</span> <span m="2790850">by</span> <span m="2791030">the</span>
  <span m="2791120">coordinate</span> <span m="2791480">transformation.</span> <span
  m="2792950">Which</span> <span m="2793130">again,</span> <span m="2793370">I</span>
  <span m="2793400">emphasize,</span> <span m="2793820">we</span> <span m="2794000">are</span>
  <span m="2794090">free</span> <span m="2794510">to</span> <span m="2794630">make</span>
  <span m="2794840">that</span> <span m="2795020">whatever</span> <span m="2795500">we</span>
  <span m="2795590">need</span> <span m="2795690">it</span> <span m="2795800">to</span>
  <span m="2795890">be.</span> <span m="2804760">So</span> <span m="2805020">the</span>
  <span m="2805140">coordinate</span> <span m="2805550">transformation</span> <span
  m="2805910">and its</span> <span m="2806270">derivative,</span> <span m="2806700">right?</span>
  <span m="2806840">We're</span> <span m="2806960">free</span> <span m="2807110">to</span>
  <span m="2807530">play</span> <span m="2807770">around</span> <span m="2807950">with</span>
  <span m="2808070">this</span> <span m="2808220">thing.</span> <span m="2808940">It's</span>
  <span m="2809150">under</span> <span m="2809420">our</span> <span m="2809660">control.</span>
  <span m="2820230">To</span> <span m="2820440">the</span> <span m="2820530">constraints</span>
  <span m="2822540">that</span> <span m="2822690">are</span> <span m="2822750">imposed</span>
  <span m="2823530">by</span> <span m="2823740">the</span> <span m="2823860">metric</span>
  <span m="2824490">and</span> <span m="2824580">its</span> <span m="2824700">derivatives,</span>
  <span m="2825210">which</span> <span m="2825390">we</span> <span m="2825510">are</span>
  <span m="2825570">given.</span></p><p><span m="2843470">So</span> <span m="2843520">what</span>
  <span m="2843640">we're</span> <span m="2843730">essentially</span> <span m="2844090">going</span>
  <span m="2844330">to</span> <span m="2844420">do--</span> <span m="2847150">so</span>
  <span m="2847300">in</span> <span m="2847390">a</span> <span m="2847420">moment</span>
  <span m="2847690">or</span> <span m="2847720">two,</span> <span m="2847980">I'm</span>
  <span m="2848040">going</span> <span m="2848110">to</span> <span m="2848200">write</span>
  <span m="2848500">out</span> <span m="2849730">very</span> <span m="2849970">schematically</span>
  <span m="2851260">what</span> <span m="2851950">this</span> <span m="2853030">coordinate</span>
  <span m="2853420">transformation</span> <span m="2854050">is</span> <span m="2854140">going</span>
  <span m="2854320">to</span> <span m="2854410">look</span> <span m="2854650">like</span>
  <span m="2854890">when</span> <span m="2855010">I</span> <span m="2855070">do</span>
  <span m="2855250">the</span> <span m="2855340">Taylor</span> <span m="2855670">expansion.</span>
  <span m="2857170">And</span> <span m="2857950">what</span> <span m="2858280">I</span>
  <span m="2858430">want</span> <span m="2858640">to</span> <span m="2858760">do</span>
  <span m="2858940">is,</span> <span m="2859060">essentially,</span> <span m="2859420">just</span>
  <span m="2859570">count</span> <span m="2860020">up</span> <span m="2860620">how</span>
  <span m="2860950">many</span> <span m="2861640">degrees</span> <span m="2862030">of</span>
  <span m="2862090">freedom</span> <span m="2862690">the</span> <span m="2862840">coordinate</span>
  <span m="2863200">system</span> <span m="2863530">offers</span> <span m="2863830">me,</span>
  <span m="2864490">count</span> <span m="2864850">up</span> <span m="2865030">the</span>
  <span m="2865150">number</span> <span m="2865420">of</span> <span m="2865510">constraints</span>
  <span m="2866530">that</span> <span m="2866680">need</span> <span m="2866860">to</span>
  <span m="2866920">be</span> <span m="2867040">matched</span> <span m="2867490">in</span>
  <span m="2867580">order</span> <span m="2867790">to</span> <span m="2867970">effect</span>
  <span m="2868300">this</span> <span m="2868450">transformation,</span> <span m="2869620">see</span>
  <span m="2869920">whether</span> <span m="2870190">I've</span> <span m="2870280">got</span>
  <span m="2870490">enough.</span> <span m="2872220">Assess</span> <span m="2872520">what</span>
  <span m="2872610">we</span> <span m="2872700">learn</span> <span m="2872880">from</span>
  <span m="2873030">that,</span> <span m="2873666">OK?</span></p><p><span m="2882610">We</span>
  <span m="2882880">just</span> <span m="2883030">set</span> <span m="2883240">up</span>
  <span m="2883360">with</span> <span m="2883480">a</span> <span m="2883540">few</span>
  <span m="2883810">more</span> <span m="2884020">things</span> <span m="2885070">to</span>
  <span m="2885190">help</span> <span m="2885370">define</span> <span m="2885730">the</span>
  <span m="2885820">logic.</span> <span m="2890000">So</span> <span m="2890170">I'm</span>
  <span m="2890260">going</span> <span m="2890350">to</span> <span m="2890440">write</span>
  <span m="2892340">G</span> <span m="2892600">alpha</span> <span m="2892870">beta</span>
  <span m="2895290">as</span> <span m="2895810">G</span> <span m="2896200">alpha</span>
  <span m="2896470">beta</span> <span m="2897670">at</span> <span m="2897820">the</span>
  <span m="2897880">point</span> <span m="2898180">p</span> <span m="2899560">plus</span>
  <span m="2901480">x</span> <span m="2901720">gamma.</span> <span m="2902840">And</span>
  <span m="2902860">you know</span> <span m="2902930">what?</span> <span m="2903110">Let's</span>
  <span m="2903220">do</span> <span m="2903310">the</span> <span m="2903400">expansion</span>
  <span m="2903850">in</span> <span m="2903910">the</span> <span m="2903970">bar</span>
  <span m="2904220">coordinate.</span> <span m="2906950">Minus</span> <span m="2907470">x</span>
  <span m="2907690">gamma</span> <span m="2907980">bar</span> <span m="2908640">at</span>
  <span m="2908940">point</span> <span m="2909150">p</span> <span m="2912560">times</span>
  <span m="2913100">the</span> <span m="2913290">derivative</span> <span m="2914200">at</span>
  <span m="2914340">point</span> <span m="2914610">p.</span> <span m="2919580">And</span>
  <span m="2920060">then</span> <span m="2920170">I'm</span> <span m="2920230">going</span>
  <span m="2920300">to</span> <span m="2920390">get</span> <span m="2920540">something</span>
  <span m="2920960">that</span> <span m="2921080">involves</span> <span m="2926990">a</span>
  <span m="2927080">complicated</span> <span m="2927800">form</span> <span m="2928520">of</span>
  <span m="2929000">x</span> <span m="2929180">squared</span> <span m="2937260">and</span>
  <span m="2937460">second</span> <span m="2937820">derivatives.</span> <span m="2939150">OK,</span>
  <span m="2939350">this</span> <span m="2939500">can</span> <span m="2939620">keep</span>
  <span m="2939830">going.</span> <span m="2940160">But</span> <span m="2940280">this</span>
  <span m="2940400">is</span> <span m="2940470">going</span> <span m="2940530">to</span>
  <span m="2940610">be</span> <span m="2940670">enough</span> <span m="2940940">for</span>
  <span m="2941060">our</span> <span m="2941150">purposes.</span></p><p><span m="2942500">I</span>
  <span m="2942710">am</span> <span m="2942860">likewise</span> <span m="2947630">going</span>
  <span m="2947900">to</span> <span m="2948020">expand</span> <span m="2948440">my</span>
  <span m="2948650">coordinate</span> <span m="2949010">transformation</span> <span
  m="2949670">matrix.</span> <span m="2968940">Make sure</span> <span m="2969160">I</span>
  <span m="2969220">got</span> <span m="2969340">all</span> <span m="2969430">my</span>
  <span m="2969550">bars</span> <span m="2969880">in</span> <span m="2969970">place.</span>
  <span m="2971216">OK.</span> <span m="2987840">OK.</span> <span m="2994470">So</span>
  <span m="2994670">let me</span> <span m="2994760">go</span> <span m="2994970">over
  to</span> <span m="2995090">another</span> <span m="2995330">board,</span> <span
  m="2995720">just</span> <span m="2995870">write</span> <span m="2996020">down</span>
  <span m="2996170">a</span> <span m="2996230">few</span> <span m="2996470">more</span>
  <span m="2996740">important</span> <span m="2997160">things.</span> <span m="2997740">And</span>
  <span m="2997840">then</span> <span m="2997880">we'll</span> <span m="2998000">start</span>
  <span m="2998240">counting.</span></p><p><span m="3009510">So</span> <span m="3011830">first</span>
  <span m="3012130">key</span> <span m="3012310">thing,</span> <span m="3012490">which</span>
  <span m="3012640">I</span> <span m="3012700">want</span> <span m="3012880">to</span>
  <span m="3012940">note</span> <span m="3013150">before</span> <span m="3013480">I</span>
  <span m="3013930">dig</span> <span m="3014140">into</span> <span m="3014290">the</span>
  <span m="3014380">calculation,</span> <span m="3017400">is</span> <span m="3017580">the</span>
  <span m="3017640">metric</span> <span m="3018000">at</span> <span m="3018120">this</span>
  <span m="3018300">point,</span> <span m="3021550">its</span> <span m="3022070">derivative,</span>
  <span m="3025640">its</span> <span m="3025890">second</span> <span m="3026280">derivative.</span>
  <span m="3029590">These</span> <span m="3029950">have</span> <span m="3030040">been</span>
  <span m="3030220">handed</span> <span m="3030640">to</span> <span m="3030820">us.</span>
  <span m="3031960">OK?</span> <span m="3032290">So</span> <span m="3032710">we</span>
  <span m="3032920">have</span> <span m="3033010">no</span> <span m="3033190">freedom</span>
  <span m="3033490">to</span> <span m="3033580">play</span> <span m="3033790">with</span>
  <span m="3033880">these.</span> <span m="3034240">These</span> <span m="3034600">are</span>
  <span m="3034720">going</span> <span m="3034930">to</span> <span m="3034990">give</span>
  <span m="3035200">us</span> <span m="3035380">constraints</span> <span m="3036190">that</span>
  <span m="3036280">we</span> <span m="3036370">need</span> <span m="3036490">to</span>
  <span m="3036550">satisfy.</span> <span m="3051320">The</span> <span m="3051410">coordinate</span>
  <span m="3051800">transformation</span> <span m="3053960">in</span> <span m="3054200">its</span>
  <span m="3054350">various</span> <span m="3054740">derivatives,</span> <span m="3061610">we</span>
  <span m="3061730">are</span> <span m="3061820">free</span> <span m="3062180">to</span>
  <span m="3062300">specify</span> <span m="3062810">these.</span> <span m="3068166">These</span>
  <span m="3068880">are</span> <span m="3069120">our</span> <span m="3070080">degrees</span>
  <span m="3071250">of</span> <span m="3071370">freedom.</span></p><p><span m="3080670">OK,</span>
  <span m="3081090">so</span> <span m="3081270">let</span> <span m="3081360">me</span>
  <span m="3081480">just</span> <span m="3081810">restate</span> <span m="3083070">the</span>
  <span m="3083160">calculation</span> <span m="3083820">that</span> <span m="3083910">we</span>
  <span m="3084030">are</span> <span m="3084090">going</span> <span m="3084330">to</span>
  <span m="3084450">do.</span> <span m="3084630">Basically,</span> <span m="3085020">we</span>
  <span m="3085140">wanted</span> <span m="3085430">to</span> <span m="3085560">do</span>
  <span m="3085830">this.</span> <span m="3087960">Schematically,</span> <span m="3088980">here's</span>
  <span m="3089280">what</span> <span m="3089400">this</span> <span m="3089550">calculation</span>
  <span m="3090210">is</span> <span m="3090330">going</span> <span m="3090540">to</span>
  <span m="3090630">look</span> <span m="3090810">like.</span> <span m="3093610">And</span>
  <span m="3094140">if</span> <span m="3094260">you</span> <span m="3094320">look</span>
  <span m="3094470">at</span> <span m="3094530">this</span> <span m="3094680">right</span>
  <span m="3094890">now,</span> <span m="3095610">you</span> <span m="3095730">might</span>
  <span m="3095910">think</span> <span m="3096120">this</span> <span m="3096210">is</span>
  <span m="3096280">going</span> <span m="3096360">to</span> <span m="3096450">be</span>
  <span m="3096540">horrible.</span> <span m="3096990">But</span> <span m="3097080">we</span>
  <span m="3097200">don't</span> <span m="3097440">need</span> <span m="3097650">to</span>
  <span m="3097830">specify</span> <span m="3098610">every</span> <span m="3099270">step</span>
  <span m="3099570">of</span> <span m="3099630">this</span> <span m="3099810">thing</span>
  <span m="3100020">in</span> <span m="3100110">absolutely</span> <span m="3100560">gory</span>
  <span m="3100830">detail.</span></p><p><span m="3106040">What</span> <span m="3106250">we</span>
  <span m="3106370">want</span> <span m="3106550">to</span> <span m="3106670">do</span>
  <span m="3107150">is</span> <span m="3107390">make</span> <span m="3116050">this,</span>
  <span m="3117350">which</span> <span m="3117490">I</span> <span m="3117580">can</span>
  <span m="3117760">write</span> <span m="3118180">as</span> <span m="3121480">this</span>
  <span m="3121750">guy</span> <span m="3122370">at</span> <span m="3122500">point</span>
  <span m="3122840">p,</span> <span m="3129360">this</span> <span m="3129540">guy</span>
  <span m="3129810">at</span> <span m="3129930">point</span> <span m="3130240">p,</span>
  <span m="3135810">this</span> <span m="3135990">guy</span> <span m="3136410">at</span>
  <span m="3136500">point</span> <span m="3136740">p</span> <span m="3138210">plus</span>
  <span m="3143970">a</span> <span m="3144030">term</span> <span m="3144390">that</span>
  <span m="3144520">is</span> <span m="3144580">going</span> <span m="3144660">to</span>
  <span m="3144750">be</span> <span m="3144990">linear</span> <span m="3147150">in</span>
  <span m="3147450">the</span> <span m="3147510">distance</span> <span m="3147930">from</span>
  <span m="3148290">the</span> <span m="3148350">spacetime</span> <span m="3149820">displacement</span>
  <span m="3150390">away</span> <span m="3150600">from</span> <span m="3150750">point</span>
  <span m="3151020">p.</span> <span m="3157130">If</span> <span m="3157280">you</span>
  <span m="3157530">want</span> <span m="3157650">to</span> <span m="3157710">go</span>
  <span m="3157810">and</span> <span m="3157870">multiply</span> <span m="3158250">this</span>
  <span m="3158460">out,</span> <span m="3158640">knock</span> <span m="3158880">yourself</span>
  <span m="3159240">out.</span> <span m="3159420">But</span> <span m="3159540">it</span>
  <span m="3159630">suffices</span> <span m="3160230">to</span> <span m="3160320">know</span>
  <span m="3160620">that</span> <span m="3161580">you</span> <span m="3161790">are</span>
  <span m="3161880">going</span> <span m="3162120">to</span> <span m="3162210">get</span>
  <span m="3162390">some</span> <span m="3162600">new</span> <span m="3162810">things</span>
  <span m="3163230">that</span> <span m="3163350">involve</span> <span m="3163860">first</span>
  <span m="3164280">derivatives</span> <span m="3164760">of</span> <span m="3164850">all</span>
  <span m="3164970">these</span> <span m="3165120">quantities.</span> <span m="3166180">So</span>
  <span m="3166230">this</span> <span m="3166440">will</span> <span m="3166650">involve</span>
  <span m="3175330">these</span> <span m="3175570">two</span> <span m="3175720">things.</span>
  <span m="3190310">And</span> <span m="3190470">this</span> <span m="3190650">will</span>
  <span m="3190830">involve</span> <span m="3194100">second</span> <span m="3194490">derivatives</span>
  <span m="3194790">of</span> <span m="3194910">all</span> <span m="3195000">these</span>
  <span m="3195240">things.</span></p><p><span m="3200530">Now</span> <span m="3200680">what</span>
  <span m="3200760">we're</span> <span m="3200860">going</span> <span m="3201040">to</span>
  <span m="3201130">do</span> <span m="3201550">is</span> <span m="3201640">we're</span>
  <span m="3201730">going</span> <span m="3201850">to</span> <span m="3201910">try</span>
  <span m="3202270">to</span> <span m="3202420">make</span> <span m="3203080">what</span>
  <span m="3203260">we</span> <span m="3203380">would</span> <span m="3203500">get</span>
  <span m="3203830">multiplying</span> <span m="3204400">all</span> <span m="3204490">this</span>
  <span m="3204670">out</span> <span m="3204830">look</span> <span m="3205090">as</span>
  <span m="3205300">much</span> <span m="3205810">like</span> <span m="3207010">minus</span>
  <span m="3207370">1,</span> <span m="3207740">1,</span> <span m="3208110">1, 1</span>
  <span m="3208480">of the</span> <span m="3208540">diagonal</span> <span m="3208960">as</span>
  <span m="3209140">possible.</span> <span m="3210560">And</span> <span m="3210670">like</span>
  <span m="3210790">I</span> <span m="3210850">said,</span> <span m="3211220">it</span>
  <span m="3211240">really</span> <span m="3211840">just</span> <span m="3212380">involves</span>
  <span m="3213430">accounting</span> <span m="3213910">argument.</span> <span m="3214600">It's</span>
  <span m="3214910">actually</span> <span m="3215080">one</span> <span m="3215170">of</span>
  <span m="3215230">my</span> <span m="3215320">favorite</span> <span m="3215620">little</span>
  <span m="3215740">calculations</span> <span m="3216310">we</span> <span m="3216400">do</span>
  <span m="3216520">in</span> <span m="3216610">this</span> <span m="3216730">class</span>
  <span m="3217090">because</span> <span m="3217390">it's</span> <span m="3218980">my</span>
  <span m="3219100">favorite</span> <span m="3219370">word</span> <span m="3219580">for</span>
  <span m="3219640">this</span> <span m="3219820">is</span> <span m="3219910">it</span>
  <span m="3220000">really</span> <span m="3220210">looks</span> <span m="3220420">vomitous.</span>
  <span m="3220960">But</span> <span m="3222100">it's</span> <span m="3222280">quite</span>
  <span m="3222670">elegant.</span></p><p><span m="3225700">And</span> <span m="3229450">I</span>
  <span m="3229480">have</span> <span m="3229570">an</span> <span m="3229690">eight-year-old</span>
  <span m="3230050">kid.</span> <span m="3230290">And</span> <span m="3230380">I'm</span>
  <span m="3230470">constantly</span> <span m="3230860">trying</span> <span m="3231070">to</span>
  <span m="3231160">teach</span> <span m="3231400">her,</span> <span m="3231520">math</span>
  <span m="3231880">is</span> <span m="3231970">just</span> <span m="3232150">all</span>
  <span m="3232330">about</span> <span m="3232600">counting.</span> <span m="3232860">And</span>
  <span m="3233120">this</span> <span m="3233230">is</span> <span m="3233290">a</span>
  <span m="3233320">perfect</span> <span m="3233590">example.</span> <span m="3234080">This</span>
  <span m="3234100">is</span> <span m="3234190">really</span> <span m="3234520">just</span>
  <span m="3234910">about</span> <span m="3235270">counting.</span></p><p><span m="3236770">So</span>
  <span m="3237040">let's</span> <span m="3237220">look</span> <span m="3237370">at</span>
  <span m="3237430">this</span> <span m="3237610">thing</span> <span m="3237850">at</span>
  <span m="3238000">0th</span> <span m="3238390">order.</span> <span m="3242930">So</span>
  <span m="3243080">what</span> <span m="3243260">I'm</span> <span m="3243410">trying</span>
  <span m="3243710">to</span> <span m="3243800">do</span> <span m="3244130">is</span>
  <span m="3244520">guarantee</span> <span m="3245150">that</span> <span m="3245480">I've</span>
  <span m="3245720">got</span> <span m="3246020">some</span> <span m="3246710">l,</span>
  <span m="3247760">which</span> <span m="3247970">I</span> <span m="3248060">can</span>
  <span m="3248240">choose,</span> <span m="3248780">which</span> <span m="3249020">will</span>
  <span m="3249110">make</span> <span m="3249380">the</span> <span m="3249500">components</span>
  <span m="3250250">of</span> <span m="3250370">the</span> <span m="3250550">g</span>
  <span m="3250865">at</span> <span m="3251180">that</span> <span m="3251360">point</span>
  <span m="3251690">be</span> <span m="3251960">minus</span> <span m="3252290">1,</span>
  <span m="3252950">1,</span> <span m="3253190">1,</span> <span m="3253400">1.</span></p><p><span
  m="3255260">So</span> <span m="3255710">my</span> <span m="3255980">constraints,</span>
  <span m="3259630">the</span> <span m="3259730">conditions</span> <span m="3260240">I</span>
  <span m="3260360">must</span> <span m="3260570">satisfy</span> <span m="3262550">involve</span>
  <span m="3263600">things</span> <span m="3264140">that</span> <span m="3264320">hit</span>
  <span m="3264620">these</span> <span m="3266060">4</span> <span m="3266420">by</span>
  <span m="3266660">4</span> <span m="3267260">symmetric</span> <span m="3268370">tensor</span>
  <span m="3268760">components.</span> <span m="3270240">So</span> <span m="3270290">this</span>
  <span m="3270500">guy</span> <span m="3270800">is</span> <span m="3271010">something</span>
  <span m="3271340">that</span> <span m="3271460">is</span> <span m="3271550">symmetric.</span>
  <span m="3276280">Nature</span> <span m="3276700">has</span> <span m="3276940">just</span>
  <span m="3277120">handed</span> <span m="3277420">me</span> <span m="3277990">a</span>
  <span m="3278050">symmetric</span> <span m="3278470">tensor</span> <span m="3278830">with</span>
  <span m="3279240">a</span> <span m="3279310">symmetric</span> <span m="3279700">4</span>
  <span m="3279880">by</span> <span m="3280000">4</span> <span m="3280270">object.</span>
  <span m="3281230">Those</span> <span m="3281590">are</span> <span m="3281710">10</span>
  <span m="3282220">constraints</span> <span m="3283060">that</span> <span m="3283180">my</span>
  <span m="3283300">transformation</span> <span m="3283990">must</span> <span m="3284170">satisfy.</span></p><p><span
  m="3295590">What</span> <span m="3295800">I'm</span> <span m="3295920">going</span>
  <span m="3296130">to</span> <span m="3296220">use</span> <span m="3296520">to</span>
  <span m="3296610">do</span> <span m="3296820">this</span> <span m="3297420">is</span>
  <span m="3299490">this</span> <span m="3299730">matrix</span> <span m="3301350">at</span>
  <span m="3301470">the</span> <span m="3301560">point</span> <span m="3301840">p.</span>
  <span m="3303270">And</span> <span m="3303390">I'll</span> <span m="3303450">remind</span>
  <span m="3303840">you,</span> <span m="3303960">this</span> <span m="3304110">matrix</span>
  <span m="3305240">is</span> <span m="3305430">just</span> <span m="3309870">following</span>
  <span m="3310260">set</span> <span m="3310470">of</span> <span m="3310590">partial</span>
  <span m="3310980">derivatives</span> <span m="3311940">at</span> <span m="3312060">that</span>
  <span m="3312240">point</span> <span m="3312480">p.</span> <span m="3314280">This</span>
  <span m="3314430">is</span> <span m="3314550">also</span> <span m="3314880">4</span>
  <span m="3315120">by</span> <span m="3315300">4.</span> <span m="3316290">It</span>
  <span m="3316650">is</span> <span m="3316890">not</span> <span m="3317700">symmetric.</span>
  <span m="3320460">So</span> <span m="3320640">this</span> <span m="3321060">actually</span>
  <span m="3321540">gives</span> <span m="3321840">me</span> <span m="3323120">16</span>
  <span m="3323760">degrees</span> <span m="3324180">of</span> <span m="3324240">freedom</span>
  <span m="3329670">to</span> <span m="3329820">satisfy</span> <span m="3330450">these</span>
  <span m="3330630">constraints.</span></p><p><span m="3339868">Ta</span> <span m="3340349">da!</span>
  <span m="3340840">We</span> <span m="3341020">can</span> <span m="3341290">easily</span>
  <span m="3342010">make</span> <span m="3342310">this</span> <span m="3342490">thing</span>
  <span m="3342910">look</span> <span m="3343210">Lorentzian</span> <span m="3343810">at</span>
  <span m="3344020">the</span> <span m="3344110">point</span> <span m="3344410">p.</span>
  <span m="3344980">In</span> <span m="3345100">fact,</span> <span m="3345400">we</span>
  <span m="3345490">can</span> <span m="3345640">do</span> <span m="3345850">so</span>
  <span m="3346150">and</span> <span m="3346300">have</span> <span m="3346570">six</span>
  <span m="3346930">degrees</span> <span m="3347290">of</span> <span m="3347350">freedom</span>
  <span m="3347680">left</span> <span m="3347880">over.</span> <span m="3349180">Any</span>
  <span m="3349330">idea</span> <span m="3349570">what</span> <span m="3349690">those</span>
  <span m="3349870">six</span> <span m="3350110">degrees</span> <span m="3350380">of</span>
  <span m="3350440">freedom</span> <span m="3350710">are?</span> <span m="3352840">Remember</span>
  <span m="3353280">you're</span> <span m="3353380">going</span> <span m="3353560">into</span>
  <span m="3353740">a</span> <span m="3353800">Lorentz</span> <span m="3354220">frame.</span>
  <span m="3355406">Yeah?</span> <span m="3357180">Three</span> <span m="3357510">rotations,</span>
  <span m="3358140">three</span> <span m="3358380">boosts.</span> <span m="3358830">Exactly</span>
  <span m="3359280">right.</span></p><p><span m="3373640">Boom.</span> <span m="3374820">So</span>
  <span m="3375030">not</span> <span m="3375300">only</span> <span m="3376020">does</span>
  <span m="3376290">it</span> <span m="3376380">work</span> <span m="3376620">mathematically,</span>
  <span m="3378940">but</span> <span m="3379050">there's</span> <span m="3379200">a</span>
  <span m="3379230">little</span> <span m="3379410">bit</span> <span m="3379770">of</span>
  <span m="3380160">leftover</span> <span m="3380670">stuff</span> <span m="3381030">which</span>
  <span m="3381660">hopefully</span> <span m="3382080">hits</span> <span m="3382320">our</span>
  <span m="3382410">intuition</span> <span m="3382890">as</span> <span m="3382980">to</span>
  <span m="3383070">how</span> <span m="3383220">things</span> <span m="3383460">should</span>
  <span m="3383790">behave</span> <span m="3384210">in</span> <span m="3384300">special</span>
  <span m="3384600">relativity.</span> <span m="3388956">OK,</span> <span m="3389450">that's</span>
  <span m="3389600">not</span> <span m="3389780">really</span> <span m="3390020">good</span>
  <span m="3390170">enough</span> <span m="3390380">though,</span> <span m="3390620">right?</span>
  <span m="3391400">So</span> <span m="3391550">I</span> <span m="3391620">just</span>
  <span m="3391690">showed</span> <span m="3391880">that</span> <span m="3391970">I</span>
  <span m="3392030">can</span> <span m="3392180">do</span> <span m="3392360">it</span>
  <span m="3392540">at</span> <span m="3392780">this</span> <span m="3393050">point.</span>
  <span m="3394140">And</span> <span m="3394520">if</span> <span m="3394640">I</span>
  <span m="3394760">move</span> <span m="3395030">a</span> <span m="3395120">centimeter</span>
  <span m="3395630">away</span> <span m="3395870">from</span> <span m="3396050">that</span>
  <span m="3396200">point,</span> <span m="3397400">suppose,</span> <span m="3398330">there's</span>
  <span m="3398510">some</span> <span m="3398720">really</span> <span m="3398900">steep</span>
  <span m="3399170">gradient,</span> <span m="3399590">and then it</span> <span m="3399680">goes</span>
  <span m="3400310">completely</span> <span m="3400670">to</span> <span m="3400760">hell.</span>
  <span m="3401040">OK?</span> <span m="3401270">Then</span> <span m="3401450">we're</span>
  <span m="3401540">in</span> <span m="3401630">trouble.</span></p><p><span m="3402600">So</span>
  <span m="3402650">we</span> <span m="3402770">have</span> <span m="3402860">to</span>
  <span m="3402950">keep</span> <span m="3403130">going.</span> <span m="3403580">We</span>
  <span m="3403700">have</span> <span m="3403790">to</span> <span m="3403880">look</span>
  <span m="3404180">at</span> <span m="3404810">the</span> <span m="3404960">additional</span>
  <span m="3405320">terms</span> <span m="3405740">in</span> <span m="3405800">this</span>
  <span m="3405950">expansion.</span> <span m="3412420">So</span> <span m="3412570">when</span>
  <span m="3412660">we</span> <span m="3412780">do</span> <span m="3412930">things</span>
  <span m="3413170">at</span> <span m="3413290">0th</span> <span m="3413690">order,</span>
  <span m="3414700">we</span> <span m="3414880">have</span> <span m="3415060">now--</span>
  <span m="3415630">so</span> <span m="3415850">g has</span> <span m="3416260">been</span>
  <span m="3416380">handed</span> <span m="3416680">to</span> <span m="3416830">us.</span>
  <span m="3417400">We</span> <span m="3417580">have</span> <span m="3417730">now</span>
  <span m="3418060">specified</span> <span m="3418810">behavior</span> <span m="3419290">of</span>
  <span m="3419470">l</span> <span m="3419770">at</span> <span m="3419950">that</span>
  <span m="3420160">point.</span> <span m="3421900">So</span> <span m="3422140">l</span>
  <span m="3422380">has</span> <span m="3422620">been</span> <span m="3423160">completely</span>
  <span m="3425200">soaked</span> <span m="3425530">up.</span> <span m="3425710">I</span>
  <span m="3425770">don't</span> <span m="3425920">have</span> <span m="3426010">any</span>
  <span m="3426130">more</span> <span m="3426280">freedom</span> <span m="3426610">to</span>
  <span m="3426910">mess</span> <span m="3427120">around</span> <span m="3427360">with</span>
  <span m="3427480">it.</span></p><p><span m="3429340">When</span> <span m="3429460">I</span>
  <span m="3429520">go</span> <span m="3429670">to</span> <span m="3429760">the</span>
  <span m="3429850">next</span> <span m="3430180">order,</span> <span m="3436490">OK,</span>
  <span m="3436770">so</span> <span m="3437100">the</span> <span m="3437220">quantity</span>
  <span m="3437990">that</span> <span m="3438200">is</span> <span m="3438330">setting</span>
  <span m="3438570">my</span> <span m="3438750">constraints</span> <span m="3442280">is</span>
  <span m="3442550">the</span> <span m="3442640">first</span> <span m="3442910">derivative</span>
  <span m="3443330">of</span> <span m="3443420">this.</span> <span m="3445350">So</span>
  <span m="3445400">these</span> <span m="3445610">are</span> <span m="3445700">four</span>
  <span m="3446240">derivatives</span> <span m="3447380">of</span> <span m="3447710">my</span>
  <span m="3448550">10</span> <span m="3449300">metric</span> <span m="3449810">functions.</span>
  <span m="3458100">4</span> <span m="3458340">by</span> <span m="3458460">4</span>
  <span m="3458700">symmetric</span> <span m="3460200">by</span> <span m="3463970">4</span>
  <span m="3464240">components.</span> <span m="3467770">So</span> <span m="3467940">I</span>
  <span m="3468180">have</span> <span m="3468330">got</span> <span m="3469770">40</span>
  <span m="3470160">constraints</span> <span m="3470700">I</span> <span m="3470760">must</span>
  <span m="3470910">satisfy.</span></p><p><span m="3479010">OK,</span> <span m="3479940">well,</span>
  <span m="3480180">the</span> <span m="3480300">tool</span> <span m="3480570">that</span>
  <span m="3480660">I</span> <span m="3480690">have</span> <span m="3480810">available,</span>
  <span m="3481290">I</span> <span m="3481440">am</span> <span m="3481530">free</span>
  <span m="3481830">to</span> <span m="3481920">specify</span> <span m="3482580">the</span>
  <span m="3483780">derivatives</span> <span m="3484260">at</span> <span m="3484380">this</span>
  <span m="3484530">point.</span> <span m="3487560">Again,</span> <span m="3487830">remember</span>
  <span m="3488250">this</span> <span m="3488460">is</span> <span m="3488580">itself</span>
  <span m="3488940">a</span> <span m="3489000">partial</span> <span m="3489330">derivative.</span>
  <span m="3500860">So</span> <span m="3501340">I've</span> <span m="3501670">got</span>
  <span m="3502150">4</span> <span m="3502480">components</span> <span m="3503200">alpha,</span>
  <span m="3511710">4</span> <span m="3512080">derivatives</span> <span m="3512520">with</span>
  <span m="3512640">gamma</span> <span m="3512970">bar,</span> <span m="3513300">4</span>
  <span m="3513540">derivatives</span> <span m="3514080">with</span> <span m="3514260">mu</span>
  <span m="3514500">bar.</span> <span m="3515640">Partial</span> <span m="3516150">derivatives,</span>
  <span m="3516630">it</span> <span m="3516720">should</span> <span m="3516960">not</span>
  <span m="3518070">matter</span> <span m="3518340">what</span> <span m="3518490">the</span>
  <span m="3518610">order</span> <span m="3518910">is.</span> <span m="3519450">So</span>
  <span m="3519600">this</span> <span m="3519900">needs</span> <span m="3520230">to</span>
  <span m="3520290">be</span> <span m="3520410">symmetric</span> <span m="3521520">on</span>
  <span m="3521700">mu</span> <span m="3521970">and</span> <span m="3522120">gamma.</span></p><p><span
  m="3532430">So</span> <span m="3532540">I,</span> <span m="3532600">in</span> <span
  m="3532690">fact,</span> <span m="3533200">have</span> <span m="3533500">40</span>
  <span m="3533890">degrees</span> <span m="3534190">of</span> <span m="3534250">freedom</span>
  <span m="3535090">at</span> <span m="3535210">1st</span> <span m="3535480">order.</span>
  <span m="3543400">Perfect</span> <span m="3543700">match.</span> <span m="3544980">OK?</span>
  <span m="3545320">So</span> <span m="3545500">I</span> <span m="3545590">can</span>
  <span m="3545710">make</span> <span m="3545920">my</span> <span m="3546150">coordinate</span>
  <span m="3546550">system.</span> <span m="3546970">Not</span> <span m="3547300">only</span>
  <span m="3547630">can</span> <span m="3547810">I</span> <span m="3547930">make</span>
  <span m="3548230">it</span> <span m="3548440">equal</span> <span m="3548800">to</span>
  <span m="3550000">the</span> <span m="3550120">Lorentz</span> <span m="3550480">form</span>
  <span m="3550900">at--</span> <span m="3551140">I</span> <span m="3551200">can</span>
  <span m="3551350">make</span> <span m="3551470">the</span> <span m="3551560">spacetime</span>
  <span m="3551780">metric</span> <span m="3552190">Lorentz</span> <span m="3552730">at</span>
  <span m="3552940">the</span> <span m="3553030">point</span> <span m="3553360">p,</span>
  <span m="3554110">I</span> <span m="3554170">can</span> <span m="3554320">also</span>
  <span m="3554530">make</span> <span m="3554710">it</span> <span m="3554800">flat</span>
  <span m="3555340">at</span> <span m="3555460">that</span> <span m="3555640">point</span>
  <span m="3555970">p.</span></p><p><span m="3559820">All</span> <span m="3559910">right,</span>
  <span m="3561170">now</span> <span m="3561290">we're</span> <span m="3561380">feeling</span>
  <span m="3561620">cocky.</span> <span m="3561950">So</span> <span m="3562040">let's</span>
  <span m="3562160">move</span> <span m="3562340">on.</span> <span m="3564860">How</span>
  <span m="3565130">far</span> <span m="3565520">can</span> <span m="3565760">I</span>
  <span m="3565850">go?</span> <span m="3569950">I</span> <span m="3570100">lost</span>
  <span m="3570400">the</span> <span m="3570490">page</span> <span m="3570790">I</span>
  <span m="3570820">need.</span> <span m="3590970">OK,</span> <span m="3591130">so</span>
  <span m="3591230">now</span> <span m="3591380">you</span> <span m="3591440">have</span>
  <span m="3591530">a</span> <span m="3591560">flavor</span> <span m="3591980">for</span>
  <span m="3592070">what</span> <span m="3592220">we're</span> <span m="3592310">doing.</span>
  <span m="3592740">OK?</span> <span m="3592960">I</span> <span m="3593000">want</span>
  <span m="3593120">to</span> <span m="3593180">count</span> <span m="3593480">up</span>
  <span m="3593660">the</span> <span m="3593750">number</span> <span m="3594050">of</span>
  <span m="3594140">degrees</span> <span m="3594530">of--</span> <span m="3595250">sorry--</span>
  <span m="3595940">the</span> <span m="3596060">number</span> <span m="3596300">of</span>
  <span m="3596390">constraints</span> <span m="3597080">that</span> <span m="3597260">are</span>
  <span m="3597860">in</span> <span m="3598100">the</span> <span m="3598190">metric</span>
  <span m="3598550">object,</span> <span m="3599060">the</span> <span m="3599160">new</span>
  <span m="3599270">metric</span> <span m="3599550">object</span> <span m="3599900">I</span>
  <span m="3599990">work</span> <span m="3600200">with</span> <span m="3600340">at</span>
  <span m="3600470">this</span> <span m="3600620">order</span> <span m="3601370">and</span>
  <span m="3601850">compare</span> <span m="3602240">it</span> <span m="3602300">to</span>
  <span m="3602420">the</span> <span m="3602480">degrees</span> <span m="3602780">of</span>
  <span m="3602840">freedom</span> <span m="3603380">in</span> <span m="3603530">the</span>
  <span m="3603620">coordinate</span> <span m="3603890">transformation</span> <span
  m="3604490">at</span> <span m="3604550">this</span> <span m="3604700">order.</span></p><p><span
  m="3609420">So</span> <span m="3609460">when</span> <span m="3609540">I</span> <span
  m="3609590">go</span> <span m="3609700">to</span> <span m="3609770">2nd</span> <span
  m="3610100">order,</span> <span m="3610280">my</span> <span m="3610460">new</span>
  <span m="3610640">metric</span> <span m="3611030">thing</span> <span m="3611300">that</span>
  <span m="3611390">I'm</span> <span m="3611450">going to be</span> <span m="3611630">messing</span>
  <span m="3611900">around</span> <span m="3612170">with</span> <span m="3613430">is</span>
  <span m="3613970">the</span> <span m="3614060">second</span> <span m="3614390">derivative.</span>
  <span m="3616050">So</span> <span m="3616070">I</span> <span m="3616130">take</span>
  <span m="3616340">two</span> <span m="3616550">derivatives</span> <span m="3618390">of</span>
  <span m="3619065">g</span> <span m="3619400">alpha</span> <span m="3619715">beta</span>
  <span m="3620030">at</span> <span m="3620150">the</span> <span m="3620240">point</span>
  <span m="3620480">p.</span> <span m="3622840">So</span> <span m="3623120">this</span>
  <span m="3623310">again</span> <span m="3623550">needs</span> <span m="3623820">to</span>
  <span m="3623880">be</span> <span m="3624000">symmetric</span> <span m="3624490">in
  the</span> <span m="3624590">derivative.</span> <span m="3625770">So</span> <span
  m="3626010">I</span> <span m="3626100">have</span> <span m="3626250">a</span> <span
  m="3626280">symmetric</span> <span m="3627810">4</span> <span m="3628140">by</span>
  <span m="3628320">4</span> <span m="3636390">on</span> <span m="3636540">these</span>
  <span m="3636750">two</span> <span m="3636930">guys.</span> <span m="3638820">And</span>
  <span m="3639480">the</span> <span m="3639570">metric</span> <span m="3639930">is</span>
  <span m="3640050">itself</span> <span m="3643000">4</span> <span m="3643300">by</span>
  <span m="3643480">4,</span> <span m="3645840">one</span> <span m="3646230">alpha</span>
  <span m="3646530">and</span> <span m="3646630">beta.</span> <span m="3649030">So</span>
  <span m="3649240">there</span> <span m="3649500">is</span> <span m="3649670">100</span>
  <span m="3650020">conditions,</span> <span m="3650470">100</span> <span m="3650710">constraints</span>
  <span m="3651190">that</span> <span m="3651280">we</span> <span m="3651370">must</span>
  <span m="3651520">satisfy.</span></p><p><span m="3655750">So</span> <span m="3657160">let's</span>
  <span m="3657370">look</span> <span m="3657580">at</span> <span m="3657700">the</span>
  <span m="3657820">second</span> <span m="3658300">derivative</span> <span m="3665960">of</span>
  <span m="3666110">this.</span> <span m="3667410">OK,</span> <span m="3667870">so</span>
  <span m="3668270">I'm</span> <span m="3668520">going to move</span> <span m="3668690">this
  down</span> <span m="3668900">a</span> <span m="3668930">little</span> <span m="3669050">bit.</span>
  <span m="3681440">This</span> <span m="3681660">is</span> <span m="3681780">now</span>
  <span m="3681990">going</span> <span m="3682140">to</span> <span m="3682230">look</span>
  <span m="3682470">like</span> <span m="3683130">the</span> <span m="3683280">third</span>
  <span m="3683670">derivative</span> <span m="3684670">when</span> <span m="3684720">I</span>
  <span m="3684840">do</span> <span m="3684960">this</span> <span m="3685110">transformation.</span>
  <span m="3685800">So</span> <span m="3685950">it's</span> <span m="3686070">going</span>
  <span m="3686150">to</span> <span m="3686220">be</span> <span m="3686280">the</span>
  <span m="3686370">third</span> <span m="3686640">derivative</span> <span m="3687120">of</span>
  <span m="3687270">x</span> <span m="3687540">alpha</span> <span m="3693470">with</span>
  <span m="3693620">respect</span> <span m="3693920">to</span> <span m="3694040">mu</span>
  <span m="3694250">bar,</span> <span m="3697810">delta</span> <span m="3698110">bar,</span>
  <span m="3700380">and</span> <span m="3700600">gamma</span> <span m="3700840">bar.</span></p><p><span
  m="3703420">So</span> <span m="3703960">I've</span> <span m="3704260">got</span>
  <span m="3705700">4</span> <span m="3706090">degrees</span> <span m="3706420">of</span>
  <span m="3706480">freedom</span> <span m="3708010">for</span> <span m="3708220">my</span>
  <span m="3708400">alpha.</span> <span m="3712690">And</span> <span m="3712840">this</span>
  <span m="3713020">must</span> <span m="3713260">be</span> <span m="3713470">perfectly</span>
  <span m="3716110">symmetric</span> <span m="3716680">under</span> <span m="3716890">the</span>
  <span m="3717130">any</span> <span m="3717460">interchange</span> <span m="3718750">of</span>
  <span m="3718900">the</span> <span m="3719020">indices</span> <span m="3719560">mu</span>
  <span m="3719770">bar,</span> <span m="3720190">delta</span> <span m="3720520">bar,</span>
  <span m="3721000">and</span> <span m="3721120">gamma</span> <span m="3721360">bar.</span>
  <span m="3722022">OK?</span> <span m="3723710">This</span> <span m="3723830">is</span>
  <span m="3723890">a</span> <span m="3723920">little</span> <span m="3724100">exercise</span>
  <span m="3724590">in</span> <span m="3724670">combinatorics.</span> <span m="3727400">So</span>
  <span m="3727640">the</span> <span m="3727730">number</span> <span m="3730130">of</span>
  <span m="3730190">equivalent</span> <span m="3730580">ways</span> <span m="3730850">of</span>
  <span m="3730940">arranging</span> <span m="3731390">this</span> <span m="3732170">turns</span>
  <span m="3732590">out</span> <span m="3732770">to</span> <span m="3732860">be</span>
  <span m="3733670">n</span> <span m="3734870">times</span> <span m="3735140">m</span>
  <span m="3735290">plus</span> <span m="3735560">1</span> <span m="3737090">times</span>
  <span m="3737390">n plus</span> <span m="3737750">2</span> <span m="3739400">over</span>
  <span m="3741170">3</span> <span m="3741440">factorial.</span> <span m="3742860">And</span>
  <span m="3743270">I'm</span> <span m="3743340">in</span> <span m="3743450">4</span>
  <span m="3743660">dimensions</span> <span m="3744080">for</span> <span m="3744200">n</span>
  <span m="3744320">equals</span> <span m="3744530">4.</span> <span m="3747620">Work</span>
  <span m="3748010">that</span> <span m="3748220">out,</span> <span m="3748790">and</span>
  <span m="3748970">you</span> <span m="3749060">will</span> <span m="3749150">find</span>
  <span m="3749600">that</span> <span m="3749780">you</span> <span m="3750020">have</span>
  <span m="3751100">80</span> <span m="3754180">degrees</span> <span m="3754510">of</span>
  <span m="3754570">freedom.</span></p><p><span m="3762210">So</span> <span m="3762290">what</span>
  <span m="3762410">we</span> <span m="3762500">can</span> <span m="3762650">do</span>
  <span m="3763190">is</span> <span m="3763760">we</span> <span m="3763910">can</span>
  <span m="3764600">always</span> <span m="3765050">find</span> <span m="3765290">a</span>
  <span m="3765320">coordinate</span> <span m="3765650">transformation</span> <span
  m="3766310">that</span> <span m="3766430">makes</span> <span m="3766700">it</span>
  <span m="3766820">flat.</span> <span m="3767780">It</span> <span m="3767870">makes</span>
  <span m="3768140">it</span> <span m="3768340">Lorentzian</span> <span m="3769010">at</span>
  <span m="3769100">point</span> <span m="3769460">p.</span> <span m="3770570">It</span>
  <span m="3770750">is</span> <span m="3771080">flat</span> <span m="3771620">in</span>
  <span m="3771710">that</span> <span m="3771830">region.</span> <span m="3772290">In</span>
  <span m="3772390">other</span> <span m="3772430">words,</span> <span m="3773070">there</span>
  <span m="3773180">is</span> <span m="3773300">no</span> <span m="3773540">first</span>
  <span m="3773900">derivative</span> <span m="3774380">there.</span> <span m="3776470">Sorry.</span>
  <span m="3777020">Flat's</span> <span m="3777290">not</span> <span m="3777430">really</span>
  <span m="3777530">the</span> <span m="3777590">right</span> <span m="3777710">word.</span>
  <span m="3780020">There</span> <span m="3780200">is</span> <span m="3780440">no</span>
  <span m="3780770">slope</span> <span m="3781220">right</span> <span m="3781490">at</span>
  <span m="3782300">that</span> <span m="3782450">point.</span></p><p><span m="3783170">But</span>
  <span m="3783350">we</span> <span m="3783530">cannot</span> <span m="3784190">transfer</span>
  <span m="3784670">away</span> <span m="3785000">the</span> <span m="3785120">second</span>
  <span m="3785450">derivative.</span> <span m="3786430">And</span> <span m="3786500">so</span>
  <span m="3786620">what</span> <span m="3786770">this</span> <span m="3786920">tells</span>
  <span m="3787310">me</span> <span m="3787820">is</span> <span m="3790880">the</span>
  <span m="3790970">coordinate</span> <span m="3791480">freedom</span> <span m="3791840">that</span>
  <span m="3791960">we</span> <span m="3792110">have</span> <span m="3793100">means</span>
  <span m="3793430">that</span> <span m="3793550">we</span> <span m="3793670">can</span>
  <span m="3793910">always</span> <span m="3794450">put</span> <span m="3794750">our</span>
  <span m="3794900">metric</span> <span m="3796070">into</span> <span m="3796280">the</span>
  <span m="3796370">following</span> <span m="3796910">form.</span> <span m="3836470">I'm
  just</span> <span m="3836640">going</span> <span m="3836760">to write</span> <span
  m="3836930">this</span> <span m="3837030">schematically.</span> <span m="3837990">Second</span>
  <span m="3838300">derivative</span> <span m="3838610">to</span> <span m="3838710">the</span>
  <span m="3838830">metric</span> <span m="3842270">and</span> <span m="3842430">sort</span>
  <span m="3842580">of</span> <span m="3842640">the</span> <span m="3842730">quadratic</span>
  <span m="3844260">separation</span> <span m="3845190">in</span> <span m="3845310">spacetime</span>
  <span m="3845820">coordinate.</span></p><p><span m="3869810">So</span> <span m="3870990">a</span>
  <span m="3871470">couple</span> <span m="3871770">things</span> <span m="3872010">about</span>
  <span m="3872250">this</span> <span m="3872400">are</span> <span m="3872460">pretty</span>
  <span m="3872700">interesting.</span> <span m="3875110">So</span> <span m="3875350">this
  is</span> <span m="3875460">basically</span> <span m="3875850">telling</span> <span
  m="3876210">me</span> <span m="3876480">that</span> <span m="3876750">we</span>
  <span m="3876870">can</span> <span m="3876990">make</span> <span m="3877230">it</span>
  <span m="3877320">Lorentz</span> <span m="3877800">only</span> <span m="3878100">up</span>
  <span m="3878220">to</span> <span m="3879360">terms</span> <span m="3879750">that</span>
  <span m="3879840">look,</span> <span m="3880260">essentially,</span> <span m="3880590">like</span>
  <span m="3880740">the</span> <span m="3880830">second</span> <span m="3881160">derivative</span>
  <span m="3881520">of the</span> <span m="3881580">metric.</span> <span m="3882570">Well,</span>
  <span m="3882780">the</span> <span m="3882870">second</span> <span m="3883260">derivative</span>
  <span m="3883630">of</span> <span m="3883710">any</span> <span m="3883890">function</span>
  <span m="3884640">tells</span> <span m="3884820">you</span> <span m="3884880">about</span>
  <span m="3885030">the</span> <span m="3885090">curvature</span> <span m="3885480">of</span>
  <span m="3885570">that</span> <span m="3885720">function.</span> <span m="3886690">So</span>
  <span m="3886800">this</span> <span m="3886950">word</span> <span m="3887190">curvature</span>
  <span m="3887640">is</span> <span m="3887700">going</span> <span m="3887810">to</span>
  <span m="3887880">be</span> <span m="3887940">coming</span> <span m="3888240">up</span>
  <span m="3888420">over</span> <span m="3888690">and</span> <span m="3888810">over</span>
  <span m="3889020">and</span> <span m="3889110">over</span> <span m="3889350">again.</span></p><p><span
  m="3890560">We</span> <span m="3890640">are,</span> <span m="3890790">in</span>
  <span m="3890940">fact,</span> <span m="3891690">because</span> <span m="3892200">this</span>
  <span m="3892310">is</span> <span m="3892390">general</span> <span m="3892890">relativity,</span>
  <span m="3893010">we can't</span> <span m="3893190">do</span> <span m="3893310">everything</span>
  <span m="3893610">simply.</span> <span m="3893940">We're</span> <span m="3894060">going</span>
  <span m="3894170">to</span> <span m="3894240">actually</span> <span m="3894540">find</span>
  <span m="3895110">that</span> <span m="3895260">there</span> <span m="3895440">is</span>
  <span m="3895560">a</span> <span m="3895650">rigorous</span> <span m="3896100">way</span>
  <span m="3896340">to</span> <span m="3896460">define</span> <span m="3896880">a</span>
  <span m="3896940">notion</span> <span m="3897300">of</span> <span m="3897360">curvature</span>
  <span m="3898740">that</span> <span m="3898890">we're</span> <span m="3898980">going</span>
  <span m="3899050">to</span> <span m="3899140">play</span> <span m="3899340">with,</span>
  <span m="3899550">which</span> <span m="3899760">indeed</span> <span m="3900210">looks</span>
  <span m="3900480">like</span> <span m="3901220">two</span> <span m="3901470">derivatives</span>
  <span m="3902370">of</span> <span m="3902490">the</span> <span m="3902550">spacetime</span>
  <span m="3903000">metric.</span> <span m="3904350">And</span> <span m="3904530">we</span>
  <span m="3904670">are</span> <span m="3904740">going</span> <span m="3904950">to</span>
  <span m="3905040">find</span> <span m="3905970">it</span> <span m="3906120">has,</span>
  <span m="3906730">I</span> <span m="3906790">mean,</span> <span m="3906990">it's</span>
  <span m="3907170">actually</span> <span m="3907440">going</span> <span m="3907590">to</span>
  <span m="3907650">end</span> <span m="3907830">up</span> <span m="3907950">looking</span>
  <span m="3908220">like</span> <span m="3908430">a</span> <span m="3909590">4</span>
  <span m="3910020">index</span> <span m="3910470">tensor.</span> <span m="3910960">OK?</span></p><p><span
  m="3911190">So</span> <span m="3911400">it's</span> <span m="3911490">going to be</span>
  <span m="3911580">an</span> <span m="3911700">object</span> <span m="3912240">that's</span>
  <span m="3912450">got</span> <span m="3912660">4</span> <span m="3912930">indices</span>
  <span m="3913350">on</span> <span m="3913500">it.</span> <span m="3914850">Each</span>
  <span m="3915000">of</span> <span m="3915060">those</span> <span m="3915270">indices</span>
  <span m="3916650">goes</span> <span m="3916860">over</span> <span m="3917010">the</span>
  <span m="3917070">4</span> <span m="3917320">spacetime</span> <span m="3918390">coordinates.</span>
  <span m="3919540">And</span> <span m="3919560">so</span> <span m="3919740">naively,</span>
  <span m="3920280">it</span> <span m="3920370">looks</span> <span m="3920550">like</span>
  <span m="3920700">it's</span> <span m="3920820">got</span> <span m="3921870">4</span>
  <span m="3922200">to</span> <span m="3922290">the</span> <span m="3922380">4th</span>
  <span m="3922710">power</span> <span m="3923100">independent</span> <span m="3923550">components.</span>
  <span m="3924840">256.</span></p><p><span m="3927120">It</span> <span m="3927240">has</span>
  <span m="3927420">certain</span> <span m="3927780">symmetries</span> <span m="3928260">we're</span>
  <span m="3928350">going</span> <span m="3928470">to</span> <span m="3928530">see,</span>
  <span m="3928710">though.</span> <span m="3929070">And</span> <span m="3929220">when</span>
  <span m="3929340">you</span> <span m="3929430">take</span> <span m="3929720">into</span>
  <span m="3929850">account</span> <span m="3930150">those</span> <span m="3930330">symmetries</span>
  <span m="3930810">and</span> <span m="3930900">you</span> <span m="3930960">count</span>
  <span m="3931320">up</span> <span m="3931440">how</span> <span m="3931680">many</span>
  <span m="3931920">of</span> <span m="3931980">those</span> <span m="3932730">components</span>
  <span m="3933330">are</span> <span m="3933420">actually</span> <span m="3933720">independent,</span>
  <span m="3935130">any</span> <span m="3935400">guesses</span> <span m="3935820">what</span>
  <span m="3935970">the</span> <span m="3936030">number</span> <span m="3936250">is</span>
  <span m="3936320">going</span> <span m="3936390">to</span> <span m="3936450">turn</span>
  <span m="3936570">out</span> <span m="3936660">to</span> <span m="3936720">be?</span>
  <span m="3937870">20.</span> <span m="3939310">Yes,</span> <span m="3939590">it</span>
  <span m="3939970">exactly</span> <span m="3940480">compensates</span> <span m="3941200">for</span>
  <span m="3941980">the</span> <span m="3942130">number</span> <span m="3942520">that</span>
  <span m="3942640">cannot</span> <span m="3942940">be</span> <span m="3943090">zeroed</span>
  <span m="3943390">out</span> <span m="3943540">by</span> <span m="3943660">this</span>
  <span m="3943800">coordinate</span> <span m="3944080">transformation.</span> <span
  m="3944700">It's</span> <span m="3944800">called</span> <span m="3945010">the</span>
  <span m="3945070">Riemann</span> <span m="3945460">curvature</span> <span m="3945850">tensor,</span>
  <span m="3946690">and</span> <span m="3946810">we</span> <span m="3946930">will</span>
  <span m="3947020">get</span> <span m="3947170">to</span> <span m="3947290">that</span>
  <span m="3947500">fairly--</span> <span m="3948490">actually,</span> <span m="3948730">really,</span>
  <span m="3949270">just</span> <span m="3949450">in</span> <span m="3949540">a</span>
  <span m="3949570">couple</span> <span m="3949810">lectures.</span></p><p><span m="3950810">The</span>
  <span m="3950900">other</span> <span m="3951010">thing</span> <span m="3951220">which</span>
  <span m="3951370">this</span> <span m="3951510">is</span> <span m="3951640">useful</span>
  <span m="3952030">for</span> <span m="3954520">is</span> <span m="3958500">in</span>
  <span m="3958660">all</span> <span m="3958870">of</span> <span m="3958960">my</span>
  <span m="3959140">discussion</span> <span m="3959920">of</span> <span m="3960220">the</span>
  <span m="3960310">equivalence</span> <span m="3960760">principle</span> <span m="3961180">up</span>
  <span m="3961330">to</span> <span m="3961450">now,</span> <span m="3963340">there's</span>
  <span m="3963580">been</span> <span m="3963730">a</span> <span m="3963790">weasel</span>
  <span m="3964180">word</span> <span m="3964690">that</span> <span m="3964870">I
  have</span> <span m="3965230">inserted</span> <span m="3965980">into</span> <span
  m="3966260">much</span> <span m="3966460">of</span> <span m="3966520">the</span>
  <span m="3966580">physics.</span> <span m="3966940">I</span> <span m="3967000">always</span>
  <span m="3967210">said</span> <span m="3967480">over</span> <span m="3968110">sufficiently</span>
  <span m="3968770">small</span> <span m="3969310">regions.</span> <span m="3970320">OK?</span>
  <span m="3970750">I</span> <span m="3970840">say</span> <span m="3971080">that</span>
  <span m="3971620">trajectories</span> <span m="3972070">begin</span> <span m="3972340">to</span>
  <span m="3972490">deviate</span> <span m="3972970">from</span> <span m="3973120">one</span>
  <span m="3973270">another</span> <span m="3973630">when</span> <span m="3973840">they</span>
  <span m="3973990">get</span> <span m="3974470">sufficiently</span> <span m="3974980">far</span>
  <span m="3975280">away</span> <span m="3975490">from</span> <span m="3975640">one</span>
  <span m="3975780">another.</span> <span m="3976540">OK?</span></p><p><span m="3976790">And</span>
  <span m="3976870">you</span> <span m="3976960">should</span> <span m="3977320">be</span>
  <span m="3977785">going,</span> <span m="3978160">what the</span> <span m="3978370">hell
  does</span> <span m="3978400">sufficiently</span> <span m="3978970">small,</span>
  <span m="3979300">sufficiently</span> <span m="3979720">far</span> <span m="3979870">away,</span>
  <span m="3980050">what</span> <span m="3980320">do</span> <span m="3980590">all</span>
  <span m="3980740">these</span> <span m="3980980">things</span> <span m="3981280">mean?</span>
  <span m="3982070">OK?</span> <span m="3982600">And</span> <span m="3982690">the</span>
  <span m="3982780">issue</span> <span m="3983110">is</span> <span m="3983260">you</span>
  <span m="3983350">need</span> <span m="3983500">to</span> <span m="3983560">have</span>
  <span m="3983740">a</span> <span m="3983770">scale.</span> <span m="3984880">Well,</span>
  <span m="3987230">this</span> <span m="3987390">scale</span> <span m="3988060">is</span>
  <span m="3988210">going</span> <span m="3988300">to</span> <span m="3988420">be</span>
  <span m="3988510">set</span> <span m="3988780">by</span> <span m="3989230">the</span>
  <span m="3989320">second</span> <span m="3989650">derivative</span> <span m="3990070">of</span>
  <span m="3990130">the</span> <span m="3990190">metric.</span></p><p><span m="3998730">So</span>
  <span m="3998890">the</span> <span m="3999010">size</span> <span m="3999430">of</span>
  <span m="3999490">the</span> <span m="3999580">region</span> <span m="4001810">over</span>
  <span m="4003750">which</span> <span m="4003990">spacetime</span> <span m="4007080">is</span>
  <span m="4007320">inertial</span> <span m="4007980">in</span> <span m="4008100">this</span>
  <span m="4008220">coordinate</span> <span m="4008550">system,</span> <span m="4009600">in</span>
  <span m="4009750">this</span> <span m="4009870">representation</span> <span m="4021560">is</span>
  <span m="4021700">approximately</span> <span m="4023690">so</span> <span m="4023890">imagine</span>
  <span m="4024310">it's</span> <span m="4024460">1</span> <span m="4024790">over--</span>
  <span m="4024950">we</span> <span m="4025030">can</span> <span m="4025150">think</span>
  <span m="4025690">of</span> <span m="4025810">d2g</span> <span m="4028060">as</span>
  <span m="4028510">being</span> <span m="4029650">1</span> <span m="4029890">over</span>
  <span m="4030160">a</span> <span m="4030250">length</span> <span m="4030520">squared.</span>
  <span m="4031375">So</span> <span m="4031750">1</span> <span m="4031900">over</span>
  <span m="4032020">the</span> <span m="4032080">square</span> <span m="4032380">root</span>
  <span m="4032530">of</span> <span m="4032620">that</span> <span m="4032800">gives</span>
  <span m="4033010">me</span> <span m="4033190">a</span> <span m="4033280">rough</span>
  <span m="4033580">idea</span> <span m="4033970">of</span> <span m="4034180">how</span>
  <span m="4034720">long</span> <span m="4035170">the</span> <span m="4035290">curvature</span>
  <span m="4035650">scale</span> <span m="4036040">associated</span> <span m="4036520">with
  your</span> <span m="4036640">spacetime</span> <span m="4037120">actually</span>
  <span m="4037420">is.</span> <span m="4037730">And</span> <span m="4037830">it</span>
  <span m="4037930">tells</span> <span m="4038110">you</span> <span m="4038710">how</span>
  <span m="4038980">big</span> <span m="4039340">your</span> <span m="4039520">inertial</span>
  <span m="4039820">region</span> <span m="4040180">actually</span> <span m="4040600">is.</span></p><p><span
  m="4045160">So</span> <span m="4045250">we're</span> <span m="4045340">going</span>
  <span m="4045440">to</span> <span m="4045520">make</span> <span m="4045940">this</span>
  <span m="4046150">notion</span> <span m="4046510">of</span> <span m="4046600">curvature</span>
  <span m="4047080">regress</span> <span m="4047530">very,</span> <span m="4047900">very</span>
  <span m="4048010">soon.</span> <span m="4050410">As</span> <span m="4050590">a</span>
  <span m="4050620">prelude</span> <span m="4051040">to</span> <span m="4051160">this,</span>
  <span m="4052060">we</span> <span m="4052180">now</span> <span m="4052420">need</span>
  <span m="4052600">to</span> <span m="4052660">start</span> <span m="4052900">thinking</span>
  <span m="4053200">about</span> <span m="4053500">how</span> <span m="4054040">we</span>
  <span m="4054280">do</span> <span m="4054790">mathematics</span> <span m="4055360">and</span>
  <span m="4055450">physics</span> <span m="4055990">on</span> <span m="4056260">a</span>
  <span m="4056320">curved</span> <span m="4056620">manifold.</span> <span m="4060290">So</span>
  <span m="4061670">I'm</span> <span m="4061820">going</span> <span m="4062000">to</span>
  <span m="4062120">start</span> <span m="4062360">to</span> <span m="4062480">set</span>
  <span m="4062780">up</span> <span m="4063500">some</span> <span m="4063950">of</span>
  <span m="4064310">the</span> <span m="4065720">issues</span> <span m="4066140">that</span>
  <span m="4066260">we</span> <span m="4066380">need</span> <span m="4066530">to</span>
  <span m="4066620">face.</span></p><p><span m="4099430">So</span> <span m="4099590">we're</span>
  <span m="4099710">going</span> <span m="4099830">to need</span> <span m="4099950">to
  define</span> <span m="4100220">what</span> <span m="4100340">I</span> <span m="4100399">mean</span>
  <span m="4100640">by</span> <span m="4100819">a</span> <span m="4100880">manifold</span>
  <span m="4101359">that</span> <span m="4101479">is</span> <span m="4101600">curved.</span>
  <span m="4102439">So</span> <span m="4102680">a</span> <span m="4102740">curved</span>
  <span m="4103069">manifold</span> <span m="4103680">is</span> <span m="4103910">going</span>
  <span m="4104180">to</span> <span m="4104330">simply</span> <span m="4104660">be</span>
  <span m="4104870">one</span> <span m="4105770">in</span> <span m="4105950">which</span>
  <span m="4107899">initially</span> <span m="4108649">parallel</span> <span m="4109370">trajectories</span>
  <span m="4110090">do</span> <span m="4110270">not</span> <span m="4110479">remain</span>
  <span m="4111620">parallel.</span> <span m="4140830">So</span> <span m="4141010">an</span>
  <span m="4141100">example</span> <span m="4141910">is</span> <span m="4142130">the</span>
  <span m="4142180">surface</span> <span m="4142479">of</span> <span m="4142540">a</span>
  <span m="4142600">sphere,</span> <span m="4143090">as</span> <span m="4143220">I</span>
  <span m="4143560">illustrated.</span> <span m="4144819">You</span> <span m="4145000">start</span>
  <span m="4145330">somewhere</span> <span m="4145660">on</span> <span m="4145779">the</span>
  <span m="4145870">equator</span> <span m="4146260">in</span> <span m="4146350">Brazil.</span>
  <span m="4147189">Your</span> <span m="4147279">friend</span> <span m="4147550">starts</span>
  <span m="4147850">somewhere</span> <span m="4148090">on</span> <span m="4148180">the</span>
  <span m="4148270">equator</span> <span m="4148990">in</span> <span m="4149350">Africa.</span>
  <span m="4150170">The</span> <span m="4150260">two</span> <span m="4150500">of</span>
  <span m="4150609">you</span> <span m="4150760">start</span> <span m="4151450">walking</span>
  <span m="4151840">north.</span> <span m="4152290">You</span> <span m="4152470">are</span>
  <span m="4152590">exactly</span> <span m="4153220">parallel</span> <span m="4153729">when</span>
  <span m="4153850">you</span> <span m="4153910">take</span> <span m="4154120">that</span>
  <span m="4154240">first</span> <span m="4154510">step</span> <span m="4154779">of</span>
  <span m="4155020">the</span> <span m="4155109">equator.</span> <span m="4155920">But</span>
  <span m="4156100">your</span> <span m="4156189">trajectories</span> <span m="4156609">cross</span>
  <span m="4156970">at</span> <span m="4157029">the</span> <span m="4157090">North</span>
  <span m="4157300">Pole.</span></p><p><span m="4165600">Interestingly,</span> <span
  m="4166420">an</span> <span m="4166439">example</span> <span m="4166890">that</span>
  <span m="4167069">looks</span> <span m="4167370">curved</span> <span m="4167790">but</span>
  <span m="4167970">is</span> <span m="4168120">not,</span> <span m="4171810">the</span>
  <span m="4171899">surface</span> <span m="4172319">of</span> <span m="4172410">a</span>
  <span m="4172470">cylinder.</span> <span m="4180858">OK?</span> <span m="4181359">If</span>
  <span m="4181450">I</span> <span m="4181569">take</span> <span m="4182290">two</span>
  <span m="4182560">lines,</span> <span m="4183180">again,</span> <span m="4183410">I</span>
  <span m="4183490">need to</span> <span m="4183670">imagine</span> <span m="4184060">that</span>
  <span m="4184180">this</span> <span m="4184630">region</span> <span m="4184960">continues</span>
  <span m="4185350">all</span> <span m="4185439">the</span> <span m="4185529">way</span>
  <span m="4185649">up</span> <span m="4185770">here.</span> <span m="4186340">I</span>
  <span m="4186430">make</span> <span m="4186609">two</span> <span m="4186790">lines</span>
  <span m="4187149">that</span> <span m="4187270">are</span> <span m="4187330">parallel</span>
  <span m="4187720">to</span> <span m="4187840">each</span> <span m="4188020">other</span>
  <span m="4188229">here</span> <span m="4188470">and</span> <span m="4188590">I</span>
  <span m="4188689">have</span> <span m="4188950">them</span> <span m="4189340">extend</span>
  <span m="4189700">around</span> <span m="4190029">this</span> <span m="4190210">thing,</span>
  <span m="4190840">they</span> <span m="4190960">would</span> <span m="4191080">remain</span>
  <span m="4191380">parallel</span> <span m="4191859">the</span> <span m="4191979">entire</span>
  <span m="4192370">way</span> <span m="4192609">out,</span> <span m="4193069">OK?</span>
  <span m="4193899">Another</span> <span m="4194200">way</span> <span m="4194350">of</span>
  <span m="4194410">stating</span> <span m="4194740">that</span> <span m="4195010">is</span>
  <span m="4195190">that</span> <span m="4195400">you</span> <span m="4195520">can</span>
  <span m="4195700">always</span> <span m="4196150">take</span> <span m="4196360">a</span>
  <span m="4196420">cylinder</span> <span m="4197590">and,</span> <span m="4198370">with</span>
  <span m="4198610">an</span> <span m="4198700">appropriate</span> <span m="4199180">cut,</span>
  <span m="4200500">but</span> <span m="4200770">without</span> <span m="4201310">tearing</span>
  <span m="4201760">it,</span> <span m="4202480">you</span> <span m="4202570">can</span>
  <span m="4202720">flatten</span> <span m="4203050">it</span> <span m="4203140">out</span>
  <span m="4203350">and</span> <span m="4203440">make</span> <span m="4203620">it</span>
  <span m="4203710">into</span> <span m="4204070">a</span> <span m="4204340">simple</span>
  <span m="4204880">sheet,</span> <span m="4205540">a</span> <span m="4205600">perfectly</span>
  <span m="4206560">flat</span> <span m="4206890">sheet.</span> <span m="4207760">You</span>
  <span m="4207880">cannot</span> <span m="4208210">do</span> <span m="4208360">that</span>
  <span m="4208480">with</span> <span m="4208600">a</span> <span m="4208630">sphere</span>
  <span m="4208900">without</span> <span m="4209170">tearing</span> <span m="4209500">it</span>
  <span m="4209560">in</span> <span m="4209620">some</span> <span m="4209830">places.</span></p><p><span
  m="4214040">So</span> <span m="4214270">what</span> <span m="4214480">is</span>
  <span m="4214600">going</span> <span m="4214840">to</span> <span m="4214960">begin</span>
  <span m="4215620">to</span> <span m="4215770">complicate</span> <span m="4216430">things</span>
  <span m="4220510">is</span> <span m="4220990">that</span> <span m="4221620">we</span>
  <span m="4221860">want</span> <span m="4222130">to</span> <span m="4222280">work</span>
  <span m="4222580">with</span> <span m="4222940">vectors</span> <span m="4223510">and</span>
  <span m="4223600">tensors</span> <span m="4224680">that</span> <span m="4224890">live</span>
  <span m="4225640">in</span> <span m="4225880">this</span> <span m="4226090">curved</span>
  <span m="4226540">manifold.</span> <span m="4239170">We</span> <span m="4239350">haven't</span>
  <span m="4239620">really</span> <span m="4239830">thought</span> <span m="4240100">too</span>
  <span m="4240280">carefully</span> <span m="4240700">yet</span> <span m="4241420">about</span>
  <span m="4241780">the</span> <span m="4242290">space.</span> <span m="4243210">And</span>
  <span m="4243280">let's</span> <span m="4243580">just</span> <span m="4243700">focus</span>
  <span m="4244000">on</span> <span m="4244120">vectors</span> <span m="4244480">for</span>
  <span m="4244570">now.</span> <span m="4245230">We</span> <span m="4245310">haven't</span>
  <span m="4245470">thought</span> <span m="4245680">too</span> <span m="4245830">carefully</span>
  <span m="4246310">about</span> <span m="4246580">the</span> <span m="4246670">space</span>
  <span m="4247180">in</span> <span m="4247330">which</span> <span m="4247630">the</span>
  <span m="4247750">vectors</span> <span m="4248230">actually</span> <span m="4248650">live.</span></p><p><span
  m="4249640">So</span> <span m="4249790">implicit</span> <span m="4250240">to</span>
  <span m="4250480">everything</span> <span m="4250870">we</span> <span m="4250990">have</span>
  <span m="4251140">talked</span> <span m="4251440">about</span> <span m="4251700">up</span>
  <span m="4251800">until</span> <span m="4252010">now</span> <span m="4258920">is</span>
  <span m="4259010">that</span> <span m="4259470">we</span> <span m="4259590">often</span>
  <span m="4260070">regard</span> <span m="4260760">vectors</span> <span m="4262530">as</span>
  <span m="4262770">objects</span> <span m="4263250">that</span> <span m="4263340">themselves</span>
  <span m="4263850">reside</span> <span m="4265410">in</span> <span m="4265590">a</span>
  <span m="4266760">tangent</span> <span m="4267300">space.</span> <span m="4271580">OK,
  if</span> <span m="4271670">I'm</span> <span m="4271820">working</span> <span m="4272120">in</span>
  <span m="4272210">a</span> <span m="4272270">manifold</span> <span m="4272760">that</span>
  <span m="4272820">is</span> <span m="4272960">flat,</span> <span m="4273500">say</span>
  <span m="4273780">it's</span> <span m="4273950">the</span> <span m="4274040">surface</span>
  <span m="4274370">of</span> <span m="4274430">this</span> <span m="4274580">board,</span>
  <span m="4274875">OK,</span> <span m="4275170">and</span> <span m="4275200">just</span>
  <span m="4275330">two</span> <span m="4275480">dimensions,</span> <span m="4277850">every</span>
  <span m="4278180">point</span> <span m="4278480">on</span> <span m="4278570">this</span>
  <span m="4278690">board</span> <span m="4279050">has</span> <span m="4279260">the</span>
  <span m="4279350">same</span> <span m="4279650">tangent,</span> <span m="4280300">all</span>
  <span m="4280350">right?</span> <span m="4280580">So</span> <span m="4280790">if</span>
  <span m="4280940">I</span> <span m="4281180">draw</span> <span m="4281480">a</span>
  <span m="4281570">vector</span> <span m="4281990">here</span> <span m="4283050">and</span>
  <span m="4283340">I</span> <span m="4283430">draw</span> <span m="4283640">another</span>
  <span m="4283880">vector</span> <span m="4284240">over</span> <span m="4284510">here,</span>
  <span m="4285450">it's</span> <span m="4285470">really</span> <span m="4285650">easy</span>
  <span m="4285920">for</span> <span m="4286010">me</span> <span m="4286100">to</span>
  <span m="4286190">compare</span> <span m="4286550">them</span> <span m="4286700">because</span>
  <span m="4286850">they</span> <span m="4286910">actually</span> <span m="4287180">live</span>
  <span m="4287540">in</span> <span m="4287630">the</span> <span m="4287720">same</span>
  <span m="4288080">space</span> <span m="4288770">that</span> <span m="4288890">is</span>
  <span m="4289010">tangent</span> <span m="4289490">to</span> <span m="4289610">this</span>
  <span m="4289790">board.</span></p><p><span m="4291410">If</span> <span m="4291560">I'm</span>
  <span m="4291770">on</span> <span m="4291890">the</span> <span m="4291980">surface</span>
  <span m="4292370">of</span> <span m="4292460">a</span> <span m="4292520">sphere,</span>
  <span m="4294410">points</span> <span m="4294830">that</span> <span m="4294950">are</span>
  <span m="4295040">tangent</span> <span m="4295610">to</span> <span m="4295700">the</span>
  <span m="4295790">sphere</span> <span m="4296180">at</span> <span m="4296240">the</span>
  <span m="4296330">North</span> <span m="4296600">Pole</span> <span m="4297110">are</span>
  <span m="4297230">very</span> <span m="4297530">different</span> <span m="4298010">from</span>
  <span m="4298280">points</span> <span m="4298610">that</span> <span m="4298730">are</span>
  <span m="4298790">tangent</span> <span m="4299240">to</span> <span m="4299330">the</span>
  <span m="4299420">sphere</span> <span m="4299780">on</span> <span m="4299930">the</span>
  <span m="4300050">equator.</span> <span m="4301800">So</span> <span m="4301850">it</span>
  <span m="4301910">becomes</span> <span m="4302210">difficult</span> <span m="4302600">for</span>
  <span m="4302690">me</span> <span m="4302780">to</span> <span m="4302870">actually</span>
  <span m="4303170">compare</span> <span m="4304250">fields</span> <span m="4304910">when</span>
  <span m="4305060">they</span> <span m="4305170">are</span> <span m="4305270">defined</span>
  <span m="4305750">on</span> <span m="4305870">a</span> <span m="4305900">curved</span>
  <span m="4306200">surface</span> <span m="4306560">like</span> <span m="4306710">this.</span>
  <span m="4343670">So</span> <span m="4344920">this</span> <span m="4345070">makes</span>
  <span m="4345280">it</span> <span m="4345340">a</span> <span m="4345370">little</span>
  <span m="4345550">bit--</span> <span m="4345780">and</span> <span m="4345880">so</span>
  <span m="4345980">I'm</span> <span m="4346080">just</span> <span m="4346180">going</span>
  <span m="4346280">to</span> <span m="4346380">set</span> <span m="4346480">up</span>
  <span m="4346570">this</span> <span m="4346720">problem,</span> <span m="4347230">and</span>
  <span m="4347650">I</span> <span m="4347830">will</span> <span m="4348310">sketch</span>
  <span m="4349030">the</span> <span m="4349210">issue.</span> <span m="4349630">And</span>
  <span m="4349720">then</span> <span m="4349870">we</span> <span m="4349960">will</span>
  <span m="4350080">resolve</span> <span m="4350710">it</span> <span m="4351010">in</span>
  <span m="4351310">our</span> <span m="4351610">lecture</span> <span m="4352060">on</span>
  <span m="4352270">Tuesday.</span></p><p><span m="4353320">This</span> <span m="4353440">makes</span>
  <span m="4353620">it</span> <span m="4353680">a</span> <span m="4353710">little</span>
  <span m="4353860">bit</span> <span m="4353980">complicated</span> <span m="4354520">for</span>
  <span m="4354640">me</span> <span m="4354730">to</span> <span m="4354820">take</span>
  <span m="4355090">derivatives</span> <span m="4355600">of</span> <span m="4355690">things</span>
  <span m="4355900">like</span> <span m="4356050">vectors</span> <span m="4357370">when</span>
  <span m="4357590">I'm</span> <span m="4358840">working</span> <span m="4359170">in</span>
  <span m="4359260">a</span> <span m="4359320">curved</span> <span m="4359620">manifold.</span>
  <span m="4360700">So</span> <span m="4360970">let's</span> <span m="4361150">consider</span>
  <span m="4361570">the</span> <span m="4361660">following</span> <span m="4362140">situation.</span>
  <span m="4367250">So</span> <span m="4367420">I'm</span> <span m="4367540">going</span>
  <span m="4367660">to</span> <span m="4367780">define</span> <span m="4368170">some</span>
  <span m="4368380">curve,</span> <span m="4369280">which</span> <span m="4369430">I</span>
  <span m="4369520">would</span> <span m="4369640">just</span> <span m="4369760">call</span>
  <span m="4370090">gamma.</span> <span m="4372970">It</span> <span m="4373780">lives</span>
  <span m="4374050">in</span> <span m="4374140">a</span> <span m="4374200">curved</span>
  <span m="4374530">space</span> <span m="4374830">of</span> <span m="4374920">some</span>
  <span m="4375150">sort.</span></p><p><span m="4379920">I'm</span> <span m="4379980">going</span>
  <span m="4380100">to</span> <span m="4380160">draw</span> <span m="4380460">it</span>
  <span m="4380550">here</span> <span m="4380760">on</span> <span m="4380850">the</span>
  <span m="4380940">board.</span> <span m="4381990">But</span> <span m="4382110">imagine</span>
  <span m="4382590">that</span> <span m="4382710">this</span> <span m="4382920">is</span>
  <span m="4383280">on</span> <span m="4383490">the</span> <span m="4383580">surface</span>
  <span m="4384000">of</span> <span m="4384060">a</span> <span m="4384120">sphere.</span>
  <span m="4386200">OK?</span> <span m="4387490">So</span> <span m="4387620">here's</span>
  <span m="4388700">the</span> <span m="4388790">curve</span> <span m="4389030">gamma.</span>
  <span m="4390686">And</span> <span m="4391140">let's</span> <span m="4391350">say</span>
  <span m="4393780">this</span> <span m="4393960">point</span> <span m="4394290">p</span>
  <span m="4394620">here</span> <span m="4396060">has</span> <span m="4396240">coordinates</span>
  <span m="4396720">x</span> <span m="4396990">alpha.</span> <span m="4399690">And</span>
  <span m="4399860">this</span> <span m="4400280">point</span> <span m="4400550">q</span>
  <span m="4400850">here</span> <span m="4401780">has</span> <span m="4401990">coordinates</span>
  <span m="4404060">x</span> <span m="4404300">alpha</span> <span m="4404800">plus</span>
  <span m="4404910">dx</span> <span m="4405440">alpha.</span></p><p><span m="4407940">Suppose</span>
  <span m="4408300">there's</span> <span m="4408410">some</span> <span m="4408650">vector</span>
  <span m="4408950">field</span> <span m="4409250">that</span> <span m="4409370">fills</span>
  <span m="4410330">all</span> <span m="4410600">this</span> <span m="4410750">manifold.</span>
  <span m="4411630">OK?</span> <span m="4412830">And</span> <span m="4412880">so</span>
  <span m="4413120">let's</span> <span m="4413190">say</span> <span m="4413390">the</span>
  <span m="4413480">vector</span> <span m="4413790">a</span> <span m="4417730">looks</span>
  <span m="4417910">like</span> <span m="4418180">this</span> <span m="4419200">here</span>
  <span m="4419440">at</span> <span m="4419530">the</span> <span m="4419620">point</span>
  <span m="4419890">p.</span> <span m="4421858">And</span> <span m="4422260">it</span>
  <span m="4422320">looks</span> <span m="4422530">like</span> <span m="4422710">this</span>
  <span m="4423010">here</span> <span m="4425050">at</span> <span m="4425140">the</span>
  <span m="4425200">point</span> <span m="4425480">q.</span></p><p><span m="4428140">How</span>
  <span m="4428290">do</span> <span m="4428440">I</span> <span m="4428500">take</span>
  <span m="4428740">the</span> <span m="4428830">derivative</span> <span m="4429090">of</span>
  <span m="4429350">the</span> <span m="4429450">vector</span> <span m="4429640">field</span>
  <span m="4430480">as</span> <span m="4430630">I</span> <span m="4430720">go</span>
  <span m="4430930">from</span> <span m="4431110">point</span> <span m="4431350">p</span>
  <span m="4431500">to</span> <span m="4431590">point</span> <span m="4431830">q?</span>
  <span m="4451350">Well,</span> <span m="4457910">your</span> <span m="4458030">first</span>
  <span m="4458330">guess</span> <span m="4458650">should</span> <span m="4458750">basically</span>
  <span m="4459140">just</span> <span m="4459320">be</span> <span m="4460300">do</span>
  <span m="4460490">what</span> <span m="4461020">you</span> <span m="4461090">always</span>
  <span m="4461450">do</span> <span m="4461660">when</span> <span m="4461810">you</span>
  <span m="4461900">first</span> <span m="4462170">learn</span> <span m="4462350">how</span>
  <span m="4462440">to</span> <span m="4462500">take</span> <span m="4462680">a</span>
  <span m="4462710">derivative.</span> <span m="4510280">OK?</span> <span m="4511360">So</span>
  <span m="4511410">that</span> <span m="4511620">would</span> <span m="4511860">be</span>
  <span m="4512100">a</span> <span m="4512310">notion</span> <span m="4512760">of</span>
  <span m="4512850">a</span> <span m="4512880">derivative.</span> <span m="4514380">There's</span>
  <span m="4514590">nothing</span> <span m="4515100">mathematically</span> <span m="4515850">wrong</span>
  <span m="4516090">with</span> <span m="4516240">that.</span> <span m="4516845">OK?</span></p><p><span
  m="4517240">But</span> <span m="4517440">we're</span> <span m="4517590">going</span>
  <span m="4517710">to</span> <span m="4517770">find</span> <span m="4518130">that</span>
  <span m="4518250">it</span> <span m="4518340">gives</span> <span m="4518580">us</span>
  <span m="4518700">problems</span> <span m="4519660">for</span> <span m="4519810">the</span>
  <span m="4519930">same</span> <span m="4520350">reason</span> <span m="4521280">that</span>
  <span m="4521520">we</span> <span m="4521670">ran</span> <span m="4521910">into</span>
  <span m="4522060">problems</span> <span m="4522600">when</span> <span m="4522690">we</span>
  <span m="4522780">began</span> <span m="4523140">working</span> <span m="4523590">with</span>
  <span m="4524280">vector</span> <span m="4524610">spaces</span> <span m="4524900">and</span>
  <span m="4525120">curvilinear</span> <span m="4525660">coordinates.</span> <span
  m="4526270">OK?</span> <span m="4527520">If</span> <span m="4527700">I</span> <span
  m="4527910">want</span> <span m="4528210">this</span> <span m="4528480">to</span>
  <span m="4528600">be</span> <span m="4529440">a</span> <span m="4529560">tensorial</span>
  <span m="4530340">object</span> <span m="4530850">in</span> <span m="4531000">the</span>
  <span m="4531120">same</span> <span m="4531450">way</span> <span m="4531660">that</span>
  <span m="4531810">we</span> <span m="4531960">have</span> <span m="4532050">been</span>
  <span m="4532170">defining</span> <span m="4532750">tensors</span> <span m="4533460">all</span>
  <span m="4533640">along</span> <span m="4533970">here,</span> <span m="4534180">I'm</span>
  <span m="4534260">going</span> <span m="4534330">to</span> <span m="4534420">run</span>
  <span m="4534570">into</span> <span m="4534750">problems.</span> <span m="4535210">So</span>
  <span m="4535230">let me</span> <span m="4535320">just</span> <span m="4535500">actually</span>
  <span m="4536310">demonstrate</span> <span m="4536760">what</span> <span m="4536880">happens</span>
  <span m="4537240">if</span> <span m="4537720">I</span> <span m="4537810">try</span>
  <span m="4538140">to</span> <span m="4538230">do</span> <span m="4538440">this.</span></p><p><span
  m="4540300">So</span> <span m="4540420">the</span> <span m="4540480">key</span>
  <span m="4540720">bit,</span> <span m="4541260">the</span> <span m="4541320">way</span>
  <span m="4541470">we</span> <span m="4541560">want</span> <span m="4541710">to</span>
  <span m="4541770">think</span> <span m="4541950">about</span> <span m="4542220">it</span>
  <span m="4542310">is</span> <span m="4542480">that</span> <span m="4542550">the</span>
  <span m="4542610">points</span> <span m="4542910">p</span> <span m="4543180">and</span>
  <span m="4543270">q</span> <span m="4544470">don't</span> <span m="4544740">have</span>
  <span m="4545010">the</span> <span m="4545070">same</span> <span m="4545340">tangent</span>
  <span m="4545790">space,</span> <span m="4555320">which</span> <span m="4555470">is</span>
  <span m="4555530">a</span> <span m="4555560">fancy</span> <span m="4555950">way</span>
  <span m="4556100">of</span> <span m="4556160">saying</span> <span m="4556640">that,</span>
  <span m="4556850">as</span> <span m="4557030">I</span> <span m="4557120">move</span>
  <span m="4557480">from</span> <span m="4557780">point</span> <span m="4558050">p</span>
  <span m="4558260">to</span> <span m="4558320">point</span> <span m="4558620">q,</span>
  <span m="4559310">the</span> <span m="4559400">basis</span> <span m="4559790">vectors</span>
  <span m="4560390">are</span> <span m="4560510">moving.</span> <span m="4561260">They're</span>
  <span m="4561500">starting</span> <span m="4561710">to</span> <span m="4561770">point</span>
  <span m="4562040">in</span> <span m="4562100">different</span> <span m="4562340">directions.</span>
  <span m="4577870">So</span> <span m="4578460">if</span> <span m="4578700">this</span>
  <span m="4578940">were</span> <span m="4579210">to</span> <span m="4579360">be--</span>
  <span m="4579870">like</span> <span m="4580050">I</span> <span m="4580110">said,</span>
  <span m="4580350">mathematically,</span> <span m="4581070">if</span> <span m="4581160">you</span>
  <span m="4581250">just</span> <span m="4581400">want</span> <span m="4581760">to</span>
  <span m="4581940">get</span> <span m="4582270">that</span> <span m="4582420">derivative,</span>
  <span m="4582840">that</span> <span m="4583050">is</span> <span m="4583350">a</span>
  <span m="4583440">quantity</span> <span m="4584100">which</span> <span m="4584310">has</span>
  <span m="4584730">a</span> <span m="4584820">mathematical</span> <span m="4585420">meaning,</span>
  <span m="4585810">OK?</span> <span m="4586810">But</span> <span m="4587060">it's</span>
  <span m="4587250">not</span> <span m="4587550">the</span> <span m="4587640">component</span>
  <span m="4588240">of</span> <span m="4588330">a</span> <span m="4588390">tensor,</span>
  <span m="4588960">which</span> <span m="4589140">we</span> <span m="4589300">have</span>
  <span m="4589380">called</span> <span m="4589700">out</span> <span m="4589890">as</span>
  <span m="4590010">having</span> <span m="4590250">a</span> <span m="4590310">particularly</span>
  <span m="4590730">important</span> <span m="4591210">meaning</span> <span m="4591990">in</span>
  <span m="4592140">this</span> <span m="4592230">geometric</span> <span m="4592650">construction</span>
  <span m="4593100">of</span> <span m="4593160">physics</span> <span m="4593490">that</span>
  <span m="4593580">we</span> <span m="4593670">are</span> <span m="4593730">doing.</span></p><p><span
  m="4594840">And</span> <span m="4594960">so</span> <span m="4596100">if</span> <span
  m="4596400">this</span> <span m="4596610">were</span> <span m="4596820">to</span>
  <span m="4596940">be</span> <span m="4597680">tensorial,</span> <span m="4598300">then</span>
  <span m="4598590">I</span> <span m="4598650">should</span> <span m="4598800">be</span>
  <span m="4598920">able</span> <span m="4599010">to</span> <span m="4599070">switch</span>
  <span m="4599340">to</span> <span m="4599460">new</span> <span m="4599670">coordinates,</span>
  <span m="4600180">which</span> <span m="4600280">I'll</span> <span m="4600330">designate</span>
  <span m="4600720">with</span> <span m="4600840">primes,</span> <span m="4603210">such</span>
  <span m="4603570">that</span> <span m="4615760">the</span> <span m="4615830">following</span>
  <span m="4616550">was</span> <span m="4616730">true.</span> <span m="4624390">The</span>
  <span m="4624490">reason</span> <span m="4624630">why</span> <span m="4624810">this</span>
  <span m="4624990">doesn't</span> <span m="4625290">actually</span> <span m="4625590">work</span>
  <span m="4628050">is</span> <span m="4628530">I'm</span> <span m="4628650">going</span>
  <span m="4628770">to</span> <span m="4628830">demand</span> <span m="4629280">that</span>
  <span m="4629430">alpha--</span> <span m="4630000">excuse</span> <span m="4630180">me--</span>
  <span m="4630330">that</span> <span m="4630540">a</span> <span m="4631350">is,</span>
  <span m="4631650">in</span> <span m="4631740">fact,</span> <span m="4632100">actually</span>
  <span m="4632520">already</span> <span m="4632880">tensorial.</span> <span m="4633550">OK?</span>
  <span m="4633830">It's</span> <span m="4633990">the</span> <span m="4634050">compound</span>
  <span m="4634410">of</span> <span m="4634480">a</span> <span m="4634520">vector,</span>
  <span m="4634960">which</span> <span m="4635040">is</span> <span m="4635160">a</span>
  <span m="4635700">particular</span> <span m="4636090">kind</span> <span m="4636300">of</span>
  <span m="4636390">tensor.</span></p><p><span m="4643400">So</span> <span m="4643570">I'm</span>
  <span m="4643660">going</span> <span m="4643740">to</span> <span m="4643840">demand</span>
  <span m="4649490">that</span> <span m="4649610">the</span> <span m="4649670">following</span>
  <span m="4650120">be</span> <span m="4650240">true.</span> <span m="4653470">And</span>
  <span m="4653700">I'm</span> <span m="4653760">going</span> <span m="4653820">to</span>
  <span m="4653880">demand</span> <span m="4654330">that</span> <span m="4654510">my</span>
  <span m="4655740">derivatives,</span> <span m="4660760">they</span> <span m="4660920">are</span>
  <span m="4661100">just</span> <span m="4661620">derivatives.</span> <span m="4661970">They</span>
  <span m="4662180">do the</span> <span m="4662270">usual</span> <span m="4662660">rule</span>
  <span m="4663500">Jacobian</span> <span m="4663980">rule</span> <span m="4664190">when</span>
  <span m="4664340">I</span> <span m="4664850">switch</span> <span m="4665120">coordinate</span>
  <span m="4665480">systems.</span> <span m="4667310">And</span> <span m="4667490">so</span>
  <span m="4667850">skipping</span> <span m="4668330">a</span> <span m="4668390">line</span>
  <span m="4668660">of</span> <span m="4668750">algebra,</span> <span m="4669450">which</span>
  <span m="4669710">you</span> <span m="4669800">can</span> <span m="4669950">get</span>
  <span m="4670100">in</span> <span m="4670190">my</span> <span m="4670310">notes,</span>
  <span m="4670640">this</span> <span m="4670760">is</span> <span m="4670850">actually</span>
  <span m="4671150">very</span> <span m="4671330">similar</span> <span m="4671640">to
  the</span> <span m="4671720">notes</span> <span m="4671990">I've</span> <span m="4672140">already</span>
  <span m="4672410">posted.</span> <span m="4673520">When</span> <span m="4673670">you</span>
  <span m="4673760">work</span> <span m="4673940">this</span> <span m="4674150">out,</span>
  <span m="4674610">you're</span> <span m="4674630">going</span> <span m="4674720">to</span>
  <span m="4674810">find</span> <span m="4688440">you</span> <span m="4688530">get</span>
  <span m="4688650">one</span> <span m="4688980">term</span> <span m="4689280">that's</span>
  <span m="4689460">correct,</span> <span m="4695280">but</span> <span m="4695400">you</span>
  <span m="4695460">get</span> <span m="4695580">another</span> <span m="4695880">term</span>
  <span m="4696180">that</span> <span m="4696330">involves</span> <span m="4698790">a</span>
  <span m="4698880">derivative</span> <span m="4699600">of</span> <span m="4699720">your</span>
  <span m="4699810">coordinate</span> <span m="4700150">transformation</span> <span
  m="4700770">matrix.</span></p><p><span m="4706220">And</span> <span m="4706320">this
  is</span> <span m="4706390">an actual</span> <span m="4706630">term,</span> <span
  m="4707050">spoils</span> <span m="4707710">the</span> <span m="4707800">tensorialness</span>
  <span m="4709480">of</span> <span m="4709570">this</span> <span m="4709720">quantity.</span>
  <span m="4714100">The</span> <span m="4714190">way</span> <span m="4714460">we</span>
  <span m="4714610">are</span> <span m="4714670">going</span> <span m="4714970">to</span>
  <span m="4715060">cure</span> <span m="4715390">this</span> <span m="4719990">is</span>
  <span m="4720320">we</span> <span m="4720510">are</span> <span m="4720620">going</span>
  <span m="4720860">to</span> <span m="4720950">demand</span> <span m="4722000">that</span>
  <span m="4722780">if</span> <span m="4722990">we</span> <span m="4723200">want</span>
  <span m="4724500">our</span> <span m="4724700">derivatives</span> <span m="4725930">to</span>
  <span m="4726080">be</span> <span m="4726350">derivatives</span> <span m="4727130">that</span>
  <span m="4728420">comport</span> <span m="4728930">with</span> <span m="4729080">a</span>
  <span m="4729140">notion</span> <span m="4729650">of</span> <span m="4729800">taking</span>
  <span m="4730160">tensor</span> <span m="4730580">objects</span> <span m="4731420">and</span>
  <span m="4731570">getting</span> <span m="4731900">other</span> <span m="4732170">tensor</span>
  <span m="4732650">objects</span> <span m="4733130">out</span> <span m="4733400">of</span>
  <span m="4733460">them,</span> <span m="4734480">before</span> <span m="4734810">we</span>
  <span m="4734930">take</span> <span m="4735110">the</span> <span m="4735200">derivative,</span>
  <span m="4735840">we</span> <span m="4735920">have</span> <span m="4736130">to</span>
  <span m="4736250">have</span> <span m="4736370">some</span> <span m="4736580">way</span>
  <span m="4736820">of</span> <span m="4736940">transporting</span> <span m="4738530">the</span>
  <span m="4738680">objects</span> <span m="4739190">to</span> <span m="4739280">the</span>
  <span m="4739370">same</span> <span m="4739760">location</span> <span m="4740330">in</span>
  <span m="4740390">the</span> <span m="4740480">manifold,</span> <span m="4741020">where</span>
  <span m="4741230">I</span> <span m="4741350">can</span> <span m="4741620">then</span>
  <span m="4742160">compare</span> <span m="4742640">them.</span></p><p><span m="4774190">So</span>
  <span m="4776850">here's</span> <span m="4777090">one</span> <span m="4777510">example</span>
  <span m="4778260">of</span> <span m="4778380">a</span> <span m="4778440">notion</span>
  <span m="4778770">of</span> <span m="4778830">transport</span> <span m="4779400">that</span>
  <span m="4779520">we</span> <span m="4779670">could</span> <span m="4779820">use.</span>
  <span m="4785920">So</span> <span m="4786000">here's</span> <span m="4786840">a</span>
  <span m="4787560">at</span> <span m="4787920">point</span> <span m="4788250">q.</span>
  <span m="4788920">There's</span> <span m="4789240">a</span> <span m="4789720">at</span>
  <span m="4789900">point</span> <span m="4790230">p.</span> <span m="4791490">Notion</span>
  <span m="4791940">one</span> <span m="4792180">that</span> <span m="4792300">we'll</span>
  <span m="4792450">talk</span> <span m="4792750">about</span> <span m="4793110">is</span>
  <span m="4793320">known</span> <span m="4793620">as</span> <span m="4794160">parallel</span>
  <span m="4794610">transport.</span></p><p><span m="4803750">What</span> <span m="4804290">that's</span>
  <span m="4804500">essentially</span> <span m="4804860">going</span> <span m="4805010">to</span>
  <span m="4805070">mean</span> <span m="4805490">is</span> <span m="4805880">I'm</span>
  <span m="4805970">going</span> <span m="4806080">to</span> <span m="4806180">say,</span>
  <span m="4806550">well,</span> <span m="4806790">let's</span> <span m="4806870">take</span>
  <span m="4807110">one</span> <span m="4807350">of</span> <span m="4807440">these</span>
  <span m="4807650">guys,</span> <span m="4808550">either</span> <span m="4808760">q</span>
  <span m="4809090">or</span> <span m="4809180">p.</span> <span m="4809465">The</span>
  <span m="4809750">way it's</span> <span m="4809990">drawn</span> <span m="4810290">in</span>
  <span m="4810350">my</span> <span m="4810500">notes,</span> <span m="4810860">I've</span>
  <span m="4811010">used</span> <span m="4811280">q.</span> <span m="4811490">But</span>
  <span m="4811610">it</span> <span m="4811670">could</span> <span m="4811760">be</span>
  <span m="4811910">either.</span> <span m="4812810">And</span> <span m="4813140">let's</span>
  <span m="4813350">imagine</span> <span m="4813800">I</span> <span m="4814100">slide</span>
  <span m="4814520">it</span> <span m="4814610">parallel</span> <span m="4815090">to</span>
  <span m="4815240">itself</span> <span m="4830650">until</span> <span m="4835480">this</span>
  <span m="4835750">gives</span> <span m="4836050">me</span> <span m="4837670">a</span>
  <span m="4837910">alpha</span> <span m="4838630">from</span> <span m="4838870">q</span>
  <span m="4840400">transported</span> <span m="4840970">to</span> <span m="4841090">p.</span>
  <span m="4842120">And</span> <span m="4842140">then</span> <span m="4842290">I</span>
  <span m="4842380">define</span> <span m="4842710">a</span> <span m="4842770">derivative</span>
  <span m="4843340">with</span> <span m="4843850">that</span> <span m="4844060">transported</span>
  <span m="4844810">notion</span> <span m="4845140">of</span> <span m="4845200">the</span>
  <span m="4845260">vector.</span></p><p><span m="4846370">Now</span> <span m="4847700">notice</span>
  <span m="4847900">I've</span> <span m="4848020">called</span> <span m="4848290">this</span>
  <span m="4848470">notion</span> <span m="4848860">one.</span> <span m="4849970">You</span>
  <span m="4850090">can</span> <span m="4850210">take</span> <span m="4850420">from</span>
  <span m="4850600">that</span> <span m="4850840">this</span> <span m="4851050">idea</span>
  <span m="4851500">of</span> <span m="4851620">how</span> <span m="4851890">I</span>
  <span m="4851980">transport</span> <span m="4852670">the</span> <span m="4852730">vector</span>
  <span m="4853090">from</span> <span m="4853270">one</span> <span m="4853480">place</span>
  <span m="4853720">to</span> <span m="4853810">the</span> <span m="4853930">other</span>
  <span m="4854210">to</span> <span m="4854310">do</span> <span m="4854410">this</span>
  <span m="4854440">comparison.</span> <span m="4855430">I</span> <span m="4855730">cannot</span>
  <span m="4856480">uniquely</span> <span m="4857080">define</span> <span m="4857470">it.</span>
  <span m="4857800">There</span> <span m="4857920">are,</span> <span m="4858010">in</span>
  <span m="4858100">fact,</span> <span m="4858340">multiple</span> <span m="4858670">ways</span>
  <span m="4858890">you</span> <span m="4858950">can</span> <span m="4859090">do</span>
  <span m="4859240">this.</span></p><p><span m="4860180">We're</span> <span m="4860280">going</span>
  <span m="4860290">to</span> <span m="4860350">talk</span> <span m="4860650">about</span>
  <span m="4860890">two</span> <span m="4861400">that</span> <span m="4861610">are</span>
  <span m="4861670">useful</span> <span m="4862630">at</span> <span m="4862750">the</span>
  <span m="4862840">level</span> <span m="4863110">of</span> <span m="4863200">8.962.</span>
  <span m="4864940">In</span> <span m="4865060">principle,</span> <span m="4865420">I</span>
  <span m="4865510">imagine</span> <span m="4865900">you</span> <span m="4865960">could</span>
  <span m="4866080">probably</span> <span m="4866470">come</span> <span m="4866620">up</span>
  <span m="4866710">with</span> <span m="4867120">a</span> <span m="4867160">whole</span>
  <span m="4867340">butt load</span> <span m="4867790">of these</span> <span m="4868030">things.</span>
  <span m="4868760">These</span> <span m="4869050">are</span> <span m="4869230">two</span>
  <span m="4869710">that</span> <span m="4869860">the</span> <span m="4869980">physics</span>
  <span m="4870670">picks</span> <span m="4870970">out</span> <span m="4871150">as</span>
  <span m="4871270">being</span> <span m="4871450">particularly</span> <span m="4871870">useful</span>
  <span m="4872260">for</span> <span m="4872440">us</span> <span m="4872740">for</span>
  <span m="4872920">the</span> <span m="4873040">analysis</span> <span m="4873490">that</span>
  <span m="4873610">we</span> <span m="4873720">are</span> <span m="4873790">going</span>
  <span m="4874030">to</span> <span m="4874150">do.</span> <span m="4874930">OK?</span></p><p><span
  m="4875530">So</span> <span m="4875650">we'll</span> <span m="4875770">pick</span>
  <span m="4875920">it</span> <span m="4876010">up</span> <span m="4876130">there</span>
  <span m="4876400">on</span> <span m="4876550">Tuesday.</span> <span m="4876910">We're</span>
  <span m="4877000">going</span> <span m="4877120">to</span> <span m="4877180">start</span>
  <span m="4877510">by</span> <span m="4877750">coming</span> <span m="4877990">back</span>
  <span m="4878200">to</span> <span m="4878290">this</span> <span m="4878440">notion</span>
  <span m="4878830">of</span> <span m="4879100">I</span> <span m="4879190">want</span>
  <span m="4879400">to</span> <span m="4879490">differentiate</span> <span m="4880090">a</span>
  <span m="4880150">vector</span> <span m="4880510">field</span> <span m="4880870">in</span>
  <span m="4880960">a</span> <span m="4881020">curved</span> <span m="4881290">manifold.</span>
  <span m="4882540">And</span> <span m="4882700">let</span> <span m="4882820">me</span>
  <span m="4882910">just</span> <span m="4883020">state</span> <span m="4883270">before</span>
  <span m="4883940">we</span> <span m="4883990">conclude,</span> <span m="4884950">now</span>
  <span m="4885220">that</span> <span m="4885340">I've</span> <span m="4885490">transported</span>
  <span m="4887500">a</span> <span m="4887740">from</span> <span m="4887980">q</span>
  <span m="4888220">to</span> <span m="4888280">p,</span> <span m="4889030">they</span>
  <span m="4889180">share</span> <span m="4889540">the</span> <span m="4889630">same</span>
  <span m="4889960">tangent</span> <span m="4890440">space.</span> <span m="4891220">Since</span>
  <span m="4891430">they</span> <span m="4891550">share</span> <span m="4891790">the</span>
  <span m="4891880">same</span> <span m="4892150">tangent</span> <span m="4892570">space,</span>
  <span m="4893650">I</span> <span m="4893770">can</span> <span m="4893920">compare</span>
  <span m="4894370">them</span> <span m="4894490">more</span> <span m="4894670">easily.</span>
  <span m="4895030">That</span> <span m="4895270">allows</span> <span m="4895600">me</span>
  <span m="4895690">to</span> <span m="4895780">make</span> <span m="4895930">a</span>
  <span m="4896020">sensible</span> <span m="4896470">derivative</span> <span m="4897310">that</span>
  <span m="4897520">respects</span> <span m="4898180">all</span> <span m="4898330">the</span>
  <span m="4898420">notions</span> <span m="4898750">of</span> <span m="4898800">what</span>
  <span m="4898900">a</span> <span m="4898960">tensor</span> <span m="4899260">should</span>
  <span m="4899440">be.</span> <span m="4900280">We'll</span> <span m="4900400">pick</span>
  <span m="4900520">it</span> <span m="4900610">up</span> <span m="4900670">from</span>
  <span m="4900820">there</span> <span m="4901150">on</span> <span m="4901390">Tuesday.</span></p>
type: course
uid: 009e9bc81210f24c8ec57e2bed6dc256

---
None