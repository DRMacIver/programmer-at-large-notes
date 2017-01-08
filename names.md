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


<ol start=0>
<li>bac</li>
<li>bad</li>
<li>baf</li>
<li>bam</li>
<li>bec</li>
<li>bed</li>
<li>bef</li>
<li>bem</li>
<li>bic</li>
<li>bid</li>
<li>bif</li>
<li>bim</li>
<li>boc</li>
<li>bod</li>
<li>bof</li>
<li>bom</li>
<li>gac</li>
<li>gad</li>
<li>gaf</li>
<li>gam</li>
<li>gec</li>
<li>ged</li>
<li>gef</li>
<li>gem</li>
<li>gic</li>
<li>gid</li>
<li>gif</li>
<li>gim</li>
<li>goc</li>
<li>god</li>
<li>gof</li>
<li>gom</li>
<li>hac</li>
<li>had</li>
<li>haf</li>
<li>ham</li>
<li>hec</li>
<li>hed</li>
<li>hef</li>
<li>hem</li>
<li>hic</li>
<li>hid</li>
<li>hif</li>
<li>him</li>
<li>hoc</li>
<li>hod</li>
<li>hof</li>
<li>hom</li>
<li>jac</li>
<li>jad</li>
<li>jaf</li>
<li>jam</li>
<li>jec</li>
<li>jed</li>
<li>jef</li>
<li>jem</li>
<li>jic</li>
<li>jid</li>
<li>jif</li>
<li>jim</li>
<li>joc</li>
<li>jod</li>
<li>jof</li>
<li>jom</li>
<li>kac</li>
<li>kad</li>
<li>kaf</li>
<li>kam</li>
<li>kec</li>
<li>ked</li>
<li>kef</li>
<li>kem</li>
<li>kic</li>
<li>kid</li>
<li>kif</li>
<li>kim</li>
<li>koc</li>
<li>kod</li>
<li>kof</li>
<li>kom</li>
<li>lac</li>
<li>lad</li>
<li>laf</li>
<li>lam</li>
<li>lec</li>
<li>led</li>
<li>lef</li>
<li>lem</li>
<li>lic</li>
<li>lid</li>
<li>lif</li>
<li>lim</li>
<li>loc</li>
<li>lod</li>
<li>lof</li>
<li>lom</li>
<li>nac</li>
<li>nad</li>
<li>naf</li>
<li>nam</li>
<li>nec</li>
<li>ned</li>
<li>nef</li>
<li>nem</li>
<li>nic</li>
<li>nid</li>
<li>nif</li>
<li>nim</li>
<li>noc</li>
<li>nod</li>
<li>nof</li>
<li>nom</li>
<li>pac</li>
<li>pad</li>
<li>paf</li>
<li>pam</li>
<li>pec</li>
<li>ped</li>
<li>pef</li>
<li>pem</li>
<li>pic</li>
<li>pid</li>
<li>pif</li>
<li>pim</li>
<li>poc</li>
<li>pod</li>
<li>pof</li>
<li>pom</li>
<li>qac</li>
<li>qad</li>
<li>qaf</li>
<li>qam</li>
<li>qec</li>
<li>qed</li>
<li>qef</li>
<li>qem</li>
<li>qic</li>
<li>qid</li>
<li>qif</li>
<li>qim</li>
<li>qoc</li>
<li>qod</li>
<li>qof</li>
<li>qom</li>
<li>rac</li>
<li>rad</li>
<li>raf</li>
<li>ram</li>
<li>rec</li>
<li>red</li>
<li>ref</li>
<li>rem</li>
<li>ric</li>
<li>rid</li>
<li>rif</li>
<li>rim</li>
<li>roc</li>
<li>rod</li>
<li>rof</li>
<li>rom</li>
<li>sac</li>
<li>sad</li>
<li>saf</li>
<li>sam</li>
<li>sec</li>
<li>sed</li>
<li>sef</li>
<li>sem</li>
<li>sic</li>
<li>sid</li>
<li>sif</li>
<li>sim</li>
<li>soc</li>
<li>sod</li>
<li>sof</li>
<li>som</li>
<li>tac</li>
<li>tad</li>
<li>taf</li>
<li>tam</li>
<li>tec</li>
<li>ted</li>
<li>tef</li>
<li>tem</li>
<li>tic</li>
<li>tid</li>
<li>tif</li>
<li>tim</li>
<li>toc</li>
<li>tod</li>
<li>tof</li>
<li>tom</li>
<li>vac</li>
<li>vad</li>
<li>vaf</li>
<li>vam</li>
<li>vec</li>
<li>ved</li>
<li>vef</li>
<li>vem</li>
<li>vic</li>
<li>vid</li>
<li>vif</li>
<li>vim</li>
<li>voc</li>
<li>vod</li>
<li>vof</li>
<li>vom</li>
<li>wac</li>
<li>wad</li>
<li>waf</li>
<li>wam</li>
<li>wec</li>
<li>wed</li>
<li>wef</li>
<li>wem</li>
<li>wic</li>
<li>wid</li>
<li>wif</li>
<li>wim</li>
<li>woc</li>
<li>wod</li>
<li>wof</li>
<li>wom</li>
<li>yac</li>
<li>yad</li>
<li>yaf</li>
<li>yam</li>
<li>yec</li>
<li>yed</li>
<li>yef</li>
<li>yem</li>
<li>yic</li>
<li>yid</li>
<li>yif</li>
<li>yim</li>
<li>yoc</li>
<li>yod</li>
<li>yof</li>
<li>yom</li>
<li>zac</li>
<li>zad</li>
<li>zaf</li>
<li>zam</li>
<li>zec</li>
<li>zed</li>
<li>zef</li>
<li>zem</li>
<li>zic</li>
<li>zid</li>
<li>zif</li>
<li>zim</li>
<li>zoc</li>
<li>zod</li>
<li>zof</li>
<li>zom</li>
</ol>

With the name read off in little endian order. So if the UUID ended FD0B
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
(which may be changed over time by vote but tends to be pretty stable -
you occasionally get votes to include new names encountered in local
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
