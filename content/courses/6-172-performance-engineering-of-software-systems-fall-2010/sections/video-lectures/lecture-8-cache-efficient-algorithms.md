---
about_this_resource_text: <p><strong>Description:</strong> Lecture covering cache-efficient
  algorithms, with tiled and recursive matrix multiplication examples.</p> <p><strong>Speaker:</strong>
  Charles Leiserson</p>
content_type: resource
course_id: 6-172-performance-engineering-of-software-systems-fall-2010
embedded_media:
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.172F10/MIT6_172_F10_lec08_300k.mp4
  parent_uid: de1926ed02fad947746bf4e847d859d3
  title: Video-Internet Archive-MP4
  type: Video
  uid: b202609d6ef3c0fbf94b207f8de06f15
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/itunes-u/lecture-8-cache-efficient/id481759887?i=109649103
  parent_uid: de1926ed02fad947746bf4e847d859d3
  title: Video-iTunes U-MP4
  type: Video
  uid: 882869ead4b81a9d5239eca3b71fe90e
- id: Video-YouTube-Stream
  media_location: T9LkSKK075M
  parent_uid: de1926ed02fad947746bf4e847d859d3
  title: Video-YouTube-Stream
  type: Video
  uid: 688cd78e959a744795314b2b9bb1b087
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/T9LkSKK075M/default.jpg
  parent_uid: de1926ed02fad947746bf4e847d859d3
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 8b8d171e2724a6308a518483036783b6
- id: MIT6_172F10_lec08.pdf
  parent_uid: de1926ed02fad947746bf4e847d859d3
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-8-cache-efficient-algorithms/MIT6_172F10_lec08.pdf
  title: MIT6_172F10_lec08.pdf
  type: null
  uid: 29186b8d2c448129afb0998c5298cc87
- id: 3Play-3PlayYouTubeid-MP4
  media_location: T9LkSKK075M
  parent_uid: de1926ed02fad947746bf4e847d859d3
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: f74795daf2ef85cbea916194eeaeae5c
- id: T9LkSKK075M.srt
  parent_uid: de1926ed02fad947746bf4e847d859d3
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-8-cache-efficient-algorithms/T9LkSKK075M.srt
  title: 3play caption file
  type: null
  uid: 7584f36b4447a510dbb455ef9c4a3c57
- id: T9LkSKK075M.pdf
  parent_uid: de1926ed02fad947746bf4e847d859d3
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-8-cache-efficient-algorithms/T9LkSKK075M.pdf
  title: 3play pdf file
  type: null
  uid: aa5b936f3da492715082a6b854f57b17
- id: Caption-3Play YouTube id-SRT
  parent_uid: de1926ed02fad947746bf4e847d859d3
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ffd71dcd0c367515d8fa206d52709478
- id: Transcript-3Play YouTube id-PDF
  parent_uid: de1926ed02fad947746bf4e847d859d3
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 8c57bf871f9fc0895357715d17509354
file: null
file_size: null
inline_embed_id: 56577474lecture8:cache-efficientalgorithms64297208
layout: video
license: https://creativecommons.org/licenses/by-nc-sa/4.0/
order_index: 93
parent_uid: 24169d0487e846a39c316276f85b8cb5
related_resources_text: ''
short_url: lecture-8-cache-efficient-algorithms
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-8-cache-efficient-algorithms
title: 'Lecture 8: Cache-Efficient Algorithms'
transcript: <p><span m='120'>The</span> <span m='190'>following</span> <span m='630'>content</span>
  <span m='1230'>is</span> <span m='1340'>provided</span> <span m='1790'>under</span>
  <span m='2070'>a</span> <span m='2090'>Creative</span> <span m='2500'>Commons</span>
  <span m='2910'>license.</span> <span m='3910'>Your</span> <span m='4200'>support</span>
  <span m='4700'>will</span> <span m='4870'>help</span> <span m='5100'>MIT</span>
  <span m='5580'>OpenCourseWare</span> <span m='6360'>continue</span> <span m='6870'>to</span>
  <span m='6950'>offer</span> <span m='7380'>high</span> <span m='7590'>quality</span>
  <span m='8119'>educational</span> <span m='8740'>resources</span> <span m='9390'>for</span>
  <span m='9520'>free.</span> <span m='10600'>To</span> <span m='10730'>make</span>
  <span m='10930'>a</span> <span m='10980'>donation</span> <span m='11620'>or</span>
  <span m='11930'>view</span> <span m='12340'>additional</span> <span m='12800'>materials</span>
  <span m='13340'>from</span> <span m='13500'>hundreds</span> <span m='13930'>of</span>
  <span m='14040'>MIT</span> <span m='14460'>courses,</span> <span m='15460'>visit</span>
  <span m='15790'>MIT</span> <span m='16219'>OpenCourseWare</span> <span m='17250'>at</span>
  <span m='17430'>ocw.mit.edu.</span> </p><p><span m='21764'>PROFESSOR:</span> <span
  m='22190'>Good,</span> <span m='22440'>we're</span> <span m='22560'>going</span>
  <span m='22680'>to</span> <span m='22750'>take</span> <span m='23170'>a</span> <span
  m='23220'>detour</span> <span m='23730'>today</span> <span m='24150'>into</span>
  <span m='24590'>the</span> <span m='25730'>realm</span> <span m='26060'>of</span>
  <span m='26170'>algorithms.</span> <span m='30860'>So</span> <span m='31060'>when</span>
  <span m='31240'>you're</span> <span m='31350'>trying</span> <span m='31480'>to</span>
  <span m='31610'>make</span> <span m='31820'>code</span> <span m='32130'>go</span>
  <span m='32310'>fast,</span> <span m='32940'>of</span> <span m='33040'>course,</span>
  <span m='34570'>there's</span> <span m='34900'>no</span> <span m='35060'>holds</span>
  <span m='35420'>barred.</span> <span m='36470'>You</span> <span m='36640'>can</span>
  <span m='36790'>use</span> <span m='37070'>whatever</span> <span m='37430'>you</span>
  <span m='37650'>need</span> <span m='37950'>to</span> <span m='38310'>in</span>
  <span m='38670'>order to</span> <span m='38970'>make</span> <span m='39180'>it</span>
  <span m='39270'>go</span> <span m='39410'>fast.</span> <span m='40290'>Today</span>
  <span m='40550'>we're</span> <span m='40690'>going</span> <span m='40770'>to</span>
  <span m='40860'>talk</span> <span m='41650'>a</span> <span m='41750'>little</span>
  <span m='41950'>bit</span> <span m='42560'>in</span> <span m='42630'>a</span> <span
  m='42680'>more</span> <span m='42900'>principled</span> <span m='43700'>way</span>
  <span m='44780'>about</span> <span m='45180'>the</span> <span m='45260'>memory</span>
  <span m='45580'>hierarchy.</span> </p><p><span m='47870'>And</span> <span m='48150'>to</span>
  <span m='48230'>do</span> <span m='48420'>that</span> <span m='48790'>we're</span>
  <span m='48950'>going</span> <span m='49040'>to</span> <span m='49080'>introduce</span>
  <span m='50160'>what</span> <span m='50310'>we</span> <span m='50430'>call</span>
  <span m='50720'>the</span> <span m='50850'>ideal-cache</span> <span m='51860'>model.</span>
  <span m='54290'>So</span> <span m='54630'>as</span> <span m='54750'>you know</span>
  <span m='55120'>most</span> <span m='55450'>caches</span> <span m='57740'>are</span>
  <span m='58620'>hacked</span> <span m='58980'>together</span> <span m='59600'>to</span>
  <span m='59730'>try</span> <span m='60090'>to</span> <span m='61880'>provide</span>
  <span m='62270'>something</span> <span m='62580'>that will</span> <span m='63030'>cache</span>
  <span m='63450'>well</span> <span m='63820'>while</span> <span m='64040'>still</span>
  <span m='64310'>making</span> <span m='64660'>it</span> <span m='65310'>easy</span>
  <span m='65670'>to</span> <span m='65760'>build</span> <span m='67010'>and</span>
  <span m='67270'>fast</span> <span m='67640'>to</span> <span m='67720'>build.</span>
  <span m='68530'>The</span> <span m='68720'>ideal-cache</span> <span m='69490'>model</span>
  <span m='71470'>is</span> <span m='71640'>a</span> <span m='73230'>pretty</span>
  <span m='73520'>nice</span> <span m='73850'>beast</span> <span m='74220'>if</span>
  <span m='74340'>we</span> <span m='74450'>had</span> <span m='74740'>them.</span>
  </p><p><span m='76720'>It's</span> <span m='76950'>got</span> <span m='77130'>a</span>
  <span m='77230'>two-level</span> <span m='77720'>hierarchy.</span> <span m='79760'>It's</span>
  <span m='79960'>got</span> <span m='80100'>a</span> <span m='80160'>cache</span>
  <span m='81280'>that</span> <span m='81420'>has</span> <span m='81830'>m</span>
  <span m='82090'>bytes</span> <span m='82650'>that</span> <span m='82780'>are</span>
  <span m='82850'>organized</span> <span m='83610'>in</span> <span m='83700'>to</span>
  <span m='83810'>b</span> <span m='84080'>byte</span> <span m='85100'>cache-lines.</span>
  <span m='86430'>So</span> <span m='86540'>each</span> <span m='86780'>block</span>
  <span m='87560'>is</span> <span m='88360'>b</span> <span m='88520'>bytes.</span>
  <span m='90020'>And</span> <span m='90410'>it's</span> <span m='90600'>fully</span>
  <span m='90900'>associative.</span> <span m='91980'>So you</span> <span m='92230'>recall,</span>
  <span m='92670'>that</span> <span m='92850'>means</span> <span m='93100'>that</span>
  <span m='93880'>any</span> <span m='94250'>line</span> <span m='94670'>can</span>
  <span m='94840'>go</span> <span m='95020'>anywhere</span> <span m='95550'>in</span>
  <span m='95680'>cache.</span> </p><p><span m='97720'>And</span> <span m='98000'>probably</span>
  <span m='98580'>the</span> <span m='98700'>most</span> <span m='99430'>impressive</span>
  <span m='100100'>aspect</span> <span m='100710'>of</span> <span m='100790'>an</span>
  <span m='100900'>ideal-cache</span> <span m='102680'>is</span> <span m='102990'>that</span>
  <span m='103120'>it</span> <span m='103280'>has</span> <span m='103890'>an</span>
  <span m='104230'>optimal</span> <span m='104950'>omniscient</span> <span m='105680'>replacement</span>
  <span m='106360'>algorithm.</span> <span m='108590'>So</span> <span m='108820'>what</span>
  <span m='108990'>it</span> <span m='109130'>does,</span> <span m='109500'>is</span>
  <span m='109670'>it</span> <span m='109840'>figures</span> <span m='110200'>out</span>
  <span m='111510'>when</span> <span m='111970'>it</span> <span m='112270'>needs</span>
  <span m='112530'>to</span> <span m='112640'>kick</span> <span m='112920'>something</span>
  <span m='113300'>out</span> <span m='113400'>of</span> <span m='113480'>cache,</span>
  <span m='113920'>it</span> <span m='114030'>says,</span> <span m='114450'>what</span>
  <span m='114830'>is</span> <span m='115010'>the</span> <span m='115170'>absolutely</span>
  <span m='116110'>best</span> <span m='116660'>thing</span> <span m='117510'>you</span>
  <span m='117680'>could</span> <span m='117880'>possibly</span> <span m='118680'>kick</span>
  <span m='118970'>out</span> <span m='119150'>of</span> <span m='119240'>cache.</span>
  <span m='121080'>And</span> <span m='121290'>it</span> <span m='121440'>does</span>
  <span m='121740'>that</span> <span m='121990'>one.</span> <span m='123310'>Looking</span>
  <span m='123690'>into</span> <span m='123850'>the</span> <span m='123970'>future</span>
  <span m='124450'>if</span> <span m='124580'>need</span> <span m='124820'>be.</span>
  </p><p><span m='125400'>It</span> <span m='125670'>says,</span> <span m='125910'>oh</span>
  <span m='126070'>is</span> <span m='126190'>this</span> <span m='126370'>going</span>
  <span m='126500'>to</span> <span m='126630'>be</span> <span m='126780'>accessed</span>
  <span m='127230'>a</span> <span m='127290'>lot</span> <span m='127610'>in</span>
  <span m='127700'>the</span> <span m='127790'>future?</span> <span m='128210'>I</span>
  <span m='128320'>think</span> <span m='128590'>I'll</span> <span m='128740'>keep</span>
  <span m='129009'>this</span> <span m='129210'>one.</span> <span m='129800'>Let's</span>
  <span m='130000'>throw</span> <span m='130280'>out</span> <span m='130479'>this</span>
  <span m='130639'>one.</span> <span m='130810'>I</span> <span m='130870'>know</span>
  <span m='131090'>it's</span> <span m='131230'>never</span> <span m='131440'>going</span>
  <span m='131530'>to</span> <span m='131590'>be</span> <span m='131700'>used</span>
  <span m='132000'>again.</span> <span m='132920'>So</span> <span m='133120'>it</span>
  <span m='133220'>has</span> <span m='135230'>that</span> <span m='135480'>omniscient</span>
  <span m='137210'>character</span> <span m='137730'>to</span> <span m='137900'>it.</span>
  </p><p><span m='140790'>The</span> <span m='141190'>performance</span> <span m='141930'>measures</span>
  <span m='142340'>we're</span> <span m='142470'>going</span> <span m='142540'>to</span>
  <span m='142610'>look</span> <span m='142920'>at</span> <span m='143330'>in</span>
  <span m='143510'>this</span> <span m='144120'>model,</span> <span m='144830'>the</span>
  <span m='145270'>first</span> <span m='145640'>one</span> <span m='145810'>is</span>
  <span m='147240'>what</span> <span m='147370'>we</span> <span m='147470'>call</span>
  <span m='147710'>the</span> <span m='147790'>work.</span> <span m='148180'>And</span>
  <span m='148290'>that's</span> <span m='148500'>just</span> <span m='148690'>the</span>
  <span m='148870'>ordinary</span> <span m='149490'>serial</span> <span m='150590'>running</span>
  <span m='150940'>time</span> <span m='151310'>if</span> <span m='151390'>you</span>
  <span m='151490'>just</span> <span m='151700'>ran</span> <span m='153250'>the</span>
  <span m='153710'>code</span> <span m='154140'>on</span> <span m='154990'>one</span>
  <span m='155350'>processor</span> <span m='156280'>and</span> <span m='156450'>counted</span>
  <span m='156840'>up</span> <span m='157420'>essentially</span> <span m='159190'>how</span>
  <span m='159420'>many</span> <span m='159650'>processor</span> <span m='160350'>instructions</span>
  <span m='162070'>you</span> <span m='162370'>would</span> <span m='162540'>do.</span>
  <span m='163980'>That's</span> <span m='164230'>essentially</span> <span m='164730'>the</span>
  <span m='164840'>work.</span> </p><p><span m='166530'>The</span> <span m='166640'>second</span>
  <span m='167060'>measure,</span> <span m='167450'>which</span> <span m='167650'>is</span>
  <span m='167750'>the</span> <span m='167850'>one</span> <span m='169980'>that's</span>
  <span m='170260'>much</span> <span m='170470'>more</span> <span m='170660'>interesting,</span>
  <span m='171260'>is</span> <span m='171480'>cache</span> <span m='171890'>misses.</span>
  <span m='173150'>So</span> <span m='173330'>the</span> <span m='173420'>work</span>
  <span m='174500'>has</span> <span m='174790'>to</span> <span m='174870'>do</span>
  <span m='174980'>with</span> <span m='175070'>the</span> <span m='175170'>processor.</span>
  <span m='176080'>The</span> <span m='176190'>cache</span> <span m='176600'>misses</span>
  <span m='177000'>has</span> <span m='177310'>to</span> <span m='177410'>do</span>
  <span m='177650'>with</span> <span m='178100'>what</span> <span m='178380'>moves</span>
  <span m='178800'>between</span> <span m='179290'>these</span> <span m='179650'>two</span>
  <span m='182860'>levels</span> <span m='183290'>of</span> <span m='183370'>memory.</span>
  </p><p><span m='184470'>So</span> <span m='184660'>in</span> <span m='184730'>this</span>
  <span m='184960'>case,</span> <span m='186680'>what</span> <span m='186920'>we're</span>
  <span m='187120'>interested</span> <span m='187530'>in</span> <span m='187650'>doing</span>
  <span m='187860'>is,</span> <span m='187970'>how</span> <span m='188230'>often</span>
  <span m='189080'>do</span> <span m='189230'>I</span> <span m='189310'>try</span>
  <span m='189500'>to</span> <span m='189560'>access</span> <span m='190120'>something.</span>
  <span m='190620'>It's</span> <span m='190820'>not</span> <span m='191180'>in</span>
  <span m='191310'>the</span> <span m='191410'>cache.</span> <span m='192050'>I have</span>
  <span m='192100'>to go</span> <span m='192230'>to</span> <span m='192370'>main</span>
  <span m='193100'>memory</span> <span m='193680'>and</span> <span m='193850'>bring</span>
  <span m='194040'>it</span> <span m='194140'>back</span> <span m='194400'>into</span>
  <span m='194630'>cache.</span> <span m='196480'>And</span> <span m='196610'>so</span>
  <span m='196720'>that's</span> <span m='197020'>what</span> <span m='197210'>we'll</span>
  <span m='197360'>be</span> <span m='197500'>counting</span> <span m='198300'>in</span>
  <span m='198470'>this</span> <span m='198660'>model.</span> </p><p><span m='202460'>So</span>
  <span m='203190'>it's</span> <span m='203440'>reasonable</span> <span m='203980'>to</span>
  <span m='204060'>ask</span> <span m='204520'>how</span> <span m='205490'>reasonable</span>
  <span m='207080'>ideal</span> <span m='207580'>caches</span> <span m='208120'>are.</span>
  <span m='210030'>In</span> <span m='210300'>particular</span> <span m='211800'>the</span>
  <span m='212440'>assumption</span> <span m='213020'>of</span> <span m='213340'>omniscient</span>
  <span m='213930'>replacement,</span> <span m='216830'>that's</span> <span m='217050'>pretty</span>
  <span m='217690'>powerful</span> <span m='218220'>stuff.</span> <span m='219280'>Well</span>
  <span m='219470'>it</span> <span m='219560'>turns</span> <span m='219930'>out</span>
  <span m='220240'>there's</span> <span m='220420'>a</span> <span m='220470'>great</span>
  <span m='220790'>lemma</span> <span m='221210'>due</span> <span m='221380'>to</span>
  <span m='221620'>Slater</span> <span m='221950'>and</span> <span m='222070'>Tarjan</span>
  <span m='225000'>that</span> <span m='225310'>says</span> <span m='225470'>essentially</span>
  <span m='226060'>the</span> <span m='226170'>following.</span> </p><p><span m='226760'>Suppose</span>
  <span m='227440'>that</span> <span m='227570'>you</span> <span m='227670'>have</span>
  <span m='227780'>an</span> <span m='227880'>algorithm</span> <span m='228560'>that</span>
  <span m='228710'>incurs</span> <span m='229900'>q</span> <span m='230340'>cache</span>
  <span m='230800'>misses</span> <span m='231870'>on</span> <span m='232030'>an</span>
  <span m='232200'>ideal</span> <span m='232700'>cache</span> <span m='233250'>of</span>
  <span m='233360'>size</span> <span m='234120'>n.</span> <span m='236220'>So</span>
  <span m='236340'>you</span> <span m='236490'>ran</span> <span m='236730'>the</span>
  <span m='236860'>algorithm</span> <span m='237270'>on</span> <span m='237420'>your</span>
  <span m='237510'>machine,</span> <span m='237970'>you had</span> <span m='238130'>a</span>
  <span m='238190'>cache</span> <span m='238590'>of</span> <span m='238670'>size</span>
  <span m='239150'>n.</span> <span m='240870'>Then,</span> <span m='241800'>if</span>
  <span m='242180'>instead</span> <span m='242700'>of</span> <span m='242820'>having</span>
  <span m='243160'>an</span> <span m='243300'>ideal</span> <span m='243890'>cache,</span>
  <span m='244290'>you have</span> <span m='244550'>a</span> <span m='244800'>fully</span>
  <span m='245050'>associative</span> <span m='245640'>cache</span> <span m='246080'>of</span>
  <span m='246200'>size</span> <span m='246690'>two</span> <span m='247060'>m</span>
  <span m='248300'>and</span> <span m='248510'>use</span> <span m='248860'>the</span>
  <span m='248970'>least</span> <span m='249350'>recently</span> <span m='249970'>used</span>
  <span m='250380'>replacement</span> <span m='251030'>policy.</span> </p><p><span
  m='252180'>So</span> <span m='252410'>you</span> <span m='252540'>always,</span>
  <span m='252910'>whenever</span> <span m='253210'>you're</span> <span m='253360'>kicking</span>
  <span m='253710'>something</span> <span m='254130'>out</span> <span m='254260'>of</span>
  <span m='254350'>cache,</span> <span m='255160'>you</span> <span m='255290'>kick</span>
  <span m='255540'>out</span> <span m='255760'>the</span> <span m='255860'>thing</span>
  <span m='256170'>that</span> <span m='256300'>has</span> <span m='256510'>been</span>
  <span m='256709'>touched</span> <span m='257110'>the</span> <span m='257190'>longest</span>
  <span m='257839'>ago</span> <span m='258240'>in</span> <span m='258310'>the</span>
  <span m='258399'>past.</span> <span m='262110'>Then</span> <span m='262540'>it</span>
  <span m='262800'>incurs</span> <span m='263340'>at</span> <span m='263490'>most</span>
  <span m='264320'>2Q</span> <span m='265280'>cache</span> <span m='265730'>misses.</span>
  <span m='268290'>So</span> <span m='268440'>what</span> <span m='268570'>that</span>
  <span m='268800'>says</span> <span m='269200'>is</span> <span m='269560'>that</span>
  <span m='269860'>LRU</span> <span m='271180'>is</span> <span m='272220'>to</span>
  <span m='272360'>with</span> <span m='272560'>it</span> <span m='272710'>constant</span>
  <span m='273320'>factors</span> <span m='273940'>essentially</span> <span m='274580'>the</span>
  <span m='274720'>same</span> <span m='275220'>as</span> <span m='275360'>optimal.</span>
  <span m='277550'>Really</span> <span m='277870'>quite</span> <span m='278150'>a</span>
  <span m='278210'>remarkable</span> <span m='278790'>result.</span> </p><p><span
  m='282170'>Who's</span> <span m='282380'>taking</span> <span m='282690'>6046?</span>
  <span m='284800'>You've</span> <span m='285250'>just</span> <span m='285480'>seen</span>
  <span m='285700'>this,</span> <span m='285920'>right?</span> <span m='286630'>Yeah,</span>
  <span m='287300'>OK.</span> <span m='287970'>Just</span> <span m='288220'>seen</span>
  <span m='288440'>this</span> <span m='289790'>result</span> <span m='290300'>in</span>
  <span m='290430'>6046.</span> <span m='291810'>See,</span> <span m='291950'>I</span>
  <span m='292000'>do</span> <span m='292190'>talk</span> <span m='292430'>to</span>
  <span m='292520'>my</span> <span m='292630'>colleagues</span> <span m='293080'>occasionally.</span>
  </p><p><span m='295830'>So</span> <span m='296040'>then</span> <span m='296620'>something</span>
  <span m='297000'>about</span> <span m='297240'>how</span> <span m='297440'>this</span>
  <span m='297630'>is</span> <span m='297780'>proved.</span> <span m='299720'>And</span>
  <span m='301090'>what's</span> <span m='301470'>important</span> <span m='301950'>here</span>
  <span m='302390'>is</span> <span m='302660'>that</span> <span m='302820'>really</span>
  <span m='303190'>it</span> <span m='303320'>just</span> <span m='303550'>says,</span>
  <span m='303860'>OK,</span> <span m='304240'>Yeah</span> <span m='304530'>you</span>
  <span m='304720'>could</span> <span m='304930'>dither</span> <span m='305290'>on</span>
  <span m='305420'>the</span> <span m='305520'>constants,</span> <span m='306780'>but</span>
  <span m='306960'>basically</span> <span m='307550'>whether</span> <span m='307790'>you</span>
  <span m='307920'>choose</span> <span m='308220'>LRU</span> <span m='309160'>or</span>
  <span m='309350'>choose</span> <span m='309760'>ideal</span> <span m='310740'>cache</span>
  <span m='312160'>with</span> <span m='312310'>the</span> <span m='312440'>omniscient</span>
  <span m='312910'>replacement,</span> <span m='314710'>asymptotically</span> <span
  m='315480'>you're</span> <span m='315770'>not</span> <span m='315960'>going</span>
  <span m='316060'>to</span> <span m='316100'>be</span> <span m='316250'>off</span>
  <span m='316510'>at</span> <span m='316590'>all.</span> </p><p><span m='319110'>So</span>
  <span m='319370'>for</span> <span m='319550'>most</span> <span m='319910'>asymptotic</span>
  <span m='320570'>analyses,</span> <span m='321150'>you</span> <span m='321270'>can</span>
  <span m='321400'>assume</span> <span m='321900'>optimal</span> <span m='322470'>or</span>
  <span m='322830'>LRU</span> <span m='323190'>replacement</span> <span m='323790'>as</span>
  <span m='324090'>convenient.</span> <span m='325550'>And</span> <span m='325700'>the</span>
  <span m='325810'>typical</span> <span m='326260'>way</span> <span m='326520'>that</span>
  <span m='326710'>you</span> <span m='326850'>do</span> <span m='327190'>convenience</span>
  <span m='328010'>is</span> <span m='329470'>if</span> <span m='329620'>you're</span>
  <span m='329740'>looking</span> <span m='330130'>at</span> <span m='330340'>upper</span>
  <span m='330640'>bounds.</span> <span m='332810'>So</span> <span m='332950'>you're</span>
  <span m='333100'>trying</span> <span m='333400'>to</span> <span m='333470'>show</span>
  <span m='333900'>that a</span> <span m='334090'>particular</span> <span m='334590'>algorithm</span>
  <span m='335090'>is</span> <span m='335290'>good,</span> <span m='336380'>then</span>
  <span m='336610'>what</span> <span m='336770'>you</span> <span m='336950'>do</span>
  <span m='337130'>is</span> <span m='337260'>you</span> <span m='337420'>assume</span>
  <span m='337810'>optimal</span> <span m='338380'>replacement.</span> </p><p><span
  m='340970'>If</span> <span m='341140'>you're</span> <span m='341250'>trying</span>
  <span m='341540'>to</span> <span m='341610'>show</span> <span m='341870'>that</span>
  <span m='342020'>some</span> <span m='342220'>algorithm</span> <span m='342730'>is</span>
  <span m='342910'>bad,</span> <span m='344890'>then</span> <span m='345070'>what</span>
  <span m='345200'>you</span> <span m='345300'>do</span> <span m='345460'>is</span>
  <span m='345590'>assume</span> <span m='345910'>that</span> <span m='346030'>it's</span>
  <span m='346200'>LRU</span> <span m='347360'>to</span> <span m='347500'>get</span>
  <span m='347650'>a</span> <span m='347710'>lower</span> <span m='348060'>bound.</span>
  <span m='349510'>Because</span> <span m='349700'>then</span> <span m='349850'>you</span>
  <span m='349970'>can</span> <span m='350090'>reason</span> <span m='350680'>more</span>
  <span m='350920'>easily</span> <span m='351400'>about</span> <span m='351710'>what's</span>
  <span m='351930'>actually</span> <span m='352330'>in</span> <span m='352410'>memory.</span>
  <span m='353450'>Because you</span> <span m='353790'>just</span> <span m='353930'>say,</span>
  <span m='354190'>oh</span> <span m='354330'>we'll</span> <span m='354440'>just</span>
  <span m='354640'>keep</span> <span m='354860'>the</span> <span m='354940'>least</span>
  <span m='355210'>recently</span> <span m='355630'>used</span> <span m='356010'>one.</span>
  <span m='357960'>So</span> <span m='358240'>you</span> <span m='358390'>tend</span>
  <span m='358660'>to</span> <span m='358700'>use</span> <span m='359160'>the</span>
  <span m='359280'>two</span> <span m='359560'>for</span> <span m='359820'>upper</span>
  <span m='360100'>bounds</span> <span m='360510'>and</span> <span m='360550'>lower</span>
  <span m='360860'>bounds.</span> </p><p><span m='363230'>Now,</span> <span m='364750'>the</span>
  <span m='364860'>way</span> <span m='365070'>this</span> <span m='365260'>relates</span>
  <span m='365830'>to</span> <span m='366110'>software</span> <span m='366610'>engineering</span>
  <span m='368840'>is</span> <span m='369100'>as</span> <span m='369240'>follows.</span>
  <span m='370280'>If</span> <span m='370430'>you're</span> <span m='370550'>developing</span>
  <span m='372610'>a</span> <span m='372690'>really</span> <span m='372960'>fast</span>
  <span m='373380'>algorithm,</span> <span m='373990'>it's</span> <span m='374250'>going</span>
  <span m='374450'>to</span> <span m='374530'>start</span> <span m='375000'>from</span>
  <span m='375090'>a</span> <span m='375180'>theoretically</span> <span m='375870'>sound</span>
  <span m='376330'>algorithm.</span> <span m='378800'>And</span> <span m='379080'>from</span>
  <span m='379450'>that</span> <span m='379780'>then</span> <span m='379980'>you</span>
  <span m='380210'>have</span> <span m='380450'>to</span> <span m='380870'>engineer</span>
  <span m='382090'>for</span> <span m='382280'>detailed</span> <span m='382790'>performance.</span>
  </p><p><span m='384460'>So</span> <span m='386230'>you</span> <span m='386380'>have</span>
  <span m='386530'>to</span> <span m='386640'>take</span> <span m='387460'>into</span>
  <span m='387670'>account</span> <span m='388040'>things</span> <span m='388290'>like</span>
  <span m='388510'>real</span> <span m='388790'>caches</span> <span m='389300'>are</span>
  <span m='389380'>not</span> <span m='389620'>fully</span> <span m='389900'>associative.</span>
  <span m='391630'>That</span> <span m='391910'>loads</span> <span m='392320'>and</span>
  <span m='392420'>stores,</span> <span m='392840'>for</span> <span m='392940'>example,</span>
  <span m='393320'>have</span> <span m='393370'>different</span> <span m='393770'>cost</span>
  <span m='394240'>with</span> <span m='394350'>respect</span> <span m='394790'>to</span>
  <span m='394860'>bandwidth</span> <span m='395360'>and</span> <span m='395450'>latency.</span>
  <span m='396670'>So</span> <span m='396860'>whether</span> <span m='397110'>you</span>
  <span m='397270'>miss</span> <span m='397510'>some</span> <span m='397680'>a</span>
  <span m='397750'>load or</span> <span m='398190'>miss</span> <span m='398450'>on</span>
  <span m='398590'>a</span> <span m='398640'>store,</span> <span m='399460'>there's</span>
  <span m='399630'>a</span> <span m='399700'>different</span> <span m='400120'>impact.</span>
  <span m='402200'>But</span> <span m='402360'>these</span> <span m='402560'>are</span>
  <span m='402700'>all</span> <span m='403830'>the</span> <span m='403970'>tuning.</span>
  </p><p><span m='404800'>And</span> <span m='404970'>as</span> <span m='405160'>you
  know,</span> <span m='405550'>those</span> <span m='405790'>constant</span> <span
  m='406220'>factors</span> <span m='406770'>can</span> <span m='406910'>sometimes</span>
  <span m='407570'>add</span> <span m='407860'>up</span> <span m='408870'>to</span>
  <span m='409080'>dramatic</span> <span m='409680'>numbers,</span> <span m='411900'>orders</span>
  <span m='412350'>of</span> <span m='412400'>magnitude.</span> <span m='414550'>And</span>
  <span m='414710'>so</span> <span m='414850'>it's</span> <span m='414950'>important</span>
  <span m='415340'>to</span> <span m='415420'>do</span> <span m='415600'>that</span>
  <span m='415800'>software</span> <span m='416090'>engineering.</span> <span m='416560'>But</span>
  <span m='416730'>starting</span> <span m='417190'>from</span> <span m='417360'>a</span>
  <span m='417540'>good</span> <span m='417800'>theoretical</span> <span m='418350'>basis</span>
  <span m='418900'>means</span> <span m='419650'>that</span> <span m='419800'>you</span>
  <span m='419910'>actually</span> <span m='420200'>have</span> <span m='420440'>an</span>
  <span m='420510'>algorithm</span> <span m='421460'>that</span> <span m='421630'>is</span>
  <span m='421810'>going</span> <span m='421960'>to</span> <span m='422020'>work</span>
  <span m='422360'>well</span> <span m='423600'>across</span> <span m='424550'>a</span>
  <span m='425590'>large</span> <span m='426020'>variety</span> <span m='426770'>of</span>
  <span m='427660'>real</span> <span m='427980'>situations.</span> </p><p><span m='431370'>Now,</span>
  <span m='432230'>there's</span> <span m='432410'>one</span> <span m='432670'>other</span>
  <span m='432900'>assumption</span> <span m='433510'>we</span> <span m='433680'>tend</span>
  <span m='433970'>to</span> <span m='434070'>make</span> <span m='434500'>when</span>
  <span m='434700'>we're</span> <span m='434810'>dealing</span> <span m='435280'>with</span>
  <span m='435700'>ideal</span> <span m='436130'>caches,</span> <span m='437160'>and</span>
  <span m='437290'>that's</span> <span m='437570'>called</span> <span m='438150'>the</span>
  <span m='438540'>tall-cache</span> <span m='439400'>assumption.</span> <span m='442080'>So</span>
  <span m='442700'>what</span> <span m='442860'>the</span> <span m='442970'>tall-cache</span>
  <span m='443760'>assumption</span> <span m='444410'>says,</span> <span m='445400'>is</span>
  <span m='445760'>that</span> <span m='446300'>I</span> <span m='446960'>you</span>
  <span m='447100'>have</span> <span m='447380'>at</span> <span m='447500'>least</span>
  <span m='448030'>as</span> <span m='448210'>many</span> <span m='448550'>lines</span>
  <span m='449090'>of</span> <span m='449190'>cache,</span> <span m='449910'>essentially,</span>
  <span m='452910'>in</span> <span m='453090'>your</span> <span m='453230'>cache,</span>
  <span m='454240'>as</span> <span m='454560'>you</span> <span m='454760'>have</span>
  <span m='455300'>bytes</span> <span m='455800'>in</span> <span m='456000'>the</span>
  <span m='456090'>line.</span> <span m='459130'>So</span> <span m='459400'>it</span>
  <span m='459540'>says</span> <span m='459620'>the cache</span> <span m='460040'>is</span>
  <span m='460210'>tall.</span> </p><p><span m='460620'>In</span> <span m='460720'>other</span>
  <span m='460860'>words,</span> <span m='461040'>this</span> <span m='461310'>dimension</span>
  <span m='461790'>here</span> <span m='464120'>is</span> <span m='464490'>bigger</span>
  <span m='464880'>than</span> <span m='465090'>this</span> <span m='465310'>dimension</span>
  <span m='465770'>here.</span> <span m='468040'>And</span> <span m='468230'>in</span>
  <span m='468330'>particular,</span> <span m='468960'>you</span> <span m='469110'>want</span>
  <span m='469410'>that</span> <span m='469630'>to</span> <span m='469720'>be</span>
  <span m='469950'>true</span> <span m='470190'>for</span> <span m='470820'>where</span>
  <span m='470980'>we</span> <span m='471070'>have</span> <span m='471190'>some</span>
  <span m='471440'>constant</span> <span m='472130'>here</span> <span m='472750'>of</span>
  <span m='472900'>slop</span> <span m='473400'>that</span> <span m='473560'>we</span>
  <span m='473720'>can</span> <span m='473970'>throw</span> <span m='474360'>in.</span>
  <span m='475000'>Yes,</span> <span m='475280'>question.</span> </p><p><span m='476168'>AUDIENCE:</span>
  <span m='476636'>Does that</span> <span m='477104'>[INAUDIBLE]</span> <span m='478976'>associatively</span>
  <span m='479912'>make the</span> <span m='480380'>cache</span> <span m='480848'>shorter</span>
  <span m='481316'>here.</span> </p><p><span m='482090'>PROFESSOR:</span> <span m='482390'>Yes,</span>
  <span m='482670'>so</span> <span m='482800'>this</span> <span m='483020'>is</span>
  <span m='483150'>basically</span> <span m='483680'>assuming</span> <span m='485090'>everything</span>
  <span m='485510'>is</span> <span m='485660'>ideal.</span> <span m='487310'>We're</span>
  <span m='487430'>going</span> <span m='487510'>to</span> <span m='487550'>go</span>
  <span m='487730'>back.</span> <span m='488420'>When</span> <span m='488670'>you</span>
  <span m='488770'>engineer</span> <span m='489220'>things,</span> <span m='489750'>you</span>
  <span m='489920'>have</span> <span m='490090'>to</span> <span m='490210'>deal</span>
  <span m='490430'>with</span> <span m='490510'>the</span> <span m='490600'>fact</span>
  <span m='490880'>that</span> <span m='491030'>things</span> <span m='491280'>aren't</span>
  <span m='491520'>ideal.</span> </p><p><span m='492330'>But</span> <span m='492540'>usually</span>
  <span m='492880'>that's</span> <span m='493190'>just</span> <span m='493420'>a</span>
  <span m='493460'>little</span> <span m='493680'>bit</span> <span m='493810'>of</span>
  <span m='493900'>a</span> <span m='493970'>tweak</span> <span m='495590'>on</span>
  <span m='495840'>the</span> <span m='496090'>actual</span> <span m='496520'>ideal</span>
  <span m='497140'>algorithm.</span> <span m='497570'>And</span> <span m='497680'>for</span>
  <span m='497790'>many</span> <span m='498900'>programs,</span> <span m='499510'>the</span>
  <span m='499820'>ideal</span> <span m='500950'>algorithm</span> <span m='501430'>you</span>
  <span m='501510'>don't</span> <span m='501640'>actually</span> <span m='501910'>have</span>
  <span m='502020'>to</span> <span m='502120'>tweak</span> <span m='502400'>at</span>
  <span m='502480'>all</span> <span m='504750'>to</span> <span m='504910'>get</span>
  <span m='505040'>a</span> <span m='505170'>good</span> <span m='507050'>practical</span>
  <span m='507700'>algorithm.</span> <span m='508470'>So</span> <span m='508650'>here</span>
  <span m='508910'>is</span> <span m='509030'>just</span> <span m='509260'>saying</span>
  <span m='509530'>the</span> <span m='509620'>cache</span> <span m='509910'>should</span>
  <span m='510140'>be</span> <span m='510290'>tall.</span> </p><p><span m='513080'>Now,</span>
  <span m='514669'>just</span> <span m='514909'>as</span> <span m='515049'>an</span>
  <span m='515130'>example,</span> <span m='516309'>if</span> <span m='516460'>we</span>
  <span m='516570'>look</span> <span m='516830'>at</span> <span m='517980'>the</span>
  <span m='518210'>machines</span> <span m='518600'>that</span> <span m='518710'>we're</span>
  <span m='518929'>using,</span> <span m='519470'>the</span> <span m='519580'>cache-line</span>
  <span m='520230'>length</span> <span m='520520'>is</span> <span m='520630'>64 bytes.</span>
  <span m='522165'>The</span> <span m='522450'>L1</span> <span m='523039'>cache</span>
  <span m='523390'>size</span> <span m='523789'>is</span> <span m='523980'>32 kilobytes.</span>
  <span m='526420'>And</span> <span m='526570'>of</span> <span m='526670'>course,</span>
  <span m='529290'>for</span> <span m='529710'>L1</span> <span m='529900'>it's</span>
  <span m='530140'>is</span> <span m='530290'>32 kilobytes</span> <span m='531190'>and</span>
  <span m='531340'>for</span> <span m='532000'>L2 and</span> <span m='532260'>L3,</span>
  <span m='533150'>it's</span> <span m='533330'>even</span> <span m='533590'>bigger.</span>
  <span m='534530'>It's</span> <span m='534620'>even</span> <span m='534920'>taller.</span>
  <span m='535710'>Because</span> <span m='535940'>they</span> <span m='536100'>also</span>
  <span m='536500'>have</span> <span m='536760'>64k</span> <span m='539870'>line.</span>
  <span m='540200'>So</span> <span m='540320'>this</span> <span m='540510'>is</span>
  <span m='540650'>a</span> <span m='540710'>fairly</span> <span m='541170'>reasonable</span>
  <span m='541710'>assumption</span> <span m='542650'>to</span> <span m='542790'>make,</span>
  <span m='543330'>that</span> <span m='543600'>you</span> <span m='543730'>have</span>
  <span m='543920'>more</span> <span m='544400'>lines</span> <span m='547600'>in</span>
  <span m='547790'>your</span> <span m='547950'>cache</span> <span m='548760'>then</span>
  <span m='549060'>essentially</span> <span m='549490'>the</span> <span m='549620'>length,</span>
  <span m='550040'>the</span> <span m='550140'>number</span> <span m='550410'>of</span>
  <span m='550490'>items</span> <span m='550880'>you</span> <span m='551020'>can</span>
  <span m='551170'>put</span> <span m='553380'>on</span> <span m='553580'>a</span>
  <span m='553630'>cache</span> <span m='554010'>line.</span> </p><p><span m='554780'>Now</span>
  <span m='554920'>why</span> <span m='555150'>is</span> <span m='555290'>this</span>
  <span m='555510'>an</span> <span m='555590'>important</span> <span m='556080'>assumption?</span>
  <span m='558310'>So</span> <span m='558500'>what's</span> <span m='558770'>wrong</span>
  <span m='559080'>with</span> <span m='559200'>short</span> <span m='559590'>caches?</span>
  <span m='561030'>So</span> <span m='561610'>we're</span> <span m='561800'>going</span>
  <span m='561880'>to</span> <span m='561940'>look</span> <span m='562180'>at,</span>
  <span m='563730'>surprise,</span> <span m='564250'>surprise,</span> <span m='564910'>matrix</span>
  <span m='565330'>multiplication.</span> <span m='568950'>Which,</span> <span m='570460'>by</span>
  <span m='570640'>the</span> <span m='570810'>end</span> <span m='570970'>of</span>
  <span m='571050'>this</span> <span m='571230'>class</span> <span m='572190'>you</span>
  <span m='572400'>will</span> <span m='572610'>learn</span> <span m='572830'>more</span>
  <span m='573070'>algorithms</span> <span m='573600'>than</span> <span m='573680'>matrix</span>
  <span m='574080'>multiplication.</span> <span m='574890'>But</span> <span m='575070'>it</span>
  <span m='575180'>is</span> <span m='575370'>a</span> <span m='575410'>good</span>
  <span m='575620'>one</span> <span m='576370'>to</span> <span m='576520'>illustrate</span>
  <span m='577050'>things.</span> </p><p><span m='577940'>So</span> <span m='578130'>the</span>
  <span m='578270'>idea</span> <span m='578620'>here</span> <span m='578980'>is,</span>
  <span m='579200'>suppose</span> <span m='579680'>that</span> <span m='579800'>you</span>
  <span m='579920'>have</span> <span m='580050'>an</span> <span m='580190'>n by n</span>
  <span m='580850'>matrix</span> <span m='581320'>here.</span> <span m='583910'>And</span>
  <span m='585540'>you</span> <span m='585710'>don't</span> <span m='586030'>have</span>
  <span m='586260'>this</span> <span m='586440'>tall-cache</span> <span m='587320'>assumption.</span>
  <span m='589220'>So</span> <span m='589450'>where</span> <span m='589770'>your</span>
  <span m='590630'>cache is</span> <span m='591110'>short.</span> <span m='591890'>You
  have</span> <span m='591970'>a</span> <span m='592020'>lot</span> <span m='592340'>of</span>
  <span m='592420'>bytes</span> <span m='592770'>in</span> <span m='592830'>a</span>
  <span m='592890'>line,</span> <span m='593400'>but</span> <span m='593580'>very</span>
  <span m='593910'>few</span> <span m='594170'>lines.</span> </p><p><span m='595560'>Then</span>
  <span m='595840'>even</span> <span m='596250'>if</span> <span m='599350'>the</span>
  <span m='599700'>size</span> <span m='600180'>of</span> <span m='600280'>your</span>
  <span m='600420'>matrix</span> <span m='601170'>fits,</span> <span m='601870'>in</span>
  <span m='602090'>principle,</span> <span m='602820'>in</span> <span m='603060'>the</span>
  <span m='603180'>cache.</span> <span m='604460'>In</span> <span m='604940'>other</span>
  <span m='605070'>words,</span> <span m='605350'>n</span> <span m='605560'>squared</span>
  <span m='606000'>is</span> <span m='606190'>less</span> <span m='606470'>than</span>
  <span m='606660'>m</span> <span m='607160'>by</span> <span m='607500'>more</span>
  <span m='607780'>than</span> <span m='607920'>a</span> <span m='608010'>constant</span>
  <span m='608470'>amount.</span> <span m='609270'>So</span> <span m='609390'>you'd</span>
  <span m='609480'>say,</span> <span m='609670'>Oh gee,</span> <span m='610090'>that</span>
  <span m='610290'>ought</span> <span m='610450'>to</span> <span m='610500'>fit</span>
  <span m='610760'>in.</span> <span m='611620'>If</span> <span m='611740'>you</span>
  <span m='611840'>have</span> <span m='611930'>a</span> <span m='612020'>short</span>
  <span m='612390'>cache</span> <span m='613200'>it</span> <span m='613320'>doesn't</span>
  <span m='613610'>necessarily</span> <span m='614300'>fit</span> <span m='614520'>in</span>
  <span m='615750'>because</span> <span m='616810'>your</span> <span m='617270'>length</span>
  <span m='617620'>n</span> <span m='617870'>here</span> <span m='618210'>is</span>
  <span m='618330'>going</span> <span m='618410'>to</span> <span m='618500'>be</span>
  <span m='618620'>shorter</span> <span m='619690'>than</span> <span m='620450'>the</span>
  <span m='620870'>number</span> <span m='621200'>of</span> <span m='621260'>bytes</span>
  <span m='621630'>on</span> <span m='621710'>a</span> <span m='621790'>line.</span>
  </p><p><span m='623220'>However,</span> <span m='623420'>if</span> <span m='623540'>you</span>
  <span m='623660'>have</span> <span m='623820'>a</span> <span m='623980'>tall</span>
  <span m='624430'>cache,</span> <span m='624930'>it's</span> <span m='625110'>always</span>
  <span m='625600'>the</span> <span m='625700'>case</span> <span m='626200'>that</span>
  <span m='632150'>if</span> <span m='632310'>the</span> <span m='632460'>matrix</span>
  <span m='633400'>size</span> <span m='634560'>is</span> <span m='634680'>smaller</span>
  <span m='635100'>than</span> <span m='635250'>the</span> <span m='635400'>cache</span>
  <span m='635720'>size</span> <span m='636970'>by</span> <span m='637190'>a</span>
  <span m='637240'>certain</span> <span m='637520'>amount,</span> <span m='638200'>then</span>
  <span m='638550'>the</span> <span m='638660'>matrix</span> <span m='639170'>will</span>
  <span m='639360'>fit</span> <span m='639710'>in</span> <span m='639890'>the</span>
  <span m='639990'>cache.</span> <span m='641830'>OK,</span> <span m='642270'>question?</span>
  </p><p><span m='642665'>AUDIENCE:</span> <span m='643060'>Why wouldn't</span> <span
  m='643557'>you fit</span> <span m='644551'>more than</span> <span m='645048'>one
  row</span> <span m='645545'>per cache</span> <span m='646042'>line?</span> </p><p><span
  m='647036'>PROFESSOR:</span> <span m='647540'>Well</span> <span m='647810'>the</span>
  <span m='648080'>issue is</span> <span m='648290'>you</span> <span m='648550'>may</span>
  <span m='648680'>not</span> <span m='648890'>have</span> <span m='649090'>control</span>
  <span m='649600'>over</span> <span m='649750'>the</span> <span m='649820'>way</span>
  <span m='649990'>this</span> <span m='650190'>is</span> <span m='650320'>laid</span>
  <span m='650580'>out.</span> <span m='651770'>So,</span> <span m='651970'>for</span>
  <span m='652160'>example,</span> <span m='652500'>if</span> <span m='652590'>this</span>
  <span m='652750'>is</span> <span m='652870'>row-major</span> <span m='653460'>order,</span>
  <span m='654940'>and</span> <span m='655120'>this</span> <span m='655280'>is</span>
  <span m='655430'>a</span> <span m='655490'>submatrix</span> <span m='656310'>of</span>
  <span m='656430'>a</span> <span m='656480'>much</span> <span m='656740'>bigger</span>
  <span m='657090'>matrix,</span> <span m='658910'>then</span> <span m='659450'>you</span>
  <span m='659580'>may</span> <span m='659710'>not</span> <span m='659960'>have</span>
  <span m='660280'>the</span> <span m='660370'>freedom</span> <span m='660750'>to</span>
  <span m='660850'>be</span> <span m='661020'>using</span> <span m='661400'>these.</span>
  <span m='663020'>But</span> <span m='663200'>if</span> <span m='663380'>you</span>
  <span m='663480'>have</span> <span m='663590'>the</span> <span m='663700'>tall-cache</span>
  <span m='664400'>assumption,</span> <span m='664830'>then</span> <span m='665260'>any</span>
  <span m='665890'>section</span> <span m='666540'>you</span> <span m='666670'>pull</span>
  <span m='667010'>out</span> <span m='667330'>is</span> <span m='667500'>going</span>
  <span m='667640'>to</span> <span m='667690'>fit.</span> <span m='668130'>As</span>
  <span m='668260'>long</span> <span m='668530'>as</span> <span m='668640'>the</span>
  <span m='668750'>data</span> <span m='669790'>fits</span> <span m='671160'>mathematically</span>
  <span m='672150'>in</span> <span m='672270'>the</span> <span m='672360'>cache,</span>
  <span m='673470'>it</span> <span m='673590'>will</span> <span m='673790'>fit</span>
  <span m='674070'>practically</span> <span m='674650'>in</span> <span m='674740'>the</span>
  <span m='674850'>cache</span> <span m='675230'>if</span> <span m='675320'>you</span>
  <span m='675420'>have</span> <span m='675520'>the</span> <span m='675620'>tall-cache</span>
  <span m='676190'>assumption.</span> </p><p><span m='678390'>Whereas</span> <span
  m='678530'>if</span> <span m='678650'>it's</span> <span m='678770'>short,</span>
  <span m='680100'>you</span> <span m='680230'>basically</span> <span m='680850'>end</span>
  <span m='681100'>up</span> <span m='681870'>with</span> <span m='683320'>the</span>
  <span m='683440'>cache</span> <span m='683770'>lines</span> <span m='684090'>being</span>
  <span m='684360'>long</span> <span m='685090'>and</span> <span m='685320'>you</span>
  <span m='685430'>not</span> <span m='685720'>having</span> <span m='686110'>any</span>
  <span m='686270'>flexibility</span> <span m='686940'>as</span> <span m='687060'>to</span>
  <span m='687150'>where</span> <span m='687300'>the</span> <span m='687440'>data</span>
  <span m='687710'>goes.</span> <span m='688530'>So this is</span> <span m='688680'>sort</span>
  <span m='688930'>of</span> <span m='689470'>a--</span> <span m='690600'>So</span>
  <span m='690760'>any</span> <span m='690970'>questions</span> <span m='691480'>about</span>
  <span m='691780'>that</span> <span m='692000'>before</span> <span m='692380'>we</span>
  <span m='693070'>get</span> <span m='693270'>into</span> <span m='695710'>the</span>
  <span m='695900'>use</span> <span m='696120'>of</span> <span m='696180'>this?</span>
  <span m='696310'>We're going to</span> <span m='696570'>see</span> <span m='696830'>the</span>
  <span m='696900'>use</span> <span m='697180'>of</span> <span m='697290'>this and</span>
  <span m='697510'>where</span> <span m='697800'>it</span> <span m='697860'>comes</span>
  <span m='698130'>up.</span> </p><p><span m='698480'>So</span> <span m='698680'>one</span>
  <span m='698830'>of</span> <span m='698900'>the</span> <span m='698980'>things</span>
  <span m='699370'>is</span> <span m='699700'>that,</span> <span m='700530'>if</span>
  <span m='700740'>it</span> <span m='700890'>does</span> <span m='701220'>fit</span>
  <span m='701410'>in,</span> <span m='702050'>then</span> <span m='702250'>it</span>
  <span m='702430'>takes,</span> <span m='704090'>at</span> <span m='704370'>most,</span>
  <span m='704880'>size</span> <span m='707060'>of</span> <span m='707220'>the</span>
  <span m='707320'>matrix</span> <span m='707790'>divided</span> <span m='708280'>by</span>
  <span m='708870'>the</span> <span m='709050'>cache</span> <span m='709470'>line</span>
  <span m='709720'>size</span> <span m='710660'>misses</span> <span m='711180'>to</span>
  <span m='711290'>load</span> <span m='711540'>it</span> <span m='711650'>in.</span>
  <span m='713060'>So</span> <span m='713230'>this</span> <span m='713410'>is</span>
  <span m='713800'>linear</span> <span m='714220'>time</span> <span m='715890'>in</span>
  <span m='716250'>the</span> <span m='716370'>cache</span> <span m='716760'>world.</span>
  <span m='717090'>Linear</span> <span m='717360'>time</span> <span m='717830'>says,</span>
  <span m='718540'>you</span> <span m='718660'>should</span> <span m='718830'>only</span>
  <span m='719070'>take</span> <span m='719390'>one</span> <span m='719690'>cache</span>
  <span m='720110'>fault</span> <span m='720590'>for</span> <span m='720740'>every</span>
  <span m='721180'>line</span> <span m='721530'>of</span> <span m='721630'>cache.</span>
  <span m='723240'>And</span> <span m='723440'>so</span> <span m='723580'>that's</span>
  <span m='723850'>what</span> <span m='724010'>you'll</span> <span m='724180'>have</span>
  <span m='724460'>here</span> <span m='724840'>if</span> <span m='725040'>you</span>
  <span m='725130'>have</span> <span m='725220'>a</span> <span m='725320'>tall</span>
  <span m='725620'>cache.</span> <span m='726040'>You'll</span> <span m='726300'>have</span>
  <span m='726500'>n squared over b</span> <span m='727640'>cache</span> <span m='728000'>misses</span>
  <span m='728720'>to</span> <span m='728860'>load</span> <span m='729490'>in</span>
  <span m='729690'>n square</span> <span m='730050'>data.</span> <span m='731390'>And</span>
  <span m='732240'>that's</span> <span m='732530'>good.</span> <span m='736096'>OK,</span>
  <span m='736540'>good.</span> </p><p><span m='737550'>So</span> <span m='737720'>let's</span>
  <span m='737940'>take</span> <span m='738190'>on</span> <span m='738720'>the</span>
  <span m='738850'>problem</span> <span m='739230'>of</span> <span m='739310'>multiplying</span>
  <span m='740610'>matrices.</span> <span m='741220'>We're going to</span> <span m='741410'>look</span>
  <span m='741620'>at</span> <span m='741730'>square</span> <span m='742080'>matrices</span>
  <span m='742690'>because</span> <span m='742950'>they're</span> <span m='743610'>easier</span>
  <span m='743960'>to</span> <span m='744040'>think</span> <span m='744260'>about</span>
  <span m='744670'>than</span> <span m='745190'>rectangular</span> <span m='745730'>ones.</span>
  <span m='745900'>But</span> <span m='746010'>almost</span> <span m='746350'>everything</span>
  <span m='746780'>I</span> <span m='746860'>say</span> <span m='747140'>today</span>
  <span m='747950'>will</span> <span m='748290'>relate</span> <span m='748760'>to</span>
  <span m='748970'>rectangular</span> <span m='749780'>matrices</span> <span m='750390'>as</span>
  <span m='750520'>well.</span> <span m='753380'>And</span> <span m='753670'>it</span>
  <span m='753820'>we'll</span> <span m='754000'>generalize</span> <span m='754600'>beyond</span>
  <span m='754950'>matrices</span> <span m='755530'>as</span> <span m='755660'>we'll</span>
  <span m='755780'>see</span> <span m='755980'>next</span> <span m='756270'>time.</span>
  </p><p><span m='758450'>So</span> <span m='758600'>here's</span> <span m='758890'>a</span>
  <span m='758980'>typical</span> <span m='759410'>code</span> <span m='759750'>for</span>
  <span m='759850'>multiplying</span> <span m='760350'>matrices.</span> <span m='760900'>It's</span>
  <span m='761030'>not</span> <span m='761260'>the</span> <span m='761340'>most</span>
  <span m='761600'>efficient</span> <span m='762010'>code</span> <span m='762220'>in</span>
  <span m='762290'>the</span> <span m='762370'>world,</span> <span m='763120'>but</span>
  <span m='763450'>it's</span> <span m='763670'>good</span> <span m='763810'>enough</span>
  <span m='764030'>to</span> <span m='764130'>illustrate</span> <span m='766090'>what</span>
  <span m='766320'>I</span> <span m='766390'>want</span> <span m='766630'>to</span>
  <span m='766970'>show</span> <span m='767240'>you.</span> <span m='768180'>So</span>
  <span m='768380'>the</span> <span m='768570'>first</span> <span m='768770'>thing</span>
  <span m='769010'>is,</span> <span m='769470'>what</span> <span m='769850'>is</span>
  <span m='770030'>the</span> <span m='770130'>work</span> <span m='772140'>of</span>
  <span m='772280'>this</span> <span m='773960'>algorithm?</span> <span m='777460'>This</span>
  <span m='777650'>is,</span> <span m='777850'>by</span> <span m='777980'>the</span>
  <span m='778080'>way,</span> <span m='778700'>the</span> <span m='778770'>softball</span>
  <span m='779480'>question.</span> <span m='781240'>What's</span> <span m='781440'>the</span>
  <span m='781640'>work?</span> <span m='782680'>So</span> <span m='782840'>the</span>
  <span m='782930'>work,</span> <span m='783190'>remember,</span> <span m='783660'>is
  just</span> <span m='784750'>if</span> <span m='784880'>you're</span> <span m='785050'>analyzing</span>
  <span m='785730'>it</span> <span m='785860'>just</span> <span m='786080'>like</span>
  <span m='787610'>processor</span> <span m='788190'>forget</span> <span m='788480'>about</span>
  <span m='788730'>caches</span> <span m='789230'>and</span> <span m='789310'>so</span>
  <span m='789500'>forth.</span> </p><p><span m='790284'>AUDIENCE:</span> <span m='790698'>n
  cubed.</span> </p><p><span m='791526'>PROFESSOR:</span> <span m='791940'>n cubed,</span>
  <span m='792750'>right.</span> <span m='794110'>Because</span> <span m='794530'>there's</span>
  <span m='794720'>a</span> <span m='794790'>triply</span> <span m='795170'>nested</span>
  <span m='795550'>loop</span> <span m='796020'>going</span> <span m='796280'>up</span>
  <span m='796410'>to</span> <span m='796500'>n</span> <span m='797710'>and</span>
  <span m='797910'>you're</span> <span m='798040'>doing</span> <span m='798300'>constant</span>
  <span m='798780'>work</span> <span m='799030'>in</span> <span m='799100'>the</span>
  <span m='799170'>middle.</span> <span m='799470'>So</span> <span m='799610'>it's</span>
  <span m='799760'>n times n times 1.</span> <span m='803080'>n</span> <span m='803280'>cubed</span>
  <span m='803580'>work.</span> <span m='804920'>That</span> <span m='804980'>was</span>
  <span m='805140'>easy.</span> </p><p><span m='806620'>Now</span> <span m='806840'>let's</span>
  <span m='807060'>analyze</span> <span m='807510'>caches.</span> <span m='809460'>So</span>
  <span m='809580'>we're</span> <span m='809690'>going</span> <span m='809750'>to</span>
  <span m='809820'>look</span> <span m='809980'>at</span> <span m='810150'>row</span>
  <span m='810380'>major.</span> <span m='810800'>I'm</span> <span m='810940'>only</span>
  <span m='811130'>going</span> <span m='811230'>to</span> <span m='811530'>illustrate</span>
  <span m='812110'>the</span> <span m='812190'>cache</span> <span m='812580'>lines</span>
  <span m='812950'>on</span> <span m='813100'>this</span> <span m='813700'>side</span>
  <span m='814080'>because</span> <span m='814200'>B</span> <span m='814400'>is</span>
  <span m='814550'>where</span> <span m='814760'>all</span> <span m='814920'>the</span>
  <span m='815050'>action</span> <span m='815450'>is.</span> </p><p><span m='817310'>So</span>
  <span m='818140'>we're</span> <span m='818390'>going</span> <span m='818470'>to</span>
  <span m='818530'>analyze</span> <span m='819180'>two</span> <span m='819430'>cases</span>
  <span m='820100'>when</span> <span m='820300'>the</span> <span m='820390'>matrix</span>
  <span m='820930'>doesn't</span> <span m='821270'>fit</span> <span m='821490'>in</span>
  <span m='821620'>the</span> <span m='821700'>cache.</span> <span m='821990'>If</span>
  <span m='822080'>the</span> <span m='822180'>matrix</span> <span m='822650'>fits</span>
  <span m='822900'>in</span> <span m='822980'>the</span> <span m='823090'>cache,</span>
  <span m='824460'>then</span> <span m='824630'>there's</span> <span m='824780'>nothing</span>
  <span m='825080'>to</span> <span m='825140'>analyze,</span> <span m='826970'>at</span>
  <span m='827120'>some</span> <span m='827310'>level.</span> <span m='828160'>So</span>
  <span m='828280'>we're</span> <span m='828350'>going</span> <span m='828430'>to</span>
  <span m='828480'>look</span> <span m='828680'>at</span> <span m='828760'>the</span>
  <span m='828850'>cases</span> <span m='829290'>where</span> <span m='829400'>the</span>
  <span m='829500'>matrix</span> <span m='829950'>doesn't</span> <span m='830280'>fit</span>
  <span m='830430'>in</span> <span m='830530'>the</span> <span m='830620'>cache.</span>
  </p><p><span m='831440'>And</span> <span m='831620'>the</span> <span m='831680'>first</span>
  <span m='832030'>one</span> <span m='832180'>is</span> <span m='832300'>going</span>
  <span m='832390'>to</span> <span m='832490'>be</span> <span m='832690'>when</span>
  <span m='832990'>the</span> <span m='833080'>side</span> <span m='833530'>of</span>
  <span m='833590'>the</span> <span m='833700'>matrix</span> <span m='834320'>is</span>
  <span m='834520'>bigger</span> <span m='834920'>than</span> <span m='835160'>m over
  b.</span> <span m='836585'>So</span> <span m='836890'>remember,</span> <span m='837230'>m
  over b</span> <span m='837800'>is</span> <span m='837950'>the</span> <span m='838020'>height</span>
  <span m='838500'>of</span> <span m='838640'>our</span> <span m='838790'>cache,</span>
  <span m='839820'>the</span> <span m='839940'>number</span> <span m='840180'>of</span>
  <span m='840300'>lines</span> <span m='840770'>in</span> <span m='840860'>our</span>
  <span m='840980'>cache.</span> <span m='848320'>So</span> <span m='848580'>let's</span>
  <span m='848940'>assume</span> <span m='849540'>for</span> <span m='849730'>this,</span>
  <span m='850260'>now</span> <span m='850510'>I</span> <span m='850610'>have</span>
  <span m='850710'>a</span> <span m='850780'>choice</span> <span m='851220'>of</span>
  <span m='851300'>assuming</span> <span m='853480'>optimal</span> <span m='853950'>omniscient</span>
  <span m='854370'>replacement</span> <span m='855120'>or</span> <span m='855490'>assuming</span>
  <span m='855870'>LRU.</span> <span m='856760'>Since</span> <span m='857030'>I</span>
  <span m='857110'>want</span> <span m='857250'>to</span> <span m='857290'>show</span>
  <span m='857570'>this</span> <span m='857770'>is</span> <span m='857940'>bad,</span>
  <span m='859000'>I'm going to</span> <span m='859170'>assume</span> <span m='859540'>LRU.</span>
  </p><p><span m='861800'>Could</span> <span m='861950'>somebody</span> <span m='862290'>please</span>
  <span m='862590'>close</span> <span m='862910'>the</span> <span m='862980'>back</span>
  <span m='864570'>door</span> <span m='864790'>there?</span> <span m='865010'>Because</span>
  <span m='865250'>it's</span> <span m='865410'>we're</span> <span m='865560'>getting</span>
  <span m='865820'>some</span> <span m='865950'>noise</span> <span m='866300'>in</span>
  <span m='866440'>from</span> <span m='866590'>out</span> <span m='866770'>there.</span>
  <span m='869300'>Thank</span> <span m='869530'>you.</span> </p><p><span m='871350'>So</span>
  <span m='871480'>let's</span> <span m='871670'>assume</span> <span m='871990'>LRU.</span>
  <span m='872530'>So</span> <span m='872710'>what</span> <span m='872830'>happens</span>
  <span m='873340'>in</span> <span m='873520'>the</span> <span m='873620'>code</span>
  <span m='874120'>is</span> <span m='874300'>basically</span> <span m='875820'>I</span>
  <span m='875990'>go</span> <span m='876220'>across</span> <span m='876740'>a</span>
  <span m='876800'>row</span> <span m='877140'>of</span> <span m='877280'>A,</span>
  <span m='878630'>while</span> <span m='878900'>I</span> <span m='878980'>go</span>
  <span m='879190'>down</span> <span m='879620'>a</span> <span m='879690'>column</span>
  <span m='880160'>of</span> <span m='880230'>B.</span> <span m='881990'>And</span>
  <span m='882110'>now</span> <span m='882230'>if</span> <span m='882320'>I'm</span>
  <span m='882460'>using</span> <span m='882860'>LRU,</span> <span m='883650'>what's</span>
  <span m='883930'>happening?</span> </p><p><span m='884830'>I</span> <span m='884970'>read</span>
  <span m='885250'>in</span> <span m='885420'>this</span> <span m='885650'>cache</span>
  <span m='886330'>block</span> <span m='887000'>and</span> <span m='887210'>this</span>
  <span m='887390'>one,</span> <span m='887600'>then</span> <span m='887730'>this</span>
  <span m='887900'>one</span> <span m='888070'>et</span> <span m='888380'>cetera.</span>
  <span m='889080'>And</span> <span m='889460'>if</span> <span m='889730'>n</span>
  <span m='889970'>is</span> <span m='890160'>bigger</span> <span m='890570'>than</span>
  <span m='890760'>M/B</span> <span m='892400'>and</span> <span m='892570'>I'm</span>
  <span m='892680'>using</span> <span m='893020'>least</span> <span m='893300'>recently</span>
  <span m='893800'>used,</span> <span m='894300'>by</span> <span m='894440'>the</span>
  <span m='894570'>time</span> <span m='894900'>I</span> <span m='894970'>get</span>
  <span m='895190'>down</span> <span m='895420'>to</span> <span m='895530'>the</span>
  <span m='895600'>bottom</span> <span m='896020'>here,</span> <span m='896270'>what's</span>
  <span m='896470'>happened</span> <span m='896890'>the</span> <span m='896970'>first</span>
  <span m='897330'>cache</span> <span m='897690'>line?</span> <span m='900030'>First</span>
  <span m='900270'>cache</span> <span m='900530'>block?</span> <span m='902300'>It's</span>
  <span m='902510'>out</span> <span m='902700'>of</span> <span m='902770'>there.</span>
  <span m='904960'>It's</span> <span m='905280'>out</span> <span m='905470'>of</span>
  <span m='905690'>there if</span> <span m='905830'>I</span> <span m='905890'>used</span>
  <span m='906150'>LRU.</span> </p><p><span m='909490'>So</span> <span m='909680'>therefore,</span>
  <span m='910650'>what</span> <span m='910810'>happens</span> <span m='911270'>is</span>
  <span m='911390'>I</span> <span m='911480'>took</span> <span m='911720'>a</span>
  <span m='911780'>miss</span> <span m='912120'>on</span> <span m='912270'>every</span>
  <span m='912490'>one</span> <span m='912670'>of</span> <span m='912740'>those.</span>
  <span m='913860'>And</span> <span m='914010'>then</span> <span m='914160'>when</span>
  <span m='914340'>I</span> <span m='914390'>go</span> <span m='914600'>to</span>
  <span m='914850'>the</span> <span m='914960'>second</span> <span m='915360'>one,</span>
  <span m='915870'>I</span> <span m='916110'>take</span> <span m='916360'>a</span>
  <span m='916420'>miss</span> <span m='916670'>on</span> <span m='916790'>every</span>
  <span m='917010'>one</span> <span m='917200'>again.</span> <span m='921070'>And</span>
  <span m='921280'>so</span> <span m='921800'>as</span> <span m='922080'>I</span>
  <span m='922170'>keep</span> <span m='922430'>going</span> <span m='922720'>through,</span>
  <span m='923700'>every</span> <span m='924430'>access</span> <span m='925060'>to</span>
  <span m='925160'>B</span> <span m='926500'>causes</span> <span m='926860'>a</span>
  <span m='926920'>miss</span> <span m='927500'>throughout</span> <span m='927850'>the</span>
  <span m='927920'>whole</span> <span m='928230'>accessing</span> <span m='928740'>of</span>
  <span m='928800'>B.</span> <span m='929830'>Now</span> <span m='930040'>go</span>
  <span m='930250'>on</span> <span m='930410'>to</span> <span m='930500'>the</span>
  <span m='930590'>second</span> <span m='931000'>row</span> <span m='931250'>A</span>
  <span m='932120'>and</span> <span m='932350'>I</span> <span m='932430'>had</span>
  <span m='932560'>the</span> <span m='932640'>same</span> <span m='932940'>thing</span>
  <span m='933150'>repeats.</span> <span m='936280'>So</span> <span m='936470'>therefore,</span>
  <span m='937570'>the</span> <span m='937670'>number</span> <span m='937960'>of</span>
  <span m='938030'>cache</span> <span m='938500'>misses</span> <span m='939430'>is</span>
  <span m='939670'>order</span> <span m='940060'>n</span> <span m='940320'>cubed</span>
  <span m='944730'>since</span> <span m='946250'>we</span> <span m='946430'>miss</span>
  <span m='947150'>on</span> <span m='947300'>matrix</span> <span m='947450'>B</span>
  <span m='947860'>on</span> <span m='948050'>every</span> <span m='948400'>access.</span>
  <span m='950690'>OK,</span> <span m='950950'>question.</span> </p><p><span m='951868'>AUDIENCE:</span>
  <span m='952366'>I</span> <span m='952864'>know that</span> <span m='953362'>you
  said it's</span> <span m='953860'>e.</span> <span m='954856'>Does B push out</span>
  <span m='955354'>due to</span> <span m='955852'>conflict</span> <span m='956350'>misses</span>
  <span m='956848'>or</span> <span m='957346'>capacity</span> <span m='957844'>misses?</span>
  </p><p><span m='958342'>PROFESSOR:</span> <span m='958850'>So</span> <span m='960560'>in</span>
  <span m='960730'>this</span> <span m='960910'>case</span> <span m='962010'>they're</span>
  <span m='962180'>capacity</span> <span m='962740'>misses</span> <span m='963130'>that</span>
  <span m='963930'>we're</span> <span m='964060'>talking</span> <span m='964350'>about</span>
  <span m='964500'>here.</span> <span m='964820'>So</span> <span m='964990'>there's</span>
  <span m='965170'>no</span> <span m='965340'>conflict</span> <span m='965850'>misses</span>
  <span m='966350'>in</span> <span m='966480'>a</span> <span m='966620'>fully</span>
  <span m='966910'>associative</span> <span m='967480'>cache.</span> <span m='970490'>Conflict</span>
  <span m='970970'>misses</span> <span m='971200'>occurs</span> <span m='971700'>because</span>
  <span m='971940'>of</span> <span m='972040'>direct</span> <span m='972390'>mapping.</span>
  <span m='973070'>So</span> <span m='973240'>there's</span> <span m='973330'>no</span>
  <span m='973590'>conflict</span> <span m='974100'>misses</span> <span m='974580'>in</span>
  <span m='975360'>what</span> <span m='975560'>I'm</span> <span m='975640'>going</span>
  <span m='975720'>to</span> <span m='975780'>be</span> <span m='975890'>talking</span>
  <span m='976210'>about</span> <span m='976450'>today.</span> <span m='977030'>That</span>
  <span m='977220'>is</span> <span m='977460'>an</span> <span m='977550'>extra</span>
  <span m='977960'>concern</span> <span m='978410'>that</span> <span m='978500'>you</span>
  <span m='978800'>have</span> <span m='979270'>for</span> <span m='979400'>real</span>
  <span m='979680'>caches,</span> <span m='980550'>not</span> <span m='980790'>a</span>
  <span m='980840'>concern</span> <span m='981380'>when</span> <span m='981510'>you</span>
  <span m='981640'>have</span> <span m='981770'>a</span> <span m='981830'>fully</span>
  <span m='982120'>associative</span> <span m='982670'>cache.</span> </p><p><span
  m='983060'>AUDIENCE:</span> <span m='983533'>[INAUDIBLE]</span> <span m='985425'>n</span>
  <span m='985898'>needs</span> <span m='986371'>to be</span> <span m='986844'>bigger</span>
  <span m='987317'>than</span> <span m='987790'>B?</span> </p><p><span m='988736'>PROFESSOR:</span>
  <span m='989220'>So</span> <span m='991930'>the</span> <span m='992030'>number</span>
  <span m='992360'>of</span> <span m='992420'>lines</span> <span m='992780'>to</span>
  <span m='992900'>fit</span> <span m='993130'>in</span> <span m='993230'>my</span>
  <span m='993390'>cache</span> <span m='993900'>is</span> <span m='994090'>m</span>
  <span m='994310'>over</span> <span m='994560'>b,</span> <span m='996240'>right?</span>
  </p><p><span m='996720'>AUDIENCE:</span> <span m='997200'>So can't you put multiple</span>
  <span m='997658'>units of data--</span> </p><p><span m='999490'>PROFESSOR:</span>
  <span m='999950'>Well</span> <span m='1000070'>there</span> <span m='1000230'>are</span>
  <span m='1000440'>multiple</span> <span m='1000880'>units</span> <span m='1001200'>of</span>
  <span m='1001340'>data.</span> <span m='1001690'>But</span> <span m='1001910'>notice</span>
  <span m='1002250'>this</span> <span m='1002380'>is</span> <span m='1002520'>row</span>
  <span m='1002760'>major,</span> <span m='1003800'>what's</span> <span m='1004000'>stored</span>
  <span m='1004420'>here</span> <span m='1004830'>is</span> <span m='1005610'>B11,</span>
  <span m='1006580'>B12,</span> <span m='1007730'>B13.</span> <span m='1009060'>That's</span>
  <span m='1009340'>stored</span> <span m='1009660'>here.</span> <span m='1010110'>The</span>
  <span m='1010210'>way</span> <span m='1010550'>I'm</span> <span m='1010660'>going</span>
  <span m='1010940'>through</span> <span m='1011120'>the</span> <span m='1011260'>access,</span>
  <span m='1011810'>I'm</span> <span m='1011920'>going</span> <span m='1012210'>down</span>
  <span m='1012500'>the</span> <span m='1012600'>columns</span> <span m='1013180'>of</span>
  <span m='1013270'>B.</span> <span m='1015240'>So</span> <span m='1015430'>by</span>
  <span m='1015530'>the</span> <span m='1015740'>time</span> <span m='1016020'>to</span>
  <span m='1016070'>get</span> <span m='1016250'>up</span> <span m='1016390'>to</span>
  <span m='1016480'>the</span> <span m='1016600'>top</span> <span m='1016920'>again,</span>
  <span m='1018570'>that</span> <span m='1019370'>cache</span> <span m='1019670'>block</span>
  <span m='1020050'>is</span> <span m='1020180'>no</span> <span m='1020330'>longer</span>
  <span m='1020660'>there.</span> </p><p><span m='1021320'>And</span> <span m='1021460'>so</span>
  <span m='1021580'>when</span> <span m='1021720'>I</span> <span m='1021790'>access</span>
  <span m='1022370'>B12,</span> <span m='1025069'>assuming</span> <span m='1025819'>indexing</span>
  <span m='1026310'>from</span> <span m='1026490'>one</span> <span m='1026720'>or</span>
  <span m='1026800'>whatever,</span> <span m='1028420'>this</span> <span m='1028720'>block</span>
  <span m='1029089'>is</span> <span m='1029260'>no</span> <span m='1029400'>longer</span>
  <span m='1029790'>in</span> <span m='1029900'>cache.</span> <span m='1032220'>Because</span>
  <span m='1032490'>LRU</span> <span m='1033020'>would</span> <span m='1033190'>say,</span>
  <span m='1033900'>somewhere</span> <span m='1034319'>along</span> <span m='1034670'>here</span>
  <span m='1035020'>I</span> <span m='1035130'>hit</span> <span m='1035400'>the</span>
  <span m='1035480'>limit</span> <span m='1035750'>of</span> <span m='1035819'>my</span>
  <span m='1036240'>size</span> <span m='1036640'>of</span> <span m='1036720'>cache,</span>
  <span m='1037619'>let's</span> <span m='1037800'>say</span> <span m='1037980'>around</span>
  <span m='1038400'>here.</span> <span m='1039109'>Then</span> <span m='1039300'>when</span>
  <span m='1039440'>this</span> <span m='1039619'>one</span> <span m='1039829'>goes</span>
  <span m='1040130'>in,</span> <span m='1040589'>that</span> <span m='1040890'>one</span>
  <span m='1041050'>goes</span> <span m='1041319'>out.</span> <span m='1041609'>When</span>
  <span m='1041740'>the</span> <span m='1041900'>next</span> <span m='1042060'>one</span>
  <span m='1042200'>goes</span> <span m='1042440'>in,</span> <span m='1042609'>the</span>
  <span m='1042700'>next</span> <span m='1042990'>one</span> <span m='1043160'>goes</span>
  <span m='1043400'>out</span> <span m='1043599'>et</span> <span m='1043710'>cetera</span>
  <span m='1044349'>using</span> <span m='1044650'>the</span> <span m='1044740'>least</span>
  <span m='1045069'>recently</span> <span m='1045660'>used</span> <span m='1046030'>replacement.</span>
  <span m='1047660'>So</span> <span m='1047839'>my--</span> </p><p><span m='1048329'>AUDIENCE:</span>
  <span m='1048726'>Spatial locality.</span> </p><p><span m='1049520'>PROFESSOR:</span>
  <span m='1049920'>I'm</span> <span m='1050030'>sorry?</span> <span m='1050930'>You</span>
  <span m='1051070'>don't</span> <span m='1051220'>have</span> <span m='1051360'>any</span>
  <span m='1051540'>spatial</span> <span m='1051950'>locality</span> <span m='1052470'>here.</span>
  </p><p><span m='1053300'>AUDIENCE:</span> <span m='1053790'>I'm</span> <span m='1054280'>just</span>
  <span m='1054770'>wondering</span> <span m='1055260'>why</span> <span m='1055750'>they</span>
  <span m='1056240'>can't</span> <span m='1056730'>hold</span> <span m='1057220'>units.</span>
  <span m='1057710'>I</span> <span m='1058200'>guess</span> <span m='1058690'>this
  is the</span> <span m='1059180'>question,</span> <span m='1059670'>why can't they</span>
  <span m='1060160'>hold</span> <span m='1060650'>multiple</span> <span m='1061140'>addresses</span>
  <span m='1061630'>per</span> <span m='1062120'>cache line.</span> <span m='1062610'>So
  why</span> <span m='1063100'>is</span> <span m='1063590'>it even</span> <span m='1064080'>pushed</span>
  <span m='1064570'>out?</span> <span m='1065550'>It's</span> <span m='1065648'>being</span>
  <span m='1065746'>pushed</span> <span m='1065844'>out</span> <span m='1065942'>[UNINTELLIGIBLE]</span>
  <span m='1066040'>one</span> <span m='1066530'>per cache</span> <span m='1067020'>line,</span>
  <span m='1067530'>right?</span> </p><p><span m='1068010'>PROFESSOR:</span> <span
  m='1068295'>No,</span> <span m='1068580'>so</span> <span m='1068720'>it's</span>
  <span m='1068830'>getting</span> <span m='1069320'>pushed</span> <span m='1069610'>out</span>
  <span m='1069800'>because</span> <span m='1070760'>the</span> <span m='1070900'>cache</span>
  <span m='1071370'>can</span> <span m='1071540'>hold</span> <span m='1071930'>M/B</span>
  <span m='1074130'>blocks,</span> <span m='1075760'>right?</span> <span m='1076820'>So</span>
  <span m='1077500'>once</span> <span m='1077920'>it's</span> <span m='1078090'>accessed</span>
  <span m='1078910'>m over b</span> <span m='1079340'>blocks,</span> <span m='1079890'>if</span>
  <span m='1080030'>I</span> <span m='1080110'>want</span> <span m='1080270'>to</span>
  <span m='1080320'>access</span> <span m='1080730'>anything</span> <span m='1081130'>else,</span>
  <span m='1081460'>something</span> <span m='1081850'>has</span> <span m='1082140'>to</span>
  <span m='1082240'>go</span> <span m='1082480'>out.</span> <span m='1083820'>It's
  a</span> <span m='1083970'>capacity</span> <span m='1084590'>issue.</span> <span
  m='1085480'>I</span> <span m='1085590'>access</span> <span m='1086010'>m over b</span>
  <span m='1086550'>blocks,</span> <span m='1087300'>something</span> <span m='1087660'>has
  to</span> <span m='1087850'>go out.</span> </p><p><span m='1088550'>LRU</span> <span
  m='1089230'>says,</span> <span m='1091460'>the</span> <span m='1091610'>latest</span>
  <span m='1092100'>thing</span> <span m='1092390'>that</span> <span m='1092540'>I</span>
  <span m='1092670'>accessed,</span> <span m='1093320'>well</span> <span m='1093470'>that</span>
  <span m='1093660'>was</span> <span m='1093790'>the</span> <span m='1093880'>first</span>
  <span m='1094220'>one,</span> <span m='1094570'>gets</span> <span m='1094910'>knocked</span>
  <span m='1095240'>out.</span> <span m='1096610'>So</span> <span m='1096840'>what</span>
  <span m='1096980'>happens</span> <span m='1097450'>is</span> <span m='1098260'>every</span>
  <span m='1098600'>one</span> <span m='1098950'>causes</span> <span m='1099400'>a</span>
  <span m='1099480'>miss.</span> <span m='1100030'>Even</span> <span m='1100310'>though</span>
  <span m='1100420'>I</span> <span m='1100930'>may</span> <span m='1101240'>access</span>
  <span m='1101700'>that</span> <span m='1102010'>very</span> <span m='1102310'>nearby</span>
  <span m='1102870'>in</span> <span m='1102960'>the</span> <span m='1103050'>future,</span>
  <span m='1104700'>it</span> <span m='1104900'>doesn't</span> <span m='1105530'>take</span>
  <span m='1105780'>advantage</span> <span m='1106230'>of</span> <span m='1106300'>that.</span>
  <span m='1107040'>Because</span> <span m='1107330'>LRU</span> <span m='1107880'>says</span>
  <span m='1108190'>knock</span> <span m='1108470'>it</span> <span m='1108550'>out.</span>
  </p><p><span m='1109342'>AUDIENCE:</span> <span m='1109784'>[INAUDIBLE]</span> </p><p><span
  m='1111552'>PROFESSOR:</span> <span m='1112000'>Is</span> <span m='1112420'>it</span>
  <span m='1112610'>row</span> <span m='1112750'>major</span> <span m='1113120'>that's</span>
  <span m='1113570'>the</span> <span m='1114440'>confusion?</span> <span m='1114880'>This</span>
  <span m='1115120'>is the</span> <span m='1115200'>way</span> <span m='1115340'>we've</span>
  <span m='1115550'>been</span> <span m='1116150'>dealing</span> <span m='1116460'>with</span>
  <span m='1116600'>are</span> <span m='1116710'>matrices.</span> <span m='1117300'>So
  in</span> <span m='1117590'>row</span> <span m='1117770'>major,</span> <span m='1119580'>there's</span>
  <span m='1119670'>a</span> <span m='1119760'>good--</span> <span m='1121490'>that's</span>
  <span m='1121840'>nice,</span> <span m='1122180'>there's</span> <span m='1122390'>no</span>
  <span m='1122520'>chalk</span> <span m='1122870'>here.</span> <span m='1127320'>Oh,</span>
  <span m='1127780'>there's</span> <span m='1128000'>a</span> <span m='1128040'>big</span>
  <span m='1128200'>one</span> <span m='1128320'>there,</span> <span m='1128490'>great.</span>
  </p><p><span m='1133520'>Yeah,</span> <span m='1134470'>so</span> <span m='1134650'>here's</span>
  <span m='1135000'>B. </span> <span m='1136810'>So</span> <span m='1136990'>the</span>
  <span m='1137140'>order</span> <span m='1139020'>that</span> <span m='1139380'>B
  </span> <span m='1139610'>is</span> <span m='1139720'>stored</span> <span m='1140200'>is</span>
  <span m='1140360'>like</span> <span m='1140600'>this</span> <span m='1142080'>in</span>
  <span m='1142250'>memory.</span> <span m='1144290'>So</span> <span m='1144440'>basically</span>
  <span m='1145050'>we're</span> <span m='1145180'>storing</span> <span m='1146620'>these</span>
  <span m='1147050'>elements</span> <span m='1147540'>in</span> <span m='1147710'>this</span>
  <span m='1147910'>order.</span> <span m='1148790'>So</span> <span m='1148940'>it's</span>
  <span m='1149060'>a</span> <span m='1149110'>linear</span> <span m='1149730'>block</span>
  <span m='1150090'>of</span> <span m='1150190'>memory,</span> <span m='1151610'>right?</span>
  <span m='1151900'>And</span> <span m='1152030'>it's</span> <span m='1152160'>being</span>
  <span m='1152340'>stored</span> <span m='1153200'>row</span> <span m='1153430'>by</span>
  <span m='1153630'>row</span> <span m='1154180'>as</span> <span m='1154370'>we</span>
  <span m='1154450'>go</span> <span m='1154640'>through.</span> </p><p><span m='1156250'>So</span>
  <span m='1156550'>actually</span> <span m='1156910'>if</span> <span m='1157060'>I</span>
  <span m='1158000'>do</span> <span m='1158190'>it</span> <span m='1158270'>like</span>
  <span m='1158520'>this,</span> <span m='1158810'>let</span> <span m='1158910'>me</span>
  <span m='1159890'>do this</span> <span m='1160030'>a</span> <span m='1160080'>little</span>
  <span m='1160190'>bit</span> <span m='1160340'>more.</span> <span m='1162950'>So</span>
  <span m='1163110'>the</span> <span m='1163260'>idea</span> <span m='1163620'>is</span>
  <span m='1164070'>that</span> <span m='1164420'>the</span> <span m='1164550'>first</span>
  <span m='1164990'>element</span> <span m='1165340'>is</span> <span m='1165490'>going</span>
  <span m='1165590'>to</span> <span m='1165630'>be</span> <span m='1165770'>here,</span>
  <span m='1168320'>and</span> <span m='1168460'>then</span> <span m='1168590'>we</span>
  <span m='1168700'>get</span> <span m='1168870'>up</span> <span m='1169020'>to</span>
  <span m='1169150'>n minus 1,</span> <span m='1170600'>and</span> <span m='1170770'>then</span>
  <span m='1170940'>we</span> <span m='1171060'>get</span> <span m='1171260'>to</span>
  <span m='1171540'>n minus 2</span> <span m='1172530'>is</span> <span m='1172630'>stored</span>
  <span m='1173000'>here.</span> <span m='1175956'>n</span> <span m='1176390'>plus</span>
  <span m='1176760'>1,</span> <span m='1177560'>n</span> <span m='1177880'>plus</span>
  <span m='1178310'>2,</span> <span m='1180900'>2n minus 1.</span> <span m='1182150'>So</span>
  <span m='1182300'>that's</span> <span m='1182510'>the</span> <span m='1182660'>order</span>
  <span m='1183000'>that</span> <span m='1183170'>they're</span> <span m='1183300'>stored</span>
  <span m='1184270'>in</span> <span m='1184340'>linear</span> <span m='1184750'>and</span>
  <span m='1184830'>memory.</span> </p><p><span m='1185830'>Now</span> <span m='1185940'>these</span>
  <span m='1186250'>guys</span> <span m='1186560'>will</span> <span m='1186710'>all</span>
  <span m='1186920'>be</span> <span m='1187070'>on</span> <span m='1187160'>the</span>
  <span m='1187250'>same</span> <span m='1187570'>cache</span> <span m='1187950'>line</span>
  <span m='1189410'>if</span> <span m='1189520'>it's</span> <span m='1189690'>in</span>
  <span m='1189750'>row-major</span> <span m='1190370'>storage.</span> <span m='1192020'>So</span>
  <span m='1192200'>when</span> <span m='1192310'>I'm</span> <span m='1192420'>accessing</span>
  <span m='1193050'>B, </span> <span m='1193440'>I'm</span> <span m='1193560'>going</span>
  <span m='1193880'>and</span> <span m='1193960'>I'm</span> <span m='1194080'>accessing</span>
  <span m='1194680'>zero,</span> <span m='1195680'>then</span> <span m='1195820'>I'm</span>
  <span m='1195920'>accessing</span> <span m='1196860'>the</span> <span m='1196980'>thing</span>
  <span m='1197180'>at</span> <span m='1197300'>location</span> <span m='1197890'>n.</span>
  <span m='1200390'>And</span> <span m='1200520'>I'm</span> <span m='1200630'>going</span>
  <span m='1200920'>down</span> <span m='1201160'>like</span> <span m='1201380'>this.</span>
  </p><p><span m='1201820'>At</span> <span m='1202010'>some</span> <span m='1202320'>point</span>
  <span m='1202610'>here</span> <span m='1203310'>I</span> <span m='1203470'>reach</span>
  <span m='1204990'>the</span> <span m='1205110'>limit</span> <span m='1205560'>of</span>
  <span m='1205740'>my</span> <span m='1206690'>cache.</span> <span m='1207180'>This</span>
  <span m='1207380'>is</span> <span m='1207560'>M/B.</span> <span m='1211030'>Notice</span>
  <span m='1211300'>it's</span> <span m='1211440'>a</span> <span m='1211490'>different</span>
  <span m='1211770'>B--</span> <span m='1212050'>script</span> <span m='1212460'>B</span>
  <span m='1212630'>verses--</span> <span m='1213840'>so</span> <span m='1214100'>when</span>
  <span m='1214320'>I</span> <span m='1214380'>get</span> <span m='1214600'>to</span>
  <span m='1214900'>m over b.</span> <span m='1215990'>Now</span> <span m='1216480'>all</span>
  <span m='1216780'>these</span> <span m='1217050'>things</span> <span m='1217360'>are</span>
  <span m='1217420'>sitting</span> <span m='1217760'>in</span> <span m='1217880'>cache,</span>
  <span m='1218920'>that's</span> <span m='1219140'>great.</span> <span m='1220590'>However,</span>
  <span m='1220930'>now</span> <span m='1221210'>I</span> <span m='1221300'>go</span>
  <span m='1221630'>to</span> <span m='1221800'>one</span> <span m='1222060'>more,</span>
  <span m='1222950'>and</span> <span m='1223150'>it says</span> <span m='1223370'>OK,</span>
  <span m='1225270'>all</span> <span m='1225490'>those</span> <span m='1225770'>things</span>
  <span m='1226140'>are</span> <span m='1226310'>sitting</span> <span m='1227130'>in</span>
  <span m='1227600'>cache,</span> <span m='1228020'>which</span> <span m='1228340'>one</span>
  <span m='1228520'>do</span> <span m='1228650'>I</span> <span m='1228750'>kick</span>
  <span m='1229070'>out?</span> <span m='1229440'>And the</span> <span m='1229540'>answer</span>
  <span m='1229850'>is</span> <span m='1230020'>the</span> <span m='1230130'>least</span>
  <span m='1230590'>recently</span> <span m='1231120'>used</span> <span m='1231480'>one.</span>
  <span m='1231970'>That's</span> <span m='1232260'>this</span> <span m='1232510'>guy</span>
  <span m='1232690'>goes</span> <span m='1232970'>out.</span> </p><p><span m='1233380'>AUDIENCE:</span>
  <span m='1233823'>Do you only</span> <span m='1234266'>use one</span> <span m='1234709'>element</span>
  <span m='1235152'>per cache link?</span> </p><p><span m='1235595'>PROFESSOR:</span>
  <span m='1236040'>And</span> <span m='1236510'>I've</span> <span m='1236620'>only</span>
  <span m='1236820'>used</span> <span m='1237010'>one</span> <span m='1237240'>element</span>
  <span m='1237620'>from</span> <span m='1237760'>each</span> <span m='1237930'>cache</span>
  <span m='1238260'>line</span> <span m='1238700'>at this</span> <span m='1239050'>point.</span>
  <span m='1239680'>Then</span> <span m='1239840'>I</span> <span m='1239890'>go</span>
  <span m='1240110'>to</span> <span m='1240180'>the</span> <span m='1240410'>next</span>
  <span m='1240640'>one</span> <span m='1241570'>and it</span> <span m='1241850'>knocks</span>
  <span m='1242190'>out</span> <span m='1242370'>the</span> <span m='1242450'>second</span>
  <span m='1242790'>one.</span> <span m='1243330'>By</span> <span m='1243550'>the</span>
  <span m='1243650'>time</span> <span m='1243900'>I</span> <span m='1243950'>get</span>
  <span m='1244140'>to</span> <span m='1244220'>the</span> <span m='1244310'>bottom</span>
  <span m='1245510'>and</span> <span m='1245650'>then</span> <span m='1245760'>I</span>
  <span m='1245810'>go</span> <span m='1245980'>up</span> <span m='1246090'>to</span>
  <span m='1246180'>the</span> <span m='1246270'>top</span> <span m='1246580'>to</span>
  <span m='1246670'>access</span> <span m='1247960'>1</span> <span m='1248250'>here,</span>
  <span m='1248530'>it's</span> <span m='1248670'>not</span> <span m='1248890'>in</span>
  <span m='1249020'>cache.</span> <span m='1249930'>And</span> <span m='1250070'>so</span>
  <span m='1250160'>it</span> <span m='1250230'>repeats</span> <span m='1250730'>the</span>
  <span m='1250820'>same</span> <span m='1251170'>process,</span> <span m='1251770'>missing</span>
  <span m='1252250'>every</span> <span m='1252520'>single</span> <span m='1252830'>time.</span>
  <span m='1253400'>We</span> <span m='1253550'>have</span> <span m='1253610'>a</span>
  <span m='1253670'>question.</span> </p><p><span m='1254100'>AUDIENCE:</span> <span
  m='1254543'>Yeah,so</span> <span m='1254986'>my question</span> <span m='1255430'>is</span>
  <span m='1256110'>why</span> <span m='1256240'>does</span> <span m='1256515'>the</span>
  <span m='1256790'>cache</span> <span m='1257080'>know</span> <span m='1260320'>where</span>
  <span m='1260680'>each</span> <span m='1260860'>row</span> <span m='1261115'>is?</span>
  <span m='1261370'>To</span> <span m='1261862'>us,</span> <span m='1262354'>we</span>
  <span m='1262846'>draw</span> <span m='1263338'>the</span> <span m='1263830'>matrix,</span>
  <span m='1264322'>but</span> <span m='1264814'>the</span> <span m='1265306'>computer</span>
  <span m='1265798'>doesn't know it's</span> <span m='1266290'>a matrix.</span> <span
  m='1267274'>To the</span> <span m='1267766'>computer,</span> <span m='1268258'>its
  a</span> <span m='1268750'>linear array of numbers.</span> </p><p><span m='1269250'>PROFESSOR:</span>
  <span m='1269490'>That's</span> <span m='1269870'>correct.</span> </p><p><span m='1270370'>AUDIENCE:</span>
  <span m='1270695'>So why would</span> <span m='1271020'>it</span> <span m='1272140'>load</span>
  <span m='1273340'>the</span> <span m='1273550'>first</span> <span m='1274990'>couple</span>
  <span m='1275430'>elements</span> <span m='1275870'>in the first</span> <span m='1276310'>row,
  and</span> <span m='1276750'>the second column</span> <span m='1277190'>is an extended
  row</span> <span m='1277630'>the second time.</span> </p><p><span m='1281455'>PROFESSOR:</span>
  <span m='1281890'>So</span> <span m='1282430'>the</span> <span m='1282590'>cache</span>
  <span m='1282970'>blocks</span> <span m='1283470'>are</span> <span m='1283700'>determined</span>
  <span m='1284240'>by</span> <span m='1285040'>the</span> <span m='1285140'>locality</span>
  <span m='1285730'>and</span> <span m='1285830'>memory.</span> </p><p><span m='1287415'>AUDIENCE:</span>
  <span m='1287730'>So</span> <span m='1288187'>my assumption would be</span> <span
  m='1289558'>the</span> <span m='1290015'>first</span> <span m='1290472'>cache</span>
  <span m='1290929'>line</span> <span m='1291386'>for</span> <span m='1291850'>say--</span>
  </p><p><span m='1292255'>PROFESSOR:</span> <span m='1292660'>Let's</span> <span
  m='1292820'>say</span> <span m='1292950'>0</span> <span m='1293260'>through</span>
  <span m='1293960'>3.</span> </p><p><span m='1294330'>AUDIENCE:</span> <span m='1294820'>So
  yeah,</span> <span m='1295310'>0 through 3.</span> </p><p><span m='1295680'>PROFESSOR:</span>
  <span m='1296010'>Let's</span> <span m='1296080'>say we</span> <span m='1296330'>have</span>
  <span m='1296640'>four</span> <span m='1296950'>items</span> <span m='1297320'>on</span>
  <span m='1297430'>that</span> <span m='1297590'>cache</span> <span m='1297810'>line.</span>
  </p><p><span m='1297980'>AUDIENCE:</span> <span m='1298430'>4 to 6.</span> </p><p><span
  m='1299040'>PROFESSOR:</span> <span m='1299230'>The next</span> <span m='1299490'>one</span>
  <span m='1299590'>the</span> <span m='1299710'>hold</span> <span m='1300200'>4</span>
  <span m='1300610'>to</span> <span m='1301690'>7,</span> <span m='1302190'>I think.</span>
  </p><p><span m='1302664'>AUDIENCE:</span> <span m='1303138'>4 to 7,</span> <span
  m='1303612'>yeah.</span> <span m='1304086'>So</span> <span m='1304560'>that is a--</span>
  </p><p><span m='1305034'>PROFESSOR:</span> <span m='1305510'>So</span> <span m='1305780'>that
  would</span> <span m='1306090'>be the next one,</span> <span m='1306570'>right?</span>
  <span m='1308010'>4 to</span> <span m='1308280'>7.</span> </p><p><span m='1308715'>AUDIENCE:</span>
  <span m='1309150'>When you get</span> <span m='1309592'>cache</span> <span m='1310034'>line.</span>
  <span m='1310476'>You are not</span> <span m='1310918'>using the</span> <span m='1311360'>fully
  cache</span> <span m='1311802'>line.</span> <span m='1312250'>There is no</span>
  <span m='1312640'>spatial</span> <span m='1313130'>locale.</span> <span m='1313620'>You
  are</span> <span m='1314110'>using</span> <span m='1314600'>one from the cache line.</span>
  </p><p><span m='1315062'>PROFESSOR:</span> <span m='1315524'>So</span> <span m='1318710'>this</span>
  <span m='1318890'>code</span> <span m='1319040'>is</span> <span m='1319220'>using</span>
  <span m='1319485'>this</span> <span m='1319750'>one</span> <span m='1320020'>and</span>
  <span m='1320180'>then</span> <span m='1320400'>this</span> <span m='1320620'>one.</span>
  <span m='1320820'>It's</span> <span m='1320940'>not</span> <span m='1321180'>using</span>
  <span m='1321530'>the</span> <span m='1321630'>rest.</span> <span m='1321870'>So</span>
  <span m='1322080'>it's</span> <span m='1322210'>not</span> <span m='1322590'>very</span>
  <span m='1322890'>efficient</span> <span m='1323290'>code.</span> </p><p><span m='1323690'>AUDIENCE:</span>
  <span m='1324090'>So</span> <span m='1324572'>the</span> <span m='1325054'>cache</span>
  <span m='1325536'>line</span> <span m='1326018'>is</span> <span m='1326500'>holding</span>
  <span m='1326982'>the</span> <span m='1327464'>0 to 3</span> <span m='1327946'>and
  the</span> <span m='1328428'>4 to 7.</span> <span m='1329874'>[INAUDIBLE]</span>
  <span m='1331320'>n plus 2</span> <span m='1332560'>just</span> <span m='1332830'>reading--</span>
  </p><p><span m='1333320'>[INTERPOSING VOICES]</span> </p><p><span m='1334955'>PROFESSOR:</span>
  <span m='1335380'>Right.</span> <span m='1335990'>And</span> <span m='1336150'>those
  are</span> <span m='1336560'>fixed.</span> <span m='1337340'>So</span> <span m='1337930'>if</span>
  <span m='1338060'>you</span> <span m='1338140'>just</span> <span m='1338420'>a</span>
  <span m='1338490'>dice</span> <span m='1338890'>up</span> <span m='1339040'>memory</span>
  <span m='1339800'>in</span> <span m='1340520'>our</span> <span m='1340640'>machine</span>
  <span m='1341040'>into</span> <span m='1341150'>64 byte</span> <span m='1342100'>sizes,</span>
  <span m='1343890'>those</span> <span m='1344190'>are</span> <span m='1344230'>the</span>
  <span m='1344450'>things</span> <span m='1344790'>that</span> <span m='1344920'>come</span>
  <span m='1345160'>in</span> <span m='1345320'>together</span> <span m='1346050'>whenever</span>
  <span m='1346460'>you</span> <span m='1346540'>access</span> <span m='1347070'>anything</span>
  <span m='1347490'>on</span> <span m='1347710'>that</span> <span m='1347900'>line.</span>
  </p><p><span m='1348220'>AUDIENCE:</span> <span m='1348713'>And on</span> <span
  m='1349206'>this</span> <span m='1349699'>particular</span> <span m='1350192'>axis,</span>
  <span m='1351178'>you never</span> <span m='1351671'>actually</span> <span m='1352164'>get</span>
  <span m='1352657'>the</span> <span m='1353150'>4 to the 7</span> <span m='1353643'>in
  the--</span> </p><p><span m='1354136'>PROFESSOR:</span> <span m='1354640'>Well</span>
  <span m='1354820'>we</span> <span m='1355010'>eventually</span> <span m='1355250'>do.</span>
  <span m='1356390'>Until</span> <span m='1356530'>we</span> <span m='1356630'>get</span>
  <span m='1356790'>there,</span> <span m='1357195'>yes,</span> <span m='1357600'>that's</span>
  <span m='1358005'>right.</span> <span m='1358410'>Until</span> <span m='1358550'>we</span>
  <span m='1358660'>get</span> <span m='1358860'>there.</span> </p><p><span m='1360130'>Now,</span>
  <span m='1360250'>of</span> <span m='1360320'>course,</span> <span m='1360830'>we're</span>
  <span m='1361030'>also</span> <span m='1361300'>accessing</span> <span m='1361930'>A</span>
  <span m='1362170'>and</span> <span m='1362350'>C,</span> <span m='1363140'>but</span>
  <span m='1363370'>turns</span> <span m='1363600'>out</span> <span m='1363800'>to</span>
  <span m='1363870'>this</span> <span m='1364050'>analysis</span> <span m='1364680'>it</span>
  <span m='1364810'>sufficient</span> <span m='1365370'>to</span> <span m='1365470'>show</span>
  <span m='1366490'>that</span> <span m='1366690'>we're</span> <span m='1367010'>getting</span>
  <span m='1367450'>n cubed</span> <span m='1369930'>misses</span> <span m='1371680'>just</span>
  <span m='1371940'>on</span> <span m='1372040'>the</span> <span m='1372120'>matrix</span>
  <span m='1372550'>B.</span> <span m='1374140'>In</span> <span m='1374240'>order</span>
  <span m='1374400'>to</span> <span m='1374460'>say</span> <span m='1374780'>hey,</span>
  <span m='1376080'>we've</span> <span m='1376210'>got</span> <span m='1376340'>a</span>
  <span m='1376370'>lot</span> <span m='1376590'>of</span> <span m='1376640'>misses</span>
  <span m='1377000'>here.</span> </p><p><span m='1380170'>So</span> <span m='1380300'>this</span>
  <span m='1380510'>was</span> <span m='1380690'>the</span> <span m='1380790'>case</span>
  <span m='1381220'>where</span> <span m='1381490'>n</span> <span m='1381840'>was</span>
  <span m='1382080'>bigger</span> <span m='1383080'>than</span> <span m='1383270'>the</span>
  <span m='1383350'>size</span> <span m='1383760'>of</span> <span m='1383820'>a</span>
  <span m='1383900'>cache.</span> <span m='1385290'>So</span> <span m='1385440'>the</span>
  <span m='1385500'>situation</span> <span m='1386000'>is</span> <span m='1386520'>a</span>
  <span m='1387300'>little</span> <span m='1387580'>bit</span> <span m='1387810'>different</span>
  <span m='1388370'>if</span> <span m='1388600'>n</span> <span m='1389060'>is</span>
  <span m='1389490'>large</span> <span m='1390630'>but</span> <span m='1393690'>still</span>
  <span m='1394310'>actually</span> <span m='1394730'>less</span> <span m='1395190'>than</span>
  <span m='1395830'>m over b.</span> </p><p><span m='1397560'>So</span> <span m='1397730'>in</span>
  <span m='1397790'>this</span> <span m='1398020'>case,</span> <span m='1399650'>we</span>
  <span m='1399850'>suppose</span> <span m='1400340'>it</span> <span m='1400500'>n
  squared</span> <span m='1401920'>is</span> <span m='1402810'>bigger</span> <span
  m='1403120'>than</span> <span m='1403440'>m.</span> <span m='1404410'>So</span>
  <span m='1404600'>the</span> <span m='1404680'>matrix</span> <span m='1405140'>doesn't</span>
  <span m='1405480'>fit</span> <span m='1405670'>in</span> <span m='1405820'>memory.</span>
  <span m='1407520'>So</span> <span m='1407710'>that's</span> <span m='1407940'>what</span>
  <span m='1408120'>this</span> <span m='1408400'>part</span> <span m='1408650'>of</span>
  <span m='1408760'>the</span> <span m='1409030'>equation</span> <span m='1409460'>is,</span>
  <span m='1409680'>m to the 1/2  less than n</span> <span m='1411300'>is</span> <span
  m='1411410'>the</span> <span m='1411470'>same</span> <span m='1411780'>as</span>
  <span m='1411970'>n squared</span> <span m='1413310'>is</span> <span m='1413500'>bigger</span>
  <span m='1413760'>than</span> <span m='1413920'>memory.</span> <span m='1414210'>So</span>
  <span m='1414330'>we</span> <span m='1414400'>still</span> <span m='1414680'>don't</span>
  <span m='1414920'>fit</span> <span m='1415080'>in</span> <span m='1415220'>memory,</span>
  <span m='1416210'>but</span> <span m='1416380'>in</span> <span m='1416510'>fact</span>
  <span m='1417640'>it's</span> <span m='1417900'>less</span> <span m='1418290'>than</span>
  <span m='1418450'>some</span> <span m='1418690'>constant</span> <span m='1419260'>times</span>
  <span m='1419600'>m</span> <span m='1419820'>over</span> <span m='1420030'>b.</span>
  </p><p><span m='1421320'>And</span> <span m='1421430'>now</span> <span m='1421580'>let's</span>
  <span m='1421820'>look</span> <span m='1422060'>at</span> <span m='1422140'>the</span>
  <span m='1422230'>difference</span> <span m='1423520'>with</span> <span m='1423700'>what</span>
  <span m='1423860'>happens</span> <span m='1424600'>with the caches</span> <span
  m='1426550'>as</span> <span m='1426740'>we</span> <span m='1426830'>go</span> <span
  m='1426980'>through</span> <span m='1427170'>the</span> <span m='1427320'>algorithm.</span>
  <span m='1428290'>So</span> <span m='1428460'>we</span> <span m='1428600'>essentially</span>
  <span m='1429050'>do</span> <span m='1429190'>the</span> <span m='1429300'>same</span>
  <span m='1429690'>thing.</span> <span m='1429960'>Once</span> <span m='1430120'>again,</span>
  <span m='1430290'>we're</span> <span m='1430430'>going to assume</span> <span m='1430810'>LRU.</span>
  </p><p><span m='1432270'>And</span> <span m='1432440'>so</span> <span m='1432580'>what</span>
  <span m='1432690'>happens</span> <span m='1433130'>is</span> <span m='1433250'>we're</span>
  <span m='1433380'>going</span> <span m='1433470'>to</span> <span m='1433510'>go</span>
  <span m='1433710'>down</span> <span m='1434570'>a</span> <span m='1434670'>single</span>
  <span m='1435060'>row</span> <span m='1435340'>there.</span> <span m='1436320'>But</span>
  <span m='1436560'>now,</span> <span m='1437380'>notice</span> <span m='1437850'>that</span>
  <span m='1438030'>by</span> <span m='1438150'>the</span> <span m='1438270'>time</span>
  <span m='1438570'>I</span> <span m='1438630'>get</span> <span m='1438830'>down</span>
  <span m='1439070'>to</span> <span m='1439170'>the</span> <span m='1439270'>bottom,</span>
  <span m='1448870'>basically</span> <span m='1449310'>I've</span> <span m='1449640'>accessed</span>
  <span m='1449800'>fewer</span> <span m='1450160'>than</span> <span m='1450380'>some</span>
  <span m='1450610'>constant</span> <span m='1451090'>times</span> <span m='1451440'>m
  over b</span> <span m='1452380'>locations.</span> <span m='1454410'>And</span> <span
  m='1454570'>so</span> <span m='1454800'>nothing</span> <span m='1455240'>has</span>
  <span m='1455410'>gotten</span> <span m='1455720'>kicked</span> <span m='1456020'>out</span>
  <span m='1456280'>yet.</span> </p><p><span m='1457460'>So</span> <span m='1457630'>when</span>
  <span m='1457770'>I</span> <span m='1457820'>go</span> <span m='1458010'>back</span>
  <span m='1458370'>to</span> <span m='1458460'>the</span> <span m='1458610'>top</span>
  <span m='1460750'>for</span> <span m='1460880'>the</span> <span m='1460980'>next</span>
  <span m='1463360'>access</span> <span m='1463810'>to</span> <span m='1463910'>B,</span>
  <span m='1464580'>all</span> <span m='1464880'>these</span> <span m='1465120'>things</span>
  <span m='1465400'>are</span> <span m='1465480'>still</span> <span m='1465860'>in</span>
  <span m='1466000'>memory.</span> <span m='1469150'>So</span> <span m='1469370'>I</span>
  <span m='1469440'>don't</span> <span m='1469740'>take</span> <span m='1470060'>a</span>
  <span m='1470430'>cache fall,</span> <span m='1471510'>a</span> <span m='1471700'>cache</span>
  <span m='1472020'>miss</span> <span m='1472260'>in</span> <span m='1472370'>those</span>
  <span m='1472590'>cases.</span> <span m='1475030'>And</span> <span m='1475200'>so</span>
  <span m='1475360'>we</span> <span m='1475520'>keep</span> <span m='1475760'>going</span>
  <span m='1476040'>through.</span> </p><p><span m='1476470'>And</span> <span m='1476590'>basically</span>
  <span m='1477130'>this</span> <span m='1477290'>is</span> <span m='1477410'>much</span>
  <span m='1477680'>better</span> <span m='1478420'>because</span> <span m='1480550'>we're</span>
  <span m='1480810'>actually</span> <span m='1481040'>getting</span> <span m='1481710'>to</span>
  <span m='1481850'>take</span> <span m='1482100'>advantage</span> <span m='1482560'>of</span>
  <span m='1482670'>the</span> <span m='1482770'>spatial</span> <span m='1483230'>locality.</span>
  <span m='1484310'>So</span> <span m='1484490'>this</span> <span m='1484630'>algorithm</span>
  <span m='1485060'>takes</span> <span m='1485460'>advantage</span> <span m='1485910'>of</span>
  <span m='1485970'>the</span> <span m='1486670'>spatial</span> <span m='1487150'>locality.</span>
  <span m='1488580'>If</span> <span m='1489140'>n</span> <span m='1489310'>is</span>
  <span m='1489620'>really</span> <span m='1489940'>big</span> <span m='1490220'>it</span>
  <span m='1490380'>doesn't,</span> <span m='1491870'>but</span> <span m='1492030'>if</span>
  <span m='1492220'>n</span> <span m='1493380'>is</span> <span m='1493810'>just</span>
  <span m='1494180'>kind</span> <span m='1494540'>of</span> <span m='1494590'>big,</span>
  <span m='1497040'>then</span> <span m='1497210'>it</span> <span m='1497340'>does.</span>
  <span m='1499300'>And</span> <span m='1499700'>then if</span> <span m='1499900'>n</span>
  <span m='1500170'>is small</span> <span m='1500440'>enough,</span> <span m='1500650'>of</span>
  <span m='1500750'>course,</span> <span m='1501700'>it</span> <span m='1501850'>all</span>
  <span m='1502020'>fits</span> <span m='1502870'>in</span> <span m='1503510'>cache</span>
  <span m='1503900'>and</span> <span m='1504010'>there's</span> <span m='1504170'>no</span>
  <span m='1504320'>misses</span> <span m='1505090'>other</span> <span m='1505310'>than</span>
  <span m='1505510'>those</span> <span m='1505820'>needed</span> <span m='1506100'>to</span>
  <span m='1506170'>bring</span> <span m='1506490'>it</span> <span m='1506580'>in</span>
  <span m='1506750'>once.</span> <span m='1509820'>And</span> <span m='1509940'>then</span>
  <span m='1510070'>the</span> <span m='1510150'>same</span> <span m='1510410'>thing</span>
  <span m='1510570'>happens</span> <span m='1511000'>once</span> <span m='1511180'>you</span>
  <span m='1512290'>go</span> <span m='1512440'>through</span> <span m='1512610'>the</span>
  <span m='1512710'>next</span> <span m='1513000'>one.</span> </p><p><span m='1513820'>So</span>
  <span m='1514020'>in</span> <span m='1514080'>this</span> <span m='1514300'>case,</span>
  <span m='1514630'>what's</span> <span m='1514800'>happening</span> <span m='1515270'>is</span>
  <span m='1518080'>we</span> <span m='1518250'>have</span> <span m='1518470'>n squared
  over b</span> <span m='1520750'>misses</span> <span m='1521320'>per</span> <span
  m='1522300'>run</span> <span m='1522630'>through</span> <span m='1523850'>the</span>
  <span m='1524030'>matrix</span> <span m='1524510'>B,</span> <span m='1525310'>and</span>
  <span m='1525640'>then</span> <span m='1526690'>we</span> <span m='1526920'>have</span>
  <span m='1527130'>n times</span> <span m='1527760'>that</span> <span m='1527930'>we</span>
  <span m='1528040'>go</span> <span m='1528270'>through.</span> <span m='1528510'>Once</span>
  <span m='1528730'>for</span> <span m='1528910'>every</span> <span m='1529140'>row</span>
  <span m='1529570'>of</span> <span m='1529956'>A.</span> <span m='1531240'>So</span>
  <span m='1531380'>the</span> <span m='1531500'>total</span> <span m='1531900'>then</span>
  <span m='1532130'>is</span> <span m='1532320'>n cubed over b</span> <span m='1534250'>the</span>
  <span m='1534410'>cache</span> <span m='1536160'>block</span> <span m='1536510'>size.</span>
  </p><p><span m='1537700'>So</span> <span m='1538400'>depending</span> <span m='1538750'>upon</span>
  <span m='1539080'>the</span> <span m='1539150'>size,</span> <span m='1539900'>we</span>
  <span m='1540030'>can</span> <span m='1540180'>analyze</span> <span m='1540750'>with</span>
  <span m='1540900'>this,</span> <span m='1541440'>that</span> <span m='1543050'>this</span>
  <span m='1543220'>is</span> <span m='1543360'>better</span> <span m='1544030'>because</span>
  <span m='1544230'>we</span> <span m='1544330'>get</span> <span m='1544460'>a</span>
  <span m='1544510'>factor</span> <span m='1544910'>of</span> <span m='1545020'>B</span>
  <span m='1545190'>improvement.</span> <span m='1547730'>But</span> <span m='1547980'>it's</span>
  <span m='1548070'>still</span> <span m='1548450'>not</span> <span m='1548800'>particularly</span>
  <span m='1549260'>good.</span> <span m='1549550'>And</span> <span m='1549660'>it</span>
  <span m='1549750'>only</span> <span m='1550040'>works,</span> <span m='1550440'>of</span>
  <span m='1550560'>course,</span> <span m='1550990'>if</span> <span m='1551710'>my</span>
  <span m='1556780'>side</span> <span m='1557170'>of</span> <span m='1557240'>my</span>
  <span m='1557400'>matrix</span> <span m='1557980'>fits</span> <span m='1558280'>in</span>
  <span m='1559480'>the</span> <span m='1559670'>number</span> <span m='1559930'>of</span>
  <span m='1560000'>lines</span> <span m='1560340'>of</span> <span m='1560400'>cache</span>
  <span m='1560740'>that</span> <span m='1560880'>I</span> <span m='1560950'>have.</span>
  <span m='1562780'>Yeah,</span> <span m='1562980'>question.</span> </p><p><span m='1563345'>AUDIENCE:</span>
  <span m='1563710'>Can you</span> <span m='1564183'>explain</span> <span m='1564656'>in--</span>
  <span m='1565129'>I don't understand</span> <span m='1565602'>why you</span> <span
  m='1566075'>have</span> <span m='1566548'>n cubed over b?</span> </p><p><span m='1567494'>PROFESSOR:</span>
  <span m='1567970'>OK,</span> <span m='1568870'>so</span> <span m='1569790'>we're</span>
  <span m='1569910'>going</span> <span m='1570210'>through</span> <span m='1570490'>this</span>
  <span m='1570740'>matrix</span> <span m='1571270'>n</span> <span m='1571510'>times.</span>
  <span m='1572590'>And</span> <span m='1572750'>for</span> <span m='1572860'>each</span>
  <span m='1573110'>one</span> <span m='1573290'>of</span> <span m='1573360'>those,</span>
  <span m='1573660'>we're</span> <span m='1573780'>running</span> <span m='1574100'>through</span>
  <span m='1574290'>this</span> <span m='1574540'>thing.</span> <span m='1576440'>So</span>
  <span m='1577070'>this</span> <span m='1577450'>thing</span> <span m='1577670'>basically,</span>
  <span m='1579210'>I</span> <span m='1579360'>get</span> <span m='1579590'>to</span>
  <span m='1579660'>go</span> <span m='1580160'>b times</span> <span m='1580910'>through,</span>
  <span m='1581920'>because</span> <span m='1582170'>all</span> <span m='1582480'>these</span>
  <span m='1582690'>things</span> <span m='1582930'>are</span> <span m='1583000'>going</span>
  <span m='1583110'>to</span> <span m='1583180'>be</span> <span m='1583320'>in</span>
  <span m='1583430'>memory</span> <span m='1584050'>when</span> <span m='1584340'>I</span>
  <span m='1584400'>come</span> <span m='1584600'>back</span> <span m='1584890'>to</span>
  <span m='1585040'>do</span> <span m='1585230'>them</span> <span m='1585390'>again.</span>
  </p><p><span m='1586580'>And</span> <span m='1586720'>so</span> <span m='1586840'>it's</span>
  <span m='1586960'>only</span> <span m='1587300'>once</span> <span m='1587680'>every</span>
  <span m='1588030'>B</span> <span m='1590310'>columns</span> <span m='1591510'>that</span>
  <span m='1591640'>I</span> <span m='1591710'>take</span> <span m='1591990'>a</span>
  <span m='1592050'>miss.</span> <span m='1592740'>I</span> <span m='1592840'>take</span>
  <span m='1593060'>a</span> <span m='1593120'>miss</span> <span m='1593440'>and</span>
  <span m='1593550'>then</span> <span m='1593700'>I</span> <span m='1594000'>get</span>
  <span m='1594250'>to</span> <span m='1594440'>the</span> <span m='1594610'>other</span>
  <span m='1594780'>b minus 1</span> <span m='1596420'>access</span> <span m='1596910'>is</span>
  <span m='1597220'>that</span> <span m='1597390'>I</span> <span m='1597560'>get</span>
  <span m='1597780'>cache</span> <span m='1598160'>hit.</span> <span m='1600120'>And</span>
  <span m='1600280'>so</span> <span m='1600740'>the</span> <span m='1600890'>total</span>
  <span m='1601310'>here</span> <span m='1601680'>is</span> <span m='1601980'>then</span>
  <span m='1602380'>n squared over b.</span> <span m='1604790'>So</span> <span m='1605030'>therefore
  a</span> <span m='1605420'>total</span> <span m='1605720'>of</span> <span m='1605820'>n
  cubed over b.</span> <span m='1609120'>So</span> <span m='1609950'>even</span> <span
  m='1610260'>this</span> <span m='1610490'>is</span> <span m='1610630'>not</span>
  <span m='1610900'>very</span> <span m='1611120'>good</span> <span m='1611370'>compared</span>
  <span m='1611780'>to</span> <span m='1612050'>what</span> <span m='1612380'>we</span>
  <span m='1612490'>can</span> <span m='1612630'>actually</span> <span m='1612950'>do</span>
  <span m='1613130'>if</span> <span m='1613250'>we</span> <span m='1613330'>exploit</span>
  <span m='1613760'>the</span> <span m='1613840'>cache</span> <span m='1614180'>well.</span>
  </p><p><span m='1617780'>So</span> <span m='1617920'>let's</span> <span m='1618150'>go</span>
  <span m='1618350'>on</span> <span m='1618510'>and</span> <span m='1618620'>take</span>
  <span m='1618840'>a</span> <span m='1618910'>look.</span> <span m='1619150'>We</span>
  <span m='1619250'>saw</span> <span m='1619540'>this</span> <span m='1619780'>before.</span>
  <span m='1620660'>Let's</span> <span m='1620950'>use</span> <span m='1621220'>tiling.</span>
  </p><p><span m='1623710'>So</span> <span m='1623960'>the</span> <span m='1624110'>idea</span>
  <span m='1624390'>of</span> <span m='1624480'>tiling</span> <span m='1625280'>is</span>
  <span m='1625510'>to</span> <span m='1625620'>say,</span> <span m='1627190'>let's</span>
  <span m='1628450'>break</span> <span m='1628870'>our</span> <span m='1629030'>matrix</span>
  <span m='1629950'>into</span> <span m='1630220'>blocks</span> <span m='1630900'>of</span>
  <span m='1631180'>s times s</span> <span m='1632270'>size.</span> <span m='1634510'>And</span>
  <span m='1634660'>essentially</span> <span m='1635150'>what</span> <span m='1635350'>we</span>
  <span m='1635490'>do</span> <span m='1636400'>is</span> <span m='1637340'>we</span>
  <span m='1638160'>treat</span> <span m='1639000'>our</span> <span m='1639200'>big</span>
  <span m='1639460'>matrix</span> <span m='1643200'>as</span> <span m='1643420'>if</span>
  <span m='1643540'>we're</span> <span m='1643620'>doing</span> <span m='1643830'>block</span>
  <span m='1644250'>matrix</span> <span m='1644650'>multiplications</span> <span m='1645460'>of</span>
  <span m='1645570'>things</span> <span m='1645870'>of</span> <span m='1645960'>size</span>
  <span m='1646380'>s by s.</span> </p><p><span m='1648300'>So</span> <span m='1648490'>the</span>
  <span m='1648630'>inner</span> <span m='1648870'>loop</span> <span m='1649190'>here</span>
  <span m='1649990'>is</span> <span m='1650220'>doing</span> <span m='1650490'>essentially</span>
  <span m='1651180'>the</span> <span m='1651910'>matrix</span> <span m='1652360'>multiplication.</span>
  <span m='1653710'>It's</span> <span m='1653890'>actually</span> <span m='1655650'>matrix</span>
  <span m='1656020'>multiply and</span> <span m='1656280'>add.</span> <span m='1659020'>The</span>
  <span m='1659350'>inner</span> <span m='1659570'>three</span> <span m='1659890'>loops</span>
  <span m='1660190'>are</span> <span m='1660260'>just</span> <span m='1660460'>doing</span>
  <span m='1660690'>ordinary</span> <span m='1661170'>matrix</span> <span m='1661500'>multiplication,</span>
  <span m='1662150'>but</span> <span m='1662260'>on</span> <span m='1662540'>s-sized</span>
  <span m='1663860'>matrices.</span> </p><p><span m='1665210'>And</span> <span m='1665280'>the</span>
  <span m='1665390'>outer</span> <span m='1665750'>loop</span> <span m='1666040'>is</span>
  <span m='1666240'>jumping</span> <span m='1666630'>over</span> <span m='1668830'>matrix</span>
  <span m='1669310'>by</span> <span m='1669490'>matrix</span> <span m='1674110'>for</span>
  <span m='1674280'>each</span> <span m='1674490'>of</span> <span m='1674570'>those</span>
  <span m='1674880'>doing</span> <span m='1675120'>a</span> <span m='1675170'>matrix</span>
  <span m='1675580'>multiply</span> <span m='1676200'>as</span> <span m='1676350'>its</span>
  <span m='1676520'>elemental</span> <span m='1677070'>piece.</span> <span m='1678450'>So</span>
  <span m='1678610'>this</span> <span m='1678800'>is</span> <span m='1678910'>the</span>
  <span m='1679020'>tiling</span> <span m='1679460'>solution</span> <span m='1679880'>that</span>
  <span m='1679960'>you've</span> <span m='1680100'>seen</span> <span m='1680330'>before.</span>
  <span m='1681430'>We</span> <span m='1681590'>can</span> <span m='1681720'>analyze</span>
  <span m='1682320'>it</span> <span m='1682420'>in</span> <span m='1682520'>this</span>
  <span m='1682710'>model</span> <span m='1683130'>to</span> <span m='1683230'>see,</span>
  <span m='1683920'>is</span> <span m='1684120'>this</span> <span m='1684300'>a</span>
  <span m='1684360'>good</span> <span m='1684550'>solution.</span> <span m='1687250'>So</span>
  <span m='1687510'>everybody</span> <span m='1687930'>clear</span> <span m='1688230'>on</span>
  <span m='1688310'>what</span> <span m='1688460'>the</span> <span m='1688540'>code</span>
  <span m='1688800'>does?</span> <span m='1690740'>So</span> <span m='1690950'>it's</span>
  <span m='1691910'>a</span> <span m='1691990'>lot</span> <span m='1692140'>of</span>
  <span m='1692280'>four</span> <span m='1692580'>loops,</span> <span m='1692880'>right?</span>
  <span m='1694737'>Yeah.</span> </p><p><span m='1695226'>AUDIENCE:</span> <span m='1695715'>There
  should be</span> <span m='1697182'>less</span> <span m='1697671'>than</span> <span
  m='1698160'>n</span> <span m='1698649'>somewhere?</span> <span m='1699138'>There's
  like</span> <span m='1699627'>an and</span> <span m='1700116'>something.</span>
  </p><p><span m='1700610'>PROFESSOR:</span> <span m='1700950'>Oh</span> <span m='1701230'>yeah.</span>
  <span m='1702354'>That</span> <span m='1702776'>must</span> <span m='1703198'>have</span>
  <span m='1703620'>happened</span> <span m='1704060'>when</span> <span m='1704270'>I</span>
  <span m='1704730'>coped</span> <span m='1704920'>it.</span> <span m='1705100'>That
  should</span> <span m='1705230'>be</span> <span m='1705870'>j less than n</span>
  <span m='1706620'>here.</span> <span m='1707490'>It</span> <span m='1707540'>should</span>
  <span m='1707850'>just</span> <span m='1708050'>follow</span> <span m='1708330'>this</span>
  <span m='1708615'>pattern.</span> <span m='1709732'>i</span> <span m='1710150'>less
  than n,</span> <span m='1710810'>k less than n,</span> <span m='1711410'>that</span>
  <span m='1711560'>should</span> <span m='1711670'>be</span> <span m='1711770'>j
  less than n</span> <span m='1712250'>there.</span> </p><p><span m='1715830'>Good</span>
  <span m='1716010'>catch.</span> <span m='1717880'>I</span> <span m='1717990'>did</span>
  <span m='1718180'>execute</span> <span m='1718690'>this.</span> <span m='1719270'>That
  must have</span> <span m='1719370'>happened</span> <span m='1719690'>when</span>
  <span m='1719840'>I</span> <span m='1719940'>was</span> <span m='1720030'>editing.</span>
  </p><p><span m='1723520'>So</span> <span m='1723690'>here's</span> <span m='1723920'>the</span>
  <span m='1724010'>analysis</span> <span m='1724610'>of</span> <span m='1724700'>work.</span>
  <span m='1725870'>So</span> <span m='1726040'>what's</span> <span m='1726230'>going</span>
  <span m='1726490'>on</span> <span m='1726660'>in</span> <span m='1726750'>the</span>
  <span m='1726830'>work?</span> <span m='1728990'>So</span> <span m='1729480'>here</span>
  <span m='1729680'>we</span> <span m='1729880'>have,</span> <span m='1730280'>basically</span>
  <span m='1731070'>the</span> <span m='1731240'>outer</span> <span m='1731580'>loop</span>
  <span m='1731930'>is</span> <span m='1732530'>going</span> <span m='1732930'>n</span>
  <span m='1733720'>over</span> <span m='1734410'>s</span> <span m='1735120'>times,</span>
  <span m='1737160'>each</span> <span m='1737430'>loop.</span> <span m='1737880'>So</span>
  <span m='1738050'>there's</span> <span m='1738310'>cube</span> <span m='1738650'>there</span>
  <span m='1738970'>times</span> <span m='1739470'>the</span> <span m='1739650'>inner
  loops</span> <span m='1740220'>here</span> <span m='1740730'>which</span> <span
  m='1741050'>are</span> <span m='1741110'>going</span> <span m='1741780'>each</span>
  <span m='1742540'>s</span> <span m='1742820'>times.</span> <span m='1743430'>So</span>
  <span m='1743620'>times</span> <span m='1743920'>s cubed.</span> </p><p><span m='1744790'>Multiply</span>
  <span m='1745210'>that</span> <span m='1745480'>through,</span> <span m='1746170'>n</span>
  <span m='1746370'>cubed</span> <span m='1746660'>operations.</span> <span m='1747250'>That's</span>
  <span m='1747490'>kind</span> <span m='1747650'>of</span> <span m='1747710'>what</span>
  <span m='1747870'>you'd</span> <span m='1747990'>expect.</span> <span m='1750810'>What</span>
  <span m='1750980'>about</span> <span m='1751310'>cache</span> <span m='1751920'>misses?</span>
  </p><p><span m='1755320'>So</span> <span m='1755490'>the</span> <span m='1755680'>whole</span>
  <span m='1755980'>idea</span> <span m='1756410'>here</span> <span m='1756860'>is</span>
  <span m='1757190'>that</span> <span m='1757470'>s</span> <span m='1757890'>becomes</span>
  <span m='1758260'>a</span> <span m='1758340'>tuning</span> <span m='1758710'>parameter.</span>
  <span m='1759520'>And</span> <span m='1759730'>whether</span> <span m='1760030'>we</span>
  <span m='1760550'>choose</span> <span m='1760940'>s</span> <span m='1761240'>well</span>
  <span m='1761620'>or</span> <span m='1761720'>poorly</span> <span m='1762780'>influences</span>
  <span m='1763600'>how</span> <span m='1763820'>well</span> <span m='1764060'>this</span>
  <span m='1764240'>algorithm</span> <span m='1764690'>works.</span> <span m='1767430'>So</span>
  <span m='1767630'>the</span> <span m='1767770'>idea</span> <span m='1768110'>here</span>
  <span m='1768420'>is</span> <span m='1768530'>we</span> <span m='1768600'>want</span>
  <span m='1768820'>tune</span> <span m='1768930'>s</span> <span m='1769980'>so</span>
  <span m='1770210'>that</span> <span m='1770350'>the</span> <span m='1770480'>submatrices</span>
  <span m='1771620'>just</span> <span m='1772110'>fit</span> <span m='1772260'>into</span>
  <span m='1772500'>cache.</span> </p><p><span m='1773570'>So</span> <span m='1773950'>in</span>
  <span m='1774080'>this</span> <span m='1774290'>case,</span> <span m='1774710'>if</span>
  <span m='1774900'>I</span> <span m='1774970'>want</span> <span m='1775440'>a</span>
  <span m='1775550'>matrix</span> <span m='1775920'>to</span> <span m='1776010'>fit</span>
  <span m='1776160'>into</span> <span m='1776370'>cache,</span> <span m='1777080'>I</span>
  <span m='1777230'>want</span> <span m='1777560'>to</span> <span m='1777650'>be</span>
  <span m='1777820'>about</span> <span m='1778300'>the</span> <span m='1778390'>size</span>
  <span m='1778810'>of</span> <span m='1778940'>the</span> <span m='1779000'>square</span>
  <span m='1779470'>root</span> <span m='1779830'>of</span> <span m='1780000'>the</span>
  <span m='1780100'>cache</span> <span m='1780470'>size.</span> <span m='1783350'>And</span>
  <span m='1783470'>this</span> <span m='1783600'>is</span> <span m='1783750'>where</span>
  <span m='1784010'>we're</span> <span m='1784140'>going</span> <span m='1784220'>to</span>
  <span m='1784260'>use</span> <span m='1784510'>the</span> <span m='1784600'>tall-cache</span>
  <span m='1785250'>assumption</span> <span m='1785730'>now.</span> <span m='1787090'>Because</span>
  <span m='1787410'>I</span> <span m='1787470'>want</span> <span m='1787640'>to</span>
  <span m='1787680'>say,</span> <span m='1788330'>it</span> <span m='1788520'>fits</span>
  <span m='1788770'>in</span> <span m='1788910'>cache,</span> <span m='1789270'>therefore</span>
  <span m='1792060'>I</span> <span m='1792260'>can</span> <span m='1792410'>just</span>
  <span m='1792620'>assume</span> <span m='1793000'>it</span> <span m='1793190'>all</span>
  <span m='1793410'>fits</span> <span m='1793670'>in</span> <span m='1793790'>cache.</span>
  <span m='1794220'>It's</span> <span m='1794380'>not</span> <span m='1794550'>like</span>
  <span m='1795060'>the</span> <span m='1795160'>size</span> <span m='1795730'>fits</span>
  <span m='1796100'>but</span> <span m='1796350'>the</span> <span m='1796890'>actual</span>
  <span m='1797290'>data</span> <span m='1797610'>doesn't,</span> <span m='1798220'>which</span>
  <span m='1798420'>is</span> <span m='1798520'>what</span> <span m='1798640'>happens</span>
  <span m='1799050'>with</span> <span m='1799140'>the</span> <span m='1799230'>short</span>
  <span m='1799570'>cache.</span> </p><p><span m='1801900'>So</span> <span m='1802420'>the</span>
  <span m='1802740'>tall-cache</span> <span m='1803380'>assumption</span> <span m='1803820'>implies</span>
  <span m='1804940'>that</span> <span m='1805070'>when</span> <span m='1805230'>I'm</span>
  <span m='1805320'>executing</span> <span m='1805990'>one</span> <span m='1806140'>of</span>
  <span m='1806210'>these</span> <span m='1806430'>inner</span> <span m='1806640'>loops,</span>
  <span m='1807700'>what's</span> <span m='1808180'>happening?</span> <span m='1809660'>When</span>
  <span m='1809790'>I'm</span> <span m='1810020'>executing</span> <span m='1810260'>one</span>
  <span m='1810380'>of</span> <span m='1810430'>these</span> <span m='1810630'>linear</span>
  <span m='1810900'>loops,</span> <span m='1811560'>all</span> <span m='1811890'>of</span>
  <span m='1811990'>the</span> <span m='1812110'>matrices</span> <span m='1812940'>are</span>
  <span m='1813070'>going</span> <span m='1813170'>to</span> <span m='1813240'>fit</span>
  <span m='1813570'>in</span> <span m='1813770'>cache.</span> <span m='1814600'>So</span>
  <span m='1814900'>all</span> <span m='1815200'>I</span> <span m='1815550'>have</span>
  <span m='1816530'>is</span> <span m='1816700'>my</span> <span m='1816880'>cold</span>
  <span m='1817350'>misses,</span> <span m='1818410'>if</span> <span m='1818610'>any,</span>
  <span m='1819130'>on</span> <span m='1819450'>that</span> <span m='1820050'>submatrix.</span>
  </p><p><span m='1822520'>And</span> <span m='1822660'>how</span> <span m='1822850'>many</span>
  <span m='1823090'>cold</span> <span m='1823460'>misses</span> <span m='1823860'>can</span>
  <span m='1824010'>I</span> <span m='1824310'>have?</span> <span m='1824820'>Well</span>
  <span m='1825210'>the</span> <span m='1825490'>size</span> <span m='1825650'>of</span>
  <span m='1825800'>the</span> <span m='1825880'>matrix</span> <span m='1826350'>is</span>
  <span m='1826530'>s squared</span> <span m='1827690'>and</span> <span m='1828650'>I</span>
  <span m='1828770'>get</span> <span m='1828980'>to</span> <span m='1829050'>bring</span>
  <span m='1829300'>in</span> <span m='1829500'>b</span> <span m='1831300'>bytes</span>
  <span m='1831790'>of</span> <span m='1831990'>the</span> <span m='1832090'>matrix</span>
  <span m='1832620'>each</span> <span m='1832880'>time.</span> <span m='1833500'>So</span>
  <span m='1833650'>I</span> <span m='1833720'>get s</span> <span m='1833960'>squared</span>
  <span m='1834032'>over</span> <span m='1834068'>b</span> <span m='1834104'>misses</span>
  <span m='1835470'>per</span> <span m='1835640'>submatrix.</span> </p><p><span m='1837820'>So</span>
  <span m='1838030'>that</span> <span m='1838180'>was</span> <span m='1838280'>a</span>
  <span m='1838320'>little</span> <span m='1838480'>bit</span> <span m='1838680'>fast,</span>
  <span m='1838940'>but</span> <span m='1839200'>I</span> <span m='1839270'>just</span>
  <span m='1839450'>want</span> <span m='1839520'>to</span> <span m='1839580'>make</span>
  <span m='1839760'>sure--</span> <span m='1843520'>it's</span> <span m='1844050'>at</span>
  <span m='1844240'>one</span> <span m='1844430'>level</span> <span m='1844720'>straightforward,</span>
  <span m='1845400'>and</span> <span m='1845480'>the</span> <span m='1845600'>other</span>
  <span m='1845790'>level</span> <span m='1846130'>it's</span> <span m='1846230'>a</span>
  <span m='1846280'>little</span> <span m='1846450'>bit</span> <span m='1846650'>fast.</span>
  <span m='1848300'>So</span> <span m='1848490'>the</span> <span m='1848580'>point</span>
  <span m='1848850'>is</span> <span m='1849040'>that</span> <span m='1849170'>the</span>
  <span m='1849330'>inner</span> <span m='1849600'>three</span> <span m='1849930'>loops</span>
  <span m='1850350'>I</span> <span m='1850440'>can</span> <span m='1850610'>analyze</span>
  <span m='1851390'>if</span> <span m='1851580'>I</span> <span m='1851680'>know</span>
  <span m='1851970'>that</span> <span m='1852180'>s</span> <span m='1852470'>is</span>
  <span m='1852650'>fitting</span> <span m='1853000'>in</span> <span m='1853150'>cache.</span>
  <span m='1853990'>The</span> <span m='1854100'>inner</span> <span m='1854320'>three</span>
  <span m='1854600'>loops</span> <span m='1854900'>I</span> <span m='1855000'>can</span>
  <span m='1855180'>analyze</span> <span m='1856140'>by</span> <span m='1856340'>saying,</span>
  <span m='1856630'>look</span> <span m='1856920'>it's</span> <span m='1857100'>s</span>
  <span m='1857340'>squared</span> <span m='1857760'>data.</span> <span m='1858610'>Once</span>
  <span m='1858870'>I</span> <span m='1858930'>get</span> <span m='1859140'>the</span>
  <span m='1859230'>data</span> <span m='1859510'>in</span> <span m='1859730'>cache,</span>
  <span m='1860240'>if</span> <span m='1860370'>I'm</span> <span m='1860490'>using</span>
  <span m='1860740'>an</span> <span m='1860880'>optimal</span> <span m='1861400'>replacement,</span>
  <span m='1863270'>then</span> <span m='1863450'>it's</span> <span m='1863610'>going</span>
  <span m='1863720'>to</span> <span m='1863780'>stay</span> <span m='1864120'>in</span>
  <span m='1864320'>there.</span> <span m='1866480'>And</span> <span m='1866690'>so</span>
  <span m='1867820'>it will</span> <span m='1868060'>cost</span> <span m='1868500'>me
  s</span> <span m='1868670'>squared</span> <span m='1868746'>over</span> <span m='1868784'>b</span>
  <span m='1868822'>misses</span> <span m='1870050'>to</span> <span m='1870140'>bring</span>
  <span m='1870460'>that</span> <span m='1870720'>matrix</span> <span m='1871180'>in</span>
  <span m='1871510'>for</span> <span m='1873020'>each</span> <span m='1873190'>of</span>
  <span m='1873280'>the</span> <span m='1873360'>three</span> <span m='1873600'>matrices.</span>
  </p><p><span m='1874410'>But</span> <span m='1874560'>once</span> <span m='1874820'>it's</span>
  <span m='1874980'>in</span> <span m='1875170'>there,</span> <span m='1875800'>I</span>
  <span m='1875950'>can</span> <span m='1876160'>keep</span> <span m='1876680'>going</span>
  <span m='1876990'>over</span> <span m='1877300'>and</span> <span m='1877370'>over</span>
  <span m='1877720'>it</span> <span m='1877820'>as</span> <span m='1877960'>the</span>
  <span m='1878100'>algorithm</span> <span m='1878540'>does.</span> <span m='1879480'>I</span>
  <span m='1879610'>don't</span> <span m='1879750'>get</span> <span m='1879910'>any</span>
  <span m='1880100'>cache</span> <span m='1880430'>misses.</span> <span m='1881190'>Because</span>
  <span m='1881360'>those</span> <span m='1881580'>all</span> <span m='1883730'>fitting</span>
  <span m='1884050'>in</span> <span m='1884200'>the</span> <span m='1884290'>cache.</span>
  <span m='1885720'>Question?</span> <span m='1888050'>Everybody</span> <span m='1888370'>with</span>
  <span m='1888540'>me?</span> <span m='1889770'>OK.</span> </p><p><span m='1891890'>So</span>
  <span m='1893450'>then</span> <span m='1893750'>I</span> <span m='1893880'>basically</span>
  <span m='1894440'>have</span> <span m='1894600'>the</span> <span m='1894730'>outer</span>
  <span m='1895100'>three</span> <span m='1895430'>loops.</span> <span m='1896020'>And</span>
  <span m='1896170'>here</span> <span m='1896480'>I</span> <span m='1896560'>don't</span>
  <span m='1896920'>make</span> <span m='1897140'>any</span> <span m='1897310'>assumptions</span>
  <span m='1897740'>whatsoever.</span> <span m='1898360'>There's</span> <span m='1898660'>n
  over s</span> <span m='1900770'>iterations</span> <span m='1901990'>for</span> <span
  m='1902200'>each</span> <span m='1902450'>loop.</span> <span m='1903120'>And</span>
  <span m='1903250'>there's</span> <span m='1903350'>three</span> <span m='1903660'>loops.</span>
  <span m='1903940'>So</span> <span m='1904070'>that's</span> <span m='1904300'>n
  over s cubed.</span> <span m='1905690'>And</span> <span m='1905870'>then</span>
  <span m='1906010'>the</span> <span m='1906110'>cost</span> <span m='1906600'>of</span>
  <span m='1906680'>the</span> <span m='1906770'>misses</span> <span m='1907670'>in</span>
  <span m='1907800'>the</span> <span m='1907940'>inner</span> <span m='1908140'>loop</span>
  <span m='1908540'>is</span> <span m='1908780'>s squared over b.</span> <span m='1910440'>And</span>
  <span m='1910580'>that</span> <span m='1910820'>gives</span> <span m='1911020'>me</span>
  <span m='1911200'>n cubed over bm to the 1/2</span> <span m='1914360'>if</span>
  <span m='1914500'>you</span> <span m='1915290'>plug in</span> <span m='1915810'>s</span>
  <span m='1916210'>being</span> <span m='1916600'>m to the 1/2.</span> </p><p><span
  m='1921110'>So</span> <span m='1921310'>this</span> <span m='1921550'>is</span>
  <span m='1922010'>radically</span> <span m='1922780'>better</span> <span m='1925870'>because</span>
  <span m='1926480'>m</span> <span m='1926740'>is</span> <span m='1926860'>usually</span>
  <span m='1927320'>big.</span> <span m='1928530'>Especially</span> <span m='1931260'>for</span>
  <span m='1931440'>a</span> <span m='1931470'>higher</span> <span m='1931760'>level</span>
  <span m='1932040'>cache,</span> <span m='1932430'>for</span> <span m='1932630'>an</span>
  <span m='1933120'>L2</span> <span m='1933310'>or</span> <span m='1933440'>an</span>
  <span m='1934460'>L3.</span> <span m='1934690'>m</span> <span m='1934800'>is really</span>
  <span m='1935060'>big.</span> </p><p><span m='1935980'>What</span> <span m='1936150'>was</span>
  <span m='1936280'>the</span> <span m='1936370'>value</span> <span m='1936750'>we</span>
  <span m='1936880'>had</span> <span m='1937090'>before</span> <span m='1937610'>for</span>
  <span m='1937720'>the</span> <span m='1937820'>best</span> <span m='1938170'>case</span>
  <span m='1939050'>for</span> <span m='1939180'>the</span> <span m='1939350'>other</span>
  <span m='1939860'>algorithm</span> <span m='1940670'>when</span> <span m='1940820'>it</span>
  <span m='1940910'>didn't</span> <span m='1941170'>fit in</span> <span m='1941410'>matrix?</span>
  <span m='1942260'>It</span> <span m='1942430'>was</span> <span m='1942650'>n cubed
  over b.</span> <span m='1945280'>b</span> <span m='1945600'>is</span> <span m='1945770'>like</span>
  <span m='1946020'>64</span> <span m='1946610'>bytes.</span> <span m='1948570'>m</span>
  <span m='1949240'>is</span> <span m='1949420'>like</span> <span m='1949860'>the</span>
  <span m='1949980'>small</span> <span m='1951730'>L1</span> <span m='1952200'>cache</span>
  <span m='1952750'>is</span> <span m='1952970'>32</span> <span m='1953470'>kilobytes.</span>
  <span m='1956160'>So</span> <span m='1956300'>you</span> <span m='1956380'>get</span>
  <span m='1956550'>to</span> <span m='1956640'>square</span> <span m='1957070'>root</span>
  <span m='1957340'>the</span> <span m='1957430'>32</span> <span m='1957720'>kilobytes.</span>
  <span m='1959460'>What's</span> <span m='1959890'>that?</span> </p><p><span m='1967470'>So</span>
  <span m='1967690'>that's</span> <span m='1968710'>32</span> <span m='1969100'>kilobytes</span>
  <span m='1969610'>is</span> <span m='1971160'>2 to the 15th.</span> <span m='1972670'>So</span>
  <span m='1972810'>it's</span> <span m='1973140'>2 to the 7.5.</span> <span m='1975590'>2
  to the 7</span> <span m='1976100'>is</span> <span m='1976220'>128.</span> <span
  m='1979120'>So</span> <span m='1979660'>it's</span> <span m='1981420'>somewhere</span>
  <span m='1981730'>between</span> <span m='1982190'>128</span> <span m='1983110'>and</span>
  <span m='1986630'>256.</span> </p><p><span m='1988020'>So</span> <span m='1988250'>if</span>
  <span m='1988390'>we</span> <span m='1988470'>said</span> <span m='1988620'>128,</span>
  <span m='1989900'>I've</span> <span m='1990040'>got</span> <span m='1990200'>a</span>
  <span m='1990240'>64</span> <span m='1990660'>and a</span> <span m='1991080'>128</span>
  <span m='1991960'>multiplier</span> <span m='1992580'>there.</span> <span m='1993130'>Much,</span>
  <span m='1993430'>much</span> <span m='1993680'>better</span> <span m='1994460'>in</span>
  <span m='1994570'>terms</span> <span m='1995060'>of</span> <span m='1995180'>calculating.</span>
  <span m='1995400'>In fact,</span> <span m='1995600'>this is</span> <span m='1995720'>such</span>
  <span m='1996590'>that</span> <span m='1996900'>if</span> <span m='1997080'>we</span>
  <span m='1997220'>tune</span> <span m='1997470'>this</span> <span m='1997680'>properly</span>
  <span m='2000560'>and</span> <span m='2000760'>then</span> <span m='2000920'>we</span>
  <span m='2001050'>say,</span> <span m='2001370'>well</span> <span m='2001510'>what</span>
  <span m='2001700'>was</span> <span m='2001850'>the</span> <span m='2001950'>cost</span>
  <span m='2002590'>of</span> <span m='2002910'>the</span> <span m='2003600'>cache</span>
  <span m='2003960'>misses</span> <span m='2004350'>here,</span> <span m='2005470'>you're</span>
  <span m='2005650'>not</span> <span m='2005830'>going</span> <span m='2005930'>to</span>
  <span m='2005990'>see</span> <span m='2006260'>the</span> <span m='2006370'>cost</span>
  <span m='2006740'>of</span> <span m='2006800'>the</span> <span m='2006860'>cache</span>
  <span m='2007190'>misses</span> <span m='2008760'>when</span> <span m='2008880'>you</span>
  <span m='2008970'>do</span> <span m='2009100'>your</span> <span m='2009260'>performance</span>
  <span m='2010440'>analysis.</span> <span m='2011300'>It's</span> <span m='2011490'>all</span>
  <span m='2011860'>going</span> <span m='2011980'>to</span> <span m='2012050'>be</span>
  <span m='2012660'>the</span> <span m='2012790'>work.</span> <span m='2013590'>Because</span>
  <span m='2013740'>the</span> <span m='2013820'>work</span> <span m='2014070'>is</span>
  <span m='2014170'>still</span> <span m='2014480'>n cubed.</span> </p><p><span m='2017080'>The</span>
  <span m='2017170'>work</span> <span m='2017410'>is</span> <span m='2017500'>still</span>
  <span m='2017800'>n</span> <span m='2017970'>cubed,</span> <span m='2018600'>but</span>
  <span m='2018800'>now</span> <span m='2019000'>the</span> <span m='2019100'>misses</span>
  <span m='2019630'>are</span> <span m='2019930'>so</span> <span m='2020050'>infrequent,</span>
  <span m='2022230'>because</span> <span m='2022430'>we're</span> <span m='2022570'>only</span>
  <span m='2022740'>getting</span> <span m='2023470'>one</span> <span m='2023870'>every--</span>
  <span m='2025180'>on</span> <span m='2025380'>the</span> <span m='2025470'>order</span>
  <span m='2025760'>of</span> <span m='2025820'>64</span> <span m='2026500'>times</span>
  <span m='2026750'>128,</span> <span m='2028230'>which</span> <span m='2028460'>is</span>
  <span m='2029370'>2 to the 6th</span> <span m='2030020'>times</span> <span m='2030340'>2
  to the 7th</span> <span m='2031110'>is</span> <span m='2031320'>2 to the 13th</span>
  <span m='2032270'>is</span> <span m='2033260'>8K.</span> <span m='2034200'>Every</span>
  <span m='2034455'>8,000</span> <span m='2034710'>or</span> <span m='2035220'>so</span>
  <span m='2036450'>accesses</span> <span m='2037600'>there's a</span> <span m='2037680'>constant</span>
  <span m='2038040'>factor</span> <span m='2038380'>in</span> <span m='2038490'>there</span>
  <span m='2038640'>or</span> <span m='2038730'>whatever,</span> <span m='2039080'>but</span>
  <span m='2040040'>every</span> <span m='2040370'>8,000</span> <span m='2040960'>or</span>
  <span m='2041060'>so</span> <span m='2041300'>accesses</span> <span m='2042050'>we're</span>
  <span m='2042150'>getting</span> <span m='2042510'>a</span> <span m='2042560'>cache</span>
  <span m='2043090'>miss.</span> <span m='2043370'>Uh,</span> <span m='2043650'>too</span>
  <span m='2043780'>bad.</span> </p><p><span m='2045700'>If</span> <span m='2045810'>it's</span>
  <span m='2045880'>L1,</span> <span m='2046350'>that</span> <span m='2046500'>cost</span>
  <span m='2046800'>is</span> <span m='2046920'>four</span> <span m='2047160'>cycles</span>
  <span m='2047570'>rather</span> <span m='2047880'>than</span> <span m='2048010'>one.</span>
  <span m='2051350'>Or</span> <span m='2051750'>that</span> <span m='2051929'>cost</span>
  <span m='2052230'>us</span> <span m='2053179'>10</span> <span m='2053400'>cycles</span>
  <span m='2053780'>if I had</span> <span m='2054040'>to</span> <span m='2054090'>go</span>
  <span m='2054230'>to</span> <span m='2054500'>L2</span> <span m='2054730'>rather</span>
  <span m='2055020'>than</span> <span m='2055170'>one,</span> <span m='2056120'>or</span>
  <span m='2056199'>whatever.</span> <span m='2057030'>So</span> <span m='2057370'>is</span>
  <span m='2057469'>to</span> <span m='2057560'>the</span> <span m='2057650'>point</span>
  <span m='2057920'>is,</span> <span m='2058480'>that's</span> <span m='2058739'>a</span>
  <span m='2058790'>great</span> <span m='2059170'>multiplier</span> <span m='2059730'>to</span>
  <span m='2059960'>have.</span> <span m='2062940'>So</span> <span m='2063100'>this</span>
  <span m='2063260'>is</span> <span m='2063300'>a</span> <span m='2063380'>really</span>
  <span m='2063630'>good</span> <span m='2063810'>algorithm.</span> <span m='2066190'>And</span>
  <span m='2066389'>in</span> <span m='2066500'>fact,</span> <span m='2066920'>this</span>
  <span m='2067100'>is</span> <span m='2067230'>the</span> <span m='2067360'>optimal</span>
  <span m='2067830'>behavior</span> <span m='2068239'>you</span> <span m='2068389'>can</span>
  <span m='2068520'>get</span> <span m='2068750'>for</span> <span m='2068870'>matrix</span>
  <span m='2069219'>multiplication.</span> </p><p><span m='2073420'>Hong</span> <span
  m='2073989'>and</span> <span m='2074389'>Kung</span> <span m='2074730'>proved</span>
  <span m='2075010'>back</span> <span m='2075260'>in</span> <span m='2075350'>1981</span>
  <span m='2076889'>that</span> <span m='2077090'>this</span> <span m='2077510'>particular</span>
  <span m='2077989'>strategy</span> <span m='2078580'>and</span> <span m='2078690'>this</span>
  <span m='2078860'>bound</span> <span m='2079290'>was</span> <span m='2079400'>the</span>
  <span m='2079480'>best</span> <span m='2079800'>you</span> <span m='2079900'>could</span>
  <span m='2080060'>do</span> <span m='2080620'>for</span> <span m='2080750'>matrix</span>
  <span m='2081139'>multiplication.</span> <span m='2084010'>So</span> <span m='2084210'>that's</span>
  <span m='2084480'>great.</span> <span m='2085310'>I</span> <span m='2085400'>want</span>
  <span m='2085620'>you</span> <span m='2085699'>to</span> <span m='2085770'>remember</span>
  <span m='2086219'>this</span> <span m='2086840'>number</span> <span m='2087150'>because</span>
  <span m='2087290'>we're</span> <span m='2087370'>going</span> <span m='2087449'>to</span>
  <span m='2087489'>come</span> <span m='2087650'>back</span> <span m='2087949'>to</span>
  <span m='2088110'>it.</span> <span m='2090130'>So</span> <span m='2090480'>remember</span>
  <span m='2091000'>it's</span> <span m='2091280'>b times n to the 1/2,</span> <span
  m='2092690'>b times square root of m</span> <span m='2094159'>in</span> <span m='2094230'>the</span>
  <span m='2094320'>denominator.</span> </p><p><span m='2097990'>Now</span> <span
  m='2101140'>there's</span> <span m='2101480'>one</span> <span m='2103330'>hitch</span>
  <span m='2103720'>in</span> <span m='2103820'>this</span> <span m='2103920'>story.</span>
  <span m='2106390'>And</span> <span m='2106600'>that</span> <span m='2106860'>is,</span>
  <span m='2107120'>what</span> <span m='2107270'>do</span> <span m='2107360'>I</span>
  <span m='2107510'>have</span> <span m='2107760'>to</span> <span m='2107870'>do</span>
  <span m='2108100'>for</span> <span m='2108220'>this</span> <span m='2108400'>algorithm</span>
  <span m='2108840'>to</span> <span m='2108950'>work</span> <span m='2109220'>well?</span>
  <span m='2112720'>It</span> <span m='2112800'>says</span> <span m='2113020'>right</span>
  <span m='2113240'>up</span> <span m='2113360'>there</span> <span m='2113540'>on</span>
  <span m='2113620'>the</span> <span m='2113690'>slide.</span> <span m='2117630'>Tune</span>
  <span m='2117940'>s.</span> <span m='2119560'>I've</span> <span m='2119690'>got</span>
  <span m='2119830'>to</span> <span m='2119930'>tune</span> <span m='2120160'>s.</span>
  </p><p><span m='2121660'>How</span> <span m='2121840'>do</span> <span m='2121960'>I</span>
  <span m='2122070'>do</span> <span m='2122290'>that?</span> <span m='2125130'>How</span>
  <span m='2125280'>do</span> <span m='2125400'>I</span> <span m='2125510'>tune</span>
  <span m='2125810'>s?</span> <span m='2128950'>How</span> <span m='2129260'>would</span>
  <span m='2129450'>you</span> <span m='2129550'>suggest</span> <span m='2130070'>we</span>
  <span m='2130190'>tune</span> <span m='2130500'>s?</span> </p><p><span m='2130810'>AUDIENCE:</span>
  <span m='2131265'>Just run a</span> <span m='2133085'>binary</span> <span m='2133540'>[INAUDIBLE].</span>
  </p><p><span m='2133995'>PROFESSOR:</span> <span m='2134450'>Yeah,</span> <span
  m='2134510'>do</span> <span m='2134870'>binary</span> <span m='2135380'>search</span>
  <span m='2136270'>on</span> <span m='2136480'>s</span> <span m='2137520'>to</span>
  <span m='2137640'>find</span> <span m='2137990'>out</span> <span m='2138280'>what's</span>
  <span m='2139160'>the</span> <span m='2139250'>best</span> <span m='2139540'>value</span>
  <span m='2139890'>for</span> <span m='2140100'>s.</span> <span m='2141990'>Good</span>
  <span m='2142180'>strategy.</span> <span m='2144490'>What</span> <span m='2144640'>if</span>
  <span m='2144750'>we</span> <span m='2144880'>guess</span> <span m='2145260'>wrong?</span>
  </p><p><span m='2148500'>What</span> <span m='2148750'>happens</span> <span m='2149210'>if,</span>
  <span m='2149310'>say,</span> <span m='2150450'>we</span> <span m='2150610'>tune</span>
  <span m='2150870'>s,</span> <span m='2151880'>we</span> <span m='2151990'>get</span>
  <span m='2152170'>some</span> <span m='2152360'>value</span> <span m='2152730'>for
  it.</span> <span m='2153000'>Let's</span> <span m='2153210'>say</span> <span m='2153330'>the</span>
  <span m='2153410'>value</span> <span m='2153730'>is</span> <span m='2154050'>100.</span>
  <span m='2156690'>So</span> <span m='2156930'>we've</span> <span m='2157120'>turned</span>
  <span m='2157430'>it.</span> <span m='2157670'>We</span> <span m='2157790'>find</span>
  <span m='2158020'>100</span> <span m='2158410'>is</span> <span m='2158550'>our</span>
  <span m='2158660'>best</span> <span m='2158960'>value.</span> <span m='2159970'>We</span>
  <span m='2160320'>run</span> <span m='2160570'>it</span> <span m='2160670'>on</span>
  <span m='2160900'>our</span> <span m='2161500'>workstation,</span> <span m='2162320'>and</span>
  <span m='2162450'>somebody</span> <span m='2162820'>else</span> <span m='2163060'>has</span>
  <span m='2163300'>another</span> <span m='2163570'>job</span> <span m='2163960'>running.</span>
  </p><p><span m='2166770'>What</span> <span m='2167040'>happens</span> <span m='2167490'>then?</span>
  <span m='2169730'>That</span> <span m='2169910'>other</span> <span m='2170110'>job</span>
  <span m='2170400'>starts</span> <span m='2170650'>sharing</span> <span m='2171130'>part</span>
  <span m='2171350'>of</span> <span m='2171400'>that</span> <span m='2171620'>cache.</span>
  <span m='2173520'>So</span> <span m='2173670'>the</span> <span m='2173780'>effective</span>
  <span m='2174290'>cache</span> <span m='2174640'>size</span> <span m='2175140'>is</span>
  <span m='2175230'>going</span> <span m='2175360'>to</span> <span m='2175430'>be</span>
  <span m='2176460'>smaller</span> <span m='2177070'>than</span> <span m='2177230'>what</span>
  <span m='2177450'>we</span> <span m='2177580'>turned</span> <span m='2177850'>it</span>
  <span m='2178000'>for.</span> <span m='2178410'>And</span> <span m='2178540'>what's</span>
  <span m='2178750'>going</span> <span m='2178820'>to</span> <span m='2178890'>happen?</span>
  <span m='2183740'>What's</span> <span m='2183940'>going</span> <span m='2184010'>to</span>
  <span m='2184080'>happen</span> <span m='2184390'>in</span> <span m='2184470'>that</span>
  <span m='2184660'>case?</span> <span m='2187700'>If</span> <span m='2187870'>I've</span>
  <span m='2187950'>tuned</span> <span m='2188320'>in</span> <span m='2188410'>for</span>
  <span m='2188590'>a</span> <span m='2188620'>given</span> <span m='2189080'>size</span>
  <span m='2189530'>and</span> <span m='2189740'>then</span> <span m='2189890'>I</span>
  <span m='2189970'>actually</span> <span m='2190330'>have</span> <span m='2190540'>to</span>
  <span m='2190790'>run</span> <span m='2190920'>with</span> <span m='2191060'>something</span>
  <span m='2191390'>that's</span> <span m='2191550'>effectively</span> <span m='2192240'>a</span>
  <span m='2192340'>smaller</span> <span m='2192910'>cache,</span> <span m='2196340'>does</span>
  <span m='2196440'>it</span> <span m='2196510'>matter</span> <span m='2196910'>or</span>
  <span m='2196950'>doesn't</span> <span m='2197200'>matter?</span> </p><p><span m='2197710'>AUDIENCE:</span>
  <span m='2198150'>Is it</span> <span m='2198590'>still tall?</span> </p><p><span
  m='2199030'>PROFESSOR:</span> <span m='2199470'>Still</span> <span m='2199760'>tall.</span>
  </p><p><span m='2201601'>AUDIENCE:</span> <span m='2202088'>[INAUDIBLE]</span> </p><p><span
  m='2206958'>PROFESSOR:</span> <span m='2207445'>So if</span> <span m='2207932'>you</span>
  <span m='2208430'>imagine this</span> <span m='2208600'>fit</span> <span m='2208850'>exactly</span>
  <span m='2209460'>into</span> <span m='2209670'>cache,</span> <span m='2210600'>and</span>
  <span m='2210760'>now</span> <span m='2210950'>I</span> <span m='2211040'>only</span>
  <span m='2211250'>have</span> <span m='2211380'>half</span> <span m='2211760'>that</span>
  <span m='2211970'>amount.</span> <span m='2212960'>Then</span> <span m='2213130'>the</span>
  <span m='2213240'>assumption</span> <span m='2214800'>that</span> <span m='2215230'>these</span>
  <span m='2215480'>three</span> <span m='2215850'>inner loops</span> <span m='2216400'>is</span>
  <span m='2216550'>running</span> <span m='2218090'>with</span> <span m='2218310'>only</span>
  <span m='2219290'>s squared over b</span> <span m='2219520'>misses</span> <span
  m='2221570'>is</span> <span m='2221710'>going to be</span> <span m='2221840'>totally</span>
  <span m='2222280'>out</span> <span m='2222470'>the</span> <span m='2222560'>window.</span>
  <span m='2224410'>In</span> <span m='2224580'>fact,</span> <span m='2224870'>it's</span>
  <span m='2225030'>going</span> <span m='2225160'>to</span> <span m='2225230'>be</span>
  <span m='2225490'>just</span> <span m='2225890'>like</span> <span m='2227870'>the</span>
  <span m='2228040'>case</span> <span m='2228860'>of</span> <span m='2230060'>the</span>
  <span m='2230480'>first</span> <span m='2230870'>algorithm,</span> <span m='2231370'>the</span>
  <span m='2231760'>naive</span> <span m='2231930'>algorithm</span> <span m='2232400'>that</span>
  <span m='2232540'>I</span> <span m='2232620'>gave.</span> <span m='2234460'>Because</span>
  <span m='2235060'>the</span> <span m='2235440'>size</span> <span m='2235910'>of</span>
  <span m='2235970'>matrix</span> <span m='2236340'>that I'm</span> <span m='2236620'>feeding</span>
  <span m='2236960'>it,</span> <span m='2237100'>s by s,</span> <span m='2238180'>isn't</span>
  <span m='2238570'>fitting</span> <span m='2238890'>in</span> <span m='2238980'>the</span>
  <span m='2239070'>cache.</span> </p><p><span m='2241850'>And</span> <span m='2241990'>so</span>
  <span m='2242140'>rather</span> <span m='2242530'>than</span> <span m='2242710'>it</span>
  <span m='2242890'>being</span> <span m='2243860'>s squared over b</span> <span m='2244080'>accesses,</span>
  <span m='2245660'>it's</span> <span m='2245850'>going</span> <span m='2245960'>to</span>
  <span m='2246000'>be</span> <span m='2246140'>much</span> <span m='2246390'>bigger.</span>
  <span m='2249290'>I'm</span> <span m='2249320'>going to</span> <span m='2249490'>end</span>
  <span m='2249680'>up</span> <span m='2251210'>with</span> <span m='2251750'>essentially</span>
  <span m='2252280'>s cubed</span> <span m='2254170'>accesses</span> <span m='2256720'>if</span>
  <span m='2256950'>the</span> <span m='2257180'>cache,</span> <span m='2257520'>in</span>
  <span m='2257620'>fact,</span> <span m='2257920'>gets</span> <span m='2258050'>enough</span>
  <span m='2258240'>smaller.</span> </p><p><span m='2264590'>It's</span> <span m='2264750'>also</span>
  <span m='2265160'>one</span> <span m='2265530'>thing you</span> <span m='2265650'>have</span>
  <span m='2265860'>to</span> <span m='2265980'>put</span> <span m='2266180'>in</span>
  <span m='2266320'>there</span> <span m='2266960'>is</span> <span m='2267520'>what</span>
  <span m='2267790'>I</span> <span m='2267880'>like</span> <span m='2268130'>to</span>
  <span m='2268240'>call</span> <span m='2269840'>voodoo.</span> <span m='2271770'>Whenever</span>
  <span m='2272150'>you</span> <span m='2272290'>have</span> <span m='2273165'>a</span>
  <span m='2273540'>program</span> <span m='2274620'>and</span> <span m='2274730'>you've</span>
  <span m='2274840'>got</span> <span m='2275090'>some</span> <span m='2275290'>parameters</span>
  <span m='2276190'>that,</span> <span m='2277130'>oh good</span> <span m='2277670'>we've</span>
  <span m='2277790'>got</span> <span m='2278070'>these</span> <span m='2278310'>parameters</span>
  <span m='2278910'>we</span> <span m='2279020'>get</span> <span m='2279240'>to</span>
  <span m='2279330'>tweak</span> <span m='2279830'>to</span> <span m='2279940'>make</span>
  <span m='2280170'>it</span> <span m='2280280'>go</span> <span m='2280460'>better.</span>
  <span m='2282170'>I</span> <span m='2282260'>call</span> <span m='2282500'>those</span>
  <span m='2282950'>voodoo</span> <span m='2283080'>parameters.</span> <span m='2284970'>Because</span>
  <span m='2285340'>typically</span> <span m='2285920'>setting</span> <span m='2286330'>them</span>
  <span m='2286550'>is</span> <span m='2286930'>not</span> <span m='2287530'>straightforward.</span>
  </p><p><span m='2290320'>Now</span> <span m='2290450'>there are</span> <span m='2290570'>different</span>
  <span m='2290920'>strategies.</span> <span m='2291590'>One,</span> <span m='2291910'>as
  you</span> <span m='2292010'>say,</span> <span m='2292220'>is</span> <span m='2292340'>to</span>
  <span m='2292430'>do</span> <span m='2292530'>binary</span> <span m='2292960'>search</span>
  <span m='2293340'>by</span> <span m='2293490'>doing</span> <span m='2293810'>it.</span>
  <span m='2294270'>There</span> <span m='2294460'>are</span> <span m='2294520'>some</span>
  <span m='2295350'>programs,</span> <span m='2296540'>in</span> <span m='2296680'>fact,</span>
  <span m='2297230'>which</span> <span m='2297650'>when</span> <span m='2297900'>you</span>
  <span m='2298020'>start</span> <span m='2298360'>them</span> <span m='2298540'>up</span>
  <span m='2298690'>you</span> <span m='2298800'>call</span> <span m='2299160'>an</span>
  <span m='2299490'>initialization</span> <span m='2300280'>routine.</span> <span
  m='2301350'>And</span> <span m='2301420'>what</span> <span m='2301590'>they</span>
  <span m='2301720'>will</span> <span m='2301890'>do</span> <span m='2302340'>is</span>
  <span m='2304010'>automatically</span> <span m='2304980'>check</span> <span m='2305470'>to</span>
  <span m='2305590'>see</span> <span m='2305920'>what</span> <span m='2306520'>size</span>
  <span m='2307050'>is</span> <span m='2307220'>my</span> <span m='2307440'>cache</span>
  <span m='2307960'>and</span> <span m='2308030'>what's</span> <span m='2308330'>the</span>
  <span m='2308420'>best</span> <span m='2308690'>size</span> <span m='2309410'>should</span>
  <span m='2309620'>I</span> <span m='2309700'>do</span> <span m='2309910'>something</span>
  <span m='2310350'>on</span> <span m='2311040'>and</span> <span m='2311220'>then</span>
  <span m='2311370'>use</span> <span m='2311650'>that</span> <span m='2311900'>when</span>
  <span m='2312000'>you</span> <span m='2312100'>actually</span> <span m='2312470'>run</span>
  <span m='2312720'>it</span> <span m='2313050'>later</span> <span m='2313420'>in</span>
  <span m='2313500'>the</span> <span m='2313570'>program.</span> <span m='2314430'>So</span>
  <span m='2314580'>it</span> <span m='2314690'>does</span> <span m='2315010'>an</span>
  <span m='2316250'>automatic</span> <span m='2316820'>adaptation</span> <span m='2317670'>automatically</span>
  <span m='2318390'>when</span> <span m='2318550'>you</span> <span m='2318640'>start.</span>
  <span m='2319470'>But</span> <span m='2319680'>the</span> <span m='2319760'>more</span>
  <span m='2320040'>parameters</span> <span m='2320620'>you</span> <span m='2320760'>get,</span>
  <span m='2321930'>the</span> <span m='2322070'>more</span> <span m='2322280'>troublesome</span>
  <span m='2322780'>it</span> <span m='2322940'>becomes.</span> </p><p><span m='2324640'>So</span>
  <span m='2324780'>let's</span> <span m='2325090'>take</span> <span m='2325310'>a</span>
  <span m='2325360'>look.</span> <span m='2325580'>For</span> <span m='2325690'>example,</span>
  <span m='2326150'>suppose</span> <span m='2326540'>we</span> <span m='2326640'>have</span>
  <span m='2326750'>a</span> <span m='2326840'>two-level</span> <span m='2327410'>cache</span>
  <span m='2327780'>rather</span> <span m='2328070'>than</span> <span m='2328230'>a</span>
  <span m='2328290'>one-level</span> <span m='2328820'>cache.</span> <span m='2331500'>Now</span>
  <span m='2331800'>I</span> <span m='2331940'>need</span> <span m='2332250'>to</span>
  <span m='2332470'>have</span> <span m='2332680'>something</span> <span m='2333060'>that</span>
  <span m='2333220'>I</span> <span m='2333330'>tune</span> <span m='2333660'>in</span>
  <span m='2333760'>for</span> <span m='2334220'>L1</span> <span m='2335250'>and</span>
  <span m='2335430'>something</span> <span m='2335790'>that</span> <span m='2335910'>I</span>
  <span m='2336010'>tune</span> <span m='2336340'>for</span> <span m='2336730'>L2.</span>
  <span m='2341210'>So</span> <span m='2342130'>it</span> <span m='2342290'>turns</span>
  <span m='2342620'>out</span> <span m='2342850'>that</span> <span m='2342940'>if</span>
  <span m='2343060'>I</span> <span m='2343140'>want</span> <span m='2343310'>to</span>
  <span m='2343360'>optimize</span> <span m='2345010'>s</span> <span m='2345290'>and</span>
  <span m='2345450'>t,</span> <span m='2346150'>I</span> <span m='2346280'>can't</span>
  <span m='2346660'>do</span> <span m='2346810'>it</span> <span m='2346890'>in</span>
  <span m='2347120'>more</span> <span m='2347320'>with</span> <span m='2347460'>binary</span>
  <span m='2347890'>search</span> <span m='2348400'>because</span> <span m='2348550'>I
  have</span> <span m='2348730'>two</span> <span m='2348910'>parameters.</span> <span
  m='2351090'>And</span> <span m='2351350'>binary</span> <span m='2351750'>search</span>
  <span m='2352060'>won't</span> <span m='2352340'>suffice</span> <span m='2352870'>for</span>
  <span m='2352990'>figuring</span> <span m='2353360'>out</span> <span m='2353550'>what's</span>
  <span m='2353800'>the</span> <span m='2353890'>best</span> <span m='2354230'>combination</span>
  <span m='2355310'>of</span> <span m='2355490'>s</span> <span m='2355880'>and</span>
  <span m='2356155'>t.</span> </p><p><span m='2356430'>And</span> <span m='2356580'>generally</span>
  <span m='2357160'>multidimensional</span> <span m='2358360'>searches</span> <span
  m='2358870'>are</span> <span m='2358980'>much</span> <span m='2359260'>harder</span>
  <span m='2360000'>than</span> <span m='2360170'>one-dimensional</span> <span m='2360820'>searches</span>
  <span m='2362570'>for</span> <span m='2362760'>optimizing.</span> <span m='2364720'>Moreover,</span>
  <span m='2365210'>here's</span> <span m='2365460'>what</span> <span m='2365630'>the</span>
  <span m='2365710'>code</span> <span m='2366030'>looks</span> <span m='2366310'>like.</span>
  <span m='2371290'>So</span> <span m='2371510'>now</span> <span m='2371770'>I've</span>
  <span m='2371940'>got,</span> <span m='2372110'>how</span> <span m='2372360'>many</span>
  <span m='2372610'>four</span> <span m='2372900'>loops?</span> <span m='2374530'>1,2,3,4,5,6,7,8,9</span>
  <span m='2376720'>nested</span> <span m='2377120'>for</span> <span m='2377390'>loops.</span>
  </p><p><span m='2381160'>So</span> <span m='2381320'>you</span> <span m='2381460'>can</span>
  <span m='2381590'>see</span> <span m='2382790'>the</span> <span m='2382910'>voodoo</span>
  <span m='2383430'>is</span> <span m='2383540'>starting</span> <span m='2384990'>to</span>
  <span m='2385130'>make</span> <span m='2385380'>this</span> <span m='2385530'>stuff</span>
  <span m='2385840'>run.</span> <span m='2386160'>You</span> <span m='2386310'>really</span>
  <span m='2386530'>have</span> <span m='2386710'>to</span> <span m='2386820'>be</span>
  <span m='2386980'>a</span> <span m='2387030'>magician</span> <span m='2388120'>to</span>
  <span m='2388430'>tune</span> <span m='2388720'>these</span> <span m='2388960'>things</span>
  <span m='2389720'>appropriately.</span> <span m='2391900'>I</span> <span m='2391930'>mean,</span>
  <span m='2392040'>if</span> <span m='2392130'>you can</span> <span m='2392230'>can</span>
  <span m='2392380'>do</span> <span m='2392540'>it</span> <span m='2392650'>that's</span>
  <span m='2392910'>great.</span> <span m='2393410'>But</span> <span m='2394010'>if</span>
  <span m='2394170'>you</span> <span m='2394450'>don't</span> <span m='2394750'>do</span>
  <span m='2394900'>it,</span> <span m='2395010'>OK.</span> </p><p><span m='2396110'>So</span>
  <span m='2396300'>now</span> <span m='2396520'>what</span> <span m='2396640'>about</span>
  <span m='2396880'>three</span> <span m='2397120'>levels</span> <span m='2397540'>of</span>
  <span m='2397610'>cache?</span> <span m='2399940'>So</span> <span m='2400110'>now</span>
  <span m='2400310'>we</span> <span m='2400400'>need</span> <span m='2400580'>three</span>
  <span m='2401410'>tuning</span> <span m='2401770'>parameters.</span> <span m='2404650'>Here</span>
  <span m='2404940'>s,</span> <span m='2405180'>t</span> <span m='2405390'>and</span>
  <span m='2405490'>u,</span> <span m='2406340'>we</span> <span m='2406610'>have</span>
  <span m='2406730'>12</span> <span m='2407220'>nested</span> <span m='2407650'>four</span>
  <span m='2407940'>loops.</span> <span m='2408190'>I</span> <span m='2408270'>didn't</span>
  <span m='2408470'>have</span> <span m='2408620'>the</span> <span m='2408710'>heart</span>
  <span m='2409060'>to</span> <span m='2409130'>actually</span> <span m='2409590'>write</span>
  <span m='2409840'>out</span> <span m='2410030'>the</span> <span m='2410120'>code</span>
  <span m='2412040'>for</span> <span m='2412140'>the</span> <span m='2412250'>12</span>
  <span m='2412590'>nested</span> <span m='2412970'>for</span> <span m='2413210'>loops.</span>
  <span m='2413400'>That</span> <span m='2413650'>just</span> <span m='2413700'>seemed</span>
  <span m='2414330'>overhead.</span> <span m='2415940'>But</span> <span m='2416120'>our
  new</span> <span m='2416380'>halo</span> <span m='2416600'>machines,</span> <span
  m='2416920'>they</span> <span m='2417040'>have</span> <span m='2417160'>three</span>
  <span m='2417380'>levels</span> <span m='2417660'>of</span> <span m='2417740'>caches.</span>
  </p><p><span m='2418800'>So</span> <span m='2418980'>let's</span> <span m='2420020'>tune</span>
  <span m='2420390'>for</span> <span m='2420580'>all</span> <span m='2420840'>the</span>
  <span m='2420910'>levels</span> <span m='2421240'>of</span> <span m='2421320'>caches.</span>
  <span m='2422750'>And</span> <span m='2422890'>as</span> <span m='2423010'>we</span>
  <span m='2423120'>mentioned,</span> <span m='2423500'>in</span> <span m='2423700'>a</span>
  <span m='2423800'>multi-program</span> <span m='2424270'>environment,</span> <span
  m='2424590'>you</span> <span m='2424690'>don't</span> <span m='2424850'>actually</span>
  <span m='2425110'>know</span> <span m='2425270'>what</span> <span m='2425420'>the</span>
  <span m='2425510'>cache</span> <span m='2425820'>size</span> <span m='2426115'>is,</span>
  <span m='2426410'>what</span> <span m='2426540'>other</span> <span m='2426720'>programs</span>
  <span m='2427060'>are</span> <span m='2427120'>running.</span> <span m='2427960'>So</span>
  <span m='2428100'>it's</span> <span m='2428170'>really</span> <span m='2428520'>easy</span>
  <span m='2428870'>to</span> <span m='2428970'>mistune</span> <span m='2429420'>these</span>
  <span m='2429610'>parameters.</span> </p><p><span m='2433464'>AUDIENCE:</span> <span
  m='2433931'>[INAUDIBLE]</span> <span m='2434398'>don't</span> <span m='2434865'>you
  have</span> <span m='2435332'>a</span> <span m='2435799'>problem</span> <span m='2436266'>because</span>
  <span m='2436733'>you're running</span> <span m='2437200'>the program</span> <span
  m='2437667'>for</span> <span m='2438134'>a</span> <span m='2438601'>particular</span>
  <span m='2438835'>n,</span> <span m='2439776'>and</span> <span m='2440130'>you</span>
  <span m='2440604'>don't</span> <span m='2441078'>necessarily</span> <span m='2441552'>know
  whether your program is</span> <span m='2442026'>going to run</span> <span m='2442500'>faster
  or</span> <span m='2442974'>slower--</span> </p><p><span m='2443922'>PROFESSOR:</span>
  <span m='2444400'>Well</span> <span m='2444750'>what you're</span> <span m='2445100'>usually</span>
  <span m='2445460'>doing,</span> <span m='2445810'>is</span> <span m='2445910'>you're</span>
  <span m='2446090'>tuning</span> <span m='2446410'>for</span> <span m='2446610'>s</span>
  <span m='2447050'>not</span> <span m='2447300'>n,</span> <span m='2447630'>right?</span>
  <span m='2448030'>So</span> <span m='2448390'>you're</span> <span m='2448540'>assuming--</span>
  </p><p><span m='2449040'>AUDIENCE:</span> <span m='2449535'>No, no</span> <span
  m='2450030'>a particular</span> <span m='2450525'>n.</span> </p><p><span m='2451515'>PROFESSOR:</span>
  <span m='2452010'>But</span> <span m='2452450'>the</span> <span m='2452550'>tuning</span>
  <span m='2452850'>of</span> <span m='2453150'>this</span> <span m='2453410'>is</span>
  <span m='2453580'>only</span> <span m='2453920'>dependent</span> <span m='2454330'>on</span>
  <span m='2454510'>s.</span> <span m='2454990'>It doesn't</span> <span m='2455270'>depend</span>
  <span m='2455630'>on</span> <span m='2455770'>n.</span> <span m='2456480'>So</span>
  <span m='2456550'>if</span> <span m='2456620'>you</span> <span m='2456710'>run</span>
  <span m='2456930'>it for</span> <span m='2457000'>a</span> <span m='2457070'>sufficiently</span>
  <span m='2457700'>large</span> <span m='2458000'>n,</span> <span m='2458560'>I</span>
  <span m='2458660'>think</span> <span m='2458800'>it's</span> <span m='2458900'>reasonable</span>
  <span m='2459450'>to</span> <span m='2459590'>assume</span> <span m='2460725'>that
  the</span> <span m='2461170'>s you</span> <span m='2461320'>get</span> <span m='2461550'>would</span>
  <span m='2461690'>be</span> <span m='2461840'>a</span> <span m='2461890'>good</span>
  <span m='2462110'>s</span> <span m='2462450'>for</span> <span m='2462670'>any</span>
  <span m='2463790'>large</span> <span m='2464160'>n.</span> <span m='2465300'>Because</span>
  <span m='2465650'>the</span> <span m='2465740'>real</span> <span m='2465990'>question</span>
  <span m='2466350'>is,</span> <span m='2466510'>what's</span> <span m='2466740'>fitting</span>
  <span m='2467010'>in</span> <span m='2467130'>cache?</span> <span m='2468830'>Yeah--</span>
  </p><p><span m='2469190'>AUDIENCE:</span> <span m='2469671'>How</span> <span m='2470152'>long</span>
  <span m='2470633'>does it</span> <span m='2471114'>take</span> <span m='2471595'>to
  fill up the cache</span> <span m='2473519'>relative</span> <span m='2474000'>to</span>
  <span m='2474481'>the</span> <span m='2474962'>context</span> <span m='2475924'>each
  time?</span> </p><p><span m='2477848'>PROFESSOR:</span> <span m='2478340'>Generally</span>
  <span m='2478670'>you</span> <span m='2478920'>can</span> <span m='2479540'>do</span>
  <span m='2479630'>it</span> <span m='2480180'>pretty</span> <span m='2480430'>quickly.</span>
  </p><p><span m='2481510'>AUDIENCE:</span> <span m='2481850'>Right.</span> <span
  m='2482810'>So why does it matter if your</span> <span m='2483290'>have</span> <span
  m='2483770'>multiple users,</span> <span m='2485210'>if you can fill</span> <span
  m='2485690'>it</span> <span m='2486170'>[INAUDIBLE].</span> </p><p><span m='2487610'>PROFESSOR:</span>
  <span m='2488090'>No because,</span> <span m='2488660'>he</span> <span m='2488950'>may</span>
  <span m='2489060'>not</span> <span m='2489300'>be</span> <span m='2489390'>using</span>
  <span m='2489850'>all</span> <span m='2490130'>of</span> <span m='2490200'>the</span>
  <span m='2490290'>cache,</span> <span m='2490740'>right?</span> <span m='2491850'>So</span>
  <span m='2492020'>when</span> <span m='2492150'>you</span> <span m='2492240'>come</span>
  <span m='2492420'>back,</span> <span m='2495200'>you're</span> <span m='2495330'>going</span>
  <span m='2495410'>to</span> <span m='2495520'>have</span> <span m='2495630'>it</span>
  <span m='2495780'>polluted</span> <span m='2496160'>with</span> <span m='2496320'>a</span>
  <span m='2496370'>certain</span> <span m='2496650'>amount</span> <span m='2496960'>of</span>
  <span m='2499680'>stuff.</span> <span m='2502830'>I</span> <span m='2503125'>think</span>
  <span m='2503420'>it's</span> <span m='2503570'>a</span> <span m='2503610'>good</span>
  <span m='2503760'>question.</span> </p><p><span m='2504280'>AUDIENCE:</span> <span
  m='2504743'>[INAUDIBLE]</span> </p><p><span m='2509836'>PROFESSOR:</span> <span
  m='2510310'>OK,</span> <span m='2510610'>so</span> <span m='2510750'>anyway,</span>
  <span m='2511110'>so</span> <span m='2511270'>this</span> <span m='2511480'>is</span>
  <span m='2511970'>the--</span> <span m='2512350'>yeah</span> <span m='2512630'>question.</span>
  </p><p><span m='2513000'>AUDIENCE:</span> <span m='2513472'>So if</span> <span m='2513944'>n</span>
  <span m='2514416'>is</span> <span m='2514888'>really</span> <span m='2515360'>large,</span>
  <span m='2515832'>is</span> <span m='2516304'>it</span> <span m='2516776'>possible</span>
  <span m='2517250'>that</span> <span m='2517740'>the</span> <span m='2518240'>second</span>
  <span m='2518708'>row</span> <span m='2519176'>of the</span> <span m='2519644'>matrix</span>
  <span m='2520112'>never loaded?</span> </p><p><span m='2521984'>PROFESSOR:</span>
  <span m='2522452'>If</span> <span m='2522920'>n is</span> <span m='2523390'>really</span>
  <span m='2523660'>large--</span> </p><p><span m='2524115'>AUDIENCE:</span> <span
  m='2524570'>Because</span> <span m='2525013'>n</span> <span m='2525456'>is</span>
  <span m='2525899'>really</span> <span m='2526342'>large,</span> <span m='2526785'>right?</span>
  <span m='2527228'>Just the</span> <span m='2527671'>first</span> <span m='2528120'>row</span>
  <span m='2528430'>of the</span> <span m='2528740'>matrix</span> <span m='2528820'>will
  fill up</span> <span m='2529080'>all the</span> <span m='2529565'>caches.</span>
  </p><p><span m='2533620'>PROFESSOR:</span> <span m='2534050'>It's</span> <span m='2534290'>LRU</span>
  <span m='2534690'>and in</span> <span m='2534890'>B</span> <span m='2535260'>you're</span>
  <span m='2535420'>going</span> <span m='2535690'>down</span> <span m='2536010'>this</span>
  <span m='2536160'>way.</span> <span m='2539210'>You're</span> <span m='2539380'>accessing</span>
  <span m='2539840'>things</span> <span m='2540260'>going</span> <span m='2540600'>down.</span>
  <span m='2543010'>OK,</span> <span m='2543790'>good.</span> <span m='2545480'>So</span>
  <span m='2545680'>let's</span> <span m='2545910'>look</span> <span m='2546200'>at</span>
  <span m='2546310'>a</span> <span m='2546510'>solution</span> <span m='2547170'>to</span>
  <span m='2547290'>these</span> <span m='2547760'>alternatives.</span> </p><p><span
  m='2548690'>What</span> <span m='2548840'>I</span> <span m='2548880'>want</span>
  <span m='2549090'>to</span> <span m='2551700'>in</span> <span m='2551850'>particular</span>
  <span m='2552340'>take</span> <span m='2552590'>a</span> <span m='2552780'>look</span>
  <span m='2552980'>at</span> <span m='2553180'>is</span> <span m='2553340'>recursive</span>
  <span m='2553950'>matrix</span> <span m='2554390'>multiplication.</span> <span m='2558510'>So</span>
  <span m='2558810'>the</span> <span m='2558960'>idea</span> <span m='2559440'>is</span>
  <span m='2560340'>you</span> <span m='2560490'>can</span> <span m='2560630'>do</span>
  <span m='2560780'>divide</span> <span m='2561250'>and</span> <span m='2561330'>conquer</span>
  <span m='2563160'>on</span> <span m='2563460'>multiplying</span> <span m='2564010'>matrices</span>
  <span m='2565490'>because</span> <span m='2566120'>if</span> <span m='2566300'>I</span>
  <span m='2566390'>divide</span> <span m='2566810'>each</span> <span m='2567000'>of</span>
  <span m='2567090'>these</span> <span m='2567340'>into</span> <span m='2567530'>four</span>
  <span m='2567890'>pieces,</span> <span m='2569080'>then</span> <span m='2570990'>essentially</span>
  <span m='2571600'>I</span> <span m='2571830'>have</span> <span m='2573290'>8</span>
  <span m='2573510'>multiply</span> <span m='2574200'>adds</span> <span m='2574430'>of</span>
  <span m='2574500'>n over 2</span> <span m='2575110'>by</span> <span m='2575270'>n
  over 2</span> <span m='2575750'>matrices.</span> <span m='2577450'>Because</span>
  <span m='2577680'>I</span> <span m='2577760'>basically</span> <span m='2578210'>do</span>
  <span m='2578390'>these</span> <span m='2578720'>eight</span> <span m='2578960'>multiplies</span>
  <span m='2579710'>each</span> <span m='2579970'>going</span> <span m='2580250'>into</span>
  <span m='2580460'>the</span> <span m='2580550'>correct</span> <span m='2581110'>result.</span>
  </p><p><span m='2581880'>So</span> <span m='2582050'>multiply</span> <span m='2583090'>A11</span>
  <span m='2583490'>B11</span> <span m='2584450'>and</span> <span m='2584570'>add</span>
  <span m='2584770'>it</span> <span m='2584880'>into</span> <span m='2585130'>C11.</span>
  <span m='2586090'>Multiply</span> <span m='2586280'>A12</span> <span m='2586840'>B21</span>
  <span m='2587710'>add it</span> <span m='2588030'>into</span> <span m='2588230'>C11</span>
  <span m='2588910'>and</span> <span m='2589050'>so</span> <span m='2589250'>forth.</span>
  <span m='2592310'>So</span> <span m='2592550'>I</span> <span m='2592670'>can</span>
  <span m='2592890'>basically</span> <span m='2593720'>do</span> <span m='2593950'>divide</span>
  <span m='2594110'>and</span> <span m='2594260'>conquer.</span> <span m='2594690'>And</span>
  <span m='2594780'>then</span> <span m='2594990'>each</span> <span m='2595190'>of</span>
  <span m='2595270'>those</span> <span m='2595630'>I</span> <span m='2595770'>recursively</span>
  <span m='2596430'>divide</span> <span m='2596790'>and</span> <span m='2596860'>conquer.</span>
  </p><p><span m='2600480'>So</span> <span m='2600650'>what's</span> <span m='2600940'>the</span>
  <span m='2601060'>intuition</span> <span m='2601660'>by</span> <span m='2601830'>why</span>
  <span m='2602120'>this</span> <span m='2602340'>might</span> <span m='2602660'>a</span>
  <span m='2602720'>good</span> <span m='2602930'>scheme</span> <span m='2603250'>to</span>
  <span m='2603360'>use?</span> </p><p><span m='2607624'>AUDIENCE:</span> <span m='2608102'>[INAUDIBLE]</span>
  </p><p><span m='2610492'>PROFESSOR:</span> <span m='2610970'>Well, we're</span>
  <span m='2611010'>not going</span> <span m='2611430'>to</span> <span m='2611490'>do</span>
  <span m='2611620'>parallel</span> <span m='2612070'>yet.</span> <span m='2613730'>Just</span>
  <span m='2613970'>why</span> <span m='2614160'>is</span> <span m='2614250'>this</span>
  <span m='2614410'>going</span> <span m='2614510'>to</span> <span m='2614550'>use</span>
  <span m='2614790'>the</span> <span m='2614880'>cache</span> <span m='2615270'>well?</span>
  </p><p><span m='2617028'>AUDIENCE:</span> <span m='2617504'>[INAUDIBLE]</span> </p><p><span
  m='2619408'>PROFESSOR:</span> <span m='2619890'>Yeah</span> <span m='2620290'>eventually</span>
  <span m='2621350'>I</span> <span m='2621470'>get</span> <span m='2621690'>down</span>
  <span m='2621950'>to</span> <span m='2622040'>a</span> <span m='2622130'>size</span>
  <span m='2624150'>where</span> <span m='2625430'>the</span> <span m='2625580'>matrix</span>
  <span m='2625990'>that</span> <span m='2626060'>I'm</span> <span m='2626160'>working</span>
  <span m='2626530'>on</span> <span m='2626970'>fits</span> <span m='2627190'>into</span>
  <span m='2627410'>cache,</span> <span m='2628760'>and</span> <span m='2628910'>then</span>
  <span m='2629100'>all</span> <span m='2629380'>the</span> <span m='2629450'>rest</span>
  <span m='2629820'>of</span> <span m='2629950'>the</span> <span m='2630270'>operations</span>
  <span m='2630940'>I</span> <span m='2631080'>do</span> <span m='2631340'>are</span>
  <span m='2631470'>all</span> <span m='2631710'>going</span> <span m='2631810'>to</span>
  <span m='2631860'>be</span> <span m='2631970'>cache</span> <span m='2632390'>hits.</span>
  <span m='2634240'>It</span> <span m='2634640'>is</span> <span m='2636030'>taking</span>
  <span m='2636390'>something</span> <span m='2636860'>and</span> <span m='2636980'>it</span>
  <span m='2637390'>it's</span> <span m='2637740'>doing</span> <span m='2638330'>what</span>
  <span m='2638480'>the</span> <span m='2638570'>tiling</span> <span m='2639090'>is</span>
  <span m='2639260'>doing</span> <span m='2639820'>but</span> <span m='2640190'>doing</span>
  <span m='2640490'>it</span> <span m='2641110'>blindly.</span> </p><p><span m='2644210'>So</span>
  <span m='2644350'>let's</span> <span m='2644540'>take</span> <span m='2644740'>a</span>
  <span m='2644790'>look.</span> <span m='2644980'>Here's</span> <span m='2645260'>the</span>
  <span m='2645300'>recursive</span> <span m='2645770'>code.</span> <span m='2648000'>So</span>
  <span m='2648180'>here</span> <span m='2648470'>I</span> <span m='2648580'>have</span>
  <span m='2649890'>the</span> <span m='2650110'>base</span> <span m='2650480'>case</span>
  <span m='2651230'>if</span> <span m='2651520'>n</span> <span m='2651740'>is</span>
  <span m='2651880'>1,</span> <span m='2652300'>I</span> <span m='2652440'>basically</span>
  <span m='2653280'>have</span> <span m='2653570'>a</span> <span m='2653890'>one</span>
  <span m='2654120'>by</span> <span m='2654280'>one</span> <span m='2654480'>matrix</span>
  <span m='2654930'>and</span> <span m='2655010'>I</span> <span m='2655090'>just</span>
  <span m='2655310'>simply</span> <span m='2655770'>update</span> <span m='2656320'>c,</span>
  <span m='2656800'>with</span> <span m='2657090'>a</span> <span m='2657240'>times</span>
  <span m='2657610'>b.</span> <span m='2659460'>And</span> <span m='2659650'>otherwise</span>
  <span m='2660390'>what</span> <span m='2660520'>I</span> <span m='2660600'>do,</span>
  <span m='2660890'>is</span> <span m='2661060'>I'm</span> <span m='2661120'>going</span>
  <span m='2661200'>to</span> <span m='2661270'>do</span> <span m='2661420'>this</span>
  <span m='2661620'>by</span> <span m='2661770'>computing</span> <span m='2662260'>offsets.</span>
  <span m='2662890'>So</span> <span m='2663090'>generally</span> <span m='2663440'>when</span>
  <span m='2663570'>you're</span> <span m='2663690'>dealing</span> <span m='2664060'>with</span>
  <span m='2664960'>matrices,</span> <span m='2665590'>especially</span> <span m='2665950'>if</span>
  <span m='2665990'>you</span> <span m='2666080'>want</span> <span m='2666300'>fast</span>
  <span m='2666630'>code,</span> <span m='2666910'>I</span> <span m='2666990'>usually</span>
  <span m='2667300'>don't</span> <span m='2667590'>rely</span> <span m='2668510'>on</span>
  <span m='2668810'>two-dimensional</span> <span m='2670670'>addressing,</span> <span
  m='2671260'>but</span> <span m='2671410'>rather</span> <span m='2671750'>do</span>
  <span m='2671960'>the</span> <span m='2672140'>addressing</span> <span m='2672680'>myself</span>
  <span m='2673680'>and</span> <span m='2673920'>rely</span> <span m='2674350'>on</span>
  <span m='2674620'>the</span> <span m='2674900'>compiler</span> <span m='2675700'>to</span>
  <span m='2676030'>do</span> <span m='2676290'>common</span> <span m='2676620'>subexpression</span>
  <span m='2677280'>elimination.</span> </p><p><span m='2678470'>So,</span> <span
  m='2678690'>for</span> <span m='2678810'>example,</span> <span m='2679190'>here</span>
  <span m='2679440'>what</span> <span m='2679590'>I'm</span> <span m='2679670'>going</span>
  <span m='2679750'>to</span> <span m='2679840'>do</span> <span m='2680280'>is</span>
  <span m='2680980'>compute</span> <span m='2681440'>the</span> <span m='2681550'>offsets.</span>
  <span m='2682890'>So</span> <span m='2683080'>here's</span> <span m='2683310'>how</span>
  <span m='2683450'>I</span> <span m='2683560'>do</span> <span m='2683750'>it.</span>
  <span m='2684240'>So</span> <span m='2684390'>first</span> <span m='2684670'>of</span>
  <span m='2684770'>all,</span> <span m='2685390'>in</span> <span m='2685550'>practice</span>
  <span m='2686030'>what</span> <span m='2686170'>you</span> <span m='2686260'>do,</span>
  <span m='2686330'>is</span> <span m='2686440'>you</span> <span m='2686520'>don't</span>
  <span m='2686660'>go</span> <span m='2686770'>down</span> <span m='2686980'>to</span>
  <span m='2687090'>n equals 1.</span> <span m='2688360'>You</span> <span m='2688430'>have</span>
  <span m='2688510'>some</span> <span m='2688740'>cutoff.</span> <span m='2690300'>Maybe</span>
  <span m='2690700'>n</span> <span m='2690910'>is</span> <span m='2691150'>8</span>
  <span m='2691540'>or</span> <span m='2691640'>something.</span> <span m='2692220'>And</span>
  <span m='2692420'>at</span> <span m='2692620'>that</span> <span m='2692920'>point</span>
  <span m='2693210'>you</span> <span m='2693320'>go</span> <span m='2693570'>into</span>
  <span m='2693770'>a</span> <span m='2693810'>specialized</span> <span m='2694580'>routine</span>
  <span m='2695570'>that</span> <span m='2695760'>does</span> <span m='2695960'>a</span>
  <span m='2696030'>really</span> <span m='2696320'>good</span> <span m='2696630'>8</span>
  <span m='2696880'>by</span> <span m='2697050'>8</span> <span m='2697280'>multiply.</span>
  </p><p><span m='2698490'>And</span> <span m='2698640'>the</span> <span m='2698720'>reason</span>
  <span m='2699070'>for</span> <span m='2699190'>that</span> <span m='2699450'>is</span>
  <span m='2699600'>you</span> <span m='2700000'>don't</span> <span m='2700210'>want</span>
  <span m='2700350'>to</span> <span m='2700540'>have</span> <span m='2700730'>the</span>
  <span m='2700820'>function</span> <span m='2701240'>call</span> <span m='2701570'>overheads.</span>
  <span m='2702200'>This</span> <span m='2702390'>function</span> <span m='2702770'>call</span>
  <span m='2703380'>is</span> <span m='2703550'>expensive</span> <span m='2704190'>to</span>
  <span m='2704290'>do</span> <span m='2705370'>two</span> <span m='2705560'>floating</span>
  <span m='2705900'>point</span> <span m='2706130'>operations</span> <span m='2706750'>here.</span>
  <span m='2708040'>So</span> <span m='2708180'>you'd</span> <span m='2708310'>like</span>
  <span m='2708510'>to</span> <span m='2708600'>have</span> <span m='2708910'>a</span>
  <span m='2708960'>function</span> <span m='2709390'>call</span> <span m='2709740'>and</span>
  <span m='2709820'>then</span> <span m='2710020'>do</span> <span m='2710880'>100</span>
  <span m='2711200'>floating</span> <span m='2711500'>point</span> <span m='2711730'>operations</span>
  <span m='2712320'>or</span> <span m='2712400'>something.</span> <span m='2713380'>So</span>
  <span m='2713550'>that you</span> <span m='2713710'>get</span> <span m='2713840'>a</span>
  <span m='2713880'>better</span> <span m='2714140'>balance.</span> <span m='2715040'>Do</span>
  <span m='2715380'>people</span> <span m='2715700'>understand</span> <span m='2716160'>that?</span>
  </p><p><span m='2716370'>So</span> <span m='2716440'>normally</span> <span m='2717460'>to</span>
  <span m='2717580'>write</span> <span m='2717800'>recursive</span> <span m='2718270'>codes</span>
  <span m='2718660'>you</span> <span m='2718740'>want</span> <span m='2718850'>a</span>
  <span m='2718920'>course</span> <span m='2719360'>in</span> <span m='2719460'>the</span>
  <span m='2719540'>recursion.</span> <span m='2722210'>Make</span> <span m='2722420'>it</span>
  <span m='2722530'>so</span> <span m='2722620'>you're</span> <span m='2722760'>not</span>
  <span m='2723010'>going</span> <span m='2723240'>all</span> <span m='2723340'>go</span>
  <span m='2723360'>the</span> <span m='2723440'>into</span> <span m='2723490'>way</span>
  <span m='2723660'>down</span> <span m='2723910'>to</span> <span m='2724000'>n equals
  1.</span> <span m='2724760'>But</span> <span m='2724900'>rather</span> <span m='2725320'>are</span>
  <span m='2726200'>stopping</span> <span m='2726650'>short</span> <span m='2727310'>and</span>
  <span m='2727490'>then</span> <span m='2727670'>doing</span> <span m='2727970'>something</span>
  <span m='2728430'>that</span> <span m='2728590'>doesn't</span> <span m='2728870'>involve</span>
  <span m='2729380'>a</span> <span m='2729500'>lot</span> <span m='2729750'>of</span>
  <span m='2729860'>overhead</span> <span m='2731570'>in</span> <span m='2731780'>the</span>
  <span m='2732470'>base</span> <span m='2732750'>case</span> <span m='2733060'>of</span>
  <span m='2733200'>your</span> <span m='2733630'>recursion.</span> <span m='2734230'>But</span>
  <span m='2734380'>here</span> <span m='2734620'>I'll</span> <span m='2734730'>explain</span>
  <span m='2735180'>it</span> <span m='2736410'>as</span> <span m='2736560'>if</span>
  <span m='2736700'>we</span> <span m='2736760'>went</span> <span m='2736960'>all</span>
  <span m='2737050'>the</span> <span m='2737150'>way</span> <span m='2737260'>down</span>
  <span m='2737520'>to</span> <span m='2737610'>n equals 1.</span> </p><p><span m='2740590'>So</span>
  <span m='2740780'>then</span> <span m='2741050'>what</span> <span m='2741220'>we</span>
  <span m='2741380'>do</span> <span m='2741730'>is,</span> <span m='2742640'>if</span>
  <span m='2743150'>this</span> <span m='2743350'>is</span> <span m='2743500'>a</span>
  <span m='2743560'>submatrix,</span> <span m='2744980'>which</span> <span m='2745380'>is</span>
  <span m='2745490'>basically</span> <span m='2745940'>what</span> <span m='2746080'>I'm</span>
  <span m='2746160'>showing</span> <span m='2746480'>here.</span> <span m='2746650'>We</span>
  <span m='2746740'>have</span> <span m='2746840'>an</span> <span m='2746920'>n by
  n</span> <span m='2747520'>submatrix.</span> <span m='2748310'>And</span> <span
  m='2748530'>it's</span> <span m='2748770'>being</span> <span m='2748960'>pulled</span>
  <span m='2749300'>out</span> <span m='2749540'>on a</span> <span m='2749590'>matrix</span>
  <span m='2750340'>of</span> <span m='2750470'>size</span> <span m='2750860'>row</span>
  <span m='2751090'>size,</span> <span m='2751920'>of</span> <span m='2752070'>width</span>
  <span m='2752280'>row</span> <span m='2752520'>size.</span> </p><p><span m='2754690'>So</span>
  <span m='2754860'>what</span> <span m='2755000'>I</span> <span m='2755080'>can</span>
  <span m='2755290'>do</span> <span m='2755580'>is,</span> <span m='2755930'>if</span>
  <span m='2756080'>I</span> <span m='2756170'>want</span> <span m='2756360'>to</span>
  <span m='2756430'>know</span> <span m='2756720'>where</span> <span m='2757150'>the</span>
  <span m='2758110'>elements</span> <span m='2759160'>of</span> <span m='2759330'>the</span>
  <span m='2759420'>beginning</span> <span m='2759780'>of</span> <span m='2759930'>matrices</span>
  <span m='2760530'>are,</span> <span m='2761410'>well</span> <span m='2761580'>the</span>
  <span m='2761650'>first</span> <span m='2762000'>one</span> <span m='2762190'>is</span>
  <span m='2762320'>exactly</span> <span m='2763000'>the</span> <span m='2763130'>same</span>
  <span m='2763390'>place</span> <span m='2763910'>that</span> <span m='2764860'>the</span>
  <span m='2765260'>input</span> <span m='2765600'>matrix</span> <span m='2766060'>is.</span>
  <span m='2766770'>The</span> <span m='2766880'>second</span> <span m='2767270'>one</span>
  <span m='2768150'>is</span> <span m='2768360'>basically</span> <span m='2768930'>I</span>
  <span m='2769080'>have</span> <span m='2769280'>to</span> <span m='2769390'>add</span>
  <span m='2769780'>n over 2</span> <span m='2771500'>to</span> <span m='2771640'>the</span>
  <span m='2771950'>location</span> <span m='2772720'>in</span> <span m='2772910'>the</span>
  <span m='2773010'>array.</span> <span m='2774990'>The</span> <span m='2775160'>third</span>
  <span m='2775540'>one</span> <span m='2775720'>here,</span> <span m='2775980'>21,</span>
  <span m='2776960'>I</span> <span m='2777100'>have</span> <span m='2777340'>to</span>
  <span m='2777450'>basically</span> <span m='2778030'>add</span> <span m='2778730'>n
  over 2</span> <span m='2779220'>rows</span> <span m='2780950'>to</span> <span m='2781070'>get</span>
  <span m='2781260'>the</span> <span m='2781350'>starting</span> <span m='2781750'>point</span>
  <span m='2781970'>of</span> <span m='2782020'>that</span> <span m='2782260'>matrix.</span>
  </p><p><span m='2783440'>And</span> <span m='2783910'>for</span> <span m='2784000'>the</span>
  <span m='2784080'>last</span> <span m='2784470'>one</span> <span m='2784600'>I</span>
  <span m='2784690'>have</span> <span m='2784780'>to</span> <span m='2784880'>add</span>
  <span m='2785380'>n over 2</span> <span m='2786220'>and</span> <span m='2786730'>n
  over 2</span> <span m='2787300'>rows</span> <span m='2787870'>and</span> <span m='2788060'>n
  over 2 plus 1</span> <span m='2789240'>rows</span> <span m='2789960'>to</span> <span
  m='2790080'>get</span> <span m='2790280'>to</span> <span m='2790370'>that</span>
  <span m='2790620'>point.</span> <span m='2791070'>So</span> <span m='2791380'>I</span>
  <span m='2791520'>compute</span> <span m='2792030'>those</span> <span m='2792390'>and</span>
  <span m='2792620'>now</span> <span m='2792950'>I</span> <span m='2793120'>can</span>
  <span m='2793930'>recursively</span> <span m='2794560'>multiply</span> <span m='2795560'>with</span>
  <span m='2795690'>sizes</span> <span m='2796005'>of</span> <span m='2796320'>n over
  2</span> <span m='2799050'>and</span> <span m='2799730'>perform</span> <span m='2800200'>the</span>
  <span m='2801690'>program</span> <span m='2802050'>recursively.</span> <span m='2802620'>Yeah--</span>
  </p><p><span m='2808883'>AUDIENCE:</span> <span m='2809382'>So you said it</span>
  <span m='2809881'>rightly.</span> <span m='2810380'>You're</span> <span m='2810879'>blindly</span>
  <span m='2811378'>dividing</span> <span m='2811877'>the</span> <span m='2812376'>matrix</span>
  <span m='2812875'>up til</span> <span m='2813374'>you get something</span> <span
  m='2813873'>to fit the cache.</span> <span m='2814380'>So</span> <span m='2814850'>essentially--</span>
  </p><p><span m='2815230'>PROFESSOR:</span> <span m='2815670'>Well and you're continuing.</span>
  <span m='2816520'>The</span> <span m='2817410'>algorithm</span> <span m='2818230'>is</span>
  <span m='2818370'>completely</span> <span m='2818720'>blind</span> <span m='2819080'>all</span>
  <span m='2819220'>the</span> <span m='2819290'>way</span> <span m='2819460'>down</span>
  <span m='2819710'>to</span> <span m='2819810'>n equals 1.</span> </p><p><span m='2823418'>AUDIENCE:</span>
  <span m='2823911'>This</span> <span m='2824404'>could</span> <span m='2824897'>never</span>
  <span m='2825390'>be</span> <span m='2825883'>better</span> <span m='2826869'>if</span>
  <span m='2827362'>the other one-- your computer's version</span> <span m='2827855'>is</span>
  <span m='2828348'>well-tuned.</span> <span m='2829334'>Because the</span> <span
  m='2829827'>applications</span> <span m='2830320'>are the same,</span> <span m='2830813'>but
  this one</span> <span m='2831306'>you have all the</span> <span m='2831799'>overhead</span>
  <span m='2832292'>from the</span> <span m='2832785'>[INAUDIBLE].</span> </p><p><span
  m='2833278'>PROFESSOR:</span> <span m='2833771'>Could be.</span> </p><p><span m='2834757'>AUDIENCE:</span>
  <span m='2835250'>At the end,</span> <span m='2835743'>you still need</span> <span
  m='2836236'>to make</span> <span m='2836729'>a</span> <span m='2837222'>multiplication</span>
  <span m='2837715'>and then</span> <span m='2838208'>go back and</span> <span m='2838701'>look</span>
  <span m='2839220'>at all of the--</span> </p><p><span m='2839610'>PROFESSOR:</span>
  <span m='2839840'>Could</span> <span m='2840135'>be.</span> <span m='2840430'>So</span>
  <span m='2841390'>let's</span> <span m='2841640'>discuss</span> <span m='2842010'>that</span>
  <span m='2842190'>later</span> <span m='2842560'>at</span> <span m='2842720'>the</span>
  <span m='2842910'>end</span> <span m='2843480'>when</span> <span m='2843660'>we</span>
  <span m='2843790'>talk</span> <span m='2844040'>about</span> <span m='2848800'>the</span>
  <span m='2848930'>differences between the</span> <span m='2849040'>algorithms.</span>
  <span m='2849420'>Let's</span> <span m='2849600'>at</span> <span m='2849680'>this</span>
  <span m='2849860'>point,</span> <span m='2850070'>just</span> <span m='2850230'>try</span>
  <span m='2850360'>to</span> <span m='2850450'>understand</span> <span m='2851140'>what's</span>
  <span m='2851560'>going</span> <span m='2851800'>on</span> <span m='2852240'>in</span>
  <span m='2852340'>the</span> <span m='2852460'>algorithm.</span> <span m='2853230'>Question--</span>
  </p><p><span m='2854572'>AUDIENCE:</span> <span m='2855068'>[INAUDIBLE]</span> </p><p><span
  m='2866476'>PROFESSOR:</span> <span m='2866990'>n over 2</span> <span m='2867910'>times</span>
  <span m='2868210'>row size</span> <span m='2868510'>plus--</span> <span m='2870900'>plus
  n over 2.</span> <span m='2871070'>It</span> <span m='2871240'>should</span> <span
  m='2871430'>be</span> <span m='2871520'>row size plus 1.</span> <span m='2874040'>You're</span>
  <span m='2874230'>right.</span> <span m='2874920'>Good,</span> <span m='2875280'>bug.</span>
  <span m='2877470'>Should</span> <span m='2877630'>be</span> <span m='2877780'>n
  over 2</span> <span m='2878280'>times</span> <span m='2878720'>row size plus 1.</span>
  </p><p><span m='2883940'>So</span> <span m='2884090'>let's</span> <span m='2884310'>analyze</span>
  <span m='2884780'>the</span> <span m='2884860'>work</span> <span m='2885230'>assuming</span>
  <span m='2885590'>the</span> <span m='2885670'>code</span> <span m='2886040'>actually</span>
  <span m='2886330'>did</span> <span m='2886530'>work.</span> <span m='2889780'>So</span>
  <span m='2889970'>the</span> <span m='2890060'>work</span> <span m='2890490'>we</span>
  <span m='2890730'>can</span> <span m='2890910'>write</span> <span m='2891090'>a</span>
  <span m='2891130'>recurrence</span> <span m='2891740'>for.</span> <span m='2894430'>So</span>
  <span m='2894800'>here</span> <span m='2895510'>we</span> <span m='2895680'>have</span>
  <span m='2895980'>the</span> <span m='2896380'>work</span> <span m='2897490'>to</span>
  <span m='2897970'>solve</span> <span m='2898410'>an</span> <span m='2898500'>n</span>
  <span m='2898710'>by</span> <span m='2898880'>n</span> <span m='2899110'>matrix</span>
  <span m='2899860'>problem.</span> </p><p><span m='2900980'>Well if</span> <span
  m='2901330'>n</span> <span m='2901530'>is</span> <span m='2901690'>1,</span> <span
  m='2902810'>then</span> <span m='2903640'>it's</span> <span m='2903850'>just</span>
  <span m='2904050'>order</span> <span m='2904370'>one</span> <span m='2904690'>work--</span>
  <span m='2905510'>constant</span> <span m='2905920'>amount</span> <span m='2906120'>of</span>
  <span m='2906220'>work.</span> <span m='2908270'>But</span> <span m='2908480'>if</span>
  <span m='2908550'>n</span> <span m='2908770'>is</span> <span m='2908970'>bigger</span>
  <span m='2909360'>than</span> <span m='2909570'>1,</span> <span m='2910510'>then</span>
  <span m='2910920'>I'm</span> <span m='2911040'>solving</span> <span m='2911620'>eight</span>
  <span m='2911810'>problems</span> <span m='2912570'>of</span> <span m='2912700'>size</span>
  <span m='2913120'>n</span> <span m='2913290'>over</span> <span m='2913520'>2,</span>
  <span m='2915130'>plus</span> <span m='2915970'>doing</span> <span m='2916210'>a</span>
  <span m='2916300'>constant</span> <span m='2916650'>amount</span> <span m='2916890'>of</span>
  <span m='2916980'>work</span> <span m='2917270'>to</span> <span m='2917400'>divide</span>
  <span m='2917870'>all</span> <span m='2918020'>those</span> <span m='2918270'>up.</span>
  <span m='2921090'>So</span> <span m='2921230'>everybody</span> <span m='2921650'>understand</span>
  <span m='2922080'>where</span> <span m='2922220'>I</span> <span m='2922270'>get</span>
  <span m='2922520'>this</span> <span m='2922960'>recurrence?</span> </p><p><span
  m='2923580'>Now</span> <span m='2923660'>normally,</span> <span m='2926820'>as</span>
  <span m='2926990'>you know,</span> <span m='2927290'>when</span> <span m='2927440'>you</span>
  <span m='2927560'>do</span> <span m='2928610'>algorithmic</span> <span m='2929880'>work,</span>
  <span m='2930360'>we</span> <span m='2930480'>usually</span> <span m='2930980'>omit</span>
  <span m='2931960'>this</span> <span m='2932590'>first</span> <span m='2933020'>line</span>
  <span m='2933330'>because</span> <span m='2933570'>we</span> <span m='2933680'>assume</span>
  <span m='2934110'>a</span> <span m='2934200'>base</span> <span m='2935210'>case</span>
  <span m='2935540'>of</span> <span m='2936990'>constant</span> <span m='2937460'>if</span>
  <span m='2937590'>it's</span> <span m='2937750'>one.</span> <span m='2938260'>I'm</span>
  <span m='2938480'>actually</span> <span m='2938720'>going</span> <span m='2938850'>to</span>
  <span m='2938930'>keep</span> <span m='2939250'>it.</span> <span m='2939650'>And</span>
  <span m='2939790'>the</span> <span m='2939870'>reason</span> <span m='2940130'>is</span>
  <span m='2940220'>because</span> <span m='2940380'>when</span> <span m='2940500'>we</span>
  <span m='2940620'>do</span> <span m='2940740'>caching</span> <span m='2941540'>the</span>
  <span m='2941640'>basic</span> <span m='2942090'>cases</span> <span m='2942540'>are</span>
  <span m='2942770'>important.</span> <span m='2945890'>So</span> <span m='2946020'>everybody</span>
  <span m='2946380'>understand</span> <span m='2946810'>where</span> <span m='2946930'>this</span>
  <span m='2948360'>recurrence</span> <span m='2948770'>came</span> <span m='2948950'>from?</span>
  </p><p><span m='2949530'>So</span> <span m='2949700'>I</span> <span m='2949800'>can</span>
  <span m='2949960'>use</span> <span m='2950160'>the</span> <span m='2950260'>master</span>
  <span m='2950720'>theorem</span> <span m='2951870'>or</span> <span m='2952370'>something</span>
  <span m='2953090'>like</span> <span m='2953320'>that</span> <span m='2953600'>to</span>
  <span m='2953690'>solve</span> <span m='2954140'>this.</span> <span m='2954380'>In</span>
  <span m='2954450'>which</span> <span m='2954640'>case</span> <span m='2954930'>the</span>
  <span m='2955040'>answer</span> <span m='2955410'>for</span> <span m='2955540'>this</span>
  <span m='2955770'>is</span> <span m='2955890'>what?</span> <span m='2957060'>Those</span>
  <span m='2957300'>of</span> <span m='2957380'>you</span> <span m='2957580'>who</span>
  <span m='2958090'>have</span> <span m='2958290'>the</span> <span m='2958380'>master</span>
  <span m='2958760'>theorem</span> <span m='2959060'>in</span> <span m='2959150'>your</span>
  <span m='2959280'>hip</span> <span m='2959460'>pocket.</span> </p><p><span m='2963170'>What's</span>
  <span m='2963485'>the</span> <span m='2963800'>solution of this</span> <span m='2963950'>recurrence?</span>
  <span m='2967890'>People</span> <span m='2968150'>remember?</span> <span m='2968500'>Who's</span>
  <span m='2969010'>has</span> <span m='2969110'>heard</span> <span m='2969370'>of</span>
  <span m='2969450'>the</span> <span m='2969530'>master</span> <span m='2969900'>theorem?</span>
  <span m='2971920'>I</span> <span m='2972000'>thought</span> <span m='2972480'>that</span>
  <span m='2972680'>was</span> <span m='2972870'>kind</span> <span m='2972980'>of</span>
  <span m='2973090'>a</span> <span m='2973170'>prerequisite</span> <span m='2973800'>or</span>
  <span m='2973910'>something</span> <span m='2974260'>of this</span> <span m='2974430'>class,</span>
  <span m='2974750'>right?</span> <span m='2978770'>So</span> <span m='2979180'>you</span>
  <span m='2979360'>might</span> <span m='2979550'>want</span> <span m='2979680'>to</span>
  <span m='2979720'>brush</span> <span m='2980040'>up</span> <span m='2980200'>on</span>
  <span m='2980280'>the</span> <span m='2980350'>master</span> <span m='2980750'>theorem</span>
  <span m='2981080'>for</span> <span m='2981190'>the</span> <span m='2981290'>quiz</span>
  <span m='2981600'>next</span> <span m='2981880'>week.</span> </p><p><span m='2985230'>So</span>
  <span m='2985550'>basically</span> <span m='2986730'>it's</span> <span m='2987600'>a
  n over b,</span> <span m='2988470'>so</span> <span m='2988620'>it's</span> <span
  m='2988820'>n to the log base 2 of 8.</span> <span m='2993080'>So</span> <span m='2993220'>that's</span>
  <span m='2993460'>n cubed,</span> <span m='2994640'>n to the log base 2 of 8 is
  n to the n cubed.</span> <span m='2998180'>And</span> <span m='2998290'>that's</span>
  <span m='2998490'>bigger</span> <span m='2998880'>than</span> <span m='2999160'>the</span>
  <span m='2999280'>order</span> <span m='2999560'>one</span> <span m='2999810'>here,</span>
  <span m='3000160'>so</span> <span m='3000310'>the</span> <span m='3000440'>answer</span>
  <span m='3000780'>is</span> <span m='3000890'>order</span> <span m='3001190'>n</span>
  <span m='3001350'>cubed.</span> <span m='3002080'>Which</span> <span m='3002340'>is</span>
  <span m='3002810'>a</span> <span m='3002900'>relief,</span> <span m='3003320'>right?</span>
  <span m='3003700'>Because</span> <span m='3005510'>if</span> <span m='3005740'>weren't</span>
  <span m='3006060'>order</span> <span m='3006810'>n cubed</span> <span m='3007370'>we</span>
  <span m='3007520'>would</span> <span m='3007720'>be</span> <span m='3008630'>doing</span>
  <span m='3008870'>a</span> <span m='3008930'>lot</span> <span m='3009140'>more</span>
  <span m='3009320'>work</span> <span m='3011360'>than</span> <span m='3012010'>one</span>
  <span m='3012270'>of</span> <span m='3012360'>the</span> <span m='3012540'>looping</span>
  <span m='3012910'>algorithms.</span> </p><p><span m='3015260'>However,</span> <span
  m='3015590'>let's</span> <span m='3015870'>actually</span> <span m='3016210'>go</span>
  <span m='3016430'>through</span> <span m='3017110'>and</span> <span m='3017360'>understand</span>
  <span m='3018120'>where</span> <span m='3018270'>that</span> <span m='3018530'>n
  cubed</span> <span m='3019020'>comes</span> <span m='3019320'>from.</span> <span
  m='3021120'>And</span> <span m='3021300'>to</span> <span m='3021390'>do</span> <span
  m='3021600'>that</span> <span m='3022320'>I'm</span> <span m='3022410'>going</span>
  <span m='3022490'>to</span> <span m='3022530'>use</span> <span m='3022880'>the</span>
  <span m='3022970'>technique</span> <span m='3023440'>of</span> <span m='3023550'>a</span>
  <span m='3023680'>recursive</span> <span m='3024250'>tree,</span> <span m='3025320'>which</span>
  <span m='3025550'>I</span> <span m='3025620'>think</span> <span m='3026420'>all</span>
  <span m='3026600'>of</span> <span m='3026770'>you</span> <span m='3026900'>have</span>
  <span m='3027030'>seen.</span> <span m='3027380'>But</span> <span m='3027530'>let</span>
  <span m='3027690'>me</span> <span m='3027800'>go</span> <span m='3027970'>through</span>
  <span m='3028200'>it</span> <span m='3028400'>slowly</span> <span m='3028840'>here</span>
  <span m='3029460'>to</span> <span m='3029580'>make</span> <span m='3029770'>sure,</span>
  <span m='3030060'>because</span> <span m='3030340'>we're</span> <span m='3030440'>going</span>
  <span m='3030520'>to</span> <span m='3030590'>do</span> <span m='3030770'>it</span>
  <span m='3030820'>again</span> <span m='3031410'>when</span> <span m='3031660'>we</span>
  <span m='3031850'>do</span> <span m='3031990'>cache</span> <span m='3032360'>misses</span>
  <span m='3032780'>and</span> <span m='3032920'>it's going to</span> <span m='3033080'>be</span>
  <span m='3033190'>more</span> <span m='3033390'>complicated.</span> </p><p><span
  m='3035940'>So</span> <span m='3036070'>here's</span> <span m='3036330'>the</span>
  <span m='3036460'>idea.</span> <span m='3037080'>I</span> <span m='3037210'>write</span>
  <span m='3037520'>down</span> <span m='3037880'>the</span> <span m='3038090'>left</span>
  <span m='3038370'>hand</span> <span m='3038570'>side</span> <span m='3038890'>the</span>
  <span m='3038980'>recurrence,</span> <span m='3040760'>w of n.</span> <span m='3042160'>And</span>
  <span m='3042300'>now</span> <span m='3042490'>what</span> <span m='3042640'>I</span>
  <span m='3042730'>do</span> <span m='3042930'>is</span> <span m='3043080'>I</span>
  <span m='3043180'>substitute,</span> <span m='3044400'>and</span> <span m='3044540'>I</span>
  <span m='3044610'>draw</span> <span m='3044850'>it</span> <span m='3044910'>out</span>
  <span m='3045090'>as</span> <span m='3045230'>a</span> <span m='3045290'>tree.</span>
  <span m='3046040'>I</span> <span m='3046140'>have</span> <span m='3046370'>eight</span>
  <span m='3046660'>problems</span> <span m='3047240'>of</span> <span m='3047320'>size</span>
  <span m='3047730'>n over 2.</span> <span m='3049580'>So</span> <span m='3049780'>what</span>
  <span m='3049890'>I</span> <span m='3049990'>do</span> <span m='3050270'>is</span>
  <span m='3051350'>I</span> <span m='3051540'>replace</span> <span m='3052170'>that</span>
  <span m='3052670'>with</span> <span m='3053450'>the</span> <span m='3053570'>thing</span>
  <span m='3053850'>that's</span> <span m='3054030'>on</span> <span m='3054190'>the</span>
  <span m='3054350'>right</span> <span m='3054550'>hand</span> <span m='3054740'>side,</span>
  <span m='3054960'>I've</span> <span m='3055000'>dropped</span> <span m='3055540'>the</span>
  <span m='3056220'>theta</span> <span m='3056530'>here,</span> <span m='3057350'>but</span>
  <span m='3057680'>basically</span> <span m='3058170'>put</span> <span m='3058460'>just</span>
  <span m='3058700'>a</span> <span m='3058750'>constant</span> <span m='3059250'>one</span>
  <span m='3059480'>here.</span> <span m='3059640'>Because</span> <span m='3059820'>I'll</span>
  <span m='3059950'>take</span> <span m='3060200'>into</span> <span m='3060400'>account</span>
  <span m='3060730'>the</span> <span m='3060820'>thetas</span> <span m='3061290'>at</span>
  <span m='3061390'>the</span> <span m='3061530'>end.</span> </p><p><span m='3062440'>So</span>
  <span m='3062550'>I</span> <span m='3062640'>have</span> <span m='3062740'>a</span>
  <span m='3062800'>one</span> <span m='3063070'>here,</span> <span m='3063820'>and</span>
  <span m='3064050'>then</span> <span m='3064360'>I</span> <span m='3064670'>have,</span>
  <span m='3068200'>loops</span> <span m='3068510'>that</span> <span m='3068670'>should</span>
  <span m='3068820'>be</span> <span m='3068960'>a</span> <span m='3069000'>w.</span>
  <span m='3070870'>Should</span> <span m='3071050'>be</span> <span m='3071220'>w
  n over 2.</span> <span m='3073110'>That's</span> <span m='3073340'>a</span> <span
  m='3073420'>bug</span> <span m='3073850'>there.</span> </p><p><span m='3076060'>And</span>
  <span m='3076230'>then</span> <span m='3076390'>I</span> <span m='3076530'>replace</span>
  <span m='3077000'>each</span> <span m='3077190'>of</span> <span m='3077280'>those.</span>
  <span m='3081420'>OK,</span> <span m='3082232'>wn over 2,</span> <span m='3085500'>sorry</span>
  <span m='3085630'>that</span> <span m='3085810'>should</span> <span m='3085940'>be</span>
  <span m='3086060'>wn over 4.</span> <span m='3087795'>Ah,</span> <span m='3088200'>more</span>
  <span m='3088400'>bugs.</span> <span m='3090240'>I'll</span> <span m='3090410'>fix</span>
  <span m='3090630'>them</span> <span m='3090780'>up</span> <span m='3091010'>on</span>
  <span m='3092430'>after</span> <span m='3092930'>lecture.</span> </p><p><span m='3093240'>So</span>
  <span m='3093370'>this</span> <span m='3093470'>should</span> <span m='3093600'>be</span>
  <span m='3093720'>w of n over 4.</span> <span m='3095760'>And</span> <span m='3095850'>we</span>
  <span m='3095950'>go</span> <span m='3096140'>all</span> <span m='3096230'>the</span>
  <span m='3096320'>way</span> <span m='3096460'>down</span> <span m='3096770'>to</span>
  <span m='3096840'>the</span> <span m='3096930'>bottom</span> <span m='3098480'>to</span>
  <span m='3098630'>where</span> <span m='3098880'>I</span> <span m='3098970'>hit</span>
  <span m='3099180'>the</span> <span m='3099260'>base</span> <span m='3099630'>case</span>
  <span m='3100950'>of</span> <span m='3101670'>theta 1.</span> <span m='3104410'>So</span>
  <span m='3104570'>I</span> <span m='3104630'>built</span> <span m='3104950'>out</span>
  <span m='3105140'>this</span> <span m='3105330'>big</span> <span m='3105620'>tree</span>
  <span m='3106190'>that</span> <span m='3106360'>represents,</span> <span m='3107600'>if</span>
  <span m='3107720'>you</span> <span m='3107810'>think</span> <span m='3108020'>about</span>
  <span m='3108280'>it,</span> <span m='3108400'>that's</span> <span m='3108600'>exactly</span>
  <span m='3109150'>what</span> <span m='3109370'>the</span> <span m='3109500'>algorithm</span>
  <span m='3109920'>is</span> <span m='3110020'>going</span> <span m='3110130'>to</span>
  <span m='3110200'>do.</span> <span m='3110350'>It's</span> <span m='3110480'>going</span>
  <span m='3110560'>to</span> <span m='3110610'>walk</span> <span m='3111050'>this</span>
  <span m='3111270'>tree</span> <span m='3112200'>doing</span> <span m='3112500'>the</span>
  <span m='3112580'>work.</span> <span m='3113140'>And</span> <span m='3113290'>what</span>
  <span m='3113430'>I've</span> <span m='3113560'>just</span> <span m='3113760'>simply</span>
  <span m='3114050'>put</span> <span m='3114220'>up</span> <span m='3114410'>here</span>
  <span m='3114590'>is</span> <span m='3114670'>to</span> <span m='3114760'>work</span>
  <span m='3115000'>it</span> <span m='3115120'>does</span> <span m='3115380'>at</span>
  <span m='3115450'>every</span> <span m='3115660'>level.</span> </p><p><span m='3120450'>So</span>
  <span m='3121130'>the</span> <span m='3121210'>first</span> <span m='3121580'>thing</span>
  <span m='3121800'>we</span> <span m='3121900'>want</span> <span m='3122110'>to</span>
  <span m='3122170'>do</span> <span m='3122420'>is</span> <span m='3122660'>figure</span>
  <span m='3122880'>out</span> <span m='3123020'>what's</span> <span m='3123240'>the</span>
  <span m='3123320'>height</span> <span m='3123640'>of</span> <span m='3123800'>this</span>
  <span m='3123960'>tree.</span> <span m='3124480'>Can</span> <span m='3124610'>somebody</span>
  <span m='3124860'>tell</span> <span m='3125050'>me</span> <span m='3125160'>what</span>
  <span m='3125330'>the</span> <span m='3125400'>height</span> <span m='3125650'>of</span>
  <span m='3125730'>the</span> <span m='3125810'>tree</span> <span m='3126060'>is?</span>
  <span m='3130479'>It</span> <span m='3130970'>is</span> <span m='3131240'>a</span>
  <span m='3131300'>log n.</span> <span m='3131830'>What's</span> <span m='3131980'>the</span>
  <span m='3132120'>base?</span> <span m='3133830'>Log base 2 of n,</span> <span m='3134100'>base</span>
  <span m='3134940'>because</span> <span m='3135240'>at</span> <span m='3135320'>every</span>
  <span m='3135570'>level</span> <span m='3136400'>if</span> <span m='3136570'>I</span>
  <span m='3136670'>hadn't</span> <span m='3136950'>made</span> <span m='3137120'>a</span>
  <span m='3137160'>mistake</span> <span m='3137590'>here,</span> <span m='3137820'>I'm</span>
  <span m='3137950'>actually</span> <span m='3138210'>having</span> <span m='3138680'>the</span>
  <span m='3138810'>argument.</span> <span m='3141280'>So</span> <span m='3141420'>I'm</span>
  <span m='3141500'>having</span> <span m='3141860'>the</span> <span m='3141980'>argument</span>
  <span m='3142660'>at</span> <span m='3142810'>each</span> <span m='3143010'>level.</span>
  <span m='3144250'>So</span> <span m='3144480'>the</span> <span m='3144740'>height</span>
  <span m='3145070'>is</span> <span m='3145250'>log base 2 of n.</span> <span m='3146610'>So</span>
  <span m='3146780'>LG</span> <span m='3147310'>is</span> <span m='3147520'>notation</span>
  <span m='3148060'>for</span> <span m='3148180'>log</span> <span m='3148450'>base</span>
  <span m='3148730'>2.</span> </p><p><span m='3151720'>So</span> <span m='3151910'>if</span>
  <span m='3151990'>I</span> <span m='3152100'>have</span> <span m='3152360'>log base
  2 of n,</span> <span m='3153490'>I can</span> <span m='3153700'>count</span> <span
  m='3154030'>how</span> <span m='3154240'>many</span> <span m='3154450'>leaves</span>
  <span m='3154930'>there</span> <span m='3155120'>are</span> <span m='3155330'>to</span>
  <span m='3155450'>this</span> <span m='3155640'>tree.</span> <span m='3156940'>So</span>
  <span m='3157060'>how</span> <span m='3157210'>many</span> <span m='3157400'>leaves</span>
  <span m='3157750'>are</span> <span m='3157900'>there?</span> <span m='3160350'>Well</span>
  <span m='3160560'>I'm</span> <span m='3160710'>branching</span> <span m='3161410'>a</span>
  <span m='3161450'>factor</span> <span m='3161900'>of</span> <span m='3162110'>eight</span>
  <span m='3162460'>at every</span> <span m='3162880'>level.</span> </p><p><span m='3165200'>And</span>
  <span m='3165330'>if</span> <span m='3165430'>I'm</span> <span m='3165530'>going</span>
  <span m='3165880'>log base 2</span> <span m='3166900'>levels,</span> <span m='3168110'>the
  number of</span> <span m='3168490'>leaves</span> <span m='3169030'>is</span> <span
  m='3169680'>8 to the log base 2.</span> <span m='3172030'>So</span> <span m='3172250'>8
  to the log base 2 of n.</span> <span m='3174550'>And</span> <span m='3174680'>then</span>
  <span m='3174810'>with</span> <span m='3174930'>a</span> <span m='3174970'>little</span>
  <span m='3175200'>bit</span> <span m='3175330'>of</span> <span m='3175410'>algebraic</span>
  <span m='3175980'>magic</span> <span m='3176500'>that</span> <span m='3176670'>turns</span>
  <span m='3176910'>out</span> <span m='3177100'>that's</span> <span m='3177300'>the</span>
  <span m='3177370'>same</span> <span m='3177730'>as</span> <span m='3178050'>n to
  the log base 2 of 8.</span> <span m='3182140'>And</span> <span m='3182350'>that</span>
  <span m='3182700'>is</span> <span m='3182900'>equal</span> <span m='3183150'>to</span>
  <span m='3183230'>n</span> <span m='3183450'>cubed.</span> <span m='3185710'>So</span>
  <span m='3185830'>I</span> <span m='3185890'>end</span> <span m='3186030'>up</span>
  <span m='3186150'>with</span> <span m='3186300'>n</span> <span m='3186530'>cubed</span>
  <span m='3186830'>leaves.</span> </p><p><span m='3188820'>Now</span> <span m='3189120'>let's</span>
  <span m='3189420'>add</span> <span m='3189740'>up</span> <span m='3190030'>all</span>
  <span m='3190320'>the</span> <span m='3190390'>work</span> <span m='3190740'>that's</span>
  <span m='3190950'>in</span> <span m='3191050'>here.</span> <span m='3192750'>So</span>
  <span m='3193200'>what</span> <span m='3193370'>I</span> <span m='3193450'>do</span>
  <span m='3193650'>is</span> <span m='3193760'>I</span> <span m='3193860'>add</span>
  <span m='3194050'>across</span> <span m='3194320'>the</span> <span m='3194580'>rows.</span>
  <span m='3194940'>So the</span> <span m='3195110'>top</span> <span m='3195470'>level</span>
  <span m='3195810'>I've</span> <span m='3196020'>got</span> <span m='3196390'>work</span>
  <span m='3196640'>of</span> <span m='3196780'>one.</span> <span m='3198020'>The</span>
  <span m='3198140'>next</span> <span m='3198450'>level</span> <span m='3198740'>I</span>
  <span m='3198850'>work</span> <span m='3199160'>of</span> <span m='3199270'>eight.</span>
  <span m='3200220'>The</span> <span m='3200430'>next</span> <span m='3200640'>I have</span>
  <span m='3200750'>work</span> <span m='3201290'>of</span> <span m='3201670'>64.</span>
  <span m='3202690'>Do</span> <span m='3202890'>people</span> <span m='3203150'>see</span>
  <span m='3203300'>the</span> <span m='3203400'>pattern?</span> <span m='3205340'>The</span>
  <span m='3205470'>work</span> <span m='3205780'>is</span> <span m='3205940'>growing</span>
  <span m='3206280'>how?</span> <span m='3208830'>Geometrically.</span> </p><p><span
  m='3211190'>And at</span> <span m='3211470'>this</span> <span m='3211690'>level</span>
  <span m='3212010'>I</span> <span m='3212110'>know</span> <span m='3212410'>that</span>
  <span m='3212560'>if</span> <span m='3212750'>I</span> <span m='3212870'>add</span>
  <span m='3213060'>up</span> <span m='3213210'>all</span> <span m='3213390'>the</span>
  <span m='3213775'>leaves</span> <span m='3214160'>I've</span> <span m='3214390'>got</span>
  <span m='3215510'>work</span> <span m='3216150'>of</span> <span m='3216970'>n cubed.</span>
  <span m='3219000'>Because</span> <span m='3219200'>I've</span> <span m='3219290'>got</span>
  <span m='3219470'>n cubed</span> <span m='3219910'>leaves,</span> <span m='3220380'>each</span>
  <span m='3220590'>of</span> <span m='3220700'>them</span> <span m='3220800'>taking</span>
  <span m='3221140'>a</span> <span m='3221200'>constant.</span> <span m='3222270'>And</span>
  <span m='3222400'>so</span> <span m='3222520'>this</span> <span m='3222690'>is</span>
  <span m='3222860'>geometrically</span> <span m='3223570'>increasing,</span> <span
  m='3224140'>which</span> <span m='3224320'>means</span> <span m='3224710'>that</span>
  <span m='3224840'>it's</span> <span m='3225090'>all</span> <span m='3225470'>born</span>
  <span m='3225810'>in</span> <span m='3225880'>the</span> <span m='3225980'>leaves.</span>
  </p><p><span m='3226570'>So</span> <span m='3226740'>the</span> <span m='3226850'>total</span>
  <span m='3227180'>work</span> <span m='3227410'>is</span> <span m='3227550'>order</span>
  <span m='3227820'>n</span> <span m='3228030'>cubed.</span> <span m='3231600'>And</span>
  <span m='3231870'>that's</span> <span m='3232110'>nice.</span> <span m='3232430'>It's</span>
  <span m='3232560'>the</span> <span m='3232640'>same</span> <span m='3232890'>work</span>
  <span m='3233130'>is</span> <span m='3233270'>the</span> <span m='3233350'>looping</span>
  <span m='3233690'>versions.</span> <span m='3235220'>Because</span> <span m='3235480'>we</span>
  <span m='3235570'>don't</span> <span m='3235690'>want</span> <span m='3235810'>to</span>
  <span m='3235850'>increase</span> <span m='3236240'>that.</span> <span m='3241140'>Questions?</span>
  <span m='3241730'>Because</span> <span m='3241900'>now</span> <span m='3242100'>we're</span>
  <span m='3242170'>going</span> <span m='3242250'>to</span> <span m='3242320'>do</span>
  <span m='3242450'>cache</span> <span m='3242820'>misses</span> <span m='3243230'>and</span>
  <span m='3243320'>it's</span> <span m='3243440'>going</span> <span m='3243550'>to</span>
  <span m='3243600'>get</span> <span m='3243750'>hairy,</span> <span m='3245610'>not</span>
  <span m='3245810'>too</span> <span m='3245940'>hairy,</span> <span m='3246260'>but</span>
  <span m='3247100'>hairier.</span> </p><p><span m='3253810'>So</span> <span m='3254210'>here</span>
  <span m='3254360'>we're</span> <span m='3254440'>going</span> <span m='3254520'>to</span>
  <span m='3254790'>cache</span> <span m='3255220'>misses.</span> <span m='3255540'>So</span>
  <span m='3255640'>the</span> <span m='3255730'>first</span> <span m='3256090'>thing</span>
  <span m='3256280'>is</span> <span m='3256430'>coming</span> <span m='3256730'>up</span>
  <span m='3256850'>with</span> <span m='3256990'>a</span> <span m='3257040'>recurrence.</span>
  <span m='3257690'>And</span> <span m='3257800'>this</span> <span m='3257940'>is</span>
  <span m='3258070'>probably</span> <span m='3258430'>the</span> <span m='3258510'>hardest</span>
  <span m='3258950'>part,</span> <span m='3261440'>except</span> <span m='3261770'>for</span>
  <span m='3261830'>the</span> <span m='3261960'>other</span> <span m='3262180'>hard</span>
  <span m='3262460'>part</span> <span m='3262700'>which</span> <span m='3262870'>is</span>
  <span m='3262950'>solving the</span> <span m='3263340'>recurrence.</span> </p><p><span
  m='3266270'>So</span> <span m='3266590'>here</span> <span m='3266910'>what</span>
  <span m='3267110'>we're</span> <span m='3267250'>doing</span> <span m='3267720'>is,</span>
  <span m='3268280'>we</span> <span m='3268380'>have</span> <span m='3268520'>the</span>
  <span m='3268600'>same</span> <span m='3268940'>thing</span> <span m='3269360'>is</span>
  <span m='3269670'>that</span> <span m='3269910'>I'm</span> <span m='3270050'>solving</span>
  <span m='3270810'>eight</span> <span m='3271200'>problems</span> <span m='3271950'>of</span>
  <span m='3272070'>size</span> <span m='3272460'>n over 2</span> <span m='3273590'>and</span>
  <span m='3274940'>to</span> <span m='3275070'>do</span> <span m='3275460'>the</span>
  <span m='3275570'>work</span> <span m='3275900'>in</span> <span m='3276020'>here.</span>
  <span m='3276360'>I'm</span> <span m='3276490'>taking</span> <span m='3276940'>basically</span>
  <span m='3277480'>order</span> <span m='3277780'>one</span> <span m='3278110'>cache</span>
  <span m='3278480'>misses.</span> <span m='3279580'>However</span> <span m='3280140'>I</span>
  <span m='3280240'>do,</span> <span m='3281060'>those</span> <span m='3281520'>things</span>
  <span m='3281750'>work</span> <span m='3282010'>out.</span> <span m='3284440'>Plus</span>
  <span m='3284680'>the</span> <span m='3284760'>cache</span> <span m='3285090'>misses</span>
  <span m='3285440'>I</span> <span m='3285550'>have</span> <span m='3285830'>in</span>
  <span m='3286010'>there.</span> </p><p><span m='3286920'>But</span> <span m='3287080'>then</span>
  <span m='3287250'>at</span> <span m='3287390'>some</span> <span m='3287720'>point,</span>
  <span m='3289300'>when</span> <span m='3289500'>I'm</span> <span m='3289620'>claiming</span>
  <span m='3290230'>is</span> <span m='3290660'>that</span> <span m='3290850'>I'm</span>
  <span m='3290980'>going</span> <span m='3291060'>to</span> <span m='3291130'>bottom</span>
  <span m='3291610'>out</span> <span m='3292030'>the</span> <span m='3292120'>recursion</span>
  <span m='3292870'>early.</span> <span m='3293680'>Not</span> <span m='3294000'>when</span>
  <span m='3294170'>I</span> <span m='3294230'>get</span> <span m='3294450'>to</span>
  <span m='3294570'>n equals 1,</span> <span m='3295630'>but</span> <span m='3295800'>in</span>
  <span m='3295940'>fact</span> <span m='3296950'>when</span> <span m='3298170'>n
  squared</span> <span m='3299040'>is</span> <span m='3299260'>less</span> <span m='3299620'>than</span>
  <span m='3299780'>some</span> <span m='3300480'>constant</span> <span m='3301070'>times</span>
  <span m='3301400'>the</span> <span m='3301490'>cache</span> <span m='3301800'>size.</span>
  <span m='3303960'>For</span> <span m='3304090'>some</span> <span m='3304310'>sufficiently</span>
  <span m='3304850'>small</span> <span m='3306510'>concept.</span> <span m='3307010'>And</span>
  <span m='3307140'>what</span> <span m='3307250'>I</span> <span m='3307320'>claim,</span>
  <span m='3307740'>at</span> <span m='3307840'>that</span> <span m='3308090'>point,</span>
  <span m='3308730'>is</span> <span m='3309010'>that</span> <span m='3309230'>the</span>
  <span m='3309870'>number</span> <span m='3310150'>of</span> <span m='3310200'>cache</span>
  <span m='3310570'>misses</span> <span m='3310950'>I'm</span> <span m='3311050'>going</span>
  <span m='3311130'>to</span> <span m='3311200'>take</span> <span m='3311510'>at</span>
  <span m='3311580'>that</span> <span m='3311810'>point,</span> <span m='3312040'>I</span>
  <span m='3312100'>can</span> <span m='3312340'>just,</span> <span m='3313540'>without</span>
  <span m='3313870'>doing</span> <span m='3314120'>any</span> <span m='3314350'>more</span>
  <span m='3315780'>recursive</span> <span m='3316850'>stuff,</span> <span m='3317115'>I
  can</span> <span m='3317380'>just</span> <span m='3317450'>say</span> <span m='3317710'>it's</span>
  <span m='3318000'>n squared over b.</span> </p><p><span m='3321140'>So</span> <span
  m='3321310'>where</span> <span m='3321510'>does</span> <span m='3321680'>that</span>
  <span m='3321850'>come</span> <span m='3322070'>from?</span> <span m='3323080'>So</span>
  <span m='3323230'>this</span> <span m='3323410'>basically</span> <span m='3323880'>comes</span>
  <span m='3324210'>from</span> <span m='3324350'>the</span> <span m='3324460'>tall-cache</span>
  <span m='3325150'>assumption.</span> <span m='3327450'>So</span> <span m='3327630'>the</span>
  <span m='3327760'>idea</span> <span m='3328190'>is</span> <span m='3328620'>that</span>
  <span m='3328900'>when</span> <span m='3329080'>n squared</span> <span m='3329780'>is</span>
  <span m='3329960'>less</span> <span m='3330270'>than</span> <span m='3330390'>a</span>
  <span m='3330460'>constant</span> <span m='3330940'>times</span> <span m='3331250'>the</span>
  <span m='3331330'>size</span> <span m='3331720'>of</span> <span m='3332240'>your</span>
  <span m='3333190'>cache,</span> <span m='3335040'>constant</span> <span m='3335390'>times</span>
  <span m='3335590'>the</span> <span m='3335660'>size</span> <span m='3336000'>of</span>
  <span m='3336100'>m,</span> <span m='3337040'>then</span> <span m='3337340'>that</span>
  <span m='3337560'>means</span> <span m='3337850'>that</span> <span m='3338060'>this</span>
  <span m='3338370'>fits</span> <span m='3338890'>into--</span> <span m='3339410'>the</span>
  <span m='3339590'>n by n</span> <span m='3340110'>matrices</span> <span m='3340820'>fit</span>
  <span m='3341120'>within</span> <span m='3341420'>m.</span> <span m='3342120'>I've</span>
  <span m='3342200'>got</span> <span m='3342430'>three</span> <span m='3342710'>of</span>
  <span m='3342780'>them.</span> <span m='3342960'>I've</span> <span m='3343060'>got</span>
  <span m='3343230'>C,</span> <span m='3343590'>A</span> <span m='3343700'>and</span>
  <span m='3343890'>B.</span> <span m='3344510'>So</span> <span m='3344660'>that's</span>
  <span m='3344870'>where</span> <span m='3345270'>I</span> <span m='3345520'>need</span>
  <span m='3345710'>a</span> <span m='3345750'>constant</span> <span m='3346260'>here.</span>
  <span m='3348660'>So</span> <span m='3348830'>they're</span> <span m='3349040'>all</span>
  <span m='3349320'>going</span> <span m='3349400'>to</span> <span m='3349750'>fit</span>
  <span m='3350300'>in</span> <span m='3350450'>memory.</span> </p><p><span m='3353220'>And</span>
  <span m='3353410'>so</span> <span m='3354000'>if</span> <span m='3354200'>I</span>
  <span m='3354320'>look</span> <span m='3354820'>at</span> <span m='3355170'>it,</span>
  <span m='3355400'>all I</span> <span m='3355480'>have</span> <span m='3355690'>to</span>
  <span m='3355790'>do</span> <span m='3356000'>is</span> <span m='3356150'>count</span>
  <span m='3356420'>up</span> <span m='3356550'>the</span> <span m='3356640'>cold</span>
  <span m='3357120'>misses</span> <span m='3359070'>for</span> <span m='3359290'>bringing</span>
  <span m='3359830'>in</span> <span m='3360270'>those</span> <span m='3361780'>submatrices</span>
  <span m='3365050'>at</span> <span m='3365240'>the</span> <span m='3365340'>time</span>
  <span m='3365840'>that</span> <span m='3366060'>n</span> <span m='3366380'>hits</span>
  <span m='3366860'>this</span> <span m='3367090'>threshold</span> <span m='3367600'>here</span>
  <span m='3368200'>of</span> <span m='3368370'>some</span> <span m='3368650'>constant</span>
  <span m='3369100'>times</span> <span m='3369430'>m.</span> <span m='3370970'>And</span>
  <span m='3371150'>to</span> <span m='3371230'>bring</span> <span m='3371470'>in</span>
  <span m='3371560'>those</span> <span m='3371780'>matrices</span> <span m='3372460'>is</span>
  <span m='3372590'>only</span> <span m='3372780'>going</span> <span m='3372880'>to</span>
  <span m='3372940'>cost</span> <span m='3373280'>me</span> <span m='3373580'>n squared
  over b</span> <span m='3375050'>cache</span> <span m='3375400'>misses.</span> </p><p><span
  m='3376580'>And</span> <span m='3376660'>once</span> <span m='3376950'>I've</span>
  <span m='3377160'>done</span> <span m='3377410'>that,</span> <span m='3377860'>all</span>
  <span m='3378180'>of</span> <span m='3378280'>the</span> <span m='3378370'>rest</span>
  <span m='3378680'>of</span> <span m='3378740'>the</span> <span m='3378830'>recursion</span>
  <span m='3379430'>that's</span> <span m='3379650'>going</span> <span m='3379930'>on</span>
  <span m='3380900'>down</span> <span m='3381290'>below</span> <span m='3382070'>is</span>
  <span m='3382240'>all</span> <span m='3382580'>operating</span> <span m='3383180'>out</span>
  <span m='3383320'>of</span> <span m='3383400'>cache.</span> <span m='3384350'>It's</span>
  <span m='3384520'>not</span> <span m='3384760'>taking</span> <span m='3385120'>any</span>
  <span m='3385280'>misses</span> <span m='3387130'>if</span> <span m='3387300'>I</span>
  <span m='3387440'>have</span> <span m='3388000'>an</span> <span m='3389510'>optimal</span>
  <span m='3389960'>replacement</span> <span m='3390225'>algorithm.</span> <span m='3392450'>it's</span>
  <span m='3392620'>not</span> <span m='3392890'>taking</span> <span m='3393210'>any</span>
  <span m='3393380'>more</span> <span m='3393520'>misses</span> <span m='3393940'>as</span>
  <span m='3394090'>I</span> <span m='3394160'>get</span> <span m='3394410'>further</span>
  <span m='3394720'>down.</span> <span m='3396540'>Questions</span> <span m='3398310'>about</span>
  <span m='3401370'>this</span> <span m='3403590'>part</span> <span m='3403780'>of</span>
  <span m='3403960'>the</span> <span m='3404690'>recurrence</span> <span m='3405150'>here?</span>
  <span m='3411510'>So</span> <span m='3411680'>people</span> <span m='3411980'>with</span>
  <span m='3412160'>me?</span> </p><p><span m='3415690'>So</span> <span m='3415850'>when</span>
  <span m='3415990'>I</span> <span m='3416070'>get</span> <span m='3416300'>down</span>
  <span m='3416570'>to</span> <span m='3416650'>something</span> <span m='3417040'>of</span>
  <span m='3417100'>size n squared,</span> <span m='3418550'>where</span> <span m='3418680'>the</span>
  <span m='3418790'>submatrix</span> <span m='3419420'>is</span> <span m='3419490'>size
  n squared,</span> <span m='3421080'>the</span> <span m='3421170'>point</span> <span
  m='3421440'>is</span> <span m='3421810'>that</span> <span m='3422990'>I'll</span>
  <span m='3423140'>bring</span> <span m='3423480'>in</span> <span m='3424010'>the</span>
  <span m='3424230'>entire</span> <span m='3424680'>submatrix.</span> <span m='3425300'>But</span>
  <span m='3425400'>all</span> <span m='3425730'>the</span> <span m='3426350'>stuff</span>
  <span m='3426720'>that</span> <span m='3426860'>I</span> <span m='3426920'>have</span>
  <span m='3427120'>to</span> <span m='3427230'>do</span> <span m='3427410'>in</span>
  <span m='3427580'>there</span> <span m='3428180'>is</span> <span m='3428330'>never</span>
  <span m='3428560'>going</span> <span m='3428640'>to</span> <span m='3428720'>get</span>
  <span m='3428910'>kicked</span> <span m='3429210'>out,</span> <span m='3429850'>because</span>
  <span m='3430110'>it's</span> <span m='3430250'>small</span> <span m='3430610'>enough</span>
  <span m='3430820'>that</span> <span m='3430930'>it</span> <span m='3431070'>all</span>
  <span m='3431250'>fits.</span> <span m='3432340'>And an</span> <span m='3432590'>optimal</span>
  <span m='3433050'>algorithm</span> <span m='3433900'>for</span> <span m='3434030'>replacement</span>
  <span m='3434540'>is</span> <span m='3434640'>going</span> <span m='3434740'>to</span>
  <span m='3434780'>make</span> <span m='3434960'>sure</span> <span m='3435140'>that</span>
  <span m='3435350'>stuff</span> <span m='3435580'>stays</span> <span m='3435950'>in</span>
  <span m='3436080'>there,</span> <span m='3436490'>because</span> <span m='3436670'>there's</span>
  <span m='3436840'>plenty</span> <span m='3437200'>of</span> <span m='3437330'>room</span>
  <span m='3437590'>in</span> <span m='3437710'>the</span> <span m='3437800'>cache</span>
  <span m='3438230'>at</span> <span m='3438340'>that</span> <span m='3438560'>point.</span>
  <span m='3439160'>There's</span> <span m='3439300'>room</span> <span m='3439560'>for</span>
  <span m='3439660'>three</span> <span m='3439950'>matrices</span> <span m='3440560'>in</span>
  <span m='3440640'>the</span> <span m='3440730'>cache</span> <span m='3441920'>and</span>
  <span m='3442140'>a</span> <span m='3442350'>couple</span> <span m='3442650'>of</span>
  <span m='3442760'>other</span> <span m='3443270'>variables</span> <span m='3443920'>that</span>
  <span m='3444040'>I</span> <span m='3444100'>might</span> <span m='3444360'>need</span>
  <span m='3444660'>and</span> <span m='3444760'>that's</span> <span m='3444970'>basically</span>
  <span m='3445460'>it.</span> <span m='3450400'>Any</span> <span m='3450570'>questions</span>
  <span m='3451070'>about</span> <span m='3451280'>that?</span> </p><p><span m='3453610'>So</span>
  <span m='3453780'>let's</span> <span m='3454030'>then</span> <span m='3454350'>solve</span>
  <span m='3454780'>this</span> <span m='3454930'>recurrence.</span> <span m='3457540'>So</span>
  <span m='3457640'>we're</span> <span m='3457710'>going</span> <span m='3457790'>to</span>
  <span m='3457830'>go</span> <span m='3458000'>about</span> <span m='3458310'>it</span>
  <span m='3458420'>very</span> <span m='3458630'>much</span> <span m='3458830'>the</span>
  <span m='3458920'>same</span> <span m='3459210'>way.</span> <span m='3459480'>We</span>
  <span m='3459580'>make</span> <span m='3459880'>draw</span> <span m='3460050'>a</span>
  <span m='3460100'>recursion</span> <span m='3460640'>tree.</span> <span m='3461230'>So</span>
  <span m='3461750'>those</span> <span m='3462000'>of</span> <span m='3462080'>you</span>
  <span m='3462240'>are</span> <span m='3462350'>rusty</span> <span m='3462750'>in
  drawing</span> <span m='3463160'>recursion</span> <span m='3463580'>trees,</span>
  <span m='3464130'>I</span> <span m='3464290'>can</span> <span m='3464470'>promise</span>
  <span m='3464860'>you</span> <span m='3464980'>there will</span> <span m='3465190'>be
  a</span> <span m='3465330'>recursion</span> <span m='3465860'>tree</span> <span
  m='3466510'>on</span> <span m='3466810'>the</span> <span m='3467050'>quiz</span>
  <span m='3467430'>next</span> <span m='3467750'>Thursday.</span> </p><p><span m='3469350'>I</span>
  <span m='3469450'>think</span> <span m='3469690'>I</span> <span m='3469730'>can</span>
  <span m='3469890'>promise</span> <span m='3470230'>that.</span> <span m='3470570'>Can
  I promise</span> <span m='3470860'>that?</span> <span m='3471250'>Yeah, OK</span>
  <span m='3471520'>I can</span> <span m='3471750'>promise</span> <span m='3472130'>that.</span>
  </p><p><span m='3475970'>The</span> <span m='3476080'>way</span> <span m='3476280'>I</span>
  <span m='3476370'>like</span> <span m='3476620'>to</span> <span m='3476710'>do</span>
  <span m='3476880'>it,</span> <span m='3476980'>by</span> <span m='3477110'>the</span>
  <span m='3477210'>way,</span> <span m='3477350'>is</span> <span m='3477510'>not</span>
  <span m='3477790'>to</span> <span m='3477880'>try</span> <span m='3478090'>to</span>
  <span m='3478200'>just</span> <span m='3478450'>brought</span> <span m='3478780'>out</span>
  <span m='3478980'>all</span> <span m='3479200'>at</span> <span m='3479280'>once.</span>
  <span m='3482020'>In</span> <span m='3482150'>my</span> <span m='3482300'>own</span>
  <span m='3482580'>notes</span> <span m='3482860'>when</span> <span m='3483010'>I</span>
  <span m='3483080'>do</span> <span m='3483290'>this</span> <span m='3483530'>I</span>
  <span m='3483680'>always</span> <span m='3484170'>draw it</span> <span m='3484480'>step</span>
  <span m='3484810'>by</span> <span m='3484950'>step.</span> <span m='3485500'>I</span>
  <span m='3485580'>copy</span> <span m='3486040'>over</span> <span m='3486320'>and</span>
  <span m='3486420'>just</span> <span m='3486600'>do</span> <span m='3486710'>a</span>
  <span m='3486770'>step</span> <span m='3487120'>by</span> <span m='3487250'>step.</span>
  </p><p><span m='3487980'>You</span> <span m='3488080'>might</span> <span m='3488310'>think</span>
  <span m='3488510'>that</span> <span m='3488640'>that's</span> <span m='3488880'>extensive.</span>
  <span m='3489290'>Gee,</span> <span m='3489500'>why</span> <span m='3489660'>do</span>
  <span m='3489750'>I</span> <span m='3489850'>have</span> <span m='3489940'>to</span>
  <span m='3490040'>draw</span> <span m='3490370'>every one</span> <span m='3490790'>along</span>
  <span m='3491140'>the</span> <span m='3491210'>way?</span> <span m='3492680'>Well</span>
  <span m='3492840'>the</span> <span m='3492950'>answer</span> <span m='3493320'>is,</span>
  <span m='3493700'>it's</span> <span m='3493880'>a</span> <span m='3493930'>geometric</span>
  <span m='3494460'>process.</span> <span m='3496060'>All</span> <span m='3496370'>the</span>
  <span m='3496440'>ones</span> <span m='3496760'>going</span> <span m='3497070'>up</span>
  <span m='3497550'>to</span> <span m='3497750'>the</span> <span m='3497860'>last</span>
  <span m='3498350'>one</span> <span m='3498990'>are</span> <span m='3499170'>a</span>
  <span m='3499250'>small</span> <span m='3499760'>amount</span> <span m='3500050'>of</span>
  <span m='3500130'>the</span> <span m='3500220'>work</span> <span m='3500600'>to</span>
  <span m='3500710'>draw</span> <span m='3501130'>out</span> <span m='3502360'>the</span>
  <span m='3502460'>last</span> <span m='3502860'>one.</span> <span m='3503710'>And</span>
  <span m='3503890'>they</span> <span m='3504010'>help</span> <span m='3504280'>you</span>
  <span m='3504420'>get</span> <span m='3504600'>it</span> <span m='3504750'>correct</span>
  <span m='3505390'>the</span> <span m='3505490'>first</span> <span m='3505900'>time.</span>
  <span m='3507520'>So</span> <span m='3507950'>let</span> <span m='3508130'>me</span>
  <span m='3508250'>encourage</span> <span m='3508690'>you</span> <span m='3508870'>to</span>
  <span m='3509500'>draw</span> <span m='3509810'>out</span> <span m='3510270'>the</span>
  <span m='3510810'>tree</span> <span m='3512550'>iteration</span> <span m='3513030'>by</span>
  <span m='3513190'>iteration.</span> <span m='3513620'>Here</span> <span m='3513820'>I'm</span>
  <span m='3513890'>going</span> <span m='3513970'>to</span> <span m='3514020'>just</span>
  <span m='3514230'>do</span> <span m='3514340'>replacement.</span> </p><p><span m='3516200'>So</span>
  <span m='3516400'>what</span> <span m='3516580'>we</span> <span m='3516710'>do</span>
  <span m='3516940'>is</span> <span m='3517060'>we</span> <span m='3517210'>replace</span>
  <span m='3517840'>with</span> <span m='3517970'>the</span> <span m='3518050'>right</span>
  <span m='3518260'>hand</span> <span m='3518510'>side</span> <span m='3519670'>to</span>
  <span m='3519790'>do</span> <span m='3519940'>the</span> <span m='3520150'>recursion.</span>
  <span m='3521890'>And</span> <span m='3522160'>replace</span> <span m='3522650'>that.</span>
  <span m='3522940'>And</span> <span m='3523050'>once</span> <span m='3523250'>again</span>
  <span m='3523480'>I</span> <span m='3523530'>made</span> <span m='3523780'>the</span>
  <span m='3523850'>bug,</span> <span m='3524120'>that</span> <span m='3524290'>should</span>
  <span m='3524410'>be</span> <span m='3524520'>in</span> <span m='3524680'>over</span>
  <span m='3524950'>8.</span> <span m='3526890'>Sorry,</span> <span m='3527140'>n
  over 4</span> <span m='3528030'>here.</span> <span m='3528600'>n over 4.</span>
  <span m='3530140'>And</span> <span m='3530330'>then</span> <span m='3530490'>we</span>
  <span m='3530600'>keep</span> <span m='3530810'>going</span> <span m='3531140'>down</span>
  <span m='3531530'>until</span> <span m='3531900'>I</span> <span m='3531980'>get</span>
  <span m='3532270'>to</span> <span m='3534190'>the</span> <span m='3534320'>base</span>
  <span m='3534660'>case,</span> <span m='3535570'>which</span> <span m='3535790'>is</span>
  <span m='3535910'>this</span> <span m='3536130'>case</span> <span m='3536400'>here.</span>
  </p><p><span m='3538780'>Now</span> <span m='3539160'>comes</span> <span m='3539500'>the</span>
  <span m='3539590'>first</span> <span m='3539980'>hard</span> <span m='3540320'>part.</span>
  <span m='3542120'>How</span> <span m='3542430'>tall</span> <span m='3543030'>is</span>
  <span m='3543260'>this</span> <span m='3543370'>tree?</span> <span m='3543800'>Yeah--</span>
  </p><p><span m='3544130'>AUDIENCE:</span> <span m='3544564'>[INAUDIBLE]</span> <span
  m='3546300'>square root of n over b.</span> <span m='3548038'>You</span> <span m='3548454'>want</span>
  <span m='3548870'>n squared</span> <span m='3549180'>to</span> <span m='3549671'>be</span>
  <span m='3550162'>cm,</span> <span m='3550653'>not</span> <span m='3551144'>[INAUDIBLE].</span>
  </p><p><span m='3551635'>PROFESSOR:</span> <span m='3552130'>So</span> <span m='3553000'>here's</span>
  <span m='3553360'>the thing,</span> <span m='3553870'>let's</span> <span m='3554140'>discuss,</span>
  <span m='3554540'>first</span> <span m='3554760'>of</span> <span m='3554830'>all,</span>
  <span m='3555000'>why</span> <span m='3555240'>this</span> <span m='3555470'>is</span>
  <span m='3555620'>what</span> <span m='3555790'>it</span> <span m='3555900'>is.</span>
  <span m='3557090'>So</span> <span m='3557400'>at</span> <span m='3557640'>the</span>
  <span m='3557720'>point</span> <span m='3558210'>where</span> <span m='3558400'>n
  squared</span> <span m='3559050'>is</span> <span m='3559220'>less</span> <span m='3559550'>than</span>
  <span m='3559700'>cm,</span> <span m='3562580'>that</span> <span m='3562850'>says</span>
  <span m='3563290'>that</span> <span m='3563930'>it's</span> <span m='3564130'>going</span>
  <span m='3564210'>to</span> <span m='3564290'>cost</span> <span m='3564760'>us</span>
  <span m='3566100'>n squared</span> <span m='3566870'>over</span> <span m='3567180'>b.</span>
  <span m='3568066'>But</span> <span m='3568510'>n squared</span> <span m='3568990'>is</span>
  <span m='3569200'>just</span> <span m='3569650'>less</span> <span m='3569970'>than</span>
  <span m='3570140'>cm,</span> <span m='3571800'>so</span> <span m='3572020'>therefore,</span>
  <span m='3573280'>this</span> <span m='3573590'>is</span> <span m='3573720'>effectively</span>
  <span m='3574400'>m over b.</span> </p><p><span m='3577420'>Good</span> <span m='3577590'>question.</span>
  <span m='3579230'>So</span> <span m='3579380'>everybody</span> <span m='3579750'>see</span>
  <span m='3579940'>that?</span> <span m='3580580'>So</span> <span m='3580700'>when
  I</span> <span m='3580780'>get</span> <span m='3580980'>down</span> <span m='3581190'>to</span>
  <span m='3581250'>the</span> <span m='3581330'>bottom,</span> <span m='3582070'>it's</span>
  <span m='3582260'>basically</span> <span m='3582690'>costing</span> <span m='3583020'>me</span>
  <span m='3583140'>something</span> <span m='3583580'>that's</span> <span m='3583740'>about</span>
  <span m='3584260'>the</span> <span m='3584340'>number</span> <span m='3584660'>of</span>
  <span m='3584750'>lines</span> <span m='3585150'>I</span> <span m='3585190'>have</span>
  <span m='3585420'>in</span> <span m='3585530'>my</span> <span m='3585630'>cache,</span>
  <span m='3587530'>number</span> <span m='3587850'>of</span> <span m='3587890'>misses</span>
  <span m='3589760'>to</span> <span m='3590120'>fill</span> <span m='3590310'>things</span>
  <span m='3590520'>up.</span> </p><p><span m='3591640'>The</span> <span m='3591750'>tricky</span>
  <span m='3592180'>thing</span> <span m='3592420'>is,</span> <span m='3592550'>what's</span>
  <span m='3592730'>the</span> <span m='3592910'>height?</span> <span m='3593820'>Because</span>
  <span m='3594040'>this</span> <span m='3594270'>is</span> <span m='3594370'>crucial</span>
  <span m='3595380'>to</span> <span m='3595510'>getting</span> <span m='3595850'>this</span>
  <span m='3596030'>kind</span> <span m='3596160'>of</span> <span m='3596280'>calculation</span>
  <span m='3597000'>right.</span> <span m='3598110'>So</span> <span m='3598290'>what</span>
  <span m='3598470'>is</span> <span m='3598590'>the</span> <span m='3598660'>height</span>
  <span m='3599090'>of</span> <span m='3599480'>this</span> <span m='3600290'>tree?</span>
  <span m='3604690'>So</span> <span m='3604850'>I'm</span> <span m='3604980'>having</span>
  <span m='3605490'>every</span> <span m='3605750'>time.</span> </p><p><span m='3607730'>So</span>
  <span m='3607890'>one</span> <span m='3608090'>way</span> <span m='3608210'>to</span>
  <span m='3608320'>think</span> <span m='3608630'>about</span> <span m='3608960'>it</span>
  <span m='3609090'>is,</span> <span m='3610720'>it's</span> <span m='3610900'>going</span>
  <span m='3610990'>to</span> <span m='3611070'>be</span> <span m='3611260'>log bas
  2 of n,</span> <span m='3612670'>just</span> <span m='3612940'>as</span> <span m='3613090'>before,</span>
  <span m='3614450'>minus</span> <span m='3615750'>the</span> <span m='3615830'>height</span>
  <span m='3616220'>of</span> <span m='3616350'>the</span> <span m='3616480'>tree</span>
  <span m='3616810'>that</span> <span m='3616930'>is</span> <span m='3617120'>hidden</span>
  <span m='3617470'>here</span> <span m='3617740'>that</span> <span m='3617880'>I</span>
  <span m='3617950'>didn't</span> <span m='3618190'>have</span> <span m='3618410'>to</span>
  <span m='3618500'>actually</span> <span m='3618780'>go</span> <span m='3619000'>into</span>
  <span m='3619310'>because</span> <span m='3619510'>there are</span> <span m='3619590'>no</span>
  <span m='3619750'>cache</span> <span m='3620090'>misses</span> <span m='3620470'>in
  it.</span> <span m='3623210'>So</span> <span m='3623970'>that's</span> <span m='3624300'>going</span>
  <span m='3624410'>to</span> <span m='3624510'>occur</span> <span m='3625580'>when</span>
  <span m='3625950'>n</span> <span m='3626300'>is</span> <span m='3627050'>approximately</span>
  <span m='3628550'>m,</span> <span m='3630390'>cm,</span> <span m='3631980'>sorry</span>
  <span m='3632870'>when</span> <span m='3633080'>n</span> <span m='3633300'>is</span>
  <span m='3633410'>approximately</span> <span m='3634050'>square</span> <span m='3634530'>root</span>
  <span m='3634820'>of</span> <span m='3634950'>cm.</span> </p><p><span m='3636560'>So</span>
  <span m='3636710'>I</span> <span m='3636820'>end</span> <span m='3637030'>up</span>
  <span m='3637260'>with</span> <span m='3638780'>log of n minus 1/2 log of cm.</span>
  <span m='3644600'>That's</span> <span m='3644870'>the</span> <span m='3644950'>height</span>
  <span m='3645180'>here.</span> <span m='3645340'>Because</span> <span m='3645650'>the</span>
  <span m='3645720'>height</span> <span m='3646190'>at</span> <span m='3646390'>this</span>
  <span m='3646630'>point</span> <span m='3647240'>of</span> <span m='3647350'>the</span>
  <span m='3647450'>tree</span> <span m='3647690'>that's</span> <span m='3647880'>missing</span>
  <span m='3648620'>because</span> <span m='3648890'>they're</span> <span m='3648990'>no</span>
  <span m='3649220'>cache,</span> <span m='3650190'>I</span> <span m='3650270'>don't</span>
  <span m='3650410'>have</span> <span m='3650540'>to</span> <span m='3650620'>account</span>
  <span m='3651000'>for</span> <span m='3651120'>any</span> <span m='3651260'>cache</span>
  <span m='3651580'>misses</span> <span m='3651960'>in</span> <span m='3652080'>there,</span>
  <span m='3653640'>is</span> <span m='3654560'>log</span> <span m='3655130'>of</span>
  <span m='3655350'>cm</span> <span m='3655770'>to</span> <span m='3655880'>the</span>
  <span m='3655960'>one</span> <span m='3656260'>half,</span> <span m='3656880'>based</span>
  <span m='3657180'>on</span> <span m='3657300'>this.</span> <span m='3661610'>Does</span>
  <span m='3661740'>that</span> <span m='3661800'>follow</span> <span m='3662570'>for</span>
  <span m='3662880'>everybody?</span> <span m='3663400'>People</span> <span m='3663680'>comfortable?</span>
  <span m='3667080'>Yeah?</span> <span m='3668060'>OK,</span> <span m='3668360'>good.</span>
  </p><p><span m='3670090'>So</span> <span m='3670280'>now</span> <span m='3671120'>what</span>
  <span m='3671260'>do</span> <span m='3671320'>we</span> <span m='3671450'>do?</span>
  <span m='3671950'>We</span> <span m='3672100'>count</span> <span m='3672390'>up</span>
  <span m='3672510'>how</span> <span m='3672690'>many</span> <span m='3672870'>leaves</span>
  <span m='3673210'>there</span> <span m='3673460'>are.</span> <span m='3675430'>So</span>
  <span m='3675590'>the number</span> <span m='3675880'>of</span> <span m='3675940'>leaves</span>
  <span m='3676330'>is</span> <span m='3676580'>8,</span> <span m='3677060'>because</span>
  <span m='3677270'>I</span> <span m='3677360'>have</span> <span m='3677450'>a</span>
  <span m='3677500'>branching</span> <span m='3677930'>factor</span> <span m='3678310'>of</span>
  <span m='3678380'>8,</span> <span m='3679240'>2</span> <span m='3679540'>whatever</span>
  <span m='3679940'>the</span> <span m='3680060'>height</span> <span m='3680350'>is.</span>
  <span m='3681150'>Log n minus 1/2 log of cm.</span> </p><p><span m='3684760'>And</span>
  <span m='3684920'>then</span> <span m='3685040'>if</span> <span m='3685170'>I</span>
  <span m='3685260'>do</span> <span m='3685470'>my</span> <span m='3685670'>matrix</span>
  <span m='3686100'>magic,</span> <span m='3686380'>well</span> <span m='3686660'>that</span>
  <span m='3686930'>part</span> <span m='3687270'>is</span> <span m='3687550'>n cubed,</span>
  <span m='3687970'>the</span> <span m='3688070'>minus</span> <span m='3688440'>becomes</span>
  <span m='3688770'>a</span> <span m='3688820'>divide,</span> <span m='3689760'>and</span>
  <span m='3690020'>now</span> <span m='3690950'>8 to the 1/2 log of cm</span> <span
  m='3695660'>is</span> <span m='3698530'>the</span> <span m='3698620'>square</span>
  <span m='3699010'>root</span> <span m='3699290'>of</span> <span m='3699390'>n cubed,</span>
  <span m='3700180'>which</span> <span m='3700460'>is</span> <span m='3700560'>m to
  the 3/2.</span> <span m='3706561'>Is</span> <span m='3707040'>that</span> <span
  m='3707200'>good?</span> </p><p><span m='3709090'>The</span> <span m='3709180'>rest</span>
  <span m='3709510'>of</span> <span m='3709590'>it</span> <span m='3709680'>is</span>
  <span m='3710080'>very</span> <span m='3710350'>similar</span> <span m='3710710'>to</span>
  <span m='3710780'>what</span> <span m='3710910'>we</span> <span m='3711000'>did</span>
  <span m='3711170'>before.</span> <span m='3712050'>At</span> <span m='3712210'>every</span>
  <span m='3712470'>level</span> <span m='3713390'>I</span> <span m='3713530'>have</span>
  <span m='3715240'>a</span> <span m='3715350'>certain</span> <span m='3715680'>number</span>
  <span m='3716040'>of</span> <span m='3716190'>things</span> <span m='3717350'>that</span>
  <span m='3717570'>I'm</span> <span m='3717900'>adding</span> <span m='3718280'>up.</span>
  <span m='3718710'>And</span> <span m='3719120'>on</span> <span m='3719240'>the</span>
  <span m='3719310'>bottom</span> <span m='3719730'>level,</span> <span m='3720050'>I</span>
  <span m='3720250'>take</span> <span m='3720640'>the</span> <span m='3720750'>cost</span>
  <span m='3721260'>here,</span> <span m='3721630'>m over b,</span> <span m='3722850'>and</span>
  <span m='3723030'>I</span> <span m='3723070'>multiply</span> <span m='3723760'>it</span>
  <span m='3723960'>by</span> <span m='3724500'>a</span> <span m='3724520'>number</span>
  <span m='3724820'>of</span> <span m='3724900'>leaves.</span> <span m='3726620'>When</span>
  <span m='3726850'>I</span> <span m='3726920'>do</span> <span m='3727160'>that</span>
  <span m='3728320'>I</span> <span m='3728450'>get,</span> <span m='3728800'>what?</span>
  </p><p><span m='3729440'>I</span> <span m='3729540'>get</span> <span m='3730470'>n
  cubed over b</span> <span m='3732810'>times</span> <span m='3733260'>m to the 1/2.</span>
  <span m='3736660'>This</span> <span m='3736840'>is</span> <span m='3737000'>geometric.</span>
  <span m='3738200'>So</span> <span m='3738420'>the</span> <span m='3738600'>answer</span>
  <span m='3738980'>is</span> <span m='3739120'>going,</span> <span m='3739270'>in</span>
  <span m='3739410'>this</span> <span m='3739570'>case,</span> <span m='3739850'>just</span>
  <span m='3740110'>going to be</span> <span m='3740300'>the</span> <span m='3740400'>sum</span>
  <span m='3740800'>of</span> <span m='3745240'>a</span> <span m='3745310'>constant</span>
  <span m='3745700'>factor</span> <span m='3746030'>times</span> <span m='3746430'>the</span>
  <span m='3747130'>large</span> <span m='3747340'>thing.</span> </p><p><span m='3747860'>And</span>
  <span m='3748010'>why</span> <span m='3748270'>does</span> <span m='3748410'>this</span>
  <span m='3748610'>look</span> <span m='3748790'>familiar?</span> <span m='3751630'>That</span>
  <span m='3751790'>was</span> <span m='3751920'>the</span> <span m='3752070'>optimal</span>
  <span m='3752570'>result</span> <span m='3753060'>we</span> <span m='3753230'>got</span>
  <span m='3753490'>from</span> <span m='3753630'>tiling.</span> <span m='3756180'>But</span>
  <span m='3756360'>where's</span> <span m='3756730'>the</span> <span m='3756830'>tuning</span>
  <span m='3757200'>parameters?</span> <span m='3760670'>No</span> <span m='3761110'>tuning</span>
  <span m='3761530'>parameters.</span> <span m='3764380'>No</span> <span m='3764690'>tuning</span>
  <span m='3765060'>parameters.</span> </p><p><span m='3766440'>So</span> <span m='3766610'>that</span>
  <span m='3766870'>means</span> <span m='3767130'>that</span> <span m='3767270'>this</span>
  <span m='3767440'>analysis</span> <span m='3768170'>that</span> <span m='3768280'>I</span>
  <span m='3768350'>did</span> <span m='3768570'>for</span> <span m='3768720'>one</span>
  <span m='3768970'>level</span> <span m='3769300'>of</span> <span m='3769380'>caching,</span>
  <span m='3771360'>it</span> <span m='3771500'>applies</span> <span m='3772000'>even</span>
  <span m='3772220'>if</span> <span m='3772320'>you</span> <span m='3772440'>have</span>
  <span m='3773950'>three</span> <span m='3774200'>levels</span> <span m='3774550'>of</span>
  <span m='3774630'>caching.</span> <span m='3775950'>At</span> <span m='3776180'>every</span>
  <span m='3776560'>level</span> <span m='3777470'>you're</span> <span m='3777610'>getting</span>
  <span m='3777920'>near</span> <span m='3778170'>optimal</span> <span m='3781360'>cache</span>
  <span m='3781710'>behavior.</span> <span m='3783885'>So</span> <span m='3784160'>it's</span>
  <span m='3784360'>got</span> <span m='3784500'>the</span> <span m='3784560'>same</span>
  <span m='3784830'>cache</span> <span m='3785140'>misses</span> <span m='3785500'>as</span>
  <span m='3785640'>with</span> <span m='3785790'>tiling.</span> </p><p><span m='3796450'>These</span>
  <span m='3796880'>are</span> <span m='3796990'>called</span> <span m='3797390'>cache-oblivious</span>
  <span m='3798430'>algorithms.</span> <span m='3799510'>Because</span> <span m='3799750'>the</span>
  <span m='3799880'>algorithm</span> <span m='3800380'>itself</span> <span m='3801320'>has</span>
  <span m='3801560'>no</span> <span m='3801780'>tuning</span> <span m='3802170'>parameters</span>
  <span m='3802680'>related</span> <span m='3802940'>to</span> <span m='3803200'>cache.</span>
  <span m='3803700'>Unlike</span> <span m='3805470'>the</span> <span m='3805580'>tiling</span>
  <span m='3806060'>algorithm.</span> <span m='3806670'>That's</span> <span m='3806930'>a</span>
  <span m='3806980'>cache-aware</span> <span m='3807870'>algorithm.</span> </p><p><span
  m='3808895'>The</span> <span m='3809380'>cache-oblivious</span> <span m='3809680'>algorithm</span>
  <span m='3810630'>has</span> <span m='3810910'>no</span> <span m='3811480'>tuning</span>
  <span m='3811830'>parameters.</span> <span m='3813830'>And</span> <span m='3813960'>if</span>
  <span m='3814070'>it's</span> <span m='3814220'>an</span> <span m='3814290'>efficient</span>
  <span m='3814810'>one.</span> <span m='3816950'>So,</span> <span m='3817120'>by</span>
  <span m='3817290'>the</span> <span m='3817380'>way,</span> <span m='3817630'>our</span>
  <span m='3817810'>first</span> <span m='3818180'>algorithm</span> <span m='3818590'>was</span>
  <span m='3818740'>cache-oblivious</span> <span m='3819520'>as</span> <span m='3819640'>well.</span>
  <span m='3820550'>The</span> <span m='3820730'>naive</span> <span m='3821030'>one.</span>
  <span m='3821260'>It's</span> <span m='3821530'>just</span> <span m='3821750'>not</span>
  <span m='3821920'>efficient.</span> </p><p><span m='3825260'>So</span> <span m='3826010'>in</span>
  <span m='3826140'>this</span> <span m='3826330'>case</span> <span m='3826530'>we</span>
  <span m='3826630'>have</span> <span m='3826720'>an</span> <span m='3826790'>efficient</span>
  <span m='3827300'>one.</span> <span m='3828132'>It's</span> <span m='3828514'>got</span>
  <span m='3828896'>no</span> <span m='3829280'>voodoo</span> <span m='3829570'>turning</span>
  <span m='3829910'>of</span> <span m='3829980'>parameters,</span> <span m='3831080'>no</span>
  <span m='3831360'>explicit</span> <span m='3831970'>knowledge</span> <span m='3832360'>of</span>
  <span m='3832850'>caches,</span> <span m='3833880'>and</span> <span m='3834010'>it</span>
  <span m='3834140'>passively</span> <span m='3834910'>autotunes</span> <span m='3835730'>itself.</span>
  <span m='3837980'>As</span> <span m='3838190'>it</span> <span m='3838290'>goes</span>
  <span m='3838600'>down</span> <span m='3839290'>when</span> <span m='3839490'>it</span>
  <span m='3839620'>fits</span> <span m='3839880'>things</span> <span m='3840140'>into</span>
  <span m='3840310'>cache</span> <span m='3840690'>it</span> <span m='3840810'>fits</span>
  <span m='3841070'>them</span> <span m='3841180'>and</span> <span m='3841590'>uses</span>
  <span m='3841740'>things</span> <span m='3842000'>locally.</span> <span m='3842890'>And</span>
  <span m='3843010'>then</span> <span m='3843140'>it</span> <span m='3843240'>goes</span>
  <span m='3843480'>down</span> <span m='3843710'>and</span> <span m='3843800'>it</span>
  <span m='3843910'>fits</span> <span m='3844090'>into</span> <span m='3844220'>the</span>
  <span m='3844330'>next</span> <span m='3844630'>level</span> <span m='3844890'>of</span>
  <span m='3844990'>cache</span> <span m='3845610'>and</span> <span m='3845740'>uses</span>
  <span m='3846050'>things</span> <span m='3846300'>locally</span> <span m='3846730'>and</span>
  <span m='3846880'>so</span> <span m='3847020'>forth.</span> </p><p><span m='3849080'>It</span>
  <span m='3849220'>handles</span> <span m='3849660'>multi-level</span> <span m='3850390'>caches</span>
  <span m='3850950'>automatically.</span> <span m='3853260'>And</span> <span m='3853560'>it's</span>
  <span m='3853820'>good</span> <span m='3854940'>in</span> <span m='3855330'>multi-programmed</span>
  <span m='3856070'>environments.</span> <span m='3856660'>Because</span> <span m='3856920'>if
  you</span> <span m='3857160'>end</span> <span m='3857310'>up</span> <span m='3857450'>taking</span>
  <span m='3857810'>away</span> <span m='3858340'>some</span> <span m='3858640'>of</span>
  <span m='3858700'>the</span> <span m='3858790'>cache</span> <span m='3860250'>it</span>
  <span m='3860410'>doesn't</span> <span m='3860740'>matter.</span> <span m='3862650'>It</span>
  <span m='3863050'>still</span> <span m='3863620'>will</span> <span m='3864090'>end</span>
  <span m='3864320'>up</span> <span m='3864470'>using</span> <span m='3864960'>whatever</span>
  <span m='3865430'>cache</span> <span m='3865800'>is</span> <span m='3865930'>available</span>
  <span m='3866510'>nearly</span> <span m='3866840'>as</span> <span m='3866980'>well</span>
  <span m='3867380'>as</span> <span m='3868570'>any</span> <span m='3868930'>other</span>
  <span m='3872120'>program</span> <span m='3874370'>could</span> <span m='3874520'>use</span>
  <span m='3874720'>that</span> <span m='3874900'>cache.</span> <span m='3876160'>So</span>
  <span m='3876720'>these</span> <span m='3876940'>are</span> <span m='3876990'>very</span>
  <span m='3877300'>good</span> <span m='3877520'>in</span> <span m='3877630'>multi-programmed</span>
  <span m='3878280'>environments.</span> </p><p><span m='3883930'>The</span> <span
  m='3884030'>best</span> <span m='3884360'>cache-oblivious</span> <span m='3885170'>matrix</span>
  <span m='3885460'>multiplication,</span> <span m='3885850'>in</span> <span m='3886240'>fact</span>
  <span m='3886600'>doesn't</span> <span m='3886990'>do</span> <span m='3887160'>an</span>
  <span m='3887280'>eight</span> <span m='3887550'>way</span> <span m='3887720'>split</span>
  <span m='3888180'>as</span> <span m='3888350'>I</span> <span m='3888500'>described</span>
  <span m='3889070'>here.</span> <span m='3890430'>That</span> <span m='3890950'>was</span>
  <span m='3891220'>easier</span> <span m='3891580'>to</span> <span m='3891680'>analyze</span>
  <span m='3892670'>and</span> <span m='3892820'>so</span> <span m='3893020'>forth.</span>
  <span m='3894060'>The</span> <span m='3894150'>best</span> <span m='3894460'>one</span>
  <span m='3894620'>that</span> <span m='3894780'>I</span> <span m='3894880'>know</span>
  <span m='3895540'>work</span> <span m='3895930'>on</span> <span m='3896030'>arbitrary</span>
  <span m='3896530'>rectangular</span> <span m='3897080'>matrix.</span> <span m='3897610'>And</span>
  <span m='3897700'>what</span> <span m='3897870'>they</span> <span m='3898000'>do,</span>
  <span m='3898220'>is</span> <span m='3898360'>they</span> <span m='3898480'>do</span>
  <span m='3898620'>binary</span> <span m='3899140'>splitting.</span> </p><p><span
  m='3900500'>So</span> <span m='3900670'>you</span> <span m='3900820'>would take</span>
  <span m='3901150'>your</span> <span m='3901270'>matrix,</span> <span m='3901880'>i
  times j,</span> <span m='3907501'>So if</span> <span m='3908000'>you</span> <span
  m='3908120'>take</span> <span m='3908380'>a</span> <span m='3908440'>matrix,</span>
  <span m='3908880'>let's</span> <span m='3909080'>say</span> <span m='3909220'>it's</span>
  <span m='3910650'>something</span> <span m='3910940'>like</span> <span m='3911180'>this.</span>
  <span m='3914640'>So</span> <span m='3914840'>here</span> <span m='3915020'>we</span>
  <span m='3915130'>have</span> <span m='3915990'>i,</span> <span m='3916450'>k,</span>
  <span m='3918355'>k,</span> <span m='3919840'>j.</span> <span m='3922590'>And</span>
  <span m='3922830'>you're</span> <span m='3922970'>going</span> <span m='3923040'>to</span>
  <span m='3923110'>get</span> <span m='3923310'>something</span> <span m='3923780'>of</span>
  <span m='3923850'>shape.</span> <span m='3929160'>i</span> <span m='3930690'>times</span>
  <span m='3931300'>j,</span> <span m='3932820'>right?</span> </p><p><span m='3936250'>What</span>
  <span m='3936570'>it</span> <span m='3936670'>does,</span> <span m='3937010'>is</span>
  <span m='3937130'>it</span> <span m='3937260'>takes</span> <span m='3937560'>whatever</span>
  <span m='3937940'>is</span> <span m='3938050'>the</span> <span m='3938130'>largest</span>
  <span m='3938650'>dimension.</span> <span m='3939750'>In</span> <span m='3939790'>this</span>
  <span m='3939940'>case</span> <span m='3940230'>k</span> <span m='3940480'>is</span>
  <span m='3940640'>the</span> <span m='3940720'>largest</span> <span m='3941130'>dimension.</span>
  <span m='3942560'>And</span> <span m='3942750'>it</span> <span m='3942890'>partitions</span>
  <span m='3944930'>either</span> <span m='3945150'>one</span> <span m='3945400'>or</span>
  <span m='3945470'>both</span> <span m='3945740'>of</span> <span m='3945810'>the</span>
  <span m='3945890'>matrices</span> <span m='3946920'>along</span> <span m='3948090'>k.</span>
  <span m='3948560'>In this</span> <span m='3948890'>case,</span> <span m='3949160'>it</span>
  <span m='3949250'>doesn't</span> <span m='3949550'>do</span> <span m='3949670'>that.</span>
  <span m='3950280'>And</span> <span m='3950480'>then it</span> <span m='3950720'>recursively</span>
  <span m='3951400'>solves</span> <span m='3952410'>the</span> <span m='3952520'>two</span>
  <span m='3953020'>sub-rectangular</span> <span m='3953890'>problems.</span> <span
  m='3955210'>And</span> <span m='3955470'>that</span> <span m='3955650'>ends</span>
  <span m='3955860'>up</span> <span m='3955950'>being</span> <span m='3956160'>a</span>
  <span m='3956220'>very,</span> <span m='3956650'>very</span> <span m='3956950'>efficient</span>
  <span m='3957430'>fast</span> <span m='3957770'>code</span> <span m='3958060'>if</span>
  <span m='3958150'>you</span> <span m='3958260'>code</span> <span m='3958490'>that</span>
  <span m='3958640'>up</span> <span m='3958770'>tightly.</span> </p><p><span m='3960650'>So
  it</span> <span m='3960800'>does</span> <span m='3961040'>binary</span> <span m='3961500'>splitting</span>
  <span m='3961980'>rather</span> <span m='3962310'>than--</span> <span m='3962590'>and</span>
  <span m='3962710'>it's</span> <span m='3962920'>general.</span> <span m='3963660'>And</span>
  <span m='3963830'>if</span> <span m='3963940'>you</span> <span m='3964330'>analyze</span>
  <span m='3964880'>this,</span> <span m='3965060'>it's</span> <span m='3965210'>got</span>
  <span m='3965390'>the</span> <span m='3965460'>same</span> <span m='3965860'>behavior</span>
  <span m='3967910'>as</span> <span m='3968140'>the</span> <span m='3968290'>eight</span>
  <span m='3968500'>way</span> <span m='3968680'>division.</span> <span m='3969130'>It's</span>
  <span m='3969270'>just</span> <span m='3969540'>more</span> <span m='3971250'>efficient.</span>
  </p><p><span m='3976060'>So</span> <span m='3976410'>questions?</span> <span m='3976790'>We</span>
  <span m='3976880'>had</span> <span m='3976970'>a</span> <span m='3977030'>question</span>
  <span m='3977440'>about</span> <span m='3977760'>now</span> <span m='3977990'>comparing</span>
  <span m='3980590'>with</span> <span m='3981100'>the</span> <span m='3981710'>tiled</span>
  <span m='3982090'>algorithm.</span> <span m='3983750'>Do</span> <span m='3984190'>you</span>
  <span m='3984290'>want to</span> <span m='3984390'>reprise</span> <span m='3984720'>your</span>
  <span m='3984840'>question?</span> </p><p><span m='3985145'>AUDIENCE:</span> <span
  m='3985450'>What I</span> <span m='3985925'>was</span> <span m='3986400'>saying</span>
  <span m='3986875'>was,</span> <span m='3987825'>I</span> <span m='3988300'>guess
  this answers</span> <span m='3988775'>my question.</span> <span m='3989725'>If</span>
  <span m='3990200'>you were</span> <span m='3990675'>to tune</span> <span m='3991850'>the</span>
  <span m='3992332'>previous</span> <span m='3992814'>algorithm</span> <span m='3993296'>properly,</span>
  <span m='3994742'>and</span> <span m='3995224'>you're</span> <span m='3995706'>assuming</span>
  <span m='3996188'>it's not</span> <span m='3996670'>in a</span> <span m='3997152'>multi-program</span>
  <span m='3997634'>environment,</span> <span m='3998116'>the</span> <span m='3998598'>recursive</span>
  <span m='3999080'>one,</span> <span m='4000044'>it will</span> <span m='4000526'>never</span>
  <span m='4001008'>be</span> <span m='4001500'>the</span> <span m='4001680'>one that</span>
  <span m='4002120'>is</span> <span m='4002560'>locked.</span> <span m='4003550'>[INAUDIBLE]</span>
  </p><p><span m='4004050'>PROFESSOR:</span> <span m='4004550'>So</span> <span m='4008230'>at</span>
  <span m='4008440'>some</span> <span m='4008650'>level</span> <span m='4008920'>that's</span>
  <span m='4009150'>true,</span> <span m='4009430'>and at</span> <span m='4009560'>some</span>
  <span m='4009740'>level</span> <span m='4010010'>it's</span> <span m='4010140'>not</span>
  <span m='4010320'>true.</span> <span m='4014400'>So</span> <span m='4014690'>it</span>
  <span m='4014790'>is</span> <span m='4014960'>true</span> <span m='4015400'>in</span>
  <span m='4015610'>that</span> <span m='4015960'>if</span> <span m='4016130'>it's</span>
  <span m='4016370'>cache-oblivious</span> <span m='4021920'>you</span> <span m='4022080'>can't</span>
  <span m='4022370'>take</span> <span m='4022590'>advantage</span> <span m='4022940'>of
  all</span> <span m='4023350'>the</span> <span m='4023450'>corner</span> <span m='4023790'>cases</span>
  <span m='4024370'>that</span> <span m='4024550'>you</span> <span m='4024730'>would</span>
  <span m='4025110'>might</span> <span m='4025400'>be</span> <span m='4025550'>able</span>
  <span m='4025670'>to</span> <span m='4025730'>take</span> <span m='4026000'>advantage</span>
  <span m='4026410'>of</span> <span m='4026540'>in a</span> <span m='4026730'>tiling</span>
  <span m='4027170'>algorithm.</span> <span m='4028140'>So</span> <span m='4028320'>from</span>
  <span m='4028490'>that</span> <span m='4028740'>point</span> <span m='4028950'>of</span>
  <span m='4029010'>view,</span> <span m='4029290'>that's</span> <span m='4029610'>true.</span>
  </p><p><span m='4029900'>On</span> <span m='4030030'>the</span> <span m='4030190'>other</span>
  <span m='4030350'>hand,</span> <span m='4031260'>these</span> <span m='4031480'>algorithms</span>
  <span m='4031940'>work</span> <span m='4032230'>even</span> <span m='4032630'>as</span>
  <span m='4032850'>you</span> <span m='4033800'>go</span> <span m='4034050'>into</span>
  <span m='4034410'>paging</span> <span m='4034930'>and</span> <span m='4035080'>disks</span>
  <span m='4035580'>and</span> <span m='4035740'>so</span> <span m='4035940'>forth.</span>
  <span m='4036705'>And</span> <span m='4037050'>the</span> <span m='4037150'>interesting</span>
  <span m='4037580'>thing</span> <span m='4037780'>about</span> <span m='4038060'>a</span>
  <span m='4038110'>disk,</span> <span m='4038560'>if</span> <span m='4038640'>you</span>
  <span m='4038730'>start</span> <span m='4039090'>having</span> <span m='4039410'>a</span>
  <span m='4039700'>big</span> <span m='4040170'>problem</span> <span m='4040990'>that</span>
  <span m='4041100'>doesn't</span> <span m='4041410'>fit</span> <span m='4041550'>in</span>
  <span m='4041670'>memory</span> <span m='4042080'>and,</span> <span m='4042180'>in</span>
  <span m='4042290'>fact,</span> <span m='4042660'>is</span> <span m='4043380'>out</span>
  <span m='4043570'>of</span> <span m='4043680'>core</span> <span m='4044190'>as</span>
  <span m='4044360'>they</span> <span m='4044470'>call</span> <span m='4044770'>it,</span>
  <span m='4045180'>and</span> <span m='4045440'>is</span> <span m='4045570'>paging</span>
  <span m='4045960'>to</span> <span m='4046060'>disk,</span> <span m='4047180'>is</span>
  <span m='4047480'>that</span> <span m='4047980'>the</span> <span m='4048620'>disk</span>
  <span m='4049750'>sizes</span> <span m='4051430'>of</span> <span m='4052470'>sectors</span>
  <span m='4053040'>that</span> <span m='4053120'>can</span> <span m='4053250'>be</span>
  <span m='4053360'>brought</span> <span m='4053680'>efficiently</span> <span m='4054220'>off</span>
  <span m='4054430'>of</span> <span m='4054550'>a</span> <span m='4054590'>disk,</span>
  <span m='4055550'>vary.</span> </p><p><span m='4060430'>And</span> <span m='4060570'>the</span>
  <span m='4060640'>reason</span> <span m='4060940'>is</span> <span m='4061110'>because</span>
  <span m='4061470'>in</span> <span m='4061560'>a</span> <span m='4061630'>disk,</span>
  <span m='4066700'>if</span> <span m='4066860'>you</span> <span m='4067010'>read</span>
  <span m='4067190'>a</span> <span m='4067280'>track</span> <span m='4067770'>around</span>
  <span m='4068050'>the</span> <span m='4068170'>outside</span> <span m='4069920'>you</span>
  <span m='4070100'>can</span> <span m='4070280'>get</span> <span m='4070820'>two</span>
  <span m='4070990'>or</span> <span m='4071090'>three</span> <span m='4071340'>times</span>
  <span m='4071770'>as</span> <span m='4071900'>much</span> <span m='4072300'>data</span>
  <span m='4072640'>off</span> <span m='4074420'>the</span> <span m='4074570'>disk</span>
  <span m='4075040'>as</span> <span m='4075280'>a</span> <span m='4075560'>track that</span>
  <span m='4075840'>you</span> <span m='4075940'>read</span> <span m='4076180'>near</span>
  <span m='4076350'>the</span> <span m='4076520'>inside.</span> <span m='4077510'>So</span>
  <span m='4077680'>the</span> <span m='4077870'>head</span> <span m='4078060'>moves</span>
  <span m='4078540'>in</span> <span m='4078700'>and</span> <span m='4078830'>out</span>
  <span m='4079050'>of</span> <span m='4079452'>the</span> <span m='4082290'>disk</span>
  <span m='4082600'>like</span> <span m='4082790'>this.</span> <span m='4082960'>It's</span>
  <span m='4083080'>typically</span> <span m='4083470'>on</span> <span m='4083560'>a</span>
  <span m='4083640'>pivot</span> <span m='4084500'>and</span> <span m='4084780'>pivots</span>
  <span m='4084970'>in and</span> <span m='4085240'>out.</span> </p><p><span m='4085920'>If
  it's</span> <span m='4086170'>reading</span> <span m='4086510'>towards</span> <span
  m='4086810'>the</span> <span m='4086930'>inside,</span> <span m='4087860'>you</span>
  <span m='4088040'>get</span> <span m='4088370'>blocks</span> <span m='4088840'>that</span>
  <span m='4088940'>are</span> <span m='4089040'>small</span> <span m='4089540'>versus</span>
  <span m='4089890'>blocks</span> <span m='4090240'>that are large.</span> <span m='4091810'>This</span>
  <span m='4091990'>is</span> <span m='4092140'>effectively</span> <span m='4092750'>a</span>
  <span m='4092810'>cache</span> <span m='4093220'>line</span> <span m='4093520'>size</span>
  <span m='4094830'>that</span> <span m='4094950'>gets</span> <span m='4095170'>brought</span>
  <span m='4095420'>in.</span> <span m='4096160'>And</span> <span m='4096310'>so</span>
  <span m='4096520'>the</span> <span m='4096859'>thing</span> <span m='4097140'>is</span>
  <span m='4097430'>that</span> <span m='4098939'>there</span> <span m='4099250'>are</span>
  <span m='4099359'>actually</span> <span m='4101100'>programs</span> <span m='4102319'>in</span>
  <span m='4102569'>which,</span> <span m='4103590'>when</span> <span m='4104149'>you</span>
  <span m='4104600'>run</span> <span m='4104870'>them</span> <span m='4105029'>on</span>
  <span m='4105220'>disk,</span> <span m='4105609'>there</span> <span m='4105790'>is</span>
  <span m='4105930'>no</span> <span m='4106290'>fixed</span> <span m='4106660'>size</span>
  <span m='4107189'>tuning</span> <span m='4107540'>parameter</span> <span m='4110210'>that</span>
  <span m='4110319'>beats</span> <span m='4110710'>the</span> <span m='4110830'>cache-oblivious</span>
  <span m='4111700'>one.</span> </p><p><span m='4113529'>So</span> <span m='4113670'>the</span>
  <span m='4113760'>cache-oblivious</span> <span m='4114479'>one</span> <span m='4114609'>will</span>
  <span m='4114770'>beat</span> <span m='4115100'>every</span> <span m='4115460'>fixed-size</span>
  <span m='4116240'>tuning</span> <span m='4116590'>parameters</span> <span m='4117250'>you</span>
  <span m='4117340'>put</span> <span m='4117569'>in.</span> <span m='4118090'>Because</span>
  <span m='4119130'>you</span> <span m='4119260'>don't</span> <span m='4119420'>have</span>
  <span m='4119580'>any</span> <span m='4119740'>control</span> <span m='4120359'>over</span>
  <span m='4120580'>where</span> <span m='4120920'>your</span> <span m='4121450'>file</span>
  <span m='4121859'>got</span> <span m='4122069'>laid</span> <span m='4122319'>out</span>
  <span m='4122479'>on</span> <span m='4122680'>disk</span> <span m='4124830'>and</span>
  <span m='4125620'>how</span> <span m='4125880'>much</span> <span m='4126130'>it's</span>
  <span m='4126279'>bringing</span> <span m='4126649'>in</span> <span m='4126830'>and</span>
  <span m='4126930'>how</span> <span m='4127130'>much</span> <span m='4127359'>it</span>
  <span m='4127490'>isn't</span> <span m='4128979'>varies.</span> </p><p><span m='4129720'>On</span>
  <span m='4129800'>the</span> <span m='4129930'>other</span> <span m='4130060'>hand,</span>
  <span m='4130399'>for</span> <span m='4131319'>in-core</span> <span m='4131810'>thing,</span>
  <span m='4132090'>you're</span> <span m='4132310'>exactly</span> <span m='4132830'>right.</span>
  <span m='4133439'>That,</span> <span m='4133950'>in</span> <span m='4134120'>principle,</span>
  <span m='4134700'>you</span> <span m='4134840'>could</span> <span m='4135029'>tune</span>
  <span m='4135160'>it</span> <span m='4135330'>up</span> <span m='4135470'>more</span>
  <span m='4136160'>if</span> <span m='4136310'>you</span> <span m='4136430'>make</span>
  <span m='4136660'>it</span> <span m='4137240'>more</span> <span m='4137550'>cache</span>
  <span m='4137870'>aware.</span> <span m='4138710'>But</span> <span m='4139060'>then,</span>
  <span m='4139250'>of</span> <span m='4139340'>course,</span> <span m='4139560'>you</span>
  <span m='4139680'>suffer</span> <span m='4140750'>from</span> <span m='4140990'>portability</span>
  <span m='4141720'>loss</span> <span m='4142229'>and</span> <span m='4142450'>from,</span>
  <span m='4142710'>if</span> <span m='4142819'>you're</span> <span m='4142939'>in</span>
  <span m='4142990'>a</span> <span m='4143040'>multi-programmed</span> <span m='4143689'>environment</span>
  <span m='4143964'>and</span> <span m='4144240'>so</span> <span m='4144399'>forth.</span>
  </p><p><span m='4144840'>So</span> <span m='4145450'>the</span> <span m='4145609'>answer</span>
  <span m='4145990'>is,</span> <span m='4146250'>that</span> <span m='4146430'>there</span>
  <span m='4146620'>are</span> <span m='4146760'>situations</span> <span m='4147529'>where</span>
  <span m='4147660'>you're</span> <span m='4147790'>doing</span> <span m='4148200'>some</span>
  <span m='4148399'>kind</span> <span m='4148700'>of</span> <span m='4150779'>embedded</span>
  <span m='4151330'>or</span> <span m='4151510'>dedicated</span> <span m='4152720'>type</span>
  <span m='4153029'>of</span> <span m='4153140'>application,</span> <span m='4154340'>you</span>
  <span m='4154569'>can</span> <span m='4155380'>take</span> <span m='4155620'>advantage</span>
  <span m='4156069'>of</span> <span m='4156109'>a</span> <span m='4156170'>lot</span>
  <span m='4156450'>of</span> <span m='4156580'>things</span> <span m='4157279'>that</span>
  <span m='4157430'>you</span> <span m='4157580'>want.</span> <span m='4157990'>There</span>
  <span m='4158100'>are</span> <span m='4158140'>other</span> <span m='4158340'>times</span>
  <span m='4158700'>where you're</span> <span m='4158870'>doing</span> <span m='4159130'>a</span>
  <span m='4159180'>multi-programmed</span> <span m='4161180'>environment,</span>
  <span m='4161700'>or</span> <span m='4161920'>where</span> <span m='4162080'>you</span>
  <span m='4162220'>want</span> <span m='4162450'>to</span> <span m='4163760'>be</span>
  <span m='4163990'>able</span> <span m='4164109'>to</span> <span m='4164170'>move</span>
  <span m='4164439'>something</span> <span m='4165640'>from</span> <span m='4165899'>one</span>
  <span m='4166140'>platform</span> <span m='4166649'>to</span> <span m='4166750'>another</span>
  <span m='4167020'>without</span> <span m='4167279'>having</span> <span m='4167529'>to</span>
  <span m='4167640'>re-engineer</span> <span m='4168430'>all</span> <span m='4168529'>of</span>
  <span m='4168649'>the</span> <span m='4169229'>tuning</span> <span m='4169550'>and</span>
  <span m='4169660'>testing.</span> <span m='4170590'>In</span> <span m='4170710'>which</span>
  <span m='4170899'>case</span> <span m='4171160'>it's</span> <span m='4171310'>better</span>
  <span m='4171580'>to</span> <span m='4171640'>use</span> <span m='4172990'>the</span>
  <span m='4173330'>cache</span> <span m='4173600'>oblivious.</span> </p><p><span
  m='4174189'>So</span> <span m='4174370'>as</span> <span m='4174670'>I</span> <span
  m='4174859'>mentioned,</span> <span m='4175550'>my</span> <span m='4175990'>view</span>
  <span m='4176300'>of</span> <span m='4176430'>these</span> <span m='4176689'>things</span>
  <span m='4176979'>is</span> <span m='4177229'>that</span> <span m='4178410'>performance</span>
  <span m='4178990'>is</span> <span m='4179140'>like</span> <span m='4179340'>a</span>
  <span m='4179430'>currency.</span> <span m='4181069'>It's a</span> <span m='4181310'>universal</span>
  <span m='4182080'>medium</span> <span m='4182420'>of</span> <span m='4182520'>exchange.</span>
  <span m='4183540'>So</span> <span m='4183710'>one</span> <span m='4183910'>place</span>
  <span m='4184189'>you</span> <span m='4184290'>might</span> <span m='4184490'>want</span>
  <span m='4184609'>to</span> <span m='4184649'>pay</span> <span m='4184880'>a</span>
  <span m='4184960'>little</span> <span m='4185260'>bit</span> <span m='4185410'>of</span>
  <span m='4185490'>performance</span> <span m='4186479'>is</span> <span m='4186620'>to</span>
  <span m='4186720'>make</span> <span m='4186910'>it</span> <span m='4187020'>so</span>
  <span m='4187149'>it's</span> <span m='4187260'>very</span> <span m='4187510'>portable</span>
  <span m='4188020'>as</span> <span m='4188090'>for</span> <span m='4188200'>the</span>
  <span m='4188300'>cache-oblivious</span> <span m='4189930'>stuff.</span> <span m='4190240'>So
  you get</span> <span m='4190660'>nearly</span> <span m='4191979'>good</span> <span
  m='4192279'>performance,</span> <span m='4192740'>but</span> <span m='4192890'>now</span>
  <span m='4193640'>I</span> <span m='4194020'>don't</span> <span m='4194210'>have</span>
  <span m='4194330'>that</span> <span m='4194510'>headache</span> <span m='4194870'>to</span>
  <span m='4194970'>worry</span> <span m='4195180'>about.</span> <span m='4197760'>And</span>
  <span m='4197960'>then</span> <span m='4198120'>sometimes,</span> <span m='4198670'>in</span>
  <span m='4198770'>fact,</span> <span m='4199190'>it</span> <span m='4199320'>actually</span>
  <span m='4200080'>does</span> <span m='4200310'>as</span> <span m='4200520'>well</span>
  <span m='4201000'>or</span> <span m='4201740'>better</span> <span m='4202080'>than</span>
  <span m='4202330'>the</span> <span m='4202420'>one.</span> <span m='4202880'>For
  matrix</span> <span m='4203360'>multiplication,</span> <span m='4204410'>the</span>
  <span m='4204520'>best</span> <span m='4204890'>algorithms</span> <span m='4205480'>are</span>
  <span m='4205620'>the</span> <span m='4205740'>cache</span> <span m='4206090'>oblivious</span>
  <span m='4206490'>ones that</span> <span m='4206780'>I'm</span> <span m='4206960'>aware</span>
  <span m='4207270'>of.</span> </p><p><span m='4207450'>AUDIENCE:</span> <span m='4207933'>[INAUDIBLE]</span>
  <span m='4210348'>currency</span> <span m='4210831'>and all</span> <span m='4211314'>the
  different</span> <span m='4211797'>currencies.</span> <span m='4212763'>Single</span>
  <span m='4213246'>currency.</span> </p><p><span m='4213729'>PROFESSOR:</span> <span
  m='4214220'>You want a</span> <span m='4214640'>currency</span> <span m='4215120'>for--</span>
  <span m='4215670'>so</span> <span m='4215900'>in</span> <span m='4216070'>fact</span>
  <span m='4216360'>the</span> <span m='4216440'>performance</span> <span m='4218030'>for</span>
  <span m='4218260'>this</span> <span m='4218520'>is</span> <span m='4219740'>people</span>
  <span m='4219920'>who</span> <span m='4220090'>have</span> <span m='4220210'>engineered</span>
  <span m='4220730'>it</span> <span m='4220860'>to</span> <span m='4220950'>take</span>
  <span m='4221180'>advantage</span> <span m='4221630'>of</span> <span m='4221710'>exactly</span>
  <span m='4222200'>the</span> <span m='4222290'>cache</span> <span m='4222580'>size,</span>
  <span m='4223280'>we</span> <span m='4223500'>can</span> <span m='4223600'>do</span>
  <span m='4224440'>just</span> <span m='4224730'>as</span> <span m='4224850'>well</span>
  <span m='4225110'>with</span> <span m='4225200'>the</span> <span m='4225270'>cache</span>
  <span m='4225570'>oblivious</span> <span m='4226040'>one.</span> <span m='4226470'>And</span>
  <span m='4226730'>particularly,</span> <span m='4227160'>if</span> <span m='4227250'>you</span>
  <span m='4227350'>think</span> <span m='4227570'>about</span> <span m='4227840'>it,</span>
  <span m='4227940'>when</span> <span m='4228060'>you've</span> <span m='4228170'>got</span>
  <span m='4228450'>three</span> <span m='4228700'>levels</span> <span m='4229150'>hierarchy,</span>
  <span m='4231490'>you've</span> <span m='4231620'>got</span> <span m='4231840'>12</span>
  <span m='4232280'>loops.</span> <span m='4236380'>And</span> <span m='4236550'>now</span>
  <span m='4236690'>you're</span> <span m='4236800'>going</span> <span m='4236930'>to</span>
  <span m='4237230'>tune</span> <span m='4237610'>that.</span> <span m='4239550'>It's</span>
  <span m='4239730'>hard</span> <span m='4239910'>to</span> <span m='4239980'>get</span>
  <span m='4240130'>it</span> <span m='4240200'>all</span> <span m='4240360'>right.</span>
  </p><p><span m='4244310'>So</span> <span m='4244500'>next</span> <span m='4244780'>time</span>
  <span m='4244940'>we're</span> <span m='4245030'>going</span> <span m='4245100'>to</span>
  <span m='4245170'>see</span> <span m='4245350'>a</span> <span m='4245390'>bunch</span>
  <span m='4245620'>of</span> <span m='4245720'>other</span> <span m='4245920'>examples</span>
  <span m='4246940'>of</span> <span m='4247480'>cache-oblivious</span> <span m='4248960'>algorithms</span>
  <span m='4250030'>that</span> <span m='4250240'>are</span> <span m='4250480'>optimal</span>
  <span m='4251580'>in</span> <span m='4251730'>terms</span> <span m='4252010'>of</span>
  <span m='4252080'>their</span> <span m='4252230'>use</span> <span m='4252510'>of</span>
  <span m='4252570'>cache.</span> <span m='4253110'>Of</span> <span m='4253230'>course,</span>
  <span m='4253480'>by</span> <span m='4253590'>the</span> <span m='4253680'>way,</span>
  <span m='4254130'>those</span> <span m='4254370'>people</span> <span m='4254660'>who</span>
  <span m='4254750'>are</span> <span m='4255280'>familiar</span> <span m='4255640'>with</span>
  <span m='4255790'>Strassen's</span> <span m='4256360'>algorithm,</span> <span m='4257960'>that's</span>
  <span m='4258170'>a</span> <span m='4258200'>cache-oblivious</span> <span m='4258980'>algorithm.</span>
  <span m='4259420'>Takes</span> <span m='4259680'>advantage</span> <span m='4260080'>the</span>
  <span m='4260190'>same</span> <span m='4260920'>kind</span> <span m='4261180'>of</span>
  <span m='4261280'>thing.</span> <span m='4261500'>And in</span> <span m='4261610'>fact</span>
  <span m='4261860'>you</span> <span m='4261950'>can</span> <span m='4262100'>analyze</span>
  <span m='4262660'>it</span> <span m='4262800'>and</span> <span m='4263490'>come</span>
  <span m='4263710'>up</span> <span m='4263860'>with</span> <span m='4264930'>good</span>
  <span m='4265110'>bounds</span> <span m='4265530'>on</span> <span m='4267370'>performance</span>
  <span m='4268000'>for</span> <span m='4268130'>Strassen's</span> <span m='4268600'>algorithm</span>
  <span m='4269520'>just</span> <span m='4269740'>the</span> <span m='4269810'>same.</span>
  <span m='4270670'>Just</span> <span m='4270930'>as</span> <span m='4271090'>we've</span>
  <span m='4271270'>done</span> <span m='4271440'>here.</span> </p>
uid: de1926ed-02fa-d947-746b-f4e847d859d3
---
