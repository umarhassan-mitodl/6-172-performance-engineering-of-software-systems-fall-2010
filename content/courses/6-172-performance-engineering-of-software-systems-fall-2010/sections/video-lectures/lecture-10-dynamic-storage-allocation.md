---
about_this_resource_text: <p><strong>Description:</strong> Lecture covering dynamic
  storage allocation, including reference counting, a graph abstraction, and updating
  pointers.</p> <p><strong>Speaker:</strong> Charles Leiserson</p>
content_type: resource
course_id: 6-172-performance-engineering-of-software-systems-fall-2010
embedded_media:
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.172F10/MIT6_172_F10_lec10_300k.mp4
  parent_uid: 7bddd3a5edad77679f5510757575b5a8
  title: Video-Internet Archive-MP4
  type: Video
  uid: f46244f7928246b5c5506d88d6d47fb8
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/itunes-u/lecture-10-dynamic-storage/id481759887?i=109649118
  parent_uid: 7bddd3a5edad77679f5510757575b5a8
  title: Video-iTunes U-MP4
  type: Video
  uid: e0c1b5eb07f03813c76e269fef44ee12
- id: Video-YouTube-Stream
  media_location: p0bc1f6ULxw
  parent_uid: 7bddd3a5edad77679f5510757575b5a8
  title: Video-YouTube-Stream
  type: Video
  uid: d73c3b0c6cbce8db68b9b5aba9b677d3
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/p0bc1f6ULxw/default.jpg
  parent_uid: 7bddd3a5edad77679f5510757575b5a8
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: b2e8ba34cf6d4e7b4afbbf3dd88dce60
- id: MIT6_172F10_lec10.pdf
  parent_uid: 7bddd3a5edad77679f5510757575b5a8
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-10-dynamic-storage-allocation/MIT6_172F10_lec10.pdf
  title: MIT6_172F10_lec10.pdf
  type: null
  uid: 2d0d2c2eb10ff55d98f63e50f9f85290
- id: 3Play-3PlayYouTubeid-MP4
  media_location: p0bc1f6ULxw
  parent_uid: 7bddd3a5edad77679f5510757575b5a8
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 2d0a3c68287bd4722533e71671608553
- id: p0bc1f6ULxw.srt
  parent_uid: 7bddd3a5edad77679f5510757575b5a8
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-10-dynamic-storage-allocation/p0bc1f6ULxw.srt
  title: 3play caption file
  type: null
  uid: 0ba7d78fcdcefabf4bed687f152281d8
- id: p0bc1f6ULxw.pdf
  parent_uid: 7bddd3a5edad77679f5510757575b5a8
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-10-dynamic-storage-allocation/p0bc1f6ULxw.pdf
  title: 3play pdf file
  type: null
  uid: c0f982ceefb577ed659484e7838e338d
- id: Caption-3Play YouTube id-SRT
  parent_uid: 7bddd3a5edad77679f5510757575b5a8
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 1bd265c5a8d9f62021ccbd0857933b74
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 7bddd3a5edad77679f5510757575b5a8
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 36830f614fca7427ac9325eb1de730b1
file: null
file_size: null
hide_download: true
hide_download_original: null
inline_embed_id: 59916963lecture10:dynamicstorageallocation50533877
layout: video
license: https://creativecommons.org/licenses/by-nc-sa/4.0/
order_index: 115
parent_uid: 24169d0487e846a39c316276f85b8cb5
related_resources_text: ''
short_url: lecture-10-dynamic-storage-allocation
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-10-dynamic-storage-allocation
title: 'Lecture 10: Dynamic Storage Allocation'
transcript: '<p><span m=''120''>The</span> <span m=''190''>following</span> <span
  m=''630''>content</span> <span m=''1230''>is</span> <span m=''1340''>provided</span>
  <span m=''1790''>under</span> <span m=''2070''>a</span> <span m=''2090''>Creative</span>
  <span m=''2500''>Commons</span> <span m=''2910''>license.</span> <span m=''3910''>Your</span>
  <span m=''4200''>support</span> <span m=''4700''>will</span> <span m=''4870''>help</span>
  <span m=''5100''>MIT</span> <span m=''5580''>OpenCourseWare</span> <span m=''6360''>continue</span>
  <span m=''6870''>to</span> <span m=''6950''>offer</span> <span m=''7380''>high-quality</span>
  <span m=''8119''>educational</span> <span m=''8740''>resources</span> <span m=''9390''>for</span>
  <span m=''9520''>free.</span> <span m=''10600''>To</span> <span m=''10730''>make</span>
  <span m=''10930''>a</span> <span m=''10980''>donation</span> <span m=''11620''>or</span>
  <span m=''11930''>view</span> <span m=''12340''>additional</span> <span m=''12800''>materials</span>
  <span m=''13340''>from</span> <span m=''13500''>hundreds</span> <span m=''13930''>of</span>
  <span m=''14040''>MIT</span> <span m=''14460''>courses,</span> <span m=''15460''>visit</span>
  <span m=''15790''>MIT</span> <span m=''16219''>OpenCourseWare</span> <span m=''17250''>at</span>
  <span m=''17430''>ocw.mit.edu.</span> </p><p><span m=''23960''>CHARLES LEISERSON:
  Today</span> <span m=''24390''>we''re</span> <span m=''24540''>going</span> <span
  m=''24620''>to</span> <span m=''24700''>talk</span> <span m=''24960''>about</span>
  <span m=''25360''>dynamic</span> <span m=''25840''>storage</span> <span m=''26280''>allocation,</span>
  <span m=''27070''>which</span> <span m=''27300''>is</span> <span m=''27610''>a</span>
  <span m=''28640''>hugely</span> <span m=''29670''>rich</span> <span m=''30260''>and</span>
  <span m=''30580''>interesting</span> <span m=''31070''>topic,</span> <span m=''32140''>and</span>
  <span m=''33770''>hopefully</span> <span m=''34160''>cover</span> <span m=''34460''>some</span>
  <span m=''34650''>of</span> <span m=''34690''>the</span> <span m=''34770''>basics</span>
  <span m=''35440''>of</span> <span m=''35710''>dynamic</span> <span m=''36110''>storage</span>
  <span m=''36430''>allocation</span> <span m=''36990''>today.</span> <span m=''38090''>I</span>
  <span m=''38170''>want</span> <span m=''38320''>to</span> <span m=''38370''>start</span>
  <span m=''38660''>out</span> <span m=''38860''>with</span> <span m=''39070''>perhaps</span>
  <span m=''39490''>the</span> <span m=''39580''>simplest</span> <span m=''40610''>storage</span>
  <span m=''41150''>allocation</span> <span m=''41720''>scheme,</span> <span m=''42120''>and</span>
  <span m=''42170''>that''s</span> <span m=''42390''>stack</span> <span m=''42820''>allocation,</span>
  <span m=''44670''>which</span> <span m=''44980''>I</span> <span m=''45110''>think</span>
  <span m=''45380''>you''re</span> <span m=''45500''>probably</span> <span m=''45950''>fairly</span>
  <span m=''46370''>familiar</span> <span m=''46790''>with.</span> <span m=''47890''>So</span>
  <span m=''48090''>stack</span> <span m=''48480''>allocation</span> <span m=''49170''>is</span>
  <span m=''49370''>just</span> <span m=''49720''>an</span> <span m=''49840''>array</span>
  <span m=''51110''>and</span> <span m=''51460''>a</span> <span m=''51520''>pointer</span>
  <span m=''52180''>into</span> <span m=''52480''>the</span> <span m=''52620''>array,</span>
  <span m=''53040''>an</span> <span m=''53280''>index</span> <span m=''53890''>or
  a</span> <span m=''54010''>pointer</span> <span m=''54420''>into</span> <span m=''54600''>the</span>
  <span m=''54720''>array.</span> <span m=''56380''>And</span> <span m=''56560''>when
  you</span> <span m=''56680''>have</span> <span m=''56800''>a</span> <span m=''56850''>stack</span>
  <span m=''57330''>in</span> <span m=''57450''>a</span> <span m=''57520''>computer</span>
  <span m=''57960''>memory,</span> <span m=''59700''>you''re</span> <span m=''59890''>talking</span>
  <span m=''60120''>about</span> <span m=''60300''>the</span> <span m=''60420''>array</span>
  <span m=''60710''>of</span> <span m=''60820''>all</span> <span m=''61030''>memory,</span>
  <span m=''61840''>and</span> <span m=''62150''>the</span> <span m=''62210''>stack</span>
  <span m=''62620''>pointer</span> <span m=''62900''>pointing</span> <span m=''63260''>that''s</span>
  <span m=''63640''>used,</span> <span m=''64000''>for</span> <span m=''64110''>example,</span>
  <span m=''64540''>for</span> <span m=''65200''>calls.</span> </p><p><span m=''66540''>The</span>
  <span m=''67030''>reason</span> <span m=''67490''>stack</span> <span m=''67840''>allocation</span>
  <span m=''68660''>is</span> <span m=''69600''>neat</span> <span m=''69970''>is</span>
  <span m=''70170''>because</span> <span m=''70480''>it''s</span> <span m=''70630''>so</span>
  <span m=''70810''>simple.</span> <span m=''72210''>If</span> <span m=''72390''>I</span>
  <span m=''72480''>want</span> <span m=''72650''>to</span> <span m=''72700''>allocate</span>
  <span m=''73320''>x</span> <span m=''73620''>bytes,</span> <span m=''74960''>then</span>
  <span m=''75100''>what</span> <span m=''75270''>I</span> <span m=''75370''>do,</span>
  <span m=''75650''>is</span> <span m=''75810''>I</span> <span m=''75920''>just</span>
  <span m=''76130''>simply</span> <span m=''78120''>increment</span> <span m=''78660''>my</span>
  <span m=''78810''>stack</span> <span m=''79260''>pointer</span> <span m=''80070''>by</span>
  <span m=''81720''>x</span> <span m=''82000''>bytes,</span> <span m=''83210''>and</span>
  <span m=''83470''>then</span> <span m=''83780''>I</span> <span m=''84030''>return</span>
  <span m=''85300''>the</span> <span m=''85460''>original</span> <span m=''86040''>position</span>
  <span m=''86680''>of</span> <span m=''86890''>the</span> <span m=''86980''>stack</span>
  <span m=''87360''>pointer</span> <span m=''87890''>as</span> <span m=''88140''>being</span>
  <span m=''88470''>the</span> <span m=''88570''>location</span> <span m=''89210''>of</span>
  <span m=''89330''>the</span> <span m=''89410''>storage</span> <span m=''89870''>that''s</span>
  <span m=''90070''>just</span> <span m=''90290''>been</span> <span m=''90440''>allocated.</span>
  <span m=''93210''>So</span> <span m=''95390''>pretty</span> <span m=''95700''>simple.</span>
  <span m=''97320''>Typically</span> <span m=''98760''>if</span> <span m=''98950''>you</span>
  <span m=''99330''>write a</span> <span m=''99620''>stack</span> <span m=''99930''>allocator,</span>
  <span m=''100470''>the</span> <span m=''100560''>routines</span> <span m=''100970''>are</span>
  <span m=''101040''>so</span> <span m=''101260''>simple</span> <span m=''101680''>they</span>
  <span m=''101790''>get</span> <span m=''101980''>inlined,</span> <span m=''102700''>although</span>
  <span m=''103180''>it''s</span> <span m=''103370''>of</span> <span m=''103670''>course</span>
  <span m=''104500''>advantageous</span> <span m=''106520''>to</span> <span m=''106680''>say</span>
  <span m=''106980''>that</span> <span m=''107130''>things</span> <span m=''107330''>are</span>
  <span m=''107430''>inlined,</span> <span m=''107840''>but</span> <span m=''108010''>most</span>
  <span m=''108290''>compilers</span> <span m=''108830''>these</span> <span m=''109050''>days</span>
  <span m=''109360''>will</span> <span m=''109830''>inline.</span> <span m=''110460''>And</span>
  <span m=''110770''>as</span> <span m=''110970''>you</span> <span m=''111050''>can</span>
  <span m=''111150''>see,</span> <span m=''111320''>it''s</span> <span m=''111440''>just</span>
  <span m=''111650''>a</span> <span m=''111700''>couple</span> <span m=''111980''>of</span>
  <span m=''112060''>operations</span> <span m=''112720''>here</span> <span m=''112970''>to</span>
  <span m=''113530''>perform</span> <span m=''113950''>this</span> <span m=''114310''>calculation.</span>
  </p><p><span m=''115934''>To</span> <span m=''116690''>deallocate</span> <span m=''117990''>the</span>
  <span m=''118190''>bytes,</span> <span m=''118630''>we</span> <span m=''118820''>basically--</span>
  <span m=''119440''>oh,</span> <span m=''119620''>yeah,</span> <span m=''119780''>I</span>
  <span m=''120040''>should</span> <span m=''120270''>mention,</span> <span m=''121010''>this</span>
  <span m=''121190''>isn''t</span> <span m=''121430''>checking</span> <span m=''121790''>for</span>
  <span m=''121940''>overflow.</span> <span m=''123820''>So</span> <span m=''123950''>technically,</span>
  <span m=''124500''>one</span> <span m=''124700''>should</span> <span m=''124890''>check</span>
  <span m=''125170''>for</span> <span m=''125340''>overflow.</span> <span m=''130020''>One</span>
  <span m=''130250''>way</span> <span m=''130350''>to</span> <span m=''130460''>do</span>
  <span m=''130620''>that</span> <span m=''130830''>is</span> <span m=''130960''>for</span>
  <span m=''131050''>the</span> <span m=''131180''>assert</span> <span m=''131570''>package,</span>
  <span m=''132700''>and</span> <span m=''132930''>that</span> <span m=''133170''>way,</span>
  <span m=''133880''>at</span> <span m=''134050''>run</span> <span m=''134280''>time,</span>
  <span m=''134560''>you</span> <span m=''134630''>don''t</span> <span m=''134780''>have</span>
  <span m=''134970''>to</span> <span m=''135080''>pay</span> <span m=''136060''>the</span>
  <span m=''136750''>extra</span> <span m=''137060''>overhead</span> <span m=''137520''>of</span>
  <span m=''137600''>checking.</span> <span m=''137930''>And</span> <span m=''138380''>see,</span>
  <span m=''138550''>these</span> <span m=''138750''>operations</span> <span m=''139240''>are</span>
  <span m=''139330''>so</span> <span m=''139580''>cheap</span> <span m=''140430''>that</span>
  <span m=''140600''>actually</span> <span m=''140900''>checking</span> <span m=''141260''>for</span>
  <span m=''141440''>overflow</span> <span m=''142510''>is</span> <span m=''142770''>perhaps</span>
  <span m=''144810''>as</span> <span m=''145170''>expensive</span> <span m=''145820''>as</span>
  <span m=''146210''>doing</span> <span m=''146420''>the</span> <span m=''146500''>rest</span>
  <span m=''146770''>of</span> <span m=''146820''>the</span> <span m=''146950''>operations</span>
  <span m=''147570''>themselves.</span> <span m=''148970''>Checking</span> <span m=''149500''>to</span>
  <span m=''149600''>see</span> <span m=''149750''>whether</span> <span m=''149920''>you</span>
  <span m=''150020''>went</span> <span m=''150190''>over</span> <span m=''150370''>the</span>
  <span m=''150700''>right</span> <span m=''150920''>end of</span> <span m=''151220''>the</span>
  <span m=''151740''>array</span> <span m=''152050''>here.</span> </p><p><span m=''153890''>So</span>
  <span m=''154160''>to</span> <span m=''154300''>free</span> <span m=''155820''>x
  bytes,</span> <span m=''156920''>you</span> <span m=''157050''>basically</span>
  <span m=''157610''>just</span> <span m=''157800''>simply</span> <span m=''158820''>decrement</span>
  <span m=''159560''>the</span> <span m=''159640''>stack</span> <span m=''160050''>pointer.</span>
  <span m=''161930''>And</span> <span m=''162080''>of</span> <span m=''162170''>course,</span>
  <span m=''162460''>technically,</span> <span m=''162940''>you</span> <span m=''163020''>should</span>
  <span m=''163170''>also</span> <span m=''163430''>check</span> <span m=''163740''>for</span>
  <span m=''163900''>underflow,</span> <span m=''165190''>make</span> <span m=''165360''>sure</span>
  <span m=''165890''>somebody</span> <span m=''166190''>didn''t</span> <span m=''166350''>say</span>
  <span m=''166600''>to</span> <span m=''166700''>deallocate</span> <span m=''168120''>more</span>
  <span m=''169120''>bytes</span> <span m=''169700''>than</span> <span m=''169940''>were</span>
  <span m=''170140''>actually</span> <span m=''170740''>already</span> <span m=''171190''>allocated</span>
  <span m=''171730''>on</span> <span m=''171830''>the</span> <span m=''171930''>stack.</span>
  <span m=''175030''>And</span> <span m=''175680''>so</span> <span m=''175990''>course,</span>
  <span m=''176280''>check for</span> <span m=''176650''>stack</span> <span m=''176980''>underflow.</span>
  </p><p><span m=''178290''>So</span> <span m=''178710''>this</span> <span m=''179040''>is</span>
  <span m=''179190''>pretty</span> <span m=''179410''>good,</span> <span m=''179660''>because</span>
  <span m=''180130''>allocating</span> <span m=''180960''>and</span> <span m=''181200''>freeing</span>
  <span m=''181790''>take</span> <span m=''182530''>just</span> <span m=''182760''>constant</span>
  <span m=''183210''>time.</span> <span m=''183850''>Very</span> <span m=''184130''>quick.</span>
  <span m=''186230''>But</span> <span m=''186720''>you''re</span> <span m=''186890''>required</span>
  <span m=''187740''>to</span> <span m=''188630''>free</span> <span m=''189710''>memory</span>
  <span m=''190150''>consistent</span> <span m=''190760''>with</span> <span m=''190870''>the</span>
  <span m=''190990''>stack</span> <span m=''191470''>discipline,</span> <span m=''191960''>which</span>
  <span m=''192170''>is</span> <span m=''192280''>the</span> <span m=''193760''>last</span>
  <span m=''194200''>in,</span> <span m=''195010''>first</span> <span m=''195390''>out</span>
  <span m=''195910''>discipline.</span> <span m=''197110''>So</span> <span m=''197300''>you</span>
  <span m=''197430''>don''t</span> <span m=''197610''>get</span> <span m=''197720''>to</span>
  <span m=''197830''>free</span> <span m=''198150''>something</span> <span m=''199900''>that</span>
  <span m=''200230''>you</span> <span m=''200850''>allocated</span> <span m=''201400''>long</span>
  <span m=''201710''>ago</span> <span m=''202150''>until</span> <span m=''202350''>you''ve</span>
  <span m=''202460''>freed</span> <span m=''202730''>everything</span> <span m=''203120''>else</span>
  <span m=''203330''>that''s</span> <span m=''203580''>been</span> <span m=''205460''>allocated</span>
  <span m=''206040''>since.</span> <span m=''207960''>So</span> <span m=''208670''>therefore,</span>
  <span m=''209030''>it</span> <span m=''209140''>has</span> <span m=''209250''>limited</span>
  <span m=''209670''>applicability,</span> <span m=''210920''>but</span> <span m=''211030''>it''s</span>
  <span m=''211210''>great</span> <span m=''211520''>when</span> <span m=''211650''>it</span>
  <span m=''211740''>works.</span> </p><p><span m=''213160''>Now</span> <span m=''213290''>it</span>
  <span m=''213400''>turns</span> <span m=''213690''>out,</span> <span m=''213870''>sometimes</span>
  <span m=''214380''>you</span> <span m=''214490''>can</span> <span m=''214630''>actually</span>
  <span m=''214980''>use</span> <span m=''215480''>the</span> <span m=''217700''>call</span>
  <span m=''218010''>stack</span> <span m=''218440''>yourself</span> <span m=''219420''>to</span>
  <span m=''221930''>store</span> <span m=''222230''>stack</span> <span m=''223130''>values,</span>
  <span m=''225190''>using</span> <span m=''225610''>a</span> <span m=''225670''>function</span>
  <span m=''226070''>called</span> <span m=''226370''>alloca.</span> <span m=''227570''>But</span>
  <span m=''227880''>this</span> <span m=''228100''>function</span> <span m=''228470''>is</span>
  <span m=''228630''>now</span> <span m=''228870''>deprecated,</span> <span m=''229870''>meaning</span>
  <span m=''230230''>that</span> <span m=''230780''>people</span> <span m=''231090''>advise</span>
  <span m=''231540''>you</span> <span m=''231670''>not</span> <span m=''231970''>to</span>
  <span m=''232070''>use</span> <span m=''232380''>it</span> <span m=''232480''>in</span>
  <span m=''232610''>any</span> <span m=''232790''>modern</span> <span m=''233210''>programming.</span>
  <span m=''234520''>And</span> <span m=''234660''>part</span> <span m=''234860''>of</span>
  <span m=''234920''>the</span> <span m=''234990''>reason</span> <span m=''235440''>is</span>
  <span m=''235980''>that</span> <span m=''236140''>the</span> <span m=''236230''>compiler</span>
  <span m=''236910''>is</span> <span m=''237110''>more</span> <span m=''237350''>efficient</span>
  <span m=''238510''>with</span> <span m=''238720''>fixed</span> <span m=''238990''>size</span>
  <span m=''239320''>stack</span> <span m=''239810''>frames.</span> <span m=''240330''>You</span>
  <span m=''240450''>remember</span> <span m=''240780''>when</span> <span m=''240950''>we</span>
  <span m=''241040''>went</span> <span m=''241370''>through</span> <span m=''242970''>how</span>
  <span m=''243240''>the</span> <span m=''243480''>compiler</span> <span m=''244150''>actually</span>
  <span m=''244810''>lays</span> <span m=''245210''>out</span> <span m=''245500''>memory</span>
  <span m=''245950''>and</span> <span m=''246160''>does</span> <span m=''246350''>the</span>
  <span m=''246440''>calling</span> <span m=''246860''>convention?</span> <span m=''248660''>If</span>
  <span m=''248900''>you</span> <span m=''249010''>have</span> <span m=''249130''>a</span>
  <span m=''249170''>fixed</span> <span m=''249460''>size</span> <span m=''249730''>stack</span>
  <span m=''250160''>frame,</span> <span m=''250910''>then</span> <span m=''251230''>the</span>
  <span m=''251740''>frame</span> <span m=''252100''>pointer</span> <span m=''252590''>and</span>
  <span m=''252670''>the</span> <span m=''252740''>stack</span> <span m=''253180''>pointer</span>
  <span m=''253560''>are</span> <span m=''253720''>redundant,</span> <span m=''254350''>and</span>
  <span m=''254500''>so</span> <span m=''254610''>you</span> <span m=''254750''>can</span>
  <span m=''254880''>reclaim</span> <span m=''255330''>a</span> <span m=''255400''>register,</span>
  <span m=''256040''>namely,</span> <span m=''256920''>the</span> <span m=''257459''>frame</span>
  <span m=''257779''>pointer</span> <span m=''258120''>register,</span> <span m=''258930''>and</span>
  <span m=''259160''>do</span> <span m=''259300''>everything</span> <span m=''259740''>off</span>
  <span m=''259950''>the</span> <span m=''260050''>stack</span> <span m=''260490''>pointer.</span>
  <span m=''260769''>But</span> <span m=''260910''>if</span> <span m=''261000''>you</span>
  <span m=''261130''>use</span> <span m=''261529''>things</span> <span m=''261779''>like</span>
  <span m=''261990''>alloca,</span> <span m=''262680''>which</span> <span m=''262980''>are</span>
  <span m=''263060''>pushing</span> <span m=''263470''>the</span> <span m=''263550''>sides</span>
  <span m=''263970''>of</span> <span m=''264040''>the</span> <span m=''264120''>stack</span>
  <span m=''264620''>frame,</span> <span m=''265140''>then</span> <span m=''265340''>you</span>
  <span m=''265440''>actually</span> <span m=''265740''>have</span> <span m=''265910''>to</span>
  <span m=''266090''>keep</span> <span m=''266360''>both</span> <span m=''266670''>pointers</span>
  <span m=''267140''>there,</span> <span m=''267350''>and</span> <span m=''267410''>that''s</span>
  <span m=''267610''>a</span> <span m=''267660''>little</span> <span m=''267860''>bit</span>
  <span m=''268020''>less</span> <span m=''268270''>efficient</span> <span m=''269080''>in</span>
  <span m=''269270''>terms</span> <span m=''269590''>of</span> <span m=''269670''>the</span>
  <span m=''269770''>register</span> <span m=''270220''>usage.</span> <span m=''271480''>OK?</span>
  </p><p><span m=''271740''>So</span> <span m=''271920''>that''s</span> <span m=''272150''>pretty</span>
  <span m=''272370''>much</span> <span m=''272620''>stack</span> <span m=''272950''>storage.</span>
  <span m=''273370''>Any</span> <span m=''273520''>questions</span> <span m=''275100''>about</span>
  <span m=''275410''>stacks?</span> <span m=''275780''>Yeah?</span> </p><p><span m=''277210''>AUDIENCE:
  Is there anything</span> <span m=''277685''>that detects</span> <span m=''278635''>overflow</span>
  <span m=''279110''>or underflow</span> <span m=''279585''>without</span> <span m=''280060''>using</span>
  <span m=''280535''>inserts?</span> <span m=''281010''>Like, if you</span> <span
  m=''281485''>wanted to check--</span> </p><p><span m=''281960''>CHARLES LEISERSON:
  Yeah, you</span> <span m=''282435''>couldn''t check</span> <span m=''282910''>explicitly.</span>
  <span m=''283385''>Just</span> <span m=''283860''>say,</span> <span m=''284335''>you
  know,</span> <span m=''284810''>for</span> <span m=''285370''>this,</span> <span
  m=''285650''>is</span> <span m=''285940''>before you</span> <span m=''286245''>check</span>
  <span m=''286550''>that, make</span> <span m=''286840''>sure that</span> <span m=''288710''>SP</span>
  <span m=''289020''>plus</span> <span m=''289490''>x,</span> <span m=''289700''>is</span>
  <span m=''289910''>it</span> <span m=''290010''>bigger</span> <span m=''290280''>than</span>
  <span m=''290450''>the</span> <span m=''290520''>right</span> <span m=''290740''>end?</span>
  </p><p><span m=''291451''>AUDIENCE: But</span> <span m=''291892''>how do you know</span>
  <span m=''292333''>where the right</span> <span m=''292774''>end is?</span> </p><p><span
  m=''293880''>CHARLES LEISERSON: Well, because I''m</span> <span m=''294725''>assuming</span>
  <span m=''295130''>here that</span> <span m=''295510''>in</span> <span m=''295710''>this</span>
  <span m=''295930''>case,</span> <span m=''296300''>you</span> <span m=''296530''>are</span>
  <span m=''296920''>allocating it.</span> <span m=''297920''>Now,</span> <span m=''298510''>if</span>
  <span m=''298680''>you''re</span> <span m=''298800''>talking</span> <span m=''299140''>about</span>
  <span m=''299410''>using</span> <span m=''299640''>the</span> <span m=''299730''>call</span>
  <span m=''300010''>stack,</span> <span m=''300380''>you</span> <span m=''300480''>mean?</span>
  <span m=''301650''>You''ll</span> <span m=''301850''>never</span> <span m=''302100''>run</span>
  <span m=''302310''>out.</span> <span m=''302840''>We''ll</span> <span m=''303150''>do</span>
  <span m=''303270''>that</span> <span m=''303440''>analysis</span> <span m=''304020''>in</span>
  <span m=''304100''>a</span> <span m=''304160''>little</span> <span m=''304370''>bit.</span>
  <span m=''304620''>But</span> <span m=''304740''>you''ll</span> <span m=''304870''>never</span>
  <span m=''305160''>run</span> <span m=''305420''>out</span> <span m=''305730''>of</span>
  <span m=''306460''>stack</span> <span m=''306860''>space.</span> <span m=''308470''>Although</span>
  <span m=''309050''>as</span> <span m=''309160''>a</span> <span m=''309280''>practical</span>
  <span m=''309830''>matter,</span> <span m=''310640''>most</span> <span m=''311270''>compilers</span>
  <span m=''312240''>assume</span> <span m=''312670''>a</span> <span m=''312720''>stack</span>
  <span m=''313210''>of</span> <span m=''313290''>a</span> <span m=''313690''>megabyte,</span>
  <span m=''314420''>and</span> <span m=''314650''>so</span> <span m=''315200''>if</span>
  <span m=''315350''>you</span> <span m=''315510''>overflow</span> <span m=''316050''>that,</span>
  <span m=''321270''>your</span> <span m=''321420''>program</span> <span m=''321820''>will</span>
  <span m=''321940''>fail</span> <span m=''322460''>in</span> <span m=''322830''>any</span>
  <span m=''323050''>of</span> <span m=''323140''>a</span> <span m=''323200''>variety</span>
  <span m=''323580''>of</span> <span m=''323650''>ways.</span> </p><p><span m=''324140''>AUDIENCE:
  You</span> <span m=''324603''>can</span> <span m=''324757''>do</span> <span m=''324911''>guard</span>
  <span m=''325066''>pages.</span> </p><p><span m=''325530''>CHARLES LEISERSON: You</span>
  <span m=''325660''>can</span> <span m=''325750''>do</span> <span m=''325860''>guard</span>
  <span m=''326590''>pages,</span> <span m=''327020''>which</span> <span m=''327250''>don''t</span>
  <span m=''327460''>always</span> <span m=''327780''>work.</span> <span m=''329260''>But
  let me</span> <span m=''329760''>explain</span> <span m=''330160''>guard</span>
  <span m=''330450''>pages,</span> <span m=''331170''>OK?</span> </p><p><span m=''331800''>So</span>
  <span m=''333300''>what''s</span> <span m=''333490''>sometimes</span> <span m=''334110''>done</span>
  <span m=''338020''>is,</span> <span m=''338570''>if</span> <span m=''338750''>I
  have</span> <span m=''338850''>my</span> <span m=''339010''>stack</span> <span m=''339500''>growing</span>
  <span m=''339790''>down</span> <span m=''340070''>in</span> <span m=''340160''>memory--</span>
  <span m=''341450''>OK,</span> <span m=''341770''>so</span> <span m=''341890''>here''s</span>
  <span m=''342150''>my</span> <span m=''342300''>stack,</span> <span m=''344240''>and</span>
  <span m=''344370''>it''s</span> <span m=''344510''>growing</span> <span m=''344860''>this</span>
  <span m=''345060''>way--</span> <span m=''345720''>and</span> <span m=''345870''>I</span>
  <span m=''345900''>want</span> <span m=''346120''>to</span> <span m=''346170''>make</span>
  <span m=''346360''>sure,</span> <span m=''346610''>for</span> <span m=''346740''>example,</span>
  <span m=''347260''>the</span> <span m=''347370''>thing</span> <span m=''347580''>that''s</span>
  <span m=''347750''>typically</span> <span m=''348130''>growing</span> <span m=''348460''>up</span>
  <span m=''348610''>this</span> <span m=''348790''>way</span> <span m=''348980''>is</span>
  <span m=''349100''>heat,</span> <span m=''350510''>and</span> <span m=''350740''>I</span>
  <span m=''350790''>want</span> <span m=''350960''>to</span> <span m=''351010''>make</span>
  <span m=''351200''>sure</span> <span m=''351390''>that</span> <span m=''351570''>they</span>
  <span m=''351700''>don''t</span> <span m=''352120''>collide</span> <span m=''352590''>somewhere</span>
  <span m=''352920''>in</span> <span m=''353000''>here.</span> </p><p><span m=''354290''>So</span>
  <span m=''354450''>one</span> <span m=''354630''>thing</span> <span m=''354820''>I</span>
  <span m=''354900''>can</span> <span m=''355090''>do</span> <span m=''355840''>is</span>
  <span m=''356030''>put</span> <span m=''356240''>some</span> <span m=''356410''>pages</span>
  <span m=''356900''>in</span> <span m=''357000''>here</span> <span m=''357950''>that</span>
  <span m=''358110''>are</span> <span m=''358250''>protected.</span> <span m=''360480''>These</span>
  <span m=''360800''>are</span> <span m=''361760''>read-only</span> <span m=''362390''>pages.</span>
  <span m=''363430''>Or</span> <span m=''363840''>actually</span> <span m=''364180''>even</span>
  <span m=''364390''>better</span> <span m=''364760''>is</span> <span m=''365820''>no</span>
  <span m=''365990''>permissions.</span> <span m=''369450''>So</span> <span m=''369550''>I</span>
  <span m=''369600''>can</span> <span m=''369740''>put</span> <span m=''370010''>no</span>
  <span m=''370180''>permissions</span> <span m=''371830''>so that</span> <span m=''372050''>if</span>
  <span m=''372230''>you</span> <span m=''372380''>ever</span> <span m=''372560''>try</span>
  <span m=''372780''>to</span> <span m=''372860''>read or write</span> <span m=''373480''>that</span>
  <span m=''373710''>page,</span> <span m=''374260''>it</span> <span m=''374400''>automatically</span>
  <span m=''375040''>generates</span> <span m=''376230''>a</span> <span m=''376720''>fault.</span>
  <span m=''377600''>And</span> <span m=''377840''>so</span> <span m=''377970''>the</span>
  <span m=''378050''>runtime</span> <span m=''378570''>will</span> <span m=''378680''>sometimes</span>
  <span m=''379240''>do</span> <span m=''379400''>that.</span> </p><p><span m=''379980''>The</span>
  <span m=''380090''>difficulty</span> <span m=''380720''>is,</span> <span m=''380860''>what</span>
  <span m=''381000''>happens</span> <span m=''381400''>if</span> <span m=''381490''>you</span>
  <span m=''381620''>increased</span> <span m=''382020''>your</span> <span m=''382140''>stack</span>
  <span m=''382480''>so</span> <span m=''382640''>much</span> <span m=''382900''>that</span>
  <span m=''383010''>you</span> <span m=''383100''>went</span> <span m=''383300''>beyond</span>
  <span m=''384440''>your</span> <span m=''384750''>guard</span> <span m=''385050''>pages?</span>
  <span m=''385590''>But</span> <span m=''385800''>as</span> <span m=''385940''>a</span>
  <span m=''386080''>practical</span> <span m=''386630''>matter</span> <span m=''387330''>most</span>
  <span m=''387510''>of</span> <span m=''387690''>the</span> <span m=''387790''>times</span>
  <span m=''388110''>that</span> <span m=''388260''>people</span> <span m=''388590''>exceed</span>
  <span m=''389480''>the</span> <span m=''390160''>guard</span> <span m=''390470''>pages</span>
  <span m=''391050''>is</span> <span m=''393360''>only</span> <span m=''393620''>by</span>
  <span m=''393820''>small</span> <span m=''394240''>amount.</span> <span m=''394920''>And</span>
  <span m=''395050''>so</span> <span m=''395140''>just</span> <span m=''395320''>putting</span>
  <span m=''395550''>a</span> <span m=''395600''>few</span> <span m=''395860''>guard</span>
  <span m=''396180''>pages</span> <span m=''396570''>in</span> <span m=''396710''>there</span>
  <span m=''397130''>will</span> <span m=''397330''>make</span> <span m=''397530''>sure</span>
  <span m=''398330''>that</span> <span m=''398750''>you</span> <span m=''400650''>can</span>
  <span m=''400830''>use</span> <span m=''401180''>the</span> <span m=''401300''>memory</span>
  <span m=''402160''>management</span> <span m=''402670''>hardware,</span> <span m=''403870''>which</span>
  <span m=''404450''>basically</span> <span m=''404940''>ends</span> <span m=''405130''>up</span>
  <span m=''405200''>being</span> <span m=''405430''>free</span> <span m=''406420''>from</span>
  <span m=''406590''>your</span> <span m=''406760''>point</span> <span m=''407020''>of</span>
  <span m=''407100''>view</span> <span m=''407360''>as</span> <span m=''407460''>a</span>
  <span m=''407560''>programmer,</span> <span m=''408530''>in</span> <span m=''408680''>order</span>
  <span m=''408920''>to</span> <span m=''409100''>catch</span> <span m=''409520''>a</span>
  <span m=''410180''>stack</span> <span m=''410600''>overflow</span> <span m=''411010''>problem.</span>
  </p><p><span m=''412490''>And</span> <span m=''412660''>you</span> <span m=''412780''>can</span>
  <span m=''412900''>do</span> <span m=''413010''>that</span> <span m=''413240''>yourself.</span>
  <span m=''413770''>You</span> <span m=''413900''>can</span> <span m=''414040''>use</span>
  <span m=''415600''>the</span> <span m=''416360''>call</span> <span m=''416900''>mmap,</span>
  <span m=''420010''>which</span> <span m=''420700''>we</span> <span m=''420760''>haven''t</span>
  <span m=''420970''>talked</span> <span m=''421240''>about,</span> <span m=''421920''>to</span>
  <span m=''422200''>set</span> <span m=''422800''>permissions</span> <span m=''423470''>on</span>
  <span m=''424270''>pages</span> <span m=''424740''>at</span> <span m=''424890''>user</span>
  <span m=''425170''>level.</span> </p><p><span m=''427860''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''430660''>CHARLES LEISERSON: No.</span> <span m=''430840''>You</span>
  <span m=''430980''>can</span> <span m=''431120''>actually</span> <span m=''431730''>handle</span>
  <span m=''434030''>the</span> <span m=''434180''>error</span> <span m=''434390''>however</span>
  <span m=''434690''>you</span> <span m=''434810''>want.</span> <span m=''435090''>You</span>
  <span m=''435210''>can</span> <span m=''435330''>vector</span> <span m=''435700''>into</span>
  <span m=''436430''>a</span> <span m=''436560''>user</span> <span m=''436900''>to
  find</span> <span m=''437310''>routine.</span> <span m=''437610''>Now,</span> <span
  m=''437760''>what</span> <span m=''437890''>are</span> <span m=''437910''>you</span>
  <span m=''438000''>going</span> <span m=''438090''>to</span> <span m=''438190''>do,</span>
  <span m=''438450''>I</span> <span m=''438680''>don''t</span> <span m=''438920''>know,</span>
  <span m=''441060''>but</span> <span m=''441520''>you</span> <span m=''441650''>can</span>
  <span m=''441780''>indeed</span> <span m=''445760''>catch</span> <span m=''446120''>the</span>
  <span m=''446290''>error</span> <span m=''446470''>yourself</span> <span m=''447060''>and</span>
  <span m=''447650''>decide</span> <span m=''448310''>that</span> <span m=''448480''>there''s</span>
  <span m=''449830''>some</span> <span m=''450030''>way</span> <span m=''450180''>of</span>
  <span m=''450290''>recovering,</span> <span m=''450780''>as</span> <span m=''450920''>opposed</span>
  <span m=''451380''>to</span> <span m=''452260''>crashing</span> <span m=''452710''>and</span>
  <span m=''452800''>burning.</span> <span m=''453540''>So</span> <span m=''453750''>generally,</span>
  <span m=''454800''>it''s</span> <span m=''455270''>considered</span> <span m=''455740''>poor</span>
  <span m=''456010''>form</span> <span m=''456390''>for</span> <span m=''456510''>your</span>
  <span m=''456670''>software</span> <span m=''457450''>to</span> <span m=''458320''>fail,</span>
  <span m=''459170''>other</span> <span m=''459470''>than</span> <span m=''459770''>in</span>
  <span m=''459960''>a</span> <span m=''460030''>controlled</span> <span m=''460540''>way.</span>
  </p><p><span m=''462130''>So</span> <span m=''462280''>you</span> <span m=''462420''>should</span>
  <span m=''462600''>always</span> <span m=''462980''>have</span> <span m=''463120''>your</span>
  <span m=''463240''>software</span> <span m=''463730''>exiting</span> <span m=''464630''>or</span>
  <span m=''464930''>calling</span> <span m=''465370''>error,</span> <span m=''466280''>and</span>
  <span m=''466450''>it</span> <span m=''466530''>should</span> <span m=''466760''>never</span>
  <span m=''467480''>segment</span> <span m=''467940''>fault.</span> <span m=''470310''>Most</span>
  <span m=''470620''>people</span> <span m=''470890''>consider</span> <span m=''471290''>any</span>
  <span m=''471800''>program</span> <span m=''472280''>that</span> <span m=''472465''>segfaults</span>
  <span m=''472930''>to</span> <span m=''473020''>be</span> <span m=''474260''>poorly</span>
  <span m=''474630''>engineered.</span> <span m=''477420''>Is</span> <span m=''477540''>there</span>
  <span m=''477650''>any</span> <span m=''477780''>case</span> <span m=''478060''>where</span>
  <span m=''478200''>there''s</span> <span m=''478460''>a</span> <span m=''478510''>segfaulting</span>
  <span m=''479180''>program</span> <span m=''479590''>that</span> <span m=''479700''>is</span>
  <span m=''479810''>not</span> <span m=''480080''>poorly</span> <span m=''480390''>engineered?</span>
  <span m=''482700''>I</span> <span m=''482740''>don''t</span> <span m=''482890''>know.</span>
  <span m=''483400''>I</span> <span m=''483920''>think</span> <span m=''484580''>most</span>
  <span m=''484850''>people,</span> <span m=''485110''>it''s</span> <span m=''485200''>probably</span>
  <span m=''485580''>an</span> <span m=''486490''>understatement.</span> <span m=''488450''>OK?</span>
  </p><p><span m=''491580''>So</span> <span m=''491750''>this</span> <span m=''491940''>is</span>
  <span m=''492050''>stack</span> <span m=''492530''>memory.  You can</span> <span
  m=''492920''>build it</span> <span m=''493250''>yourself</span> <span m=''493770''>out</span>
  <span m=''494060''>of an array</span> <span m=''494560''>and</span> <span m=''494670''>a</span>
  <span m=''494710''>pointer,</span> <span m=''496410''>or</span> <span m=''498150''>you</span>
  <span m=''498320''>can</span> <span m=''498760''>I</span> <span m=''498990''>use</span>
  <span m=''499320''>this</span> <span m=''499620''>the</span> <span m=''499770''>call</span>
  <span m=''500060''>stack.</span> <span m=''501820''>And</span> <span m=''502950''>when</span>
  <span m=''503200''>you</span> <span m=''503320''>have</span> <span m=''503440''>something</span>
  <span m=''503850''>that''s</span> <span m=''504000''>using</span> <span m=''504380''>that</span>
  <span m=''504590''>kind</span> <span m=''504930''>of</span> <span m=''505920''>discipline,</span>
  <span m=''506400''>it''s</span> <span m=''506570''>great,</span> <span m=''506890''>because</span>
  <span m=''507050''>it''s</span> <span m=''507170''>really</span> <span m=''507450''>cheap.</span>
  </p><p><span m=''511040''>Now</span> <span m=''512010''>in</span> <span m=''512220''>C</span>
  <span m=''512690''>and</span> <span m=''513490''>C++,</span> <span m=''515110''>and</span>
  <span m=''515309''>we''re</span> <span m=''515400''>going</span> <span m=''515480''>to</span>
  <span m=''515520''>start</span> <span m=''515789''>moving</span> <span m=''516120''>and</span>
  <span m=''516200''>talking</span> <span m=''516630''>more</span> <span m=''516840''>about</span>
  <span m=''517190''>things</span> <span m=''517400''>like</span> <span m=''517559''>C++,</span>
  <span m=''519650''>we</span> <span m=''520020''>have</span> <span m=''520150''>what''s</span>
  <span m=''520340''>called</span> <span m=''520690''>heap</span> <span m=''520919''>allocation.</span>
  <span m=''522970''>And in</span> <span m=''523299''>C,</span> <span m=''523640''>the</span>
  <span m=''524370''>routines</span> <span m=''525040''>are</span> <span m=''525180''>called</span>
  <span m=''525550''>malloc</span> <span m=''526020''>and</span> <span m=''526170''>free,</span>
  <span m=''527100''>and</span> <span m=''527780''>C++</span> <span m=''528160''>provides</span>
  <span m=''528760''>a</span> <span m=''529580''>new</span> <span m=''530510''>directive</span>
  <span m=''531430''>and</span> <span m=''531660''>delete.</span> <span m=''532750''>So</span>
  <span m=''532960''>unlike</span> <span m=''533560''>Java</span> <span m=''534010''>and</span>
  <span m=''534210''>Python,</span> <span m=''536120''>C</span> <span m=''536600''>and</span>
  <span m=''536770''>C++</span> <span m=''537610''>provide</span> <span m=''538120''>no</span>
  <span m=''538300''>garbage</span> <span m=''538810''>collector.</span> <span m=''541050''>So</span>
  <span m=''541540''>in</span> <span m=''541710''>other</span> <span m=''541860''>words,</span>
  <span m=''542380''>you''re</span> <span m=''542680''>responsible</span> <span m=''544270''>as</span>
  <span m=''544400''>a</span> <span m=''544540''>programmer</span> <span m=''545190''>for</span>
  <span m=''545480''>freeing</span> <span m=''546510''>allocated</span> <span m=''547180''>storage</span>
  <span m=''547740''>yourself.</span> <span m=''548490''>If</span> <span m=''548620''>you</span>
  <span m=''548750''>fail</span> <span m=''549230''>to</span> <span m=''549360''>do</span>
  <span m=''549590''>so,</span> <span m=''550550''>you</span> <span m=''550670''>create</span>
  <span m=''551050''>a</span> <span m=''551090''>memory</span> <span m=''551440''>leak.</span>
  <span m=''553150''>So a</span> <span m=''553230''>memory</span> <span m=''553550''>leak</span>
  <span m=''553820''>means</span> <span m=''554160''>I</span> <span m=''554270''>allocated</span>
  <span m=''554860''>something,</span> <span m=''555740''>I</span> <span m=''555890''>no</span>
  <span m=''556130''>longer am</span> <span m=''556600''>in</span> <span m=''557020''>a</span>
  <span m=''557080''>position</span> <span m=''557550''>to</span> <span m=''557610''>use</span>
  <span m=''558000''>it,</span> <span m=''558160''>but</span> <span m=''558270''>I</span>
  <span m=''558340''>failed</span> <span m=''558820''>to</span> <span m=''558950''>free</span>
  <span m=''559270''>it,</span> <span m=''559650''>so</span> <span m=''559820''>it</span>
  <span m=''559910''>can''t</span> <span m=''560230''>be</span> <span m=''560360''>reused.</span>
  </p><p><span m=''562530''>And if</span> <span m=''563000''>you</span> <span m=''563080''>keep</span>
  <span m=''563360''>doing</span> <span m=''563680''>that,</span> <span m=''563890''>especially</span>
  <span m=''564270''>if</span> <span m=''564360''>you''re</span> <span m=''564570''>in
  a</span> <span m=''564650''>loop,</span> <span m=''565970''>then you</span> <span
  m=''566170''>have</span> <span m=''566380''>a memory</span> <span m=''566800''>leak.</span>
  <span m=''567080''>Where</span> <span m=''567410''>if</span> <span m=''567590''>you</span>
  <span m=''567710''>look</span> <span m=''567950''>at</span> <span m=''568150''>a</span>
  <span m=''568500''>program</span> <span m=''568930''>with</span> <span m=''569070''>a</span>
  <span m=''569110''>memory</span> <span m=''569450''>leak, and</span> <span m=''569840''>you</span>
  <span m=''570120''>look</span> <span m=''571190''>using</span> <span m=''571520''>[?
  Top ?]</span> <span m=''571880''>or</span> <span m=''571970''>whatever,</span> <span
  m=''572580''>how</span> <span m=''572760''>big</span> <span m=''572990''>is</span>
  <span m=''573090''>my</span> <span m=''573240''>program,</span> <span m=''574500''>you</span>
  <span m=''574640''>watch</span> <span m=''574930''>as</span> <span m=''575080''>it</span>
  <span m=''575210''>goes</span> <span m=''575560''>and</span> <span m=''575650''>computes</span>
  <span m=''576070''>and</span> <span m=''576180''>computes,</span> <span m=''576460''>and
  it</span> <span m=''576740''>keeps</span> <span m=''576990''>getting</span> <span
  m=''577230''>bigger</span> <span m=''577610''>and</span> <span m=''577720''>bigger</span>
  <span m=''578080''>and</span> <span m=''578180''>bigger</span> <span m=''578520''>and</span>
  <span m=''578620''>bigger</span> <span m=''578960''>as</span> <span m=''579070''>it''s</span>
  <span m=''579210''>running,</span> <span m=''580120''>and it</span> <span m=''580260''>just</span>
  <span m=''580450''>runs</span> <span m=''580750''>away,</span> <span m=''581090''>getting</span>
  <span m=''581410''>more</span> <span m=''581630''>and</span> <span m=''581700''>more</span>
  <span m=''582120''>storage.</span> </p><p><span m=''584390''>Also</span> <span m=''585190''>you</span>
  <span m=''585320''>have</span> <span m=''585480''>to</span> <span m=''585650''>watch</span>
  <span m=''586000''>out</span> <span m=''586260''>for</span> <span m=''586360''>things</span>
  <span m=''586670''>like</span> <span m=''586890''>dangling</span> <span m=''587430''>pointers.</span>
  <span m=''588590''>That</span> <span m=''588730''>is,</span> <span m=''588910''>you</span>
  <span m=''589090''>deallocated</span> <span m=''590050''>something,</span> <span
  m=''590490''>but</span> <span m=''590660''>somebody</span> <span m=''591070''>still</span>
  <span m=''591490''>wanted</span> <span m=''591790''>to</span> <span m=''591880''>use</span>
  <span m=''592190''>it.</span> <span m=''594590''>Or</span> <span m=''595740''>double-freeing.</span>
  <span m=''597750''>You</span> <span m=''597850''>have</span> <span m=''597960''>two</span>
  <span m=''598140''>places</span> <span m=''598580''>in the code</span> <span m=''598875''>where</span>
  <span m=''599170''>you</span> <span m=''599410''>free</span> <span m=''599720''>the</span>
  <span m=''599830''>same</span> <span m=''600410''>storage.</span> <span m=''602720''>Very</span>
  <span m=''603050''>bad</span> <span m=''603990''>to</span> <span m=''604090''>try</span>
  <span m=''604290''>to</span> <span m=''604360''>free</span> <span m=''604580''>the</span>
  <span m=''604660''>same</span> <span m=''604920''>storage.</span> <span m=''607310''>Yeah?</span>
  </p><p><span m=''608826''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''612040''>CHARLES
  LEISERSON: It''s</span> <span m=''612270''>basically</span> <span m=''614240''>going</span>
  <span m=''614340''>to</span> <span m=''614380''>be</span> <span m=''614470''>sitting</span>
  <span m=''614860''>in</span> <span m=''615390''>the</span> <span m=''616100''>storage</span>
  <span m=''616520''>structure,</span> <span m=''617510''>which</span> <span m=''617670''>we''ll</span>
  <span m=''617780''>talk</span> <span m=''618010''>about</span> <span m=''618200''>how</span>
  <span m=''618360''>those</span> <span m=''618570''>are</span> <span m=''618630''>organized</span>
  <span m=''619300''>in</span> <span m=''619380''>a</span> <span m=''619420''>few</span>
  <span m=''619620''>minutes--</span> <span m=''620515''>going</span> <span m=''620930''>to</span>
  <span m=''620970''>be</span> <span m=''621040''>sitting</span> <span m=''621270''>in</span>
  <span m=''621340''>the</span> <span m=''621390''>storage</span> <span m=''621710''>structure,</span>
  <span m=''622510''>but</span> <span m=''622780''>the</span> <span m=''622970''>program</span>
  <span m=''623610''>that</span> <span m=''623810''>is</span> <span m=''624000''>going</span>
  <span m=''624860''>to</span> <span m=''624920''>look</span> <span m=''625120''>at</span>
  <span m=''625190''>that</span> <span m=''625380''>and</span> <span m=''625480''>not</span>
  <span m=''625700''>recognize</span> <span m=''626430''>that</span> <span m=''626570''>it''s</span>
  <span m=''626700''>in</span> <span m=''626770''>the</span> <span m=''626850''>storage</span>
  <span m=''627170''>structure,</span> <span m=''627860''>and</span> <span m=''628060''>think</span>
  <span m=''628300''>that</span> <span m=''628420''>it''s</span> <span m=''628590''>something</span>
  <span m=''628930''>that</span> <span m=''629170''>now</span> <span m=''629460''>all</span>
  <span m=''629720''>its</span> <span m=''629860''>pointers</span> <span m=''630270''>can</span>
  <span m=''630400''>be</span> <span m=''630540''>reset.</span> <span m=''631370''>And</span>
  <span m=''631500''>so</span> <span m=''631570''>you</span> <span m=''631670''>basically</span>
  <span m=''632610''>clobber</span> <span m=''633110''>all</span> <span m=''633260''>the</span>
  <span m=''633380''>invariants</span> <span m=''633840''>of</span> <span m=''633890''>the</span>
  <span m=''633950''>storage</span> <span m=''634240''>structure,</span> <span m=''634680''>and</span>
  <span m=''634920''>somewhere</span> <span m=''635320''>down</span> <span m=''635610''>the</span>
  <span m=''635940''>road,</span> <span m=''636540''>you</span> <span m=''636660''>get</span>
  <span m=''636780''>a</span> <span m=''636820''>segment</span> <span m=''637230''>fault</span>
  <span m=''637500''>or</span> <span m=''637580''>something.</span> <span m=''638950''>OK?</span>
  <span m=''639720''>Yeah,</span> <span m=''639950''>John?</span> </p><p><span m=''640762''>AUDIENCE:
  [UNINTELLIGIBLE]</span> <span m=''642238''>that</span> <span m=''642730''>comes
  out of</span> <span m=''643222''>that is--</span> </p><p><span m=''643714''>CHARLES
  LEISERSON: Just a second.</span> <span m=''644206''>Why don''t you</span> <span
  m=''644698''>take this?</span> </p><p><span m=''648634''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''657500''>One</span> <span m=''657800''>thing</span> <span m=''657970''>that</span>
  <span m=''658400''>often</span> <span m=''658740''>happens</span> <span m=''659150''>in</span>
  <span m=''659220''>the</span> <span m=''659300''>real</span> <span m=''659520''>world</span>
  <span m=''659860''>is</span> <span m=''660140''>when</span> <span m=''660300''>you</span>
  <span m=''660400''>free</span> <span m=''660680''>something,</span> <span m=''661070''>it</span>
  <span m=''661170''>adds</span> <span m=''661450''>it</span> <span m=''661550''>to</span>
  <span m=''661740''>a</span> <span m=''661870''>free,</span> <span m=''662220''>list</span>
  <span m=''662940''>and</span> <span m=''663460''>if</span> <span m=''663620''>you</span>
  <span m=''664570''>free</span> <span m=''664800''>something</span> <span m=''665110''>twice,</span>
  <span m=''665480''>it</span> <span m=''665600''>will</span> <span m=''665690''>add</span>
  <span m=''665790''>two</span> <span m=''665950''>copies</span> <span m=''666340''>of</span>
  <span m=''666440''>that</span> <span m=''666620''>pointer</span> <span m=''666990''>to</span>
  <span m=''667250''>the</span> <span m=''667350''>free</span> <span m=''667620''>list.</span>
  <span m=''668130''>So</span> <span m=''668340''>later</span> <span m=''668680''>on,</span>
  <span m=''668840''>when</span> <span m=''668990''>you</span> <span m=''669110''>malloc,</span>
  <span m=''669600''>malloc</span> <span m=''669990''>might</span> <span m=''670160''>return</span>
  <span m=''670540''>the</span> <span m=''670640''>same</span> <span m=''670970''>pointer</span>
  <span m=''671310''>to</span> <span m=''671420''>you</span> <span m=''671560''>twice.</span>
  <span m=''672400''>So</span> <span m=''673500''>the</span> <span m=''673690''>same</span>
  <span m=''674110''>memory</span> <span m=''674490''>block</span> <span m=''674810''>might</span>
  <span m=''675000''>be</span> <span m=''675120''>allocated</span> <span m=''675560''>for</span>
  <span m=''675680''>two</span> <span m=''675990''>completely</span> <span m=''676400''>different</span>
  <span m=''677430''>functionalities,</span> <span m=''677870''>and</span> <span m=''678800''>attackers</span>
  <span m=''679330''>use</span> <span m=''679610''>that</span> <span m=''679850''>to</span>
  <span m=''680740''>do</span> <span m=''680950''>all</span> <span m=''681110''>sorts</span>
  <span m=''681330''>of</span> <span m=''681430''>interesting</span> <span m=''681890''>things</span>
  <span m=''682180''>to your</span> <span m=''682340''>program.</span> </p><p><span
  m=''682770''>CHARLES LEISERSON: Yeah.</span> <span m=''684108''>OK?</span> </p><p><span
  m=''686000''>So</span> <span m=''687170''>fortunately,</span> <span m=''688100''>there</span>
  <span m=''688360''>are</span> <span m=''688950''>some</span> <span m=''689250''>really</span>
  <span m=''689510''>good--</span> <span m=''689680''>why don''t</span> <span m=''689830''>you</span>
  <span m=''689930''>keep</span> <span m=''690100''>that</span> <span m=''690280''>down</span>
  <span m=''690480''>there,</span> <span m=''690650''>and</span> <span m=''690720''>then</span>
  <span m=''691320''>if</span> <span m=''691910''>you</span> <span m=''692050''>guys</span>
  <span m=''692290''>want</span> <span m=''692500''>to</span> <span m=''693280''>chime</span>
  <span m=''693600''>in,</span> <span m=''693730''>you''ll</span> <span m=''693870''>have</span>
  <span m=''697290''>some</span> <span m=''697480''>power</span> <span m=''697780''>to</span>
  <span m=''697860''>do</span> <span m=''698010''>so.</span> <span m=''699660''>So</span>
  <span m=''699930''>fortunately,</span> <span m=''700380''>there</span> <span m=''700670''>are</span>
  <span m=''700780''>now</span> <span m=''702300''>some</span> <span m=''702530''>tools</span>
  <span m=''702980''>to</span> <span m=''703150''>make</span> <span m=''703400''>that</span>
  <span m=''703790''>easier</span> <span m=''704720''>to</span> <span m=''704850''>debug</span>
  <span m=''705300''>these</span> <span m=''705520''>kinds</span> <span m=''705840''>of</span>
  <span m=''706380''>really</span> <span m=''706650''>nasty</span> <span m=''707110''>bugs.</span>
  <span m=''708260''>The</span> <span m=''708360''>one</span> <span m=''708580''>we''ll</span>
  <span m=''708770''>be</span> <span m=''708880''>using</span> <span m=''709240''>is</span>
  <span m=''709380''>Valgrind,</span> <span m=''711270''>and</span> <span m=''711560''>what</span>
  <span m=''711710''>you</span> <span m=''711800''>do</span> <span m=''711980''>is</span>
  <span m=''712080''>you</span> <span m=''712200''>just</span> <span m=''712500''>say,</span>
  <span m=''712930''>Valgrind</span> <span m=''713605''>minus</span> <span m=''713940''>minus
  leak</span> <span m=''714440''>check</span> <span m=''714770''>equals</span> <span
  m=''715080''>yes,</span> <span m=''715820''>and</span> <span m=''715980''>then</span>
  <span m=''716190''>run</span> <span m=''716380''>your</span> <span m=''716520''>program</span>
  <span m=''717000''>the</span> <span m=''717100''>way</span> <span m=''717280''>you</span>
  <span m=''717400''>would</span> <span m=''717500''>normally</span> <span m=''717870''>run</span>
  <span m=''718370''>it.</span> <span m=''718950''>And</span> <span m=''719120''>what</span>
  <span m=''719270''>it</span> <span m=''719360''>will</span> <span m=''719490''>do</span>
  <span m=''719730''>is,</span> <span m=''719910''>it</span> <span m=''720030''>will</span>
  <span m=''720470''>monitor</span> <span m=''721600''>the</span> <span m=''721710''>way</span>
  <span m=''721960''>that</span> <span m=''722670''>the</span> <span m=''723270''>program</span>
  <span m=''723910''>is</span> <span m=''724160''>doing</span> <span m=''724440''>allocations</span>
  <span m=''725190''>and</span> <span m=''725310''>frees,</span> <span m=''727120''>and</span>
  <span m=''729360''>give</span> <span m=''729640''>you</span> <span m=''729770''>a</span>
  <span m=''729850''>report</span> <span m=''730330''>as</span> <span m=''730470''>to</span>
  <span m=''730580''>whether</span> <span m=''731280''>everything</span> <span m=''731710''>that</span>
  <span m=''731810''>was</span> <span m=''731910''>allocated</span> <span m=''732490''>was</span>
  <span m=''732690''>free,</span> <span m=''733610''>and</span> <span m=''734150''>whether</span>
  <span m=''734480''>you</span> <span m=''734620''>tried</span> <span m=''734800''>to</span>
  <span m=''734980''>free</span> <span m=''735220''>something</span> <span m=''735610''>twice,</span>
  <span m=''736030''>and</span> <span m=''736130''>so</span> <span m=''736330''>forth.</span>
  </p><p><span m=''737820''>Now,</span> <span m=''738020''>this</span> <span m=''738250''>works</span>
  <span m=''738770''>with</span> <span m=''740320''>the</span> <span m=''740550''>existing</span>
  <span m=''741060''>allocators.</span> <span m=''741830''>If</span> <span m=''741950''>you</span>
  <span m=''742970''>have</span> <span m=''743080''>your</span> <span m=''743290''>own</span>
  <span m=''743530''>allocator</span> <span m=''744110''>that</span> <span m=''744260''>you</span>
  <span m=''744340''>decide</span> <span m=''744730''>you''re</span> <span m=''744840''>going</span>
  <span m=''744980''>to</span> <span m=''745060''>write</span> <span m=''745520''>for</span>
  <span m=''745640''>a</span> <span m=''745690''>little</span> <span m=''745990''>piece</span>
  <span m=''746270''>of</span> <span m=''746360''>your</span> <span m=''746520''>code,</span>
  <span m=''746790''>you</span> <span m=''746860''>say,</span> <span m=''747040''>gee,</span>
  <span m=''747270''>I''m</span> <span m=''747400''>going</span> <span m=''747490''>to</span>
  <span m=''747750''>do</span> <span m=''747880''>my</span> <span m=''748040''>own</span>
  <span m=''748250''>little</span> <span m=''748510''>allocation</span> <span m=''749090''>here,</span>
  <span m=''749840''>you</span> <span m=''750030''>can</span> <span m=''750210''>actually</span>
  <span m=''750540''>communicate</span> <span m=''751110''>to Valgrind</span> <span
  m=''752340''>what</span> <span m=''752730''>that</span> <span m=''753620''>allocator</span>
  <span m=''754280''>is,</span> <span m=''754730''>and it</span> <span m=''754980''>can</span>
  <span m=''755160''>check</span> <span m=''755500''>for</span> <span m=''756030''>proper</span>
  <span m=''756320''>use</span> <span m=''756580''>of</span> <span m=''756660''>that</span>
  <span m=''756870''>structure</span> <span m=''757310''>as</span> <span m=''757430''>well.</span>
  <span m=''758670''>So</span> <span m=''758850''>you</span> <span m=''758990''>can</span>
  <span m=''759120''>see</span> <span m=''760180''>valgrind.org</span> <span m=''761300''>for</span>
  <span m=''761560''>details.</span> <span m=''761970''>And</span> <span m=''762080''>are</span>
  <span m=''762190''>a</span> <span m=''762250''>lot</span> <span m=''762510''>of</span>
  <span m=''762630''>other</span> <span m=''763580''>programs</span> <span m=''764310''>on</span>
  <span m=''764580''>the</span> <span m=''766030''>market,</span> <span m=''766670''>and</span>
  <span m=''767360''>out</span> <span m=''767700''>there</span> <span m=''767990''>as</span>
  <span m=''768740''>open</span> <span m=''769040''>software,</span> <span m=''769960''>such</span>
  <span m=''770170''>as</span> <span m=''770300''>purify</span> <span m=''771040''>and</span>
  <span m=''771450''>a</span> <span m=''771620''>variety of</span> <span m=''772120''>others.</span>
  </p><p><span m=''775110''>So</span> <span m=''777570''>let''s</span> <span m=''777760''>talk</span>
  <span m=''778000''>about</span> <span m=''778210''>heap</span> <span m=''778520''>allocation.</span>
  <span m=''779100''>I</span> <span m=''779130''>want</span> <span m=''779260''>to</span>
  <span m=''779300''>start</span> <span m=''779690''>by</span> <span m=''779820''>talking</span>
  <span m=''780200''>about</span> <span m=''780520''>fixed</span> <span m=''780750''>size</span>
  <span m=''781120''>allocation.</span> <span m=''781770''>So</span> <span m=''781900''>suppose</span>
  <span m=''782390''>the</span> <span m=''782490''>world</span> <span m=''783410''>has</span>
  <span m=''783570''>only</span> <span m=''783810''>one</span> <span m=''784120''>size</span>
  <span m=''784510''>of</span> <span m=''784600''>objects</span> <span m=''785180''>that</span>
  <span m=''785310''>you</span> <span m=''785400''>care</span> <span m=''785680''>about.</span>
  <span m=''787760''>Then</span> <span m=''788920''>it</span> <span m=''789130''>turns</span>
  <span m=''789420''>out</span> <span m=''789770''>that</span> <span m=''790270''>doing</span>
  <span m=''790830''>an</span> <span m=''791190''>allocator</span> <span m=''791860''>is</span>
  <span m=''791970''>really</span> <span m=''792260''>simple,</span> <span m=''792710''>and</span>
  <span m=''792800''>you</span> <span m=''792900''>could</span> <span m=''793060''>program</span>
  <span m=''793540''>one</span> <span m=''793720''>yourself.</span> </p><p><span m=''795640''>So</span>
  <span m=''795830''>here''s</span> <span m=''796160''>basically</span> <span m=''796620''>how</span>
  <span m=''796820''>it</span> <span m=''796860''>works.</span> <span m=''797200''>It''s</span>
  <span m=''797340''>called</span> <span m=''797810''>using</span> <span m=''798120''>a</span>
  <span m=''798170''>free</span> <span m=''798480''>list.</span> <span m=''799275''>And</span>
  <span m=''799630''>what</span> <span m=''799840''>you</span> <span m=''800050''>have</span>
  <span m=''800300''>is,</span> <span m=''802350''>in</span> <span m=''802690''>your</span>
  <span m=''804360''>array,</span> <span m=''804680''>say,</span> <span m=''805060''>that</span>
  <span m=''805290''>you''re</span> <span m=''805450''>using</span> <span m=''805830''>for</span>
  <span m=''805980''>storing</span> <span m=''809750''>all</span> <span m=''809910''>of</span>
  <span m=''810070''>your</span> <span m=''810550''>values,</span> <span m=''811030''>and</span>
  <span m=''811130''>here</span> <span m=''811340''>they''re</span> <span m=''811500''>basically</span>
  <span m=''811980''>this</span> <span m=''812090''>size,</span> <span m=''814190''>what</span>
  <span m=''814360''>you</span> <span m=''814510''>do</span> <span m=''814660''>is</span>
  <span m=''814760''>you</span> <span m=''814830''>have a</span> <span m=''814960''>certain</span>
  <span m=''815260''>number</span> <span m=''815490''>that</span> <span m=''815590''>are</span>
  <span m=''815690''>used.</span> <span m=''816400''>That</span> <span m=''816600''>means</span>
  <span m=''816850''>that</span> <span m=''816990''>the</span> <span m=''817070''>program</span>
  <span m=''817670''>is</span> <span m=''817770''>using</span> <span m=''818160''>them,</span>
  <span m=''819560''>not</span> <span m=''819820''>the</span> <span m=''819910''>storage</span>
  <span m=''820340''>allocator.</span> <span m=''821165''>And</span> <span m=''821450''>what</span>
  <span m=''821650''>you</span> <span m=''821750''>do</span> <span m=''822040''>is</span>
  <span m=''822200''>you</span> <span m=''822500''>take</span> <span m=''822800''>advantage</span>
  <span m=''823400''>of</span> <span m=''823540''>the</span> <span m=''823640''>fact</span>
  <span m=''824070''>that</span> <span m=''824380''>if</span> <span m=''824520''>it''s
  an</span> <span m=''824680''>unused</span> <span m=''825310''>block</span> <span
  m=''825650''>of</span> <span m=''825740''>storage,</span> <span m=''827510''>then</span>
  <span m=''827910''>you</span> <span m=''828070''>can</span> <span m=''828230''>put</span>
  <span m=''828390''>a</span> <span m=''828440''>pointer</span> <span m=''828910''>in</span>
  <span m=''829010''>there.</span> </p><p><span m=''830710''>And</span> <span m=''830870''>so</span>
  <span m=''830980''>what</span> <span m=''831110''>you</span> <span m=''831190''>do,</span>
  <span m=''831400''>is</span> <span m=''831500''>you</span> <span m=''831620''>string</span>
  <span m=''832020''>all</span> <span m=''832230''>these</span> <span m=''832430''>unblocked</span>
  <span m=''834290''>pieces</span> <span m=''834670''>of</span> <span m=''834730''>storage</span>
  <span m=''835120''>together</span> <span m=''835900''>into</span> <span m=''836140''>a</span>
  <span m=''836210''>free list.</span> <span m=''836810''>So</span> <span m=''836960''>we</span>
  <span m=''837110''>point</span> <span m=''837430''>to</span> <span m=''837530''>there,</span>
  <span m=''838330''>which</span> <span m=''838500''>points</span> <span m=''838770''>to</span>
  <span m=''838880''>there,</span> <span m=''839480''>which</span> <span m=''839680''>points</span>
  <span m=''839960''>to</span> <span m=''840070''>there,</span> <span m=''840420''>which</span>
  <span m=''840630''>points to</span> <span m=''840890''>there,</span> <span m=''841340''>which</span>
  <span m=''841530''>points</span> <span m=''841840''>nowhere.</span> <span m=''844180''>So</span>
  <span m=''844320''>you</span> <span m=''844370''>just</span> <span m=''844530''>simply</span>
  <span m=''844800''>linked</span> <span m=''845120''>together</span> <span m=''845680''>all</span>
  <span m=''846000''>of</span> <span m=''846090''>the</span> <span m=''846180''>things</span>
  <span m=''846530''>that</span> <span m=''846630''>are</span> <span m=''846710''>free</span>
  <span m=''848150''>in</span> <span m=''848380''>that</span> <span m=''849090''>list.</span>
  <span m=''849540''>And</span> <span m=''849660''>then</span> <span m=''849840''>whenever</span>
  <span m=''850190''>you</span> <span m=''850310''>need</span> <span m=''850640''>one</span>
  <span m=''851520''>to</span> <span m=''851610''>allocate</span> <span m=''852210''>an</span>
  <span m=''852310''>object,</span> <span m=''853170''>what</span> <span m=''853350''>you</span>
  <span m=''853460''>do</span> <span m=''854380''>is,</span> <span m=''855250''>you</span>
  <span m=''855470''>grab</span> <span m=''855890''>one</span> <span m=''856070''>off</span>
  <span m=''856310''>the</span> <span m=''856390''>free</span> <span m=''856640''>list.</span>
  <span m=''857400''>So</span> <span m=''857570''>you</span> <span m=''857730''>set</span>
  <span m=''859030''>the</span> <span m=''859260''>value</span> <span m=''859690''>that</span>
  <span m=''859860''>you''re</span> <span m=''860030''>going</span> <span m=''860360''>to</span>
  <span m=''861550''>want</span> <span m=''861940''>to</span> <span m=''863050''>take</span>
  <span m=''863290''>off</span> <span m=''863710''>free list to</span> <span m=''864210''>free--</span>
  <span m=''865040''>so</span> <span m=''865200''>here</span> <span m=''865450''>x</span>
  <span m=''865780''>gets</span> <span m=''865970''>a</span> <span m=''866030''>pointer</span>
  <span m=''866390''>to</span> <span m=''866510''>this</span> <span m=''866720''>object,</span>
  <span m=''868020''>the</span> <span m=''868120''>one</span> <span m=''868290''>that''s</span>
  <span m=''868470''>at</span> <span m=''868540''>the</span> <span m=''868620''>start</span>
  <span m=''868980''>of</span> <span m=''869040''>the</span> <span m=''869120''>list.</span>
  <span m=''870740''>Then</span> <span m=''871400''>you</span> <span m=''871620''>update</span>
  <span m=''872210''>free</span> <span m=''872680''>with</span> <span m=''872890''>free</span>
  <span m=''876700''>arrow</span> <span m=''876960''>next,</span> <span m=''877490''>which</span>
  <span m=''877690''>gives</span> <span m=''877850''>you</span> <span m=''877960''>this</span>
  <span m=''878230''>guy.</span> <span m=''881170''>So</span> <span m=''881340''>that''s</span>
  <span m=''881580''>the</span> <span m=''881670''>next</span> <span m=''882070''>guy</span>
  <span m=''882200''>in</span> <span m=''882340''>line.</span> <span m=''883180''>And</span>
  <span m=''883370''>then</span> <span m=''883560''>you</span> <span m=''883650''>basically</span>
  <span m=''884200''>return</span> <span m=''884670''>x.</span> <span m=''886850''>And</span>
  <span m=''886970''>that''s</span> <span m=''887200''>all</span> <span m=''887370''>there</span>
  <span m=''887520''>is</span> <span m=''887670''>to</span> <span m=''887880''>it.</span>
  <span m=''888920''>You</span> <span m=''889300''>just</span> <span m=''889700''>grab</span>
  <span m=''890110''>the</span> <span m=''890190''>first</span> <span m=''890540''>element</span>
  <span m=''890900''>off the</span> <span m=''891270''>free</span> <span m=''891490''>list.</span>
  </p><p><span m=''893550''>Now,</span> <span m=''893720''>there''s</span> <span m=''893900''>a</span>
  <span m=''893950''>little</span> <span m=''894220''>bit</span> <span m=''894380''>of</span>
  <span m=''894900''>subtlety</span> <span m=''895510''>in</span> <span m=''895610''>that</span>
  <span m=''895750''>the</span> <span m=''895850''>thing</span> <span m=''896070''>that</span>
  <span m=''896190''>you''re</span> <span m=''896880''>grabbing</span> <span m=''897300''>off</span>
  <span m=''897580''>has</span> <span m=''897680''>a</span> <span m=''897780''>garbage</span>
  <span m=''898230''>pointer</span> <span m=''898670''>in it,</span> <span m=''899430''>because</span>
  <span m=''899900''>we''re</span> <span m=''900110''>not</span> <span m=''900670''>initializing</span>
  <span m=''901360''>storage.</span> <span m=''901730''>There are</span> <span m=''901940''>some</span>
  <span m=''902180''>storage</span> <span m=''902590''>allocators</span> <span m=''903370''>that</span>
  <span m=''903480''>will</span> <span m=''903610''>always</span> <span m=''903970''>set</span>
  <span m=''904270''>the</span> <span m=''904350''>value</span> <span m=''904780''>that''s</span>
  <span m=''904950''>returned</span> <span m=''905340''>to</span> <span m=''905410''>the</span>
  <span m=''905480''>user</span> <span m=''905870''>to</span> <span m=''905980''>all</span>
  <span m=''906230''>zeros,</span> <span m=''906720''>for</span> <span m=''906830''>example.</span>
  <span m=''908210''>But</span> <span m=''908410''>typically</span> <span m=''908820''>malloc</span>
  <span m=''909350''>doesn''t</span> <span m=''909670''>do</span> <span m=''909810''>that.</span>
  <span m=''911890''>It</span> <span m=''912100''>basically</span> <span m=''912550''>leaves</span>
  <span m=''912900''>that</span> <span m=''913850''>as</span> <span m=''914090''>uninitialized</span>
  <span m=''914760''>storage.</span> <span m=''915590''>And</span> <span m=''915730''>so</span>
  <span m=''915830''>you</span> <span m=''915960''>can</span> <span m=''916090''>actually</span>
  <span m=''916410''>go</span> <span m=''916650''>and</span> <span m=''916750''>see,</span>
  <span m=''917130''>what</span> <span m=''917290''>were</span> <span m=''917380''>the</span>
  <span m=''917470''>values</span> <span m=''917850''>that</span> <span m=''917970''>used</span>
  <span m=''918100''>to</span> <span m=''918240''>be</span> <span m=''918380''>stored</span>
  <span m=''918730''>in</span> <span m=''918840''>there?</span> <span m=''921030''>And</span>
  <span m=''921210''>so</span> <span m=''921890''>basically,</span> <span m=''922880''>you</span>
  <span m=''923090''>can</span> <span m=''923300''>end</span> <span m=''923520''>up</span>
  <span m=''923660''>with</span> <span m=''923800''>a</span> <span m=''924320''>garbage</span>
  <span m=''924720''>pointer</span> <span m=''925010''>there,</span> <span m=''925220''>but</span>
  <span m=''925380''>you</span> <span m=''925510''>really</span> <span m=''925700''>don''t</span>
  <span m=''925920''>care</span> <span m=''926160''>about</span> <span m=''926430''>that,</span>
  <span m=''927820''>because</span> <span m=''928020''>it''s</span> <span m=''928170''>no</span>
  <span m=''928380''>longer</span> <span m=''928840''>on</span> <span m=''928960''>the</span>
  <span m=''929090''>list.</span> </p><p><span m=''929850''>So</span> <span m=''929990''>you</span>
  <span m=''930090''>can</span> <span m=''930200''>see,</span> <span m=''930460''>for</span>
  <span m=''930570''>example,</span> <span m=''930980''>if</span> <span m=''931080''>I</span>
  <span m=''931360''>then</span> <span m=''931930''>went</span> <span m=''932160''>and</span>
  <span m=''932450''>I--</span> <span m=''936060''>well,</span> <span m=''936880''>let''s</span>
  <span m=''937170''>do</span> <span m=''937290''>this,</span> <span m=''938220''>to</span>
  <span m=''938670''>take</span> <span m=''939150''>a</span> <span m=''939200''>look</span>
  <span m=''939390''>at</span> <span m=''939480''>what</span> <span m=''939600''>happens</span>
  <span m=''939960''>when</span> <span m=''940120''>a</span> <span m=''940190''>free</span>
  <span m=''940480''>an</span> <span m=''940590''>item.</span> <span m=''941490''>So
  if I</span> <span m=''941610''>want to</span> <span m=''941850''>free</span> <span
  m=''942160''>an</span> <span m=''942250''>object</span> <span m=''942690''>x,</span>
  <span m=''944540''>I</span> <span m=''944690''>take</span> <span m=''945170''>some</span>
  <span m=''945380''>object</span> <span m=''945810''>x</span> <span m=''946100''>here.</span>
  <span m=''946790''>Let''s</span> <span m=''946970''>say</span> <span m=''947080''>it''s</span>
  <span m=''947210''>this</span> <span m=''947410''>guy that''s</span> <span m=''947760''>being</span>
  <span m=''947990''>freed.</span> <span m=''949020''>What</span> <span m=''949160''>I</span>
  <span m=''949260''>do</span> <span m=''949590''>is,</span> <span m=''949970''>I</span>
  <span m=''950150''>make</span> <span m=''950520''>it</span> <span m=''950850''>point</span>
  <span m=''951260''>to</span> <span m=''956360''>the</span> <span m=''957190''>first</span>
  <span m=''957620''>element</span> <span m=''957950''>of</span> <span m=''958020''>the</span>
  <span m=''958090''>list.</span> <span m=''960820''>So</span> <span m=''961040''>basically,</span>
  <span m=''961630''>next</span> <span m=''962030''>equals</span> <span m=''962410''>free,</span>
  <span m=''963760''>So</span> <span m=''963950''>he</span> <span m=''964050''>basically</span>
  <span m=''964500''>points</span> <span m=''964910''>there.</span> <span m=''965680''>And</span>
  <span m=''965830''>then</span> <span m=''966000''>I</span> <span m=''966110''>say</span>
  <span m=''966450''>free</span> <span m=''966860''>equals</span> <span m=''967190''>x,</span>
  <span m=''967560''>meaning</span> <span m=''968350''>move the</span> <span m=''968850''>free</span>
  <span m=''969170''>pointer</span> <span m=''969560''>up</span> <span m=''969720''>to</span>
  <span m=''970770''>now</span> <span m=''971010''>point</span> <span m=''971320''>to</span>
  <span m=''971430''>the</span> <span m=''971800''>new</span> <span m=''972240''>beginning</span>
  <span m=''972640''>of</span> <span m=''972720''>the</span> <span m=''972800''>list.</span>
  <span m=''973510''>So we''re</span> <span m=''973700''>basically</span> <span m=''974160''>pushing</span>
  <span m=''974570''>and</span> <span m=''974680''>popping</span> <span m=''975130''>things</span>
  <span m=''975410''>off</span> <span m=''975590''>the</span> <span m=''975690''>front</span>
  <span m=''975830''>of</span> <span m=''975900''>the</span> <span m=''976020''>list.</span>
  <span m=''976250''>It''s</span> <span m=''976370''>just</span> <span m=''976620''>the</span>
  <span m=''976700''>stack</span> <span m=''977120''>discipline,</span> <span m=''977920''>except</span>
  <span m=''978260''>we''re</span> <span m=''978350''>using</span> <span m=''978640''>a</span>
  <span m=''978700''>linked</span> <span m=''978990''>list,</span> <span m=''979910''>rather</span>
  <span m=''980230''>than</span> <span m=''980430''>using</span> <span m=''981240''>an</span>
  <span m=''981420''>array.</span> <span m=''983060''>So</span> <span m=''983710''>we</span>
  <span m=''983860''>push</span> <span m=''985240''>to</span> <span m=''986540''>free,</span>
  <span m=''986910''>and</span> <span m=''987060''>we</span> <span m=''987190''>pop</span>
  <span m=''988089''>to</span> <span m=''992650''>allocate.</span> </p><p><span m=''993880''>Now</span>
  <span m=''994070''>the</span> <span m=''994180''>tricky</span> <span m=''994540''>thing</span>
  <span m=''994750''>here--</span> <span m=''995140''>you</span> <span m=''995240''>can</span>
  <span m=''995350''>sort</span> <span m=''995520''>of</span> <span m=''995580''>see</span>
  <span m=''995810''>what</span> <span m=''996020''>might</span> <span m=''996230''>go</span>
  <span m=''996440''>wrong</span> <span m=''997300''>if</span> <span m=''997500''>I</span>
  <span m=''997670''>then</span> <span m=''997840''>said,</span> <span m=''998190''>oh,</span>
  <span m=''998390''>let</span> <span m=''998570''>me</span> <span m=''998700''>free</span>
  <span m=''998980''>this</span> <span m=''999210''>thing</span> <span m=''999390''>again.</span>
  <span m=''1001910''>Suppose</span> <span m=''1002300''>you</span> <span m=''1002410''>said,</span>
  <span m=''1003300''>now that</span> <span m=''1003530''>this</span> <span m=''1003810''>is</span>
  <span m=''1003930''>free,</span> <span m=''1004160''>suppose</span> <span m=''1004520''>you</span>
  <span m=''1004600''>came</span> <span m=''1004860''>in</span> <span m=''1004950''>and</span>
  <span m=''1005040''>say,</span> <span m=''1005170''>oh, I''ll</span> <span m=''1005490''>free</span>
  <span m=''1005680''>that</span> <span m=''1005930''>thing</span> <span m=''1006110''>again.</span>
  <span m=''1007540''>Well,</span> <span m=''1007660''>now</span> <span m=''1007870''>you''re</span>
  <span m=''1008000''>going</span> <span m=''1008100''>to</span> <span m=''1008920''>go</span>
  <span m=''1009040''>through</span> <span m=''1009270''>the</span> <span m=''1009370''>same</span>
  <span m=''1010640''>code</span> <span m=''1011050''>here,</span> <span m=''1011500''>and</span>
  <span m=''1011950''>you''re</span> <span m=''1012050''>going</span> <span m=''1012120''>to</span>
  <span m=''1012190''>see,</span> <span m=''1012380''>you''re</span> <span m=''1012490''>going</span>
  <span m=''1012600''>to</span> <span m=''1012700''>completely</span> <span m=''1013100''>screw</span>
  <span m=''1013410''>up</span> <span m=''1013590''>the</span> <span m=''1013650''>free</span>
  <span m=''1013880''>list.</span> <span m=''1015070''>So</span> <span m=''1015190''>that''s</span>
  <span m=''1015350''>why</span> <span m=''1015480''>you</span> <span m=''1015570''>don''t</span>
  <span m=''1015710''>want</span> <span m=''1015830''>to</span> <span m=''1015890''>do</span>
  <span m=''1016030''>a</span> <span m=''1016090''>double</span> <span m=''1016380''>free.</span>
  <span m=''1019000''>So</span> <span m=''1019150''>you</span> <span m=''1019230''>can</span>
  <span m=''1019310''>see</span> <span m=''1019470''>exactly</span> <span m=''1019930''>what''s</span>
  <span m=''1020120''>going</span> <span m=''1020230''>to</span> <span m=''1020270''>go</span>
  <span m=''1020510''>on</span> <span m=''1020660''>in</span> <span m=''1020780''>the</span>
  <span m=''1020910''>free</span> <span m=''1021150''>list</span> <span m=''1021410''>implementation.</span>
  </p><p><span m=''1023050''>So</span> <span m=''1023270''>this</span> <span m=''1023460''>is</span>
  <span m=''1023620''>pretty</span> <span m=''1023870''>good</span> <span m=''1024140''>and</span>
  <span m=''1024260''>pretty</span> <span m=''1024520''>cheap.</span> <span m=''1027780''>Allocating</span>
  <span m=''1028380''>and</span> <span m=''1028460''>freeing</span> <span m=''1029040''>take</span>
  <span m=''1029270''>constant</span> <span m=''1029760''>time.</span> <span m=''1030069''>That''s</span>
  <span m=''1030329''>great,</span> <span m=''1030930''>just</span> <span m=''1031240''>as</span>
  <span m=''1031410''>with</span> <span m=''1031599''>stack</span> <span m=''1031990''>pointer.</span>
  <span m=''1032740''>It''s</span> <span m=''1032910''>got</span> <span m=''1033140''>good</span>
  <span m=''1033380''>temporal</span> <span m=''1033800''>locality,</span> <span m=''1034540''>and</span>
  <span m=''1034630''>the</span> <span m=''1034720''>reason</span> <span m=''1035069''>is</span>
  <span m=''1035240''>because</span> <span m=''1035650''>you''re</span> <span m=''1035810''>tending</span>
  <span m=''1036190''>to</span> <span m=''1036300''>allocate</span> <span m=''1037819''>the</span>
  <span m=''1038140''>thing</span> <span m=''1038380''>that</span> <span m=''1038520''>you</span>
  <span m=''1038650''>freed</span> <span m=''1039060''>most</span> <span m=''1039349''>recently.</span>
  <span m=''1040319''>The</span> <span m=''1040440''>free</span> <span m=''1040700''>list</span>
  <span m=''1040940''>operates</span> <span m=''1041530''>as</span> <span m=''1041819''>a</span>
  <span m=''1041940''>last</span> <span m=''1042390''>in,</span> <span m=''1042560''>first</span>
  <span m=''1042950''>out</span> <span m=''1043700''>data</span> <span m=''1043960''>structure.</span>
  <span m=''1044930''>So</span> <span m=''1045130''>from</span> <span m=''1045290''>a</span>
  <span m=''1045349''>temporal</span> <span m=''1045770''>locality</span> <span m=''1046369''>point
  of</span> <span m=''1046700''>view,</span> <span m=''1046829''>it''s</span> <span
  m=''1046940''>really</span> <span m=''1047230''>very</span> <span m=''1047500''>good.</span>
  <span m=''1048670''>You''re</span> <span m=''1048810''>always</span> <span m=''1049150''>using</span>
  <span m=''1049580''>the</span> <span m=''1049690''>most</span> <span m=''1050200''>recently</span>
  <span m=''1050910''>freed</span> <span m=''1051370''>stuff</span> <span m=''1052170''>whenever</span>
  <span m=''1052550''>you</span> <span m=''1052700''>allocate,</span> <span m=''1054150''>and</span>
  <span m=''1054830''>that</span> <span m=''1055040''>means</span> <span m=''1055220''>you</span>
  <span m=''1055360''>have</span> <span m=''1055490''>very</span> <span m=''1055780''>good</span>
  <span m=''1056310''>caching</span> <span m=''1056740''>behavior</span> <span m=''1057190''>from</span>
  <span m=''1057390''>a</span> <span m=''1057440''>temporal</span> <span m=''1058110''>locality</span>
  <span m=''1058660''>point</span> <span m=''1058910''>of</span> <span m=''1058970''>view.</span>
  </p><p><span m=''1059450''>However,</span> <span m=''1059920''>it</span> <span m=''1060010''>has</span>
  <span m=''1060220''>poor</span> <span m=''1060590''>spatial</span> <span m=''1061220''>locality,</span>
  <span m=''1062750''>and</span> <span m=''1062900''>the</span> <span m=''1062990''>reason</span>
  <span m=''1063380''>is</span> <span m=''1064200''>due</span> <span m=''1064520''>to</span>
  <span m=''1065290''>what''s</span> <span m=''1065470''>called</span> <span m=''1065690''>external</span>
  <span m=''1066210''>fragmentation,</span> <span m=''1068590''>where</span> <span
  m=''1068740''>you</span> <span m=''1068880''>get</span> <span m=''1069760''>your</span>
  <span m=''1070140''>storage</span> <span m=''1070870''>distributed</span> <span
  m=''1071710''>across</span> <span m=''1072360''>virtual</span> <span m=''1072710''>memory.</span>
  <span m=''1074250''>So if</span> <span m=''1074380''>you</span> <span m=''1074530''>think</span>
  <span m=''1074760''>about</span> <span m=''1075090''>this,</span> <span m=''1075300''>as</span>
  <span m=''1075610''>you</span> <span m=''1075750''>start</span> <span m=''1076060''>allocating</span>
  <span m=''1076660''>and</span> <span m=''1076750''>freeing</span> <span m=''1077130''>in</span>
  <span m=''1077230''>different</span> <span m=''1077500''>orders,</span> <span m=''1078230''>the</span>
  <span m=''1078350''>order</span> <span m=''1078770''>of</span> <span m=''1078840''>that</span>
  <span m=''1079150''>free</span> <span m=''1079350''>list</span> <span m=''1079570''>gets</span>
  <span m=''1079780''>very</span> <span m=''1080050''>jumbled</span> <span m=''1080500''>up.</span>
  <span m=''1082450''>And</span> <span m=''1084820''>as</span> <span m=''1085150''>it</span>
  <span m=''1085260''>increases,</span> <span m=''1086220''>and</span> <span m=''1086490''>you</span>
  <span m=''1086610''>end</span> <span m=''1086840''>up</span> <span m=''1088160''>with</span>
  <span m=''1088460''>jumping</span> <span m=''1088880''>from</span> <span m=''1089070''>one</span>
  <span m=''1089720''>thing</span> <span m=''1089920''>to</span> <span m=''1090090''>another,</span>
  <span m=''1090870''>you</span> <span m=''1090990''>basically</span> <span m=''1092130''>can</span>
  <span m=''1093420''>end</span> <span m=''1093700''>up</span> <span m=''1095390''>causing</span>
  <span m=''1097750''>you to</span> <span m=''1097920''>use</span> <span m=''1098190''>a</span>
  <span m=''1098240''>lot</span> <span m=''1098600''>of</span> <span m=''1100280''>the</span>
  <span m=''1100390''>page</span> <span m=''1100760''>table,</span> <span m=''1101420''>because</span>
  <span m=''1101600''>you''re</span> <span m=''1101740''>basically</span> <span m=''1102250''>using</span>
  <span m=''1102730''>a</span> <span m=''1102770''>huge</span> <span m=''1103520''>piece</span>
  <span m=''1103760''>of</span> <span m=''1103870''>it,</span> <span m=''1104030''>rather</span>
  <span m=''1104370''>than--</span> <span m=''1104680''>and</span> <span m=''1104900''>in</span>
  <span m=''1105090''>particular,</span> <span m=''1105870''>the</span> <span m=''1105970''>translation</span>
  <span m=''1106960''>look</span> <span m=''1107180''>aside</span> <span m=''1107550''>buffer</span>
  <span m=''1108400''>can</span> <span m=''1108530''>also</span> <span m=''1108860''>be</span>
  <span m=''1109040''>a</span> <span m=''1109090''>problem.</span> <span m=''1110430''>So
  the</span> <span m=''1110570''>translation</span> <span m=''1111160''>look</span>
  <span m=''1111340''>aside</span> <span m=''1111660''>buffer</span> <span m=''1112970''>typically</span>
  <span m=''1114000''>works</span> <span m=''1114510''>on</span> <span m=''1114640''>a</span>
  <span m=''1114770''>page</span> <span m=''1115220''>basis.</span> <span m=''1116140''>And</span>
  <span m=''1116290''>if</span> <span m=''1116390''>you</span> <span m=''1116580''>recently</span>
  <span m=''1117150''>referenced</span> <span m=''1117640''>things</span> <span m=''1117900''>on</span>
  <span m=''1118030''>a</span> <span m=''1118070''>given</span> <span m=''1118390''>page,</span>
  <span m=''1119370''>that''s</span> <span m=''1119630''>very</span> <span m=''1119900''>good</span>
  <span m=''1120200''>for</span> <span m=''1120290''>the</span> <span m=''1120400''>TLB,</span>
  <span m=''1121090''>because</span> <span m=''1121520''>it''s</span> <span m=''1121740''>already</span>
  <span m=''1121940''>got</span> <span m=''1122260''>the</span> <span m=''1122340''>translation,</span>
  <span m=''1123340''>the</span> <span m=''1123450''>virtual</span> <span m=''1123850''>address</span>
  <span m=''1124220''>mapping</span> <span m=''1124600''>of</span> <span m=''1124690''>that</span>
  <span m=''1124950''>page</span> <span m=''1126360''>dealt</span> <span m=''1126610''>with.</span>
  <span m=''1128120''>So</span> <span m=''1128970''>it</span> <span m=''1129180''>basically</span>
  <span m=''1129720''>has</span> <span m=''1129970''>poor</span> <span m=''1130190''>spatial</span>
  <span m=''1130540''>locality,</span> <span m=''1130970''>because</span> <span m=''1131180''>it''s</span>
  <span m=''1131310''>getting</span> <span m=''1131570''>all</span> <span m=''1131770''>jumbled</span>
  <span m=''1132160''>up.</span> <span m=''1132610''>Compared</span> <span m=''1132940''>to</span>
  <span m=''1133040''>stack</span> <span m=''1133480''>allocation,</span> <span m=''1134400''>which</span>
  <span m=''1134660''>is</span> <span m=''1134770''>always</span> <span m=''1135140''>very</span>
  <span m=''1135380''>nice</span> <span m=''1135800''>in</span> <span m=''1135920''>terms</span>
  <span m=''1136220''>of</span> <span m=''1136290''>its</span> <span m=''1136470''>behavior,</span>
  <span m=''1137200''>because</span> <span m=''1137490''>you''re</span> <span m=''1137590''>going</span>
  <span m=''1137840''>across</span> <span m=''1138240''>consecutive</span> <span m=''1139330''>locations</span>
  <span m=''1140010''>in</span> <span m=''1140090''>memory,</span> <span m=''1140770''>which</span>
  <span m=''1140950''>means</span> <span m=''1141650''>you''re</span> <span m=''1141980''>always</span>
  <span m=''1142410''>allocating</span> <span m=''1143030''>and</span> <span m=''1143140''>freeing</span>
  <span m=''1143560''>from</span> <span m=''1143720''>the</span> <span m=''1143790''>same</span>
  <span m=''1144220''>page,</span> <span m=''1145080''>unless</span> <span m=''1145360''>you</span>
  <span m=''1145960''>trip</span> <span m=''1146200''>over</span> <span m=''1146470''>a</span>
  <span m=''1146500''>page</span> <span m=''1146820''>boundary.</span> </p><p><span
  m=''1149170''>So</span> <span m=''1150370''>here''s</span> <span m=''1151290''>some</span>
  <span m=''1151510''>ways</span> <span m=''1152040''>of</span> <span m=''1152160''>mitigating</span>
  <span m=''1152730''>external</span> <span m=''1153180''>fragmentation.</span> <span
  m=''1154020''>Of</span> <span m=''1154100''>course,</span> <span m=''1154390''>this</span>
  <span m=''1154570''>makes</span> <span m=''1156310''>the</span> <span m=''1156690''>code</span>
  <span m=''1157080''>for</span> <span m=''1157260''>free</span> <span m=''1157500''>list</span>
  <span m=''1157760''>more</span> <span m=''1157940''>complicated.</span> <span m=''1159230''>And</span>
  <span m=''1159480''>then</span> <span m=''1159610''>you</span> <span m=''1159740''>have</span>
  <span m=''1159880''>to</span> <span m=''1160010''>weigh,</span> <span m=''1160860''>how</span>
  <span m=''1161030''>much</span> <span m=''1161240''>am</span> <span m=''1161280''>I</span>
  <span m=''1161430''>losing</span> <span m=''1162560''>in</span> <span m=''1163190''>having</span>
  <span m=''1163500''>a</span> <span m=''1163540''>more</span> <span m=''1163780''>complicated</span>
  <span m=''1164450''>allocator</span> <span m=''1165180''>versus</span> <span m=''1166120''>suffering</span>
  <span m=''1166710''>the</span> <span m=''1167160''>fragmentation</span> <span m=''1168040''>may</span>
  <span m=''1168440''>occur?</span> <span m=''1168840''>Yes,</span> <span m=''1169080''>question?</span>
  </p><p><span m=''1169943''>AUDIENCE: You</span> <span m=''1170426''>specificed</span>
  <span m=''1170909''>before</span> <span m=''1171029''>that</span> <span m=''1171150''>it</span>
  <span m=''1171271''>was</span> <span m=''1171392''>fixed</span> <span m=''1171875''>size.</span>
  <span m=''1172358''>Is that why</span> <span m=''1172841''>we don''t</span> <span
  m=''1173324''>specify</span> <span m=''1174290''>anything about</span> <span m=''1174773''>the
  size?</span> </p><p><span m=''1175260''>CHARLES LEISERSON: That''s right.</span>
  <span m=''1175990''>We''re</span> <span m=''1176100''>just</span> <span m=''1176350''>assuming</span>
  <span m=''1176790''>that</span> <span m=''1176900''>it''s</span> <span m=''1177080''>all</span>
  <span m=''1177360''>whatever</span> <span m=''1177660''>the</span> <span m=''1177770''>unit</span>
  <span m=''1177960''>size is.</span> </p><p><span m=''1178780''>So</span> <span m=''1178950''>this</span>
  <span m=''1179110''>is</span> <span m=''1179240''>really</span> <span m=''1179510''>good</span>
  <span m=''1179740''>when</span> <span m=''1181300''>you''ve</span> <span m=''1181520''>created</span>
  <span m=''1181910''>your</span> <span m=''1182070''>own</span> <span m=''1182180''>data</span>
  <span m=''1182450''>structure,</span> <span m=''1183040''>and</span> <span m=''1184310''>let''s</span>
  <span m=''1184500''>say</span> <span m=''1184620''>you''re</span> <span m=''1184730''>doing</span>
  <span m=''1184990''>nodes</span> <span m=''1185290''>in</span> <span m=''1185350''>a</span>
  <span m=''1185400''>graph.</span> <span m=''1186400''>You</span> <span m=''1186540''>know</span>
  <span m=''1186650''>exactly</span> <span m=''1187140''>what</span> <span m=''1187310''>elements</span>
  <span m=''1187780''>you</span> <span m=''1187890''>want</span> <span m=''1188180''>in</span>
  <span m=''1188300''>the</span> <span m=''1188360''>graph,</span> <span m=''1190290''>for</span>
  <span m=''1190490''>each</span> <span m=''1190670''>vertex.</span> <span m=''1192200''>And</span>
  <span m=''1192430''>now</span> <span m=''1192710''>what</span> <span m=''1192860''>you</span>
  <span m=''1192960''>want</span> <span m=''1193100''>to</span> <span m=''1193160''>do</span>
  <span m=''1193430''>is</span> <span m=''1193660''>basically</span> <span m=''1194180''>be</span>
  <span m=''1194370''>able</span> <span m=''1194700''>to</span> <span m=''1196020''>give</span>
  <span m=''1196240''>yourself</span> <span m=''1196660''>a</span> <span m=''1196760''>note</span>
  <span m=''1197000''>of</span> <span m=''1197080''>a</span> <span m=''1197130''>graph,</span>
  <span m=''1197960''>free</span> <span m=''1198230''>a</span> <span m=''1198350''>note</span>
  <span m=''1198480''>of</span> <span m=''1198580''>a</span> <span m=''1198630''>graph,</span>
  <span m=''1199030''>and</span> <span m=''1199110''>manage</span> <span m=''1199460''>that</span>
  <span m=''1199650''>storage</span> <span m=''1200070''>yourself.</span> <span m=''1202970''>Yes,</span>
  <span m=''1203220''>question?</span> </p><p><span m=''1204067''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''1205061''>allocated</span> <span m=''1205558''>across</span> <span m=''1206055''>virtual</span>
  <span m=''1206552''>memory</span> <span m=''1207049''>[INAUDIBLE]</span> <span m=''1207546''>one</span>
  <span m=''1208043''>application?</span> </p><p><span m=''1211030''>CHARLES LEISERSON:
  Why</span> <span m=''1211540''>is</span> <span m=''1211640''>it</span> <span m=''1211740''>allocated</span>
  <span m=''1212200''>across</span> <span m=''1212690''>virtual</span> <span m=''1213040''>memory</span>
  <span m=''1213640''>if</span> <span m=''1213820''>it''s</span> <span m=''1214020''>all</span>
  <span m=''1214410''>one</span> <span m=''1214710''>application?</span> <span m=''1215060''>Well,</span>
  <span m=''1215550''>because</span> <span m=''1216290''>the</span> <span m=''1216800''>size</span>
  <span m=''1217180''>that</span> <span m=''1217320''>you</span> <span m=''1217410''>may</span>
  <span m=''1217700''>end</span> <span m=''1217920''>up</span> <span m=''1218050''>needing</span>
  <span m=''1218910''>can</span> <span m=''1219090''>end</span> <span m=''1219260''>up</span>
  <span m=''1219400''>being</span> <span m=''1219570''>large.</span> <span m=''1219990''>And</span>
  <span m=''1220090''>I''ll</span> <span m=''1220180''>show</span> <span m=''1220430''>you</span>
  <span m=''1220560''>in</span> <span m=''1220660''>just</span> <span m=''1220910''>a</span>
  <span m=''1220960''>minute</span> <span m=''1221200''>how</span> <span m=''1221380''>that</span>
  <span m=''1221550''>happens.</span> </p><p><span m=''1224880''>So</span> <span m=''1225100''>here''s</span>
  <span m=''1225340''>the</span> <span m=''1225490''>idea.</span> <span m=''1227920''>What</span>
  <span m=''1228250''>you</span> <span m=''1228370''>can</span> <span m=''1228540''>do</span>
  <span m=''1228750''>is</span> <span m=''1228920''>keep</span> <span m=''1229200''>a</span>
  <span m=''1229330''>free</span> <span m=''1229850''>list</span> <span m=''1230190''>per</span>
  <span m=''1230350''>disk</span> <span m=''1230730''>page.</span> <span m=''1231990''>So</span>
  <span m=''1232670''>disk</span> <span m=''1232940''>page,</span> <span m=''1233910''>a</span>
  <span m=''1234490''>traditional</span> <span m=''1235500''>page is</span> <span
  m=''1236000''>4,000</span> <span m=''1236710''>bytes.</span> <span m=''1237030''>These</span>
  <span m=''1237310''>days</span> <span m=''1237610''>they</span> <span m=''1237740''>talk</span>
  <span m=''1237980''>about</span> <span m=''1238200''>super</span> <span m=''1238530''>pages</span>
  <span m=''1238980''>that</span> <span m=''1239070''>are</span> <span m=''1239150''>megabytes,</span>
  <span m=''1240750''>and</span> <span m=''1241670''>who</span> <span m=''1241820''>knows</span>
  <span m=''1242140''>what</span> <span m=''1242320''>size</span> <span m=''1242600''>pages</span>
  <span m=''1244370''>various</span> <span m=''1244690''>operating</span> <span m=''1245120''>systems</span>
  <span m=''1245530''>will</span> <span m=''1245670''>support.</span> <span m=''1246020''>I</span>
  <span m=''1246080''>believe</span> <span m=''1246330''>the</span> <span m=''1246420''>clouds</span>
  <span m=''1246870''>use</span> <span m=''1247740''>4k,</span> <span m=''1249170''>as</span>
  <span m=''1249480''>configured</span> <span m=''1249990''>right</span> <span m=''1250200''>now</span>
  <span m=''1250360''>are</span> <span m=''1250450''>using</span> <span m=''1250750''>4k,</span>
  <span m=''1251580''>which</span> <span m=''1251800''>leads</span> <span m=''1252140''>to</span>
  <span m=''1252260''>some</span> <span m=''1252500''>strange</span> <span m=''1252900''>anomalies</span>
  <span m=''1253560''>where</span> <span m=''1253700''>the</span> <span m=''1254260''>TLB</span>
  <span m=''1256180''>can</span> <span m=''1256360''>address</span> <span m=''1256840''>less</span>
  <span m=''1257130''>stuff</span> <span m=''1257480''>than</span> <span m=''1257800''>the</span>
  <span m=''1258010''>L3</span> <span m=''1258450''>cache.</span> <span m=''1260704''>But
  so</span> <span m=''1261160''>be</span> <span m=''1261310''>it.</span> </p><p><span
  m=''1262250''>So</span> <span m=''1262400''>basically,</span> <span m=''1262660''>they</span>
  <span m=''1262920''>just</span> <span m=''1263170''>keep a</span> <span m=''1263430''>free</span>
  <span m=''1263680''>list</span> <span m=''1263920''>per</span> <span m=''1264090''>disk</span>
  <span m=''1264430''>page,</span> <span m=''1265460''>and</span> <span m=''1265630''>basically</span>
  <span m=''1266080''>always</span> <span m=''1266480''>allocate</span> <span m=''1267070''>from</span>
  <span m=''1267200''>the</span> <span m=''1267340''>free</span> <span m=''1267820''>list</span>
  <span m=''1268640''>for</span> <span m=''1268810''>the</span> <span m=''1268930''>page</span>
  <span m=''1269320''>that''s</span> <span m=''1269600''>fullest,</span> <span m=''1270050''>the</span>
  <span m=''1270160''>page</span> <span m=''1270470''>that</span> <span m=''1270570''>you''ve</span>
  <span m=''1270690''>allocated</span> <span m=''1271250''>the</span> <span m=''1271330''>most</span>
  <span m=''1271650''>of</span> <span m=''1271730''>the</span> <span m=''1271810''>stuff</span>
  <span m=''1272170''>off</span> <span m=''1272410''>of.</span> <span m=''1273880''>Rather</span>
  <span m=''1274310''>than</span> <span m=''1274710''>for a</span> <span m=''1274910''>page</span>
  <span m=''1275300''>that''s</span> <span m=''1275500''>less</span> <span m=''1275750''>empty.</span>
  <span m=''1277390''>So</span> <span m=''1277610''>what</span> <span m=''1277850''>this</span>
  <span m=''1278020''>means</span> <span m=''1278350''>is</span> <span m=''1278450''>that</span>
  <span m=''1278560''>when</span> <span m=''1278720''>you</span> <span m=''1278830''>come</span>
  <span m=''1279030''>to allocate,</span> <span m=''1279900''>you</span> <span m=''1279990''>have</span>
  <span m=''1280070''>to</span> <span m=''1280170''>figure</span> <span m=''1280450''>out,</span>
  <span m=''1280630''>which</span> <span m=''1280830''>page</span> <span m=''1281530''>should</span>
  <span m=''1281730''>I</span> <span m=''1281800''>do</span> <span m=''1281960''>the</span>
  <span m=''1282120''>allocation</span> <span m=''1282820''>off of?</span> <span m=''1283670''>But</span>
  <span m=''1283790''>we''ll have a</span> <span m=''1284100''>free</span> <span m=''1284340''>list
  on each</span> <span m=''1284840''>page.</span> </p><p><span m=''1286490''>Whenever</span>
  <span m=''1286810''>you</span> <span m=''1286940''>free</span> <span m=''1287180''>of</span>
  <span m=''1287270''>a block</span> <span m=''1287510''>of</span> <span m=''1287580''>storage,</span>
  <span m=''1287920''>you</span> <span m=''1288070''>have</span> <span m=''1288210''>to</span>
  <span m=''1288360''>free it</span> <span m=''1288700''>to</span> <span m=''1288800''>the</span>
  <span m=''1288890''>page</span> <span m=''1289260''>on</span> <span m=''1289340''>which</span>
  <span m=''1289550''>the</span> <span m=''1289630''>block</span> <span m=''1289970''>resides.</span>
  <span m=''1290460''>Don''t</span> <span m=''1290660''>put</span> <span m=''1290800''>into</span>
  <span m=''1291180''>a</span> <span m=''1291240''>free</span> <span m=''1291500''>list</span>
  <span m=''1292140''>of</span> <span m=''1292290''>a</span> <span m=''1292350''>different</span>
  <span m=''1292660''>page.</span> <span m=''1293040''>You</span> <span m=''1293100''>put</span>
  <span m=''1293280''>it</span> <span m=''1293370''>into</span> <span m=''1293570''>a</span>
  <span m=''1293620''>free</span> <span m=''1293860''>list</span> <span m=''1294170''>all</span>
  <span m=''1294320''>of</span> <span m=''1294420''>that</span> <span m=''1294700''>particular</span>
  <span m=''1295160''>page.</span> </p><p><span m=''1296430''>Now</span> <span m=''1296580''>if</span>
  <span m=''1297270''>a</span> <span m=''1297340''>page</span> <span m=''1297670''>becomes</span>
  <span m=''1298090''>empty,</span> <span m=''1299150''>in other words,</span> <span
  m=''1299450''>there''s</span> <span m=''1299620''>only</span> <span m=''1300020''>the</span>
  <span m=''1300110''>free</span> <span m=''1300380''>list</span> <span m=''1300680''>on</span>
  <span m=''1300840''>it,</span> <span m=''1300960''>there''s</span> <span m=''1301130''>no</span>
  <span m=''1301330''>actually</span> <span m=''1301690''>used</span> <span m=''1302070''>elements</span>
  <span m=''1302870''>by</span> <span m=''1303180''>the</span> <span m=''1303640''>programmer,</span>
  <span m=''1305140''>the</span> <span m=''1305330''>virtual</span> <span m=''1305660''>memory</span>
  <span m=''1305950''>system</span> <span m=''1306290''>will</span> <span m=''1306430''>page</span>
  <span m=''1306760''>it</span> <span m=''1306820''>out.</span> <span m=''1307550''>And</span>
  <span m=''1307740''>since</span> <span m=''1308230''>the</span> <span m=''1308340''>programmer''s</span>
  <span m=''1308900''>never</span> <span m=''1309170''>referencing</span> <span m=''1309810''>things</span>
  <span m=''1310100''>on</span> <span m=''1310220''>that</span> <span m=''1310470''>page,</span>
  <span m=''1311500''>it</span> <span m=''1311650''>basically</span> <span m=''1312260''>costs</span>
  <span m=''1312690''>you</span> <span m=''1312970''>nothing.</span> <span m=''1313400''>You</span>
  <span m=''1313550''>end</span> <span m=''1313710''>up</span> <span m=''1314040''>not</span>
  <span m=''1314280''>having</span> <span m=''1314620''>to</span> <span m=''1314690''>have</span>
  <span m=''1314880''>an</span> <span m=''1314960''>entry</span> <span m=''1315240''>in</span>
  <span m=''1315310''>the</span> <span m=''1315410''>TLB,</span> <span m=''1316420''>and</span>
  <span m=''1316610''>you</span> <span m=''1319570''>may</span> <span m=''1319710''>have</span>
  <span m=''1319870''>written</span> <span m=''1320220''>to</span> <span m=''1320450''>it,</span>
  <span m=''1320640''>but</span> <span m=''1320790''>you</span> <span m=''1321240''>will</span>
  <span m=''1321570''>end</span> <span m=''1321820''>up</span> <span m=''1322330''>allocating</span>
  <span m=''1322890''>things</span> <span m=''1323110''>preferentially</span> <span
  m=''1324370''>to</span> <span m=''1324580''>the</span> <span m=''1324720''>more</span>
  <span m=''1325070''>full</span> <span m=''1326600''>pages.</span> </p><p><span m=''1327770''>And</span>
  <span m=''1328050''>the</span> <span m=''1328180''>basic</span> <span m=''1328610''>idea</span>
  <span m=''1329180''>is,</span> <span m=''1329590''>it''s</span> <span m=''1329730''>better</span>
  <span m=''1330090''>to</span> <span m=''1330310''>have</span> <span m=''1331250''>the</span>
  <span m=''1331360''>use</span> <span m=''1331740''>of</span> <span m=''1331840''>your</span>
  <span m=''1331980''>pages</span> <span m=''1332750''>balance</span> <span m=''1333160''>90/10</span>
  <span m=''1334076''>than</span> <span m=''1334534''>50/50.</span> <span m=''1335720''>So</span>
  <span m=''1335930''>this</span> <span m=''1336170''>kind</span> <span m=''1336330''>[?
  of fig ?]</span> <span m=''1336650''>configuration</span> <span m=''1337320''>is</span>
  <span m=''1337440''>better</span> <span m=''1337750''>than</span> <span m=''1337910''>that.</span>
  <span m=''1340160''>So</span> <span m=''1340780''>why</span> <span m=''1341100''>is</span>
  <span m=''1341320''>that?</span> <span m=''1342590''>If</span> <span m=''1342760''>you</span>
  <span m=''1342990''>have</span> <span m=''1343220''>90%</span> <span m=''1343690''>of</span>
  <span m=''1344080''>your</span> <span m=''1344230''>storage</span> <span m=''1344730''>on</span>
  <span m=''1344920''>one</span> <span m=''1345200''>page</span> <span m=''1345640''>and</span>
  <span m=''1345740''>only</span> <span m=''1347450''>10%</span> <span m=''1348280''>on</span>
  <span m=''1348510''>another--</span> <span m=''1350940''>yeah,</span> <span m=''1351770''>let''s</span>
  <span m=''1351990''>say</span> <span m=''1352080''>we</span> <span m=''1352200''>only
  of</span> <span m=''1352460''>two</span> <span m=''1352610''>pages</span> <span
  m=''1353040''>in</span> <span m=''1353110''>our</span> <span m=''1353220''>system,</span>
  <span m=''1353990''>and</span> <span m=''1354140''>90%</span> <span m=''1354850''>of</span>
  <span m=''1354990''>the</span> <span m=''1355380''>objects</span> <span m=''1356080''>are</span>
  <span m=''1356160''>on</span> <span m=''1356310''>one</span> <span m=''1356530''>page,</span>
  <span m=''1356860''>and</span> <span m=''1358230''>10%</span> <span m=''1358590''>of</span>
  <span m=''1358750''>the</span> <span m=''1358860''>objects</span> <span m=''1359210''>are</span>
  <span m=''1359310''>on</span> <span m=''1359400''>the</span> <span m=''1359520''>other</span>
  <span m=''1359710''>page,</span> <span m=''1360370''>versus</span> <span m=''1360710''>if</span>
  <span m=''1360820''>they''re</span> <span m=''1360940''>50-50.</span> <span m=''1362210''>Then</span>
  <span m=''1362460''>what</span> <span m=''1363140''>you</span> <span m=''1363280''>can</span>
  <span m=''1363420''>do</span> <span m=''1363600''>is</span> <span m=''1363710''>look</span>
  <span m=''1363950''>at</span> <span m=''1364080''>the</span> <span m=''1364180''>probability</span>
  <span m=''1365750''>that</span> <span m=''1366600''>two</span> <span m=''1366860''>accesses</span>
  <span m=''1368040''>are</span> <span m=''1368190''>going</span> <span m=''1368340''>to</span>
  <span m=''1368380''>go</span> <span m=''1368630''>to</span> <span m=''1368790''>the</span>
  <span m=''1368900''>same</span> <span m=''1369310''>page.</span> <span m=''1371050''>Because</span>
  <span m=''1372080''>if</span> <span m=''1372190''>you''re</span> <span m=''1372290''>going</span>
  <span m=''1372530''>to</span> <span m=''1372610''>the</span> <span m=''1372670''>same</span>
  <span m=''1372950''>page,</span> <span m=''1373370''>then</span> <span m=''1373630''>your</span>
  <span m=''1374460''>paging</span> <span m=''1374870''>hardware,</span> <span m=''1375390''>which</span>
  <span m=''1375550''>is</span> <span m=''1375660''>very</span> <span m=''1375860''>much</span>
  <span m=''1376110''>like</span> <span m=''1376290''>the</span> <span m=''1376390''>cache,</span>
  <span m=''1377220''>your</span> <span m=''1377400''>TLB,</span> <span m=''1378060''>which</span>
  <span m=''1378250''>is</span> <span m=''1378360''>very</span> <span m=''1378580''>much</span>
  <span m=''1378800''>like</span> <span m=''1378960''>a</span> <span m=''1379050''>cache--</span>
  <span m=''1380330''>whenever</span> <span m=''1380710''>you</span> <span m=''1380840''>get</span>
  <span m=''1380920''>a</span> <span m=''1381000''>hit</span> <span m=''1381290''>on</span>
  <span m=''1381390''>the</span> <span m=''1381500''>same</span> <span m=''1381780''>page,</span>
  <span m=''1382450''>that''s</span> <span m=''1382730''>good,</span> <span m=''1382920''>it</span>
  <span m=''1383010''>costs</span> <span m=''1383330''>you</span> <span m=''1383430''>nothing.</span>
  <span m=''1384190''>If</span> <span m=''1384320''>you</span> <span m=''1384400''>hit</span>
  <span m=''1384560''>on</span> <span m=''1384700''>a</span> <span m=''1384730''>different</span>
  <span m=''1385160''>page,</span> <span m=''1385550''>that''s</span> <span m=''1385840''>bad.</span>
  </p><p><span m=''1386760''>So</span> <span m=''1386900''>what</span> <span m=''1386990''>happens</span>
  <span m=''1387470''>is,</span> <span m=''1387650''>the</span> <span m=''1387730''>probability</span>
  <span m=''1388140''>that</span> <span m=''1388390''>two</span> <span m=''1388710''>hit</span>
  <span m=''1388840''>the</span> <span m=''1388910''>same</span> <span m=''1389170''>page</span>
  <span m=''1389590''>is,</span> <span m=''1390230''>well,</span> <span m=''1390440''>for</span>
  <span m=''1390530''>the</span> <span m=''1390630''>first</span> <span m=''1390980''>one,</span>
  <span m=''1391170''>it''s,</span> <span m=''1391370''>what''s</span> <span m=''1391710''>the</span>
  <span m=''1391830''>probability</span> <span m=''1392460''>that</span> <span m=''1392710''>the</span>
  <span m=''1392800''>first</span> <span m=''1393160''>one</span> <span m=''1393350''>was</span>
  <span m=''1393710''>on</span> <span m=''1393920''>this</span> <span m=''1394140''>page,</span>
  <span m=''1394930''>versus</span> <span m=''1396170''>on</span> <span m=''1396420''>the</span>
  <span m=''1396570''>other?</span> <span m=''1396900''>So</span> <span m=''1397300''>it''s</span>
  <span m=''1397500''>going</span> <span m=''1397590''>to</span> <span m=''1397630''>be</span>
  <span m=''1397760''>on</span> <span m=''1397840''>the</span> <span m=''1397910''>same</span>
  <span m=''1398220''>page</span> <span m=''1398690''>if</span> <span m=''1398970''>they''re</span>
  <span m=''1399100''>both</span> <span m=''1399460''>on</span> <span m=''1399580''>this</span>
  <span m=''1399800''>page</span> <span m=''1400490''>or</span> <span m=''1400630''>they''re</span>
  <span m=''1400760''>both</span> <span m=''1401060''>on</span> <span m=''1401160''>this</span>
  <span m=''1401370''>page.</span> <span m=''1402230''>And</span> <span m=''1402360''>so</span>
  <span m=''1402460''>that''s</span> <span m=''1402670''>going</span> <span m=''1402740''>to</span>
  <span m=''1402810''>be</span> <span m=''1402920''>0.9</span> <span m=''1403600''>times</span>
  <span m=''1403940''>0.9</span> <span m=''1404580''>plus</span> <span m=''1404930''>0.1</span>
  <span m=''1405840''>times</span> <span m=''1406120''>0.1.</span> <span m=''1407330''>Whereas
  if</span> <span m=''1407650''>it''s</span> <span m=''1408200''>50/50,</span> <span
  m=''1409200''>then</span> <span m=''1409900''>the</span> <span m=''1410000''>probability</span>
  <span m=''1410690''>that</span> <span m=''1410870''>you</span> <span m=''1410980''>get</span>
  <span m=''1411170''>hit</span> <span m=''1411400''>on</span> <span m=''1411490''>the</span>
  <span m=''1411590''>same</span> <span m=''1411870''>page</span> <span m=''1412320''>is</span>
  <span m=''1412440''>now</span> <span m=''1412730''>this</span> <span m=''1413470''>0.5</span>
  <span m=''1414110''>times</span> <span m=''1414440''>0.5</span> <span m=''1415660''>plus</span>
  <span m=''1416240''>0.5</span> <span m=''1416820''>times</span> <span m=''1417070''>0.5,</span>
  <span m=''1418450''>which</span> <span m=''1418670''>is</span> <span m=''1418750''>only</span>
  <span m=''1418960''>50%.</span> <span m=''1419460''>So</span> <span m=''1419690''>we</span>
  <span m=''1419780''>get</span> <span m=''1419920''>82%</span> <span m=''1420820''>hit</span>
  <span m=''1421040''>rate</span> <span m=''1421700''>versus</span> <span m=''1422040''>the</span>
  <span m=''1422120''>50%</span> <span m=''1423020''>hit</span> <span m=''1423230''>rate.</span>
  <span m=''1425520''>So</span> <span m=''1425670''>it''s</span> <span m=''1425770''>much</span>
  <span m=''1426020''>more</span> <span m=''1426240''>likely,</span> <span m=''1426770''>if</span>
  <span m=''1426900''>I''m</span> <span m=''1427020''>stacking</span> <span m=''1427570''>everything</span>
  <span m=''1427910''>out</span> <span m=''1428070''>in</span> <span m=''1428200''>the</span>
  <span m=''1428390''>extreme,</span> <span m=''1429240''>it''s</span> <span m=''1429420''>better</span>
  <span m=''1429670''>to</span> <span m=''1429740''>have</span> <span m=''1429910''>everything</span>
  <span m=''1430340''>on</span> <span m=''1430530''>one</span> <span m=''1430770''>page</span>
  <span m=''1431140''>and</span> <span m=''1431240''>nothing</span> <span m=''1431550''>on</span>
  <span m=''1431700''>the</span> <span m=''1431840''>other.</span> <span m=''1432890''>Then</span>
  <span m=''1433020''>I</span> <span m=''1433080''>get</span> <span m=''1433230''>100%</span>
  <span m=''1433920''>hit</span> <span m=''1434140''>rate,</span> <span m=''1434380''>because</span>
  <span m=''1434600''>whenever</span> <span m=''1434930''>I''m</span> <span m=''1435050''>accessing</span>
  <span m=''1435640''>something,</span> <span m=''1437070''>I</span> <span m=''1437210''>always</span>
  <span m=''1437590''>am</span> <span m=''1437680''>hitting</span> <span m=''1437960''>on</span>
  <span m=''1438080''>the</span> <span m=''1438160''>page</span> <span m=''1438480''>I</span>
  <span m=''1438550''>had</span> <span m=''1438800''>before.</span> </p><p><span m=''1440750''>So</span>
  <span m=''1440930''>this</span> <span m=''1441250''>kind</span> <span m=''1441480''>of</span>
  <span m=''1441630''>heuristic</span> <span m=''1442740''>helps</span> <span m=''1443130''>it</span>
  <span m=''1443290''>so</span> <span m=''1443480''>that</span> <span m=''1443640''>you''re</span>
  <span m=''1443770''>swinging</span> <span m=''1444510''>your</span> <span m=''1446830''>accesses</span>
  <span m=''1447530''>to</span> <span m=''1447630''>using</span> <span m=''1448100''>fewer</span>
  <span m=''1448490''>pages,</span> <span m=''1449520''>and</span> <span m=''1449750''>the</span>
  <span m=''1449940''>fewer</span> <span m=''1450360''>pages,</span> <span m=''1451290''>the</span>
  <span m=''1451390''>less</span> <span m=''1451680''>likely</span> <span m=''1452140''>it</span>
  <span m=''1452220''>is</span> <span m=''1452830''>that</span> <span m=''1452980''>you''re</span>
  <span m=''1453130''>going</span> <span m=''1453250''>to</span> <span m=''1453300''>stress</span>
  <span m=''1453810''>your</span> <span m=''1453990''>virtual</span> <span m=''1454370''>memory</span>
  <span m=''1454690''>paging,</span> <span m=''1455820''>disk</span> <span m=''1456090''>swapping,</span>
  <span m=''1456620''>you''re</span> <span m=''1456860''>going</span> <span m=''1456920''>to</span>
  <span m=''1456990''>stress</span> <span m=''1457400''>your</span> <span m=''1457530''>TLB</span>
  <span m=''1458110''>and</span> <span m=''1458220''>what</span> <span m=''1458370''>have</span>
  <span m=''1458610''>you.</span> <span m=''1461770''>Good</span> <span m=''1462290''>for</span>
  <span m=''1462380''>that?</span> <span m=''1463660''>We''re</span> <span m=''1463830''>going</span>
  <span m=''1463910''>to</span> <span m=''1463950''>get</span> <span m=''1464150''>deeper</span>
  <span m=''1464470''>into</span> <span m=''1464650''>this,</span> <span m=''1464870''>so.</span>
  </p><p><span m=''1470130''>So</span> <span m=''1470330''>that''s</span> <span m=''1470590''>basically</span>
  <span m=''1471910''>fixed</span> <span m=''1472320''>size</span> <span m=''1472700''>allocation.</span>
  <span m=''1473270''>It''s</span> <span m=''1473340''>really</span> <span m=''1473630''>nice,</span>
  <span m=''1473920''>because</span> <span m=''1474080''>you</span> <span m=''1474180''>can</span>
  <span m=''1474280''>basically</span> <span m=''1474730''>use</span> <span m=''1474920''>a</span>
  <span m=''1474990''>very</span> <span m=''1475230''>simple</span> <span m=''1475600''>free</span>
  <span m=''1475880''>list.</span> <span m=''1477220''>But</span> <span m=''1477400''>of</span>
  <span m=''1477490''>course</span> <span m=''1477810''>what</span> <span m=''1478050''>most</span>
  <span m=''1478370''>people</span> <span m=''1479010''>need</span> <span m=''1479270''>and</span>
  <span m=''1479380''>want</span> <span m=''1479670''>is</span> <span m=''1479890''>variable</span>
  <span m=''1480350''>sized</span> <span m=''1480760''>allocation.</span> <span m=''1482240''>The</span>
  <span m=''1482330''>most</span> <span m=''1482570''>popular</span> <span m=''1483100''>way</span>
  <span m=''1483360''>of</span> <span m=''1483470''>doing</span> <span m=''1485310''>variable</span>
  <span m=''1485700''>sized</span> <span m=''1486040''>allocation</span> <span m=''1486660''>is</span>
  <span m=''1486780''>a</span> <span m=''1486830''>scheme</span> <span m=''1487170''>called</span>
  <span m=''1487490''>binned</span> <span m=''1487850''>free</span> <span m=''1488100''>lists,</span>
  <span m=''1488920''>and</span> <span m=''1489240''>of</span> <span m=''1489360''>that,</span>
  <span m=''1489700''>then</span> <span m=''1489860''>there</span> <span m=''1490020''>are</span>
  <span m=''1490050''>a</span> <span m=''1490090''>zillion</span> <span m=''1490560''>variations</span>
  <span m=''1491250''>on</span> <span m=''1491420''>it.</span> <span m=''1491680''>But</span>
  <span m=''1491910''>mostly,</span> <span m=''1492370''>people</span> <span m=''1492630''>use</span>
  <span m=''1492900''>binned</span> <span m=''1493150''>free lists.</span> </p><p><span
  m=''1495180''>The</span> <span m=''1495300''>idea</span> <span m=''1495670''>is,</span>
  <span m=''1495970''>we''re</span> <span m=''1496080''>going</span> <span m=''1496160''>to</span>
  <span m=''1496450''>leverage</span> <span m=''1497000''>the</span> <span m=''1497140''>efficiency</span>
  <span m=''1498070''>of</span> <span m=''1498330''>normal</span> <span m=''1498820''>free</span>
  <span m=''1499070''>lists.</span> <span m=''1499880''>Normal</span> <span m=''1500130''>free</span>
  <span m=''1500330''>lists</span> <span m=''1500560''>I</span> <span m=''1500640''>can</span>
  <span m=''1500780''>allocate</span> <span m=''1501360''>and</span> <span m=''1501480''>free</span>
  <span m=''1502210''>in</span> <span m=''1502350''>just</span> <span m=''1502600''>one</span>
  <span m=''1502800''>operation,</span> <span m=''1503820''>in</span> <span m=''1504410''>just</span>
  <span m=''1504690''>a</span> <span m=''1504850''>constant</span> <span m=''1505240''>amount
  of</span> <span m=''1505390''>time I</span> <span m=''1505725''>make.</span> <span
  m=''1507370''>And</span> <span m=''1507460''>what</span> <span m=''1507600''>we''re</span>
  <span m=''1507690''>going</span> <span m=''1507780''>to</span> <span m=''1507840''>do</span>
  <span m=''1508010''>is</span> <span m=''1508130''>accept</span> <span m=''1508630''>some</span>
  <span m=''1508970''>internal</span> <span m=''1509700''>fragmentation.</span> <span
  m=''1511220''>So</span> <span m=''1511370''>by</span> <span m=''1511520''>internal</span>
  <span m=''1511930''>fragmentation</span> <span m=''1512740''>I</span> <span m=''1512780''>mean</span>
  <span m=''1513200''>the</span> <span m=''1513330''>following.</span> <span m=''1514080''>When</span>
  <span m=''1515390''>somebody</span> <span m=''1515910''>asks</span> <span m=''1516550''>for</span>
  <span m=''1516690''>something</span> <span m=''1517160''>of</span> <span m=''1517250''>a</span>
  <span m=''1517300''>given</span> <span m=''1517640''>size,</span> <span m=''1519130''>what</span>
  <span m=''1519300''>we''re</span> <span m=''1519480''>going</span> <span m=''1519580''>to</span>
  <span m=''1519670''>do</span> <span m=''1520350''>is</span> <span m=''1521010''>actually</span>
  <span m=''1521520''>give</span> <span m=''1521810''>them</span> <span m=''1522430''>something</span>
  <span m=''1523200''>which</span> <span m=''1523600''>is</span> <span m=''1524280''>a</span>
  <span m=''1524390''>little</span> <span m=''1524610''>bit</span> <span m=''1524790''>bigger,</span>
  <span m=''1525100''>maybe.</span> <span m=''1527350''>And</span> <span m=''1527530''>so</span>
  <span m=''1527660''>we''ll</span> <span m=''1527890''>waste</span> <span m=''1528460''>some.</span>
  </p><p><span m=''1528815''>And</span> <span m=''1529170''>in</span> <span m=''1529250''>particular,</span>
  <span m=''1529860''>what</span> <span m=''1530090''>we''ll</span> <span m=''1530260''>do</span>
  <span m=''1530730''>is,</span> <span m=''1531070''>we''ll</span> <span m=''1531750''>organize</span>
  <span m=''1532360''>our</span> <span m=''1532460''>system</span> <span m=''1532930''>so</span>
  <span m=''1533140''>that</span> <span m=''1533700''>all</span> <span m=''1534160''>the</span>
  <span m=''1535030''>blocks</span> <span m=''1535530''>that</span> <span m=''1535640''>we</span>
  <span m=''1535790''>ever</span> <span m=''1536000''>give</span> <span m=''1536190''>out</span>
  <span m=''1536400''>are</span> <span m=''1536550''>always</span> <span m=''1536890''>a</span>
  <span m=''1536950''>size</span> <span m=''1537350''>the</span> <span m=''1537400''>power</span>
  <span m=''1537790''>of</span> <span m=''1537880''>two.</span> <span m=''1539250''>In</span>
  <span m=''1539380''>practice,</span> <span m=''1540050''>you</span> <span m=''1540190''>don''t</span>
  <span m=''1540370''>always</span> <span m=''1540690''>give</span> <span m=''1540850''>out</span>
  <span m=''1541020''>exactly</span> <span m=''1541520''>a</span> <span m=''1541570''>power</span>
  <span m=''1541880''>of</span> <span m=''1541980''>two,</span> <span m=''1542190''>because</span>
  <span m=''1542530''>then</span> <span m=''1542690''>you</span> <span m=''1542780''>get</span>
  <span m=''1542970''>cache</span> <span m=''1543300''>alignment</span> <span m=''1543770''>problems.</span>
  <span m=''1544260''>But</span> <span m=''1544400''>this</span> <span m=''1544560''>is</span>
  <span m=''1545870''>the</span> <span m=''1545970''>basic</span> <span m=''1546340''>scheme,</span>
  <span m=''1547930''>is</span> <span m=''1548130''>to</span> <span m=''1548240''>give</span>
  <span m=''1548440''>out</span> <span m=''1548700''>things</span> <span m=''1548960''>are</span>
  <span m=''1549090''>powers</span> <span m=''1549560''>of</span> <span m=''1549660''>two.</span>
  <span m=''1550880''>And</span> <span m=''1551040''>that</span> <span m=''1551240''>way,</span>
  <span m=''1551710''>if</span> <span m=''1551770''>somebody</span> <span m=''1552090''>asks</span>
  <span m=''1552340''>for</span> <span m=''1552450''>something</span> <span m=''1552890''>that</span>
  <span m=''1553000''>has</span> <span m=''1553400''>13</span> <span m=''1553930''>bytes,</span>
  <span m=''1554310''>you</span> <span m=''1554410''>give</span> <span m=''1554600''>them</span>
  <span m=''1554780''>16</span> <span m=''1555310''>bytes.</span> <span m=''1557270''>For</span>
  <span m=''1557580''>somebody</span> <span m=''1557910''>who</span> <span m=''1558010''>asked</span>
  <span m=''1558390''>for</span> <span m=''1558560''>65</span> <span m=''1559470''>bytes,</span>
  <span m=''1560560''>have</span> <span m=''1560710''>to</span> <span m=''1560780''>give</span>
  <span m=''1560970''>them</span> <span m=''1561100''>128</span> <span m=''1561990''>bytes.</span>
  <span m=''1563570''>So</span> <span m=''1563700''>you</span> <span m=''1563780''>might</span>
  <span m=''1564070''>waste</span> <span m=''1564580''>up</span> <span m=''1564840''>to</span>
  <span m=''1565140''>as</span> <span m=''1565340''>much</span> <span m=''1565690''>as</span>
  <span m=''1566070''>a</span> <span m=''1566140''>factor</span> <span m=''1566580''>of</span>
  <span m=''1566670''>two.</span> </p><p><span m=''1567630''>But</span> <span m=''1567780''>now,</span>
  <span m=''1569240''>for</span> <span m=''1569400''>a</span> <span m=''1569440''>given</span>
  <span m=''1569810''>that</span> <span m=''1569960''>range</span> <span m=''1570430''>of</span>
  <span m=''1570500''>values,</span> <span m=''1571150''>there''s</span> <span m=''1571310''>only</span>
  <span m=''1571590''>a</span> <span m=''1571650''>logarithmic</span> <span m=''1572530''>number</span>
  <span m=''1573160''>of</span> <span m=''1573400''>different</span> <span m=''1573950''>sizes</span>
  <span m=''1574560''>that</span> <span m=''1574660''>we</span> <span m=''1574760''>have</span>
  <span m=''1575000''>to</span> <span m=''1575100''>give</span> <span m=''1575290''>out,</span>
  <span m=''1575830''>because</span> <span m=''1575970''>we''re</span> <span m=''1576070''>only</span>
  <span m=''1576260''>giving</span> <span m=''1576520''>them</span> <span m=''1576610''>out
  in</span> <span m=''1576930''>powers</span> <span m=''1577350''>of</span> <span
  m=''1577450''>two.</span> </p><p><span m=''1579910''>So</span> <span m=''1581940''>here''s</span>
  <span m=''1582200''>the</span> <span m=''1582290''>basic</span> <span m=''1583910''>allocation</span>
  <span m=''1584590''>scheme</span> <span m=''1585020''>to</span> <span m=''1585140''>allocate</span>
  <span m=''1585830''>x bytes.</span> <span m=''1587430''>So</span> <span m=''1589320''>what</span>
  <span m=''1589540''>I</span> <span m=''1589630''>do</span> <span m=''1589990''>is,</span>
  <span m=''1590710''>if I''m</span> <span m=''1590970''>allocating</span> <span m=''1591560''>x
  bytes,</span> <span m=''1592220''>what</span> <span m=''1592350''>I</span> <span
  m=''1592420''>do</span> <span m=''1592660''>is,</span> <span m=''1592800''>I</span>
  <span m=''1592920''>look</span> <span m=''1593240''>in</span> <span m=''1593390''>the</span>
  <span m=''1594340''>bin</span> <span m=''1594710''>ceiling</span> <span m=''1595260''>of</span>
  <span m=''1595440''>log</span> <span m=''1595920''>x,</span> <span m=''1597880''>because</span>
  <span m=''1598130''>that''s</span> <span m=''1598490''>where</span> <span m=''1598870''>everything</span>
  <span m=''1599450''>of</span> <span m=''1599550''>size</span> <span m=''1600100''>two</span>
  <span m=''1600740''>to</span> <span m=''1600870''>the</span> <span m=''1600950''>ceiling</span>
  <span m=''1601370''>of</span> <span m=''1601450''>log</span> <span m=''1601790''>x</span>
  <span m=''1602050''>is,</span> <span m=''1602360''>which</span> <span m=''1602550''>is</span>
  <span m=''1602650''>basically</span> <span m=''1603110''>rounding</span> <span m=''1603600''>x
  up to</span> <span m=''1604070''>the</span> <span m=''1604260''>next</span> <span
  m=''1604460''>power</span> <span m=''1604890''>of two.</span> <span m=''1606890''>If</span>
  <span m=''1607060''>it''s</span> <span m=''1607210''>non-empty,</span> <span m=''1608330''>I</span>
  <span m=''1608450''>just</span> <span m=''1608660''>return</span> <span m=''1609060''>a</span>
  <span m=''1609110''>block</span> <span m=''1609660''>as</span> <span m=''1609920''>if</span>
  <span m=''1610060''>it</span> <span m=''1610220''>were</span> <span m=''1611750''>an</span>
  <span m=''1612240''>ordinary</span> <span m=''1612750''>free</span> <span m=''1613000''>list.</span>
  <span m=''1614030''>And</span> <span m=''1614140''>what</span> <span m=''1614260''>I''ll</span>
  <span m=''1614380''>be</span> <span m=''1614540''>doing</span> <span m=''1614860''>is</span>
  <span m=''1614980''>returning</span> <span m=''1615460''>a</span> <span m=''1615520''>block</span>
  <span m=''1615980''>which</span> <span m=''1616150''>is</span> <span m=''1616260''>at</span>
  <span m=''1616350''>most</span> <span m=''1616710''>twice</span> <span m=''1617080''>the</span>
  <span m=''1617180''>size</span> <span m=''1618140''>of</span> <span m=''1618340''>the</span>
  <span m=''1618440''>requested</span> <span m=''1618940''>block.</span> </p><p><span
  m=''1619380''>But</span> <span m=''1619580''>that''s</span> <span m=''1619890''>generally</span>
  <span m=''1620260''>OK.</span> <span m=''1621040''>Somebody</span> <span m=''1621680''>wants</span>
  <span m=''1622130''>at</span> <span m=''1622220''>least</span> <span m=''1622560''>that</span>
  <span m=''1622770''>many</span> <span m=''1622990''>bytes.</span> <span m=''1623940''>The</span>
  <span m=''1624030''>fact</span> <span m=''1624310''>that</span> <span m=''1624410''>it''s</span>
  <span m=''1624540''>a</span> <span m=''1624600''>few</span> <span m=''1624790''>more</span>
  <span m=''1625030''>bytes</span> <span m=''1625360''>won''t</span> <span m=''1625590''>matter</span>
  <span m=''1625920''>to</span> <span m=''1626030''>them.</span> <span m=''1626240''>They</span>
  <span m=''1626410''>don''t</span> <span m=''1626660''>know</span> <span m=''1626900''>that</span>
  <span m=''1627070''>there''s</span> <span m=''1627240''>more</span> <span m=''1627460''>bytes</span>
  <span m=''1628220''>hidden</span> <span m=''1628520''>there.</span> <span m=''1628800''>They</span>
  <span m=''1629180''>only</span> <span m=''1630040''>take</span> <span m=''1630260''>advantage</span>
  <span m=''1630690''>of</span> <span m=''1630740''>the</span> <span m=''1630790''>fact</span>
  <span m=''1631020''>that</span> <span m=''1631250''>there are</span> <span m=''1631500''>many</span>
  <span m=''1631720''>bytes</span> <span m=''1632050''>as</span> <span m=''1632200''>I''ve</span>
  <span m=''1632760''>asked</span> <span m=''1633120''>for.</span> </p><p><span m=''1635760''>Otherwise,</span>
  <span m=''1636630''>suppose</span> <span m=''1637170''>that</span> <span m=''1637270''>that</span>
  <span m=''1637670''>bin</span> <span m=''1637900''>is</span> <span m=''1638130''>empty.</span>
  <span m=''1640190''>There''s</span> <span m=''1640420''>nothing</span> <span m=''1640890''>in</span>
  <span m=''1641100''>that</span> <span m=''1641390''>bin</span> <span m=''1641680''>at</span>
  <span m=''1641830''>this</span> <span m=''1642040''>time.</span> <span m=''1642930''>Well,</span>
  <span m=''1643070''>then</span> <span m=''1643250''>what</span> <span m=''1643440''>you</span>
  <span m=''1643670''>do</span> <span m=''1643980''>is</span> <span m=''1644170''>you</span>
  <span m=''1644350''>start</span> <span m=''1644660''>looking</span> <span m=''1646820''>to
  find</span> <span m=''1647280''>a</span> <span m=''1647850''>block</span> <span
  m=''1648250''>in</span> <span m=''1648420''>the</span> <span m=''1648510''>next</span>
  <span m=''1648850''>larger</span> <span m=''1649350''>non-empty</span> <span m=''1649910''>bin,</span>
  <span m=''1650825''>and</span> <span m=''1651160''>you</span> <span m=''1651400''>split</span>
  <span m=''1651750''>it</span> <span m=''1651870''>up.</span> <span m=''1652430''>So</span>
  <span m=''1652600''>for</span> <span m=''1652700''>example</span> <span m=''1653070''>here,</span>
  <span m=''1653590''>suppose</span> <span m=''1653980''>that</span> <span m=''1654100''>the</span>
  <span m=''1654180''>request</span> <span m=''1654720''>is</span> <span m=''1654850''>x</span>
  <span m=''1655150''>equals</span> <span m=''1655540''>3.</span> <span m=''1656820''>I</span>
  <span m=''1656940''>have</span> <span m=''1657180''>to</span> <span m=''1657330''>look</span>
  <span m=''1657590''>in</span> <span m=''1657780''>bin</span> <span m=''1658110''>2,</span>
  <span m=''1658540''>which</span> <span m=''1658730''>is</span> <span m=''1658840''>blocks</span>
  <span m=''1659240''>of</span> <span m=''1659340''>size</span> <span m=''1659780''>4.</span>
  <span m=''1660705''>Uh</span> <span m=''1660960''>oh, bin</span> <span m=''1661320''>2</span>
  <span m=''1661650''>is</span> <span m=''1661800''>empty.</span> <span m=''1662960''>So</span>
  <span m=''1663100''>what</span> <span m=''1663220''>I</span> <span m=''1663300''>do</span>
  <span m=''1663540''>is,</span> <span m=''1663640''>I</span> <span m=''1663720''>start</span>
  <span m=''1664070''>going</span> <span m=''1664420''>down,</span> <span m=''1664820''>looking</span>
  <span m=''1665680''>in</span> <span m=''1665800''>the next bin.  Oops,</span> <span
  m=''1666070''>that''s</span> <span m=''1666270''>empty</span> <span m=''1666730''>too,</span>
  <span m=''1667290''>that''s</span> <span m=''1667630''>empty--</span> <span m=''1668190''>and</span>
  <span m=''1668360''>then</span> <span m=''1668510''>finally,</span> <span m=''1668900''>I</span>
  <span m=''1668970''>get</span> <span m=''1669180''>to</span> <span m=''1669280''>one</span>
  <span m=''1669500''>where</span> <span m=''1669590''>there</span> <span m=''1669780''>is</span>
  <span m=''1669960''>a</span> <span m=''1670000''>block</span> <span m=''1670340''>in
  it.</span> </p><p><span m=''1671960''>So</span> <span m=''1672150''>what</span>
  <span m=''1672390''>I</span> <span m=''1672530''>do</span> <span m=''1672780''>then</span>
  <span m=''1673010''>is</span> <span m=''1673180''>I</span> <span m=''1673290''>dice</span>
  <span m=''1673720''>this</span> <span m=''1673930''>up.</span> <span m=''1674160''>I</span>
  <span m=''1674450''>cut</span> <span m=''1674690''>it</span> <span m=''1674770''>in</span>
  <span m=''1674860''>half,</span> <span m=''1676780''>and</span> <span m=''1676960''>then</span>
  <span m=''1677150''>cut</span> <span m=''1677410''>that</span> <span m=''1677900''>one</span>
  <span m=''1678110''>in</span> <span m=''1678310''>half,</span> <span m=''1678520''>until</span>
  <span m=''1678800''>I</span> <span m=''1678890''>get</span> <span m=''1679090''>a</span>
  <span m=''1679140''>piece</span> <span m=''1679530''>that''s</span> <span m=''1679720''>exactly</span>
  <span m=''1680250''>the</span> <span m=''1680340''>size</span> <span m=''1680740''>I</span>
  <span m=''1680790''>want</span> <span m=''1681000''>to</span> <span m=''1681040''>return.</span>
  <span m=''1682490''>OK?</span> <span m=''1683180''>And</span> <span m=''1683310''>then</span>
  <span m=''1683450''>I</span> <span m=''1683540''>distribute</span> <span m=''1684180''>all</span>
  <span m=''1684520''>of</span> <span m=''1684580''>these</span> <span m=''1684840''>guys</span>
  <span m=''1685290''>up</span> <span m=''1685520''>to</span> <span m=''1685630''>the</span>
  <span m=''1685780''>other</span> <span m=''1685960''>bins,</span> <span m=''1686760''>like</span>
  <span m=''1686940''>this.</span> </p><p><span m=''1692230''>So</span> <span m=''1692380''>I</span>
  <span m=''1692510''>return</span> <span m=''1692990''>one</span> <span m=''1693190''>of</span>
  <span m=''1693270''>this</span> <span m=''1693540''>size,</span> <span m=''1694310''>and</span>
  <span m=''1694420''>I</span> <span m=''1694540''>populate</span> <span m=''1695190''>these</span>
  <span m=''1695370''>other</span> <span m=''1695570''>guys</span> <span m=''1698350''>with</span>
  <span m=''1698740''>one</span> <span m=''1699010''>block</span> <span m=''1699370''>each</span>
  <span m=''1699720''>of</span> <span m=''1699790''>the</span> <span m=''1699880''>appropriate</span>
  <span m=''1700370''>size.</span> <span m=''1702490''>And</span> <span m=''1702610''>as</span>
  <span m=''1702750''>you</span> <span m=''1702840''>can</span> <span m=''1702980''>see,</span>
  <span m=''1703190''>they''re</span> <span m=''1703300''>basically</span> <span m=''1703780''>growing</span>
  <span m=''1704560''>in</span> <span m=''1704750''>a</span> <span m=''1704910''>geometric</span>
  <span m=''1705430''>fashion.</span> <span m=''1707630''>And</span> <span m=''1707750''>then</span>
  <span m=''1707890''>I</span> <span m=''1708400''>distribute</span> <span m=''1708990''>that</span>
  <span m=''1709270''>bin.</span> </p><p><span m=''1710070''>Now</span> <span m=''1712580''>there''s</span>
  <span m=''1712750''>a</span> <span m=''1712800''>caveat</span> <span m=''1713380''>here.</span>
  <span m=''1713760''>Suppose</span> <span m=''1714370''>that</span> <span m=''1714590''>no</span>
  <span m=''1714850''>larger</span> <span m=''1715310''>blocks</span> <span m=''1715710''>exist</span>
  <span m=''1716210''>in</span> <span m=''1716380''>my</span> <span m=''1717210''>storage</span>
  <span m=''1717730''>structure.</span> <span m=''1719230''>Well,</span> <span m=''1719400''>then</span>
  <span m=''1719660''>I</span> <span m=''1719750''>have</span> <span m=''1719960''>to</span>
  <span m=''1720100''>ask</span> <span m=''1720490''>the</span> <span m=''1720680''>operating</span>
  <span m=''1721280''>system</span> <span m=''1723330''>for</span> <span m=''1723460''>more</span>
  <span m=''1723720''>bytes,</span> <span m=''1726550''>to</span> <span m=''1726650''>allocate</span>
  <span m=''1728430''>x</span> <span m=''1728650''>more</span> <span m=''1728850''>bytes</span>
  <span m=''1729210''>of</span> <span m=''1729310''>virtual</span> <span m=''1729680''>memory.</span>
  <span m=''1730860''>Now</span> <span m=''1731040''>in</span> <span m=''1731160''>practice</span>
  <span m=''1731720''>what</span> <span m=''1731850''>you</span> <span m=''1731940''>do</span>
  <span m=''1732070''>is</span> <span m=''1732170''>you</span> <span m=''1732240''>don''t</span>
  <span m=''1732410''>actually</span> <span m=''1732710''>ask</span> <span m=''1732990''>for</span>
  <span m=''1733150''>x, since</span> <span m=''1733540''>you</span> <span m=''1733620''>never</span>
  <span m=''1733910''>ask</span> <span m=''1734220''>the</span> <span m=''1734320''>operating</span>
  <span m=''1734620''>system</span> <span m=''1735270''>for</span> <span m=''1735430''>small</span>
  <span m=''1735740''>values.</span> <span m=''1736590''>You</span> <span m=''1736720''>always</span>
  <span m=''1737010''>ask</span> <span m=''1737270''>the</span> <span m=''1737400''>operating</span>
  <span m=''1737730''>system</span> <span m=''1738080''>for</span> <span m=''1738210''>big</span>
  <span m=''1738510''>values.</span> <span m=''1739300''>Give</span> <span m=''1739440''>me</span>
  <span m=''1739560''>another</span> <span m=''1739850''>page</span> <span m=''1740240''>worth,</span>
  <span m=''1740560''>or</span> <span m=''1740620''>give</span> <span m=''1740780''>me</span>
  <span m=''1740900''>another</span> <span m=''1741170''>five</span> <span m=''1741550''>pages,</span>
  <span m=''1741980''>or</span> <span m=''1742050''>something.</span> <span m=''1743110''>Because</span>
  <span m=''1743500''>that''s</span> <span m=''1743760''>an</span> <span m=''1743820''>expensive</span>
  <span m=''1744390''>call</span> <span m=''1745040''>to</span> <span m=''1745150''>the</span>
  <span m=''1745280''>operating</span> <span m=''1745660''>system,</span> <span m=''1746000''>to</span>
  <span m=''1746080''>ask</span> <span m=''1746460''>it</span> <span m=''1746680''>to</span>
  <span m=''1746770''>allocate</span> <span m=''1748030''>more</span> <span m=''1748330''>storage.</span>
  </p><p><span m=''1749130''>Let</span> <span m=''1749350''>me</span> <span m=''1749430''>explain</span>
  <span m=''1749860''>how</span> <span m=''1750050''>that</span> <span m=''1750290''>works.</span>
  <span m=''1750570''>And</span> <span m=''1750650''>this</span> <span m=''1750800''>gets</span>
  <span m=''1751050''>back</span> <span m=''1751280''>to</span> <span m=''1751370''>the</span>
  <span m=''1751460''>question</span> <span m=''1751790''>you</span> <span m=''1751910''>had</span>
  <span m=''1752140''>before,</span> <span m=''1752780''>which</span> <span m=''1753070''>is,</span>
  <span m=''1753500''>where''s</span> <span m=''1754070''>the</span> <span m=''1754160''>stuff</span>
  <span m=''1754450''>coming</span> <span m=''1754760''>from</span> <span m=''1755110''>anyway?</span>
  <span m=''1756460''>What</span> <span m=''1756640''>the</span> <span m=''1756780''>operating</span>
  <span m=''1757320''>system</span> <span m=''1757700''>is</span> <span m=''1757820''>allocating</span>
  <span m=''1758570''>is</span> <span m=''1758840''>actually</span> <span m=''1759200''>not</span>
  <span m=''1759570''>physical</span> <span m=''1760720''>pages,</span> <span m=''1761530''>but</span>
  <span m=''1761600''>rather</span> <span m=''1762080''>parts</span> <span m=''1762480''>of</span>
  <span m=''1762590''>virtual</span> <span m=''1763040''>memory.</span> <span m=''1764620''>So</span>
  <span m=''1766920''>we</span> <span m=''1767290''>looked</span> <span m=''1767530''>at</span>
  <span m=''1767630''>this</span> <span m=''1767860''>before,</span> <span m=''1768380''>about</span>
  <span m=''1768600''>how</span> <span m=''1768980''>virtual</span> <span m=''1769235''>memory</span>
  <span m=''1769680''>is</span> <span m=''1769830''>laid</span> <span m=''1770080''>out</span>
  <span m=''1770320''>for a</span> <span m=''1770450''>typical</span> <span m=''1770890''>program.</span>
  </p><p><span m=''1773150''>So</span> <span m=''1773370''>what</span> <span m=''1773500''>we</span>
  <span m=''1773610''>do</span> <span m=''1773770''>is,</span> <span m=''1774160''>on
  the</span> <span m=''1774330''>very</span> <span m=''1774620''>high</span> <span
  m=''1774940''>addresses,</span> <span m=''1775460''>we</span> <span m=''1775570''>have</span>
  <span m=''1775710''>the</span> <span m=''1775790''>stack,</span> <span m=''1776400''>and</span>
  <span m=''1776500''>the</span> <span m=''1776600''>stack</span> <span m=''1777010''>grows</span>
  <span m=''1777310''>downwards.</span> <span m=''1777760''>This</span> <span m=''1777920''>is</span>
  <span m=''1778030''>the</span> <span m=''1778130''>call</span> <span m=''1778570''>stack.</span>
  <span m=''1779480''>At</span> <span m=''1779620''>the</span> <span m=''1779700''>low</span>
  <span m=''1779990''>address,</span> <span m=''1780490''>we</span> <span m=''1780610''>typically</span>
  <span m=''1781010''>start</span> <span m=''1781350''>out</span> <span m=''1781630''>with</span>
  <span m=''1781750''>what''s</span> <span m=''1781940''>called</span> <span m=''1782130''>the</span>
  <span m=''1782210''>text</span> <span m=''1782560''>segment,</span> <span m=''1782950''>which</span>
  <span m=''1783100''>holds</span> <span m=''1783360''>your</span> <span m=''1783490''>code.</span>
  <span m=''1786320''>Then</span> <span m=''1786990''>there''s</span> <span m=''1787230''>a</span>
  <span m=''1787300''>region</span> <span m=''1788050''>called</span> <span m=''1788280''>the</span>
  <span m=''1788360''>data</span> <span m=''1788710''>segment,</span> <span m=''1789290''>and</span>
  <span m=''1789460''>this</span> <span m=''1789860''>consists</span> <span m=''1790360''>of</span>
  <span m=''1790500''>data</span> <span m=''1790800''>that</span> <span m=''1791270''>needs</span>
  <span m=''1791590''>to</span> <span m=''1791670''>be</span> <span m=''1791810''>initialized.</span>
  <span m=''1794480''>So</span> <span m=''1794930''>the</span> <span m=''1795600''>compiler</span>
  <span m=''1796220''>typically</span> <span m=''1796710''>distinguishes</span> <span
  m=''1797570''>between</span> <span m=''1797980''>data</span> <span m=''1798320''>that</span>
  <span m=''1798500''>needs</span> <span m=''1799130''>initialization</span> <span
  m=''1799980''>and</span> <span m=''1800190''>data</span> <span m=''1800490''>which</span>
  <span m=''1800700''>is</span> <span m=''1800820''>going</span> <span m=''1800910''>to</span>
  <span m=''1801010''>be</span> <span m=''1801160''>zero,</span> <span m=''1802310''>because</span>
  <span m=''1802940''>data</span> <span m=''1803210''>that</span> <span m=''1803350''>needs</span>
  <span m=''1803910''>initialization,</span> <span m=''1804400''>it</span> <span m=''1804610''>writes</span>
  <span m=''1804860''>into</span> <span m=''1805150''>the</span> <span m=''1805240''>binary</span>
  <span m=''1805700''>executable</span> <span m=''1806360''>file</span> <span m=''1807080''>and</span>
  <span m=''1807230''>stores</span> <span m=''1807620''>that</span> <span m=''1807820''>on</span>
  <span m=''1807980''>disk.</span> <span m=''1808610''>So</span> <span m=''1808770''>when</span>
  <span m=''1808880''>you</span> <span m=''1809000''>load</span> <span m=''1809270''>in</span>
  <span m=''1809360''>your</span> <span m=''1809490''>program,</span> <span m=''1810370''>it</span>
  <span m=''1810560''>just</span> <span m=''1810800''>loads</span> <span m=''1811190''>as</span>
  <span m=''1811320''>part</span> <span m=''1811580''>of</span> <span m=''1811640''>the</span>
  <span m=''1811740''>text</span> <span m=''1812130''>here, it</span> <span m=''1812400''>loads</span>
  <span m=''1812700''>that</span> <span m=''1812920''>data</span> <span m=''1813190''>segment,</span>
  <span m=''1814140''>saying</span> <span m=''1814560''>what</span> <span m=''1814710''>all</span>
  <span m=''1814990''>of</span> <span m=''1815070''>the</span> <span m=''1815240''>storage</span>
  <span m=''1815670''>is.</span> </p><p><span m=''1816370''>The</span> <span m=''1816480''>next</span>
  <span m=''1816850''>segment</span> <span m=''1817440''>is,</span> <span m=''1817650''>for</span>
  <span m=''1817790''>historical</span> <span m=''1818620''>reasons,</span> <span
  m=''1819050''>called</span> <span m=''1819320''>the</span> <span m=''1819390''>BSS</span>
  <span m=''1820060''>segment.</span> <span m=''1821250''>And</span> <span m=''1821370''>what</span>
  <span m=''1821720''>BSS</span> <span m=''1822350''>consists</span> <span m=''1822790''>of</span>
  <span m=''1823080''>is</span> <span m=''1824860''>all</span> <span m=''1825200''>the</span>
  <span m=''1825290''>variables</span> <span m=''1826420''>that</span> <span m=''1826600''>at</span>
  <span m=''1826700''>the</span> <span m=''1826780''>start</span> <span m=''1827100''>of</span>
  <span m=''1827140''>the</span> <span m=''1827220''>program</span> <span m=''1827700''>should</span>
  <span m=''1827840''>be</span> <span m=''1827990''>initialized</span> <span m=''1828610''>to</span>
  <span m=''1828720''>0.</span> <span m=''1830480''>It</span> <span m=''1830650''>doesn''t</span>
  <span m=''1830990''>bother</span> <span m=''1831390''>storing</span> <span m=''1832000''>these</span>
  <span m=''1833800''>in</span> <span m=''1833940''>the</span> <span m=''1834020''>file.</span>
  <span m=''1834700''>Why</span> <span m=''1834940''>not?</span> <span m=''1835500''>Because</span>
  <span m=''1835650''>it''s</span> <span m=''1835800''>easy</span> <span m=''1836110''>enough</span>
  <span m=''1836310''>to</span> <span m=''1836430''>just</span> <span m=''1836620''>bring</span>
  <span m=''1836930''>it</span> <span m=''1837040''>in,</span> <span m=''1837840''>understand</span>
  <span m=''1838520''>what</span> <span m=''1838750''>that</span> <span m=''1838980''>distance</span>
  <span m=''1839420''>there</span> <span m=''1839710''>is,</span> <span m=''1840020''>and</span>
  <span m=''1840240''>then</span> <span m=''1840530''>do</span> <span m=''1840900''>a</span>
  <span m=''1841650''>memset</span> <span m=''1843660''>of</span> <span m=''1843830''>this</span>
  <span m=''1843980''>whole</span> <span m=''1844250''>region</span> <span m=''1844920''>with</span>
  <span m=''1845120''>zero,</span> <span m=''1845630''>to</span> <span m=''1845720''>zero</span>
  <span m=''1846120''>it</span> <span m=''1846190''>out,</span> <span m=''1847660''>rather</span>
  <span m=''1848000''>than</span> <span m=''1848170''>trying</span> <span m=''1848350''>to</span>
  <span m=''1848540''>read</span> <span m=''1848850''>in</span> <span m=''1849350''>a</span>
  <span m=''1849400''>whole</span> <span m=''1849610''>bunch</span> <span m=''1849840''>of</span>
  <span m=''1849900''>zeroes.</span> <span m=''1852800''>An</span> <span m=''1853260''>obvious</span>
  <span m=''1853680''>kind</span> <span m=''1853800''>of</span> <span m=''1853930''>data</span>
  <span m=''1854190''>compression.</span> </p><p><span m=''1855790''>Then</span> <span
  m=''1856670''>heap</span> <span m=''1856950''>storage</span> <span m=''1857500''>is</span>
  <span m=''1857820''>allocated</span> <span m=''1859010''>in</span> <span m=''1859170''>the</span>
  <span m=''1859250''>space</span> <span m=''1859740''>above</span> <span m=''1860780''>the</span>
  <span m=''1860890''>BSS</span> <span m=''1861480''>segment.</span> <span m=''1862920''>So</span>
  <span m=''1863100''>the</span> <span m=''1863230''>idea</span> <span m=''1863630''>is,</span>
  <span m=''1863990''>there''s</span> <span m=''1864150''>a</span> <span m=''1864210''>part</span>
  <span m=''1864540''>of</span> <span m=''1864630''>heap</span> <span m=''1864990''>which</span>
  <span m=''1865180''>has</span> <span m=''1865290''>already</span> <span m=''1865530''>been</span>
  <span m=''1865700''>allocated</span> <span m=''1866290''>stuff.</span> <span m=''1867360''>And</span>
  <span m=''1867450''>whenever</span> <span m=''1867820''>you</span> <span m=''1867970''>need</span>
  <span m=''1868230''>more</span> <span m=''1868450''>heap</span> <span m=''1868700''>storage,</span>
  <span m=''1869750''>you</span> <span m=''1869900''>ask</span> <span m=''1870160''>the</span>
  <span m=''1870280''>operating</span> <span m=''1870740''>system--</span> <span m=''1871150''>the</span>
  <span m=''1871270''>operating</span> <span m=''1871610''>system</span> <span m=''1872040''>moves</span>
  <span m=''1872910''>just</span> <span m=''1873250''>as</span> <span m=''1873400''>if</span>
  <span m=''1873540''>it</span> <span m=''1873640''>were</span> <span m=''1873790''>a</span>
  <span m=''1873850''>stack,</span> <span m=''1874680''>moves</span> <span m=''1875190''>the</span>
  <span m=''1875290''>line</span> <span m=''1875950''>for</span> <span m=''1876170''>where</span>
  <span m=''1876520''>heap</span> <span m=''1876830''>is</span> <span m=''1878730''>to</span>
  <span m=''1878850''>allocate,</span> <span m=''1879590''>to</span> <span m=''1879690''>give</span>
  <span m=''1879950''>you</span> <span m=''1880100''>more</span> <span m=''1880400''>pages</span>
  <span m=''1880930''>of</span> <span m=''1881220''>heap</span> <span m=''1881490''>storage</span>
  <span m=''1881970''>that</span> <span m=''1882130''>you</span> <span m=''1882260''>can</span>
  <span m=''1882390''>now</span> <span m=''1882640''>allocate</span> <span m=''1883150''>out</span>
  <span m=''1883360''>of.</span> <span m=''1885660''>And</span> <span m=''1885880''>what</span>
  <span m=''1886020''>it''s</span> <span m=''1886170''>doing</span> <span m=''1886430''>is</span>
  <span m=''1886540''>allocating</span> <span m=''1887110''>pieces</span> <span m=''1887460''>of</span>
  <span m=''1887530''>virtual</span> <span m=''1887910''>memory.</span> </p><p><span
  m=''1891380''>Now,</span> <span m=''1893840''>here''s</span> <span m=''1894180''>a</span>
  <span m=''1895530''>good</span> <span m=''1895810''>mind</span> <span m=''1896140''>question,</span>
  <span m=''1896560''>which</span> <span m=''1896730''>I</span> <span m=''1896790''>think</span>
  <span m=''1897030''>gets</span> <span m=''1897630''>directly</span> <span m=''1898090''>to</span>
  <span m=''1898240''>your</span> <span m=''1898440''>point.</span> <span m=''1900570''>So</span>
  <span m=''1901320''>think</span> <span m=''1901580''>about</span> <span m=''1901880''>this.</span>
  <span m=''1902070''>We</span> <span m=''1902190''>have</span> <span m=''1902310''>a</span>
  <span m=''1902360''>64-bit</span> <span m=''1903210''>address</span> <span m=''1903670''>space.</span>
  <span m=''1905370''>If</span> <span m=''1905610''>I</span> <span m=''1905850''>try</span>
  <span m=''1906170''>to</span> <span m=''1906280''>write</span> <span m=''1906620''>at</span>
  <span m=''1906730''>the</span> <span m=''1906810''>rate</span> <span m=''1907070''>of</span>
  <span m=''1907220''>4</span> <span m=''1907490''>billion</span> <span m=''1907840''>bytes</span>
  <span m=''1908230''>per</span> <span m=''1908370''>second,</span> <span m=''1909480''>that''s</span>
  <span m=''1909690''>pretty</span> <span m=''1909900''>fast,</span> <span m=''1910290''>because</span>
  <span m=''1910470''>that''s</span> <span m=''1910800''>the</span> <span m=''1910900''>speed</span>
  <span m=''1911260''>at</span> <span m=''1911340''>which</span> <span m=''1911500''>the</span>
  <span m=''1911640''>registers</span> <span m=''1912220''>get written.</span> <span
  m=''1912590''>Not</span> <span m=''1912890''>the</span> <span m=''1912960''>speed</span>
  <span m=''1913260''>that</span> <span m=''1913380''>memory</span> <span m=''1913730''>gets</span>
  <span m=''1913930''>written.</span> <span m=''1915360''>So</span> <span m=''1916400''>really,</span>
  <span m=''1917340''>it''s</span> <span m=''1917660''>something</span> <span m=''1918060''>like</span>
  <span m=''1918240''>4</span> <span m=''1918460''>billion</span> <span m=''1918780''>bytes</span>
  <span m=''1919090''>per</span> <span m=''1919210''>second.</span> <span m=''1920060''>It</span>
  <span m=''1920220''>takes</span> <span m=''1920470''>over</span> <span m=''1920710''>a</span>
  <span m=''1920770''>century</span> <span m=''1922810''>to</span> <span m=''1922970''>write</span>
  <span m=''1923440''>all</span> <span m=''1923970''>of</span> <span m=''1924230''>virtual</span>
  <span m=''1924700''>memory.</span> </p><p><span m=''1927330''>So</span> <span m=''1927590''>as</span>
  <span m=''1927680''>a</span> <span m=''1927780''>practical</span> <span m=''1928400''>matter,</span>
  <span m=''1929460''>that</span> <span m=''1929670''>means</span> <span m=''1929950''>I</span>
  <span m=''1930100''>never</span> <span m=''1930550''>run</span> <span m=''1930840''>out</span>
  <span m=''1931080''>of</span> <span m=''1931170''>stack</span> <span m=''1931550''>space.</span>
  <span m=''1932600''>I</span> <span m=''1932710''>never</span> <span m=''1933040''>run</span>
  <span m=''1933320''>out</span> <span m=''1933550''>of</span> <span m=''1933670''>heap</span>
  <span m=''1933890''>space.</span> <span m=''1936370''>They''re</span> <span m=''1936500''>never</span>
  <span m=''1936830''>going</span> <span m=''1936990''>to</span> <span m=''1937060''>cross,</span>
  <span m=''1938120''>no</span> <span m=''1938180''>matter</span> <span m=''1938360''>how</span>
  <span m=''1938550''>much</span> <span m=''1938790''>I''m</span> <span m=''1938910''>allocating.</span>
  <span m=''1939760''>Even</span> <span m=''1939960''>if</span> <span m=''1940070''>I</span>
  <span m=''1940160''>allocate</span> <span m=''1940740''>on</span> <span m=''1940880''>every</span>
  <span m=''1941100''>cycle,</span> <span m=''1942310''>there''s</span> <span m=''1942510''>not</span>
  <span m=''1942720''>going</span> <span m=''1942830''>to</span> <span m=''1942870''>be</span>
  <span m=''1942980''>a</span> <span m=''1943040''>program--</span> <span m=''1943370''>unless
  you''re going to</span> <span m=''1943820''>set a</span> <span m=''1943950''>program</span>
  <span m=''1944450''>running</span> <span m=''1944780''>for</span> <span m=''1945010''>a</span>
  <span m=''1945250''>millennium</span> <span m=''1945740''>sort</span> <span m=''1945960''>of</span>
  <span m=''1946040''>thing,</span> <span m=''1948360''>you''re</span> <span m=''1948490''>not</span>
  <span m=''1948670''>going</span> <span m=''1948770''>to</span> <span m=''1948830''>see</span>
  <span m=''1949060''>that.</span> <span m=''1949550''>Most</span> <span m=''1949830''>programs</span>
  <span m=''1950270''>run</span> <span m=''1950520''>for</span> <span m=''1951010''>a</span>
  <span m=''1951090''>few</span> <span m=''1951280''>minutes.</span> <span m=''1953190''>Some</span>
  <span m=''1953420''>may</span> <span m=''1953580''>run</span> <span m=''1953800''>for</span>
  <span m=''1953930''>days.</span> <span m=''1954205''>Some</span> <span m=''1954510''>may</span>
  <span m=''1954720''>run</span> <span m=''1954920''>for</span> <span m=''1955040''>years.</span>
  <span m=''1955980''>Very</span> <span m=''1956190''>few</span> <span m=''1956460''>do</span>
  <span m=''1956730''>people</span> <span m=''1957070''>write</span> <span m=''1957320''>to</span>
  <span m=''1957420''>run</span> <span m=''1957620''>for a</span> <span m=''1957730''>century.</span>
  </p><p><span m=''1961370''>So</span> <span m=''1961700''>why</span> <span m=''1961950''>not</span>
  <span m=''1962090''>just</span> <span m=''1962370''>allocate</span> <span m=''1962980''>out</span>
  <span m=''1963150''>of</span> <span m=''1963330''>free</span> <span m=''1963980''>virtual</span>
  <span m=''1964330''>memory</span> <span m=''1964700''>and</span> <span m=''1964920''>never</span>
  <span m=''1965170''>bother</span> <span m=''1965520''>freeing?</span> <span m=''1965850''>Why</span>
  <span m=''1966030''>am</span> <span m=''1966160''>I</span> <span m=''1966260''>worried</span>
  <span m=''1966660''>about</span> <span m=''1966920''>freeing</span> <span m=''1967390''>stuff</span>
  <span m=''1967710''>all</span> <span m=''1967870''>the</span> <span m=''1967950''>time?</span>
  <span m=''1968810''>Why not</span> <span m=''1968970''>just</span> <span m=''1969260''>allocate</span>
  <span m=''1969670''>it?</span> <span m=''1970080''>It''s</span> <span m=''1970270''>virtual</span>
  <span m=''1970650''>memory.  It''s</span> <span m=''1971070''>virtual.</span> <span
  m=''1972150''>I</span> <span m=''1972220''>just</span> <span m=''1972410''>allocate</span>
  <span m=''1972960''>more</span> <span m=''1973170''>storage</span> <span m=''1973600''>as</span>
  <span m=''1973750''>I</span> <span m=''1973840''>need</span> <span m=''1973970''>it.</span>
  <span m=''1975290''>Yeah?</span> </p><p><span m=''1976090''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''1976535''>memory?</span> </p><p><span m=''1977870''>CHARLES LEISERSON:
  So</span> <span m=''1978080''>it</span> <span m=''1978210''>is</span> <span m=''1978400''>tied</span>
  <span m=''1978670''>to</span> <span m=''1978780''>real</span> <span m=''1979020''>memory,</span>
  <span m=''1979340''>and</span> <span m=''1979410''>that''s</span> <span m=''1979620''>part</span>
  <span m=''1979850''>of</span> <span m=''1979900''>the</span> <span m=''1980030''>answer.</span>
  <span m=''1981070''>It</span> <span m=''1981500''>is</span> <span m=''1981770''>tied</span>
  <span m=''1982000''>to</span> <span m=''1982100''>real</span> <span m=''1982290''>memory,</span>
  <span m=''1982560''>because</span> <span m=''1983190''>anything</span> <span m=''1983440''>that</span>
  <span m=''1983620''>you</span> <span m=''1983800''>write</span> <span m=''1984920''>must</span>
  <span m=''1985300''>find</span> <span m=''1985630''>itself</span> <span m=''1986200''>a</span>
  <span m=''1986300''>place</span> <span m=''1986720''>on</span> <span m=''1986920''>disk.</span>
  <span m=''1989030''>Because</span> <span m=''1989530''>it''s</span> <span m=''1989740''>going</span>
  <span m=''1989860''>to</span> <span m=''1989910''>be</span> <span m=''1990030''>written</span>
  <span m=''1990290''>to</span> <span m=''1990390''>pages,</span> <span m=''1990870''>and
  those</span> <span m=''1991110''>pages</span> <span m=''1991390''>are</span> <span
  m=''1991520''>going</span> <span m=''1991620''>to</span> <span m=''1991730''>be</span>
  <span m=''1991830''>paged</span> <span m=''1992700''>and</span> <span m=''1992940''>then</span>
  <span m=''1993610''>written</span> <span m=''1993940''>to</span> <span m=''1994020''>what''s</span>
  <span m=''1994220''>called</span> <span m=''1994460''>the</span> <span m=''1994520''>swap</span>
  <span m=''1994950''>space</span> <span m=''1995390''>on</span> <span m=''1995540''>disk,</span>
  <span m=''1996830''>which</span> <span m=''1997030''>allows</span> <span m=''1997430''>you</span>
  <span m=''1997680''>to</span> <span m=''1997830''>put</span> <span m=''1998070''>things</span>
  <span m=''1998320''>there.</span> </p><p><span m=''1998810''>Even</span> <span m=''1999140''>so,</span>
  <span m=''1999540''>though,</span> <span m=''2000130''>writing</span> <span m=''2000480''>to</span>
  <span m=''2000640''>disk--</span> <span m=''2003320''>it''s</span> <span m=''2003450''>still</span>
  <span m=''2003690''>not</span> <span m=''2003870''>going</span> <span m=''2003960''>to</span>
  <span m=''2004100''>take</span> <span m=''2005120''>very</span> <span m=''2005440''>long.</span>
  <span m=''2006450''>I</span> <span m=''2006470''>mean,</span> <span m=''2006660''>you''re</span>
  <span m=''2006790''>never</span> <span m=''2007070''>going</span> <span m=''2007170''>to</span>
  <span m=''2007210''>be</span> <span m=''2007390''>able</span> <span m=''2007520''>to</span>
  <span m=''2007580''>use</span> <span m=''2007830''>up</span> <span m=''2008060''>disk,</span>
  <span m=''2009000''>because</span> <span m=''2009270''>disk</span> <span m=''2009510''>takes</span>
  <span m=''2009820''>so</span> <span m=''2009900''>long</span> <span m=''2010160''>to</span>
  <span m=''2010260''>write</span> <span m=''2010500''>for.</span> <span m=''2011580''>But
  that</span> <span m=''2011730''>is</span> <span m=''2011890''>part of the</span>
  <span m=''2012270''>answer.</span> </p><p><span m=''2013109''>AUDIENCE: So you need
  to</span> <span m=''2014516''>basically</span> <span m=''2016861''>use</span> <span
  m=''2017330''>[INAUDIBLE]</span> <span m=''2018268''>software?</span> <span m=''2019206''>And
  so--</span> </p><p><span m=''2021040''>CHARLES LEISERSON: And</span> <span m=''2021230''>the</span>
  <span m=''2021300''>page</span> <span m=''2021650''>table.</span> </p><p><span m=''2022520''>AUDIENCE:
  [UNINTELLIGIBLE]</span> <span m=''2024560''>on the disk.</span> </p><p><span m=''2025260''>CHARLES
  LEISERSON: So</span> <span m=''2025680''>the</span> <span m=''2026023''>issue is,</span>
  <span m=''2026710''>this</span> <span m=''2026910''>is</span> <span m=''2027070''>where</span>
  <span m=''2027300''>the</span> <span m=''2027480''>external</span> <span m=''2027970''>fragmentation</span>
  <span m=''2028920''>would</span> <span m=''2029080''>be</span> <span m=''2029250''>horrendous.</span>
  <span m=''2030950''>If</span> <span m=''2031030''>you</span> <span m=''2031150''>just</span>
  <span m=''2031370''>kept</span> <span m=''2031580''>writing</span> <span m=''2031980''>across</span>
  <span m=''2032450''>memory,</span> <span m=''2033360''>and</span> <span m=''2033510''>you</span>
  <span m=''2033600''>only</span> <span m=''2033850''>had</span> <span m=''2034020''>a</span>
  <span m=''2034100''>couple</span> <span m=''2034470''>of</span> <span m=''2034550''>words</span>
  <span m=''2034930''>written</span> <span m=''2035300''>on</span> <span m=''2035470''>every</span>
  <span m=''2035740''>page</span> <span m=''2036180''>that</span> <span m=''2036300''>were</span>
  <span m=''2036450''>actually</span> <span m=''2036840''>used,</span> <span m=''2038950''>the</span>
  <span m=''2039080''>rest</span> <span m=''2039410''>is</span> <span m=''2039540''>just</span>
  <span m=''2039770''>garbage,</span> <span m=''2040750''>then</span> <span m=''2041650''>what</span>
  <span m=''2041830''>you''re</span> <span m=''2041950''>saying</span> <span m=''2042370''>is</span>
  <span m=''2042580''>that</span> <span m=''2042700''>in</span> <span m=''2042810''>order</span>
  <span m=''2043080''>to</span> <span m=''2043160''>access</span> <span m=''2043760''>a</span>
  <span m=''2043800''>given</span> <span m=''2044900''>datum,</span> <span m=''2045870''>I''m</span>
  <span m=''2046050''>not</span> <span m=''2046370''>going</span> <span m=''2046560''>to</span>
  <span m=''2046620''>have</span> <span m=''2046970''>it</span> <span m=''2047080''>in</span>
  <span m=''2047260''>memory</span> <span m=''2047940''>with</span> <span m=''2048170''>it</span>
  <span m=''2048300''>a</span> <span m=''2048409''>lot</span> <span m=''2048730''>of</span>
  <span m=''2048870''>other</span> <span m=''2049159''>stuff.</span> <span m=''2049659''>What</span>
  <span m=''2049770''>I''m</span> <span m=''2049850''>going</span> <span m=''2049940''>to</span>
  <span m=''2050060''>have</span> <span m=''2050190''>in</span> <span m=''2050300''>memory</span>
  <span m=''2050639''>with</span> <span m=''2050850''>it</span> <span m=''2050949''>is</span>
  <span m=''2051080''>going</span> <span m=''2051159''>to</span> <span m=''2051239''>be</span>
  <span m=''2051380''>all</span> <span m=''2051590''>garbage,</span> <span m=''2052850''>this</span>
  <span m=''2052989''>stuff</span> <span m=''2053260''>that</span> <span m=''2053460''>I</span>
  <span m=''2053560''>would</span> <span m=''2053760''>have</span> <span m=''2053909''>freed.</span>
  <span m=''2055500''>And</span> <span m=''2055639''>so</span> <span m=''2055790''>therefore,</span>
  <span m=''2056650''>you</span> <span m=''2056810''>end</span> <span m=''2057010''>up</span>
  <span m=''2057130''>having</span> <span m=''2057429''>your</span> <span m=''2057560''>program</span>
  <span m=''2058100''>distributed</span> <span m=''2058750''>across</span> <span m=''2059139''>a</span>
  <span m=''2059210''>large</span> <span m=''2060980''>region</span> <span m=''2061429''>of</span>
  <span m=''2061610''>virtual</span> <span m=''2061980''>memory,</span> <span m=''2062699''>and</span>
  <span m=''2062870''>that</span> <span m=''2063070''>means</span> <span m=''2063320''>as</span>
  <span m=''2063480''>we''re</span> <span m=''2063610''>doing</span> <span m=''2063870''>the</span>
  <span m=''2063949''>paging,</span> <span m=''2064469''>et</span> <span m=''2064570''>cetera,</span>
  <span m=''2065210''>we''re</span> <span m=''2065330''>getting</span> <span m=''2065630''>very</span>
  <span m=''2065989''>poor</span> <span m=''2068210''>page</span> <span m=''2068550''>locality</span>
  <span m=''2070070''>as</span> <span m=''2070330''>I''m</span> <span m=''2070469''>accessing</span>
  <span m=''2071100''>things.</span> </p><p><span m=''2071909''>And</span> <span m=''2072060''>so</span>
  <span m=''2072250''>I</span> <span m=''2072370''>have</span> <span m=''2072600''>a</span>
  <span m=''2072650''>finite</span> <span m=''2073130''>number</span> <span m=''2073350''>of</span>
  <span m=''2073429''>pages</span> <span m=''2073870''>that</span> <span m=''2074000''>I</span>
  <span m=''2074070''>fit</span> <span m=''2074320''>in</span> <span m=''2074429''>memory,</span>
  <span m=''2075409''>and</span> <span m=''2075610''>now</span> <span m=''2075820''>I</span>
  <span m=''2075940''>may</span> <span m=''2076150''>be</span> <span m=''2076320''>blowing</span>
  <span m=''2076750''>that</span> <span m=''2076960''>out,</span> <span m=''2077179''>and</span>
  <span m=''2077380''>every</span> <span m=''2077750''>access,</span> <span m=''2078280''>rather</span>
  <span m=''2078610''>than</span> <span m=''2078760''>going</span> <span m=''2078920''>to</span>
  <span m=''2079080''>something</span> <span m=''2079500''>nearby,</span> <span m=''2080350''>is</span>
  <span m=''2080520''>instead</span> <span m=''2080929''>going</span> <span m=''2081199''>to</span>
  <span m=''2081300''>disk.</span> <span m=''2082260''>And</span> <span m=''2082440''>so</span>
  <span m=''2082540''>that can</span> <span m=''2083570''>cause</span> <span m=''2083940''>disk</span>
  <span m=''2084270''>thrashing,</span> <span m=''2085790''>where</span> <span m=''2085949''>every</span>
  <span m=''2086280''>access</span> <span m=''2086770''>causes</span> <span m=''2087190''>a</span>
  <span m=''2087260''>disk</span> <span m=''2087570''>access.</span> <span m=''2088780''>So</span>
  <span m=''2088889''>how</span> <span m=''2089040''>fast are</span> <span m=''2089480''>disk</span>
  <span m=''2089770''>accesses?</span> <span m=''2091830''>Order of</span> <span m=''2092179''>magnitude?</span>
  <span m=''2096896''>How</span> <span m=''2097350''>fast are</span> <span m=''2097740''>disk</span>
  <span m=''2098010''>accesses?</span> <span m=''2098550''>What''s</span> <span m=''2098680''>a</span>
  <span m=''2098820''>disk</span> <span m=''2099100''>access</span> <span m=''2099480''>cost?</span>
  <span m=''2100680''>Fast disk?</span> </p><p><span m=''2104656''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''2110057''>CHARLES LEISERSON: No,</span> <span m=''2110560''>it''s</span>
  <span m=''2110720''>slower</span> <span m=''2111090''>than</span> <span m=''2111230''>that.</span>
  <span m=''2114054''>Disk</span> <span m=''2114535''>access.</span> <span m=''2115497''>So</span>
  <span m=''2115978''>good</span> <span m=''2116460''>memory</span> <span m=''2116530''>access,</span>
  <span m=''2117090''>DRAM</span> <span m=''2117460''>memory</span> <span m=''2117770''>is,</span>
  <span m=''2117870''>like,</span> <span m=''2118050''>60</span> <span m=''2118470''>nanoseconds</span>
  <span m=''2120600''>for</span> <span m=''2120980''>DRAM</span> <span m=''2121630''>access.</span>
  <span m=''2122070''>It''s</span> <span m=''2122200''>like</span> <span m=''2122380''>60</span>
  <span m=''2122790''>nanoseconds.</span> <span m=''2123810''>So</span> <span m=''2124090''>the</span>
  <span m=''2124320''>processor</span> <span m=''2124980''>is</span> <span m=''2125100''>going</span>
  <span m=''2125470''>somewhere</span> <span m=''2125800''>around,</span> <span m=''2126710''>these</span>
  <span m=''2126930''>days,</span> <span m=''2128460''>between</span> <span m=''2128810''>3</span>
  <span m=''2129170''>and</span> <span m=''2129300''>4</span> <span m=''2130180''>gigahertz.</span>
  <span m=''2132370''>So</span> <span m=''2133110''>memory</span> <span m=''2133600''>is</span>
  <span m=''2133810''>like</span> <span m=''2135830''>200</span> <span m=''2138000''>processor</span>
  <span m=''2138530''>cycles</span> <span m=''2138850''>away.</span> </p><p><span
  m=''2139210''>How</span> <span m=''2139410''>fast</span> <span m=''2139810''>is</span>
  <span m=''2139960''>disk?</span> <span m=''2141950''>An</span> <span m=''2142010''>ordinary</span>
  <span m=''2142490''>disk,</span> <span m=''2142730''>not</span> <span m=''2142870''>a</span>
  <span m=''2142910''>solid</span> <span m=''2143250''>state</span> <span m=''2144090''>device.</span>
  <span m=''2145050''>Ordinary</span> <span m=''2145430''>disk.</span> </p><p><span
  m=''2148720''>10</span> <span m=''2148940''>milliseconds</span> <span m=''2149540''>is</span>
  <span m=''2149690''>a</span> <span m=''2149720''>good</span> <span m=''2151110''>ballpark</span>
  <span m=''2151580''>to give.</span> <span m=''2151840''>That''s</span> <span m=''2152050''>a</span>
  <span m=''2152100''>good</span> <span m=''2152300''>number</span> <span m=''2152540''>to</span>
  <span m=''2152610''>know.</span> <span m=''2153040''>10</span> <span m=''2153730''>milliseconds,</span>
  <span m=''2155300''>not</span> <span m=''2155630''>10</span> <span m=''2156380''>microseconds,</span>
  <span m=''2156890''>not</span> <span m=''2157200''>10</span> <span m=''2157590''>nanoseconds.</span>
  <span m=''2158780''>10</span> <span m=''2159200''>milliseconds.</span> <span m=''2161510''>So</span>
  <span m=''2161730''>you</span> <span m=''2162030''>are,</span> <span m=''2163590''>what?</span>
  <span m=''2165510''>6</span> <span m=''2165810''>to</span> <span m=''2165910''>7</span>
  <span m=''2166330''>orders</span> <span m=''2166910''>of</span> <span m=''2167030''>magnitude</span>
  <span m=''2167820''>slower</span> <span m=''2168440''>if</span> <span m=''2168570''>you</span>
  <span m=''2168700''>go</span> <span m=''2168870''>to</span> <span m=''2168970''>disk.</span>
  <span m=''2171930''>Really</span> <span m=''2172350''>slow.</span> <span m=''2173840''>So</span>
  <span m=''2174040''>one</span> <span m=''2174240''>of</span> <span m=''2174290''>the</span>
  <span m=''2174340''>things</span> <span m=''2174620''>in</span> <span m=''2174740''>performance</span>
  <span m=''2175540''>optimization--</span> <span m=''2176280''>we''re</span> <span
  m=''2176440''>focusing</span> <span m=''2176960''>a</span> <span m=''2177010''>lot</span>
  <span m=''2177280''>on</span> <span m=''2177390''>the</span> <span m=''2177440''>CPU--</span>
  <span m=''2178630''>is</span> <span m=''2178790''>often</span> <span m=''2179170''>the</span>
  <span m=''2179260''>case</span> <span m=''2179710''>for</span> <span m=''2179860''>database</span>
  <span m=''2180470''>things.</span> <span m=''2181070''>How</span> <span m=''2181310''>do</span>
  <span m=''2181370''>you</span> <span m=''2181480''>minimize</span> <span m=''2182010''>those</span>
  <span m=''2182250''>disk</span> <span m=''2182510''>accesses?</span> <span m=''2183530''>And</span>
  <span m=''2183630''>all</span> <span m=''2183870''>the</span> <span m=''2184500''>things
  that</span> <span m=''2184770''>we''re</span> <span m=''2184950''>learning</span>
  <span m=''2185320''>about,</span> <span m=''2186050''>performance</span> <span m=''2186640''>for</span>
  <span m=''2186760''>CPUs,</span> <span m=''2187590''>can</span> <span m=''2187770''>be</span>
  <span m=''2187960''>applied</span> <span m=''2188490''>to</span> <span m=''2188950''>disk</span>
  <span m=''2190530''>accesses,</span> <span m=''2191150''>as</span> <span m=''2191270''>well.</span>
  </p><p><span m=''2194040''>So</span> <span m=''2194770''>the</span> <span m=''2194870''>idea</span>
  <span m=''2195190''>here</span> <span m=''2195560''>is</span> <span m=''2196180''>we</span>
  <span m=''2196350''>want</span> <span m=''2196560''>to</span> <span m=''2196620''>avoid--</span>
  <span m=''2197280''>that''s</span> <span m=''2197520''>why</span> <span m=''2197760''>we</span>
  <span m=''2197910''>don''t</span> <span m=''2198190''>want</span> <span m=''2198330''>to</span>
  <span m=''2198680''>have</span> <span m=''2199050''>our</span> <span m=''2199190''>stuff</span>
  <span m=''2199420''>strewn</span> <span m=''2199830''>across</span> <span m=''2200220''>a</span>
  <span m=''2200280''>whole</span> <span m=''2200490''>bunch</span> <span m=''2200720''>of</span>
  <span m=''2200800''>pages</span> <span m=''2201770''>where</span> <span m=''2202010''>we</span>
  <span m=''2202130''>only</span> <span m=''2202320''>have</span> <span m=''2202410''>a</span>
  <span m=''2202470''>fixed</span> <span m=''2202810''>amount</span> <span m=''2203415''>of</span>
  <span m=''2203670''>internal</span> <span m=''2204020''>memory,</span> <span m=''2204340''>because</span>
  <span m=''2204550''>then we''ll</span> <span m=''2204670''>end up</span> <span m=''2204980''>paging</span>
  <span m=''2205470''>all</span> <span m=''2205620''>the</span> <span m=''2205710''>time.</span>
  <span m=''2206640''>Every</span> <span m=''2206940''>access</span> <span m=''2207390''>will</span>
  <span m=''2207530''>cause</span> <span m=''2207840''>us</span> <span m=''2207940''>to</span>
  <span m=''2208040''>do</span> <span m=''2208160''>a</span> <span m=''2208220''>disk</span>
  <span m=''2208530''>access,</span> <span m=''2209560''>because</span> <span m=''2210350''>it</span>
  <span m=''2210500''>won''t</span> <span m=''2210640''>be</span> <span m=''2210790''>very</span>
  <span m=''2210990''>likely</span> <span m=''2211430''>that</span> <span m=''2211530''>we''re
  getting</span> <span m=''2211820''>stuff</span> <span m=''2212160''>on</span> <span
  m=''2212230''>the</span> <span m=''2212300''>same</span> <span m=''2212600''>page.</span>
  <span m=''2213400''>So</span> <span m=''2213570''>getting</span> <span m=''2213830''>back,</span>
  <span m=''2214070''>for</span> <span m=''2214150''>example, to</span> <span m=''2214560''>the</span>
  <span m=''2214680''>fixed</span> <span m=''2215060''>allocation,</span> <span m=''2215630''>that''s</span>
  <span m=''2215820''>why</span> <span m=''2215980''>it''s</span> <span m=''2216100''>a</span>
  <span m=''2216130''>good</span> <span m=''2216400''>idea</span> <span m=''2217050''>to</span>
  <span m=''2217170''>try</span> <span m=''2217420''>to</span> <span m=''2217510''>keep</span>
  <span m=''2217770''>those</span> <span m=''2218010''>pages</span> <span m=''2218400''>full,</span>
  <span m=''2220040''>so that</span> <span m=''2220430''>we</span> <span m=''2220620''>have</span>
  <span m=''2220830''>a</span> <span m=''2220870''>small</span> <span m=''2221220''>thing.</span>
  </p><p><span m=''2221790''>So</span> <span m=''2222520''>the</span> <span m=''2223000''>goal</span>
  <span m=''2223360''>of</span> <span m=''2223440''>most</span> <span m=''2223730''>storage</span>
  <span m=''2224190''>allocators</span> <span m=''2225250''>is</span> <span m=''2225460''>therefore</span>
  <span m=''2225920''>to</span> <span m=''2226040''>use</span> <span m=''2226480''>as</span>
  <span m=''2226660''>little</span> <span m=''2227170''>virtual</span> <span m=''2227690''>memory</span>
  <span m=''2228110''>as</span> <span m=''2228270''>possible,</span> <span m=''2230870''>and</span>
  <span m=''2231010''>try</span> <span m=''2231260''>to</span> <span m=''2231360''>keep</span>
  <span m=''2231620''>the</span> <span m=''2231710''>used</span> <span m=''2232090''>portions</span>
  <span m=''2232730''>very</span> <span m=''2233060''>compact.</span> <span m=''2234130''>Because</span>
  <span m=''2234860''>the</span> <span m=''2234930''>more</span> <span m=''2235150''>compact</span>
  <span m=''2235710''>it</span> <span m=''2235790''>is,</span> <span m=''2236330''>the</span>
  <span m=''2236460''>more</span> <span m=''2236690''>likely</span> <span m=''2237200''>it</span>
  <span m=''2237290''>is</span> <span m=''2237900''>that</span> <span m=''2238030''>when</span>
  <span m=''2238150''>you</span> <span m=''2238230''>access</span> <span m=''2238800''>one,</span>
  <span m=''2239150''>you''ll</span> <span m=''2239280''>be</span> <span m=''2239490''>able</span>
  <span m=''2239620''>to</span> <span m=''2239720''>access</span> <span m=''2240710''>something</span>
  <span m=''2241180''>nearby</span> <span m=''2241680''>without</span> <span m=''2242020''>causing</span>
  <span m=''2242580''>a</span> <span m=''2242820''>page</span> <span m=''2243170''>fault.</span>
  <span m=''2245360''>So</span> <span m=''2245510''>that''s</span> <span m=''2245830''>the</span>
  <span m=''2245920''>goal</span> <span m=''2246220''>of</span> <span m=''2246340''>almost</span>
  <span m=''2246640''>all</span> <span m=''2246850''>storage</span> <span m=''2247220''>allocators.</span>
  <span m=''2247940''>Try</span> <span m=''2248230''>to</span> <span m=''2248300''>keep</span>
  <span m=''2248540''>things</span> <span m=''2248830''>compact,</span> <span m=''2249430''>try</span>
  <span m=''2249640''>to</span> <span m=''2249720''>keep</span> <span m=''2249950''>things</span>
  <span m=''2251070''>tight</span> <span m=''2251420''>and in</span> <span m=''2251740''>very</span>
  <span m=''2252040''>little</span> <span m=''2253090''>virtual</span> <span m=''2253420''>memory</span>
  <span m=''2253740''>space,</span> <span m=''2254270''>even</span> <span m=''2254570''>though</span>
  <span m=''2254740''>virtual</span> <span m=''2255050''>memory</span> <span m=''2255330''>is</span>
  <span m=''2255450''>huge.</span> </p><p><span m=''2256640''>Now,</span> <span m=''2256740''>that</span>
  <span m=''2256910''>doesn''t</span> <span m=''2257220''>mean</span> <span m=''2257900''>that</span>
  <span m=''2258030''>everything</span> <span m=''2258370''>has</span> <span m=''2258610''>to</span>
  <span m=''2258690''>be</span> <span m=''2258790''>contiguous.</span> <span m=''2259430''>For</span>
  <span m=''2259520''>example,</span> <span m=''2260020''>in</span> <span m=''2260850''>this</span>
  <span m=''2261400''>organization</span> <span m=''2262180''>as</span> <span m=''2262330''>I</span>
  <span m=''2262380''>showed</span> <span m=''2262650''>before,</span> <span m=''2263090''>actually,</span>
  <span m=''2263300''>I have</span> <span m=''2263410''>it</span> <span m=''2263520''>just</span>
  <span m=''2263760''>on</span> <span m=''2263830''>the</span> <span m=''2263900''>previous</span>
  <span m=''2264270''>slide,</span> <span m=''2264640''>so</span> <span m=''2264730''>why
  don''t</span> <span m=''2264910''>I</span> <span m=''2264980''>go</span> <span m=''2265110''>back</span>
  <span m=''2265390''>there--</span> <span m=''2267360''>these</span> <span m=''2267760''>are</span>
  <span m=''2267900''>very</span> <span m=''2268300''>far</span> <span m=''2268640''>away</span>
  <span m=''2269340''>in</span> <span m=''2269550''>memory,</span> <span m=''2269980''>but</span>
  <span m=''2270110''>there''s</span> <span m=''2270260''>only</span> <span m=''2270580''>a</span>
  <span m=''2270660''>couple</span> <span m=''2271050''>of</span> <span m=''2271170''>them,</span>
  <span m=''2273290''>and</span> <span m=''2273510''>they''re</span> <span m=''2274300''>tight</span>
  <span m=''2274630''>and</span> <span m=''2274750''>local</span> <span m=''2275240''>in</span>
  <span m=''2275410''>the</span> <span m=''2275500''>regions</span> <span m=''2275970''>that</span>
  <span m=''2276140''>they''re</span> <span m=''2276360''>operating</span> <span m=''2276950''>in.</span>
  <span m=''2277650''>What</span> <span m=''2277900''>I</span> <span m=''2277970''>don''t</span>
  <span m=''2278230''>want</span> <span m=''2278360''>to</span> <span m=''2278450''>do</span>
  <span m=''2278710''>is</span> <span m=''2278830''>have</span> <span m=''2279190''>it</span>
  <span m=''2279520''>where</span> <span m=''2279780''>I have</span> <span m=''2279950''>just</span>
  <span m=''2280160''>little</span> <span m=''2280500''>stuff.</span> <span m=''2281560''>It''s</span>
  <span m=''2281690''>OK</span> <span m=''2282010''>to</span> <span m=''2282210''>go</span>
  <span m=''2282420''>into</span> <span m=''2283610''>the</span> <span m=''2283690''>middle</span>
  <span m=''2284040''>of</span> <span m=''2284130''>virtual</span> <span m=''2284480''>memory</span>
  <span m=''2285120''>and</span> <span m=''2285260''>have</span> <span m=''2285420''>a</span>
  <span m=''2285460''>whole</span> <span m=''2285680''>bunch</span> <span m=''2285950''>of</span>
  <span m=''2286060''>consecutive</span> <span m=''2286700''>pages</span> <span m=''2287140''>full
  of</span> <span m=''2287410''>data.</span> <span m=''2287760''>That''s</span> <span
  m=''2288070''>fine.</span> <span m=''2289360''>What''s</span> <span m=''2289620''>bad</span>
  <span m=''2290360''>is</span> <span m=''2290500''>having</span> <span m=''2290740''>just</span>
  <span m=''2290910''>a</span> <span m=''2290950''>little</span> <span m=''2291190''>bit</span>
  <span m=''2291330''>of</span> <span m=''2291400''>data,</span> <span m=''2291780''>a</span>
  <span m=''2291840''>little</span> <span m=''2292060''>bit</span> <span m=''2292180''>of</span>
  <span m=''2292270''>data,</span> <span m=''2292620''>and</span> <span m=''2292780''>a</span>
  <span m=''2292830''>little</span> <span m=''2293010''>bit</span> <span m=''2293150''>of</span>
  <span m=''2293210''>data</span> <span m=''2293540''>sort of</span> <span m=''2294120''>sprinkled</span>
  <span m=''2294690''>all</span> <span m=''2294940''>over.</span> <span m=''2295290''>That''s</span>
  <span m=''2295580''>bad.</span> <span m=''2296680''>But</span> <span m=''2296910''>as</span>
  <span m=''2297030''>long</span> <span m=''2297260''>as</span> <span m=''2297370''>I</span>
  <span m=''2297450''>can</span> <span m=''2297640''>put</span> <span m=''2297880''>a</span>
  <span m=''2297940''>whole</span> <span m=''2298100''>bunch</span> <span m=''2298310''>of</span>
  <span m=''2298390''>data</span> <span m=''2298970''>nearby,</span> <span m=''2299800''>it</span>
  <span m=''2299930''>doesn''t</span> <span m=''2300200''>matter</span> <span m=''2300480''>where</span>
  <span m=''2300740''>in</span> <span m=''2300830''>virtual</span> <span m=''2301180''>memory</span>
  <span m=''2301920''>I</span> <span m=''2302560''>put</span> <span m=''2302730''>it,</span>
  <span m=''2302950''>particularly.</span> <span m=''2306100''>So</span> <span m=''2306270''>the</span>
  <span m=''2306410''>idea</span> <span m=''2306750''>is,</span> <span m=''2306850''>let''s</span>
  <span m=''2307040''>try</span> <span m=''2307220''>to</span> <span m=''2307985''>use
  as</span> <span m=''2308260''>little</span> <span m=''2308490''>virtual</span> <span
  m=''2308830''>memory</span> <span m=''2309090''>as</span> <span m=''2309190''>possible.</span>
  <span m=''2309980''>Any</span> <span m=''2310140''>questions</span> <span m=''2310610''>about</span>
  <span m=''2310890''>that?</span> <span m=''2316180''>OK.</span> </p><p><span m=''2317227''>So
  how do</span> <span m=''2317704''>we do that?</span> <span m=''2318660''>So</span>
  <span m=''2320320''>the</span> <span m=''2320550''>first</span> <span m=''2320900''>thing</span>
  <span m=''2321230''>is,</span> <span m=''2321780''>binned</span> <span m=''2321930''>free</span>
  <span m=''2322180''>list</span> <span m=''2322520''>turns</span> <span m=''2322800''>out</span>
  <span m=''2322990''>to</span> <span m=''2323070''>do</span> <span m=''2323210''>a</span>
  <span m=''2323270''>really</span> <span m=''2323550''>good</span> <span m=''2324990''>job</span>
  <span m=''2325530''>of</span> <span m=''2325750''>using</span> <span m=''2326150''>relatively</span>
  <span m=''2326690''>little</span> <span m=''2326980''>memory.</span> <span m=''2329170''>So</span>
  <span m=''2329820''>suppose</span> <span m=''2330440''>that</span> <span m=''2330980''>the</span>
  <span m=''2331090''>user</span> <span m=''2331600''>program</span> <span m=''2333830''>is</span>
  <span m=''2334120''>using,</span> <span m=''2334590''>at</span> <span m=''2334720''>most,</span>
  <span m=''2335550''>m</span> <span m=''2335930''>memory</span> <span m=''2336370''>at</span>
  <span m=''2336510''>any</span> <span m=''2336790''>point</span> <span m=''2337140''>during</span>
  <span m=''2337360''>the</span> <span m=''2337440''>execution.</span> <span m=''2338020''>Maybe</span>
  <span m=''2338340''>allocating,</span> <span m=''2338940''>maybe</span> <span m=''2339240''>freeing.</span>
  <span m=''2339770''>But</span> <span m=''2340110''>if</span> <span m=''2340190''>I</span>
  <span m=''2340260''>took</span> <span m=''2340500''>the</span> <span m=''2340590''>high</span>
  <span m=''2340940''>watermark</span> <span m=''2341610''>of</span> <span m=''2341710''>everything</span>
  <span m=''2342140''>he</span> <span m=''2342330''>says</span> <span m=''2342660''>that</span>
  <span m=''2342760''>he</span> <span m=''2342860''>needs,</span> <span m=''2344280''>we</span>
  <span m=''2344410''>call</span> <span m=''2344670''>that</span> <span m=''2344900''>m.</span>
  </p><p><span m=''2346810''>Then</span> <span m=''2346950''>it</span> <span m=''2347050''>turns</span>
  <span m=''2347390''>out</span> <span m=''2347830''>that</span> <span m=''2349010''>if</span>
  <span m=''2349180''>you</span> <span m=''2349300''>use</span> <span m=''2349630''>a</span>
  <span m=''2349680''>bin</span> <span m=''2349970''>free</span> <span m=''2350190''>list</span>
  <span m=''2350430''>allocator,</span> <span m=''2351440''>the</span> <span m=''2351530''>amount</span>
  <span m=''2351830''>of</span> <span m=''2351920''>virtual</span> <span m=''2352280''>memory</span>
  <span m=''2352650''>consumed</span> <span m=''2353930''>is</span> <span m=''2354190''>at</span>
  <span m=''2354330''>most</span> <span m=''2355110''>m</span> <span m=''2355440''>times</span>
  <span m=''2355830''>log</span> <span m=''2356160''>n.</span> <span m=''2357480''>Order</span>
  <span m=''2357750''>m</span> <span m=''2357940''>times</span> <span m=''2358260''>log</span>
  <span m=''2358550''>n.</span> <span m=''2360170''>And</span> <span m=''2360290''>why</span>
  <span m=''2360620''>is</span> <span m=''2360850''>that?</span> <span m=''2361160''>Here''s</span>
  <span m=''2361360''>kind</span> <span m=''2361500''>of</span> <span m=''2361650''>a</span>
  <span m=''2361860''>hand-wavy</span> <span m=''2362490''>proof</span> <span m=''2362720''>sketch.</span>
  <span m=''2364000''>So</span> <span m=''2364220''>whenever</span> <span m=''2364610''>I</span>
  <span m=''2365530''>make</span> <span m=''2365780''>a</span> <span m=''2365820''>request</span>
  <span m=''2366410''>for</span> <span m=''2366520''>a</span> <span m=''2366550''>block</span>
  <span m=''2366870''>of</span> <span m=''2366960''>size</span> <span m=''2367330''>x,</span>
  <span m=''2367720''>it</span> <span m=''2367900''>may</span> <span m=''2368370''>consume</span>
  <span m=''2369560''>at</span> <span m=''2369740''>most</span> <span m=''2370100''>twice</span>
  <span m=''2370550''>x</span> <span m=''2370810''>storage</span> <span m=''2372970''>that''s</span>
  <span m=''2373120''>actually in</span> <span m=''2373520''>use.</span> </p><p><span
  m=''2374710''>And</span> <span m=''2374870''>so</span> <span m=''2376080''>it</span>
  <span m=''2376300''>turns</span> <span m=''2376550''>out</span> <span m=''2376730''>that</span>
  <span m=''2376890''>the</span> <span m=''2377070''>total</span> <span m=''2377470''>amount</span>
  <span m=''2377750''>of</span> <span m=''2377850''>memory</span> <span m=''2378310''>devoted</span>
  <span m=''2378840''>to</span> <span m=''2378920''>blocks</span> <span m=''2379410''>of</span>
  <span m=''2379510''>size</span> <span m=''2379880''>2</span> <span m=''2380060''>to</span>
  <span m=''2380140''>the</span> <span m=''2380240''>k</span> <span m=''2380670''>is</span>
  <span m=''2380830''>therefore at</span> <span m=''2381280''>most</span> <span m=''2381690''>2m.</span>
  <span m=''2383540''>So</span> <span m=''2383800''>for</span> <span m=''2383980''>any</span>
  <span m=''2384260''>given</span> <span m=''2384640''>size,</span> <span m=''2387170''>I</span>
  <span m=''2387250''>might,</span> <span m=''2387530''>at</span> <span m=''2387610''>any</span>
  <span m=''2387810''>given</span> <span m=''2388080''>point</span> <span m=''2388340''>in</span>
  <span m=''2388430''>time,</span> <span m=''2389220''>have</span> <span m=''2389450''>the</span>
  <span m=''2389540''>program</span> <span m=''2390040''>using</span> <span m=''2391030''>all</span>
  <span m=''2391350''>blocks</span> <span m=''2391840''>of</span> <span m=''2391930''>that</span>
  <span m=''2392220''>given</span> <span m=''2392530''>size.</span> <span m=''2393140''>Let''s</span>
  <span m=''2393380''>say</span> <span m=''2395020''>size</span> <span m=''2395350''>2</span>
  <span m=''2395510''>to</span> <span m=''2395580''>the</span> <span m=''2395680''>k.</span>
  <span m=''2397200''>And</span> <span m=''2397690''>since there are</span> <span
  m=''2398110''>a</span> <span m=''2398170''>logarithmic</span> <span m=''2398900''>number</span>
  <span m=''2399280''>of</span> <span m=''2400200''>those</span> <span m=''2401350''>bins,</span>
  <span m=''2405430''>each</span> <span m=''2406990''>bin</span> <span m=''2407230''>of</span>
  <span m=''2407330''>which</span> <span m=''2407570''>could</span> <span m=''2407690''>have</span>
  <span m=''2407880''>a</span> <span m=''2408070''>size</span> <span m=''2408450''>at</span>
  <span m=''2408550''>most</span> <span m=''2408880''>m,</span> <span m=''2409580''>the</span>
  <span m=''2409690''>total</span> <span m=''2410050''>is</span> <span m=''2410160''>order</span>
  <span m=''2410440''>m</span> <span m=''2410660''>log</span> <span m=''2410990''>m.</span>
  </p><p><span m=''2413980''>Now</span> <span m=''2414070''>it</span> <span m=''2414140''>turns</span>
  <span m=''2414440''>out</span> <span m=''2414660''>that</span> <span m=''2414770''>there''s</span>
  <span m=''2414950''>actually</span> <span m=''2415320''>a</span> <span m=''2415370''>stronger</span>
  <span m=''2415980''>property.</span> <span m=''2416990''>In</span> <span m=''2417130''>fact,</span>
  <span m=''2418510''>you</span> <span m=''2418670''>can</span> <span m=''2418820''>show</span>
  <span m=''2419250''>that</span> <span m=''2419960''>binned free</span> <span m=''2420330''>list</span>
  <span m=''2420690''>is</span> <span m=''2420920''>order</span> <span m=''2421250''>one</span>
  <span m=''2421550''>competitive.</span> <span m=''2422230''>Who</span> <span m=''2422380''>knows</span>
  <span m=''2422620''>the</span> <span m=''2422730''>term</span> <span m=''2423050''>&quot;competitive&quot;</span>
  <span m=''2423610''>in</span> <span m=''2423710''>this</span> <span m=''2423790''>sense?</span>
  <span m=''2424620''>The</span> <span m=''2425300''>algorithmic</span> <span m=''2425860''>meaning</span>
  <span m=''2426180''>of</span> <span m=''2426400''>&quot;competitive&quot;?</span>
  <span m=''2427530''>So</span> <span m=''2427670''>what</span> <span m=''2427790''>it</span>
  <span m=''2427890''>means</span> <span m=''2428270''>is,</span> <span m=''2429650''>it''s</span>
  <span m=''2429870''>at</span> <span m=''2430010''>most</span> <span m=''2430310''>a</span>
  <span m=''2430360''>constant</span> <span m=''2430880''>factor</span> <span m=''2431310''>slower</span>
  <span m=''2432180''>than</span> <span m=''2432330''>the</span> <span m=''2432550''>optimal</span>
  <span m=''2433250''>omniscient</span> <span m=''2434380''>algorithm</span> <span
  m=''2435190''>that</span> <span m=''2435340''>could</span> <span m=''2435500''>figure</span>
  <span m=''2435850''>out</span> <span m=''2436010''>exactly</span> <span m=''2436580''>what''s</span>
  <span m=''2436860''>going</span> <span m=''2437140''>on</span> <span m=''2437360''>in</span>
  <span m=''2437460''>every</span> <span m=''2437690''>step.</span> <span m=''2439420''>So</span>
  <span m=''2439570''>you''re</span> <span m=''2439720''>within</span> <span m=''2440120''>a</span>
  <span m=''2440180''>constant</span> <span m=''2440790''>factor</span> <span m=''2441650''>competitive</span>
  <span m=''2442050''>with</span> <span m=''2442190''>the</span> <span m=''2442280''>optimal</span>
  <span m=''2442850''>allocator,</span> <span m=''2443720''>assuming</span> <span
  m=''2444690''>that</span> <span m=''2444880''>the</span> <span m=''2445010''>optimal</span>
  <span m=''2445460''>allocator</span> <span m=''2445970''>does</span> <span m=''2446180''>not</span>
  <span m=''2446520''>do</span> <span m=''2446670''>what''s</span> <span m=''2446920''>called</span>
  <span m=''2447290''>coalescing.</span> <span m=''2449470''>If it</span> <span m=''2449700''>simply</span>
  <span m=''2450060''>is</span> <span m=''2450200''>dividing</span> <span m=''2450740''>up</span>
  <span m=''2450970''>things,</span> <span m=''2451310''>then it</span> <span m=''2451380''>can</span>
  <span m=''2451790''>subdivide,</span> <span m=''2452170''>but</span> <span m=''2452550''>it</span>
  <span m=''2452680''>can</span> <span m=''2452840''>never</span> <span m=''2453110''>glue</span>
  <span m=''2453410''>things</span> <span m=''2453750''>back</span> <span m=''2454020''>together</span>
  <span m=''2454410''>again.</span> <span m=''2455390''>It</span> <span m=''2455560''>turns</span>
  <span m=''2455830''>out</span> <span m=''2456070''>that</span> <span m=''2456610''>in</span>
  <span m=''2456820''>fact,</span> <span m=''2457190''>binned</span> <span m=''2457320''>free</span>
  <span m=''2457470''>list</span> <span m=''2457750''>is</span> <span m=''2457880''>really</span>
  <span m=''2458150''>much</span> <span m=''2458390''>better</span> <span m=''2458650''>than</span>
  <span m=''2458800''>that.</span> </p><p><span m=''2461430''>So</span> <span m=''2461690''>let''s</span>
  <span m=''2461920''>talk</span> <span m=''2462180''>a</span> <span m=''2462250''>bit</span>
  <span m=''2462490''>about</span> <span m=''2462850''>coalescing,</span> <span m=''2463480''>because</span>
  <span m=''2464230''>many,</span> <span m=''2464580''>many</span> <span m=''2464830''>memory</span>
  <span m=''2465000''>allocators</span> <span m=''2465770''>use</span> <span m=''2466050''>coalescing.</span>
  <span m=''2469220''>So</span> <span m=''2469450''>the</span> <span m=''2469580''>idea</span>
  <span m=''2469990''>is,</span> <span m=''2472140''>I''m</span> <span m=''2472300''>concerned</span>
  <span m=''2472740''>about</span> <span m=''2473010''>the</span> <span m=''2473110''>case</span>
  <span m=''2473560''>where</span> <span m=''2473780''>I</span> <span m=''2473860''>end</span>
  <span m=''2474100''>up</span> <span m=''2474250''>with</span> <span m=''2474390''>a</span>
  <span m=''2474430''>whole</span> <span m=''2474710''>bunch</span> <span m=''2474960''>of</span>
  <span m=''2475060''>little</span> <span m=''2475330''>small</span> <span m=''2475790''>objects,</span>
  <span m=''2477790''>and</span> <span m=''2477960''>yet</span> <span m=''2478240''>the</span>
  <span m=''2478380''>allocations</span> <span m=''2479070''>now</span> <span m=''2479330''>come</span>
  <span m=''2479500''>from</span> <span m=''2479640''>big</span> <span m=''2479920''>chunks.</span>
  <span m=''2481110''>And</span> <span m=''2481230''>so</span> <span m=''2481300''>I</span>
  <span m=''2481400''>have</span> <span m=''2481510''>to</span> <span m=''2481600''>go</span>
  <span m=''2481890''>and</span> <span m=''2482030''>use</span> <span m=''2482860''>more</span>
  <span m=''2483120''>of</span> <span m=''2483200''>my</span> <span m=''2483370''>virtual</span>
  <span m=''2483770''>memory,</span> <span m=''2484610''>or</span> <span m=''2485340''>maybe</span>
  <span m=''2485600''>I</span> <span m=''2485670''>can</span> <span m=''2485870''>glue</span>
  <span m=''2486130''>together</span> <span m=''2486510''>those</span> <span m=''2486750''>little</span>
  <span m=''2486990''>pieces</span> <span m=''2487470''>into</span> <span m=''2487690''>a</span>
  <span m=''2487740''>big</span> <span m=''2487970''>chunk,</span> <span m=''2488360''>and</span>
  <span m=''2488470''>not</span> <span m=''2488650''>have</span> <span m=''2488840''>to</span>
  <span m=''2488920''>go</span> <span m=''2489120''>off</span> <span m=''2489310''>to</span>
  <span m=''2489450''>memory.</span> <span m=''2490100''>So</span> <span m=''2490240''>that''s</span>
  <span m=''2490430''>what</span> <span m=''2490590''>coalescing</span> <span m=''2491220''>is</span>
  <span m=''2491340''>all</span> <span m=''2491500''>about.</span> </p><p><span m=''2492670''>So</span>
  <span m=''2493410''>the</span> <span m=''2493870''>idea</span> <span m=''2494160''>is,</span>
  <span m=''2494300''>if</span> <span m=''2494450''>two</span> <span m=''2494650''>things</span>
  <span m=''2494930''>are</span> <span m=''2495060''>adjacent,</span> <span m=''2495490''>let</span>
  <span m=''2495610''>me</span> <span m=''2495740''>glue them</span> <span m=''2496050''>together.</span>
  <span m=''2497490''>And</span> <span m=''2497650''>there are</span> <span m=''2497840''>really</span>
  <span m=''2498100''>clever</span> <span m=''2498500''>systems</span> <span m=''2498960''>for</span>
  <span m=''2499080''>doing</span> <span m=''2499380''>that,</span> <span m=''2500060''>including</span>
  <span m=''2500790''>a</span> <span m=''2500920''>very</span> <span m=''2501170''>famous</span>
  <span m=''2501560''>one</span> <span m=''2501740''>called</span> <span m=''2501990''>the</span>
  <span m=''2502050''>buddy</span> <span m=''2502350''>system.</span> <span m=''2504450''>But</span>
  <span m=''2505070''>using</span> <span m=''2505500''>any</span> <span m=''2505790''>of</span>
  <span m=''2505850''>these</span> <span m=''2506070''>mechanisms</span> <span m=''2506700''>for</span>
  <span m=''2506840''>coalescing,</span> <span m=''2507650''>you</span> <span m=''2507820''>always</span>
  <span m=''2508010''>have</span> <span m=''2508190''>to</span> <span m=''2508290''>trade</span>
  <span m=''2508640''>off</span> <span m=''2508960''>between</span> <span m=''2509290''>the</span>
  <span m=''2509360''>simplicity</span> <span m=''2510360''>of</span> <span m=''2510470''>not</span>
  <span m=''2510730''>coalescing.</span> <span m=''2512690''>Not</span> <span m=''2512960''>coalescing</span>
  <span m=''2513500''>so</span> <span m=''2513570''>stick it</span> <span m=''2513970''>in</span>
  <span m=''2514100''>the</span> <span m=''2514190''>free</span> <span m=''2514370''>list,</span>
  <span m=''2514620''>I''m</span> <span m=''2514730''>done.</span> <span m=''2515710''>Coalescing</span>
  <span m=''2516290''>is,</span> <span m=''2516420''>stick it</span> <span m=''2516620''>in</span>
  <span m=''2516710''>the</span> <span m=''2516800''>free</span> <span m=''2516980''>list,</span>
  <span m=''2517250''>oh,</span> <span m=''2517490''>am I</span> <span m=''2517630''>next</span>
  <span m=''2517890''>to</span> <span m=''2517950''>somebody</span> <span m=''2518380''>I</span>
  <span m=''2518470''>can merge</span> <span m=''2518900''>with?</span> <span m=''2520130''>Now</span>
  <span m=''2520290''>let</span> <span m=''2520410''>me</span> <span m=''2520530''>merge.</span>
  <span m=''2521400''>So</span> <span m=''2521620''>you</span> <span m=''2521770''>always</span>
  <span m=''2521940''>have</span> <span m=''2522130''>to</span> <span m=''2522750''>weigh,</span>
  <span m=''2524520''>is</span> <span m=''2524670''>that</span> <span m=''2524880''>really</span>
  <span m=''2525120''>going</span> <span m=''2525200''>to</span> <span m=''2525290''>be
  an</span> <span m=''2525460''>advantageous</span> <span m=''2526230''>thing?</span>
  </p><p><span m=''2527290''>It</span> <span m=''2527450''>turns</span> <span m=''2527740''>out</span>
  <span m=''2527960''>there</span> <span m=''2528200''>are</span> <span m=''2528240''>no</span>
  <span m=''2528580''>good</span> <span m=''2529440''>theoretical</span> <span m=''2529970''>bounds</span>
  <span m=''2530340''>that</span> <span m=''2530410''>I''m</span> <span m=''2530730''>aware</span>
  <span m=''2531530''>that</span> <span m=''2531660''>prove</span> <span m=''2532040''>the</span>
  <span m=''2532150''>effectiveness</span> <span m=''2532830''>of</span> <span m=''2532920''>coalescing.</span>
  <span m=''2535060''>People</span> <span m=''2535440''>have</span> <span m=''2535570''>not</span>
  <span m=''2535890''>figured</span> <span m=''2536230''>out</span> <span m=''2536390''>how</span>
  <span m=''2536560''>to</span> <span m=''2536720''>analyze</span> <span m=''2537300''>this,</span>
  <span m=''2537480''>or</span> <span m=''2537550''>what</span> <span m=''2537740''>an</span>
  <span m=''2537850''>appropriate</span> <span m=''2538390''>model</span> <span m=''2538850''>is</span>
  <span m=''2539330''>for</span> <span m=''2539440''>understanding</span> <span m=''2540180''>whether</span>
  <span m=''2540620''>coalescing</span> <span m=''2541200''>is</span> <span m=''2541330''>a</span>
  <span m=''2541380''>good</span> <span m=''2541640''>idea.</span> <span m=''2542940''>However,</span>
  <span m=''2543340''>it</span> <span m=''2543470''>does</span> <span m=''2543700''>seem</span>
  <span m=''2543920''>to</span> <span m=''2544010''>work</span> <span m=''2544260''>in</span>
  <span m=''2544370''>practice</span> <span m=''2544900''>for</span> <span m=''2545020''>some</span>
  <span m=''2545270''>things,</span> <span m=''2546090''>and</span> <span m=''2546610''>I</span>
  <span m=''2546790''>think</span> <span m=''2547110''>the</span> <span m=''2547210''>reason</span>
  <span m=''2547620''>for</span> <span m=''2547760''>that--</span> <span m=''2548100''>and</span>
  <span m=''2548210''>this</span> <span m=''2548340''>is</span> <span m=''2548470''>just</span>
  <span m=''2548710''>my</span> <span m=''2548890''>own</span> <span m=''2549510''>take</span>
  <span m=''2549980''>on</span> <span m=''2550130''>it--</span> <span m=''2550680''>is</span>
  <span m=''2551280''>that</span> <span m=''2551500''>storage</span> <span m=''2551900''>tends</span>
  <span m=''2552160''>to</span> <span m=''2552260''>be</span> <span m=''2552420''>deallocated</span>
  <span m=''2553280''>as</span> <span m=''2553440''>a</span> <span m=''2553490''>stack.</span>
  <span m=''2554090''>So</span> <span m=''2555220''>you</span> <span m=''2555370''>tend</span>
  <span m=''2555660''>to</span> <span m=''2556030''>go</span> <span m=''2556220''>into</span>
  <span m=''2556420''>a</span> <span m=''2556440''>region of a</span> <span m=''2556860''>program</span>
  <span m=''2557210''>where you</span> <span m=''2557370''>do</span> <span m=''2557480''>a</span>
  <span m=''2557520''>lot</span> <span m=''2557750''>of</span> <span m=''2557800''>heap</span>
  <span m=''2558060''>allocation--</span> <span m=''2559200''>let''s</span> <span
  m=''2559340''>say</span> <span m=''2559460''>I''m</span> <span m=''2559550''>building</span>
  <span m=''2559880''>up</span> <span m=''2559980''>a</span> <span m=''2560050''>graph,</span>
  <span m=''2561070''>and</span> <span m=''2561180''>I</span> <span m=''2561230''>keep</span>
  <span m=''2561440''>doing</span> <span m=''2561610''>a</span> <span m=''2561690''>whole</span>
  <span m=''2561850''>bunch</span> <span m=''2562060''>of</span> <span m=''2562110''>mallocs.</span>
  <span m=''2562570''>And</span> <span m=''2562670''>when</span> <span m=''2562810''>I''m</span>
  <span m=''2562910''>done</span> <span m=''2563120''>with</span> <span m=''2563220''>the</span>
  <span m=''2563300''>graph,</span> <span m=''2563680''>what do</span> <span m=''2563880''>I</span>
  <span m=''2563950''>do?</span> <span m=''2564840''>I</span> <span m=''2564930''>free</span>
  <span m=''2565210''>it</span> <span m=''2565310''>all.</span> <span m=''2567320''>So</span>
  <span m=''2567520''>I</span> <span m=''2567610''>tend</span> <span m=''2568090''>to</span>
  <span m=''2568380''>have</span> <span m=''2568720''>these</span> <span m=''2569080''>batch</span>
  <span m=''2570930''>allocations</span> <span m=''2571920''>and</span> <span m=''2572080''>then</span>
  <span m=''2572250''>deallocations,</span> <span m=''2574310''>and</span> <span m=''2576120''>they</span>
  <span m=''2576310''>tend</span> <span m=''2576520''>to</span> <span m=''2576590''>work</span>
  <span m=''2577140''>often</span> <span m=''2577500''>as</span> <span m=''2577620''>a</span>
  <span m=''2577680''>stack,</span> <span m=''2578130''>often</span> <span m=''2578530''>in</span>
  <span m=''2578610''>a</span> <span m=''2578680''>batch.</span> <span m=''2579120''>And</span>
  <span m=''2579220''>that</span> <span m=''2579470''>means</span> <span m=''2579870''>that</span>
  <span m=''2580020''>when</span> <span m=''2580210''>I</span> <span m=''2580290''>do</span>
  <span m=''2580470''>that</span> <span m=''2580780''>freeing,</span> <span m=''2581520''>I</span>
  <span m=''2581610''>can</span> <span m=''2581780''>sometimes</span> <span m=''2582280''>take</span>
  <span m=''2582510''>advantage</span> <span m=''2582980''>of</span> <span m=''2583050''>that</span>
  <span m=''2583410''>and</span> <span m=''2583810''>do</span> <span m=''2583980''>coalescing.</span>
  </p><p><span m=''2585550''>In</span> <span m=''2586850''>some</span> <span m=''2589220''>systems,</span>
  <span m=''2590940''>people</span> <span m=''2592060''>have</span> <span m=''2592410''>what</span>
  <span m=''2592520''>are</span> <span m=''2592620''>called</span> <span m=''2592920''>memory</span>
  <span m=''2593330''>pools,</span> <span m=''2594130''>where</span> <span m=''2594440''>you</span>
  <span m=''2594630''>have</span> <span m=''2594820''>a</span> <span m=''2594910''>region</span>
  <span m=''2595950''>where</span> <span m=''2596140''>when</span> <span m=''2596290''>you</span>
  <span m=''2596380''>allocate</span> <span m=''2596990''>out</span> <span m=''2597190''>of</span>
  <span m=''2597270''>it,</span> <span m=''2597440''>you know</span> <span m=''2597790''>you''re</span>
  <span m=''2597970''>allocating</span> <span m=''2598540''>out</span> <span m=''2598670''>of</span>
  <span m=''2598770''>your</span> <span m=''2598960''>own</span> <span m=''2599250''>particular</span>
  <span m=''2599790''>region</span> <span m=''2600640''>specifically</span> <span
  m=''2601350''>so</span> <span m=''2601650''>that</span> <span m=''2601810''>you</span>
  <span m=''2601940''>can</span> <span m=''2602060''>do</span> <span m=''2602200''>coalescing</span>
  <span m=''2602900''>of</span> <span m=''2603020''>things</span> <span m=''2603350''>in</span>
  <span m=''2604220''>that</span> <span m=''2604350''>region.</span> <span m=''2606100''>And</span>
  <span m=''2606250''>so</span> <span m=''2606350''>you</span> <span m=''2606460''>may</span>
  <span m=''2606610''>have</span> <span m=''2606760''>multiple</span> <span m=''2607340''>allocators,</span>
  <span m=''2608080''>and</span> <span m=''2608270''>you''ll</span> <span m=''2608440''>call</span>
  <span m=''2608760''>the</span> <span m=''2608890''>allocator</span> <span m=''2609820''>on</span>
  <span m=''2610020''>the</span> <span m=''2610110''>region,</span> <span m=''2610800''>say,
  for a</span> <span m=''2611210''>graph,</span> <span m=''2611610''>because</span>
  <span m=''2611930''>let''s</span> <span m=''2612290''>imagine</span> <span m=''2612700''>you''re</span>
  <span m=''2612810''>creating</span> <span m=''2613210''>two</span> <span m=''2613370''>graphs,</span>
  <span m=''2614380''>and</span> <span m=''2614560''>one</span> <span m=''2614720''>of</span>
  <span m=''2614780''>them</span> <span m=''2614910''>you''re</span> <span m=''2615030''>going</span>
  <span m=''2615120''>to</span> <span m=''2615180''>keep</span> <span m=''2615470''>around,</span>
  <span m=''2615790''>and</span> <span m=''2615850''>the</span> <span m=''2615970''>other</span>
  <span m=''2616140''>you''re</span> <span m=''2616310''>going</span> <span m=''2616410''>to</span>
  <span m=''2616510''>dump.</span> <span m=''2617060''>Well,</span> <span m=''2617250''>if</span>
  <span m=''2617330''>I</span> <span m=''2617420''>create</span> <span m=''2617690''>them</span>
  <span m=''2617810''>at</span> <span m=''2617880''>the</span> <span m=''2617950''>same</span>
  <span m=''2618240''>time,</span> <span m=''2618660''>the</span> <span m=''2618740''>storage</span>
  <span m=''2619160''>gets</span> <span m=''2619340''>all intermixed,</span> <span
  m=''2620860''>I''ll</span> <span m=''2621195''>deallocate</span> <span m=''2622010''>one</span>
  <span m=''2622260''>graph.</span> <span m=''2623120''>The</span> <span m=''2623270''>other</span>
  <span m=''2623450''>one</span> <span m=''2623720''>will</span> <span m=''2623870''>be,</span>
  <span m=''2624230''>I''ll</span> <span m=''2624390''>have</span> <span m=''2624630''>fragmentation</span>
  <span m=''2625380''>all</span> <span m=''2625620''>over.</span> <span m=''2626020''>These</span>
  <span m=''2626220''>little</span> <span m=''2626460''>spots</span> <span m=''2627270''>appeared</span>
  <span m=''2627680''>where</span> <span m=''2627780''>the</span> <span m=''2627920''>other</span>
  <span m=''2628060''>graph</span> <span m=''2628410''>used</span> <span m=''2628570''>to</span>
  <span m=''2628720''>be--</span> <span m=''2629380''>not</span> <span m=''2629580''>so</span>
  <span m=''2629740''>good.</span> </p><p><span m=''2630380''>But</span> <span m=''2630550''>if</span>
  <span m=''2630670''>I</span> <span m=''2630800''>say,</span> <span m=''2631690''>use</span>
  <span m=''2632030''>this</span> <span m=''2632240''>allocator</span> <span m=''2632810''>for</span>
  <span m=''2632900''>this</span> <span m=''2633150''>graph,</span> <span m=''2633770''>use</span>
  <span m=''2633990''>that</span> <span m=''2634220''>allocator</span> <span m=''2634730''>for</span>
  <span m=''2634850''>that</span> <span m=''2635160''>graph,</span> <span m=''2636440''>then</span>
  <span m=''2636760''>when</span> <span m=''2636960''>I''m</span> <span m=''2637570''>done</span>
  <span m=''2639000''>and</span> <span m=''2639200''>I''m</span> <span m=''2639310''>allocating</span>
  <span m=''2639800''>those</span> <span m=''2640000''>out</span> <span m=''2640120''>of</span>
  <span m=''2640230''>two</span> <span m=''2640370''>different</span> <span m=''2640660''>regions</span>
  <span m=''2641030''>of</span> <span m=''2641100''>memory,</span> <span m=''2641790''>that</span>
  <span m=''2641980''>when</span> <span m=''2642140''>I''m</span> <span m=''2642260''>done</span>
  <span m=''2642530''>with</span> <span m=''2642650''>the</span> <span m=''2642710''>first</span>
  <span m=''2643110''>graph</span> <span m=''2643460''>and</span> <span m=''2645160''>deallocate</span>
  <span m=''2646000''>everything,</span> <span m=''2646620''>now</span> <span m=''2646840''>I''ve</span>
  <span m=''2647030''>created</span> <span m=''2647440''>a</span> <span m=''2647460''>nice</span>
  <span m=''2647790''>big</span> <span m=''2648000''>piece</span> <span m=''2648260''>of</span>
  <span m=''2648340''>contiguous</span> <span m=''2648850''>storage.</span> <span
  m=''2650650''>So</span> <span m=''2651230''>people</span> <span m=''2651600''>will</span>
  <span m=''2651760''>sometimes</span> <span m=''2652250''>play</span> <span m=''2652620''>with</span>
  <span m=''2655520''>different</span> <span m=''2655820''>memory</span> <span m=''2656150''>pools</span>
  <span m=''2656610''>for</span> <span m=''2656750''>allocators,</span> <span m=''2657760''>and</span>
  <span m=''2657920''>C++</span> <span m=''2658670''>has</span> <span m=''2658870''>a</span>
  <span m=''2659120''>fairly</span> <span m=''2659440''>rich</span> <span m=''2661440''>set</span>
  <span m=''2661640''>of</span> <span m=''2662940''>libraries</span> <span m=''2663550''>and</span>
  <span m=''2663640''>so</span> <span m=''2663800''>forth</span> <span m=''2664070''>for</span>
  <span m=''2664180''>that,</span> <span m=''2665220''>to</span> <span m=''2665600''>allow</span>
  <span m=''2665860''>you</span> <span m=''2665980''>to</span> <span m=''2666080''>do</span>
  <span m=''2666220''>that</span> <span m=''2666420''>kind</span> <span m=''2666570''>of</span>
  <span m=''2666720''>thing.</span> </p><p><span m=''2670170''>So</span> <span m=''2672520''>let''s</span>
  <span m=''2672770''>go</span> <span m=''2673050''>on</span> <span m=''2673300''>and</span>
  <span m=''2673520''>talk</span> <span m=''2673960''>about</span> <span m=''2674660''>garbage</span>
  <span m=''2675130''>collection,</span> <span m=''2675570''>because</span> <span
  m=''2675800''>that''s</span> <span m=''2676000''>something</span> <span m=''2676290''>you''ve</span>
  <span m=''2676430''>probably</span> <span m=''2676940''>seen</span> <span m=''2677340''>in</span>
  <span m=''2677520''>Java</span> <span m=''2677880''>and</span> <span m=''2678040''>Python,</span>
  <span m=''2679060''>and</span> <span m=''2679230''>what''s</span> <span m=''2679460''>going</span>
  <span m=''2679720''>on</span> <span m=''2679960''>under</span> <span m=''2680170''>the</span>
  <span m=''2680280''>covers</span> <span m=''2680670''>there.</span> <span m=''2680940''>Because</span>
  <span m=''2682130''>even</span> <span m=''2682370''>though</span> <span m=''2682510''>C</span>
  <span m=''2682810''>and</span> <span m=''2683450''>C++</span> <span m=''2684180''>do</span>
  <span m=''2684290''>not</span> <span m=''2684560''>have</span> <span m=''2684770''>garbage</span>
  <span m=''2685210''>collection,</span> <span m=''2685630''>you</span> <span m=''2685790''>can</span>
  <span m=''2685940''>actually</span> <span m=''2686290''>implement</span> <span m=''2686730''>your</span>
  <span m=''2686910''>own</span> <span m=''2687050''>garbage</span> <span m=''2687450''>collector.</span>
  <span m=''2687860''>It''s</span> <span m=''2688020''>not</span> <span m=''2688250''>that</span>
  <span m=''2688460''>hard,</span> <span m=''2691550''>except</span> <span m=''2691890''>for</span>
  <span m=''2691990''>some</span> <span m=''2692200''>details.</span> <span m=''2695260''>It''s</span>
  <span m=''2695430''>only</span> <span m=''2695650''>hard</span> <span m=''2695910''>when</span>
  <span m=''2696030''>you</span> <span m=''2696120''>want</span> <span m=''2696270''>it</span>
  <span m=''2696340''>to</span> <span m=''2696420''>perform</span> <span m=''2696890''>well.</span>
  </p><p><span m=''2699840''>So</span> <span m=''2699990''>the</span> <span m=''2700120''>idea</span>
  <span m=''2700530''>is</span> <span m=''2701050''>to</span> <span m=''2701160''>free</span>
  <span m=''2701500''>the</span> <span m=''2701630''>programmer</span> <span m=''2702180''>from</span>
  <span m=''2702360''>freeing</span> <span m=''2702730''>objects.</span> <span m=''2704310''>The</span>
  <span m=''2704440''>downside,</span> <span m=''2705070''>by</span> <span m=''2705190''>the</span>
  <span m=''2705280''>way,</span> <span m=''2705400''>is</span> <span m=''2705500''>when</span>
  <span m=''2705620''>you</span> <span m=''2705710''>free</span> <span m=''2705960''>the</span>
  <span m=''2706040''>programmer</span> <span m=''2706490''>from</span> <span m=''2706680''>freeing</span>
  <span m=''2707030''>objects,</span> <span m=''2707750''>they</span> <span m=''2707900''>tend</span>
  <span m=''2708120''>to</span> <span m=''2708200''>create</span> <span m=''2708600''>lots</span>
  <span m=''2708910''>of</span> <span m=''2708990''>garbage.</span> <span m=''2710570''>And</span>
  <span m=''2710720''>so</span> <span m=''2710820''>what</span> <span m=''2710920''>happens</span>
  <span m=''2711330''>in</span> <span m=''2711450''>Java</span> <span m=''2711840''>programs,</span>
  <span m=''2712390''>for</span> <span m=''2712490''>example,</span> <span m=''2713220''>is</span>
  <span m=''2713460''>you''ll</span> <span m=''2713640''>have</span> <span m=''2713870''>these--</span>
  <span m=''2715120''>I</span> <span m=''2715220''>remember</span> <span m=''2715520''>once</span>
  <span m=''2715860''>having</span> <span m=''2716660''>a</span> <span m=''2718040''>Java</span>
  <span m=''2718380''>program</span> <span m=''2718840''>where,</span> <span m=''2719030''>when</span>
  <span m=''2719270''>it</span> <span m=''2719340''>was</span> <span m=''2719460''>sitting,</span>
  <span m=''2720000''>waiting</span> <span m=''2720370''>for</span> <span m=''2720520''>user</span>
  <span m=''2720910''>input,</span> <span m=''2722550''>it</span> <span m=''2722670''>would</span>
  <span m=''2722780''>periodically</span> <span m=''2723640''>go,</span> <span m=''2724360''>garbage</span>
  <span m=''2724700''>collect.</span> <span m=''2725750''>It was</span> <span m=''2726100''>just</span>
  <span m=''2726250''>sitting</span> <span m=''2726600''>there,</span> <span m=''2727110''>and</span>
  <span m=''2727530''>then it would</span> <span m=''2727600''>go,</span> <span m=''2727800''>garbage</span>
  <span m=''2728280''>collect.</span> <span m=''2729050''>We</span> <span m=''2729210''>weren''t</span>
  <span m=''2729340''>doing</span> <span m=''2729630''>anything.</span> <span m=''2730010''>It
  was</span> <span m=''2730100''>just</span> <span m=''2730780''>periodically,</span>
  <span m=''2732070''>the</span> <span m=''2732240''>way</span> <span m=''2732440''>they</span>
  <span m=''2732590''>had</span> <span m=''2732700''>written</span> <span m=''2732920''>the</span>
  <span m=''2733030''>code,</span> <span m=''2733460''>they</span> <span m=''2733570''>were</span>
  <span m=''2733990''>somehow</span> <span m=''2734430''>generating</span> <span m=''2735170''>garbage,</span>
  <span m=''2735800''>doing</span> <span m=''2736030''>allocations</span> <span m=''2736820''>and</span>
  <span m=''2736940''>frees,</span> <span m=''2737820''>when</span> <span m=''2738040''>you</span>
  <span m=''2738130''>were</span> <span m=''2738230''>sitting</span> <span m=''2738520''>around</span>
  <span m=''2738850''>doing</span> <span m=''2739080''>nothing.</span> <span m=''2740540''>And</span>
  <span m=''2740720''>so</span> <span m=''2740910''>it would</span> <span m=''2741010''>basically</span>
  <span m=''2741540''>use</span> <span m=''2741840''>up</span> <span m=''2742050''>all
  of</span> <span m=''2742230''>the</span> <span m=''2742400''>space</span> <span
  m=''2743210''>and</span> <span m=''2743360''>then</span> <span m=''2743510''>do
  a</span> <span m=''2743660''>garbage</span> <span m=''2744050''>collection,</span>
  <span m=''2744420''>use</span> <span m=''2744580''>up</span> <span m=''2744710''>all</span>
  <span m=''2744810''>the</span> <span m=''2744910''>space</span> <span m=''2745200''>and
  do</span> <span m=''2745370''>a garbage</span> <span m=''2745690''>collection.</span>
  <span m=''2746260''>Naturally</span> <span m=''2746800''>that''s</span> <span m=''2747560''>kind</span>
  <span m=''2747770''>of</span> <span m=''2747840''>a</span> <span m=''2747890''>slow</span>
  <span m=''2748170''>system.</span> </p><p><span m=''2748840''>And</span> <span m=''2748990''>so</span>
  <span m=''2749280''>even</span> <span m=''2749610''>in</span> <span m=''2749730''>something</span>
  <span m=''2750160''>like</span> <span m=''2750360''>Java,</span> <span m=''2750750''>where
  you</span> <span m=''2750880''>have</span> <span m=''2751060''>a</span> <span m=''2751100''>garbage</span>
  <span m=''2751520''>collector,</span> <span m=''2752050''>you</span> <span m=''2752170''>do</span>
  <span m=''2752340''>have</span> <span m=''2752520''>to</span> <span m=''2752640''>worry</span>
  <span m=''2753000''>about</span> <span m=''2753320''>whether</span> <span m=''2753550''>you''re</span>
  <span m=''2753770''>creating</span> <span m=''2754250''>garbage</span> <span m=''2754660''>or</span>
  <span m=''2754730''>not, and</span> <span m=''2755210''>you</span> <span m=''2755390''>can</span>
  <span m=''2755520''>generate</span> <span m=''2755950''>faster</span> <span m=''2756390''>code</span>
  <span m=''2757200''>by</span> <span m=''2757570''>not</span> <span m=''2757890''>creating</span>
  <span m=''2758290''>as</span> <span m=''2758400''>much</span> <span m=''2758610''>garbage,</span>
  <span m=''2759110''>or</span> <span m=''2759340''>by</span> <span m=''2760030''>finding</span>
  <span m=''2760380''>ways</span> <span m=''2760700''>of</span> <span m=''2760820''>recycling</span>
  <span m=''2761750''>the</span> <span m=''2761860''>garbage</span> <span m=''2762250''>yourself.</span>
  <span m=''2763120''>So</span> <span m=''2764260''>even</span> <span m=''2764520''>in</span>
  <span m=''2764620''>Java,</span> <span m=''2764950''>it''s</span> <span m=''2765100''>worthwhile</span>
  <span m=''2765600''>saying,</span> <span m=''2766250''>give</span> <span m=''2766390''>me</span>
  <span m=''2766530''>a</span> <span m=''2766580''>big</span> <span m=''2766760''>chunk</span>
  <span m=''2766970''>of</span> <span m=''2767030''>memory,</span> <span m=''2767390''>let</span>
  <span m=''2767520''>me</span> <span m=''2767650''>manage</span> <span m=''2768000''>it</span>
  <span m=''2768080''>myself,</span> <span m=''2768890''>now</span> <span m=''2769050''>let</span>
  <span m=''2769190''>me</span> <span m=''2769290''>free</span> <span m=''2769560''>it.</span>
  <span m=''2769960''>I</span> <span m=''2770040''>don''t</span> <span m=''2770230''>have</span>
  <span m=''2770380''>to</span> <span m=''2770490''>free it,</span> <span m=''2770910''>but</span>
  <span m=''2771230''>when</span> <span m=''2771430''>I''m</span> <span m=''2771540''>done</span>
  <span m=''2771720''>with</span> <span m=''2771860''>it,</span> <span m=''2771970''>I''ll</span>
  <span m=''2772080''>be</span> <span m=''2772220''>done</span> <span m=''2772440''>with</span>
  <span m=''2772580''>it.</span> <span m=''2772670''>But</span> <span m=''2772770''>in</span>
  <span m=''2772840''>the</span> <span m=''2772900''>meantime,</span> <span m=''2773690''>let</span>
  <span m=''2773830''>me</span> <span m=''2773960''>manage</span> <span m=''2774320''>it</span>
  <span m=''2774410''>myself</span> <span m=''2774860''>so</span> <span m=''2775010''>that</span>
  <span m=''2775110''>I</span> <span m=''2775170''>don''t</span> <span m=''2775750''>have</span>
  <span m=''2776020''>it</span> <span m=''2776340''>continually</span> <span m=''2776860''>generating</span>
  <span m=''2778700''>more</span> <span m=''2779180''>garbage.</span> </p><p><span
  m=''2780790''>So</span> <span m=''2781460''>the</span> <span m=''2781620''>garbage</span>
  <span m=''2781960''>collector</span> <span m=''2782200''>can</span> <span m=''2782340''>be</span>
  <span m=''2782460''>built</span> <span m=''2782780''>in,</span> <span m=''2783050''>or</span>
  <span m=''2783790''>you</span> <span m=''2783900''>can</span> <span m=''2784020''>do</span>
  <span m=''2784150''>it</span> <span m=''2784220''>yourself.</span> <span m=''2785350''>And</span>
  <span m=''2785670''>mostly</span> <span m=''2786550''>in</span> <span m=''2786650''>this</span>
  <span m=''2786800''>class,</span> <span m=''2787140''>we</span> <span m=''2787240''>do</span>
  <span m=''2787370''>stuff</span> <span m=''2787630''>ourselves,</span> <span m=''2788690''>so</span>
  <span m=''2788850''>we</span> <span m=''2788930''>know</span> <span m=''2789020''>how</span>
  <span m=''2789150''>they</span> <span m=''2789240''>work.</span> <span m=''2790290''>So</span>
  <span m=''2790430''>that</span> <span m=''2790590''>even</span> <span m=''2790870''>when</span>
  <span m=''2791030''>you''re</span> <span m=''2791140''>doing</span> <span m=''2791450''>it</span>
  <span m=''2791680''>with</span> <span m=''2791880''>built</span> <span m=''2792130''>in,</span>
  <span m=''2792390''>you know</span> <span m=''2792840''>what''s</span> <span m=''2793050''>going</span>
  <span m=''2793290''>on</span> <span m=''2793480''>under</span> <span m=''2793600''>the</span>
  <span m=''2793720''>covers.</span> </p><p><span m=''2796470''>So</span> <span m=''2797280''>here''s</span>
  <span m=''2797490''>some</span> <span m=''2797630''>terminology.</span> <span m=''2798450''>The</span>
  <span m=''2798570''>roots</span> <span m=''2800100''>in</span> <span m=''2800310''>garbage</span>
  <span m=''2800630''>collection</span> <span m=''2800990''>are</span> <span m=''2801040''>the</span>
  <span m=''2801160''>objects</span> <span m=''2801660''>that are</span> <span m=''2801820''>directly</span>
  <span m=''2802310''>accessible</span> <span m=''2802880''>by</span> <span m=''2803090''>the</span>
  <span m=''2803200''>program.</span> <span m=''2803930''>And</span> <span m=''2804110''>those</span>
  <span m=''2804350''>typically</span> <span m=''2804820''>are</span> <span m=''2804960''>things</span>
  <span m=''2805190''>like</span> <span m=''2805350''>globals,</span> <span m=''2806190''>stacked</span>
  <span m=''2806770''>variables,</span> <span m=''2807900''>and</span> <span m=''2808070''>so</span>
  <span m=''2808270''>forth.</span> <span m=''2808570''>Things</span> <span m=''2808850''>that</span>
  <span m=''2808940''>the</span> <span m=''2809020''>program</span> <span m=''2810510''>can</span>
  <span m=''2811170''>directly</span> <span m=''2811670''>address</span> <span m=''2812040''>by</span>
  <span m=''2812210''>name.</span> <span m=''2813830''>The</span> <span m=''2813910''>live</span>
  <span m=''2814380''>objects</span> <span m=''2814980''>are</span> <span m=''2815240''>reachable</span>
  <span m=''2815720''>from</span> <span m=''2815900''>the</span> <span m=''2815990''>roots</span>
  <span m=''2816410''>by</span> <span m=''2816560''>following</span> <span m=''2817100''>pointers,</span>
  <span m=''2818530''>and</span> <span m=''2818710''>the</span> <span m=''2818790''>debt</span>
  <span m=''2819050''>objects</span> <span m=''2819550''>are</span> <span m=''2819660''>the</span>
  <span m=''2819760''>ones</span> <span m=''2820050''>that</span> <span m=''2820790''>the</span>
  <span m=''2820890''>programmer</span> <span m=''2821390''>can</span> <span m=''2821610''>never</span>
  <span m=''2821900''>get</span> <span m=''2822190''>to</span> <span m=''2822340''>again.</span>
  <span m=''2824790''>And</span> <span m=''2825030''>so</span> <span m=''2826090''>what</span>
  <span m=''2826390''>we''re</span> <span m=''2826530''>interested</span> <span m=''2826850''>in</span>
  <span m=''2826940''>doing in</span> <span m=''2827200''>garbage</span> <span m=''2827600''>collection</span>
  <span m=''2828180''>is</span> <span m=''2828630''>finding</span> <span m=''2829040''>all</span>
  <span m=''2829690''>the</span> <span m=''2830200''>dead</span> <span m=''2830460''>objects</span>
  <span m=''2831530''>and</span> <span m=''2831740''>recycling</span> <span m=''2832340''>them</span>
  <span m=''2832480''>so</span> <span m=''2832610''>we</span> <span m=''2832710''>can</span>
  <span m=''2832850''>use</span> <span m=''2833080''>them</span> <span m=''2833240''>again,</span>
  <span m=''2833840''>so that</span> <span m=''2834000''>they</span> <span m=''2834170''>don''t</span>
  <span m=''2834390''>end</span> <span m=''2834550''>up</span> <span m=''2834690''>taking
  up</span> <span m=''2835060''>space</span> <span m=''2835560''>in</span> <span m=''2835740''>our</span>
  <span m=''2835910''>virtual</span> <span m=''2836270''>memory</span> <span m=''2837050''>and</span>
  <span m=''2837440''>slowing</span> <span m=''2837970''>us</span> <span m=''2838150''>down</span>
  <span m=''2838590''>by</span> <span m=''2839240''>making</span> <span m=''2839590''>our</span>
  <span m=''2839710''>virtual</span> <span m=''2840090''>memory</span> <span m=''2840390''>space</span>
  <span m=''2840830''>continue</span> <span m=''2841270''>to</span> <span m=''2841350''>grow</span>
  <span m=''2841700''>and</span> <span m=''2841770''>grow</span> <span m=''2842050''>and</span>
  <span m=''2842140''>grow</span> <span m=''2843230''>across</span> <span m=''2844250''>many</span>
  <span m=''2844510''>disk</span> <span m=''2844770''>pages.</span> </p><p><span m=''2847050''>So</span>
  <span m=''2847670''>one</span> <span m=''2847950''>of</span> <span m=''2848030''>the</span>
  <span m=''2848110''>questions,</span> <span m=''2848640''>in</span> <span m=''2848720''>order</span>
  <span m=''2849000''>for</span> <span m=''2849520''>one</span> <span m=''2849770''>to</span>
  <span m=''2849860''>be</span> <span m=''2850000''>able</span> <span m=''2850300''>to</span>
  <span m=''2853000''>do</span> <span m=''2853220''>garbage</span> <span m=''2853670''>collection,</span>
  <span m=''2854090''>is</span> <span m=''2854180''>how</span> <span m=''2854490''>do</span>
  <span m=''2854650''>I</span> <span m=''2854790''>know</span> <span m=''2856200''>where</span>
  <span m=''2856560''>pointers</span> <span m=''2857080''>are</span> <span m=''2857360''>in</span>
  <span m=''2857490''>objects?</span> <span m=''2859080''>How</span> <span m=''2859230''>do</span>
  <span m=''2859330''>I</span> <span m=''2859400''>know</span> <span m=''2859620''>what''s</span>
  <span m=''2859860''>accessible?</span> <span m=''2861200''>And</span> <span m=''2861360''>so</span>
  <span m=''2861500''>typically,</span> <span m=''2862810''>in</span> <span m=''2862960''>order</span>
  <span m=''2863220''>to</span> <span m=''2863330''>do</span> <span m=''2863530''>that,</span>
  <span m=''2863850''>you</span> <span m=''2864020''>have</span> <span m=''2864180''>to</span>
  <span m=''2864270''>have</span> <span m=''2864500''>a</span> <span m=''2864590''>very</span>
  <span m=''2864860''>strong</span> <span m=''2865360''>idea</span> <span m=''2865635''>of</span>
  <span m=''2865910''>where</span> <span m=''2866400''>is</span> <span m=''2866590''>a</span>
  <span m=''2866640''>pointer</span> <span m=''2867290''>and</span> <span m=''2867440''>where</span>
  <span m=''2867710''>is</span> <span m=''2867950''>data?</span> <span m=''2868730''>Because</span>
  <span m=''2868900''>you</span> <span m=''2869000''>don''t</span> <span m=''2869140''>want</span>
  <span m=''2869270''>to</span> <span m=''2869320''>follow</span> <span m=''2869730''>data</span>
  <span m=''2870070''>as</span> <span m=''2870310''>if</span> <span m=''2870410''>it''s</span>
  <span m=''2870580''>a</span> <span m=''2870630''>pointer,</span> <span m=''2871460''>you</span>
  <span m=''2871580''>want</span> <span m=''2871720''>to</span> <span m=''2871790''>know</span>
  <span m=''2872120''>which</span> <span m=''2872550''>regions</span> <span m=''2873100''>of</span>
  <span m=''2873360''>a</span> <span m=''2873440''>given</span> <span m=''2873810''>block</span>
  <span m=''2874220''>of</span> <span m=''2874280''>memory</span> <span m=''2875030''>are</span>
  <span m=''2875220''>pointers.</span> <span m=''2876090''>And</span> <span m=''2876210''>so</span>
  <span m=''2876340''>strong</span> <span m=''2876840''>typing</span> <span m=''2877260''>helps</span>
  <span m=''2877570''>a</span> <span m=''2877630''>lot</span> <span m=''2877910''>with</span>
  <span m=''2878050''>that,</span> <span m=''2878490''>which</span> <span m=''2878660''>is</span>
  <span m=''2878780''>why</span> <span m=''2879370''>mostly</span> <span m=''2879770''>people</span>
  <span m=''2880040''>do</span> <span m=''2880160''>garbage</span> <span m=''2880550''>collection</span>
  <span m=''2881390''>in</span> <span m=''2881740''>strongly</span> <span m=''2882240''>typed</span>
  <span m=''2882540''>languages,</span> <span m=''2883420''>because</span> <span m=''2883600''>then</span>
  <span m=''2883740''>you</span> <span m=''2883840''>can</span> <span m=''2883960''>actually</span>
  <span m=''2884220''>identify</span> <span m=''2884800''>it.</span> </p><p><span
  m=''2885590''>It</span> <span m=''2885740''>also</span> <span m=''2886790''>requires</span>
  <span m=''2887310''>you</span> <span m=''2887450''>to</span> <span m=''2887540''>prohibit</span>
  <span m=''2888220''>pointer</span> <span m=''2888700''>arithmetic.</span> <span
  m=''2890040''>So</span> <span m=''2890170''>the</span> <span m=''2890220''>ability</span>
  <span m=''2890590''>to</span> <span m=''2890630''>take</span> <span m=''2890850''>a</span>
  <span m=''2890920''>pointer</span> <span m=''2891340''>and</span> <span m=''2891460''>then</span>
  <span m=''2891580''>index</span> <span m=''2892070''>off</span> <span m=''2892280''>that</span>
  <span m=''2892530''>pointer</span> <span m=''2893900''>means</span> <span m=''2894150''>I</span>
  <span m=''2894260''>can</span> <span m=''2894490''>get</span> <span m=''2894720''>to</span>
  <span m=''2894820''>some</span> <span m=''2895040''>piece</span> <span m=''2895300''>of</span>
  <span m=''2895380''>storage</span> <span m=''2895870''>that</span> <span m=''2896000''>I</span>
  <span m=''2896060''>can''t</span> <span m=''2896360''>access</span> <span m=''2896820''>directly.</span>
  <span m=''2898140''>And</span> <span m=''2898260''>so</span> <span m=''2898360''>typically</span>
  <span m=''2898830''>in</span> <span m=''2898950''>these</span> <span m=''2899270''>kinds</span>
  <span m=''2899530''>of</span> <span m=''2899610''>systems,</span> <span m=''2900280''>pointer</span>
  <span m=''2900640''>arithmetic</span> <span m=''2901370''>is</span> <span m=''2901820''>illegal.</span>
  <span m=''2903940''>So</span> <span m=''2904080''>you</span> <span m=''2904230''>can</span>
  <span m=''2904370''>do</span> <span m=''2904610''>array</span> <span m=''2905760''>indexing,</span>
  <span m=''2906380''>as</span> <span m=''2906490''>long</span> <span m=''2906720''>as</span>
  <span m=''2906800''>you</span> <span m=''2906910''>treat</span> <span m=''2907380''>the
  array</span> <span m=''2908000''>as</span> <span m=''2908180''>a</span> <span m=''2908230''>single</span>
  <span m=''2908610''>object.</span> <span m=''2909310''>You</span> <span m=''2909440''>can''t</span>
  <span m=''2909720''>treat</span> <span m=''2909970''>an</span> <span m=''2910120''>array</span>
  <span m=''2910480''>as</span> <span m=''2910710''>the</span> <span m=''2910930''>component</span>
  <span m=''2911450''>pieces.</span> <span m=''2913450''>You</span> <span m=''2913640''>have</span>
  <span m=''2913820''>to</span> <span m=''2913950''>treat</span> <span m=''2914200''>it</span>
  <span m=''2914290''>as</span> <span m=''2914450''>a</span> <span m=''2914500''>single</span>
  <span m=''2914870''>object.</span> <span m=''2916070''>So</span> <span m=''2916230''>pointer</span>
  <span m=''2916560''>arithmetic.</span> </p><p><span m=''2917310''>Well,</span> <span
  m=''2918100''>you</span> <span m=''2918240''>folks,</span> <span m=''2918930''>who''s</span>
  <span m=''2919210''>familiar</span> <span m=''2919550''>with</span> <span m=''2919720''>pointer</span>
  <span m=''2919910''>arithmetic?</span> <span m=''2921420''>At this</span> <span
  m=''2921600''>point,</span> <span m=''2921820''>almost</span> <span m=''2922130''>all</span>
  <span m=''2922390''>of</span> <span m=''2922490''>you</span> <span m=''2922650''>have</span>
  <span m=''2922800''>done</span> <span m=''2922970''>stuff</span> <span m=''2923220''>with</span>
  <span m=''2923320''>pointer</span> <span m=''2923650''>arithmetic,</span> <span
  m=''2924330''>if</span> <span m=''2924480''>your</span> <span m=''2924600''>code</span>
  <span m=''2924820''>is</span> <span m=''2924940''>any</span> <span m=''2925100''>good.</span>
  <span m=''2927770''>Almost</span> <span m=''2928060''>all</span> <span m=''2928260''>of</span>
  <span m=''2928370''>you have</span> <span m=''2928530''>done</span> <span m=''2929330''>adding</span>
  <span m=''2929740''>to</span> <span m=''2930070''>pointers</span> <span m=''2930510''>in</span>
  <span m=''2930580''>order</span> <span m=''2930820''>to</span> <span m=''2930940''>move</span>
  <span m=''2931160''>through an</span> <span m=''2931510''>array</span> <span m=''2931730''>or</span>
  <span m=''2931820''>what</span> <span m=''2931960''>have</span> <span m=''2932230''>you</span>
  <span m=''2932690''>as</span> <span m=''2932860''>being</span> <span m=''2933630''>somewhat</span>
  <span m=''2934020''>cheaper</span> <span m=''2934820''>than</span> <span m=''2935060''>doing</span>
  <span m=''2935280''>an</span> <span m=''2935360''>array</span> <span m=''2935660''>index</span>
  <span m=''2936030''>every</span> <span m=''2936240''>time.</span> <span m=''2937370''>It</span>
  <span m=''2937560''>saves</span> <span m=''2937840''>you</span> <span m=''2939170''>an</span>
  <span m=''2939300''>extra</span> <span m=''2939770''>memory</span> <span m=''2940060''>reference,</span>
  <span m=''2940470''>typically.</span> <span m=''2942460''>So</span> <span m=''2943360''>that''s</span>
  <span m=''2943610''>one</span> <span m=''2943850''>of</span> <span m=''2943970''>their</span>
  <span m=''2944170''>restrictions</span> <span m=''2944840''>when</span> <span m=''2944970''>you</span>
  <span m=''2945060''>want</span> <span m=''2945240''>to</span> <span m=''2945300''>do</span>
  <span m=''2945430''>garbage</span> <span m=''2945880''>collection</span> <span m=''2946390''>in</span>
  <span m=''2946580''>a</span> <span m=''2946630''>general</span> <span m=''2946970''>setting.</span>
  </p><p><span m=''2948530''>Now</span> <span m=''2948630''>probably</span> <span
  m=''2948990''>the</span> <span m=''2949110''>simplest</span> <span m=''2949820''>and</span>
  <span m=''2950120''>most</span> <span m=''2950400''>useful</span> <span m=''2950980''>one</span>
  <span m=''2951230''>as</span> <span m=''2951310''>a</span> <span m=''2951380''>programmer</span>
  <span m=''2952670''>to</span> <span m=''2952790''>use</span> <span m=''2953280''>for</span>
  <span m=''2953920''>garbage</span> <span m=''2954290''>collection</span> <span m=''2954650''>is</span>
  <span m=''2954760''>what''s</span> <span m=''2954930''>called</span> <span m=''2955150''>reference</span>
  <span m=''2955620''>counting.</span> <span m=''2956680''>I</span> <span m=''2956870''>know</span>
  <span m=''2957060''>many,</span> <span m=''2957440''>many</span> <span m=''2957700''>programs</span>
  <span m=''2958440''>where</span> <span m=''2958660''>what</span> <span m=''2958850''>you</span>
  <span m=''2958960''>do</span> <span m=''2959150''>is</span> <span m=''2959240''>you</span>
  <span m=''2959340''>do</span> <span m=''2959490''>reference</span> <span m=''2960010''>counting</span>
  <span m=''2961280''>because</span> <span m=''2961690''>you</span> <span m=''2961820''>can.</span>
  <span m=''2963130''>But</span> <span m=''2963410''>as</span> <span m=''2963570''>you''ll</span>
  <span m=''2963690''>see,</span> <span m=''2963870''>it</span> <span m=''2963960''>has</span>
  <span m=''2964180''>a</span> <span m=''2964230''>limitation.</span> </p><p><span
  m=''2965660''>So</span> <span m=''2965780''>the</span> <span m=''2965920''>idea</span>
  <span m=''2966320''>in</span> <span m=''2966450''>reference</span> <span m=''2966850''>counting</span>
  <span m=''2967570''>is</span> <span m=''2967720''>to</span> <span m=''2967850''>keep</span>
  <span m=''2968110''>a</span> <span m=''2968450''>count</span> <span m=''2968880''>of</span>
  <span m=''2968950''>the</span> <span m=''2969050''>number</span> <span m=''2969390''>of</span>
  <span m=''2969460''>pointers</span> <span m=''2970570''>referencing</span> <span
  m=''2971150''>each</span> <span m=''2971390''>object.</span> <span m=''2971890''>So</span>
  <span m=''2972010''>here</span> <span m=''2972260''>we</span> <span m=''2972360''>have</span>
  <span m=''2972530''>a</span> <span m=''2972570''>whole</span> <span m=''2972760''>bunch</span>
  <span m=''2972960''>of</span> <span m=''2973060''>different</span> <span m=''2973310''>objects</span>
  <span m=''2973700''>of</span> <span m=''2973780''>different</span> <span m=''2974070''>sizes,</span>
  <span m=''2974960''>and</span> <span m=''2975100''>whenever</span> <span m=''2975420''>there''s</span>
  <span m=''2975590''>a</span> <span m=''2975660''>pointer</span> <span m=''2976050''>going</span>
  <span m=''2976330''>to</span> <span m=''2976470''>the</span> <span m=''2976630''>object,</span>
  <span m=''2977110''>I</span> <span m=''2977280''>add</span> <span m=''2977600''>one</span>
  <span m=''2977870''>to</span> <span m=''2977950''>the</span> <span m=''2978050''>reference</span>
  <span m=''2978500''>count</span> <span m=''2978770''>shown</span> <span m=''2979110''>in</span>
  <span m=''2979240''>green at the</span> <span m=''2979580''>top</span> <span m=''2979960''>here.</span>
  <span m=''2981070''>I</span> <span m=''2981230''>hope</span> <span m=''2981550''>I</span>
  <span m=''2981620''>got</span> <span m=''2981810''>the</span> <span m=''2981890''>count</span>
  <span m=''2982190''>right.</span> <span m=''2984760''>Whenever</span> <span m=''2985220''>the</span>
  <span m=''2985370''>count</span> <span m=''2985710''>drops</span> <span m=''2986130''>to</span>
  <span m=''2986240''>zero,</span> <span m=''2988050''>you</span> <span m=''2988190''>free</span>
  <span m=''2988550''>the</span> <span m=''2988710''>object.</span> <span m=''2990820''>That</span>
  <span m=''2991010''>means</span> <span m=''2991240''>nobody''s</span> <span m=''2991670''>pointing</span>
  <span m=''2992010''>to</span> <span m=''2992110''>this</span> <span m=''2992270''>object</span>
  <span m=''2992600''>[UNINTELLIGIBLE].</span> <span m=''2992930''>Let''s</span> <span
  m=''2993200''>free</span> <span m=''2993420''>it.</span> <span m=''2993930''>So</span>
  <span m=''2994060''>let''s</span> <span m=''2994190''>see</span> <span m=''2994310''>how</span>
  <span m=''2994480''>that</span> <span m=''2994700''>goes.</span> </p><p><span m=''2996470''>So</span>
  <span m=''2996680''>suppose</span> <span m=''2997000''>that,</span> <span m=''2997320''>for</span>
  <span m=''2997420''>example,</span> <span m=''2997840''>that</span> <span m=''2998120''>pointer</span>
  <span m=''2998460''>got</span> <span m=''2998840''>moved</span> <span m=''2999530''>to</span>
  <span m=''2999830''>over</span> <span m=''3000110''>here.</span> <span m=''3000920''>Went</span>
  <span m=''3001080''>away</span> <span m=''3001340''>from</span> <span m=''3001540''>there,</span>
  <span m=''3001760''>got</span> <span m=''3001990''>moved</span> <span m=''3002100''>to</span>
  <span m=''3002210''>there.</span> <span m=''3002750''>Well,</span> <span m=''3002910''>now</span>
  <span m=''3002990''>there are</span> <span m=''3003240''>two</span> <span m=''3003440''>fields</span>
  <span m=''3003860''>that</span> <span m=''3003950''>have</span> <span m=''3004120''>to</span>
  <span m=''3004280''>be</span> <span m=''3004420''>updated.</span> <span m=''3005800''>The</span>
  <span m=''3005900''>one</span> <span m=''3006090''>that</span> <span m=''3006200''>we</span>
  <span m=''3006310''>took</span> <span m=''3006520''>the</span> <span m=''3006590''>pointer</span>
  <span m=''3006970''>away</span> <span m=''3007290''>from</span> <span m=''3007680''>and</span>
  <span m=''3007860''>the</span> <span m=''3007940''>one</span> <span m=''3008140''>that</span>
  <span m=''3008230''>we</span> <span m=''3008360''>put</span> <span m=''3008560''>it</span>
  <span m=''3008690''>to.</span> </p><p><span m=''3009700''>So</span> <span m=''3009880''>we</span>
  <span m=''3010020''>update</span> <span m=''3010430''>those.</span> <span m=''3011850''>Oops,</span>
  <span m=''3012100''>that</span> <span m=''3012370''>guy</span> <span m=''3012480''>went</span>
  <span m=''3012730''>to</span> <span m=''3012830''>zero.</span> <span m=''3013410''>That</span>
  <span m=''3013630''>means</span> <span m=''3013870''>this</span> <span m=''3014040''>stuff</span>
  <span m=''3014320''>is</span> <span m=''3014530''>garbage.</span> <span m=''3016210''>But</span>
  <span m=''3016420''>I</span> <span m=''3016490''>can''t</span> <span m=''3016840''>just</span>
  <span m=''3017090''>immediately</span> <span m=''3017650''>go</span> <span m=''3017980''>and</span>
  <span m=''3018090''>collect</span> <span m=''3018470''>that</span> <span m=''3018710''>piece</span>
  <span m=''3018930''>of</span> <span m=''3019010''>storage.</span> <span m=''3019490''>Why</span>
  <span m=''3019680''>not?</span> </p><p><span m=''3022956''>AUDIENCE: To save</span>
  <span m=''3023452''>the value of</span> <span m=''3023948''>the</span> <span m=''3024444''>pointer,
  and</span> <span m=''3025436''>[INAUDIBLE]</span> <span m=''3025932''>pointer</span>
  <span m=''3026428''>later?</span> </p><p><span m=''3026924''>CHARLES LEISERSON:
  Yeah, to</span> <span m=''3027430''>save</span> <span m=''3027890''>the</span> <span
  m=''3027970''>value</span> <span m=''3028460''>of</span> <span m=''3028620''>the</span>
  <span m=''3028710''>pointer--</span> </p><p><span m=''3029230''>AUDIENCE: To save</span>
  <span m=''3029717''>the value</span> <span m=''3030204''>of the pointer and then</span>
  <span m=''3030691''>use it again</span> <span m=''3031178''>later.</span> <span
  m=''3032152''>The</span> <span m=''3032639''>pointer isn''t there,</span> <span
  m=''3033126''>but you know where--</span> </p><p><span m=''3035074''>CHARLES LEISERSON:
  Not</span> <span m=''3035561''>quite,</span> <span m=''3036048''>not quite.</span>
  <span m=''3037022''>Yes?</span> </p><p><span m=''3037509''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''3038970''>the reference</span> <span m=''3039457''>counts</span> <span
  m=''3039944''>for</span> <span m=''3040431''>[INAUDIBLE],</span> <span m=''3040918''>and
  also--</span> </p><p><span m=''3041405''>CHARLES LEISERSON: Yeah.</span> <span m=''3041892''>If</span>
  <span m=''3042019''>you''re</span> <span m=''3042146''>going</span> <span m=''3042273''>to</span>
  <span m=''3042400''>deallocate</span> <span m=''3042870''>this</span> <span m=''3043080''>guy,</span>
  <span m=''3043390''>he''s</span> <span m=''3043680''>got</span> <span m=''3043980''>pointers.</span>
  <span m=''3045490''>They</span> <span m=''3045590''>have</span> <span m=''3045940''>to
  follow</span> <span m=''3046330''>his</span> <span m=''3046580''>pointers</span>
  <span m=''3047580''>and</span> <span m=''3047780''>see</span> <span m=''3047960''>which</span>
  <span m=''3048150''>ones</span> <span m=''3048440''>need</span> <span m=''3048630''>to</span>
  <span m=''3048710''>be</span> <span m=''3048850''>deallocated.</span> <span m=''3050690''>Good.</span>
  </p><p><span m=''3052080''>So</span> <span m=''3052820''>this</span> <span m=''3053070''>guy</span>
  <span m=''3053270''>now,</span> <span m=''3053530''>we</span> <span m=''3053650''>realize,</span>
  <span m=''3054050''>is</span> <span m=''3054170''>garbage.</span> <span m=''3054610''>But</span>
  <span m=''3054870''>before</span> <span m=''3055260''>we</span> <span m=''3055370''>can</span>
  <span m=''3055500''>just</span> <span m=''3055690''>free</span> <span m=''3056000''>him,</span>
  <span m=''3057840''>I''ve</span> <span m=''3058070''>got</span> <span m=''3058260''>to
  deallocate</span> <span m=''3059000''>these</span> <span m=''3059250''>pointers.</span>
  <span m=''3061410''>So</span> <span m=''3061570''>this</span> <span m=''3061760''>guy</span>
  <span m=''3061920''>also</span> <span m=''3062180''>got</span> <span m=''3062370''>decremented,</span>
  <span m=''3062910''>but</span> <span m=''3063030''>he</span> <span m=''3063120''>didn''t.</span>
  <span m=''3063510''>So</span> <span m=''3063670''>this</span> <span m=''3063900''>guy,</span>
  <span m=''3064730''>we</span> <span m=''3066180''>have</span> <span m=''3066390''>to</span>
  <span m=''3066480''>decrement</span> <span m=''3067350''>these</span> <span m=''3067600''>two</span>
  <span m=''3067760''>fields,</span> <span m=''3068150''>because</span> <span m=''3068420''>we</span>
  <span m=''3068530''>took</span> <span m=''3068730''>away</span> <span m=''3068950''>those</span>
  <span m=''3069250''>pointers</span> <span m=''3069710''>because</span> <span m=''3069890''>we''re</span>
  <span m=''3070020''>going</span> <span m=''3070150''>to</span> <span m=''3070200''>garbage</span>
  <span m=''3070460''>collect</span> <span m=''3070930''>that.</span> <span m=''3072050''>And</span>
  <span m=''3072410''>when</span> <span m=''3072610''>we</span> <span m=''3072720''>do</span>
  <span m=''3072930''>that,</span> <span m=''3073190''>it</span> <span m=''3073290''>turns</span>
  <span m=''3073530''>out</span> <span m=''3073680''>this</span> <span m=''3073870''>thing</span>
  <span m=''3074030''>turns</span> <span m=''3074310''>to</span> <span m=''3074380''>garbage,</span>
  <span m=''3074780''>as</span> <span m=''3074910''>well.</span> <span m=''3077310''>So</span>
  <span m=''3077580''>when</span> <span m=''3077750''>you</span> <span m=''3077850''>do</span>
  <span m=''3078000''>reference</span> <span m=''3078490''>counting,</span> <span
  m=''3079340''>you</span> <span m=''3079400''>have</span> <span m=''3079580''>to</span>
  <span m=''3079760''>make</span> <span m=''3079960''>sure</span> <span m=''3080250''>that</span>
  <span m=''3081990''>when</span> <span m=''3082170''>you</span> <span m=''3082280''>decrement</span>
  <span m=''3082860''>things</span> <span m=''3083170''>and decide</span> <span m=''3083580''>you''re
  going to</span> <span m=''3083720''>free</span> <span m=''3083940''>something,</span>
  <span m=''3084270''>you</span> <span m=''3084430''>also</span> <span m=''3084720''>then</span>
  <span m=''3084920''>go</span> <span m=''3085060''>through</span> <span m=''3085470''>and</span>
  <span m=''3085590''>free</span> <span m=''3086620''>the</span> <span m=''3086740''>things,</span>
  <span m=''3087120''>and</span> <span m=''3087190''>you</span> <span m=''3087300''>continue</span>
  <span m=''3087760''>that</span> <span m=''3088000''>process</span> <span m=''3088470''>until</span>
  <span m=''3088800''>everything</span> <span m=''3089250''>that</span> <span m=''3089380''>has</span>
  <span m=''3089560''>been</span> <span m=''3092610''>deallocated</span> <span m=''3094130''>can</span>
  <span m=''3094350''>be</span> <span m=''3094470''>deallocated.</span> <span m=''3095880''>And</span>
  <span m=''3096050''>then</span> <span m=''3096190''>this</span> <span m=''3096350''>becomes</span>
  <span m=''3097090''>recyclable,</span> <span m=''3098410''>put</span> <span m=''3098600''>back</span>
  <span m=''3098900''>into</span> <span m=''3099240''>the</span> <span m=''3099340''>storage,</span>
  <span m=''3100710''>into</span> <span m=''3100970''>your</span> <span m=''3101090''>free</span>
  <span m=''3101320''>list</span> <span m=''3101620''>or</span> <span m=''3101680''>whatever</span>
  <span m=''3102420''>scheme</span> <span m=''3102790''>you have.</span> </p><p><span
  m=''3103310''>So</span> <span m=''3103470''>this</span> <span m=''3103630''>is</span>
  <span m=''3103730''>a</span> <span m=''3103790''>very</span> <span m=''3104180''>simple</span>
  <span m=''3104540''>way,</span> <span m=''3107280''>when</span> <span m=''3107420''>you''re</span>
  <span m=''3107510''>implementing</span> <span m=''3107890''>data</span> <span m=''3108130''>structures,</span>
  <span m=''3108500''>of</span> <span m=''3108560''>building</span> <span m=''3108840''>your</span>
  <span m=''3109020''>own</span> <span m=''3109120''>dynamic</span> <span m=''3109590''>storage.</span>
  <span m=''3110070''>Because</span> <span m=''3110790''>you</span> <span m=''3110970''>basically</span>
  <span m=''3111470''>can</span> <span m=''3111640''>allocate</span> <span m=''3112070''>stuff,</span>
  <span m=''3112370''>you</span> <span m=''3112520''>can</span> <span m=''3112660''>free</span>
  <span m=''3112930''>it,</span> <span m=''3114080''>and</span> <span m=''3114500''>whenever</span>
  <span m=''3115880''>the</span> <span m=''3116070''>reference</span> <span m=''3116440''>count</span>
  <span m=''3116700''>goes</span> <span m=''3116940''>to</span> <span m=''3117040''>0,</span>
  <span m=''3117420''>boom.</span> <span m=''3118230''>You</span> <span m=''3118350''>just</span>
  <span m=''3118570''>have</span> <span m=''3118780''>it</span> <span m=''3120140''>deallocated.</span>
  <span m=''3121890''>OK?</span> <span m=''3122480''>But</span> <span m=''3122630''>you</span>
  <span m=''3123405''>can</span> <span m=''3123780''>program</span> <span m=''3124130''>that</span>
  <span m=''3124320''>yourself</span> <span m=''3124680''>[INAUDIBLE].</span> </p><p><span
  m=''3125590''>Now</span> <span m=''3125690''>there''s</span> <span m=''3125820''>a</span>
  <span m=''3125870''>problem</span> <span m=''3126340''>with</span> <span m=''3126430''>the</span>
  <span m=''3126510''>scheme,</span> <span m=''3126870''>though.</span> <span m=''3127170''>What''s</span>
  <span m=''3127350''>the</span> <span m=''3127520''>problem?</span> <span m=''3129710''>Cycles.</span>
  <span m=''3131170''>Yeah,</span> <span m=''3131470''>cycles</span> <span m=''3131880''>are</span>
  <span m=''3131950''>the</span> <span m=''3132040''>problem</span> <span m=''3132560''>for</span>
  <span m=''3132750''>reference</span> <span m=''3133200''>counting.</span> <span
  m=''3134090''>So</span> <span m=''3134210''>here''s</span> <span m=''3134500''>an</span>
  <span m=''3134570''>example.</span> <span m=''3136040''>The</span> <span m=''3136130''>problem</span>
  <span m=''3136450''>is</span> <span m=''3136550''>that</span> <span m=''3136630''>a</span>
  <span m=''3136700''>cycle</span> <span m=''3137150''>is</span> <span m=''3137280''>never</span>
  <span m=''3137550''>garbage</span> <span m=''3137980''>collected.</span> <span m=''3138890''>Let''s</span>
  <span m=''3139090''>take</span> <span m=''3139310''>a</span> <span m=''3139370''>look</span>
  <span m=''3139600''>at</span> <span m=''3139710''>this</span> <span m=''3139810''>structure</span>
  <span m=''3140340''>here.</span> <span m=''3142030''>So</span> <span m=''3142430''>everybody''s</span>
  <span m=''3143040''>got</span> <span m=''3143200''>a</span> <span m=''3143250''>pointer</span>
  <span m=''3143660''>from</span> <span m=''3143890''>somewhere,</span> <span m=''3145100''>but</span>
  <span m=''3145210''>it</span> <span m=''3145310''>turns</span> <span m=''3145640''>out</span>
  <span m=''3145990''>that</span> <span m=''3146130''>there''s</span> <span m=''3146340''>a</span>
  <span m=''3146400''>cycle</span> <span m=''3146910''>here</span> <span m=''3152220''>where,</span>
  <span m=''3153150''>notice</span> <span m=''3153520''>that</span> <span m=''3153660''>they</span>
  <span m=''3153790''>are</span> <span m=''3153950''>pointing</span> <span m=''3154300''>to</span>
  <span m=''3154350''>each</span> <span m=''3154620''>other,</span> <span m=''3154800''>we
  even</span> <span m=''3155070''>have</span> <span m=''3155190''>a</span> <span m=''3155240''>guy</span>
  <span m=''3155460''>coming</span> <span m=''3155750''>off</span> <span m=''3156040''>here,</span>
  <span m=''3156230''>but</span> <span m=''3156440''>nothing</span> <span m=''3156880''>points</span>
  <span m=''3157270''>into</span> <span m=''3157490''>the</span> <span m=''3157600''>cycle.</span>
  </p><p><span m=''3159870''>So</span> <span m=''3160030''>there''s</span> <span m=''3160230''>no</span>
  <span m=''3160470''>way</span> <span m=''3160730''>that,</span> <span m=''3160920''>from</span>
  <span m=''3161070''>the</span> <span m=''3161160''>roots,</span> <span m=''3161540''>I</span>
  <span m=''3161620''>can</span> <span m=''3161800''>ever</span> <span m=''3162140''>access</span>
  <span m=''3162760''>these</span> <span m=''3163000''>four</span> <span m=''3163270''>guys.</span>
  <span m=''3164980''>They''re</span> <span m=''3165140''>garbage,</span> <span m=''3166310''>but
  my</span> <span m=''3166570''>reference</span> <span m=''3167000''>counting</span>
  <span m=''3167330''>scheme</span> <span m=''3167660''>will</span> <span m=''3167790''>never</span>
  <span m=''3168080''>find</span> <span m=''3168540''>it,</span> <span m=''3171450''>because</span>
  <span m=''3172840''>no</span> <span m=''3173080''>one''s</span> <span m=''3173330''>ever</span>
  <span m=''3173590''>going</span> <span m=''3173800''>to</span> <span m=''3174000''>decrement</span>
  <span m=''3175220''>one</span> <span m=''3175420''>of</span> <span m=''3175500''>those</span>
  <span m=''3176400''>counters</span> <span m=''3176770''>here.</span> <span m=''3177810''>So</span>
  <span m=''3178010''>those</span> <span m=''3178220''>are</span> <span m=''3178320''>all</span>
  <span m=''3178520''>garbage,</span> <span m=''3179690''>but</span> <span m=''3179900''>how</span>
  <span m=''3180230''>would</span> <span m=''3180380''>I</span> <span m=''3180440''>know?</span>
  <span m=''3181060''>And</span> <span m=''3181520''>that''s</span> <span m=''3181790''>basically</span>
  <span m=''3182310''>the</span> <span m=''3182610''>disadvantage</span> <span m=''3183550''>of</span>
  <span m=''3185920''>reference</span> <span m=''3186560''>counting.</span> <span
  m=''3188420''>And</span> <span m=''3189620''>uncollected</span> <span m=''3190170''>garbage,</span>
  <span m=''3190590''>as</span> <span m=''3190720''>we</span> <span m=''3190850''>all</span>
  <span m=''3191020''>know,</span> <span m=''3191170''>stinks.</span> <span m=''3193860''>So</span>
  <span m=''3194380''>we</span> <span m=''3194820''>don''t</span> <span m=''3195070''>want</span>
  <span m=''3195300''>that</span> <span m=''3195500''>situation</span> <span m=''3196030''>to</span>
  <span m=''3196150''>occur.</span> </p><p><span m=''3197630''>So</span> <span m=''3197950''>nevertheless,</span>
  <span m=''3198520''>reference</span> <span m=''3198850''>counting</span> <span m=''3200580''>is</span>
  <span m=''3200790''>great</span> <span m=''3201190''>if</span> <span m=''3201650''>you''ve</span>
  <span m=''3201860''>got</span> <span m=''3202220''>an acyclic</span> <span m=''3202740''>structure.</span>
  <span m=''3204650''>And</span> <span m=''3205680''>the</span> <span m=''3205770''>number</span>
  <span m=''3206090''>of</span> <span m=''3206170''>times</span> <span m=''3206490''>acyclic</span>
  <span m=''3206980''>structures</span> <span m=''3207480''>come</span> <span m=''3207680''>up</span>
  <span m=''3208070''>where</span> <span m=''3208310''>reference</span> <span m=''3208690''>counting</span>
  <span m=''3209000''>is</span> <span m=''3209130''>the</span> <span m=''3209200''>simple</span>
  <span m=''3209580''>and</span> <span m=''3209700''>easy</span> <span m=''3209990''>way</span>
  <span m=''3210340''>to</span> <span m=''3210480''>do</span> <span m=''3210830''>the</span>
  <span m=''3211390''>storage</span> <span m=''3211740''>management</span> <span m=''3212690''>is</span>
  <span m=''3212860''>huge</span> <span m=''3213360''>when</span> <span m=''3213510''>you</span>
  <span m=''3213610''>get</span> <span m=''3213810''>into</span> <span m=''3214330''>doing</span>
  <span m=''3215320''>any</span> <span m=''3215540''>kind</span> <span m=''3215750''>of</span>
  <span m=''3215820''>interesting</span> <span m=''3216230''>programming.</span> <span
  m=''3217530''>Lots</span> <span m=''3217890''>and</span> <span m=''3217960''>lots</span>
  <span m=''3218230''>of</span> <span m=''3218320''>opportunity</span> <span m=''3218930''>to</span>
  <span m=''3218980''>use</span> <span m=''3219220''>reference</span> <span m=''3219670''>counting</span>
  <span m=''3219930''>approach.</span> <span m=''3221840''>So</span> <span m=''3222040''>questions</span>
  <span m=''3222420''>about</span> <span m=''3222630''>reference</span> <span m=''3222970''>counting?</span>
  <span m=''3227230''>You have a</span> <span m=''3227830''>question?</span> <span
  m=''3228130''>Yeah?</span> </p><p><span m=''3228809''>AUDIENCE: So</span> <span
  m=''3229288''>this</span> <span m=''3229383''>means</span> <span m=''3229479''>you</span>
  <span m=''3229575''>actually</span> <span m=''3229671''>have</span> <span m=''3229767''>to</span>
  <span m=''3229926''>do</span> <span m=''3230086''>this</span> <span m=''3230246''>[UNINTELLIGIBLE]</span>
  <span m=''3231683''>ever</span> <span m=''3232162''>do a</span> <span m=''3232641''>[INAUDIBLE]?</span>
  <span m=''3233120''>You</span> <span m=''3233599''>can, like,</span> <span m=''3234078''>save
  the work--</span> </p><p><span m=''3235040''>CHARLES LEISERSON: That''s</span> <span
  m=''3235330''>right.</span> <span m=''3235650''>Whenever</span> <span m=''3236110''>you</span>
  <span m=''3236470''>move</span> <span m=''3236720''>a</span> <span m=''3236780''>pointer,</span>
  <span m=''3237480''>if</span> <span m=''3237920''>you''re</span> <span m=''3238010''>going</span>
  <span m=''3238110''>to</span> <span m=''3238150''>move</span> <span m=''3238290''>a</span>
  <span m=''3238380''>pointer,</span> <span m=''3238760''>you</span> <span m=''3238910''>first</span>
  <span m=''3239310''>decrement</span> <span m=''3240340''>the</span> <span m=''3240980''>counter</span>
  <span m=''3241530''>on</span> <span m=''3241640''>the</span> <span m=''3241720''>place</span>
  <span m=''3242180''>you''re</span> <span m=''3242290''>moving</span> <span m=''3242610''>it</span>
  <span m=''3242720''>from,</span> <span m=''3243250''>and</span> <span m=''3243480''>then</span>
  <span m=''3243770''>garbage</span> <span m=''3244160''>collect</span> <span m=''3244430''>if</span>
  <span m=''3244570''>need</span> <span m=''3244820''>be,</span> <span m=''3245430''>and</span>
  <span m=''3245650''>then</span> <span m=''3245880''>you</span> <span m=''3246700''>move</span>
  <span m=''3246980''>the</span> <span m=''3247060''>pointer--</span> <span m=''3247740''>that''s</span>
  <span m=''3247840''>typically</span> <span m=''3248190''>what</span> <span m=''3248370''>you</span>
  <span m=''3248480''>do--</span> <span m=''3248810''>you</span> <span m=''3248960''>move</span>
  <span m=''3249210''>the</span> <span m=''3249300''>pointer</span> <span m=''3249790''>and</span>
  <span m=''3249930''>increment</span> <span m=''3250590''>the</span> <span m=''3251540''>count</span>
  <span m=''3251950''>at</span> <span m=''3252110''>that</span> <span m=''3252470''>location,</span>
  <span m=''3253900''>which</span> <span m=''3256040''>typically</span> <span m=''3256390''>doesn''t</span>
  <span m=''3256650''>require</span> <span m=''3256990''>any</span> <span m=''3257230''>extra</span>
  <span m=''3257500''>work</span> <span m=''3257810''>to</span> <span m=''3258910''>decrement,</span>
  <span m=''3259420''>which</span> <span m=''3259610''>is</span> <span m=''3259710''>the</span>
  <span m=''3259790''>trick</span> <span m=''3259960''>thing.</span> <span m=''3260680''>Sorry?</span>
  </p><p><span m=''3260960''>AUDIENCE: There''s</span> <span m=''3261240''>no</span>
  <span m=''3261363''>good</span> <span m=''3261487''>way</span> <span m=''3261610''>to</span>
  <span m=''3261734''>do</span> <span m=''3261898''>this</span> <span m=''3262063''>in</span>
  <span m=''3262228''>idle time.</span> <span m=''3262722''>Like</span> <span m=''3263216''>I''ll</span>
  <span m=''3263710''>have some</span> <span m=''3264204''>idle time</span> <span
  m=''3264698''>later,</span> <span m=''3265192''>let me do it--</span> </p><p><span
  m=''3266180''>CHARLES LEISERSON: So</span> <span m=''3266340''>that''s</span> <span
  m=''3266590''>what</span> <span m=''3266740''>you</span> <span m=''3266860''>use</span>
  <span m=''3267930''>true</span> <span m=''3268160''>garbage</span> <span m=''3268520''>collection</span>
  <span m=''3268930''>for</span> <span m=''3270220''>Yeah?</span> </p><p><span m=''3273790''>AUDIENCE:
  You</span> <span m=''3273920''>could</span> <span m=''3274010''>actually,</span>
  <span m=''3274400''>there''s</span> <span m=''3274580''>techniques</span> <span
  m=''3274950''>where you can</span> <span m=''3275690''>defer</span> <span m=''3276410''>the</span>
  <span m=''3276580''>work</span> <span m=''3277050''>of</span> <span m=''3278210''>incrementing</span>
  <span m=''3278330''>it.</span> <span m=''3278680''>Like</span> <span m=''3278830''>you</span>
  <span m=''3278890''>basically</span> <span m=''3279190''>put</span> <span m=''3279430''>the</span>
  <span m=''3279590''>increment and</span> <span m=''3280070''>decrement</span> <span
  m=''3280390''>operations</span> <span m=''3280850''>that</span> <span m=''3280950''>you''d</span>
  <span m=''3281110''>like</span> <span m=''3281290''>to</span> <span m=''3281370''>do</span>
  <span m=''3281630''>into</span> <span m=''3281900''>a</span> <span m=''3281960''>buffer,</span>
  <span m=''3282740''>and</span> <span m=''3282850''>then</span> <span m=''3282950''>you</span>
  <span m=''3283040''>can</span> <span m=''3283190''>do</span> <span m=''3283310''>them</span>
  <span m=''3283450''>later.</span> <span m=''3284100''>But</span> <span m=''3284310''>it''s</span>
  <span m=''3284480''>sort</span> <span m=''3284680''>of</span> <span m=''3285810''>the
  same.</span> </p><p><span m=''3286230''>CHARLES LEISERSON: Yeah, you</span> <span
  m=''3286650''>could</span> <span m=''3286780''>log.</span> <span m=''3287610''>So</span>
  <span m=''3287790''>there</span> <span m=''3287960''>are</span> <span m=''3288040''>schemes</span>
  <span m=''3288390''>where</span> <span m=''3288500''>you</span> <span m=''3288640''>log</span>
  <span m=''3289220''>that,</span> <span m=''3289540''>oh,</span> <span m=''3289720''>I</span>
  <span m=''3289800''>decremented</span> <span m=''3290350''>this,</span> <span m=''3290520''>better</span>
  <span m=''3290720''>check</span> <span m=''3290960''>it</span> <span m=''3291030''>later,</span>
  <span m=''3292070''>type</span> <span m=''3292310''>thing.</span> <span m=''3292590''>Or</span>
  <span m=''3292870''>I</span> <span m=''3293210''>decrement</span> <span m=''3293640''>it</span>
  <span m=''3293780''>to</span> <span m=''3293880''>0.</span> <span m=''3294260''>Let</span>
  <span m=''3294430''>me</span> <span m=''3294520''>just</span> <span m=''3295140''>put</span>
  <span m=''3295300''>it</span> <span m=''3295400''>in</span> <span m=''3295530''>there,</span>
  <span m=''3295800''>and</span> <span m=''3295860''>I''ll</span> <span m=''3296020''>go</span>
  <span m=''3296400''>actually</span> <span m=''3296820''>do</span> <span m=''3297080''>the</span>
  <span m=''3297550''>stuff</span> <span m=''3297840''>in</span> <span m=''3297950''>batch</span>
  <span m=''3298270''>mode</span> <span m=''3298500''>at</span> <span m=''3298630''>some</span>
  <span m=''3298780''>later</span> <span m=''3299010''>time.</span> <span m=''3300460''>Yep.</span>
  <span m=''3301150''>So</span> <span m=''3302430''>programming</span> <span m=''3302820''>is</span>
  <span m=''3303000''>fun,</span> <span m=''3303270''>because</span> <span m=''3303480''>you
  can</span> <span m=''3303550''>be</span> <span m=''3303660''>clever</span> <span
  m=''3304720''>with</span> <span m=''3305080''>schemes</span> <span m=''3305430''>like</span>
  <span m=''3305610''>that.</span> <span m=''3307020''>And</span> <span m=''3307240''>that</span>
  <span m=''3307400''>could</span> <span m=''3307520''>be</span> <span m=''3307650''>quite</span>
  <span m=''3307920''>a</span> <span m=''3308370''>reasonable</span> <span m=''3308720''>thing</span>
  <span m=''3308930''>to</span> <span m=''3309010''>do,</span> <span m=''3309220''>which</span>
  <span m=''3309430''>is</span> <span m=''3310090''>wait</span> <span m=''3310330''>until</span>
  <span m=''3310740''>you''re</span> <span m=''3310900''>waiting</span> <span m=''3311230''>on</span>
  <span m=''3311330''>the</span> <span m=''3311410''>user</span> <span m=''3311740''>for</span>
  <span m=''3311890''>input,</span> <span m=''3313190''>and at</span> <span m=''3313370''>that</span>
  <span m=''3313600''>point,</span> <span m=''3313850''>collect your</span> <span
  m=''3314270''>garbage.</span> </p><p><span m=''3314730''>Now,</span> <span m=''3314840''>the</span>
  <span m=''3315130''>thing</span> <span m=''3315380''>you have to</span> <span m=''3315630''>risk</span>
  <span m=''3316620''>is,</span> <span m=''3317100''>what</span> <span m=''3317270''>happens</span>
  <span m=''3317650''>if</span> <span m=''3317760''>that</span> <span m=''3317970''>takes</span>
  <span m=''3318190''>a</span> <span m=''3318240''>long</span> <span m=''3318510''>time</span>
  <span m=''3318770''>to</span> <span m=''3318840''>get</span> <span m=''3319090''>there?</span>
  <span m=''3320690''>And</span> <span m=''3320910''>then</span> <span m=''3321480''>there''s</span>
  <span m=''3321680''>the</span> <span m=''3321770''>complexity</span> <span m=''3322440''>of</span>
  <span m=''3322530''>your</span> <span m=''3326830''>algorithms</span> <span m=''3327350''>and</span>
  <span m=''3327420''>so</span> <span m=''3327600''>forth.</span> <span m=''3328060''>So</span>
  <span m=''3329060''>you</span> <span m=''3329230''>get</span> <span m=''3329360''>into</span>
  <span m=''3329560''>a</span> <span m=''3329600''>lot</span> <span m=''3329880''>of</span>
  <span m=''3329960''>issues</span> <span m=''3330340''>of</span> <span m=''3330410''>software</span>
  <span m=''3330820''>maintenance</span> <span m=''3331260''>and</span> <span m=''3331360''>so</span>
  <span m=''3331530''>forth.</span> <span m=''3332460''>But that</span> <span m=''3332650''>can</span>
  <span m=''3332740''>be</span> <span m=''3332880''>a</span> <span m=''3332930''>very</span>
  <span m=''3333220''>effective</span> <span m=''3334060''>thing,</span> <span m=''3334310''>is</span>
  <span m=''3334680''>take it</span> <span m=''3334990''>out</span> <span m=''3335190''>of</span>
  <span m=''3335250''>the</span> <span m=''3335340''>critical</span> <span m=''3335730''>path</span>
  <span m=''3336060''>of</span> <span m=''3336140''>the</span> <span m=''3336260''>actual</span>
  <span m=''3336510''>complication</span> <span m=''3337130''>you''re</span> <span
  m=''3337220''>doing,</span> <span m=''3337790''>if</span> <span m=''3337960''>that''s</span>
  <span m=''3338210''>mission</span> <span m=''3338540''>critical,</span> <span m=''3339480''>and</span>
  <span m=''3339730''>put</span> <span m=''3339890''>it</span> <span m=''3340030''>in</span>
  <span m=''3340170''>some</span> <span m=''3340390''>part</span> <span m=''3340590''>of
  the</span> <span m=''3340660''>computation</span> <span m=''3340925''>where</span>
  <span m=''3341057''>it</span> <span m=''3341190''>isn''t</span> <span m=''3341570''>mission</span>
  <span m=''3341840''>critical.</span> <span m=''3342490''>Very</span> <span m=''3342670''>good</span>
  <span m=''3342840''>idea.</span> </p><p><span m=''3346875''>I''m</span> <span m=''3347320''>sorry?</span>
  </p><p><span m=''3347730''>AUDIENCE: For thread safety.</span> <span m=''3351890''>Like</span>
  <span m=''3354140''>if</span> <span m=''3354440''>you</span> <span m=''3354510''>have</span>
  <span m=''3354610''>shared</span> <span m=''3354860''>reference</span> <span m=''3355210''>accounts,</span>
  <span m=''3355970''>like</span> <span m=''3356120''>multiple</span> <span m=''3356410''>threads</span>
  <span m=''3356710''>updating</span> <span m=''3357050''>the</span> <span m=''3357140''>counts,</span>
  <span m=''3357570''>you</span> <span m=''3357690''>don''t</span> <span m=''3357930''>want</span>
  <span m=''3358170''>to</span> <span m=''3358430''>have</span> <span m=''3358600''>them</span>
  <span m=''3358740''>all</span> <span m=''3359780''>in</span> <span m=''3360000''>the</span>
  <span m=''3360090''>same</span> <span m=''3360290''>count at the</span> <span m=''3360590''>same</span>
  <span m=''3360760''>time.</span> <span m=''3361370''>So</span> <span m=''3362100''>they</span>
  <span m=''3362320''>fill it</span> <span m=''3362570''>like</span> <span m=''3362720''>a</span>
  <span m=''3362770''>thread</span> <span m=''3363010''>local</span> <span m=''3363240''>buffer,</span>
  <span m=''3363800''>and--</span> </p><p><span m=''3364160''>CHARLES LEISERSON: I
  see what you''re</span> <span m=''3364540''>saying.</span> <span m=''3364670''>Yes.</span>
  <span m=''3365230''>So</span> <span m=''3365410''>we''re</span> <span m=''3365590''>going</span>
  <span m=''3365690''>to</span> <span m=''3365730''>get</span> <span m=''3365890''>into</span>
  <span m=''3366090''>that</span> <span m=''3366300''>as</span> <span m=''3366410''>we</span>
  <span m=''3366530''>deal</span> <span m=''3366820''>with</span> <span m=''3366970''>multi-threading</span>
  <span m=''3367640''>and</span> <span m=''3367730''>so</span> <span m=''3367900''>forth,</span>
  <span m=''3368170''>that</span> <span m=''3369480''>if</span> <span m=''3369980''>you''ve</span>
  <span m=''3370080''>got</span> <span m=''3370290''>two</span> <span m=''3370440''>guys</span>
  <span m=''3370780''>that are</span> <span m=''3370980''>operating</span> <span m=''3371370''>on</span>
  <span m=''3371460''>the</span> <span m=''3371510''>same</span> <span m=''3371750''>data</span>
  <span m=''3372000''>structure,</span> <span m=''3372290''>you have to</span> <span
  m=''3372390''>be</span> <span m=''3372490''>very</span> <span m=''3373110''>careful</span>
  <span m=''3373440''>about</span> <span m=''3373650''>the</span> <span m=''3373730''>consistency,</span>
  <span m=''3374740''>and</span> <span m=''3374840''>that</span> <span m=''3374930''>one</span>
  <span m=''3375180''>doesn''t</span> <span m=''3375460''>do</span> <span m=''3375600''>something</span>
  <span m=''3375980''>while</span> <span m=''3376140''>the</span> <span m=''3376280''>other
  is</span> <span m=''3376690''>doing</span> <span m=''3376900''>something</span>
  <span m=''3377270''>else,</span> <span m=''3377500''>and</span> <span m=''3377610''>so</span>
  <span m=''3377760''>forth.</span> <span m=''3378310''>So</span> <span m=''3379240''>for</span>
  <span m=''3379340''>that</span> <span m=''3379550''>reason,</span> <span m=''3379780''>it</span>
  <span m=''3379870''>can</span> <span m=''3379990''>be</span> <span m=''3380150''>a</span>
  <span m=''3380190''>good</span> <span m=''3380390''>idea</span> <span m=''3380610''>to</span>
  <span m=''3380670''>postpone</span> <span m=''3381630''>operation.</span> </p><p><span
  m=''3385090''>So</span> <span m=''3386520''>general</span> <span m=''3387020''>garbage</span>
  <span m=''3387440''>collection</span> <span m=''3387860''>is</span> <span m=''3388000''>based</span>
  <span m=''3388460''>on</span> <span m=''3388720''>a</span> <span m=''3388770''>graph</span>
  <span m=''3389150''>abstraction.</span> <span m=''3389800''>So</span> <span m=''3389920''>let''s</span>
  <span m=''3390120''>move</span> <span m=''3390370''>into</span> <span m=''3390550''>the</span>
  <span m=''3390640''>graph</span> <span m=''3391050''>world.</span> <span m=''3393080''>So</span>
  <span m=''3393280''>I</span> <span m=''3393410''>can</span> <span m=''3393670''>view</span>
  <span m=''3394390''>objects</span> <span m=''3394900''>and</span> <span m=''3395050''>pointers</span>
  <span m=''3395740''>as</span> <span m=''3396020''>forming</span> <span m=''3396420''>a</span>
  <span m=''3396500''>directed</span> <span m=''3397040''>graph</span> <span m=''3397550''>G</span>
  <span m=''3397840''>equals</span> <span m=''3398170''>VE,</span> <span m=''3398680''>where</span>
  <span m=''3398850''>V are</span> <span m=''3399150''>the</span> <span m=''3399310''>objects</span>
  <span m=''3399850''>and</span> <span m=''3399980''>E</span> <span m=''3400260''>are</span>
  <span m=''3400310''>the</span> <span m=''3400480''>pointers</span> <span m=''3401320''>from</span>
  <span m=''3401520''>one</span> <span m=''3401710''>object</span> <span m=''3402080''>to</span>
  <span m=''3402220''>another.</span> <span m=''3405310''>The</span> <span m=''3405530''>live</span>
  <span m=''3405970''>objects</span> <span m=''3406380''>are</span> <span m=''3406470''>reachable</span>
  <span m=''3406910''>from</span> <span m=''3407120''>the</span> <span m=''3407200''>roots.</span>
  <span m=''3408560''>And</span> <span m=''3408710''>now</span> <span m=''3408840''>the</span>
  <span m=''3409480''>thing</span> <span m=''3409730''>is</span> <span m=''3409940''>that</span>
  <span m=''3410730''>finding</span> <span m=''3411330''>all</span> <span m=''3411780''>of</span>
  <span m=''3411900''>the</span> <span m=''3412700''>live</span> <span m=''3413080''>objects</span>
  <span m=''3413810''>is</span> <span m=''3414050''>then</span> <span m=''3415160''>like</span>
  <span m=''3415430''>doing</span> <span m=''3415690''>a</span> <span m=''3415760''>graph</span>
  <span m=''3416180''>search.</span> <span m=''3417270''>The</span> <span m=''3417420''>common</span>
  <span m=''3417800''>ways</span> <span m=''3418060''>of</span> <span m=''3418110''>doing
  a</span> <span m=''3418430''>graph</span> <span m=''3419120''>search</span> <span
  m=''3419560''>are</span> <span m=''3420200''>depth</span> <span m=''3420510''>for</span>
  <span m=''3420770''>search</span> <span m=''3421540''>and</span> <span m=''3421720''>breadth-first</span>
  <span m=''3422300''>search.</span> <span m=''3423080''>It</span> <span m=''3423210''>turns</span>
  <span m=''3423440''>out</span> <span m=''3423580''>we''re</span> <span m=''3423680''>going</span>
  <span m=''3423740''>to</span> <span m=''3423800''>use</span> <span m=''3424020''>breadth-first</span>
  <span m=''3424560''>search</span> <span m=''3425180''>for</span> <span m=''3425540''>reasons
  that</span> <span m=''3425970''>I''ll</span> <span m=''3426530''>show</span> <span
  m=''3426760''>you.</span> </p><p><span m=''3428660''>So</span> <span m=''3428960''>the</span>
  <span m=''3429100''>idea</span> <span m=''3429550''>in</span> <span m=''3429830''>breadth-first</span>
  <span m=''3430360''>search,</span> <span m=''3430630''>to</span> <span m=''3430740''>find</span>
  <span m=''3431140''>all</span> <span m=''3431400''>the</span> <span m=''3431550''>objects.</span>
  <span m=''3432140''>So</span> <span m=''3432250''>the</span> <span m=''3432380''>idea</span>
  <span m=''3432690''>is,</span> <span m=''3432810''>what</span> <span m=''3432970''>we''re</span>
  <span m=''3433080''>going</span> <span m=''3433170''>to</span> <span m=''3433260''>do</span>
  <span m=''3433480''>is</span> <span m=''3433710''>go</span> <span m=''3433900''>through</span>
  <span m=''3434520''>and</span> <span m=''3434740''>find,</span> <span m=''3435310''>where
  are</span> <span m=''3435750''>all</span> <span m=''3436000''>the</span> <span m=''3436140''>objects</span>
  <span m=''3436580''>in</span> <span m=''3436660''>my</span> <span m=''3436820''>system</span>
  <span m=''3438310''>that are</span> <span m=''3438520''>reachable</span> <span m=''3438990''>from</span>
  <span m=''3439100''>the</span> <span m=''3439210''>root?</span> <span m=''3439760''>And</span>
  <span m=''3439910''>then</span> <span m=''3440060''>anything</span> <span m=''3440560''>that</span>
  <span m=''3440680''>I</span> <span m=''3440850''>didn''t</span> <span m=''3441010''>find,</span>
  <span m=''3442120''>ah.</span> <span m=''3442590''>That</span> <span m=''3442780''>must</span>
  <span m=''3443020''>be</span> <span m=''3445020''>garbage.</span> </p><p><span m=''3447540''>So</span>
  <span m=''3447710''>here''s</span> <span m=''3447990''>the</span> <span m=''3448110''>idea.</span>
  <span m=''3448480''>What</span> <span m=''3448630''>we''re</span> <span m=''3448710''>going</span>
  <span m=''3448780''>to</span> <span m=''3448840''>use</span> <span m=''3449340''>is</span>
  <span m=''3449540''>FIFO</span> <span m=''3450230''>queue</span> <span m=''3451080''>called</span>
  <span m=''3451380''>Q.</span> <span m=''3453500''>So</span> <span m=''3454160''>that''s</span>
  <span m=''3454600''>a</span> <span m=''3454670''>first</span> <span m=''3455080''>in,</span>
  <span m=''3455260''>first</span> <span m=''3456110''>out.</span> <span m=''3456420''>It</span>
  <span m=''3456540''>has</span> <span m=''3456750''>a</span> <span m=''3456810''>head</span>
  <span m=''3457410''>and</span> <span m=''3457530''>a</span> <span m=''3457640''>tail.</span>
  <span m=''3459070''>And</span> <span m=''3459420''>the</span> <span m=''3459920''>mechanism</span>
  <span m=''3460510''>is</span> <span m=''3460630''>very</span> <span m=''3460820''>much</span>
  <span m=''3461050''>like</span> <span m=''3461250''>a</span> <span m=''3461310''>stack.</span>
  <span m=''3461840''>Whenever</span> <span m=''3462250''>I</span> <span m=''3462370''>need</span>
  <span m=''3462760''>to</span> <span m=''3462980''>enqueue</span> <span m=''3463460''>something,</span>
  <span m=''3464240''>I</span> <span m=''3464350''>put</span> <span m=''3464580''>it</span>
  <span m=''3464680''>on</span> <span m=''3464970''>the</span> <span m=''3465110''>tail</span>
  <span m=''3465490''>end</span> <span m=''3466630''>and</span> <span m=''3466810''>increment</span>
  <span m=''3467090''>the</span> <span m=''3467370''>tail</span> <span m=''3467660''>pointer.</span>
  <span m=''3468000''>Whenever</span> <span m=''3468380''>I</span> <span m=''3468460''>need</span>
  <span m=''3468710''>to</span> <span m=''3469220''>take</span> <span m=''3469450''>something</span>
  <span m=''3469720''>off</span> <span m=''3470000''>the</span> <span m=''3470110''>queue,
  I</span> <span m=''3470560''>increment</span> <span m=''3471030''>the</span> <span
  m=''3471190''>head</span> <span m=''3471340''>pointer.</span> <span m=''3474290''>So</span>
  <span m=''3474460''>I''m</span> <span m=''3474590''>always</span> <span m=''3474830''>doing</span>
  <span m=''3475030''>head and</span> <span m=''3475430''>tail,</span> <span m=''3477770''>pushing</span>
  <span m=''3478110''>on</span> <span m=''3478270''>the</span> <span m=''3478980''>tail</span>
  <span m=''3479460''>and</span> <span m=''3479800''>pulling</span> <span m=''3480110''>off</span>
  <span m=''3480360''>the</span> <span m=''3480440''>head.</span> <span m=''3481380''>Enqueue</span>
  <span m=''3481750''>and</span> <span m=''3481910''>dequeue.</span> </p><p><span
  m=''3483010''>So</span> <span m=''3483150''>the</span> <span m=''3483220''>way</span>
  <span m=''3483470''>that</span> <span m=''3484500''>this</span> <span m=''3484700''>works</span>
  <span m=''3485100''>is,</span> <span m=''3485490''>I</span> <span m=''3485660''>basically</span>
  <span m=''3486210''>go</span> <span m=''3486420''>through</span> <span m=''3486730''>all</span>
  <span m=''3487110''>my</span> <span m=''3487340''>objects,</span> <span m=''3489520''>and</span>
  <span m=''3489690''>if</span> <span m=''3489800''>they''re</span> <span m=''3490060''>a
  route,</span> <span m=''3490790''>I</span> <span m=''3490930''>put</span> <span
  m=''3491160''>a</span> <span m=''3491210''>mark</span> <span m=''3491590''>on</span>
  <span m=''3491960''>it.</span> <span m=''3493000''>And</span> <span m=''3493240''>I</span>
  <span m=''3493320''>enqueue--</span> <span m=''3495120''>this is</span> <span m=''3495380''>pseudocode,</span>
  <span m=''3495940''>by</span> <span m=''3496090''>the</span> <span m=''3496180''>way,</span>
  <span m=''3496320''>so</span> <span m=''3496450''>don''t</span> <span m=''3496610''>hold</span>
  <span m=''3496830''>me</span> <span m=''3496960''>to</span> <span m=''3497110''>my</span>
  <span m=''3498080''>C</span> <span m=''3498320''>programming</span> <span m=''3498720''>standard</span>
  <span m=''3499130''>here.</span> <span m=''3500580''>And</span> <span m=''3501220''>I</span>
  <span m=''3501330''>market,</span> <span m=''3501880''>and</span> <span m=''3502050''>then</span>
  <span m=''3502190''>I</span> <span m=''3502290''>enqueue</span> <span m=''3502660''>it</span>
  <span m=''3502820''>on</span> <span m=''3503260''>the</span> <span m=''3503970''>queue</span>
  <span m=''3504466''>Q.</span> <span m=''3506450''>And</span> <span m=''3506600''>otherwise,</span>
  <span m=''3507240''>I</span> <span m=''3507330''>just</span> <span m=''3507490''>simply</span>
  <span m=''3507760''>mark</span> <span m=''3508110''>it</span> <span m=''3508300''>as</span>
  <span m=''3508900''>zero.</span> </p><p><span m=''3509320''>So</span> <span m=''3509520''>being</span>
  <span m=''3509910''>marked</span> <span m=''3510340''>means</span> <span m=''3511830''>whether</span>
  <span m=''3512200''>we''ve</span> <span m=''3512370''>discovered</span> <span m=''3512900''>it''s</span>
  <span m=''3513030''>reachable</span> <span m=''3513490''>from</span> <span m=''3513670''>a</span>
  <span m=''3513740''>route.</span> <span m=''3514740''>So</span> <span m=''3514890''>to</span>
  <span m=''3514980''>begin</span> <span m=''3515330''>with,</span> <span m=''3515550''>what</span>
  <span m=''3515710''>we''re</span> <span m=''3515810''>going</span> <span m=''3515910''>to</span>
  <span m=''3516000''>do</span> <span m=''3516430''>is</span> <span m=''3516780''>mark</span>
  <span m=''3517220''>everything</span> <span m=''3517660''>that''s</span> <span m=''3517820''>reachable</span>
  <span m=''3518260''>from</span> <span m=''3518470''>the</span> <span m=''3518550''>routes,</span>
  <span m=''3521010''>and</span> <span m=''3521470''>we''re</span> <span m=''3521640''>going</span>
  <span m=''3521820''>to</span> <span m=''3522000''>enqueue</span> <span m=''3522130''>them</span>
  <span m=''3522310''>on</span> <span m=''3522460''>the</span> <span m=''3522520''>FIFO.</span>
  <span m=''3524870''>And</span> <span m=''3525050''>everything</span> <span m=''3525480''>else,</span>
  <span m=''3525670''>we''re</span> <span m=''3525760''>going</span> <span m=''3525830''>to</span>
  <span m=''3525890''>mark as</span> <span m=''3526320''>unreachable,</span> <span
  m=''3527620''>for</span> <span m=''3527770''>now.</span> <span m=''3528550''>And</span>
  <span m=''3528670''>now what</span> <span m=''3528820''>we''re</span> <span m=''3528980''>going</span>
  <span m=''3529060''>to</span> <span m=''3529410''>do</span> <span m=''3529540''>is</span>
  <span m=''3529600''>see</span> <span m=''3529810''>which</span> <span m=''3529990''>ones</span>
  <span m=''3530240''>we</span> <span m=''3530360''>discover.</span> </p><p><span
  m=''3531450''>So what</span> <span m=''3531630''>we</span> <span m=''3531800''>do</span>
  <span m=''3532020''>is,</span> <span m=''3532200''>while</span> <span m=''3532860''>the</span>
  <span m=''3532970''>queue</span> <span m=''3534980''>is</span> <span m=''3535160''>non-empty,</span>
  <span m=''3536800''>we''re</span> <span m=''3536930''>going</span> <span m=''3537230''>to</span>
  <span m=''3537540''>take</span> <span m=''3537950''>something</span> <span m=''3538290''>off</span>
  <span m=''3538600''>of</span> <span m=''3538710''>the</span> <span m=''3538810''>queue</span>
  <span m=''3540080''>and</span> <span m=''3540250''>then</span> <span m=''3540400''>look</span>
  <span m=''3540710''>at</span> <span m=''3540790''>all</span> <span m=''3541030''>of</span>
  <span m=''3541120''>its</span> <span m=''3541290''>neighbors.</span> <span m=''3542520''>So</span>
  <span m=''3542760''>all</span> <span m=''3543120''>the</span> <span m=''3543280''>edges</span>
  <span m=''3543590''>UV,</span> <span m=''3544500''>look</span> <span m=''3544670''>at</span>
  <span m=''3544730''>all</span> <span m=''3545030''>the</span> <span m=''3545520''>things</span>
  <span m=''3545850''>that</span> <span m=''3546230''>go</span> <span m=''3546470''>from</span>
  <span m=''3546820''>U to</span> <span m=''3546960''>V</span> <span m=''3548440''>And</span>
  <span m=''3548910''>if</span> <span m=''3549070''>it''s</span> <span m=''3549230''>not</span>
  <span m=''3549540''>marked,</span> <span m=''3550420''>then</span> <span m=''3550570''>we''re</span>
  <span m=''3550690''>going</span> <span m=''3550790''>to</span> <span m=''3550830''>mark
  it</span> <span m=''3551440''>and</span> <span m=''3551600''>put</span> <span m=''3551760''>it</span>
  <span m=''3551840''>on</span> <span m=''3551980''>the</span> <span m=''3552070''>queue.</span>
  <span m=''3553340''>That''s</span> <span m=''3553550''>it.</span> <span m=''3555800''>If
  it''s</span> <span m=''3555960''>already</span> <span m=''3556190''>marked,</span>
  <span m=''3556490''>we</span> <span m=''3556600''>don''t</span> <span m=''3556750''>have</span>
  <span m=''3556870''>to</span> <span m=''3556950''>do</span> <span m=''3557090''>anything</span>
  <span m=''3557390''>with</span> <span m=''3557530''>it,</span> <span m=''3557700''>but</span>
  <span m=''3557880''>if it''s</span> <span m=''3557980''>unmarked,</span> <span m=''3558280''>we''ll</span>
  <span m=''3558580''>mark it</span> <span m=''3559280''>and</span> <span m=''3559440''>do</span>
  <span m=''3559550''>it.</span> <span m=''3559960''>And</span> <span m=''3560110''>then</span>
  <span m=''3560260''>in</span> <span m=''3560370''>the</span> <span m=''3560740''>end,</span>
  <span m=''3561560''>everything</span> <span m=''3562040''>that''s</span> <span m=''3562230''>marked</span>
  <span m=''3563690''>is</span> <span m=''3563910''>going</span> <span m=''3564040''>to</span>
  <span m=''3564110''>be</span> <span m=''3564860''>something</span> <span m=''3565320''>that</span>
  <span m=''3565640''>is</span> <span m=''3566740''>live,</span> <span m=''3567300''>and</span>
  <span m=''3567430''>everything</span> <span m=''3568250''>that</span> <span m=''3568540''>is</span>
  <span m=''3569040''>unmarked</span> <span m=''3569630''>is</span> <span m=''3569780''>going</span>
  <span m=''3569910''>to</span> <span m=''3569960''>be</span> <span m=''3570180''>things</span>
  <span m=''3570520''>that</span> <span m=''3570630''>are</span> <span m=''3570710''>dead.</span>
  <span m=''3572110''>But</span> <span m=''3572250''>it''s</span> <span m=''3572380''>going</span>
  <span m=''3572470''>to</span> <span m=''3572520''>be</span> <span m=''3572650''>actually</span>
  <span m=''3573020''>even</span> <span m=''3574270''>sexier</span> <span m=''3574890''>and</span>
  <span m=''3574960''>more</span> <span m=''3575160''>clever</span> <span m=''3575480''>than</span>
  <span m=''3575630''>that,</span> <span m=''3576610''>as you''ll</span> <span m=''3576740''>see.</span>
  </p><p><span m=''3577930''>So</span> <span m=''3577950''>here''s</span> <span m=''3578200''>an</span>
  <span m=''3578260''>example.</span> <span m=''3580520''>We</span> <span m=''3580600''>start</span>
  <span m=''3580890''>out</span> <span m=''3581120''>with</span> <span m=''3581230''>my</span>
  <span m=''3581350''>queue</span> <span m=''3581620''>being</span> <span m=''3581870''>empty,</span>
  <span m=''3582220''>with</span> <span m=''3582360''>head</span> <span m=''3582800''>and</span>
  <span m=''3583030''>tail</span> <span m=''3583310''>pointing</span> <span m=''3583630''>to</span>
  <span m=''3583710''>the</span> <span m=''3583770''>same</span> <span m=''3584070''>place.</span>
  <span m=''3584570''>And</span> <span m=''3584980''>what</span> <span m=''3585160''>we</span>
  <span m=''3585250''>do,</span> <span m=''3585460''>is</span> <span m=''3585560''>we</span>
  <span m=''3585690''>go</span> <span m=''3585900''>through</span> <span m=''3586240''>and</span>
  <span m=''3586330''>we</span> <span m=''3586460''>first--</span> <span m=''3586800''>in</span>
  <span m=''3586840''>this</span> <span m=''3587000''>case,</span> <span m=''3587210''>I
  have</span> <span m=''3587330''>just</span> <span m=''3587630''>one</span> <span
  m=''3587870''>route</span> <span m=''3588200''>R,</span> <span m=''3589070''>right</span>
  <span m=''3589220''>here.</span> <span m=''3590360''>So</span> <span m=''3590470''>we</span>
  <span m=''3590540''>basically</span> <span m=''3592180''>mark</span> <span m=''3592600''>R</span>
  <span m=''3592930''>and</span> <span m=''3593100''>put</span> <span m=''3593250''>it</span>
  <span m=''3593370''>on,</span> <span m=''3593670''>and</span> <span m=''3593780''>that''s</span>
  <span m=''3593980''>how</span> <span m=''3594110''>we</span> <span m=''3594200''>get</span>
  <span m=''3594370''>started.</span> <span m=''3594790''>And</span> <span m=''3594960''>everything</span>
  <span m=''3595380''>else</span> <span m=''3595600''>is</span> <span m=''3595720''>unmarked</span>
  <span m=''3596670''>up</span> <span m=''3596820''>here.</span> <span m=''3597640''>So</span>
  <span m=''3597790''>I''m</span> <span m=''3597890''>going</span> <span m=''3597980''>to</span>
  <span m=''3598020''>mark</span> <span m=''3598410''>with</span> <span m=''3598530''>green</span>
  <span m=''3598860''>up</span> <span m=''3598990''>here,</span> <span m=''3599570''>and</span>
  <span m=''3599660''>I''m going to</span> <span m=''3599750''>show</span> <span m=''3600010''>what''s</span>
  <span m=''3600260''>on</span> <span m=''3600410''>the queue</span> <span m=''3602080''>with</span>
  <span m=''3602250''>the</span> <span m=''3602420''>green</span> <span m=''3602690''>down</span>
  <span m=''3602930''>here,</span> <span m=''3603180''>and</span> <span m=''3603380''>dark</span>
  <span m=''3603660''>green</span> <span m=''3603900''>when</span> <span m=''3604020''>I</span>
  <span m=''3604060''>pop</span> <span m=''3604360''>something</span> <span m=''3604680''>off.</span>
  </p><p><span m=''3606510''>So</span> <span m=''3606790''>the</span> <span m=''3606880''>first</span>
  <span m=''3607190''>thing</span> <span m=''3607370''>I</span> <span m=''3607470''>do</span>
  <span m=''3607780''>is</span> <span m=''3608140''>I</span> <span m=''3608320''>say,</span>
  <span m=''3608570''>OK.</span> <span m=''3608920''>Let</span> <span m=''3609140''>me</span>
  <span m=''3609710''>dequeue</span> <span m=''3610230''>something.</span> <span m=''3610750''>And</span>
  <span m=''3610950''>in</span> <span m=''3611060''>this</span> <span m=''3611230''>case,</span>
  <span m=''3611440''>I''m</span> <span m=''3611540''>dequeueing</span> <span m=''3612090''>R,</span>
  <span m=''3613390''>because</span> <span m=''3613650''>it''s</span> <span m=''3613790''>the</span>
  <span m=''3613900''>only</span> <span m=''3614080''>thing</span> <span m=''3614270''>on</span>
  <span m=''3614460''>there.</span> <span m=''3615180''>And</span> <span m=''3615310''>what</span>
  <span m=''3615430''>I</span> <span m=''3615520''>do</span> <span m=''3615720''>now</span>
  <span m=''3615930''>is</span> <span m=''3616040''>I</span> <span m=''3616230''>visit</span>
  <span m=''3616510''>all</span> <span m=''3616730''>the</span> <span m=''3616830''>neighbors.</span>
  <span m=''3617730''>So</span> <span m=''3617880''>I</span> <span m=''3617950''>visit</span>
  <span m=''3618740''>b,</span> <span m=''3620380''>so</span> <span m=''3620500''>I</span>
  <span m=''3620560''>put</span> <span m=''3620800''>that</span> <span m=''3621030''>on,</span>
  <span m=''3621270''>mark it and</span> <span m=''3621640''>put</span> <span m=''3621870''>that</span>
  <span m=''3622080''>on,</span> <span m=''3622340''>and</span> <span m=''3622520''>then</span>
  <span m=''3622650''>I</span> <span m=''3622710''>visit</span> <span m=''3623050''>c,</span>
  <span m=''3623790''>so</span> <span m=''3623920''>I</span> <span m=''3624160''>visit
  and</span> <span m=''3624390''>put</span> <span m=''3624590''>that</span> <span
  m=''3624810''>on.</span> <span m=''3628330''>Then</span> <span m=''3629690''>I''m</span>
  <span m=''3629860''>done</span> <span m=''3630130''>with</span> <span m=''3630270''>R.</span>
  <span m=''3630770''>I</span> <span m=''3630840''>visited</span> <span m=''3631220''>all</span>
  <span m=''3631450''>its</span> <span m=''3631610''>neighbors.</span> <span m=''3632500''>So</span>
  <span m=''3632690''>then</span> <span m=''3632920''>I</span> <span m=''3633030''>go</span>
  <span m=''3633440''>and</span> <span m=''3633570''>I</span> <span m=''3633970''>dequeue</span>
  <span m=''3634390''>B,</span> <span m=''3636640''>and</span> <span m=''3637090''>now</span>
  <span m=''3637390''>visit</span> <span m=''3637690''>all</span> <span m=''3637950''>its</span>
  <span m=''3638140''>neighbors.</span> <span m=''3638660''>Well,</span> <span m=''3638905''>in</span>
  <span m=''3639150''>[? visit ?]</span> <span m=''3639540''>c,</span> <span m=''3640120''>there''s</span>
  <span m=''3640300''>nothing</span> <span m=''3640620''>to</span> <span m=''3640690''>be</span>
  <span m=''3640810''>done</span> <span m=''3641090''>there,</span> <span m=''3641310''>because</span>
  <span m=''3641700''>c</span> <span m=''3641810''>is</span> <span m=''3641950''>already</span>
  <span m=''3642190''>marked.</span> <span m=''3643230''>So</span> <span m=''3643350''>I</span>
  <span m=''3643520''>don''t</span> <span m=''3643690''>enqueue</span> <span m=''3644020''>it</span>
  <span m=''3644100''>again.</span> <span m=''3644520''>I</span> <span m=''3644750''>already</span>
  <span m=''3644980''>have</span> <span m=''3645300''>observed</span> <span m=''3645750''>that.</span>
  <span m=''3647460''>And</span> <span m=''3648440''>there''s</span> <span m=''3648600''>nothing</span>
  <span m=''3648930''>else</span> <span m=''3652550''>adjacent</span> <span m=''3653080''>to</span>
  <span m=''3653630''>b,</span> <span m=''3654330''>so</span> <span m=''3654610''>basically,</span>
  <span m=''3655290''>I</span> <span m=''3655500''>then</span> <span m=''3655810''>go</span>
  <span m=''3656020''>on</span> <span m=''3656290''>and</span> <span m=''3656670''>dequeue</span>
  <span m=''3657140''>c.</span> <span m=''3659510''>So</span> <span m=''3659690''>I
  have</span> <span m=''3659840''>c</span> <span m=''3660140''>here,</span> <span
  m=''3660500''>and</span> <span m=''3660650''>now</span> <span m=''3660840''>we</span>
  <span m=''3660940''>go</span> <span m=''3661200''>visit</span> <span m=''3661550''>its</span>
  <span m=''3661790''>neighbours,</span> <span m=''3662270''>and</span> <span m=''3662380''>the</span>
  <span m=''3662440''>neighbors</span> <span m=''3662860''>are</span> <span m=''3662970''>d
  and</span> <span m=''3663390''>e.</span> <span m=''3664170''>So</span> <span m=''3664310''>we</span>
  <span m=''3664410''>enqueue</span> <span m=''3664750''>d,</span> <span m=''3665250''>enqueue</span>
  <span m=''3665470''>e,</span> <span m=''3668260''>and</span> <span m=''3668430''>now</span>
  <span m=''3668720''>we</span> <span m=''3670030''>are</span> <span m=''3670330''>done</span>
  <span m=''3671310''>dequeuing</span> <span m=''3671980''>all</span> <span m=''3672180''>his</span>
  <span m=''3672390''>neighbors</span> <span m=''3672780''>and</span> <span m=''3672860''>marking</span>
  <span m=''3673250''>them,</span> <span m=''3673690''>so</span> <span m=''3673850''>now</span>
  <span m=''3674060''>we</span> <span m=''3674170''>pop</span> <span m=''3674520''>off</span>
  <span m=''3674760''>d.</span> <span m=''3676120''>And</span> <span m=''3676260''>now</span>
  <span m=''3676430''>d</span> <span m=''3676640''>has</span> <span m=''3676880''>no</span>
  <span m=''3677070''>neighbors,</span> <span m=''3677750''>so</span> <span m=''3677930''>there''s</span>
  <span m=''3678090''>nothing</span> <span m=''3678380''>to</span> <span m=''3678420''>be</span>
  <span m=''3678550''>done.</span> <span m=''3679510''>And</span> <span m=''3679690''>now</span>
  <span m=''3679990''>I</span> <span m=''3680130''>dequeue</span> <span m=''3680538''>e,</span>
  <span m=''3682400''>and</span> <span m=''3682600''>basically,</span> <span m=''3683050''>e</span>
  <span m=''3683240''>has</span> <span m=''3683440''>one</span> <span m=''3683670''>neighbor</span>
  <span m=''3683990''>f,</span> <span m=''3684880''>so</span> <span m=''3685060''>we
  mark</span> <span m=''3685410''>f.</span> <span m=''3687640''>Then</span> <span
  m=''3687780''>we</span> <span m=''3687900''>dequeue</span> <span m=''3688150''>f,</span>
  <span m=''3688985''>we</span> <span m=''3689410''>mark</span> <span m=''3689710''>g,</span>
  <span m=''3690640''>then</span> <span m=''3690790''>we</span> <span m=''3690900''>dequeue</span>
  <span m=''3691270''>g,</span> <span m=''3692370''>and</span> <span m=''3693120''>g</span>
  <span m=''3693390''>has--</span> <span m=''3694540''>the</span> <span m=''3694750''>only</span>
  <span m=''3694960''>neighbor</span> <span m=''3695310''>is</span> <span m=''3695490''>e.</span>
  <span m=''3696660''>And</span> <span m=''3696870''>now</span> <span m=''3697440''>my</span>
  <span m=''3697820''>queue</span> <span m=''3697950''>is</span> <span m=''3698060''>empty,</span>
  <span m=''3700870''>and</span> <span m=''3701050''>so</span> <span m=''3701300''>I''m</span>
  <span m=''3701420''>done.</span> <span m=''3703330''>And</span> <span m=''3703490''>now</span>
  <span m=''3703620''>you''ll</span> <span m=''3703790''>see,</span> <span m=''3704210''>what</span>
  <span m=''3704340''>did</span> <span m=''3704460''>I</span> <span m=''3704520''>do?</span>
  <span m=''3704690''>I</span> <span m=''3704790''>marked</span> <span m=''3705340''>all</span>
  <span m=''3705640''>the</span> <span m=''3705730''>things</span> <span m=''3706030''>that</span>
  <span m=''3706130''>were</span> <span m=''3706520''>reachable</span> <span m=''3707000''>from</span>
  <span m=''3707170''>r,</span> <span m=''3707880''>and</span> <span m=''3708010''>everything</span>
  <span m=''3708420''>else</span> <span m=''3708660''>is</span> <span m=''3708760''>garbage.</span>
  </p><p><span m=''3711470''>Now,</span> <span m=''3711770''>that''s</span> <span
  m=''3712020''>only</span> <span m=''3712220''>half</span> <span m=''3712560''>the</span>
  <span m=''3712710''>story.</span> <span m=''3714090''>So I''ve</span> <span m=''3714450''>marked</span>
  <span m=''3714800''>them,</span> <span m=''3715860''>but</span> <span m=''3716040''>more</span>
  <span m=''3716400''>relevantly,</span> <span m=''3716860''>it</span> <span m=''3717120''>turns</span>
  <span m=''3717410''>out</span> <span m=''3717600''>for</span> <span m=''3717720''>garbage</span>
  <span m=''3718180''>collection,</span> <span m=''3718620''>is</span> <span m=''3718750''>look</span>
  <span m=''3719080''>at</span> <span m=''3719180''>what</span> <span m=''3719350''>I''ve</span>
  <span m=''3719550''>got</span> <span m=''3719820''>in</span> <span m=''3720050''>my</span>
  <span m=''3720240''>queue.</span> <span m=''3721190''>What</span> <span m=''3721330''>do</span>
  <span m=''3721410''>I</span> <span m=''3721520''>have</span> <span m=''3721770''>in</span>
  <span m=''3721900''>my</span> <span m=''3722030''>queue?</span> <span m=''3724320''>I''ve</span>
  <span m=''3724500''>got</span> <span m=''3724810''>all</span> <span m=''3725260''>the</span>
  <span m=''3725340''>live</span> <span m=''3727540''>objects,</span> <span m=''3729820''>got</span>
  <span m=''3730070''>put</span> <span m=''3730250''>in</span> <span m=''3730350''>the</span>
  <span m=''3730450''>queue</span> <span m=''3730800''>as</span> <span m=''3731000''>we</span>
  <span m=''3731100''>were</span> <span m=''3731260''>going</span> <span m=''3731560''>along.</span>
  <span m=''3733060''>All</span> <span m=''3733380''>the</span> <span m=''3733460''>live</span>
  <span m=''3733780''>objects</span> <span m=''3734180''>are</span> <span m=''3734260''>put</span>
  <span m=''3734460''>in</span> <span m=''3734530''>the</span> <span m=''3734630''>queue.</span>
  <span m=''3734940''>And</span> <span m=''3735050''>not</span> <span m=''3735220''>only</span>
  <span m=''3735390''>that,</span> <span m=''3735690''>but</span> <span m=''3735840''>notice</span>
  <span m=''3736650''>they''re</span> <span m=''3736840''>all</span> <span m=''3737130''>adjacent</span>
  <span m=''3737700''>to</span> <span m=''3737770''>each</span> <span m=''3738040''>other</span>
  <span m=''3738270''>in</span> <span m=''3738340''>the</span> <span m=''3738440''>queue.</span>
  <span m=''3739440''>They''re</span> <span m=''3739650''>compact</span> <span m=''3741520''>in</span>
  <span m=''3741680''>the</span> <span m=''3741780''>queue.</span> </p><p><span m=''3745070''>And</span>
  <span m=''3745220''>so</span> <span m=''3745380''>the</span> <span m=''3745510''>idea</span>
  <span m=''3745730''>is, we''re</span> <span m=''3745810''>going</span> <span m=''3745970''>to</span>
  <span m=''3746050''>take</span> <span m=''3746330''>advantage</span> <span m=''3746970''>of</span>
  <span m=''3747050''>that</span> <span m=''3747370''>property.</span> <span m=''3747920''>That</span>
  <span m=''3748050''>when</span> <span m=''3748200''>I</span> <span m=''3748280''>do</span>
  <span m=''3748430''>breadth-first</span> <span m=''3749000''>search,</span> <span
  m=''3749590''>that</span> <span m=''3749780''>the</span> <span m=''3749890''>queue,</span>
  <span m=''3750210''>when</span> <span m=''3750440''>I''m</span> <span m=''3750640''>done,</span>
  <span m=''3751420''>I</span> <span m=''3751550''>put</span> <span m=''3751770''>every</span>
  <span m=''3752040''>object</span> <span m=''3752480''>in</span> <span m=''3752640''>there.</span>
  <span m=''3754630''>So</span> <span m=''3754760''>all</span> <span m=''3755100''>the</span>
  <span m=''3755150''>live</span> <span m=''3755490''>vertices</span> <span m=''3755940''>are</span>
  <span m=''3756010''>placed in</span> <span m=''3756430''>contiguous</span> <span
  m=''3757030''>storage</span> <span m=''3757470''>in</span> <span m=''3757720''>queue.</span>
  </p><p><span m=''3760580''>So</span> <span m=''3760840''>this</span> <span m=''3761050''>is</span>
  <span m=''3761240''>the</span> <span m=''3761570''>principle</span> <span m=''3762020''>behind</span>
  <span m=''3762390''>the</span> <span m=''3762480''>copying</span> <span m=''3763260''>garbage</span>
  <span m=''3763680''>collector,</span> <span m=''3765300''>which</span> <span m=''3765520''>is</span>
  <span m=''3765650''>one</span> <span m=''3765940''>of</span> <span m=''3766000''>the</span>
  <span m=''3766050''>more</span> <span m=''3766880''>popular</span> <span m=''3767400''>garbage</span>
  <span m=''3767780''>collectors</span> <span m=''3768300''>that''s</span> <span m=''3768490''>used.</span>
  <span m=''3769540''>The</span> <span m=''3769690''>idea</span> <span m=''3770110''>is</span>
  <span m=''3770660''>that</span> <span m=''3771560''>as</span> <span m=''3771880''>I''m</span>
  <span m=''3772040''>executing,</span> <span m=''3773290''>I''m</span> <span m=''3773410''>going</span>
  <span m=''3773490''>to</span> <span m=''3773530''>have</span> <span m=''3773860''>some</span>
  <span m=''3774320''>live</span> <span m=''3776040''>objects</span> <span m=''3778160''>and</span>
  <span m=''3778450''>some</span> <span m=''3779050''>dead</span> <span m=''3779530''>objects,</span>
  <span m=''3780980''>and</span> <span m=''3781340''>I''m</span> <span m=''3781430''>going</span>
  <span m=''3781510''>to</span> <span m=''3781630''>have</span> <span m=''3781740''>some</span>
  <span m=''3781960''>place</span> <span m=''3782280''>that</span> <span m=''3782370''>I''m</span>
  <span m=''3782480''>doing</span> <span m=''3782760''>my</span> <span m=''3782870''>next</span>
  <span m=''3783220''>allocation</span> <span m=''3783830''>at.</span> <span m=''3785830''>And</span>
  <span m=''3786010''>as</span> <span m=''3786240''>I</span> <span m=''3786300''>go</span>
  <span m=''3786510''>through,</span> <span m=''3786810''>I</span> <span m=''3786930''>allocate</span>
  <span m=''3787540''>more</span> <span m=''3787780''>things</span> <span m=''3791020''>in</span>
  <span m=''3791170''>what''s</span> <span m=''3791410''>called the</span> <span m=''3791700''>from</span>
  <span m=''3792010''>space,</span> <span m=''3793320''>and</span> <span m=''3793510''>I</span>
  <span m=''3793580''>keep</span> <span m=''3793840''>allocating,</span> <span m=''3795010''>and</span>
  <span m=''3795210''>I</span> <span m=''3795260''>may</span> <span m=''3795460''>do</span>
  <span m=''3795610''>a</span> <span m=''3795710''>deallocation,</span> <span m=''3797210''>and</span>
  <span m=''3797310''>maybe</span> <span m=''3797530''>some</span> <span m=''3797680''>more</span>
  <span m=''3797910''>allocation,</span> <span m=''3799260''>and</span> <span m=''3799360''>maybe</span>
  <span m=''3799590''>another</span> <span m=''3799860''>deallocation,</span> <span
  m=''3801310''>and some</span> <span m=''3801480''>more</span> <span m=''3801780''>allocation,</span>
  <span m=''3802890''>and</span> <span m=''3803030''>eventually</span> <span m=''3803560''>I</span>
  <span m=''3803670''>run</span> <span m=''3803940''>out</span> <span m=''3804120''>of</span>
  <span m=''3804220''>my</span> <span m=''3804990''>memory</span> <span m=''3805370''>that</span>
  <span m=''3805500''>I''ve</span> <span m=''3806310''>assigned</span> <span m=''3807210''>for</span>
  <span m=''3812140''>my</span> <span m=''3812290''>heap</span> <span m=''3812500''>storage.</span>
  </p><p><span m=''3814000''>So</span> <span m=''3814170''>when</span> <span m=''3814400''>I</span>
  <span m=''3814480''>get</span> <span m=''3814720''>to</span> <span m=''3814810''>this</span>
  <span m=''3815020''>point,</span> <span m=''3816070''>now</span> <span m=''3816410''>what</span>
  <span m=''3816590''>I</span> <span m=''3816690''>do</span> <span m=''3817020''>is</span>
  <span m=''3817170''>I''m</span> <span m=''3817270''>going</span> <span m=''3817360''>to</span>
  <span m=''3817440''>do</span> <span m=''3817610''>breadth-first</span> <span m=''3818300''>search</span>
  <span m=''3818970''>on</span> <span m=''3820320''>the from</span> <span m=''3820620''>space.</span>
  <span m=''3823120''>And</span> <span m=''3823260''>what</span> <span m=''3823390''>I''m</span>
  <span m=''3823500''>going</span> <span m=''3823600''>to</span> <span m=''3823690''>do</span>
  <span m=''3824190''>is</span> <span m=''3824360''>I''m</span> <span m=''3824460''>going</span>
  <span m=''3824540''>to</span> <span m=''3824640''>copy</span> <span m=''3826290''>using</span>
  <span m=''3827100''>the</span> <span m=''3827190''>live</span> <span m=''3827530''>storage</span>
  <span m=''3827980''>here,</span> <span m=''3828160''>using</span> <span m=''3828660''>[UNINTELLIGIBLE]</span>
  <span m=''3829140''>to</span> <span m=''3829300''>a</span> <span m=''3829410''>TO</span>
  <span m=''3829670''>space,</span> <span m=''3832300''>where</span> <span m=''3832430''>the</span>
  <span m=''3832580''>TO</span> <span m=''3832800''>space</span> <span m=''3833210''>implements</span>
  <span m=''3833740''>the</span> <span m=''3833860''>FIFO</span> <span m=''3834560''>queue.</span>
  <span m=''3836600''>So</span> <span m=''3836720''>here''s</span> <span m=''3837040''>the</span>
  <span m=''3837140''>TO</span> <span m=''3837350''>space,</span> <span m=''3838130''>and</span>
  <span m=''3838250''>when</span> <span m=''3838420''>I</span> <span m=''3838480''>go</span>
  <span m=''3838710''>through</span> <span m=''3838920''>and</span> <span m=''3839050''>I</span>
  <span m=''3839120''>walk</span> <span m=''3839540''>all</span> <span m=''3839730''>that,</span>
  <span m=''3840120''>I''ve</span> <span m=''3840310''>now</span> <span m=''3840620''>copied</span>
  <span m=''3841210''>all</span> <span m=''3841530''>of</span> <span m=''3841630''>the</span>
  <span m=''3841710''>values,</span> <span m=''3842780''>all</span> <span m=''3843030''>of</span>
  <span m=''3843100''>the</span> <span m=''3843250''>objects</span> <span m=''3843710''>down</span>
  <span m=''3843950''>to</span> <span m=''3844040''>this</span> <span m=''3844140''>space</span>
  <span m=''3844540''>over</span> <span m=''3844780''>here.</span> <span m=''3845690''>And</span>
  <span m=''3845860''>now</span> <span m=''3846060''>I</span> <span m=''3846190''>have</span>
  <span m=''3846740''>this</span> <span m=''3846980''>amount</span> <span m=''3847430''>of</span>
  <span m=''3847650''>storage</span> <span m=''3848080''>left.</span> <span m=''3848390''>I</span>
  <span m=''3848420''>make</span> <span m=''3848650''>the</span> <span m=''3848770''>two</span>
  <span m=''3848990''>space</span> <span m=''3849660''>exactly</span> <span m=''3850220''>the</span>
  <span m=''3850310''>same</span> <span m=''3850590''>size</span> <span m=''3851020''>as
  the</span> <span m=''3851190''>from</span> <span m=''3851460''>space.</span> <span
  m=''3852130''>I</span> <span m=''3852260''>have</span> <span m=''3852490''>to</span>
  <span m=''3852590''>make</span> <span m=''3852790''>it</span> <span m=''3852880''>at</span>
  <span m=''3852960''>least</span> <span m=''3853220''>that</span> <span m=''3853470''>big,</span>
  <span m=''3853670''>because</span> <span m=''3854760''>I</span> <span m=''3854890''>know</span>
  <span m=''3855730''>that</span> <span m=''3856000''>it</span> <span m=''3856170''>may</span>
  <span m=''3856360''>be</span> <span m=''3856520''>that</span> <span m=''3856790''>everything</span>
  <span m=''3857280''>here</span> <span m=''3857500''>is</span> <span m=''3857590''>alive.</span>
  <span m=''3859200''>Maybe</span> <span m=''3859490''>nothing</span> <span m=''3859820''>got</span>
  <span m=''3860030''>deallocated.</span> <span m=''3860660''>So I have</span> <span
  m=''3860870''>to</span> <span m=''3860960''>make</span> <span m=''3861140''>sure
  that</span> <span m=''3861300''>the</span> <span m=''3861460''>TO</span> <span m=''3861840''>space</span>
  <span m=''3862670''>is</span> <span m=''3862930''>large</span> <span m=''3863280''>enough</span>
  <span m=''3863490''>to</span> <span m=''3863590''>handle</span> <span m=''3864630''>everything</span>
  <span m=''3865050''>that</span> <span m=''3865190''>might</span> <span m=''3865420''>be</span>
  <span m=''3865530''>alive</span> <span m=''3865930''>there,</span> <span m=''3866180''>and
  it</span> <span m=''3866340''>may be</span> <span m=''3866690''>everything.</span>
  <span m=''3867960''>So</span> <span m=''3868120''>the</span> <span m=''3868220''>TO</span>
  <span m=''3868380''>space is</span> <span m=''3868870''>generally</span> <span m=''3869540''>allocated</span>
  <span m=''3869970''>to</span> <span m=''3870060''>be</span> <span m=''3870160''>exactly</span>
  <span m=''3870640''>the</span> <span m=''3870700''>same</span> <span m=''3870980''>size</span>
  <span m=''3871350''>as the</span> <span m=''3871520''>FROM</span> <span m=''3871770''>space.</span>
  <span m=''3874750''>So</span> <span m=''3874960''>basically,</span> <span m=''3876080''>the</span>
  <span m=''3876180''>way</span> <span m=''3876410''>I</span> <span m=''3876500''>compacted</span>
  <span m=''3877150''>is</span> <span m=''3877270''>I</span> <span m=''3877360''>copied</span>
  <span m=''3877840''>things</span> <span m=''3878140''>down</span> <span m=''3878600''>using</span>
  <span m=''3878970''>the</span> <span m=''3879050''>breadth-first</span> <span m=''3879580''>search</span>
  <span m=''3879870''>algorithm.</span> </p><p><span m=''3882700''>Now</span> <span
  m=''3883730''>there''s</span> <span m=''3884010''>one</span> <span m=''3884390''>problem</span>
  <span m=''3884940''>with</span> <span m=''3885100''>this,</span> <span m=''3885510''>and</span>
  <span m=''3885690''>that</span> <span m=''3885930''>is</span> <span m=''3886220''>that</span>
  <span m=''3886330''>we</span> <span m=''3886440''>have</span> <span m=''3886650''>pointers</span>
  <span m=''3888960''>in</span> <span m=''3889200''>these</span> <span m=''3889440''>objects.</span>
  <span m=''3890630''>And</span> <span m=''3890730''>when</span> <span m=''3890940''>I</span>
  <span m=''3891030''>copy</span> <span m=''3891590''>it</span> <span m=''3891700''>down</span>
  <span m=''3892030''>here,</span> <span m=''3892770''>how</span> <span m=''3892930''>did</span>
  <span m=''3893140''>I</span> <span m=''3893400''>make</span> <span m=''3893630''>sure</span>
  <span m=''3893850''>that</span> <span m=''3893940''>all</span> <span m=''3894120''>the</span>
  <span m=''3894190''>pointers</span> <span m=''3894680''>now</span> <span m=''3894880''>point</span>
  <span m=''3895210''>to</span> <span m=''3895310''>the</span> <span m=''3895420''>new</span>
  <span m=''3895580''>locations?</span> <span m=''3897050''>So</span> <span m=''3897200''>here''s</span>
  <span m=''3897500''>how</span> <span m=''3897630''>you</span> <span m=''3897780''>do</span>
  <span m=''3897970''>that.</span> <span m=''3900010''>So</span> <span m=''3900230''>since</span>
  <span m=''3900490''>the</span> <span m=''3900750''>FROM</span> <span m=''3901140''>address</span>
  <span m=''3901690''>of</span> <span m=''3901850''>the</span> <span m=''3901990''>object</span>
  <span m=''3902880''>is</span> <span m=''3903040''>not</span> <span m=''3903300''>generally</span>
  <span m=''3903740''>equal</span> <span m=''3904000''>to</span> <span m=''3904090''>the</span>
  <span m=''3904230''>TO</span> <span m=''3904480''>address,</span> <span m=''3904970''>pointers</span>
  <span m=''3905380''>must</span> <span m=''3905630''>be</span> <span m=''3905800''>updated.</span>
  <span m=''3906980''>So</span> <span m=''3907110''>I</span> <span m=''3907160''>have</span>
  <span m=''3907250''>to</span> <span m=''3907360''>know, of</span> <span m=''3907600''>course,</span>
  <span m=''3907860''>where</span> <span m=''3907970''>the</span> <span m=''3908090''>pointers</span>
  <span m=''3908520''>are.</span> <span m=''3909340''>So</span> <span m=''3909540''>the</span>
  <span m=''3909680''>idea</span> <span m=''3910050''>is</span> <span m=''3910190''>that</span>
  <span m=''3910290''>when</span> <span m=''3910440''>an</span> <span m=''3910580''>object</span>
  <span m=''3911040''>is</span> <span m=''3911180''>copied</span> <span m=''3911590''>to</span>
  <span m=''3911700''>the</span> <span m=''3911850''>TO</span> <span m=''3912100''>space,</span>
  <span m=''3912930''>what</span> <span m=''3913160''>we''re</span> <span m=''3913270''>going</span>
  <span m=''3913370''>to</span> <span m=''3913470''>do</span> <span m=''3913780''>in</span>
  <span m=''3914100''>FROM</span> <span m=''3914490''>space</span> <span m=''3915010''>is</span>
  <span m=''3915180''>store</span> <span m=''3915620''>a</span> <span m=''3915920''>forwarding</span>
  <span m=''3916460''>pointer</span> <span m=''3917600''>in</span> <span m=''3917810''>FROM</span>
  <span m=''3918100''>space</span> <span m=''3918490''>saying,</span> <span m=''3919010''>I</span>
  <span m=''3919120''>copy</span> <span m=''3919580''>you to</span> <span m=''3919940''>here.</span>
  <span m=''3922800''>So</span> <span m=''3923000''>that</span> <span m=''3923270''>whenever</span>
  <span m=''3923810''>I</span> <span m=''3923910''>look</span> <span m=''3924190''>at</span>
  <span m=''3924280''>something</span> <span m=''3924650''>in the</span> <span m=''3924810''>FROM</span>
  <span m=''3925120''>space</span> <span m=''3925540''>that''s</span> <span m=''3925700''>already</span>
  <span m=''3926070''>been</span> <span m=''3926270''>copied,</span> <span m=''3928200''>I</span>
  <span m=''3928320''>can</span> <span m=''3928480''>say,</span> <span m=''3928710''>oh,</span>
  <span m=''3928980''>here''s</span> <span m=''3929250''>where</span> <span m=''3929370''>it''s</span>
  <span m=''3929490''>been</span> <span m=''3929630''>copied</span> <span m=''3930100''>to.</span>
  <span m=''3930805''>It''s</span> <span m=''3931150''>been</span> <span m=''3931290''>copied</span>
  <span m=''3931660''>to</span> <span m=''3931760''>this</span> <span m=''3931960''>region</span>
  <span m=''3932360''>in</span> <span m=''3932470''>the</span> <span m=''3932580''>TO</span>
  <span m=''3932770''>space.</span> </p><p><span m=''3935060''>When</span> <span m=''3935210''>an</span>
  <span m=''3935330''>object</span> <span m=''3935790''>is</span> <span m=''3935880''>removed</span>
  <span m=''3936320''>from</span> <span m=''3936480''>the</span> <span m=''3936570''>FIFO</span>
  <span m=''3937120''>queue</span> <span m=''3938380''>in</span> <span m=''3938550''>the</span>
  <span m=''3938660''>TO</span> <span m=''3938890''>space,</span> <span m=''3940400''>we''re</span>
  <span m=''3940520''>going</span> <span m=''3940610''>to</span> <span m=''3940670''>update</span>
  <span m=''3941090''>all</span> <span m=''3941270''>its</span> <span m=''3941400''>pointers.</span>
  <span m=''3941685''>I''m going</span> <span m=''3941970''>to</span> <span m=''3942020''>give</span>
  <span m=''3942180''>you</span> <span m=''3942250''>an</span> <span m=''3942310''>example</span>
  <span m=''3942770''>of</span> <span m=''3942850''>this.</span> <span m=''3947580''>So</span>
  <span m=''3947990''>if</span> <span m=''3948120''>you</span> <span m=''3948210''>think</span>
  <span m=''3948420''>about</span> <span m=''3948690''>it,</span> <span m=''3948840''>when</span>
  <span m=''3949070''>I</span> <span m=''3949170''>remove</span> <span m=''3949640''>something</span>
  <span m=''3950090''>from</span> <span m=''3950320''>the</span> <span m=''3950380''>FIFO</span>
  <span m=''3950910''>queue,</span> <span m=''3952030''>at</span> <span m=''3952220''>that</span>
  <span m=''3952480''>point,</span> <span m=''3952730''>I</span> <span m=''3952860''>know</span>
  <span m=''3953300''>all</span> <span m=''3953800''>of</span> <span m=''3953900''>its</span>
  <span m=''3954430''>adjacent</span> <span m=''3956120''>vertices</span> <span m=''3957450''>have</span>
  <span m=''3957940''>been</span> <span m=''3958730''>placed</span> <span m=''3959120''>into
  the</span> <span m=''3959560''>queue,</span> <span m=''3960440''>into</span> <span
  m=''3960750''>the TO</span> <span m=''3961080''>space.</span> <span m=''3963790''>And</span>
  <span m=''3963920''>so at</span> <span m=''3964040''>that</span> <span m=''3964340''>point,</span>
  <span m=''3964680''>I</span> <span m=''3964790''>know</span> <span m=''3965680''>where</span>
  <span m=''3965940''>all</span> <span m=''3966130''>the</span> <span m=''3966210''>final</span>
  <span m=''3966570''>destinations</span> <span m=''3967260''>of</span> <span m=''3967360''>pointers</span>
  <span m=''3967850''>are.</span> </p><p><span m=''3969000''>So</span> <span m=''3969460''>here''s</span>
  <span m=''3969720''>an</span> <span m=''3969780''>example.</span> <span m=''3972390''>So</span>
  <span m=''3972880''>suppose</span> <span m=''3973390''>that</span> <span m=''3975080''>I''m</span>
  <span m=''3975270''>doing</span> <span m=''3975540''>the</span> <span m=''3975650''>copy</span>
  <span m=''3976130''>of</span> <span m=''3976220''>these</span> <span m=''3976490''>guys,
  and</span> <span m=''3976790''>I''ve</span> <span m=''3976930''>got</span> <span
  m=''3977060''>all</span> <span m=''3977270''>the</span> <span m=''3977340''>pointers</span>
  <span m=''3977810''>around</span> <span m=''3978130''>here,</span> <span m=''3978980''>and</span>
  <span m=''3979050''>now</span> <span m=''3979200''>some</span> <span m=''3979480''>of</span>
  <span m=''3979520''>these</span> <span m=''3979770''>guys</span> <span m=''3980090''>have</span>
  <span m=''3980240''>already</span> <span m=''3980470''>made</span> <span m=''3980750''>it</span>
  <span m=''3980950''>into</span> <span m=''3981930''>the</span> <span m=''3982790''>FIFO</span>
  <span m=''3983190''>queue.</span> <span m=''3983420''>Let''s</span> <span m=''3983630''>say</span>
  <span m=''3983760''>this</span> <span m=''3983970''>guy</span> <span m=''3984210''>has</span>
  <span m=''3984350''>made</span> <span m=''3984580''>it</span> <span m=''3984680''>in,</span>
  <span m=''3984990''>because</span> <span m=''3985190''>I''ve</span> <span m=''3985300''>got</span>
  <span m=''3985400''>forwarding</span> <span m=''3985910''>pointer</span> <span m=''3986260''>to</span>
  <span m=''3986360''>there,</span> <span m=''3986990''>and</span> <span m=''3987140''>this</span>
  <span m=''3987350''>guy has</span> <span m=''3987670''>made it in,</span> <span
  m=''3988120''>so</span> <span m=''3988240''>I''ve</span> <span m=''3988370''>got</span>
  <span m=''3988500''>forwarding</span> <span m=''3988960''>pointer</span> <span m=''3989320''>to</span>
  <span m=''3989440''>there.</span> <span m=''3990080''>And</span> <span m=''3990270''>this</span>
  <span m=''3990450''>is</span> <span m=''3990570''>what</span> <span m=''3990770''>my</span>
  <span m=''3990900''>queue</span> <span m=''3991220''>currently</span> <span m=''3991610''>holds.</span>
  </p><p><span m=''3993610''>So</span> <span m=''3993790''>when</span> <span m=''3994010''>I</span>
  <span m=''3994220''>remove</span> <span m=''3994680''>an</span> <span m=''3994790''>item</span>
  <span m=''3995040''>from</span> <span m=''3995210''>the</span> <span m=''3995300''>queue,</span>
  <span m=''3996570''>I</span> <span m=''3996700''>then</span> <span m=''3996840''>look</span>
  <span m=''3997130''>at</span> <span m=''3997250''>this</span> <span m=''3997490''>guy,</span>
  <span m=''3998580''>and</span> <span m=''3998680''>what</span> <span m=''3998830''>I</span>
  <span m=''3998910''>do</span> <span m=''3999110''>is</span> <span m=''3999250''>first</span>
  <span m=''3999600''>of</span> <span m=''3999670''>all,</span> <span m=''3999990''>I</span>
  <span m=''4000080''>visit</span> <span m=''4000440''>all</span> <span m=''4000770''>of</span>
  <span m=''4000840''>the</span> <span m=''4000960''>adjacent</span> <span m=''4001480''>neighbors.</span>
  <span m=''4002440''>So I</span> <span m=''4002610''>visit</span> <span m=''4002910''>this</span>
  <span m=''4003190''>guy</span> <span m=''4003420''>and</span> <span m=''4003600''>I</span>
  <span m=''4003670''>say,</span> <span m=''4003900''>oh,</span> <span m=''4004250''>he''s</span>
  <span m=''4004520''>already</span> <span m=''4004730''>been</span> <span m=''4004900''>copied,</span>
  <span m=''4005340''>because</span> <span m=''4005530''>I have a</span> <span m=''4005730''>forwarding</span>
  <span m=''4006190''>pointer.</span> <span m=''4006910''>So</span> <span m=''4007080''>nothing</span>
  <span m=''4007420''>to</span> <span m=''4007490''>be</span> <span m=''4007620''>done</span>
  <span m=''4007870''>there.</span> <span m=''4008540''>But</span> <span m=''4008780''>this</span>
  <span m=''4009050''>guy,</span> <span m=''4009360''>he</span> <span m=''4009490''>hasn''t</span>
  <span m=''4009790''>been</span> <span m=''4009970''>copied</span> <span m=''4010410''>yet.</span>
  <span m=''4011640''>So</span> <span m=''4011750''>I</span> <span m=''4011800''>have</span>
  <span m=''4011970''>to</span> <span m=''4012140''>make</span> <span m=''4012340''>sure
  that</span> <span m=''4012670''>that</span> <span m=''4012920''>guy</span> <span
  m=''4013710''>is</span> <span m=''4014080''>copied</span> <span m=''4014500''>by
  enqueuing</span> <span m=''4015210''>the</span> <span m=''4015340''>adjacent</span>
  <span m=''4015820''>vertices.</span> </p><p><span m=''4016270''>So</span> <span
  m=''4016480''>I</span> <span m=''4016550''>copy</span> <span m=''4017190''>my</span>
  <span m=''4017360''>neighbor</span> <span m=''4021340''>to</span> <span m=''4021590''>there.</span>
  <span m=''4022220''>And</span> <span m=''4022400''>part</span> <span m=''4022680''>of</span>
  <span m=''4022760''>copying</span> <span m=''4023400''>is,</span> <span m=''4024830''>if</span>
  <span m=''4024970''>I''m</span> <span m=''4025080''>actually</span> <span m=''4025350''>making</span>
  <span m=''4025720''>a</span> <span m=''4025800''>copy,</span> <span m=''4026260''>I''m</span>
  <span m=''4026350''>going</span> <span m=''4026450''>to</span> <span m=''4026490''>have</span>
  <span m=''4026590''>a</span> <span m=''4026680''>pointer</span> <span m=''4027200''>from</span>
  <span m=''4027460''>here.</span> <span m=''4028630''>The</span> <span m=''4028720''>pointer</span>
  <span m=''4029080''>now</span> <span m=''4029300''>has</span> <span m=''4029540''>to</span>
  <span m=''4029640''>point</span> <span m=''4029990''>to</span> <span m=''4030090''>this</span>
  <span m=''4030530''>guy</span> <span m=''4030770''>over</span> <span m=''4031030''>here,</span>
  <span m=''4031670''>because</span> <span m=''4033590''>that''s</span> <span m=''4033840''>how</span>
  <span m=''4034070''>I''m</span> <span m=''4034280''>copying.</span> <span m=''4035140''>Otherwise</span>
  <span m=''4035510''>it</span> <span m=''4035590''>isn''t</span> <span m=''4035780''>a</span>
  <span m=''4035830''>copy.</span> <span m=''4037260''>So</span> <span m=''4037460''>in</span>
  <span m=''4037610''>the</span> <span m=''4037710''>copy,</span> <span m=''4038620''>this</span>
  <span m=''4038880''>pointer</span> <span m=''4039400''>is</span> <span m=''4039560''>the</span>
  <span m=''4039640''>same</span> <span m=''4039960''>as</span> <span m=''4040090''>that</span>
  <span m=''4040370''>one, is</span> <span m=''4040780''>pointing to</span> <span
  m=''4041110''>the</span> <span m=''4041210''>same</span> <span m=''4041510''>storage</span>
  <span m=''4041930''>location,</span> <span m=''4042710''>namely</span> <span m=''4043050''>this</span>
  <span m=''4043260''>place</span> <span m=''4043540''>over</span> <span m=''4043770''>here.</span>
  <span m=''4045520''>So</span> <span m=''4045670''>I</span> <span m=''4045750''>do</span>
  <span m=''4045970''>that</span> <span m=''4046240''>for all</span> <span m=''4046590''>my</span>
  <span m=''4046780''>adjacent</span> <span m=''4048040''>vertices.</span> <span m=''4049170''>People</span>
  <span m=''4049450''>follow</span> <span m=''4049730''>so</span> <span m=''4049920''>far?</span>
  </p><p><span m=''4051660''>Now</span> <span m=''4053080''>I''ve</span> <span m=''4053320''>copied</span>
  <span m=''4053800''>all of</span> <span m=''4054200''>the</span> <span m=''4054310''>neighbors</span>
  <span m=''4054820''>for</span> <span m=''4054920''>this</span> <span m=''4055180''>guy.</span>
  <span m=''4055760''>Now</span> <span m=''4056050''>this</span> <span m=''4056400''>guy,</span>
  <span m=''4056680''>all</span> <span m=''4056980''>of</span> <span m=''4057120''>his</span>
  <span m=''4057250''>neighbors</span> <span m=''4059280''>are</span> <span m=''4059470''>in</span>
  <span m=''4059670''>their</span> <span m=''4059810''>final</span> <span m=''4060210''>destinations</span>
  <span m=''4060980''>in</span> <span m=''4061090''>the</span> <span m=''4061180''>TO</span>
  <span m=''4061400''>space.</span> <span m=''4063070''>So</span> <span m=''4063250''>that</span>
  <span m=''4063490''>means</span> <span m=''4063700''>I</span> <span m=''4063780''>can</span>
  <span m=''4063970''>now</span> <span m=''4064280''>update</span> <span m=''4064770''>these</span>
  <span m=''4065000''>pointers</span> <span m=''4065950''>to</span> <span m=''4066070''>be</span>
  <span m=''4066390''>the</span> <span m=''4066520''>pointers</span> <span m=''4067060''>in</span>
  <span m=''4067200''>the</span> <span m=''4067280''>TO</span> <span m=''4067470''>space.</span>
  <span m=''4068310''>So</span> <span m=''4068450''>I</span> <span m=''4068530''>do</span>
  <span m=''4068710''>that</span> <span m=''4068960''>as</span> <span m=''4069110''>follows.</span>
  <span m=''4071590''>Oh,</span> <span m=''4071890''>first of all,</span> <span m=''4072190''>I</span>
  <span m=''4072310''>forgot</span> <span m=''4072930''>to</span> <span m=''4073220''>place
  the</span> <span m=''4073500''>forwarding</span> <span m=''4073940''>pointer</span>
  <span m=''4074310''>here</span> <span m=''4075010''>to</span> <span m=''4075080''>indicate</span>
  <span m=''4075480''>that</span> <span m=''4075550''>he''s</span> <span m=''4075750''>been</span>
  <span m=''4075900''>copied.</span> <span m=''4076930''>That''s</span> <span m=''4077140''>how</span>
  <span m=''4077210''>I''m</span> <span m=''4077330''>doing</span> <span m=''4077560''>the</span>
  <span m=''4077640''>marks.</span> <span m=''4079200''>Sorry</span> <span m=''4079420''>about</span>
  <span m=''4079630''>that.</span> </p><p><span m=''4080540''>So</span> <span m=''4080670''>I</span>
  <span m=''4080730''>copied</span> <span m=''4081210''>the</span> <span m=''4081280''>values,</span>
  <span m=''4082350''>and</span> <span m=''4082500''>that''s</span> <span m=''4082690''>just</span>
  <span m=''4082880''>a</span> <span m=''4082940''>straight</span> <span m=''4083340''>copy,</span>
  <span m=''4083690''>because</span> <span m=''4083930''>all</span> <span m=''4084220''>the</span>
  <span m=''4084320''>pointer</span> <span m=''4084690''>values</span> <span m=''4085150''>are</span>
  <span m=''4085220''>now</span> <span m=''4085380''>pointing</span> <span m=''4086080''>into</span>
  <span m=''4086310''>this</span> <span m=''4086420''>space.</span> <span m=''4088130''>Then</span>
  <span m=''4088390''>I</span> <span m=''4088470''>put</span> <span m=''4088690''>a</span>
  <span m=''4088740''>forwarding</span> <span m=''4089190''>pointer</span> <span m=''4089580''>in.</span>
  <span m=''4090170''>Now</span> <span m=''4090480''>I''m</span> <span m=''4090640''>ready</span>
  <span m=''4090930''>to</span> <span m=''4091070''>do</span> <span m=''4091280''>the</span>
  <span m=''4092530''>update</span> <span m=''4092940''>of</span> <span m=''4093010''>the</span>
  <span m=''4093080''>pointers</span> <span m=''4093520''>here.</span> </p><p><span
  m=''4095040''>So</span> <span m=''4095180''>I</span> <span m=''4095310''>update</span>
  <span m=''4095700''>the</span> <span m=''4095770''>pointers</span> <span m=''4096279''>to</span>
  <span m=''4096390''>the</span> <span m=''4096510''>removed</span> <span m=''4096960''>item.</span>
  <span m=''4097819''>So</span> <span m=''4097939''>here''s</span> <span m=''4098240''>one</span>
  <span m=''4098450''>pointer.</span> <span m=''4099000''>I</span> <span m=''4099109''>get</span>
  <span m=''4099350''>rid</span> <span m=''4099490''>of</span> <span m=''4099529''>him</span>
  <span m=''4099729''>there</span> <span m=''4100040''>and</span> <span m=''4100229''>I</span>
  <span m=''4100370''>make</span> <span m=''4100609''>him</span> <span m=''4100710''>point</span>
  <span m=''4100979''>to</span> <span m=''4101060''>the</span> <span m=''4101140''>forwarding</span>
  <span m=''4101640''>thing.</span> <span m=''4101770''>He</span> <span m=''4102109''>used</span>
  <span m=''4102420''>to</span> <span m=''4102470''>point to</span> <span m=''4102770''>here,</span>
  <span m=''4103630''>now</span> <span m=''4103979''>he''s pointing</span> <span m=''4104310''>to</span>
  <span m=''4104380''>here.</span> <span m=''4105100''>This</span> <span m=''4105340''>one</span>
  <span m=''4105550''>used</span> <span m=''4105720''>to</span> <span m=''4105890''>point
  to</span> <span m=''4106279''>here,</span> <span m=''4106990''>I</span> <span m=''4107130''>want</span>
  <span m=''4107300''>to</span> <span m=''4107350''>make</span> <span m=''4107569''>him</span>
  <span m=''4107700''>point</span> <span m=''4107990''>to</span> <span m=''4108069''>there.</span>
  <span m=''4113399''>There</span> <span m=''4113580''>we</span> <span m=''4113640''>go.</span>
  <span m=''4116220''>So</span> <span m=''4116399''>now</span> <span m=''4116609''>he''s</span>
  <span m=''4116770''>pointing</span> <span m=''4116990''>here.</span> <span m=''4117350''>And</span>
  <span m=''4117490''>now</span> <span m=''4118149''>this</span> <span m=''4118620''>guy</span>
  <span m=''4118870''>here</span> <span m=''4119180''>now</span> <span m=''4119470''>has</span>
  <span m=''4119729''>his</span> <span m=''4120000''>pointers</span> <span m=''4120350''>to</span>
  <span m=''4120470''>his</span> <span m=''4120649''>final</span> <span m=''4120979''>destinations.</span>
  <span m=''4123270''>And</span> <span m=''4123410''>so</span> <span m=''4123710''>the</span>
  <span m=''4123840''>invariance</span> <span m=''4124220''>that</span> <span m=''4124359''>I''m</span>
  <span m=''4124399''>maintaining</span> <span m=''4125040''>is</span> <span m=''4125180''>that</span>
  <span m=''4125290''>everything</span> <span m=''4125899''>before</span> <span m=''4126319''>the</span>
  <span m=''4126649''>head</span> <span m=''4129380''>of</span> <span m=''4129550''>the</span>
  <span m=''4129660''>queue</span> <span m=''4130270''>all</span> <span m=''4130550''>have</span>
  <span m=''4130819''>their</span> <span m=''4130950''>final</span> <span m=''4132060''>pointers</span>
  <span m=''4132630''>in</span> <span m=''4132800''>place</span> <span m=''4133550''>in</span>
  <span m=''4133720''>the</span> <span m=''4133810''>TO</span> <span m=''4133990''>space.</span>
  <span m=''4134890''>Question?</span> </p><p><span m=''4136359''>AUDIENCE: So do
  you know</span> <span m=''4137279''>where to</span> <span m=''4137739''>put the</span>
  <span m=''4138199''>pointers--</span> <span m=''4139119''>how do</span> <span m=''4139579''>[UNINTELLIGIBLE]</span>
  <span m=''4140039''>pointers</span> <span m=''4141040''>go</span> <span m=''4141840''>from
  the</span> <span m=''4142204''>TO</span> <span m=''4142569''>space to the</span>
  <span m=''4143065''>TO</span> <span m=''4143561''>space</span> <span m=''4144057''>so
  that they''re actually</span> <span m=''4144553''>getting to their</span> <span
  m=''4145049''>final destination?</span> <span m=''4145545''>So my question</span>
  <span m=''4146041''>is,</span> <span m=''4146537''>[UNINTELLIGIBLE]</span> <span
  m=''4147033''>by</span> <span m=''4147529''>following</span> <span m=''4148025''>[UNINTELLIGIBLE].</span>
  <span m=''4153000''>But</span> <span m=''4153859''>how do you know</span> <span
  m=''4154319''>what pointer</span> <span m=''4154779''>to follow?</span> <span m=''4155699''>How
  do you</span> <span m=''4156159''>know that</span> <span m=''4156619''>[INAUDIBLE]?</span>
  </p><p><span m=''4157539''>CHARLES LEISERSON: If</span> <span m=''4157615''>I</span>
  <span m=''4157692''>have</span> <span m=''4157769''>a</span> <span m=''4157845''>pointer</span>
  <span m=''4157922''>to</span> <span m=''4157999''>something</span> <span m=''4158459''>in</span>
  <span m=''4158919''>the</span> <span m=''4159380''>FROM</span> <span m=''4159630''>space,</span>
  <span m=''4161359''>then</span> <span m=''4161810''>I</span> <span m=''4161950''>update</span>
  <span m=''4162239''>it</span> <span m=''4162529''>to</span> <span m=''4162620''>be</span>
  <span m=''4162819''>the</span> <span m=''4162910''>forwarding</span> <span m=''4163399''>pointer</span>
  <span m=''4163870''>in</span> <span m=''4163960''>the</span> <span m=''4164050''>TO</span>
  <span m=''4164220''>space.</span> </p><p><span m=''4165196''>AUDIENCE: Yeah, the</span>
  <span m=''4165663''>question is,</span> <span m=''4166130''>how do you</span> <span
  m=''4166600''>know that</span> <span m=''4167015''>[INAUDIBLE]</span> <span m=''4167729''>it''s</span>
  <span m=''4168029''>being</span> <span m=''4168290''>pointed</span> <span m=''4168384''>to</span>
  <span m=''4168479''>[? the ?]</span> <span m=''4168859''>actually</span> <span m=''4169317''>in
  the</span> <span m=''4169775''>TO</span> <span m=''4170233''>space?</span> <span
  m=''4171607''>Can you</span> <span m=''4172065''>check,</span> <span m=''4172523''>is
  this</span> <span m=''4172981''>in</span> <span m=''4173095''>the</span> <span m=''4173210''>TO</span>
  <span m=''4173324''>space?</span> </p><p><span m=''4173439''>CHARLES LEISERSON:
  Well, yeah.</span> <span m=''4173939''>I mean, you know what</span> <span m=''4174439''>the</span>
  <span m=''4174479''>range</span> <span m=''4174859''>of</span> <span m=''4174950''>the</span>
  <span m=''4175060''>two</span> <span m=''4175200''>spaces</span> <span m=''4175700''>is,</span>
  <span m=''4175880''>so</span> <span m=''4175990''>you</span> <span m=''4176130''>could</span>
  <span m=''4176260''>check</span> <span m=''4176580''>that.</span> <span m=''4179330''>OK.</span>
  <span m=''4179510''>Question?</span> </p><p><span m=''4180140''>AUDIENCE: So</span>
  <span m=''4180625''>the</span> <span m=''4180786''>reason</span> <span m=''4180948''>you</span>
  <span m=''4181110''>would</span> <span m=''4181352''>be</span> <span m=''4181595''>using</span>
  <span m=''4182080''>[? BFS ?]</span> <span m=''4182322''>instead</span> <span m=''4182565''>of</span>
  <span m=''4183050''>[? DFS ?]</span> <span m=''4183535''>is</span> <span m=''4183777''>because</span>
  <span m=''4184020''>[INAUDIBLE].</span> </p><p><span m=''4187410''>CHARLES LEISERSON:
  The</span> <span m=''4187890''>reason</span> <span m=''4188285''>you''re</span>
  <span m=''4188482''>using</span> <span m=''4188680''>BFS</span> <span m=''4188934''>is
  because it</span> <span m=''4189189''>has</span> <span m=''4189310''>this</span>
  <span m=''4189710''>nice</span> <span m=''4189970''>property</span> <span m=''4190300''>that
  the</span> <span m=''4190630''>queue</span> <span m=''4191130''>represents</span>
  <span m=''4191680''>the</span> <span m=''4191910''>copying</span> <span m=''4192430''>of</span>
  <span m=''4192560''>all</span> <span m=''4192689''>the</span> <span m=''4192810''>values.</span>
  <span m=''4193390''>If</span> <span m=''4193740''>I</span> <span m=''4193890''>use</span>
  <span m=''4194149''>DFS,</span> <span m=''4194720''>I</span> <span m=''4194790''>need</span>
  <span m=''4194910''>a</span> <span m=''4195030''>stack</span> <span m=''4195550''>to</span>
  <span m=''4195640''>do</span> <span m=''4195840''>it,</span> <span m=''4196240''>and
  then I''m</span> <span m=''4196600''>overwriting</span> <span m=''4197910''>the</span>
  <span m=''4198020''>locations</span> <span m=''4199860''>where</span> <span m=''4200080''>the</span>
  <span m=''4201000''>vertices</span> <span m=''4201470''>would</span> <span m=''4201600''>be</span>
  <span m=''4201710''>stored</span> <span m=''4202150''>in</span> <span m=''4202240''>the</span>
  <span m=''4202320''>data</span> <span m=''4202540''>structure.</span> <span m=''4204280''>By</span>
  <span m=''4204430''>using</span> <span m=''4204720''>DFS,</span> <span m=''4206120''>there''s</span>
  <span m=''4206400''>this</span> <span m=''4206610''>just</span> <span m=''4206850''>clever</span>
  <span m=''4207230''>thing</span> <span m=''4207570''>that</span> <span m=''4208120''>the</span>
  <span m=''4208240''>queue,</span> <span m=''4208640''>when</span> <span m=''4208830''>I''m</span>
  <span m=''4208990''>done</span> <span m=''4209260''>with</span> <span m=''4209440''>DFS,</span>
  <span m=''4210020''>represents</span> <span m=''4210670''>all</span> <span m=''4211010''>of</span>
  <span m=''4211090''>the</span> <span m=''4211180''>visited</span> <span m=''4211600''>vertices.</span>
  <span m=''4213550''>It''s</span> <span m=''4213730''>very</span> <span m=''4213990''>clever.</span>
  <span m=''4215620''>Wish</span> <span m=''4215810''>I''d</span> <span m=''4215900''>thought</span>
  <span m=''4216155''>of that.</span> <span m=''4217230''>But</span> <span m=''4217380''>I</span>
  <span m=''4217500''>was,</span> <span m=''4217720''>I</span> <span m=''4217780''>think,</span>
  <span m=''4218030''>only</span> <span m=''4218380''>10</span> <span m=''4218600''>years</span>
  <span m=''4218820''>old</span> <span m=''4219030''>or</span> <span m=''4219090''>something</span>
  <span m=''4219400''>when</span> <span m=''4219520''>they</span> <span m=''4219630''>invented</span>
  <span m=''4219990''>this,</span> <span m=''4222500''>and</span> <span m=''4222630''>I</span>
  <span m=''4222670''>wasn''t</span> <span m=''4222970''>that</span> <span m=''4223160''>precocious.</span>
  <span m=''4226390''>OK?</span> <span m=''4228570''>So</span> <span m=''4228790''>very,</span>
  <span m=''4229110''>very</span> <span m=''4229400''>clever.</span> </p><p><span
  m=''4230560''>So</span> <span m=''4230680''>this</span> <span m=''4230900''>is</span>
  <span m=''4231210''>the</span> <span m=''4231580''>scheme</span> <span m=''4231890''>behind</span>
  <span m=''4232450''>the</span> <span m=''4234110''>Minsky,</span> <span m=''4234760''>Fenichel,</span>
  <span m=''4235340''>Yochelson</span> <span m=''4236220''>garbage</span> <span m=''4236630''>collector.</span>
  <span m=''4237120''>So</span> <span m=''4237320''>Marvin</span> <span m=''4237660''>Minsky,</span>
  <span m=''4238050''>you</span> <span m=''4238160''>may</span> <span m=''4238280''>have</span>
  <span m=''4238390''>heard</span> <span m=''4238590''>of,</span> <span m=''4239590''>was</span>
  <span m=''4239890''>one</span> <span m=''4240020''>of</span> <span m=''4240060''>the</span>
  <span m=''4240160''>inventors</span> <span m=''4241140''>of</span> <span m=''4241340''>a</span>
  <span m=''4241590''>scheme</span> <span m=''4241770''>like</span> <span m=''4241980''>this.</span>
  <span m=''4244020''>One</span> <span m=''4244200''>reason</span> <span m=''4244480''>he''s</span>
  <span m=''4244620''>so</span> <span m=''4244750''>famous.</span> </p><p><span m=''4248020''>Good.</span>
  <span m=''4249020''>So</span> <span m=''4249750''>this</span> <span m=''4249960''>is</span>
  <span m=''4250090''>really</span> <span m=''4250320''>nice,</span> <span m=''4250600''>because</span>
  <span m=''4250760''>it</span> <span m=''4250860''>takes</span> <span m=''4251120''>me</span>
  <span m=''4251240''>linear</span> <span m=''4251670''>time</span> <span m=''4252030''>to</span>
  <span m=''4252110''>copy</span> <span m=''4252630''>and</span> <span m=''4252740''>update</span>
  <span m=''4253110''>all of</span> <span m=''4253310''>the</span> <span m=''4253370''>vertices.</span>
  <span m=''4255990''>It''s</span> <span m=''4256120''>just</span> <span m=''4256310''>one</span>
  <span m=''4256560''>pass</span> <span m=''4256910''>of</span> <span m=''4256960''>breadth-first</span>
  <span m=''4257480''>search.</span> <span m=''4257800''>Very</span> <span m=''4258040''>fast</span>
  <span m=''4258450''>to</span> <span m=''4258540''>copy and</span> <span m=''4259010''>update</span>
  <span m=''4259350''>all</span> <span m=''4259460''>the</span> <span m=''4259570''>vertices.</span>
  <span m=''4260990''>Sometimes,</span> <span m=''4261410''>by the way,</span> <span
  m=''4261760''>people</span> <span m=''4262060''>call</span> <span m=''4262270''>these</span>
  <span m=''4262460''>forwarding</span> <span m=''4262840''>pointers,</span> <span
  m=''4263180''>they</span> <span m=''4263270''>call</span> <span m=''4263460''>them</span>
  <span m=''4263540''>broken</span> <span m=''4263910''>hearts.</span> <span m=''4264760''>You''ll</span>
  <span m=''4264870''>see</span> <span m=''4265060''>that</span> <span m=''4265250''>in</span>
  <span m=''4265350''>the</span> <span m=''4265430''>literature.</span> <span m=''4266220''>They</span>
  <span m=''4266330''>call</span> <span m=''4266580''>them</span> <span m=''4267040''>a</span>
  <span m=''4267110''>broken</span> <span m=''4267490''>heart</span> <span m=''4267840''>if</span>
  <span m=''4268020''>it''s--</span> <span m=''4269400''>I</span> <span m=''4269770''>don''t</span>
  <span m=''4269940''>quite</span> <span m=''4270160''>remember</span> <span m=''4270410''>why</span>
  <span m=''4270750''>that''s</span> <span m=''4271130''>the--</span> <span m=''4273750''>it''s</span>
  <span m=''4273940''>like,</span> <span m=''4274380''>I</span> <span m=''4274460''>went</span>
  <span m=''4274780''>there,</span> <span m=''4275180''>oh, you''re</span> <span m=''4275300''>not</span>
  <span m=''4275580''>there,</span> <span m=''4275840''>it''s</span> <span m=''4276020''>over</span>
  <span m=''4276240''>there--</span> <span m=''4276800''>it''s</span> <span m=''4276910''>like,</span>
  <span m=''4277140''>I</span> <span m=''4277210''>don''t</span> <span m=''4277310''>know.</span>
  </p><p><span m=''4280400''>Now,</span> <span m=''4281870''>the</span> <span m=''4281980''>last</span>
  <span m=''4282430''>thing</span> <span m=''4282590''>you</span> <span m=''4282660''>have</span>
  <span m=''4282860''>to</span> <span m=''4282980''>do--</span> <span m=''4283270''>and</span>
  <span m=''4283370''>this</span> <span m=''4283540''>is</span> <span m=''4283650''>something</span>
  <span m=''4283980''>that''s</span> <span m=''4284150''>not</span> <span m=''4284420''>talked</span>
  <span m=''4284770''>about</span> <span m=''4285020''>a</span> <span m=''4285040''>lot</span>
  <span m=''4286200''>in</span> <span m=''4286370''>the</span> <span m=''4286480''>literature--</span>
  <span m=''4287370''>is</span> <span m=''4287510''>how</span> <span m=''4287750''>do</span>
  <span m=''4287830''>you</span> <span m=''4287930''>manage</span> <span m=''4288380''>these</span>
  <span m=''4288710''>from</span> <span m=''4289040''>and</span> <span m=''4289230''>to</span>
  <span m=''4289460''>spaces</span> <span m=''4290690''>in</span> <span m=''4290900''>virtual</span>
  <span m=''4291280''>memory?</span> <span m=''4293830''>So</span> <span m=''4293970''>here''s</span>
  <span m=''4294280''>the</span> <span m=''4294360''>strategy</span> <span m=''4294970''>that</span>
  <span m=''4295100''>works</span> <span m=''4295440''>well.</span> <span m=''4297440''>So</span>
  <span m=''4297640''>basically,</span> <span m=''4298870''>typically</span> <span
  m=''4299340''>what</span> <span m=''4299650''>I''m</span> <span m=''4299690''>doing</span>
  <span m=''4300080''>is</span> <span m=''4300220''>after</span> <span m=''4300700''>I''ve</span>
  <span m=''4300910''>done</span> <span m=''4301290''>a</span> <span m=''4301660''>copy,</span>
  <span m=''4302370''>I''ve</span> <span m=''4302730''>emptied</span> <span m=''4303160''>everything</span>
  <span m=''4303570''>out</span> <span m=''4303720''>of the</span> <span m=''4303900''>FROM</span>
  <span m=''4304220''>space,</span> <span m=''4305010''>and</span> <span m=''4305130''>I''ve</span>
  <span m=''4305240''>got</span> <span m=''4305410''>a</span> <span m=''4305470''>portion</span>
  <span m=''4305990''>that''s</span> <span m=''4306760''>used</span> <span m=''4307870''>in</span>
  <span m=''4308030''>the</span> <span m=''4308140''>TO</span> <span m=''4308380''>space,</span>
  <span m=''4309150''>and</span> <span m=''4309320''>then</span> <span m=''4309450''>an</span>
  <span m=''4309590''>unused</span> <span m=''4310110''>portion</span> <span m=''4310880''>that</span>
  <span m=''4311010''>I''m</span> <span m=''4311080''>going</span> <span m=''4311160''>to</span>
  <span m=''4311210''>be</span> <span m=''4311410''>able</span> <span m=''4311540''>to</span>
  <span m=''4311630''>do</span> <span m=''4311780''>allocations</span> <span m=''4312500''>out</span>
  <span m=''4312680''>of</span> <span m=''4312860''>for</span> <span m=''4312950''>the</span>
  <span m=''4313160''>next</span> <span m=''4313370''>pass</span> <span m=''4313740''>around.</span>
  </p><p><span m=''4315900''>So</span> <span m=''4316990''>what</span> <span m=''4317140''>I</span>
  <span m=''4317220''>do</span> <span m=''4317430''>at</span> <span m=''4317530''>that</span>
  <span m=''4317800''>point</span> <span m=''4318020''>is</span> <span m=''4318160''>I</span>
  <span m=''4318240''>make</span> <span m=''4318510''>the</span> <span m=''4318690''>old</span>
  <span m=''4319130''>TO</span> <span m=''4319580''>become</span> <span m=''4319920''>the</span>
  <span m=''4320000''>new</span> <span m=''4320230''>FROM.</span> <span m=''4321260''>So</span>
  <span m=''4321380''>here''s</span> <span m=''4321660''>the</span> <span m=''4321740''>new</span>
  <span m=''4321920''>FROM.</span> <span m=''4322980''>This</span> <span m=''4323200''>is</span>
  <span m=''4323520''>available</span> <span m=''4323970''>space.</span> <span m=''4324740''>And</span>
  <span m=''4325040''>now</span> <span m=''4325250''>what</span> <span m=''4325380''>I</span>
  <span m=''4325470''>do</span> <span m=''4325780''>is</span> <span m=''4326040''>I</span>
  <span m=''4326150''>extend</span> <span m=''4326710''>this</span> <span m=''4327660''>space,</span>
  <span m=''4328060''>if</span> <span m=''4328190''>necessary,</span> <span m=''4328820''>to</span>
  <span m=''4328940''>make</span> <span m=''4329250''>the</span> <span m=''4329350''>new</span>
  <span m=''4329800''>heap</span> <span m=''4330120''>space</span> <span m=''4330500''>that</span>
  <span m=''4330700''>I''m</span> <span m=''4330760''>going</span> <span m=''4330870''>to</span>
  <span m=''4330980''>allocate</span> <span m=''4331580''>out</span> <span m=''4331810''>of</span>
  <span m=''4332230''>equal</span> <span m=''4332700''>in</span> <span m=''4332800''>size</span>
  <span m=''4333310''>to</span> <span m=''4333460''>the</span> <span m=''4333550''>used</span>
  <span m=''4333890''>space.</span> <span m=''4336130''>And</span> <span m=''4336230''>the</span>
  <span m=''4336310''>reason</span> <span m=''4336650''>for</span> <span m=''4336770''>doing</span>
  <span m=''4337090''>this</span> <span m=''4337300''>is</span> <span m=''4337420''>to</span>
  <span m=''4337530''>amortize</span> <span m=''4338000''>the</span> <span m=''4338470''>cost</span>
  <span m=''4338880''>of</span> <span m=''4338980''>going</span> <span m=''4339300''>through</span>
  <span m=''4339680''>all</span> <span m=''4339970''>of</span> <span m=''4340070''>the</span>
  <span m=''4341060''>storage,</span> <span m=''4341600''>so</span> <span m=''4341840''>that
  the</span> <span m=''4342110''>cost</span> <span m=''4342540''>of</span> <span m=''4342640''>going</span>
  <span m=''4343840''>the</span> <span m=''4343930''>garbage</span> <span m=''4344310''>question</span>
  <span m=''4344650''>can</span> <span m=''4344830''>be</span> <span m=''4345010''>amortized</span>
  <span m=''4345660''>against</span> <span m=''4346070''>what''s</span> <span m=''4346230''>used.</span>
  <span m=''4346680''>If</span> <span m=''4346950''>I</span> <span m=''4347180''>didn''t</span>
  <span m=''4347410''>extend</span> <span m=''4347890''>this,</span> <span m=''4348100''>I</span>
  <span m=''4348170''>might</span> <span m=''4348380''>have</span> <span m=''4348490''>only</span>
  <span m=''4348730''>freed</span> <span m=''4349010''>up</span> <span m=''4349140''>a</span>
  <span m=''4349230''>tiny</span> <span m=''4349650''>little</span> <span m=''4349880''>bit</span>
  <span m=''4350050''>of</span> <span m=''4350110''>space,</span> <span m=''4351990''>and</span>
  <span m=''4352150''>now</span> <span m=''4352330''>when</span> <span m=''4352480''>I</span>
  <span m=''4352550''>run</span> <span m=''4352790''>out</span> <span m=''4352940''>of</span>
  <span m=''4352980''>that</span> <span m=''4353170''>space,</span> <span m=''4353520''>I''ll</span>
  <span m=''4353660''>run</span> <span m=''4353820''>the</span> <span m=''4353900''>garbage</span>
  <span m=''4354340''>collector</span> <span m=''4354690''>going</span> <span m=''4354960''>over</span>
  <span m=''4355210''>all</span> <span m=''4355520''>the</span> <span m=''4355660''>elements,</span>
  <span m=''4357850''>but I''ll</span> <span m=''4358010''>only</span> <span m=''4358330''>have</span>
  <span m=''4358460''>gotten</span> <span m=''4358820''>a</span> <span m=''4358870''>few</span>
  <span m=''4359160''>elements</span> <span m=''4359630''>[INAUDIBLE].</span> <span
  m=''4359800''>So</span> <span m=''4359930''>what</span> <span m=''4360080''>I</span>
  <span m=''4360120''>want</span> <span m=''4360300''>to</span> <span m=''4360360''>do</span>
  <span m=''4360560''>is</span> <span m=''4360710''>make</span> <span m=''4360920''>sure</span>
  <span m=''4361060''>that</span> <span m=''4361180''>I''ve</span> <span m=''4361340''>done</span>
  <span m=''4361560''>at</span> <span m=''4361620''>least</span> <span m=''4362020''>a</span>
  <span m=''4362070''>certain</span> <span m=''4362380''>number</span> <span m=''4362590''>of</span>
  <span m=''4362660''>allocations</span> <span m=''4363730''>proportional</span> <span
  m=''4364420''>to</span> <span m=''4364530''>the</span> <span m=''4364640''>number</span>
  <span m=''4365300''>that</span> <span m=''4365430''>I''m</span> <span m=''4365580''>going</span>
  <span m=''4365750''>to</span> <span m=''4365800''>have</span> <span m=''4365980''>to</span>
  <span m=''4366150''>walk</span> <span m=''4366500''>over</span> <span m=''4367230''>in</span>
  <span m=''4367370''>order</span> <span m=''4367610''>to</span> <span m=''4367690''>finish
  it.</span> <span m=''4368090''>So</span> <span m=''4368290''>that''s</span> <span
  m=''4368510''>why</span> <span m=''4368680''>you</span> <span m=''4368780''>make</span>
  <span m=''4368970''>this be</span> <span m=''4369360''>the</span> <span m=''4369540''>same</span>
  <span m=''4369770''>size.</span> </p><p><span m=''4370630''>Now</span> <span m=''4370800''>when</span>
  <span m=''4370860''>the</span> <span m=''4370910''>space</span> <span m=''4371350''>runs</span>
  <span m=''4371670''>out,</span> <span m=''4372400''>the new</span> <span m=''4372810''>TO</span>
  <span m=''4373220''>is</span> <span m=''4373340''>allocated</span> <span m=''4374020''>with</span>
  <span m=''4374110''>the</span> <span m=''4374200''>same</span> <span m=''4374550''>size</span>
  <span m=''4375040''>as</span> <span m=''4375180''>FROM.</span> <span m=''4377580''>So</span>
  <span m=''4378430''>if</span> <span m=''4378650''>you</span> <span m=''4378830''>can</span>
  <span m=''4378970''>allocate</span> <span m=''4379550''>it</span> <span m=''4380250''>back</span>
  <span m=''4380700''>in</span> <span m=''4380810''>the</span> <span m=''4380920''>old</span>
  <span m=''4382620''>FROM</span> <span m=''4382880''>space</span> <span m=''4383220''>here,</span>
  <span m=''4383360''>that''s</span> <span m=''4383630''>great.</span> <span m=''4384720''>If</span>
  <span m=''4384850''>there''s</span> <span m=''4385010''>room</span> <span m=''4385240''>here
  to</span> <span m=''4385430''>allocate</span> <span m=''4385690''>it</span> <span
  m=''4385950''>at</span> <span m=''4386040''>the</span> <span m=''4386110''>front,</span>
  <span m=''4386930''>super.</span> <span m=''4387340''>That''s</span> <span m=''4387570''>where
  you</span> <span m=''4387895''>allocate it.</span> <span m=''4388600''>But</span>
  <span m=''4388900''>as</span> <span m=''4389130''>in</span> <span m=''4389240''>this</span>
  <span m=''4389440''>example,</span> <span m=''4390400''>the</span> <span m=''4390830''>FROM</span>
  <span m=''4391140''>space</span> <span m=''4391530''>here</span> <span m=''4391750''>is</span>
  <span m=''4391930''>bigger</span> <span m=''4392320''>than</span> <span m=''4392500''>the</span>
  <span m=''4392580''>space</span> <span m=''4393030''>that</span> <span m=''4393190''>goes</span>
  <span m=''4393460''>up</span> <span m=''4393650''>to</span> <span m=''4393730''>here.</span>
  <span m=''4394770''>So</span> <span m=''4394920''>therefore</span> <span m=''4395430''>what</span>
  <span m=''4395560''>I</span> <span m=''4395650''>do</span> <span m=''4395820''>is</span>
  <span m=''4395930''>I</span> <span m=''4396030''>allocate</span> <span m=''4396355''>it</span>
  <span m=''4396680''>at</span> <span m=''4396800''>the</span> <span m=''4397010''>end,</span>
  <span m=''4399360''>and</span> <span m=''4399560''>then</span> <span m=''4399760''>I</span>
  <span m=''4399830''>go</span> <span m=''4400080''>through</span> <span m=''4400930''>and</span>
  <span m=''4401130''>copy to</span> <span m=''4401500''>here.</span> </p><p><span
  m=''4402600''>Now</span> <span m=''4402910''>if</span> <span m=''4403040''>this</span>
  <span m=''4403220''>ended</span> <span m=''4403470''>up</span> <span m=''4403600''>being</span>
  <span m=''4403800''>used,</span> <span m=''4404750''>then</span> <span m=''4404950''>the</span>
  <span m=''4405030''>next</span> <span m=''4405370''>time</span> <span m=''4405620''>around,</span>
  <span m=''4406040''>I</span> <span m=''4406090''>would</span> <span m=''4406240''>be</span>
  <span m=''4406410''>able</span> <span m=''4406530''>to</span> <span m=''4406610''>reuse</span>
  <span m=''4407060''>this</span> <span m=''4407160''>space</span> <span m=''4407580''>at</span>
  <span m=''4407690''>the</span> <span m=''4407740''>front</span> <span m=''4410400''>for</span>
  <span m=''4410520''>the</span> <span m=''4410620''>next</span> <span m=''4410920''>time
  that</span> <span m=''4411210''>I</span> <span m=''4411320''>flip</span> <span m=''4412070''>the</span>
  <span m=''4412280''>garbage</span> <span m=''4412670''>collection.</span> <span
  m=''4413440''>The</span> <span m=''4413600''>idea</span> <span m=''4413860''>is,</span>
  <span m=''4415360''>if</span> <span m=''4415580''>things</span> <span m=''4415840''>will</span>
  <span m=''4415980''>fit</span> <span m=''4417110''>as</span> <span m=''4417310''>early</span>
  <span m=''4417660''>in</span> <span m=''4417760''>memory</span> <span m=''4418100''>as</span>
  <span m=''4418220''>possible,</span> <span m=''4418680''>that''s</span> <span m=''4418890''>where</span>
  <span m=''4419040''>I</span> <span m=''4419100''>put</span> <span m=''4419350''>them.</span>
  <span m=''4419470''>But if</span> <span m=''4419660''>they</span> <span m=''4419790''>don''t</span>
  <span m=''4420080''>fit,</span> <span m=''4420520''>I</span> <span m=''4420630''>put</span>
  <span m=''4420870''>them</span> <span m=''4421020''>later.</span> <span m=''4421760''>And</span>
  <span m=''4422090''>you</span> <span m=''4422260''>can</span> <span m=''4422430''>prove,</span>
  <span m=''4422800''>if</span> <span m=''4422930''>you</span> <span m=''4423060''>do</span>
  <span m=''4423270''>this,</span> <span m=''4423550''>that</span> <span m=''4423660''>the</span>
  <span m=''4423730''>virtual</span> <span m=''4424110''>memory</span> <span m=''4424420''>space</span>
  <span m=''4424830''>used</span> <span m=''4425930''>is</span> <span m=''4426450''>order</span>
  <span m=''4426750''>1</span> <span m=''4427040''>times</span> <span m=''4427400''>the</span>
  <span m=''4427540''>optimal,</span> <span m=''4428190''>where</span> <span m=''4428250''>you''re</span>
  <span m=''4428380''>getting</span> <span m=''4428720''>nearly</span> <span m=''4429110''>the</span>
  <span m=''4429200''>best</span> <span m=''4429620''>virtual</span> <span m=''4430010''>memory</span>
  <span m=''4430320''>space</span> <span m=''4430730''>used</span> <span m=''4431330''>compared</span>
  <span m=''4431750''>to</span> <span m=''4431810''>the</span> <span m=''4431890''>amount</span>
  <span m=''4432560''>of</span> <span m=''4433900''>items</span> <span m=''4434380''>that</span>
  <span m=''4434480''>are</span> <span m=''4434580''>in</span> <span m=''4435400''>use</span>
  <span m=''4435790''>by</span> <span m=''4435950''>the</span> <span m=''4436050''>user</span>
  <span m=''4436430''>at</span> <span m=''4436490''>any</span> <span m=''4436670''>time.</span>
  <span m=''4438460''>So it</span> <span m=''4438620''>keeps</span> <span m=''4438870''>everything</span>
  <span m=''4439270''>sort</span> <span m=''4439420''>of</span> <span m=''4439500''>compact</span>
  <span m=''4440510''>towards</span> <span m=''4440880''>the</span> <span m=''4440960''>front</span>
  <span m=''4441250''>end</span> <span m=''4441480''>here.</span> </p><p><span m=''4442310''>So</span>
  <span m=''4442450''>in</span> <span m=''4442500''>this</span> <span m=''4442690''>case,</span>
  <span m=''4442910''>I</span> <span m=''4443000''>had</span> <span m=''4443200''>to</span>
  <span m=''4443260''>allocate</span> <span m=''4443750''>to</span> <span m=''4443880''>here.</span>
  <span m=''4444360''>If</span> <span m=''4444590''>the</span> <span m=''4444680''>use</span>
  <span m=''4445050''>had</span> <span m=''4445200''>been</span> <span m=''4445310''>very</span>
  <span m=''4445550''>small,</span> <span m=''4446510''>I</span> <span m=''4446630''>could
  have</span> <span m=''4446920''>allocated</span> <span m=''4447410''>just</span>
  <span m=''4447610''>a</span> <span m=''4447660''>very</span> <span m=''4447960''>small</span>
  <span m=''4448380''>amount</span> <span m=''4448740''>for the</span> <span m=''4449140''>heap.</span>
  <span m=''4449630''>When</span> <span m=''4449790''>I</span> <span m=''4449950''>was</span>
  <span m=''4450100''>done,</span> <span m=''4451430''>the</span> <span m=''4451610''>new</span>
  <span m=''4451800''>TO</span> <span m=''4452030''>space</span> <span m=''4452360''>would
  have</span> <span m=''4452620''>fit</span> <span m=''4452730''>at</span> <span m=''4452820''>the</span>
  <span m=''4452900''>beginning.</span> <span m=''4453550''>I</span> <span m=''4453630''>would</span>
  <span m=''4453750''>have</span> <span m=''4453840''>allocated</span> <span m=''4454205''>it</span>
  <span m=''4454570''>at</span> <span m=''4454760''>the</span> <span m=''4454830''>beginning.</span>
  <span m=''4456380''>And</span> <span m=''4456590''>it''s</span> <span m=''4457120''>a</span>
  <span m=''4457620''>nice</span> <span m=''4457970''>little</span> <span m=''4458180''>exercise,</span>
  <span m=''4458780''>for</span> <span m=''4458890''>those</span> <span m=''4459190''>of</span>
  <span m=''4459290''>you</span> <span m=''4459460''>who</span> <span m=''4459550''>are</span>
  <span m=''4460070''>analytically</span> <span m=''4460730''>inclined,</span> <span
  m=''4461640''>to</span> <span m=''4461760''>figure</span> <span m=''4462070''>out</span>
  <span m=''4462300''>what</span> <span m=''4462450''>the</span> <span m=''4462530''>constant</span>
  <span m=''4463050''>is</span> <span m=''4463220''>here,</span> <span m=''4464970''>because</span>
  <span m=''4465540''>it''s</span> <span m=''4465790''>a</span> <span m=''4466210''>little</span>
  <span m=''4466500''>bit</span> <span m=''4466630''>of</span> <span m=''4466710''>a</span>
  <span m=''4466740''>game</span> <span m=''4467070''>to</span> <span m=''4467130''>figure</span>
  <span m=''4467400''>out</span> <span m=''4467570''>what</span> <span m=''4467800''>the</span>
  <span m=''4468740''>amortized</span> <span m=''4469220''>constant,</span> <span
  m=''4469600''>for</span> <span m=''4469700''>those</span> <span m=''4469980''>who</span>
  <span m=''4470390''>have</span> <span m=''4470580''>some</span> <span m=''4470730''>algorithmic</span>
  <span m=''4472540''>energy</span> <span m=''4473090''>and</span> <span m=''4474930''>our</span>
  <span m=''4475080''>confident</span> <span m=''4475470''>about</span> <span m=''4477060''>working</span>
  <span m=''4477640''>in</span> <span m=''4477700''>this</span> <span m=''4477850''>kind</span>
  <span m=''4478000''>of</span> <span m=''4478080''>thing</span> <span m=''4478370''>instead</span>
  <span m=''4478500''>of</span> <span m=''4478550''>studying</span> <span m=''4478880''>for</span>
  <span m=''4478970''>the</span> <span m=''4479060''>quiz.</span> </p><p><span m=''4483460''>So</span>
  <span m=''4484580''>dynamic</span> <span m=''4485020''>storage</span> <span m=''4485360''>allocation.</span>
  <span m=''4485880''>Hugely</span> <span m=''4486470''>interesting</span> <span m=''4486940''>area.</span>
  <span m=''4488960''>Lots</span> <span m=''4489360''>is</span> <span m=''4489510''>known</span>
  <span m=''4489890''>and</span> <span m=''4489960''>lots</span> <span m=''4490290''>is</span>
  <span m=''4490440''>unknown.</span> <span m=''4490930''>For</span> <span m=''4491050''>example,</span>
  <span m=''4491340''>I</span> <span m=''4491380''>mentioned</span> <span m=''4491800''>coalescing.</span>
  <span m=''4492430''>We</span> <span m=''4492540''>really</span> <span m=''4492810''>don''t</span>
  <span m=''4493020''>understand</span> <span m=''4493530''>coalescing.</span> <span
  m=''4494460''>Disaster</span> <span m=''4494950''>people have</span> <span m=''4495230''>been</span>
  <span m=''4495390''>doing</span> <span m=''4495610''>it</span> <span m=''4495710''>for</span>
  <span m=''4495830''>50</span> <span m=''4496150''>years</span> <span m=''4496480''>or</span>
  <span m=''4496550''>more.</span> <span m=''4497680''>We</span> <span m=''4497820''>do</span>
  <span m=''4497990''>not</span> <span m=''4498200''>understand</span> <span m=''4498730''>coalescing.</span>
  </p><p><span m=''4501490''>There</span> <span m=''4501600''>are</span> <span m=''4501620''>a</span>
  <span m=''4501670''>lot</span> <span m=''4501990''>of</span> <span m=''4502480''>strategies</span>
  <span m=''4503210''>that</span> <span m=''4503330''>people</span> <span m=''4503590''>have</span>
  <span m=''4503840''>studied,</span> <span m=''4504190''>things</span> <span m=''4504430''>like</span>
  <span m=''4504590''>the</span> <span m=''4504660''>buddy</span> <span m=''4504950''>system,</span>
  <span m=''4505310''>I</span> <span m=''4505390''>mentioned.</span> <span m=''4506300''>There</span>
  <span m=''4506390''>are</span> <span m=''4506420''>other</span> <span m=''4506650''>types</span>
  <span m=''4506940''>of</span> <span m=''4507030''>garbage</span> <span m=''4507390''>collectors</span>
  <span m=''4507810''>called</span> <span m=''4508640''>mark</span> <span m=''4509050''>and</span>
  <span m=''4509190''>sweep</span> <span m=''4509530''>garbage</span> <span m=''4509930''>collection.</span>
  <span m=''4510820''>Those</span> <span m=''4511020''>are</span> <span m=''4511100''>typically</span>
  <span m=''4511570''>inferior</span> <span m=''4512350''>to</span> <span m=''4512460''>the</span>
  <span m=''4512550''>copying</span> <span m=''4513110''>garbage</span> <span m=''4513500''>collection,</span>
  <span m=''4514380''>because</span> <span m=''4516010''>they</span> <span m=''4517470''>leave</span>
  <span m=''4517800''>you</span> <span m=''4517940''>with</span> <span m=''4518230''>a</span>
  <span m=''4519070''>memory</span> <span m=''4519460''>that</span> <span m=''4519580''>isn''t</span>
  <span m=''4519860''>compact.</span> <span m=''4521980''>And</span> <span m=''4522140''>so</span>
  <span m=''4522250''>you</span> <span m=''4522390''>end</span> <span m=''4522600''>up</span>
  <span m=''4522730''>using</span> <span m=''4523100''>more</span> <span m=''4523340''>and</span>
  <span m=''4523410''>more</span> <span m=''4523690''>of</span> <span m=''4523760''>your</span>
  <span m=''4523920''>virtual</span> <span m=''4524390''>memory,</span> <span m=''4525800''>because</span>
  <span m=''4526150''>you''re</span> <span m=''4526420''>leaving</span> <span m=''4526800''>things</span>
  <span m=''4527070''>in</span> <span m=''4527180''>place.</span> <span m=''4527560''>On</span>
  <span m=''4527640''>the</span> <span m=''4527730''>other</span> <span m=''4527840''>hand,</span>
  <span m=''4528000''>you</span> <span m=''4528120''>leave</span> <span m=''4528380''>things</span>
  <span m=''4528610''>in</span> <span m=''4528710''>place</span> <span m=''4529320''>so</span>
  <span m=''4529500''>there''s</span> <span m=''4529690''>no</span> <span m=''4529840''>need</span>
  <span m=''4530100''>to</span> <span m=''4530180''>move</span> <span m=''4530420''>pointers.</span>
  <span m=''4532100''>So</span> <span m=''4532620''>that can</span> <span m=''4532910''>be</span>
  <span m=''4533020''>a</span> <span m=''4533060''>valuable</span> <span m=''4533450''>thing.</span>
  </p><p><span m=''4533970''>There''s</span> <span m=''4534120''>things</span> <span
  m=''4534330''>called</span> <span m=''4534550''>generational</span> <span m=''4535220''>garbage</span>
  <span m=''4535620''>collection.</span> <span m=''4536650''>Generational</span> <span
  m=''4537180''>garbage</span> <span m=''4537480''>collectors</span> <span m=''4537840''>realize</span>
  <span m=''4538840''>that</span> <span m=''4539350''>things</span> <span m=''4539660''>that</span>
  <span m=''4539840''>are</span> <span m=''4540380''>allocated</span> <span m=''4542210''>typically</span>
  <span m=''4542790''>are</span> <span m=''4542850''>freed</span> <span m=''4543330''>very</span>
  <span m=''4543600''>soon</span> <span m=''4543930''>thereafter,</span> <span m=''4545900''>and</span>
  <span m=''4546100''>so</span> <span m=''4546240''>therefore,</span> <span m=''4546690''>if</span>
  <span m=''4546790''>you</span> <span m=''4546890''>especially</span> <span m=''4547580''>take</span>
  <span m=''4547850''>care</span> <span m=''4548510''>of</span> <span m=''4548660''>the</span>
  <span m=''4548750''>things</span> <span m=''4549020''>that</span> <span m=''4549110''>are</span>
  <span m=''4549430''>allocated</span> <span m=''4550130''>and</span> <span m=''4550370''>guess</span>
  <span m=''4550680''>that</span> <span m=''4550840''>they''re</span> <span m=''4550950''>going</span>
  <span m=''4551080''>to</span> <span m=''4551130''>be</span> <span m=''4553300''>used</span>
  <span m=''4553680''>again,</span> <span m=''4554330''>and</span> <span m=''4554490''>that</span>
  <span m=''4554590''>things</span> <span m=''4554890''>that</span> <span m=''4554990''>haven''t</span>
  <span m=''4555480''>been</span> <span m=''4555640''>deallocated</span> <span m=''4556310''>for</span>
  <span m=''4556420''>a</span> <span m=''4556520''>long</span> <span m=''4556790''>time</span>
  <span m=''4557160''>are</span> <span m=''4557270''>very</span> <span m=''4557600''>unlikely</span>
  <span m=''4558240''>to</span> <span m=''4558360''>be</span> <span m=''4558980''>allocated,</span>
  <span m=''4559800''>you</span> <span m=''4559990''>can</span> <span m=''4560170''>get</span>
  <span m=''4560530''>better</span> <span m=''4561780''>performance</span> <span m=''4562410''>out</span>
  <span m=''4562540''>of</span> <span m=''4562610''>a</span> <span m=''4562650''>garbage</span>
  <span m=''4563050''>collector.</span> </p><p><span m=''4564580''>There''s</span>
  <span m=''4564990''>real</span> <span m=''4565300''>time</span> <span m=''4565590''>garbage</span>
  <span m=''4565960''>collection.</span> <span m=''4566730''>So</span> <span m=''4566890''>this</span>
  <span m=''4567070''>is</span> <span m=''4567270''>what</span> <span m=''4567460''>I''ve</span>
  <span m=''4567670''>explained,</span> <span m=''4568120''>is</span> <span m=''4568220''>what''s</span>
  <span m=''4568430''>called</span> <span m=''4568710''>a</span> <span m=''4568810''>stop</span>
  <span m=''4569210''>and</span> <span m=''4569340''>copy</span> <span m=''4570160''>garbage</span>
  <span m=''4570520''>collector.</span> <span m=''4571500''>Meaning</span> <span m=''4571830''>that</span>
  <span m=''4572430''>when</span> <span m=''4572630''>you</span> <span m=''4572740''>run</span>
  <span m=''4572920''>out of</span> <span m=''4573040''>storage,</span> <span m=''4573410''>oops!</span>
  <span m=''4573560''>Stop</span> <span m=''4573910''>the</span> <span m=''4574170''>world,</span>
  <span m=''4574430''>run</span> <span m=''4574630''>the</span> <span m=''4574710''>garbage</span>
  <span m=''4575040''>collector.</span> <span m=''4575430''>There</span> <span m=''4575640''>are</span>
  <span m=''4575750''>real</span> <span m=''4575980''>time</span> <span m=''4576230''>garbage</span>
  <span m=''4576570''>collectors</span> <span m=''4577050''>which,</span> <span m=''4577220''>whenever</span>
  <span m=''4577690''>you</span> <span m=''4577880''>do</span> <span m=''4578310''>an</span>
  <span m=''4578490''>allocation,</span> <span m=''4580130''>it</span> <span m=''4580330''>goes</span>
  <span m=''4580680''>and</span> <span m=''4580790''>it</span> <span m=''4580940''>does</span>
  <span m=''4581190''>a</span> <span m=''4581240''>few</span> <span m=''4581460''>cycles</span>
  <span m=''4581920''>of</span> <span m=''4581980''>garbage</span> <span m=''4582370''>collection,</span>
  <span m=''4584710''>and</span> <span m=''4584910''>is</span> <span m=''4585240''>such</span>
  <span m=''4585620''>that</span> <span m=''4585760''>you</span> <span m=''4585850''>can</span>
  <span m=''4585980''>always</span> <span m=''4586390''>keep</span> <span m=''4586680''>up</span>
  <span m=''4587360''>with</span> <span m=''4587570''>the</span> <span m=''4587780''>allocations</span>
  <span m=''4588600''>and</span> <span m=''4588750''>deallocations</span> <span m=''4589470''>going</span>
  <span m=''4589740''>on.</span> <span m=''4590060''>By</span> <span m=''4590190''>doing</span>
  <span m=''4590410''>a</span> <span m=''4590450''>few</span> <span m=''4590680''>cycles,</span>
  <span m=''4591820''>you</span> <span m=''4591990''>eventually</span> <span m=''4592440''>get</span>
  <span m=''4592730''>to</span> <span m=''4593720''>garbage</span> <span m=''4594070''>collect</span>
  <span m=''4594400''>everything,</span> <span m=''4595390''>but</span> <span m=''4595540''>you</span>
  <span m=''4595640''>do</span> <span m=''4595850''>it</span> <span m=''4596260''>intermixed,</span>
  <span m=''4596860''>so</span> <span m=''4596990''>that</span> <span m=''4597595''>you''re</span>
  <span m=''4597960''>slowing</span> <span m=''4598320''>everything</span> <span m=''4598710''>down</span>
  <span m=''4598950''>by</span> <span m=''4599080''>a constant</span> <span m=''4599420''>amount,</span>
  <span m=''4599700''>rather</span> <span m=''4599990''>than</span> <span m=''4600140''>running</span>
  <span m=''4600510''>and</span> <span m=''4600630''>suddenly,</span> <span m=''4601360''>OK,</span>
  <span m=''4601590''>your</span> <span m=''4601730''>robot</span> <span m=''4602040''>arm</span>
  <span m=''4602260''>is</span> <span m=''4602380''>going</span> <span m=''4602560''>like</span>
  <span m=''4602760''>this,</span> <span m=''4602990''>oops,</span> <span m=''4603630''>garbage</span>
  <span m=''4603920''>collect,</span> <span m=''4604400''>garbage collect,</span>
  <span m=''4604630''>garbage</span> <span m=''4604890''>collect,</span> <span m=''4605276''>[CREAKING
  SOUND].</span> <span m=''4606850''>So</span> <span m=''4607000''>you can</span>
  <span m=''4607130''>have</span> <span m=''4607360''>your</span> <span m=''4607480''>robot</span>
  <span m=''4607780''>arm</span> <span m=''4607990''>move</span> <span m=''4608180''>smoothly,</span>
  <span m=''4608730''>because</span> <span m=''4609570''>it''s</span> <span m=''4610160''>paying</span>
  <span m=''4610470''>the</span> <span m=''4610560''>price</span> <span m=''4611610''>all</span>
  <span m=''4611790''>the</span> <span m=''4611860''>way.</span> <span m=''4612080''>It''s</span>
  <span m=''4612250''>not</span> <span m=''4612440''>stopping</span> <span m=''4612920''>and
  going.</span> </p><p><span m=''4614430''>There</span> <span m=''4614890''>is</span>
  <span m=''4615180''>multi-threaded</span> <span m=''4615970''>storage</span> <span
  m=''4616540''>allocation.</span> <span m=''4617570''>What</span> <span m=''4617710''>happens</span>
  <span m=''4618160''>when</span> <span m=''4618310''>you</span> <span m=''4618630''>have</span>
  <span m=''4621580''>a</span> <span m=''4622980''>multi-threaded</span> <span m=''4623750''>environment</span>
  <span m=''4624390''>where you</span> <span m=''4624500''>have</span> <span m=''4624600''>many</span>
  <span m=''4624850''>processors</span> <span m=''4626010''>that are</span> <span
  m=''4626220''>all</span> <span m=''4626490''>allocating</span> <span m=''4627040''>out</span>
  <span m=''4627170''>of</span> <span m=''4627240''>the</span> <span m=''4627290''>same</span>
  <span m=''4627620''>pool?</span> <span m=''4628040''>How</span> <span m=''4628270''>do</span>
  <span m=''4628340''>they</span> <span m=''4628500''>organize</span> <span m=''4629130''>it?</span>
  <span m=''4629790''>You can</span> <span m=''4630020''>have</span> <span m=''4630250''>the</span>
  <span m=''4630500''>interesting</span> <span m=''4630920''>things</span> <span m=''4631260''>going</span>
  <span m=''4631550''>there</span> <span m=''4631760''>where</span> <span m=''4631920''>things</span>
  <span m=''4632200''>are</span> <span m=''4632300''>allocated</span> <span m=''4632960''>on</span>
  <span m=''4633100''>one</span> <span m=''4633960''>processor,</span> <span m=''4635290''>and</span>
  <span m=''4635460''>then</span> <span m=''4635610''>get</span> <span m=''4635990''>deallocated</span>
  <span m=''4636600''>on</span> <span m=''4636730''>another.</span> <span m=''4637800''>And</span>
  <span m=''4637960''>if</span> <span m=''4638050''>you''re</span> <span m=''4638170''>not</span>
  <span m=''4638460''>careful,</span> <span m=''4638910''>you</span> <span m=''4639000''>have</span>
  <span m=''4639100''>something</span> <span m=''4639430''>like</span> <span m=''4639620''>a</span>
  <span m=''4639680''>memory</span> <span m=''4640050''>leak</span> <span m=''4640290''>going</span>
  <span m=''4640620''>on,</span> <span m=''4641190''>which</span> <span m=''4641350''>is</span>
  <span m=''4641460''>called</span> <span m=''4641680''>memory</span> <span m=''4642030''>drift,</span>
  <span m=''4643330''>where</span> <span m=''4643470''>the</span> <span m=''4643570''>memory</span>
  <span m=''4644420''>gets</span> <span m=''4644600''>allocated</span> <span m=''4645140''>on</span>
  <span m=''4645230''>one, and</span> <span m=''4645550''>one</span> <span m=''4645760''>guy''s</span>
  <span m=''4646040''>busy</span> <span m=''4646820''>creating it,</span> <span m=''4647280''>and
  it</span> <span m=''4647660''>keeps</span> <span m=''4647900''>getting</span> <span
  m=''4648120''>deallocated</span> <span m=''4648890''>on</span> <span m=''4649020''>the</span>
  <span m=''4649160''>other,</span> <span m=''4649820''>but</span> <span m=''4649990''>never</span>
  <span m=''4650200''>gets</span> <span m=''4650360''>recycled</span> <span m=''4650940''>back</span>
  <span m=''4651270''>to</span> <span m=''4651370''>the</span> <span m=''4651460''>guy</span>
  <span m=''4651720''>who</span> <span m=''4651830''>needs</span> <span m=''4652140''>it.</span>
  <span m=''4653210''>And</span> <span m=''4653390''>so</span> <span m=''4653540''>how</span>
  <span m=''4653800''>is</span> <span m=''4654160''>it that</span> <span m=''4654270''>you</span>
  <span m=''4654400''>figure</span> <span m=''4654810''>out</span> <span m=''4655280''>to</span>
  <span m=''4655370''>make</span> <span m=''4655570''>sure</span> <span m=''4655750''>that</span>
  <span m=''4656280''>memory</span> <span m=''4656580''>drift</span> <span m=''4657180''>doesn''t</span>
  <span m=''4657450''>end</span> <span m=''4657670''>up</span> <span m=''4657750''>having</span>
  <span m=''4658060''>you</span> <span m=''4658180''>grow</span> <span m=''4658560''>your</span>
  <span m=''4659020''>memory?</span> <span m=''4659590''>In fact,</span> <span m=''4659860''>many,</span>
  <span m=''4660130''>many</span> <span m=''4660890''>garbage</span> <span m=''4661270''>collectors</span>
  <span m=''4662050''>that are</span> <span m=''4662250''>out</span> <span m=''4662450''>there</span>
  <span m=''4662580''>have</span> <span m=''4662760''>this</span> <span m=''4663580''>memory</span>
  <span m=''4663890''>drift</span> <span m=''4664190''>problem</span> <span m=''4664600''>for</span>
  <span m=''4664860''>multi-threaded</span> <span m=''4665500''>storage</span> <span
  m=''4665910''>allocation.</span> </p><p><span m=''4666710''>There''s</span> <span
  m=''4666820''>also</span> <span m=''4667060''>parallel</span> <span m=''4667590''>garbage</span>
  <span m=''4667970''>collection.</span> <span m=''4668740''>How</span> <span m=''4668950''>do</span>
  <span m=''4669070''>you,</span> <span m=''4669290''>in</span> <span m=''4669410''>a</span>
  <span m=''4669900''>parallel</span> <span m=''4670350''>environment,</span> <span
  m=''4670810''>have</span> <span m=''4671030''>the</span> <span m=''4671110''>garbage</span>
  <span m=''4671480''>collector</span> <span m=''4671850''>going</span> <span m=''4672160''>on</span>
  <span m=''4672310''>as</span> <span m=''4672430''>a</span> <span m=''4672490''>separate</span>
  <span m=''4672920''>process</span> <span m=''4673790''>while</span> <span m=''4674320''>you</span>
  <span m=''4674470''>have</span> <span m=''4674660''>other</span> <span m=''4674920''>things</span>
  <span m=''4675240''>going</span> <span m=''4675530''>on</span> <span m=''4675690''>at</span>
  <span m=''4675760''>the</span> <span m=''4675830''>same</span> <span m=''4676110''>time?</span>
  <span m=''4676670''>So</span> <span m=''4676810''>a</span> <span m=''4676840''>huge,</span>
  <span m=''4677470''>huge,</span> <span m=''4677790''>huge</span> <span m=''4678610''>area</span>
  <span m=''4679110''>of</span> <span m=''4679350''>storage.</span> <span m=''4679960''>And</span>
  <span m=''4680310''>for</span> <span m=''4680520''>our</span> <span m=''4681210''>next</span>
  <span m=''4681530''>lab,</span> <span m=''4682010''>lab</span> <span m=''4683140''>3,</span>
  <span m=''4684240''>you''ll</span> <span m=''4684390''>be</span> <span m=''4684540''>building</span>
  <span m=''4684880''>your</span> <span m=''4685070''>own</span> <span m=''4685240''>storage</span>
  <span m=''4685620''>allocator.</span> <span m=''4686100''>So</span> <span m=''4686220''>you</span>
  <span m=''4686330''>have</span> <span m=''4686430''>a</span> <span m=''4686470''>lot</span>
  <span m=''4686650''>of</span> <span m=''4686720''>fun</span> <span m=''4686920''>with</span>
  <span m=''4687030''>this.</span> <span m=''4688880''>[? Reid ?]</span> <span m=''4689130''>says</span>
  <span m=''4689370''>this</span> <span m=''4689540''>is</span> <span m=''4689650''>his</span>
  <span m=''4689830''>favorite</span> <span m=''4690190''>lab.</span> </p><p><span
  m=''4693560''>Great.</span> <span m=''4693820''>Any</span> <span m=''4693980''>questions?</span>
  <span m=''4697560''>OK.</span> <span m=''4697910''>Good</span> <span m=''4698100''>luck</span>
  <span m=''4698310''>on</span> <span m=''4698400''>the</span> <span m=''4698480''>quiz</span>
  <span m=''4698760''>next</span> <span m=''4699000''>time.</span> </p>'
uid: 7bddd3a5-edad-7767-9f55-10757575b5a8
---
