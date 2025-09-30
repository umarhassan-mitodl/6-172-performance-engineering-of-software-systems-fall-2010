---
about_this_resource_text: <p><strong>Description:</strong> Lecture covering analysis
  of multithreaded algorithms, including divide-and-conquer recurrences, loop parallelism
  in Cilk++, and matrix multiplication and merge sort examples.</p> <p><strong>Speaker:</strong>
  Charles Leiserson</p>
content_type: resource
course_id: 6-172-performance-engineering-of-software-systems-fall-2010
embedded_media:
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.172F10/MIT6_172_F10_lec14_300k.mp4
  parent_uid: b10ba5b4b7fe0a47956d67ad505deee1
  title: Video-Internet Archive-MP4
  type: Video
  uid: fdd815ad444c06e899e8554019b6ae6b
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/itunes-u/lecture-14-analysis-multithreaded/id481759887?i=109649116
  parent_uid: b10ba5b4b7fe0a47956d67ad505deee1
  title: Video-iTunes U-MP4
  type: Video
  uid: b512e06a6920218a2c9cb16baebcae86
- id: Video-YouTube-Stream
  media_location: F8yY7jri32M
  parent_uid: b10ba5b4b7fe0a47956d67ad505deee1
  title: Video-YouTube-Stream
  type: Video
  uid: 975cc2614ea2d5d256f8bad7879db0a8
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/F8yY7jri32M/default.jpg
  parent_uid: b10ba5b4b7fe0a47956d67ad505deee1
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e4026ee75e94decc1258591585f72037
- id: MIT6_172F10_lec14.pdf
  parent_uid: b10ba5b4b7fe0a47956d67ad505deee1
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-14-analysis-of-multithreaded-algorithms/MIT6_172F10_lec14.pdf
  title: MIT6_172F10_lec14.pdf
  type: null
  uid: ee70f3488ac70d5e65bdcff6cb7611ba
- id: 3Play-3PlayYouTubeid-MP4
  media_location: F8yY7jri32M
  parent_uid: b10ba5b4b7fe0a47956d67ad505deee1
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 9aa312f0361aa63593e9329832ad3e28
- id: F8yY7jri32M.srt
  parent_uid: b10ba5b4b7fe0a47956d67ad505deee1
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-14-analysis-of-multithreaded-algorithms/F8yY7jri32M.srt
  title: 3play caption file
  type: null
  uid: d86b81911259611c52da2d01f0be98b7
- id: F8yY7jri32M.pdf
  parent_uid: b10ba5b4b7fe0a47956d67ad505deee1
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-14-analysis-of-multithreaded-algorithms/F8yY7jri32M.pdf
  title: 3play pdf file
  type: null
  uid: 71eeef19fd25cc06ee67501ed791c783
- id: Caption-3Play YouTube id-SRT
  parent_uid: b10ba5b4b7fe0a47956d67ad505deee1
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: bb4a17baa2591a8080bc61c13f895c9c
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b10ba5b4b7fe0a47956d67ad505deee1
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 5623d5fa8cb2a0d3b3ff184f4419331c
file: null
file_size: null
hide_download: true
hide_download_original: null
inline_embed_id: 93956577lecture14:analysisofmultithreadedalgorithms68697711
layout: video
license: https://creativecommons.org/licenses/by-nc-sa/4.0/
order_index: 159
parent_uid: 24169d0487e846a39c316276f85b8cb5
related_resources_text: ''
short_url: lecture-14-analysis-of-multithreaded-algorithms
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-14-analysis-of-multithreaded-algorithms
title: 'Lecture 14: Analysis of Multithreaded Algorithms'
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
  <span m=''17780''>ocw.mit.edu.</span> </p><p><span m=''23360''>CHARLES LEISERSON:
  So</span> <span m=''24230''>today,</span> <span m=''24630''>more</span> <span m=''24900''>parallel</span>
  <span m=''25550''>programming,</span> <span m=''26990''>as</span> <span m=''27230''>we</span>
  <span m=''27330''>will</span> <span m=''27470''>do</span> <span m=''27640''>for</span>
  <span m=''29170''>the</span> <span m=''29380''>next</span> <span m=''29590''>couple</span>
  <span m=''29830''>lectures</span> <span m=''30210''>as</span> <span m=''30340''>well.</span>
  <span m=''32170''>So</span> <span m=''32380''>today,</span> <span m=''32689''>we''re</span>
  <span m=''32820''>going</span> <span m=''32930''>to</span> <span m=''33000''>look</span>
  <span m=''33360''>at</span> <span m=''35040''>how</span> <span m=''35270''>to</span>
  <span m=''35500''>analyze</span> <span m=''36570''>multi-threaded</span> <span m=''37640''>algorithms,</span>
  <span m=''39590''>and</span> <span m=''42760''>I''m</span> <span m=''42900''>going</span>
  <span m=''42980''>to</span> <span m=''43020''>start</span> <span m=''43370''>out</span>
  <span m=''43850''>with</span> <span m=''44900''>a</span> <span m=''44970''>review</span>
  <span m=''45470''>of</span> <span m=''45610''>what</span> <span m=''45780''>I</span>
  <span m=''45860''>hope</span> <span m=''46110''>most</span> <span m=''46420''>of</span>
  <span m=''46500''>you</span> <span m=''46630''>know</span> <span m=''49020''>from</span>
  <span m=''49420''>6006</span> <span m=''52090''>or</span> <span m=''52330''>6046,</span>
  <span m=''53470''>which</span> <span m=''53840''>is</span> <span m=''54280''>how</span>
  <span m=''54490''>to</span> <span m=''54570''>solve</span> <span m=''54970''>divide</span>
  <span m=''55300''>and</span> <span m=''55390''>conquer</span> <span m=''55810''>recurrences.</span>
  <span m=''56380''>Now,</span> <span m=''56890''>we</span> <span m=''57120''>know</span>
  <span m=''57340''>that</span> <span m=''57460''>we</span> <span m=''57570''>can</span>
  <span m=''57660''>solve</span> <span m=''57810''>them</span> <span m=''58200''>with</span>
  <span m=''58360''>recursion</span> <span m=''58950''>trees,</span> <span m=''59920''>and</span>
  <span m=''60280''>that</span> <span m=''60560''>gets</span> <span m=''60880''>tedious</span>
  <span m=''61310''>after</span> <span m=''61630''>a</span> <span m=''61690''>while,</span>
  <span m=''62370''>so</span> <span m=''62910''>I</span> <span m=''63040''>want</span>
  <span m=''63270''>to</span> <span m=''63490''>go</span> <span m=''63690''>through</span>
  <span m=''64069''>the</span> <span m=''64180''>so-called</span> <span m=''64680''>Master</span>
  <span m=''65110''>Method</span> <span m=''65540''>to</span> <span m=''65620''>begin</span>
  <span m=''65920''>with,</span> <span m=''66470''>and</span> <span m=''66610''>then</span>
  <span m=''66760''>we''ll</span> <span m=''66900''>get</span> <span m=''67050''>into</span>
  <span m=''67260''>the</span> <span m=''67370''>content</span> <span m=''67960''>of</span>
  <span m=''70200''>the</span> <span m=''70760''>course.</span> <span m=''71680''>But</span>
  <span m=''71920''>it</span> <span m=''72050''>will</span> <span m=''72170''>be</span>
  <span m=''72360''>very</span> <span m=''72600''>helpful,</span> <span m=''72930''>since</span>
  <span m=''73130''>we''re going to</span> <span m=''73260''>do</span> <span m=''73400''>so</span>
  <span m=''73610''>many</span> <span m=''73820''>divide</span> <span m=''74140''>and</span>
  <span m=''74240''>conquer</span> <span m=''74590''>recurrences.</span> </p><p><span
  m=''75650''>The</span> <span m=''75770''>difference</span> <span m=''76190''>between</span>
  <span m=''76540''>these</span> <span m=''76810''>divide</span> <span m=''77110''>and</span>
  <span m=''77230''>conquer</span> <span m=''77660''>recurrences</span> <span m=''78270''>and</span>
  <span m=''78410''>the</span> <span m=''78500''>ones</span> <span m=''78780''>for</span>
  <span m=''78900''>caching</span> <span m=''79850''>is</span> <span m=''80080''>that</span>
  <span m=''80190''>caching</span> <span m=''80770''>is</span> <span m=''80900''>all</span>
  <span m=''81100''>tricky</span> <span m=''81560''>by</span> <span m=''81790''>the</span>
  <span m=''81900''>base</span> <span m=''82220''>condition.</span> <span m=''83270''>Here,</span>
  <span m=''83540''>are</span> <span m=''83640''>all</span> <span m=''83780''>the</span>
  <span m=''83850''>recurrences</span> <span m=''84270''>are</span> <span m=''84400''>going</span>
  <span m=''84490''>to</span> <span m=''84590''>be</span> <span m=''84690''>nice</span>
  <span m=''85010''>and</span> <span m=''85140''>clean,</span> <span m=''86450''>just</span>
  <span m=''86730''>like</span> <span m=''87160''>you</span> <span m=''87350''>learn</span>
  <span m=''87610''>in</span> <span m=''87680''>your</span> <span m=''87810''>algorithms</span>
  <span m=''88280''>class.</span> <span m=''89690''>So</span> <span m=''89920''>we''ll</span>
  <span m=''90040''>start</span> <span m=''90480''>with</span> <span m=''91040''>talking</span>
  <span m=''91410''>about</span> <span m=''91630''>it,</span> <span m=''91760''>and</span>
  <span m=''91880''>then</span> <span m=''92020''>we''ll</span> <span m=''92140''>go</span>
  <span m=''92310''>through</span> <span m=''92690''>several</span> <span m=''93200''>examples</span>
  <span m=''93870''>of</span> <span m=''93970''>analysis</span> <span m=''94620''>of</span>
  <span m=''94870''>algorithms.</span> <span m=''96140''>And</span> <span m=''96400''>it''ll</span>
  <span m=''96560''>also</span> <span m=''96920''>tell</span> <span m=''97200''>us</span>
  <span m=''97350''>something</span> <span m=''97710''>about</span> <span m=''98000''>what</span>
  <span m=''98170''>we</span> <span m=''98270''>need</span> <span m=''98450''>to</span>
  <span m=''98540''>do</span> <span m=''98730''>to</span> <span m=''98810''>make</span>
  <span m=''99610''>our</span> <span m=''100000''>code</span> <span m=''100300''>go</span>
  <span m=''100490''>fast.</span> </p><p><span m=''102290''>So</span> <span m=''102550''>the</span>
  <span m=''102690''>main</span> <span m=''103690''>method</span> <span m=''104070''>we''re</span>
  <span m=''104200''>going</span> <span m=''104260''>to</span> <span m=''104330''>use</span>
  <span m=''104730''>is</span> <span m=''104870''>called</span> <span m=''105110''>the</span>
  <span m=''105170''>Master</span> <span m=''105610''>Method.</span> <span m=''108400''>It''s</span>
  <span m=''108630''>for</span> <span m=''108760''>solving</span> <span m=''109940''>recurrences</span>
  <span m=''110990''>of the</span> <span m=''111460''>form</span> <span m=''111900''>t</span>
  <span m=''112140''>of</span> <span m=''112310''>n</span> <span m=''112490''>equals</span>
  <span m=''112850''>a</span> <span m=''113105''>t</span> <span m=''113360''>of</span>
  <span m=''113450''>n</span> <span m=''113610''>over</span> <span m=''113850''>b</span>
  <span m=''114150''>plus</span> <span m=''114470''>f</span> <span m=''114680''>of
  n,</span> <span m=''116510''>where</span> <span m=''117170''>we</span> <span m=''117290''>have</span>
  <span m=''117450''>some</span> <span m=''117610''>technical</span> <span m=''118100''>conditions,</span>
  <span m=''118730''>a</span> <span m=''119100''>is</span> <span m=''119360''>greater</span>
  <span m=''119590''>than or</span> <span m=''119640''>equal</span> <span m=''119850''>to</span>
  <span m=''119910''>1,</span> <span m=''120276''>b</span> <span m=''121010''>is</span>
  <span m=''121170''>greater</span> <span m=''121480''>than</span> <span m=''121640''>one,</span>
  <span m=''122060''>and</span> <span m=''122230''>f</span> <span m=''122500''>is</span>
  <span m=''122670''>asymptotically</span> <span m=''123360''>positive.</span> <span
  m=''123950''>As</span> <span m=''124990''>f</span> <span m=''125200''>gets</span>
  <span m=''125440''>large,</span> <span m=''125850''>it</span> <span m=''125960''>becomes</span>
  <span m=''126390''>positive.</span> <span m=''128460''>When</span> <span m=''128660''>we</span>
  <span m=''128750''>give</span> <span m=''128970''>a</span> <span m=''129120''>recurrence</span>
  <span m=''129460''>like</span> <span m=''129699''>this,</span> <span m=''130169''>normally</span>
  <span m=''130780''>if</span> <span m=''130910''>the</span> <span m=''131000''>base</span>
  <span m=''131330''>case</span> <span m=''131670''>is</span> <span m=''131820''>order</span>
  <span m=''132120''>one,</span> <span m=''132960''>it''s</span> <span m=''133200''>convention</span>
  <span m=''133760''>not</span> <span m=''134130''>give</span> <span m=''134320''>it,</span>
  <span m=''134730''>to</span> <span m=''134850''>just</span> <span m=''135090''>assume,</span>
  <span m=''135480''>yeah,</span> <span m=''135640''>we</span> <span m=''135780''>understand</span>
  <span m=''136350''>that</span> <span m=''136460''>when</span> <span m=''137510''>n</span>
  <span m=''137710''>is</span> <span m=''137810''>small</span> <span m=''138210''>enough,</span>
  <span m=''139820''>the</span> <span m=''140500''>result</span> <span m=''141210''>is</span>
  <span m=''141330''>constant.</span> <span m=''142670''>As</span> <span m=''142840''>I</span>
  <span m=''142900''>say,</span> <span m=''143100''>that''s</span> <span m=''143400''>the</span>
  <span m=''143490''>place</span> <span m=''143920''>where</span> <span m=''144670''>this</span>
  <span m=''144920''>differs</span> <span m=''145410''>from</span> <span m=''145630''>the</span>
  <span m=''145710''>way</span> <span m=''146080''>that</span> <span m=''146920''>we</span>
  <span m=''147240''>solve</span> <span m=''150970''>recurrences</span> <span m=''151570''>for</span>
  <span m=''151680''>caching,</span> <span m=''152790''>where you</span> <span m=''152960''>have</span>
  <span m=''153150''>to</span> <span m=''153260''>worry</span> <span m=''153560''>about</span>
  <span m=''154220''>what</span> <span m=''154430''>is</span> <span m=''154630''>the</span>
  <span m=''154710''>base</span> <span m=''155010''>case</span> <span m=''155280''>of</span>
  <span m=''155360''>the</span> <span m=''155450''>recurrence.</span> </p><p><span
  m=''158640''>So</span> <span m=''158910''>the</span> <span m=''159000''>way</span>
  <span m=''159130''>to</span> <span m=''159270''>solve</span> <span m=''159590''>this</span>
  <span m=''159790''>is,</span> <span m=''159920''>in</span> <span m=''160030''>fact,</span>
  <span m=''160380''>the</span> <span m=''160450''>way</span> <span m=''160600''>we''ve</span>
  <span m=''160770''>seen</span> <span m=''160960''>before.</span> <span m=''161330''>It''s</span>
  <span m=''161410''>a</span> <span m=''161705''>recursion</span> <span m=''162000''>tree.</span>
  <span m=''162730''>So</span> <span m=''162920''>we</span> <span m=''163010''>start</span>
  <span m=''163310''>with</span> <span m=''163510''>t</span> <span m=''163660''>of</span>
  <span m=''163915''>n,</span> <span m=''164700''>and</span> <span m=''164820''>then</span>
  <span m=''164980''>we</span> <span m=''165110''>replace</span> <span m=''165800''>t</span>
  <span m=''166010''>of</span> <span m=''166080''>n</span> <span m=''166970''>by</span>
  <span m=''167340''>the</span> <span m=''167490''>right</span> <span m=''167730''>hand</span>
  <span m=''168000''>side,</span> <span m=''168460''>just</span> <span m=''168670''>by</span>
  <span m=''168800''>substitution.</span> <span m=''170010''>So</span> <span m=''170290''>what''s</span>
  <span m=''170390''>always</span> <span m=''170830''>going</span> <span m=''170940''>to</span>
  <span m=''170990''>be</span> <span m=''171130''>in</span> <span m=''171230''>the</span>
  <span m=''171320''>tree</span> <span m=''171690''>as</span> <span m=''171810''>we</span>
  <span m=''171930''>develop</span> <span m=''172410''>it</span> <span m=''172590''>is</span>
  <span m=''172770''>the</span> <span m=''172870''>total</span> <span m=''173230''>amount</span>
  <span m=''173500''>of</span> <span m=''173620''>work.</span> <span m=''176150''>So</span>
  <span m=''176500''>we</span> <span m=''176730''>basically</span> <span m=''177220''>replace</span>
  <span m=''177630''>it</span> <span m=''177750''>by</span> <span m=''177920''>f</span>
  <span m=''178180''>of</span> <span m=''178310''>n</span> <span m=''178750''>plus</span>
  <span m=''179080''>a</span> <span m=''179330''>copies</span> <span m=''179870''>of</span>
  <span m=''179980''>t</span> <span m=''180180''>of</span> <span m=''180280''>n</span>
  <span m=''180390''>over</span> <span m=''180610''>b.</span> <span m=''182410''>And</span>
  <span m=''182510''>then</span> <span m=''182660''>each</span> <span m=''182840''>of</span>
  <span m=''182930''>those</span> <span m=''184410''>we</span> <span m=''184580''>replace</span>
  <span m=''185160''>by</span> <span m=''186410''>a</span> <span m=''186630''>copies</span>
  <span m=''187310''>so</span> <span m=''188150''>t</span> <span m=''188400''>of</span>
  <span m=''188500''>n</span> <span m=''188650''>over</span> <span m=''188870''>b</span>
  <span m=''189040''>squared.</span> <span m=''191280''>And</span> <span m=''191440''>so</span>
  <span m=''191660''>forth,</span> <span m=''193270''>continually</span> <span m=''193900''>replacing</span>
  <span m=''194420''>until</span> <span m=''194520''>we</span> <span m=''194620''>get</span>
  <span m=''194830''>down</span> <span m=''195080''>to</span> <span m=''195190''>t</span>
  <span m=''195420''>of</span> <span m=''195550''>1.</span> <span m=''195980''>And
  at the</span> <span m=''196210''>point</span> <span m=''196420''>t</span> <span
  m=''196630''>of 1,</span> <span m=''196920''>we</span> <span m=''197030''>no</span>
  <span m=''197200''>longer can</span> <span m=''197700''>substitute</span> <span
  m=''198130''>here,</span> <span m=''198680''>but</span> <span m=''198820''>we</span>
  <span m=''198940''>know</span> <span m=''199160''>that</span> <span m=''199350''>t</span>
  <span m=''199540''>of</span> <span m=''199640''>1</span> <span m=''199900''>is</span>
  <span m=''200040''>order</span> <span m=''200300''>1.</span> </p><p><span m=''202340''>And</span>
  <span m=''202490''>now</span> <span m=''202780''>what we</span> <span m=''202920''>do</span>
  <span m=''203100''>is</span> <span m=''203670''>add</span> <span m=''203890''>across</span>
  <span m=''204190''>the</span> <span m=''204490''>rows.</span> <span m=''205560''>So
  we</span> <span m=''205640''>get</span> <span m=''205830''>f</span> <span m=''206020''>of</span>
  <span m=''206510''>n,</span> <span m=''206890''>we</span> <span m=''207000''>get</span>
  <span m=''207220''>a,</span> <span m=''207540''>f</span> <span m=''207730''>of n</span>
  <span m=''208000''>over</span> <span m=''208230''>b,</span> <span m=''209440''>a</span>
  <span m=''209660''>squared</span> <span m=''210100''>f of</span> <span m=''210350''>n</span>
  <span m=''210510''>over</span> <span m=''210740''>b</span> <span m=''210960''>squared,</span>
  <span m=''212440''>and</span> <span m=''212820''>we</span> <span m=''212950''>keep</span>
  <span m=''213220''>going</span> <span m=''213850''>to</span> <span m=''213950''>the</span>
  <span m=''214040''>height</span> <span m=''214540''>of</span> <span m=''214740''>this,</span>
  <span m=''215110''>which</span> <span m=''216000''>we''re</span> <span m=''216150''>dividing</span>
  <span m=''216610''>by</span> <span m=''217370''>the</span> <span m=''217530''>argument</span>
  <span m=''217990''>by</span> <span m=''218160''>b</span> <span m=''218490''>each</span>
  <span m=''218710''>time.</span> <span m=''219050''>So to</span> <span m=''219250''>get</span>
  <span m=''219450''>down</span> <span m=''219710''>to</span> <span m=''219810''>1</span>
  <span m=''220570''>is</span> <span m=''220730''>just</span> <span m=''220940''>log</span>
  <span m=''221270''>base</span> <span m=''221580''>b</span> <span m=''221800''>of</span>
  <span m=''221880''>n.</span> <span m=''224440''>So</span> <span m=''225590''>the</span>
  <span m=''225750''>number</span> <span m=''226070''>of</span> <span m=''226150''>leaves</span>
  <span m=''226940''>is,</span> <span m=''227330''>since</span> <span m=''227520''>this</span>
  <span m=''227700''>is</span> <span m=''228170''>a</span> <span m=''228420''>regular</span>
  <span m=''230200''>[? a area ?]</span> <span m=''230680''>tree,</span> <span m=''231590''>is</span>
  <span m=''231960''>a</span> <span m=''232280''>to</span> <span m=''232410''>the</span>
  <span m=''232500''>height,</span> <span m=''232970''>which</span> <span m=''233170''>is</span>
  <span m=''233330''>a</span> <span m=''233550''>to</span> <span m=''233620''>the</span>
  <span m=''233690''>log</span> <span m=''233980''>base</span> <span m=''234260''>b</span>
  <span m=''234440''>of</span> <span m=''234530''>n.</span> <span m=''234880''>And</span>
  <span m=''235080''>for</span> <span m=''235260''>each</span> <span m=''235520''>of</span>
  <span m=''235630''>those,</span> <span m=''236370''>we''re</span> <span m=''236510''>paying</span>
  <span m=''237290''>t of</span> <span m=''237520''>1,</span> <span m=''238010''>which</span>
  <span m=''238170''>is</span> <span m=''238290''>order</span> <span m=''238610''>1.</span>
  </p><p><span m=''240840''>And</span> <span m=''240990''>so</span> <span m=''241160''>now,</span>
  <span m=''242430''>it</span> <span m=''242610''>turns</span> <span m=''242890''>out</span>
  <span m=''243090''>there''s</span> <span m=''243270''>no</span> <span m=''243470''>closed</span>
  <span m=''243920''>form</span> <span m=''244220''>solution.</span> <span m=''244740''>If</span>
  <span m=''244870''>I</span> <span m=''245000''>add</span> <span m=''245250''>up</span>
  <span m=''245420''>all</span> <span m=''245630''>these</span> <span m=''245860''>terms,</span>
  <span m=''246310''>there''s</span> <span m=''246480''>no</span> <span m=''246650''>closed</span>
  <span m=''247030''>form</span> <span m=''247320''>solution.</span> <span m=''248790''>But</span>
  <span m=''249160''>there</span> <span m=''249340''>are</span> <span m=''249380''>three</span>
  <span m=''249790''>common</span> <span m=''250610''>situations</span> <span m=''251390''>that</span>
  <span m=''251490''>occur</span> <span m=''251780''>in</span> <span m=''251880''>practice.</span>
  <span m=''254020''>So</span> <span m=''254200''>yes,</span> <span m=''254480''>this</span>
  <span m=''254670''>is</span> <span m=''254790''>just</span> <span m=''255010''>n
  to the</span> <span m=''255280''>log</span> <span m=''255590''>base</span> <span
  m=''256029''>b of a,</span> <span m=''256769''>just</span> <span m=''257000''>this</span>
  <span m=''257170''>term,</span> <span m=''258649''>not</span> <span m=''258860''>the</span>
  <span m=''258940''>sum,</span> <span m=''259430''>just</span> <span m=''259600''>this</span>
  <span m=''259690''>term.</span> <span m=''262210''>So</span> <span m=''262830''>three</span>
  <span m=''263060''>cases</span> <span m=''263720''>have</span> <span m=''264080''>to</span>
  <span m=''264210''>do</span> <span m=''264360''>with</span> <span m=''264540''>comparing</span>
  <span m=''266010''>the</span> <span m=''266120''>number</span> <span m=''266520''>of</span>
  <span m=''266600''>leaves,</span> <span m=''268370''>which</span> <span m=''268600''>is</span>
  <span m=''269160''>times</span> <span m=''269440''>order</span> <span m=''269590''>1,</span>
  <span m=''270440''>with</span> <span m=''270670''>f</span> <span m=''270880''>of
  n.</span> <span m=''273880''>So</span> <span m=''274480''>the</span> <span m=''274630''>first</span>
  <span m=''275030''>case</span> <span m=''275860''>is</span> <span m=''276050''>the</span>
  <span m=''276140''>case</span> <span m=''276540''>where</span> <span m=''278020''>n</span>
  <span m=''278250''>the</span> <span m=''278360''>log</span> <span m=''278660''>base</span>
  <span m=''278980''>b</span> <span m=''279150''>of</span> <span m=''279240''>a</span>
  <span m=''279450''>is</span> <span m=''279760''>bigger</span> <span m=''280130''>than</span>
  <span m=''280320''>f</span> <span m=''280470''>of</span> <span m=''280750''>n.</span>
  <span m=''282170''>So</span> <span m=''282440''>whenever</span> <span m=''282800''>you''re
  given</span> <span m=''283030''>a recurrence to</span> <span m=''283400''>compute</span>
  <span m=''284070''>n</span> <span m=''284250''>to the</span> <span m=''284430''>log</span>
  <span m=''284710''>base</span> <span m=''285010''>b of a--</span> <span m=''285480''>I</span>
  <span m=''285530''>hope</span> <span m=''285710''>this</span> <span m=''285880''>is</span>
  <span m=''285990''>repeat</span> <span m=''286400''>for</span> <span m=''286530''>most</span>
  <span m=''286800''>people.</span> <span m=''288010''>If</span> <span m=''288210''>not,</span>
  <span m=''289070''>that''s</span> <span m=''289320''>fine,</span> <span m=''289600''>but</span>
  <span m=''289740''>hopefully</span> <span m=''290100''>it''ll</span> <span m=''290240''>get</span>
  <span m=''290450''>you</span> <span m=''292720''>caught</span> <span m=''293050''>up.</span>
  <span m=''293990''>n</span> <span m=''294210''>log</span> <span m=''294480''>base
  b of</span> <span m=''294930''>a,</span> <span m=''295300''>if</span> <span m=''295440''>it''s</span>
  <span m=''295580''>much</span> <span m=''295770''>bigger</span> <span m=''296150''>than</span>
  <span m=''296510''>f of n,</span> <span m=''297540''>then</span> <span m=''298020''>these</span>
  <span m=''298310''>terms</span> <span m=''298730''>are</span> <span m=''299320''>geometrically</span>
  <span m=''299990''>increasing.</span> </p><p><span m=''301080''>And</span> <span
  m=''301550''>since</span> <span m=''301820''>it''s</span> <span m=''301950''>geometrically</span>
  <span m=''302520''>increasing,</span> <span m=''303020''>all</span> <span m=''303260''>that</span>
  <span m=''303420''>matters</span> <span m=''303930''>is</span> <span m=''304290''>the</span>
  <span m=''304500''>base</span> <span m=''304850''>case.</span> <span m=''305630''>In</span>
  <span m=''305750''>fact,</span> <span m=''306030''>actually,</span> <span m=''306430''>it</span>
  <span m=''306640''>has</span> <span m=''306900''>to</span> <span m=''307000''>be</span>
  <span m=''307600''>not</span> <span m=''307820''>just</span> <span m=''308070''>greater</span>
  <span m=''308440''>than,</span> <span m=''308790''>it''s</span> <span m=''308970''>got</span>
  <span m=''309120''>to</span> <span m=''309170''>be</span> <span m=''309270''>greater</span>
  <span m=''309640''>than</span> <span m=''309870''>by</span> <span m=''310010''>a</span>
  <span m=''310090''>polynomial</span> <span m=''310800''>amount,</span> <span m=''311210''>by</span>
  <span m=''311320''>some</span> <span m=''311590''>n to</span> <span m=''311930''>the</span>
  <span m=''312060''>epsilon</span> <span m=''312570''>amount</span> <span m=''312970''>for</span>
  <span m=''313100''>some</span> <span m=''313320''>epsilon</span> <span m=''313880''>greater</span>
  <span m=''314170''>than</span> <span m=''314340''>0.</span> <span m=''315200''>So</span>
  <span m=''315340''>it</span> <span m=''315410''>might</span> <span m=''315630''>be</span>
  <span m=''315860''>n</span> <span m=''316090''>to</span> <span m=''316210''>the</span>
  <span m=''316840''>1/2,</span> <span m=''317500''>it</span> <span m=''317650''>might</span>
  <span m=''317920''>be</span> <span m=''318320''>n to</span> <span m=''318670''>the</span>
  <span m=''319650''>1/3,</span> <span m=''320330''>it</span> <span m=''320480''>could</span>
  <span m=''320640''>be</span> <span m=''320820''>n</span> <span m=''321080''>to</span>
  <span m=''321210''>the</span> <span m=''321620''>100th.</span> <span m=''323510''>But</span>
  <span m=''323780''>what</span> <span m=''323940''>it</span> <span m=''324080''>can''t</span>
  <span m=''324470''>be</span> <span m=''325190''>is</span> <span m=''326710''>log</span>
  <span m=''327100''>n,</span> <span m=''327580''>because</span> <span m=''327790''>log</span>
  <span m=''328100''>n</span> <span m=''328270''>is</span> <span m=''328400''>less</span>
  <span m=''328760''>than</span> <span m=''328900''>any</span> <span m=''329320''>polynomial</span>
  <span m=''329940''>amount.</span> <span m=''331590''>So</span> <span m=''331740''>it''s</span>
  <span m=''331860''>got</span> <span m=''332010''>to</span> <span m=''332110''>exceed
  it</span> <span m=''332580''>by</span> <span m=''332750''>at</span> <span m=''332820''>least</span>
  <span m=''333580''>n to the</span> <span m=''333710''>epsilon</span> <span m=''334220''>for</span>
  <span m=''334330''>some</span> <span m=''334570''>epsilon.</span> <span m=''335830''>In</span>
  <span m=''335970''>that</span> <span m=''336200''>case,</span> <span m=''336590''>it''s</span>
  <span m=''336780''>geometrically</span> <span m=''337340''>increasing,</span> <span
  m=''337880''>the</span> <span m=''338010''>answer is</span> <span m=''338500''>just</span>
  <span m=''338740''>what''s</span> <span m=''338860''>at the</span> <span m=''338980''>leaves.</span>
  <span m=''340550''>So</span> <span m=''340820''>that''s</span> <span m=''341080''>case</span>
  <span m=''341390''>one,</span> <span m=''341720''>geometrically</span> <span m=''342370''>increasing.</span>
  </p><p><span m=''344270''>Case</span> <span m=''344680''>two</span> <span m=''345580''>is</span>
  <span m=''345830''>when</span> <span m=''346080''>things</span> <span m=''346450''>are</span>
  <span m=''347020''>actually</span> <span m=''347370''>fairly</span> <span m=''347800''>equal</span>
  <span m=''348210''>on</span> <span m=''348370''>every</span> <span m=''348610''>level.</span>
  <span m=''350670''>And</span> <span m=''351330''>the</span> <span m=''351670''>general</span>
  <span m=''352070''>case</span> <span m=''352580''>we''ll</span> <span m=''352690''>look</span>
  <span m=''352870''>at</span> <span m=''353030''>is</span> <span m=''353180''>when</span>
  <span m=''353520''>it''s</span> <span m=''353680''>arithmetically</span> <span m=''354330''>increasing.</span>
  <span m=''356500''>So</span> <span m=''357930''>in</span> <span m=''358100''>particular,</span>
  <span m=''360890''>this</span> <span m=''361080''>occurs</span> <span m=''361510''>when</span>
  <span m=''361660''>f</span> <span m=''361860''>of n</span> <span m=''362280''>is</span>
  <span m=''362540''>n to</span> <span m=''362850''>the</span> <span m=''362910''>log</span>
  <span m=''363200''>base</span> <span m=''363520''>b</span> <span m=''363700''>of</span>
  <span m=''363800''>a</span> <span m=''364590''>times</span> <span m=''364970''>log</span>
  <span m=''366070''>to</span> <span m=''366170''>some</span> <span m=''366410''>power,</span>
  <span m=''366860''>n,</span> <span m=''367390''>for</span> <span m=''367790''>some</span>
  <span m=''368000''>constant</span> <span m=''368530''>k</span> <span m=''369000''>that''s</span>
  <span m=''369210''>at</span> <span m=''369260''>least</span> <span m=''369570''>0.</span>
  <span m=''372080''>So</span> <span m=''372240''>this</span> <span m=''372420''>is</span>
  <span m=''372540''>the</span> <span m=''372630''>situation.</span> <span m=''373450''>If</span>
  <span m=''373680''>k</span> <span m=''373940''>is</span> <span m=''374070''>equal</span>
  <span m=''374440''>to</span> <span m=''374490''>0,</span> <span m=''375270''>it</span>
  <span m=''375400''>just</span> <span m=''375630''>says</span> <span m=''376020''>that</span>
  <span m=''376500''>f</span> <span m=''376670''>of n,</span> <span m=''377700''>the</span>
  <span m=''377800''>amount</span> <span m=''378080''>here</span> <span m=''378460''>is</span>
  <span m=''378560''>exactly</span> <span m=''379090''>the</span> <span m=''379180''>same</span>
  <span m=''379470''>as</span> <span m=''379580''>the</span> <span m=''379670''>number</span>
  <span m=''379930''>of</span> <span m=''379990''>leaves.</span> <span m=''382420''>And</span>
  <span m=''382570''>that</span> <span m=''382900''>case,</span> <span m=''383190''>it</span>
  <span m=''383310''>turns</span> <span m=''383590''>out</span> <span m=''383830''>that</span>
  <span m=''383900''>every</span> <span m=''384150''>level</span> <span m=''384530''>has</span>
  <span m=''384680''>almost</span> <span m=''384960''>exactly</span> <span m=''385520''>the</span>
  <span m=''385600''>same</span> <span m=''385880''>amount.</span> <span m=''386960''>And</span>
  <span m=''387150''>since</span> <span m=''387370''>there are</span> <span m=''387510''>log
  n</span> <span m=''388010''>levels,</span> <span m=''388470''>you</span> <span m=''388610''>tack</span>
  <span m=''388970''>on</span> <span m=''389160''>an</span> <span m=''389260''>extra</span>
  <span m=''389610''>log n</span> <span m=''390160''>for</span> <span m=''390270''>the</span>
  <span m=''390360''>solution.</span> <span m=''391300''>In fact,</span> <span m=''391500''>the</span>
  <span m=''391570''>solution</span> <span m=''391960''>is</span> <span m=''392080''>one</span>
  <span m=''392250''>more</span> <span m=''392450''>log.</span> </p><p><span m=''393050''>Turns</span>
  <span m=''393310''>out</span> <span m=''393510''>that</span> <span m=''393610''>if</span>
  <span m=''393730''>it''s</span> <span m=''393920''>growing</span> <span m=''395060''>arithmetically</span>
  <span m=''396920''>with</span> <span m=''397260''>layer,</span> <span m=''398590''>you</span>
  <span m=''398720''>basically</span> <span m=''399400''>take</span> <span m=''399700''>on</span>
  <span m=''399930''>one</span> <span m=''400220''>extra</span> <span m=''400600''>log.</span>
  <span m=''401400''>It''s</span> <span m=''401590''>actually</span> <span m=''401900''>like</span>
  <span m=''402180''>doing</span> <span m=''403440''>the</span> <span m=''403940''>integral</span>
  <span m=''404500''>of</span> <span m=''404660''>a</span> <span m=''405120''>as</span>
  <span m=''405320''>an</span> <span m=''405490''>arithmetic</span> <span m=''406080''>series.</span>
  <span m=''406430''>If</span> <span m=''406510''>you''re</span> <span m=''409080''>adding</span>
  <span m=''409410''>the</span> <span m=''409530''>terms</span> <span m=''410130''>of,</span>
  <span m=''410410''>say,</span> <span m=''410830''>i</span> <span m=''411050''>squared,</span>
  <span m=''411810''>the</span> <span m=''412000''>result</span> <span m=''412500''>is</span>
  <span m=''412630''>i</span> <span m=''412770''>cubed.</span> <span m=''416000''>If</span>
  <span m=''416430''>you</span> <span m=''416510''>have</span> <span m=''416600''>a</span>
  <span m=''416650''>summation</span> <span m=''417260''>that</span> <span m=''417410''>goes</span>
  <span m=''417720''>from</span> <span m=''418050''>i</span> <span m=''418260''>equals</span>
  <span m=''418560''>1</span> <span m=''418810''>to</span> <span m=''418890''>n</span>
  <span m=''419660''>of</span> <span m=''419840''>i</span> <span m=''420030''>squared,</span>
  <span m=''421360''>the</span> <span m=''421480''>result</span> <span m=''421900''>is</span>
  <span m=''422230''>proportional</span> <span m=''422920''>to</span> <span m=''423070''>n</span>
  <span m=''423350''>cubed.</span> <span m=''424640''>And</span> <span m=''424790''>similarly,</span>
  <span m=''425390''>if</span> <span m=''425520''>it''s</span> <span m=''428490''>i</span>
  <span m=''428790''>to</span> <span m=''429130''>any</span> <span m=''429340''>k,</span>
  <span m=''430460''>the</span> <span m=''430660''>result</span> <span m=''431100''>is</span>
  <span m=''431210''>going</span> <span m=''431290''>to</span> <span m=''431380''>be</span>
  <span m=''432970''>n</span> <span m=''433310''>to</span> <span m=''433580''>the</span>
  <span m=''433750''>k</span> <span m=''433980''>plus</span> <span m=''434290''>1,</span>
  <span m=''434920''>and</span> <span m=''435060''>that''s</span> <span m=''435270''>basically</span>
  <span m=''435690''>what''s</span> <span m=''435920''>going</span> <span m=''436180''>on</span>
  <span m=''436350''>here.</span> </p><p><span m=''438450''>And</span> <span m=''438590''>then</span>
  <span m=''438750''>the</span> <span m=''438830''>third</span> <span m=''439200''>case</span>
  <span m=''440080''>is</span> <span m=''440330''>when</span> <span m=''440500''>it''s</span>
  <span m=''440660''>geometrically</span> <span m=''441320''>decreasing,</span> <span
  m=''442260''>when</span> <span m=''442430''>the</span> <span m=''442500''>amount</span>
  <span m=''442800''>at</span> <span m=''442910''>the</span> <span m=''443000''>root</span>
  <span m=''443300''>dominates.</span> <span m=''446860''>So</span> <span m=''447600''>in</span>
  <span m=''447770''>this</span> <span m=''448000''>case,</span> <span m=''448470''>if</span>
  <span m=''449030''>it''s</span> <span m=''449430''>much</span> <span m=''449740''>less</span>
  <span m=''450040''>than</span> <span m=''450190''>n,</span> <span m=''450420''>and</span>
  <span m=''450550''>specifically,</span> <span m=''453960''>f</span> <span m=''454340''>of</span>
  <span m=''454520''>n</span> <span m=''454720''>is</span> <span m=''455070''>at</span>
  <span m=''455200''>least</span> <span m=''457940''>n to</span> <span m=''458190''>the</span>
  <span m=''458360''>epsilon</span> <span m=''458890''>less</span> <span m=''459310''>than</span>
  <span m=''459840''>log</span> <span m=''460160''>base</span> <span m=''460610''>b
  of a,</span> <span m=''461970''>for</span> <span m=''462120''>some</span> <span
  m=''462330''>constant</span> <span m=''462750''>epsilon,</span> <span m=''464670''>it</span>
  <span m=''464800''>turns</span> <span m=''465030''>out</span> <span m=''465180''>in</span>
  <span m=''465380''>addition,</span> <span m=''465810''>you</span> <span m=''465930''>need</span>
  <span m=''466080''>f</span> <span m=''466230''>of</span> <span m=''466340''>n</span>
  <span m=''466570''>to</span> <span m=''466650''>satisfy</span> <span m=''466945''>a</span>
  <span m=''467240''>regularity</span> <span m=''467950''>condition,</span> <span
  m=''468410''>but</span> <span m=''468550''>this</span> <span m=''468680''>regularity</span>
  <span m=''469260''>condition</span> <span m=''469710''>is</span> <span m=''469790''>satisfied</span>
  <span m=''470370''>by</span> <span m=''470510''>all</span> <span m=''470810''>the</span>
  <span m=''470920''>normal</span> <span m=''471960''>functions</span> <span m=''472370''>that</span>
  <span m=''472470''>we''re</span> <span m=''472610''>going</span> <span m=''472700''>to</span>
  <span m=''472760''>come</span> <span m=''473010''>up.</span> <span m=''473300''>It''s</span>
  <span m=''473490''>not</span> <span m=''475820''>satisfied</span> <span m=''476480''>by</span>
  <span m=''476640''>things</span> <span m=''477040''>like</span> <span m=''477370''>n
  to</span> <span m=''477770''>the</span> <span m=''477880''>sine n,</span> <span
  m=''479930''>which</span> <span m=''480110''>oscillates</span> <span m=''480760''>like</span>
  <span m=''480920''>crazy.</span> <span m=''482150''>But</span> <span m=''483330''>it</span>
  <span m=''483530''>also</span> <span m=''483780''>isn''t</span> <span m=''484030''>satisfied</span>
  <span m=''484610''>by</span> <span m=''484750''>exponentially</span> <span m=''485390''>growing</span>
  <span m=''486010''>functions.</span> <span m=''486800''>But</span> <span m=''486990''>it</span>
  <span m=''487100''>is</span> <span m=''487250''>satisfied</span> <span m=''487830''>by</span>
  <span m=''487940''>anything</span> <span m=''488200''>that''s</span> <span m=''488350''>polynomial,</span>
  <span m=''488800''>or</span> <span m=''489150''>polynomial</span> <span m=''489720''>times</span>
  <span m=''490000''>a</span> <span m=''490060''>logarithm,</span> <span m=''490910''>or</span>
  <span m=''491110''>what</span> <span m=''491270''>have</span> <span m=''491460''>you.</span>
  <span m=''492580''>So</span> <span m=''492940''>generally,</span> <span m=''493740''>we</span>
  <span m=''493850''>don''t</span> <span m=''494040''>really</span> <span m=''494260''>have</span>
  <span m=''494450''>to</span> <span m=''494560''>check</span> <span m=''494830''>this</span>
  <span m=''494990''>too</span> <span m=''495160''>carefully.</span> </p><p><span
  m=''496820''>And</span> <span m=''497080''>then</span> <span m=''497610''>the</span>
  <span m=''497910''>answer</span> <span m=''498220''>there</span> <span m=''498540''>is</span>
  <span m=''498660''>just</span> <span m=''498900''>it''s</span> <span m=''499010''>order</span>
  <span m=''499340''>f of</span> <span m=''499560''>n,</span> <span m=''499850''>because
  it''s</span> <span m=''500240''>geometrically</span> <span m=''500890''>decreasing,</span>
  <span m=''502040''>f</span> <span m=''502220''>of</span> <span m=''502390''>n</span>
  <span m=''502560''>dominates.</span> <span m=''504530''>So is</span> <span m=''504710''>this</span>
  <span m=''504880''>review</span> <span m=''505210''>for</span> <span m=''505360''>everybody?</span>
  <span m=''506890''>Pretty</span> <span m=''507080''>much,</span> <span m=''507550''>yeah,</span>
  <span m=''507870''>yeah,</span> <span m=''508040''>yeah?</span> <span m=''508920''>You</span>
  <span m=''509040''>can</span> <span m=''509130''>do</span> <span m=''509240''>this</span>
  <span m=''509420''>in</span> <span m=''509470''>your</span> <span m=''509580''>head,</span>
  <span m=''511210''>because</span> <span m=''511420''>we''re</span> <span m=''511510''>going</span>
  <span m=''511590''>to</span> <span m=''511630''>ask</span> <span m=''511870''>you</span>
  <span m=''511960''>to</span> <span m=''512070''>do</span> <span m=''512260''>this</span>
  <span m=''512450''>in</span> <span m=''512539''>your</span> <span m=''512659''>head</span>
  <span m=''513490''>during</span> <span m=''513700''>the</span> <span m=''513760''>lecture?</span>
  <span m=''515195''>Yeah,</span> <span m=''515610''>we''re</span> <span m=''515770''>all</span>
  <span m=''515890''>good?</span> <span m=''516110''>OK,</span> <span m=''516470''>good.</span>
  </p><p><span m=''518940''>One</span> <span m=''519240''>of</span> <span m=''519360''>the</span>
  <span m=''520460''>things</span> <span m=''520720''>that</span> <span m=''520940''>students,</span>
  <span m=''521470''>when</span> <span m=''521700''>they</span> <span m=''521840''>learn</span>
  <span m=''522130''>this</span> <span m=''522299''>in an</span> <span m=''522500''>algorithms</span>
  <span m=''523000''>class,</span> <span m=''523380''>don''t</span> <span m=''523740''>recognize</span>
  <span m=''524930''>is that</span> <span m=''525010''>this</span> <span m=''525200''>also</span>
  <span m=''525500''>tells</span> <span m=''525980''>you</span> <span m=''526450''>where</span>
  <span m=''527040''>in</span> <span m=''527120''>your</span> <span m=''527320''>program,</span>
  <span m=''527830''>where in</span> <span m=''528120''>your</span> <span m=''528260''>recursive</span>
  <span m=''528760''>program,</span> <span m=''529260''>you</span> <span m=''529470''>should</span>
  <span m=''529720''>bother</span> <span m=''530920''>to</span> <span m=''531040''>try</span>
  <span m=''531310''>to</span> <span m=''531450''>eke</span> <span m=''531740''>out</span>
  <span m=''532100''>constant</span> <span m=''532600''>factors.</span> <span m=''535570''>So</span>
  <span m=''535710''>if</span> <span m=''535770''>you</span> <span m=''535880''>think</span>
  <span m=''536110''>about</span> <span m=''536400''>it,</span> <span m=''536490''>for</span>
  <span m=''536570''>example,</span> <span m=''536940''>in</span> <span m=''537030''>case</span>
  <span m=''537400''>three</span> <span m=''537690''>here,</span> <span m=''538210''>it''s</span>
  <span m=''538510''>geometrically</span> <span m=''539380''>decreasing.</span> <span
  m=''540290''>Does</span> <span m=''540470''>it</span> <span m=''540580''>make</span>
  <span m=''540850''>sense</span> <span m=''541160''>to</span> <span m=''541280''>try</span>
  <span m=''541490''>to</span> <span m=''541570''>optimize</span> <span m=''543000''>the</span>
  <span m=''543120''>leaves?</span> <span m=''545530''>No,</span> <span m=''546030''>because</span>
  <span m=''546220''>very</span> <span m=''546470''>little</span> <span m=''546810''>time</span>
  <span m=''547070''>is</span> <span m=''547140''>spent there.</span> <span m=''547510''>It</span>
  <span m=''547650''>makes</span> <span m=''547880''>sense to</span> <span m=''548190''>optimize</span>
  <span m=''549960''>what''s</span> <span m=''550220''>going</span> <span m=''550430''>on</span>
  <span m=''550620''>at</span> <span m=''550720''>the root,</span> <span m=''552420''>and</span>
  <span m=''552550''>to</span> <span m=''552620''>save</span> <span m=''553030''>anything</span>
  <span m=''553390''>you</span> <span m=''553540''>can</span> <span m=''554460''>at</span>
  <span m=''554630''>the</span> <span m=''554700''>root.</span> <span m=''554850''>And</span>
  <span m=''554950''>sometimes,</span> <span m=''555460''>the</span> <span m=''555570''>root</span>
  <span m=''555870''>in</span> <span m=''556050''>particular</span> <span m=''556590''>has</span>
  <span m=''556800''>special</span> <span m=''557250''>properties</span> <span m=''558230''>that</span>
  <span m=''558380''>aren''t</span> <span m=''558690''>true</span> <span m=''558980''>of</span>
  <span m=''559080''>the</span> <span m=''559310''>internal</span> <span m=''559750''>nodes
  that</span> <span m=''560070''>you</span> <span m=''560140''>can</span> <span m=''560250''>take</span>
  <span m=''560470''>advantage</span> <span m=''560970''>of,</span> <span m=''562080''>that</span>
  <span m=''562210''>you</span> <span m=''562290''>may</span> <span m=''562410''>not</span>
  <span m=''562640''>be</span> <span m=''562760''>able</span> <span m=''562870''>to</span>
  <span m=''562950''>take</span> <span m=''563160''>advantage</span> <span m=''563620''>of</span>
  <span m=''563780''>regularly.</span> <span m=''564360''>But</span> <span m=''564530''>since</span>
  <span m=''564720''>it''s</span> <span m=''564840''>going</span> <span m=''564900''>to</span>
  <span m=''564960''>be</span> <span m=''565040''>dominated</span> <span m=''565530''>by</span>
  <span m=''565690''>the</span> <span m=''565810''>root,</span> <span m=''566200''>trying</span>
  <span m=''566390''>to</span> <span m=''566580''>save in</span> <span m=''567020''>the</span>
  <span m=''567110''>root</span> <span m=''567730''>makes</span> <span m=''567980''>sense.</span>
  </p><p><span m=''568340''>Correspondingly,</span> <span m=''568655''>if</span> <span
  m=''568970''>we''re</span> <span m=''569250''>in</span> <span m=''569530''>case</span>
  <span m=''569840''>one,</span> <span m=''573860''>in</span> <span m=''574110''>case</span>
  <span m=''574410''>one,</span> <span m=''575350''>it''s</span> <span m=''575540''>absolutely</span>
  <span m=''576110''>critical</span> <span m=''576750''>that you</span> <span m=''576950''>coarsen</span>
  <span m=''577370''>the</span> <span m=''577440''>recursion,</span> <span m=''579610''>because</span>
  <span m=''579810''>all</span> <span m=''580180''>the</span> <span m=''580270''>work</span>
  <span m=''580690''>is</span> <span m=''580910''>down</span> <span m=''581200''>at</span>
  <span m=''581290''>this</span> <span m=''581490''>level.</span> <span m=''584420''>And</span>
  <span m=''584560''>so</span> <span m=''584690''>if</span> <span m=''584750''>you</span>
  <span m=''584890''>want</span> <span m=''585050''>to</span> <span m=''585090''>get</span>
  <span m=''585920''>additional</span> <span m=''586410''>performance,</span> <span
  m=''587250''>you</span> <span m=''587430''>want</span> <span m=''587650''>to</span>
  <span m=''588140''>basically</span> <span m=''588650''>move</span> <span m=''588920''>this</span>
  <span m=''589120''>up</span> <span m=''589280''>high</span> <span m=''589550''>enough</span>
  <span m=''589960''>that</span> <span m=''590140''>you</span> <span m=''590280''>can</span>
  <span m=''590420''>cut</span> <span m=''590660''>off</span> <span m=''590980''>that</span>
  <span m=''591230''>constant</span> <span m=''591680''>amount</span> <span m=''593210''>and</span>
  <span m=''593450''>get</span> <span m=''594530''>factors</span> <span m=''594980''>two,</span>
  <span m=''595240''>three,</span> <span m=''595540''>sometimes</span> <span m=''596020''>more,</span>
  <span m=''597280''>out</span> <span m=''597520''>of</span> <span m=''597690''>your</span>
  <span m=''598280''>code.</span> <span m=''600820''>So</span> <span m=''601480''>understanding</span>
  <span m=''603040''>the</span> <span m=''603450''>structure</span> <span m=''604140''>of</span>
  <span m=''604390''>the</span> <span m=''604610''>recursion</span> <span m=''605360''>allows</span>
  <span m=''605830''>you</span> <span m=''606070''>to</span> <span m=''606200''>figure</span>
  <span m=''606510''>out</span> <span m=''606730''>where</span> <span m=''607010''>it</span>
  <span m=''607090''>is</span> <span m=''607310''>that</span> <span m=''607450''>you</span>
  <span m=''607550''>should</span> <span m=''607740''>optimize</span> <span m=''608360''>your</span>
  <span m=''608910''>code.</span> <span m=''609165''>Of</span> <span m=''609420''>course,</span>
  <span m=''609660''>with loops,</span> <span m=''610110''>it''s</span> <span m=''610270''>much</span>
  <span m=''610500''>easier.</span> <span m=''610870''>Where</span> <span m=''611040''>do</span>
  <span m=''611100''>you</span> <span m=''611190''>spend</span> <span m=''611460''>your</span>
  <span m=''611570''>time</span> <span m=''611850''>with</span> <span m=''611980''>loops</span>
  <span m=''613302''>to</span> <span m=''613720''>make</span> <span m=''613960''>code</span>
  <span m=''614210''>go</span> <span m=''614360''>fast?</span> <span m=''617520''>The</span>
  <span m=''617960''>innermost</span> <span m=''619020''>loop,</span> <span m=''619310''>right,</span>
  <span m=''620440''>because</span> <span m=''620630''>that''s</span> <span m=''620850''>the</span>
  <span m=''620940''>one</span> <span m=''621090''>that''s</span> <span m=''621250''>executing</span>
  <span m=''621830''>the</span> <span m=''621910''>most.</span> <span m=''622790''>The</span>
  <span m=''622920''>outer</span> <span m=''623230''>loops</span> <span m=''623520''>are</span>
  <span m=''623600''>not</span> <span m=''623890''>that</span> <span m=''624070''>important.</span>
  <span m=''625230''>This</span> <span m=''625500''>is</span> <span m=''625650''>sort</span>
  <span m=''625910''>of</span> <span m=''625990''>the</span> <span m=''626090''>corresponding</span>
  <span m=''626830''>thing</span> <span m=''627090''>for</span> <span m=''627360''>recursion.</span>
  <span m=''628840''>Figure</span> <span m=''629200''>out</span> <span m=''629440''>where</span>
  <span m=''629780''>the</span> <span m=''630010''>recursion is</span> <span m=''630440''>spending</span>
  <span m=''630820''>the</span> <span m=''630940''>time,</span> <span m=''631240''>that''s</span>
  <span m=''631490''>where</span> <span m=''631670''>you</span> <span m=''632240''>spend</span>
  <span m=''632580''>time</span> <span m=''632820''>eking</span> <span m=''633230''>out</span>
  <span m=''633340''>extra</span> <span m=''633640''>factors.</span> </p><p><span
  m=''638550''>Here''s</span> <span m=''638830''>the</span> <span m=''638940''>cheat</span>
  <span m=''639190''>sheet.</span> <span m=''643010''>So</span> <span m=''643970''>if</span>
  <span m=''644170''>it''s</span> <span m=''645220''>n to</span> <span m=''645510''>the</span>
  <span m=''645700''>log</span> <span m=''645980''>base</span> <span m=''646240''>b</span>
  <span m=''646380''>of</span> <span m=''646470''>a</span> <span m=''646780''>minus</span>
  <span m=''647010''>epsilon,</span> <span m=''647820''>the</span> <span m=''647920''>answer''s</span>
  <span m=''648210''>n to the</span> <span m=''648410''>log</span> <span m=''648700''>base</span>
  <span m=''648930''>b of</span> <span m=''649060''>a.</span> <span m=''649505''>If</span>
  <span m=''649910''>it''s</span> <span m=''650040''>plus</span> <span m=''650350''>epsilon,</span>
  <span m=''650870''>it''s</span> <span m=''651090''>f of</span> <span m=''651210''>n.</span>
  <span m=''652020''>And</span> <span m=''652180''>if</span> <span m=''652290''>it''s</span>
  <span m=''652640''>n to the</span> <span m=''653010''>log</span> <span m=''653260''>base</span>
  <span m=''653530''>b</span> <span m=''653730''>of</span> <span m=''653850''>a</span>
  <span m=''654070''>times</span> <span m=''654390''>a</span> <span m=''654440''>logarithmic</span>
  <span m=''655030''>factor,</span> <span m=''655850''>where</span> <span m=''656030''>this</span>
  <span m=''656220''>logarithm</span> <span m=''657170''>has</span> <span m=''657580''>the</span>
  <span m=''657780''>exponent</span> <span m=''658530''>greater</span> <span m=''658810''>than
  or</span> <span m=''658940''>equal</span> <span m=''659200''>to</span> <span m=''659250''>0,</span>
  <span m=''660020''>you</span> <span m=''660140''>add</span> <span m=''660310''>a</span>
  <span m=''660370''>1.</span> <span m=''662140''>This</span> <span m=''662330''>is</span>
  <span m=''662470''>not</span> <span m=''662800''>all</span> <span m=''663120''>of</span>
  <span m=''663200''>the</span> <span m=''663990''>situations.</span> <span m=''664340''>There</span>
  <span m=''664690''>are</span> <span m=''664880''>situations</span> <span m=''665920''>which</span>
  <span m=''666210''>don''t</span> <span m=''666660''>occur.</span> </p><p><span m=''666935''>OK,</span>
  <span m=''667210''>quick</span> <span m=''667410''>quiz.</span> <span m=''670380''>So</span>
  <span m=''670750''>t</span> <span m=''670980''>of</span> <span m=''671060''>n</span>
  <span m=''671210''>equals</span> <span m=''671490''>4t</span> <span m=''671980''>of</span>
  <span m=''672060''>n</span> <span m=''672210''>over</span> <span m=''672410''>2</span>
  <span m=''672630''>plus</span> <span m=''673040''>n.</span> <span m=''673390''>What''s</span>
  <span m=''673560''>the</span> <span m=''673730''>solution?</span> <span m=''677550''>n</span>
  <span m=''677800''>squared,</span> <span m=''678290''>good.</span> <span m=''679730''>So</span>
  <span m=''679940''>this</span> <span m=''680160''>is</span> <span m=''680310''>n
  to</span> <span m=''680560''>the</span> <span m=''680690''>log</span> <span m=''680970''>base</span>
  <span m=''681260''>b</span> <span m=''681420''>of</span> <span m=''681480''>a,</span>
  <span m=''682070''>is n to the</span> <span m=''682320''>log</span> <span m=''682660''>base</span>
  <span m=''682950''>2</span> <span m=''683170''>of</span> <span m=''683260''>4,</span>
  <span m=''684080''>which</span> <span m=''684310''>is</span> <span m=''684430''>n</span>
  <span m=''684610''>squared.</span> <span m=''685910''>That''s</span> <span m=''686130''>much</span>
  <span m=''686360''>bigger</span> <span m=''686630''>than</span> <span m=''686790''>n.</span>
  <span m=''687260''>It''s</span> <span m=''687710''>bigger</span> <span m=''687950''>by
  a</span> <span m=''688160''>factor</span> <span m=''688450''>of n.</span> <span
  m=''689230''>Here,</span> <span m=''689380''>the</span> <span m=''689560''>epsilon</span>
  <span m=''690050''>of</span> <span m=''690170''>1</span> <span m=''690450''>would</span>
  <span m=''690640''>do,</span> <span m=''691160''>so</span> <span m=''691390''>would
  an</span> <span m=''691520''>epsilon</span> <span m=''691930''>of</span> <span m=''692050''>1/2</span>
  <span m=''692430''>or an</span> <span m=''692570''>epsilon</span> <span m=''692930''>of</span>
  <span m=''693010''>1/4,</span> <span m=''693400''>but</span> <span m=''693990''>in</span>
  <span m=''694100''>particular,</span> <span m=''694490''>an</span> <span m=''694580''>epsilon</span>
  <span m=''694990''>of</span> <span m=''695080''>1</span> <span m=''695310''>would</span>
  <span m=''695500''>do.</span> <span m=''696050''>That''s</span> <span m=''696310''>case</span>
  <span m=''696640''>one.</span> <span m=''697430''>The</span> <span m=''697720''>n</span>
  <span m=''697850''>squared</span> <span m=''698250''>dominates,</span> <span m=''698820''>so</span>
  <span m=''698910''>the</span> <span m=''699060''>answer</span> <span m=''699360''>is</span>
  <span m=''699470''>n</span> <span m=''699620''>squared.</span> <span m=''700590''>The</span>
  <span m=''700660''>basic</span> <span m=''700990''>idea is</span> <span m=''701300''>whichever</span>
  <span m=''701670''>side</span> <span m=''702010''>dominates</span> <span m=''702920''>for</span>
  <span m=''703030''>case</span> <span m=''703330''>one and</span> <span m=''703590''>case</span>
  <span m=''703890''>three,</span> <span m=''704170''>that''s</span> <span m=''704470''>the</span>
  <span m=''704550''>one</span> <span m=''704730''>that</span> <span m=''704950''>is</span>
  <span m=''705140''>the</span> <span m=''705330''>answer.</span> </p><p><span m=''707700''>Here</span>
  <span m=''707850''>we</span> <span m=''707960''>go.</span> <span m=''708150''>What
  about</span> <span m=''708450''>this</span> <span m=''708620''>one?</span> <span
  m=''710650''>n</span> <span m=''710920''>squared</span> <span m=''711290''>log</span>
  <span m=''711630''>n,</span> <span m=''712310''>because</span> <span m=''712630''>the</span>
  <span m=''712740''>two</span> <span m=''712950''>sides</span> <span m=''714000''>are</span>
  <span m=''714170''>about</span> <span m=''714370''>the</span> <span m=''714570''>same</span>
  <span m=''714850''>size.</span> <span m=''716950''>It''s</span> <span m=''717180''>n</span>
  <span m=''717660''>squared</span> <span m=''718150''>times</span> <span m=''718390''>log
  to</span> <span m=''718710''>the</span> <span m=''718780''>0n,</span> <span m=''719640''>tack</span>
  <span m=''719950''>on</span> <span m=''720080''>the</span> <span m=''720210''>extra</span>
  <span m=''720500''>log.</span> <span m=''722240''>How</span> <span m=''722370''>about</span>
  <span m=''722570''>this</span> <span m=''722750''>one?</span> <span m=''724120''>n</span>
  <span m=''724460''>cubed.</span> <span m=''725180''>How</span> <span m=''725310''>about</span>
  <span m=''725520''>this</span> <span m=''725690''>one?</span> </p><p><span m=''729403''>AUDIENCE:
  [INAUDIBLE].</span> <span m=''731399''>Master</span> <span m=''731898''>Theorem</span>
  <span m=''732397''>[INAUDIBLE]?</span> </p><p><span m=''734900''>CHARLES LEISERSON:
  Yeah,</span> <span m=''735760''>the Master</span> <span m=''736150''>Theorem</span>
  <span m=''736430''>does</span> <span m=''736580''>not</span> <span m=''736780''>apply</span>
  <span m=''737140''>to</span> <span m=''737230''>this</span> <span m=''737430''>one.</span>
  <span m=''738790''>It</span> <span m=''738940''>looks</span> <span m=''739240''>like</span>
  <span m=''739450''>it''s</span> <span m=''739640''>case</span> <span m=''740010''>two</span>
  <span m=''740770''>with an</span> <span m=''741150''>an</span> <span m=''741250''>exponent</span>
  <span m=''741750''>of</span> <span m=''742620''>minus</span> <span m=''743070''>1,</span>
  <span m=''744780''>but</span> <span m=''745270''>that''s</span> <span m=''745610''>bogus</span>
  <span m=''746030''>because</span> <span m=''746310''>the</span> <span m=''746430''>exponent</span>
  <span m=''747330''>of</span> <span m=''747500''>the</span> <span m=''747580''>log</span>
  <span m=''748010''>must</span> <span m=''748360''>be</span> <span m=''749510''>greater</span>
  <span m=''749820''>than</span> <span m=''749880''>or</span> <span m=''749920''>equal</span>
  <span m=''750170''>to</span> <span m=''750220''>0.</span> <span m=''752280''>So</span>
  <span m=''752580''>instead,</span> <span m=''753170''>this</span> <span m=''753330''>actually</span>
  <span m=''753630''>has</span> <span m=''753800''>a</span> <span m=''753860''>solution,</span>
  <span m=''754910''>so</span> <span m=''755050''>it</span> <span m=''755140''>does</span>
  <span m=''755320''>not</span> <span m=''755510''>apply,</span> <span m=''756360''>it</span>
  <span m=''756490''>actually</span> <span m=''756780''>has</span> <span m=''756920''>the</span>
  <span m=''757010''>solution</span> <span m=''757470''>n</span> <span m=''757690''>squared,</span>
  <span m=''758370''>log</span> <span m=''758820''>log</span> <span m=''759180''>n,</span>
  <span m=''760750''>but</span> <span m=''760920''>that''s</span> <span m=''761160''>not</span>
  <span m=''761370''>covered</span> <span m=''761680''>by</span> <span m=''761820''>the</span>
  <span m=''761920''>Master</span> <span m=''762370''>Theorem.</span> <span m=''763320''>You</span>
  <span m=''763500''>can</span> <span m=''763710''>have</span> <span m=''764070''>an</span>
  <span m=''764350''>infinite</span> <span m=''764800''>hierarchy</span> <span m=''765913''>of</span>
  <span m=''766640''>narrowing</span> <span m=''767250''>in</span> <span m=''767780''>things.</span>
  </p><p><span m=''768840''>So</span> <span m=''768960''>if</span> <span m=''769180''>you</span>
  <span m=''769320''>don''t</span> <span m=''769630''>have</span> <span m=''770140''>a</span>
  <span m=''770870''>solution</span> <span m=''771750''>to</span> <span m=''771870''>something</span>
  <span m=''772210''>that</span> <span m=''772330''>looks</span> <span m=''772560''>like</span>
  <span m=''772730''>a</span> <span m=''772790''>Master</span> <span m=''773860''>Theorem</span>
  <span m=''774420''>type</span> <span m=''774680''>of</span> <span m=''774830''>recurrence,</span>
  <span m=''775810''>what''s</span> <span m=''776250''>your</span> <span m=''776410''>best</span>
  <span m=''776650''>strategy</span> <span m=''777200''>for</span> <span m=''777320''>solving</span>
  <span m=''777730''>it?</span> </p><p><span m=''779782''>AUDIENCE: [INAUDIBLE].</span>
  </p><p><span m=''780750''>CHARLES LEISERSON: What''s</span> <span m=''781150''>that?</span>
  </p><p><span m=''783260''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''784840''>CHARLES
  LEISERSON: So</span> <span m=''785165''>a recursion tree can</span> <span m=''785490''>be</span>
  <span m=''785580''>good,</span> <span m=''785860''>but</span> <span m=''785970''>actually,</span>
  <span m=''786390''>the</span> <span m=''786490''>best</span> <span m=''786870''>is</span>
  <span m=''786970''>the</span> <span m=''787050''>substitution</span> <span m=''787710''>method,</span>
  <span m=''788960''>basically</span> <span m=''789410''>proving</span> <span m=''789760''>it</span>
  <span m=''789880''>by</span> <span m=''790030''>induction.</span> <span m=''791090''>And</span>
  <span m=''791230''>the</span> <span m=''791300''>recursion</span> <span m=''791600''>tree</span>
  <span m=''791980''>can</span> <span m=''792110''>be</span> <span m=''792540''>very</span>
  <span m=''792840''>helpful</span> <span m=''793620''>in</span> <span m=''793850''>giving</span>
  <span m=''794090''>you</span> <span m=''794250''>a</span> <span m=''794320''>good</span>
  <span m=''794550''>guess</span> <span m=''795610''>for</span> <span m=''795710''>what</span>
  <span m=''795870''>you</span> <span m=''795980''>think</span> <span m=''796280''>the</span>
  <span m=''796420''>answer</span> <span m=''796810''>is.</span> <span m=''798070''>But</span>
  <span m=''798170''>the</span> <span m=''798250''>most</span> <span m=''798510''>reliable</span>
  <span m=''798990''>way</span> <span m=''799100''>to</span> <span m=''799220''>prove</span>
  <span m=''799450''>any</span> <span m=''799670''>of</span> <span m=''799740''>these</span>
  <span m=''800000''>things</span> <span m=''800310''>is</span> <span m=''801170''>using</span>
  <span m=''801830''>substitution</span> <span m=''802340''>method.</span> <span m=''803900''>Good</span>
  <span m=''804040''>enough.</span> <span m=''805270''>So</span> <span m=''805420''>that</span>
  <span m=''805590''>was</span> <span m=''805700''>review</span> <span m=''806060''>for,</span>
  <span m=''806390''>I</span> <span m=''806490''>hope,</span> <span m=''806750''>most</span>
  <span m=''806980''>people?</span> <span m=''808590''>Yeah?</span> <span m=''808820''>OK,</span>
  <span m=''809120''>good.</span> </p><p><span m=''810580''>OK,</span> <span m=''810870''>let''s</span>
  <span m=''811120''>talk</span> <span m=''811350''>about</span> <span m=''811780''>parallel</span>
  <span m=''812120''>programming.</span> <span m=''812510''>We''re</span> <span m=''812560''>going
  to</span> <span m=''812760''>start</span> <span m=''813060''>out</span> <span m=''813230''>with</span>
  <span m=''813360''>loops.</span> <span m=''814550''>So</span> <span m=''815020''>last</span>
  <span m=''815580''>time,</span> <span m=''815830''>we</span> <span m=''816000''>talked</span>
  <span m=''816280''>about</span> <span m=''816500''>how</span> <span m=''816770''>the</span>
  <span m=''817460''>cilk++</span> <span m=''818360''>runtime</span> <span m=''818920''>system</span>
  <span m=''819800''>is</span> <span m=''820040''>based</span> <span m=''821090''>on,</span>
  <span m=''822560''>essentially,</span> <span m=''823010''>implementing</span> <span
  m=''823530''>spawns</span> <span m=''824270''>and</span> <span m=''824520''>syncs,</span>
  <span m=''826430''>using</span> <span m=''826770''>the</span> <span m=''826860''>work</span>
  <span m=''827120''>stealing</span> <span m=''827560''>algorithm,</span> <span m=''828130''>and</span>
  <span m=''828220''>we</span> <span m=''828320''>talked</span> <span m=''828570''>about</span>
  <span m=''828820''>scheduling</span> <span m=''829400''>and</span> <span m=''829510''>so</span>
  <span m=''829720''>forth.</span> <span m=''831660''>We</span> <span m=''832060''>didn''t</span>
  <span m=''832250''>talk</span> <span m=''832480''>about</span> <span m=''832680''>how</span>
  <span m=''832880''>loops</span> <span m=''833230''>are</span> <span m=''833350''>implemented,</span>
  <span m=''835490''>except</span> <span m=''835830''>to</span> <span m=''835920''>mention</span>
  <span m=''836240''>that</span> <span m=''836380''>they</span> <span m=''836470''>were</span>
  <span m=''836610''>implemented</span> <span m=''837110''>with</span> <span m=''837240''>divide</span>
  <span m=''837610''>and</span> <span m=''837700''>conquer.</span> <span m=''838580''>So</span>
  <span m=''838710''>here</span> <span m=''838970''>I</span> <span m=''838990''>want</span>
  <span m=''839190''>to</span> <span m=''839230''>go</span> <span m=''839450''>into</span>
  <span m=''840530''>the</span> <span m=''840730''>subtleties</span> <span m=''841320''>of</span>
  <span m=''841420''>loops,</span> <span m=''841840''>because</span> <span m=''842160''>probably</span>
  <span m=''842800''>most</span> <span m=''843230''>programs</span> <span m=''844680''>that</span>
  <span m=''845380''>occur</span> <span m=''845730''>in</span> <span m=''845810''>the</span>
  <span m=''845900''>real</span> <span m=''846170''>world</span> <span m=''846540''>these</span>
  <span m=''846770''>days</span> <span m=''847380''>are</span> <span m=''848090''>programs</span>
  <span m=''848710''>where</span> <span m=''848880''>people</span> <span m=''849160''>just</span>
  <span m=''849350''>simply</span> <span m=''849650''>say,</span> <span m=''851500''>make</span>
  <span m=''851730''>this</span> <span m=''851880''>a</span> <span m=''851930''>parallel</span>
  <span m=''852340''>loop.</span> <span m=''853800''>That''s</span> <span m=''854110''>it.</span>
  </p><p><span m=''855830''>So</span> <span m=''855990''>let''s</span> <span m=''856200''>take</span>
  <span m=''856470''>an</span> <span m=''856540''>example</span> <span m=''857330''>of</span>
  <span m=''857590''>the</span> <span m=''857760''>in-place</span> <span m=''858360''>matrix</span>
  <span m=''858780''>transpose,</span> <span m=''861730''>where</span> <span m=''862160''>we''re</span>
  <span m=''862370''>basically</span> <span m=''863560''>trying</span> <span m=''863710''>to</span>
  <span m=''863870''>flip</span> <span m=''864150''>everything</span> <span m=''864510''>along</span>
  <span m=''864810''>the</span> <span m=''864880''>main</span> <span m=''865110''>diagonal.</span>
  <span m=''866660''>I''ve</span> <span m=''866810''>used</span> <span m=''867090''>this</span>
  <span m=''867290''>figure</span> <span m=''867560''>before,</span> <span m=''868455''>I
  think.</span> <span m=''871030''>So</span> <span m=''872010''>let''s</span> <span
  m=''872300''>just</span> <span m=''872560''>do</span> <span m=''872730''>it</span>
  <span m=''872940''>not</span> <span m=''873310''>cache</span> <span m=''873720''>efficiently.</span>
  <span m=''874860''>So</span> <span m=''875010''>the</span> <span m=''875090''>cache</span>
  <span m=''875430''>efficient</span> <span m=''875840''>algorithm</span> <span m=''876240''>actually</span>
  <span m=''876540''>parallelizes</span> <span m=''877350''>beautifully</span> <span
  m=''877880''>also,</span> <span m=''879160''>but</span> <span m=''879380''>let''s</span>
  <span m=''879630''>not</span> <span m=''879800''>look</span> <span m=''879980''>at</span>
  <span m=''880050''>the</span> <span m=''881690''>cache</span> <span m=''881990''>efficient</span>
  <span m=''882500''>version,</span> <span m=''882870''>the</span> <span m=''882950''>divide</span>
  <span m=''883350''>and</span> <span m=''883685''>conquer version.</span> <span m=''884020''>Let''s</span>
  <span m=''884240''>look</span> <span m=''884480''>at</span> <span m=''885310''>a</span>
  <span m=''885870''>looping</span> <span m=''886250''>version</span> <span m=''886670''>to</span>
  <span m=''886790''>understand.</span> <span m=''888010''>And</span> <span m=''889660''>once</span>
  <span m=''889960''>again</span> <span m=''890230''>here,</span> <span m=''890520''>as</span>
  <span m=''890670''>I</span> <span m=''890800''>did</span> <span m=''891010''>before,</span>
  <span m=''891470''>I''m going to</span> <span m=''891590''>make</span> <span m=''891840''>the</span>
  <span m=''891940''>indices</span> <span m=''892490''>for</span> <span m=''892610''>my</span>
  <span m=''892820''>implementation</span> <span m=''893470''>run</span> <span m=''893650''>from</span>
  <span m=''893840''>0,</span> <span m=''894150''>not</span> <span m=''894460''>1.</span>
  <span m=''896430''>And</span> <span m=''896580''>basically,</span> <span m=''897020''>I
  have</span> <span m=''897210''>an</span> <span m=''897310''>outer</span> <span m=''897660''>loop</span>
  <span m=''898160''>that</span> <span m=''898340''>goes</span> <span m=''898620''>from</span>
  <span m=''898830''>i</span> <span m=''899070''>equals</span> <span m=''899420''>1</span>
  <span m=''901030''>up</span> <span m=''901250''>to</span> <span m=''901370''>n</span>
  <span m=''901550''>minus</span> <span m=''901940''>1,</span> <span m=''902730''>and</span>
  <span m=''904230''>an</span> <span m=''904400''>inner</span> <span m=''904630''>loop</span>
  <span m=''904940''>that</span> <span m=''905100''>goes</span> <span m=''905420''>from</span>
  <span m=''905740''>j</span> <span m=''906690''>equals</span> <span m=''907120''>0</span>
  <span m=''908020''>up</span> <span m=''908210''>to</span> <span m=''908430''>i</span>
  <span m=''908650''>minus</span> <span m=''909040''>1.</span> <span m=''909990''>And</span>
  <span m=''910230''>then</span> <span m=''911260''>I</span> <span m=''911410''>do</span>
  <span m=''911650''>a</span> <span m=''912020''>little</span> <span m=''912210''>swap</span>
  <span m=''913000''>in</span> <span m=''913160''>there.</span> <span m=''915850''>And</span>
  <span m=''917200''>in</span> <span m=''917410''>here,</span> <span m=''919700''>the</span>
  <span m=''919870''>outer</span> <span m=''920070''>loop</span> <span m=''920310''>I''ve</span>
  <span m=''920410''>parallelized,</span> <span m=''921220''>the</span> <span m=''921380''>inner</span>
  <span m=''921590''>loop</span> <span m=''923600''>is</span> <span m=''923770''>running</span>
  <span m=''924040''>serially.</span> </p><p><span m=''931600''>So</span> <span m=''931790''>let''s</span>
  <span m=''932020''>take</span> <span m=''932220''>a</span> <span m=''932290''>look</span>
  <span m=''932680''>at</span> <span m=''932820''>analyzing</span> <span m=''933870''>this</span>
  <span m=''934250''>particular</span> <span m=''934810''>piece</span> <span m=''935110''>of</span>
  <span m=''935210''>code</span> <span m=''936420''>to</span> <span m=''936540''>understand</span>
  <span m=''937180''>what''s</span> <span m=''937420''>going</span> <span m=''937670''>on.</span>
  <span m=''937900''>So</span> <span m=''938070''>the</span> <span m=''938160''>way</span>
  <span m=''938480''>this</span> <span m=''938680''>actually</span> <span m=''939060''>gets</span>
  <span m=''939320''>implemented</span> <span m=''941300''>is</span> <span m=''941820''>as</span>
  <span m=''942030''>follows.</span> <span m=''942380''>So</span> <span m=''942470''>here''s</span>
  <span m=''942760''>the</span> <span m=''942840''>code</span> <span m=''943130''>on</span>
  <span m=''943270''>the</span> <span m=''943360''>left.</span> <span m=''944830''>What</span>
  <span m=''944990''>actually</span> <span m=''945400''>happens</span> <span m=''946930''>in</span>
  <span m=''947180''>the</span> <span m=''950210''>cilk++</span> <span m=''951790''>compiler</span>
  <span m=''952920''>is</span> <span m=''953130''>it</span> <span m=''953240''>converts</span>
  <span m=''953790''>it</span> <span m=''953930''>into</span> <span m=''954360''>recursion,</span>
  <span m=''955870''>divide</span> <span m=''956220''>and</span> <span m=''956350''>conquer</span>
  <span m=''956730''>recursion.</span> <span m=''958210''>So</span> <span m=''958360''>what</span>
  <span m=''958480''>it</span> <span m=''958640''>does</span> <span m=''959020''>is</span>
  <span m=''959360''>it</span> <span m=''959780''>has</span> <span m=''960100''>a</span>
  <span m=''960150''>range</span> <span m=''960980''>from</span> <span m=''961170''>low</span>
  <span m=''961400''>to</span> <span m=''961470''>high,</span> <span m=''961970''>is</span>
  <span m=''962160''>sort</span> <span m=''962340''>of</span> <span m=''962400''>the</span>
  <span m=''962470''>common</span> <span m=''962880''>case.</span> <span m=''963840''>We''re</span>
  <span m=''964010''>going</span> <span m=''964090''>to</span> <span m=''964160''>call</span>
  <span m=''964560''>it</span> <span m=''964750''>on</span> <span m=''965160''>from</span>
  <span m=''965340''>1</span> <span m=''965570''>to</span> <span m=''965640''>n</span>
  <span m=''965820''>minus</span> <span m=''966150''>1,</span> <span m=''966380''>because</span>
  <span m=''966570''>that''s</span> <span m=''966920''>the</span> <span m=''967510''>indexes</span>
  <span m=''967950''>that I''ve</span> <span m=''968230''>given</span> <span m=''968670''>to</span>
  <span m=''969250''>the</span> <span m=''969350''>cilk_for</span> <span m=''969570''>loop.</span>
  <span m=''971300''>And</span> <span m=''971490''>what</span> <span m=''971650''>we</span>
  <span m=''971770''>do</span> <span m=''972190''>is,</span> <span m=''973130''>if</span>
  <span m=''973440''>I</span> <span m=''973570''>have</span> <span m=''974140''>a</span>
  <span m=''974800''>region</span> <span m=''975940''>to</span> <span m=''976970''>do</span>
  <span m=''977110''>divide and</span> <span m=''977530''>conquer</span> <span m=''977865''>on,</span>
  <span m=''978980''>a</span> <span m=''979020''>set</span> <span m=''979280''>of</span>
  <span m=''980620''>values</span> <span m=''981090''>for</span> <span m=''981240''>i,</span>
  <span m=''982110''>I</span> <span m=''982230''>basically</span> <span m=''982760''>divide</span>
  <span m=''983250''>that</span> <span m=''983960''>in</span> <span m=''984100''>half.</span>
  <span m=''986760''>And</span> <span m=''986950''>then</span> <span m=''987140''>I</span>
  <span m=''987610''>recursively</span> <span m=''989870''>execute</span> <span m=''990560''>the</span>
  <span m=''991170''>first</span> <span m=''991510''>half,</span> <span m=''992240''>and</span>
  <span m=''992420''>then</span> <span m=''992560''>the</span> <span m=''992640''>second</span>
  <span m=''993010''>half,</span> <span m=''993370''>and</span> <span m=''993600''>then</span>
  <span m=''993800''>cilk_sync.</span> <span m=''994740''>So</span> <span m=''994930''>the</span>
  <span m=''995030''>two</span> <span m=''995240''>sides</span> <span m=''995670''>are</span>
  <span m=''995730''>going</span> <span m=''996030''>off</span> <span m=''996280''>in</span>
  <span m=''996410''>parallel.</span> </p><p><span m=''997790''>And</span> <span m=''998020''>then</span>
  <span m=''998260''>if</span> <span m=''998470''>I</span> <span m=''999310''>am</span>
  <span m=''999520''>at</span> <span m=''999650''>the</span> <span m=''999730''>base,</span>
  <span m=''1000520''>then</span> <span m=''1000970''>I</span> <span m=''1001170''>go</span>
  <span m=''1001430''>through</span> <span m=''1001830''>the</span> <span m=''1002200''>inner</span>
  <span m=''1002450''>loop</span> <span m=''1003370''>and</span> <span m=''1003680''>do</span>
  <span m=''1003800''>the</span> <span m=''1003930''>swap</span> <span m=''1004640''>of</span>
  <span m=''1004850''>the</span> <span m=''1005360''>values</span> <span m=''1005540''>in</span>
  <span m=''1005640''>the</span> <span m=''1005760''>inner</span> <span m=''1005940''>loop.</span>
  <span m=''1008260''>So</span> <span m=''1008410''>the</span> <span m=''1008540''>outer</span>
  <span m=''1008820''>loop</span> <span m=''1009440''>is</span> <span m=''1009620''>the</span>
  <span m=''1009690''>one</span> <span m=''1009860''>that''s</span> <span m=''1010040''>the</span>
  <span m=''1010120''>parallel</span> <span m=''1010620''>loop.</span> <span m=''1011100''>That</span>
  <span m=''1011360''>one</span> <span m=''1012050''>we''re</span> <span m=''1012190''>doing</span>
  <span m=''1012430''>divide</span> <span m=''1012800''>and</span> <span m=''1012870''>conquer</span>
  <span m=''1013350''>on.</span> <span m=''1014450''>So</span> <span m=''1014630''>we</span>
  <span m=''1014750''>basically</span> <span m=''1015360''>recursively</span> <span
  m=''1016480''>spawn</span> <span m=''1017430''>the</span> <span m=''1017650''>first</span>
  <span m=''1017880''>half,</span> <span m=''1018550''>execute</span> <span m=''1018990''>the</span>
  <span m=''1019060''>second,</span> <span m=''1019500''>and</span> <span m=''1019600''>then</span>
  <span m=''1019770''>each</span> <span m=''1019980''>of</span> <span m=''1020070''>those</span>
  <span m=''1021500''>recursively</span> <span m=''1022680''>does</span> <span m=''1022890''>the</span>
  <span m=''1022960''>same</span> <span m=''1023250''>thing</span> <span m=''1026690''>until</span>
  <span m=''1027079''>all</span> <span m=''1027200''>the</span> <span m=''1027319''>iterations</span>
  <span m=''1027800''>have</span> <span m=''1027890''>been</span> <span m=''1028050''>done.</span>
  <span m=''1028680''>Any</span> <span m=''1028829''>questions</span> <span m=''1029240''>about</span>
  <span m=''1029480''>how</span> <span m=''1029680''>that</span> <span m=''1029849''>operates?</span>
  <span m=''1034069''>So</span> <span m=''1034200''>this</span> <span m=''1034349''>is</span>
  <span m=''1034490''>the</span> <span m=''1034569''>way</span> <span m=''1034740''>all</span>
  <span m=''1035119''>the</span> <span m=''1035740''>parallel</span> <span m=''1036160''>loops</span>
  <span m=''1036420''>are</span> <span m=''1036500''>done,</span> <span m=''1036790''>is</span>
  <span m=''1036940''>basically</span> <span m=''1037460''>this</span> <span m=''1037569''>strategy.</span>
  </p><p><span m=''1038560''>Now</span> <span m=''1038710''>here,</span> <span m=''1038960''>I</span>
  <span m=''1039020''>mention</span> <span m=''1039410''>that</span> <span m=''1039599''>this</span>
  <span m=''1039819''>is</span> <span m=''1040130''>in</span> <span m=''1040329''>fact</span>
  <span m=''1040869''>what</span> <span m=''1041000''>happens</span> <span m=''1041440''>is</span>
  <span m=''1041609''>this</span> <span m=''1042349''>test</span> <span m=''1042660''>here
  is</span> <span m=''1042940''>actually</span> <span m=''1043230''>coarsened.</span>
  <span m=''1045589''>So</span> <span m=''1046430''>we</span> <span m=''1046550''>don''t</span>
  <span m=''1046780''>want</span> <span m=''1046920''>to</span> <span m=''1046970''>go</span>
  <span m=''1047210''>all</span> <span m=''1047490''>the</span> <span m=''1047579''>way</span>
  <span m=''1047770''>to</span> <span m=''1047960''>n</span> <span m=''1048130''>equals</span>
  <span m=''1048450''>1,</span> <span m=''1048740''>because</span> <span m=''1049000''>then</span>
  <span m=''1049150''>we''ll</span> <span m=''1049300''>have</span> <span m=''1049610''>this</span>
  <span m=''1049790''>recursion</span> <span m=''1050360''>call</span> <span m=''1050690''>overhead</span>
  <span m=''1051670''>every</span> <span m=''1051990''>time</span> <span m=''1052320''>we</span>
  <span m=''1052420''>do</span> <span m=''1052600''>a</span> <span m=''1052660''>call.</span>
  <span m=''1053280''>So</span> <span m=''1053440''>in</span> <span m=''1053530''>fact,</span>
  <span m=''1053860''>what</span> <span m=''1054230''>happens</span> <span m=''1054620''>is</span>
  <span m=''1054720''>you</span> <span m=''1054820''>go</span> <span m=''1055010''>down</span>
  <span m=''1055270''>to</span> <span m=''1055370''>some</span> <span m=''1055590''>grain</span>
  <span m=''1055960''>size</span> <span m=''1059120''>of</span> <span m=''1059720''>some</span>
  <span m=''1059990''>number</span> <span m=''1060270''>of</span> <span m=''1060340''>iterations,</span>
  <span m=''1062110''>and</span> <span m=''1062380''>at</span> <span m=''1062600''>that</span>
  <span m=''1062800''>number</span> <span m=''1063030''>of</span> <span m=''1063365''>iterations,</span>
  <span m=''1063700''>it</span> <span m=''1063930''>then</span> <span m=''1064160''>just</span>
  <span m=''1064420''>runs</span> <span m=''1064730''>through</span> <span m=''1064940''>it</span>
  <span m=''1065030''>as</span> <span m=''1065260''>an</span> <span m=''1065320''>ordinary</span>
  <span m=''1065790''>serial</span> <span m=''1066200''>four</span> <span m=''1066490''>loop,</span>
  <span m=''1068370''>in</span> <span m=''1068510''>order</span> <span m=''1068760''>not</span>
  <span m=''1069080''>to</span> <span m=''1069170''>pay</span> <span m=''1069370''>the</span>
  <span m=''1069460''>function</span> <span m=''1069830''>call</span> <span m=''1070140''>overhead</span>
  <span m=''1071060''>all</span> <span m=''1071270''>the</span> <span m=''1071340''>way</span>
  <span m=''1071490''>down.</span> <span m=''1071830''>We''re</span> <span m=''1071970''>going</span>
  <span m=''1072050''>to</span> <span m=''1072090''>look</span> <span m=''1072310''>exactly</span>
  <span m=''1072820''>at</span> <span m=''1072900''>that</span> <span m=''1073110''>issue.</span>
  </p><p><span m=''1075600''>So</span> <span m=''1075810''>if</span> <span m=''1075930''>I</span>
  <span m=''1076020''>take</span> <span m=''1076300''>a</span> <span m=''1076380''>look</span>
  <span m=''1076760''>at</span> <span m=''1077000''>it</span> <span m=''1077860''>from</span>
  <span m=''1078280''>using</span> <span m=''1083750''>the</span> <span m=''1084370''>DAG</span>
  <span m=''1084980''>model</span> <span m=''1085390''>that</span> <span m=''1085530''>I</span>
  <span m=''1085660''>introduced</span> <span m=''1086050''>last</span> <span m=''1086420''>time,</span>
  <span m=''1087060''>remember</span> <span m=''1087420''>that</span> <span m=''1087650''>the</span>
  <span m=''1088900''>rectangles</span> <span m=''1089610''>here</span> <span m=''1091860''>kind</span>
  <span m=''1092000''>of</span> <span m=''1092140''>count</span> <span m=''1092430''>as</span>
  <span m=''1092620''>activation</span> <span m=''1093340''>frames,</span> <span m=''1096150''>stack</span>
  <span m=''1096560''>frames</span> <span m=''1096980''>on</span> <span m=''1097130''>the</span>
  <span m=''1097220''>call</span> <span m=''1097500''>stack.</span> <span m=''1098520''>And</span>
  <span m=''1099060''>the</span> <span m=''1099430''>circles</span> <span m=''1099760''>here
  are</span> <span m=''1100000''>strands,</span> <span m=''1100810''>which</span>
  <span m=''1101060''>are</span> <span m=''1102170''>sequences</span> <span m=''1102700''>of</span>
  <span m=''1102780''>serial</span> <span m=''1103930''>code.</span> <span m=''1105020''>And</span>
  <span m=''1105250''>so</span> <span m=''1105400''>what''s</span> <span m=''1105560''>happening</span>
  <span m=''1106010''>here</span> <span m=''1106260''>is</span> <span m=''1106370''>essentially,</span>
  <span m=''1107000''>I''m</span> <span m=''1107160''>running</span> <span m=''1107430''>the</span>
  <span m=''1107540''>code</span> <span m=''1108450''>that</span> <span m=''1109180''>divides</span>
  <span m=''1109680''>it</span> <span m=''1109790''>into</span> <span m=''1110030''>two</span>
  <span m=''1110230''>parts,</span> <span m=''1110665''>and</span> <span m=''1111100''>I</span>
  <span m=''1111890''>spawn</span> <span m=''1112240''>one</span> <span m=''1112510''>part.</span>
  <span m=''1113200''>Then</span> <span m=''1113490''>this</span> <span m=''1113710''>guy</span>
  <span m=''1113890''>spawns</span> <span m=''1114390''>the</span> <span m=''1114590''>other</span>
  <span m=''1114780''>and</span> <span m=''1114880''>waits</span> <span m=''1115210''>for</span>
  <span m=''1115300''>the</span> <span m=''1115410''>return,</span> <span m=''1116360''>and</span>
  <span m=''1116480''>then</span> <span m=''1116620''>these</span> <span m=''1116830''>guys</span>
  <span m=''1117090''>come</span> <span m=''1117230''>back.</span> <span m=''1117530''>And</span>
  <span m=''1117610''>then</span> <span m=''1117730''>I</span> <span m=''1117780''>keep</span>
  <span m=''1118030''>doing</span> <span m=''1118240''>that</span> <span m=''1118450''>recursively,</span>
  <span m=''1119540''>and</span> <span m=''1119660''>then</span> <span m=''1119800''>when</span>
  <span m=''1119960''>I</span> <span m=''1120010''>get</span> <span m=''1120260''>to</span>
  <span m=''1120350''>the</span> <span m=''1120430''>bottom,</span> <span m=''1121280''>I</span>
  <span m=''1121440''>then</span> <span m=''1121780''>run</span> <span m=''1122050''>through</span>
  <span m=''1123000''>the</span> <span m=''1123380''>innermost</span> <span m=''1124680''>loop,</span>
  <span m=''1125010''>which</span> <span m=''1125210''>starts</span> <span m=''1125590''>out</span>
  <span m=''1125930''>with</span> <span m=''1126640''>just</span> <span m=''1126880''>one</span>
  <span m=''1127140''>element</span> <span m=''1128040''>to</span> <span m=''1128140''>do,</span>
  <span m=''1128460''>two,</span> <span m=''1128830''>three.</span> </p><p><span m=''1129470''>And</span>
  <span m=''1129630''>so</span> <span m=''1129760''>the</span> <span m=''1129870''>number</span>
  <span m=''1130170''>of</span> <span m=''1130240''>elements--</span> <span m=''1131210''>for</span>
  <span m=''1131310''>example,</span> <span m=''1131660''>in</span> <span m=''1131700''>this</span>
  <span m=''1131860''>case</span> <span m=''1132090''>where I''ve</span> <span m=''1132290''>done
  eight,</span> <span m=''1132840''>I</span> <span m=''1132910''>go</span> <span m=''1133080''>through</span>
  <span m=''1133320''>eight</span> <span m=''1133510''>elements</span> <span m=''1137390''>at</span>
  <span m=''1137570''>the</span> <span m=''1137990''>bottom</span> <span m=''1138280''>here</span>
  <span m=''1138640''>if this</span> <span m=''1138800''>were</span> <span m=''1138990''>an</span>
  <span m=''1139130''>eight</span> <span m=''1139370''>by</span> <span m=''1139550''>eight</span>
  <span m=''1140060''>matrix</span> <span m=''1140580''>that</span> <span m=''1140710''>I</span>
  <span m=''1140830''>was</span> <span m=''1140940''>transposing.</span> <span m=''1143430''>So</span>
  <span m=''1143600''>there''s</span> <span m=''1143750''>more</span> <span m=''1144050''>work</span>
  <span m=''1145090''>in</span> <span m=''1145240''>these</span> <span m=''1145500''>guys</span>
  <span m=''1145960''>than</span> <span m=''1146090''>there</span> <span m=''1146240''>is</span>
  <span m=''1146370''>over</span> <span m=''1146590''>here.</span> <span m=''1148450''>So</span>
  <span m=''1148550''>it''s</span> <span m=''1148670''>not</span> <span m=''1148950''>something</span>
  <span m=''1149270''>you</span> <span m=''1149400''>just</span> <span m=''1149630''>can</span>
  <span m=''1149760''>map</span> <span m=''1150110''>onto</span> <span m=''1150340''>processors</span>
  <span m=''1151040''>in</span> <span m=''1151150''>some</span> <span m=''1151340''>naive</span>
  <span m=''1151700''>fashion.</span> <span m=''1152770''>It</span> <span m=''1152990''>does</span>
  <span m=''1153210''>take</span> <span m=''1153430''>some</span> <span m=''1153580''>load</span>
  <span m=''1153800''>balancing</span> <span m=''1154330''>to</span> <span m=''1154410''>parallelize</span>
  <span m=''1154980''>this</span> <span m=''1155160''>loop.</span> <span m=''1156040''>Any</span>
  <span m=''1156220''>questions</span> <span m=''1157810''>about</span> <span m=''1158110''>what''s</span>
  <span m=''1158300''>going</span> <span m=''1158490''>on</span> <span m=''1158610''>here?</span>
  <span m=''1158750''>Yeah?</span> </p><p><span m=''1159800''>AUDIENCE: Why</span>
  <span m=''1160110''>is</span> <span m=''1160420''>it that</span> <span m=''1160910''>it''s</span>
  <span m=''1161382''>one, two,</span> <span m=''1161854''>three, four,</span> <span
  m=''1162326''>up to</span> <span m=''1162798''>eight?</span> </p><p><span m=''1163270''>CHARLES
  LEISERSON: Take</span> <span m=''1163742''>a</span> <span m=''1164214''>look.</span>
  <span m=''1164686''>The inner</span> <span m=''1165160''>loop</span> <span m=''1165480''>goes
  from</span> <span m=''1165800''>j to i.</span> <span m=''1168710''>So</span> <span
  m=''1169080''>this</span> <span m=''1169400''>guy just</span> <span m=''1169640''>does</span>
  <span m=''1169970''>one</span> <span m=''1170210''>iteration</span> <span m=''1170710''>of
  the inner</span> <span m=''1170950''>loop,</span> <span m=''1171230''>this</span>
  <span m=''1171390''>guy</span> <span m=''1171540''>does two,</span> <span m=''1172100''>this</span>
  <span m=''1172300''>guy</span> <span m=''1172470''>does</span> <span m=''1172740''>three,</span>
  <span m=''1173050''>all</span> <span m=''1173190''>the</span> <span m=''1173340''>way</span>
  <span m=''1173480''>up</span> <span m=''1173570''>to</span> <span m=''1173660''>this</span>
  <span m=''1173860''>guy</span> <span m=''1174020''>doing eight</span> <span m=''1174300''>iterations,</span>
  <span m=''1175430''>if</span> <span m=''1175530''>it</span> <span m=''1175630''>were
  an</span> <span m=''1175820''>eight</span> <span m=''1176030''>by</span> <span m=''1176180''>eight</span>
  <span m=''1176420''>matrix.</span> <span m=''1178880''>And</span> <span m=''1179020''>in</span>
  <span m=''1179110''>general,</span> <span m=''1179510''>if</span> <span m=''1179610''>it''s</span>
  <span m=''1179740''>n</span> <span m=''1179950''>by</span> <span m=''1180160''>n,</span>
  <span m=''1180570''>it''s</span> <span m=''1180770''>going</span> <span m=''1181020''>from</span>
  <span m=''1181210''>one</span> <span m=''1181950''>to</span> <span m=''1182310''>n</span>
  <span m=''1182610''>work</span> <span m=''1182850''>up</span> <span m=''1183010''>here,</span>
  <span m=''1183750''>but</span> <span m=''1183890''>only</span> <span m=''1184110''>one</span>
  <span m=''1184380''>work</span> <span m=''1184610''>down</span> <span m=''1184840''>here.</span>
  <span m=''1185630''>Because</span> <span m=''1185820''>I''m</span> <span m=''1185910''>basically</span>
  <span m=''1186500''>iterating</span> <span m=''1186900''>through</span> <span m=''1186980''>a</span>
  <span m=''1187070''>triangular</span> <span m=''1187800''>iteration</span> <span
  m=''1188270''>space</span> <span m=''1189020''>to</span> <span m=''1189140''>swap</span>
  <span m=''1189870''>the</span> <span m=''1189950''>matrix,</span> <span m=''1191220''>and</span>
  <span m=''1191360''>this</span> <span m=''1191480''>is</span> <span m=''1191590''>basically</span>
  <span m=''1192000''>swapping</span> <span m=''1192490''>row</span> <span m=''1192640''>by</span>
  <span m=''1192820''>row.</span> <span m=''1194480''>Questions?</span> <span m=''1195550''>Is</span>
  <span m=''1195680''>that</span> <span m=''1195720''>good?</span> <span m=''1197160''>Everybody</span>
  <span m=''1197480''>see</span> <span m=''1197650''>what''s</span> <span m=''1197880''>going</span>
  <span m=''1198150''>on?</span> </p><p><span m=''1198770''>So</span> <span m=''1198910''>now</span>
  <span m=''1199080''>let''s</span> <span m=''1199250''>take</span> <span m=''1199480''>a</span>
  <span m=''1199550''>look</span> <span m=''1199780''>and</span> <span m=''1199980''>let''s</span>
  <span m=''1200250''>analyze</span> <span m=''1200780''>this</span> <span m=''1201080''>for</span>
  <span m=''1201210''>work</span> <span m=''1201480''>and</span> <span m=''1201580''>span.</span>
  <span m=''1202500''>So</span> <span m=''1202650''>what</span> <span m=''1202800''>is</span>
  <span m=''1202940''>the</span> <span m=''1203020''>work</span> <span m=''1203350''>of</span>
  <span m=''1203470''>this</span> <span m=''1205320''>in</span> <span m=''1205450''>terms</span>
  <span m=''1205730''>of</span> <span m=''1205820''>n,</span> <span m=''1206180''>if</span>
  <span m=''1206320''>I</span> <span m=''1206410''>have</span> <span m=''1206920''>an</span>
  <span m=''1207310''>n</span> <span m=''1207520''>by</span> <span m=''1207680''>n</span>
  <span m=''1207920''>matrix?</span> <span m=''1218550''>What''s the work?</span>
  <span m=''1218950''>The work</span> <span m=''1219200''>is</span> <span m=''1219310''>the</span>
  <span m=''1219410''>ordinary</span> <span m=''1219820''>serial</span> <span m=''1220260''>running</span>
  <span m=''1220520''>time,</span> <span m=''1220800''>right?</span> <span m=''1223470''>It''s</span>
  <span m=''1223760''>n</span> <span m=''1223960''>squared.</span> <span m=''1224420''>Good.</span>
  <span m=''1226370''>So</span> <span m=''1226540''>basically,</span> <span m=''1227040''>it''s</span>
  <span m=''1227100''>order</span> <span m=''1227370''>n</span> <span m=''1227530''>squared,</span>
  <span m=''1227960''>because</span> <span m=''1229030''>these</span> <span m=''1229360''>guys</span>
  <span m=''1229710''>are</span> <span m=''1229840''>all</span> <span m=''1230140''>adding</span>
  <span m=''1230460''>up.</span> <span m=''1230670''>This</span> <span m=''1230820''>is</span>
  <span m=''1230950''>an</span> <span m=''1231030''>arithmetic</span> <span m=''1231640''>sequence</span>
  <span m=''1232140''>up to</span> <span m=''1232500''>n,</span> <span m=''1234200''>and</span>
  <span m=''1234360''>so</span> <span m=''1234570''>the</span> <span m=''1234710''>total</span>
  <span m=''1235060''>amount</span> <span m=''1235360''>in</span> <span m=''1235480''>here</span>
  <span m=''1235710''>is</span> <span m=''1235800''>order</span> <span m=''1236100''>n</span>
  <span m=''1236270''>squared.</span> </p><p><span m=''1238420''>What</span> <span
  m=''1238560''>about</span> <span m=''1238860''>this</span> <span m=''1239040''>part</span>
  <span m=''1239280''>up</span> <span m=''1239430''>here?</span> <span m=''1243420''>How</span>
  <span m=''1243530''>much</span> <span m=''1243730''>does</span> <span m=''1243920''>that</span>
  <span m=''1244120''>cost</span> <span m=''1244510''>us</span> <span m=''1247710''>for</span>
  <span m=''1247810''>work?</span> <span m=''1250580''>How</span> <span m=''1250730''>much</span>
  <span m=''1250940''>is</span> <span m=''1251080''>in</span> <span m=''1251240''>the</span>
  <span m=''1251330''>control</span> <span m=''1251890''>overhead</span> <span m=''1252310''>of</span>
  <span m=''1252460''>doing</span> <span m=''1252730''>that</span> <span m=''1252940''>outer</span>
  <span m=''1253270''>loop?</span> <span m=''1265935''>So</span> <span m=''1266430''>asymptotically,</span>
  <span m=''1267190''>how</span> <span m=''1267300''>much</span> <span m=''1267540''>is</span>
  <span m=''1267650''>in</span> <span m=''1267750''>here?</span> <span m=''1268530''>The</span>
  <span m=''1268650''>total</span> <span m=''1268960''>is</span> <span m=''1269040''>going</span>
  <span m=''1269120''>to</span> <span m=''1269200''>be</span> <span m=''1269330''>n</span>
  <span m=''1269490''>squared.</span> <span m=''1269890''>That</span> <span m=''1270070''>I</span>
  <span m=''1270120''>guarantee</span> <span m=''1270450''>you.</span> <span m=''1271180''>But</span>
  <span m=''1271530''>what''s</span> <span m=''1271960''>going</span> <span m=''1272230''>on</span>
  <span m=''1272410''>up</span> <span m=''1272530''>here?</span> <span m=''1273820''>How</span>
  <span m=''1274010''>do</span> <span m=''1274120''>I</span> <span m=''1274770''>count</span>
  <span m=''1275080''>that</span> <span m=''1275560''>up?</span> </p><p><span m=''1276500''>AUDIENCE:
  I''m assuming</span> <span m=''1276970''>that each</span> <span m=''1277440''>[?
  strain ?]</span> <span m=''1277910''>is going to be</span> <span m=''1278380''>constant</span>
  <span m=''1278850''>time?</span> </p><p><span m=''1280730''>CHARLES LEISERSON: Yeah,</span>
  <span m=''1281200''>well in</span> <span m=''1281490''>this case, it is</span> <span
  m=''1281700''>constant</span> <span m=''1282160''>time,</span> <span m=''1283590''>for</span>
  <span m=''1283930''>these</span> <span m=''1284220''>up</span> <span m=''1284390''>here,</span>
  <span m=''1284610''>because</span> <span m=''1284890''>what</span> <span m=''1285050''>am</span>
  <span m=''1285160''>I</span> <span m=''1285250''>doing?</span> <span m=''1285520''>All</span>
  <span m=''1285670''>I''m</span> <span m=''1285790''>doing</span> <span m=''1286050''>is</span>
  <span m=''1287330''>the</span> <span m=''1287360''>recursion</span> <span m=''1287730''>code</span>
  <span m=''1287950''>where I</span> <span m=''1288200''>divide</span> <span m=''1291650''>the</span>
  <span m=''1292080''>range</span> <span m=''1292690''>and</span> <span m=''1292790''>then</span>
  <span m=''1292930''>spawn</span> <span m=''1293330''>off</span> <span m=''1293500''>two</span>
  <span m=''1293710''>things.</span> <span m=''1294060''>That</span> <span m=''1294240''>takes</span>
  <span m=''1294440''>me</span> <span m=''1294540''>only</span> <span m=''1294800''>a
  constant</span> <span m=''1295150''>amount</span> <span m=''1295470''>of</span>
  <span m=''1295870''>manipulation</span> <span m=''1296620''>to</span> <span m=''1296720''>be</span>
  <span m=''1296880''>able</span> <span m=''1297040''>to</span> <span m=''1297090''>do</span>
  <span m=''1297210''>that.</span> <span m=''1298600''>So</span> <span m=''1298770''>this</span>
  <span m=''1298930''>is</span> <span m=''1299060''>all</span> <span m=''1299530''>order</span>
  <span m=''1299550''>n.</span> <span m=''1302090''>Total</span> <span m=''1302440''>of</span>
  <span m=''1302530''>order</span> <span m=''1302920''>n</span> <span m=''1303120''>here.</span>
  <span m=''1303760''>The</span> <span m=''1303880''>reason</span> <span m=''1304190''>is</span>
  <span m=''1304410''>because</span> <span m=''1304860''>in</span> <span m=''1304960''>some</span>
  <span m=''1305150''>sense,</span> <span m=''1305430''>there</span> <span m=''1305620''>are
  n</span> <span m=''1305830''>leaves</span> <span m=''1306260''>here.</span> <span
  m=''1307550''>And</span> <span m=''1307950''>if</span> <span m=''1308090''>you</span>
  <span m=''1308230''>have</span> <span m=''1308380''>a</span> <span m=''1308840''>full</span>
  <span m=''1309180''>binary</span> <span m=''1309670''>tree,</span> <span m=''1310090''>meaning</span>
  <span m=''1310390''>every</span> <span m=''1310870''>child</span> <span m=''1311840''>is</span>
  <span m=''1312040''>either</span> <span m=''1312340''>a</span> <span m=''1312420''>leaf</span>
  <span m=''1313050''>or</span> <span m=''1313360''>has</span> <span m=''1313740''>two</span>
  <span m=''1313920''>children,</span> <span m=''1315070''>then</span> <span m=''1315280''>the</span>
  <span m=''1315370''>number</span> <span m=''1315690''>of the</span> <span m=''1315860''>internal</span>
  <span m=''1316330''>nodes</span> <span m=''1316670''>of</span> <span m=''1316770''>the</span>
  <span m=''1316860''>tree</span> <span m=''1317250''>is</span> <span m=''1317400''>one</span>
  <span m=''1317670''>less</span> <span m=''1317990''>than</span> <span m=''1318120''>the</span>
  <span m=''1318200''>number</span> <span m=''1318520''>of</span> <span m=''1318590''>leaves.</span>
  <span m=''1321330''>So</span> <span m=''1321460''>that''s</span> <span m=''1321750''>a</span>
  <span m=''1321910''>basic</span> <span m=''1322290''>property</span> <span m=''1322750''>of</span>
  <span m=''1322820''>trees,</span> <span m=''1325140''>that</span> <span m=''1325470''>the</span>
  <span m=''1325600''>number</span> <span m=''1325920''>of the</span> <span m=''1326080''>internal</span>
  <span m=''1326470''>nodes</span> <span m=''1326780''>here</span> <span m=''1327440''>is</span>
  <span m=''1327610''>going</span> <span m=''1327680''>to</span> <span m=''1327760''>be</span>
  <span m=''1328010''>n</span> <span m=''1328200''>minus</span> <span m=''1328540''>1,</span>
  <span m=''1328780''>in</span> <span m=''1328890''>this</span> <span m=''1329070''>case.</span>
  <span m=''1330430''>In</span> <span m=''1330550''>particular,</span> <span m=''1331020''>we</span>
  <span m=''1331150''>have</span> <span m=''1331340''>7</span> <span m=''1332240''>here.</span>
  <span m=''1334460''>Is</span> <span m=''1334720''>that good?</span> <span m=''1335910''>So</span>
  <span m=''1336220''>this</span> <span m=''1336510''>part</span> <span m=''1336870''>doesn''t</span>
  <span m=''1337240''>contribute</span> <span m=''1337730''>significantly</span> <span
  m=''1338610''>to</span> <span m=''1338730''>the</span> <span m=''1338830''>work.</span>
  <span m=''1339790''>Just</span> <span m=''1340130''>this</span> <span m=''1340340''>part</span>
  <span m=''1340600''>contributes</span> <span m=''1341100''>to</span> <span m=''1341190''>the</span>
  <span m=''1341270''>work.</span> <span m=''1342700''>Is</span> <span m=''1342820''>that</span>
  <span m=''1342890''>good?</span> </p><p><span m=''1346000''>What</span> <span m=''1346190''>about</span>
  <span m=''1346430''>the</span> <span m=''1346510''>span</span> <span m=''1347030''>for</span>
  <span m=''1347120''>this?</span> <span m=''1364470''>What''s</span> <span m=''1364610''>the</span>
  <span m=''1364740''>span?</span> </p><p><span m=''1368819''>AUDIENCE: Log</span>
  <span m=''1369306''>n.</span> </p><p><span m=''1370770''>CHARLES LEISERSON: It''s</span>
  <span m=''1371080''>not</span> <span m=''1371310''>log</span> <span m=''1371620''>n,</span>
  <span m=''1373160''>but</span> <span m=''1373400''>your</span> <span m=''1373570''>heads</span>
  <span m=''1373840''>are</span> <span m=''1373920''>in</span> <span m=''1374010''>the</span>
  <span m=''1374090''>right</span> <span m=''1374370''>place.</span> </p><p><span
  m=''1377796''>AUDIENCE: The longest</span> <span m=''1378282''>path</span> <span
  m=''1378768''>is going</span> <span m=''1379254''>[INAUDIBLE].</span> </p><p><span
  m=''1380720''>CHARLES LEISERSON: Which</span> <span m=''1381090''>is the</span>
  <span m=''1381310''>longest</span> <span m=''1381550''>path</span> <span m=''1382028''>going</span>
  <span m=''1382506''>to be here,</span> <span m=''1383940''>starting</span> <span
  m=''1384370''>here</span> <span m=''1385220''>and</span> <span m=''1385700''>ending</span>
  <span m=''1386150''>there,</span> <span m=''1388040''>which</span> <span m=''1388230''>way</span>
  <span m=''1388410''>do we</span> <span m=''1388530''>go?</span> </p><p><span m=''1390371''>AUDIENCE:
  Go all the way down.</span> </p><p><span m=''1390840''>CHARLES LEISERSON: Which</span>
  <span m=''1391030''>way?</span> </p><p><span m=''1391707''>AUDIENCE: To the</span>
  <span m=''1392124''>right.</span> </p><p><span m=''1392960''>CHARLES LEISERSON:
  Down</span> <span m=''1393200''>to</span> <span m=''1393290''>the</span> <span m=''1393390''>right,</span>
  <span m=''1396040''>over,</span> <span m=''1397020''>down</span> <span m=''1397310''>through</span>
  <span m=''1397460''>this</span> <span m=''1397750''>guy.</span> <span m=''1398040''>How
  big is</span> <span m=''1398340''>this</span> <span m=''1398530''>guy?</span> <span
  m=''1399800''>n.</span> <span m=''1400730''>Go</span> <span m=''1400900''>back</span>
  <span m=''1401510''>up</span> <span m=''1401670''>this</span> <span m=''1401880''>way.</span>
  <span m=''1402830''>So</span> <span m=''1402960''>how</span> <span m=''1403140''>much</span>
  <span m=''1403410''>is</span> <span m=''1403590''>in</span> <span m=''1403830''>this</span>
  <span m=''1404020''>part</span> <span m=''1404420''>going</span> <span m=''1404630''>down?</span>
  </p><p><span m=''1405407''>AUDIENCE: Log</span> <span m=''1405794''>n.</span> </p><p><span
  m=''1406800''>CHARLES LEISERSON: Going</span> <span m=''1407000''>down</span> <span
  m=''1407250''>and</span> <span m=''1407340''>up</span> <span m=''1407530''>is</span>
  <span m=''1407670''>log</span> <span m=''1407880''>n,</span> <span m=''1408280''>but</span>
  <span m=''1408470''>this</span> <span m=''1408690''>is</span> <span m=''1409880''>n.</span>
  <span m=''1410890''>Good.</span> <span m=''1415160''>So it''s</span> <span m=''1415430''>basically</span>
  <span m=''1415910''>order</span> <span m=''1416190''>n</span> <span m=''1416620''>plus</span>
  <span m=''1416910''>order</span> <span m=''1417210''>log</span> <span m=''1417620''>n,</span>
  <span m=''1418340''>order</span> <span m=''1418550''>n</span> <span m=''1419690''>down</span>
  <span m=''1419940''>here</span> <span m=''1420310''>plus</span> <span m=''1420530''>order</span>
  <span m=''1420800''>log</span> <span m=''1421210''>n</span> <span m=''1421360''>up</span>
  <span m=''1421490''>and</span> <span m=''1421660''>down,</span> <span m=''1421980''>that''s</span>
  <span m=''1422200''>order</span> <span m=''1422540''>n.</span> <span m=''1424490''>So</span>
  <span m=''1424650''>the</span> <span m=''1424730''>parallelism</span> <span m=''1426220''>is</span>
  <span m=''1426520''>the</span> <span m=''1426620''>ratio</span> <span m=''1427030''>of</span>
  <span m=''1427110''>those</span> <span m=''1427380''>two</span> <span m=''1427530''>things,</span>
  <span m=''1428840''>which</span> <span m=''1428990''>is</span> <span m=''1429110''>order</span>
  <span m=''1429400''>n.</span> <span m=''1431530''>So</span> <span m=''1431660''>that''s</span>
  <span m=''1431880''>got</span> <span m=''1432070''>good</span> <span m=''1432250''>parallelism.</span>
  <span m=''1434260''>And</span> <span m=''1434420''>so</span> <span m=''1434550''>if</span>
  <span m=''1434610''>you</span> <span m=''1434740''>imagine</span> <span m=''1435140''>doing</span>
  <span m=''1435380''>this</span> <span m=''1435550''>in</span> <span m=''1435600''>a</span>
  <span m=''1435670''>large</span> <span m=''1436030''>number</span> <span m=''1436280''>processors,</span>
  <span m=''1436960''>very</span> <span m=''1437260''>easy</span> <span m=''1438260''>to</span>
  <span m=''1438390''>get</span> <span m=''1438660''>sort</span> <span m=''1438810''>of</span>
  <span m=''1438960''>your</span> <span m=''1441980''>benchmark</span> <span m=''1442560''>of</span>
  <span m=''1442630''>maybe</span> <span m=''1442900''>10</span> <span m=''1443180''>times</span>
  <span m=''1443540''>more</span> <span m=''1443740''>parallelism</span> <span m=''1444410''>than</span>
  <span m=''1444630''>the</span> <span m=''1444730''>number</span> <span m=''1444980''>of</span>
  <span m=''1445040''>processors</span> <span m=''1445710''>that</span> <span m=''1445810''>you''re</span>
  <span m=''1445910''>running</span> <span m=''1446160''>on.</span> <span m=''1448570''>Everybody</span>
  <span m=''1448920''>follow</span> <span m=''1449220''>this?</span> <span m=''1452240''>Good.</span>
  </p><p><span m=''1454460''>So</span> <span m=''1454690''>the</span> <span m=''1454790''>span</span>
  <span m=''1455130''>of the</span> <span m=''1455220''>loop</span> <span m=''1455440''>control</span>
  <span m=''1455890''>is</span> <span m=''1455990''>order</span> <span m=''1456180''>log</span>
  <span m=''1456440''>n.</span> <span m=''1456700''>And in</span> <span m=''1456860''>general,</span>
  <span m=''1458970''>when</span> <span m=''1459220''>you</span> <span m=''1459460''>have</span>
  <span m=''1459840''>a</span> <span m=''1461100''>four</span> <span m=''1461660''>loop</span>
  <span m=''1461900''>with</span> <span m=''1462040''>n</span> <span m=''1462240''>iterations,</span>
  <span m=''1463310''>the</span> <span m=''1463420''>loop</span> <span m=''1463730''>control</span>
  <span m=''1464150''>itself</span> <span m=''1464560''>is</span> <span m=''1464700''>going</span>
  <span m=''1464810''>to</span> <span m=''1464970''>have</span> <span m=''1465190''>log
  n</span> <span m=''1467450''>is</span> <span m=''1467600''>going</span> <span m=''1467700''>to</span>
  <span m=''1467810''>have</span> <span m=''1467920''>to</span> <span m=''1468020''>be</span>
  <span m=''1468180''>added</span> <span m=''1468530''>to</span> <span m=''1468620''>the</span>
  <span m=''1468720''>span</span> <span m=''1469290''>every</span> <span m=''1469540''>time</span>
  <span m=''1469780''>you</span> <span m=''1469880''>hit a</span> <span m=''1470000''>loop,</span>
  <span m=''1471590''>log</span> <span m=''1471930''>of</span> <span m=''1472020''>whatever</span>
  <span m=''1472290''>the</span> <span m=''1472390''>number</span> <span m=''1472650''>of</span>
  <span m=''1472720''>iterations</span> <span m=''1473260''>is.</span> <span m=''1475570''>And</span>
  <span m=''1475760''>then</span> <span m=''1475940''>we</span> <span m=''1476060''>have</span>
  <span m=''1476230''>the</span> <span m=''1476630''>maximum</span> <span m=''1477260''>span</span>
  <span m=''1477670''>of</span> <span m=''1477760''>the</span> <span m=''1477840''>body.</span>
  <span m=''1478680''>Well,</span> <span m=''1478900''>the</span> <span m=''1478970''>worst</span>
  <span m=''1479290''>case</span> <span m=''1479800''>for</span> <span m=''1479890''>this</span>
  <span m=''1480140''>thing</span> <span m=''1480500''>in</span> <span m=''1480660''>the</span>
  <span m=''1480730''>body</span> <span m=''1481120''>is</span> <span m=''1481310''>when</span>
  <span m=''1481500''>it''s</span> <span m=''1481710''>doing</span> <span m=''1481900''>the</span>
  <span m=''1481980''>whole</span> <span m=''1482210''>thing,</span> <span m=''1483540''>because</span>
  <span m=''1483740''>whenever</span> <span m=''1484120''>we''re</span> <span m=''1484270''>looking</span>
  <span m=''1484580''>at</span> <span m=''1484680''>spans,</span> <span m=''1485140''>we''re</span>
  <span m=''1485260''>always</span> <span m=''1485470''>looking</span> <span m=''1485760''>what''s</span>
  <span m=''1485900''>the</span> <span m=''1486050''>maximum</span> <span m=''1488080''>of</span>
  <span m=''1488260''>things</span> <span m=''1488490''>that</span> <span m=''1488580''>are</span>
  <span m=''1488690''>operating</span> <span m=''1489130''>in</span> <span m=''1489220''>parallel.</span>
  <span m=''1490740''>Everybody</span> <span m=''1491130''>good?</span> <span m=''1493060''>Questions?</span>
  <span m=''1496330''>Great.</span> </p><p><span m=''1498440''>So</span> <span m=''1498620''>now</span>
  <span m=''1498870''>let''s</span> <span m=''1499230''>do</span> <span m=''1499370''>something</span>
  <span m=''1499730''>a</span> <span m=''1499790''>little</span> <span m=''1501610''>more</span>
  <span m=''1503620''>parallel.</span> <span m=''1505590''>Let''s</span> <span m=''1505900''>make</span>
  <span m=''1506200''>both</span> <span m=''1506510''>loops</span> <span m=''1506860''>be</span>
  <span m=''1507040''>parallel.</span> <span m=''1509380''>So</span> <span m=''1509580''>here</span>
  <span m=''1509790''>we</span> <span m=''1509900''>have</span> <span m=''1510080''>a</span>
  <span m=''1510260''>cilk_for</span> <span m=''1510900''>loop</span> <span m=''1511160''>here,</span>
  <span m=''1511790''>and</span> <span m=''1511930''>then</span> <span m=''1512060''>another</span>
  <span m=''1512510''>cilk_for</span> <span m=''1513080''>loop</span> <span m=''1513330''>on</span>
  <span m=''1513450''>the</span> <span m=''1513610''>interior.</span> <span m=''1516570''>And</span>
  <span m=''1516700''>let''s</span> <span m=''1516910''>see</span> <span m=''1517050''>what</span>
  <span m=''1517230''>we</span> <span m=''1517340''>get</span> <span m=''1517540''>here.</span>
  <span m=''1518480''>So</span> <span m=''1518640''>what''s</span> <span m=''1518800''>the</span>
  <span m=''1518950''>work</span> <span m=''1519300''>for</span> <span m=''1519400''>this?</span>
  </p><p><span m=''1520868''>AUDIENCE:</span> <span m=''1521342''>n squared.</span>
  </p><p><span m=''1521816''>CHARLES LEISERSON: Yeah,</span> <span m=''1522290''>n</span>
  <span m=''1522620''>squared.</span> <span m=''1523000''>That''s</span> <span m=''1523260''>not</span>
  <span m=''1523420''>going</span> <span m=''1523510''>to</span> <span m=''1523600''>change.</span>
  <span m=''1525230''>That''s</span> <span m=''1525480''>not</span> <span m=''1525600''>going</span>
  <span m=''1525680''>to</span> <span m=''1525770''>change.</span> <span m=''1529650''>What''s</span>
  <span m=''1529830''>the</span> <span m=''1530010''>span?</span> </p><p><span m=''1534992''>AUDIENCE:</span>
  <span m=''1535490''>log</span> <span m=''1535988''>n.</span> </p><p><span m=''1537990''>CHARLES
  LEISERSON: Yeah,</span> <span m=''1538200''>log n.</span> <span m=''1540490''>So</span>
  <span m=''1540660''>it''s</span> <span m=''1540790''>log</span> <span m=''1541180''>n</span>
  <span m=''1541500''>because</span> <span m=''1542540''>the</span> <span m=''1542630''>span</span>
  <span m=''1543090''>of</span> <span m=''1543170''>the</span> <span m=''1543330''>outer</span>
  <span m=''1543660''>control</span> <span m=''1544170''>loop</span> <span m=''1544420''>is</span>
  <span m=''1544580''>going</span> <span m=''1544680''>to</span> <span m=''1544740''>add</span>
  <span m=''1545080''>log</span> <span m=''1545440''>n.</span> <span m=''1546490''>The</span>
  <span m=''1547640''>max</span> <span m=''1548035''>span of</span> <span m=''1548430''>the</span>
  <span m=''1548560''>inner</span> <span m=''1548840''>control</span> <span m=''1549300''>loop,</span>
  <span m=''1549500''>well,</span> <span m=''1549810''>it''s</span> <span m=''1550500''>going</span>
  <span m=''1550750''>from</span> <span m=''1550940''>log</span> <span m=''1552300''>of</span>
  <span m=''1553870''>1</span> <span m=''1554440''>up</span> <span m=''1554620''>to</span>
  <span m=''1554720''>log</span> <span m=''1555130''>of</span> <span m=''1556290''>i,</span>
  <span m=''1557160''>but</span> <span m=''1557310''>the</span> <span m=''1557390''>maximums</span>
  <span m=''1558200''>of</span> <span m=''1558380''>those</span> <span m=''1558730''>is</span>
  <span m=''1558850''>going</span> <span m=''1558920''>to</span> <span m=''1558990''>be</span>
  <span m=''1559260''>proportional</span> <span m=''1559940''>to</span> <span m=''1560040''>log
  n</span> <span m=''1561960''>because</span> <span m=''1563000''>it''s</span> <span
  m=''1563270''>not</span> <span m=''1563460''>regular.</span> <span m=''1565420''>And</span>
  <span m=''1565590''>the</span> <span m=''1565670''>span</span> <span m=''1566050''>of</span>
  <span m=''1566150''>the</span> <span m=''1566220''>body</span> <span m=''1566650''>now</span>
  <span m=''1567130''>is</span> <span m=''1567340''>going</span> <span m=''1567420''>to</span>
  <span m=''1567500''>be</span> <span m=''1567620''>order</span> <span m=''1567920''>1.</span>
  <span m=''1569490''>And</span> <span m=''1569670''>so</span> <span m=''1569830''>we</span>
  <span m=''1570020''>add</span> <span m=''1571370''>the</span> <span m=''1571480''>logs</span>
  <span m=''1572140''>because</span> <span m=''1572630''>those</span> <span m=''1573150''>things</span>
  <span m=''1573560''>are</span> <span m=''1574120''>in</span> <span m=''1574520''>series.</span>
  <span m=''1576470''>We</span> <span m=''1576550''>don''t</span> <span m=''1576770''>multiply</span>
  <span m=''1577410''>them.</span> <span m=''1581250''>What</span> <span m=''1581380''>we''re</span>
  <span m=''1581480''>doing</span> <span m=''1581770''>is</span> <span m=''1581870''>we''re</span>
  <span m=''1581960''>looking</span> <span m=''1582220''>at,</span> <span m=''1582310''>what''s</span>
  <span m=''1582550''>the</span> <span m=''1582640''>worst</span> <span m=''1582980''>case?</span>
  <span m=''1583170''>The</span> <span m=''1583240''>worst</span> <span m=''1583530''>case
  is</span> <span m=''1583910''>I</span> <span m=''1584030''>have</span> <span m=''1584130''>to</span>
  <span m=''1584250''>do</span> <span m=''1584740''>the</span> <span m=''1584860''>control</span>
  <span m=''1585390''>for</span> <span m=''1585510''>this,</span> <span m=''1585920''>plus</span>
  <span m=''1586270''>the</span> <span m=''1586380''>control</span> <span m=''1586860''>for</span>
  <span m=''1586970''>this,</span> <span m=''1587670''>plus</span> <span m=''1588870''>the</span>
  <span m=''1588990''>worst</span> <span m=''1589320''>iteration</span> <span m=''1589790''>here,</span>
  <span m=''1590010''>which</span> <span m=''1590170''>in</span> <span m=''1590230''>this</span>
  <span m=''1590370''>case</span> <span m=''1590600''>is</span> <span m=''1590720''>just</span>
  <span m=''1590920''>order</span> <span m=''1591160''>one.</span> <span m=''1592000''>So</span>
  <span m=''1592190''>the</span> <span m=''1592280''>total</span> <span m=''1592620''>is</span>
  <span m=''1592730''>order</span> <span m=''1592960''>log</span> <span m=''1593320''>n.</span>
  <span m=''1595090''>That</span> <span m=''1595390''>can</span> <span m=''1595520''>be</span>
  <span m=''1595650''>confusing</span> <span m=''1596210''>for</span> <span m=''1596360''>people,</span>
  <span m=''1597480''>why</span> <span m=''1597790''>it</span> <span m=''1597900''>is</span>
  <span m=''1598090''>that</span> <span m=''1598200''>we</span> <span m=''1598370''>add</span>
  <span m=''1598810''>here</span> <span m=''1599200''>rather</span> <span m=''1599570''>than</span>
  <span m=''1602290''>multiply</span> <span m=''1602940''>or</span> <span m=''1603180''>do</span>
  <span m=''1603370''>something</span> <span m=''1603760''>else.</span> <span m=''1605210''>So</span>
  <span m=''1605770''>let</span> <span m=''1605940''>me</span> <span m=''1606080''>pause</span>
  <span m=''1606420''>here</span> <span m=''1606610''>for</span> <span m=''1606760''>some</span>
  <span m=''1606920''>questions</span> <span m=''1607460''>if</span> <span m=''1607560''>people</span>
  <span m=''1609690''>have</span> <span m=''1610590''>questions.</span> <span m=''1611020''>Everybody</span>
  <span m=''1611430''>with us?</span> <span m=''1612020''>Anybody</span> <span m=''1612430''>want</span>
  <span m=''1612730''>clarification</span> <span m=''1613570''>or</span> <span m=''1613760''>make</span>
  <span m=''1614110''>a</span> <span m=''1614200''>point</span> <span m=''1614700''>that</span>
  <span m=''1614930''>would</span> <span m=''1615110''>lead</span> <span m=''1615550''>to</span>
  <span m=''1616280''>clarification?</span> <span m=''1619630''>Yes,</span> <span
  m=''1619890''>question.</span> </p><p><span m=''1620780''>AUDIENCE: If you were</span>
  <span m=''1621271''>going to draw a</span> <span m=''1621762''>tree</span> <span
  m=''1622253''>like the</span> <span m=''1622744''>previous slide,</span> <span m=''1623235''>what
  would it look like?</span> </p><p><span m=''1629670''>CHARLES LEISERSON: Let''s</span>
  <span m=''1629930''>see.</span> <span m=''1630910''>I</span> <span m=''1631340''>had</span>
  <span m=''1631630''>wanted</span> <span m=''1632040''>to</span> <span m=''1632260''>do</span>
  <span m=''1632540''>that</span> <span m=''1632890''>and</span> <span m=''1633170''>it</span>
  <span m=''1633330''>got</span> <span m=''1633640''>out</span> <span m=''1633810''>of</span>
  <span m=''1633870''>control.</span> <span m=''1637510''>So</span> <span m=''1637740''>what
  it</span> <span m=''1637820''>would</span> <span m=''1637980''>look</span> <span
  m=''1638250''>like</span> <span m=''1638700''>is</span> <span m=''1639070''>if</span>
  <span m=''1639180''>we</span> <span m=''1639250''>go</span> <span m=''1639370''>back</span>
  <span m=''1639640''>to</span> <span m=''1639720''>the</span> <span m=''1639800''>previous</span>
  <span m=''1640220''>slide,</span> <span m=''1641930''>it</span> <span m=''1642080''>basically</span>
  <span m=''1642720''>would</span> <span m=''1642920''>look</span> <span m=''1643260''>like</span>
  <span m=''1644010''>this,</span> <span m=''1644600''>except</span> <span m=''1645010''>where</span>
  <span m=''1645300''>each</span> <span m=''1645550''>one</span> <span m=''1645740''>of</span>
  <span m=''1645840''>these</span> <span m=''1646190''>guys</span> <span m=''1647280''>is</span>
  <span m=''1647470''>replaced</span> <span m=''1648120''>by</span> <span m=''1648290''>a</span>
  <span m=''1648370''>tree</span> <span m=''1648740''>that</span> <span m=''1648940''>looks</span>
  <span m=''1649200''>like</span> <span m=''1649490''>this</span> <span m=''1650450''>with</span>
  <span m=''1650610''>as</span> <span m=''1650720''>many</span> <span m=''1651050''>leaves</span>
  <span m=''1651730''>as</span> <span m=''1656050''>the</span> <span m=''1656130''>number</span>
  <span m=''1656380''>here</span> <span m=''1656620''>indicates.</span> <span m=''1658900''>So</span>
  <span m=''1659570''>once</span> <span m=''1659760''>again,</span> <span m=''1659980''>this</span>
  <span m=''1660170''>would</span> <span m=''1660330''>be</span> <span m=''1660560''>the</span>
  <span m=''1660660''>one</span> <span m=''1660880''>with</span> <span m=''1660970''>the</span>
  <span m=''1661060''>longest</span> <span m=''1661500''>span</span> <span m=''1662310''>because</span>
  <span m=''1662580''>this</span> <span m=''1662740''>would</span> <span m=''1662880''>be</span>
  <span m=''1663110''>log</span> <span m=''1663480''>of</span> <span m=''1663580''>the</span>
  <span m=''1663640''>largest</span> <span m=''1664140''>number.</span> <span m=''1664990''>But</span>
  <span m=''1665210''>basically,</span> <span m=''1665750''>each</span> <span m=''1665970''>one</span>
  <span m=''1666120''>of</span> <span m=''1666200''>these</span> <span m=''1666460''>would</span>
  <span m=''1666600''>be</span> <span m=''1666770''>a</span> <span m=''1666820''>tree</span>
  <span m=''1668550''>that</span> <span m=''1668720''>came</span> <span m=''1668990''>from</span>
  <span m=''1669160''>this.</span> <span m=''1669640''>Is</span> <span m=''1669830''>that</span>
  <span m=''1670020''>clear?</span> <span m=''1670200''>That''s</span> <span m=''1670410''>a</span>
  <span m=''1670450''>great</span> <span m=''1670670''>question.</span> <span m=''1672070''>Anybody</span>
  <span m=''1672440''>else</span> <span m=''1672600''>have</span> <span m=''1672750''>as</span>
  <span m=''1672900''>illuminating</span> <span m=''1673580''>questions</span> <span
  m=''1674060''>as</span> <span m=''1674180''>those?</span> <span m=''1674670''>Everybody</span>
  <span m=''1675060''>understand</span> <span m=''1675500''>that</span> <span m=''1675660''>explanation,</span>
  <span m=''1677170''>what</span> <span m=''1677370''>the</span> <span m=''1677450''>tree</span>
  <span m=''1677630''>would</span> <span m=''1677760''>look</span> <span m=''1677960''>like?</span>
  <span m=''1678310''>OK,</span> <span m=''1679700''>good.</span> <span m=''1687420''>Get</span>
  </p><p><span m=''1690140''>So</span> <span m=''1690310''>the</span> <span m=''1690390''>parallelism</span>
  <span m=''1691050''>here</span> <span m=''1691360''>is</span> <span m=''1692700''>n</span>
  <span m=''1692910''>squared</span> <span m=''1693370''>over</span> <span m=''1693570''>log</span>
  <span m=''1694000''>n.</span> <span m=''1695022''>Now</span> <span m=''1695450''>it''s</span>
  <span m=''1695790''>tempting,</span> <span m=''1696350''>when</span> <span m=''1696470''>you</span>
  <span m=''1696580''>do</span> <span m=''1696710''>parallel</span> <span m=''1697090''>programming,
  to</span> <span m=''1697590''>say</span> <span m=''1697790''>therefore,</span> <span
  m=''1698220''>this</span> <span m=''1698440''>is</span> <span m=''1698630''>better</span>
  <span m=''1699340''>parallel</span> <span m=''1699810''>code.</span> <span m=''1704190''>And</span>
  <span m=''1704360''>the</span> <span m=''1704520''>reason</span> <span m=''1704860''>is,</span>
  <span m=''1705040''>well,</span> <span m=''1705280''>it</span> <span m=''1705370''>does</span>
  <span m=''1705600''>asymptotically</span> <span m=''1706370''>have</span> <span
  m=''1706520''>more</span> <span m=''1706760''>parallelism.</span> <span m=''1707430''>But</span>
  <span m=''1707710''>generally</span> <span m=''1708170''>when</span> <span m=''1708350''>you''re</span>
  <span m=''1708520''>programming,</span> <span m=''1709720''>you''re</span> <span
  m=''1709990''>not</span> <span m=''1710900''>trying</span> <span m=''1711110''>to</span>
  <span m=''1711150''>get</span> <span m=''1711410''>the</span> <span m=''1711500''>most</span>
  <span m=''1711980''>parallelism.</span> <span m=''1713120''>What</span> <span m=''1713380''>you''re</span>
  <span m=''1713430''>trying</span> <span m=''1713620''>to</span> <span m=''1713810''>do</span>
  <span m=''1714000''>is</span> <span m=''1714170''>get</span> <span m=''1714400''>sufficient</span>
  <span m=''1715210''>parallelism.</span> </p><p><span m=''1717840''>So</span> <span
  m=''1718190''>if</span> <span m=''1718400''>n</span> <span m=''1718890''>is</span>
  <span m=''1719450''>sufficiently</span> <span m=''1720120''>large,</span> <span
  m=''1722090''>it''s</span> <span m=''1722300''>going</span> <span m=''1722390''>to</span>
  <span m=''1722490''>be</span> <span m=''1722680''>way</span> <span m=''1722960''>more--</span>
  <span m=''1723470''>if</span> <span m=''1723590''>n</span> <span m=''1723790''>is</span>
  <span m=''1723920''>a</span> <span m=''1723970''>million--</span> <span m=''1724710''>which</span>
  <span m=''1724870''>is</span> <span m=''1725050''>typical</span> <span m=''1725480''>problem</span>
  <span m=''1725840''>size</span> <span m=''1726290''>for</span> <span m=''1726380''>a</span>
  <span m=''1726480''>loop,</span> <span m=''1726780''>for</span> <span m=''1726900''>example,</span>
  <span m=''1727360''>for</span> <span m=''1727500''>a</span> <span m=''1727540''>big</span>
  <span m=''1727770''>loop,</span> <span m=''1728090''>or</span> <span m=''1728470''>even</span>
  <span m=''1728720''>if</span> <span m=''1728820''>it''s</span> <span m=''1728970''>a</span>
  <span m=''1729020''>few</span> <span m=''1729230''>thousand</span> <span m=''1729720''>or</span>
  <span m=''1729810''>whatever--</span> <span m=''1731180''>it</span> <span m=''1731420''>may</span>
  <span m=''1731650''>be</span> <span m=''1731860''>just</span> <span m=''1732220''>fine</span>
  <span m=''1732850''>to</span> <span m=''1732990''>have</span> <span m=''1733170''>parallelism</span>
  <span m=''1733800''>on</span> <span m=''1733960''>the</span> <span m=''1734090''>order</span>
  <span m=''1734430''>of</span> <span m=''1735820''>1,000,</span> <span m=''1737550''>which</span>
  <span m=''1737760''>is</span> <span m=''1737850''>what</span> <span m=''1738040''>the</span>
  <span m=''1738120''>first</span> <span m=''1738450''>one</span> <span m=''1738630''>gives</span>
  <span m=''1738840''>you.</span> <span m=''1740720''>So</span> <span m=''1741030''>1,000</span>
  <span m=''1741570''>iterations</span> <span m=''1742140''>is</span> <span m=''1742410''>generally</span>
  <span m=''1742810''>a</span> <span m=''1742860''>small</span> <span m=''1743220''>number</span>
  <span m=''1743450''>of</span> <span m=''1743520''>iterations.</span> <span m=''1745310''>So</span>
  <span m=''1745550''>1,000</span> <span m=''1745960''>by</span> <span m=''1746110''>1,000</span>
  <span m=''1746860''>matrix</span> <span m=''1747280''>is</span> <span m=''1747530''>going</span>
  <span m=''1747630''>to</span> <span m=''1747720''>generate</span> <span m=''1748150''>parallelism</span>
  <span m=''1748570''>of</span> <span m=''1748670''>1,000.</span> <span m=''1749470''>Here,</span>
  <span m=''1749750''>we''re</span> <span m=''1749910''>going</span> <span m=''1750030''>to</span>
  <span m=''1750080''>get</span> <span m=''1750310''>a</span> <span m=''1750370''>parallelism</span>
  <span m=''1750930''>of</span> <span m=''1751010''>1</span> <span m=''1751110''>million</span>
  <span m=''1751480''>divided</span> <span m=''1751870''>by</span> <span m=''1752040''>about</span>
  <span m=''1752370''>20,</span> <span m=''1752960''>log</span> <span m=''1753330''>of</span>
  <span m=''1754280''>10</span> <span m=''1754490''>or</span> <span m=''1754570''>20,</span>
  <span m=''1756340''>so</span> <span m=''1756680''>like</span> <span m=''1756880''>100,000.</span>
  </p><p><span m=''1758010''>But</span> <span m=''1759090''>if</span> <span m=''1761250''>I
  have</span> <span m=''1761575''>1,000</span> <span m=''1761900''>by</span> <span
  m=''1762040''>1,000</span> <span m=''1762440''>matrix,</span> <span m=''1767600''>the</span>
  <span m=''1767750''>difference</span> <span m=''1768160''>between</span> <span m=''1768520''>having</span>
  <span m=''1768870''>parallelism</span> <span m=''1769380''>of</span> <span m=''1769500''>1,000</span>
  <span m=''1769830''>and</span> <span m=''1770160''>parallelism</span> <span m=''1770580''>of</span>
  <span m=''1771390''>100,000,</span> <span m=''1773140''>when</span> <span m=''1773300''>I''m</span>
  <span m=''1773420''>running</span> <span m=''1773710''>on</span> <span m=''1775820''>100</span>
  <span m=''1776210''>cores,</span> <span m=''1776570''>let''s</span> <span m=''1777035''>say,</span>
  <span m=''1777500''>it</span> <span m=''1777540''>doesn''t</span> <span m=''1777710''>matter.</span>
  <span m=''1778440''>Up</span> <span m=''1778590''>to</span> <span m=''1778700''>100</span>
  <span m=''1778970''>cores,</span> <span m=''1779310''>it</span> <span m=''1779410''>doesn''t</span>
  <span m=''1779680''>matter.</span> <span m=''1780740''>And</span> <span m=''1780890''>in</span>
  <span m=''1781050''>fact,</span> <span m=''1781350''>running</span> <span m=''1781650''>this
  on</span> <span m=''1781790''>100</span> <span m=''1782290''>cores,</span> <span
  m=''1782720''>that''s</span> <span m=''1782970''>really</span> <span m=''1783400''>a</span>
  <span m=''1783540''>tiny</span> <span m=''1784220''>problem</span> <span m=''1785270''>compared
  to</span> <span m=''1785600''>the</span> <span m=''1785690''>amount</span> <span
  m=''1785930''>of</span> <span m=''1785980''>memory</span> <span m=''1786410''>you''re</span>
  <span m=''1786580''>going</span> <span m=''1786670''>to</span> <span m=''1786750''>get.</span>
  <span m=''1788670''>1,000</span> <span m=''1788955''>by</span> <span m=''1789240''>1,000</span>
  <span m=''1789470''>matrix</span> <span m=''1789860''>is</span> <span m=''1789990''>tiny</span>
  <span m=''1792760''>when</span> <span m=''1793040''>it</span> <span m=''1793110''>comes</span>
  <span m=''1793410''>to</span> <span m=''1793520''>the</span> <span m=''1795420''>size</span>
  <span m=''1795770''>of</span> <span m=''1795840''>memory</span> <span m=''1796160''>that</span>
  <span m=''1796290''>you''re</span> <span m=''1796390''>going</span> <span m=''1796490''>to</span>
  <span m=''1796580''>have</span> <span m=''1796660''>access</span> <span m=''1797120''>to</span>
  <span m=''1797310''>and</span> <span m=''1797450''>so</span> <span m=''1797580''>forth.</span>
  </p><p><span m=''1798390''>So</span> <span m=''1798570''>for</span> <span m=''1798700''>big</span>
  <span m=''1798980''>problems</span> <span m=''1799480''>and</span> <span m=''1799620''>so</span>
  <span m=''1799760''>forth</span> <span m=''1799960''>you</span> <span m=''1800090''>really</span>
  <span m=''1800300''>want</span> <span m=''1800460''>to</span> <span m=''1800510''>look</span>
  <span m=''1800760''>at</span> <span m=''1800880''>this</span> <span m=''1801120''>and</span>
  <span m=''1801260''>say,</span> <span m=''1805220''>of</span> <span m=''1805540''>things</span>
  <span m=''1807250''>that</span> <span m=''1807450''>have</span> <span m=''1807660''>ample</span>
  <span m=''1807970''>parallelism,</span> <span m=''1808650''>which</span> <span m=''1808850''>ones</span>
  <span m=''1809310''>really</span> <span m=''1809730''>are</span> <span m=''1809820''>going</span>
  <span m=''1809940''>to</span> <span m=''1809980''>give</span> <span m=''1810150''>me</span>
  <span m=''1811260''>the</span> <span m=''1811450''>best</span> <span m=''1811760''>bang</span>
  <span m=''1812320''>for</span> <span m=''1812450''>the</span> <span m=''1812570''>buck</span>
  <span m=''1813420''>for</span> <span m=''1813850''>reasonable</span> <span m=''1814360''>machine</span>
  <span m=''1814750''>sizes?</span> <span m=''1818300''>That''s</span> <span m=''1818830''>different</span>
  <span m=''1819190''>from</span> <span m=''1819980''>things</span> <span m=''1820230''>like</span>
  <span m=''1820460''>work or</span> <span m=''1820950''>serial</span> <span m=''1821370''>running</span>
  <span m=''1821640''>time.</span> <span m=''1822240''>Usually</span> <span m=''1822630''>less</span>
  <span m=''1824050''>running</span> <span m=''1824310''>time</span> <span m=''1824600''>is</span>
  <span m=''1824710''>better,</span> <span m=''1825880''>and</span> <span m=''1826180''>it''s</span>
  <span m=''1826360''>always</span> <span m=''1826730''>better.</span> <span m=''1827970''>But</span>
  <span m=''1828080''>here</span> <span m=''1828960''>parallelism--</span> <span m=''1830170''>yes,</span>
  <span m=''1830930''>it''s</span> <span m=''1831190''>good</span> <span m=''1831520''>to</span>
  <span m=''1831810''>minimize</span> <span m=''1832390''>your</span> <span m=''1832580''>span,</span>
  <span m=''1834390''>but</span> <span m=''1834640''>you</span> <span m=''1834730''>don''t</span>
  <span m=''1834940''>have</span> <span m=''1835150''>to</span> <span m=''1835260''>minimize</span>
  <span m=''1835830''>it</span> <span m=''1837290''>extremely.</span> <span m=''1838680''>You</span>
  <span m=''1838760''>just</span> <span m=''1838970''>have</span> <span m=''1839070''>to</span>
  <span m=''1839140''>get it</span> <span m=''1839410''>small</span> <span m=''1839820''>enough,</span>
  <span m=''1841600''>whereas</span> <span m=''1841870''>the</span> <span m=''1841960''>work</span>
  <span m=''1842310''>term,</span> <span m=''1843220''>that</span> <span m=''1843490''>you</span>
  <span m=''1843620''>really</span> <span m=''1843850''>want</span> <span m=''1844030''>to</span>
  <span m=''1844090''>minimize,</span> <span m=''1845120''>because</span> <span m=''1845320''>that''s</span>
  <span m=''1845570''>what</span> <span m=''1845680''>you''re</span> <span m=''1845780''>going</span>
  <span m=''1845860''>to</span> <span m=''1845960''>have</span> <span m=''1846050''>to</span>
  <span m=''1846150''>do,</span> <span m=''1846310''>even</span> <span m=''1846610''>in</span>
  <span m=''1846700''>a</span> <span m=''1846970''>serial</span> <span m=''1847250''>implementation.</span>
  <span m=''1848420''>Question.</span> </p><p><span m=''1849780''>AUDIENCE: So</span>
  <span m=''1850245''>are</span> <span m=''1850710''>you</span> <span m=''1851175''>suggesting</span>
  <span m=''1851640''>that the</span> <span m=''1852105''>other</span> <span m=''1852570''>code</span>
  <span m=''1853035''>was OK?</span> </p><p><span m=''1855800''>CHARLES LEISERSON:
  We''re</span> <span m=''1855940''>going</span> <span m=''1856030''>to</span> <span
  m=''1856090''>look</span> <span m=''1856470''>a</span> <span m=''1856560''>little</span>
  <span m=''1856800''>bit</span> <span m=''1858030''>closer</span> <span m=''1858610''>at</span>
  <span m=''1859050''>the</span> <span m=''1859230''>issue</span> <span m=''1859590''>of</span>
  <span m=''1859820''>overheads.</span> <span m=''1862210''>We''re</span> <span m=''1862610''>now</span>
  <span m=''1862790''>going</span> <span m=''1862910''>to</span> <span m=''1863000''>take</span>
  <span m=''1863210''>a</span> <span m=''1863280''>look</span> <span m=''1863460''>at</span>
  <span m=''1863530''>what''s</span> <span m=''1863770''>the</span> <span m=''1863850''>difference</span>
  <span m=''1864200''>between</span> <span m=''1864520''>these</span> <span m=''1864730''>two</span>
  <span m=''1864970''>codes?</span> <span m=''1865930''>We''ll</span> <span m=''1866070''>come</span>
  <span m=''1866240''>back</span> <span m=''1866440''>to</span> <span m=''1866530''>that</span>
  <span m=''1866650''>in</span> <span m=''1866770''>a</span> <span m=''1866810''>minute.</span>
  <span m=''1868320''>The</span> <span m=''1868760''>way</span> <span m=''1868900''>I</span>
  <span m=''1868970''>want</span> <span m=''1869110''>to</span> <span m=''1869180''>do</span>
  <span m=''1869490''>it is</span> <span m=''1869850''>take</span> <span m=''1870100''>a</span>
  <span m=''1870190''>look</span> <span m=''1871850''>at</span> <span m=''1872110''>the</span>
  <span m=''1872270''>issue</span> <span m=''1872510''>of</span> <span m=''1872620''>overheads</span>
  <span m=''1873570''>with</span> <span m=''1873820''>a</span> <span m=''1873890''>simpler</span>
  <span m=''1874370''>example,</span> <span m=''1875920''>where</span> <span m=''1876090''>we</span>
  <span m=''1876190''>can</span> <span m=''1876340''>see</span> <span m=''1876590''>what''s</span>
  <span m=''1876790''>really</span> <span m=''1877040''>going</span> <span m=''1877370''>on.</span>
  <span m=''1878380''>So</span> <span m=''1878650''>here,</span> <span m=''1879080''>what</span>
  <span m=''1879300''>I''ve</span> <span m=''1879440''>done</span> <span m=''1879610''>is</span>
  <span m=''1879770''>I''ve</span> <span m=''1879940''>got</span> <span m=''1882000''>a</span>
  <span m=''1882250''>loop</span> <span m=''1882580''>that</span> <span m=''1882710''>is</span>
  <span m=''1882850''>basically</span> <span m=''1883240''>just</span> <span m=''1883480''>doing</span>
  <span m=''1883720''>vector</span> <span m=''1884100''>addition.</span> <span m=''1885520''>It''s</span>
  <span m=''1885680''>adding</span> <span m=''1886550''>for</span> <span m=''1887170''>i</span>
  <span m=''1887330''>equals</span> <span m=''1887590''>0</span> <span m=''1888040''>to
  n</span> <span m=''1888450''>minus</span> <span m=''1888780''>1,</span> <span m=''1889790''>add</span>
  <span m=''1891740''>b</span> <span m=''1892110''>of</span> <span m=''1892440''>i</span>
  <span m=''1892630''>into</span> <span m=''1892890''>a</span> <span m=''1893270''>of
  i.</span> <span m=''1896120''>Pretty</span> <span m=''1896300''>simple</span> <span
  m=''1896590''>code,</span> <span m=''1896900''>and</span> <span m=''1897130''>we</span>
  <span m=''1897220''>want</span> <span m=''1897390''>to</span> <span m=''1897430''>make</span>
  <span m=''1897630''>that</span> <span m=''1897860''>be a</span> <span m=''1898020''>parallel</span>
  <span m=''1898440''>loop.</span> </p><p><span m=''1900660''>So</span> <span m=''1900870''>I</span>
  <span m=''1900940''>get</span> <span m=''1901130''>a</span> <span m=''1901180''>recursion</span>
  <span m=''1901740''>tree</span> <span m=''1902010''>that</span> <span m=''1902150''>looks</span>
  <span m=''1902410''>like</span> <span m=''1902650''>this,</span> <span m=''1903860''>where</span>
  <span m=''1903990''>I</span> <span m=''1904170''>have</span> <span m=''1904290''>constant</span>
  <span m=''1904800''>work</span> <span m=''1905300''>at</span> <span m=''1905460''>every</span>
  <span m=''1906250''>step</span> <span m=''1906600''>there.</span> <span m=''1907170''>And</span>
  <span m=''1907380''>of</span> <span m=''1907470''>course,</span> <span m=''1907760''>the</span>
  <span m=''1907850''>work</span> <span m=''1908170''>is</span> <span m=''1908320''>order</span>
  <span m=''1908640''>n,</span> <span m=''1909460''>because</span> <span m=''1909730''>I''ve</span>
  <span m=''1909880''>got</span> <span m=''1910200''>n</span> <span m=''1911820''>leaves.</span>
  <span m=''1912500''>And</span> <span m=''1912730''>the</span> <span m=''1912930''>number</span>
  <span m=''1913260''>of</span> <span m=''1913370''>internal</span> <span m=''1913800''>nodes,</span>
  <span m=''1914500''>the</span> <span m=''1914890''>control,</span> <span m=''1915330''>is</span>
  <span m=''1915420''>all</span> <span m=''1915670''>constant</span> <span m=''1916590''>size</span>
  <span m=''1916930''>strands</span> <span m=''1917420''>there.</span> <span m=''1917600''>So</span>
  <span m=''1917760''>this</span> <span m=''1917940''>is</span> <span m=''1918050''>all</span>
  <span m=''1918390''>just</span> <span m=''1918620''>order</span> <span m=''1918940''>n</span>
  <span m=''1919250''>for</span> <span m=''1919390''>work.</span> <span m=''1920170''>And</span>
  <span m=''1920440''>the</span> <span m=''1920510''>span</span> <span m=''1921040''>is</span>
  <span m=''1921330''>basically</span> <span m=''1921850''>log</span> <span m=''1922220''>n,</span>
  <span m=''1922420''>as</span> <span m=''1922550''>we''ve</span> <span m=''1922750''>seen,</span>
  <span m=''1923220''>by</span> <span m=''1923350''>going</span> <span m=''1923830''>down</span>
  <span m=''1924230''>one</span> <span m=''1924380''>of</span> <span m=''1924450''>these</span>
  <span m=''1924670''>paths,</span> <span m=''1925060''>for</span> <span m=''1925180''>example.</span>
  <span m=''1926000''>And</span> <span m=''1926140''>so</span> <span m=''1926240''>the</span>
  <span m=''1926330''>parallelism</span> <span m=''1926970''>for</span> <span m=''1927080''>this</span>
  <span m=''1927300''>is</span> <span m=''1927460''>order</span> <span m=''1927800''>n</span>
  <span m=''1928030''>over</span> <span m=''1928300''>log n.</span> <span m=''1931000''>So</span>
  <span m=''1931300''>a</span> <span m=''1931340''>very</span> <span m=''1931640''>simple</span>
  <span m=''1931940''>problem.</span> </p><p><span m=''1932550''>But</span> <span
  m=''1932660''>now</span> <span m=''1932820''>let''s</span> <span m=''1933030''>take</span>
  <span m=''1933230''>a</span> <span m=''1933300''>look</span> <span m=''1933600''>more</span>
  <span m=''1933860''>closely</span> <span m=''1934490''>at</span> <span m=''1934980''>the</span>
  <span m=''1935760''>overheads</span> <span m=''1936350''>here.</span> <span m=''1937280''>So</span>
  <span m=''1937460''>the</span> <span m=''1937560''>problem</span> <span m=''1938180''>is</span>
  <span m=''1938540''>that</span> <span m=''1938700''>this</span> <span m=''1938840''>work</span>
  <span m=''1939230''>term</span> <span m=''1939540''>contains</span> <span m=''1940100''>substantial</span>
  <span m=''1940850''>overhead.</span> <span m=''1942570''>In</span> <span m=''1942740''>other</span>
  <span m=''1942900''>words,</span> <span m=''1943330''>if</span> <span m=''1943460''>I</span>
  <span m=''1943620''>really</span> <span m=''1943910''>was</span> <span m=''1944150''>doing</span>
  <span m=''1944590''>that,</span> <span m=''1944890''>if</span> <span m=''1945020''>I</span>
  <span m=''1945110''>hadn''t</span> <span m=''1945440''>coarsened</span> <span m=''1945790''>the</span>
  <span m=''1945890''>recursion</span> <span m=''1946480''>at</span> <span m=''1946600''>all</span>
  <span m=''1947610''>in</span> <span m=''1947860''>the</span> <span m=''1948130''>implementation</span>
  <span m=''1948930''>of</span> <span m=''1949160''>cilk_for,</span> <span m=''1949710''>if</span>
  <span m=''1949840''>the</span> <span m=''1949990''>developers</span> <span m=''1950510''>hadn''t</span>
  <span m=''1950680''>done</span> <span m=''1950880''>that,</span> <span m=''1951420''>then</span>
  <span m=''1951760''>I''ve</span> <span m=''1951940''>got</span> <span m=''1952130''>a</span>
  <span m=''1952190''>function</span> <span m=''1952750''>call,</span> <span m=''1953420''>I''ve</span>
  <span m=''1953530''>got</span> <span m=''1953840''>n</span> <span m=''1954150''>function</span>
  <span m=''1954620''>calls</span> <span m=''1954860''>here</span> <span m=''1955260''>for</span>
  <span m=''1957210''>doing</span> <span m=''1957480''>a</span> <span m=''1957540''>single</span>
  <span m=''1957890''>addition</span> <span m=''1960200''>of</span> <span m=''1961240''>values</span>
  <span m=''1961740''>at</span> <span m=''1961820''>the leaves.</span> <span m=''1963000''>I''ve</span>
  <span m=''1963120''>got</span> <span m=''1963430''>n</span> <span m=''1963650''>minus</span>
  <span m=''1963980''>one</span> <span m=''1964170''>of</span> <span m=''1964250''>these</span>
  <span m=''1964530''>guys,</span> <span m=''1964860''>that''s</span> <span m=''1965050''>approximately</span>
  <span m=''1965730''>n,</span> <span m=''1967035''>and</span> <span m=''1967470''>I''ve</span>
  <span m=''1967600''>got</span> <span m=''1967850''>n</span> <span m=''1968060''>of</span>
  <span m=''1968150''>these</span> <span m=''1968450''>guys.</span> <span m=''1968940''>And</span>
  <span m=''1969120''>which</span> <span m=''1969310''>are</span> <span m=''1969370''>bigger,</span>
  <span m=''1969800''>these</span> <span m=''1970140''>guys</span> <span m=''1970490''>or</span>
  <span m=''1970600''>these</span> <span m=''1970900''>guys?</span> <span m=''1974540''>These</span>
  <span m=''1974800''>guys</span> <span m=''1975100''>are way</span> <span m=''1975350''>bigger.</span>
  <span m=''1975690''>They''ve</span> <span m=''1975880''>got</span> <span m=''1976040''>a</span>
  <span m=''1976090''>function</span> <span m=''1976500''>call</span> <span m=''1976820''>in</span>
  <span m=''1976890''>there.</span> <span m=''1978040''>This</span> <span m=''1978250''>guy</span>
  <span m=''1978360''>right</span> <span m=''1978520''>here</span> <span m=''1978760''>just</span>
  <span m=''1979040''>has</span> <span m=''1979190''>what?</span> <span m=''1979590''>One</span>
  <span m=''1979790''>floating</span> <span m=''1980130''>point</span> <span m=''1980340''>addition.</span>
  </p><p><span m=''1982300''>And</span> <span m=''1982450''>so</span> <span m=''1982540''>if
  I</span> <span m=''1982700''>really</span> <span m=''1983020''>was</span> <span
  m=''1983220''>doing</span> <span m=''1983460''>my</span> <span m=''1983590''>divide</span>
  <span m=''1983920''>and</span> <span m=''1984010''>conquer</span> <span m=''1984410''>down</span>
  <span m=''1984860''>to</span> <span m=''1986530''>a</span> <span m=''1987080''>single</span>
  <span m=''1987520''>element,</span> <span m=''1988350''>this</span> <span m=''1988550''>would</span>
  <span m=''1988690''>be</span> <span m=''1988840''>way</span> <span m=''1989590''>slower</span>
  <span m=''1992000''>on</span> <span m=''1992260''>one</span> <span m=''1992550''>processor</span>
  <span m=''1993230''>than</span> <span m=''1993400''>if</span> <span m=''1993540''>I</span>
  <span m=''1993640''>just</span> <span m=''1993900''>ran</span> <span m=''1994190''>it</span>
  <span m=''1994290''>with</span> <span m=''1994430''>a</span> <span m=''1994480''>for</span>
  <span m=''1994750''>loop.</span> <span m=''1995790''>Because if</span> <span m=''1995950''>I</span>
  <span m=''1996030''>do</span> <span m=''1996210''>a for</span> <span m=''1996490''>loop,</span>
  <span m=''1996690''>it''s</span> <span m=''1996800''>just</span> <span m=''1996990''>going</span>
  <span m=''1997090''>to</span> <span m=''1997140''>go</span> <span m=''1997310''>through,</span>
  <span m=''1997620''>and</span> <span m=''1998000''>the</span> <span m=''1998120''>overhead</span>
  <span m=''1998610''>it</span> <span m=''1998710''>has</span> <span m=''1999230''>is</span>
  <span m=''1999870''>incrementing</span> <span m=''2000970''>i</span> <span m=''2002290''>and</span>
  <span m=''2002480''>testing</span> <span m=''2004190''>for</span> <span m=''2004440''>termination.</span>
  <span m=''2005100''>That''s</span> <span m=''2005330''>it.</span> <span m=''2006160''>And</span>
  <span m=''2006300''>of</span> <span m=''2006370''>course,</span> <span m=''2006610''>that''s</span>
  <span m=''2006850''>a</span> <span m=''2006910''>predictable</span> <span m=''2007580''>branch,</span>
  <span m=''2009010''>because</span> <span m=''2009950''>it</span> <span m=''2010130''>almost</span>
  <span m=''2010500''>never</span> <span m=''2010780''>terminates</span> <span m=''2011310''>until</span>
  <span m=''2011600''>it</span> <span m=''2011650''>actually</span> <span m=''2012020''>terminates,</span>
  <span m=''2013060''>and</span> <span m=''2013220''>so</span> <span m=''2014070''>that''s</span>
  <span m=''2014580''>exactly the</span> <span m=''2015080''>sort</span> <span m=''2015280''>of</span>
  <span m=''2015360''>thing</span> <span m=''2015590''>that''s</span> <span m=''2015790''>going</span>
  <span m=''2015880''>to</span> <span m=''2015920''>have</span> <span m=''2016090''>a</span>
  <span m=''2016150''>really,</span> <span m=''2016520''>really</span> <span m=''2016760''>tight</span>
  <span m=''2017070''>loop</span> <span m=''2017310''>with</span> <span m=''2017470''>very</span>
  <span m=''2017690''>few</span> <span m=''2017880''>instructions.</span> </p><p><span
  m=''2018850''>But</span> <span m=''2019080''>in</span> <span m=''2019180''>the</span>
  <span m=''2019260''>parallel</span> <span m=''2019760''>implementation,</span> <span
  m=''2020500''>there''s</span> <span m=''2020680''>going</span> <span m=''2020750''>to</span>
  <span m=''2020820''>be</span> <span m=''2020920''>this</span> <span m=''2021130''>function</span>
  <span m=''2021490''>call</span> <span m=''2021790''>overhead</span> <span m=''2022190''>everywhere.</span>
  <span m=''2024590''>And</span> <span m=''2024770''>so</span> <span m=''2024910''>therefore,</span>
  <span m=''2025380''>this</span> <span m=''2025510''>cilk_for</span> <span m=''2026150''>loop</span>
  <span m=''2026380''>in</span> <span m=''2026540''>principle</span> <span m=''2027310''>would</span>
  <span m=''2027590''>not</span> <span m=''2027920''>be</span> <span m=''2028490''>as</span>
  <span m=''2028740''>efficient.</span> <span m=''2029430''>It</span> <span m=''2029570''>actually</span>
  <span m=''2029980''>is,</span> <span m=''2030520''>but</span> <span m=''2030760''>we''re</span>
  <span m=''2030930''>going</span> <span m=''2031020''>to</span> <span m=''2031060''>explain</span>
  <span m=''2031500''>why</span> <span m=''2031760''>it</span> <span m=''2031850''>is,</span>
  <span m=''2032290''>what</span> <span m=''2032530''>goes</span> <span m=''2032780''>on</span>
  <span m=''2033130''>in</span> <span m=''2033280''>the</span> <span m=''2033760''>runtime</span>
  <span m=''2034200''>system,</span> <span m=''2034530''>to</span> <span m=''2034610''>understand</span>
  <span m=''2035100''>that.</span> </p><p><span m=''2036760''>So</span> <span m=''2036940''>here''s</span>
  <span m=''2037220''>the</span> <span m=''2037360''>idea,</span> <span m=''2039800''>and</span>
  <span m=''2039990''>you</span> <span m=''2040110''>can</span> <span m=''2040290''>control</span>
  <span m=''2040780''>this</span> <span m=''2040990''>with</span> <span m=''2041090''>a</span>
  <span m=''2041190''>pragma.</span> <span m=''2042230''>So</span> <span m=''2042580''>a</span>
  <span m=''2042650''>pragma</span> <span m=''2043260''>is</span> <span m=''2043560''>a</span>
  <span m=''2043900''>statement</span> <span m=''2044870''>to</span> <span m=''2044990''>the</span>
  <span m=''2045620''>compiler</span> <span m=''2046200''>that</span> <span m=''2046340''>gives</span>
  <span m=''2046590''>it a</span> <span m=''2046720''>hint.</span> <span m=''2048070''>And</span>
  <span m=''2048239''>here,</span> <span m=''2048460''>the</span> <span m=''2048620''>pragma</span>
  <span m=''2049170''>says,</span> <span m=''2049639''>you</span> <span m=''2049870''>can</span>
  <span m=''2050110''>name</span> <span m=''2051440''>a</span> <span m=''2051570''>grain</span>
  <span m=''2051989''>size</span> <span m=''2052550''>and</span> <span m=''2052730''>give</span>
  <span m=''2052880''>it</span> <span m=''2052960''>a</span> <span m=''2053000''>value</span>
  <span m=''2053489''>of</span> <span m=''2053570''>g.</span> <span m=''2055389''>And</span>
  <span m=''2055460''>what</span> <span m=''2055639''>that</span> <span m=''2055889''>says</span>
  <span m=''2056310''>is</span> <span m=''2056600''>rather</span> <span m=''2057050''>than</span>
  <span m=''2057290''>just</span> <span m=''2057610''>doing</span> <span m=''2058050''>one</span>
  <span m=''2058500''>element</span> <span m=''2059000''>when</span> <span m=''2059120''>you</span>
  <span m=''2059199''>get</span> <span m=''2059420''>down</span> <span m=''2059659''>to</span>
  <span m=''2059730''>the</span> <span m=''2059820''>bottom</span> <span m=''2060170''>here,</span>
  <span m=''2061239''>do</span> <span m=''2061409''>g</span> <span m=''2061730''>elements</span>
  <span m=''2062449''>in</span> <span m=''2062590''>a</span> <span m=''2062639''>for</span>
  <span m=''2062980''>loop</span> <span m=''2063210''>when</span> <span m=''2063320''>you</span>
  <span m=''2063409''>get</span> <span m=''2063590''>down</span> <span m=''2063810''>to</span>
  <span m=''2063889''>the</span> <span m=''2063969''>bottom.</span> <span m=''2066750''>And</span>
  <span m=''2066900''>that way,</span> <span m=''2067650''>you</span> <span m=''2067699''>halt</span>
  <span m=''2068120''>the</span> <span m=''2068210''>recursion</span> <span m=''2068850''>earlier.</span>
  <span m=''2069880''>You</span> <span m=''2070139''>have</span> <span m=''2070330''>fewer
  of</span> <span m=''2070540''>these</span> <span m=''2071310''>internal</span> <span
  m=''2071800''>nodes.</span> <span m=''2072570''>And</span> <span m=''2072710''>if</span>
  <span m=''2072810''>you</span> <span m=''2072980''>make</span> <span m=''2073320''>the</span>
  <span m=''2073409''>grain</span> <span m=''2073750''>size</span> <span m=''2074150''>sufficiently</span>
  <span m=''2074739''>large,</span> <span m=''2076210''>the</span> <span m=''2076350''>cost</span>
  <span m=''2076760''>of</span> <span m=''2076840''>the</span> <span m=''2076969''>recursion</span>
  <span m=''2077310''>at</span> <span m=''2077380''>the</span> <span m=''2077480''>top</span>
  <span m=''2077800''>you</span> <span m=''2077900''>won''t</span> <span m=''2078100''>be</span>
  <span m=''2078260''>able</span> <span m=''2078420''>to</span> <span m=''2078489''>see.</span>
  </p><p><span m=''2080600''>So</span> <span m=''2080760''>let''s</span> <span m=''2080989''>analyze</span>
  <span m=''2081530''>what</span> <span m=''2081650''>happens</span> <span m=''2082210''>when</span>
  <span m=''2082360''>we</span> <span m=''2082480''>do</span> <span m=''2082630''>this.</span>
  <span m=''2083989''>So</span> <span m=''2084150''>we</span> <span m=''2084239''>can</span>
  <span m=''2084370''>understand</span> <span m=''2085190''>this</span> <span m=''2087380''>vis</span>
  <span m=''2087760''>a</span> <span m=''2088080''>vis</span> <span m=''2088270''>this</span>
  <span m=''2088560''>equation.</span> <span m=''2089190''>So</span> <span m=''2089500''>the</span>
  <span m=''2089650''>idea</span> <span m=''2090010''>here</span> <span m=''2090320''>is,</span>
  <span m=''2090699''>if</span> <span m=''2090870''>I</span> <span m=''2090949''>look</span>
  <span m=''2091210''>at</span> <span m=''2091300''>my</span> <span m=''2091480''>work,</span>
  <span m=''2093239''>imagine</span> <span m=''2093800''>that</span> <span m=''2094100''>t</span>
  <span m=''2094380''>iter</span> <span m=''2094699''>is</span> <span m=''2094850''>the</span>
  <span m=''2094960''>time</span> <span m=''2095340''>for</span> <span m=''2095520''>iteration</span>
  <span m=''2096199''>of</span> <span m=''2096320''>one</span> <span m=''2096560''>iteration</span>
  <span m=''2097030''>of</span> <span m=''2097120''>the</span> <span m=''2097210''>loop,</span>
  <span m=''2098290''>basic</span> <span m=''2098620''>time</span> <span m=''2098860''>for</span>
  <span m=''2098960''>one</span> <span m=''2099160''>iteration</span> <span m=''2099660''>of
  the</span> <span m=''2099740''>loop.</span> <span m=''2100490''>So</span> <span
  m=''2100760''>the</span> <span m=''2100870''>amount</span> <span m=''2101140''>of</span>
  <span m=''2101250''>work</span> <span m=''2101510''>that</span> <span m=''2101630''>I</span>
  <span m=''2101710''>have</span> <span m=''2101940''>to</span> <span m=''2102060''>do</span>
  <span m=''2102330''>is</span> <span m=''2102580''>n</span> <span m=''2102930''>times</span>
  <span m=''2103280''>the</span> <span m=''2103400''>time</span> <span m=''2104340''>for</span>
  <span m=''2104460''>the</span> <span m=''2104630''>iterations</span> <span m=''2105080''>of</span>
  <span m=''2105170''>the</span> <span m=''2105280''>loop.</span> <span m=''2106580''>And</span>
  <span m=''2106760''>then</span> <span m=''2106920''>depending</span> <span m=''2107320''>upon</span>
  <span m=''2107660''>my</span> <span m=''2107820''>grain</span> <span m=''2108260''>size,</span>
  <span m=''2109020''>I''ve</span> <span m=''2109210''>got</span> <span m=''2109430''>to</span>
  <span m=''2109510''>do</span> <span m=''2110430''>things</span> <span m=''2110690''>having</span>
  <span m=''2110980''>to</span> <span m=''2111020''>do</span> <span m=''2111140''>with</span>
  <span m=''2111240''>the</span> <span m=''2111390''>internal</span> <span m=''2111860''>nodes,</span>
  <span m=''2112850''>and</span> <span m=''2113050''>there''s</span> <span m=''2113220''>basically</span>
  <span m=''2113720''>going</span> <span m=''2113850''>to</span> <span m=''2113970''>be</span>
  <span m=''2114110''>n</span> <span m=''2114300''>over</span> <span m=''2114570''>g</span>
  <span m=''2114840''>of</span> <span m=''2114960''>those,</span> <span m=''2118440''>times</span>
  <span m=''2118820''>the</span> <span m=''2118930''>time</span> <span m=''2119260''>for</span>
  <span m=''2120100''>a</span> <span m=''2120180''>spawn,</span> <span m=''2121510''>which</span>
  <span m=''2121740''>is</span> <span m=''2121860''>I''m</span> <span m=''2122060''>saying</span>
  <span m=''2122380''>is</span> <span m=''2122510''>the</span> <span m=''2122620''>time</span>
  <span m=''2123260''>to</span> <span m=''2123370''>execute</span> <span m=''2123810''>one</span>
  <span m=''2123970''>of</span> <span m=''2124050''>these</span> <span m=''2124330''>things.</span>
  <span m=''2126110''>So</span> <span m=''2126320''>if</span> <span m=''2126510''>these</span>
  <span m=''2126770''>are</span> <span m=''2126850''>batched</span> <span m=''2127370''>into</span>
  <span m=''2127540''>groups</span> <span m=''2127900''>of</span> <span m=''2128100''>g,</span>
  <span m=''2129150''>then</span> <span m=''2129280''>there are</span> <span m=''2129410''>n</span>
  <span m=''2129640''>over</span> <span m=''2129910''>g</span> <span m=''2130210''>such</span>
  <span m=''2130530''>leaves.</span> <span m=''2132560''>There''s</span> <span m=''2132710''>a</span>
  <span m=''2132770''>minus</span> <span m=''2133150''>1</span> <span m=''2133380''>in</span>
  <span m=''2133470''>here,</span> <span m=''2133670''>but</span> <span m=''2133780''>it</span>
  <span m=''2133870''>doesn''t</span> <span m=''2134140''>matter.</span> <span m=''2134840''>It''s</span>
  <span m=''2135000''>basically</span> <span m=''2135540''>n</span> <span m=''2135690''>over</span>
  <span m=''2135930''>g</span> <span m=''2136210''>times</span> <span m=''2136510''>the</span>
  <span m=''2136600''>time</span> <span m=''2136950''>for</span> <span m=''2139250''>the</span>
  <span m=''2139490''>internal</span> <span m=''2139910''>nodes.</span> <span m=''2140700''>So</span>
  <span m=''2140870''>everybody</span> <span m=''2141220''>see</span> <span m=''2141480''>where</span>
  <span m=''2141720''>I''m</span> <span m=''2141800''>getting</span> <span m=''2142110''>this?</span>
  <span m=''2142740''>So I''m</span> <span m=''2142870''>trying</span> <span m=''2143100''>to</span>
  <span m=''2143190''>account</span> <span m=''2143610''>for</span> <span m=''2143680''>the</span>
  <span m=''2143780''>constants</span> <span m=''2144560''>in</span> <span m=''2144730''>the</span>
  <span m=''2144820''>implementation.</span> <span m=''2146620''>People</span> <span
  m=''2146930''>follow where</span> <span m=''2147330''>I''m</span> <span m=''2147470''>getting</span>
  <span m=''2147720''>this?</span> <span m=''2148000''>Ask</span> <span m=''2148250''>questions.</span>
  <span m=''2149180''>I</span> <span m=''2149250''>see</span> <span m=''2149420''>a</span>
  <span m=''2149470''>couple</span> <span m=''2149760''>of</span> <span m=''2150740''>people
  who</span> <span m=''2151010''>are</span> <span m=''2151110''>sort</span> <span
  m=''2151220''>of</span> <span m=''2151330''>going,</span> <span m=''2152270''>not</span>
  <span m=''2152920''>sure</span> <span m=''2153150''>I</span> <span m=''2153220''>understand.</span>
  <span m=''2157480''>Yes?</span> </p><p><span m=''2158260''>AUDIENCE: The</span>
  <span m=''2158650''>constants</span> <span m=''2159128''>[INAUDIBLE].</span> </p><p><span
  m=''2161040''>CHARLES LEISERSON: Yes.</span> <span m=''2161520''>So</span> <span
  m=''2161710''>basically,</span> <span m=''2162250''>the</span> <span m=''2162500''>constants</span>
  <span m=''2163170''>are</span> <span m=''2163400''>these</span> <span m=''2163720''>t</span>
  <span m=''2163950''>iter</span> <span m=''2164290''>and t</span> <span m=''2164650''>spawn.</span>
  <span m=''2165940''>So</span> <span m=''2166070''>t</span> <span m=''2166310''>spawn</span>
  <span m=''2166710''>is</span> <span m=''2166840''>the</span> <span m=''2166960''>time</span>
  <span m=''2167550''>to</span> <span m=''2167650''>execute</span> <span m=''2167830''>all</span>
  <span m=''2168130''>that</span> <span m=''2168400''>mess.</span> <span m=''2170310''>t</span>
  <span m=''2170630''>iter</span> <span m=''2171120''>is</span> <span m=''2171280''>the</span>
  <span m=''2171380''>time</span> <span m=''2171650''>to</span> <span m=''2171770''>execute</span>
  <span m=''2172320''>one</span> <span m=''2173360''>iteration</span> <span m=''2174660''>within</span>
  <span m=''2175000''>here.</span> <span m=''2175250''>I''m</span> <span m=''2175380''>doing,</span>
  <span m=''2175890''>in</span> <span m=''2176070''>this</span> <span m=''2176250''>case,</span>
  <span m=''2176890''>g</span> <span m=''2177140''>of</span> <span m=''2177230''>them.</span>
  <span m=''2177670''>So I</span> <span m=''2177980''>have n</span> <span m=''2178160''>over</span>
  <span m=''2178480''>g</span> <span m=''2179700''>leaves,</span> <span m=''2180530''>but</span>
  <span m=''2180750''>each</span> <span m=''2180960''>one</span> <span m=''2181140''>is</span>
  <span m=''2181260''>doing</span> <span m=''2181580''>g,</span> <span m=''2181960''>so</span>
  <span m=''2182100''>it''s</span> <span m=''2182270''>n</span> <span m=''2182430''>over</span>
  <span m=''2182630''>g</span> <span m=''2182860''>times</span> <span m=''2183290''>g,</span>
  <span m=''2184020''>which</span> <span m=''2184260''>is a</span> <span m=''2184350''>total</span>
  <span m=''2184700''>of n</span> <span m=''2185050''>iterations,</span> <span m=''2186070''>which</span>
  <span m=''2186240''>makes</span> <span m=''2186480''>sense.</span> <span m=''2186750''>I</span>
  <span m=''2186800''>should</span> <span m=''2186950''>be</span> <span m=''2187090''>doing</span>
  <span m=''2187340''>n</span> <span m=''2187490''>iterations</span> <span m=''2187775''>if</span>
  <span m=''2188060''>I''m</span> <span m=''2188980''>adding</span> <span m=''2189620''>two</span>
  <span m=''2189750''>vectors</span> <span m=''2190150''>here.</span> <span m=''2190460''>So</span>
  <span m=''2190600''>that''s</span> <span m=''2190830''>accounting</span> <span m=''2191240''>for</span>
  <span m=''2191390''>all</span> <span m=''2191630''>the</span> <span m=''2191720''>work</span>
  <span m=''2192010''>in</span> <span m=''2192120''>these</span> <span m=''2192360''>guys.</span>
  <span m=''2194200''>Then</span> <span m=''2194660''>in</span> <span m=''2194780''>addition,</span>
  <span m=''2195410''>I''ve</span> <span m=''2195650''>got</span> <span m=''2196200''>all</span>
  <span m=''2196480''>of</span> <span m=''2196580''>the</span> <span m=''2196660''>work</span>
  <span m=''2196980''>for</span> <span m=''2197110''>all</span> <span m=''2197240''>the</span>
  <span m=''2197470''>spawning,</span> <span m=''2198120''>which</span> <span m=''2198350''>is</span>
  <span m=''2198540''>n</span> <span m=''2198710''>over</span> <span m=''2198970''>g</span>
  <span m=''2199260''>times</span> <span m=''2199640''>t</span> <span m=''2199870''>spawn.</span>
  </p><p><span m=''2201790''>And</span> <span m=''2201920''>as</span> <span m=''2202090''>I</span>
  <span m=''2202140''>say,</span> <span m=''2202330''>you</span> <span m=''2202480''>can</span>
  <span m=''2202620''>play</span> <span m=''2202870''>with</span> <span m=''2203010''>this</span>
  <span m=''2203180''>yourself,</span> <span m=''2203720''>play</span> <span m=''2203840''>with</span>
  <span m=''2203950''>grain</span> <span m=''2204210''>size</span> <span m=''2204520''>yourself,</span>
  <span m=''2205130''>by</span> <span m=''2205240''>just</span> <span m=''2205400''>sticking</span>
  <span m=''2205780''>in</span> <span m=''2206010''>different</span> <span m=''2206320''>grain</span>
  <span m=''2206640''>size</span> <span m=''2207020''>directives.</span> <span m=''2207830''>Otherwise</span>
  <span m=''2208390''>it</span> <span m=''2208510''>turns</span> <span m=''2208780''>out</span>
  <span m=''2208930''>that</span> <span m=''2209170''>the</span> <span m=''2209670''>cilk</span>
  <span m=''2211270''>runtime</span> <span m=''2211770''>system</span> <span m=''2212160''>will</span>
  <span m=''2212410''>pick</span> <span m=''2214220''>what</span> <span m=''2214370''>it</span>
  <span m=''2214710''>deems</span> <span m=''2215150''>to</span> <span m=''2215260''>be</span>
  <span m=''2215500''>a</span> <span m=''2215640''>good</span> <span m=''2216040''>grain</span>
  <span m=''2216370''>size.</span> <span m=''2216930''>And</span> <span m=''2217080''>it</span>
  <span m=''2217180''>usually</span> <span m=''2217650''>does</span> <span m=''2217900''>a</span>
  <span m=''2217960''>good</span> <span m=''2218210''>job,</span> <span m=''2219550''>except</span>
  <span m=''2219910''>sometimes.</span> <span m=''2222080''>And</span> <span m=''2222190''>that''s</span>
  <span m=''2222470''>why</span> <span m=''2223290''>there''s</span> <span m=''2223520''>a</span>
  <span m=''2223580''>parameter</span> <span m=''2224060''>here.</span> <span m=''2225350''>So</span>
  <span m=''2225500''>if</span> <span m=''2225590''>there''s</span> <span m=''2225740''>a</span>
  <span m=''2225790''>parameter</span> <span m=''2226220''>there,</span> <span m=''2226410''>you</span>
  <span m=''2226570''>can</span> <span m=''2226720''>get</span> <span m=''2226870''>rid</span>
  <span m=''2227100''>of</span> <span m=''2229740''>that.</span> <span m=''2230160''>Yes?</span>
  </p><p><span m=''2233462''>AUDIENCE: Is the</span> <span m=''2233954''>pragma</span>
  <span m=''2234446''>something</span> <span m=''2234938''>that is</span> <span m=''2235430''>enforced,</span>
  <span m=''2235922''>or is it</span> <span m=''2236414''>something</span> <span m=''2236906''>that
  says,</span> <span m=''2237398''>hey--</span> </p><p><span m=''2238382''>CHARLES
  LEISERSON: It''s a</span> <span m=''2238874''>hint.</span> </p><p><span m=''2239366''>AUDIENCE:
  It''s a</span> <span m=''2239858''>hint.</span> </p><p><span m=''2240350''>CHARLES
  LEISERSON: Yes,</span> <span m=''2240680''>it''s</span> <span m=''2240820''>a</span>
  <span m=''2240920''>hint.</span> <span m=''2241885''>In other words,</span> <span
  m=''2242360''>compiler could</span> <span m=''2242835''>ignore it.</span> </p><p><span
  m=''2243310''>[? AUDIENCE: The compiler is ?]</span> <span m=''2243785''>going to
  be</span> <span m=''2244260''>like, oh,</span> <span m=''2244735''>that''s the</span>
  <span m=''2245210''>total</span> <span m=''2245685''>[INAUDIBLE]</span> <span m=''2246975''>constant.</span>
  </p><p><span m=''2248000''>CHARLES LEISERSON: It''s</span> <span m=''2248280''>supposed</span>
  <span m=''2248560''>to</span> <span m=''2248600''>be</span> <span m=''2248730''>something</span>
  <span m=''2249180''>that</span> <span m=''2249340''>gives</span> <span m=''2249540''>a</span>
  <span m=''2249620''>hint</span> <span m=''2249920''>for</span> <span m=''2250080''>performance</span>
  <span m=''2250650''>reasons</span> <span m=''2251050''>but</span> <span m=''2251270''>does</span>
  <span m=''2251440''>not</span> <span m=''2251870''>affect</span> <span m=''2252240''>the</span>
  <span m=''2252310''>correctness</span> <span m=''2252800''>of</span> <span m=''2252890''>the</span>
  <span m=''2252980''>program.</span> <span m=''2255120''>So</span> <span m=''2255290''>the</span>
  <span m=''2255390''>program</span> <span m=''2255810''>is</span> <span m=''2256110''>going</span>
  <span m=''2256220''>to</span> <span m=''2256260''>be</span> <span m=''2256840''>doing</span>
  <span m=''2257060''>the</span> <span m=''2257140''>same</span> <span m=''2257420''>thing</span>
  <span m=''2257650''>regardless.</span> <span m=''2258350''>The</span> <span m=''2258450''>question</span>
  <span m=''2258830''>is,</span> <span m=''2259310''>here''s</span> <span m=''2259540''>a</span>
  <span m=''2259610''>hint</span> <span m=''2259920''>to</span> <span m=''2260000''>the</span>
  <span m=''2260090''>compiler</span> <span m=''2260580''>and</span> <span m=''2260690''>the</span>
  <span m=''2260800''>runtime</span> <span m=''2261210''>system.</span> <span m=''2264020''>And</span>
  <span m=''2264210''>so</span> <span m=''2264350''>then</span> <span m=''2264530''>it''s</span>
  <span m=''2264710''>picked</span> <span m=''2265080''>at--</span> <span m=''2266788''>yeah?</span>
  </p><p><span m=''2269268''>AUDIENCE: My</span> <span m=''2269770''>question</span>
  <span m=''2270260''>is,</span> <span m=''2271240''>so</span> <span m=''2271730''>there''s
  these</span> <span m=''2272220''>cases</span> <span m=''2272638''>where</span> <span
  m=''2273056''>you say</span> <span m=''2273474''>that the</span> <span m=''2273892''>runtime</span>
  <span m=''2274310''>system</span> <span m=''2274740''>fails</span> <span m=''2275170''>to</span>
  <span m=''2275600''>find an</span> <span m=''2276030''>appropriate</span> <span
  m=''2276460''>value</span> <span m=''2276931''>for that</span> <span m=''2277402''>[INAUDIBLE].</span>
  <span m=''2277873''>I mean,</span> <span m=''2278344''>basically,</span> <span m=''2278815''>chooses</span>
  <span m=''2279286''>one that''s</span> <span m=''2279757''>not as</span> <span m=''2280228''>good.</span>
  <span m=''2280699''>If you put</span> <span m=''2281170''>a pragma on it,</span>
  <span m=''2281641''>will the</span> <span m=''2282112''>runtime</span> <span m=''2282583''>system</span>
  <span m=''2283054''>choose the one</span> <span m=''2283525''>that you give it,</span>
  <span m=''2283996''>or still choose--</span> </p><p><span m=''2284890''>CHARLES
  LEISERSON: No,</span> <span m=''2285530''>if you</span> <span m=''2285830''>give</span>
  <span m=''2286000''>it,</span> <span m=''2286200''>the</span> <span m=''2286290''>runtime</span>
  <span m=''2286670''>system</span> <span m=''2286980''>will--</span> <span m=''2287840''>in</span>
  <span m=''2287980''>the</span> <span m=''2288070''>current</span> <span m=''2288410''>implementation,</span>
  <span m=''2289510''>it</span> <span m=''2289660''>always</span> <span m=''2290050''>picks</span>
  <span m=''2290630''>whatever</span> <span m=''2290850''>you</span> <span m=''2291040''>say</span>
  <span m=''2291290''>is</span> <span m=''2291450''>here.</span> <span m=''2292340''>And</span>
  <span m=''2292440''>that</span> <span m=''2292590''>can</span> <span m=''2292720''>be</span>
  <span m=''2292850''>an</span> <span m=''2292900''>expression.</span> <span m=''2293215''>You
  can</span> <span m=''2293530''>evaluate</span> <span m=''2294130''>something</span>
  <span m=''2294460''>there.</span> <span m=''2295490''>It''s</span> <span m=''2295690''>not</span>
  <span m=''2295880''>just</span> <span m=''2296070''>a</span> <span m=''2296120''>constant.</span>
  <span m=''2296540''>It</span> <span m=''2296620''>could</span> <span m=''2296880''>be</span>
  <span m=''2297750''>maximum</span> <span m=''2298370''>of</span> <span m=''2298490''>this</span>
  <span m=''2298800''>and</span> <span m=''2299040''>that</span> <span m=''2299280''>times</span>
  <span m=''2300070''>whatever,</span> <span m=''2300530''>et cetera.</span> <span
  m=''2302655''>Is</span> <span m=''2303140''>that</span> <span m=''2303240''>good?</span>
  <span m=''2305670''>So</span> <span m=''2305830''>this</span> <span m=''2306070''>is</span>
  <span m=''2306230''>a</span> <span m=''2306330''>description</span> <span m=''2306900''>of</span>
  <span m=''2306990''>the</span> <span m=''2307080''>work.</span> <span m=''2307390''>Now</span>
  <span m=''2307610''>let''s</span> <span m=''2307850''>get</span> <span m=''2307960''>a</span>
  <span m=''2308070''>description</span> <span m=''2309470''>with</span> <span m=''2309610''>the</span>
  <span m=''2309750''>constants</span> <span m=''2310400''>again</span> <span m=''2311200''>of</span>
  <span m=''2311360''>the</span> <span m=''2311440''>span.</span> <span m=''2313840''>So</span>
  <span m=''2314020''>what</span> <span m=''2314220''>is</span> <span m=''2314350''>going</span>
  <span m=''2314460''>to</span> <span m=''2314510''>be</span> <span m=''2314640''>the</span>
  <span m=''2314760''>constants</span> <span m=''2315360''>for</span> <span m=''2315430''>the</span>
  <span m=''2315520''>span?</span> <span m=''2320040''>Well,</span> <span m=''2321120''>I''m</span>
  <span m=''2321240''>executing</span> <span m=''2321890''>this</span> <span m=''2322140''>part</span>
  <span m=''2322400''>in</span> <span m=''2322520''>here</span> <span m=''2322800''>now</span>
  <span m=''2323010''>serially.</span> </p><p><span m=''2326320''>So</span> <span
  m=''2326760''>for</span> <span m=''2326850''>the</span> <span m=''2326970''>span</span>
  <span m=''2327390''>part,</span> <span m=''2327640''>we''re</span> <span m=''2327730''>basically</span>
  <span m=''2328250''>going</span> <span m=''2328390''>to</span> <span m=''2328440''>go</span>
  <span m=''2328630''>down</span> <span m=''2328980''>on</span> <span m=''2329120''>one</span>
  <span m=''2329260''>of</span> <span m=''2329320''>these</span> <span m=''2329550''>paths
  and</span> <span m=''2330010''>back</span> <span m=''2330360''>up</span> <span m=''2330980''>I''m</span>
  <span m=''2331050''>not</span> <span m=''2331230''>sure</span> <span m=''2331380''>which</span>
  <span m=''2331570''>one,</span> <span m=''2331870''>but</span> <span m=''2332220''>they''re</span>
  <span m=''2332330''>basically</span> <span m=''2332980''>all</span> <span m=''2333580''>fairly</span>
  <span m=''2333890''>symmetric.</span> <span m=''2335330''>But</span> <span m=''2335530''>then</span>
  <span m=''2335770''>when</span> <span m=''2335900''>I</span> <span m=''2335950''>get</span>
  <span m=''2336140''>to</span> <span m=''2336210''>the</span> <span m=''2336300''>leaf,</span>
  <span m=''2336690''>I''m</span> <span m=''2336860''>executing</span> <span m=''2337400''>the</span>
  <span m=''2337500''>leaf</span> <span m=''2337840''>serially.</span> <span m=''2340110''>So</span>
  <span m=''2340320''>I''m</span> <span m=''2340400''>going</span> <span m=''2340480''>to</span>
  <span m=''2340550''>have</span> <span m=''2340860''>whatever</span> <span m=''2341260''>the</span>
  <span m=''2341410''>cost</span> <span m=''2341850''>is,</span> <span m=''2342020''>g</span>
  <span m=''2342400''>times</span> <span m=''2343100''>the</span> <span m=''2343230''>time</span>
  <span m=''2343790''>per</span> <span m=''2343960''>iteration,</span> <span m=''2344880''>is</span>
  <span m=''2345040''>going</span> <span m=''2345140''>to</span> <span m=''2345180''>be</span>
  <span m=''2345260''>executed</span> <span m=''2346160''>serially,</span> <span m=''2346750''>plus</span>
  <span m=''2347220''>now</span> <span m=''2347520''>log</span> <span m=''2347860''>of</span>
  <span m=''2350630''>n</span> <span m=''2350980''>over</span> <span m=''2351340''>g--</span>
  <span m=''2352850''>n</span> <span m=''2352990''>over</span> <span m=''2353210''>g</span>
  <span m=''2353370''>is</span> <span m=''2353490''>the</span> <span m=''2353580''>number</span>
  <span m=''2353970''>of</span> <span m=''2354080''>things</span> <span m=''2354370''>I</span>
  <span m=''2354510''>have</span> <span m=''2354750''>here--</span> <span m=''2355680''>times</span>
  <span m=''2356020''>the</span> <span m=''2356120''>cost</span> <span m=''2356530''>of</span>
  <span m=''2356610''>the</span> <span m=''2356690''>spawn,</span> <span m=''2357150''>basically.</span>
  <span m=''2361152''>Does</span> <span m=''2361530''>that</span> <span m=''2361700''>make</span>
  <span m=''2361890''>sense?</span> </p><p><span m=''2365470''>So</span> <span m=''2365710''>the</span>
  <span m=''2365850''>idea</span> <span m=''2366310''>is,</span> <span m=''2366700''>what</span>
  <span m=''2366870''>do</span> <span m=''2366920''>we</span> <span m=''2367060''>want</span>
  <span m=''2367260''>to</span> <span m=''2367450''>have</span> <span m=''2367630''>here</span>
  <span m=''2367830''>if</span> <span m=''2367950''>I</span> <span m=''2368030''>want</span>
  <span m=''2368230''>a</span> <span m=''2368270''>good</span> <span m=''2368540''>parallel</span>
  <span m=''2369000''>code?</span> <span m=''2369640''>We</span> <span m=''2369860''>would</span>
  <span m=''2370010''>like</span> <span m=''2370260''>the</span> <span m=''2370380''>work</span>
  <span m=''2370870''>to</span> <span m=''2370970''>be</span> <span m=''2371180''>as</span>
  <span m=''2371280''>small</span> <span m=''2371790''>as</span> <span m=''2371950''>possible.</span>
  <span m=''2373230''>How</span> <span m=''2373380''>do</span> <span m=''2373480''>I</span>
  <span m=''2373570''>make</span> <span m=''2373820''>the</span> <span m=''2373900''>work</span>
  <span m=''2374180''>small?</span> <span m=''2378270''>How</span> <span m=''2378480''>can</span>
  <span m=''2378630''>I</span> <span m=''2378700''>set</span> <span m=''2379040''>g</span>
  <span m=''2379280''>to</span> <span m=''2379370''>make</span> <span m=''2379590''>the</span>
  <span m=''2379690''>work</span> <span m=''2380110''>small?</span> </p><p><span m=''2382758''>AUDIENCE:
  [INAUDIBLE].</span> </p><p><span m=''2384580''>CHARLES LEISERSON: Make</span> <span
  m=''2385050''>g--</span> </p><p><span m=''2385520''>AUDIENCE: Square root</span>
  <span m=''2385880''>of n.</span> </p><p><span m=''2386540''>CHARLES LEISERSON: Well,</span>
  <span m=''2387090''>make</span> <span m=''2387300''>g</span> <span m=''2388750''>big</span>
  <span m=''2389030''>or</span> <span m=''2389680''>little?</span> <span m=''2391090''>If</span>
  <span m=''2391500''>you</span> <span m=''2391820''>want</span> <span m=''2392510''>this</span>
  <span m=''2392700''>term</span> <span m=''2393020''>to</span> <span m=''2393130''>be</span>
  <span m=''2393860''>small,</span> <span m=''2394800''>you</span> <span m=''2394960''>want</span>
  <span m=''2395310''>g</span> <span m=''2395480''>to</span> <span m=''2395570''>be</span>
  <span m=''2396670''>big.</span> <span m=''2398770''>But</span> <span m=''2398850''>we</span>
  <span m=''2398980''>also</span> <span m=''2399270''>want</span> <span m=''2399420''>to</span>
  <span m=''2399460''>have</span> <span m=''2399620''>a</span> <span m=''2399670''>lot</span>
  <span m=''2399890''>of</span> <span m=''2399960''>parallelism.</span> <span m=''2402380''>So</span>
  <span m=''2402560''>I</span> <span m=''2402650''>want</span> <span m=''2402930''>this</span>
  <span m=''2403130''>term</span> <span m=''2403420''>to</span> <span m=''2403520''>be</span>
  <span m=''2403680''>what?</span> <span m=''2405530''>Small,</span> <span m=''2406500''>which</span>
  <span m=''2406660''>means</span> <span m=''2406920''>I</span> <span m=''2407030''>need</span>
  <span m=''2407190''>to</span> <span m=''2407350''>make</span> <span m=''2407950''>g</span>
  <span m=''2408220''>what?</span> <span m=''2409290''>Well,</span> <span m=''2410300''>we</span>
  <span m=''2410410''>got</span> <span m=''2410640''>an n</span> <span m=''2410950''>over</span>
  <span m=''2411180''>g</span> <span m=''2411400''>here,</span> <span m=''2412470''>but</span>
  <span m=''2412630''>it''s</span> <span m=''2412790''>in</span> <span m=''2412910''>a</span>
  <span m=''2413010''>log.</span> <span m=''2414366''>It''s</span> <span m=''2414790''>minus</span>
  <span m=''2415210''>log.</span> <span m=''2415910''>So</span> <span m=''2416960''>really,</span>
  <span m=''2417330''>to</span> <span m=''2417500''>get</span> <span m=''2417730''>this</span>
  <span m=''2417820''>small,</span> <span m=''2418760''>I</span> <span m=''2418880''>want</span>
  <span m=''2419220''>g</span> <span m=''2419400''>to</span> <span m=''2419470''>be</span>
  <span m=''2419620''>small.</span> <span m=''2420882''>So I</span> <span m=''2421310''>have</span>
  <span m=''2421610''>tension,</span> <span m=''2422830''>trade</span> <span m=''2423110''>off.</span>
  <span m=''2424670''>I</span> <span m=''2425080''>have</span> <span m=''2425170''>trade</span>
  <span m=''2425480''>off.</span> </p><p><span m=''2426090''>So</span> <span m=''2426270''>let''s</span>
  <span m=''2426540''>analyze</span> <span m=''2427060''>this</span> <span m=''2427240''>a</span>
  <span m=''2427290''>little</span> <span m=''2427460''>bit.</span> <span m=''2430210''>Essentially,</span>
  <span m=''2431670''>if</span> <span m=''2431820''>I</span> <span m=''2431920''>look</span>
  <span m=''2432180''>at</span> <span m=''2432290''>this,</span> <span m=''2432570''>I</span>
  <span m=''2432680''>want</span> <span m=''2433040''>g</span> <span m=''2433820''>to</span>
  <span m=''2433920''>be</span> <span m=''2434100''>bigger--</span> <span m=''2441860''>from</span>
  <span m=''2442010''>this</span> <span m=''2442190''>one</span> <span m=''2442340''>I</span>
  <span m=''2442380''>want</span> <span m=''2442630''>g</span> <span m=''2442760''>to</span>
  <span m=''2442830''>be</span> <span m=''2442980''>small.</span> <span m=''2444130''>But</span>
  <span m=''2444370''>here,</span> <span m=''2444800''>what</span> <span m=''2444960''>I</span>
  <span m=''2445020''>would</span> <span m=''2445180''>like</span> <span m=''2445540''>is</span>
  <span m=''2445720''>to</span> <span m=''2445830''>make</span> <span m=''2446040''>it</span>
  <span m=''2446190''>so</span> <span m=''2446340''>that</span> <span m=''2446560''>this</span>
  <span m=''2446840''>term</span> <span m=''2447170''>dominates</span> <span m=''2447900''>this</span>
  <span m=''2448130''>term.</span> <span m=''2451390''>If</span> <span m=''2451550''>the</span>
  <span m=''2451630''>first</span> <span m=''2452050''>term</span> <span m=''2452310''>here</span>
  <span m=''2452650''>dominates</span> <span m=''2453350''>the</span> <span m=''2453600''>second</span>
  <span m=''2453840''>term,</span> <span m=''2456470''>then</span> <span m=''2457510''>the</span>
  <span m=''2457630''>work</span> <span m=''2457970''>is</span> <span m=''2458120''>going</span>
  <span m=''2458240''>to</span> <span m=''2458290''>be</span> <span m=''2458400''>the</span>
  <span m=''2458480''>same</span> <span m=''2458820''>as</span> <span m=''2458940''>if</span>
  <span m=''2459090''>I</span> <span m=''2459250''>did an</span> <span m=''2459400''>ordinary</span>
  <span m=''2459910''>for</span> <span m=''2460210''>loop</span> <span m=''2463580''>to</span>
  <span m=''2463990''>within</span> <span m=''2464310''>a</span> <span m=''2464360''>few</span>
  <span m=''2464590''>percent.</span> <span m=''2465450''>So</span> <span m=''2465640''>therefore,</span>
  <span m=''2466160''>I</span> <span m=''2466270''>want</span> <span m=''2467270''>t</span>
  <span m=''2467490''>span</span> <span m=''2467920''>over</span> <span m=''2468180''>t</span>
  <span m=''2468480''>iter,</span> <span m=''2468805''>if</span> <span m=''2469130''>I</span>
  <span m=''2469240''>take</span> <span m=''2469470''>the</span> <span m=''2469570''>ratio</span>
  <span m=''2469960''>of</span> <span m=''2470040''>these</span> <span m=''2470270''>things,</span>
  <span m=''2471030''>I</span> <span m=''2471130''>want</span> <span m=''2471410''>g</span>
  <span m=''2471560''>to</span> <span m=''2471650''>be</span> <span m=''2471800''>bigger</span>
  <span m=''2472220''>than</span> <span m=''2472560''>the</span> <span m=''2473410''>time</span>
  <span m=''2474110''>to</span> <span m=''2474300''>spawn</span> <span m=''2474690''>divided</span>
  <span m=''2475050''>by</span> <span m=''2475180''>the</span> <span m=''2475330''>time</span>
  <span m=''2475620''>to</span> <span m=''2475905''>iterate.</span> <span m=''2477450''>If</span>
  <span m=''2477570''>I</span> <span m=''2477640''>get</span> <span m=''2478070''>it</span>
  <span m=''2478530''>much</span> <span m=''2478800''>bigger</span> <span m=''2479090''>than</span>
  <span m=''2479260''>that,</span> <span m=''2479890''>then</span> <span m=''2480230''>this</span>
  <span m=''2480440''>term</span> <span m=''2480680''>will</span> <span m=''2480820''>be</span>
  <span m=''2480960''>much</span> <span m=''2481190''>bigger</span> <span m=''2481470''>than</span>
  <span m=''2481630''>that</span> <span m=''2481900''>term</span> <span m=''2482110''>and
  I</span> <span m=''2482210''>don''t</span> <span m=''2482350''>have</span> <span
  m=''2482480''>to</span> <span m=''2482580''>worry</span> <span m=''2482800''>about</span>
  <span m=''2483040''>this</span> <span m=''2483210''>term.</span> <span m=''2485760''>So</span>
  <span m=''2487760''>I</span> <span m=''2487920''>want</span> <span m=''2488090''>it
  to</span> <span m=''2488150''>be</span> <span m=''2488260''>much</span> <span m=''2488530''>bigger,</span>
  <span m=''2488840''>but</span> <span m=''2489010''>I</span> <span m=''2489100''>want</span>
  <span m=''2489360''>to</span> <span m=''2489450''>be</span> <span m=''2489570''>as</span>
  <span m=''2489660''>small</span> <span m=''2490000''>as</span> <span m=''2490110''>possible.</span>
  <span m=''2491850''>There''s</span> <span m=''2492030''>no</span> <span m=''2492150''>point
  in</span> <span m=''2492430''>making</span> <span m=''2492770''>it</span> <span
  m=''2492900''>much</span> <span m=''2493250''>bigger</span> <span m=''2494410''>than</span>
  <span m=''2495070''>that</span> <span m=''2495460''>which</span> <span m=''2495630''>causes</span>
  <span m=''2496030''>this</span> <span m=''2496180''>term</span> <span m=''2496410''>to</span>
  <span m=''2496470''>essentially</span> <span m=''2496850''>be</span> <span m=''2496990''>wiped</span>
  <span m=''2497330''>out.</span> <span m=''2498340''>People</span> <span m=''2498610''>follow</span>
  <span m=''2498930''>that?</span> </p><p><span m=''2504830''>So</span> <span m=''2505060''>basically,</span>
  <span m=''2505920''>the</span> <span m=''2506360''>idea</span> <span m=''2506770''>is</span>
  <span m=''2507470''>we</span> <span m=''2507890''>pick</span> <span m=''2508070''>a</span>
  <span m=''2508140''>grain</span> <span m=''2508470''>size</span> <span m=''2508920''>that''s</span>
  <span m=''2509120''>large</span> <span m=''2509580''>but</span> <span m=''2509750''>not</span>
  <span m=''2510020''>too</span> <span m=''2510190''>large,</span> <span m=''2510590''>is</span>
  <span m=''2510700''>what</span> <span m=''2510880''>you</span> <span m=''2511090''>generally</span>
  <span m=''2511430''>want</span> <span m=''2511640''>to</span> <span m=''2511690''>do,</span>
  <span m=''2513050''>so that</span> <span m=''2513180''>you</span> <span m=''2513300''>have</span>
  <span m=''2513520''>enough</span> <span m=''2513760''>parallelism,</span> <span
  m=''2514750''>but</span> <span m=''2514920''>you</span> <span m=''2515010''>don''t.</span>
  <span m=''2515930''>The</span> <span m=''2516060''>way</span> <span m=''2516320''>that</span>
  <span m=''2516550''>the</span> <span m=''2516830''>runtime</span> <span m=''2517350''>system</span>
  <span m=''2517700''>does</span> <span m=''2518000''>it</span> <span m=''2518470''>is</span>
  <span m=''2518670''>it</span> <span m=''2518830''>has</span> <span m=''2519150''>a</span>
  <span m=''2519690''>somewhat</span> <span m=''2521360''>complicated</span> <span
  m=''2521930''>heuristic,</span> <span m=''2522330''>but it</span> <span m=''2522510''>actually</span>
  <span m=''2522780''>looks</span> <span m=''2522940''>to</span> <span m=''2523120''>see</span>
  <span m=''2523340''>how</span> <span m=''2523610''>many</span> <span m=''2524080''>processors</span>
  <span m=''2524720''>you''re</span> <span m=''2524890''>running</span> <span m=''2525180''>on.</span>
  <span m=''2526660''>And</span> <span m=''2526930''>it</span> <span m=''2527800''>uses</span>
  <span m=''2528010''>a</span> <span m=''2528070''>heuristic</span> <span m=''2528640''>that</span>
  <span m=''2528830''>says,</span> <span m=''2530190''>let''s</span> <span m=''2530420''>make</span>
  <span m=''2530610''>sure</span> <span m=''2530730''>there''s</span> <span m=''2530970''>at</span>
  <span m=''2531040''>least</span> <span m=''2531500''>parallelism</span> <span m=''2532110''>10</span>
  <span m=''2532360''>times</span> <span m=''2532800''>more</span> <span m=''2533020''>than</span>
  <span m=''2533210''>the</span> <span m=''2533290''>number of</span> <span m=''2533550''>processors.</span>
  <span m=''2534820''>But</span> <span m=''2535150''>there''s</span> <span m=''2535330''>no</span>
  <span m=''2535510''>point</span> <span m=''2535860''>in</span> <span m=''2535950''>having</span>
  <span m=''2536340''>more</span> <span m=''2536620''>iterations</span> <span m=''2537350''>than</span>
  <span m=''2537480''>like</span> <span m=''2537710''>500</span> <span m=''2538330''>or</span>
  <span m=''2538420''>something,</span> <span m=''2540780''>because</span> <span m=''2541380''>at</span>
  <span m=''2541610''>500</span> <span m=''2542160''>iterations,</span> <span m=''2542660''>you</span>
  <span m=''2542760''>can''t</span> <span m=''2543050''>see</span> <span m=''2543250''>the</span>
  <span m=''2543350''>spawn</span> <span m=''2543700''>overhead</span> <span m=''2544370''>regardless.</span>
  <span m=''2545940''>So</span> <span m=''2546270''>basically,</span> <span m=''2547700''>it</span>
  <span m=''2547850''>uses</span> <span m=''2548220''>a</span> <span m=''2548270''>formula</span>
  <span m=''2548880''>kind</span> <span m=''2549120''>of</span> <span m=''2549310''>that</span>
  <span m=''2549540''>nature</span> <span m=''2549830''>to</span> <span m=''2549900''>pick</span>
  <span m=''2550330''>this</span> <span m=''2550570''>automatically.</span> <span
  m=''2551590''>But</span> <span m=''2551790''>you''re</span> <span m=''2551950''>free</span>
  <span m=''2552270''>to</span> <span m=''2552370''>pick</span> <span m=''2552620''>this</span>
  <span m=''2552800''>yourself.</span> </p><p><span m=''2554150''>But</span> <span
  m=''2554610''>you</span> <span m=''2554650''>can</span> <span m=''2554800''>see</span>
  <span m=''2555050''>the</span> <span m=''2555160''>point</span> <span m=''2555570''>is</span>
  <span m=''2556050''>that</span> <span m=''2556830''>although</span> <span m=''2557140''>it''s</span>
  <span m=''2557270''>doing</span> <span m=''2557540''>divide</span> <span m=''2557830''>and</span>
  <span m=''2557940''>conquer,</span> <span m=''2558770''>you</span> <span m=''2558910''>do</span>
  <span m=''2559680''>this</span> <span m=''2559840''>issue</span> <span m=''2560140''>of</span>
  <span m=''2560250''>coarsening</span> <span m=''2561060''>and</span> <span m=''2561470''>you</span>
  <span m=''2561650''>do</span> <span m=''2561890''>want</span> <span m=''2562120''>to</span>
  <span m=''2562170''>make</span> <span m=''2562390''>sure</span> <span m=''2562630''>that</span>
  <span m=''2564120''>you</span> <span m=''2564290''>have</span> <span m=''2564450''>enough</span>
  <span m=''2565670''>work</span> <span m=''2566100''>to</span> <span m=''2566200''>do</span>
  <span m=''2566610''>in</span> <span m=''2566760''>any</span> <span m=''2567000''>of</span>
  <span m=''2567060''>the</span> <span m=''2567150''>leaves</span> <span m=''2567500''>of</span>
  <span m=''2567580''>the</span> <span m=''2567660''>computation.</span> <span m=''2569100''>And</span>
  <span m=''2569230''>as</span> <span m=''2569370''>I</span> <span m=''2569430''>say,</span>
  <span m=''2569600''>usually</span> <span m=''2570150''>it''ll</span> <span m=''2570290''>guess</span>
  <span m=''2570530''>right.</span> <span m=''2571470''>But</span> <span m=''2571580''>if</span>
  <span m=''2571640''>you</span> <span m=''2571710''>have</span> <span m=''2571850''>trouble</span>
  <span m=''2572250''>with</span> <span m=''2572400''>that,</span> <span m=''2573620''>you</span>
  <span m=''2573770''>have</span> <span m=''2573920''>a</span> <span m=''2573990''>parameter</span>
  <span m=''2574410''>you</span> <span m=''2574550''>can</span> <span m=''2574690''>play</span>
  <span m=''2575104''>with.</span> </p><p><span m=''2576760''>Let''s</span> <span
  m=''2576970''>take</span> <span m=''2577190''>a</span> <span m=''2577260''>look</span>
  <span m=''2577480''>at</span> <span m=''2577550''>another</span> <span m=''2577990''>implementation</span>
  <span m=''2579390''>just</span> <span m=''2579600''>to</span> <span m=''2579710''>try</span>
  <span m=''2579890''>to</span> <span m=''2579990''>understand</span> <span m=''2580530''>this</span>
  <span m=''2580690''>issue.</span> <span m=''2584490''>Suppose</span> <span m=''2584830''>I''m</span>
  <span m=''2584910''>going</span> <span m=''2584990''>to</span> <span m=''2585060''>do</span>
  <span m=''2585230''>a</span> <span m=''2585280''>vector</span> <span m=''2585760''>add.</span>
  <span m=''2586100''>So</span> <span m=''2586220''>here</span> <span m=''2586410''>I</span>
  <span m=''2586470''>have</span> <span m=''2586520''>a</span> <span m=''2586580''>vector</span>
  <span m=''2587020''>add</span> <span m=''2588272''>of</span> <span m=''2588630''>two</span>
  <span m=''2588750''>arrays,</span> <span m=''2589790''>where</span> <span m=''2590030''>I''m</span>
  <span m=''2590110''>basically</span> <span m=''2590710''>saying</span> <span m=''2591070''>ai</span>
  <span m=''2593750''>gets</span> <span m=''2595590''>the</span> <span m=''2595720''>value</span>
  <span m=''2596040''>of b</span> <span m=''2596320''>added</span> <span m=''2596720''>into</span>
  <span m=''2596860''>it.</span> <span m=''2597750''>That''s</span> <span m=''2598110''>kind</span>
  <span m=''2598260''>of</span> <span m=''2598400''>the</span> <span m=''2598540''>code</span>
  <span m=''2598790''>we</span> <span m=''2598900''>had</span> <span m=''2599140''>before.</span>
  <span m=''2600260''>But</span> <span m=''2600400''>now,</span> <span m=''2600680''>what</span>
  <span m=''2600840''>I</span> <span m=''2600910''>want</span> <span m=''2601130''>to</span>
  <span m=''2601200''>do</span> <span m=''2601710''>is</span> <span m=''2602190''>I''m</span>
  <span m=''2602380''>going</span> <span m=''2602500''>to</span> <span m=''2602830''>implement</span>
  <span m=''2604120''>a</span> <span m=''2605440''>vector</span> <span m=''2605810''>add</span>
  <span m=''2606140''>using</span> <span m=''2606510''>cilk</span> <span m=''2606710''>spawn.</span>
  <span m=''2610560''>So</span> <span m=''2610790''>rather</span> <span m=''2611150''>than</span>
  <span m=''2611360''>using</span> <span m=''2611710''>a</span> <span m=''2611760''>cilk_for</span>
  <span m=''2612490''>loop,</span> <span m=''2613900''>I''m going</span> <span m=''2614030''>to</span>
  <span m=''2614160''>parallelize</span> <span m=''2614780''>this</span> <span m=''2614970''>loop</span>
  <span m=''2615230''>by</span> <span m=''2615420''>hand</span> <span m=''2615840''>using</span>
  <span m=''2616240''>cilk</span> <span m=''2616550''>spawn.</span> <span m=''2617660''>What</span>
  <span m=''2617880''>I''m</span> <span m=''2617990''>going</span> <span m=''2618090''>to</span>
  <span m=''2618180''>do</span> <span m=''2618560''>is</span> <span m=''2618750''>I''m</span>
  <span m=''2618840''>going</span> <span m=''2618930''>to</span> <span m=''2619010''>say</span>
  <span m=''2619870''>for</span> <span m=''2619990''>j</span> <span m=''2620290''>equals</span>
  <span m=''2620640''>0</span> <span m=''2620970''>up</span> <span m=''2621240''>to--</span>
  <span m=''2621460''>and</span> <span m=''2621550''>I''m</span> <span m=''2621630''>going</span>
  <span m=''2621730''>to</span> <span m=''2621820''>jump</span> <span m=''2622190''>by</span>
  <span m=''2622360''>whatever</span> <span m=''2622690''>my</span> <span m=''2622970''>grain</span>
  <span m=''2623250''>size</span> <span m=''2623535''>is</span> <span m=''2623820''>here--</span>
  <span m=''2625020''>and</span> <span m=''2625190''>spawn</span> <span m=''2625640''>off</span>
  <span m=''2625960''>the</span> <span m=''2626100''>addition</span> <span m=''2628330''>of</span>
  <span m=''2629010''>things</span> <span m=''2629290''>of</span> <span m=''2629420''>size,</span>
  <span m=''2630080''>essentially,</span> <span m=''2630610''>g,</span> <span m=''2631140''>unless</span>
  <span m=''2631480''>I</span> <span m=''2631540''>get</span> <span m=''2631790''>close</span>
  <span m=''2632040''>to</span> <span m=''2632120''>the</span> <span m=''2632270''>end</span>
  <span m=''2632410''>of</span> <span m=''2632450''>the</span> <span m=''2632560''>array.</span>
  <span m=''2633180''>But</span> <span m=''2633430''>basically,</span> <span m=''2634530''>I''m</span>
  <span m=''2634680''>always</span> <span m=''2635240''>spawning</span> <span m=''2635710''>off</span>
  <span m=''2636270''>the</span> <span m=''2636520''>next</span> <span m=''2637120''>g</span>
  <span m=''2637440''>iterations</span> <span m=''2637980''>to</span> <span m=''2638160''>do</span>
  <span m=''2638300''>that</span> <span m=''2638540''>in</span> <span m=''2638630''>parallel.</span>
  <span m=''2640200''>And</span> <span m=''2640390''>then</span> <span m=''2640620''>I</span>
  <span m=''2641490''>sync</span> <span m=''2641700''>all</span> <span m=''2641890''>these</span>
  <span m=''2642000''>spawns.</span> </p><p><span m=''2643280''>So</span> <span m=''2643420''>everybody</span>
  <span m=''2643740''>understand</span> <span m=''2644150''>the</span> <span m=''2644220''>code?</span>
  <span m=''2646180''>I</span> <span m=''2646390''>see</span> <span m=''2646600''>nods.</span>
  <span m=''2647270''>I</span> <span m=''2647400''>want to</span> <span m=''2647520''>see</span>
  <span m=''2647800''>everybody</span> <span m=''2648210''>nod,</span> <span m=''2648510''>actually,</span>
  <span m=''2648810''>when I</span> <span m=''2649030''>do</span> <span m=''2649160''>this.</span>
  <span m=''2649740''>Otherwise</span> <span m=''2650110''>what</span> <span m=''2650220''>happens</span>
  <span m=''2650620''>is</span> <span m=''2650770''>I</span> <span m=''2650870''>see</span>
  <span m=''2651080''>three</span> <span m=''2651350''>people</span> <span m=''2651650''>nod,</span>
  <span m=''2652440''>and</span> <span m=''2652610''>I</span> <span m=''2652690''>assume</span>
  <span m=''2653040''>that</span> <span m=''2653200''>people</span> <span m=''2653440''>are</span>
  <span m=''2653500''>nodding.</span> <span m=''2653770''>Because</span> <span m=''2653960''>if
  you</span> <span m=''2654050''>don''t</span> <span m=''2654260''>do</span> <span
  m=''2654350''>it,</span> <span m=''2654460''>you</span> <span m=''2654540''>can</span>
  <span m=''2654640''>shake</span> <span m=''2654880''>your</span> <span m=''2654970''>head,</span>
  <span m=''2655450''>and</span> <span m=''2655680''>I</span> <span m=''2655760''>promise</span>
  <span m=''2657150''>none</span> <span m=''2657340''>of</span> <span m=''2657400''>your</span>
  <span m=''2657520''>friends</span> <span m=''2657820''>will</span> <span m=''2657920''>see</span>
  <span m=''2658130''>that</span> <span m=''2658250''>you''re</span> <span m=''2658410''>shaking</span>
  <span m=''2658780''>your</span> <span m=''2658940''>head.</span> <span m=''2661280''>And</span>
  <span m=''2661760''>since</span> <span m=''2661990''>the</span> <span m=''2662090''>TAs</span>
  <span m=''2662550''>are</span> <span m=''2662610''>doing</span> <span m=''2662840''>the</span>
  <span m=''2662910''>grading</span> <span m=''2663340''>and</span> <span m=''2663420''>they''re</span>
  <span m=''2663540''>facing</span> <span m=''2663880''>this</span> <span m=''2664070''>way,</span>
  <span m=''2664280''>they</span> <span m=''2664410''>won''t</span> <span m=''2664690''>see</span>
  <span m=''2664860''>either.</span> <span m=''2666450''>And</span> <span m=''2666670''>so</span>
  <span m=''2666900''>it''s</span> <span m=''2667050''>perfectly</span> <span m=''2667600''>safe</span>
  <span m=''2667960''>to</span> <span m=''2668100''>let</span> <span m=''2668290''>me</span>
  <span m=''2668480''>know,</span> <span m=''2669280''>and</span> <span m=''2669440''>that</span>
  <span m=''2669610''>way</span> <span m=''2669810''>I</span> <span m=''2669900''>can</span>
  <span m=''2670080''>make</span> <span m=''2670250''>sure</span> <span m=''2670410''>you</span>
  <span m=''2670640''>understand.</span> <span m=''2673590''>So</span> <span m=''2674320''>everybody</span>
  <span m=''2674710''>understand</span> <span m=''2675130''>what</span> <span m=''2675260''>this</span>
  <span m=''2675480''>does?</span> <span m=''2677290''>OK,</span> <span m=''2677660''>so</span>
  <span m=''2677790''>I</span> <span m=''2677920''>see</span> <span m=''2678110''>a</span>
  <span m=''2678140''>few</span> <span m=''2678340''>more.</span> <span m=''2678500''>No.</span>
  <span m=''2678820''>OK,</span> <span m=''2679550''>question?</span> <span m=''2679910''>Do</span>
  <span m=''2680050''>you</span> <span m=''2680190''>have</span> <span m=''2680290''>a</span>
  <span m=''2680380''>question,</span> <span m=''2681590''>or should</span> <span
  m=''2681760''>I</span> <span m=''2681840''>just</span> <span m=''2682060''>explain</span>
  <span m=''2682430''>again?</span> </p><p><span m=''2683540''>So</span> <span m=''2683850''>this</span>
  <span m=''2684100''>is</span> <span m=''2684260''>basically</span> <span m=''2684720''>doing</span>
  <span m=''2684990''>a</span> <span m=''2685040''>vector</span> <span m=''2685490''>add</span>
  <span m=''2685830''>of</span> <span m=''2687280''>b</span> <span m=''2687560''>into</span>
  <span m=''2687800''>a,</span> <span m=''2688700''>of</span> <span m=''2689000''>n</span>
  <span m=''2689490''>iterations</span> <span m=''2690060''>here.</span> <span m=''2691970''>And</span>
  <span m=''2692260''>we''re</span> <span m=''2692380''>going</span> <span m=''2692460''>to</span>
  <span m=''2692540''>call</span> <span m=''2692980''>it</span> <span m=''2693050''>here,</span>
  <span m=''2693900''>when</span> <span m=''2694040''>I</span> <span m=''2694130''>do</span>
  <span m=''2694260''>a</span> <span m=''2694310''>vector</span> <span m=''2694640''>add,</span>
  <span m=''2694910''>of</span> <span m=''2695140''>basically</span> <span m=''2695700''>g</span>
  <span m=''2696040''>iterations.</span> <span m=''2697490''>So what it''s</span>
  <span m=''2697800''>doing</span> <span m=''2698150''>is</span> <span m=''2699000''>it''s</span>
  <span m=''2699230''>going</span> <span m=''2699330''>to</span> <span m=''2699430''>take</span>
  <span m=''2699760''>my</span> <span m=''2699890''>array</span> <span m=''2700150''>of</span>
  <span m=''2700250''>size</span> <span m=''2700670''>n,</span> <span m=''2701050''>bust
  it</span> <span m=''2701480''>into</span> <span m=''2701730''>chunks</span> <span
  m=''2702090''>of</span> <span m=''2702180''>size</span> <span m=''2702660''>g,</span>
  <span m=''2703670''>and</span> <span m=''2703820''>spawn</span> <span m=''2704260''>off</span>
  <span m=''2705140''>the</span> <span m=''2705220''>first</span> <span m=''2705590''>one,</span>
  <span m=''2705870''>spawn</span> <span m=''2706020''>off</span> <span m=''2706340''>the</span>
  <span m=''2706580''>second</span> <span m=''2706810''>one,</span> <span m=''2707060''>spawn
  off the</span> <span m=''2707440''>third</span> <span m=''2707770''>one,</span>
  <span m=''2708000''>each</span> <span m=''2708230''>one</span> <span m=''2708450''>to</span>
  <span m=''2708890''>do</span> <span m=''2709070''>g</span> <span m=''2709330''>iterations.</span>
  <span m=''2711310''>That</span> <span m=''2711470''>make</span> <span m=''2711630''>sense?</span>
  <span m=''2713340''>We''ll</span> <span m=''2713430''>see</span> <span m=''2713780''>it.</span>
  <span m=''2714700''>So</span> <span m=''2715160''>here''s</span> <span m=''2715560''>sort</span>
  <span m=''2715830''>of</span> <span m=''2715920''>the</span> <span m=''2716270''>instruction</span>
  <span m=''2717010''>stream</span> <span m=''2717330''>for</span> <span m=''2717430''>the</span>
  <span m=''2717530''>code</span> <span m=''2717800''>here.</span> </p><p><span m=''2718980''>So</span>
  <span m=''2719170''>basically,</span> <span m=''2719910''>it</span> <span m=''2720070''>says</span>
  <span m=''2720450''>here</span> <span m=''2720730''>is</span> <span m=''2720840''>one,</span>
  <span m=''2721500''>we</span> <span m=''2721760''>spawn</span> <span m=''2722170''>off</span>
  <span m=''2722310''>something</span> <span m=''2722720''>of</span> <span m=''2722810''>size</span>
  <span m=''2723270''>g,</span> <span m=''2725400''>then</span> <span m=''2725530''>we</span>
  <span m=''2725650''>go</span> <span m=''2725920''>on,</span> <span m=''2726130''>we</span>
  <span m=''2726240''>spawn</span> <span m=''2726620''>off</span> <span m=''2726740''>something</span>
  <span m=''2727070''>else</span> <span m=''2727290''>of</span> <span m=''2727370''>size</span>
  <span m=''2727850''>g,</span> <span m=''2728150''>et</span> <span m=''2728430''>cetera.</span>
  <span m=''2728870''>We</span> <span m=''2729010''>keep</span> <span m=''2729210''>going</span>
  <span m=''2729410''>up</span> <span m=''2729540''>there</span> <span m=''2729750''>until</span>
  <span m=''2730000''>we</span> <span m=''2730100''>hit</span> <span m=''2730280''>the</span>
  <span m=''2730350''>cilk</span> <span m=''2730640''>sync.</span> <span m=''2732740''>That</span>
  <span m=''2732830''>make</span> <span m=''2733010''>sense?</span> <span m=''2734480''>Each</span>
  <span m=''2734710''>of</span> <span m=''2734810''>these</span> <span m=''2735100''>is</span>
  <span m=''2735240''>doing</span> <span m=''2735480''>a</span> <span m=''2735530''>vector</span>
  <span m=''2735950''>add</span> <span m=''2736210''>of</span> <span m=''2736310''>size</span>
  <span m=''2737670''>g</span> <span m=''2738250''>using</span> <span m=''2738610''>this</span>
  <span m=''2739210''>serial</span> <span m=''2739680''>routine.</span> <span m=''2742610''>So</span>
  <span m=''2742780''>let''s</span> <span m=''2743000''>analyze</span> <span m=''2743670''>this</span>
  <span m=''2743940''>to</span> <span m=''2744040''>understand</span> <span m=''2745090''>the</span>
  <span m=''2745250''>efficiency</span> <span m=''2746060''>of</span> <span m=''2746420''>this</span>
  <span m=''2746630''>type</span> <span m=''2746880''>of</span> <span m=''2747010''>looping</span>
  <span m=''2747330''>structure.</span> </p><p><span m=''2749980''>So</span> <span
  m=''2750150''>let''s</span> <span m=''2750360''>assume</span> <span m=''2750800''>for</span>
  <span m=''2750890''>this</span> <span m=''2751070''>analysis</span> <span m=''2751640''>that</span>
  <span m=''2751770''>g</span> <span m=''2752010''>equals</span> <span m=''2752410''>1,</span>
  <span m=''2752800''>to</span> <span m=''2752910''>make</span> <span m=''2753110''>it</span>
  <span m=''2753180''>easy,</span> <span m=''2753590''>so</span> <span m=''2753760''>we</span>
  <span m=''2753840''>don''t</span> <span m=''2753980''>have</span> <span m=''2754120''>to</span>
  <span m=''2754230''>worry</span> <span m=''2754440''>about it.</span> <span m=''2754690''>So</span>
  <span m=''2755060''>we''re</span> <span m=''2755290''>simply</span> <span m=''2755620''>spawning</span>
  <span m=''2756130''>off</span> <span m=''2756390''>one</span> <span m=''2756640''>thing</span>
  <span m=''2756840''>here,</span> <span m=''2757430''>one</span> <span m=''2757650''>thing</span>
  <span m=''2757840''>here,</span> <span m=''2758080''>one</span> <span m=''2758310''>iteration</span>
  <span m=''2758760''>here,</span> <span m=''2758990''>all</span> <span m=''2759120''>the</span>
  <span m=''2759180''>way</span> <span m=''2759290''>to</span> <span m=''2759390''>the</span>
  <span m=''2759600''>end.</span> <span m=''2761760''>So</span> <span m=''2761950''>what</span>
  <span m=''2762150''>is</span> <span m=''2762280''>the</span> <span m=''2762370''>work</span>
  <span m=''2762780''>for</span> <span m=''2762920''>this,</span> <span m=''2763560''>if
  I</span> <span m=''2763920''>spawn</span> <span m=''2764210''>off</span> <span m=''2764580''>things</span>
  <span m=''2764930''>of</span> <span m=''2764990''>size</span> <span m=''2765370''>one,</span>
  <span m=''2766510''>asymptotic</span> <span m=''2767180''>work?</span> <span m=''2769370''>It''s</span>
  <span m=''2769630''>order</span> <span m=''2770000''>n,</span> <span m=''2770760''>because</span>
  <span m=''2770940''>I''ve</span> <span m=''2771060''>got</span> <span m=''2771280''>n</span>
  <span m=''2771490''>leaves, and</span> <span m=''2771960''>I''ve</span> <span m=''2772110''>got</span>
  <span m=''2772300''>n</span> <span m=''2772550''>guys</span> <span m=''2772850''>that
  I''m</span> <span m=''2773130''>spawning</span> <span m=''2773430''>off.</span>
  <span m=''2773710''>So</span> <span m=''2773850''>it''s</span> <span m=''2773920''>order</span>
  <span m=''2773990''>n.</span> <span m=''2775720''>What''s</span> <span m=''2775890''>the</span>
  <span m=''2776050''>span?</span> </p><p><span m=''2778019''>AUDIENCE: [INAUDIBLE].</span>
  </p><p><span m=''2780800''>CHARLES LEISERSON: Yeah,</span> <span m=''2781040''>it''s</span>
  <span m=''2781130''>also</span> <span m=''2781550''>order</span> <span m=''2781940''>n,</span>
  <span m=''2785630''>because</span> <span m=''2786850''>the</span> <span m=''2787130''>critical</span>
  <span m=''2787540''>path</span> <span m=''2788040''>goes</span> <span m=''2788360''>something</span>
  <span m=''2788720''>like</span> <span m=''2789030''>brrrup, brrrup, brrrup.</span>
  <span m=''2793620''>That''s</span> <span m=''2793880''>order</span> <span m=''2794230''>n</span>
  <span m=''2794500''>length.</span> <span m=''2795850''>It''s</span> <span m=''2795920''>not</span>
  <span m=''2796260''>this,</span> <span m=''2796570''>because</span> <span m=''2796720''>that''s</span>
  <span m=''2796930''>only</span> <span m=''2797540''>order</span> <span m=''2797760''>one</span>
  <span m=''2798030''>length,</span> <span m=''2798280''>all</span> <span m=''2798430''>those.</span>
  <span m=''2798820''>The</span> <span m=''2798920''>longest</span> <span m=''2799550''>path</span>
  <span m=''2800840''>is</span> <span m=''2801070''>order</span> <span m=''2801360''>n.</span>
  <span m=''2802130''>So</span> <span m=''2802270''>that</span> <span m=''2802430''>says</span>
  <span m=''2802640''>the</span> <span m=''2802740''>parallelism</span> <span m=''2803380''>is</span>
  <span m=''2806310''>order</span> <span m=''2806690''>one.</span> <span m=''2809220''>Conclusion,</span>
  <span m=''2811490''>at</span> <span m=''2811610''>least</span> <span m=''2811930''>with</span>
  <span m=''2812060''>grain</span> <span m=''2812390''>size</span> <span m=''2812760''>one,</span>
  <span m=''2813200''>this</span> <span m=''2813380''>is</span> <span m=''2813540''>a</span>
  <span m=''2813720''>really</span> <span m=''2814220''>bad</span> <span m=''2814660''>way</span>
  <span m=''2814840''>to</span> <span m=''2815020''>implement</span> <span m=''2815630''>a</span>
  <span m=''2815730''>parallel</span> <span m=''2816320''>loop.</span> <span m=''2817950''>However,</span>
  <span m=''2818430''>I</span> <span m=''2818510''>guarantee,</span> <span m=''2819800''>it</span>
  <span m=''2819940''>may</span> <span m=''2820070''>not</span> <span m=''2820300''>be</span>
  <span m=''2820410''>the</span> <span m=''2820510''>people</span> <span m=''2820840''>in</span>
  <span m=''2820960''>this</span> <span m=''2821080''>room,</span> <span m=''2823440''>but</span>
  <span m=''2823940''>some</span> <span m=''2824440''>fraction</span> <span m=''2825090''>of</span>
  <span m=''2825170''>students</span> <span m=''2825600''>in</span> <span m=''2825720''>this</span>
  <span m=''2825930''>class</span> <span m=''2826710''>will</span> <span m=''2827130''>write</span>
  <span m=''2827520''>this</span> <span m=''2828320''>rather</span> <span m=''2828890''>than</span>
  <span m=''2829170''>doing</span> <span m=''2829600''>a</span> <span m=''2829750''>cilk</span>
  <span m=''2830140''>for.</span> <span m=''2832080''>Bad</span> <span m=''2832710''>idea.</span>
  <span m=''2835440''>Bad</span> <span m=''2836030''>idea.</span> <span m=''2837270''>Generally,</span>
  <span m=''2837670''>bad</span> <span m=''2838050''>idea.</span> <span m=''2839950''>Question?</span>
  </p><p><span m=''2840862''>AUDIENCE: Do you think you could find a</span> <span
  m=''2841344''>constant</span> <span m=''2841826''>factor,</span> <span m=''2842308''>not
  just</span> <span m=''2842790''>[INAUDIBLE]?</span> </p><p><span m=''2846164''>CHARLES
  LEISERSON: Well</span> <span m=''2846646''>here,</span> <span m=''2847128''>actually,</span>
  <span m=''2848092''>with</span> <span m=''2848580''>grain</span> <span m=''2848880''>size</span>
  <span m=''2849180''>one,</span> <span m=''2849360''>this</span> <span m=''2849500''>is</span>
  <span m=''2849620''>really</span> <span m=''2849970''>bad,</span> <span m=''2850350''>because</span>
  <span m=''2850630''>I''ve</span> <span m=''2850770''>got</span> <span m=''2851020''>this</span>
  <span m=''2851210''>overhead</span> <span m=''2851850''>of</span> <span m=''2851960''>doing</span>
  <span m=''2852210''>a</span> <span m=''2852480''>spawn,</span> <span m=''2853450''>and</span>
  <span m=''2853570''>then</span> <span m=''2853690''>I''m</span> <span m=''2853810''>only</span>
  <span m=''2854010''>doing</span> <span m=''2854280''>one</span> <span m=''2854440''>iteration.</span>
  <span m=''2855450''>So</span> <span m=''2855640''>the</span> <span m=''2855790''>ideal</span>
  <span m=''2856250''>thing</span> <span m=''2856500''>would</span> <span m=''2856620''>be</span>
  <span m=''2856910''>that</span> <span m=''2857110''>I</span> <span m=''2857200''>really</span>
  <span m=''2857520''>am</span> <span m=''2857650''>only</span> <span m=''2857890''>paying</span>
  <span m=''2858250''>for</span> <span m=''2858400''>the</span> <span m=''2858480''>leaves,</span>
  <span m=''2859440''>and</span> <span m=''2859540''>the</span> <span m=''2859690''>internal</span>
  <span m=''2860070''>nodes,</span> <span m=''2860740''>I</span> <span m=''2860890''>don''t</span>
  <span m=''2861050''>have</span> <span m=''2861170''>to</span> <span m=''2861260''>pay</span>
  <span m=''2861430''>anything</span> <span m=''2861780''>for.</span> <span m=''2862405''>Yeah,</span>
  <span m=''2862730''>Eric?</span> </p><p><span m=''2864182''>AUDIENCE: Shouldn''t</span>
  <span m=''2864673''>there be a</span> <span m=''2865164''>sort of</span> <span m=''2865655''>keyword
  in the</span> <span m=''2866150''>b add too?</span> </p><p><span m=''2866560''>CHARLES
  LEISERSON: In</span> <span m=''2866710''>the where?</span> </p><p><span m=''2867150''>AUDIENCE:
  In the</span> <span m=''2867590''>b add?</span> </p><p><span m=''2868175''>CHARLES
  LEISERSON: No,</span> <span m=''2868490''>that''s</span> <span m=''2868765''>serial.</span>
  <span m=''2869470''>That''s</span> <span m=''2869900''>a</span> <span m=''2870330''>serial</span>
  <span m=''2870760''>code.</span> </p><p><span m=''2871190''>AUDIENCE: No,</span>
  <span m=''2871620''>but if you</span> <span m=''2872050''>were going to call it</span>
  <span m=''2872456''>with</span> <span m=''2872862''>cilk spawn,</span> <span m=''2873270''>don''t
  you</span> <span m=''2873700''>have to</span> <span m=''2874130''>declare</span>
  <span m=''2874560''>it</span> <span m=''2874990''>cilk?</span> <span m=''2876140''>Is</span>
  <span m=''2876496''>that</span> <span m=''2876852''>not the</span> <span m=''2877210''>case?</span>
  </p><p><span m=''2878581''>CHARLES LEISERSON: No.</span> </p><p><span m=''2879038''>AUDIENCE:
  Never mind.</span> </p><p><span m=''2882820''>CHARLES LEISERSON: Yes,</span> <span
  m=''2883050''>question.</span> </p><p><span m=''2883900''>AUDIENCE: If g is</span>
  <span m=''2884396''>[INAUDIBLE],</span> <span m=''2884892''>isn''t that</span> <span
  m=''2885388''>good enough?</span> </p><p><span m=''2888420''>CHARLES LEISERSON:
  Yeah,</span> <span m=''2888855''>so let''s take a look.</span> <span m=''2889290''>That''s
  actually</span> <span m=''2889370''>the</span> <span m=''2889460''>next</span> <span
  m=''2889850''>slide.</span> <span m=''2892980''>This</span> <span m=''2893140''>is</span>
  <span m=''2893250''>basically,</span> <span m=''2894270''>this</span> <span m=''2894400''>we</span>
  <span m=''2894490''>call</span> <span m=''2894830''>puny</span> <span m=''2894880''>parallelism.</span>
  <span m=''2897036''>We</span> <span m=''2897470''>don''t</span> <span m=''2897630''>like</span>
  <span m=''2897860''>puny</span> <span m=''2898175''>parallelism.</span> <span m=''2900580''>It</span>
  <span m=''2900750''>doesn''t</span> <span m=''2901030''>have</span> <span m=''2901210''>to</span>
  <span m=''2901390''>be</span> <span m=''2902030''>spectacular.</span> <span m=''2902470''>It</span>
  <span m=''2902910''>has</span> <span m=''2903230''>to</span> <span m=''2903330''>be</span>
  <span m=''2903910''>good</span> <span m=''2904120''>enough.</span> <span m=''2905680''>And</span>
  <span m=''2905860''>this</span> <span m=''2906030''>is</span> <span m=''2906160''>not</span>
  <span m=''2906420''>good</span> <span m=''2906590''>enough</span> <span m=''2906920''>for</span>
  <span m=''2907030''>most</span> <span m=''2908020''>applications.</span> <span m=''2911960''>So</span>
  <span m=''2912080''>here''s</span> <span m=''2912340''>another</span> <span m=''2912720''>implementation.</span>
  <span m=''2914250''>Here''s</span> <span m=''2914760''>another</span> <span m=''2915150''>way</span>
  <span m=''2915310''>of doing it.</span> </p><p><span m=''2915620''>Now</span> <span
  m=''2915940''>let''s</span> <span m=''2916230''>analyze</span> <span m=''2916810''>it</span>
  <span m=''2917930''>where</span> <span m=''2918210''>we</span> <span m=''2918350''>have</span>
  <span m=''2918550''>control</span> <span m=''2919140''>over</span> <span m=''2919400''>g.</span>
  <span m=''2920710''>So</span> <span m=''2920910''>we''ll</span> <span m=''2921070''>analyze</span>
  <span m=''2921490''>it</span> <span m=''2921560''>in</span> <span m=''2921700''>terms</span>
  <span m=''2922200''>of</span> <span m=''2922330''>g,</span> <span m=''2923590''>and</span>
  <span m=''2923760''>then</span> <span m=''2923910''>see</span> <span m=''2924150''>whether</span>
  <span m=''2924430''>there''s</span> <span m=''2924660''>a</span> <span m=''2924710''>setting</span>
  <span m=''2925070''>for</span> <span m=''2925190''>which</span> <span m=''2925440''>this</span>
  <span m=''2925650''>make</span> <span m=''2925900''>sense.</span> <span m=''2927270''>So</span>
  <span m=''2927450''>if</span> <span m=''2927530''>I</span> <span m=''2927630''>analyze</span>
  <span m=''2928070''>it in</span> <span m=''2928230''>terms</span> <span m=''2928570''>of</span>
  <span m=''2928660''>g,</span> <span m=''2929060''>now I</span> <span m=''2929080''>have</span>
  <span m=''2929180''>to</span> <span m=''2929280''>do</span> <span m=''2929410''>a</span>
  <span m=''2929460''>little</span> <span m=''2929690''>bit</span> <span m=''2929850''>more</span>
  <span m=''2930080''>careful</span> <span m=''2930910''>analysis</span> <span m=''2931200''>here.</span>
  <span m=''2931600''>How</span> <span m=''2931810''>much</span> <span m=''2932010''>work</span>
  <span m=''2932320''>do</span> <span m=''2932420''>I</span> <span m=''2932590''>have</span>
  <span m=''2932760''>here</span> <span m=''2934640''>in</span> <span m=''2934810''>terms</span>
  <span m=''2935100''>of</span> <span m=''2935150''>n and</span> <span m=''2935230''>g?</span>
  </p><p><span m=''2937798''>AUDIENCE: It''s</span> <span m=''2938265''>the same.</span>
  </p><p><span m=''2939200''>CHARLES LEISERSON: Yeah,</span> <span m=''2939380''>the</span>
  <span m=''2939490''>work</span> <span m=''2939750''>is</span> <span m=''2939850''>still</span>
  <span m=''2940120''>asymptotically</span> <span m=''2940710''>order</span> <span
  m=''2940840''>n.</span> <span m=''2945220''>Because</span> <span m=''2945440''>I</span>
  <span m=''2945660''>always</span> <span m=''2945970''>have</span> <span m=''2946240''>n</span>
  <span m=''2946420''>work</span> <span m=''2946700''>in</span> <span m=''2946780''>the</span>
  <span m=''2946870''>leaves,</span> <span m=''2947250''>even</span> <span m=''2947450''>if</span>
  <span m=''2947570''>I</span> <span m=''2947710''>do</span> <span m=''2947940''>more</span>
  <span m=''2948190''>iterations</span> <span m=''2948710''>here.</span> <span m=''2949190''>What</span>
  <span m=''2949830''>increasing</span> <span m=''2950830''>g</span> <span m=''2951100''>does</span>
  <span m=''2951460''>is</span> <span m=''2951620''>it</span> <span m=''2951720''>shrinks</span>
  <span m=''2952150''>this,</span> <span m=''2952510''>right?</span> <span m=''2954091''>It</span>
  <span m=''2954470''>shrinks</span> <span m=''2954810''>this.</span> <span m=''2957350''>The</span>
  <span m=''2957460''>span</span> <span m=''2958000''>for</span> <span m=''2958120''>this</span>
  <span m=''2958370''>is</span> <span m=''2958490''>what?</span> <span m=''2963240''>So</span>
  <span m=''2963630''>I</span> <span m=''2963840''>heard</span> <span m=''2964010''>somebody</span>
  <span m=''2964340''>say</span> <span m=''2964580''>it.</span> <span m=''2965820''>n</span>
  <span m=''2966040''>over</span> <span m=''2966220''>g</span> <span m=''2966490''>plus</span>
  <span m=''2966970''>g.</span> <span m=''2970560''>And</span> <span m=''2970710''>it</span>
  <span m=''2970800''>corresponds</span> <span m=''2971440''>to</span> <span m=''2971550''>this</span>
  <span m=''2971770''>path.</span> <span m=''2974750''>So</span> <span m=''2974960''>this</span>
  <span m=''2975190''>is</span> <span m=''2975330''>the</span> <span m=''2975470''>n</span>
  <span m=''2975620''>over</span> <span m=''2975840''>g</span> <span m=''2976090''>part</span>
  <span m=''2976400''>up</span> <span m=''2976550''>here,</span> <span m=''2977480''>and</span>
  <span m=''2977660''>this</span> <span m=''2977840''>is</span> <span m=''2978050''>the</span>
  <span m=''2978270''>plus</span> <span m=''2978670''>g.</span> </p><p><span m=''2981720''>So</span>
  <span m=''2983230''>what</span> <span m=''2983410''>we</span> <span m=''2983480''>want</span>
  <span m=''2983670''>to</span> <span m=''2983740''>do</span> <span m=''2984680''>to</span>
  <span m=''2984850''>minimize</span> <span m=''2985560''>this,</span> <span m=''2986110''>is</span>
  <span m=''2986790''>we</span> <span m=''2986930''>can</span> <span m=''2987060''>minimize</span>
  <span m=''2987440''>this.</span> <span m=''2987820''>This</span> <span m=''2987990''>has</span>
  <span m=''2988130''>the</span> <span m=''2988230''>smallest</span> <span m=''2988850''>value</span>
  <span m=''2989320''>when</span> <span m=''2989520''>these</span> <span m=''2989750''>two</span>
  <span m=''2990180''>terms</span> <span m=''2990520''>are</span> <span m=''2990630''>equal,</span>
  <span m=''2992040''>which</span> <span m=''2992190''>you</span> <span m=''2992300''>can</span>
  <span m=''2992980''>either</span> <span m=''2993420''>know</span> <span m=''2993790''>as</span>
  <span m=''2994020''>a</span> <span m=''2994190''>basic</span> <span m=''2994620''>fact</span>
  <span m=''2995030''>of</span> <span m=''2995240''>the</span> <span m=''2995370''>summation</span>
  <span m=''2995970''>of</span> <span m=''2996120''>these</span> <span m=''2996360''>kinds</span>
  <span m=''2996620''>of</span> <span m=''2996710''>things,</span> <span m=''2997060''>or</span>
  <span m=''2997720''>you</span> <span m=''2997880''>could</span> <span m=''2998050''>take</span>
  <span m=''2998300''>derivatives</span> <span m=''2999040''>and</span> <span m=''2999770''>so</span>
  <span m=''3000040''>forth.</span> <span m=''3002210''>Or</span> <span m=''3002360''>you
  can</span> <span m=''3002540''>just</span> <span m=''3002730''>eyeball it</span>
  <span m=''3003160''>and</span> <span m=''3003290''>say,</span> <span m=''3003460''>gee,</span>
  <span m=''3003830''>if</span> <span m=''3004070''>g</span> <span m=''3004320''>is</span>
  <span m=''3004520''>bigger</span> <span m=''3004880''>than</span> <span m=''3005050''>square</span>
  <span m=''3005470''>root</span> <span m=''3005735''>of n,</span> <span m=''3006480''>then</span>
  <span m=''3007340''>this</span> <span m=''3007550''>is</span> <span m=''3007690''>going</span>
  <span m=''3007780''>to</span> <span m=''3007860''>be the</span> <span m=''3008000''>dominant,</span>
  <span m=''3008520''>and</span> <span m=''3008710''>if</span> <span m=''3009210''>g</span>
  <span m=''3009600''>is</span> <span m=''3009710''>smaller</span> <span m=''3010140''>than</span>
  <span m=''3010360''>square root</span> <span m=''3010820''>of</span> <span m=''3010960''>n,
  then</span> <span m=''3011120''>this</span> <span m=''3011290''>is</span> <span
  m=''3011420''>going</span> <span m=''3011500''>to</span> <span m=''3011570''>be</span>
  <span m=''3011680''>dominant.</span> <span m=''3012630''>And</span> <span m=''3012790''>so</span>
  <span m=''3013020''>when</span> <span m=''3013260''>they''re</span> <span m=''3013450''>equal,</span>
  <span m=''3013890''>that</span> <span m=''3014110''>sounds</span> <span m=''3014420''>like</span>
  <span m=''3014590''>about</span> <span m=''3014890''>when</span> <span m=''3015010''>it</span>
  <span m=''3015130''>should</span> <span m=''3015300''>be</span> <span m=''3015440''>the</span>
  <span m=''3015540''>smallest,</span> <span m=''3016100''>which</span> <span m=''3016260''>is</span>
  <span m=''3016430''>true.</span> <span m=''3017720''>So</span> <span m=''3017880''>we
  pick</span> <span m=''3018110''>it</span> <span m=''3018210''>to</span> <span m=''3018290''>be</span>
  <span m=''3018430''>about</span> <span m=''3018780''>square</span> <span m=''3019120''>root</span>
  <span m=''3019230''>of</span> <span m=''3019330''>n,</span> <span m=''3020140''>to</span>
  <span m=''3020270''>minimize</span> <span m=''3021570''>the</span> <span m=''3021670''>span.</span>
  <span m=''3022970''>Since</span> <span m=''3023270''>g, I</span> <span m=''3023730''>don''t</span>
  <span m=''3023910''>have</span> <span m=''3024030''>anything</span> <span m=''3024380''>to</span>
  <span m=''3024470''>minimize</span> <span m=''3024920''>here.</span> <span m=''3025620''>So</span>
  <span m=''3025750''>pick it</span> <span m=''3025940''>around</span> <span m=''3026290''>square</span>
  <span m=''3026570''>root</span> <span m=''3026650''>of</span> <span m=''3026750''>n,</span>
  <span m=''3028610''>then</span> <span m=''3028990''>the</span> <span m=''3029090''>span</span>
  <span m=''3029650''>is</span> <span m=''3029790''>around</span> <span m=''3030200''>square
  root of</span> <span m=''3030490''>n.</span> <span m=''3031520''>And</span> <span
  m=''3031670''>so</span> <span m=''3031800''>then</span> <span m=''3031970''>the</span>
  <span m=''3032060''>parallelism</span> <span m=''3032800''>is</span> <span m=''3034620''>order</span>
  <span m=''3034890''>square</span> <span m=''3035180''>root</span> <span m=''3035270''>of</span>
  <span m=''3035360''>n.</span> <span m=''3037680''>So</span> <span m=''3037860''>that''s</span>
  <span m=''3038110''>pretty</span> <span m=''3038350''>good.</span> <span m=''3038880''>So</span>
  <span m=''3039340''>that''s</span> <span m=''3039580''>not</span> <span m=''3039810''>bad.</span>
  <span m=''3040150''>So</span> <span m=''3040290''>for</span> <span m=''3040450''>something</span>
  <span m=''3040830''>that''s</span> <span m=''3040980''>a</span> <span m=''3041030''>big
  array,</span> <span m=''3042040''>array</span> <span m=''3042290''>of</span> <span
  m=''3042570''>size</span> <span m=''3042890''>1</span> <span m=''3042950''>million,</span>
  <span m=''3044720''>parallelism</span> <span m=''3045025''>might</span> <span m=''3045330''>be</span>
  <span m=''3045590''>1,000.</span> <span m=''3046310''>That</span> <span m=''3046500''>might</span>
  <span m=''3046720''>be</span> <span m=''3046850''>just</span> <span m=''3047650''>hunky</span>
  <span m=''3047930''>dory.</span> <span m=''3050300''>Question.</span> <span m=''3051142''>What''s
  that?</span> </p><p><span m=''3051594''>AUDIENCE:</span> <span m=''3052046''>I don''t</span>
  <span m=''3052950''>see</span> <span m=''3053402''>where--</span> </p><p><span m=''3054510''>CHARLES
  LEISERSON: We''ve</span> <span m=''3054880''>picked</span> <span m=''3055250''>g</span>
  <span m=''3055510''>to</span> <span m=''3055580''>be</span> <span m=''3055760''>equal</span>
  <span m=''3056090''>to</span> <span m=''3056170''>square</span> <span m=''3056600''>root
  of</span> <span m=''3057000''>n.</span> </p><p><span m=''3057986''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''3058479''>plus</span> <span m=''3058972''>n over</span> <span m=''3059465''>g,</span>
  <span m=''3060451''>plus g.</span> <span m=''3060944''>I don''t</span> <span m=''3061437''>see
  where</span> <span m=''3061930''>[INAUDIBLE].</span> </p><p><span m=''3062430''>CHARLES
  LEISERSON: You</span> <span m=''3062815''>don''t see</span> <span m=''3063200''>where</span>
  <span m=''3063650''>this</span> <span m=''3063910''>g</span> <span m=''3064130''>came</span>
  <span m=''3064350''>from?</span> <span m=''3065870''>This</span> <span m=''3066100''>g</span>
  <span m=''3066340''>comes</span> <span m=''3066590''>from,</span> <span m=''3066780''>because</span>
  <span m=''3066990''>I''m</span> <span m=''3067090''>doing</span> <span m=''3067330''>g</span>
  <span m=''3067680''>iterations</span> <span m=''3068030''>here.</span> <span m=''3069540''>So</span>
  <span m=''3069680''>remember</span> <span m=''3069990''>that</span> <span m=''3070180''>these</span>
  <span m=''3070420''>are</span> <span m=''3070490''>now</span> <span m=''3070780''>of</span>
  <span m=''3070910''>size</span> <span m=''3071450''>g.</span> <span m=''3071780''>I''m</span>
  <span m=''3072110''>doing</span> <span m=''3072300''>g</span> <span m=''3072660''>iterations</span>
  <span m=''3073020''>in</span> <span m=''3073130''>each</span> <span m=''3073370''>leaf</span>
  <span m=''3073630''>here,</span> <span m=''3074390''>if</span> <span m=''3074510''>I</span>
  <span m=''3074600''>set</span> <span m=''3074900''>g to be</span> <span m=''3075240''>large.</span>
  <span m=''3075860''>So</span> <span m=''3076000''>I''m</span> <span m=''3076110''>doing</span>
  <span m=''3076450''>n</span> <span m=''3076670''>over</span> <span m=''3076940''>g</span>
  <span m=''3077160''>pieces</span> <span m=''3077580''>here,</span> <span m=''3078230''>plus</span>
  <span m=''3078490''>g</span> <span m=''3079190''>iterations</span> <span m=''3081650''>in</span>
  <span m=''3081810''>my</span> <span m=''3081960''>[INAUDIBLE].</span> <span m=''3082610''>Is</span>
  <span m=''3082760''>that</span> <span m=''3082910''>clear?</span> <span m=''3084090''>So</span>
  <span m=''3084260''>the</span> <span m=''3084390''>n</span> <span m=''3084550''>over</span>
  <span m=''3084760''>g</span> <span m=''3085020''>is</span> <span m=''3085200''>this</span>
  <span m=''3085420''>part.</span> <span m=''3086120''>This</span> <span m=''3086500''>size</span>
  <span m=''3086910''>here,</span> <span m=''3087090''>this</span> <span m=''3087220''>is</span>
  <span m=''3087340''>not</span> <span m=''3087600''>one.</span> <span m=''3088710''>This</span>
  <span m=''3088880''>has</span> <span m=''3089310''>g</span> <span m=''3089500''>iterations</span>
  <span m=''3089990''>in it.</span> <span m=''3090620''>So</span> <span m=''3090780''>the</span>
  <span m=''3090900''>total</span> <span m=''3091250''>span</span> <span m=''3091700''>is</span>
  <span m=''3092010''>g</span> <span m=''3092180''>plus</span> <span m=''3092450''>n</span>
  <span m=''3092610''>over</span> <span m=''3092800''>g.</span> <span m=''3097370''>Any</span>
  <span m=''3097570''>other</span> <span m=''3097740''>questions</span> <span m=''3098210''>about</span>
  <span m=''3098450''>this?</span> </p><p><span m=''3099280''>So</span> <span m=''3099450''>basically,</span>
  <span m=''3099910''>I</span> <span m=''3100000''>get</span> <span m=''3100280''>order</span>
  <span m=''3100570''>square</span> <span m=''3101070''>root of</span> <span m=''3101410''>n.</span>
  <span m=''3104270''>And</span> <span m=''3104590''>so</span> <span m=''3104740''>this</span>
  <span m=''3104930''>is</span> <span m=''3105050''>not</span> <span m=''3105330''>necessarily</span>
  <span m=''3106180''>a</span> <span m=''3106230''>bad</span> <span m=''3106540''>way</span>
  <span m=''3106710''>of</span> <span m=''3106850''>doing</span> <span m=''3107210''>it,</span>
  <span m=''3108940''>but</span> <span m=''3109170''>the</span> <span m=''3109370''>cilk
  for</span> <span m=''3109930''>is</span> <span m=''3110040''>a</span> <span m=''3110100''>far</span>
  <span m=''3110420''>more</span> <span m=''3110640''>reliable</span> <span m=''3111200''>way</span>
  <span m=''3111390''>of</span> <span m=''3111490''>making</span> <span m=''3111810''>sure
  that</span> <span m=''3112160''>you</span> <span m=''3112380''>get</span> <span
  m=''3113050''>the</span> <span m=''3113150''>parallelism</span> <span m=''3113660''>than</span>
  <span m=''3113770''>spawning</span> <span m=''3114230''>things</span> <span m=''3114500''>off</span>
  <span m=''3114740''>one</span> <span m=''3114910''>by</span> <span m=''3115080''>one.</span>
  <span m=''3115710''>One</span> <span m=''3115960''>of</span> <span m=''3116020''>the</span>
  <span m=''3116070''>things,</span> <span m=''3116380''>by</span> <span m=''3116510''>the</span>
  <span m=''3116620''>way,</span> <span m=''3116880''>in</span> <span m=''3117080''>this,</span>
  <span m=''3118250''>I''ve</span> <span m=''3118420''>seen</span> <span m=''3118750''>people</span>
  <span m=''3120000''>write</span> <span m=''3120310''>code</span> <span m=''3121040''>where</span>
  <span m=''3121170''>their</span> <span m=''3121320''>first</span> <span m=''3121760''>instinct</span>
  <span m=''3122390''>is</span> <span m=''3122590''>to</span> <span m=''3122720''>write</span>
  <span m=''3123010''>something</span> <span m=''3123370''>like</span> <span m=''3123630''>this,</span>
  <span m=''3124320''>where</span> <span m=''3124620''>this</span> <span m=''3125080''>that</span>
  <span m=''3125250''>they''re</span> <span m=''3125380''>spawning</span> <span m=''3125790''>off</span>
  <span m=''3126140''>is</span> <span m=''3126380''>only</span> <span m=''3126600''>constant</span>
  <span m=''3127120''>time.</span> <span m=''3127660''>And</span> <span m=''3127980''>they</span>
  <span m=''3128190''>say,</span> <span m=''3128360''>gee,</span> <span m=''3128600''>I</span>
  <span m=''3128730''>spawned</span> <span m=''3129120''>off n</span> <span m=''3129610''>things.</span>
  <span m=''3131810''>That''s</span> <span m=''3132060''>really</span> <span m=''3132450''>parallel.</span>
  <span m=''3134340''>When</span> <span m=''3134540''>in</span> <span m=''3134650''>fact,</span>
  <span m=''3135020''>their</span> <span m=''3135070''>parallelism</span> <span m=''3135730''>is</span>
  <span m=''3135850''>order</span> <span m=''3136130''>one.</span> <span m=''3138270''>So</span>
  <span m=''3139530''>it''s</span> <span m=''3139760''>really</span> <span m=''3140520''>seductive</span>
  <span m=''3141230''>to</span> <span m=''3141350''>think</span> <span m=''3141650''>that</span>
  <span m=''3141790''>you</span> <span m=''3141940''>can</span> <span m=''3142350''>get</span>
  <span m=''3142600''>parallelism</span> <span m=''3143140''>by</span> <span m=''3143320''>this,</span>
  <span m=''3143420''>[? right. ?]</span> <span m=''3143880''>It''s</span> <span m=''3144020''>much</span>
  <span m=''3144250''>better</span> <span m=''3144640''>to</span> <span m=''3144740''>do</span>
  <span m=''3144930''>divide</span> <span m=''3145280''>and</span> <span m=''3145400''>conquer,</span>
  <span m=''3146220''>and</span> <span m=''3146420''>cilk for</span> <span m=''3146950''>does</span>
  <span m=''3147160''>that</span> <span m=''3147420''>for</span> <span m=''3147600''>you</span>
  <span m=''3147720''>automatically.</span> <span m=''3149140''>If you''re</span>
  <span m=''3149420''>going to do it</span> <span m=''3149770''>by</span> <span m=''3149940''>hand,</span>
  <span m=''3150260''>sometimes</span> <span m=''3150650''>you</span> <span m=''3150740''>do</span>
  <span m=''3150860''>want</span> <span m=''3151010''>to</span> <span m=''3151060''>do
  it by hand,</span> <span m=''3151780''>then</span> <span m=''3151930''>you</span>
  <span m=''3152040''>probably</span> <span m=''3152460''>want</span> <span m=''3152640''>to</span>
  <span m=''3152690''>think</span> <span m=''3152940''>more</span> <span m=''3153160''>about</span>
  <span m=''3153420''>divide</span> <span m=''3153720''>and</span> <span m=''3153850''>conquer</span>
  <span m=''3154650''>to</span> <span m=''3154770''>generate</span> <span m=''3155200''>parallelism,</span>
  <span m=''3155670''>because</span> <span m=''3155900''>you''ll</span> <span m=''3155970''>have</span>
  <span m=''3156080''>a</span> <span m=''3156130''>small</span> <span m=''3156490''>span,</span>
  <span m=''3156670''>than</span> <span m=''3157600''>doing</span> <span m=''3157930''>many</span>
  <span m=''3158230''>things</span> <span m=''3158590''>one</span> <span m=''3158770''>at</span>
  <span m=''3158840''>a</span> <span m=''3158950''>time.</span> </p><p><span m=''3161800''>So</span>
  <span m=''3161920''>here''s</span> <span m=''3162160''>some</span> <span m=''3162330''>tips</span>
  <span m=''3164720''>for</span> <span m=''3164870''>performance.</span> <span m=''3167520''>So</span>
  <span m=''3168350''>you</span> <span m=''3168450''>want</span> <span m=''3168610''>to</span>
  <span m=''3170090''>minimize</span> <span m=''3170700''>the</span> <span m=''3170840''>span,</span>
  <span m=''3171260''>so the</span> <span m=''3171350''>parallelism</span> <span m=''3171980''>is</span>
  <span m=''3172090''>the</span> <span m=''3172180''>work</span> <span m=''3172440''>over</span>
  <span m=''3172570''>the</span> <span m=''3172700''>span.</span> <span m=''3173470''>So</span>
  <span m=''3173620''>you</span> <span m=''3173700''>want</span> <span m=''3173860''>to</span>
  <span m=''3173900''>minimize</span> <span m=''3174530''>the</span> <span m=''3174610''>span</span>
  <span m=''3175630''>to</span> <span m=''3175770''>maximize</span> <span m=''3176570''>parallelism.</span>
  <span m=''3177880''>And</span> <span m=''3178220''>in</span> <span m=''3178410''>general,</span>
  <span m=''3178790''>you</span> <span m=''3178900''>should</span> <span m=''3179080''>try</span>
  <span m=''3179290''>to</span> <span m=''3179390''>generate</span> <span m=''3179950''>something</span>
  <span m=''3180270''>like</span> <span m=''3180510''>10</span> <span m=''3180770''>times</span>
  <span m=''3181140''>more</span> <span m=''3181350''>parallelism</span> <span m=''3182050''>than</span>
  <span m=''3182160''>processors,</span> <span m=''3183450''>if</span> <span m=''3183590''>you</span>
  <span m=''3183720''>want</span> <span m=''3183910''>to</span> <span m=''3183960''>get</span>
  <span m=''3184290''>near</span> <span m=''3184480''>perfect</span> <span m=''3184850''>linear</span>
  <span m=''3185130''>speed-up.</span> <span m=''3185510''>In</span> <span m=''3185620''>other
  words,</span> <span m=''3185870''>a</span> <span m=''3185920''>parallel</span> <span
  m=''3186360''>slackness</span> <span m=''3186950''>of</span> <span m=''3187070''>10</span>
  <span m=''3188230''>or</span> <span m=''3188370''>better</span> <span m=''3189030''>is</span>
  <span m=''3189200''>usually</span> <span m=''3189670''>adequate.</span> <span m=''3193340''>If</span>
  <span m=''3193500''>you</span> <span m=''3193650''>can</span> <span m=''3193840''>get</span>
  <span m=''3194100''>more,</span> <span m=''3194500''>you''re</span> <span m=''3194680''>now</span>
  <span m=''3194920''>talking</span> <span m=''3195390''>that</span> <span m=''3195600''>you</span>
  <span m=''3195740''>can</span> <span m=''3195920''>get</span> <span m=''3196190''>more</span>
  <span m=''3197400''>performance,</span> <span m=''3198130''>but</span> <span m=''3198330''>now</span>
  <span m=''3199230''>you''re</span> <span m=''3201790''>getting</span> <span m=''3202200''>performance</span>
  <span m=''3202720''>increases</span> <span m=''3204500''>in</span> <span m=''3204630''>the</span>
  <span m=''3204730''>range</span> <span m=''3205040''>of</span> <span m=''3205120''>5%</span>
  <span m=''3205485''>or</span> <span m=''3205850''>so,</span> <span m=''3206130''>5%</span>
  <span m=''3206410''>to</span> <span m=''3206510''>10%,</span> <span m=''3207110''>something</span>
  <span m=''3207370''>like</span> <span m=''3207590''>that.</span> </p><p><span m=''3209890''>Second</span>
  <span m=''3210220''>thing</span> <span m=''3210370''>is</span> <span m=''3210470''>if</span>
  <span m=''3210540''>you</span> <span m=''3210640''>have</span> <span m=''3210990''>plenty</span>
  <span m=''3211300''>of</span> <span m=''3211370''>parallelism,</span> <span m=''3213100''>try</span>
  <span m=''3213390''>to</span> <span m=''3213520''>trade</span> <span m=''3213950''>some</span>
  <span m=''3214200''>of</span> <span m=''3214320''>it</span> <span m=''3214410''>off</span>
  <span m=''3214820''>to</span> <span m=''3214970''>reduce</span> <span m=''3215400''>work</span>
  <span m=''3215810''>overhead.</span> <span m=''3216970''>So</span> <span m=''3217110''>this
  is</span> <span m=''3217260''>a</span> <span m=''3217360''>general</span> <span
  m=''3217770''>case.</span> <span m=''3218060''>This</span> <span m=''3218210''>is</span>
  <span m=''3218360''>what</span> <span m=''3218780''>actually</span> <span m=''3219220''>goes</span>
  <span m=''3219520''>on</span> <span m=''3220330''>underneath</span> <span m=''3220970''>in</span>
  <span m=''3221230''>the</span> <span m=''3221450''>cilk++</span> <span m=''3222800''>runtime</span>
  <span m=''3223280''>system,</span> <span m=''3223690''>is</span> <span m=''3223880''>they
  are</span> <span m=''3224150''>trying</span> <span m=''3224380''>to</span> <span
  m=''3224610''>do</span> <span m=''3224770''>this</span> <span m=''3225020''>themselves.</span>
  <span m=''3225790''>But</span> <span m=''3226000''>you</span> <span m=''3226200''>in</span>
  <span m=''3226300''>your</span> <span m=''3226460''>own</span> <span m=''3226620''>code</span>
  <span m=''3226940''>can</span> <span m=''3227110''>play</span> <span m=''3227360''>exactly</span>
  <span m=''3227900''>the</span> <span m=''3228000''>same</span> <span m=''3228350''>game.</span>
  <span m=''3229640''>Whenever</span> <span m=''3229990''>you</span> <span m=''3230120''>have</span>
  <span m=''3230240''>a</span> <span m=''3230310''>problem</span> <span m=''3230840''>and</span>
  <span m=''3230910''>it</span> <span m=''3231030''>says,</span> <span m=''3231360''>whoa,</span>
  <span m=''3231930''>look</span> <span m=''3232120''>at</span> <span m=''3232170''>all</span>
  <span m=''3232330''>this</span> <span m=''3232460''>parallelism,</span> <span m=''3233400''>think</span>
  <span m=''3233570''>about</span> <span m=''3233860''>ways</span> <span m=''3234170''>that</span>
  <span m=''3234280''>you</span> <span m=''3234380''>could</span> <span m=''3234550''>reduce</span>
  <span m=''3235040''>the</span> <span m=''3235130''>parallelism</span> <span m=''3236220''>and</span>
  <span m=''3236450''>get</span> <span m=''3236730''>something</span> <span m=''3237170''>back</span>
  <span m=''3237730''>in</span> <span m=''3239220''>the</span> <span m=''3239360''>efficiency</span>
  <span m=''3239960''>of</span> <span m=''3240050''>the</span> <span m=''3240140''>work</span>
  <span m=''3240470''>term,</span> <span m=''3241910''>because</span> <span m=''3242150''>the</span>
  <span m=''3242230''>performance</span> <span m=''3242800''>in</span> <span m=''3242870''>the</span>
  <span m=''3243000''>end</span> <span m=''3243330''>is</span> <span m=''3243490''>going</span>
  <span m=''3243610''>to</span> <span m=''3243670''>be</span> <span m=''3244800''>something</span>
  <span m=''3245200''>like</span> <span m=''3245710''>t1</span> <span m=''3246010''>over</span>
  <span m=''3246330''>p</span> <span m=''3246620''>plus</span> <span m=''3246990''>t</span>
  <span m=''3247190''>infinity.</span> <span m=''3248070''>If t</span> <span m=''3248380''>infinity</span>
  <span m=''3248830''>is</span> <span m=''3248960''>small,</span> <span m=''3249275''>it''s</span>
  <span m=''3249590''>like</span> <span m=''3249970''>t1</span> <span m=''3250180''>over</span>
  <span m=''3250480''>p,</span> <span m=''3251160''>and</span> <span m=''3251300''>so</span>
  <span m=''3251400''>anything</span> <span m=''3251820''>you</span> <span m=''3251920''>save</span>
  <span m=''3252290''>in</span> <span m=''3252400''>the</span> <span m=''3252720''>t1</span>
  <span m=''3253030''>term</span> <span m=''3253960''>is</span> <span m=''3254090''>saving</span>
  <span m=''3254520''>you</span> <span m=''3254730''>overall.</span> <span m=''3256060''>It''s</span>
  <span m=''3256360''>going</span> <span m=''3256480''>to</span> <span m=''3256520''>be</span>
  <span m=''3256620''>a</span> <span m=''3256660''>savings</span> <span m=''3257120''>for</span>
  <span m=''3257200''>you</span> <span m=''3257380''>overall.</span> </p><p><span
  m=''3259630''>Use</span> <span m=''3259890''>divide and</span> <span m=''3260340''>conquer</span>
  <span m=''3260595''>recursion</span> <span m=''3260850''>on</span> <span m=''3261470''>parallel</span>
  <span m=''3261910''>loops</span> <span m=''3262200''>rather</span> <span m=''3262510''>than</span>
  <span m=''3262660''>sprawling</span> <span m=''3263200''>one</span> <span m=''3263460''>small</span>
  <span m=''3263860''>thing</span> <span m=''3264100''>after</span> <span m=''3264390''>another.</span>
  <span m=''3264870''>In</span> <span m=''3265230''>other words,</span> <span m=''3265590''>do</span>
  <span m=''3265760''>this</span> <span m=''3266690''>not</span> <span m=''3267020''>this,</span>
  <span m=''3268480''>generally.</span> <span m=''3273620''>And</span> <span m=''3273760''>here''s</span>
  <span m=''3273960''>some</span> <span m=''3274070''>more</span> <span m=''3274270''>tips.</span>
  <span m=''3276220''>Another</span> <span m=''3276670''>thing</span> <span m=''3276880''>that</span>
  <span m=''3277030''>can</span> <span m=''3277160''>happen</span> <span m=''3278050''>that</span>
  <span m=''3278150''>we</span> <span m=''3278280''>looked</span> <span m=''3278550''>at</span>
  <span m=''3278680''>here</span> <span m=''3279040''>was</span> <span m=''3279520''>make</span>
  <span m=''3279800''>sure</span> <span m=''3280050''>that</span> <span m=''3280270''>the</span>
  <span m=''3280380''>amount</span> <span m=''3280620''>of</span> <span m=''3280760''>work</span>
  <span m=''3281050''>you''re</span> <span m=''3281220''>doing</span> <span m=''3282130''>is</span>
  <span m=''3282300''>reasonably</span> <span m=''3282760''>large</span> <span m=''3283130''>compared</span>
  <span m=''3283550''>to</span> <span m=''3283640''>the</span> <span m=''3283730''>number</span>
  <span m=''3284070''>of</span> <span m=''3284130''>spawns.</span> <span m=''3285390''>You</span>
  <span m=''3285520''>could</span> <span m=''3285610''>also</span> <span m=''3285900''>say</span>
  <span m=''3286140''>this</span> <span m=''3286330''>is</span> <span m=''3286460''>true</span>
  <span m=''3286770''>when</span> <span m=''3286970''>you</span> <span m=''3287080''>do</span>
  <span m=''3287230''>recursion</span> <span m=''3287590''>for</span> <span m=''3287950''>function</span>
  <span m=''3288380''>calls.</span> <span m=''3289280''>Make</span> <span m=''3289480''>sure</span>
  <span m=''3289710''>if</span> <span m=''3289810''>you''re</span> <span m=''3289990''>just</span>
  <span m=''3290300''>in</span> <span m=''3290400''>serial</span> <span m=''3290900''>programming,</span>
  <span m=''3291750''>you</span> <span m=''3291850''>always</span> <span m=''3292040''>want</span>
  <span m=''3292180''>to</span> <span m=''3292230''>make</span> <span m=''3292440''>sure</span>
  <span m=''3292780''>that</span> <span m=''3292970''>the</span> <span m=''3293050''>amount</span>
  <span m=''3293280''>of</span> <span m=''3293370''>work</span> <span m=''3293630''>you''re</span>
  <span m=''3293780''>doing</span> <span m=''3294100''>is</span> <span m=''3294180''>small</span>
  <span m=''3294970''>compared</span> <span m=''3295350''>to</span> <span m=''3295420''>the</span>
  <span m=''3295510''>number of</span> <span m=''3295770''>function</span> <span m=''3296190''>calls</span>
  <span m=''3296520''>are</span> <span m=''3296610''>doing</span> <span m=''3297350''>if</span>
  <span m=''3297500''>you</span> <span m=''3297610''>can,</span> <span m=''3297910''>and</span>
  <span m=''3298000''>that''ll</span> <span m=''3298270''>make</span> <span m=''3298500''>things</span>
  <span m=''3298780''>go</span> <span m=''3298920''>faster.</span> <span m=''3300120''>So</span>
  <span m=''3300270''>same</span> <span m=''3300550''>thing</span> <span m=''3300740''>here,</span>
  <span m=''3305834''>you</span> <span m=''3306291''>want to</span> <span m=''3306750''>have</span>
  <span m=''3306960''>a</span> <span m=''3307000''>lot</span> <span m=''3307290''>of</span>
  <span m=''3307380''>work</span> <span m=''3307680''>compared</span> <span m=''3308050''>to</span>
  <span m=''3308130''>the</span> <span m=''3308250''>total</span> <span m=''3308560''>number</span>
  <span m=''3308850''>of</span> <span m=''3308940''>spawns</span> <span m=''3309390''>that</span>
  <span m=''3309510''>you''re</span> <span m=''3309620''>doing</span> <span m=''3309900''>in</span>
  <span m=''3309960''>your</span> <span m=''3310080''>program.</span> <span m=''3311780''>So</span>
  <span m=''3311950''>spawns,</span> <span m=''3312500''>by</span> <span m=''3312610''>the</span>
  <span m=''3312710''>way,</span> <span m=''3312910''>in</span> <span m=''3313020''>this</span>
  <span m=''3313100''>system,</span> <span m=''3313510''>are</span> <span m=''3313630''>about</span>
  <span m=''3314210''>three</span> <span m=''3314470''>or</span> <span m=''3314520''>four</span>
  <span m=''3314880''>times</span> <span m=''3315830''>the</span> <span m=''3315960''>cost</span>
  <span m=''3316320''>of</span> <span m=''3316410''>a</span> <span m=''3316460''>function</span>
  <span m=''3316870''>call.</span> <span m=''3319500''>They''re</span> <span m=''3319620''>sort</span>
  <span m=''3319800''>of</span> <span m=''3319850''>the</span> <span m=''3319930''>same</span>
  <span m=''3321000''>order</span> <span m=''3321250''>of</span> <span m=''3321300''>magnitude</span>
  <span m=''3322180''>as</span> <span m=''3322350''>a</span> <span m=''3322400''>function</span>
  <span m=''3322800''>call,</span> <span m=''3324970''>a</span> <span m=''3325040''>little</span>
  <span m=''3325330''>bit</span> <span m=''3325470''>heavier</span> <span m=''3325850''>than</span>
  <span m=''3325990''>a</span> <span m=''3326040''>function</span> <span m=''3326430''>call.</span>
  <span m=''3326670''>So you can</span> <span m=''3326980''>spawn</span> <span m=''3327770''>pretty</span>
  <span m=''3328450''>readily,</span> <span m=''3329870''>as</span> <span m=''3330030''>long</span>
  <span m=''3330300''>as</span> <span m=''3331440''>the</span> <span m=''3331560''>total</span>
  <span m=''3331960''>number</span> <span m=''3332240''>of</span> <span m=''3332630''>spawns
  you''re</span> <span m=''3333130''>doing</span> <span m=''3333490''>isn''t</span>
  <span m=''3333770''>dominating</span> <span m=''3334340''>your</span> <span m=''3334490''>work.</span>
  </p><p><span m=''3337350''>Generally</span> <span m=''3338100''>parallelize</span>
  <span m=''3338940''>outer</span> <span m=''3339040''>loops</span> <span m=''3339390''>as</span>
  <span m=''3339530''>opposed</span> <span m=''3339880''>to</span> <span m=''3339960''>inner</span>
  <span m=''3340210''>loops</span> <span m=''3340510''>if</span> <span m=''3340620''>you''re</span>
  <span m=''3340740''>forced</span> <span m=''3341100''>to</span> <span m=''3341180''>make</span>
  <span m=''3341380''>a</span> <span m=''3341440''>choice.</span> <span m=''3343620''>So</span>
  <span m=''3343880''>it''s</span> <span m=''3344010''>always</span> <span m=''3344410''>better</span>
  <span m=''3345270''>to</span> <span m=''3345490''>have</span> <span m=''3345700''>an</span>
  <span m=''3345920''>outer</span> <span m=''3346170''>loop</span> <span m=''3346500''>that</span>
  <span m=''3346690''>runs</span> <span m=''3346990''>in</span> <span m=''3347090''>parallel</span>
  <span m=''3348520''>rather</span> <span m=''3348850''>than</span> <span m=''3349010''>an</span>
  <span m=''3349150''>inner</span> <span m=''3349360''>loop</span> <span m=''3350110''>that</span>
  <span m=''3350260''>runs</span> <span m=''3350550''>in</span> <span m=''3350650''>parallel,</span>
  <span m=''3351000''>because</span> <span m=''3351170''>when you</span> <span m=''3351340''>do</span>
  <span m=''3351450''>an</span> <span m=''3351540''>inner</span> <span m=''3351750''>loop</span>
  <span m=''3352000''>that</span> <span m=''3352140''>runs</span> <span m=''3352390''>in</span>
  <span m=''3352500''>parallel,</span> <span m=''3354750''>you''ve</span> <span m=''3354880''>got</span>
  <span m=''3355020''>a</span> <span m=''3355040''>lot</span> <span m=''3355270''>of</span>
  <span m=''3355390''>overhead</span> <span m=''3355860''>to</span> <span m=''3356180''>overcome.</span>
  <span m=''3356590''>But in an</span> <span m=''3356820''>outer</span> <span m=''3357150''>loop,</span>
  <span m=''3358110''>you''ve</span> <span m=''3358240''>got</span> <span m=''3358480''>all</span>
  <span m=''3358780''>of</span> <span m=''3358860''>the</span> <span m=''3359010''>inner</span>
  <span m=''3359210''>loop</span> <span m=''3360650''>to</span> <span m=''3360980''>amortize</span>
  <span m=''3361690''>against</span> <span m=''3361960''>the</span> <span m=''3362220''>cost</span>
  <span m=''3362610''>of</span> <span m=''3362690''>the</span> <span m=''3362760''>spawns</span>
  <span m=''3363340''>that</span> <span m=''3363420''>are</span> <span m=''3363480''>being</span>
  <span m=''3363680''>used</span> <span m=''3363930''>to</span> <span m=''3364000''>parallelize</span>
  <span m=''3364540''>the</span> <span m=''3364690''>outer</span> <span m=''3365090''>loop.</span>
  <span m=''3366570''>So</span> <span m=''3366690''>you''ll</span> <span m=''3366810''>do</span>
  <span m=''3366940''>many</span> <span m=''3367280''>fewer</span> <span m=''3367520''>spawns</span>
  <span m=''3369440''>in</span> <span m=''3369750''>the</span> <span m=''3369830''>implementation.</span>
  </p><p><span m=''3372810''>Watch</span> <span m=''3373170''>out</span> <span m=''3373400''>for</span>
  <span m=''3373580''>scheduling</span> <span m=''3374100''>overheads.</span> <span
  m=''3378620''>So</span> <span m=''3379520''>if</span> <span m=''3379690''>you</span>
  <span m=''3379840''>do</span> <span m=''3380120''>something</span> <span m=''3380570''>like</span>
  <span m=''3380890''>this--</span> <span m=''3381990''>so</span> <span m=''3382190''>here</span>
  <span m=''3384220''>we''re</span> <span m=''3384400''>paralyzing</span> <span m=''3384715''>an</span>
  <span m=''3385030''>inner</span> <span m=''3385350''>loop</span> <span m=''3386630''>rather</span>
  <span m=''3386900''>than</span> <span m=''3387040''>an</span> <span m=''3387310''>outer
  loop.</span> <span m=''3387640''>Now</span> <span m=''3387910''>this</span> <span
  m=''3388130''>turns</span> <span m=''3388500''>out,</span> <span m=''3388870''>it</span>
  <span m=''3388990''>doesn''t</span> <span m=''3389280''>matter</span> <span m=''3389510''>which</span>
  <span m=''3389740''>order</span> <span m=''3389990''>we''re</span> <span m=''3390120''>going</span>
  <span m=''3390470''>in</span> <span m=''3390550''>or</span> <span m=''3390640''>whatever.</span>
  <span m=''3393000''>It''s</span> <span m=''3393260''>generally</span> <span m=''3393600''>not</span>
  <span m=''3393920''>desirable</span> <span m=''3394420''>to do</span> <span m=''3394530''>this</span>
  <span m=''3394870''>because</span> <span m=''3395130''>I''m</span> <span m=''3395260''>paying</span>
  <span m=''3395650''>scheduling</span> <span m=''3396260''>overhead</span> <span
  m=''3397840''>n</span> <span m=''3398120''>times</span> <span m=''3398520''>through</span>
  <span m=''3398800''>this</span> <span m=''3399020''>loop,</span> <span m=''3399885''>whereas</span>
  <span m=''3400230''>here,</span> <span m=''3400540''>I</span> <span m=''3400600''>pay</span>
  <span m=''3400850''>for</span> <span m=''3401220''>scheduling</span> <span m=''3401760''>overhead</span>
  <span m=''3403390''>just</span> <span m=''3403660''>twice.</span> <span m=''3406920''>So</span>
  <span m=''3407050''>is</span> <span m=''3407210''>generally</span> <span m=''3407620''>better,</span>
  <span m=''3408130''>if</span> <span m=''3408350''>I</span> <span m=''3408490''>have</span>
  <span m=''3408720''>n</span> <span m=''3409090''>pieces</span> <span m=''3409450''>of</span>
  <span m=''3409520''>work</span> <span m=''3409730''>to</span> <span m=''3409820''>do,</span>
  <span m=''3410010''>rather</span> <span m=''3410390''>than,</span> <span m=''3410920''>in</span>
  <span m=''3411050''>this</span> <span m=''3411280''>case,</span> <span m=''3412050''>parallelizing--</span>
  <span m=''3415200''>let</span> <span m=''3416130''>me</span> <span m=''3416240''>slow</span>
  <span m=''3416460''>down</span> <span m=''3416670''>here.</span> </p><p><span m=''3417510''>So</span>
  <span m=''3417690''>let''s</span> <span m=''3417900''>look</span> <span m=''3418100''>at</span>
  <span m=''3418170''>what</span> <span m=''3418320''>this</span> <span m=''3418490''>code</span>
  <span m=''3418740''>does.</span> <span m=''3418980''>This</span> <span m=''3419180''>says,</span>
  <span m=''3419530''>go</span> <span m=''3419850''>for</span> <span m=''3420230''>two</span>
  <span m=''3420470''>iterations.</span> <span m=''3423740''>Do</span> <span m=''3424010''>something</span>
  <span m=''3424890''>for</span> <span m=''3424980''>which</span> <span m=''3425160''>it
  is</span> <span m=''3425280''>going</span> <span m=''3425390''>to</span> <span m=''3425460''>take</span>
  <span m=''3425760''>n</span> <span m=''3425980''>iterations</span> <span m=''3429020''>for
  j.</span> <span m=''3429840''>So</span> <span m=''3430010''>two</span> <span m=''3430220''>iterations
  for</span> <span m=''3430630''>i,</span> <span m=''3431070''>n</span> <span m=''3431470''>iterations</span>
  <span m=''3431890''>for j.</span> <span m=''3435710''>If</span> <span m=''3435850''>you</span>
  <span m=''3435960''>look</span> <span m=''3436160''>at</span> <span m=''3436230''>the</span>
  <span m=''3436310''>parallelism</span> <span m=''3437030''>of</span> <span m=''3437140''>this,</span>
  <span m=''3437570''>what</span> <span m=''3437750''>is</span> <span m=''3437880''>the</span>
  <span m=''3437970''>parallelism</span> <span m=''3438285''>of</span> <span m=''3438600''>this</span>
  <span m=''3438840''>assuming</span> <span m=''3439250''>that f</span> <span m=''3439450''>is</span>
  <span m=''3439620''>constant</span> <span m=''3440060''>time?</span> <span m=''3443830''>What''s</span>
  <span m=''3444010''>the</span> <span m=''3444100''>parallelism</span> <span m=''3444600''>of</span>
  <span m=''3444690''>this</span> <span m=''3444900''>code?</span> <span m=''3453460''>Two.</span>
  <span m=''3455210''>The</span> <span m=''3455490''>parallelism</span> <span m=''3455970''>of</span>
  <span m=''3456060''>two,</span> <span m=''3456320''>because</span> <span m=''3456600''>I''ve</span>
  <span m=''3456680''>got</span> <span m=''3456980''>two</span> <span m=''3457160''>things</span>
  <span m=''3457460''>on</span> <span m=''3457570''>the</span> <span m=''3457690''>outer</span>
  <span m=''3457970''>loop</span> <span m=''3458230''>here,</span> <span m=''3458820''>and</span>
  <span m=''3458970''>then</span> <span m=''3459110''>each</span> <span m=''3459390''>is</span>
  <span m=''3459520''>n.</span> <span m=''3459930''>So</span> <span m=''3460060''>my</span>
  <span m=''3460200''>span</span> <span m=''3460660''>is</span> <span m=''3460800''>essentially</span>
  <span m=''3462210''>n.</span> <span m=''3463420''>My</span> <span m=''3463570''>work</span>
  <span m=''3463840''>is</span> <span m=''3463970''>like</span> <span m=''3464240''>2n,</span>
  <span m=''3465960''>something</span> <span m=''3466270''>like</span> <span m=''3466480''>that.</span>
  <span m=''3466770''>So</span> <span m=''3466880''>it''s</span> <span m=''3467000''>got</span>
  <span m=''3467140''>a</span> <span m=''3467180''>parallelism</span> <span m=''3467660''>of
  that,</span> <span m=''3468090''>too.</span> </p><p><span m=''3469250''>What''s</span>
  <span m=''3469430''>the</span> <span m=''3469530''>parallelism</span> <span m=''3470040''>of</span>
  <span m=''3470140''>this</span> <span m=''3470360''>code?</span> <span m=''3484970''>What''s</span>
  <span m=''3485100''>the</span> <span m=''3485230''>parallelism?</span> <span m=''3485790''>It''s</span>
  <span m=''3485980''>not</span> <span m=''3486210''>n,</span> <span m=''3486590''>because</span>
  <span m=''3486810''>I''m</span> <span m=''3486920''>basically</span> <span m=''3487390''>going</span>
  <span m=''3487710''>through</span> <span m=''3487920''>this</span> <span m=''3488220''>serially,</span>
  <span m=''3488590''>the</span> <span m=''3488660''>outer</span> <span m=''3489130''>loop</span>
  <span m=''3489600''>serially.</span> <span m=''3498680''>What''s</span> <span m=''3498910''>the</span>
  <span m=''3499000''>theoretical</span> <span m=''3499530''>parallelism</span> <span
  m=''3499795''>of</span> <span m=''3500060''>this?</span> <span m=''3504270''>So</span>
  <span m=''3504520''>for</span> <span m=''3504680''>each</span> <span m=''3504960''>iteration</span>
  <span m=''3505550''>here,</span> <span m=''3505800''>the</span> <span m=''3505930''>parallelism</span>
  <span m=''3506570''>is</span> <span m=''3506820''>two.</span> <span m=''3509430''>No,</span>
  <span m=''3510440''>not</span> <span m=''3510650''>n.</span> <span m=''3511170''>It</span>
  <span m=''3511360''>can''t</span> <span m=''3511690''>be</span> <span m=''3511840''>n,</span>
  <span m=''3512060''>because</span> <span m=''3512540''>I''m</span> <span m=''3512710''>basically</span>
  <span m=''3513270''>only</span> <span m=''3514210''>parallelizing</span> <span m=''3514980''>two</span>
  <span m=''3515200''>things,</span> <span m=''3516510''>and I''m</span> <span m=''3516750''>doing</span>
  <span m=''3516950''>them</span> <span m=''3517090''>serially.</span> <span m=''3520462''>The</span>
  <span m=''3520840''>outer</span> <span m=''3521110''>loop</span> <span m=''3521320''>is</span>
  <span m=''3521460''>going</span> <span m=''3521730''>serially</span> <span m=''3522300''>through</span>
  <span m=''3522630''>the</span> <span m=''3522740''>code</span> <span m=''3524280''>and</span>
  <span m=''3524540''>it''s</span> <span m=''3524960''>spawning</span> <span m=''3525410''>off</span>
  <span m=''3525590''>two</span> <span m=''3525830''>things,</span> <span m=''3526320''>two</span>
  <span m=''3526490''>things,</span> <span m=''3526810''>two</span> <span m=''3527000''>things,</span>
  <span m=''3527360''>two</span> <span m=''3527480''>things,</span> <span m=''3527730''>two</span>
  <span m=''3527930''>things.</span> <span m=''3528530''>And</span> <span m=''3528670''>waiting</span>
  <span m=''3528940''>for</span> <span m=''3529030''>them</span> <span m=''3529190''>to</span>
  <span m=''3529270''>be</span> <span m=''3529370''>done,</span> <span m=''3529690''>two</span>
  <span m=''3529830''>things,</span> <span m=''3530130''>wait for</span> <span m=''3530360''>it
  to be</span> <span m=''3530420''>done,</span> <span m=''3530730''>two</span> <span
  m=''3530880''>things,</span> <span m=''3531140''>wait for</span> <span m=''3531290''>it
  to be</span> <span m=''3531500''>done.</span> <span m=''3532540''>So</span> <span
  m=''3532900''>the</span> <span m=''3533000''>parallelism</span> <span m=''3533520''>is</span>
  <span m=''3533640''>two.</span> </p><p><span m=''3534930''>These</span> <span m=''3535140''>have</span>
  <span m=''3535200''>the</span> <span m=''3535320''>same</span> <span m=''3535620''>parallelism.</span>
  <span m=''3538690''>However if</span> <span m=''3539050''>you</span> <span m=''3539200''>run</span>
  <span m=''3539470''>this,</span> <span m=''3539830''>this</span> <span m=''3540050''>one</span>
  <span m=''3540320''>will</span> <span m=''3540460''>give</span> <span m=''3540710''>you</span>
  <span m=''3542520''>a</span> <span m=''3542600''>speedup</span> <span m=''3543050''>of</span>
  <span m=''3543190''>two</span> <span m=''3543640''>on</span> <span m=''3543820''>two</span>
  <span m=''3543980''>cores,</span> <span m=''3545740''>very</span> <span m=''3545950''>close</span>
  <span m=''3546260''>to</span> <span m=''3546330''>it.</span> <span m=''3547530''>Because</span>
  <span m=''3547880''>there''s</span> <span m=''3548120''>the</span> <span m=''3548220''>scheduling</span>
  <span m=''3548780''>overhead</span> <span m=''3549220''>here,</span> <span m=''3549580''>you''ve</span>
  <span m=''3549800''>only</span> <span m=''3549990''>paid</span> <span m=''3550280''>once
  for</span> <span m=''3550650''>the</span> <span m=''3550780''>scheduling</span>
  <span m=''3551280''>overhead,</span> <span m=''3552000''>and</span> <span m=''3552120''>then</span>
  <span m=''3552260''>you''re</span> <span m=''3552390''>doing</span> <span m=''3552600''>a</span>
  <span m=''3552650''>whole</span> <span m=''3553020''>bunch</span> <span m=''3553340''>of</span>
  <span m=''3553410''>stuff.</span> <span m=''3554640''>So</span> <span m=''3554740''>remember,</span>
  <span m=''3555060''>to</span> <span m=''3555160''>schedule</span> <span m=''3555580''>it,</span>
  <span m=''3555810''>it''s got</span> <span m=''3555910''>to</span> <span m=''3556000''>be</span>
  <span m=''3556120''>migrated,</span> <span m=''3556950''>it''s</span> <span m=''3557140''>got</span>
  <span m=''3557270''>to be</span> <span m=''3557640''>moved</span> <span m=''3557930''>to</span>
  <span m=''3558060''>another</span> <span m=''3558340''>processor,</span> <span m=''3558970''>et</span>
  <span m=''3559050''>cetera.</span> <span m=''3559910''>This</span> <span m=''3560200''>one,</span>
  <span m=''3561980''>it''s</span> <span m=''3562150''>not</span> <span m=''3562330''>even</span>
  <span m=''3562610''>worth it</span> <span m=''3562970''>probably</span> <span m=''3564120''>to</span>
  <span m=''3564530''>steal</span> <span m=''3565120''>each</span> <span m=''3565340''>of</span>
  <span m=''3565410''>these</span> <span m=''3565610''>individual</span> <span m=''3565980''>things.</span>
  <span m=''3566250''>You''re</span> <span m=''3566730''>spawning off</span> <span
  m=''3566880''>things</span> <span m=''3567100''>that are</span> <span m=''3567270''>so</span>
  <span m=''3567480''>small,</span> <span m=''3568450''>this</span> <span m=''3568640''>may
  even</span> <span m=''3569020''>have</span> <span m=''3569620''>parallelism</span>
  <span m=''3570200''>that''s</span> <span m=''3570340''>less</span> <span m=''3570670''>than</span>
  <span m=''3570790''>1</span> <span m=''3571320''>in</span> <span m=''3571460''>practice.</span>
  </p><p><span m=''3573395''>And</span> <span m=''3573650''>if</span> <span m=''3573790''>you</span>
  <span m=''3573910''>look</span> <span m=''3574150''>at</span> <span m=''3574270''>the</span>
  <span m=''3574450''>cilkview</span> <span m=''3574880''>tool,</span> <span m=''3575330''>this</span>
  <span m=''3575520''>will</span> <span m=''3575620''>show</span> <span m=''3575880''>you</span>
  <span m=''3576050''>a</span> <span m=''3576100''>high</span> <span m=''3576450''>burden</span>
  <span m=''3577010''>parallelism.</span> <span m=''3578180''>Because</span> <span
  m=''3578410''>the</span> <span m=''3578520''>cilkview</span> <span m=''3579390''>tool,</span>
  <span m=''3579710''>the</span> <span m=''3579800''>burden</span> <span m=''3580120''>parallelism</span>
  <span m=''3580560''>tells</span> <span m=''3580940''>you</span> <span m=''3581450''>what</span>
  <span m=''3581800''>the</span> <span m=''3581940''>overhead</span> <span m=''3582510''>is</span>
  <span m=''3583360''>from</span> <span m=''3583630''>scheduling,</span> <span m=''3585910''>as</span>
  <span m=''3586160''>well</span> <span m=''3586470''>as</span> <span m=''3586800''>what</span>
  <span m=''3586980''>the</span> <span m=''3587130''>actual</span> <span m=''3587440''>parallelism
  is.</span> <span m=''3588310''>And it</span> <span m=''3588960''>recognizes</span>
  <span m=''3589830''>that</span> <span m=''3589980''>oh,</span> <span m=''3590380''>gee</span>
  <span m=''3590600''>whiz.</span> <span m=''3591010''>This</span> <span m=''3591210''>thing</span>
  <span m=''3591450''>really</span> <span m=''3592720''>has</span> <span m=''3593010''>very</span>
  <span m=''3593270''>small--</span> <span m=''3600670''>there''s</span> <span m=''3600890''>almost</span>
  <span m=''3601240''>no</span> <span m=''3601430''>work in</span> <span m=''3601880''>here.</span>
  <span m=''3602200''>So you''re</span> <span m=''3602760''>trying</span> <span m=''3602960''>to</span>
  <span m=''3603030''>parallelize</span> <span m=''3603550''>something</span> <span
  m=''3603880''>where</span> <span m=''3604000''>the</span> <span m=''3604110''>work</span>
  <span m=''3604380''>is</span> <span m=''3604470''>so</span> <span m=''3604690''>small,</span>
  <span m=''3605010''>it''s</span> <span m=''3605120''>not</span> <span m=''3605270''>even</span>
  <span m=''3605480''>worth</span> <span m=''3606130''>migrating</span> <span m=''3606720''>it</span>
  <span m=''3606840''>to</span> <span m=''3606960''>take</span> <span m=''3607200''>advantage</span>
  <span m=''3607650''>of</span> <span m=''3607710''>it.</span> <span m=''3610380''>So</span>
  <span m=''3610520''>those</span> <span m=''3610710''>are</span> <span m=''3610770''>some</span>
  <span m=''3610960''>tips.</span> </p><p><span m=''3612740''>Now</span> <span m=''3612940''>let''s</span>
  <span m=''3613240''>go</span> <span m=''3613430''>through</span> <span m=''3613680''>and</span>
  <span m=''3613760''>analyze</span> <span m=''3614280''>a</span> <span m=''3614320''>bunch</span>
  <span m=''3614560''>of</span> <span m=''3614650''>algorithms</span> <span m=''3615140''>reasonably</span>
  <span m=''3615550''>quickly.</span> <span m=''3616730''>We''ll</span> <span m=''3616860''>start</span>
  <span m=''3617250''>with</span> <span m=''3619030''>matrix</span> <span m=''3619370''>multiplication.</span>
  <span m=''3621670''>People</span> <span m=''3621920''>seen</span> <span m=''3622120''>this</span>
  <span m=''3622260''>problem</span> <span m=''3622510''>before?</span> <span m=''3628400''>Here''s</span>
  <span m=''3628690''>the</span> <span m=''3628770''>matrix</span> <span m=''3629130''>multiplication</span>
  <span m=''3629890''>problem.</span> <span m=''3631900''>And</span> <span m=''3632050''>let''s</span>
  <span m=''3632250''>assume</span> <span m=''3632600''>for</span> <span m=''3632730''>simplicity</span>
  <span m=''3633390''>that</span> <span m=''3633580''>n</span> <span m=''3633780''>is</span>
  <span m=''3633900''>a</span> <span m=''3633950''>power</span> <span m=''3634400''>of</span>
  <span m=''3634520''>2.</span> <span m=''3638470''>So</span> <span m=''3638730''>basically,</span>
  <span m=''3639650''>let''s</span> <span m=''3639900''>start</span> <span m=''3640190''>out</span>
  <span m=''3640450''>with</span> <span m=''3640630''>just</span> <span m=''3641010''>our</span>
  <span m=''3643450''>looping</span> <span m=''3643870''>version.</span> <span m=''3644250''>In</span>
  <span m=''3644390''>fact,</span> <span m=''3644620''>this</span> <span m=''3644770''>isn''t</span>
  <span m=''3645000''>even</span> <span m=''3645220''>a</span> <span m=''3645250''>very</span>
  <span m=''3645470''>good</span> <span m=''3645710''>looping</span> <span m=''3646060''>version,</span>
  <span m=''3646390''>because</span> <span m=''3646600''>I''ve</span> <span m=''3646710''>got</span>
  <span m=''3646910''>the</span> <span m=''3647000''>order of</span> <span m=''3647250''>the</span>
  <span m=''3647370''>loops</span> <span m=''3647660''>wrong,</span> <span m=''3647960''>I</span>
  <span m=''3648170''>think.</span> <span m=''3649340''>But</span> <span m=''3649500''>it</span>
  <span m=''3649570''>is</span> <span m=''3649780''>just</span> <span m=''3650430''>illustrative.</span>
  <span m=''3652380''>Basically</span> <span m=''3652880''>let''s</span> <span m=''3653080''>parallelize</span>
  <span m=''3653660''>the</span> <span m=''3653810''>outer</span> <span m=''3654090''>two</span>
  <span m=''3654260''>loops.</span> <span m=''3655080''>I</span> <span m=''3655210''>can''t</span>
  <span m=''3655670''>parallelize</span> <span m=''3656200''>the</span> <span m=''3656370''>inner</span>
  <span m=''3656770''>loop.</span> <span m=''3657070''>Why</span> <span m=''3657270''>not?</span>
  <span m=''3658140''>What</span> <span m=''3658280''>happens</span> <span m=''3658560''>if</span>
  <span m=''3658670''>I</span> <span m=''3658760''>tried</span> <span m=''3659040''>to</span>
  <span m=''3659100''>parallelize</span> <span m=''3659660''>the inner</span> <span
  m=''3659850''>loop</span> <span m=''3660180''>with</span> <span m=''3660250''>a</span>
  <span m=''3660330''>cilk_for</span> <span m=''3662470''>in</span> <span m=''3662570''>this</span>
  <span m=''3662740''>implementation?</span> <span m=''3667580''>Why</span> <span
  m=''3667920''>can''t I</span> <span m=''3668010''>just</span> <span m=''3668230''>put
  a</span> <span m=''3668330''>cilk_for</span> <span m=''3668900''>there?</span> <span
  m=''3671040''>Yes,</span> <span m=''3671280''>somebody</span> <span m=''3671490''>said
  it.</span> </p><p><span m=''3672408''>AUDIENCE: It</span> <span m=''3672846''>does
  that</span> <span m=''3673284''>in</span> <span m=''3673722''>cij.</span> </p><p><span
  m=''3674600''>CHARLES LEISERSON: Yeah,</span> <span m=''3675070''>we get</span>
  <span m=''3675540''>a</span> <span m=''3675560''>race</span> <span m=''3675990''>condition.</span>
  <span m=''3677220''>We</span> <span m=''3677340''>have</span> <span m=''3677440''>more</span>
  <span m=''3677750''>than</span> <span m=''3678030''>two</span> <span m=''3678250''>things</span>
  <span m=''3678590''>in</span> <span m=''3678710''>parallel</span> <span m=''3679220''>trying</span>
  <span m=''3679480''>to</span> <span m=''3679530''>update</span> <span m=''3679980''>the</span>
  <span m=''3680060''>same</span> <span m=''3680390''>cij,</span> <span m=''3681580''>and</span>
  <span m=''3681960''>we''ll</span> <span m=''3682120''>have</span> <span m=''3682300''>a</span>
  <span m=''3682370''>race</span> <span m=''3682670''>condition.</span> <span m=''3685070''>So</span>
  <span m=''3685280''>always</span> <span m=''3685780''>run</span> <span m=''3686080''>cilkview</span>
  <span m=''3687860''>to</span> <span m=''3688040''>tell</span> <span m=''3688440''>your</span>
  <span m=''3688570''>performance.</span> <span m=''3689000''>But</span> <span m=''3689280''>always,</span>
  <span m=''3690140''>always,</span> <span m=''3690970''>run</span> <span m=''3691500''>cilk</span>
  <span m=''3691900''>screen</span> <span m=''3692820''>to</span> <span m=''3692970''>tell</span>
  <span m=''3693250''>whether</span> <span m=''3693440''>or</span> <span m=''3693480''>not
  you''ve</span> <span m=''3693910''>got</span> <span m=''3694130''>races</span> <span
  m=''3694520''>in</span> <span m=''3694620''>your</span> <span m=''3694760''>code.</span>
  <span m=''3698500''>So</span> <span m=''3698760''>yeah,</span> <span m=''3699000''>you''ll</span>
  <span m=''3699150''>have</span> <span m=''3699310''>a</span> <span m=''3699350''>race</span>
  <span m=''3699640''>condition</span> <span m=''3699970''>if</span> <span m=''3700040''>you</span>
  <span m=''3700090''>try</span> <span m=''3700280''>to</span> <span m=''3700650''>naively</span>
  <span m=''3701210''>parallelize</span> <span m=''3701940''>the</span> <span m=''3702600''>loop</span>
  <span m=''3702950''>here.</span> </p><p><span m=''3706570''>So</span> <span m=''3706800''>the</span>
  <span m=''3706890''>work</span> <span m=''3707210''>of</span> <span m=''3707310''>this</span>
  <span m=''3707530''>is</span> <span m=''3707680''>what?</span> <span m=''3713460''>It''s</span>
  <span m=''3713590''>order</span> <span m=''3713870''>n</span> <span m=''3714060''>cubed,</span>
  <span m=''3715100''>just</span> <span m=''3715310''>three</span> <span m=''3715520''>nested</span>
  <span m=''3715850''>loops</span> <span m=''3716410''>each</span> <span m=''3716620''>going</span>
  <span m=''3716870''>to n.</span> <span m=''3718090''>What''s</span> <span m=''3718310''>the</span>
  <span m=''3718400''>span</span> <span m=''3718830''>of</span> <span m=''3718920''>this?</span>
  <span m=''3732180''>What''s</span> <span m=''3732330''>the</span> <span m=''3732410''>span</span>
  <span m=''3732760''>of</span> <span m=''3732840''>this?</span> <span m=''3740990''>It''s</span>
  <span m=''3741240''>order</span> <span m=''3741540''>n,</span> <span m=''3742770''>because</span>
  <span m=''3743470''>it''s</span> <span m=''3743760''>log</span> <span m=''3745020''>n</span>
  <span m=''3745320''>for</span> <span m=''3745420''>this</span> <span m=''3745680''>loop,</span>
  <span m=''3746200''>log</span> <span m=''3746505''>n</span> <span m=''3746810''>for</span>
  <span m=''3746900''>this</span> <span m=''3747130''>loop,</span> <span m=''3747330''>plus</span>
  <span m=''3747700''>the</span> <span m=''3747790''>maximum</span> <span m=''3748450''>of</span>
  <span m=''3748550''>this,</span> <span m=''3748840''>well,</span> <span m=''3749130''>that''s</span>
  <span m=''3749490''>n.</span> <span m=''3750290''>Log</span> <span m=''3750590''>n</span>
  <span m=''3750750''>plus</span> <span m=''3751010''>log</span> <span m=''3751300''>n</span>
  <span m=''3751560''>plus</span> <span m=''3751910''>n</span> <span m=''3752330''>is</span>
  <span m=''3752510''>order</span> <span m=''3752810''>n.</span> <span m=''3754860''>So</span>
  <span m=''3755290''>order</span> <span m=''3755620''>n</span> <span m=''3755910''>span,</span>
  <span m=''3756730''>which</span> <span m=''3756900''>says</span> <span m=''3757130''>parallelism</span>
  <span m=''3757750''>is</span> <span m=''3759210''>order</span> <span m=''3759460''>n</span>
  <span m=''3759630''>squared.</span> <span m=''3762340''>So</span> <span m=''3762570''>for</span>
  <span m=''3762900''>1,000 by</span> <span m=''3763230''>1,000</span> <span m=''3763610''>matrices,</span>
  <span m=''3763985''>the</span> <span m=''3764360''>parallelism</span> <span m=''3764940''>is</span>
  <span m=''3765080''>on</span> <span m=''3765220''>the</span> <span m=''3765320''>order</span>
  <span m=''3765670''>of</span> <span m=''3767500''>a</span> <span m=''3767570''>million.</span>
  <span m=''3769376''>Wow.</span> <span m=''3772430''>That''s</span> <span m=''3772810''>great.</span>
  </p><p><span m=''3776050''>However,</span> <span m=''3778750''>it''s on the</span>
  <span m=''3779230''>order of a</span> <span m=''3779710''>million,</span> <span
  m=''3780010''>but</span> <span m=''3780140''>as</span> <span m=''3780270''>we</span>
  <span m=''3780370''>know,</span> <span m=''3780600''>this</span> <span m=''3780790''>doesn''t</span>
  <span m=''3781140''>use</span> <span m=''3781510''>cache</span> <span m=''3781950''>very</span>
  <span m=''3782160''>effectively.</span> <span m=''3784630''>So</span> <span m=''3784820''>one</span>
  <span m=''3784980''>of</span> <span m=''3785050''>the</span> <span m=''3785120''>nice</span>
  <span m=''3785420''>things</span> <span m=''3785680''>about</span> <span m=''3786030''>doing</span>
  <span m=''3786270''>divide and</span> <span m=''3786640''>conquer is,</span> <span
  m=''3787140''>as</span> <span m=''3787270''>you know,</span> <span m=''3787620''>that''s</span>
  <span m=''3787820''>a</span> <span m=''3787880''>really</span> <span m=''3788130''>good</span>
  <span m=''3788280''>way</span> <span m=''3788480''>to</span> <span m=''3788730''>take</span>
  <span m=''3788860''>advantage</span> <span m=''3789260''>of</span> <span m=''3789360''>caching.</span>
  <span m=''3791850''>And</span> <span m=''3792140''>this</span> <span m=''3792440''>works</span>
  <span m=''3792670''>in</span> <span m=''3792780''>parallel,</span> <span m=''3793320''>too.</span>
  <span m=''3795100''>In</span> <span m=''3795300''>particular</span> <span m=''3795830''>because</span>
  <span m=''3797020''>whenever</span> <span m=''3797510''>you</span> <span m=''3797760''>have</span>
  <span m=''3798400''>sufficient</span> <span m=''3798920''>parallelism,</span> <span
  m=''3800150''>these</span> <span m=''3800340''>processors</span> <span m=''3800920''>are</span>
  <span m=''3801010''>executing</span> <span m=''3801610''>the</span> <span m=''3801710''>code</span>
  <span m=''3803480''>just</span> <span m=''3803740''>as</span> <span m=''3803880''>if</span>
  <span m=''3804030''>they</span> <span m=''3804140''>were</span> <span m=''3804520''>executing</span>
  <span m=''3805010''>serial</span> <span m=''3805450''>code.</span> <span m=''3806160''>So</span>
  <span m=''3806290''>you</span> <span m=''3806360''>get</span> <span m=''3806540''>all</span>
  <span m=''3806860''>the</span> <span m=''3806960''>same</span> <span m=''3807290''>cache</span>
  <span m=''3807670''>locality</span> <span m=''3807970''>you</span> <span m=''3808270''>would</span>
  <span m=''3808420''>get in</span> <span m=''3808690''>the</span> <span m=''3808750''>serial</span>
  <span m=''3809170''>code</span> <span m=''3809840''>in</span> <span m=''3810040''>the</span>
  <span m=''3810130''>parallel</span> <span m=''3810610''>code,</span> <span m=''3811290''>except</span>
  <span m=''3811700''>for</span> <span m=''3811780''>the</span> <span m=''3811900''>times</span>
  <span m=''3812280''>that</span> <span m=''3812380''>you''re</span> <span m=''3812530''>actually</span>
  <span m=''3812910''>migrating</span> <span m=''3813510''>work.</span> <span m=''3814300''>And</span>
  <span m=''3814560''>if you have</span> <span m=''3814810''>sufficient</span> <span
  m=''3815190''>parallelism,</span> <span m=''3815710''>that</span> <span m=''3815900''>isn''t</span>
  <span m=''3816150''>too</span> <span m=''3816330''>often.</span> </p><p><span m=''3818590''>So</span>
  <span m=''3818750''>let''s</span> <span m=''3818920''>take</span> <span m=''3819100''>a</span>
  <span m=''3819170''>look</span> <span m=''3819400''>at</span> <span m=''3819480''>recursive</span>
  <span m=''3819960''>divide and</span> <span m=''3820380''>conquer</span> <span m=''3820740''>multiplication.</span>
  <span m=''3821890''>So</span> <span m=''3822380''>we''re</span> <span m=''3822500''>familiar</span>
  <span m=''3822900''>with</span> <span m=''3823020''>this,</span> <span m=''3823250''>too.</span>
  <span m=''3825770''>So</span> <span m=''3826580''>this</span> <span m=''3826800''>is</span>
  <span m=''3826930''>eight</span> <span m=''3827110''>multiplications</span> <span
  m=''3827760''>of</span> <span m=''3827860''>n</span> <span m=''3827980''>over</span>
  <span m=''3828190''>2</span> <span m=''3828360''>by</span> <span m=''3828520''>2</span>
  <span m=''3828720''>matrices,</span> <span m=''3829370''>and</span> <span m=''3829600''>one</span>
  <span m=''3829850''>addition</span> <span m=''3830290''>of</span> <span m=''3830400''>n</span>
  <span m=''3830610''>by</span> <span m=''3830770''>n</span> <span m=''3830950''>matrix.</span>
  <span m=''3831350''>So</span> <span m=''3831440''>here''s</span> <span m=''3831710''>a</span>
  <span m=''3831780''>code</span> <span m=''3834060''>using</span> <span m=''3834390''>a</span>
  <span m=''3834440''>little</span> <span m=''3834640''>bit</span> <span m=''3834800''>of</span>
  <span m=''3835390''>C++ism.</span> <span m=''3835970''>So</span> <span m=''3836140''>I''ve</span>
  <span m=''3836810''>made</span> <span m=''3837150''>the</span> <span m=''3837260''>type</span>
  <span m=''3839900''>a</span> <span m=''3840000''>variable</span> <span m=''3840500''>t.</span>
  <span m=''3841560''>So</span> <span m=''3841700''>we''re</span> <span m=''3841780''>going</span>
  <span m=''3841850''>to</span> <span m=''3841930''>do</span> <span m=''3842050''>matrix</span>
  <span m=''3842350''>multiplication</span> <span m=''3842770''>of</span> <span m=''3843190''>an</span>
  <span m=''3843530''>array,</span> <span m=''3843870''>a,</span> <span m=''3847710''>the</span>
  <span m=''3848070''>result</span> <span m=''3848470''>is</span> <span m=''3848560''>going</span>
  <span m=''3848660''>to</span> <span m=''3848710''>go</span> <span m=''3848870''>in</span>
  <span m=''3848970''>c,</span> <span m=''3849810''>and</span> <span m=''3849960''>we''re</span>
  <span m=''3850070''>going</span> <span m=''3850180''>to</span> <span m=''3850220''>basically</span>
  <span m=''3850780''>have</span> <span m=''3851090''>a</span> <span m=''3851370''>and</span>
  <span m=''3851590''>b,</span> <span m=''3852870''>and</span> <span m=''3853040''>we''re</span>
  <span m=''3853130''>going</span> <span m=''3853200''>to</span> <span m=''3853270''>add</span>
  <span m=''3853630''>the</span> <span m=''3853720''>result</span> <span m=''3854140''>into</span>
  <span m=''3854310''>c.</span> <span m=''3855240''>We</span> <span m=''3855370''>have</span>
  <span m=''3856010''>n,</span> <span m=''3856370''>which</span> <span m=''3856590''>is</span>
  <span m=''3856740''>the</span> <span m=''3856810''>side</span> <span m=''3857260''>of</span>
  <span m=''3857450''>the</span> <span m=''3859060''>submatrix</span> <span m=''3859740''>that</span>
  <span m=''3859850''>we''re</span> <span m=''3859950''>working</span> <span m=''3860370''>on,</span>
  <span m=''3860590''>and</span> <span m=''3860690''>we''re</span> <span m=''3860900''>also</span>
  <span m=''3861240''>going</span> <span m=''3861360''>to</span> <span m=''3861580''>have</span>
  <span m=''3861810''>an</span> <span m=''3862050''>n</span> <span m=''3862240''>size,</span>
  <span m=''3862880''>which</span> <span m=''3863080''>is</span> <span m=''3863200''>the</span>
  <span m=''3863290''>length</span> <span m=''3863620''>of</span> <span m=''3863690''>the</span>
  <span m=''3863750''>row</span> <span m=''3865080''>in</span> <span m=''3865240''>the</span>
  <span m=''3865360''>original</span> <span m=''3865750''>matrix.</span> <span m=''3866105''>So</span>
  <span m=''3866460''>remember</span> <span m=''3866700''>when</span> <span m=''3866910''>we</span>
  <span m=''3867020''>do</span> <span m=''3867160''>matrix</span> <span m=''3868120''>things,</span>
  <span m=''3868500''>if</span> <span m=''3868650''>I</span> <span m=''3868750''>take</span>
  <span m=''3869020''>a</span> <span m=''3869090''>submatrix,</span> <span m=''3869870''>it''s</span>
  <span m=''3870040''>not</span> <span m=''3870270''>contiguous</span> <span m=''3870820''>in</span>
  <span m=''3870890''>memory.</span> <span m=''3871240''>So</span> <span m=''3871700''>I</span>
  <span m=''3871810''>have</span> <span m=''3871900''>to</span> <span m=''3872010''>know</span>
  <span m=''3872230''>the</span> <span m=''3872350''>row</span> <span m=''3872740''>size</span>
  <span m=''3873310''>of</span> <span m=''3873450''>the</span> <span m=''3873540''>matrix</span>
  <span m=''3873940''>that</span> <span m=''3874240''>I''m in in</span> <span m=''3874470''>order</span>
  <span m=''3874700''>to</span> <span m=''3874750''>be</span> <span m=''3874910''>able</span>
  <span m=''3874990''>to</span> <span m=''3875080''>calculate</span> <span m=''3876170''>what</span>
  <span m=''3876360''>the</span> <span m=''3876510''>elements</span> <span m=''3876970''>are.</span>
  </p><p><span m=''3878710''>So</span> <span m=''3879450''>the</span> <span m=''3879540''>way</span>
  <span m=''3879710''>it''s</span> <span m=''3879850''>going</span> <span m=''3879960''>to</span>
  <span m=''3880020''>work</span> <span m=''3880370''>is</span> <span m=''3880540''>I''m</span>
  <span m=''3880640''>going</span> <span m=''3880720''>to</span> <span m=''3880780''>assign</span>
  <span m=''3881210''>this</span> <span m=''3881370''>temporary</span> <span m=''3881810''>d,</span>
  <span m=''3885220''>by</span> <span m=''3885340''>using the new--</span> <span m=''3886060''>which</span>
  <span m=''3886490''>is</span> <span m=''3886740''>basically</span> <span m=''3887170''>memory</span>
  <span m=''3887450''>allocation</span> <span m=''3888060''>C++--</span> <span m=''3889096''>array</span>
  <span m=''3889760''>of</span> <span m=''3889860''>size</span> <span m=''3890540''>n</span>
  <span m=''3890820''>by</span> <span m=''3891020''>n.</span> <span m=''3892410''>And</span>
  <span m=''3892950''>what</span> <span m=''3893100''>we''re</span> <span m=''3893210''>going</span>
  <span m=''3893300''>to</span> <span m=''3893400''>do</span> <span m=''3893870''>is</span>
  <span m=''3894800''>then</span> <span m=''3895710''>do</span> <span m=''3897390''>four
  of</span> <span m=''3897650''>the</span> <span m=''3897910''>recursive</span> <span
  m=''3898670''>multiplications,</span> <span m=''3899950''>these</span> <span m=''3900210''>guys</span>
  <span m=''3900510''>here,</span> <span m=''3901230''>into</span> <span m=''3903310''>the</span>
  <span m=''3903650''>elements</span> <span m=''3904160''>of</span> <span m=''3904260''>c,</span>
  <span m=''3905470''>and</span> <span m=''3905650''>then</span> <span m=''3905860''>four</span>
  <span m=''3906240''>of</span> <span m=''3906310''>them</span> <span m=''3906500''>also</span>
  <span m=''3907490''>into</span> <span m=''3907780''>d</span> <span m=''3911090''>using
  the</span> <span m=''3911530''>temporary.</span> <span m=''3912000''>And</span>
  <span m=''3912150''>then</span> <span m=''3912300''>we''re</span> <span m=''3912440''>going</span>
  <span m=''3912530''>to</span> <span m=''3912610''>sync,</span> <span m=''3913400''>after</span>
  <span m=''3913630''>we</span> <span m=''3913710''>get</span> <span m=''3913890''>all</span>
  <span m=''3914110''>that</span> <span m=''3914310''>parallel</span> <span m=''3914690''>work</span>
  <span m=''3914970''>done,</span> <span m=''3915480''>and</span> <span m=''3915630''>then</span>
  <span m=''3915740''>we''re</span> <span m=''3915910''>going</span> <span m=''3916000''>to</span>
  <span m=''3916100''>add</span> <span m=''3916610''>d</span> <span m=''3916880''>into</span>
  <span m=''3917100''>c,</span> <span m=''3918160''>and</span> <span m=''3918440''>then
  we''ll</span> <span m=''3918570''>delete</span> <span m=''3918960''>d, because</span>
  <span m=''3919400''>we</span> <span m=''3919510''>allocated</span> <span m=''3919785''>it</span>
  <span m=''3920060''>up</span> <span m=''3920230''>here.</span> <span m=''3922880''>Everybody</span>
  <span m=''3923290''>understand</span> <span m=''3923720''>the</span> <span m=''3923800''>code?</span>
  <span m=''3925920''>So</span> <span m=''3926020''>we''re</span> <span m=''3926120''>doing</span>
  <span m=''3926380''>this,</span> <span m=''3926590''>it''s</span> <span m=''3926700''>just
  we''re</span> <span m=''3927080''>going</span> <span m=''3927240''>to</span> <span
  m=''3927300''>do</span> <span m=''3927440''>it</span> <span m=''3927510''>in</span>
  <span m=''3927600''>parallel.</span> <span m=''3930490''>Good?</span> <span m=''3931520''>Questions?</span>
  <span m=''3933620''>OK.</span> </p><p><span m=''3936260''>So</span> <span m=''3936350''>this</span>
  <span m=''3936530''>is</span> <span m=''3936660''>the</span> <span m=''3936760''>row</span>
  <span m=''3937070''>length</span> <span m=''3937340''>of</span> <span m=''3937420''>the</span>
  <span m=''3937510''>matrices</span> <span m=''3938130''>so that</span> <span m=''3938240''>I</span>
  <span m=''3938310''>can</span> <span m=''3938470''>do</span> <span m=''3938680''>the</span>
  <span m=''3939300''>base</span> <span m=''3939700''>cases,</span> <span m=''3940010''>and</span>
  <span m=''3940320''>in particular,</span> <span m=''3941060''>partition</span> <span
  m=''3941520''>the</span> <span m=''3941590''>matrices</span> <span m=''3942680''>effectively.</span>
  <span m=''3943350''>I</span> <span m=''3943460''>haven''t</span> <span m=''3943720''>shown</span>
  <span m=''3943980''>that</span> <span m=''3944190''>code.</span> <span m=''3945720''>And</span>
  <span m=''3945960''>of</span> <span m=''3946030''>course,</span> <span m=''3946310''>the</span>
  <span m=''3946720''>base</span> <span m=''3947020''>case,</span> <span m=''3947270''>normally,
  we</span> <span m=''3947600''>would</span> <span m=''3947740''>want</span> <span
  m=''3947920''>to</span> <span m=''3947980''>coarsen</span> <span m=''3948420''>for</span>
  <span m=''3948570''>efficiency.</span> <span m=''3949560''>I would</span> <span
  m=''3949680''>want</span> <span m=''3949860''>to</span> <span m=''3949910''>go</span>
  <span m=''3950080''>down</span> <span m=''3950390''>to</span> <span m=''3950470''>something</span>
  <span m=''3950900''>like</span> <span m=''3951120''>maybe</span> <span m=''3951570''>a</span>
  <span m=''3951930''>eight</span> <span m=''3952390''>by</span> <span m=''3952570''>eight</span>
  <span m=''3952910''>or</span> <span m=''3952980''>16</span> <span m=''3953410''>by</span>
  <span m=''3953540''>16</span> <span m=''3954040''>matrix,</span> <span m=''3954480''>and</span>
  <span m=''3954560''>at</span> <span m=''3954650''>that</span> <span m=''3954890''>point</span>
  <span m=''3955130''>switch</span> <span m=''3955540''>to</span> <span m=''3957090''>something</span>
  <span m=''3957390''>that''s</span> <span m=''3957530''>going</span> <span m=''3957630''>to</span>
  <span m=''3957680''>use</span> <span m=''3957930''>the</span> <span m=''3958000''>processor</span>
  <span m=''3958500''>pipeline</span> <span m=''3959500''>better.</span> <span m=''3961880''>The</span>
  <span m=''3962060''>base</span> <span m=''3962420''>cases,</span> <span m=''3962860''>once</span>
  <span m=''3963070''>again,</span> <span m=''3963220''>I</span> <span m=''3963280''>want</span>
  <span m=''3963420''>to</span> <span m=''3963540''>emphasize</span> <span m=''3964040''>this</span>
  <span m=''3964240''>because</span> <span m=''3964360''>a</span> <span m=''3964430''>couple</span>
  <span m=''3964720''>people</span> <span m=''3964990''>on</span> <span m=''3965080''>the</span>
  <span m=''3965180''>quiz</span> <span m=''3966120''>misunderstood</span> <span m=''3966870''>this.</span>
  <span m=''3967430''>The</span> <span m=''3967540''>reason</span> <span m=''3967820''>you</span>
  <span m=''3968010''>coarsen</span> <span m=''3968510''>has</span> <span m=''3968640''>nothing</span>
  <span m=''3968960''>to</span> <span m=''3969030''>do</span> <span m=''3969150''>with</span>
  <span m=''3969290''>caches.</span> <span m=''3971250''>The</span> <span m=''3971310''>reason</span>
  <span m=''3971550''>you</span> <span m=''3971670''>coarsen</span> <span m=''3972430''>is</span>
  <span m=''3972570''>to</span> <span m=''3972670''>overcome</span> <span m=''3973130''>the</span>
  <span m=''3973250''>overhead</span> <span m=''3973990''>of</span> <span m=''3974250''>the</span>
  <span m=''3974410''>function</span> <span m=''3974860''>calls,</span> <span m=''3976310''>and</span>
  <span m=''3976450''>the</span> <span m=''3976530''>coarsening</span> <span m=''3977130''>is</span>
  <span m=''3977280''>generally</span> <span m=''3977610''>chosen</span> <span m=''3978440''>independent</span>
  <span m=''3979370''>of</span> <span m=''3979520''>what</span> <span m=''3979670''>the</span>
  <span m=''3979750''>size</span> <span m=''3980130''>of</span> <span m=''3980190''>the</span>
  <span m=''3980270''>caches</span> <span m=''3980790''>are.</span> <span m=''3981280''>It''s</span>
  <span m=''3981460''>not</span> <span m=''3981730''>a</span> <span m=''3982480''>parameter</span>
  <span m=''3983500''>that</span> <span m=''3984000''>has</span> <span m=''3984210''>to</span>
  <span m=''3984290''>be</span> <span m=''3984430''>tuned</span> <span m=''3984810''>to</span>
  <span m=''3984930''>cache</span> <span m=''3985250''>size.</span> <span m=''3985590''>It''s</span>
  <span m=''3985750''>a</span> <span m=''3985810''>parameter</span> <span m=''3986540''>that
  has</span> <span m=''3986910''>to be tuned</span> <span m=''3987130''>to</span>
  <span m=''3987350''>function</span> <span m=''3987830''>call,</span> <span m=''3988190''>versus</span>
  <span m=''3988560''>ALU</span> <span m=''3989100''>instructions,</span> <span m=''3990150''>and</span>
  <span m=''3990240''>what</span> <span m=''3990450''>that</span> <span m=''3990670''>balance</span>
  <span m=''3991040''>is.</span> <span m=''3993080''>Question?</span> </p><p><span
  m=''3994464''>AUDIENCE: I mean,</span> <span m=''3994961''>I understand</span> <span
  m=''3995458''>that''s</span> <span m=''3995955''>true,</span> <span m=''3996452''>but</span>
  <span m=''3996949''>I thought--</span> <span m=''3997446''>I mean,</span> <span
  m=''3997943''>maybe I</span> <span m=''3998440''>[? heard the call ?]</span> <span
  m=''3998937''>wrong,</span> <span m=''3999434''>but</span> <span m=''3999931''>I
  thought we</span> <span m=''4000428''>wanted,</span> <span m=''4000925''>in general,</span>
  <span m=''4001422''>in terms of</span> <span m=''4001919''>caching,</span> <span
  m=''4002416''>that</span> <span m=''4002913''>you would</span> <span m=''4003410''>choose
  it</span> <span m=''4003907''>somehow</span> <span m=''4004404''>so that</span>
  <span m=''4004901''>all</span> <span m=''4005398''>of the</span> <span m=''4005895''>data</span>
  <span m=''4006392''>that you</span> <span m=''4006889''>have would</span> <span
  m=''4007386''>somehow fit--</span> </p><p><span m=''4008380''>CHARLES LEISERSON:
  That''s what the</span> <span m=''4008900''>divide</span> <span m=''4009220''>and</span>
  <span m=''4009300''>conquer</span> <span m=''4009680''>does</span> <span m=''4010060''>automatically.</span>
  <span m=''4012210''>The</span> <span m=''4012290''>divide and</span> <span m=''4012610''>conquer</span>
  <span m=''4013010''>keeps</span> <span m=''4013240''>halving it</span> <span m=''4013660''>until</span>
  <span m=''4013990''>it</span> <span m=''4014100''>fits</span> <span m=''4014380''>in</span>
  <span m=''4014550''>whatever</span> <span m=''4014880''>size</span> <span m=''4015220''>cache</span>
  <span m=''4015590''>you</span> <span m=''4015840''>have.</span> <span m=''4016450''>And</span>
  <span m=''4016630''>in</span> <span m=''4016710''>fact,</span> <span m=''4017110''>we</span>
  <span m=''4017240''>have</span> <span m=''4017360''>three</span> <span m=''4017650''>caches</span>
  <span m=''4018140''>on</span> <span m=''4018260''>the</span> <span m=''4018330''>machines</span>
  <span m=''4018710''>we''re</span> <span m=''4018870''>using.</span> </p><p><span
  m=''4019770''>AUDIENCE: Yeah,</span> <span m=''4020260''>but I''m</span> <span m=''4020750''>saying</span>
  <span m=''4021240''>if</span> <span m=''4021730''>your</span> <span m=''4022220''>coarsened</span>
  <span m=''4022710''>constant</span> <span m=''4023200''>is too big,</span> <span
  m=''4023690''>that''s</span> <span m=''4024180''>not going to</span> <span m=''4024670''>happen.</span>
  </p><p><span m=''4025160''>CHARLES LEISERSON: If</span> <span m=''4025650''>the
  coarsened</span> <span m=''4026140''>constant</span> <span m=''4026540''>is</span>
  <span m=''4026660''>too</span> <span m=''4026810''>big,</span> <span m=''4027030''>that''s</span>
  <span m=''4027400''>not</span> <span m=''4027580''>going</span> <span m=''4027680''>to</span>
  <span m=''4027720''>happen.</span> <span m=''4028180''>But</span> <span m=''4028380''>generally,</span>
  <span m=''4028750''>the</span> <span m=''4028860''>caches</span> <span m=''4029450''>are</span>
  <span m=''4029520''>much</span> <span m=''4029760''>bigger</span> <span m=''4030970''>than</span>
  <span m=''4031700''>what</span> <span m=''4031850''>you</span> <span m=''4031930''>need</span>
  <span m=''4032120''>to</span> <span m=''4032210''>do</span> <span m=''4032390''>to</span>
  <span m=''4032470''>amortize</span> <span m=''4033310''>the</span> <span m=''4034030''>cost.</span>
  <span m=''4034410''>But</span> <span m=''4034500''>you''re</span> <span m=''4034630''>right,</span>
  <span m=''4034840''>that</span> <span m=''4035000''>is</span> <span m=''4035150''>an</span>
  <span m=''4035190''>assumption.</span> <span m=''4036660''>The</span> <span m=''4036770''>caches</span>
  <span m=''4037260''>are</span> <span m=''4037310''>generally</span> <span m=''4037650''>much</span>
  <span m=''4037940''>bigger</span> <span m=''4038660''>than</span> <span m=''4038790''>the</span>
  <span m=''4038870''>size</span> <span m=''4039270''>that</span> <span m=''4039390''>you</span>
  <span m=''4039490''>need</span> <span m=''4039750''>in</span> <span m=''4039850''>order</span>
  <span m=''4040110''>to</span> <span m=''4040270''>overcome</span> <span m=''4040690''>function</span>
  <span m=''4041060''>call</span> <span m=''4041320''>overhead.</span> <span m=''4041680''>Function</span>
  <span m=''4041980''>call overhead</span> <span m=''4042210''>is</span> <span m=''4042560''>not</span>
  <span m=''4042820''>that</span> <span m=''4043050''>high.</span> <span m=''4044170''>OK?</span>
  <span m=''4044930''>Good.</span> <span m=''4047020''>I''m</span> <span m=''4047160''>glad</span>
  <span m=''4047790''>I</span> <span m=''4048050''>raised</span> <span m=''4048330''>that</span>
  <span m=''4048470''>issue</span> <span m=''4048670''>again.</span> <span m=''4049280''>And</span>
  <span m=''4049510''>so</span> <span m=''4049650''>we''re</span> <span m=''4049740''>going</span>
  <span m=''4049820''>to</span> <span m=''4049910''>determine</span> <span m=''4050220''>the</span>
  <span m=''4050530''>submatrices</span> <span m=''4051320''>by</span> <span m=''4051690''>index</span>
  <span m=''4051910''>calculation.</span> <span m=''4053330''>And</span> <span m=''4053490''>then</span>
  <span m=''4053680''>we</span> <span m=''4053800''>have</span> <span m=''4053980''>to</span>
  <span m=''4054060''>implement</span> <span m=''4054620''>this</span> <span m=''4055130''>parallel</span>
  <span m=''4055660''>add,</span> <span m=''4056130''>and</span> <span m=''4056250''>that</span>
  <span m=''4056400''>I''m</span> <span m=''4056490''>going</span> <span m=''4056570''>to</span>
  <span m=''4056650''>do</span> <span m=''4056820''>just</span> <span m=''4057040''>with</span>
  <span m=''4057120''>a</span> <span m=''4057220''>doubly</span> <span m=''4057550''>nested</span>
  <span m=''4057920''>for</span> <span m=''4058190''>loop</span> <span m=''4061270''>to</span>
  <span m=''4062030''>add</span> <span m=''4062270''>the</span> <span m=''4062340''>things.</span>
  <span m=''4065530''>There''s</span> <span m=''4065730''>no</span> <span m=''4066110''>cache</span>
  <span m=''4066830''>behavior</span> <span m=''4067370''>I</span> <span m=''4067430''>can</span>
  <span m=''4067600''>really</span> <span m=''4067850''>take</span> <span m=''4068090''>advantage</span>
  <span m=''4068570''>of</span> <span m=''4068650''>here</span> <span m=''4068840''>except</span>
  <span m=''4069250''>for</span> <span m=''4069740''>spatial</span> <span m=''4070330''>locality.</span>
  <span m=''4071750''>There''s</span> <span m=''4071910''>no</span> <span m=''4072070''>temporal</span>
  <span m=''4072510''>locality</span> <span m=''4072870''>because</span> <span m=''4073030''>I''m</span>
  <span m=''4073110''>just</span> <span m=''4073290''>adding</span> <span m=''4073590''>two</span>
  <span m=''4073760''>matrices</span> <span m=''4074580''>once,</span> <span m=''4075860''>so</span>
  <span m=''4076030''>there''s</span> <span m=''4076230''>no</span> <span m=''4076500''>real</span>
  <span m=''4078430''>temporal</span> <span m=''4078760''>locality</span> <span m=''4079015''>that</span>
  <span m=''4079270''>I''ll</span> <span m=''4079440''>get</span> <span m=''4079600''>out</span>
  <span m=''4079720''>of</span> <span m=''4079840''>it.</span> <span m=''4080726''>And</span>
  <span m=''4081170''>here,</span> <span m=''4081450''>I''ve</span> <span m=''4081560''>actually</span>
  <span m=''4081830''>done</span> <span m=''4082020''>the</span> <span m=''4082120''>index</span>
  <span m=''4082440''>calculations</span> <span m=''4083190''>by</span> <span m=''4083340''>hand.</span>
  </p><p><span m=''4088550''>So</span> <span m=''4088730''>let''s</span> <span m=''4089090''>analyze</span>
  <span m=''4089740''>this.</span> <span m=''4091050''>So</span> <span m=''4091210''>to</span>
  <span m=''4091270''>analyze</span> <span m=''4091780''>the</span> <span m=''4091910''>multiplication</span>
  <span m=''4093080''>program,</span> <span m=''4093540''>I</span> <span m=''4093630''>have</span>
  <span m=''4093790''>to</span> <span m=''4093890''>start</span> <span m=''4094210''>by</span>
  <span m=''4094340''>analyzing</span> <span m=''4094970''>the</span> <span m=''4095100''>addition</span>
  <span m=''4095460''>program.</span> <span m=''4096590''>So</span> <span m=''4096800''>this</span>
  <span m=''4096939''>should</span> <span m=''4097120''>be,</span> <span m=''4097939''>I</span>
  <span m=''4098050''>think,</span> <span m=''4098540''>fairly</span> <span m=''4099210''>straightforward.</span>
  <span m=''4099890''>What''s the</span> <span m=''4100080''>work</span> <span m=''4101620''>for</span>
  <span m=''4102149''>adding</span> <span m=''4102550''>two</span> <span m=''4102800''>n</span>
  <span m=''4102960''>by</span> <span m=''4103130''>n</span> <span m=''4103319''>matrices</span>
  <span m=''4103899''>here?</span> <span m=''4106290''>n</span> <span m=''4106540''>squared,</span>
  <span m=''4106979''>good,</span> <span m=''4108109''>just</span> <span m=''4108370''>doubly</span>
  <span m=''4108660''>nested</span> <span m=''4109020''>loop.</span> <span m=''4109689''>What''s</span>
  <span m=''4109859''>the</span> <span m=''4110029''>span?</span> </p><p><span m=''4112612''>AUDIENCE:
  [INAUDIBLE].</span> </p><p><span m=''4115609''>CHARLES LEISERSON: Yeah,</span> <span
  m=''4115850''>here it''s</span> <span m=''4116210''>log</span> <span m=''4116540''>n,</span>
  <span m=''4116960''>very</span> <span m=''4117170''>good.</span> <span m=''4117859''>Because</span>
  <span m=''4118050''>I''ve</span> <span m=''4118120''>got</span> <span m=''4118450''>log</span>
  <span m=''4118790''>n</span> <span m=''4118930''>plus</span> <span m=''4119200''>log</span>
  <span m=''4119490''>n</span> <span m=''4119680''>plus</span> <span m=''4120180''>order</span>
  <span m=''4120420''>one.</span> <span m=''4124600''>I''m</span> <span m=''4124740''>not</span>
  <span m=''4124899''>going</span> <span m=''4125000''>to</span> <span m=''4125040''>analyze</span>
  <span m=''4125490''>the</span> <span m=''4125569''>parallelism,</span> <span m=''4126060''>because</span>
  <span m=''4126240''>I</span> <span m=''4126310''>really</span> <span m=''4126470''>don''t</span>
  <span m=''4126640''>care</span> <span m=''4126830''>about</span> <span m=''4127029''>the</span>
  <span m=''4127090''>parallelism</span> <span m=''4127620''>of</span> <span m=''4127710''>the</span>
  <span m=''4127859''>addition.</span> <span m=''4128260''>I</span> <span m=''4128340''>really</span>
  <span m=''4128590''>care</span> <span m=''4128810''>about</span> <span m=''4129370''>the</span>
  <span m=''4129460''>parallelism</span> <span m=''4129970''>of</span> <span m=''4130180''>the</span>
  <span m=''4130810''>matrix</span> <span m=''4131180''>multiplication.</span> <span
  m=''4131859''>But</span> <span m=''4132100''>we''ll</span> <span m=''4132319''>plug</span>
  <span m=''4132590''>those</span> <span m=''4132830''>values</span> <span m=''4133229''>in</span>
  <span m=''4133410''>now.</span> <span m=''4134859''>What</span> <span m=''4135130''>is</span>
  <span m=''4135350''>the</span> <span m=''4135529''>work</span> <span m=''4135970''>of</span>
  <span m=''4136140''>the</span> <span m=''4136229''>matrix</span> <span m=''4136590''>multiplication?</span>
  <span m=''4137430''>Well</span> <span m=''4137620''>for</span> <span m=''4137729''>this,</span>
  <span m=''4139330''>what</span> <span m=''4139580''>we</span> <span m=''4139670''>want</span>
  <span m=''4139880''>to</span> <span m=''4139950''>do</span> <span m=''4140160''>is</span>
  <span m=''4140290''>get</span> <span m=''4140470''>a</span> <span m=''4140500''>recurrence</span>
  <span m=''4141540''>that</span> <span m=''4142210''>we</span> <span m=''4142359''>can</span>
  <span m=''4142510''>then</span> <span m=''4142710''>solve.</span> <span m=''4143140''>So</span>
  <span m=''4143240''>what''s</span> <span m=''4143380''>the</span> <span m=''4143520''>recurrence</span>
  <span m=''4144069''>that</span> <span m=''4144170''>we</span> <span m=''4144290''>want</span>
  <span m=''4144490''>to</span> <span m=''4144529''>get</span> <span m=''4144920''>for</span>
  <span m=''4145880''>m of</span> <span m=''4146050''>1 of</span> <span m=''4146120''>n?</span>
  <span m=''4151050''>Yeah,</span> <span m=''4151310''>it''s going to be</span> <span
  m=''4151550''>8m</span> <span m=''4153609''>sub 1</span> <span m=''4153830''>of</span>
  <span m=''4154180''>n</span> <span m=''4154450''>over</span> <span m=''4154710''>2,</span>
  <span m=''4157180''>that</span> <span m=''4157439''>corresponds</span> <span m=''4157890''>to</span>
  <span m=''4157970''>these</span> <span m=''4158140''>things,</span> <span m=''4158479''>plus</span>
  <span m=''4159770''>some</span> <span m=''4159960''>constant</span> <span m=''4160510''>stuff,</span>
  <span m=''4161160''>plus</span> <span m=''4162399''>the</span> <span m=''4162510''>work</span>
  <span m=''4162830''>of</span> <span m=''4162930''>the</span> <span m=''4163069''>addition.</span>
  <span m=''4166300''>Does</span> <span m=''4166800''>that</span> <span m=''4166950''>make</span>
  <span m=''4167140''>sense?</span> </p><p><span m=''4168040''>We</span> <span m=''4168260''>analyze</span>
  <span m=''4168680''>the</span> <span m=''4168760''>work</span> <span m=''4168960''>of</span>
  <span m=''4169010''>the</span> <span m=''4169109''>addition.</span> <span m=''4169390''>What''s</span>
  <span m=''4169550''>the</span> <span m=''4169620''>work</span> <span m=''4169830''>of</span>
  <span m=''4169899''>the</span> <span m=''4169990''>addition?</span> <span m=''4172000''>Order</span>
  <span m=''4172229''>n</span> <span m=''4172439''>squared.</span> <span m=''4173630''>So</span>
  <span m=''4173810''>that''s</span> <span m=''4174330''>going</span> <span m=''4174460''>to</span>
  <span m=''4174529''>dominate</span> <span m=''4175060''>that</span> <span m=''4175630''>constant</span>
  <span m=''4176100''>there,</span> <span m=''4176319''>so</span> <span m=''4176439''>we</span>
  <span m=''4176529''>get</span> <span m=''4177090''>8.</span> <span m=''4178569''>And</span>
  <span m=''4178750''>what''s</span> <span m=''4178979''>the</span> <span m=''4179069''>solution</span>
  <span m=''4179500''>to</span> <span m=''4179560''>this?</span> <span m=''4181090''>Back</span>
  <span m=''4181370''>to</span> <span m=''4182500''>Master Theorem.</span> <span m=''4183319''>Now</span>
  <span m=''4183500''>we''re</span> <span m=''4183580''>going</span> <span m=''4183660''>to</span>
  <span m=''4183700''>start</span> <span m=''4184029''>pulling</span> <span m=''4184290''>out</span>
  <span m=''4184399''>the</span> <span m=''4184479''>Master</span> <span m=''4184840''>Theorem</span>
  <span m=''4186210''>multiple</span> <span m=''4186609''>times</span> <span m=''4187000''>per</span>
  <span m=''4187149''>slide</span> <span m=''4187569''>for</span> <span m=''4187660''>the</span>
  <span m=''4187740''>rest</span> <span m=''4187939''>of</span> <span m=''4187979''>the</span>
  <span m=''4188060''>lecture.</span> <span m=''4189850''>n</span> <span m=''4190380''>cubed,</span>
  <span m=''4190850''>because</span> <span m=''4191220''>we</span> <span m=''4191319''>have</span>
  <span m=''4191430''>log</span> <span m=''4191750''>base</span> <span m=''4192060''>2</span>
  <span m=''4192290''>of</span> <span m=''4192359''>8.</span> <span m=''4192700''>That''s</span>
  <span m=''4192910''>n</span> <span m=''4193149''>cubed</span> <span m=''4194840''>compared</span>
  <span m=''4195210''>with</span> <span m=''4195340''>n</span> <span m=''4195490''>squared.</span>
  <span m=''4197330''>So</span> <span m=''4197740''>we</span> <span m=''4197970''>get</span>
  <span m=''4198430''>a</span> <span m=''4198680''>solution</span> <span m=''4199140''>which</span>
  <span m=''4199340''>is</span> <span m=''4199460''>n</span> <span m=''4199680''>cubed--</span>
  <span m=''4200450''>Case 3</span> <span m=''4200750''>of the</span> <span m=''4200940''>Master</span>
  <span m=''4201350''>Theorem.</span> <span m=''4202390''>So</span> <span m=''4202670''>that''s</span>
  <span m=''4202990''>good.</span> <span m=''4203670''>The</span> <span m=''4203760''>work</span>
  <span m=''4204030''>we''re</span> <span m=''4204150''>doing</span> <span m=''4204440''>is</span>
  <span m=''4204570''>the</span> <span m=''4204650''>same</span> <span m=''4205010''>asymptotic</span>
  <span m=''4205660''>work</span> <span m=''4206010''>we''re</span> <span m=''4206140''>doing</span>
  <span m=''4206810''>for</span> <span m=''4206930''>the</span> <span m=''4207030''>triply</span>
  <span m=''4207360''>nested</span> <span m=''4207700''>loop.</span> </p><p><span
  m=''4209220''>Now</span> <span m=''4209440''>let''s</span> <span m=''4209660''>take</span>
  <span m=''4209870''>a</span> <span m=''4209940''>look</span> <span m=''4210210''>at</span>
  <span m=''4211000''>the</span> <span m=''4211100''>span.</span> <span m=''4214170''>So</span>
  <span m=''4214300''>what''s</span> <span m=''4214480''>the</span> <span m=''4214660''>span</span>
  <span m=''4215240''>for</span> <span m=''4215380''>this?</span> <span m=''4221030''>So</span>
  <span m=''4221170''>once</span> <span m=''4221380''>again,</span> <span m=''4221600''>we</span>
  <span m=''4221670''>want</span> <span m=''4221900''>a</span> <span m=''4221940''>recurrence.</span>
  <span m=''4223420''>What''s</span> <span m=''4223580''>the</span> <span m=''4223740''>recurrence</span>
  <span m=''4224190''>look</span> <span m=''4224400''>like?</span> <span m=''4231930''>So</span>
  <span m=''4232080''>the</span> <span m=''4232150''>span</span> <span m=''4232560''>of</span>
  <span m=''4232680''>this</span> <span m=''4232950''>is</span> <span m=''4233090''>going</span>
  <span m=''4233230''>to</span> <span m=''4233280''>be</span> <span m=''4233440''>the</span>
  <span m=''4233560''>span</span> <span m=''4233845''>of--</span> <span m=''4235444''>it''s</span>
  <span m=''4235882''>going</span> <span m=''4236320''>to be the sum</span> <span
  m=''4236760''>of</span> <span m=''4236850''>some</span> <span m=''4237050''>things.</span>
  <span m=''4239990''>But</span> <span m=''4240160''>the</span> <span m=''4240250''>key</span>
  <span m=''4240560''>observation</span> <span m=''4241400''>is</span> <span m=''4242960''>that</span>
  <span m=''4243070''>it''s</span> <span m=''4243250''>going</span> <span m=''4243350''>to</span>
  <span m=''4243460''>be--</span> <span m=''4243790''>we</span> <span m=''4243950''>want</span>
  <span m=''4244190''>the</span> <span m=''4244270''>maximum</span> <span m=''4244930''>of</span>
  <span m=''4245110''>these</span> <span m=''4245300''>guys.</span> <span m=''4252970''>So</span>
  <span m=''4253210''>we''re</span> <span m=''4253340''>going</span> <span m=''4253470''>to</span>
  <span m=''4253520''>basically</span> <span m=''4254020''>have</span> <span m=''4254735''>the</span>
  <span m=''4255050''>allocation</span> <span m=''4255450''>as</span> <span m=''4255850''>constant</span>
  <span m=''4256290''>time,</span> <span m=''4257250''>we</span> <span m=''4257360''>have</span>
  <span m=''4257480''>the</span> <span m=''4257560''>maximum</span> <span m=''4258110''>of</span>
  <span m=''4258250''>these,</span> <span m=''4259940''>which</span> <span m=''4260230''>is</span>
  <span m=''4260720''>m</span> <span m=''4260900''>of</span> <span m=''4261640''>infinity</span>
  <span m=''4262260''>of</span> <span m=''4262520''>n</span> <span m=''4262700''>over</span>
  <span m=''4262950''>2,</span> <span m=''4263360''>and</span> <span m=''4263530''>then</span>
  <span m=''4263680''>we</span> <span m=''4263780''>have</span> <span m=''4263900''>the</span>
  <span m=''4263990''>span</span> <span m=''4264570''>of</span> <span m=''4264860''>the</span>
  <span m=''4265010''>add.</span> <span m=''4267160''>So</span> <span m=''4267390''>we</span>
  <span m=''4267490''>get</span> <span m=''4267680''>this</span> <span m=''4268120''>recurrence.</span>
  <span m=''4270060''>m</span> <span m=''4270370''>infinity</span> <span m=''4270900''>sub</span>
  <span m=''4271100''>n</span> <span m=''4271310''>over</span> <span m=''4271530''>2,</span>
  <span m=''4271860''>because</span> <span m=''4272010''>we</span> <span m=''4272130''>have</span>
  <span m=''4272250''>only</span> <span m=''4272510''>to</span> <span m=''4272630''>worry</span>
  <span m=''4272930''>about</span> <span m=''4273220''>the</span> <span m=''4273310''>worst</span>
  <span m=''4273760''>of</span> <span m=''4273850''>these</span> <span m=''4274100''>guys.</span>
  <span m=''4275740''>The</span> <span m=''4275900''>worst</span> <span m=''4276190''>of</span>
  <span m=''4276280''>them</span> <span m=''4276470''>is--</span> <span m=''4277400''>they''re</span>
  <span m=''4277540''>all</span> <span m=''4277650''>symmetric,</span> <span m=''4278170''>so</span>
  <span m=''4278260''>it''s</span> <span m=''4278410''>basically</span> <span m=''4278760''>the</span>
  <span m=''4278820''>same.</span> <span m=''4279620''>We</span> <span m=''4279750''>have</span>
  <span m=''4279950''>a</span> <span m=''4280200''>of n,</span> <span m=''4280520''>and</span>
  <span m=''4280690''>then</span> <span m=''4280830''>there''s</span> <span m=''4281030''>a</span>
  <span m=''4281100''>constant</span> <span m=''4281440''>amount</span> <span m=''4281700''>of</span>
  <span m=''4281800''>other</span> <span m=''4282020''>overhead</span> <span m=''4282410''>here.</span>
  <span m=''4284290''>Any</span> <span m=''4284470''>questions</span> <span m=''4284900''>about</span>
  <span m=''4285070''>where</span> <span m=''4285220''>I</span> <span m=''4285310''>pulled</span>
  <span m=''4285750''>that</span> <span m=''4285950''>out</span> <span m=''4286110''>of,</span>
  <span m=''4287830''>why</span> <span m=''4288040''>that''s</span> <span m=''4288320''>the</span>
  <span m=''4288400''>recurrence?</span> </p><p><span m=''4292710''>So</span> <span
  m=''4292850''>this</span> <span m=''4293010''>is</span> <span m=''4293110''>the</span>
  <span m=''4293250''>addition,</span> <span m=''4294220''>the</span> <span m=''4294290''>span</span>
  <span m=''4294660''>of</span> <span m=''4294740''>the</span> <span m=''4294850''>addition</span>
  <span m=''4296100''>of</span> <span m=''4296190''>this</span> <span m=''4296390''>guy</span>
  <span m=''4296590''>that</span> <span m=''4296730''>we</span> <span m=''4296860''>analyzed</span>
  <span m=''4297280''>already.</span> <span m=''4297570''>What</span> <span m=''4297760''>is</span>
  <span m=''4297950''>the</span> <span m=''4298030''>span</span> <span m=''4298350''>of</span>
  <span m=''4298430''>the</span> <span m=''4298540''>addition?</span> <span m=''4301000''>What
  did</span> <span m=''4301240''>we</span> <span m=''4301350''>decide</span> <span
  m=''4301700''>that</span> <span m=''4301870''>was?</span> <span m=''4302900''>log
  n.</span> <span m=''4304530''>So</span> <span m=''4304760''>basically,</span> <span
  m=''4305290''>that</span> <span m=''4305520''>dominates</span> <span m=''4306050''>the</span>
  <span m=''4306170''>order</span> <span m=''4306540''>one.</span> <span m=''4306730''>So</span>
  <span m=''4306860''>we</span> <span m=''4306950''>get</span> <span m=''4307130''>this</span>
  <span m=''4307350''>term,</span> <span m=''4307940''>and</span> <span m=''4308000''>what''s</span>
  <span m=''4308190''>the</span> <span m=''4308270''>solution</span> <span m=''4308710''>of</span>
  <span m=''4308780''>this</span> <span m=''4308920''>recurrence?</span> </p><p><span
  m=''4309530''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''4314270''>CHARLES LEISERSON:
  What</span> <span m=''4314450''>case is</span> <span m=''4314900''>this?</span>
  </p><p><span m=''4315727''>AUDIENCE: [INAUDIBLE]</span> <span m=''4317515''>log
  n</span> <span m=''4317962''>squared.</span> </p><p><span m=''4318860''>CHARLES
  LEISERSON: Yes,</span> <span m=''4319210''>it''s</span> <span m=''4319480''>log</span>
  <span m=''4319740''>squared</span> <span m=''4320130''>n.</span> <span m=''4322500''>So</span>
  <span m=''4322660''>basically,</span> <span m=''4323230''>it''s</span> <span m=''4323400''>case</span>
  <span m=''4323780''>two.</span> <span m=''4324530''>So</span> <span m=''4324700''>if</span>
  <span m=''4324780''>I</span> <span m=''4324870''>do</span> <span m=''4325030''>n
  to</span> <span m=''4325290''>the</span> <span m=''4325440''>log</span> <span m=''4325780''>base</span>
  <span m=''4326150''>b</span> <span m=''4326340''>of</span> <span m=''4326440''>a,</span>
  <span m=''4326780''>that''s</span> <span m=''4327020''>n to the</span> <span m=''4327280''>log</span>
  <span m=''4327590''>base</span> <span m=''4327880''>2</span> <span m=''4328080''>of</span>
  <span m=''4328200''>1,</span> <span m=''4329610''>that''s</span> <span m=''4329820''>just</span>
  <span m=''4330020''>1.</span> <span m=''4332330''>And</span> <span m=''4332440''>so</span>
  <span m=''4332580''>this</span> <span m=''4332830''>is</span> <span m=''4333000''>basically</span>
  <span m=''4334090''>a</span> <span m=''4334210''>logarithmic</span> <span m=''4334920''>factor</span>
  <span m=''4335380''>times</span> <span m=''4335810''>the</span> <span m=''4335900''>1,</span>
  <span m=''4336670''>so</span> <span m=''4337180''>we</span> <span m=''4337250''>add</span>
  <span m=''4337490''>an</span> <span m=''4337590''>extra</span> <span m=''4337890''>log.</span>
  <span m=''4338250''>We</span> <span m=''4338350''>get</span> <span m=''4338500''>log</span>
  <span m=''4338760''>squared</span> <span m=''4339100''>n.</span> <span m=''4342330''>That''s</span>
  <span m=''4342570''>just</span> <span m=''4342770''>Master</span> <span m=''4343140''>Theorem</span>
  <span m=''4343470''>plugging</span> <span m=''4343850''>in.</span> </p><p><span
  m=''4344300''>So</span> <span m=''4344480''>here,</span> <span m=''4344690''>the</span>
  <span m=''4344820''>span</span> <span m=''4345300''>is</span> <span m=''4345440''>order</span>
  <span m=''4345660''>log</span> <span m=''4345960''>squared</span> <span m=''4346410''>n.</span>
  <span m=''4349370''>And</span> <span m=''4349580''>so</span> <span m=''4349800''>we</span>
  <span m=''4349970''>have</span> <span m=''4350160''>the</span> <span m=''4350260''>work</span>
  <span m=''4350600''>of</span> <span m=''4350710''>n</span> <span m=''4350920''>cubed,</span>
  <span m=''4351400''>the</span> <span m=''4351480''>span</span> <span m=''4351910''>of</span>
  <span m=''4353040''>log</span> <span m=''4353370''>squared</span> <span m=''4353840''>n,</span>
  <span m=''4354300''>so</span> <span m=''4354440''>the</span> <span m=''4354520''>parallelism</span>
  <span m=''4355170''>is</span> <span m=''4355290''>the</span> <span m=''4355400''>ratio,</span>
  <span m=''4355900''>which</span> <span m=''4356120''>is</span> <span m=''4356250''>n</span>
  <span m=''4356530''>cubed</span> <span m=''4356940''>over</span> <span m=''4357150''>log</span>
  <span m=''4357450''>squared</span> <span m=''4357850''>n.</span> <span m=''4360810''>Not</span>
  <span m=''4361010''>too</span> <span m=''4361110''>bad</span> <span m=''4361420''>for
  a</span> <span m=''4361540''>1,000</span> <span m=''4361940''>by</span> <span m=''4362080''>1,000</span>
  <span m=''4362470''>matrices,</span> <span m=''4362810''>the</span> <span m=''4363150''>parallelism</span>
  <span m=''4363670''>is</span> <span m=''4365540''>about</span> <span m=''4366670''>10</span>
  <span m=''4366910''>million.</span> <span m=''4369300''>Plenty</span> <span m=''4369550''>of</span>
  <span m=''4369730''>parallelism.</span> <span m=''4372940''>So</span> <span m=''4373080''>let''s</span>
  <span m=''4373300''>use</span> <span m=''4373520''>the</span> <span m=''4373610''>fact
  that</span> <span m=''4373940''>we</span> <span m=''4374020''>have</span> <span
  m=''4374100''>plenty</span> <span m=''4374410''>of</span> <span m=''4374480''>parallelism</span>
  <span m=''4375570''>to</span> <span m=''4375760''>say,</span> <span m=''4375990''>let''s</span>
  <span m=''4376690''>get</span> <span m=''4376840''>rid</span> <span m=''4376990''>of</span>
  <span m=''4377060''>some</span> <span m=''4377240''>of</span> <span m=''4377280''>that</span>
  <span m=''4377510''>parallelism</span> <span m=''4378070''>and</span> <span m=''4378230''>put</span>
  <span m=''4378380''>it</span> <span m=''4378500''>back</span> <span m=''4378820''>into</span>
  <span m=''4379120''>making</span> <span m=''4379460''>our</span> <span m=''4379610''>code</span>
  <span m=''4379900''>more</span> <span m=''4380070''>efficient.</span> </p><p><span
  m=''4382180''>So</span> <span m=''4382360''>in</span> <span m=''4382470''>particular,</span>
  <span m=''4384070''>this</span> <span m=''4384820''>code</span> <span m=''4385270''>uses</span>
  <span m=''4387740''>an</span> <span m=''4387890''>extra</span> <span m=''4388260''>temporary</span>
  <span m=''4388950''>d,</span> <span m=''4389520''>which it</span> <span m=''4389770''>allocates</span>
  <span m=''4390340''>here</span> <span m=''4390640''>and</span> <span m=''4390760''>it</span>
  <span m=''4390890''>deletes</span> <span m=''4391240''>here.</span> <span m=''4394080''>And</span>
  <span m=''4394375''>generally,</span> <span m=''4394670''>there''s</span> <span
  m=''4394870''>a</span> <span m=''4394920''>good</span> <span m=''4395120''>rule</span>
  <span m=''4395400''>that</span> <span m=''4395550''>says,</span> <span m=''4396110''>if</span>
  <span m=''4396280''>you</span> <span m=''4396410''>use</span> <span m=''4396640''>more</span>
  <span m=''4396840''>storage</span> <span m=''4397310''>you''re</span> <span m=''4397370''>going</span>
  <span m=''4397460''>to</span> <span m=''4397500''>use</span> <span m=''4397720''>more</span>
  <span m=''4397930''>time,</span> <span m=''4398360''>because</span> <span m=''4398550''>you''re
  going to</span> <span m=''4398610''>have</span> <span m=''4398840''>to</span> <span
  m=''4398940''>look</span> <span m=''4399170''>at</span> <span m=''4399240''>that</span>
  <span m=''4399470''>storage,</span> <span m=''4399860''>it''s going</span> <span
  m=''4400250''>to</span> <span m=''4400440''>take</span> <span m=''4400660''>up</span>
  <span m=''4400770''>space</span> <span m=''4401160''>in</span> <span m=''4401220''>your</span>
  <span m=''4401350''>cache,</span> <span m=''4402580''>and</span> <span m=''4402780''>it''s</span>
  <span m=''4402900''>generally</span> <span m=''4403220''>going</span> <span m=''4403340''>to</span>
  <span m=''4403390''>make</span> <span m=''4403620''>you</span> <span m=''4403710''>slower.</span>
  <span m=''4404300''>So</span> <span m=''4404480''>things</span> <span m=''4404770''>that</span>
  <span m=''4404880''>use</span> <span m=''4405090''>less</span> <span m=''4405330''>storage</span>
  <span m=''4405770''>are</span> <span m=''4405830''>generally</span> <span m=''4406210''>faster.</span>
  <span m=''4408470''>Not</span> <span m=''4408720''>always</span> <span m=''4408940''>the</span>
  <span m=''4409020''>case,</span> <span m=''4409210''>sometimes</span> <span m=''4409550''>there''s</span>
  <span m=''4409700''>a</span> <span m=''4409760''>trade</span> <span m=''4410040''>off.</span>
  <span m=''4410240''>But</span> <span m=''4410620''>often it''s</span> <span m=''4411090''>the</span>
  <span m=''4411180''>case,</span> <span m=''4411890''>use</span> <span m=''4412200''>more</span>
  <span m=''4412410''>storage,</span> <span m=''4413250''>it</span> <span m=''4413400''>runs</span>
  <span m=''4413620''>slower.</span> <span m=''4414290''>So</span> <span m=''4414450''>let''s</span>
  <span m=''4414620''>get</span> <span m=''4414800''>rid</span> <span m=''4414990''>of</span>
  <span m=''4415060''>this</span> <span m=''4415270''>guy.</span> <span m=''4416380''>How</span>
  <span m=''4416540''>do</span> <span m=''4416620''>we</span> <span m=''4416720''>get</span>
  <span m=''4416850''>rid</span> <span m=''4416970''>of</span> <span m=''4417080''>this</span>
  <span m=''4417190''>guy?</span> <span m=''4424440''>Yeah?</span> </p><p><span m=''4425754''>AUDIENCE:
  [INAUDIBLE PHRASE].</span> </p><p><span m=''4435140''>CHARLES LEISERSON: You''re
  going to</span> <span m=''4435200''>do this serially,</span> <span m=''4435530''>you''re
  saying?</span> </p><p><span m=''4435860''>AUDIENCE: Yeah,</span> <span m=''4436290''>you
  do those</span> <span m=''4436720''>serially</span> <span m=''4437167''>in add.</span>
  </p><p><span m=''4438510''>CHARLES LEISERSON: If</span> <span m=''4439010''>you</span>
  <span m=''4439390''>do this serially</span> <span m=''4439735''>in add,</span> <span
  m=''4440500''>it</span> <span m=''4440630''>turns</span> <span m=''4440880''>out</span>
  <span m=''4441010''>if</span> <span m=''4441120''>you</span> <span m=''4441260''>do</span>
  <span m=''4441490''>that,</span> <span m=''4441910''>you''re</span> <span m=''4442060''>going</span>
  <span m=''4442170''>to</span> <span m=''4442220''>be</span> <span m=''4442370''>in</span>
  <span m=''4442490''>trouble</span> <span m=''4443010''>because</span> <span m=''4443290''>you''re</span>
  <span m=''4443470''>going</span> <span m=''4443620''>to</span> <span m=''4444120''>not</span>
  <span m=''4444330''>have</span> <span m=''4444460''>very</span> <span m=''4444650''>much</span>
  <span m=''4444860''>parallelism,</span> <span m=''4447120''>unfortunately.</span>
  <span m=''4449330''>Actually,</span> <span m=''4449650''>analyzing</span> <span
  m=''4450130''>exactly</span> <span m=''4450700''>what</span> <span m=''4451010''>the</span>
  <span m=''4451080''>parallelism</span> <span m=''4451590''>is</span> <span m=''4451750''>there</span>
  <span m=''4451920''>is</span> <span m=''4452000''>actually</span> <span m=''4452280''>pretty</span>
  <span m=''4452510''>good.</span> <span m=''4453330''>It''s</span> <span m=''4453500''>a</span>
  <span m=''4453530''>good</span> <span m=''4453720''>puzzle.</span> <span m=''4455130''>Maybe</span>
  <span m=''4455280''>we''ll</span> <span m=''4455410''>do</span> <span m=''4455520''>that</span>
  <span m=''4455710''>on</span> <span m=''4455820''>the</span> <span m=''4455910''>quiz,</span>
  <span m=''4457530''>the</span> <span m=''4457710''>take</span> <span m=''4457920''>home</span>
  <span m=''4458270''>problem</span> <span m=''4458740''>set</span> <span m=''4458970''>we''re</span>
  <span m=''4459080''>calling</span> <span m=''4459370''>it</span> <span m=''4459480''>now,</span>
  <span m=''4459650''>right?</span> <span m=''4461110''>We''re</span> <span m=''4461520''>going
  to have a</span> <span m=''4461860''>take</span> <span m=''4462090''>home</span>
  <span m=''4462210''>problem set,</span> <span m=''4462680''>maybe</span> <span m=''4462930''>that''s</span>
  <span m=''4463170''>a</span> <span m=''4463190''>good</span> <span m=''4463560''>one.</span>
  </p><p><span m=''4466100''>Yeah,</span> <span m=''4467400''>so</span> <span m=''4467620''>the</span>
  <span m=''4467760''>idea</span> <span m=''4468070''>is,</span> <span m=''4468720''>you</span>
  <span m=''4468960''>can</span> <span m=''4469245''>sync.</span> <span m=''4469865''>And</span>
  <span m=''4470200''>in</span> <span m=''4470510''>particular,</span> <span m=''4471400''>why</span>
  <span m=''4471980''>not</span> <span m=''4473560''>compute</span> <span m=''4474000''>these,</span>
  <span m=''4474970''>then</span> <span m=''4475330''>sync,</span> <span m=''4476630''>and</span>
  <span m=''4476810''>then</span> <span m=''4477000''>compute</span> <span m=''4477450''>these,</span>
  <span m=''4477820''>adding</span> <span m=''4478190''>their</span> <span m=''4478410''>results</span>
  <span m=''4478870''>into</span> <span m=''4479170''>the</span> <span m=''4479290''>places</span>
  <span m=''4479780''>where</span> <span m=''4479950''>we</span> <span m=''4480050''>added</span>
  <span m=''4480170''>these</span> <span m=''4480290''>in?</span> <span m=''4483850''>So</span>
  <span m=''4484000''>it''s</span> <span m=''4484100''>making</span> <span m=''4484510''>the</span>
  <span m=''4484600''>program</span> <span m=''4485000''>more</span> <span m=''4485210''>serial,</span>
  <span m=''4487120''>because</span> <span m=''4487280''>I''m</span> <span m=''4487370''>putting</span>
  <span m=''4487630''>in a</span> <span m=''4487770''>sync.</span> <span m=''4490420''>That</span>
  <span m=''4490530''>shouldn''t</span> <span m=''4490710''>have</span> <span m=''4490890''>an</span>
  <span m=''4490980''>impact</span> <span m=''4491400''>on</span> <span m=''4491450''>the</span>
  <span m=''4491520''>work,</span> <span m=''4491810''>but</span> <span m=''4491910''>it</span>
  <span m=''4491980''>will</span> <span m=''4492210''>have</span> <span m=''4492300''>an</span>
  <span m=''4492360''>impact</span> <span m=''4493230''>on</span> <span m=''4493560''>the</span>
  <span m=''4494520''>span.</span> <span m=''4498430''>So</span> <span m=''4498620''>we''re</span>
  <span m=''4498740''>going</span> <span m=''4498830''>to</span> <span m=''4499250''>trade
  it</span> <span m=''4499610''>off,</span> <span m=''4499860''>and</span> <span m=''4499980''>the</span>
  <span m=''4500060''>way</span> <span m=''4500220''>we''ll</span> <span m=''4500390''>do</span>
  <span m=''4500540''>that</span> <span m=''4500880''>is by</span> <span m=''4501020''>putting</span>
  <span m=''4501340''>essentially</span> <span m=''4501780''>a</span> <span m=''4501820''>sync</span>
  <span m=''4502120''>in</span> <span m=''4502220''>the</span> <span m=''4502300''>middle.</span>
  <span m=''4504470''>And</span> <span m=''4504630''>since</span> <span m=''4504840''>they''re</span>
  <span m=''4504960''>adding</span> <span m=''4505420''>it</span> <span m=''4505510''>in,</span>
  <span m=''4505650''>I</span> <span m=''4505800''>don''t</span> <span m=''4505970''>even</span>
  <span m=''4506150''>have</span> <span m=''4506380''>we</span> <span m=''4506450''>call</span>
  <span m=''4506700''>the</span> <span m=''4506820''>addition</span> <span m=''4507130''>routine,</span>
  <span m=''4509960''>because</span> <span m=''4510320''>it''s</span> <span m=''4510490''>just</span>
  <span m=''4510650''>going</span> <span m=''4510740''>to</span> <span m=''4510800''>add</span>
  <span m=''4511070''>it</span> <span m=''4511190''>in</span> <span m=''4511430''>in</span>
  <span m=''4511600''>place.</span> <span m=''4512800''>So</span> <span m=''4512940''>I</span>
  <span m=''4513100''>spawn off</span> <span m=''4513580''>these</span> <span m=''4513820''>four</span>
  <span m=''4514070''>guys,</span> <span m=''4515210''>putting</span> <span m=''4515510''>their</span>
  <span m=''4515760''>results</span> <span m=''4516190''>into</span> <span m=''4516440''>c,</span>
  <span m=''4517230''>then I</span> <span m=''4517510''>spawn</span> <span m=''4517730''>off</span>
  <span m=''4517870''>these</span> <span m=''4518160''>four</span> <span m=''4518410''>guys,</span>
  <span m=''4518810''>and</span> <span m=''4518920''>they</span> <span m=''4519880''>add</span>
  <span m=''4520150''>their</span> <span m=''4520260''>results</span> <span m=''4520670''>into</span>
  <span m=''4520750''>c.</span> <span m=''4521920''>Is that</span> <span m=''4522180''>clear</span>
  <span m=''4523540''>what</span> <span m=''4523720''>the</span> <span m=''4523880''>code</span>
  <span m=''4524160''>is?</span> <span m=''4525060''>So</span> <span m=''4525290''>let''s</span>
  <span m=''4525510''>analyze</span> <span m=''4526080''>this.</span> </p><p><span
  m=''4532050''>So</span> <span m=''4534070''>the</span> <span m=''4534170''>work</span>
  <span m=''4534450''>for</span> <span m=''4534560''>this</span> <span m=''4534810''>is</span>
  <span m=''4540900''>order</span> <span m=''4541070''>n</span> <span m=''4541260''>cubed.</span>
  <span m=''4541570''>It''s</span> <span m=''4541690''>the</span> <span m=''4541780''>same</span>
  <span m=''4542080''>as</span> <span m=''4542200''>anything</span> <span m=''4542560''>else,</span>
  <span m=''4542850''>we</span> <span m=''4542970''>can</span> <span m=''4543120''>come</span>
  <span m=''4543300''>up</span> <span m=''4543430''>with</span> <span m=''4543530''>a</span>
  <span m=''4543580''>recurrence,</span> <span m=''4544750''>slightly</span> <span
  m=''4545170''>different</span> <span m=''4545490''>from</span> <span m=''4545610''>before</span>
  <span m=''4545865''>because</span> <span m=''4546120''>I</span> <span m=''4546210''>only</span>
  <span m=''4546380''>have</span> <span m=''4546490''>an order</span> <span m=''4546830''>one</span>
  <span m=''4547070''>there,</span> <span m=''4547240''>but</span> <span m=''4547350''>it</span>
  <span m=''4547420''>doesn''t</span> <span m=''4547690''>really</span> <span m=''4547910''>matter.</span>
  <span m=''4548510''>The</span> <span m=''4548950''>answer</span> <span m=''4549410''>is</span>
  <span m=''4549530''>order</span> <span m=''4549790''>n</span> <span m=''4549980''>cubed.</span>
  <span m=''4551570''>The</span> <span m=''4551670''>span,</span> <span m=''4553630''>now</span>
  <span m=''4553910''>this</span> <span m=''4554090''>gets</span> <span m=''4554270''>a</span>
  <span m=''4554320''>little</span> <span m=''4554540''>trickier.</span> <span m=''4555850''>What''s</span>
  <span m=''4556010''>the</span> <span m=''4556180''>recurrence</span> <span m=''4556580''>of</span>
  <span m=''4556660''>the</span> <span m=''4556750''>span?</span> </p><p><span m=''4564430''>AUDIENCE:
  [INAUDIBLE].</span> </p><p><span m=''4566570''>CHARLES LEISERSON: What</span> <span
  m=''4566780''>is</span> <span m=''4566990''>that?</span> </p><p><span m=''4567706''>AUDIENCE:
  Twice the</span> <span m=''4568202''>span of</span> <span m=''4568698''>m of n over</span>
  <span m=''4569194''>2.</span> </p><p><span m=''4569690''>CHARLES LEISERSON:</span>
  <span m=''4570190''>Twice</span> <span m=''4570620''>the</span> <span m=''4570710''>span</span>
  <span m=''4571140''>of</span> <span m=''4572260''>m</span> <span m=''4572520''>of</span>
  <span m=''4572630''>n</span> <span m=''4572780''>over</span> <span m=''4572990''>2,</span>
  <span m=''4573150''>that''s</span> <span m=''4573380''>right.</span> <span m=''4575510''>So</span>
  <span m=''4575710''>basically,</span> <span m=''4576250''>we</span> <span m=''4576380''>have</span>
  <span m=''4576500''>the</span> <span m=''4576590''>maximum</span> <span m=''4577210''>of</span>
  <span m=''4577330''>these</span> <span m=''4577670''>guys,</span> <span m=''4577955''>the</span>
  <span m=''4578560''>maximum of</span> <span m=''4579020''>these</span> <span m=''4579350''>guys,</span>
  <span m=''4579720''>and</span> <span m=''4579820''>then</span> <span m=''4579970''>this</span>
  <span m=''4580160''>is</span> <span m=''4580270''>making</span> <span m=''4580610''>those</span>
  <span m=''4580870''>things</span> <span m=''4581130''>be</span> <span m=''4581280''>in</span>
  <span m=''4581400''>series.</span> <span m=''4583090''>So</span> <span m=''4583230''>things
  that</span> <span m=''4583540''>are</span> <span m=''4583660''>in</span> <span m=''4583760''>parallel</span>
  <span m=''4584250''>I</span> <span m=''4584350''>take</span> <span m=''4584600''>the</span>
  <span m=''4584690''>max,</span> <span m=''4585180''>if it''s</span> <span m=''4585540''>in</span>
  <span m=''4585650''>series,</span> <span m=''4586090''>I</span> <span m=''4586180''>have</span>
  <span m=''4586360''>to</span> <span m=''4586450''>add</span> <span m=''4586760''>them.</span>
  <span m=''4586940''>So</span> <span m=''4587390''>I end</span> <span m=''4587660''>up</span>
  <span m=''4587770''>with</span> <span m=''4587970''>2m</span> <span m=''4588710''>infinity</span>
  <span m=''4589230''>of</span> <span m=''4589310''>n</span> <span m=''4589460''>over</span>
  <span m=''4589670''>2</span> <span m=''4589920''>plus</span> <span m=''4590210''>order</span>
  <span m=''4590460''>one.</span> <span m=''4591916''>Does</span> <span m=''4592300''>that</span>
  <span m=''4592430''>make</span> <span m=''4592610''>sense?</span> <span m=''4595270''>OK,</span>
  <span m=''4595470''>good.</span> </p><p><span m=''4596250''>So</span> <span m=''4596420''>let''s</span>
  <span m=''4596610''>solve</span> <span m=''4596890''>that</span> <span m=''4597110''>recurrence.</span>
  <span m=''4597550''>What''s</span> <span m=''4597700''>the</span> <span m=''4597800''>answer</span>
  <span m=''4598070''>to</span> <span m=''4598130''>that</span> <span m=''4598350''>one?</span>
  <span m=''4600260''>That''s</span> <span m=''4600500''>order</span> <span m=''4600800''>in.</span>
  <span m=''4601120''>Which</span> <span m=''4601330''>case</span> <span m=''4601590''>is</span>
  <span m=''4601750''>it?</span> <span m=''4604290''>I</span> <span m=''4604420''>never</span>
  <span m=''4604660''>know</span> <span m=''4604800''>what</span> <span m=''4604920''>the</span>
  <span m=''4605010''>cases are.</span> <span m=''4606540''>I</span> <span m=''4606610''>know</span>
  <span m=''4606820''>two,</span> <span m=''4607160''>but</span> <span m=''4607380''>one</span>
  <span m=''4607590''>and</span> <span m=''4607700''>three,</span> <span m=''4608010''>it''s</span>
  <span m=''4608180''>like--</span> <span m=''4609410''>they''re</span> <span m=''4609620''>the</span>
  <span m=''4609740''>same</span> <span m=''4610050''>thing, it''s</span> <span m=''4610410''>just</span>
  <span m=''4610650''>which</span> <span m=''4610990''>side</span> <span m=''4611330''>it''s
  in,</span> <span m=''4611700''>so</span> <span m=''4611940''>I</span> <span m=''4612030''>never</span>
  <span m=''4612320''>remember</span> <span m=''4612640''>what</span> <span m=''4612790''>the</span>
  <span m=''4612880''>number</span> <span m=''4613230''>is.</span> <span m=''4613370''>But</span>
  <span m=''4613590''>anyway,</span> <span m=''4614190''>case</span> <span m=''4614500''>one,</span>
  <span m=''4614770''>yes.</span> <span m=''4615250''>Case</span> <span m=''4615680''>one.</span>
  <span m=''4617720''>It''s</span> <span m=''4617900''>the</span> <span m=''4617990''>one</span>
  <span m=''4618270''>where</span> <span m=''4618540''>this</span> <span m=''4618800''>thing</span>
  <span m=''4618980''>is</span> <span m=''4619120''>bigger,</span> <span m=''4619760''>so</span>
  <span m=''4619920''>that''s</span> <span m=''4620170''>order</span> <span m=''4620430''>n.</span>
  <span m=''4624410''>Good.</span> </p><p><span m=''4627200''>So</span> <span m=''4627430''>then</span>
  <span m=''4628380''>the</span> <span m=''4628480''>work</span> <span m=''4628760''>is</span>
  <span m=''4628910''>n</span> <span m=''4629110''>cubed,</span> <span m=''4630590''>the</span>
  <span m=''4630700''>span</span> <span m=''4631160''>is</span> <span m=''4631280''>order</span>
  <span m=''4631330''>n,</span> <span m=''4632910''>the</span> <span m=''4633010''>parallelism</span>
  <span m=''4633630''>is</span> <span m=''4633750''>order</span> <span m=''4634010''>n</span>
  <span m=''4634170''>squared.</span> <span m=''4635870''>So</span> <span m=''4636090''>for</span>
  <span m=''4636445''>1,000 by</span> <span m=''4636800''>1,000</span> <span m=''4637150''>matrices,</span>
  <span m=''4637780''>I</span> <span m=''4637850''>get</span> <span m=''4638070''>parallelism</span>
  <span m=''4638570''>on</span> <span m=''4638660''>the</span> <span m=''4638770''>order</span>
  <span m=''4639010''>of</span> <span m=''4639110''>a</span> <span m=''4639160''>million,</span>
  <span m=''4640330''>instead</span> <span m=''4640700''>of</span> <span m=''4640920''>before,</span>
  <span m=''4641350''>I</span> <span m=''4641420''>had</span> <span m=''4641600''>parallelism</span>
  <span m=''4642160''>on</span> <span m=''4642340''>the</span> <span m=''4642390''>order
  of</span> <span m=''4642660''>10</span> <span m=''4642950''>million.</span> <span
  m=''4645710''>So</span> <span m=''4645880''>this</span> <span m=''4646080''>turns</span>
  <span m=''4646360''>out</span> <span m=''4647830''>way</span> <span m=''4648090''>better</span>
  <span m=''4648390''>code</span> <span m=''4648710''>than</span> <span m=''4648800''>the</span>
  <span m=''4648870''>previous</span> <span m=''4649340''>one</span> <span m=''4649540''>because</span>
  <span m=''4649760''>it</span> <span m=''4649860''>avoids</span> <span m=''4650340''>the</span>
  <span m=''4650430''>temporary</span> <span m=''4652130''>and</span> <span m=''4652700''>therefore</span>
  <span m=''4653130''>runs,</span> <span m=''4653840''>you</span> <span m=''4653990''>get</span>
  <span m=''4654090''>a</span> <span m=''4654190''>constant</span> <span m=''4654620''>factor</span>
  <span m=''4654950''>improvement</span> <span m=''4656510''>for</span> <span m=''4656600''>that,</span>
  <span m=''4656990''>and</span> <span m=''4657140''>it''s</span> <span m=''4657280''>still,</span>
  <span m=''4657940''>on</span> <span m=''4658700''>12</span> <span m=''4659045''>cores,</span>
  <span m=''4659390''>it''s</span> <span m=''4659530''>going</span> <span m=''4659660''>to</span>
  <span m=''4659710''>run</span> <span m=''4661240''>pretty</span> <span m=''4661520''>fast.</span>
  <span m=''4662300''>And</span> <span m=''4662670''>in</span> <span m=''4662780''>practice,</span>
  <span m=''4663290''>this</span> <span m=''4663460''>is</span> <span m=''4663600''>a</span>
  <span m=''4663640''>much</span> <span m=''4663940''>better</span> <span m=''4664130''>way</span>
  <span m=''4664250''>to</span> <span m=''4664370''>do</span> <span m=''4664550''>it.</span>
  </p><p><span m=''4665530''>The</span> <span m=''4665670''>actual</span> <span m=''4666240''>best</span>
  <span m=''4666520''>code</span> <span m=''4666750''>that</span> <span m=''4666870''>I</span>
  <span m=''4666960''>know</span> <span m=''4667210''>for</span> <span m=''4667370''>doing</span>
  <span m=''4667620''>this</span> <span m=''4669190''>essentially</span> <span m=''4671020''>does</span>
  <span m=''4671340''>divide and</span> <span m=''4671720''>conquer in</span> <span
  m=''4672130''>only</span> <span m=''4672360''>one</span> <span m=''4672590''>dimension</span>
  <span m=''4673000''>at</span> <span m=''4673070''>a</span> <span m=''4673180''>time.</span>
  <span m=''4674580''>So</span> <span m=''4674710''>basically,</span> <span m=''4675230''>it</span>
  <span m=''4675300''>looks</span> <span m=''4675580''>to</span> <span m=''4675720''>see</span>
  <span m=''4675880''>what''s</span> <span m=''4676130''>the</span> <span m=''4676220''>long</span>
  <span m=''4676530''>dimension,</span> <span m=''4677160''>and</span> <span m=''4677270''>whatever</span>
  <span m=''4677550''>the</span> <span m=''4677630''>long</span> <span m=''4677890''>dimension</span>
  <span m=''4678310''>is,</span> <span m=''4679050''>it</span> <span m=''4679240''>slices</span>
  <span m=''4679740''>it</span> <span m=''4679820''>in</span> <span m=''4679890''>half</span>
  <span m=''4680720''>and</span> <span m=''4680880''>then</span> <span m=''4681000''>recurses,</span>
  <span m=''4682170''>and</span> <span m=''4682320''>just</span> <span m=''4682540''>does</span>
  <span m=''4682830''>that</span> <span m=''4683120''>as</span> <span m=''4683230''>a</span>
  <span m=''4683340''>binary</span> <span m=''4684670''>thing.</span> <span m=''4684920''>And</span>
  <span m=''4685020''>it</span> <span m=''4685110''>basically</span> <span m=''4685480''>is</span>
  <span m=''4685600''>the</span> <span m=''4685680''>same</span> <span m=''4685990''>work,</span>
  <span m=''4686220''>et cetera.</span> <span m=''4686450''>It''s</span> <span m=''4686570''>a</span>
  <span m=''4686610''>little</span> <span m=''4686710''>bit</span> <span m=''4686880''>more</span>
  <span m=''4687080''>tricky</span> <span m=''4687400''>to</span> <span m=''4687480''>analyze.</span>
  </p><p><span m=''4694820''>Let</span> <span m=''4694970''>me</span> <span m=''4695080''>quick</span>
  <span m=''4695650''>do</span> <span m=''4696290''>merge</span> <span m=''4696610''>sort.</span>
  <span m=''4697940''>So</span> <span m=''4698070''>you know</span> <span m=''4698330''>merge</span>
  <span m=''4698610''>sort.</span> <span m=''4698900''>There''s</span> <span m=''4699130''>merging</span>
  <span m=''4699510''>two</span> <span m=''4699660''>sorted</span> <span m=''4700010''>arrays,</span>
  <span m=''4700620''>we</span> <span m=''4700730''>saw</span> <span m=''4700920''>this</span>
  <span m=''4701120''>before.</span> <span m=''4703470''>If</span> <span m=''4703680''>I</span>
  <span m=''4704160''>spend</span> <span m=''4704490''>all</span> <span m=''4704630''>this</span>
  <span m=''4704780''>time</span> <span m=''4705020''>doing</span> <span m=''4705230''>animations,</span>
  <span m=''4705880''>I</span> <span m=''4705930''>might as</span> <span m=''4706190''>well</span>
  <span m=''4706320''>get</span> <span m=''4706520''>my</span> <span m=''4708330''>mileage</span>
  <span m=''4708800''>out</span> <span m=''4708910''>of</span> <span m=''4709030''>it.</span>
  <span m=''4709830''>There</span> <span m=''4710060''>we</span> <span m=''4710100''>go.</span>
  <span m=''4710480''>So</span> <span m=''4710770''>you</span> <span m=''4710910''>merge,</span>
  <span m=''4711490''>that''s</span> <span m=''4711720''>basically</span> <span m=''4712140''>what</span>
  <span m=''4712310''>this</span> <span m=''4712490''>code</span> <span m=''4712760''>does.</span>
  <span m=''4713820''>Order</span> <span m=''4714130''>n</span> <span m=''4714320''>time</span>
  <span m=''4714920''>to</span> <span m=''4715030''>merge.</span> <span m=''4717090''>So</span>
  <span m=''4717220''>here''s</span> <span m=''4717500''>merge</span> <span m=''4717760''>sort.</span>
  <span m=''4718470''>So</span> <span m=''4718610''>what</span> <span m=''4718700''>I''ll</span>
  <span m=''4718790''>do</span> <span m=''4718950''>in</span> <span m=''4719040''>merge</span>
  <span m=''4719380''>sort</span> <span m=''4719610''>is</span> <span m=''4719770''>the</span>
  <span m=''4719850''>same</span> <span m=''4720150''>thing</span> <span m=''4720380''>I</span>
  <span m=''4720470''>normally</span> <span m=''4720880''>do,</span> <span m=''4721060''>except</span>
  <span m=''4721360''>that</span> <span m=''4721470''>I''ll</span> <span m=''4721610''>make</span>
  <span m=''4730260''>recursive</span> <span m=''4732210''>routines</span> <span m=''4732740''>go</span>
  <span m=''4732930''>in</span> <span m=''4733020''>parallel.</span> <span m=''4733500''>So</span>
  <span m=''4733660''>when</span> <span m=''4733790''>I</span> <span m=''4733860''>do</span>
  <span m=''4734060''>that,</span> <span m=''4734920''>it</span> <span m=''4735050''>basically</span>
  <span m=''4737210''>divide and</span> <span m=''4737650''>conquers</span> <span
  m=''4738500''>down,</span> <span m=''4738900''>and</span> <span m=''4739120''>then</span>
  <span m=''4739480''>it sort of</span> <span m=''4739890''>does</span> <span m=''4740210''>this</span>
  <span m=''4740770''>to</span> <span m=''4741250''>merge</span> <span m=''4741650''>things</span>
  <span m=''4741890''>together.</span> <span m=''4743760''>So we</span> <span m=''4744080''>saw</span>
  <span m=''4744340''>this</span> <span m=''4744580''>before,</span> <span m=''4745530''>except</span>
  <span m=''4745830''>now,</span> <span m=''4746770''>I''ve</span> <span m=''4746950''>got</span>
  <span m=''4748120''>the</span> <span m=''4748200''>fact</span> <span m=''4748520''>that</span>
  <span m=''4748640''>I</span> <span m=''4748710''>can</span> <span m=''4748900''>sort</span>
  <span m=''4749270''>two</span> <span m=''4749430''>things</span> <span m=''4749730''>in</span>
  <span m=''4749850''>parallel</span> <span m=''4750470''>rather</span> <span m=''4750800''>than</span>
  <span m=''4750980''>sorting</span> <span m=''4751450''>them</span> <span m=''4751860''>serially.</span>
  </p><p><span m=''4753020''>So</span> <span m=''4753160''>let''s</span> <span m=''4753320''>take</span>
  <span m=''4753510''>a</span> <span m=''4753580''>look</span> <span m=''4753710''>at</span>
  <span m=''4753840''>the</span> <span m=''4753920''>work.</span> <span m=''4754375''>What''s</span>
  <span m=''4754830''>the</span> <span m=''4754910''>work of</span> <span m=''4755200''>merge</span>
  <span m=''4755480''>sort?</span> <span m=''4755900''>We</span> <span m=''4755990''>know</span>
  <span m=''4756170''>that.</span> <span m=''4758770''>n</span> <span m=''4758960''>log</span>
  <span m=''4759290''>n,</span> <span m=''4759840''>right?</span> <span m=''4760370''>2t</span>
  <span m=''4760900''>of</span> <span m=''4761000''>n</span> <span m=''4761590''>over</span>
  <span m=''4761840''>2</span> <span m=''4762100''>plus</span> <span m=''4762390''>order</span>
  <span m=''4762700''>n,</span> <span m=''4763580''>so</span> <span m=''4763730''>that''s</span>
  <span m=''4764070''>order</span> <span m=''4764640''>n</span> <span m=''4764830''>log
  n.</span> <span m=''4766790''>The</span> <span m=''4766900''>span</span> <span m=''4767600''>is</span>
  <span m=''4768190''>what?</span> <span m=''4769590''>What''s</span> <span m=''4769770''>the</span>
  <span m=''4769850''>recurrence</span> <span m=''4770300''>of</span> <span m=''4770380''>the</span>
  <span m=''4770460''>span?</span> <span m=''4776150''>So</span> <span m=''4776260''>we''re</span>
  <span m=''4776340''>going</span> <span m=''4776430''>to</span> <span m=''4776500''>take</span>
  <span m=''4776740''>the</span> <span m=''4776820''>maximum</span> <span m=''4777460''>of</span>
  <span m=''4777560''>these</span> <span m=''4777800''>two</span> <span m=''4777960''>guys.</span>
  <span m=''4778890''>So</span> <span m=''4779010''>we</span> <span m=''4779080''>only</span>
  <span m=''4779280''>have</span> <span m=''4779500''>one</span> <span m=''4780530''>term</span>
  <span m=''4780980''>that</span> <span m=''4781090''>involves</span> <span m=''4782330''>t</span>
  <span m=''4782520''>infinity,</span> <span m=''4783770''>and</span> <span m=''4783910''>then</span>
  <span m=''4784050''>the</span> <span m=''4784140''>merge</span> <span m=''4784640''>costs
  us</span> <span m=''4785110''>order</span> <span m=''4785410''>n,</span> <span m=''4785690''>so</span>
  <span m=''4785850''>we</span> <span m=''4785930''>get</span> <span m=''4786090''>this</span>
  <span m=''4786240''>recurrence.</span> <span m=''4789440''>So</span> <span m=''4789620''>that</span>
  <span m=''4790200''>says</span> <span m=''4790660''>that</span> <span m=''4792110''>the</span>
  <span m=''4792220''>solution</span> <span m=''4792490''>is</span> <span m=''4792760''>order</span>
  <span m=''4793070''>n.</span> <span m=''4794990''>So</span> <span m=''4795140''>therefore,</span>
  <span m=''4795660''>the</span> <span m=''4796780''>work</span> <span m=''4797130''>is</span>
  <span m=''4798270''>n</span> <span m=''4798460''>log</span> <span m=''4798750''>n,</span>
  <span m=''4798890''>the</span> <span m=''4799030''>span is</span> <span m=''4799500''>order</span>
  <span m=''4799805''>n,</span> <span m=''4801590''>and</span> <span m=''4801740''>so</span>
  <span m=''4801920''>the</span> <span m=''4802020''>parallelism</span> <span m=''4802640''>is</span>
  <span m=''4802780''>order</span> <span m=''4803050''>log</span> <span m=''4803410''>n.</span>
  <span m=''4806546''>Puny.</span> <span m=''4807950''>Puny</span> <span m=''4808320''>parallelism.</span>
  <span m=''4808410''>Log n</span> <span m=''4808780''>is</span> <span m=''4808950''>like,</span>
  <span m=''4809580''>you</span> <span m=''4809810''>can</span> <span m=''4810040''>run</span>
  <span m=''4810230''>it,</span> <span m=''4810450''>and</span> <span m=''4810620''>it''ll</span>
  <span m=''4810800''>work</span> <span m=''4811040''>fine</span> <span m=''4811370''>on</span>
  <span m=''4811470''>a</span> <span m=''4811520''>few</span> <span m=''4811750''>cores,</span>
  <span m=''4812160''>but</span> <span m=''4812370''>it''s</span> <span m=''4812540''>not</span>
  <span m=''4812710''>to</span> <span m=''4812800''>be</span> <span m=''4812890''>something</span>
  <span m=''4813210''>that</span> <span m=''4813300''>generally</span> <span m=''4814130''>will</span>
  <span m=''4814250''>scale</span> <span m=''4814690''>and</span> <span m=''4814820''>give</span>
  <span m=''4814950''>you</span> <span m=''4815070''>a</span> <span m=''4815130''>lot</span>
  <span m=''4815350''>of</span> <span m=''4815420''>parallelism.</span> </p><p><span
  m=''4817570''>So</span> <span m=''4818320''>it''s</span> <span m=''4818550''>pretty</span>
  <span m=''4818840''>clear</span> <span m=''4819200''>from</span> <span m=''4819380''>this</span>
  <span m=''4819640''>that</span> <span m=''4819780''>the</span> <span m=''4819850''>bottleneck--</span>
  <span m=''4820630''>where''s</span> <span m=''4820990''>all</span> <span m=''4821250''>the</span>
  <span m=''4821320''>span</span> <span m=''4821790''>going to?</span> <span m=''4822330''>It''s</span>
  <span m=''4822510''>going</span> <span m=''4822810''>to</span> <span m=''4822940''>that</span>
  <span m=''4823200''>merge.</span> <span m=''4826730''>So</span> <span m=''4826900''>when
  you</span> <span m=''4827080''>understand</span> <span m=''4827950''>that</span>
  <span m=''4828080''>that''s</span> <span m=''4828320''>the</span> <span m=''4828400''>structure</span>
  <span m=''4828850''>of it,</span> <span m=''4828960''>now</span> <span m=''4829180''>you</span>
  <span m=''4829300''>say</span> <span m=''4829470''>if</span> <span m=''4829570''>you</span>
  <span m=''4829690''>want</span> <span m=''4829810''>to</span> <span m=''4829850''>get</span>
  <span m=''4830060''>parallelism,</span> <span m=''4830930''>you''ve</span> <span
  m=''4831020''>got</span> <span m=''4831140''>to</span> <span m=''4831190''>go</span>
  <span m=''4831410''>after</span> <span m=''4831710''>the</span> <span m=''4831810''>merge.</span>
  <span m=''4832230''>So</span> <span m=''4832410''>here''s</span> <span m=''4832680''>how</span>
  <span m=''4832820''>we</span> <span m=''4832940''>parallelize</span> <span m=''4833480''>the</span>
  <span m=''4833560''>merge.</span> <span m=''4834480''>So</span> <span m=''4834600''>we''re</span>
  <span m=''4834710''>going</span> <span m=''4834790''>to</span> <span m=''4834850''>look</span>
  <span m=''4835050''>at</span> <span m=''4835130''>merging</span> <span m=''4835570''>of</span>
  <span m=''4835690''>two</span> <span m=''4835870''>arrays</span> <span m=''4836330''>that</span>
  <span m=''4836520''>are of</span> <span m=''4836710''>possibly</span> <span m=''4837250''>different</span>
  <span m=''4837570''>length.</span> <span m=''4838920''>So</span> <span m=''4839120''>one</span>
  <span m=''4839360''>we''ll</span> <span m=''4839500''>call</span> <span m=''4839850''>A,</span>
  <span m=''4840210''>and one we''ll</span> <span m=''4840600''>call</span> <span
  m=''4840860''>B,</span> <span m=''4841220''>with</span> <span m=''4841390''>na</span>
  <span m=''4841820''>and</span> <span m=''4842210''>nb</span> <span m=''4842400''>elements.</span>
  <span m=''4842810''>And</span> <span m=''4842930''>let</span> <span m=''4843080''>me</span>
  <span m=''4843190''>assume</span> <span m=''4843500''>without</span> <span m=''4843810''>loss</span>
  <span m=''4844070''>of</span> <span m=''4844170''>generality</span> <span m=''4844860''>that</span>
  <span m=''4845170''>na</span> <span m=''4846010''>is</span> <span m=''4846540''>greater</span>
  <span m=''4846790''>than or</span> <span m=''4846880''>equal</span> <span m=''4847120''>to</span>
  <span m=''4847220''>nb,</span> <span m=''4847910''>because</span> <span m=''4848090''>otherwise</span>
  <span m=''4848510''>I</span> <span m=''4848540''>can</span> <span m=''4848700''>just</span>
  <span m=''4848830''>switch</span> <span m=''4849120''>the</span> <span m=''4849230''>roles</span>
  <span m=''4849590''>of</span> <span m=''4849690''>A</span> <span m=''4849790''>and</span>
  <span m=''4849950''>B.</span> </p><p><span m=''4851280''>So</span> <span m=''4851410''>the</span>
  <span m=''4851480''>way</span> <span m=''4851680''>that</span> <span m=''4851790''>I''m</span>
  <span m=''4851880''>going</span> <span m=''4851960''>to</span> <span m=''4852040''>do
  it</span> <span m=''4852480''>is</span> <span m=''4852690''>I''m</span> <span m=''4852790''>going</span>
  <span m=''4852890''>to</span> <span m=''4852940''>find</span> <span m=''4853300''>the</span>
  <span m=''4853370''>middle</span> <span m=''4853680''>element</span> <span m=''4853985''>of</span>
  <span m=''4854290''>A.</span> <span m=''4855290''>These</span> <span m=''4855480''>are</span>
  <span m=''4855550''>sorted</span> <span m=''4855960''>arrays</span> <span m=''4856225''>that</span>
  <span m=''4856490''>I''m going to</span> <span m=''4856720''>merge.</span> <span
  m=''4858300''>I</span> <span m=''4858360''>find</span> <span m=''4858590''>the</span>
  <span m=''4858650''>middle</span> <span m=''4858940''>element</span> <span m=''4859300''>of</span>
  <span m=''4859430''>A,</span> <span m=''4861020''>so</span> <span m=''4861130''>these</span>
  <span m=''4861370''>guys</span> <span m=''4861590''>are</span> <span m=''4861700''>or</span>
  <span m=''4861780''>less</span> <span m=''4861990''>than</span> <span m=''4862070''>or</span>
  <span m=''4862130''>equal</span> <span m=''4862510''>to</span> <span m=''4862860''>a</span>
  <span m=''4863130''>of</span> <span m=''4863290''>ma,</span> <span m=''4863450''>and</span>
  <span m=''4863800''>these</span> <span m=''4863980''>are</span> <span m=''4864210''>greater</span>
  <span m=''4864540''>than or</span> <span m=''4864680''>equal</span> <span m=''4864980''>to.</span>
  <span m=''4865930''>And</span> <span m=''4866120''>now</span> <span m=''4866320''>I</span>
  <span m=''4866430''>binary</span> <span m=''4866970''>search</span> <span m=''4867380''>and</span>
  <span m=''4867510''>find</span> <span m=''4867860''>out</span> <span m=''4868110''>where</span>
  <span m=''4869070''>that</span> <span m=''4869290''>middle</span> <span m=''4869570''>element</span>
  <span m=''4870090''>would</span> <span m=''4870250''>fall</span> <span m=''4870930''>in</span>
  <span m=''4871120''>the</span> <span m=''4871240''>array</span> <span m=''4871510''>B.</span>
  <span m=''4873740''>So</span> <span m=''4873860''>that</span> <span m=''4874050''>costs</span>
  <span m=''4874370''>me</span> <span m=''4874480''>log</span> <span m=''4874840''>n</span>
  <span m=''4875010''>time</span> <span m=''4875300''>to</span> <span m=''4875380''>binary</span>
  <span m=''4875760''>search.</span> <span m=''4876460''>Remember</span> <span m=''4876680''>binary</span>
  <span m=''4877020''>search?</span> </p><p><span m=''4882420''>Then</span> <span
  m=''4882730''>what</span> <span m=''4883030''>I''m going</span> <span m=''4883310''>to</span>
  <span m=''4883390''>do</span> <span m=''4883540''>is</span> <span m=''4883630''>recursively</span>
  <span m=''4884430''>merge</span> <span m=''4884800''>these</span> <span m=''4885110''>guys,</span>
  <span m=''4885560''>because</span> <span m=''4885750''>these</span> <span m=''4886040''>are</span>
  <span m=''4886210''>sorted</span> <span m=''4886790''>and</span> <span m=''4887040''>less</span>
  <span m=''4887330''>than</span> <span m=''4887430''>or</span> <span m=''4887490''>equal</span>
  <span m=''4887710''>to</span> <span m=''4887950''>ma,</span> <span m=''4888490''>recursively</span>
  <span m=''4889390''>merge</span> <span m=''4889780''>those</span> <span m=''4890480''>and</span>
  <span m=''4890670''>put</span> <span m=''4890860''>this</span> <span m=''4891120''>guy</span>
  <span m=''4891360''>in</span> <span m=''4891470''>the</span> <span m=''4891540''>middle.</span>
  <span m=''4895140''>So</span> <span m=''4895290''>when</span> <span m=''4895420''>I</span>
  <span m=''4895510''>do</span> <span m=''4895740''>that,</span> <span m=''4899270''>the</span>
  <span m=''4899890''>key</span> <span m=''4900230''>question</span> <span m=''4900810''>when</span>
  <span m=''4900960''>we</span> <span m=''4901190''>analyze--</span> <span m=''4902180''>it</span>
  <span m=''4902330''>turns</span> <span m=''4902560''>out</span> <span m=''4902710''>the</span>
  <span m=''4902780''>work</span> <span m=''4903100''>is</span> <span m=''4903240''>going</span>
  <span m=''4903360''>to</span> <span m=''4903410''>basically</span> <span m=''4904000''>be</span>
  <span m=''4904270''>the</span> <span m=''4904780''>same,</span> <span m=''4905150''>but</span>
  <span m=''4905310''>the</span> <span m=''4905420''>key</span> <span m=''4905650''>thing</span>
  <span m=''4905860''>is</span> <span m=''4905990''>going</span> <span m=''4906070''>to</span>
  <span m=''4906160''>be</span> <span m=''4906300''>what</span> <span m=''4906470''>happens</span>
  <span m=''4906960''>to</span> <span m=''4907590''>the</span> <span m=''4907690''>span?</span>
  <span m=''4909170''>And</span> <span m=''4909440''>the</span> <span m=''4909560''>idea</span>
  <span m=''4909890''>here</span> <span m=''4910170''>is</span> <span m=''4910290''>that</span>
  <span m=''4910440''>the</span> <span m=''4910550''>total</span> <span m=''4910920''>number</span>
  <span m=''4911170''>of</span> <span m=''4911240''>elements</span> <span m=''4911880''>in</span>
  <span m=''4912080''>the</span> <span m=''4912170''>larger</span> <span m=''4912930''>of</span>
  <span m=''4913120''>these</span> <span m=''4913410''>two</span> <span m=''4913600''>things</span>
  <span m=''4915240''>is</span> <span m=''4915460''>going</span> <span m=''4915560''>to</span>
  <span m=''4915660''>be</span> <span m=''4915880''>at</span> <span m=''4916020''>most</span>
  <span m=''4917850''>what?</span> <span m=''4919690''>Another</span> <span m=''4919930''>way</span>
  <span m=''4920050''>of</span> <span m=''4920150''>looking</span> <span m=''4920470''>at</span>
  <span m=''4920710''>it is</span> <span m=''4920860''>in</span> <span m=''4921030''>the</span>
  <span m=''4921100''>smaller</span> <span m=''4921640''>partition,</span> <span m=''4924015''>if</span>
  <span m=''4924310''>n</span> <span m=''4924520''>is</span> <span m=''4924680''>the</span>
  <span m=''4924780''>total</span> <span m=''4925090''>number</span> <span m=''4925310''>of</span>
  <span m=''4925390''>elements,</span> <span m=''4925760''>the</span> <span m=''4925830''>smaller</span>
  <span m=''4926230''>partition</span> <span m=''4927120''>has</span> <span m=''4927465''>how</span>
  <span m=''4927810''>many</span> <span m=''4928920''>elements</span> <span m=''4929240''>at</span>
  <span m=''4929310''>least</span> <span m=''4930110''>relative</span> <span m=''4930520''>to</span>
  <span m=''4930610''>n?</span> <span m=''4933750''>No</span> <span m=''4933840''>matter</span>
  <span m=''4934180''>where</span> <span m=''4934690''>this</span> <span m=''4934830''>binary</span>
  <span m=''4935300''>search</span> <span m=''4935650''>finds</span> <span m=''4935960''>itself.</span>
  <span m=''4937620''>So</span> <span m=''4937780''>the</span> <span m=''4937850''>worst</span>
  <span m=''4938130''>case</span> <span m=''4938380''>is</span> <span m=''4938470''>sort
  of going</span> <span m=''4938790''>to</span> <span m=''4938870''>come</span> <span
  m=''4939170''>when</span> <span m=''4939430''>this</span> <span m=''4939710''>guy</span>
  <span m=''4940890''>is</span> <span m=''4941060''>like</span> <span m=''4941500''>at</span>
  <span m=''4941640''>one</span> <span m=''4941880''>end</span> <span m=''4942140''>or</span>
  <span m=''4942270''>the</span> <span m=''4942510''>other.</span> <span m=''4944900''>And</span>
  <span m=''4945030''>then</span> <span m=''4945180''>the</span> <span m=''4945270''>point</span>
  <span m=''4945600''>is</span> <span m=''4945840''>that</span> <span m=''4945980''>because</span>
  <span m=''4946300''>A</span> <span m=''4946380''>is</span> <span m=''4946780''>the</span>
  <span m=''4946920''>larger</span> <span m=''4947410''>array,</span> <span m=''4948070''>at</span>
  <span m=''4948220''>least</span> <span m=''4948600''>a</span> <span m=''4948680''>quarter</span>
  <span m=''4949210''>of</span> <span m=''4949280''>the</span> <span m=''4949430''>elements</span>
  <span m=''4949900''>will</span> <span m=''4950010''>still</span> <span m=''4950360''>be</span>
  <span m=''4950470''>in</span> <span m=''4950580''>the</span> <span m=''4950640''>smaller</span>
  <span m=''4951080''>partition.</span> <span m=''4953340''>Of</span> <span m=''4953640''>all</span>
  <span m=''4954030''>the</span> <span m=''4954160''>elements</span> <span m=''4954550''>here,</span>
  <span m=''4955900''>at</span> <span m=''4956020''>least</span> <span m=''4956340''>a</span>
  <span m=''4956410''>quarter</span> <span m=''4956830''>will</span> <span m=''4956990''>be</span>
  <span m=''4957110''>in</span> <span m=''4957210''>the</span> <span m=''4957280''>smaller</span>
  <span m=''4957640''>partition,</span> <span m=''4957930''>which</span> <span m=''4958150''>will</span>
  <span m=''4958220''>occur</span> <span m=''4958500''>when</span> <span m=''4958720''>B</span>
  <span m=''4958960''>is</span> <span m=''4959120''>equal</span> <span m=''4959540''>to</span>
  <span m=''4959680''>in</span> <span m=''4959840''>size</span> <span m=''4960220''>to
  A.</span> <span m=''4962270''>So</span> <span m=''4962450''>the</span> <span m=''4963160''>number,</span>
  <span m=''4963700''>in</span> <span m=''4963890''>the</span> <span m=''4963970''>larger</span>
  <span m=''4964320''>of</span> <span m=''4964670''>the recursive</span> <span m=''4965170''>merges,</span>
  <span m=''4965590''>is</span> <span m=''4965770''>at</span> <span m=''4965850''>most</span>
  <span m=''4966140''>3/4</span> <span m=''4966465''>n.</span> <span m=''4969350''>Sound</span>
  <span m=''4969610''>good?</span> </p><p><span m=''4970750''>That''s</span> <span
  m=''4971020''>the</span> <span m=''4971110''>main,</span> <span m=''4971840''>key</span>
  <span m=''4972110''>idea</span> <span m=''4972630''>behind</span> <span m=''4973040''>this.</span>
  <span m=''4974410''>So</span> <span m=''4975810''>here''s</span> <span m=''4976160''>the</span>
  <span m=''4976240''>parallel</span> <span m=''4976710''>merge.</span> <span m=''4977420''>Basically</span>
  <span m=''4977910''>you</span> <span m=''4978000''>do</span> <span m=''4978140''>binary</span>
  <span m=''4978620''>search,</span> <span m=''4979680''>you</span> <span m=''4979790''>spawn,</span>
  <span m=''4980095''>then,</span> <span m=''4981160''>the</span> <span m=''4981290''>two</span>
  <span m=''4981480''>merges.</span> <span m=''4982660''>Here''s</span> <span m=''4982920''>one</span>
  <span m=''4983120''>merge,</span> <span m=''4983740''>and</span> <span m=''4983840''>here''s</span>
  <span m=''4984090''>the</span> <span m=''4984210''>other</span> <span m=''4984400''>merge,</span>
  <span m=''4984720''>and</span> <span m=''4984800''>then</span> <span m=''4984950''>you</span>
  <span m=''4985040''>sync.</span> <span m=''4986140''>So</span> <span m=''4986270''>that''s</span>
  <span m=''4986500''>the</span> <span m=''4986580''>code</span> <span m=''4986920''>for</span>
  <span m=''4987050''>the</span> <span m=''4987360''>doing</span> <span m=''4987820''>the</span>
  <span m=''4988410''>parallel</span> <span m=''4988840''>merge.</span> <span m=''4989590''>And</span>
  <span m=''4989720''>now</span> <span m=''4989880''>you</span> <span m=''4990020''>want</span>
  <span m=''4990160''>to</span> <span m=''4990200''>incorporate</span> <span m=''4990870''>that</span>
  <span m=''4991090''>parallel</span> <span m=''4991430''>merge</span> <span m=''4991940''>into</span>
  <span m=''4992830''>the</span> <span m=''4992930''>parallel</span> <span m=''4993350''>merge</span>
  <span m=''4993620''>sort.</span> <span m=''4994750''>Of</span> <span m=''4994820''>course,</span>
  <span m=''4995050''>you</span> <span m=''4995140''>coarsen</span> <span m=''4995510''>the</span>
  <span m=''4995580''>base</span> <span m=''4995840''>cases</span> <span m=''4996250''>for</span>
  <span m=''4996400''>efficiency.</span> </p><p><span m=''5001190''>So</span> <span
  m=''5001590''>let''s</span> <span m=''5001830''>analyze</span> <span m=''5002380''>the</span>
  <span m=''5002460''>span</span> <span m=''5002940''>of</span> <span m=''5003040''>this.</span>
  <span m=''5004190''>So</span> <span m=''5004350''>the</span> <span m=''5004450''>span</span>
  <span m=''5004980''>is</span> <span m=''5005120''>basically</span> <span m=''5005640''>then</span>
  <span m=''5005850''>the</span> <span m=''5005940''>span</span> <span m=''5006680''>of</span>
  <span m=''5007130''>something</span> <span m=''5007610''>of</span> <span m=''5008480''>3/4,</span>
  <span m=''5009470''>at</span> <span m=''5009570''>most</span> <span m=''5009870''>3/4,</span>
  <span m=''5011220''>the</span> <span m=''5011310''>size</span> <span m=''5012460''>plus</span>
  <span m=''5012730''>the</span> <span m=''5012810''>log</span> <span m=''5013230''>n</span>
  <span m=''5013440''>for</span> <span m=''5013560''>the</span> <span m=''5013660''>binary</span>
  <span m=''5014080''>search.</span> <span m=''5016380''>So</span> <span m=''5016520''>the</span>
  <span m=''5016620''>span</span> <span m=''5017080''>of</span> <span m=''5017170''>parallel</span>
  <span m=''5017610''>merge</span> <span m=''5018660''>is</span> <span m=''5018930''>therefore</span>
  <span m=''5019430''>order</span> <span m=''5019760''>log</span> <span m=''5020080''>squared</span>
  <span m=''5020500''>n,</span> <span m=''5021590''>because</span> <span m=''5022320''>the</span>
  <span m=''5022540''>important</span> <span m=''5022910''>thing</span> <span m=''5023040''>is,</span>
  <span m=''5023150''>I''m</span> <span m=''5023580''>whacking</span> <span m=''5024010''>off</span>
  <span m=''5024210''>a</span> <span m=''5024300''>constant</span> <span m=''5024780''>fraction</span>
  <span m=''5025250''>here</span> <span m=''5025490''>every</span> <span m=''5025720''>time.</span>
  <span m=''5026415''>So</span> <span m=''5026740''>I</span> <span m=''5026840''>get</span>
  <span m=''5027000''>log</span> <span m=''5027270''>squared</span> <span m=''5027690''>n</span>
  <span m=''5027850''>as</span> <span m=''5027990''>the</span> <span m=''5028070''>span,</span>
  <span m=''5029110''>and</span> <span m=''5029490''>the</span> <span m=''5029720''>work</span>
  <span m=''5030750''>I</span> <span m=''5030920''>get</span> <span m=''5031850''>this</span>
  <span m=''5032050''>hairy</span> <span m=''5032380''>recurrence,</span> <span m=''5034120''>that</span>
  <span m=''5034280''>it''s</span> <span m=''5034590''>t</span> <span m=''5034890''>of</span>
  <span m=''5034990''>alpha</span> <span m=''5035380''>n</span> <span m=''5036120''>plus</span>
  <span m=''5036790''>t1</span> <span m=''5037650''>minus</span> <span m=''5037970''>alpha</span>
  <span m=''5038270''>n</span> <span m=''5038560''>plus</span> <span m=''5038840''>log</span>
  <span m=''5039260''>n,</span> <span m=''5039850''>where</span> <span m=''5040030''>alpha</span>
  <span m=''5040350''>falls</span> <span m=''5040760''>in</span> <span m=''5040860''>this</span>
  <span m=''5041050''>range.</span> <span m=''5043920''>This</span> <span m=''5044110''>does</span>
  <span m=''5044260''>not</span> <span m=''5044480''>satisfy</span> <span m=''5044920''>the</span>
  <span m=''5045000''>Master</span> <span m=''5045350''>Theorem.</span> <span m=''5047700''>You</span>
  <span m=''5047800''>can</span> <span m=''5047890''>actually</span> <span m=''5048130''>do</span>
  <span m=''5048390''>this</span> <span m=''5048620''>pretty</span> <span m=''5048860''>easily</span>
  <span m=''5049280''>with</span> <span m=''5049450''>a</span> <span m=''5049510''>recursion</span>
  <span m=''5050080''>tree,</span> <span m=''5050820''>but</span> <span m=''5051040''>the</span>
  <span m=''5051130''>way</span> <span m=''5051260''>to</span> <span m=''5051390''>verify</span>
  <span m=''5051970''>is--</span> <span m=''5053270''>we</span> <span m=''5053390''>call</span>
  <span m=''5053600''>this</span> <span m=''5053900''>technically</span> <span m=''5054410''>a</span>
  <span m=''5054500''>hairy</span> <span m=''5054850''>recurrence.</span> <span m=''5056370''>That''s</span>
  <span m=''5056620''>the</span> <span m=''5056890''>technical</span> <span m=''5057410''>term</span>
  <span m=''5057740''>for</span> <span m=''5057990''>it.</span> <span m=''5060360''>So</span>
  <span m=''5060610''>it</span> <span m=''5060730''>turns</span> <span m=''5060970''>out,</span>
  <span m=''5061170''>this</span> <span m=''5061340''>has</span> <span m=''5061500''>order</span>
  <span m=''5061840''>n,</span> <span m=''5062860''>just</span> <span m=''5063110''>like</span>
  <span m=''5063370''>ordinary</span> <span m=''5063830''>merge,</span> <span m=''5065030''>order</span>
  <span m=''5065190''>n</span> <span m=''5065670''>time.</span> <span m=''5068010''>here''s</span>
  <span m=''5068570''>You</span> <span m=''5068800''>can</span> <span m=''5068890''>use</span>
  <span m=''5069080''>the</span> <span m=''5069160''>substitution</span> <span m=''5069840''>method,</span>
  <span m=''5070240''>and</span> <span m=''5070510''>I</span> <span m=''5070540''>won''t</span>
  <span m=''5070800''>drag</span> <span m=''5071170''>you</span> <span m=''5071330''>through</span>
  <span m=''5071630''>it,</span> <span m=''5071780''>but</span> <span m=''5071890''>you</span>
  <span m=''5071970''>can</span> <span m=''5072050''>look</span> <span m=''5072230''>at</span>
  <span m=''5072420''>it</span> <span m=''5072520''>in</span> <span m=''5072640''>the</span>
  <span m=''5072720''>notes.</span> <span m=''5075510''>And</span> <span m=''5075890''>this</span>
  <span m=''5076090''>should</span> <span m=''5076270''>be</span> <span m=''5076380''>very</span>
  <span m=''5076610''>familiar</span> <span m=''5077110''>to</span> <span m=''5077250''>you</span>
  <span m=''5077550''>as</span> <span m=''5078050''>having</span> <span m=''5078830''>all</span>
  <span m=''5079180''>aced</span> <span m=''5079650''>6006,</span> <span m=''5080660''>right?</span>
  <span m=''5083270''>Otherwise</span> <span m=''5083590''>you</span> <span m=''5083690''>wouldn''t</span>
  <span m=''5083840''>be</span> <span m=''5083970''>here,</span> <span m=''5084265''>right?</span>
  </p><p><span m=''5087930''>So</span> <span m=''5088090''>the</span> <span m=''5088170''>parallelism</span>
  <span m=''5089260''>of</span> <span m=''5089420''>the</span> <span m=''5089500''>parallel</span>
  <span m=''5089900''>merge</span> <span m=''5090900''>is</span> <span m=''5091240''>something</span>
  <span m=''5091640''>like</span> <span m=''5091970''>n</span> <span m=''5092170''>over</span>
  <span m=''5092390''>log</span> <span m=''5092660''>squared</span> <span m=''5093080''>n.</span>
  <span m=''5095670''>So</span> <span m=''5095800''>that''s</span> <span m=''5095970''>much</span>
  <span m=''5096200''>better</span> <span m=''5096930''>than</span> <span m=''5097280''>having</span>
  <span m=''5098380''>n</span> <span m=''5098540''>order</span> <span m=''5098870''>n</span>
  <span m=''5099720''>bound.</span> <span m=''5100510''>And</span> <span m=''5100670''>now,</span>
  <span m=''5100880''>we</span> <span m=''5101000''>can</span> <span m=''5101160''>plug</span>
  <span m=''5101450''>it</span> <span m=''5101520''>into</span> <span m=''5101750''>merge</span>
  <span m=''5102080''>sort.</span> <span m=''5103340''>So</span> <span m=''5103500''>the</span>
  <span m=''5103600''>work</span> <span m=''5103910''>is</span> <span m=''5104060''>going</span>
  <span m=''5104180''>to</span> <span m=''5104230''>be</span> <span m=''5104430''>the</span>
  <span m=''5104520''>same</span> <span m=''5104820''>as</span> <span m=''5104940''>before,</span>
  <span m=''5105430''>because</span> <span m=''5105590''>I</span> <span m=''5105690''>just</span>
  <span m=''5105920''>have</span> <span m=''5106040''>the</span> <span m=''5106130''>work</span>
  <span m=''5106540''>of</span> <span m=''5106720''>the</span> <span m=''5106810''>merge,</span>
  <span m=''5107170''>which</span> <span m=''5107320''>is</span> <span m=''5107400''>still</span>
  <span m=''5107670''>order</span> <span m=''5107960''>n.</span> <span m=''5108780''>So</span>
  <span m=''5109000''>the</span> <span m=''5109340''>work</span> <span m=''5109760''>is</span>
  <span m=''5110210''>order</span> <span m=''5110520''>n</span> <span m=''5110680''>log</span>
  <span m=''5111020''>n,</span> <span m=''5111190''>once</span> <span m=''5111450''>again</span>
  <span m=''5111670''>pulling</span> <span m=''5111990''>out</span> <span m=''5112110''>the</span>
  <span m=''5112190''>Master</span> <span m=''5112570''>Theorem.</span> <span m=''5113550''>And</span>
  <span m=''5113730''>then</span> <span m=''5113890''>the</span> <span m=''5113970''>span</span>
  <span m=''5115120''>is</span> <span m=''5118150''>n</span> <span m=''5118890''>over</span>
  <span m=''5119210''>2</span> <span m=''5120070''>plus</span> <span m=''5120350''>log
  n,</span> <span m=''5120890''>because</span> <span m=''5121360''>basically,</span>
  <span m=''5121660''>I</span> <span m=''5121960''>have</span> <span m=''5122090''>the</span>
  <span m=''5122220''>span</span> <span m=''5122800''>of</span> <span m=''5124090''>a</span>
  <span m=''5124190''>problem</span> <span m=''5124570''>of</span> <span m=''5124640''>half</span>
  <span m=''5124990''>the</span> <span m=''5125080''>size</span> <span m=''5126280''>plus</span>
  <span m=''5127140''>the</span> <span m=''5127230''>span</span> <span m=''5127590''>that</span>
  <span m=''5127700''>I</span> <span m=''5127780''>need</span> <span m=''5128060''>to</span>
  <span m=''5128150''>merge</span> <span m=''5128550''>things.</span> <span m=''5128910''>That''s</span>
  <span m=''5129140''>order</span> <span m=''5129390''>log</span> <span m=''5129680''>squared</span>
  <span m=''5130010''>n.</span> </p><p><span m=''5130660''>This</span> <span m=''5131000''>I</span>
  <span m=''5131040''>want</span> <span m=''5131210''>to</span> <span m=''5131260''>pause</span>
  <span m=''5131535''>on</span> <span m=''5131810''>for</span> <span m=''5131930''>moment.</span>
  <span m=''5132300''>People</span> <span m=''5132590''>get</span> <span m=''5133290''>this</span>
  <span m=''5133480''>recurrence?</span> <span m=''5135520''>Because</span> <span
  m=''5135690''>this</span> <span m=''5135860''>is</span> <span m=''5136020''>the</span>
  <span m=''5136110''>span</span> <span m=''5136610''>of</span> <span m=''5136840''>the</span>
  <span m=''5136940''>merge.</span> <span m=''5138230''>And</span> <span m=''5138380''>so</span>
  <span m=''5138560''>what</span> <span m=''5138710''>I</span> <span m=''5138830''>end</span>
  <span m=''5139070''>up</span> <span m=''5139260''>with</span> <span m=''5139500''>is</span>
  <span m=''5139640''>I</span> <span m=''5139720''>get</span> <span m=''5141160''>another</span>
  <span m=''5141540''>log,</span> <span m=''5142390''>log</span> <span m=''5142700''>cubed</span>
  <span m=''5142990''>n.</span> <span m=''5145310''>And</span> <span m=''5145500''>so</span>
  <span m=''5146230''>the</span> <span m=''5147470''>total</span> <span m=''5147800''>parallelism</span>
  <span m=''5148340''>is</span> <span m=''5148500''>n</span> <span m=''5148730''>over</span>
  <span m=''5148940''>log</span> <span m=''5149250''>squared</span> <span m=''5149640''>n.</span>
  <span m=''5150350''>And</span> <span m=''5150470''>this</span> <span m=''5150610''>is</span>
  <span m=''5150700''>actually</span> <span m=''5151050''>quite</span> <span m=''5151340''>a</span>
  <span m=''5151400''>practical</span> <span m=''5151970''>thing</span> <span m=''5152200''>to</span>
  <span m=''5152270''>implement,</span> <span m=''5155440''>to</span> <span m=''5155600''>get</span>
  <span m=''5155950''>the</span> <span m=''5156740''>n</span> <span m=''5156920''>over</span>
  <span m=''5157120''>log</span> <span m=''5157370''>squared</span> <span m=''5157780''>n</span>
  <span m=''5158080''>parallelism</span> <span m=''5158680''>versus</span> <span m=''5159640''>just</span>
  <span m=''5159860''>a</span> <span m=''5159980''>log n</span> <span m=''5160520''>parallelism.</span>
  <span m=''5162770''>We''re</span> <span m=''5162900''>not</span> <span m=''5163050''>going</span>
  <span m=''5163150''>to</span> <span m=''5163370''>do</span> <span m=''5163600''>tableau</span>
  <span m=''5163670''>construction.</span> <span m=''5164200''>You</span> <span m=''5164270''>can</span>
  <span m=''5164400''>read</span> <span m=''5164580''>that</span> <span m=''5164800''>up,</span>
  <span m=''5165120''>that''s</span> <span m=''5165350''>on</span> <span m=''5165770''>the</span>
  <span m=''5166310''>notes</span> <span m=''5166610''>that are</span> <span m=''5166700''>online,</span>
  <span m=''5167170''>but</span> <span m=''5167300''>you</span> <span m=''5167350''>should</span>
  <span m=''5167540''>read</span> <span m=''5167770''>through</span> <span m=''5168090''>that</span>
  <span m=''5170040''>part</span> <span m=''5170310''>of</span> <span m=''5170410''>it.</span>
  <span m=''5171010''>It''s</span> <span m=''5171260''>got</span> <span m=''5171450''>some</span>
  <span m=''5171550''>nice</span> <span m=''5171810''>animations</span> <span m=''5172420''>which
  you</span> <span m=''5172900''>don''t get</span> <span m=''5173120''>to see.</span>
  <span m=''5180630''>This is</span> <span m=''5181210''>like</span> <span m=''5181400''>when
  you</span> <span m=''5181490''>do</span> <span m=''5181710''>longest</span> <span
  m=''5182160''>common</span> <span m=''5182460''>subsequence</span> <span m=''5183150''>and</span>
  <span m=''5183240''>stuff</span> <span m=''5183530''>like</span> <span m=''5183710''>that,</span>
  <span m=''5183930''>how</span> <span m=''5184120''>you</span> <span m=''5184270''>would</span>
  <span m=''5184410''>solve</span> <span m=''5184690''>that</span> <span m=''5185190''>type</span>
  <span m=''5185460''>of</span> <span m=''5185560''>problem</span> <span m=''5185870''>in</span>
  <span m=''5185970''>parallel.</span> <span m=''5187110''>OK,</span> <span m=''5187450''>great.</span>
  </p>'
uid: b10ba5b4-b7fe-0a47-956d-67ad505deee1
---
