---
about_this_resource_text: <p><strong>Description:</strong> Lecture covering synchronizing
  without locks, including memory consistency, lock-free protocols, the ABA problem,
  and reducer hyperobjects.</p> <p><strong>Speaker:</strong> Charles Leiserson</p>
content_type: resource
course_id: 6-172-performance-engineering-of-software-systems-fall-2010
embedded_media:
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.172F10/MIT6_172_F10_lec16_300k.mp4
  parent_uid: b263e81725114d98eef9a09440703cdf
  title: Video-Internet Archive-MP4
  type: Video
  uid: 26939e9316be2364ecfad7cf6105e8a5
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/itunes-u/lecture-16-synchronizing-without/id481759887?i=109649254
  parent_uid: b263e81725114d98eef9a09440703cdf
  title: Video-iTunes U-MP4
  type: Video
  uid: fd4ca688031bba4de714448a58c0f707
- id: Video-YouTube-Stream
  media_location: n_Cqx8KamFA
  parent_uid: b263e81725114d98eef9a09440703cdf
  title: Video-YouTube-Stream
  type: Video
  uid: b4f97dccb7bcb46e10f96658c3f12235
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/n_Cqx8KamFA/default.jpg
  parent_uid: b263e81725114d98eef9a09440703cdf
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: ae33358bd1a8c1844bfe9fccade7d08e
- id: MIT6_172F10_lec16.pdf
  parent_uid: b263e81725114d98eef9a09440703cdf
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-16-synchronizing-without-locks/MIT6_172F10_lec16.pdf
  title: MIT6_172F10_lec16.pdf
  type: null
  uid: 722ec7c18cbb7f5748e5b2dd497ab6eb
- id: 3Play-3PlayYouTubeid-MP4
  media_location: n_Cqx8KamFA
  parent_uid: b263e81725114d98eef9a09440703cdf
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 3889bd63682063bfb9f1e83501510845
- id: n_Cqx8KamFA.srt
  parent_uid: b263e81725114d98eef9a09440703cdf
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-16-synchronizing-without-locks/n_Cqx8KamFA.srt
  title: 3play caption file
  type: null
  uid: a76300f1d5a87de203b4252f767b678a
- id: n_Cqx8KamFA.pdf
  parent_uid: b263e81725114d98eef9a09440703cdf
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-16-synchronizing-without-locks/n_Cqx8KamFA.pdf
  title: 3play pdf file
  type: null
  uid: 66d8025a2743f6fb65bf4f7456171c00
- id: Caption-3Play YouTube id-SRT
  parent_uid: b263e81725114d98eef9a09440703cdf
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 62f29ab381189d4cf5d13fabf640b0fc
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b263e81725114d98eef9a09440703cdf
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: aa17d40343bc809e8364309c8f39a189
file: null
file_size: null
hide_download: true
hide_download_original: null
inline_embed_id: 11306234lecture16:synchronizingwithoutlocks53713649
layout: video
license: https://creativecommons.org/licenses/by-nc-sa/4.0/
order_index: 181
parent_uid: 24169d0487e846a39c316276f85b8cb5
related_resources_text: ''
short_url: lecture-16-synchronizing-without-locks
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/video-lectures/lecture-16-synchronizing-without-locks
title: 'Lecture 16: Synchronizing without Locks'
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
  <span m=''17250''>at</span> <span m=''17430''>ocw.mit.edu.</span> </p><p><span m=''27980''>PROFESSOR:
  The</span> <span m=''28160''>last</span> <span m=''28530''>time</span> <span m=''29140''>we</span>
  <span m=''29340''>talked</span> <span m=''29600''>about</span> <span m=''29820''>nondeterministic</span>
  <span m=''30590''>programming.</span> <span m=''32400''>And</span> <span m=''35000''>I</span>
  <span m=''35130''>think</span> <span m=''35430''>actually</span> <span m=''35680''>the</span>
  <span m=''36120''>mic</span> <span m=''36350''>is</span> <span m=''36470''>up</span>
  <span m=''36550''>pretty</span> <span m=''36840''>high.</span> <span m=''37290''>If</span>
  <span m=''37560''>we</span> <span m=''37870''>can</span> <span m=''38570''>tone</span>
  <span m=''38790''>that</span> <span m=''38960''>down</span> <span m=''39190''>just</span>
  <span m=''39350''>a</span> <span m=''39380''>little</span> <span m=''39500''>bit.</span>
  <span m=''40740''>We</span> <span m=''40790''>talked</span> <span m=''40980''>about</span>
  <span m=''41190''>nondeterministic</span> <span m=''41980''>programming.</span>
  <span m=''43410''>And</span> <span m=''43820''>as</span> <span m=''43990''>you</span>
  <span m=''44070''>recall,</span> <span m=''45690''>the</span> <span m=''45860''>rule</span>
  <span m=''46140''>with</span> <span m=''46210''>nondeterministic</span> <span m=''47080''>programming</span>
  <span m=''47610''>is</span> <span m=''47710''>you</span> <span m=''47830''>should</span>
  <span m=''48060''>never</span> <span m=''48350''>do</span> <span m=''48600''>it</span>
  <span m=''49630''>unless</span> <span m=''49980''>you</span> <span m=''50060''>have</span>
  <span m=''50340''>to.</span> </p><p><span m=''53800''>Today</span> <span m=''54170''>we''re</span>
  <span m=''54300''>going</span> <span m=''54390''>to</span> <span m=''54480''>talk</span>
  <span m=''54720''>about</span> <span m=''55000''>synchronizing</span> <span m=''55670''>with</span>
  <span m=''55790''>locks.</span> <span m=''56730''>And</span> <span m=''57180''>it</span>
  <span m=''57410''>goes</span> <span m=''57810''>doubly</span> <span m=''58270''>that</span>
  <span m=''58440''>you</span> <span m=''58530''>should</span> <span m=''58750''>never</span>
  <span m=''59020''>synchronize</span> <span m=''59730''>without</span> <span m=''60090''>locks</span>
  <span m=''61370''>unless</span> <span m=''61650''>you</span> <span m=''61740''>have</span>
  <span m=''62070''>to.</span> <span m=''64569''>There''s</span> <span m=''64810''>some</span>
  <span m=''64950''>good</span> <span m=''65129''>reasons</span> <span m=''65660''>for</span>
  <span m=''66610''>synchronizing</span> <span m=''66890''>without</span> <span m=''67240''>locks
  as</span> <span m=''67640''>we''ll</span> <span m=''67760''>see.</span> <span m=''70620''>But</span>
  <span m=''71840''>it,</span> <span m=''72010''>once</span> <span m=''72290''>again,</span>
  <span m=''72630''>becomes</span> <span m=''73010''>even</span> <span m=''73290''>more</span>
  <span m=''73620''>difficult</span> <span m=''74380''>to</span> <span m=''74530''>test</span>
  <span m=''74910''>correctness</span> <span m=''75760''>and</span> <span m=''76030''>to</span>
  <span m=''76150''>ensure</span> <span m=''77060''>that</span> <span m=''77210''>the</span>
  <span m=''77300''>program</span> <span m=''77890''>that</span> <span m=''79250''>you</span>
  <span m=''79320''>think</span> <span m=''79550''>you''ve</span> <span m=''79730''>written</span>
  <span m=''80020''>is,</span> <span m=''80170''>in</span> <span m=''80280''>fact,</span>
  <span m=''80670''>the</span> <span m=''80960''>program</span> <span m=''81310''>you</span>
  <span m=''81400''>meant</span> <span m=''81610''>to</span> <span m=''81730''>write.</span>
  </p><p><span m=''82860''>So</span> <span m=''83290''>we''re going</span> <span m=''83450''>to
  talk</span> <span m=''83850''>about</span> <span m=''84350''>a</span> <span m=''84770''>bunch</span>
  <span m=''85120''>of</span> <span m=''86260''>really</span> <span m=''86520''>important</span>
  <span m=''86960''>topics.</span> <span m=''87870''>The</span> <span m=''87960''>first</span>
  <span m=''88310''>is</span> <span m=''88420''>memory</span> <span m=''88770''>consistency.</span>
  <span m=''90630''>And</span> <span m=''90860''>then</span> <span m=''91020''>we''ll</span>
  <span m=''91140''>talk</span> <span m=''91370''>a</span> <span m=''91410''>little</span>
  <span m=''91590''>bit</span> <span m=''91700''>about</span> <span m=''91960''>lock</span>
  <span m=''92350''>free</span> <span m=''92540''>protocols</span> <span m=''93480''>and</span>
  <span m=''93780''>one</span> <span m=''93920''>of</span> <span m=''93960''>the</span>
  <span m=''94040''>problems</span> <span m=''94480''>that</span> <span m=''94630''>arises</span>
  <span m=''95100''>called</span> <span m=''95280''>the</span> <span m=''95410''>AVA</span>
  <span m=''95870''>problem.</span> <span m=''96800''>And</span> <span m=''96930''>then</span>
  <span m=''97020''>we''re</span> <span m=''97140''>going</span> <span m=''97220''>to</span>
  <span m=''97300''>talk</span> <span m=''97610''>about</span> <span m=''98060''>a</span>
  <span m=''99550''>technology</span> <span m=''100270''>that</span> <span m=''100470''>we''re</span>
  <span m=''100700''>using</span> <span m=''101400''>in</span> <span m=''102060''>the</span>
  <span m=''102490''>Cilk++</span> <span m=''103460''>system,</span> <span m=''104450''>which</span>
  <span m=''104990''>tries</span> <span m=''105490''>to</span> <span m=''105610''>make</span>
  <span m=''105860''>an</span> <span m=''105950''>end</span> <span m=''106850''>run</span>
  <span m=''107180''>around</span> <span m=''107550''>some</span> <span m=''107740''>of</span>
  <span m=''107790''>these</span> <span m=''107990''>problems</span> <span m=''108740''>and</span>
  <span m=''110940''>allows</span> <span m=''111590''>you</span> <span m=''111790''>to</span>
  <span m=''111990''>do</span> <span m=''112180''>synchronization</span> <span m=''112950''>without</span>
  <span m=''113280''>locks,</span> <span m=''114140''>with</span> <span m=''114280''>low</span>
  <span m=''114500''>overhead.</span> <span m=''115410''>But</span> <span m=''115520''>it</span>
  <span m=''115590''>only</span> <span m=''115840''>works</span> <span m=''116780''>in</span>
  <span m=''117450''>certain</span> <span m=''117840''>context.</span> </p><p><span
  m=''119810''>So we''re going to</span> <span m=''119880''>start</span> <span m=''120180''>with</span>
  <span m=''120310''>memory</span> <span m=''120610''>consistency.</span> <span m=''125240''>So</span>
  <span m=''126210''>here</span> <span m=''126490''>is</span> <span m=''126640''>a</span>
  <span m=''127250''>very</span> <span m=''127690''>simple</span> <span m=''128740''>parallel</span>
  <span m=''129180''>program.</span> <span m=''129729''>So</span> <span m=''129860''>initially</span>
  <span m=''130430''>a</span> <span m=''130660''>and</span> <span m=''130840''>b</span>
  <span m=''131039''>are</span> <span m=''131100''>both</span> <span m=''131400''>0.</span>
  <span m=''132870''>And</span> <span m=''133080''>processor</span> <span m=''133680''>zero</span>
  <span m=''134140''>moves</span> <span m=''134490''>a</span> <span m=''134560''>1</span>
  <span m=''135100''>into a.</span> <span m=''137250''>And</span> <span m=''137510''>then</span>
  <span m=''137980''>it</span> <span m=''138270''>moves</span> <span m=''139270''>whatever</span>
  <span m=''139780''>is</span> <span m=''140190''>in</span> <span m=''141240''>location</span>
  <span m=''141830''>b</span> <span m=''142360''>into</span> <span m=''142860''>the</span>
  <span m=''143120''>EBX</span> <span m=''143720''>register.</span> </p><p><span m=''146240''>Processor</span>
  <span m=''146780''>one</span> <span m=''147180''>does</span> <span m=''147340''>something</span>
  <span m=''147940''>complementary.</span> <span m=''149070''>It</span> <span m=''149230''>moves</span>
  <span m=''149490''>a</span> <span m=''149570''>1</span> <span m=''149800''>into</span>
  <span m=''150000''>b.</span> <span m=''151050''>And</span> <span m=''151260''>then</span>
  <span m=''151490''>it</span> <span m=''151660''>moves</span> <span m=''153520''>whatever</span>
  <span m=''153930''>is</span> <span m=''154040''>in</span> <span m=''154360''>a</span>
  <span m=''154680''>into</span> <span m=''154920''>the</span> <span m=''156520''>EAX</span>
  <span m=''157050''>register.</span> <span m=''159040''>Into the</span> <span m=''159430''>EAX</span>
  <span m=''159840''>register</span> <span m=''160260''>as opposed</span> <span m=''160360''>to
  the</span> <span m=''160630''>EBX</span> <span m=''161040''>register.</span> </p><p><span
  m=''162090''>And</span> <span m=''162950''>the</span> <span m=''163060''>question</span>
  <span m=''163550''>is</span> <span m=''165320''>what</span> <span m=''165690''>are</span>
  <span m=''165820''>the</span> <span m=''166000''>final</span> <span m=''166610''>possible</span>
  <span m=''167190''>values</span> <span m=''168350''>of</span> <span m=''168870''>EAX</span>
  <span m=''169650''>and</span> <span m=''169860''>EBX</span> <span m=''170960''>after</span>
  <span m=''171030''>both</span> <span m=''171350''>processors</span> <span m=''172010''>have</span>
  <span m=''172160''>executed.</span> <span m=''173860''>Seems</span> <span m=''174150''>like</span>
  <span m=''174320''>a</span> <span m=''174380''>straightforward</span> <span m=''175000''>enough</span>
  <span m=''175240''>question.</span> <span m=''178470''>What</span> <span m=''178720''>values</span>
  <span m=''179480''>can</span> <span m=''180010''>EAX</span> <span m=''180580''>and</span>
  <span m=''180680''>EBX</span> <span m=''181300''>have,</span> <span m=''182330''>depending</span>
  <span m=''182690''>upon--</span> <span m=''183040''>there</span> <span m=''183320''>may</span>
  <span m=''183470''>be</span> <span m=''183600''>scheduling</span> <span m=''184310''>of</span>
  <span m=''184460''>when</span> <span m=''184760''>things</span> <span m=''185040''>happen</span>
  <span m=''185410''>and</span> <span m=''185530''>so</span> <span m=''185750''>forth.</span>
  <span m=''187400''>So</span> <span m=''187550''>it''s</span> <span m=''187650''>not</span>
  <span m=''187830''>always</span> <span m=''188050''>going</span> <span m=''188150''>to</span>
  <span m=''188190''>give</span> <span m=''188370''>the</span> <span m=''188450''>same</span>
  <span m=''188840''>answer.</span> <span m=''189320''>But</span> <span m=''189550''>the</span>
  <span m=''189640''>question</span> <span m=''189950''>is</span> <span m=''190040''>what''s</span>
  <span m=''190250''>the</span> <span m=''190330''>set</span> <span m=''190660''>of</span>
  <span m=''190770''>answers</span> <span m=''191550''>that</span> <span m=''191690''>you</span>
  <span m=''191820''>can</span> <span m=''191950''>get?</span> </p><p><span m=''192720''>Well,</span>
  <span m=''192910''>it</span> <span m=''192970''>turns</span> <span m=''193240''>out</span>
  <span m=''193360''>you</span> <span m=''193470''>can''t</span> <span m=''193770''>just</span>
  <span m=''194020''>answer</span> <span m=''194360''>this</span> <span m=''194590''>question</span>
  <span m=''195080''>for</span> <span m=''195230''>any</span> <span m=''195450''>particular</span>
  <span m=''196270''>machine</span> <span m=''198060''>without</span> <span m=''198520''>knowing</span>
  <span m=''198850''>the</span> <span m=''198940''>machine''s</span> <span m=''199970''>memory</span>
  <span m=''200340''>model.</span> <span m=''202370''>So</span> <span m=''202550''>it</span>
  <span m=''202640''>depends</span> <span m=''203040''>upon</span> <span m=''203380''>how</span>
  <span m=''203570''>memory</span> <span m=''204500''>operations</span> <span m=''205250''>behave</span>
  <span m=''205780''>in</span> <span m=''205860''>the</span> <span m=''205940''>parallel</span>
  <span m=''206350''>computer</span> <span m=''206770''>system.</span> <span m=''208290''>And</span>
  <span m=''208490''>different</span> <span m=''208770''>machines</span> <span m=''209290''>have</span>
  <span m=''209440''>different</span> <span m=''209770''>memory</span> <span m=''210090''>models.</span>
  <span m=''211070''>And</span> <span m=''211200''>we''ll</span> <span m=''211340''>give</span>
  <span m=''211540''>you</span> <span m=''211710''>different</span> <span m=''212090''>answers</span>
  <span m=''213530''>for</span> <span m=''214740''>this</span> <span m=''215180''>code.</span>
  <span m=''215450''>There''ll</span> <span m=''215530''>be</span> <span m=''215650''>some</span>
  <span m=''215910''>answers</span> <span m=''216270''>that you</span> <span m=''216440''>get</span>
  <span m=''216600''>on</span> <span m=''216720''>some</span> <span m=''216940''>machines,</span>
  <span m=''217660''>different</span> <span m=''217940''>answers</span> <span m=''218380''>on</span>
  <span m=''218510''>different</span> <span m=''218800''>machines.</span> </p><p><span
  m=''222620''>So</span> <span m=''223390''>probably</span> <span m=''224080''>the</span>
  <span m=''225520''>bedrock</span> <span m=''226600''>of</span> <span m=''227160''>memory</span>
  <span m=''227520''>models</span> <span m=''228130''>is</span> <span m=''228490''>a</span>
  <span m=''228580''>model</span> <span m=''228930''>called</span> <span m=''229200''>sequential</span>
  <span m=''229730''>consistency.</span> <span m=''231750''>And</span> <span m=''231890''>this</span>
  <span m=''232060''>is</span> <span m=''232210''>intuitively</span> <span m=''233520''>what</span>
  <span m=''233730''>you</span> <span m=''233830''>might</span> <span m=''234770''>think</span>
  <span m=''235020''>you</span> <span m=''235140''>want.</span> <span m=''238470''>So</span>
  <span m=''238920''>Lamport</span> <span m=''239340''>in 1979</span> <span m=''240220''>said,</span>
  <span m=''240380''>&quot;The</span> <span m=''240550''>result</span> <span m=''240815''>of</span>
  <span m=''241080''>any</span> <span m=''241390''>execution</span> <span m=''242150''>is</span>
  <span m=''242300''>the</span> <span m=''242390''>same</span> <span m=''242780''>as</span>
  <span m=''242920''>if</span> <span m=''243030''>the</span> <span m=''243150''>operations</span>
  <span m=''243900''>of</span> <span m=''244020''>all</span> <span m=''244230''>the</span>
  <span m=''244310''>processors</span> <span m=''245430''>were</span> <span m=''245650''>executed</span>
  <span m=''246240''>in</span> <span m=''246370''>some</span> <span m=''246660''>sequential</span>
  <span m=''247240''>order,</span> <span m=''248030''>and</span> <span m=''248140''>the</span>
  <span m=''248260''>operations</span> <span m=''248870''>of</span> <span m=''248940''>each</span>
  <span m=''249140''>individual</span> <span m=''249660''>processor</span> <span m=''250320''>appear</span>
  <span m=''250660''>in</span> <span m=''250730''>this</span> <span m=''250900''>sequence</span>
  <span m=''251760''>in</span> <span m=''251930''>the</span> <span m=''252060''>order</span>
  <span m=''252410''>specified</span> <span m=''253140''>by</span> <span m=''253310''>its</span>
  <span m=''253470''>program.&quot;</span> </p><p><span m=''255380''>So</span> <span
  m=''255530''>what</span> <span m=''255660''>does</span> <span m=''255770''>that</span>
  <span m=''256010''>mean?</span> <span m=''257579''>So</span> <span m=''258760''>what</span>
  <span m=''258959''>it</span> <span m=''259100''>says</span> <span m=''259579''>is</span>
  <span m=''260800''>that</span> <span m=''261550''>if</span> <span m=''261760''>I</span>
  <span m=''261910''>look</span> <span m=''262460''>at</span> <span m=''262720''>the</span>
  <span m=''262790''>processor''s</span> <span m=''263560''>program</span> <span m=''264110''>and</span>
  <span m=''264180''>the</span> <span m=''264250''>sequence</span> <span m=''264780''>of</span>
  <span m=''264880''>operations</span> <span m=''265690''>that</span> <span m=''265800''>are</span>
  <span m=''265880''>issued</span> <span m=''266340''>by</span> <span m=''266510''>that</span>
  <span m=''266900''>processor''s</span> <span m=''267530''>program,</span> <span
  m=''269560''>they''re</span> <span m=''269760''>interleaved</span> <span m=''271270''>with</span>
  <span m=''271680''>the</span> <span m=''271780''>corresponding</span> <span m=''272550''>sequences</span>
  <span m=''273210''>defined</span> <span m=''273640''>by</span> <span m=''273790''>the</span>
  <span m=''273940''>other</span> <span m=''274230''>processors</span> <span m=''276130''>to</span>
  <span m=''276270''>produce</span> <span m=''276710''>a</span> <span m=''276790''>global</span>
  <span m=''277990''>linear</span> <span m=''278410''>order.</span> <span m=''281600''>So</span>
  <span m=''281970''>the</span> <span m=''282200''>first</span> <span m=''282430''>thing</span>
  <span m=''282710''>is</span> <span m=''282870''>that</span> <span m=''282980''>there''s</span>
  <span m=''283170''>a</span> <span m=''283230''>global</span> <span m=''283580''>linear</span>
  <span m=''284110''>order</span> <span m=''284470''>that</span> <span m=''284620''>consists</span>
  <span m=''285160''>of</span> <span m=''285370''>all</span> <span m=''285720''>of</span>
  <span m=''285820''>these</span> <span m=''286040''>processors''</span> <span m=''286670''>instructions</span>
  <span m=''287670''>being</span> <span m=''287900''>interleaved.</span> </p><p><span
  m=''291850''>In</span> <span m=''292110''>this</span> <span m=''292340''>linear</span>
  <span m=''292670''>order,</span> <span m=''293140''>whenever</span> <span m=''293580''>you</span>
  <span m=''293800''>perform</span> <span m=''294310''>a</span> <span m=''294380''>load</span>
  <span m=''295560''>from</span> <span m=''295790''>memory</span> <span m=''296190''>into</span>
  <span m=''296490''>register,</span> <span m=''298090''>it</span> <span m=''298240''>receives</span>
  <span m=''298850''>the</span> <span m=''298940''>value</span> <span m=''299410''>that</span>
  <span m=''299560''>was</span> <span m=''299700''>stored</span> <span m=''300330''>by</span>
  <span m=''300480''>the</span> <span m=''300770''>most</span> <span m=''301170''>recent</span>
  <span m=''301660''>store</span> <span m=''302320''>operation</span> <span m=''303110''>in</span>
  <span m=''303290''>that</span> <span m=''303550''>linear</span> <span m=''303910''>order</span>
  <span m=''305200''>to</span> <span m=''305530''>that</span> <span m=''305920''>location,</span>
  <span m=''307700''>i.e.</span> <span m=''308100''>it''s</span> <span m=''308270''>memory.</span>
  <span m=''311680''>So</span> <span m=''311900''>you</span> <span m=''312040''>don''t</span>
  <span m=''312330''>get</span> <span m=''312550''>something</span> <span m=''313110''>if</span>
  <span m=''313490''>you</span> <span m=''313630''>have</span> <span m=''313930''>in</span>
  <span m=''314050''>this</span> <span m=''314240''>linear</span> <span m=''314560''>order</span>
  <span m=''317060''>that</span> <span m=''317560''>two</span> <span m=''317910''>processors</span>
  <span m=''318680''>wrote.</span> <span m=''319480''>Well,</span> <span m=''319750''>one</span>
  <span m=''319940''>of</span> <span m=''320040''>them</span> <span m=''320250''>came</span>
  <span m=''320780''>last.</span> <span m=''321780''>The</span> <span m=''321880''>most</span>
  <span m=''322200''>recent</span> <span m=''322600''>one</span> <span m=''322790''>before</span>
  <span m=''323220''>you</span> <span m=''323380''>read,</span> <span m=''323920''>that''s</span>
  <span m=''324240''>the</span> <span m=''324340''>one</span> <span m=''324650''>that
  you</span> <span m=''324800''>get.</span> </p><p><span m=''326490''>Now,</span>
  <span m=''326590''>there</span> <span m=''326690''>may</span> <span m=''326860''>be</span>
  <span m=''327000''>many</span> <span m=''327280''>different</span> <span m=''327580''>interleavings</span>
  <span m=''328340''>and</span> <span m=''328510''>so</span> <span m=''328720''>forth.</span>
  <span m=''329060''>And</span> <span m=''329170''>you</span> <span m=''329290''>could</span>
  <span m=''329490''>get</span> <span m=''329760''>any</span> <span m=''330050''>of</span>
  <span m=''330150''>the</span> <span m=''330230''>values</span> <span m=''331500''>that</span>
  <span m=''331620''>correspond</span> <span m=''332220''>to</span> <span m=''332290''>any</span>
  <span m=''332520''>of</span> <span m=''332650''>those</span> <span m=''332790''>interleavings.</span>
  <span m=''333430''>But</span> <span m=''333560''>the</span> <span m=''333630''>point</span>
  <span m=''333940''>is</span> <span m=''335350''>that</span> <span m=''336020''>you</span>
  <span m=''336190''>must</span> <span m=''336510''>get</span> <span m=''336660''>a</span>
  <span m=''336700''>value</span> <span m=''337180''>that</span> <span m=''337290''>is</span>
  <span m=''337350''>represented</span> <span m=''338170''>by</span> <span m=''338350''>some</span>
  <span m=''338750''>interleaving.</span> </p><p><span m=''342230''>The</span> <span
  m=''342300''>hardware</span> <span m=''342830''>can</span> <span m=''342960''>then</span>
  <span m=''343230''>do</span> <span m=''343380''>anything</span> <span m=''343770''>it</span>
  <span m=''343890''>wants,</span> <span m=''344820''>but</span> <span m=''345050''>for</span>
  <span m=''345130''>the</span> <span m=''345240''>execution</span> <span m=''345990''>to</span>
  <span m=''346100''>satisfy</span> <span m=''347010''>the</span> <span m=''347100''>sequential</span>
  <span m=''347680''>consistency</span> <span m=''348370''>model,</span> <span m=''349290''>for</span>
  <span m=''349600''>it to</span> <span m=''349680''>be</span> <span m=''349810''>sequentially</span>
  <span m=''350940''>consistent,</span> <span m=''351470''>must</span> <span m=''351750''>appear</span>
  <span m=''352160''>as</span> <span m=''352460''>if</span> <span m=''352800''>the</span>
  <span m=''352890''>loads</span> <span m=''353190''>and</span> <span m=''353300''>storage</span>
  <span m=''353970''>obey</span> <span m=''354760''>some</span> <span m=''355640''>global</span>
  <span m=''356300''>linear</span> <span m=''356770''>order.</span> <span m=''358950''>So</span>
  <span m=''359150''>let''s</span> <span m=''359430''>be</span> <span m=''359640''>concrete</span>
  <span m=''360150''>about</span> <span m=''360480''>that</span> <span m=''361480''>with</span>
  <span m=''361710''>the</span> <span m=''362910''>problem</span> <span m=''363320''>that</span>
  <span m=''363660''>I</span> <span m=''363760''>gave</span> <span m=''364050''>before.</span>
  <span m=''364580''>So</span> <span m=''364760''>initially,</span> <span m=''365990''>we</span>
  <span m=''366160''>have</span> <span m=''366500''>a</span> <span m=''366700''>and</span>
  <span m=''366860''>b</span> <span m=''367050''>are</span> <span m=''367150''>0.</span>
  <span m=''367840''>And</span> <span m=''368040''>now,</span> <span m=''368320''>we</span>
  <span m=''368480''>have</span> <span m=''368730''>these</span> <span m=''368980''>instructions</span>
  <span m=''369640''>executed.</span> </p><p><span m=''370620''>So</span> <span m=''370810''>what
  I</span> <span m=''370910''>have</span> <span m=''371110''>to</span> <span m=''371230''>do</span>
  <span m=''371510''>is</span> <span m=''372140''>say,</span> <span m=''372610''>I</span>
  <span m=''372740''>get</span> <span m=''373080''>any</span> <span m=''373350''>possible</span>
  <span m=''373970''>outcome</span> <span m=''375020''>based</span> <span m=''375360''>on</span>
  <span m=''375560''>interleaving</span> <span m=''376200''>these</span> <span m=''376430''>instructions</span>
  <span m=''377170''>in</span> <span m=''377260''>this</span> <span m=''377360''>order.</span>
  <span m=''378980''>So</span> <span m=''379220''>if</span> <span m=''379320''>I</span>
  <span m=''379410''>look</span> <span m=''379650''>at</span> <span m=''379790''>it,</span>
  <span m=''379940''>I''ve</span> <span m=''380130''>got</span> <span m=''380460''>two</span>
  <span m=''380600''>instructions</span> <span m=''381210''>here,</span> <span m=''381890''>two</span>
  <span m=''382100''>over</span> <span m=''382350''>here.</span> <span m=''383160''>So</span>
  <span m=''383360''>that there</span> <span m=''383720''>are</span> <span m=''383770''>six</span>
  <span m=''384180''>possible</span> <span m=''384800''>interleavings</span> <span
  m=''387040''>because</span> <span m=''387420''>4</span> <span m=''387710''>choose</span>
  <span m=''388040''>2</span> <span m=''388280''>is</span> <span m=''388400''>6</span>
  <span m=''389590''>for</span> <span m=''389680''>those</span> <span m=''389920''>people</span>
  <span m=''390200''>who''ve</span> <span m=''390430''>taken</span> <span m=''390780''>6042.</span>
  <span m=''393270''>So</span> <span m=''393490''>there are</span> <span m=''393680''>six</span>
  <span m=''393940''>possible</span> <span m=''394450''>interleavings.</span> </p><p><span
  m=''395660''>So</span> <span m=''395860''>for</span> <span m=''395960''>example,</span>
  <span m=''396500''>if</span> <span m=''396610''>I</span> <span m=''396740''>execute</span>
  <span m=''397410''>first</span> <span m=''398760''>move</span> <span m=''399065''>a</span>
  <span m=''399370''>1</span> <span m=''399630''>into</span> <span m=''399890''>a,</span>
  <span m=''401100''>and</span> <span m=''401330''>then</span> <span m=''401580''>I</span>
  <span m=''401850''>execute</span> <span m=''403030''>move</span> <span m=''404810''>load</span>
  <span m=''405450''>into</span> <span m=''407000''>register,</span> <span m=''408050''>the</span>
  <span m=''408310''>value</span> <span m=''408710''>of</span> <span m=''408890''>b,</span>
  <span m=''410180''>and</span> <span m=''410330''>then</span> <span m=''410560''>I</span>
  <span m=''410750''>move</span> <span m=''411290''>1</span> <span m=''411610''>into</span>
  <span m=''411830''>b,</span> <span m=''412360''>and</span> <span m=''412530''>then</span>
  <span m=''412680''>I</span> <span m=''412770''>load</span> <span m=''413010''>the</span>
  <span m=''413090''>value</span> <span m=''413470''>of</span> <span m=''413590''>a,</span>
  <span m=''413990''>I</span> <span m=''414130''>get</span> <span m=''414250''>a</span>
  <span m=''414380''>value</span> <span m=''415300''>of</span> <span m=''415500''>1</span>
  <span m=''415950''>for</span> <span m=''416250''>EAX</span> <span m=''416950''>and</span>
  <span m=''417160''>a</span> <span m=''417210''>value</span> <span m=''417680''>of
  0</span> <span m=''418100''>for</span> <span m=''419220''>EBX.</span> <span m=''419940''>For</span>
  <span m=''420020''>this</span> <span m=''420230''>particular</span> <span m=''420880''>interleaving</span>
  <span m=''421590''>of</span> <span m=''421690''>those</span> <span m=''421960''>instructions.</span>
  </p><p><span m=''425310''>That''s</span> <span m=''425540''>what</span> <span m=''425670''>happens</span>
  <span m=''425990''>if</span> <span m=''426090''>I</span> <span m=''426190''>execute</span>
  <span m=''426600''>these</span> <span m=''426930''>two</span> <span m=''427070''>before</span>
  <span m=''427460''>these</span> <span m=''427700''>two.</span> <span m=''427850''>If</span>
  <span m=''427960''>I</span> <span m=''428070''>execute</span> <span m=''428690''>these</span>
  <span m=''429080''>two</span> <span m=''430680''>instructions</span> <span m=''431310''>here</span>
  <span m=''431890''>before</span> <span m=''432250''>these</span> <span m=''432600''>two</span>
  <span m=''432820''>here,</span> <span m=''433610''>I</span> <span m=''433730''>get</span>
  <span m=''433890''>the</span> <span m=''433990''>order</span> <span m=''434230''>3412.</span>
  <span m=''435840''>And</span> <span m=''435950''>essentially,</span> <span m=''436330''>the</span>
  <span m=''436420''>opposite</span> <span m=''436940''>thing</span> <span m=''437130''>happens.</span>
  <span m=''437780''>EAX</span> <span m=''438370''>gets</span> <span m=''438620''>0</span>
  <span m=''439300''>and</span> <span m=''439580''>EBX</span> <span m=''440060''>gets</span>
  <span m=''440320''>1.</span> <span m=''441870''>And</span> <span m=''442020''>then,</span>
  <span m=''442140''>if</span> <span m=''442380''>I</span> <span m=''442570''>interleave</span>
  <span m=''442920''>them</span> <span m=''443090''>in</span> <span m=''443260''>some</span>
  <span m=''443600''>way,</span> <span m=''444710''>where</span> <span m=''445520''>1</span>
  <span m=''445940''>and</span> <span m=''446180''>3</span> <span m=''446850''>somehow</span>
  <span m=''447390''>come</span> <span m=''447630''>first</span> <span m=''448200''>before</span>
  <span m=''448710''>I</span> <span m=''448790''>do</span> <span m=''449070''>the</span>
  <span m=''449740''>2</span> <span m=''450010''>and</span> <span m=''450140''>4,</span>
  <span m=''450940''>then</span> <span m=''451120''>I''ll</span> <span m=''451280''>get</span>
  <span m=''451460''>a</span> <span m=''451510''>value</span> <span m=''452030''>of</span>
  <span m=''452560''>11</span> <span m=''452840''>for</span> <span m=''453010''>each</span>
  <span m=''453190''>of</span> <span m=''453300''>them.</span> <span m=''454030''>Those</span>
  <span m=''454270''>are</span> <span m=''454370''>the middle</span> <span m=''454640''>cases.</span>
  </p><p><span m=''457060''>So</span> <span m=''457520''>what</span> <span m=''457770''>don''t</span>
  <span m=''458280''>I</span> <span m=''458540''>get?</span> </p><p><span m=''459386''>AUDIENCE:
  00</span> </p><p><span m=''460360''>PROFESSOR: You</span> <span m=''460500''>never</span>
  <span m=''460870''>gets</span> <span m=''461290''>00</span> <span m=''462470''>in</span>
  <span m=''462570''>a</span> <span m=''462670''>sequentially</span> <span m=''463350''>consistent</span>
  <span m=''463960''>execution.</span> <span m=''466120''>Sequential</span> <span
  m=''466930''>consistent</span> <span m=''467370''>implies</span> <span m=''467790''>that</span>
  <span m=''468000''>no</span> <span m=''468250''>execution--</span> <span m=''469680''>whoops,</span>
  <span m=''469840''>that</span> <span m=''470080''>should</span> <span m=''470440''>be</span>
  <span m=''470780''>EAX.</span> <span m=''472730''>That</span> <span m=''472930''>EAX</span>
  <span m=''473670''>equals</span> <span m=''474100''>EBX</span> <span m=''474780''>equals</span>
  <span m=''475140''>0.</span> <span m=''476220''>I</span> <span m=''476410''>don''t</span>
  <span m=''476700''>ever</span> <span m=''477010''>get</span> <span m=''477330''>that</span>
  <span m=''478350''>outcome.</span> <span m=''479450''>If</span> <span m=''479630''>I</span>
  <span m=''479740''>did,</span> <span m=''480880''>then</span> <span m=''481040''>I</span>
  <span m=''481100''>would</span> <span m=''481250''>say</span> <span m=''481470''>my</span>
  <span m=''481620''>machine</span> <span m=''482170''>wasn''t</span> <span m=''483000''>sequentially</span>
  <span m=''483610''>consistent.</span> </p><p><span m=''487020''>So</span> <span
  m=''487160''>now</span> <span m=''487310''>let</span> <span m=''487480''>me</span>
  <span m=''487600''>take</span> <span m=''487870''>a</span> <span m=''487960''>detour</span>
  <span m=''488520''>a</span> <span m=''488560''>little</span> <span m=''488770''>bit</span>
  <span m=''489170''>to</span> <span m=''489330''>look</span> <span m=''489780''>at</span>
  <span m=''490930''>mutual</span> <span m=''491360''>exclusion</span> <span m=''491960''>again.</span>
  <span m=''494640''>And</span> <span m=''495160''>understand</span> <span m=''496760''>what</span>
  <span m=''496900''>happens</span> <span m=''497330''>to</span> <span m=''497430''>mutual</span>
  <span m=''497690''>exclusion</span> <span m=''498220''>algorithms</span> <span m=''498750''>in</span>
  <span m=''498890''>the</span> <span m=''498980''>context</span> <span m=''500100''>of</span>
  <span m=''500270''>memory</span> <span m=''500580''>consistency.</span> <span m=''501280''>So</span>
  <span m=''501430''>everybody</span> <span m=''501830''>understood</span> <span m=''502320''>what</span>
  <span m=''502490''>sequential</span> <span m=''502910''>consistency</span> <span
  m=''503520''>is.</span> <span m=''504100''>I</span> <span m=''504250''>simply</span>
  <span m=''504630''>look</span> <span m=''504880''>at</span> <span m=''504960''>my</span>
  <span m=''505110''>program</span> <span m=''505580''>as</span> <span m=''505730''>if</span>
  <span m=''505860''>I''m</span> <span m=''506320''>interleaving</span> <span m=''506690''>instructions.</span>
  </p><p><span m=''512510''>So</span> <span m=''512679''>most</span> <span m=''513140''>implementations</span>
  <span m=''514200''>of</span> <span m=''514330''>mutual</span> <span m=''514710''>exclusion,</span>
  <span m=''515470''>as</span> <span m=''515730''>I</span> <span m=''516350''>showed</span>
  <span m=''517440''>previously,</span> <span m=''518700''>employ</span> <span m=''519090''>some</span>
  <span m=''519419''>kind</span> <span m=''519700''>of</span> <span m=''519789''>atomic</span>
  <span m=''520950''>read-modify-write.</span> <span m=''522530''>So</span> <span
  m=''522679''>the</span> <span m=''522830''>example</span> <span m=''523299''>I</span>
  <span m=''523370''>gave</span> <span m=''523720''>you</span> <span m=''523909''>last</span>
  <span m=''524300''>time</span> <span m=''525110''>was</span> <span m=''526030''>using</span>
  <span m=''526660''>the</span> <span m=''526850''>exchange</span> <span m=''528130''>operation</span>
  <span m=''529350''>to</span> <span m=''529910''>atomically</span> <span m=''530660''>exchange</span>
  <span m=''531300''>a</span> <span m=''531360''>value</span> <span m=''531780''>in
  a</span> <span m=''531880''>register</span> <span m=''532370''>with</span> <span
  m=''532500''>a</span> <span m=''532580''>value</span> <span m=''532990''>in</span>
  <span m=''533090''>memory.</span> <span m=''533920''>People</span> <span m=''534140''>remember</span>
  <span m=''534480''>that?</span> <span m=''536690''>To</span> <span m=''536790''>implement</span>
  <span m=''537180''>a</span> <span m=''537240''>lock?</span> <span m=''538180''>So</span>
  <span m=''538400''>in</span> <span m=''538520''>order</span> <span m=''538740''>to</span>
  <span m=''538800''>implement</span> <span m=''539100''>a</span> <span m=''539150''>lock,</span>
  <span m=''539570''>I</span> <span m=''540500''>atomically</span> <span m=''541710''>switch</span>
  <span m=''542160''>two</span> <span m=''542310''>values.</span> </p><p><span m=''546500''>So</span>
  <span m=''546680''>we,</span> <span m=''546890''>in particular,</span> <span m=''547320''>use</span>
  <span m=''547520''>the</span> <span m=''547610''>exchange</span> <span m=''548090''>one.</span>
  <span m=''548330''>And</span> <span m=''548500''>there are</span> <span m=''548670''>a</span>
  <span m=''548710''>bunch</span> <span m=''549020''>of</span> <span m=''549130''>other</span>
  <span m=''549390''>commands</span> <span m=''549950''>that</span> <span m=''550080''>people</span>
  <span m=''550370''>can</span> <span m=''550510''>use.</span> <span m=''550750''>Test-and-set,</span>
  <span m=''551460''>compare-and-swap,</span> <span m=''552270''>load-linked-store-conditional,</span>
  <span m=''555470''>which</span> <span m=''556870''>essentially</span> <span m=''557240''>do</span>
  <span m=''557500''>some</span> <span m=''557690''>kind</span> <span m=''557830''>of</span>
  <span m=''557980''>read-modify-write</span> <span m=''558940''>on</span> <span m=''559060''>memory.</span>
  <span m=''559630''>These</span> <span m=''559830''>tend</span> <span m=''560050''>to</span>
  <span m=''560120''>be</span> <span m=''560290''>expensive</span> <span m=''560790''>instructions,</span>
  <span m=''561470''>as</span> <span m=''561620''>I</span> <span m=''561700''>mentioned.</span>
  <span m=''562340''>They</span> <span m=''562450''>usually</span> <span m=''562770''>tend</span>
  <span m=''563030''>to</span> <span m=''563120''>cost</span> <span m=''563470''>something</span>
  <span m=''563810''>like</span> <span m=''564040''>an</span> <span m=''564150''>L2</span>
  <span m=''565100''>cache</span> <span m=''565490''>hit.</span> </p><p><span m=''567820''>Now,</span>
  <span m=''568040''>the</span> <span m=''568150''>question</span> <span m=''568660''>is</span>
  <span m=''569150''>can</span> <span m=''569420''>mutual</span> <span m=''569800''>exclusion</span>
  <span m=''570320''>be</span> <span m=''570480''>implemented</span> <span m=''571070''>with</span>
  <span m=''571290''>only</span> <span m=''571910''>atomic</span> <span m=''572510''>loads</span>
  <span m=''572970''>and</span> <span m=''573120''>stores?</span> <span m=''573620''>Do</span>
  <span m=''573690''>you</span> <span m=''573770''>really</span> <span m=''574030''>need</span>
  <span m=''574900''>one</span> <span m=''575130''>of</span> <span m=''575190''>these</span>
  <span m=''575390''>heavyweight</span> <span m=''577430''>operations</span> <span
  m=''578870''>to</span> <span m=''579040''>implement</span> <span m=''581560''>mutual</span>
  <span m=''581870''>exclusion?</span> <span m=''582740''>What</span> <span m=''582920''>if</span>
  <span m=''583020''>I</span> <span m=''583110''>don''t</span> <span m=''583490''>use</span>
  <span m=''583700''>our</span> <span m=''583810''>read-modify-write?</span> <span
  m=''584710''>Is</span> <span m=''584860''>that</span> <span m=''585020''>possible</span>
  <span m=''586140''>to</span> <span m=''586560''>do</span> <span m=''586720''>it?</span>
  </p><p><span m=''586860''>And</span> <span m=''587070''>in</span> <span m=''587170''>fact,</span>
  <span m=''587470''>the</span> <span m=''587580''>answer</span> <span m=''588400''>is</span>
  <span m=''588580''>yes.</span> <span m=''590690''>So</span> <span m=''590910''>Dekker</span>
  <span m=''591195''>and</span> <span m=''591480''>Dijksra</span> <span m=''591910''>show</span>
  <span m=''592160''>that</span> <span m=''592640''>it</span> <span m=''592900''>can</span>
  <span m=''593240''>as</span> <span m=''593370''>long</span> <span m=''593720''>as</span>
  <span m=''593830''>the</span> <span m=''593920''>computer</span> <span m=''594320''>system</span>
  <span m=''595110''>is</span> <span m=''595260''>sequentially</span> <span m=''595860''>consistent.</span>
  <span m=''598420''>So</span> <span m=''598660''>as long as you have</span> <span
  m=''599060''>sequential</span> <span m=''599590''>consistency,</span> <span m=''600530''>you</span>
  <span m=''600660''>in</span> <span m=''600770''>fact,</span> <span m=''601310''>can</span>
  <span m=''602030''>implement</span> <span m=''602790''>a</span> <span m=''605750''>mutual</span>
  <span m=''606100''>exclusion</span> <span m=''606660''>with</span> <span m=''606850''>read-modify-write.</span>
  </p><p><span m=''608940''>We''re</span> <span m=''609220''>actually</span> <span
  m=''609430''>not</span> <span m=''609580''>going</span> <span m=''609650''>to</span>
  <span m=''609940''>use</span> <span m=''610260''>either</span> <span m=''610660''>the</span>
  <span m=''610770''>Dekker</span> <span m=''611040''>or</span> <span m=''611330''>Dijksra</span>
  <span m=''611780''>algorithms,</span> <span m=''612300''>although</span> <span m=''612490''>you</span>
  <span m=''612650''>can</span> <span m=''612750''>read</span> <span m=''612920''>about</span>
  <span m=''613210''>those</span> <span m=''613560''>in</span> <span m=''614090''>the</span>
  <span m=''614300''>literature.</span> <span m=''615010''>We''re</span> <span m=''615160''>going</span>
  <span m=''615240''>to</span> <span m=''615290''>look</span> <span m=''615500''>at</span>
  <span m=''615720''>what</span> <span m=''615880''>is</span> <span m=''616000''>probably</span>
  <span m=''616340''>the</span> <span m=''616440''>simplest</span> <span m=''616970''>such</span>
  <span m=''617230''>algorithm</span> <span m=''618080''>that''s</span> <span m=''618300''>been</span>
  <span m=''618450''>devised</span> <span m=''618920''>to</span> <span m=''619010''>date,</span>
  <span m=''619410''>which</span> <span m=''619580''>is</span> <span m=''619820''>devised</span>
  <span m=''620670''>by</span> <span m=''622160''>Peterson.</span> </p><p><span m=''623690''>And</span>
  <span m=''624370''>I''m going</span> <span m=''624710''>to</span> <span m=''624750''>illustrate</span>
  <span m=''625350''>it</span> <span m=''625540''>with</span> <span m=''626020''>these</span>
  <span m=''626530''>two</span> <span m=''626690''>smileys.</span> <span m=''629370''>That''s</span>
  <span m=''629790''>a</span> <span m=''629840''>she.</span> <span m=''630320''>And</span>
  <span m=''630520''>that''s</span> <span m=''630750''>a</span> <span m=''630850''>he.</span>
  <span m=''631590''>And</span> <span m=''631730''>they</span> <span m=''631860''>want</span>
  <span m=''632180''>to</span> <span m=''632290''>operate</span> <span m=''632980''>on</span>
  <span m=''633520''>widget</span> <span m=''633860''>x.</span> <span m=''634280''>And</span>
  <span m=''634420''>she</span> <span m=''634640''>wants</span> <span m=''634920''>to</span>
  <span m=''635020''>frob</span> <span m=''635440''>it.</span> <span m=''636040''>And</span>
  <span m=''636200''>he</span> <span m=''636330''>wants</span> <span m=''636590''>to</span>
  <span m=''636700''>borf</span> <span m=''637200''>it.</span> <span m=''638560''>And</span>
  <span m=''638740''>we</span> <span m=''638870''>want</span> <span m=''639070''>to</span>
  <span m=''639310''>preserve</span> <span m=''639790''>the</span> <span m=''639890''>property</span>
  <span m=''640490''>that</span> <span m=''640680''>we</span> <span m=''640840''>are</span>
  <span m=''640920''>not</span> <span m=''641240''>frobbing</span> <span m=''641660''>and</span>
  <span m=''642040''>borfing</span> <span m=''642190''>at</span> <span m=''642280''>the</span>
  <span m=''642350''>same</span> <span m=''642640''>time.</span> </p><p><span m=''646380''>So</span>
  <span m=''646560''>how</span> <span m=''646740''>do</span> <span m=''646810''>we</span>
  <span m=''646940''>do</span> <span m=''647130''>that?</span> <span m=''647430''>Well,</span>
  <span m=''647570''>here''s</span> <span m=''647840''>the</span> <span m=''647930''>code.</span>
  <span m=''650010''>So</span> <span m=''650210''>we''re</span> <span m=''650310''>going</span>
  <span m=''650410''>to</span> <span m=''650470''>set</span> <span m=''650750''>up</span>
  <span m=''650920''>some</span> <span m=''651140''>things</span> <span m=''651480''>before</span>
  <span m=''651930''>we</span> <span m=''652400''>start</span> <span m=''652840''>he</span>
  <span m=''653000''>and</span> <span m=''653120''>she</span> <span m=''653340''>operating.</span>
  <span m=''654830''>So</span> <span m=''655000''>we''re</span> <span m=''655080''>going</span>
  <span m=''655160''>to</span> <span m=''655330''>have</span> <span m=''655510''>our</span>
  <span m=''655670''>widget</span> <span m=''655990''>x.</span> <span m=''656300''>That''s</span>
  <span m=''656510''>our</span> <span m=''656590''>protected</span> <span m=''657130''>variable.</span>
  <span m=''657820''>And</span> <span m=''658150''>we''re</span> <span m=''658320''>going</span>
  <span m=''658400''>to</span> <span m=''658520''>have</span> <span m=''658640''>a</span>
  <span m=''658700''>Boolean</span> <span m=''659750''>set</span> <span m=''660150''>initially</span>
  <span m=''660610''>to false</span> <span m=''661700''>that</span> <span m=''661860''>says</span>
  <span m=''662170''>whether</span> <span m=''662410''>she</span> <span m=''662640''>wants</span>
  <span m=''662990''>to</span> <span m=''663080''>frob</span> <span m=''663420''>it.</span>
  <span m=''663980''>So</span> <span m=''664550''>we</span> <span m=''664740''>don''t</span>
  <span m=''664950''>want</span> <span m=''665100''>to</span> <span m=''665150''>make</span>
  <span m=''665410''>them</span> <span m=''665550''>frob it</span> <span m=''665840''>unless</span>
  <span m=''666190''>they</span> <span m=''666290''>want</span> <span m=''666580''>to</span>
  <span m=''666630''>frob</span> <span m=''666840''>it.</span> <span m=''668020''>And</span>
  <span m=''668390''>we</span> <span m=''668480''>don''t</span> <span m=''668640''>want</span>
  <span m=''668760''>him</span> <span m=''669090''>to</span> <span m=''670200''>borf</span>
  <span m=''670510''>it</span> <span m=''670650''>unless</span> <span m=''670940''>he</span>
  <span m=''671060''>wants</span> <span m=''671390''>to</span> <span m=''671490''>borf</span>
  <span m=''671970''>it.</span> </p><p><span m=''673510''>And</span> <span m=''673720''>we''re</span>
  <span m=''673850''>going</span> <span m=''673930''>to</span> <span m=''673980''>have</span>
  <span m=''674280''>an</span> <span m=''674730''>extra</span> <span m=''675160''>auxiliary</span>
  <span m=''675720''>variable,</span> <span m=''676320''>which</span> <span m=''676550''>is</span>
  <span m=''676750''>whose</span> <span m=''676980''>turn</span> <span m=''677250''>it</span>
  <span m=''677490''>is.</span> <span m=''678620''>So</span> <span m=''678780''>they''re</span>
  <span m=''678910''>going</span> <span m=''679030''>to</span> <span m=''679100''>sort</span>
  <span m=''679330''>of</span> <span m=''679460''>do</span> <span m=''679610''>a</span>
  <span m=''679730''>take</span> <span m=''680120''>turn.</span> <span m=''681030''>But</span>
  <span m=''681180''>that</span> <span m=''681330''>only</span> <span m=''681670''>is</span>
  <span m=''681840''>going</span> <span m=''681960''>to</span> <span m=''682020''>come</span>
  <span m=''682240''>into</span> <span m=''682450''>account</span> <span m=''683050''>if</span>
  <span m=''683680''>the</span> <span m=''683850''>other</span> <span m=''684040''>one</span>
  <span m=''685190''>doesn''t</span> <span m=''685320''>have</span> <span m=''685420''>a</span>
  <span m=''685520''>conflict.</span> <span m=''686120''>If</span> <span m=''686200''>they</span>
  <span m=''686280''>don''t</span> <span m=''686410''>have</span> <span m=''686500''>a</span>
  <span m=''686590''>conflict,</span> <span m=''687190''>then</span> <span m=''687660''>one
  of</span> <span m=''687950''>them is</span> <span m=''688240''>going</span> <span
  m=''688330''>to</span> <span m=''688370''>be</span> <span m=''688490''>able</span>
  <span m=''688620''>to</span> <span m=''688690''>go.</span> </p><p><span m=''689340''>So</span>
  <span m=''689490''>here''s</span> <span m=''690060''>what</span> <span m=''690250''>she</span>
  <span m=''690470''>basically</span> <span m=''690970''>does.</span> <span m=''691180''>She</span>
  <span m=''691490''>initially</span> <span m=''691960''>sets</span> <span m=''692710''>that</span>
  <span m=''692840''>she</span> <span m=''693090''>wants</span> <span m=''693860''>to</span>
  <span m=''694200''>operate</span> <span m=''696960''>on</span> <span m=''697160''>the</span>
  <span m=''697250''>widget.</span> <span m=''699440''>And</span> <span m=''699650''>then,</span>
  <span m=''700270''>what</span> <span m=''701420''>she</span> <span m=''701630''>does</span>
  <span m=''702130''>is she</span> <span m=''702320''>sets</span> <span m=''703090''>the</span>
  <span m=''703270''>turn</span> <span m=''703820''>to</span> <span m=''703920''>be</span>
  <span m=''704100''>his.</span> <span m=''707900''>And</span> <span m=''708050''>then,</span>
  <span m=''708260''>while</span> <span m=''708740''>he</span> <span m=''709020''>wants</span>
  <span m=''709470''>it,</span> <span m=''709720''>and</span> <span m=''709930''>the</span>
  <span m=''710140''>turn</span> <span m=''710460''>is</span> <span m=''710640''>his,</span>
  <span m=''714090''>she''s</span> <span m=''714350''>going</span> <span m=''714450''>to</span>
  <span m=''714550''>just</span> <span m=''714940''>spin.</span> </p><p><span m=''715210''>Notice</span>
  <span m=''715520''>that</span> <span m=''716230''>you''re</span> <span m=''716360''>not</span>
  <span m=''716650''>frobbing</span> <span m=''717100''>it</span> <span m=''717240''>in</span>
  <span m=''717410''>while</span> <span m=''717820''>loop.</span> <span m=''718050''>The</span>
  <span m=''718150''>body</span> <span m=''718510''>of</span> <span m=''718580''>the</span>
  <span m=''718660''>while</span> <span m=''718970''>loop</span> <span m=''719160''>is</span>
  <span m=''719310''>empty.</span> <span m=''720840''>So</span> <span m=''721010''>this</span>
  <span m=''721170''>is a</span> <span m=''721330''>spinning</span> <span m=''721910''>solution.</span>
  <span m=''723510''>So</span> <span m=''723700''>while</span> <span m=''724490''>he</span>
  <span m=''724650''>wants</span> <span m=''725000''>it,</span> <span m=''725130''>and</span>
  <span m=''725270''>it''s</span> <span m=''725470''>his</span> <span m=''725670''>turn,</span>
  <span m=''726690''>you''re</span> <span m=''726840''>just</span> <span m=''727020''>going</span>
  <span m=''727120''>to</span> <span m=''727170''>sit</span> <span m=''727490''>there,</span>
  <span m=''728590''>continually</span> <span m=''729200''>testing</span> <span m=''730160''>the</span>
  <span m=''730260''>variables</span> <span m=''730870''>he</span> <span m=''731040''>wants</span>
  <span m=''731610''>and</span> <span m=''731850''>turn</span> <span m=''732080''>equals</span>
  <span m=''732430''>his</span> <span m=''733190''>until</span> <span m=''733640''>one</span>
  <span m=''733860''>of</span> <span m=''733970''>them</span> <span m=''734220''>ends</span>
  <span m=''734500''>up</span> <span m=''734770''>being</span> <span m=''735450''>false.</span>
  </p><p><span m=''738920''>So</span> <span m=''739070''>if</span> <span m=''739740''>he</span>
  <span m=''739900''>doesn''t</span> <span m=''740240''>want</span> <span m=''740610''>it,</span>
  <span m=''741560''>or</span> <span m=''741920''>it''s</span> <span m=''742090''>not</span>
  <span m=''742310''>his</span> <span m=''742580''>turn,</span> <span m=''743320''>then</span>
  <span m=''743590''>she</span> <span m=''743760''>gets</span> <span m=''743970''>to</span>
  <span m=''744070''>frob it.</span> <span m=''744710''>And</span> <span m=''744970''>when</span>
  <span m=''745220''>she''s</span> <span m=''745500''>done,</span> <span m=''745880''>she</span>
  <span m=''746060''>sets</span> <span m=''747400''>she</span> <span m=''747630''>wants</span>
  <span m=''747950''>to</span> <span m=''748050''>false.</span> <span m=''748950''>And</span>
  <span m=''749090''>he</span> <span m=''749270''>does</span> <span m=''749520''>a</span>
  <span m=''749580''>similar</span> <span m=''750010''>thing.</span> <span m=''750450''>He</span>
  <span m=''750570''>sets</span> <span m=''750870''>it</span> <span m=''750980''>to</span>
  <span m=''751090''>true,</span> <span m=''751850''>says</span> <span m=''752100''>it''s</span>
  <span m=''752260''>her turn.</span> <span m=''753220''>And</span> <span m=''753380''>then,</span>
  <span m=''753530''>while</span> <span m=''754330''>she</span> <span m=''754580''>wants</span>
  <span m=''754970''>it,</span> <span m=''755190''>and</span> <span m=''755340''>the</span>
  <span m=''755500''>turn is</span> <span m=''755890''>hers,</span> <span m=''756500''>just</span>
  <span m=''756700''>sits</span> <span m=''756980''>there</span> <span m=''757850''>waiting,</span>
  <span m=''760340''>continually</span> <span m=''760960''>re-executing</span> <span
  m=''761710''>this</span> <span m=''762190''>until</span> <span m=''762430''>finally,</span>
  <span m=''763720''>one</span> <span m=''763980''>of</span> <span m=''764060''>these</span>
  <span m=''764280''>turns</span> <span m=''764540''>out</span> <span m=''764680''>to</span>
  <span m=''764750''>be</span> <span m=''764900''>false.</span> <span m=''765510''>And</span>
  <span m=''765660''>then</span> <span m=''765800''>he</span> <span m=''765910''>borfs</span>
  <span m=''766320''>it. And he</span> <span m=''766670''>sets</span> <span m=''766950''>it</span>
  <span m=''767030''>to</span> <span m=''767120''>false.</span> </p><p><span m=''767900''>And</span>
  <span m=''768070''>then,</span> <span m=''768300''>they''re</span> <span m=''768450''>doing</span>
  <span m=''768750''>both</span> <span m=''769020''>of</span> <span m=''769110''>these</span>
  <span m=''769370''>things</span> <span m=''769650''>sort</span> <span m=''769840''>of</span>
  <span m=''769940''>in</span> <span m=''770380''>a</span> <span m=''770520''>loop,</span>
  <span m=''771240''>periodically</span> <span m=''771890''>coming</span> <span m=''772200''>back</span>
  <span m=''773360''>and</span> <span m=''773990''>executing</span> <span m=''774280''>it.</span>
  <span m=''775200''>And</span> <span m=''775320''>what</span> <span m=''775450''>you</span>
  <span m=''775540''>want</span> <span m=''775690''>to</span> <span m=''775750''>do</span>
  <span m=''775940''>is</span> <span m=''776060''>you</span> <span m=''776170''>don''t</span>
  <span m=''776350''>want</span> <span m=''776480''>to</span> <span m=''776520''>make</span>
  <span m=''776750''>it</span> <span m=''776870''>so that</span> <span m=''777010''>it''s</span>
  <span m=''777340''>forced.</span> <span m=''777770''>That</span> <span m=''777890''>it''s</span>
  <span m=''778030''>one</span> <span m=''778310''>turn,</span> <span m=''778560''>then</span>
  <span m=''778700''>the</span> <span m=''778850''>other</span> <span m=''779900''>because</span>
  <span m=''780780''>maybe</span> <span m=''781070''>he</span> <span m=''781190''>never</span>
  <span m=''781460''>wants</span> <span m=''781820''>to</span> <span m=''782710''>borf</span>
  <span m=''783130''>it.</span> <span m=''783830''>And</span> <span m=''783950''>then,</span>
  <span m=''784070''>she</span> <span m=''784250''>would</span> <span m=''784410''>be</span>
  <span m=''784550''>stuck</span> <span m=''784990''>not</span> <span m=''785250''>being</span>
  <span m=''785440''>able</span> <span m=''785630''>to</span> <span m=''785700''>frob</span>
  <span m=''785990''>it,</span> <span m=''786160''>even</span> <span m=''786360''>though</span>
  <span m=''786480''>he</span> <span m=''786580''>doesn''t</span> <span m=''786890''>want.</span>
  </p><p><span m=''788350''>So</span> <span m=''788550''>if</span> <span m=''788630''>you</span>
  <span m=''788740''>think</span> <span m=''788960''>about</span> <span m=''789290''>this--</span>
  <span m=''789500''>let''s</span> <span m=''790090''>think</span> <span m=''790380''>about</span>
  <span m=''790720''>why</span> <span m=''791130''>this</span> <span m=''792560''>always</span>
  <span m=''793720''>is</span> <span m=''793900''>going</span> <span m=''794020''>to</span>
  <span m=''794060''>give</span> <span m=''794280''>you</span> <span m=''794420''>mutual</span>
  <span m=''794830''>exclusion.</span> <span m=''797710''>So</span> <span m=''797890''>basically,</span>
  <span m=''798940''>what''s</span> <span m=''799150''>happening</span> <span m=''799620''>here</span>
  <span m=''799950''>is</span> <span m=''800200''>if</span> <span m=''800330''>he</span>
  <span m=''800540''>wants</span> <span m=''800990''>it--</span> <span m=''801840''>by
  the way,</span> <span m=''802090''>these</span> <span m=''802510''>things</span>
  <span m=''802770''>are</span> <span m=''802870''>not</span> <span m=''803100''>easy</span>
  <span m=''803410''>to</span> <span m=''803520''>reason</span> <span m=''803800''>about.</span>
  <span m=''804120''>And</span> <span m=''804320''>usually,</span> <span m=''805180''>as</span>
  <span m=''805320''>much</span> <span m=''805540''>as</span> <span m=''805670''>I</span>
  <span m=''805780''>can</span> <span m=''805980''>talk</span> <span m=''806340''>and</span>
  <span m=''806450''>talk</span> <span m=''806750''>in</span> <span m=''806870''>class,</span>
  <span m=''807980''>what</span> <span m=''808160''>you</span> <span m=''808270''>really</span>
  <span m=''808500''>need</span> <span m=''808680''>to</span> <span m=''808770''>do</span>
  <span m=''809030''>is</span> <span m=''809200''>go</span> <span m=''809390''>home,</span>
  <span m=''809730''>and</span> <span m=''809900''>sit</span> <span m=''810260''>down</span>
  <span m=''810910''>with</span> <span m=''811050''>this</span> <span m=''811220''>kind</span>
  <span m=''811430''>of</span> <span m=''811540''>thing.</span> <span m=''812090''>And</span>
  <span m=''812250''>study</span> <span m=''812700''>it</span> <span m=''813070''>for</span>
  <span m=''814460''>10</span> <span m=''814670''>minutes.</span> <span m=''815940''>And</span>
  <span m=''816170''>then,</span> <span m=''816340''>you''ll</span> <span m=''816620''>understand</span>
  <span m=''817550''>what</span> <span m=''817820''>the</span> <span m=''817880''>subtleties</span>
  <span m=''818500''>are</span> <span m=''819350''>as</span> <span m=''819500''>what''s</span>
  <span m=''819700''>going</span> <span m=''819900''>on.</span> </p><p><span m=''820100''>But</span>
  <span m=''820260''>basically,</span> <span m=''822510''>what</span> <span m=''822800''>we''re</span>
  <span m=''822910''>doing</span> <span m=''823410''>is</span> <span m=''823680''>we''re</span>
  <span m=''823790''>making</span> <span m=''824190''>it</span> <span m=''824320''>so</span>
  <span m=''824620''>that</span> <span m=''825990''>it''s</span> <span m=''826260''>not</span>
  <span m=''826510''>going</span> <span m=''826620''>to</span> <span m=''826660''>be</span>
  <span m=''826780''>the</span> <span m=''826920''>case</span> <span m=''827890''>that</span>
  <span m=''828230''>both</span> <span m=''829050''>she''s</span> <span m=''829340''>setting</span>
  <span m=''829680''>it</span> <span m=''829940''>and</span> <span m=''830090''>she</span>
  <span m=''830240''>wants</span> <span m=''830670''>it.</span> <span m=''830820''>And</span>
  <span m=''830930''>the</span> <span m=''831050''>turn</span> <span m=''831500''>is</span>
  <span m=''831790''>his.</span> <span m=''833060''>And</span> <span m=''833310''>then,</span>
  <span m=''834010''>if</span> <span m=''834190''>there''s</span> <span m=''834420''>a</span>
  <span m=''834470''>race</span> <span m=''835040''>where</span> <span m=''835690''>he</span>
  <span m=''835860''>wants</span> <span m=''836280''>it</span> <span m=''836420''>also,</span>
  <span m=''838720''>then</span> <span m=''839010''>that''s</span> <span m=''839280''>going</span>
  <span m=''839360''>to</span> <span m=''839440''>preclude</span> <span m=''840130''>both</span>
  <span m=''840480''>of</span> <span m=''840590''>them</span> <span m=''840760''>from</span>
  <span m=''840950''>going</span> <span m=''841290''>into</span> <span m=''841670''>it</span>
  <span m=''842100''>at</span> <span m=''842270''>the</span> <span m=''842350''>same</span>
  <span m=''842640''>time.</span> <span m=''843790''>And</span> <span m=''843920''>then</span>
  <span m=''844060''>whichever</span> <span m=''845470''>one</span> <span m=''845950''>sets</span>
  <span m=''846790''>the</span> <span m=''847220''>turn,</span> <span m=''849170''>one</span>
  <span m=''849510''>of</span> <span m=''849620''>those</span> <span m=''849910''>is</span>
  <span m=''850040''>going</span> <span m=''850130''>to</span> <span m=''850220''>occur</span>
  <span m=''850540''>first.</span> <span m=''851830''>And</span> <span m=''851980''>one</span>
  <span m=''852160''>is</span> <span m=''852270''>going</span> <span m=''852350''>to</span>
  <span m=''852430''>occur</span> <span m=''852730''>second.</span> <span m=''853810''>And</span>
  <span m=''854150''>whoever</span> <span m=''854570''>ends</span> <span m=''854870''>up</span>
  <span m=''856360''>coming</span> <span m=''856630''>second,</span> <span m=''858070''>the</span>
  <span m=''858220''>other</span> <span m=''858380''>one</span> <span m=''858580''>gets</span>
  <span m=''858790''>to</span> <span m=''858880''>go</span> <span m=''859050''>ahead.</span>
  <span m=''862700''>So</span> <span m=''862870''>it''s</span> <span m=''863270''>very</span>
  <span m=''863890''>subtle</span> <span m=''864410''>how</span> <span m=''864670''>that</span>
  <span m=''865240''>is</span> <span m=''865440''>actually</span> <span m=''865830''>working</span>
  <span m=''866650''>to</span> <span m=''866780''>make</span> <span m=''866990''>sure</span>
  <span m=''867160''>that</span> <span m=''867330''>each</span> <span m=''867580''>one</span>
  <span m=''867780''>is</span> <span m=''867950''>gating</span> <span m=''868350''>the</span>
  <span m=''868490''>other</span> <span m=''868820''>to</span> <span m=''868960''>allow</span>
  <span m=''869320''>them</span> <span m=''869500''>to</span> <span m=''869590''>go.</span>
  </p><p><span m=''872470''>But</span> <span m=''873120''>the</span> <span m=''873270''>way</span>
  <span m=''873450''>to</span> <span m=''873640''>reason</span> <span m=''874010''>about</span>
  <span m=''874340''>this</span> <span m=''874570''>is</span> <span m=''874700''>to</span>
  <span m=''874830''>reason</span> <span m=''875160''>about</span> <span m=''875440''>it
  is</span> <span m=''875590''>what</span> <span m=''875800''>are</span> <span m=''875860''>the</span>
  <span m=''875970''>possible</span> <span m=''876540''>interleavings?</span> <span
  m=''877860''>And</span> <span m=''878010''>the</span> <span m=''878090''>important</span>
  <span m=''878510''>interleavings</span> <span m=''878795''>here</span> <span m=''879080''>as</span>
  <span m=''879390''>you</span> <span m=''879510''>can</span> <span m=''879670''>see</span>
  <span m=''880430''>are</span> <span m=''881730''>what</span> <span m=''882150''>happens</span>
  <span m=''882600''>when</span> <span m=''882720''>setting</span> <span m=''883150''>these</span>
  <span m=''883400''>things.</span> <span m=''883710''>And</span> <span m=''883800''>once</span>
  <span m=''884100''>they''re</span> <span m=''884270''>set,</span> <span m=''885010''>what</span>
  <span m=''885150''>happens</span> <span m=''885620''>in</span> <span m=''885740''>testing</span>
  <span m=''886190''>these</span> <span m=''886430''>things?</span> <span m=''886850''>And</span>
  <span m=''887350''>especially</span> <span m=''887870''>because</span> <span m=''888320''>when</span>
  <span m=''888490''>you</span> <span m=''888600''>go</span> <span m=''888780''>around</span>
  <span m=''888980''>the</span> <span m=''889180''>loop</span> <span m=''889450''>and</span>
  <span m=''889630''>so</span> <span m=''889810''>forth,</span> <span m=''890440''>you</span>
  <span m=''890580''>have</span> <span m=''890710''>to</span> <span m=''890820''>imagine</span>
  <span m=''891350''>that</span> <span m=''891580''>an</span> <span m=''891800''>arbitrarily</span>
  <span m=''892430''>long</span> <span m=''892730''>amount</span> <span m=''892970''>of</span>
  <span m=''893070''>time</span> <span m=''893520''>is</span> <span m=''893690''>gone.</span>
  </p><p><span m=''894600''>So</span> <span m=''894790''>for</span> <span m=''894920''>example,</span>
  <span m=''895310''>between</span> <span m=''895790''>the</span> <span m=''895910''>time</span>
  <span m=''896410''>that you</span> <span m=''896570''>check</span> <span m=''897450''>that</span>
  <span m=''897610''>the</span> <span m=''897730''>turn</span> <span m=''898010''>is</span>
  <span m=''898170''>his,</span> <span m=''899500''>he</span> <span m=''900050''>may</span>
  <span m=''900280''>have</span> <span m=''900400''>already</span> <span m=''900680''>gone</span>
  <span m=''900910''>around</span> <span m=''901200''>this</span> <span m=''901360''>loop.</span>
  <span m=''904350''>And</span> <span m=''904570''>so</span> <span m=''904650''>you</span>
  <span m=''904740''>have</span> <span m=''904860''>to</span> <span m=''904970''>worry</span>
  <span m=''905250''>about--</span> <span m=''906140''>even</span> <span m=''906380''>though,</span>
  <span m=''906740''>it</span> <span m=''906890''>may</span> <span m=''907120''>look</span>
  <span m=''907290''>like</span> <span m=''907490''>one</span> <span m=''907650''>instruction</span>
  <span m=''908280''>from</span> <span m=''908870''>this</span> <span m=''909110''>processors</span>
  <span m=''909680''>point</span> <span m=''909900''>of</span> <span m=''909970''>view</span>
  <span m=''910200''>for</span> <span m=''910420''>correctness</span> <span m=''910940''>purpose,</span>
  <span m=''911540''>you</span> <span m=''911640''>have</span> <span m=''911740''>to</span>
  <span m=''911820''>imagine</span> <span m=''912260''>that</span> <span m=''912490''>an</span>
  <span m=''912600''>arbitrary</span> <span m=''913080''>amount</span> <span m=''913300''>of</span>
  <span m=''913380''>computation</span> <span m=''914300''>could</span> <span m=''914450''>occur</span>
  <span m=''914760''>between</span> <span m=''915140''>any</span> <span m=''915360''>two</span>
  <span m=''915520''>instructions.</span> <span m=''918340''>So</span> <span m=''918510''>any</span>
  <span m=''918640''>question</span> <span m=''919070''>about</span> <span m=''920870''>this</span>
  <span m=''921070''>code?</span> <span m=''921260''>People</span> <span m=''921560''>see</span>
  <span m=''922320''>how</span> <span m=''922510''>it</span> <span m=''922890''>preserves</span>
  <span m=''923500''>mutual</span> <span m=''923860''>exclusion</span> <span m=''924650''>and</span>
  <span m=''924810''>how</span> <span m=''925640''>you</span> <span m=''925780''>use</span>
  <span m=''926040''>sequential</span> <span m=''926530''>consistency</span> <span
  m=''927320''>to</span> <span m=''927400''>reason</span> <span m=''927760''>about</span>
  <span m=''928100''>it</span> <span m=''928460''>by</span> <span m=''928640''>asking</span>
  <span m=''929090''>what</span> <span m=''929280''>are</span> <span m=''929350''>the</span>
  <span m=''929450''>possible</span> <span m=''929950''>interleavings?</span> <span
  m=''932000''>Questions?</span> <span m=''932930''>Yeah.</span> </p><p><span m=''934057''>AUDIENCE:
  So,</span> <span m=''934494''>I don''t know</span> <span m=''934931''>if I got it</span>
  <span m=''935370''>right.</span> <span m=''936756''>So basically,</span> <span m=''939184''>sets</span>
  <span m=''939675''>the</span> <span m=''940166''>[UNINTELLIGIBLE]</span> <span m=''941148''>to</span>
  <span m=''941639''>give him</span> <span m=''942130''>a chance</span> <span m=''942630''>before</span>
  <span m=''943990''>she</span> <span m=''944280''>goes</span> <span m=''945710''>to</span>
  <span m=''945810''>loop.</span> <span m=''946500''>So</span> <span m=''946670''>basically,
  she</span> <span m=''946910''>waits</span> <span m=''947120''>there</span> <span
  m=''948250''>until</span> <span m=''948720''>he has</span> <span m=''949190''>been</span>
  <span m=''949660''>able</span> <span m=''949890''>to go?</span> <span m=''950130''>That''s
  why</span> <span m=''950875''>on the</span> <span m=''951320''>[UNINTELLIGIBLE].</span>
  </p><p><span m=''951770''>PROFESSOR: So on</span> <span m=''952220''>this</span>
  <span m=''952670''>third line--</span> </p><p><span m=''955070''>AUDIENCE: Both</span>
  <span m=''955550''>of them.</span> <span m=''955995''>Either</span> <span m=''956440''>before</span>
  <span m=''957190''>actually</span> <span m=''957960''>frobbing</span> <span m=''958460''>or</span>
  <span m=''958690''>borfing.</span> <span m=''959043''>And</span> <span m=''959396''>before
  that</span> <span m=''959820''>while</span> <span m=''960320''>you</span> <span
  m=''960570''>always</span> <span m=''961010''>give the turn</span> <span m=''961500''>to
  the other</span> <span m=''961990''>to give them</span> <span m=''962480''>a chance</span>
  <span m=''962755''>to go.</span> </p><p><span m=''963030''>PROFESSOR: Yeah. So</span>
  <span m=''963430''>there are</span> <span m=''963680''>two</span> <span m=''963850''>things</span>
  <span m=''964060''>you</span> <span m=''964140''>want</span> <span m=''964240''>to</span>
  <span m=''964280''>show.</span> <span m=''964550''>One</span> <span m=''964840''>is</span>
  <span m=''965190''>that</span> <span m=''967820''>they</span> <span m=''967980''>can''t</span>
  <span m=''968330''>both</span> <span m=''968600''>be</span> <span m=''968730''>stalled</span>
  <span m=''969310''>on</span> <span m=''970470''>the</span> <span m=''970600''>while</span>
  <span m=''971410''>loop there.  And</span> <span m=''971570''>that</span> <span
  m=''971800''>can''t</span> <span m=''972040''>happen</span> <span m=''972400''>because</span>
  <span m=''972670''>the</span> <span m=''972790''>turn</span> <span m=''973100''>can''t</span>
  <span m=''973390''>be</span> <span m=''973510''>simultaneously</span> <span m=''974570''>his</span>
  <span m=''974870''>and hers.</span> <span m=''976780''>So</span> <span m=''977300''>you</span>
  <span m=''977450''>know that</span> <span m=''977560''>they''re not</span> <span
  m=''977850''>both</span> <span m=''978140''>going</span> <span m=''978380''>to</span>
  <span m=''978740''>deadlock</span> <span m=''979950''>in</span> <span m=''980110''>trying</span>
  <span m=''980340''>to</span> <span m=''980400''>do</span> <span m=''980560''>this</span>
  <span m=''980750''>by</span> <span m=''980910''>sitting</span> <span m=''981260''>there</span>
  <span m=''981430''>waiting</span> <span m=''981780''>for</span> <span m=''981890''>the</span>
  <span m=''982190''>other</span> <span m=''983400''>because</span> <span m=''983770''>of</span>
  <span m=''983870''>this.</span> </p><p><span m=''984400''>And</span> <span m=''984540''>now,</span>
  <span m=''984720''>the</span> <span m=''984830''>question</span> <span m=''985140''>is</span>
  <span m=''985220''>well,</span> <span m=''985320''>how</span> <span m=''985510''>do</span>
  <span m=''985580''>you</span> <span m=''985690''>know</span> <span m=''987760''>that</span>
  <span m=''988210''>one</span> <span m=''988600''>can''t</span> <span m=''988960''>get</span>
  <span m=''989230''>through</span> <span m=''991260''>while</span> <span m=''991590''>the</span>
  <span m=''991750''>other</span> <span m=''992870''>is</span> <span m=''993050''>also</span>
  <span m=''993430''>going</span> <span m=''993740''>through?</span> <span m=''996580''>And</span>
  <span m=''996820''>for</span> <span m=''996940''>that,</span> <span m=''997130''>you</span>
  <span m=''998200''>have</span> <span m=''998340''>to</span> <span m=''998450''>look</span>
  <span m=''998650''>and</span> <span m=''998800''>say,</span> <span m=''999080''>oh</span>
  <span m=''999430''>well,</span> <span m=''1005260''>if</span> <span m=''1005460''>you</span>
  <span m=''1005590''>go</span> <span m=''1005780''>through,</span> <span m=''1006320''>then</span>
  <span m=''1007110''>you know that</span> <span m=''1007970''>it</span> <span m=''1008170''>is</span>
  <span m=''1008460''>either</span> <span m=''1008870''>he</span> <span m=''1009040''>doesn''t</span>
  <span m=''1009410''>want</span> <span m=''1009660''>it,</span> <span m=''1009850''>or</span>
  <span m=''1010000''>it''s</span> <span m=''1010140''>not</span> <span m=''1010370''>his</span>
  <span m=''1010610''>turn.</span> <span m=''1013280''>And</span> <span m=''1013470''>in</span>
  <span m=''1013550''>which</span> <span m=''1013770''>case,</span> <span m=''1014000''>if</span>
  <span m=''1014090''>he</span> <span m=''1014180''>doesn''t</span> <span m=''1014450''>want</span>
  <span m=''1014640''>it, it''s</span> <span m=''1014750''>not</span> <span m=''1014940''>his
  turn.</span> <span m=''1015205''>If he</span> <span m=''1015470''>does</span> <span
  m=''1015800''>change</span> <span m=''1016090''>it</span> <span m=''1016200''>to</span>
  <span m=''1016780''>that</span> <span m=''1016880''>he</span> <span m=''1016980''>wants</span>
  <span m=''1017380''>it,</span> <span m=''1017970''>then</span> <span m=''1018150''>in</span>
  <span m=''1018240''>fact,</span> <span m=''1018490''>it''s</span> <span m=''1018620''>going</span>
  <span m=''1018720''>to</span> <span m=''1018770''>be</span> <span m=''1018880''>your</span>
  <span m=''1019070''>turn.</span> <span m=''1020970''>Question?</span> </p><p><span
  m=''1021785''>AUDIENCE: This only</span> <span m=''1022220''>works for</span> <span
  m=''1022655''>exactly two</span> <span m=''1023090''>threads, right?</span> </p><p><span
  m=''1023960''>PROFESSOR: This</span> <span m=''1024119''>only</span> <span m=''1024310''>works</span>
  <span m=''1024569''>for</span> <span m=''1024650''>exactly</span> <span m=''1025319''>two</span>
  <span m=''1025500''>threads.</span> <span m=''1026349''>This</span> <span m=''1026500''>does</span>
  <span m=''1026660''>not</span> <span m=''1026869''>work</span> <span m=''1027109''>for</span>
  <span m=''1027200''>three,</span> <span m=''1027800''>but</span> <span m=''1027950''>there</span>
  <span m=''1028119''>are</span> <span m=''1028280''>extensions</span> <span m=''1029000''>of</span>
  <span m=''1029099''>this</span> <span m=''1029339''>sort</span> <span m=''1029560''>of</span>
  <span m=''1029650''>thing</span> <span m=''1030020''>to</span> <span m=''1030460''>end</span>
  <span m=''1032079''>threads</span> <span m=''1032540''>in an</span> <span m=''1032650''>arbitrary</span>
  <span m=''1033109''>large</span> <span m=''1033430''>number.</span> <span m=''1034859''>However,</span>
  <span m=''1035270''>the</span> <span m=''1035390''>data</span> <span m=''1035700''>structures</span>
  <span m=''1036220''>to</span> <span m=''1036310''>implement</span> <span m=''1036890''>this</span>
  <span m=''1037180''>kind</span> <span m=''1037319''>of</span> <span m=''1037460''>mutual</span>
  <span m=''1037750''>exclusion</span> <span m=''1038670''>for</span> <span m=''1039140''>end</span>
  <span m=''1039430''>threads</span> <span m=''1040410''>end</span> <span m=''1040660''>up</span>
  <span m=''1041099''>taking</span> <span m=''1041500''>space</span> <span m=''1041960''>proportional</span>
  <span m=''1042540''>to</span> <span m=''1042670''>n.</span> </p><p><span m=''1043730''>And</span>
  <span m=''1043829''>so</span> <span m=''1044050''>one</span> <span m=''1044200''>of</span>
  <span m=''1044240''>the</span> <span m=''1044349''>advantages</span> <span m=''1045130''>of</span>
  <span m=''1045400''>the</span> <span m=''1046310''>built</span> <span m=''1046609''>in</span>
  <span m=''1046720''>atomics--</span> <span m=''1048329''>the</span> <span m=''1048800''>compare-and-swap,</span>
  <span m=''1049780''>or</span> <span m=''1049910''>the</span> <span m=''1051640''>atomic</span>
  <span m=''1052050''>exchange,</span> <span m=''1052560''>or</span> <span m=''1052620''>whatever--</span>
  <span m=''1054590''>is</span> <span m=''1054690''>they</span> <span m=''1054760''>work</span>
  <span m=''1055010''>for</span> <span m=''1055100''>an</span> <span m=''1055170''>arbitrary</span>
  <span m=''1055790''>number</span> <span m=''1056110''>of</span> <span m=''1056600''>threads</span>
  <span m=''1056970''>with</span> <span m=''1057220''>only</span> <span m=''1057490''>a</span>
  <span m=''1057540''>bounded</span> <span m=''1058230''>amount</span> <span m=''1058910''>of</span>
  <span m=''1059170''>resource.</span> <span m=''1060560''>You</span> <span m=''1060740''>don''t</span>
  <span m=''1060940''>require</span> <span m=''1061580''>extra</span> <span m=''1063050''>data</span>
  <span m=''1063320''>structures</span> <span m=''1063900''>and</span> <span m=''1064000''>so</span>
  <span m=''1064190''>forth.</span> <span m=''1066010''>So</span> <span m=''1066200''>that''s</span>
  <span m=''1066440''>why</span> <span m=''1066770''>they</span> <span m=''1066920''>put</span>
  <span m=''1067130''>those</span> <span m=''1067350''>things</span> <span m=''1067580''>in</span>
  <span m=''1067660''>the</span> <span m=''1067780''>architecture</span> <span m=''1068710''>because</span>
  <span m=''1068840''>in</span> <span m=''1068890''>the</span> <span m=''1069010''>architecture</span>
  <span m=''1069660''>you</span> <span m=''1069840''>can</span> <span m=''1073510''>build</span>
  <span m=''1074230''>things</span> <span m=''1074480''>that</span> <span m=''1074580''>will</span>
  <span m=''1074690''>solve</span> <span m=''1075050''>this</span> <span m=''1075210''>problem</span>
  <span m=''1075610''>much</span> <span m=''1075810''>more</span> <span m=''1076470''>simply</span>
  <span m=''1076940''>than</span> <span m=''1077090''>this</span> <span m=''1077250''>sort</span>
  <span m=''1077450''>of</span> <span m=''1077530''>thing.</span> <span m=''1084510''>However,</span>
  <span m=''1084910''>there are</span> <span m=''1085030''>going</span> <span m=''1085100''>to</span>
  <span m=''1085180''>be</span> <span m=''1085250''>lessons</span> <span m=''1085680''>here</span>
  <span m=''1085870''>that</span> <span m=''1086150''>you</span> <span m=''1086300''>may</span>
  <span m=''1086460''>want</span> <span m=''1086640''>to</span> <span m=''1086870''>use</span>
  <span m=''1087180''>in</span> <span m=''1087250''>your</span> <span m=''1087370''>programming,</span>
  <span m=''1087890''>depending</span> <span m=''1088280''>on</span> <span m=''1088520''>what</span>
  <span m=''1088670''>you''re</span> <span m=''1088780''>doing.</span> </p><p><span
  m=''1089330''>So</span> <span m=''1090600''>now,</span> <span m=''1091520''>it</span>
  <span m=''1091730''>turns</span> <span m=''1092090''>out</span> <span m=''1093400''>that</span>
  <span m=''1097090''>no</span> <span m=''1097400''>modern</span> <span m=''1097890''>day</span>
  <span m=''1098250''>processor</span> <span m=''1099310''>implements</span> <span
  m=''1099830''>sequential</span> <span m=''1100390''>consistency.</span> <span m=''1103450''>There</span>
  <span m=''1103620''>have</span> <span m=''1103850''>been</span> <span m=''1104050''>machines</span>
  <span m=''1104510''>that</span> <span m=''1104630''>were</span> <span m=''1104750''>built--</span>
  <span m=''1105100''>actually</span> <span m=''1105350''>quite</span> <span m=''1105650''>good</span>
  <span m=''1105840''>machines--</span> <span m=''1106740''>that</span> <span m=''1106870''>implemented</span>
  <span m=''1107340''>sequential</span> <span m=''1107810''>consistency.</span> <span
  m=''1108500''>But</span> <span m=''1108690''>today,</span> <span m=''1110240''>nobody</span>
  <span m=''1110620''>implements</span> <span m=''1110900''>it.</span> </p><p><span
  m=''1112920''>They</span> <span m=''1113100''>all</span> <span m=''1113420''>implement</span>
  <span m=''1113850''>some</span> <span m=''1114120''>form</span> <span m=''1114590''>of</span>
  <span m=''1114730''>what''s</span> <span m=''1114950''>called</span> <span m=''1115300''>relaxed</span>
  <span m=''1115930''>consistency,</span> <span m=''1118980''>where</span> <span m=''1119400''>the</span>
  <span m=''1119540''>hardware</span> <span m=''1120170''>may</span> <span m=''1120370''>reorder</span>
  <span m=''1120930''>instructions.</span> <span m=''1122840''>And</span> <span m=''1123010''>so</span>
  <span m=''1123180''>you</span> <span m=''1123400''>have</span> <span m=''1123620''>things</span>
  <span m=''1123860''>executing</span> <span m=''1124490''>not</span> <span m=''1124760''>in</span>
  <span m=''1124920''>program</span> <span m=''1125430''>order.</span> <span m=''1125910''>And</span>
  <span m=''1126020''>the</span> <span m=''1126130''>compilers</span> <span m=''1126750''>may</span>
  <span m=''1126940''>reorder</span> <span m=''1127370''>instructions</span> <span
  m=''1128010''>as</span> <span m=''1128150''>well.</span> <span m=''1129790''>So</span>
  <span m=''1129960''>both</span> <span m=''1130260''>the</span> <span m=''1130330''>hardware</span>
  <span m=''1130800''>and the</span> <span m=''1130920''>software</span> <span m=''1131330''>are</span>
  <span m=''1131430''>going</span> <span m=''1131740''>in</span> <span m=''1131870''>there.</span>
  <span m=''1133120''>So</span> <span m=''1133290''>let''s</span> <span m=''1133510''>take</span>
  <span m=''1133760''>a</span> <span m=''1133790''>look</span> <span m=''1134020''>at
  that.</span> </p><p><span m=''1136720''>So</span> <span m=''1137810''>here''s</span>
  <span m=''1138110''>the</span> <span m=''1138200''>program</span> <span m=''1138840''>order</span>
  <span m=''1139770''>for</span> <span m=''1140650''>one</span> <span m=''1140890''>of</span>
  <span m=''1140930''>the</span> <span m=''1140980''>things.</span> <span m=''1141280''>We</span>
  <span m=''1141380''>move</span> <span m=''1142170''>1</span> <span m=''1142590''>into</span>
  <span m=''1142750''>a,</span> <span m=''1143100''>and</span> <span m=''1143300''>then</span>
  <span m=''1143570''>move</span> <span m=''1144770''>the</span> <span m=''1144990''>value</span>
  <span m=''1145850''>of</span> <span m=''1147560''>b</span> <span m=''1147940''>into</span>
  <span m=''1148210''>EBX</span> <span m=''1149840''>to</span> <span m=''1149960''>do</span>
  <span m=''1150080''>a</span> <span m=''1150140''>load.</span> <span m=''1151210''>Here''s</span>
  <span m=''1151420''>the</span> <span m=''1151510''>program</span> <span m=''1152010''>order.</span>
  <span m=''1153150''>Most</span> <span m=''1153900''>modern</span> <span m=''1154370''>hardware</span>
  <span m=''1156560''>will</span> <span m=''1156740''>switch</span> <span m=''1158170''>these</span>
  <span m=''1158640''>and</span> <span m=''1158780''>execute</span> <span m=''1159320''>it</span>
  <span m=''1159450''>in</span> <span m=''1159760''>this order.</span> <span m=''1161740''>Why</span>
  <span m=''1162030''>do</span> <span m=''1162120''>you</span> <span m=''1162220''>suppose?</span>
  </p><p><span m=''1164360''>Even</span> <span m=''1164640''>if</span> <span m=''1164750''>you</span>
  <span m=''1164890''>write</span> <span m=''1165120''>it</span> <span m=''1165280''>this</span>
  <span m=''1165480''>way,</span> <span m=''1165710''>the</span> <span m=''1165850''>instruction</span>
  <span m=''1166430''>level</span> <span m=''1166740''>parallelism</span> <span m=''1167400''>within</span>
  <span m=''1167690''>the</span> <span m=''1167770''>processor</span> <span m=''1169350''>will,</span>
  <span m=''1170440''>in</span> <span m=''1170640''>fact,</span> <span m=''1171270''>execute</span>
  <span m=''1171810''>it</span> <span m=''1172030''>in</span> <span m=''1172170''>the</span>
  <span m=''1172300''>opposite</span> <span m=''1172750''>order</span> <span m=''1174540''>most</span>
  <span m=''1174880''>of</span> <span m=''1174930''>the</span> <span m=''1174990''>time.</span>
  <span m=''1175260''>Yeah?</span> </p><p><span m=''1175510''>AUDIENCE: Because loading</span>
  <span m=''1175967''>takes</span> <span m=''1176424''>longer.</span> </p><p><span
  m=''1177340''>PROFESSOR: Yeah.</span> <span m=''1177520''>Because</span> <span m=''1177720''>loading</span>
  <span m=''1178150''>takes</span> <span m=''1178500''>longer.</span> <span m=''1179900''>Loading</span>
  <span m=''1182030''>is</span> <span m=''1182300''>going</span> <span m=''1182400''>to</span>
  <span m=''1182480''>take</span> <span m=''1182730''>latency.</span> <span m=''1183290''>I</span>
  <span m=''1183400''>can''t</span> <span m=''1183770''>complete</span> <span m=''1184240''>the</span>
  <span m=''1184330''>load</span> <span m=''1184740''>from</span> <span m=''1184900''>the</span>
  <span m=''1184980''>processor''s</span> <span m=''1185590''>point</span> <span m=''1185790''>of</span>
  <span m=''1185840''>view</span> <span m=''1186110''>until</span> <span m=''1186420''>I</span>
  <span m=''1186480''>get</span> <span m=''1186710''>an</span> <span m=''1186890''>answer.</span>
  <span m=''1187850''>So</span> <span m=''1188070''>if</span> <span m=''1188180''>I</span>
  <span m=''1188310''>load,</span> <span m=''1188960''>and</span> <span m=''1189100''>I</span>
  <span m=''1189160''>wait</span> <span m=''1189540''>for</span> <span m=''1189700''>it
  to</span> <span m=''1189800''>go</span> <span m=''1190030''>out</span> <span m=''1190270''>to</span>
  <span m=''1190350''>the</span> <span m=''1190440''>memory</span> <span m=''1190730''>system</span>
  <span m=''1191150''>and</span> <span m=''1191260''>back</span> <span m=''1191560''>into</span>
  <span m=''1191750''>the</span> <span m=''1191840''>processor,</span> <span m=''1193240''>and</span>
  <span m=''1193490''>then</span> <span m=''1193870''>I</span> <span m=''1194070''>do</span>
  <span m=''1194290''>a</span> <span m=''1194350''>store--</span> <span m=''1196720''>well,
  as soon as I''ve</span> <span m=''1196850''>done</span> <span m=''1197020''>the</span>
  <span m=''1197090''>store,</span> <span m=''1197460''>I</span> <span m=''1197510''>can</span>
  <span m=''1197680''>move</span> <span m=''1197940''>on.</span> </p><p><span m=''1198730''>Even</span>
  <span m=''1198980''>if</span> <span m=''1199080''>the</span> <span m=''1199170''>store</span>
  <span m=''1199500''>takes</span> <span m=''1199750''>a</span> <span m=''1199810''>while</span>
  <span m=''1200160''>to</span> <span m=''1200260''>get</span> <span m=''1200420''>out</span>
  <span m=''1200560''>to</span> <span m=''1200690''>the</span> <span m=''1200770''>memory</span>
  <span m=''1201050''>system.</span> <span m=''1201870''>But</span> <span m=''1202020''>if</span>
  <span m=''1202120''>I</span> <span m=''1202190''>do</span> <span m=''1202340''>it
  in</span> <span m=''1202410''>the</span> <span m=''1202550''>opposite</span> <span
  m=''1202980''>order.</span> <span m=''1203260''>I</span> <span m=''1203320''>do</span>
  <span m=''1203480''>the</span> <span m=''1203570''>store</span> <span m=''1203990''>first,</span>
  <span m=''1206060''>and</span> <span m=''1206220''>then</span> <span m=''1206400''>I</span>
  <span m=''1206500''>do</span> <span m=''1206680''>the</span> <span m=''1206780''>load,</span>
  <span m=''1208600''>I''ve</span> <span m=''1208790''>ended</span> <span m=''1209080''>up</span>
  <span m=''1211650''>wasting</span> <span m=''1212960''>essentially</span> <span
  m=''1213300''>one</span> <span m=''1213580''>cycle,</span> <span m=''1214480''>the</span>
  <span m=''1214590''>cycle</span> <span m=''1214970''>to</span> <span m=''1215090''>do</span>
  <span m=''1215220''>the</span> <span m=''1215330''>store,</span> <span m=''1216340''>when</span>
  <span m=''1216500''>I</span> <span m=''1216560''>could</span> <span m=''1216900''>have</span>
  <span m=''1217200''>been</span> <span m=''1217440''>overlapping</span> <span m=''1218200''>that</span>
  <span m=''1218530''>with</span> <span m=''1218650''>the</span> <span m=''1218740''>time</span>
  <span m=''1219050''>it</span> <span m=''1219160''>took</span> <span m=''1219370''>to</span>
  <span m=''1219470''>do</span> <span m=''1219740''>the</span> <span m=''1219920''>load.</span>
  <span m=''1222500''>So</span> <span m=''1222670''>people</span> <span m=''1222990''>follow</span>
  <span m=''1223280''>that?</span> </p><p><span m=''1223520''>So</span> <span m=''1223650''>if</span>
  <span m=''1223740''>I</span> <span m=''1223860''>execute</span> <span m=''1224390''>the</span>
  <span m=''1224480''>load</span> <span m=''1224860''>first,</span> <span m=''1225780''>I</span>
  <span m=''1225870''>can</span> <span m=''1226060''>go</span> <span m=''1226240''>right</span>
  <span m=''1226560''>on</span> <span m=''1226780''>to</span> <span m=''1226870''>execute</span>
  <span m=''1227380''>the</span> <span m=''1227460''>store.</span> <span m=''1229030''>I</span>
  <span m=''1229300''>can</span> <span m=''1229480''>issue</span> <span m=''1229780''>the</span>
  <span m=''1229890''>load,</span> <span m=''1230800''>go</span> <span m=''1230960''>right</span>
  <span m=''1231200''>on</span> <span m=''1231340''>to</span> <span m=''1231490''>execute</span>
  <span m=''1231980''>the</span> <span m=''1232050''>store</span> <span m=''1233950''>without</span>
  <span m=''1234340''>having</span> <span m=''1234740''>to</span> <span m=''1235220''>wait</span>
  <span m=''1235590''>for</span> <span m=''1235670''>the</span> <span m=''1235760''>load</span>
  <span m=''1236050''>to</span> <span m=''1236200''>complete</span> <span m=''1238040''>if</span>
  <span m=''1238240''>I</span> <span m=''1238350''>have</span> <span m=''1239010''>a</span>
  <span m=''1239160''>multi-issue</span> <span m=''1241160''>CPU</span> <span m=''1242540''>in</span>
  <span m=''1242670''>the</span> <span m=''1242750''>processor</span> <span m=''1243270''>core.</span>
  <span m=''1244950''>So</span> <span m=''1245090''>you</span> <span m=''1245140''>get</span>
  <span m=''1245290''>higher</span> <span m=''1245680''>instruction</span> <span m=''1246210''>level</span>
  <span m=''1246490''>parallelism.</span> </p><p><span m=''1247520''>Now</span> <span
  m=''1249550''>when</span> <span m=''1249740''>is</span> <span m=''1249890''>it</span>
  <span m=''1250030''>safe</span> <span m=''1251700''>for the</span> <span m=''1251880''>hardware</span>
  <span m=''1252370''>compiler</span> <span m=''1252910''>to</span> <span m=''1253000''>perform</span>
  <span m=''1253490''>this</span> <span m=''1253650''>reordering?</span> <span m=''1255930''>Can</span>
  <span m=''1256590''>it</span> <span m=''1256750''>always</span> <span m=''1257290''>switch</span>
  <span m=''1257670''>instructions</span> <span m=''1258430''>like</span> <span m=''1258630''>this</span>
  <span m=''1258810''>to</span> <span m=''1258910''>put</span> <span m=''1259070''>loads</span>
  <span m=''1259420''>before</span> <span m=''1259770''>stores?</span> <span m=''1265360''>When</span>
  <span m=''1265580''>would</span> <span m=''1265730''>this</span> <span m=''1265920''>be</span>
  <span m=''1266040''>a</span> <span m=''1266090''>bad</span> <span m=''1266620''>idea</span>
  <span m=''1268240''>to</span> <span m=''1268340''>put</span> <span m=''1268510''>a</span>
  <span m=''1268580''>load</span> <span m=''1268920''>before</span> <span m=''1269520''>a</span>
  <span m=''1269570''>store?</span> <span m=''1273870''>Yeah?</span> </p><p><span
  m=''1274620''>AUDIENCE: You''re loading</span> <span m=''1275020''>the variable</span>
  <span m=''1275420''>you just</span> <span m=''1275820''>stored.</span> </p><p><span
  m=''1276250''>PROFESSOR: Yeah, if you''re</span> <span m=''1276680''>loading</span>
  <span m=''1277000''>the</span> <span m=''1277100''>variable</span> <span m=''1277540''>you</span>
  <span m=''1277690''>just</span> <span m=''1277880''>stored.</span> <span m=''1279720''>Suppose</span>
  <span m=''1280160''>you</span> <span m=''1280270''>say</span> <span m=''1282000''>store</span>
  <span m=''1282500''>into</span> <span m=''1282780''>x</span> <span m=''1284820''>and</span>
  <span m=''1284970''>then</span> <span m=''1285130''>load</span> <span m=''1285500''>from</span>
  <span m=''1285760''>x.</span> <span m=''1287820''>That''s</span> <span m=''1288070''>different</span>
  <span m=''1288540''>from</span> <span m=''1288760''>if</span> <span m=''1288810''>I</span>
  <span m=''1289190''>load</span> <span m=''1289450''>from</span> <span m=''1289710''>x,</span>
  <span m=''1290020''>and</span> <span m=''1290120''>then</span> <span m=''1290290''>I</span>
  <span m=''1290370''>store</span> <span m=''1290780''>into x.</span> <span m=''1293450''>So</span>
  <span m=''1293700''>if</span> <span m=''1293770''>you''re</span> <span m=''1294450''>going</span>
  <span m=''1294850''>to</span> <span m=''1295000''>the</span> <span m=''1295320''>same</span>
  <span m=''1297310''>location,</span> <span m=''1299960''>then</span> <span m=''1300150''>that''s</span>
  <span m=''1300430''>not</span> <span m=''1300660''>a</span> <span m=''1300710''>safe</span>
  <span m=''1301020''>thing</span> <span m=''1301250''>to</span> <span m=''1301350''>do.</span>
  </p><p><span m=''1303540''>So</span> <span m=''1305940''>basically,</span> <span
  m=''1306480''>in</span> <span m=''1306580''>this</span> <span m=''1306790''>case,</span>
  <span m=''1307390''>if</span> <span m=''1308626''>a</span> <span m=''1309070''>is</span>
  <span m=''1309330''>not</span> <span m=''1309570''>equal</span> <span m=''1309860''>to</span>
  <span m=''1309920''>b,</span> <span m=''1312090''>then</span> <span m=''1312460''>this</span>
  <span m=''1312620''>is</span> <span m=''1312720''>safe</span> <span m=''1313050''>to</span>
  <span m=''1313180''>do.</span> <span m=''1313815''>But</span> <span m=''1314090''>if</span>
  <span m=''1314190''>a</span> <span m=''1314380''>equals</span> <span m=''1314910''>b,</span>
  <span m=''1315850''>this</span> <span m=''1316030''>is</span> <span m=''1316190''>not</span>
  <span m=''1316430''>safe</span> <span m=''1316690''>to</span> <span m=''1316810''>do.</span>
  <span m=''1319780''>Because</span> <span m=''1321350''>it''s</span> <span m=''1321460''>going</span>
  <span m=''1321560''>to</span> <span m=''1321600''>give</span> <span m=''1321740''>you
  a</span> <span m=''1321830''>different</span> <span m=''1322120''>answer.</span>
  </p><p><span m=''1324680''>However,</span> <span m=''1325170''>it</span> <span m=''1325320''>turns</span>
  <span m=''1325680''>out</span> <span m=''1326710''>that</span> <span m=''1326930''>there''s</span>
  <span m=''1327160''>another</span> <span m=''1327510''>time</span> <span m=''1327880''>when</span>
  <span m=''1328010''>this</span> <span m=''1328190''>is</span> <span m=''1328300''>not</span>
  <span m=''1328540''>safe</span> <span m=''1328780''>to</span> <span m=''1328930''>do.</span>
  <span m=''1329790''>So</span> <span m=''1329950''>this</span> <span m=''1330180''>would</span>
  <span m=''1330390''>have</span> <span m=''1330470''>been</span> <span m=''1330560''>the</span>
  <span m=''1330700''>end</span> <span m=''1330870''>of</span> <span m=''1330930''>the</span>
  <span m=''1331040''>story</span> <span m=''1332210''>if</span> <span m=''1332380''>we</span>
  <span m=''1332510''>were</span> <span m=''1332600''>running</span> <span m=''1332970''>on</span>
  <span m=''1333240''>one</span> <span m=''1333620''>processor.</span> <span m=''1334320''>The</span>
  <span m=''1334580''>other</span> <span m=''1334830''>time</span> <span m=''1335530''>that</span>
  <span m=''1335650''>it''s</span> <span m=''1335840''>not</span> <span m=''1336370''>safe</span>
  <span m=''1336770''>to</span> <span m=''1336880''>do</span> <span m=''1337080''>it</span>
  <span m=''1337450''>is--</span> <span m=''1338350''>if</span> <span m=''1339250''>it''s</span>
  <span m=''1339720''>safe,</span> <span m=''1340300''>the</span> <span m=''1340490''>other</span>
  <span m=''1341870''>assumption</span> <span m=''1342430''>is</span> <span m=''1342750''>that</span>
  <span m=''1342940''>there''s</span> <span m=''1343120''>no</span> <span m=''1343320''>concurrency.</span>
  <span m=''1344260''>If</span> <span m=''1344460''>there</span> <span m=''1344710''>is</span>
  <span m=''1345220''>concurrency,</span> <span m=''1346670''>you</span> <span m=''1346840''>can</span>
  <span m=''1347010''>run</span> <span m=''1347230''>into</span> <span m=''1347460''>trouble</span>
  <span m=''1347900''>as</span> <span m=''1348020''>well.</span> <span m=''1350920''>And</span>
  <span m=''1351520''>the</span> <span m=''1351650''>reason</span> <span m=''1352050''>is</span>
  <span m=''1352240''>because</span> <span m=''1352780''>another</span> <span m=''1353250''>processor</span>
  <span m=''1354100''>may be</span> <span m=''1354420''>changing</span> <span m=''1354990''>the</span>
  <span m=''1355080''>value</span> <span m=''1356190''>that</span> <span m=''1356340''>you''re</span>
  <span m=''1356500''>planning</span> <span m=''1356900''>to</span> <span m=''1357050''>read.</span>
  <span m=''1359710''>And</span> <span m=''1359910''>so</span> <span m=''1360130''>if</span>
  <span m=''1360240''>you</span> <span m=''1360370''>read</span> <span m=''1360640''>things</span>
  <span m=''1360910''>out</span> <span m=''1361090''>of</span> <span m=''1361170''>order,</span>
  <span m=''1361870''>you</span> <span m=''1362010''>may</span> <span m=''1362210''>violate</span>
  <span m=''1362780''>sequential</span> <span m=''1363280''>consistency.</span> </p><p><span
  m=''1365180''>Let</span> <span m=''1365330''>me</span> <span m=''1365420''>show</span>
  <span m=''1365670''>you</span> <span m=''1365810''>what''s</span> <span m=''1366050''>going</span>
  <span m=''1366300''>on</span> <span m=''1366500''>in</span> <span m=''1366580''>the</span>
  <span m=''1366650''>hardware</span> <span m=''1367190''>so</span> <span m=''1367310''>you</span>
  <span m=''1367390''>have</span> <span m=''1367560''>an</span> <span m=''1367620''>appreciation</span>
  <span m=''1368860''>of</span> <span m=''1369010''>what</span> <span m=''1369200''>the</span>
  <span m=''1369340''>issue</span> <span m=''1369620''>is</span> <span m=''1369760''>here.</span>
  <span m=''1371030''>So</span> <span m=''1371250''>here''s</span> <span m=''1373520''>30,000</span>
  <span m=''1374350''>feet</span> <span m=''1374700''>of</span> <span m=''1374810''>hardware</span>
  <span m=''1375360''>reordering.</span> <span m=''1376940''>So</span> <span m=''1377110''>the</span>
  <span m=''1377200''>processor</span> <span m=''1377900''>is</span> <span m=''1378030''>going</span>
  <span m=''1378140''>to</span> <span m=''1378290''>issue</span> <span m=''1379760''>memory</span>
  <span m=''1381900''>operations</span> <span m=''1382600''>to</span> <span m=''1382770''>the</span>
  <span m=''1382880''>memory</span> <span m=''1383210''>system.</span> <span m=''1384050''>And</span>
  <span m=''1385060''>results</span> <span m=''1385510''>of</span> <span m=''1385580''>memory</span>
  <span m=''1385880''>operations</span> <span m=''1386480''>are</span> <span m=''1386560''>going</span>
  <span m=''1386690''>to</span> <span m=''1386760''>come</span> <span m=''1386950''>back.</span>
  <span m=''1388480''>But</span> <span m=''1388660''>they</span> <span m=''1388760''>really</span>
  <span m=''1389050''>only</span> <span m=''1389260''>have</span> <span m=''1389480''>to</span>
  <span m=''1389600''>come</span> <span m=''1389810''>back</span> <span m=''1390630''>when?</span>
  <span m=''1392280''>If</span> <span m=''1392460''>they''re</span> <span m=''1393790''>loads.</span>
  <span m=''1394670''>If</span> <span m=''1394850''>they''re</span> <span m=''1394960''>stores,</span>
  <span m=''1396020''>they</span> <span m=''1396130''>don''t</span> <span m=''1396250''>have</span>
  <span m=''1396410''>to</span> <span m=''1396510''>come</span> <span m=''1396670''>back.</span>
  </p><p><span m=''1399040''>So</span> <span m=''1400590''>the</span> <span m=''1400750''>processor,</span>
  <span m=''1401690''>in</span> <span m=''1401870''>fact,</span> <span m=''1402320''>can</span>
  <span m=''1402410''>issue</span> <span m=''1402740''>stores</span> <span m=''1403250''>faster</span>
  <span m=''1404290''>than</span> <span m=''1404470''>the</span> <span m=''1404570''>network</span>
  <span m=''1405600''>can</span> <span m=''1405780''>handle</span> <span m=''1406150''>them.</span>
  <span m=''1406320''>And</span> <span m=''1406440''>the</span> <span m=''1406510''>memory</span>
  <span m=''1406790''>system</span> <span m=''1407170''>can</span> <span m=''1407310''>handle</span>
  <span m=''1407630''>them.</span> <span m=''1408190''>So the</span> <span m=''1408280''>processors</span>
  <span m=''1408740''>are</span> <span m=''1408830''>generally</span> <span m=''1409150''>very</span>
  <span m=''1409360''>fast.</span> <span m=''1409780''>The</span> <span m=''1409860''>memory</span>
  <span m=''1410140''>systems</span> <span m=''1410520''>are</span> <span m=''1410610''>relatively</span>
  <span m=''1411310''>slow.</span> </p><p><span m=''1413520''>But</span> <span m=''1413620''>the</span>
  <span m=''1413700''>processor</span> <span m=''1414300''>is</span> <span m=''1414390''>not</span>
  <span m=''1414700''>generally</span> <span m=''1415170''>issuing</span> <span m=''1415610''>a</span>
  <span m=''1415670''>store</span> <span m=''1416120''>on</span> <span m=''1416220''>every</span>
  <span m=''1416430''>cycle.</span> <span m=''1417850''>It may do</span> <span m=''1418080''>store,</span>
  <span m=''1418570''>it may</span> <span m=''1418750''>do</span> <span m=''1418920''>some</span>
  <span m=''1419120''>additions,</span> <span m=''1419485''>it</span> <span m=''1419850''>may</span>
  <span m=''1420000''>do</span> <span m=''1420150''>another</span> <span m=''1420440''>store,</span>
  <span m=''1421520''>et</span> <span m=''1421700''>cetera.</span> <span m=''1422720''>So</span>
  <span m=''1423130''>rather</span> <span m=''1423550''>than</span> <span m=''1423960''>waiting</span>
  <span m=''1424870''>for</span> <span m=''1424970''>the</span> <span m=''1425060''>memory</span>
  <span m=''1425560''>system</span> <span m=''1425890''>to</span> <span m=''1426020''>do</span>
  <span m=''1426300''>every</span> <span m=''1426580''>store,</span> <span m=''1427420''>they</span>
  <span m=''1427530''>create</span> <span m=''1427860''>a</span> <span m=''1427910''>store</span>
  <span m=''1428260''>buffer.</span> <span m=''1429570''>And</span> <span m=''1429820''>the</span>
  <span m=''1429990''>memory</span> <span m=''1430340''>system</span> <span m=''1430730''>pulls</span>
  <span m=''1431100''>things</span> <span m=''1431350''>out</span> <span m=''1431520''>of</span>
  <span m=''1431590''>the</span> <span m=''1431650''>store</span> <span m=''1432010''>buffer</span>
  <span m=''1432820''>as</span> <span m=''1433000''>fast</span> <span m=''1433370''>as</span>
  <span m=''1433500''>it</span> <span m=''1433660''>can.</span> <span m=''1434880''>And</span>
  <span m=''1435010''>the</span> <span m=''1435140''>processor</span> <span m=''1436150''>shoves</span>
  <span m=''1436410''>stuff</span> <span m=''1436770''>into</span> <span m=''1436980''>the</span>
  <span m=''1437070''>store</span> <span m=''1437380''>buffer</span> <span m=''1437730''>up</span>
  <span m=''1437840''>to</span> <span m=''1437940''>the</span> <span m=''1438020''>point</span>
  <span m=''1438340''>that</span> <span m=''1438400''>the</span> <span m=''1438490''>store</span>
  <span m=''1438780''>buffer</span> <span m=''1439100''>gets</span> <span m=''1439380''>full,</span>
  <span m=''1440100''>in</span> <span m=''1440170''>which</span> <span m=''1440360''>case</span>
  <span m=''1440550''>it</span> <span m=''1440640''>would</span> <span m=''1440820''>have</span>
  <span m=''1441000''>to</span> <span m=''1441110''>stall.</span> <span m=''1441540''>But</span>
  <span m=''1441830''>for</span> <span m=''1441980''>most</span> <span m=''1442350''>many</span>
  <span m=''1442650''>codes,</span> <span m=''1443600''>it</span> <span m=''1443750''>never</span>
  <span m=''1443990''>has</span> <span m=''1444240''>to</span> <span m=''1444350''>stall</span>
  <span m=''1444830''>because</span> <span m=''1446630''>there</span> <span m=''1446890''>is</span>
  <span m=''1447080''>a</span> <span m=''1448000''>sufficient</span> <span m=''1448580''>frequency</span>
  <span m=''1449270''>of</span> <span m=''1449460''>other</span> <span m=''1449750''>operations</span>
  <span m=''1450400''>going</span> <span m=''1450670''>on</span> <span m=''1451390''>that</span>
  <span m=''1451550''>you</span> <span m=''1451650''>don''t</span> <span m=''1452620''>have</span>
  <span m=''1452870''>to</span> <span m=''1452990''>wait.</span> <span m=''1453730''>So</span>
  <span m=''1453930''>when</span> <span m=''1454050''>a</span> <span m=''1454100''>store</span>
  <span m=''1454470''>occurs,</span> <span m=''1454910''>it</span> <span m=''1455030''>doesn''t</span>
  <span m=''1455290''>occur</span> <span m=''1455590''>immediately</span> <span m=''1456150''>on</span>
  <span m=''1456280''>the</span> <span m=''1456400''>store</span> <span m=''1456750''>buffer.</span>
  </p><p><span m=''1458480''>Now</span> <span m=''1458750''>along</span> <span m=''1459290''>comes</span>
  <span m=''1460640''>a</span> <span m=''1461430''>load</span> <span m=''1462200''>operation.</span>
  <span m=''1463700''>And</span> <span m=''1463810''>the</span> <span m=''1463900''>load</span>
  <span m=''1464190''>operation,</span> <span m=''1464820''>if</span> <span m=''1464930''>it''s</span>
  <span m=''1465150''>to</span> <span m=''1465280''>a</span> <span m=''1465360''>different</span>
  <span m=''1465700''>address,</span> <span m=''1468120''>you</span> <span m=''1468290''>want</span>
  <span m=''1468430''>to</span> <span m=''1468540''>have</span> <span m=''1468650''>that</span>
  <span m=''1468920''>take</span> <span m=''1469120''>priority</span> <span m=''1469540''>because</span>
  <span m=''1469690''>the</span> <span m=''1469790''>processor</span> <span m=''1470540''>can</span>
  <span m=''1470710''>be</span> <span m=''1470840''>waiting.</span> <span m=''1471920''>It''s</span>
  <span m=''1472120''>next</span> <span m=''1472420''>instructions</span> <span m=''1473060''>may</span>
  <span m=''1473220''>be</span> <span m=''1473340''>waiting</span> <span m=''1473760''>on</span>
  <span m=''1473930''>the</span> <span m=''1474010''>result.</span> <span m=''1476090''>So</span>
  <span m=''1476230''>you</span> <span m=''1476330''>want</span> <span m=''1476510''>that</span>
  <span m=''1476700''>to</span> <span m=''1476880''>go as</span> <span m=''1477010''>fast</span>
  <span m=''1477360''>as</span> <span m=''1477460''>possible.</span> </p><p><span
  m=''1479910''>They</span> <span m=''1480100''>have</span> <span m=''1480290''>a</span>
  <span m=''1481140''>passing</span> <span m=''1481620''>lane</span> <span m=''1481850''>here</span>
  <span m=''1483220''>where</span> <span m=''1484020''>the</span> <span m=''1484140''>fast</span>
  <span m=''1484570''>cars</span> <span m=''1485020''>or</span> <span m=''1485110''>the</span>
  <span m=''1485190''>important</span> <span m=''1485630''>cars,</span> <span m=''1486050''>the</span>
  <span m=''1486200''>ambulances,</span> <span m=''1486540''>et cetera,</span> <span
  m=''1487300''>in</span> <span m=''1487400''>this</span> <span m=''1487550''>case</span>
  <span m=''1487780''>loads,</span> <span m=''1488670''>can</span> <span m=''1488920''>scoot</span>
  <span m=''1489350''>by</span> <span m=''1489710''>all</span> <span m=''1489950''>the</span>
  <span m=''1490080''>other</span> <span m=''1490730''>things</span> <span m=''1491000''>in</span>
  <span m=''1491120''>traffic</span> <span m=''1491640''>and</span> <span m=''1492010''>get</span>
  <span m=''1492170''>to</span> <span m=''1492240''>the</span> <span m=''1492320''>memory</span>
  <span m=''1492600''>system</span> <span m=''1492960''>first.</span> <span m=''1493980''>But</span>
  <span m=''1494160''>as</span> <span m=''1494270''>we</span> <span m=''1494410''>said,</span>
  <span m=''1495390''>we</span> <span m=''1495510''>don''t</span> <span m=''1495720''>want</span>
  <span m=''1495870''>to</span> <span m=''1495940''>do</span> <span m=''1496190''>that</span>
  <span m=''1496720''>if</span> <span m=''1496880''>the</span> <span m=''1496960''>last</span>
  <span m=''1497350''>thing</span> <span m=''1497510''>that</span> <span m=''1497640''>I</span>
  <span m=''1497730''>stored</span> <span m=''1499200''>was</span> <span m=''1500010''>to</span>
  <span m=''1500610''>the</span> <span m=''1500700''>same</span> <span m=''1501010''>address.</span>
  </p><p><span m=''1501850''>So</span> <span m=''1502160''>in</span> <span m=''1502270''>fact,</span>
  <span m=''1503140''>there</span> <span m=''1503390''>is</span> <span m=''1503640''>content</span>
  <span m=''1504130''>addressable</span> <span m=''1504660''>memory</span> <span m=''1505040''>here,</span>
  <span m=''1505710''>which</span> <span m=''1505890''>matches</span> <span m=''1506980''>the</span>
  <span m=''1507190''>address</span> <span m=''1507780''>that</span> <span m=''1507930''>is</span>
  <span m=''1508080''>being</span> <span m=''1508290''>loaded</span> <span m=''1508950''>with</span>
  <span m=''1509180''>everything</span> <span m=''1509660''>in</span> <span m=''1509750''>the</span>
  <span m=''1509830''>store</span> <span m=''1510200''>buffer.</span> <span m=''1511780''>And</span>
  <span m=''1511960''>if</span> <span m=''1512070''>it</span> <span m=''1512250''>does</span>
  <span m=''1512560''>match,</span> <span m=''1513290''>it</span> <span m=''1513430''>gets</span>
  <span m=''1513660''>satisfied</span> <span m=''1514340''>immediately</span> <span
  m=''1514860''>by</span> <span m=''1515050''>the</span> <span m=''1515150''>store</span>
  <span m=''1515470''>buffer.</span> <span m=''1517340''>And</span> <span m=''1517510''>only</span>
  <span m=''1518420''>does</span> <span m=''1518600''>it</span> <span m=''1518680''>make</span>
  <span m=''1518870''>it</span> <span m=''1518960''>out</span> <span m=''1519150''>to</span>
  <span m=''1519240''>the</span> <span m=''1519320''>network</span> <span m=''1521160''>if</span>
  <span m=''1521350''>it''s</span> <span m=''1521520''>not</span> <span m=''1521780''>in</span>
  <span m=''1521880''>the</span> <span m=''1521940''>store</span> <span m=''1522250''>buffer.</span>
  </p><p><span m=''1523940''>But</span> <span m=''1524140''>what</span> <span m=''1524300''>you</span>
  <span m=''1524410''>can</span> <span m=''1524540''>see</span> <span m=''1524870''>here</span>
  <span m=''1525170''>is</span> <span m=''1525530''>that</span> <span m=''1525830''>this</span>
  <span m=''1526030''>mechanism,</span> <span m=''1527090''>which</span> <span m=''1527350''>works</span>
  <span m=''1527710''>great</span> <span m=''1528180''>on</span> <span m=''1528410''>one</span>
  <span m=''1528790''>processor,</span> <span m=''1531320''>violates</span> <span
  m=''1531980''>sequential</span> <span m=''1532510''>consistency</span> <span m=''1533290''>because</span>
  <span m=''1533720''>I</span> <span m=''1533880''>may</span> <span m=''1534150''>have</span>
  <span m=''1534480''>operations</span> <span m=''1535640''>going</span> <span m=''1535840''>to</span>
  <span m=''1536030''>two</span> <span m=''1536230''>different</span> <span m=''1536550''>memory</span>
  <span m=''1536880''>locations,</span> <span m=''1538720''>where</span> <span m=''1539520''>the</span>
  <span m=''1539660''>order,</span> <span m=''1540040''>in</span> <span m=''1540200''>fact,</span>
  <span m=''1540580''>matters</span> <span m=''1541050''>to</span> <span m=''1541210''>me.</span>
  <span m=''1542600''>So</span> <span m=''1542750''>let''s</span> <span m=''1542990''>see</span>
  <span m=''1543970''>how</span> <span m=''1544100''>that</span> <span m=''1544370''>works</span>
  <span m=''1544660''>out.</span> </p><p><span m=''1545150''>So</span> <span m=''1545360''>first</span>
  <span m=''1545630''>of</span> <span m=''1545690''>all,</span> <span m=''1545850''>let</span>
  <span m=''1545970''>me</span> <span m=''1546490''>tell</span> <span m=''1546710''>you</span>
  <span m=''1546820''>what</span> <span m=''1547010''>the</span> <span m=''1547100''>memory</span>
  <span m=''1547530''>can--</span> <span m=''1547660''>so</span> <span m=''1547930''>a</span>
  <span m=''1547990''>load</span> <span m=''1548500''>can</span> <span m=''1548640''>bypass</span>
  <span m=''1549130''>a</span> <span m=''1549200''>store</span> <span m=''1549510''>to</span>
  <span m=''1549640''>different</span> <span m=''1549920''>address.</span> <span m=''1550580''>First
  of all,</span> <span m=''1550910''>any</span> <span m=''1551150''>questions</span>
  <span m=''1551590''>about</span> <span m=''1553440''>this</span> <span m=''1553630''>mechanism?</span>
  <span m=''1554350''>So</span> <span m=''1555250''>this</span> <span m=''1558230''>accounts</span>
  <span m=''1558770''>for</span> <span m=''1559200''>a</span> <span m=''1559270''>whole</span>
  <span m=''1559630''>bunch</span> <span m=''1560610''>of</span> <span m=''1561120''>understanding</span>
  <span m=''1562200''>of</span> <span m=''1562500''>what</span> <span m=''1562650''>happens</span>
  <span m=''1563220''>in</span> <span m=''1564140''>concurrency</span> <span m=''1564370''>in</span>
  <span m=''1564520''>systems.</span> <span m=''1565020''>This</span> <span m=''1565210''>one</span>
  <span m=''1565970''>understanding</span> <span m=''1566670''>of</span> <span m=''1566760''>store</span>
  <span m=''1567060''>buffers.</span> <span m=''1568810''>It''s</span> <span m=''1569960''>absolutely</span>
  <span m=''1571300''>crucial.</span> </p><p><span m=''1571620''>And</span> <span
  m=''1571840''>I</span> <span m=''1571960''>have</span> <span m=''1572080''>talked,</span>
  <span m=''1572500''>by</span> <span m=''1572620''>the</span> <span m=''1572710''>way,</span>
  <span m=''1572900''>with</span> <span m=''1573070''>lots</span> <span m=''1573450''>of</span>
  <span m=''1573600''>experts</span> <span m=''1574610''>who</span> <span m=''1574710''>don''t</span>
  <span m=''1574980''>understand</span> <span m=''1575990''>this.</span> <span m=''1576255''>That</span>
  <span m=''1576520''>this</span> <span m=''1576840''>is</span> <span m=''1576950''>what''s</span>
  <span m=''1577200''>going</span> <span m=''1577480''>on</span> <span m=''1577710''>for</span>
  <span m=''1577850''>why</span> <span m=''1578250''>we</span> <span m=''1578420''>don''t</span>
  <span m=''1578660''>have</span> <span m=''1579340''>sequential</span> <span m=''1579880''>consistency</span>
  <span m=''1580580''>in</span> <span m=''1580700''>our</span> <span m=''1581340''>computers.</span>
  <span m=''1582420''>It''s</span> <span m=''1582560''>because</span> <span m=''1582870''>they</span>
  <span m=''1582990''>made</span> <span m=''1583400''>the</span> <span m=''1583780''>decision</span>
  <span m=''1584890''>to</span> <span m=''1585060''>allow</span> <span m=''1585500''>this</span>
  <span m=''1585760''>optimization,</span> <span m=''1586980''>even</span> <span m=''1587290''>though</span>
  <span m=''1587520''>it</span> <span m=''1587620''>doesn''t</span> <span m=''1588030''>preserve</span>
  <span m=''1588540''>sequential</span> <span m=''1589040''>consistency.</span> </p><p><span
  m=''1591250''>There</span> <span m=''1591400''>were</span> <span m=''1591850''>machines</span>
  <span m=''1592320''>in</span> <span m=''1592380''>the</span> <span m=''1592620''>past</span>
  <span m=''1592850''>that</span> <span m=''1592950''>did</span> <span m=''1593300''>support</span>
  <span m=''1593750''>sequential</span> <span m=''1594170''>consistency.</span> <span
  m=''1594840''>And</span> <span m=''1594920''>what</span> <span m=''1595140''>they</span>
  <span m=''1595320''>did</span> <span m=''1595890''>was</span> <span m=''1596150''>they</span>
  <span m=''1596340''>used</span> <span m=''1596570''>speculation</span> <span m=''1598630''>to</span>
  <span m=''1599470''>allow</span> <span m=''1600040''>the</span> <span m=''1600140''>processor</span>
  <span m=''1600850''>to</span> <span m=''1601010''>assume</span> <span m=''1601490''>that</span>
  <span m=''1601610''>it</span> <span m=''1601650''>was</span> <span m=''1601790''>sequentially</span>
  <span m=''1602350''>consistent.</span> <span m=''1603010''>And</span> <span m=''1603200''>if</span>
  <span m=''1603310''>that</span> <span m=''1603540''>turned</span> <span m=''1603760''>out</span>
  <span m=''1603950''>to</span> <span m=''1604030''>be</span> <span m=''1604180''>wrong,</span>
  <span m=''1604900''>they</span> <span m=''1605060''>were</span> <span m=''1605150''>able</span>
  <span m=''1605360''>to</span> <span m=''1605400''>roll</span> <span m=''1605820''>back</span>
  <span m=''1606150''>the</span> <span m=''1606230''>processor''s</span> <span m=''1606830''>state</span>
  <span m=''1608210''>to</span> <span m=''1608360''>the</span> <span m=''1608500''>point</span>
  <span m=''1608940''>before</span> <span m=''1609430''>the</span> <span m=''1611200''>access</span>
  <span m=''1611670''>was</span> <span m=''1611860''>done.</span> </p><p><span m=''1612440''>In</span>
  <span m=''1612550''>fact,</span> <span m=''1612810''>the</span> <span m=''1612880''>processor</span>
  <span m=''1613540''>is</span> <span m=''1613640''>already</span> <span m=''1614160''>doing</span>
  <span m=''1614560''>that</span> <span m=''1615070''>for</span> <span m=''1615340''>branches,</span>
  <span m=''1616520''>where</span> <span m=''1616700''>it</span> <span m=''1616760''>makes</span>
  <span m=''1617040''>branch</span> <span m=''1617440''>predictions</span> <span m=''1618040''>and</span>
  <span m=''1618340''>executes</span> <span m=''1618910''>down</span> <span m=''1619120''>a</span>
  <span m=''1619200''>line.</span> <span m=''1619840''>But</span> <span m=''1620000''>it''s</span>
  <span m=''1620160''>wrong,</span> <span m=''1620850''>it</span> <span m=''1620980''>has</span>
  <span m=''1621200''>to</span> <span m=''1621310''>flush</span> <span m=''1621650''>the</span>
  <span m=''1621800''>pipeline</span> <span m=''1622930''>and</span> <span m=''1623310''>so</span>
  <span m=''1623500''>forth.</span> <span m=''1624180''>Why</span> <span m=''1625620''>they</span>
  <span m=''1625800''>don''t</span> <span m=''1626130''>do</span> <span m=''1626260''>the</span>
  <span m=''1626380''>same</span> <span m=''1627010''>thing</span> <span m=''1627470''>for</span>
  <span m=''1628580''>hardware</span> <span m=''1629200''>is</span> <span m=''1629390''>an</span>
  <span m=''1629540''>interesting--</span> <span m=''1630530''>for</span> <span m=''1631860''>loads</span>
  <span m=''1632320''>of</span> <span m=''1632430''>stores--</span> <span m=''1632800''>is</span>
  <span m=''1632940''>an</span> <span m=''1633020''>interesting</span> <span m=''1633430''>question.</span>
  <span m=''1633900''>Because</span> <span m=''1634750''>at</span> <span m=''1634930''>some</span>
  <span m=''1635180''>level</span> <span m=''1635520''>there''s</span> <span m=''1635690''>no</span>
  <span m=''1635850''>reason</span> <span m=''1636170''>they</span> <span m=''1636300''>couldn''t</span>
  <span m=''1636600''>do</span> <span m=''1636750''>this.</span> </p><p><span m=''1637970''>Instead,</span>
  <span m=''1638890''>it''s</span> <span m=''1639140''>sort</span> <span m=''1639340''>of</span>
  <span m=''1639440''>been</span> <span m=''1639840''>a</span> <span m=''1640070''>thing</span>
  <span m=''1640270''>where</span> <span m=''1640370''>the</span> <span m=''1640490''>software</span>
  <span m=''1640890''>people</span> <span m=''1641160''>say,</span> <span m=''1641380''>yeah</span>
  <span m=''1641700''>we</span> <span m=''1641830''>can</span> <span m=''1641970''>handle</span>
  <span m=''1642390''>it.</span> <span m=''1643020''>And</span> <span m=''1643140''>the</span>
  <span m=''1643190''>hardware</span> <span m=''1643580''>people</span> <span m=''1643920''>say,</span>
  <span m=''1644160''>OK.</span> <span m=''1644480''>You''re</span> <span m=''1644880''>willing</span>
  <span m=''1645110''>to</span> <span m=''1645160''>handle</span> <span m=''1645420''>it.</span>
  <span m=''1646240''>We</span> <span m=''1646370''>won''t</span> <span m=''1646710''>worry</span>
  <span m=''1646990''>about</span> <span m=''1647240''>it</span> <span m=''1647370''>then.</span>
  <span m=''1648170''>When</span> <span m=''1648330''>in</span> <span m=''1648430''>fact,</span>
  <span m=''1649430''>it</span> <span m=''1649600''>just</span> <span m=''1649810''>makes</span>
  <span m=''1650070''>life</span> <span m=''1650530''>complicated</span> <span m=''1651260''>for</span>
  <span m=''1651440''>everybody</span> <span m=''1652360''>that you</span> <span m=''1652520''>don''t</span>
  <span m=''1652720''>have</span> <span m=''1652940''>sequential</span> <span m=''1653400''>consistency.</span>
  </p><p><span m=''1654100''>AUDIENCE: [INAUDIBLE]</span> <span m=''1656465''>you
  have</span> <span m=''1656938''>to do</span> <span m=''1657884''>speculation</span>
  <span m=''1658357''>across</span> <span m=''1659303''>both</span> <span m=''1659776''>[INAUDIBLE].</span>
  </p><p><span m=''1661670''>PROFESSOR: Well</span> <span m=''1661900''>here,</span>
  <span m=''1662090''>you</span> <span m=''1662200''>only</span> <span m=''1662380''>have</span>
  <span m=''1662520''>to do</span> <span m=''1662690''>speculation</span> <span m=''1663340''>over</span>
  <span m=''1663530''>what</span> <span m=''1663730''>actually</span> <span m=''1664140''>is</span>
  <span m=''1664270''>coming</span> <span m=''1664540''>out</span> <span m=''1664670''>of</span>
  <span m=''1664760''>your</span> <span m=''1664870''>memory</span> <span m=''1665150''>system.</span>
  <span m=''1665730''>And</span> <span m=''1665850''>if</span> <span m=''1665910''>it</span>
  <span m=''1666030''>doesn''t</span> <span m=''1666330''>match,</span> <span m=''1667210''>you</span>
  <span m=''1667370''>could</span> <span m=''1667510''>roll</span> <span m=''1667760''>back.</span>
  <span m=''1669310''>The</span> <span m=''1669580''>issue,</span> <span m=''1669850''>in</span>
  <span m=''1670020''>part,</span> <span m=''1670430''>is</span> <span m=''1670620''>how</span>
  <span m=''1670820''>many</span> <span m=''1672130''>machine</span> <span m=''1672530''>states</span>
  <span m=''1672880''>are you</span> <span m=''1673050''>ready</span> <span m=''1673280''>to</span>
  <span m=''1673380''>roll</span> <span m=''1673630''>back</span> <span m=''1673970''>to.</span>
  <span m=''1674860''>Loads</span> <span m=''1675230''>come</span> <span m=''1675430''>more</span>
  <span m=''1675610''>frequently</span> <span m=''1676070''>than</span> <span m=''1676210''>branches.</span>
  <span m=''1676810''>That''s</span> <span m=''1677030''>one</span> <span m=''1677240''>thing.</span>
  <span m=''1677940''>So</span> <span m=''1679680''>no</span> <span m=''1679920''>doubt,</span>
  <span m=''1680240''>there</span> <span m=''1680360''>are</span> <span m=''1680410''>good</span>
  <span m=''1680610''>reasons</span> <span m=''1681080''>for</span> <span m=''1681200''>why</span>
  <span m=''1681400''>they''re</span> <span m=''1681520''>doing</span> <span m=''1681840''>it.</span>
  <span m=''1682090''>Nevertheless,</span> <span m=''1683730''>definitely</span> <span
  m=''1684160''>loss</span> <span m=''1684490''>of</span> <span m=''1684580''>sequential</span>
  <span m=''1685020''>consistency</span> <span m=''1686080''>becomes</span> <span
  m=''1686460''>a</span> <span m=''1686500''>headache</span> <span m=''1686920''>for</span>
  <span m=''1687040''>a</span> <span m=''1687080''>lot</span> <span m=''1687290''>of</span>
  <span m=''1687360''>people</span> <span m=''1687980''>in</span> <span m=''1688250''>doing</span>
  <span m=''1688660''>a</span> <span m=''1688830''>concurrent</span> <span m=''1689200''>program.</span>
  <span m=''1689700''>We</span> <span m=''1689830''>had</span> <span m=''1689890''>a</span>
  <span m=''1689940''>question</span> <span m=''1690270''>here?</span> <span m=''1690440''>Yes,</span>
  <span m=''1690690''>Sara?</span> </p><p><span m=''1691570''>AUDIENCE: So</span>
  <span m=''1692040''>this does</span> <span m=''1692510''>not preserve sequential
  consistency?</span> <span m=''1693450''>But as long</span> <span m=''1693920''>as
  there''s only</span> <span m=''1694390''>one processor,</span> <span m=''1694860''>it</span>
  <span m=''1695330''>should</span> <span m=''1695800''>have the same</span> <span
  m=''1696270''>effect,</span> <span m=''1696750''>right?</span> </p><p><span m=''1698050''>PROFESSOR:
  But</span> <span m=''1698290''>sequential</span> <span m=''1698750''>consistency</span>
  <span m=''1699400''>for</span> <span m=''1699530''>one</span> <span m=''1699760''>processor</span>
  <span m=''1700320''>is</span> <span m=''1700440''>easy</span> <span m=''1700710''>because</span>
  <span m=''1701000''>all</span> <span m=''1701140''>you</span> <span m=''1701220''>do</span>
  <span m=''1701360''>is</span> <span m=''1701480''>execute</span> <span m=''1701835''>them--</span>
  </p><p><span m=''1702190''>AUDIENCE: Yeah, I''m just saying--</span> </p><p><span
  m=''1703170''>PROFESSOR: It</span> <span m=''1703490''>should</span> <span m=''1703620''>have</span>
  <span m=''1703750''>the</span> <span m=''1703810''>same</span> <span m=''1704080''>effect,</span>
  <span m=''1704950''>exactly.</span> <span m=''1705450''>So</span> <span m=''1705760''>on</span>
  <span m=''1705890''>one</span> <span m=''1706140''>processor,</span> <span m=''1707160''>this</span>
  <span m=''1707370''>works</span> <span m=''1708270''>perfectly</span> <span m=''1708730''>well.</span>
  <span m=''1710080''>If</span> <span m=''1710210''>there''s</span> <span m=''1710370''>no</span>
  <span m=''1710570''>concurrency,</span> <span m=''1711830''>this</span> <span m=''1712090''>is</span>
  <span m=''1712220''>going</span> <span m=''1712340''>to</span> <span m=''1712380''>give</span>
  <span m=''1712590''>you</span> <span m=''1712710''>the</span> <span m=''1712820''>same</span>
  <span m=''1713290''>behavior.</span> <span m=''1714520''>And</span> <span m=''1714720''>yet,</span>
  <span m=''1714990''>you''ve</span> <span m=''1715170''>now</span> <span m=''1715770''>got</span>
  <span m=''1715960''>this</span> <span m=''1716120''>optimization</span> <span m=''1717480''>that</span>
  <span m=''1717940''>loads</span> <span m=''1718310''>can</span> <span m=''1718470''>bypass</span>
  <span m=''1718970''>stores.</span> <span m=''1719580''>And</span> <span m=''1719770''>therefore,</span>
  <span m=''1720140''>you</span> <span m=''1720310''>can</span> <span m=''1720820''>do</span>
  <span m=''1720990''>a</span> <span m=''1721040''>store</span> <span m=''1721580''>and</span>
  <span m=''1721730''>a</span> <span m=''1721800''>load</span> <span m=''1723570''>and</span>
  <span m=''1724010''>be</span> <span m=''1724210''>able</span> <span m=''1724400''>to</span>
  <span m=''1724510''>overlap</span> <span m=''1725190''>their</span> <span m=''1725630''>execution.</span>
  <span m=''1726500''>So</span> <span m=''1726680''>this</span> <span m=''1727000''>definitely</span>
  <span m=''1727560''>wins</span> <span m=''1728290''>for</span> <span m=''1729600''>serial</span>
  <span m=''1730000''>execution.</span> </p><p><span m=''1732290''>Yep,</span> <span
  m=''1732780''>good.</span> <span m=''1733230''>Any</span> <span m=''1733440''>other</span>
  <span m=''1733590''>questions</span> <span m=''1734030''>about</span> <span m=''1734290''>this</span>
  <span m=''1734440''>mechanism?</span> <span m=''1737620''>You</span> <span m=''1737750''>could</span>
  <span m=''1737890''>reason</span> <span m=''1738890''>about</span> <span m=''1739210''>it</span>
  <span m=''1739380''>on</span> <span m=''1739580''>the</span> <span m=''1739660''>quiz.</span>
  <span m=''1740030''>That</span> <span m=''1740190''>kind</span> <span m=''1740310''>of</span>
  <span m=''1740430''>thing,</span> <span m=''1740800''>right?</span> <span m=''1743250''>Yeah,</span>
  <span m=''1743630''>OK?</span> </p><p><span m=''1745990''>So</span> <span m=''1746260''>here''s</span>
  <span m=''1746740''>the</span> <span m=''1747030''>x86</span> <span m=''1747750''>memory</span>
  <span m=''1748210''>consistency</span> <span m=''1748720''>model.</span> <span m=''1750960''>For</span>
  <span m=''1751160''>many</span> <span m=''1751470''>years,</span> <span m=''1751780''>Intel</span>
  <span m=''1752180''>was</span> <span m=''1752350''>unwilling</span> <span m=''1752920''>to</span>
  <span m=''1753010''>say</span> <span m=''1753270''>what</span> <span m=''1753460''>their</span>
  <span m=''1753590''>memory</span> <span m=''1753880''>consistency</span> <span m=''1754460''>model</span>
  <span m=''1754800''>was</span> <span m=''1755170''>for</span> <span m=''1755280''>fear</span>
  <span m=''1755560''>that</span> <span m=''1755730''>people</span> <span m=''1756140''>would</span>
  <span m=''1756930''>then</span> <span m=''1757180''>rely</span> <span m=''1757600''>on</span>
  <span m=''1757780''>it.</span> <span m=''1758740''>And</span> <span m=''1758940''>then,</span>
  <span m=''1759090''>they</span> <span m=''1759320''>would</span> <span m=''1759420''>be</span>
  <span m=''1759550''>forced</span> <span m=''1760020''>into</span> <span m=''1760200''>it.</span>
  <span m=''1760310''>But</span> <span m=''1760460''>recently,</span> <span m=''1761430''>they''ve</span>
  <span m=''1761580''>started</span> <span m=''1761970''>being</span> <span m=''1762180''>more</span>
  <span m=''1762340''>explicit</span> <span m=''1762820''>about</span> <span m=''1763110''>it.</span>
  <span m=''1763190''>And</span> <span m=''1763360''>this</span> <span m=''1763530''>is</span>
  <span m=''1764570''>the</span> <span m=''1764630''>large</span> <span m=''1764930''>part</span>
  <span m=''1765120''>of</span> <span m=''1765200''>it.</span> <span m=''1765290''>I</span>
  <span m=''1765350''>haven''t</span> <span m=''1765900''>put</span> <span m=''1766070''>up</span>
  <span m=''1766300''>all</span> <span m=''1766600''>the</span> <span m=''1766670''>things</span>
  <span m=''1766980''>because</span> <span m=''1767190''>there are</span> <span m=''1767300''>a
  whole</span> <span m=''1767500''>bunch</span> <span m=''1767710''>of</span> <span
  m=''1767790''>instructions,</span> <span m=''1768810''>such</span> <span m=''1769140''>as</span>
  <span m=''1770930''>locking</span> <span m=''1771480''>instructions</span> <span
  m=''1772110''>and</span> <span m=''1772200''>so</span> <span m=''1772400''>forth,</span>
  <span m=''1773310''>for</span> <span m=''1773440''>which</span> <span m=''1773760''>for</span>
  <span m=''1773910''>some</span> <span m=''1774140''>of</span> <span m=''1774190''>them,</span>
  <span m=''1774340''>it''s</span> <span m=''1774500''>more</span> <span m=''1774720''>complicated.</span>
  <span m=''1775280''>But</span> <span m=''1775390''>this</span> <span m=''1775540''>is</span>
  <span m=''1775670''>the</span> <span m=''1775750''>basics.</span> </p><p><span m=''1776890''>So</span>
  <span m=''1777100''>loads</span> <span m=''1777550''>are</span> <span m=''1777640''>not</span>
  <span m=''1777910''>reordered</span> <span m=''1778370''>with</span> <span m=''1778490''>loads.</span>
  <span m=''1780190''>So</span> <span m=''1780380''>if</span> <span m=''1780450''>you</span>
  <span m=''1780620''>add</span> <span m=''1780790''>a</span> <span m=''1780840''>load</span>
  <span m=''1781080''>to</span> <span m=''1781190''>one</span> <span m=''1781380''>location,</span>
  <span m=''1781820''>a load</span> <span m=''1782010''>to</span> <span m=''1782140''>another</span>
  <span m=''1782390''>location,</span> <span m=''1783150''>they</span> <span m=''1783330''>always</span>
  <span m=''1783880''>execute</span> <span m=''1784360''>in</span> <span m=''1784450''>the</span>
  <span m=''1784500''>same</span> <span m=''1784820''>order.</span> <span m=''1785470''>Stores</span>
  <span m=''1785980''>are</span> <span m=''1786060''>not</span> <span m=''1786970''>reordered</span>
  <span m=''1787440''>with</span> <span m=''1787760''>stores.</span> <span m=''1788080''>If</span>
  <span m=''1788190''>you have</span> <span m=''1788300''>store</span> <span m=''1789230''>and</span>
  <span m=''1789390''>then</span> <span m=''1789490''>a</span> <span m=''1789550''>subsequent</span>
  <span m=''1790040''>store,</span> <span m=''1790920''>those</span> <span m=''1791180''>two</span>
  <span m=''1791310''>stores</span> <span m=''1791690''>always</span> <span m=''1792110''>go</span>
  <span m=''1792290''>in</span> <span m=''1792360''>that</span> <span m=''1792550''>order.</span>
  <span m=''1793980''>Stores</span> <span m=''1794680''>are</span> <span m=''1794860''>not</span>
  <span m=''1795210''>reordered</span> <span m=''1795820''>with</span> <span m=''1795990''>prior</span>
  <span m=''1796480''>loads.</span> <span m=''1798240''>So</span> <span m=''1798460''>if</span>
  <span m=''1798580''>you</span> <span m=''1798690''>do</span> <span m=''1798830''>a</span>
  <span m=''1798880''>store</span> <span m=''1801380''>after</span> <span m=''1801880''>a</span>
  <span m=''1801950''>load--</span> <span m=''1802780''>if you</span> <span m=''1802870''>do</span>
  <span m=''1802980''>a</span> <span m=''1803050''>load</span> <span m=''1803870''>and</span>
  <span m=''1804060''>then</span> <span m=''1804190''>a</span> <span m=''1804260''>store,</span>
  <span m=''1806830''>they''re</span> <span m=''1807050''>going</span> <span m=''1807160''>to</span>
  <span m=''1807200''>go</span> <span m=''1807450''>in</span> <span m=''1807530''>that</span>
  <span m=''1807720''>order.</span> </p><p><span m=''1809460''>However,</span> <span
  m=''1810530''>a</span> <span m=''1810660''>load--</span> <span m=''1811180''>and</span>
  <span m=''1811290''>this</span> <span m=''1811440''>is</span> <span m=''1811590''>what</span>
  <span m=''1811720''>we</span> <span m=''1811810''>just</span> <span m=''1812010''>talked</span>
  <span m=''1812260''>about--</span> <span m=''1812980''>may be</span> <span m=''1813470''>reordered</span>
  <span m=''1814010''>with</span> <span m=''1814100''>a</span> <span m=''1814190''>prior</span>
  <span m=''1814620''>store</span> <span m=''1815050''>to</span> <span m=''1815160''>a</span>
  <span m=''1815270''>different</span> <span m=''1815700''>location</span> <span m=''1816570''>but</span>
  <span m=''1816850''>not</span> <span m=''1817200''>with</span> <span m=''1817330''>a</span>
  <span m=''1817380''>prior</span> <span m=''1817760''>store</span> <span m=''1818160''>to</span>
  <span m=''1818270''>the</span> <span m=''1818350''>same</span> <span m=''1818690''>location.</span>
  <span m=''1821770''>So</span> <span m=''1821940''>that''s</span> <span m=''1822150''>exactly</span>
  <span m=''1822620''>what</span> <span m=''1822760''>we</span> <span m=''1822860''>just</span>
  <span m=''1823090''>talked</span> <span m=''1823340''>about</span> <span m=''1823590''>on</span>
  <span m=''1823650''>the</span> <span m=''1823720''>previous</span> <span m=''1824110''>slide.</span>
  <span m=''1825230''>Then,</span> <span m=''1825400''>loads</span> <span m=''1825660''>and</span>
  <span m=''1825830''>stores</span> <span m=''1826180''>are</span> <span m=''1826260''>not</span>
  <span m=''1826680''>reordered</span> <span m=''1827130''>with lock</span> <span
  m=''1827610''>instructions.</span> </p><p><span m=''1828720''>So a</span> <span
  m=''1828900''>certain</span> <span m=''1829220''>set</span> <span m=''1829430''>of</span>
  <span m=''1829520''>instructions</span> <span m=''1830110''>are</span> <span m=''1830200''>called</span>
  <span m=''1830490''>lock</span> <span m=''1830790''>instructions.</span> <span m=''1831640''>And</span>
  <span m=''1831810''>they</span> <span m=''1831960''>include</span> <span m=''1832500''>all</span>
  <span m=''1832780''>the</span> <span m=''1833030''>atomic</span> <span m=''1833530''>updates,</span>
  <span m=''1834020''>the</span> <span m=''1834100''>exchanges,</span> <span m=''1835140''>comparisons-and-swaps,</span>
  <span m=''1837610''>and</span> <span m=''1837750''>a</span> <span m=''1837780''>variety</span>
  <span m=''1838240''>of</span> <span m=''1838340''>other</span> <span m=''1838570''>atomic</span>
  <span m=''1839160''>operations</span> <span m=''1839910''>that</span> <span m=''1840050''>the</span>
  <span m=''1840140''>hardware</span> <span m=''1840500''>supports.</span> </p><p><span
  m=''1842680''>The</span> <span m=''1842800''>stores</span> <span m=''1843580''>to</span>
  <span m=''1843670''>the</span> <span m=''1843740''>same</span> <span m=''1844050''>location</span>
  <span m=''1844610''>always</span> <span m=''1844980''>respect</span> <span m=''1845400''>a</span>
  <span m=''1845470''>global</span> <span m=''1846330''>order.</span> <span m=''1847070''>Everybody</span>
  <span m=''1847590''>sees</span> <span m=''1848050''>the</span> <span m=''1848130''>store</span>
  <span m=''1849950''>to</span> <span m=''1850310''>a</span> <span m=''1850360''>location</span>
  <span m=''1850940''>in</span> <span m=''1851060''>exactly</span> <span m=''1851600''>the</span>
  <span m=''1851690''>same</span> <span m=''1852430''>order.</span> <span m=''1853970''>And</span>
  <span m=''1854140''>the</span> <span m=''1854210''>lock</span> <span m=''1854550''>instructions</span>
  <span m=''1855420''>respect</span> <span m=''1855890''>a</span> <span m=''1855990''>global</span>
  <span m=''1856380''>total</span> <span m=''1856700''>order.</span> <span m=''1857410''>So
  that</span> <span m=''1857760''>everybody</span> <span m=''1858300''>sees</span>
  <span m=''1858880''>that</span> <span m=''1859620''>this</span> <span m=''1860080''>thread,</span>
  <span m=''1861020''>or</span> <span m=''1861220''>processor,</span> <span m=''1862020''>got</span>
  <span m=''1862460''>a</span> <span m=''1862940''>lock</span> <span m=''1863300''>before</span>
  <span m=''1863700''>that</span> <span m=''1864020''>one.</span> <span m=''1864260''>You</span>
  <span m=''1864320''>don''t</span> <span m=''1864470''>have</span> <span m=''1864710''>two</span>
  <span m=''1866530''>different</span> <span m=''1866900''>processors</span> <span
  m=''1867500''>disagreeing</span> <span m=''1868040''>on</span> <span m=''1868160''>what</span>
  <span m=''1868330''>the</span> <span m=''1868490''>order</span> <span m=''1868780''>was</span>
  <span m=''1869110''>that</span> <span m=''1869260''>somebody</span> <span m=''1869620''>acquired</span>
  <span m=''1870040''>a</span> <span m=''1870090''>lock</span> <span m=''1870440''>or</span>
  <span m=''1870500''>whatever.</span> </p><p><span m=''1872200''>And</span> <span
  m=''1872780''>then,</span> <span m=''1873240''>memory</span> <span m=''1873610''>ordering</span>
  <span m=''1874740''>preserves</span> <span m=''1875340''>transitive</span> <span
  m=''1876190''>visibility,</span> <span m=''1877020''>which</span> <span m=''1877210''>is</span>
  <span m=''1877310''>sort</span> <span m=''1877510''>of</span> <span m=''1877600''>like</span>
  <span m=''1877850''>saying</span> <span m=''1878630''>it</span> <span m=''1878770''>obeys</span>
  <span m=''1879170''>causality.</span> <span m=''1879950''>In</span> <span m=''1880090''>other</span>
  <span m=''1880220''>words,</span> <span m=''1880830''>if</span> <span m=''1881330''>after</span>
  <span m=''1881810''>doing</span> <span m=''1882240''>a,</span> <span m=''1882770''>if
  you</span> <span m=''1882910''>had</span> <span m=''1883110''>some</span> <span
  m=''1883350''>effect,</span> <span m=''1887380''>and</span> <span m=''1887530''>then</span>
  <span m=''1887680''>you</span> <span m=''1887790''>did</span> <span m=''1888050''>b,</span>
  <span m=''1888590''>it</span> <span m=''1888760''>should</span> <span m=''1888990''>look</span>
  <span m=''1889340''>like</span> <span m=''1890020''>to</span> <span m=''1890190''>other</span>
  <span m=''1890490''>people</span> <span m=''1890830''>like</span> <span m=''1891100''>a
  and then</span> <span m=''1891630''>b</span> <span m=''1891840''>happened.</span>
  <span m=''1892680''>Like</span> <span m=''1892980''>there''s</span> <span m=''1893270''>a</span>
  <span m=''1893350''>causality</span> <span m=''1893970''>going</span> <span m=''1894250''>on.</span>
  <span m=''1896590''>But</span> <span m=''1896720''>that''s</span> <span m=''1896960''>not</span>
  <span m=''1897200''>sequential</span> <span m=''1897620''>consistency,</span> <span
  m=''1899590''>mainly</span> <span m=''1899980''>because</span> <span m=''1900320''>of</span>
  <span m=''1900380''>four</span> <span m=''1900720''>here.</span> </p><p><span m=''1903770''>So</span>
  <span m=''1903950''>what''s</span> <span m=''1904210''>the</span> <span m=''1904360''>impact</span>
  <span m=''1904850''>of</span> <span m=''1904950''>reordering?</span> <span m=''1906280''>So</span>
  <span m=''1906490''>here,</span> <span m=''1906770''>we</span> <span m=''1907120''>have</span>
  <span m=''1907830''>our</span> <span m=''1908290''>example</span> <span m=''1908770''>from</span>
  <span m=''1909000''>the</span> <span m=''1909090''>beginning</span> <span m=''1910100''>for</span>
  <span m=''1910170''>the</span> <span m=''1910240''>memory</span> <span m=''1910510''>bottle,</span>
  <span m=''1910970''>where</span> <span m=''1911230''>I''m</span> <span m=''1913980''>storing
  a</span> <span m=''1914120''>1</span> <span m=''1914470''>into</span> <span m=''1914620''>a</span>
  <span m=''1915010''>and</span> <span m=''1915150''>then</span> <span m=''1915260''>loading</span>
  <span m=''1915840''>whatever</span> <span m=''1916390''>is</span> <span m=''1916820''>in</span>
  <span m=''1917050''>b.</span> <span m=''1918960''>And</span> <span m=''1919190''>similarly,</span>
  <span m=''1919730''>over</span> <span m=''1920000''>here</span> <span m=''1920210''>the</span>
  <span m=''1920380''>opposite.</span> <span m=''1921890''>So</span> <span m=''1922090''>what</span>
  <span m=''1922290''>happens</span> <span m=''1925310''>if</span> <span m=''1925530''>I''m</span>
  <span m=''1925820''>allowed</span> <span m=''1926180''>to</span> <span m=''1926270''>do</span>
  <span m=''1926450''>reordering?</span> <span m=''1927040''>What</span> <span m=''1927420''>can</span>
  <span m=''1927540''>happen</span> <span m=''1927910''>to</span> <span m=''1928020''>these</span>
  <span m=''1928290''>two</span> <span m=''1928430''>instructions?</span> </p><p><span
  m=''1930960''>Yeah.</span> <span m=''1931180''>They</span> <span m=''1931360''>can</span>
  <span m=''1931510''>execute</span> <span m=''1931960''>in</span> <span m=''1932050''>the</span>
  <span m=''1932170''>opposite</span> <span m=''1932600''>order.</span> <span m=''1934060''>Similarly,</span>
  <span m=''1934480''>these</span> <span m=''1934730''>two</span> <span m=''1934860''>guys</span>
  <span m=''1935170''>can</span> <span m=''1935300''>execute</span> <span m=''1935770''>in</span>
  <span m=''1935840''>the</span> <span m=''1935970''>opposite</span> <span m=''1936350''>order.</span>
  <span m=''1937960''>So</span> <span m=''1938860''>they</span> <span m=''1939010''>can</span>
  <span m=''1939150''>actually</span> <span m=''1939500''>execute</span> <span m=''1941710''>in</span>
  <span m=''1941860''>this</span> <span m=''1942060''>order</span> <span m=''1945710''>where</span>
  <span m=''1945960''>we</span> <span m=''1946090''>do</span> <span m=''1947640''>the</span>
  <span m=''1948050''>load</span> <span m=''1948480''>and</span> <span m=''1948670''>then</span>
  <span m=''1949370''>the</span> <span m=''1950520''>stores.</span> <span m=''1950990''>So
  it</span> <span m=''1951090''>executes</span> <span m=''1951670''>as</span> <span
  m=''1951810''>if</span> <span m=''1951980''>this</span> <span m=''1952190''>were</span>
  <span m=''1952360''>the</span> <span m=''1952500''>order.</span> <span m=''1953450''>Did
  I do</span> <span m=''1953540''>this</span> <span m=''1953640''>right?</span> <span
  m=''1954540''>Executes</span> <span m=''1955090''>as</span> <span m=''1955270''>if</span>
  <span m=''1955440''>this</span> <span m=''1955680''>were</span> <span m=''1956510''>the</span>
  <span m=''1956620''>order.</span> <span m=''1956940''>So</span> <span m=''1957040''>I</span>
  <span m=''1957110''>could</span> <span m=''1957360''>do</span> <span m=''1957500''>1,</span>
  <span m=''1957800''>2,</span> <span m=''1957990''>3,</span> <span m=''1958250''>4.</span>
  </p><p><span m=''1958990''>So</span> <span m=''1959660''>if</span> <span m=''1959860''>then,</span>
  <span m=''1960150''>I</span> <span m=''1960280''>do</span> <span m=''1960530''>the</span>
  <span m=''1960710''>ordering</span> <span m=''1962080''>2,</span> <span m=''1962420''>4,</span>
  <span m=''1962840''>1,</span> <span m=''1963160''>3.</span> </p><p><span m=''1967250''>AUDIENCE:
  [INAUDIBLE]</span> </p><p><span m=''1969800''>PROFESSOR: I</span> <span m=''1969870''>got</span>
  <span m=''1970050''>the</span> <span m=''1970140''>screwed</span> <span m=''1970480''>up,</span>
  <span m=''1970630''>I</span> <span m=''1970780''>think.</span> <span m=''1970940''>Didn''t
  I?</span> </p><p><span m=''1971320''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''1972820''>PROFESSOR:
  Because</span> <span m=''1973110''>I</span> <span m=''1973190''>should</span> <span
  m=''1973460''>be</span> <span m=''1973610''>swapping</span> <span m=''1974140''>these</span>
  <span m=''1974370''>guys,</span> <span m=''1974680''>right?</span> </p><p><span
  m=''1975060''>AUDIENCE: Swapped the wrong</span> <span m=''1975440''>[INAUDIBLE].</span>
  </p><p><span m=''1975820''>PROFESSOR: Ugh.</span> <span m=''1977480''>OK.</span>
  <span m=''1980730''>So</span> <span m=''1980970''>if</span> <span m=''1981190''>I</span>
  <span m=''1981300''>did</span> <span m=''1981710''>this</span> <span m=''1981910''>one</span>
  <span m=''1982210''>2,</span> <span m=''1982880''>1,</span> <span m=''1983770''>4,</span>
  <span m=''1984450''>3.</span> <span m=''1988380''>So</span> <span m=''1988830''>ignore</span>
  <span m=''1989140''>this</span> <span m=''1989360''>thing.</span> <span m=''1989850''>Suppose</span>
  <span m=''1990220''>I</span> <span m=''1990280''>do</span> <span m=''1990410''>the</span>
  <span m=''1990520''>order</span> <span m=''1993460''>2.</span> <span m=''1994050''>So</span>
  <span m=''1994220''>basically,</span> <span m=''1994580''>I</span> <span m=''1994730''>load</span>
  <span m=''1995100''>b.</span> <span m=''1996330''>Then,</span> <span m=''1996510''>I</span>
  <span m=''1996620''>load</span> <span m=''1997000''>a.</span> <span m=''1997900''>Then,</span>
  <span m=''1998030''>I</span> <span m=''2002030''>store</span> <span m=''2002870''>a.</span>
  <span m=''2003230''>And</span> <span m=''2003400''>then,</span> <span m=''2003520''>I</span>
  <span m=''2003590''>store</span> <span m=''2004020''>b.</span> <span m=''2005320''>What''s</span>
  <span m=''2005490''>the</span> <span m=''2005660''>result</span> <span m=''2006150''>value</span>
  <span m=''2006810''>that</span> <span m=''2007240''>are</span> <span m=''2007400''>in</span>
  <span m=''2008940''>EAX</span> <span m=''2009150''>and</span> <span m=''2010160''>EBX?</span>
  <span m=''2011740''>You</span> <span m=''2011860''>get</span> <span m=''2012040''>00.</span>
  </p><p><span m=''2013570''>Remember</span> <span m=''2013830''>00</span> <span m=''2017000''>wasn''t</span>
  <span m=''2017370''>the</span> <span m=''2017460''>legal</span> <span m=''2018690''>value</span>
  <span m=''2019210''>from</span> <span m=''2019650''>sequential</span> <span m=''2020130''>consistency.</span>
  <span m=''2020870''>But</span> <span m=''2021010''>in</span> <span m=''2021090''>this</span>
  <span m=''2021330''>case,</span> <span m=''2023200''>the</span> <span m=''2023390''>Intel</span>
  <span m=''2023750''>architecture</span> <span m=''2024440''>and</span> <span m=''2024520''>many</span>
  <span m=''2024800''>other</span> <span m=''2025040''>architectures</span> <span
  m=''2025580''>out</span> <span m=''2025820''>there</span> <span m=''2026000''>will</span>
  <span m=''2026210''>give</span> <span m=''2026460''>you</span> <span m=''2026660''>the</span>
  <span m=''2026770''>wrong</span> <span m=''2027260''>value</span> <span m=''2030680''>for</span>
  <span m=''2030820''>the</span> <span m=''2030990''>execution</span> <span m=''2031510''>of</span>
  <span m=''2031570''>these</span> <span m=''2031780''>instructions.</span> <span
  m=''2033920''>Any</span> <span m=''2034100''>question</span> <span m=''2034440''>about</span>
  <span m=''2034700''>that?</span> <span m=''2036270''>So</span> <span m=''2036450''>it</span>
  <span m=''2036620''>doesn''t</span> <span m=''2037060''>preserve</span> <span m=''2040190''>sequential</span>
  <span m=''2040720''>consistency.</span> <span m=''2044370''>So</span> <span m=''2044510''>that''s</span>
  <span m=''2044780''>kind</span> <span m=''2044970''>of</span> <span m=''2045810''>scary</span>
  <span m=''2046330''>in</span> <span m=''2046450''>some</span> <span m=''2046660''>way</span>
  <span m=''2048020''>because</span> <span m=''2048250''>you</span> <span m=''2048320''>got</span>
  <span m=''2048409''>to</span> <span m=''2048510''>reason</span> <span m=''2048850''>about</span>
  <span m=''2049130''>this.</span> </p><p><span m=''2050280''>Let''s</span> <span
  m=''2050530''>see</span> <span m=''2050650''>what</span> <span m=''2050820''>happens</span>
  <span m=''2051290''>in</span> <span m=''2051400''>Peterson''s</span> <span m=''2052030''>algorithm</span>
  <span m=''2052489''>if</span> <span m=''2052590''>you</span> <span m=''2052679''>don''t</span>
  <span m=''2052870''>have</span> <span m=''2053000''>sequential</span> <span m=''2053480''>consistency.</span>
  <span m=''2055889''>So</span> <span m=''2056030''>here</span> <span m=''2056260''>we</span>
  <span m=''2056360''>go.</span> <span m=''2059139''>We</span> <span m=''2059320''>have</span>
  <span m=''2059489''>the</span> <span m=''2059670''>code</span> <span m=''2059969''>where</span>
  <span m=''2060139''>she</span> <span m=''2060389''>wants</span> <span m=''2060679''>is</span>
  <span m=''2060810''>true,</span> <span m=''2061179''>turn</span> <span m=''2061620''>is</span>
  <span m=''2061860''>his,</span> <span m=''2061940''>et cetera.</span> <span m=''2063130''>How</span>
  <span m=''2063480''>is</span> <span m=''2063650''>this</span> <span m=''2063940''>going</span>
  <span m=''2064210''>to</span> <span m=''2065170''>fail?</span> <span m=''2066150''>What</span>
  <span m=''2066340''>could</span> <span m=''2066460''>happen</span> <span m=''2066800''>here?</span>
  <span m=''2074100''>Where</span> <span m=''2074340''>will</span> <span m=''2074570''>the
  bug</span> <span m=''2074770''>arise?</span> <span m=''2075550''>What''s</span>
  <span m=''2075820''>going</span> <span m=''2075900''>to</span> <span m=''2075989''>happen?</span>
  <span m=''2076460''>What''s</span> <span m=''2076620''>the</span> <span m=''2076790''>reordering</span>
  <span m=''2077350''>that</span> <span m=''2077500''>might</span> <span m=''2077710''>happen?</span>
  </p><p><span m=''2079520''>AUDIENCE: On the</span> <span m=''2079889''>while</span>
  <span m=''2080344''>you</span> <span m=''2080799''>do</span> <span m=''2081254''>loads,</span>
  <span m=''2081709''>right?</span> <span m=''2082164''>[INAUDIBLE]</span> <span m=''2082619''>the
  he_wants and</span> <span m=''2083080''>turn</span> <span m=''2083385''>is.</span>
  </p><p><span m=''2083690''>PROFESSOR: Sorry?</span> </p><p><span m=''2084994''>AUDIENCE:
  On the while</span> <span m=''2085468''>statement,</span> <span m=''2086416''>you</span>
  <span m=''2086890''>do a load,</span> <span m=''2087364''>right?</span> <span m=''2088312''>Because</span>
  <span m=''2088786''>[INAUDIBLE].</span> </p><p><span m=''2089260''>PROFESSOR: Right.</span>
  <span m=''2089380''>He_wants</span> <span m=''2089929''>is a</span> <span m=''2090170''>load.</span>
  </p><p><span m=''2091810''>AUDIENCE: And so</span> <span m=''2092219''>that will</span>
  <span m=''2092659''>get reordered.</span> </p><p><span m=''2093420''>PROFESSOR:
  Where could</span> <span m=''2093679''>that</span> <span m=''2093949''>be reordered</span>
  <span m=''2094250''>to?</span> <span m=''2099250''>That</span> <span m=''2099380''>could</span>
  <span m=''2099510''>be</span> <span m=''2099630''>reordered</span> <span m=''2101150''>all</span>
  <span m=''2101370''>the</span> <span m=''2101430''>way</span> <span m=''2101580''>to</span>
  <span m=''2101740''>the</span> <span m=''2101880''>top.</span> <span m=''2103480''>Similarly,</span>
  <span m=''2105710''>this</span> <span m=''2105910''>one</span> <span m=''2106130''>can</span>
  <span m=''2106250''>be</span> <span m=''2106510''>reordered</span> <span m=''2106970''>all</span>
  <span m=''2107130''>the</span> <span m=''2107190''>way</span> <span m=''2107320''>to</span>
  <span m=''2107460''>the</span> <span m=''2107580''>top.</span> <span m=''2109830''>So</span>
  <span m=''2109950''>the</span> <span m=''2110030''>loads</span> <span m=''2111150''>could</span>
  <span m=''2111290''>be</span> <span m=''2111430''>ordered</span> <span m=''2111790''>all</span>
  <span m=''2112040''>the</span> <span m=''2112100''>way</span> <span m=''2112230''>to</span>
  <span m=''2112360''>the</span> <span m=''2112500''>top.</span> </p><p><span m=''2113530''>And</span>
  <span m=''2113710''>now,</span> <span m=''2113930''>what''s</span> <span m=''2114130''>going</span>
  <span m=''2114210''>to</span> <span m=''2114290''>happen</span> <span m=''2114700''>is</span>
  <span m=''2114980''>you''re</span> <span m=''2115120''>going</span> <span m=''2115230''>to</span>
  <span m=''2115340''>set</span> <span m=''2116550''>that</span> <span m=''2116690''>she_wants</span>
  <span m=''2117260''>is</span> <span m=''2117440''>true</span> <span m=''2118560''>but</span>
  <span m=''2118770''>get</span> <span m=''2118980''>a</span> <span m=''2119040''>value</span>
  <span m=''2119690''>of</span> <span m=''2119940''>he_wants</span> <span m=''2120630''>that</span>
  <span m=''2120800''>might</span> <span m=''2121120''>be</span> <span m=''2121420''>old.</span>
  <span m=''2123420''>And</span> <span m=''2123520''>so</span> <span m=''2123640''>they</span>
  <span m=''2123760''>won''t</span> <span m=''2124080''>see</span> <span m=''2124310''>each</span>
  <span m=''2124600''>other''s</span> <span m=''2125130''>values.</span> <span m=''2126110''>And</span>
  <span m=''2126260''>so</span> <span m=''2126400''>then,</span> <span m=''2126630''>both</span>
  <span m=''2127700''>threads</span> <span m=''2128200''>can</span> <span m=''2128370''>now</span>
  <span m=''2128660''>enter</span> <span m=''2129080''>the</span> <span m=''2129190''>critical</span>
  <span m=''2129570''>section</span> <span m=''2129970''>simultaneously.</span> <span
  m=''2133420''>Yeah,</span> <span m=''2133690''>Reid?</span> </p><p><span m=''2135666''>AUDIENCE:
  If you swap</span> <span m=''2136160''>the order</span> <span m=''2136654''>of the</span>
  <span m=''2137148''>loads,</span> <span m=''2139124''>does</span> <span m=''2139618''>the</span>
  <span m=''2140112''>[INAUDIBLE]?</span> </p><p><span m=''2143090''>PROFESSOR: If
  you swap</span> <span m=''2143450''>the order</span> <span m=''2143520''>of the
  loads--</span> </p><p><span m=''2145512''>AUDIENCE: If you</span> <span m=''2146010''>swap--</span>
  <span m=''2146508''>put the</span> <span m=''2147006''>turn equals his</span> <span
  m=''2147504''>on the</span> <span m=''2148002''>left,</span> <span m=''2148500''>[INAUDIBLE]</span>
  <span m=''2148998''>on</span> <span m=''2149496''>the right.</span> <span m=''2150492''>Because</span>
  <span m=''2150990''>according to--</span> </p><p><span m=''2152484''>PROFESSOR:
  Put the turn</span> <span m=''2152982''>equals</span> <span m=''2153480''>his</span>
  <span m=''2154850''>over here?</span> </p><p><span m=''2155485''>AUDIENCE: Because</span>
  <span m=''2155980''>the he_wants</span> <span m=''2156970''>can''t</span> <span
  m=''2157465''>cross the</span> <span m=''2157960''>load.</span> </p><p><span m=''2158460''>PROFESSOR:
  Yeah,</span> <span m=''2159010''>but</span> <span m=''2159140''>that''s</span> <span
  m=''2159370''>not</span> <span m=''2159550''>what</span> <span m=''2159700''>you</span>
  <span m=''2159790''>want</span> <span m=''2159940''>to</span> <span m=''2160000''>do.</span>
  </p><p><span m=''2161130''>AUDIENCE: Then you</span> <span m=''2161625''>can''t</span>
  <span m=''2162120''>[INAUDIBLE].</span> </p><p><span m=''2165590''>PROFESSOR: The</span>
  <span m=''2165680''>whole</span> <span m=''2165900''>idea</span> <span m=''2166240''>here</span>
  <span m=''2166580''>is</span> <span m=''2166730''>that</span> <span m=''2167270''>when</span>
  <span m=''2167620''>you''re</span> <span m=''2167940''>saying</span> <span m=''2168310''>you</span>
  <span m=''2168410''>want</span> <span m=''2168580''>to</span> <span m=''2168640''>do</span>
  <span m=''2168840''>something,</span> <span m=''2169220''>you</span> <span m=''2169300''>give</span>
  <span m=''2169750''>the</span> <span m=''2169980''>other</span> <span m=''2170840''>one</span>
  <span m=''2171020''>a</span> <span m=''2171120''>turn</span> <span m=''2171560''>so</span>
  <span m=''2171740''>that</span> <span m=''2172320''>whoever</span> <span m=''2172690''>ends</span>
  <span m=''2172870''>up</span> <span m=''2173020''>winning</span> <span m=''2173280''>the</span>
  <span m=''2173370''>race</span> <span m=''2175350''>allows</span> <span m=''2177930''>just</span>
  <span m=''2178160''>one of them</span> <span m=''2178560''>to</span> <span m=''2178610''>go</span>
  <span m=''2178780''>through.</span> <span m=''2179130''>Yeah?</span> </p><p><span
  m=''2180089''>AUDIENCE: I think the point</span> <span m=''2180558''>is that</span>
  <span m=''2181027''>if you put</span> <span m=''2181496''>turn</span> <span m=''2181965''>equals</span>
  <span m=''2182434''>his and</span> <span m=''2183841''>he_wants--</span> </p><p><span
  m=''2185720''>PROFESSOR: You''re</span> <span m=''2185880''>saying</span> <span
  m=''2186120''>this</span> <span m=''2186350''>stuff</span> <span m=''2186550''>here.</span>
  </p><p><span m=''2187266''>AUDIENCE: Swap</span> <span m=''2187752''>those</span>
  <span m=''2188238''>two</span> <span m=''2188724''>[UNINTELLIGIBLE]</span> <span
  m=''2189210''>turn equals</span> <span m=''2189696''>his</span> <span m=''2190182''>will
  not be</span> <span m=''2190668''>reordered before</span> <span m=''2191154''>the</span>
  <span m=''2191640''>store</span> <span m=''2192612''>that--</span> </p><p><span
  m=''2193770''>PROFESSOR: You</span> <span m=''2193900''>might</span> <span m=''2194120''>be</span>
  <span m=''2194260''>right.</span> <span m=''2194530''>Let</span> <span m=''2194600''>me</span>
  <span m=''2194700''>think</span> <span m=''2194880''>about</span> <span m=''2195130''>that.</span>
  </p><p><span m=''2195801''>AUDIENCE: You both</span> <span m=''2196282''>reorder</span>
  <span m=''2196763''>the same</span> <span m=''2197244''>[? word. ?]</span> </p><p><span
  m=''2197725''>AUDIENCE: But</span> <span m=''2198206''>you</span> <span m=''2198687''>just</span>
  <span m=''2199168''>stored</span> <span m=''2199649''>turn,</span> <span m=''2200130''>right?</span>
  </p><p><span m=''2200611''>PROFESSOR: Yeah.</span> <span m=''2201092''>So if</span>
  <span m=''2201573''>do turn</span> <span m=''2202054''>equals his--</span> <span
  m=''2202535''>I</span> <span m=''2203016''>see what you''re</span> <span m=''2203497''>saying.
  Do this</span> <span m=''2203978''>turn equals his.</span> <span m=''2204459''>I
  was looking at this turn equals</span> <span m=''2204940''>his.</span> </p><p><span
  m=''2205920''>AUDIENCE: You mean</span> <span m=''2206240''>turn</span> <span m=''2206710''>equals
  equals</span> <span m=''2207180''>his.</span> </p><p><span m=''2207650''>AUDIENCE:
  So the</span> <span m=''2208120''>Boolean expression</span> <span m=''2208590''>[INAUDIBLE].</span>
  </p><p><span m=''2209060''>PROFESSOR: Yeah.</span> <span m=''2209530''>OK,</span>
  <span m=''2210000''>I hadn''t thought</span> <span m=''2210470''>about that.</span>
  <span m=''2210940''>Let me</span> <span m=''2211410''>just think</span> <span m=''2211880''>about
  that a</span> <span m=''2212350''>second.</span> <span m=''2212840''>So if</span>
  <span m=''2213440''>we</span> <span m=''2213820''>do</span> <span m=''2214180''>the</span>
  <span m=''2214510''>turn</span> <span m=''2214780''>equals</span> <span m=''2215170''>his--</span>
  </p><p><span m=''2217175''>AUDIENCE: [INAUDIBLE]</span> <span m=''2218540''>and
  you won''t</span> <span m=''2218995''>reorder</span> <span m=''2219450''>those two</span>
  <span m=''2219905''>[INAUDIBLE]?</span> </p><p><span m=''2220360''>PROFESSOR: Then</span>
  <span m=''2220720''>the--</span> <span m=''2226600''>Yeah.</span> <span m=''2227000''>You</span>
  <span m=''2227090''>got</span> <span m=''2227340''>to</span> <span m=''2227400''>be--</span>
  <span m=''2231120''>I</span> <span m=''2231240''>have</span> <span m=''2231430''>to</span>
  <span m=''2231540''>think</span> <span m=''2231720''>about</span> <span m=''2232010''>that.</span>
  <span m=''2233760''>I don''t know</span> <span m=''2233870''>about</span> <span
  m=''2234070''>you</span> <span m=''2234190''>folks,</span> <span m=''2234510''>but
  I</span> <span m=''2234670''>find</span> <span m=''2234910''>this</span> <span m=''2235030''>stuff</span>
  <span m=''2235270''>really</span> <span m=''2235610''>hard</span> <span m=''2235820''>to</span>
  <span m=''2235880''>think</span> <span m=''2236090''>about.</span> <span m=''2238220''>And</span>
  <span m=''2238470''>so</span> <span m=''2238620''>do</span> <span m=''2238710''>most</span>
  <span m=''2238980''>people,</span> <span m=''2239270''>I</span> <span m=''2239330''>think.</span>
  <span m=''2242290''>This is</span> <span m=''2242690''>one</span> <span m=''2242810''>of</span>
  <span m=''2242850''>these</span> <span m=''2243020''>things</span> <span m=''2243280''>where</span>
  <span m=''2243680''>I</span> <span m=''2243810''>don''t</span> <span m=''2243990''>think</span>
  <span m=''2244150''>I</span> <span m=''2244200''>can</span> <span m=''2244330''>do</span>
  <span m=''2244450''>without</span> <span m=''2244760''>sitting</span> <span m=''2244950''>down</span>
  <span m=''2245210''>for</span> <span m=''2245330''>10</span> <span m=''2245520''>minutes</span>
  <span m=''2247580''>and</span> <span m=''2247800''>thinking</span> <span m=''2248100''>about</span>
  <span m=''2248270''>it</span> <span m=''2248440''>deeply.</span> <span m=''2250820''>But</span>
  <span m=''2250980''>it''s</span> <span m=''2251110''>an</span> <span m=''2251200''>interesting</span>
  <span m=''2251550''>thought</span> <span m=''2252410''>that if</span> <span m=''2252500''>you</span>
  <span m=''2252580''>did</span> <span m=''2252740''>it</span> <span m=''2252860''>the</span>
  <span m=''2252980''>other</span> <span m=''2253160''>direction</span> <span m=''2253880''>that</span>
  <span m=''2254190''>maybe</span> <span m=''2254530''>there</span> <span m=''2254700''>would</span>
  <span m=''2254960''>be</span> <span m=''2255220''>a</span> <span m=''2257900''>requirement</span>
  <span m=''2258520''>there.</span> </p><p><span m=''2259350''>I''m</span> <span m=''2259590''>skeptical</span>
  <span m=''2260270''>that</span> <span m=''2260370''>that</span> <span m=''2260650''>is</span>
  <span m=''2260830''>true</span> <span m=''2262600''>because</span> <span m=''2263180''>to</span>
  <span m=''2263280''>my</span> <span m=''2263440''>knowledge</span> <span m=''2263910''>to</span>
  <span m=''2264040''>do</span> <span m=''2264210''>the</span> <span m=''2264290''>mutual</span>
  <span m=''2264580''>exclusion,</span> <span m=''2265100''>you</span> <span m=''2265180''>pretty</span>
  <span m=''2265440''>much</span> <span m=''2266150''>have</span> <span m=''2266420''>to</span>
  <span m=''2266560''>do</span> <span m=''2267020''>what</span> <span m=''2267310''>I''m</span>
  <span m=''2267400''>going</span> <span m=''2267530''>to</span> <span m=''2267570''>talk</span>
  <span m=''2267790''>about</span> <span m=''2268000''>next.</span> <span m=''2271890''>But</span>
  <span m=''2272350''>it</span> <span m=''2272490''>would</span> <span m=''2272650''>be</span>
  <span m=''2272800''>interesting</span> <span m=''2273160''>if</span> <span m=''2273240''>is
  true.</span> <span m=''2277890''>Because</span> <span m=''2278140''>you</span> <span
  m=''2278230''>also</span> <span m=''2278500''>have</span> <span m=''2278690''>to</span>
  <span m=''2278800''>worry</span> <span m=''2279100''>about</span> <span m=''2279690''>this</span>
  <span m=''2280110''>guy</span> <span m=''2280330''>getting</span> <span m=''2280680''>reordered</span>
  <span m=''2281180''>with</span> <span m=''2281340''>respect</span> <span m=''2281690''>to</span>
  <span m=''2281770''>this</span> <span m=''2281980''>one.</span> </p><p><span m=''2283052''>AUDIENCE:
  The loads</span> <span m=''2283498''>can''t be</span> <span m=''2283944''>reordered
  with</span> <span m=''2284390''>respect to</span> <span m=''2284836''>each other.</span>
  </p><p><span m=''2285730''>PROFESSOR: So</span> <span m=''2285870''>he_wants</span>
  <span m=''2286470''>and</span> <span m=''2286630''>turn</span> <span m=''2286930''>equals</span>
  <span m=''2287410''>his.</span> <span m=''2288910''>Yeah.</span> <span m=''2290596''>So</span>
  <span m=''2290990''>the</span> <span m=''2291090''>loads</span> <span m=''2291380''>won''t</span>
  <span m=''2291590''>be</span> <span m=''2291730''>reordered.</span> <span m=''2292220''>Yeah.</span>
  <span m=''2294010''>So</span> <span m=''2294550''>that</span> <span m=''2294740''>looks</span>
  <span m=''2294940''>OK.</span> <span m=''2295630''>And</span> <span m=''2295690''>then,</span>
  <span m=''2295810''>you''re</span> <span m=''2295920''>saying</span> <span m=''2296240''>and
  then</span> <span m=''2296560''>therefore,</span> <span m=''2296970''>it</span>
  <span m=''2297050''>can''t</span> <span m=''2297310''>go</span> <span m=''2297460''>forward</span>
  <span m=''2297890''>because</span> <span m=''2298730''>this</span> <span m=''2298940''>one</span>
  <span m=''2299200''>won''t</span> <span m=''2299450''>get</span> <span m=''2299600''>reordered</span>
  <span m=''2299950''>with</span> <span m=''2300050''>that</span> <span m=''2300250''>one.</span>
  <span m=''2300450''>You might</span> <span m=''2300720''>be</span> <span m=''2300790''>right.</span>
  <span m=''2302450''>That''d</span> <span m=''2302700''>be cute.</span> <span m=''2306370''>So
  I have to</span> <span m=''2306700''>update</span> <span m=''2307060''>the</span>
  <span m=''2307140''>slides</span> <span m=''2307510''>for</span> <span m=''2307600''>next</span>
  <span m=''2307840''>year</span> <span m=''2308630''>if</span> <span m=''2308770''>that''s</span>
  <span m=''2309020''>true.</span> </p><p><span m=''2312670''>So</span> <span m=''2312890''>one</span>
  <span m=''2313160''>way</span> <span m=''2313430''>out</span> <span m=''2313630''>of</span>
  <span m=''2313740''>this</span> <span m=''2314880''>quandary</span> <span m=''2315580''>is</span>
  <span m=''2315840''>to</span> <span m=''2315940''>use</span> <span m=''2316270''>what''s</span>
  <span m=''2316530''>called</span> <span m=''2317010''>a</span> <span m=''2317210''>memory</span>
  <span m=''2317630''>fence</span> <span m=''2318070''>or</span> <span m=''2318290''>memory</span>
  <span m=''2318610''>barrier.</span> <span m=''2320070''>And</span> <span m=''2320270''>it''s</span>
  <span m=''2320450''>a</span> <span m=''2320550''>hardware</span> <span m=''2321120''>action</span>
  <span m=''2321650''>that</span> <span m=''2321830''>enforces</span> <span m=''2322340''>an</span>
  <span m=''2322450''>ordering</span> <span m=''2322950''>constraint</span> <span
  m=''2323670''>between</span> <span m=''2324110''>the</span> <span m=''2324480''>instructions</span>
  <span m=''2325040''>before</span> <span m=''2325620''>and</span> <span m=''2325770''>after</span>
  <span m=''2326170''>the</span> <span m=''2326290''>fence.</span> <span m=''2328770''>So</span>
  <span m=''2328910''>a</span> <span m=''2328960''>memory</span> <span m=''2329270''>fence</span>
  <span m=''2329570''>says</span> <span m=''2329950''>don''t</span> <span m=''2330750''>allow</span>
  <span m=''2331210''>the</span> <span m=''2331370''>processor</span> <span m=''2332020''>to</span>
  <span m=''2332130''>reorder</span> <span m=''2332600''>these</span> <span m=''2332880''>things.</span>
  <span m=''2334210''>So</span> <span m=''2334390''>why</span> <span m=''2334750''>would</span>
  <span m=''2335000''>you</span> <span m=''2335750''>not</span> <span m=''2336210''>want</span>
  <span m=''2336420''>to</span> <span m=''2336480''>do</span> <span m=''2336640''>a</span>
  <span m=''2336690''>memory</span> <span m=''2337010''>fence?</span> <span m=''2341680''>Then</span>
  <span m=''2341810''>we''ll</span> <span m=''2341910''>talk</span> <span m=''2342090''>about</span>
  <span m=''2342270''>why</span> <span m=''2342440''>you</span> <span m=''2342530''>do</span>
  <span m=''2342690''>it.</span> <span m=''2342810''>Yeah?</span> </p><p><span m=''2345213''>AUDIENCE:</span>
  <span m=''2345656''>To force</span> <span m=''2346099''>a hardware</span> <span
  m=''2346542''>slowdown?</span> </p><p><span m=''2347430''>PROFESSOR: Yeah.</span>
  <span m=''2347710''>You''re</span> <span m=''2348010''>forcing the hardware</span>
  <span m=''2348320''>slowdown.</span> <span m=''2348480''>You''re</span> <span m=''2348770''>also</span>
  <span m=''2348930''>forcing</span> <span m=''2349280''>compiler</span> <span m=''2350280''>because
  the</span> <span m=''2350380''>compiler</span> <span m=''2350810''>has</span> <span
  m=''2351010''>to</span> <span m=''2351100''>respect</span> <span m=''2351510''>that,</span>
  <span m=''2351750''>too.</span> <span m=''2352190''>You''re</span> <span m=''2352530''>not</span>
  <span m=''2352700''>letting</span> <span m=''2352930''>the</span> <span m=''2353010''>compiler</span>
  <span m=''2353510''>do</span> <span m=''2353680''>optimizations</span> <span m=''2354480''>across</span>
  <span m=''2354730''>the</span> <span m=''2354980''>fence.</span> <span m=''2356810''>So</span>
  <span m=''2356980''>generally,</span> <span m=''2359810''>fences</span> <span m=''2360310''>slow</span>
  <span m=''2360610''>things</span> <span m=''2360940''>down.</span> <span m=''2361800''>In</span>
  <span m=''2361940''>addition,</span> <span m=''2362330''>it</span> <span m=''2362450''>turns</span>
  <span m=''2362710''>out</span> <span m=''2362880''>that</span> <span m=''2363020''>they</span>
  <span m=''2363230''>have</span> <span m=''2363440''>some</span> <span m=''2363630''>significant</span>
  <span m=''2364090''>overhead.</span> </p><p><span m=''2366970''>So</span> <span
  m=''2367170''>you</span> <span m=''2367340''>can</span> <span m=''2367460''>issue</span>
  <span m=''2368130''>a</span> <span m=''2368650''>memory</span> <span m=''2368980''>fence</span>
  <span m=''2370340''>explicitly</span> <span m=''2371550''>as</span> <span m=''2371980''>an</span>
  <span m=''2372510''>instruction.</span> <span m=''2373230''>So</span> <span m=''2373420''>the</span>
  <span m=''2373590''>mfence</span> <span m=''2374190''>instruction</span> <span m=''2376610''>sets</span>
  <span m=''2376960''>a</span> <span m=''2377000''>memory</span> <span m=''2377320''>fence.</span>
  <span m=''2379180''>There''s</span> <span m=''2379360''>also,</span> <span m=''2379660''>it</span>
  <span m=''2379760''>turns</span> <span m=''2380020''>out,</span> <span m=''2380220''>on</span>
  <span m=''2380530''>x86</span> <span m=''2381020''>an</span> <span m=''2381430''>lfence</span>
  <span m=''2381850''>and</span> <span m=''2382050''>an</span> <span m=''2382240''>sfence,</span>
  <span m=''2383990''>which</span> <span m=''2384660''>allow</span> <span m=''2388480''>loads</span>
  <span m=''2389060''>to</span> <span m=''2389170''>go</span> <span m=''2389450''>over</span>
  <span m=''2389760''>but</span> <span m=''2389970''>not</span> <span m=''2390270''>stores</span>
  <span m=''2390780''>and</span> <span m=''2390940''>stores</span> <span m=''2391370''>but</span>
  <span m=''2391530''>not</span> <span m=''2391730''>loads.</span> <span m=''2392300''>And</span>
  <span m=''2392860''>this</span> <span m=''2393060''>one</span> <span m=''2393240''>is</span>
  <span m=''2393350''>basically</span> <span m=''2393900''>both.</span> <span m=''2394860''>From</span>
  <span m=''2395050''>the</span> <span m=''2395140''>point</span> <span m=''2395370''>of</span>
  <span m=''2395450''>view</span> <span m=''2395590''>of</span> <span m=''2395670''>what</span>
  <span m=''2395820''>we''re</span> <span m=''2396010''>using</span> <span m=''2396290''>it</span>
  <span m=''2396400''>for,</span> <span m=''2396660''>we''re</span> <span m=''2396930''>only</span>
  <span m=''2397090''>going</span> <span m=''2397230''>to</span> <span m=''2397720''>worry</span>
  <span m=''2397960''>about</span> <span m=''2398390''>the</span> <span m=''2399010''>fences.</span>
  </p><p><span m=''2400070''>They''re</span> <span m=''2400290''>done</span> <span
  m=''2400530''>by</span> <span m=''2400690''>the</span> <span m=''2400770''>explicit</span>
  <span m=''2401250''>one.</span> <span m=''2401490''>But</span> <span m=''2401630''>it</span>
  <span m=''2401670''>also</span> <span m=''2402010''>turns</span> <span m=''2402320''>out</span>
  <span m=''2402440''>all</span> <span m=''2402670''>the</span> <span m=''2402760''>locking</span>
  <span m=''2403240''>instructions</span> <span m=''2403840''>automatically</span>
  <span m=''2404560''>put</span> <span m=''2404710''>a</span> <span m=''2404760''>fence</span>
  <span m=''2405140''>in.</span> <span m=''2407530''>One</span> <span m=''2407710''>of</span>
  <span m=''2407790''>the</span> <span m=''2407880''>humorous</span> <span m=''2410170''>things</span>
  <span m=''2410540''>in</span> <span m=''2410700''>recent</span> <span m=''2411080''>memory</span>
  <span m=''2411980''>is</span> <span m=''2413770''>major</span> <span m=''2414170''>manufacturers</span>
  <span m=''2415230''>for</span> <span m=''2415410''>whom</span> <span m=''2417150''>the</span>
  <span m=''2417250''>lock</span> <span m=''2417660''>instruction</span> <span m=''2418420''>was</span>
  <span m=''2418590''>actually</span> <span m=''2418930''>faster</span> <span m=''2419570''>than</span>
  <span m=''2419750''>doing</span> <span m=''2420000''>a</span> <span m=''2420050''>memory</span>
  <span m=''2420370''>fence,</span> <span m=''2422110''>which is</span> <span m=''2422380''>kind</span>
  <span m=''2422580''>of</span> <span m=''2422680''>weird</span> <span m=''2423000''>because</span>
  <span m=''2423290''>a</span> <span m=''2423350''>lock</span> <span m=''2423580''>instruction</span>
  <span m=''2424290''>does</span> <span m=''2424580''>a</span> <span m=''2424650''>memory</span>
  <span m=''2425010''>fence.</span> </p><p><span m=''2427510''>So</span> <span m=''2427660''>how</span>
  <span m=''2427860''>do</span> <span m=''2427930''>you</span> <span m=''2428010''>think</span>
  <span m=''2428260''>that</span> <span m=''2428510''>sort</span> <span m=''2428680''>of</span>
  <span m=''2428760''>thing</span> <span m=''2428920''>comes</span> <span m=''2429180''>about?</span>
  <span m=''2429530''>So</span> <span m=''2429790''>when</span> <span m=''2429950''>you</span>
  <span m=''2430070''>looked</span> <span m=''2430170''>at</span> <span m=''2430370''>performance</span>
  <span m=''2431160''>it</span> <span m=''2431420''>would</span> <span m=''2431620''>be</span>
  <span m=''2431790''>like--</span> <span m=''2433160''>for</span> <span m=''2433240''>this</span>
  <span m=''2433430''>particular</span> <span m=''2433800''>machine</span> <span m=''2434100''>I''m</span>
  <span m=''2434210''>thinking</span> <span m=''2434440''>about--</span> <span m=''2435020''>it</span>
  <span m=''2435130''>was</span> <span m=''2435310''>30</span> <span m=''2435600''>cycles</span>
  <span m=''2436140''>to</span> <span m=''2436260''>do</span> <span m=''2436580''>a</span>
  <span m=''2440080''>lock</span> <span m=''2440600''>instruction.</span> <span m=''2441750''>And</span>
  <span m=''2441970''>it</span> <span m=''2442090''>was</span> <span m=''2443610''>on</span>
  <span m=''2443760''>the</span> <span m=''2443850''>order</span> <span m=''2444210''>of</span>
  <span m=''2444780''>50</span> <span m=''2445080''>cycles</span> <span m=''2445570''>to</span>
  <span m=''2445690''>do</span> <span m=''2445820''>a</span> <span m=''2445880''>memory</span>
  <span m=''2446160''>fence.</span> <span m=''2449610''>And</span> <span m=''2449820''>so</span>
  <span m=''2450170''>if</span> <span m=''2450260''>you</span> <span m=''2450360''>want</span>
  <span m=''2450490''>to</span> <span m=''2450530''>do</span> <span m=''2450630''>a</span>
  <span m=''2450680''>memory</span> <span m=''2450970''>fence,</span> <span m=''2451230''>what</span>
  <span m=''2451370''>should</span> <span m=''2451520''>you</span> <span m=''2451620''>do?</span>
  </p><p><span m=''2453725''>AUDIENCE: Do a</span> <span m=''2454000''>lock.</span>
  </p><p><span m=''2454260''>PROFESSOR: Do</span> <span m=''2454370''>a</span> <span
  m=''2454420''>lock</span> <span m=''2454650''>instruction</span> <span m=''2455490''>instead</span>
  <span m=''2456240''>to</span> <span m=''2456340''>get</span> <span m=''2456600''>the</span>
  <span m=''2457180''>effect.</span> <span m=''2457550''>But</span> <span m=''2457600''>why</span>
  <span m=''2457830''>do</span> <span m=''2457890''>you</span> <span m=''2457950''>suppose</span>
  <span m=''2458290''>that</span> <span m=''2458530''>came</span> <span m=''2458770''>up</span>
  <span m=''2458910''>in</span> <span m=''2458990''>the</span> <span m=''2459060''>hardware?</span>
  <span m=''2459460''>Why is</span> <span m=''2459870''>it</span> <span m=''2460030''>that</span>
  <span m=''2461390''>one</span> <span m=''2461640''>instruction</span> <span m=''2462280''>would</span>
  <span m=''2462540''>be--</span> <span m=''2468400''>It''s</span> <span m=''2468710''>a</span>
  <span m=''2468760''>social</span> <span m=''2469260''>reason</span> <span m=''2470520''>why</span>
  <span m=''2471310''>this sort</span> <span m=''2471540''>of</span> <span m=''2471620''>thing</span>
  <span m=''2471760''>happens.</span> <span m=''2474190''>So</span> <span m=''2474630''>I</span>
  <span m=''2474790''>don''t</span> <span m=''2474970''>know</span> <span m=''2475160''>for</span>
  <span m=''2475340''>sure.</span> <span m=''2476510''>But</span> <span m=''2477050''>I</span>
  <span m=''2477230''>know</span> <span m=''2477440''>enough</span> <span m=''2477640''>about</span>
  <span m=''2477900''>engineering</span> <span m=''2478470''>to</span> <span m=''2478560''>understand</span>
  <span m=''2479040''>how</span> <span m=''2479220''>these</span> <span m=''2479480''>things</span>
  <span m=''2479740''>come</span> <span m=''2479900''>about.</span> </p><p><span m=''2480760''>So</span>
  <span m=''2480880''>here''s</span> <span m=''2481130''>what</span> <span m=''2481300''>goes</span>
  <span m=''2481580''>on.</span> <span m=''2482240''>They</span> <span m=''2482440''>do</span>
  <span m=''2482650''>studies</span> <span m=''2483350''>of</span> <span m=''2483570''>traces</span>
  <span m=''2484210''>of</span> <span m=''2484320''>programs.</span> <span m=''2485680''>And</span>
  <span m=''2485880''>how</span> <span m=''2486250''>often</span> <span m=''2486840''>do</span>
  <span m=''2486910''>you</span> <span m=''2487000''>think</span> <span m=''2487290''>lock</span>
  <span m=''2487630''>instructions</span> <span m=''2488290''>occur?</span> <span
  m=''2488690''>And</span> <span m=''2488770''>how</span> <span m=''2489020''>often</span>
  <span m=''2489340''>do</span> <span m=''2489410''>you</span> <span m=''2489490''>think</span>
  <span m=''2489790''>fence</span> <span m=''2490140''>instructions</span> <span m=''2490760''>occur?</span>
  <span m=''2492200''>Turns</span> <span m=''2492470''>out</span> <span m=''2492640''>lock</span>
  <span m=''2492920''>instructions</span> <span m=''2493500''>occur</span> <span m=''2493830''>all</span>
  <span m=''2494170''>the</span> <span m=''2494270''>time,</span> <span m=''2495490''>whereas</span>
  <span m=''2495640''>fences,</span> <span m=''2497030''>they</span> <span m=''2497180''>don''t</span>
  <span m=''2497380''>occur</span> <span m=''2497710''>so</span> <span m=''2497950''>often</span>
  <span m=''2498290''>because</span> <span m=''2498490''>usually</span> <span m=''2498900''>it''s</span>
  <span m=''2499040''>somebody</span> <span m=''2499400''>who</span> <span m=''2499520''>really</span>
  <span m=''2499800''>knows</span> <span m=''2500090''>what</span> <span m=''2500250''>they''re</span>
  <span m=''2500390''>doing</span> <span m=''2500820''>who''s</span> <span m=''2500930''>using</span>
  <span m=''2501230''>a</span> <span m=''2501280''>memory</span> <span m=''2501570''>fence.</span>
  </p><p><span m=''2503120''>So</span> <span m=''2503380''>then,</span> <span m=''2503610''>they</span>
  <span m=''2503780''>say</span> <span m=''2504300''>to</span> <span m=''2504510''>the</span>
  <span m=''2504720''>engineering</span> <span m=''2505300''>team,</span> <span m=''2506310''>we''re</span>
  <span m=''2506490''>going</span> <span m=''2506590''>to</span> <span m=''2506640''>make</span>
  <span m=''2506900''>our</span> <span m=''2507110''>code</span> <span m=''2507380''>go</span>
  <span m=''2507530''>faster.</span> <span m=''2508170''>And</span> <span m=''2508420''>lock</span>
  <span m=''2508730''>instructions</span> <span m=''2509360''>are</span> <span m=''2509440''>going</span>
  <span m=''2509700''>really</span> <span m=''2509960''>fast.</span> <span m=''2510630''>So</span>
  <span m=''2510800''>they</span> <span m=''2510940''>put</span> <span m=''2511250''>a</span>
  <span m=''2511330''>top</span> <span m=''2511670''>engineer</span> <span m=''2512910''>on</span>
  <span m=''2513090''>making</span> <span m=''2513440''>lock</span> <span m=''2513740''>instructions</span>
  <span m=''2514410''>go</span> <span m=''2514540''>fast.</span> <span m=''2516350''>They</span>
  <span m=''2516520''>put</span> <span m=''2518006''>a</span> <span m=''2518420''>second-rate</span>
  <span m=''2519780''>engineer</span> <span m=''2521070''>on</span> <span m=''2521270''>making</span>
  <span m=''2524240''>memory</span> <span m=''2524530''>fence</span> <span m=''2524840''>operations</span>
  <span m=''2525450''>go</span> <span m=''2525560''>fast</span> <span m=''2525850''>because</span>
  <span m=''2526000''>they''re</span> <span m=''2526120''>not</span> <span m=''2526340''>used</span>
  <span m=''2526690''>as</span> <span m=''2526860''>often,</span> <span m=''2529270''>without</span>
  <span m=''2529670''>sort</span> <span m=''2529880''>of</span> <span m=''2530000''>recognizing</span>
  <span m=''2531040''>that,</span> <span m=''2531330''>gee,</span> <span m=''2531600''>what</span>
  <span m=''2531780''>you</span> <span m=''2531870''>do</span> <span m=''2532040''>for</span>
  <span m=''2532230''>one</span> <span m=''2533070''>is</span> <span m=''2533240''>the</span>
  <span m=''2533330''>same</span> <span m=''2533670''>problem.</span> <span m=''2534800''>You</span>
  <span m=''2534970''>can</span> <span m=''2535100''>do</span> <span m=''2535200''>the</span>
  <span m=''2535290''>same</span> <span m=''2535590''>thing</span> <span m=''2535810''>for</span>
  <span m=''2535930''>the</span> <span m=''2536060''>other.</span> </p><p><span m=''2537510''>So</span>
  <span m=''2537670''>it</span> <span m=''2537720''>ends</span> <span m=''2537930''>up</span>
  <span m=''2538330''>you''ll</span> <span m=''2538490''>see</span> <span m=''2538760''>things
  in</span> <span m=''2539040''>architecture</span> <span m=''2539690''>that are</span>
  <span m=''2539850''>really</span> <span m=''2540100''>quite</span> <span m=''2540370''>humorous</span>
  <span m=''2540820''>like</span> <span m=''2541040''>that,</span> <span m=''2541290''>where</span>
  <span m=''2541440''>things</span> <span m=''2541770''>are</span> <span m=''2541840''>sort</span>
  <span m=''2542000''>of</span> <span m=''2542070''>like,</span> <span m=''2542570''>wait</span>
  <span m=''2542760''>a</span> <span m=''2542810''>minute,</span> <span m=''2543000''>how</span>
  <span m=''2543180''>come</span> <span m=''2543330''>this</span> <span m=''2543490''>is</span>
  <span m=''2543600''>slower</span> <span m=''2545080''>when</span> <span m=''2545400''>well,</span>
  <span m=''2545600''>it</span> <span m=''2545750''>probably</span> <span m=''2546020''>has</span>
  <span m=''2546210''>to</span> <span m=''2546330''>do</span> <span m=''2546900''>with</span>
  <span m=''2547390''>the</span> <span m=''2547620''>engineering</span> <span m=''2548060''>team</span>
  <span m=''2548350''>that</span> <span m=''2548510''>built</span> <span m=''2548770''>the</span>
  <span m=''2548850''>system.</span> <span m=''2551500''>And</span> <span m=''2552140''>actually</span>
  <span m=''2552450''>now</span> <span m=''2552730''>I''m</span> <span m=''2552830''>aware</span>
  <span m=''2553090''>of</span> <span m=''2553220''>two</span> <span m=''2553470''>architectures</span>
  <span m=''2554120''>where</span> <span m=''2554230''>they</span> <span m=''2554390''>did</span>
  <span m=''2554570''>the</span> <span m=''2555310''>same</span> <span m=''2555600''>kind</span>
  <span m=''2555840''>of</span> <span m=''2555930''>thing</span> <span m=''2556670''>by</span>
  <span m=''2556850''>different</span> <span m=''2557180''>manufacturers.</span> <span
  m=''2558810''>Where</span> <span m=''2558960''>they</span> <span m=''2559090''>got</span>
  <span m=''2559480''>these</span> <span m=''2561110''>memory</span> <span m=''2561420''>fences.</span>
  <span m=''2561990''>It</span> <span m=''2562050''>should</span> <span m=''2562240''>be</span>
  <span m=''2562410''>at</span> <span m=''2562870''>least</span> <span m=''2563320''>as</span>
  <span m=''2563470''>fast</span> <span m=''2563910''>because</span> <span m=''2565350''>the</span>
  <span m=''2565490''>one</span> <span m=''2565700''>is</span> <span m=''2565850''>doing--</span>
  <span m=''2566390''>anyway.</span> <span m=''2568910''>Interesting</span> <span
  m=''2569450''>story</span> <span m=''2569780''>there.</span> </p><p><span m=''2571220''>Now,</span>
  <span m=''2571700''>you</span> <span m=''2571890''>can</span> <span m=''2572030''>actually</span>
  <span m=''2572390''>access</span> <span m=''2573220''>a</span> <span m=''2573710''>memory</span>
  <span m=''2574030''>fence</span> <span m=''2574440''>using</span> <span m=''2574800''>a</span>
  <span m=''2574850''>built</span> <span m=''2575180''>in</span> <span m=''2575580''>function</span>
  <span m=''2576900''>called</span> <span m=''2577250''>sync</span> <span m=''2577640''>synchronize.</span>
  <span m=''2579280''>And in</span> <span m=''2579450''>fact,</span> <span m=''2579680''>there</span>
  <span m=''2579770''>whole</span> <span m=''2579980''>set</span> <span m=''2580250''>of</span>
  <span m=''2580340''>atomics--</span> <span m=''2580890''>I''ve</span> <span m=''2580930''>put</span>
  <span m=''2581260''>the</span> <span m=''2581490''>information</span> <span m=''2582070''>here</span>
  <span m=''2582670''>for</span> <span m=''2582800''>where</span> <span m=''2583010''>you</span>
  <span m=''2583120''>can</span> <span m=''2583240''>go</span> <span m=''2583460''>and</span>
  <span m=''2583530''>look</span> <span m=''2583770''>at</span> <span m=''2583860''>the</span>
  <span m=''2583970''>atomic</span> <span m=''2584400''>operations</span> <span m=''2585570''>that</span>
  <span m=''2585700''>include</span> <span m=''2586370''>memory</span> <span m=''2586720''>fences</span>
  <span m=''2587180''>and</span> <span m=''2587280''>so</span> <span m=''2587480''>forth</span>
  <span m=''2587870''>to</span> <span m=''2587960''>using</span> <span m=''2588290''>in
  the</span> <span m=''2588380''>compiler.</span> <span m=''2589690''>It</span> <span
  m=''2589890''>turns</span> <span m=''2590130''>out</span> <span m=''2590920''>when</span>
  <span m=''2591190''>I</span> <span m=''2591280''>was</span> <span m=''2591400''>trying</span>
  <span m=''2591490''>to</span> <span m=''2591590''>get</span> <span m=''2591840''>this</span>
  <span m=''2592090''>going</span> <span m=''2592370''>last</span> <span m=''2592680''>night,</span>
  <span m=''2593610''>I</span> <span m=''2593910''>couldn''t</span> <span m=''2594240''>get</span>
  <span m=''2594360''>it</span> <span m=''2594480''>to</span> <span m=''2594570''>work.</span>
  </p><p><span m=''2595100''>And</span> <span m=''2595320''>it turns</span> <span
  m=''2595540''>out</span> <span m=''2595690''>that''s</span> <span m=''2595920''>because</span>
  <span m=''2596240''>our</span> <span m=''2596360''>compiler</span> <span m=''2596830''>had</span>
  <span m=''2596910''>a</span> <span m=''2597000''>bug</span> <span m=''2598590''>where</span>
  <span m=''2600050''>this</span> <span m=''2600260''>instruction</span> <span m=''2600900''>was</span>
  <span m=''2601070''>compiling</span> <span m=''2601590''>to</span> <span m=''2602480''>nothing.</span>
  <span m=''2605320''>There''s</span> <span m=''2605520''>a</span> <span m=''2605570''>compiler</span>
  <span m=''2606020''>bug.</span> <span m=''2607250''>And</span> <span m=''2607620''>so</span>
  <span m=''2607810''>I</span> <span m=''2610120''>messed</span> <span m=''2610460''>around</span>
  <span m=''2610810''>for</span> <span m=''2611860''>far</span> <span m=''2612160''>too</span>
  <span m=''2612290''>much</span> <span m=''2612520''>time</span> <span m=''2612930''>and</span>
  <span m=''2613110''>then finally</span> <span m=''2613460''>sent</span> <span m=''2613720''>out</span>
  <span m=''2613850''>a</span> <span m=''2613870''>help</span> <span m=''2614120''>message</span>
  <span m=''2614520''>to the</span> <span m=''2614670''>T.A.s.</span> <span m=''2615740''>And</span>
  <span m=''2615880''>then,</span> <span m=''2616040''>John</span> <span m=''2616350''>figured</span>
  <span m=''2616670''>out</span> <span m=''2616880''>that</span> <span m=''2617020''>there</span>
  <span m=''2617140''>was</span> <span m=''2617300''>a</span> <span m=''2617350''>bug.</span>
  <span m=''2617750''>And</span> <span m=''2617870''>he''s</span> <span m=''2618030''>patched</span>
  <span m=''2618390''>all</span> <span m=''2618490''>the</span> <span m=''2618590''>compilers</span>
  <span m=''2619120''>so</span> <span m=''2619260''>that</span> <span m=''2619370''>you</span>
  <span m=''2619520''>guys</span> <span m=''2619820''>all</span> <span m=''2619980''>have</span>
  <span m=''2620300''>it.</span> <span m=''2622800''>But</span> <span m=''2622940''>anyway,</span>
  <span m=''2623270''>it</span> <span m=''2623330''>was</span> <span m=''2623450''>like,</span>
  <span m=''2623900''>how</span> <span m=''2624150''>come</span> <span m=''2624410''>this</span>
  <span m=''2624640''>isn''t</span> <span m=''2624930''>working?</span> </p><p><span
  m=''2626590''>AUDIENCE: What</span> <span m=''2626860''>compiler</span> <span m=''2627130''>are
  we using?</span> </p><p><span m=''2627950''>PROFESSOR: This</span> <span m=''2628120''>was</span>
  <span m=''2628310''>GCC.</span> <span m=''2629550''>I</span> <span m=''2629680''>was</span>
  <span m=''2630430''>trying</span> <span m=''2630790''>4</span> <span m=''2631100''>1,</span>
  <span m=''2631750''>and I</span> <span m=''2631940''>tried</span> <span m=''2632120''>4</span>
  <span m=''2632400''>3.</span> <span m=''2634120''>And</span> <span m=''2635050''>so</span>
  <span m=''2635590''>the</span> <span m=''2635710''>one</span> <span m=''2635900''>that</span>
  <span m=''2636030''>we''re</span> <span m=''2636230''>using</span> <span m=''2636510''>in</span>
  <span m=''2636600''>class</span> <span m=''2636940''>for</span> <span m=''2637020''>the</span>
  <span m=''2637150''>most</span> <span m=''2637290''>part,</span> <span m=''2637450''>is</span>
  <span m=''2637560''>4</span> <span m=''2637770''>3.</span> <span m=''2639010''>So</span>
  <span m=''2639420''>anyway,</span> <span m=''2639860''>John</span> <span m=''2640100''>put</span>
  <span m=''2640190''>the</span> <span m=''2640300''>patch</span> <span m=''2640650''>in.</span>
  <span m=''2640830''>So</span> <span m=''2641730''>now,</span> <span m=''2642230''>when</span>
  <span m=''2642400''>you</span> <span m=''2642510''>use</span> <span m=''2643060''>these</span>
  <span m=''2643370''>instructions,</span> <span m=''2644310''>they''re</span> <span
  m=''2644720''>all</span> <span m=''2644830''>there.</span> </p><p><span m=''2649100''>And</span>
  <span m=''2649250''>then,</span> <span m=''2649380''>the</span> <span m=''2649450''>last</span>
  <span m=''2649810''>thing</span> <span m=''2650070''>is</span> <span m=''2650340''>that</span>
  <span m=''2650500''>the</span> <span m=''2650660''>typical</span> <span m=''2651080''>cost</span>
  <span m=''2651410''>of a</span> <span m=''2651580''>memory</span> <span m=''2651910''>fence</span>
  <span m=''2652440''>operation</span> <span m=''2652890''>is</span> <span m=''2653010''>comparable</span>
  <span m=''2653530''>to</span> <span m=''2653630''>that</span> <span m=''2653860''>of</span>
  <span m=''2653930''>an</span> <span m=''2654040''>L2</span> <span m=''2655610''>cache</span>
  <span m=''2655970''>access.</span> <span m=''2658870''>So</span> <span m=''2659040''>memory</span>
  <span m=''2659350''>fences</span> <span m=''2659780''>tend</span> <span m=''2660070''>to</span>
  <span m=''2660150''>be</span> <span m=''2663180''>on</span> <span m=''2663400''>our</span>
  <span m=''2663570''>machine--</span> <span m=''2664400''>and</span> <span m=''2664630''>I</span>
  <span m=''2664650''>haven''t</span> <span m=''2664880''>actually</span> <span m=''2665120''>measured</span>
  <span m=''2665590''>in our</span> <span m=''2665730''>machine.</span> <span m=''2666030''>I</span>
  <span m=''2666120''>meant</span> <span m=''2666370''>to</span> <span m=''2666460''>do</span>
  <span m=''2666590''>that,</span> <span m=''2666800''>and</span> <span m=''2666910''>I</span>
  <span m=''2667270''>didn''t</span> <span m=''2667470''>get</span> <span m=''2667590''>around</span>
  <span m=''2667920''>to</span> <span m=''2668030''>it.</span> <span m=''2668430''>It''s</span>
  <span m=''2668610''>probably</span> <span m=''2668950''>on</span> <span m=''2669250''>the</span>
  <span m=''2669380''>order</span> <span m=''2669690''>of</span> <span m=''2669790''>10,</span>
  <span m=''2670760''>or</span> <span m=''2670960''>15</span> <span m=''2671360''>cycles,</span>
  <span m=''2671780''>or</span> <span m=''2671850''>something,</span> <span m=''2672350''>which</span>
  <span m=''2672650''>is</span> <span m=''2672780''>not</span> <span m=''2672980''>bad.</span>
  <span m=''2675680''>If</span> <span m=''2675800''>it''s</span> <span m=''2675940''>less</span>
  <span m=''2676170''>than</span> <span m=''2676300''>20,</span> <span m=''2677070''>it''s</span>
  <span m=''2677310''>pretty</span> <span m=''2677500''>good.</span> </p><p><span
  m=''2682130''>So</span> <span m=''2682340''>here''s</span> <span m=''2682640''>Peterson''s</span>
  <span m=''2683210''>algorithm</span> <span m=''2683670''>with</span> <span m=''2683840''>memory</span>
  <span m=''2684140''>fences.</span> <span m=''2684550''>You</span> <span m=''2684660''>just</span>
  <span m=''2684820''>simply</span> <span m=''2685140''>sticky</span> <span m=''2685530''>in</span>
  <span m=''2686810''>the</span> <span m=''2687420''>memory</span> <span m=''2687770''>fence</span>
  <span m=''2688100''>there</span> <span m=''2688310''>to</span> <span m=''2688450''>prevent</span>
  <span m=''2688820''>the</span> <span m=''2688900''>reordering.</span> <span m=''2689460''>And
  it''s</span> <span m=''2689640''>interesting</span> <span m=''2690100''>if</span>
  <span m=''2690200''>there''s</span> <span m=''2690370''>a</span> <span m=''2690420''>way</span>
  <span m=''2690600''>that</span> <span m=''2690700''>we</span> <span m=''2690810''>can</span>
  <span m=''2691530''>play</span> <span m=''2691730''>the</span> <span m=''2691820''>game</span>
  <span m=''2692090''>with</span> <span m=''2692180''>the</span> <span m=''2692290''>instruction</span>
  <span m=''2692780''>stream</span> <span m=''2693090''>to</span> <span m=''2693190''>do</span>
  <span m=''2693290''>the</span> <span m=''2693400''>same</span> <span m=''2693670''>thing</span>
  <span m=''2694230''>because</span> <span m=''2694400''>that</span> <span m=''2694580''>would</span>
  <span m=''2694740''>make</span> <span m=''2694970''>this</span> <span m=''2695380''>code</span>
  <span m=''2695790''>go,</span> <span m=''2696400''>generally,</span> <span m=''2696780''>a</span>
  <span m=''2696840''>lot</span> <span m=''2697350''>faster</span> <span m=''2699640''>in</span>
  <span m=''2699940''>terms</span> <span m=''2700240''>of</span> <span m=''2700360''>overhead.</span>
  <span m=''2702230''>And</span> <span m=''2702430''>so</span> <span m=''2702570''>using</span>
  <span m=''2702980''>memory</span> <span m=''2703280''>fences,</span> <span m=''2703680''>you</span>
  <span m=''2703800''>can</span> <span m=''2703930''>restore</span> <span m=''2704380''>consistency.</span>
  </p><p><span m=''2706380''>Now,</span> <span m=''2706930''>memory</span> <span m=''2707140''>fences</span>
  <span m=''2707560''>are</span> <span m=''2707630''>like</span> <span m=''2707860''>data</span>
  <span m=''2708130''>races.</span> <span m=''2708530''>If</span> <span m=''2708630''>you</span>
  <span m=''2708740''>don''t</span> <span m=''2709100''>have</span> <span m=''2709420''>them,</span>
  <span m=''2709770''>how</span> <span m=''2709960''>do</span> <span m=''2710030''>you</span>
  <span m=''2710130''>know</span> <span m=''2710350''>that</span> <span m=''2710480''>you</span>
  <span m=''2710560''>don''t</span> <span m=''2710770''>have</span> <span m=''2711200''>them.</span>
  <span m=''2711400''>It''s very</span> <span m=''2711880''>difficult</span> <span
  m=''2712370''>to</span> <span m=''2712480''>regression</span> <span m=''2712960''>test</span>
  <span m=''2713260''>for them,</span> <span m=''2713950''>which</span> <span m=''2714130''>is</span>
  <span m=''2714210''>one</span> <span m=''2714420''>reason</span> <span m=''2714690''>I</span>
  <span m=''2714760''>think</span> <span m=''2714970''>there</span> <span m=''2715060''>was</span>
  <span m=''2715200''>a</span> <span m=''2715250''>bug</span> <span m=''2715520''>in</span>
  <span m=''2715580''>the</span> <span m=''2715670''>GCC</span> <span m=''2716230''>compiler.</span>
  <span m=''2717400''>How</span> <span m=''2717610''>do</span> <span m=''2717680''>you</span>
  <span m=''2717810''>know</span> <span m=''2718980''>that</span> <span m=''2720700''>some</span>
  <span m=''2720920''>piece</span> <span m=''2721120''>of</span> <span m=''2721190''>code</span>
  <span m=''2721500''>is</span> <span m=''2721690''>failing</span> <span m=''2722200''>because</span>
  <span m=''2722790''>most</span> <span m=''2723070''>of</span> <span m=''2723360''>the</span>
  <span m=''2723470''>time</span> <span m=''2723800''>it will</span> <span m=''2723930''>work</span>
  <span m=''2724240''>correctly.</span> <span m=''2725170''>It''s</span> <span m=''2725570''>just</span>
  <span m=''2725880''>occasionally,</span> <span m=''2726410''>they''ll</span> <span
  m=''2726540''>be</span> <span m=''2726650''>some</span> <span m=''2726880''>reordering,</span>
  <span m=''2728640''>and</span> <span m=''2728840''>timing,</span> <span m=''2729330''>and</span>
  <span m=''2729420''>race</span> <span m=''2729700''>condition</span> <span m=''2730090''>that</span>
  <span m=''2730210''>causes</span> <span m=''2730680''>it</span> <span m=''2730820''>not</span>
  <span m=''2731100''>to</span> <span m=''2731190''>work</span> <span m=''2731440''>out.</span>
  <span m=''2732190''>In</span> <span m=''2732470''>this</span> <span m=''2732630''>case,</span>
  <span m=''2732870''>you</span> <span m=''2732960''>both</span> <span m=''2733350''>have</span>
  <span m=''2733570''>to</span> <span m=''2733670''>have</span> <span m=''2733870''>the</span>
  <span m=''2733970''>race</span> <span m=''2735060''>and</span> <span m=''2736160''>the</span>
  <span m=''2736270''>reordering</span> <span m=''2736860''>happening</span> <span
  m=''2737330''>at</span> <span m=''2737410''>the</span> <span m=''2737470''>same</span>
  <span m=''2737750''>time</span> <span m=''2738800''>for</span> <span m=''2738980''>Peterson''s</span>
  <span m=''2739520''>algorithm,</span> <span m=''2739880''>for</span> <span m=''2740010''>example.</span>
  </p><p><span m=''2741230''>So</span> <span m=''2741980''>compilers</span> <span
  m=''2742490''>can</span> <span m=''2742600''>be</span> <span m=''2742710''>very</span>
  <span m=''2743570''>difficult</span> <span m=''2744090''>for</span> <span m=''2744180''>things</span>
  <span m=''2744460''>like</span> <span m=''2744700''>this.</span> <span m=''2745770''>Really,</span>
  <span m=''2746040''>the</span> <span m=''2746130''>way</span> <span m=''2746260''>to</span>
  <span m=''2746400''>do</span> <span m=''2746610''>it,</span> <span m=''2747090''>which</span>
  <span m=''2747270''>is</span> <span m=''2747380''>what</span> <span m=''2747530''>I</span>
  <span m=''2747650''>was</span> <span m=''2747840''>doing,</span> <span m=''2748110''>was</span>
  <span m=''2748920''>do</span> <span m=''2749240''>an</span> <span m=''2749470''>objdump</span>
  <span m=''2750210''>and</span> <span m=''2752400''>search</span> <span m=''2752820''>for</span>
  <span m=''2753480''>is</span> <span m=''2753560''>fence</span> <span m=''2753950''>in</span>
  <span m=''2754070''>there.</span> <span m=''2754590''>And</span> <span m=''2756730''>in</span>
  <span m=''2756980''>this</span> <span m=''2757150''>case,</span> <span m=''2757360''>it</span>
  <span m=''2757430''>wasn''t</span> <span m=''2757710''>in</span> <span m=''2757810''>there.</span>
  </p><p><span m=''2759376''>AUDIENCE: And also</span> <span m=''2759828''>compiler''s</span>
  <span m=''2760280''>self-analyzers,</span> <span m=''2761184''>by</span> <span m=''2761640''>itself.</span>
  <span m=''2762610''>And that''s</span> <span m=''2763100''>this instruction</span>
  <span m=''2763590''>that</span> <span m=''2764048''>basically</span> <span m=''2764506''>can</span>
  <span m=''2764964''>take</span> <span m=''2765422''>code.</span> </p><p><span m=''2766340''>PROFESSOR:
  Right.</span> <span m=''2767130''>It''s</span> <span m=''2767220''>not</span> <span
  m=''2767370''>doing</span> <span m=''2767580''>anything.</span> <span m=''2767960''>Right.</span>
  <span m=''2768780''>So</span> <span m=''2768880''>it</span> <span m=''2768920''>says,</span>
  <span m=''2769310''>oop,</span> <span m=''2769550''>get</span> <span m=''2769700''>out</span>
  <span m=''2769860''>of</span> <span m=''2770210''>it.</span> <span m=''2770570''>Yep.</span>
  <span m=''2771400''>Good.</span> </p><p><span m=''2775220''>So</span> <span m=''2775530''>any</span>
  <span m=''2775740''>questions</span> <span m=''2776260''>about</span> <span m=''2776850''>consistency.</span>
  <span m=''2777550''>So</span> <span m=''2777710''>what</span> <span m=''2777950''>turns</span>
  <span m=''2778210''>out</span> <span m=''2778420''>to</span> <span m=''2778510''>be</span>
  <span m=''2779450''>most</span> <span m=''2779850''>of</span> <span m=''2779910''>the</span>
  <span m=''2779980''>time</span> <span m=''2780270''>when</span> <span m=''2780390''>you''re</span>
  <span m=''2780490''>designing</span> <span m=''2781070''>things</span> <span m=''2782020''>where</span>
  <span m=''2782210''>you</span> <span m=''2782330''>want</span> <span m=''2782470''>to</span>
  <span m=''2782510''>synchronize</span> <span m=''2783130''>through</span> <span
  m=''2783320''>memory</span> <span m=''2783690''>directly,</span> <span m=''2784380''>rather</span>
  <span m=''2784720''>than</span> <span m=''2784890''>using</span> <span m=''2787110''>locks</span>
  <span m=''2787630''>or</span> <span m=''2787690''>what</span> <span m=''2787830''>have</span>
  <span m=''2788140''>you.</span> <span m=''2790610''>The</span> <span m=''2790810''>methodology</span>
  <span m=''2791450''>that</span> <span m=''2791570''>I</span> <span m=''2791700''>found</span>
  <span m=''2791950''>works</span> <span m=''2792190''>pretty</span> <span m=''2792440''>well.</span>
  <span m=''2792870''>Work</span> <span m=''2793130''>it</span> <span m=''2793220''>out</span>
  <span m=''2793430''>for</span> <span m=''2793540''>sequential</span> <span m=''2794090''>consistency,</span>
  <span m=''2795400''>and</span> <span m=''2795500''>then</span> <span m=''2795650''>figure</span>
  <span m=''2796010''>out</span> <span m=''2796220''>where</span> <span m=''2796360''>you</span>
  <span m=''2796460''>have</span> <span m=''2796700''>to</span> <span m=''2796800''>put</span>
  <span m=''2797000''>the</span> <span m=''2797080''>fences</span> <span m=''2797580''>in.</span>
  </p><p><span m=''2799150''>And</span> <span m=''2799340''>that''s</span> <span m=''2799590''>a</span>
  <span m=''2799660''>pretty</span> <span m=''2799940''>good</span> <span m=''2800110''>methodology</span>
  <span m=''2802530''>for</span> <span m=''2802770''>working</span> <span m=''2803150''>out</span>
  <span m=''2803340''>where--</span> <span m=''2804190''>here''s</span> <span m=''2804510''>sequential</span>
  <span m=''2804940''>consistency.</span> <span m=''2805550''>Now,</span> <span m=''2805830''>what</span>
  <span m=''2806040''>reorderings</span> <span m=''2806670''>do</span> <span m=''2806790''>I</span>
  <span m=''2806890''>need</span> <span m=''2807590''>to</span> <span m=''2807760''>ensure</span>
  <span m=''2808300''>in</span> <span m=''2808440''>order</span> <span m=''2808680''>to</span>
  <span m=''2808750''>make</span> <span m=''2808950''>sure</span> <span m=''2809120''>that</span>
  <span m=''2809230''>it</span> <span m=''2809350''>works</span> <span m=''2809610''>properly.</span>
  <span m=''2811250''>And</span> <span m=''2811420''>that</span> <span m=''2811620''>can</span>
  <span m=''2811740''>be</span> <span m=''2811950''>error</span> <span m=''2812200''>prone.</span>
  <span m=''2813450''>So</span> <span m=''2813660''>once</span> <span m=''2813880''>again,</span>
  <span m=''2814150''>big</span> <span m=''2814390''>skull</span> <span m=''2814690''>and</span>
  <span m=''2814790''>cross</span> <span m=''2815140''>bones</span> <span m=''2815490''>on</span>
  <span m=''2816530''>whether</span> <span m=''2816780''>you</span> <span m=''2816910''>actually</span>
  <span m=''2817220''>try</span> <span m=''2817550''>this</span> <span m=''2817750''>in</span>
  <span m=''2817860''>practice.</span> <span m=''2818830''>It</span> <span m=''2818970''>really</span>
  <span m=''2819310''>better</span> <span m=''2819520''>make</span> <span m=''2819730''>a</span>
  <span m=''2819780''>difference.</span> </p><p><span m=''2824100''>Now,</span> <span
  m=''2825610''>the</span> <span m=''2825740''>fact</span> <span m=''2825970''>that</span>
  <span m=''2826210''>you</span> <span m=''2826320''>can</span> <span m=''2826430''>synchronize</span>
  <span m=''2826990''>directly</span> <span m=''2827510''>through</span> <span m=''2827730''>memory</span>
  <span m=''2828180''>has</span> <span m=''2828420''>led</span> <span m=''2828830''>to</span>
  <span m=''2828980''>a</span> <span m=''2829140''>lot</span> <span m=''2829680''>of</span>
  <span m=''2829970''>protocols</span> <span m=''2832050''>that</span> <span m=''2832280''>are</span>
  <span m=''2832360''>called</span> <span m=''2832600''>lock-free</span> <span m=''2833120''>protocols,</span>
  <span m=''2835320''>which</span> <span m=''2836730''>have</span> <span m=''2837060''>some</span>
  <span m=''2838350''>advantages,</span> <span m=''2839280''>even</span> <span m=''2839610''>though,</span>
  <span m=''2839960''>in</span> <span m=''2840150''>particular,</span> <span m=''2840570''>because</span>
  <span m=''2840870''>they</span> <span m=''2840970''>don''t</span> <span m=''2841260''>use</span>
  <span m=''2841440''>locks.</span> <span m=''2842290''>And</span> <span m=''2842510''>so</span>
  <span m=''2842660''>I</span> <span m=''2842710''>want</span> <span m=''2842880''>to</span>
  <span m=''2842930''>illustrate</span> <span m=''2844180''>some</span> <span m=''2844450''>of</span>
  <span m=''2844540''>those</span> <span m=''2844930''>because</span> <span m=''2845270''>you''ll</span>
  <span m=''2845870''>see</span> <span m=''2846120''>these</span> <span m=''2846340''>in</span>
  <span m=''2846410''>certain places.</span> </p><p><span m=''2846790''>So</span>
  <span m=''2847020''>recall</span> <span m=''2847920''>the</span> <span m=''2848020''>summing</span>
  <span m=''2848370''>problem</span> <span m=''2848780''>from</span> <span m=''2848990''>last</span>
  <span m=''2849330''>time.</span> <span m=''2849620''>So</span> <span m=''2849770''>here</span>
  <span m=''2849970''>we</span> <span m=''2850100''>have</span> <span m=''2851630''>an
  array.</span> <span m=''2853710''>And</span> <span m=''2854120''>what</span> <span
  m=''2854290''>we''re</span> <span m=''2854400''>going</span> <span m=''2854480''>to</span>
  <span m=''2854570''>do</span> <span m=''2854980''>is</span> <span m=''2855420''>run</span>
  <span m=''2855780''>through</span> <span m=''2856200''>all</span> <span m=''2856460''>the</span>
  <span m=''2856570''>elements</span> <span m=''2856950''>in the</span> <span m=''2857070''>array,</span>
  <span m=''2857520''>computing</span> <span m=''2858010''>something</span> <span
  m=''2858460''>on</span> <span m=''2858610''>every</span> <span m=''2858880''>element,</span>
  <span m=''2859310''>and</span> <span m=''2859460''>adding</span> <span m=''2859810''>into</span>
  <span m=''2860130''>result.</span> <span m=''2861050''>And</span> <span m=''2861170''>we</span>
  <span m=''2861270''>wanted</span> <span m=''2861580''>to</span> <span m=''2861670''>parallelize</span>
  <span m=''2862400''>that.</span> <span m=''2863100''>So</span> <span m=''2863230''>we</span>
  <span m=''2863330''>parallelize</span> <span m=''2863920''>that</span> <span m=''2864230''>with</span>
  <span m=''2864360''>a</span> <span m=''2864620''>Cilk</span> <span m=''2864870''>4.</span>
  </p><p><span m=''2865750''>And</span> <span m=''2865920''>what</span> <span m=''2866070''>was</span>
  <span m=''2866200''>the</span> <span m=''2866280''>problem</span> <span m=''2866630''>when</span>
  <span m=''2866750''>we</span> <span m=''2866870''>parallelize</span> <span m=''2867390''>this?</span>
  <span m=''2869450''>We</span> <span m=''2869600''>get</span> <span m=''2869760''>a</span>
  <span m=''2869830''>race.</span> <span m=''2871770''>So</span> <span m=''2871930''>there''s</span>
  <span m=''2872190''>the</span> <span m=''2872280''>race.</span> <span m=''2872610''>We</span>
  <span m=''2872710''>get</span> <span m=''2872830''>a</span> <span m=''2872890''>race</span>
  <span m=''2873190''>on</span> <span m=''2873280''>result</span> <span m=''2873740''>because</span>
  <span m=''2873970''>we''ve</span> <span m=''2874140''>got</span> <span m=''2875100''>two</span>
  <span m=''2877660''>parallel</span> <span m=''2878110''>instructions</span> <span
  m=''2878690''>both</span> <span m=''2878920''>trying</span> <span m=''2879100''>to</span>
  <span m=''2879280''>update</span> <span m=''2879840''>results</span> <span m=''2880240''>at</span>
  <span m=''2880330''>the</span> <span m=''2880380''>same</span> <span m=''2880640''>time.</span>
  </p><p><span m=''2882810''>So</span> <span m=''2884010''>we</span> <span m=''2884500''>can</span>
  <span m=''2884830''>solve</span> <span m=''2885290''>that</span> <span m=''2885610''>with</span>
  <span m=''2885730''>a</span> <span m=''2885810''>lock.</span> <span m=''2886230''>And</span>
  <span m=''2886330''>I</span> <span m=''2886390''>showed</span> <span m=''2886640''>you</span>
  <span m=''2886760''>last</span> <span m=''2887160''>time</span> <span m=''2887450''>that</span>
  <span m=''2887570''>we</span> <span m=''2887690''>could</span> <span m=''2887830''>solve</span>
  <span m=''2888150''>this</span> <span m=''2888350''>for</span> <span m=''2888490''>lock.</span>
  <span m=''2890870''>By</span> <span m=''2892160''>declaring</span> <span m=''2892710''>a</span>
  <span m=''2892760''>mutex,</span> <span m=''2893500''>and</span> <span m=''2893930''>then</span>
  <span m=''2894090''>locking</span> <span m=''2894620''>before</span> <span m=''2895070''>we</span>
  <span m=''2896220''>update</span> <span m=''2896610''>the</span> <span m=''2896690''>results,</span>
  <span m=''2897070''>and</span> <span m=''2897150''>then</span> <span m=''2897350''>unlock.</span>
  <span m=''2898250''>And</span> <span m=''2898370''>of</span> <span m=''2898450''>course,</span>
  <span m=''2898740''>as</span> <span m=''2898870''>we</span> <span m=''2899010''>argued</span>
  <span m=''2899360''>yesterday,</span> <span m=''2899860''>that</span> <span m=''2900210''>could
  cause</span> <span m=''2900650''>severe</span> <span m=''2900930''>contention.</span>
  </p><p><span m=''2902170''>Now,</span> <span m=''2903010''>contention</span> <span
  m=''2903590''>can</span> <span m=''2903740''>be</span> <span m=''2903880''>an</span>
  <span m=''2903970''>issue.</span> <span m=''2904430''>But</span> <span m=''2904700''>if</span>
  <span m=''2905020''>it</span> <span m=''2905240''>turns</span> <span m=''2905540''>out</span>
  <span m=''2905770''>that</span> <span m=''2905910''>the</span> <span m=''2906030''>compute</span>
  <span m=''2906560''>here,</span> <span m=''2906960''>which</span> <span m=''2907170''>I''ve</span>
  <span m=''2907300''>moved</span> <span m=''2907740''>outside</span> <span m=''2908480''>the</span>
  <span m=''2908570''>lock</span> <span m=''2908970''>notice.</span> <span m=''2909990''>I''ve</span>
  <span m=''2910180''>put</span> <span m=''2910420''>it</span> <span m=''2910520''>into</span>
  <span m=''2910830''>temp</span> <span m=''2911520''>and</span> <span m=''2911670''>then</span>
  <span m=''2911830''>added</span> <span m=''2912230''>temp</span> <span m=''2912495''>in</span>
  <span m=''2912760''>so</span> <span m=''2912970''>I can</span> <span m=''2913060''>lock</span>
  <span m=''2913400''>for the</span> <span m=''2913520''>shortest</span> <span m=''2913910''>possible</span>
  <span m=''2914260''>time.</span> <span m=''2914860''>If</span> <span m=''2915000''>this</span>
  <span m=''2915220''>compute</span> <span m=''2915610''>is</span> <span m=''2915700''>sufficiently</span>
  <span m=''2916400''>large,</span> <span m=''2917950''>there</span> <span m=''2918080''>may</span>
  <span m=''2918250''>be</span> <span m=''2918380''>contention.</span> <span m=''2918890''>But</span>
  <span m=''2919030''>it</span> <span m=''2919080''>may</span> <span m=''2919200''>not</span>
  <span m=''2919470''>be</span> <span m=''2919570''>a</span> <span m=''2919620''>significant</span>
  <span m=''2920450''>contention</span> <span m=''2921030''>in</span> <span m=''2921150''>your</span>
  <span m=''2921340''>execution</span> <span m=''2922270''>because</span> <span m=''2922860''>the</span>
  <span m=''2923000''>update</span> <span m=''2923380''>here</span> <span m=''2923620''>could</span>
  <span m=''2923760''>be</span> <span m=''2923950''>very,</span> <span m=''2924220''>very</span>
  <span m=''2924470''>short</span> <span m=''2924860''>compared</span> <span m=''2925290''>with</span>
  <span m=''2925410''>the</span> <span m=''2925490''>time</span> <span m=''2925780''>it</span>
  <span m=''2925870''>takes</span> <span m=''2926190''>to</span> <span m=''2926800''>compute.</span>
  </p><p><span m=''2927330''>So</span> <span m=''2927530''>for</span> <span m=''2927640''>example,</span>
  <span m=''2927940''>if</span> <span m=''2928040''>computing</span> <span m=''2928550''>on</span>
  <span m=''2929220''>array</span> <span m=''2929510''>i</span> <span m=''2930300''>cost</span>
  <span m=''2930600''>you</span> <span m=''2930690''>more</span> <span m=''2931000''>than</span>
  <span m=''2931290''>say</span> <span m=''2932080''>order</span> <span m=''2932400''>n</span>
  <span m=''2932660''>time,</span> <span m=''2934020''>then</span> <span m=''2934890''>the</span>
  <span m=''2934980''>fact</span> <span m=''2935300''>that</span> <span m=''2938210''>you
  have</span> <span m=''2938520''>contention</span> <span m=''2939000''>there</span>
  <span m=''2939200''>isn''t</span> <span m=''2939420''>going</span> <span m=''2939500''>to</span>
  <span m=''2939580''>matter,</span> <span m=''2940040''>generally,</span> <span m=''2940520''>because</span>
  <span m=''2941540''>the</span> <span m=''2942240''>total</span> <span m=''2942530''>amount</span>
  <span m=''2942760''>of</span> <span m=''2942840''>time</span> <span m=''2943180''>that</span>
  <span m=''2943280''>you''re</span> <span m=''2943580''>going</span> <span m=''2943720''>to</span>
  <span m=''2943780''>be</span> <span m=''2943940''>locking</span> <span m=''2944410''>is</span>
  <span m=''2944530''>just</span> <span m=''2944710''>small</span> <span m=''2945110''>compared</span>
  <span m=''2945470''>to</span> <span m=''2945530''>the</span> <span m=''2945630''>total</span>
  <span m=''2945950''>execution</span> <span m=''2946510''>time.</span> <span m=''2949370''>Still</span>
  <span m=''2951040''>in</span> <span m=''2951170''>a</span> <span m=''2951210''>multiprogram</span>
  <span m=''2952000''>setting,</span> <span m=''2952580''>there</span> <span m=''2952770''>may</span>
  <span m=''2952980''>be</span> <span m=''2953160''>other</span> <span m=''2953370''>problems</span>
  <span m=''2953655''>that</span> <span m=''2953940''>you</span> <span m=''2954040''>can</span>
  <span m=''2954320''>get</span> <span m=''2954470''>into,</span> <span m=''2954890''>even</span>
  <span m=''2955290''>when</span> <span m=''2955480''>you</span> <span m=''2955650''>have</span>
  <span m=''2956080''>this</span> <span m=''2956470''>and</span> <span m=''2956790''>even</span>
  <span m=''2957140''>if</span> <span m=''2957340''>you</span> <span m=''2957510''>think</span>
  <span m=''2958340''>that</span> <span m=''2958600''>contention</span> <span m=''2959510''>is</span>
  <span m=''2959720''>going</span> <span m=''2959810''>to</span> <span m=''2959900''>be</span>
  <span m=''2960040''>minimal.</span> </p><p><span m=''2963810''>So</span> <span m=''2964130''>can
  anybody</span> <span m=''2964290''>think</span> <span m=''2964540''>of</span> <span
  m=''2964650''>what</span> <span m=''2964850''>the</span> <span m=''2965010''>issues</span>
  <span m=''2965350''>might</span> <span m=''2965610''>be?</span> <span m=''2966160''>Why</span>
  <span m=''2966390''>could</span> <span m=''2966600''>this</span> <span m=''2966780''>be</span>
  <span m=''2966900''>problematic</span> <span m=''2967600''>even</span> <span m=''2967950''>if</span>
  <span m=''2968120''>contention</span> <span m=''2969180''>is</span> <span m=''2969370''>not</span>
  <span m=''2969840''>a</span> <span m=''2969920''>big</span> <span m=''2970140''>issue?</span>
  <span m=''2975170''>And</span> <span m=''2975530''>the</span> <span m=''2975680''>hint</span>
  <span m=''2975930''>here</span> <span m=''2976260''>is</span> <span m=''2976380''>it''s</span>
  <span m=''2976570''>in a</span> <span m=''2976630''>multiprogram</span> <span m=''2977410''>setting.</span>
  <span m=''2990720''>So</span> <span m=''2990840''>what</span> <span m=''2990950''>happens</span>
  <span m=''2991330''>in</span> <span m=''2991370''>a</span> <span m=''2991410''>multiprogram</span>
  <span m=''2992080''>setting.</span> <span m=''2998770''>Yeah.</span> </p><p><span
  m=''2999445''>AUDIENCE: [INAUDIBLE]</span> <span m=''3001225''>PROFESSOR: Because</span>
  <span m=''3001670''>the resolve is--</span> </p><p><span m=''3002810''>AUDIENCE:
  [INAUDIBLE PHRASE]</span> </p><p><span m=''3007380''>PROFESSOR: It actually</span>
  <span m=''3007530''>doesn''t</span> <span m=''3007690''>have</span> <span m=''3007940''>to</span>
  <span m=''3008040''>do</span> <span m=''3008200''>with</span> <span m=''3008370''>resolve</span>
  <span m=''3008790''>here.</span> <span m=''3009960''>It has</span> <span m=''3010190''>to</span>
  <span m=''3010260''>do</span> <span m=''3010330''>with</span> <span m=''3010470''>locking</span>
  <span m=''3011110''>explicitly.</span> <span m=''3013960''>It''s</span> <span m=''3014090''>a</span>
  <span m=''3014140''>problem</span> <span m=''3014560''>with</span> <span m=''3014670''>locking</span>
  <span m=''3015200''>in</span> <span m=''3015280''>a</span> <span m=''3015330''>multiprogrammed</span>
  <span m=''3016010''>environment.</span> <span m=''3016800''>What</span> <span m=''3016940''>happens</span>
  <span m=''3017360''>in</span> <span m=''3017430''>a</span> <span m=''3017470''>multiprogrammed</span>
  <span m=''3018130''>environment?</span> <span m=''3018890''>What</span> <span m=''3019020''>do</span>
  <span m=''3019100''>I</span> <span m=''3019190''>mean</span> <span m=''3019390''>by</span>
  <span m=''3019530''>multiprogrammed</span> <span m=''3020210''>environment?</span>
  </p><p><span m=''3021143''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''3022090''>PROFESSOR:
  Have</span> <span m=''3022220''>multiple</span> <span m=''3022600''>jobs</span>
  <span m=''3023000''>running,</span> <span m=''3023320''>right?</span> <span m=''3023640''>And</span>
  <span m=''3023760''>what</span> <span m=''3023900''>happens</span> <span m=''3024360''>to</span>
  <span m=''3024460''>the</span> <span m=''3024560''>processor</span> <span m=''3025650''>when</span>
  <span m=''3025770''>there are</span> <span m=''3025870''>multiple</span> <span m=''3026240''>jobs</span>
  <span m=''3026590''>running?</span> </p><p><span m=''3027762''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''3029470''>PROFESSOR: Contact</span> <span m=''3030030''>switches.</span>
  <span m=''3034530''>So</span> <span m=''3034680''>now,</span> <span m=''3035430''>what</span>
  <span m=''3035620''>can</span> <span m=''3035760''>go</span> <span m=''3035940''>wrong</span>
  <span m=''3036240''>here?</span> <span m=''3036430''>What</span> <span m=''3036580''>can</span>
  <span m=''3036690''>be</span> <span m=''3036800''>really</span> <span m=''3037050''>bad</span>
  <span m=''3037320''>here?</span> <span m=''3038280''>Yeah.</span> </p><p><span m=''3038530''>AUDIENCE:
  You aquire</span> <span m=''3039027''>the lock</span> <span m=''3039524''>and then
  the</span> <span m=''3040021''>contacts switch out.</span> </p><p><span m=''3040520''>PROFESSOR:
  Yeah.</span> <span m=''3041560''>You</span> <span m=''3041660''>acquire</span> <span
  m=''3042030''>the</span> <span m=''3042140''>lock.</span> <span m=''3043140''>And</span>
  <span m=''3043300''>then,</span> <span m=''3043410''>the</span> <span m=''3043540''>operating</span>
  <span m=''3043890''>system</span> <span m=''3044240''>contact</span> <span m=''3044810''>switches</span>
  <span m=''3045110''>you</span> <span m=''3045270''>out.</span> <span m=''3046190''>And</span>
  <span m=''3046320''>so</span> <span m=''3046420''>what</span> <span m=''3046540''>happens?</span>
  <span m=''3046890''>You</span> <span m=''3047020''>hold</span> <span m=''3047330''>the</span>
  <span m=''3047390''>lock</span> <span m=''3049020''>while</span> <span m=''3049200''>some</span>
  <span m=''3049420''>other</span> <span m=''3049620''>job</span> <span m=''3050020''>is</span>
  <span m=''3050140''>running.</span> <span m=''3050570''>And</span> <span m=''3050660''>what</span>
  <span m=''3050810''>are</span> <span m=''3050860''>those</span> <span m=''3051150''>guys</span>
  <span m=''3051460''>doing.</span> <span m=''3052090''>They</span> <span m=''3052230''>go</span>
  <span m=''3052460''>and</span> <span m=''3052580''>spin</span> <span m=''3052940''>and</span>
  <span m=''3053060''>wait</span> <span m=''3053320''>on</span> <span m=''3053450''>the
  lock.</span> </p><p><span m=''3055460''>Now,</span> <span m=''3055590''>this</span>
  <span m=''3055760''>is</span> <span m=''3055930''>a</span> <span m=''3055980''>good</span>
  <span m=''3056320''>time</span> <span m=''3056700''>where</span> <span m=''3056850''>you''d</span>
  <span m=''3057020''>rather</span> <span m=''3057340''>not</span> <span m=''3057540''>have</span>
  <span m=''3057730''>a</span> <span m=''3058380''>spinning</span> <span m=''3058860''>lock.</span>
  <span m=''3059130''>You''d</span> <span m=''3059260''>rather</span> <span m=''3059570''>have</span>
  <span m=''3059870''>a</span> <span m=''3060930''>yielding</span> <span m=''3061410''>lock.</span>
  <span m=''3063010''>But</span> <span m=''3063150''>even</span> <span m=''3063460''>so,</span>
  <span m=''3064740''>suddenly</span> <span m=''3065300''>you''re</span> <span m=''3065490''>talking</span>
  <span m=''3065840''>about</span> <span m=''3066070''>something</span> <span m=''3066420''>that''s</span>
  <span m=''3066590''>operating</span> <span m=''3067740''>at</span> <span m=''3067840''>the</span>
  <span m=''3068130''>level</span> <span m=''3068530''>of</span> <span m=''3069000''>100</span>
  <span m=''3069390''>times</span> <span m=''3069700''>a</span> <span m=''3069750''>second,</span>
  <span m=''3070450''>10</span> <span m=''3070650''>milliseconds,</span> <span m=''3072250''>versus</span>
  <span m=''3072600''>something</span> <span m=''3072930''>that is</span> <span m=''3073060''>operating</span>
  <span m=''3073540''>on</span> <span m=''3073810''>a</span> <span m=''3073970''>nanosecond</span>
  <span m=''3074360''>level.</span> <span m=''3075940''>So</span> <span m=''3076060''>you''re</span>
  <span m=''3076150''>talking</span> <span m=''3076790''>six</span> <span m=''3077080''>orders</span>
  <span m=''3077400''>of</span> <span m=''3077450''>magnitude</span> <span m=''3078560''>of</span>
  <span m=''3078690''>performance</span> <span m=''3079460''>difference</span> <span
  m=''3080510''>if</span> <span m=''3080680''>you</span> <span m=''3080800''>end</span>
  <span m=''3080930''>up</span> <span m=''3081050''>getting</span> <span m=''3081250''>switched</span>
  <span m=''3081680''>out</span> <span m=''3084680''>while you</span> <span m=''3085020''>hold
  a lock.</span> <span m=''3090310''>That''s</span> <span m=''3090560''>the</span>
  <span m=''3090660''>issue.</span> <span m=''3090900''>What</span> <span m=''3091090''>happens.</span>
  </p><p><span m=''3091880''>And</span> <span m=''3092050''>then,</span> <span m=''3092370''>if</span>
  <span m=''3092610''>that</span> <span m=''3092830''>happens,</span> <span m=''3093590''>all</span>
  <span m=''3093930''>the</span> <span m=''3094070''>other</span> <span m=''3094330''>loop</span>
  <span m=''3094550''>iterations</span> <span m=''3095080''>must</span> <span m=''3095390''>wait.</span>
  </p><p><span m=''3097225''>AUDIENCE: [INAUDIBLE]</span> <span m=''3098710''>in the</span>
  <span m=''3099205''>large</span> <span m=''3099700''>program</span> <span m=''3100195''>here</span>
  <span m=''3100690''>[UNINTELLIGIBLE PHRASE].</span> <span m=''3103887''>I don''t</span>
  <span m=''3104294''>have a mic.</span> <span m=''3105110''>If one</span> <span m=''3105490''>[UNINTELLIGIBLE]</span>
  <span m=''3105870''>crashes</span> <span m=''3106366''>or one</span> <span m=''3106862''>[UNINTELLIGIBLE
  PHRASE]</span> <span m=''3112318''>the lock</span> <span m=''3112814''>[UNINTELLIGIBLE
  PHRASE].</span> </p><p><span m=''3121742''>AUDIENCE: Can</span> <span m=''3122260''>you</span>
  <span m=''3122490''>specify</span> <span m=''3123720''>whether</span> <span m=''3123980''>those</span>
  <span m=''3124630''>are yielding locks</span> <span m=''3125075''>or spinning locks?</span>
  </p><p><span m=''3125890''>PROFESSOR: Usually,</span> <span m=''3126165''>the</span>
  <span m=''3126440''>mutex</span> <span m=''3127360''>type</span> <span m=''3128065''>will
  tell you.</span> <span m=''3128370''>I''m</span> <span m=''3128680''>just</span>
  <span m=''3128850''>using</span> <span m=''3128960''>a simple</span> <span m=''3129245''>name</span>
  <span m=''3129530''>of</span> <span m=''3130030''>mutex.</span> <span m=''3130850''>I</span>
  <span m=''3130950''>probably</span> <span m=''3131200''>should</span> <span m=''3131350''>have</span>
  <span m=''3131420''>been</span> <span m=''3131560''>using</span> <span m=''3133620''>the</span>
  <span m=''3133730''>ones</span> <span m=''3134190''>that--</span> <span m=''3135140''>we
  were</span> <span m=''3135430''>using</span> <span m=''3135730''>one</span> <span
  m=''3135870''>called</span> <span m=''3136100''>Cilk</span> <span m=''3136280''>mutex.</span>
  <span m=''3137090''>And</span> <span m=''3137570''>I</span> <span m=''3137810''>probably
  should''ve</span> <span m=''3138080''>used</span> <span m=''3138360''>that</span>
  <span m=''3138650''>here</span> <span m=''3139310''>rather</span> <span m=''3139610''>than</span>
  <span m=''3139790''>just</span> <span m=''3140000''>simple</span> <span m=''3140460''>mutex.</span>
  </p><p><span m=''3142770''>AUDIENCE: Are they yielding?</span> </p><p><span m=''3145560''>PROFESSOR:
  There''s</span> <span m=''3145910''>a</span> <span m=''3145950''>good</span> <span
  m=''3146110''>question.</span> <span m=''3146620''>I</span> <span m=''3146800''>used</span>
  <span m=''3147020''>to</span> <span m=''3147090''>know</span> <span m=''3147250''>the</span>
  <span m=''3147360''>answer</span> <span m=''3147640''>to</span> <span m=''3147690''>this.</span>
  <span m=''3150330''>I</span> <span m=''3150440''>believe</span> <span m=''3150960''>that</span>
  <span m=''3151160''>those</span> <span m=''3152630''>spin</span> <span m=''3153160''>for</span>
  <span m=''3153280''>a</span> <span m=''3153410''>while, are</span> <span m=''3153780''>competitive.</span>
  <span m=''3154390''>They</span> <span m=''3154490''>spin</span> <span m=''3154800''>for</span>
  <span m=''3154880''>a</span> <span m=''3154960''>while</span> <span m=''3155310''>and</span>
  <span m=''3155430''>then</span> <span m=''3155560''>yield.</span> <span m=''3155890''>But</span>
  <span m=''3156020''>I''m</span> <span m=''3156120''>not</span> <span m=''3156320''>sure.</span>
  <span m=''3156610''>They</span> <span m=''3156730''>may</span> <span m=''3156900''>just</span>
  <span m=''3157090''>spin.</span> <span m=''3159260''>They</span> <span m=''3159410''>don''t</span>
  <span m=''3159720''>just</span> <span m=''3159910''>automatically</span> <span m=''3160470''>yield.</span>
  <span m=''3162720''>They''re</span> <span m=''3162820''>either</span> <span m=''3163120''>competitive,</span>
  <span m=''3163700''>or</span> <span m=''3163830''>they''ll</span> <span m=''3164100''>spin</span>
  <span m=''3164510''>and</span> <span m=''3164630''>yield.</span> <span m=''3165520''>I</span>
  <span m=''3165610''>believe</span> <span m=''3165930''>they</span> <span m=''3166050''>spin</span>
  <span m=''3166360''>and</span> <span m=''3166470''>yield.</span> <span m=''3167170''>And</span>
  <span m=''3167300''>I</span> <span m=''3167350''>believe</span> <span m=''3167620''>there''s</span>
  <span m=''3167770''>actually a</span> <span m=''3168130''>switch</span> <span m=''3168560''>where</span>
  <span m=''3168690''>you</span> <span m=''3168790''>can</span> <span m=''3168940''>tell</span>
  <span m=''3169210''>it--</span> <span m=''3169720''>if you''re</span> <span m=''3169820''>doing</span>
  <span m=''3170030''>timing</span> <span m=''3170410''>measurements--</span> <span
  m=''3173400''>make</span> <span m=''3173630''>it</span> <span m=''3173740''>so</span>
  <span m=''3173860''>that it</span> <span m=''3174020''>purely</span> <span m=''3174410''>spins</span>
  <span m=''3174760''>so that</span> <span m=''3175030''>you can get</span> <span
  m=''3175140''>better</span> <span m=''3175340''>benchmark</span> <span m=''3175810''>results.</span>
  </p><p><span m=''3177757''>AUDIENCE: So</span> <span m=''3178236''>my</span> <span
  m=''3178715''>question</span> <span m=''3179194''>is</span> <span m=''3180152''>does
  the</span> <span m=''3180631''>colonel</span> <span m=''3181110''>have</span> <span
  m=''3184950''>power</span> <span m=''3185430''>to</span> <span m=''3186370''>switch
  out</span> <span m=''3186790''>a spinning</span> <span m=''3187630''>lock</span>
  <span m=''3188050''>or not?</span> </p><p><span m=''3188660''>PROFESSOR: Yeah.</span>
  <span m=''3189270''>Well,</span> <span m=''3189460''>the</span> <span m=''3189550''>colonel,</span>
  <span m=''3190190''>the</span> <span m=''3190600''>scheduler,</span> <span m=''3191120''>can</span>
  <span m=''3191280''>come</span> <span m=''3191480''>in</span> <span m=''3191590''>at</span>
  <span m=''3191710''>any</span> <span m=''3191910''>moment</span> <span m=''3192330''>and
  say,</span> <span m=''3192690''>whip</span> <span m=''3192910''>you''re</span> <span
  m=''3193140''>out.</span> <span m=''3196160''>You''re</span> <span m=''3196470''>out.</span>
  <span m=''3196790''>That''s</span> <span m=''3196980''>it.</span> <span m=''3198850''>And</span>
  <span m=''3199210''>wherever</span> <span m=''3199820''>it</span> <span m=''3200040''>is,</span>
  <span m=''3200780''>it</span> <span m=''3200920''>interrupts</span> <span m=''3201370''>it</span>
  <span m=''3201520''>at</span> <span m=''3201640''>that</span> <span m=''3202600''>moment</span>
  <span m=''3202880''>in</span> <span m=''3202940''>time.</span> </p><p><span m=''3206670''>So</span>
  <span m=''3206980''>one</span> <span m=''3209100''>solution</span> <span m=''3209720''>to</span>
  <span m=''3209830''>this</span> <span m=''3210070''>problem</span> <span m=''3211060''>is</span>
  <span m=''3211360''>to</span> <span m=''3211450''>use</span> <span m=''3211800''>a</span>
  <span m=''3211910''>lock-free</span> <span m=''3212520''>method.</span> <span m=''3213110''>And</span>
  <span m=''3213350''>one</span> <span m=''3213500''>of</span> <span m=''3213570''>the</span>
  <span m=''3213640''>common</span> <span m=''3214030''>ways</span> <span m=''3214290''>of</span>
  <span m=''3214380''>doing</span> <span m=''3214630''>that</span> <span m=''3214870''>is</span>
  <span m=''3215010''>with</span> <span m=''3215150''>what''s</span> <span m=''3215430''>called</span>
  <span m=''3215730''>compare-and-swap</span> <span m=''3217160''>instruction.</span>
  <span m=''3218730''>So</span> <span m=''3218870''>this</span> <span m=''3219080''>is</span>
  <span m=''3219240''>what''s</span> <span m=''3219460''>called</span> <span m=''3219790''>a
  locking</span> <span m=''3220230''>instruction,</span> <span m=''3220810''>meaning</span>
  <span m=''3221130''>it''s</span> <span m=''3221370''>one</span> <span m=''3221560''>of</span>
  <span m=''3221600''>these</span> <span m=''3221770''>ones</span> <span m=''3222040''>that</span>
  <span m=''3222140''>goes</span> <span m=''3222460''>out</span> <span m=''3222720''>to</span>
  <span m=''3222810''>L2,</span> <span m=''3224240''>in</span> <span m=''3224390''>terms</span>
  <span m=''3224700''>of</span> <span m=''3225150''>timing</span> <span m=''3225600''>and</span>
  <span m=''3225710''>so</span> <span m=''3225910''>forth.</span> <span m=''3226590''>And</span>
  <span m=''3226710''>what</span> <span m=''3226870''>it</span> <span m=''3227010''>does</span>
  <span m=''3227690''>is</span> <span m=''3228550''>it</span> <span m=''3228730''>does</span>
  <span m=''3228940''>the</span> <span m=''3229020''>following</span> <span m=''3229530''>thing.</span>
  </p><p><span m=''3230950''>It</span> <span m=''3231320''>has</span> <span m=''3231800''>an</span>
  <span m=''3233170''>address of</span> <span m=''3233330''>a</span> <span m=''3233440''>location.</span>
  <span m=''3234530''>And</span> <span m=''3234690''>it''s</span> <span m=''3234860''>got</span>
  <span m=''3235200''>the</span> <span m=''3235360''>old</span> <span m=''3235790''>value</span>
  <span m=''3236220''>that</span> <span m=''3236390''>was</span> <span m=''3236500''>stored</span>
  <span m=''3237580''>in</span> <span m=''3238220''>the</span> <span m=''3238660''>location</span>
  <span m=''3239240''>and</span> <span m=''3239430''>a</span> <span m=''3239500''>new</span>
  <span m=''3239700''>value.</span> <span m=''3240520''>And it</span> <span m=''3240720''>says</span>
  <span m=''3241090''>if</span> <span m=''3241220''>the</span> <span m=''3241320''>value</span>
  <span m=''3241830''>that</span> <span m=''3242250''>is</span> <span m=''3242530''>there</span>
  <span m=''3243400''>is</span> <span m=''3243590''>the</span> <span m=''3243720''>old</span>
  <span m=''3244010''>value,</span> <span m=''3244810''>well,</span> <span m=''3244980''>then</span>
  <span m=''3245180''>stick</span> <span m=''3245530''>the</span> <span m=''3245620''>new</span>
  <span m=''3245810''>value</span> <span m=''3246230''>in</span> <span m=''3246360''>there.</span>
  <span m=''3247420''>And</span> <span m=''3248050''>then</span> <span m=''3248260''>return</span>
  <span m=''3249380''>essentially</span> <span m=''3250180''>true.</span> <span m=''3250700''>Otherwise</span>
  <span m=''3251230''>return</span> <span m=''3251610''>false.</span> <span m=''3254250''>So</span>
  <span m=''3254420''>it''s</span> <span m=''3254530''>basically</span> <span m=''3255030''>saying</span>
  <span m=''3260740''>what</span> <span m=''3260940''>you</span> <span m=''3261040''>tend</span>
  <span m=''3261320''>to</span> <span m=''3261410''>do</span> <span m=''3261780''>is</span>
  <span m=''3261980''>you</span> <span m=''3262130''>first</span> <span m=''3263020''>look</span>
  <span m=''3263300''>to</span> <span m=''3263410''>see</span> <span m=''3263590''>what''s</span>
  <span m=''3263860''>the</span> <span m=''3263920''>value.</span> <span m=''3265530''>You</span>
  <span m=''3265660''>then</span> <span m=''3265850''>update</span> <span m=''3266320''>the</span>
  <span m=''3266400''>value.</span> <span m=''3267260''>And</span> <span m=''3267380''>then
  you</span> <span m=''3267540''>say,</span> <span m=''3267820''>if</span> <span m=''3267950''>it</span>
  <span m=''3268050''>hasn''t</span> <span m=''3268490''>changed,</span> <span m=''3270910''>stick</span>
  <span m=''3271210''>it</span> <span m=''3271310''>back</span> <span m=''3271600''>in</span>
  <span m=''3272140''>and</span> <span m=''3272310''>return</span> <span m=''3272660''>true.</span>
  <span m=''3273160''>If</span> <span m=''3273300''>it</span> <span m=''3273410''>has</span>
  <span m=''3273840''>changed,</span> <span m=''3274820''>return</span> <span m=''3275180''>false.</span>
  <span m=''3277470''>So</span> <span m=''3277610''>it''s</span> <span m=''3278000''>only</span>
  <span m=''3278360''>swaps</span> <span m=''3279010''>the</span> <span m=''3279090''>value</span>
  <span m=''3280270''>if</span> <span m=''3280460''>it</span> <span m=''3281160''>is</span>
  <span m=''3281770''>true.</span> </p><p><span m=''3282110''>There''s</span> <span
  m=''3282290''>actually</span> <span m=''3282680''>two</span> <span m=''3282920''>versions.</span>
  <span m=''3283900''>One</span> <span m=''3284370''>which</span> <span m=''3284530''>says</span>
  <span m=''3284830''>bool</span> <span m=''3285240''>and</span> <span m=''3285310''>one</span>
  <span m=''3285500''>which</span> <span m=''3285660''>says</span> <span m=''3285940''>val.</span>
  <span m=''3287060''>And</span> <span m=''3287270''>if</span> <span m=''3287360''>you</span>
  <span m=''3287500''>do</span> <span m=''3287660''>the</span> <span m=''3287770''>bool</span>
  <span m=''3288120''>version,</span> <span m=''3288500''>it</span> <span m=''3288630''>returns</span>
  <span m=''3289270''>a</span> <span m=''3289470''>flag.</span> <span m=''3289765''>If</span>
  <span m=''3290060''>you</span> <span m=''3290190''>do the</span> <span m=''3290290''>val</span>
  <span m=''3290710''>version,</span> <span m=''3290990''>it</span> <span m=''3291270''>actually</span>
  <span m=''3291580''>returns the</span> <span m=''3291670''>value</span> <span m=''3292110''>that</span>
  <span m=''3292290''>was</span> <span m=''3292580''>in</span> <span m=''3292770''>there.</span>
  <span m=''3293210''>So</span> <span m=''3293360''>it''s</span> <span m=''3293960''>more</span>
  <span m=''3294340''>like</span> <span m=''3294570''>a</span> <span m=''3294670''>compare-and-swap.</span>
  <span m=''3295620''>The</span> <span m=''3295710''>main</span> <span m=''3295920''>thing</span>
  <span m=''3296060''>about</span> <span m=''3296630''>this is this</span> <span m=''3297100''>code</span>
  <span m=''3297560''>essentially</span> <span m=''3298140''>executes</span> <span
  m=''3298650''>atomically</span> <span m=''3299660''>with</span> <span m=''3299870''>the</span>
  <span m=''3300080''>single</span> <span m=''3300490''>instruction,</span> <span
  m=''3302120''>which</span> <span m=''3302420''>is</span> <span m=''3302550''>called--</span>
  <span m=''3307990''>The</span> <span m=''3308090''>instruction</span> <span m=''3309060''>is</span>
  <span m=''3310140''>cmpxchg.</span> <span m=''3314760''>Is it up there?</span> <span
  m=''3315420''>Oh,</span> <span m=''3315550''>there</span> <span m=''3315720''>it</span>
  <span m=''3315780''>is.</span> </p><p><span m=''3317720''>Yeah.</span> <span m=''3317970''>So</span>
  <span m=''3318080''>the</span> <span m=''3318250''>cmpxchg</span> <span m=''3319440''>instruction</span>
  <span m=''3320370''>on</span> <span m=''3320730''>x86.</span> <span m=''3321190''>So</span>
  <span m=''3321290''>when</span> <span m=''3321440''>you</span> <span m=''3321550''>compile</span>
  <span m=''3322860''>this,</span> <span m=''3323720''>you</span> <span m=''3323870''>should</span>
  <span m=''3324070''>find</span> <span m=''3324430''>on</span> <span m=''3324540''>your</span>
  <span m=''3325450''>assembly</span> <span m=''3326030''>output</span> <span m=''3326740''>that</span>
  <span m=''3327030''>instruction</span> <span m=''3327610''>somewhere</span> <span
  m=''3329400''>unless</span> <span m=''3330370''>the</span> <span m=''3330450''>compiler</span>
  <span m=''3330890''>figures</span> <span m=''3331180''>out</span> <span m=''3331310''>a</span>
  <span m=''3331350''>better</span> <span m=''3331620''>way</span> <span m=''3331760''>to</span>
  <span m=''3331910''>optimize</span> <span m=''3332470''>that.</span> <span m=''3333310''>But</span>
  <span m=''3333480''>generally,</span> <span m=''3333790''>you</span> <span m=''3333880''>should</span>
  <span m=''3334060''>find</span> <span m=''3334350''>that.</span> </p><p><span m=''3337330''>Also,</span>
  <span m=''3337780''>one</span> <span m=''3337970''>of</span> <span m=''3338010''>the</span>
  <span m=''3338100''>things</span> <span m=''3338340''>about</span> <span m=''3338650''>this</span>
  <span m=''3338850''>is</span> <span m=''3338980''>it</span> <span m=''3339060''>works</span>
  <span m=''3339480''>on</span> <span m=''3339760''>values</span> <span m=''3340400''>that</span>
  <span m=''3340540''>are</span> <span m=''3340660''>sort</span> <span m=''3340890''>of</span>
  <span m=''3340950''>integer</span> <span m=''3341370''>type</span> <span m=''3341680''>values.</span>
  <span m=''3342970''>But</span> <span m=''3343090''>it</span> <span m=''3343210''>doesn''t</span>
  <span m=''3343540''>work on</span> <span m=''3343920''>floating</span> <span m=''3344250''>point</span>
  <span m=''3344500''>numbers,</span> <span m=''3346410''>in</span> <span m=''3346550''>particular.</span>
  <span m=''3348080''>So</span> <span m=''3348260''>you</span> <span m=''3348360''>can''t</span>
  <span m=''3348680''>compare-and-swap</span> <span m=''3350000''>a</span> <span m=''3350070''>value,</span>
  <span m=''3350500''>which</span> <span m=''3350720''>is</span> <span m=''3350880''>a</span>
  <span m=''3351050''>floating</span> <span m=''3351410''>point</span> <span m=''3351720''>value.</span>
  <span m=''3351940''>You</span> <span m=''3352030''>can</span> <span m=''3352120''>only</span>
  <span m=''3352330''>do it</span> <span m=''3352470''>with</span> <span m=''3352650''>energy</span>
  <span m=''3352990''>type</span> <span m=''3353240''>values.</span> </p><p><span
  m=''3354060''>So</span> <span m=''3354250''>let''s</span> <span m=''3354400''>take</span>
  <span m=''3354590''>a</span> <span m=''3354670''>look</span> <span m=''3354880''>at</span>
  <span m=''3354940''>how</span> <span m=''3355170''>we</span> <span m=''3355340''>can</span>
  <span m=''3355680''>use</span> <span m=''3356100''>the</span> <span m=''3356260''>compare-and-swap</span>
  <span m=''3357370''>for the</span> <span m=''3357910''>summing</span> <span m=''3358300''>problem.</span>
  <span m=''3360120''>So</span> <span m=''3360270''>what</span> <span m=''3360410''>we</span>
  <span m=''3360540''>do</span> <span m=''3361020''>is</span> <span m=''3362010''>we</span>
  <span m=''3362160''>have</span> <span m=''3362350''>the</span> <span m=''3362430''>same</span>
  <span m=''3362730''>sort</span> <span m=''3362940''>of</span> <span m=''3363030''>code.</span>
  <span m=''3364090''>And</span> <span m=''3364270''>now,</span> <span m=''3364480''>what</span>
  <span m=''3364600''>I''m</span> <span m=''3364700''>going</span> <span m=''3364790''>to</span>
  <span m=''3364880''>do</span> <span m=''3365280''>is</span> <span m=''3365940''>compute</span>
  <span m=''3366590''>my</span> <span m=''3367140''>temporary</span> <span m=''3367530''>value.</span>
  <span m=''3368470''>And</span> <span m=''3368610''>then,</span> <span m=''3368720''>what</span>
  <span m=''3368910''>I''ll</span> <span m=''3369060''>do</span> <span m=''3369300''>is</span>
  <span m=''3369660''>I''ll</span> <span m=''3369980''>read</span> <span m=''3370240''>the</span>
  <span m=''3370320''>value</span> <span m=''3370740''>of</span> <span m=''3370860''>result</span>
  <span m=''3371350''>into</span> <span m=''3371610''>old.</span> <span m=''3373020''>I''ll</span>
  <span m=''3373220''>then</span> <span m=''3374240''>update</span> <span m=''3374840''>my</span>
  <span m=''3374980''>new</span> <span m=''3375260''>value</span> <span m=''3375760''>for</span>
  <span m=''3376410''>what</span> <span m=''3376590''>I</span> <span m=''3376670''>think</span>
  <span m=''3376940''>I</span> <span m=''3377020''>want</span> <span m=''3377350''>the</span>
  <span m=''3377430''>result</span> <span m=''3378140''>to</span> <span m=''3378260''>be</span>
  <span m=''3378420''>the</span> <span m=''3378530''>result</span> <span m=''3379000''>plus</span>
  <span m=''3379300''>the</span> <span m=''3379400''>thing</span> <span m=''3379610''>that</span>
  <span m=''3379720''>I</span> <span m=''3379810''>computed.</span> </p><p><span m=''3382240''>And</span>
  <span m=''3382410''>now,</span> <span m=''3382620''>what</span> <span m=''3382780''>I</span>
  <span m=''3382890''>do</span> <span m=''3383380''>is</span> <span m=''3385020''>I</span>
  <span m=''3385880''>attempt</span> <span m=''3386660''>to</span> <span m=''3388620''>compare-and-swap</span>
  <span m=''3390520''>as</span> <span m=''3390660''>long</span> <span m=''3390970''>as</span>
  <span m=''3391070''>the</span> <span m=''3391210''>old</span> <span m=''3391520''>value
  is</span> <span m=''3392010''>what</span> <span m=''3392160''>I</span> <span m=''3392400''>read</span>
  <span m=''3392640''>it</span> <span m=''3392780''>to</span> <span m=''3392880''>be.</span>
  <span m=''3395280''>Swap</span> <span m=''3395700''>in</span> <span m=''3395840''>the</span>
  <span m=''3395930''>new</span> <span m=''3396080''>value.</span> <span m=''3398560''>If</span>
  <span m=''3398750''>the</span> <span m=''3398890''>old</span> <span m=''3399150''>value</span>
  <span m=''3399490''>turns</span> <span m=''3399780''>out</span> <span m=''3399940''>to</span>
  <span m=''3400020''>be</span> <span m=''3400150''>different</span> <span m=''3400940''>from</span>
  <span m=''3402170''>what</span> <span m=''3402420''>is</span> <span m=''3402590''>currently</span>
  <span m=''3403160''>in</span> <span m=''3403310''>the</span> <span m=''3403410''>result</span>
  <span m=''3403770''>location,</span> <span m=''3404940''>then</span> <span m=''3405120''>it</span>
  <span m=''3405220''>returns</span> <span m=''3405760''>false.</span> <span m=''3406470''>And</span>
  <span m=''3406680''>I</span> <span m=''3406780''>redo</span> <span m=''3407170''>this</span>
  <span m=''3407360''>again.</span> <span m=''3412110''>Then,</span> <span m=''3412240''>I</span>
  <span m=''3412350''>have</span> <span m=''3412510''>to</span> <span m=''3412620''>redo</span>
  <span m=''3412920''>the</span> <span m=''3413020''>whole</span> <span m=''3413320''>loop</span>
  <span m=''3413490''>again.</span> </p><p><span m=''3415020''>So</span> <span m=''3415150''>this</span>
  <span m=''3415250''>is</span> <span m=''3415300''>a</span> <span m=''3415380''>do-while</span>
  <span m=''3415930''>loop.</span> <span m=''3416560''>Do-while</span> <span m=''3416990''>is</span>
  <span m=''3417220''>like</span> <span m=''3417400''>a</span> <span m=''3417460''>while</span>
  <span m=''3417740''>loop,</span> <span m=''3417930''>except</span> <span m=''3418280''>you</span>
  <span m=''3418380''>do</span> <span m=''3418530''>the</span> <span m=''3418630''>body</span>
  <span m=''3418950''>first.</span> <span m=''3419690''>And</span> <span m=''3419820''>then</span>
  <span m=''3419950''>you</span> <span m=''3420070''>test</span> <span m=''3420550''>the</span>
  <span m=''3420980''>condition.</span> <span m=''3421860''>So</span> <span m=''3422050''>if</span>
  <span m=''3422120''>this</span> <span m=''3422350''>fails,</span> <span m=''3422850''>I</span>
  <span m=''3422950''>go</span> <span m=''3423120''>back.</span> <span m=''3423970''>I
  then</span> <span m=''3424200''>get</span> <span m=''3424460''>a</span> <span m=''3424570''>new</span>
  <span m=''3424780''>value</span> <span m=''3425150''>for</span> <span m=''3425250''>the</span>
  <span m=''3425360''>result</span> <span m=''3426330''>and</span> <span m=''3426420''>so</span>
  <span m=''3426590''>forth.</span> <span m=''3426850''>So</span> <span m=''3427050''>let</span>
  <span m=''3427180''>me</span> <span m=''3427270''>show</span> <span m=''3427440''>you</span>
  <span m=''3427520''>how</span> <span m=''3427690''>that</span> <span m=''3427860''>works.</span>
  <span m=''3433410''>Let''s</span> <span m=''3433630''>see.</span> <span m=''3435190''>So</span>
  <span m=''3435390''>first,</span> <span m=''3435690''>I''ll</span> <span m=''3435920''>show</span>
  <span m=''3436050''>you</span> <span m=''3436130''>how</span> <span m=''3436290''>this</span>
  <span m=''3436450''>works.</span> <span m=''3437160''>Actually,</span> <span m=''3437570''>I''ll</span>
  <span m=''3437780''>show</span> <span m=''3438050''>it on</span> <span m=''3438180''>a</span>
  <span m=''3438520''>more</span> <span m=''3438840''>interesting</span> <span m=''3439310''>example</span>
  <span m=''3439710''>how</span> <span m=''3439850''>this</span> <span m=''3440040''>works.</span>
  </p><p><span m=''3441930''>So</span> <span m=''3442110''>what</span> <span m=''3442240''>happens</span>
  <span m=''3442960''>if</span> <span m=''3443170''>I</span> <span m=''3443320''>get</span>
  <span m=''3443510''>swapped</span> <span m=''3443990''>out</span> <span m=''3444230''>in</span>
  <span m=''3444340''>the</span> <span m=''3444420''>middle</span> <span m=''3444690''>of</span>
  <span m=''3444780''>a</span> <span m=''3444850''>loop</span> <span m=''3445080''>iteration?</span>
  <span m=''3446360''>All</span> <span m=''3446650''>I</span> <span m=''3446710''>do</span>
  <span m=''3446920''>is</span> <span m=''3447040''>when</span> <span m=''3447190''>I</span>
  <span m=''3447260''>do</span> <span m=''3447400''>the</span> <span m=''3447500''>compare-and-swap</span>
  <span m=''3448290''>it</span> <span m=''3448400''>fails.</span> <span m=''3451100''>So</span>
  <span m=''3451310''>no</span> <span m=''3451540''>other</span> <span m=''3451840''>instructions</span>
  <span m=''3452480''>can</span> <span m=''3452630''>wait.</span> <span m=''3452850''>They</span>
  <span m=''3452940''>can</span> <span m=''3453070''>all</span> <span m=''3454280''>march</span>
  <span m=''3454640''>ahead</span> <span m=''3455050''>and</span> <span m=''3455250''>do</span>
  <span m=''3455370''>the</span> <span m=''3455480''>thing</span> <span m=''3455720''>they</span>
  <span m=''3455830''>need</span> <span m=''3456080''>to</span> <span m=''3456170''>do.</span>
  <span m=''3457120''>And</span> <span m=''3457320''>then,</span> <span m=''3457460''>the</span>
  <span m=''3457550''>one</span> <span m=''3457760''>that</span> <span m=''3457890''>got</span>
  <span m=''3458080''>swapped</span> <span m=''3458450''>out,</span> <span m=''3458800''>eh.</span>
  <span m=''3459520''>It</span> <span m=''3459680''>gets</span> <span m=''3459910''>some</span>
  <span m=''3460240''>old</span> <span m=''3460480''>value.</span> <span m=''3461870''>It</span>
  <span m=''3462050''>discovers</span> <span m=''3462590''>that</span> <span m=''3463260''>and</span>
  <span m=''3463400''>has</span> <span m=''3463540''>to</span> <span m=''3463650''>re-execute</span>
  <span m=''3464280''>the</span> <span m=''3464360''>loop.</span> </p><p><span m=''3467230''>So</span>
  <span m=''3467360''>is</span> <span m=''3467510''>that</span> <span m=''3467810''>fine?</span>
  <span m=''3468270''>So what</span> <span m=''3468380''>this</span> <span m=''3468530''>means</span>
  <span m=''3468900''>is</span> <span m=''3469240''>that</span> <span m=''3469460''>the</span>
  <span m=''3469580''>amount</span> <span m=''3470000''>work</span> <span m=''3470490''>that''s</span>
  <span m=''3470700''>going</span> <span m=''3470960''>on,</span> <span m=''3471200''>however,</span>
  <span m=''3472200''>could</span> <span m=''3472370''>in</span> <span m=''3472500''>fact,</span>
  <span m=''3472850''>be</span> <span m=''3472940''>greater,</span> <span m=''3474100''>depending</span>
  <span m=''3474470''>upon</span> <span m=''3476220''>how</span> <span m=''3476420''>much</span>
  <span m=''3476630''>contention</span> <span m=''3477390''>there is. If</span> <span
  m=''3477480''>there''s</span> <span m=''3477630''>a</span> <span m=''3477680''>lot</span>
  <span m=''3477920''>of</span> <span m=''3478010''>contention,</span> <span m=''3478580''>you</span>
  <span m=''3478700''>could</span> <span m=''3478830''>end</span> <span m=''3479010''>up</span>
  <span m=''3479120''>having</span> <span m=''3479960''>these</span> <span m=''3480190''>guys</span>
  <span m=''3481890''>fighting</span> <span m=''3482790''>and</span> <span m=''3483030''>not</span>
  <span m=''3486150''>re</span> <span m=''3486400''>executing</span> <span m=''3487700''>a</span>
  <span m=''3487790''>lot</span> <span m=''3487960''>of</span> <span m=''3488060''>code.</span>
  <span m=''3488680''>But</span> <span m=''3488850''>that''s</span> <span m=''3489140''>really</span>
  <span m=''3489440''>not</span> <span m=''3489690''>much</span> <span m=''3489890''>worse</span>
  <span m=''3490180''>than</span> <span m=''3490350''>them</span> <span m=''3490530''>spinning</span>
  <span m=''3491140''>is</span> <span m=''3491330''>what</span> <span m=''3491450''>it</span>
  <span m=''3491520''>comes</span> <span m=''3491740''>down</span> <span m=''3491970''>to.</span>
  <span m=''3494590''>Any</span> <span m=''3494750''>questions?</span> </p><p><span
  m=''3496470''>Let''s</span> <span m=''3496660''>do</span> <span m=''3496760''>a</span>
  <span m=''3496820''>more</span> <span m=''3497040''>interesting</span> <span m=''3497440''>example.</span>
  <span m=''3500170''>Here''s</span> <span m=''3500500''>a</span> <span m=''3500580''>lock-free</span>
  <span m=''3501150''>stack.</span> <span m=''3503160''>So</span> <span m=''3503350''>what</span>
  <span m=''3503500''>we''re</span> <span m=''3503600''>going</span> <span m=''3503680''>to</span>
  <span m=''3503770''>do</span> <span m=''3504210''>is</span> <span m=''3504520''>we''re</span>
  <span m=''3504610''>going</span> <span m=''3504690''>to</span> <span m=''3504830''>have</span>
  <span m=''3504970''>a</span> <span m=''3505040''>node,</span> <span m=''3505550''>which</span>
  <span m=''3505720''>has</span> <span m=''3505900''>a</span> <span m=''3505960''>next</span>
  <span m=''3506360''>pointer</span> <span m=''3506620''>and</span> <span m=''3506810''>some</span>
  <span m=''3507010''>data.</span> <span m=''3507760''>All</span> <span m=''3507950''>we</span>
  <span m=''3508070''>really</span> <span m=''3508330''>care</span> <span m=''3508590''>about</span>
  <span m=''3508780''>is</span> <span m=''3508870''>the</span> <span m=''3508970''>next</span>
  <span m=''3509300''>pointer.</span> <span m=''3510170''>And</span> <span m=''3510400''>we</span>
  <span m=''3510490''>have</span> <span m=''3510620''>a</span> <span m=''3510670''>stack,</span>
  <span m=''3511190''>which</span> <span m=''3511570''>has</span> <span m=''3512910''>basically</span>
  <span m=''3513760''>a</span> <span m=''3514040''>head</span> <span m=''3514870''>pointer.</span>
  </p><p><span m=''3518150''>So</span> <span m=''3518320''>we</span> <span m=''3518400''>have</span>
  <span m=''3518550''>a</span> <span m=''3518610''>linked</span> <span m=''3518870''>list</span>
  <span m=''3519100''>here.</span> <span m=''3519790''>We</span> <span m=''3519900''>want</span>
  <span m=''3520080''>to</span> <span m=''3520120''>basically</span> <span m=''3520590''>be
  able to</span> <span m=''3520780''>insert</span> <span m=''3521230''>things</span>
  <span m=''3521480''>at</span> <span m=''3521570''>the</span> <span m=''3521660''>front</span>
  <span m=''3522010''>and</span> <span m=''3522170''>take</span> <span m=''3522380''>things</span>
  <span m=''3522630''>out</span> <span m=''3522850''>of the</span> <span m=''3522930''>front.</span>
  <span m=''3525440''>So</span> <span m=''3525700''>here''s</span> <span m=''3526000''>a</span>
  <span m=''3526060''>lock-free</span> <span m=''3526730''>push.</span> <span m=''3527910''>So</span>
  <span m=''3528420''>remember,</span> <span m=''3528640''>this</span> <span m=''3528820''>could</span>
  <span m=''3528940''>be</span> <span m=''3529070''>concurrent.</span> <span m=''3529710''>So</span>
  <span m=''3529880''>these</span> <span m=''3530140''>guys</span> <span m=''3530480''>want</span>
  <span m=''3530680''>to</span> <span m=''3530770''>operate</span> <span m=''3531260''>on</span>
  <span m=''3531430''>it</span> <span m=''3531540''>at</span> <span m=''3531610''>a</span>
  <span m=''3531710''>time.</span> <span m=''3532060''>We</span> <span m=''3532160''>saw</span>
  <span m=''3532360''>last</span> <span m=''3532760''>time</span> <span m=''3533280''>how</span>
  <span m=''3533510''>in</span> <span m=''3533760''>doing</span> <span m=''3534030''>very</span>
  <span m=''3534250''>simple</span> <span m=''3534610''>updates</span> <span m=''3535130''>on</span>
  <span m=''3535590''>link</span> <span m=''3536030''>structures,</span> <span m=''3536540''>you</span>
  <span m=''3536660''>could</span> <span m=''3536840''>get</span> <span m=''3537570''>yourself</span>
  <span m=''3537950''>into</span> <span m=''3538150''>a</span> <span m=''3538210''>mess</span>
  <span m=''3539920''>if</span> <span m=''3540120''>you</span> <span m=''3540260''>didn''t</span>
  <span m=''3540620''>properly</span> <span m=''3541070''>synchronize</span> <span
  m=''3541710''>when</span> <span m=''3541840''>we</span> <span m=''3541960''>did</span>
  <span m=''3542260''>the</span> <span m=''3543300''>insertion</span> <span m=''3543800''>in</span>
  <span m=''3543890''>the</span> <span m=''3543950''>hash</span> <span m=''3544280''>table.</span>
  </p><p><span m=''3545710''>So</span> <span m=''3545830''>here''s</span> <span m=''3546120''>my</span>
  <span m=''3546280''>push</span> <span m=''3546590''>[? up ?]</span> <span m=''3546900''>code.</span>
  <span m=''3549370''>Well</span> <span m=''3549540''>let''s</span> <span m=''3549710''>walk</span>
  <span m=''3549960''>through</span> <span m=''3550170''>it.</span> <span m=''3550430''>It
  says,</span> <span m=''3550670''>basically,</span> <span m=''3552690''>here''s</span>
  <span m=''3552950''>my</span> <span m=''3553120''>node</span> <span m=''3553470''>that</span>
  <span m=''3553680''>I</span> <span m=''3553760''>want</span> <span m=''3554020''>to</span>
  <span m=''3554180''>insert.</span> <span m=''3555580''>It</span> <span m=''3555890''>says,</span>
  <span m=''3556740''>first</span> <span m=''3557180''>of</span> <span m=''3557290''>all,</span>
  <span m=''3557750''>make</span> <span m=''3558030''>node.next</span> <span m=''3558820''>point</span>
  <span m=''3559310''>to the</span> <span m=''3559585''>head.</span> <span m=''3560350''>So</span>
  <span m=''3560470''>we</span> <span m=''3560550''>basically</span> <span m=''3561000''>have</span>
  <span m=''3561120''>it</span> <span m=''3561240''>pointing</span> <span m=''3561630''>to</span>
  <span m=''3561730''>77.</span> <span m=''3565220''>So</span> <span m=''3565410''>then</span>
  <span m=''3565630''>what</span> <span m=''3565780''>we</span> <span m=''3565920''>say</span>
  <span m=''3566320''>is</span> <span m=''3566820''>OK.</span> <span m=''3567840''>Let''s</span>
  <span m=''3568570''>compare-and-swap</span> <span m=''3570400''>to</span> <span
  m=''3570570''>make</span> <span m=''3571410''>the</span> <span m=''3571500''>head</span>
  <span m=''3572390''>point</span> <span m=''3572690''>to</span> <span m=''3572790''>the</span>
  <span m=''3572900''>node</span> <span m=''3574430''>but</span> <span m=''3574610''>only</span>
  <span m=''3575730''>if</span> <span m=''3576090''>the</span> <span m=''3576260''>value</span>
  <span m=''3577460''>of</span> <span m=''3577730''>the</span> <span m=''3578000''>head</span>
  <span m=''3578280''>has</span> <span m=''3578540''>not</span> <span m=''3578800''>changed.</span>
  <span m=''3579670''>It''s</span> <span m=''3579870''>still</span> <span m=''3580820''>the</span>
  <span m=''3580910''>value</span> <span m=''3581250''>of</span> <span m=''3581330''>the</span>
  <span m=''3581420''>node.next.</span> <span m=''3585100''>And</span> <span m=''3585280''>if</span>
  <span m=''3585370''>so,</span> <span m=''3585910''>it</span> <span m=''3586080''>does</span>
  <span m=''3586320''>the</span> <span m=''3586410''>swap.</span> <span m=''3587900''>Question?</span>
  </p><p><span m=''3589585''>AUDIENCE:</span> <span m=''3590010''>You</span> <span
  m=''3590410''>say</span> <span m=''3590800''>compare-and-swap.</span> <span m=''3591232''>But</span>
  <span m=''3591664''>you</span> <span m=''3592096''>compare it</span> <span m=''3592530''>to</span>
  <span m=''3592880''>what?</span> </p><p><span m=''3594850''>PROFESSOR: PROFESSOR:
  In</span> <span m=''3594940''>this</span> <span m=''3595100''>case it''s</span>
  <span m=''3595390''>comparing</span> <span m=''3596480''>to</span> <span m=''3596610''>the--</span>
  <span m=''3597270''>so</span> <span m=''3597430''>this</span> <span m=''3597620''>is</span>
  <span m=''3597730''>basically</span> <span m=''3598210''>the</span> <span m=''3599810''>location</span>
  <span m=''3600360''>that</span> <span m=''3600470''>you''re</span> <span m=''3600580''>doing</span>
  <span m=''3600790''>the</span> <span m=''3600940''>compare-and-swap</span> <span
  m=''3601700''>on,</span> <span m=''3602360''>the</span> <span m=''3602560''>old</span>
  <span m=''3602940''>value</span> <span m=''3603670''>that</span> <span m=''3604130''>you</span>
  <span m=''3604340''>expect</span> <span m=''3604820''>to</span> <span m=''3604910''>see</span>
  <span m=''3605690''>in</span> <span m=''3605820''>that</span> <span m=''3606030''>location,</span>
  <span m=''3606940''>and</span> <span m=''3607110''>the</span> <span m=''3607190''>new</span>
  <span m=''3607340''>value.</span> <span m=''3608400''>So</span> <span m=''3608600''>here,</span>
  <span m=''3608910''>what</span> <span m=''3609060''>it</span> <span m=''3609200''>says--</span>
  <span m=''3610730''>when</span> <span m=''3610760''>we''re</span> <span m=''3611040''>at
  this</span> <span m=''3611320''>point</span> <span m=''3611540''>here--</span> <span
  m=''3612250''>we''re</span> <span m=''3612360''>saying</span> <span m=''3612660''>before</span>
  <span m=''3613000''>you</span> <span m=''3613230''>do the</span> <span m=''3613620''>compare-and-swap,</span>
  <span m=''3614000''>we''re saying,</span> <span m=''3614660''>I</span> <span m=''3614810''>only</span>
  <span m=''3615170''>want</span> <span m=''3615610''>you to</span> <span m=''3615690''>set</span>
  <span m=''3616000''>that</span> <span m=''3616290''>pointer</span> <span m=''3616580''>to</span>
  <span m=''3616640''>go</span> <span m=''3616900''>to here</span> <span m=''3622770''>if</span>
  <span m=''3623770''>this</span> <span m=''3624060''>value</span> <span m=''3624410''>is</span>
  <span m=''3624490''>still</span> <span m=''3624720''>pointing</span> <span m=''3625020''>to</span>
  <span m=''3625130''>there.</span> </p><p><span m=''3627410''>So</span> <span m=''3627660''>only</span>
  <span m=''3628010''>move</span> <span m=''3628270''>this</span> <span m=''3628490''>here</span>
  <span m=''3629070''>if</span> <span m=''3629220''>this</span> <span m=''3629440''>value
  is</span> <span m=''3629780''>still</span> <span m=''3630050''>77.</span> <span
  m=''3630800''>In other words,</span> <span m=''3631000''>if somebody</span> <span
  m=''3631420''>else</span> <span m=''3631620''>came</span> <span m=''3631870''>in--</span>
  <span m=''3632420''>well,</span> <span m=''3632740''>I''ll</span> <span m=''3632870''>do</span>
  <span m=''3633070''>an</span> <span m=''3633140''>example</span> <span m=''3633520''>in</span>
  <span m=''3633580''>a</span> <span m=''3633630''>second</span> <span m=''3634330''>that</span>
  <span m=''3634440''>shows</span> <span m=''3634860''>what</span> <span m=''3635010''>happens</span>
  <span m=''3635670''>when</span> <span m=''3635820''>we</span> <span m=''3635950''>have</span>
  <span m=''3636190''>concurrency,</span> <span m=''3636710''>and</span> <span m=''3637010''>one</span>
  <span m=''3637170''>of</span> <span m=''3637300''>them might</span> <span m=''3637490''>fail.</span>
  <span m=''3639940''>But</span> <span m=''3640090''>if</span> <span m=''3640200''>it</span>
  <span m=''3640300''>is</span> <span m=''3640600''>true,</span> <span m=''3640900''>then</span>
  <span m=''3641090''>it</span> <span m=''3641210''>basically</span> <span m=''3641660''>sets
  it.</span> <span m=''3642030''>And</span> <span m=''3642250''>now</span> <span m=''3642460''>I''m</span>
  <span m=''3643520''>home</span> <span m=''3643730''>free.</span> </p><p><span m=''3646790''>So</span>
  <span m=''3646990''>let''s</span> <span m=''3647280''>take</span> <span m=''3647500''>a</span>
  <span m=''3647560''>look</span> <span m=''3647810''>at</span> <span m=''3647880''>what</span>
  <span m=''3648010''>happens</span> <span m=''3648430''>when</span> <span m=''3648580''>we</span>
  <span m=''3648680''>have</span> <span m=''3648810''>contention.</span> <span m=''3649195''>So
  I have</span> <span m=''3649580''>two</span> <span m=''3650030''>guys.</span> <span
  m=''3651220''>So</span> <span m=''3651440''>33</span> <span m=''3652610''>says,</span>
  <span m=''3652970''>OK</span> <span m=''3653370''>I''ll</span> <span m=''3653550''>come</span>
  <span m=''3653760''>in.</span> <span m=''3654170''>Let</span> <span m=''3654330''>me</span>
  <span m=''3654500''>set</span> <span m=''3654770''>my</span> <span m=''3654920''>next</span>
  <span m=''3655240''>pointer</span> <span m=''3655520''>to the</span> <span m=''3655640''>head.</span>
  <span m=''3656600''>But</span> <span m=''3656730''>then</span> <span m=''3656910''>comes</span>
  <span m=''3657370''>81.</span> <span m=''3658030''>And it</span> <span m=''3658190''>says,</span>
  <span m=''3658400''>OK.</span> <span m=''3659450''>Let</span> <span m=''3659590''>me</span>
  <span m=''3659770''>try</span> <span m=''3660140''>to</span> <span m=''3661740''>set</span>
  <span m=''3662000''>my</span> <span m=''3662210''>pointer</span> <span m=''3662610''>to</span>
  <span m=''3662770''>also</span> <span m=''3663100''>be</span> <span m=''3663260''>77</span>
  <span m=''3663990''>because</span> <span m=''3664170''>I</span> <span m=''3664420''>look</span>
  <span m=''3664700''>at</span> <span m=''3664860''>what the</span> <span m=''3665000''>head</span>
  <span m=''3665150''>is, and</span> <span m=''3665400''>that''s</span> <span m=''3665640''>where
  it''s</span> <span m=''3665760''>supposed</span> <span m=''3666110''>to</span> <span
  m=''3666180''>go.</span> </p><p><span m=''3668600''>So</span> <span m=''3668770''>now,</span>
  <span m=''3669010''>what</span> <span m=''3669140''>happens</span> <span m=''3669570''>is</span>
  <span m=''3669680''>we</span> <span m=''3669790''>do</span> <span m=''3669990''>the</span>
  <span m=''3670160''>compare-and-swap</span> <span m=''3671210''>operation.</span>
  <span m=''3672950''>And</span> <span m=''3673080''>they</span> <span m=''3673170''>both</span>
  <span m=''3673560''>are</span> <span m=''3673640''>going</span> <span m=''3673760''>to</span>
  <span m=''3673820''>try</span> <span m=''3674040''>to</span> <span m=''3674140''>do</span>
  <span m=''3674370''>it.</span> <span m=''3674560''>And one</span> <span m=''3674820''>of</span>
  <span m=''3674870''>them</span> <span m=''3675020''>is</span> <span m=''3675140''>going</span>
  <span m=''3675380''>to,</span> <span m=''3675640''>essentially,</span> <span m=''3676580''>do</span>
  <span m=''3676730''>it</span> <span m=''3676920''>first</span> <span m=''3677330''>because</span>
  <span m=''3677690''>the</span> <span m=''3678200''>hardware</span> <span m=''3678800''>preserves</span>
  <span m=''3679250''>that</span> <span m=''3679700''>the</span> <span m=''3679820''>compare-and-swaps,</span>
  <span m=''3680530''>their</span> <span m=''3680670''>locking</span> <span m=''3681090''>operations,</span>
  <span m=''3681910''>they</span> <span m=''3682070''>will</span> <span m=''3682280''>happen</span>
  <span m=''3682670''>in</span> <span m=''3682800''>some</span> <span m=''3683070''>definite</span>
  <span m=''3683460''>order.</span> </p><p><span m=''3685220''>So</span> <span m=''3685390''>in</span>
  <span m=''3685450''>this</span> <span m=''3685650''>case,</span> <span m=''3687170''>81</span>
  <span m=''3687740''>got</span> <span m=''3687960''>in</span> <span m=''3688140''>there</span>
  <span m=''3688400''>and</span> <span m=''3688750''>did its</span> <span m=''3688920''>compare-and-swap</span>
  <span m=''3689660''>first.</span> <span m=''3689990''>When it</span> <span m=''3690190''>looked,</span>
  <span m=''3690850''>77</span> <span m=''3691550''>was</span> <span m=''3691680''>still</span>
  <span m=''3692010''>a</span> <span m=''3692040''>value</span> <span m=''3692390''>that</span>
  <span m=''3692520''>it</span> <span m=''3692670''>said.</span> <span m=''3693040''>So</span>
  <span m=''3693190''>it</span> <span m=''3693280''>allowed</span> <span m=''3693580''>that</span>
  <span m=''3693780''>pointer</span> <span m=''3693970''>to</span> <span m=''3694100''>be</span>
  <span m=''3694240''>changed.</span> <span m=''3694950''>But</span> <span m=''3695320''>now</span>
  <span m=''3695530''>what</span> <span m=''3695660''>happens</span> <span m=''3696080''>when</span>
  <span m=''3696260''>33</span> <span m=''3696800''>tries.</span> <span m=''3698310''>33</span>
  <span m=''3698810''>tries</span> <span m=''3699110''>to</span> <span m=''3699200''>do</span>
  <span m=''3699400''>the</span> <span m=''3699700''>compare-and-swap.</span> <span
  m=''3700850''>And</span> <span m=''3700950''>the</span> <span m=''3701030''>compare-and-swap</span>
  <span m=''3701820''>fails</span> <span m=''3702720''>because</span> <span m=''3703530''>it''s</span>
  <span m=''3703820''>saying,</span> <span m=''3704090''>I</span> <span m=''3704130''>want</span>
  <span m=''3704280''>to</span> <span m=''3704320''>swap</span> <span m=''3704650''>33</span>
  <span m=''3705150''>in</span> <span m=''3705320''>as</span> <span m=''3705490''>long</span>
  <span m=''3705990''>as</span> <span m=''3707060''>the</span> <span m=''3707170''>value</span>
  <span m=''3707580''>of</span> <span m=''3707670''>head</span> <span m=''3708840''>is</span>
  <span m=''3709160''>the</span> <span m=''3710070''>pointer</span> <span m=''3710400''>to</span>
  <span m=''3710490''>70,</span> <span m=''3711040''>the</span> <span m=''3711220''>node</span>
  <span m=''3711470''>was</span> <span m=''3711540''>77.</span> <span m=''3713880''>The</span>
  <span m=''3714290''>value</span> <span m=''3714650''>is no longer</span> <span m=''3715090''>the</span>
  <span m=''3715180''>pointer</span> <span m=''3715590''>to</span> <span m=''3715700''>the
  node</span> <span m=''3715880''>of 77.</span> <span m=''3716500''>It''s</span> <span
  m=''3716590''>now</span> <span m=''3716720''>the</span> <span m=''3716860''>pointer</span>
  <span m=''3717210''>to</span> <span m=''3717270''>the</span> <span m=''3717370''>value</span>
  <span m=''3717930''>of</span> <span m=''3718140''>the</span> <span m=''3718350''>node</span>
  <span m=''3718630''>with</span> <span m=''3718770''>81.</span> <span m=''3721430''>So</span>
  <span m=''3721620''>the</span> <span m=''3721730''>compare-and-swap</span> <span
  m=''3722570''>fails.</span> <span m=''3724650''>People</span> <span m=''3724910''>follow</span>
  <span m=''3725220''>that?</span> </p><p><span m=''3726200''>And</span> <span m=''3726340''>so</span>
  <span m=''3726470''>what</span> <span m=''3726640''>does</span> <span m=''3726860''>33</span>
  <span m=''3727360''>have</span> <span m=''3727590''>to</span> <span m=''3727680''>do?</span>
  <span m=''3729420''>It''s</span> <span m=''3729620''>got</span> <span m=''3729740''>to</span>
  <span m=''3729800''>start</span> <span m=''3730150''>again.</span> <span m=''3730910''>So</span>
  <span m=''3731040''>it</span> <span m=''3731130''>goes</span> <span m=''3731350''>back</span>
  <span m=''3731700''>around</span> <span m=''3732020''>the</span> <span m=''3732090''>loop,</span>
  <span m=''3732420''>and</span> <span m=''3732540''>now</span> <span m=''3732760''>it</span>
  <span m=''3732900''>sets</span> <span m=''3733210''>it</span> <span m=''3733300''>to</span>
  <span m=''3733400''>81,</span> <span m=''3733930''>which</span> <span m=''3734090''>is</span>
  <span m=''3734220''>now</span> <span m=''3734450''>the</span> <span m=''3734740''>head.</span>
  <span m=''3735240''>And</span> <span m=''3735380''>now,</span> <span m=''3735610''>it</span>
  <span m=''3735920''>can</span> <span m=''3736230''>compare-and-swap</span> <span
  m=''3737170''>in</span> <span m=''3737960''>the</span> <span m=''3738090''>value.</span>
  <span m=''3738410''>And</span> <span m=''3738520''>they</span> <span m=''3738610''>both</span>
  <span m=''3738920''>get</span> <span m=''3739070''>in</span> <span m=''3739230''>there</span>
  <span m=''3740340''>perfectly</span> <span m=''3740770''>well.</span> <span m=''3742940''>Question?</span>
  </p><p><span m=''3743470''>AUDIENCE: What if</span> <span m=''3743952''>there''s</span>
  <span m=''3744434''>[INAUDIBLE]?</span> <span m=''3744916''>What if</span> <span
  m=''3745398''>two nodes</span> <span m=''3745880''>have--</span> </p><p><span m=''3746850''>PROFESSOR:
  Well,</span> <span m=''3748150''>notice</span> <span m=''3748420''>here,</span>
  <span m=''3748570''>it''s</span> <span m=''3748700''>not</span> <span m=''3749010''>looking</span>
  <span m=''3749360''>at</span> <span m=''3749790''>the</span> <span m=''3750990''>value</span>
  <span m=''3751470''>of</span> <span m=''3751620''>the</span> <span m=''3751720''>data.</span>
  <span m=''3752230''>Nowhere</span> <span m=''3752350''>does</span> <span m=''3752570''>data</span>
  <span m=''3752910''>appear</span> <span m=''3753280''>here.</span> <span m=''3753500''>It''s</span>
  <span m=''3753620''>actually</span> <span m=''3753890''>looking</span> <span m=''3754180''>at</span>
  <span m=''3754280''>the</span> <span m=''3754410''>address</span> <span m=''3754950''>of</span>
  <span m=''3755050''>this</span> <span m=''3755190''>chunk</span> <span m=''3755430''>of</span>
  <span m=''3755490''>memory.</span> <span m=''3757410''>There</span> <span m=''3757540''>is</span>
  <span m=''3757830''>a</span> <span m=''3757880''>similar</span> <span m=''3758380''>problem,</span>
  <span m=''3758850''>which</span> <span m=''3758900''>I</span> <span m=''3759175''>will</span>
  <span m=''3759450''>raise</span> <span m=''3759790''>in</span> <span m=''3759890''>just</span>
  <span m=''3760120''>a</span> <span m=''3760170''>moment.</span> <span m=''3761000''>There</span>
  <span m=''3761160''>is</span> <span m=''3761270''>still</span> <span m=''3761520''>a</span>
  <span m=''3761570''>problem.</span> <span m=''3762620''>Yeah,</span> <span m=''3762830''>question?</span>
  </p><p><span m=''3763720''>AUDIENCE: So</span> <span m=''3764220''>I''m confused</span>
  <span m=''3764720''>about the interface.</span> <span m=''3765220''>So</span> <span
  m=''3765720''>you give</span> <span m=''3766220''>it</span> <span m=''3766720''>the</span>
  <span m=''3766850''>address</span> <span m=''3768180''>of</span> <span m=''3768590''>where</span>
  <span m=''3768740''>you</span> <span m=''3768860''>want</span> <span m=''3769060''>to</span>
  <span m=''3769300''>compare</span> <span m=''3769480''>the value</span> <span m=''3769940''>of.</span>
  <span m=''3770840''>And</span> <span m=''3771258''>you''re</span> <span m=''3771676''>giving
  it</span> <span m=''3772512''>what</span> <span m=''3772930''>you''re</span> <span
  m=''3773350''>pointing at and--</span> </p><p><span m=''3774760''>PROFESSOR: And</span>
  <span m=''3774940''>here''s</span> <span m=''3775210''>the</span> <span m=''3775525''>value</span>
  <span m=''3775840''>that I</span> <span m=''3775980''>expect</span> <span m=''3776500''>to</span>
  <span m=''3776570''>be</span> <span m=''3777060''>stored</span> <span m=''3777660''>in</span>
  <span m=''3777760''>this</span> <span m=''3777960''>location.</span> <span m=''3779160''>The</span>
  <span m=''3779470''>value</span> <span m=''3779850''>I</span> <span m=''3779970''>expect</span>
  <span m=''3780430''>to</span> <span m=''3780530''>be</span> <span m=''3780720''>in
  there</span> <span m=''3781310''>is</span> <span m=''3781540''>node</span> <span
  m=''3781760''>dot</span> <span m=''3782050''>next.</span> <span m=''3783870''>So</span>
  <span m=''3784030''>if</span> <span m=''3784120''>I</span> <span m=''3784160''>go</span>
  <span m=''3784330''>back</span> <span m=''3784820''>a</span> <span m=''3784880''>couple
  things.</span> <span m=''3786500''>Here.</span> </p><p><span m=''3790960''>Here,</span>
  <span m=''3791180''>the</span> <span m=''3791300''>guy</span> <span m=''3791570''>says,</span>
  <span m=''3792030''>the</span> <span m=''3792180''>value</span> <span m=''3792550''>I</span>
  <span m=''3792640''>expect</span> <span m=''3793140''>to</span> <span m=''3793260''>be</span>
  <span m=''3793490''>there</span> <span m=''3794600''>is</span> <span m=''3796080''>in</span>
  <span m=''3796190''>this</span> <span m=''3796370''>case.</span> <span m=''3797470''>the</span>
  <span m=''3797910''>address</span> <span m=''3798430''>of</span> <span m=''3798630''>this</span>
  <span m=''3799020''>chunk</span> <span m=''3799260''>of</span> <span m=''3799320''>memory</span>
  <span m=''3799640''>here.</span> <span m=''3800960''>He</span> <span m=''3801260''>expects</span>
  <span m=''3802390''>the</span> <span m=''3802980''>address</span> <span m=''3803480''>of</span>
  <span m=''3803600''>the</span> <span m=''3803890''>node</span> <span m=''3804230''>containing</span>
  <span m=''3804680''>77</span> <span m=''3805770''>is</span> <span m=''3805970''>going</span>
  <span m=''3806100''>to</span> <span m=''3806170''>be</span> <span m=''3806940''>in</span>
  <span m=''3807130''>this</span> <span m=''3807360''>location.</span> <span m=''3808000''>It''s</span>
  <span m=''3808220''>not.</span> <span m=''3808580''>What''s</span> <span m=''3808890''>in</span>
  <span m=''3809000''>this</span> <span m=''3809140''>location</span> <span m=''3809660''>is</span>
  <span m=''3809790''>the</span> <span m=''3809900''>address</span> <span m=''3810660''>of</span>
  <span m=''3810790''>this</span> <span m=''3810990''>chunk</span> <span m=''3811220''>of</span>
  <span m=''3811270''>memory.</span> </p><p><span m=''3813490''>But</span> <span m=''3813640''>you''re</span>
  <span m=''3813710''>saying,</span> <span m=''3814090''>if it''s</span> <span m=''3814470''>equal</span>
  <span m=''3815440''>to</span> <span m=''3815730''>this,</span> <span m=''3816240''>then</span>
  <span m=''3816440''>you</span> <span m=''3816570''>can</span> <span m=''3816720''>go</span>
  <span m=''3816880''>ahead</span> <span m=''3817080''>and</span> <span m=''3817180''>do</span>
  <span m=''3817250''>the</span> <span m=''3817370''>swap.</span> <span m=''3817720''>Otherwise</span>
  <span m=''3818140''>you''re</span> <span m=''3818230''>going</span> <span m=''3818350''>to</span>
  <span m=''3818400''>fail.</span> <span m=''3819530''>And</span> <span m=''3819650''>the</span>
  <span m=''3819720''>swap</span> <span m=''3820080''>consists</span> <span m=''3820530''>of</span>
  <span m=''3820670''>now</span> <span m=''3820950''>sticking</span> <span m=''3821420''>this</span>
  <span m=''3821680''>value</span> <span m=''3822490''>into--</span> <span m=''3823970''>conditionally</span>
  <span m=''3824600''>sticking</span> <span m=''3824980''>it</span> <span m=''3825080''>in</span>
  <span m=''3825220''>there.</span> <span m=''3825560''>So</span> <span m=''3825720''>you
  either</span> <span m=''3826000''>do</span> <span m=''3826210''>it</span> <span
  m=''3826270''>or</span> <span m=''3826340''>you</span> <span m=''3826520''>don''t</span>
  <span m=''3826710''>do</span> <span m=''3826900''>it.</span> </p><p><span m=''3831810''>So</span>
  <span m=''3832080''>let''s</span> <span m=''3832560''>now</span> <span m=''3832820''>do</span>
  <span m=''3832990''>a</span> <span m=''3833070''>pop.</span> <span m=''3834790''>So</span>
  <span m=''3834960''>pop</span> <span m=''3835320''>you</span> <span m=''3835420''>can</span>
  <span m=''3835560''>also</span> <span m=''3835870''>do</span> <span m=''3836200''>with</span>
  <span m=''3838710''>things.</span> <span m=''3839030''>So</span> <span m=''3839160''>here,</span>
  <span m=''3839390''>I''m</span> <span m=''3839470''>going</span> <span m=''3839610''>to</span>
  <span m=''3839690''>want</span> <span m=''3839910''>to</span> <span m=''3840050''>extract</span>
  <span m=''3842270''>an</span> <span m=''3842590''>element.</span> <span m=''3843510''>And</span>
  <span m=''3843710''>what</span> <span m=''3843820''>I''m</span> <span m=''3843890''>going</span>
  <span m=''3843970''>to</span> <span m=''3844020''>do</span> <span m=''3844310''>is</span>
  <span m=''3844490''>create</span> <span m=''3845300''>a</span> <span m=''3845440''>current</span>
  <span m=''3845820''>value</span> <span m=''3846380''>that</span> <span m=''3846570''>I</span>
  <span m=''3846640''>want</span> <span m=''3846840''>to</span> <span m=''3846900''>make</span>
  <span m=''3847230''>point</span> <span m=''3847600''>to</span> <span m=''3847770''>the</span>
  <span m=''3847910''>element</span> <span m=''3848250''>that</span> <span m=''3848390''>gets</span>
  <span m=''3849860''>eliminated.</span> </p><p><span m=''3851800''>So</span> <span
  m=''3851940''>what</span> <span m=''3852040''>I</span> <span m=''3852120''>do</span>
  <span m=''3852370''>is</span> <span m=''3852510''>I</span> <span m=''3852620''>say,</span>
  <span m=''3852850''>well,</span> <span m=''3853520''>the</span> <span m=''3853610''>element</span>
  <span m=''3854030''>that I</span> <span m=''3854300''>want</span> <span m=''3854600''>is</span>
  <span m=''3854850''>that</span> <span m=''3855100''>guy</span> <span m=''3855330''>there.</span>
  <span m=''3857640''>And</span> <span m=''3857790''>now,</span> <span m=''3858010''>what</span>
  <span m=''3858140''>I</span> <span m=''3858200''>want</span> <span m=''3858970''>to</span>
  <span m=''3859010''>do</span> <span m=''3859290''>is</span> <span m=''3859940''>make</span>
  <span m=''3860250''>the</span> <span m=''3860510''>head</span> <span m=''3860780''>jump</span>
  <span m=''3861020''>around</span> <span m=''3861440''>and</span> <span m=''3861560''>point</span>
  <span m=''3861820''>to</span> <span m=''3861920''>94.</span> <span m=''3864500''>So</span>
  <span m=''3864710''>what</span> <span m=''3864850''>I</span> <span m=''3864940''>do</span>
  <span m=''3865220''>is</span> <span m=''3865470''>I</span> <span m=''3866190''>say,</span>
  <span m=''3866400''>well,</span> <span m=''3866560''>as</span> <span m=''3866680''>long</span>
  <span m=''3867120''>as</span> <span m=''3868030''>the--</span> <span m=''3873110''>and</span>
  <span m=''3873290''>I</span> <span m=''3873320''>want</span> <span m=''3873480''>to</span>
  <span m=''3873520''>do</span> <span m=''3873720''>that</span> <span m=''3873930''>unless</span>
  <span m=''3874380''>I</span> <span m=''3874450''>get</span> <span m=''3874690''>down</span>
  <span m=''3874970''>to</span> <span m=''3875090''>the</span> <span m=''3875180''>fact</span>
  <span m=''3875520''>that</span> <span m=''3875870''>I</span> <span m=''3875990''>have</span>
  <span m=''3876110''>an</span> <span m=''3880380''>empty</span> <span m=''3880680''>list.</span>
  <span m=''3881110''>So</span> <span m=''3881310''>basically,</span> <span m=''3882000''>I</span>
  <span m=''3882160''>say,</span> <span m=''3893340''>if</span> <span m=''3893570''>the</span>
  <span m=''3893910''>head</span> <span m=''3895150''>still</span> <span m=''3895500''>has</span>
  <span m=''3895750''>the</span> <span m=''3895850''>value</span> <span m=''3896300''>of</span>
  <span m=''3896420''>current--</span> <span m=''3897180''>so</span> <span m=''3897380''>they''re</span>
  <span m=''3897490''>pointing</span> <span m=''3897940''>to the</span> <span m=''3897990''>same</span>
  <span m=''3898340''>place--</span> <span m=''3899580''>then,</span> <span m=''3899830''>I</span>
  <span m=''3899930''>want</span> <span m=''3900230''>to</span> <span m=''3900440''>move</span>
  <span m=''3900800''>in</span> <span m=''3901090''>current</span> <span m=''3902650''>arrow</span>
  <span m=''3902940''>next.</span> <span m=''3904680''>And</span> <span m=''3904820''>then</span>
  <span m=''3904940''>I''m</span> <span m=''3905070''>done.</span> </p><p><span m=''3907470''>Otherwise,</span>
  <span m=''3908790''>I</span> <span m=''3908890''>want</span> <span m=''3909150''>to</span>
  <span m=''3910210''>set</span> <span m=''3910585''>current to</span> <span m=''3910960''>head,</span>
  <span m=''3912170''>reset</span> <span m=''3912590''>it,</span> <span m=''3912790''>and</span>
  <span m=''3912940''>go</span> <span m=''3913070''>back</span> <span m=''3913370''>to</span>
  <span m=''3913450''>the</span> <span m=''3913540''>beginning</span> <span m=''3913980''>and</span>
  <span m=''3914090''>try</span> <span m=''3914350''>to</span> <span m=''3914430''>pop</span>
  <span m=''3914740''>again.</span> <span m=''3915550''>And</span> <span m=''3915670''>I''m
  going to</span> <span m=''3915790''>keep</span> <span m=''3916080''>doing</span>
  <span m=''3916400''>that</span> <span m=''3917560''>until</span> <span m=''3917930''>I</span>
  <span m=''3918000''>get</span> <span m=''3918230''>my</span> <span m=''3918370''>pop</span>
  <span m=''3918680''>to</span> <span m=''3918770''>succeed</span> <span m=''3919500''>or</span>
  <span m=''3920380''>until</span> <span m=''3920870''>current</span> <span m=''3921310''>points</span>
  <span m=''3921630''>to</span> <span m=''3921760''>nil.</span> <span m=''3923240''>If</span>
  <span m=''3923320''>it</span> <span m=''3923430''>ended</span> <span m=''3923700''>up</span>
  <span m=''3923920''>at</span> <span m=''3924080''>the</span> <span m=''3924230''>end,</span>
  <span m=''3924520''>then</span> <span m=''3924640''>I</span> <span m=''3924790''>don''t</span>
  <span m=''3924940''>want</span> <span m=''3925080''>to</span> <span m=''3925160''>keep</span>
  <span m=''3925390''>popping</span> <span m=''3926860''>if</span> <span m=''3927530''>the</span>
  <span m=''3928540''>list</span> <span m=''3928860''>ended</span> <span m=''3929030''>up</span>
  <span m=''3929190''>being</span> <span m=''3929400''>empty.</span> <span m=''3931660''>So</span>
  <span m=''3932010''>basically,</span> <span m=''3933020''>it</span> <span m=''3933750''>sets</span>
  <span m=''3934130''>that</span> <span m=''3934370''>one</span> <span m=''3934560''>to</span>
  <span m=''3934640''>jump</span> <span m=''3934930''>over.</span> </p><p><span m=''3936980''>And</span>
  <span m=''3937160''>now,</span> <span m=''3937900''>once</span> <span m=''3938130''>it''s</span>
  <span m=''3938320''>done</span> <span m=''3938540''>that,</span> <span m=''3939050''>I</span>
  <span m=''3939180''>can</span> <span m=''3939420''>go,</span> <span m=''3939640''>and</span>
  <span m=''3939730''>I</span> <span m=''3939790''>can</span> <span m=''3939990''>clean</span>
  <span m=''3940290''>up,</span> <span m=''3940450''>I</span> <span m=''3940510''>can
  get</span> <span m=''3940770''>rid</span> <span m=''3940880''>of</span> <span m=''3940940''>this</span>
  <span m=''3941140''>pointer,</span> <span m=''3941430''>et</span> <span m=''3941520''>cetera.</span>
  <span m=''3941900''>But</span> <span m=''3942140''>nobody</span> <span m=''3942520''>else</span>
  <span m=''3942750''>who''s</span> <span m=''3942890''>coming</span> <span m=''3943160''>in</span>
  <span m=''3943260''>to</span> <span m=''3943360''>use</span> <span m=''3943570''>this</span>
  <span m=''3943730''>link</span> <span m=''3943950''>list,</span> <span m=''3944560''>can</span>
  <span m=''3944660''>see</span> <span m=''3944890''>15</span> <span m=''3945390''>now</span>
  <span m=''3945630''>because</span> <span m=''3945790''>I''m</span> <span m=''3946010''>the</span>
  <span m=''3946160''>only</span> <span m=''3946320''>one</span> <span m=''3946550''>with</span>
  <span m=''3946630''>a</span> <span m=''3947080''>pointer</span> <span m=''3947550''>to
  it.</span> <span m=''3948960''>So</span> <span m=''3949100''>people</span> <span
  m=''3949380''>understand</span> <span m=''3949870''>that?</span> </p><p><span m=''3953930''>So</span>
  <span m=''3954170''>where''s</span> <span m=''3956590''>the</span> <span m=''3956710''>bug?</span>
  <span m=''3960200''>Turns</span> <span m=''3960450''>out</span> <span m=''3960570''>this</span>
  <span m=''3960730''>has</span> <span m=''3960860''>a</span> <span m=''3961145''>but</span>
  <span m=''3962490''>after</span> <span m=''3962740''>all</span> <span m=''3962860''>that</span>
  <span m=''3963040''>work.</span> <span m=''3964990''>Each</span> <span m=''3965230''>of</span>
  <span m=''3965320''>these</span> <span m=''3965570''>individually</span> <span m=''3966730''>does</span>
  <span m=''3967000''>what</span> <span m=''3967140''>it''s</span> <span m=''3967260''>supposed</span>
  <span m=''3967620''>to</span> <span m=''3967690''>do.</span> <span m=''3969330''>But</span>
  <span m=''3969520''>here''s</span> <span m=''3969810''>the</span> <span m=''3969890''>bug.</span>
  <span m=''3970280''>And</span> <span m=''3970410''>it''s</span> <span m=''3970580''>a</span>
  <span m=''3970630''>famous</span> <span m=''3971150''>problem</span> <span m=''3971570''>because</span>
  <span m=''3971810''>you</span> <span m=''3971910''>see</span> <span m=''3972080''>it</span>
  <span m=''3972140''>all</span> <span m=''3972340''>the</span> <span m=''3972420''>time</span>
  <span m=''3973920''>when</span> <span m=''3974180''>people</span> <span m=''3974510''>are</span>
  <span m=''3974880''>synchronizing</span> <span m=''3975390''>through</span> <span
  m=''3975660''>memory</span> <span m=''3976050''>with</span> <span m=''3976690''>lock-free</span>
  <span m=''3977180''>algorithms.</span> <span m=''3978210''>It''s</span> <span m=''3978320''>called</span>
  <span m=''3978760''>the</span> <span m=''3979260''>ABA</span> <span m=''3979590''>problem.</span>
  </p><p><span m=''3982150''>So</span> <span m=''3982270''>here''s</span> <span m=''3982590''>the</span>
  <span m=''3982660''>problem.</span> <span m=''3983040''>And it''s</span> <span m=''3983210''>similar</span>
  <span m=''3983590''>to</span> <span m=''3983670''>what</span> <span m=''3984050''>some</span>
  <span m=''3984210''>people</span> <span m=''3984460''>were</span> <span m=''3984570''>concerned</span>
  <span m=''3984930''>about</span> <span m=''3985350''>earlier.</span> <span m=''3985780''>So</span>
  <span m=''3985990''>here''s</span> <span m=''3986250''>the</span> <span m=''3986370''>ABA</span>
  <span m=''3986800''>problem.</span> <span m=''3988020''>Thread</span> <span m=''3988380''>1</span>
  <span m=''3988650''>begins</span> <span m=''3989070''>to</span> <span m=''3989190''>pop</span>
  <span m=''3990040''>15.</span> <span m=''3991830''>So</span> <span m=''3991980''>imagine</span>
  <span m=''3992410''>that</span> <span m=''3992530''>what</span> <span m=''3992680''>it</span>
  <span m=''3992820''>does</span> <span m=''3993320''>is</span> <span m=''3993740''>it</span>
  <span m=''3994230''>sets</span> <span m=''3996390''>its</span> <span m=''3996650''>current</span>
  <span m=''3997030''>there,</span> <span m=''3998000''>and</span> <span m=''3998170''>then</span>
  <span m=''3998320''>it</span> <span m=''3998500''>reads</span> <span m=''3999270''>the</span>
  <span m=''3999350''>value</span> <span m=''3999810''>here,</span> <span m=''4001040''>and</span>
  <span m=''4001210''>starts</span> <span m=''4001790''>to</span> <span m=''4002310''>set</span>
  <span m=''4003240''>the head here</span> <span m=''4003730''>using</span> <span
  m=''4004070''>the</span> <span m=''4004210''>compare-and-swap.</span> </p><p><span
  m=''4006640''>But</span> <span m=''4006840''>it</span> <span m=''4007010''>doesn''t</span>
  <span m=''4007390''>complete</span> <span m=''4007830''>the</span> <span m=''4007920''>compare-and-swap</span>
  <span m=''4008650''>yet.</span> <span m=''4009040''>The</span> <span m=''4009170''>compare-and-swap</span>
  <span m=''4009710''>hasn''t</span> <span m=''4009990''>executed.</span> <span m=''4010810''>It''s</span>
  <span m=''4010980''>simply</span> <span m=''4011290''>gotten</span> <span m=''4011720''>this</span>
  <span m=''4011940''>value,</span> <span m=''4012660''>and</span> <span m=''4012880''>it''s</span>
  <span m=''4013110''>about</span> <span m=''4013820''>to</span> <span m=''4014050''>swap</span>
  <span m=''4014470''>it here.</span> </p><p><span m=''4015560''>So</span> <span m=''4015690''>then,</span>
  <span m=''4015900''>thread</span> <span m=''4016290''>2</span> <span m=''4016470''>comes</span>
  <span m=''4016750''>along.</span> <span m=''4017110''>And</span> <span m=''4017190''>it</span>
  <span m=''4017350''>says,</span> <span m=''4017590''>oh,</span> <span m=''4017740''>I</span>
  <span m=''4017820''>want</span> <span m=''4017990''>to</span> <span m=''4018040''>pop</span>
  <span m=''4018350''>something</span> <span m=''4018720''>as</span> <span m=''4018840''>well.</span>
  <span m=''4020900''>So</span> <span m=''4021130''>it</span> <span m=''4021720''>comes</span>
  <span m=''4022020''>in.</span> <span m=''4022210''>And</span> <span m=''4022330''>it</span>
  <span m=''4022480''>turns</span> <span m=''4022720''>out</span> <span m=''4022880''>it''s</span>
  <span m=''4023050''>faster,</span> <span m=''4023500''>and</span> <span m=''4023580''>manages</span>
  <span m=''4024000''>to</span> <span m=''4024100''>pop</span> <span m=''4024460''>15</span>
  <span m=''4024920''>off,</span> <span m=''4025360''>and</span> <span m=''4025790''>set</span>
  <span m=''4026060''>up</span> <span m=''4026210''>its</span> <span m=''4026490''>pointers.</span>
  </p><p><span m=''4028680''>Now,</span> <span m=''4028820''>what</span> <span m=''4028950''>would</span>
  <span m=''4029080''>normally</span> <span m=''4029510''>happen</span> <span m=''4029910''>here</span>
  <span m=''4030220''>is</span> <span m=''4030340''>if</span> <span m=''4030470''>this</span>
  <span m=''4030690''>completed,</span> <span m=''4031320''>what</span> <span m=''4031510''>would</span>
  <span m=''4031610''>happen?</span> <span m=''4033520''>The</span> <span m=''4033620''>compare-and-swap</span>
  <span m=''4034420''>instruction</span> <span m=''4034990''>would</span> <span m=''4035130''>discover</span>
  <span m=''4036090''>that</span> <span m=''4036220''>this</span> <span m=''4036460''>pointer</span>
  <span m=''4036900''>is</span> <span m=''4037020''>no</span> <span m=''4037210''>longer</span>
  <span m=''4038170''>the</span> <span m=''4038270''>pointer</span> <span m=''4038760''>to</span>
  <span m=''4039070''>the</span> <span m=''4039220''>head.</span> <span m=''4040630''>And</span>
  <span m=''4040760''>so</span> <span m=''4040950''>it</span> <span m=''4041220''>would</span>
  <span m=''4041490''>fail.</span> <span m=''4041630''>We''d</span> <span m=''4041780''>be
  all</span> <span m=''4042370''>hunky</span> <span m=''4042650''>dory.</span> <span
  m=''4043000''>No</span> <span m=''4043190''>problem.</span> </p><p><span m=''4044160''>But</span>
  <span m=''4044600''>what</span> <span m=''4044830''>could</span> <span m=''4045000''>actually</span>
  <span m=''4045410''>happen</span> <span m=''4045870''>here?</span> <span m=''4046760''>Thread</span>
  <span m=''4047120''>2</span> <span m=''4047380''>keeps</span> <span m=''4047710''>going</span>
  <span m=''4048020''>on.</span> <span m=''4048290''>It</span> <span m=''4048410''>says,</span>
  <span m=''4048620''>oh,</span> <span m=''4048780''>let</span> <span m=''4048930''>me</span>
  <span m=''4049080''>pop</span> <span m=''4049620''>94.</span> <span m=''4051900''>So</span>
  <span m=''4052120''>it</span> <span m=''4052290''>does</span> <span m=''4052540''>the</span>
  <span m=''4052610''>same</span> <span m=''4052920''>thing.</span> <span m=''4054630''>So</span>
  <span m=''4054830''>thread</span> <span m=''4055140''>1</span> <span m=''4055350''>is</span>
  <span m=''4055430''>still</span> <span m=''4055670''>stalled</span> <span m=''4056210''>here,</span>
  <span m=''4056910''>not</span> <span m=''4057120''>having</span> <span m=''4057330''>completed</span>
  <span m=''4057870''>its</span> <span m=''4058240''>compare-and-swap.</span> <span
  m=''4060770''>It swaps</span> <span m=''4061020''>94.</span> </p><p><span m=''4061820''>Then,</span>
  <span m=''4062090''>thread</span> <span m=''4062360''>2</span> <span m=''4062460''>goes
  on</span> <span m=''4062740''>and says,</span> <span m=''4063200''>oh,</span> <span
  m=''4063630''>let''s</span> <span m=''4063840''>put 15</span> <span m=''4064330''>back</span>
  <span m=''4064590''>on.</span> <span m=''4066410''>So</span> <span m=''4066520''>it</span>
  <span m=''4066650''>puts</span> <span m=''4066890''>15</span> <span m=''4067400''>back</span>
  <span m=''4067690''>on</span> <span m=''4067900''>because</span> <span m=''4068070''>after</span>
  <span m=''4068330''>all,</span> <span m=''4068450''>it</span> <span m=''4068530''>had</span>
  <span m=''4068780''>15.</span> <span m=''4070800''>So</span> <span m=''4070940''>now,</span>
  <span m=''4071180''>what</span> <span m=''4071340''>happens</span> <span m=''4071780''>here?</span>
  <span m=''4074570''>Thread</span> <span m=''4075030''>1</span> <span m=''4076020''>now</span>
  <span m=''4076330''>looks,</span> <span m=''4077390''>and</span> <span m=''4077570''>it</span>
  <span m=''4077750''>now</span> <span m=''4078010''>completes,</span> <span m=''4078790''>and</span>
  <span m=''4078990''>does</span> <span m=''4079210''>its</span> <span m=''4079520''>compare-and-swap,</span>
  <span m=''4081140''>it</span> <span m=''4081370''>resumes,</span> <span m=''4087920''>splicing</span>
  <span m=''4088580''>out</span> <span m=''4088770''>15,</span> <span m=''4089200''>which</span>
  <span m=''4089390''>it</span> <span m=''4089510''>thinks</span> <span m=''4089750''>it</span>
  <span m=''4089850''>has.</span> <span m=''4090180''>But</span> <span m=''4090310''>it</span>
  <span m=''4090400''>doesn''t</span> <span m=''4090730''>realize</span> <span m=''4092370''>that</span>
  <span m=''4092820''>other</span> <span m=''4093100''>stuff</span> <span m=''4093450''>has</span>
  <span m=''4093680''>gone</span> <span m=''4093960''>on.</span> <span m=''4094300''>And</span>
  <span m=''4094480''>now,</span> <span m=''4095500''>we''ve</span> <span m=''4095730''>got</span>
  <span m=''4096729''>a</span> <span m=''4096830''>mess.</span> </p><p><span m=''4102380''>So</span>
  <span m=''4102529''>this is</span> <span m=''4102720''>the</span> <span m=''4103060''>ABA</span>
  <span m=''4103390''>problem</span> <span m=''4103710''>because</span> <span m=''4103899''>what</span>
  <span m=''4104050''>happened</span> <span m=''4104529''>was</span> <span m=''4105620''>we</span>
  <span m=''4105750''>were</span> <span m=''4105899''>checking</span> <span m=''4106460''>to</span>
  <span m=''4106580''>see</span> <span m=''4106779''>whether</span> <span m=''4107029''>the</span>
  <span m=''4107180''>value</span> <span m=''4107760''>was</span> <span m=''4107950''>still</span>
  <span m=''4108290''>the</span> <span m=''4108380''>same</span> <span m=''4108840''>value,</span>
  <span m=''4109240''>the</span> <span m=''4109300''>same</span> <span m=''4109600''>chunk</span>
  <span m=''4109880''>of</span> <span m=''4109960''>memory.</span> <span m=''4111260''>It</span>
  <span m=''4111430''>got</span> <span m=''4111729''>popped</span> <span m=''4112040''>off.</span>
  <span m=''4112340''>But</span> <span m=''4112460''>it</span> <span m=''4112670''>got</span>
  <span m=''4112880''>popped back</span> <span m=''4113130''>on.</span> <span m=''4115160''>But</span>
  <span m=''4115310''>now,</span> <span m=''4115590''>it could</span> <span m=''4115729''>be</span>
  <span m=''4115880''>in</span> <span m=''4115979''>any</span> <span m=''4116229''>configuration.</span>
  <span m=''4117800''>We</span> <span m=''4117950''>don''t</span> <span m=''4118160''>know</span>
  <span m=''4118290''>what</span> <span m=''4118460''>it</span> <span m=''4118580''>is.</span>
  <span m=''4118840''>And</span> <span m=''4119100''>now,</span> <span m=''4120100''>the</span>
  <span m=''4120550''>code</span> <span m=''4120850''>is</span> <span m=''4121010''>thinking,</span>
  <span m=''4121950''>that</span> <span m=''4122180''>oh,</span> <span m=''4122380''>nothing</span>
  <span m=''4122729''>happened.</span> <span m=''4123960''>But</span> <span m=''4124090''>in</span>
  <span m=''4124180''>fact,</span> <span m=''4124450''>something</span> <span m=''4124770''>happened.</span>
  </p><p><span m=''4127109''>So</span> <span m=''4127250''>it''s</span> <span m=''4127390''>ABA</span>
  <span m=''4128310''>because</span> <span m=''4128640''>basically,</span> <span m=''4129660''>you''ve</span>
  <span m=''4129819''>got</span> <span m=''4130080''>15</span> <span m=''4130569''>there.</span>
  <span m=''4131050''>It</span> <span m=''4131170''>goes</span> <span m=''4131430''>away.</span>
  <span m=''4131825''>Then,</span> <span m=''4132220''>15</span> <span m=''4132700''>comes</span>
  <span m=''4132960''>back.</span> <span m=''4134029''>Question?</span> </p><p><span
  m=''4136274''>AUDIENCE: Can you</span> <span m=''4136745''>compare</span> <span
  m=''4137216''>two things</span> <span m=''4137687''>and then swap because</span>
  <span m=''4138158''>that would solve this, right?</span> </p><p><span m=''4139100''>PROFESSOR:
  That''s</span> <span m=''4139500''>called</span> <span m=''4139770''>a</span> <span
  m=''4139830''>double</span> <span m=''4140270''>compare-and-swap.</span> <span m=''4143233''>And</span>
  <span m=''4143710''>we''ll</span> <span m=''4144680''>talk</span> <span m=''4144910''>about</span>
  <span m=''4145029''>it in a</span> <span m=''4145160''>second.</span> <span m=''4147689''>So</span>
  <span m=''4148210''>the</span> <span m=''4148420''>classic</span> <span m=''4149020''>way</span>
  <span m=''4149260''>to</span> <span m=''4149359''>solve</span> <span m=''4149819''>this</span>
  <span m=''4150040''>problem</span> <span m=''4152120''>is</span> <span m=''4152340''>to</span>
  <span m=''4152430''>use</span> <span m=''4152899''>versioning.</span> <span m=''4155050''>So</span>
  <span m=''4155200''>what</span> <span m=''4155390''>you</span> <span m=''4155550''>do</span>
  <span m=''4155710''>is</span> <span m=''4155810''>you</span> <span m=''4155920''>pack</span>
  <span m=''4156250''>a</span> <span m=''4156350''>version</span> <span m=''4156859''>number</span>
  <span m=''4157140''>with</span> <span m=''4157310''>each</span> <span m=''4157540''>pointer</span>
  <span m=''4158479''>in</span> <span m=''4158590''>the</span> <span m=''4158660''>same</span>
  <span m=''4159000''>atomically</span> <span m=''4159630''>updatable</span> <span
  m=''4159970''>word.</span> </p><p><span m=''4162180''>So</span> <span m=''4162430''>that</span>
  <span m=''4162689''>when</span> <span m=''4162979''>15</span> <span m=''4163569''>comes</span>
  <span m=''4163939''>back,</span> <span m=''4167940''>you''ve got</span> <span m=''4168390''>the</span>
  <span m=''4168479''>pointer.</span> <span m=''4168840''>But</span> <span m=''4168960''>you</span>
  <span m=''4169060''>also</span> <span m=''4169300''>have</span> <span m=''4169399''>a</span>
  <span m=''4169510''>version</span> <span m=''4170060''>on</span> <span m=''4170210''>that</span>
  <span m=''4170510''>pointer</span> <span m=''4170819''>so</span> <span m=''4171020''>that</span>
  <span m=''4171189''>the</span> <span m=''4171270''>value</span> <span m=''4171770''>has</span>
  <span m=''4172010''>to</span> <span m=''4172090''>be</span> <span m=''4172200''>the</span>
  <span m=''4172290''>same</span> <span m=''4172620''>as</span> <span m=''4172720''>the</span>
  <span m=''4172810''>version</span> <span m=''4173200''>you</span> <span m=''4173420''>had</span>
  <span m=''4174180''>and</span> <span m=''4174340''>not</span> <span m=''4174560''>the</span>
  <span m=''4174649''>value.</span> <span m=''4175399''>What</span> <span m=''4175540''>you</span>
  <span m=''4175790''>do is you</span> <span m=''4175979''>increment</span> <span
  m=''4176259''>the</span> <span m=''4176540''>version</span> <span m=''4176899''>number</span>
  <span m=''4177189''>every</span> <span m=''4177439''>time</span> <span m=''4177729''>the</span>
  <span m=''4177819''>pointer</span> <span m=''4178189''>is</span> <span m=''4178330''>changed.</span>
  <span m=''4180560''>So</span> <span m=''4180710''>you</span> <span m=''4180779''>just</span>
  <span m=''4181250''>do</span> <span m=''4181479''>an</span> <span m=''4181720''>increment.</span>
  <span m=''4182779''>But</span> <span m=''4183040''>you</span> <span m=''4183210''>do</span>
  <span m=''4183340''>the</span> <span m=''4183450''>compare-and-swap</span> <span
  m=''4184490''>on</span> <span m=''4184710''>the</span> <span m=''4184950''>version</span>
  <span m=''4185479''>number</span> <span m=''4186279''>and</span> <span m=''4186710''>the</span>
  <span m=''4186910''>pointer</span> <span m=''4187470''>at</span> <span m=''4187590''>the</span>
  <span m=''4187649''>same</span> <span m=''4187990''>time.</span> </p><p><span m=''4189779''>Now,</span>
  <span m=''4189890''>it</span> <span m=''4190000''>turns</span> <span m=''4190330''>out</span>
  <span m=''4190620''>that</span> <span m=''4190810''>some</span> <span m=''4191310''>architectures</span>
  <span m=''4192080''>actually</span> <span m=''4192410''>have</span> <span m=''4192630''>what''s</span>
  <span m=''4192790''>called</span> <span m=''4193069''>a</span> <span m=''4193149''>double</span>
  <span m=''4193950''>compare-and-swap,</span> <span m=''4195360''>which</span> <span
  m=''4195620''>will</span> <span m=''4195710''>do</span> <span m=''4196020''>compare-and-swap</span>
  <span m=''4196810''>on</span> <span m=''4197030''>two</span> <span m=''4197260''>distinct</span>
  <span m=''4197780''>locations.</span> <span m=''4199320''>And</span> <span m=''4199470''>that</span>
  <span m=''4199700''>simplifies</span> <span m=''4200470''>things</span> <span m=''4200850''>even</span>
  <span m=''4201110''>more</span> <span m=''4201430''>because</span> <span m=''4201710''>it</span>
  <span m=''4201830''>means</span> <span m=''4202060''>you</span> <span m=''4202140''>don''t</span>
  <span m=''4202290''>have</span> <span m=''4202430''>to</span> <span m=''4202530''>pack</span>
  <span m=''4203390''>and</span> <span m=''4203540''>make</span> <span m=''4203720''>sure</span>
  <span m=''4203910''>that</span> <span m=''4204050''>things</span> <span m=''4204570''>fit
  in</span> <span m=''4204940''>one</span> <span m=''4205170''>word.</span> <span
  m=''4205420''>You</span> <span m=''4205500''>can</span> <span m=''4205650''>keep</span>
  <span m=''4205870''>versioning</span> <span m=''4206330''>elsewhere.</span> <span
  m=''4206990''>And</span> <span m=''4207130''>there</span> <span m=''4207210''>are</span>
  <span m=''4207280''>a</span> <span m=''4207300''>whole</span> <span m=''4207510''>bunch</span>
  <span m=''4207730''>of</span> <span m=''4207850''>other</span> <span m=''4208020''>places</span>
  <span m=''4208510''>where</span> <span m=''4209330''>you</span> <span m=''4209480''>can,</span>
  <span m=''4209620''>in</span> <span m=''4209730''>fact,</span> <span m=''4210110''>optimize</span>
  <span m=''4210445''>and</span> <span m=''4210780''>get</span> <span m=''4210920''>even</span>
  <span m=''4211260''>tighter</span> <span m=''4211660''>code</span> <span m=''4212010''>than</span>
  <span m=''4212130''>you</span> <span m=''4212240''>could</span> <span m=''4212590''>if</span>
  <span m=''4212700''>you</span> <span m=''4212780''>have</span> <span m=''4212980''>to</span>
  <span m=''4213080''>pack.</span> </p><p><span m=''4214990''>So</span> <span m=''4215110''>that''s</span>
  <span m=''4215340''>generally</span> <span m=''4215750''>the</span> <span m=''4215850''>way</span>
  <span m=''4216090''>you</span> <span m=''4216230''>solve</span> <span m=''4216650''>this.</span>
  <span m=''4216910''>And,</span> <span m=''4217000''>of</span> <span m=''4217070''>course,</span>
  <span m=''4217260''>you</span> <span m=''4217330''>can</span> <span m=''4217460''>see</span>
  <span m=''4217680''>this</span> <span m=''4217860''>gets--</span> <span m=''4219730''>as</span>
  <span m=''4219970''>I</span> <span m=''4220000''>say,</span> <span m=''4221710''>this</span>
  <span m=''4221930''>week</span> <span m=''4222190''>has</span> <span m=''4222360''>been</span>
  <span m=''4222520''>skull</span> <span m=''4222820''>and</span> <span m=''4222930''>cross</span>
  <span m=''4223280''>bones</span> <span m=''4224000''>lecture.</span> <span m=''4224310''>It''s</span>
  <span m=''4224440''>appropriate</span> <span m=''4224705''>it</span> <span m=''4224970''>comes</span>
  <span m=''4225180''>right</span> <span m=''4225360''>after</span> <span m=''4225620''>Halloween</span>
  <span m=''4228060''>because</span> <span m=''4228920''>really,</span> <span m=''4229460''>you</span>
  <span m=''4229720''>do</span> <span m=''4229920''>not</span> <span m=''4230170''>want</span>
  <span m=''4230310''>to</span> <span m=''4230360''>play</span> <span m=''4230600''>these</span>
  <span m=''4230860''>games</span> <span m=''4231260''>unless</span> <span m=''4231650''>you</span>
  <span m=''4231720''>have</span> <span m=''4232040''>to.</span> </p><p><span m=''4232740''>But</span>
  <span m=''4232880''>you</span> <span m=''4232970''>should</span> <span m=''4233140''>know</span>
  <span m=''4233290''>about</span> <span m=''4233600''>them</span> <span m=''4233710''>because</span>
  <span m=''4233970''>you</span> <span m=''4234080''>will</span> <span m=''4234350''>find</span>
  <span m=''4234720''>times</span> <span m=''4235320''>where</span> <span m=''4236150''>you</span>
  <span m=''4236270''>need</span> <span m=''4236670''>this,</span> <span m=''4236950''>or</span>
  <span m=''4237120''>you</span> <span m=''4237220''>need</span> <span m=''4237410''>to</span>
  <span m=''4237500''>understand</span> <span m=''4238210''>somebody''s</span> <span
  m=''4238680''>code</span> <span m=''4239000''>that</span> <span m=''4239130''>they''ve</span>
  <span m=''4239320''>written</span> <span m=''4239630''>in a</span> <span m=''4239700''>lock-free</span>
  <span m=''4240010''>way.</span> <span m=''4240720''>Because</span> <span m=''4240990''>remember</span>
  <span m=''4241330''>lock-free</span> <span m=''4241820''>has</span> <span m=''4241940''>the</span>
  <span m=''4242060''>nice</span> <span m=''4242330''>property</span> <span m=''4243140''>that</span>
  <span m=''4243270''>hey,</span> <span m=''4243810''>the</span> <span m=''4243910''>operating</span>
  <span m=''4244260''>system</span> <span m=''4245060''>swaps</span> <span m=''4245400''>something</span>
  <span m=''4245800''>out,</span> <span m=''4246510''>it</span> <span m=''4246680''>just</span>
  <span m=''4246870''>keeps</span> <span m=''4247080''>running</span> <span m=''4247470''>nice</span>
  <span m=''4248400''>and</span> <span m=''4248940''>jolly</span> <span m=''4249670''>if</span>
  <span m=''4249870''>it''s</span> <span m=''4250050''>correct.</span> </p><p><span
  m=''4254300''>So</span> <span m=''4255510''>the</span> <span m=''4255660''>other</span>
  <span m=''4255920''>issue</span> <span m=''4256170''>is</span> <span m=''4256290''>that</span>
  <span m=''4256370''>version</span> <span m=''4256830''>numbers</span> <span m=''4257160''>may</span>
  <span m=''4257340''>need</span> <span m=''4257550''>to</span> <span m=''4257600''>be</span>
  <span m=''4257750''>very</span> <span m=''4258080''>large.</span> <span m=''4260170''>So</span>
  <span m=''4260320''>if</span> <span m=''4260380''>you</span> <span m=''4260550''>have</span>
  <span m=''4260730''>a</span> <span m=''4260780''>version</span> <span m=''4261140''>number,</span>
  <span m=''4261340''>how</span> <span m=''4261500''>many</span> <span m=''4261670''>bits</span>
  <span m=''4262000''>to</span> <span m=''4262070''>you</span> <span m=''4262170''>assign</span>
  <span m=''4262540''>to that</span> <span m=''4262740''>version</span> <span m=''4263120''>number.</span>
  <span m=''4263970''>Well,</span> <span m=''4264100''>64</span> <span m=''4264750''>bits,</span>
  <span m=''4265060''>that''s</span> <span m=''4265330''>no</span> <span m=''4265440''>problem.</span>
  <span m=''4265810''>You never</span> <span m=''4266190''>run</span> <span m=''4266420''>out</span>
  <span m=''4266540''>of</span> <span m=''4266600''>64</span> <span m=''4266960''>bits.</span>
  <span m=''4267930''>2</span> <span m=''4268090''>to the</span> <span m=''4268270''>64th</span>
  <span m=''4268970''>is</span> <span m=''4269120''>a</span> <span m=''4269250''>very,</span>
  <span m=''4269670''>very,</span> <span m=''4269980''>very</span> <span m=''4270280''>big</span>
  <span m=''4270510''>number.</span> <span m=''4271390''>And</span> <span m=''4271530''>you''ll</span>
  <span m=''4271670''>never</span> <span m=''4271980''>run</span> <span m=''4272170''>out</span>
  <span m=''4272430''>of</span> <span m=''4272550''>2 to the</span> <span m=''4272650''>64th.</span>
  </p><p><span m=''4273400''>We</span> <span m=''4273550''>did</span> <span m=''4273710''>that</span>
  <span m=''4273890''>calculation</span> <span m=''4274180''>at the</span> <span m=''4274470''>beginning</span>
  <span m=''4274720''>of the</span> <span m=''4274840''>term.</span> <span m=''4275370''>How</span>
  <span m=''4275500''>big</span> <span m=''4275700''>did</span> <span m=''4275790''>we</span>
  <span m=''4275900''>say</span> <span m=''4276080''>it</span> <span m=''4276150''>was?</span>
  <span m=''4282240''>It''s</span> <span m=''4282400''>pretty</span> <span m=''4282610''>big,</span>
  <span m=''4282950''>right?</span> <span m=''4283940''>It''s</span> <span m=''4284930''>like</span>
  <span m=''4285150''>this</span> <span m=''4285552''>big.</span> <span m=''4286758''>Or
  is it</span> <span m=''4287160''>this</span> <span m=''4287470''>big?</span> <span
  m=''4289740''>My</span> <span m=''4289880''>two-year-old</span> <span m=''4290830''>is</span>
  <span m=''4291225''>this</span> <span m=''4291620''>big.</span> </p><p><span m=''4294810''>So</span>
  <span m=''4295250''>anyway,</span> <span m=''4296280''>it''s</span> <span m=''4296840''>pretty</span>
  <span m=''4297000''>big.</span> <span m=''4297200''>So</span> <span m=''4297390''>is
  it</span> <span m=''4297560''>bigger</span> <span m=''4297940''>than--</span> <span
  m=''4299340''>no,</span> <span m=''4299490''>it''s</span> <span m=''4299640''>not</span>
  <span m=''4299880''>bigger</span> <span m=''4300170''>than</span> <span m=''4300480''>the</span>
  <span m=''4300560''>number</span> <span m=''4300940''>of</span> <span m=''4301000''>particles</span>
  <span m=''4301480''>in</span> <span m=''4301520''>the</span> <span m=''4301570''>universe,</span>
  <span m=''4301960''>right?</span> <span m=''4302230''>That''s</span> <span m=''4302480''>10</span>
  <span m=''4302680''>to</span> <span m=''4302740''>the</span> <span m=''4302880''>80th,</span>
  <span m=''4304490''>which</span> <span m=''4304760''>is</span> <span m=''4305020''>much</span>
  <span m=''4305270''>bigger</span> <span m=''4305540''>than</span> <span m=''4305820''>2
  to the 64th.</span> <span m=''4306690''>But</span> <span m=''4306820''>it''s</span>
  <span m=''4306930''>still</span> <span m=''4307600''>a</span> <span m=''4307690''>big</span>
  <span m=''4307880''>number.</span> <span m=''4308280''>I think it''s</span> <span
  m=''4308560''>like</span> <span m=''4308750''>more</span> <span m=''4308990''>than</span>
  <span m=''4309150''>there</span> <span m=''4309290''>are</span> <span m=''4309450''>atoms</span>
  <span m=''4309780''>in</span> <span m=''4309850''>the</span> <span m=''4309970''>earth</span>
  <span m=''4310180''>or</span> <span m=''4310250''>something.</span> <span m=''4310610''>It''s</span>
  <span m=''4310730''>still</span> <span m=''4310950''>pretty</span> <span m=''4311150''>big.</span>
  <span m=''4312430''>You</span> <span m=''4312580''>never</span> <span m=''4312880''>get</span>
  <span m=''4313100''>through</span> <span m=''4313330''>it</span> <span m=''4313420''>if</span>
  <span m=''4313510''>you</span> <span m=''4313610''>calculate</span> <span m=''4313900''>it.</span>
  <span m=''4314060''>I</span> <span m=''4314130''>think</span> <span m=''4314310''>we</span>
  <span m=''4314420''>calculated</span> <span m=''4314620''>it</span> <span m=''4314800''>and</span>
  <span m=''4315430''>it was</span> <span m=''4315780''>hundreds</span> <span m=''4316110''>of</span>
  <span m=''4316150''>years</span> <span m=''4316380''>or</span> <span m=''4316440''>whatever.</span>
  </p><p><span m=''4317320''>Anyway,</span> <span m=''4317950''>it''s</span> <span
  m=''4318310''>a</span> <span m=''4318370''>long</span> <span m=''4318640''>time.</span>
  <span m=''4319670''>Many,</span> <span m=''4319920''>many,</span> <span m=''4320090''>many</span>
  <span m=''4320350''>years</span> <span m=''4320910''>at</span> <span m=''4321150''>the</span>
  <span m=''4321220''>very</span> <span m=''4321520''>fastest,</span> <span m=''4322610''>updating</span>
  <span m=''4323110''>with</span> <span m=''4323230''>biggest</span> <span m=''4323570''>supercomputers,</span>
  <span m=''4324420''>and</span> <span m=''4324490''>the</span> <span m=''4324560''>most</span>
  <span m=''4324880''>processors,</span> <span m=''4325210''>et cetera.</span> <span
  m=''4325860''>Never run out</span> <span m=''4326480''>of</span> <span m=''4327170''>64
  bits.</span> <span m=''4327806''>32 bits.</span> <span m=''4329250''>Four</span>
  <span m=''4329470''>billion.</span> <span m=''4330810''>Maybe</span> <span m=''4331250''>you
  run</span> <span m=''4331470''>out.</span> <span m=''4331650''>Maybe</span> <span
  m=''4331880''>you</span> <span m=''4332040''>don''t.</span> </p><p><span m=''4333570''>So</span>
  <span m=''4334190''>that''s</span> <span m=''4334450''>one</span> <span m=''4334560''>of</span>
  <span m=''4334600''>the</span> <span m=''4334750''>issues.</span> <span m=''4335070''>You</span>
  <span m=''4335170''>have</span> <span m=''4335320''>to</span> <span m=''4335400''>say,</span>
  <span m=''4335630''>well,</span> <span m=''4335750''>how</span> <span m=''4336020''>often</span>
  <span m=''4336350''>do</span> <span m=''4336460''>I</span> <span m=''4336560''>have</span>
  <span m=''4336690''>to</span> <span m=''4336770''>do</span> <span m=''4336890''>that.</span>
  <span m=''4338370''>Really,</span> <span m=''4338770''>you only</span> <span m=''4339000''>have</span>
  <span m=''4339190''>to</span> <span m=''4339310''>worry</span> <span m=''4339570''>about</span>
  <span m=''4339860''>this.</span> <span m=''4340020''>You</span> <span m=''4340130''>can</span>
  <span m=''4340270''>wraparound.</span> <span m=''4342160''>But</span> <span m=''4342360''>you''ve</span>
  <span m=''4342460''>got</span> <span m=''4342580''>to</span> <span m=''4342650''>make</span>
  <span m=''4342850''>sure</span> <span m=''4343320''>that</span> <span m=''4343590''>then</span>
  <span m=''4344310''>you</span> <span m=''4344420''>never</span> <span m=''4344750''>have</span>
  <span m=''4344830''>a</span> <span m=''4344880''>situation</span> <span m=''4345670''>where</span>
  <span m=''4347040''>something</span> <span m=''4347650''>could</span> <span m=''4347790''>be</span>
  <span m=''4347910''>swapped</span> <span m=''4348360''>out</span> <span m=''4348650''>for</span>
  <span m=''4348760''>long</span> <span m=''4349110''>enough</span> <span m=''4349380''>that</span>
  <span m=''4349480''>it</span> <span m=''4349560''>would</span> <span m=''4349700''>come</span>
  <span m=''4349900''>back</span> <span m=''4350290''>and</span> <span m=''4351230''>bite</span>
  <span m=''4351730''>you</span> <span m=''4352620''>because</span> <span m=''4352820''>you''re</span>
  <span m=''4352920''>coming</span> <span m=''4353130''>around</span> <span m=''4353490''>and
  then</span> <span m=''4353960''>eating</span> <span m=''4354170''>your</span> <span
  m=''4354310''>tail.</span> <span m=''4354640''>And you''ve</span> <span m=''4354770''>got</span>
  <span m=''4354930''>to make</span> <span m=''4355100''>sure</span> <span m=''4355790''>you</span>
  <span m=''4355900''>wouldn''t</span> <span m=''4356110''>have</span> <span m=''4356310''>things</span>
  <span m=''4356540''>overlap</span> <span m=''4357140''>and</span> <span m=''4357300''>get</span>
  <span m=''4357500''>a</span> <span m=''4357785''>[? thing. ?]</span> </p><p><span
  m=''4358070''>So</span> <span m=''4358670''>that</span> <span m=''4358860''>might</span>
  <span m=''4359110''>be</span> <span m=''4359240''>a</span> <span m=''4359300''>risk</span>
  <span m=''4359580''>you''re</span> <span m=''4359690''>willing</span> <span m=''4359970''>to</span>
  <span m=''4360080''>take.</span> <span m=''4360580''>You</span> <span m=''4361010''>can</span>
  <span m=''4361160''>do</span> <span m=''4361310''>an</span> <span m=''4361380''>analysis</span>
  <span m=''4361980''>and</span> <span m=''4362100''>say,</span> <span m=''4362260''>what</span>
  <span m=''4362420''>are</span> <span m=''4362440''>the</span> <span m=''4362580''>odds</span>
  <span m=''4362820''>my</span> <span m=''4363240''>system</span> <span m=''4363600''>crashes</span>
  <span m=''4365200''>from</span> <span m=''4365400''>this</span> <span m=''4365600''>reason</span>
  <span m=''4365960''>or</span> <span m=''4366090''>from</span> <span m=''4366270''>a</span>
  <span m=''4366330''>different</span> <span m=''4366630''>reason?</span> <span m=''4368010''>That</span>
  <span m=''4368170''>can</span> <span m=''4368320''>be</span> <span m=''4368470''>reasonable</span>
  <span m=''4369110''>engineering</span> <span m=''4369530''>trade-off.</span> </p><p><span
  m=''4371560''>So</span> <span m=''4372660''>there''s</span> <span m=''4372860''>an</span>
  <span m=''4372920''>alternative</span> <span m=''4373660''>to</span> <span m=''4373760''>compare-and-swap.</span>
  <span m=''4374460''>One</span> <span m=''4374620''>is</span> <span m=''4374790''>the</span>
  <span m=''4374890''>double</span> <span m=''4375540''>compare-and-swap.</span> <span
  m=''4376430''>Another</span> <span m=''4376730''>one</span> <span m=''4377360''>is</span>
  <span m=''4377530''>some</span> <span m=''4377770''>machines</span> <span m=''4378220''>have</span>
  <span m=''4378580''>what''s</span> <span m=''4378770''>called</span> <span m=''4379060''>a</span>
  <span m=''4379170''>load-linked,</span> <span m=''4380050''>store</span> <span m=''4380470''>conditional</span>
  <span m=''4381070''>instruction.</span> </p><p><span m=''4382300''>What those are</span>
  <span m=''4382850''>actually</span> <span m=''4383280''>is a</span> <span m=''4383360''>pair</span>
  <span m=''4383720''>of</span> <span m=''4383800''>instructions.</span> <span m=''4384620''>One</span>
  <span m=''4384810''>is</span> <span m=''4384930''>load-linked.</span> <span m=''4385870''>When</span>
  <span m=''4386080''>you</span> <span m=''4386210''>load-linked,</span> <span m=''4387500''>it</span>
  <span m=''4387640''>basically</span> <span m=''4388150''>says,</span> <span m=''4389240''>let''s</span>
  <span m=''4389530''>set</span> <span m=''4389750''>a</span> <span m=''4389800''>bit,</span>
  <span m=''4390190''>essentially,</span> <span m=''4390700''>in that</span> <span
  m=''4390740''>word.</span> <span m=''4391950''>And</span> <span m=''4392070''>if</span>
  <span m=''4392180''>that</span> <span m=''4392450''>word</span> <span m=''4392630''>ever</span>
  <span m=''4392930''>changes</span> <span m=''4394310''>when</span> <span m=''4394450''>you</span>
  <span m=''4394560''>do</span> <span m=''4394740''>store</span> <span m=''4395150''>conditional,</span>
  <span m=''4396870''>it</span> <span m=''4396990''>will</span> <span m=''4397120''>fail.</span>
  </p><p><span m=''4398770''>So</span> <span m=''4398950''>even</span> <span m=''4399240''>if</span>
  <span m=''4399970''>some</span> <span m=''4400190''>other</span> <span m=''4400410''>processor</span>
  <span m=''4400970''>changes</span> <span m=''4401460''>it</span> <span m=''4401610''>to</span>
  <span m=''4401750''>the</span> <span m=''4401870''>exact</span> <span m=''4402380''>same</span>
  <span m=''4402740''>value,</span> <span m=''4404050''>it''s</span> <span m=''4404230''>keeping</span>
  <span m=''4404580''>track</span> <span m=''4405040''>of</span> <span m=''4405130''>whether</span>
  <span m=''4405420''>anybody</span> <span m=''4405840''>else</span> <span m=''4406030''>wrote</span>
  <span m=''4406320''>it</span> <span m=''4406460''>using</span> <span m=''4406990''>the</span>
  <span m=''4407510''>memory</span> <span m=''4407810''>consistency</span> <span m=''4408430''>mechanism.</span>
  <span m=''4409490''>The</span> <span m=''4409640''>MSI</span> <span m=''4410380''>type</span>
  <span m=''4410650''>protocol</span> <span m=''4411080''>that</span> <span m=''4411170''>we</span>
  <span m=''4411270''>talked</span> <span m=''4411580''>about.</span> <span m=''4411870''>It''s</span>
  <span m=''4412110''>using</span> <span m=''4412390''>that</span> <span m=''4412610''>kind</span>
  <span m=''4412730''>of</span> <span m=''4412850''>mechanism</span> <span m=''4413720''>to</span>
  <span m=''4413840''>make</span> <span m=''4414060''>sure</span> <span m=''4415650''>that</span>
  <span m=''4415910''>if</span> <span m=''4416060''>it</span> <span m=''4416150''>changes.</span>
  <span m=''4416530''>And</span> <span m=''4416660''>so</span> <span m=''4416790''>this</span>
  <span m=''4417050''>is</span> <span m=''4417200''>actually</span> <span m=''4417570''>much</span>
  <span m=''4417890''>more</span> <span m=''4418120''>reliable</span> <span m=''4418750''>as</span>
  <span m=''4418850''>a</span> <span m=''4418900''>mechanism.</span> <span m=''4421800''>x86</span>
  <span m=''4422230''>does</span> <span m=''4422390''>not</span> <span m=''4422600''>have</span>
  <span m=''4422770''>load-linked,</span> <span m=''4423120''>store</span> <span m=''4423410''>conditional.</span>
  <span m=''4426060''>I''m</span> <span m=''4426290''>not</span> <span m=''4426480''>sure</span>
  <span m=''4426650''>why.</span> <span m=''4426930''>I</span> <span m=''4426970''>don''t</span>
  <span m=''4427100''>know</span> <span m=''4427160''>if</span> <span m=''4427260''>there''s</span>
  <span m=''4427410''>a</span> <span m=''4427450''>patent</span> <span m=''4427870''>on</span>
  <span m=''4428050''>it</span> <span m=''4428160''>or</span> <span m=''4428730''>what''s</span>
  <span m=''4429010''>going</span> <span m=''4429220''>on.</span> <span m=''4429300''>But</span>
  <span m=''4429410''>they</span> <span m=''4429520''>don''t</span> <span m=''4429700''>have</span>
  <span m=''4429810''>it.</span> </p><p><span m=''4435630''>Final</span> <span m=''4436040''>topic</span>
  <span m=''4436770''>is</span> <span m=''4437170''>reducers.</span> <span m=''4440650''>So</span>
  <span m=''4440880''>once</span> <span m=''4441100''>again,</span> <span m=''4441350''>recall</span>
  <span m=''4441770''>the</span> <span m=''4441840''>summing</span> <span m=''4442210''>problem.</span>
  <span m=''4446140''>In</span> <span m=''4447030''>Cilk++,</span> <span m=''4447680''>they</span>
  <span m=''4447880''>have</span> <span m=''4448090''>a</span> <span m=''4448150''>mechanism</span>
  <span m=''4448830''>called</span> <span m=''4449470''>reducer</span> <span m=''4449830''>hyperobjects,</span>
  <span m=''4451070''>which</span> <span m=''4451990''>lets</span> <span m=''4452200''>you</span>
  <span m=''4452300''>do</span> <span m=''4452620''>an</span> <span m=''4452970''>end
  run</span> <span m=''4453630''>around</span> <span m=''4454830''>some</span> <span
  m=''4455100''>of</span> <span m=''4455150''>these</span> <span m=''4455280''>synchronization</span>
  <span m=''4456040''>problems.</span> <span m=''4457610''>And</span> <span m=''4457700''>the</span>
  <span m=''4457760''>basic</span> <span m=''4458150''>idea</span> <span m=''4458510''>behind</span>
  <span m=''4459060''>it</span> <span m=''4459300''>is</span> <span m=''4460250''>we</span>
  <span m=''4460520''>actually</span> <span m=''4461000''>could</span> <span m=''4461200''>code</span>
  <span m=''4461620''>this</span> <span m=''4462420''>fairly</span> <span m=''4462800''>easily</span>
  <span m=''4463220''>as</span> <span m=''4463340''>we</span> <span m=''4463440''>talked</span>
  <span m=''4463700''>about</span> <span m=''4463930''>last</span> <span m=''4464280''>time</span>
  <span m=''4464490''>by</span> <span m=''4464630''>just</span> <span m=''4464870''>doing</span>
  <span m=''4465110''>divide</span> <span m=''4465490''>and</span> <span m=''4465580''>conquer</span>
  <span m=''4467170''>on</span> <span m=''4467410''>the</span> <span m=''4467560''>array.</span>
  </p><p><span m=''4468110''>We</span> <span m=''4468280''>add</span> <span m=''4468580''>up</span>
  <span m=''4468750''>the</span> <span m=''4468820''>first</span> <span m=''4469150''>half</span>
  <span m=''4469390''>of</span> <span m=''4469430''>the</span> <span m=''4469540''>elements,</span>
  <span m=''4470440''>add</span> <span m=''4470640''>up</span> <span m=''4470770''>the</span>
  <span m=''4470830''>second</span> <span m=''4471140''>half</span> <span m=''4471360''>of</span>
  <span m=''4471400''>the</span> <span m=''4471530''>elements,</span> <span m=''4471870''>when</span>
  <span m=''4472010''>they</span> <span m=''4472120''>return,</span> <span m=''4472520''>add</span>
  <span m=''4472780''>them</span> <span m=''4472910''>together.</span> <span m=''4473810''>But</span>
  <span m=''4474070''>the</span> <span m=''4474140''>problem</span> <span m=''4474500''>is</span>
  <span m=''4474620''>that</span> <span m=''4474740''>coding</span> <span m=''4475200''>that</span>
  <span m=''4475400''>is</span> <span m=''4475510''>a</span> <span m=''4475560''>pain</span>
  <span m=''4477120''>to</span> <span m=''4477460''>do.</span> <span m=''4478120''>So</span>
  <span m=''4478310''>the</span> <span m=''4478390''>hyper</span> <span m=''4478800''>object</span>
  <span m=''4479170''>mechanism</span> <span m=''4479920''>sort</span> <span m=''4480140''>of</span>
  <span m=''4480250''>does</span> <span m=''4480520''>that</span> <span m=''4480770''>automatically</span>
  <span m=''4481500''>for</span> <span m=''4481750''>you.</span> </p><p><span m=''4482660''>What</span>
  <span m=''4482930''>you</span> <span m=''4483100''>can</span> <span m=''4483280''>do</span>
  <span m=''4483520''>is</span> <span m=''4483680''>declare</span> <span m=''4485220''>result</span>
  <span m=''4486360''>to</span> <span m=''4486480''>be</span> <span m=''4487100''>an</span>
  <span m=''4488520''>integer,</span> <span m=''4489850''>which</span> <span m=''4490350''>is</span>
  <span m=''4490590''>going</span> <span m=''4490830''>to</span> <span m=''4490910''>have</span>
  <span m=''4492640''>the</span> <span m=''4492770''>operation</span> <span m=''4493400''>add</span>
  <span m=''4493910''>performed</span> <span m=''4494460''>on</span> <span m=''4494600''>it.</span>
  <span m=''4496530''>And</span> <span m=''4496790''>what</span> <span m=''4496940''>happens</span>
  <span m=''4497400''>then</span> <span m=''4497580''>is</span> <span m=''4497730''>you</span>
  <span m=''4497880''>can</span> <span m=''4498290''>just</span> <span m=''4498500''>go</span>
  <span m=''4498650''>ahead</span> <span m=''4499080''>and</span> <span m=''4499200''>add</span>
  <span m=''4499700''>the</span> <span m=''4499780''>values</span> <span m=''4500360''>up</span>
  <span m=''4501360''>like</span> <span m=''4501600''>this.</span> <span m=''4503730''>And</span>
  <span m=''4504130''>basically,</span> <span m=''4505800''>what</span> <span m=''4506000''>it</span>
  <span m=''4506130''>does</span> <span m=''4506460''>is</span> <span m=''4506770''>essentially</span>
  <span m=''4507380''>adds</span> <span m=''4507780''>things</span> <span m=''4508060''>locally</span>
  <span m=''4509130''>and</span> <span m=''4509270''>will</span> <span m=''4509420''>combine</span>
  <span m=''4509940''>them</span> <span m=''4510620''>on</span> <span m=''4510770''>an</span>
  <span m=''4510870''>as</span> <span m=''4511190''>needed</span> <span m=''4511490''>basis.</span>
  <span m=''4512090''>So you</span> <span m=''4512230''>don''t</span> <span m=''4512390''>actually</span>
  <span m=''4512680''>have</span> <span m=''4512880''>to</span> <span m=''4513080''>do</span>
  <span m=''4513370''>any</span> <span m=''4513570''>synchronization</span> <span
  m=''4514320''>at</span> <span m=''4514400''>all.</span> <span m=''4515210''>In</span>
  <span m=''4515380''>the</span> <span m=''4515630''>end,</span> <span m=''4515890''>you</span>
  <span m=''4516020''>have</span> <span m=''4516200''>to</span> <span m=''4516390''>get</span>
  <span m=''4516650''>the</span> <span m=''4516750''>result</span> <span m=''4517700''>by</span>
  <span m=''4517860''>doing</span> <span m=''4518150''>a</span> <span m=''4518260''>get</span>
  <span m=''4518460''>value.</span> </p><p><span m=''4518810''>So</span> <span m=''4519030''>let</span>
  <span m=''4519210''>me</span> <span m=''4520000''>show</span> <span m=''4520310''>you</span>
  <span m=''4520590''>a</span> <span m=''4520690''>little</span> <span m=''4520830''>bit</span>
  <span m=''4521000''>more</span> <span m=''4521210''>what''s</span> <span m=''4521450''>going</span>
  <span m=''4521710''>on</span> <span m=''4522980''>in</span> <span m=''4523150''>this</span>
  <span m=''4523650''>situation.</span> <span m=''4524250''>So</span> <span m=''4524880''>the</span>
  <span m=''4524980''>first</span> <span m=''4525280''>thing</span> <span m=''4525410''>here</span>
  <span m=''4525630''>is</span> <span m=''4525720''>we''re</span> <span m=''4525830''>saying</span>
  <span m=''4526450''>result</span> <span m=''4527250''>is</span> <span m=''4527550''>a</span>
  <span m=''4527690''>summing</span> <span m=''4528180''>reducer</span> <span m=''4528760''>over</span>
  <span m=''4529070''>int.</span> <span m=''4532430''>The</span> <span m=''4532560''>updates
  are</span> <span m=''4532970''>resolved</span> <span m=''4533420''>automatically</span>
  <span m=''4534160''>without</span> <span m=''4534550''>races</span> <span m=''4535250''>or</span>
  <span m=''4535480''>contention</span> <span m=''4536780''>because</span> <span m=''4537050''>they''re</span>
  <span m=''4537150''>basically</span> <span m=''4537880''>doing</span> <span m=''4538190''>it</span>
  <span m=''4538670''>by</span> <span m=''4538840''>keeping</span> <span m=''4539380''>local</span>
  <span m=''4539810''>values</span> <span m=''4540400''>and</span> <span m=''4540990''>copying</span>
  <span m=''4541430''>them.</span> <span m=''4542200''>And</span> <span m=''4542440''>then,</span>
  <span m=''4542640''>at</span> <span m=''4542760''>the</span> <span m=''4542890''>end,</span>
  <span m=''4543170''>you</span> <span m=''4543300''>can</span> <span m=''4543480''>get</span>
  <span m=''4543670''>the</span> <span m=''4543800''>underlying</span> <span m=''4544290''>value.</span>
  </p><p><span m=''4547610''>So</span> <span m=''4547730''>the</span> <span m=''4547810''>way</span>
  <span m=''4548040''>this</span> <span m=''4548250''>works</span> <span m=''4548860''>is</span>
  <span m=''4549300''>that</span> <span m=''4549940''>when</span> <span m=''4550250''>you</span>
  <span m=''4550350''>declare</span> <span m=''4551380''>the</span> <span m=''4551570''>variable,</span>
  <span m=''4552240''>you''re</span> <span m=''4552380''>declaring</span> <span m=''4552850''>it
  as a</span> <span m=''4553030''>reducer</span> <span m=''4553730''>over</span> <span
  m=''4554670''>some</span> <span m=''4556330''>associative</span> <span m=''4557210''>operation,</span>
  <span m=''4558090''>such</span> <span m=''4558370''>as</span> <span m=''4558500''>addition.</span>
  <span m=''4560370''>So</span> <span m=''4560550''>it</span> <span m=''4560640''>only</span>
  <span m=''4560900''>works</span> <span m=''4562460''>cleanly</span> <span m=''4563050''>if</span>
  <span m=''4563180''>your</span> <span m=''4563360''>operation</span> <span m=''4563910''>is</span>
  <span m=''4564110''>associative.</span> <span m=''4564720''>And</span> <span m=''4565100''>there</span>
  <span m=''4565220''>are</span> <span m=''4565240''>a</span> <span m=''4565280''>lot</span>
  <span m=''4565500''>of</span> <span m=''4565580''>associative</span> <span m=''4566370''>operations.</span>
  <span m=''4567860''>Addition,</span> <span m=''4568300''>multiplication,</span>
  <span m=''4568990''>logical,</span> <span m=''4569410''>and,</span> <span m=''4570120''>list</span>
  <span m=''4570480''>concatenation.</span> <span m=''4571430''>I can</span> <span
  m=''4571670''>concatenate</span> <span m=''4572320''>two</span> <span m=''4572430''>lists.</span>
  </p><p><span m=''4574400''>So</span> <span m=''4574490''>what</span> <span m=''4574610''>does</span>
  <span m=''4574700''>associative</span> <span m=''4575230''>mean?</span> <span m=''4578210''>I</span>
  <span m=''4578620''>think</span> <span m=''4578810''>I</span> <span m=''4578970''>have
  a</span> <span m=''4579140''>slide</span> <span m=''4579380''>on</span> <span m=''4579460''>this</span>
  <span m=''4579630''>in a</span> <span m=''4579760''>minute.</span> <span m=''4580730''>It</span>
  <span m=''4580810''>means</span> <span m=''4581320''>a</span> <span m=''4581740''>times</span>
  <span m=''4582280''>b</span> <span m=''4583290''>times</span> <span m=''4583620''>c.</span>
  <span m=''4583900''>I</span> <span m=''4584040''>can</span> <span m=''4584190''>parenthesize</span>
  <span m=''4584530''>it</span> <span m=''4584620''>any</span> <span m=''4584960''>way</span>
  <span m=''4585170''>I</span> <span m=''4585210''>want</span> <span m=''4585740''>and</span>
  <span m=''4586220''>get</span> <span m=''4586360''>the</span> <span m=''4586420''>same</span>
  <span m=''4586670''>answer.</span> <span m=''4587020''>Associative,</span> <span
  m=''4587380''>right?</span> <span m=''4588970''>It''s not</span> <span m=''4589510''>associative</span>
  <span m=''4589940''>like</span> <span m=''4590140''>associative</span> <span m=''4590610''>memory</span>
  <span m=''4591040''>or</span> <span m=''4593120''>whatever.</span> </p><p><span
  m=''4595840''>So</span> <span m=''4596020''>now,</span> <span m=''4596280''>the</span>
  <span m=''4596620''>individual</span> <span m=''4597080''>strands</span> <span m=''4597580''>in</span>
  <span m=''4597630''>the</span> <span m=''4597720''>computation</span> <span m=''4598340''>can</span>
  <span m=''4598520''>update</span> <span m=''4598950''>x</span> <span m=''4599850''>as</span>
  <span m=''4600040''>if</span> <span m=''4600200''>it</span> <span m=''4600330''>were</span>
  <span m=''4600510''>an</span> <span m=''4600660''>ordinary</span> <span m=''4601280''>non-local</span>
  <span m=''4601950''>variable.</span> <span m=''4603880''>But</span> <span m=''4604030''>in</span>
  <span m=''4604210''>fact,</span> <span m=''4604610''>it''s</span> <span m=''4604750''>maintained</span>
  <span m=''4605250''>as</span> <span m=''4605750''>a set of</span> <span m=''4605820''>different</span>
  <span m=''4607100''>copies</span> <span m=''4607670''>called</span> <span m=''4608120''>views.</span>
  <span m=''4610540''>The</span> <span m=''4610630''>Cilk++</span> <span m=''4611480''>runtime</span>
  <span m=''4611920''>system</span> <span m=''4612340''>coordinates</span> <span m=''4612890''>the</span>
  <span m=''4612970''>views</span> <span m=''4613290''>and</span> <span m=''4613400''>combines</span>
  <span m=''4613930''>them</span> <span m=''4614080''>when</span> <span m=''4614230''>appropriate.</span>
  <span m=''4615370''>And</span> <span m=''4615510''>when</span> <span m=''4615700''>only</span>
  <span m=''4616020''>one</span> <span m=''4616410''>view</span> <span m=''4616740''>remains,</span>
  <span m=''4617680''>now</span> <span m=''4617910''>you</span> <span m=''4618080''>can</span>
  <span m=''4618250''>get</span> <span m=''4618490''>the</span> <span m=''4618620''>actual</span>
  <span m=''4618980''>value.</span> </p><p><span m=''4619710''>So</span> <span m=''4619890''>for</span>
  <span m=''4619980''>example,</span> <span m=''4620270''>you</span> <span m=''4620380''>may</span>
  <span m=''4620540''>have</span> <span m=''4620630''>a</span> <span m=''4620720''>summing</span>
  <span m=''4621600''>reducer</span> <span m=''4622610''>where</span> <span m=''4622750''>the</span>
  <span m=''4622890''>actual</span> <span m=''4623290''>value</span> <span m=''4624660''>at</span>
  <span m=''4624850''>this</span> <span m=''4625000''>point</span> <span m=''4625190''>in
  time is</span> <span m=''4625540''>89.</span> <span m=''4626620''>But</span> <span
  m=''4626760''>locally,</span> <span m=''4629990''>each</span> <span m=''4630540''>processor</span>
  <span m=''4631200''>may</span> <span m=''4631480''>only</span> <span m=''4631800''>see</span>
  <span m=''4632440''>a</span> <span m=''4632540''>different</span> <span m=''4633030''>value</span>
  <span m=''4636120''>whose</span> <span m=''4636350''>sum</span> <span m=''4636900''>is</span>
  <span m=''4637110''>89.</span> <span m=''4638790''>But</span> <span m=''4638990''>locally,</span>
  <span m=''4639590''>I</span> <span m=''4639710''>could</span> <span m=''4639980''>do</span>
  <span m=''4640140''>something</span> <span m=''4640540''>like</span> <span m=''4641060''>increment</span>
  <span m=''4641650''>this.</span> <span m=''4643170''>And</span> <span m=''4643320''>this</span>
  <span m=''4643500''>guy</span> <span m=''4643660''>can</span> <span m=''4643840''>independently</span>
  <span m=''4644590''>increment</span> <span m=''4644920''>his</span> <span m=''4645230''>view</span>
  <span m=''4646130''>and</span> <span m=''4646600''>has</span> <span m=''4646890''>the</span>
  <span m=''4647010''>effect</span> <span m=''4647440''>that it</span> <span m=''4647570''>increments</span>
  <span m=''4648200''>whatever</span> <span m=''4648540''>the</span> <span m=''4648660''>total</span>
  <span m=''4649000''>sum is.</span> <span m=''4650100''>And</span> <span m=''4650210''>then,</span>
  <span m=''4650320''>the</span> <span m=''4650430''>runtime</span> <span m=''4650910''>system</span>
  <span m=''4651260''>manages</span> <span m=''4651840''>to</span> <span m=''4653220''>combine</span>
  <span m=''4653530''>everything</span> <span m=''4653920''>at</span> <span m=''4654030''>the</span>
  <span m=''4654200''>end</span> <span m=''4654810''>to</span> <span m=''4654920''>make</span>
  <span m=''4655140''>it</span> <span m=''4655290''>be</span> <span m=''4656880''>the</span>
  <span m=''4657280''>value</span> <span m=''4657970''>when</span> <span m=''4658080''>there''s</span>
  <span m=''4658270''>no</span> <span m=''4658400''>more</span> <span m=''4658630''>parallelism</span>
  <span m=''4659280''>associated</span> <span m=''4659950''>with</span> <span m=''4660080''>that</span>
  <span m=''4660600''>reducer.</span> </p><p><span m=''4662410''>So</span> <span m=''4662530''>here''s</span>
  <span m=''4662950''>the</span> <span m=''4663040''>conceptual</span> <span m=''4663580''>behavior.</span>
  <span m=''4664390''>Imagine</span> <span m=''4664860''>I</span> <span m=''4664940''>have</span>
  <span m=''4665150''>this</span> <span m=''4665390''>code.</span> <span m=''4665980''>I</span>
  <span m=''4666080''>set</span> <span m=''4666320''>x</span> <span m=''4666550''>equal</span>
  <span m=''4666770''>to</span> <span m=''4666830''>0.</span> <span m=''4667780''>I</span>
  <span m=''4667900''>then</span> <span m=''4668080''>add</span> <span m=''4668660''>3.</span>
  <span m=''4669180''>I</span> <span m=''4669230''>then</span> <span m=''4669530''>increment.</span>
  <span m=''4670210''>I</span> <span m=''4670370''>had</span> <span m=''4670530''>4,</span>
  <span m=''4670930''>increments</span> <span m=''4671210''>at</span> <span m=''4671490''>5.</span>
  <span m=''4671960''>Fa da da da da.</span> <span m=''4673240''>At</span> <span m=''4673340''>the</span>
  <span m=''4673470''>end,</span> <span m=''4675830''>I</span> <span m=''4675940''>get</span>
  <span m=''4676230''>some</span> <span m=''4676420''>value,</span> <span m=''4676870''>which</span>
  <span m=''4677040''>I</span> <span m=''4677130''>don''t</span> <span m=''4677230''>think</span>
  <span m=''4677410''>I</span> <span m=''4677440''>put</span> <span m=''4677680''>down.</span>
  </p><p><span m=''4681360''>Another</span> <span m=''4681740''>way</span> <span m=''4681960''>I</span>
  <span m=''4682060''>could</span> <span m=''4682340''>do</span> <span m=''4682520''>this</span>
  <span m=''4682750''>is</span> <span m=''4682900''>the</span> <span m=''4682990''>following.</span>
  <span m=''4683550''>Let</span> <span m=''4683780''>me</span> <span m=''4683910''>do</span>
  <span m=''4684050''>exactly</span> <span m=''4684650''>the</span> <span m=''4684750''>same</span>
  <span m=''4685070''>here</span> <span m=''4685450''>but</span> <span m=''4685660''>with</span>
  <span m=''4685920''>a</span> <span m=''4686100''>local</span> <span m=''4686540''>view</span>
  <span m=''4686830''>that</span> <span m=''4686970''>I''ll</span> <span m=''4687140''>call</span>
  <span m=''4687700''>x1.</span> <span m=''4690520''>For</span> <span m=''4690640''>this</span>
  <span m=''4690890''>set</span> <span m=''4691270''>of</span> <span m=''4691350''>operations,</span>
  <span m=''4692100''>let</span> <span m=''4692300''>me</span> <span m=''4692430''>start</span>
  <span m=''4692810''>a</span> <span m=''4692880''>new</span> <span m=''4693340''>view</span>
  <span m=''4693910''>that I</span> <span m=''4694060''>start</span> <span m=''4694420''>out</span>
  <span m=''4694730''>with</span> <span m=''4694800''>the</span> <span m=''4694920''>identity</span>
  <span m=''4695670''>for</span> <span m=''4696010''>addition,</span> <span m=''4696680''>which</span>
  <span m=''4696890''>is</span> <span m=''4697030''>0</span> <span m=''4698020''>and</span>
  <span m=''4698210''>add</span> <span m=''4698530''>those</span> <span m=''4698840''>guys</span>
  <span m=''4699190''>up.</span> <span m=''4699970''>And</span> <span m=''4700120''>then,</span>
  <span m=''4700270''>at</span> <span m=''4700400''>the</span> <span m=''4700640''>end,</span>
  <span m=''4700880''>let</span> <span m=''4701050''>me</span> <span m=''4701220''>add</span>
  <span m=''4701780''>x1</span> <span m=''4701960''>and</span> <span m=''4702300''>x2.</span>
  <span m=''4704060''>It</span> <span m=''4704420''>should</span> <span m=''4704670''>give</span>
  <span m=''4704780''>me</span> <span m=''4704880''>the</span> <span m=''4704970''>same</span>
  <span m=''4705290''>answer</span> <span m=''4705820''>if</span> <span m=''4706020''>addition</span>
  <span m=''4706400''>is</span> <span m=''4706540''>associative.</span> <span m=''4710600''>In
  particular,</span> <span m=''4711240''>these</span> <span m=''4711530''>now</span>
  <span m=''4711780''>can operate</span> <span m=''4712030''>in parallel</span> <span
  m=''4712940''>with</span> <span m=''4713070''>no</span> <span m=''4713210''>races.</span>
  </p><p><span m=''4716520''>So</span> <span m=''4716700''>if</span> <span m=''4716760''>you</span>
  <span m=''4716880''>don''t</span> <span m=''4717300''>actually</span> <span m=''4717710''>look</span>
  <span m=''4718160''>at</span> <span m=''4718260''>the</span> <span m=''4718390''>intermediate</span>
  <span m=''4718890''>values--</span> <span m=''4719830''>if</span> <span m=''4719970''>all</span>
  <span m=''4720210''>I''m</span> <span m=''4720270''>doing</span> <span m=''4720620''>is</span>
  <span m=''4720800''>updating</span> <span m=''4721450''>them,</span> <span m=''4721850''>but</span>
  <span m=''4721990''>I''m</span> <span m=''4722100''>not</span> <span m=''4722300''>actually</span>
  <span m=''4722640''>looking</span> <span m=''4723080''>to</span> <span m=''4723150''>see</span>
  <span m=''4723350''>what</span> <span m=''4723570''>the</span> <span m=''4724150''>absolute</span>
  <span m=''4724670''>value</span> <span m=''4725110''>of</span> <span m=''4725310''>the</span>
  <span m=''4725910''>thing</span> <span m=''4726200''>is,</span> <span m=''4726690''>I</span>
  <span m=''4726810''>should</span> <span m=''4727010''>get</span> <span m=''4727170''>the</span>
  <span m=''4727240''>same</span> <span m=''4727570''>answer</span> <span m=''4727940''>at
  the end.</span> <span m=''4729900''>The answer to the</span> <span m=''4729960''>result</span>
  <span m=''4730370''>is</span> <span m=''4730490''>then</span> <span m=''4730720''>determinant.</span>
  <span m=''4731420''>It''s</span> <span m=''4731620''>not</span> <span m=''4731910''>deterministic</span>
  <span m=''4733190''>because it''s</span> <span m=''4733360''>going</span> <span
  m=''4733470''>to</span> <span m=''4733510''>get</span> <span m=''4733820''>done</span>
  <span m=''4734040''>in</span> <span m=''4734190''>a</span> <span m=''4734230''>different</span>
  <span m=''4734620''>way</span> <span m=''4734900''>with</span> <span m=''4735050''>different</span>
  <span m=''4735350''>memory</span> <span m=''4735640''>state.</span> <span m=''4736200''>But
  it''s</span> <span m=''4736370''>determinant,</span> <span m=''4737050''>meaning</span>
  <span m=''4737390''>the</span> <span m=''4738080''>output</span> <span m=''4738590''>answer
  is</span> <span m=''4739110''>going</span> <span m=''4739220''>to</span> <span m=''4739260''>give</span>
  <span m=''4739440''>you</span> <span m=''4739510''>the</span> <span m=''4739620''>same</span>
  <span m=''4740730''>no</span> <span m=''4740850''>matter</span> <span m=''4741100''>how</span>
  <span m=''4741350''>it</span> <span m=''4741450''>executes,</span> <span m=''4742560''>even</span>
  <span m=''4742810''>if</span> <span m=''4742930''>the</span> <span m=''4743350''>resulting</span>
  <span m=''4743790''>computation</span> <span m=''4744730''>is</span> <span m=''4744910''>nondeterministic.</span>
  </p><p><span m=''4746250''>So</span> <span m=''4746370''>this</span> <span m=''4746540''>is</span>
  <span m=''4746610''>a</span> <span m=''4746710''>way</span> <span m=''4746940''>of</span>
  <span m=''4747170''>encapsulating,</span> <span m=''4748010''>if</span> <span m=''4748120''>you</span>
  <span m=''4748240''>will,</span> <span m=''4748470''>nondeterminism.</span> <span
  m=''4749650''>And</span> <span m=''4750000''>it</span> <span m=''4750170''>worked</span>
  <span m=''4750520''>because</span> <span m=''4750650''>addition</span> <span m=''4751010''>is</span>
  <span m=''4751140''>associative.</span> <span m=''4752430''>It</span> <span m=''4752620''>didn''t</span>
  <span m=''4752800''>matter</span> <span m=''4753070''>which</span> <span m=''4753260''>order</span>
  <span m=''4753520''>I</span> <span m=''4753610''>did</span> <span m=''4753910''>it.</span>
  <span m=''4755340''>And</span> <span m=''4755530''>once</span> <span m=''4755810''>again,</span>
  <span m=''4756050''>I</span> <span m=''4756110''>could</span> <span m=''4756310''>have</span>
  <span m=''4756390''>broken</span> <span m=''4756800''>it</span> <span m=''4756900''>here</span>
  <span m=''4757240''>instead</span> <span m=''4757570''>of</span> <span m=''4757660''>there,</span>
  <span m=''4758410''>and</span> <span m=''4758520''>I</span> <span m=''4758580''>still</span>
  <span m=''4758820''>get</span> <span m=''4758940''>the</span> <span m=''4759000''>same</span>
  <span m=''4759270''>answer.</span> <span m=''4760360''>It</span> <span m=''4760530''>doesn''t</span>
  <span m=''4760810''>matter.</span> </p><p><span m=''4761460''>So</span> <span m=''4761630''>the</span>
  <span m=''4761760''>idea</span> <span m=''4762070''>is</span> <span m=''4762190''>as</span>
  <span m=''4762480''>these</span> <span m=''4762730''>things</span> <span m=''4762960''>are</span>
  <span m=''4763030''>work</span> <span m=''4763300''>stealing</span> <span m=''4763780''>around.</span>
  <span m=''4764540''>they''re</span> <span m=''4764690''>accumulating</span> <span
  m=''4765230''>things</span> <span m=''4765520''>locally</span> <span m=''4765970''>but</span>
  <span m=''4766160''>combining</span> <span m=''4766740''>them</span> <span m=''4766900''>in</span>
  <span m=''4766970''>a</span> <span m=''4767030''>way</span> <span m=''4767330''>that</span>
  <span m=''4767500''>maintains</span> <span m=''4769370''>the</span> <span m=''4769830''>invariant</span>
  <span m=''4770770''>that</span> <span m=''4770950''>the</span> <span m=''4771100''>final</span>
  <span m=''4771500''>value</span> <span m=''4772080''>is</span> <span m=''4772860''>going
  to</span> <span m=''4773000''>be</span> <span m=''4773070''>the</span> <span m=''4773290''>sum.</span>
  <span m=''4776240''>So</span> <span m=''4776440''>there''s</span> <span m=''4776630''>a</span>
  <span m=''4776690''>lot</span> <span m=''4776960''>of</span> <span m=''4777070''>other</span>
  <span m=''4777290''>related</span> <span m=''4777720''>work</span> <span m=''4778010''>where</span>
  <span m=''4778120''>people</span> <span m=''4778550''>do</span> <span m=''4778760''>reduction</span>
  <span m=''4779320''>types</span> <span m=''4779590''>of</span> <span m=''4779710''>things,</span>
  <span m=''4780030''>but</span> <span m=''4780310''>they''re</span> <span m=''4780480''>all</span>
  <span m=''4780790''>tied</span> <span m=''4781590''>to</span> <span m=''4781940''>specific</span>
  <span m=''4782680''>control</span> <span m=''4783280''>or</span> <span m=''4783410''>data</span>
  <span m=''4783670''>structures.</span> </p><p><span m=''4784520''>And</span> <span
  m=''4784650''>the</span> <span m=''4784730''>neat</span> <span m=''4784990''>thing</span>
  <span m=''4785200''>about</span> <span m=''4785730''>the</span> <span m=''4786210''>Cilk++</span>
  <span m=''4787570''>version</span> <span m=''4788340''>is</span> <span m=''4788710''>that</span>
  <span m=''4788860''>it</span> <span m=''4789110''>is</span> <span m=''4790300''>not</span>
  <span m=''4790560''>tied</span> <span m=''4790860''>to</span> <span m=''4790940''>anything.</span>
  <span m=''4791290''>You</span> <span m=''4791470''>can</span> <span m=''4791660''>name</span>
  <span m=''4791920''>it anywhere.</span> <span m=''4792430''>You can</span> <span
  m=''4792610''>write</span> <span m=''4792940''>recursive</span> <span m=''4793310''>programs.</span>
  <span m=''4794280''>You</span> <span m=''4794400''>can</span> <span m=''4794570''>update</span>
  <span m=''4794980''>locally</span> <span m=''4795550''>your</span> <span m=''4796340''>reducer</span>
  <span m=''4796850''>wherever</span> <span m=''4797330''>you</span> <span m=''4797450''>want,</span>
  <span m=''4797875''>and</span> <span m=''4798300''>it</span> <span m=''4798880''>figures</span>
  <span m=''4799280''>out</span> <span m=''4799720''>exactly</span> <span m=''4800220''>how</span>
  <span m=''4800580''>to</span> <span m=''4801910''>combine</span> <span m=''4802340''>them</span>
  <span m=''4803040''>in</span> <span m=''4803470''>order</span> <span m=''4803700''>to</span>
  <span m=''4803810''>get</span> <span m=''4804020''>your</span> <span m=''4804140''>final</span>
  <span m=''4804550''>answer.</span> </p><p><span m=''4806760''>So</span> <span m=''4807340''>the</span>
  <span m=''4807470''>algebraic</span> <span m=''4808080''>framework</span> <span
  m=''4808600''>for</span> <span m=''4808700''>this</span> <span m=''4809100''>is</span>
  <span m=''4809430''>that</span> <span m=''4809540''>we</span> <span m=''4809670''>have</span>
  <span m=''4809840''>a</span> <span m=''4810020''>monoid,</span> <span m=''4811450''>which</span>
  <span m=''4811660''>is</span> <span m=''4812806''>a</span> <span m=''4813240''>set,</span>
  <span m=''4813950''>an</span> <span m=''4814090''>operator,</span> <span m=''4814710''>and</span>
  <span m=''4814860''>an</span> <span m=''4815000''>identity,</span> <span m=''4816380''>where</span>
  <span m=''4817480''>the</span> <span m=''4817720''>operator</span> <span m=''4818170''>is</span>
  <span m=''4818280''>an</span> <span m=''4818490''>associative</span> <span m=''4819010''>binary</span>
  <span m=''4820140''>operator.</span> <span m=''4820740''>And</span> <span m=''4821150''>the</span>
  <span m=''4821290''>identity</span> <span m=''4821790''>is,</span> <span m=''4821950''>in</span>
  <span m=''4822040''>fact,</span> <span m=''4822300''>the</span> <span m=''4822430''>identity.</span>
  <span m=''4824450''>So</span> <span m=''4824750''>here</span> <span m=''4824950''>are</span>
  <span m=''4825020''>some</span> <span m=''4825180''>examples.</span> </p><p><span
  m=''4826730''>Integers</span> <span m=''4827340''>with</span> <span m=''4827500''>plus</span>
  <span m=''4827765''>and</span> <span m=''4828160''>0,</span> <span m=''4828650''>the</span>
  <span m=''4828730''>real</span> <span m=''4829010''>numbers</span> <span m=''4829410''>with</span>
  <span m=''4829530''>times</span> <span m=''4830020''>and</span> <span m=''4830150''>1,</span>
  <span m=''4831510''>true</span> <span m=''4831790''>and</span> <span m=''4831910''>false,</span>
  <span m=''4832270''>Booleans</span> <span m=''4832860''>with</span> <span m=''4833090''>and,</span>
  <span m=''4834270''>where</span> <span m=''4834370''>true</span> <span m=''4834610''>is</span>
  <span m=''4834730''>the</span> <span m=''4835110''>identity,</span> <span m=''4836730''>strings</span>
  <span m=''4838170''>over</span> <span m=''4838440''>some</span> <span m=''4838640''>alphabet</span>
  <span m=''4839360''>with</span> <span m=''4839540''>concatenation,</span> <span
  m=''4840810''>where</span> <span m=''4840950''>the</span> <span m=''4841080''>empty</span>
  <span m=''4841380''>string</span> <span m=''4841780''>is</span> <span m=''4841940''>the</span>
  <span m=''4842050''>identity.</span> <span m=''4843530''>You</span> <span m=''4843700''>can</span>
  <span m=''4843810''>do</span> <span m=''4843930''>MAX</span> <span m=''4845110''>with</span>
  <span m=''4845690''>minus</span> <span m=''4846060''>infinity</span> <span m=''4846500''>as</span>
  <span m=''4846620''>the</span> <span m=''4846720''>operation,</span> <span m=''4847160''>and</span>
  <span m=''4847600''>so</span> <span m=''4847810''>forth.</span> <span m=''4848110''>And</span>
  <span m=''4848440''>you</span> <span m=''4848580''>can</span> <span m=''4848710''>come</span>
  <span m=''4848890''>up</span> <span m=''4849020''>with</span> <span m=''4849130''>your</span>
  <span m=''4849310''>own.</span> <span m=''4849540''>It''s</span> <span m=''4849690''>easy</span>
  <span m=''4849960''>to</span> <span m=''4850030''>come</span> <span m=''4850250''>up</span>
  <span m=''4850410''>with</span> <span m=''4851320''>examples</span> <span m=''4851800''>of</span>
  <span m=''4851850''>monoids.</span> </p><p><span m=''4852990''>So</span> <span m=''4853220''>what</span>
  <span m=''4853390''>we</span> <span m=''4853500''>do</span> <span m=''4853660''>in</span>
  <span m=''4853790''>Cilk++</span> <span m=''4855030''>is</span> <span m=''4855230''>we</span>
  <span m=''4855350''>represent</span> <span m=''4855900''>a</span> <span m=''4855950''>monoid</span>
  <span m=''4856620''>over</span> <span m=''4857050''>a set</span> <span m=''4857530''>t</span>
  <span m=''4857870''>by</span> <span m=''4858100''>a</span> <span m=''4858770''>C++</span>
  <span m=''4859060''>class</span> <span m=''4859910''>that</span> <span m=''4860050''>inherits</span>
  <span m=''4861100''>from</span> <span m=''4861390''>this</span> <span m=''4861670''>base</span>
  <span m=''4861980''>class</span> <span m=''4862340''>that''s</span> <span m=''4862530''>predefined</span>
  <span m=''4863130''>for</span> <span m=''4863270''>you,</span> <span m=''4864250''>which</span>
  <span m=''4864450''>is</span> <span m=''4864590''>parameterized</span> <span m=''4866060''>using</span>
  <span m=''4866420''>templates</span> <span m=''4867550''>with</span> <span m=''4868270''>the</span>
  <span m=''4868410''>types.</span> <span m=''4868880''>So</span> <span m=''4868950''>the</span>
  <span m=''4869030''>set</span> <span m=''4869460''>that</span> <span m=''4869580''>we''re</span>
  <span m=''4869690''>going</span> <span m=''4869760''>to</span> <span m=''4869840''>use</span>
  <span m=''4870240''>is,</span> <span m=''4870400''>in</span> <span m=''4870510''>fact,</span>
  <span m=''4870770''>going to</span> <span m=''4870870''>be</span> <span m=''4871070''>a</span>
  <span m=''4871180''>type.</span> </p><p><span m=''4873120''>And</span> <span m=''4873310''>the</span>
  <span m=''4873390''>member</span> <span m=''4873730''>function</span> <span m=''4874150''>reduced--</span>
  <span m=''4875090''>this</span> <span m=''4875380''>monoid</span> <span m=''4876050''>has</span>
  <span m=''4876350''>to</span> <span m=''4876510''>have</span> <span m=''4876670''>a</span>
  <span m=''4876750''>member</span> <span m=''4877100''>function</span> <span m=''4877460''>reduced</span>
  <span m=''4878300''>that</span> <span m=''4878440''>implements</span> <span m=''4879010''>the</span>
  <span m=''4879090''>binary</span> <span m=''4879620''>operator</span> <span m=''4880510''>times.</span>
  <span m=''4881050''>And it</span> <span m=''4881280''>also</span> <span m=''4881570''>has</span>
  <span m=''4881810''>an</span> <span m=''4881900''>identity</span> <span m=''4882390''>member</span>
  <span m=''4882720''>function.</span> <span m=''4884640''>So</span> <span m=''4884820''>we</span>
  <span m=''4884930''>set</span> <span m=''4885180''>up</span> <span m=''4885310''>the</span>
  <span m=''4885430''>algebraic</span> <span m=''4886000''>framework.</span> </p><p><span
  m=''4888570''>So</span> <span m=''4888780''>here''s,</span> <span m=''4889070''>for</span>
  <span m=''4889160''>example,</span> <span m=''4889520''>how</span> <span m=''4889780''>I</span>
  <span m=''4889890''>could</span> <span m=''4890110''>define</span> <span m=''4890880''>a</span>
  <span m=''4891410''>sum</span> <span m=''4891665''>monoid.</span> <span m=''4892620''>I</span>
  <span m=''4892790''>inherit</span> <span m=''4893350''>from</span> <span m=''4893970''>the</span>
  <span m=''4894060''>base</span> <span m=''4894920''>with int,</span> <span m=''4895340''>for</span>
  <span m=''4895580''>example,</span> <span m=''4895970''>here.</span> <span m=''4896600''>And</span>
  <span m=''4896740''>I</span> <span m=''4896800''>define</span> <span m=''4897480''>my</span>
  <span m=''4897630''>reduced</span> <span m=''4898090''>function.</span> <span m=''4899650''>And</span>
  <span m=''4899910''>it</span> <span m=''4900090''>actually</span> <span m=''4900430''>turns</span>
  <span m=''4900680''>out</span> <span m=''4900860''>to</span> <span m=''4900920''>be</span>
  <span m=''4901050''>important,</span> <span m=''4901470''>you always</span> <span
  m=''4902390''>do</span> <span m=''4902530''>the</span> <span m=''4902640''>right</span>
  <span m=''4902980''>one</span> <span m=''4903170''>into</span> <span m=''4903410''>the</span>
  <span m=''4903510''>left.</span> <span m=''4904970''>Otherwise,</span> <span m=''4905450''>you</span>
  <span m=''4905560''>won''t</span> <span m=''4905740''>have</span> <span m=''4905970''>it</span>
  <span m=''4906110''>be</span> <span m=''4906260''>associative.</span> <span m=''4907420''>And</span>
  <span m=''4907920''>then,</span> <span m=''4908120''>you</span> <span m=''4908260''>have</span>
  <span m=''4908420''>an</span> <span m=''4908530''>identity,</span> <span m=''4909070''>which</span>
  <span m=''4909260''>gives</span> <span m=''4909460''>you</span> <span m=''4909630''>in</span>
  <span m=''4909710''>this</span> <span m=''4909900''>case</span> <span m=''4910360''>a</span>
  <span m=''4910820''>new</span> <span m=''4911810''>element,</span> <span m=''4912260''>which</span>
  <span m=''4912430''>is</span> <span m=''4912560''>0.</span> </p><p><span m=''4915610''>And</span>
  <span m=''4915800''>so</span> <span m=''4916730''>you</span> <span m=''4916890''>can</span>
  <span m=''4917040''>now</span> <span m=''4917310''>define</span> <span m=''4918360''>the</span>
  <span m=''4919080''>reducer</span> <span m=''4921630''>as</span> <span m=''4921800''>so.</span>
  <span m=''4922080''>You</span> <span m=''4922210''>just</span> <span m=''4922460''>say</span>
  <span m=''4922660''>Cilk reducer,</span> <span m=''4923550''>the</span> <span m=''4923630''>sum
  monoid</span> <span m=''4924270''>you''ve</span> <span m=''4924420''>defined</span>
  <span m=''4925110''>and</span> <span m=''4925490''>x.</span> <span m=''4926760''>And</span>
  <span m=''4926950''>now,</span> <span m=''4927150''>the</span> <span m=''4927250''>local</span>
  <span m=''4927650''>view</span> <span m=''4927820''>of</span> <span m=''4927910''>x</span>
  <span m=''4928160''>can</span> <span m=''4928290''>be</span> <span m=''4928470''>accessed</span>
  <span m=''4929130''>as</span> <span m=''4929380''>x</span> <span m=''4929870''>open</span>
  <span m=''4930360''>close</span> <span m=''4930690''>parenthesis.</span> </p><p><span
  m=''4931990''>Now,</span> <span m=''4932080''>in</span> <span m=''4932160''>the</span>
  <span m=''4932230''>example</span> <span m=''4932630''>I</span> <span m=''4932700''>showed</span>
  <span m=''4932990''>you,</span> <span m=''4933180''>you didn''t</span> <span m=''4933370''>need</span>
  <span m=''4933570''>to</span> <span m=''4933650''>do</span> <span m=''4933820''>the</span>
  <span m=''4933940''>open</span> <span m=''4934440''>close</span> <span m=''4934780''>parenthesis.</span>
  <span m=''4935980''>And</span> <span m=''4936310''>the</span> <span m=''4936420''>way</span>
  <span m=''4936570''>you</span> <span m=''4936640''>get</span> <span m=''4936830''>rid</span>
  <span m=''4937010''>of</span> <span m=''4937090''>those</span> <span m=''4937300''>open</span>
  <span m=''4937540''>close</span> <span m=''4937790''>parenthesis</span> <span m=''4938045''>is</span>
  <span m=''4938300''>you</span> <span m=''4938540''>define</span> <span m=''4938900''>a</span>
  <span m=''4938970''>wrapper</span> <span m=''4939400''>class.</span> <span m=''4940930''>So</span>
  <span m=''4941060''>it''s</span> <span m=''4941190''>generally</span> <span m=''4942010''>inconvenient</span>
  <span m=''4942290''>to</span> <span m=''4942570''>replace</span> <span m=''4943000''>every</span>
  <span m=''4943240''>access</span> <span m=''4943890''>with</span> <span m=''4944120''>x</span>
  <span m=''4944420''>over</span> <span m=''4945500''>brown.</span> <span m=''4945970''>That''s</span>
  <span m=''4946180''>one</span> <span m=''4946350''>issue.</span> </p><p><span m=''4946880''>The</span>
  <span m=''4947000''>other</span> <span m=''4947150''>thing</span> <span m=''4947460''>is</span>
  <span m=''4947590''>accesses</span> <span m=''4948180''>aren''t</span> <span m=''4948410''>safe.</span>
  <span m=''4948640''>Nothing</span> <span m=''4948970''>prevents</span> <span m=''4949530''>a</span>
  <span m=''4949620''>programmer</span> <span m=''4950050''>from</span> <span m=''4950250''>writing</span>
  <span m=''4951040''>x</span> <span m=''4951860''>times</span> <span m=''4952260''>equals</span>
  <span m=''4952670''>2,</span> <span m=''4953070''>even</span> <span m=''4953310''>though</span>
  <span m=''4953440''>the</span> <span m=''4953540''>reducer</span> <span m=''4953990''>was</span>
  <span m=''4954170''>defined</span> <span m=''4954590''>over</span> <span m=''4954800''>plus.</span>
  <span m=''4955960''>And</span> <span m=''4956260''>that will</span> <span m=''4956490''>screw</span>
  <span m=''4956910''>up</span> <span m=''4957070''>the</span> <span m=''4957140''>logic</span>
  <span m=''4957630''>of</span> <span m=''4957700''>this</span> <span m=''4957910''>code</span>
  <span m=''4958230''>if</span> <span m=''4958340''>somewhere</span> <span m=''4959080''>he''s</span>
  <span m=''4959250''>multiplying</span> <span m=''4960000''>when,</span> <span m=''4960130''>in</span>
  <span m=''4960220''>fact,</span> <span m=''4960580''>it''s</span> <span m=''4960670''>only</span>
  <span m=''4960920''>supposed</span> <span m=''4961270''>to</span> <span m=''4961330''>be</span>
  <span m=''4961630''>combined</span> <span m=''4962140''>with</span> <span m=''4962280''>addition.</span>
  </p><p><span m=''4964300''>So</span> <span m=''4964650''>the</span> <span m=''4964740''>way</span>
  <span m=''4964920''>you</span> <span m=''4965010''>solve</span> <span m=''4965340''>that</span>
  <span m=''4965520''>is</span> <span m=''4965660''>with</span> <span m=''4965790''>a</span>
  <span m=''4965860''>wrapper</span> <span m=''4966240''>class.</span> <span m=''4966740''>You
  can</span> <span m=''4966830''>do</span> <span m=''4966920''>a</span> <span m=''4966990''>wrapper</span>
  <span m=''4967340''>class</span> <span m=''4967680''>that will</span> <span m=''4968020''>protect</span>
  <span m=''4968620''>all</span> <span m=''4968850''>of</span> <span m=''4968940''>the</span>
  <span m=''4969540''>operations</span> <span m=''4970910''>inside</span> <span m=''4971940''>and</span>
  <span m=''4972220''>export</span> <span m=''4972810''>things</span> <span m=''4973010''>that</span>
  <span m=''4973150''>you</span> <span m=''4973280''>can</span> <span m=''4973390''>just</span>
  <span m=''4973590''>refer</span> <span m=''4974020''>to</span> <span m=''4974120''>the</span>
  <span m=''4974220''>variable.</span> <span m=''4974760''>And it</span> <span m=''4975130''>will</span>
  <span m=''4975260''>actually</span> <span m=''4976000''>call</span> <span m=''4976260''>that.</span>
  <span m=''4976770''>For</span> <span m=''4977030''>most</span> <span m=''4977300''>of</span>
  <span m=''4977360''>what</span> <span m=''4977520''>you''re</span> <span m=''4977660''>doing,</span>
  <span m=''4977940''>you</span> <span m=''4978050''>probably</span> <span m=''4978400''>don''t</span>
  <span m=''4978670''>need</span> <span m=''4978830''>to</span> <span m=''4978930''>write</span>
  <span m=''4979130''>a</span> <span m=''4979180''>wrapper</span> <span m=''4979530''>class.</span>
  <span m=''4980380''>You''ll</span> <span m=''4980520''>do</span> <span m=''4980660''>fine</span>
  <span m=''4981430''>just</span> <span m=''4982900''>operating</span> <span m=''4983760''>with</span>
  <span m=''4984080''>the</span> <span m=''4984800''>extra</span> <span m=''4985090''>parentheses.</span>
  </p><p><span m=''4987950''>In</span> <span m=''4988080''>addition,</span> <span
  m=''4988490''>there''s</span> <span m=''4988640''>a</span> <span m=''4988700''>whole</span>
  <span m=''4988980''>bunch</span> <span m=''4989240''>of</span> <span m=''4989330''>commonly</span>
  <span m=''4990370''>use</span> <span m=''4990620''>reducers.</span> <span m=''4991680''>Lists,</span>
  <span m=''4992080''>appends,</span> <span m=''4992670''>max,</span> <span m=''4993150''>min,</span>
  <span m=''4994530''>adds,</span> <span m=''4996020''>an</span> <span m=''4996250''>output</span>
  <span m=''4996690''>stream,</span> <span m=''4997600''>and</span> <span m=''4997980''>some</span>
  <span m=''4998180''>strings,</span> <span m=''4999030''>and</span> <span m=''4999190''>also</span>
  <span m=''4999410''>you</span> <span m=''4999510''>can roll</span> <span m=''4999930''>your</span>
  <span m=''5000160''>own</span> <span m=''5000410''>using</span> <span m=''5001900''>things.</span>
  <span m=''5003640''>One</span> <span m=''5003930''>issue</span> <span m=''5005000''>with</span>
  <span m=''5005310''>addition</span> <span m=''5006290''>is</span> <span m=''5006600''>that,</span>
  <span m=''5006840''>in</span> <span m=''5006990''>fact,</span> <span m=''5007380''>this</span>
  <span m=''5007650''>doesn''t</span> <span m=''5008060''>preserve--</span> <span
  m=''5009810''>for</span> <span m=''5010540''>floating</span> <span m=''5010920''>point</span>
  <span m=''5011140''>addition--</span> <span m=''5011580''>does</span> <span m=''5011750''>not</span>
  <span m=''5012030''>preserve</span> <span m=''5012860''>the</span> <span m=''5013370''>same</span>
  <span m=''5013810''>answer.</span> </p><p><span m=''5014970''>And</span> <span m=''5015120''>the</span>
  <span m=''5015200''>reason</span> <span m=''5015530''>is</span> <span m=''5015740''>because</span>
  <span m=''5016490''>floating</span> <span m=''5016840''>point</span> <span m=''5017090''>numbers</span>
  <span m=''5017420''>are</span> <span m=''5017480''>not</span> <span m=''5017710''>associative.</span>
  <span m=''5018970''>If I</span> <span m=''5019140''>had</span> <span m=''5019340''>a
  to b</span> <span m=''5020130''>and</span> <span m=''5020270''>add</span> <span
  m=''5020460''>that</span> <span m=''5020700''>to</span> <span m=''5020760''>c,</span>
  <span m=''5021460''>I</span> <span m=''5021550''>can</span> <span m=''5021690''>get</span>
  <span m=''5021840''>something</span> <span m=''5022270''>different</span> <span
  m=''5022740''>because</span> <span m=''5022990''>of</span> <span m=''5023120''>round</span>
  <span m=''5023430''>off</span> <span m=''5023640''>error</span> <span m=''5024260''>from</span>
  <span m=''5024390''>adding</span> <span m=''5024810''>a</span> <span m=''5025160''>to</span>
  <span m=''5025300''>the</span> <span m=''5025370''>result</span> <span m=''5025770''>of</span>
  <span m=''5025840''>b</span> <span m=''5026090''>and</span> <span m=''5026210''>c.</span>
  <span m=''5027320''>So</span> <span m=''5027530''>generally,</span> <span m=''5027920''>floating</span>
  <span m=''5028250''>point</span> <span m=''5028740''>operations</span> <span m=''5029790''>don''t</span>
  <span m=''5030510''>give</span> <span m=''5030640''>you-- they''ll give you</span>
  <span m=''5030730''>something</span> <span m=''5031050''>that is</span> <span m=''5031210''>close</span>
  <span m=''5031520''>enough</span> <span m=''5032270''>for</span> <span m=''5032390''>most</span>
  <span m=''5033400''>things,</span> <span m=''5033680''>but</span> <span m=''5033810''>it''s</span>
  <span m=''5033960''>not</span> <span m=''5034190''>actually</span> <span m=''5034560''>associative.</span>
  <span m=''5035110''>So</span> <span m=''5035210''>you</span> <span m=''5035340''>will</span>
  <span m=''5035550''>get</span> <span m=''5035750''>different</span> <span m=''5035990''>answers.</span>
  </p><p><span m=''5038580''>A</span> <span m=''5038680''>quick</span> <span m=''5038910''>example.</span>
  <span m=''5039390''>I''m</span> <span m=''5039490''>sorry</span> <span m=''5039690''>to</span>
  <span m=''5039770''>run</span> <span m=''5040000''>over</span> <span m=''5040230''>a</span>
  <span m=''5040280''>little</span> <span m=''5040460''>bit</span> <span m=''5040810''>here.</span>
  <span m=''5041200''>I</span> <span m=''5041510''>hope</span> <span m=''5041730''>people</span>
  <span m=''5041980''>have</span> <span m=''5042150''>a</span> <span m=''5042350''>couple</span>
  <span m=''5042590''>minutes.</span> </p><p><span m=''5043850''>Here''s</span> <span
  m=''5044040''>a</span> <span m=''5044110''>real</span> <span m=''5044370''>world</span>
  <span m=''5044650''>example.</span> <span m=''5045800''>A company</span> <span m=''5046670''>had</span>
  <span m=''5046790''>a</span> <span m=''5046950''>mechanical</span> <span m=''5047440''>assembly</span>
  <span m=''5047910''>represented</span> <span m=''5048530''>a</span> <span m=''5048610''>tree</span>
  <span m=''5048890''>of</span> <span m=''5048970''>assemblies</span> <span m=''5049620''>down</span>
  <span m=''5049860''>to</span> <span m=''5049960''>individual</span> <span m=''5050420''>parts.</span>
  <span m=''5051170''>A</span> <span m=''5051250''>pickup</span> <span m=''5051590''>truck</span>
  <span m=''5051900''>has</span> <span m=''5052080''>all</span> <span m=''5052250''>these</span>
  <span m=''5052440''>parts</span> <span m=''5053460''>and</span> <span m=''5053610''>all
  of</span> <span m=''5053810''>these</span> <span m=''5054020''>extra</span> <span
  m=''5054820''>subparts</span> <span m=''5055360''>all</span> <span m=''5055480''>the</span>
  <span m=''5055600''>way</span> <span m=''5055720''>down</span> <span m=''5056090''>to</span>
  <span m=''5056220''>some</span> <span m=''5056550''>geometric</span> <span m=''5057100''>description</span>
  <span m=''5057990''>of</span> <span m=''5058110''>what</span> <span m=''5058280''>the</span>
  <span m=''5058360''>part is.</span> <span m=''5059670''>And</span> <span m=''5059830''>what</span>
  <span m=''5060010''>they</span> <span m=''5060100''>want</span> <span m=''5060270''>to</span>
  <span m=''5060340''>do</span> <span m=''5060540''>is</span> <span m=''5060700''>the</span>
  <span m=''5060770''>so-called</span> <span m=''5061230''>collision</span> <span
  m=''5061610''>detection</span> <span m=''5062070''>problem, which</span> <span m=''5062430''>has</span>
  <span m=''5062580''>nothing</span> <span m=''5062810''>to</span> <span m=''5062850''>do</span>
  <span m=''5062980''>with</span> <span m=''5063180''>colliding</span> <span m=''5063560''>autos.</span>
  </p><p><span m=''5064390''>What</span> <span m=''5064600''>they''re</span> <span
  m=''5064700''>doing</span> <span m=''5065000''>is</span> <span m=''5065090''>saying,</span>
  <span m=''5066500''>find</span> <span m=''5066810''>collisions</span> <span m=''5067350''>between</span>
  <span m=''5067650''>the</span> <span m=''5067730''>assembly</span> <span m=''5068140''>and
  a</span> <span m=''5068280''>target</span> <span m=''5068790''>object.</span> <span
  m=''5069230''>And</span> <span m=''5069370''>that</span> <span m=''5069520''>object</span>
  <span m=''5069890''>might</span> <span m=''5070070''>be</span> <span m=''5070160''>something</span>
  <span m=''5070490''>like</span> <span m=''5070690''>a</span> <span m=''5070720''>half</span>
  <span m=''5071020''>space</span> <span m=''5071870''>because</span> <span m=''5072020''>they''re</span>
  <span m=''5072130''>computing</span> <span m=''5072580''>a</span> <span m=''5072650''>cutaway.</span>
  <span m=''5073250''>Tell</span> <span m=''5073430''>me</span> <span m=''5073610''>all</span>
  <span m=''5073890''>the</span> <span m=''5073980''>things</span> <span m=''5074340''>that</span>
  <span m=''5074450''>fall</span> <span m=''5075220''>within</span> <span m=''5075480''>this.</span>
  <span m=''5075720''>Or</span> <span m=''5075960''>maybe,</span> <span m=''5076670''>here''s</span>
  <span m=''5076830''>an</span> <span m=''5076930''>engine</span> <span m=''5077940''>compartment,</span>
  <span m=''5078590''>and</span> <span m=''5079190''>does</span> <span m=''5079460''>the</span>
  <span m=''5079710''>engine</span> <span m=''5080080''>fit</span> <span m=''5080280''>in</span>
  <span m=''5080910''>with</span> <span m=''5081100''>it?</span> </p><p><span m=''5082270''>So</span>
  <span m=''5083060''>here''s</span> <span m=''5083410''>a</span> <span m=''5083520''>code</span>
  <span m=''5083890''>that</span> <span m=''5084050''>does</span> <span m=''5084370''>that.</span>
  <span m=''5084690''>Basically,</span> <span m=''5085170''>it</span> <span m=''5085300''>does</span>
  <span m=''5086060''>a</span> <span m=''5086120''>recursive</span> <span m=''5086630''>walk,</span>
  <span m=''5088610''>where</span> <span m=''5089200''>it</span> <span m=''5089380''>looks</span>
  <span m=''5089630''>to</span> <span m=''5089740''>see</span> <span m=''5090020''>whether</span>
  <span m=''5090320''>it''s</span> <span m=''5090450''>an</span> <span m=''5090560''>internal</span>
  <span m=''5091080''>node</span> <span m=''5091450''>or a leaf.</span> <span m=''5092080''>If</span>
  <span m=''5092330''>it''s</span> <span m=''5092470''>a</span> <span m=''5092540''>leaf,</span>
  <span m=''5093390''>it</span> <span m=''5093540''>says,</span> <span m=''5093770''>oh,</span>
  <span m=''5094220''>let</span> <span m=''5094430''>me</span> <span m=''5097150''>check</span>
  <span m=''5097420''>to</span> <span m=''5097520''>see</span> <span m=''5097750''>whether</span>
  <span m=''5098000''>the</span> <span m=''5098150''>target</span> <span m=''5098650''>collides</span>
  <span m=''5099190''>with</span> <span m=''5099390''>a</span> <span m=''5099440''>particular</span>
  <span m=''5100440''>element</span> <span m=''5100910''>of</span> <span m=''5101030''>the</span>
  <span m=''5101120''>tree.</span> <span m=''5101790''>And</span> <span m=''5101940''>if</span>
  <span m=''5102030''>so,</span> <span m=''5102460''>add</span> <span m=''5102890''>that</span>
  <span m=''5103780''>object</span> <span m=''5104640''>to</span> <span m=''5104720''>the</span>
  <span m=''5104870''>end</span> <span m=''5105060''>of</span> <span m=''5105130''>a</span>
  <span m=''5105740''>list.</span> <span m=''5106120''>So</span> <span m=''5106320''>this</span>
  <span m=''5106520''>is</span> <span m=''5106700''>the</span> <span m=''5109590''>standard</span>
  <span m=''5109990''>a</span> <span m=''5110980''>C++</span> <span m=''5112160''>library</span>
  <span m=''5112640''>for</span> <span m=''5112870''>putting</span> <span m=''5113380''>something</span>
  <span m=''5113730''>on</span> <span m=''5113850''>the</span> <span m=''5113970''>end</span>
  <span m=''5114120''>of</span> <span m=''5114170''>the</span> <span m=''5114250''>list.</span>
  </p><p><span m=''5115950''>If</span> <span m=''5116070''>it''s</span> <span m=''5116210''>an</span>
  <span m=''5116320''>internal</span> <span m=''5116870''>node,</span> <span m=''5117630''>then</span>
  <span m=''5117790''>go</span> <span m=''5118000''>through</span> <span m=''5118250''>all</span>
  <span m=''5118570''>of</span> <span m=''5118670''>the</span> <span m=''5118800''>children</span>
  <span m=''5119670''>recursively.</span> <span m=''5121030''>And</span> <span m=''5122500''>walk</span>
  <span m=''5123060''>the</span> <span m=''5123160''>children</span> <span m=''5123770''>recursively.</span>
  <span m=''5125680''>So</span> <span m=''5125810''>basically,</span> <span m=''5126660''>you''re</span>
  <span m=''5126770''>going</span> <span m=''5126900''>to</span> <span m=''5126950''>look</span>
  <span m=''5127460''>through</span> <span m=''5127640''>the</span> <span m=''5127700''>whole</span>
  <span m=''5127930''>tree.</span> <span m=''5128850''>Does</span> <span m=''5129060''>it</span>
  <span m=''5129130''>intersect</span> <span m=''5130430''>this</span> <span m=''5131630''>particular</span>
  <span m=''5132160''>object,</span> <span m=''5132640''>x?</span> </p><p><span m=''5134290''>So</span>
  <span m=''5134520''>how</span> <span m=''5134680''>do</span> <span m=''5134770''>we</span>
  <span m=''5134870''>parallelize</span> <span m=''5135610''>this?</span> <span m=''5136290''>We</span>
  <span m=''5136420''>can</span> <span m=''5136530''>parallelize</span> <span m=''5137110''>the</span>
  <span m=''5137290''>recursion.</span> <span m=''5138060''>We</span> <span m=''5138220''>turn</span>
  <span m=''5139020''>the</span> <span m=''5139090''>4</span> <span m=''5139320''>loop</span>
  <span m=''5139560''>here</span> <span m=''5139850''>into</span> <span m=''5140040''>a</span>
  <span m=''5140090''>Cilk</span> <span m=''5140300''>4.</span> <span m=''5141280''>So</span>
  <span m=''5141460''>it goes</span> <span m=''5141660''>through</span> <span m=''5141840''>all</span>
  <span m=''5142030''>the</span> <span m=''5142140''>children</span> <span m=''5142490''>at
  the</span> <span m=''5142550''>same</span> <span m=''5142850''>time.</span> <span
  m=''5143640''>They</span> <span m=''5143780''>all</span> <span m=''5144120''>can</span>
  <span m=''5144280''>do</span> <span m=''5144410''>their</span> <span m=''5144560''>comparisons</span>
  <span m=''5145270''>completely</span> <span m=''5146330''>the</span> <span m=''5146440''>same.</span>
  </p><p><span m=''5147830''>Oops, but</span> <span m=''5147960''>we</span> <span
  m=''5148050''>have</span> <span m=''5148140''>a</span> <span m=''5148240''>bug.</span>
  <span m=''5149580''>What''s</span> <span m=''5149740''>the</span> <span m=''5149910''>bug?</span>
  </p><p><span m=''5152170''>AUDIENCE: Is it</span> <span m=''5152625''>push</span>
  <span m=''5153080''>back?</span> </p><p><span m=''5154900''>PROFESSOR: Yeah.</span>
  <span m=''5155230''>The</span> <span m=''5155400''>push</span> <span m=''5155720''>back</span>
  <span m=''5156000''>here.</span> <span m=''5156760''>We</span> <span m=''5156850''>have</span>
  <span m=''5156950''>a</span> <span m=''5157020''>race</span> <span m=''5157370''>here</span>
  <span m=''5160600''>because</span> <span m=''5160980''>they''re</span> <span m=''5161090''>all</span>
  <span m=''5161380''>trying</span> <span m=''5161670''>to</span> <span m=''5161730''>push</span>
  <span m=''5162040''>on</span> <span m=''5162300''>to</span> <span m=''5162400''>this</span>
  <span m=''5162590''>output</span> <span m=''5163010''>list</span> <span m=''5163280''>at</span>
  <span m=''5163340''>the</span> <span m=''5163400''>same</span> <span m=''5163760''>time.</span>
  </p><p><span m=''5165380''>So</span> <span m=''5165530''>we</span> <span m=''5165620''>could</span>
  <span m=''5165840''>resolve</span> <span m=''5166280''>it</span> <span m=''5166360''>with</span>
  <span m=''5166510''>a</span> <span m=''5166560''>lock</span> <span m=''5168120''>or</span>
  <span m=''5168220''>whatever.</span> <span m=''5168870''>But</span> <span m=''5169020''>it</span>
  <span m=''5169140''>turns</span> <span m=''5169460''>out</span> <span m=''5169670''>it''s</span>
  <span m=''5170000''>much</span> <span m=''5170250''>better</span> <span m=''5170590''>to</span>
  <span m=''5170730''>resolve</span> <span m=''5171180''>it</span> <span m=''5171280''>with</span>
  <span m=''5171740''>a--</span> <span m=''5173340''>so</span> <span m=''5173400''>we</span>
  <span m=''5173500''>could</span> <span m=''5173740''>do</span> <span m=''5173880''>this,</span>
  <span m=''5174340''>right?</span> <span m=''5175900''>But</span> <span m=''5176080''>now,</span>
  <span m=''5176310''>you''ve</span> <span m=''5176520''>got</span> <span m=''5176700''>lock</span>
  <span m=''5177430''>contention.</span> <span m=''5178140''>And</span> <span m=''5178760''>also,</span>
  <span m=''5179000''>the</span> <span m=''5179040''>list</span> <span m=''5179370''>ends</span>
  <span m=''5179500''>up</span> <span m=''5179600''>getting</span> <span m=''5179860''>produced</span>
  <span m=''5180270''>in</span> <span m=''5180350''>a</span> <span m=''5180390''>jumbled</span>
  <span m=''5180780''>order.</span> </p><p><span m=''5183100''>So it</span> <span
  m=''5183250''>turns</span> <span m=''5183540''>out</span> <span m=''5183840''>if</span>
  <span m=''5183960''>you use</span> <span m=''5184410''>a reducer,</span> <span m=''5185760''>you</span>
  <span m=''5185870''>declare</span> <span m=''5187650''>this</span> <span m=''5187940''>to</span>
  <span m=''5188040''>be</span> <span m=''5188300''>a</span> <span m=''5188490''>reducer</span>
  <span m=''5188890''>with</span> <span m=''5189200''>list</span> <span m=''5189580''>append.</span>
  <span m=''5192045''>And</span> <span m=''5192450''>what</span> <span m=''5192640''>happens</span>
  <span m=''5193160''>then</span> <span m=''5193570''>is</span> <span m=''5195210''>turns</span>
  <span m=''5195500''>out</span> <span m=''5195700''>list</span> <span m=''5196250''>concatenation</span>
  <span m=''5197040''>is</span> <span m=''5197180''>associative.</span> <span m=''5198710''>If</span>
  <span m=''5198960''>I</span> <span m=''5199040''>concatenate</span> <span m=''5199480''>a</span>
  <span m=''5199590''>to</span> <span m=''5199880''>b,</span> <span m=''5201030''>and</span>
  <span m=''5201180''>then</span> <span m=''5201350''>concatenate</span> <span m=''5201920''>c,</span>
  <span m=''5202230''>that''s</span> <span m=''5202440''>the</span> <span m=''5202510''>same</span>
  <span m=''5202810''>as</span> <span m=''5202950''>concatenating</span> <span m=''5203150''>a</span>
  <span m=''5203610''>to</span> <span m=''5203955''>the</span> <span m=''5204300''>concatenation</span>
  <span m=''5204870''>of</span> <span m=''5204940''>b</span> <span m=''5205140''>and</span>
  <span m=''5205260''>c.</span> <span m=''5206040''>And</span> <span m=''5206250''>I</span>
  <span m=''5206300''>can</span> <span m=''5206530''>concatenate</span> <span m=''5207180''>lists</span>
  <span m=''5207600''>in</span> <span m=''5207840''>constant</span> <span m=''5208300''>time</span>
  <span m=''5209300''>by</span> <span m=''5209400''>keeping</span> <span m=''5209720''>a</span>
  <span m=''5209780''>pointer</span> <span m=''5210160''>to</span> <span m=''5210270''>the</span>
  <span m=''5210350''>head</span> <span m=''5210550''>and</span> <span m=''5210700''>tail</span>
  <span m=''5211020''>of</span> <span m=''5211110''>each</span> <span m=''5211810''>list.</span>
  </p><p><span m=''5213290''>So</span> <span m=''5213430''>if</span> <span m=''5213500''>you</span>
  <span m=''5213600''>do</span> <span m=''5213810''>that,</span> <span m=''5214130''>and</span>
  <span m=''5214280''>that</span> <span m=''5214480''>turns</span> <span m=''5214700''>out</span>
  <span m=''5214840''>to</span> <span m=''5214900''>be</span> <span m=''5215020''>one</span>
  <span m=''5215200''>of</span> <span m=''5215260''>the</span> <span m=''5215340''>built</span>
  <span m=''5215660''>in</span> <span m=''5215800''>functions,</span> <span m=''5216780''>then,</span>
  <span m=''5217620''>in</span> <span m=''5217780''>fact,</span> <span m=''5218090''>this</span>
  <span m=''5218290''>code</span> <span m=''5218810''>operates</span> <span m=''5219220''>perfectly</span>
  <span m=''5219740''>well</span> <span m=''5220060''>with</span> <span m=''5220240''>no</span>
  <span m=''5220460''>contention</span> <span m=''5221650''>and</span> <span m=''5221820''>so</span>
  <span m=''5221980''>forth.</span> <span m=''5222200''>And</span> <span m=''5222340''>in</span>
  <span m=''5222450''>fact,</span> <span m=''5222790''>produces</span> <span m=''5223390''>the</span>
  <span m=''5223510''>output</span> <span m=''5224250''>in</span> <span m=''5224320''>the</span>
  <span m=''5224400''>same</span> <span m=''5224720''>order</span> <span m=''5225060''>as</span>
  <span m=''5226000''>the</span> <span m=''5226120''>original</span> <span m=''5226490''>C++.</span>
  <span m=''5228000''>It</span> <span m=''5228160''>runs</span> <span m=''5228440''>fast.</span>
  <span m=''5231540''>And</span> <span m=''5231970''>there''s</span> <span m=''5232120''>a</span>
  <span m=''5232170''>little</span> <span m=''5232450''>description</span> <span m=''5233020''>of</span>
  <span m=''5233100''>how</span> <span m=''5233370''>it</span> <span m=''5233580''>works.</span>
  </p><p><span m=''5236050''>The actual</span> <span m=''5236460''>protocol</span>
  <span m=''5236980''>is</span> <span m=''5237100''>kind</span> <span m=''5237360''>of</span>
  <span m=''5237460''>tricky.</span> <span m=''5237940''>And</span> <span m=''5238010''>we''ll</span>
  <span m=''5238160''>put</span> <span m=''5238410''>the</span> <span m=''5238500''>paper--</span>
  <span m=''5239730''>let''s</span> <span m=''5239910''>make</span> <span m=''5240090''>sure</span>
  <span m=''5240210''>we</span> <span m=''5240290''>get</span> <span m=''5240440''>this</span>
  <span m=''5240590''>paper</span> <span m=''5240940''>up</span> <span m=''5241100''>on</span>
  <span m=''5242480''>the</span> <span m=''5242690''>web.</span> <span m=''5242970''>I</span>
  <span m=''5243020''>think</span> <span m=''5243230''>it</span> <span m=''5243420''>was</span>
  <span m=''5243640''>there</span> <span m=''5243800''>from</span> <span m=''5243980''>last</span>
  <span m=''5244300''>year.</span> <span m=''5244480''>So</span> <span m=''5245030''>we</span>
  <span m=''5245110''>should</span> <span m=''5245230''>be</span> <span m=''5245360''>able</span>
  <span m=''5245490''>to</span> <span m=''5245550''>find</span> <span m=''5245970''>it.</span>
  <span m=''5246990''>If</span> <span m=''5247150''>you''re</span> <span m=''5247270''>interested</span>
  <span m=''5247620''>in</span> <span m=''5247700''>how</span> <span m=''5247900''>the</span>
  <span m=''5248000''>details</span> <span m=''5248500''>work.</span> <span m=''5248740''>Here''s</span>
  <span m=''5249000''>the</span> <span m=''5249140''>important</span> <span m=''5249660''>thing</span>
  <span m=''5249860''>to</span> <span m=''5249960''>know</span> <span m=''5250620''>from</span>
  <span m=''5250810''>a</span> <span m=''5250860''>programmer</span> <span m=''5251360''>point</span>
  <span m=''5251680''>of view.</span> </p><p><span m=''5253450''>So</span> <span m=''5254280''>typically,</span>
  <span m=''5255400''>the</span> <span m=''5255520''>cost--</span> <span m=''5256630''>it</span>
  <span m=''5256870''>turns</span> <span m=''5257100''>out</span> <span m=''5257290''>the</span>
  <span m=''5257380''>reduce</span> <span m=''5257950''>operations</span> <span m=''5258810''>you''re</span>
  <span m=''5258980''>only</span> <span m=''5259430''>calling</span> <span m=''5260010''>when</span>
  <span m=''5260140''>there''s</span> <span m=''5260310''>actually</span> <span m=''5260730''>a</span>
  <span m=''5260780''>steal.</span> <span m=''5261310''>It''s</span> <span m=''5261700''>actually</span>
  <span m=''5261960''>a return</span> <span m=''5262400''>from</span> <span m=''5262490''>a</span>
  <span m=''5262590''>steal.</span> <span m=''5262900''>But</span> <span m=''5263810''>since</span>
  <span m=''5264210''>stealing</span> <span m=''5264650''>occurs</span> <span m=''5265010''>relatively</span>
  <span m=''5265560''>infrequently</span> <span m=''5266460''>the</span> <span m=''5266560''>load</span>
  <span m=''5266830''>balance,</span> <span m=''5267870''>the</span> <span m=''5267970''>number</span>
  <span m=''5268230''>of</span> <span m=''5268310''>times</span> <span m=''5268610''>you</span>
  <span m=''5268700''>actually</span> <span m=''5269040''>do</span> <span m=''5269210''>one</span>
  <span m=''5269350''>of</span> <span m=''5269450''>these</span> <span m=''5269620''>reduce</span>
  <span m=''5270640''>operations is</span> <span m=''5270700''>small.</span> </p><p><span
  m=''5273200''>The</span> <span m=''5273320''>most</span> <span m=''5273780''>of</span>
  <span m=''5273840''>the</span> <span m=''5273950''>cost</span> <span m=''5274470''>is</span>
  <span m=''5274650''>actually</span> <span m=''5275060''>accessing</span> <span m=''5275690''>the</span>
  <span m=''5275780''>reducer</span> <span m=''5276250''>to</span> <span m=''5276370''>do</span>
  <span m=''5276570''>the</span> <span m=''5276730''>updates.</span> <span m=''5278410''>And</span>
  <span m=''5278580''>it''s</span> <span m=''5278760''>never</span> <span m=''5279070''>worse</span>
  <span m=''5279370''>than</span> <span m=''5279460''>a</span> <span m=''5279510''>hash</span>
  <span m=''5279900''>table</span> <span m=''5280220''>lookup</span> <span m=''5280630''>the</span>
  <span m=''5280750''>way</span> <span m=''5280910''>it''s</span> <span m=''5281060''>implemented.</span>
  <span m=''5282480''>If</span> <span m=''5282730''>the</span> <span m=''5282880''>reducer</span>
  <span m=''5283140''>is</span> <span m=''5283780''>accessed</span> <span m=''5284470''>several
  times</span> <span m=''5284760''>within</span> <span m=''5284870''>a</span> <span
  m=''5285040''>region</span> <span m=''5285380''>of</span> <span m=''5285480''>code,</span>
  <span m=''5286460''>the</span> <span m=''5286930''>compiler</span> <span m=''5287400''>can</span>
  <span m=''5287570''>optimize</span> <span m=''5288200''>the lookups</span> <span
  m=''5288700''>using</span> <span m=''5288990''>common</span> <span m=''5289330''>subexpression</span>
  <span m=''5290040''>elimination.</span> </p><p><span m=''5291170''>And</span> <span
  m=''5291340''>in</span> <span m=''5291460''>the</span> <span m=''5291550''>common</span>
  <span m=''5291990''>case,</span> <span m=''5292950''>then,</span> <span m=''5293320''>what</span>
  <span m=''5293440''>happens</span> <span m=''5293940''>is</span> <span m=''5294290''>it</span>
  <span m=''5294530''>basically</span> <span m=''5295380''>has</span> <span m=''5295650''>an</span>
  <span m=''5295880''>access</span> <span m=''5296580''>cost</span> <span m=''5296930''>equal</span>
  <span m=''5297200''>to</span> <span m=''5297270''>one</span> <span m=''5297550''>additional</span>
  <span m=''5298000''>level</span> <span m=''5298270''>of</span> <span m=''5298480''>indirection,</span>
  <span m=''5299450''>which</span> <span m=''5299590''>is</span> <span m=''5299700''>typically</span>
  <span m=''5300150''>an</span> <span m=''5300670''>L1</span> <span m=''5301120''>cache</span>
  <span m=''5301550''>hit.</span> <span m=''5302480''>So</span> <span m=''5302700''>the</span>
  <span m=''5302950''>overhead</span> <span m=''5303780''>of</span> <span m=''5303970''>actually</span>
  <span m=''5304380''>updating</span> <span m=''5305300''>one</span> <span m=''5305460''>of</span>
  <span m=''5305520''>these</span> <span m=''5305760''>things</span> <span m=''5306080''>is</span>
  <span m=''5306180''>really</span> <span m=''5306500''>just</span> <span m=''5306770''>like</span>
  <span m=''5306970''>an</span> <span m=''5307110''>extra</span> <span m=''5308410''>L1</span>
  <span m=''5308810''>cache</span> <span m=''5309220''>hit</span> <span m=''5309520''>for</span>
  <span m=''5309660''>most</span> <span m=''5310010''>of</span> <span m=''5310050''>these</span>
  <span m=''5310320''>things,</span> <span m=''5310600''>for</span> <span m=''5310720''>most</span>
  <span m=''5311100''>of the</span> <span m=''5311540''>time.</span> <span m=''5312160''>If</span>
  <span m=''5312370''>you</span> <span m=''5312490''>have</span> <span m=''5312620''>the</span>
  <span m=''5312720''>case</span> <span m=''5315030''>that</span> <span m=''5315780''>you''re</span>
  <span m=''5315960''>accessing</span> <span m=''5316225''>a</span> <span m=''5316490''>reducer</span>
  <span m=''5317210''>several</span> <span m=''5317580''>times</span> <span m=''5317960''>within</span>
  <span m=''5318120''>the</span> <span m=''5318280''>same</span> <span m=''5318550''>block</span>
  <span m=''5318880''>of</span> <span m=''5318990''>code.</span> </p><p><span m=''5319640''>Otherwise,</span>
  <span m=''5320100''>at</span> <span m=''5320190''>the</span> <span m=''5320270''>very</span>
  <span m=''5320560''>worst,</span> <span m=''5320930''>you</span> <span m=''5321060''>have</span>
  <span m=''5321200''>to</span> <span m=''5321350''>actually</span> <span m=''5321620''>do</span>
  <span m=''5321760''>a</span> <span m=''5321800''>hash</span> <span m=''5322150''>table</span>
  <span m=''5322490''>lookup.</span> <span m=''5323140''>And</span> <span m=''5323250''>that</span>
  <span m=''5324070''>tends</span> <span m=''5324320''>to</span> <span m=''5324400''>be</span>
  <span m=''5324560''>a</span> <span m=''5324630''>little</span> <span m=''5324860''>bit</span>
  <span m=''5325050''>more</span> <span m=''5325280''>like</span> <span m=''5325540''>a</span>
  <span m=''5325610''>function</span> <span m=''5326010''>call</span> <span m=''5326270''>overhead</span>
  <span m=''5327590''>just</span> <span m=''5327830''>in</span> <span m=''5327920''>terms</span>
  <span m=''5328250''>of</span> <span m=''5328380''>order</span> <span m=''5328610''>of</span>
  <span m=''5328670''>magnitude.</span> <span m=''5331180''>Sorry</span> <span m=''5331320''>for</span>
  <span m=''5331520''>running</span> <span m=''5331810''>over.</span> </p>'
uid: b263e817-2511-4d98-eef9-a09440703cdf
---
