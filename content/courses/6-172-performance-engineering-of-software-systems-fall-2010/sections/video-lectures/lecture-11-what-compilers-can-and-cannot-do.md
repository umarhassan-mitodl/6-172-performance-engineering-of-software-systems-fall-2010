---
about_this_resource_text: <p><strong>Description:</strong> Lecture covering compiler
  hacks, when to optimize, data-flow analysis and optimizations, and instruction scheduling.
  Discussion of quiz, including common mistakes.</p> <p><strong>Speakers:</strong>
  Saman Amarasinghe, Charles Leiserson</p>
content_type: resource
course_id: 6-172-performance-engineering-of-software-systems-fall-2010
embedded_media:
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.172F10/MIT6_172_F10_lec11_300k.mp4
  parent_uid: d03413176a68e88f4be959b08b68f7ab
  title: Video-Internet Archive-MP4
  type: Video
  uid: 2d42833db43c51a9875e3e0639fee075
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/itunes-u/lecture-11-what-compilers/id481759887?i=109649105
  parent_uid: d03413176a68e88f4be959b08b68f7ab
  title: Video-iTunes U-MP4
  type: Video
  uid: 154cb013b9063f972d2f57c041531efb
- id: Video-YouTube-Stream
  media_location: HH1k11sdlTc
  parent_uid: d03413176a68e88f4be959b08b68f7ab
  title: Video-YouTube-Stream
  type: Video
  uid: be075938ba9a74aad4207cdbd21f4243
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/HH1k11sdlTc/default.jpg
  parent_uid: d03413176a68e88f4be959b08b68f7ab
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: beee032f4271d3104a22da288502edb4
- id: MIT6_172F10_lec11.pdf
  parent_uid: d03413176a68e88f4be959b08b68f7ab
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-11-what-compilers-can-and-cannot-do/MIT6_172F10_lec11.pdf
  title: MIT6_172F10_lec11.pdf
  type: null
  uid: 9f08c8723be77ca95d5d645e1150510b
- id: 3Play-3PlayYouTubeid-MP4
  media_location: HH1k11sdlTc
  parent_uid: d03413176a68e88f4be959b08b68f7ab
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 3d63270625019d953ce1e38ece18ca55
- id: HH1k11sdlTc.srt
  parent_uid: d03413176a68e88f4be959b08b68f7ab
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-11-what-compilers-can-and-cannot-do/HH1k11sdlTc.srt
  title: 3play caption file
  type: null
  uid: 7be201b03e1c993c62a8c737ffbfcff1
- id: HH1k11sdlTc.pdf
  parent_uid: d03413176a68e88f4be959b08b68f7ab
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-11-what-compilers-can-and-cannot-do/HH1k11sdlTc.pdf
  title: 3play pdf file
  type: null
  uid: 8a9c8452fbc2b88546fc5e6389d4272d
- id: Caption-3Play YouTube id-SRT
  parent_uid: d03413176a68e88f4be959b08b68f7ab
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b1fe3efc5388cb77ac1360ef05e0d02e
- id: Transcript-3Play YouTube id-PDF
  parent_uid: d03413176a68e88f4be959b08b68f7ab
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 3e2eb14c98643f3b107cd80031b8372e
file: null
file_size: null
hide_download: true
hide_download_original: null
inline_embed_id: 24075555lecture11:whatcompilerscanandcannotdo38243619
layout: video
license: https://creativecommons.org/licenses/by-nc-sa/4.0/
order_index: 126
parent_uid: 24169d0487e846a39c316276f85b8cb5
related_resources_text: ''
short_url: lecture-11-what-compilers-can-and-cannot-do
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-11-what-compilers-can-and-cannot-do
title: 'Lecture 11: What Compilers Can and Cannot Do'
transcript: '<p><span m=''570''>The</span> <span m=''690''>following</span> <span
  m=''1130''>content</span> <span m=''1730''>is</span> <span m=''1840''>provided</span>
  <span m=''2290''>under</span> <span m=''2570''>a</span> <span m=''2590''>Creative</span>
  <span m=''3000''>Commons</span> <span m=''3410''>license.</span> <span m=''4410''>Your</span>
  <span m=''4700''>support</span> <span m=''5210''>will</span> <span m=''5370''>help</span>
  <span m=''5600''>MIT</span> <span m=''6080''>OpenCourseWare</span> <span m=''6860''>continue</span>
  <span m=''7370''>to</span> <span m=''7450''>offer</span> <span m=''7880''>high</span>
  <span m=''8090''>quality</span> <span m=''8620''>educational</span> <span m=''9240''>resources</span>
  <span m=''9890''>for</span> <span m=''10020''>free.</span> <span m=''11100''>To</span>
  <span m=''11230''>make</span> <span m=''11430''>a</span> <span m=''11480''>donation</span>
  <span m=''12120''>or</span> <span m=''12430''>view</span> <span m=''12840''>additional</span>
  <span m=''13300''>materials</span> <span m=''13840''>from</span> <span m=''14000''>hundreds</span>
  <span m=''14430''>of</span> <span m=''14540''>MIT</span> <span m=''14960''>courses,</span>
  <span m=''15970''>visit</span> <span m=''16290''>MIT</span> <span m=''16720''>OpenCourseWare</span>
  <span m=''17750''>at</span> <span m=''17930''>ocw.mit.edu.</span> </p><p><span m=''23290''>PROFESSOR:
  So</span> <span m=''25690''>hopefully</span> <span m=''26260''>by</span> <span m=''26410''>the</span>
  <span m=''26790''>end</span> <span m=''27010''>of</span> <span m=''27090''>the</span>
  <span m=''27190''>class,</span> <span m=''27460''>we will</span> <span m=''27720''>show</span>
  <span m=''28020''>you</span> <span m=''28260''>a</span> <span m=''28570''>histogram</span>
  <span m=''29300''>for</span> <span m=''29740''>the</span> <span m=''30180''>quiz.</span>
  <span m=''31350''>We</span> <span m=''31560''>are</span> <span m=''31590''>very</span>
  <span m=''31790''>happy.</span> <span m=''32930''>You</span> <span m=''33060''>guys</span>
  <span m=''33240''>did</span> <span m=''33370''>really</span> <span m=''33670''>well,</span>
  <span m=''34950''>so</span> <span m=''35150''>we</span> <span m=''35330''>feel</span>
  <span m=''35600''>like,</span> <span m=''35860''>actually,</span> <span m=''36090''>you</span>
  <span m=''36450''>learned</span> <span m=''36650''>something</span> <span m=''37020''>in</span>
  <span m=''37090''>the</span> <span m=''37180''>quiz,</span> <span m=''37360''>so</span>
  <span m=''37530''>it</span> <span m=''37680''>makes</span> <span m=''37870''>us</span>
  <span m=''38000''>happy.</span> <span m=''41820''>We''re</span> <span m=''41970''>hoping</span>
  <span m=''42300''>to</span> <span m=''42420''>have</span> <span m=''42540''>the</span>
  <span m=''43230''>histogram</span> <span m=''43400''>ready</span> <span m=''43730''>by</span>
  <span m=''43920''>now,</span> <span m=''44110''>but</span> <span m=''44360''>we</span>
  <span m=''44450''>don''t.</span> <span m=''45160''>By</span> <span m=''45500''>end</span>
  <span m=''45640''>of</span> <span m=''45700''>the</span> <span m=''45790''>class,</span>
  <span m=''46120''>hopefully we</span> <span m=''46340''>take</span> <span m=''46490''>a</span>
  <span m=''46540''>break</span> <span m=''46810''>in</span> <span m=''46920''>a</span>
  <span m=''46970''>middle,</span> <span m=''47350''>and</span> <span m=''47510''>go
  through</span> <span m=''47900''>rest of</span> <span m=''48360''>that.</span> </p><p><span
  m=''48660''>So</span> <span m=''49290''>we</span> <span m=''49420''>are</span> <span
  m=''49755''>going</span> <span m=''50090''>a little bit</span> <span m=''50240''>off</span>
  <span m=''50480''>from</span> <span m=''50650''>regular</span> <span m=''51010''>programming.</span>
  <span m=''51610''>If</span> <span m=''51730''>you</span> <span m=''51860''>look</span>
  <span m=''52060''>at</span> <span m=''52270''>the</span> <span m=''52520''>class
  schedule,</span> <span m=''53010''>we are</span> <span m=''53360''>going</span>
  <span m=''53580''>to</span> <span m=''53750''>have</span> <span m=''53920''>a</span>
  <span m=''53980''>guest</span> <span m=''54255''>lecture</span> <span m=''54530''>today,</span>
  <span m=''55220''>but</span> <span m=''55950''>I am the</span> <span m=''56240''>guest</span>
  <span m=''56480''>lecture,</span> <span m=''56740''>I</span> <span m=''56790''>guess.</span>
  <span m=''57540''>So</span> <span m=''59000''>I''m</span> <span m=''59380''>going</span>
  <span m=''59610''>to</span> <span m=''59700''>talk</span> <span m=''59950''>about</span>
  <span m=''61560''>what</span> <span m=''62040''>compilers</span> <span m=''62770''>can</span>
  <span m=''63120''>and</span> <span m=''63280''>cannot</span> <span m=''63630''>do</span>
  <span m=''64230''>because,</span> <span m=''65550''>as</span> <span m=''65860''>you</span>
  <span m=''65940''>went</span> <span m=''66240''>on</span> <span m=''66440''>last</span>
  <span m=''66680''>couple</span> <span m=''66880''>of</span> <span m=''66950''>projects,</span>
  <span m=''67550''>you</span> <span m=''67740''>tried</span> <span m=''68080''>hard</span>
  <span m=''68400''>to</span> <span m=''68490''>do</span> <span m=''68750''>weird</span>
  <span m=''69010''>things</span> <span m=''69220''>out</span> <span m=''69370''>of</span>
  <span m=''69420''>the</span> <span m=''69470''>compiler,</span> <span m=''70480''>create</span>
  <span m=''70920''>different</span> <span m=''71230''>piece</span> <span m=''71460''>of</span>
  <span m=''72570''>code,</span> <span m=''72970''>[UNINTELLIGIBLE]</span> <span m=''73740''>programs.</span>
  <span m=''74640''>And</span> <span m=''75250''>so</span> <span m=''75350''>I''m</span>
  <span m=''75550''>going</span> <span m=''75690''>to</span> <span m=''76060''>kind</span>
  <span m=''76320''>of,</span> <span m=''76690''>first,</span> <span m=''77030''>walk</span>
  <span m=''77520''>through</span> <span m=''78700''>some</span> <span m=''79030''>stuff</span>
  <span m=''79430''>that</span> <span m=''79630''>is</span> <span m=''80140''>very</span>
  <span m=''80430''>practical,</span> <span m=''81980''>what</span> <span m=''82560''>the</span>
  <span m=''82880''>current</span> <span m=''83110''>GCC</span> <span m=''83740''>do</span>
  <span m=''83950''>or</span> <span m=''84120''>don''t</span> <span m=''84400''>do.</span>
  </p><p><span m=''84980''>OK,</span> <span m=''85210''>so</span> <span m=''85360''>we''ll</span>
  <span m=''85720''>go</span> <span m=''85920''>through</span> <span m=''86030''>some</span>
  <span m=''86220''>stuff,</span> <span m=''86730''>which</span> <span m=''86860''>is</span>
  <span m=''86950''>interesting,</span> <span m=''87550''>and</span> <span m=''87830''>then</span>
  <span m=''88130''>I''m</span> <span m=''88270''>going</span> <span m=''88460''>to--</span>
  <span m=''89570''>let''s get</span> <span m=''89760''>the outline</span> <span m=''90000''>first.</span>
  <span m=''91480''>OK,</span> <span m=''91730''>this</span> <span m=''91930''>doesn''t</span>
  <span m=''92210''>work.</span> <span m=''100020''>OK.</span> <span m=''102640''>Then</span>
  <span m=''102980''>we will</span> <span m=''103550''>talk a</span> <span m=''103850''>little
  more</span> <span m=''104700''>about</span> <span m=''105860''>where</span> <span
  m=''106310''>the</span> <span m=''106420''>normal</span> <span m=''106710''>optimizations</span>
  <span m=''107450''>happen,</span> <span m=''108750''>what</span> <span m=''108950''>are</span>
  <span m=''109150''>all</span> <span m=''109260''>the</span> <span m=''109380''>possibilities,</span>
  <span m=''110010''>just</span> <span m=''110180''>very</span> <span m=''110380''>quickly,</span>
  <span m=''111080''>to</span> <span m=''111170''>give</span> <span m=''111330''>you</span>
  <span m=''111430''>a</span> <span m=''111480''>feel.</span> <span m=''111830''>It''s
  not</span> <span m=''112140''>all</span> <span m=''112585''>static</span> <span
  m=''113030''>type</span> <span m=''113430''>compilation.</span> <span m=''114250''>And</span>
  <span m=''114760''>then</span> <span m=''114980''>go</span> <span m=''115120''>through</span>
  <span m=''115390''>two</span> <span m=''115560''>things.</span> </p><p><span m=''115830''>One</span>
  <span m=''116120''>is</span> <span m=''116310''>data-flow</span> <span m=''116710''>analysis</span>
  <span m=''117210''>and</span> <span m=''117330''>optimization.</span> <span m=''118090''>That''s</span>
  <span m=''118340''>a</span> <span m=''118400''>big</span> <span m=''118790''>part
  what</span> <span m=''119190''>compilers</span> <span m=''119760''>does.</span>
  <span m=''120380''>And</span> <span m=''120750''>then</span> <span m=''120920''>also</span>
  <span m=''121250''>instructions</span> <span m=''121850''>scheduling.</span> <span
  m=''122660''>Instruction</span> <span m=''122980''>scheduling</span> <span m=''123470''>might</span>
  <span m=''123720''>not</span> <span m=''123880''>be</span> <span m=''123960''>that</span>
  <span m=''124260''>important</span> <span m=''124740''>on a</span> <span m=''124840''>superscalar.</span>
  <span m=''125860''>but</span> <span m=''126080''>it''s</span> <span m=''126240''>always</span>
  <span m=''126560''>good</span> <span m=''126730''>to</span> <span m=''126820''>know</span>
  <span m=''126980''>what</span> <span m=''127200''>it</span> <span m=''127350''>does</span>
  <span m=''127650''>because</span> <span m=''127850''>there</span> <span m=''127990''>are</span>
  <span m=''128039''>some</span> <span m=''128310''>cases</span> <span m=''128740''>where</span>
  <span m=''129190''>you had</span> <span m=''129280''>to</span> <span m=''129449''>do
  it</span> <span m=''129530''>in the</span> <span m=''129650''>compiler</span> <span
  m=''130370''>the</span> <span m=''130699''>hardware</span> <span m=''131130''>cannot</span>
  <span m=''131420''>do,</span> <span m=''131530''>so</span> <span m=''132060''>we''ll</span>
  <span m=''132300''>look</span> <span m=''132480''>at</span> <span m=''132580''>some</span>
  <span m=''132760''>of</span> <span m=''132860''>those</span> <span m=''133050''>cases.</span>
  </p><p><span m=''135880''>So</span> <span m=''137580''>the</span> <span m=''137810''>first</span>
  <span m=''138040''>thing</span> <span m=''138690''>that</span> <span m=''139500''>we</span>
  <span m=''139690''>found</span> <span m=''140000''>a lot</span> <span m=''140240''>of</span>
  <span m=''140380''>you</span> <span m=''140520''>guys</span> <span m=''140920''>did</span>
  <span m=''141730''>is</span> <span m=''143270''>you</span> <span m=''143550''>try</span>
  <span m=''143760''>to</span> <span m=''144040''>inline</span> <span m=''144300''>a</span>
  <span m=''144490''>lot</span> <span m=''144760''>of</span> <span m=''144900''>code</span>
  <span m=''147060''>in</span> <span m=''147770''>your</span> <span m=''147900''>projects,</span>
  <span m=''149060''>and</span> <span m=''149540''>in</span> <span m=''149700''>fact,</span>
  <span m=''150320''>one</span> <span m=''150540''>way</span> <span m=''150640''>to</span>
  <span m=''150740''>do</span> <span m=''150900''>that</span> <span m=''151150''>is</span>
  <span m=''151330''>have you</span> <span m=''151460''>do</span> <span m=''151650''>a</span>
  <span m=''151710''>macro.</span> <span m=''152400''>A</span> <span m=''152650''>macro</span>
  <span m=''153440''>basically</span> <span m=''154440''>make</span> <span m=''154820''>sure</span>
  <span m=''154930''>that</span> <span m=''155340''>definitely</span> <span m=''155580''>get</span>
  <span m=''155820''>in</span> <span m=''155920''>line,</span> <span m=''156500''>but</span>
  <span m=''156790''>macros</span> <span m=''156960''>are</span> <span m=''157210''>ugly.</span>
  <span m=''158450''>There</span> <span m=''158630''>are</span> <span m=''158680''>many</span>
  <span m=''158900''>things</span> <span m=''159100''>you can''t</span> <span m=''159200''>really</span>
  <span m=''159570''>do</span> <span m=''159690''>with</span> <span m=''159800''>a</span>
  <span m=''159920''>macro.</span> </p><p><span m=''161120''>The</span> <span m=''161270''>other</span>
  <span m=''161420''>thing</span> <span m=''161650''>is,</span> <span m=''161780''>we</span>
  <span m=''161920''>can</span> <span m=''162160''>actually</span> <span m=''162440''>do</span>
  <span m=''164660''>simple</span> <span m=''165000''>max</span> <span m=''165460''>calculation</span>
  <span m=''165850''>using</span> <span m=''166520''>function.</span> <span m=''167390''>OK,</span>
  <span m=''167600''>starting</span> <span m=''167760''>function</span> <span m=''168320''>defined.</span>
  <span m=''168800''>And</span> <span m=''169020''>the</span> <span m=''169090''>first</span>
  <span m=''169420''>one</span> <span m=''169580''>is</span> <span m=''169700''>calling</span>
  <span m=''172100''>this</span> <span m=''172440''>one.</span> <span m=''172690''>Second</span>
  <span m=''172980''>one</span> <span m=''173150''>is</span> <span m=''173260''>calling</span>
  <span m=''173510''>this</span> <span m=''173730''>one.</span> <span m=''174580''>So</span>
  <span m=''175850''>what</span> <span m=''176280''>do</span> <span m=''176370''>you</span>
  <span m=''176440''>think</span> <span m=''176630''>this is</span> <span m=''176770''>going</span>
  <span m=''176900''>to</span> <span m=''176960''>do?</span> </p><p><span m=''178790''>How</span>
  <span m=''179490''>many</span> <span m=''179670''>people</span> <span m=''180190''>think</span>
  <span m=''180470''>that</span> <span m=''180760''>the</span> <span m=''181020''>code</span>
  <span m=''181295''>produced</span> <span m=''181790''>between</span> <span m=''182230''>this</span>
  <span m=''182490''>and</span> <span m=''182680''>this</span> <span m=''182960''>going
  to</span> <span m=''183190''>be</span> <span m=''183380''>drastically</span> <span
  m=''183790''>different?</span> <span m=''187530''>Code</span> <span m=''187845''>produced</span>
  <span m=''188340''>for</span> <span m=''188420''>this</span> <span m=''188670''>function</span>
  <span m=''188970''>versus</span> <span m=''189270''>this</span> <span m=''189670''>function</span>
  <span m=''190040''>going</span> <span m=''190170''>to</span> <span m=''190300''>be</span>
  <span m=''190430''>drastically</span> <span m=''191040''>different?</span> <span
  m=''195240''>Real</span> <span m=''195540''>different.</span> <span m=''197180''>For</span>
  <span m=''197660''>some</span> <span m=''197830''>people,</span> <span m=''198050''>[UNINTELLIGIBLE]</span>
  <span m=''198700''>going</span> <span m=''198820''>to be</span> <span m=''198940''>different.</span>
  <span m=''199810''>OK,</span> <span m=''200910''>why</span> <span m=''201110''>do
  you</span> <span m=''201200''>think</span> <span m=''201290''>it''s</span> <span
  m=''201390''>different?</span> </p><p></p><p><span m=''204000''>GUEST SPEAKER: So
  the</span> <span m=''204490''>second function</span> <span m=''204980''>calls</span>
  <span m=''205470''>the first function,</span> <span m=''205960''>and the</span>
  <span m=''206450''>first</span> <span m=''206940''>[INAUDIBLE]</span> <span m=''207430''>calls
  the</span> <span m=''207920''>second one.</span> </p><p><span m=''208410''>PROFESSOR:
  Yes.</span> </p><p><span m=''216950''>AUDIENCE: So</span> <span m=''217930''>since
  you</span> <span m=''218420''>have</span> <span m=''219890''>the first one</span>
  <span m=''220380''>calling</span> <span m=''220870''>max1,</span> <span m=''221360''>which
  is</span> <span m=''221850''>a macro,</span> <span m=''222340''>the</span> <span
  m=''222830''>compiler</span> <span m=''223320''>just copied</span> <span m=''223810''>[UNINTELLIGIBLE]</span>
  <span m=''224790''>out of</span> <span m=''225280''>there.</span> <span m=''226260''>Whereas</span>
  <span m=''226750''>the second</span> <span m=''227240''>one--</span> <span m=''232630''>it
  will</span> <span m=''232870''>try to</span> <span m=''233220''>actually</span>
  <span m=''233570''>optimize</span> <span m=''234040''>the--</span> <span m=''234980''>Won''t
  it</span> <span m=''235450''>try to optimize</span> <span m=''235920''>what is</span>
  <span m=''236390''>inside</span> <span m=''236860''>un64</span> <span m=''238740''>[INAUDIBLE]?</span>
  </p><p><span m=''240540''>PROFESSOR: So what he</span> <span m=''240948''>thinks
  is that is</span> <span m=''241356''>just</span> <span m=''241764''>going to</span>
  <span m=''242172''>get copied.</span> <span m=''242600''>This</span> <span m=''242900''>will</span>
  <span m=''243200''>be</span> <span m=''243670''>still a</span> <span m=''243730''>function</span>
  <span m=''244120''>call,</span> <span m=''244590''>try</span> <span m=''244760''>and</span>
  <span m=''244800''>do</span> <span m=''244950''>some</span> <span m=''245140''>optimizing.</span>
  <span m=''246190''>In</span> <span m=''246470''>fact,</span> <span m=''247080''>what</span>
  <span m=''247520''>it will</span> <span m=''247700''>do</span> <span m=''247960''>is,</span>
  <span m=''248160''>the</span> <span m=''248330''>first</span> <span m=''248510''>function</span>
  <span m=''249970''>is</span> <span m=''250430''>going</span> <span m=''250650''>to
  get</span> <span m=''250790''>inline.</span> <span m=''251970''>Something</span>
  <span m=''252390''>interesting</span> <span m=''252790''>here,</span> <span m=''253020''>what
  you</span> <span m=''253190''>see</span> <span m=''253400''>is</span> <span m=''253950''>even</span>
  <span m=''254350''>though</span> <span m=''254570''>there''s</span> <span m=''254820''>a</span>
  <span m=''254900''>condition</span> <span m=''255470''>here,</span> <span m=''255660''>there''s</span>
  <span m=''255850''>no</span> <span m=''256105''>branch.</span> <span m=''257110''>They</span>
  <span m=''257260''>have</span> <span m=''257420''>the</span> <span m=''257510''>same</span>
  <span m=''257829''>old</span> <span m=''258149''>instruction</span> <span m=''258740''>that</span>
  <span m=''258959''>basically</span> <span m=''260490''>can</span> <span m=''260760''>be</span>
  <span m=''260860''>used</span> <span m=''261160''>to</span> <span m=''261279''>do</span>
  <span m=''261399''>a</span> <span m=''261480''>conditional</span> <span m=''261940''>[UNINTELLIGIBLE].</span>
  <span m=''262610''>So</span> <span m=''263250''>instead of</span> <span m=''263440''>having</span>
  <span m=''263840''>a</span> <span m=''263920''>branch and</span> <span m=''264380''>having
  a</span> <span m=''264700''>pipeline</span> <span m=''265310''>[UNINTELLIGIBLE],</span>
  <span m=''265880''>this</span> <span m=''266080''>managed</span> <span m=''266310''>to</span>
  <span m=''266410''>convert</span> <span m=''266780''>this</span> <span m=''266960''>into</span>
  <span m=''267915''>nice,</span> <span m=''268180''>direct</span> <span m=''268300''>call.</span>
  </p><p><span m=''269240''>The</span> <span m=''269330''>interesting</span> <span
  m=''269710''>thing</span> <span m=''269900''>is</span> <span m=''270000''>the</span>
  <span m=''270070''>second</span> <span m=''270430''>one</span> <span m=''270660''>is</span>
  <span m=''270870''>also</span> <span m=''270980''>identical,</span> <span m=''272370''>so</span>
  <span m=''272550''>what</span> <span m=''272740''>it</span> <span m=''272800''>did</span>
  <span m=''273160''>was</span> <span m=''273340''>it said,</span> <span m=''273490''>hi,</span>
  <span m=''274020''>I</span> <span m=''274130''>know</span> <span m=''274300''>this
  function,</span> <span m=''274810''>I</span> <span m=''274870''>can</span> <span
  m=''275240''>inline.</span> <span m=''275550''>It got</span> <span m=''275850''>inline</span>
  <span m=''276590''>automatically.</span> <span m=''276910''>You</span> <span m=''277230''>didn''t</span>
  <span m=''277440''>tell</span> <span m=''277590''>you</span> <span m=''277680''>to</span>
  <span m=''277790''>do,</span> <span m=''278310''>the</span> <span m=''278440''>compiler</span>
  <span m=''278860''>actually</span> <span m=''279080''>inlined</span> <span m=''279460''>it
  for</span> <span m=''279840''>you,</span> <span m=''280230''>and</span> <span m=''281250''>then</span>
  <span m=''281510''>did</span> <span m=''281730''>all</span> <span m=''281930''>the</span>
  <span m=''282030''>things</span> <span m=''282220''>that</span> <span m=''282360''>are</span>
  <span m=''282390''>necessary.</span> <span m=''283030''>So what</span> <span m=''283240''>that</span>
  <span m=''283550''>means</span> <span m=''283930''>is</span> <span m=''284130''>you</span>
  <span m=''284260''>don''t</span> <span m=''284470''>have</span> <span m=''284690''>to</span>
  <span m=''284920''>write</span> <span m=''285270''>some</span> <span m=''285520''>of</span>
  <span m=''285620''>these</span> <span m=''285980''>ugly</span> <span m=''286340''>macros</span>
  <span m=''287250''>and</span> <span m=''287540''>hand</span> <span m=''287850''>inline.</span>
  <span m=''288430''>You</span> <span m=''288640''>can</span> <span m=''288810''>have</span>
  <span m=''288970''>nice</span> <span m=''289940''>functions</span> <span m=''290350''>in</span>
  <span m=''290490''>there,</span> <span m=''290980''>especially</span> <span m=''291510''>if
  it''s</span> <span m=''291790''>in</span> <span m=''291850''>the</span> <span m=''291930''>same</span>
  <span m=''292200''>file,</span> <span m=''292650''>it can</span> <span m=''292870''>get</span>
  <span m=''292990''>inline.</span> </p><p><span m=''293560''>Of</span> <span m=''293680''>course,</span>
  <span m=''293950''>if</span> <span m=''294050''>you</span> <span m=''294440''>define</span>
  <span m=''294600''>it</span> <span m=''294850''>to</span> <span m=''295040''>different</span>
  <span m=''295340''>file,</span> <span m=''295650''>and</span> <span m=''296630''>this</span>
  <span m=''296810''>file</span> <span m=''297000''>doesn''t</span> <span m=''297230''>have</span>
  <span m=''297330''>access</span> <span m=''297630''>to</span> <span m=''297890''>it,</span>
  <span m=''298110''>it won''t.</span> <span m=''298670''>But</span> <span m=''298840''>if</span>
  <span m=''298900''>it</span> <span m=''298960''>is</span> <span m=''299100''>the</span>
  <span m=''299180''>same</span> <span m=''299430''>file,</span> <span m=''299670''>it''ll</span>
  <span m=''299780''>get</span> <span m=''299930''>inline,</span> <span m=''301690''>so</span>
  <span m=''302650''>you</span> <span m=''302750''>get</span> <span m=''302880''>the</span>
  <span m=''302950''>same</span> <span m=''303230''>result.</span> <span m=''303790''>So</span>
  <span m=''304850''>you</span> <span m=''304940''>can</span> <span m=''305060''>still</span>
  <span m=''305220''>have</span> <span m=''305400''>this</span> <span m=''305580''>nice</span>
  <span m=''305670''>[UNINTELLIGIBLE].</span> <span m=''306170''>You</span> <span
  m=''306280''>don''t</span> <span m=''306400''>have</span> <span m=''306600''>to</span>
  <span m=''306670''>be</span> <span m=''306810''>with</span> <span m=''308110''>optimizations</span>
  <span m=''308485''>at that</span> <span m=''308860''>level.</span> </p><p><span
  m=''310950''>So</span> <span m=''311160''>another</span> <span m=''311410''>thing</span>
  <span m=''311650''>is</span> <span m=''311940''>we</span> <span m=''312070''>have</span>
  <span m=''312210''>this</span> <span m=''312370''>entire--</span> <span m=''313090''>Question?</span>
  </p><p><span m=''313590''>AUDIENCE: On the previous</span> <span m=''314090''>slide,</span>
  <span m=''314583''>other than</span> <span m=''315076''>looking at</span> <span
  m=''315569''>the</span> <span m=''316062''>assembly code,</span> <span m=''316555''>how
  do</span> <span m=''317048''>we know when</span> <span m=''317541''>the</span> <span
  m=''318034''>compiler</span> <span m=''318527''>based this</span> <span m=''319020''>on?</span>
  </p><p><span m=''320500''>PROFESSOR: You''ve</span> <span m=''320810''>got</span>
  <span m=''321120''>the</span> <span m=''321240''>assembly</span> <span m=''321340''>code.</span>
  <span m=''324974''>Question?</span> </p><p><span m=''325468''>AUDIENCE: Why</span>
  <span m=''325962''>do you</span> <span m=''326456''>prefer</span> <span m=''326950''>static</span>
  <span m=''327444''>converge</span> <span m=''327938''>versus</span> <span m=''328432''>inline?</span>
  </p><p><span m=''329420''>PROFESSOR: So</span> <span m=''330120''>the</span> <span
  m=''330495''>reason</span> <span m=''330870''>I did</span> <span m=''331440''>static</span>
  <span m=''331940''>is</span> <span m=''332230''>basically,</span> <span m=''332780''>I</span>
  <span m=''332850''>want</span> <span m=''332960''>to</span> <span m=''333070''>make</span>
  <span m=''333270''>sure</span> <span m=''333410''>it''s</span> <span m=''333630''>not</span>
  <span m=''333870''>visible</span> <span m=''334260''>outside</span> <span m=''334610''>the</span>
  <span m=''334690''>file,</span> <span m=''335710''>so</span> <span m=''335960''>if</span>
  <span m=''336140''>you</span> <span m=''336470''>don''t</span> <span m=''336770''>make</span>
  <span m=''336950''>it</span> <span m=''337070''>static,</span> <span m=''337680''>what''ll</span>
  <span m=''337940''>happen</span> <span m=''338270''>is</span> <span m=''338420''>everybody</span>
  <span m=''338840''>else</span> <span m=''339050''>had</span> <span m=''339230''>the</span>
  <span m=''339300''>visibility</span> <span m=''339690''>and</span> <span m=''339940''>then</span>
  <span m=''340060''>you</span> <span m=''340170''>kind</span> <span m=''340400''>of</span>
  <span m=''340510''>pollute</span> <span m=''341010''>the</span> <span m=''341380''>space</span>
  <span m=''341890''>with</span> <span m=''342050''>a</span> <span m=''342190''>lot</span>
  <span m=''342420''>of</span> <span m=''342490''>names.</span> <span m=''343110''>So</span>
  <span m=''343240''>if</span> <span m=''343330''>you</span> <span m=''343420''>give</span>
  <span m=''343640''>static,</span> <span m=''344010''>it''s</span> <span m=''344150''>only</span>
  <span m=''344360''>within you.</span> <span m=''345200''>If</span> <span m=''345430''>I</span>
  <span m=''345500''>had</span> <span m=''345690''>inline</span> <span m=''345880''>I</span>
  <span m=''346200''>can''t</span> <span m=''346475''>ask</span> <span m=''346750''>it
  to</span> <span m=''347220''>forcefully</span> <span m=''347720''>do</span> <span
  m=''347890''>that,</span> <span m=''348390''>but</span> <span m=''348660''>what</span>
  <span m=''348810''>I''m</span> <span m=''348940''>showing is</span> <span m=''349150''>you
  don''t</span> <span m=''349370''>even</span> <span m=''349440''>have to</span> <span
  m=''349790''>say inline.</span> <span m=''350275''>It''ll inline</span> <span m=''350760''>by</span>
  <span m=''350870''>itself.</span> <span m=''351165''>Question?</span> </p><p><span
  m=''352197''>AUDIENCE: [INAUDIBLE]</span> <span m=''355536''>this function</span>
  <span m=''356013''>to be</span> <span m=''356490''>inline</span> <span m=''356967''>without
  actually</span> <span m=''357444''>[INAUDIBLE]?</span> </p><p><span m=''361250''>PROFESSOR:
  Actually,</span> <span m=''361560''>gprof,</span> <span m=''362070''>what''ll</span>
  <span m=''362680''>happen</span> <span m=''363040''>is</span> <span m=''363500''>the</span>
  <span m=''363660''>file</span> <span m=''363950''>will</span> <span m=''364130''>vanish</span>
  <span m=''364300''>from</span> <span m=''364500''>gprof,</span> <span m=''364870''>isn''t
  it?</span> <span m=''368320''>The</span> <span m=''368440''>function</span> <span
  m=''368930''>will</span> <span m=''369060''>vanish</span> <span m=''369450''>because</span>
  <span m=''369700''>gprof</span> <span m=''369830''>will</span> <span m=''370240''>basically,</span>
  <span m=''370495''>if</span> <span m=''370750''>you have</span> <span m=''370990''>a
  function,</span> <span m=''371270''>you</span> <span m=''371330''>go</span> <span
  m=''371460''>look,</span> <span m=''371860''>you</span> <span m=''371980''>don''t</span>
  <span m=''372200''>see</span> <span m=''372300''>the</span> <span m=''372390''>function.</span>
  <span m=''373090''>And</span> <span m=''373200''>it</span> <span m=''373310''>might</span>
  <span m=''373490''>give,</span> <span m=''373620''>even,</span> <span m=''373780''>a</span>
  <span m=''373880''>bad</span> <span m=''374250''>impression that</span> <span m=''374470''>OK,</span>
  <span m=''374790''>that</span> <span m=''374950''>function</span> <span m=''375280''>is</span>
  <span m=''375370''>not</span> <span m=''375520''>important,</span> <span m=''376950''>so</span>
  <span m=''377060''>that you</span> <span m=''377240''>had</span> <span m=''377320''>to</span>
  <span m=''377400''>be</span> <span m=''377480''>careful</span> <span m=''377940''>in
  that</span> <span m=''379040''>because</span> <span m=''379310''>when</span> <span
  m=''379400''>you</span> <span m=''379540''>look at</span> <span m=''379700''>gprof,</span>
  <span m=''380110''>you will</span> <span m=''380220''>see</span> <span m=''380370''>some</span>
  <span m=''380570''>files.</span> <span m=''381270''>The</span> <span m=''381390''>inline</span>
  <span m=''381766''>find</span> <span m=''382950''>some</span> <span m=''383150''>functions,</span>
  <span m=''383670''>inline</span> <span m=''383860''>function</span> <span m=''384160''>won''t</span>
  <span m=''384330''>be</span> <span m=''384460''>there.</span> </p><p><span m=''386490''>Am
  I right,</span> <span m=''386960''>or</span> <span m=''387190''>is it</span> <span
  m=''387400''>doing</span> <span m=''387660''>anything</span> <span m=''388790''>interesting</span>
  <span m=''389210''>to</span> <span m=''389230''>the</span> <span m=''389320''>samples?</span>
  <span m=''389760''>No.</span> <span m=''390510''>[UNINTELLIGIBLE]</span> <span m=''391690''>vanish</span>
  <span m=''391870''>and</span> <span m=''392160''>oh, yeah,</span> <span m=''392420''>that</span>
  <span m=''392600''>function</span> <span m=''392910''>is</span> <span m=''393010''>not</span>
  <span m=''393150''>important,</span> <span m=''393530''>but</span> <span m=''393690''>in</span>
  <span m=''393830''>fact,</span> <span m=''394330''>it</span> <span m=''394520''>might</span>
  <span m=''394710''>be</span> <span m=''394810''>really</span> <span m=''395050''>important,</span>
  <span m=''395470''>but</span> <span m=''395600''>it</span> <span m=''395690''>got</span>
  <span m=''395800''>inlined.</span> <span m=''396990''>So</span> <span m=''397130''>that''s</span>
  <span m=''397650''>one</span> <span m=''397900''>way</span> <span m=''398010''>to,</span>
  <span m=''398620''>a little bit,</span> <span m=''398760''>worry</span> <span m=''398920''>about.</span>
  <span m=''400330''>Does it</span> <span m=''400480''>make</span> <span m=''400660''>sense?</span>
  <span m=''402840''>OK.</span> </p><p><span m=''404700''>So</span> <span m=''404880''>we
  learned</span> <span m=''405390''>bithacks.</span> <span m=''406200''>So</span>
  <span m=''406340''>it was</span> <span m=''406660''>really</span> <span m=''406890''>fun.</span>
  <span m=''407270''>We</span> <span m=''407650''>are</span> <span m=''407690''>learning</span>
  <span m=''407950''>all</span> <span m=''408160''>these</span> <span m=''408290''>interesting</span>
  <span m=''408690''>bithacks,</span> <span m=''409630''>but</span> <span m=''410580''>the</span>
  <span m=''410640''>interesting</span> <span m=''411000''>thing</span> <span m=''411190''>is,</span>
  <span m=''411320''>in</span> <span m=''411470''>fact,</span> <span m=''411900''>GCC</span>
  <span m=''412280''>compiler</span> <span m=''412660''>also</span> <span m=''413010''>knows</span>
  <span m=''413330''>a lot</span> <span m=''413450''>of</span> <span m=''413580''>bithacks,</span>
  <span m=''414310''>so</span> <span m=''414450''>it''s</span> <span m=''414680''>also</span>
  <span m=''414970''>a pretty</span> <span m=''415370''>smart</span> <span m=''415640''>compiler.</span>
  <span m=''416470''>So</span> <span m=''416670''>if</span> <span m=''416810''>you</span>
  <span m=''416920''>have</span> <span m=''417040''>something</span> <span m=''417310''>like</span>
  <span m=''417540''>this,</span> <span m=''418370''>what</span> <span m=''418610''>do
  you</span> <span m=''418700''>think</span> <span m=''418800''>the smd</span> <span
  m=''418990''>would</span> <span m=''419020''>be?</span> </p><p><span m=''420783''>AUDIENCE:
  [INAUDIBLE].</span> </p><p><span m=''422196''>PROFESSOR: Yeah,</span> <span m=''422670''>it</span>
  <span m=''422910''>actually</span> <span m=''423240''>did</span> <span m=''423610''>this</span>
  <span m=''424020''>one.</span> <span m=''424140''>This</span> <span m=''424290''>is</span>
  <span m=''424430''>very</span> <span m=''424680''>interesting</span> <span m=''425050''>because</span>
  <span m=''425210''>what</span> <span m=''425290''>it</span> <span m=''425620''>did</span>
  <span m=''425930''>was</span> <span m=''427510''>it</span> <span m=''427700''>didn''t</span>
  <span m=''428100''>do</span> <span m=''428410''>shift.</span> <span m=''428770''>It</span>
  <span m=''428870''>did</span> <span m=''429580''>this</span> <span m=''430860''>load</span>
  <span m=''431200''>effective</span> <span m=''431630''>address</span> <span m=''432540''>quad</span>
  <span m=''432900''>instruction,</span> <span m=''433530''>leaq</span> <span m=''434460''>instruction.</span>
  </p><p><span m=''435170''>What</span> <span m=''435400''>it</span> <span m=''435540''>does</span>
  <span m=''435820''>is</span> <span m=''436150''>multiply</span> <span m=''436820''>these</span>
  <span m=''437200''>two,</span> <span m=''438000''>and</span> <span m=''438220''>it''s</span>
  <span m=''438400''>add.</span> <span m=''438800''>It does</span> <span m=''438950''>nothing</span>
  <span m=''439410''>in here</span> <span m=''439570''>to add,</span> <span m=''440770''>and</span>
  <span m=''440970''>then</span> <span m=''441110''>it</span> <span m=''441200''>can</span>
  <span m=''441380''>add</span> <span m=''441520''>a</span> <span m=''441570''>constanant.</span>
  <span m=''442120''>So</span> <span m=''442180''>this</span> <span m=''442410''>very</span>
  <span m=''442950''>complex</span> <span m=''443490''>address</span> <span m=''445220''>mode</span>
  <span m=''445970''>that</span> <span m=''446400''>is being</span> <span m=''446510''>used</span>
  <span m=''446740''>for</span> <span m=''446830''>completely</span> <span m=''447300''>different</span>
  <span m=''447610''>purpose.</span> <span m=''448370''>So</span> <span m=''448540''>this</span>
  <span m=''448840''>[UNINTELLIGIBLE]</span> <span m=''450340''>address.</span> </p><p><span
  m=''450660''>It''s</span> <span m=''450860''>doing</span> <span m=''451400''>this</span>
  <span m=''451620''>multiplied</span> <span m=''452110''>by</span> <span m=''452250''>this,</span>
  <span m=''452560''>there''s</span> <span m=''452710''>nothing</span> <span m=''452980''>to</span>
  <span m=''453070''>add,</span> <span m=''453440''>there''s</span> <span m=''453630''>no</span>
  <span m=''453870''>offset</span> <span m=''454080''>to</span> <span m=''454170''>add,</span>
  <span m=''454526''>save</span> <span m=''454882''>it here.</span> <span m=''459190''>So</span>
  <span m=''459300''>it''s</span> <span m=''459470''>actually</span> <span m=''460280''>doing</span>
  <span m=''460730''>this</span> <span m=''460900''>multiply-by.</span> <span m=''461280''>The</span>
  <span m=''461380''>nice</span> <span m=''461630''>thing</span> <span m=''461940''>is</span>
  <span m=''462160''>it</span> <span m=''462290''>doesn''t</span> <span m=''462500''>affect</span>
  <span m=''462840''>any</span> <span m=''463030''>things</span> <span m=''463330''>like</span>
  <span m=''465020''>condition</span> <span m=''465490''>codes</span> <span m=''465800''>and</span>
  <span m=''465920''>stuff</span> <span m=''466200''>like</span> <span m=''466370''>that,</span>
  <span m=''466530''>so</span> <span m=''466640''>this</span> <span m=''466810''>is</span>
  <span m=''466980''>a</span> <span m=''467560''>fast thing</span> <span m=''467920''>to
  do.</span> <span m=''469100''>OK?</span> </p><p><span m=''470500''>Actually,</span>
  <span m=''470860''>that''s</span> <span m=''471030''>interesting.</span> <span m=''471310''>How
  would</span> <span m=''471685''>[UNINTELLIGIBLE]</span> <span m=''472060''>43?</span>
  <span m=''473960''>That</span> <span m=''474160''>makes</span> <span m=''474480''>it</span>
  <span m=''474570''>a little</span> <span m=''474610''>bit</span> <span m=''474820''>more</span>
  <span m=''474960''>complicated.</span> <span m=''475810''>What do</span> <span m=''476040''>you</span>
  <span m=''476160''>think?</span> <span m=''477200''>How</span> <span m=''477410''>to</span>
  <span m=''477630''>multiply</span> <span m=''478010''>something</span> <span m=''478290''>by</span>
  <span m=''478400''>43?</span> <span m=''483379''>Anybody</span> <span m=''483860''>want</span>
  <span m=''483960''>to</span> <span m=''484060''>take a guess</span> <span m=''484380''>[UNINTELLIGIBLE]</span>
  <span m=''484980''>multiply</span> <span m=''485340''>43</span> <span m=''485650''>[UNINTELLIGIBLE]</span>
  <span m=''486070''>mul43?</span> </p><p><span m=''487870''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''488820''>multiple</span> <span m=''489295''>by</span> <span m=''489770''>32,</span>
  <span m=''490245''>have</span> <span m=''490720''>that</span> <span m=''491195''>multiplied</span>
  <span m=''491670''>by--</span> </p><p><span m=''493570''>PROFESSOR: So</span> <span
  m=''494310''>it</span> <span m=''494420''>did</span> <span m=''494630''>something</span>
  <span m=''494965''>interesting.</span> <span m=''495820''>So</span> <span m=''495980''>here''s</span>
  <span m=''496280''>what</span> <span m=''496590''>it did.</span> <span m=''497350''>I</span>
  <span m=''497410''>want</span> <span m=''497610''>you guys</span> <span m=''497730''>to</span>
  <span m=''498130''>stare</span> <span m=''498465''>at it</span> <span m=''498800''>a
  little</span> <span m=''499040''>bit</span> <span m=''499150''>and see</span> <span
  m=''499250''>if</span> <span m=''499610''>you</span> <span m=''499750''>can</span>
  <span m=''499920''>even</span> <span m=''500200''>figure</span> <span m=''500560''>out</span>
  <span m=''500750''>what''s</span> <span m=''501120''>going</span> <span m=''501420''>on</span>
  <span m=''501590''>here</span> <span m=''502240''>because</span> <span m=''502340''>this</span>
  <span m=''502580''>is</span> <span m=''502740''>kind</span> <span m=''502930''>of</span>
  <span m=''503010''>funky.</span> </p><p><span m=''511120''>So</span> <span m=''511610''>what</span>
  <span m=''511780''>happens</span> <span m=''512120''>after</span> <span m=''512320''>the</span>
  <span m=''512400''>first</span> <span m=''513179''>leaq?</span> <span m=''515090''>What''s</span>
  <span m=''515419''>an</span> <span m=''515640''>rax?</span> <span m=''523789''>What''s</span>
  <span m=''523990''>an</span> <span m=''524090''>rax</span> <span m=''524530''>after</span>
  <span m=''524790''>first</span> <span m=''524980''>leaq</span> <span m=''525480''>instruction?</span>
  <span m=''527890''>Anyone</span> <span m=''528180''>take a</span> <span m=''528460''>wild</span>
  <span m=''528570''>guess?</span> </p><p><span m=''533276''>AUDIENCE: Five?</span>
  </p><p><span m=''534230''>PROFESSOR: Five.</span> <span m=''535170''>Yes,</span>
  <span m=''535250''>exactly.</span> <span m=''535790''>What</span> <span m=''535980''>it</span>
  <span m=''536100''>does</span> <span m=''536350''>is</span> <span m=''536490''>it''s</span>
  <span m=''536660''>4a+a</span> <span m=''537600''>because</span> <span m=''538480''>this</span>
  <span m=''538920''>is</span> <span m=''539090''>a+a,</span> <span m=''540240''>5a</span>
  <span m=''540590''>in</span> <span m=''540870''>here.</span> <span m=''541490''>And</span>
  <span m=''541800''>then</span> <span m=''542430''>after</span> <span m=''542760''>here,</span>
  <span m=''542970''>what</span> <span m=''543140''>happened?</span> <span m=''553320''>4</span>
  <span m=''553720''>times</span> <span m=''554860''>this</span> <span m=''555170''>one</span>
  <span m=''555460''>plus</span> <span m=''555750''>this</span> <span m=''555960''>one.</span>
  </p><p><span m=''561090''>Yeah,</span> <span m=''561190''>it''s</span> <span m=''561480''>21</span>
  <span m=''562230''>because</span> <span m=''562740''>4</span> <span m=''563040''>times</span>
  <span m=''563360''>this</span> <span m=''563560''>is</span> <span m=''563720''>20,</span>
  <span m=''564470''>and</span> <span m=''564670''>you</span> <span m=''564800''>add</span>
  <span m=''564930''>the whole</span> <span m=''565320''>original</span> <span m=''565490''>rax</span>
  <span m=''565840''>21</span> <span m=''566630''>here,</span> <span m=''567600''>21.</span>
  <span m=''568560''>And</span> <span m=''569190''>then</span> <span m=''569400''>you</span>
  <span m=''569490''>do</span> <span m=''569710''>this</span> <span m=''569950''>time</span>
  <span m=''570230''>again</span> <span m=''570660''>42,</span> <span m=''572170''>and</span>
  <span m=''572420''>add</span> <span m=''572600''>another</span> <span m=''572820''>one,</span>
  <span m=''573150''>43.</span> <span m=''574280''>So</span> <span m=''574960''>it</span>
  <span m=''574980''>did</span> <span m=''575280''>all</span> <span m=''575450''>this</span>
  <span m=''575630''>interesting</span> <span m=''576630''>three</span> <span m=''577190''>instructions</span>
  <span m=''577990''>to</span> <span m=''578080''>get</span> <span m=''578270''>to</span>
  <span m=''578730''>43.</span> <span m=''579900''>And</span> <span m=''580730''>so</span>
  <span m=''580870''>this</span> <span m=''581040''>is</span> <span m=''581180''>fun.</span>
  <span m=''581380''>You</span> <span m=''581450''>can</span> <span m=''581590''>spend</span>
  <span m=''581940''>days</span> <span m=''582215''>giving</span> <span m=''582490''>different</span>
  <span m=''582755''>meaning</span> <span m=''583020''>to</span> <span m=''583090''>this</span>
  <span m=''583290''>and</span> <span m=''583430''>see</span> <span m=''583560''>what</span>
  <span m=''584600''>the</span> <span m=''584840''>compiler</span> <span m=''585260''>generates.</span>
  </p><p><span m=''586100''>And</span> <span m=''587040''>I</span> <span m=''587270''>notice</span>
  <span m=''587510''>at some</span> <span m=''587610''>point say,</span> <span m=''588490''>when</span>
  <span m=''588920''>do it</span> <span m=''589120''>give up?</span> <span m=''590310''>And</span>
  <span m=''590560''>it</span> <span m=''590650''>doesn''t</span> <span m=''590900''>give
  up</span> <span m=''591110''>for</span> <span m=''591210''>a</span> <span m=''591310''>while.</span>
  <span m=''591530''>It</span> <span m=''591770''>start</span> <span m=''592080''>creating</span>
  <span m=''592700''>some</span> <span m=''593020''>crazy</span> <span m=''593160''>things.</span>
  <span m=''593320''>OK,</span> <span m=''593870''>try</span> <span m=''594080''>one
  more</span> <span m=''594300''>thing.</span> </p><p><span m=''594940''>OK,</span>
  <span m=''595440''>this</span> <span m=''595600''>has</span> <span m=''595770''>to</span>
  <span m=''595850''>be</span> <span m=''595980''>hard.</span> <span m=''597500''>255.</span>
  <span m=''599180''>How</span> <span m=''599470''>did</span> <span m=''599760''>it
  get</span> <span m=''600040''>254?</span> <span m=''600370''>There''s</span> <span
  m=''601440''>no easy</span> <span m=''601550''>way</span> <span m=''601700''>to</span>
  <span m=''601850''>do</span> <span m=''602010''>that.</span> <span m=''602590''>How</span>
  <span m=''602780''>did</span> <span m=''602970''>that</span> <span m=''603120''>to
  that?</span> <span m=''603370''>This</span> <span m=''603540''>is</span> <span m=''603670''>the</span>
  <span m=''604250''>very</span> <span m=''604510''>interesting</span> <span m=''604890''>thing
  in here,</span> <span m=''605250''>so</span> <span m=''605410''>I will</span> <span
  m=''605700''>show you</span> <span m=''606010''>this one.</span> </p><p><span m=''606410''>So</span>
  <span m=''606810''>here</span> <span m=''607010''>is</span> <span m=''607100''>that</span>
  <span m=''607320''>instructions</span> <span m=''607780''>you</span> <span m=''607880''>generated.</span>
  <span m=''614670''>So</span> <span m=''615250''>what</span> <span m=''615370''>it</span>
  <span m=''615500''>did</span> <span m=''615850''>was,</span> <span m=''617490''>it''s</span>
  <span m=''617740''>doing</span> <span m=''618150''>here,</span> <span m=''618360''>getting</span>
  <span m=''618600''>it</span> <span m=''618730''>2a,</span> <span m=''619500''>by</span>
  <span m=''619730''>doing</span> <span m=''620420''>leaq</span> <span m=''620800''>because</span>
  <span m=''622600''>since</span> <span m=''622830''>it</span> <span m=''622890''>didn''t</span>
  <span m=''623140''>give</span> <span m=''623320''>a</span> <span m=''623390''>multiply,</span>
  <span m=''623730''>it</span> <span m=''623840''>just</span> <span m=''624080''>multiplied</span>
  <span m=''624430''>by</span> <span m=''624540''>1,</span> <span m=''624880''>so</span>
  <span m=''624990''>it''s</span> <span m=''625130''>just</span> <span m=''625310''>adding</span>
  <span m=''625510''>these</span> <span m=''625700''>two.</span> <span m=''626070''>You
  get</span> <span m=''626440''>2a.</span> <span m=''628310''>And</span> <span m=''628560''>then</span>
  <span m=''628860''>it</span> <span m=''630730''>multiplied</span> <span m=''631390''>by</span>
  <span m=''631790''>128</span> <span m=''632750''>by</span> <span m=''633110''>doing</span>
  <span m=''633400''>a</span> <span m=''633450''>bitshift</span> <span m=''633980''>here,</span>
  <span m=''635230''>and</span> <span m=''635900''>then</span> <span m=''636050''>it</span>
  <span m=''636130''>got</span> <span m=''636340''>such a wonderful thing.</span>
  <span m=''637020''>Why</span> <span m=''637430''>did it</span> <span m=''637750''>do</span>
  <span m=''637910''>this</span> <span m=''638260''>instead</span> <span m=''638500''>of</span>
  <span m=''638580''>doing</span> <span m=''638860''>one</span> <span m=''639140''>instruction</span>
  <span m=''639540''>to</span> <span m=''639740''>256?</span> </p><p><span m=''643528''>AUDIENCE:
  [INAUDIBLE].</span> </p><p><span m=''645440''>PROFESSOR: Yeah,</span> <span m=''645670''>then</span>
  <span m=''646010''>it</span> <span m=''646300''>went</span> <span m=''646520''>and</span>
  <span m=''646880''>subtracted</span> <span m=''647350''>a</span> <span m=''647510''>2a</span>
  <span m=''647910''>again,</span> <span m=''648470''>and</span> <span m=''648810''>got</span>
  <span m=''648910''>254.</span> <span m=''650560''>So</span> <span m=''650730''>it</span>
  <span m=''650900''>went</span> <span m=''651070''>overshoot,</span> <span m=''651930''>subtract,</span>
  <span m=''652570''>and</span> <span m=''652720''>subject</span> <span m=''653260''>one
  more,</span> <span m=''653430''>so</span> <span m=''653710''>[UNINTELLIGIBLE]</span>
  <span m=''653980''>got</span> <span m=''654090''>calculated</span> <span m=''654375''>here.</span>
  <span m=''655210''>It</span> <span m=''655340''>does a</span> <span m=''655630''>really</span>
  <span m=''656090''>smart</span> <span m=''656630''>way,</span> <span m=''656810''>I</span>
  <span m=''656940''>don''t</span> <span m=''657070''>know</span> <span m=''657210''>what</span>
  <span m=''657570''>complex</span> <span m=''657950''>logic</span> <span m=''658280''>is</span>
  <span m=''658460''>there,</span> <span m=''659060''>to</span> <span m=''659150''>basically</span>
  <span m=''659770''>figure</span> <span m=''660200''>out</span> <span m=''660710''>these</span>
  <span m=''661040''>combinations</span> <span m=''661620''>of</span> <span m=''661710''>instructions</span>
  <span m=''662710''>that</span> <span m=''663360''>can</span> <span m=''663540''>do</span>
  <span m=''663630''>multiplication.</span> </p><p><span m=''664620''>We</span> <span
  m=''664740''>planned on</span> <span m=''665120''>a bunch</span> <span m=''665500''>of</span>
  <span m=''665600''>things</span> <span m=''666140''>until</span> <span m=''666610''>we</span>
  <span m=''666790''>run</span> <span m=''667060''>into a</span> <span m=''667160''>couple</span>
  <span m=''667400''>of</span> <span m=''667490''>thousand.</span> <span m=''667840''>It</span>
  <span m=''668190''>was</span> <span m=''668410''>doing</span> <span m=''668650''>these</span>
  <span m=''668830''>weird</span> <span m=''669100''>patterns</span> <span m=''669450''>after</span>
  <span m=''669650''>a</span> <span m=''669750''>couple</span> <span m=''669850''>of</span>
  <span m=''669950''>thousand.</span> <span m=''671050''>Especially</span> <span m=''672660''>if</span>
  <span m=''672810''>it</span> <span m=''672930''>is</span> <span m=''673100''>to</span>
  <span m=''673320''>close</span> <span m=''673910''>to</span> <span m=''674980''>2</span>
  <span m=''675330''>to the power,</span> <span m=''675480''>it</span> <span m=''675710''>easily</span>
  <span m=''676000''>find</span> <span m=''676490''>it.</span> <span m=''676790''>Even</span>
  <span m=''677170''>primes,</span> <span m=''677630''>it managed</span> <span m=''677740''>to</span>
  <span m=''677850''>find.</span> </p><p><span m=''678910''>Actually,</span> <span
  m=''679580''>before</span> <span m=''679910''>we</span> <span m=''680030''>gave</span>
  <span m=''680210''>a prime,</span> <span m=''680290''>and it</span> <span m=''680790''>found
  it</span> <span m=''681040''>because</span> <span m=''681310''>it</span> <span m=''681400''>found</span>
  <span m=''681690''>the</span> <span m=''681760''>closest</span> <span m=''682190''>thing,</span>
  <span m=''682450''>and</span> <span m=''682680''>a</span> <span m=''682840''>couple</span>
  <span m=''683090''>of</span> <span m=''683230''>things</span> <span m=''683440''>[UNINTELLIGIBLE],</span>
  <span m=''683660''>and</span> <span m=''683750''>you</span> <span m=''683850''>can</span>
  <span m=''684010''>get</span> <span m=''684130''>to</span> <span m=''684180''>the</span>
  <span m=''684280''>prime.</span> <span m=''686140''>So it''s</span> <span m=''686470''>kind
  of</span> <span m=''686800''>interesting</span> <span m=''687940''>how</span> <span
  m=''688210''>find</span> <span m=''688600''>goes</span> <span m=''690510''>in</span>
  <span m=''691200''>just</span> <span m=''691400''>[UNINTELLIGIBLE]</span> <span
  m=''691740''>multiplies.</span> </p><p><span m=''694375''>AUDIENCE: [INAUDIBLE]?</span>
  </p><p><span m=''698780''>PROFESSOR: So</span> <span m=''699490''>this is a</span>
  <span m=''699953''>very interesting</span> <span m=''700416''>question.</span> <span
  m=''700880''>So</span> <span m=''701150''>what</span> <span m=''701460''>it''s</span>
  <span m=''701730''>doing</span> <span m=''702090''>is,</span> <span m=''702480''>it</span>
  <span m=''702730''>has</span> <span m=''702910''>realized</span> <span m=''703380''>somehow</span>
  <span m=''703790''>that</span> <span m=''703910''>doing</span> <span m=''704270''>a</span>
  <span m=''704300''>direct</span> <span m=''704810''>multiply</span> <span m=''705540''>by</span>
  <span m=''706090''>254</span> <span m=''707410''>is</span> <span m=''708080''>going</span>
  <span m=''708190''>to</span> <span m=''708300''>be</span> <span m=''708420''>slower,</span>
  <span m=''709810''>so</span> <span m=''710080''>the</span> <span m=''710180''>multiply</span>
  <span m=''710650''>instruction--</span> <span m=''711200''>if</span> <span m=''711310''>you</span>
  <span m=''711670''>go,</span> <span m=''712120''>I</span> <span m=''712260''>think</span>
  <span m=''712470''>you</span> <span m=''712570''>can</span> <span m=''712770''>also</span>
  <span m=''712990''>look</span> <span m=''713190''>at</span> <span m=''713620''>multiply</span>
  <span m=''714110''>instruction,</span> <span m=''714510''>how</span> <span m=''714690''>many</span>
  <span m=''714880''>cycles</span> <span m=''715430''>it''s</span> <span m=''715560''>going</span>
  <span m=''715700''>to</span> <span m=''715780''>take</span> <span m=''716510''>to</span>
  <span m=''716620''>come--</span> </p><p><span m=''717010''>AUDIENCE: [INAUDIBLE]?</span>
  </p><p><span m=''720320''>PROFESSOR: Oh,</span> <span m=''720730''>because</span>
  <span m=''721420''>it</span> <span m=''721900''>needs</span> <span m=''722140''>to</span>
  <span m=''722250''>get</span> <span m=''722390''>this</span> <span m=''722560''>2a</span>
  <span m=''722990''>again.</span> <span m=''724470''>So</span> <span m=''724630''>it''s</span>
  <span m=''724780''>[UNINTELLIGIBLE],</span> <span m=''725950''>use the two</span>
  <span m=''726190''>2a.</span> <span m=''727470''>So</span> <span m=''728210''>by</span>
  <span m=''728590''>calculating</span> <span m=''729150''>that,</span> <span m=''730555''>it</span>
  <span m=''730870''>kept it.</span> <span m=''731340''>I</span> <span m=''731590''>don''t</span>
  <span m=''731730''>know,</span> <span m=''731870''>you might</span> <span m=''732110''>be</span>
  <span m=''732330''>right,</span> <span m=''732460''>because</span> <span m=''732810''>if</span>
  <span m=''732950''>it</span> <span m=''733080''>[UNINTELLIGIBLE]</span> <span m=''733200''>2a</span>
  <span m=''733490''>to</span> <span m=''733590''>6n2,</span> <span m=''734310''>then</span>
  <span m=''734460''>there''s</span> <span m=''734670''>no</span> <span m=''734770''>dependency,</span>
  <span m=''735590''>and</span> <span m=''735710''>right</span> <span m=''735810''>now,</span>
  <span m=''736000''>there''s</span> <span m=''736100''>a</span> <span m=''736210''>dependent</span>
  <span m=''736475''>change</span> <span m=''736960''>here.</span> </p><p><span m=''737365''>AUDIENCE:
  [INAUDIBLE]?</span> </p><p><span m=''742680''>PROFESSOR: Twice,</span> <span m=''742840''>yes,</span>
  <span m=''743160''>something</span> <span m=''743470''>like</span> <span m=''743660''>that.</span>
  <span m=''743800''>Or</span> <span m=''744330''>calculate</span> <span m=''744740''>this</span>
  <span m=''745020''>separately.</span> <span m=''745700''>2*8</span> <span m=''746170''>and</span>
  <span m=''746310''>256,</span> <span m=''747000''>and</span> <span m=''747250''>then</span>
  <span m=''747870''>add</span> <span m=''748120''>and</span> <span m=''748230''>subtract</span>
  <span m=''748690''>them.</span> <span m=''749160''>Might</span> <span m=''749460''>be</span>
  <span m=''749700''>interesting.</span> <span m=''750290''>So</span> <span m=''750420''>there
  are</span> <span m=''750590''>other</span> <span m=''750860''>ways</span> <span
  m=''751060''>of</span> <span m=''751170''>doing</span> <span m=''751340''>that,</span>
  <span m=''751470''>so</span> <span m=''751580''>in</span> <span m=''751970''>fact--</span>
  </p><p><span m=''753140''>I</span> <span m=''753250''>don''t</span> <span m=''753350''>know</span>
  <span m=''753420''>why,</span> <span m=''753630''>it</span> <span m=''753780''>might</span>
  <span m=''754040''>be</span> <span m=''754120''>in</span> <span m=''754240''>because</span>
  <span m=''754560''>[UNINTELLIGIBLE].</span> <span m=''755610''>I</span> <span m=''755680''>don''t</span>
  <span m=''755850''>know</span> <span m=''757020''>why they</span> <span m=''757240''>didn''t</span>
  <span m=''757340''>do</span> <span m=''757550''>that.</span> <span m=''758800''>But</span>
  <span m=''759270''>it''s</span> <span m=''759520''>thinking.</span> <span m=''760080''>It''s</span>
  <span m=''760350''>thinking,</span> <span m=''761160''>look</span> <span m=''761330''>at</span>
  <span m=''761480''>all</span> <span m=''761630''>instructions,</span> <span m=''762750''>sequence,</span>
  <span m=''763280''>how</span> <span m=''763380''>long</span> <span m=''763640''>it</span>
  <span m=''763830''>would</span> <span m=''764020''>take,</span> <span m=''764470''>and</span>
  <span m=''764590''>it</span> <span m=''764710''>find</span> <span m=''765000''>this</span>
  <span m=''765140''>interesting</span> <span m=''765480''>sequence.</span> </p><p><span
  m=''765880''>So</span> <span m=''766270''>sometimes</span> <span m=''766780''>when</span>
  <span m=''766890''>you</span> <span m=''766970''>are</span> <span m=''767040''>looking</span>
  <span m=''767310''>into</span> <span m=''767990''>optimized</span> <span m=''768520''>code,</span>
  <span m=''769410''>they</span> <span m=''769820''>will look</span> <span m=''770260''>like</span>
  <span m=''770810''>something</span> <span m=''771340''>crazy</span> <span m=''771690''>that</span>
  <span m=''771840''>you</span> <span m=''771940''>can''t read</span> <span m=''772350''>because</span>
  <span m=''772830''>it</span> <span m=''772990''>does</span> <span m=''773190''>things</span>
  <span m=''773420''>like</span> <span m=''773630''>this.</span> <span m=''774100''>So</span>
  <span m=''774250''>you</span> <span m=''774340''>found</span> <span m=''774840''>a</span>
  <span m=''774970''>simple</span> <span m=''775100''>multiply</span> <span m=''775570''>[UNINTELLIGIBLE],</span>
  <span m=''776100''>and</span> <span m=''776290''>end</span> <span m=''776460''>up</span>
  <span m=''776590''>with</span> <span m=''776700''>a</span> <span m=''776750''>piece</span>
  <span m=''776990''>of</span> <span m=''777090''>code</span> <span m=''777310''>like</span>
  <span m=''777490''>this.</span> <span m=''778120''>And</span> <span m=''778950''>so</span>
  <span m=''779230''>you</span> <span m=''779350''>need</span> <span m=''779490''>to</span>
  <span m=''779560''>kind</span> <span m=''779770''>of</span> <span m=''779840''>decipher,</span>
  <span m=''780310''>seeing</span> <span m=''780510''>what''s</span> <span m=''780730''>going</span>
  <span m=''780940''>on</span> <span m=''781040''>backward.</span> <span m=''782010''>So</span>
  <span m=''782150''>that''s</span> <span m=''782380''>why</span> <span m=''782830''>reading</span>
  <span m=''783150''>assembly</span> <span m=''783410''>is</span> <span m=''783510''>sometimes</span>
  <span m=''783880''>hard,</span> <span m=''784130''>especially</span> <span m=''784360''>optimized</span>
  <span m=''784690''>assembly.</span> </p><p><span m=''786800''>OK,</span> <span m=''787500''>so</span>
  <span m=''788790''>I</span> <span m=''789150''>did</span> <span m=''790570''>absolute</span>
  <span m=''791110''>value,</span> <span m=''792050''>and</span> <span m=''792310''>look,</span>
  <span m=''792580''>it did</span> <span m=''792980''>the</span> <span m=''793080''>bithack</span>
  <span m=''794160''>we</span> <span m=''794480''>basically</span> <span m=''795010''>learned</span>
  <span m=''795300''>in</span> <span m=''795430''>class.</span> <span m=''795720''>You</span>
  <span m=''795860''>can</span> <span m=''796000''>go</span> <span m=''796110''>look</span>
  <span m=''796280''>at</span> <span m=''796460''>that.</span> <span m=''796920''>This</span>
  <span m=''797080''>is</span> <span m=''797210''>the</span> <span m=''797280''>entire</span>
  <span m=''797660''>thing</span> <span m=''798470''>that</span> <span m=''799170''>Charles</span>
  <span m=''800000''>talked</span> <span m=''800220''>about</span> <span m=''800780''>to</span>
  <span m=''800890''>find</span> <span m=''801150''>absolute</span> <span m=''801510''>value.</span>
  <span m=''801960''>It</span> <span m=''802120''>knew</span> <span m=''802280''>that,</span>
  <span m=''802670''>so</span> <span m=''802820''>it has</span> <span m=''803250''>attended</span>
  <span m=''803640''>Charles''</span> <span m=''804340''>lecture.</span> <span m=''805290''>That</span>
  <span m=''805480''>[UNINTELLIGIBLE]</span> <span m=''806140''>programmer.</span>
  </p><p><span m=''808162''>OK,</span> <span m=''809710''>so</span> <span m=''811270''>here''s</span>
  <span m=''811550''>interesting</span> <span m=''812030''>thing.</span> <span m=''813230''>So</span>
  <span m=''813420''>what</span> <span m=''813580''>I</span> <span m=''813740''>did</span>
  <span m=''814010''>was</span> <span m=''814260''>I</span> <span m=''814380''>am
  doing</span> <span m=''814680''>update,</span> <span m=''816180''>and</span> <span
  m=''817250''>I</span> <span m=''817300''>have</span> <span m=''817450''>this</span>
  <span m=''817610''>big</span> <span m=''817980''>large</span> <span m=''818180''>array</span>
  <span m=''818750''>here,</span> <span m=''819200''>and</span> <span m=''819490''>I''m</span>
  <span m=''819670''>checking</span> <span m=''820080''>the</span> <span m=''820290''>index</span>
  <span m=''820650''>to</span> <span m=''820710''>be</span> <span m=''820900''>within</span>
  <span m=''821190''>0</span> <span m=''821920''>and</span> <span m=''822670''>this</span>
  <span m=''822870''>value</span> <span m=''823150''>to</span> <span m=''823270''>before</span>
  <span m=''823390''>I</span> <span m=''823640''>updated,</span> <span m=''824120''>because</span>
  <span m=''824330''>I</span> <span m=''824500''>don''t want</span> <span m=''824670''>to
  write</span> <span m=''825320''>out</span> <span m=''825570''>the</span> <span m=''825640''>bounds</span>
  <span m=''826060''>on this</span> <span m=''826210''>setting.</span> <span m=''828100''>OK?</span>
  <span m=''828760''>Makes</span> <span m=''828960''>sense,</span> <span m=''829360''>because</span>
  <span m=''829520''>I</span> <span m=''829750''>want</span> <span m=''830000''>to</span>
  <span m=''830250''>make</span> <span m=''830460''>sure</span> <span m=''830560''>that</span>
  <span m=''830680''>I</span> <span m=''830740''>write in</span> <span m=''831200''>the</span>
  <span m=''831270''>bound.</span> </p><p><span m=''832550''>Interesting</span> <span
  m=''833050''>thing</span> <span m=''833230''>here</span> <span m=''833500''>is</span>
  <span m=''833810''>I am</span> <span m=''834070''>doing</span> <span m=''834200''>two</span>
  <span m=''834610''>checks,</span> <span m=''834840''>here.</span> <span m=''835630''>I
  end up</span> <span m=''836070''>doing</span> <span m=''836480''>only</span> <span
  m=''836550''>one</span> <span m=''836890''>check</span> <span m=''837120''>here.</span>
  <span m=''838280''>What</span> <span m=''838430''>happened</span> <span m=''838860''>to
  my</span> <span m=''838980''>other</span> <span m=''839110''>check?</span> </p><p><span
  m=''844220''>AUDIENCE: [INAUDIBLE],</span> <span m=''846820''>how</span> <span m=''847185''>big
  was</span> <span m=''847550''>the array,</span> <span m=''847981''>and</span> <span
  m=''848412''>[INAUDIBLE].</span> </p><p><span m=''850136''>PROFESSOR: No,</span>
  <span m=''850570''>no,</span> <span m=''850730''>[UNINTELLIGIBLE]</span> <span m=''851090''>something</span>
  <span m=''851545''>a lot</span> <span m=''852000''>more</span> <span m=''852500''>simpler.</span>
  <span m=''854540''>So</span> <span m=''854840''>to give you</span> <span m=''855230''>a
  hint,</span> <span m=''856400''>this</span> <span m=''856480''>is</span> <span m=''856690''>unsigned</span>
  <span m=''857310''>value,</span> <span m=''858580''>and</span> <span m=''858750''>I''m</span>
  <span m=''858940''>doing</span> <span m=''859180''>unsigned</span> <span m=''859780''>compare.</span>
  <span m=''865400''>What</span> <span m=''865720''>happens</span> <span m=''866070''>if</span>
  <span m=''866150''>the</span> <span m=''866230''>value</span> <span m=''866485''>is</span>
  <span m=''866740''>more</span> <span m=''867010''>than</span> <span m=''867280''>0?</span>
  <span m=''869810''>A</span> <span m=''869900''>signed</span> <span m=''870330''>value</span>
  <span m=''870460''>that''s</span> <span m=''870600''>smaller</span> <span m=''871020''>than</span>
  <span m=''871180''>0</span> <span m=''871530''>is</span> <span m=''871980''>what</span>
  <span m=''872270''>it</span> <span m=''872390''>is</span> <span m=''872510''>like</span>
  <span m=''872710''>in</span> <span m=''872840''>unsigned.</span> <span m=''874020''>It''s</span>
  <span m=''874430''>a</span> <span m=''874520''>huge</span> <span m=''874920''>number.</span>
  <span m=''876540''>It</span> <span m=''876880''>[UNINTELLIGIBLE]</span> <span m=''877150''>to</span>
  <span m=''877210''>be</span> <span m=''877320''>bigger</span> <span m=''877490''>than</span>
  <span m=''877600''>this</span> <span m=''877790''>one,</span> <span m=''879200''>so</span>
  <span m=''879640''>because</span> <span m=''879930''>of</span> <span m=''880000''>that,</span>
  <span m=''880320''>it</span> <span m=''881030''>can</span> <span m=''881190''>just
  say,</span> <span m=''881490''>OK</span> <span m=''881690''>look,</span> <span m=''882540''>I</span>
  <span m=''882660''>don''t</span> <span m=''882780''>have</span> <span m=''882870''>to</span>
  <span m=''882940''>check</span> <span m=''883180''>that.</span> <span m=''883360''>I</span>
  <span m=''883410''>can</span> <span m=''883590''>unsigned</span> <span m=''884010''>compare,</span>
  <span m=''884770''>and</span> <span m=''885080''>I</span> <span m=''885190''>will</span>
  <span m=''885300''>get</span> <span m=''885520''>anything</span> <span m=''885820''>less</span>
  <span m=''886000''>than</span> <span m=''886160''>zero</span> <span m=''886590''>also</span>
  <span m=''886770''>in</span> <span m=''886870''>there.</span> </p><p><span m=''887490''>So</span>
  <span m=''889040''>one</span> <span m=''889240''>more</span> <span m=''889390''>thing.</span>
  <span m=''889590''>So</span> <span m=''890070''>before</span> <span m=''890470''>I</span>
  <span m=''890500''>continue</span> <span m=''890910''>with</span> <span m=''891050''>this</span>
  <span m=''891250''>one,</span> <span m=''891790''>so</span> <span m=''891970''>if</span>
  <span m=''892230''>I</span> <span m=''892310''>actually</span> <span m=''893320''>put</span>
  <span m=''893610''>it in</span> <span m=''893740''>a</span> <span m=''893840''>loop</span>
  <span m=''895920''>and</span> <span m=''896340''>say I''m</span> <span m=''896650''>going
  to</span> <span m=''896960''>trade</span> <span m=''897100''>[UNINTELLIGIBLE]</span>
  <span m=''897560''>to</span> <span m=''897720''>this</span> <span m=''898180''>value</span>
  <span m=''898460''>in here.</span> <span m=''899580''>Then</span> <span m=''899820''>what</span>
  <span m=''899920''>it''ll do</span> <span m=''900375''>is,</span> <span m=''900830''>at</span>
  <span m=''901050''>that</span> <span m=''901290''>point,</span> <span m=''901790''>it''ll</span>
  <span m=''901940''>inline</span> <span m=''902320''>this.</span> <span m=''903420''>And</span>
  <span m=''903670''>when</span> <span m=''903830''>it</span> <span m=''903960''>can</span>
  <span m=''904120''>complete</span> <span m=''904560''>[UNINTELLIGIBLE]</span> <span
  m=''904710''>near</span> <span m=''904940''>the</span> <span m=''905030''>check,</span>
  <span m=''905300''>it</span> <span m=''905490''>will know</span> <span m=''905930''>that,</span>
  <span m=''906150''>in</span> <span m=''906320''>fact,</span> <span m=''908010''>my</span>
  <span m=''908300''>bound</span> <span m=''908660''>is</span> <span m=''908800''>going</span>
  <span m=''909040''>from</span> <span m=''909210''>0</span> <span m=''909600''>to
  this</span> <span m=''909840''>one,</span> <span m=''910280''>so</span> <span m=''910420''>I</span>
  <span m=''910490''>don''t</span> <span m=''910690''>have</span> <span m=''910890''>to</span>
  <span m=''911040''>check the</span> <span m=''911140''>bound.</span> </p><p><span
  m=''912060''>So</span> <span m=''912720''>what</span> <span m=''912970''>this</span>
  <span m=''913220''>did</span> <span m=''913450''>was</span> <span m=''913710''>this</span>
  <span m=''913810''>inlined</span> <span m=''914260''>this</span> <span m=''914740''>function</span>
  <span m=''915080''>in</span> <span m=''915420''>here</span> <span m=''915880''>and</span>
  <span m=''916150''>completely</span> <span m=''916630''>get</span> <span m=''916790''>rid
  of</span> <span m=''917110''>the</span> <span m=''917230''>checks</span> <span m=''917540''>completely,</span>
  <span m=''918920''>and</span> <span m=''919080''>this</span> <span m=''919200''>is</span>
  <span m=''919310''>basically</span> <span m=''919620''>the</span> <span m=''920380''>branch</span>
  <span m=''920790''>condition</span> <span m=''921165''>in here</span> <span m=''921860''>because</span>
  <span m=''922110''>it said,</span> <span m=''922270''>OK,</span> <span m=''922340''>look.</span>
  <span m=''922820''>These</span> <span m=''923050''>things</span> <span m=''923290''>are</span>
  <span m=''923400''>redundant</span> <span m=''923710''>because</span> <span m=''924010''>I</span>
  <span m=''924100''>know</span> <span m=''924860''>because</span> <span m=''925200''>I''m</span>
  <span m=''925730''>trading</span> <span m=''926070''>from</span> <span m=''926290''>this</span>
  <span m=''926450''>to</span> <span m=''926550''>this</span> <span m=''926710''>value</span>
  <span m=''926960''>within</span> <span m=''927270''>these</span> <span m=''927500''>bounds</span>
  <span m=''927900''>[UNINTELLIGIBLE].</span> <span m=''929880''>So</span> <span m=''930050''>it
  is</span> <span m=''930500''>smart</span> <span m=''930730''>in</span> <span m=''930950''>that.</span>
  </p><p><span m=''932320''>Do you</span> <span m=''932750''>see</span> <span m=''932890''>this,</span>
  <span m=''933662''>how</span> <span m=''934050''>this</span> <span m=''934270''>is</span>
  <span m=''934410''>going?</span> <span m=''935060''>Cool</span> <span m=''935340''>stuff</span>
  <span m=''935560''>the</span> <span m=''935660''>compiler does.</span> <span m=''935940''>So
  this</span> <span m=''936300''>is why</span> <span m=''936660''>compilers</span>
  <span m=''937120''>are</span> <span m=''937310''>smart,</span> <span m=''938550''>when</span>
  <span m=''938800''>they are</span> <span m=''938900''>smart.</span> </p><p><span
  m=''940140''>And the</span> <span m=''940390''>interesting</span> <span m=''940770''>thing</span>
  <span m=''940930''>is,</span> <span m=''941060''>here''s</span> <span m=''941510''>another</span>
  <span m=''941650''>one.</span> <span m=''942880''>So</span> <span m=''943090''>now</span>
  <span m=''943340''>see</span> <span m=''943560''>[UNINTELLIGIBLE]</span> <span m=''944120''>imagine,</span>
  <span m=''944850''>because</span> <span m=''945190''>less</span> <span m=''945420''>than</span>
  <span m=''945550''>0,</span> <span m=''946040''>I</span> <span m=''946130''>can</span>
  <span m=''946330''>do</span> <span m=''946430''>that.</span> <span m=''947040''>How</span>
  <span m=''947280''>about</span> <span m=''947470''>if</span> <span m=''947640''>I''m</span>
  <span m=''947850''>checking</span> <span m=''948160''>from</span> <span m=''948310''>5,000?</span>
  </p><p><span m=''951180''>So</span> <span m=''951310''>we</span> <span m=''951420''>generated</span>
  <span m=''951790''>this</span> <span m=''952190''>funky</span> <span m=''952540''>code.</span>
  <span m=''953390''>It</span> <span m=''954040''>subtracted</span> <span m=''954790''>a</span>
  <span m=''955000''>6</span> <span m=''955260''>here</span> <span m=''956650''>in</span>
  <span m=''956780''>the</span> <span m=''956880''>value,</span> <span m=''958500''>and</span>
  <span m=''958810''>then</span> <span m=''959110''>checked</span> <span m=''959480''>for</span>
  <span m=''959680''>[UNINTELLIGIBLE]</span> <span m=''961200''>because</span> <span
  m=''961460''>it</span> <span m=''961620''>kind</span> <span m=''961830''>of</span>
  <span m=''961890''>shifted</span> <span m=''962340''>the</span> <span m=''962430''>value</span>
  <span m=''962690''>to</span> <span m=''963000''>a</span> <span m=''963580''>0</span>
  <span m=''963940''>basis,</span> <span m=''964360''>basically.</span> <span m=''965250''>And</span>
  <span m=''966100''>then</span> <span m=''966280''>you</span> <span m=''966360''>can</span>
  <span m=''966540''>check</span> <span m=''966770''>that</span> <span m=''966970''>thing,</span>
  <span m=''967160''>and</span> <span m=''967280''>then</span> <span m=''968650''>can</span>
  <span m=''968880''>basically</span> <span m=''969360''>get</span> <span m=''969500''>two</span>
  <span m=''969760''>conditions</span> <span m=''970180''>down to</span> <span m=''970440''>one.</span>
  </p><p><span m=''973000''>See,</span> <span m=''973190''>the</span> <span m=''973280''>thing</span>
  <span m=''973720''>is</span> <span m=''974980''>there</span> <span m=''975200''>are</span>
  <span m=''975260''>many</span> <span m=''975560''>places</span> <span m=''976110''>where</span>
  <span m=''976690''>bound</span> <span m=''977050''>checks</span> <span m=''977410''>is</span>
  <span m=''977540''>very</span> <span m=''977780''>important.</span> <span m=''979050''>If</span>
  <span m=''979280''>you</span> <span m=''979380''>are doing</span> <span m=''979490''>a</span>
  <span m=''979570''>lot</span> <span m=''979740''>of</span> <span m=''979830''>adding
  compilation</span> <span m=''980560''>stuff</span> <span m=''980860''>like</span>
  <span m=''981040''>that,</span> <span m=''981180''>if</span> <span m=''981290''>you</span>
  <span m=''981400''>don''t</span> <span m=''981640''>want</span> <span m=''981890''>to</span>
  <span m=''981980''>have</span> <span m=''982400''>buffer overflows</span> <span
  m=''983100''>and</span> <span m=''983180''>stuff,</span> <span m=''983390''>you</span>
  <span m=''983500''>want it</span> <span m=''983650''>with</span> <span m=''983690''>bound</span>
  <span m=''983910''>checks.</span> <span m=''984750''>And so</span> <span m=''984950''>optimizing</span>
  <span m=''985560''>bound</span> <span m=''985825''>checks</span> <span m=''986090''>is</span>
  <span m=''986200''>a</span> <span m=''986250''>very</span> <span m=''986480''>important</span>
  <span m=''986910''>thing.</span> <span m=''987390''>So</span> <span m=''987540''>having</span>
  <span m=''987980''>these</span> <span m=''988240''>kind</span> <span m=''988470''>of</span>
  <span m=''988560''>things</span> <span m=''988870''>can,</span> <span m=''989390''>in</span>
  <span m=''989680''>many</span> <span m=''989930''>programs,</span> <span m=''990380''>probably</span>
  <span m=''990730''>give</span> <span m=''990930''>good</span> <span m=''991140''>performance,</span>
  <span m=''991560''>so</span> <span m=''991630''>that''s</span> <span m=''991870''>why</span>
  <span m=''992470''>compilers</span> <span m=''993130''>are</span> <span m=''993520''>really</span>
  <span m=''993750''>good</span> <span m=''993990''>at</span> <span m=''994340''>it</span>
  <span m=''994480''>and</span> <span m=''994890''>spend</span> <span m=''995200''>time</span>
  <span m=''995770''>trying</span> <span m=''995990''>to</span> <span m=''996060''>do</span>
  <span m=''996200''>bound</span> <span m=''996540''>checks.</span> <span m=''996870''>So</span>
  <span m=''997010''>this</span> <span m=''997140''>is</span> <span m=''997290''>kind</span>
  <span m=''997530''>of</span> <span m=''997660''>interesting</span> <span m=''998980''>way
  of</span> <span m=''999220''>doing that.</span> </p><p><span m=''1002580''>So</span>
  <span m=''1002860''>the</span> <span m=''1002980''>next</span> <span m=''1003290''>thing</span>
  <span m=''1004020''>I</span> <span m=''1004120''>want</span> <span m=''1004360''>to</span>
  <span m=''1004410''>look</span> <span m=''1004540''>at</span> <span m=''1004680''>is</span>
  <span m=''1004790''>vectorization</span> <span m=''1005630''>because</span> <span
  m=''1006150''>all</span> <span m=''1006450''>these</span> <span m=''1009520''>machines</span>
  <span m=''1009960''>we</span> <span m=''1010150''>have</span> <span m=''1010340''>have</span>
  <span m=''1010680''>this</span> <span m=''1010880''>as</span> <span m=''1011010''>the</span>
  <span m=''1011140''>instructions,</span> <span m=''1011790''>that</span> <span m=''1011960''>can
  run</span> <span m=''1012300''>really</span> <span m=''1012510''>fast,</span> <span
  m=''1013310''>and</span> <span m=''1013490''>you</span> <span m=''1013580''>probably</span>
  <span m=''1013820''>saw</span> <span m=''1014060''>it</span> <span m=''1014200''>in</span>
  <span m=''1014320''>there,</span> <span m=''1014860''>and</span> <span m=''1015410''>see</span>
  <span m=''1016030''>what</span> <span m=''1016460''>kind</span> <span m=''1016670''>of</span>
  <span m=''1016790''>code</span> <span m=''1017040''>will</span> <span m=''1017110''>get</span>
  <span m=''1017400''>produced</span> <span m=''1017850''>after</span> <span m=''1018070''>doing</span>
  <span m=''1018280''>something</span> <span m=''1018570''>like</span> <span m=''1018875''>that.</span>
  <span m=''1019180''>So</span> <span m=''1019340''>here''s</span> <span m=''1019630''>a</span>
  <span m=''1019700''>simple</span> <span m=''1020050''>program.</span> </p><p><span
  m=''1021980''>So</span> <span m=''1022210''>I</span> <span m=''1022390''>have</span>
  <span m=''1022580''>two</span> <span m=''1022760''>arrays,</span> <span m=''1023900''>and</span>
  <span m=''1024215''>I''m</span> <span m=''1024530''>just</span> <span m=''1024650''>copying</span>
  <span m=''1025500''>A</span> <span m=''1025890''>to</span> <span m=''1026119''>B,</span>
  <span m=''1027869''>something</span> <span m=''1028220''>very</span> <span m=''1028349''>simple.</span>
  <span m=''1029050''>And</span> <span m=''1029410''>also</span> <span m=''1029720''>the</span>
  <span m=''1029829''>other</span> <span m=''1029940''>thing</span> <span m=''1030130''>to</span>
  <span m=''1030210''>notice,</span> <span m=''1030569''>I</span> <span m=''1030670''>know</span>
  <span m=''1030810''>exactly</span> <span m=''1031380''>from</span> <span m=''1031569''>where</span>
  <span m=''1031810''>to where</span> <span m=''1031980''>I''m</span> <span m=''1032160''>copying,</span>
  <span m=''1032640''>and</span> <span m=''1032790''>I</span> <span m=''1033240''>also</span>
  <span m=''1033579''>know</span> <span m=''1033819''>which</span> <span m=''1033960''>arrays</span>
  <span m=''1034109''>I''m</span> <span m=''1034260''>copying,</span> <span m=''1034480''>so</span>
  <span m=''1035240''>when</span> <span m=''1035380''>you</span> <span m=''1035500''>look</span>
  <span m=''1035650''>at</span> <span m=''1035810''>it,</span> <span m=''1036300''>it</span>
  <span m=''1036470''>produces</span> <span m=''1036910''>a</span> <span m=''1037230''>code
  like</span> <span m=''1037700''>this.</span> <span m=''1038250''>So</span> <span
  m=''1038500''>what</span> <span m=''1038680''>it''s</span> <span m=''1038819''>doing</span>
  <span m=''1039089''>is</span> <span m=''1039390''>it''s</span> <span m=''1039640''>basically</span>
  <span m=''1040369''>making</span> <span m=''1041630''>eax0</span> <span m=''1042394''>here</span>
  <span m=''1042680''>by</span> <span m=''1042890''>doing</span> <span m=''1043150''>xorl.</span>
  <span m=''1044510''>And</span> <span m=''1045310''>then</span> <span m=''1045680''>basically,</span>
  <span m=''1048430''>moving</span> <span m=''1049370''>the</span> <span m=''1049470''>value</span>
  <span m=''1049760''>A</span> <span m=''1050050''>into</span> <span m=''1050535''>the</span>
  <span m=''1051350''>xmm</span> <span m=''1052090''>registers,</span> <span m=''1053110''>much</span>
  <span m=''1053450''>larger.</span> <span m=''1053870''>Instead</span> <span m=''1054080''>of</span>
  <span m=''1054200''>having</span> <span m=''1054450''>to</span> <span m=''1054490''>[UNINTELLIGIBLE]</span>
  <span m=''1055040''>16</span> <span m=''1055440''>of</span> <span m=''1055570''>them,</span>
  <span m=''1056290''>and</span> <span m=''1056510''>copying</span> <span m=''1056890''>it</span>
  <span m=''1057010''>back</span> <span m=''1057540''>into</span> <span m=''1058530''>B.</span>
  </p><p><span m=''1058970''>So</span> <span m=''1059200''>basically,</span> <span
  m=''1059470''>you</span> <span m=''1059740''>are</span> <span m=''1059800''>doing</span>
  <span m=''1060040''>copying</span> <span m=''1060375''>here,</span> <span m=''1061000''>an</span>
  <span m=''1061190''>increment</span> <span m=''1061640''>by</span> <span m=''1061770''>16.</span>
  <span m=''1062230''>By</span> <span m=''1062350''>now,</span> <span m=''1062780''>every</span>
  <span m=''1063080''>refresh,</span> <span m=''1063660''>you''re</span> <span m=''1063800''>coping</span>
  <span m=''1064120''>16</span> <span m=''1064510''>of them.</span> <span m=''1068180''>Why</span>
  <span m=''1068610''>could</span> <span m=''1068850''>I</span> <span m=''1069330''>just</span>
  <span m=''1069540''>be</span> <span m=''1069670''>done</span> <span m=''1070010''>with</span>
  <span m=''1070200''>just</span> <span m=''1070650''>putting</span> <span m=''1070890''>this</span>
  <span m=''1071070''>small</span> <span m=''1071420''>piece</span> <span m=''1071630''>of</span>
  <span m=''1071750''>code?</span> <span m=''1072070''>What</span> <span m=''1072370''>additional</span>
  <span m=''1072740''>information</span> <span m=''1073210''>this</span> <span m=''1073350''>is</span>
  <span m=''1074220''>taking</span> <span m=''1074510''>advantage</span> <span m=''1075010''>of?</span>
  </p><p><span m=''1078064''>AUDIENCE: Does it</span> <span m=''1078553''>know that</span>
  <span m=''1079531''>[INAUDIBLE]?</span> </p><p><span m=''1083940''>PROFESSOR: Exactly,</span>
  <span m=''1084840''>because</span> <span m=''1085280''>it</span> <span m=''1085460''>knows</span>
  <span m=''1085820''>that</span> <span m=''1086020''>it</span> <span m=''1086150''>goes</span>
  <span m=''1086360''>from</span> <span m=''1086510''>0</span> <span m=''1086740''>to</span>
  <span m=''1086910''>this</span> <span m=''1087030''>value.</span> <span m=''1087480''>In</span>
  <span m=''1087580''>fact,</span> <span m=''1087770''>it</span> <span m=''1087960''>knows</span>
  <span m=''1088480''>it''s</span> <span m=''1088630''>a</span> <span m=''1088690''>multiple</span>
  <span m=''1088990''>of</span> <span m=''1089330''>16.</span> <span m=''1089550''>So</span>
  <span m=''1090020''>it knows</span> <span m=''1090160''>that.</span> <span m=''1090480''>That''s</span>
  <span m=''1090920''>why it</span> <span m=''1091140''>do</span> <span m=''1091490''>that.</span>
  </p><p><span m=''1091830''>It</span> <span m=''1092000''>knows</span> <span m=''1092410''>exactly,</span>
  <span m=''1093050''>and</span> <span m=''1093680''>these</span> <span m=''1094180''>things</span>
  <span m=''1094940''>are</span> <span m=''1095420''>nicely</span> <span m=''1096000''>aligned</span>
  <span m=''1096510''>to</span> <span m=''1099360''>the</span> <span m=''1099880''>boundaries,</span>
  <span m=''1100410''>word</span> <span m=''1100650''>boundaries.</span> <span m=''1101150''>So</span>
  <span m=''1101370''>it</span> <span m=''1101510''>knows</span> <span m=''1101760''>that.</span>
  <span m=''1102270''>So</span> <span m=''1102370''>I</span> <span m=''1102440''>can</span>
  <span m=''1102800''>read</span> <span m=''1103160''>that,</span> <span m=''1103360''>and</span>
  <span m=''1103480''>I</span> <span m=''1103600''>know all</span> <span m=''1103870''>those</span>
  <span m=''1104080''>facts,</span> <span m=''1104310''>and</span> <span m=''1104420''>that</span>
  <span m=''1104590''>is</span> <span m=''1104750''>why</span> <span m=''1104970''>I
  can</span> <span m=''1105160''>do this</span> <span m=''1105360''>computation.</span>
  </p><p><span m=''1107400''>So</span> <span m=''1107580''>now,</span> <span m=''1108880''>you</span>
  <span m=''1109080''>start</span> <span m=''1109360''>doing</span> <span m=''1109490''>that,</span>
  <span m=''1109670''>did</span> <span m=''1109730''>one</span> <span m=''1110230''>simple</span>
  <span m=''1110410''>change.</span> <span m=''1110520''>You</span> <span m=''1110690''>start</span>
  <span m=''1111240''>going</span> <span m=''1111710''>from</span> <span m=''1113600''>value,</span>
  <span m=''1113950''>I went</span> <span m=''1114250''>to</span> <span m=''1114400''>end.</span>
  <span m=''1116150''>0</span> <span m=''1116440''>to</span> <span m=''1116720''>end.</span>
  <span m=''1116990''>I</span> <span m=''1117200''>know</span> <span m=''1117330''>where
  it</span> <span m=''1117640''>starts,</span> <span m=''1118360''>and</span> <span
  m=''1118570''>I know</span> <span m=''1118790''>where it''s</span> <span m=''1119900''>ending.</span>
  <span m=''1120070''>Ending is</span> <span m=''1120120''>somewhere at</span> <span
  m=''1120550''>N.</span> <span m=''1121920''>I</span> <span m=''1122050''>don''t</span>
  <span m=''1122180''>know</span> <span m=''1122270''>where the</span> <span m=''1122350''>end</span>
  <span m=''1122490''>is.</span> </p><p><span m=''1125010''>Then</span> <span m=''1125730''>this</span>
  <span m=''1125820''>has</span> <span m=''1126080''>to do something</span> <span
  m=''1126260''>a</span> <span m=''1126525''>little bit</span> <span m=''1126790''>difficult.</span>
  <span m=''1128080''>So</span> <span m=''1128260''>the</span> <span m=''1128410''>code</span>
  <span m=''1128730''>produced</span> <span m=''1129630''>looks</span> <span m=''1129820''>like</span>
  <span m=''1130040''>this</span> <span m=''1130840''>because,</span> <span m=''1131440''>now,</span>
  <span m=''1131710''>I''m</span> <span m=''1131890''>not</span> <span m=''1132040''>going</span>
  <span m=''1132170''>to</span> <span m=''1132210''>go</span> <span m=''1132430''>through</span>
  <span m=''1132510''>this</span> <span m=''1132710''>code.</span> <span m=''1133050''>The
  only thing</span> <span m=''1133620''>to</span> <span m=''1133670''>say,</span>
  <span m=''1133870''>this</span> <span m=''1134160''>is</span> <span m=''1134340''>actually</span>
  <span m=''1134610''>doing</span> <span m=''1134860''>still</span> <span m=''1135330''>a</span>
  <span m=''1135390''>memx</span> <span m=''1135760''>instruction,</span> <span m=''1136790''>but</span>
  <span m=''1136990''>its</span> <span m=''1137130''>trying</span> <span m=''1137310''>to</span>
  <span m=''1137410''>make</span> <span m=''1137620''>sure</span> <span m=''1138000''>that</span>
  <span m=''1138220''>because</span> <span m=''1138620''>N</span> <span m=''1138970''>it</span>
  <span m=''1139100''>might</span> <span m=''1139320''>not</span> <span m=''1139490''>be</span>
  <span m=''1139590''>a</span> <span m=''1139930''>multiple</span> <span m=''1140210''>of</span>
  <span m=''1140920''>16.</span> <span m=''1141750''>You have to</span> <span m=''1142060''>take</span>
  <span m=''1142450''>care</span> <span m=''1142600''>of</span> <span m=''1142750''>the</span>
  <span m=''1143380''>final</span> <span m=''1144400''>number</span> <span m=''1144660''>of</span>
  <span m=''1145510''>iterations</span> <span m=''1146160''>outside</span> <span m=''1146830''>that,</span>
  <span m=''1147140''>so</span> <span m=''1147230''>you</span> <span m=''1147330''>had</span>
  <span m=''1147410''>to</span> <span m=''1147480''>go</span> <span m=''1147640''>up</span>
  <span m=''1147850''>to</span> <span m=''1148480''>the</span> <span m=''1148620''>multiple,</span>
  <span m=''1149110''>and</span> <span m=''1149230''>then</span> <span m=''1149400''>basically</span>
  <span m=''1149870''>do</span> <span m=''1150000''>a</span> <span m=''1150160''>normal</span>
  <span m=''1150440''>loop</span> <span m=''1151140''>one</span> <span m=''1151450''>at</span>
  <span m=''1151530''>a</span> <span m=''1151600''>time.</span> <span m=''1152170''>So</span>
  <span m=''1152610''>as we</span> <span m=''1152730''>produce</span> <span m=''1153160''>a
  little</span> <span m=''1153310''>bit</span> <span m=''1153510''>of</span> <span
  m=''1153610''>a</span> <span m=''1153660''>more</span> <span m=''1153850''>complicated</span>
  <span m=''1154340''>piece</span> <span m=''1154570''>like</span> <span m=''1154770''>that.</span>
  </p><p><span m=''1155960''>So</span> <span m=''1156650''>that''s</span> <span m=''1156690''>[UNINTELLIGIBLE]</span>
  <span m=''1157080''>compiler</span> <span m=''1157170''>has</span> <span m=''1157340''>to</span>
  <span m=''1157640''>do.</span> <span m=''1158690''>And</span> <span m=''1159190''>so</span>
  <span m=''1159600''>then</span> <span m=''1159920''>you</span> <span m=''1160090''>have</span>
  <span m=''1160250''>a</span> <span m=''1160300''>piece</span> <span m=''1160570''>of</span>
  <span m=''1160700''>code</span> <span m=''1160940''>like</span> <span m=''1161170''>this.</span>
  <span m=''1170760''>The</span> <span m=''1170930''>interesting</span> <span m=''1171450''>thing</span>
  <span m=''1171630''>here</span> <span m=''1171960''>is,</span> <span m=''1172510''>now,</span>
  <span m=''1173600''>I</span> <span m=''1173760''>created</span> <span m=''1174730''>basically</span>
  <span m=''1175560''>a</span> <span m=''1177200''>function,</span> <span m=''1178350''>where</span>
  <span m=''1179470''>it''s</span> <span m=''1179580''>not</span> <span m=''1179880''>A</span>
  <span m=''1180220''>and B.</span> <span m=''1180380''>I''m</span> <span m=''1180550''>giving</span>
  <span m=''1180800''>two</span> <span m=''1181240''>arrays</span> <span m=''1181660''>as</span>
  <span m=''1181890''>arguments,</span> <span m=''1183210''>and</span> <span m=''1183440''>then</span>
  <span m=''1183590''>I''m</span> <span m=''1183710''>giving</span> <span m=''1184160''>a</span>
  <span m=''1184240''>size</span> <span m=''1184540''>to</span> <span m=''1184650''>copy,</span>
  <span m=''1184960''>and</span> <span m=''1185100''>I''m</span> <span m=''1185200''>copying</span>
  <span m=''1185580''>that.</span> <span m=''1186450''>And I</span> <span m=''1186660''>would</span>
  <span m=''1186870''>have</span> <span m=''1187110''>an</span> <span m=''1187810''>extremely</span>
  <span m=''1188530''>complicated</span> <span m=''1189060''>thing</span> <span m=''1189280''>that''s</span>
  <span m=''1189710''>getting</span> <span m=''1191800''>generated.</span> </p><p><span
  m=''1192420''>Why</span> <span m=''1192675''>is</span> <span m=''1192930''>it</span>
  <span m=''1193030''>complicated?</span> <span m=''1193650''>What</span> <span m=''1193800''>do</span>
  <span m=''1193940''>I</span> <span m=''1194040''>have</span> <span m=''1194140''>to</span>
  <span m=''1194240''>know,</span> <span m=''1195920''>when</span> <span m=''1196130''>I</span>
  <span m=''1196190''>get</span> <span m=''1196380''>this</span> <span m=''1196550''>function,</span>
  <span m=''1197490''>to</span> <span m=''1197580''>make</span> <span m=''1197830''>sure</span>
  <span m=''1197990''>that,</span> <span m=''1199120''>first</span> <span m=''1199320''>of
  all,</span> <span m=''1200210''>it''s</span> <span m=''1200400''>still</span> <span
  m=''1200810''>doing</span> <span m=''1201150''>xmm</span> <span m=''1201620''>somewhere</span>
  <span m=''1201885''>in</span> <span m=''1202150''>here.</span> <span m=''1204640''>What</span>
  <span m=''1204880''>that</span> <span m=''1205090''>means</span> <span m=''1205430''>is
  it''s</span> <span m=''1205600''>trying</span> <span m=''1205820''>to</span> <span
  m=''1206030''>do</span> <span m=''1206190''>this</span> <span m=''1206430''>very</span>
  <span m=''1206640''>fast</span> <span m=''1206960''>copy</span> <span m=''1207720''>of</span>
  <span m=''1209170''>a</span> <span m=''1209330''>multiple</span> <span m=''1209820''>using</span>
  <span m=''1210090''>[UNINTELLIGIBLE]</span> <span m=''1210590''>instruction.</span>
  </p><p><span m=''1211240''>But</span> <span m=''1212150''>what</span> <span m=''1212430''>else</span>
  <span m=''1212720''>can</span> <span m=''1212860''>happen</span> <span m=''1213270''>in</span>
  <span m=''1213410''>this</span> <span m=''1213580''>function?</span> <span m=''1214280''>Because</span>
  <span m=''1214600''>compilers</span> <span m=''1215190''>delete</span> <span m=''1215540''>all</span>
  <span m=''1215630''>the</span> <span m=''1215730''>cases.</span> <span m=''1216620''>What
  are</span> <span m=''1217040''>other</span> <span m=''1217280''>cases</span> <span
  m=''1217700''>tests</span> <span m=''1217910''>deal</span> <span m=''1218200''>with?</span>
  </p><p><span m=''1221286''>AUDIENCE: May not</span> <span m=''1221752''>be aligned.</span>
  </p><p><span m=''1222690''>PROFESSOR: May</span> <span m=''1222830''>not</span>
  <span m=''1222990''>be</span> <span m=''1223200''>aligned</span> <span m=''1223770''>because,</span>
  <span m=''1224170''>for</span> <span m=''1224330''>example,</span> <span m=''1225230''>because</span>
  <span m=''1225680''>xmm</span> <span m=''1226410''>assumes</span> <span m=''1226950''>that</span>
  <span m=''1227670''>they</span> <span m=''1227830''>had</span> <span m=''1227980''>the</span>
  <span m=''1228550''>word</span> <span m=''1228900''>boundaries.</span> <span m=''1229460''>When</span>
  <span m=''1229620''>you</span> <span m=''1229770''>read</span> <span m=''1229940''>16</span>
  <span m=''1232250''>bytes,</span> <span m=''1232570''>we assume</span> <span m=''1232930''>it''s</span>
  <span m=''1233050''>aligned</span> <span m=''1233410''>with</span> <span m=''1233490''>16-byte</span>
  <span m=''1233970''>boundary.</span> <span m=''1234740''>It</span> <span m=''1234870''>might</span>
  <span m=''1235060''>not be</span> <span m=''1235290''>aligned,</span> <span m=''1235680''>so
  you</span> <span m=''1235780''>have</span> <span m=''1235860''>no</span> <span m=''1236020''>idea</span>
  <span m=''1236270''>where</span> <span m=''1236510''>these</span> <span m=''1236700''>two</span>
  <span m=''1236830''>are</span> <span m=''1236910''>coming</span> <span m=''1237280''>from.</span>
  <span m=''1237470''>So</span> <span m=''1237600''>that''s</span> <span m=''1237760''>one</span>
  <span m=''1237970''>thing</span> <span m=''1238140''>is</span> <span m=''1238270''>they</span>
  <span m=''1238360''>might</span> <span m=''1238560''>not</span> <span m=''1238730''>be</span>
  <span m=''1238810''>aligned.</span> <span m=''1239400''>What</span> <span m=''1239550''>else?</span>
  </p><p><span m=''1239870''>AUDIENCE: They don''t</span> <span m=''1240365''>even
  have to be a</span> <span m=''1240860''>[INAUDIBLE].</span> <span m=''1242345''>Because</span>
  <span m=''1242840''>I mean,</span> <span m=''1243335''>that</span> <span m=''1243830''>thing
  could</span> <span m=''1244325''>just be</span> <span m=''1244820''>copying</span>
  <span m=''1245315''>up to</span> <span m=''1245810''>N.</span> <span m=''1247295''>But</span>
  <span m=''1248285''>it might just</span> <span m=''1248780''>be copying</span> <span
  m=''1249275''>partially</span> <span m=''1249770''>parts of</span> <span m=''1250265''>the
  array.</span> </p><p><span m=''1250760''>PROFESSOR: Yes,</span> <span m=''1251270''>yeah,</span>
  <span m=''1251695''>that''s true.</span> <span m=''1252120''>So what</span> <span
  m=''1252230''>that</span> <span m=''1252560''>means</span> <span m=''1252870''>is
  because</span> <span m=''1253050''>arrays</span> <span m=''1253220''>[UNINTELLIGIBLE]</span>
  <span m=''1253690''>it,</span> <span m=''1253840''>but</span> <span m=''1254160''>arrays</span>
  <span m=''1254350''>is</span> <span m=''1254460''>somewhere</span> <span m=''1254680''>in</span>
  <span m=''1254910''>memory,</span> <span m=''1255310''>just</span> <span m=''1255530''>you
  do</span> <span m=''1255840''>two-point</span> <span m=''1256370''>to</span> <span
  m=''1256600''>starting</span> <span m=''1256980''>point.</span> <span m=''1257610''>That</span>
  <span m=''1257800''>is</span> <span m=''1257940''>what</span> <span m=''1258050''>x
  and</span> <span m=''1258240''>y are</span> <span m=''1258570''>there,</span> <span
  m=''1258740''>two</span> <span m=''1259090''>starting</span> <span m=''1259460''>points</span>
  <span m=''1259690''>in</span> <span m=''1259840''>main</span> <span m=''1260080''>memory,</span>
  <span m=''1260710''>and</span> <span m=''1260830''>start</span> <span m=''1261110''>copying</span>
  <span m=''1261480''>there.</span> </p><p><span m=''1262160''>So</span> <span m=''1262330''>what</span>
  <span m=''1262510''>else</span> <span m=''1262720''>can</span> <span m=''1262850''>happen</span>
  <span m=''1263140''>because</span> <span m=''1263440''>of</span> <span m=''1263560''>that?</span>
  <span m=''1265240''>Because in</span> <span m=''1265490''>A</span> <span m=''1265750''>and</span>
  <span m=''1266010''>B,</span> <span m=''1266210''>we knew</span> <span m=''1266550''>they</span>
  <span m=''1266660''>were</span> <span m=''1267240''>two</span> <span m=''1267650''>separate</span>
  <span m=''1267990''>arrays.</span> <span m=''1268410''>What</span> <span m=''1268830''>else</span>
  <span m=''1269110''>can</span> <span m=''1269250''>happen?</span> <span m=''1275996''>Back</span>
  <span m=''1276488''>there.</span> </p><p><span m=''1276980''>AUDIENCE: [INAUDIBLE].</span>
  </p><p><span m=''1279932''>PROFESSOR: Yes.</span> <span m=''1280430''>So</span>
  <span m=''1280740''>arrays</span> <span m=''1281160''>can</span> <span m=''1281320''>start
  to</span> <span m=''1281590''>overlap,</span> <span m=''1282610''>and</span> <span
  m=''1283050''>if</span> <span m=''1283210''>arrays</span> <span m=''1283370''>are</span>
  <span m=''1283540''>overlapping,</span> <span m=''1284190''>then</span> <span m=''1284360''>you</span>
  <span m=''1284470''>might</span> <span m=''1285280''>end</span> <span m=''1285580''>up</span>
  <span m=''1285870''>in</span> <span m=''1286060''>an interesting</span> <span m=''1286355''>situation.</span>
  <span m=''1287100''>So</span> <span m=''1287230''>you</span> <span m=''1287300''>have</span>
  <span m=''1287430''>to</span> <span m=''1287480''>figure</span> <span m=''1287810''>out</span>
  <span m=''1287940''>if</span> <span m=''1288010''>that</span> <span m=''1288250''>arrays
  are</span> <span m=''1288440''>overlapping,</span> <span m=''1289140''>whether</span>
  <span m=''1289510''>they''re</span> <span m=''1290070''>aligned.</span> <span m=''1290270''>Actually,</span>
  <span m=''1290380''>there</span> <span m=''1290480''>are</span> <span m=''1290670''>two</span>
  <span m=''1290820''>types</span> <span m=''1291080''>of</span> <span m=''1291160''>aligned.</span>
  </p><p><span m=''1291660''>One</span> <span m=''1292040''>is</span> <span m=''1293070''>self-aligning,</span>
  <span m=''1293930''>so</span> <span m=''1294050''>assume</span> <span m=''1295440''>we</span>
  <span m=''1295855''>took</span> <span m=''1296130''>these</span> <span m=''1296690''>arrays</span>
  <span m=''1297460''>and</span> <span m=''1297670''>start</span> <span m=''1298050''>copying</span>
  <span m=''1298570''>from</span> <span m=''1298780''>the</span> <span m=''1298860''>byte</span>
  <span m=''1299550''>3.</span> <span m=''1301550''>So</span> <span m=''1301850''>then</span>
  <span m=''1302080''>what</span> <span m=''1302310''>you</span> <span m=''1302440''>know</span>
  <span m=''1302620''>is</span> <span m=''1302990''>basically</span> <span m=''1303560''>byte</span>
  <span m=''1304000''>3</span> <span m=''1304250''>to</span> <span m=''1304340''>16,</span>
  <span m=''1304800''>it''s</span> <span m=''1304870''>not</span> <span m=''1305090''>aligned.</span>
  <span m=''1305600''>You</span> <span m=''1305730''>can''t</span> <span m=''1306130''>start</span>
  <span m=''1306530''>copying</span> <span m=''1307050''>chunks</span> <span m=''1307310''>in</span>
  <span m=''1307570''>there.</span> <span m=''1307950''>So</span> <span m=''1308090''>you</span>
  <span m=''1308240''>run</span> <span m=''1308470''>bytes,</span> <span m=''1308890''>but</span>
  <span m=''1309230''>when</span> <span m=''1309360''>you</span> <span m=''1309480''>run</span>
  <span m=''1309710''>up</span> <span m=''1309830''>to</span> <span m=''1312350''>13</span>
  <span m=''1312750''>iterations,</span> <span m=''1314130''>then</span> <span m=''1314520''>you</span>
  <span m=''1314780''>end</span> <span m=''1315000''>up in,</span> <span m=''1315290''>again,</span>
  <span m=''1315700''>aligned</span> <span m=''1315940''>chunks.</span> </p><p><span
  m=''1317950''>So</span> <span m=''1318490''>in that</span> <span m=''1318740''>case,</span>
  <span m=''1318920''>you</span> <span m=''1319030''>just</span> <span m=''1319210''>run</span>
  <span m=''1319540''>the</span> <span m=''1319640''>sum</span> <span m=''1320160''>preamble</span>
  <span m=''1320770''>to</span> <span m=''1321480''>first</span> <span m=''1321710''>aligned</span>
  <span m=''1321970''>place,</span> <span m=''1322440''>and</span> <span m=''1322600''>then</span>
  <span m=''1322720''>you</span> <span m=''1322980''>go</span> <span m=''1323080''>to</span>
  <span m=''1323130''>aligned</span> <span m=''1323340''>chunk.</span> <span m=''1323850''>But</span>
  <span m=''1324130''>if</span> <span m=''1324850''>this</span> <span m=''1325100''>is</span>
  <span m=''1325260''>starting</span> <span m=''1325650''>to</span> <span m=''1325790''>at
  3,</span> <span m=''1326040''>this</span> <span m=''1326220''>is</span> <span m=''1326330''>starting</span>
  <span m=''1326690''>at</span> <span m=''1326790''>8,</span> <span m=''1327830''>then</span>
  <span m=''1328000''>they''re</span> <span m=''1328090''>never</span> <span m=''1328230''>going</span>
  <span m=''1328350''>to</span> <span m=''1328460''>be</span> <span m=''1328570''>aligned.</span>
  <span m=''1329160''>The</span> <span m=''1329380''>things</span> <span m=''1329530''>are</span>
  <span m=''1329680''>copying</span> <span m=''1330150''>A and</span> <span m=''1330430''>B</span>
  <span m=''1330580''>are</span> <span m=''1330720''>not</span> <span m=''1330880''>aligned,</span>
  <span m=''1331170''>so</span> <span m=''1331260''>then</span> <span m=''1331430''>you</span>
  <span m=''1331500''>have</span> <span m=''1331650''>to treat</span> <span m=''1331820''>it</span>
  <span m=''1331930''>differently.</span> </p><p><span m=''1333650''>So</span> <span
  m=''1333770''>there''s</span> <span m=''1333930''>a lot</span> <span m=''1334400''>of</span>
  <span m=''1334540''>different</span> <span m=''1334850''>cases</span> <span m=''1335180''>you
  have</span> <span m=''1335380''>to</span> <span m=''1335440''>do,</span> <span m=''1335840''>so</span>
  <span m=''1336540''>if</span> <span m=''1336680''>you</span> <span m=''1336820''>just</span>
  <span m=''1337060''>give</span> <span m=''1337240''>something</span> <span m=''1337530''>like</span>
  <span m=''1337790''>this,</span> <span m=''1338430''>the</span> <span m=''1338560''>problem</span>
  <span m=''1338990''>is</span> <span m=''1339310''>the</span> <span m=''1339430''>compiler</span>
  <span m=''1339930''>has</span> <span m=''1340190''>to</span> <span m=''1340290''>deal</span>
  <span m=''1340660''>with</span> <span m=''1340840''>these</span> <span m=''1341050''>thousands</span>
  <span m=''1341500''>of</span> <span m=''1341590''>different</span> <span m=''1341910''>cases.</span>
  <span m=''1342600''>And</span> <span m=''1342840''>in</span> <span m=''1342980''>this</span>
  <span m=''1343230''>one,</span> <span m=''1343720''>since</span> <span m=''1344050''>this</span>
  <span m=''1344450''>small,</span> <span m=''1344755''>it</span> <span m=''1345060''>probably</span>
  <span m=''1345560''>tore</span> <span m=''1345800''>through</span> <span m=''1345890''>all</span>
  <span m=''1346120''>the</span> <span m=''1346360''>possible</span> <span m=''1346780''>cases</span>
  <span m=''1347150''>at the</span> <span m=''1347490''>[UNINTELLIGIBLE].</span> <span
  m=''1348870''>So</span> <span m=''1348990''>it''s</span> <span m=''1349210''>dealing</span>
  <span m=''1349510''>with</span> <span m=''1349660''>all</span> <span m=''1349850''>those,</span>
  <span m=''1350080''>and</span> <span m=''1350190''>checking</span> <span m=''1350600''>over</span>
  <span m=''1350730''>everything</span> <span m=''1351210''>and</span> <span m=''1351390''>trying</span>
  <span m=''1351590''>to</span> <span m=''1351790''>find</span> <span m=''1351970''>optimal</span>
  <span m=''1352470''>case</span> <span m=''1352720''>and</span> <span m=''1352840''>do</span>
  <span m=''1352960''>that</span> <span m=''1353150''>fast,</span> <span m=''1353690''>hoping</span>
  <span m=''1354290''>that</span> <span m=''1354480''>you</span> <span m=''1354610''>get</span>
  <span m=''1354760''>optimal</span> <span m=''1355085''>case</span> <span m=''1355410''>for
  it.</span> <span m=''1355890''>But</span> <span m=''1356150''>if</span> <span m=''1356270''>you</span>
  <span m=''1356340''>have</span> <span m=''1356440''>something</span> <span m=''1356780''>more</span>
  <span m=''1356940''>complicated,</span> <span m=''1357540''>the</span> <span m=''1357600''>compiler</span>
  <span m=''1358010''>won''t</span> <span m=''1358200''>be</span> <span m=''1358290''>able</span>
  <span m=''1358510''>to do</span> <span m=''1358630''>all</span> <span m=''1358690''>of</span>
  <span m=''1358760''>those</span> <span m=''1358960''>things,</span> <span m=''1359170''>so
  it</span> <span m=''1359330''>might</span> <span m=''1359540''>give</span> <span
  m=''1359670''>up.</span> <span m=''1360110''>So</span> <span m=''1360240''>the</span>
  <span m=''1360350''>interesting</span> <span m=''1360680''>thing</span> <span m=''1360860''>to</span>
  <span m=''1361010''>here</span> <span m=''1361150''>note</span> <span m=''1361430''>is</span>
  <span m=''1362430''>more</span> <span m=''1362700''>information</span> <span m=''1363200''>to</span>
  <span m=''1363260''>go</span> <span m=''1363360''>into</span> <span m=''1363470''>the</span>
  <span m=''1363580''>compiler</span> <span m=''1363930''>is</span> <span m=''1364130''>better.</span>
  <span m=''1364840''>And</span> <span m=''1365230''>then</span> <span m=''1365370''>here,</span>
  <span m=''1365490''>compiler</span> <span m=''1366720''>has</span> <span m=''1366840''>to</span>
  <span m=''1366930''>divide</span> <span m=''1367670''>a</span> <span m=''1367930''>lot</span>
  <span m=''1368280''>of</span> <span m=''1368380''>things,</span> <span m=''1368600''>but</span>
  <span m=''1369020''>probably</span> <span m=''1369200''>not</span> <span m=''1369655''>happen.</span>
  </p><p><span m=''1371020''>Another</span> <span m=''1371300''>interesting</span>
  <span m=''1371740''>thing</span> <span m=''1371970''>is</span> <span m=''1372130''>now,</span>
  <span m=''1373750''>the</span> <span m=''1373880''>first</span> <span m=''1374180''>time</span>
  <span m=''1374330''>I</span> <span m=''1374410''>just</span> <span m=''1374620''>copy</span>
  <span m=''1374970''>to</span> <span m=''1375050''>where</span> <span m=''1375320''>is</span>
  <span m=''1375440''>A</span> <span m=''1375610''>to</span> <span m=''1375670''>B,</span>
  <span m=''1376870''>in</span> <span m=''1377050''>memcpy4,</span> <span m=''1378070''>I</span>
  <span m=''1378200''>just</span> <span m=''1378480''>call</span> <span m=''1378880''>memcpy3</span>
  <span m=''1380620''>by</span> <span m=''1380740''>doing the</span> <span m=''1380960''>same</span>
  <span m=''1381250''>thing,</span> <span m=''1381440''>A</span> <span m=''1381640''>to</span>
  <span m=''1381770''>B,</span> <span m=''1382990''>copy</span> <span m=''1383360''>1024</span>
  <span m=''1383760''>[UNINTELLIGIBLE].</span> <span m=''1387080''>This</span> <span
  m=''1387320''>is</span> <span m=''1387650''>the</span> <span m=''1387760''>beauty</span>
  <span m=''1388210''>of</span> <span m=''1388290''>inlining.</span> <span m=''1389250''>So</span>
  <span m=''1389410''>what</span> <span m=''1389590''>it</span> <span m=''1389680''>did</span>
  <span m=''1390050''>was,</span> <span m=''1391470''>in</span> <span m=''1391900''>memcpy4,</span>
  <span m=''1393200''>it</span> <span m=''1393670''>inline</span> <span m=''1394260''>memcpy3</span>
  <span m=''1395870''>and</span> <span m=''1396100''>substitute</span> <span m=''1396790''>X</span>
  <span m=''1397310''>and</span> <span m=''1397510''>Y to</span> <span m=''1397780''>A</span>
  <span m=''1398050''>and B</span> <span m=''1398370''>and</span> <span m=''1398690''>end</span>
  <span m=''1398950''>2,024.</span> <span m=''1401310''>And</span> <span m=''1401460''>it</span>
  <span m=''1401670''>realized</span> <span m=''1402250''>that</span> <span m=''1402440''>it</span>
  <span m=''1402550''>doesn''t</span> <span m=''1402760''>have to</span> <span m=''1403000''>do
  all</span> <span m=''1403280''>these</span> <span m=''1403530''>tests</span> <span
  m=''1404090''>like</span> <span m=''1404290''>it</span> <span m=''1404360''>did.</span>
  </p><p><span m=''1405450''>What</span> <span m=''1405620''>it</span> <span m=''1405710''>generated</span>
  <span m=''1406230''>is</span> <span m=''1406350''>very</span> <span m=''1406610''>close</span>
  <span m=''1406920''>to</span> <span m=''1407250''>what</span> <span m=''1407570''>we</span>
  <span m=''1407680''>got</span> <span m=''1407900''>here</span> <span m=''1409785''>because</span>
  <span m=''1410390''>after</span> <span m=''1410690''>inlining,</span> <span m=''1410820''>it
  should</span> <span m=''1411040''>realize,</span> <span m=''1411170''>wait a minute,</span>
  <span m=''1411460''>I''m</span> <span m=''1411620''>copying</span> <span m=''1412270''>A</span>
  <span m=''1412410''>to</span> <span m=''1412480''>B.</span> <span m=''1412640''>I</span>
  <span m=''1412710''>know</span> <span m=''1412830''>we</span> <span m=''1412910''>have</span>
  <span m=''1413000''>the</span> <span m=''1413090''>start.</span> <span m=''1413390''>I</span>
  <span m=''1413460''>know</span> <span m=''1413630''>we have</span> <span m=''1413850''>the
  end.</span> <span m=''1413980''>I</span> <span m=''1414120''>know</span> <span m=''1414260''>the</span>
  <span m=''1414470''>size.</span> </p><p><span m=''1414570''>I know</span> <span
  m=''1414820''>all of</span> <span m=''1415040''>these</span> <span m=''1415290''>things,</span>
  <span m=''1415790''>and</span> <span m=''1416050''>I</span> <span m=''1416110''>don''t</span>
  <span m=''1416480''>have to do</span> <span m=''1416600''>any</span> <span m=''1416790''>of</span>
  <span m=''1416880''>these</span> <span m=''1417090''>things.</span> <span m=''1417360''>I</span>
  <span m=''1417720''>can</span> <span m=''1418060''>actually</span> <span m=''1418470''>generate</span>
  <span m=''1418980''>this</span> <span m=''1419430''>very</span> <span m=''1419720''>simple</span>
  <span m=''1420080''>piece</span> <span m=''1420290''>of</span> <span m=''1420390''>code.</span>
  <span m=''1422320''>So</span> <span m=''1422560''>I</span> <span m=''1422700''>think</span>
  <span m=''1422850''>that</span> <span m=''1423050''>is a neat</span> <span m=''1423220''>thing.</span>
  </p><p><span m=''1426080''>What</span> <span m=''1426350''>this</span> <span m=''1426500''>shows</span>
  <span m=''1426960''>you</span> <span m=''1427230''>is,</span> <span m=''1427490''>in</span>
  <span m=''1427690''>fact,</span> <span m=''1428380''>if</span> <span m=''1429070''>you</span>
  <span m=''1429320''>can</span> <span m=''1429560''>build</span> <span m=''1429770''>this</span>
  <span m=''1430770''>general</span> <span m=''1431380''>function</span> <span m=''1432140''>of</span>
  <span m=''1432430''>things</span> <span m=''1432720''>in</span> <span m=''1432860''>there,</span>
  <span m=''1433510''>and</span> <span m=''1433810''>then</span> <span m=''1433950''>you</span>
  <span m=''1434050''>can</span> <span m=''1434280''>call</span> <span m=''1434700''>them,</span>
  <span m=''1435390''>and</span> <span m=''1435860''>if</span> <span m=''1436090''>it</span>
  <span m=''1436210''>is</span> <span m=''1436400''>done</span> <span m=''1436730''>right,</span>
  <span m=''1437430''>the</span> <span m=''1437550''>inlining</span> <span m=''1438250''>will</span>
  <span m=''1438430''>basically</span> <span m=''1439030''>do all</span> <span m=''1439390''>optimizations.</span>
  <span m=''1439735''>So</span> <span m=''1440080''>you</span> <span m=''1440190''>don''t</span>
  <span m=''1440390''>have</span> <span m=''1440600''>to</span> <span m=''1440690''>have</span>
  <span m=''1441320''>50</span> <span m=''1441690''>different</span> <span m=''1442410''>memcpies</span>
  <span m=''1443150''>for</span> <span m=''1443390''>all the</span> <span m=''1443500''>different</span>
  <span m=''1444100''>things</span> <span m=''1444390''>in</span> <span m=''1444660''>your</span>
  <span m=''1444840''>code.</span> <span m=''1446100''>If</span> <span m=''1446190''>you</span>
  <span m=''1446650''>wrote</span> <span m=''1446960''>a</span> <span m=''1447020''>general</span>
  <span m=''1447320''>function,</span> <span m=''1448100''>and</span> <span m=''1448260''>you</span>
  <span m=''1448410''>call</span> <span m=''1448690''>it</span> <span m=''1448990''>in
  a way</span> <span m=''1449170''>it can</span> <span m=''1449380''>get</span> <span
  m=''1449530''>inline</span> <span m=''1450050''>and</span> <span m=''1450240''>got</span>
  <span m=''1450380''>that</span> <span m=''1451020''>as</span> <span m=''1451330''>efficient</span>
  <span m=''1451740''>as</span> <span m=''1452390''>possible</span> <span m=''1452900''>as</span>
  <span m=''1453450''>hand</span> <span m=''1453860''>optimization.</span> </p><p><span
  m=''1457665''>I</span> <span m=''1458050''>think</span> <span m=''1458260''>it''s</span>
  <span m=''1458360''>a real</span> <span m=''1458510''>interesting</span> <span m=''1459700''>thing,</span>
  <span m=''1459930''>and</span> <span m=''1460170''>what</span> <span m=''1460360''>does</span>
  <span m=''1460610''>for you,</span> <span m=''1462650''>when you''re</span> <span
  m=''1462940''>doing</span> <span m=''1463210''>projects,</span> <span m=''1463600''>you</span>
  <span m=''1463700''>don''t</span> <span m=''1463840''>have</span> <span m=''1464010''>to</span>
  <span m=''1464170''>do</span> <span m=''1464350''>all</span> <span m=''1464440''>of</span>
  <span m=''1464590''>these</span> <span m=''1465240''>very</span> <span m=''1465620''>complex</span>
  <span m=''1466050''>and</span> <span m=''1466510''>small</span> <span m=''1466730''>functions,</span>
  <span m=''1467620''>hand</span> <span m=''1467900''>inline</span> <span m=''1468350''>stuff</span>
  <span m=''1468630''>like</span> <span m=''1468860''>that.</span> <span m=''1469260''>But</span>
  <span m=''1470730''>it''s</span> <span m=''1470880''>always</span> <span m=''1471190''>good</span>
  <span m=''1471320''>to</span> <span m=''1471440''>check</span> <span m=''1471750''>that,</span>
  <span m=''1471900''>in</span> <span m=''1472010''>fact,</span> <span m=''1472160''>the</span>
  <span m=''1472240''>compiler''s</span> <span m=''1472740''>doing</span> <span m=''1472950''>that</span>
  <span m=''1473180''>because</span> <span m=''1473510''>you</span> <span m=''1473610''>don''t</span>
  <span m=''1473810''>know.</span> <span m=''1473940''>You</span> <span m=''1474170''>assume</span>
  <span m=''1474490''>the</span> <span m=''1474570''>compiler''s</span> <span m=''1474990''>doing</span>
  <span m=''1475200''>that,</span> <span m=''1475370''>and</span> <span m=''1475500''>there</span>
  <span m=''1475620''>might</span> <span m=''1475780''>be</span> <span m=''1475880''>cases</span>
  <span m=''1476290''>it might</span> <span m=''1476690''>not be.</span> <span m=''1476890''>And</span>
  <span m=''1477210''>I</span> <span m=''1477330''>will</span> <span m=''1477460''>show</span>
  <span m=''1477660''>you</span> <span m=''1478170''>one</span> <span m=''1478460''>example</span>
  <span m=''1478760''>here.</span> </p><p><span m=''1480640''>So</span> <span m=''1481040''>I</span>
  <span m=''1481170''>want you</span> <span m=''1481520''>guys</span> <span m=''1481660''>to</span>
  <span m=''1481740''>look</span> <span m=''1481890''>at</span> <span m=''1482030''>this</span>
  <span m=''1482240''>function</span> <span m=''1482550''>a little</span> <span m=''1482700''>bit.</span>
  <span m=''1483634''>OK?</span> <span m=''1484470''>I am</span> <span m=''1484780''>doing</span>
  <span m=''1485030''>two</span> <span m=''1485260''>memcpies.</span> <span m=''1486500''>I
  am</span> <span m=''1486750''>copying</span> <span m=''1487060''>1,024</span> <span
  m=''1487630''>elements.</span> </p><p><span m=''1488620''>One,</span> <span m=''1489100''>I''m</span>
  <span m=''1489400''>doing</span> <span m=''1489720''>ai+1,</span> <span m=''1491950''>a</span>
  <span m=''1492040''>into--</span> <span m=''1493150''>this</span> <span m=''1493300''>is</span>
  <span m=''1493440''>XY,</span> <span m=''1493870''>this is</span> <span m=''1494300''>X</span>
  <span m=''1495350''>get</span> <span m=''1495440''>copied</span> <span m=''1495770''>into</span>
  <span m=''1495860''>Y.</span> <span m=''1496610''>ai+1</span> <span m=''1497800''>to</span>
  <span m=''1498190''>A,</span> <span m=''1499060''>so</span> <span m=''1499210''>that</span>
  <span m=''1499480''>means</span> <span m=''1499840''>I</span> <span m=''1499900''>have</span>
  <span m=''1500100''>array</span> <span m=''1500370''>like</span> <span m=''1500600''>that,</span>
  <span m=''1506770''>array</span> <span m=''1507100''>like</span> <span m=''1507350''>this.</span>
  <span m=''1511090''>I am</span> <span m=''1511390''>giving</span> <span m=''1511820''>ai+1</span>
  <span m=''1513240''>as</span> <span m=''1513550''>the</span> <span m=''1513600''>source.</span>
  <span m=''1514090''>I am</span> <span m=''1514270''>giving this</span> <span m=''1514490''>as
  the</span> <span m=''1514710''>source,</span> <span m=''1516830''>and</span> <span
  m=''1516980''>I''m</span> <span m=''1517060''>doing</span> <span m=''1517350''>this</span>
  <span m=''1517600''>as</span> <span m=''1517720''>the</span> <span m=''1517830''>destination.</span>
  <span m=''1521570''>OK,</span> <span m=''1521770''>what</span> <span m=''1522050''>does</span>
  <span m=''1522230''>this</span> <span m=''1522430''>copy</span> <span m=''1522740''>do?</span>
  </p><p><span m=''1528830''>I''m</span> <span m=''1528970''>copying</span> <span
  m=''1529380''>1,024,</span> <span m=''1529970''>yes.</span> <span m=''1535960''>So</span>
  <span m=''1536140''>the</span> <span m=''1536210''>first</span> <span m=''1536530''>one,</span>
  <span m=''1537105''>this</span> <span m=''1537440''>one</span> <span m=''1537630''>gets</span>
  <span m=''1537770''>copied</span> <span m=''1538120''>to</span> <span m=''1538230''>here.</span>
  <span m=''1539870''>Second</span> <span m=''1540230''>iteration,</span> <span m=''1540620''>this</span>
  <span m=''1540790''>will</span> <span m=''1540950''>get</span> <span m=''1541210''>copied.</span>
  <span m=''1541390''>Third</span> <span m=''1541480''>iteration,</span> <span m=''1542160''>this
  will</span> <span m=''1542240''>get copied</span> <span m=''1542550''>to here.</span>
  <span m=''1543250''>What</span> <span m=''1543400''>does</span> <span m=''1543550''>it</span>
  <span m=''1543660''>do?</span> <span m=''1544672''>Yeah,</span> <span m=''1545080''>I</span>
  <span m=''1545180''>just</span> <span m=''1545420''>do</span> <span m=''1545620''>one</span>
  <span m=''1546170''>left-shift</span> <span m=''1547220''>of</span> <span m=''1547450''>the</span>
  <span m=''1547660''>array.</span> </p><p><span m=''1549600''>My</span> <span m=''1549710''>second</span>
  <span m=''1550080''>example.</span> <span m=''1556710''>I</span> <span m=''1556870''>give</span>
  <span m=''1557230''>this</span> <span m=''1557510''>as</span> <span m=''1557720''>my</span>
  <span m=''1557900''>first</span> <span m=''1558620''>element.</span> <span m=''1560720''>This</span>
  <span m=''1560975''>as</span> <span m=''1561230''>my</span> <span m=''1562210''>source.</span>
  <span m=''1562550''>This</span> <span m=''1562890''>as</span> <span m=''1563070''>my</span>
  <span m=''1563180''>destination.</span> <span m=''1565840''>What</span> <span m=''1566000''>happens</span>
  <span m=''1566350''>here?</span> </p><p><span m=''1567161''>AUDIENCE: All your</span>
  <span m=''1567642''>copies</span> <span m=''1568123''>have the</span> <span m=''1568604''>same
  number.</span> </p><p><span m=''1569570''>PROFESSOR: Exactly.</span> <span m=''1570470''>All</span>
  <span m=''1570830''>of</span> <span m=''1570990''>them</span> <span m=''1571160''>will</span>
  <span m=''1571410''>copy</span> <span m=''1571480''>the same</span> <span m=''1571940''>number.</span>
  <span m=''1574400''>OK,</span> <span m=''1575500''>so</span> <span m=''1575760''>now,</span>
  <span m=''1577870''>if</span> <span m=''1578030''>you</span> <span m=''1578160''>look</span>
  <span m=''1578340''>at</span> <span m=''1578510''>the</span> <span m=''1578650''>code</span>
  <span m=''1578970''>that''s</span> <span m=''1579180''>been</span> <span m=''1579390''>produced,</span>
  <span m=''1582690''>so</span> <span m=''1582860''>the</span> <span m=''1582960''>interesting</span>
  <span m=''1583380''>thing</span> <span m=''1583670''>here is</span> <span m=''1583930''>it</span>
  <span m=''1584400''>realizes,</span> <span m=''1584850''>in</span> <span m=''1585040''>this</span>
  <span m=''1585360''>one,</span> <span m=''1585980''>I</span> <span m=''1586110''>can</span>
  <span m=''1586350''>still</span> <span m=''1586710''>do</span> <span m=''1586820''>mmx</span>
  <span m=''1588610''>because</span> <span m=''1588880''>I</span> <span m=''1588940''>can</span>
  <span m=''1589120''>still</span> <span m=''1589420''>copy,</span> <span m=''1590230''>take</span>
  <span m=''1590440''>a</span> <span m=''1590550''>chunk,</span> <span m=''1591380''>and</span>
  <span m=''1591530''>copy</span> <span m=''1591790''>it</span> <span m=''1591940''>one</span>
  <span m=''1592080''>back,</span> <span m=''1592500''>take a</span> <span m=''1592760''>chunk</span>
  <span m=''1593210''>and copy it</span> <span m=''1593540''>one</span> <span m=''1593710''>back,</span>
  <span m=''1593900''>take a</span> <span m=''1594020''>chunk</span> <span m=''1594380''>and
  copy it</span> <span m=''1594780''>one back.</span> <span m=''1599590''>OK,</span>
  <span m=''1599660''>do you see</span> <span m=''1600020''>that?</span> </p><p><span
  m=''1602300''>But</span> <span m=''1603020''>what</span> <span m=''1603230''>does</span>
  <span m=''1603370''>the</span> <span m=''1603450''>next</span> <span m=''1603680''>one</span>
  <span m=''1603850''>do?</span> <span m=''1608460''>[UNINTELLIGIBLE]</span> <span
  m=''1609540''>mmx</span> <span m=''1610000''>is,</span> <span m=''1610260''>and</span>
  <span m=''1610580''>what</span> <span m=''1610880''>does</span> <span m=''1611030''>this</span>
  <span m=''1611210''>one</span> <span m=''1611440''>do?</span> <span m=''1617020''>Copying</span>
  <span m=''1617680''>something</span> <span m=''1618010''>from</span> <span m=''1618180''>dl--</span>
  </p><p><span m=''1638510''>[? movzdl ?]</span> <span m=''1639390''>array</span>
  <span m=''1640230''>expressed</span> <span m=''1640560''>dl.</span> <span m=''1645730''>Reverse</span>
  <span m=''1646330''>dl,</span> <span m=''1647420''>is this</span> <span m=''1647670''>copied,</span>
  <span m=''1648050''>this</span> <span m=''1648240''>one?</span> <span m=''1652640''>I
  hope</span> <span m=''1652940''>I</span> <span m=''1653040''>copied it</span> <span
  m=''1653340''>properly.</span> <span m=''1653640''>That</span> <span m=''1653800''>doesn''t</span>
  <span m=''1654380''>look</span> <span m=''1654640''>right</span> <span m=''1654905''>to
  me.</span> </p><p><span m=''1665040''>So</span> <span m=''1665190''>this</span>
  <span m=''1665390''>is</span> <span m=''1665510''>interesting.</span> <span m=''1665890''>So</span>
  <span m=''1666710''>I</span> <span m=''1666810''>might</span> <span m=''1667090''>have</span>
  <span m=''1667160''>missed</span> <span m=''1667360''>[UNINTELLIGIBLE].</span> <span
  m=''1668030''>I</span> <span m=''1668450''>think</span> <span m=''1669250''>it</span>
  <span m=''1669340''>takes--</span> <span m=''1673830''>This</span> <span m=''1674130''>doesn''t</span>
  <span m=''1674410''>look</span> <span m=''1674550''>right,</span> <span m=''1674720''>does</span>
  <span m=''1674820''>it?</span> </p><p><span m=''1675462''>AUDIENCE: So</span> <span
  m=''1675924''>what''s</span> <span m=''1676386''>a</span> <span m=''1676848''>bound?</span>
  <span m=''1677310''>It''s</span> <span m=''1677772''>char,</span> <span m=''1678234''>I</span>
  <span m=''1678696''>see.</span> <span m=''1679158''>One</span> <span m=''1679620''>byte.</span>
  </p><p><span m=''1680082''>PROFESSOR: Yeah,</span> <span m=''1680550''>one</span>
  <span m=''1680730''>byte.</span> </p><p><span m=''1681190''>AUDIENCE: So</span>
  <span m=''1681660''>what this</span> <span m=''1682130''>is doing</span> <span m=''1682600''>is
  just taking</span> <span m=''1683070''>the first byte,</span> <span m=''1683540''>and
  then</span> <span m=''1684010''>just</span> <span m=''1684480''>moving it.</span>
  </p><p><span m=''1684950''>PROFESSOR: Into edx?</span> </p><p><span m=''1686160''>AUDIENCE:
  [INAUDIBLE].</span> </p><p><span m=''1686930''>PROFESSOR: Oh,</span> <span m=''1687330''>right,</span>
  <span m=''1687500''>this</span> <span m=''1687660''>is actually</span> <span m=''1688080''>doing
  the</span> <span m=''1688210''>right</span> <span m=''1688450''>thing.</span> <span
  m=''1688850''>It''s</span> <span m=''1689020''>doing the</span> <span m=''1689250''>right</span>
  <span m=''1689320''>thing,</span> <span m=''1689540''>so</span> <span m=''1689630''>what</span>
  <span m=''1689780''>it does</span> <span m=''1690090''>is</span> <span m=''1690290''>this</span>
  <span m=''1690610''>move</span> <span m=''1690930''>this</span> <span m=''1691130''>one</span>
  <span m=''1692100''>into edx,</span> <span m=''1694700''>entire</span> <span m=''1695220''>thing,</span>
  <span m=''1695540''>and</span> <span m=''1695760''>then</span> <span m=''1695940''>this</span>
  <span m=''1696200''>calls</span> <span m=''1696330''>the</span> <span m=''1696450''>dl,</span>
  <span m=''1696720''>it</span> <span m=''1696800''>gets</span> <span m=''1697200''>the
  first</span> <span m=''1697490''>byte out of</span> <span m=''1697830''>edx.</span>
  <span m=''1699390''>Do</span> <span m=''1699740''>you</span> <span m=''1699870''>see</span>
  <span m=''1699990''>what''s</span> <span m=''1700170''>happening</span> <span m=''1700530''>here?</span>
  <span m=''1701460''>So</span> <span m=''1701750''>a</span> <span m=''1702020''>gets</span>
  <span m=''1702270''>into--</span> <span m=''1702580''>first</span> <span m=''1702970''>[UNINTELLIGIBLE]</span>
  <span m=''1703780''>the</span> <span m=''1703950''>first</span> <span m=''1704760''>byte</span>
  <span m=''1704940''>out in</span> <span m=''1705370''>here,</span> <span m=''1705940''>and</span>
  <span m=''1706110''>then</span> <span m=''1706240''>you</span> <span m=''1706360''>keep</span>
  <span m=''1706680''>copying</span> <span m=''1707040''>that</span> <span m=''1707260''>byte</span>
  <span m=''1707570''>one</span> <span m=''1707790''>at</span> <span m=''1707880''>a</span>
  <span m=''1707960''>time</span> <span m=''1708720''>into</span> <span m=''1711138''>this</span>
  <span m=''1711570''>location.</span> </p><p><span m=''1711900''>AUDIENCE: So</span>
  <span m=''1712400''>it''s not</span> <span m=''1712900''>smart enough to</span>
  <span m=''1713400''>[INAUDIBLE].</span> </p><p><span m=''1714900''>PROFESSOR: So</span>
  <span m=''1715030''>this</span> <span m=''1715250''>is</span> <span m=''1715460''>where</span>
  <span m=''1715715''>we</span> <span m=''1715970''>find</span> <span m=''1716390''>something</span>
  <span m=''1716740''>interesting</span> <span m=''1717160''>in</span> <span m=''1717230''>the</span>
  <span m=''1717320''>compiler.</span> </p><p><span m=''1719390''>AUDIENCE: [INAUDIBLE]?</span>
  </p><p><span m=''1722870''>PROFESSOR: So</span> <span m=''1723070''>what</span>
  <span m=''1723490''>doing</span> <span m=''1723800''>is,</span> <span m=''1724720''>in</span>
  <span m=''1724990''>here,</span> <span m=''1727200''>you</span> <span m=''1727390''>are</span>
  <span m=''1727550''>copying</span> <span m=''1729340''>this</span> <span m=''1734450''>byte</span>
  <span m=''1734830''>into</span> <span m=''1735270''>edx.</span> <span m=''1737130''>So</span>
  <span m=''1737300''>dl</span> <span m=''1738250''>is</span> <span m=''1738430''>the</span>
  <span m=''1738620''>first</span> <span m=''1738800''>bite</span> <span m=''1739080''>out</span>
  <span m=''1739220''>of</span> <span m=''1739330''>edl.</span> <span m=''1740120''>That''s</span>
  <span m=''1740520''>byte,</span> <span m=''1741000''>because</span> <span m=''1741260''>what--</span>
  </p><p><span m=''1741450''>AUDIENCE: The first</span> <span m=''1741855''>byte.</span>
  </p><p><span m=''1742260''>PROFESSOR: Yes,</span> <span m=''1742900''>because</span>
  <span m=''1744680''>except</span> <span m=''1745140''>the</span> <span m=''1745240''>six</span>
  <span m=''1745420''>address</span> <span m=''1745600''>themes,</span> <span m=''1746360''>do</span>
  <span m=''1746470''>you</span> <span m=''1747000''>do</span> <span m=''1747180''>r32e,</span>
  <span m=''1749820''>r64e,</span> <span m=''1750690''>32,</span> <span m=''1751240''>and</span>
  <span m=''1751770''>just</span> <span m=''1751970''>dl</span> <span m=''1752180''>is
  just</span> <span m=''1752610''>first</span> <span m=''1752800''>byte</span> <span
  m=''1753100''>[UNINTELLIGIBLE],</span> <span m=''1753850''>but</span> <span m=''1754020''>[UNINTELLIGIBLE]</span>
  <span m=''1754950''>low</span> <span m=''1755090''>byte</span> <span m=''1755340''>of</span>
  <span m=''1755440''>that.</span> <span m=''1756160''>d</span> <span m=''1756830''>is</span>
  <span m=''1756980''>just the</span> <span m=''1757700''>higher</span> <span m=''1757990''>byte.</span>
  </p><p><span m=''1758190''>AUDIENCE: So why</span> <span m=''1758480''>does it just</span>
  <span m=''1758953''>take the</span> <span m=''1759426''>first</span> <span m=''1759899''>byte?</span>
  </p><p><span m=''1761320''>PROFESSOR: Because</span> <span m=''1762940''>this</span>
  <span m=''1763210''>byte</span> <span m=''1763510''>get</span> <span m=''1763980''>copied</span>
  <span m=''1764260''>into</span> <span m=''1764470''>everything</span> <span m=''1764830''>here.</span>
  <span m=''1766660''>So</span> <span m=''1766790''>do</span> <span m=''1766880''>you</span>
  <span m=''1766960''>see</span> <span m=''1767070''>that?</span> <span m=''1768510''>This</span>
  <span m=''1768810''>byte</span> <span m=''1769480''>is</span> <span m=''1769620''>the</span>
  <span m=''1769700''>one</span> <span m=''1769840''>that--</span> <span m=''1770070''>because</span>
  <span m=''1770200''>that''s</span> <span m=''1770370''>what</span> <span m=''1770470''>happened</span>
  <span m=''1770790''>when</span> <span m=''1770900''>this</span> <span m=''1771100''>copy</span>
  <span m=''1771390''>is</span> <span m=''1771530''>basically</span> <span m=''1772360''>this</span>
  <span m=''1772610''>byte</span> <span m=''1772850''>got</span> <span m=''1773520''>everything</span>
  <span m=''1773990''>[UNINTELLIGIBLE]</span> <span m=''1774320''>got</span> <span
  m=''1774410''>replaced</span> <span m=''1774590''>by</span> <span m=''1774940''>this</span>
  <span m=''1775120''>first</span> <span m=''1775550''>byte</span> <span m=''1775760''>in
  here.</span> <span m=''1776195''>And you</span> <span m=''1776470''>incorporate</span>
  <span m=''1776850''>in</span> <span m=''1778040''>there,</span> <span m=''1778620''>and</span>
  <span m=''1779510''>then</span> <span m=''1780940''>it</span> <span m=''1781090''>just</span>
  <span m=''1781375''>goes</span> <span m=''1781660''>around</span> <span m=''1781880''>copying
  it</span> <span m=''1782330''>in here.</span> </p><p><span m=''1782900''>So</span>
  <span m=''1783040''>I try,</span> <span m=''1783330''>I</span> <span m=''1783590''>did</span>
  <span m=''1783780''>it</span> <span m=''1785110''>this</span> <span m=''1785380''>way,</span>
  <span m=''1785530''>so</span> <span m=''1785650''>what</span> <span m=''1785840''>I</span>
  <span m=''1786020''>did</span> <span m=''1786210''>was</span> <span m=''1786790''>basically</span>
  <span m=''1787420''>went from</span> <span m=''1787510''>1</span> <span m=''1787972''>to</span>
  <span m=''1788434''>1,025.</span> <span m=''1789630''>[UNINTELLIGIBLE]</span> <span
  m=''1790610''>0.</span> <span m=''1790890''>This</span> <span m=''1791070''>is</span>
  <span m=''1791190''>basically</span> <span m=''1791610''>what</span> <span m=''1791780''>happened.</span>
  <span m=''1792980''>So</span> <span m=''1793200''>one</span> <span m=''1793730''>2,025,</span>
  <span m=''1795700''>I</span> <span m=''1796290''>got</span> <span m=''1796450''>a</span>
  <span m=''1796620''>0,</span> <span m=''1797620''>and</span> <span m=''1797790''>then</span>
  <span m=''1797970''>basically</span> <span m=''1798410''>that''s</span> <span m=''1798680''>what</span>
  <span m=''1798820''>happens</span> <span m=''1799130''>in</span> <span m=''1799230''>here,</span>
  <span m=''1799330''>same</span> <span m=''1799580''>thing</span> <span m=''1799990''>here.</span>
  <span m=''1801950''>OK?</span> <span m=''1804930''>Do you</span> <span m=''1805070''>see</span>
  <span m=''1805450''>what''s</span> <span m=''1805690''>going</span> <span m=''1805920''>on?</span>
  </p><p><span m=''1807780''>But</span> <span m=''1808250''>I</span> <span m=''1808590''>just</span>
  <span m=''1808860''>did</span> <span m=''1808980''>something</span> <span m=''1809240''>else,</span>
  <span m=''1809500''>so</span> <span m=''1809630''>assume</span> <span m=''1810185''>[UNINTELLIGIBLE]</span>
  <span m=''1812410''>is</span> <span m=''1812670''>doing</span> <span m=''1812910''>right</span>
  <span m=''1813150''>here.</span> <span m=''1815700''>What</span> <span m=''1815890''>happens</span>
  <span m=''1816160''>if I</span> <span m=''1816240''>just</span> <span m=''1816460''>use</span>
  <span m=''1816580''>something</span> <span m=''1816940''>else?</span> <span m=''1817850''>I</span>
  <span m=''1817940''>use</span> <span m=''1818140''>B[0],</span> <span m=''1819960''>so</span>
  <span m=''1820530''>it</span> <span m=''1820850''>should</span> <span m=''1821040''>be</span>
  <span m=''1821150''>the</span> <span m=''1821250''>same,</span> <span m=''1821550''>isn''t
  it?</span> <span m=''1822310''>If</span> <span m=''1822490''>I</span> <span m=''1822560''>use</span>
  <span m=''1822740''>b[0]</span> <span m=''1823220''>here,</span> <span m=''1824690''>instead</span>
  <span m=''1825090''>of</span> <span m=''1825270''>doing</span> <span m=''1825510''>A[i],</span>
  <span m=''1826170''>this</span> <span m=''1826390''>should</span> <span m=''1826590''>be</span>
  <span m=''1826940''>B[i],</span> <span m=''1827210''>isn''t</span> <span m=''1827610''>it?</span>
  </p><p><span m=''1829935''>AUDIENCE: I''m sorry, where</span> <span m=''1830400''>is</span>
  <span m=''1830865''>[INAUDIBLE]?</span> </p><p><span m=''1831330''>PROFESSOR: Yeah.</span>
  <span m=''1832090''>It''s</span> <span m=''1832240''>a</span> <span m=''1832270''>different</span>
  <span m=''1832690''>array.</span> <span m=''1834120''>Sorry,</span> <span m=''1834490''>I
  didn''t</span> <span m=''1834800''>put it</span> <span m=''1834990''>here.</span>
  <span m=''1835190''>It''s a different</span> <span m=''1835250''>array.</span> <span
  m=''1835400''>So</span> <span m=''1835530''>instead</span> <span m=''1835650''>of</span>
  <span m=''1835880''>A[0]</span> <span m=''1836460''>here,</span> <span m=''1837950''>I</span>
  <span m=''1838230''>put</span> <span m=''1838550''>another</span> <span m=''1838900''>array,</span>
  <span m=''1839230''>B[0],</span> <span m=''1839630''>here.</span> </p><p><span m=''1843080''>Does</span>
  <span m=''1843250''>it</span> <span m=''1843400''>matter</span> <span m=''1843760''>whether
  that''s</span> <span m=''1843920''>A[0]</span> <span m=''1844270''>or</span> <span
  m=''1844530''>B[0]?</span> <span m=''1845140''>B[0]</span> <span m=''1845480''>is
  a</span> <span m=''1845610''>different</span> <span m=''1845700''>array.</span>
  <span m=''1848920''>It</span> <span m=''1849010''>shouldn''t</span> <span m=''1849300''>matter</span>
  <span m=''1849880''>because</span> <span m=''1850430''>a</span> <span m=''1850480''>different</span>
  <span m=''1850830''>array,</span> <span m=''1851490''>different</span> <span m=''1851830''>element</span>
  <span m=''1852160''>that</span> <span m=''1852280''>you</span> <span m=''1852380''>don''t</span>
  <span m=''1852620''>do</span> <span m=''1852710''>that,</span> <span m=''1853090''>but</span>
  <span m=''1853910''>the</span> <span m=''1853990''>interesting</span> <span m=''1854400''>thing</span>
  <span m=''1854580''>is</span> <span m=''1854700''>if</span> <span m=''1854810''>you</span>
  <span m=''1854950''>do</span> <span m=''1855190''>that,</span> <span m=''1855790''>it</span>
  <span m=''1855850''>managed</span> <span m=''1856170''>to</span> <span m=''1856280''>convert</span>
  <span m=''1856670''>it</span> <span m=''1856800''>into</span> <span m=''1857040''>mmx.</span>
  <span m=''1858100''>So</span> <span m=''1858270''>this</span> <span m=''1858510''>is</span>
  <span m=''1858780''>where</span> <span m=''1859410''>the compiler</span> <span m=''1860040''>is</span>
  <span m=''1860330''>basically</span> <span m=''1861120''>falling</span> <span m=''1861660''>short</span>
  <span m=''1861940''>a little</span> <span m=''1862286''>bit</span> <span m=''1862980''>because</span>
  <span m=''1863260''>it</span> <span m=''1863440''>could</span> <span m=''1863650''>have</span>
  <span m=''1863860''>done</span> <span m=''1864180''>this</span> <span m=''1864680''>for</span>
  <span m=''1864830''>these</span> <span m=''1865090''>two.</span> </p><p><span m=''1867404''>OK,</span>
  <span m=''1867870''>it''s</span> <span m=''1868060''>the</span> <span m=''1868120''>same</span>
  <span m=''1868370''>thing</span> <span m=''1868610''>because</span> <span m=''1869050''>what</span>
  <span m=''1869160''>it</span> <span m=''1869270''>does</span> <span m=''1869500''>is</span>
  <span m=''1869630''>it</span> <span m=''1869700''>takes</span> <span m=''1870020''>this</span>
  <span m=''1870130''>one</span> <span m=''1870370''>element</span> <span m=''1870610''>from</span>
  <span m=''1870790''>me</span> <span m=''1870970''>and</span> <span m=''1871140''>copy
  it</span> <span m=''1871490''>everywhere.</span> <span m=''1872190''>I could</span>
  <span m=''1872380''>have done</span> <span m=''1872600''>it,</span> <span m=''1874290''>but</span>
  <span m=''1874630''>for</span> <span m=''1874750''>some</span> <span m=''1874960''>reason,</span>
  <span m=''1875620''>the</span> <span m=''1875750''>compiler</span> <span m=''1876810''>decided</span>
  <span m=''1877220''>if</span> <span m=''1877680''>using</span> <span m=''1877930''>a</span>
  <span m=''1877980''>different</span> <span m=''1878280''>array,</span> <span m=''1878950''>B[0].</span>
  <span m=''1879200''>I</span> <span m=''1879270''>can</span> <span m=''1879450''>do</span>
  <span m=''1879590''>it,</span> <span m=''1879770''>but</span> <span m=''1880140''>I''m</span>
  <span m=''1880290''>doing</span> <span m=''1880520''>A[0]</span> <span m=''1880780''>[UNINTELLIGIBLE],</span>
  <span m=''1881730''>even</span> <span m=''1881960''>though</span> <span m=''1882220''>these</span>
  <span m=''1882600''>two</span> <span m=''1883690''>are</span> <span m=''1883850''>basically</span>
  <span m=''1884650''>identical</span> <span m=''1885220''>except</span> <span m=''1885510''>these
  are</span> <span m=''1885650''>different.</span> <span m=''1885970''>I''m</span>
  <span m=''1886390''>not</span> <span m=''1886560''>doing</span> <span m=''1886800''>any</span>
  <span m=''1887040''>kind</span> <span m=''1887270''>of</span> <span m=''1887330''>[UNINTELLIGIBLE],</span>
  <span m=''1887740''>anything.</span> <span m=''1888110''>Question?</span> </p><p><span
  m=''1889046''>AUDIENCE: [INAUDIBLE]?</span> </p><p><span m=''1892308''>PROFESSOR:
  Yes,</span> <span m=''1892780''>so</span> <span m=''1892940''>what</span> <span
  m=''1893380''>does</span> <span m=''1893700''>is</span> <span m=''1894370''>when</span>
  <span m=''1894500''>it</span> <span m=''1894630''>goes</span> <span m=''1894840''>somewhere,</span>
  <span m=''1895120''>it''s</span> <span m=''1895620''>doing</span> <span m=''1895750''>pac.</span>
  <span m=''1897050''>[UNINTELLIGIBLE]</span> <span m=''1897200''>pac</span> <span
  m=''1897540''>instructions</span> <span m=''1898260''>in</span> <span m=''1898360''>here.</span>
  <span m=''1898990''>What</span> <span m=''1899220''>it</span> <span m=''1899350''>does</span>
  <span m=''1899570''>is</span> <span m=''1899670''>it</span> <span m=''1900360''>takes</span>
  <span m=''1900940''>a</span> <span m=''1901240''>byte</span> <span m=''1901600''>and</span>
  <span m=''1901840''>kind</span> <span m=''1901950''>of</span> <span m=''1902300''>makes</span>
  <span m=''1902570''>multiple</span> <span m=''1902930''>copies</span> <span m=''1903270''>of</span>
  <span m=''1903350''>the</span> <span m=''1903430''>byte</span> <span m=''1903710''>and</span>
  <span m=''1903860''>create</span> <span m=''1904130''>a</span> <span m=''1904280''>larger</span>
  <span m=''1904560''>copy</span> <span m=''1904980''>than the</span> <span m=''1905100''>16</span>
  <span m=''1905460''>copies</span> <span m=''1905830''>in</span> <span m=''1905950''>there,</span>
  <span m=''1906330''>and</span> <span m=''1906500''>then</span> <span m=''1906610''>it</span>
  <span m=''1906700''>can</span> <span m=''1906930''>kind</span> <span m=''1907130''>of</span>
  <span m=''1907190''>stamp</span> <span m=''1907485''>it</span> <span m=''1908270''>everywhere.</span>
  </p><p><span m=''1908760''>AUDIENCE: [INAUDIBLE]</span> <span m=''1911700''>because</span>
  <span m=''1912190''>the</span> <span m=''1912680''>A[0] would</span> <span m=''1913170''>go
  off</span> <span m=''1913660''>of A[1].</span> </p><p><span m=''1914640''>PROFESSOR:
  So</span> <span m=''1914930''>what it''s</span> <span m=''1915290''>doing</span>
  <span m=''1915490''>is</span> <span m=''1915650''>copying</span> <span m=''1916000''>A[0]</span>
  <span m=''1916380''>multiple</span> <span m=''1916850''>times</span> <span m=''1917100''>one</span>
  <span m=''1917290''>at</span> <span m=''1917380''>a</span> <span m=''1917470''>times</span>
  <span m=''1917750''>slowly.</span> <span m=''1918980''>So</span> <span m=''1919140''>what</span>
  <span m=''1919330''>this</span> <span m=''1919480''>does</span> <span m=''1919710''>is</span>
  <span m=''1919810''>it</span> <span m=''1919990''>takes</span> <span m=''1920800''>B[0],</span>
  <span m=''1921480''>make</span> <span m=''1922850''>16</span> <span m=''1923250''>copies</span>
  <span m=''1923590''>in</span> <span m=''1923720''>there,</span> <span m=''1923850''>in</span>
  <span m=''1924100''>registers,</span> <span m=''1924610''>not in</span> <span m=''1924920''>memory.</span>
  <span m=''1925720''>I</span> <span m=''1925790''>created</span> <span m=''1926760''>a</span>
  <span m=''1926860''>template</span> <span m=''1927250''>of</span> <span m=''1927330''>16,</span>
  <span m=''1927720''>and</span> <span m=''1927840''>I</span> <span m=''1927960''>kind</span>
  <span m=''1928180''>of</span> <span m=''1928230''>stamp</span> <span m=''1928690''>it</span>
  <span m=''1929100''>as</span> <span m=''1929310''>I</span> <span m=''1929420''>go.</span>
  </p><p><span m=''1929660''>AUDIENCE: That''s probably</span> <span m=''1930074''>failure
  of</span> <span m=''1930488''>its alias</span> <span m=''1930902''>analysis.</span>
  </p><p><span m=''1931730''>PROFESSOR: Yeah,</span> <span m=''1932100''>it''s</span>
  <span m=''1932300''>failure</span> <span m=''1932610''>[UNINTELLIGIBLE].</span>
  <span m=''1932900''>So</span> <span m=''1933000''>this</span> <span m=''1933210''>is</span>
  <span m=''1933440''>where</span> <span m=''1933590''>the</span> <span m=''1933740''>compiler</span>
  <span m=''1934170''>does</span> <span m=''1934450''>some</span> <span m=''1934680''>magic,</span>
  <span m=''1935220''>kind</span> <span m=''1935370''>of</span> <span m=''1935430''>very</span>
  <span m=''1935720''>complex</span> <span m=''1936120''>things</span> <span m=''1936250''>in</span>
  <span m=''1936500''>here.</span> <span m=''1937060''>But</span> <span m=''1938830''>somewhere</span>
  <span m=''1939460''>in the</span> <span m=''1939610''>compiler</span> <span m=''1940000''>it
  failed.</span> <span m=''1940810''>so</span> <span m=''1941130''>what</span> <span
  m=''1941280''>you</span> <span m=''1941430''>want</span> <span m=''1941740''>in
  here</span> <span m=''1942025''>is</span> <span m=''1942310''>a</span> <span m=''1944370''>code</span>
  <span m=''1944580''>looking</span> <span m=''1944840''>like</span> <span m=''1945080''>this,</span>
  <span m=''1946110''>but</span> <span m=''1946660''>it</span> <span m=''1946840''>produces</span>
  <span m=''1947310''>this</span> <span m=''1947480''>one.</span> </p><p><span m=''1947570''>So</span>
  <span m=''1947680''>this</span> <span m=''1947860''>is</span> <span m=''1948050''>where</span>
  <span m=''1948720''>the</span> <span m=''1949170''>compilers</span> <span m=''1949630''>are</span>
  <span m=''1949800''>great.</span> <span m=''1950080''>It</span> <span m=''1950140''>do</span>
  <span m=''1950320''>some</span> <span m=''1950540''>amazing</span> <span m=''1951070''>things,</span>
  <span m=''1951670''>but</span> <span m=''1952710''>it''s</span> <span m=''1953170''>not</span>
  <span m=''1955280''>infallible.</span> <span m=''1956620''>It</span> <span m=''1956800''>can</span>
  <span m=''1956990''>do,</span> <span m=''1958150''>there</span> <span m=''1958290''>might</span>
  <span m=''1958420''>be</span> <span m=''1958510''>corner cases</span> <span m=''1958800''>that</span>
  <span m=''1959070''>data</span> <span m=''1959270''>analysis</span> <span m=''1959500''>fails.</span>
  <span m=''1961120''>So</span> <span m=''1961520''>that''s</span> <span m=''1961880''>why</span>
  <span m=''1962100''>it''s</span> <span m=''1962180''>always</span> <span m=''1962590''>good,</span>
  <span m=''1962850''>even</span> <span m=''1963210''>though</span> <span m=''1963780''>you</span>
  <span m=''1963940''>can</span> <span m=''1964120''>take</span> <span m=''1964390''>advantage</span>
  <span m=''1964900''>of</span> <span m=''1964960''>the</span> <span m=''1965050''>compiler,</span>
  <span m=''1965430''>to</span> <span m=''1965530''>look</span> <span m=''1965710''>at</span>
  <span m=''1965840''>what''s</span> <span m=''1966110''>generating.</span> </p><p><span
  m=''1967010''>And</span> <span m=''1967210''>sometimes</span> <span m=''1967660''>when</span>
  <span m=''1967820''>you</span> <span m=''1967960''>tweak</span> <span m=''1968260''>around</span>
  <span m=''1968590''>it,</span> <span m=''1968920''>you suddenly</span> <span m=''1969350''>realize,</span>
  <span m=''1969640''>wait a</span> <span m=''1969690''>minute.</span> <span m=''1970140''>I</span>
  <span m=''1970280''>can</span> <span m=''1970480''>get</span> <span m=''1970560''>the</span>
  <span m=''1970650''>compiler</span> <span m=''1971100''>do</span> <span m=''1971230''>something</span>
  <span m=''1971490''>better,</span> <span m=''1972550''>and</span> <span m=''1972790''>then</span>
  <span m=''1973010''>you</span> <span m=''1973090''>can</span> <span m=''1973220''>say</span>
  <span m=''1973310''>wait</span> <span m=''1973500''>a</span> <span m=''1973520''>minute,</span>
  <span m=''1973760''>now</span> <span m=''1973840''>how do I</span> <span m=''1974650''>work</span>
  <span m=''1974880''>myself</span> <span m=''1975250''>back?</span> <span m=''1975740''>Sometimes,</span>
  <span m=''1977020''>you</span> <span m=''1977170''>end</span> <span m=''1977330''>up</span>
  <span m=''1977500''>changing</span> <span m=''1979250''>your</span> <span m=''1979470''>SQL</span>
  <span m=''1979680''>a</span> <span m=''1979720''>little</span> <span m=''1979920''>bit</span>
  <span m=''1980090''>like</span> <span m=''1980450''>the</span> <span m=''1980520''>examples,</span>
  <span m=''1981920''>the</span> <span m=''1982010''>TAs</span> <span m=''1982150''>showed</span>
  <span m=''1982290''>when</span> <span m=''1982720''>they were</span> <span m=''1982950''>doing</span>
  <span m=''1983050''>their</span> <span m=''1986130''>demo,</span> <span m=''1987670''>that</span>
  <span m=''1988300''>if</span> <span m=''1988470''>you</span> <span m=''1988580''>tweak</span>
  <span m=''1988750''>it</span> <span m=''1989170''>a little,</span> <span m=''1989580''>you
  can</span> <span m=''1989940''>actually</span> <span m=''1990080''>get the</span>
  <span m=''1990200''>compiler</span> <span m=''1990520''>to</span> <span m=''1990590''>do</span>
  <span m=''1990740''>that,</span> <span m=''1990900''>instead</span> <span m=''1991000''>of</span>
  <span m=''1991260''>trying</span> <span m=''1991480''>to</span> <span m=''1991560''>do</span>
  <span m=''1991740''>these</span> <span m=''1991950''>things</span> <span m=''1992130''>by</span>
  <span m=''1992240''>hand.</span> <span m=''1995050''>So</span> <span m=''1995190''>the</span>
  <span m=''1995290''>compilers</span> <span m=''1995670''>are</span> <span m=''1995790''>powerful,</span>
  <span m=''1996170''>but you</span> <span m=''1996500''>have to be</span> <span m=''1996600''>careful.</span>
  </p><p><span m=''2000070''>Another</span> <span m=''2000310''>interesting</span>
  <span m=''2000710''>thing</span> <span m=''2000910''>is</span> <span m=''2001610''>this</span>
  <span m=''2001980''>factorial</span> <span m=''2002150''>here.</span> <span m=''2003460''>So</span>
  <span m=''2003610''>normal</span> <span m=''2003830''>factorial</span> <span m=''2004570''>is</span>
  <span m=''2004710''>basically</span> <span m=''2005260''>you</span> <span m=''2005540''>call</span>
  <span m=''2005710''>a</span> <span m=''2005790''>function</span> <span m=''2006080''>call</span>
  <span m=''2006210''>with</span> <span m=''2006475''>x-1</span> <span m=''2007410''>and</span>
  <span m=''2007540''>multiply</span> <span m=''2007960''>by</span> <span m=''2008220''>x.</span>
  <span m=''2008890''>But</span> <span m=''2010196''>you</span> <span m=''2010532''>know</span>
  <span m=''2010870''>functions</span> <span m=''2011260''>calls</span> <span m=''2011490''>are</span>
  <span m=''2011590''>very</span> <span m=''2011730''>expensive,</span> <span m=''2013060''>and</span>
  <span m=''2013920''>in</span> <span m=''2014060''>fact,</span> <span m=''2015366''>GCC</span>
  <span m=''2015820''>knows</span> <span m=''2016050''>that,</span> <span m=''2016240''>too.</span>
  <span m=''2016750''>So</span> <span m=''2016880''>what</span> <span m=''2017010''>GCC</span>
  <span m=''2017580''>did,</span> <span m=''2018200''>it</span> <span m=''2018430''>basically</span>
  <span m=''2019030''>eliminated</span> <span m=''2019560''>the</span> <span m=''2019640''>function</span>
  <span m=''2020060''>call</span> <span m=''2020580''>and</span> <span m=''2020820''>converted</span>
  <span m=''2021330''>it</span> <span m=''2021625''>into</span> <span m=''2021920''>its</span>
  <span m=''2022000''>[UNINTELLIGIBLE]</span> <span m=''2022660''>function</span>
  <span m=''2023080''>here.</span> </p><p><span m=''2023620''>So</span> <span m=''2023960''>if</span>
  <span m=''2024350''>EDA</span> <span m=''2024790''>got</span> <span m=''2025110''>x
  in</span> <span m=''2025480''>here,</span> <span m=''2026280''>and</span> <span
  m=''2027010''>then</span> <span m=''2027130''>it</span> <span m=''2027680''>goes
  to a</span> <span m=''2028140''>loop,</span> <span m=''2028410''>so</span> <span
  m=''2028530''>it</span> <span m=''2028660''>first</span> <span m=''2029050''>check</span>
  <span m=''2029250''>with</span> <span m=''2029370''>[UNINTELLIGIBLE].</span> <span
  m=''2030250''>If it is</span> <span m=''2030470''>one,</span> <span m=''2030670''>you</span>
  <span m=''2030770''>go</span> <span m=''2030910''>to</span> <span m=''2031050''>the
  end</span> <span m=''2031310''>and return</span> <span m=''2031605''>it.</span>
  <span m=''2031900''>You are</span> <span m=''2032250''>done</span> <span m=''2033190''>if</span>
  <span m=''2034180''>x</span> <span m=''2034380''>is</span> <span m=''2034520''>1</span>
  <span m=''2034815''>or</span> <span m=''2035110''>less</span> <span m=''2035260''>than</span>
  <span m=''2035460''>1.</span> </p><p><span m=''2036150''>And</span> <span m=''2036800''>otherwise,</span>
  <span m=''2037350''>it</span> <span m=''2037510''>goes through</span> <span m=''2037650''>a
  loop.</span> <span m=''2037890''>It</span> <span m=''2038100''>doesn''t</span> <span
  m=''2038470''>go do</span> <span m=''2038660''>any</span> <span m=''2038800''>function</span>
  <span m=''2039190''>call.</span> <span m=''2039330''>It</span> <span m=''2039460''>just</span>
  <span m=''2039950''>basically</span> <span m=''2040110''>calculate</span> <span
  m=''2040600''>this</span> <span m=''2040780''>fact</span> <span m=''2041040''>value</span>
  <span m=''2041290''>inside</span> <span m=''2043000''>EAX</span> <span m=''2044050''>and</span>
  <span m=''2044260''>keep</span> <span m=''2044500''>multiplying</span> <span m=''2045050''>[UNINTELLIGIBLE].</span>
  <span m=''2047100''>So</span> <span m=''2047260''>it</span> <span m=''2048150''>can</span>
  <span m=''2048620''>take</span> <span m=''2048920''>this</span> <span m=''2050480''>simple</span>
  <span m=''2050929''>recursive</span> <span m=''2051800''>functions,</span> <span
  m=''2052469''>and</span> <span m=''2052820''>also</span> <span m=''2053219''>convert</span>
  <span m=''2053520''>it</span> <span m=''2053650''>into</span> <span m=''2053780''>[UNINTELLIGIBLE].</span>
  </p><p><span m=''2055030''>So</span> <span m=''2055219''>it</span> <span m=''2055340''>does</span>
  <span m=''2055560''>some</span> <span m=''2055880''>very,</span> <span m=''2056170''>very</span>
  <span m=''2056550''>fancy</span> <span m=''2057030''>stuff</span> <span m=''2057300''>in</span>
  <span m=''2057400''>the</span> <span m=''2057480''>compiler.</span> <span m=''2058080''>So</span>
  <span m=''2058380''>the</span> <span m=''2058500''>compilers</span> <span m=''2058969''>are</span>
  <span m=''2059110''>fun</span> <span m=''2059510''>when</span> <span m=''2059739''>they</span>
  <span m=''2059870''>work.</span> <span m=''2060320''>But</span> <span m=''2060610''>the</span>
  <span m=''2060690''>key</span> <span m=''2060870''>thing</span> <span m=''2061120''>is</span>
  <span m=''2061480''>there</span> <span m=''2061630''>are</span> <span m=''2061659''>many</span>
  <span m=''2061889''>cases</span> <span m=''2062100''>it</span> <span m=''2062290''>doesn''t</span>
  <span m=''2062550''>work.</span> </p><p><span m=''2064469''>So</span> <span m=''2064690''>next,</span>
  <span m=''2065420''>I</span> <span m=''2065540''>want</span> <span m=''2065699''>to</span>
  <span m=''2065790''>switch</span> <span m=''2065940''>gears.</span> <span m=''2066179''>Any</span>
  <span m=''2066350''>questions</span> <span m=''2066760''>so</span> <span m=''2067104''>far?</span>
  <span m=''2068920''>Sometimes</span> <span m=''2069330''>it''s</span> <span m=''2069360''>fun</span>
  <span m=''2069780''>to</span> <span m=''2069850''>find</span> <span m=''2070949''>breaking</span>
  <span m=''2071380''>points</span> <span m=''2071600''>in the</span> <span m=''2071750''>compiler.</span>
  </p><p><span m=''2072089''>AUDIENCE: [INAUDIBLE]?</span> </p><p><span m=''2079234''>PROFESSOR:
  If</span> <span m=''2079540''>I</span> <span m=''2079870''>use,</span> <span m=''2080770''>in</span>
  <span m=''2080960''>some--</span> <span m=''2081389''>this</span> <span m=''2081760''>is</span>
  <span m=''2081949''>not</span> <span m=''2082230''>static?</span> </p><p><span m=''2082659''>AUDIENCE:
  Yeah.</span> </p><p><span m=''2084250''>PROFESSOR: No,</span> <span m=''2084500''>it</span>
  <span m=''2084679''>won''t</span> <span m=''2084850''>make</span> <span m=''2084989''>a</span>
  <span m=''2085040''>difference</span> <span m=''2085370''>because</span> <span m=''2085600''>what</span>
  <span m=''2085770''>it</span> <span m=''2085920''>says</span> <span m=''2086120''>is</span>
  <span m=''2086340''>if</span> <span m=''2086469''>it</span> <span m=''2086580''>is</span>
  <span m=''2086699''>not</span> <span m=''2086850''>static,</span> <span m=''2087340''>it''s</span>
  <span m=''2087710''>visible</span> <span m=''2087820''>to</span> <span m=''2087960''>the</span>
  <span m=''2088100''>outside</span> <span m=''2088440''>world,</span> <span m=''2089310''>but</span>
  <span m=''2090230''>within</span> <span m=''2090520''>this</span> <span m=''2090730''>function,</span>
  <span m=''2091409''>it''s the</span> <span m=''2091550''>same.</span> <span m=''2092360''>So</span>
  <span m=''2092540''>what</span> <span m=''2092710''>it</span> <span m=''2092820''>does,</span>
  <span m=''2093010''>it</span> <span m=''2093190''>kind</span> <span m=''2093409''>of</span>
  <span m=''2095270''>like</span> <span m=''2095500''>limiting</span> <span m=''2095880''>my</span>
  <span m=''2095989''>pollution</span> <span m=''2097200''>because</span> <span m=''2097630''>otherwise</span>
  <span m=''2098020''>what</span> <span m=''2098170''>happens</span> <span m=''2098450''>is</span>
  <span m=''2098610''>everybody</span> <span m=''2099000''>outside</span> <span m=''2099430''>will</span>
  <span m=''2099550''>see</span> <span m=''2099800''>these</span> <span m=''2100030''>names.</span>
  <span m=''2102130''>So</span> <span m=''2102220''>if</span> <span m=''2102350''>you</span>
  <span m=''2102480''>use</span> <span m=''2102710''>that</span> <span m=''2102880''>name</span>
  <span m=''2103090''>again</span> <span m=''2103380''>somewhere,</span> <span m=''2103800''>it</span>
  <span m=''2103950''>might</span> <span m=''2104150''>just</span> <span m=''2104320''>use</span>
  <span m=''2104530''>this</span> <span m=''2104730''>one.</span> </p><p><span m=''2105415''>[UNINTELLIGIBLE
  PHRASE]</span> <span m=''2106850''>this</span> <span m=''2106960''>is</span> <span
  m=''2107090''>within</span> <span m=''2107270''>the</span> <span m=''2107370''>file,</span>
  <span m=''2107950''>nobody else</span> <span m=''2108390''>should</span> <span m=''2108580''>see</span>
  <span m=''2108840''>this.</span> <span m=''2109630''>It''s</span> <span m=''2110210''>creating</span>
  <span m=''2110490''>a</span> <span m=''2110720''>local</span> <span m=''2111040''>copy.</span>
  <span m=''2111700''>It''s</span> <span m=''2111910''>kind</span> <span m=''2112150''>of</span>
  <span m=''2112230''>a</span> <span m=''2112820''>poor</span> <span m=''2112970''>man''s</span>
  <span m=''2113310''>class</span> <span m=''2114160''>heierarchy.</span> </p><p><span
  m=''2115950''>In</span> <span m=''2116120''>Java,</span> <span m=''2117050''>basically,</span>
  <span m=''2118390''>each</span> <span m=''2118690''>file</span> <span m=''2119140''>is
  a single</span> <span m=''2119550''>class,</span> <span m=''2120890''>and</span>
  <span m=''2121070''>you</span> <span m=''2121170''>make</span> <span m=''2121390''>sure</span>
  <span m=''2121550''>that</span> <span m=''2121760''>things</span> <span m=''2122400''>inside</span>
  <span m=''2122730''>the</span> <span m=''2123900''>class</span> <span m=''2124340''>is</span>
  <span m=''2124420''>not</span> <span m=''2124490''>visible</span> <span m=''2124790''>to</span>
  <span m=''2125110''>outside.</span> <span m=''2126080''>When</span> <span m=''2126190''>you</span>
  <span m=''2126290''>make</span> <span m=''2126940''>static,</span> <span m=''2127630''>you</span>
  <span m=''2127760''>made</span> <span m=''2128030''>it</span> <span m=''2128800''>only</span>
  <span m=''2128930''>visible</span> <span m=''2129310''>within</span> <span m=''2129510''>that</span>
  <span m=''2129660''>file,</span> <span m=''2129970''>so</span> <span m=''2130170''>you</span>
  <span m=''2130330''>kind</span> <span m=''2130500''>of</span> <span m=''2130660''>make</span>
  <span m=''2130870''>[UNINTELLIGIBLE].</span> <span m=''2131380''>You</span> <span
  m=''2131480''>can</span> <span m=''2131630''>think</span> <span m=''2131830''>about</span>
  <span m=''2132030''>your</span> <span m=''2132140''>file as</span> <span m=''2132450''>your</span>
  <span m=''2132760''>class,</span> <span m=''2134030''>and</span> <span m=''2134260''>so</span>
  <span m=''2134890''>you</span> <span m=''2135310''>limit</span> <span m=''2135620''>the</span>
  <span m=''2135700''>scope</span> <span m=''2136030''>of</span> <span m=''2136190''>the</span>
  <span m=''2136380''>variable</span> <span m=''2136780''>doing</span> <span m=''2137080''>that.</span>
  <span m=''2138710''>So</span> <span m=''2139270''>some</span> <span m=''2139750''>benefits</span>
  <span m=''2140230''>of</span> <span m=''2140370''>object-orientedness</span> <span
  m=''2141370''>can</span> <span m=''2141763''>be</span> <span m=''2142156''>[UNINTELLIGIBLE],</span>
  <span m=''2142550''>I</span> <span m=''2142670''>guess.</span> <span m=''2144570''>[UNINTELLIGIBLE]</span>
  <span m=''2144680''>static</span> <span m=''2145000''>variable,</span> <span m=''2145410''>it''s</span>
  <span m=''2145640''>not</span> <span m=''2145880''>a</span> <span m=''2146570''>class</span>
  <span m=''2147040''>variable.</span> </p><p><span m=''2152260''>OK,</span> <span
  m=''2152650''>so</span> <span m=''2152790''>next,</span> <span m=''2153880''>before</span>
  <span m=''2154250''>I</span> <span m=''2154360''>get</span> <span m=''2154540''>into</span>
  <span m=''2155380''>doing</span> <span m=''2155650''>compilers</span> <span m=''2156370''>and</span>
  <span m=''2156530''>say</span> <span m=''2156640''>what</span> <span m=''2156910''>compilers</span>
  <span m=''2157410''>do,</span> <span m=''2157780''>I</span> <span m=''2157990''>want</span>
  <span m=''2158230''>to</span> <span m=''2158270''>give</span> <span m=''2158510''>you
  a</span> <span m=''2158820''>[UNINTELLIGIBLE].</span> <span m=''2159580''>There</span>
  <span m=''2159820''>are</span> <span m=''2159890''>many</span> <span m=''2160290''>different</span>
  <span m=''2160830''>places</span> <span m=''2161350''>where</span> <span m=''2161500''>you</span>
  <span m=''2161660''>can</span> <span m=''2161810''>do</span> <span m=''2161970''>optimization.</span>
  <span m=''2162955''>So if</span> <span m=''2163280''>you</span> <span m=''2163460''>look</span>
  <span m=''2163730''>at</span> <span m=''2164650''>what</span> <span m=''2164860''>happens</span>
  <span m=''2165130''>in</span> <span m=''2165180''>the</span> <span m=''2165270''>program,</span>
  <span m=''2165670''>program</span> <span m=''2166050''>first</span> <span m=''2166270''>goes
  through</span> <span m=''2166600''>compile</span> <span m=''2167000''>time,</span>
  <span m=''2167490''>compiles</span> <span m=''2167850''>each</span> <span m=''2168120''>file,</span>
  <span m=''2169070''>then</span> <span m=''2169260''>it</span> <span m=''2169390''>links</span>
  <span m=''2169680''>all</span> <span m=''2169910''>the</span> <span m=''2170020''>files</span>
  <span m=''2170350''>together.</span> <span m=''2171200''>At</span> <span m=''2171560''>some</span>
  <span m=''2171820''>point,</span> <span m=''2172050''>the</span> <span m=''2172420''>files</span>
  <span m=''2172950''>will</span> <span m=''2173120''>get</span> <span m=''2173360''>loaded</span>
  <span m=''2173510''>into</span> <span m=''2173660''>your</span> <span m=''2173810''>machine,</span>
  <span m=''2174790''>and</span> <span m=''2174980''>then</span> <span m=''2175120''>it''ll</span>
  <span m=''2175300''>be</span> <span m=''2175410''>running.</span> <span m=''2176930''>So</span>
  <span m=''2177530''>if</span> <span m=''2177740''>you</span> <span m=''2178130''>load
  things</span> <span m=''2178260''>in a</span> <span m=''2178490''>compiler,</span>
  <span m=''2179590''>you</span> <span m=''2179750''>have</span> <span m=''2179900''>full</span>
  <span m=''2180160''>access</span> <span m=''2180480''>to</span> <span m=''2180560''>source</span>
  <span m=''2180910''>code,</span> <span m=''2182040''>it''s</span> <span m=''2182330''>very</span>
  <span m=''2182570''>easy</span> <span m=''2182870''>to</span> <span m=''2183000''>kind</span>
  <span m=''2183360''>of</span> <span m=''2185140''>look</span> <span m=''2185300''>at</span>
  <span m=''2185390''>the</span> <span m=''2185440''>high-level</span> <span m=''2186710''>transformation,</span>
  <span m=''2187430''>low-level</span> <span m=''2187690''>transformation,</span>
  <span m=''2188240''>you</span> <span m=''2188380''>can</span> <span m=''2188540''>look</span>
  <span m=''2188680''>at</span> <span m=''2188800''>the</span> <span m=''2188870''>entire</span>
  <span m=''2189190''>gamut</span> <span m=''2189550''>of</span> <span m=''2189670''>things</span>
  <span m=''2189900''>to</span> <span m=''2189980''>do.</span> </p><p><span m=''2192400''>And</span>
  <span m=''2192770''>the</span> <span m=''2192930''>nice</span> <span m=''2193060''>thing</span>
  <span m=''2193190''>about</span> <span m=''2193330''>compilers,</span> <span m=''2193940''>compilers</span>
  <span m=''2194250''>can</span> <span m=''2194550''>be</span> <span m=''2194680''>slow.</span>
  <span m=''2195370''>Nobody''s</span> <span m=''2195750''>going</span> <span m=''2195840''>to</span>
  <span m=''2195930''>complain.</span> <span m=''2196480''>It''s</span> <span m=''2196620''>not</span>
  <span m=''2196700''>going</span> <span m=''2196900''>to be</span> <span m=''2197040''>part
  of</span> <span m=''2197420''>your</span> <span m=''2197600''>run-time,</span> <span
  m=''2198950''>so</span> <span m=''2199090''>you</span> <span m=''2199260''>just</span>
  <span m=''2199470''>would</span> <span m=''2199620''>wait,</span> <span m=''2200070''>but</span>
  <span m=''2200360''>it''s</span> <span m=''2200650''>you,</span> <span m=''2200830''>not</span>
  <span m=''2201210''>the</span> <span m=''2201530''>customer.</span> </p><p><span
  m=''2202940''>But</span> <span m=''2203240''>the</span> <span m=''2203310''>problem</span>
  <span m=''2203710''>with</span> <span m=''2203850''>compilers,</span> <span m=''2204390''>it</span>
  <span m=''2204540''>doesn''t</span> <span m=''2204770''>see</span> <span m=''2204940''>the
  whole</span> <span m=''2205160''>programs.</span> <span m=''2205660''>You see a</span>
  <span m=''2205790''>file</span> <span m=''2206080''>at</span> <span m=''2206220''>a</span>
  <span m=''2206300''>time,</span> <span m=''2206680''>so</span> <span m=''2207240''>all</span>
  <span m=''2207340''>this</span> <span m=''2207470''>inline</span> <span m=''2207920''>things</span>
  <span m=''2208190''>and</span> <span m=''2208270''>stuff</span> <span m=''2208490''>has</span>
  <span m=''2208710''>to</span> <span m=''2208810''>be in</span> <span m=''2208980''>the</span>
  <span m=''2209070''>file.</span> <span m=''2209340''>You</span> <span m=''2209410''>can''t</span>
  <span m=''2209580''>put</span> <span m=''2209780''>in</span> <span m=''2209840''>a</span>
  <span m=''2209900''>different</span> <span m=''2210270''>file</span> <span m=''2210590''>and</span>
  <span m=''2210730''>get</span> <span m=''2210990''>[UNINTELLIGIBLE].</span> </p><p><span
  m=''2214760''>And</span> <span m=''2215090''>also</span> <span m=''2215400''>don''t</span>
  <span m=''2215630''>know the</span> <span m=''2215850''>run-time</span> <span m=''2216200''>conditions</span>
  <span m=''2216730''>because</span> <span m=''2216940''>that''s</span> <span m=''2217140''>run-time.</span>
  <span m=''2217760''>It might</span> <span m=''2219680''>be</span> <span m=''2220710''>having</span>
  <span m=''2221030''>different</span> <span m=''2221340''>inputs,</span> <span m=''2221750''>different</span>
  <span m=''2222470''>size</span> <span m=''2222780''>of</span> <span m=''2224010''>load</span>
  <span m=''2224390''>and</span> <span m=''2224550''>stuff,</span> <span m=''2224810''>that
  I</span> <span m=''2224910''>don''t</span> <span m=''2225060''>know</span> <span
  m=''2225100''>any</span> <span m=''2225300''>of</span> <span m=''2225420''>those</span>
  <span m=''2225640''>things.</span> <span m=''2226100''>And</span> <span m=''2226320''>also,</span>
  <span m=''2226570''>I</span> <span m=''2226660''>don''t</span> <span m=''2226820''>know</span>
  <span m=''2226900''>about the</span> <span m=''2227120''>architecture,</span> <span
  m=''2227840''>so</span> <span m=''2228010''>if</span> <span m=''2228150''>my</span>
  <span m=''2228200''>compiler</span> <span m=''2228700''>have</span> <span m=''2228870''>to</span>
  <span m=''2228950''>make</span> <span m=''2229180''>sure</span> <span m=''2229310''>that
  it</span> <span m=''2229590''>works</span> <span m=''2229980''>on</span> <span m=''2231710''>AMD</span>
  <span m=''2232090''>machines,</span> <span m=''2232750''>Intel</span> <span m=''2233080''>machines,</span>
  <span m=''2233500''>stuff</span> <span m=''2233760''>like</span> <span m=''2233970''>that,</span>
  <span m=''2234100''>of</span> <span m=''2234330''>course,</span> <span m=''2234470''>you</span>
  <span m=''2234530''>can</span> <span m=''2234690''>use</span> <span m=''2234850''>special</span>
  <span m=''2235160''>flags</span> <span m=''2235950''>and</span> <span m=''2236210''>try</span>
  <span m=''2236350''>to</span> <span m=''2236440''>comply</span> <span m=''2236760''>for</span>
  <span m=''2236870''>one</span> <span m=''2237120''>machine,</span> <span m=''2237780''>and</span>
  <span m=''2238010''>breaks,</span> <span m=''2238740''>you</span> <span m=''2238980''>finish</span>
  <span m=''2239180''>on</span> <span m=''2239480''>the other</span> <span m=''2239620''>one.</span>
  <span m=''2239760''>But</span> <span m=''2239910''>you</span> <span m=''2240010''>don''t
  want</span> <span m=''2240350''>to do</span> <span m=''2240440''>that,</span> <span
  m=''2240590''>so</span> <span m=''2240750''>the</span> <span m=''2240850''>compiler</span>
  <span m=''2241210''>has</span> <span m=''2241320''>to</span> <span m=''2241390''>be</span>
  <span m=''2241450''>a</span> <span m=''2241470''>lot</span> <span m=''2241690''>more</span>
  <span m=''2241810''>general,</span> <span m=''2242420''>and</span> <span m=''2242610''>this</span>
  <span m=''2242760''>can</span> <span m=''2242950''>be</span> <span m=''2243040''>sometimes</span>
  <span m=''2243440''>problematic.</span> </p><p><span m=''2244870''>So</span> <span
  m=''2245030''>when</span> <span m=''2245250''>you''re</span> <span m=''2245430''>going
  to</span> <span m=''2245460''>link,</span> <span m=''2246880''>the</span> <span
  m=''2247000''>nice</span> <span m=''2247250''>thing</span> <span m=''2247410''>is</span>
  <span m=''2247530''>that</span> <span m=''2247850''>this</span> <span m=''2247980''>is</span>
  <span m=''2248070''>a</span> <span m=''2248160''>place</span> <span m=''2248470''>you
  have</span> <span m=''2248780''>the entire</span> <span m=''2248990''>program</span>
  <span m=''2249450''>available.</span> <span m=''2250370''>Sometimes,</span> <span
  m=''2250830''>people</span> <span m=''2251100''>try</span> <span m=''2251270''>to</span>
  <span m=''2251310''>do</span> <span m=''2251460''>things</span> <span m=''2251650''>like</span>
  <span m=''2251790''>inlining</span> <span m=''2252330''>in</span> <span m=''2252420''>the</span>
  <span m=''2252510''>linktime,</span> <span m=''2253070''>because</span> <span m=''2253440''>that</span>
  <span m=''2253630''>means</span> <span m=''2253780''>you know</span> <span m=''2254130''>everything</span>
  <span m=''2254570''>in</span> <span m=''2254730''>there,</span> <span m=''2254940''>so</span>
  <span m=''2255070''>you</span> <span m=''2255220''>went</span> <span m=''2255390''>with</span>
  <span m=''2255550''>couple</span> <span m=''2255850''>different</span> <span m=''2256160''>file</span>
  <span m=''2256360''>I can</span> <span m=''2256420''>inline</span> <span m=''2256715''>it</span>
  <span m=''2257010''>because</span> <span m=''2257190''>I</span> <span m=''2257250''>have</span>
  <span m=''2257470''>access</span> <span m=''2257790''>through</span> <span m=''2258220''>here.</span>
  <span m=''2258650''>And</span> <span m=''2261400''>still,</span> <span m=''2261900''>there</span>
  <span m=''2262100''>might</span> <span m=''2262280''>be</span> <span m=''2262370''>things</span>
  <span m=''2262670''>that''s</span> <span m=''2262850''>not</span> <span m=''2263110''>available,</span>
  <span m=''2263430''>like</span> <span m=''2263630''>dynamically-loaded</span> <span
  m=''2264530''>classes</span> <span m=''2265000''>and</span> <span m=''2265190''>dynamic-loaded</span>
  <span m=''2265930''>data,</span> <span m=''2266580''>and</span> <span m=''2266780''>so</span>
  <span m=''2266910''>things</span> <span m=''2267160''>like</span> <span m=''2267320''>Java</span>
  <span m=''2267570''>might</span> <span m=''2267810''>not</span> <span m=''2267980''>be</span>
  <span m=''2268080''>available.</span> <span m=''2268960''>And</span> <span m=''2269200''>of</span>
  <span m=''2269340''>course,</span> <span m=''2269470''>you</span> <span m=''2269560''>don''t</span>
  <span m=''2269690''>have</span> <span m=''2269790''>access</span> <span m=''2270040''>to</span>
  <span m=''2270150''>source</span> <span m=''2270470''>most</span> <span m=''2270680''>of</span>
  <span m=''2270740''>the</span> <span m=''2270800''>time.</span> </p><p><span m=''2271636''>AUDIENCE:
  Sorry,</span> <span m=''2272132''>sir.</span> <span m=''2273124''>What do you</span>
  <span m=''2273620''>mean</span> <span m=''2274116''>[INAUDIBLE]?</span> <span m=''2274612''>Do
  you have</span> <span m=''2275108''>the full program</span> <span m=''2275604''>[INAUDIBLE]?</span>
  <span m=''2278580''>But</span> <span m=''2279076''>so</span> <span m=''2279572''>how
  do you</span> <span m=''2280068''>say that</span> <span m=''2280564''>[INAUDIBLE]?</span>
  </p><p><span m=''2282560''>PROFESSOR: So</span> <span m=''2282850''>dynamic</span>
  <span m=''2283320''>links,</span> <span m=''2284020''>if</span> <span m=''2284180''>you</span>
  <span m=''2284270''>have</span> <span m=''2284350''>something</span> <span m=''2284630''>like</span>
  <span m=''2284760''>Java,</span> <span m=''2285410''>there</span> <span m=''2285570''>might</span>
  <span m=''2285730''>be</span> <span m=''2285820''>some</span> <span m=''2286080''>data</span>
  <span m=''2286330''>that</span> <span m=''2286540''>kind</span> <span m=''2286730''>of</span>
  <span m=''2286770''>get</span> <span m=''2287060''>dynamically</span> <span m=''2287280''>generated</span>
  <span m=''2288000''>or</span> <span m=''2288060''>dynamically</span> <span m=''2288465''>linked.</span>
  <span m=''2289780''>So</span> <span m=''2289930''>when</span> <span m=''2290090''>you''re</span>
  <span m=''2290210''>running,</span> <span m=''2290520''>if</span> <span m=''2290540''>you''re</span>
  <span m=''2291050''>running</span> <span m=''2291590''>right</span> <span m=''2291980''>[UNINTELLIGIBLE]</span>
  <span m=''2292360''>your</span> <span m=''2292600''>browser,</span> <span m=''2294000''>all</span>
  <span m=''2294490''>those</span> <span m=''2294850''>Javascript</span> <span m=''2295480''>classes</span>
  <span m=''2296060''>and</span> <span m=''2296180''>stuff like</span> <span m=''2296450''>that,</span>
  <span m=''2296700''>you</span> <span m=''2296800''>don''t</span> <span m=''2296960''>have</span>
  <span m=''2297150''>access to</span> <span m=''2297450''>because</span> <span m=''2297590''>those</span>
  <span m=''2297910''>are</span> <span m=''2298050''>coming</span> <span m=''2298490''>in
  here.</span> <span m=''2298990''>So</span> <span m=''2299310''>there</span> <span
  m=''2299470''>might</span> <span m=''2299650''>be</span> <span m=''2299750''>places,</span>
  <span m=''2300290''>things</span> <span m=''2300570''>that</span> <span m=''2301350''>it</span>
  <span m=''2301430''>gets</span> <span m=''2301980''>as</span> <span m=''2302450''>it</span>
  <span m=''2302590''>runs.</span> <span m=''2303030''>Not</span> <span m=''2303240''>in</span>
  <span m=''2303370''>C,</span> <span m=''2303910''>but</span> <span m=''2304370''>in</span>
  <span m=''2304510''>other</span> <span m=''2304710''>languages.</span> </p><p><span
  m=''2306370''>And</span> <span m=''2306740''>the</span> <span m=''2306800''>load</span>
  <span m=''2307040''>is</span> <span m=''2307210''>interesting</span> <span m=''2307620''>time.</span>
  <span m=''2309070''>Here,</span> <span m=''2309290''>load</span> <span m=''2309540''>time</span>
  <span m=''2309820''>is</span> <span m=''2310260''>important</span> <span m=''2310700''>because</span>
  <span m=''2311030''>when</span> <span m=''2311230''>you</span> <span m=''2311270''>double-click,</span>
  <span m=''2312090''>you</span> <span m=''2312260''>want</span> <span m=''2312460''>your</span>
  <span m=''2312570''>program</span> <span m=''2312950''>to</span> <span m=''2313120''>appear</span>
  <span m=''2313300''>fast.</span> <span m=''2313710''>You</span> <span m=''2314090''>don''t</span>
  <span m=''2314260''>want it</span> <span m=''2314430''>to</span> <span m=''2315100''>take</span>
  <span m=''2315290''>a</span> <span m=''2315330''>long</span> <span m=''2315600''>time.</span>
  <span m=''2316120''>But</span> <span m=''2316610''>you</span> <span m=''2316760''>have</span>
  <span m=''2317400''>kind</span> <span m=''2317590''>of</span> <span m=''2317660''>access</span>
  <span m=''2318140''>to</span> <span m=''2320210''>all</span> <span m=''2320640''>that</span>
  <span m=''2320790''>code</span> <span m=''2320940''>in</span> <span m=''2321245''>here,</span>
  <span m=''2322010''>and</span> <span m=''2322200''>you</span> <span m=''2322270''>have</span>
  <span m=''2322420''>some</span> <span m=''2322650''>idea</span> <span m=''2322930''>about</span>
  <span m=''2323760''>the</span> <span m=''2324200''>run-time,</span> <span m=''2324490''>also,</span>
  <span m=''2324570''>the</span> <span m=''2324700''>architecture,</span> <span m=''2325220''>and</span>
  <span m=''2325350''>stuff</span> <span m=''2325600''>like</span> <span m=''2325790''>that,</span>
  <span m=''2326840''>what</span> <span m=''2327010''>you</span> <span m=''2327080''>have,</span>
  <span m=''2327360''>not</span> <span m=''2327570''>the</span> <span m=''2327720''>run-time,</span>
  <span m=''2328050''>but</span> <span m=''2328200''>the</span> <span m=''2328400''>architecture,</span>
  <span m=''2329030''>exactly</span> <span m=''2329440''>what machines</span> <span
  m=''2329560''>you are</span> <span m=''2329900''>running.</span> <span m=''2330580''>And</span>
  <span m=''2330770''>then,</span> <span m=''2330990''>of course,</span> <span m=''2331200''>you</span>
  <span m=''2331300''>can</span> <span m=''2331470''>do it</span> <span m=''2331750''>run-time.</span>
  </p><p><span m=''2332750''>The</span> <span m=''2332850''>thing</span> <span m=''2333040''>about</span>
  <span m=''2333360''>run-time is</span> <span m=''2333740''>you have</span> <span
  m=''2333820''>full knowledge</span> <span m=''2334370''>of</span> <span m=''2334470''>everything,</span>
  <span m=''2335000''>it''s great,</span> <span m=''2335650''>but</span> <span m=''2336290''>every</span>
  <span m=''2337420''>clock</span> <span m=''2337620''>cycle</span> <span m=''2337960''>you</span>
  <span m=''2338110''>spend</span> <span m=''2338560''>optimizing</span> <span m=''2339060''>is</span>
  <span m=''2339200''>one</span> <span m=''2339450''>clock</span> <span m=''2339630''>cycle</span>
  <span m=''2339870''>you</span> <span m=''2340170''>take</span> <span m=''2340380''>away</span>
  <span m=''2340510''>from</span> <span m=''2340640''>the</span> <span m=''2340720''>program.</span>
  <span m=''2341360''>So</span> <span m=''2341510''>things</span> <span m=''2341630''>like</span>
  <span m=''2341940''>Java</span> <span m=''2342270''>JIT</span> <span m=''2342570''>compilers,</span>
  <span m=''2343420''>they</span> <span m=''2343540''>try</span> <span m=''2343730''>to</span>
  <span m=''2343830''>do</span> <span m=''2344455''>minimal</span> <span m=''2344930''>things,</span>
  <span m=''2345100''>so</span> <span m=''2345270''>very</span> <span m=''2345510''>fast</span>
  <span m=''2345940''>things.</span> <span m=''2346270''>It</span> <span m=''2346620''>can''t</span>
  <span m=''2346890''>do</span> <span m=''2346950''>a</span> <span m=''2346970''>lot</span>
  <span m=''2347320''>of</span> <span m=''2347430''>complicated</span> <span m=''2347950''>things</span>
  <span m=''2348140''>because it''s</span> <span m=''2348420''>too</span> <span m=''2348550''>expensive.</span>
  </p><p><span m=''2349950''>OK,</span> <span m=''2350440''>so</span> <span m=''2351130''>we''re</span>
  <span m=''2351450''>not</span> <span m=''2351910''>talking</span> <span m=''2352190''>about</span>
  <span m=''2352370''>any</span> <span m=''2352570''>of</span> <span m=''2352710''>these</span>
  <span m=''2352970''>things</span> <span m=''2353720''>any</span> <span m=''2353960''>more,</span>
  <span m=''2354110''>but</span> <span m=''2354340''>it''s</span> <span m=''2354460''>always</span>
  <span m=''2354860''>good</span> <span m=''2354960''>to</span> <span m=''2355060''>know,</span>
  <span m=''2355180''>as</span> <span m=''2355410''>you</span> <span m=''2355550''>go</span>
  <span m=''2355840''>about</span> <span m=''2356640''>using</span> <span m=''2357150''>Python</span>
  <span m=''2357730''>or</span> <span m=''2357970''>Java</span> <span m=''2358250''>or</span>
  <span m=''2358710''>JavaScript</span> <span m=''2359360''>and</span> <span m=''2359750''>stuff</span>
  <span m=''2360000''>like</span> <span m=''2360120''>this</span> <span m=''2360370''>where</span>
  <span m=''2360850''>is</span> <span m=''2360980''>this</span> <span m=''2361210''>thing</span>
  <span m=''2361430''>happening</span> <span m=''2361790''>to</span> <span m=''2361860''>my
  code?</span> <span m=''2362860''>Because</span> <span m=''2363180''>it</span> <span
  m=''2363310''>might</span> <span m=''2363490''>not be</span> <span m=''2363690''>all</span>
  <span m=''2363870''>compile-time</span> <span m=''2364470''>stuff.</span> <span
  m=''2364720''>It</span> <span m=''2364870''>might</span> <span m=''2365040''>be</span>
  <span m=''2365110''>happening</span> <span m=''2365420''>at</span> <span m=''2365510''>different</span>
  <span m=''2365850''>stages.</span> <span m=''2366200''>So</span> <span m=''2366370''>you</span>
  <span m=''2366590''>need</span> <span m=''2366730''>to</span> <span m=''2366820''>know</span>
  <span m=''2367500''>who''s</span> <span m=''2367830''>actually</span> <span m=''2368100''>mucking</span>
  <span m=''2368510''>with your</span> <span m=''2368700''>code,</span> <span m=''2369150''>and</span>
  <span m=''2369290''>know</span> <span m=''2369580''>that there are</span> <span
  m=''2369690''>other</span> <span m=''2369910''>people</span> <span m=''2370120''>who</span>
  <span m=''2370270''>can</span> <span m=''2370370''>muck with</span> <span m=''2370660''>your
  code.</span> </p><p><span m=''2373470''>So</span> <span m=''2374120''>next,</span>
  <span m=''2374390''>I</span> <span m=''2374450''>want</span> <span m=''2374650''>to</span>
  <span m=''2374860''>switch</span> <span m=''2375225''>into</span> <span m=''2375810''>dataflow</span>
  <span m=''2375900''>analysis.</span> <span m=''2377390''>So</span> <span m=''2377530''>this</span>
  <span m=''2377720''>is</span> <span m=''2378630''>what</span> <span m=''2378940''>compilers</span>
  <span m=''2379500''>are</span> <span m=''2379590''>good</span> <span m=''2379820''>at,</span>
  <span m=''2379970''>and</span> <span m=''2380120''>compilers</span> <span m=''2380570''>try</span>
  <span m=''2380740''>to do</span> <span m=''2380970''>all</span> <span m=''2381090''>the</span>
  <span m=''2381200''>time.</span> <span m=''2381830''>So</span> <span m=''2383010''>it''s</span>
  <span m=''2383340''>basically</span> <span m=''2383630''>compile-time</span> <span
  m=''2384540''>reasoning</span> <span m=''2385100''>about</span> <span m=''2386090''>run-time</span>
  <span m=''2386770''>values</span> <span m=''2387040''>and</span> <span m=''2387310''>variables,</span>
  <span m=''2387840''>or</span> <span m=''2388120''>expressions,</span> <span m=''2388650''>within</span>
  <span m=''2388910''>the</span> <span m=''2388990''>program</span> <span m=''2390000''>at</span>
  <span m=''2390550''>different</span> <span m=''2390950''>program</span> <span m=''2391330''>points.</span>
  </p><p><span m=''2392310''>OK,</span> <span m=''2392410''>so</span> <span m=''2392480''>that</span>
  <span m=''2392630''>means</span> <span m=''2392740''>compile-time,</span> <span
  m=''2393280''>I</span> <span m=''2393390''>need</span> <span m=''2393590''>to</span>
  <span m=''2393780''>know</span> <span m=''2393960''>I have</span> <span m=''2394190''>this</span>
  <span m=''2394420''>program</span> <span m=''2394790''>point,</span> <span m=''2395250''>what</span>
  <span m=''2395620''>could it</span> <span m=''2395890''>be.</span> <span m=''2398400''>So</span>
  <span m=''2398530''>things</span> <span m=''2398830''>like</span> <span m=''2399110''>which</span>
  <span m=''2399290''>assignment</span> <span m=''2399870''>statement</span> <span
  m=''2400360''>produced</span> <span m=''2400700''>a</span> <span m=''2400750''>value</span>
  <span m=''2401095''>or</span> <span m=''2401440''>variable</span> <span m=''2401820''>that</span>
  <span m=''2401960''>I am</span> <span m=''2402060''>using?</span> <span m=''2403190''>OK,</span>
  <span m=''2403290''>if I</span> <span m=''2403540''>use</span> <span m=''2403730''>a
  value,</span> <span m=''2403920''>who</span> <span m=''2404270''>actually</span>
  <span m=''2404460''>created</span> <span m=''2404920''>that</span> <span m=''2405140''>value?</span>
  </p><p><span m=''2405750''>Or</span> <span m=''2407650''>which</span> <span m=''2407890''>variable</span>
  <span m=''2408160''>contain</span> <span m=''2411120''>values</span> <span m=''2411410''>that</span>
  <span m=''2411560''>are</span> <span m=''2411640''>no</span> <span m=''2411880''>longer</span>
  <span m=''2412090''>being</span> <span m=''2412270''>used</span> <span m=''2412500''>by</span>
  <span m=''2412600''>somebody</span> <span m=''2413040''>here?</span> <span m=''2413320''>So</span>
  <span m=''2413470''>that</span> <span m=''2413610''>means</span> <span m=''2413750''>I
  am</span> <span m=''2414070''>trying to</span> <span m=''2414180''>analyze</span>
  <span m=''2414520''>the</span> <span m=''2414600''>program</span> <span m=''2415480''>and</span>
  <span m=''2416050''>watch</span> <span m=''2416390''>the</span> <span m=''2416530''>range</span>
  <span m=''2416860''>of</span> <span m=''2416970''>values</span> <span m=''2417310''>that</span>
  <span m=''2417440''>each</span> <span m=''2417740''>variable</span> <span m=''2418060''>can</span>
  <span m=''2418230''>have.</span> <span m=''2420100''>So</span> <span m=''2420260''>the</span>
  <span m=''2420360''>key</span> <span m=''2420790''>thing</span> <span m=''2420960''>here</span>
  <span m=''2421240''>is</span> <span m=''2421600''>this</span> <span m=''2421760''>has</span>
  <span m=''2421930''>to</span> <span m=''2422040''>be</span> <span m=''2422390''>true</span>
  <span m=''2422660''>for</span> <span m=''2423030''>every</span> <span m=''2423580''>possible</span>
  <span m=''2424060''>input</span> <span m=''2424770''>at</span> <span m=''2424910''>every</span>
  <span m=''2425240''>possible</span> <span m=''2425610''>execution.</span> <span
  m=''2426920''>Normally,</span> <span m=''2427360''>[UNINTELLIGIBLE],</span> <span
  m=''2427890''>and</span> <span m=''2428070''>this</span> <span m=''2428330''>time,</span>
  <span m=''2428640''>I</span> <span m=''2428730''>know</span> <span m=''2429000''>why</span>
  <span m=''2429080''>my</span> <span m=''2429340''>variable</span> <span m=''2429780''>[UNINTELLIGIBLE],</span>
  <span m=''2430020''>but</span> <span m=''2431120''>every</span> <span m=''2431520''>possible</span>
  <span m=''2432020''>time,</span> <span m=''2432170''>this has to</span> <span m=''2432320''>be
  true.</span> </p><p><span m=''2433360''>OK,</span> <span m=''2433740''>if</span>
  <span m=''2433950''>there''s</span> <span m=''2434140''>a</span> <span m=''2434230''>condition</span>
  <span m=''2435110''>that</span> <span m=''2435630''>something</span> <span m=''2436040''>can</span>
  <span m=''2436190''>happen,</span> <span m=''2436565''>you</span> <span m=''2436940''>have</span>
  <span m=''2437050''>to</span> <span m=''2437160''>make</span> <span m=''2437360''>sure</span>
  <span m=''2437930''>that</span> <span m=''2438280''>condition</span> <span m=''2439130''>is</span>
  <span m=''2439320''>not</span> <span m=''2439480''>going</span> <span m=''2439580''>to</span>
  <span m=''2439670''>break</span> <span m=''2439890''>your</span> <span m=''2439990''>program.</span>
  <span m=''2441520''>Last</span> <span m=''2441780''>thing</span> <span m=''2442040''>you</span>
  <span m=''2442210''>want</span> <span m=''2442400''>from</span> <span m=''2442560''>optimizer</span>
  <span m=''2443200''>is</span> <span m=''2443910''>to</span> <span m=''2443980''>basically</span>
  <span m=''2444500''>start</span> <span m=''2444750''>producing</span> <span m=''2445160''>different</span>
  <span m=''2445460''>results.</span> <span m=''2446870''>Even</span> <span m=''2447260''>[UNINTELLIGIBLE],</span>
  <span m=''2447525''>it''s</span> <span m=''2447790''>not</span> <span m=''2448020''>good,</span>
  <span m=''2448730''>so</span> <span m=''2448880''>you</span> <span m=''2449000''>want</span>
  <span m=''2449290''>a</span> <span m=''2449350''>compile</span> <span m=''2449910''>optimizer</span>
  <span m=''2450270''>to</span> <span m=''2450340''>kind</span> <span m=''2450540''>of</span>
  <span m=''2450600''>produce</span> <span m=''2451000''>the same</span> <span m=''2451100''>result</span>
  <span m=''2451810''>that</span> <span m=''2451990''>you</span> <span m=''2452130''>got</span>
  <span m=''2452420''>without</span> <span m=''2452480''>optimizing.</span> <span
  m=''2453770''>And</span> <span m=''2454370''>this</span> <span m=''2454540''>is</span>
  <span m=''2454720''>why</span> <span m=''2454860''>this</span> <span m=''2455070''>has</span>
  <span m=''2455240''>to be</span> <span m=''2455630''>[UNINTELLIGIBLE].</span> </p><p><span
  m=''2457070''>So</span> <span m=''2457210''>first,</span> <span m=''2457520''>I
  want</span> <span m=''2457610''>to go</span> <span m=''2458010''>through</span>
  <span m=''2458610''>a</span> <span m=''2459050''>little</span> <span m=''2459290''>bit</span>
  <span m=''2459430''>of</span> <span m=''2459500''>example,</span> <span m=''2460010''>what</span>
  <span m=''2460350''>kind</span> <span m=''2460600''>of</span> <span m=''2460720''>things</span>
  <span m=''2460960''>the</span> <span m=''2461050''>compiler</span> <span m=''2461500''>do.</span>
  <span m=''2461990''>You</span> <span m=''2462180''>probably</span> <span m=''2462450''>have</span>
  <span m=''2462560''>seen</span> <span m=''2462890''>this</span> <span m=''2463260''>in</span>
  <span m=''2464110''>one</span> <span m=''2464320''>of</span> <span m=''2464400''>the</span>
  <span m=''2464770''>earlier lectures.</span> <span m=''2465290''>We</span> <span
  m=''2465430''>talked</span> <span m=''2465660''>about</span> <span m=''2465860''>some</span>
  <span m=''2466020''>of</span> <span m=''2466110''>this</span> <span m=''2466300''>as</span>
  <span m=''2466440''>hand</span> <span m=''2466710''>optimizations,</span> <span
  m=''2467750''>but</span> <span m=''2468020''>I''m</span> <span m=''2468170''>going</span>
  <span m=''2468340''>to</span> <span m=''2468400''>go</span> <span m=''2468590''>through</span>
  <span m=''2468750''>some</span> <span m=''2468960''>of</span> <span m=''2469070''>them</span>
  <span m=''2469630''>by</span> <span m=''2469850''>using</span> <span m=''2470170''>this</span>
  <span m=''2470350''>program.</span> </p><p><span m=''2476380''>It</span> <span m=''2476510''>doesn''t</span>
  <span m=''2476760''>mean</span> <span m=''2476930''>anything</span> <span m=''2477200''>what</span>
  <span m=''2477390''>I''m</span> <span m=''2477560''>doing</span> <span m=''2477940''>here.</span>
  <span m=''2478130''>I have</span> <span m=''2478320''>a</span> <span m=''2478410''>loop</span>
  <span m=''2478760''>here.</span> <span m=''2479490''>I''m</span> <span m=''2479740''>calculating</span>
  <span m=''2480350''>some</span> <span m=''2480560''>function</span> <span m=''2481030''>in</span>
  <span m=''2481160''>here.</span> <span m=''2481880''>And</span> <span m=''2482490''>then</span>
  <span m=''2482740''>I am</span> <span m=''2483690''>adding</span> <span m=''2484230''>something</span>
  <span m=''2484560''>else</span> <span m=''2484740''>to this x</span> <span m=''2485240''>here,</span>
  <span m=''2485890''>and</span> <span m=''2486060''>I</span> <span m=''2486080''>have</span>
  <span m=''2486210''>some</span> <span m=''2486440''>initializations</span> <span
  m=''2487580''>in</span> <span m=''2487690''>here,</span> <span m=''2487970''>just</span>
  <span m=''2489020''>something</span> <span m=''2489400''>that</span> <span m=''2489570''>I</span>
  <span m=''2489640''>can</span> <span m=''2489810''>demonstrate</span> <span m=''2490240''>what</span>
  <span m=''2490420''>it</span> <span m=''2490530''>does.</span> <span m=''2490770''>So</span>
  <span m=''2490870''>it has</span> <span m=''2491120''>no</span> <span m=''2491830''>meaning</span>
  <span m=''2492100''>for</span> <span m=''2492210''>this</span> <span m=''2492460''>one.</span>
  </p><p><span m=''2494020''>And</span> <span m=''2494150''>here''s</span> <span m=''2494690''>the</span>
  <span m=''2495110''>assembly</span> <span m=''2495530''>instructions.</span> <span
  m=''2496050''>I''m</span> <span m=''2496210''>not</span> <span m=''2496360''>going</span>
  <span m=''2496460''>to</span> <span m=''2496560''>go</span> <span m=''2496770''>through</span>
  <span m=''2496940''>assembly,</span> <span m=''2497720''>but</span> <span m=''2498140''>[UNINTELLIGIBLE]</span>
  <span m=''2499490''>you</span> <span m=''2499630''>can</span> <span m=''2499920''>actually</span>
  <span m=''2500070''>create</span> <span m=''2500430''>and</span> <span m=''2500560''>understand</span>
  <span m=''2501070''>why</span> <span m=''2501320''>this</span> <span m=''2501610''>is</span>
  <span m=''2501720''>happening</span> <span m=''2502440''>in</span> <span m=''2502570''>[INAUDIBLE].</span>
  <span m=''2503360''>So</span> <span m=''2503600''>I</span> <span m=''2503840''>[UNINTELLIGIBLE]</span>
  <span m=''2504140''>into</span> <span m=''2504610''>two</span> <span m=''2504790''>slides.</span>
  </p><p><span m=''2507710''>The</span> <span m=''2508060''>first</span> <span m=''2508350''>thing</span>
  <span m=''2508490''>you</span> <span m=''2508600''>can</span> <span m=''2508810''>do</span>
  <span m=''2508970''>is</span> <span m=''2509290''>think of</span> <span m=''2509910''>constant</span>
  <span m=''2510300''>propagation.</span> <span m=''2511780''>So what</span> <span
  m=''2512210''>it</span> <span m=''2512340''>says</span> <span m=''2512590''>is</span>
  <span m=''2513510''>for</span> <span m=''2513870''>all</span> <span m=''2514320''>possible</span>
  <span m=''2514880''>executions,</span> <span m=''2516930''>if</span> <span m=''2517080''>a</span>
  <span m=''2517180''>value</span> <span m=''2517950''>that</span> <span m=''2518140''>has</span>
  <span m=''2518440''>in</span> <span m=''2518540''>a</span> <span m=''2518580''>variable</span>
  <span m=''2519500''>is</span> <span m=''2519650''>the</span> <span m=''2519720''>same,</span>
  <span m=''2520150''>and</span> <span m=''2520240''>we</span> <span m=''2520390''>know</span>
  <span m=''2520520''>that</span> <span m=''2520700''>value,</span> <span m=''2522180''>that''s</span>
  <span m=''2522360''>a</span> <span m=''2522440''>constant.</span> <span m=''2523220''>And</span>
  <span m=''2523410''>I</span> <span m=''2523520''>don''t</span> <span m=''2523630''>have</span>
  <span m=''2523770''>to</span> <span m=''2523830''>keep</span> <span m=''2524050''>that
  value</span> <span m=''2524340''>in</span> <span m=''2524500''>that</span> <span
  m=''2524680''>variable.</span> <span m=''2525060''>I</span> <span m=''2525130''>can</span>
  <span m=''2525320''>replace</span> <span m=''2525790''>that</span> <span m=''2525980''>with</span>
  <span m=''2526120''>a</span> <span m=''2526260''>constant.</span> </p><p><span m=''2532590''>Sometimes,</span>
  <span m=''2533120''>when</span> <span m=''2533230''>you</span> <span m=''2533310''>look</span>
  <span m=''2533440''>at</span> <span m=''2533570''>dataflow</span> <span m=''2533790''>optimization,</span>
  <span m=''2534370''>you</span> <span m=''2534480''>can</span> <span m=''2534600''>say</span>
  <span m=''2535120''>this</span> <span m=''2535250''>is</span> <span m=''2535430''>done.</span>
  <span m=''2535880''>As</span> <span m=''2535990''>a</span> <span m=''2536100''>programmer,</span>
  <span m=''2536670''>I will</span> <span m=''2536840''>never</span> <span m=''2537010''>do
  that.</span> <span m=''2538330''>This</span> <span m=''2538510''>is</span> <span
  m=''2538630''>something</span> <span m=''2538940''>you</span> <span m=''2539000''>should</span>
  <span m=''2539220''>be</span> <span m=''2539340''>doing,</span> <span m=''2539590''>for</span>
  <span m=''2539740''>example,</span> <span m=''2540200''>have</span> <span m=''2541280''>things</span>
  <span m=''2541500''>like</span> <span m=''2541620''>constant</span> <span m=''2542100''>variables</span>
  <span m=''2542630''>that</span> <span m=''2542820''>constant</span> <span m=''2543240''>values</span>
  <span m=''2543370''>or</span> <span m=''2543500''>lower.</span> </p><p><span m=''2544100''>But</span>
  <span m=''2544360''>sometimes,</span> <span m=''2544790''>something</span> <span
  m=''2545020''>looks</span> <span m=''2545250''>dumb,</span> <span m=''2545400''>but</span>
  <span m=''2545820''>what</span> <span m=''2545990''>happens</span> <span m=''2546410''>is</span>
  <span m=''2546500''>sometimes</span> <span m=''2547010''>when</span> <span m=''2547090''>you''re</span>
  <span m=''2547380''>in</span> <span m=''2547520''>optimization</span> <span m=''2548440''>does,</span>
  <span m=''2548900''>one</span> <span m=''2549190''>optimization</span> <span m=''2549900''>might</span>
  <span m=''2550160''>lead</span> <span m=''2550870''>to</span> <span m=''2550980''>code
  that</span> <span m=''2551480''>looks</span> <span m=''2551690''>like.</span> <span
  m=''2552390''>That</span> <span m=''2552600''>can</span> <span m=''2552870''>lead</span>
  <span m=''2553080''>to it.</span> <span m=''2553230''>I will</span> <span m=''2553550''>show</span>
  <span m=''2553790''>you</span> <span m=''2553870''>something</span> <span m=''2554250''>sometimes</span>
  <span m=''2555290''>that</span> <span m=''2555700''>you</span> <span m=''2555850''>might</span>
  <span m=''2556080''>not</span> <span m=''2556290''>find</span> <span m=''2556540''>a</span>
  <span m=''2556680''>code</span> <span m=''2556930''>that</span> <span m=''2557090''>looks</span>
  <span m=''2557280''>dumb,</span> <span m=''2557650''>but</span> <span m=''2558170''>previous</span>
  <span m=''2558640''>optimization</span> <span m=''2559320''>will</span> <span m=''2559430''>leave,</span>
  <span m=''2560140''>or</span> <span m=''2560460''>change</span> <span m=''2560890''>the</span>
  <span m=''2561010''>code</span> <span m=''2561300''>in a way</span> <span m=''2561550''>that</span>
  <span m=''2561810''>this</span> <span m=''2562070''>optimization</span> <span m=''2562510''>can</span>
  <span m=''2562820''>take</span> <span m=''2563040''>advantage</span> <span m=''2563580''>of.</span>
  <span m=''2564920''>So</span> <span m=''2565490''>nice</span> <span m=''2565700''>thing</span>
  <span m=''2565910''>about</span> <span m=''2566390''>this</span> <span m=''2566710''>is</span>
  <span m=''2568180''>you</span> <span m=''2568320''>don''t</span> <span m=''2568450''>need</span>
  <span m=''2568590''>to</span> <span m=''2568660''>keep</span> <span m=''2568850''>values</span>
  <span m=''2569150''>in</span> <span m=''2569220''>the</span> <span m=''2569300''>variables</span>
  <span m=''2570160''>because</span> <span m=''2570270''>you</span> <span m=''2570360''>can</span>
  <span m=''2570850''>free</span> <span m=''2571050''>some</span> <span m=''2571500''>variable,</span>
  <span m=''2571700''>that</span> <span m=''2571800''>means</span> <span m=''2571960''>free</span>
  <span m=''2572040''>RAM</span> <span m=''2572290''>registers.</span> <span m=''2573582''>Also,</span>
  <span m=''2574580''>most</span> <span m=''2574750''>of</span> <span m=''2574920''>the</span>
  <span m=''2575010''>time when</span> <span m=''2575230''>you do</span> <span m=''2575480''>constant</span>
  <span m=''2575780''>propagation</span> <span m=''2576380''>it leads to</span> <span
  m=''2576610''>[UNINTELLIGIBLE]</span> <span m=''2577050''>optimizations.</span>
  </p><p><span m=''2579130''>So</span> <span m=''2579280''>in</span> <span m=''2579510''>this</span>
  <span m=''2579710''>program</span> <span m=''2580660''>what</span> <span m=''2581160''>are</span>
  <span m=''2581390''>the</span> <span m=''2581610''>things</span> <span m=''2581860''>that</span>
  <span m=''2582030''>can</span> <span m=''2582190''>be</span> <span m=''2582320''>constant</span>
  <span m=''2582580''>propagated?</span> <span m=''2583650''>So</span> <span m=''2584833''>we
  know</span> <span m=''2585296''>x</span> <span m=''2585760''>equals</span> <span
  m=''2585910''>0,</span> <span m=''2587210''>x''s</span> <span m=''2587540''>are</span>
  <span m=''2587630''>constant</span> <span m=''2588000''>up</span> <span m=''2588120''>to</span>
  <span m=''2588200''>this</span> <span m=''2588410''>point.</span> <span m=''2589700''>But</span>
  <span m=''2592730''>since</span> <span m=''2593210''>x</span> <span m=''2593600''>get</span>
  <span m=''2594120''>modified</span> <span m=''2594555''>here,</span> <span m=''2595230''>my</span>
  <span m=''2595370''>dataflow</span> <span m=''2595940''>say</span> <span m=''2596130''>wait</span>
  <span m=''2596330''>a</span> <span m=''2596360''>minute,</span> <span m=''2596760''>I</span>
  <span m=''2596990''>am</span> <span m=''2597230''>going</span> <span m=''2597460''>through</span>
  <span m=''2597610''>this</span> <span m=''2597820''>loop,</span> <span m=''2598460''>and</span>
  <span m=''2599430''>x</span> <span m=''2599790''>is</span> <span m=''2600350''>constant</span>
  <span m=''2600860''>from</span> <span m=''2601060''>here</span> <span m=''2601370''>to</span>
  <span m=''2601440''>here.</span> <span m=''2601670''>But</span> <span m=''2601990''>after</span>
  <span m=''2602400''>this</span> <span m=''2602570''>point,</span> <span m=''2602790''>x</span>
  <span m=''2602960''>is</span> <span m=''2603080''>not</span> <span m=''2603250''>constant</span>
  <span m=''2603630''>because</span> <span m=''2603910''>it get</span> <span m=''2604230''>modified</span>
  <span m=''2604610''>in here.</span> <span m=''2605780''>So</span> <span m=''2606040''>that''s</span>
  <span m=''2606210''>what</span> <span m=''2606440''>dataflow</span> <span m=''2606630''>is</span>
  <span m=''2606910''>going to</span> <span m=''2607040''>say,</span> <span m=''2607860''>and
  so</span> <span m=''2608050''>I</span> <span m=''2608130''>can''t</span> <span m=''2608330''>do</span>
  <span m=''2608440''>that</span> <span m=''2608590''>x.</span> </p><p><span m=''2609540''>But</span>
  <span m=''2609750''>[UNINTELLIGIBLE]</span> <span m=''2611310''>why it</span> <span
  m=''2611580''>become</span> <span m=''2611900''>constant</span> <span m=''2612330''>here?</span>
  <span m=''2612870''>All</span> <span m=''2613150''>input</span> <span m=''2613540''>that</span>
  <span m=''2613720''>goes</span> <span m=''2613980''>into</span> <span m=''2614140''>this</span>
  <span m=''2614370''>loop,</span> <span m=''2614910''>has</span> <span m=''2615150''>to</span>
  <span m=''2615230''>go</span> <span m=''2615400''>through</span> <span m=''2615570''>here,</span>
  <span m=''2615760''>becomes</span> <span m=''2616190''>constant</span> <span m=''2617060''>in
  every</span> <span m=''2617370''>path.</span> <span m=''2617940''>And</span> <span
  m=''2618140''>then</span> <span m=''2618810''>it</span> <span m=''2618970''>doesn''t</span>
  <span m=''2619350''>get</span> <span m=''2619510''>modified</span> <span m=''2619750''>in
  this</span> <span m=''2619950''>loop</span> <span m=''2620050''>at</span> <span
  m=''2620420''>all.</span> <span m=''2621900''>OK,</span> <span m=''2622290''>so</span>
  <span m=''2622480''>then</span> <span m=''2622840''>I</span> <span m=''2622910''>can</span>
  <span m=''2623130''>actually,</span> <span m=''2625000''>through</span> <span m=''2625250''>constant</span>
  <span m=''2625510''>propagation,</span> <span m=''2625770''>get</span> <span m=''2625880''>to</span>
  <span m=''2625960''>the</span> <span m=''2626080''>file.</span> <span m=''2627650''>OK,</span>
  <span m=''2628390''>so</span> <span m=''2628580''>now</span> <span m=''2629310''>I</span>
  <span m=''2629410''>have</span> <span m=''2629540''>a</span> <span m=''2629590''>program</span>
  <span m=''2629950''>like</span> <span m=''2630140''>that.</span> </p><p><span m=''2630360''>So</span>
  <span m=''2630450''>normal</span> <span m=''2631020''>compiler</span> <span m=''2631230''>optimization</span>
  <span m=''2631880''>is</span> <span m=''2632010''>done</span> <span m=''2632260''>by</span>
  <span m=''2632880''>pass-by-pass.</span> <span m=''2633860''>A lot of</span> <span
  m=''2634170''>passes get</span> <span m=''2634480''>repeated</span> <span m=''2634870''>multiple</span>
  <span m=''2635280''>times,</span> <span m=''2635570''>so I</span> <span m=''2635790''>leave
  it</span> <span m=''2636150''>like this.</span> <span m=''2636590''>So</span> <span
  m=''2636950''>even</span> <span m=''2637220''>though</span> <span m=''2637400''>this</span>
  <span m=''2637835''>is</span> <span m=''2638270''>just</span> <span m=''2638970''>simple</span>
  <span m=''2639170''>thing,</span> <span m=''2639840''>but</span> <span m=''2640100''>we</span>
  <span m=''2641220''>leave it to</span> <span m=''2641430''>somebody</span> <span
  m=''2641830''>else</span> <span m=''2642080''>to</span> <span m=''2642380''>optimize</span>
  <span m=''2642510''>that,</span> <span m=''2643090''>which</span> <span m=''2643350''>is</span>
  <span m=''2643490''>what</span> <span m=''2643640''>we</span> <span m=''2643730''>call</span>
  <span m=''2644070''>algebraic</span> <span m=''2644180''>simplification.</span>
  <span m=''2646020''>Basically,</span> <span m=''2646840''>it</span> <span m=''2647120''>says</span>
  <span m=''2647440''>you</span> <span m=''2647660''>go</span> <span m=''2647870''>to</span>
  <span m=''2648010''>your,</span> <span m=''2648440''>whatever,</span> <span m=''2649090''>fourth</span>
  <span m=''2649280''>grade,</span> <span m=''2649460''>fifth</span> <span m=''2649640''>grade,</span>
  <span m=''2649910''>sixth</span> <span m=''2650180''>grade</span> <span m=''2651500''>algebra</span>
  <span m=''2651810''>book--</span> <span m=''2652120''>I don''t</span> <span m=''2652290''>know</span>
  <span m=''2652500''>where</span> <span m=''2652590''>you</span> <span m=''2652800''>learn,</span>
  <span m=''2652990''>somewhere</span> <span m=''2653300''>you</span> <span m=''2653540''>learned</span>
  <span m=''2653790''>algebraic</span> <span m=''2654730''>--and</span> <span m=''2654980''>they</span>
  <span m=''2655180''>have</span> <span m=''2655380''>all</span> <span m=''2655510''>these</span>
  <span m=''2655760''>very</span> <span m=''2655890''>simple</span> <span m=''2656020''>rules,</span>
  <span m=''2657750''>like</span> <span m=''2658180''>something</span> <span m=''2658580''>multiplied</span>
  <span m=''2658760''>by 0</span> <span m=''2658930''>is 0,</span> <span m=''2659350''>multiply</span>
  <span m=''2659690''>1</span> <span m=''2659900''>by</span> <span m=''2660190''>that,</span>
  <span m=''2660600''>and</span> <span m=''2660770''>all</span> <span m=''2660980''>of</span>
  <span m=''2661080''>those</span> <span m=''2661300''>rules,</span> <span m=''2661830''>and</span>
  <span m=''2662010''>then</span> <span m=''2662150''>you</span> <span m=''2662290''>can</span>
  <span m=''2662430''>just</span> <span m=''2662600''>busy</span> <span m=''2662890''>code</span>
  <span m=''2663240''>them</span> <span m=''2663400''>up</span> <span m=''2663850''>and</span>
  <span m=''2664030''>look</span> <span m=''2664170''>for</span> <span m=''2664260''>these</span>
  <span m=''2664460''>patterns</span> <span m=''2664620''>and</span> <span m=''2664900''>replace.</span>
  <span m=''2666460''>And</span> <span m=''2666650''>that''s</span> <span m=''2666830''>what</span>
  <span m=''2666890''>the</span> <span m=''2667060''>compiler</span> <span m=''2667300''>does.</span>
  </p><p><span m=''2668230''>And</span> <span m=''2668480''>in</span> <span m=''2668600''>fact,</span>
  <span m=''2668830''>we</span> <span m=''2669320''>look</span> <span m=''2669500''>at</span>
  <span m=''2669600''>something</span> <span m=''2669890''>like</span> <span m=''2670100''>this,</span>
  <span m=''2670240''>a</span> <span m=''2670310''>simple</span> <span m=''2670980''>shape,</span>
  <span m=''2671630''>but</span> <span m=''2671810''>you</span> <span m=''2671970''>saw</span>
  <span m=''2672200''>before</span> <span m=''2672560''>that,</span> <span m=''2672690''>it</span>
  <span m=''2672820''>do</span> <span m=''2673020''>much</span> <span m=''2673360''>more</span>
  <span m=''2673490''>complicated</span> <span m=''2673970''>things.</span> <span
  m=''2675220''>And</span> <span m=''2676170''>it''s</span> <span m=''2676340''>a</span>
  <span m=''2676400''>lot</span> <span m=''2676750''>less</span> <span m=''2676950''>work</span>
  <span m=''2677120''>at</span> <span m=''2677220''>run-time,</span> <span m=''2677770''>and</span>
  <span m=''2678060''>also</span> <span m=''2678390''>it leads</span> <span m=''2678640''>to
  more</span> <span m=''2678820''>optimization,</span> <span m=''2679480''>so</span>
  <span m=''2679590''>it</span> <span m=''2679690''>can</span> <span m=''2679940''>simplify</span>
  <span m=''2680370''>things</span> <span m=''2680630''>in here.</span> <span m=''2681870''>And</span>
  <span m=''2683970''>other</span> <span m=''2684230''>thing</span> <span m=''2684500''>is,</span>
  <span m=''2685170''>sometimes</span> <span m=''2686000''>instead of</span> <span
  m=''2686275''>algebraic</span> <span m=''2686550''>simplification,</span> <span
  m=''2687410''>kind</span> <span m=''2687810''>of</span> <span m=''2687920''>weird</span>
  <span m=''2688230''>things.</span> <span m=''2690080''>If</span> <span m=''2690180''>you</span>
  <span m=''2690440''>want</span> <span m=''2690820''>exact</span> <span m=''2692180''>precise,</span>
  <span m=''2693320''>for</span> <span m=''2693490''>example</span> <span m=''2693850''>if
  you''re</span> <span m=''2693970''>doing</span> <span m=''2694100''>floating</span>
  <span m=''2694460''>point,</span> <span m=''2694730''>because</span> <span m=''2695170''>floating</span>
  <span m=''2695650''>point,</span> <span m=''2697190''>a</span> <span m=''2697210''>plus</span>
  <span m=''2697590''>b</span> <span m=''2697900''>plus</span> <span m=''2698270''>c,</span>
  <span m=''2698660''>is</span> <span m=''2698850''>not</span> <span m=''2701920''>b</span>
  <span m=''2702090''>plus</span> <span m=''2702430''>c</span> <span m=''2702680''>plus</span>
  <span m=''2702935''>a,</span> <span m=''2703190''>are</span> <span m=''2703340''>different</span>
  <span m=''2703550''>because</span> <span m=''2703910''>you</span> <span m=''2704000''>can</span>
  <span m=''2704120''>get</span> <span m=''2704660''>small</span> <span m=''2705200''>teeny</span>
  <span m=''2705740''>differences</span> <span m=''2706770''>in</span> <span m=''2707750''>these</span>
  <span m=''2708000''>kind</span> <span m=''2708240''>of--</span> <span m=''2709520''>[UNINTELLIGIBLE]</span>
  <span m=''2710670''>and</span> <span m=''2710860''>associate</span> <span m=''2711160''>duty,</span>
  <span m=''2711810''>and</span> <span m=''2712050''>some</span> <span m=''2712260''>people</span>
  <span m=''2712600''>care.</span> <span m=''2712850''>Most</span> <span m=''2713120''>people</span>
  <span m=''2713360''>don''t</span> <span m=''2713610''>because</span> <span m=''2713800''>it''s</span>
  <span m=''2714180''>so</span> <span m=''2714640''>small,</span> <span m=''2714850''>most</span>
  <span m=''2715120''>people,</span> <span m=''2715360''>they</span> <span m=''2715500''>don''t</span>
  <span m=''2715690''>care.</span> <span m=''2716240''>Others</span> <span m=''2716430''>do.</span>
  </p><p><span m=''2716930''>And</span> <span m=''2717160''>also</span> <span m=''2717480''>sometimes</span>
  <span m=''2717970''>when you</span> <span m=''2718010''>do</span> <span m=''2718180''>this</span>
  <span m=''2718640''>optimization,</span> <span m=''2719330''>things</span> <span
  m=''2719730''>like</span> <span m=''2720010''>overflow</span> <span m=''2720620''>and</span>
  <span m=''2720730''>underflow,</span> <span m=''2720980''>that</span> <span m=''2721150''>happens</span>
  <span m=''2722040''>because</span> <span m=''2722410''>if</span> <span m=''2722590''>I</span>
  <span m=''2722710''>do</span> <span m=''2723820''>x</span> <span m=''2724080''>plus</span>
  <span m=''2724310''>x</span> <span m=''2725040''>minus</span> <span m=''2725460''>x,</span>
  <span m=''2726310''>or</span> <span m=''2726840''>x</span> <span m=''2727040''>is</span>
  <span m=''2727180''>very</span> <span m=''2727370''>large,</span> <span m=''2727660''>x</span>
  <span m=''2727915''>plus</span> <span m=''2728170''>x</span> <span m=''2728640''>minus</span>
  <span m=''2728810''>overflow,</span> <span m=''2730180''>and</span> <span m=''2730340''>then</span>
  <span m=''2730510''>you</span> <span m=''2731220''>end</span> <span m=''2731340''>of</span>
  <span m=''2731440''>doing</span> <span m=''2731540''>minus</span> <span m=''2731920''>x</span>
  <span m=''2732060''>because</span> <span m=''2732140''>it</span> <span m=''2732260''>overflows.</span>
  <span m=''2732960''>But</span> <span m=''2733280''>instead of</span> <span m=''2733680''>x
  plus</span> <span m=''2734050''>x</span> <span m=''2734190''>minus</span> <span
  m=''2734460''>x,</span> <span m=''2734670''>it''s</span> <span m=''2734790''>just</span>
  <span m=''2734990''>x,</span> <span m=''2735890''>you</span> <span m=''2735980''>don''t</span>
  <span m=''2736120''>overflow</span> <span m=''2736460''>anymore.</span> <span m=''2737450''>So</span>
  <span m=''2737600''>you</span> <span m=''2737660''>have</span> <span m=''2737950''>changed</span>
  <span m=''2738260''>the</span> <span m=''2738350''>behavior</span> <span m=''2738690''>of</span>
  <span m=''2738780''>the</span> <span m=''2738860''>program,</span> <span m=''2739580''>but</span>
  <span m=''2739880''>most</span> <span m=''2740160''>of</span> <span m=''2740450''>the</span>
  <span m=''2740560''>time,</span> <span m=''2740710''>compilers</span> <span m=''2740960''>think</span>
  <span m=''2741190''>that</span> <span m=''2741670''>things</span> <span m=''2742010''>like</span>
  <span m=''2742200''>that</span> <span m=''2742420''>are</span> <span m=''2745060''>special</span>
  <span m=''2745550''>cases.</span> <span m=''2746020''>They are</span> <span m=''2746200''>not</span>
  <span m=''2746380''>the</span> <span m=''2746460''>normal</span> <span m=''2746760''>behavior,</span>
  <span m=''2747250''>so</span> <span m=''2747580''>changing</span> <span m=''2748100''>them</span>
  <span m=''2748520''>is</span> <span m=''2748700''>probably</span> <span m=''2748940''>OK.</span>
  <span m=''2749290''>Sometimes,</span> <span m=''2749650''>you can''t</span> <span
  m=''2749990''>do</span> <span m=''2750330''>anything.</span> </p><p><span m=''2753250''>So</span>
  <span m=''2753430''>now</span> <span m=''2753600''>here,</span> <span m=''2754540''>what</span>
  <span m=''2754780''>are</span> <span m=''2754950''>algebraic</span> <span m=''2755400''>simplification</span>
  <span m=''2755940''>I</span> <span m=''2756000''>can</span> <span m=''2756200''>do?</span>
  <span m=''2765640''>What</span> <span m=''2765810''>can I</span> <span m=''2765920''>do</span>
  <span m=''2766000''>here?</span> <span m=''2773320''>Yeah,</span> <span m=''2773820''>I</span>
  <span m=''2773970''>multiply</span> <span m=''2774430''>by</span> <span m=''2774500''>0,</span>
  <span m=''2774650''>[UNINTELLIGIBLE]</span> <span m=''2775540''>this,</span> <span
  m=''2775770''>that.</span> <span m=''2776250''>At 0,</span> <span m=''2776510''>I</span>
  <span m=''2776580''>leave</span> <span m=''2776810''>it here,</span> <span m=''2777540''>and</span>
  <span m=''2777890''>then</span> <span m=''2778040''>there''s</span> <span m=''2778260''>another</span>
  <span m=''2778510''>algebraic</span> <span m=''2778880''>simplification,</span>
  <span m=''2779520''>I</span> <span m=''2779570''>can</span> <span m=''2779760''>do</span>
  <span m=''2779860''>that,</span> <span m=''2780920''>but</span> <span m=''2781090''>now,</span>
  <span m=''2781240''>I am</span> <span m=''2781340''>leaving it</span> <span m=''2781760''>here</span>
  <span m=''2782570''>because</span> <span m=''2782830''>there''s no</span> <span
  m=''2783120''>algebraic</span> <span m=''2783960''>simplification.</span> </p><p><span
  m=''2784960''>X</span> <span m=''2785190''>equals</span> <span m=''2785440''>x</span>
  <span m=''2785820''>is--</span> <span m=''2786720''>there''s</span> <span m=''2786910''>nothing</span>
  <span m=''2787140''>you</span> <span m=''2787270''>can</span> <span m=''2787400''>do.</span>
  <span m=''2787610''>That''s</span> <span m=''2787860''>called</span> <span m=''2789280''>copy</span>
  <span m=''2789350''>propagation.</span> <span m=''2790530''>Copy</span> <span m=''2790690''>propagation</span>
  <span m=''2791360''>says</span> <span m=''2791740''>you''re</span> <span m=''2792090''>just</span>
  <span m=''2792390''>making</span> <span m=''2792740''>a</span> <span m=''2792760''>copy</span>
  <span m=''2793110''>of</span> <span m=''2793250''>one</span> <span m=''2793370''>value
  to</span> <span m=''2793790''>another,</span> <span m=''2794410''>just</span> <span
  m=''2794700''>get</span> <span m=''2795100''>another</span> <span m=''2795310''>copy.</span>
  </p><p><span m=''2795940''>You</span> <span m=''2796040''>don''t</span> <span m=''2796150''>need</span>
  <span m=''2796280''>to do</span> <span m=''2796690''>a</span> <span m=''2796870''>copy.</span>
  <span m=''2797160''>Very</span> <span m=''2797570''>simple thing</span> <span m=''2797920''>in
  here.</span> <span m=''2798820''>Less</span> <span m=''2798990''>instructions,</span>
  <span m=''2799530''>less</span> <span m=''2799910''>memory</span> <span m=''2800100''>registers</span>
  <span m=''2800750''>because</span> <span m=''2801020''>we</span> <span m=''2801180''>are
  not</span> <span m=''2801310''>copying.</span> <span m=''2802180''>However,</span>
  <span m=''2802880''>when</span> <span m=''2803370''>we</span> <span m=''2803520''>[UNINTELLIGIBLE]</span>
  <span m=''2804300''>register</span> <span m=''2804840''>location,</span> <span m=''2805270''>I
  will</span> <span m=''2805520''>talk,</span> <span m=''2806010''>basically.</span>
  <span m=''2807410''>If</span> <span m=''2807710''>I</span> <span m=''2807800''>use</span>
  <span m=''2808080''>the</span> <span m=''2808150''>same</span> <span m=''2808390''>register</span>
  <span m=''2808970''>now,</span> <span m=''2809480''>I</span> <span m=''2809630''>might</span>
  <span m=''2809950''>have</span> <span m=''2811220''>things</span> <span m=''2811510''>that</span>
  <span m=''2811710''>was</span> <span m=''2811900''>in two</span> <span m=''2812250''>registers,</span>
  <span m=''2812570''>x</span> <span m=''2812820''>copied</span> <span m=''2813090''>to</span>
  <span m=''2813210''>y,</span> <span m=''2813860''>now it''s</span> <span m=''2814140''>all</span>
  <span m=''2814340''>in</span> <span m=''2814560''>x.</span> <span m=''2815300''>So</span>
  <span m=''2815450''>that</span> <span m=''2815710''>means</span> <span m=''2815930''>I</span>
  <span m=''2816010''>might</span> <span m=''2816280''>have</span> <span m=''2816600''>some</span>
  <span m=''2816840''>variable</span> <span m=''2817410''>in</span> <span m=''2818000''>the</span>
  <span m=''2818220''>register</span> <span m=''2819330''>that</span> <span m=''2819710''>you</span>
  <span m=''2820060''>call</span> <span m=''2821430''>my</span> <span m=''2821960''>interference</span>
  <span m=''2822620''>graph.</span> </p><p><span m=''2822850''>I''ll</span> <span
  m=''2822930''>talk</span> <span m=''2823270''>about</span> <span m=''2823440''>this</span>
  <span m=''2823680''>in</span> <span m=''2823780''>a little</span> <span m=''2823910''>while,</span>
  <span m=''2824620''>so</span> <span m=''2824770''>I''m</span> <span m=''2824940''>just</span>
  <span m=''2825440''>forward</span> <span m=''2825820''>referencing.</span> <span
  m=''2826710''>That</span> <span m=''2827050''>might</span> <span m=''2827310''>not</span>
  <span m=''2827590''>be</span> <span m=''2827770''>easily</span> <span m=''2828960''>register</span>
  <span m=''2829380''>locatable.</span> <span m=''2831440''>And</span> <span m=''2831620''>so</span>
  <span m=''2831710''>in here,</span> <span m=''2831880''>x</span> <span m=''2832170''>equals</span>
  <span m=''2832460''>x.</span> <span m=''2832600''>I</span> <span m=''2832740''>can</span>
  <span m=''2832900''>get</span> <span m=''2833040''>rid of</span> <span m=''2833270''>that.</span>
  </p><p><span m=''2834680''>And</span> <span m=''2835140''>another</span> <span m=''2835390''>interesting</span>
  <span m=''2835730''>thing</span> <span m=''2835880''>is</span> <span m=''2836000''>common</span>
  <span m=''2836400''>subexpression</span> <span m=''2836840''>elimination.</span>
  <span m=''2837620''>If</span> <span m=''2837710''>you</span> <span m=''2837810''>do</span>
  <span m=''2837940''>the</span> <span m=''2838040''>same thing</span> <span m=''2838240''>multiple</span>
  <span m=''2838725''>times, you</span> <span m=''2839210''>calculate it</span> <span
  m=''2839710''>once,</span> <span m=''2840210''>less</span> <span m=''2840410''>computation,</span>
  <span m=''2841580''>Cons</span> <span m=''2842440''>is you</span> <span m=''2842860''>need</span>
  <span m=''2843010''>to</span> <span m=''2843080''>keep</span> <span m=''2843340''>this</span>
  <span m=''2843550''>result</span> <span m=''2843920''>somewhere</span> <span m=''2844380''>between</span>
  <span m=''2844710''>the</span> <span m=''2844810''>two</span> <span m=''2844990''>users.</span>
  <span m=''2846220''>So</span> <span m=''2846550''>if</span> <span m=''2846750''>I</span>
  <span m=''2846830''>have</span> <span m=''2847020''>too</span> <span m=''2847170''>many</span>
  <span m=''2847340''>of</span> <span m=''2847460''>these</span> <span m=''2847680''>things,</span>
  <span m=''2848000''>I</span> <span m=''2848110''>might</span> <span m=''2848330''>just</span>
  <span m=''2848460''>run</span> <span m=''2848630''>out of</span> <span m=''2848770''>registers</span>
  <span m=''2849220''>to</span> <span m=''2849360''>keep</span> <span m=''2849600''>these</span>
  <span m=''2849820''>values</span> <span m=''2850240''>calculated.</span> </p><p><span
  m=''2851470''>And</span> <span m=''2851760''>also</span> <span m=''2852190''>interesting</span>
  <span m=''2852600''>thing</span> <span m=''2852830''>is,</span> <span m=''2853050''>this</span>
  <span m=''2853250''>can</span> <span m=''2853710''>hinder</span> <span m=''2853920''>things</span>
  <span m=''2854170''>like</span> <span m=''2854340''>parallelization.</span> <span
  m=''2856500''>When we</span> <span m=''2856740''>get</span> <span m=''2856990''>there,</span>
  <span m=''2857130''>we</span> <span m=''2857210''>can</span> <span m=''2857380''>see</span>
  <span m=''2857530''>that</span> <span m=''2857900''>by</span> <span m=''2858020''>adding</span>
  <span m=''2858410''>additional</span> <span m=''2858790''>dependencies</span> <span
  m=''2859190''>in</span> <span m=''2859590''>there.</span> <span m=''2860050''>So</span>
  <span m=''2860210''>in</span> <span m=''2860310''>here,</span> <span m=''2860590''>what
  are</span> <span m=''2860730''>the</span> <span m=''2861520''>common</span> <span
  m=''2861900''>expressions?</span> <span m=''2870813''>Either</span> <span m=''2871310''>you</span>
  <span m=''2871480''>guys</span> <span m=''2871760''>are</span> <span m=''2871840''>bored,</span>
  <span m=''2872210''>or</span> <span m=''2873300''>this</span> <span m=''2873850''>slide</span>
  <span m=''2874180''>is</span> <span m=''2874310''>way</span> <span m=''2874530''>too</span>
  <span m=''2874810''>hard.</span> <span m=''2875560''>You''re</span> <span m=''2875680''>bored?</span>
  </p><p><span m=''2876340''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''2877640''>PROFESSOR:
  y</span> <span m=''2877780''>plus</span> <span m=''2877930''>1,</span> <span m=''2878200''>OK,</span>
  <span m=''2878450''>good.</span> <span m=''2879000''>So</span> <span m=''2879250''>there''s</span>
  <span m=''2879430''>y</span> <span m=''2879560''>plus</span> <span m=''2879810''>1</span>
  <span m=''2880130''>in here,</span> <span m=''2880630''>and</span> <span m=''2880770''>I</span>
  <span m=''2880840''>can</span> <span m=''2881040''>calculate</span> <span m=''2881450''>it</span>
  <span m=''2881600''>once,</span> <span m=''2882020''>and</span> <span m=''2882210''>then</span>
  <span m=''2882390''>I</span> <span m=''2882470''>can</span> <span m=''2882660''>just</span>
  <span m=''2882830''>do</span> <span m=''2882960''>the</span> <span m=''2883040''>multiplication</span>
  <span m=''2883395''>of</span> <span m=''2883750''>that,</span> <span m=''2884560''>and</span>
  <span m=''2885490''>do</span> <span m=''2885600''>that,</span> <span m=''2885840''>and</span>
  <span m=''2886100''>voila.</span> <span m=''2886360''>It</span> <span m=''2886880''>got</span>
  <span m=''2887120''>rid</span> <span m=''2887220''>of</span> <span m=''2889390''>two</span>
  <span m=''2889570''>addition</span> <span m=''2889910''>and</span> <span m=''2890010''>one</span>
  <span m=''2890140''>multiplication</span> <span m=''2890920''>to one</span> <span
  m=''2891000''>addition</span> <span m=''2891470''>and</span> <span m=''2891580''>one</span>
  <span m=''2891780''>multiplication.</span> </p><p><span m=''2893530''>OK,</span>
  <span m=''2894370''>next</span> <span m=''2894670''>thing</span> <span m=''2894810''>is</span>
  <span m=''2894900''>dead</span> <span m=''2895240''>code</span> <span m=''2895630''>elimination.</span>
  <span m=''2896290''>So</span> <span m=''2896450''>if</span> <span m=''2896560''>you''re</span>
  <span m=''2896860''>doing</span> <span m=''2897190''>something</span> <span m=''2897590''>that</span>
  <span m=''2897800''>nobody''s</span> <span m=''2898330''>using</span> <span m=''2898720''>the</span>
  <span m=''2898810''>value,</span> <span m=''2899150''>why</span> <span m=''2899530''>do</span>
  <span m=''2899620''>you</span> <span m=''2899780''>do</span> <span m=''2899950''>it?</span>
  <span m=''2900560''>And</span> <span m=''2901340''>less</span> <span m=''2901520''>computation,</span>
  <span m=''2902670''>and</span> <span m=''2903640''>maybe</span> <span m=''2903960''>you</span>
  <span m=''2904200''>release</span> <span m=''2904320''>storage</span> <span m=''2904860''>because</span>
  <span m=''2905050''>you''re</span> <span m=''2905170''>not</span> <span m=''2905320''>storing</span>
  <span m=''2905710''>these</span> <span m=''2905910''>values</span> <span m=''2906070''>your</span>
  <span m=''2906390''>computing,</span> <span m=''2907330''>and</span> <span m=''2908430''>that''s</span>
  <span m=''2908660''>really nice.</span> </p><p><span m=''2909510''>And</span> <span
  m=''2910110''>there''s</span> <span m=''2910290''>not</span> <span m=''2910510''>much</span>
  <span m=''2910720''>of</span> <span m=''2911590''>bad</span> <span m=''2911960''>things</span>
  <span m=''2912210''>about</span> <span m=''2912390''>dead</span> <span m=''2912620''>code.</span>
  <span m=''2912740''>Dead</span> <span m=''2912870''>code</span> <span m=''2913210''>is</span>
  <span m=''2913310''>pretty</span> <span m=''2913530''>dead.</span> <span m=''2913860''>You</span>
  <span m=''2913980''>can get</span> <span m=''2914240''>rid</span> <span m=''2914360''>of
  it.</span> <span m=''2915290''>So</span> <span m=''2915450''>here,</span> <span
  m=''2915660''>what</span> <span m=''2915890''>are the</span> <span m=''2915980''>dead
  code</span> <span m=''2916200''>you have?</span> <span m=''2921310''>I</span> <span
  m=''2921410''>want</span> <span m=''2921620''>keep you</span> <span m=''2921880''>at</span>
  <span m=''2922280''>least</span> <span m=''2922840''>somewhat</span> <span m=''2923155''>engaged,</span>
  <span m=''2923910''>so</span> <span m=''2924976''>see</span> <span m=''2925330''>if
  you</span> <span m=''2925570''>can</span> <span m=''2925710''>find</span> <span
  m=''2925970''>my</span> <span m=''2926090''>dead</span> <span m=''2926380''>code.</span>
  </p><p><span m=''2927116''>AUDIENCE: y.</span> </p><p><span m=''2927850''>PROFESSOR:
  y,</span> <span m=''2928230''>yeah.</span> <span m=''2928950''>I</span> <span m=''2929060''>got</span>
  <span m=''2929220''>rid of</span> <span m=''2929500''>[UNINTELLIGIBLE].</span> <span
  m=''2930120''>Now,</span> <span m=''2930290''>I</span> <span m=''2930370''>don''t</span>
  <span m=''2930550''>need</span> <span m=''2930730''>it,</span> <span m=''2930970''>I</span>
  <span m=''2931060''>can just</span> <span m=''2931330''>get</span> <span m=''2931480''>rid</span>
  <span m=''2931570''>of</span> <span m=''2931700''>that,</span> <span m=''2931970''>and</span>
  <span m=''2932170''>then</span> <span m=''2932340''>I</span> <span m=''2932420''>can</span>
  <span m=''2932630''>even</span> <span m=''2932820''>get</span> <span m=''2932970''>rid
  of</span> <span m=''2933040''>allocating</span> <span m=''2933700''>y.</span> <span
  m=''2934420''>So</span> <span m=''2934620''>I</span> <span m=''2934720''>got</span>
  <span m=''2934870''>rid</span> <span m=''2935000''>of</span> <span m=''2935120''>both</span>
  <span m=''2936170''>instruction</span> <span m=''2936830''>and</span> <span m=''2937000''>some</span>
  <span m=''2937190''>memory-allocated</span> <span m=''2938190''>registry</span>
  <span m=''2939000''>that</span> <span m=''2939260''>used</span> <span m=''2939420''>to</span>
  <span m=''2939580''>keep that</span> <span m=''2939700''>value</span> <span m=''2940110''>there.</span>
  </p><p><span m=''2941830''>Another</span> <span m=''2941990''>interesting</span>
  <span m=''2942340''>thing</span> <span m=''2942530''>you can</span> <span m=''2942730''>do</span>
  <span m=''2942900''>is</span> <span m=''2943100''>loop</span> <span m=''2943540''>invariant</span>
  <span m=''2943760''>code</span> <span m=''2944080''>[UNINTELLIGIBLE]</span> <span
  m=''2944330''>because</span> <span m=''2944760''>loops are</span> <span m=''2945110''>very</span>
  <span m=''2945410''>important.</span> <span m=''2946830''>Most</span> <span m=''2947210''>of</span>
  <span m=''2947320''>execution</span> <span m=''2947810''>time</span> <span m=''2948050''>is</span>
  <span m=''2948170''>mainly</span> <span m=''2948540''>inside</span> <span m=''2948710''>loops,</span>
  <span m=''2949250''>so</span> <span m=''2949410''>if</span> <span m=''2949530''>you</span>
  <span m=''2949640''>can</span> <span m=''2949920''>get</span> <span m=''2950140''>something</span>
  <span m=''2950410''>out</span> <span m=''2950540''>of</span> <span m=''2950670''>a</span>
  <span m=''2950710''>loop,</span> <span m=''2950850''>that''s</span> <span m=''2951000''>really</span>
  <span m=''2951330''>good.</span> <span m=''2951580''>We</span> <span m=''2951720''>talked</span>
  <span m=''2951980''>about</span> <span m=''2952210''>that</span> <span m=''2952870''>previously.</span>
  <span m=''2955360''>But</span> <span m=''2955730''>you</span> <span m=''2955960''>have
  to</span> <span m=''2956590''>worry</span> <span m=''2956900''>about,</span> <span
  m=''2957250''>basically,</span> <span m=''2958670''>two</span> <span m=''2958970''>things.</span>
  </p><p><span m=''2960140''>One</span> <span m=''2960430''>thing</span> <span m=''2960640''>is</span>
  <span m=''2961070''>that</span> <span m=''2961690''>when</span> <span m=''2961800''>you</span>
  <span m=''2961940''>move</span> <span m=''2962120''>too many</span> <span m=''2962440''>things</span>
  <span m=''2962650''>out</span> <span m=''2962760''>of</span> <span m=''2962870''>the</span>
  <span m=''2962950''>loops,</span> <span m=''2963220''>you</span> <span m=''2963340''>have</span>
  <span m=''2963410''>to</span> <span m=''2963490''>keep all</span> <span m=''2963960''>those</span>
  <span m=''2964130''>values</span> <span m=''2964500''>in</span> <span m=''2964580''>registers,</span>
  <span m=''2965930''>so</span> <span m=''2966120''>that</span> <span m=''2966310''>means</span>
  <span m=''2966480''>you</span> <span m=''2966830''>need</span> <span m=''2967000''>more</span>
  <span m=''2967170''>registers</span> <span m=''2967360''>inside</span> <span m=''2967580''>the</span>
  <span m=''2967650''>loop.</span> <span m=''2968420''>Second</span> <span m=''2968820''>thing</span>
  <span m=''2969050''>is</span> <span m=''2969510''>when you</span> <span m=''2969750''>execute</span>
  <span m=''2970310''>that,</span> <span m=''2970910''>you have</span> <span m=''2971020''>to</span>
  <span m=''2971120''>make</span> <span m=''2971370''>sure</span> <span m=''2971690''>that</span>
  <span m=''2973350''>it</span> <span m=''2973580''>have</span> <span m=''2973780''>the</span>
  <span m=''2973850''>same</span> <span m=''2974180''>behavior</span> <span m=''2974690''>as</span>
  <span m=''2976270''>when you</span> <span m=''2976770''>run</span> <span m=''2976870''>the</span>
  <span m=''2976970''>program.</span> <span m=''2977750''>How</span> <span m=''2977980''>about</span>
  <span m=''2979000''>special</span> <span m=''2979100''>cases,</span> <span m=''2979530''>the</span>
  <span m=''2979630''>loop</span> <span m=''2979970''>never</span> <span m=''2980330''>get</span>
  <span m=''2980390''>executed.</span> </p><p><span m=''2985380''>First</span> <span
  m=''2985650''>let''s</span> <span m=''2985820''>look</span> <span m=''2985960''>at</span>
  <span m=''2986110''>this.</span> <span m=''2987090''>What</span> <span m=''2987160''>other</span>
  <span m=''2987540''>loop</span> <span m=''2987945''>invariant</span> <span m=''2989050''>expressions</span>
  <span m=''2989540''>in</span> <span m=''2989660''>here?</span> </p><p><span m=''2990360''>AUDIENCE:
  [INAUDIBLE].</span> </p><p><span m=''2991650''>PROFESSOR: Hm?</span> </p><p><span
  m=''2992080''>AUDIENCE: 4</span> <span m=''2992510''>times</span> <span m=''2992940''>[INAUDIBLE]--</span>
  </p><p><span m=''2993120''>PROFESSOR: 4</span> <span m=''2993620''>times</span>
  <span m=''2993900''>eta a</span> <span m=''2993990''>divided</span> <span m=''2994400''>by</span>
  <span m=''2994610''>b.</span> <span m=''2995190''>OK,</span> <span m=''2995460''>good,</span>
  <span m=''2995940''>I just</span> <span m=''2996210''>moved</span> <span m=''2996450''>up</span>
  <span m=''2996630''>there.</span> <span m=''2998370''>So</span> <span m=''2998610''>I</span>
  <span m=''2998690''>did</span> <span m=''2998890''>that,</span> <span m=''3000110''>but</span>
  <span m=''3001120''>why</span> <span m=''3001220''>am</span> <span m=''3001540''>I</span>
  <span m=''3001860''>really</span> <span m=''3001980''>wrong?</span> <span m=''3003210''>Why</span>
  <span m=''3003500''>won''t</span> <span m=''3003910''>the</span> <span m=''3004040''>compiler</span>
  <span m=''3004480''>do</span> <span m=''3004650''>this?</span> <span m=''3007720''>Give</span>
  <span m=''3007890''>me a</span> <span m=''3008220''>case</span> <span m=''3008880''>that</span>
  <span m=''3009320''>this</span> <span m=''3009610''>would</span> <span m=''3009950''>change</span>
  <span m=''3010460''>the</span> <span m=''3011110''>program</span> <span m=''3011370''>behavior.</span>
  </p><p><span m=''3026450''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''3031290''>PROFESSOR:
  4</span> <span m=''3031590''>times</span> <span m=''3031770''>overflow,</span> <span
  m=''3032190''>yeah,</span> <span m=''3032440''>that</span> <span m=''3032630''>can</span>
  <span m=''3032790''>happen.</span> <span m=''3033800''>That''s</span> <span m=''3034040''>one</span>
  <span m=''3034100''>case,</span> <span m=''3034830''>but</span> <span m=''3035880''>there''s</span>
  <span m=''3036070''>something</span> <span m=''3036370''>that</span> <span m=''3036620''>can</span>
  <span m=''3036750''>happen--</span> <span m=''3037890''>overflow</span> <span m=''3038430''>happens</span>
  <span m=''3038670''>in</span> <span m=''3038760''>very</span> <span m=''3039030''>large</span>
  <span m=''3039310''>numbers,</span> <span m=''3039640''>people</span> <span m=''3039890''>don''t</span>
  <span m=''3040080''>care</span> <span m=''3040220''>that</span> <span m=''3040410''>much,</span>
  <span m=''3040850''>but</span> <span m=''3040990''>there''s</span> <span m=''3041130''>something</span>
  <span m=''3041420''>that</span> <span m=''3041590''>can</span> <span m=''3041700''>happen</span>
  <span m=''3042040''>a lot</span> <span m=''3042470''>more.</span> </p><p><span m=''3043374''>AUDIENCE:
  If B is</span> <span m=''3043826''>0,</span> <span m=''3044278''>and then</span>
  <span m=''3044730''>N is</span> <span m=''3045182''>less than</span> <span m=''3045634''>0?</span>
  </p><p><span m=''3046090''>PROFESSOR: Exactly,</span> <span m=''3046920''>when</span>
  <span m=''3047290''>B[0]</span> <span m=''3047980''>and</span> <span m=''3048310''>N
  is</span> <span m=''3048440''>less</span> <span m=''3048660''>than</span> <span
  m=''3049120''>0.</span> <span m=''3049770''>I</span> <span m=''3049870''>am</span>
  <span m=''3050210''>going</span> <span m=''3050670''>to</span> <span m=''3050980''>have</span>
  <span m=''3051150''>a</span> <span m=''3051320''>divide</span> <span m=''3051710''>by</span>
  <span m=''3051860''>0</span> <span m=''3052090''>error</span> <span m=''3052260''>in</span>
  <span m=''3052590''>here</span> <span m=''3054190''>because</span> <span m=''3054700''>I
  am</span> <span m=''3054860''>going</span> <span m=''3055210''>here,</span> <span
  m=''3055260''>dividing</span> <span m=''3055650''>by</span> <span m=''3055830''>0.</span>
  <span m=''3056620''>That</span> <span m=''3056770''>would</span> <span m=''3056920''>have</span>
  <span m=''3057100''>never</span> <span m=''3057330''>happened</span> <span m=''3057810''>because</span>
  <span m=''3058090''>the</span> <span m=''3058250''>loop</span> <span m=''3058460''>wouldn''t</span>
  <span m=''3058970''>have</span> <span m=''3059190''>gone and</span> <span m=''3059330''>executed
  it.</span> </p><p><span m=''3060970''>So</span> <span m=''3062330''>normally,</span>
  <span m=''3062810''>when</span> <span m=''3062940''>you</span> <span m=''3063340''>do</span>
  <span m=''3063640''>things</span> <span m=''3063920''>like</span> <span m=''3064140''>that</span>
  <span m=''3064380''>in</span> <span m=''3064450''>a</span> <span m=''3064520''>loop,</span>
  <span m=''3065090''>the</span> <span m=''3065230''>compiler</span> <span m=''3065800''>generate</span>
  <span m=''3066080''>a</span> <span m=''3066200''>place</span> <span m=''3066480''>called</span>
  <span m=''3066680''>a</span> <span m=''3066810''>landing</span> <span m=''3067340''>pad,</span>
  <span m=''3068380''>which</span> <span m=''3068660''>basically</span> <span m=''3069500''>is,</span>
  <span m=''3071570''>before</span> <span m=''3071900''>you</span> <span m=''3072050''>enter</span>
  <span m=''3072290''>the</span> <span m=''3072390''>loop,</span> <span m=''3072640''>you</span>
  <span m=''3072780''>check</span> <span m=''3073240''>whether</span> <span m=''3073480''>the
  loop</span> <span m=''3073750''>will</span> <span m=''3074020''>ever</span> <span
  m=''3074130''>get</span> <span m=''3074330''>executed.</span> <span m=''3075340''>And</span>
  <span m=''3075590''>then</span> <span m=''3075860''>go</span> <span m=''3076030''>to</span>
  <span m=''3076220''>the</span> <span m=''3076460''>landing</span> <span m=''3076660''>pad,</span>
  <span m=''3077140''>and</span> <span m=''3077330''>then</span> <span m=''3077500''>go</span>
  <span m=''3077650''>to</span> <span m=''3077740''>the</span> <span m=''3077830''>loop.</span>
  <span m=''3078230''>So the</span> <span m=''3078380''>landing</span> <span m=''3078850''>pad</span>
  <span m=''3079280''>will be</span> <span m=''3079550''>run</span> <span m=''3080110''>only</span>
  <span m=''3080570''>when</span> <span m=''3080680''>the</span> <span m=''3080780''>loop</span>
  <span m=''3081060''>at</span> <span m=''3081220''>least</span> <span m=''3081430''>has</span>
  <span m=''3081560''>one</span> <span m=''3081790''>iteration</span> <span m=''3082260''>running,</span>
  <span m=''3083130''>and</span> <span m=''3083440''>so</span> <span m=''3083530''>you</span>
  <span m=''3083750''>can</span> <span m=''3083970''>move all</span> <span m=''3084200''>those</span>
  <span m=''3084380''>thing in the</span> <span m=''3084730''>landing</span> <span
  m=''3085040''>pad.</span> </p><p><span m=''3085230''>So here,</span> <span m=''3085340''>you</span>
  <span m=''3085550''>can</span> <span m=''3085760''>see</span> <span m=''3086010''>there''s</span>
  <span m=''3086230''>no</span> <span m=''3086360''>landing</span> <span m=''3086750''>pad.</span>
  <span m=''3086960''>The</span> <span m=''3087290''>code</span> <span m=''3087530''>generated</span>
  <span m=''3087850''>probably would have,</span> <span m=''3089050''>and</span> <span
  m=''3089200''>so</span> <span m=''3089290''>I</span> <span m=''3089390''>did</span>
  <span m=''3089540''>something</span> <span m=''3089860''>that</span> <span m=''3090935''>is,</span>
  <span m=''3091260''>you</span> <span m=''3091390''>would</span> <span m=''3091550''>see</span>
  <span m=''3092670''>in</span> <span m=''3092830''>fact,</span> <span m=''3093080''>the</span>
  <span m=''3093360''>optimized</span> <span m=''3093800''>code</span> <span m=''3094060''>I
  did</span> <span m=''3094290''>didn''t</span> <span m=''3094570''>do</span> <span
  m=''3094670''>that.</span> <span m=''3095570''>So</span> <span m=''3095770''>GCC</span>
  <span m=''3096670''>minus</span> <span m=''3096940''>[UNINTELLIGIBLE]</span> <span
  m=''3097300''>is</span> <span m=''3097660''>smart</span> <span m=''3098030''>enough</span>
  <span m=''3098120''>not to</span> <span m=''3098375''>do</span> <span m=''3098630''>this.</span>
  </p><p><span m=''3100320''>So</span> <span m=''3100690''>then</span> <span m=''3100880''>there''s</span>
  <span m=''3101360''>another</span> <span m=''3101690''>type</span> <span m=''3101900''>of</span>
  <span m=''3102160''>strength</span> <span m=''3102500''>reduction,</span> <span
  m=''3103180''>which</span> <span m=''3103360''>is</span> <span m=''3103580''>saying</span>
  <span m=''3104500''>if</span> <span m=''3104810''>I</span> <span m=''3104920''>go</span>
  <span m=''3105380''>something</span> <span m=''3105620''>like</span> <span m=''3106040''>a</span>
  <span m=''3106280''>times</span> <span m=''3106763''>i,</span> <span m=''3109180''>what</span>
  <span m=''3109380''>I</span> <span m=''3109590''>can</span> <span m=''3109840''>do</span>
  <span m=''3110170''>is</span> <span m=''3110500''>just,</span> <span m=''3110880''>instead</span>
  <span m=''3111210''>of</span> <span m=''3111340''>doing</span> <span m=''3111550''>a</span>
  <span m=''3111760''>times</span> <span m=''3112235''>i,</span> <span m=''3112710''>I</span>
  <span m=''3112860''>can</span> <span m=''3113140''>basically</span> <span m=''3114460''>make</span>
  <span m=''3115290''>the</span> <span m=''3115620''>first</span> <span m=''3115950''>iteration</span>
  <span m=''3116470''>initialize</span> <span m=''3116770''>it,</span> <span m=''3116920''>and</span>
  <span m=''3117120''>every</span> <span m=''3117400''>time</span> <span m=''3117790''>you</span>
  <span m=''3117930''>can</span> <span m=''3118090''>update</span> <span m=''3118520''>the</span>
  <span m=''3118590''>previous</span> <span m=''3118990''>value.</span> <span m=''3120280''>OK,</span>
  <span m=''3120380''>so</span> <span m=''3120610''>array</span> <span m=''3120820''>times</span>
  <span m=''3121070''>i,</span> <span m=''3121330''>the</span> <span m=''3121520''>first</span>
  <span m=''3121710''>it''s</span> <span m=''3121920''>0</span> <span m=''3122330''>and</span>
  <span m=''3122740''>next</span> <span m=''3122940''>time</span> <span m=''3123330''>it''ll</span>
  <span m=''3123510''>be t plus</span> <span m=''3123740''>80 plus</span> <span m=''3124210''>this,</span>
  <span m=''3124690''>so I can</span> <span m=''3124840''>keep</span> <span m=''3125020''>updating</span>
  <span m=''3125410''>that.</span> <span m=''3126670''>OK,</span> <span m=''3127090''>so</span>
  <span m=''3127200''>this</span> <span m=''3127350''>is</span> <span m=''3127490''>really</span>
  <span m=''3127700''>good.</span> <span m=''3128000''>I have</span> <span m=''3128180''>this</span>
  <span m=''3128340''>computation</span> <span m=''3129670''>because</span> <span
  m=''3130010''>now</span> <span m=''3130460''>we just</span> <span m=''3130560''>sort
  of</span> <span m=''3130710''>multiply,</span> <span m=''3130910''>I</span> <span
  m=''3131100''>just</span> <span m=''3131320''>made it</span> <span m=''3131530''>add.</span>
  <span m=''3132670''>But</span> <span m=''3132950''>I</span> <span m=''3133000''>have</span>
  <span m=''3133200''>a</span> <span m=''3133220''>lot</span> <span m=''3133330''>of</span>
  <span m=''3133440''>problems</span> <span m=''3134020''>that</span> <span m=''3134120''>can</span>
  <span m=''3134660''>happen</span> <span m=''3135040''>here.</span> </p><p><span
  m=''3135160''>First</span> <span m=''3135400''>of</span> <span m=''3135520''>all,</span>
  <span m=''3136330''>I</span> <span m=''3136480''>have,</span> <span m=''3137090''>now,</span>
  <span m=''3137470''>this</span> <span m=''3138000''>one.</span> <span m=''3138200''>I</span>
  <span m=''3138310''>didn''t</span> <span m=''3138430''>have</span> <span m=''3138540''>to</span>
  <span m=''3138660''>keep</span> <span m=''3138930''>this</span> <span m=''3139090''>value</span>
  <span m=''3139560''>anywhere,</span> <span m=''3139920''>only</span> <span m=''3140220''>when</span>
  <span m=''3140600''>I</span> <span m=''3140650''>needed</span> <span m=''3140940''>it.</span>
  <span m=''3141450''>In</span> <span m=''3141700''>here,</span> <span m=''3142510''>this</span>
  <span m=''3142640''>value</span> <span m=''3142900''>has to</span> <span m=''3143090''>be</span>
  <span m=''3143800''>varied</span> <span m=''3144000''>through out</span> <span m=''3144380''>the</span>
  <span m=''3144470''>entire</span> <span m=''3144730''>loop</span> <span m=''3145480''>because</span>
  <span m=''3145720''>I</span> <span m=''3146070''>keep</span> <span m=''3146250''>updating</span>
  <span m=''3146680''>that value,</span> <span m=''3147020''>so</span> <span m=''3147220''>I</span>
  <span m=''3147620''>created</span> <span m=''3147900''>another</span> <span m=''3148300''>need</span>
  <span m=''3148550''>for a</span> <span m=''3148800''>register.</span> <span m=''3150070''>Before</span>
  <span m=''3150350''>now,</span> <span m=''3150430''>I</span> <span m=''3150460''>only</span>
  <span m=''3150700''>needed</span> <span m=''3150960''>it at</span> <span m=''3151070''>that</span>
  <span m=''3151270''>point.</span> <span m=''3151610''>I</span> <span m=''3151650''>could''ve</span>
  <span m=''3151950''>[UNINTELLIGIBLE],</span> <span m=''3152320''>rarely</span> <span
  m=''3152510''>used</span> <span m=''3152780''>it,</span> <span m=''3153100''>but</span>
  <span m=''3153290''>now</span> <span m=''3153460''>it</span> <span m=''3153650''>just</span>
  <span m=''3153840''>to</span> <span m=''3154070''>be</span> <span m=''3154200''>there</span>
  <span m=''3155080''>throughout</span> <span m=''3155390''>the</span> <span m=''3155500''>program</span>
  <span m=''3155930''>I</span> <span m=''3156000''>created</span> <span m=''3157240''>in
  there.</span> </p><p><span m=''3158290''>Also</span> <span m=''3158780''>what</span>
  <span m=''3158930''>I</span> <span m=''3159080''>fear</span> <span m=''3159410''>is</span>
  <span m=''3159570''>what</span> <span m=''3159740''>they</span> <span m=''3159860''>call</span>
  <span m=''3160150''>a</span> <span m=''3160400''>loop-carried</span> <span m=''3160660''>dependence.</span>
  <span m=''3161260''>Every</span> <span m=''3161600''>time</span> <span m=''3161810''>you</span>
  <span m=''3161900''>run</span> <span m=''3162090''>iteration,</span> <span m=''3162610''>you</span>
  <span m=''3162820''>use</span> <span m=''3163010''>the</span> <span m=''3163090''>previous</span>
  <span m=''3163490''>iteration''s</span> <span m=''3164020''>value.</span> <span
  m=''3164710''>When</span> <span m=''3165110''>we</span> <span m=''3165450''>go</span>
  <span m=''3165830''>into</span> <span m=''3166470''>a</span> <span m=''3166810''>parallelizing</span>
  <span m=''3167280''>loop,</span> <span m=''3167670''>you</span> <span m=''3167840''>suddenly</span>
  <span m=''3168130''>realize</span> <span m=''3168530''>that</span> <span m=''3168670''>means</span>
  <span m=''3168880''>I can''t</span> <span m=''3169260''>run</span> <span m=''3169420''>them</span>
  <span m=''3169500''>parallel,</span> <span m=''3170100''>so</span> <span m=''3170200''>this</span>
  <span m=''3170490''>creates</span> <span m=''3170690''>a</span> <span m=''3170930''>huge</span>
  <span m=''3171250''>problem</span> <span m=''3171620''>in</span> <span m=''3171730''>parallelization.</span>
  <span m=''3172760''>So</span> <span m=''3173260''>you</span> <span m=''3173390''>do</span>
  <span m=''3174170''>[UNINTELLIGIBLE],</span> <span m=''3175360''>strength</span>
  <span m=''3175780''>increase,</span> <span m=''3176400''>when</span> <span m=''3176530''>you</span>
  <span m=''3176640''>go</span> <span m=''3176770''>to</span> <span m=''3176840''>parallelize.</span>
  <span m=''3177280''>And you</span> <span m=''3177650''>can</span> <span m=''3177910''>undo</span>
  <span m=''3177980''>these</span> <span m=''3178470''>things.</span> </p><p><span
  m=''3179450''>So</span> <span m=''3179620''>in here,</span> <span m=''3180580''>one</span>
  <span m=''3180750''>thing</span> <span m=''3180850''>you</span> <span m=''3181010''>can</span>
  <span m=''3181180''>do</span> <span m=''3181370''>is</span> <span m=''3181850''>you</span>
  <span m=''3182105''>look</span> <span m=''3182360''>at</span> <span m=''3182670''>something</span>
  <span m=''3182890''>like</span> <span m=''3183040''>u</span> <span m=''3183210''>times</span>
  <span m=''3183460''>i</span> <span m=''3183940''>and say</span> <span m=''3184100''>wait
  a</span> <span m=''3184290''>minute,</span> <span m=''3184440''>I</span> <span m=''3184480''>don''t</span>
  <span m=''3184620''>have</span> <span m=''3184710''>to</span> <span m=''3184780''>multiply</span>
  <span m=''3185170''>by</span> <span m=''3185400''>i</span> <span m=''3186320''>because</span>
  <span m=''3186660''>it</span> <span m=''3186780''>[UNINTELLIGIBLE]</span> <span
  m=''3187170''>0</span> <span m=''3187640''>like</span> <span m=''3187910''>this,</span>
  <span m=''3188540''>and</span> <span m=''3189160''>I</span> <span m=''3189320''>can</span>
  <span m=''3189540''>just</span> <span m=''3190030''>allocate</span> <span m=''3190450''>a</span>
  <span m=''3190490''>value</span> <span m=''3190750''>b</span> <span m=''3191050''>and</span>
  <span m=''3191170''>keep</span> <span m=''3191390''>it</span> <span m=''3192220''>updating</span>
  <span m=''3192600''>by</span> <span m=''3192720''>v,</span> <span m=''3193060''>and</span>
  <span m=''3193230''>then</span> <span m=''3193400''>I</span> <span m=''3193460''>did</span>
  <span m=''3193780''>that,</span> <span m=''3194330''>allocated</span> <span m=''3194810''>a</span>
  <span m=''3194900''>variable</span> <span m=''3195540''>in</span> <span m=''3195810''>here,</span>
  <span m=''3195870''>allocated</span> <span m=''3196370''>0.</span> <span m=''3197210''>And</span>
  <span m=''3198040''>[UNINTELLIGIBLE]</span> <span m=''3198250''>this,</span> <span
  m=''3198450''>I</span> <span m=''3198680''>just</span> <span m=''3198880''>basically</span>
  <span m=''3199170''>put</span> <span m=''3199780''>v times</span> <span m=''3199930''>0.</span>
  <span m=''3200960''>You</span> <span m=''3201090''>see</span> <span m=''3201200''>that?</span>
  <span m=''3202240''>I</span> <span m=''3202430''>just</span> <span m=''3202610''>basically</span>
  <span m=''3202960''>got</span> <span m=''3203080''>rid</span> <span m=''3203210''>of
  a</span> <span m=''3203440''>multiplication</span> <span m=''3204450''>and</span>
  <span m=''3204580''>convert</span> <span m=''3204750''>it into</span> <span m=''3204920''>addition,</span>
  <span m=''3205910''>but</span> <span m=''3206460''>I</span> <span m=''3206670''>paid</span>
  <span m=''3206990''>some</span> <span m=''3207200''>cost</span> <span m=''3207560''>by,</span>
  <span m=''3207990''>I</span> <span m=''3208140''>need</span> <span m=''3208480''>now</span>
  <span m=''3208830''>this</span> <span m=''3208990''>additional</span> <span m=''3209380''>register</span>
  <span m=''3209880''>that</span> <span m=''3210080''>is</span> <span m=''3210645''>true</span>
  <span m=''3211030''>all</span> <span m=''3211415''>throughout the</span> <span m=''3211800''>entire
  thing.</span> <span m=''3212390''>[UNINTELLIGIBLE]</span> <span m=''3213320''>I</span>
  <span m=''3213370''>just</span> <span m=''3213690''>calculated</span> <span m=''3214030''>that</span>
  <span m=''3214190''>expression.</span> </p><p><span m=''3217660''>And</span> <span
  m=''3218540''>the</span> <span m=''3218620''>big</span> <span m=''3218970''>thing</span>
  <span m=''3219200''>a lot</span> <span m=''3219930''>you</span> <span m=''3220440''>get</span>
  <span m=''3220740''>performances</span> <span m=''3221350''>register</span> <span
  m=''3221650''>allocation,</span> <span m=''3222110''>so</span> <span m=''3222810''>most</span>
  <span m=''3223150''>processes</span> <span m=''3223435''>have</span> <span m=''3223720''>very
  few</span> <span m=''3224000''>registers.</span> <span m=''3225030''>In</span> <span
  m=''3225200''>fact,</span> <span m=''3225440''>one</span> <span m=''3225730''>big</span>
  <span m=''3226045''>change</span> <span m=''3226360''>that</span> <span m=''3226520''>when</span>
  <span m=''3226690''>you</span> <span m=''3226900''>went</span> <span m=''3227050''>from</span>
  <span m=''3227160''>[UNINTELLIGIBLE]</span> <span m=''3228930''>is</span> <span
  m=''3229020''>to</span> <span m=''3229120''>get</span> <span m=''3229280''>additional</span>
  <span m=''3229630''>registers.</span> <span m=''3230190''>Registers</span> <span
  m=''3230620''>are</span> <span m=''3230760''>very</span> <span m=''3230930''>important.</span>
  </p><p><span m=''3235740''>I</span> <span m=''3235880''>will</span> <span m=''3236060''>go</span>
  <span m=''3236300''>through</span> <span m=''3236430''>register</span> <span m=''3236760''>location</span>
  <span m=''3237370''>a</span> <span m=''3237450''>little</span> <span m=''3237780''>bit.</span>
  <span m=''3238340''>So</span> <span m=''3238510''>what</span> <span m=''3238730''>happens</span>
  <span m=''3239110''>is</span> <span m=''3239730''>when</span> <span m=''3240130''>you</span>
  <span m=''3240210''>have a</span> <span m=''3240490''>program,</span> <span m=''3240940''>you
  have</span> <span m=''3241405''>a</span> <span m=''3241870''>control</span> <span
  m=''3242480''>goes</span> <span m=''3242590''>like</span> <span m=''3242770''>this.</span>
  <span m=''3242920''>So</span> <span m=''3243030''>this</span> <span m=''3243270''>control</span>
  <span m=''3243620''>going,</span> <span m=''3244100''>executing</span> <span m=''3244760''>something</span>
  <span m=''3245060''>that</span> <span m=''3245300''>defines</span> <span m=''3246170''>this</span>
  <span m=''3246390''>variable</span> <span m=''3246800''>x,</span> <span m=''3247650''>defines</span>
  <span m=''3247950''>variable</span> <span m=''3248500''>y.</span> <span m=''3248840''>And</span>
  <span m=''3249020''>here,</span> <span m=''3249270''>you</span> <span m=''3249580''>use</span>
  <span m=''3249880''>variable</span> <span m=''3250300''>x</span> <span m=''3250580''>and
  variable</span> <span m=''3251060''>y,</span> <span m=''3251770''>and</span> <span
  m=''3251970''>there</span> <span m=''3252110''>are</span> <span m=''3252210''>different</span>
  <span m=''3252550''>paths</span> <span m=''3252880''>the</span> <span m=''3252960''>program</span>
  <span m=''3253340''>can</span> <span m=''3253560''>go</span> <span m=''3253700''>through.</span>
  <span m=''3253790''>There are</span> <span m=''3254010''>two</span> <span m=''3254430''>paths</span>
  <span m=''3254850''>can</span> <span m=''3255070''>merge</span> <span m=''3255360''>in</span>
  <span m=''3255450''>here,</span> <span m=''3255650''>here,</span> <span m=''3255860''>you</span>
  <span m=''3256110''>can</span> <span m=''3256370''>expand in</span> <span m=''3256770''>here.</span>
  </p><p><span m=''3257730''>So</span> <span m=''3258100''>this</span> <span m=''3258270''>is</span>
  <span m=''3258360''>kind</span> <span m=''3258490''>of</span> <span m=''3258630''>the</span>
  <span m=''3259100''>flow</span> <span m=''3259460''>of</span> <span m=''3259550''>the</span>
  <span m=''3259640''>program</span> <span m=''3260080''>in</span> <span m=''3260150''>a</span>
  <span m=''3260230''>small</span> <span m=''3260550''>part.</span> <span m=''3261220''>So</span>
  <span m=''3261370''>what</span> <span m=''3261550''>you</span> <span m=''3261610''>can</span>
  <span m=''3261810''>say is</span> <span m=''3262140''>this</span> <span m=''3262370''>definition</span>
  <span m=''3262910''>[UNINTELLIGIBLE]</span> <span m=''3263540''>here,</span> <span
  m=''3264320''>so</span> <span m=''3264480''>this</span> <span m=''3264770''>value,</span>
  <span m=''3265080''>this</span> <span m=''3265390''>line</span> <span m=''3265680''>in</span>
  <span m=''3265970''>between</span> <span m=''3266430''>here--</span> <span m=''3267610''>because</span>
  <span m=''3267810''>you</span> <span m=''3267910''>can''t</span> <span m=''3268120''>get</span>
  <span m=''3268220''>rid</span> <span m=''3268330''>of it.</span> <span m=''3268610''>When</span>
  <span m=''3268750''>you</span> <span m=''3268840''>decided</span> <span m=''3269250''>you
  had to</span> <span m=''3269420''>keep it</span> <span m=''3269720''>somewhere</span>
  <span m=''3270160''>because</span> <span m=''3270420''>somebody''s going to</span>
  <span m=''3270560''>[UNINTELLIGIBLE].</span> <span m=''3272310''>And</span> <span
  m=''3272650''>this</span> <span m=''3272830''>definition</span> <span m=''3273370''>is</span>
  <span m=''3273800''>used</span> <span m=''3274080''>here,</span> <span m=''3274320''>so</span>
  <span m=''3274460''>when</span> <span m=''3274610''>you</span> <span m=''3274690''>decided</span>
  <span m=''3275140''>you</span> <span m=''3275220''>had</span> <span m=''3275310''>to</span>
  <span m=''3275400''>be</span> <span m=''3275890''>[UNINTELLIGIBLE]</span> <span
  m=''3276200''>in</span> <span m=''3276510''>here.</span> <span m=''3277650''>When</span>
  <span m=''3277810''>you</span> <span m=''3278315''>[UNINTELLIGIBLE]</span> <span
  m=''3279290''>is only</span> <span m=''3279570''>used</span> <span m=''3279830''>here.</span>
  <span m=''3280060''>Nobody</span> <span m=''3280420''>uses</span> <span m=''3280660''>here,</span>
  <span m=''3281300''>so</span> <span m=''3281530''>this</span> <span m=''3281720''>has</span>
  <span m=''3281880''>to</span> <span m=''3281960''>be</span> <span m=''3282070''>[UNINTELLIGIBLE].</span>
  </p><p><span m=''3283670''>Interesting</span> <span m=''3284060''>thing</span> <span
  m=''3284230''>about</span> <span m=''3284270''>x</span> <span m=''3284770''>is</span>
  <span m=''3285090''>there</span> <span m=''3285240''>are</span> <span m=''3285280''>two</span>
  <span m=''3285580''>definitions</span> <span m=''3286060''>of</span> <span m=''3286430''>x</span>
  <span m=''3286670''>that</span> <span m=''3286880''>might</span> <span m=''3287100''>be</span>
  <span m=''3287180''>used</span> <span m=''3287510''>here,</span> <span m=''3288100''>and</span>
  <span m=''3288390''>this</span> <span m=''3288570''>definition</span> <span m=''3289080''>might
  be</span> <span m=''3289220''>used</span> <span m=''3289590''>here</span> <span
  m=''3289820''>or</span> <span m=''3290000''>here.</span> <span m=''3290360''>So</span>
  <span m=''3290690''>you</span> <span m=''3291375''>put</span> <span m=''3291680''>all</span>
  <span m=''3291980''>this</span> <span m=''3292230''>into</span> <span m=''3292480''>what</span>
  <span m=''3292690''>they</span> <span m=''3292790''>call</span> <span m=''3292950''>a</span>
  <span m=''3293090''>one</span> <span m=''3294445''>web</span> <span m=''3295620''>because</span>
  <span m=''3296230''>these</span> <span m=''3296690''>two</span> <span m=''3296850''>definitions</span>
  <span m=''3297340''>might--</span> <span m=''3297730''>either</span> <span m=''3297800''>one</span>
  <span m=''3297950''>of them</span> <span m=''3298110''>will be</span> <span m=''3298250''>used</span>
  <span m=''3298560''>here.</span> <span m=''3299100''>This</span> <span m=''3299300''>definition</span>
  <span m=''3299760''>will be</span> <span m=''3300020''>used,</span> <span m=''3300210''>either</span>
  <span m=''3300490''>one,</span> <span m=''3300680''>over</span> <span m=''3300850''>here,</span>
  <span m=''3301130''>so</span> <span m=''3301290''>this</span> <span m=''3302070''>value</span>
  <span m=''3302310''>has to</span> <span m=''3302540''>be</span> <span m=''3302720''>[UNINTELLIGIBLE]</span>
  <span m=''3302980''>in</span> <span m=''3303170''>here,</span> <span m=''3303460''>kept</span>
  <span m=''3303810''>somewhere.</span> </p><p><span m=''3305340''>So</span> <span
  m=''3305480''>then</span> <span m=''3305830''>what</span> <span m=''3306000''>we</span>
  <span m=''3306140''>say</span> <span m=''3306590''>is</span> <span m=''3309290''>we
  give</span> <span m=''3309650''>names</span> <span m=''3310030''>to these,</span>
  <span m=''3310430''>so</span> <span m=''3310600''>this is</span> <span m=''3310860''>s1,</span>
  <span m=''3311630''>s2.</span> <span m=''3312610''>Somebody</span> <span m=''3312930''>has
  to</span> <span m=''3313070''>keep</span> <span m=''3313270''>this</span> <span
  m=''3313450''>value.</span> <span m=''3314100''>s2</span> <span m=''3314450''>keeps</span>
  <span m=''3314680''>this</span> <span m=''3314860''>value,</span> <span m=''3315220''>s3
  keeps</span> <span m=''3315500''>this</span> <span m=''3315660''>value,</span> <span
  m=''3315820''>s4</span> <span m=''3316030''>keeps</span> <span m=''3316260''>this</span>
  <span m=''3316410''>value.</span> </p><p><span m=''3317390''>The</span> <span m=''3317490''>interesting</span>
  <span m=''3317870''>thing</span> <span m=''3318090''>is</span> <span m=''3318920''>how</span>
  <span m=''3319190''>many</span> <span m=''3319460''>registers</span> <span m=''3319860''>you</span>
  <span m=''3320100''>need</span> <span m=''3320750''>to</span> <span m=''3321040''>keep</span>
  <span m=''3321330''>all</span> <span m=''3321370''>those</span> <span m=''3321560''>values.</span>
  <span m=''3323110''>That''s</span> <span m=''3323510''>why</span> <span m=''3323630''>the
  entire</span> <span m=''3324130''>thing</span> <span m=''3324260''>of register</span>
  <span m=''3324440''>allocation.</span> <span m=''3325700''>So</span> <span m=''3325800''>what</span>
  <span m=''3326040''>you</span> <span m=''3326160''>do</span> <span m=''3326320''>is</span>
  <span m=''3326500''>this</span> <span m=''3326780''>really</span> <span m=''3327990''>cute</span>
  <span m=''3328340''>mapping</span> <span m=''3328770''>of</span> <span m=''3328990''>this</span>
  <span m=''3329460''>into</span> <span m=''3329760''>nice</span> <span m=''3330430''>theoretical</span>
  <span m=''3331050''>problem.</span> <span m=''3331900''>So</span> <span m=''3332040''>what</span>
  <span m=''3332220''>you</span> <span m=''3332390''>can</span> <span m=''3332560''>say</span>
  <span m=''3332870''>is</span> <span m=''3333610''>each</span> <span m=''3333980''>of</span>
  <span m=''3334120''>these</span> <span m=''3334430''>regions,</span> <span m=''3335070''>we</span>
  <span m=''3335530''>make</span> <span m=''3335890''>it</span> <span m=''3336800''>vertex</span>
  <span m=''3337320''>of a</span> <span m=''3337440''>graph.</span> <span m=''3340680''>If</span>
  <span m=''3341410''>these</span> <span m=''3341610''>regions</span> <span m=''3342170''>overlap,</span>
  <span m=''3343000''>then</span> <span m=''3343230''>we</span> <span m=''3343350''>get</span>
  <span m=''3343620''>edge.</span> </p><p><span m=''3344450''>S1</span> <span m=''3344980''>and</span>
  <span m=''3345120''>s2</span> <span m=''3345380''>overlap.</span> <span m=''3347620''>That</span>
  <span m=''3347920''>means</span> <span m=''3348120''>you</span> <span m=''3348300''>can''t</span>
  <span m=''3348620''>use</span> <span m=''3348810''>the</span> <span m=''3348920''>same</span>
  <span m=''3349390''>register</span> <span m=''3350060''>to</span> <span m=''3350300''>keep</span>
  <span m=''3350860''>s1</span> <span m=''3351060''>one</span> <span m=''3351250''>and</span>
  <span m=''3351370''>s2</span> <span m=''3352500''>because</span> <span m=''3353880''>before</span>
  <span m=''3354000''>s1</span> <span m=''3355160''>is</span> <span m=''3355310''>finished</span>
  <span m=''3355710''>using,</span> <span m=''3356090''>s2</span> <span m=''3356420''>has</span>
  <span m=''3356580''>to</span> <span m=''3356650''>be</span> <span m=''3356750''>free
  of</span> <span m=''3357050''>that.</span> <span m=''3357905''>OK,</span> <span
  m=''3358340''>there''s</span> <span m=''3358500''>overlap</span> <span m=''3358710''>in</span>
  <span m=''3358950''>here,</span> <span m=''3359430''>so</span> <span m=''3359610''>we''ve</span>
  <span m=''3359820''>created</span> <span m=''3360080''>edge in</span> <span m=''3360340''>here.</span>
  </p><p><span m=''3362400''>OK,</span> <span m=''3363090''>s2 and</span> <span m=''3363380''>s3.</span>
  <span m=''3364350''>So</span> <span m=''3364610''>s2 and</span> <span m=''3364770''>s3</span>
  <span m=''3365450''>overlaps</span> <span m=''3365700''>here</span> <span m=''3366190''>because</span>
  <span m=''3366510''>at</span> <span m=''3366660''>this</span> <span m=''3366900''>point,</span>
  <span m=''3367230''>both</span> <span m=''3367530''>value</span> <span m=''3367990''>s2
  and</span> <span m=''3368200''>s3</span> <span m=''3368630''>has to</span> <span
  m=''3368790''>be kept.</span> <span m=''3369520''>So</span> <span m=''3369670''>I
  create</span> <span m=''3370080''>an edge</span> <span m=''3370405''>in here.</span>
  </p><p><span m=''3372270''>OK,</span> <span m=''3372420''>so I</span> <span m=''3372610''>create</span>
  <span m=''3372710''>an</span> <span m=''3372870''>edge.</span> <span m=''3373550''>Every</span>
  <span m=''3373840''>time</span> <span m=''3374140''>I</span> <span m=''3374230''>say</span>
  <span m=''3374510''>those</span> <span m=''3374820''>do</span> <span m=''3375170''>values</span>
  <span m=''3375370''>need</span> <span m=''3375950''>separate</span> <span m=''3376320''>registers.</span>
  <span m=''3377220''>I</span> <span m=''3377310''>can''t</span> <span m=''3377580''>keep</span>
  <span m=''3377870''>the same</span> <span m=''3378110''>register.</span> </p><p><span
  m=''3379020''>And</span> <span m=''3379290''>of</span> <span m=''3379440''>course,</span>
  <span m=''3379710''>s3</span> <span m=''3379920''>and</span> <span m=''3380250''>s4.</span>
  <span m=''3380800''>s3</span> <span m=''3381350''>is here.</span> <span m=''3382210''>s4</span>
  <span m=''3383160''>can be</span> <span m=''3383530''>in the same</span> <span m=''3383795''>register.</span>
  <span m=''3386150''>So</span> <span m=''3386290''>there''s</span> <span m=''3386520''>no</span>
  <span m=''3386590''>edge</span> <span m=''3386690''>here.</span> </p><p><span m=''3387320''>os1</span>
  <span m=''3387850''>and</span> <span m=''3387970''>s4</span> <span m=''3388300''>can</span>
  <span m=''3388500''>be</span> <span m=''3388620''>in the</span> <span m=''3388710''>same</span>
  <span m=''3389100''>register.</span> <span m=''3389520''>os2</span> <span m=''3389950''>and</span>
  <span m=''3390040''>s4</span> <span m=''3390210''>can be</span> <span m=''3390470''>in</span>
  <span m=''3390670''>the</span> <span m=''3390720''>same</span> <span m=''3390920''>register</span>
  <span m=''3392780''>because</span> <span m=''3393060''>they</span> <span m=''3393130''>are
  not</span> <span m=''3393260''>live</span> <span m=''3393710''>at</span> <span m=''3393830''>the</span>
  <span m=''3393900''>same</span> <span m=''3394210''>time.</span> <span m=''3395430''>They
  are</span> <span m=''3395570''>live</span> <span m=''3395820''>at</span> <span m=''3395940''>a</span>
  <span m=''3396060''>different</span> <span m=''3396460''>time</span> <span m=''3396800''>of</span>
  <span m=''3396970''>the</span> <span m=''3397050''>program</span> <span m=''3397380''>execution.</span>
  </p><p><span m=''3398950''>Now,</span> <span m=''3399630''>what</span> <span m=''3399910''>you</span>
  <span m=''3400200''>can</span> <span m=''3400440''>do</span> <span m=''3400650''>is,</span>
  <span m=''3401930''>you have</span> <span m=''3401970''>a</span> <span m=''3402090''>graph,</span>
  <span m=''3402810''>you</span> <span m=''3403020''>have</span> <span m=''3403180''>edges,</span>
  <span m=''3403900''>and</span> <span m=''3404070''>there''s</span> <span m=''3404330''>this</span>
  <span m=''3404660''>very</span> <span m=''3404840''>famous</span> <span m=''3405240''>problem</span>
  <span m=''3405495''>called</span> <span m=''3405750''>graph</span> <span m=''3406160''>coloring</span>
  <span m=''3406500''>problem.</span> <span m=''3406775''>How many</span> <span m=''3407050''>heard</span>
  <span m=''3407300''>of</span> <span m=''3407460''>graph</span> <span m=''3407720''>coloring</span>
  <span m=''3408060''>problem?</span> <span m=''3409520''>OK,</span> <span m=''3409750''>good.</span>
  <span m=''3410380''>So</span> <span m=''3411180''>what</span> <span m=''3411350''>happens</span>
  <span m=''3411710''>is</span> <span m=''3411830''>now</span> <span m=''3412020''>we</span>
  <span m=''3412150''>can</span> <span m=''3412330''>figure</span> <span m=''3412630''>out</span>
  <span m=''3412720''>how</span> <span m=''3412940''>many</span> <span m=''3413170''>colors</span>
  <span m=''3413420''>need</span> <span m=''3413710''>to</span> <span m=''3413790''>color</span>
  <span m=''3414040''>this</span> <span m=''3414220''>graph,</span> <span m=''3414890''>and</span>
  <span m=''3415100''>that</span> <span m=''3415300''>is</span> <span m=''3415510''>the</span>
  <span m=''3415610''>number</span> <span m=''3415910''>of</span> <span m=''3416000''>colors</span>
  <span m=''3416360''>of</span> <span m=''3416420''>the</span> <span m=''3416500''>number</span>
  <span m=''3416760''>of</span> <span m=''3416840''>registers</span> <span m=''3417290''>you</span>
  <span m=''3417390''>need.</span> </p><p><span m=''3418220''>So</span> <span m=''3418400''>if</span>
  <span m=''3418550''>you</span> <span m=''3418710''>have</span> <span m=''3419080''>a</span>
  <span m=''3422170''>graph</span> <span m=''3422500''>like</span> <span m=''3422680''>this</span>
  <span m=''3422860''>with</span> <span m=''3423030''>no</span> <span m=''3423180''>edges,</span>
  <span m=''3424400''>you</span> <span m=''3424510''>can</span> <span m=''3424710''>color</span>
  <span m=''3425020''>it</span> <span m=''3425160''>with one</span> <span m=''3425350''>color.</span>
  <span m=''3427430''>How</span> <span m=''3427590''>many</span> <span m=''3427750''>colors</span>
  <span m=''3428040''>for</span> <span m=''3428110''>this</span> <span m=''3428300''>one?</span>
  <span m=''3429816''>Two</span> <span m=''3430260''>colors.</span> <span m=''3431500''>How</span>
  <span m=''3431640''>many</span> <span m=''3431820''>colors</span> <span m=''3432000''>for</span>
  <span m=''3432100''>this</span> <span m=''3432330''>one?</span> <span m=''3435280''>People</span>
  <span m=''3435490''>said</span> <span m=''3435700''>two</span> <span m=''3435850''>colors.</span>
  <span m=''3436040''>Yes,</span> <span m=''3436240''>you</span> <span m=''3436340''>can</span>
  <span m=''3436490''>color</span> <span m=''3436650''>it with</span> <span m=''3436800''>two</span>
  <span m=''3437100''>colors.</span> <span m=''3437440''>How</span> <span m=''3437560''>many</span>
  <span m=''3437710''>colors</span> <span m=''3437950''>for</span> <span m=''3438020''>this</span>
  <span m=''3438220''>one?</span> </p><p><span m=''3441780''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''3443700''>PROFESSOR: It''s</span> <span m=''3444190''>three-color</span>
  <span m=''3444480''>[UNINTELLIGIBLE].</span> <span m=''3445720''>So</span> <span
  m=''3446270''>there''s</span> <span m=''3446510''>all</span> <span m=''3446640''>these</span>
  <span m=''3446770''>algorithms</span> <span m=''3447030''>[UNINTELLIGIBLE]</span>
  <span m=''3447940''>and</span> <span m=''3448100''>say</span> <span m=''3448460''>no.</span>
  <span m=''3448820''>You can</span> <span m=''3448940''>see</span> <span m=''3449050''>by</span>
  <span m=''3449310''>coloring</span> <span m=''3449740''>this</span> <span m=''3449930''>how
  many</span> <span m=''3450200''>registers</span> <span m=''3450330''>I</span> <span
  m=''3450810''>need.</span> <span m=''3452090''>And the</span> <span m=''3452530''>interesting</span>
  <span m=''3453080''>is,</span> <span m=''3453380''>if</span> <span m=''3453550''>you</span>
  <span m=''3453660''>need</span> <span m=''3453900''>more</span> <span m=''3454100''>colors</span>
  <span m=''3455500''>than</span> <span m=''3455990''>the</span> <span m=''3456220''>register</span>
  <span m=''3456370''>you</span> <span m=''3456490''>have,</span> <span m=''3456700''>that</span>
  <span m=''3456890''>means</span> <span m=''3457050''>you can''t</span> <span m=''3457160''>register</span>
  <span m=''3457290''>allocate,</span> <span m=''3459040''>and</span> <span m=''3459210''>at
  that</span> <span m=''3459580''>point,</span> <span m=''3459770''>you</span> <span
  m=''3460230''>need</span> <span m=''3460460''>too</span> <span m=''3460570''>many</span>
  <span m=''3460750''>things</span> <span m=''3460960''>to</span> <span m=''3461060''>keep.</span>
  <span m=''3461380''>You don''t</span> <span m=''3461640''>have</span> <span m=''3461730''>that
  many</span> <span m=''3461820''>registers</span> <span m=''3462150''>and</span>
  <span m=''3462320''>that</span> <span m=''3462740''>[UNINTELLIGIBLE].</span> </p><p><span
  m=''3464790''>That</span> <span m=''3464890''>means</span> <span m=''3465100''>you</span>
  <span m=''3465210''>take</span> <span m=''3465460''>edge</span> <span m=''3465700''>and</span>
  <span m=''3465840''>say,</span> <span m=''3465980''>ah-hah,</span> <span m=''3466420''>I</span>
  <span m=''3466530''>can''t</span> <span m=''3466890''>keep</span> <span m=''3467390''>both</span>
  <span m=''3467790''>of</span> <span m=''3467940''>these</span> <span m=''3468160''>guys</span>
  <span m=''3468430''>in</span> <span m=''3468520''>the</span> <span m=''3468590''>same.</span>
  <span m=''3468940''>I</span> <span m=''3469070''>will</span> <span m=''3469200''>take</span>
  <span m=''3471660''>some</span> <span m=''3472100''>vertex</span> <span m=''3472570''>out
  and</span> <span m=''3472680''>say this</span> <span m=''3472790''>vertex</span>
  <span m=''3472940''>can''t</span> <span m=''3473110''>be in</span> <span m=''3473600''>there</span>
  <span m=''3473770''>because</span> <span m=''3474030''>I</span> <span m=''3474100''>can''t
  put</span> <span m=''3474380''>it into</span> <span m=''3474790''>register,</span>
  <span m=''3475120''>and</span> <span m=''3475340''>I</span> <span m=''3475390''>spill</span>
  <span m=''3475620''>this</span> <span m=''3475980''>out.</span> <span m=''3476500''>And</span>
  <span m=''3476650''>you</span> <span m=''3476730''>can</span> <span m=''3476850''>re-color</span>
  <span m=''3477270''>the</span> <span m=''3477340''>graphs.</span> </p><p><span m=''3477550''>You</span>
  <span m=''3477710''>can</span> <span m=''3478230''>spill it,</span> <span m=''3478690''>and</span>
  <span m=''3478860''>of</span> <span m=''3479000''>course,</span> <span m=''3479230''>spilling
  is</span> <span m=''3479580''>costly</span> <span m=''3479960''>because</span> <span
  m=''3480200''>now</span> <span m=''3480650''>[UNINTELLIGIBLE]</span> <span m=''3480870''>value</span>
  <span m=''3481130''>in the</span> <span m=''3481300''>register,</span> <span m=''3481920''>it''s</span>
  <span m=''3482170''>in</span> <span m=''3482250''>the</span> <span m=''3482470''>memory,</span>
  <span m=''3483260''>so</span> <span m=''3483390''>every time</span> <span m=''3483610''>you
  need</span> <span m=''3483680''>it,</span> <span m=''3484080''>you had to</span>
  <span m=''3484300''>bring</span> <span m=''3484470''>it</span> <span m=''3484570''>back,</span>
  <span m=''3486240''>send</span> <span m=''3486400''>it</span> <span m=''3486500''>back,</span>
  <span m=''3486740''>so</span> <span m=''3486840''>it''s</span> <span m=''3487000''>going
  to</span> <span m=''3487160''>be</span> <span m=''3487240''>expensive.</span> <span
  m=''3488110''>The</span> <span m=''3488240''>nice</span> <span m=''3488560''>thing</span>
  <span m=''3488730''>is</span> <span m=''3488840''>to</span> <span m=''3488950''>see</span>
  <span m=''3489400''>how</span> <span m=''3489590''>much</span> <span m=''3489810''>you</span>
  <span m=''3489890''>can</span> <span m=''3490040''>keep</span> <span m=''3490240''>in
  the</span> <span m=''3490585''>register.</span> </p><p><span m=''3492800''>So</span>
  <span m=''3492950''>I</span> <span m=''3493060''>have</span> <span m=''3493230''>enough</span>
  <span m=''3493470''>registers</span> <span m=''3493930''>for</span> <span m=''3494000''>this</span>
  <span m=''3494170''>program,</span> <span m=''3494620''>so</span> <span m=''3494730''>I</span>
  <span m=''3494810''>found</span> <span m=''3495230''>registers</span> <span m=''3495450''>for</span>
  <span m=''3495610''>all these</span> <span m=''3495970''>things</span> <span m=''3496330''>instead
  of</span> <span m=''3496510''>putting</span> <span m=''3496910''>it</span> <span
  m=''3497010''>in</span> <span m=''3497120''>memory.</span> <span m=''3498260''>And</span>
  <span m=''3498660''>now,</span> <span m=''3499060''>this</span> <span m=''3499190''>is</span>
  <span m=''3499670''>[UNINTELLIGIBLE]</span> <span m=''3500120''>register</span>
  <span m=''3500380''>allocation</span> <span m=''3501290''>in</span> <span m=''3501520''>a</span>
  <span m=''3502140''>pseudo</span> <span m=''3502300''>C</span> <span m=''3502500''>code,</span>
  <span m=''3503250''>so</span> <span m=''3503630''>this</span> <span m=''3503840''>is</span>
  <span m=''3503970''>the</span> <span m=''3504080''>kind of</span> <span m=''3504340''>optimized</span>
  <span m=''3504780''>code,</span> <span m=''3505130''>and</span> <span m=''3505310''>this</span>
  <span m=''3505490''>is</span> <span m=''3505700''>the</span> <span m=''3505810''>generated--</span>
  <span m=''3508050''>Basically,</span> <span m=''3508990''>all</span> <span m=''3509250''>four</span>
  <span m=''3509690''>of</span> <span m=''3509890''>the</span> <span m=''3510000''>original</span>
  <span m=''3510110''>program</span> <span m=''3510580''>generated.</span> </p><p><span
  m=''3511000''>But</span> <span m=''3511390''>in</span> <span m=''3511690''>here,</span>
  <span m=''3512050''>I</span> <span m=''3512170''>move</span> <span m=''3512400''>this</span>
  <span m=''3512620''>one</span> <span m=''3512860''>up.</span> <span m=''3514570''>But</span>
  <span m=''3514850''>in</span> <span m=''3514930''>this</span> <span m=''3515230''>one,</span>
  <span m=''3516005''>actually,</span> <span m=''3516380''>the</span> <span m=''3516720''>division</span>
  <span m=''3517120''>didn''t</span> <span m=''3517320''>get</span> <span m=''3517470''>moved</span>
  <span m=''3517720''>up,</span> <span m=''3518420''>so</span> <span m=''3519270''>[UNINTELLIGIBLE]</span>
  <span m=''3519710''>actually</span> <span m=''3520130''>inside</span> <span m=''3520530''>the
  loop</span> <span m=''3521145''>because</span> <span m=''3521570''>it''s</span>
  <span m=''3521740''>realized</span> <span m=''3521910''>you</span> <span m=''3522010''>can''t</span>
  <span m=''3522240''>do</span> <span m=''3522350''>that.</span> <span m=''3523090''>But</span>
  <span m=''3523460''>interestingly</span> <span m=''3523825''>moved</span> <span
  m=''3524190''>the</span> <span m=''3524370''>multiplication</span> <span m=''3524700''>out,</span>
  <span m=''3525230''>so</span> <span m=''3525550''>that</span> <span m=''3526010''>it</span>
  <span m=''3526190''>didn''t</span> <span m=''3526590''>care</span> <span m=''3526730''>about</span>
  <span m=''3526920''>the</span> <span m=''3527170''>overflow.</span> <span m=''3528180''>It</span>
  <span m=''3528560''>says,</span> <span m=''3528620''>hey,</span> <span m=''3529020''>overflow,</span>
  <span m=''3529420''>it</span> <span m=''3529590''>can</span> <span m=''3529830''>have</span>
  <span m=''3529980''>an</span> <span m=''3530060''>overflow,</span> <span m=''3530410''>but</span>
  <span m=''3531230''>it</span> <span m=''3531650''>will</span> <span m=''3532110''>worry</span>
  <span m=''3532500''>more</span> <span m=''3532750''>about</span> <span m=''3534430''>divide</span>
  <span m=''3534550''>by</span> <span m=''3534660''>0.</span> <span m=''3536360''>OK?</span>
  <span m=''3537590''>Any</span> <span m=''3537760''>questions</span> <span m=''3538150''>so</span>
  <span m=''3538460''>far?</span> </p><p><span m=''3544210''>So</span> <span m=''3544590''>here''s
  the</span> <span m=''3544820''>optimized</span> <span m=''3545210''>code,</span>
  <span m=''3545600''>and</span> <span m=''3545700''>if</span> <span m=''3545790''>you</span>
  <span m=''3545940''>run it,</span> <span m=''3546270''>there''s</span> <span m=''3547010''>seconds</span>
  <span m=''3547190''>versus</span> <span m=''3547590''>54</span> <span m=''3547810''>seconds.</span>
  <span m=''3548580''>Just</span> <span m=''3550000''>GCC</span> <span m=''3550330''>[UNINTELLIGIBLE]</span>
  <span m=''3550740''>0,</span> <span m=''3551840''>GCC</span> <span m=''3553340''>os,</span>
  <span m=''3553810''>so</span> <span m=''3554110''>it''ll</span> <span m=''3554430''>produce</span>
  <span m=''3554780''>very</span> <span m=''3554990''>compact</span> <span m=''3555530''>optimized</span>
  <span m=''3556010''>code.</span> <span m=''3558370''>So</span> <span m=''3558530''>the</span>
  <span m=''3558630''>key</span> <span m=''3558840''>thing</span> <span m=''3559100''>is</span>
  <span m=''3560110''>what''s</span> <span m=''3560340''>[UNINTELLIGIBLE]</span> <span
  m=''3560650''>these</span> <span m=''3560880''>optimizations.</span> </p><p><span
  m=''3562990''>The</span> <span m=''3563110''>key</span> <span m=''3563230''>thing</span>
  <span m=''3563450''>is</span> <span m=''3563910''>you</span> <span m=''3564070''>have</span>
  <span m=''3564170''>to</span> <span m=''3564270''>guarantee,</span> <span m=''3564710''>when
  you</span> <span m=''3565090''>optimize,</span> <span m=''3567060''>all</span> <span
  m=''3567970''>that</span> <span m=''3568470''>these</span> <span m=''3569330''>programs</span>
  <span m=''3569605''>[UNINTELLIGIBLE]</span> <span m=''3570460''>from</span> <span
  m=''3570600''>unoptimized,</span> <span m=''3571320''>optimized,</span> <span m=''3571880''>all</span>
  <span m=''3572320''>the</span> <span m=''3572600''>valid</span> <span m=''3572720''>input,</span>
  <span m=''3573390''>all</span> <span m=''3573665''>the valid</span> <span m=''3573940''>execution,</span>
  <span m=''3574930''>and</span> <span m=''3575140''>all valid</span> <span m=''3575570''>architecture</span>
  <span m=''3576030''>that</span> <span m=''3576180''>you''re</span> <span m=''3576310''>supposed
  to</span> <span m=''3576575''>run,</span> <span m=''3576840''>you</span> <span m=''3576970''>can''t</span>
  <span m=''3577240''>do</span> <span m=''3577310''>the</span> <span m=''3577400''>same</span>
  <span m=''3577760''>thing.</span> <span m=''3577970''>Otherwise,</span> <span m=''3578110''>it''s</span>
  <span m=''3578360''>not</span> <span m=''3578520''>a</span> <span m=''3578700''>good</span>
  <span m=''3578760''>optimizer</span> <span m=''3579560''>if</span> <span m=''3579730''>it</span>
  <span m=''3579830''>does</span> <span m=''3580000''>different</span> <span m=''3580340''>things</span>
  <span m=''3580550''>to code.</span> <span m=''3581380''>So</span> <span m=''3581560''>there
  are</span> <span m=''3581870''>a</span> <span m=''3581890''>lot</span> <span m=''3582170''>of</span>
  <span m=''3582290''>things</span> <span m=''3582570''>that</span> <span m=''3582940''>means</span>
  <span m=''3583200''>you</span> <span m=''3583300''>have</span> <span m=''3583410''>to</span>
  <span m=''3583510''>be</span> <span m=''3583650''>very</span> <span m=''3583985''>conservative</span>
  <span m=''3584320''>in</span> <span m=''3584440''>[UNINTELLIGIBLE]</span> <span
  m=''3584960''>cases.</span> <span m=''3585600''>So</span> <span m=''3586390''>you</span>
  <span m=''3586570''>have to</span> <span m=''3586760''>understand</span> <span m=''3587510''>both</span>
  <span m=''3588050''>control-flow</span> <span m=''3588340''>and</span> <span m=''3588630''>data</span>
  <span m=''3589040''>accesses,</span> <span m=''3590090''>and</span> <span m=''3590300''>make</span>
  <span m=''3590520''>sure</span> <span m=''3590690''>that</span> <span m=''3590840''>you</span>
  <span m=''3590990''>understand</span> <span m=''3591550''>them,</span> <span m=''3592020''>and</span>
  <span m=''3592280''>if</span> <span m=''3592630''>any of</span> <span m=''3592770''>them,</span>
  <span m=''3592960''>the</span> <span m=''3593150''>compile-time</span> <span m=''3593710''>analysis</span>
  <span m=''3594200''>cannot</span> <span m=''3594450''>understand,</span> <span m=''3595280''>the</span>
  <span m=''3595390''>compiler</span> <span m=''3596130''>give</span> <span m=''3596380''>up</span>
  <span m=''3596790''>very</span> <span m=''3596950''>fast.</span> </p><p><span m=''3599170''>So</span>
  <span m=''3600660''>the</span> <span m=''3600740''>thing</span> <span m=''3601070''>is,</span>
  <span m=''3601420''>most</span> <span m=''3601800''>of</span> <span m=''3601880''>the</span>
  <span m=''3601970''>time</span> <span m=''3602930''>if</span> <span m=''3603160''>that</span>
  <span m=''3603220''>information</span> <span m=''3603660''>is</span> <span m=''3603790''>not</span>
  <span m=''3603980''>available,</span> <span m=''3604810''>compilers</span> <span
  m=''3605390''>reduce</span> <span m=''3605770''>the</span> <span m=''3605880''>scope</span>
  <span m=''3606660''>of</span> <span m=''3606860''>the</span> <span m=''3606960''>region</span>
  <span m=''3607300''>[UNINTELLIGIBLE]</span> <span m=''3607570''>the</span> <span
  m=''3607690''>transformation.</span> <span m=''3608260''>So</span> <span m=''3608370''>we</span>
  <span m=''3608460''>have</span> <span m=''3608660''>this</span> <span m=''3608820''>point,</span>
  <span m=''3609030''>I</span> <span m=''3609070''>don''t know</span> <span m=''3609370''>beyond</span>
  <span m=''3609690''>that.</span> <span m=''3610100''>I</span> <span m=''3610260''>can</span>
  <span m=''3610460''>only</span> <span m=''3610640''>do</span> <span m=''3610790''>a</span>
  <span m=''3610830''>small</span> <span m=''3611190''>amount</span> <span m=''3611480''>of</span>
  <span m=''3611560''>transformations</span> <span m=''3612270''>here.</span> </p><p><span
  m=''3612820''>Or</span> <span m=''3613150''>reduce</span> <span m=''3613490''>the</span>
  <span m=''3613710''>aggressiveness</span> <span m=''3614200''>of</span> <span m=''3614310''>transformations,</span>
  <span m=''3615360''>and</span> <span m=''3615570''>sometimes</span> <span m=''3616000''>just</span>
  <span m=''3616170''>completely</span> <span m=''3617140''>leave</span> <span m=''3617600''>code</span>
  <span m=''3617860''>alone</span> <span m=''3618160''>as it</span> <span m=''3618470''>is</span>
  <span m=''3618610''>because</span> <span m=''3619350''>it</span> <span m=''3619680''>couldn''t,</span>
  <span m=''3620710''>even</span> <span m=''3620950''>the</span> <span m=''3621290''>things</span>
  <span m=''3621510''>you know,</span> <span m=''3622210''>no</span> <span m=''3622650''>sane</span>
  <span m=''3622850''>program</span> <span m=''3623280''>would</span> <span m=''3623510''>do,</span>
  <span m=''3623700''>and</span> <span m=''3623810''>of</span> <span m=''3623990''>course,</span>
  <span m=''3624130''>your</span> <span m=''3624290''>code</span> <span m=''3624530''>will</span>
  <span m=''3624810''>never</span> <span m=''3625000''>do.</span> <span m=''3625560''>The</span>
  <span m=''3625740''>compiler</span> <span m=''3626170''>assume,</span> <span m=''3626760''>if</span>
  <span m=''3626900''>it</span> <span m=''3627050''>is</span> <span m=''3627240''>a</span>
  <span m=''3627400''>valid</span> <span m=''3627570''>C</span> <span m=''3627980''>semantics,</span>
  <span m=''3628570''>it</span> <span m=''3628670''>might</span> <span m=''3628860''>happen.</span>
  <span m=''3630270''>Even</span> <span m=''3630480''>though</span> <span m=''3631340''>some</span>
  <span m=''3631510''>of</span> <span m=''3631620''>them</span> <span m=''3631740''>looked</span>
  <span m=''3632050''>really</span> <span m=''3632280''>crazy.</span> <span m=''3632940''>If</span>
  <span m=''3633080''>it</span> <span m=''3633300''>is a</span> <span m=''3633410''>valid</span>
  <span m=''3633570''>possible</span> <span m=''3633885''>way</span> <span m=''3634200''>of</span>
  <span m=''3634340''>doing</span> <span m=''3634630''>it,</span> <span m=''3634920''>compiler</span>
  <span m=''3635360''>has to</span> <span m=''3635450''>worry</span> <span m=''3635580''>about</span>
  <span m=''3635900''>it,</span> <span m=''3636400''>and</span> <span m=''3636790''>not</span>
  <span m=''3636950''>do</span> <span m=''3637070''>that.</span> <span m=''3637240''>So</span>
  <span m=''3637330''>it''s</span> <span m=''3637420''>here</span> <span m=''3637570''>to</span>
  <span m=''3637610''>be</span> <span m=''3637710''>careful</span> <span m=''3638040''>of</span>
  <span m=''3638240''>that.</span> </p><p><span m=''3639070''>So</span> <span m=''3639350''>first
  of all,</span> <span m=''3639960''>control-flow.</span> <span m=''3641630''>That</span>
  <span m=''3641850''>means</span> <span m=''3642040''>it</span> <span m=''3642130''>doesn''t</span>
  <span m=''3642380''>work</span> <span m=''3642710''>on</span> <span m=''3642990''>possible</span>
  <span m=''3643360''>paths</span> <span m=''3644380''>of</span> <span m=''3644540''>the</span>
  <span m=''3644630''>program</span> <span m=''3644885''>when you</span> <span m=''3645140''>execute</span>
  <span m=''3645590''>that.</span> <span m=''3646580''>And</span> <span m=''3647450''>the</span>
  <span m=''3647610''>way</span> <span m=''3647850''>you look</span> <span m=''3648120''>at
  this,</span> <span m=''3648260''>you</span> <span m=''3648400''>can</span> <span
  m=''3648670''>add</span> <span m=''3648890''>this</span> <span m=''3649060''>call</span>
  <span m=''3649380''>graphs</span> <span m=''3649720''>in</span> <span m=''3649970''>the</span>
  <span m=''3650130''>high-level</span> <span m=''3650560''>[UNINTELLIGIBLE]</span>
  <span m=''3650730''>the</span> <span m=''3650840''>call</span> <span m=''3651120''>in
  here,</span> <span m=''3651400''>and</span> <span m=''3651780''>control-flow</span>
  <span m=''3652200''>graphs</span> <span m=''3652700''>within</span> <span m=''3652980''>the</span>
  <span m=''3653210''>metadata</span> <span m=''3653720''>function</span> <span m=''3654640''>how</span>
  <span m=''3655190''>control</span> <span m=''3655560''>goes</span> <span m=''3655820''>from.</span>
  </p><p><span m=''3657140''>And</span> <span m=''3657410''>what</span> <span m=''3657720''>makes</span>
  <span m=''3658050''>it</span> <span m=''3658180''>hard</span> <span m=''3658445''>for</span>
  <span m=''3658710''>compiler to</span> <span m=''3659130''>analysis</span> <span
  m=''3659475''>this?</span> <span m=''3660280''>Bunch</span> <span m=''3660580''>of</span>
  <span m=''3660860''>things</span> <span m=''3660980''>[UNINTELLIGIBLE]</span> <span
  m=''3661120''>function</span> <span m=''3661490''>pointers.</span> <span m=''3662300''>You</span>
  <span m=''3662390''>probably</span> <span m=''3662650''>haven''t</span> <span m=''3662820''>done</span>
  <span m=''3662990''>function</span> <span m=''3663310''>pointers,</span> <span m=''3663750''>but</span>
  <span m=''3663980''>if you</span> <span m=''3664100''>have</span> <span m=''3664220''>function</span>
  <span m=''3664580''>pointers</span> <span m=''3664840''>in</span> <span m=''3665120''>the</span>
  <span m=''3665620''>compiler</span> <span m=''3666040''>concepts,</span> <span m=''3666510''>I</span>
  <span m=''3666580''>don''t</span> <span m=''3666690''>know</span> <span m=''3666810''>where</span>
  <span m=''3666970''>it''s</span> <span m=''3667140''>going.</span> <span m=''3667380''>I</span>
  <span m=''3667500''>have</span> <span m=''3667620''>to</span> <span m=''3667680''>be</span>
  <span m=''3667790''>very</span> <span m=''3667880''>careful.</span> </p><p><span
  m=''3668640''>Indirect</span> <span m=''3669200''>branches.</span> <span m=''3670270''>so</span>
  <span m=''3670770''>I</span> <span m=''3670960''>keep</span> <span m=''3671240''>addresses</span>
  <span m=''3671790''>somewhere</span> <span m=''3672540''>in</span> <span m=''3672660''>that</span>
  <span m=''3672830''>branch,</span> <span m=''3673190''>so that</span> <span m=''3673330''>I</span>
  <span m=''3673480''>don''t</span> <span m=''3673610''>know</span> <span m=''3673740''>where
  it''s</span> <span m=''3674115''>going.</span> <span m=''3675010''>Something</span>
  <span m=''3675060''>computed</span> <span m=''3675490''>go to</span> <span m=''3675750''>[UNINTELLIGIBLE].</span>
  </p><p><span m=''3677270''>Large</span> <span m=''3677700''>switch</span> <span
  m=''3677870''>statement.</span> <span m=''3679240''>It''s</span> <span m=''3679420''>just</span>
  <span m=''3679700''>spaghetti</span> <span m=''3679730''>code.</span> <span m=''3679910''>We</span>
  <span m=''3680210''>have</span> <span m=''3680310''>no</span> <span m=''3680460''>idea</span>
  <span m=''3680700''>where</span> <span m=''3680930''>it would</span> <span m=''3681120''>end</span>
  <span m=''3681320''>up</span> <span m=''3681430''>and</span> <span m=''3681580''>compile</span>
  <span m=''3681900''>at</span> <span m=''3682040''>us,</span> <span m=''3682220''>and</span>
  <span m=''3682290''>we</span> <span m=''3682400''>can''t</span> <span m=''3682590''>get</span>
  <span m=''3682680''>anywhere in</span> <span m=''3682950''>this switch</span> <span
  m=''3683315''>statement.</span> <span m=''3684190''>Either</span> <span m=''3684720''>[UNINTELLIGIBLE]</span>
  <span m=''3684760''>you</span> <span m=''3684920''>might</span> <span m=''3685120''>know</span>
  <span m=''3685290''>some</span> <span m=''3685500''>order</span> <span m=''3685810''>of</span>
  <span m=''3686060''>going through</span> <span m=''3686320''>that,</span> <span
  m=''3686580''>it</span> <span m=''3686720''>doesn''t</span> <span m=''3686860''>work.</span>
  </p><p><span m=''3688070''>If you</span> <span m=''3688440''>are</span> <span m=''3688810''>looped</span>
  <span m=''3688950''>with</span> <span m=''3689220''>[UNINTELLIGIBLE]</span> <span
  m=''3689740''>breaks</span> <span m=''3690240''>and</span> <span m=''3690470''>very</span>
  <span m=''3690700''>complex</span> <span m=''3691110''>things</span> <span m=''3691330''>in</span>
  <span m=''3691450''>the</span> <span m=''3691590''>compiler,</span> <span m=''3692040''>sometimes</span>
  <span m=''3692410''>it''ll</span> <span m=''3692610''>give</span> <span m=''3692740''>up.</span>
  <span m=''3693710''>When</span> <span m=''3694300''>the</span> <span m=''3694400''>loop</span>
  <span m=''3694610''>bounds are</span> <span m=''3694940''>unknown,</span> <span
  m=''3695540''>you''d</span> <span m=''3695990''>assume it</span> <span m=''3696390''>could
  be</span> <span m=''3696755''>anything.</span> <span m=''3697410''>Whereas</span>
  <span m=''3697570''>when</span> <span m=''3697650''>loop</span> <span m=''3697990''>bounds
  are</span> <span m=''3698260''>known,</span> <span m=''3698980''>as</span> <span
  m=''3699320''>you</span> <span m=''3699440''>saw</span> <span m=''3699760''>in</span>
  <span m=''3699890''>the</span> <span m=''3699980''>first</span> <span m=''3700210''>set</span>
  <span m=''3700400''>of</span> <span m=''3700510''>examples,</span> <span m=''3701050''>you</span>
  <span m=''3701160''>can</span> <span m=''3701890''>take</span> <span m=''3702120''>advantages</span>
  <span m=''3702840''>a</span> <span m=''3702890''>lot</span> <span m=''3703250''>more,</span>
  <span m=''3703660''>and</span> <span m=''3703780''>you</span> <span m=''3703900''>can
  do</span> <span m=''3704020''>a lot</span> <span m=''3704100''>more</span> <span
  m=''3704380''>aggressive</span> <span m=''3704835''>things,</span> <span m=''3705710''>or</span>
  <span m=''3706260''>not</span> <span m=''3706790''>care</span> <span m=''3707000''>about</span>
  <span m=''3707390''>cases</span> <span m=''3707710''>because</span> <span m=''3707930''>I</span>
  <span m=''3708020''>know</span> <span m=''3708220''>that.</span> <span m=''3708690''>But</span>
  <span m=''3708790''>in</span> <span m=''3708970''>this</span> <span m=''3709100''>unknown</span>
  <span m=''3709390''>loop</span> <span m=''3709570''>bounds,</span> <span m=''3710020''>you
  have</span> <span m=''3710100''>to be</span> <span m=''3710140''>a lot</span> <span
  m=''3710390''>more</span> <span m=''3710670''>careful</span> <span m=''3711040''>of</span>
  <span m=''3711180''>that.</span> </p><p><span m=''3713700''>And</span> <span m=''3714120''>conditions</span>
  <span m=''3714680''>where</span> <span m=''3714880''>branch</span> <span m=''3715190''>is
  not</span> <span m=''3715480''>analyzable.</span> <span m=''3716000''>So</span>
  <span m=''3716150''>if</span> <span m=''3716270''>you</span> <span m=''3716390''>have</span>
  <span m=''3716510''>branch</span> <span m=''3716770''>condition,</span> <span m=''3717200''>if</span>
  <span m=''3717290''>you</span> <span m=''3717390''>don''t</span> <span m=''3717660''>know</span>
  <span m=''3717770''>what''s</span> <span m=''3717950''>happening</span> <span m=''3718310''>in</span>
  <span m=''3718380''>the</span> <span m=''3718450''>branch,</span> <span m=''3719600''>I</span>
  <span m=''3719720''>might</span> <span m=''3719930''>not</span> <span m=''3720090''>be</span>
  <span m=''3720190''>able</span> <span m=''3720350''>to</span> <span m=''3720390''>take</span>
  <span m=''3720620''>advantages</span> <span m=''3721170''>or</span> <span m=''3721330''>think</span>
  <span m=''3722230''>how</span> <span m=''3722510''>to</span> <span m=''3722560''>do</span>
  <span m=''3722720''>the branch</span> <span m=''3723010''>well.</span> <span m=''3723680''>So</span>
  <span m=''3723990''>those</span> <span m=''3724240''>are</span> <span m=''3724270''>the</span>
  <span m=''3724370''>things</span> <span m=''3724600''>that</span> <span m=''3724750''>I</span>
  <span m=''3724780''>have</span> <span m=''3724920''>to</span> <span m=''3725000''>worry</span>
  <span m=''3725220''>about.</span> </p><p><span m=''3727270''>The</span> <span m=''3727430''>other</span>
  <span m=''3727590''>thing</span> <span m=''3727790''>is data</span> <span m=''3728170''>accessors,</span>
  <span m=''3728950''>so</span> <span m=''3729120''>that</span> <span m=''3729390''>means</span>
  <span m=''3730020''>who</span> <span m=''3730850''>else</span> <span m=''3731170''>can</span>
  <span m=''3731480''>read</span> <span m=''3731780''>and</span> <span m=''3731900''>write</span>
  <span m=''3732140''>the</span> <span m=''3732230''>data.</span> <span m=''3732570''>So</span>
  <span m=''3732710''>I</span> <span m=''3732800''>am</span> <span m=''3733630''>touching</span>
  <span m=''3733990''>the</span> <span m=''3734240''>data</span> <span m=''3734440''>item,</span>
  <span m=''3735640''>and</span> <span m=''3736330''>I</span> <span m=''3736480''>need</span>
  <span m=''3736700''>to</span> <span m=''3736800''>know</span> <span m=''3737070''>that,</span>
  <span m=''3737700''>between</span> <span m=''3738350''>the</span> <span m=''3738480''>two</span>
  <span m=''3738660''>points</span> <span m=''3739020''>I</span> <span m=''3739130''>am</span>
  <span m=''3739290''>looking</span> <span m=''3739570''>at</span> <span m=''3739680''>the</span>
  <span m=''3739780''>data,</span> <span m=''3740290''>nobody</span> <span m=''3740620''>else</span>
  <span m=''3740950''>go</span> <span m=''3741170''>and</span> <span m=''3741430''>muck
  with</span> <span m=''3741770''>my</span> <span m=''3742120''>data,</span> <span
  m=''3742210''>or use</span> <span m=''3742420''>my</span> <span m=''3742560''>data.</span>
  <span m=''3743920''>Because</span> <span m=''3744790''>when</span> <span m=''3745050''>I</span>
  <span m=''3745600''>look</span> <span m=''3745750''>at the</span> <span m=''3745920''>data,</span>
  <span m=''3746090''>[UNINTELLIGIBLE]</span> <span m=''3746780''>something,</span>
  <span m=''3747230''>I</span> <span m=''3747290''>want</span> <span m=''3747410''>to</span>
  <span m=''3747530''>make</span> <span m=''3747710''>sure</span> <span m=''3748320''>that''s</span>
  <span m=''3748530''>the</span> <span m=''3748600''>only</span> <span m=''3748890''>way</span>
  <span m=''3749040''>that</span> <span m=''3749240''>data</span> <span m=''3749460''>can</span>
  <span m=''3749610''>be</span> <span m=''3749770''>accessed</span> <span m=''3750250''>because,</span>
  <span m=''3750710''>as you know,</span> <span m=''3751160''>most</span> <span m=''3751470''>of</span>
  <span m=''3751520''>the</span> <span m=''3751610''>things</span> <span m=''3751930''>are
  in</span> <span m=''3752050''>memory.</span> </p><p><span m=''3752780''>So</span>
  <span m=''3752960''>normally</span> <span m=''3753320''>compiler</span> <span m=''3753870''>[UNINTELLIGIBLE]</span>
  <span m=''3754170''>is</span> <span m=''3754440''>called</span> <span m=''3755400''>def-use</span>
  <span m=''3755610''>chains,</span> <span m=''3756280''>so</span> <span m=''3756510''>defined</span>
  <span m=''3756880''>to</span> <span m=''3757040''>use,</span> <span m=''3757760''>so
  we</span> <span m=''3758040''>say</span> <span m=''3758540''>that</span> <span m=''3758780''>thing</span>
  <span m=''3758990''>that</span> <span m=''3759120''>defined</span> <span m=''3759480''>here</span>
  <span m=''3759880''>is</span> <span m=''3760060''>going</span> <span m=''3760210''>to</span>
  <span m=''3760250''>get</span> <span m=''3760400''>used</span> <span m=''3760580''>here,</span>
  <span m=''3761560''>and</span> <span m=''3761830''>nothing</span> <span m=''3762220''>comes</span>
  <span m=''3762540''>in</span> <span m=''3762620''>between</span> <span m=''3763010''>that.</span>
  <span m=''3763750''>And</span> <span m=''3764080''>that</span> <span m=''3764320''>information</span>
  <span m=''3765270''>is</span> <span m=''3765460''>that''s how</span> <span m=''3765600''>the
  compiler</span> <span m=''3766030''>[UNINTELLIGIBLE].</span> <span m=''3766430''>That''s</span>
  <span m=''3766610''>something</span> <span m=''3766970''>we</span> <span m=''3767080''>call</span>
  <span m=''3767220''>dependence</span> <span m=''3767495''>vectors.</span> <span
  m=''3770130''>We</span> <span m=''3770330''>might</span> <span m=''3770580''>talk</span>
  <span m=''3771020''>a</span> <span m=''3771040''>little</span> <span m=''3771380''>bit</span>
  <span m=''3771510''>about</span> <span m=''3771740''>that</span> <span m=''3771910''>when</span>
  <span m=''3772110''>you</span> <span m=''3772230''>go</span> <span m=''3772430''>into</span>
  <span m=''3773680''>parallel</span> <span m=''3774140''>execution.</span> </p><p><span
  m=''3775980''>So</span> <span m=''3776230''>what</span> <span m=''3776610''>makes</span>
  <span m=''3776860''>it</span> <span m=''3777010''>very</span> <span m=''3777210''>hard</span>
  <span m=''3777480''>for</span> <span m=''3777600''>compiler</span> <span m=''3778140''>to</span>
  <span m=''3778280''>analyze</span> <span m=''3779120''>this?</span> <span m=''3779980''>For</span>
  <span m=''3780130''>example,</span> <span m=''3780990''>address</span> <span m=''3781390''>taken</span>
  <span m=''3781670''>variables,</span> <span m=''3782840''>so</span> <span m=''3783320''>if</span>
  <span m=''3783480''>you</span> <span m=''3783640''>write</span> <span m=''3783950''>and</span>
  <span m=''3784030''>hack</span> <span m=''3784110''>with C,</span> <span m=''3784790''>you</span>
  <span m=''3784940''>can</span> <span m=''3785100''>say,</span> <span m=''3785210''>OK,</span>
  <span m=''3785500''>there''s</span> <span m=''3785720''>a</span> <span m=''3785770''>variable.</span>
  <span m=''3786260''>There''s</span> <span m=''3786430''>a variable</span> <span
  m=''3786540''>here,</span> <span m=''3787040''>I''m</span> <span m=''3787180''>taking</span>
  <span m=''3787400''>the address</span> <span m=''3787580''>of</span> <span m=''3787810''>that.</span>
  </p><p><span m=''3788540''>Suddenly,</span> <span m=''3789240''>that</span> <span
  m=''3789490''>means</span> <span m=''3789810''>somebody</span> <span m=''3790075''>else</span>
  <span m=''3791720''>has</span> <span m=''3792030''>the</span> <span m=''3792250''>address</span>
  <span m=''3792480''>to</span> <span m=''3792610''>the</span> <span m=''3792720''>variable.</span>
  <span m=''3793390''>That</span> <span m=''3793560''>means</span> <span m=''3793820''>anybody</span>
  <span m=''3794240''>else</span> <span m=''3794520''>can</span> <span m=''3794700''>suddenly</span>
  <span m=''3795260''>jump</span> <span m=''3795530''>in</span> <span m=''3795680''>and</span>
  <span m=''3795790''>overwrite</span> <span m=''3796180''>you,</span> <span m=''3796360''>and</span>
  <span m=''3796480''>there''s</span> <span m=''3796680''>a</span> <span m=''3796720''>lot</span>
  <span m=''3796860''>of</span> <span m=''3797000''>possibilities</span> <span m=''3797280''>of
  doing</span> <span m=''3797560''>that.</span> <span m=''3798250''>And</span> <span
  m=''3798400''>suddenly</span> <span m=''3798650''>compiler</span> <span m=''3799090''>says
  wait</span> <span m=''3799270''>a</span> <span m=''3799320''>minute,</span> <span
  m=''3799960''>that</span> <span m=''3800250''>variable,</span> <span m=''3800720''>even</span>
  <span m=''3801070''>though</span> <span m=''3801910''>I</span> <span m=''3802570''>assigned</span>
  <span m=''3803000''>the</span> <span m=''3803080''>variable</span> <span m=''3803490''>here,</span>
  <span m=''3803810''>I''m</span> <span m=''3804000''>using it</span> <span m=''3804390''>here,</span>
  <span m=''3804780''>in</span> <span m=''3805140''>between.</span> <span m=''3805790''>Somebody</span>
  <span m=''3806100''>else</span> <span m=''3806310''>might</span> <span m=''3806480''>touch
  it</span> <span m=''3806890''>even</span> <span m=''3807140''>though</span> <span
  m=''3807220''>it</span> <span m=''3807360''>might</span> <span m=''3807530''>not</span>
  <span m=''3807700''>use the</span> <span m=''3807920''>same</span> <span m=''3808150''>name</span>
  <span m=''3808530''>because</span> <span m=''3808840''>somebody</span> <span m=''3809200''>has</span>
  <span m=''3809420''>that</span> <span m=''3809590''>address</span> <span m=''3809790''>to</span>
  <span m=''3809870''>that.</span> </p><p><span m=''3811080''>OK,</span> <span m=''3811300''>so</span>
  <span m=''3811850''>that''s</span> <span m=''3812080''>a</span> <span m=''3812290''>hard</span>
  <span m=''3812550''>thing.</span> <span m=''3813080''>Global</span> <span m=''3813370''>variables,</span>
  <span m=''3813820''>sometimes,</span> <span m=''3815160''>because</span> <span m=''3815920''>between</span>
  <span m=''3816280''>function,</span> <span m=''3816590''>I don''t</span> <span m=''3816870''>know.</span>
  <span m=''3817080''>Some</span> <span m=''3817300''>other</span> <span m=''3817430''>function</span>
  <span m=''3817770''>might</span> <span m=''3818400''>go and</span> <span m=''3818580''>change</span>
  <span m=''3818830''>it.</span> </p><p><span m=''3820446''>Parameters</span> <span
  m=''3820850''>are</span> <span m=''3820960''>really</span> <span m=''3821200''>hard.</span>
  <span m=''3821790''>Like</span> <span m=''3822000''>for</span> <span m=''3822140''>example,</span>
  <span m=''3822600''>remember</span> <span m=''3822830''>when we had</span> <span
  m=''3823110''>a program,</span> <span m=''3823405''>and</span> <span m=''3823700''>we</span>
  <span m=''3823890''>had</span> <span m=''3824080''>something</span> <span m=''3824410''>like</span>
  <span m=''3825360''>copying</span> <span m=''3825810''>same</span> <span m=''3826120''>array</span>
  <span m=''3826430''>to</span> <span m=''3826490''>the</span> <span m=''3826570''>same,</span>
  <span m=''3826810''>even</span> <span m=''3826950''>though</span> <span m=''3827200''>parameters</span>
  <span m=''3827510''>say</span> <span m=''3827670''>X</span> <span m=''3828070''>and</span>
  <span m=''3828220''>Y.</span> <span m=''3829280''>I</span> <span m=''3829380''>might</span>
  <span m=''3829620''>send</span> <span m=''3829790''>the</span> <span m=''3830370''>same</span>
  <span m=''3830630''>or</span> <span m=''3830890''>overlapping</span> <span m=''3831610''>regions</span>
  <span m=''3832490''>into</span> <span m=''3832880''>two</span> <span m=''3832900''>different</span>
  <span m=''3833190''>parameters</span> <span m=''3833620''>even</span> <span m=''3833860''>though</span>
  <span m=''3834810''>it</span> <span m=''3834950''>looks</span> <span m=''3835160''>like</span>
  <span m=''3835290''>two</span> <span m=''3835510''>different</span> <span m=''3835890''>names.</span>
  <span m=''3836840''>They''re not</span> <span m=''3837170''>two</span> <span m=''3837310''>different</span>
  <span m=''3837650''>things.</span> <span m=''3837890''>They''re</span> <span m=''3838140''>actually</span>
  <span m=''3838390''>overlapping</span> <span m=''3838640''>at</span> <span m=''3838760''>some</span>
  <span m=''3838940''>point.</span> </p><p><span m=''3840000''>And</span> <span m=''3840170''>so</span>
  <span m=''3840310''>you</span> <span m=''3840480''>had to</span> <span m=''3840940''>assume,</span>
  <span m=''3841140''>even</span> <span m=''3841520''>if</span> <span m=''3841640''>you</span>
  <span m=''3841710''>have</span> <span m=''3842420''>two</span> <span m=''3842550''>different</span>
  <span m=''3842990''>parameters</span> <span m=''3843420''>point</span> <span m=''3843740''>into</span>
  <span m=''3844565''>memory,</span> <span m=''3845530''>they</span> <span m=''3845770''>might</span>
  <span m=''3846120''>be</span> <span m=''3846230''>the</span> <span m=''3846310''>same</span>
  <span m=''3846590''>thing.</span> <span m=''3847340''>And</span> <span m=''3847630''>that''s
  the</span> <span m=''3847840''>worst</span> <span m=''3848140''>case,</span> <span
  m=''3848360''>even though</span> <span m=''3848400''>a</span> <span m=''3848680''>lot</span>
  <span m=''3848800''>of</span> <span m=''3848920''>times,</span> <span m=''3849100''>nobody</span>
  <span m=''3849410''>does</span> <span m=''3849610''>that.</span> <span m=''3849840''>Nobody</span>
  <span m=''3850100''>gives</span> <span m=''3850250''>the</span> <span m=''3850380''>same</span>
  <span m=''3850730''>things</span> <span m=''3851260''>multiple</span> <span m=''3851400''>names,</span>
  <span m=''3852160''>but</span> <span m=''3852800''>it''s</span> <span m=''3853020''>possible.</span>
  <span m=''3853370''>If</span> <span m=''3853520''>it</span> <span m=''3853600''>is</span>
  <span m=''3853710''>possible,</span> <span m=''3854390''>compilers</span> <span
  m=''3854810''>deal</span> <span m=''3855280''>with it.</span> </p><p><span m=''3855500''>Either</span>
  <span m=''3855870''>it</span> <span m=''3856280''>has to</span> <span m=''3856570''>generate</span>
  <span m=''3857070''>code to</span> <span m=''3857530''>test</span> <span m=''3857820''>all</span>
  <span m=''3857980''>these</span> <span m=''3858160''>cases,</span> <span m=''3858500''>is</span>
  <span m=''3858630''>it</span> <span m=''3858700''>overlapping,</span> <span m=''3859305''>if</span>
  <span m=''3859560''>not,</span> <span m=''3859710''>do</span> <span m=''3859980''>something.</span>
  <span m=''3860480''>If</span> <span m=''3860590''>it</span> <span m=''3860760''>is</span>
  <span m=''3860890''>overlapping,</span> <span m=''3861410''>do</span> <span m=''3861540''>something</span>
  <span m=''3861830''>slower,</span> <span m=''3862810''>like</span> <span m=''3863370''>the</span>
  <span m=''3863470''>code</span> <span m=''3863910''>we</span> <span m=''3864070''>showed</span>
  <span m=''3864360''>when you</span> <span m=''3864510''>are</span> <span m=''3864750''>vectorizing.</span>
  <span m=''3865360''>You</span> <span m=''3865470''>treat it</span> <span m=''3865890''>like</span>
  <span m=''3866090''>this</span> <span m=''3866990''>huge</span> <span m=''3867320''>number</span>
  <span m=''3867660''>of</span> <span m=''3867740''>different</span> <span m=''3868020''>cases,</span>
  <span m=''3869410''>but</span> <span m=''3872640''>unless</span> <span m=''3873010''>you</span>
  <span m=''3873110''>do</span> <span m=''3873260''>something</span> <span m=''3873540''>like</span>
  <span m=''3873650''>that,</span> <span m=''3873810''>you</span> <span m=''3873960''>can''t</span>
  <span m=''3874120''>optimize,</span> <span m=''3874750''>and</span> <span m=''3874930''>complex</span>
  <span m=''3875300''>programs,</span> <span m=''3875660''>it''s very</span> <span
  m=''3875850''>hard</span> <span m=''3876090''>to do that.</span> </p><p><span m=''3877425''>A
  lot</span> <span m=''3877870''>of</span> <span m=''3878250''>times,</span> <span
  m=''3878390''>pointers</span> <span m=''3878760''>create</span> <span m=''3880710''>issues</span>
  <span m=''3880950''>in</span> <span m=''3881080''>here</span> <span m=''3882400''>because</span>
  <span m=''3882750''>the</span> <span m=''3882840''>problem</span> <span m=''3883230''>with</span>
  <span m=''3883350''>pointers</span> <span m=''3884190''>is</span> <span m=''3884820''>what</span>
  <span m=''3885070''>you</span> <span m=''3885150''>call</span> <span m=''3885260''>it</span>
  <span m=''3885350''>point</span> <span m=''3885640''>aliasing,</span> <span m=''3886080''>because</span>
  <span m=''3886630''>pointers,</span> <span m=''3887140''>you</span> <span m=''3887240''>can</span>
  <span m=''3887410''>add</span> <span m=''3887580''>any</span> <span m=''3887650''>value</span>
  <span m=''3887920''>to</span> <span m=''3888030''>a</span> <span m=''3888150''>pointer</span>
  <span m=''3889310''>and you</span> <span m=''3889410''>have no</span> <span m=''3889780''>idea</span>
  <span m=''3889910''>if you</span> <span m=''3890250''>had</span> <span m=''3890390''>a
  very</span> <span m=''3890500''>large</span> <span m=''3890670''>value.</span> <span
  m=''3891220''>It</span> <span m=''3891360''>can</span> <span m=''3892250''>be</span>
  <span m=''3892410''>anywhere</span> <span m=''3892640''>in memory</span> <span m=''3893870''>because</span>
  <span m=''3894190''>if you</span> <span m=''3894290''>have a</span> <span m=''3894430''>pointer,</span>
  <span m=''3894750''>you have</span> <span m=''3895030''>a point</span> <span m=''3895360''>in</span>
  <span m=''3895440''>the</span> <span m=''3895520''>memory</span> <span m=''3896350''>you</span>
  <span m=''3896420''>can add</span> <span m=''3896890''>anything,</span> <span m=''3897160''>subtract</span>
  <span m=''3897600''>anything.</span> <span m=''3898790''>The</span> <span m=''3898950''>world
  is</span> <span m=''3899310''>yours,</span> <span m=''3900060''>and</span> <span
  m=''3900220''>C</span> <span m=''3900440''>gives</span> <span m=''3900500''>you</span>
  <span m=''3900690''>this</span> <span m=''3900880''>ability</span> <span m=''3901360''>to</span>
  <span m=''3901530''>go</span> <span m=''3902010''>all</span> <span m=''3902260''>over
  the</span> <span m=''3902370''>world</span> <span m=''3902610''>and</span> <span
  m=''3902780''>kind</span> <span m=''3903020''>of</span> <span m=''3903445''>mapping</span>
  <span m=''3903760''>the</span> <span m=''3903970''>world,</span> <span m=''3905100''>and</span>
  <span m=''3905650''>some</span> <span m=''3905850''>programs</span> <span m=''3906130''>do</span>
  <span m=''3906410''>that.</span> </p><p><span m=''3907230''>And</span> <span m=''3907370''>so</span>
  <span m=''3907450''>the</span> <span m=''3907550''>compiler</span> <span m=''3907920''>says,</span>
  <span m=''3908050''>oh,</span> <span m=''3908310''>it''s a point.</span> <span m=''3908840''>I</span>
  <span m=''3908910''>don''t</span> <span m=''3909030''>know</span> <span m=''3909150''>where
  it</span> <span m=''3909470''>is.</span> <span m=''3910000''>I</span> <span m=''3910050''>just</span>
  <span m=''3910260''>have</span> <span m=''3910370''>to leave</span> <span m=''3910630''>it
  alone</span> <span m=''3911340''>because</span> <span m=''3911810''>some</span>
  <span m=''3912170''>guy,</span> <span m=''3912700''>probably</span> <span m=''3913110''>0.001%</span>
  <span m=''3914240''>of the</span> <span m=''3914470''>world</span> <span m=''3914910''>programmers</span>
  <span m=''3915470''>will</span> <span m=''3915640''>do</span> <span m=''3915830''>something</span>
  <span m=''3916140''>crazy,</span> <span m=''3916820''>and</span> <span m=''3916970''>everybody</span>
  <span m=''3917310''>has</span> <span m=''3917500''>to pay</span> <span m=''3917620''>the</span>
  <span m=''3917720''>price.</span> <span m=''3919410''>So</span> <span m=''3919890''>this</span>
  <span m=''3920150''>is</span> <span m=''3920340''>what</span> <span m=''3920580''>makes</span>
  <span m=''3920790''>programming</span> <span m=''3921210''>hard.</span> </p><p><span
  m=''3921730''>And</span> <span m=''3921980''>the</span> <span m=''3922060''>final</span>
  <span m=''3922430''>thing</span> <span m=''3922670''>is</span> <span m=''3922820''>there''s</span>
  <span m=''3923060''>a</span> <span m=''3923130''>thing</span> <span m=''3923420''>called</span>
  <span m=''3923590''>[UNINTELLIGIBLE]</span> <span m=''3923640''>types.</span> <span
  m=''3925570''>When</span> <span m=''3925770''>you</span> <span m=''3925900''>go</span>
  <span m=''3926250''>to</span> <span m=''3926780''>parallel</span> <span m=''3927080''>programming</span>
  <span m=''3927345''>you</span> <span m=''3927610''>realize,</span> <span m=''3927920''>because</span>
  <span m=''3928700''>normally</span> <span m=''3929980''>compilers</span> <span m=''3930730''>keep</span>
  <span m=''3931930''>normal</span> <span m=''3932110''>values</span> <span m=''3932160''>are
  in the</span> <span m=''3932600''>memory.</span> <span m=''3933792''>Compiler</span>
  <span m=''3934260''>can</span> <span m=''3934940''>[UNINTELLIGIBLE]</span> <span
  m=''3935160''>the value</span> <span m=''3935400''>into</span> <span m=''3935610''>register</span>
  <span m=''3936940''>and</span> <span m=''3937250''>keep</span> <span m=''3937470''>operating</span>
  <span m=''3937950''>in</span> <span m=''3938030''>the</span> <span m=''3938150''>register,</span>
  <span m=''3938680''>and</span> <span m=''3939030''>at</span> <span m=''3939140''>some</span>
  <span m=''3939320''>point,</span> <span m=''3939550''>put it back</span> <span m=''3939670''>to
  memory.</span> <span m=''3941330''>But</span> <span m=''3941580''>if</span> <span
  m=''3941800''>you''re</span> <span m=''3942180''>running</span> <span m=''3942340''>a
  parallel</span> <span m=''3942490''>program,</span> <span m=''3942990''>somebody</span>
  <span m=''3943770''>else</span> <span m=''3943930''>might</span> <span m=''3944230''>want</span>
  <span m=''3944410''>to</span> <span m=''3944470''>look</span> <span m=''3944640''>at</span>
  <span m=''3944780''>that</span> <span m=''3944960''>value,</span> <span m=''3946310''>and</span>
  <span m=''3946500''>if</span> <span m=''3946620''>it</span> <span m=''3946800''>isn''t</span>
  <span m=''3947100''>registered,</span> <span m=''3947320''>you don''t</span> <span
  m=''3947610''>have</span> <span m=''3947900''>that</span> <span m=''3948230''>value
  in</span> <span m=''3948350''>the right</span> <span m=''3948650''>place.</span>
  <span m=''3948910''>It''s</span> <span m=''3949370''>somewhere</span> <span m=''3949690''>else,</span>
  <span m=''3950000''>so</span> <span m=''3950110''>you</span> <span m=''3950230''>get</span>
  <span m=''3950400''>a</span> <span m=''3950640''>stale</span> <span m=''3950970''>copy</span>
  <span m=''3951630''>because</span> <span m=''3951710''>you</span> <span m=''3951850''>have</span>
  <span m=''3951920''>moved it.</span> </p><p><span m=''3952420''>What I''m</span>
  <span m=''3952680''>trying to</span> <span m=''3952930''>say is,</span> <span m=''3953530''>look,</span>
  <span m=''3953840''>you</span> <span m=''3954050''>have to</span> <span m=''3954530''>always</span>
  <span m=''3954650''>keep it</span> <span m=''3955060''>in</span> <span m=''3955220''>memory.</span>
  <span m=''3955320''>You</span> <span m=''3955400''>can''t</span> <span m=''3955680''>take</span>
  <span m=''3955850''>it</span> <span m=''3955960''>out.</span> <span m=''3956460''>You</span>
  <span m=''3956510''>can''t</span> <span m=''3956650''>just</span> <span m=''3956820''>modify</span>
  <span m=''3957150''>it,</span> <span m=''3957850''>but</span> <span m=''3958040''>you</span>
  <span m=''3958290''>can</span> <span m=''3958530''>move it</span> <span m=''3958900''>somewhere</span>
  <span m=''3959220''>else</span> <span m=''3959600''>the</span> <span m=''3960150''>faster</span>
  <span m=''3960480''>place</span> <span m=''3960570''>to</span> <span m=''3961756''>do
  things</span> <span m=''3962110''>to it</span> <span m=''3962980''>because</span>
  <span m=''3963490''>somebody else</span> <span m=''3963970''>might</span> <span
  m=''3964150''>be</span> <span m=''3964230''>looking</span> <span m=''3964520''>at</span>
  <span m=''3964620''>it.</span> <span m=''3965250''>And</span> <span m=''3965480''>so</span>
  <span m=''3965880''>what that</span> <span m=''3966110''>means is</span> <span m=''3966350''>compilers</span>
  <span m=''3966820''>give</span> <span m=''3966980''>up</span> <span m=''3967100''>it''s</span>
  <span m=''3967190''>hands and</span> <span m=''3967450''>say,</span> <span m=''3967680''>look,</span>
  <span m=''3967860''>I can''t</span> <span m=''3968000''>do anything.</span> </p><p><span
  m=''3971970''>So</span> <span m=''3973450''>we are</span> <span m=''3973890''>a
  little bit</span> <span m=''3974050''>early.</span> <span m=''3974390''>I</span>
  <span m=''3974490''>have</span> <span m=''3975060''>yet</span> <span m=''3975380''>another</span>
  <span m=''3975630''>huge</span> <span m=''3975980''>session</span> <span m=''3976275''>in</span>
  <span m=''3976570''>here</span> <span m=''3977280''>at--</span> <span m=''3977580''>OK,</span>
  <span m=''3977950''>we</span> <span m=''3978050''>have</span> <span m=''3978150''>to</span>
  <span m=''3978210''>go</span> <span m=''3978370''>through</span> <span m=''3978510''>this</span>
  <span m=''3979000''>thing.</span> <span m=''3979360''>Good.</span> </p><p><span
  m=''3981510''>I</span> <span m=''3981660''>think</span> <span m=''3982800''>now</span>
  <span m=''3984120''>we</span> <span m=''3984280''>are</span> <span m=''3984420''>going</span>
  <span m=''3984750''>to</span> <span m=''3986130''>go</span> <span m=''3986560''>about</span>
  <span m=''3986850''>and</span> <span m=''3987000''>see</span> <span m=''3987750''>how</span>
  <span m=''3987880''>you</span> <span m=''3988050''>guys</span> <span m=''3988340''>did</span>
  <span m=''3988510''>in</span> <span m=''3988600''>the</span> <span m=''3988710''>class</span>
  <span m=''3989750''>exam.</span> <span m=''3991080''>OK.</span> <span m=''3992360''>And</span>
  <span m=''3992570''>I''m</span> <span m=''3992720''>seeing</span> <span m=''3992980''>it</span>
  <span m=''3993090''>for</span> <span m=''3993170''>the</span> <span m=''3993230''>first</span>
  <span m=''3993430''>time,</span> <span m=''3993630''>and it</span> <span m=''3993740''>looks</span>
  <span m=''3994000''>really</span> <span m=''3994200''>nice.</span> <span m=''3994890''>Where</span>
  <span m=''3994980''>do you</span> <span m=''3995270''>plug this</span> <span m=''3995540''>in?</span>
  <span m=''3996900''>Where do you</span> <span m=''3997040''>plug</span> <span m=''3997170''>this
  in?</span> </p><p><span m=''4011890''>OK,</span> <span m=''4012520''>so</span> <span
  m=''4012730''>here</span> <span m=''4013260''>is</span> <span m=''4014180''>the</span>
  <span m=''4016770''>distribution</span> <span m=''4017370''>in</span> <span m=''4017470''>there.</span>
  <span m=''4018440''>This was</span> <span m=''4018610''>not an</span> <span m=''4019060''>easy</span>
  <span m=''4019200''>exam,</span> <span m=''4020050''>and</span> <span m=''4020390''>in</span>
  <span m=''4020550''>fact,</span> <span m=''4020860''>we</span> <span m=''4021260''>compared</span>
  <span m=''4021800''>how</span> <span m=''4022090''>you</span> <span m=''4022190''>guys</span>
  <span m=''4022480''>did</span> <span m=''4022840''>last</span> <span m=''4023450''>year,</span>
  <span m=''4023750''>and</span> <span m=''4024000''>you</span> <span m=''4024090''>guys</span>
  <span m=''4024300''>have</span> <span m=''4024420''>done</span> <span m=''4024550''>a</span>
  <span m=''4024570''>lot</span> <span m=''4024740''>better</span> <span m=''4024990''>than</span>
  <span m=''4025200''>I</span> <span m=''4025260''>think</span> <span m=''4025750''>the</span>
  <span m=''4025920''>first</span> <span m=''4026120''>exam</span> <span m=''4026320''>in</span>
  <span m=''4026380''>last</span> <span m=''4026520''>year.</span> <span m=''4027260''>So</span>
  <span m=''4028670''>basically,</span> <span m=''4029380''>we</span> <span m=''4029480''>have</span>
  <span m=''4030976''>a</span> <span m=''4031400''>median</span> <span m=''4032110''>about</span>
  <span m=''4032410''>70,</span> <span m=''4033090''>somewhere</span> <span m=''4033460''>here,</span>
  <span m=''4034580''>and</span> <span m=''4035080''>a</span> <span m=''4035140''>nice</span>
  <span m=''4035540''>tight</span> <span m=''4037300''>grouping</span> <span m=''4037635''>in</span>
  <span m=''4037970''>here,</span> <span m=''4038410''>which</span> <span m=''4038490''>is</span>
  <span m=''4038670''>really</span> <span m=''4038870''>good.</span> <span m=''4040060''>And</span>
  <span m=''4040690''>so</span> <span m=''4041020''>what</span> <span m=''4041240''>we</span>
  <span m=''4041490''>have</span> <span m=''4041760''>is,</span> <span m=''4042970''>we</span>
  <span m=''4043130''>have</span> <span m=''4043290''>exams</span> <span m=''4043950''>back.</span>
  <span m=''4045840''>Take</span> <span m=''4046050''>a</span> <span m=''4046090''>look.</span>
  <span m=''4046946''>And</span> <span m=''4049330''>I</span> <span m=''4049660''>think--</span>
  </p><p><span m=''4050792''>GUEST SPEAKER: I''d like to</span> <span m=''4051284''>make
  one</span> <span m=''4051776''>comment</span> <span m=''4052268''>about</span> <span
  m=''4052760''>[INAUDIBLE].</span> </p><p><span m=''4053990''>PROFESSOR: OK,</span>
  <span m=''4054090''>sure.</span> </p><p><span m=''4060114''>GUEST SPEAKER: [INAUDIBLE].</span>
  <span m=''4071950''>So</span> <span m=''4073310''>not</span> <span m=''4073500''>surprisingly,</span>
  <span m=''4074200''>I</span> <span m=''4074330''>graded</span> <span m=''4074830''>the</span>
  <span m=''4075560''>problem</span> <span m=''4076220''>on</span> <span m=''4081940''>the</span>
  <span m=''4082570''>cache</span> <span m=''4082860''>oblivious</span> <span m=''4083330''>algorithm</span>
  <span m=''4085100''>doing</span> <span m=''4085300''>the</span> <span m=''4085440''>recursion</span>
  <span m=''4085860''>tree.</span> <span m=''4087130''>There</span> <span m=''4087300''>is</span>
  <span m=''4087420''>a</span> <span m=''4087500''>common</span> <span m=''4088010''>mistake</span>
  <span m=''4088950''>that</span> <span m=''4089220''>many</span> <span m=''4089470''>people</span>
  <span m=''4089830''>made,</span> <span m=''4095220''>which</span> <span m=''4095380''>I</span>
  <span m=''4095530''>wanted</span> <span m=''4095810''>to</span> <span m=''4095880''>explain</span>
  <span m=''4096430''>why</span> <span m=''4096649''>it''s</span> <span m=''4096819''>wrong</span>
  <span m=''4098540''>because</span> <span m=''4099029''>so</span> <span m=''4099240''>many</span>
  <span m=''4099500''>people</span> <span m=''4099819''>made</span> <span m=''4100100''>this</span>
  <span m=''4100270''>mistake.</span> <span m=''4100880''>They</span> <span m=''4100990''>got</span>
  <span m=''4101200''>it</span> <span m=''4101300''>almost</span> <span m=''4101750''>all</span>
  <span m=''4101990''>right,</span> <span m=''4102390''>and</span> <span m=''4102580''>then</span>
  <span m=''4103740''>they</span> <span m=''4103859''>made</span> <span m=''4104120''>this</span>
  <span m=''4104279''>mistake.</span> </p><p><span m=''4104880''>So</span> <span m=''4105010''>it''s</span>
  <span m=''4105830''>basically</span> <span m=''4106340''>an</span> <span m=''4106420''>understanding</span>
  <span m=''4107069''>of</span> <span m=''4107290''>recurrence.</span> <span m=''4108600''>So
  the</span> <span m=''4108870''>recurrences</span> <span m=''4109430''>I</span> <span
  m=''4109630''>recall</span> <span m=''4109930''>was</span> <span m=''4110109''>q
  of</span> <span m=''4110500''>r</span> <span m=''4111330''>is</span> <span m=''4111500''>equal</span>
  <span m=''4111840''>to</span> <span m=''4112950''>square</span> <span m=''4113420''>root</span>
  <span m=''4113779''>of</span> <span m=''4113960''>r</span> <span m=''4116109''>over</span>
  <span m=''4117319''>b</span> <span m=''4124450''>if</span> <span m=''4124560''>square</span>
  <span m=''4124950''>root</span> <span m=''4125060''>of</span> <span m=''4125240''>r</span>
  <span m=''4125840''>is</span> <span m=''4126140''>less</span> <span m=''4126540''>than</span>
  <span m=''4127920''>CM</span> <span m=''4130360''>for</span> <span m=''4131824''>C,</span>
  <span m=''4132319''>et</span> <span m=''4132580''>cetera.</span> <span m=''4132819''>OK?</span>
  <span m=''4133800''>And</span> <span m=''4134090''>then</span> <span m=''4134310''>otherwise,</span>
  <span m=''4135170''>it</span> <span m=''4135439''>was</span> <span m=''4135979''>2q</span>
  <span m=''4137899''>of</span> <span m=''4139180''>r</span> <span m=''4139399''>over</span>
  <span m=''4139620''>2</span> <span m=''4141060''>plus</span> <span m=''4141560''>theta</span>
  <span m=''4141830''>1.</span> </p><p><span m=''4145500''>Now,</span> <span m=''4145750''>what</span>
  <span m=''4147410''>people</span> <span m=''4147770''>did in</span> <span m=''4148180''>their</span>
  <span m=''4148430''>recursion</span> <span m=''4148770''>tree--</span> <span m=''4149300''>first</span>
  <span m=''4149620''>of</span> <span m=''4149689''>all,</span> <span m=''4149830''>some</span>
  <span m=''4150040''>people</span> <span m=''4150370''>didn''t</span> <span m=''4150710''>recognize</span>
  <span m=''4151300''>that</span> <span m=''4151380''>what</span> <span m=''4151520''>goes</span>
  <span m=''4151790''>in</span> <span m=''4151840''>the</span> <span m=''4151970''>recursion</span>
  <span m=''4152420''>tree</span> <span m=''4152649''>is</span> <span m=''4152819''>this</span>
  <span m=''4153050''>value,</span> <span m=''4154450''>the</span> <span m=''4154540''>number</span>
  <span m=''4154810''>of</span> <span m=''4154890''>cache</span> <span m=''4155290''>misses.</span>
  <span m=''4155810''>So</span> <span m=''4156109''>the</span> <span m=''4156270''>recursion</span>
  <span m=''4156544''>tree</span> <span m=''4156819''>is</span> <span m=''4156950''>going</span>
  <span m=''4157029''>to</span> <span m=''4157100''>look</span> <span m=''4157359''>like</span>
  <span m=''4157689''>theta</span> <span m=''4157960''>1,</span> <span m=''4158920''>or</span>
  <span m=''4159060''>you</span> <span m=''4159120''>can leave</span> <span m=''4159460''>out
  the</span> <span m=''4159725''>thetas</span> <span m=''4160140''>if</span> <span
  m=''4160229''>you</span> <span m=''4160319''>want</span> <span m=''4160439''>to</span>
  <span m=''4160479''>put</span> <span m=''4160680''>them</span> <span m=''4160819''>in</span>
  <span m=''4160899''>at</span> <span m=''4161029''>the</span> <span m=''4161180''>end.</span>
  <span m=''4162560''>Theta</span> <span m=''4162729''>1,</span> <span m=''4164430''>theta</span>
  <span m=''4164510''>1,</span> <span m=''4164979''>et</span> <span m=''4165090''>cetera.</span>
  <span m=''4165170''>So</span> <span m=''4165990''>many</span> <span m=''4166260''>people</span>
  <span m=''4166590''>got</span> <span m=''4166880''>this,</span> <span m=''4167100''>and</span>
  <span m=''4167229''>then the</span> <span m=''4167370''>question</span> <span m=''4167800''>is</span>
  <span m=''4167880''>what</span> <span m=''4168149''>happens</span> <span m=''4168910''>when</span>
  <span m=''4169180''>it</span> <span m=''4169250''>hits</span> <span m=''4169560''>the</span>
  <span m=''4169660''>leaf.</span> <span m=''4171529''>OK?</span> <span m=''4172649''>So</span>
  <span m=''4173630''>when</span> <span m=''4173790''>it</span> <span m=''4173850''>hits</span>
  <span m=''4174100''>a</span> <span m=''4174180''>leaf,</span> <span m=''4174870''>many</span>
  <span m=''4175140''>people</span> <span m=''4175510''>correctly</span> <span m=''4176100''>got</span>
  <span m=''4176760''>that</span> <span m=''4176920''>you</span> <span m=''4177010''>can''t</span>
  <span m=''4177470''>mess</span> <span m=''4177710''>around</span> <span m=''4178010''>with</span>
  <span m=''4178149''>constants.</span> </p><p><span m=''4179670''>You have</span>
  <span m=''4179910''>to</span> <span m=''4179960''>be</span> <span m=''4180080''>very</span>
  <span m=''4180310''>careful</span> <span m=''4180600''>of</span> <span m=''4180680''>constants</span>
  <span m=''4181210''>if</span> <span m=''4181319''>they''re in</span> <span m=''4181490''>an
  exponent,</span> <span m=''4183640''>that</span> <span m=''4183800''>you</span>
  <span m=''4183960''>hit</span> <span m=''4184109''>the</span> <span m=''4184270''>leaf</span>
  <span m=''4190350''>when</span> <span m=''4190460''>square</span> <span m=''4190710''>root</span>
  <span m=''4190790''>of</span> <span m=''4190899''>r</span> <span m=''4191689''>becomes</span>
  <span m=''4192069''>less</span> <span m=''4192319''>than</span> <span m=''4192439''>c</span>
  <span m=''4192680''>over</span> <span m=''4192930''>m,</span> <span m=''4193189''>in</span>
  <span m=''4193300''>which</span> <span m=''4193510''>case</span> <span m=''4194270''>the</span>
  <span m=''4194400''>cost</span> <span m=''4195000''>is</span> <span m=''4195130''>going</span>
  <span m=''4195260''>to</span> <span m=''4195310''>be</span> <span m=''4195560''>square</span>
  <span m=''4195860''>root</span> <span m=''4195960''>of</span> <span m=''4196060''>r</span>
  <span m=''4196370''>over</span> <span m=''4196560''>b.</span> <span m=''4197060''>So</span>
  <span m=''4197220''>what</span> <span m=''4197370''>they</span> <span m=''4197480''>did</span>
  <span m=''4197690''>was</span> <span m=''4198060''>the</span> <span m=''4198440''>incorrect</span>
  <span m=''4199060''>thing,</span> <span m=''4199310''>was</span> <span m=''4199510''>they</span>
  <span m=''4199640''>put</span> <span m=''4199920''>square</span> <span m=''4200250''>root</span>
  <span m=''4200380''>of</span> <span m=''4200520''>r</span> <span m=''4201490''>over</span>
  <span m=''4201790''>b</span> <span m=''4202010''>here.</span> <span m=''4203470''>Why</span>
  <span m=''4203720''>is</span> <span m=''4203890''>that</span> <span m=''4204130''>wrong?</span>
  </p><p><span m=''4207090''>[INTERPOSING VOICES]</span> </p><p><span m=''4209500''>GUEST
  SPEAKER: It''s</span> <span m=''4209710''>the</span> <span m=''4209800''>wrong</span>
  <span m=''4210140''>r.</span> <span m=''4211890''>Right?</span> <span m=''4215750''>OK,</span>
  <span m=''4216150''>it''s</span> <span m=''4216340''>the</span> <span m=''4216420''>wrong</span>
  <span m=''4216770''>r.</span> <span m=''4217660''>This</span> <span m=''4218050''>r</span>
  <span m=''4218400''>is</span> <span m=''4218620''>the</span> <span m=''4218740''>r</span>
  <span m=''4219000''>here</span> <span m=''4219310''>on</span> <span m=''4219390''>the</span>
  <span m=''4219460''>right-hand</span> <span m=''4219930''>side.</span> <span m=''4220150''>It''s</span>
  <span m=''4220260''>not</span> <span m=''4220450''>the</span> <span m=''4220530''>one</span>
  <span m=''4220740''>here.</span> </p><p><span m=''4220950''>It''s the</span> <span
  m=''4221170''>r</span> <span m=''4221425''>if</span> <span m=''4221680''>r</span>
  <span m=''4222150''>is</span> <span m=''4222240''>sufficiently</span> <span m=''4222830''>small,</span>
  <span m=''4224570''>that''s</span> <span m=''4224840''>the</span> <span m=''4224920''>value
  you''re</span> <span m=''4225290''>taking.</span> <span m=''4225640''>But</span>
  <span m=''4225820''>we''re</span> <span m=''4225990''>expanding</span> <span m=''4226580''>an</span>
  <span m=''4226680''>r</span> <span m=''4227010''>from</span> <span m=''4227200''>the</span>
  <span m=''4227290''>top</span> <span m=''4227680''>here.</span> <span m=''4229380''>So</span>
  <span m=''4229550''>what''s</span> <span m=''4229780''>the</span> <span m=''4229880''>value</span>
  <span m=''4230270''>that</span> <span m=''4230410''>should</span> <span m=''4230680''>go</span>
  <span m=''4230880''>here?</span> <span m=''4233250''>OK,</span> <span m=''4233596''>cm</span>
  <span m=''4234290''>is</span> <span m=''4234470''>the</span> <span m=''4234550''>value</span>
  <span m=''4234815''>that</span> <span m=''4235080''>should</span> <span m=''4235310''>go</span>
  <span m=''4235470''>here.</span> <span m=''4237310''>OK?</span> <span m=''4238680''>The
  value</span> <span m=''4238860''>that</span> <span m=''4239110''>should</span> <span
  m=''4239390''>go</span> <span m=''4239540''>here is</span> <span m=''4239800''>cm.</span>
  <span m=''4242590''>Yes?</span> </p><p><span m=''4243070''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''4245474''>two</span> <span m=''4245955''>r''s</span> <span m=''4246436''>can
  actually</span> <span m=''4246917''>follow the</span> <span m=''4247398''>right-side?</span>
  <span m=''4249322''>And then</span> <span m=''4249803''>it''s very close</span>
  <span m=''4250284''>to where they''re</span> <span m=''4250765''>written the same</span>
  <span m=''4251246''>but are</span> <span m=''4251727''>spoken</span> <span m=''4252208''>differently.</span>
  </p><p><span m=''4253180''>GUEST SPEAKER: Well,</span> <span m=''4253720''>when</span>
  <span m=''4253890''>you</span> <span m=''4253990''>say--</span> <span m=''4254340''>what</span>
  <span m=''4254630''>do you</span> <span m=''4254650''>mean?</span> </p><p><span
  m=''4255640''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''4257030''>GUEST SPEAKER:
  There''s an</span> <span m=''4257300''>r</span> <span m=''4257760''>here.</span>
  </p><p><span m=''4258410''>AUDIENCE: And it''s</span> <span m=''4258896''>different</span>
  <span m=''4259382''>from the other</span> <span m=''4259868''>r--</span> </p><p><span
  m=''4260354''>GUEST SPEAKER: No,</span> <span m=''4260840''>it''s</span> <span m=''4261100''>the</span>
  <span m=''4261200''>same</span> <span m=''4261520''>r.</span> <span m=''4261700''>The</span>
  <span m=''4261820''>question</span> <span m=''4262260''>is</span> <span m=''4262420''>there,</span>
  <span m=''4262790''>r</span> <span m=''4263420''>is</span> <span m=''4263570''>a</span>
  <span m=''4263620''>variable.</span> <span m=''4264900''>So it''d</span> <span m=''4265130''>be</span>
  <span m=''4265270''>nice</span> <span m=''4265620''>if</span> <span m=''4265780''>the</span>
  <span m=''4265910''>r</span> <span m=''4266290''>were</span> <span m=''4266350''>constant,</span>
  <span m=''4266940''>but</span> <span m=''4267100''>it''s</span> <span m=''4267290''>not.</span>
  <span m=''4267600''>It''s</span> <span m=''4267780''>a</span> <span m=''4267890''>variable.</span>
  <span m=''4269100''>And</span> <span m=''4269270''>so</span> <span m=''4269420''>the</span>
  <span m=''4269510''>point</span> <span m=''4269850''>is</span> <span m=''4270090''>the</span>
  <span m=''4270180''>point</span> <span m=''4270550''>where</span> <span m=''4270680''>you</span>
  <span m=''4270830''>plug it</span> <span m=''4271120''>in</span> <span m=''4271410''>here,</span>
  <span m=''4272850''>you''ve</span> <span m=''4273030''>got</span> <span m=''4273190''>to</span>
  <span m=''4273240''>plug</span> <span m=''4273520''>in,</span> <span m=''4273800''>not</span>
  <span m=''4274080''>the</span> <span m=''4274180''>variable,</span> <span m=''4274640''>you''ve</span>
  <span m=''4274810''>got</span> <span m=''4274940''>to</span> <span m=''4275000''>plug
  in</span> <span m=''4275430''>the</span> <span m=''4275520''>value.</span> </p><p><span
  m=''4276470''>AUDIENCE: You</span> <span m=''4276940''>just said</span> <span m=''4277880''>for</span>
  <span m=''4278350''>r</span> <span m=''4278820''>[UNINTELLIGIBLE].</span> </p><p><span
  m=''4280935''>GUEST SPEAKER: It''s</span> <span m=''4281240''>a</span> <span m=''4281290''>variable.</span>
  <span m=''4281575''>You</span> <span m=''4281860''>have</span> <span m=''4282120''>to</span>
  <span m=''4282380''>plug in</span> <span m=''4282770''>the</span> <span m=''4282870''>value</span>
  <span m=''4283430''>of</span> <span m=''4283590''>the</span> <span m=''4283670''>variable</span>
  <span m=''4284810''>at</span> <span m=''4285010''>this</span> <span m=''4285260''>point</span>
  <span m=''4285530''>if you''re</span> <span m=''4285750''>going to</span> <span
  m=''4285900''>solve</span> <span m=''4286200''>the</span> <span m=''4286500''>recurrence.</span>
  <span m=''4287260''>Putting</span> <span m=''4287580''>an</span> <span m=''4287700''>r</span>
  <span m=''4287960''>here,</span> <span m=''4288280''>we''re</span> <span m=''4288420''>trying</span>
  <span m=''4288540''>to</span> <span m=''4288750''>I</span> <span m=''4288780''>say,</span>
  <span m=''4289390''>this</span> <span m=''4289620''>whole</span> <span m=''4289880''>thing</span>
  <span m=''4290165''>is</span> <span m=''4290450''>q</span> <span m=''4290610''>of</span>
  <span m=''4290770''>r.</span> <span m=''4292490''>And</span> <span m=''4292630''>we</span>
  <span m=''4292770''>started</span> <span m=''4293400''>out,</span> <span m=''4293560''>if</span>
  <span m=''4293680''>we</span> <span m=''4293800''>did</span> <span m=''4294030''>the</span>
  <span m=''4294100''>development</span> <span m=''4294680''>of</span> <span m=''4294780''>the</span>
  <span m=''4294860''>tree,</span> <span m=''4295150''>which</span> <span m=''4295350''>is</span>
  <span m=''4295460''>the</span> <span m=''4295540''>safest</span> <span m=''4296000''>thing</span>
  <span m=''4296170''>to</span> <span m=''4296230''>do,</span> <span m=''4296820''>you</span>
  <span m=''4296940''>get</span> <span m=''4297130''>theta</span> <span m=''4297410''>1</span>
  <span m=''4297760''>plus</span> <span m=''4298170''>q</span> <span m=''4298380''>of</span>
  <span m=''4298510''>r</span> <span m=''4298780''>over</span> <span m=''4299050''>2,</span>
  <span m=''4300080''>and</span> <span m=''4300190''>you</span> <span m=''4300300''>keep</span>
  <span m=''4300580''>going</span> <span m=''4300940''>down</span> <span m=''4301500''>until</span>
  <span m=''4302000''>your</span> <span m=''4302220''>value</span> <span m=''4302800''>for</span>
  <span m=''4303050''>r</span> <span m=''4304340''>satisfies</span> <span m=''4305160''>this</span>
  <span m=''4305380''>condition.</span> <span m=''4306960''>At</span> <span m=''4307130''>that</span>
  <span m=''4307460''>point,</span> <span m=''4307870''>what''s</span> <span m=''4308090''>the</span>
  <span m=''4308310''>value</span> <span m=''4308730''>for</span> <span m=''4308960''>r?</span>
  <span m=''4310830''>OK?</span> </p><p><span m=''4311520''>You</span> <span m=''4311690''>can''t</span>
  <span m=''4311980''>then</span> <span m=''4312180''>say</span> <span m=''4312430''>it''s</span>
  <span m=''4312650''>the</span> <span m=''4312740''>same</span> <span m=''4313090''>r</span>
  <span m=''4313690''>that</span> <span m=''4313970''>you</span> <span m=''4314180''>started</span>
  <span m=''4314660''>with.</span> <span m=''4315140''>It''s</span> <span m=''4315330''>not</span>
  <span m=''4315560''>this</span> <span m=''4315790''>r,</span> <span m=''4317120''>and</span>
  <span m=''4317220''>that''s</span> <span m=''4317440''>because</span> <span m=''4317740''>r</span>
  <span m=''4317980''>is</span> <span m=''4318070''>a</span> <span m=''4318160''>variable,</span>
  <span m=''4318860''>not</span> <span m=''4319160''>because</span> <span m=''4320580''>of</span>
  <span m=''4320700''>anything</span> <span m=''4321150''>else.</span> <span m=''4321510''>r</span>
  <span m=''4321700''>is</span> <span m=''4321890''>a</span> <span m=''4321940''>variable,</span>
  <span m=''4322510''>and</span> <span m=''4322670''>we''re</span> <span m=''4322790''>using</span>
  <span m=''4323630''>the</span> <span m=''4323800''>r.</span> <span m=''4324050''>This</span>
  <span m=''4324260''>is</span> <span m=''4324370''>a</span> <span m=''4324430''>question</span>
  <span m=''4324790''>of</span> <span m=''4324890''>understanding</span> <span m=''4325490''>of</span>
  <span m=''4325580''>the</span> <span m=''4325670''>recurrence.</span> <span m=''4327865''>So</span>
  <span m=''4328180''>in</span> <span m=''4328270''>any</span> <span m=''4328420''>case,</span>
  <span m=''4328680''>that</span> <span m=''4328850''>was</span> <span m=''4329020''>a</span>
  <span m=''4329230''>common</span> <span m=''4329660''>mistake</span> <span m=''4330470''>that</span>
  <span m=''4330890''>people</span> <span m=''4331160''>make.</span> </p><p><span
  m=''4331650''>The</span> <span m=''4331800''>other</span> <span m=''4332030''>minor</span>
  <span m=''4332590''>error</span> <span m=''4332975''>that</span> <span m=''4333360''>people</span>
  <span m=''4333640''>made</span> <span m=''4333950''>on</span> <span m=''4334540''>that</span>
  <span m=''4335100''>problem,</span> <span m=''4335360''>that</span> <span m=''4335510''>most</span>
  <span m=''4335840''>people</span> <span m=''4336130''>made,</span> <span m=''4337010''>was</span>
  <span m=''4338210''>in</span> <span m=''4338610''>describing</span> <span m=''4339360''>where</span>
  <span m=''4339620''>do you</span> <span m=''4339830''>get</span> <span m=''4340110''>this</span>
  <span m=''4340310''>recurrence,</span> <span m=''4343150''>they</span> <span m=''4343700''>left</span>
  <span m=''4344110''>out</span> <span m=''4344370''>the</span> <span m=''4344450''>fact</span>
  <span m=''4344800''>is</span> <span m=''4344920''>why</span> <span m=''4345300''>is</span>
  <span m=''4345510''>it</span> <span m=''4345650''>going</span> <span m=''4345750''>to</span>
  <span m=''4345840''>be</span> <span m=''4345990''>square</span> <span m=''4346340''>root</span>
  <span m=''4346400''>of</span> <span m=''4346510''>r</span> <span m=''4346770''>over</span>
  <span m=''4347740''>b.</span> <span m=''4348120''>It''s</span> <span m=''4348300''>really</span>
  <span m=''4348620''>because</span> <span m=''4349130''>na</span> <span m=''4349680''>is</span>
  <span m=''4349840''>approximately</span> <span m=''4350710''>nb</span> <span m=''4352030''>because</span>
  <span m=''4352320''>the</span> <span m=''4352420''>way</span> <span m=''4352640''>that</span>
  <span m=''4352810''>the</span> <span m=''4352900''>code</span> <span m=''4353270''>works,</span>
  <span m=''4353900''>we''re</span> <span m=''4354080''>keeping</span> <span m=''4354420''>na</span>
  <span m=''4354860''>and</span> <span m=''4354990''>nb</span> <span m=''4355170''>to</span>
  <span m=''4355490''>within</span> <span m=''4355750''>a</span> <span m=''4355800''>factor</span>
  <span m=''4356190''>of</span> <span m=''4356300''>two</span> <span m=''4356460''>of</span>
  <span m=''4356610''>each</span> <span m=''4356850''>other.</span> <span m=''4357820''>OK?</span>
  <span m=''4358510''>And</span> <span m=''4358670''>so</span> <span m=''4358800''>if</span>
  <span m=''4358860''>you</span> <span m=''4358950''>didn''t</span> <span m=''4359150''>mention</span>
  <span m=''4359450''>that,</span> <span m=''4359640''>you</span> <span m=''4359730''>lost</span>
  <span m=''4360030''>a</span> <span m=''4360100''>point.</span> <span m=''4360480''>It
  wasn''t</span> <span m=''4360660''>a</span> <span m=''4360770''>big</span> <span
  m=''4360990''>deal,</span> <span m=''4361310''>but</span> <span m=''4362660''>many</span>
  <span m=''4362920''>people</span> <span m=''4363650''>didn''t</span> <span m=''4363910''>neglect</span>
  <span m=''4364390''>that</span> <span m=''4364640''>very</span> <span m=''4364940''>important</span>
  <span m=''4366860''>statement.</span> </p><p><span m=''4367560''>Overall,</span>
  <span m=''4368070''>people</span> <span m=''4368370''>did</span> <span m=''4368530''>very</span>
  <span m=''4368760''>well</span> <span m=''4368970''>on</span> <span m=''4369110''>this</span>
  <span m=''4369250''>problem.</span> <span m=''4370400''>Overall,</span> <span m=''4370770''>you''ll</span>
  <span m=''4370920''>see</span> <span m=''4371150''>people</span> <span m=''4371410''>got</span>
  <span m=''4372850''>a</span> <span m=''4372940''>lot</span> <span m=''4373130''>of</span>
  <span m=''4373200''>partial</span> <span m=''4373580''>credit</span> <span m=''4373910''>on</span>
  <span m=''4374210''>it.</span> </p>'
uid: d0341317-6a68-e88f-4be9-59b08b68f7ab
---
