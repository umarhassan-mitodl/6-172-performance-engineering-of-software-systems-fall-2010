---
about_this_resource_text: <p><strong>Description:</strong> Lecture covering nondeterministic
  programming, including mutual exclusion, implementation of mutexes, and locking
  anomalies.</p> <p><strong>Speaker:</strong> Charles Leiserson</p>
content_type: resource
course_id: 6-172-performance-engineering-of-software-systems-fall-2010
embedded_media:
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.172F10/MIT6_172_F10_lec15_300k.mp4
  parent_uid: 54ebd2df04848e5ad82a102c096747a9
  title: Video-Internet Archive-MP4
  type: Video
  uid: 965b1d84302e5206e6cf1b76d4488783
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/itunes-u/lecture-15-nondeterministic/id481759887?i=109649115
  parent_uid: 54ebd2df04848e5ad82a102c096747a9
  title: Video-iTunes U-MP4
  type: Video
  uid: d6cc562992f61b3cf07e9e8224698b3e
- id: Video-YouTube-Stream
  media_location: gXRmNp4Wgb0
  parent_uid: 54ebd2df04848e5ad82a102c096747a9
  title: Video-YouTube-Stream
  type: Video
  uid: d15333da5c0d695c69076da34e6206a8
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/gXRmNp4Wgb0/default.jpg
  parent_uid: 54ebd2df04848e5ad82a102c096747a9
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 9ffc57daa5461fadf8103518fb0fa0be
- id: MIT6_172F10_lec15.pdf
  parent_uid: 54ebd2df04848e5ad82a102c096747a9
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-15-nondeterministic-programming/MIT6_172F10_lec15.pdf
  title: MIT6_172F10_lec15.pdf
  type: null
  uid: d8d31bfd66efd4700df346ab7eb47767
- id: 3Play-3PlayYouTubeid-MP4
  media_location: gXRmNp4Wgb0
  parent_uid: 54ebd2df04848e5ad82a102c096747a9
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: b241d42fe6547572d6c51a5c0d3e66b3
- id: gXRmNp4Wgb0.srt
  parent_uid: 54ebd2df04848e5ad82a102c096747a9
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-15-nondeterministic-programming/gXRmNp4Wgb0.srt
  title: 3play caption file
  type: null
  uid: 2609fe4623c731d8c18be7d9ac79f1dd
- id: gXRmNp4Wgb0.pdf
  parent_uid: 54ebd2df04848e5ad82a102c096747a9
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-15-nondeterministic-programming/gXRmNp4Wgb0.pdf
  title: 3play pdf file
  type: null
  uid: d8fb26e6be5cb603be7e19ef23ef4d46
- id: Caption-3Play YouTube id-SRT
  parent_uid: 54ebd2df04848e5ad82a102c096747a9
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 70d05149e7e833564956240653a9b257
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 54ebd2df04848e5ad82a102c096747a9
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 74abee574f555371baab0c51e0e70548
file: null
file_size: null
hide_download: true
hide_download_original: null
inline_embed_id: 34077494lecture15:nondeterministicprogramming69544271
layout: video
license: https://creativecommons.org/licenses/by-nc-sa/4.0/
order_index: 170
parent_uid: 24169d0487e846a39c316276f85b8cb5
related_resources_text: ''
short_url: lecture-15-nondeterministic-programming
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-15-nondeterministic-programming
title: 'Lecture 15: Nondeterministic Programming'
transcript: <p><span m='120'>The</span> <span m='190'>following</span> <span m='630'>content</span>
  <span m='1230'>is</span> <span m='1340'>provided</span> <span m='1790'>under</span>
  <span m='2070'>a</span> <span m='2090'>Creative</span> <span m='2500'>Commons</span>
  <span m='2910'>license.</span> <span m='3910'>Your</span> <span m='4200'>support</span>
  <span m='4700'>will</span> <span m='4870'>help</span> <span m='5100'>MIT</span>
  <span m='5580'>OpenCourseWare</span> <span m='6360'>continue</span> <span m='6870'>to</span>
  <span m='6950'>offer</span> <span m='7380'>high-quality</span> <span m='8119'>educational</span>
  <span m='8740'>resources</span> <span m='9390'>for</span> <span m='9520'>free.</span>
  <span m='10600'>To</span> <span m='10730'>make</span> <span m='10930'>a</span> <span
  m='10980'>donation</span> <span m='11620'>or</span> <span m='11930'>view</span>
  <span m='12340'>additional</span> <span m='12800'>materials</span> <span m='13340'>from</span>
  <span m='13500'>hundreds</span> <span m='13930'>of</span> <span m='14040'>MIT</span>
  <span m='14460'>courses,</span> <span m='15460'>visit</span> <span m='15790'>MIT</span>
  <span m='16219'>OpenCourseWare</span> <span m='17250'>at</span> <span m='17430'>ocw.mit.edu.</span>
  </p><p><span m='27870'>Let's</span> <span m='29940'>get</span> <span m='30150'>going</span>
  <span m='30400'>here.</span> <span m='35990'>So</span> <span m='38540'>this</span>
  <span m='38790'>is</span> <span m='39310'>a</span> <span m='39360'>lecture</span>
  <span m='39740'>that's</span> <span m='39960'>actually</span> <span m='40320'>appropriate</span>
  <span m='40830'>for</span> <span m='40940'>Halloween,</span> <span m='43130'>because</span>
  <span m='43500'>it's</span> <span m='43660'>a</span> <span m='43710'>scary</span>
  <span m='44160'>topic.</span> <span m='46670'>Non-deterministic</span> <span m='47660'>programming.</span>
  <span m='52410'>So</span> <span m='52570'>we've</span> <span m='52830'>been</span>
  <span m='53230'>looking</span> <span m='53650'>mostly at</span> <span m='54020'>deterministic</span>
  <span m='54750'>programs.</span> <span m='55280'>So a</span> <span m='55470'>program</span>
  <span m='55950'>is</span> <span m='56080'>deterministic</span> <span m='57740'>on
  a</span> <span m='57780'>given</span> <span m='58170'>input</span> <span m='59770'>if</span>
  <span m='59960'>every</span> <span m='60290'>memory</span> <span m='60700'>location</span>
  <span m='61260'>is</span> <span m='61410'>updated</span> <span m='62500'>with</span>
  <span m='62570'>the</span> <span m='62650'>same</span> <span m='62980'>sequence</span>
  <span m='63460'>of</span> <span m='63550'>values</span> <span m='64190'>in</span>
  <span m='64340'>every</span> <span m='65040'>execution.</span> </p><p><span m='68000'>So</span>
  <span m='68120'>if</span> <span m='68200'>you</span> <span m='68300'>look</span>
  <span m='68570'>at</span> <span m='68840'>the</span> <span m='69670'>memory</span>
  <span m='70820'>of</span> <span m='71070'>the</span> <span m='71480'>machine,</span>
  <span m='72070'>you</span> <span m='72170'>can</span> <span m='72300'>view</span>
  <span m='72580'>that</span> <span m='72970'>as,</span> <span m='74620'>essentially,</span>
  <span m='75350'>the</span> <span m='75440'>state</span> <span m='75890'>of</span>
  <span m='76000'>the</span> <span m='76100'>machine.</span> <span m='77250'>And</span>
  <span m='77370'>if</span> <span m='77450'>you're</span> <span m='77580'>always</span>
  <span m='77980'>updating</span> <span m='78440'>every</span> <span m='78660'>memory</span>
  <span m='78980'>location</span> <span m='79470'>with</span> <span m='79570'>exactly</span>
  <span m='80090'>the</span> <span m='80190'>same</span> <span m='80530'>sequence</span>
  <span m='81020'>of</span> <span m='81100'>values,</span> <span m='82900'>then</span>
  <span m='83070'>the</span> <span m='83150'>program</span> <span m='83620'>is</span>
  <span m='83760'>deterministic.</span> <span m='84530'>Now it</span> <span m='84660'>may
  be</span> <span m='86280'>that</span> <span m='86760'>two</span> <span m='87070'>memory</span>
  <span m='87430'>locations</span> <span m='88250'>may</span> <span m='88510'>be</span>
  <span m='88710'>updated</span> <span m='89400'>in</span> <span m='89660'>a</span>
  <span m='89700'>different</span> <span m='90070'>order.</span> </p><p><span m='91310'>So</span>
  <span m='91470'>you</span> <span m='91560'>may</span> <span m='91680'>have</span>
  <span m='91900'>one</span> <span m='93840'>location</span> <span m='94390'>which</span>
  <span m='94570'>is</span> <span m='94670'>updated</span> <span m='95570'>first</span>
  <span m='96020'>in</span> <span m='96130'>one</span> <span m='96340'>execution,</span>
  <span m='97670'>and</span> <span m='97780'>another</span> <span m='98120'>that's</span>
  <span m='98360'>second,</span> <span m='99110'>and</span> <span m='99270'>then</span>
  <span m='99410'>in</span> <span m='99530'>a</span> <span m='99600'>different</span>
  <span m='99900'>execution,</span> <span m='100370'>they</span> <span m='100450'>may</span>
  <span m='100650'>be</span> <span m='100810'>a</span> <span m='100860'>different</span>
  <span m='101150'>order.</span> <span m='101490'>That's</span> <span m='101760'>OK,</span>
  <span m='102130'>generally.</span> <span m='103270'>The</span> <span m='103430'>issue</span>
  <span m='103750'>is</span> <span m='104050'>whether</span> <span m='104360'>or</span>
  <span m='104420'>not</span> <span m='104790'>every</span> <span m='105110'>memory</span>
  <span m='105410'>location</span> <span m='105900'>sees</span> <span m='106410'>the</span>
  <span m='106490'>same</span> <span m='106870'>order.</span> <span m='107870'>And</span>
  <span m='108130'>if</span> <span m='108240'>they</span> <span m='108390'>do,</span>
  <span m='109330'>then</span> <span m='109590'>it's</span> <span m='110700'>for</span>
  <span m='110950'>every</span> <span m='112910'>execution,</span> <span m='114950'>then</span>
  <span m='115520'>it's</span> <span m='115730'>a</span> <span m='115800'>deterministic</span>
  <span m='116540'>program.</span> </p><p><span m='121850'>So</span> <span m='123130'>what's</span>
  <span m='123560'>the</span> <span m='123700'>advantage</span> <span m='125020'>of</span>
  <span m='127280'>having</span> <span m='127720'>a</span> <span m='127850'>deterministic</span>
  <span m='128669'>program?</span> <span m='130316'>Yeah?</span> </p><p><span m='131302'>AUDIENCE:</span>
  <span m='131795'>It</span> <span m='132781'>always</span> <span m='133274'>runs</span>
  <span m='133767'>the</span> <span m='134260'>same way</span> <span m='134753'>[INAUDIBLE].</span>
  </p><p><span m='135246'>PROFESSOR:</span> <span m='135740'>It always</span> <span
  m='135960'>runs the</span> <span m='136040'>same</span> <span m='136310'>way.</span>
  <span m='136470'>So</span> <span m='136780'>what?</span> <span m='137860'>What's</span>
  <span m='137950'>that good for?</span> </p><p><span m='138400'>AUDIENCE:</span>
  <span m='138855'>So you</span> <span m='139310'>can find bugs</span> <span m='139765'>easier.</span>
  </p><p><span m='140220'>PROFESSOR:</span> <span m='140675'>Yeah,</span> <span m='141130'>debugging.</span>
  <span m='142790'>It's</span> <span m='142970'>really</span> <span m='143290'>easy</span>
  <span m='143600'>to</span> <span m='143740'>find</span> <span m='144030'>bugs</span>
  <span m='144490'>if</span> <span m='144600'>every</span> <span m='144820'>time</span>
  <span m='145090'>you</span> <span m='145200'>run</span> <span m='145550'>it</span>
  <span m='145680'>it does</span> <span m='145940'>the</span> <span m='146020'>same</span>
  <span m='146340'>thing.</span> <span m='147030'>It's</span> <span m='147140'>much</span>
  <span m='147300'>harder</span> <span m='147720'>to</span> <span m='147810'>find</span>
  <span m='148190'>bugs</span> <span m='149480'>if,</span> <span m='149710'>when</span>
  <span m='149850'>you</span> <span m='149990'>run</span> <span m='150220'>it,</span>
  <span m='150970'>it</span> <span m='151120'>might</span> <span m='151360'>do</span>
  <span m='151470'>something</span> <span m='151920'>different.</span> </p><p><span
  m='154060'>So</span> <span m='154230'>that</span> <span m='154430'>leads</span>
  <span m='154990'>to</span> <span m='155490'>our</span> <span m='155640'>first</span>
  <span m='156910'>major</span> <span m='157310'>rule</span> <span m='157660'>of</span>
  <span m='157760'>thumb</span> <span m='158040'>about</span> <span m='158400'>determinism,</span>
  <span m='159780'>which</span> <span m='160110'>is</span> <span m='160370'>you</span>
  <span m='160500'>should</span> <span m='160710'>always</span> <span m='161460'>write</span>
  <span m='161910'>deterministic</span> <span m='162670'>programs.</span> <span m='166180'>Don't</span>
  <span m='166520'>write</span> </p><p><span m='167190'>non-deterministic</span> <span
  m='168200'>programs.</span> <span m='170690'>And</span> <span m='170880'>the</span>
  <span m='170980'>only</span> <span m='171150'>problem</span> <span m='171670'>is,</span>
  <span m='171870'>boy</span> <span m='172250'>is that</span> <span m='172550'>poor</span>
  <span m='173160'>quality</span> <span m='173860'>there.</span> <span m='174480'>So</span>
  <span m='174830'>basically,</span> <span m='175210'>it says,</span> <span m='175440'>always</span>
  <span m='175720'>write</span> <span m='175970'>non-deterministic</span> <span m='176750'>programs</span>
  <span m='177920'>unless</span> <span m='178310'>you</span> <span m='178430'>can't.</span>
  <span m='180570'>So</span> <span m='180710'>sometimes,</span> <span m='182250'>the</span>
  <span m='182450'>only</span> <span m='182660'>way</span> <span m='182850'>to</span>
  <span m='183050'>get</span> <span m='183560'>performance</span> <span m='184350'>is</span>
  <span m='184540'>to</span> <span m='184640'>do</span> <span m='184790'>something</span>
  <span m='185240'>non-deterministic.</span> <span m='189740'>So</span> <span m='190650'>this</span>
  <span m='191060'>lecture</span> <span m='191620'>is</span> <span m='191780'>basically</span>
  <span m='192380'>about</span> <span m='193550'>some</span> <span m='193890'>of</span>
  <span m='194000'>the</span> <span m='194100'>ways</span> <span m='194690'>of</span>
  <span m='194900'>doing</span> <span m='195740'>non-deterministic</span> <span m='196660'>programming.</span>
  <span m='198380'>So</span> <span m='198550'>it's</span> <span m='198670'>appropriate</span>
  <span m='199880'>that</span> <span m='200260'>we</span> <span m='203480'>say</span>
  <span m='204380'>this</span> <span m='204590'>is</span> <span m='204780'>not</span>
  <span m='205290'>for</span> <span m='205950'>those</span> <span m='206310'>who</span>
  <span m='206450'>are</span> <span m='206570'>faint</span> <span m='206900'>of</span>
  <span m='206990'>heart.</span> <span m='207940'>We</span> <span m='208110'>are</span>
  <span m='208190'>treading</span> <span m='208740'>into</span> <span m='211880'>dangerous</span>
  <span m='212400'>territory</span> <span m='212980'>here.</span> <span m='216020'>So</span>
  <span m='216410'>the</span> <span m='216500'>basic</span> <span m='217030'>rule</span>
  <span m='217360'>is,</span> <span m='217600'>as</span> <span m='217770'>I</span>
  <span m='217830'>say,</span> <span m='218130'>any</span> <span m='218410'>time</span>
  <span m='218680'>you</span> <span m='218800'>can,</span> <span m='219180'>make</span>
  <span m='219410'>your</span> <span m='219530'>program</span> <span m='219960'>deterministic.</span>
  </p><p><span m='222830'>So</span> <span m='222980'>we're</span> <span m='223110'>going</span>
  <span m='223190'>to</span> <span m='223280'>talk</span> <span m='223650'>about</span>
  <span m='224720'>the</span> <span m='225300'>number</span> <span m='225620'>one</span>
  <span m='225980'>way</span> <span m='226330'>that</span> <span m='226510'>people</span>
  <span m='226780'>introduce</span> <span m='227830'>non-determinism</span> <span
  m='228770'>into</span> <span m='228910'>programs,</span> <span m='229560'>which</span>
  <span m='229810'>is</span> <span m='230030'>via</span> <span m='230850'>mutual</span>
  <span m='231240'>exclusion</span> <span m='232430'>and</span> <span m='232740'>mutexes,</span>
  <span m='234300'>which</span> <span m='234520'>are a</span> <span m='234630'>type</span>
  <span m='234910'>of</span> <span m='235640'>lock,</span> <span m='236570'>and</span>
  <span m='236850'>then</span> <span m='237510'>look</span> <span m='238190'>at</span>
  <span m='238760'>some</span> <span m='239040'>of</span> <span m='239080'>the</span>
  <span m='239180'>anomalies</span> <span m='239830'>that</span> <span m='239970'>you</span>
  <span m='240090'>get.</span> <span m='241350'>Besides</span> <span m='241970'>just</span>
  <span m='242210'>things</span> <span m='242460'>being</span> <span m='244730'>non-deterministic,</span>
  <span m='245770'>you</span> <span m='245880'>can</span> <span m='245990'>also</span>
  <span m='246360'>get</span> <span m='246610'>some</span> <span m='246810'>very,</span>
  <span m='247240'>very</span> <span m='247530'>weird</span> <span m='247840'>behavior</span>
  <span m='248420'>sometimes</span> <span m='249630'>for</span> <span m='250380'>the</span>
  <span m='250850'>execution.</span> </p><p><span m='252100'>So we'll</span> <span
  m='252270'>start</span> <span m='252550'>out</span> <span m='252710'>with</span>
  <span m='252820'>mutual</span> <span m='253180'>exclusion.</span> <span m='255840'>So</span>
  <span m='256029'>let's</span> <span m='256279'>take</span> <span m='256500'>a</span>
  <span m='256560'>look,</span> <span m='256790'>for</span> <span m='256890'>example,</span>
  <span m='257470'>suppose</span> <span m='257970'>I'm</span> <span m='258120'>implementing</span>
  <span m='258630'>a</span> <span m='258660'>hash</span> <span m='259050'>table</span>
  <span m='259899'>as</span> <span m='260149'>a</span> <span m='260200'>set</span>
  <span m='260459'>of</span> <span m='260529'>bins.</span> <span m='260899'>And I'm</span>
  <span m='261370'>resolving</span> <span m='262070'>collisions</span> <span m='263190'>with</span>
  <span m='263810'>chaining.</span> <span m='264640'>So</span> <span m='264870'>here,</span>
  <span m='265160'>each</span> <span m='265800'>slot</span> <span m='266320'>of</span>
  <span m='266400'>my</span> <span m='266600'>hash</span> <span m='266990'>table</span>
  <span m='267890'>has</span> <span m='268440'>a</span> <span m='268540'>chain</span>
  <span m='269040'>of</span> <span m='269310'>all</span> <span m='269640'>the</span>
  <span m='269720'>values</span> <span m='270330'>that</span> <span m='270860'>resolve</span>
  <span m='271680'>to</span> <span m='271730'>that</span> <span m='271980'>slot.</span>
  <span m='274180'>And</span> <span m='275990'>if</span> <span m='276180'>I</span>
  <span m='276310'>have</span> <span m='276660'>a</span> <span m='277080'>value</span>
  <span m='277550'>x,</span> <span m='278200'>let's</span> <span m='278390'>say</span>
  <span m='278560'>it has</span> <span m='278830'>key</span> <span m='279070'>81,</span>
  <span m='279900'>and</span> <span m='280070'>I</span> <span m='280240'>want</span>
  <span m='280660'>to</span> <span m='281020'>insert</span> <span m='281530'>x</span>
  <span m='281820'>into</span> <span m='282030'>the</span> <span m='282130'>table,</span>
  <span m='283200'>I</span> <span m='283360'>first</span> <span m='284320'>compute</span>
  <span m='284860'>a</span> <span m='285070'>hash</span> <span m='286420'>of</span>
  <span m='286680'>x.</span> <span m='287920'>And</span> <span m='288130'>let's</span>
  <span m='288370'>say</span> <span m='288570'>it</span> <span m='289730'>hashes</span>
  <span m='290170'>to</span> <span m='290290'>this</span> <span m='290530'>particular</span>
  <span m='291070'>list</span> <span m='291370'>here.</span> </p><p><span m='293690'>And</span>
  <span m='293840'>then</span> <span m='293980'>what</span> <span m='294180'>I</span>
  <span m='294270'>do</span> <span m='294570'>is</span> <span m='294710'>I</span>
  <span m='294800'>say,</span> <span m='295090'>OK,</span> <span m='295620'>let</span>
  <span m='295790'>me</span> <span m='295960'>insert</span> <span m='296490'>x</span>
  <span m='296770'>into</span> <span m='296970'>the</span> <span m='297080'>table.</span>
  <span m='297990'>So</span> <span m='298180'>I</span> <span m='298270'>make</span>
  <span m='299140'>the</span> <span m='299340'>next</span> <span m='299780'>pointer</span>
  <span m='300000'>of</span> <span m='300180'>x</span> <span m='300650'>point</span>
  <span m='300960'>to</span> <span m='301980'>whatever</span> <span m='302510'>is</span>
  <span m='302830'>the</span> <span m='302900'>head</span> <span m='303280'>of</span>
  <span m='304710'>the</span> <span m='304850'>table.</span> <span m='307310'>And</span>
  <span m='307540'>then</span> <span m='307840'>I</span> <span m='308560'>make</span>
  <span m='308850'>the</span> <span m='308940'>table</span> <span m='309460'>0.2x.</span>
  <span m='312020'>And</span> <span m='312140'>that</span> <span m='312410'>effectively</span>
  <span m='313150'>inserts</span> <span m='314840'>x</span> <span m='317600'>into</span>
  <span m='317840'>the</span> <span m='317920'>hash</span> <span m='318270'>table.</span>
  <span m='319540'>Fairly</span> <span m='319940'>straightforward</span> <span m='320610'>piece</span>
  <span m='320860'>of</span> <span m='320920'>code.</span> <span m='321910'>I</span>
  <span m='322040'>would</span> <span m='322170'>expect</span> <span m='322600'>that</span>
  <span m='322750'>most</span> <span m='322930'>of</span> <span m='323120'>you</span>
  <span m='323300'>could</span> <span m='323520'>write</span> <span m='323820'>that</span>
  <span m='324080'>even</span> <span m='324360'>on</span> <span m='324490'>an</span>
  <span m='324590'>exam</span> <span m='325040'>and</span> <span m='325180'>get</span>
  <span m='325330'>it</span> <span m='325440'>right.</span> </p><p><span m='327760'>But</span>
  <span m='328080'>what</span> <span m='328240'>happens</span> <span m='329910'>when</span>
  <span m='331070'>we</span> <span m='331250'>say,</span> <span m='331670'>oh,</span>
  <span m='331980'>let's</span> <span m='332230'>have</span> <span m='332350'>some</span>
  <span m='333130'>concurrency.</span> <span m='333380'>Let's</span> <span m='333640'>have</span>
  <span m='334340'>the</span> <span m='334480'>ability</span> <span m='334960'>to</span>
  <span m='335070'>look</span> <span m='335320'>up</span> <span m='335510'>things</span>
  <span m='335780'>in a</span> <span m='335870'>hash</span> <span m='336240'>table</span>
  <span m='337170'>in</span> <span m='337430'>different</span> <span m='337890'>parallel</span>
  <span m='338330'>branches</span> <span m='341510'>of</span> <span m='341690'>a</span>
  <span m='341740'>parallel</span> <span m='342110'>program.</span> <span m='344080'>So</span>
  <span m='344280'>here,</span> <span m='344450'>we</span> <span m='344520'>have</span>
  <span m='344630'>a</span> <span m='344690'>concurrent</span> <span m='345160'>hash</span>
  <span m='345460'>table</span> <span m='345770'>now</span> <span m='346730'>where</span>
  <span m='347510'>I've</span> <span m='347710'>got</span> <span m='348010'>two</span>
  <span m='348200'>values,</span> <span m='349010'>and</span> <span m='349170'>I'm</span>
  <span m='349260'>going</span> <span m='349350'>to</span> <span m='349390'>have</span>
  <span m='349600'>two</span> <span m='349780'>different</span> <span m='350190'>threads</span>
  <span m='351190'>inserting</span> <span m='352350'>x</span> <span m='352770'>and</span>
  <span m='352890'>y.</span> <span m='354770'>So</span> <span m='354940'>one</span>
  <span m='355120'>of</span> <span m='355190'>them</span> <span m='355320'>is</span>
  <span m='355450'>going</span> <span m='355570'>to</span> <span m='355650'>do</span>
  <span m='355860'>this</span> <span m='356100'>one,</span> <span m='356770'>and</span>
  <span m='356900'>one</span> <span m='357100'>of</span> <span m='357190'>them</span>
  <span m='357360'>is</span> <span m='357480'>going</span> <span m='357600'>to</span>
  <span m='357680'>do</span> <span m='357840'>this</span> <span m='358070'>one.</span>
  <span m='360450'>So</span> <span m='360610'>let's</span> <span m='360840'>just</span>
  <span m='361040'>see</span> <span m='362040'>how</span> <span m='362290'>this</span>
  <span m='362530'>can</span> <span m='363100'>screw</span> <span m='363510'>up.</span>
  </p><p><span m='365580'>So</span> <span m='365800'>first,</span> <span m='366740'>we</span>
  <span m='367140'>hash</span> <span m='368880'>x,</span> <span m='369340'>and</span>
  <span m='369440'>it</span> <span m='369550'>hashes</span> <span m='370020'>to</span>
  <span m='370120'>this</span> <span m='370420'>particular</span> <span m='370910'>slot.</span>
  <span m='373440'>So</span> <span m='373620'>then</span> <span m='373830'>we</span>
  <span m='374050'>do,</span> <span m='374810'>just</span> <span m='375070'>as</span>
  <span m='375170'>we're</span> <span m='375290'>doing</span> <span m='375530'>before,</span>
  <span m='376280'>making</span> <span m='376670'>its</span> <span m='376850'>next</span>
  <span m='377170'>pointer</span> <span m='377490'>point</span> <span m='377750'>to</span>
  <span m='377840'>the</span> <span m='377940'>beginning</span> <span m='378320'>of</span>
  <span m='378400'>the</span> <span m='378480'>array.</span> <span m='382450'>Then</span>
  <span m='383050'>y</span> <span m='383360'>gets</span> <span m='383630'>in</span>
  <span m='383710'>the</span> <span m='383790'>picture,</span> <span m='384230'>and
  it</span> <span m='384340'>decides</span> <span m='384850'>oh,</span> <span m='385140'>I'm</span>
  <span m='385310'>going</span> <span m='385430'>to</span> <span m='386050'>hash.</span>
  <span m='386600'>And</span> <span m='387030'>oh,</span> <span m='387390'>it</span>
  <span m='387530'>hashes</span> <span m='387960'>to</span> <span m='388080'>exactly</span>
  <span m='388600'>the</span> <span m='388700'>same</span> <span m='388980'>slot.</span>
  </p><p><span m='391910'>And</span> <span m='392080'>then</span> <span m='392250'>y</span>
  <span m='392570'>makes</span> <span m='392880'>its</span> <span m='393120'>next</span>
  <span m='393460'>pointer</span> <span m='393790'>point</span> <span m='394130'>to</span>
  <span m='394220'>the</span> <span m='394310'>same</span> <span m='394550'>to</span>
  <span m='394830'>the</span> <span m='394960'>head</span> <span m='395210'>of</span>
  <span m='395300'>the</span> <span m='395380'>list.</span> <span m='397240'>And</span>
  <span m='397380'>then</span> <span m='397530'>it</span> <span m='397650'>sets</span>
  <span m='398900'>the</span> <span m='399070'>head</span> <span m='399300'>of</span>
  <span m='399410'>the</span> <span m='399500'>list</span> <span m='399810'>to</span>
  <span m='399860'>point</span> <span m='400200'>to</span> <span m='400290'>y.</span>
  <span m='401100'>So</span> <span m='401260'>now</span> <span m='401760'>y</span>
  <span m='402060'>is</span> <span m='402280'>in</span> <span m='402340'>the</span>
  <span m='402440'>list.</span> <span m='403700'>Whoops,</span> <span m='404630'>now</span>
  <span m='404910'>x</span> <span m='405960'>puts</span> <span m='406190'>itself</span>
  <span m='406710'>in the</span> <span m='406830'>list,</span> <span m='407160'>effectively</span>
  <span m='408260'>taking</span> <span m='408700'>y</span> <span m='409020'>out</span>
  <span m='409240'>of</span> <span m='409340'>the</span> <span m='409430'>list.</span>
  <span m='409780'>So</span> <span m='409950'>rather</span> <span m='410330'>than</span>
  <span m='410510'>x</span> <span m='410780'>and</span> <span m='410870'>y</span>
  <span m='411160'>both</span> <span m='411590'>being</span> <span m='411840'>in</span>
  <span m='411920'>the</span> <span m='412020'>list,</span> <span m='412890'>we</span>
  <span m='413040'>have</span> <span m='413240'>a</span> <span m='413300'>concurrency</span>
  <span m='413840'>bug.</span> </p><p><span m='418150'>So</span> <span m='419750'>this</span>
  <span m='420040'>is</span> <span m='421180'>clearly</span> <span m='421670'>a</span>
  <span m='421740'>race.</span> <span m='423770'>So</span> <span m='424490'>it's</span>
  <span m='424760'>a</span> <span m='424830'>determinacy</span> <span m='425580'>race,</span>
  <span m='427780'>because</span> <span m='428670'>we</span> <span m='428910'>have</span>
  <span m='429150'>two</span> <span m='431030'>parallel</span> <span m='432530'>instructions</span>
  <span m='433270'>accessing</span> <span m='433970'>essentially</span> <span m='434350'>the</span>
  <span m='434470'>same</span> <span m='434780'>location,</span> <span m='436090'>at</span>
  <span m='436230'>least</span> <span m='436550'>one</span> <span m='436790'>of</span>
  <span m='436910'>which--</span> <span m='437220'>in</span> <span m='437290'>this</span>
  <span m='437430'>case</span> <span m='437690'>both</span> <span m='437980'>of</span>
  <span m='438080'>them--</span> <span m='438450'>performing</span> <span m='439710'>a</span>
  <span m='439800'>store</span> <span m='440180'>to that</span> <span m='440490'>location.</span>
  <span m='442030'>So</span> <span m='442160'>that's</span> <span m='442450'>a</span>
  <span m='442520'>determinacy</span> <span m='443170'>race.</span> <span m='443890'>And</span>
  <span m='444070'>how</span> <span m='444440'>things</span> <span m='444750'>are</span>
  <span m='444800'>going</span> <span m='444900'>to</span> <span m='444960'>work</span>
  <span m='445220'>out</span> <span m='445520'>depends</span> <span m='445890'>upon</span>
  <span m='446580'>which</span> <span m='446950'>one</span> <span m='447120'>of</span>
  <span m='447180'>these</span> <span m='447430'>guys</span> <span m='448260'>goes</span>
  <span m='448570'>first.</span> <span m='449540'>Notice,</span> <span m='450290'>as</span>
  <span m='450600'>with</span> <span m='450750'>most</span> <span m='451070'>race</span>
  <span m='451350'>bugs,</span> <span m='451710'>that</span> <span m='451810'>if</span>
  <span m='451950'>this</span> <span m='452220'>code</span> <span m='452600'>all</span>
  <span m='452920'>executed</span> <span m='453500'>before</span> <span m='453920'>this</span>
  <span m='454160'>code,</span> <span m='454530'>we're</span> <span m='454700'>OK.</span>
  <span m='455780'>Or</span> <span m='456000'>if</span> <span m='456180'>this</span>
  <span m='456510'>code</span> <span m='457060'>all</span> <span m='457340'>executed</span>
  <span m='457900'>before</span> <span m='458280'>this</span> <span m='458580'>code,</span>
  <span m='459350'>we're</span> <span m='459590'>OK.</span> <span m='460780'>So</span>
  <span m='461010'>the</span> <span m='461120'>bug</span> <span m='461480'>occurs</span>
  <span m='462080'>when</span> <span m='462840'>they</span> <span m='462970'>happen</span>
  <span m='463320'>to</span> <span m='463420'>execute</span> <span m='464080'>at</span>
  <span m='464810'>essentially</span> <span m='465680'>the</span> <span m='466140'>same</span>
  <span m='466490'>time</span> <span m='467980'>and</span> <span m='468200'>their</span>
  <span m='468650'>instructions</span> <span m='469280'>interleave.</span> </p><p><span
  m='472380'>So</span> <span m='472550'>this</span> <span m='472690'>is</span> <span
  m='472740'>a</span> <span m='472810'>race</span> <span m='473150'>bug.</span> <span
  m='474110'>So</span> <span m='474370'>one</span> <span m='474660'>of</span> <span
  m='474790'>the</span> <span m='476060'>classic</span> <span m='476610'>ways</span>
  <span m='476900'>of</span> <span m='476990'>fixing</span> <span m='478930'>this</span>
  <span m='479230'>kind</span> <span m='479380'>of</span> <span m='479540'>race</span>
  <span m='479830'>bug</span> <span m='483610'>is</span> <span m='483860'>to</span>
  <span m='484530'>insist</span> <span m='485560'>on</span> <span m='485870'>some</span>
  <span m='486150'>kind</span> <span m='486470'>of</span> <span m='486560'>mutual</span>
  <span m='486960'>exclusion.</span> <span m='489820'>So</span> <span m='491980'>a</span>
  <span m='492180'>critical</span> <span m='492740'>section</span> <span m='494050'>is</span>
  <span m='494290'>a</span> <span m='494350'>piece</span> <span m='494700'>of</span>
  <span m='494830'>code</span> <span m='496230'>that</span> <span m='496500'>is</span>
  <span m='496660'>going</span> <span m='496770'>to</span> <span m='496830'>access</span>
  <span m='500440'>shared</span> <span m='500750'>data</span> <span m='502100'>that</span>
  <span m='502450'>must</span> <span m='502790'>not</span> <span m='503070'>be</span>
  <span m='503210'>executed</span> <span m='503810'>by</span> <span m='504030'>two</span>
  <span m='505770'>threads</span> <span m='506350'>at</span> <span m='506480'>the</span>
  <span m='506560'>same</span> <span m='506910'>time.</span> <span m='509400'>So</span>
  <span m='509590'>it</span> <span m='509710'>shouldn't</span> <span m='510020'>be</span>
  <span m='510170'>accessed</span> <span m='510740'>by</span> <span m='511420'>two</span>
  <span m='513750'>threads</span> <span m='514100'>at</span> <span m='514169'>the</span>
  <span m='514230'>same</span> <span m='514510'>time.</span> <span m='514809'>So</span>
  <span m='514909'>it's</span> <span m='515020'>mutual</span> <span m='515460'>exclusion.</span>
  <span m='516100'>So</span> <span m='516230'>that's</span> <span m='516450'>what
  a</span> <span m='516600'>critical</span> <span m='516980'>section</span> <span
  m='517450'>is.</span> </p><p><span m='519159'>And</span> <span m='521559'>we</span>
  <span m='521720'>have</span> <span m='522020'>a</span> <span m='522090'>mechanism</span>
  <span m='522820'>that</span> <span m='523169'>operating</span> <span m='523640'>systems</span>
  <span m='524100'>typically</span> <span m='524520'>provide--</span> <span m='525510'>as</span>
  <span m='526080'>well</span> <span m='526280'>as</span> <span m='526370'>runtime</span>
  <span m='526820'>systems,</span> <span m='527210'>but</span> <span m='527360'>you</span>
  <span m='527460'>can</span> <span m='527600'>build</span> <span m='527850'>your</span>
  <span m='528120'>own--</span> <span m='528910'>called</span> <span m='529190'>&quot;mutexes,&quot;</span>
  <span m='530310'>or</span> <span m='531040'>&quot;mutex</span> <span m='531860'>locks,&quot;</span>
  <span m='532370'>or</span> <span m='532570'>sometimes</span> <span m='533050'>just</span>
  <span m='533270'>&quot;locks.&quot;</span> <span m='535610'>So</span> <span m='535860'>a</span>
  <span m='535920'>mutex</span> <span m='537040'>is</span> <span m='537220'>an</span>
  <span m='537350'>object</span> <span m='537930'>that</span> <span m='538050'>has</span>
  <span m='538340'>a</span> <span m='538470'>lock</span> <span m='539030'>and</span>
  <span m='539220'>unlock</span> <span m='539860'>member</span> <span m='540220'>function.</span>
  <span m='543210'>And</span> <span m='543600'>any</span> <span m='543900'>attempt</span>
  <span m='544380'>by</span> <span m='544550'>a</span> <span m='544620'>thread</span>
  <span m='545030'>to</span> <span m='545150'>lock</span> <span m='545800'>an</span>
  <span m='545950'>already</span> <span m='546540'>locked</span> <span m='546900'>mutex</span>
  <span m='548140'>causes</span> <span m='548650'>that</span> <span m='548980'>thread</span>
  <span m='549340'>to</span> <span m='549440'>block.</span> </p><p><span m='551330'>And</span>
  <span m='552430'>&quot;block&quot;</span> <span m='552830'>is,</span> <span m='552970'>by</span>
  <span m='553100'>the</span> <span m='553190'>way,</span> <span m='553360'>a</span>
  <span m='553680'>hugely</span> <span m='554080'>overused</span> <span m='554630'>word</span>
  <span m='554870'>in</span> <span m='555000'>computer</span> <span m='555340'>science.</span>
  <span m='556190'>In</span> <span m='556320'>this</span> <span m='556500'>case,</span>
  <span m='556760'>by</span> <span m='556920'>&quot;block,&quot;</span> <span m='557330'>they</span>
  <span m='557460'>mean</span> <span m='557710'>&quot;wait.&quot;</span> <span m='558710'>It</span>
  <span m='560090'>waits</span> <span m='561060'>until</span> <span m='561540'>the</span>
  <span m='561630'>mutex is</span> <span m='562280'>unlocked.</span> <span m='565120'>So</span>
  <span m='565370'>whenever</span> <span m='566060'>you</span> <span m='566200'>have</span>
  <span m='567050'>something</span> <span m='567420'>that's</span> <span m='567610'>locked,</span>
  <span m='568210'>somebody</span> <span m='568500'>else</span> <span m='568680'>comes</span>
  <span m='568920'>and</span> <span m='569030'>tries</span> <span m='569380'>to</span>
  <span m='569570'>grab</span> <span m='570020'>the</span> <span m='570110'>lock.</span>
  <span m='571450'>The</span> <span m='571710'>mutex</span> <span m='572230'>mechanism</span>
  <span m='572770'>only</span> <span m='573050'>allows</span> <span m='573520'>one</span>
  <span m='573980'>thread</span> <span m='574430'>to</span> <span m='574530'>access</span>
  <span m='575040'>it.</span> <span m='575380'>The</span> <span m='575540'>other</span>
  <span m='575710'>one</span> <span m='575940'>waits</span> <span m='576320'>until</span>
  <span m='576570'>the lock</span> <span m='577000'>is</span> <span m='577170'>freed.</span>
  <span m='577850'>Then</span> <span m='578170'>this</span> <span m='578330'>other</span>
  <span m='578530'>one</span> <span m='578770'>can</span> <span m='578960'>go</span>
  <span m='583410'>access</span> <span m='583860'>it.</span> </p><p><span m='586220'>So</span>
  <span m='586440'>what</span> <span m='586620'>we</span> <span m='586740'>can</span>
  <span m='586940'>do</span> <span m='587490'>is</span> <span m='588910'>build</span>
  <span m='589150'>a</span> <span m='589210'>concurrent</span> <span m='589690'>hash</span>
  <span m='590060'>table</span> <span m='592120'>by</span> <span m='592370'>modifying</span>
  <span m='593810'>each</span> <span m='594120'>slot</span> <span m='594770'>in</span>
  <span m='594970'>the</span> <span m='595160'>table</span> <span m='596230'>to</span>
  <span m='596350'>have</span> <span m='596660'>both</span> <span m='597525'>a</span>
  <span m='597940'>mutex,</span> <span m='598820'>L,</span> <span m='599770'>and</span>
  <span m='599950'>a</span> <span m='600010'>pointer</span> <span m='600550'>called</span>
  <span m='600880'>&quot;head&quot;</span> <span m='601760'>to</span> <span m='601880'>the</span>
  <span m='601980'>slot</span> <span m='602420'>contents.</span> <span m='605290'>And</span>
  <span m='605410'>then</span> <span m='605550'>the</span> <span m='605670'>idea</span>
  <span m='606110'>is</span> <span m='606750'>that</span> <span m='607480'>what</span>
  <span m='607650'>we'll</span> <span m='607780'>do</span> <span m='608040'>is</span>
  <span m='608200'>hash</span> <span m='609350'>the</span> <span m='609460'>value</span>
  <span m='609980'>to</span> <span m='610090'>a</span> <span m='610200'>slot.</span>
  <span m='611370'>But</span> <span m='611630'>before</span> <span m='612100'>we</span>
  <span m='612280'>access</span> <span m='612840'>the</span> <span m='612960'>elements</span>
  <span m='613350'>of</span> <span m='613390'>the</span> <span m='613470'>slot,</span>
  <span m='613940'>we're</span> <span m='614070'>going</span> <span m='614210'>to</span>
  <span m='614250'>grab</span> <span m='614750'>the</span> <span m='614850'>lock</span>
  <span m='616020'>on</span> <span m='616260'>the</span> <span m='616350'>slot.</span>
  <span m='617460'>So</span> <span m='617680'>every</span> <span m='618080'>slot</span>
  <span m='618510'>in</span> <span m='618600'>the</span> <span m='618690'>table</span>
  <span m='619110'>has</span> <span m='619340'>a</span> <span m='619390'>lock</span>
  <span m='619750'>here.</span> <span m='619980'>Now,</span> <span m='620200'>I</span>
  <span m='620330'>could</span> <span m='620530'>have</span> <span m='620620'>a</span>
  <span m='620710'>lock</span> <span m='621080'>on</span> <span m='621210'>the</span>
  <span m='621280'>whole</span> <span m='621560'>table.</span> <span m='622040'>What's</span>
  <span m='622250'>the</span> <span m='622340'>problem</span> <span m='622680'>with</span>
  <span m='622800'>that?</span> <span m='624820'>Sure.</span> </p><p><span m='625763'>AUDIENCE:</span>
  <span m='626246'>[INAUDIBLE]</span> <span m='629627'>basically</span> <span m='630110'>can't</span>
  <span m='630593'>do anything.</span> <span m='631076'>You can't</span> <span m='631559'>read.</span>
  <span m='632042'>You couldn't be</span> <span m='632525'>reading from the table.</span>
  </p><p><span m='633020'>PROFESSOR:</span> <span m='633430'>Yeah,</span> <span m='633710'>so
  if</span> <span m='633880'>you</span> <span m='633970'>have</span> <span m='634060'>a</span>
  <span m='634100'>lock</span> <span m='634470'>on</span> <span m='634570'>the</span>
  <span m='634630'>whole</span> <span m='634900'>table--</span> </p><p><span m='635460'>AUDIENCE:</span>
  <span m='635878'>You would</span> <span m='636296'>defeat</span> <span m='636714'>the
  purpose</span> <span m='637132'>[INAUDIBLE]</span> </p><p><span m='637550'>PROFESSOR:</span>
  <span m='637600'>You defeat the</span> <span m='637910'>purpose of</span> <span
  m='638000'>trying</span> <span m='638210'>to</span> <span m='638330'>have</span>
  <span m='638450'>a</span> <span m='638510'>concurrent</span> <span m='638930'>hash</span>
  <span m='639230'>table,</span> <span m='641100'>right?</span> <span m='641380'>Because</span>
  <span m='641530'>only</span> <span m='641770'>one</span> <span m='642770'>thread</span>
  <span m='643160'>can</span> <span m='643310'>actually</span> <span m='643610'>access</span>
  <span m='644100'>the</span> <span m='644200'>hash</span> <span m='644510'>table</span>
  <span m='644830'>at a</span> <span m='644910'>time.</span> <span m='645260'>So in</span>
  <span m='645330'>this</span> <span m='645540'>case,</span> <span m='646150'>what</span>
  <span m='646320'>we'll</span> <span m='646460'>do</span> <span m='646810'>is</span>
  <span m='647150'>we'll</span> <span m='647680'>lock</span> <span m='648430'>each</span>
  <span m='648730'>slot</span> <span m='649200'>of the</span> <span m='649270'>hash</span>
  <span m='649580'>table.</span> <span m='651310'>And</span> <span m='651530'>there</span>
  <span m='651740'>are</span> <span m='651880'>actually</span> <span m='652170'>mechanisms</span>
  <span m='652750'>where you can</span> <span m='653010'>lock</span> <span m='653450'>each</span>
  <span m='653680'>element</span> <span m='654110'>of</span> <span m='654220'>the</span>
  <span m='654310'>hash</span> <span m='654670'>table</span> <span m='655030'>or</span>
  <span m='655670'>a</span> <span m='655780'>constant</span> <span m='656210'>number</span>
  <span m='656430'>of</span> <span m='656500'>elements.</span> <span m='658040'>But</span>
  <span m='658230'>basically,</span> <span m='660020'>what</span> <span m='660190'>we're</span>
  <span m='660280'>trying</span> <span m='660420'>to</span> <span m='660560'>do</span>
  <span m='660750'>is</span> <span m='660850'>make</span> <span m='661080'>it</span>
  <span m='661200'>so</span> <span m='661420'>that</span> <span m='661830'>the</span>
  <span m='662080'>odds</span> <span m='662450'>are</span> <span m='662800'>that</span>
  <span m='663160'>if</span> <span m='663250'>you</span> <span m='663310'>have</span>
  <span m='663390'>a</span> <span m='663470'>big</span> <span m='663660'>enough</span>
  <span m='663870'>table</span> <span m='664360'>and</span> <span m='664480'>relatively</span>
  <span m='665120'>few</span> <span m='666910'>processors</span> <span m='667570'>you're</span>
  <span m='667640'>running</span> <span m='667930'>on,</span> <span m='668100'>the</span>
  <span m='668220'>odds</span> <span m='668560'>that</span> <span m='668730'>they'll</span>
  <span m='668910'>conflict</span> <span m='669380'>are</span> <span m='669460'>going</span>
  <span m='669580'>to</span> <span m='669620'>be</span> <span m='669760'>very</span>
  <span m='670000'>low.</span> </p><p><span m='673100'>So</span> <span m='673270'>what</span>
  <span m='673420'>we</span> <span m='673530'>do</span> <span m='673680'>is</span>
  <span m='673790'>we</span> <span m='673900'>grab</span> <span m='674280'>a</span>
  <span m='674330'>lock</span> <span m='674680'>on</span> <span m='674810'>the</span>
  <span m='674890'>slot,</span> <span m='676220'>and</span> <span m='676430'>then</span>
  <span m='676600'>we</span> <span m='676780'>play</span> <span m='677180'>the</span>
  <span m='677280'>same</span> <span m='677650'>game</span> <span m='678850'>of</span>
  <span m='679250'>inserting</span> <span m='679810'>ourselves</span> <span m='680980'>at</span>
  <span m='681170'>the</span> <span m='681240'>head.</span> <span m='681670'>And</span>
  <span m='681860'>then</span> <span m='681990'>we</span> <span m='682150'>unlock</span>
  <span m='682860'>the</span> <span m='682940'>slot.</span> <span m='686770'>So</span>
  <span m='687360'>what</span> <span m='687550'>that</span> <span m='687810'>does</span>
  <span m='688260'>is it</span> <span m='688330'>means</span> <span m='688760'>that</span>
  <span m='689070'>only</span> <span m='690050'>one</span> <span m='690380'>of</span>
  <span m='690490'>the</span> <span m='690620'>two</span> <span m='690860'>threads</span>
  <span m='691360'>in</span> <span m='691430'>the</span> <span m='691500'>previous</span>
  <span m='691900'>example</span> <span m='694120'>can</span> <span m='694250'>actually</span>
  <span m='694590'>execute</span> <span m='695690'>this</span> <span m='695960'>code</span>
  <span m='696280'>at</span> <span m='696390'>a</span> <span m='696460'>time.</span>
  <span m='698260'>And</span> <span m='698430'>so</span> <span m='698920'>it</span>
  <span m='699130'>guarantees</span> <span m='699860'>that</span> <span m='700220'>the</span>
  <span m='700530'>two</span> <span m='701310'>regions</span> <span m='701750'>of</span>
  <span m='701850'>code</span> <span m='702500'>will</span> <span m='702820'>either</span>
  <span m='703340'>execute</span> <span m='703790'>in</span> <span m='703920'>this</span>
  <span m='704140'>order</span> <span m='704590'>or</span> <span m='704780'>in</span>
  <span m='704850'>this</span> <span m='705090'>order,</span> <span m='705530'>and</span>
  <span m='705640'>you'll</span> <span m='705790'>never</span> <span m='706050'>get</span>
  <span m='706290'>the</span> <span m='706390'>instructions</span> <span m='707000'>interleaved.</span>
  </p><p><span m='709460'>Now,</span> <span m='710920'>this</span> <span m='711210'>is</span>
  <span m='711420'>introducing</span> <span m='713300'>non-determinism.</span> <span
  m='715150'>Why</span> <span m='715460'>is</span> <span m='715630'>this</span> <span
  m='715830'>going</span> <span m='715930'>to</span> <span m='715970'>be</span> <span
  m='716090'>non-deterministic?</span> <span m='718740'>Yes?</span> </p><p><span m='720130'>AUDIENCE:</span>
  <span m='720630'>[INAUDIBLE]</span> <span m='721130'>lock first,</span> <span m='721630'>it'll
  be</span> <span m='722130'>[INAUDIBLE].</span> </p><p><span m='722630'>PROFESSOR:</span>
  <span m='723050'>Yeah,</span> <span m='723220'>depending upon</span> <span m='723510'>which</span>
  <span m='723710'>one</span> <span m='723920'>gets</span> <span m='724110'>the</span>
  <span m='724170'>lock</span> <span m='724510'>first,</span> <span m='727860'>the</span>
  <span m='728360'>length</span> <span m='728740'>list</span> <span m='729080'>in</span>
  <span m='729190'>there</span> <span m='729390'>will</span> <span m='729540'>have</span>
  <span m='729690'>the</span> <span m='729830'>elements</span> <span m='730210'>in</span>
  <span m='730300'>a</span> <span m='730360'>different</span> <span m='730650'>order.</span>
  <span m='732660'>So</span> <span m='732980'>a</span> <span m='733050'>program</span>
  <span m='733560'>that</span> <span m='733690'>depends</span> <span m='734150'>on</span>
  <span m='734300'>the</span> <span m='734390'>order</span> <span m='734740'>of</span>
  <span m='734800'>that</span> <span m='735010'>list</span> <span m='736530'>is</span>
  <span m='736700'>going</span> <span m='736820'>to</span> <span m='736870'>behave</span>
  <span m='737220'>differently</span> <span m='738210'>from</span> <span m='738420'>run</span>
  <span m='738630'>to</span> <span m='738730'>run.</span> <span m='742520'>So</span>
  <span m='742700'>let's</span> <span m='742920'>recall</span> <span m='743860'>the</span>
  <span m='743960'>definition</span> <span m='744630'>of</span> <span m='744720'>a</span>
  <span m='744780'>determinacy</span> <span m='745470'>race.</span> <span m='746610'>It</span>
  <span m='746710'>occurs</span> <span m='747220'>when</span> <span m='747570'>two</span>
  <span m='747750'>logically</span> <span m='748330'>parallel</span> <span m='748760'>instructions</span>
  <span m='749430'>access</span> <span m='749980'>the</span> <span m='750060'>same</span>
  <span m='750390'>memory</span> <span m='750660'>location,</span> <span m='751630'>and</span>
  <span m='751720'>at</span> <span m='751820'>least</span> <span m='752130'>one</span>
  <span m='752290'>of</span> <span m='752370'>the</span> <span m='752500'>instructions</span>
  <span m='753180'>performs</span> <span m='753455'>a</span> <span m='753730'>write.</span>
  </p><p><span m='756080'>So</span> <span m='756290'>that</span> <span m='756580'>is,</span>
  <span m='758670'>we</span> <span m='758940'>do</span> <span m='759130'>have</span>
  <span m='759220'>a</span> <span m='759310'>determinacy</span> <span m='760040'>race</span>
  <span m='760680'>when</span> <span m='761010'>we</span> <span m='761190'>introduce</span>
  <span m='761700'>locks.</span> <span m='763480'>Locks</span> <span m='763840'>are</span>
  <span m='764010'>essentially,</span> <span m='764440'>we're</span> <span m='764530'>going</span>
  <span m='764610'>to</span> <span m='764680'>have</span> <span m='764750'>an</span>
  <span m='764820'>intentional</span> <span m='765480'>determinacy</span> <span m='766140'>race.</span>
  <span m='768680'>So</span> <span m='769060'>a</span> <span m='769840'>program</span>
  <span m='770250'>execution</span> <span m='770840'>with</span> <span m='770980'>no</span>
  <span m='771280'>determinacy</span> <span m='772020'>races</span> <span m='773080'>means</span>
  <span m='773400'>the</span> <span m='773480'>program</span> <span m='774010'>is</span>
  <span m='774320'>deterministic</span> <span m='775430'>on</span> <span m='775770'>that</span>
  <span m='776110'>input.</span> </p><p><span m='777350'>So</span> <span m='777490'>if
  there are</span> <span m='777610'>no</span> <span m='777850'>determinacy</span>
  <span m='778500'>races,</span> <span m='779790'>then</span> <span m='781200'>although</span>
  <span m='782420'>individual</span> <span m='782930'>locations</span> <span m='783600'>may</span>
  <span m='783770'>be</span> <span m='783930'>updated</span> <span m='784420'>in</span>
  <span m='784520'>a</span> <span m='784620'>different</span> <span m='784950'>order</span>
  <span m='785300'>in</span> <span m='785380'>a</span> <span m='785430'>parallel</span>
  <span m='785900'>execution,</span> <span m='789150'>every</span> <span m='790590'>memory</span>
  <span m='790910'>location</span> <span m='791400'>will</span> <span m='791520'>be</span>
  <span m='791680'>updated</span> <span m='792200'>by</span> <span m='792380'>exactly</span>
  <span m='792970'>the</span> <span m='793060'>same</span> <span m='793990'>thing</span>
  <span m='794390'>at</span> <span m='794480'>the</span> <span m='794550'>same</span>
  <span m='795140'>time.</span> <span m='795500'>The</span> <span m='795690'>order</span>
  <span m='796030'>will</span> <span m='796190'>be</span> <span m='797000'>of update</span>
  <span m='797450'>of</span> <span m='797540'>operations</span> <span m='798150'>on</span>
  <span m='798330'>any</span> <span m='798520'>given</span> <span m='798860'>location</span>
  <span m='799420'>will</span> <span m='799540'>be</span> <span m='799630'>the</span>
  <span m='799730'>same</span> <span m='800170'>always.</span> <span m='802960'>So</span>
  <span m='803100'>that's</span> <span m='803350'>actually</span> <span m='803710'>a</span>
  <span m='803760'>theorem,</span> <span m='805070'>which</span> <span m='805240'>we're</span>
  <span m='805350'>not</span> <span m='805510'>going</span> <span m='805590'>to</span>
  <span m='805670'>prove.</span> </p><p><span m='807950'>But</span> <span m='808200'>I</span>
  <span m='808350'>think</span> <span m='809410'>if</span> <span m='809590'>you</span>
  <span m='809680'>think</span> <span m='809880'>about</span> <span m='810160'>it,</span>
  <span m='810260'>it's</span> <span m='810450'>fairly</span> <span m='810700'>straightforward.</span>
  <span m='811240'>If</span> <span m='811860'>you</span> <span m='811970'>never</span>
  <span m='812250'>have</span> <span m='812950'>two</span> <span m='813100'>guys</span>
  <span m='813390'>in</span> <span m='813490'>parallel</span> <span m='813940'>that</span>
  <span m='814030'>could</span> <span m='814190'>possibly</span> <span m='815430'>affect</span>
  <span m='815800'>the</span> <span m='815880'>same</span> <span m='816170'>location,</span>
  <span m='817380'>then</span> <span m='818040'>the</span> <span m='818140'>behavior</span>
  <span m='818730'>always</span> <span m='819260'>is</span> <span m='819410'>going</span>
  <span m='819490'>to</span> <span m='819580'>be</span> <span m='819750'>the</span>
  <span m='819850'>same</span> <span m='820310'>thing.</span> <span m='820760'>Things</span>
  <span m='821070'>are</span> <span m='821120'>going</span> <span m='821230'>to</span>
  <span m='821270'>get</span> <span m='821480'>written</span> <span m='821770'>in</span>
  <span m='821840'>the</span> <span m='821920'>same</span> <span m='822230'>order.</span>
  </p><p><span m='824020'>So</span> <span m='824150'>the</span> <span m='824240'>program</span>
  <span m='824910'>in</span> <span m='824990'>that</span> <span m='825200'>case</span>
  <span m='825440'>always</span> <span m='825910'>behaves</span> <span m='826500'>the</span>
  <span m='826590'>same</span> <span m='827080'>on</span> <span m='827200'>that</span>
  <span m='827440'>given</span> <span m='827730'>input,</span> <span m='829510'>no</span>
  <span m='829680'>matter</span> <span m='829950'>how</span> <span m='830240'>it's</span>
  <span m='830370'>scheduled</span> <span m='830920'>and</span> <span m='831010'>executed.</span>
  <span m='832960'>We'll</span> <span m='833140'>always</span> <span m='833460'>have</span>
  <span m='833630'>essentially</span> <span m='834030'>the</span> <span m='834130'>same</span>
  <span m='834480'>behavior,</span> <span m='835040'>even</span> <span m='835370'>though</span>
  <span m='836220'>it</span> <span m='836370'>may</span> <span m='836530'>get</span>
  <span m='836700'>scheduled</span> <span m='837150'>one</span> <span m='837410'>way</span>
  <span m='837620'>or</span> <span m='837740'>another.</span> <span m='844210'>And</span>
  <span m='844520'>one</span> <span m='844680'>of</span> <span m='844750'>the</span>
  <span m='844820'>nice</span> <span m='845150'>things</span> <span m='845600'>that</span>
  <span m='845880'>we</span> <span m='846010'>have</span> <span m='846300'>in</span>
  <span m='846430'>our</span> <span m='847320'>race</span> <span m='847630'>detection</span>
  <span m='848100'>tool</span> <span m='848350'>Cilkscreen</span> <span m='849250'>is</span>
  <span m='849590'>that</span> <span m='849720'>if</span> <span m='849860'>we</span>
  <span m='849980'>do</span> <span m='850370'>have</span> <span m='850710'>determinacy</span>
  <span m='851640'>races</span> <span m='852150'>that</span> <span m='852250'>exist</span>
  <span m='853300'>in</span> <span m='853600'>an</span> <span m='853925'>ostensibly</span>
  <span m='854250'>deterministic</span> <span m='855020'>program--</span> <span m='855590'>that</span>
  <span m='855710'>is,</span> <span m='855830'>a</span> <span m='855880'>program</span>
  <span m='856280'>with</span> <span m='856410'>no</span> <span m='856570'>mutexes.</span>
  <span m='858460'>If</span> <span m='859280'>basically</span> <span m='859930'>it</span>
  <span m='862820'>just</span> <span m='863620'>reads</span> <span m='863870'>and</span>
  <span m='863990'>writes</span> <span m='864760'>on</span> <span m='864980'>locations</span>
  <span m='865590'>and</span> <span m='865690'>so</span> <span m='865880'>forth,</span>
  <span m='866370'>then</span> <span m='866540'>Cilkscreen</span> <span m='867270'>guarantees</span>
  <span m='867720'>to</span> <span m='867830'>find</span> <span m='868170'>such</span>
  <span m='868400'>a</span> <span m='868460'>race.</span> <span m='870250'>So</span>
  <span m='870460'>It's</span> <span m='870590'>nice</span> <span m='870890'>that</span>
  <span m='870990'>we</span> <span m='871100'>get</span> <span m='871180'>a</span>
  <span m='871270'>guarantee</span> <span m='872370'>out</span> <span m='872550'>of</span>
  <span m='872660'>Cilkscreen.</span> </p><p><span m='878640'>So</span> <span m='878790'>this</span>
  <span m='878970'>is</span> <span m='879040'>all</span> <span m='879840'>beautiful,</span>
  <span m='881340'>elegant,</span> <span m='882550'>everything</span> <span m='882940'>works</span>
  <span m='883230'>out</span> <span m='883430'>great</span> <span m='883860'>if</span>
  <span m='884060'>there</span> <span m='884220'>are</span> <span m='884260'>no</span>
  <span m='886370'>determinacy</span> <span m='887050'>races.</span> <span m='888270'>But</span>
  <span m='888570'>when</span> <span m='888850'>we</span> <span m='888960'>do</span>
  <span m='889110'>something</span> <span m='889440'>like a</span> <span m='889740'>concurrent</span>
  <span m='890190'>hash</span> <span m='890540'>table,</span> <span m='891080'>we're</span>
  <span m='891510'>intentionally</span> <span m='893130'>putting</span> <span m='893440'>in</span>
  <span m='894540'>a</span> <span m='895050'>determinacy area.</span> <span m='896240'>So</span>
  <span m='896360'>that</span> <span m='897690'>asks</span> <span m='898120'>sort</span>
  <span m='898290'>of</span> <span m='898350'>a</span> <span m='898390'>natural</span>
  <span m='898660'>question.</span> <span m='899000'>Why</span> <span m='899280'>would</span>
  <span m='899500'>I</span> <span m='899570'>want</span> <span m='900010'>to</span>
  <span m='900960'>have</span> <span m='902580'>a</span> <span m='902670'>concurrent</span>
  <span m='903100'>hash</span> <span m='903390'>table?</span> <span m='904050'>Why</span>
  <span m='904250'>not</span> <span m='904550'>make</span> <span m='904770'>it</span>
  <span m='904900'>so</span> <span m='905010'>that</span> <span m='905160'>my</span>
  <span m='905300'>program</span> <span m='907840'>is</span> <span m='908080'>deterministic?</span>
  </p><p><span m='909450'>Why</span> <span m='909660'>might</span> <span m='910070'>a</span>
  <span m='910160'>concurrent</span> <span m='910580'>hash</span> <span m='910850'>table</span>
  <span m='911130'>be</span> <span m='911290'>an</span> <span m='911780'>advantageous</span>
  <span m='912610'>thing</span> <span m='913190'>to</span> <span m='913370'>have</span>
  <span m='913560'>in</span> <span m='913630'>a</span> <span m='913680'>program</span>
  <span m='914140'>that</span> <span m='914240'>you</span> <span m='914330'>wanted</span>
  <span m='914590'>to</span> <span m='914640'>go</span> <span m='914810'>fast?</span>
  <span m='919290'>Some</span> <span m='919470'>ideas?</span> <span m='920780'>Where</span>
  <span m='920970'>might</span> <span m='921120'>you</span> <span m='921220'>want</span>
  <span m='921360'>to</span> <span m='921410'>use</span> <span m='921610'>it?</span>
  <span m='922187'>Yeah?</span> </p><p><span m='922644'>AUDIENCE:</span> <span m='923101'>Speed?</span>
  </p><p><span m='923560'>PROFESSOR:</span> <span m='923890'>Yeah,</span> <span m='924250'>speed.</span>
  <span m='924300'>But I mean,</span> <span m='924670'>what's an</span> <span m='924750'>application?</span>
  <span m='925300'>What's</span> <span m='925440'>a</span> <span m='925510'>use</span>
  <span m='925840'>case,</span> <span m='926830'>as</span> <span m='927150'>the</span>
  <span m='928930'>entrepreneurs</span> <span m='929620'>would</span> <span m='929770'>ask</span>
  <span m='930030'>you?</span> <span m='931640'>Where</span> <span m='931890'>is it
  that</span> <span m='932120'>you would</span> <span m='932350'>really</span> <span
  m='932650'>want</span> <span m='932830'>to</span> <span m='932870'>use</span> <span
  m='933280'>a</span> <span m='933350'>concurrent</span> <span m='933720'>hash</span>
  <span m='934010'>table</span> <span m='934590'>to</span> <span m='934710'>give</span>
  <span m='934880'>you</span> <span m='935010'>speed?</span> <span m='938420'>Yeah?</span>
  </p><p><span m='938910'>AUDIENCE:</span> <span m='939400'>If you</span> <span m='939890'>started
  using</span> <span m='940380'>it</span> <span m='940870'>[INAUDIBLE]</span> <span
  m='941850'>along with</span> <span m='942340'>your system</span> <span m='942830'>[INAUDIBLE]</span>
  <span m='945430'>values.</span> </p><p><span m='945820'>PROFESSOR:</span> <span
  m='946275'>Yeah,</span> <span m='946730'>it</span> <span m='946970'>could</span>
  <span m='947100'>be</span> <span m='947230'>that</span> <span m='947420'>there's</span>
  <span m='947570'>some</span> <span m='947750'>sort</span> <span m='947940'>of</span>
  <span m='949150'>global</span> <span m='950870'>table</span> <span m='951270'>that</span>
  <span m='951410'>you</span> <span m='951510'>want</span> <span m='951830'>a</span>
  <span m='951940'>lot</span> <span m='952150'>of</span> <span m='952230'>people</span>
  <span m='952560'>to</span> <span m='952650'>be</span> <span m='952820'>able</span>
  <span m='952940'>to</span> <span m='953020'>access</span> <span m='953520'>at</span>
  <span m='953620'>one</span> <span m='953840'>time.</span> <span m='956990'>So</span>
  <span m='957240'>if</span> <span m='957410'>you</span> <span m='957580'>lock</span>
  <span m='957940'>down</span> <span m='958240'>and</span> <span m='958300'>only</span>
  <span m='958530'>had</span> <span m='958690'>one</span> <span m='959820'>thread</span>
  <span m='960220'>accessing</span> <span m='960485'>at</span> <span m='960750'>a</span>
  <span m='960960'>time,</span> <span m='961450'>you</span> <span m='961880'>reduce</span>
  <span m='962690'>how</span> <span m='962840'>much</span> <span m='963200'>concurrency</span>
  <span m='963670'>that</span> <span m='963810'>you</span> <span m='963940'>could</span>
  <span m='964140'>have.</span> <span m='964670'>That's</span> <span m='964860'>a</span>
  <span m='964890'>good</span> <span m='965030'>one.</span> <span m='965796'>Yeah?</span>
  </p><p><span m='966768'>AUDIENCE:</span> <span m='967254'>Perhaps</span> <span m='967740'>most
  of the</span> <span m='968226'>time,</span> <span m='968712'>people</span> <span
  m='969198'>are</span> <span m='969684'>just reading.</span> <span m='970170'>So
  if you</span> <span m='970656'>had</span> <span m='971142'>something</span> <span
  m='971628'>concurrent,</span> <span m='972114'>your reading</span> <span m='972600'>should
  be</span> <span m='973086'>fine.</span> <span m='975516'>So in</span> <span m='976002'>that
  case,</span> <span m='976488'>a</span> <span m='976974'>lot more reading</span>
  <span m='977946'>high performance</span> <span m='978432'>[INAUDIBLE]</span> </p><p><span
  m='981348'>PROFESSOR:</span> <span m='981834'>Yeah,</span> <span m='982350'>so in</span>
  <span m='982710'>fact,</span> <span m='982930'>there's</span> <span m='983140'>a</span>
  <span m='983210'>type</span> <span m='983480'>of</span> <span m='984540'>lock</span>
  <span m='984860'>called</span> <span m='985090'>a</span> <span m='985140'>reader-writer</span>
  <span m='985780'>lock,</span> <span m='987040'>which</span> <span m='987290'>allows</span>
  <span m='988610'>one</span> <span m='988950'>writer</span> <span m='989430'>to</span>
  <span m='990300'>operate,</span> <span m='991010'>but</span> <span m='991270'>many</span>
  <span m='991540'>readers.</span> <span m='993650'>So</span> <span m='993810'>that's</span>
  <span m='994270'>another</span> <span m='994540'>type</span> <span m='994780'>of</span>
  <span m='994900'>concurrency</span> <span m='995480'>control.</span> <span m='997120'>So</span>
  <span m='997280'>just</span> <span m='997510'>another</span> <span m='997830'>place,</span>
  <span m='998230'>a</span> <span m='998380'>common</span> <span m='998770'>place</span>
  <span m='999180'>that</span> <span m='999310'>you</span> <span m='999410'>use</span>
  <span m='999650'>it,</span> <span m='999770'>is</span> <span m='999970'>when</span>
  <span m='1000120'>you're</span> <span m='1000210'>memoizing.</span> <span m='1002440'>Meaning</span>
  <span m='1002930'>I</span> <span m='1003060'>do</span> <span m='1003240'>a</span>
  <span m='1003300'>computation,</span> <span m='1004040'>I</span> <span m='1004090'>want</span>
  <span m='1004260'>to</span> <span m='1004310'>remember</span> <span m='1004720'>the</span>
  <span m='1004840'>results</span> <span m='1005350'>so</span> <span m='1005490'>that
  if</span> <span m='1005690'>I</span> <span m='1005760'>see</span> <span m='1006020'>it</span>
  <span m='1006090'>again,</span> <span m='1007820'>I</span> <span m='1008020'>can</span>
  <span m='1008780'>look</span> <span m='1009030'>it</span> <span m='1009130'>up</span>
  <span m='1009380'>rather</span> <span m='1009690'>than</span> <span m='1009790'>having</span>
  <span m='1010080'>to</span> <span m='1010150'>compute</span> <span m='1010500'>it</span>
  <span m='1010650'>again</span> <span m='1010960'>from</span> <span m='1011120'>scratch.</span>
  </p><p><span m='1012210'>So</span> <span m='1012290'>you</span> <span m='1012380'>might</span>
  <span m='1012610'>keep</span> <span m='1012880'>all</span> <span m='1013050'>those</span>
  <span m='1013280'>values</span> <span m='1013690'>in</span> <span m='1013780'>a</span>
  <span m='1013810'>hash</span> <span m='1014120'>table.</span> <span m='1016060'>Well,</span>
  <span m='1016390'>if</span> <span m='1016720'>I</span> <span m='1016830'>go</span>
  <span m='1017410'>in</span> <span m='1017590'>the</span> <span m='1017650'>hash</span>
  <span m='1017970'>table,</span> <span m='1018700'>now</span> <span m='1018900'>I'm</span>
  <span m='1019010'>going to</span> <span m='1019170'>have</span> <span m='1019340'>concurrent</span>
  <span m='1019770'>accesses</span> <span m='1021110'>to</span> <span m='1021230'>that</span>
  <span m='1021410'>hash</span> <span m='1021710'>table</span> <span m='1022100'>if</span>
  <span m='1022230'>I've</span> <span m='1022350'>got</span> <span m='1022510'>a</span>
  <span m='1022550'>parallel</span> <span m='1023000'>program</span> <span m='1023680'>that</span>
  <span m='1023850'>wants</span> <span m='1024119'>to</span> <span m='1024200'>do</span>
  <span m='1024319'>memorizing.</span> <span m='1025890'>And</span> <span m='1026050'>there</span>
  <span m='1026210'>are</span> <span m='1026260'>a</span> <span m='1026300'>bunch</span>
  <span m='1026560'>of</span> <span m='1026660'>other</span> <span m='1026819'>cases.</span>
  </p><p><span m='1029050'>So</span> <span m='1029190'>we</span> <span m='1029280'>have</span>
  <span m='1029599'>determinacy</span> <span m='1030260'>races.</span> <span m='1031300'>And</span>
  <span m='1031730'>we</span> <span m='1031819'>have</span> <span m='1031900'>a</span>
  <span m='1031980'>great</span> <span m='1032329'>guarantee</span> <span m='1033760'>that</span>
  <span m='1034329'>if</span> <span m='1034520'>there</span> <span m='1034660'>is</span>
  <span m='1034869'>a</span> <span m='1034950'>race,</span> <span m='1035680'>we</span>
  <span m='1035810'>guarantee</span> <span m='1036270'>to</span> <span m='1036349'>find</span>
  <span m='1036790'>it.</span> <span m='1040869'>Now,</span> <span m='1041470'>there's</span>
  <span m='1041640'>another</span> <span m='1042020'>type</span> <span m='1042290'>of</span>
  <span m='1042460'>race,</span> <span m='1042730'>and in</span> <span m='1042890'>fact,</span>
  <span m='1043170'>you'll</span> <span m='1043300'>hear</span> <span m='1043500'>more</span>
  <span m='1043839'>about</span> <span m='1044109'>this</span> <span m='1044270'>type</span>
  <span m='1044490'>of</span> <span m='1044670'>race</span> <span m='1045000'>if</span>
  <span m='1045119'>you</span> <span m='1046010'>read</span> <span m='1046230'>the</span>
  <span m='1046319'>literature</span> <span m='1046859'>than</span> <span m='1047000'>you</span>
  <span m='1047099'>hear</span> <span m='1047310'>about</span> <span m='1047560'>determinacy</span>
  <span m='1048180'>races.</span> <span m='1050170'>So</span> <span m='1050360'>a</span>
  <span m='1050440'>data</span> <span m='1050850'>race</span> <span m='1051980'>occurs</span>
  <span m='1052590'>when</span> <span m='1052850'>you</span> <span m='1052940'>have</span>
  <span m='1053130'>two</span> <span m='1053340'>logically</span> <span m='1053970'>parallel</span>
  <span m='1054440'>instructions</span> <span m='1056370'>holding</span> <span m='1056830'>no</span>
  <span m='1057000'>locks</span> <span m='1057510'>in</span> <span m='1057670'>common.</span>
  <span m='1059060'>And</span> <span m='1059220'>they</span> <span m='1059340'>access</span>
  <span m='1059890'>the</span> <span m='1059970'>same</span> <span m='1060250'>location,</span>
  <span m='1060810'>and at</span> <span m='1060950'>least</span> <span m='1061210'>one</span>
  <span m='1061340'>of</span> <span m='1061400'>the</span> <span m='1061490'>instructions</span>
  <span m='1062090'>performs</span> <span m='1062650'>a</span> <span m='1062850'>write.</span>
  </p><p><span m='1064730'>So</span> <span m='1064900'>this</span> <span m='1065110'>is</span>
  <span m='1065240'>saying</span> <span m='1066230'>that</span> <span m='1066430'>I've</span>
  <span m='1066570'>got</span> <span m='1066770'>accesses.</span> <span m='1069310'>And</span>
  <span m='1069600'>if</span> <span m='1069720'>they</span> <span m='1069840'>have</span>
  <span m='1069970'>no</span> <span m='1070250'>locks</span> <span m='1070640'>in</span>
  <span m='1070750'>common--</span> <span m='1071340'>so</span> <span m='1071530'>it</span>
  <span m='1071650'>could</span> <span m='1071860'>be</span> <span m='1072070'>that</span>
  <span m='1072510'>you</span> <span m='1072730'>have</span> <span m='1072950'>a</span>
  <span m='1073470'>problem</span> <span m='1073860'>where</span> <span m='1074010'>one</span>
  <span m='1074230'>of</span> <span m='1074330'>them</span> <span m='1074490'>holds</span>
  <span m='1075110'>a</span> <span m='1075200'>lock</span> <span m='1076730'>L,</span>
  <span m='1077340'>and</span> <span m='1077470'>another</span> <span m='1077700'>one</span>
  <span m='1077870'>holds</span> <span m='1078160'>L</span> <span m='1078380'>prime.</span>
  <span m='1079720'>And</span> <span m='1079880'>then</span> <span m='1080030'>they</span>
  <span m='1080310'>access</span> <span m='1080890'>the</span> <span m='1080970'>location,</span>
  <span m='1081710'>that's</span> <span m='1081980'>going</span> <span m='1082090'>to</span>
  <span m='1082160'>be</span> <span m='1082980'>a</span> <span m='1084270'>data</span>
  <span m='1084700'>race,</span> <span m='1086230'>because</span> <span m='1086780'>they</span>
  <span m='1086890'>don't</span> <span m='1087080'>hold</span> <span m='1087300'>locks</span>
  <span m='1087640'>in</span> <span m='1087730'>common.</span> </p><p><span m='1088030'>But</span>
  <span m='1088130'>if</span> <span m='1088290'>I</span> <span m='1088400'>have</span>
  <span m='1089140'>L</span> <span m='1089500'>and</span> <span m='1089810'>L</span>
  <span m='1091760'>being</span> <span m='1092180'>the</span> <span m='1092260'>locks</span>
  <span m='1092640'>that</span> <span m='1092770'>the</span> <span m='1092890'>two</span>
  <span m='1093070'>threads</span> <span m='1093360'>hold,</span> <span m='1093630'>and
  they</span> <span m='1093760'>access</span> <span m='1094035'>the</span> <span m='1094310'>same</span>
  <span m='1094580'>location,</span> <span m='1095010'>that's</span> <span m='1095250'>not</span>
  <span m='1095480'>a</span> <span m='1095540'>data</span> <span m='1095830'>race</span>
  <span m='1096130'>now.</span> <span m='1096770'>It</span> <span m='1097040'>is</span>
  <span m='1097310'>a</span> <span m='1097390'>determinacy</span> <span m='1098120'>race,</span>
  <span m='1099180'>because it's</span> <span m='1099350'>going</span> <span m='1099460'>to</span>
  <span m='1099520'>matter</span> <span m='1100410'>which</span> <span m='1100620'>order</span>
  <span m='1100890'>it</span> <span m='1100950'>is,</span> <span m='1101120'>but</span>
  <span m='1101210'>it's</span> <span m='1101310'>not</span> <span m='1101560'>a</span>
  <span m='1101610'>data</span> <span m='1101930'>race,</span> <span m='1103340'>because</span>
  <span m='1103710'>the</span> <span m='1103780'>locks,</span> <span m='1104200'>in</span>
  <span m='1104300'>some</span> <span m='1104500'>sense,</span> <span m='1104760'>are</span>
  <span m='1104840'>protecting</span> <span m='1105450'>access.</span> </p><p><span
  m='1107160'>So</span> <span m='1107460'>Cilkscreen,</span> <span m='1108330'>in</span>
  <span m='1108460'>fact,</span> <span m='1108810'>understands</span> <span m='1109450'>locks</span>
  <span m='1109880'>and</span> <span m='1110040'>will</span> <span m='1110150'>not</span>
  <span m='1110460'>report</span> <span m='1110900'>a</span> <span m='1110960'>determinacy</span>
  <span m='1111660'>race</span> <span m='1112480'>unless</span> <span m='1112830'>it</span>
  <span m='1112920'>is</span> <span m='1113090'>also</span> <span m='1113730'>a</span>
  <span m='1113870'>data</span> <span m='1114190'>race.</span> <span m='1118880'>However,</span>
  <span m='1121420'>since</span> <span m='1121790'>codes</span> <span m='1122180'>that</span>
  <span m='1122340'>use</span> <span m='1122590'>locks</span> <span m='1123220'>are</span>
  <span m='1123450'>non-deterministic</span> <span m='1124360'>by</span> <span m='1124530'>intention,</span>
  <span m='1126360'>they</span> <span m='1126680'>actually</span> <span m='1127120'>weaken</span>
  <span m='1128850'>Cilkscreen's</span> <span m='1129600'>guarantee.</span> <span
  m='1130440'>And</span> <span m='1131220'>in</span> <span m='1131480'>particular,</span>
  <span m='1132660'>in</span> <span m='1132840'>its</span> <span m='1133030'>execution</span>
  <span m='1133860'>that</span> <span m='1133960'>it</span> <span m='1134100'>does,</span>
  <span m='1134530'>if</span> <span m='1134680'>it</span> <span m='1134820'>finds</span>
  <span m='1135500'>a</span> <span m='1135610'>data</span> <span m='1135920'>race,</span>
  <span m='1136490'>it's</span> <span m='1137040'>going</span> <span m='1137150'>to</span>
  <span m='1137210'>say,</span> <span m='1137500'>I'm</span> <span m='1137630'>going</span>
  <span m='1137700'>to</span> <span m='1137780'>ignore</span> <span m='1138250'>that</span>
  <span m='1138540'>data</span> <span m='1138820'>race.</span> </p><p><span m='1139240'>But</span>
  <span m='1139460'>now</span> <span m='1141210'>it</span> <span m='1141650'>is</span>
  <span m='1141870'>only</span> <span m='1142050'>going</span> <span m='1142150'>to</span>
  <span m='1142200'>follow</span> <span m='1142620'>one</span> <span m='1143000'>of</span>
  <span m='1143110'>the</span> <span m='1143250'>two</span> <span m='1143460'>paths</span>
  <span m='1144530'>that</span> <span m='1144710'>might</span> <span m='1144990'>arise</span>
  <span m='1145520'>from</span> <span m='1145650'>that</span> <span m='1145890'>data</span>
  <span m='1146150'>race.</span> <span m='1151460'>In</span> <span m='1151640'>other</span>
  <span m='1151790'>words,</span> <span m='1152000'>it</span> <span m='1152100'>doesn't</span>
  <span m='1152340'>follow</span> <span m='1152570'>both</span> <span m='1152890'>paths.</span>
  <span m='1153990'>If</span> <span m='1154210'>you</span> <span m='1154300'>could</span>
  <span m='1154440'>think</span> <span m='1154630'>about</span> <span m='1154900'>it,</span>
  <span m='1155130'>when</span> <span m='1155930'>one</span> <span m='1156180'>of</span>
  <span m='1156280'>them</span> <span m='1156450'>wins--</span> <span m='1158480'>so</span>
  <span m='1158620'>you</span> <span m='1158700'>have</span> <span m='1158780'>a</span>
  <span m='1158850'>race</span> <span m='1159180'>between</span> <span m='1159530'>two</span>
  <span m='1159830'>critical</span> <span m='1160220'>sections.</span> </p><p><span
  m='1160970'>When</span> <span m='1161220'>one</span> <span m='1161400'>of</span>
  <span m='1161490'>them</span> <span m='1161580'>wins,</span> <span m='1162330'>you
  can</span> <span m='1162420'>imagine</span> <span m='1163270'>that's</span> <span
  m='1163460'>one</span> <span m='1164500'>possible</span> <span m='1165080'>outcome</span>
  <span m='1165490'>of</span> <span m='1165550'>the</span> <span m='1165650'>computation.</span>
  <span m='1166300'>When</span> <span m='1166400'>the</span> <span m='1166530'>other</span>
  <span m='1166790'>wins,</span> <span m='1168060'>it's</span> <span m='1168590'>another</span>
  <span m='1170280'>path.</span> <span m='1171090'>And</span> <span m='1171230'>what</span>
  <span m='1171400'>Cilkscreen</span> <span m='1171880'>does</span> <span m='1172160'>is</span>
  <span m='1172300'>it</span> <span m='1172470'>picks</span> <span m='1172850'>one</span>
  <span m='1173110'>path.</span> <span m='1173420'>In</span> <span m='1173530'>fact,</span>
  <span m='1173750'>it</span> <span m='1173970'>picks</span> <span m='1174710'>the</span>
  <span m='1174820'>path</span> <span m='1175270'>which</span> <span m='1175510'>is</span>
  <span m='1175680'>the</span> <span m='1175780'>one</span> <span m='1176060'>that</span>
  <span m='1176210'>would</span> <span m='1176350'>occur</span> <span m='1176760'>in</span>
  <span m='1176950'>the</span> <span m='1177020'>cereal</span> <span m='1177530'>execution.</span>
  <span m='1180120'>So</span> <span m='1180300'>there's</span> <span m='1180480'>a</span>
  <span m='1180530'>whole</span> <span m='1180790'>path</span> <span m='1181210'>there</span>
  <span m='1181430'>that</span> <span m='1181580'>you're</span> <span m='1181680'>not</span>
  <span m='1181890'>exploring.</span> <span m='1185240'>So</span> <span m='1185420'>Cilkscreen's</span>
  <span m='1186080'>guarantee</span> <span m='1187770'>is</span> <span m='1187960'>not</span>
  <span m='1188310'>going</span> <span m='1188420'>to</span> <span m='1188470'>be</span>
  <span m='1188600'>strong</span> <span m='1188970'>there.</span> </p><p><span m='1189420'>However,</span>
  <span m='1190270'>if</span> <span m='1190440'>the</span> <span m='1190530'>critical</span>
  <span m='1190930'>sections,</span> <span m='1191420'>in</span> <span m='1191520'>fact,</span>
  <span m='1191940'>commute--</span> <span m='1193050'>that</span> <span m='1193200'>is,</span>
  <span m='1193370'>they</span> <span m='1193510'>do</span> <span m='1193780'>exactly</span>
  <span m='1194360'>the</span> <span m='1194450'>same</span> <span m='1194790'>thing,</span>
  <span m='1195100'>no</span> <span m='1195230'>matter</span> <span m='1195470'>what</span>
  <span m='1195710'>the</span> <span m='1195830'>order.</span> <span m='1197450'>So</span>
  <span m='1197610'>for</span> <span m='1197720'>example,</span> <span m='1198030'>if</span>
  <span m='1198110'>they're</span> <span m='1198220'>both</span> <span m='1198580'>incrementing</span>
  <span m='1198900'>a</span> <span m='1199220'>value,</span> <span m='1200780'>then</span>
  <span m='1200940'>the</span> <span m='1201030'>result,</span> <span m='1201630'>after</span>
  <span m='1202680'>doing</span> <span m='1203000'>one</span> <span m='1203320'>versus</span>
  <span m='1203650'>after</span> <span m='1203940'>the</span> <span m='1204080'>other</span>
  <span m='1204280'>is</span> <span m='1204500'>the</span> <span m='1204570'>same</span>
  <span m='1204890'>value,</span> <span m='1205940'>then</span> <span m='1206300'>you</span>
  <span m='1206410'>get</span> <span m='1206570'>a</span> <span m='1206600'>guarantee</span>
  <span m='1207150'>out</span> <span m='1207320'>of</span> <span m='1207640'>Cilkscreen.</span>
  <span m='1210860'>So</span> <span m='1211030'>Cilkscreen</span> <span m='1211240'>could</span>
  <span m='1211510'>still</span> <span m='1211770'>be</span> <span m='1211890'>very</span>
  <span m='1212120'>helpful</span> <span m='1212530'>for</span> <span m='1212690'>finding</span>
  <span m='1213100'>bugs,</span> <span m='1213460'>because</span> <span m='1215790'>typically,</span>
  <span m='1216220'>when</span> <span m='1216380'>you</span> <span m='1216510'>organize</span>
  <span m='1217030'>your</span> <span m='1217130'>computation,</span> <span m='1217830'>if</span>
  <span m='1217930'>it</span> <span m='1218060'>occurs</span> <span m='1218360'>in</span>
  <span m='1218430'>this</span> <span m='1219000'>order,</span> <span m='1219890'>there's</span>
  <span m='1220220'>typically</span> <span m='1220700'>some</span> <span m='1222180'>execution</span>
  <span m='1222970'>or</span> <span m='1223160'>input</span> <span m='1223660'>where</span>
  <span m='1223790'>you</span> <span m='1223860'>can</span> <span m='1223990'>make</span>
  <span m='1224170'>things</span> <span m='1224410'>occur</span> <span m='1224670'>in</span>
  <span m='1224740'>the</span> <span m='1224870'>other</span> <span m='1225070'>order.</span>
  </p><p><span m='1226920'>So</span> <span m='1227070'>you</span> <span m='1227240'>can</span>
  <span m='1227370'>actually</span> <span m='1227710'>cover</span> <span m='1228990'>more</span>
  <span m='1229800'>races</span> <span m='1230420'>than</span> <span m='1230560'>you</span>
  <span m='1230640'>might</span> <span m='1230840'>imagine</span> <span m='1232040'>on</span>
  <span m='1232260'>first</span> <span m='1232580'>blush.</span> <span m='1233920'>But</span>
  <span m='1234200'>it</span> <span m='1234320'>is</span> <span m='1234540'>a</span>
  <span m='1234610'>danger.</span> <span m='1236286'>But</span> <span m='1236630'>what</span>
  <span m='1236760'>we're</span> <span m='1236860'>talking</span> <span m='1237120'>about</span>
  <span m='1237360'>today</span> <span m='1237590'>is</span> <span m='1237750'>dangerous</span>
  <span m='1238140'>programming,</span> <span m='1240230'>non-deterministic</span>
  <span m='1240960'>programming.</span> <span m='1242180'>So</span> <span m='1242380'>when</span>
  <span m='1242550'>you</span> <span m='1242630'>start</span> <span m='1242940'>using</span>
  <span m='1243880'>mutexes,</span> <span m='1244890'>some</span> <span m='1245120'>of</span>
  <span m='1245170'>the</span> <span m='1245230'>guarantees</span> <span m='1245950'>and</span>
  <span m='1246050'>so</span> <span m='1246230'>forth</span> <span m='1247550'>get</span>
  <span m='1247730'>much</span> <span m='1247980'>dicier.</span> <span m='1249600'>Any</span>
  <span m='1249760'>questions</span> <span m='1250190'>about</span> <span m='1250440'>that?</span>
  </p><p><span m='1255120'>Now,</span> <span m='1256100'>if</span> <span m='1256300'>you</span>
  <span m='1256530'>have</span> <span m='1256750'>no</span> <span m='1257090'>data</span>
  <span m='1257450'>races</span> <span m='1257890'>in</span> <span m='1258010'>your</span>
  <span m='1258190'>code,</span> <span m='1259090'>that</span> <span m='1259420'>doesn't</span>
  <span m='1259840'>mean</span> <span m='1261150'>that</span> <span m='1261360'>you</span>
  <span m='1261610'>have</span> <span m='1261860'>no</span> <span m='1262100'>bugs.</span>
  <span m='1264430'>So</span> <span m='1264600'>for</span> <span m='1264740'>example,</span>
  <span m='1265670'>here's</span> <span m='1265940'>a</span> <span m='1266000'>way</span>
  <span m='1266230'>somebody</span> <span m='1267330'>might</span> <span m='1268990'>fix</span>
  <span m='1269350'>that</span> <span m='1269970'>insertion</span> <span m='1270550'>code.</span>
  <span m='1272070'>So</span> <span m='1272220'>we</span> <span m='1272510'>hash</span>
  <span m='1272910'>the</span> <span m='1273010'>key,</span> <span m='1273650'>we</span>
  <span m='1273900'>grab</span> <span m='1274280'>a</span> <span m='1274330'>lock,</span>
  <span m='1274900'>we</span> <span m='1275320'>set</span> <span m='1275620'>x</span>
  <span m='1276390'>next</span> <span m='1277210'>to</span> <span m='1277340'>be</span>
  <span m='1278750'>whatever</span> <span m='1279480'>is</span> <span m='1279790'>the</span>
  <span m='1280220'>head</span> <span m='1280600'>of</span> <span m='1280700'>the</span>
  <span m='1280780'>list,</span> <span m='1281150'>and</span> <span m='1281290'>then</span>
  <span m='1281440'>we</span> <span m='1281560'>do</span> <span m='1281710'>an</span>
  <span m='1281810'>unlock.</span> <span m='1283820'>And</span> <span m='1283950'>now</span>
  <span m='1284140'>we</span> <span m='1284260'>lock</span> <span m='1284580'>it</span>
  <span m='1284650'>again.</span> <span m='1285890'>Now</span> <span m='1286160'>we</span>
  <span m='1286660'>follow</span> <span m='1287100'>the</span> <span m='1287420'>head</span>
  <span m='1288160'>to</span> <span m='1288320'>set</span> <span m='1288900'>x--</span>
  <span m='1289500'>sorry,</span> <span m='1289860'>we</span> <span m='1290180'>set</span>
  <span m='1290380'>x</span> <span m='1290630'>to</span> <span m='1290730'>be</span>
  <span m='1290860'>the</span> <span m='1290980'>head of</span> <span m='1291100'>the</span>
  <span m='1291220'>list</span> <span m='1292190'>and</span> <span m='1292310'>then</span>
  <span m='1292470'>unlock</span> <span m='1292880'>again.</span> </p><p><span m='1293790'>And</span>
  <span m='1293950'>now</span> <span m='1294150'>notice</span> <span m='1294590'>that</span>
  <span m='1294720'>in</span> <span m='1294840'>this</span> <span m='1295030'>case,</span>
  <span m='1295360'>technically,</span> <span m='1295960'>there</span> <span m='1296170'>is</span>
  <span m='1296330'>no</span> <span m='1297160'>data</span> <span m='1297440'>race</span>
  <span m='1299170'>if I</span> <span m='1299500'>have</span> <span m='1299760'>two</span>
  <span m='1300060'>concurrent</span> <span m='1300500'>threads</span> <span m='1300880'>trying</span>
  <span m='1301020'>to</span> <span m='1301160'>access</span> <span m='1301700'>these</span>
  <span m='1301910'>at a</span> <span m='1301990'>time,</span> <span m='1302600'>because</span>
  <span m='1302820'>all</span> <span m='1303090'>the</span> <span m='1303220'>axis</span>
  <span m='1303670'>I'm</span> <span m='1303800'>doing,</span> <span m='1304060'>I'm</span>
  <span m='1304180'>holding</span> <span m='1304560'>lock</span> <span m='1304890'>L.</span>
  <span m='1305970'>Nevertheless,</span> <span m='1306670'>I can</span> <span m='1306810'>get</span>
  <span m='1307030'>that</span> <span m='1307260'>same</span> <span m='1307570'>interleaving</span>
  <span m='1310790'>of</span> <span m='1311000'>code</span> <span m='1312530'>that</span>
  <span m='1312700'>causes</span> <span m='1313190'>the</span> <span m='1313280'>bug.</span>
  <span m='1314610'>So</span> <span m='1314780'>just</span> <span m='1315050'>because</span>
  <span m='1315340'>you</span> <span m='1315450'>don't</span> <span m='1315670'>have</span>
  <span m='1315780'>a</span> <span m='1315890'>data</span> <span m='1316220'>race</span>
  <span m='1317360'>doesn't</span> <span m='1317720'>mean</span> <span m='1318530'>that</span>
  <span m='1318690'>you</span> <span m='1318790'>don't</span> <span m='1318990'>have</span>
  <span m='1319210'>a</span> <span m='1319270'>bug</span> <span m='1319650'>in</span>
  <span m='1319760'>your</span> <span m='1319910'>code.</span> <span m='1321280'>As</span>
  <span m='1321480'>I</span> <span m='1321530'>say,</span> <span m='1321760'>this
  is</span> <span m='1322130'>dangerous</span> <span m='1322500'>programming.</span>
  </p><p><span m='1325580'>However,</span> <span m='1327020'>typically,</span> <span
  m='1327900'>if</span> <span m='1328040'>you</span> <span m='1328250'>have</span>
  <span m='1328460'>mutexes</span> <span m='1329650'>and</span> <span m='1329950'>no</span>
  <span m='1330150'>data</span> <span m='1330490'>races,</span> <span m='1332180'>usually</span>
  <span m='1332610'>it</span> <span m='1332730'>means</span> <span m='1333010'>that</span>
  <span m='1333110'>you</span> <span m='1333220'>went</span> <span m='1333550'>through</span>
  <span m='1333820'>and</span> <span m='1333950'>thought</span> <span m='1334290'>about</span>
  <span m='1334590'>this</span> <span m='1334790'>code.</span> <span m='1335040'>And
  if</span> <span m='1335140'>you</span> <span m='1335230'>were</span> <span m='1335300'>thinking</span>
  <span m='1335610'>about</span> <span m='1335880'>this</span> <span m='1336090'>code,</span>
  <span m='1337610'>you</span> <span m='1337760'>would</span> <span m='1337870'>say,</span>
  <span m='1338200'>gee,</span> <span m='1339530'>really</span> <span m='1339960'>I'm</span>
  <span m='1340080'>trying</span> <span m='1340320'>to</span> <span m='1340370'>make</span>
  <span m='1340990'>these</span> <span m='1341320'>two</span> <span m='1341420'>instructions</span>
  <span m='1342150'>be</span> <span m='1342410'>the</span> <span m='1342520'>critical</span>
  <span m='1342940'>section.</span> <span m='1343400'>Why</span> <span m='1343610'>would</span>
  <span m='1343790'>I</span> <span m='1343910'>unlock</span> <span m='1344180'>and</span>
  <span m='1344450'>lock</span> <span m='1344750'>again?</span> <span m='1346590'>So</span>
  <span m='1346730'>most</span> <span m='1347110'>of</span> <span m='1347200'>the</span>
  <span m='1347290'>time,</span> <span m='1348570'>as</span> <span m='1348670'>a</span>
  <span m='1348780'>practical</span> <span m='1349320'>matter,</span> <span m='1350140'>if</span>
  <span m='1350300'>you</span> <span m='1350410'>don't</span> <span m='1350610'>have</span>
  <span m='1350790'>data</span> <span m='1351090'>races,</span> <span m='1351540'>it</span>
  <span m='1351640'>probably</span> <span m='1352040'>means</span> <span m='1352350'>you</span>
  <span m='1352480'>did</span> <span m='1352640'>the</span> <span m='1352760'>right</span>
  <span m='1353110'>thing</span> <span m='1353430'>in</span> <span m='1353590'>terms</span>
  <span m='1354010'>of</span> <span m='1354550'>identifying</span> <span m='1355210'>the</span>
  <span m='1355310'>critical</span> <span m='1355680'>sections</span> <span m='1356190'>that</span>
  <span m='1356320'>needed</span> <span m='1356570'>to</span> <span m='1356640'>be</span>
  <span m='1356780'>locked</span> <span m='1357550'>and</span> <span m='1357730'>not</span>
  <span m='1357950'>unlocking</span> <span m='1358510'>things</span> <span m='1358830'>in</span>
  <span m='1358910'>the</span> <span m='1358990'>middle</span> <span m='1359250'>of</span>
  <span m='1359350'>them.</span> </p><p><span m='1361330'>So</span> <span m='1361450'>as</span>
  <span m='1361520'>a</span> <span m='1361590'>practical</span> <span m='1362170'>matter,</span>
  <span m='1363290'>no</span> <span m='1363520'>data</span> <span m='1363830'>races</span>
  <span m='1364410'>usually</span> <span m='1364920'>means</span> <span m='1365510'>it's</span>
  <span m='1365710'>unlikely</span> <span m='1366280'>you</span> <span m='1366430'>have</span>
  <span m='1366580'>bugs.</span> <span m='1369910'>But</span> <span m='1370050'>no</span>
  <span m='1370220'>guarantees.</span> <span m='1370860'>As</span> <span m='1371020'>I</span>
  <span m='1371070'>say,</span> <span m='1371290'>dangerous</span> <span m='1371740'>programming.</span>
  <span m='1373330'>Non-deterministic</span> <span m='1374110'>programming</span>
  <span m='1374520'>is</span> <span m='1374660'>dangerous</span> <span m='1375030'>program.</span>
  <span m='1377980'>Any</span> <span m='1378190'>questions</span> <span m='1378620'>about</span>
  <span m='1378830'>that?</span> <span m='1382910'>Anybody</span> <span m='1383350'>scared</span>
  <span m='1383750'>off</span> <span m='1383970'>yet?</span> <span m='1386550'>Yeah?</span>
  </p><p><span m='1387530'>AUDIENCE:</span> <span m='1388020'>So</span> <span m='1388640'>what</span>
  <span m='1388990'>you can</span> <span m='1389350'>do is</span> <span m='1389826'>the
  opposite.</span> <span m='1390778'>You don't</span> <span m='1391254'>have any</span>
  <span m='1391730'>bugs,</span> <span m='1392206'>but you</span> <span m='1392682'>made
  the</span> <span m='1393158'>critical</span> <span m='1393634'>distinction</span>
  <span m='1394110'>to</span> <span m='1394586'>[INAUDIBLE]</span> </p><p><span m='1395070'>PROFESSOR:</span>
  <span m='1395570'>Yes,</span> <span m='1396050'>so certainly</span> <span m='1396450'>from</span>
  <span m='1396640'>a</span> <span m='1397440'>performance</span> <span m='1398050'>point</span>
  <span m='1398260'>of</span> <span m='1398310'>view,</span> <span m='1399220'>one</span>
  <span m='1399450'>of</span> <span m='1399490'>the</span> <span m='1399570'>problems</span>
  <span m='1399970'>with</span> <span m='1400070'>locking</span> <span m='1400550'>is</span>
  <span m='1400680'>that--</span> <span m='1401080'>and</span> <span m='1401250'>we'll</span>
  <span m='1401370'>talk</span> <span m='1401590'>about</span> <span m='1401750'>this
  a</span> <span m='1401900'>little</span> <span m='1402020'>bit</span> <span m='1402130'>later--</span>
  <span m='1402780'>with</span> <span m='1402980'>locking</span> <span m='1403480'>is</span>
  <span m='1403720'>that</span> <span m='1403830'>if</span> <span m='1403930'>you</span>
  <span m='1404110'>have</span> <span m='1404280'>a</span> <span m='1404330'>large</span>
  <span m='1405040'>section</span> <span m='1406070'>that</span> <span m='1406160'>you</span>
  <span m='1406300'>decide</span> <span m='1406680'>to</span> <span m='1406760'>lock,</span>
  <span m='1407180'>it</span> <span m='1407300'>means</span> <span m='1407610'>other</span>
  <span m='1408370'>threads</span> <span m='1408750'>can't</span> <span m='1409490'>do</span>
  <span m='1409640'>work</span> <span m='1410290'>on</span> <span m='1410460'>that</span>
  <span m='1410680'>section.</span> <span m='1411870'>So</span> <span m='1411980'>they're</span>
  <span m='1412160'>spinning,</span> <span m='1412730'>wasting</span> <span m='1413280'>cycles.</span>
  <span m='1414600'>So</span> <span m='1414760'>generally,</span> <span m='1415120'>you</span>
  <span m='1415210'>want</span> <span m='1415380'>to</span> <span m='1415420'>try</span>
  <span m='1415590'>to</span> <span m='1415680'>lock</span> <span m='1416020'>things</span>
  <span m='1416360'>as</span> <span m='1416530'>small</span> <span m='1417440'>as</span>
  <span m='1417620'>possible.</span> </p><p><span m='1418970'>The</span> <span m='1419120'>other</span>
  <span m='1419350'>problem</span> <span m='1419770'>is,</span> <span m='1419920'>it</span>
  <span m='1420030'>turns</span> <span m='1420340'>out</span> <span m='1420530'>that</span>
  <span m='1420650'>there's</span> <span m='1420810'>overhead</span> <span m='1421390'>associated</span>
  <span m='1422000'>with</span> <span m='1422110'>these</span> <span m='1422330'>locks.</span>
  <span m='1424550'>So</span> <span m='1424770'>if</span> <span m='1424860'>there's</span>
  <span m='1425030'>overhead</span> <span m='1425500'>associated</span> <span m='1426000'>with</span>
  <span m='1426090'>the</span> <span m='1426180'>locks,</span> <span m='1427150'>that's</span>
  <span m='1427370'>problematic</span> <span m='1427990'>as</span> <span m='1428130'>well,</span>
  <span m='1429850'>because</span> <span m='1430190'>now</span> <span m='1430450'>you</span>
  <span m='1430610'>may</span> <span m='1430770'>be</span> <span m='1430880'>slowing</span>
  <span m='1431350'>down.</span> <span m='1432180'>If</span> <span m='1432320'>this</span>
  <span m='1432490'>is</span> <span m='1433210'>in</span> <span m='1433780'>an</span>
  <span m='1433970'>inner</span> <span m='1434170'>loop,</span> <span m='1435060'>notice</span>
  <span m='1435400'>that</span> <span m='1435520'>we've</span> <span m='1435650'>now,</span>
  <span m='1436120'>even</span> <span m='1436360'>if</span> <span m='1436460'>I</span>
  <span m='1436560'>just</span> <span m='1436770'>have</span> <span m='1438530'>the</span>
  <span m='1438630'>lock</span> <span m='1438990'>and</span> <span m='1439120'>unlock</span>
  <span m='1439620'>without</span> <span m='1439930'>these</span> <span m='1440150'>two</span>
  <span m='1440430'>spurious</span> <span m='1440950'>ones</span> <span m='1441220'>here,</span>
  <span m='1442310'>we</span> <span m='1442440'>may</span> <span m='1442630'>be</span>
  <span m='1443200'>more</span> <span m='1443410'>than</span> <span m='1443570'>doubling</span>
  <span m='1444010'>the</span> <span m='1444150'>overhead.</span> <span m='1444610'>In</span>
  <span m='1444710'>fact,</span> <span m='1444950'>locking</span> <span m='1445360'>instructions</span>
  <span m='1445880'>tend</span> <span m='1446100'>to</span> <span m='1446170'>be</span>
  <span m='1446330'>much</span> <span m='1446560'>more</span> <span m='1446720'>expensive</span>
  <span m='1447760'>than</span> <span m='1448050'>register</span> <span m='1448540'>operations.</span>
  <span m='1450140'>They</span> <span m='1450250'>usually</span> <span m='1450900'>cost</span>
  <span m='1451200'>something</span> <span m='1451540'>on</span> <span m='1451730'>the</span>
  <span m='1451880'>order</span> <span m='1452230'>of</span> <span m='1452310'>going</span>
  <span m='1452640'>to</span> <span m='1453750'>L2</span> <span m='1454120'>cache</span>
  <span m='1455770'>as</span> <span m='1456010'>a</span> <span m='1456060'>minimum.</span>
  <span m='1458050'>So</span> <span m='1458840'>it's</span> <span m='1458960'>not</span>
  <span m='1459130'>even</span> <span m='1459410'>L1</span> <span m='1459890'>cache.</span>
  <span m='1460210'>It's</span> <span m='1460340'>like</span> <span m='1460470'>going</span>
  <span m='1460710'>out</span> <span m='1460850'>to</span> <span m='1460950'>L2</span>
  <span m='1461290'>cache.</span> </p><p><span m='1464780'>Now,</span> <span m='1465090'>it</span>
  <span m='1465250'>turns</span> <span m='1465490'>out</span> <span m='1465730'>there
  are</span> <span m='1465860'>some</span> <span m='1466190'>times</span> <span m='1466520'>where</span>
  <span m='1467740'>you</span> <span m='1468000'>have</span> <span m='1468260'>data</span>
  <span m='1468530'>races.</span> <span m='1468870'>So</span> <span m='1468980'>we</span>
  <span m='1469080'>say</span> <span m='1469360'>if</span> <span m='1469590'>there</span>
  <span m='1469680'>are</span> <span m='1469720'>no</span> <span m='1470130'>data</span>
  <span m='1470450'>races,</span> <span m='1470950'>then</span> <span m='1471140'>you</span>
  <span m='1471480'>have</span> <span m='1472520'>no</span> <span m='1472720'>guarantee</span>
  <span m='1473120'>there's</span> <span m='1473310'>no</span> <span m='1473480'>bugs.</span>
  <span m='1474540'>If</span> <span m='1474730'>there</span> <span m='1474880'>are</span>
  <span m='1475130'>data</span> <span m='1475470'>races,</span> <span m='1478390'>your</span>
  <span m='1478540'>program</span> <span m='1478930'>still</span> <span m='1479250'>may</span>
  <span m='1479430'>be</span> <span m='1479570'>correct.</span> <span m='1481440'>Here's</span>
  <span m='1481720'>an</span> <span m='1481790'>example</span> <span m='1482300'>of</span>
  <span m='1482410'>a</span> <span m='1482860'>code</span> <span m='1483630'>where</span>
  <span m='1483810'>you</span> <span m='1483940'>might</span> <span m='1484260'>want</span>
  <span m='1484580'>to</span> <span m='1487110'>allow</span> <span m='1488350'>a</span>
  <span m='1488560'>benign</span> <span m='1489120'>data</span> <span m='1489560'>race.</span>
  </p><p><span m='1490460'>So</span> <span m='1490590'>here</span> <span m='1490850'>we</span>
  <span m='1491230'>have,</span> <span m='1491560'>let's</span> <span m='1491800'>say,</span>
  <span m='1491980'>an</span> <span m='1492080'>array</span> <span m='1492490'>A</span>
  <span m='1492880'>that</span> <span m='1492970'>has</span> <span m='1493260'>these</span>
  <span m='1493470'>elements</span> <span m='1493950'>in</span> <span m='1494040'>it.</span>
  <span m='1494930'>And</span> <span m='1495070'>we</span> <span m='1495190'>want</span>
  <span m='1495370'>to</span> <span m='1495420'>find,</span> <span m='1495920'>what</span>
  <span m='1496130'>is</span> <span m='1496370'>the</span> <span m='1496560'>set</span>
  <span m='1496830'>of</span> <span m='1496960'>digits</span> <span m='1497520'>in</span>
  <span m='1497720'>the</span> <span m='1497870'>array?</span> <span m='1499680'>So</span>
  <span m='1499980'>these are</span> <span m='1500110'>all</span> <span m='1500250'>going</span>
  <span m='1500350'>to</span> <span m='1500460'>be</span> <span m='1500560'>values</span>
  <span m='1501120'>between</span> <span m='1501490'>0 and</span> <span m='1501840'>9.</span>
  <span m='1502880'>And</span> <span m='1503010'>I</span> <span m='1503040'>want</span>
  <span m='1503230'>to</span> <span m='1503270'>know</span> <span m='1503420'>which</span>
  <span m='1503640'>ones</span> <span m='1503930'>are</span> <span m='1504030'>present</span>
  <span m='1505070'>of</span> <span m='1505200'>the</span> <span m='1505290'>digits</span>
  <span m='1505680'>0 to 9.</span> <span m='1506230'>Which</span> <span m='1506410'>ones</span>
  <span m='1507080'>are</span> <span m='1507210'>not</span> <span m='1507460'>present?</span>
  </p><p><span m='1509110'>So</span> <span m='1509260'>I</span> <span m='1509330'>can</span>
  <span m='1509500'>write</span> <span m='1509660'>a</span> <span m='1509710'>little</span>
  <span m='1509990'>code</span> <span m='1510280'>for</span> <span m='1510420'>that.</span>
  <span m='1510710'>Let</span> <span m='1510850'>me</span> <span m='1511360'>initialize</span>
  <span m='1511840'>an</span> <span m='1512330'>array</span> <span m='1513200'>called</span>
  <span m='1513520'>&quot;digits&quot;</span> <span m='1514110'>to have</span> <span
  m='1514430'>all-zero</span> <span m='1515670'>entries.</span> <span m='1516900'>And</span>
  <span m='1517090'>now</span> <span m='1517300'>let</span> <span m='1517500'>me</span>
  <span m='1517610'>go</span> <span m='1517860'>through</span> <span m='1521310'>all</span>
  <span m='1521500'>the</span> <span m='1521590'>elements of</span> <span m='1521900'>A</span>
  <span m='1522990'>and</span> <span m='1523440'>set</span> <span m='1524880'>digits</span>
  <span m='1525400'>of</span> <span m='1525690'>whatever</span> <span m='1526050'>the</span>
  <span m='1526170'>digit</span> <span m='1526760'>is</span> <span m='1527130'>to</span>
  <span m='1527240'>be</span> <span m='1527380'>1.</span> <span m='1528790'>So</span>
  <span m='1528980'>set</span> <span m='1529635'>at</span> <span m='1529950'>1</span>
  <span m='1530300'>if</span> <span m='1530730'>that</span> <span m='1530960'>digit</span>
  <span m='1531240'>is</span> <span m='1531390'>present.</span> <span m='1532920'>And</span>
  <span m='1533050'>I</span> <span m='1533100'>can</span> <span m='1533260'>do</span>
  <span m='1533380'>that</span> <span m='1533750'>in</span> <span m='1534060'>parallel,</span>
  <span m='1534640'>even.</span> </p><p><span m='1537880'>So</span> <span m='1538700'>what</span>
  <span m='1538910'>can</span> <span m='1539030'>happen</span> <span m='1539450'>here</span>
  <span m='1539880'>is</span> <span m='1540990'>I</span> <span m='1541140'>can</span>
  <span m='1541290'>have,</span> <span m='1541710'>if</span> <span m='1541870'>I've</span>
  <span m='1542060'>done</span> <span m='1542240'>this</span> <span m='1542390'>in</span>
  <span m='1542500'>parallel,</span> <span m='1543070'>this</span> <span m='1543410'>particular</span>
  <span m='1544090'>update</span> <span m='1545330'>of</span> <span m='1545520'>digits</span>
  <span m='1545990'>of</span> <span m='1546390'>6</span> <span m='1548250'>will</span>
  <span m='1548450'>be</span> <span m='1548580'>set</span> <span m='1548820'>to</span>
  <span m='1548900'>1</span> <span m='1549160'>when</span> <span m='1549440'>this</span>
  <span m='1549680'>one</span> <span m='1549920'>is</span> <span m='1550080'>being</span>
  <span m='1550280'>sent</span> <span m='1550600'>to</span> <span m='1550690'>1.</span>
  <span m='1552170'>Is</span> <span m='1552330'>that</span> <span m='1552530'>a</span>
  <span m='1552580'>problem?</span> <span m='1554060'>In some</span> <span m='1554270'>sense,</span>
  <span m='1554550'>no.</span> <span m='1554850'>They're</span> <span m='1554980'>both</span>
  <span m='1555260'>being</span> <span m='1555470'>set</span> <span m='1555770'>to</span>
  <span m='1555850'>1.</span> <span m='1556090'>Who</span> <span m='1556250'>cares?</span>
  <span m='1558190'>But</span> <span m='1558340'>there</span> <span m='1558530'>is</span>
  <span m='1558650'>a</span> <span m='1558720'>race</span> <span m='1559110'>there.</span>
  <span m='1561370'>There</span> <span m='1561550'>is</span> <span m='1561660'>a</span>
  <span m='1561720'>race,</span> <span m='1562060'>but</span> <span m='1562190'>it's</span>
  <span m='1562350'>a</span> <span m='1562540'>benign</span> <span m='1562920'>race.</span>
  <span m='1564130'>Well,</span> <span m='1564440'>it</span> <span m='1564510'>may</span>
  <span m='1564700'>or</span> <span m='1564790'>may</span> <span m='1564930'>not</span>
  <span m='1565250'>be</span> <span m='1565380'>benign.</span> </p><p><span m='1567370'>So</span>
  <span m='1568200'>there's</span> <span m='1568410'>a</span> <span m='1568470'>gotcha</span>
  <span m='1569020'>on</span> <span m='1569180'>this</span> <span m='1569410'>one.</span>
  <span m='1572030'>So</span> <span m='1572660'>this</span> <span m='1573030'>code</span>
  <span m='1573270'>only</span> <span m='1573480'>works</span> <span m='1573780'>correctly</span>
  <span m='1574340'>if</span> <span m='1574430'>the</span> <span m='1574500'>hardware</span>
  <span m='1575320'>writes</span> <span m='1575680'>the</span> <span m='1575810'>array</span>
  <span m='1576120'>elements</span> <span m='1576570'>atomically.</span> <span m='1579410'>So</span>
  <span m='1580150'>for</span> <span m='1580260'>example,</span> <span m='1580690'>not</span>
  <span m='1580940'>on</span> <span m='1581120'>the</span> <span m='1581520'>x86-64</span>
  <span m='1582610'>architecture</span> <span m='1583140'>we're</span> <span m='1583310'>using.</span>
  <span m='1583740'>But</span> <span m='1583890'>on</span> <span m='1584030'>some</span>
  <span m='1584270'>architectures,</span> <span m='1585410'>you</span> <span m='1585550'>cannot</span>
  <span m='1586050'>write</span> <span m='1586370'>a</span> <span m='1586420'>byte</span>
  <span m='1586760'>value.</span> <span m='1589380'>You</span> <span m='1589500'>cannot</span>
  <span m='1589870'>write</span> <span m='1590070'>a</span> <span m='1590120'>byte</span>
  <span m='1590410'>value</span> <span m='1590800'>as</span> <span m='1590930'>an</span>
  <span m='1591000'>atomic</span> <span m='1591480'>operation.</span> <span m='1592902'>It</span>
  <span m='1593290'>implements</span> <span m='1593880'>a</span> <span m='1594000'>right</span>
  <span m='1594350'>to</span> <span m='1594480'>a</span> <span m='1594740'>byte</span>
  <span m='1595000'>by</span> <span m='1595160'>reading</span> <span m='1595500'>a</span>
  <span m='1595610'>word,</span> <span m='1597040'>masking</span> <span m='1597710'>out</span>
  <span m='1598030'>things,</span> <span m='1598510'>changing</span> <span m='1599020'>the</span>
  <span m='1599110'>field,</span> <span m='1599870'>masking</span> <span m='1600370'>again,</span>
  <span m='1600700'>and</span> <span m='1600840'>then</span> <span m='1601010'>writing</span>
  <span m='1601350'>it</span> <span m='1601450'>back</span> <span m='1601750'>out.</span>
  </p><p><span m='1602720'>So</span> <span m='1602810'>you</span> <span m='1602900'>can</span>
  <span m='1603030'>have</span> <span m='1603310'>a</span> <span m='1603400'>race</span>
  <span m='1603750'>on</span> <span m='1603850'>a</span> <span m='1603900'>byte</span>
  <span m='1604210'>value.</span> <span m='1604650'>In</span> <span m='1604800'>particular,</span>
  <span m='1605450'>even</span> <span m='1605700'>if</span> <span m='1605840'>I</span>
  <span m='1605920'>were</span> <span m='1606030'>going</span> <span m='1606130'>to</span>
  <span m='1606220'>do</span> <span m='1606350'>this</span> <span m='1606590'>with</span>
  <span m='1606800'>bits,</span> <span m='1607510'>I</span> <span m='1607620'>could</span>
  <span m='1607770'>have</span> <span m='1607950'>a</span> <span m='1608100'>race</span>
  <span m='1608460'>on</span> <span m='1608640'>bits,</span> <span m='1611160'>although</span>
  <span m='1611530'>C</span> <span m='1611750'>doesn't</span> <span m='1612030'>let</span>
  <span m='1612190'>me</span> <span m='1612360'>access</span> <span m='1612810'>bits</span>
  <span m='1613070'>directly.</span> <span m='1614870'>The</span> <span m='1615120'>smallest</span>
  <span m='1615710'>unit</span> <span m='1616170'>I</span> <span m='1616250'>can</span>
  <span m='1616410'>access</span> <span m='1617300'>is</span> <span m='1617510'>a</span>
  <span m='1617560'>byte.</span> </p><p><span m='1619670'>So</span> <span m='1619830'>you</span>
  <span m='1620010'>have</span> <span m='1620210'>to</span> <span m='1620730'>worry</span>
  <span m='1621160'>about</span> <span m='1621540'>what's</span> <span m='1621800'>the</span>
  <span m='1621890'>level</span> <span m='1622220'>of</span> <span m='1622310'>atomicity</span>
  <span m='1622970'>provided</span> <span m='1623490'>by</span> <span m='1623660'>your</span>
  <span m='1623890'>architecture?</span> <span m='1624520'>So</span> <span m='1624700'>the</span>
  <span m='1625050'>x86</span> <span m='1625550'>architecture,</span> <span m='1626930'>the</span>
  <span m='1627280'>grain</span> <span m='1627610'>size</span> <span m='1628120'>of</span>
  <span m='1628320'>atomic</span> <span m='1628760'>update</span> <span m='1629290'>is</span>
  <span m='1629470'>you</span> <span m='1629600'>can</span> <span m='1629750'>do</span>
  <span m='1629960'>a</span> <span m='1630020'>single-byte</span> <span m='1630810'>write,</span>
  <span m='1631450'>and</span> <span m='1631590'>it</span> <span m='1631640'>will</span>
  <span m='1631800'>do</span> <span m='1631950'>the</span> <span m='1632040'>right,</span>
  <span m='1632440'>proper</span> <span m='1632810'>thing--</span> <span m='1634370'>do</span>
  <span m='1634490'>the</span> <span m='1634580'>right</span> <span m='1634840'>thing</span>
  <span m='1635150'>on</span> <span m='1635310'>the</span> <span m='1635380'>write.</span>
  <span m='1637020'>So</span> <span m='1637310'>we</span> <span m='1637500'>have</span>
  <span m='1637730'>both</span> <span m='1638080'>things.</span> <span m='1639780'>No</span>
  <span m='1639960'>bugs.</span> <span m='1640740'>No</span> <span m='1641240'>data</span>
  <span m='1641470'>races</span> <span m='1641860'>doesn't</span> <span m='1642140'>mean</span>
  <span m='1642350'>no</span> <span m='1642530'>bugs.</span> <span m='1643370'>Presence</span>
  <span m='1643880'>of</span> <span m='1643970'>data</span> <span m='1644250'>races</span>
  <span m='1644640'>doesn't</span> <span m='1644940'>mean</span> <span m='1645110'>you</span>
  <span m='1645310'>have</span> <span m='1645560'>bugs.</span> <span m='1647090'>But</span>
  <span m='1647320'>generally,</span> <span m='1648820'>they're</span> <span m='1649070'>fairly</span>
  <span m='1649780'>well</span> <span m='1650020'>overlapped.</span> </p><p><span
  m='1651000'>Now,</span> <span m='1651940'>why</span> <span m='1652270'>would</span>
  <span m='1652480'>I</span> <span m='1652560'>not</span> <span m='1652950'>want</span>
  <span m='1653120'>to</span> <span m='1653170'>put</span> <span m='1653450'>in</span>
  <span m='1654430'>a</span> <span m='1654550'>lock</span> <span m='1654910'>and</span>
  <span m='1655040'>unlock</span> <span m='1655460'>here</span> <span m='1658740'>just</span>
  <span m='1658960'>to</span> <span m='1659190'>get</span> <span m='1659370'>rid</span>
  <span m='1659500'>of</span> <span m='1659550'>the</span> <span m='1659660'>race?</span>
  <span m='1661030'>If I</span> <span m='1661180'>run</span> <span m='1661410'>Cilkscreen</span>
  <span m='1662040'>on</span> <span m='1662140'>this,</span> <span m='1662310'>it's</span>
  <span m='1662450'>going</span> <span m='1662560'>to</span> <span m='1662630'>complain.</span>
  <span m='1663230'>It's</span> <span m='1663620'>going to</span> <span m='1663740'>say,</span>
  <span m='1663920'>you've</span> <span m='1663990'>got</span> <span m='1664130'>a</span>
  <span m='1664180'>race</span> <span m='1664480'>here.</span> <span m='1666820'>Why</span>
  <span m='1667060'>would</span> <span m='1667280'>I</span> <span m='1667430'>not</span>
  <span m='1667750'>want</span> <span m='1668030'>to</span> <span m='1668160'>put</span>
  <span m='1668400'>a</span> <span m='1668500'>lock</span> <span m='1668900'>on</span>
  <span m='1669030'>here,</span> <span m='1669260'>for</span> <span m='1669410'>example?</span>
  </p><p><span m='1673758'>AUDIENCE:</span> <span m='1674244'>Because</span> <span
  m='1674730'>then we don't</span> <span m='1675216'>have</span> <span m='1675702'>parallelism</span>
  <span m='1676188'>anymore?</span> </p><p><span m='1677160'>PROFESSOR:</span> <span
  m='1677970'>No,</span> <span m='1678470'>well,</span> <span m='1679080'>I'd</span>
  <span m='1679260'>have</span> <span m='1679420'>parallelism</span> <span m='1679910'>maybe</span>
  <span m='1680250'>up</span> <span m='1680370'>to</span> <span m='1680490'>10,</span>
  <span m='1680870'>for</span> <span m='1681010'>example,</span> <span m='1681620'>right?</span>
  <span m='1683100'>Because</span> <span m='1683350'>I</span> <span m='1683470'>have</span>
  <span m='1683620'>10</span> <span m='1683870'>different</span> <span m='1684200'>things</span>
  <span m='1684480'>that</span> <span m='1684580'>could</span> <span m='1684770'>be</span>
  <span m='1684880'>going</span> <span m='1685180'>on</span> <span m='1685370'>at</span>
  <span m='1685440'>a</span> <span m='1685550'>time.</span> <span m='1686510'>But</span>
  <span m='1687110'>that's</span> <span m='1687720'>one</span> <span m='1687910'>reason.</span>
  <span m='1689290'>That is</span> <span m='1689480'>one</span> <span m='1689640'>reason.</span>
  <span m='1690890'>What's</span> <span m='1691010'>another</span> <span m='1691280'>reason</span>
  <span m='1691580'>why</span> <span m='1691760'>I might</span> <span m='1691990'>not</span>
  <span m='1692160'>want</span> <span m='1692260'>to</span> <span m='1692310'>put</span>
  <span m='1692470'>locks</span> <span m='1692840'>in</span> <span m='1692930'>here?</span>
  </p><p><span m='1694563'>AUDIENCE:</span> <span m='1695034'>[INAUDIBLE]</span> </p><p><span
  m='1698802'>PROFESSOR:</span> <span m='1699280'>It could</span> <span m='1699670'>be
  that</span> <span m='1700040'>all</span> <span m='1700365'>the numbers--</span>
  <span m='1701400'>that's</span> <span m='1701725'>a</span> <span m='1702050'>case</span>
  <span m='1702360'>where it</span> <span m='1702500'>doesn't</span> <span m='1702770'>get
  me</span> <span m='1703020'>much</span> <span m='1703370'>speedup.</span> <span
  m='1704760'>But</span> <span m='1705150'>what's</span> <span m='1705360'>another</span>
  <span m='1705630'>reason</span> <span m='1705920'>I</span> <span m='1705950'>might</span>
  <span m='1706160'>want</span> <span m='1706290'>to do</span> <span m='1706330'>this?</span>
  </p><p><span m='1706680'>AUDIENCE:</span> <span m='1707157'>[INAUDIBLE]</span> </p><p><span
  m='1711927'>PROFESSOR:</span> <span m='1712404'>I</span> <span m='1712890'>think</span>
  <span m='1713040'>you're</span> <span m='1713190'>on</span> <span m='1713260'>the</span>
  <span m='1713330'>right</span> <span m='1713520'>track.</span> <span m='1714990'>Overhead.</span>
  <span m='1715620'>Yeah.</span> <span m='1716370'>Overhead.</span> <span m='1717040'>This</span>
  <span m='1717220'>is</span> <span m='1717370'>my</span> <span m='1717690'>inner</span>
  <span m='1717950'>loop.</span> <span m='1719730'>So</span> <span m='1719980'>if</span>
  <span m='1720070'>I'm</span> <span m='1720230'>locking</span> <span m='1720650'>and</span>
  <span m='1720730'>unlocking,</span> <span m='1721120'>all</span> <span m='1721380'>this</span>
  <span m='1721560'>is</span> <span m='1721710'>doing</span> <span m='1721970'>is</span>
  <span m='1722110'>just</span> <span m='1722340'>doing</span> <span m='1722690'>a</span>
  <span m='1723310'>memory</span> <span m='1723660'>[? dereference ?]</span> <span
  m='1724310'>and an</span> <span m='1724580'>assignment.</span> </p><p><span m='1726670'>And</span>
  <span m='1727010'>that</span> <span m='1727220'>may</span> <span m='1727340'>be</span>
  <span m='1727470'>fairly</span> <span m='1727820'>cheap,</span> <span m='1728130'>whereas</span>
  <span m='1728300'>if</span> <span m='1728410'>I</span> <span m='1728470'>grab</span>
  <span m='1728810'>a</span> <span m='1728850'>lock</span> <span m='1729320'>and</span>
  <span m='1729890'>then</span> <span m='1730170'>release</span> <span m='1730540'>the</span>
  <span m='1730630'>lock,</span> <span m='1731260'>those</span> <span m='1731490'>operations</span>
  <span m='1732740'>may be</span> <span m='1733120'>much,</span> <span m='1733370'>much</span>
  <span m='1733590'>more</span> <span m='1733790'>expensive.</span> <span m='1735810'>So</span>
  <span m='1735960'>I</span> <span m='1736060'>may</span> <span m='1736310'>be</span>
  <span m='1736470'>slowing</span> <span m='1736960'>down</span> <span m='1737720'>the</span>
  <span m='1737930'>execution</span> <span m='1738230'>of</span> <span m='1738530'>this</span>
  <span m='1738720'>loop</span> <span m='1739050'>by</span> <span m='1739830'>more</span>
  <span m='1740110'>than</span> <span m='1740290'>I'm</span> <span m='1740390'>going</span>
  <span m='1740520'>to</span> <span m='1740570'>gain</span> <span m='1740970'>out</span>
  <span m='1741120'>of</span> <span m='1741220'>the</span> <span m='1741260'>parallelism</span>
  <span m='1741770'>of</span> <span m='1743960'>this.</span> <span m='1745860'>So</span>
  <span m='1746250'>I may</span> <span m='1746330'>say,</span> <span m='1746760'>I
  may</span> <span m='1747000'>reason,</span> <span m='1747860'>hey,</span> <span
  m='1748400'>there</span> <span m='1748580'>is</span> <span m='1748730'>a</span>
  <span m='1749210'>good</span> <span m='1749380'>reason</span> <span m='1749810'>why</span>
  <span m='1750310'>not</span> <span m='1751120'>have</span> <span m='1751400'>a</span>
  <span m='1753600'>data</span> <span m='1754020'>race</span> <span m='1754300'>there.</span>
  </p><p><span m='1759280'>So</span> <span m='1759500'>I</span> <span m='1759580'>may</span>
  <span m='1759800'>want</span> <span m='1760010'>to</span> <span m='1760060'>have</span>
  <span m='1760260'>a</span> <span m='1760460'>data</span> <span m='1760770'>race,</span>
  <span m='1761240'>and</span> <span m='1761400'>I</span> <span m='1761440'>may</span>
  <span m='1761590'>want</span> <span m='1761780'>to</span> <span m='1761830'>say</span>
  <span m='1762060'>that's</span> <span m='1762360'>OK.</span> <span m='1763540'>And</span>
  <span m='1763760'>if</span> <span m='1763870'>that</span> <span m='1764070'>happens,</span>
  <span m='1764570'>however,</span> <span m='1764960'>you're</span> <span m='1765110'>now</span>
  <span m='1765320'>going</span> <span m='1765440'>to</span> <span m='1765490'>get</span>
  <span m='1765690'>warnings</span> <span m='1766190'>out</span> <span m='1766330'>of</span>
  <span m='1766400'>Cilkscreen.</span> <span m='1767060'>And</span> <span m='1767210'>I</span>
  <span m='1767300'>generally</span> <span m='1767730'>recommend</span> <span m='1768980'>that</span>
  <span m='1769110'>you</span> <span m='1769250'>have</span> <span m='1769380'>no</span>
  <span m='1769570'>warnings</span> <span m='1770130'>on</span> <span m='1770370'>Cilkscreen</span>
  <span m='1772140'>when</span> <span m='1772330'>you</span> <span m='1772450'>run</span>
  <span m='1772640'>your</span> <span m='1772770'>code.</span> <span m='1773610'>So</span>
  <span m='1775160'>the</span> <span m='1775350'>Cilk</span> <span m='1775610'>environment</span>
  <span m='1776100'>provides</span> <span m='1777330'>a</span> <span m='1777470'>mechanism</span>
  <span m='1777980'>called</span> <span m='1778280'>&quot;fake</span> <span m='1778640'>locks.&quot;</span>
  <span m='1781560'>So a</span> <span m='1781740'>fake</span> <span m='1782100'>lock</span>
  <span m='1782490'>allows</span> <span m='1782970'>you</span> <span m='1783410'>to</span>
  <span m='1784540'>communicate</span> <span m='1784925'>to</span> <span m='1785310'>Cilkscreen</span>
  <span m='1785860'>that</span> <span m='1786010'>a race is</span> <span m='1786430'>intentional.</span>
  </p><p><span m='1787290'>So what</span> <span m='1787530'>you</span> <span m='1787630'>then</span>
  <span m='1787920'>do</span> <span m='1788110'>is</span> <span m='1788220'>you</span>
  <span m='1788320'>put</span> <span m='1788510'>a</span> <span m='1788560'>fake</span>
  <span m='1788960'>lock</span> <span m='1789490'>in</span> <span m='1790020'>around</span>
  <span m='1790570'>this</span> <span m='1791460'>access</span> <span m='1792020'>here.</span>
  <span m='1793260'>And</span> <span m='1793820'>what</span> <span m='1793990'>happens</span>
  <span m='1794540'>is</span> <span m='1794850'>when</span> <span m='1794990'>Cilkscreen</span>
  <span m='1795640'>runs,</span> <span m='1796040'>it</span> <span m='1796190'>says,</span>
  <span m='1796580'>oh,</span> <span m='1796760'>you</span> <span m='1796920'>grabbed</span>
  <span m='1797370'>this</span> <span m='1797570'>lock,</span> <span m='1798660'>so</span>
  <span m='1798800'>I</span> <span m='1798860'>shouldn't</span> <span m='1799170'>report</span>
  <span m='1799530'>a</span> <span m='1799580'>race.</span> <span m='1801760'>But</span>
  <span m='1805870'>during</span> <span m='1806160'>execution,</span> <span m='1806940'>no</span>
  <span m='1807120'>lock</span> <span m='1807490'>is</span> <span m='1807640'>actually</span>
  <span m='1807990'>grabbed,</span> <span m='1808430'>because</span> <span m='1808610'>it's</span>
  <span m='1808760'>a</span> <span m='1808810'>fake</span> <span m='1809100'>one.</span>
  <span m='1810000'>So</span> <span m='1810150'>it</span> <span m='1810250'>doesn't</span>
  <span m='1810580'>slow</span> <span m='1810850'>you</span> <span m='1811010'>down</span>
  <span m='1811350'>it</span> <span m='1811460'>all</span> <span m='1811800'>at</span>
  <span m='1811930'>runtime,</span> <span m='1814530'>but</span> <span m='1814900'>Cilkscreen</span>
  <span m='1815470'>still</span> <span m='1815780'>thinks</span> <span m='1816100'>that</span>
  <span m='1816280'>a</span> <span m='1816360'>lock</span> <span m='1816660'>is</span>
  <span m='1816800'>being</span> <span m='1817020'>acquired.</span> </p><p><span m='1818970'>Questions</span>
  <span m='1819440'>about</span> <span m='1819660'>that?</span> <span m='1821160'>So</span>
  <span m='1821310'>this</span> <span m='1821470'>is</span> <span m='1821640'>if</span>
  <span m='1821810'>you</span> <span m='1821950'>want</span> <span m='1822150'>to</span>
  <span m='1822270'>have</span> <span m='1822400'>an</span> <span m='1822470'>intentional</span>
  <span m='1823000'>race,</span> <span m='1824600'>this</span> <span m='1824840'>is</span>
  <span m='1825000'>a</span> <span m='1825050'>way</span> <span m='1825310'>you</span>
  <span m='1825460'>can</span> <span m='1825620'>quiet</span> <span m='1826030'>Cilkscreen.</span>
  <span m='1826200'>Of course,</span> <span m='1826530'>it's</span> <span m='1826910'>dangerous,</span>
  <span m='1827400'>right?</span> <span m='1828360'>It's</span> <span m='1828500'>yet</span>
  <span m='1828840'>another</span> <span m='1829190'>example</span> <span m='1829780'>of</span>
  <span m='1830050'>what's</span> <span m='1830470'>dangerous</span> <span m='1830920'>here.</span>
  <span m='1831610'>Because</span> <span m='1831910'>what</span> <span m='1832070'>happens</span>
  <span m='1832460'>if</span> <span m='1832580'>you</span> <span m='1832690'>did</span>
  <span m='1832830'>it</span> <span m='1832930'>wrong?</span> <span m='1833150'>What</span>
  <span m='1833250'>happens</span> <span m='1833490'>if</span> <span m='1833610'>there</span>
  <span m='1833770'>really</span> <span m='1834070'>is</span> <span m='1834210'>a
  bug</span> <span m='1834570'>there?</span> </p><p><span m='1835350'>You're</span>
  <span m='1835500'>now</span> <span m='1835700'>telling</span> <span m='1836090'>it</span>
  <span m='1836220'>to</span> <span m='1836340'>ignore</span> <span m='1836660'>that</span>
  <span m='1836930'>bug.</span> <span m='1838080'>So</span> <span m='1838260'>one</span>
  <span m='1838460'>way</span> <span m='1838730'>that</span> <span m='1838900'>you</span>
  <span m='1839040'>can</span> <span m='1839690'>make</span> <span m='1839960'>your</span>
  <span m='1840100'>code--</span> <span m='1841960'>if</span> <span m='1842230'>you</span>
  <span m='1842330'>put</span> <span m='1842490'>in</span> <span m='1842620'>fake</span>
  <span m='1842870'>locks</span> <span m='1843200'>everywhere,</span> <span m='1844050'>you</span>
  <span m='1844240'>could</span> <span m='1844390'>make</span> <span m='1844590'>it</span>
  <span m='1844720'>so,</span> <span m='1845450'>oh,</span> <span m='1845570'>Cilkscreen</span>
  <span m='1845850'>runs</span> <span m='1846080'>just</span> <span m='1846290'>great,</span>
  <span m='1847110'>and</span> <span m='1847180'>have</span> <span m='1847360'>your</span>
  <span m='1847490'>code</span> <span m='1847700'>full</span> <span m='1848010'>of</span>
  <span m='1848110'>race</span> <span m='1848370'>bugs.</span> <span m='1851400'>So</span>
  <span m='1851990'>if</span> <span m='1852120'>you</span> <span m='1852220'>use</span>
  <span m='1852520'>fake</span> <span m='1852760'>locks,</span> <span m='1853360'>you</span>
  <span m='1853480'>should</span> <span m='1853650'>document</span> <span m='1854110'>very</span>
  <span m='1854360'>carefully</span> <span m='1856020'>that</span> <span m='1856190'>you're</span>
  <span m='1856310'>doing</span> <span m='1856630'>so</span> <span m='1857140'>and</span>
  <span m='1857460'>why</span> <span m='1857770'>that's</span> <span m='1858070'>going</span>
  <span m='1858170'>to</span> <span m='1858210'>be</span> <span m='1858340'>a</span>
  <span m='1858390'>safe</span> <span m='1859340'>thing</span> <span m='1859600'>to</span>
  <span m='1859700'>do.</span> <span m='1862160'>Any</span> <span m='1862350'>questions</span>
  <span m='1862810'>about</span> <span m='1863070'>that?</span> </p><p><span m='1867676'>By</span>
  <span m='1868070'>the way,</span> <span m='1868260'>one</span> <span m='1868490'>of</span>
  <span m='1868570'>the</span> <span m='1868670'>nice</span> <span m='1869030'>things</span>
  <span m='1869480'>about</span> <span m='1870480'>some</span> <span m='1870730'>of</span>
  <span m='1870770'>the</span> <span m='1870860'>concurrency</span> <span m='1871410'>platforms</span>
  <span m='1872130'>like</span> <span m='1872770'>Cilk</span> <span m='1873360'>is</span>
  <span m='1873620'>that</span> <span m='1873820'>they</span> <span m='1874170'>provide</span>
  <span m='1875140'>a</span> <span m='1875240'>layer</span> <span m='1875450'>of</span>
  <span m='1875540'>abstraction</span> <span m='1876160'>where</span> <span m='1876450'>generally,</span>
  <span m='1877020'>you</span> <span m='1877200'>don't</span> <span m='1877420'>have</span>
  <span m='1877720'>to</span> <span m='1877830'>do</span> <span m='1878070'>very</span>
  <span m='1878330'>much</span> <span m='1878600'>locking.</span> <span m='1879180'>If</span>
  <span m='1879660'>you</span> <span m='1879790'>program</span> <span m='1880230'>with</span>
  <span m='1880410'>Pthreads,</span> <span m='1881100'>for</span> <span m='1881220'>example,</span>
  <span m='1882040'>you're</span> <span m='1882180'>locking</span> <span m='1882670'>all</span>
  <span m='1882900'>the</span> <span m='1883000'>time.</span> <span m='1884660'>So</span>
  <span m='1884780'>you're</span> <span m='1885010'>writing</span> <span m='1885360'>non-deterministic</span>
  <span m='1886260'>programs</span> <span m='1886750'>all</span> <span m='1886990'>the</span>
  <span m='1887080'>time,</span> <span m='1887670'>and</span> <span m='1887790'>you're</span>
  <span m='1887920'>debugging</span> <span m='1888660'>non-deterministic</span> <span
  m='1889500'>programs</span> <span m='1890030'>all</span> <span m='1890140'>the</span>
  <span m='1890260'>time.</span> <span m='1891340'>Whereas</span> <span m='1891765'>Cilk</span>
  <span m='1892020'>provides</span> <span m='1892450'>a</span> <span m='1892510'>layer</span>
  <span m='1893250'>of</span> <span m='1893370'>programming</span> <span m='1893900'>where
  you</span> <span m='1894090'>can</span> <span m='1894230'>do</span> <span m='1894340'>most</span>
  <span m='1894630'>of</span> <span m='1894920'>your</span> <span m='1895090'>programming</span>
  <span m='1896170'>in</span> <span m='1896490'>a</span> <span m='1896770'>deterministic</span>
  <span m='1897500'>fashion.</span> </p><p><span m='1898040'>And</span> <span m='1898200'>occasionally,</span>
  <span m='1899620'>you</span> <span m='1899760'>may</span> <span m='1899990'>want</span>
  <span m='1900220'>to</span> <span m='1900400'>have</span> <span m='1900590'>some</span>
  <span m='1900800'>non-determinism</span> <span m='1902420'>here</span> <span m='1902700'>or</span>
  <span m='1902750'>there.</span> <span m='1903020'>But</span> <span m='1903500'>hopefully</span>
  <span m='1903910'>you</span> <span m='1904010'>can</span> <span m='1904150'>manage</span>
  <span m='1904500'>that</span> <span m='1906340'>if</span> <span m='1906780'>you</span>
  <span m='1906880'>do</span> <span m='1907000'>it</span> <span m='1907120'>judiciously.</span>
  <span m='1909580'>Any</span> <span m='1909840'>questions</span> <span m='1910970'>about</span>
  <span m='1912250'>mutexes</span> <span m='1913050'>and</span> <span m='1913290'>uses</span>
  <span m='1913670'>for</span> <span m='1913910'>them</span> <span m='1914200'>and</span>
  <span m='1914685'>so</span> <span m='1915170'>forth?</span> <span m='1916140'>Good.</span>
  </p><p><span m='1917880'>So</span> <span m='1918000'>let's</span> <span m='1918160'>talk</span>
  <span m='1918380'>about</span> <span m='1918580'>how</span> <span m='1918750'>they</span>
  <span m='1918860'>get</span> <span m='1919030'>implemented.</span> <span m='1919920'>Because</span>
  <span m='1920610'>as</span> <span m='1920880'>with</span> <span m='1921010'>all</span>
  <span m='1921210'>these</span> <span m='1921400'>things,</span> <span m='1921610'>we</span>
  <span m='1921680'>want</span> <span m='1921890'>to</span> <span m='1921930'>understand</span>
  <span m='1922900'>not</span> <span m='1923080'>just</span> <span m='1923310'>what</span>
  <span m='1923470'>the</span> <span m='1923580'>abstractions</span> <span m='1924160'>is</span>
  <span m='1924860'>but</span> <span m='1925000'>how</span> <span m='1925320'>it</span>
  <span m='1925400'>is</span> <span m='1925720'>that</span> <span m='1925850'>you</span>
  <span m='1925990'>actually</span> <span m='1928080'>implement</span> <span m='1928640'>these</span>
  <span m='1928890'>things</span> <span m='1929160'>so</span> <span m='1929260'>that</span>
  <span m='1929370'>you</span> <span m='1929660'>can</span> <span m='1929960'>reason</span>
  <span m='1930280'>about</span> <span m='1930610'>them</span> <span m='1931610'>more</span>
  <span m='1931920'>cogently.</span> <span m='1934510'>So</span> <span m='1936890'>there's</span>
  <span m='1937100'>typically</span> <span m='1937560'>three</span> <span m='1937980'>major</span>
  <span m='1938400'>properties</span> <span m='1939090'>of</span> <span m='1939200'>mutexes</span>
  <span m='1939900'>when</span> <span m='1940060'>you</span> <span m='1940190'>look</span>
  <span m='1940350'>at</span> <span m='1940510'>them.</span> </p><p><span m='1940810'>And</span>
  <span m='1940890'>when</span> <span m='1941010'>you</span> <span m='1941130'>see</span>
  <span m='1941340'>documentation</span> <span m='1942110'>for</span> <span m='1942260'>mutexes,</span>
  <span m='1943290'>you</span> <span m='1943400'>should</span> <span m='1943580'>understand</span>
  <span m='1944230'>what</span> <span m='1944390'>the</span> <span m='1944470'>difference
  is</span> <span m='1945200'>of</span> <span m='1945500'>these</span> <span m='1946120'>things.</span>
  <span m='1946740'>The</span> <span m='1946860'>first</span> <span m='1947240'>is</span>
  <span m='1947380'>whether</span> <span m='1947670'>it's</span> <span m='1947820'>a</span>
  <span m='1947920'>yielding</span> <span m='1948520'>mutex</span> <span m='1949080'>or</span>
  <span m='1949260'>a</span> <span m='1949330'>spinning</span> <span m='1949860'>mutex.</span>
  <span m='1951850'>So</span> <span m='1952000'>a</span> <span m='1952290'>yielding</span>
  <span m='1952830'>mutex,</span> <span m='1953320'>when</span> <span m='1953690'>you</span>
  <span m='1953900'>spin,</span> <span m='1954960'>it</span> <span m='1955100'>returns</span>
  <span m='1955600'>control</span> <span m='1956090'>to</span> <span m='1956190'>the</span>
  <span m='1956310'>operating</span> <span m='1956780'>system.</span> <span m='1957700'>And</span>
  <span m='1957840'>why</span> <span m='1958310'>might</span> <span m='1958520'>you</span>
  <span m='1958630'>want</span> <span m='1958820'>to</span> <span m='1958880'>do</span>
  <span m='1959040'>that?</span> <span m='1960170'>Whereas</span> <span m='1960310'>a</span>
  <span m='1960370'>spinning</span> <span m='1960820'>one</span> <span m='1961540'>just</span>
  <span m='1961970'>consumes</span> <span m='1962470'>processor</span> <span m='1963000'>cycles.</span>
  <span m='1963700'>Why</span> <span m='1963930'>would</span> <span m='1964040'>you</span>
  <span m='1964150'>want</span> <span m='1964290'>to</span> <span m='1964360'>do</span>
  <span m='1964500'>that?</span> <span m='1967926'>Yeah.</span> </p><p><span m='1968412'>AUDIENCE:</span>
  <span m='1968898'>[INAUDIBLE]</span> <span m='1969384'>allow other</span> <span
  m='1969870'>threads.</span> </p><p><span m='1970360'>PROFESSOR:</span> <span m='1970730'>Yeah,</span>
  <span m='1970820'>it can allow</span> <span m='1971170'>other</span> <span m='1971440'>threads</span>
  <span m='1971860'>or</span> <span m='1971970'>other</span> <span m='1972140'>jobs</span>
  <span m='1973090'>that</span> <span m='1973220'>could</span> <span m='1973380'>be</span>
  <span m='1973510'>running</span> <span m='1973850'>to</span> <span m='1973970'>use</span>
  <span m='1974330'>the</span> <span m='1974390'>processor</span> <span m='1976180'>while</span>
  <span m='1976440'>you're</span> <span m='1976570'>waiting.</span> <span m='1977010'>What's</span>
  <span m='1977230'>the</span> <span m='1977330'>downside</span> <span m='1977990'>of</span>
  <span m='1978060'>that?</span> <span m='1980830'>To</span> <span m='1980940'>speak</span>
  <span m='1981170'>to</span> <span m='1981290'>the--</span> <span m='1981790'>either</span>
  <span m='1982000'>one.</span> <span m='1982290'>Go ahead.</span> </p><p><span m='1983787'>AUDIENCE:</span>
  <span m='1984286'>It</span> <span m='1984785'>might</span> <span m='1985284'>be</span>
  <span m='1985783'>possible</span> <span m='1986282'>that</span> <span m='1986781'>whatever</span>
  <span m='1987280'>you're trying</span> <span m='1987779'>to do is</span> <span m='1988278'>essential,</span>
  <span m='1988777'>and you</span> <span m='1989775'>really</span> <span m='1990274'>want</span>
  <span m='1990773'>to get</span> <span m='1991272'>that done</span> <span m='1991771'>[UNINTELLIGIBLE]</span>
  <span m='1992270'>everything else</span> <span m='1992769'>executes.</span> <span
  m='1993268'>So you really want</span> <span m='1993770'>[INAUDIBLE]</span> </p><p><span
  m='1994250'>PROFESSOR:</span> <span m='1994290'>Yeah,</span> <span m='1995760'>context</span>
  <span m='1996350'>switching</span> <span m='1998550'>a</span> <span m='1998620'>thread</span>
  <span m='1998950'>out</span> <span m='1999250'>is</span> <span m='1999450'>a</span>
  <span m='1999760'>heavyweight</span> <span m='2000340'>operation.</span> <span m='2002100'>And</span>
  <span m='2002270'>It</span> <span m='2002370'>may</span> <span m='2002580'>be,</span>
  <span m='2002840'>if</span> <span m='2002970'>you</span> <span m='2003130'>end</span>
  <span m='2003340'>up</span> <span m='2003460'>context</span> <span m='2003860'>switching</span>
  <span m='2004200'>out,</span> <span m='2004700'>it</span> <span m='2004840'>may</span>
  <span m='2005010'>be you</span> <span m='2005240'>only</span> <span m='2005520'>had</span>
  <span m='2005720'>to</span> <span m='2005810'>wait</span> <span m='2006530'>for</span>
  <span m='2007630'>a</span> <span m='2007960'>half</span> <span m='2008190'>a</span>
  <span m='2008260'>dozen</span> <span m='2008550'>cycles</span> <span m='2009080'>and</span>
  <span m='2009160'>you'd</span> <span m='2009290'>have</span> <span m='2009530'>the</span>
  <span m='2009620'>lock.</span> <span m='2010480'>But</span> <span m='2010540'>instead,</span>
  <span m='2011730'>now</span> <span m='2011950'>you're</span> <span m='2012110'>going</span>
  <span m='2012540'>and</span> <span m='2012760'>you're</span> <span m='2012870'>doing</span>
  <span m='2013110'>a</span> <span m='2013180'>context</span> <span m='2013700'>switch</span>
  <span m='2014330'>and</span> <span m='2014500'>may</span> <span m='2014610'>not</span>
  <span m='2014860'>get</span> <span m='2014990'>access</span> <span m='2015380'>to</span>
  <span m='2015470'>the</span> <span m='2015530'>machine</span> <span m='2015910'>for</span>
  <span m='2016030'>another</span> <span m='2016250'>hundredth</span> <span m='2016640'>of</span>
  <span m='2016750'>a</span> <span m='2016800'>second</span> <span m='2017190'>or</span>
  <span m='2017280'>something.</span> <span m='2018750'>So</span> <span m='2019070'>it</span>
  <span m='2019390'>may be</span> <span m='2019840'>on</span> <span m='2019950'>the</span>
  <span m='2020070'>order</span> <span m='2020500'>of</span> <span m='2021590'>10</span>
  <span m='2021830'>to</span> <span m='2021940'>the</span> <span m='2022030'>6th--</span>
  <span m='2022440'>a</span> <span m='2022660'>million</span> <span m='2023640'>instructions</span>
  <span m='2024310'>before</span> <span m='2024620'>you</span> <span m='2024750'>get</span>
  <span m='2024870'>access</span> <span m='2025340'>again,</span> <span m='2025660'>rather</span>
  <span m='2026010'>than</span> <span m='2027680'>just</span> <span m='2027930'>a</span>
  <span m='2027970'>few.</span> </p><p><span m='2029500'>The</span> <span m='2029560'>second</span>
  <span m='2030300'>property</span> <span m='2030810'>of</span> <span m='2031010'>mutexes</span>
  <span m='2031920'>is</span> <span m='2034110'>whether</span> <span m='2034360'>they're</span>
  <span m='2034520'>reentrant</span> <span m='2035140'>or</span> <span m='2035220'>not.</span>
  <span m='2036850'>So a</span> <span m='2037090'>reenttrant</span> <span m='2037740'>mutex</span>
  <span m='2039000'>allows</span> <span m='2039530'>a</span> <span m='2039610'>thread</span>
  <span m='2040760'>that's</span> <span m='2040940'>holding</span> <span m='2041340'>a</span>
  <span m='2041400'>lock</span> <span m='2042550'>to</span> <span m='2042690'>acquire
  it</span> <span m='2043240'>again.</span> <span m='2045340'>So</span> <span m='2045500'>I</span>
  <span m='2045660'>may</span> <span m='2045830'>hold</span> <span m='2045950'>the</span>
  <span m='2046080'>lock,</span> <span m='2046410'>and</span> <span m='2046510'>then</span>
  <span m='2046650'>I</span> <span m='2046700'>may</span> <span m='2046930'>try</span>
  <span m='2047160'>to</span> <span m='2047270'>acquire</span> <span m='2047710'>the</span>
  <span m='2048219'>lock</span> <span m='2048520'>again.</span> <span m='2050570'>Java</span>
  <span m='2051610'>is</span> <span m='2051870'>full</span> <span m='2052440'>of</span>
  <span m='2052679'>reentrant</span> <span m='2055000'>locks,</span> <span m='2056020'>reentrant</span>
  <span m='2056449'>mutexes.</span> </p><p><span m='2059139'>So</span> <span m='2059310'>why</span>
  <span m='2059580'>is</span> <span m='2059770'>this</span> <span m='2060020'>a</span>
  <span m='2060340'>positive</span> <span m='2061000'>or</span> <span m='2061120'>negative?</span>
  <span m='2062530'>What</span> <span m='2062659'>are</span> <span m='2062710'>the</span>
  <span m='2062800'>pros</span> <span m='2063100'>and</span> <span m='2063190'>cons</span>
  <span m='2063489'>of</span> <span m='2063570'>this</span> <span m='2063739'>one?</span>
  <span m='2066130'>Why</span> <span m='2066389'>might</span> <span m='2066760'>reentrancy</span>
  <span m='2067320'>be</span> <span m='2067449'>a</span> <span m='2067500'>good</span>
  <span m='2067699'>thing</span> <span m='2069090'>to</span> <span m='2069219'>want?</span>
  <span m='2074690'>Why</span> <span m='2074909'>would</span> <span m='2075060'>I</span>
  <span m='2075130'>bother</span> <span m='2075449'>doing--</span> <span m='2078190'>why</span>
  <span m='2078330'>would</span> <span m='2078469'>I</span> <span m='2078520'>grab</span>
  <span m='2078860'>a</span> <span m='2078900'>lock</span> <span m='2079190'>that
  I</span> <span m='2079290'>already</span> <span m='2079610'>have?</span> </p><p><span
  m='2082043'>AUDIENCE:</span> <span m='2082519'>It'd be too easy</span> <span m='2082995'>to
  do</span> <span m='2083471'>a</span> <span m='2083947'>check</span> <span m='2084423'>[INAUDIBLE].</span>
  </p><p><span m='2085375'>PROFESSOR:</span> <span m='2085860'>It lets</span> <span
  m='2086100'>you do</span> <span m='2086300'>what?</span> </p><p><span m='2086739'>AUDIENCE:</span>
  <span m='2087179'>It lets</span> <span m='2087629'>you not</span> <span m='2088079'>have
  to</span> <span m='2088529'>worry about</span> <span m='2088979'>locking</span>
  <span m='2089429'>when you already have a lock.</span> </p><p><span m='2089804'>PROFESSOR:</span>
  <span m='2090179'>It lets you</span> <span m='2090469'>not</span> <span m='2090730'>worry</span>
  <span m='2090960'>about</span> <span m='2091409'>it.</span> <span m='2091610'>That's
  right.</span> <span m='2092000'>But</span> <span m='2092120'>why</span> <span m='2092320'>is</span>
  <span m='2092449'>that</span> <span m='2092670'>valuable?</span> </p><p><span m='2092944'>AUDIENCE:</span>
  <span m='2093219'>It saves you</span> <span m='2093704'>one line in</span> <span
  m='2094189'>an If statment</span> <span m='2094674'>to</span> <span m='2095159'>check
  if</span> <span m='2095644'>you have a</span> <span m='2096129'>lock or</span> <span
  m='2096614'>not.</span> </p><p><span m='2098069'>PROFESSOR:</span> <span m='2098554'>That</span>
  <span m='2099050'>could</span> <span m='2099250'>be.</span> <span m='2099640'>Basically,</span>
  <span m='2099920'>the</span> <span m='2100200'>If</span> <span m='2100330'>statement
  is</span> <span m='2100790'>embedded</span> <span m='2101220'>in</span> <span m='2101350'>there.</span>
  <span m='2102320'>But</span> <span m='2102450'>why</span> <span m='2102610'>would</span>
  <span m='2102780'>I</span> <span m='2102840'>care?</span> <span m='2103130'>Why</span>
  <span m='2103330'>would</span> <span m='2103510'>I</span> <span m='2103580'>want</span>
  <span m='2103830'>to</span> <span m='2104080'>be</span> <span m='2104250'>acquiring</span>
  <span m='2104830'>something</span> <span m='2105190'>that I</span> <span m='2105320'>already</span>
  <span m='2105710'>have?</span> <span m='2109410'>In</span> <span m='2109600'>what</span>
  <span m='2109820'>programming</span> <span m='2110240'>situation</span> <span m='2110850'>might</span>
  <span m='2111020'>that</span> <span m='2111260'>arise?</span> <span m='2112600'>This</span>
  <span m='2112680'>seems</span> <span m='2112920'>kind</span> <span m='2113070'>of</span>
  <span m='2113140'>weird,</span> <span m='2113460'>right?</span> <span m='2115510'>Could</span>
  <span m='2115680'>be</span> <span m='2115850'>recursion.</span> <span m='2116970'>Yeah.</span>
  </p><p><span m='2117890'>So</span> <span m='2118080'>usually,</span> <span m='2118650'>what</span>
  <span m='2118800'>it</span> <span m='2119060'>comes</span> <span m='2119310'>from</span>
  <span m='2119570'>is</span> <span m='2119830'>when</span> <span m='2119960'>you</span>
  <span m='2120090'>have</span> <span m='2120230'>objects,</span> <span m='2120800'>and</span>
  <span m='2120880'>you</span> <span m='2120950'>have</span> <span m='2121050'>several</span>
  <span m='2121430'>methods</span> <span m='2121930'>on</span> <span m='2122060'>the</span>
  <span m='2122190'>object.</span> <span m='2123480'>And</span> <span m='2124310'>what</span>
  <span m='2124490'>you'd</span> <span m='2124630'>like</span> <span m='2124880'>to</span>
  <span m='2125000'>do</span> <span m='2125310'>is,</span> <span m='2125650'>if</span>
  <span m='2125730'>somebody's</span> <span m='2126120'>calling</span> <span m='2126930'>the</span>
  <span m='2127070'>method</span> <span m='2127620'>from</span> <span m='2127780'>the</span>
  <span m='2127900'>outside,</span> <span m='2131520'>you</span> <span m='2131710'>would</span>
  <span m='2131820'>like</span> <span m='2132190'>to</span> <span m='2132780'>be</span>
  <span m='2132940'>able</span> <span m='2133200'>to</span> <span m='2133440'>execute</span>
  <span m='2134350'>that</span> <span m='2134810'>particular--</span> <span m='2135680'>I
  guess</span> <span m='2135960'>in</span> <span m='2136140'>C++</span> <span m='2136590'>they
  don't</span> <span m='2136780'>call</span> <span m='2136950'>them</span> <span m='2137030'>&quot;methods.&quot;</span>
  <span m='2137430'>They</span> <span m='2137530'>call</span> <span m='2137800'>them</span>
  <span m='2141650'>&quot;member</span> <span m='2141910'>functions.&quot;</span>
  <span m='2142450'>&quot;Member</span> <span m='2142730'>functions,&quot;</span>
  <span m='2143150'>they</span> <span m='2143260'>call them.</span> <span m='2143940'>In</span>
  <span m='2144050'>Java,</span> <span m='2144350'>they</span> <span m='2144500'>call</span>
  <span m='2144730'>them</span> <span m='2144800'>&quot;methods,&quot;</span> <span
  m='2145260'>and</span> <span m='2145480'>in</span> <span m='2145740'>C++,</span>
  <span m='2146320'>they</span> <span m='2146430'>call</span> <span m='2146620'>them</span>
  <span m='2146700'>&quot;member</span> <span m='2147020'>functions.&quot;</span>
  <span m='2148500'>Doesn't</span> <span m='2148760'>matter.</span> <span m='2149020'>It's</span>
  <span m='2149130'>the</span> <span m='2149200'>same</span> <span m='2149490'>thing.</span>
  </p><p><span m='2150700'>So</span> <span m='2150870'>when</span> <span m='2150950'>you</span>
  <span m='2151030'>access</span> <span m='2151550'>one</span> <span m='2151810'>of</span>
  <span m='2151880'>these,</span> <span m='2152110'>normally,</span> <span m='2152405'>from</span>
  <span m='2152700'>the</span> <span m='2152840'>outside,</span> <span m='2153460'>you</span>
  <span m='2153550'>want</span> <span m='2153660'>to</span> <span m='2153700'>make</span>
  <span m='2153850'>sure</span> <span m='2153980'>you</span> <span m='2154080'>grab</span>
  <span m='2154410'>the</span> <span m='2154510'>lock</span> <span m='2155310'>associated</span>
  <span m='2155940'>with</span> <span m='2156090'>the</span> <span m='2156230'>object.</span>
  <span m='2157380'>However,</span> <span m='2157730'>it</span> <span m='2157800'>may</span>
  <span m='2158020'>be</span> <span m='2158240'>that</span> <span m='2158510'>what</span>
  <span m='2158730'>you're</span> <span m='2158860'>doing</span> <span m='2159720'>inside</span>
  <span m='2160260'>the</span> <span m='2160380'>object</span> <span m='2160760'>is</span>
  <span m='2160850'>you</span> <span m='2160970'>want</span> <span m='2161190'>to</span>
  <span m='2161250'>be</span> <span m='2161430'>able--</span> <span m='2161880'>one</span>
  <span m='2162170'>of</span> <span m='2162250'>the</span> <span m='2162760'>operations</span>
  <span m='2163470'>may be</span> <span m='2163840'>a</span> <span m='2163890'>more</span>
  <span m='2164130'>complex</span> <span m='2164720'>operation</span> <span m='2165590'>that</span>
  <span m='2165720'>wants</span> <span m='2166010'>to</span> <span m='2166100'>use</span>
  <span m='2168090'>one</span> <span m='2168360'>of</span> <span m='2168450'>its</span>
  <span m='2168650'>own</span> <span m='2168970'>implementations.</span> <span m='2169840'>So</span>
  <span m='2169950'>rather</span> <span m='2170270'>than</span> <span m='2170410'>implementing</span>
  <span m='2170980'>it</span> <span m='2171100'>twice--</span> <span m='2171650'>once</span>
  <span m='2171980'>in</span> <span m='2172090'>the</span> <span m='2172150'>locked</span>
  <span m='2172500'>form,</span> <span m='2173070'>once</span> <span m='2173450'>without</span>
  <span m='2173890'>getting</span> <span m='2174180'>the</span> <span m='2174250'>lock--</span>
  <span m='2176560'>you</span> <span m='2176680'>just</span> <span m='2177090'>implement</span>
  <span m='2177490'>it</span> <span m='2177620'>once,</span> <span m='2178070'>and</span>
  <span m='2178520'>you</span> <span m='2178650'>use</span> <span m='2178920'>reentrant</span>
  <span m='2179410'>locks.</span> <span m='2179970'>And</span> <span m='2180140'>that</span>
  <span m='2180360'>way,</span> <span m='2180600'>you</span> <span m='2180750'>don't</span>
  <span m='2180910'>have</span> <span m='2181070'>to</span> <span m='2181180'>worry</span>
  <span m='2181540'>about,</span> <span m='2183160'>in</span> <span m='2183370'>coding</span>
  <span m='2183690'>those</span> <span m='2183900'>things,</span> <span m='2184150'>whether</span>
  <span m='2184430'>or</span> <span m='2184490'>not</span> <span m='2184770'>you've</span>
  <span m='2184950'>already</span> <span m='2185160'>got</span> <span m='2185410'>it.</span>
  <span m='2186840'>So</span> <span m='2186970'>that's</span> <span m='2187440'>probably</span>
  <span m='2187690'>the</span> <span m='2187790'>most</span> <span m='2188050'>common</span>
  <span m='2188760'>place</span> <span m='2189040'>that</span> <span m='2189150'>I</span>
  <span m='2189250'>know</span> <span m='2189430'>that</span> <span m='2189570'>people</span>
  <span m='2189840'>want</span> <span m='2190090'>reentrant</span> <span m='2190460'>locks.</span>
  </p><p><span m='2191040'>Naturally,</span> <span m='2191550'>to</span> <span m='2191960'>acquire
  a</span> <span m='2192390'>reentrant</span> <span m='2192820'>lock,</span> <span
  m='2194830'>you</span> <span m='2194960'>have</span> <span m='2195150'>to</span>
  <span m='2195270'>do</span> <span m='2195420'>some</span> <span m='2195640'>kind</span>
  <span m='2195850'>of</span> <span m='2196200'>If</span> <span m='2196360'>statement,</span>
  <span m='2196840'>which</span> <span m='2196990'>is</span> <span m='2197120'>a</span>
  <span m='2197180'>conditional.</span> <span m='2197880'>And</span> <span m='2197960'>as</span>
  <span m='2198070'>you know,</span> <span m='2198910'>if</span> <span m='2199020'>it's</span>
  <span m='2199190'>an</span> <span m='2199320'>unpredictable</span> <span m='2200050'>branch,</span>
  <span m='2200930'>that's going</span> <span m='2201100'>to</span> <span m='2201220'>be</span>
  <span m='2201360'>very</span> <span m='2201610'>expensive.</span> <span m='2203010'>So</span>
  <span m='2203970'>generally,</span> <span m='2205520'>there</span> <span m='2205720'>is</span>
  <span m='2205840'>a</span> <span m='2205930'>cost</span> <span m='2206350'>to</span>
  <span m='2206430'>making</span> <span m='2206810'>it</span> <span m='2207330'>reentrant.</span>
  </p><p><span m='2210090'>The</span> <span m='2210160'>third</span> <span m='2211210'>property</span>
  <span m='2211940'>is</span> <span m='2212150'>whether</span> <span m='2212430'>the</span>
  <span m='2212550'>lock</span> <span m='2212920'>is</span> <span m='2213230'>fair</span>
  <span m='2214030'>or</span> <span m='2214230'>unfair.</span> <span m='2215640'>So</span>
  <span m='2215800'>a</span> <span m='2215880'>fair</span> <span m='2217460'>mutex</span>
  <span m='2218110'>puts</span> <span m='2218330'>block</span> <span m='2218700'>threads</span>
  <span m='2219120'>essentially</span> <span m='2219540'>into</span> <span m='2219700'>a</span>
  <span m='2219770'>FIFO</span> <span m='2220100'>queue.</span> <span m='2220970'>And</span>
  <span m='2221410'>the</span> <span m='2221650'>unlock</span> <span m='2222100'>operation</span>
  <span m='2222720'>unblocks</span> <span m='2223330'>the</span> <span m='2223670'>thread</span>
  <span m='2224090'>that has</span> <span m='2224250'>been</span> <span m='2224420'>waiting</span>
  <span m='2224760'>the</span> <span m='2224850'>longest.</span> <span m='2226940'>So</span>
  <span m='2227120'>it</span> <span m='2227190'>makes</span> <span m='2227450'>it</span>
  <span m='2227580'>so</span> <span m='2227720'>that if</span> <span m='2227890'>you</span>
  <span m='2228040'>try</span> <span m='2228250'>to</span> <span m='2232010'>acquire</span>
  <span m='2232320'>a</span> <span m='2232810'>lock,</span> <span m='2233260'>you</span>
  <span m='2233450'>don't have</span> <span m='2233650'>some</span> <span m='2233870'>other</span>
  <span m='2234090'>thread</span> <span m='2234420'>coming</span> <span m='2234750'>in</span>
  <span m='2234900'>and</span> <span m='2235000'>trying</span> <span m='2235190'>to</span>
  <span m='2235380'>access</span> <span m='2235930'>that</span> <span m='2236180'>lock</span>
  <span m='2237490'>and</span> <span m='2237680'>getting</span> <span m='2237900'>ahead</span>
  <span m='2238140'>of you.</span> <span m='2239000'>It</span> <span m='2239260'>puts</span>
  <span m='2239460'>you</span> <span m='2239580'>in</span> <span m='2239720'>a</span>
  <span m='2240124'>queue.</span> </p><p><span m='2241740'>So</span> <span m='2241970'>an</span>
  <span m='2242110'>unfair</span> <span m='2242760'>mutex</span> <span m='2243020'>lets</span>
  <span m='2243330'>any</span> <span m='2243660'>blocked</span> <span m='2244110'>thread</span>
  <span m='2244440'>go</span> <span m='2244610'>next.</span> <span m='2247530'>So</span>
  <span m='2247760'>the</span> <span m='2247930'>cheapest</span> <span m='2248470'>thing</span>
  <span m='2248680'>to</span> <span m='2248790'>implement</span> <span m='2249860'>is</span>
  <span m='2250050'>a</span> <span m='2250190'>spinning,</span> <span m='2251030'>non-reentrant,</span>
  <span m='2252150'>unfair</span> <span m='2254260'>lock--</span> <span m='2255180'>mutex.</span>
  <span m='2256110'>Those</span> <span m='2256330'>are</span> <span m='2256360'>the</span>
  <span m='2256500'>cheapest</span> <span m='2256940'>ones</span> <span m='2257150'>to</span>
  <span m='2257250'>implement.</span> <span m='2257890'>Very</span> <span m='2258230'>lightweight,</span>
  <span m='2259520'>very</span> <span m='2259730'>easy to</span> <span m='2259930'>use.</span>
  </p><p><span m='2260490'>The</span> <span m='2260590'>heavyweight</span> <span m='2261200'>ones</span>
  <span m='2261520'>are a</span> <span m='2261660'>yielding,</span> <span m='2262270'>reentrant,</span>
  <span m='2263060'>fair lock.</span> <span m='2264900'>And</span> <span m='2265070'>of</span>
  <span m='2265140'>course,</span> <span m='2265360'>you</span> <span m='2265440'>can</span>
  <span m='2265570'>have</span> <span m='2265790'>combinations,</span> <span m='2267290'>because</span>
  <span m='2267760'>all</span> <span m='2268050'>of</span> <span m='2268130'>these</span>
  <span m='2268340'>have,</span> <span m='2269640'>as</span> <span m='2269810'>you</span>
  <span m='2269880'>can</span> <span m='2270000'>see,</span> <span m='2270600'>different</span>
  <span m='2271050'>properties</span> <span m='2271690'>in</span> <span m='2271830'>terms</span>
  <span m='2272100'>of</span> <span m='2272170'>convenience</span> <span m='2272730'>of</span>
  <span m='2272800'>use</span> <span m='2274250'>and</span> <span m='2275060'>so</span>
  <span m='2275290'>forth,</span> <span m='2275530'>as</span> <span m='2275650'>well</span>
  <span m='2275840'>as</span> <span m='2275940'>different</span> <span m='2276200'>overheads.</span>
  <span m='2277650'>So</span> <span m='2278420'>there's</span> <span m='2278580'>some</span>
  <span m='2278780'>cases</span> <span m='2279180'>where</span> <span m='2279800'>the</span>
  <span m='2279940'>overhead</span> <span m='2280260'>isn't</span> <span m='2280450'>a</span>
  <span m='2280500'>big</span> <span m='2280700'>deal</span> <span m='2280950'>because</span>
  <span m='2281140'>it's</span> <span m='2281310'>not</span> <span m='2281640'>in</span>
  <span m='2281770'>the</span> <span m='2281900'>inner</span> <span m='2282090'>loop</span>
  <span m='2283272'>of a</span> <span m='2283650'>program</span> <span m='2284390'>or</span>
  <span m='2285230'>a</span> <span m='2285280'>heavily</span> <span m='2285660'>executed</span>
  <span m='2286120'>statement.</span> </p><p><span m='2289220'>So</span> <span m='2289350'>let's</span>
  <span m='2289590'>take</span> <span m='2289840'>a</span> <span m='2289900'>look</span>
  <span m='2290230'>at</span> <span m='2290490'>one</span> <span m='2290640'>of</span>
  <span m='2290690'>the</span> <span m='2290750'>simplest</span> <span m='2291260'>locks,</span>
  <span m='2291620'>which</span> <span m='2291820'>is</span> <span m='2291970'>a</span>
  <span m='2292400'>simple</span> <span m='2292770'>spinning</span> <span m='2293230'>mutex.</span>
  <span m='2294710'>This</span> <span m='2294940'>is</span> <span m='2295160'>the</span>
  <span m='2296910'>x86</span> <span m='2297400'>code</span> <span m='2299070'>for</span>
  <span m='2299350'>how</span> <span m='2299510'>to</span> <span m='2299610'>acquire</span>
  <span m='2299980'>a</span> <span m='2300020'>lock.</span> <span m='2303260'>So</span>
  <span m='2303390'>let's</span> <span m='2303580'>run</span> <span m='2303780'>through</span>
  <span m='2303880'>this.</span> <span m='2304060'>So</span> <span m='2304180'>we</span>
  <span m='2304290'>start</span> <span m='2304590'>out</span> <span m='2304730'>at</span>
  <span m='2304820'>the</span> <span m='2304920'>top.</span> <span m='2306000'>And</span>
  <span m='2306130'>I</span> <span m='2306210'>check</span> <span m='2306520'>to</span>
  <span m='2306620'>see</span> <span m='2306780'>if</span> <span m='2306880'>the</span>
  <span m='2306980'>mutex</span> <span m='2307470'>is</span> <span m='2307630'>0,</span>
  <span m='2308220'>which</span> <span m='2308380'>is</span> <span m='2308490'>basically,</span>
  <span m='2309460'>it's</span> <span m='2309570'>going</span> <span m='2309640'>to</span>
  <span m='2309710'>be</span> <span m='2309780'>0</span> <span m='2310460'>if</span>
  <span m='2310610'>it's</span> <span m='2310790'>free</span> <span m='2311220'>and</span>
  <span m='2311460'>1</span> <span m='2311820'>if</span> <span m='2312020'>it</span>
  <span m='2312150'>has</span> <span m='2312280'>been</span> <span m='2312420'>acquired.</span>
  </p><p><span m='2314570'>So</span> <span m='2314690'>we</span> <span m='2314820'>compare</span>
  <span m='2315270'>it.</span> <span m='2316230'>If</span> <span m='2316450'>it's</span>
  <span m='2316670'>free,</span> <span m='2317590'>then</span> <span m='2317880'>I</span>
  <span m='2318020'>jump</span> <span m='2318400'>to</span> <span m='2318520'>try</span>
  <span m='2318770'>to</span> <span m='2318820'>get</span> <span m='2319120'>the</span>
  <span m='2319390'>mutex.</span> <span m='2321010'>Otherwise,</span> <span m='2321880'>I</span>
  <span m='2322050'>execute</span> <span m='2322510'>this</span> <span m='2322710'>PAUSE</span>
  <span m='2323080'>instruction,</span> <span m='2323990'>and</span> <span m='2324140'>this</span>
  <span m='2324270'>turns</span> <span m='2324510'>out</span> <span m='2324710'>to</span>
  <span m='2324790'>be</span> <span m='2324950'>a--</span> <span m='2326140'>it's</span>
  <span m='2326370'>humorous.</span> <span m='2326880'>It's</span> <span m='2327530'>x86</span>
  <span m='2328520'>hack</span> <span m='2329380'>to</span> <span m='2329650'>un-confuse</span>
  <span m='2330010'>the</span> <span m='2330060'>pipeline.</span> </p><p><span m='2330460'>So
  it</span> <span m='2330600'>turns</span> <span m='2330910'>out</span> <span m='2331120'>that</span>
  <span m='2331220'>in</span> <span m='2331340'>this</span> <span m='2331550'>case,</span>
  <span m='2333120'>if</span> <span m='2333310'>you</span> <span m='2333410'>don't</span>
  <span m='2333630'>have</span> <span m='2333760'>a</span> <span m='2333890'>pause</span>
  <span m='2334310'>here--</span> <span m='2335100'>which</span> <span m='2335360'>is</span>
  <span m='2335600'>no-op</span> <span m='2336090'>and</span> <span m='2336210'>does</span>
  <span m='2336400'>nothing--</span> <span m='2338320'>x86</span> <span m='2340360'>mispredicts</span>
  <span m='2341000'>something</span> <span m='2341530'>or</span> <span m='2341900'>whatever,</span>
  <span m='2342580'>and</span> <span m='2343350'>it's</span> <span m='2344290'>more</span>
  <span m='2344660'>time</span> <span m='2344970'>consuming</span> <span m='2346100'>than</span>
  <span m='2346360'>if</span> <span m='2346480'>it</span> <span m='2346600'>doesn't</span>
  <span m='2346890'>have</span> <span m='2347120'>that</span> <span m='2347760'>there.</span>
  <span m='2348040'>The</span> <span m='2348420'>manual</span> <span m='2348760'>explains</span>
  <span m='2349240'>very</span> <span m='2349470'>little</span> <span m='2349790'>about</span>
  <span m='2350270'>this</span> <span m='2351090'>hardware</span> <span m='2351460'>bug</span>
  <span m='2352290'>except</span> <span m='2352670'>to</span> <span m='2352740'>say,</span>
  <span m='2352990'>put</span> <span m='2353200'>in</span> <span m='2353290'>the</span>
  <span m='2353370'>pause.</span> <span m='2355440'>So</span> <span m='2355640'>if</span>
  <span m='2355720'>you</span> <span m='2355800'>didn't</span> <span m='2356070'>get</span>
  <span m='2356220'>it,</span> <span m='2356360'>then</span> <span m='2356490'>you</span>
  <span m='2356590'>jump</span> <span m='2356900'>to</span> <span m='2357010'>spin</span>
  <span m='2357300'>mutex,</span> <span m='2357770'>and</span> <span m='2357940'>try</span>
  <span m='2358180'>again,</span> <span m='2358690'>check</span> <span m='2358930'>to</span>
  <span m='2359000'>see</span> <span m='2359150'>if</span> <span m='2359240'>it's</span>
  <span m='2359400'>free.</span> </p><p><span m='2360710'>Now,</span> <span m='2360830'>notice</span>
  <span m='2361220'>that</span> <span m='2361740'>we're</span> <span m='2361830'>going</span>
  <span m='2361920'>to</span> <span m='2361980'>spin</span> <span m='2363090'>until</span>
  <span m='2363370'>it's</span> <span m='2363520'>free,</span> <span m='2363800'>and</span>
  <span m='2363890'>then</span> <span m='2364200'>we're going to</span> <span m='2364290'>try</span>
  <span m='2364490'>to</span> <span m='2364560'>get</span> <span m='2365050'>it.</span>
  <span m='2365860'>Why not</span> <span m='2365920'>just</span> <span m='2366200'>try</span>
  <span m='2366410'>to</span> <span m='2366460'>get</span> <span m='2366710'>it</span>
  <span m='2366870'>first?</span> <span m='2374900'>Well,</span> <span m='2375090'>think</span>
  <span m='2375280'>about</span> <span m='2375560'>that</span> <span m='2375750'>while</span>
  <span m='2375880'>we</span> <span m='2375990'>go</span> <span m='2376170'>through</span>
  <span m='2376470'>how</span> <span m='2376710'>to</span> <span m='2376780'>get</span>
  <span m='2377010'>it,</span> <span m='2377110'>and then</span> <span m='2377270'>I'll</span>
  <span m='2377450'>ask</span> <span m='2377660'>it</span> <span m='2377720'>again.</span>
  <span m='2379310'>Think</span> <span m='2379460'>about</span> <span m='2379730'>why</span>
  <span m='2379950'>it</span> <span m='2380030'>is</span> <span m='2380350'>that</span>
  <span m='2380600'>you</span> <span m='2380680'>might</span> <span m='2380890'>want</span>
  <span m='2381020'>to</span> <span m='2381070'>get it</span> <span m='2381310'>first.</span>
  </p><p><span m='2382310'>So</span> <span m='2382370'>if</span> <span m='2382460'>I</span>
  <span m='2382550'>want</span> <span m='2382800'>to</span> <span m='2382850'>get</span>
  <span m='2384660'>the</span> <span m='2384800'>mutex,</span> <span m='2385360'>I</span>
  <span m='2385500'>first</span> <span m='2386880'>get</span> <span m='2387130'>a</span>
  <span m='2387180'>value</span> <span m='2387540'>of</span> <span m='2387640'>1</span>
  <span m='2387920'>in</span> <span m='2388070'>my</span> <span m='2389630'>register.</span>
  <span m='2390490'>And</span> <span m='2390650'>then</span> <span m='2390800'>I</span>
  <span m='2390920'>compute</span> <span m='2391650'>this</span> <span m='2392020'>exchange</span>
  <span m='2393080'>operation,</span> <span m='2393760'>which</span> <span m='2393950'>exchanges</span>
  <span m='2395150'>the</span> <span m='2395250'>value</span> <span m='2395680'>of</span>
  <span m='2395770'>the</span> <span m='2395880'>mutex</span> <span m='2397080'>with</span>
  <span m='2397260'>the</span> <span m='2397450'>value</span> <span m='2399340'>of
  the--</span> <span m='2401210'>with</span> <span m='2401520'>the</span> <span m='2401600'>one</span>
  <span m='2401890'>that</span> <span m='2402050'>I</span> <span m='2402150'>have.</span>
  <span m='2403110'>So</span> <span m='2403360'>it</span> <span m='2403500'>exchanges</span>
  <span m='2404060'>the</span> <span m='2404190'>memory</span> <span m='2404550'>location</span>
  <span m='2405140'>with</span> <span m='2405240'>the</span> <span m='2405340'>register.</span>
  </p><p><span m='2406240'>Now,</span> <span m='2406380'>this</span> <span m='2406640'>is</span>
  <span m='2406820'>an</span> <span m='2406900'>expensive</span> <span m='2407470'>operation--</span>
  <span m='2408070'>exchange--</span> <span m='2409060'>because</span> <span m='2409350'>it's</span>
  <span m='2409510'>an</span> <span m='2409600'>atomic</span> <span m='2410110'>exchange,</span>
  <span m='2411040'>and it</span> <span m='2411280'>typically</span> <span m='2411710'>has</span>
  <span m='2411970'>to</span> <span m='2412050'>go</span> <span m='2412270'>at</span>
  <span m='2412320'>least</span> <span m='2412660'>out</span> <span m='2412860'>to</span>
  <span m='2412980'>L2</span> <span m='2413510'>to</span> <span m='2413610'>do</span>
  <span m='2413790'>this.</span> <span m='2415930'>So</span> <span m='2416090'>it's</span>
  <span m='2416210'>an</span> <span m='2416290'>expensive</span> <span m='2416880'>operation,</span>
  <span m='2417370'>because</span> <span m='2417620'>it's</span> <span m='2417760'>a</span>
  <span m='2417810'>read-modify-write</span> <span m='2419110'>operation.</span> <span
  m='2420170'>I'm</span> <span m='2420290'>swapping</span> <span m='2420900'>my</span>
  <span m='2421050'>register</span> <span m='2421530'>value</span> <span m='2423910'>with</span>
  <span m='2424180'>a</span> <span m='2424220'>value</span> <span m='2425280'>that's</span>
  <span m='2425540'>in</span> <span m='2425800'>the</span> <span m='2426020'>mutex.</span>
  </p><p><span m='2430490'>So</span> <span m='2430650'>it</span> <span m='2430740'>turns</span>
  <span m='2430990'>out</span> <span m='2431230'>that</span> <span m='2431450'>if</span>
  <span m='2431790'>it's</span> <span m='2432320'>0,</span> <span m='2433510'>then</span>
  <span m='2433700'>it</span> <span m='2433840'>means</span> <span m='2434110'>I</span>
  <span m='2434290'>got</span> <span m='2434640'>it.</span> <span m='2439730'>So</span>
  <span m='2439900'>I</span> <span m='2439990'>compare</span> <span m='2440490'>it</span>
  <span m='2440600'>with</span> <span m='2440720'>0,</span> <span m='2441600'>and</span>
  <span m='2441890'>if</span> <span m='2442010'>it's</span> <span m='2442230'>equal</span>
  <span m='2442560'>to</span> <span m='2442610'>0,</span> <span m='2443000'>I</span>
  <span m='2443090'>go</span> <span m='2443450'>onto</span> <span m='2443520'>the</span>
  <span m='2443610'>critical</span> <span m='2444010'>section.</span> <span m='2444720'>When</span>
  <span m='2444830'>I'm</span> <span m='2444910'>done</span> <span m='2445130'>with</span>
  <span m='2445250'>the</span> <span m='2445290'>critical</span> <span m='2445670'>section,</span>
  <span m='2446460'>I</span> <span m='2446720'>release</span> <span m='2447140'>the</span>
  <span m='2447190'>mutex</span> <span m='2447720'>by</span> <span m='2447870'>basically</span>
  <span m='2448330'>storing</span> <span m='2448710'>0</span> <span m='2449080'>in</span>
  <span m='2449170'>there,</span> <span m='2450650'>because</span> <span m='2450800'>I'm</span>
  <span m='2450910'>the</span> <span m='2451050'>only</span> <span m='2451200'>one</span>
  <span m='2451490'>who</span> <span m='2451910'>accesses</span> <span m='2452060'>the</span>
  <span m='2452130'>mutex</span> <span m='2452560'>at</span> <span m='2452700'>this</span>
  <span m='2452850'>point.</span> </p><p><span m='2454620'>If</span> <span m='2454790'>I</span>
  <span m='2454880'>didn't</span> <span m='2455250'>get</span> <span m='2455430'>it,</span>
  <span m='2455550'>if</span> <span m='2455670'>the</span> <span m='2455770'>value</span>
  <span m='2456080'>is</span> <span m='2456310'>1,</span> <span m='2456910'>notice</span>
  <span m='2457280'>that</span> <span m='2457410'>because</span> <span m='2457750'>I'm</span>
  <span m='2457850'>swapping</span> <span m='2458400'>a</span> <span m='2458480'>1</span>
  <span m='2458790'>in,</span> <span m='2460330'>even</span> <span m='2460600'>though</span>
  <span m='2460770'>the</span> <span m='2461520'>1</span> <span m='2461850'>got</span>
  <span m='2462060'>swapped</span> <span m='2462510'>in,</span> <span m='2462860'>well,</span>
  <span m='2463120'>there was</span> <span m='2463310'>a</span> <span m='2463370'>1</span>
  <span m='2463620'>there</span> <span m='2463810'>before.</span> <span m='2464350'>So</span>
  <span m='2464480'>it</span> <span m='2464590'>basically</span> <span m='2466510'>did</span>
  <span m='2466680'>not</span> <span m='2466880'>affect</span> <span m='2467230'>the</span>
  <span m='2467310'>value</span> <span m='2467680'>of</span> <span m='2467760'>the</span>
  <span m='2467850'>mutex.</span> <span m='2468650'>But</span> <span m='2468810'>I</span>
  <span m='2468920'>discover,</span> <span m='2469510'>oh,</span> <span m='2469790'>I</span>
  <span m='2469870'>don't</span> <span m='2470090'>have</span> <span m='2470400'>it.</span>
  <span m='2470810'>Then</span> <span m='2470990'>we</span> <span m='2471100'>go</span>
  <span m='2471330'>all</span> <span m='2471440'>the</span> <span m='2471550'>way</span>
  <span m='2471710'>back</span> <span m='2472060'>up</span> <span m='2472250'>there</span>
  <span m='2472880'>to</span> <span m='2473030'>spin</span> <span m='2473190'>mutex.</span>
  </p><p><span m='2474050'>So</span> <span m='2474220'>here's</span> <span m='2474420'>the</span>
  <span m='2474490'>question.</span> <span m='2475090'>Why</span> <span m='2475310'>do</span>
  <span m='2475410'>I</span> <span m='2475490'>need</span> <span m='2475710'>all</span>
  <span m='2475900'>this</span> <span m='2476070'>preamble</span> <span m='2476510'>code?</span>
  <span m='2476790'>Why</span> <span m='2476980'>not</span> <span m='2477150'>just</span>
  <span m='2477350'>go</span> <span m='2477610'>straight</span> <span m='2478030'>to</span>
  <span m='2478110'>Get_Mutex,</span> <span m='2479240'>make</span> <span m='2480960'>the</span>
  <span m='2481140'>spin</span> <span m='2481430'>mutex</span> <span m='2481820'>here</span>
  <span m='2481980'>be a</span> <span m='2482170'>jump</span> <span m='2482860'>to</span>
  <span m='2483000'>Get_Mutex?</span> <span m='2485110'>Yeah?</span> </p><p><span
  m='2485450'>AUDIENCE:</span> <span m='2485790'>Maybe</span> <span m='2486221'>it's
  because</span> <span m='2486652'>the exchange</span> <span m='2487083'>is expensive.</span>
  </p><p><span m='2487945'>PROFESSOR:</span> <span m='2488380'>Excuse</span> <span
  m='2488620'>me?</span> </p><p><span m='2489050'>AUDIENCE:</span> <span m='2489480'>The
  exchange is--</span> </p><p><span m='2489810'>PROFESSOR:</span> <span m='2489910'>Yeah,</span>
  <span m='2490050'>because the</span> <span m='2490510'>exchange is</span> <span
  m='2490580'>expensive.</span> <span m='2491510'>Exactly.</span> <span m='2492520'>So</span>
  <span m='2492730'>this</span> <span m='2493030'>code</span> <span m='2493290'>here,</span>
  <span m='2494990'>I</span> <span m='2495140'>can</span> <span m='2495390'>compare.</span>
  <span m='2496190'>And as</span> <span m='2496360'>long</span> <span m='2496650'>as</span>
  <span m='2496760'>nobody's</span> <span m='2497150'>touching</span> <span m='2497590'>anything,</span>
  <span m='2498650'>this</span> <span m='2498900'>becomes</span> <span m='2499870'>just</span>
  <span m='2501820'>L1</span> <span m='2502050'>memory</span> <span m='2504680'>accesses.</span>
  <span m='2506950'>Whereas</span> <span m='2507200'>here,</span> <span m='2507500'>it's</span>
  <span m='2507600'>going</span> <span m='2507710'>to</span> <span m='2507750'>be</span>
  <span m='2507870'>at</span> <span m='2507940'>least</span> <span m='2508270'>L2</span>
  <span m='2511010'>to</span> <span m='2511160'>do</span> <span m='2511320'>the</span>
  <span m='2511440'>exchange</span> <span m='2511940'>operation.</span> <span m='2512790'>So</span>
  <span m='2512960'>rather</span> <span m='2513320'>than</span> <span m='2513510'>doing</span>
  <span m='2513910'>that--</span> <span m='2515690'>moreover,</span> <span m='2516190'>this</span>
  <span m='2516640'>one</span> <span m='2518020'>actually</span> <span m='2518520'>changes</span>
  <span m='2519200'>the</span> <span m='2519280'>value.</span> </p><p><span m='2520290'>So</span>
  <span m='2520330'>what</span> <span m='2520460'>happens</span> <span m='2520790'>when</span>
  <span m='2520940'>I</span> <span m='2521030'>change</span> <span m='2521450'>the</span>
  <span m='2521550'>value</span> <span m='2521900'>of</span> <span m='2521970'>the</span>
  <span m='2522200'>mutex?</span> <span m='2522500'>Even</span> <span m='2522770'>though</span>
  <span m='2522940'>I</span> <span m='2523030'>change</span> <span m='2523380'>it</span>
  <span m='2523480'>to</span> <span m='2523560'>the</span> <span m='2523660'>same</span>
  <span m='2524090'>value,</span> <span m='2525060'>what</span> <span m='2525410'>happens</span>
  <span m='2525890'>in</span> <span m='2525970'>order</span> <span m='2526210'>to</span>
  <span m='2526330'>do</span> <span m='2526540'>that</span> <span m='2526860'>exchange?</span>
  <span m='2528590'>Remember</span> <span m='2528980'>from</span> <span m='2530310'>several</span>
  <span m='2530680'>lectures</span> <span m='2531060'>ago.</span> <span m='2533320'>What's</span>
  <span m='2533520'>going</span> <span m='2533590'>to</span> <span m='2533660'>happen</span>
  <span m='2534060'>when</span> <span m='2534220'>I</span> <span m='2534280'>make</span>
  <span m='2534610'>an</span> <span m='2535150'>exchange</span> <span m='2535650'>there?</span>
  <span m='2535890'>What</span> <span m='2536070'>does</span> <span m='2536190'>the</span>
  <span m='2536250'>hardware</span> <span m='2536670'>have</span> <span m='2536880'>to</span>
  <span m='2536990'>do?</span> <span m='2543811'>What's</span> <span m='2544320'>the</span>
  <span m='2544360'>hardware</span> <span m='2544770'>going</span> <span m='2544890'>to</span>
  <span m='2544960'>do</span> <span m='2545340'>on</span> <span m='2545600'>any</span>
  <span m='2545940'>store</span> <span m='2547170'>to</span> <span m='2547310'>a</span>
  <span m='2547350'>shared</span> <span m='2547730'>memory</span> <span m='2548000'>location,</span>
  <span m='2549980'>to a</span> <span m='2550310'>memory</span> <span m='2550630'>location</span>
  <span m='2551140'>in</span> <span m='2551290'>shared</span> <span m='2551590'>memory</span>
  <span m='2552200'>that</span> <span m='2552380'>is</span> <span m='2552520'>actually</span>
  <span m='2552950'>shared?</span> <span m='2554480'>Yeah?</span> </p><p><span m='2555260'>AUDIENCE:</span>
  <span m='2555693'>[INAUDIBLE]</span> </p><p><span m='2556126'>PROFESSOR:</span>
  <span m='2556560'>Yeah,</span> <span m='2556830'>it's got to</span> <span m='2556990'>invalidate</span>
  <span m='2557890'>all</span> <span m='2558000'>the</span> <span m='2558140'>other</span>
  <span m='2558310'>copies.</span> <span m='2561180'>So</span> <span m='2561460'>if</span>
  <span m='2561680'>everybody</span> <span m='2562180'>spinning</span> <span m='2562680'>here--</span>
  <span m='2563040'>imagine</span> <span m='2563440'>that</span> <span m='2563560'>you</span>
  <span m='2563640'>have</span> <span m='2563900'>five</span> <span m='2564200'>guys</span>
  <span m='2564480'>spinning,</span> <span m='2566910'>doing</span> <span m='2567180'>exchanges--</span>
  <span m='2568310'>they're</span> <span m='2568490'>all</span> <span m='2569300'>creating</span>
  <span m='2569710'>all</span> <span m='2570060'>this</span> <span m='2570630'>traffic</span>
  <span m='2571986'>of</span> <span m='2572350'>invalidations,</span> <span m='2573310'>what's</span>
  <span m='2573460'>called an</span> <span m='2573710'>&quot;invalidation</span> <span
  m='2574480'>storm.&quot;</span> <span m='2576300'>So</span> <span m='2576470'>they</span>
  <span m='2576570'>create an</span> <span m='2576870'>invalidation</span> <span m='2577620'>storm</span>
  <span m='2577940'>as</span> <span m='2578030'>they</span> <span m='2578160'>all
  are invalidating</span> <span m='2579190'>each</span> <span m='2579380'>other</span>
  <span m='2579760'>so</span> <span m='2579950'>that</span> <span m='2580080'>they</span>
  <span m='2580220'>can</span> <span m='2580400'>get</span> <span m='2580530'>access</span>
  <span m='2580990'>to</span> <span m='2581120'>it</span> <span m='2581220'>so</span>
  <span m='2581330'>that</span> <span m='2581470'>they</span> <span m='2581620'>can</span>
  <span m='2581780'>change</span> <span m='2582130'>the</span> <span m='2582240'>value</span>
  <span m='2582570'>themselves.</span> </p><p><span m='2585240'>But</span> <span m='2585310'>up</span>
  <span m='2585490'>here,</span> <span m='2585910'>all</span> <span m='2586220'>I'm</span>
  <span m='2586330'>doing</span> <span m='2586590'>is</span> <span m='2586720'>looking</span>
  <span m='2587080'>at</span> <span m='2587200'>the</span> <span m='2587280'>value.</span>
  <span m='2590672'>All</span> <span m='2591130'>I'm</span> <span m='2591240'>doing</span>
  <span m='2591470'>is</span> <span m='2591600'>looking</span> <span m='2591900'>at</span>
  <span m='2591990'>the</span> <span m='2592080'>value</span> <span m='2592450'>to</span>
  <span m='2592570'>see</span> <span m='2592770'>if</span> <span m='2592900'>it's</span>
  <span m='2593070'>free.</span> <span m='2595345'>And</span> <span m='2595640'>it's</span>
  <span m='2595840'>not</span> <span m='2596120'>until</span> <span m='2596920'>the</span>
  <span m='2597010'>guy</span> <span m='2597680'>actually</span> <span m='2600980'>frees</span>
  <span m='2601380'>the</span> <span m='2601490'>value</span> <span m='2606510'>that
  it</span> <span m='2606840'>actually--</span> <span m='2607430'>actually,</span>
  <span m='2609000'>this</span> <span m='2609355'>is</span> <span m='2609710'>interesting.</span>
  <span m='2610100'>I</span> <span m='2610170'>think</span> <span m='2610380'>I</span>
  <span m='2610430'>wrote</span> <span m='2610680'>this</span> <span m='2610870'>with</span>
  <span m='2612230'>Intel</span> <span m='2613690'>syntax,</span> <span m='2614180'>rather</span>
  <span m='2614260'>than</span> <span m='2614470'>AT&amp;T,</span> <span m='2615060'>didn't
  I?</span> <span m='2617670'>The</span> <span m='2617830'>MOV</span> <span m='2618660'>mutex,</span>
  <span m='2618920'>0</span> <span m='2619250'>moves</span> <span m='2619490'>0</span>
  <span m='2619770'>into</span> <span m='2620050'>the</span> <span m='2620150'>mutex,</span>
  <span m='2626020'>which</span> <span m='2626180'>is</span> <span m='2626290'>Intel</span>
  <span m='2627170'>syntax.</span> </p><p><span m='2627630'>I</span> <span m='2627660'>probably</span>
  <span m='2627910'>should</span> <span m='2628040'>have</span> <span m='2628150'>converted</span>
  <span m='2628580'>this</span> <span m='2630970'>to</span> <span m='2631130'>AT&amp;T,</span>
  <span m='2631620'>because</span> <span m='2631820'>that's</span> <span m='2632000'>what</span>
  <span m='2632100'>we're</span> <span m='2632270'>generally</span> <span m='2632610'>using</span>
  <span m='2632880'>in</span> <span m='2632950'>the</span> <span m='2633020'>class.</span>
  <span m='2634350'>I'll</span> <span m='2634760'>fix</span> <span m='2635020'>that</span>
  <span m='2635920'>before I put the</span> <span m='2636420'>slides</span> <span
  m='2636870'>up.</span> <span m='2638700'>Basically,</span> <span m='2639140'>I pulled</span>
  <span m='2639320'>this</span> <span m='2639490'>out</span> <span m='2639640'>of</span>
  <span m='2639720'>the</span> <span m='2639900'>Intel</span> <span m='2640180'>manual.</span>
  </p><p><span m='2643820'>So</span> <span m='2643990'>any</span> <span m='2644130'>questions</span>
  <span m='2644630'>about</span> <span m='2645510'>this</span> <span m='2645730'>code?</span>
  <span m='2646770'>Everybody</span> <span m='2647090'>see</span> <span m='2647300'>how</span>
  <span m='2647520'>it</span> <span m='2647560'>works?</span> <span m='2648490'>It</span>
  <span m='2648790'>relies</span> <span m='2649240'>on</span> <span m='2649300'>this</span>
  <span m='2649460'>atomic</span> <span m='2649950'>exchange</span> <span m='2650630'>operation.</span>
  <span m='2651610'>And</span> <span m='2652180'>I'm going</span> <span m='2652210'>to</span>
  <span m='2652380'>end</span> <span m='2652580'>up</span> <span m='2652680'>sitting</span>
  <span m='2653010'>here</span> <span m='2653200'>spinning</span> <span m='2654540'>until</span>
  <span m='2655310'>maybe</span> <span m='2655700'>I</span> <span m='2655790'>can</span>
  <span m='2656090'>get</span> <span m='2656260'>access</span> <span m='2656690'>to</span>
  <span m='2656850'>it.</span> <span m='2657330'>When</span> <span m='2657500'>I</span>
  <span m='2657560'>have</span> <span m='2657670'>a</span> <span m='2657730'>chance</span>
  <span m='2658080'>to</span> <span m='2658160'>get</span> <span m='2658280'>access</span>
  <span m='2658630'>to</span> <span m='2658840'>it,</span> <span m='2658930'>I try</span>
  <span m='2659220'>to</span> <span m='2659280'>get</span> <span m='2659500'>it.</span>
  <span m='2659750'>If</span> <span m='2659990'>I</span> <span m='2660090'>don't</span>
  <span m='2660310'>get</span> <span m='2660470'>it,</span> <span m='2660590'>I</span>
  <span m='2660650'>go</span> <span m='2660810'>back</span> <span m='2661050'>to</span>
  <span m='2661140'>spinning.</span> </p><p><span m='2666690'>How</span> <span m='2666910'>do</span>
  <span m='2667030'>I</span> <span m='2667130'>convert</span> <span m='2667750'>this</span>
  <span m='2668540'>to</span> <span m='2668720'>a</span> <span m='2668790'>yielding</span>
  <span m='2669380'>mutex?</span> </p><p><span m='2675449'>AUDIENCE:</span> <span
  m='2676427'>Instead</span> <span m='2676916'>of having</span> <span m='2677405'>that</span>
  <span m='2677894'>spinning</span> <span m='2678383'>mutex,</span> <span m='2679850'>you
  should--</span> <span m='2682295'>you</span> <span m='2682784'>shouldn't</span>
  <span m='2683273'>have that.</span> <span m='2683762'>You should</span> <span m='2684251'>just
  have</span> <span m='2684740'>something</span> <span m='2685229'>that allows you</span>
  <span m='2685718'>to just</span> <span m='2686207'>[INAUDIBLE].</span> </p><p><span
  m='2686696'>PROFESSOR:</span> <span m='2687190'>Yeah,</span> <span m='2687430'>so</span>
  <span m='2687710'>actually,</span> <span m='2687990'>the way</span> <span m='2688240'>you</span>
  <span m='2688490'>do</span> <span m='2688630'>it</span> <span m='2688710'>is</span>
  <span m='2688810'>you replace</span> <span m='2689290'>the</span> <span m='2689390'>PAUSE</span>
  <span m='2689720'>instruction.</span> <span m='2690460'>Exactly</span> <span m='2690820'>what</span>
  <span m='2690940'>you're</span> <span m='2691050'>saying.</span> <span m='2691610'>You've</span>
  <span m='2691860'>got</span> <span m='2692040'>the</span> <span m='2692120'>right</span>
  <span m='2692350'>place</span> <span m='2692610'>in</span> <span m='2692690'>the</span>
  <span m='2692760'>code.</span> <span m='2693650'>We</span> <span m='2693770'>basically</span>
  <span m='2694250'>call a</span> <span m='2694610'>yield.</span> <span m='2694865'>And</span>
  <span m='2695120'>you</span> <span m='2695210'>can</span> <span m='2695340'>use,</span>
  <span m='2695550'>for</span> <span m='2695630'>example,</span> <span m='2696060'>pthread_yield.</span>
  <span m='2699330'>What</span> <span m='2699470'>it</span> <span m='2699590'>tells</span>
  <span m='2699870'>the</span> <span m='2699990'>operating</span> <span m='2700320'>system</span>
  <span m='2700640'>is,</span> <span m='2700770'>give</span> <span m='2700960'>up</span>
  <span m='2701160'>on</span> <span m='2701330'>this</span> <span m='2702030'>quantum.</span>
  <span m='2702295'>You</span> <span m='2702560'>can</span> <span m='2702740'>schedule</span>
  <span m='2703100'>me</span> <span m='2703270'>out.</span> <span m='2704590'>Somebody</span>
  <span m='2704910'>else</span> <span m='2705070'>can</span> <span m='2705160'>be</span>
  <span m='2705250'>scheduled.</span> <span m='2705710'>Now,</span> <span m='2705970'>if
  nobody</span> <span m='2706320'>else</span> <span m='2706530'>is</span> <span m='2706670'>there</span>
  <span m='2706870'>to</span> <span m='2706950'>be</span> <span m='2707060'>scheduled,</span>
  <span m='2708310'>often</span> <span m='2708680'>you'll</span> <span m='2708830'>just</span>
  <span m='2709020'>get</span> <span m='2709170'>control</span> <span m='2709530'>back,</span>
  <span m='2709870'>and</span> <span m='2711480'>you'll</span> <span m='2711880'>jump</span>
  <span m='2712120'>again</span> <span m='2712490'>and</span> <span m='2712610'>give</span>
  <span m='2712710'>the</span> <span m='2712860'>operating</span> <span m='2713210'>system</span>
  <span m='2713540'>another</span> <span m='2713780'>time.</span> </p><p><span m='2717070'>Now,</span>
  <span m='2719410'>one</span> <span m='2719910'>of</span> <span m='2719960'>the</span>
  <span m='2720060'>things</span> <span m='2720630'>I've</span> <span m='2720830'>seen</span>
  <span m='2721290'>in</span> <span m='2721620'>computer</span> <span m='2722030'>benchmarks</span>
  <span m='2723300'>that</span> <span m='2723450'>use</span> <span m='2724000'>locking</span>
  <span m='2725460'>is</span> <span m='2726520'>that</span> <span m='2726700'>they</span>
  <span m='2726850'>all</span> <span m='2727150'>use</span> <span m='2727380'>spin</span>
  <span m='2727750'>locks.</span> <span m='2730470'>They</span> <span m='2730570'>never</span>
  <span m='2730900'>use</span> <span m='2731980'>the</span> <span m='2732080'>yielding,</span>
  <span m='2733790'>because</span> <span m='2735410'>if</span> <span m='2735560'>you</span>
  <span m='2735680'>yield,</span> <span m='2736480'>then</span> <span m='2737880'>when</span>
  <span m='2737980'>the lock</span> <span m='2738390'>comes</span> <span m='2738660'>free,</span>
  <span m='2739350'>you're</span> <span m='2739640'>not</span> <span m='2739820'>going</span>
  <span m='2739930'>to</span> <span m='2739970'>be</span> <span m='2740070'>ready</span>
  <span m='2740380'>to</span> <span m='2740460'>come</span> <span m='2740630'>back</span>
  <span m='2740890'>in.</span> <span m='2741020'>You</span> <span m='2741130'>may</span>
  <span m='2741300'>be</span> <span m='2741820'>switched</span> <span m='2742240'>out.</span>
  </p><p><span m='2744470'>So</span> <span m='2744700'>a</span> <span m='2744900'>common</span>
  <span m='2745370'>thing</span> <span m='2747240'>that</span> <span m='2747560'>all</span>
  <span m='2747800'>these</span> <span m='2748010'>companies</span> <span m='2748490'>do</span>
  <span m='2748730'>when</span> <span m='2748900'>they're</span> <span m='2749160'>vying</span>
  <span m='2749700'>for</span> <span m='2749850'>who's</span> <span m='2750090'>got</span>
  <span m='2750270'>the</span> <span m='2750350'>fastest</span> <span m='2751460'>on</span>
  <span m='2751620'>this</span> <span m='2751810'>benchmark</span> <span m='2752320'>or</span>
  <span m='2752410'>fastest</span> <span m='2752890'>on</span> <span m='2753230'>that</span>
  <span m='2753510'>benchmark</span> <span m='2754420'>is</span> <span m='2754550'>they</span>
  <span m='2754650'>go</span> <span m='2754830'>through</span> <span m='2755250'>and</span>
  <span m='2755340'>they</span> <span m='2755790'>convert</span> <span m='2757720'>all</span>
  <span m='2758040'>their</span> <span m='2758340'>yielding</span> <span m='2758820'>mutexes</span>
  <span m='2759680'>into</span> <span m='2759910'>spinning</span> <span m='2760510'>mutexes,</span>
  <span m='2761250'>then</span> <span m='2761490'>take</span> <span m='2761750'>their</span>
  <span m='2761850'>measurements,</span> <span m='2763460'>when</span> <span m='2763650'>in</span>
  <span m='2763740'>fact,</span> <span m='2764670'>as</span> <span m='2764760'>a</span>
  <span m='2764840'>practical</span> <span m='2765240'>matter,</span> <span m='2765500'>they</span>
  <span m='2765640'>can't</span> <span m='2765890'>actually</span> <span m='2766170'>ship</span>
  <span m='2766420'>code</span> <span m='2766710'>that</span> <span m='2766910'>way.</span>
  <span m='2768100'>So</span> <span m='2769300'>you'll</span> <span m='2769410'>see</span>
  <span m='2769620'>this</span> <span m='2769800'>kind</span> <span m='2770120'>of</span>
  <span m='2770560'>game</span> <span m='2770920'>played</span> <span m='2771350'>where</span>
  <span m='2771490'>people</span> <span m='2771780'>try</span> <span m='2771970'>to</span>
  <span m='2772030'>get</span> <span m='2772500'>the</span> <span m='2772660'>best</span>
  <span m='2772970'>performance</span> <span m='2773660'>they</span> <span m='2773790'>can</span>
  <span m='2774660'>in</span> <span m='2774880'>some</span> <span m='2775080'>kind</span>
  <span m='2775250'>of</span> <span m='2775330'>laboratory</span> <span m='2775950'>setting.</span>
  <span m='2776490'>It's</span> <span m='2776660'>not</span> <span m='2776920'>the</span>
  <span m='2777010'>same</span> <span m='2777790'>as</span> <span m='2778020'>when</span>
  <span m='2778190'>you're</span> <span m='2778370'>actually</span> <span m='2778680'>doing</span>
  <span m='2780810'>a</span> <span m='2780940'>real</span> <span m='2782160'>thing.</span>
  </p><p><span m='2782650'>So</span> <span m='2783470'>you have</span> <span m='2783650'>a</span>
  <span m='2783730'>choice</span> <span m='2784170'>here.</span> <span m='2789430'>There's</span>
  <span m='2789710'>kind</span> <span m='2789890'>of</span> <span m='2789960'>a tension</span>
  <span m='2790460'>here.</span> <span m='2795880'>You'd</span> <span m='2796120'>like</span>
  <span m='2796580'>to</span> <span m='2796850'>claim</span> <span m='2797310'>the</span>
  <span m='2797390'>mutex</span> <span m='2797830'>soon</span> <span m='2798250'>after</span>
  <span m='2798580'>it's</span> <span m='2798710'>released.</span> <span m='2799240'>And</span>
  <span m='2799360'>you're</span> <span m='2799450'>not</span> <span m='2799650'>going</span>
  <span m='2799750'>to</span> <span m='2799800'>get</span> <span m='2800090'>that</span>
  <span m='2800310'>if you</span> <span m='2800590'>yield.</span> <span m='2803600'>At</span>
  <span m='2803710'>the</span> <span m='2803790'>same</span> <span m='2804120'>time,</span>
  <span m='2805040'>you</span> <span m='2805170'>want</span> <span m='2805290'>to</span>
  <span m='2805330'>behave</span> <span m='2805720'>nicely</span> <span m='2807080'>and</span>
  <span m='2807240'>waste</span> <span m='2807620'>few</span> <span m='2807810'>cycles.</span>
  <span m='2810530'>So</span> <span m='2810670'>what's</span> <span m='2810780'>the</span>
  <span m='2810880'>strategy</span> <span m='2813380'>for</span> <span m='2813820'>being</span>
  <span m='2814030'>able</span> <span m='2814180'>to</span> <span m='2814220'>accomplish</span>
  <span m='2814740'>both</span> <span m='2815040'>of</span> <span m='2815110'>these</span>
  <span m='2815390'>goals?</span> </p><p><span m='2817260'>So</span> <span m='2817460'>one</span>
  <span m='2817660'>of</span> <span m='2817740'>these</span> <span m='2817970'>goals</span>
  <span m='2818370'>is</span> <span m='2818870'>the</span> <span m='2819300'>spinning</span>
  <span m='2819840'>mutex</span> <span m='2820570'>does</span> <span m='2820800'>a</span>
  <span m='2820850'>great</span> <span m='2821090'>job</span> <span m='2821430'>of</span>
  <span m='2821570'>claiming</span> <span m='2822080'>the</span> <span m='2822190'>mutex</span>
  <span m='2822480'>soon</span> <span m='2822590'>after</span> <span m='2822820'>it's</span>
  <span m='2822910'>released.</span> <span m='2823870'>The</span> <span m='2824320'>yielding</span>
  <span m='2825340'>mutex</span> <span m='2825800'>behaves</span> <span m='2826190'>nicely</span>
  <span m='2826630'>and wastes</span> <span m='2826970'>few</span> <span m='2827120'>cycles.</span>
  <span m='2829630'>Is</span> <span m='2829830'>there</span> <span m='2829910'>the</span>
  <span m='2830010'>best</span> <span m='2830310'>of</span> <span m='2830350'>both</span>
  <span m='2830590'>worlds?</span> <span m='2830830'>There's</span> <span m='2830890'>certainly</span>
  <span m='2831210'>the</span> <span m='2831310'>worst</span> <span m='2831620'>of</span>
  <span m='2831660'>both</span> <span m='2831910'>worlds,</span> <span m='2832220'>right?</span>
  </p><p><span m='2835500'>What's</span> <span m='2835690'>the</span> <span m='2835770'>best</span>
  <span m='2836080'>of</span> <span m='2836130'>both</span> <span m='2836370'>worlds?</span>
  <span m='2839710'>How</span> <span m='2839850'>might</span> <span m='2840090'>we</span>
  <span m='2841810'>accomplish</span> <span m='2842340'>both</span> <span m='2842540'>of</span>
  <span m='2842620'>these</span> <span m='2842840'>goals</span> <span m='2844330'>with</span>
  <span m='2844570'>small</span> <span m='2844910'>modification</span> <span m='2845650'>to</span>
  <span m='2845790'>the</span> <span m='2846840'>locking</span> <span m='2847260'>code?</span>
  <span m='2856990'>So</span> <span m='2857110'>it</span> <span m='2857210'>turns</span>
  <span m='2857470'>out</span> <span m='2857770'>you can</span> <span m='2857850'>get
  within</span> <span m='2858050'>a</span> <span m='2858100'>factor</span> <span m='2858520'>of</span>
  <span m='2858660'>two</span> <span m='2858980'>of</span> <span m='2859100'>optimal.</span>
  <span m='2867130'>How</span> <span m='2867280'>might</span> <span m='2867510'>you</span>
  <span m='2867570'>do</span> <span m='2867710'>that</span> <span m='2871290'>while</span>
  <span m='2871460'>wasting</span> <span m='2871910'>few</span> <span m='2872140'>cycles?</span>
  </p><p><span m='2875790'>So</span> <span m='2875920'>here's</span> <span m='2876180'>the</span>
  <span m='2876290'>idea.</span> <span m='2877920'>Spin</span> <span m='2878290'>for</span>
  <span m='2878380'>a</span> <span m='2878470'>little</span> <span m='2878710'>while,</span>
  <span m='2881400'>and</span> <span m='2881640'>then,</span> <span m='2882760'>if</span>
  <span m='2882970'>after</span> <span m='2883300'>a</span> <span m='2883340'>little</span>
  <span m='2883560'>while</span> <span m='2887030'>you</span> <span m='2887230'>didn't</span>
  <span m='2888830'>manage</span> <span m='2889220'>to</span> <span m='2889310'>access</span>
  <span m='2889890'>the</span> <span m='2890760'>mutex,</span> <span m='2891360'>then</span>
  <span m='2891580'>yield.</span> <span m='2894480'>So</span> <span m='2894670'>that
  if</span> <span m='2894920'>the</span> <span m='2895060'>new</span> <span m='2895240'>mutex</span>
  <span m='2895530'>was</span> <span m='2895680'>right</span> <span m='2895930'>there</span>
  <span m='2896130'>available</span> <span m='2896660'>to</span> <span m='2896760'>be</span>
  <span m='2896910'>accessed,</span> <span m='2897460'>you</span> <span m='2897570'>could</span>
  <span m='2897710'>access</span> <span m='2898150'>it,</span> <span m='2898540'>but</span>
  <span m='2899190'>you</span> <span m='2899300'>don't</span> <span m='2899500'>spin</span>
  <span m='2899900'>for</span> <span m='2900040'>an</span> <span m='2900100'>indefinite</span>
  <span m='2900600'>amount</span> <span m='2900900'>of</span> <span m='2900990'>time.</span>
  <span m='2903390'>So</span> <span m='2903560'>the</span> <span m='2903650'>question</span>
  <span m='2903980'>is,</span> <span m='2904080'>how</span> <span m='2904250'>long</span>
  <span m='2904540'>do you</span> <span m='2904760'>spin?</span> <span m='2907490'>So
  we're</span> <span m='2907760'>going to</span> <span m='2907960'>spin for</span>
  <span m='2908100'>a little</span> <span m='2908240'>while</span> <span m='2909280'>and</span>
  <span m='2909430'>then</span> <span m='2909590'>yield.</span> <span m='2910020'>Yeah?</span>
  </p><p><span m='2910360'>AUDIENCE:</span> <span m='2910840'>[INAUDIBLE].</span>
  </p><p><span m='2912760'>PROFESSOR:</span> <span m='2913240'>Yeah,</span> <span
  m='2913540'>exactly.</span> <span m='2914950'>So</span> <span m='2915090'>what</span>
  <span m='2915210'>you</span> <span m='2915290'>do</span> <span m='2915590'>is</span>
  <span m='2916370'>you spin</span> <span m='2916750'>for</span> <span m='2916870'>basically</span>
  <span m='2917500'>as</span> <span m='2917630'>long</span> <span m='2917940'>as</span>
  <span m='2918030'>a</span> <span m='2918120'>context</span> <span m='2918700'>switch</span>
  <span m='2918920'>takes.</span> <span m='2921980'>So</span> <span m='2922230'>if</span>
  <span m='2922310'>you</span> <span m='2922430'>spin</span> <span m='2922810'>for</span>
  <span m='2922960'>as</span> <span m='2923070'>long</span> <span m='2923370'>as</span>
  <span m='2923440'>it</span> <span m='2923560'>takes</span> <span m='2923880'>to</span>
  <span m='2923970'>do</span> <span m='2924140'>a</span> <span m='2924210'>context</span>
  <span m='2924760'>switch</span> <span m='2925430'>and</span> <span m='2925520'>then</span>
  <span m='2925650'>do</span> <span m='2925760'>a</span> <span m='2925830'>context</span>
  <span m='2926480'>switch,</span> <span m='2927460'>if</span> <span m='2927740'>the</span>
  <span m='2928470'>mutex</span> <span m='2928760'>became</span> <span m='2929090'>immediately</span>
  <span m='2929600'>available,</span> <span m='2930630'>well,</span> <span m='2930740'>you're</span>
  <span m='2930880'>only</span> <span m='2931050'>going to</span> <span m='2931190'>wait</span>
  <span m='2931530'>double</span> <span m='2931880'>what</span> <span m='2932060'>you</span>
  <span m='2932150'>would</span> <span m='2932280'>have</span> <span m='2932400'>waited.</span>
  <span m='2935260'>And</span> <span m='2935420'>if</span> <span m='2935530'>in</span>
  <span m='2935660'>the</span> <span m='2935770'>meantime</span> <span m='2937620'>during</span>
  <span m='2937960'>that</span> <span m='2938230'>first</span> <span m='2938500'>part</span>
  <span m='2938780'>where</span> <span m='2938890'>you're</span> <span m='2939010'>spinning</span>
  <span m='2939400'>it</span> <span m='2939510'>becomes</span> <span m='2939880'>available,</span>
  <span m='2940430'>you're</span> <span m='2940590'>not</span> <span m='2940780'>waiting</span>
  <span m='2941090'>at</span> <span m='2941160'>all</span> <span m='2941770'>any</span>
  <span m='2941970'>longer</span> <span m='2942270'>than</span> <span m='2942390'>you</span>
  <span m='2942470'>actually</span> <span m='2942780'>have</span> <span m='2943070'>to.</span>
  </p><p><span m='2943570'>So</span> <span m='2943770'>in</span> <span m='2943840'>both</span>
  <span m='2944140'>cases,</span> <span m='2944910'>you're</span> <span m='2945240'>waiting</span>
  <span m='2945630'>at</span> <span m='2945710'>most</span> <span m='2946100'>a</span>
  <span m='2946150'>factor</span> <span m='2946540'>of</span> <span m='2946630'>two.</span>
  <span m='2946950'>In</span> <span m='2947240'>one</span> <span m='2947490'>case,</span>
  <span m='2947630'>you're</span> <span m='2948190'>waiting</span> <span m='2948440'>exactly</span>
  <span m='2948900'>the</span> <span m='2949010'>right.</span> <span m='2949580'>The</span>
  <span m='2949730'>other,</span> <span m='2949890'>you</span> <span m='2950020'>can</span>
  <span m='2950150'>actually</span> <span m='2950720'>wait</span> <span m='2950840'>a</span>
  <span m='2950950'>factor</span> <span m='2951290'>of</span> <span m='2951360'>two.</span>
  <span m='2952510'>So</span> <span m='2952650'>this</span> <span m='2952830'>is a</span>
  <span m='2953020'>classic</span> <span m='2954530'>amortized</span> <span m='2955270'>kind</span>
  <span m='2955430'>of</span> <span m='2955580'>argument,</span> <span m='2957460'>that</span>
  <span m='2957910'>you</span> <span m='2958040'>can</span> <span m='2958220'>amortize</span>
  <span m='2959090'>the</span> <span m='2960220'>cost</span> <span m='2960570'>of</span>
  <span m='2960610'>the</span> <span m='2960690'>spinning</span> <span m='2960980'>to</span>
  <span m='2961380'>the</span> <span m='2961500'>context</span> <span m='2962000'>switch.</span>
  </p><p><span m='2962680'>So</span> <span m='2962950'>spin</span> <span m='2963370'>until</span>
  <span m='2964160'>you</span> <span m='2964300'>spend</span> <span m='2964600'>as</span>
  <span m='2964690'>much</span> <span m='2964950'>time</span> <span m='2965205'>as
  it would</span> <span m='2965460'>cost</span> <span m='2965790'>for a</span> <span
  m='2965930'>context</span> <span m='2966190'>switch.</span> <span m='2966940'>Then</span>
  <span m='2967240'>do</span> <span m='2967340'>the</span> <span m='2967430'>context</span>
  <span m='2967960'>switch.</span> <span m='2970130'>Yet</span> <span m='2970350'>another</span>
  <span m='2970630'>voodoo</span> <span m='2970940'>parameter.</span> <span m='2977440'>Yeah,</span>
  <span m='2977730'>so if</span> <span m='2977900'>the</span> <span m='2978060'>mutex</span>
  <span m='2978370'>is</span> <span m='2978680'>released</span> <span m='2979090'>while</span>
  <span m='2979250'>spinning,</span> <span m='2979700'>that's</span> <span m='2979940'>optimal.</span>
  <span m='2981720'>If</span> <span m='2982130'>the</span> <span m='2982440'>mutex</span>
  <span m='2982700'>is</span> <span m='2982780'>released</span> <span m='2983440'>after</span>
  <span m='2983700'>the</span> <span m='2983800'>yield,</span> <span m='2984140'>you're</span>
  <span m='2984280'>within</span> <span m='2985050'>twice</span> <span m='2985400'>optimal.</span>
  </p><p><span m='2988270'>Turns</span> <span m='2988590'>out</span> <span m='2989350'>that</span>
  <span m='2989630'>2</span> <span m='2989820'>is</span> <span m='2989960'>not</span>
  <span m='2990270'>the</span> <span m='2990400'>optimal</span> <span m='2990880'>value.</span>
  <span m='2992820'>There's</span> <span m='2993010'>a</span> <span m='2993080'>randomized</span>
  <span m='2993720'>algorithm</span> <span m='2994280'>that</span> <span m='2994500'>makes</span>
  <span m='2994840'>it</span> <span m='2995520'>e</span> <span m='2995810'>over</span>
  <span m='2996170'>e</span> <span m='2996340'>minus</span> <span m='2996720'>1</span>
  <span m='2997130'>competitive</span> <span m='2998900'>where</span> <span m='2999230'>e</span>
  <span m='2999990'>is</span> <span m='3000240'>the</span> <span m='3000330'>base</span>
  <span m='3000700'>of</span> <span m='3000790'>the</span> <span m='3000900'>natural</span>
  <span m='3001690'>logarithm.</span> <span m='3005620'>So</span> <span m='3006630'>2.7</span>
  <span m='3008160'>divided</span> <span m='3008600'>by</span> <span m='3008800'>1.7,</span>
  <span m='3010750'>which</span> <span m='3010960'>is</span> <span m='3011070'>what?</span>
  <span m='3012990'>Who's</span> <span m='3013210'>got</span> <span m='3013320'>a</span>
  <span m='3013360'>calculator?</span> <span m='3014850'>2.7</span> <span m='3015470'>divided</span>
  <span m='3015790'>by</span> <span m='3015900'>1.7</span> <span m='3016720'>is--</span>
  <span m='3017150'>I</span> <span m='3017230'>should</span> <span m='3017490'>have</span>
  <span m='3017950'>calculated</span> <span m='3018400'>this</span> <span m='3018590'>out.</span>
  </p><p><span m='3018760'>AUDIENCE:</span> <span m='3019150'>[INAUDIBLE]</span> </p><p><span
  m='3019930'>PROFESSOR:</span> <span m='3020320'>It's about</span> <span m='3020570'>1.6.</span>
  <span m='3021470'>Good.</span> <span m='3021910'>So</span> <span m='3022200'>it's</span>
  <span m='3022400'>better</span> <span m='3022730'>than</span> <span m='3022910'>2.</span>
  <span m='3026980'>People</span> <span m='3027290'>analyze</span> <span m='3027660'>these</span>
  <span m='3027930'>things,</span> <span m='3028250'>right?</span> <span m='3030021'>So</span>
  <span m='3030450'>any</span> <span m='3030660'>questions</span> <span m='3031230'>about</span>
  <span m='3031620'>implementation</span> <span m='3032890'>of</span> <span m='3033990'>locks?</span>
  <span m='3034250'>There are</span> <span m='3034350'>many</span> <span m='3034620'>other</span>
  <span m='3034790'>ways</span> <span m='3035110'>of</span> <span m='3035180'>implementing</span>
  <span m='3035650'>locks.</span> <span m='3036030'>There are</span> <span m='3036360'>other</span>
  <span m='3036600'>instructions</span> <span m='3037210'>that</span> <span m='3037390'>people</span>
  <span m='3037570'>use.</span> <span m='3039210'>They</span> <span m='3039350'>do</span>
  <span m='3039530'>things</span> <span m='3039820'>like</span> <span m='3040010'>compare-and-swap</span>
  <span m='3041100'>is</span> <span m='3041300'>another</span> <span m='3042780'>operation</span>
  <span m='3043035'>that's</span> <span m='3043290'>used.</span> </p><p><span m='3043830'>There</span>
  <span m='3044020'>are</span> <span m='3044130'>some</span> <span m='3044380'>machines</span>
  <span m='3044810'>have</span> <span m='3045520'>an</span> <span m='3045650'>operation</span>
  <span m='3046110'>called</span> <span m='3047100'>load-linked/store-conditional,</span>
  <span m='3049270'>which</span> <span m='3049630'>is</span> <span m='3049810'>not</span>
  <span m='3050060'>on</span> <span m='3050470'>the</span> <span m='3050850'>x86</span>
  <span m='3051290'>architecture,</span> <span m='3051810'>but</span> <span m='3051970'>it</span>
  <span m='3052060'>is</span> <span m='3052250'>on</span> <span m='3052390'>other</span>
  <span m='3052580'>architectures.</span> <span m='3053590'>You'll</span> <span m='3053740'>see</span>
  <span m='3053890'>a</span> <span m='3053960'>lot</span> <span m='3054180'>of</span>
  <span m='3054280'>other</span> <span m='3054470'>things</span> <span m='3054870'>of</span>
  <span m='3055020'>doing</span> <span m='3055250'>some</span> <span m='3055460'>kind</span>
  <span m='3055640'>of</span> <span m='3055720'>atomic</span> <span m='3056170'>operation</span>
  <span m='3057090'>to</span> <span m='3057210'>implement</span> <span m='3057600'>a</span>
  <span m='3057650'>lock.</span> <span m='3059130'>Uniformly,</span> <span m='3059870'>they're</span>
  <span m='3060030'>expensive</span> <span m='3061040'>compared</span> <span m='3061550'>to</span>
  <span m='3062630'>register</span> <span m='3063110'>operations</span> <span m='3063670'>in</span>
  <span m='3063760'>particular</span> <span m='3064280'>or</span> <span m='3064430'>even</span>
  <span m='3064870'>L1</span> <span m='3065040'>accesses,</span> <span m='3065750'>typically,</span>
  <span m='3066160'>in</span> <span m='3066250'>particular.</span> <span m='3068760'>Any</span>
  <span m='3068950'>questions?</span> </p><p><span m='3072860'>So</span> <span m='3073070'>now</span>
  <span m='3073310'>that</span> <span m='3073410'>we've</span> <span m='3073530'>decided</span>
  <span m='3074110'>that</span> <span m='3074210'>we're</span> <span m='3074310'>going</span>
  <span m='3074440'>to</span> <span m='3074480'>use</span> <span m='3074840'>mutexes,</span>
  <span m='3075810'>and</span> <span m='3076380'>we</span> <span m='3076700'>understand</span>
  <span m='3077035'>we're</span> <span m='3077370'>writing</span> <span m='3077630'>non-deterministic</span>
  <span m='3078520'>code</span> <span m='3079330'>and</span> <span m='3079490'>so</span>
  <span m='3079680'>forth,</span> <span m='3079980'>well,</span> <span m='3080150'>it</span>
  <span m='3080250'>turns</span> <span m='3080510'>out</span> <span m='3080770'>there</span>
  <span m='3080900'>are</span> <span m='3080970'>a</span> <span m='3081000'>host</span>
  <span m='3082090'>of</span> <span m='3082310'>other</span> <span m='3082590'>system</span>
  <span m='3082990'>anomalies</span> <span m='3083620'>that</span> <span m='3083720'>occur.</span>
  <span m='3084520'>So</span> <span m='3084700'>locks</span> <span m='3085090'>are</span>
  <span m='3085210'>like,</span> <span m='3085620'>they're</span> <span m='3085915'>this</span>
  <span m='3086210'>really</span> <span m='3086710'>evil</span> <span m='3088550'>mechanism</span>
  <span m='3089120'>that</span> <span m='3089240'>works</span> <span m='3089530'>really</span>
  <span m='3089910'>well.</span> <span m='3091360'>It</span> <span m='3091570'>feels</span>
  <span m='3091880'>so</span> <span m='3092100'>good</span> <span m='3092380'>that</span>
  <span m='3092490'>nobody</span> <span m='3092740'>wants</span> <span m='3092980'>to</span>
  <span m='3093090'>stop</span> <span m='3093420'>using</span> <span m='3093800'>it,</span>
  <span m='3093900'>even</span> <span m='3094210'>though--</span> <span m='3096510'>but</span>
  <span m='3096670'>nobody</span> <span m='3096950'>has</span> <span m='3097170'>better</span>
  <span m='3097480'>ideas.</span> </p><p><span m='3097880'>One</span> <span m='3098020'>of</span>
  <span m='3098060'>the</span> <span m='3098290'>most</span> <span m='3098620'>interesting</span>
  <span m='3099090'>ideas</span> <span m='3099520'>in</span> <span m='3099620'>recent</span>
  <span m='3100310'>memory</span> <span m='3101310'>is</span> <span m='3102310'>the</span>
  <span m='3102440'>idea</span> <span m='3102690'>of</span> <span m='3102770'>using</span>
  <span m='3103090'>what's</span> <span m='3103270'>called</span> <span m='3103510'>&quot;transactional</span>
  <span m='3104250'>memory,&quot;</span> <span m='3105650'>which</span> <span m='3105940'>is</span>
  <span m='3106080'>basically</span> <span m='3106580'>where</span> <span m='3106780'>memory</span>
  <span m='3107640'>operates</span> <span m='3108060'>like</span> <span m='3108220'>a</span>
  <span m='3108250'>database</span> <span m='3108800'>transaction.</span> <span m='3110100'>And
  it's</span> <span m='3110340'>allowed</span> <span m='3110700'>to</span> <span m='3110830'>abort,</span>
  <span m='3111320'>in</span> <span m='3111510'>which</span> <span m='3111690'>case</span>
  <span m='3111900'>you</span> <span m='3112030'>roll</span> <span m='3112320'>it</span>
  <span m='3112400'>back</span> <span m='3112730'>and</span> <span m='3112850'>retry</span>
  <span m='3113340'>it.</span> <span m='3115520'>Yet,</span> <span m='3115970'>transactional</span>
  <span m='3116520'>memory</span> <span m='3116800'>has</span> <span m='3117020'>a</span>
  <span m='3117070'>host</span> <span m='3117420'>of</span> <span m='3117500'>issues</span>
  <span m='3117970'>with</span> <span m='3118150'>it,</span> <span m='3118790'>and</span>
  <span m='3119280'>still</span> <span m='3119620'>people</span> <span m='3119870'>use</span>
  <span m='3120070'>locks.</span> </p><p><span m='3126170'>So</span> <span m='3126330'>let's</span>
  <span m='3126540'>talk</span> <span m='3126860'>about</span> <span m='3127180'>some</span>
  <span m='3127350'>of</span> <span m='3127390'>the</span> <span m='3127480'>bad</span>
  <span m='3127870'>things</span> <span m='3128160'>that</span> <span m='3128250'>happen</span>
  <span m='3128610'>when</span> <span m='3128810'>you</span> <span m='3129300'>start</span>
  <span m='3130020'>doing</span> <span m='3130280'>locks.</span> <span m='3131070'>I'm
  going to</span> <span m='3131120'>talk</span> <span m='3131340'>about</span> <span
  m='3131520'>three</span> <span m='3131780'>of</span> <span m='3131980'>them,</span>
  <span m='3132480'>deadlock,</span> <span m='3134360'>convoying,</span> <span m='3135430'>and</span>
  <span m='3135690'>contention.</span> <span m='3138230'>So</span> <span m='3138410'>deadlock</span>
  <span m='3138910'>is</span> <span m='3139030'>probably</span> <span m='3139300'>the</span>
  <span m='3139370'>most</span> <span m='3140140'>important</span> <span m='3140650'>one,</span>
  <span m='3140910'>because</span> <span m='3142480'>it</span> <span m='3142760'>has</span>
  <span m='3143030'>to</span> <span m='3143120'>do</span> <span m='3143200'>with</span>
  <span m='3143330'>correctness.</span> <span m='3144665'>So</span> <span m='3145020'>you</span>
  <span m='3145180'>can</span> <span m='3145340'>have</span> <span m='3145500'>coded--</span>
  <span m='3145880'>in</span> <span m='3145960'>fact,</span> <span m='3146180'>I've</span>
  <span m='3146320'>seen</span> <span m='3146550'>people</span> <span m='3146890'>with</span>
  <span m='3147030'>very</span> <span m='3147270'>fast</span> <span m='3147640'>code</span>
  <span m='3148610'>that</span> <span m='3148760'>has</span> <span m='3149410'>deadlock</span>
  <span m='3149850'>potential</span> <span m='3150330'>in</span> <span m='3150480'>it.</span>
  <span m='3151360'>It's like,</span> <span m='3151590'>if</span> <span m='3151720'>you</span>
  <span m='3151850'>deadlock,</span> <span m='3153240'>then</span> <span m='3153460'>your</span>
  <span m='3153630'>average</span> <span m='3154080'>running</span> <span m='3154360'>time</span>
  <span m='3154830'>is</span> <span m='3155040'>infinite</span> <span m='3156820'>if</span>
  <span m='3157020'>there's</span> <span m='3157190'>a</span> <span m='3157230'>possibility</span>
  <span m='3157860'>of a</span> <span m='3157960'>deadlock,</span> <span m='3158480'>right?</span>
  <span m='3158810'>Because</span> <span m='3158990'>you're</span> <span m='3159250'>averaging</span>
  <span m='3159890'>infinity</span> <span m='3160500'>with</span> <span m='3160690'>everything</span>
  <span m='3161200'>else</span> <span m='3161440'>that</span> <span m='3161530'>you</span>
  <span m='3161600'>might</span> <span m='3161830'>run.</span> </p><p><span m='3164410'>So</span>
  <span m='3164690'>it's</span> <span m='3164840'>not</span> <span m='3165150'>good</span>
  <span m='3165400'>to</span> <span m='3165750'>have</span> <span m='3167010'>deadlock</span>
  <span m='3167470'>in</span> <span m='3167560'>your</span> <span m='3167700'>code,</span>
  <span m='3168260'>regardless.</span> <span m='3170400'>It's</span> <span m='3170520'>kind</span>
  <span m='3170690'>of</span> <span m='3170770'>like</span> <span m='3171390'>your</span>
  <span m='3171580'>code</span> <span m='3171850'>seg</span> <span m='3172140'>faulting.</span>
  <span m='3172970'>No</span> <span m='3173270'>decent</span> <span m='3173870'>code</span>
  <span m='3174320'>should</span> <span m='3174620'>seg fault.</span> <span m='3175110'>It
  should</span> <span m='3175290'>always</span> <span m='3175560'>catch</span> <span
  m='3175850'>its</span> <span m='3175990'>own</span> <span m='3176290'>errors</span>
  <span m='3176960'>and</span> <span m='3177190'>terminate</span> <span m='3178290'>gracefully.</span>
  <span m='3179350'>It shouldn't</span> <span m='3179790'>just</span> <span m='3179990'>seg</span>
  <span m='3180220'>fault</span> <span m='3180490'>in</span> <span m='3180610'>some</span>
  <span m='3180990'>circumstance.</span> <span m='3182600'>Similarly,</span> <span
  m='3183240'>your</span> <span m='3183370'>code</span> <span m='3183620'>should</span>
  <span m='3183780'>not</span> <span m='3184020'>deadlock.</span> </p><p><span m='3187190'>So</span>
  <span m='3189170'>here's</span> <span m='3189420'>sort</span> <span m='3189620'>of</span>
  <span m='3189690'>a</span> <span m='3189780'>classical</span> <span m='3190470'>instance</span>
  <span m='3191140'>of</span> <span m='3191640'>deadlock.</span> <span m='3192540'>And</span>
  <span m='3193200'>deadlock</span> <span m='3193640'>typically</span> <span m='3194110'>occurs</span>
  <span m='3194540'>when</span> <span m='3194660'>you</span> <span m='3194770'>hold</span>
  <span m='3195170'>more</span> <span m='3195470'>than</span> <span m='3195690'>one</span>
  <span m='3196020'>lock</span> <span m='3196540'>at</span> <span m='3196640'>a</span>
  <span m='3196710'>time.</span> <span m='3198670'>So</span> <span m='3198930'>here,</span>
  <span m='3204000'>this</span> <span m='3204320'>guy is</span> <span m='3204660'>going</span>
  <span m='3204790'>to</span> <span m='3205220'>grab</span> <span m='3205520'>a</span>
  <span m='3205570'>lock</span> <span m='3206310'>A,</span> <span m='3206750'>going</span>
  <span m='3206840'>to</span> <span m='3206920'>grab</span> <span m='3207210'>a</span>
  <span m='3207250'>lock</span> <span m='3207620'>B,</span> <span m='3208760'>then</span>
  <span m='3208930'>unlock</span> <span m='3209420'>B,</span> <span m='3209710'>unlock</span>
  <span m='3210230'>A,</span> <span m='3210550'>and</span> <span m='3210770'>in</span>
  <span m='3211000'>there</span> <span m='3211150'>do</span> <span m='3211280'>a</span>
  <span m='3211350'>critical</span> <span m='3211710'>section.</span> <span m='3212050'>Why</span>
  <span m='3212300'>might</span> <span m='3212550'>I</span> <span m='3213010'>grab</span>
  <span m='3213590'>two</span> <span m='3213790'>locks?</span> <span m='3214650'>What's</span>
  <span m='3214780'>the</span> <span m='3214900'>circumstance</span> <span m='3215600'>where</span>
  <span m='3215780'>I</span> <span m='3215810'>might</span> <span m='3216060'>have</span>
  <span m='3216630'>code</span> <span m='3216990'>that</span> <span m='3217090'>looked</span>
  <span m='3217340'>very</span> <span m='3217570'>similar</span> <span m='3217930'>to</span>
  <span m='3217980'>this?</span> <span m='3220480'>Use</span> <span m='3220740'>case.</span>
  </p><p><span m='3221200'>AUDIENCE:</span> <span m='3221686'>Two objects?</span>
  </p><p><span m='3222172'>PROFESSOR:</span> <span m='3222660'>sorry?</span> </p><p><span
  m='3223156'>AUDIENCE:</span> <span m='3223652'>You need</span> <span m='3224150'>two
  objects.</span> </p><p><span m='3224250'>PROFESSOR:</span> <span m='3224510'>You
  need two</span> <span m='3224780'>objects.</span> <span m='3225430'>When</span>
  <span m='3225720'>might</span> <span m='3225940'>that</span> <span m='3226120'>occur?</span>
  </p><p><span m='3229442'>AUDIENCE:</span> <span m='3229919'>Account</span> <span
  m='3230396'>transactions.</span> </p><p><span m='3231827'>PROFESSOR:</span> <span
  m='3232310'>Yeah,</span> <span m='3232700'>account</span> <span m='3233010'>transactions.</span>
  <span m='3233780'>That's</span> <span m='3233910'>the</span> <span m='3234040'>classic</span>
  <span m='3234540'>one.</span> <span m='3236790'>You</span> <span m='3236960'>want</span>
  <span m='3237100'>to</span> <span m='3237160'>move</span> <span m='3237410'>something</span>
  <span m='3237800'>from</span> <span m='3237960'>this</span> <span m='3238160'>bank</span>
  <span m='3238390'>account</span> <span m='3238780'>to</span> <span m='3238840'>that</span>
  <span m='3239060'>bank</span> <span m='3239290'>account.</span> <span m='3240055'>And</span>
  <span m='3240450'>you</span> <span m='3240610'>want</span> <span m='3240720'>to</span>
  <span m='3240760'>make</span> <span m='3240950'>sure</span> <span m='3241110'>that
  as</span> <span m='3241350'>you're</span> <span m='3241500'>updating</span> <span
  m='3241930'>it,</span> <span m='3242080'>nothing</span> <span m='3242400'>else</span>
  <span m='3243060'>is</span> <span m='3243230'>occurring.</span> <span m='3244110'>Another</span>
  <span m='3244370'>place</span> <span m='3244680'>this</span> <span m='3244830'>comes</span>
  <span m='3245040'>up</span> <span m='3245180'>all</span> <span m='3245320'>the</span>
  <span m='3245400'>time</span> <span m='3245680'>is</span> <span m='3245770'>when</span>
  <span m='3245900'>you</span> <span m='3246000'>do</span> <span m='3246110'>graph</span>
  <span m='3246610'>algorithms.</span> <span m='3248420'>You</span> <span m='3248570'>always</span>
  <span m='3249000'>want</span> <span m='3249190'>to</span> <span m='3249240'>grab</span>
  <span m='3249650'>the</span> <span m='3249800'>edge</span> <span m='3250530'>and</span>
  <span m='3250770'>have</span> <span m='3251170'>the</span> <span m='3251280'>two</span>
  <span m='3251490'>vertices</span> <span m='3252140'>on</span> <span m='3252260'>each</span>
  <span m='3252450'>end</span> <span m='3252620'>of</span> <span m='3252670'>the</span>
  <span m='3252820'>edge</span> <span m='3253510'>not</span> <span m='3253790'>move</span>
  <span m='3254260'>while</span> <span m='3254410'>you</span> <span m='3254540'>do</span>
  <span m='3254670'>something</span> <span m='3255040'>across</span> <span m='3255470'>the</span>
  <span m='3255620'>edge.</span> <span m='3256970'>So</span> <span m='3257210'>lots</span>
  <span m='3257570'>of</span> <span m='3257630'>cases</span> <span m='3258060'>there.</span>
  </p><p><span m='3259870'>It</span> <span m='3260030'>turns</span> <span m='3260300'>out</span>
  <span m='3260450'>the</span> <span m='3260560'>order</span> <span m='3260910'>in</span>
  <span m='3260980'>which</span> <span m='3261200'>you</span> <span m='3261380'>unlock</span>
  <span m='3261860'>things</span> <span m='3262170'>doesn't</span> <span m='3262490'>matter,</span>
  <span m='3263790'>because</span> <span m='3264830'>you</span> <span m='3264960'>can</span>
  <span m='3265080'>always</span> <span m='3265500'>unlock</span> <span m='3265930'>something.</span>
  <span m='3266240'>You</span> <span m='3266570'>never</span> <span m='3266780'>hold</span>
  <span m='3267160'>up</span> <span m='3267380'>for</span> <span m='3267720'>unlocking.</span>
  <span m='3268350'>The</span> <span m='3268460'>problem</span> <span m='3269120'>with</span>
  <span m='3269280'>deadlock</span> <span m='3269750'>is</span> <span m='3269890'>generally</span>
  <span m='3270180'>how</span> <span m='3270320'>you</span> <span m='3270480'>acquire</span>
  <span m='3270930'>locks.</span> <span m='3271660'>So</span> <span m='3271840'>in</span>
  <span m='3271970'>this</span> <span m='3272160'>example,</span> <span m='3272720'>Thread
  2</span> <span m='3273390'>grabs</span> <span m='3273660'>Lock B,</span> <span m='3274310'>then</span>
  <span m='3274530'>grabs</span> <span m='3274880'>Lock A.</span> <span m='3277140'>So</span>
  <span m='3277300'>it</span> <span m='3277350'>might</span> <span m='3277650'>be,</span>
  <span m='3277810'>for</span> <span m='3277930'>example,</span> <span m='3278430'>that</span>
  <span m='3278820'>you</span> <span m='3278920'>have</span> <span m='3279120'>some</span>
  <span m='3279290'>random</span> <span m='3279660'>process</span> <span m='3280650'>that's</span>
  <span m='3280800'>at</span> <span m='3280950'>the</span> <span m='3281060'>node</span>
  <span m='3281340'>of</span> <span m='3281430'>a</span> <span m='3281480'>graph.</span>
  </p><p><span m='3282320'>And</span> <span m='3282450'>now</span> <span m='3282660'>it's</span>
  <span m='3282780'>going</span> <span m='3282880'>to</span> <span m='3282920'>grab</span>
  <span m='3283280'>a</span> <span m='3283320'>lock</span> <span m='3283930'>on</span>
  <span m='3284190'>the</span> <span m='3284440'>other</span> <span m='3284700'>end</span>
  <span m='3284920'>of</span> <span m='3285000'>an</span> <span m='3285070'>edge.</span>
  <span m='3285480'>But</span> <span m='3285940'>you</span> <span m='3286050'>might</span>
  <span m='3286200'>have</span> <span m='3286330'>the</span> <span m='3286420'>guy</span>
  <span m='3286660'>at the</span> <span m='3286840'>other</span> <span m='3287120'>end</span>
  <span m='3287390'>grabbing</span> <span m='3288550'>that</span> <span m='3288790'>vertex</span>
  <span m='3289380'>and</span> <span m='3289600'>then</span> <span m='3289760'>grabbing</span>
  <span m='3291520'>the</span> <span m='3291670'>one</span> <span m='3291860'>on</span>
  <span m='3291970'>your</span> <span m='3292210'>end.</span> <span m='3292850'>And</span>
  <span m='3292950'>that's</span> <span m='3293150'>basically</span> <span m='3293630'>the</span>
  <span m='3293740'>situation.</span> <span m='3294730'>So</span> <span m='3294850'>what</span>
  <span m='3294940'>happens</span> <span m='3295410'>is</span> <span m='3296090'>Thread
  1</span> <span m='3298600'>acquires</span> <span m='3298960'>a</span> <span m='3299000'>lock</span>
  <span m='3299190'>here.</span> <span m='3299990'>Thread 2</span> <span m='3300600'>acquires</span>
  <span m='3301020'>that</span> <span m='3301290'>lock.</span> <span m='3301890'>And</span>
  <span m='3302050'>now</span> <span m='3302240'>which</span> <span m='3302420'>one</span>
  <span m='3302620'>can</span> <span m='3302800'>go?</span> <span m='3304910'>Neither</span>
  <span m='3305260'>of</span> <span m='3305320'>them.</span> <span m='3305550'>You've</span>
  <span m='3305680'>got</span> <span m='3305840'>a</span> <span m='3305880'>deadlock.</span>
  <span m='3308110'>Ultimate</span> <span m='3308520'>loss</span> <span m='3308820'>of</span>
  <span m='3308910'>performance.</span> </p><p><span m='3311060'>So</span> <span m='3311960'>it's</span>
  <span m='3312150'>really</span> <span m='3312440'>a</span> <span m='3312490'>correctness</span>
  <span m='3313040'>issue.</span> <span m='3313280'>But</span> <span m='3313420'>you</span>
  <span m='3313500'>can</span> <span m='3313650'>view</span> <span m='3313890'>it,</span>
  <span m='3314070'>if</span> <span m='3314170'>you</span> <span m='3314320'>really</span>
  <span m='3314645'>say,</span> <span m='3314970'>oh,</span> <span m='3315410'>correctness,</span>
  <span m='3316210'>that's</span> <span m='3316480'>for</span> <span m='3316550'>sissies.</span>
  <span m='3317350'>We</span> <span m='3317480'>do</span> <span m='3317600'>performance.</span>
  <span m='3319340'>Well,</span> <span m='3321880'>it's</span> <span m='3322060'>still
  a</span> <span m='3322270'>performance</span> <span m='3322760'>issue,</span> <span
  m='3323000'>because</span> <span m='3323400'>it's</span> <span m='3323520'>the</span>
  <span m='3323630'>ultimate</span> <span m='3324000'>loss</span> <span m='3324290'>of</span>
  <span m='3324380'>performance.</span> <span m='3324970'>In</span> <span m='3325470'>fact,</span>
  <span m='3325670'>that's</span> <span m='3325830'>probably</span> <span m='3326020'>true</span>
  <span m='3326140'>of</span> <span m='3326220'>any</span> <span m='3326410'>correctness</span>
  <span m='3326900'>issue.</span> <span m='3327740'>No,</span> <span m='3327950'>that's</span>
  <span m='3328140'>not</span> <span m='3328290'>true.</span> <span m='3328470'>Sometimes</span>
  <span m='3328920'>you</span> <span m='3328980'>just</span> <span m='3329160'>get</span>
  <span m='3329280'>the</span> <span m='3329360'>wrong</span> <span m='3329610'>number.</span>
  <span m='3330700'>Here is</span> <span m='3330990'>a</span> <span m='3331060'>correctness</span>
  <span m='3331500'>issue</span> <span m='3331780'>that</span> <span m='3332700'>your</span>
  <span m='3332820'>code</span> <span m='3333070'>stops</span> <span m='3333420'>operating.</span>
  </p><p><span m='3337710'>So</span> <span m='3337970'>there</span> <span m='3338120'>are</span>
  <span m='3338160'>three</span> <span m='3338530'>conditions</span> <span m='3338870'>that</span>
  <span m='3339210'>are</span> <span m='3339320'>usually</span> <span m='3339660'>pointed</span>
  <span m='3340080'>to</span> <span m='3341410'>that</span> <span m='3341860'>you</span>
  <span m='3341950'>need</span> <span m='3342170'>for</span> <span m='3342340'>deadlock.</span>
  <span m='3343320'>The</span> <span m='3343440'>first</span> <span m='3343900'>is</span>
  <span m='3344250'>mutual</span> <span m='3344630'>exclusion.</span> <span m='3345220'>Each</span>
  <span m='3345490'>thread</span> <span m='3346420'>claims</span> <span m='3346790'>exclusive</span>
  <span m='3347390'>control</span> <span m='3348330'>over</span> <span m='3348580'>the</span>
  <span m='3348700'>resources</span> <span m='3349340'>that</span> <span m='3349440'>it</span>
  <span m='3349550'>holds,</span> <span m='3351120'>in this</span> <span m='3351290'>case,</span>
  <span m='3351890'>the</span> <span m='3352040'>resources</span> <span m='3352570'>being</span>
  <span m='3352860'>the</span> <span m='3352960'>locks.</span> <span m='3355540'>So</span>
  <span m='3355690'>there's</span> <span m='3355850'>got</span> <span m='3355950'>to</span>
  <span m='3356050'>be</span> <span m='3356150'>some</span> <span m='3356440'>resource</span>
  <span m='3356960'>that</span> <span m='3357030'>you're</span> <span m='3357220'>grabbing,</span>
  <span m='3358140'>and</span> <span m='3358270'>that</span> <span m='3358390'>you're</span>
  <span m='3358550'>the</span> <span m='3358730'>only</span> <span m='3358910'>one</span>
  <span m='3359110'>who</span> <span m='3359220'>gets</span> <span m='3359460'>to</span>
  <span m='3359560'>have</span> <span m='3359820'>it.</span> <span m='3360840'>So</span>
  <span m='3361140'>in</span> <span m='3361230'>this</span> <span m='3361390'>case,</span>
  <span m='3361630'>it</span> <span m='3361690'>would</span> <span m='3361820'>be</span>
  <span m='3361940'>the</span> <span m='3362050'>locks.</span> </p><p><span m='3363280'>The</span>
  <span m='3363500'>second</span> <span m='3363720'>is</span> <span m='3363860'>non-preemption.</span>
  <span m='3366310'>You</span> <span m='3366440'>don't</span> <span m='3366690'>let</span>
  <span m='3366890'>go</span> <span m='3367070'>of</span> <span m='3367150'>your</span>
  <span m='3367300'>resources</span> <span m='3368180'>until</span> <span m='3368720'>you</span>
  <span m='3368910'>complete</span> <span m='3369390'>your</span> <span m='3369550'>use</span>
  <span m='3369850'>of</span> <span m='3369950'>them.</span> <span m='3372370'>So</span>
  <span m='3372670'>that</span> <span m='3372800'>means</span> <span m='3374640'>you</span>
  <span m='3374780'>can't</span> <span m='3375010'>let</span> <span m='3375200'>go</span>
  <span m='3375390'>of a</span> <span m='3375430'>lock</span> <span m='3377770'>in</span>
  <span m='3378220'>a</span> <span m='3378350'>situation.</span> <span m='3378840'>If</span>
  <span m='3379280'>you're</span> <span m='3379390'>actually</span> <span m='3379630'>able</span>
  <span m='3379900'>to</span> <span m='3380000'>preempt--</span> <span m='3382060'>so</span>
  <span m='3383020'>this</span> <span m='3383240'>piece</span> <span m='3383430'>of
  code</span> <span m='3383800'>over there</span> <span m='3383990'>has</span> <span
  m='3384100'>grabbed</span> <span m='3384430'>locks,</span> <span m='3385870'>and</span>
  <span m='3386020'>now</span> <span m='3386190'>I</span> <span m='3386290'>can</span>
  <span m='3386500'>come</span> <span m='3386720'>in</span> <span m='3387000'>and</span>
  <span m='3387490'>take</span> <span m='3387760'>them</span> <span m='3387860'>away,</span>
  <span m='3388640'>then</span> <span m='3388780'>you</span> <span m='3388880'>may</span>
  <span m='3389000'>not</span> <span m='3389210'>have</span> <span m='3389340'>a</span>
  <span m='3389390'>deadlock</span> <span m='3389710'>potential.</span> <span m='3389975'>You</span>
  <span m='3390240'>may</span> <span m='3390390'>have</span> <span m='3390530'>other</span>
  <span m='3390760'>issues,</span> <span m='3391150'>but</span> <span m='3391290'>you</span>
  <span m='3391390'>won't</span> <span m='3391560'>have</span> <span m='3391630'>a</span>
  <span m='3391700'>deadlock</span> <span m='3391990'>potential.</span> </p><p><span
  m='3394090'>And</span> <span m='3394180'>the</span> <span m='3394260'>third</span>
  <span m='3394570'>one</span> <span m='3394750'>is</span> <span m='3394850'>circular</span>
  <span m='3395400'>waiting.</span> <span m='3396520'>You have</span> <span m='3396640'>a</span>
  <span m='3396710'>cycle</span> <span m='3397140'>of</span> <span m='3397270'>threads</span>
  <span m='3398030'>in</span> <span m='3398160'>which</span> <span m='3398360'>each</span>
  <span m='3398600'>thread</span> <span m='3398840'>is</span> <span m='3398990'>blocked</span>
  <span m='3399430'>waiting</span> <span m='3399730'>for</span> <span m='3399870'>resources</span>
  <span m='3400820'>held</span> <span m='3401080'>by</span> <span m='3401250'>the</span>
  <span m='3401490'>next</span> <span m='3401870'>thread</span> <span m='3402370'>in</span>
  <span m='3402540'>the</span> <span m='3402620'>cycle.</span> <span m='3404790'>So</span>
  <span m='3404950'>let</span> <span m='3405060'>me</span> <span m='3405220'>illustrate</span>
  <span m='3406300'>this</span> <span m='3406640'>with</span> <span m='3406890'>a</span>
  <span m='3407170'>very</span> <span m='3407480'>famous</span> <span m='3407930'>story</span>
  <span m='3408320'>that</span> <span m='3408480'>some</span> <span m='3408650'>of</span>
  <span m='3408750'>you</span> <span m='3408850'>may</span> <span m='3408980'>have</span>
  <span m='3409110'>seen,</span> <span m='3409740'>because</span> <span m='3410020'>it</span>
  <span m='3410120'>is</span> <span m='3410250'>so</span> <span m='3410850'>famous.</span>
  <span m='3412900'>It's</span> <span m='3413110'>the</span> <span m='3413260'>dining</span>
  <span m='3413670'>philosophers</span> <span m='3414840'>problem.</span> </p><p><span
  m='3415980'>It's</span> <span m='3416160'>an</span> <span m='3416310'>illustrative</span>
  <span m='3417040'>story</span> <span m='3417460'>a</span> <span m='3417510'>deadlock</span>
  <span m='3417835'>that</span> <span m='3418160'>was</span> <span m='3418370'>originally</span>
  <span m='3418890'>told</span> <span m='3419220'>by</span> <span m='3419400'>Tony</span>
  <span m='3419810'>Hoare,</span> <span m='3420850'>based</span> <span m='3421180'>on</span>
  <span m='3421310'>an</span> <span m='3421430'>examination</span> <span m='3422220'>question</span>
  <span m='3422670'>by</span> <span m='3423120'>Edsger</span> <span m='3423210'>Dijkstra.</span>
  <span m='3425160'>And</span> <span m='3425420'>the</span> <span m='3425490'>story</span>
  <span m='3425800'>has</span> <span m='3425950'>been</span> <span m='3426120'>embellished</span>
  <span m='3426640'>over</span> <span m='3426800'>the</span> <span m='3426890'>years</span>
  <span m='3427110'>by</span> <span m='3427260'>many</span> <span m='3427660'>retellers.</span>
  <span m='3429060'>It's</span> <span m='3429280'>one</span> <span m='3429440'>of</span>
  <span m='3429490'>these</span> <span m='3429700'>things</span> <span m='3429960'>that
  if</span> <span m='3430090'>you're a</span> <span m='3430250'>computer</span> <span
  m='3430610'>scientist,</span> <span m='3431440'>you</span> <span m='3431570'>should</span>
  <span m='3431780'>know</span> <span m='3432010'>this</span> <span m='3432110'>story</span>
  <span m='3432600'>just</span> <span m='3432810'>because</span> <span m='3433120'>everybody</span>
  <span m='3433600'>knows</span> <span m='3433910'>this</span> <span m='3434420'>story.</span>
  </p><p><span m='3436130'>So</span> <span m='3436270'>here's</span> <span m='3436530'>how</span>
  <span m='3436670'>the</span> <span m='3436760'>story</span> <span m='3437100'>goes,</span>
  <span m='3437590'>at</span> <span m='3438060'>least</span> <span m='3438360'>my</span>
  <span m='3438550'>version</span> <span m='3438890'>of</span> <span m='3438970'>it.</span>
  <span m='3439080'>I</span> <span m='3439180'>get</span> <span m='3439370'>to</span>
  <span m='3439470'>retell it</span> <span m='3439940'>now.</span> <span m='3441810'>So</span>
  <span m='3442200'>each</span> <span m='3442480'>of</span> <span m='3442560'>n</span>
  <span m='3442950'>philosophers</span> <span m='3443770'>needs</span> <span m='3444210'>the
  two</span> <span m='3444480'>chopsticks</span> <span m='3445130'>on</span> <span
  m='3445270'>either</span> <span m='3445530'>side</span> <span m='3446650'>of</span>
  <span m='3447180'>his</span> <span m='3447370'>or</span> <span m='3447460'>her</span>
  <span m='3447650'>plate</span> <span m='3448440'>to</span> <span m='3448730'>eat</span>
  <span m='3449350'>the</span> <span m='3449500'>noodles</span> <span m='3449910'>on</span>
  <span m='3450080'>the</span> <span m='3450160'>plate.</span> <span m='3451960'>So</span>
  <span m='3452330'>they're</span> <span m='3452440'>not</span> <span m='3452640'>worried</span>
  <span m='3452840'>about</span> <span m='3453600'>germs</span> <span m='3453970'>here,</span>
  <span m='3454130'>by</span> <span m='3454250'>the</span> <span m='3454360'>way.</span>
  </p><p><span m='3455940'>So you</span> <span m='3456180'>have</span> <span m='3456350'>five</span>
  <span m='3456670'>philosophers</span> <span m='3457260'>in</span> <span m='3457310'>this</span>
  <span m='3457460'>case</span> <span m='3457690'>sitting</span> <span m='3457940'>around</span>
  <span m='3458120'>the</span> <span m='3458300'>table.</span> <span m='3460250'>There
  are</span> <span m='3460390'>five</span> <span m='3460800'>chopsticks</span> <span
  m='3461410'>between</span> <span m='3461840'>them.</span> <span m='3462470'>In</span>
  <span m='3462620'>order</span> <span m='3462920'>to</span> <span m='3463330'>eat,</span>
  <span m='3463830'>they</span> <span m='3464030'>need</span> <span m='3464280'>to</span>
  <span m='3464370'>grab</span> <span m='3465160'>the</span> <span m='3465270'>two</span>
  <span m='3465440'>chopsticks</span> <span m='3466070'>on</span> <span m='3466200'>either</span>
  <span m='3466390'>side.</span> <span m='3467350'>Then</span> <span m='3467520'>they</span>
  <span m='3467650'>can</span> <span m='3467840'>eat.</span> <span m='3468200'>Then</span>
  <span m='3468340'>they</span> <span m='3468470'>put</span> <span m='3468640'>them</span>
  <span m='3468800'>down.</span> <span m='3470470'>So</span> <span m='3472840'>here's</span>
  <span m='3473380'>what</span> <span m='3473730'>philosopher</span> <span m='3474250'>i</span>
  <span m='3474470'>does.</span> <span m='3476310'>So</span> <span m='3476670'>in</span>
  <span m='3477100'>an infinite</span> <span m='3477240'>loop,</span> <span m='3480210'>the
  philosopher</span> <span m='3480700'>does</span> <span m='3481030'>thinking,</span>
  <span m='3482220'>because</span> <span m='3482410'>that's</span> <span m='3482610'>what</span>
  <span m='3482750'>philosophers</span> <span m='3483350'>do.</span> </p><p><span
  m='3484650'>Then</span> <span m='3490000'>it</span> <span m='3490270'>grabs</span>
  <span m='3490970'>the</span> <span m='3491580'>lock</span> <span m='3491910'>of</span>
  <span m='3492030'>chopstick i</span> <span m='3493480'>and</span> <span m='3493660'>grabs</span>
  <span m='3494110'>the</span> <span m='3494180'>lock</span> <span m='3494660'>of</span>
  <span m='3494950'>chopstick i</span> <span m='3495760'>plus</span> <span m='3496130'>1.</span>
  <span m='3496480'>That's</span> <span m='3496710'>the</span> <span m='3496790'>1.</span>
  <span m='3497020'>So if</span> <span m='3497140'>we</span> <span m='3497300'>index</span>
  <span m='3497700'>them,</span> <span m='3497830'>say,</span> <span m='3498100'>to</span>
  <span m='3498220'>the</span> <span m='3498300'>left</span> <span m='3498650'>of</span>
  <span m='3498710'>the</span> <span m='3498790'>plate,</span> <span m='3499580'>this</span>
  <span m='3499730'>is</span> <span m='3499850'>grabbing</span> <span m='3500220'>the</span>
  <span m='3500310'>chopstick</span> <span m='3500600'>to the</span> <span m='3500890'>left</span>
  <span m='3501310'>of</span> <span m='3501380'>your</span> <span m='3501510'>plate.</span>
  <span m='3502180'>This</span> <span m='3502340'>is</span> <span m='3502460'>grabbing</span>
  <span m='3502820'>the</span> <span m='3502920'>chopstick</span> <span m='3503340'>to</span>
  <span m='3503480'>the</span> <span m='3503550'>right</span> <span m='3503800'>of</span>
  <span m='3503870'>your</span> <span m='3504040'>plate.</span> <span m='3504930'>Then</span>
  <span m='3505110'>you</span> <span m='3505210'>can</span> <span m='3505400'>eat.</span>
  <span m='3506240'>Then</span> <span m='3506410'>you</span> <span m='3506520'>release</span>
  <span m='3506860'>your</span> <span m='3506990'>two</span> <span m='3507150'>chopsticks.</span>
  </p><p><span m='3510810'>So</span> <span m='3510970'>here,</span> <span m='3511440'>that's</span>
  <span m='3512270'>the</span> <span m='3512380'>code.</span> <span m='3512650'>And</span>
  <span m='3512760'>then</span> <span m='3512870'>you</span> <span m='3512950'>go</span>
  <span m='3513070'>back</span> <span m='3513290'>to</span> <span m='3513380'>thinking.</span>
  <span m='3516900'>I</span> <span m='3516990'>guess</span> <span m='3517150'>they</span>
  <span m='3517250'>have</span> <span m='3517350'>no</span> <span m='3517530'>other</span>
  <span m='3517680'>bodily</span> <span m='3518080'>functions.</span> <span m='3521990'>So</span>
  <span m='3522240'>the</span> <span m='3522350'>problem</span> <span m='3522830'>is,</span>
  <span m='3523110'>one</span> <span m='3523360'>day</span> <span m='3523620'>they</span>
  <span m='3523820'>all</span> <span m='3524220'>pick</span> <span m='3524460'>up</span>
  <span m='3525110'>their</span> <span m='3525280'>left</span> <span m='3525660'>chopsticks</span>
  <span m='3526550'>simultaneously.</span> <span m='3530200'>Now</span> <span m='3530470'>they</span>
  <span m='3530590'>go</span> <span m='3530800'>to</span> <span m='3530870'>look</span>
  <span m='3531130'>for</span> <span m='3531220'>their</span> <span m='3531360'>right</span>
  <span m='3531560'>chopstick.</span> <span m='3532080'>It's</span> <span m='3532240'>not</span>
  <span m='3532490'>there.</span> <span m='3533800'>So</span> <span m='3533950'>what</span>
  <span m='3534090'>happens?</span> <span m='3537150'>They</span> <span m='3537320'>starve</span>
  <span m='3540780'>because</span> <span m='3541240'>their</span> <span m='3541420'>code</span>
  <span m='3541790'>doesn't</span> <span m='3542100'>let</span> <span m='3542330'>them</span>
  <span m='3543620'>release--</span> <span m='3544520'>there's</span> <span m='3544810'>no</span>
  <span m='3544970'>preemption,</span> <span m='3546290'>so</span> <span m='3546450'>they</span>
  <span m='3546560'>can't</span> <span m='3546820'>release</span> <span m='3547200'>the</span>
  <span m='3547300'>chopstick</span> <span m='3547780'>they've</span> <span m='3547970'>already</span>
  <span m='3548220'>got.</span> </p><p><span m='3551510'>And</span> <span m='3551790'>we</span>
  <span m='3551920'>have</span> <span m='3552100'>a</span> <span m='3552170'>circular</span>
  <span m='3552700'>waiting.</span> <span m='3553090'>They have</span> <span m='3553280'>mutual</span>
  <span m='3553600'>exclusion.</span> <span m='3554130'>Only</span> <span m='3554320'>one</span>
  <span m='3554500'>of</span> <span m='3554570'>them</span> <span m='3554720'>can</span>
  <span m='3554830'>have</span> <span m='3554920'>a</span> <span m='3555000'>chopstick</span>
  <span m='3555480'>at</span> <span m='3555540'>a</span> <span m='3555620'>time.</span>
  <span m='3556570'>And</span> <span m='3556810'>we</span> <span m='3556890'>have</span>
  <span m='3557010'>a</span> <span m='3557060'>circular</span> <span m='3557550'>waiting</span>
  <span m='3557900'>thing,</span> <span m='3558100'>because</span> <span m='3558330'>everyone</span>
  <span m='3559210'>is</span> <span m='3559350'>waiting</span> <span m='3560320'>for</span>
  <span m='3560460'>the</span> <span m='3561180'>philosopher</span> <span m='3561830'>on</span>
  <span m='3561980'>the</span> <span m='3562050'>right.</span> <span m='3564320'>Is</span>
  <span m='3564440'>that</span> <span m='3564490'>clear to</span> <span m='3564810'>everybody?</span>
  <span m='3565510'>That's</span> <span m='3565750'>the</span> <span m='3565850'>dining</span>
  <span m='3566160'>philosophers</span> <span m='3566780'>problem.</span> </p><p><span
  m='3567470'>How</span> <span m='3567660'>do</span> <span m='3567720'>you</span>
  <span m='3567830'>fix</span> <span m='3568140'>this</span> <span m='3568340'>problem?</span>
  <span m='3571420'>What</span> <span m='3571600'>are</span> <span m='3571650'>solutions</span>
  <span m='3572300'>to</span> <span m='3573400'>fixing</span> <span m='3573740'>this</span>
  <span m='3573900'>problem?</span> <span m='3579390'>The</span> <span m='3579500'>problem</span>
  <span m='3579770'>being</span> <span m='3580030'>that</span> <span m='3580160'>you'd</span>
  <span m='3580300'>like</span> <span m='3580510'>them to</span> <span m='3580770'>eat</span>
  <span m='3581290'>indefinitely.</span> </p><p><span m='3581655'>AUDIENCE:</span>
  <span m='3582020'>You can</span> <span m='3582986'>index</span> <span m='3583469'>the</span>
  <span m='3583952'>chopstick</span> <span m='3584435'>and</span> <span m='3584918'>say
  that</span> <span m='3585401'>[INAUDIBLE].</span> </p><p><span m='3586850'>PROFESSOR:</span>
  <span m='3587340'>Yeah,</span> <span m='3587830'>you can</span> <span m='3587850'>pick</span>
  <span m='3588030'>the</span> <span m='3588110'>smaller</span> <span m='3588650'>index</span>
  <span m='3589130'>first.</span> <span m='3590000'>So</span> <span m='3590170'>in</span>
  <span m='3590260'>general,</span> <span m='3590600'>that</span> <span m='3590780'>means</span>
  <span m='3591020'>everybody</span> <span m='3591550'>would</span> <span m='3591700'>grab</span>
  <span m='3592020'>the</span> <span m='3592120'>one</span> <span m='3592330'>on</span>
  <span m='3592440'>their</span> <span m='3592550'>left,</span> <span m='3592980'>then</span>
  <span m='3593140'>the</span> <span m='3593230'>one on</span> <span m='3593420'>their</span>
  <span m='3593580'>right,</span> <span m='3593940'>except</span> <span m='3594360'>for</span>
  <span m='3594490'>the</span> <span m='3594630'>guy</span> <span m='3595640'>who's</span>
  <span m='3596030'>going</span> <span m='3596360'>between</span> <span m='3597880'>0</span>
  <span m='3598370'>and</span> <span m='3598510'>n</span> <span m='3598660'>minus</span>
  <span m='3598990'>1.</span> <span m='3600660'>They</span> <span m='3600800'>would</span>
  <span m='3600970'>do</span> <span m='3603400'>n</span> <span m='3603540'>minus</span>
  <span m='3603820'>1</span> <span m='3604070'>and</span> <span m='3604170'>then</span>
  <span m='3604340'>0.</span> <span m='3604850'>They</span> <span m='3604980'>would</span>
  <span m='3605110'>do</span> <span m='3605440'>n</span> <span m='3605620'>minus</span>
  <span m='3605920'>1</span> <span m='3606160'>first,</span> <span m='3606510'>and</span>
  <span m='3606660'>then</span> <span m='3606850'>0.</span> <span m='3608260'>Sorry.</span>
  <span m='3608780'>They</span> <span m='3608890'>would</span> <span m='3609040'>do</span>
  <span m='3609260'>0</span> <span m='3609650'>first,</span> <span m='3609980'>and</span>
  <span m='3610100'>then</span> <span m='3610270'>n</span> <span m='3610420'>minus</span>
  <span m='3610750'>1.</span> <span m='3611160'>[INAUDIBLE]</span> <span m='3612160'>Let</span>
  <span m='3612260'>me</span> <span m='3612340'>say</span> <span m='3612760'>that</span>
  <span m='3613150'>more</span> <span m='3613340'>precisely.</span> </p><p><span m='3614360'>So</span>
  <span m='3614520'>this</span> <span m='3614710'>is</span> <span m='3614850'>a</span>
  <span m='3614960'>classic</span> <span m='3615560'>way</span> <span m='3615700'>to</span>
  <span m='3615840'>prevent</span> <span m='3616260'>deadlock.</span> <span m='3618270'>Suppose</span>
  <span m='3618740'>that</span> <span m='3618840'>we</span> <span m='3618970'>can</span>
  <span m='3619350'>linearly</span> <span m='3619940'>order</span> <span m='3620400'>the</span>
  <span m='3620580'>mutexes</span> <span m='3622170'>in</span> <span m='3622260'>some</span>
  <span m='3622510'>order</span> <span m='3623250'>so</span> <span m='3623500'>that</span>
  <span m='3623670'>whenever a</span> <span m='3624110'>thread</span> <span m='3624560'>that</span>
  <span m='3624690'>holds</span> <span m='3625020'>a</span> <span m='3625100'>mutex</span>
  <span m='3625600'>Li</span> <span m='3626430'>and</span> <span m='3626550'>attempts</span>
  <span m='3626980'>to</span> <span m='3627070'>lock</span> <span m='3627570'>another</span>
  <span m='3627900'>mutex</span> <span m='3628440'>Lj,</span> <span m='3630580'>we</span>
  <span m='3630740'>have</span> <span m='3631010'>it</span> <span m='3631240'>that</span>
  <span m='3631480'>Li</span> <span m='3632360'>goes</span> <span m='3632650'>before</span>
  <span m='3633080'>Lj</span> <span m='3633550'>in the</span> <span m='3633800'>ordering.</span>
  <span m='3635090'>Then</span> <span m='3635340'>no</span> <span m='3635570'>deadlock</span>
  <span m='3636080'>can</span> <span m='3636240'>occur.</span> </p><p><span m='3639890'>So</span>
  <span m='3640140'>always</span> <span m='3640590'>grab</span> <span m='3641110'>the</span>
  <span m='3641560'>resource</span> <span m='3642520'>so</span> <span m='3643630'>if</span>
  <span m='3643860'>they</span> <span m='3643980'>can all</span> <span m='3644100'>order</span>
  <span m='3644810'>the</span> <span m='3644920'>resources--</span> <span m='3645530'>so</span>
  <span m='3645640'>they're</span> <span m='3645810'>always</span> <span m='3646150'>grabbing</span>
  <span m='3646680'>them</span> <span m='3647230'>in</span> <span m='3648750'>some</span>
  <span m='3649250'>subsequence</span> <span m='3650140'>of</span> <span m='3650320'>this</span>
  <span m='3650490'>order,</span> <span m='3651050'>so</span> <span m='3651400'>they're
  always</span> <span m='3651670'>grabbing</span> <span m='3652130'>one</span> <span
  m='3652290'>that's</span> <span m='3652470'>larger</span> <span m='3652910'>and</span>
  <span m='3652980'>larger</span> <span m='3653330'>and</span> <span m='3653410'>larger,</span>
  <span m='3654940'>and</span> <span m='3655620'>you're</span> <span m='3655710'>never</span>
  <span m='3655970'>going</span> <span m='3656210'>back</span> <span m='3656460'>and</span>
  <span m='3656530'>grabbing</span> <span m='3656860'>one</span> <span m='3657000'>smaller,</span>
  <span m='3657670'>than</span> <span m='3657790'>you</span> <span m='3657870'>have</span>
  <span m='3658020'>no</span> <span m='3658200'>deadlock.</span> <span m='3658960'>Here's</span>
  <span m='3659230'>why.</span> <span m='3660730'>Suppose</span> <span m='3661170'>you</span>
  <span m='3661430'>have</span> <span m='3661690'>a</span> <span m='3661750'>cycle</span>
  <span m='3662180'>of</span> <span m='3662260'>waiting.</span> <span m='3663010'>You</span>
  <span m='3663110'>have</span> <span m='3663230'>a</span> <span m='3663340'>deadlock</span>
  <span m='3663820'>has</span> <span m='3664030'>occurred.</span> </p><p><span m='3665160'>Let's</span>
  <span m='3665400'>look</span> <span m='3665730'>at</span> <span m='3665870'>the</span>
  <span m='3665960'>thread</span> <span m='3666350'>in</span> <span m='3666450'>the</span>
  <span m='3666540'>cycle</span> <span m='3666950'>that</span> <span m='3667090'>holds</span>
  <span m='3667450'>the</span> <span m='3667530'>largest</span> <span m='3668120'>mutex</span>
  <span m='3669000'>that's</span> <span m='3669170'>called</span> <span m='3669430'>Lmax</span>
  <span m='3670120'>in</span> <span m='3670250'>the ordering.</span> <span m='3670710'>So</span>
  <span m='3670980'>whatever</span> <span m='3671450'>is</span> <span m='3671710'>in</span>
  <span m='3671810'>the</span> <span m='3671900'>ordering.</span> <span m='3673090'>And</span>
  <span m='3673210'>suppose</span> <span m='3673610'>that it's</span> <span m='3673870'>waiting</span>
  <span m='3674330'>on</span> <span m='3674430'>a</span> <span m='3674450'>mutex</span>
  <span m='3674640'>L</span> <span m='3675330'>held</span> <span m='3675680'>by</span>
  <span m='3675860'>the</span> <span m='3676120'>next</span> <span m='3676380'>threat</span>
  <span m='3676670'>in</span> <span m='3676770'>the</span> <span m='3676850'>cycle.</span>
  <span m='3677350'>That's</span> <span m='3677600'>the</span> <span m='3677680'>condition.</span>
  </p><p><span m='3678640'>Well,</span> <span m='3679060'>then</span> <span m='3679230'>it</span>
  <span m='3679330'>must</span> <span m='3679620'>be</span> <span m='3679860'>that</span>
  <span m='3680060'>Lmax</span> <span m='3681700'>falls</span> <span m='3682030'>before</span>
  <span m='3682470'>L,</span> <span m='3682880'>because</span> <span m='3683270'>we're</span>
  <span m='3683460'>gathering</span> <span m='3684210'>them</span> <span m='3684470'>always</span>
  <span m='3685040'>in an</span> <span m='3685280'>increasing</span> <span m='3685820'>order.</span>
  <span m='3686930'>But</span> <span m='3687020'>that</span> <span m='3687270'>contradicts</span>
  <span m='3687830'>the</span> <span m='3687920'>fact</span> <span m='3688130'>that</span>
  <span m='3688380'>Lmax</span> <span m='3689350'>is</span> <span m='3689530'>the</span>
  <span m='3689620'>largest.</span> <span m='3692210'>So</span> <span m='3692530'>a</span>
  <span m='3692630'>deadlock</span> <span m='3693040'>cannot</span> <span m='3693410'>occur.</span>
  <span m='3696930'>Questions?</span> <span m='3705430'>Is this</span> <span m='3705590'>clear?</span>
  </p><p><span m='3706690'>Who's</span> <span m='3706870'>seen</span> <span m='3707050'>this</span>
  <span m='3707210'>before?</span> <span m='3708910'>A</span> <span m='3709320'>few</span>
  <span m='3709480'>people.</span> <span m='3709780'>OK.</span> <span m='3713030'>Is</span>
  <span m='3713150'>this</span> <span m='3713280'>clear?</span> <span m='3713820'>So</span>
  <span m='3714050'>if you</span> <span m='3714170'>grab</span> <span m='3714500'>them
  in</span> <span m='3714660'>increasing</span> <span m='3715180'>order,</span> <span
  m='3716600'>then</span> <span m='3716750'>there's</span> <span m='3716900'>always</span>
  <span m='3717170'>some</span> <span m='3717410'>guy</span> <span m='3717610'>that</span>
  <span m='3717720'>has</span> <span m='3717940'>the</span> <span m='3718020'>largest</span>
  <span m='3718510'>one,</span> <span m='3719350'>and</span> <span m='3719590'>nobody</span>
  <span m='3719990'>is</span> <span m='3720110'>holding</span> <span m='3720440'>one</span>
  <span m='3720590'>larger.</span> <span m='3721490'>So</span> <span m='3721670'>he</span>
  <span m='3721810'>can</span> <span m='3721950'>always</span> <span m='3722220'>grab</span>
  <span m='3722990'>the</span> <span m='3723090'>next</span> <span m='3723400'>one.</span>
  </p><p><span m='3725770'>So</span> <span m='3725960'>in</span> <span m='3726020'>this</span>
  <span m='3726250'>case of</span> <span m='3726650'>the</span> <span m='3726760'>dining</span>
  <span m='3727110'>philosophers,</span> <span m='3730900'>what</span> <span m='3731150'>we</span>
  <span m='3731280'>can</span> <span m='3731510'>do</span> <span m='3734110'>is</span>
  <span m='3734720'>grab</span> <span m='3737790'>the</span> <span m='3737910'>minimum</span>
  <span m='3739160'>of</span> <span m='3739370'>i</span> <span m='3739870'>and</span>
  <span m='3740090'>i</span> <span m='3740170'>plus</span> <span m='3740490'>1</span>
  <span m='3740720'>mod n</span> <span m='3742280'>and</span> <span m='3742490'>then</span>
  <span m='3742750'>the</span> <span m='3742840'>maximum</span> <span m='3743450'>of</span>
  <span m='3743590'>i</span> <span m='3743940'>and</span> <span m='3744130'>i</span>
  <span m='3744210'>plus</span> <span m='3744490'>1</span> <span m='3744690'>mod n.</span>
  <span m='3745120'>That</span> <span m='3745300'>gives</span> <span m='3745520'>us</span>
  <span m='3745700'>the</span> <span m='3745780'>same</span> <span m='3746300'>two</span>
  <span m='3746810'>chopsticks.</span> <span m='3748890'>And</span> <span m='3749040'>in</span>
  <span m='3749130'>fact,</span> <span m='3749460'>for</span> <span m='3749560'>most</span>
  <span m='3750040'>of</span> <span m='3750160'>the</span> <span m='3750550'>philosophers,</span>
  <span m='3751290'>it's</span> <span m='3751480'>exactly</span> <span m='3751990'>the</span>
  <span m='3752090'>same</span> <span m='3752410'>order.</span> <span m='3752770'>But
  for</span> <span m='3753090'>one</span> <span m='3753370'>guy,</span> <span m='3754820'>it's</span>
  <span m='3754990'>a</span> <span m='3755060'>different</span> <span m='3755330'>order.</span>
  <span m='3756830'>It</span> <span m='3757750'>ends</span> <span m='3758130'>up</span>
  <span m='3758300'>being</span> <span m='3759240'>the</span> <span m='3759360'>guy</span>
  <span m='3759630'>who</span> <span m='3760360'>would</span> <span m='3760520'>normally
  have</span> <span m='3760910'>done</span> <span m='3761890'>n</span> <span m='3762030'>minus</span>
  <span m='3762350'>1 and</span> <span m='3762620'>0.</span> </p><p><span m='3763060'>Instead,</span>
  <span m='3763310'>he</span> <span m='3763450'>does</span> <span m='3763720'>0,</span>
  <span m='3764050'>n</span> <span m='3764200'>minus</span> <span m='3764480'>1.</span>
  <span m='3764840'>So</span> <span m='3765040'>in</span> <span m='3765180'>some</span>
  <span m='3765390'>sense,</span> <span m='3766110'>it's</span> <span m='3766250'>like</span>
  <span m='3766390'>having</span> <span m='3766650'>a</span> <span m='3766710'>left-handed</span>
  <span m='3767350'>person</span> <span m='3767740'>at</span> <span m='3767850'>the</span>
  <span m='3767920'>table.</span> <span m='3769300'>You grab</span> <span m='3769460'>your</span>
  <span m='3769620'>left,</span> <span m='3769890'>then</span> <span m='3770040'>your</span>
  <span m='3770220'>right,</span> <span m='3770490'>except</span> <span m='3770750'>for</span>
  <span m='3770850'>one</span> <span m='3771140'>guy</span> <span m='3772220'>does</span>
  <span m='3772320'>right</span> <span m='3772630'>and</span> <span m='3772750'>then</span>
  <span m='3772880'>left.</span> <span m='3774030'>And</span> <span m='3774180'>that</span>
  <span m='3774380'>fixes</span> <span m='3774810'>it,</span> <span m='3775690'>OK?</span>
  <span m='3776290'>That fixes it.</span> <span m='3781060'>Good.</span> </p><p><span
  m='3781310'>So</span> <span m='3781420'>that's</span> <span m='3781670'>basically</span>
  <span m='3782120'>the</span> <span m='3782210'>dining</span> <span m='3782540'>philosophers</span>
  <span m='3783580'>problem.</span> <span m='3783865'>That's</span> <span m='3784150'>one</span>
  <span m='3784360'>way of</span> <span m='3784570'>fixing it.</span> <span m='3784880'>There
  are</span> <span m='3785010'>actually</span> <span m='3785370'>other</span> <span
  m='3785510'>ways</span> <span m='3785800'>of</span> <span m='3785890'>doing</span>
  <span m='3786180'>it.</span> <span m='3787150'>One</span> <span m='3787330'>of</span>
  <span m='3787370'>the</span> <span m='3787440'>problems</span> <span m='3787950'>with</span>
  <span m='3788080'>this</span> <span m='3788270'>particular</span> <span m='3788690'>solution</span>
  <span m='3789190'>is</span> <span m='3789310'>you</span> <span m='3789410'>still</span>
  <span m='3789710'>can have</span> <span m='3789850'>a</span> <span m='3789980'>long</span>
  <span m='3790350'>chain</span> <span m='3790660'>of</span> <span m='3790770'>waiting.</span>
  </p><p><span m='3793710'>So</span> <span m='3793920'>there</span> <span m='3794030'>are</span>
  <span m='3794120'>other</span> <span m='3794420'>schemes</span> <span m='3794950'>that</span>
  <span m='3795070'>you</span> <span m='3795210'>can</span> <span m='3795340'>use</span>
  <span m='3795730'>where,</span> <span m='3795980'>for</span> <span m='3796100'>example,</span>
  <span m='3797190'>if</span> <span m='3797460'>every</span> <span m='3797770'>other</span>
  <span m='3797970'>one</span> <span m='3799010'>grabs</span> <span m='3799460'>left</span>
  <span m='3799890'>and</span> <span m='3800000'>then</span> <span m='3800190'>right</span>
  <span m='3800560'>and</span> <span m='3800700'>then</span> <span m='3800870'>right</span>
  <span m='3801170'>and</span> <span m='3801310'>then</span> <span m='3801450'>left</span>
  <span m='3801890'>and then</span> <span m='3802130'>left</span> <span m='3802430'>and</span>
  <span m='3802550'>then</span> <span m='3802670'>right</span> <span m='3803050'>and
  then</span> <span m='3803250'>right</span> <span m='3803560'>and</span> <span m='3803640'>left</span>
  <span m='3803960'>and</span> <span m='3804060'>so</span> <span m='3804220'>forth,</span>
  <span m='3805030'>you</span> <span m='3805180'>can</span> <span m='3805310'>end</span>
  <span m='3805560'>up</span> <span m='3808660'>making</span> <span m='3808950'>it</span>
  <span m='3809050'>so</span> <span m='3809220'>that</span> <span m='3809400'>nobody</span>
  <span m='3809740'>has</span> <span m='3809990'>to</span> <span m='3810090'>wait</span>
  <span m='3810560'>to</span> <span m='3810640'>go</span> <span m='3811030'>all</span>
  <span m='3811440'>the</span> <span m='3811510'>way</span> <span m='3811660'>around</span>
  <span m='3811860'>the</span> <span m='3812050'>circle.</span> <span m='3812510'>Yeah?</span>
  </p><p><span m='3813278'>AUDIENCE:</span> <span m='3813736'>[INAUDIBLE]</span> </p><p><span
  m='3817400'>PROFESSOR:</span> <span m='3817860'>Well,</span> <span m='3818530'>that</span>
  <span m='3818720'>would</span> <span m='3818900'>be</span> <span m='3819080'>a</span>
  <span m='3819370'>preemption</span> <span m='3819960'>type</span> <span m='3820220'>of</span>
  <span m='3820360'>thing,</span> <span m='3820580'>where</span> <span m='3820760'>I</span>
  <span m='3820820'>grab</span> <span m='3821180'>one,</span> <span m='3821410'>and</span>
  <span m='3821500'>if</span> <span m='3821610'>I</span> <span m='3821670'>didn't</span>
  <span m='3821920'>get</span> <span m='3822090'>it in</span> <span m='3822280'>time,</span>
  <span m='3822640'>I</span> <span m='3822730'>release</span> <span m='3823140'>it</span>
  <span m='3824160'>and</span> <span m='3824340'>then</span> <span m='3824500'>try</span>
  <span m='3824750'>again.</span> <span m='3825320'>When</span> <span m='3825470'>you</span>
  <span m='3825630'>have</span> <span m='3825780'>something</span> <span m='3826130'>like</span>
  <span m='3826370'>that,</span> <span m='3827620'>there's</span> <span m='3827800'>an</span>
  <span m='3827860'>issue.</span> <span m='3828120'>It's,</span> <span m='3828230'>how</span>
  <span m='3828420'>do</span> <span m='3828490'>you</span> <span m='3828550'>set</span>
  <span m='3828790'>the</span> <span m='3828880'>timeout</span> <span m='3829350'>amount?</span>
  <span m='3831570'>And</span> <span m='3831690'>the</span> <span m='3831880'>second</span>
  <span m='3832060'>issue that</span> <span m='3832400'>you</span> <span m='3832500'>get</span>
  <span m='3832630'>into</span> <span m='3832950'>when</span> <span m='3833100'>you</span>
  <span m='3833210'>do</span> <span m='3833360'>timeouts</span> <span m='3833980'>is,</span>
  <span m='3834715'>how do you</span> <span m='3835100'>know you</span> <span m='3835230'>don't</span>
  <span m='3835510'>then</span> <span m='3836650'>repeat</span> <span m='3837080'>exactly</span>
  <span m='3837620'>the</span> <span m='3837700'>same</span> <span m='3837990'>thing</span>
  <span m='3838265'>and</span> <span m='3838540'>convert</span> <span m='3838855'>a</span>
  <span m='3839170'>deadlock</span> <span m='3839890'>situation</span> <span m='3840810'>into</span>
  <span m='3841040'>a</span> <span m='3841110'>livelock</span> <span m='3841800'>situation?</span>
  </p><p><span m='3843050'>So a</span> <span m='3843200'>livelock</span> <span m='3843690'>situation</span>
  <span m='3843985'>is</span> <span m='3844280'>where</span> <span m='3844390'>they're</span>
  <span m='3844520'>not</span> <span m='3844730'>making</span> <span m='3845030'>progress,</span>
  <span m='3845620'>but</span> <span m='3845730'>they're</span> <span m='3845880'>all</span>
  <span m='3846000'>busily</span> <span m='3846340'>working,</span> <span m='3847160'>thinking</span>
  <span m='3847480'>they're</span> <span m='3847590'>making</span> <span m='3847900'>progress.</span>
  <span m='3849120'>So you</span> <span m='3849380'>timeout.</span> <span m='3850370'>Let's</span>
  <span m='3850550'>try</span> <span m='3850820'>again.</span> <span m='3852320'>What</span>
  <span m='3852490'>makes</span> <span m='3852710'>you</span> <span m='3852820'>think</span>
  <span m='3853120'>that</span> <span m='3853280'>the</span> <span m='3853350'>guys</span>
  <span m='3853720'>that are</span> <span m='3853880'>deadlocking</span> <span m='3854530'>aren't</span>
  <span m='3854790'>going</span> <span m='3854920'>to</span> <span m='3854960'>do</span>
  <span m='3855120'>exactly</span> <span m='3855560'>the</span> <span m='3855630'>same</span>
  <span m='3855910'>thing.</span> </p><p><span m='3856490'>AUDIENCE:</span> <span
  m='3856760'>[INAUDIBLE]</span> </p><p><span m='3858062'>PROFESSOR:</span> <span
  m='3859030'>And</span> <span m='3859220'>exactly.</span> <span m='3859680'>And</span>
  <span m='3859790'>in</span> <span m='3859920'>fact,</span> <span m='3860200'>that's</span>
  <span m='3860420'>actually</span> <span m='3861450'>a</span> <span m='3861590'>workable</span>
  <span m='3862100'>scheme.</span> <span m='3862660'>And</span> <span m='3862890'>there</span>
  <span m='3863080'>are</span> <span m='3863160'>schemes</span> <span m='3863460'>that</span>
  <span m='3863610'>do</span> <span m='3863760'>it.</span> <span m='3863850'>Now,</span>
  <span m='3863990'>that's</span> <span m='3864210'>much</span> <span m='3864390'>more</span>
  <span m='3864580'>complicated.</span> <span m='3867240'>Sometimes</span> <span m='3867730'>has</span>
  <span m='3867890'>more</span> <span m='3868170'>overhead,</span> <span m='3869250'>especially</span>
  <span m='3869670'>because</span> <span m='3870200'>things</span> <span m='3870470'>become</span>
  <span m='3870770'>available.</span> <span m='3871440'>And</span> <span m='3871600'>it's</span>
  <span m='3871760'>like,</span> <span m='3872060'>no,</span> <span m='3872240'>you're</span>
  <span m='3872450'>busy</span> <span m='3874090'>raiding</span> <span m='3874480'>some</span>
  <span m='3874670'>random</span> <span m='3875020'>amount</span> <span m='3875280'>of</span>
  <span m='3875360'>time</span> <span m='3875710'>before</span> <span m='3876020'>you</span>
  <span m='3876140'>try</span> <span m='3876430'>again.</span> </p><p><span m='3878020'>So</span>
  <span m='3878170'>this is,</span> <span m='3878400'>by</span> <span m='3878550'>the</span>
  <span m='3878660'>way,</span> <span m='3878840'>the</span> <span m='3878990'>protocol</span>
  <span m='3879580'>that is</span> <span m='3879820'>used</span> <span m='3880170'>on</span>
  <span m='3880430'>the</span> <span m='3880590'>Ethernet</span> <span m='3882580'>for</span>
  <span m='3883070'>doing</span> <span m='3883650'>contention</span> <span m='3884180'>resolution.</span>
  <span m='3885630'>It's</span> <span m='3885800'>what's</span> <span m='3885980'>called</span>
  <span m='3886610'>&quot;exponential</span> <span m='3887170'>backoff.&quot;</span>
  <span m='3888950'>And</span> <span m='3889100'>various</span> <span m='3889440'>backoff</span>
  <span m='3889910'>schemes</span> <span m='3890350'>are</span> <span m='3890420'>used</span>
  <span m='3893920'>in</span> <span m='3894190'>order</span> <span m='3894360'>to</span>
  <span m='3894400'>allow</span> <span m='3895190'>multiple</span> <span m='3895900'>things</span>
  <span m='3896710'>acquire</span> <span m='3897510'>mutually-exclusive</span> <span
  m='3898300'>access</span> <span m='3898710'>to</span> <span m='3898810'>something</span>
  <span m='3899190'>without</span> <span m='3900520'>having</span> <span m='3900920'>to</span>
  <span m='3901340'>have</span> <span m='3901640'>a</span> <span m='3901800'>definite</span>
  <span m='3902250'>ordering.</span> <span m='3902960'>So</span> <span m='3903090'>there</span>
  <span m='3903220'>are</span> <span m='3903390'>solutions,</span> <span m='3904110'>but</span>
  <span m='3904920'>they</span> <span m='3905030'>definitely</span> <span m='3905480'>get</span>
  <span m='3905650'>more</span> <span m='3905820'>heavyweight.</span> <span m='3907230'>It's</span>
  <span m='3907360'>not</span> <span m='3907710'>lightweight.</span> </p><p><span
  m='3909080'>Whereas</span> <span m='3909350'>if</span> <span m='3909440'>you</span>
  <span m='3909570'>can</span> <span m='3909710'>prevent</span> <span m='3910130'>deadlock,</span>
  <span m='3911250'>that's</span> <span m='3911480'>really</span> <span m='3911720'>good,</span>
  <span m='3911890'>because</span> <span m='3912030'>you</span> <span m='3912150'>just</span>
  <span m='3912710'>simply</span> <span m='3913090'>do</span> <span m='3914020'>the</span>
  <span m='3914090'>natural</span> <span m='3914480'>thing.</span> <span m='3916900'>And</span>
  <span m='3917060'>that</span> <span m='3917240'>tends</span> <span m='3917450'>to</span>
  <span m='3917520'>be</span> <span m='3917620'>pretty</span> <span m='3917870'>quick.</span>
  <span m='3919500'>But</span> <span m='3919700'>yeah,</span> <span m='3921270'>all</span>
  <span m='3921560'>I'm</span> <span m='3921660'>doing</span> <span m='3921850'>is</span>
  <span m='3921920'>sort</span> <span m='3922070'>of</span> <span m='3922950'>covering</span>
  <span m='3924840'>the</span> <span m='3924950'>introduction</span> <span m='3925550'>to</span>
  <span m='3925630'>all</span> <span m='3925810'>these</span> <span m='3926000'>things.</span>
  <span m='3926240'>There are</span> <span m='3926320'>books</span> <span m='3926640'>written</span>
  <span m='3926910'>on</span> <span m='3927030'>this</span> <span m='3927180'>type</span>
  <span m='3927390'>of</span> <span m='3927470'>subject.</span> <span m='3930150'>Any</span>
  <span m='3930920'>other</span> <span m='3931170'>questions</span> <span m='3931590'>about</span>
  <span m='3932170'>dining</span> <span m='3932580'>philosophers</span> <span m='3933390'>and</span>
  <span m='3933620'>deadlock</span> <span m='3933940'>and</span> <span m='3934260'>so
  forth?</span> </p><p><span m='3936630'>Now</span> <span m='3936780'>let</span> <span
  m='3936900'>me</span> <span m='3937010'>tell</span> <span m='3937180'>you</span>
  <span m='3937270'>how</span> <span m='3937430'>to</span> <span m='3937540'>deadlock</span>
  <span m='3937750'>Cilk++.</span> <span m='3942680'>So</span> <span m='3943830'>here's</span>
  <span m='3944210'>a</span> <span m='3944660'>code</span> <span m='3945180'>that</span>
  <span m='3945280'>will</span> <span m='3945410'>deadlock</span> <span m='3945880'>Cilk++,</span>
  <span m='3947180'>or</span> <span m='3947370'>has</span> <span m='3947550'>the</span>
  <span m='3947630'>potential.</span> <span m='3948240'>You</span> <span m='3948350'>might</span>
  <span m='3948450'>run</span> <span m='3948660'>it</span> <span m='3948740'>a</span>
  <span m='3948790'>bunch</span> <span m='3949010'>of</span> <span m='3949070'>times,</span>
  <span m='3949360'>it</span> <span m='3949440'>looks</span> <span m='3949710'>fine.</span>
  <span m='3953070'>Here's</span> <span m='3953310'>what</span> <span m='3953460'>we've</span>
  <span m='3953620'>done</span> <span m='3954110'>is</span> <span m='3954220'>main</span>
  <span m='3954540'>routine</span> <span m='3955240'>spawns</span> <span m='3955910'>foo.</span>
  <span m='3956330'>Here's</span> <span m='3956610'>foo</span> <span m='3956810'>down</span>
  <span m='3957030'>here.</span> <span m='3957210'>All</span> <span m='3957430'>foo</span>
  <span m='3957700'>does</span> <span m='3957810'>is</span> <span m='3957920'>grab</span>
  <span m='3958220'>a</span> <span m='3958260'>lock</span> <span m='3958560'>and</span>
  <span m='3958690'>then</span> <span m='3958820'>unlocks</span> <span m='3959270'>it.</span>
  <span m='3961020'>Empty</span> <span m='3961290'>critical</span> <span m='3961710'>section.</span>
  <span m='3962500'>It</span> <span m='3962630'>could</span> <span m='3962800'>do</span>
  <span m='3962920'>something</span> <span m='3963280'>in</span> <span m='3963360'>there.</span>
  <span m='3963520'>It</span> <span m='3963570'>doesn't</span> <span m='3963800'>matter.</span>
  </p><p><span m='3965950'>Then</span> <span m='3966180'>the</span> <span m='3966270'>main</span>
  <span m='3966690'>grabs</span> <span m='3967090'>a</span> <span m='3967160'>lock,</span>
  <span m='3968100'>does</span> <span m='3968290'>a</span> <span m='3968360'>cilk_sync</span>
  <span m='3969170'>and</span> <span m='3969300'>then</span> <span m='3969460'>unlocks</span>
  <span m='3969950'>it.</span> <span m='3972270'>So</span> <span m='3972430'>what</span>
  <span m='3972620'>can</span> <span m='3972790'>go</span> <span m='3972970'>wrong</span>
  <span m='3973280'>here?</span> <span m='3975420'>Notice,</span> <span m='3975770'>by</span>
  <span m='3975880'>the</span> <span m='3975950'>way,</span> <span m='3976080'>this</span>
  <span m='3976260'>is</span> <span m='3976360'>only</span> <span m='3976620'>one</span>
  <span m='3976890'>lock,</span> <span m='3977790'>L.</span> <span m='3979455'>There's</span>
  <span m='3979890'>not</span> <span m='3980160'>two</span> <span m='3980340'>locks.</span>
  <span m='3982730'>So</span> <span m='3982880'>you</span> <span m='3982990'>can</span>
  <span m='3983100'>deadlock</span> <span m='3983360'>Cilk</span> <span m='3984000'>by</span>
  <span m='3984100'>just</span> <span m='3984380'>introducing</span> <span m='3984980'>one</span>
  <span m='3985180'>lock.</span> <span m='3986960'>So</span> <span m='3987120'>here's</span>
  <span m='3987380'>sort</span> <span m='3987590'>of</span> <span m='3987660'>what's</span>
  <span m='3987910'>going</span> <span m='3988180'>on.</span> <span m='3988890'>Let's</span>
  <span m='3989100'>let</span> <span m='3989330'>this</span> <span m='3990080'>be</span>
  <span m='3990230'>the</span> <span m='3990330'>main</span> <span m='3990660'>thread</span>
  <span m='3991410'>and</span> <span m='3991570'>this</span> <span m='3991770'>be</span>
  <span m='3991920'>foo.</span> <span m='3993140'>And</span> <span m='3993320'>this</span>
  <span m='3993520'>will</span> <span m='3993920'>represent</span> <span m='3994550'>a</span>
  <span m='3994760'>lock</span> <span m='3995080'>acquire,</span> <span m='3995670'>and</span>
  <span m='3995780'>this</span> <span m='3995930'>is</span> <span m='3996040'>a</span>
  <span m='3996100'>lock</span> <span m='3996440'>release.</span> </p><p><span m='3997390'>So</span>
  <span m='3997730'>what</span> <span m='3997850'>happens</span> <span m='3998290'>is</span>
  <span m='3998450'>we</span> <span m='3998640'>perform</span> <span m='3999520'>the</span>
  <span m='3999590'>lock</span> <span m='3999910'>acquire</span> <span m='4000400'>here</span>
  <span m='4002450'>in</span> <span m='4002610'>the</span> <span m='4002690'>parent.</span>
  <span m='4003970'>First,</span> <span m='4004340'>we</span> <span m='4004615'>spawned</span>
  <span m='4004890'>here,</span> <span m='4005600'>then</span> <span m='4005740'>we</span>
  <span m='4005860'>acquire</span> <span m='4006125'>the</span> <span m='4006390'>lock</span>
  <span m='4006780'>here.</span> <span m='4008090'>And</span> <span m='4008300'>now</span>
  <span m='4010140'>foo</span> <span m='4010360'>tries</span> <span m='4010760'>to</span>
  <span m='4010860'>get</span> <span m='4011120'>access</span> <span m='4011620'>to
  the</span> <span m='4011790'>lock,</span> <span m='4012170'>and</span> <span m='4012260'>it</span>
  <span m='4012300'>can't</span> <span m='4012880'>because</span> <span m='4013940'>why?</span>
  <span m='4015480'>The</span> <span m='4015580'>main</span> <span m='4015860'>routine</span>
  <span m='4016190'>has</span> <span m='4016540'>the</span> <span m='4016660'>lock.</span>
  </p><p><span m='4018570'>Now</span> <span m='4018830'>what</span> <span m='4018980'>happens?</span>
  <span m='4021000'>The</span> <span m='4021110'>main</span> <span m='4021410'>routine</span>
  <span m='4021820'>proceeds</span> <span m='4022440'>to</span> <span m='4022560'>the</span>
  <span m='4022670'>sync,</span> <span m='4023090'>and</span> <span m='4023180'>what</span>
  <span m='4023340'>does</span> <span m='4023460'>it</span> <span m='4023590'>do</span>
  <span m='4023750'>at</span> <span m='4023840'>the</span> <span m='4023930'>sync?</span>
  <span m='4026870'>It</span> <span m='4026980'>waits</span> <span m='4027500'>for</span>
  <span m='4028780'>all</span> <span m='4029020'>children</span> <span m='4029410'>to</span>
  <span m='4029490'>be</span> <span m='4029620'>done.</span> <span m='4032520'>And</span>
  <span m='4032670'>notice</span> <span m='4033010'>now</span> <span m='4033230'>we've</span>
  <span m='4033390'>created</span> <span m='4033880'>a</span> <span m='4033920'>cycle</span>
  <span m='4034360'>of</span> <span m='4034470'>waiting,</span> <span m='4034990'>even</span>
  <span m='4035270'>though</span> <span m='4035420'>we</span> <span m='4035540'>didn't</span>
  <span m='4035830'>use</span> <span m='4036030'>a</span> <span m='4036090'>lock.</span>
  <span m='4037630'>Main</span> <span m='4037960'>waits,</span> <span m='4038890'>but</span>
  <span m='4039160'>foo</span> <span m='4039330'>is</span> <span m='4039470'>never</span>
  <span m='4039750'>going</span> <span m='4039900'>to</span> <span m='4039950'>complete,</span>
  <span m='4040400'>because</span> <span m='4040580'>it's</span> <span m='4040730'>waiting</span>
  <span m='4041660'>for</span> <span m='4041790'>the</span> <span m='4041890'>main</span>
  <span m='4042500'>thread</span> <span m='4042770'>to</span> <span m='4042890'>release</span>
  <span m='4043210'>it,</span> <span m='4043530'>the</span> <span m='4043620'>main</span>
  <span m='4044170'>strand</span> <span m='4044590'>here</span> <span m='4044730'>to</span>
  <span m='4044830'>release it,</span> <span m='4045320'>the main</span> <span m='4045520'>function</span>
  <span m='4045850'>here.</span> <span m='4046722'>Is</span> <span m='4047060'>that</span>
  <span m='4047310'>clear?</span> </p><p><span m='4048850'>So</span> <span m='4049040'>you</span>
  <span m='4049250'>can</span> <span m='4049460'>deadlock</span> <span m='4050080'>Cilk</span>
  <span m='4050360'>too</span> <span m='4051490'>by</span> <span m='4051610'>doing</span>
  <span m='4052910'>non-deterministic</span> <span m='4053830'>programming.</span>
  <span m='4054690'>So</span> <span m='4054850'>here's</span> <span m='4055210'>the</span>
  <span m='4057130'>methodology</span> <span m='4058660'>that</span> <span m='4058770'>will</span>
  <span m='4058940'>help</span> <span m='4059260'>you</span> <span m='4059580'>not</span>
  <span m='4059880'>do</span> <span m='4060030'>that.</span> <span m='4060660'>So</span>
  <span m='4060850'>what's</span> <span m='4061090'>bad</span> <span m='4061460'>here?</span>
  <span m='4062060'>What's</span> <span m='4062280'>bad</span> <span m='4062660'>is</span>
  <span m='4062800'>holding</span> <span m='4063240'>the</span> <span m='4063350'>lock
  across</span> <span m='4063760'>the sync.</span> <span m='4066430'>That's</span>
  <span m='4066740'>bad.</span> <span m='4067540'>So</span> <span m='4067700'>don't</span>
  <span m='4067990'>do</span> <span m='4068140'>that.</span> <span m='4069940'>Doctor,</span>
  <span m='4071510'>my</span> <span m='4071660'>head hurts.</span> <span m='4072880'>Well,</span>
  <span m='4072930'>stop</span> <span m='4073200'>hitting</span> <span m='4073590'>it.</span>
  <span m='4079120'>So</span> <span m='4079880'>don't</span> <span m='4080070'>hold</span>
  <span m='4080300'>mutexes</span> <span m='4080930'>across</span> <span m='4081390'>Cilk</span>
  <span m='4081590'>syncs.</span> <span m='4083160'>Hold</span> <span m='4083420'>mutexes</span>
  <span m='4083970'>only</span> <span m='4084410'>within</span> <span m='4084770'>strands,</span>
  <span m='4085500'>only</span> <span m='4085820'>with</span> <span m='4086290'>serially-executing</span>
  <span m='4087140'>pieces</span> <span m='4087560'>of</span> <span m='4087660'>code.</span>
  </p><p><span m='4088802'>Now,</span> <span m='4089180'>it</span> <span m='4089370'>turns</span>
  <span m='4089640'>out</span> <span m='4089860'>that</span> <span m='4090010'>you</span>
  <span m='4090120'>can</span> <span m='4091120'>hold</span> <span m='4091420'>it</span>
  <span m='4092650'>across</span> <span m='4093130'>syncs</span> <span m='4093470'>and</span>
  <span m='4093630'>so</span> <span m='4093780'>forth,</span> <span m='4094230'>but</span>
  <span m='4094460'>you</span> <span m='4094530'>have</span> <span m='4094640'>to</span>
  <span m='4094740'>be</span> <span m='4094860'>careful.</span> <span m='4095880'>And</span>
  <span m='4098090'>I'm</span> <span m='4098140'>not</span> <span m='4098270'>going
  to</span> <span m='4098310'>get</span> <span m='4098479'>into</span> <span m='4098740'>the</span>
  <span m='4098840'>details</span> <span m='4099330'>of</span> <span m='4099390'>how</span>
  <span m='4099569'>you</span> <span m='4099720'>can</span> <span m='4099859'>do</span>
  <span m='4099960'>that.</span> <span m='4100170'>If you</span> <span m='4100250'>want</span>
  <span m='4100370'>to</span> <span m='4100410'>figure</span> <span m='4100689'>that</span>
  <span m='4100899'>out</span> <span m='4101100'>on</span> <span m='4101210'>your</span>
  <span m='4101390'>own,</span> <span m='4102630'>that's</span> <span m='4102890'>fine.</span>
  <span m='4103770'>And</span> <span m='4104010'>then</span> <span m='4104149'>you're</span>
  <span m='4104380'>welcome</span> <span m='4104819'>to</span> <span m='4104899'>try</span>
  <span m='4105120'>to</span> <span m='4105220'>do</span> <span m='4105399'>that</span>
  <span m='4105720'>without</span> <span m='4106090'>deadlocking</span> <span m='4106620'>something.</span>
  <span m='4108319'>Turns</span> <span m='4108590'>out,</span> <span m='4108779'>basically,</span>
  <span m='4109640'>if</span> <span m='4109859'>you</span> <span m='4110700'>grab</span>
  <span m='4111080'>the</span> <span m='4111160'>lock</span> <span m='4111495'>before</span>
  <span m='4112100'>you</span> <span m='4112220'>do</span> <span m='4112380'>any</span>
  <span m='4112569'>spawns,</span> <span m='4113810'>and</span> <span m='4113960'>then</span>
  <span m='4114090'>released</span> <span m='4114510'>it</span> <span m='4114600'>after</span>
  <span m='4115010'>the</span> <span m='4115120'>Cilk sync,</span> <span m='4115720'>you're</span>
  <span m='4115880'>OK.</span> <span m='4120020'>You're</span> <span m='4120140'>generally,</span>
  <span m='4120410'>in</span> <span m='4120490'>that</span> <span m='4120689'>case,</span>
  <span m='4120890'>OK.</span> </p><p><span m='4127710'>So</span> <span m='4127880'>as</span>
  <span m='4128160'>always,</span> <span m='4128529'>try</span> <span m='4128750'>to</span>
  <span m='4128830'>avoid</span> <span m='4129149'>using</span> <span m='4129439'>mutexes,</span>
  <span m='4130229'>but</span> <span m='4130490'>that's</span> <span m='4130760'>not</span>
  <span m='4130920'>always</span> <span m='4131160'>possible.</span> <span m='4132350'>In
  other words,</span> <span m='4132630'>try</span> <span m='4132840'>to</span> <span
  m='4132950'>do</span> <span m='4133109'>deterministic</span> <span m='4133750'>programming.</span>
  <span m='4134260'>That</span> <span m='4134420'>helps</span> <span m='4134720'>too.</span>
  <span m='4136790'>And</span> <span m='4137149'>on</span> <span m='4137420'>your</span>
  <span m='4138620'>homework,</span> <span m='4139010'>you</span> <span m='4139090'>had</span>
  <span m='4139210'>an</span> <span m='4139260'>example</span> <span m='4140970'>of</span>
  <span m='4141109'>where</span> <span m='4141399'>it</span> <span m='4141460'>is</span>
  <span m='4141640'>that</span> <span m='4141720'>deterministic</span> <span m='4142359'>programming</span>
  <span m='4144620'>can</span> <span m='4144859'>actually</span> <span m='4145140'>do</span>
  <span m='4145240'>a</span> <span m='4145310'>pretty</span> <span m='4145529'>good</span>
  <span m='4145689'>job.</span> </p><p><span m='4148189'>The</span> <span m='4148300'>next</span>
  <span m='4148899'>anomaly</span> <span m='4149390'>I want to</span> <span m='4149540'>talk</span>
  <span m='4149770'>about</span> <span m='4150020'>is</span> <span m='4150200'>convoying.</span>
  <span m='4151350'>Once</span> <span m='4151510'>again,</span> <span m='4151770'>another</span>
  <span m='4152140'>thing</span> <span m='4152399'>that</span> <span m='4152510'>can</span>
  <span m='4152630'>happen.</span> <span m='4153620'>This</span> <span m='4153850'>one</span>
  <span m='4154080'>is</span> <span m='4154310'>actually</span> <span m='4154649'>quite</span>
  <span m='4154880'>an</span> <span m='4154939'>embarrassment,</span> <span m='4156189'>because</span>
  <span m='4157540'>the</span> <span m='4157710'>original</span> <span m='4158100'>MIT</span>
  <span m='4158609'>Cilk</span> <span m='4158920'>system</span> <span m='4159670'>that</span>
  <span m='4159800'>we</span> <span m='4159930'>built</span> <span m='4160210'>had</span>
  <span m='4160520'>this</span> <span m='4160720'>bug in it.</span> <span m='4162760'>So</span>
  <span m='4164170'>we</span> <span m='4164279'>had</span> <span m='4164529'>this</span>
  <span m='4164729'>bug.</span> <span m='4164970'>So</span> <span m='4165140'>let</span>
  <span m='4165229'>me</span> <span m='4165310'>show</span> <span m='4165510'>you</span>
  <span m='4165640'>what</span> <span m='4165770'>it is.</span> <span m='4166590'>So</span>
  <span m='4167649'>here's</span> <span m='4167930'>the</span> <span m='4168080'>idea.</span>
  <span m='4168600'>We're</span> <span m='4168779'>using</span> <span m='4169200'>random</span>
  <span m='4169600'>work-stealing</span> <span m='4170270'>where</span> <span m='4170859'>each</span>
  <span m='4171160'>thief</span> <span m='4171520'>grabs</span> <span m='4171590'>a</span>
  <span m='4171859'>mutex</span> <span m='4172390'>on</span> <span m='4172620'>its</span>
  <span m='4172790'>victim's</span> <span m='4173229'>deck.</span> </p><p><span m='4173529'>So</span>
  <span m='4173670'>in</span> <span m='4173720'>order</span> <span m='4173970'>to</span>
  <span m='4174060'>steal</span> <span m='4175020'>from</span> <span m='4175290'>a</span>
  <span m='4175359'>victim,</span> <span m='4176910'>it</span> <span m='4177100'>grabs</span>
  <span m='4177620'>a</span> <span m='4177670'>mutex</span> <span m='4178189'>on</span>
  <span m='4178330'>the</span> <span m='4178399'>victim.</span> <span m='4179420'>And</span>
  <span m='4179609'>now,</span> <span m='4180500'>once</span> <span m='4180760'>it's</span>
  <span m='4180910'>got</span> <span m='4181090'>the</span> <span m='4181170'>mutex,</span>
  <span m='4181609'>it</span> <span m='4181729'>now</span> <span m='4181939'>is in</span>
  <span m='4182050'>a</span> <span m='4182130'>position</span> <span m='4182600'>to</span>
  <span m='4183050'>migrate</span> <span m='4183740'>the</span> <span m='4184510'>work</span>
  <span m='4184979'>that's</span> <span m='4185170'>on</span> <span m='4185380'>that</span>
  <span m='4185740'>victim</span> <span m='4186540'>to</span> <span m='4186960'>actually</span>
  <span m='4187279'>steal</span> <span m='4187649'>the</span> <span m='4187720'>work.</span>
  <span m='4188200'>And</span> <span m='4188430'>you</span> <span m='4188569'>want</span>
  <span m='4188700'>to</span> <span m='4188740'>do</span> <span m='4188859'>that</span>
  <span m='4189040'>atomically.</span> <span m='4189640'>You</span> <span m='4189710'>don't</span>
  <span m='4189850'>want</span> <span m='4190050'>two</span> <span m='4190180'>guys</span>
  <span m='4190460'>getting</span> <span m='4190620'>in</span> <span m='4190810'>there</span>
  <span m='4190990'>trying</span> <span m='4191210'>to</span> <span m='4191800'>steal</span>
  <span m='4192130'>from</span> <span m='4192319'>each</span> <span m='4192490'>other.</span>
  </p><p><span m='4194220'>So</span> <span m='4195490'>if</span> <span m='4195650'>the</span>
  <span m='4195740'>victim's</span> <span m='4196210'>deck</span> <span m='4196440'>is</span>
  <span m='4196570'>empty,</span> <span m='4196990'>the</span> <span m='4197120'>thief</span>
  <span m='4197430'>releases</span> <span m='4197960'>the</span> <span m='4198150'>mutex</span>
  <span m='4198480'>and</span> <span m='4198590'>tries</span> <span m='4198890'>again</span>
  <span m='4199150'>at</span> <span m='4199250'>random.</span> <span m='4199770'>That</span>
  <span m='4199940'>makes</span> <span m='4200170'>sense.</span> <span m='4201180'>If</span>
  <span m='4201300'>there's</span> <span m='4201450'>nothing</span> <span m='4201870'>there</span>
  <span m='4201930'>to be</span> <span m='4202330'>stolen,</span> <span m='4203280'>then</span>
  <span m='4203470'>just</span> <span m='4203650'>released</span> <span m='4204030'>the</span>
  <span m='4204070'>mutex</span> <span m='4204580'>and</span> <span m='4204690'>move</span>
  <span m='4204920'>on.</span> <span m='4206200'>If</span> <span m='4206400'>the</span>
  <span m='4206510'>victim's</span> <span m='4206910'>deck</span> <span m='4207080'>contains</span>
  <span m='4207540'>work,</span> <span m='4208050'>the</span> <span m='4208230'>thief
  then</span> <span m='4208570'>steals</span> <span m='4208960'>the</span> <span m='4209050'>topmost</span>
  <span m='4209500'>frame</span> <span m='4209780'>and</span> <span m='4209900'>then</span>
  <span m='4210070'>releases</span> <span m='4210530'>the</span> <span m='4210580'>mutex.</span>
  <span m='4213400'>Where's</span> <span m='4213730'>the</span> <span m='4213810'>performance</span>
  <span m='4214370'>bug</span> <span m='4214560'>here?</span> </p><p><span m='4219760'>AUDIENCE:</span>
  <span m='4220247'>[INAUDIBLE]</span> <span m='4221708'>trying</span> <span m='4222195'>to</span>
  <span m='4222682'>steal</span> <span m='4223169'>from each</span> <span m='4223656'>other.</span>
  <span m='4224143'>Like A steals</span> <span m='4224630'>from B,</span> <span m='4225117'>B
  steals from C,</span> <span m='4225604'>C steals from D,</span> <span m='4226578'>and</span>
  <span m='4227065'>they all</span> <span m='4227552'>have</span> <span m='4228039'>locks
  on</span> <span m='4228526'>each other,</span> <span m='4229013'>and then--</span>
  </p><p><span m='4229510'>PROFESSOR:</span> <span m='4229730'>No,</span> <span m='4229860'>because</span>
  <span m='4230030'>in</span> <span m='4230180'>that</span> <span m='4230380'>case,</span>
  <span m='4230640'>they'll</span> <span m='4230800'>each</span> <span m='4231070'>grab</span>
  <span m='4231690'>the</span> <span m='4231810'>deck</span> <span m='4232540'>from</span>
  <span m='4232760'>each</span> <span m='4232970'>other,</span> <span m='4233170'>discover</span>
  <span m='4233590'>it's empty,</span> <span m='4234090'>and release it.</span> <span
  m='4238680'>OK,</span> <span m='4238940'>let</span> <span m='4239070'>me</span>
  <span m='4239150'>show</span> <span m='4239380'>the</span> <span m='4239490'>bug.</span>
  <span m='4239720'>It</span> <span m='4239840'>is</span> <span m='4240400'>very</span>
  <span m='4240810'>subtle.</span> <span m='4241520'>As</span> <span m='4241660'>I</span>
  <span m='4241720'>say,</span> <span m='4241870'>we</span> <span m='4242040'>didn't</span>
  <span m='4242230'>realize</span> <span m='4242640'>we</span> <span m='4242740'>had</span>
  <span m='4242980'>this</span> <span m='4243160'>bug</span> <span m='4243830'>until</span>
  <span m='4244220'>we</span> <span m='4244370'>noticed</span> <span m='4245810'>some</span>
  <span m='4246460'>codes</span> <span m='4246850'>on which</span> <span m='4247050'>we</span>
  <span m='4247150'>weren't</span> <span m='4247350'>getting</span> <span m='4247570'>the</span>
  <span m='4247650'>speedups</span> <span m='4247950'>we</span> <span m='4248140'>were</span>
  <span m='4248330'>expecting.</span> <span m='4248860'>Let</span> <span m='4249360'>me</span>
  <span m='4249400'>show</span> <span m='4249580'>you</span> <span m='4249670'>where</span>
  <span m='4249800'>this</span> <span m='4250000'>bug</span> <span m='4250540'>comes</span>
  <span m='4250720'>from.</span> </p><p><span m='4251830'>Here's</span> <span m='4252020'>the</span>
  <span m='4252110'>problem.</span> <span m='4253130'>At</span> <span m='4253340'>the</span>
  <span m='4253430'>startup,</span> <span m='4254230'>most</span> <span m='4254730'>thieves</span>
  <span m='4255140'>will</span> <span m='4255490'>quickly</span> <span m='4255890'>converge</span>
  <span m='4256540'>on</span> <span m='4256760'>the</span> <span m='4256850'>worker</span>
  <span m='4257190'>P0</span> <span m='4257850'>containing</span> <span m='4258330'>the</span>
  <span m='4258440'>initial</span> <span m='4258820'>strand,</span> <span m='4261720'>creating</span>
  <span m='4262170'>a</span> <span m='4262240'>convoy.</span> <span m='4262720'>So</span>
  <span m='4262860'>let</span> <span m='4262960'>me</span> <span m='4263050'>show</span>
  <span m='4263230'>you</span> <span m='4263330'>how</span> <span m='4263530'>that</span>
  <span m='4263720'>happens.</span> <span m='4265390'>So</span> <span m='4265530'>here</span>
  <span m='4265750'>we</span> <span m='4266150'>have</span> <span m='4266720'>the</span>
  <span m='4266830'>startup</span> <span m='4267460'>of</span> <span m='4267620'>our</span>
  <span m='4267740'>Cilk</span> <span m='4268020'>system</span> <span m='4268520'>where</span>
  <span m='4268880'>one</span> <span m='4269190'>guy</span> <span m='4269450'>has</span>
  <span m='4269700'>work,</span> <span m='4270090'>and</span> <span m='4270190'>all</span>
  <span m='4270550'>these</span> <span m='4270880'>are</span> <span m='4271510'>workers</span>
  <span m='4272420'>that</span> <span m='4272700'>have</span> <span m='4272870'>no</span>
  <span m='4273090'>work</span> <span m='4273420'>to</span> <span m='4273520'>do.</span>
  <span m='4275410'>So</span> <span m='4275550'>what</span> <span m='4275670'>happens?</span>
  <span m='4276490'>They</span> <span m='4276650'>all</span> <span m='4277090'>try</span>
  <span m='4277310'>to</span> <span m='4277400'>steal</span> <span m='4277860'>at</span>
  <span m='4277920'>random.</span> </p><p><span m='4279200'>In</span> <span m='4279450'>this</span>
  <span m='4279660'>case,</span> <span m='4280410'>we</span> <span m='4280570'>have</span>
  <span m='4281220'>this</span> <span m='4281480'>guy</span> <span m='4281760'>tries</span>
  <span m='4282090'>to</span> <span m='4282230'>steal</span> <span m='4282510'>from</span>
  <span m='4283030'>this</span> <span m='4283250'>fellow,</span> <span m='4284080'>this</span>
  <span m='4284290'>guy</span> <span m='4284480'>tries</span> <span m='4284790'>to</span>
  <span m='4284910'>steal</span> <span m='4285180'>from</span> <span m='4285330'>this</span>
  <span m='4285570'>fellow,</span> <span m='4286010'>et</span> <span m='4286260'>cetera.</span>
  <span m='4286930'>So</span> <span m='4287770'>of</span> <span m='4288050'>these,</span>
  <span m='4290380'>this</span> <span m='4290550'>guy,</span> <span m='4291270'>this</span>
  <span m='4291580'>guy,</span> <span m='4291970'>and</span> <span m='4292170'>that</span>
  <span m='4292450'>guy</span> <span m='4292840'>all</span> <span m='4293150'>are</span>
  <span m='4293260'>going</span> <span m='4293520'>to</span> <span m='4294120'>discover</span>
  <span m='4294490'>there's</span> <span m='4294670'>nothing</span> <span m='4294980'>there</span>
  <span m='4295150'>to</span> <span m='4295210'>be</span> <span m='4295320'>stolen,</span>
  <span m='4295850'>and</span> <span m='4295960'>they're</span> <span m='4296080'>going</span>
  <span m='4296190'>to</span> <span m='4296240'>repeat</span> <span m='4296680'>the</span>
  <span m='4296770'>process.</span> <span m='4298270'>This</span> <span m='4298700'>guy</span>
  <span m='4298930'>and</span> <span m='4299070'>this</span> <span m='4299320'>guy,</span>
  <span m='4299640'>there's</span> <span m='4299840'>going</span> <span m='4299910'>to</span>
  <span m='4299980'>be</span> <span m='4300050'>some</span> <span m='4300270'>arbitration.</span>
  <span m='4301010'>And</span> <span m='4301130'>one</span> <span m='4301300'>of</span>
  <span m='4301370'>them</span> <span m='4301510'>is</span> <span m='4301620'>going</span>
  <span m='4301740'>to</span> <span m='4301780'>get</span> <span m='4301970'>the</span>
  <span m='4302050'>lock.</span> <span m='4303530'>Let's</span> <span m='4303770'>assume</span>
  <span m='4304070'>it's</span> <span m='4304220'>this</span> <span m='4304380'>one</span>
  <span m='4304550'>here.</span> </p><p><span m='4306540'>So</span> <span m='4306690'>what</span>
  <span m='4306790'>happens</span> <span m='4307290'>is,</span> <span m='4307920'>this</span>
  <span m='4308160'>guy</span> <span m='4308300'>gets</span> <span m='4308520'>the</span>
  <span m='4308580'>lock.</span> <span m='4308900'>What</span> <span m='4309030'>does</span>
  <span m='4309150'>this</span> <span m='4309360'>guy</span> <span m='4309540'>do?</span>
  <span m='4312440'>He's</span> <span m='4312620'>going</span> <span m='4312720'>to</span>
  <span m='4312810'>wait.</span> <span m='4315970'>Because</span> <span m='4316100'>he's</span>
  <span m='4316220'>trying</span> <span m='4316530'>to</span> <span m='4316610'>acquire</span>
  <span m='4316860'>the</span> <span m='4316980'>lock.</span> <span m='4317500'>He
  can't</span> <span m='4317630'>acquire the</span> <span m='4318010'>lock,</span>
  <span m='4318410'>so he</span> <span m='4318755'>waits.</span> </p><p><span m='4320610'>So</span>
  <span m='4320770'>then</span> <span m='4320930'>what</span> <span m='4321090'>happens?</span>
  <span m='4322350'>This</span> <span m='4322620'>guy</span> <span m='4323070'>now</span>
  <span m='4323380'>wants</span> <span m='4323730'>to</span> <span m='4324340'>steal</span>
  <span m='4324910'>the</span> <span m='4324980'>work</span> <span m='4325590'>from</span>
  <span m='4325700'>this</span> <span m='4325900'>fellow.</span> <span m='4327470'>So</span>
  <span m='4327650'>he</span> <span m='4327740'>steals</span> <span m='4328060'>a</span>
  <span m='4328100'>little</span> <span m='4328290'>bit</span> <span m='4328390'>of</span>
  <span m='4328460'>work.</span> <span m='4330980'>Then</span> <span m='4331180'>these</span>
  <span m='4331440'>guys</span> <span m='4331840'>now,</span> <span m='4332100'>what</span>
  <span m='4332200'>do</span> <span m='4332240'>they</span> <span m='4332440'>do?</span>
  <span m='4333510'>They</span> <span m='4333690'>try</span> <span m='4333940'>again.</span>
  <span m='4336550'>So</span> <span m='4337430'>this</span> <span m='4337620'>guy</span>
  <span m='4337770'>tries</span> <span m='4338050'>to</span> <span m='4338150'>steal</span>
  <span m='4338350'>from</span> <span m='4338520'>there,</span> <span m='4338760'>this</span>
  <span m='4338940'>guy</span> <span m='4339080'>tries</span> <span m='4339330'>to</span>
  <span m='4339450'>steal from</span> <span m='4339730'>there,</span> <span m='4340010'>this</span>
  <span m='4340180'>one</span> <span m='4340380'>happens</span> <span m='4340730'>to</span>
  <span m='4340830'>try</span> <span m='4341050'>to steal</span> <span m='4341370'>there.</span>
  <span m='4342100'>This</span> <span m='4342300'>one</span> <span m='4342500'>sees</span>
  <span m='4342810'>there's</span> <span m='4343010'>work</span> <span m='4343310'>there</span>
  <span m='4343480'>to</span> <span m='4343570'>be</span> <span m='4343680'>done,</span>
  <span m='4345300'>so</span> <span m='4345510'>what</span> <span m='4345630'>does</span>
  <span m='4345750'>it</span> <span m='4345870'>do?</span> <span m='4347320'>It waits.</span>
  </p><p><span m='4349200'>But</span> <span m='4349390'>these</span> <span m='4349670'>guys</span>
  <span m='4350490'>then</span> <span m='4350670'>try</span> <span m='4350970'>again.</span>
  <span m='4352590'>Maybe</span> <span m='4352790'>a</span> <span m='4352850'>little</span>
  <span m='4353020'>bit</span> <span m='4353190'>more</span> <span m='4353440'>stuff</span>
  <span m='4353730'>is</span> <span m='4353920'>moved.</span> <span m='4356675'>They</span>
  <span m='4357050'>try</span> <span m='4357320'>again.</span> <span m='4358490'>A</span>
  <span m='4358650'>little</span> <span m='4358780'>bit</span> <span m='4358920'>more</span>
  <span m='4359140'>stuff.</span> <span m='4360550'>They</span> <span m='4360670'>try</span>
  <span m='4360940'>again.</span> <span m='4362020'>But</span> <span m='4362160'>every</span>
  <span m='4362390'>time</span> <span m='4362670'>one</span> <span m='4363200'>tries</span>
  <span m='4363590'>and</span> <span m='4363720'>gets</span> <span m='4363870'>stuck</span>
  <span m='4364240'>on</span> <span m='4364720'>P0</span> <span m='4365400'>while</span>
  <span m='4365750'>we're</span> <span m='4365870'>doing</span> <span m='4366090'>that</span>
  <span m='4366270'>whole</span> <span m='4366460'>transfer,</span> <span m='4367980'>they</span>
  <span m='4368150'>all</span> <span m='4369200'>are</span> <span m='4369420'>ending</span>
  <span m='4369730'>up</span> <span m='4371220'>getting</span> <span m='4371540'>stuck</span>
  <span m='4372090'>waiting</span> <span m='4372600'>for</span> <span m='4372710'>this</span>
  <span m='4372940'>guy</span> <span m='4373140'>to</span> <span m='4373230'>finish.</span>
  </p><p><span m='4374980'>And</span> <span m='4375240'>now,</span> <span m='4376190'>we've</span>
  <span m='4376310'>got</span> <span m='4376590'>work</span> <span m='4376870'>over</span>
  <span m='4377130'>here,</span> <span m='4377420'>but</span> <span m='4377560'>how</span>
  <span m='4377740'>many</span> <span m='4377920'>guys</span> <span m='4378250'>are</span>
  <span m='4378300'>going</span> <span m='4378410'>to</span> <span m='4378450'>be</span>
  <span m='4378520'>trying</span> <span m='4378660'>to</span> <span m='4378800'>steal</span>
  <span m='4379150'>from</span> <span m='4379320'>this</span> <span m='4379400'>guy?</span>
  <span m='4380580'>None.</span> <span m='4382800'>They're</span> <span m='4382960'>all</span>
  <span m='4383220'>going</span> <span m='4383300'>to</span> <span m='4383370'>be</span>
  <span m='4383440'>trying</span> <span m='4383590'>to</span> <span m='4383740'>steal</span>
  <span m='4384040'>from</span> <span m='4384180'>this</span> <span m='4384390'>one,</span>
  <span m='4385140'>because</span> <span m='4385350'>they</span> <span m='4385500'>all</span>
  <span m='4385810'>have</span> <span m='4386440'>done</span> <span m='4386610'>a</span>
  <span m='4386680'>lock</span> <span m='4387010'>acquisition,</span> <span m='4387650'>and</span>
  <span m='4387780'>they're</span> <span m='4387870'>sitting</span> <span m='4388280'>there</span>
  <span m='4388340'>waiting.</span> <span m='4390520'>So</span> <span m='4390620'>this</span>
  <span m='4390800'>is</span> <span m='4391020'>called</span> <span m='4391220'>convoying,</span>
  <span m='4391870'>where</span> <span m='4391990'>they</span> <span m='4392140'>all</span>
  <span m='4392440'>pile</span> <span m='4392780'>up</span> <span m='4392940'>on</span>
  <span m='4394110'>one</span> <span m='4394300'>thing,</span> <span m='4394530'>and</span>
  <span m='4394630'>now</span> <span m='4394820'>resolving</span> <span m='4395440'>that</span>
  <span m='4395660'>convoy.</span> </p><p><span m='4396090'>So</span> <span m='4396220'>this</span>
  <span m='4396410'>was</span> <span m='4396590'>a</span> <span m='4396810'>bug</span>
  <span m='4397193'>in</span> <span m='4397960'>startup.</span> <span m='4398530'>Why</span>
  <span m='4398730'>wasn't</span> <span m='4399050'>Cilk</span> <span m='4399540'>starting</span>
  <span m='4400000'>up</span> <span m='4400210'>fast?</span> <span m='4402540'>Initially,</span>
  <span m='4402880'>we</span> <span m='4402970'>just</span> <span m='4403140'>thought,</span>
  <span m='4403320'>oh,</span> <span m='4404800'>there's</span> <span m='4404920'>system</span>
  <span m='4405320'>kinds</span> <span m='4406520'>of</span> <span m='4406680'>things</span>
  <span m='4406960'>going</span> <span m='4407170'>on</span> <span m='4407370'>there.</span>
  <span m='4408870'>So</span> <span m='4409040'>the work</span> <span m='4409240'>now</span>
  <span m='4409450'>gets</span> <span m='4409660'>distributed</span> <span m='4409980'>very</span>
  <span m='4410290'>slowly,</span> <span m='4410770'>because</span> <span m='4411020'>each</span>
  <span m='4411280'>one</span> <span m='4411480'>is</span> <span m='4411590'>going</span>
  <span m='4411690'>to</span> <span m='4411730'>serially</span> <span m='4412210'>try</span>
  <span m='4412400'>to</span> <span m='4412470'>get</span> <span m='4412680'>this</span>
  <span m='4412860'>work,</span> <span m='4413340'>and</span> <span m='4413500'>they're</span>
  <span m='4413610'>not</span> <span m='4413970'>going</span> <span m='4414080'>to</span>
  <span m='4414140'>try</span> <span m='4414340'>to</span> <span m='4414390'>get</span>
  <span m='4414580'>the</span> <span m='4414650'>work</span> <span m='4414910'>from</span>
  <span m='4415060'>each</span> <span m='4415260'>other.</span> <span m='4416460'>What</span>
  <span m='4416610'>you</span> <span m='4416710'>want</span> <span m='4417160'>is</span>
  <span m='4417510'>that</span> <span m='4417680'>on</span> <span m='4417800'>the</span>
  <span m='4417910'>second</span> <span m='4419360'>phase,</span> <span m='4420360'>half</span>
  <span m='4420540'>the</span> <span m='4420640'>guys</span> <span m='4421040'>might</span>
  <span m='4421700'>start</span> <span m='4422020'>hitting</span> <span m='4422250'>this</span>
  <span m='4422450'>one.</span> </p><p><span m='4423100'>So</span> <span m='4423180'>you</span>
  <span m='4423230'>get</span> <span m='4423370'>some</span> <span m='4423510'>kind</span>
  <span m='4423680'>of</span> <span m='4423770'>exponential</span> <span m='4424500'>distribution</span>
  <span m='4426990'>of</span> <span m='4427170'>the</span> <span m='4427270'>work</span>
  <span m='4427540'>in</span> <span m='4427650'>kind</span> <span m='4427800'>of</span>
  <span m='4427950'>a</span> <span m='4428270'>tree</span> <span m='4428890'>fashion.</span>
  <span m='4429590'>And</span> <span m='4429680'>that's</span> <span m='4429920'>what</span>
  <span m='4430250'>theory</span> <span m='4430570'>says</span> <span m='4430890'>would</span>
  <span m='4431030'>happen.</span> <span m='4432080'>But</span> <span m='4432340'>the</span>
  <span m='4432440'>theory</span> <span m='4432810'>is</span> <span m='4432940'>usually</span>
  <span m='4433230'>done</span> <span m='4433490'>without</span> <span m='4433880'>worrying</span>
  <span m='4434160'>about</span> <span m='4435270'>what</span> <span m='4435420'>happens</span>
  <span m='4436750'>in</span> <span m='4436940'>the</span> <span m='4437215'>implementation
  of</span> <span m='4437490'>the lock.</span> <span m='4438810'>What's</span> <span
  m='4439040'>the</span> <span m='4439140'>fix</span> <span m='4439490'>for</span>
  <span m='4439580'>this?</span> <span m='4441547'>Yeah?</span> </p><p><span m='4443044'>AUDIENCE:</span>
  <span m='4443543'>Can you just</span> <span m='4444042'>basically</span> <span m='4444541'>shove--</span>
  <span m='4445040'>when</span> <span m='4445539'>you're</span> <span m='4446038'>transferring,</span>
  <span m='4446537'>you should</span> <span m='4447036'>also say,</span> <span m='4447535'>I
  have</span> <span m='4448034'>work,</span> <span m='4448533'>so that</span> <span
  m='4449032'>people</span> <span m='4449531'>[INAUDIBLE]</span> <span m='4450030'>waiting</span>
  <span m='4450529'>for</span> <span m='4451028'>that</span> <span m='4451527'>guy
  to</span> <span m='4452026'>[INAUDIBLE].</span> </p><p><span m='4453024'>PROFESSOR:</span>
  <span m='4453540'>You</span> <span m='4453690'>could</span> <span m='4453900'>do</span>
  <span m='4454020'>that,</span> <span m='4454350'>but in</span> <span m='4454670'>the</span>
  <span m='4454750'>meantime,</span> <span m='4455400'>it</span> <span m='4455600'>could</span>
  <span m='4455790'>be</span> <span m='4455980'>that</span> <span m='4457400'>the</span>
  <span m='4457590'>attempt</span> <span m='4457960'>to</span> <span m='4458050'>steal</span>
  <span m='4458310'>goes</span> <span m='4458430'>so</span> <span m='4458630'>much</span>
  <span m='4458850'>faster</span> <span m='4459280'>than</span> <span m='4459440'>the</span>
  <span m='4459540'>actual</span> <span m='4459840'>getting</span> <span m='4460110'>of</span>
  <span m='4460190'>the</span> <span m='4460270'>work,</span> <span m='4461010'>you're</span>
  <span m='4461130'>still</span> <span m='4461320'>going</span> <span m='4461420'>to</span>
  <span m='4461460'>get</span> <span m='4461630'>half</span> <span m='4462000'>the</span>
  <span m='4462090'>guys</span> <span m='4463810'>locked</span> <span m='4464140'>up</span>
  <span m='4464310'>on</span> <span m='4464420'>this</span> <span m='4464610'>one.</span>
  <span m='4464980'>And</span> <span m='4465140'>the</span> <span m='4465250'>other</span>
  <span m='4465430'>half</span> <span m='4465800'>might</span> <span m='4466070'>be</span>
  <span m='4466180'>locked</span> <span m='4466480'>up</span> <span m='4466650'>on</span>
  <span m='4466760'>this</span> <span m='4466950'>one.</span> <span m='4470890'>Good</span>
  <span m='4471060'>idea.</span> <span m='4472640'>What</span> <span m='4472840'>other</span>
  <span m='4472960'>things</span> <span m='4473260'>can</span> <span m='4473350'>we</span>
  <span m='4473460'>do?</span> </p><p><span m='4475584'>AUDIENCE:</span> <span m='4476045'>Can
  you</span> <span m='4476506'>check how</span> <span m='4476967'>many people</span>
  <span m='4477428'>are</span> <span m='4477889'>waiting on the--</span> </p><p><span
  m='4478350'>PROFESSOR:</span> <span m='4478820'>Yeah,</span> <span m='4479450'>so</span>
  <span m='4479620'>the</span> <span m='4479810'>idea</span> <span m='4480120'>is</span>
  <span m='4480810'>we</span> <span m='4480910'>don't</span> <span m='4481010'>want</span>
  <span m='4481110'>to</span> <span m='4481150'>use</span> <span m='4482440'>a</span>
  <span m='4482560'>lock</span> <span m='4482900'>operation.</span> <span m='4486350'>So</span>
  <span m='4486630'>here's</span> <span m='4486940'>the</span> <span m='4487060'>idea.</span>
  <span m='4488280'>We</span> <span m='4488420'>use</span> <span m='4488690'>a</span>
  <span m='4488910'>non-blocking</span> <span m='4489620'>function</span> <span m='4490060'>that's</span>
  <span m='4490750'>usually</span> <span m='4491070'>called</span> <span m='4491370'>&quot;try_lock,&quot;</span>
  <span m='4493500'>rather</span> <span m='4493810'>than</span> <span m='4493980'>&quot;lock.&quot;</span>
  <span m='4494310'>try_lock</span> <span m='4494990'>attempts</span> <span m='4495530'>to</span>
  <span m='4495660'>acquire</span> <span m='4496100'>the</span> <span m='4496230'>mutex.</span>
  <span m='4497360'>If</span> <span m='4497540'>it</span> <span m='4497660'>succeeds,</span>
  <span m='4498500'>great.</span> <span m='4499830'>It's</span> <span m='4500040'>got</span>
  <span m='4500160'>it.</span> <span m='4500770'>If it</span> <span m='4501190'>fails,</span>
  <span m='4502210'>it</span> <span m='4502320'>doesn't</span> <span m='4502610'>go</span>
  <span m='4502750'>to</span> <span m='4502840'>spin.</span> <span m='4503800'>It</span>
  <span m='4503950'>simply</span> <span m='4504250'>returns</span> <span m='4504710'>and</span>
  <span m='4504830'>say,</span> <span m='4505100'>I</span> <span m='4505170'>failed.</span>
  </p><p><span m='4508290'>It</span> <span m='4508390'>doesn't</span> <span m='4508650'>go</span>
  <span m='4508780'>to</span> <span m='4508850'>spin</span> <span m='4509280'>or</span>
  <span m='4509430'>to</span> <span m='4509570'>yield</span> <span m='4509950'>or</span>
  <span m='4510030'>anything.</span> <span m='4510350'>It</span> <span m='4510420'>just</span>
  <span m='4510570'>says,</span> <span m='4510820'>oh,</span> <span m='4511130'>I</span>
  <span m='4511290'>failed,</span> <span m='4512130'>and</span> <span m='4512300'>tells</span>
  <span m='4512550'>that</span> <span m='4512770'>back</span> <span m='4513090'>to</span>
  <span m='4513200'>the</span> <span m='4514050'>user.</span> <span m='4515750'>But
  it</span> <span m='4515910'>doesn't</span> <span m='4516130'>attempt</span> <span
  m='4516420'>to</span> <span m='4516500'>block.</span> <span m='4518710'>So</span>
  <span m='4518910'>with</span> <span m='4519090'>try_lock</span> <span m='4519860'>now,</span>
  <span m='4520150'>what</span> <span m='4520400'>can</span> <span m='4520540'>these</span>
  <span m='4520720'>other</span> <span m='4522410'>processors</span> <span m='4523410'>do?</span>
  <span m='4523610'>They</span> <span m='4523790'>do</span> <span m='4523950'>a</span>
  <span m='4524010'>try_lock--</span> <span m='4524940'>yeah?</span> </p><p><span
  m='4525440'>AUDIENCE:</span> <span m='4525888'>[INAUDIBLE]</span> </p><p><span m='4527680'>PROFESSOR:</span>
  <span m='4528130'>Exactly.</span> <span m='4530190'>Instead</span> <span m='4530680'>of</span>
  <span m='4531320'>waiting</span> <span m='4531840'>there</span> <span m='4532130'>on</span>
  <span m='4532250'>the</span> <span m='4532330'>guy</span> <span m='4532650'>that</span>
  <span m='4532870'>they</span> <span m='4533200'>fail</span> <span m='4533660'>on,</span>
  <span m='4534700'>they</span> <span m='4534870'>pick</span> <span m='4535730'>another</span>
  <span m='4536110'>random</span> <span m='4536510'>one</span> <span m='4536740'>to</span>
  <span m='4536850'>steal</span> <span m='4537150'>from.</span> <span m='4539950'>So</span>
  <span m='4540150'>they'll</span> <span m='4540410'>just</span> <span m='4540650'>continually</span>
  <span m='4541540'>try</span> <span m='4541790'>to</span> <span m='4541830'>get it.</span>
  <span m='4542030'>If</span> <span m='4542160'>they</span> <span m='4542270'>get</span>
  <span m='4542530'>it,</span> <span m='4543040'>then</span> <span m='4543300'>they</span>
  <span m='4543410'>can</span> <span m='4543560'>do</span> <span m='4543670'>their</span>
  <span m='4543810'>operation.</span> <span m='4544150'>If</span> <span m='4544260'>they</span>
  <span m='4544370'>don't</span> <span m='4544680'>get</span> <span m='4544860'>it,</span>
  <span m='4546700'>they</span> <span m='4546820'>just</span> <span m='4547380'>look</span>
  <span m='4547610'>elsewhere</span> <span m='4548020'>for</span> <span m='4548180'>work.</span>
  <span m='4550110'>So</span> <span m='4550290'>that's</span> <span m='4550530'>what</span>
  <span m='4550640'>it</span> <span m='4550740'>does.</span> <span m='4551020'>It</span>
  <span m='4551090'>just</span> <span m='4551300'>tries</span> <span m='4551560'>to</span>
  <span m='4551660'>steal</span> <span m='4552000'>again</span> <span m='4552230'>at</span>
  <span m='4552330'>random,</span> <span m='4552770'>rather</span> <span m='4553060'>than</span>
  <span m='4553230'>blocking.</span> </p><p><span m='4557820'>And</span> <span m='4557990'>that</span>
  <span m='4558210'>gets</span> <span m='4558390'>rid</span> <span m='4558620'>of</span>
  <span m='4559710'>this</span> <span m='4559950'>convoying</span> <span m='4560450'>problem.</span>
  <span m='4564090'>As</span> <span m='4564370'>I</span> <span m='4564420'>say,</span>
  <span m='4565020'>dangerous</span> <span m='4565590'>programming,</span> <span m='4566830'>because</span>
  <span m='4568950'>we</span> <span m='4569100'>didn't</span> <span m='4569250'>even</span>
  <span m='4569470'>know</span> <span m='4569650'>we</span> <span m='4569790'>had</span>
  <span m='4569950'>a</span> <span m='4570010'>problem.</span> <span m='4570800'>Just</span>
  <span m='4570980'>our</span> <span m='4571460'>code</span> <span m='4571710'>was</span>
  <span m='4571850'>slower</span> <span m='4572220'>than</span> <span m='4572370'>it</span>
  <span m='4572470'>could</span> <span m='4572610'>have</span> <span m='4572770'>been.</span>
  <span m='4576740'>Questions</span> <span m='4577330'>about</span> <span m='4577650'>convoying?</span>
  </p><p><span m='4584210'>So</span> <span m='4584390'>try_lock</span> <span m='4585030'>is</span>
  <span m='4585170'>actually</span> <span m='4585450'>a very</span> <span m='4585790'>convenient</span>
  <span m='4586320'>thing</span> <span m='4586480'>to</span> <span m='4586570'>use.</span>
  <span m='4587230'>So</span> <span m='4587850'>in</span> <span m='4588050'>many</span>
  <span m='4588470'>cases,</span> <span m='4588940'>you</span> <span m='4589040'>may</span>
  <span m='4589220'>find</span> <span m='4589550'>that,</span> <span m='4589710'>hey,</span>
  <span m='4590270'>rather</span> <span m='4590550'>than</span> <span m='4590720'>waiting</span>
  <span m='4591150'>on</span> <span m='4591350'>something</span> <span m='4591770'>with</span>
  <span m='4591860'>nothing</span> <span m='4592170'>to</span> <span m='4592230'>do,</span>
  <span m='4592450'>let</span> <span m='4592620'>me</span> <span m='4592720'>go</span>
  <span m='4593500'>see</span> <span m='4593640'>if</span> <span m='4593720'>there's</span>
  <span m='4593860'>something</span> <span m='4594160'>else</span> <span m='4594370'>I</span>
  <span m='4594450'>can</span> <span m='4594630'>do</span> <span m='4596790'>in</span>
  <span m='4596910'>the</span> <span m='4596980'>meantime.</span> </p><p><span m='4600320'>Contention.</span>
  <span m='4603760'>So</span> <span m='4603930'>here's</span> <span m='4604980'>an</span>
  <span m='4605140'>example</span> <span m='4606160'>of</span> <span m='4606650'>a</span>
  <span m='4607860'>code</span> <span m='4608270'>where</span> <span m='4608630'>I</span>
  <span m='4608690'>want</span> <span m='4609000'>to</span> <span m='4609220'>add</span>
  <span m='4609540'>up</span> <span m='4610430'>some</span> <span m='4611390'>function</span>
  <span m='4615470'>of</span> <span m='4615700'>the</span> <span m='4615930'>elements</span>
  <span m='4616370'>of</span> <span m='4616460'>some</span> <span m='4616720'>array.</span>
  <span m='4617060'>So</span> <span m='4617200'>here</span> <span m='4617560'>I've</span>
  <span m='4617850'>got</span> <span m='4618530'>a</span> <span m='4619830'>value</span>
  <span m='4620230'>of</span> <span m='4620410'>n,</span> <span m='4621360'>which</span>
  <span m='4621630'>is</span> <span m='4622800'>a</span> <span m='4622880'>million.</span>
  <span m='4624470'>And</span> <span m='4625060'>I</span> <span m='4625480'>have</span>
  <span m='4627490'>a</span> <span m='4627790'>type</span> <span m='4628290'>X.</span>
  <span m='4628770'>So</span> <span m='4632110'>we</span> <span m='4632280'>have</span>
  <span m='4632470'>a</span> <span m='4632640'>compute</span> <span m='4633070'>function,</span>
  <span m='4634020'>which</span> <span m='4637410'>takes</span> <span m='4637880'>a</span>
  <span m='4637930'>pointer</span> <span m='4638350'>to</span> <span m='4638840'>a--</span>
  <span m='4640680'>did I</span> <span m='4641035'>do this right?</span> <span m='4642640'>To</span>
  <span m='4642770'>value</span> <span m='4643185'>V.</span> <span m='4647500'>So</span>
  <span m='4647710'>anyway,</span> <span m='4648150'>my</span> <span m='4648330'>C++</span>
  <span m='4649010'>is</span> <span m='4649140'>not</span> <span m='4649380'>as</span>
  <span m='4649520'>good</span> <span m='4649660'>as</span> <span m='4649750'>my</span>
  <span m='4649920'>C,</span> <span m='4650800'>and</span> <span m='4651150'>for</span>
  <span m='4651260'>those</span> <span m='4651460'>who</span> <span m='4651510'>don't</span>
  <span m='4651750'>know,</span> <span m='4651880'>my</span> <span m='4652040'>C</span>
  <span m='4652290'>isn't</span> <span m='4652520'>very</span> <span m='4652730'>good.</span>
  </p><p><span m='4655220'>So</span> <span m='4655380'>anyway,</span> <span m='4657520'>we</span>
  <span m='4657720'>have</span> <span m='4658020'>an</span> <span m='4658260'>array</span>
  <span m='4658880'>of</span> <span m='4659290'>type</span> <span m='4659660'>X</span>
  <span m='4660370'>of</span> <span m='4660520'>n</span> <span m='4660700'>elements.</span>
  <span m='4663730'>And</span> <span m='4663920'>what</span> <span m='4664040'>I</span>
  <span m='4664120'>do</span> <span m='4664270'>is</span> <span m='4664390'>I</span>
  <span m='4664500'>set</span> <span m='4665280'>result</span> <span m='4665700'>to</span>
  <span m='4665780'>be</span> <span m='4665920'>0,</span> <span m='4666780'>and</span>
  <span m='4666890'>then</span> <span m='4667020'>I</span> <span m='4667150'>have</span>
  <span m='4667270'>a</span> <span m='4667390'>loop</span> <span m='4667720'>here</span>
  <span m='4668000'>which</span> <span m='4668210'>basically</span> <span m='4668780'>goes</span>
  <span m='4669370'>and</span> <span m='4669850'>adds</span> <span m='4670220'>into</span>
  <span m='4670520'>result</span> <span m='4671930'>the</span> <span m='4672090'>result</span>
  <span m='4672520'>of</span> <span m='4672630'>computing</span> <span m='4673160'>on</span>
  <span m='4673510'>each</span> <span m='4673670'>element</span> <span m='4674000'>of</span>
  <span m='4674130'>the</span> <span m='4674280'>array.</span> <span m='4675220'>And</span>
  <span m='4675490'>then it</span> <span m='4675590'>outputs</span> <span m='4676000'>the</span>
  <span m='4676080'>result.</span> <span m='4678810'>Does</span> <span m='4679030'>everybody</span>
  <span m='4679220'>understand</span> <span m='4679640'>what's</span> <span m='4679820'>going</span>
  <span m='4680040'>on</span> <span m='4680190'>in</span> <span m='4680240'>the</span>
  <span m='4680320'>code?</span> <span m='4680940'>It's</span> <span m='4681210'>basically</span>
  <span m='4681630'>compute</span> <span m='4682470'>on</span> <span m='4682680'>every
  element</span> <span m='4682850'>in the array,</span> <span m='4683230'>take</span>
  <span m='4683440'>the</span> <span m='4683530'>result,</span> <span m='4684070'>add</span>
  <span m='4684260'>all</span> <span m='4684440'>those</span> <span m='4684590'>results</span>
  <span m='4685020'>together.</span> </p><p><span m='4686270'>We</span> <span m='4686460'>want</span>
  <span m='4686650'>to</span> <span m='4686690'>parallelize</span> <span m='4687420'>this.</span>
  <span m='4688680'>So</span> <span m='4688870'>let's</span> <span m='4689080'>parallelize</span>
  <span m='4689620'>that.</span> <span m='4692090'>What</span> <span m='4692410'>looks</span>
  <span m='4692640'>like</span> <span m='4692840'>the</span> <span m='4692930'>best</span>
  <span m='4693190'>opportunity</span> <span m='4693820'>for</span> <span m='4693950'>parallelizing?</span>
  <span m='4698970'>Yeah,</span> <span m='4699220'>we</span> <span m='4699310'>go</span>
  <span m='4699490'>after</span> <span m='4699770'>the</span> <span m='4699860'>for</span>
  <span m='4700180'>and</span> <span m='4700240'>make</span> <span m='4700450'>it</span>
  <span m='4700540'>be</span> <span m='4700650'>a</span> <span m='4700700'>cilk_for.</span>
  <span m='4701490'>Let's add</span> <span m='4701820'>all</span> <span m='4701980'>those</span>
  <span m='4702160'>guys</span> <span m='4702450'>up.</span> <span m='4704310'>And</span>
  <span m='4705200'>what's</span> <span m='4705510'>the</span> <span m='4705590'>problem</span>
  <span m='4705870'>with</span> <span m='4705960'>that?</span> <span m='4708490'>We</span>
  <span m='4708660'>get</span> <span m='4708750'>a</span> <span m='4708840'>race.</span>
  <span m='4709580'>What's</span> <span m='4709840'>the</span> <span m='4709950'>race</span>
  <span m='4710260'>on?</span> </p><p><span m='4710590'>AUDIENCE:</span> <span m='4711050'>Result.</span>
  </p><p><span m='4711510'>PROFESSOR:</span> <span m='4711845'>Result.</span> <span
  m='4713360'>They're</span> <span m='4713520'>all</span> <span m='4713830'>updating</span>
  <span m='4714260'>result</span> <span m='4714670'>in</span> <span m='4714770'>parallel.</span>
  <span m='4716200'>Oh,</span> <span m='4716550'>I</span> <span m='4716680'>know</span>
  <span m='4716810'>how</span> <span m='4716960'>to</span> <span m='4717030'>resolve</span>
  <span m='4717450'>a</span> <span m='4717500'>race.</span> <span m='4719910'>Let's</span>
  <span m='4720150'>just</span> <span m='4720840'>put</span> <span m='4721000'>a</span>
  <span m='4721050'>lock</span> <span m='4721360'>around</span> <span m='4721760'>it.</span>
  <span m='4723800'>So</span> <span m='4723930'>here</span> <span m='4724130'>we</span>
  <span m='4724210'>have</span> <span m='4724340'>the</span> <span m='4724440'>race.</span>
  <span m='4728460'>First,</span> <span m='4728680'>let's</span> <span m='4728900'>analyze</span>
  <span m='4729430'>this.</span> <span m='4730630'>So</span> <span m='4730810'>the</span>
  <span m='4730880'>work</span> <span m='4731160'>here</span> <span m='4731390'>is</span>
  <span m='4731490'>order n.</span> <span m='4733940'>What</span> <span m='4734120'>is</span>
  <span m='4734340'>the</span> <span m='4734770'>span?</span> </p><p><span m='4735320'>AUDIENCE:</span>
  <span m='4735780'>Log n.</span> </p><p><span m='4736240'>PROFESSOR:</span> <span
  m='4736700'>Yeah, the</span> <span m='4736770'>span</span> <span m='4737140'>is</span>
  <span m='4737270'>log n</span> <span m='4737900'>for</span> <span m='4738010'>the</span>
  <span m='4738100'>control</span> <span m='4738710'>of</span> <span m='4738840'>the</span>
  <span m='4740000'>stuff</span> <span m='4740290'>here,</span> <span m='4740470'>because</span>
  <span m='4740830'>this is</span> <span m='4741130'>all</span> <span m='4741430'>constant</span>
  <span m='4741880'>time.</span> <span m='4744080'>So</span> <span m='4744550'>the</span>
  <span m='4744650'>running</span> <span m='4745020'>time</span> <span m='4745830'>here</span>
  <span m='4746160'>is</span> <span m='4746700'>order n</span> <span m='4748970'>over</span>
  <span m='4749270'>P</span> <span m='4749500'>plus</span> <span m='4749830'>log n.</span>
  <span m='4751760'>If</span> <span m='4751860'>you</span> <span m='4752010'>remember</span>
  <span m='4752250'>the</span> <span m='4752340'>greedy</span> <span m='4752710'>scheduling,</span>
  <span m='4753240'>it's</span> <span m='4753370'>going</span> <span m='4753460'>to</span>
  <span m='4753500'>be</span> <span m='4753560'>something</span> <span m='4753920'>like</span>
  <span m='4754190'>this,</span> <span m='4755100'>because</span> <span m='4755360'>this</span>
  <span m='4755540'>is</span> <span m='4755660'>the</span> <span m='4755750'>work</span>
  <span m='4756100'>over</span> <span m='4756370'>P</span> <span m='4757010'>plus</span>
  <span m='4757330'>the</span> <span m='4757410'>span.</span> <span m='4760080'>So</span>
  <span m='4760290'>we</span> <span m='4760420'>expect</span> <span m='4760920'>that</span>
  <span m='4761050'>if</span> <span m='4761850'>n</span> <span m='4762080'>over</span>
  <span m='4762350'>P</span> <span m='4762520'>is</span> <span m='4762650'>big</span>
  <span m='4762960'>compared</span> <span m='4763450'>to</span> <span m='4764370'>log
  n,</span> <span m='4765610'>we're</span> <span m='4765720'>going</span> <span m='4765810'>to</span>
  <span m='4765870'>do</span> <span m='4765990'>pretty</span> <span m='4766240'>well,</span>
  <span m='4766760'>because</span> <span m='4767000'>we</span> <span m='4767100'>have</span>
  <span m='4767320'>parallelism</span> <span m='4768060'>over</span> <span m='4768260'>log
  n.</span> </p><p><span m='4771370'>So</span> <span m='4771560'>let's</span> <span
  m='4771850'>fix</span> <span m='4772190'>this</span> <span m='4772450'>bug.</span>
  <span m='4773330'>So</span> <span m='4773480'>this</span> <span m='4773660'>is</span>
  <span m='4773810'>fast</span> <span m='4774260'>code,</span> <span m='4775270'>but
  it's</span> <span m='4775860'>incorrect</span> <span m='4776400'>code.</span> <span
  m='4778030'>So</span> <span m='4778210'>let's</span> <span m='4778480'>fix</span>
  <span m='4778810'>it</span> <span m='4779140'>by</span> <span m='4779260'>getting</span>
  <span m='4779600'>rid</span> <span m='4780010'>of</span> <span m='4780390'>this</span>
  <span m='4780610'>race.</span> <span m='4783040'>So</span> <span m='4783210'>what</span>
  <span m='4783400'>we'll</span> <span m='4783550'>do</span> <span m='4784010'>is</span>
  <span m='4784530'>we'll</span> <span m='4785040'>put</span> <span m='4785270'>a</span>
  <span m='4785510'>lock</span> <span m='4786850'>before.</span> <span m='4787410'>We'll</span>
  <span m='4787560'>introduce</span> <span m='4787960'>a</span> <span m='4788030'>mutex</span>
  <span m='4788590'>L,</span> <span m='4789390'>and</span> <span m='4789520'>we'll</span>
  <span m='4789700'>lock</span> <span m='4790050'>L</span> <span m='4790250'>before</span>
  <span m='4790670'>we</span> <span m='4791620'>add</span> <span m='4791990'>to the</span>
  <span m='4792100'>result,</span> <span m='4792550'>and</span> <span m='4792700'>then</span>
  <span m='4792860'>we'll</span> <span m='4793010'>unlock</span> <span m='4793470'>it.</span>
  </p><p><span m='4795400'>So</span> <span m='4795570'>first</span> <span m='4795900'>of</span>
  <span m='4796000'>all,</span> <span m='4796210'>this</span> <span m='4796380'>is</span>
  <span m='4796520'>a</span> <span m='4796570'>bad</span> <span m='4796950'>way</span>
  <span m='4797140'>to</span> <span m='4797260'>do</span> <span m='4797460'>it,</span>
  <span m='4798840'>because</span> <span m='4799880'>what</span> <span m='4800050'>I</span>
  <span m='4800120'>really</span> <span m='4800410'>should</span> <span m='4800670'>do</span>
  <span m='4800920'>is</span> <span m='4801190'>first</span> <span m='4801710'>compute</span>
  <span m='4802360'>the</span> <span m='4802460'>result</span> <span m='4802980'>of</span>
  <span m='4803170'>my</span> <span m='4803430'>array</span> <span m='4805380'>and</span>
  <span m='4805600'>then</span> <span m='4806010'>lock,</span> <span m='4806850'>add
  it</span> <span m='4807210'>to</span> <span m='4807300'>the</span> <span m='4807370'>result,</span>
  <span m='4807950'>and</span> <span m='4808090'>then</span> <span m='4808260'>unlock</span>
  <span m='4810020'>so</span> <span m='4810210'>that</span> <span m='4810330'>we</span>
  <span m='4810470'>lessen</span> <span m='4810950'>the</span> <span m='4811060'>time</span>
  <span m='4811440'>that</span> <span m='4811550'>I'm</span> <span m='4811640'>holding</span>
  <span m='4812090'>the</span> <span m='4812160'>lock</span> <span m='4812740'>in</span>
  <span m='4812870'>each</span> <span m='4813090'>iteration.</span> <span m='4814200'>Nevertheless,</span>
  <span m='4814720'>this</span> <span m='4814880'>is</span> <span m='4814980'>still</span>
  <span m='4815260'>a lousy</span> <span m='4815590'>piece of</span> <span m='4815980'>code.</span>
  <span m='4816270'>Why's</span> <span m='4816530'>that?</span> </p><p><span m='4817311'>AUDIENCE:</span>
  <span m='4817792'>It's still</span> <span m='4818273'>serialized.</span> </p><p><span
  m='4819235'>PROFESSOR:</span> <span m='4819720'>Yeah, it's</span> <span m='4820050'>serialized.</span>
  <span m='4820820'>Every</span> <span m='4821560'>update</span> <span m='4822570'>to</span>
  <span m='4822750'>result</span> <span m='4823160'>here</span> <span m='4823770'>has</span>
  <span m='4824060'>to</span> <span m='4824180'>go</span> <span m='4824530'>on</span>
  <span m='4825600'>serially.</span> <span m='4827110'>They're</span> <span m='4827270'>n</span>
  <span m='4827530'>accesses.</span> <span m='4828130'>They're</span> <span m='4828280'>all</span>
  <span m='4828500'>going</span> <span m='4828630'>to</span> <span m='4828670'>go</span>
  <span m='4828880'>one</span> <span m='4829120'>at</span> <span m='4829210'>a</span>
  <span m='4829300'>time.</span> <span m='4830760'>So</span> <span m='4831060'>my</span>
  <span m='4831230'>running</span> <span m='4831610'>time,</span> <span m='4832030'>instead</span>
  <span m='4832340'>of</span> <span m='4832410'>being</span> <span m='4833200'>n</span>
  <span m='4833370'>over</span> <span m='4833580'>log</span> <span m='4833920'>n,</span>
  <span m='4834150'>is</span> <span m='4834320'>going</span> <span m='4834450'>to</span>
  <span m='4834520'>be</span> <span m='4836870'>something</span> <span m='4837260'>like</span>
  <span m='4837510'>order n.</span> </p><p><span m='4843490'>Believe</span> <span
  m='4844050'>me,</span> <span m='4844330'>I</span> <span m='4844480'>have</span>
  <span m='4844630'>seen</span> <span m='4844880'>many</span> <span m='4845280'>people</span>
  <span m='4846220'>write</span> <span m='4846520'>code</span> <span m='4848490'>where</span>
  <span m='4849230'>they</span> <span m='4849390'>essentially</span> <span m='4850470'>do</span>
  <span m='4850620'>exactly</span> <span m='4851220'>this.</span> <span m='4853220'>They</span>
  <span m='4853430'>take</span> <span m='4853710'>something,</span> <span m='4854100'>they</span>
  <span m='4854200'>make</span> <span m='4854440'>it</span> <span m='4854580'>parallel,</span>
  <span m='4855580'>they</span> <span m='4855750'>have</span> <span m='4855910'>a</span>
  <span m='4855980'>race</span> <span m='4856340'>bug,</span> <span m='4856830'>they</span>
  <span m='4856990'>fix</span> <span m='4857280'>it</span> <span m='4857370'>with</span>
  <span m='4857520'>a</span> <span m='4857540'>mutex.</span> <span m='4861200'>Bad</span>
  <span m='4861490'>idea,</span> <span m='4862690'>because</span> <span m='4862980'>then</span>
  <span m='4863150'>we</span> <span m='4863310'>end</span> <span m='4863490'>up</span>
  <span m='4864710'>with</span> <span m='4865240'>contention</span> <span m='4865840'>on</span>
  <span m='4866080'>this</span> <span m='4866300'>mutex.</span> <span m='4867170'>What's</span>
  <span m='4867440'>the</span> <span m='4867530'>right</span> <span m='4867850'>way</span>
  <span m='4867970'>to</span> <span m='4868080'>parallelize</span> <span m='4868610'>this?</span>
  <span m='4877900'>Yeah?</span> </p><p><span m='4878395'>AUDIENCE:</span> <span m='4878890'>Maybe</span>
  <span m='4879385'>you could</span> <span m='4879880'>have</span> <span m='4882850'>each</span>
  <span m='4883345'>[INAUDIBLE]</span> <span m='4884830'>have</span> <span m='4885325'>result</span>
  <span m='4885820'>as</span> <span m='4886315'>an</span> <span m='4886810'>array</span>
  <span m='4887305'>and</span> <span m='4887800'>have</span> <span m='4888295'>each</span>
  <span m='4888790'>[INAUDIBLE]</span> <span m='4889780'>one place</span> <span m='4890275'>[INAUDIBLE].</span>
  <span m='4890770'>And then</span> <span m='4891265'>at the</span> <span m='4891760'>end,</span>
  <span m='4892255'>some of all the--</span> </p><p><span m='4892750'>PROFESSOR:</span>
  <span m='4893280'>But won't</span> <span m='4893630'>that be</span> <span m='4893880'>n
  elements</span> <span m='4894330'>to</span> <span m='4894420'>sum</span> <span m='4894720'>up?</span>
  </p><p><span m='4894970'>AUDIENCE:</span> <span m='4895467'>[INAUDIBLE]</span> </p><p><span
  m='4897455'>AUDIENCE:</span> <span m='4897952'>So basically,</span> <span m='4898449'>have,</span>
  <span m='4899443'>say.</span> <span m='4899940'>Eight results,</span> <span m='4900437'>instead
  of</span> <span m='4900934'>having--</span> </p><p><span m='4901440'>PROFESSOR:</span>
  <span m='4901760'>For</span> <span m='4901950'>each</span> <span m='4902250'>thread.</span>
  <span m='4905180'>Good.</span> <span m='4906400'>So that</span> <span m='4906720'>each</span>
  <span m='4906970'>one</span> <span m='4907280'>could</span> <span m='4907450'>keep</span>
  <span m='4907730'>it</span> <span m='4908040'>local</span> <span m='4908450'>to</span>
  <span m='4908580'>its</span> <span m='4908730'>own</span> <span m='4909665'>thread.</span>
  <span m='4910310'>Now,</span> <span m='4910410'>of</span> <span m='4910470'>course,</span>
  <span m='4910680'>that</span> <span m='4911040'>involves</span> <span m='4911570'>me</span>
  <span m='4911690'>knowing</span> <span m='4911990'>how</span> <span m='4912260'>many</span>
  <span m='4912530'>processors</span> <span m='4913180'>I'm</span> <span m='4913320'>running</span>
  <span m='4913610'>on.</span> <span m='4915770'>So</span> <span m='4916630'>now,</span>
  <span m='4917150'>if</span> <span m='4918045'>that</span> <span m='4918410'>number</span>
  <span m='4918780'>changes</span> <span m='4919510'>or</span> <span m='4919810'>whatever--</span>
  <span m='4921490'>there's</span> <span m='4921650'>a</span> <span m='4921700'>way</span>
  <span m='4921890'>of</span> <span m='4922020'>doing</span> <span m='4922290'>it</span>
  <span m='4922410'>completely</span> <span m='4922900'>processor</span> <span m='4923530'>obliviously.</span>
  </p><p><span m='4925570'>AUDIENCE:</span> <span m='4926000'>Divide and conquer.</span>
  </p><p><span m='4926430'>PROFESSOR:</span> <span m='4926860'>Yeah,</span> <span
  m='4927030'>do</span> <span m='4927200'>divide</span> <span m='4927510'>and</span>
  <span m='4927600'>conquer.</span> <span m='4928970'>Add</span> <span m='4929270'>up</span>
  <span m='4929790'>recursively</span> <span m='4930870'>the</span> <span m='4931070'>first</span>
  <span m='4931260'>half</span> <span m='4931500'>of</span> <span m='4931560'>the</span>
  <span m='4931680'>elements,</span> <span m='4932360'>add</span> <span m='4932570'>up</span>
  <span m='4932680'>the</span> <span m='4932760'>second</span> <span m='4933060'>half
  of</span> <span m='4933300'>the</span> <span m='4933440'>elements,</span> <span
  m='4934080'>and</span> <span m='4934250'>add</span> <span m='4934440'>them</span>
  <span m='4934580'>together.</span> <span m='4935820'>Next</span> <span m='4936060'>time,</span>
  <span m='4936260'>we're</span> <span m='4936340'>going</span> <span m='4936410'>to</span>
  <span m='4936480'>see</span> <span m='4936960'>yet</span> <span m='4937210'>another</span>
  <span m='4937600'>mechanism</span> <span m='4938090'>for</span> <span m='4938240'>doing</span>
  <span m='4938520'>that,</span> <span m='4938990'>which</span> <span m='4939280'>gets</span>
  <span m='4940680'>the</span> <span m='4940990'>kind</span> <span m='4941250'>of</span>
  <span m='4941320'>performance</span> <span m='4941920'>that</span> <span m='4942060'>you're</span>
  <span m='4942260'>mentioning</span> <span m='4944260'>but</span> <span m='4944460'>without</span>
  <span m='4944730'>having</span> <span m='4945090'>to</span> <span m='4945320'>rewrite</span>
  <span m='4945780'>the</span> <span m='4945850'>For loop</span> <span m='4946340'>as</span>
  <span m='4946490'>divide</span> <span m='4946800'>and</span> <span m='4946870'>conquer.</span>
  <span m='4947780'>We'll</span> <span m='4947870'>see</span> <span m='4948030'>that</span>
  <span m='4948220'>next</span> <span m='4948450'>time.</span> </p><p><span m='4951390'>So</span>
  <span m='4951840'>in this</span> <span m='4951980'>case,</span> <span m='4952170'>we</span>
  <span m='4952230'>have</span> <span m='4952320'>lock</span> <span m='4952610'>contention</span>
  <span m='4953030'>that</span> <span m='4953130'>takes</span> <span m='4953380'>away
  our</span> <span m='4953640'>parallelism.</span> <span m='4954570'>Unfortunately,</span>
  <span m='4955970'>very</span> <span m='4956310'>little</span> <span m='4956780'>is</span>
  <span m='4957010'>known</span> <span m='4959820'>about</span> <span m='4960230'>lock</span>
  <span m='4960500'>contention.</span> <span m='4960960'>The</span> <span m='4960990'>greedy</span>
  <span m='4961350'>scheduler,</span> <span m='4961900'>you</span> <span m='4962080'>can</span>
  <span m='4962250'>show</span> <span m='4963420'>that</span> <span m='4963620'>it</span>
  <span m='4963810'>achieves</span> <span m='4964730'>T1</span> <span m='4964930'>over</span>
  <span m='4965200'>P</span> <span m='4965430'>plus</span> <span m='4965760'>T</span>
  <span m='4965920'>infinity</span> <span m='4967190'>plus</span> <span m='4968170'>B</span>
  <span m='4969610'>where</span> <span m='4969760'>B</span> <span m='4970070'>is</span>
  <span m='4970290'>the</span> <span m='4970380'>bondage,</span> <span m='4971320'>that
  is,</span> <span m='4971600'>if</span> <span m='4971740'>you</span> <span m='4971850'>add</span>
  <span m='4972310'>the</span> <span m='4972410'>total</span> <span m='4972780'>time</span>
  <span m='4973080'>of</span> <span m='4973200'>all</span> <span m='4973430'>critical</span>
  <span m='4973850'>sections.</span> <span m='4976180'>That's</span> <span m='4976410'>a</span>
  <span m='4976470'>lousy</span> <span m='4976960'>bound,</span> <span m='4977400'>because</span>
  <span m='4977620'>it</span> <span m='4977740'>says,</span> <span m='4978010'>even</span>
  <span m='4978230'>if</span> <span m='4978330'>they're</span> <span m='4978440'>locked</span>
  <span m='4978800'>by</span> <span m='4978930'>different</span> <span m='4979230'>locks,</span>
  <span m='4980650'>you</span> <span m='4980760'>still</span> <span m='4981080'>add</span>
  <span m='4981280'>up</span> <span m='4981430'>the</span> <span m='4981530'>total</span>
  <span m='4981890'>time</span> <span m='4982220'>of</span> <span m='4982310'>all</span>
  <span m='4982600'>the</span> <span m='4982700'>critical</span> <span m='4983070'>sections.</span>
  </p><p><span m='4984100'>And</span> <span m='4984350'>generally,</span> <span m='4984950'>although</span>
  <span m='4985300'>you</span> <span m='4985630'>can</span> <span m='4986390'>improve</span>
  <span m='4986830'>this</span> <span m='4987040'>in</span> <span m='4987160'>special</span>
  <span m='4987550'>cases,</span> <span m='4988360'>the</span> <span m='4988500'>general</span>
  <span m='4988960'>theory</span> <span m='4989400'>for</span> <span m='4989600'>understanding</span>
  <span m='4990060'>contention</span> <span m='4991930'>is</span> <span m='4992120'>not</span>
  <span m='4992370'>understood</span> <span m='4992830'>very</span> <span m='4993040'>well.</span>
  <span m='4994220'>And</span> <span m='4994330'>this</span> <span m='4994470'>upper</span>
  <span m='4994700'>bound</span> <span m='4995000'>is</span> <span m='4995130'>weak,</span>
  <span m='4996870'>but</span> <span m='4997060'>little</span> <span m='4997370'>is</span>
  <span m='4997560'>known</span> <span m='4997840'>about</span> <span m='4998440'>lock</span>
  <span m='4998740'>contention.</span> <span m='5000100'>Very</span> <span m='5000300'>little</span>
  <span m='5000530'>is</span> <span m='5000640'>known</span> <span m='5000810'>about</span>
  <span m='5001080'>lock</span> <span m='5001300'>contention.</span> </p><p><span
  m='5002890'>So</span> <span m='5004010'>to</span> <span m='5004160'>conclude,</span>
  <span m='5006250'>always</span> <span m='5006840'>write</span> <span m='5007220'>deterministic</span>
  <span m='5008050'>programs,</span> <span m='5010220'>unless</span> <span m='5010580'>you</span>
  <span m='5010670'>can't.</span> <span m='5013790'>Always</span> <span m='5014090'>write</span>
  <span m='5014290'>deterministic</span> <span m='5014780'>programs,</span> <span
  m='5015220'>unless</span> <span m='5015410'>you</span> <span m='5015480'>can't.</span>
  <span m='5017410'>Great.</span> </p>
uid: 54ebd2df-0484-8e5a-d82a-102c096747a9
---
