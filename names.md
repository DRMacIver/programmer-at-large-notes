# On Naming

Far more than you want to know about how people and ships are named and addressed.

Attention conservation notice: You really don't care about the details in here.

## Identifiers

Naming conventions across the trade fleet vary a bit, but the core addressing
system remains constant:

Every member of the trade fleet past or present has
a UUID (in the lineage of the ship in the story these are extended UUIDs with
extra bits. This convention has not become entirely universal - some people are
still on old UUIDs because they consider the switchover not really worth the
hassle for the very low chance of collision and some people have switched over
to an entirely different identifier system. This occasionally causes interoperability
problems when ships meet).

Every ship also has a unique identifier, typically of the same format as individuals.

## Ship-local addressing

When generating new crewmembers UUIDs the ship ensures that the two least significant
bytes (which are random) are unique amongst living crewmembers. This allows people to
be addressed in casual mode by the last two bytes.

When this is done the bytes are pronounced as follows ([taken from here](http://hewo.xedoloh.com/2015/04/base-256/)):

0. bac
1. bad
2. baf
3. bam
4. bec
5. bed
6. bef
7. bem
8. bic
9. bid
10. bif
11. bim
12. boc
13. bod
14. bof
15. bom
16. gac
17. gad
18. gaf
19. gam
20. gec
21. ged
22. gef
23. gem
24. gic
25. gid
26. gif
27. gim
28. goc
29. god
30. gof
31. gom
32. hac
33. had
34. haf
35. ham
36. hec
37. hed
38. hef
39. hem
40. hic
41. hid
42. hif
43. him
44. hoc
45. hod
46. hof
47. hom
48. jac
49. jad
50. jaf
51. jam
52. jec
53. jed
54. jef
55. jem
56. jic
57. jid
58. jif
59. jim
60. joc
61. jod
62. jof
63. jom
64. kac
65. kad
66. kaf
67. kam
68. kec
69. ked
70. kef
71. kem
72. kic
73. kid
74. kif
75. kim
76. koc
77. kod
78. kof
79. kom
80. lac
81. lad
82. laf
83. lam
84. lec
85. led
86. lef
87. lem
88. lic
89. lid
90. lif
91. lim
92. loc
93. lod
94. lof
95. lom
96. nac
97. nad
98. naf
99. nam
100. nec
101. ned
102. nef
103. nem
104. nic
105. nid
106. nif
107. nim
108. noc
109. nod
110. nof
111. nom
112. pac
113. pad
114. paf
115. pam
116. pec
117. ped
118. pef
119. pem
120. pic
121. pid
122. pif
123. pim
124. poc
125. pod
126. pof
127. pom
128. qac
129. qad
130. qaf
131. qam
132. qec
133. qed
134. qef
135. qem
136. qic
137. qid
138. qif
139. qim
140. qoc
141. qod
142. qof
143. qom
144. rac
145. rad
146. raf
147. ram
148. rec
149. red
150. ref
151. rem
152. ric
153. rid
154. rif
155. rim
156. roc
157. rod
158. rof
159. rom
160. sac
161. sad
162. saf
163. sam
164. sec
165. sed
166. sef
167. sem
168. sic
169. sid
170. sif
171. sim
172. soc
173. sod
174. sof
175. som
176. tac
177. tad
178. taf
179. tam
180. tec
181. ted
182. tef
183. tem
184. tic
185. tid
186. tif
187. tim
188. toc
189. tod
190. tof
191. tom
192. vac
193. vad
194. vaf
195. vam
196. vec
197. ved
198. vef
199. vem
200. vic
201. vid
202. vif
203. vim
204. voc
205. vod
206. vof
207. vom
208. wac
209. wad
210. waf
211. wam
212. wec
213. wed
214. wef
215. wem
216. wic
217. wid
218. wif
219. wim
220. woc
221. wod
222. wof
223. wom
224. yac
225. yad
226. yaf
227. yam
228. yec
229. yed
230. yef
231. yem
232. yic
233. yid
234. yif
235. yim
236. yoc
237. yod
238. yof
239. yom
240. zac
241. zad
242. zaf
243. zam
244. zec
245. zed
246. zef
247. zem
248. zic
249. zid
250. zif
251. zim
252. zoc
253. zod
254. zof
255. zom

With the name read off in least signifcant form. So if the UUID ended FD0B
(253, 11), then their casual address would be zod(11)-bim(253).

People can and do use casual address in person, but it's considered a
bit weird and formal. Think of it as equivalent to referring to you by
your full name and title.

Shortening someone's casual address to the least significant byte is considered
*very bad manners*. Do not refer to zod-bim as zod.

The casual address convention is quite common in the trade fleet, though
not everyone pronounces the byte values the same way.

People sometimes use extended casual address when needing a referent that
is globally unique across all crew members present or past. This is the
casual address followed by the number of people who have had that casual
address. For example zod-bim might be disambiguated as zod-bim 7 if there
were 6 previous crew members identifiable as zod-bim.

## Use names

People shipboard can also register one or more *use names*, which are
the ones most people will refer to them as on a day to day basis.

No two current crew members can register the same use name, and having
a registered use name is not required (but is considered a bit weird and
subtly disapproved of).

Newborn babies are assigned a use name at random from a standard pool
(which may be changed over time by vote but tends to be pretty stable
- you occasionally get votes to include new names encountered in local
cultures that people think are cool, and sometimes names held by
particularly disgraced crew members are voted out of the pool).

It's considered quite normal to discard your given use name once you
qualify to full crew member - about two thirds of the population do it.

Typically people will have at least two use names registerd along with
preferences for how you should use them - e.g. a friends use name and a
formal use name.

Some people remain quite stable in their use names over their life while
some like to change them on a regular basis. HUD technology and active cues
make it relatively easy to keep track of what use name you should be using
for someone.

Certain use names are reserved for special positions. You may not take the
use name Captain unless you are actually the captain (but the captain does
not always take it either). The rules are a relatively complex system of
classification (you can't call yourself "Captain Jack Sparrow" if you're not
the Captain either, but nor can you call yourself El Capitan, or Centurio).
You can always appeal by taking it to a vote, but it will cost to do this.
Most people don't bother and pick simple and uncontroversial names.

## Ship names

Ships are named at time of creation though may change over their lifetime.
Names are normally a meaningful phrase although tend to stop short of full
blown Culture ship naming conventions.

The ship in the story is named "Eschaton Arbitrage" (profiting from the
fact that different civilizations have their apocalypse at different times).

The crew generally agree that this is in poor taste, but the constitution
makes changing ship names moderately tricky - you need a 73% majority for
a replacement name, and nobody has been able to come up with a name they
like better.

Names are best-effort globally unique: When traders meet they synchronize
their ship databases, and if they notice a ship of a different identifier
which has ever had the same name as their current ship name they must
change names to one they know to be unique.

The name-change faction keep hoping to run into another ship called Eschaton
Arbitrage, but so far no luck.

(Violations of this policy occasionally occur, but it's embedded at the
constitution at an early enough level that anyone that forked before then
hardly counts as the same trade fleet, and people who have changed that
part of their constitution are generally regarded as jerks and are less
likely to be cooperated with).

When needing to refer to a ship uniquely in casual conversation you
would typically use however many of the least significant set of bytes
in their identifier are required to disambiguate it in the local database
(together with a version number for the local database if you want to
be *really* precise), but because of the practice of keeping ship names
distinct this rarely comes up except in historical documents.

## Honorifics

There are no honorifics in the trade fleet.

## Intership name usage

Ship names are used as patronymics when referring to crew in a broader
context. Zod-bim 7 could be more fully referred to as "Zod-bim 7 off the
Eschaton Arbitrage (yom-sic-tem as of database revision 54992).

This is both the trade fleet convention but also matches typical local
usage of patronymics: Essentially everyone aboard a ship is related to
some greater or lesser degree, except for the relatively small fraction
of first generation crew (typically well under 1%).
