---
about_this_resource_text: <p><strong>Description:</strong> Lecture covering the impact
  of synchronization and memory on parallel performance, using OpenMP instead of Cilk.
  Topics include granularity of parallelism, true and false sharing, and load balancing.</p>
  <p><strong>Speaker:</strong> Saman Amarasinghe</p>
content_type: resource
course_id: 6-172-performance-engineering-of-software-systems-fall-2010
embedded_media:
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.172F10/MIT6_172_F10_lec17_300k.mp4
  parent_uid: ce8bc21dbf7722d15cf763b66e912439
  title: Video-Internet Archive-MP4
  type: Video
  uid: 3ed11bf48cce02907b485818f7f4f882
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/itunes-u/lecture-17-performance-issues/id481759887?i=109649102
  parent_uid: ce8bc21dbf7722d15cf763b66e912439
  title: Video-iTunes U-MP4
  type: Video
  uid: 15e7fcce26e9a56d7c7aefb1c8023978
- id: Video-YouTube-Stream
  media_location: MFmxByf9x88
  parent_uid: ce8bc21dbf7722d15cf763b66e912439
  title: Video-YouTube-Stream
  type: Video
  uid: 2a602747142cba50926b5c886b2d3872
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/MFmxByf9x88/default.jpg
  parent_uid: ce8bc21dbf7722d15cf763b66e912439
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 99e1c2538540ab507daadb7f456b63a4
- id: MIT6_172F10_lec17.pdf
  parent_uid: ce8bc21dbf7722d15cf763b66e912439
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-17-performance-issues-in-parallelization/MIT6_172F10_lec17.pdf
  title: MIT6_172F10_lec17.pdf
  type: null
  uid: 5caee9b11d8dcc3bef46bb2ed9c100de
- id: 3Play-3PlayYouTubeid-MP4
  media_location: MFmxByf9x88
  parent_uid: ce8bc21dbf7722d15cf763b66e912439
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 075c174f394ad9acd8a4ed59871ab44d
- id: MFmxByf9x88.srt
  parent_uid: ce8bc21dbf7722d15cf763b66e912439
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-17-performance-issues-in-parallelization/MFmxByf9x88.srt
  title: 3play caption file
  type: null
  uid: a65b225bfe63283a8cb848355bf3f9b4
- id: MFmxByf9x88.pdf
  parent_uid: ce8bc21dbf7722d15cf763b66e912439
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-17-performance-issues-in-parallelization/MFmxByf9x88.pdf
  title: 3play pdf file
  type: null
  uid: 7e1ab08636565c61f6c59036e5cc9f8f
- id: Caption-3Play YouTube id-SRT
  parent_uid: ce8bc21dbf7722d15cf763b66e912439
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: d31c365bfbd07b54c96071ca52de2499
- id: Transcript-3Play YouTube id-PDF
  parent_uid: ce8bc21dbf7722d15cf763b66e912439
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 9866d130aff2c579183c66a6073b4e65
file: null
file_size: null
inline_embed_id: 9362944lecture17:performanceissuesinparallelization91659756
layout: video
license: https://creativecommons.org/licenses/by-nc-sa/4.0/
order_index: 192
parent_uid: 24169d0487e846a39c316276f85b8cb5
related_resources_text: ''
short_url: lecture-17-performance-issues-in-parallelization
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-17-performance-issues-in-parallelization
title: 'Lecture 17: Performance Issues in Parallelization'
transcript: '<p><span m=''120''>The</span> <span m=''190''>following</span> <span
  m=''630''>content</span> <span m=''1230''>is</span> <span m=''1340''>provided</span>
  <span m=''1790''>under</span> <span m=''2070''>a</span> <span m=''2090''>Creative</span>
  <span m=''2500''>Commons</span> <span m=''2910''>license.</span> <span m=''3910''>Your</span>
  <span m=''4200''>support</span> <span m=''4700''>will</span> <span m=''4870''>help</span>
  <span m=''5100''>MIT</span> <span m=''5580''>OpenCourseWare</span> <span m=''6360''>continue</span>
  <span m=''6870''>to</span> <span m=''6950''>offer</span> <span m=''7380''>high</span>
  <span m=''7590''>quality</span> <span m=''8119''>educational</span> <span m=''8740''>resources</span>
  <span m=''9390''>for</span> <span m=''9520''>free.</span> <span m=''10600''>To</span>
  <span m=''10730''>make</span> <span m=''10930''>a</span> <span m=''10980''>donation</span>
  <span m=''11620''>or</span> <span m=''11930''>view</span> <span m=''12340''>additional</span>
  <span m=''12800''>materials</span> <span m=''13340''>from</span> <span m=''13500''>hundreds</span>
  <span m=''13930''>of</span> <span m=''14040''>MIT</span> <span m=''14460''>courses,</span>
  <span m=''15460''>visit</span> <span m=''15790''>MIT</span> <span m=''16219''>OpenCourseWare</span>
  <span m=''17250''>at</span> <span m=''17430''>ocw.mit.edu.</span> </p><p><span m=''23660''>PROFESSOR:
  Let''s</span> <span m=''23890''>get</span> <span m=''24040''>started.</span> <span
  m=''25450''>So</span> <span m=''25660''>today,</span> <span m=''26520''>I''m</span>
  <span m=''26830''>going</span> <span m=''27170''>to</span> <span m=''27750''>talk</span>
  <span m=''28030''>a little</span> <span m=''28310''>bit</span> <span m=''28590''>more</span>
  <span m=''28990''>about</span> <span m=''29750''>performance</span> <span m=''30400''>issues</span>
  <span m=''31060''>in</span> <span m=''31500''>parallelization.</span> <span m=''33200''>A
  little</span> <span m=''33430''>bit</span> <span m=''33620''>more</span> <span m=''34030''>out</span>
  <span m=''34280''>of</span> <span m=''35430''>the</span> <span m=''35870''>[INAUDIBLE]</span>
  <span m=''36860''>to</span> <span m=''37060''>what</span> <span m=''37270''>people</span>
  <span m=''37560''>are</span> <span m=''37620''>doing</span> <span m=''38380''>otherwise.</span>
  <span m=''39170''>So</span> <span m=''40200''>normally</span> <span m=''40700''>what</span>
  <span m=''40900''>we</span> <span m=''41020''>have</span> <span m=''41140''>done</span>
  <span m=''41330''>so</span> <span m=''41550''>far,</span> <span m=''42340''>is</span>
  <span m=''43030''>we looked</span> <span m=''43300''>at</span> <span m=''43490''>Cilk.</span>
  </p><p><span m=''44030''>It</span> <span m=''44200''>provides</span> <span m=''44540''>a</span>
  <span m=''44590''>very</span> <span m=''44800''>robust</span> <span m=''45260''>and</span>
  <span m=''45370''>environment</span> <span m=''46060''>for</span> <span m=''46100''>parallelization.</span>
  <span m=''46930''>It</span> <span m=''47250''>hides</span> <span m=''47900''>many</span>
  <span m=''48780''>issues</span> <span m=''49430''>and</span> <span m=''49630''>eliminates</span>
  <span m=''50110''>many</span> <span m=''50380''>of</span> <span m=''50460''>the</span>
  <span m=''50550''>problems</span> <span m=''51030''>out</span> <span m=''51210''>there</span>
  <span m=''53820''>if</span> <span m=''53980''>you</span> <span m=''54140''>find</span>
  <span m=''54590''>other</span> <span m=''54730''>areas</span> <span m=''54880''>of</span>
  <span m=''55030''>parallelization</span> <span m=''56120''>that</span> <span m=''56300''>you</span>
  <span m=''56490''>deal</span> <span m=''56690''>with.</span> <span m=''57710''>And</span>
  <span m=''57820''>in</span> <span m=''58080''>last lectures,</span> <span m=''58340''>we</span>
  <span m=''58670''>looked</span> <span m=''58880''>at</span> <span m=''59000''>things</span>
  <span m=''59310''>like</span> <span m=''59960''>cache</span> <span m=''60290''>[UNINTELLIGIBLE]</span>
  <span m=''61140''>algorithims,</span> <span m=''62880''>algorithmic</span> <span
  m=''63530''>issues,</span> <span m=''64069''>like</span> <span m=''64269''>looking</span>
  <span m=''64470''>at</span> <span m=''64569''>work</span> <span m=''64849''>and</span>
  <span m=''64980''>spend.</span> <span m=''66710''>And</span> <span m=''66970''>in</span>
  <span m=''67100''>fact,</span> <span m=''67350''>in your</span> <span m=''67560''>projects,</span>
  <span m=''67950''>you''re</span> <span m=''68080''>going</span> <span m=''68250''>to</span>
  <span m=''68400''>use all</span> <span m=''68590''>these</span> <span m=''68790''>nice</span>
  <span m=''69050''>concepts</span> <span m=''69750''>to</span> <span m=''69840''>get</span>
  <span m=''70170''>you</span> <span m=''70480''>a</span> <span m=''70790''>nice</span>
  <span m=''71160''>parallel</span> <span m=''71580''>learning</span> <span m=''71870''>CorD.</span>
  </p><p><span m=''73660''>But</span> <span m=''74550''>if</span> <span m=''74730''>you</span>
  <span m=''74890''>look</span> <span m=''75180''>at</span> <span m=''78510''>a</span>
  <span m=''78910''>lot</span> <span m=''79130''>of</span> <span m=''79210''>these</span>
  <span m=''79450''>CorD</span> <span m=''79770''>[UNINTELLIGIBLE]</span> <span m=''80640''>the</span>
  <span m=''80920''>very</span> <span m=''81210''>people</span> <span m=''81530''>normally</span>
  <span m=''82220''>for</span> <span m=''82520''>parallelized</span> <span m=''82770''>CorD</span>
  <span m=''82970''>outside</span> <span m=''84150''>probably</span> <span m=''85030''>Cilk.</span>
  <span m=''85800''>And</span> <span m=''86960''>there</span> <span m=''87100''>are
  a</span> <span m=''87180''>lot of</span> <span m=''87480''>other</span> <span m=''87910''>issues</span>
  <span m=''89260''>that</span> <span m=''89450''>arise,</span> <span m=''89740''>things</span>
  <span m=''90040''>like</span> <span m=''90270''>synchronization</span> <span m=''91030''>issues</span>
  <span m=''91800''>and</span> <span m=''92150''>memory</span> <span m=''92870''>issues.</span>
  </p><p><span m=''93160''>Today,</span> <span m=''93260''>I think</span> <span m=''93480''>we</span>
  <span m=''94230''>are going to</span> <span m=''94490''>focus</span> <span m=''94840''>mostly</span>
  <span m=''95170''>on</span> <span m=''95320''>memory</span> <span m=''95700''>issues.</span>
  <span m=''96380''>And</span> <span m=''96550''>we</span> <span m=''96620''>are</span>
  <span m=''96800''>going to</span> <span m=''96910''>use</span> <span m=''97250''>open</span>
  <span m=''97610''>OpenMP</span> <span m=''97720''>instead</span> <span m=''98210''>of</span>
  <span m=''98623''>[INAUDIBLE].</span> <span m=''99450''>And</span> <span m=''100110''>most</span>
  <span m=''100380''>of</span> <span m=''100450''>these</span> <span m=''100650''>issues</span>
  <span m=''101040''>will</span> <span m=''101290''>be</span> <span m=''101550''>affected</span>
  <span m=''101910''>on</span> <span m=''102400''>Cilk</span> <span m=''102700''>sometimes,</span>
  <span m=''103150''>too.</span> <span m=''103710''>But</span> <span m=''103960''>Cilk</span>
  <span m=''104310''>tries</span> <span m=''104580''>to</span> <span m=''104660''>hide</span>
  <span m=''105020''>them</span> <span m=''105180''>from</span> <span m=''105630''>you.</span>
  <span m=''105990''>There''s</span> <span m=''106290''>a layer</span> <span m=''106550''>of</span>
  <span m=''106650''>abstract.</span> <span m=''106920''>And</span> <span m=''107190''>it''s</span>
  <span m=''107350''>hard</span> <span m=''107710''>to</span> <span m=''107810''>kind</span>
  <span m=''108150''>of</span> <span m=''108360''>get</span> <span m=''108640''>to
  those</span> <span m=''108910''>issues</span> <span m=''109290''>in</span> <span
  m=''109440''>there.</span> <span m=''109940''>So</span> <span m=''110200''>we</span>
  <span m=''110380''>are going to</span> <span m=''110690''>look</span> <span m=''111030''>at</span>
  <span m=''111380''>this</span> <span m=''111530''>thing</span> <span m=''111660''>called</span>
  <span m=''111800''>OpenMP.</span> </p><p><span m=''113200''>So</span> <span m=''113470''>today,</span>
  <span m=''113780''>we</span> <span m=''113880''>are</span> <span m=''113990''>going
  to</span> <span m=''114090''>address</span> <span m=''114440''>things</span> <span
  m=''114790''>like</span> <span m=''115430''>granularity</span> <span m=''116020''>of</span>
  <span m=''116130''>parallelism.</span> <span m=''118820''>There are</span> <span
  m=''119070''>so</span> <span m=''119180''>many</span> <span m=''119340''>things</span>
  <span m=''119540''>that</span> <span m=''119640''>just</span> <span m=''119810''>went</span>
  <span m=''120000''>out</span> <span m=''120140''>on</span> <span m=''120220''>the</span>
  <span m=''120310''>page,</span> <span m=''120670''>I</span> <span m=''120720''>guess.</span>
  <span m=''121820''>True</span> <span m=''122020''>sharing,</span> <span m=''122520''>false</span>
  <span m=''122830''>sharing,</span> <span m=''123490''>load</span> <span m=''123780''>balancing</span>
  <span m=''124220''>issues,</span> <span m=''124900''>the</span> <span m=''125060''>[UNINTELLIGIBLE].</span>
  <span m=''126170''>So</span> <span m=''127830''>from</span> <span m=''128000''>the</span>
  <span m=''128080''>license</span> <span m=''128430''>and</span> <span m=''128580''>keep</span>
  <span m=''128830''>talking</span> <span m=''129240''>about</span> <span m=''129990''>that</span>
  <span m=''130180''>we</span> <span m=''130340''>want</span> <span m=''130520''>to</span>
  <span m=''130570''>be</span> <span m=''130740''>out</span> <span m=''130930''>of
  all</span> <span m=''131320''>this</span> <span m=''131610''>not</span> <span m=''131980''>dealing</span>
  <span m=''132250''>with</span> <span m=''132400''>Voodoo</span> <span m=''132600''>parameter.</span>
  <span m=''133550''>Today,</span> <span m=''134220''>we</span> <span m=''134320''>actually</span>
  <span m=''134640''>are dealing</span> <span m=''135090''>mainly</span> <span m=''135460''>with</span>
  <span m=''135550''>Voodoo.</span> <span m=''136350''>So</span> <span m=''137180''>I</span>
  <span m=''137310''>guess</span> <span m=''137540''>this</span> <span m=''137890''>should</span>
  <span m=''138140''>be</span> <span m=''140180''>basically</span> <span m=''140460''>the</span>
  <span m=''140510''>Halloween</span> <span m=''141070''>lecture.</span> <span m=''141670''>So</span>
  <span m=''141850''>we</span> <span m=''141990''>are all</span> <span m=''142200''>about</span>
  <span m=''142470''>Voodoo</span> <span m=''142830''>today</span> <span m=''143160''>and</span>
  <span m=''143330''>see</span> <span m=''143470''>how</span> <span m=''143630''>we</span>
  <span m=''143810''>can</span> <span m=''144280''>deal</span> <span m=''144703''>with</span>
  <span m=''145126''>Voodoo</span> <span m=''145890''>issues.</span> </p><p><span
  m=''147760''>So</span> <span m=''149190''>if</span> <span m=''149500''>you</span>
  <span m=''149630''>look</span> <span m=''149830''>at</span> <span m=''150230''>a</span>
  <span m=''150560''>Cilk program,</span> <span m=''151710''>here is</span> <span
  m=''152010''>a</span> <span m=''152090''>nice</span> <span m=''152370''>simple</span>
  <span m=''152690''>matrix</span> <span m=''153040''>multiply,</span> <span m=''153750''>seem</span>
  <span m=''153980''>to</span> <span m=''154060''>be</span> <span m=''154140''>[INAUDIBLE]</span>
  <span m=''154740''>example</span> <span m=''155250''>these</span> <span m=''155470''>days.</span>
  <span m=''156320''>What</span> <span m=''156520''>you</span> <span m=''156660''>can</span>
  <span m=''156800''>do</span> <span m=''157000''>is</span> <span m=''157230''>you
  can</span> <span m=''157490''>put</span> <span m=''157590''>a</span> <span m=''157680''>Cilk</span>
  <span m=''157990''>formula</span> <span m=''158400''>in</span> <span m=''158740''>these</span>
  <span m=''158940''>two</span> <span m=''159060''>loops</span> <span m=''159560''>and</span>
  <span m=''160040''>get</span> <span m=''160140''>a</span> <span m=''160240''>nice</span>
  <span m=''160530''>parallel</span> <span m=''160800''>performance.</span> <span
  m=''162070''>However,</span> <span m=''163030''>[UNINTELLIGIBLE]</span> <span m=''164870''>from
  where</span> <span m=''165240''>how the</span> <span m=''165390''>memory</span>
  <span m=''166160''>is</span> <span m=''166390''>arranged</span> <span m=''166980''>is</span>
  <span m=''167270''>up to</span> <span m=''167585''>the</span> <span m=''167900''>Cilk
  scheduler.</span> </p><p><span m=''168820''>Cilk</span> <span m=''169120''>scheduler</span>
  <span m=''169550''>is</span> <span m=''169710''>doing</span> <span m=''169880''>some</span>
  <span m=''170070''>work</span> <span m=''170270''>stealing.</span> <span m=''170980''>Depending</span>
  <span m=''171540''>on</span> <span m=''171930''>how</span> <span m=''172110''>the</span>
  <span m=''172190''>work</span> <span m=''172420''>gets</span> <span m=''172550''>distributed,</span>
  <span m=''173710''>the</span> <span m=''173830''>process</span> <span m=''174050''>will</span>
  <span m=''174420''>get</span> <span m=''174580''>worked,</span> <span m=''175170''>it</span>
  <span m=''175260''>will</span> <span m=''175350''>happen.</span> <span m=''176090''>Hopefully,</span>
  <span m=''176300''>everything</span> <span m=''176770''>will</span> <span m=''176900''>go</span>
  <span m=''177060''>nicely.</span> <span m=''178370''>And</span> <span m=''178860''>so</span>
  <span m=''179510''>what</span> <span m=''179780''>that</span> <span m=''179960''>means</span>
  <span m=''180220''>is</span> <span m=''180630''>it</span> <span m=''180820''>ties</span>
  <span m=''181260''>the</span> <span m=''181370''>distribution</span> <span m=''181960''>and</span>
  <span m=''182050''>load</span> <span m=''182270''>balancing</span> <span m=''182730''>issues.</span>
  </p><p><span m=''184060''>So</span> <span m=''184180''>it''s</span> <span m=''184320''>nice</span>
  <span m=''184630''>if you have</span> <span m=''184750''>access</span> <span m=''185150''>to</span>
  <span m=''185210''>Cilk,</span> <span m=''185980''>but</span> <span m=''187170''>many</span>
  <span m=''187460''>other</span> <span m=''187640''>[UNINTELLIGIBLE]</span> <span
  m=''188000''>you</span> <span m=''188100''>might</span> <span m=''188350''>not</span>
  <span m=''188580''>be.</span> <span m=''189050''>And</span> <span m=''189270''>even</span>
  <span m=''189550''>within</span> <span m=''189780''>Cilk,</span> <span m=''190080''>some</span>
  <span m=''190270''>of</span> <span m=''190350''>these</span> <span m=''190770''>issues</span>
  <span m=''191390''>might</span> <span m=''191620''>show</span> <span m=''191880''>up.</span>
  <span m=''192320''>So</span> <span m=''193020''>what</span> <span m=''193240''>we</span>
  <span m=''193380''>are going to</span> <span m=''193620''>do</span> <span m=''193810''>is</span>
  <span m=''194280''>step</span> <span m=''194630''>one</span> <span m=''195390''>below</span>
  <span m=''196080''>the</span> <span m=''196200''>Cilk</span> <span m=''196590''>scheduler.</span>
  </p><p><span m=''197820''>So</span> <span m=''198680''>there''s</span> <span m=''200256''>this</span>
  <span m=''200640''>system</span> <span m=''200990''>called</span> <span m=''201170''>OpenMP.</span>
  <span m=''202470''>It''s</span> <span m=''202760''>a</span> <span m=''203220''>more</span>
  <span m=''203430''>simplified</span> <span m=''204520''>model</span> <span m=''204840''>of</span>
  <span m=''204900''>parallelism.</span> <span m=''205640''>So</span> <span m=''205760''>what</span>
  <span m=''205940''>it</span> <span m=''206080''>tries</span> <span m=''206360''>to</span>
  <span m=''206470''>do</span> <span m=''206710''>is</span> <span m=''208310''>instead</span>
  <span m=''208710''>of</span> <span m=''208880''>giving</span> <span m=''209190''>this</span>
  <span m=''209400''>very</span> <span m=''209665''>[UNINTELLIGIBLE]</span> <span
  m=''210460''>system,</span> <span m=''210770''>it</span> <span m=''211120''>lets</span>
  <span m=''211580''>you</span> <span m=''211820''>basically</span> <span m=''213000''>direct</span>
  <span m=''213420''>access</span> <span m=''213780''>to</span> <span m=''213850''>the</span>
  <span m=''213930''>processors.</span> <span m=''215110''>So</span> <span m=''215410''>what</span>
  <span m=''215630''>that</span> <span m=''216680''>means</span> <span m=''217050''>is</span>
  <span m=''217180''>there''s</span> <span m=''217370''>normally</span> <span m=''217760''>what</span>
  <span m=''217870''>we</span> <span m=''217980''>call</span> <span m=''218150''>a</span>
  <span m=''218280''>fork-join</span> <span m=''218860''>model.</span> <span m=''219210''>[UNINTELLIGIBLE]</span>
  <span m=''219520''>we</span> <span m=''219630''>have</span> <span m=''219780''>with</span>
  <span m=''219860''>Cilk,</span> <span m=''221530''>basically.</span> <span m=''223580''>We</span>
  <span m=''223700''>can</span> <span m=''223880''>do</span> <span m=''223970''>fork</span>
  <span m=''224380''>into</span> <span m=''224650''>different</span> <span m=''224950''>workers</span>
  <span m=''225180''>and</span> <span m=''225460''>join.</span> <span m=''226490''>And</span>
  <span m=''227240''>more or less,</span> <span m=''227850''>you can</span> <span
  m=''227910''>actually</span> <span m=''228050''>bind</span> <span m=''228880''>these</span>
  <span m=''229130''>workers</span> <span m=''229640''>to</span> <span m=''229750''>[UNINTELLIGIBLE]</span>
  <span m=''230420''>sometimes</span> <span m=''231040''>or</span> <span m=''232170''>make</span>
  <span m=''232440''>sure</span> <span m=''232570''>that</span> <span m=''232760''>the</span>
  <span m=''232850''>number--</span> <span m=''233510''>I''ll</span> <span m=''233640''>give
  you</span> <span m=''233880''>some techniques how</span> <span m=''234350''>to</span>
  <span m=''234530''>do</span> <span m=''234700''>that</span> <span m=''235200''>as</span>
  <span m=''235450''>I</span> <span m=''235510''>go on.</span> </p><p><span m=''236800''>So</span>
  <span m=''237400''>for</span> <span m=''237500''>parallel</span> <span m=''238050''>loops,</span>
  <span m=''239260''>you</span> <span m=''239460''>can</span> <span m=''239680''>do</span>
  <span m=''239820''>data</span> <span m=''240120''>parallelism,</span> <span m=''240880''>different</span>
  <span m=''241540''>[UNINTELLIGIBLE]</span> <span m=''242340''>parallelism</span>
  <span m=''242500''>you can</span> <span m=''242890''>do</span> <span m=''243110''>something</span>
  <span m=''243370''>like</span> <span m=''243520''>fork-join.</span> <span m=''244580''>And</span>
  <span m=''245370''>you</span> <span m=''245510''>can</span> <span m=''245650''>see</span>
  <span m=''245840''>a</span> <span m=''246100''>bunch</span> <span m=''246520''>of</span>
  <span m=''246960''>static</span> <span m=''247530''>or</span> <span m=''247620''>dynamic</span>
  <span m=''248080''>scheduling</span> <span m=''248560''>policies.</span> </p><p><span
  m=''251220''>So</span> <span m=''251430''>for</span> <span m=''251580''>example</span>
  <span m=''252560''>in</span> <span m=''252770''>OpenMP,</span> <span m=''253000''>you</span>
  <span m=''253130''>can</span> <span m=''253590''>see</span> <span m=''253830''>for</span>
  <span m=''253940''>this</span> <span m=''254370''>loop</span> <span m=''255370''>that</span>
  <span m=''256300''>add</span> <span m=''256790''>a</span> <span m=''256950''>pragma</span>
  <span m=''257360''>to</span> <span m=''257500''>[UNINTELLIGIBLE]</span> <span m=''257959''>in</span>
  <span m=''258070''>front</span> <span m=''258260''>of</span> <span m=''258339''>this</span>
  <span m=''258480''>loop</span> <span m=''258750''>and</span> <span m=''258899''>say</span>
  <span m=''259019''>this</span> <span m=''259200''>is</span> <span m=''259339''>OpenMP.</span>
  <span m=''261029''>Parallel</span> <span m=''261490''>loop</span> <span m=''261829''>in
  here.</span> <span m=''262450''>Parallel</span> <span m=''262890''>full</span> <span
  m=''263160''>loop</span> <span m=''263400''>in</span> <span m=''263560''>this</span>
  <span m=''263770''>one.</span> <span m=''264310''>And</span> <span m=''264940''>schedule</span>
  <span m=''265260''>it</span> <span m=''265810''>using</span> <span m=''266150''>static</span>
  <span m=''266640''>chunk.</span> <span m=''266990''>I</span> <span m=''267060''>will</span>
  <span m=''267240''>tell</span> <span m=''267450''>you</span> <span m=''267540''>what</span>
  <span m=''268260''>exactly</span> <span m=''268640''>that</span> <span m=''268840''>means.</span>
  <span m=''269610''>And</span> <span m=''270740''>that</span> <span m=''270950''>gives</span>
  <span m=''271190''>you</span> <span m=''271690''>direct</span> <span m=''272070''>access</span>
  <span m=''272440''>to</span> <span m=''273040''>how</span> <span m=''273800''>each</span>
  <span m=''274110''>of</span> <span m=''274230''>these</span> <span m=''274680''>parts</span>
  <span m=''275280''>will</span> <span m=''275410''>be</span> <span m=''275550''>run.</span>
  </p><p><span m=''276730''>So</span> <span m=''277090''>let</span> <span m=''277490''>me</span>
  <span m=''277720''>get a</span> <span m=''277810''>little</span> <span m=''278240''>bit</span>
  <span m=''278520''>in</span> <span m=''278800''>detail.</span> <span m=''279320''>So</span>
  <span m=''279490''>assume</span> <span m=''279855''>you</span> <span m=''280220''>have</span>
  <span m=''280932''>[UNINTELLIGIBLE]</span> <span m=''281290''>courses</span> <span
  m=''281610''>in</span> <span m=''281730''>there,</span> <span m=''282010''>[UNINTELLIGIBLE]</span>
  <span m=''282200''>processors.</span> <span m=''282950''>So</span> <span m=''283110''>now</span>
  <span m=''283580''>in</span> <span m=''283710''>OpenMP,</span> <span m=''284260''>you
  are</span> <span m=''284520''>basically</span> <span m=''285090''>opening</span>
  <span m=''285560''>the</span> <span m=''285930''>entire</span> <span m=''286270''>world</span>
  <span m=''286810''>underneath.</span> <span m=''286990''>And</span> <span m=''287050''>you</span>
  <span m=''287210''>have</span> <span m=''287390''>to</span> <span m=''287470''>kind</span>
  <span m=''287560''>of</span> <span m=''287900''>see</span> <span m=''288120''>what''s</span>
  <span m=''288360''>going</span> <span m=''288590''>on.</span> </p><p><span m=''289840''>And</span>
  <span m=''290350''>if</span> <span m=''290500''>you say,</span> <span m=''291570''>schedule</span>
  <span m=''291970''>a</span> <span m=''292170''>static</span> <span m=''293430''>chunk</span>
  <span m=''293870''>of</span> <span m=''294050''>four,</span> <span m=''294830''>assume</span>
  <span m=''295330''>you</span> <span m=''295390''>have</span> <span m=''295830''>16</span>
  <span m=''295910''>iterations.</span> <span m=''298050''>Here are</span> <span m=''298290''>my</span>
  <span m=''298420''>16</span> <span m=''299250''>iterations.</span> <span m=''300200''>So
  each</span> <span m=''300530''>of</span> <span m=''300640''>these</span> <span m=''300860''>dots</span>
  <span m=''301120''>represent</span> <span m=''301700''>a</span> <span m=''301770''>value</span>
  <span m=''302040''>for</span> <span m=''302180''>i.</span> <span m=''302990''>So</span>
  <span m=''303120''>what</span> <span m=''303280''>it</span> <span m=''303430''>says</span>
  <span m=''303800''>is</span> <span m=''304020''>you</span> <span m=''304180''>take</span>
  <span m=''304490''>chunks</span> <span m=''304900''>of</span> <span m=''305000''>four</span>
  <span m=''307040''>and</span> <span m=''307400''>basically</span> <span m=''307890''>send
  it</span> <span m=''308140''>across</span> <span m=''308440''>it.</span> <span m=''308950''>So</span>
  <span m=''309120''>what</span> <span m=''309280''>happens</span> <span m=''309630''>is</span>
  <span m=''309820''>the first</span> <span m=''310070''>four</span> <span m=''310300''>iterations</span>
  <span m=''310750''>will</span> <span m=''310920''>go</span> <span m=''311050''>to</span>
  <span m=''311190''>[UNINTELLIGIBLE]</span> <span m=''311470''>or</span> <span m=''312180''>core</span>
  <span m=''312480''>zero.</span> <span m=''313240''>Next</span> <span m=''313490''>four</span>
  <span m=''313620''>will</span> <span m=''313750''>go to</span> <span m=''314220''>core</span>
  <span m=''314390''>one,</span> <span m=''314690''>core two</span> <span m=''314870''>and
  core</span> <span m=''315100''>three.</span> </p><p><span m=''315650''>So</span>
  <span m=''315860''>you</span> <span m=''316070''>know</span> <span m=''316420''>exactly</span>
  <span m=''317090''>which</span> <span m=''317430''>iterations</span> <span m=''318050''>run</span>
  <span m=''318300''>where.</span> <span m=''318870''>It''s</span> <span m=''319120''>a</span>
  <span m=''319180''>very</span> <span m=''319480''>static</span> <span m=''319910''>thing.</span>
  <span m=''320660''>You have</span> <span m=''320850''>full</span> <span m=''321030''>control</span>
  <span m=''321370''>of</span> <span m=''321530''>what''s</span> <span m=''321740''>going</span>
  <span m=''321990''>on.</span> <span m=''323100''>Whereas</span> <span m=''323270''>in</span>
  <span m=''323570''>Cilk,</span> <span m=''325500''>it''s</span> <span m=''325860''>up</span>
  <span m=''326040''>to</span> <span m=''326120''>the</span> <span m=''326230''>scheduler.</span>
  <span m=''326980''>So</span> <span m=''327150''>the</span> <span m=''327230''>nice</span>
  <span m=''327450''>thing</span> <span m=''327660''>here</span> <span m=''327980''>is
  you can</span> <span m=''328090''>have</span> <span m=''328200''>full</span> <span
  m=''328360''>control.</span> <span m=''329090''>But</span> <span m=''329390''>you
  get</span> <span m=''329500''>enough</span> <span m=''329610''>room to</span> <span
  m=''329720''>harm</span> <span m=''330520''>yourself</span> <span m=''330870''>if</span>
  <span m=''330960''>you do</span> <span m=''331060''>things</span> <span m=''331350''>wrong.</span>
  <span m=''332260''>So</span> <span m=''333270''>this</span> <span m=''333480''>is</span>
  <span m=''333600''>a</span> <span m=''333650''>double-edged</span> <span m=''334100''>sword</span>
  <span m=''334430''>in</span> <span m=''334520''>that</span> <span m=''334730''>sense.</span>
  </p><p><span m=''336510''>So</span> <span m=''337010''>instead</span> <span m=''337350''>of</span>
  <span m=''337440''>doing</span> <span m=''337630''>static five</span> <span m=''338420''>you
  do</span> <span m=''338700''>static</span> <span m=''339230''>two.</span> <span
  m=''339990''>You''re</span> <span m=''340700''>assigning</span> <span m=''341400''>chunks</span>
  <span m=''341840''>of</span> <span m=''341970''>size</span> <span m=''342380''>two.</span>
  <span m=''343010''>What</span> <span m=''343570''>it will</span> <span m=''343730''>do</span>
  <span m=''344020''>is</span> <span m=''344330''>it will</span> <span m=''344550''>assign</span>
  <span m=''344920''>chunks</span> <span m=''345210''>of</span> <span m=''345350''>size</span>
  <span m=''345710''>two</span> <span m=''345920''>to the</span> <span m=''347830''>four</span>
  <span m=''348070''>cores.</span> <span m=''348450''>And</span> <span m=''348640''>then</span>
  <span m=''348790''>you''re</span> <span m=''348920''>not</span> <span m=''349100''>done</span>
  <span m=''349350''>yet.</span> <span m=''349770''>And</span> <span m=''349920''>then</span>
  <span m=''350090''>you</span> <span m=''350150''>start</span> <span m=''350650''>with</span>
  <span m=''350780''>again</span> <span m=''351300''>core</span> <span m=''351610''>zero</span>
  <span m=''351880''>and</span> <span m=''352190''>assign</span> <span m=''352620''>chunks</span>
  <span m=''352860''>of</span> <span m=''352960''>size</span> <span m=''353330''>two.</span>
  </p><p><span m=''353980''>This</span> <span m=''354170''>is</span> <span m=''354340''>called</span>
  <span m=''355840''>block</span> <span m=''356500''>cyclic</span> <span m=''357030''>schedule.</span>
  <span m=''357880''>And</span> <span m=''358040''>if</span> <span m=''358160''>you</span>
  <span m=''358280''>do a</span> <span m=''358600''>chunk</span> <span m=''358920''>of</span>
  <span m=''359010''>size</span> <span m=''359370''>one,</span> <span m=''359700''>it''s</span>
  <span m=''359880''>called</span> <span m=''360030''>a</span> <span m=''360080''>cyclic</span>
  <span m=''360220''>schedule.</span> <span m=''360890''>[UNINTELLIGIBLE]</span> <span
  m=''361160''>cycles</span> <span m=''363286''>just</span> <span m=''363740''>assigning</span>
  <span m=''366280''>iterations</span> <span m=''366860''>to</span> <span m=''366960''>cores.</span>
  <span m=''368190''>OK.</span> <span m=''368830''>So</span> <span m=''369070''>far</span>
  <span m=''369230''>so</span> <span m=''369410''>good?</span> <span m=''371700''>OK.</span>
  </p><p><span m=''373780''>So</span> <span m=''374970''>I</span> <span m=''375110''>want
  to</span> <span m=''375300''>do</span> <span m=''375400''>something.</span> <span
  m=''375780''>So</span> <span m=''375970''>I</span> <span m=''378450''>have</span>
  <span m=''378740''>this</span> <span m=''378910''>program.</span> <span m=''379740''>This</span>
  <span m=''379950''>is</span> <span m=''380620''>again</span> <span m=''380690''>your</span>
  <span m=''381790''>run-of-the-mill</span> <span m=''382930''>matrix</span> <span
  m=''383300''>multiply.</span> <span m=''384350''>And</span> <span m=''385290''>I</span>
  <span m=''385530''>ran</span> <span m=''386070''>a</span> <span m=''386190''>sequential</span>
  <span m=''387880''>single</span> <span m=''388280''>machine,</span> <span m=''388770''>and</span>
  <span m=''389710''>I</span> <span m=''389770''>got</span> <span m=''389880''>this</span>
  <span m=''390070''>performance.</span> <span m=''391860''>Then,</span> <span m=''392050''>I</span>
  <span m=''392130''>said</span> <span m=''392570''>look, I</span> <span m=''392760''>want</span>
  <span m=''392940''>to</span> <span m=''393000''>parallelize</span> <span m=''393230''>the</span>
  <span m=''393530''>outer</span> <span m=''393680''>loop.</span> <span m=''394750''>So</span>
  <span m=''395480''>I</span> <span m=''395640''>parallelize</span> <span m=''395840''>this</span>
  <span m=''395880''>loop.</span> </p><p><span m=''397640''>What</span> <span m=''397780''>should</span>
  <span m=''397930''>I</span> <span m=''397970''>get?</span> <span m=''400710''>[UNINTELLIGIBLE]</span>
  <span m=''400980''>fast</span> <span m=''401420''>or slow.</span> <span m=''401790''>I</span>
  <span m=''401960''>want to just</span> <span m=''402140''>check</span> <span m=''402510''>whether</span>
  <span m=''402750''>you</span> <span m=''403060''>are</span> <span m=''403370''>awake</span>
  <span m=''403790''>or</span> <span m=''404210''>sleep.</span> <span m=''406970''>How
  do</span> <span m=''407430''>[UNINTELLIGIBLE PHRASE]</span> <span m=''407890''>to
  run</span> <span m=''408010''>slower.</span> <span m=''413030''>It''s</span> <span
  m=''413210''>not</span> <span m=''413350''>a</span> <span m=''413390''>trick</span>
  <span m=''413630''>question.</span> <span m=''414370''>This</span> <span m=''414570''>is</span>
  <span m=''414640''>just</span> <span m=''414830''>to</span> <span m=''414910''>make</span>
  <span m=''415090''>sure</span> <span m=''415190''>that</span> <span m=''415330''>actually</span>
  <span m=''415690''>participate.</span> <span m=''417460''>How</span> <span m=''417930''>do</span>
  <span m=''418330''>people</span> <span m=''418460''>think it''s</span> <span m=''418590''>run</span>
  <span m=''418730''>faster?</span> </p><p><span m=''419230''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''420950''>PROFESSOR: OK.</span> <span m=''421100''>Good.</span>
  <span m=''422390''>What</span> <span m=''422560''>do</span> <span m=''422760''>others</span>
  <span m=''422900''>think?</span> <span m=''425234''>OK.</span> <span m=''426070''>They''re</span>
  <span m=''426400''>probably</span> <span m=''427300''>checking their</span> <span
  m=''427640''>email</span> <span m=''428030''>or</span> <span m=''428100''>something.</span>
  <span m=''428980''>OK.</span> <span m=''430550''>So</span> <span m=''431300''>actually</span>
  <span m=''431890''>it ran</span> <span m=''432500''>faster.</span> <span m=''434340''>The</span>
  <span m=''434450''>source</span> <span m=''434910''>not</span> <span m=''435220''>run</span>
  <span m=''436120''>on</span> <span m=''436400''>the</span> <span m=''436680''>common</span>
  <span m=''438180''>cloud</span> <span m=''438480''>machines.</span> <span m=''438910''>This</span>
  <span m=''439030''>was a</span> <span m=''439160''>previous</span> <span m=''439620''>generation</span>
  <span m=''440240''>that</span> <span m=''440370''>I</span> <span m=''440500''>ran.</span>
  <span m=''440990''>So</span> <span m=''441210''>[UNINTELLIGIBLE]</span> <span m=''441380''>was</span>
  <span m=''441610''>seven</span> <span m=''441880''>times</span> <span m=''442140''>faster.</span>
  <span m=''443390''>So</span> <span m=''443600''>this</span> <span m=''443800''>was</span>
  <span m=''444000''>great.</span> <span m=''444290''>I</span> <span m=''444370''>parallized</span>
  <span m=''444730''>outer</span> <span m=''444820''>loop.</span> </p><p><span m=''445670''>What</span>
  <span m=''445930''>happens</span> <span m=''446250''>if</span> <span m=''446380''>I</span>
  <span m=''446600''>parallize</span> <span m=''447265''>inner loop?</span> <span
  m=''448390''>So</span> <span m=''448520''>this</span> <span m=''448800''>test,</span>
  <span m=''449060''>this</span> <span m=''449500''>i loop,</span> <span m=''449890''>runs</span>
  <span m=''450190''>parallel.</span> <span m=''451570''>Here,</span> <span m=''451840''>I</span>
  <span m=''451990''>launch</span> <span m=''452150''>the</span> <span m=''452270''>[UNINTELLIGIBLE]</span>
  <span m=''452400''>parallel.</span> <span m=''454060''>How</span> <span m=''454230''>much</span>
  <span m=''454870''>people</span> <span m=''455210''>thinks</span> <span m=''455330''>this</span>
  <span m=''455440''>runs</span> <span m=''455720''>faster?</span> </p><p><span m=''458138''>AUDIENCE:
  [INAUDIBLE]</span> </p><p><span m=''459970''>PROFESSOR: Compared</span> <span m=''460470''>to</span>
  <span m=''460510''>this</span> <span m=''460720''>one.</span> <span m=''462800''>How</span>
  <span m=''462940''>many</span> <span m=''463560''>people</span> <span m=''463820''>thinks</span>
  <span m=''463930''>this</span> <span m=''464120''>runs</span> <span m=''464210''>slower?</span>
  <span m=''465290''>OK.</span> <span m=''466530''>There''s</span> <span m=''466760''>some</span>
  <span m=''469320''>consistent</span> <span m=''469680''>answers</span> <span m=''469860''>here.</span>
  <span m=''470530''>Why</span> <span m=''470800''>do</span> <span m=''471070''>you</span>
  <span m=''471130''>think</span> <span m=''471290''>it</span> <span m=''471640''>would</span>
  <span m=''472050''>run</span> <span m=''472503''>slower?</span> <span m=''476130''>So</span>
  <span m=''476350''>OK.</span> <span m=''477720''>It ran</span> <span m=''477870''>slower,
  so</span> <span m=''478100''>it</span> <span m=''478350''>can improve</span> <span
  m=''478600''>that.</span> <span m=''480180''>And that''s</span> <span m=''480430''>a</span>
  <span m=''480680''>little bit</span> <span m=''480830''>slow.</span> <span m=''482270''>Why</span>
  <span m=''482510''>is</span> <span m=''482630''>it</span> <span m=''482810''>slow?</span>
  </p><p><span m=''485774''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''488250''>PROFESSOR:
  Exactly.</span> <span m=''489050''>So</span> <span m=''489200''>what</span> <span
  m=''489390''>it''s</span> <span m=''489630''>doing</span> <span m=''489910''>here,</span>
  <span m=''490390''>it''s basically</span> <span m=''491340''>spawning</span> <span
  m=''492070''>many,</span> <span m=''492280''>many</span> <span m=''492520''>times</span>
  <span m=''492860''>in</span> <span m=''493000''>here.</span> <span m=''493200''>Because</span>
  <span m=''493570''>every</span> <span m=''493790''>time</span> <span m=''495170''>you</span>
  <span m=''495380''>have</span> <span m=''495590''>parallelism,</span> <span m=''496450''>you</span>
  <span m=''496630''>chunkify</span> <span m=''496920''>into</span> <span m=''497530''>the</span>
  <span m=''497640''>processor.</span> <span m=''498500''>Here</span> <span m=''498750''>you
  are</span> <span m=''498900''>getting</span> <span m=''499260''>a</span> <span m=''499280''>lot</span>
  <span m=''499560''>more</span> <span m=''499760''>smaller</span> <span m=''500280''>chunks</span>
  <span m=''500670''>inside.</span> <span m=''501450''>So</span> <span m=''501640''>let''s</span>
  <span m=''501880''>look</span> <span m=''502070''>at</span> <span m=''502170''>how</span>
  <span m=''502470''>this</span> <span m=''502690''>is</span> <span m=''502850''>basically</span>
  <span m=''503410''>run.</span> </p><p><span m=''504700''>So</span> <span m=''504870''>normally,</span>
  <span m=''506890''>you</span> <span m=''507010''>can</span> <span m=''507190''>think</span>
  <span m=''507420''>about</span> <span m=''507770''>an</span> <span m=''508040''>OpenMP</span>
  <span m=''508730''>program</span> <span m=''509610''>as</span> <span m=''510880''>you
  have</span> <span m=''511270''>one</span> <span m=''511550''>sequential</span> <span
  m=''512020''>thread.</span> <span m=''512549''>You</span> <span m=''512710''>run</span>
  <span m=''512830''>the</span> <span m=''512909''>main</span> <span m=''513150''>program.</span>
  <span m=''514000''>And</span> <span m=''514210''>then</span> <span m=''514350''>assume</span>
  <span m=''514490''>you</span> <span m=''514880''>have,</span> <span m=''515320''>in</span>
  <span m=''515880''>cores,</span> <span m=''516620''>you</span> <span m=''516730''>might</span>
  <span m=''516919''>have</span> <span m=''517070''>n</span> <span m=''517299''>minus</span>
  <span m=''517760''>1</span> <span m=''518110''>other</span> <span m=''518480''>thread</span>
  <span m=''518710''>just</span> <span m=''518970''>waiting</span> <span m=''520539''>for</span>
  <span m=''520669''>work.</span> </p><p><span m=''522100''>And</span> <span m=''522400''>then,</span>
  <span m=''522809''>when</span> <span m=''523010''>you</span> <span m=''523159''>finally</span>
  <span m=''523679''>come</span> <span m=''524169''>to</span> <span m=''524440''>the</span>
  <span m=''524870''>parallel</span> <span m=''525270''>loop,</span> <span m=''525640''>it
  says,</span> <span m=''526000''>OK.</span> <span m=''528180''>Set</span> <span m=''528400''>up.</span>
  <span m=''528730''>What</span> <span m=''529060''>do</span> <span m=''529120''>you</span>
  <span m=''529190''>want</span> <span m=''529350''>to</span> <span m=''529410''>run</span>
  <span m=''529650''>on</span> <span m=''529700''>other</span> <span m=''531220''>basic</span>
  <span m=''531710''>cores.</span> <span m=''532080''>And</span> <span m=''532280''>release</span>
  <span m=''532590''>it.</span> <span m=''533510''>Release</span> <span m=''533865''>these</span>
  <span m=''534220''>waiting</span> <span m=''534620''>people.</span> <span m=''535360''>And</span>
  <span m=''535670''>let</span> <span m=''535820''>them</span> <span m=''536020''>start</span>
  <span m=''536330''>working</span> <span m=''536620''>on</span> <span m=''536710''>the</span>
  <span m=''536790''>parallel</span> <span m=''536980''>work.</span> <span m=''537020''>And</span>
  <span m=''537150''>also,</span> <span m=''537430''>I</span> <span m=''537600''>will</span>
  <span m=''537800''>start</span> <span m=''538440''>doing</span> <span m=''538720''>on
  my</span> <span m=''538920''>own</span> <span m=''539060''>chunk.</span> <span m=''539650''>So</span>
  <span m=''539790''>suddenly,</span> <span m=''540260''>when</span> <span m=''540380''>you</span>
  <span m=''540480''>say</span> <span m=''542040''>parallel</span> <span m=''542350''>four,</span>
  <span m=''542940''>it</span> <span m=''543350''>releases</span> <span m=''543560''>all</span>
  <span m=''543720''>other</span> <span m=''543880''>cores</span> <span m=''544260''>to</span>
  <span m=''544330''>go</span> <span m=''544630''>run</span> <span m=''545340''>that</span>
  <span m=''545620''>part</span> <span m=''545830''>of</span> <span m=''545910''>the</span>
  <span m=''546020''>core.</span> </p><p><span m=''547310''>And</span> <span m=''547540''>once</span>
  <span m=''547990''>it''s</span> <span m=''548260''>done,</span> <span m=''549680''>it''s</span>
  <span m=''549860''>will</span> <span m=''550090''>say,</span> <span m=''550310''>OK,
  I''m done.</span> <span m=''551740''>I</span> <span m=''551820''>have</span> <span
  m=''551970''>to</span> <span m=''552280''>wait</span> <span m=''552540''>until</span>
  <span m=''552630''>everybody</span> <span m=''552820''>is</span> <span m=''552970''>done.</span>
  <span m=''553140''>So</span> <span m=''553300''>even</span> <span m=''553720''>if</span>
  <span m=''553910''>the</span> <span m=''554130''>main</span> <span m=''554420''>guy</span>
  <span m=''554730''>is done, it</span> <span m=''555050''>has</span> <span m=''555170''>to</span>
  <span m=''555280''>wait</span> <span m=''556180''>until</span> <span m=''556570''>everybody</span>
  <span m=''557020''>is</span> <span m=''557150''>finished.</span> <span m=''558200''>And</span>
  <span m=''558400''>then,</span> <span m=''560700''>start</span> <span m=''561000''>executing</span>
  <span m=''561460''>the sequence</span> <span m=''561715''>[UNINTELLIGIBLE].</span>
  <span m=''562610''>So</span> <span m=''562760''>this</span> <span m=''562980''>is</span>
  <span m=''563170''>the</span> <span m=''563280''>gist</span> <span m=''563710''>of</span>
  <span m=''563850''>how</span> <span m=''564990''>OpenMP</span> <span m=''565500''>program</span>
  <span m=''565890''>is</span> <span m=''565970''>run.</span> </p><p><span m=''567670''>And</span>
  <span m=''568000''>if</span> <span m=''568090''>you</span> <span m=''568220''>realize</span>
  <span m=''569150''>that</span> <span m=''569320''>it</span> <span m=''569420''>all</span>
  <span m=''569830''>heads here</span> <span m=''570390''>because</span> <span m=''570550''>you</span>
  <span m=''570760''>have</span> <span m=''570840''>basically</span> <span m=''571400''>make</span>
  <span m=''571620''>sure</span> <span m=''571940''>all these</span> <span m=''572160''>cases</span>
  <span m=''572410''>are</span> <span m=''572570''>broken</span> <span m=''572850''>up.</span>
  <span m=''573150''>So</span> <span m=''573310''>there''s</span> <span m=''573500''>some</span>
  <span m=''574450''>things</span> <span m=''574770''>that</span> <span m=''574940''>has</span>
  <span m=''575030''>to be</span> <span m=''575170''>issued.</span> <span m=''575740''>And</span>
  <span m=''575940''>there''s</span> <span m=''576080''>a</span> <span m=''576150''>delay</span>
  <span m=''576440''>between</span> <span m=''577170''>these</span> <span m=''577450''>guys</span>
  <span m=''577980''>can</span> <span m=''578120''>start</span> <span m=''578270''>if</span>
  <span m=''578590''>everybody</span> <span m=''578880''>has</span> <span m=''579000''>equal</span>
  <span m=''579090''>work.</span> </p><p><span m=''579990''>Despite</span> <span m=''580200''>not</span>
  <span m=''580560''>finishing</span> <span m=''580820''>on</span> <span m=''580930''>time</span>
  <span m=''581130''>because</span> <span m=''581330''>it</span> <span m=''581440''>may</span>
  <span m=''581590''>take</span> <span m=''581820''>some</span> <span m=''582010''>time</span>
  <span m=''582200''>for</span> <span m=''582290''>this</span> <span m=''582450''>to</span>
  <span m=''582740''>start.</span> <span m=''583430''>And</span> <span m=''583670''>then,</span>
  <span m=''584230''>it</span> <span m=''584330''>has</span> <span m=''584490''>to</span>
  <span m=''584580''>also</span> <span m=''584850''>tell</span> <span m=''585120''>this</span>
  <span m=''585290''>back</span> <span m=''585660''>OK,</span> <span m=''585780''>I</span>
  <span m=''586020''>am</span> <span m=''586250''>done.</span> <span m=''586490''>So</span>
  <span m=''586590''>there''s</span> <span m=''586780''>a lot</span> <span m=''586980''>of</span>
  <span m=''587060''>synchronization</span> <span m=''587780''>going</span> <span
  m=''588100''>on.</span> <span m=''588320''>Locks and</span> <span m=''588800''>unlocks.</span>
  <span m=''589390''>Here it''s</span> <span m=''590430''>called</span> <span m=''590650''>various</span>
  <span m=''590860''>synchronization</span> <span m=''590940''>here.</span> <span
  m=''594085''>And</span> <span m=''594400''>so</span> <span m=''594750''>if</span>
  <span m=''595020''>this</span> <span m=''595360''>work</span> <span m=''595670''>is</span>
  <span m=''595830''>small,</span> <span m=''597210''>this</span> <span m=''597400''>synchronization</span>
  <span m=''598110''>starts</span> <span m=''598400''>dominating.</span> </p><p><span
  m=''600070''>So</span> <span m=''602240''>what</span> <span m=''602510''>happens</span>
  <span m=''602810''>is</span> <span m=''603010''>[UNINTELLIGIBLE]</span> <span m=''603530''>fine</span>
  <span m=''603620''>grain</span> <span m=''603880''>parallelism.</span> <span m=''605490''>Do</span>
  <span m=''605660''>a</span> <span m=''605740''>little</span> <span m=''605920''>work</span>
  <span m=''606150''>in</span> <span m=''606270''>the</span> <span m=''606520''>parallel</span>
  <span m=''606680''>region,</span> <span m=''607450''>and</span> <span m=''608090''>synchronization</span>
  <span m=''608425''>will</span> <span m=''608760''>basically</span> <span m=''609090''>start</span>
  <span m=''609300''>dominating</span> <span m=''609410''>your</span> <span m=''609860''>time.</span>
  <span m=''610880''>So</span> <span m=''611060''>how</span> <span m=''611230''>do</span>
  <span m=''611430''>you</span> <span m=''611520''>take</span> <span m=''611730''>this?</span>
  <span m=''613310''>And</span> <span m=''613560''>sometimes</span> <span m=''614480''>when
  you</span> <span m=''614630''>run</span> <span m=''615050''>something</span> <span
  m=''615300''>parallel,</span> <span m=''615530''>it</span> <span m=''615720''>might</span>
  <span m=''615880''>even</span> <span m=''616120''>run slow</span> <span m=''617390''>because</span>
  <span m=''618120''>the</span> <span m=''618170''>amount</span> <span m=''618480''>of</span>
  <span m=''618580''>stuff</span> <span m=''619060''>in the</span> <span m=''619150''>parallel</span>
  <span m=''619560''>region</span> <span m=''619830''>is</span> <span m=''619910''>so</span>
  <span m=''620130''>small,</span> <span m=''621210''>[UNINTELLIGIBLE]</span> <span
  m=''621480''>will</span> <span m=''621700''>start</span> <span m=''622420''>dominating.</span>
  <span m=''622760''>And</span> <span m=''622940''>that''s not</span> <span m=''623050''>a</span>
  <span m=''623170''>good</span> <span m=''623400''>way.</span> </p><p><span m=''624010''>And</span>
  <span m=''624680''>also,</span> <span m=''625720''>sometimes</span> <span m=''626190''>you</span>
  <span m=''626280''>assume.</span> <span m=''626700''>And you</span> <span m=''626790''>keep</span>
  <span m=''626970''>increasing</span> <span m=''627490''>the</span> <span m=''627580''>number</span>
  <span m=''627870''>of</span> <span m=''627990''>cores.</span> <span m=''629240''>Hopefully,</span>
  <span m=''630050''>you</span> <span m=''630460''>want</span> <span m=''631130''>to</span>
  <span m=''631180''>see</span> <span m=''631330''>a nice</span> <span m=''631610''>parallelism</span>
  <span m=''632070''>increase,</span> <span m=''632540''>but</span> <span m=''632750''>it</span>
  <span m=''632840''>doesn''t,</span> <span m=''633585''>even</span> <span m=''634020''>though
  you</span> <span m=''634130''>have</span> <span m=''634380''>enough</span> <span
  m=''634580''>information.</span> <span m=''635090''>But</span> <span m=''635280''>that</span>
  <span m=''635470''>means</span> <span m=''635650''>you''re</span> <span m=''635820''>running</span>
  <span m=''636150''>a</span> <span m=''636430''>lot of</span> <span m=''636510''>small</span>
  <span m=''636830''>chunks,</span> <span m=''637530''>even</span> <span m=''637880''>though</span>
  <span m=''638000''>you</span> <span m=''638180''>seem</span> <span m=''638440''>to</span>
  <span m=''638530''>have</span> <span m=''638630''>a</span> <span m=''638650''>lot</span>
  <span m=''638750''>of</span> <span m=''638850''>parallelism</span> <span m=''639120''>available.</span>
  </p><p><span m=''642730''>And</span> <span m=''643390''>also,</span> <span m=''643670''>you
  can</span> <span m=''643850''>make sure the</span> <span m=''644210''>synchronization</span>
  <span m=''645930''>in</span> <span m=''646040''>the</span> <span m=''646160''>time
  in</span> <span m=''646310''>the</span> <span m=''646460''>parallel</span> <span
  m=''646620''>region.</span> <span m=''647210''>If</span> <span m=''647350''>the
  parallel</span> <span m=''647500''>regions</span> <span m=''647910''>are</span>
  <span m=''648140''>on</span> <span m=''648320''>a</span> <span m=''648540''>very</span>
  <span m=''648720''>short</span> <span m=''649040''>time,</span> <span m=''649780''>this</span>
  <span m=''650030''>happens.</span> <span m=''650670''>We saw</span> <span m=''651030''>this</span>
  <span m=''651190''>effect</span> <span m=''651960''>when</span> <span m=''652120''>we</span>
  <span m=''653540''>were</span> <span m=''653970''>doing</span> <span m=''654180''>Cilk.</span>
  <span m=''654780''>Remember?</span> </p><p><span m=''656030''>When did we</span>
  <span m=''656230''>see</span> <span m=''656760''>this</span> <span m=''658700''>granularity</span>
  <span m=''659260''>affecting</span> <span m=''659420''>Cilk?</span> <span m=''659450''>And</span>
  <span m=''659670''>what</span> <span m=''659870''>did</span> <span m=''660110''>he</span>
  <span m=''660480''>do?</span> <span m=''663900''>When you</span> <span m=''664050''>write</span>
  <span m=''664350''>Cilk</span> <span m=''664450''>programs.</span> <span m=''664910''>You</span>
  <span m=''665000''>write</span> <span m=''665140''>[UNINTELLIGIBLE]</span> <span
  m=''665660''>programs.</span> <span m=''666950''>Where</span> <span m=''667060''>did
  the</span> <span m=''667290''>granularity</span> <span m=''667590''>start</span>
  <span m=''668060''>showing</span> <span m=''668450''>up</span> <span m=''669660''>on</span>
  <span m=''669810''>us?</span> <span m=''672500''>It</span> <span m=''672650''>may
  not be</span> <span m=''672910''>exactly</span> <span m=''673270''>this</span> <span
  m=''673630''>because</span> <span m=''674400''>the</span> <span m=''674600''>scheduling</span>
  <span m=''675050''>is</span> <span m=''675160''>complicated.</span> <span m=''675430''>OK.</span>
  <span m=''675890''>Yes?</span> </p><p><span m=''676380''>AUDIENCE: The</span> <span
  m=''676872''>two</span> <span m=''677364''>by two matrix</span> <span m=''677856''>[INAUDIBLE]</span>
  </p><p><span m=''679280''>PROFESSOR: Yeah.</span> <span m=''679720''>Something like</span>
  <span m=''679860''>two by--</span> <span m=''680420''>for example,</span> <span
  m=''681170''>that''s</span> <span m=''681480''>the reason</span> <span m=''681910''>we</span>
  <span m=''682020''>wanted</span> <span m=''682590''>to</span> <span m=''682650''>have</span>
  <span m=''682800''>a</span> <span m=''682860''>large</span> <span m=''683260''>base</span>
  <span m=''683520''>case.</span> <span m=''684580''>Because</span> <span m=''684850''>if</span>
  <span m=''684960''>you</span> <span m=''685050''>didn''t</span> <span m=''685270''>put</span>
  <span m=''685390''>a</span> <span m=''685460''>large</span> <span m=''685690''>base
  case,</span> <span m=''686090''>it</span> <span m=''686530''>keeps</span> <span
  m=''686900''>dividing</span> <span m=''687530''>into</span> <span m=''687730''>smaller</span>
  <span m=''688050''>and</span> <span m=''688170''>smaller</span> <span m=''688530''>problems.</span>
  <span m=''690110''>And</span> <span m=''690780''>if</span> <span m=''691020''>the</span>
  <span m=''691130''>schedule</span> <span m=''691500''>is</span> <span m=''691750''>smart,</span>
  <span m=''692130''>it</span> <span m=''692430''>won''t be</span> <span m=''692580''>doing</span>
  <span m=''693080''>exactly</span> <span m=''693470''>this.</span> <span m=''693700''>But</span>
  <span m=''694920''>it''s</span> <span m=''695080''>always</span> <span m=''695440''>good</span>
  <span m=''695610''>to</span> <span m=''695670''>have</span> <span m=''695800''>these</span>
  <span m=''695910''>large</span> <span m=''696290''>granulated</span> <span m=''696850''>chunks</span>
  <span m=''697350''>at</span> <span m=''698230''>the</span> <span m=''698310''>bottom.</span>
  </p><p><span m=''701870''>So</span> <span m=''702050''>how</span> <span m=''702250''>to</span>
  <span m=''702330''>get</span> <span m=''702500''>[UNINTELLIGIBLE]</span> <span m=''703890''>granulated</span>
  <span m=''704120''>parallelism.</span> <span m=''705560''>What</span> <span m=''705770''>we</span>
  <span m=''705870''>need</span> <span m=''706040''>to</span> <span m=''706110''>do</span>
  <span m=''706300''>is</span> <span m=''706730''>reduce</span> <span m=''706990''>the</span>
  <span m=''707040''>number</span> <span m=''707370''>of</span> <span m=''707630''>[UNINTELLIGIBLE]</span>
  <span m=''708080''>equations.</span> <span m=''708770''>So</span> <span m=''708910''>you</span>
  <span m=''709030''>want</span> <span m=''709200''>to</span> <span m=''709600''>always</span>
  <span m=''710090''>try</span> <span m=''710260''>to</span> <span m=''710300''>look</span>
  <span m=''710470''>for</span> <span m=''710690''>the</span> <span m=''711040''>outer</span>
  <span m=''711290''>most</span> <span m=''711570''>loop</span> <span m=''711760''>you</span>
  <span m=''711850''>can</span> <span m=''712080''>get</span> <span m=''712890''>at</span>
  <span m=''713350''>all</span> <span m=''713460''>the</span> <span m=''713580''>really</span>
  <span m=''713670''>large</span> <span m=''714150''>independent</span> <span m=''714660''>regions.</span>
  <span m=''715080''>So</span> <span m=''715280''>you</span> <span m=''715430''>go</span>
  <span m=''715550''>look,</span> <span m=''715900''>and</span> <span m=''716300''>not</span>
  <span m=''716500''>[UNINTELLIGIBLE]</span> <span m=''717040''>thing</span> <span
  m=''717310''>you want</span> <span m=''717490''>to parallelize.</span> <span m=''717930''>You</span>
  <span m=''718040''>go</span> <span m=''718220''>up,</span> <span m=''718540''>up,</span>
  <span m=''718860''>up,</span> <span m=''719070''>up</span> <span m=''719350''>until</span>
  <span m=''719600''>the</span> <span m=''719700''>point</span> <span m=''720020''>you</span>
  <span m=''720320''>can</span> <span m=''720820''>parallelize.</span> <span m=''721165''>And</span>
  <span m=''721510''>that''s</span> <span m=''722310''>the</span> <span m=''722390''>best</span>
  <span m=''722630''>way</span> <span m=''722730''>to</span> <span m=''722810''>get</span>
  <span m=''723250''>good</span> <span m=''723530''>performance.</span> <span m=''725490''>OK?</span>
  </p><p><span m=''729580''>So</span> <span m=''730390''>if</span> <span m=''730550''>you</span>
  <span m=''730680''>really</span> <span m=''730990''>compare</span> <span m=''731210''>these</span>
  <span m=''731370''>three</span> <span m=''731760''>programs</span> <span m=''732240''>here,</span>
  <span m=''733110''>again,</span> <span m=''733850''>what</span> <span m=''734120''>you</span>
  <span m=''734310''>see--</span> <span m=''735210''>of</span> <span m=''735360''>course,</span>
  <span m=''735540''>this</span> <span m=''735700''>has</span> <span m=''735850''>no</span>
  <span m=''735980''>synchronization.</span> <span m=''736720''>This</span> <span
  m=''736930''>has</span> <span m=''737210''>n</span> <span m=''737640''>amount</span>
  <span m=''737930''>of</span> <span m=''738000''>synchronizations.</span> <span m=''739400''>Here</span>
  <span m=''739630''>in</span> <span m=''740130''>[UNINTELLIGIBLE]</span> <span m=''740560''>synchronization,</span>
  <span m=''740660''>that''s</span> <span m=''740870''>obviously</span> <span m=''741350''>a</span>
  <span m=''741370''>lot</span> <span m=''741610''>more</span> <span m=''741740''>synchronization</span>
  <span m=''742420''>going</span> <span m=''742730''>on.</span> <span m=''743210''>And</span>
  <span m=''743700''>that</span> <span m=''743850''>is</span> <span m=''744010''>where</span>
  <span m=''744160''>this</span> <span m=''744310''>[UNINTELLIGIBLE]</span> <span
  m=''744740''>comes from.</span> </p><p><span m=''747190''>OK.</span> <span m=''747620''>So</span>
  <span m=''747830''>now,</span> <span m=''748430''>I am</span> <span m=''748670''>switching</span>
  <span m=''749100''>a</span> <span m=''749150''>little</span> <span m=''749380''>bit</span>
  <span m=''749590''>in</span> <span m=''749750''>here.</span> <span m=''750260''>I</span>
  <span m=''750360''>want</span> <span m=''750560''>you</span> <span m=''750670''>guys</span>
  <span m=''751030''>to</span> <span m=''751410''>look</span> <span m=''751690''>at</span>
  <span m=''751770''>this</span> <span m=''751910''>program</span> <span m=''752370''>a</span>
  <span m=''752730''>little</span> <span m=''753090''>bit.</span> <span m=''753450''>So</span>
  <span m=''753620''>what</span> <span m=''753780''>am</span> <span m=''753920''>I</span>
  <span m=''754000''>doing</span> <span m=''754300''>here?</span> <span m=''755000''>I</span>
  <span m=''755190''>have</span> <span m=''756360''>two</span> <span m=''756840''>[UNINTELLIGIBLE].</span>
  <span m=''757580''>And</span> <span m=''758005''>I am</span> <span m=''758430''>just</span>
  <span m=''758630''>basically</span> <span m=''759330''>adding</span> <span m=''759820''>matrix</span>
  <span m=''760450''>B</span> <span m=''761370''>to</span> <span m=''761480''>matrix</span>
  <span m=''761910''>A.</span> <span m=''764320''>OK?</span> <span m=''765110''>And</span>
  <span m=''765570''>then</span> <span m=''765850''>I</span> <span m=''765930''>have</span>
  <span m=''766240''>another</span> <span m=''766600''>loop</span> <span m=''766860''>test</span>
  <span m=''767200''>here,</span> <span m=''767540''>adding</span> <span m=''767980''>matrix</span>
  <span m=''768130''>C</span> <span m=''768660''>to</span> <span m=''768720''>matrix</span>
  <span m=''769160''>A.</span> <span m=''769545''>And</span> <span m=''769930''>what</span>
  <span m=''770150''>am</span> <span m=''770390''>I</span> <span m=''770470''>doing</span>
  <span m=''770930''>in here?</span> <span m=''772120''>I am</span> <span m=''772420''>basically</span>
  <span m=''774230''>going</span> <span m=''774480''>through</span> <span m=''774740''>matrix</span>
  <span m=''774960''>A</span> <span m=''775160''>in</span> <span m=''775410''>another</span>
  <span m=''775740''>direction</span> <span m=''777110''>in here.</span> </p><p><span
  m=''779020''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''782310''>PROFESSOR: It''s</span>
  <span m=''782460''>not</span> <span m=''782730''>really</span> <span m=''783000''>a</span>
  <span m=''783070''>transpose.</span> <span m=''783700''>I''m</span> <span m=''783730''>not</span>
  <span m=''783970''>transposing.</span> <span m=''784590''>What</span> <span m=''784800''>I''m</span>
  <span m=''784960''>doing</span> <span m=''785320''>is</span> <span m=''785430''>I''m</span>
  <span m=''785830''>actually</span> <span m=''786080''>doing a</span> <span m=''786350''>mirror</span>
  <span m=''787770''>because</span> <span m=''788520''>the</span> <span m=''788660''>C</span>
  <span m=''788830''>gets</span> <span m=''789040''>mirrored</span> <span m=''789650''>on</span>
  <span m=''790090''>ix.</span> <span m=''790210''>It''s</span> <span m=''790475''>because</span>
  <span m=''790740''>[UNINTELLIGIBLE]</span> <span m=''791030''>ix</span> <span m=''791200''>[UNINTELLIGIBLE]</span>
  <span m=''791590''>the</span> <span m=''791930''>other</span> <span m=''792110''>direction.</span>
  <span m=''792425''>OK?</span> <span m=''792740''>So</span> <span m=''792880''>it''s</span>
  <span m=''792990''>not</span> <span m=''793090''>really</span> <span m=''793320''>a</span>
  <span m=''793410''>transpose.</span> <span m=''794400''>So</span> <span m=''794570''>I
  do a</span> <span m=''794650''>mirror</span> <span m=''794930''>addition.</span>
  <span m=''796960''>And</span> <span m=''797210''>then</span> <span m=''797360''>I''m</span>
  <span m=''797490''>asking</span> <span m=''798050''>for</span> <span m=''798500''>the</span>
  <span m=''798570''>two</span> <span m=''798840''>outer</span> <span m=''799010''>most</span>
  <span m=''799190''>loops</span> <span m=''799400''>to</span> <span m=''799490''>be</span>
  <span m=''799610''>parallel.</span> </p><p><span m=''802130''>So</span> <span m=''803000''>if</span>
  <span m=''803180''>you</span> <span m=''803260''>run</span> <span m=''803570''>this</span>
  <span m=''803730''>sequential--</span> <span m=''805440''>OK,</span> <span m=''805680''>you</span>
  <span m=''805800''>get</span> <span m=''805970''>about</span> <span m=''808720''>30</span>
  <span m=''809150''>milliseconds,</span> <span m=''809820''>I</span> <span m=''809870''>guess,</span>
  <span m=''810060''>to</span> <span m=''811100''>run in</span> <span m=''811540''>here.</span>
  <span m=''812120''>So</span> <span m=''812960''>that</span> <span m=''813170''>is</span>
  <span m=''813480''>in</span> <span m=''813590''>[UNINTELLIGIBLE].</span> <span m=''813700''>But
  if</span> <span m=''814020''>you''re</span> <span m=''814200''>running</span> <span
  m=''814380''>parallel,</span> <span m=''815000''>what</span> <span m=''815260''>do
  you</span> <span m=''815400''>get?</span> <span m=''815580''>Should</span> <span
  m=''815690''>you</span> <span m=''815800''>get</span> <span m=''816060''>faster
  or</span> <span m=''816510''>slower?</span> <span m=''820960''>OK.</span> <span
  m=''822310''>Anyone</span> <span m=''822330''>want to</span> <span m=''822610''>take</span>
  <span m=''822890''>a</span> <span m=''822950''>guess</span> <span m=''823410''>[UNINTELLIGIBLE]</span>
  <span m=''825200''>Sometimes</span> <span m=''825670''>some</span> <span m=''825840''>of</span>
  <span m=''825890''>these</span> <span m=''826070''>questions,</span> <span m=''826370''>you</span>
  <span m=''826460''>might</span> <span m=''826640''>not</span> <span m=''826890''>have
  enough</span> <span m=''827100''>information</span> <span m=''827640''>to answer.</span>
  <span m=''828040''>But</span> <span m=''828160''>it''s</span> <span m=''828460''>still</span>
  <span m=''828720''>good</span> <span m=''828990''>to</span> <span m=''829070''>just</span>
  <span m=''829330''>take</span> <span m=''829540''>a</span> <span m=''829600''>stand</span>
  <span m=''830060''>on</span> <span m=''830200''>one</span> <span m=''830360''>direction</span>
  <span m=''830750''>or</span> <span m=''830930''>another.</span> <span m=''831450''>How
  many</span> <span m=''831820''>people think</span> <span m=''832160''>it runs</span>
  <span m=''832380''>faster?</span> <span m=''834120''>How many</span> <span m=''834330''>people</span>
  <span m=''834540''>think it runs slower?</span> <span m=''836350''>OK.</span> <span
  m=''837750''>Some.</span> </p><p><span m=''839550''>Oops.</span> <span m=''841940''>What</span>
  <span m=''842170''>happened?</span> <span m=''847310''>What</span> <span m=''847540''>happened</span>
  <span m=''848040''>in</span> <span m=''848980''>here?</span> <span m=''859750''>Can</span>
  <span m=''859910''>anybody</span> <span m=''862020''>point</span> <span m=''862340''>out</span>
  <span m=''862500''>why</span> <span m=''863610''>it</span> <span m=''863800''>might</span>
  <span m=''864090''>be</span> <span m=''864250''>running</span> <span m=''864560''>slower</span>
  <span m=''865150''>parallely</span> <span m=''865410''>than</span> <span m=''865530''>running</span>
  <span m=''867440''>sequentially?</span> </p><p><span m=''871275''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''873220''>PROFESSOR: Yeah.</span> <span m=''873550''>There''s</span>
  <span m=''873890''>a</span> <span m=''874070''>cache</span> <span m=''874350''>issue.</span>
  <span m=''874760''>Watch</span> <span m=''875070''>the</span> <span m=''875190''>possible</span>
  <span m=''875530''>cache</span> <span m=''875650''>issue</span> <span m=''875820''>in</span>
  <span m=''875920''>here.</span> </p><p><span m=''878611''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''881600''>PROFESSOR: Yeah.</span> <span m=''884610''>If</span> <span
  m=''884940''>you</span> <span m=''885060''>think</span> <span m=''885350''>about,</span>
  <span m=''886980''>the</span> <span m=''887430''>first</span> <span m=''888380''>equations</span>
  <span m=''889150''>of,</span> <span m=''889510''>I</span> <span m=''890060''>guess,</span>
  <span m=''890390''>the</span> <span m=''890610''>first</span> <span m=''890840''>core--</span>
  <span m=''891080''>I</span> <span m=''891530''>have</span> <span m=''891690''>some</span>
  <span m=''891860''>diagram.</span> <span m=''892230''>I''ll</span> <span m=''892330''>show
  it</span> <span m=''892620''>to</span> <span m=''892800''>you</span> <span m=''892980''>in</span>
  <span m=''893190''>there.</span> <span m=''893740''>And</span> <span m=''893960''>here,</span>
  <span m=''894650''>only</span> <span m=''894920''>the</span> <span m=''895040''>last</span>
  <span m=''895630''>data</span> <span m=''896040''>elements</span> <span m=''896230''>we''ll</span>
  <span m=''896580''>get</span> <span m=''896650''>for the</span> <span m=''896850''>first</span>
  <span m=''897630''>iterations</span> <span m=''898170''>because</span> <span m=''898390''>we
  are</span> <span m=''898550''>going</span> <span m=''898760''>in the</span> <span
  m=''898870''>other</span> <span m=''898980''>direction.</span> <span m=''899970''>So</span>
  <span m=''900200''>if</span> <span m=''900490''>you</span> <span m=''901410''>look</span>
  <span m=''901670''>at</span> <span m=''902020''>it</span> <span m=''902240''>a little</span>
  <span m=''902390''>more</span> <span m=''902540''>deeply</span> <span m=''903270''>into</span>
  <span m=''903500''>what''s</span> <span m=''903750''>going</span> <span m=''904030''>on.</span>
  </p><p><span m=''904980''>Number</span> <span m=''905310''>of</span> <span m=''905410''>instructions</span>
  <span m=''907200''>seem</span> <span m=''907470''>to be a little</span> <span m=''907950''>higher.</span>
  <span m=''908710''>This</span> <span m=''908940''>one</span> <span m=''909100''>I</span>
  <span m=''909160''>couldn''t</span> <span m=''909590''>actually</span> <span m=''909680''>explain</span>
  <span m=''910020''>why</span> <span m=''910650''>this</span> <span m=''910890''>might</span>
  <span m=''911090''>be</span> <span m=''911180''>the</span> <span m=''911310''>case</span>
  <span m=''911600''>in</span> <span m=''911730''>here.</span> <span m=''913270''>If</span>
  <span m=''913430''>anybody</span> <span m=''913750''>has</span> <span m=''913980''>an</span>
  <span m=''914460''>idea,</span> <span m=''914950''>you can</span> <span m=''915120''>say</span>
  <span m=''915220''>that.</span> <span m=''915530''>But</span> <span m=''915760''>this</span>
  <span m=''915930''>was</span> <span m=''916080''>kind</span> <span m=''916170''>of</span>
  <span m=''916270''>[UNINTELLIGIBLE].</span> <span m=''918620''>This</span> <span
  m=''918800''>might</span> <span m=''919080''>be</span> <span m=''920270''>[UNINTELLIGIBLE]</span>
  <span m=''920670''>the</span> <span m=''920820''>cycles.</span> <span m=''921500''>Huh.</span>
  <span m=''927830''>OK.</span> <span m=''928600''>I</span> <span m=''928690''>can</span>
  <span m=''928860''>explain</span> <span m=''929140''>this.</span> </p><p><span m=''930610''>Because</span>
  <span m=''930940''>this</span> <span m=''931090''>is</span> <span m=''931210''>a</span>
  <span m=''931270''>sequential</span> <span m=''931700''>run,</span> <span m=''932980''>this</span>
  <span m=''933200''>is</span> <span m=''933430''>a</span> <span m=''933850''>sum</span>
  <span m=''934260''>total</span> <span m=''934460''>of</span> <span m=''934660''>a</span>
  <span m=''934730''>parallel</span> <span m=''934990''>run.</span> <span m=''936380''>So</span>
  <span m=''936580''>because</span> <span m=''936950''>of</span> <span m=''937080''>all</span>
  <span m=''937310''>the</span> <span m=''937420''>overhead</span> <span m=''937640''>that</span>
  <span m=''938040''>happens</span> <span m=''938590''>because</span> <span m=''940150''>this</span>
  <span m=''940400''>was</span> <span m=''940560''>running</span> <span m=''940860''>on,</span>
  <span m=''940980''>I</span> <span m=''941190''>think,</span> <span m=''941810''>an
  eight</span> <span m=''942270''>core</span> <span m=''942430''>machine.</span> <span
  m=''943200''>So</span> <span m=''943500''>you''re</span> <span m=''943690''>running</span>
  <span m=''944150''>eight</span> <span m=''944520''>times</span> <span m=''944840''>of</span>
  <span m=''944920''>small</span> <span m=''945240''>companies.</span> <span m=''945630''>There''s
  a lot</span> <span m=''946070''>of overhead</span> <span m=''946580''>that</span>
  <span m=''946770''>goes</span> <span m=''947020''>around,</span> <span m=''947620''>synchronization,</span>
  <span m=''948420''>and</span> <span m=''948520''>stuff</span> <span m=''948790''>like</span>
  <span m=''949020''>that.</span> <span m=''949320''>So</span> <span m=''949460''>a</span>
  <span m=''949480''>number</span> <span m=''949730''>of</span> <span m=''949820''>instructions</span>
  <span m=''950280''>just</span> <span m=''950480''>blows</span> <span m=''950740''>up.</span>
  <span m=''952050''>But</span> <span m=''952500''>for</span> <span m=''952860''>each</span>
  <span m=''953210''>core,</span> <span m=''953770''>you</span> <span m=''953880''>don''t</span>
  <span m=''954020''>have</span> <span m=''955080''>this</span> <span m=''955260''>blow
  up.</span> </p><p><span m=''955998''>AUDIENCE: [INAUDIBLE]</span> <span m=''959484''>Cilk?</span>
  <span m=''959982''>Because</span> <span m=''960480''>does</span> <span m=''960978''>Cilk</span>
  <span m=''961476''>have</span> <span m=''961974''>different</span> <span m=''962472''>processor</span>
  <span m=''962970''>affinity,</span> <span m=''963468''>things</span> <span m=''963966''>that</span>
  <span m=''964464''>open</span> <span m=''964962''>[UNINTELLIGIBLE]?</span> <span
  m=''966456''>Because</span> <span m=''966954''>it seems like</span> <span m=''968448''>if</span>
  <span m=''969444''>the</span> <span m=''969942''>program,</span> <span m=''970938''>the</span>
  <span m=''971436''>language--</span> </p><p><span m=''971960''>PROFESSOR: [INAUDIBLE].</span>
  <span m=''973786''>Let''s</span> <span m=''974140''>see</span> <span m=''974800''>if</span>
  <span m=''975135''>we</span> <span m=''975470''>can</span> <span m=''975630''>process</span>
  <span m=''975750''>the</span> <span m=''976110''>affinity</span> <span m=''976610''>information</span>
  <span m=''977300''>or</span> <span m=''977690''>if not.</span> <span m=''978670''>It''s</span>
  <span m=''979180''>just</span> <span m=''979540''>pure</span> <span m=''980130''>[UNINTELLIGIBLE].</span>
  </p><p><span m=''981330''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''983780''>PROFESSOR:
  Yeah.</span> <span m=''984600''>I</span> <span m=''984690''>mean</span> <span m=''984920''>if</span>
  <span m=''985030''>you</span> <span m=''985260''>like</span> <span m=''985470''>executed</span>
  <span m=''986050''>locally</span> <span m=''986550''>if</span> <span m=''986680''>you</span>
  <span m=''986850''>have</span> <span m=''987030''>good</span> <span m=''988060''>cache</span>
  <span m=''988430''>[UNINTELLIGIBLE]</span> <span m=''988900''>with</span> <span
  m=''989110''>them.</span> <span m=''989210''>But</span> <span m=''989340''>if</span>
  <span m=''989470''>there''s</span> <span m=''989700''>no</span> <span m=''989870''>cache</span>
  <span m=''990040''>[UNINTELLIGIBLE]</span> <span m=''991060''>you</span> <span m=''991170''>might</span>
  <span m=''991450''>steal</span> <span m=''991630''>something</span> <span m=''992080''>where</span>
  <span m=''992290''>data</span> <span m=''992490''>might</span> <span m=''992670''>be</span>
  <span m=''992770''>somewhere</span> <span m=''993020''>else.</span> </p><p><span
  m=''993887''>AUDIENCE: But</span> <span m=''994374''>you''ll</span> <span m=''994861''>still</span>
  <span m=''995348''>mimic</span> <span m=''995835''>the</span> <span m=''996322''>cache</span>
  <span m=''996809''>behavior,</span> <span m=''997296''>considerably,</span> <span
  m=''999244''>except for</span> <span m=''999731''>when</span> <span m=''1000218''>you</span>
  <span m=''1000705''>steal.</span> <span m=''1002166''>[INAUDIBLE]</span> </p><p><span
  m=''1004601''>PROFESSOR: Yeah.</span> <span m=''1005088''>So</span> <span m=''1005575''>OK.</span>
  <span m=''1006070''>We</span> <span m=''1006370''>don''t</span> <span m=''1006670''>have</span>
  <span m=''1006975''>a</span> <span m=''1007280''>mic in here.</span> <span m=''1009450''>OK.</span>
  <span m=''1009640''>There''s</span> <span m=''1009880''>a mic.</span> <span m=''1010570''>There</span>
  <span m=''1010630''>we go.</span> <span m=''1014380''>But</span> <span m=''1014600''>if</span>
  <span m=''1014730''>you</span> <span m=''1014860''>have</span> <span m=''1015170''>two</span>
  <span m=''1015250''>different</span> <span m=''1015450''>of</span> <span m=''1015500''>these</span>
  <span m=''1015640''>regions,</span> <span m=''1016440''>the</span> <span m=''1016650''>way</span>
  <span m=''1016990''>the</span> <span m=''1017110''>parallelization</span> <span
  m=''1017820''>happens</span> <span m=''1020020''>can</span> <span m=''1020190''>be</span>
  <span m=''1020290''>different.</span> </p><p><span m=''1021985''>AUDIENCE: In</span>
  <span m=''1022280''>Cilk,</span> <span m=''1022680''>what</span> <span m=''1022850''>happens</span>
  <span m=''1023340''>is</span> <span m=''1025510''>the</span> <span m=''1025960''>code</span>
  <span m=''1026280''>is</span> <span m=''1026440''>mimicking,</span> <span m=''1027500''>for</span>
  <span m=''1027589''>the</span> <span m=''1027790''>most</span> <span m=''1027980''>part,</span>
  <span m=''1028250''>exactly</span> <span m=''1028819''>what</span> <span m=''1029140''>the</span>
  <span m=''1029210''>C</span> <span m=''1029490''>or</span> <span m=''1029740''>C++</span>
  <span m=''1030339''>code</span> <span m=''1030569''>would</span> <span m=''1030690''>be</span>
  <span m=''1030819''>doing.</span> <span m=''1031930''>And</span> <span m=''1032160''>so</span>
  <span m=''1032569''>you</span> <span m=''1032710''>get</span> <span m=''1032849''>exactly</span>
  <span m=''1033359''>the</span> <span m=''1033450''>same</span> <span m=''1033920''>cache</span>
  <span m=''1034329''>hits</span> <span m=''1034599''>and</span> <span m=''1034730''>misses.</span>
  <span m=''1035339''>Except</span> <span m=''1036599''>when</span> <span m=''1036790''>you</span>
  <span m=''1036890''>steal,</span> <span m=''1038060''>it''s</span> <span m=''1038280''>like</span>
  <span m=''1038500''>starting</span> <span m=''1038859''>over</span> <span m=''1039190''>with</span>
  <span m=''1039329''>an</span> <span m=''1039690''>empty</span> <span m=''1040000''>cache.</span>
  <span m=''1041550''>OK?</span> <span m=''1041770''>But</span> <span m=''1041940''>as</span>
  <span m=''1042069''>long</span> <span m=''1042359''>as</span> <span m=''1042450''>you</span>
  <span m=''1042550''>have</span> <span m=''1042650''>sufficient</span> <span m=''1043119''>parallelism,</span>
  <span m=''1044520''>the</span> <span m=''1044589''>steals</span> <span m=''1044970''>don''t</span>
  <span m=''1045410''>occur</span> <span m=''1047670''>very</span> <span m=''1047900''>often.</span>
  <span m=''1049080''>And</span> <span m=''1049230''>so</span> <span m=''1049420''>therefore,</span>
  <span m=''1050040''>you</span> <span m=''1050260''>end</span> <span m=''1050440''>up</span>
  <span m=''1050610''>getting</span> <span m=''1050910''>the</span> <span m=''1051000''>same</span>
  <span m=''1051250''>kind</span> <span m=''1051470''>of</span> <span m=''1051520''>behavior</span>
  <span m=''1052050''>that</span> <span m=''1052160''>you</span> <span m=''1052250''>would</span>
  <span m=''1052370''>get</span> <span m=''1052540''>out</span> <span m=''1052720''>of</span>
  <span m=''1052810''>the</span> <span m=''1052880''>serial</span> <span m=''1053520''>code.</span>
  </p><p><span m=''1053740''>PROFESSOR: Yeah.</span> <span m=''1054120''>But</span>
  <span m=''1054400''>Charles,</span> <span m=''1054680''>in</span> <span m=''1054880''>this</span>
  <span m=''1055200''>one,</span> <span m=''1056020''>because</span> <span m=''1056500''>you</span>
  <span m=''1056610''>had</span> <span m=''1056710''>to</span> <span m=''1056790''>steal</span>
  <span m=''1057250''>everything</span> <span m=''1057720''>here,</span> <span m=''1058550''>the</span>
  <span m=''1058660''>between</span> <span m=''1059220''>here</span> <span m=''1059450''>and</span>
  <span m=''1059660''>here,</span> <span m=''1060530''>the</span> <span m=''1060690''>parallelism</span>
  <span m=''1061240''>would</span> <span m=''1061600''>be different.</span> </p><p><span
  m=''1061830''>AUDIENCE: There would be no</span> <span m=''1062050''>affinity</span>
  <span m=''1062490''>between</span> <span m=''1062850''>those</span> <span m=''1063070''>two.</span>
  </p><p><span m=''1063220''>PROFESSOR: No</span> <span m=''1063300''>[? affinity
  ?]</span> <span m=''1063550''>will</span> <span m=''1063760''>be</span> <span m=''1063880''>there.</span>
  <span m=''1064380''>Yeah,</span> <span m=''1064600''>exactly.</span> <span m=''1065300''>So</span>
  <span m=''1066000''>in</span> <span m=''1066220''>the</span> <span m=''1066370''>sequential</span>
  <span m=''1066820''>one,</span> <span m=''1067150''>everything</span> <span m=''1067580''>that</span>
  <span m=''1067800''>fits</span> <span m=''1067980''>in</span> <span m=''1068080''>the</span>
  <span m=''1068180''>cache,</span> <span m=''1068870''>so</span> <span m=''1069000''>that</span>
  <span m=''1069260''>would</span> <span m=''1069740''>be affinity</span> <span m=''1070020''>because</span>
  <span m=''1070390''>we are</span> <span m=''1070590''>not</span> <span m=''1070720''>doing</span>
  <span m=''1071210''>parallelism.</span> <span m=''1071790''>And</span> <span m=''1071930''>that''s</span>
  <span m=''1072080''>what</span> <span m=''1072200''>I</span> <span m=''1072330''>think</span>
  <span m=''1072630''>happened</span> <span m=''1072920''>here.</span> <span m=''1073510''>Because</span>
  <span m=''1073910''>you</span> <span m=''1074090''>had</span> <span m=''1074240''>no</span>
  <span m=''1074640''>[? affinity-- ?]</span> </p><p><span m=''1074990''>AUDIENCE:
  No in a serial code,</span> <span m=''1075260''>there''s</span> <span m=''1075440''>no</span>
  <span m=''1075570''>[? affinity. ?]</span> </p><p><span m=''1077960''>PROFESSOR:
  No.</span> <span m=''1078070''>Serial</span> <span m=''1078300''>code--</span> <span
  m=''1078410''>if</span> <span m=''1078610''>this</span> <span m=''1079410''>fits</span>
  <span m=''1079720''>in</span> <span m=''1079830''>the</span> <span m=''1079940''>cache,</span>
  <span m=''1080290''>it''s</span> <span m=''1080400''>then</span> <span m=''1080660''>running</span>
  <span m=''1080920''>on one</span> <span m=''1081140''>core.</span> <span m=''1083090''>So</span>
  <span m=''1083270''>if</span> <span m=''1083410''>it</span> <span m=''1083560''>fits</span>
  <span m=''1083800''>in</span> <span m=''1084420''>the</span> <span m=''1084510''>one</span>
  <span m=''1084730''>core''s</span> <span m=''1085050''>cache,</span> <span m=''1085550''>you''re</span>
  <span m=''1085740''>happy.</span> </p><p><span m=''1087900''>AUDIENCE: So</span>
  <span m=''1088110''>the</span> <span m=''1088310''>issue</span> <span m=''1088600''>is--</span>
  <span m=''1088830''>right--</span> <span m=''1089110''>is</span> <span m=''1089840''>if</span>
  <span m=''1090040''>you</span> <span m=''1090240''>only</span> <span m=''1090430''>access</span>
  <span m=''1090770''>it</span> <span m=''1090830''>once,</span> <span m=''1091160''>by</span>
  <span m=''1091270''>the</span> <span m=''1091360''>time</span> <span m=''1091650''>you</span>
  <span m=''1092450''>fill</span> <span m=''1092730''>up</span> <span m=''1092940''>the</span>
  <span m=''1093290''>cache--</span> <span m=''1094860''>It takes some</span> <span
  m=''1095050''>time</span> <span m=''1095310''>to</span> <span m=''1095410''>fill
  up</span> <span m=''1095620''>the</span> <span m=''1095710''>cache</span> <span
  m=''1096030''>to</span> <span m=''1096120''>get</span> <span m=''1096280''>them</span>
  <span m=''1096600''>synchronized.</span> </p><p><span m=''1097280''>PROFESSOR: So</span>
  <span m=''1097460''>it fits</span> <span m=''1097930''>in the</span> <span m=''1098110''>one
  core''s</span> <span m=''1098380''>cache,</span> <span m=''1098650''>it''s</span>
  <span m=''1098790''>OK.</span> <span m=''1099050''>Otherwise,</span> <span m=''1099460''>it</span>
  <span m=''1099940''>has</span> <span m=''1100130''>no</span> <span m=''1100260''>affinity</span>
  <span m=''1100760''>in here.</span> <span m=''1101210''>So</span> <span m=''1101430''>the</span>
  <span m=''1101570''>key</span> <span m=''1101870''>difference</span> <span m=''1102340''>in</span>
  <span m=''1102510''>here</span> <span m=''1102860''>is,</span> <span m=''1104260''>of</span>
  <span m=''1104480''>course,</span> <span m=''1104700''>CPI</span> <span m=''1105020''>is</span>
  <span m=''1105180''>slow.</span> <span m=''1106290''>We</span> <span m=''1106400''>don''t</span>
  <span m=''1106570''>know</span> <span m=''1106640''>exactly</span> <span m=''1107000''>why.</span>
  <span m=''1107530''>But</span> <span m=''1107790''>in</span> <span m=''1107900''>[UNINTELLIGIBLE].</span>
  <span m=''1108910''>So</span> <span m=''1109060''>what</span> <span m=''1109210''>you</span>
  <span m=''1109370''>find</span> <span m=''1109840''>is that</span> <span m=''1110170''>there''s</span>
  <span m=''1110340''>a</span> <span m=''1110380''>huge</span> <span m=''1110810''>amount</span>
  <span m=''1111050''>of</span> <span m=''1111170''>cache</span> <span m=''1111480''>in</span>
  <span m=''1111630''>[UNINTELLIGIBLE]</span> <span m=''1112150''>going</span> <span
  m=''1112400''>on.</span> <span m=''1113660''>So</span> <span m=''1113800''>that</span>
  <span m=''1114040''>should</span> <span m=''1114250''>give</span> <span m=''1114460''>you</span>
  <span m=''1114640''>a</span> <span m=''1114690''>feeling</span> <span m=''1115060''>of
  what''s</span> <span m=''1115290''>going</span> <span m=''1115520''>on.</span> <span
  m=''1115660''>So</span> <span m=''1115770''>let''s</span> <span m=''1115970''>look</span>
  <span m=''1116110''>at</span> <span m=''1116250''>what</span> <span m=''1116460''>might</span>
  <span m=''1116630''>happen.</span> </p><p><span m=''1117370''>So</span> <span m=''1119350''>I''m</span>
  <span m=''1119620''>showing</span> <span m=''1120510''>this</span> <span m=''1120820''>matches</span>
  <span m=''1121110''>[UNINTELLIGIBLE]</span> <span m=''1122070''>last</span> <span
  m=''1122410''>year</span> <span m=''1124510''>on--</span> <span m=''1124580''>what</span>
  <span m=''1124850''>we had</span> <span m=''1125040''>were</span> <span m=''1125200''>Cagnode</span>
  <span m=''1125360''>machines</span> <span m=''1126680''>that</span> <span m=''1126950''>were</span>
  <span m=''1127110''>basically</span> <span m=''1127760''>code</span> <span m=''1128060''>to</span>
  <span m=''1128280''>quad</span> <span m=''1128560''>processor.</span> <span m=''1129130''>So
  we</span> <span m=''1129340''>had</span> <span m=''1129820''>eight codes in</span>
  <span m=''1129970''>here.</span> <span m=''1130620''>And</span> <span m=''1131810''>I</span>
  <span m=''1131940''>put</span> <span m=''1132140''>them--</span> <span m=''1132630''>you
  don''t have</span> <span m=''1132730''>to now look</span> <span m=''1133070''>at</span>
  <span m=''1133180''>this</span> <span m=''1133350''>table.</span> <span m=''1133680''>I</span>
  <span m=''1133830''>put</span> <span m=''1134020''>them</span> <span m=''1134140''>in</span>
  <span m=''1134280''>the</span> <span m=''1135030''>slides</span> <span m=''1135460''>so</span>
  <span m=''1135910''>you</span> <span m=''1136080''>can</span> <span m=''1136260''>look</span>
  <span m=''1136400''>at</span> <span m=''1136450''>it</span> <span m=''1136540''>later.</span>
  </p><p><span m=''1137210''>And</span> <span m=''1137410''>so</span> <span m=''1137510''>this</span>
  <span m=''1137720''>is</span> <span m=''1137930''>the</span> <span m=''1138030''>last</span>
  <span m=''1138390''>year''s</span> <span m=''1138550''>machine.</span> <span m=''1138920''>And</span>
  <span m=''1139060''>of</span> <span m=''1139240''>course,</span> <span m=''1139510''>this</span>
  <span m=''1139930''>year''s</span> <span m=''1140110''>machine</span> <span m=''1140390''>is</span>
  <span m=''1140510''>different.</span> <span m=''1141360''>We</span> <span m=''1141520''>have</span>
  <span m=''1141850''>two</span> <span m=''1142855''>six</span> <span m=''1143290''>core</span>
  <span m=''1143350''>processors</span> <span m=''1144300''>in</span> <span m=''1144400''>here.</span>
  <span m=''1144610''>So</span> <span m=''1144740''>this</span> <span m=''1144920''>is</span>
  <span m=''1145040''>what</span> <span m=''1145200''>we</span> <span m=''1145470''>[UNINTELLIGIBLE]</span>
  <span m=''1146330''>this</span> <span m=''1146410''>year.</span> <span m=''1147650''>[UNINTELLIGIBLE]</span>
  <span m=''1149380''>OK.</span> </p><p><span m=''1150390''>And</span> <span m=''1150930''>so</span>
  <span m=''1151890''>right</span> <span m=''1152080''>now,</span> <span m=''1152270''>I''m</span>
  <span m=''1152470''>showing</span> <span m=''1152820''>numbers</span> <span m=''1153160''>for</span>
  <span m=''1153240''>this</span> <span m=''1153470''>one.</span> <span m=''1153670''>And</span>
  <span m=''1154000''>later, I</span> <span m=''1154130''>will</span> <span m=''1154270''>show</span>
  <span m=''1154440''>what</span> <span m=''1154610''>happened</span> <span m=''1155090''>in</span>
  <span m=''1155360''>the</span> <span m=''1155830''>[UNINTELLIGIBLE].</span> <span
  m=''1156770''>So</span> <span m=''1157400''>if</span> <span m=''1157800''>you</span>
  <span m=''1157910''>look</span> <span m=''1158090''>at</span> <span m=''1158180''>a</span>
  <span m=''1158250''>cache--</span> <span m=''1159360''>so</span> <span m=''1159780''>what</span>
  <span m=''1159990''>happened</span> <span m=''1160430''>is</span> <span m=''1163420''>each</span>
  <span m=''1163860''>of</span> <span m=''1163980''>the</span> <span m=''1164080''>data</span>
  <span m=''1164430''>items</span> <span m=''1164780''>in</span> <span m=''1164880''>the</span>
  <span m=''1164970''>cache</span> <span m=''1165390''>can</span> <span m=''1165670''>be</span>
  <span m=''1165900''>in multiple</span> <span m=''1166060''>states.</span> <span
  m=''1167340''>This</span> <span m=''1167410''>is</span> <span m=''1167590''>called</span>
  <span m=''1167860''>MSI</span> <span m=''1168230''>protocol</span> <span m=''1168800''>here.</span>
  <span m=''1169600''>What</span> <span m=''1169840''>that</span> <span m=''1170060''>means</span>
  <span m=''1170480''>is</span> <span m=''1170870''>the</span> <span m=''1171410''>item</span>
  <span m=''1171760''>might</span> <span m=''1172070''>be</span> <span m=''1172180''>modified.</span>
  <span m=''1173120''>If</span> <span m=''1173410''>it is</span> <span m=''1173640''>modified,</span>
  <span m=''1174160''>it</span> <span m=''1174260''>can</span> <span m=''1174470''>be</span>
  <span m=''1174580''>only</span> <span m=''1174790''>in</span> <span m=''1174980''>one</span>
  <span m=''1175220''>cache.</span> </p><p><span m=''1176490''>If</span> <span m=''1176690''>anybody</span>
  <span m=''1177120''>else</span> <span m=''1177300''>wants</span> <span m=''1177520''>to</span>
  <span m=''1177600''>touch it,</span> <span m=''1178270''>it</span> <span m=''1179000''>has</span>
  <span m=''1179140''>to</span> <span m=''1179690''>get</span> <span m=''1179860''>it</span>
  <span m=''1179980''>out</span> <span m=''1180100''>of</span> <span m=''1180220''>the</span>
  <span m=''1180300''>modified</span> <span m=''1180750''>state.</span> <span m=''1182340''>Or
  it</span> <span m=''1182680''>can</span> <span m=''1182900''>be</span> <span m=''1183000''>sharing.</span>
  <span m=''1183670''>Sharing</span> <span m=''1184170''>means</span> <span m=''1184410''>it''s</span>
  <span m=''1184660''>reading.</span> <span m=''1186190''>So</span> <span m=''1186330''>that</span>
  <span m=''1186570''>means</span> <span m=''1186920''>that</span> <span m=''1187190''>item</span>
  <span m=''1187700''>is</span> <span m=''1188280''>read</span> <span m=''1188720''>by</span>
  <span m=''1188850''>multiple</span> <span m=''1189390''>people.</span> <span m=''1189780''>And</span>
  <span m=''1190000''>that</span> <span m=''1190220''>can have</span> <span m=''1190390''>multiple</span>
  <span m=''1190700''>covers.</span> <span m=''1191160''>So</span> <span m=''1191270''>sharing</span>
  <span m=''1191860''>items</span> <span m=''1192190''>can</span> <span m=''1192380''>be</span>
  <span m=''1192490''>in</span> <span m=''1192590''>multiple</span> <span m=''1193020''>places.</span>
  </p><p><span m=''1195890''>However</span> <span m=''1196390''>if you''re</span>
  <span m=''1196880''>modifying,</span> <span m=''1197805''>[UNINTELLIGIBLE]</span>
  <span m=''1199220''>items</span> <span m=''1199900''>in</span> <span m=''1200030''>everybody</span>
  <span m=''1200450''>else.</span> <span m=''1200890''>So</span> <span m=''1201010''>that</span>
  <span m=''1201190''>means</span> <span m=''1201390''>if</span> <span m=''1201500''>I</span>
  <span m=''1201560''>modify</span> <span m=''1202000''>something,</span> <span m=''1203020''>it</span>
  <span m=''1203130''>can</span> <span m=''1203410''>only</span> <span m=''1203660''>be</span>
  <span m=''1203850''>in</span> <span m=''1203940''>mine.</span> <span m=''1204230''>If</span>
  <span m=''1204300''>other</span> <span m=''1204620''>people</span> <span m=''1205240''>had</span>
  <span m=''1205490''>that</span> <span m=''1205690''>data,</span> <span m=''1205970''>I
  had</span> <span m=''1206250''>to</span> <span m=''1206280''>go in and</span> <span
  m=''1206670''>validate</span> <span m=''1206780''>this.</span> <span m=''1207070''>So</span>
  <span m=''1207210''>if</span> <span m=''1207360''>you</span> <span m=''1207510''>modify</span>
  <span m=''1207920''>this,</span> <span m=''1208170''>I</span> <span m=''1208250''>had</span>
  <span m=''1208350''>to</span> <span m=''1208450''>go in</span> <span m=''1208560''>and</span>
  <span m=''1208660''>validate</span> <span m=''1208940''>it.</span> <span m=''1209470''>So</span>
  <span m=''1209670''>that''s</span> <span m=''1209820''>a</span> <span m=''1209970''>sharing</span>
  <span m=''1210550''>state.</span> <span m=''1210740''>That</span> <span m=''1210870''>means</span>
  <span m=''1211060''>I''m</span> <span m=''1211230''>[UNINTELLIGIBLE]</span> <span
  m=''1211490''>everybody</span> <span m=''1211910''>[UNINTELLIGIBLE]</span> <span
  m=''1213130''>read</span> <span m=''1213460''>this.</span> <span m=''1213880''>But</span>
  <span m=''1214150''>if I</span> <span m=''1214770''>ever</span> <span m=''1214830''>want</span>
  <span m=''1215070''>to</span> <span m=''1215170''>change</span> <span m=''1215560''>that,</span>
  <span m=''1215750''>I</span> <span m=''1215820''>have to</span> <span m=''1216040''>go
  in</span> <span m=''1216160''>and</span> <span m=''1216290''>validate</span> <span
  m=''1216740''>this</span> <span m=''1216920''>one.</span> </p><p><span m=''1217780''>So</span>
  <span m=''1217930''>what</span> <span m=''1218090''>that</span> <span m=''1218310''>means</span>
  <span m=''1218530''>is</span> <span m=''1218670''>when</span> <span m=''1218860''>I</span>
  <span m=''1218910''>start</span> <span m=''1219180''>writing,</span> <span m=''1220140''>I</span>
  <span m=''1220340''>am validating</span> <span m=''1220530''>it</span> <span m=''1220660''>from</span>
  <span m=''1221280''>everybody.</span> <span m=''1221750''>So</span> <span m=''1222060''>even</span>
  <span m=''1222410''>if</span> <span m=''1222540''>everybody</span> <span m=''1223050''>kept</span>
  <span m=''1223210''>a</span> <span m=''1223370''>copy</span> <span m=''1224500''>and</span>
  <span m=''1224620''>they</span> <span m=''1224730''>start</span> <span m=''1225150''>modifying,</span>
  <span m=''1225980''>I</span> <span m=''1226100''>had</span> <span m=''1226310''>to</span>
  <span m=''1226360''>get</span> <span m=''1227530''>my</span> <span m=''1227780''>own</span>
  <span m=''1227990''>copy.</span> <span m=''1228540''>And</span> <span m=''1228690''>everybody</span>
  <span m=''1228810''>else</span> <span m=''1228890''>will</span> <span m=''1229050''>invalidate.</span>
  <span m=''1230000''>And</span> <span m=''1230190''>then,</span> <span m=''1230370''>if</span>
  <span m=''1230850''>somebody</span> <span m=''1231200''>else</span> <span m=''1231350''>wanted</span>
  <span m=''1231500''>to</span> <span m=''1231540''>read--</span> <span m=''1232260''>for</span>
  <span m=''1232510''>example,</span> <span m=''1232960''>if</span> <span m=''1233080''>this</span>
  <span m=''1233290''>guy</span> <span m=''1233400''>wants</span> <span m=''1233640''>to</span>
  <span m=''1233690''>read--</span> <span m=''1234410''>basically,</span> <span m=''1235000''>this</span>
  <span m=''1235200''>has</span> <span m=''1235360''>to</span> <span m=''1235470''>make</span>
  <span m=''1235730''>this</span> <span m=''1235890''>a</span> <span m=''1235960''>sharing</span>
  <span m=''1236830''>and</span> <span m=''1237080''>back</span> <span m=''1237360''>to</span>
  <span m=''1237640''>sharing.</span> <span m=''1237950''>That</span> <span m=''1238120''>means</span>
  <span m=''1238270''>I</span> <span m=''1238500''>have to get</span> <span m=''1238650''>the</span>
  <span m=''1238730''>value</span> <span m=''1238960''>13,</span> <span m=''1239430''>propogate
  it,</span> <span m=''1239930''>and</span> <span m=''1240080''>this</span> <span
  m=''1240230''>becomes</span> <span m=''1240460''>sharing</span> <span m=''1240775''>again.</span>
  </p><p><span m=''1243100''>OK.</span> <span m=''1243560''>Did</span> <span m=''1243770''>you</span>
  <span m=''1243910''>get</span> <span m=''1244100''>that?</span> <span m=''1244600''>What''s</span>
  <span m=''1244800''>going</span> <span m=''1245010''>on</span> <span m=''1245150''>in</span>
  <span m=''1245270''>here?</span> <span m=''1245770''>In</span> <span m=''1245880''>the</span>
  <span m=''1245970''>cache?</span> <span m=''1247520''>So</span> <span m=''1248640''>reads,</span>
  <span m=''1249090''>everybody</span> <span m=''1249470''>can</span> <span m=''1249650''>keep</span>
  <span m=''1250140''>a</span> <span m=''1250250''>copy if they</span> <span m=''1250370''>want.</span>
  <span m=''1251050''>Write--</span> <span m=''1251350''>only</span> <span m=''1251540''>one</span>
  <span m=''1251720''>guy</span> <span m=''1251920''>can keep</span> <span m=''1252050''>a
  copy.</span> </p><p><span m=''1253530''>So</span> <span m=''1253710''>what</span>
  <span m=''1253930''>happens</span> <span m=''1254360''>then</span> <span m=''1254660''>is</span>
  <span m=''1254930''>true</span> <span m=''1255170''>sharing.</span> <span m=''1255730''>So</span>
  <span m=''1255890''>you</span> <span m=''1256030''>have</span> <span m=''1256250''>these</span>
  <span m=''1256460''>two</span> <span m=''1256620''>different</span> <span m=''1256930''>cores.</span>
  <span m=''1258280''>So</span> <span m=''1258410''>I</span> <span m=''1258480''>want</span>
  <span m=''1258870''>to read</span> <span m=''1259360''>something.</span> <span m=''1259550''>So
  I</span> <span m=''1259630''>get</span> <span m=''1259880''>it</span> <span m=''1260420''>from</span>
  <span m=''1260620''>outside</span> <span m=''1261080''>probably</span> <span m=''1261560''>on</span>
  <span m=''1261710''>main</span> <span m=''1261910''>memory,</span> <span m=''1262270''>and</span>
  <span m=''1262440''>I</span> <span m=''1262500''>put</span> <span m=''1262730''>it
  in</span> <span m=''1262880''>my</span> <span m=''1263110''>cache</span> <span m=''1263465''>in
  here.</span> <span m=''1264820''>And</span> <span m=''1265080''>then,</span> <span
  m=''1266150''>the</span> <span m=''1266240''>next</span> <span m=''1266520''>guy</span>
  <span m=''1266750''>wants</span> <span m=''1267410''>to</span> <span m=''1269080''>write</span>
  <span m=''1269310''>the</span> <span m=''1269380''>same</span> <span m=''1269620''>thing.</span>
  <span m=''1269790''>Assume</span> <span m=''1269880''>I''m</span> <span m=''1269970''>writing</span>
  <span m=''1270200''>that.</span> <span m=''1271200''>And</span> <span m=''1271530''>once</span>
  <span m=''1271830''>I</span> <span m=''1271920''>want</span> <span m=''1272100''>to</span>
  <span m=''1272160''>write</span> <span m=''1272520''>that,</span> <span m=''1273130''>I</span>
  <span m=''1273260''>can</span> <span m=''1273580''>keep</span> <span m=''1273780''>this</span>
  <span m=''1273970''>copy</span> <span m=''1274280''>I</span> <span m=''1274400''>had</span>
  <span m=''1274520''>invalidated</span> <span m=''1275100''>from</span> <span m=''1275340''>here
  and</span> <span m=''1275750''>get</span> <span m=''1275870''>a</span> <span m=''1275930''>copy</span>
  <span m=''1276230''>here.</span> <span m=''1276920''>And</span> <span m=''1277320''>then,</span>
  <span m=''1277450''>if</span> <span m=''1277560''>this</span> <span m=''1277800''>way,</span>
  <span m=''1277890''>I want to</span> <span m=''1278080''>write</span> <span m=''1278400''>it</span>
  <span m=''1278540''>again,</span> <span m=''1278740''>I</span> <span m=''1278870''>have</span>
  <span m=''1279000''>to</span> <span m=''1279130''>basically</span> <span m=''1279730''>invalidate</span>
  <span m=''1280180''>it from</span> <span m=''1280420''>here</span> <span m=''1280500''>and</span>
  <span m=''1280620''>get</span> <span m=''1280750''>a</span> <span m=''1280810''>copy.</span>
  </p><p><span m=''1281140''>If I''m</span> <span m=''1281350''>reading,</span> <span
  m=''1281710''>both of us</span> <span m=''1282020''>can</span> <span m=''1282200''>keep</span>
  <span m=''1282590''>a copy</span> <span m=''1282990''>and</span> <span m=''1283150''>just
  kind</span> <span m=''1283320''>of</span> <span m=''1283400''>keep</span> <span
  m=''1283600''>bouncing</span> <span m=''1283960''>back</span> <span m=''1284170''>and</span>
  <span m=''1284300''>forth,</span> <span m=''1284530''>back</span> <span m=''1284750''>and</span>
  <span m=''1284890''>forth.</span> <span m=''1285570''>And</span> <span m=''1286310''>so</span>
  <span m=''1286400''>if</span> <span m=''1286550''>you</span> <span m=''1286670''>bounce</span>
  <span m=''1287010''>too</span> <span m=''1287120''>many</span> <span m=''1287320''>times,</span>
  <span m=''1287930''>you</span> <span m=''1288180''>get</span> <span m=''1289010''>all</span>
  <span m=''1289300''>of</span> <span m=''1289370''>these</span> <span m=''1290350''>invalidations.</span>
  <span m=''1291520''>So</span> <span m=''1292180''>the</span> <span m=''1292280''>fact</span>
  <span m=''1292670''>I</span> <span m=''1292770''>looked</span> <span m=''1292950''>at
  that</span> <span m=''1293330''>I</span> <span m=''1293450''>have</span> <span m=''1293570''>invalidations</span>
  <span m=''1294190''>basically</span> <span m=''1294770''>tells</span> <span m=''1295200''>me</span>
  <span m=''1295530''>something</span> <span m=''1295980''>like</span> <span m=''1296180''>this
  is</span> <span m=''1296310''>going</span> <span m=''1296530''>on.</span> </p><p><span
  m=''1297770''>So</span> <span m=''1297970''>what''s</span> <span m=''1298290''>happening</span>
  <span m=''1298800''>in</span> <span m=''1298990''>this</span> <span m=''1299210''>program?</span>
  <span m=''1302070''>When</span> <span m=''1302380''>I</span> <span m=''1302550''>parallelize</span>
  <span m=''1303270''>this</span> <span m=''1303530''>four</span> <span m=''1304150''>loop,</span>
  <span m=''1305220''>my</span> <span m=''1305410''>four</span> <span m=''1305730''>cores--</span>
  <span m=''1306420''>basically</span> <span m=''1306680''>since</span> <span m=''1307240''>I
  am</span> <span m=''1307430''>doing</span> <span m=''1307700''>here</span> <span
  m=''1308110''>[UNINTELLIGIBLE]--</span> <span m=''1309080''>are</span> <span m=''1309300''>going</span>
  <span m=''1309550''>to</span> <span m=''1309630''>get</span> <span m=''1310230''>this</span>
  <span m=''1310450''>nice</span> <span m=''1310890''>distribution</span> <span m=''1311560''>of</span>
  <span m=''1311710''>data</span> <span m=''1312410''>into</span> <span m=''1312660''>the</span>
  <span m=''1312770''>caches.</span> <span m=''1313690''>Assume</span> <span m=''1313990''>it</span>
  <span m=''1314090''>fits</span> <span m=''1314280''>in</span> <span m=''1314410''>cache.</span>
  <span m=''1315900''>OK.</span> <span m=''1316140''>So</span> <span m=''1316460''>all</span>
  <span m=''1316690''>this</span> <span m=''1316800''>data</span> <span m=''1316960''>nicely</span>
  <span m=''1317040''>fits</span> <span m=''1317120''>into</span> <span m=''1317520''>cache,</span>
  <span m=''1318280''>and</span> <span m=''1318570''>now I''m</span> <span m=''1318760''>pretty</span>
  <span m=''1319050''>happy</span> <span m=''1319490''>when</span> <span m=''1319590''>I</span>
  <span m=''1319710''>run this</span> <span m=''1319910''>one</span> <span m=''1320100''>because</span>
  <span m=''1320350''>I</span> <span m=''1320410''>got</span> <span m=''1320620''>this</span>
  <span m=''1320760''>data</span> <span m=''1320940''>into</span> <span m=''1321080''>the</span>
  <span m=''1321180''>cache.</span> <span m=''1321490''>And</span> <span m=''1321720''>I</span>
  <span m=''1321800''>write it.</span> </p><p><span m=''1322910''>But</span> <span
  m=''1323130''>the</span> <span m=''1323360''>minute I</span> <span m=''1323560''>go
  in</span> <span m=''1323940''>here,</span> <span m=''1325390''>basically</span>
  <span m=''1325790''>this</span> <span m=''1325900''>data</span> <span m=''1326140''>has</span>
  <span m=''1326520''>to</span> <span m=''1327860''>[UNINTELLIGIBLE].</span> <span
  m=''1330710''>OK,</span> <span m=''1330880''>because</span> <span m=''1331270''>I
  am</span> <span m=''1331530''>going</span> <span m=''1331860''>this</span> <span
  m=''1332050''>is</span> <span m=''1332230''>n</span> <span m=''1332300''>minus</span>
  <span m=''1332730''>i</span> <span m=''1333920''>in</span> <span m=''1333990''>here</span>
  <span m=''1334330''>so</span> <span m=''1334510''>this</span> <span m=''1334620''>data
  has a</span> <span m=''1334830''>flip route.</span> <span m=''1335520''>And</span>
  <span m=''1336170''>by</span> <span m=''1336360''>doing</span> <span m=''1336970''>this,</span>
  <span m=''1337340''>basically,</span> <span m=''1338140''>I incur</span> <span m=''1338660''>this</span>
  <span m=''1338820''>huge</span> <span m=''1339070''>amount</span> <span m=''1339290''>of</span>
  <span m=''1339380''>[UNINTELLIGIBLE],</span> <span m=''1340020''>and</span> <span
  m=''1340130''>it</span> <span m=''1340250''>slows down.</span> <span m=''1342090''>OK?</span>
  <span m=''1342670''>So</span> <span m=''1342790''>that''s</span> <span m=''1343150''>why</span>
  <span m=''1343240''>it</span> <span m=''1343410''>didn''t</span> <span m=''1343590''>work</span>
  <span m=''1343810''>well.</span> </p><p><span m=''1345250''>So</span> <span m=''1348020''>what</span>
  <span m=''1348460''>can</span> <span m=''1348650''>you</span> <span m=''1348690''>do?</span>
  <span m=''1353580''>When</span> <span m=''1353740''>you</span> <span m=''1353890''>have</span>
  <span m=''1354050''>these</span> <span m=''1356340''>read,</span> <span m=''1356510''>write</span>
  <span m=''1357290''>and</span> <span m=''1357420''>write,</span> <span m=''1357650''>write</span>
  <span m=''1358230''>conflicts</span> <span m=''1358650''>in here.</span> <span m=''1360050''>And</span>
  <span m=''1360560''>you</span> <span m=''1360670''>have</span> <span m=''1360980''>to
  actually</span> <span m=''1361150''>move</span> <span m=''1361310''>the</span> <span
  m=''1361410''>data</span> <span m=''1362210''>across</span> <span m=''1362510''>in</span>
  <span m=''1362850''>here.</span> <span m=''1364420''>And</span> <span m=''1364910''>what</span>
  <span m=''1365090''>you</span> <span m=''1365190''>can</span> <span m=''1365370''>do</span>
  <span m=''1365470''>is</span> <span m=''1365790''>look</span> <span m=''1366090''>for
  this</span> <span m=''1367790''>true</span> <span m=''1368160''>sharing.</span>
  <span m=''1368450''>You can</span> <span m=''1368600''>look</span> <span m=''1368730''>at</span>
  <span m=''1368870''>the</span> <span m=''1368960''>[UNINTELLIGIBLE]</span> <span
  m=''1369550''>and</span> <span m=''1369710''>see</span> <span m=''1370230''>if</span>
  <span m=''1370460''>we have</span> <span m=''1370690''>excessive</span> <span m=''1371030''>[UNINTELLIGIBLE],</span>
  <span m=''1371610''>we have a</span> <span m=''1371760''>problem.</span> </p><p><span
  m=''1372910''>And</span> <span m=''1373370''>how</span> <span m=''1373520''>do</span>
  <span m=''1373680''>we</span> <span m=''1373850''>eliminate</span> <span m=''1374080''>that?</span>
  <span m=''1374990''>You</span> <span m=''1375160''>want</span> <span m=''1375290''>to</span>
  <span m=''1375360''>make</span> <span m=''1375660''>the</span> <span m=''1375730''>sharing</span>
  <span m=''1376030''>minimal.</span> <span m=''1379580''>If</span> <span m=''1379740''>you</span>
  <span m=''1379860''>want</span> <span m=''1380280''>to</span> <span m=''1380390''>get</span>
  <span m=''1380580''>some</span> <span m=''1380750''>data</span> <span m=''1381300''>into</span>
  <span m=''1381530''>a</span> <span m=''1381760''>cache,</span> <span m=''1381880''>you
  want to try to</span> <span m=''1382010''>keep</span> <span m=''1382230''>it</span>
  <span m=''1382390''>there as</span> <span m=''1382580''>much</span> <span m=''1382770''>as</span>
  <span m=''1382900''>possible.</span> <span m=''1384320''>And if</span> <span m=''1384440''>you''re</span>
  <span m=''1384540''>using,</span> <span m=''1384960''>you''d</span> <span m=''1385110''>want</span>
  <span m=''1385330''>to</span> <span m=''1385370''>try</span> <span m=''1385550''>to</span>
  <span m=''1385680''>align</span> <span m=''1386050''>everything</span> <span m=''1386540''>across.</span>
  <span m=''1388080''>So</span> <span m=''1388430''>even</span> <span m=''1388900''>across</span>
  <span m=''1389190''>different</span> <span m=''1389490''>regions,</span> <span m=''1390590''>it''ll</span>
  <span m=''1390660''>use</span> <span m=''1390820''>the</span> <span m=''1390890''>same</span>
  <span m=''1391140''>kind</span> <span m=''1391370''>of</span> <span m=''1391460''>things.</span>
  <span m=''1392950''>And/or</span> <span m=''1393540''>enforce</span> <span m=''1393780''>some
  kind</span> <span m=''1394200''>of</span> <span m=''1394480''>[UNINTELLIGIBLE]</span>
  <span m=''1394640''>technique</span> <span m=''1395020''>to</span> <span m=''1395120''>keep</span>
  <span m=''1395320''>the</span> <span m=''1395400''>data</span> <span m=''1395600''>alive.</span>
  <span m=''1395900''>So</span> <span m=''1396000''>there are</span> <span m=''1396150''>a</span>
  <span m=''1396170''>lot</span> <span m=''1396360''>of</span> <span m=''1396450''>techniques</span>
  <span m=''1396830''>in</span> <span m=''1396960''>there,</span> <span m=''1397110''>but</span>
  <span m=''1397810''>true sharing</span> <span m=''1398280''>can</span> <span m=''1398420''>be
  an</span> <span m=''1398570''>interesting</span> <span m=''1398930''>problem.</span>
  </p><p><span m=''1399900''>So</span> <span m=''1400620''>in here,</span> <span m=''1401440''>simple</span>
  <span m=''1401900''>change,</span> <span m=''1402380''>yes.</span> <span m=''1403090''>You''re,</span>
  <span m=''1403250''>basically,</span> <span m=''1403840''>instead of</span> <span
  m=''1404080''>changing</span> <span m=''1405160''>A,</span> <span m=''1405810''>you</span>
  <span m=''1406040''>change</span> <span m=''1406270''>C.</span> <span m=''1408280''>So</span>
  <span m=''1408380''>you</span> <span m=''1408550''>write</span> <span m=''1408930''>A</span>
  <span m=''1409160''>the</span> <span m=''1409250''>same</span> <span m=''1409620''>way.</span>
  <span m=''1410130''>But</span> <span m=''1410440''>now</span> <span m=''1410650''>what</span>
  <span m=''1410820''>I</span> <span m=''1410960''>have</span> <span m=''1411100''>done</span>
  <span m=''1411330''>is</span> <span m=''1411690''>I</span> <span m=''1412620''>am</span>
  <span m=''1412760''>doing</span> <span m=''1413020''>the</span> <span m=''1413110''>mirror</span>
  <span m=''1413440''>by</span> <span m=''1413580''>changing</span> <span m=''1414060''>the</span>
  <span m=''1414130''>axis</span> <span m=''1414430''>to</span> <span m=''1414520''>C,</span>
  <span m=''1415380''>is</span> <span m=''1415480''>to</span> <span m=''1415690''>[UNINTELLIGIBLE]</span>
  <span m=''1415810''>is</span> <span m=''1416320''>the</span> <span m=''1416410''>same</span>
  <span m=''1416760''>as</span> <span m=''1417550''>this</span> <span m=''1417780''>axis.</span>
  <span m=''1418590''>So</span> <span m=''1418640''>these</span> <span m=''1418860''>two</span>
  <span m=''1419000''>are</span> <span m=''1419090''>the</span> <span m=''1419170''>same</span>
  <span m=''1419470''>thing.</span> </p><p><span m=''1420070''>And</span> <span m=''1420340''>the</span>
  <span m=''1420420''>minute</span> <span m=''1420580''>I</span> <span m=''1420720''>do</span>
  <span m=''1420920''>that,</span> <span m=''1421540''>voila!</span> <span m=''1422620''>I</span>
  <span m=''1422720''>get</span> <span m=''1422920''>good</span> <span m=''1423080''>speed</span>
  <span m=''1423300''>up.</span> <span m=''1424210''>Because</span> <span m=''1424850''>if</span>
  <span m=''1424930''>you</span> <span m=''1425020''>look</span> <span m=''1425170''>at</span>
  <span m=''1425320''>that,</span> <span m=''1425500''>my</span> <span m=''1425650''>inundations</span>
  <span m=''1426250''>has</span> <span m=''1426400''>gone</span> <span m=''1426670''>down.</span>
  <span m=''1427290''>My</span> <span m=''1427470''>L1</span> <span m=''1427860''>cache</span>
  <span m=''1428130''>[UNINTELLIGIBLE]</span> <span m=''1428520''>has now</span> <span
  m=''1428640''>really,</span> <span m=''1428990''>really</span> <span m=''1429230''>gone</span>
  <span m=''1429480''>down.</span> <span m=''1429610''>I''m not</span> <span m=''1429930''>doing</span>
  <span m=''1430210''>anything.</span> <span m=''1431030''>And</span> <span m=''1431370''>of</span>
  <span m=''1431550''>course,</span> <span m=''1431730''>I</span> <span m=''1431800''>am</span>
  <span m=''1431920''>doing</span> <span m=''1432100''>more</span> <span m=''1432260''>instructions</span>
  <span m=''1432930''>here</span> <span m=''1434060''>than</span> <span m=''1434590''>this</span>
  <span m=''1434820''>one</span> <span m=''1435070''>because--</span> <span m=''1437220''>I</span>
  <span m=''1437720''>think,</span> <span m=''1438310''>the</span> <span m=''1438430''>difference</span>
  <span m=''1438850''>between</span> <span m=''1438940''>instruction</span> <span
  m=''1439650''>here</span> <span m=''1439970''>and</span> <span m=''1440070''>here</span>
  <span m=''1440300''>is</span> <span m=''1440550''>because</span> <span m=''1440990''>a
  lot of times</span> <span m=''1441460''>synchronization</span> <span m=''1443050''>operations
  are</span> <span m=''1443220''>dynamic</span> <span m=''1444130''>because</span>
  <span m=''1444600''>in</span> <span m=''1444790''>the</span> <span m=''1444860''>[UNINTELLIGIBLE]</span>
  <span m=''1445530''>miscounted</span> <span m=''1445780''>as</span> <span m=''1446050''>the</span>
  <span m=''1446330''>instructions,</span> <span m=''1446540''>you</span> <span m=''1446940''>are</span>
  <span m=''1447260''>busy</span> <span m=''1447760''>waiting</span> <span m=''1448570''>in</span>
  <span m=''1448720''>there.</span> <span m=''1449770''>So</span> <span m=''1450510''>this</span>
  <span m=''1450700''>number</span> <span m=''1450920''>is</span> <span m=''1451040''>not</span>
  <span m=''1451230''>really a</span> <span m=''1451480''>constant</span> <span m=''1451850''>number.</span>
  <span m=''1453350''>OK,</span> <span m=''1453590''>question.</span> </p><p><span
  m=''1454850''>AUDIENCE: Not a</span> <span m=''1455010''>question.</span> <span
  m=''1455440''>So</span> <span m=''1455640''>another</span> <span m=''1456550''>thing</span>
  <span m=''1456860''>one</span> <span m=''1457060''>could</span> <span m=''1457220''>do</span>
  <span m=''1457360''>here</span> <span m=''1457590''>is</span> <span m=''1457680''>do</span>
  <span m=''1457810''>loop</span> <span m=''1458000''>fusion.</span> </p><p><span
  m=''1459020''>PROFESSOR: Yes.</span> <span m=''1459530''>Yes.</span> <span m=''1460410''>Here</span>
  <span m=''1460630''>is</span> <span m=''1460710''>a</span> <span m=''1460760''>nice</span>
  <span m=''1461050''>way</span> <span m=''1461190''>of</span> <span m=''1461320''>putting</span>
  <span m=''1462210''>both</span> <span m=''1462530''>of</span> <span m=''1462630''>the</span>
  <span m=''1462710''>loops</span> <span m=''1462960''>into</span> <span m=''1463140''>one</span>
  <span m=''1463770''>and</span> <span m=''1464100''>do loop fusion.</span> <span
  m=''1464990''>And</span> <span m=''1465520''>that</span> <span m=''1465650''>works.</span>
  <span m=''1466300''>In</span> <span m=''1466740''>this</span> <span m=''1466940''>case,</span>
  <span m=''1467130''>you</span> <span m=''1467200''>can</span> <span m=''1467360''>do</span>
  <span m=''1467460''>that.</span> </p><p><span m=''1468230''>AUDIENCE: So</span>
  <span m=''1468450''>loop</span> <span m=''1468680''>fusion</span> <span m=''1469100''>is</span>
  <span m=''1469200''>where</span> <span m=''1469360''>you</span> <span m=''1469440''>take</span>
  <span m=''1470220''>two</span> <span m=''1470440''>loops,</span> <span m=''1471070''>and</span>
  <span m=''1471360''>you</span> <span m=''1471690''>convert</span> <span m=''1472090''>it</span>
  <span m=''1472160''>into</span> <span m=''1472450''>one</span> <span m=''1472710''>loop.</span>
  <span m=''1473620''>So</span> <span m=''1473760''>in</span> <span m=''1473820''>this</span>
  <span m=''1473990''>case,</span> <span m=''1474250''>you</span> <span m=''1474340''>could</span>
  <span m=''1474460''>have</span> <span m=''1474590''>just</span> <span m=''1474820''>written</span>
  <span m=''1475830''>one</span> <span m=''1476110''>nest,</span> <span m=''1477050''>which</span>
  <span m=''1477240''>has</span> <span m=''1477460''>two</span> <span m=''1477750''>things</span>
  <span m=''1478090''>going</span> <span m=''1478360''>on</span> <span m=''1478560''>inside.</span>
  <span m=''1481490''>And</span> <span m=''1482310''>then</span> <span m=''1482580''>you</span>
  <span m=''1482690''>would</span> <span m=''1482810''>save</span> <span m=''1483140''>all</span>
  <span m=''1483380''>the</span> <span m=''1483460''>loop</span> <span m=''1483740''>overhead</span>
  <span m=''1484320''>and</span> <span m=''1484520''>the</span> <span m=''1484580''>scheduling</span>
  <span m=''1485050''>overhead.</span> <span m=''1486090''>So</span> <span m=''1486290''>rather</span>
  <span m=''1486530''>than</span> <span m=''1486650''>doing</span> <span m=''1486880''>it</span>
  <span m=''1487000''>twice,</span> <span m=''1487480''>you</span> <span m=''1487760''>actually</span>
  <span m=''1488440''>have</span> <span m=''1488620''>reduced</span> <span m=''1488970''>the</span>
  <span m=''1489090''>overhead</span> <span m=''1489590''>to</span> <span m=''1489670''>just</span>
  <span m=''1490020''>the</span> <span m=''1490640''>parallelism</span> <span m=''1491190''>of</span>
  <span m=''1491300''>the</span> <span m=''1491400''>one</span> <span m=''1491610''>loop.</span>
  <span m=''1492890''>So</span> <span m=''1493040''>if</span> <span m=''1493120''>you</span>
  <span m=''1493200''>look</span> <span m=''1493380''>at</span> <span m=''1493480''>that,</span>
  <span m=''1493700''>you''ll</span> <span m=''1493910''>realize</span> <span m=''1494360''>that</span>
  <span m=''1494470''>you</span> <span m=''1494590''>could</span> <span m=''1495320''>somehow</span>
  <span m=''1495790''>make</span> <span m=''1496310''>it</span> <span m=''1496500''>just</span>
  <span m=''1496740''>be</span> <span m=''1496930''>a</span> <span m=''1497140''>single</span>
  <span m=''1497550''>nest</span> <span m=''1498450''>with</span> <span m=''1498660''>two</span>
  <span m=''1498860''>statements</span> <span m=''1499360''>in</span> <span m=''1499460''>there,</span>
  <span m=''1499670''>rather</span> <span m=''1500000''>than</span> <span m=''1500170''>one.</span>
  </p><p><span m=''1501130''>PROFESSOR: So</span> <span m=''1501830''>basically,</span>
  <span m=''1502790''>instead</span> <span m=''1503210''>of</span> <span m=''1503400''>[UNINTELLIGIBLE]</span>
  <span m=''1504100''>entire</span> <span m=''1504340''>thing</span> <span m=''1504700''>and</span>
  <span m=''1504920''>move</span> <span m=''1505370''>plus</span> <span m=''1505725''>C</span>
  <span m=''1506080''>into</span> <span m=''1506310''>here,</span> <span m=''1506600''>basically.</span>
  <span m=''1508190''>And</span> <span m=''1508340''>I could</span> <span m=''1508430''>have</span>
  <span m=''1508720''>just</span> <span m=''1508940''>done</span> <span m=''1509110''>it</span>
  <span m=''1509230''>in</span> <span m=''1509360''>one</span> <span m=''1509540''>loop</span>
  <span m=''1509770''>nest.</span> <span m=''1510040''>That''s</span> <span m=''1510120''>what</span>
  <span m=''1510500''>loop</span> <span m=''1510570''>fusion</span> <span m=''1511020''>would</span>
  <span m=''1511130''>do</span> <span m=''1511300''>here.</span> <span m=''1511950''>So</span>
  <span m=''1512060''>we can</span> <span m=''1512210''>actually</span> <span m=''1512590''>[UNINTELLIGIBLE]</span>
  <span m=''1513750''>much</span> <span m=''1514060''>nicer</span> <span m=''1514350''>in
  here.</span> </p><p><span m=''1515280''>But</span> <span m=''1515960''>just</span>
  <span m=''1516180''>for</span> <span m=''1516400''>example</span> <span m=''1517060''>purposes,</span>
  <span m=''1517690''>so</span> <span m=''1518020''>now</span> <span m=''1518230''>I</span>
  <span m=''1518330''>really</span> <span m=''1518720''>reduced</span> <span m=''1518990''>this</span>
  <span m=''1519190''>one</span> <span m=''1519680''>and</span> <span m=''1519850''>got</span>
  <span m=''1520050''>that.</span> <span m=''1520540''>So</span> <span m=''1520700''>this</span>
  <span m=''1520890''>is</span> <span m=''1521130''>great.</span> <span m=''1521740''>Cagnodes</span>
  <span m=''1521860''>really</span> <span m=''1522650''>showed</span> <span m=''1523170''>this</span>
  <span m=''1523360''>classic</span> <span m=''1523830''>problem</span> <span m=''1524590''>in</span>
  <span m=''1525010''>the computer.</span> <span m=''1525820''>And so</span> <span
  m=''1525980''>I''m</span> <span m=''1526140''>like,</span> <span m=''1526290''>OK.</span>
  <span m=''1527070''>Now</span> <span m=''1527170''>we</span> <span m=''1527250''>have</span>
  <span m=''1527410''>new</span> <span m=''1527520''>machines.</span> <span m=''1528720''>Let''s</span>
  <span m=''1528990''>try</span> <span m=''1529320''>it and</span> <span m=''1529480''>see</span>
  <span m=''1529620''>what</span> <span m=''1529770''>happens.</span> </p><p><span
  m=''1534090''>What</span> <span m=''1534280''>does</span> <span m=''1534390''>this</span>
  <span m=''1534590''>show?</span> <span m=''1535670''>This</span> <span m=''1535870''>is</span>
  <span m=''1536570''>your</span> <span m=''1537370''>nice</span> <span m=''1538040''>cloud</span>
  <span m=''1538350''>machines</span> <span m=''1538750''>we''ve</span> <span m=''1539248''>got
  now.</span> <span m=''1541240''>I</span> <span m=''1541310''>have</span> <span m=''1541500''>no</span>
  <span m=''1541820''>slow down.</span> <span m=''1542480''>I</span> <span m=''1542600''>was</span>
  <span m=''1542770''>really</span> <span m=''1543030''>disappointed</span> <span
  m=''1544840''>because</span> <span m=''1546270''>beforehand,</span> <span m=''1546850''>I</span>
  <span m=''1547090''>had</span> <span m=''1547340''>this</span> <span m=''1547570''>for</span>
  <span m=''1547830''>sharing</span> <span m=''1548190''>going</span> <span m=''1548470''>on</span>
  <span m=''1548650''>in</span> <span m=''1548800''>here</span> <span m=''1549380''>and</span>
  <span m=''1549840''>had</span> <span m=''1550030''>a</span> <span m=''1550070''>really</span>
  <span m=''1550410''>big</span> <span m=''1550610''>slow</span> <span m=''1550830''>down.</span>
  <span m=''1551100''>But</span> <span m=''1551280''>this</span> <span m=''1551500''>one,</span>
  <span m=''1552080''>in fact,</span> <span m=''1552610''>the</span> <span m=''1552890''>difference</span>
  <span m=''1553640''>is very small.</span> <span m=''1554070''>And</span> <span m=''1554390''>when
  you</span> <span m=''1554620''>look</span> <span m=''1554790''>at</span> <span m=''1554970''>any</span>
  <span m=''1555160''>kind</span> <span m=''1555460''>of</span> <span m=''1555560''>performance</span>
  <span m=''1556020''>counters,</span> <span m=''1556290''>they</span> <span m=''1556540''>are</span>
  <span m=''1556935''>pretty</span> <span m=''1558070''>comparable.</span> <span m=''1558580''>There''s</span>
  <span m=''1558750''>nothing</span> <span m=''1559030''>much</span> <span m=''1559250''>going</span>
  <span m=''1559510''>on</span> <span m=''1559670''>here.</span> </p><p><span m=''1560220''>So</span>
  <span m=''1560820''>what</span> <span m=''1561080''>do</span> <span m=''1561230''>you
  think</span> <span m=''1561380''>is</span> <span m=''1561660''>going</span> <span
  m=''1561970''>on</span> <span m=''1562230''>in</span> <span m=''1562350''>this</span>
  <span m=''1563390''>new</span> <span m=''1563580''>architecture</span> <span m=''1564080''>now?</span>
  <span m=''1566130''>Why</span> <span m=''1566410''>this</span> <span m=''1566760''>might</span>
  <span m=''1567100''>be?</span> </p><p><span m=''1575730''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''1586030''>PROFESSOR: That''s</span> <span m=''1586295''>an</span>
  <span m=''1586560''>interesting</span> <span m=''1586970''>observation,</span> <span
  m=''1587490''>but</span> <span m=''1588800''>also</span> <span m=''1589960''>we</span>
  <span m=''1590200''>have--</span> <span m=''1592050''>yes,</span> <span m=''1592270''>core
  seven</span> <span m=''1593060''>basically</span> <span m=''1593940''>is</span>
  <span m=''1594270''>two</span> <span m=''1594460''>by</span> <span m=''1594650''>two</span>
  <span m=''1594800''>in</span> <span m=''1594910''>the</span> <span m=''1595020''>die.</span>
  <span m=''1596250''>But</span> <span m=''1596550''>we</span> <span m=''1596680''>also</span>
  <span m=''1597010''>have</span> <span m=''1597240''>two</span> <span m=''1597440''>different</span>
  <span m=''1597770''>processors.</span> <span m=''1598650''>So</span> <span m=''1598860''>that''s</span>
  <span m=''1599140''>there,</span> <span m=''1599890''>too.</span> <span m=''1600110''>So</span>
  <span m=''1600240''>in</span> <span m=''1600540''>some</span> <span m=''1600730''>sense,</span>
  <span m=''1601810''>when</span> <span m=''1602040''>you</span> <span m=''1602190''>get</span>
  <span m=''1602700''>our</span> <span m=''1602930''>two-way</span> <span m=''1603020''>process</span>
  <span m=''1603640''>[UNINTELLIGIBLE]</span> <span m=''1604670''>So</span> <span
  m=''1604840''>that''s</span> <span m=''1605140''>there.</span> <span m=''1605620''>That</span>
  <span m=''1605910''>might</span> <span m=''1606130''>help.</span> <span m=''1606370''>That''s
  an</span> <span m=''1606790''>interesting</span> <span m=''1607210''>observation.</span>
  </p><p><span m=''1608650''>What</span> <span m=''1608800''>else</span> <span m=''1609110''>might</span>
  <span m=''1609340''>be</span> <span m=''1609440''>going</span> <span m=''1609730''>on</span>
  <span m=''1609880''>here?</span> <span m=''1610340''>Why</span> <span m=''1610450''>do
  you</span> <span m=''1610620''>think</span> <span m=''1611960''>they</span> <span
  m=''1612040''>manage</span> <span m=''1612310''>to</span> <span m=''1612390''>get</span>
  <span m=''1612570''>this</span> <span m=''1612760''>one?</span> <span m=''1612880''>What</span>
  <span m=''1613080''>might</span> <span m=''1613280''>be</span> <span m=''1613430''>another</span>
  <span m=''1614100''>answer?</span> <span m=''1618790''>What</span> <span m=''1619420''>can</span>
  <span m=''1619715''>hide</span> <span m=''1620010''>these</span> <span m=''1620300''>kind
  of</span> <span m=''1620400''>delays</span> <span m=''1622750''>that</span> <span
  m=''1622920''>can</span> <span m=''1623110''>happen?</span> <span m=''1623350''>Load</span>
  <span m=''1623770''>delays,</span> <span m=''1624130''>and</span> <span m=''1625430''>cache</span>
  <span m=''1625780''>misses,</span> <span m=''1626050''>and</span> <span m=''1626200''>stuff</span>
  <span m=''1626480''>like</span> <span m=''1626670''>that.</span> <span m=''1626990''>What</span>
  <span m=''1627350''>techniques</span> <span m=''1627810''>and</span> <span m=''1627900''>hardware</span>
  <span m=''1628320''>can</span> <span m=''1628470''>hide</span> <span m=''1628750''>those?</span>
  <span m=''1635300''>Just</span> <span m=''1635390''>[UNINTELLIGIBLE]</span> <span
  m=''1635675''>a speculation.</span> </p><p><span m=''1637050''>Prefetching.</span>
  <span m=''1638610''>So</span> <span m=''1638990''>most</span> <span m=''1639500''>hardware</span>
  <span m=''1640500''>has</span> <span m=''1640870''>an</span> <span m=''1641150''>internal</span>
  <span m=''1641290''>mechanism.</span> <span m=''1642290''>When</span> <span m=''1642430''>you</span>
  <span m=''1642590''>start</span> <span m=''1642930''>fetching</span> <span m=''1643310''>data,</span>
  <span m=''1644110''>you</span> <span m=''1644310''>say,</span> <span m=''1644600''>aha!</span>
  <span m=''1644890''>I</span> <span m=''1645020''>see</span> <span m=''1645190''>a</span>
  <span m=''1645290''>pattern.</span> <span m=''1646420''>I</span> <span m=''1646670''>know</span>
  <span m=''1646810''>you</span> <span m=''1646960''>want</span> <span m=''1647130''>to</span>
  <span m=''1647170''>get</span> <span m=''1647380''>this</span> <span m=''1647520''>thing.</span>
  <span m=''1647650''>Let</span> <span m=''1647850''>me</span> <span m=''1648050''>go</span>
  <span m=''1648260''>forward</span> <span m=''1648820''>and</span> <span m=''1650380''>bring</span>
  <span m=''1650640''>more</span> <span m=''1650820''>data,</span> <span m=''1651410''>thinking</span>
  <span m=''1651690''>you</span> <span m=''1651810''>are</span> <span m=''1651960''>going</span>
  <span m=''1652100''>to</span> <span m=''1652630''>follow</span> <span m=''1652780''>that</span>
  <span m=''1652980''>pattern.</span> <span m=''1654240''>OK.</span> <span m=''1654590''>All
  or</span> <span m=''1655010''>most</span> <span m=''1655440''>of</span> <span m=''1655510''>the</span>
  <span m=''1655590''>[UNINTELLIGIBLE]</span> <span m=''1656240''>for,</span> <span
  m=''1656680''>I</span> <span m=''1656920''>think,</span> <span m=''1657270''>have</span>
  <span m=''1658350''>[UNINTELLIGIBLE]</span> <span m=''1658750''>even</span> <span
  m=''1658960''>a</span> <span m=''1659010''>Pentium</span> <span m=''1660090''>had</span>
  <span m=''1660420''>something</span> <span m=''1660740''>for</span> <span m=''1661100''>prefetching</span>
  <span m=''1661280''>going</span> <span m=''1661550''>on.</span> </p><p><span m=''1662280''>But</span>
  <span m=''1662620''>most</span> <span m=''1662890''>of</span> <span m=''1662960''>the</span>
  <span m=''1663030''>time,</span> <span m=''1663240''>what</span> <span m=''1663370''>happens</span>
  <span m=''1663760''>is</span> <span m=''1663930''>the</span> <span m=''1664020''>prefetching</span>
  <span m=''1664470''>engine</span> <span m=''1664830''>can''t</span> <span m=''1665130''>keep</span>
  <span m=''1665330''>up.</span> <span m=''1665970''>If</span> <span m=''1666090''>you
  are</span> <span m=''1666300''>getting</span> <span m=''1666620''>there,</span>
  <span m=''1667340''>it''s</span> <span m=''1667570''>[UNINTELLIGIBLE]</span> <span
  m=''1667930''>a</span> <span m=''1667960''>little</span> <span m=''1668190''>bit</span>
  <span m=''1668370''>further.</span> <span m=''1668880''>You are</span> <span m=''1669020''>going</span>
  <span m=''1669160''>to</span> <span m=''1669220''>catch</span> <span m=''1669480''>up,</span>
  <span m=''1669640''>and</span> <span m=''1669770''>you''re</span> <span m=''1669900''>going</span>
  <span m=''1670040''>to</span> <span m=''1670100''>start</span> <span m=''1670400''>because</span>
  <span m=''1670650''>you</span> <span m=''1670740''>have</span> <span m=''1670910''>more</span>
  <span m=''1671080''>[UNINTELLIGIBLE]</span> <span m=''1671420''>here.</span> <span
  m=''1673026''>I</span> <span m=''1673500''>think</span> <span m=''1673900''>[UNINTELLIGIBLE]</span>
  <span m=''1674980''>has</span> <span m=''1675120''>a</span> <span m=''1675560''>really,</span>
  <span m=''1675900''>really</span> <span m=''1676160''>good</span> <span m=''1676690''>prefetcher.</span>
  <span m=''1676880''>And</span> <span m=''1677030''>then,</span> <span m=''1677210''>we</span>
  <span m=''1677760''>saw</span> <span m=''1677960''>it</span> <span m=''1678150''>in</span>
  <span m=''1678650''>our</span> <span m=''1679005''>architecture</span> <span m=''1681280''>slides,</span>
  <span m=''1681640''>too.</span> <span m=''1682170''>That</span> <span m=''1682440''>a</span>
  <span m=''1682460''>lot</span> <span m=''1682670''>of</span> <span m=''1682740''>things</span>
  <span m=''1682930''>that</span> <span m=''1683100''>used</span> <span m=''1683300''>to</span>
  <span m=''1683360''>happen</span> <span m=''1683630''>before</span> <span m=''1684020''>is</span>
  <span m=''1684210''>gone.</span> <span m=''1684940''>So</span> <span m=''1685070''>this</span>
  <span m=''1685260''>is really</span> <span m=''1685560''>good.</span> <span m=''1685990''>What</span>
  <span m=''1686160''>that</span> <span m=''1686340''>means</span> <span m=''1687090''>is</span>
  <span m=''1687990''>a lot</span> <span m=''1688460''>of</span> <span m=''1688920''>weird</span>
  <span m=''1689810''>stuff</span> <span m=''1690130''>that''s</span> <span m=''1690380''>going</span>
  <span m=''1690740''>on</span> <span m=''1691330''>[UNINTELLIGIBLE]</span> <span
  m=''1692360''>making</span> <span m=''1693120''>them</span> <span m=''1693260''>disappear.</span>
  <span m=''1694010''>So</span> <span m=''1694210''>these</span> <span m=''1694440''>kind</span>
  <span m=''1694610''>of</span> <span m=''1694680''>problems</span> <span m=''1695060''>don''t</span>
  <span m=''1695300''>show</span> <span m=''1695500''>up.</span> <span m=''1695990''>So</span>
  <span m=''1696140''>that''s</span> <span m=''1696380''>the nice</span> <span m=''1696630''>story.</span>
  </p><p><span m=''1697260''>The</span> <span m=''1697390''>other</span> <span m=''1697590''>part</span>
  <span m=''1697890''>is,</span> <span m=''1698350''>OK.</span> <span m=''1698920''>Now</span>
  <span m=''1699380''>if</span> <span m=''1699590''>you</span> <span m=''1699810''>start</span>
  <span m=''1700430''>really</span> <span m=''1700910''>tweaking</span> <span m=''1701360''>your</span>
  <span m=''1701510''>programs</span> <span m=''1702130''>to</span> <span m=''1702280''>one</span>
  <span m=''1702630''>architecture,</span> <span m=''1704050''>you</span> <span m=''1704200''>wait</span>
  <span m=''1704380''>a</span> <span m=''1704440''>generation.</span> <span m=''1705120''>And</span>
  <span m=''1705410''>then</span> <span m=''1705550''>now,</span> <span m=''1705680''>we</span>
  <span m=''1705780''>have</span> <span m=''1705990''>done</span> <span m=''1706670''>either</span>
  <span m=''1707030''>the</span> <span m=''1707190''>tweaking--</span> <span m=''1708300''>the</span>
  <span m=''1708480''>best</span> <span m=''1708760''>case,</span> <span m=''1709080''>tweaking</span>
  <span m=''1710380''>has</span> <span m=''1710630''>no impact,</span> <span m=''1711750''>and</span>
  <span m=''1713370''>it''s</span> <span m=''1713910''>not</span> <span m=''1714060''>affecting</span>
  <span m=''1714640''>anything.</span> <span m=''1715170''>In</span> <span m=''1715320''>most</span>
  <span m=''1715610''>of</span> <span m=''1715670''>the</span> <span m=''1715730''>time,</span>
  <span m=''1715930''>worst</span> <span m=''1716160''>case,</span> <span m=''1716440''>tweaking</span>
  <span m=''1716740''>actually</span> <span m=''1717090''>slows down</span> <span
  m=''1717380''>the</span> <span m=''1717490''>program</span> <span m=''1717820''>because</span>
  <span m=''1718200''>you</span> <span m=''1718370''>are</span> <span m=''1718500''>trying</span>
  <span m=''1718670''>to</span> <span m=''1718720''>do</span> <span m=''1718840''>something</span>
  <span m=''1719160''>complicated.</span> <span m=''1720030''>That''s</span> <span
  m=''1720400''>just</span> <span m=''1720580''>not</span> <span m=''1720750''>needed</span>
  <span m=''1721040''>anymore.</span> </p><p><span m=''1722790''>So</span> <span m=''1724430''>even</span>
  <span m=''1724770''>though</span> <span m=''1725400''>these</span> <span m=''1725800''>kind</span>
  <span m=''1725990''>of</span> <span m=''1726060''>things</span> <span m=''1726240''>showed</span>
  <span m=''1726550''>up</span> <span m=''1726970''>in</span> <span m=''1726990''>[UNINTELLIGIBLE]</span>
  <span m=''1727500''>architecture,</span> <span m=''1727930''>it''s not an</span>
  <span m=''1728190''>issue.</span> <span m=''1728750''>But</span> <span m=''1729250''>if</span>
  <span m=''1729390''>you</span> <span m=''1729540''>go</span> <span m=''1729790''>to</span>
  <span m=''1729910''>many</span> <span m=''1730270''>of</span> <span m=''1730390''>the</span>
  <span m=''1730920''>smaller</span> <span m=''1731350''>architectures</span> <span
  m=''1732080''>that</span> <span m=''1732250''>have</span> <span m=''1733552''>that</span>
  <span m=''1734040''>don''t</span> <span m=''1734420''>have</span> <span m=''1734500''>that</span>
  <span m=''1734710''>much</span> <span m=''1734940''>of the</span> <span m=''1735230''>very</span>
  <span m=''1735460''>popular</span> <span m=''1735830''>prefetchers,</span> <span
  m=''1736570''>this</span> <span m=''1736790''>kind</span> <span m=''1736970''>of</span>
  <span m=''1737040''>issue</span> <span m=''1737260''>you would see.</span> <span
  m=''1737620''>So</span> <span m=''1737780''>for</span> <span m=''1737880''>example,</span>
  <span m=''1738200''>if</span> <span m=''1738290''>you</span> <span m=''1738380''>go
  to</span> <span m=''1738520''>a cell phone</span> <span m=''1738900''>[UNINTELLIGIBLE],</span>
  <span m=''1740610''>you would</span> <span m=''1740870''>probably</span> <span m=''1741140''>see</span>
  <span m=''1741280''>these</span> <span m=''1741470''>kind</span> <span m=''1741630''>of</span>
  <span m=''1741730''>issues</span> <span m=''1742020''>happening.</span> </p><p><span
  m=''1743770''>Any</span> <span m=''1743930''>questions</span> <span m=''1744440''>here
  so</span> <span m=''1744660''>far?</span> <span m=''1745560''>So that''s the</span>
  <span m=''1745820''>good</span> <span m=''1745970''>news.</span> <span m=''1746300''>You</span>
  <span m=''1746410''>guys</span> <span m=''1746640''>don''t have</span> <span m=''1746780''>to</span>
  <span m=''1746910''>worry</span> <span m=''1747110''>about</span> <span m=''1747320''>it</span>
  <span m=''1747460''>too</span> <span m=''1747580''>much.</span> <span m=''1748280''>But</span>
  <span m=''1749100''>at least</span> <span m=''1749410''>it''s</span> <span m=''1749570''>good</span>
  <span m=''1749720''>to</span> <span m=''1749800''>know</span> <span m=''1749940''>the</span>
  <span m=''1750050''>technique</span> <span m=''1750410''>because</span> <span m=''1751250''>you''ll</span>
  <span m=''1751440''>see</span> <span m=''1751830''>it in other</span> <span m=''1751970''>architectures.</span>
  </p><p><span m=''1753820''>So</span> <span m=''1753990''>now,</span> <span m=''1754840''>I</span>
  <span m=''1754980''>want</span> <span m=''1755160''>to</span> <span m=''1755220''>switch</span>
  <span m=''1755540''>a</span> <span m=''1755590''>little</span> <span m=''1755990''>bit</span>
  <span m=''1756240''>into</span> <span m=''1757270''>looking</span> <span m=''1757650''>at</span>
  <span m=''1758110''>programs</span> <span m=''1758760''>that</span> <span m=''1759760''>don''t</span>
  <span m=''1760090''>have</span> <span m=''1760250''>what</span> <span m=''1760460''>we
  call</span> <span m=''1760800''>data</span> <span m=''1761070''>parallelism.</span>
  <span m=''1761630''>That</span> <span m=''1762040''>means</span> <span m=''1762320''>you</span>
  <span m=''1762450''>can</span> <span m=''1762580''>start</span> <span m=''1762920''>and</span>
  <span m=''1763080''>say,</span> <span m=''1763790''>[UNINTELLIGIBLE]</span> <span
  m=''1764320''>parallels.</span> <span m=''1764740''>Everybody</span> <span m=''1765220''>get</span>
  <span m=''1765380''>the</span> <span m=''1765440''>different</span> <span m=''1765560''>chunk</span>
  <span m=''1765940''>and</span> <span m=''1766190''>run.</span> <span m=''1766840''>And</span>
  <span m=''1767480''>we</span> <span m=''1767560''>are going</span> <span m=''1767690''>a</span>
  <span m=''1767930''>little</span> <span m=''1768140''>bit</span> <span m=''1768300''>more</span>
  <span m=''1768520''>deeply</span> <span m=''1769000''>into</span> <span m=''1769700''>looking</span>
  <span m=''1769990''>at</span> <span m=''1770110''>programs</span> <span m=''1770490''>that</span>
  <span m=''1770630''>are</span> <span m=''1770770''>a little</span> <span m=''1770990''>bit</span>
  <span m=''1771060''>different.</span> </p><p><span m=''1772230''>So</span> <span
  m=''1774390''>I</span> <span m=''1774520''>wanted</span> <span m=''1774680''>to</span>
  <span m=''1774720''>come</span> <span m=''1774850''>up</span> <span m=''1774970''>with</span>
  <span m=''1775120''>this little</span> <span m=''1775590''>representation</span>
  <span m=''1776230''>to</span> <span m=''1776540''>represent</span> <span m=''1776650''>the</span>
  <span m=''1776730''>program.</span> <span m=''1777580''>And</span> <span m=''1778420''>so</span>
  <span m=''1778520''>if</span> <span m=''1778640''>you</span> <span m=''1778770''>think</span>
  <span m=''1779050''>about</span> <span m=''1779860''>iteration</span> <span m=''1780430''>space--</span>
  <span m=''1782090''>actually</span> <span m=''1782380''>before</span> <span m=''1782680''>you,</span>
  <span m=''1782850''>I''ll</span> <span m=''1782990''>go</span> <span m=''1783300''>down</span>
  <span m=''1783570''>to</span> <span m=''1783660''>dependence.</span> <span m=''1784090''>I''ll</span>
  <span m=''1784830''>also</span> <span m=''1785170''>do a little bit</span> <span
  m=''1785310''>of load</span> <span m=''1785580''>balance.</span> <span m=''1786200''>So</span>
  <span m=''1786360''>here''s</span> <span m=''1786780''>a</span> <span m=''1786900''>loop</span>
  <span m=''1788170''>that</span> <span m=''1788430''>in</span> <span m=''1788570''>my</span>
  <span m=''1788700''>iterations--</span> <span m=''1789890''>the</span> <span m=''1789980''>first</span>
  <span m=''1790270''>one</span> <span m=''1790500''>I</span> <span m=''1790840''>transformed</span>
  <span m=''1791090''>zero</span> <span m=''1792013''>to</span> <span m=''1792980''>eight.</span>
  <span m=''1793690''>But</span> <span m=''1793830''>J</span> <span m=''1794120''>only</span>
  <span m=''1794420''>runs</span> <span m=''1794630''>from</span> <span m=''1794900''>one</span>
  <span m=''1795130''>to</span> <span m=''1795280''>eight.</span> <span m=''1795670''>So</span>
  <span m=''1795950''>each</span> <span m=''1796370''>I,</span> <span m=''1796760''>I</span>
  <span m=''1796950''>have</span> <span m=''1797150''>less</span> <span m=''1797410''>and</span>
  <span m=''1797570''>less</span> <span m=''1798000''>amount</span> <span m=''1798460''>of</span>
  <span m=''1798630''>J</span> <span m=''1799610''>iterations,</span> <span m=''1799920''>basically.</span>
  <span m=''1802160''>OK?</span> <span m=''1802600''>It''s</span> <span m=''1802750''>a
  triangular</span> <span m=''1803080''>loop.</span> <span m=''1805100''>OK?</span>
  </p><p><span m=''1810050''>OK.</span> <span m=''1810250''>So</span> <span m=''1810350''>this</span>
  <span m=''1810530''>is</span> <span m=''1810670''>the way</span> <span m=''1810880''>to</span>
  <span m=''1810920''>represent</span> <span m=''1811285''>iteration</span> <span
  m=''1811650''>space,</span> <span m=''1812280''>so</span> <span m=''1812420''>I</span>
  <span m=''1812500''>will</span> <span m=''1812680''>represent</span> <span m=''1813110''>data</span>
  <span m=''1813780''>and</span> <span m=''1814220''>get</span> <span m=''1814420''>back</span>
  <span m=''1814600''>to</span> <span m=''1814670''>this</span> <span m=''1814840''>again.</span>
  <span m=''1815600''>So</span> <span m=''1815730''>if</span> <span m=''1815860''>you</span>
  <span m=''1816050''>look</span> <span m=''1816170''>at a</span> <span m=''1816300''>data</span>
  <span m=''1816650''>space,</span> <span m=''1817460''>you</span> <span m=''1817630''>can</span>
  <span m=''1817860''>assume</span> <span m=''1818550''>data</span> <span m=''1818830''>iteration</span>
  <span m=''1819130''>space</span> <span m=''1819670''>could</span> <span m=''1819800''>be</span>
  <span m=''1819940''>this</span> <span m=''1820160''>funky,</span> <span m=''1820560''>triangular,</span>
  <span m=''1822810''>hyperplane</span> <span m=''1823740''>type</span> <span m=''1824000''>of</span>
  <span m=''1824160''>thing.</span> <span m=''1824760''>Whereas</span> <span m=''1826320''>data
  is</span> <span m=''1826720''>mostly</span> <span m=''1828090''>[? rectangulineum
  ?],</span> <span m=''1828990''>multi-dimensional</span> <span m=''1829720''>rectangle.</span>
  </p><p><span m=''1830740''>So</span> <span m=''1830920''>for</span> <span m=''1831050''>example,</span>
  <span m=''1831580''>if</span> <span m=''1831730''>I</span> <span m=''1832090''>have</span>
  <span m=''1832290''>[UNINTELLIGIBLE]</span> <span m=''1832810''>and</span> <span
  m=''1832880''>it''s</span> <span m=''1833100''>a</span> <span m=''1833330''>one-dimensional</span>
  <span m=''1833700''>one,</span> <span m=''1833990''>this</span> <span m=''1834210''>is</span>
  <span m=''1834410''>basically</span> <span m=''1835060''>a</span> <span m=''1835140''>two-dimensional</span>
  <span m=''1835740''>data.</span> <span m=''1836050''>And</span> <span m=''1836130''>you</span>
  <span m=''1836260''>can</span> <span m=''1836390''>have three-dimensional</span>
  <span m=''1836990''>cubes</span> <span m=''1837380''>and</span> <span m=''1837480''>stuff</span>
  <span m=''1837740''>like</span> <span m=''1837900''>that.</span> <span m=''1838020''>You</span>
  <span m=''1838110''>can</span> <span m=''1838260''>represent</span> <span m=''1838390''>data</span>
  <span m=''1838510''>like that.</span> <span m=''1839500''>So</span> <span m=''1839730''>this</span>
  <span m=''1839910''>is</span> <span m=''1840050''>a</span> <span m=''1840080''>way</span>
  <span m=''1840380''>to</span> <span m=''1840450''>nicely</span> <span m=''1840690''>represent.</span>
  <span m=''1841170''>And</span> <span m=''1841460''>when</span> <span m=''1841570''>you</span>
  <span m=''1841650''>start</span> <span m=''1841890''>thinking</span> <span m=''1842210''>about</span>
  <span m=''1842500''>it,</span> <span m=''1844540''>we</span> <span m=''1844640''>can</span>
  <span m=''1844790''>look</span> <span m=''1844910''>at</span> <span m=''1845000''>what''s</span>
  <span m=''1845220''>going</span> <span m=''1845420''>on.</span> <span m=''1845850''>OK?</span>
  </p><p><span m=''1846780''>So</span> <span m=''1847170''>now</span> <span m=''1848290''>you</span>
  <span m=''1848440''>have</span> <span m=''1848590''>this</span> <span m=''1848950''>loop</span>
  <span m=''1849050''>again.</span> <span m=''1849870''>So</span> <span m=''1850040''>here''s</span>
  <span m=''1850570''>the</span> <span m=''1850660''>basic</span> <span m=''1851060''>[UNINTELLIGIBLE]</span>
  <span m=''1851170''>iterations.</span> <span m=''1852820''>And</span> <span m=''1853030''>here''s</span>
  <span m=''1853570''>the</span> <span m=''1853690''>data.</span> <span m=''1854140''>Assume</span>
  <span m=''1854430''>this</span> <span m=''1854570''>is</span> <span m=''1854710''>both</span>
  <span m=''1855000''>A</span> <span m=''1855160''>and</span> <span m=''1855470''>B.</span>
  <span m=''1855820''>There</span> <span m=''1855910''>will</span> <span m=''1856100''>be</span>
  <span m=''1856210''>another</span> <span m=''1856470''>one</span> <span m=''1856640''>for</span>
  <span m=''1856850''>matrix</span> <span m=''1857220''>[UNINTELLIGIBLE]</span> <span
  m=''1857480''>B. One</span> <span m=''1857800''>data</span> <span m=''1858050''>into</span>
  <span m=''1858310''>each</span> <span m=''1858560''>iteration</span> <span m=''1858920''>is</span>
  <span m=''1859020''>going</span> <span m=''1859130''>to touch.</span> <span m=''1859870''>So</span>
  <span m=''1860000''>these</span> <span m=''1860230''>are</span> <span m=''1860300''>the</span>
  <span m=''1860410''>data</span> <span m=''1860650''>that</span> <span m=''1860800''>need</span>
  <span m=''1860950''>to get</span> <span m=''1861090''>touched,</span> <span m=''1861520''>and</span>
  <span m=''1861700''>here''s</span> <span m=''1861900''>the iterations</span> <span
  m=''1862160''>you are</span> <span m=''1862420''>going to run.</span> </p><p><span
  m=''1864270''>So</span> <span m=''1865050''>we</span> <span m=''1865310''>can</span>
  <span m=''1865560''>say</span> <span m=''1867450''>OpenMP</span> <span m=''1868020''>parallel</span>
  <span m=''1868140''>four.</span> <span m=''1869720''>So</span> <span m=''1869860''>what</span>
  <span m=''1870070''>happens</span> <span m=''1870380''>when</span> <span m=''1870470''>you
  do</span> <span m=''1870540''>parallel</span> <span m=''1870950''>four?</span> <span
  m=''1872200''>So</span> <span m=''1873180''>I</span> <span m=''1873280''>am going</span>
  <span m=''1873490''>to</span> <span m=''1873560''>get</span> <span m=''1873750''>parallel.</span>
  <span m=''1874630''>And</span> <span m=''1875270''>so</span> <span m=''1875610''>core</span>
  <span m=''1875870''>one</span> <span m=''1876130''>gets</span> <span m=''1876470''>this</span>
  <span m=''1876710''>one,</span> <span m=''1876890''>another</span> <span m=''1877270''>core,</span>
  <span m=''1877560''>another</span> <span m=''1877760''>core,</span> <span m=''1877930''>another</span>
  <span m=''1878110''>core</span> <span m=''1878840''>get</span> <span m=''1879030''>these</span>
  <span m=''1879620''>iterations</span> <span m=''1880015''>running.</span> </p><p><span
  m=''1880610''>So</span> <span m=''1880780''>what</span> <span m=''1880960''>happens</span>
  <span m=''1881280''>if</span> <span m=''1881380''>you</span> <span m=''1881490''>do</span>
  <span m=''1881630''>this</span> <span m=''1881940''>one?</span> <span m=''1886520''>Do</span>
  <span m=''1886980''>you</span> <span m=''1887140''>get</span> <span m=''1887280''>really</span>
  <span m=''1887520''>good</span> <span m=''1887690''>performance?</span> <span m=''1889590''>Why?</span>
  </p><p><span m=''1891852''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''1894570''>PROFESSOR:
  It''s</span> <span m=''1894620''>not</span> <span m=''1894890''>balanced.</span>
  <span m=''1895080''>The</span> <span m=''1895360''>load</span> <span m=''1895550''>is
  not</span> <span m=''1895750''>balanced</span> <span m=''1895910''>in here.</span>
  <span m=''1896900''>So</span> <span m=''1897140''>basically</span> <span m=''1897660''>if</span>
  <span m=''1897840''>you</span> <span m=''1898320''>run</span> <span m=''1898630''>sequential</span>
  <span m=''1899210''>and</span> <span m=''1899530''>if</span> <span m=''1899660''>you</span>
  <span m=''1899720''>run</span> <span m=''1900150''>block</span> <span m=''1900350''>distribution,</span>
  <span m=''1901570''>I</span> <span m=''1901790''>get</span> <span m=''1902850''>about</span>
  <span m=''1904090''>3x</span> <span m=''1904420''>performance</span> <span m=''1904890''>in</span>
  <span m=''1905010''>here.</span> <span m=''1905990''>So</span> <span m=''1906130''>if</span>
  <span m=''1906320''>I</span> <span m=''1906430''>look</span> <span m=''1906620''>at</span>
  <span m=''1906810''>closely,</span> <span m=''1907880''>here is</span> <span m=''1908290''>the</span>
  <span m=''1908410''>number</span> <span m=''1908800''>of</span> <span m=''1908900''>iterations</span>
  <span m=''1909470''>given</span> <span m=''1909610''>to each</span> <span m=''1909905''>core.</span>
  <span m=''1911340''>The</span> <span m=''1911530''>first</span> <span m=''1911730''>core</span>
  <span m=''1911880''>gets</span> <span m=''1912090''>almost</span> <span m=''1912430''>nothing,</span>
  <span m=''1912890''>and</span> <span m=''1912990''>the</span> <span m=''1913080''>last</span>
  <span m=''1913380''>guy</span> <span m=''1913510''>gets</span> <span m=''1913790''>a</span>
  <span m=''1913820''>lot</span> <span m=''1914050''>of</span> <span m=''1914190''>work.</span>
  <span m=''1915380''>Here''s</span> <span m=''1915590''>where</span> <span m=''1916490''>something</span>
  <span m=''1916820''>like</span> <span m=''1916990''>the</span> <span m=''1917210''>Cilk</span>
  <span m=''1917430''>runtime</span> <span m=''1917980''>can</span> <span m=''1918150''>come</span>
  <span m=''1918320''>into</span> <span m=''1918510''>play</span> <span m=''1919280''>because</span>
  <span m=''1919720''>with</span> <span m=''1920090''>Cilk</span> <span m=''1920620''>runtime,</span>
  <span m=''1921050''>basically,</span> <span m=''1921490''>this</span> <span m=''1921730''>guy
  will</span> <span m=''1922180''>finish</span> <span m=''1922410''>the</span> <span
  m=''1922600''>[UNINTELLIGIBLE]</span> <span m=''1923040''>start</span> <span m=''1923300''>stealing</span>
  <span m=''1923630''>from</span> <span m=''1923790''>somebody</span> <span m=''1924160''>else.</span>
  <span m=''1924620''>And</span> <span m=''1925270''>so</span> <span m=''1925430''>it</span>
  <span m=''1925550''>would</span> <span m=''1925660''>be</span> <span m=''1926450''>done</span>
  <span m=''1926990''>nicely.</span> <span m=''1927620''>But</span> <span m=''1927850''>whereas</span>
  <span m=''1928060''>if</span> <span m=''1928150''>you</span> <span m=''1928450''>do</span>
  <span m=''1928550''>a</span> <span m=''1928600''>static</span> <span m=''1928920''>schedule,</span>
  <span m=''1929680''>you</span> <span m=''1929860''>are</span> <span m=''1930110''>in</span>
  <span m=''1930230''>this</span> <span m=''1930410''>big</span> <span m=''1930640''>bind.</span>
  <span m=''1931190''>You don''t</span> <span m=''1931430''>have</span> <span m=''1932450''>too</span>
  <span m=''1932550''>many</span> <span m=''1932680''>things</span> <span m=''1932910''>going</span>
  <span m=''1933170''>on.</span> </p><p><span m=''1937990''>And</span> <span m=''1938630''>basically,</span>
  <span m=''1939230''>this</span> <span m=''1939420''>is</span> <span m=''1939600''>what</span>
  <span m=''1939750''>we</span> <span m=''1939840''>call</span> <span m=''1940070''>load</span>
  <span m=''1940220''>imbalance.</span> <span m=''1940650''>So</span> <span m=''1940810''>what</span>
  <span m=''1941200''>you</span> <span m=''1941320''>can</span> <span m=''1941510''>do</span>
  <span m=''1941690''>is</span> <span m=''1942000''>figure</span> <span m=''1942320''>out</span>
  <span m=''1942550''>a</span> <span m=''1943200''>complicated</span> <span m=''1944130''>partitioning</span>
  <span m=''1944760''>so</span> <span m=''1944870''>you</span> <span m=''1944990''>can</span>
  <span m=''1945500''>statically</span> <span m=''1946190''>partition</span> <span
  m=''1946520''>this</span> <span m=''1946690''>out.</span> <span m=''1947645''>Or</span>
  <span m=''1947930''>you</span> <span m=''1948080''>can</span> <span m=''1948230''>do</span>
  <span m=''1948390''>something</span> <span m=''1948670''>like</span> <span m=''1948960''>the</span>
  <span m=''1949080''>dynamic</span> <span m=''1951080''>scheduler</span> <span m=''1951470''>like</span>
  <span m=''1951710''>the</span> <span m=''1951810''>[UNINTELLIGIBLE]</span> <span
  m=''1952530''>scheduler</span> <span m=''1953490''>for</span> <span m=''1953990''>a</span>
  <span m=''1954120''>solution.</span> </p><p><span m=''1955720''>So</span> <span
  m=''1955980''>how</span> <span m=''1956140''>to</span> <span m=''1956230''>detect</span>
  <span m=''1956270''>load</span> <span m=''1956400''>imbalance?</span> <span m=''1959290''>Basically,</span>
  <span m=''1960980''>what</span> <span m=''1961510''>you</span> <span m=''1961670''>might</span>
  <span m=''1961880''>want</span> <span m=''1962050''>to</span> <span m=''1962120''>do</span>
  <span m=''1962320''>is</span> <span m=''1963110''>for</span> <span m=''1963330''>each</span>
  <span m=''1963790''>of</span> <span m=''1963940''>the</span> <span m=''1964120''>different</span>
  <span m=''1964510''>sections</span> <span m=''1964870''>you are</span> <span m=''1965010''>running,</span>
  <span m=''1965300''>you want to</span> <span m=''1965430''>look</span> <span m=''1965610''>at</span>
  <span m=''1965690''>the</span> <span m=''1966430''>time</span> <span m=''1966670''>mistakes.</span>
  <span m=''1967520''>And in</span> <span m=''1967630''>the</span> <span m=''1967780''>[UNINTELLIGIBLE]</span>
  <span m=''1967900''>axis</span> <span m=''1968160''>varying,</span> <span m=''1969400''>huge</span>
  <span m=''1969810''>varying,</span> <span m=''1970530''>that</span> <span m=''1970730''>means</span>
  <span m=''1970910''>there''s</span> <span m=''1971080''>a</span> <span m=''1971380''>load
  imbalance</span> <span m=''1971720''>going</span> <span m=''1971940''>on.</span>
  <span m=''1972260''>So</span> <span m=''1972400''>you</span> <span m=''1972460''>might</span>
  <span m=''1972660''>want</span> <span m=''1972820''>to</span> <span m=''1972900''>check</span>
  <span m=''1973670''>and make sure</span> <span m=''1974050''>each</span> <span m=''1974760''>of</span>
  <span m=''1974810''>the</span> <span m=''1975200''>parallel regions</span> <span
  m=''1975780''>time is taking.</span> <span m=''1978330''>And</span> <span m=''1978840''>that</span>
  <span m=''1979010''>gives</span> <span m=''1979210''>you</span> <span m=''1979320''>this</span>
  <span m=''1979530''>view.</span> </p><p><span m=''1981370''>How</span> <span m=''1981580''>to</span>
  <span m=''1981760''>eliminate</span> <span m=''1981840''>load</span> <span m=''1982150''>imbalance</span>
  <span m=''1983610''>or</span> <span m=''1983730''>the</span> <span m=''1984400''>use</span>
  <span m=''1984560''>of</span> <span m=''1984620''>dynamic</span> <span m=''1986550''>scheduler</span>
  <span m=''1986870''>that</span> <span m=''1987050''>will</span> <span m=''1987200''>deal</span>
  <span m=''1987430''>with</span> <span m=''1987600''>that.</span> <span m=''1988500''>Or</span>
  <span m=''1988700''>you can</span> <span m=''1988900''>do</span> <span m=''1989090''>a</span>
  <span m=''1989140''>different</span> <span m=''1989910''>distribution</span> <span
  m=''1991130''>statically.</span> <span m=''1992220''>That</span> <span m=''1992490''>will</span>
  <span m=''1992680''>not</span> <span m=''1993040''>partition</span> <span m=''1993640''>in
  this</span> <span m=''1993770''>large</span> <span m=''1994270''>block.</span> <span
  m=''1994690''>So</span> <span m=''1994840''>let</span> <span m=''1994980''>me</span>
  <span m=''1995130''>show</span> <span m=''1995350''>you</span> <span m=''1995560''>a</span>
  <span m=''1995630''>static</span> <span m=''1995940''>part</span> <span m=''1996190''>because</span>
  <span m=''1996420''>we</span> <span m=''1996580''>have already</span> <span m=''1996900''>learned</span>
  <span m=''1997090''>the</span> <span m=''1997190''>dynamic</span> <span m=''1997590''>part</span>
  <span m=''1997740''>before.</span> </p><p><span m=''1998440''>So</span> <span m=''1998820''>now</span>
  <span m=''1999090''>instead</span> <span m=''1999350''>of</span> <span m=''1999500''>doing</span>
  <span m=''1999720''>that,</span> <span m=''1999910''>we do</span> <span m=''2000090''>a</span>
  <span m=''2000290''>cyclic</span> <span m=''2000800''>distribution.</span> <span
  m=''2001165''>We use</span> <span m=''2001530''>a static</span> <span m=''2001850''>one.</span>
  <span m=''2003370''>That</span> <span m=''2003620''>means</span> <span m=''2005690''>if</span>
  <span m=''2005820''>you</span> <span m=''2005950''>have</span> <span m=''2006060''>a</span>
  <span m=''2006150''>lot</span> <span m=''2006470''>more</span> <span m=''2006660''>than</span>
  <span m=''2006860''>and a</span> <span m=''2007020''>little bit</span> <span m=''2007690''>better</span>
  <span m=''2008020''>distribution</span> <span m=''2008550''>so</span> <span m=''2008670''>what</span>
  <span m=''2008850''>happens</span> <span m=''2009160''>to</span> <span m=''2009240''>the</span>
  <span m=''2009320''>processor?</span> <span m=''2012220''>Zero</span> <span m=''2012500''>gets</span>
  <span m=''2012810''>this</span> <span m=''2013010''>one</span> <span m=''2013250''>and</span>
  <span m=''2013360''>this</span> <span m=''2013570''>one.</span> <span m=''2013810''>One</span>
  <span m=''2014080''>gets</span> <span m=''2014330''>this</span> <span m=''2014530''>one</span>
  <span m=''2014700''>and</span> <span m=''2014800''>this</span> <span m=''2015000''>one.</span>
  <span m=''2015740''>So</span> <span m=''2015910''>on</span> <span m=''2016000''>and</span>
  <span m=''2016110''>so</span> <span m=''2016220''>forth.</span> <span m=''2016860''>So</span>
  <span m=''2017040''>that</span> <span m=''2017180''>would</span> <span m=''2017270''>be</span>
  <span m=''2017350''>a</span> <span m=''2017390''>little</span> <span m=''2017660''>bit</span>
  <span m=''2017780''>between balancing</span> <span m=''2018050''>there.</span> <span
  m=''2019380''>But</span> <span m=''2020190''>if</span> <span m=''2020300''>you</span>
  <span m=''2020490''>have</span> <span m=''2020740''>enough</span> <span m=''2021230''>of
  cyclic,</span> <span m=''2021500''>the</span> <span m=''2022090''>imbalance</span>
  <span m=''2022510''>would</span> <span m=''2022710''>be</span> <span m=''2022830''>much</span>
  <span m=''2022980''>lower.</span> </p><p><span m=''2025550''>So</span> <span m=''2026690''>should</span>
  <span m=''2026730''>we</span> <span m=''2026880''>run</span> <span m=''2027160''>faster?</span>
  <span m=''2031070''>So</span> <span m=''2031670''>here''s</span> <span m=''2032300''>the</span>
  <span m=''2033090''>iterations</span> <span m=''2033810''>each</span> <span m=''2034090''>guy</span>
  <span m=''2034340''>gets</span> <span m=''2034900''>in</span> <span m=''2035150''>here.</span>
  <span m=''2036470''>This</span> <span m=''2036740''>looks</span> <span m=''2036960''>very</span>
  <span m=''2037170''>balanced</span> <span m=''2037610''>because</span> <span m=''2038460''>I</span>
  <span m=''2038580''>had</span> <span m=''2038850''>a lot</span> <span m=''2039120''>more</span>
  <span m=''2039360''>iterations</span> <span m=''2039880''>than</span> <span m=''2041340''>this</span>
  <span m=''2041500''>eight</span> <span m=''2041630''>one.</span> <span m=''2041810''>This
  is not</span> <span m=''2041990''>that balanced here</span> <span m=''2042140''>because</span>
  <span m=''2042560''>this</span> <span m=''2042870''>guy</span> <span m=''2042980''>gets</span>
  <span m=''2043190''>a</span> <span m=''2043210''>lot</span> <span m=''2043420''>more</span>
  <span m=''2043580''>than</span> <span m=''2043750''>the</span> <span m=''2043830''>first</span>
  <span m=''2044100''>one.</span> <span m=''2044800''>The first</span> <span m=''2045090''>one</span>
  <span m=''2046040''>gets</span> <span m=''2046380''>six.</span> <span m=''2046820''>And</span>
  <span m=''2047060''>the</span> <span m=''2047370''>second and</span> <span m=''2047680''>last</span>
  <span m=''2047990''>one</span> <span m=''2048139''>gets</span> <span m=''2048580''>a</span>
  <span m=''2048620''>lot</span> <span m=''2048860''>more.</span> </p><p><span m=''2053775''>Uh</span>
  <span m=''2054239''>oh.</span> <span m=''2056560''>What</span> <span m=''2056750''>do
  you</span> <span m=''2056900''>think is</span> <span m=''2057239''>happening</span>
  <span m=''2057710''>here</span> <span m=''2057920''>now?</span> <span m=''2062040''>I
  ran</span> <span m=''2062199''>again</span> <span m=''2062460''>slower.</span> <span
  m=''2065870''>See</span> <span m=''2066100''>I</span> <span m=''2066170''>guess</span>
  <span m=''2066389''>the</span> <span m=''2066469''>people</span> <span m=''2066790''>in</span>
  <span m=''2066920''>class</span> <span m=''2067219''>last</span> <span m=''2067540''>year</span>
  <span m=''2067699''>had</span> <span m=''2068020''>things</span> <span m=''2068429''>worse</span>
  <span m=''2068800''>because</span> <span m=''2069110''>they</span> <span m=''2069210''>had</span>
  <span m=''2069320''>this</span> <span m=''2069400''>old</span> <span m=''2069650''>processor</span>
  <span m=''2070550''>that</span> <span m=''2070840''>did</span> <span m=''2070920''>all</span>
  <span m=''2071199''>these</span> <span m=''2071389''>crazy</span> <span m=''2071670''>things</span>
  <span m=''2071940''>on</span> <span m=''2072060''>them.</span> <span m=''2073010''>and</span>
  <span m=''2073350''>you</span> <span m=''2073449''>guys</span> <span m=''2073690''>get</span>
  <span m=''2073790''>the</span> <span m=''2073900''>fast</span> <span m=''2074260''>one</span>
  <span m=''2074600''>that</span> <span m=''2075400''>doesn''t</span> <span m=''2075540''>do
  that.</span> </p><p><span m=''2075830''>So</span> <span m=''2075980''>why</span>
  <span m=''2076179''>do you</span> <span m=''2076330''>think</span> <span m=''2078199''>cyclic</span>
  <span m=''2078400''>distribution</span> <span m=''2080812''>is</span> <span m=''2081310''>running</span>
  <span m=''2081710''>a lot</span> <span m=''2081800''>slower?</span> <span m=''2083639''>What</span>
  <span m=''2083840''>might</span> <span m=''2084030''>be</span> <span m=''2084159''>going?</span>
  </p><p><span m=''2084454''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''2087420''>PROFESSOR:
  Spoiling</span> <span m=''2087860''>[UNINTELLIGIBLE]</span> <span m=''2088300''>it''s</span>
  <span m=''2088719''>not</span> <span m=''2088969''>that</span> <span m=''2089219''>much</span>
  <span m=''2089489''>because</span> <span m=''2089940''>if</span> <span m=''2090040''>you
  don''t</span> <span m=''2090320''>run</span> <span m=''2090600''>this</span> <span
  m=''2090750''>and</span> <span m=''2090980''>synchronize,</span> <span m=''2091489''>what</span>
  <span m=''2091670''>you</span> <span m=''2091830''>do</span> <span m=''2091989''>is</span>
  <span m=''2092500''>you</span> <span m=''2092679''>run</span> <span m=''2092929''>the</span>
  <span m=''2093030''>same</span> <span m=''2093370''>amount</span> <span m=''2093580''>of</span>
  <span m=''2093800''>tread</span> <span m=''2094080''>and</span> <span m=''2094360''>say,</span>
  <span m=''2094469''>now,</span> <span m=''2094650''>instead</span> <span m=''2094929''>of</span>
  <span m=''2095340''>running</span> <span m=''2095510''>continuously,</span> <span
  m=''2095670''>you</span> <span m=''2096030''>run</span> <span m=''2097110''>jumping</span>
  <span m=''2097370''>all</span> <span m=''2097690''>iterations.</span> <span m=''2099260''>You
  should</span> <span m=''2099330''>run</span> <span m=''2099470''>zero</span> <span
  m=''2099700''>and nine</span> <span m=''2099930''>or</span> <span m=''2100150''>whatever</span>
  <span m=''2100830''>jump</span> <span m=''2101520''>over</span> <span m=''2101810''>iterations.</span>
  <span m=''2112500''>Why</span> <span m=''2112650''>do</span> <span m=''2112710''>you</span>
  <span m=''2112770''>think?</span> </p><p><span m=''2113130''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''2114630''>PROFESSOR: Yeah,</span> <span m=''2115090''>there''s</span>
  <span m=''2115270''>a</span> <span m=''2115390''>cache</span> <span m=''2115665''>issue.</span>
  <span m=''2116240''>All</span> <span m=''2116510''>this</span> <span m=''2116790''>time</span>
  <span m=''2117020''>and</span> <span m=''2117130''>the</span> <span m=''2118520''>question</span>
  <span m=''2118870''>is</span> <span m=''2118960''>not</span> <span m=''2119200''>sure,</span>
  <span m=''2119350''>it''s</span> <span m=''2119430''>probably</span> <span m=''2119880''>a</span>
  <span m=''2119980''>cache issue.</span> <span m=''2120470''>What</span> <span m=''2120760''>type</span>
  <span m=''2120920''>of</span> <span m=''2121080''>cache</span> <span m=''2121400''>issue</span>
  <span m=''2121560''>do you</span> <span m=''2121760''>think is</span> <span m=''2122130''>going</span>
  <span m=''2122370''>on?</span> </p><p><span m=''2122550''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''2128920''>PROFESSOR: Yeah.</span> <span m=''2129410''>[UNINTELLIGIBLE].</span>
  <span m=''2131010''>But</span> <span m=''2132820''>let</span> <span m=''2133020''>me</span>
  <span m=''2133090''>show</span> <span m=''2133230''>you</span> <span m=''2133350''>what</span>
  <span m=''2133540''>happens.</span> <span m=''2134280''>So</span> <span m=''2134440''>you</span>
  <span m=''2134610''>get</span> <span m=''2134650''>off</span> <span m=''2134830''>then.</span>
  <span m=''2135580''>OK,</span> <span m=''2136080''>so</span> <span m=''2136730''>if</span>
  <span m=''2136860''>you</span> <span m=''2137000''>look</span> <span m=''2137160''>at--</span>
  <span m=''2137780''>the</span> <span m=''2138060''>data</span> <span m=''2138530''>is
  here</span> <span m=''2138810''>so</span> <span m=''2139380''>let''s</span> <span
  m=''2139610''>look at</span> <span m=''2139700''>what</span> <span m=''2139900''>happens.</span>
  <span m=''2140150''>So</span> <span m=''2140270''>this</span> <span m=''2140460''>is</span>
  <span m=''2140570''>running</span> <span m=''2140800''>a</span> <span m=''2140870''>[UNINTELLIGIBLE]</span>
  <span m=''2141260''>lower.</span> <span m=''2142950''>It''s</span> <span m=''2143100''>showing</span>
  <span m=''2143400''>a</span> <span m=''2143690''>lot more</span> <span m=''2143850''>instructions,</span>
  <span m=''2144410''>but</span> <span m=''2144880''>instruction</span> <span m=''2145460''>doesn''t</span>
  <span m=''2145740''>tell</span> <span m=''2145910''>you</span> <span m=''2146080''>too</span>
  <span m=''2146280''>much</span> <span m=''2146500''>because</span> <span m=''2146850''>a</span>
  <span m=''2146890''>lot</span> <span m=''2147140''>of</span> <span m=''2147240''>them</span>
  <span m=''2147460''>might</span> <span m=''2147670''>be missing</span> <span m=''2147750''>synchronization</span>
  <span m=''2148480''>costs</span> <span m=''2148920''>in here.</span> <span m=''2149360''>So</span>
  <span m=''2149470''>instruction</span> <span m=''2149950''>is</span> <span m=''2150060''>not</span>
  <span m=''2150200''>that</span> <span m=''2150510''>illuminating</span> <span m=''2150860''>here.</span>
  </p><p><span m=''2152690''>The</span> <span m=''2152900''>big</span> <span m=''2153190''>illumination</span>
  <span m=''2153520''>here</span> <span m=''2153850''>is</span> <span m=''2154120''>this</span>
  <span m=''2154320''>one</span> <span m=''2154460''>again.</span> <span m=''2154850''>Invalidations.</span>
  <span m=''2156950''>I</span> <span m=''2157000''>have</span> <span m=''2157200''>a</span>
  <span m=''2157410''>huge</span> <span m=''2157520''>amount</span> <span m=''2157680''>of
  invalidations</span> <span m=''2157710''>going</span> <span m=''2157880''>on.</span>
  </p><p><span m=''2159300''>So</span> <span m=''2161040''>here</span> <span m=''2161720''>is</span>
  <span m=''2161920''>a</span> <span m=''2161990''>case</span> <span m=''2162370''>of</span>
  <span m=''2162470''>false sharing.</span> <span m=''2164330''>So</span> <span m=''2164510''>what</span>
  <span m=''2164730''>happens</span> <span m=''2165120''>is</span> <span m=''2165290''>now</span>
  <span m=''2166110''>things</span> <span m=''2166430''>next</span> <span m=''2166700''>to</span>
  <span m=''2166760''>each</span> <span m=''2167020''>other,</span> <span m=''2167510''>you</span>
  <span m=''2167710''>want</span> <span m=''2168080''>to</span> <span m=''2168230''>multiply</span>
  <span m=''2168680''>different</span> <span m=''2168980''>processors.</span> <span
  m=''2169550''>We''re</span> <span m=''2169940''>not touching</span> <span m=''2170060''>the</span>
  <span m=''2170120''>same</span> <span m=''2170340''>data.</span> <span m=''2170890''>Everybody''s</span>
  <span m=''2171310''>looking</span> <span m=''2171540''>at</span> <span m=''2171600''>somebody</span>
  <span m=''2171920''>else''s</span> <span m=''2172220''>data.</span> </p><p><span
  m=''2173250''>So</span> <span m=''2173420''>what</span> <span m=''2173600''>happens</span>
  <span m=''2173930''>is</span> <span m=''2174030''>assume</span> <span m=''2174290''>I</span>
  <span m=''2174490''>want</span> <span m=''2174650''>to</span> <span m=''2174700''>write</span>
  <span m=''2174960''>this</span> <span m=''2175110''>data</span> <span m=''2175350''>item.</span>
  <span m=''2176290''>I like that</span> <span m=''2176480''>data item.</span> <span
  m=''2177550''>But</span> <span m=''2177810''>I</span> <span m=''2177940''>get</span>
  <span m=''2178180''>the entire</span> <span m=''2178520''>cache</span> <span m=''2178820''>line</span>
  <span m=''2180850''>because</span> <span m=''2181120''>when</span> <span m=''2181250''>I</span>
  <span m=''2182330''>ask for that,</span> <span m=''2182480''>I</span> <span m=''2182900''>get</span>
  <span m=''2183190''>my</span> <span m=''2183330''>synchronization</span> <span m=''2184120''>by</span>
  <span m=''2184250''>the</span> <span m=''2184400''>cache</span> <span m=''2184670''>line.</span>
  <span m=''2185330''>I</span> <span m=''2185450''>get</span> <span m=''2185630''>this</span>
  <span m=''2185710''>entire</span> <span m=''2185910''>cache</span> <span m=''2186050''>line</span>
  <span m=''2186580''>coming in</span> <span m=''2187010''>here</span> <span m=''2188020''>into</span>
  <span m=''2188040''>this</span> <span m=''2188160''>one.</span> </p><p><span m=''2188830''>And</span>
  <span m=''2189090''>the</span> <span m=''2189170''>next</span> <span m=''2189490''>guys</span>
  <span m=''2189660''>[UNINTELLIGIBLE]</span> <span m=''2189970''>at me.</span> <span
  m=''2190550''>This</span> <span m=''2190800''>core</span> <span m=''2191110''>won''t</span>
  <span m=''2191420''>write</span> <span m=''2191610''>this data</span> <span m=''2191860''>because</span>
  <span m=''2192660''>instead</span> <span m=''2192930''>of</span> <span m=''2193020''>blocks,</span>
  <span m=''2193460''>I</span> <span m=''2193590''>basically</span> <span m=''2194140''>give</span>
  <span m=''2194490''>each</span> <span m=''2194790''>strips.</span> <span m=''2196000''>There''s</span>
  <span m=''2196180''>a</span> <span m=''2196210''>lot</span> <span m=''2196380''>of</span>
  <span m=''2196460''>overlap</span> <span m=''2196930''>between</span> <span m=''2197215''>strips.</span>
  <span m=''2197840''>So</span> <span m=''2198020''>this</span> <span m=''2198270''>guy</span>
  <span m=''2198490''>says</span> <span m=''2199060''>not</span> <span m=''2199410''>to</span>
  <span m=''2199470''>write</span> <span m=''2199780''>this</span> <span m=''2200010''>one,</span>
  <span m=''2200150''>I</span> <span m=''2200190''>had</span> <span m=''2200340''>to</span>
  <span m=''2200500''>get</span> <span m=''2200740''>the</span> <span m=''2201000''>entire
  cache</span> <span m=''2201260''>line</span> <span m=''2201480''>going</span> <span
  m=''2201690''>back</span> <span m=''2201880''>here.</span> </p><p><span m=''2203580''>And</span>
  <span m=''2203840''>so</span> <span m=''2203920''>if</span> <span m=''2204050''>you</span>
  <span m=''2204190''>want</span> <span m=''2204330''>to</span> <span m=''2204370''>write</span>
  <span m=''2204590''>that</span> <span m=''2204750''>again,</span> <span m=''2205080''>I</span>
  <span m=''2205130''>had</span> <span m=''2205210''>to</span> <span m=''2205300''>get</span>
  <span m=''2205460''>the</span> <span m=''2205630''>entire cache line</span> <span
  m=''2206100''>going</span> <span m=''2206300''>back</span> <span m=''2206450''>even</span>
  <span m=''2206630''>though</span> <span m=''2206780''>we</span> <span m=''2207045''>are</span>
  <span m=''2207310''>writing</span> <span m=''2207680''>different</span> <span m=''2208050''>data.</span>
  <span m=''2208790''>Because</span> <span m=''2209350''>we</span> <span m=''2209500''>are
  sharing</span> <span m=''2210130''>cache</span> <span m=''2210490''>lines</span>
  <span m=''2211170''>in</span> <span m=''2211360''>here.</span> <span m=''2212010''>This</span>
  <span m=''2212220''>thinking</span> <span m=''2212640''>was</span> <span m=''2212910''>in</span>
  <span m=''2212980''>back</span> <span m=''2213220''>and</span> <span m=''2213340''>forth,</span>
  <span m=''2213500''>back</span> <span m=''2213730''>and</span> <span m=''2213880''>forth,</span>
  <span m=''2214040''>back</span> <span m=''2214260''>and</span> <span m=''2214390''>forth.</span>
  <span m=''2214960''>I</span> <span m=''2215100''>have</span> <span m=''2215290''>a</span>
  <span m=''2215310''>lot</span> <span m=''2215540''>of</span> <span m=''2215650''>cache</span>
  <span m=''2215930''>[UNINTELLIGIBLE].</span> <span m=''2216520''>Things</span> <span
  m=''2216810''>are</span> <span m=''2216980''>really</span> <span m=''2217050''>shot.</span>
  <span m=''2219200''>OK?</span> </p><p><span m=''2220160''>And</span> <span m=''2220790''>so</span>
  <span m=''2220920''>what</span> <span m=''2221110''>happens</span> <span m=''2221520''>here
  is</span> <span m=''2222000''>if</span> <span m=''2222480''>you</span> <span m=''2222560''>look</span>
  <span m=''2222710''>at</span> <span m=''2222800''>the</span> <span m=''2222910''>cache</span>
  <span m=''2223260''>lines--</span> <span m=''2223740''>there''s</span> <span m=''2223960''>my</span>
  <span m=''2224090''>animation.</span> <span m=''2225140''>So</span> <span m=''2225490''>cache</span>
  <span m=''2225850''>lines</span> <span m=''2226130''>basically</span> <span m=''2226600''>mess</span>
  <span m=''2226830''>this</span> <span m=''2226920''>all</span> <span m=''2227190''>up.</span>
  <span m=''2227280''>You can</span> <span m=''2227420''>see</span> <span m=''2227900''>that</span>
  <span m=''2228060''>really</span> <span m=''2228300''>carefully.</span> <span m=''2228690''>What</span>
  <span m=''2228860''>happens</span> <span m=''2229200''>is</span> <span m=''2229700''>between</span>
  <span m=''2231190''>these</span> <span m=''2231620''>lines,</span> <span m=''2231940''>there</span>
  <span m=''2232090''>would</span> <span m=''2232200''>be</span> <span m=''2232300''>some
  overlap</span> <span m=''2232700''>of cache lines.</span> <span m=''2235710''>And</span>
  <span m=''2236000''>this</span> <span m=''2236070''>overlap</span> <span m=''2236170''>in</span>
  <span m=''2236340''>cache</span> <span m=''2236390''>lines</span> <span m=''2237110''>keeps</span>
  <span m=''2237210''>bouncing</span> <span m=''2237560''>back</span> <span m=''2237760''>and</span>
  <span m=''2237890''>forth,</span> <span m=''2238030''>back</span> <span m=''2238250''>and</span>
  <span m=''2238380''>forth</span> <span m=''2238600''>in here.</span> </p><p><span
  m=''2239990''>And</span> <span m=''2241130''>so</span> <span m=''2241320''>what</span>
  <span m=''2241490''>happens</span> <span m=''2241850''>is</span> <span m=''2241990''>basically</span>
  <span m=''2243010''>cache lines</span> <span m=''2243510''>are</span> <span m=''2243630''>bigger</span>
  <span m=''2243910''>than</span> <span m=''2244160''>the</span> <span m=''2244250''>data</span>
  <span m=''2244510''>size,</span> <span m=''2245390''>or</span> <span m=''2245560''>there''s</span>
  <span m=''2246250''>overlap</span> <span m=''2246840''>in</span> <span m=''2247120''>here,</span>
  <span m=''2248416''>and</span> <span m=''2248850''>the</span> <span m=''2248960''>cache</span>
  <span m=''2249280''>line</span> <span m=''2249530''>is shared</span> <span m=''2249720''>when
  the</span> <span m=''2250120''>data</span> <span m=''2250330''>is</span> <span m=''2250450''>not</span>
  <span m=''2250600''>shared.</span> </p><p><span m=''2251480''>And</span> <span m=''2253690''>so</span>
  <span m=''2254300''>how</span> <span m=''2254460''>to</span> <span m=''2254630''>detect</span>
  <span m=''2255100''>false</span> <span m=''2255500''>sharing</span> <span m=''2255770''>in</span>
  <span m=''2255940''>too many</span> <span m=''2256270''>conflicts.</span> <span
  m=''2257050''>You</span> <span m=''2258030''>assume</span> <span m=''2258440''>this</span>
  <span m=''2258740''>is</span> <span m=''2258910''>a</span> <span m=''2259010''>nice</span>
  <span m=''2259320''>parallelism,</span> <span m=''2259860''>but</span> <span m=''2260040''>suddenly,</span>
  <span m=''2260970''>you</span> <span m=''2261340''>don''t</span> <span m=''2262190''>have</span>
  <span m=''2262270''>a</span> <span m=''2262360''>speed</span> <span m=''2262640''>up,</span>
  <span m=''2262830''>and</span> <span m=''2262950''>you have</span> <span m=''2263120''>a
  lot</span> <span m=''2263430''>of conflicts</span> <span m=''2263560''>here,</span>
  <span m=''2263840''>even</span> <span m=''2264160''>though</span> <span m=''2264440''>there
  isn''t</span> <span m=''2264650''>something</span> <span m=''2264990''>to</span>
  <span m=''2265120''>be</span> <span m=''2265270''>sharing.</span> </p><p><span m=''2267090''>And</span>
  <span m=''2267170''>how to</span> <span m=''2267260''>eliminate</span> <span m=''2267790''>false</span>
  <span m=''2268000''>sharing.</span> <span m=''2269770''>Make</span> <span m=''2270190''>data</span>
  <span m=''2270740''>used</span> <span m=''2271050''>by</span> <span m=''2271550''>each</span>
  <span m=''2272080''>contiguous</span> <span m=''2272620''>in</span> <span m=''2272750''>memory.</span>
  <span m=''2274250''>That''s</span> <span m=''2274440''>a</span> <span m=''2274490''>good</span>
  <span m=''2274660''>way of doing</span> <span m=''2275100''>that.</span> <span m=''2275550''>Or
  pad</span> <span m=''2276010''>at</span> <span m=''2276310''>the</span> <span m=''2276530''>end.</span>
  <span m=''2277360''>So</span> <span m=''2278190''>these</span> <span m=''2278510''>kind</span>
  <span m=''2278810''>of</span> <span m=''2278880''>at</span> <span m=''2279200''>the</span>
  <span m=''2279300''>corners,</span> <span m=''2279720''>there''s</span> <span m=''2279930''>not</span>
  <span m=''2280140''>going</span> <span m=''2280230''>to</span> <span m=''2280330''>be</span>
  <span m=''2280430''>any</span> <span m=''2280580''>overlapping.</span> </p><p><span
  m=''2282830''>So</span> <span m=''2283120''>in</span> <span m=''2283400''>here,</span>
  <span m=''2283710''>one</span> <span m=''2283870''>thing</span> <span m=''2283990''>you</span>
  <span m=''2284140''>can</span> <span m=''2284300''>do</span> <span m=''2284470''>is,</span>
  <span m=''2286320''>you</span> <span m=''2286470''>can</span> <span m=''2286670''>measure</span>
  <span m=''2287090''>each</span> <span m=''2287770''>thing</span> <span m=''2288070''>that</span>
  <span m=''2288550''>each</span> <span m=''2288930''>of</span> <span m=''2289090''>the</span>
  <span m=''2289380''>cores</span> <span m=''2289820''>get.</span> <span m=''2290370''>We</span>
  <span m=''2290480''>can</span> <span m=''2290680''>make</span> <span m=''2290880''>[UNINTELLIGIBLE].</span>
  <span m=''2291350''>But</span> <span m=''2291480''>before</span> <span m=''2291960''>what</span>
  <span m=''2292120''>happens</span> <span m=''2292430''>was</span> <span m=''2293340''>a</span>
  <span m=''2293530''>core</span> <span m=''2293830''>used</span> <span m=''2294010''>to</span>
  <span m=''2294100''>get</span> <span m=''2294350''>this</span> <span m=''2294560''>line</span>
  <span m=''2294800''>and</span> <span m=''2294920''>this</span> <span m=''2295120''>line.</span>
  <span m=''2295970''>There are</span> <span m=''2296310''>different</span> <span
  m=''2296680''>places</span> <span m=''2297010''>in</span> <span m=''2297130''>memory.</span>
  <span m=''2297730''>But</span> <span m=''2297980''>you</span> <span m=''2298100''>can</span>
  <span m=''2298300''>make</span> <span m=''2298560''>these</span> <span m=''2298790''>two</span>
  <span m=''2298940''>contiguous</span> <span m=''2299450''>in</span> <span m=''2299550''>memory</span>
  <span m=''2299910''>by</span> <span m=''2300220''>basically</span> <span m=''2300990''>now,</span>
  <span m=''2301160''>instead</span> <span m=''2301500''>of</span> <span m=''2301610''>having</span>
  <span m=''2301840''>a</span> <span m=''2301940''>two-dimensional</span> <span m=''2302190''>array,</span>
  <span m=''2303075''>you</span> <span m=''2303410''>made</span> <span m=''2303650''>that</span>
  <span m=''2303790''>a</span> <span m=''2303940''>three-dimensional</span> <span
  m=''2304520''>or</span> <span m=''2304860''>disarrays.</span> </p><p><span m=''2306210''>AUDIENCE:
  Can</span> <span m=''2306630''>you say that again?</span> </p><p><span m=''2307890''>PROFESSOR:
  So</span> <span m=''2308240''>before</span> <span m=''2308590''>you</span> <span
  m=''2308710''>what</span> <span m=''2308920''>just</span> <span m=''2309140''>happened</span>
  <span m=''2309280''>was</span> <span m=''2309640''>each</span> <span m=''2310010''>of</span>
  <span m=''2310150''>them</span> <span m=''2311030''>were</span> <span m=''2311240''>going</span>
  <span m=''2311470''>to</span> <span m=''2311530''>get</span> <span m=''2311780''>this</span>
  <span m=''2312030''>line</span> <span m=''2312340''>and</span> <span m=''2312480''>this</span>
  <span m=''2312690''>line,</span> <span m=''2313030''>each</span> <span m=''2313370''>core.</span>
  <span m=''2314210''>All</span> <span m=''2314440''>these</span> <span m=''2314670''>lines</span>
  <span m=''2314850''>that</span> <span m=''2315200''>were</span> <span m=''2316830''>in</span>
  <span m=''2317030''>different</span> <span m=''2317420''>parts</span> <span m=''2317670''>of</span>
  <span m=''2317730''>the</span> <span m=''2317800''>memory.</span> <span m=''2318070''>In</span>
  <span m=''2318150''>here,</span> <span m=''2318650''>each</span> <span m=''2318920''>would</span>
  <span m=''2319120''>get</span> <span m=''2319410''>only</span> <span m=''2319700''>two</span>
  <span m=''2319965''>lines.</span> <span m=''2320510''>But they''re in</span> <span
  m=''2320670''>a</span> <span m=''2320840''>different place.</span> <span m=''2321570''>So</span>
  <span m=''2321690''>if</span> <span m=''2321760''>you</span> <span m=''2321850''>have</span>
  <span m=''2321940''>more</span> <span m=''2322170''>cyclic,</span> <span m=''2322540''>you''ll</span>
  <span m=''2322720''>get</span> <span m=''2322890''>a</span> <span m=''2322910''>lot</span>
  <span m=''2323130''>more</span> <span m=''2323310''>lines</span> <span m=''2323630''>or
  lower</span> <span m=''2324130''>memory.</span> </p><p><span m=''2324820''>So</span>
  <span m=''2324970''>what</span> <span m=''2325100''>we</span> <span m=''2325330''>can</span>
  <span m=''2325390''>do</span> <span m=''2325650''>is</span> <span m=''2326390''>we</span>
  <span m=''2326780''>can</span> <span m=''2327000''>arrange</span> <span m=''2327230''>the</span>
  <span m=''2327340''>cache.</span> <span m=''2327830''>So</span> <span m=''2327940''>if</span>
  <span m=''2328080''>you</span> <span m=''2328230''>think</span> <span m=''2328470''>about</span>
  <span m=''2328770''>this,</span> <span m=''2329330''>you</span> <span m=''2329490''>can</span>
  <span m=''2329650''>think</span> <span m=''2329840''>the</span> <span m=''2329950''>cache,</span>
  <span m=''2330340''>now</span> <span m=''2330560''>the</span> <span m=''2331190''>data,</span>
  <span m=''2331540''>is instead</span> <span m=''2331750''>of</span> <span m=''2332010''>two-dimensions</span>
  <span m=''2332780''>is</span> <span m=''2333220''>three-dimensional</span> <span
  m=''2333660''>data.</span> <span m=''2335390''>One</span> <span m=''2335650''>dimension</span>
  <span m=''2336100''>is</span> <span m=''2336350''>this cyclic</span> <span m=''2337200''>part</span>
  <span m=''2337530''>in</span> <span m=''2337630''>here.</span> <span m=''2338360''>So</span>
  <span m=''2338850''>we</span> <span m=''2339030''>can</span> <span m=''2339190''>do</span>
  <span m=''2339290''>that.</span> </p><p><span m=''2339450''>And</span> <span m=''2339670''>then,</span>
  <span m=''2339920''>you</span> <span m=''2340030''>can</span> <span m=''2340230''>change</span>
  <span m=''2340575''>any</span> <span m=''2340920''>way</span> <span m=''2341720''>that</span>
  <span m=''2342070''>the</span> <span m=''2342460''>cyclic</span> <span m=''2343110''>part,</span>
  <span m=''2343940''>the</span> <span m=''2344030''>one</span> <span m=''2344250''>that</span>
  <span m=''2344420''>I</span> <span m=''2344480''>got</span> <span m=''2344700''>this</span>
  <span m=''2344940''>line</span> <span m=''2345230''>and</span> <span m=''2345360''>this</span>
  <span m=''2345580''>line,</span> <span m=''2345830''>now</span> <span m=''2345980''>become</span>
  <span m=''2346290''>contiguous.</span> <span m=''2347660''>So</span> <span m=''2348240''>you</span>
  <span m=''2348680''>think</span> <span m=''2348930''>about</span> <span m=''2349160''>data</span>
  <span m=''2349430''>as</span> <span m=''2349780''>a</span> <span m=''2349950''>two-dimension.</span>
  <span m=''2350390''>You</span> <span m=''2350690''>think</span> <span m=''2350860''>about</span>
  <span m=''2351010''>it</span> <span m=''2351170''>as</span> <span m=''2351300''>a</span>
  <span m=''2351570''>cube.</span> <span m=''2351790''>And</span> <span m=''2351930''>you</span>
  <span m=''2352010''>kind</span> <span m=''2352190''>of</span> <span m=''2352270''>change</span>
  <span m=''2352530''>the</span> <span m=''2352640''>cube</span> <span m=''2353740''>for</span>
  <span m=''2353960''>the</span> <span m=''2354120''>inner</span> <span m=''2354280''>dimension</span>
  <span m=''2354690''>to</span> <span m=''2354800''>be</span> <span m=''2354960''>the</span>
  <span m=''2355070''>one</span> <span m=''2355230''>that''s</span> <span m=''2355440''>contiguous.</span>
  <span m=''2356670''>So</span> <span m=''2356810''>you</span> <span m=''2356880''>can</span>
  <span m=''2357060''>do</span> <span m=''2357820''>data</span> <span m=''2358410''>[UNINTELLIGIBLE]</span>
  <span m=''2358980''>transformation</span> <span m=''2359600''>and get</span> <span
  m=''2359890''>there.</span> </p><p><span m=''2363290''>So</span> <span m=''2363790''>now</span>
  <span m=''2364100''>what</span> <span m=''2364290''>happens</span> <span m=''2364650''>is</span>
  <span m=''2366420''>the</span> <span m=''2366690''>role</span> <span m=''2366940''>of</span>
  <span m=''2367480''>core</span> <span m=''2367810''>zero</span> <span m=''2367980''>just</span>
  <span m=''2368120''>gets</span> <span m=''2369130''>contiguous</span> <span m=''2369340''>in</span>
  <span m=''2369460''>memory.</span> <span m=''2370590''>And</span> <span m=''2370780''>core</span>
  <span m=''2371080''>one</span> <span m=''2371210''>gets</span> <span m=''2371340''>contiguous</span>
  <span m=''2371450''>in memory.</span> <span m=''2372370''>So</span> <span m=''2372540''>if</span>
  <span m=''2372690''>you''re</span> <span m=''2372750''>trying</span> <span m=''2372880''>to</span>
  <span m=''2372960''>make</span> <span m=''2373140''>it</span> <span m=''2373240''>contiguous,</span>
  <span m=''2373820''>that''s</span> <span m=''2374030''>great.</span> <span m=''2374600''>So</span>
  <span m=''2374770''>between</span> <span m=''2375090''>padding</span> <span m=''2375550''>and</span>
  <span m=''2375660''>making</span> <span m=''2375910''>things</span> <span m=''2376140''>contiguous,</span>
  <span m=''2377020''>you</span> <span m=''2377150''>can</span> <span m=''2377770''>get</span>
  <span m=''2377930''>good</span> <span m=''2378100''>performance.</span> </p><p><span
  m=''2378840''>And</span> <span m=''2379570''>if</span> <span m=''2379690''>you</span>
  <span m=''2379760''>do</span> <span m=''2379850''>data</span> <span m=''2380040''>transformation,</span>
  <span m=''2381040''>voila!</span> <span m=''2381520''>My</span> <span m=''2382600''>invalidations</span>
  <span m=''2383240''>just</span> <span m=''2383400''>went down</span> <span m=''2383850''>drastically.</span>
  <span m=''2384940''>I</span> <span m=''2385060''>again</span> <span m=''2385440''>have</span>
  <span m=''2386060''>a nice</span> <span m=''2386350''>load</span> <span m=''2386550''>balancing</span>
  <span m=''2387010''>here.</span> <span m=''2387900''>Invalidations</span> <span
  m=''2388635''>went</span> <span m=''2389010''>down</span> <span m=''2389150''>drastically.</span>
  <span m=''2390100''>That</span> <span m=''2390410''>means</span> <span m=''2390940''>my</span>
  <span m=''2391100''>[UNINTELLIGIBLE]</span> <span m=''2391310''>increased</span>
  <span m=''2391830''>a</span> <span m=''2391860''>little</span> <span m=''2392150''>bit</span>
  <span m=''2392810''>and</span> <span m=''2393530''>I</span> <span m=''2393660''>get</span>
  <span m=''2393890''>really</span> <span m=''2394130''>nice</span> <span m=''2394410''>speed</span>
  <span m=''2394510''>up.</span> </p><p><span m=''2396600''>So</span> <span m=''2396840''>here</span>
  <span m=''2397010''>are</span> <span m=''2397180''>the</span> <span m=''2397220''>kind</span>
  <span m=''2397620''>of</span> <span m=''2399550''>crazy</span> <span m=''2399890''>things</span>
  <span m=''2400060''>you</span> <span m=''2400510''>are to do</span> <span m=''2400940''>if</span>
  <span m=''2401180''>you</span> <span m=''2401320''>are</span> <span m=''2401580''>doing</span>
  <span m=''2402510''>things</span> <span m=''2402830''>like</span> <span m=''2404460''>algorithms</span>
  <span m=''2405010''>that</span> <span m=''2405200''>are</span> <span m=''2405310''>not</span>
  <span m=''2406110''>cache</span> <span m=''2406230''>obvious.</span> <span m=''2407100''>And</span>
  <span m=''2407560''>if</span> <span m=''2407710''>you are</span> <span m=''2408220''>doing</span>
  <span m=''2408350''>directly</span> <span m=''2408460''>parallizing</span> <span
  m=''2408560''>yourself without</span> <span m=''2408820''>letting</span> <span m=''2409210''>a</span>
  <span m=''2409320''>nice</span> <span m=''2411740''>[UNINTELLIGIBLE]</span> <span
  m=''2411890''>time</span> <span m=''2412080''>to</span> <span m=''2412390''>help</span>
  <span m=''2412530''>you. Something</span> <span m=''2412790''>like</span> <span
  m=''2412930''>a</span> <span m=''2413415''>[UNINTELLIGIBLE]</span> <span m=''2413900''>assistant.</span>
  </p><p><span m=''2416580''>So</span> <span m=''2418280''>I''m</span> <span m=''2418470''>just</span>
  <span m=''2418610''>going</span> <span m=''2418700''>to</span> <span m=''2418790''>summarize</span>
  <span m=''2419420''>this</span> <span m=''2419710''>because</span> <span m=''2419990''>this</span>
  <span m=''2420200''>is</span> <span m=''2420240''>important.</span> <span m=''2420990''>We</span>
  <span m=''2421430''>looked</span> <span m=''2421730''>at a</span> <span m=''2421780''>bunch</span>
  <span m=''2422050''>of</span> <span m=''2422230''>cache issues.</span> <span m=''2422630''>We</span>
  <span m=''2422720''>looked</span> <span m=''2422910''>at</span> <span m=''2423100''>cold</span>
  <span m=''2423460''>missiles,</span> <span m=''2424200''>capacity</span> <span m=''2424720''>missiles,</span>
  <span m=''2424870''>and</span> <span m=''2425420''>conflict</span> <span m=''2425785''>missiles</span>
  <span m=''2426290''>before.</span> <span m=''2426970''>And</span> <span m=''2427240''>today,</span>
  <span m=''2428190''>here</span> <span m=''2428380''>are</span> <span m=''2428460''>some</span>
  <span m=''2428640''>examples</span> <span m=''2429280''>of</span> <span m=''2429390''>true</span>
  <span m=''2429720''>sharing</span> <span m=''2430070''>missiles.</span> </p><p><span
  m=''2431340''>What</span> <span m=''2431520''>happened</span> <span m=''2431840''>was</span>
  <span m=''2433270''>I am</span> <span m=''2433680''>actually</span> <span m=''2434950''>really</span>
  <span m=''2435190''>using</span> <span m=''2435530''>data,</span> <span m=''2436160''>but</span>
  <span m=''2436600''>I</span> <span m=''2436760''>set</span> <span m=''2436960''>up</span>
  <span m=''2437080''>my</span> <span m=''2437210''>parallelism</span> <span m=''2437880''>in</span>
  <span m=''2438630''>such</span> <span m=''2438870''>a</span> <span m=''2438890''>way</span>
  <span m=''2439140''>that</span> <span m=''2440800''>between</span> <span m=''2441880''>different</span>
  <span m=''2442210''>executions,</span> <span m=''2444010''>my</span> <span m=''2444190''>data</span>
  <span m=''2444570''>has</span> <span m=''2444800''>to</span> <span m=''2444890''>move</span>
  <span m=''2445200''>across.</span> <span m=''2446000''>[UNINTELLIGIBLE]</span> <span
  m=''2447030''>So</span> <span m=''2447150''>I</span> <span m=''2447240''>am</span>
  <span m=''2447470''>truly</span> <span m=''2447770''>sharing</span> <span m=''2449660''>data,</span>
  <span m=''2450110''>but</span> <span m=''2450560''>the</span> <span m=''2450700''>data</span>
  <span m=''2451010''>has to go to</span> <span m=''2451230''>somebody</span> <span
  m=''2451520''>else''s</span> <span m=''2451885''>cache.</span> <span m=''2452250''>So</span>
  <span m=''2452440''>I''ve</span> <span m=''2452540''>got a lot of</span> <span m=''2452710''>[UNINTELLIGIBLE]</span>
  <span m=''2453110''>violations</span> <span m=''2453400''>here.</span> </p><p><span
  m=''2454830''>More</span> <span m=''2455180''>into</span> <span m=''2455470''>this</span>
  <span m=''2455710''>one</span> <span m=''2455940''>is</span> <span m=''2456080''>more</span>
  <span m=''2456480''>like</span> <span m=''2456700''>false</span> <span m=''2457170''>sharing,</span>
  <span m=''2457750''>where</span> <span m=''2458180''>you</span> <span m=''2458420''>assume</span>
  <span m=''2458600''>there''s</span> <span m=''2458810''>no</span> <span m=''2458970''>sharing,</span>
  <span m=''2459460''>nice</span> <span m=''2459770''>parallelism,</span> <span m=''2460420''>everything,</span>
  <span m=''2461240''>except</span> <span m=''2461600''>the</span> <span m=''2461680''>program</span>
  <span m=''2462040''>runs</span> <span m=''2462270''>very</span> <span m=''2462370''>slow.</span>
  <span m=''2463120''>And</span> <span m=''2463890''>that</span> <span m=''2464070''>can</span>
  <span m=''2464230''>be</span> <span m=''2464320''>because</span> <span m=''2464600''>of</span>
  <span m=''2465080''>false</span> <span m=''2465345''>sharing.</span> <span m=''2465610''>So</span>
  <span m=''2466220''>we</span> <span m=''2466340''>just</span> <span m=''2466530''>kind</span>
  <span m=''2466730''>of</span> <span m=''2467240''>touch</span> <span m=''2467500''>on</span>
  <span m=''2467590''>these</span> <span m=''2467780''>two</span> <span m=''2467900''>topics.</span>
  <span m=''2469550''>OK?</span> </p><p><span m=''2470660''>So</span> <span m=''2471530''>let</span>
  <span m=''2471730''>me</span> <span m=''2471930''>switch</span> <span m=''2472210''>gears</span>
  <span m=''2472460''>a</span> <span m=''2472520''>little</span> <span m=''2472790''>bit</span>
  <span m=''2473420''>about</span> <span m=''2473620''>dependences.</span> <span m=''2474340''>We</span>
  <span m=''2474470''>touched</span> <span m=''2474700''>on</span> <span m=''2474975''>the</span>
  <span m=''2475250''>dependences</span> <span m=''2475515''>a</span> <span m=''2475780''>little</span>
  <span m=''2475880''>bit.</span> <span m=''2476380''>And</span> <span m=''2476550''>these</span>
  <span m=''2476730''>are</span> <span m=''2477330''>two</span> <span m=''2477550''>fine</span>
  <span m=''2477980''>programs</span> <span m=''2478520''>that</span> <span m=''2478950''>are
  not</span> <span m=''2479070''>completely</span> <span m=''2479500''>parallel.</span>
  <span m=''2480410''>So</span> <span m=''2480650''>normally,</span> <span m=''2481080''>what</span>
  <span m=''2481220''>happens</span> <span m=''2481610''>is</span> <span m=''2482390''>a
  true</span> <span m=''2482480''>dependence</span> <span m=''2483040''>means</span>
  <span m=''2483840''>that</span> <span m=''2484510''>I''m</span> <span m=''2484710''>writing</span>
  <span m=''2485130''>and</span> <span m=''2485230''>reading</span> <span m=''2485570''>[UNINTELLIGIBLE]</span>
  <span m=''2486570''>other</span> <span m=''2486810''>way</span> <span m=''2487100''>out.</span>
  <span m=''2487660''>And</span> <span m=''2487850''>if</span> <span m=''2488080''>two</span>
  <span m=''2488250''>guys</span> <span m=''2488600''>are</span> <span m=''2488700''>both</span>
  <span m=''2489020''>fighting,</span> <span m=''2489290''>then</span> <span m=''2489440''>the</span>
  <span m=''2489910''>order</span> <span m=''2490060''>has</span> <span m=''2490400''>to
  maintiain</span> <span m=''2490480''>us</span> <span m=''2490590''>out</span> <span
  m=''2490800''>would</span> <span m=''2491295''>be dependence.</span> </p><p><span
  m=''2492780''>And</span> <span m=''2496220''>did</span> <span m=''2496420''>our</span>
  <span m=''2496780''>dependence</span> <span m=''2496970''>even</span> <span m=''2497030''>loop,</span>
  <span m=''2498300''>because</span> <span m=''2498650''>these</span> <span m=''2498810''>are</span>
  <span m=''2499570''>single</span> <span m=''2500530''>items.</span> <span m=''2500880''>So</span>
  <span m=''2500990''>if</span> <span m=''2501210''>you</span> <span m=''2501440''>have
  an</span> <span m=''2501650''>error</span> <span m=''2501980''>here,</span> <span
  m=''2502540''>this</span> <span m=''2502760''>is</span> <span m=''2503040''>becoming</span>
  <span m=''2503400''>a lot</span> <span m=''2503600''>more</span> <span m=''2503760''>complicated.</span>
  <span m=''2504600''>Because</span> <span m=''2504850''>there''s</span> <span m=''2505100''>no</span>
  <span m=''2505250''>simple</span> <span m=''2505490''>thing</span> <span m=''2505610''>in
  here.</span> <span m=''2506200''>Because</span> <span m=''2506430''>it''s</span>
  <span m=''2506540''>not</span> <span m=''2506720''>just</span> <span m=''2506910''>using</span>
  <span m=''2507280''>the</span> <span m=''2507400''>same</span> <span m=''2507690''>iteration.</span>
  <span m=''2508450''>You</span> <span m=''2508570''>might</span> <span m=''2508770''>be</span>
  <span m=''2508870''>using</span> <span m=''2509240''>data</span> <span m=''2509500''>from</span>
  <span m=''2509720''>different</span> <span m=''2510170''>iterations.</span> <span
  m=''2511910''>So</span> <span m=''2512060''>what</span> <span m=''2512290''>happens</span>
  <span m=''2512700''>is</span> <span m=''2514470''>there''s</span> <span m=''2514690''>a</span>
  <span m=''2514740''>dynamic</span> <span m=''2515310''>instance</span> <span m=''2515780''>of</span>
  <span m=''2515920''>iterations.</span> <span m=''2516840''>So</span> <span m=''2517000''>one</span>
  <span m=''2517300''>iteration</span> <span m=''2517770''>writes</span> <span m=''2518050''>the</span>
  <span m=''2518130''>data,</span> <span m=''2518370''>and</span> <span m=''2518490''>somebody</span>
  <span m=''2518850''>else</span> <span m=''2519050''>might</span> <span m=''2519230''>be</span>
  <span m=''2519490''>reading</span> <span m=''2519640''>the</span> <span m=''2519730''>data.</span>
  </p><p><span m=''2521310''>And</span> <span m=''2521560''>that is</span> <span m=''2522010''>basically</span>
  <span m=''2522830''>the</span> <span m=''2522930''>order</span> <span m=''2523180''>we</span>
  <span m=''2523280''>have</span> <span m=''2523380''>to</span> <span m=''2523490''>[UNINTELLIGIBLE].</span>
  <span m=''2523990''>Let me give you an</span> <span m=''2524340''>example.</span>
  <span m=''2525060''>This</span> <span m=''2525250''>kind</span> <span m=''2525360''>of</span>
  <span m=''2525480''>demonstrates</span> <span m=''2525900''>what''s</span> <span
  m=''2526080''>going</span> <span m=''2526290''>on.</span> <span m=''2527580''>OK?</span>
  <span m=''2528170''>And</span> <span m=''2528620''>when</span> <span m=''2528880''>you</span>
  <span m=''2529070''>edit,</span> <span m=''2529210''>you say</span> <span m=''2529440''>look,</span>
  <span m=''2529690''>this</span> <span m=''2530070''>is</span> <span m=''2530200''>where</span>
  <span m=''2530310''>you</span> <span m=''2530500''>[UNINTELLIGIBLE]</span> <span
  m=''2530910''>complicated.</span> </p><p><span m=''2532590''>So</span> <span m=''2532770''>in</span>
  <span m=''2532890''>order</span> <span m=''2533100''>to</span> <span m=''2533140''>give</span>
  <span m=''2533260''>you and</span> <span m=''2533330''>example,</span> <span m=''2533890''>let</span>
  <span m=''2534130''>me</span> <span m=''2534380''>look</span> <span m=''2534500''>at</span>
  <span m=''2534630''>this</span> <span m=''2534790''>program.</span> <span m=''2535876''>I
  have a</span> <span m=''2536260''>simple</span> <span m=''2536580''>program</span>
  <span m=''2536865''>here.</span> <span m=''2537150''>Ai</span> <span m=''2537400''>equals</span>
  <span m=''2537710''>Ai</span> <span m=''2538340''>plus</span> <span m=''2538590''>one.</span>
  <span m=''2539210''>My</span> <span m=''2539520''>iterations--</span> <span m=''2539990''>I''m</span>
  <span m=''2540250''>running</span> <span m=''2540480''>five</span> <span m=''2540780''>iterations</span>
  <span m=''2541240''>in</span> <span m=''2541370''>here.</span> <span m=''2541570''>So</span>
  <span m=''2541790''>this is</span> <span m=''2542010''>my iteration</span> <span
  m=''2542560''>space.</span> <span m=''2543420''>I</span> <span m=''2543590''>have</span>
  <span m=''2543780''>a</span> <span m=''2543840''>large</span> <span m=''2544170''>array,</span>
  <span m=''2544480''>so</span> <span m=''2544570''>this</span> <span m=''2544690''>is</span>
  <span m=''2544820''>my</span> <span m=''2544930''>data</span> <span m=''2545200''>space.</span>
  </p><p><span m=''2548090''>And</span> <span m=''2548340''>now,</span> <span m=''2548780''>I</span>
  <span m=''2548900''>keep</span> <span m=''2549170''>running</span> <span m=''2549440''>this</span>
  <span m=''2549620''>program.</span> <span m=''2549990''>So</span> <span m=''2550110''>what</span>
  <span m=''2550370''>happens</span> <span m=''2550760''>is</span> <span m=''2550900''>this</span>
  <span m=''2551080''>is</span> <span m=''2551270''>time</span> <span m=''2551540''>going</span>
  <span m=''2551800''>down</span> <span m=''2552170''>in here.</span> <span m=''2552800''>So</span>
  <span m=''2553180''>the</span> <span m=''2553260''>first</span> <span m=''2553510''>situation</span>
  <span m=''2554250''>basically,</span> <span m=''2554660''>I</span> <span m=''2554760''>first</span>
  <span m=''2555070''>read</span> <span m=''2555820''>and</span> <span m=''2555930''>then</span>
  <span m=''2556040''>write.</span> <span m=''2556560''>Same in</span> <span m=''2556800''>the</span>
  <span m=''2556990''>second</span> <span m=''2557310''>iteration,</span> <span m=''2558220''>I</span>
  <span m=''2558430''>read</span> <span m=''2558780''>and</span> <span m=''2558900''>write.</span>
  <span m=''2559350''>Third</span> <span m=''2559590''>iteration</span> <span m=''2560070''>read</span>
  <span m=''2560260''>and</span> <span m=''2560440''>write.</span> <span m=''2560700''>Fourth</span>
  <span m=''2560860''>iteration,</span> <span m=''2561460''>read and</span> <span
  m=''2561660''>write.</span> </p><p><span m=''2562770''>Do you</span> <span m=''2562930''>see</span>
  <span m=''2563040''>how</span> <span m=''2563180''>this</span> <span m=''2563310''>is</span>
  <span m=''2563440''>going</span> <span m=''2563700''>on</span> <span m=''2563800''>these</span>
  <span m=''2563990''>four</span> <span m=''2564040''>situations?</span> <span m=''2564610''>Second</span>
  <span m=''2564910''>iteration,</span> <span m=''2565080''>third</span> <span m=''2565210''>iteration,</span>
  <span m=''2565780''>fourth</span> <span m=''2565910''>iteration,</span> <span m=''2566050''>[UNINTELLIGIBLE].</span>
  <span m=''2568115''>OK.</span> <span m=''2568580''>So</span> <span m=''2568710''>what</span>
  <span m=''2568900''>happens</span> <span m=''2569300''>is</span> <span m=''2569500''>first</span>
  <span m=''2569800''>iteration</span> <span m=''2570370''>read</span> <span m=''2570710''>this</span>
  <span m=''2570900''>value</span> <span m=''2572650''>is</span> <span m=''2572915''>zero.</span>
  <span m=''2573810''>And write</span> <span m=''2574050''>the</span> <span m=''2574130''>value</span>
  <span m=''2574350''>as</span> <span m=''2574540''>zero</span> <span m=''2575130''>in</span>
  <span m=''2575230''>the</span> <span m=''2575320''>menu</span> <span m=''2575745''>writing.</span>
  <span m=''2576170''>Second</span> <span m=''2576580''>iteration</span> <span m=''2577010''>A1,</span>
  <span m=''2577760''>A1,</span> <span m=''2578590''>A2,</span> <span m=''2578810''>A2,</span>
  <span m=''2578950''>A3,</span> <span m=''2579120''>A3.</span> </p><p><span m=''2580930''>So</span>
  <span m=''2581180''>now,</span> <span m=''2582375''>when</span> <span m=''2582680''>this</span>
  <span m=''2582800''>is</span> <span m=''2583950''>writing,</span> <span m=''2586460''>that''s</span>
  <span m=''2586740''>a</span> <span m=''2586800''>dependence</span> <span m=''2587290''>between</span>
  <span m=''2587610''>these</span> <span m=''2587820''>two.</span> <span m=''2588160''>You</span>
  <span m=''2588300''>see</span> <span m=''2588410''>the</span> <span m=''2588580''>true</span>
  <span m=''2588970''>and</span> <span m=''2589200''>entire</span> <span m=''2589430''>output</span>
  <span m=''2589800''>dependence</span> <span m=''2590150''>between</span> <span m=''2590270''>these</span>
  <span m=''2590380''>two.</span> </p><p><span m=''2595545''>What</span> <span m=''2595720''>type</span>
  <span m=''2595860''>of</span> <span m=''2596120''>dependence</span> <span m=''2596240''>do</span>
  <span m=''2596520''>we have?</span> <span m=''2598270''>[UNINTELLIGIBLE]</span>
  <span m=''2598390''>dependence.</span> <span m=''2604240''>True</span> <span m=''2604690''>dependence
  is</span> <span m=''2605045''>what?</span> <span m=''2606340''>What</span> <span
  m=''2606670''>to</span> <span m=''2606820''>what?</span> <span m=''2608780''>What''s</span>
  <span m=''2608920''>the</span> <span m=''2609060''>first</span> <span m=''2609330''>thing</span>
  <span m=''2609550''>that</span> <span m=''2609750''>occurs?</span> <span m=''2609940''>What''s</span>
  <span m=''2610150''>the</span> <span m=''2610260''>next</span> <span m=''2610380''>thing</span>
  <span m=''2610520''>that</span> <span m=''2610962''>occurs?</span> <span m=''2613620''>Anybody</span>
  <span m=''2614020''>want</span> <span m=''2614200''>to</span> <span m=''2614390''>answer?</span>
  </p><p><span m=''2620820''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''2623140''>PROFESSOR:
  Write to read.</span> <span m=''2623900''>So</span> <span m=''2624150''>you have
  the</span> <span m=''2624330''>first</span> <span m=''2624520''>thing</span> <span
  m=''2624680''>has</span> <span m=''2624770''>to</span> <span m=''2624950''>be</span>
  <span m=''2625170''>write</span> <span m=''2625445''>to read.</span> <span m=''2625720''>Watch</span>
  <span m=''2625970''>this.</span> <span m=''2626570''>This is</span> <span m=''2626730''>a</span>
  <span m=''2627100''>read</span> <span m=''2627470''>to</span> <span m=''2628430''>write.</span>
  <span m=''2628800''>So</span> <span m=''2628930''>what</span> <span m=''2629110''>type</span>
  <span m=''2629260''>of</span> <span m=''2629350''>dependence</span> <span m=''2629635''>is</span>
  <span m=''2629920''>this?</span> <span m=''2631230''>This is</span> <span m=''2631450''>anti-dependent.</span>
  <span m=''2632240''>So</span> <span m=''2632410''>here is</span> <span m=''2632670''>ante-dependence</span>
  <span m=''2633380''>in</span> <span m=''2633500''>here.</span> </p><p><span m=''2634680''>But</span>
  <span m=''2634940''>the</span> <span m=''2635030''>nice</span> <span m=''2635370''>thing</span>
  <span m=''2635490''>about</span> <span m=''2635710''>that</span> <span m=''2635980''>is</span>
  <span m=''2636220''>this</span> <span m=''2636410''>dependent</span> <span m=''2636990''>didn''t</span>
  <span m=''2637360''>cross</span> <span m=''2637710''>the</span> <span m=''2637790''>iteration</span>
  <span m=''2638310''>boundary.</span> <span m=''2638940''>So</span> <span m=''2639100''>these</span>
  <span m=''2639340''>black</span> <span m=''2639690''>lines</span> <span m=''2639930''>are</span>
  <span m=''2640150''>my iteration</span> <span m=''2640670''>boundaries.</span> <span
  m=''2641050''>So</span> <span m=''2641180''>these</span> <span m=''2641380''>are</span>
  <span m=''2641520''>for</span> <span m=''2641710''>situations</span> <span m=''2642200''>that</span>
  <span m=''2642350''>[UNINTELLIGIBLE].</span> <span m=''2643190''>So</span> <span
  m=''2643690''>there''s</span> <span m=''2643960''>no iteration</span> <span m=''2644470''>crossing</span>
  <span m=''2644950''>in</span> <span m=''2645430''>here.</span> </p><p><span m=''2646780''>You</span>
  <span m=''2646960''>can</span> <span m=''2647150''>kind</span> <span m=''2647370''>of</span>
  <span m=''2647520''>[UNINTELLIGIBLE]</span> <span m=''2647850''>it</span> <span
  m=''2648500''>using</span> <span m=''2648950''>each</span> <span m=''2649360''>of</span>
  <span m=''2649830''>these</span> <span m=''2650050''>iterations</span> <span m=''2651170''>and</span>
  <span m=''2651460''>my</span> <span m=''2652740''>dependencies</span> <span m=''2652900''>within</span>
  <span m=''2653190''>the</span> <span m=''2653400''>very</span> <span m=''2653590''>same</span>
  <span m=''2653860''>iteration.</span> <span m=''2654360''>So the</span> <span m=''2654560''>same</span>
  <span m=''2654830''>iteration</span> <span m=''2655290''>I</span> <span m=''2655390''>have</span>
  <span m=''2655500''>dependency</span> <span m=''2655860''>[UNINTELLIGIBLE].</span>
  <span m=''2658116''>OK?</span> <span m=''2658590''>This</span> <span m=''2658770''>is</span>
  <span m=''2658910''>a simpler</span> <span m=''2659190''>case.</span> </p><p><span
  m=''2659910''>So</span> <span m=''2660100''>let''s</span> <span m=''2660330''>look</span>
  <span m=''2660500''>at</span> <span m=''2660600''>something</span> <span m=''2661060''>a
  little</span> <span m=''2661100''>bit</span> <span m=''2661270''>more</span> <span
  m=''2661430''>complicated.</span> <span m=''2664060''>So</span> <span m=''2664220''>I</span>
  <span m=''2664310''>have</span> <span m=''2664915''>Ai</span> <span m=''2665250''>plus</span>
  <span m=''2665640''>1</span> <span m=''2665980''>equals</span> <span m=''2666550''>Ai</span>
  <span m=''2667300''>plus</span> <span m=''2667520''>1.</span> <span m=''2668560''>So</span>
  <span m=''2668760''>what</span> <span m=''2668950''>happens</span> <span m=''2669290''>is</span>
  <span m=''2669430''>first</span> <span m=''2669680''>I am</span> <span m=''2669930''>reading</span>
  <span m=''2670280''>Ai.</span> <span m=''2672430''>And</span> <span m=''2672670''>then,</span>
  <span m=''2672850''>I am</span> <span m=''2673070''>writing</span> <span m=''2673380''>Ai</span>
  <span m=''2673930''>plus</span> <span m=''2674250''>1</span> <span m=''2677940''>in</span>
  <span m=''2678030''>the</span> <span m=''2678130''>same</span> <span m=''2678560''>iteration.</span>
  </p><p><span m=''2679270''>The</span> <span m=''2679380''>next</span> <span m=''2679500''>iteration,</span>
  <span m=''2680070''>I am</span> <span m=''2680390''>reading</span> <span m=''2680660''>now</span>
  <span m=''2680890''>Ai</span> <span m=''2681100''>[UNINTELLIGIBLE]</span> <span
  m=''2682050''>this</span> <span m=''2682390''>is</span> <span m=''2682570''>A0</span>
  <span m=''2683480''>and</span> <span m=''2683650''>1.</span> <span m=''2684250''>This
  is</span> <span m=''2684750''>A</span> <span m=''2684920''>is</span> <span m=''2685070''>1.</span>
  <span m=''2685890''>[UNINTELLIGIBLE]</span> <span m=''2686410''>I am</span> <span
  m=''2686640''>writing</span> <span m=''2687340''>Ai</span> <span m=''2687430''>plus</span>
  <span m=''2687720''>1.</span> <span m=''2687880''>I am</span> <span m=''2688010''>writing</span>
  <span m=''2688320''>2.</span> <span m=''2691610''>So</span> <span m=''2691780''>I</span>
  <span m=''2691950''>have</span> <span m=''2692130''>a</span> <span m=''2692200''>dependence</span>
  <span m=''2692540''>like</span> <span m=''2692710''>this</span> <span m=''2692930''>now.</span>
  <span m=''2694070''>What</span> <span m=''2694280''>type</span> <span m=''2694500''>of</span>
  <span m=''2694720''>dependence</span> <span m=''2694990''>is this?</span> <span
  m=''2698190''>This</span> <span m=''2698440''>is</span> <span m=''2698550''>a</span>
  <span m=''2698640''>true</span> <span m=''2698780''>dependence</span> <span m=''2699340''>because</span>
  <span m=''2699750''>I</span> <span m=''2699900''>am</span> <span m=''2700080''>writing.</span>
  <span m=''2700560''>And</span> <span m=''2700690''>this</span> <span m=''2700810''>is</span>
  <span m=''2700910''>actually</span> <span m=''2701110''>reading</span> <span m=''2701460''>what</span>
  <span m=''2701690''>what it is</span> <span m=''2701900''>writing.</span> </p><p><span
  m=''2704610''>So</span> <span m=''2705560''>does</span> <span m=''2705770''>this</span>
  <span m=''2705970''>look</span> <span m=''2706200''>parallel?</span> <span m=''2708720''>No.</span>
  <span m=''2709590''>Because</span> <span m=''2709970''>what</span> <span m=''2710220''>happens</span>
  <span m=''2710530''>is</span> <span m=''2710640''>if</span> <span m=''2710750''>you</span>
  <span m=''2710840''>look</span> <span m=''2711020''>at</span> <span m=''2711940''>each</span>
  <span m=''2712580''>iteration</span> <span m=''2713440''>depends</span> <span m=''2713790''>on</span>
  <span m=''2713850''>the</span> <span m=''2713940''>previous</span> <span m=''2714280''>iteration.</span>
  <span m=''2715680''>So</span> <span m=''2715890''>you</span> <span m=''2716070''>have</span>
  <span m=''2716250''>to</span> <span m=''2716340''>actually</span> <span m=''2716630''>have</span>
  <span m=''2716810''>this</span> <span m=''2717000''>dependence</span> <span m=''2717460''>going</span>
  <span m=''2717690''>back</span> <span m=''2717920''>and</span> <span m=''2718040''>forth,</span>
  <span m=''2718180''>back</span> <span m=''2718380''>and</span> <span m=''2718500''>forth</span>
  <span m=''2718690''>in</span> <span m=''2718810''>here.</span> </p><p><span m=''2720890''>So</span>
  <span m=''2721900''>let''s</span> <span m=''2722090''>look</span> <span m=''2722230''>at
  a</span> <span m=''2722370''>couple</span> <span m=''2722630''>more</span> <span
  m=''2722850''>other</span> <span m=''2723080''>things.</span> <span m=''2723550''>So</span>
  <span m=''2723730''>here is</span> <span m=''2723950''>Ai</span> <span m=''2724180''>equals</span>
  <span m=''2725270''>Ai</span> <span m=''2725360''>plus</span> <span m=''2725730''>2.</span>
  <span m=''2726830''>So</span> <span m=''2727390''>I</span> <span m=''2727570''>am</span>
  <span m=''2727840''>basically</span> <span m=''2728220''>reading</span> <span m=''2728710''>Ai</span>
  <span m=''2728810''>plus</span> <span m=''2729160''>2.</span> <span m=''2730660''>So</span>
  <span m=''2730920''>I am</span> <span m=''2731170''>reading this</span> <span m=''2731440''>one.</span>
  <span m=''2731670''>I am</span> <span m=''2731850''>writing</span> <span m=''2732160''>this</span>
  <span m=''2732360''>one.</span> <span m=''2733220''>Reading</span> <span m=''2733450''>this</span>
  <span m=''2733660''>one.</span> <span m=''2733810''>Writing</span> <span m=''2734010''>this</span>
  <span m=''2734290''>one.</span> <span m=''2736060''>Here is</span> <span m=''2736310''>my</span>
  <span m=''2736420''>dependence</span> <span m=''2736680''>that''s</span> <span m=''2736940''>in</span>
  <span m=''2737060''>here.</span> <span m=''2738040''>You</span> <span m=''2738120''>see</span>
  <span m=''2738240''>the</span> <span m=''2738460''>two</span> <span m=''2738850''>are</span>
  <span m=''2739020''>anti in</span> <span m=''2739370''>here.</span> <span m=''2742210''>This</span>
  <span m=''2742390''>is anti-dependence</span> <span m=''2743200''>because</span>
  <span m=''2743450''>I am</span> <span m=''2743600''>going</span> <span m=''2743850''>from</span>
  <span m=''2744020''>a</span> <span m=''2744150''>reading</span> <span m=''2745180''>to</span>
  <span m=''2745260''>a</span> <span m=''2745340''>write</span> <span m=''2745610''>in</span>
  <span m=''2745820''>here.</span> </p><p><span m=''2747160''>Can</span> <span m=''2747370''>this</span>
  <span m=''2747540''>loop</span> <span m=''2747820''>be</span> <span m=''2748030''>parallel?</span>
  <span m=''2755240''>Can</span> <span m=''2755360''>this loop</span> <span m=''2755450''>run
  parallel?</span> </p><p><span m=''2757744''>AUDIENCE: [INAUDIBLE]</span> </p><p><span
  m=''2760440''>PROFESSOR: So</span> <span m=''2761610''>can</span> <span m=''2762000''>every
  iteration</span> <span m=''2762670''>run</span> <span m=''2762880''>parallel?</span>
  <span m=''2764090''>There</span> <span m=''2764340''>could</span> <span m=''2764470''>be</span>
  <span m=''2764590''>basically.</span> <span m=''2765030''>No</span> <span m=''2765300''>because</span>
  <span m=''2765710''>what</span> <span m=''2765890''>happens</span> <span m=''2766220''>is
  if</span> <span m=''2766400''>you</span> <span m=''2766490''>look</span> <span m=''2766660''>at</span>
  <span m=''2766840''>that,</span> <span m=''2767340''>there''s</span> <span m=''2767530''>a</span>
  <span m=''2767590''>dependence</span> <span m=''2768060''>that</span> <span m=''2768210''>goes</span>
  <span m=''2768480''>like</span> <span m=''2768670''>this.</span> <span m=''2769690''>And</span>
  <span m=''2769920''>of</span> <span m=''2770090''>course,</span> <span m=''2770260''>there</span>
  <span m=''2770390''>are</span> <span m=''2770520''>two</span> <span m=''2770630''>chains.</span>
  <span m=''2771060''>So</span> <span m=''2772090''>if you are</span> <span m=''2772450''>interested,</span>
  <span m=''2772860''>you</span> <span m=''2773010''>can</span> <span m=''2773170''>run</span>
  <span m=''2773850''>at least</span> <span m=''2773990''>two-way</span> <span m=''2774170''>parallelism.</span>
  <span m=''2775210''>You</span> <span m=''2775320''>can</span> <span m=''2775460''>run</span>
  <span m=''2775680''>one</span> <span m=''2775950''>chain</span> <span m=''2776990''>parallel</span>
  <span m=''2777460''>to another</span> <span m=''2777660''>chain</span> <span m=''2777850''>when</span>
  <span m=''2777980''>you do</span> <span m=''2778200''>get</span> <span m=''2778330''>that</span>
  <span m=''2778480''>much</span> <span m=''2778660''>parallelism.</span> </p><p><span
  m=''2781130''>How</span> <span m=''2781290''>about</span> <span m=''2781480''>this</span>
  <span m=''2781670''>one?</span> <span m=''2784740''>2i</span> <span m=''2785860''>and</span>
  <span m=''2786080''>2i</span> <span m=''2786440''>plus</span> <span m=''2786590''>1.</span>
  <span m=''2786970''>[UNINTELLIGIBLE]</span> <span m=''2789890''>Is</span> <span
  m=''2790030''>there</span> <span m=''2790160''>independence</span> <span m=''2790425''>in</span>
  <span m=''2790690''>here?</span> <span m=''2794740''>Nope</span> <span m=''2795080''>because</span>
  <span m=''2795350''>one</span> <span m=''2795570''>is--</span> <span m=''2796120''>you</span>
  <span m=''2796260''>are</span> <span m=''2796650''>reading</span> <span m=''2797000''>all
  the</span> <span m=''2797280''>elements</span> <span m=''2797610''>and</span> <span
  m=''2797780''>even writing</span> <span m=''2798300''>elements</span> <span m=''2798610''>[UNINTELLIGIBLE]</span>
  <span m=''2799210''>dependence.</span> <span m=''2799730''>So</span> <span m=''2799900''>you</span>
  <span m=''2800020''>can</span> <span m=''2800170''>have</span> <span m=''2800390''>a</span>
  <span m=''2800500''>missing</span> <span m=''2800660''>parallel.</span> <span m=''2802100''>OK?</span>
  </p><p><span m=''2803230''>So</span> <span m=''2803390''>this</span> <span m=''2803590''>is</span>
  <span m=''2803980''>the</span> <span m=''2804090''>kind</span> <span m=''2804390''>of</span>
  <span m=''2805640''>interesting</span> <span m=''2806060''>thing</span> <span m=''2806210''>that
  is</span> <span m=''2806390''>going</span> <span m=''2806650''>on.</span> <span
  m=''2806890''>So</span> <span m=''2807600''>next,</span> <span m=''2808060''>I</span>
  <span m=''2808180''>want</span> <span m=''2808560''>to</span> <span m=''2809260''>look</span>
  <span m=''2809510''>at</span> <span m=''2810110''>something</span> <span m=''2810710''>a
  little bit</span> <span m=''2811000''>more</span> <span m=''2811150''>complicated.</span>
  <span m=''2812130''>So</span> <span m=''2812320''>let''s</span> <span m=''2812560''>look</span>
  <span m=''2812720''>at</span> <span m=''2812890''>this.</span> </p><p><span m=''2814400''>So</span>
  <span m=''2815030''>here''s</span> <span m=''2815490''>a</span> <span m=''2815800''>classic</span>
  <span m=''2816820''>algorithm</span> <span m=''2817400''>called</span> <span m=''2819010''>successive</span>
  <span m=''2819380''>over</span> <span m=''2819850''>relaxation.</span> <span m=''2821320''>So</span>
  <span m=''2821590''>it</span> <span m=''2821850''>kind</span> <span m=''2822060''>of</span>
  <span m=''2822400''>simulates</span> <span m=''2822960''>a</span> <span m=''2823310''>lot</span>
  <span m=''2823440''>of</span> <span m=''2823580''>times</span> <span m=''2823800''>things</span>
  <span m=''2824050''>like</span> <span m=''2824130''>heat</span> <span m=''2824800''>flow</span>
  <span m=''2825050''>through</span> <span m=''2825270''>a</span> <span m=''2825360''>plane.</span>
  <span m=''2826460''>So</span> <span m=''2826610''>the</span> <span m=''2826690''>idea</span>
  <span m=''2827020''>there</span> <span m=''2827270''>is--</span> <span m=''2828830''>let</span>
  <span m=''2829110''>me</span> <span m=''2829520''>illustrate</span> <span m=''2830010''>what</span>
  <span m=''2830150''>he</span> <span m=''2830270''>does.</span> </p><p><span m=''2830500''>So
  assume</span> <span m=''2832250''>you</span> <span m=''2832430''>have</span> <span
  m=''2834485''>a</span> <span m=''2834960''>big</span> <span m=''2835390''>metal</span>
  <span m=''2835950''>sheet.</span> <span m=''2836750''>And</span> <span m=''2836990''>you</span>
  <span m=''2837130''>put</span> <span m=''2838630''>some</span> <span m=''2838790''>kind</span>
  <span m=''2838960''>of</span> <span m=''2839020''>heat</span> <span m=''2839260''>source</span>
  <span m=''2839490''>in</span> <span m=''2839980''>one</span> <span m=''2840200''>place.</span>
  <span m=''2840790''>And</span> <span m=''2840960''>after</span> <span m=''2841270''>sometime,</span>
  <span m=''2841720''>it</span> <span m=''2842220''>all</span> <span m=''2842660''>reaches</span>
  <span m=''2842910''>a</span> <span m=''2843150''>steady state.</span> <span m=''2843640''>The</span>
  <span m=''2843770''>other</span> <span m=''2844000''>side</span> <span m=''2844290''>might</span>
  <span m=''2844440''>be</span> <span m=''2844580''>cold.</span> <span m=''2844920''>And
  you want to know</span> <span m=''2847090''>part of</span> <span m=''2847260''>the</span>
  <span m=''2847420''>sheet''s</span> <span m=''2847805''>temperature.</span> </p><p><span
  m=''2851070''>Because</span> <span m=''2852110''>temperature</span> <span m=''2852820''>can</span>
  <span m=''2853100''>leak</span> <span m=''2853380''>out.</span> <span m=''2854700''>And</span>
  <span m=''2855070''>there</span> <span m=''2855600''>are</span> <span m=''2858290''>more</span>
  <span m=''2858530''>things</span> <span m=''2858790''>like</span> <span m=''2859440''>you</span>
  <span m=''2859670''>have a heat</span> <span m=''2859970''>source</span> <span m=''2860310''>and
  others</span> <span m=''2860720''>that</span> <span m=''2860800''>[UNINTELLIGIBLE]</span>
  <span m=''2861130''>to</span> <span m=''2861230''>work</span> <span m=''2861720''>a</span>
  <span m=''2862270''>glass</span> <span m=''2862490''>of</span> <span m=''2862640''>water</span>
  <span m=''2862910''>or</span> <span m=''2864480''>some</span> <span m=''2864690''>kind</span>
  <span m=''2864870''>of</span> <span m=''2865000''>a sink.</span> <span m=''2865300''>So</span>
  <span m=''2865480''>what</span> <span m=''2865710''>is</span> <span m=''2865830''>the</span>
  <span m=''2865890''>heat</span> <span m=''2866160''>distribution?</span> </p><p><span
  m=''2867650''>So</span> <span m=''2868200''>one</span> <span m=''2868610''>way</span>
  <span m=''2868710''>to</span> <span m=''2868820''>compare</span> <span m=''2869140''>that</span>
  <span m=''2869430''>this</span> <span m=''2869720''>is</span> <span m=''2870110''>basically</span>
  <span m=''2870440''>the</span> <span m=''2870690''>same</span> <span m=''2871120''>[UNINTELLIGIBLE].</span>
  <span m=''2871550''>The</span> <span m=''2871660''>heat</span> <span m=''2872140''>value</span>
  <span m=''2872320''>here</span> <span m=''2872830''>is</span> <span m=''2873170''>basically</span>
  <span m=''2873920''>the</span> <span m=''2874200''>average</span> <span m=''2874970''>around</span>
  <span m=''2875230''>all</span> <span m=''2875530''>these</span> <span m=''2875710''>other</span>
  <span m=''2875890''>values</span> <span m=''2876310''>right</span> <span m=''2876776''>now.</span>
  <span m=''2879690''>Because</span> <span m=''2879980''>if</span> <span m=''2880090''>something</span>
  <span m=''2880380''>is</span> <span m=''2880480''>too</span> <span m=''2880590''>hot,</span>
  <span m=''2881170''>the</span> <span m=''2881360''>heat is</span> <span m=''2881540''>going
  to</span> <span m=''2881700''>propagate</span> <span m=''2882180''>something</span>
  <span m=''2882310''>that</span> <span m=''2882440''>is too</span> <span m=''2882570''>cold.</span>
  <span m=''2883040''>The</span> <span m=''2883140''>heat is</span> <span m=''2883300''>going
  to</span> <span m=''2883440''>propagate</span> <span m=''2883820''>because</span>
  <span m=''2884100''>it</span> <span m=''2884250''>kind</span> <span m=''2884440''>of</span>
  <span m=''2884490''>has</span> <span m=''2884630''>to</span> <span m=''2884720''>be</span>
  <span m=''2884800''>average</span> <span m=''2884980''>around</span> <span m=''2885110''>that.</span>
  </p><p><span m=''2886820''>Then, you</span> <span m=''2886940''>take</span> <span
  m=''2887120''>the</span> <span m=''2887310''>average</span> <span m=''2887510''>in</span>
  <span m=''2887710''>here.</span> <span m=''2887840''>So</span> <span m=''2887980''>what</span>
  <span m=''2888180''>it''s</span> <span m=''2888330''>doing</span> <span m=''2888660''>is</span>
  <span m=''2888790''>calculating</span> <span m=''2889260''>the</span> <span m=''2889430''>average</span>
  <span m=''2890030''>in</span> <span m=''2890210''>here.</span> <span m=''2891200''>And</span>
  <span m=''2891400''>then,</span> <span m=''2891510''>you have</span> <span m=''2891960''>to
  do</span> <span m=''2892020''>it many,</span> <span m=''2892240''>many</span> <span
  m=''2892470''>times.</span> <span m=''2892810''>So</span> <span m=''2893030''>if
  you have</span> <span m=''2893320''>a</span> <span m=''2893380''>heat</span> <span
  m=''2893610''>source,</span> <span m=''2893850''>at</span> <span m=''2893980''>that</span>
  <span m=''2894210''>point,</span> <span m=''2894390''>it</span> <span m=''2894480''>would</span>
  <span m=''2894600''>be</span> <span m=''2894670''>very</span> <span m=''2894960''>hard.</span>
  <span m=''2895300''>And</span> <span m=''2895480''>then,</span> <span m=''2895580''>it
  will</span> <span m=''2895810''>start</span> <span m=''2896140''>propagating</span>
  <span m=''2896610''>slowly</span> <span m=''2897070''>and</span> <span m=''2897220''>kind</span>
  <span m=''2897450''>of</span> <span m=''2897790''>propagate</span> <span m=''2898240''>down.</span>
  </p><p><span m=''2898810''>And</span> <span m=''2899230''>the</span> <span m=''2899460''>cold
  side</span> <span m=''2899690''>in</span> <span m=''2899860''>this way</span> <span
  m=''2900040''>or</span> <span m=''2900270''>after</span> <span m=''2901050''>running</span>
  <span m=''2901310''>many</span> <span m=''2901560''>times,</span> <span m=''2901890''>it
  basically</span> <span m=''2902230''>stabilizes.</span> <span m=''2903180''>And</span>
  <span m=''2903310''>at</span> <span m=''2903440''>that</span> <span m=''2903640''>point,</span>
  <span m=''2903880''>you</span> <span m=''2903990''>have</span> <span m=''2904580''>the
  kind of heat</span> <span m=''2904710''>distribution</span> <span m=''2905350''>that</span>
  <span m=''2905820''>we</span> <span m=''2905900''>[UNINTELLIGIBLE]</span> <span
  m=''2906030''>have.</span> <span m=''2906180''>This is</span> <span m=''2906260''>the</span>
  <span m=''2906360''>kind</span> <span m=''2906550''>of</span> <span m=''2906750''>calculation</span>
  <span m=''2907070''>you</span> <span m=''2907390''>do.</span> </p><p><span m=''2908220''>So</span>
  <span m=''2909240''>this</span> <span m=''2909410''>is</span> <span m=''2909540''>the</span>
  <span m=''2909570''>calculation.</span> <span m=''2910070''>So</span> <span m=''2910170''>what</span>
  <span m=''2910330''>you''re</span> <span m=''2910460''>doing</span> <span m=''2910670''>is</span>
  <span m=''2910770''>calculating</span> <span m=''2911210''>this.</span> <span m=''2911410''>You</span>
  <span m=''2911630''>are</span> <span m=''2912070''>creating</span> <span m=''2912850''>this,</span>
  <span m=''2913090''>this,</span> <span m=''2913220''>this,</span> <span m=''2913920''>and</span>
  <span m=''2914860''>this</span> <span m=''2915220''>and</span> <span m=''2915320''>updating</span>
  <span m=''2915760''>that.</span> <span m=''2916370''>And</span> <span m=''2916570''>then,</span>
  <span m=''2916710''>you</span> <span m=''2916860''>do</span> <span m=''2917010''>it</span>
  <span m=''2917110''>for</span> <span m=''2917340''>t</span> <span m=''2917690''>time</span>
  <span m=''2917810''>stamps.</span> <span m=''2918480''>So</span> <span m=''2918620''>you</span>
  <span m=''2918710''>just</span> <span m=''2918880''>go</span> <span m=''2919040''>around</span>
  <span m=''2919380''>doing</span> <span m=''2919600''>each</span> <span m=''2919860''>of</span>
  <span m=''2919960''>these</span> <span m=''2920170''>things</span> <span m=''2920460''>first</span>
  <span m=''2921190''>and</span> <span m=''2921380''>doing</span> <span m=''2921580''>it</span>
  <span m=''2921660''>for</span> <span m=''2921770''>t time</span> <span m=''2922115''>stamps.</span>
  <span m=''2924284''>OK?</span> </p><p><span m=''2924740''>So</span> <span m=''2924960''>we</span>
  <span m=''2925100''>would</span> <span m=''2925270''>like</span> <span m=''2925640''>to</span>
  <span m=''2925800''>run</span> <span m=''2926204''>this parallel.</span> <span m=''2929620''>So</span>
  <span m=''2929770''>here''s</span> <span m=''2930150''>my</span> <span m=''2932430''>basically</span>
  <span m=''2933210''>data</span> <span m=''2933470''>space.</span> <span m=''2933650''>There''s</span>
  <span m=''2934100''>my</span> <span m=''2934220''>data</span> <span m=''2934550''>items.</span>
  <span m=''2935270''>So</span> <span m=''2935410''>here''s</span> <span m=''2935510''>my</span>
  <span m=''2935620''>array,</span> <span m=''2936150''>two-dimensional</span> <span
  m=''2936640''>array.</span> <span m=''2936980''>So</span> <span m=''2937070''>this</span>
  <span m=''2937240''>is</span> <span m=''2937380''>how</span> <span m=''2937520''>I''m</span>
  <span m=''2938010''>trying</span> <span m=''2938210''>to update.</span> <span m=''2938540''>I''m
  reading</span> <span m=''2938850''>all</span> <span m=''2939010''>this</span> <span
  m=''2939210''>file.</span> </p><p><span m=''2940170''>So</span> <span m=''2940340''>here''s</span>
  <span m=''2940660''>my</span> <span m=''2940810''>iteration</span> <span m=''2941300''>space.</span>
  <span m=''2941760''>So</span> <span m=''2942000''>what</span> <span m=''2942170''>I</span>
  <span m=''2942280''>have</span> <span m=''2942500''>looked</span> <span m=''2942740''>at</span>
  <span m=''2942870''>this.</span> <span m=''2943050''>I</span> <span m=''2943300''>don''t</span>
  <span m=''2943550''>want</span> <span m=''2943760''>to--</span> <span m=''2944590''>it''s</span>
  <span m=''2944730''>hard</span> <span m=''2945000''>to</span> <span m=''2945070''>give</span>
  <span m=''2945250''>you</span> <span m=''2945350''>a</span> <span m=''2945400''>3D</span>
  <span m=''2945820''>diagram.</span> <span m=''2946400''>I</span> <span m=''2946530''>don''t</span>
  <span m=''2946670''>have</span> <span m=''2946790''>a</span> <span m=''2946910''>3D</span>
  <span m=''2947230''>projector.</span> <span m=''2948190''>So</span> <span m=''2948400''>what</span>
  <span m=''2948550''>I''m</span> <span m=''2948710''>showing</span> <span m=''2949150''>here</span>
  <span m=''2949380''>is</span> <span m=''2950240''>three-dimension</span> <span m=''2950940''>here.</span>
  <span m=''2951160''>So</span> <span m=''2951280''>this</span> <span m=''2951480''>is</span>
  <span m=''2951620''>the</span> <span m=''2951720''>previous</span> <span m=''2952120''>iteration,</span>
  <span m=''2952730''>first</span> <span m=''2952830''>iteration.</span> </p><p><span
  m=''2953850''>So</span> <span m=''2954140''>if</span> <span m=''2954320''>I</span>
  <span m=''2954530''>still</span> <span m=''2954930''>go</span> <span m=''2955130''>tij.</span>
  <span m=''2955990''>So</span> <span m=''2956220''>you</span> <span m=''2956360''>go</span>
  <span m=''2956590''>through</span> <span m=''2956750''>t,</span> <span m=''2957470''>and</span>
  <span m=''2957670''>then</span> <span m=''2957840''>you</span> <span m=''2957960''>go</span>
  <span m=''2958180''>through</span> <span m=''2958420''>i</span> <span m=''2958630''>in</span>
  <span m=''2958840''>here,</span> <span m=''2959580''>and</span> <span m=''2959800''>then,</span>
  <span m=''2960050''>when you''re</span> <span m=''2960190''>done,</span> <span m=''2960440''>you</span>
  <span m=''2960540''>go</span> <span m=''2960750''>to</span> <span m=''2960840''>the</span>
  <span m=''2961150''>[UNINTELLIGIBLE]</span> <span m=''2961560''>iteration</span>
  <span m=''2962280''>and</span> <span m=''2962380''>you</span> <span m=''2962490''>go</span>
  <span m=''2962640''>this</span> <span m=''2962880''>way.</span> <span m=''2963440''>So</span>
  <span m=''2963580''>here''s</span> <span m=''2964090''>how</span> <span m=''2964230''>you</span>
  <span m=''2964370''>would</span> <span m=''2964480''>iterate.</span> <span m=''2964820''>So</span>
  <span m=''2964940''>you</span> <span m=''2965090''>run</span> <span m=''2965280''>this</span>
  <span m=''2965480''>one,</span> <span m=''2965640''>this</span> <span m=''2965820''>one,</span>
  <span m=''2965940''>this</span> <span m=''2966150''>one,</span> <span m=''2966680''>this</span>
  <span m=''2966880''>one,</span> <span m=''2967010''>this</span> <span m=''2967180''>one,</span>
  <span m=''2967300''>this</span> <span m=''2967480''>one,</span> <span m=''2967590''>this</span>
  <span m=''2967845''>one,</span> <span m=''2968100''>this one,</span> <span m=''2968200''>this</span>
  <span m=''2968390''>one.</span> <span m=''2968530''>And</span> <span m=''2968650''>then</span>
  <span m=''2969410''>increase</span> <span m=''2969900''>t</span> <span m=''2970080''>by
  1,</span> <span m=''2970380''>and</span> <span m=''2970550''>go</span> <span m=''2970670''>like</span>
  <span m=''2970920''>this.</span> </p><p><span m=''2971500''>And</span> <span m=''2971860''>right</span>
  <span m=''2972130''>now,</span> <span m=''2972410''>we</span> <span m=''2972560''>are
  here.</span> <span m=''2975370''>We are trying</span> <span m=''2975800''>to</span>
  <span m=''2976125''>update</span> <span m=''2976450''>this</span> <span m=''2976750''>one.</span>
  <span m=''2977140''>That''s what we are</span> <span m=''2977625''>trying to do.</span>
  <span m=''2979080''>And</span> <span m=''2979210''>that</span> <span m=''2979410''>means</span>
  <span m=''2979940''>we</span> <span m=''2980070''>are already</span> <span m=''2980570''>finished</span>
  <span m=''2980980''>up</span> <span m=''2981100''>to</span> <span m=''2981200''>this</span>
  <span m=''2981370''>point.</span> <span m=''2982570''>All</span> <span m=''2982800''>these</span>
  <span m=''2982980''>points</span> <span m=''2983190''>are</span> <span m=''2983320''>finished</span>
  <span m=''2983590''>up.</span> </p><p><span m=''2985760''>Now,</span> <span m=''2985960''>what</span>
  <span m=''2986180''>we</span> <span m=''2986260''>have</span> <span m=''2986410''>to</span>
  <span m=''2986490''>do</span> <span m=''2986740''>is</span> <span m=''2987190''>figure</span>
  <span m=''2987660''>out</span> <span m=''2988020''>when</span> <span m=''2988230''>I''m</span>
  <span m=''2988880''>reading,</span> <span m=''2990160''>who</span> <span m=''2990310''>actually</span>
  <span m=''2990460''>wrote</span> <span m=''2990730''>this</span> <span m=''2990990''>value.</span>
  <span m=''2993480''>OK?</span> <span m=''2993920''>First</span> <span m=''2994200''>of</span>
  <span m=''2994310''>all,</span> <span m=''2994420''>let''s</span> <span m=''2994710''>figure</span>
  <span m=''2995010''>out</span> <span m=''2995280''>which</span> <span m=''2995470''>iterations</span>
  <span m=''2996120''>might</span> <span m=''2996600''>be</span> <span m=''2996700''>able</span>
  <span m=''2996830''>to</span> <span m=''2996930''>write</span> <span m=''2997190''>this</span>
  <span m=''2997390''>value.</span> <span m=''2998430''>So</span> <span m=''2999480''>if</span>
  <span m=''2999670''>you</span> <span m=''2999870''>look</span> <span m=''3000030''>at</span>
  <span m=''3001320''>this</span> <span m=''3001670''>value,</span> <span m=''3003230''>this</span>
  <span m=''3004460''>relationship</span> <span m=''3004780''>in</span> <span m=''3005100''>between</span>
  <span m=''3005430''>here.</span> <span m=''3006110''>This</span> <span m=''3006600''>one,</span>
  <span m=''3006920''>basically,</span> <span m=''3007900''>is</span> <span m=''3008590''>ij.</span>
  <span m=''3009060''>And</span> <span m=''3009220''>this</span> <span m=''3009370''>is</span>
  <span m=''3009540''>ij,</span> <span m=''3009770''>ij,</span> <span m=''3009960''>ij.</span>
  <span m=''3011030''>These</span> <span m=''3011400''>three</span> <span m=''3011760''>iterations</span>
  <span m=''3012120''>can</span> <span m=''3012300''>write</span> <span m=''3012580''>this</span>
  <span m=''3012780''>one.</span> <span m=''3013770''>So</span> <span m=''3015075''>and</span>
  <span m=''3015530''>these</span> <span m=''3015900''>iterations</span> <span m=''3016590''>can</span>
  <span m=''3017070''>write</span> <span m=''3017240''>this</span> <span m=''3017570''>one.</span>
  <span m=''3017650''>Let me</span> <span m=''3017900''>go</span> <span m=''3018010''>to</span>
  <span m=''3018090''>this</span> <span m=''3018320''>one.</span> </p><p><span m=''3019770''>This</span>
  <span m=''3019940''>is</span> <span m=''3020060''>a</span> <span m=''3020250''>pretty</span>
  <span m=''3020510''>darn</span> <span m=''3020740''>complicated</span> <span m=''3022050''>[UNINTELLIGIBLE].</span>
  <span m=''3022480''>So</span> <span m=''3022650''>what</span> <span m=''3022810''>that</span>
  <span m=''3023000''>means</span> <span m=''3023280''>is</span> <span m=''3025610''>in</span>
  <span m=''3025790''>this</span> <span m=''3025990''>one,</span> <span m=''3026150''>this</span>
  <span m=''3026450''>one</span> <span m=''3026650''>already</span> <span m=''3027650''>wrote</span>
  <span m=''3027930''>something.</span> <span m=''3028870''>This</span> <span m=''3029060''>is</span>
  <span m=''3029180''>what</span> <span m=''3029340''>I''m</span> <span m=''3029480''>reading</span>
  <span m=''3029890''>in here.</span> <span m=''3030990''>This</span> <span m=''3031240''>one</span>
  <span m=''3031830''>already</span> <span m=''3031990''>wrote</span> <span m=''3032330''>something.</span>
  <span m=''3032500''>This is</span> <span m=''3032620''>what</span> <span m=''3032770''>I''m</span>
  <span m=''3032900''>reading</span> <span m=''3033280''>here. This</span> <span m=''3033430''>iteration</span>
  <span m=''3033890''>wrote</span> <span m=''3034020''>something.</span> <span m=''3034390''>I
  read</span> <span m=''3034480''>it</span> <span m=''3034720''>here.</span> <span
  m=''3035930''>OK.</span> <span m=''3036200''>Everybody</span> <span m=''3036760''>following
  so</span> <span m=''3036920''>far?</span> </p><p><span m=''3038850''>How</span>
  <span m=''3039030''>about</span> <span m=''3039250''>this,</span> <span m=''3039500''>guys?</span>
  <span m=''3040170''>Who</span> <span m=''3040370''>wrote</span> <span m=''3040600''>the</span>
  <span m=''3040760''>value</span> <span m=''3041200''>I am</span> <span m=''3041430''>reading</span>
  <span m=''3041770''>in</span> <span m=''3042090''>these</span> <span m=''3042340''>iterations?</span>
  <span m=''3047530''>In</span> <span m=''3047590''>this</span> <span m=''3047780''>one,</span>
  <span m=''3047970''>I haven''t</span> <span m=''3048080''>reached there</span> <span
  m=''3048385''>yet.</span> <span m=''3050300''>So</span> <span m=''3050750''>who</span>
  <span m=''3050930''>has</span> <span m=''3051090''>written</span> <span m=''3051340''>that?</span>
  <span m=''3053130''>So</span> <span m=''3053250''>I</span> <span m=''3053490''>assume</span>
  <span m=''3053590''>this</span> <span m=''3053720''>is</span> <span m=''3053850''>t</span>
  <span m=''3054000''>equals</span> <span m=''3054300''>1.</span> <span m=''3056812''>[UNINTELLIGIBLE]</span>
  <span m=''3057630''>somebody</span> <span m=''3058100''>has</span> <span m=''3058300''>to
  write</span> <span m=''3058560''>those things.</span> <span m=''3059260''>So</span>
  <span m=''3059390''>what</span> <span m=''3059530''>that</span> <span m=''3059730''>means</span>
  <span m=''3060030''>is</span> <span m=''3061110''>this</span> <span m=''3061550''>also</span>
  <span m=''3062000''>wrote</span> <span m=''3062360''>all</span> <span m=''3062550''>of</span>
  <span m=''3062630''>those</span> <span m=''3062840''>values</span> <span m=''3063150''>because</span>
  <span m=''3063380''>I</span> <span m=''3063450''>have</span> <span m=''3063640''>done</span>
  <span m=''3063860''>those</span> <span m=''3064000''>iterations.</span> </p><p><span
  m=''3064520''>But</span> <span m=''3065300''>the</span> <span m=''3065350''>interesting</span>
  <span m=''3065780''>thing</span> <span m=''3066010''>is</span> <span m=''3066330''>some</span>
  <span m=''3066640''>of</span> <span m=''3066730''>these</span> <span m=''3066930''>values</span>
  <span m=''3067070''>got</span> <span m=''3067190''>overwritten.</span> <span m=''3067630''>This</span>
  <span m=''3067930''>value</span> <span m=''3068230''>got overwritten ,</span> <span
  m=''3069110''>this</span> <span m=''3069310''>value</span> <span m=''3069430''>got</span>
  <span m=''3069500''>overwritten.</span> <span m=''3069650''>So</span> <span m=''3070080''>these</span>
  <span m=''3070310''>two</span> <span m=''3070480''>values</span> <span m=''3070660''>disappear.</span>
  <span m=''3073310''>This</span> <span m=''3073780''>value</span> <span m=''3073980''>got</span>
  <span m=''3074200''>overwritten</span> <span m=''3074780''>by</span> <span m=''3074910''>this</span>
  <span m=''3075200''>guy.</span> <span m=''3075720''>This</span> <span m=''3075840''>value</span>
  <span m=''3076050''>got</span> <span m=''3076150''>overwritten</span> <span m=''3076840''>by</span>
  <span m=''3077420''>this</span> <span m=''3077710''>guy.</span> <span m=''3080080''>OK.</span>
  <span m=''3080280''>But</span> <span m=''3080550''>we</span> <span m=''3080730''>haven''t</span>
  <span m=''3080890''>overwritten</span> <span m=''3081320''>this</span> <span m=''3081570''>value,</span>
  <span m=''3081830''>this</span> <span m=''3082080''>value,</span> <span m=''3082310''>and</span>
  <span m=''3082400''>this</span> <span m=''3082560''>value</span> <span m=''3082770''>yet.</span>
  </p><p><span m=''3083310''>This</span> <span m=''3083620''>one,</span> <span m=''3083940''>basically,</span>
  <span m=''3084970''>I''ve</span> <span m=''3085160''>just</span> <span m=''3085390''>updated.</span>
  <span m=''3085850''>But</span> <span m=''3085980''>I</span> <span m=''3086070''>[UNINTELLIGIBLE]</span>
  <span m=''3086620''>this</span> <span m=''3086880''>one.</span> <span m=''3088894''>Do</span>
  <span m=''3089350''>you</span> <span m=''3089510''>see</span> <span m=''3089650''>this?</span>
  <span m=''3090676''>Is</span> <span m=''3091030''>everybody</span> <span m=''3091390''>following</span>
  <span m=''3091700''>me?</span> </p><p><span m=''3093954''>AUDIENCE: Once again,</span>
  <span m=''3094430''>sir.</span> <span m=''3094906''>I got</span> <span m=''3095382''>lost.</span>
  <span m=''3096810''>So</span> <span m=''3099190''>what are</span> <span m=''3099666''>[INAUDIBLE]</span>
  </p><p><span m=''3100630''>PROFESSOR: So</span> <span m=''3100790''>what</span>
  <span m=''3101020''>happens</span> <span m=''3101430''>is</span> <span m=''3101590''>I
  am</span> <span m=''3101830''>trying</span> <span m=''3101920''>to</span> <span
  m=''3102310''>update in</span> <span m=''3102470''>this</span> <span m=''3102640''>iteration</span>
  <span m=''3103670''>because</span> <span m=''3103940''>this</span> <span m=''3104130''>array</span>
  <span m=''3104330''>get</span> <span m=''3104710''>rid</span> <span m=''3104910''>of</span>
  <span m=''3105020''>multiple</span> <span m=''3105210''>times.</span> <span m=''3106780''>But</span>
  <span m=''3107180''>in each</span> <span m=''3107520''>iteration,</span> <span m=''3107900''>you
  are</span> <span m=''3108180''>only</span> <span m=''3108570''>doing</span> <span
  m=''3108750''>one</span> <span m=''3108960''>update.</span> <span m=''3110200''>So</span>
  <span m=''3110320''>I am</span> <span m=''3110510''>trying</span> <span m=''3110660''>to</span>
  <span m=''3110810''>read</span> <span m=''3111090''>and write</span> <span m=''3111425''>in
  here.</span> </p><p><span m=''3112220''>So</span> <span m=''3112370''>I</span> <span
  m=''3112470''>need</span> <span m=''3112660''>to</span> <span m=''3112750''>read</span>
  <span m=''3113180''>all</span> <span m=''3113510''>of</span> <span m=''3113590''>these</span>
  <span m=''3113820''>five</span> <span m=''3114380''>elements</span> <span m=''3114850''>in</span>
  <span m=''3114950''>this</span> <span m=''3115070''>iteration.</span> <span m=''3116010''>So</span>
  <span m=''3116160''>I</span> <span m=''3116280''>want</span> <span m=''3116460''>to</span>
  <span m=''3116510''>figure</span> <span m=''3116750''>out</span> <span m=''3116850''>who</span>
  <span m=''3117000''>wrote</span> <span m=''3117260''>that.</span> <span m=''3118450''>OK?</span>
  <span m=''3119550''>This</span> <span m=''3120030''>one</span> <span m=''3120770''>can</span>
  <span m=''3121040''>be</span> <span m=''3121150''>written</span> <span m=''3121630''>by</span>
  <span m=''3121830''>this</span> <span m=''3122190''>guy</span> <span m=''3122410''>and</span>
  <span m=''3122610''>this</span> <span m=''3122740''>iteration.</span> <span m=''3123180''>Could</span>
  <span m=''3123290''>this</span> <span m=''3123400''>iteration</span> <span m=''3123960''>write</span>
  <span m=''3124300''>its</span> <span m=''3124590''>value</span> <span m=''3124860''>in</span>
  <span m=''3125150''>here?</span> <span m=''3128110''>OK?</span> <span m=''3129000''>[UNINTELLIGIBLE]</span>
  <span m=''3129420''>This</span> <span m=''3129550''>iteration</span> <span m=''3129980''>write</span>
  <span m=''3130210''>because</span> <span m=''3130280''>we</span> <span m=''3130440''>see</span>
  <span m=''3130580''>it''s</span> <span m=''3131130''>writing</span> <span m=''3131630''>ij.</span>
  <span m=''3131990''>I</span> <span m=''3132040''>mean</span> <span m=''3133010''>my</span>
  <span m=''3133180''>diagram</span> <span m=''3133620''>is</span> <span m=''3133770''>not</span>
  <span m=''3133990''>that</span> <span m=''3134260''>great</span> <span m=''3134630''>because</span>
  <span m=''3134920''>I</span> <span m=''3135020''>have</span> <span m=''3136020''>three</span>
  <span m=''3136560''>in</span> <span m=''3136890''>here</span> <span m=''3137350''>and</span>
  <span m=''3137690''>five</span> <span m=''3138020''>in</span> <span m=''3138400''>here.</span>
  <span m=''3138660''>So</span> <span m=''3138830''>just</span> <span m=''3139110''>bear
  with</span> <span m=''3139380''>me</span> <span m=''3139570''>on</span> <span m=''3139680''>that.</span>
  <span m=''3139890''>So</span> <span m=''3140060''>assume</span> <span m=''3140380''>I</span>
  <span m=''3140520''>am</span> <span m=''3140640''>writing</span> <span m=''3141010''>ij</span>
  <span m=''3141100''>in here.</span> </p><p><span m=''3144760''>So</span> <span m=''3144890''>my</span>
  <span m=''3145110''>iterations</span> <span m=''3145510''>go</span> <span m=''3145550''>from</span>
  <span m=''3145930''>1</span> <span m=''3146180''>to</span> <span m=''3146320''>n,</span>
  <span m=''3146470''>but</span> <span m=''3146640''>my</span> <span m=''3146810''>data</span>
  <span m=''3146970''>goes</span> <span m=''3147040''>from</span> <span m=''3147470''>0</span>
  <span m=''3147890''>to</span> <span m=''3148150''>n</span> <span m=''3148310''>plus</span>
  <span m=''3148550''>1,</span> <span m=''3148810''>basically.</span> <span m=''3149260''>1</span>
  <span m=''3149470''>to</span> <span m=''3149570''>n</span> <span m=''3149670''>minus</span>
  <span m=''3149980''>1</span> <span m=''3150120''>iterations.</span> <span m=''3150990''>0</span>
  <span m=''3151310''>to n</span> <span m=''3151420''>plus</span> <span m=''3151640''>1</span>
  <span m=''3152000''>data.</span> <span m=''3152270''>So</span> <span m=''3152640''>data</span>
  <span m=''3153110''>is</span> <span m=''3153230''>bigger</span> <span m=''3153540''>than</span>
  <span m=''3153760''>iteration</span> <span m=''3154170''>space</span> <span m=''3154750''>because</span>
  <span m=''3155100''>of</span> <span m=''3155160''>[UNINTELLIGIBLE].</span> <span
  m=''3156290''>So</span> <span m=''3156420''>what</span> <span m=''3156550''>happens</span>
  <span m=''3156930''>is</span> <span m=''3157440''>when</span> <span m=''3157720''>I''m</span>
  <span m=''3157910''>in</span> <span m=''3158040''>this</span> <span m=''3158190''>iteration,</span>
  <span m=''3159230''>we''ll</span> <span m=''3159440''>say</span> <span m=''3160520''>this</span>
  <span m=''3160740''>is</span> <span m=''3160910''>1</span> <span m=''3161270''>2</span>
  <span m=''3162930''>iteration.</span> <span m=''3164770''>I</span> <span m=''3165220''>will</span>
  <span m=''3165390''>write</span> <span m=''3165560''>this</span> <span m=''3165870''>value.</span>
  <span m=''3167590''>This</span> <span m=''3167850''>iteration</span> <span m=''3168460''>will
  also</span> <span m=''3170160''>write</span> <span m=''3170420''>this</span> <span
  m=''3170580''>value.</span> <span m=''3172370''>OK?</span> <span m=''3173075''>You</span>
  <span m=''3173350''>see</span> <span m=''3173610''>that?</span> </p><p><span m=''3174730''>All</span>
  <span m=''3174990''>of</span> <span m=''3175110''>these</span> <span m=''3175240''>iterations</span>
  <span m=''3175540''>are the</span> <span m=''3175840''>same.</span> <span m=''3176400''>This</span>
  <span m=''3176570''>iteration</span> <span m=''3176990''>we will</span> <span m=''3177270''>also</span>
  <span m=''3177290''>write</span> <span m=''3177430''>this</span> <span m=''3177650''>value.</span>
  <span m=''3178170''>But</span> <span m=''3178450''>right</span> <span m=''3178780''>now,</span>
  <span m=''3179290''>who is</span> <span m=''3179360''>the last</span> <span m=''3179640''>guy</span>
  <span m=''3179770''>who</span> <span m=''3180040''>wrote</span> <span m=''3180250''>it?</span>
  <span m=''3180880''>The</span> <span m=''3180960''>last</span> <span m=''3181330''>guy</span>
  <span m=''3181590''>that wrote</span> <span m=''3181790''>it</span> <span m=''3181920''>is</span>
  <span m=''3182030''>this</span> <span m=''3182210''>guy.</span> <span m=''3185125''>Because</span>
  <span m=''3185730''>this</span> <span m=''3186040''>iteration</span> <span m=''3186420''>wrote</span>
  <span m=''3186680''>it,</span> <span m=''3186790''>and</span> <span m=''3187040''>after</span>
  <span m=''3187200''>that,</span> <span m=''3187380''>it</span> <span m=''3187670''>got</span>
  <span m=''3187910''>ordered</span> <span m=''3188270''>in</span> <span m=''3188420''>this</span>
  <span m=''3188590''>one.</span> </p><p><span m=''3189060''>But</span> <span m=''3189270''>this</span>
  <span m=''3189440''>one</span> <span m=''3189630''>hadn''t</span> <span m=''3189750''>occurred</span>
  <span m=''3189970''>yet,</span> <span m=''3190390''>so</span> <span m=''3190560''>it</span>
  <span m=''3190650''>hadn''t</span> <span m=''3190870''>been</span> <span m=''3190960''>ordered</span>
  <span m=''3191330''>by</span> <span m=''3191440''>this</span> <span m=''3191560''>guy.</span>
  <span m=''3191900''>So</span> <span m=''3192040''>the</span> <span m=''3192140''>last</span>
  <span m=''3192580''>guy</span> <span m=''3192650''>who</span> <span m=''3192900''>wrote
  it</span> <span m=''3193160''>was</span> <span m=''3193340''>this</span> <span m=''3193510''>one.</span>
  <span m=''3195670''>So</span> <span m=''3195790''>that''s</span> <span m=''3196010''>why</span>
  <span m=''3196100''>I</span> <span m=''3196150''>had</span> <span m=''3196340''>to</span>
  <span m=''3196390''>eliminate</span> <span m=''3196670''>this.</span> <span m=''3196820''>But</span>
  <span m=''3198050''>this</span> <span m=''3198470''>data</span> <span m=''3198790''>value--</span>
  <span m=''3199630''>I</span> <span m=''3199800''>haven''t</span> <span m=''3199970''>executed</span>
  <span m=''3200350''>this</span> <span m=''3200560''>iteration</span> <span m=''3201050''>yet.</span>
  <span m=''3201400''>So</span> <span m=''3201550''>nobody</span> <span m=''3201960''>had</span>
  <span m=''3202190''>written</span> <span m=''3202360''>this one</span> <span m=''3202520''>in</span>
  <span m=''3202610''>this</span> <span m=''3202910''>time</span> <span m=''3203150''>stamp.</span>
  <span m=''3204260''>So</span> <span m=''3204430''>it has to be</span> <span m=''3204780''>from</span>
  <span m=''3204920''>the</span> <span m=''3205010''>previous</span> <span m=''3205350''>time</span>
  <span m=''3205510''>stamp.</span> </p><p><span m=''3206310''>So</span> <span m=''3206460''>I</span>
  <span m=''3206840''>read</span> <span m=''3209850''>two</span> <span m=''3210205''>values</span>
  <span m=''3210560''>from the</span> <span m=''3210620''>current</span> <span m=''3211020''>time</span>
  <span m=''3211170''>stamp,</span> <span m=''3212180''>three</span> <span m=''3212300''>values
  from</span> <span m=''3212440''>the</span> <span m=''3212530''>previous</span> <span
  m=''3212930''>time</span> <span m=''3213220''>stamp.</span> <span m=''3213870''>These</span>
  <span m=''3214050''>three</span> <span m=''3214530''>values have to</span> <span
  m=''3214690''>come</span> <span m=''3214910''>from</span> <span m=''3215050''>the</span>
  <span m=''3215120''>previous</span> <span m=''3215280''>time</span> <span m=''3215450''>stamp.</span>
  <span m=''3215980''>These</span> <span m=''3216230''>two</span> <span m=''3216380''>values</span>
  <span m=''3216460''>that</span> <span m=''3216590''>come</span> <span m=''3216640''>from</span>
  <span m=''3217020''>the</span> <span m=''3217060''>current</span> <span m=''3217320''>time</span>
  <span m=''3217480''>stamp.</span> <span m=''3218670''>You</span> <span m=''3218800''>see</span>
  <span m=''3218940''>that?</span> <span m=''3219830''>OK.</span> <span m=''3220105''>Good.</span>
  </p><p><span m=''3221350''>So</span> <span m=''3222340''>what</span> <span m=''3222570''>that</span>
  <span m=''3222800''>means</span> <span m=''3223160''>is</span> <span m=''3223520''>because</span>
  <span m=''3224720''>dependence</span> <span m=''3224930''>means--</span> <span m=''3225250''>OK.</span>
  <span m=''3227500''>This</span> <span m=''3227850''>line,</span> <span m=''3229250''>this</span>
  <span m=''3229470''>dark,</span> <span m=''3229790''>red</span> <span m=''3230190''>line.</span>
  <span m=''3230455''>See.</span> <span m=''3231160''>I</span> <span m=''3231340''>am</span>
  <span m=''3231730''>reading</span> <span m=''3232750''>a</span> <span m=''3232850''>value</span>
  <span m=''3233270''>in</span> <span m=''3233530''>a</span> <span m=''3233630''>current</span>
  <span m=''3234100''>iteration</span> <span m=''3234570''>that</span> <span m=''3234740''>was
  written</span> <span m=''3235210''>by</span> <span m=''3235340''>this</span> <span
  m=''3235530''>iteration.</span> <span m=''3236070''>So</span> <span m=''3236190''>that</span>
  <span m=''3236390''>means</span> <span m=''3236530''>I</span> <span m=''3236600''>have</span>
  <span m=''3236770''>no</span> <span m=''3236910''>dependence</span> <span m=''3237460''>between</span>
  <span m=''3237740''>these</span> <span m=''3237890''>two</span> <span m=''3238210''>iterations.</span>
  </p><p><span m=''3240670''>OK.</span> <span m=''3240960''>This</span> <span m=''3241410''>line,</span>
  <span m=''3242780''>this</span> <span m=''3243020''>dark,</span> <span m=''3243300''>red</span>
  <span m=''3243620''>line.</span> <span m=''3243930''>I am</span> <span m=''3244170''>reading</span>
  <span m=''3244660''>a</span> <span m=''3244770''>value</span> <span m=''3244940''>written</span>
  <span m=''3245060''>by</span> <span m=''3245170''>this</span> <span m=''3245400''>iteration.</span>
  <span m=''3246020''>So I have a</span> <span m=''3246250''>dependency</span> <span
  m=''3246625''>in here.</span> <span m=''3247870''>This</span> <span m=''3248300''>line</span>
  <span m=''3248710''>means</span> <span m=''3248990''>I</span> <span m=''3249070''>have
  a</span> <span m=''3249240''>dependence</span> <span m=''3249710''>between</span>
  <span m=''3249940''>this</span> <span m=''3250070''>iteration</span> <span m=''3250590''>to
  the</span> <span m=''3250660''>current</span> <span m=''3250830''>one.</span> <span
  m=''3251750''>This</span> <span m=''3252000''>line</span> <span m=''3252380''>means</span>
  <span m=''3252540''>I have</span> <span m=''3252820''>dependence</span> <span m=''3253100''>between</span>
  <span m=''3253240''>this</span> <span m=''3253310''>iteration</span> <span m=''3253920''>and
  the</span> <span m=''3254250''>current</span> <span m=''3254340''>one.</span> <span
  m=''3254540''>This line</span> <span m=''3254860''>means</span> <span m=''3254990''>I
  have</span> <span m=''3255250''>dependence</span> <span m=''3255630''>between</span>
  <span m=''3255880''>this</span> <span m=''3255980''>iteration</span> <span m=''3256470''>and
  the</span> <span m=''3256888''>current</span> <span m=''3257306''>one.</span> <span
  m=''3258980''>You</span> <span m=''3259100''>see</span> <span m=''3259220''>that?</span>
  </p><p><span m=''3262480''>OK.</span> <span m=''3263320''>So</span> <span m=''3263630''>now,</span>
  <span m=''3264320''>I</span> <span m=''3264460''>want</span> <span m=''3264650''>to</span>
  <span m=''3264720''>see</span> <span m=''3265140''>how we can</span> <span m=''3265580''>parallelize</span>
  <span m=''3266020''>this</span> <span m=''3266370''>group.</span> <span m=''3268560''>So</span>
  <span m=''3268780''>what</span> <span m=''3269060''>can I do?</span> <span m=''3270380''>So</span>
  <span m=''3270510''>I</span> <span m=''3270590''>look</span> <span m=''3270790''>at</span>
  <span m=''3270840''>all</span> <span m=''3271080''>this</span> <span m=''3271250''>dependence.</span>
  <span m=''3272200''>At</span> <span m=''3272330''>this</span> <span m=''3272510''>point,</span>
  <span m=''3272690''>I</span> <span m=''3272750''>don''t</span> <span m=''3273100''>have
  to think</span> <span m=''3273280''>about</span> <span m=''3273490''>all</span>
  <span m=''3273670''>this</span> <span m=''3274020''>where</span> <span m=''3274250''>who</span>
  <span m=''3274720''>wrote what.</span> <span m=''3274910''>I</span> <span m=''3274960''>can</span>
  <span m=''3275180''>say</span> <span m=''3275460''>this is dependence.</span> <span
  m=''3277840''>In</span> <span m=''3278120''>order</span> <span m=''3278660''>to</span>
  <span m=''3280440''>do</span> <span m=''3280700''>this</span> <span m=''3280850''>equation,</span>
  <span m=''3282260''>all</span> <span m=''3282400''>these</span> <span m=''3282550''>iterations</span>
  <span m=''3283060''>have</span> <span m=''3283230''>to</span> <span m=''3283310''>be</span>
  <span m=''3283410''>done</span> <span m=''3285000''>because</span> <span m=''3285240''>I
  am</span> <span m=''3285450''>losing</span> <span m=''3285700''>the</span> <span
  m=''3285790''>values</span> <span m=''3286120''>produced</span> <span m=''3286420''>by</span>
  <span m=''3286540''>them.</span> <span m=''3287440''>So</span> <span m=''3287610''>these</span>
  <span m=''3287940''>have to</span> <span m=''3288080''>be</span> <span m=''3288220''>finished</span>
  <span m=''3288510''>before</span> <span m=''3288710''>I</span> <span m=''3288780''>can</span>
  <span m=''3288960''>patch that.</span> </p><p><span m=''3289740''>So</span> <span
  m=''3289990''>the</span> <span m=''3290130''>parallelism</span> <span m=''3290490''>means</span>
  <span m=''3291010''>I</span> <span m=''3291160''>tried</span> <span m=''3291700''>to</span>
  <span m=''3291760''>do</span> <span m=''3291940''>things</span> <span m=''3292510''>in</span>
  <span m=''3292650''>parallel.</span> <span m=''3294430''>So</span> <span m=''3295780''>can</span>
  <span m=''3295950''>we</span> <span m=''3296040''>parallelize</span> <span m=''3296490''>this</span>
  <span m=''3296680''>loop?</span> <span m=''3300120''>Can</span> <span m=''3300340''>we</span>
  <span m=''3300490''>run</span> <span m=''3300750''>each</span> <span m=''3301060''>time</span>
  <span m=''3301290''>stamp</span> <span m=''3301500''>separately?</span> <span m=''3305110''>No</span>
  <span m=''3305730''>because</span> <span m=''3306440''>I</span> <span m=''3306630''>am</span>
  <span m=''3306860''>using</span> <span m=''3307210''>these</span> <span m=''3307620''>three
  values</span> <span m=''3308350''>from</span> <span m=''3308520''>the</span> <span
  m=''3308590''>previous</span> <span m=''3308940''>time</span> <span m=''3309150''>stamp.</span>
  <span m=''3310100''>So</span> <span m=''3310270''>I</span> <span m=''3310360''>can''t</span>
  <span m=''3310680''>run</span> <span m=''3311030''>this</span> <span m=''3311320''>time
  stamp,</span> <span m=''3311700''>B</span> <span m=''3312060''>equals</span> <span
  m=''3312365''>1,</span> <span m=''3313380''>until</span> <span m=''3313610''>B</span>
  <span m=''3314030''>equals</span> <span m=''3314500''>0</span> <span m=''3314640''>is
  done.</span> <span m=''3315670''>Or</span> <span m=''3315790''>B</span> <span m=''3315930''>plus</span>
  <span m=''3316160''>2</span> <span m=''3316260''>[UNINTELLIGIBLE]</span> <span m=''3316460''>B</span>
  <span m=''3316560''>plus</span> <span m=''3316880''>1</span> <span m=''3317190''>is
  done.</span> <span m=''3318700''>OK?</span> <span m=''3319030''>So</span> <span
  m=''3319180''>I</span> <span m=''3319260''>can''t</span> <span m=''3319640''>parallelize</span>
  <span m=''3319880''>this</span> <span m=''3320090''>loop.</span> </p><p><span m=''3322690''>OK.</span>
  <span m=''3322930''>Can</span> <span m=''3323205''>I</span> <span m=''3323480''>parallelize</span>
  <span m=''3323800''>this loop?</span> <span m=''3326320''>Why?</span> <span m=''3327850''>Will</span>
  <span m=''3328060''>dependence</span> <span m=''3328910''>stop</span> <span m=''3329440''>me</span>
  <span m=''3329600''>from</span> <span m=''3329920''>parallelizing</span> <span m=''3330350''>this</span>
  <span m=''3330540''>one?</span> <span m=''3336070''>So</span> <span m=''3336220''>I''m</span>
  <span m=''3336410''>looking</span> <span m=''3336760''>at</span> <span m=''3337270''>i.</span>
  <span m=''3337710''>This</span> <span m=''3337860''>is</span> <span m=''3337990''>my</span>
  <span m=''3338230''>i</span> <span m=''3338500''>dimension.</span> <span m=''3340180''>How</span>
  <span m=''3340330''>many</span> <span m=''3340540''>lines,</span> <span m=''3340830''>at</span>
  <span m=''3340980''>least,</span> <span m=''3341130''>tell</span> <span m=''3341460''>me.</span>
  <span m=''3341720''>How</span> <span m=''3341890''>many</span> <span m=''3342570''>dependencies</span>
  <span m=''3342690''>are</span> <span m=''3342850''>going</span> <span m=''3342980''>to</span>
  <span m=''3343120''>stop</span> <span m=''3343370''>me</span> <span m=''3343520''>from</span>
  <span m=''3343700''>doing</span> <span m=''3343910''>that?</span> <span m=''3346850''>OK.</span>
  <span m=''3347160''>Good.</span> <span m=''3347510''>I</span> <span m=''3347630''>have</span>
  <span m=''3347750''>[UNINTELLIGIBLE].</span> <span m=''3348180''>Somebody</span>
  <span m=''3348520''>says</span> <span m=''3348660''>three.</span> <span m=''3349290''>Somebody
  says</span> <span m=''3349730''>one.</span> </p><p><span m=''3350750''>OK.</span>
  <span m=''3351030''>Let''s</span> <span m=''3351150''>get</span> <span m=''3351270''>a</span>
  <span m=''3351440''>vote.</span> <span m=''3351930''>How</span> <span m=''3352060''>many</span>
  <span m=''3352200''>people</span> <span m=''3352490''>think</span> <span m=''3352750''>it''s</span>
  <span m=''3353280''>three?</span> <span m=''3356390''>OK.</span> <span m=''3356630''>There''s</span>
  <span m=''3356830''>one</span> <span m=''3357060''>vote</span> <span m=''3357210''>for
  three.</span> <span m=''3358760''>How many</span> <span m=''3358990''>people</span>
  <span m=''3359150''>think it''s</span> <span m=''3359340''>three?</span> <span m=''3360060''>How
  many</span> <span m=''3360220''>people</span> <span m=''3360600''>think it''s</span>
  <span m=''3360730''>one?</span> <span m=''3363770''>Wait a</span> <span m=''3364080''>minute.</span>
  <span m=''3364530''>One</span> <span m=''3364750''>vote</span> <span m=''3365060''>for</span>
  <span m=''3365380''>three</span> <span m=''3365740''>and</span> <span m=''3365860''>two
  votes</span> <span m=''3365940''>for</span> <span m=''3366150''>one?</span> <span
  m=''3368100''>OK.</span> <span m=''3368350''>Where''s</span> <span m=''3368625''>the</span>
  <span m=''3368900''>rest?</span> <span m=''3370100''>For</span> <span m=''3370290''>two?</span>
  <span m=''3370930''>For</span> <span m=''3371080''>0?</span> <span m=''3372110''>Can''t</span>
  <span m=''3372290''>be</span> <span m=''3372390''>0</span> <span m=''3372750''>if</span>
  <span m=''3372850''>the</span> <span m=''3372930''>0</span> <span m=''3373205''>is
  parallel.</span> <span m=''3373480''>OK.</span> <span m=''3374300''>So we''ll</span>
  <span m=''3374510''>start</span> <span m=''3374730''>parallelizing.</span> </p><p><span
  m=''3376150''>OK.</span> <span m=''3376750''>So</span> <span m=''3376940''>what</span>
  <span m=''3377150''>happens</span> <span m=''3377520''>in</span> <span m=''3377650''>here?</span>
  <span m=''3378960''>Right</span> <span m=''3379220''>now,</span> <span m=''3379480''>this
  is</span> <span m=''3379580''>actually</span> <span m=''3379960''>one.</span> <span
  m=''3381210''>This</span> <span m=''3381420''>one.</span> <span m=''3382660''>Because</span>
  <span m=''3383230''>these</span> <span m=''3383610''>things</span> <span m=''3383870''>don''t</span>
  <span m=''3384150''>participate</span> <span m=''3384920''>because</span> <span
  m=''3386330''>this</span> <span m=''3386590''>has</span> <span m=''3386900''>already</span>
  <span m=''3387620''>happened.</span> <span m=''3388350''>When</span> <span m=''3388460''>you</span>
  <span m=''3388780''>go</span> <span m=''3389190''>to</span> <span m=''3390800''>ij</span>
  <span m=''3391180''>iterations,</span> <span m=''3392040''>these</span> <span m=''3392300''>are
  already</span> <span m=''3392800''>done.</span> <span m=''3393030''>So</span> <span
  m=''3393130''>you''re</span> <span m=''3393260''>going</span> <span m=''3393550''>from</span>
  <span m=''3393730''>t.</span> <span m=''3394170''>So</span> <span m=''3394290''>you''re</span>
  <span m=''3394480''>looking</span> <span m=''3394730''>at</span> <span m=''3394810''>the</span>
  <span m=''3394920''>current</span> <span m=''3395340''>iterations</span> <span m=''3395960''>because</span>
  <span m=''3396160''>you''re</span> <span m=''3396310''>ending</span> <span m=''3397740''>in</span>
  <span m=''3397870''>two</span> <span m=''3398130''>loops.</span> </p><p><span m=''3398680''>So</span>
  <span m=''3398760''>the</span> <span m=''3398920''>t</span> <span m=''3399220''>is
  done.</span> <span m=''3399740''>So</span> <span m=''3399960''>these</span> <span
  m=''3400170''>all are</span> <span m=''3400520''>already</span> <span m=''3401000''>done</span>
  <span m=''3401400''>when</span> <span m=''3401600''>you go try</span> <span m=''3401720''>to</span>
  <span m=''3401850''>parallelize</span> <span m=''3402030''>sides.</span> <span m=''3402490''>So</span>
  <span m=''3402610''>I</span> <span m=''3402720''>don''t</span> <span m=''3402830''>have</span>
  <span m=''3402890''>to</span> <span m=''3402960''>worry</span> <span m=''3403120''>about</span>
  <span m=''3403320''>these</span> <span m=''3403510''>three.</span> <span m=''3404740''>In
  here</span> <span m=''3405060''>because</span> <span m=''3405430''>actually</span>
  <span m=''3405790''>I''m losing</span> <span m=''3405950''>t</span> <span m=''3406630''>of</span>
  <span m=''3406960''>something</span> <span m=''3407300''>here,</span> <span m=''3407750''>I</span>
  <span m=''3408150''>am in</span> <span m=''3408623''>trouble.</span> <span m=''3411480''>So</span>
  <span m=''3411870''>when you</span> <span m=''3412020''>go</span> <span m=''3412290''>look</span>
  <span m=''3412490''>at</span> <span m=''3412620''>this</span> <span m=''3412860''>one,</span>
  <span m=''3413280''>I</span> <span m=''3413360''>have</span> <span m=''3413560''>this</span>
  <span m=''3413750''>one.</span> <span m=''3416410''>So</span> <span m=''3416570''>every</span>
  <span m=''3416920''>dimension</span> <span m=''3417030''>has</span> <span m=''3417440''>a</span>
  <span m=''3417710''>dependence</span> <span m=''3417985''>in here.</span> <span
  m=''3419020''>So</span> <span m=''3419230''>I</span> <span m=''3419390''>can''t</span>
  <span m=''3419850''>run</span> <span m=''3419940''>it in parallel.</span> </p><p><span
  m=''3420750''>So</span> <span m=''3420930''>does</span> <span m=''3421280''>this</span>
  <span m=''3421470''>mean</span> <span m=''3421850''>that</span> <span m=''3422060''>there''s
  no</span> <span m=''3422390''>parallelism?</span> <span m=''3428160''>Who</span>
  <span m=''3428290''>think</span> <span m=''3428420''>there''s</span> <span m=''3428630''>no</span>
  <span m=''3428740''>parallelism?</span> <span m=''3432410''>Who</span> <span m=''3432610''>thinks</span>
  <span m=''3432810''>there</span> <span m=''3433120''>is?</span> <span m=''3433340''>Oh,</span>
  <span m=''3433390''>somebody</span> <span m=''3433660''>thinks</span> <span m=''3433760''>there''s</span>
  <span m=''3433930''>no</span> <span m=''3434070''>parallelism.</span> <span m=''3434370''>Who</span>
  <span m=''3434500''>thinks</span> <span m=''3434630''>there''s</span> <span m=''3434880''>parallelism?</span>
  <span m=''3436680''>OK.</span> <span m=''3437170''>More</span> <span m=''3437350''>people</span>
  <span m=''3437570''>think</span> <span m=''3437620''>there''s</span> <span m=''3437770''>parallelism.</span>
  <span m=''3438080''>Let''s</span> <span m=''3438430''>see</span> <span m=''3438640''>what</span>
  <span m=''3438890''>we can do.</span> <span m=''3440090''>Question?</span> </p><p><span
  m=''3441889''>AUDIENCE: Do</span> <span m=''3442382''>you</span> <span m=''3442875''>really</span>
  <span m=''3443368''>think</span> <span m=''3443861''>[INAUDIBLE]</span> <span m=''3454214''>I''m
  trying to figure</span> <span m=''3454707''>out how to</span> <span m=''3455200''>word
  this.</span> <span m=''3456679''>Do you</span> <span m=''3457172''>really</span>
  <span m=''3457665''>want to have</span> <span m=''3458158''>dependence</span> <span
  m=''3458651''>on the same concept?</span> <span m=''3459144''>[INAUDIBLE]?</span>
  </p><p><span m=''3463620''>PROFESSOR: Yeah.</span> <span m=''3463880''>I mean</span>
  <span m=''3464080''>you</span> <span m=''3464230''>can</span> <span m=''3464600''>do--</span>
  <span m=''3465730''>this</span> <span m=''3465970''>is the</span> <span m=''3466090''>way</span>
  <span m=''3467110''>this</span> <span m=''3467380''>SOR</span> <span m=''3467510''>is</span>
  <span m=''3467710''>sitting</span> <span m=''3468410''>so</span> <span m=''3468560''>there''s</span>
  <span m=''3468770''>a</span> <span m=''3468810''>dependence</span> <span m=''3468970''>between</span>
  <span m=''3469110''>time</span> <span m=''3469250''>stamp.</span> <span m=''3470420''>There''s</span>
  <span m=''3470880''>another</span> <span m=''3471300''>SOR.</span> <span m=''3471750''>What</span>
  <span m=''3471950''>they</span> <span m=''3472090''>do is</span> <span m=''3472400''>kind</span>
  <span m=''3472540''>of</span> <span m=''3472690''>a</span> <span m=''3472770''>red,</span>
  <span m=''3473010''>black.</span> <span m=''3473380''>So</span> <span m=''3473490''>when
  you</span> <span m=''3473790''>calculate</span> <span m=''3474280''>the</span> <span
  m=''3474380''>next</span> <span m=''3474630''>time</span> <span m=''3474880''>stamp,</span>
  <span m=''3475590''>you</span> <span m=''3475840''>calculate</span> <span m=''3476260''>it</span>
  <span m=''3476400''>right</span> <span m=''3476570''>and complete</span> <span m=''3476750''>the</span>
  <span m=''3477250''>new</span> <span m=''3477590''>array.</span> <span m=''3477760''>So</span>
  <span m=''3477880''>there''s</span> <span m=''3478080''>no</span> <span m=''3478290''>dependence.</span>
  <span m=''3478560''>So</span> <span m=''3478700''>that''s</span> <span m=''3478890''>a</span>
  <span m=''3478950''>different</span> <span m=''3479470''>algorithm.</span> </p><p><span
  m=''3480900''>This</span> <span m=''3481120''>algorithm,</span> <span m=''3481630''>basically,</span>
  <span m=''3482580''>uses</span> <span m=''3482800''>sum</span> <span m=''3483265''>value</span>
  <span m=''3483530''>from</span> <span m=''3483800''>[UNINTELLIGIBLE]</span> <span
  m=''3483980''>because</span> <span m=''3484580''>the</span> <span m=''3484720''>value--</span>
  <span m=''3485070''>the algorithm</span> <span m=''3485370''>you''re</span> <span
  m=''3485730''>talking--</span> <span m=''3486070''>you already</span> <span m=''3486240''>created</span>
  <span m=''3486540''>the</span> <span m=''3486620''>other</span> <span m=''3486720''>copies.</span>
  <span m=''3486985''>You</span> <span m=''3487250''>had</span> <span m=''3487370''>two</span>
  <span m=''3487490''>copies.</span> <span m=''3487890''>You''re</span> <span m=''3487980''>bouncing</span>
  <span m=''3488310''>back</span> <span m=''3488520''>and</span> <span m=''3488640''>forth.</span>
  <span m=''3489170''>Nice.</span> <span m=''3489530''>No</span> <span m=''3489820''>real</span>
  <span m=''3490120''>problem</span> <span m=''3490510''>in here.</span> <span m=''3491100''>But</span>
  <span m=''3491360''>then</span> <span m=''3491490''>you</span> <span m=''3491660''>had</span>
  <span m=''3491830''>to have</span> <span m=''3492100''>twice the amount</span> <span
  m=''3492350''>of</span> <span m=''3492410''>storage.</span> </p><p><span m=''3492760''>Here,</span>
  <span m=''3492890''>you</span> <span m=''3493090''>are</span> <span m=''3493360''>updating</span>
  <span m=''3493840''>in.</span> <span m=''3494320''>And</span> <span m=''3494560''>since</span>
  <span m=''3494800''>this</span> <span m=''3494960''>is</span> <span m=''3495090''>kind</span>
  <span m=''3495290''>of</span> <span m=''3495340''>running</span> <span m=''3496140''>enough</span>
  <span m=''3496460''>iterations</span> <span m=''3497740''>until</span> <span m=''3498140''>it</span>
  <span m=''3498700''>converges,</span> <span m=''3500130''>it</span> <span m=''3500390''>doesn''t</span>
  <span m=''3500630''>seem</span> <span m=''3500780''>to</span> <span m=''3500840''>matter</span>
  <span m=''3501110''>that</span> <span m=''3502510''>the</span> <span m=''3503190''>[UNINTELLIGIBLE
  PHRASE].</span> </p><p><span m=''3506520''>OK.</span> <span m=''3507280''>So</span>
  <span m=''3509780''>we</span> <span m=''3509890''>cannot</span> <span m=''3510210''>find</span>
  <span m=''3510490''>a</span> <span m=''3510620''>loop,</span> <span m=''3510990''>what</span>
  <span m=''3511170''>we</span> <span m=''3511280''>call</span> <span m=''3511540''>doall</span>
  <span m=''3512140''>loop.</span> <span m=''3512380''>The</span> <span m=''3512570''>doall</span>
  <span m=''3513310''>loop means</span> <span m=''3513520''>there''s</span> <span
  m=''3513800''>no</span> <span m=''3513930''>loop</span> <span m=''3514230''>carried</span>
  <span m=''3514450''>dependences.</span> <span m=''3515380''>It''s</span> <span m=''3515620''>fully</span>
  <span m=''3515910''>parallel.</span> <span m=''3516930''>This</span> <span m=''3517110''>is</span>
  <span m=''3517190''>the</span> <span m=''3517270''>best</span> <span m=''3517670''>case.</span>
  </p><p><span m=''3518900''>So</span> <span m=''3519080''>what</span> <span m=''3519260''>happens</span>
  <span m=''3519560''>is</span> <span m=''3519670''>when</span> <span m=''3519820''>you</span>
  <span m=''3519960''>get</span> <span m=''3520240''>there,</span> <span m=''3521470''>everybody</span>
  <span m=''3521880''>can</span> <span m=''3522020''>run</span> <span m=''3522250''>parallel.</span>
  <span m=''3522620''>And</span> <span m=''3522990''>when you''re</span> <span m=''3523050''>done,</span>
  <span m=''3523310''>you</span> <span m=''3523680''>can stop</span> <span m=''3523800''>and</span>
  <span m=''3523970''>then</span> <span m=''3524140''>do that.</span> <span m=''3524770''>So</span>
  <span m=''3524850''>this</span> <span m=''3525040''>is</span> <span m=''3525160''>the</span>
  <span m=''3525220''>doall</span> <span m=''3525310''>loop.</span> <span m=''3526540''>Of</span>
  <span m=''3526700''>course,</span> <span m=''3526910''>there''s</span> <span m=''3527110''>no</span>
  <span m=''3527240''>doall</span> <span m=''3527400''>loop.</span> <span m=''3527560''>We</span>
  <span m=''3527840''>can look</span> <span m=''3527970''>at</span> <span m=''3528100''>every</span>
  <span m=''3528350''>dimension.</span> <span m=''3528830''>We</span> <span m=''3528900''>had</span>
  <span m=''3529070''>some</span> <span m=''3529280''>kind</span> <span m=''3529380''>of</span>
  <span m=''3529490''>dependence.</span> </p><p><span m=''3530290''>So</span> <span
  m=''3530440''>there''s</span> <span m=''3530550''>another</span> <span m=''3530910''>choice,</span>
  <span m=''3531260''>what</span> <span m=''3531410''>we</span> <span m=''3531730''>call</span>
  <span m=''3531920''>doacross</span> <span m=''3532520''>loop.</span> <span m=''3533430''>What</span>
  <span m=''3533770''>that</span> <span m=''3534010''>means</span> <span m=''3534380''>is</span>
  <span m=''3534590''>we</span> <span m=''3534830''>have</span> <span m=''3535070''>some</span>
  <span m=''3535490''>loop</span> <span m=''3535670''>carried</span> <span m=''3535980''>dependence.</span>
  <span m=''3537200''>There''s</span> <span m=''3537300''>something</span> <span m=''3537790''>I
  have</span> <span m=''3538080''>to</span> <span m=''3538370''>use</span> <span m=''3538660''>for</span>
  <span m=''3538760''>the</span> <span m=''3538850''>previous</span> <span m=''3539180''>iteration.</span>
  <span m=''3540320''>But</span> <span m=''3540840''>it''s</span> <span m=''3540990''>only</span>
  <span m=''3541200''>one</span> <span m=''3541510''>thing.</span> </p><p><span m=''3541910''>I</span>
  <span m=''3542020''>have</span> <span m=''3542150''>a</span> <span m=''3542180''>lot</span>
  <span m=''3542440''>of</span> <span m=''3542570''>other</span> <span m=''3542830''>things</span>
  <span m=''3543080''>I</span> <span m=''3543140''>can</span> <span m=''3543610''>run</span>
  <span m=''3543890''>around</span> <span m=''3544190''>that</span> <span m=''3544410''>only</span>
  <span m=''3544950''>I</span> <span m=''3545150''>just</span> <span m=''3545350''>have</span>
  <span m=''3545440''>to</span> <span m=''3545520''>wait</span> <span m=''3545760''>one</span>
  <span m=''3546010''>thing.</span> <span m=''3546190''>One is</span> <span m=''3546580''>done.</span>
  <span m=''3546820''>I</span> <span m=''3546890''>can</span> <span m=''3547060''>just</span>
  <span m=''3547290''>keep</span> <span m=''3547490''>running.</span> <span m=''3548190''>And</span>
  <span m=''3548350''>if</span> <span m=''3548520''>I</span> <span m=''3548600''>calculate</span>
  <span m=''3548855''>and</span> <span m=''3549110''>send</span> <span m=''3549340''>this</span>
  <span m=''3549480''>one</span> <span m=''3549660''>early,</span> <span m=''3550140''>then</span>
  <span m=''3550430''>I</span> <span m=''3550510''>can</span> <span m=''3550760''>do</span>
  <span m=''3551020''>my</span> <span m=''3551140''>other</span> <span m=''3551270''>calculations</span>
  <span m=''3551575''>later.</span> </p><p><span m=''3553250''>This</span> <span m=''3553410''>is</span>
  <span m=''3553570''>not</span> <span m=''3553730''>that</span> <span m=''3553910''>great.</span>
  <span m=''3554160''>If</span> <span m=''3554250''>you</span> <span m=''3554340''>look</span>
  <span m=''3554480''>at</span> <span m=''3554630''>the</span> <span m=''3554730''>difference</span>
  <span m=''3555110''>here.</span> <span m=''3555820''>This</span> <span m=''3556040''>definitely</span>
  <span m=''3556570''>has</span> <span m=''3556950''>very</span> <span m=''3557300''>little</span>
  <span m=''3557470''>overhead</span> <span m=''3558130''>in</span> <span m=''3558420''>here.</span>
  <span m=''3559350''>This</span> <span m=''3560750''>can</span> <span m=''3561120''>run
  slow.</span> <span m=''3561330''>And</span> <span m=''3561550''>of</span> <span
  m=''3561640''>course,</span> <span m=''3561990''>this</span> <span m=''3562240''>thing</span>
  <span m=''3562380''>gets</span> <span m=''3562550''>produced</span> <span m=''3562850''>very</span>
  <span m=''3562950''>late.</span> <span m=''3563050''>It''s</span> <span m=''3563310''>[?
  almost ?]</span> <span m=''3563430''>sequential.</span> <span m=''3564790''>So</span>
  <span m=''3565090''>I</span> <span m=''3565420''>hope</span> <span m=''3566240''>you</span>
  <span m=''3566340''>can</span> <span m=''3566530''>just--</span> <span m=''3566920''>it</span>
  <span m=''3567080''>the other</span> <span m=''3567250''>guy</span> <span m=''3567370''>wants</span>
  <span m=''3567610''>something,</span> <span m=''3567890''>I</span> <span m=''3567930''>can</span>
  <span m=''3568120''>immediately</span> <span m=''3568560''>send</span> <span m=''3568800''>it
  very</span> <span m=''3569180''>early.</span> <span m=''3569810''>And</span> <span
  m=''3569960''>then</span> <span m=''3570090''>I</span> <span m=''3570150''>can</span>
  <span m=''3570370''>run</span> <span m=''3570570''>there.</span> <span m=''3571560''>So</span>
  <span m=''3572410''>you can get</span> <span m=''3572590''>some</span> <span m=''3572780''>kind</span>
  <span m=''3572930''>of</span> <span m=''3573030''>doacross</span> <span m=''3573230''>patterns</span>
  <span m=''3573440''>in here.</span> </p><p><span m=''3575600''>So</span> <span m=''3576170''>if</span>
  <span m=''3576320''>you</span> <span m=''3576460''>want</span> <span m=''3576630''>to</span>
  <span m=''3576720''>do</span> <span m=''3576910''>this</span> <span m=''3577130''>one--</span>
  <span m=''3577690''>this</span> <span m=''3577850''>is</span> <span m=''3578200''>a
  little bit</span> <span m=''3578760''>crazy</span> <span m=''3579210''>in here.</span>
  <span m=''3579710''>But they''ll</span> <span m=''3580050''>do it</span> <span m=''3580500''>in
  here.</span> <span m=''3581580''>And</span> <span m=''3582530''>so</span> <span
  m=''3582690''>what</span> <span m=''3582950''>first we are</span> <span m=''3583205''>to
  do</span> <span m=''3583460''>is you are to</span> <span m=''3583710''>say,</span>
  <span m=''3584010''>OK.</span> <span m=''3584260''>Look.</span> <span m=''3584640''>I''m</span>
  <span m=''3584830''>running</span> <span m=''3585120''>this</span> <span m=''3585360''>loop,</span>
  <span m=''3585660''>the</span> <span m=''3585990''>i</span> <span m=''3586180''>loop</span>
  <span m=''3586470''>in</span> <span m=''3586670''>parallel.</span> <span m=''3588570''>But</span>
  <span m=''3589230''>I</span> <span m=''3589330''>have</span> <span m=''3589550''>to</span>
  <span m=''3589920''>exchange</span> <span m=''3590460''>some</span> <span m=''3590700''>data.</span>
  <span m=''3592410''>Before</span> <span m=''3592710''>I</span> <span m=''3592780''>want</span>
  <span m=''3592980''>to</span> <span m=''3593050''>run</span> <span m=''3593310''>this</span>
  <span m=''3593540''>one,</span> <span m=''3594270''>I</span> <span m=''3594400''>have</span>
  <span m=''3594570''>to</span> <span m=''3594740''>basically</span> <span m=''3595370''>get</span>
  <span m=''3595650''>the</span> <span m=''3595730''>previous</span> <span m=''3596230''>i</span>
  <span m=''3596450''>value</span> <span m=''3597520''>produced.</span> <span m=''3598060''>And</span>
  <span m=''3598230''>when</span> <span m=''3598430''>it''s</span> <span m=''3598630''>done,</span>
  <span m=''3598920''>I</span> <span m=''3598990''>can</span> <span m=''3599170''>say</span>
  <span m=''3599360''>the</span> <span m=''3599480''>next</span> <span m=''3599690''>guy</span>
  <span m=''3599830''>can</span> <span m=''3600010''>use</span> <span m=''3600220''>it.</span>
  </p><p><span m=''3600620''>So</span> <span m=''3600930''>this</span> <span m=''3601110''>is</span>
  <span m=''3601220''>a</span> <span m=''3601340''>very</span> <span m=''3601530''>complicated</span>
  <span m=''3601810''>one.</span> <span m=''3602490''>I</span> <span m=''3602660''>don''t</span>
  <span m=''3602830''>want</span> <span m=''3602920''>you</span> <span m=''3603420''>to</span>
  <span m=''3604120''>understand</span> <span m=''3604590''>it</span> <span m=''3604710''>too</span>
  <span m=''3604920''>well.</span> <span m=''3605430''>So</span> <span m=''3605640''>the</span>
  <span m=''3605960''>reason</span> <span m=''3606250''>I</span> <span m=''3606320''>put</span>
  <span m=''3606510''>it</span> <span m=''3606650''>is to</span> <span m=''3606720''>show</span>
  <span m=''3606960''>that</span> <span m=''3607110''>OK,</span> <span m=''3608550''>if</span>
  <span m=''3608850''>you</span> <span m=''3608990''>want</span> <span m=''3609160''>to</span>
  <span m=''3609210''>spend</span> <span m=''3609440''>a</span> <span m=''3609520''>week</span>
  <span m=''3609920''>trying</span> <span m=''3610190''>to</span> <span m=''3610820''>really</span>
  <span m=''3611190''>call</span> <span m=''3611420''>this</span> <span m=''3611660''>up</span>
  <span m=''3611820''>and</span> <span m=''3611970''>understand</span> <span m=''3612080''>and</span>
  <span m=''3612260''>make</span> <span m=''3612600''>sure</span> <span m=''3612760''>that</span>
  <span m=''3613030''>it</span> <span m=''3613300''>works</span> <span m=''3613450''>OK.</span>
  <span m=''3614230''>So you can</span> <span m=''3614710''>do</span> <span m=''3614820''>things</span>
  <span m=''3615060''>like</span> <span m=''3615210''>that.</span> <span m=''3616930''>OK?</span>
  <span m=''3617910''>Aha.</span> <span m=''3618570''>So</span> <span m=''3618710''>this</span>
  <span m=''3618890''>is</span> <span m=''3619060''>the</span> <span m=''3619350''>true</span>
  <span m=''3619770''>voodooness.</span> <span m=''3621410''>OK.</span> </p><p><span
  m=''3623170''>AUDIENCE: So</span> <span m=''3625990''>in</span> <span m=''3626170''>Cilk,</span>
  <span m=''3626580''>if</span> <span m=''3626710''>you</span> <span m=''3626850''>do</span>
  <span m=''3627010''>this</span> <span m=''3627510''>with</span> <span m=''3627680''>divide</span>
  <span m=''3628020''>and</span> <span m=''3628150''>conquer,</span> <span m=''3628870''>you</span>
  <span m=''3629060''>can</span> <span m=''3629300''>make</span> <span m=''3629590''>it</span>
  <span m=''3629770''>be</span> <span m=''3629940''>what</span> <span m=''3630210''>I</span>
  <span m=''3630330''>called</span> <span m=''3630970''>in</span> <span m=''3631920''>the</span>
  <span m=''3633800''>Tableau</span> <span m=''3634400''>construction.</span> <span
  m=''3635760''>Each</span> <span m=''3636210''>layer</span> <span m=''3636550''>here</span>
  <span m=''3636790''>is</span> <span m=''3636940''>basically</span> <span m=''3637480''>constructing</span>
  <span m=''3638070''>a</span> <span m=''3638140''>Tableau.</span> <span m=''3638820''>And</span>
  <span m=''3638970''>so</span> <span m=''3639060''>if</span> <span m=''3639140''>you</span>
  <span m=''3639220''>do it with</span> <span m=''3639500''>divide</span> <span m=''3639820''>and</span>
  <span m=''3639930''>conquer,</span> <span m=''3640880''>you can do it with a</span>
  <span m=''3641280''>very</span> <span m=''3641520''>simple</span> <span m=''3641860''>recursive</span>
  <span m=''3642380''>code.</span> <span m=''3644670''>But</span> <span m=''3645380''>you</span>
  <span m=''3645470''>can</span> <span m=''3645560''>also</span> <span m=''3645820''>do</span>
  <span m=''3646060''>it</span> <span m=''3646180''>with</span> <span m=''3646280''>a</span>
  <span m=''3646380''>loop</span> <span m=''3646720''>that</span> <span m=''3646830''>goes</span>
  <span m=''3647120''>diagonally.</span> </p><p><span m=''3649160''>AUDIENCE: [INTERPOSING
  VOICES]</span> </p><p><span m=''3649260''>PROFESSOR: Yes.</span> <span m=''3649390''>I''m
  going</span> <span m=''3649580''>to</span> <span m=''3649620''>get</span> <span
  m=''3649790''>that.</span> <span m=''3650460''>That''s</span> <span m=''3650770''>next.</span>
  </p><p><span m=''3652690''>AUDIENCE: Sorry.</span> </p><p><span m=''3653770''>PROFESSOR:
  That''s</span> <span m=''3653950''>OK.</span> <span m=''3654540''>So</span> <span
  m=''3655330''>the</span> <span m=''3655520''>reason</span> <span m=''3656030''>that</span>
  <span m=''3657012''>I''m</span> <span m=''3657370''>showing</span> <span m=''3657720''>that</span>
  <span m=''3657950''>is</span> <span m=''3659960''>because</span> <span m=''3660260''>this</span>
  <span m=''3660490''>class</span> <span m=''3660860''>is</span> <span m=''3661080''>not</span>
  <span m=''3661390''>just</span> <span m=''3661760''>about</span> <span m=''3663250''>how</span>
  <span m=''3663490''>to</span> <span m=''3663620''>make</span> <span m=''3663820''>the</span>
  <span m=''3663920''>cores</span> <span m=''3664320''>exactly</span> <span m=''3664710''>run</span>
  <span m=''3664830''>faster.</span> <span m=''3665210''>Think</span> <span m=''3665460''>about</span>
  <span m=''3665630''>algorithmic</span> <span m=''3665940''>issues</span> <span m=''3666440''>and</span>
  <span m=''3666570''>stuff</span> <span m=''3666830''>like</span> <span m=''3666990''>that.</span>
  <span m=''3667630''>So</span> <span m=''3667820''>sometimes,</span> <span m=''3668370''>when</span>
  <span m=''3668480''>you</span> <span m=''3668570''>look</span> <span m=''3668700''>at</span>
  <span m=''3668830''>a</span> <span m=''3668890''>problem,</span> <span m=''3669360''>it</span>
  <span m=''3669480''>looks</span> <span m=''3669920''>crazy.</span> <span m=''3670670''>And</span>
  <span m=''3670930''>there</span> <span m=''3670980''>might</span> <span m=''3671190''>be</span>
  <span m=''3671280''>some</span> <span m=''3671550''>changes</span> <span m=''3672010''>you</span>
  <span m=''3672160''>can</span> <span m=''3672410''>do</span> <span m=''3672950''>that</span>
  <span m=''3673140''>you</span> <span m=''3673240''>can</span> <span m=''3673430''>get</span>
  <span m=''3673900''>to run things</span> <span m=''3674250''>in</span> <span m=''3674470''>parallel.</span>
  </p><p><span m=''3676590''>So</span> <span m=''3677100''>I''m</span> <span m=''3677370''>actually</span>
  <span m=''3677630''>doing</span> <span m=''3678210''>not</span> <span m=''3678290''>diagonal.</span>
  <span m=''3678890''>I''m actually</span> <span m=''3679150''>doing</span> <span
  m=''3679220''>something</span> <span m=''3679750''>very</span> <span m=''3680500''>simple.</span>
  <span m=''3681030''>So</span> <span m=''3681170''>what</span> <span m=''3681400''>I</span>
  <span m=''3681660''>have</span> <span m=''3681920''>done</span> <span m=''3682230''>here</span>
  <span m=''3683730''>is</span> <span m=''3685280''>I</span> <span m=''3685390''>have</span>
  <span m=''3685650''>all</span> <span m=''3685990''>these</span> <span m=''3686120''>dependences</span>
  <span m=''3686640''>in here.</span> <span m=''3687120''>OK?</span> <span m=''3687660''>So</span>
  <span m=''3687970''>the</span> <span m=''3688090''>problem</span> <span m=''3688580''>here</span>
  <span m=''3688880''>is</span> <span m=''3690770''>I</span> <span m=''3690910''>can''t</span>
  <span m=''3691240''>find</span> <span m=''3691450''>a</span> <span m=''3691490''>single</span>
  <span m=''3692290''>[UNINTELLIGIBLE]</span> <span m=''3694380''>that</span> <span
  m=''3694710''>basically</span> <span m=''3695430''>has</span> <span m=''3696490''>no</span>
  <span m=''3696700''>crossing.</span> </p><p><span m=''3697390''>But</span> <span
  m=''3697740''>if</span> <span m=''3697900''>you</span> <span m=''3698060''>look</span>
  <span m=''3698300''>at</span> <span m=''3698590''>this</span> <span m=''3698910''>[UNINTELLIGIBLE]</span>
  <span m=''3699500''>diagonal</span> <span m=''3699720''>here.</span> <span m=''3701140''>What</span>
  <span m=''3701340''>you</span> <span m=''3701540''>see</span> <span m=''3701910''>is,</span>
  <span m=''3702820''>in</span> <span m=''3703030''>fact,</span> <span m=''3703530''>there''s</span>
  <span m=''3704010''>nothing</span> <span m=''3704390''>that</span> <span m=''3704530''>crosses</span>
  <span m=''3704780''>the</span> <span m=''3704870''>diagonal.</span> <span m=''3708370''>OK?</span>
  <span m=''3708880''>So</span> <span m=''3709570''>this</span> <span m=''3709990''>one</span>
  <span m=''3710270''>basically</span> <span m=''3710930''>doesn''t</span> <span m=''3711190''>depend</span>
  <span m=''3711490''>on</span> <span m=''3711600''>this</span> <span m=''3711820''>one</span>
  <span m=''3712030''>or</span> <span m=''3712090''>this</span> <span m=''3712340''>one.</span>
  <span m=''3712790''>It</span> <span m=''3712910''>only</span> <span m=''3713150''>depends</span>
  <span m=''3713460''>on</span> <span m=''3713550''>the previous</span> <span m=''3714050''>one.</span>
  <span m=''3714480''>So</span> <span m=''3714630''>I</span> <span m=''3714710''>can</span>
  <span m=''3714940''>run</span> <span m=''3715180''>everything</span> <span m=''3715780''>in</span>
  <span m=''3715850''>the</span> <span m=''3715940''>diagonal</span> <span m=''3716270''>parallel</span>
  <span m=''3717030''>in here</span> <span m=''3717430''>in this</span> <span m=''3717630''>one.</span>
  </p><p><span m=''3718560''>So</span> <span m=''3718890''>of</span> <span m=''3719080''>course,</span>
  <span m=''3719280''>I</span> <span m=''3719370''>can''t</span> <span m=''3719730''>write</span>
  <span m=''3720370''>anything</span> <span m=''3720730''>[UNINTELLIGIBLE]</span>
  <span m=''3721075''>in here,</span> <span m=''3721420''>but</span> <span m=''3721820''>there''s</span>
  <span m=''3722020''>a</span> <span m=''3722090''>cute</span> <span m=''3722380''>trick</span>
  <span m=''3722620''>you</span> <span m=''3722790''>can</span> <span m=''3722960''>do.</span>
  <span m=''3723260''>What</span> <span m=''3723510''>you</span> <span m=''3723770''>can</span>
  <span m=''3723980''>do</span> <span m=''3724140''>is</span> <span m=''3724280''>you</span>
  <span m=''3724620''>can</span> <span m=''3725880''>take iteration</span> <span m=''3726400''>space</span>
  <span m=''3727210''>and</span> <span m=''3727410''>skew</span> <span m=''3727800''>it.</span>
  <span m=''3730620''>So</span> <span m=''3730820''>what</span> <span m=''3730970''>I</span>
  <span m=''3731160''>have</span> <span m=''3731350''>done</span> <span m=''3731650''>is</span>
  <span m=''3731970''>now</span> <span m=''3732190''>instead</span> <span m=''3732690''>off</span>
  <span m=''3733990''>the same thing,</span> <span m=''3735300''>instead</span> <span
  m=''3735520''>of</span> <span m=''3735700''>this</span> <span m=''3735890''>being</span>
  <span m=''3736300''>a square,</span> <span m=''3736950''>now I</span> <span m=''3737240''>skewed</span>
  <span m=''3737630''>it</span> <span m=''3737710''>a little bit.</span> <span m=''3740250''>OK?</span>
  </p><p><span m=''3740790''>So</span> <span m=''3740930''>what</span> <span m=''3741080''>that</span>
  <span m=''3741280''>means</span> <span m=''3743370''>is</span> <span m=''3744340''>when
  I''m</span> <span m=''3744550''>running</span> <span m=''3745880''>first</span>
  <span m=''3747600''>i,</span> <span m=''3747820''>I</span> <span m=''3748180''>basically</span>
  <span m=''3748730''>don''t</span> <span m=''3748860''>run</span> <span m=''3749050''>any</span>
  <span m=''3749140''>here.</span> <span m=''3749530''>Then,</span> <span m=''3749610''>I</span>
  <span m=''3749830''>run</span> <span m=''3749950''>this</span> <span m=''3750190''>one</span>
  <span m=''3750490''>and</span> <span m=''3750740''>this</span> <span m=''3750950''>iteration</span>
  <span m=''3752110''>here.</span> <span m=''3752380''>So</span> <span m=''3752510''>what</span>
  <span m=''3752690''>I</span> <span m=''3752790''>have</span> <span m=''3752900''>done</span>
  <span m=''3753050''>is</span> <span m=''3753160''>I have</span> <span m=''3753430''>kind</span>
  <span m=''3753640''>of</span> <span m=''3753680''>moved</span> <span m=''3753910''>my</span>
  <span m=''3754040''>iteration</span> <span m=''3754220''>space</span> <span m=''3754630''>around.</span>
  <span m=''3755090''>Do you</span> <span m=''3755270''>see</span> <span m=''3755400''>how</span>
  <span m=''3756330''>this</span> <span m=''3756500''>might</span> <span m=''3756720''>be?</span>
  </p><p><span m=''3758810''>So</span> <span m=''3758990''>now,</span> <span m=''3759710''>the</span>
  <span m=''3759800''>interesting</span> <span m=''3760300''>thing is</span> <span
  m=''3760430''>when</span> <span m=''3760540''>I</span> <span m=''3760670''>skew,</span>
  <span m=''3761440''>if</span> <span m=''3761650''>I</span> <span m=''3761910''>look</span>
  <span m=''3762080''>at</span> <span m=''3762900''>this</span> <span m=''3763290''>line,</span>
  <span m=''3770200''>I</span> <span m=''3770320''>can</span> <span m=''3770510''>parallelize</span>
  <span m=''3770830''>in</span> <span m=''3771120''>this</span> <span m=''3771310''>one</span>
  <span m=''3775990''>because</span> <span m=''3776260''>all</span> <span m=''3776390''>the
  dependences</span> <span m=''3777070''>come</span> <span m=''3777330''>from</span>
  <span m=''3777500''>the</span> <span m=''3777590''>previous</span> <span m=''3777950''>iteration.</span>
  <span m=''3778490''>Am</span> <span m=''3778630''>I</span> <span m=''3778770''>right?</span>
  <span m=''3779150''>[UNINTELLIGIBLE]</span> <span m=''3783532''>Yeah.</span> <span
  m=''3784000''>I</span> <span m=''3784220''>skewed</span> <span m=''3784560''>it.</span>
  <span m=''3790864''>Yes,</span> <span m=''3791640''>everything</span> <span m=''3792900''>in</span>
  <span m=''3793120''>here,</span> <span m=''3794240''>these</span> <span m=''3794560''>ones</span>
  <span m=''3794840''>are</span> <span m=''3795000''>parallel.</span> <span m=''3796440''>OK?</span>
  </p><p><span m=''3796990''>And</span> <span m=''3797260''>any dependence</span>
  <span m=''3798040''>comes</span> <span m=''3798210''>from</span> <span m=''3798310''>the</span>
  <span m=''3798410''>previous</span> <span m=''3798730''>iteration.</span> <span
  m=''3801070''>There''s</span> <span m=''3801440''>no current iteration</span> <span
  m=''3802100''>in</span> <span m=''3802260''>here.</span> <span m=''3802670''>Everything</span>
  <span m=''3803100''>in</span> <span m=''3803190''>this</span> <span m=''3803390''>one</span>
  <span m=''3803610''>is</span> <span m=''3803770''>parallel.</span> <span m=''3804580''>So</span>
  <span m=''3804710''>I</span> <span m=''3804750''>can</span> <span m=''3804920''>parallelize</span>
  <span m=''3805080''>this.</span> <span m=''3806960''>So</span> <span m=''3807090''>this</span>
  <span m=''3807220''>one</span> <span m=''3807710''>doesn''t</span> <span m=''3807900''>depend</span>
  <span m=''3808150''>on</span> <span m=''3808240''>this</span> <span m=''3808420''>one</span>
  <span m=''3808590''>or</span> <span m=''3808680''>this</span> <span m=''3808860''>one.</span>
  <span m=''3809020''>So</span> <span m=''3809130''>this</span> <span m=''3809320''>is</span>
  <span m=''3809400''>all</span> <span m=''3809580''>parallel.</span> <span m=''3812000''>This</span>
  <span m=''3812150''>is</span> <span m=''3812340''>a</span> <span m=''3812430''>little
  bit more</span> <span m=''3812730''>complicated.</span> <span m=''3813570''>So</span>
  <span m=''3814520''>if</span> <span m=''3814660''>you''re</span> <span m=''3814830''>interested</span>
  <span m=''3815000''>to</span> <span m=''3815970''>go</span> <span m=''3816110''>deep,</span>
  <span m=''3816380''>just</span> <span m=''3816640''>go</span> <span m=''3816990''>stare</span>
  <span m=''3817190''>at</span> <span m=''3817360''>the</span> <span m=''3817440''>slides.</span>
  <span m=''3818005''>I have the slides</span> <span m=''3818270''>out</span> <span
  m=''3818470''>there</span> <span m=''3819440''>to</span> <span m=''3819530''>understand</span>
  <span m=''3819930''>how</span> <span m=''3820070''>that</span> <span m=''3820170''>happens.</span>
  </p><p><span m=''3820460''>So</span> <span m=''3820620''>if</span> <span m=''3820780''>you</span>
  <span m=''3820940''>think</span> <span m=''3821200''>about</span> <span m=''3821420''>what</span>
  <span m=''3821620''>I''m</span> <span m=''3821790''>running</span> <span m=''3822130''>here
  in</span> <span m=''3822480''>parallel</span> <span m=''3822920''>is</span> <span
  m=''3823170''>the</span> <span m=''3823300''>one</span> <span m=''3824010''>basically</span>
  <span m=''3824440''>this</span> <span m=''3825670''>diagonal</span> <span m=''3825930''>in</span>
  <span m=''3826240''>here.</span> <span m=''3827660''>So</span> <span m=''3827840''>what</span>
  <span m=''3828000''>happens</span> <span m=''3828380''>is</span> <span m=''3828880''>if</span>
  <span m=''3829020''>you</span> <span m=''3829210''>run</span> <span m=''3829440''>this,</span>
  <span m=''3829700''>this,</span> <span m=''3829890''>and</span> <span m=''3830150''>this</span>
  <span m=''3830350''>parallel,</span> <span m=''3830870''>there''s</span> <span m=''3831360''>no</span>
  <span m=''3831480''>dependence.</span> <span m=''3831690''>I</span> <span m=''3831860''>don''t</span>
  <span m=''3832030''>need</span> <span m=''3832510''>this</span> <span m=''3832730''>one</span>
  <span m=''3832970''>or</span> <span m=''3833090''>this</span> <span m=''3833340''>one</span>
  <span m=''3833700''>to</span> <span m=''3833830''>run this</span> <span m=''3834050''>one.</span>
  <span m=''3834600''>So</span> <span m=''3834720''>I</span> <span m=''3834790''>can</span>
  <span m=''3835000''>run</span> <span m=''3835150''>this,</span> <span m=''3835625''>this,</span>
  <span m=''3836100''>this,</span> <span m=''3836340''>this, all</span> <span m=''3836550''>this</span>
  <span m=''3836840''>diagonal</span> <span m=''3837340''>in</span> <span m=''3837675''>parallel.</span>
  </p><p><span m=''3838010''>But</span> <span m=''3838160''>the</span> <span m=''3838230''>trouble</span>
  <span m=''3838550''>with just the</span> <span m=''3838760''>diagonal</span> <span
  m=''3839240''>is</span> <span m=''3839340''>I</span> <span m=''3839430''>don''t</span>
  <span m=''3839530''>have a</span> <span m=''3839680''>place</span> <span m=''3840130''>in
  here</span> <span m=''3840360''>to</span> <span m=''3840440''>say</span> <span m=''3841290''>[UNINTELLIGIBLE]</span>
  <span m=''3841850''>for a</span> <span m=''3842090''>diagonal.</span> <span m=''3842560''>So
  I</span> <span m=''3842800''>basically</span> <span m=''3843780''>skewed it</span>
  <span m=''3844010''>and</span> <span m=''3844140''>then</span> <span m=''3844530''>made</span>
  <span m=''3844840''>a</span> <span m=''3844940''>diagonal</span> <span m=''3845390''>into</span>
  <span m=''3845900''>one</span> <span m=''3846260''>loop.</span> <span m=''3846760''>So</span>
  <span m=''3846920''>then,</span> <span m=''3847300''>now</span> <span m=''3847590''>what</span>
  <span m=''3847790''>happens</span> <span m=''3848130''>is</span> <span m=''3849880''>basically</span>
  <span m=''3852330''>j</span> <span m=''3852780''>loop</span> <span m=''3853530''>I</span>
  <span m=''3853620''>can</span> <span m=''3853830''>run</span> <span m=''3854234''>parallel.</span>
  <span m=''3855850''>This</span> <span m=''3856040''>one.</span> <span m=''3857800''>So</span>
  <span m=''3857920''>I</span> <span m=''3857960''>can</span> <span m=''3858120''>do</span>
  <span m=''3858230''>it</span> <span m=''3858340''>four</span> <span m=''3858620''>[UNINTELLIGIBLE]</span>
  <span m=''3859000''>four.</span> <span m=''3860450''>OK?</span> </p><p><span m=''3861070''>So</span>
  <span m=''3861250''>here''s</span> <span m=''3861540''>something</span> <span m=''3862390''>you</span>
  <span m=''3862550''>found</span> <span m=''3865820''>a</span> <span m=''3866250''>problem</span>
  <span m=''3866630''>that</span> <span m=''3866820''>has</span> <span m=''3867310''>no</span>
  <span m=''3867670''>nice</span> <span m=''3867910''>parallelism.</span> <span m=''3868200''>But
  you</span> <span m=''3868560''>realize</span> <span m=''3869440''>there''s</span>
  <span m=''3869830''>kind</span> <span m=''3870110''>of</span> <span m=''3870210''>a</span>
  <span m=''3870270''>what</span> <span m=''3870490''>you</span> <span m=''3870580''>call</span>
  <span m=''3870840''>a</span> <span m=''3871050''>wavefront</span> <span m=''3871370''>going</span>
  <span m=''3871620''>on</span> <span m=''3871770''>here.</span> <span m=''3872550''>Wave</span>
  <span m=''3872930''>going</span> <span m=''3873200''>on</span> <span m=''3873340''>here.</span>
  <span m=''3873530''>So</span> <span m=''3874350''>not the</span> <span m=''3874660''>given</span>
  <span m=''3874960''>dimension,</span> <span m=''3875340''>but</span> <span m=''3875520''>there''s</span>
  <span m=''3875800''>another</span> <span m=''3876580''>dimension</span> <span m=''3876870''>that</span>
  <span m=''3877010''>you</span> <span m=''3877120''>can</span> <span m=''3877300''>parallel.</span>
  <span m=''3877690''>So</span> <span m=''3877810''>you</span> <span m=''3877910''>kind</span>
  <span m=''3878200''>of</span> <span m=''3878740''>skewed</span> <span m=''3879210''>your</span>
  <span m=''3879330''>space</span> <span m=''3880350''>to</span> <span m=''3880420''>get</span>
  <span m=''3880650''>that</span> <span m=''3880810''>nice</span> <span m=''3881090''>[UNINTELLIGIBLE]</span>
  <span m=''3881260''>line.</span> <span m=''3881690''>And</span> <span m=''3881890''>you
  run</span> <span m=''3882725''>parallel.</span> <span m=''3884210''>So</span> <span
  m=''3885170''>that''s</span> <span m=''3885510''>all</span> <span m=''3885720''>I</span>
  <span m=''3885810''>have</span> <span m=''3886610''>for</span> <span m=''3886800''>today.</span>
  </p>'
uid: ce8bc21d-bf77-22d1-5cf7-63b66e912439
---
