---
title: "SAV: Informace pro studenty"
lang: cs
---

# [Statická analýza a verifikace](https://www.fit.vut.cz/study/course/SAV)
{: .no_toc }

zimní semestr 2026/2027
{: .page-subtitle }

<div id="page-toc" markdown="block">
- TOC
{:toc}
</div>

---

(původní stránka byla převzata po T. Vojnarovi)

## Informace, termíny

*Zde se objevují upozornění na nové závažné informace, blížící se termíny apod.*

* **Stream z přednášek** bude (snad) k dispozici na [YouTube](https://www.youtube.com/playlist?list=XXXXXXXXXXXXXXXXXXXXX).

---

## Projekt

Informace o projektu budou k dispozici.

* **Cílem projektu** je bližší seznámení se s vybraným nástrojem pro statickou analýzu a/nebo verifikaci a principy, na nichž je založen, reprodukce dostupných případových studií pro zvolený nástroj (ideálně s nějakými modifikacemi, aby se ověřilo, jak moc je nástroj vyladěn jen pro dané úlohy), vlastní experimenty s uvedeným nástrojem. Výjimečně lze akceptovat i nástroj pro dynamickou analýzu, který je založen na netriviálních formálních kořenech. Lze také experimentovat s "podpůrnými" nástroji např. pro SAT/SMT solving, práci s BDD, automaty, apod.

* Projekt je za **30 bodů** celkem. Výsledky projektů se odevzdávají formou technické zprávy, která bude mít tři hlavní části:

  1. **Popis nástroje**, přičemž důraz je na **matematické/algoritmické/věcné principy**, na kterých nástroj stojí. Použití nástroje z uživatelského pohledu je možno uvést, ale v míře spíše menší, ideálně jako odrazový můstek pro popis principů.
  2. **Popis reprodukovaných experimentů**: jaké experimenty byly reprodukovány, s jakými výsledky, k jakým pokusům o modifikace došlo, jak dopadly. (Pokud žádné stávající experimenty nejsou dostupné, je možno je nahradit větším důrazem na níže uvedený bod.)
  3. **Popis vlastních originálních experimentů**: ideálně nad školními projekty, volně dostupným software apod. (Uměle vytvořené příklady jsou možné, ale ne úplně ideální, pokud neukazují něco zcela zásadního. Pouhá modifikace parametrů či dílčích částí stávajících experimentů spadá do výše uvedeného bodu.)

  Každá část cca 3–-5 stran v podobném formátu jako diplomová práce, každá za 10 bodů, hodnoceno dle míry zpracování a originality. Při přípravě lze užít libovolné LLM, **ALE** je na Vás, abyste AI uřídili tak, že mi poskytne stručné, relevantní a pravdivé informace, které mi umožní se rychle zorientovat (za předpokladu nulové znalosti daného nástroje a jeho principů). Jinými slovy: nechci číst žádnou reklamu, nechci číst nic zbytečného, žádný AI slop, ale také chci vše dostatečně a rychle pochopit.

* Do **BUDE UPŘESNĚNO je nutno registrovat nástroje**, na které se jednotliví studenti zaměří (jde zejména o kontrolu toho, zda se projekt zaměřený na daný nástroj dá rozumně řešit---pokud si vyberete triviální nástroj, budete zřejmě mít problémy o něm něco zajímavého sepsat). Registraci proveďte zasláním e-mailu [O. Lengálovi](mailto:lengal@fit.vutbr.cz).

* Termín odevzdání vypracované technické zprávy v pdf přes IS VUT/Moodle **BUDE UPŘESNĚN**.  <!-- **19. 12. 2025 12:00 CET**. -->

* Průběžně doplňovaný seznam zaregistrovaných studentů pro řešení projektu je uveden [ZDE](XXXXXXXXXXXXXXX).

* **Prémiové body** (až 10 za vynikající výkon): Analýza zaměřená na kód Linuxového jádra (či jiného otevřeného OS) či některého reálného open source software, zejména v případě nalezení reálných nareportovaných chyb.

* **Odevzdání projektu:** přes elearning (Moodle) VUT. Odevzdat je nutno pdf soubor technické zprávy a volitelně zip/tgz s provedenými experimenty a jejich výsledky.

---

## Přednášky

* [Úvod, základní pojmy](XXXXXXXXXXXXXXXXXX)

další přednášky budou průběžně doplňovány

<!--
* [Logiky CTL*, CTL, LTL (a lehký úvod do explicitního CTL model checkingu)](OLD-2025/Lectures/2025/sav-lecture-02.pdf)
* [LTL model checking, Büchiho automaty](OLD-2025/Lectures/2025/sav-lecture-03-ltl-mc.pdf) ([bez overlayů](OLD-2025/Lectures/2025/sav-lecture-03-ltl-mc-fast.pdf))
* [Predikátová abstrakce](OLD-2025/Lectures/2025/sav-lecture-04.pdf) + [příklad na procvičení predikátové abstrakce](OLD-2025/Lectures/2025/SAV-priklad-predikatova-abstrakce.pdf)
* [Abstraktní interpretace](OLD-2025/Lectures/2025/sav-lecture-05.pdf), [svazy](OLD-2025/Lectures/2025/sav-lecture-05b.pdf), [redukovaný produkt (F. Nečas)](OLD-2025/Lectures/2025/reduced-product.pdf) + [příklad na procvičení abstraktní interpretace](OLD-2025/Lectures/2025/SAV-priklad-abstraktni-interpretace.pdf)
* [Deduktivní verifikace](OLD-2025/Lectures/2025/sav-lecture-06.pdf)
* [Symbolická exekuce](OLD-2025/Lectures/2025/sav-lecture-07-symbolic-execution.pdf) ([bez overlayů](OLD-2025/Lectures/2025/sav-lecture-07-symbolic-execution-fast.pdf))
* [Binární rozhodovací diagramy](OLD-2025/Lectures/2025/sav-lecture-08-bdds.pdf)
* [Řešení SAT a SMT problémů](OLD-2025/Lectures/2025/sav-lecture-09.pdf)
* [Analýza toku dat, ukazatelové analýzy](OLD-2025/Lectures/2025/sav-lecture-10.pdf) + [příklad na procvičení analýzy toku dat](OLD-2025/Lectures/2025/SAV-priklad-analyza-toku-dat.pdf)
-->

### Demonstrační příklady -- mimo již výše uvedené

* v případě potřeby bude průběžně doplňováno
<!-- - [Predikátová abstrakce, LTL a Büchiho automaty, BDDs, abstraktní interpretace, analýza toku dat](OLD-2025/Lectures/2025/SAV-procviceni-PA-BA-BDD-AI-DFA.pdf) -->

---

## Monografie, přehledové články

### Doporučený základ

- B. Křena, T. Vojnar. [Automated Formal Analysis and Verification: An Overview](https://www.fit.vut.cz/person/vojnar/public/Publications/ijgs-13.pdf). International Journal of General Systems, 42(4):335-365, Taylor and Francis, 2013. -- *stručný přehled celé oblasti, volně dostupný -- dobrý první text*
- A. Møller, M.I. Schwartzbach. [Static Program Analysis](https://cs.au.dk/~amoeller/spa/). Aarhus University, 2026. -- *volně dostupné skriptum: analýza toku dat, ukazatelové analýzy*
- C. Baier, J.-P. Katoen. [Principles of Model Checking](https://mitpress.mit.edu/books/principles-model-checking). MIT Press, 2008. -- *standardní učebnice model checkingu: CTL/LTL, Büchiho automaty*
- X. Rival, K. Yi. [Introduction to Static Analysis: An Abstract Interpretation Perspective](https://mitpress.mit.edu/books/introduction-static-analysis). MIT Press, 2020. -- *abstraktní interpretace od základů*
- A.R. Bradley, Z. Manna. [The Calculus of Computation: Decision Procedures with Applications to Verification](https://link.springer.com/computer/theoretical+computer+science/book/978-3-540-74112-1). Springer, 2007. -- *deduktivní verifikace, Hoareova logika, rozhodovací procedury*
- D. Kroening, O. Strichman. [Decision Procedures: An Algorithmic Point of View](https://www.decision-procedures.org/). Springer, 2016. -- *SAT a SMT solving algoritmicky*

<details markdown="block">
  <summary>Další literatura (13 titulů)</summary>

- E.M. Clarke, T.A. Henzinger, H. Veith, R. Bloem (Eds.). [Handbook of Model Checking](https://link.springer.com/book/9783319105741). Springer, 2018.
- E.M. Clarke, O. Grumberg, D. Kroening, D. Peled, H. Veith. [Model Checking](https://mitpress.mit.edu/books/model-checking-second-edition), 2nd edition. MIT Press, 2018.
- G.J. Holzmann. [The SPIN Model Checker: Primer and Reference Manual](https://dl.acm.org/doi/10.5555/1405716). Addison-Wesley Professional, 2003.
- M. Ben-Ari. [Principles of the Spin Model Checker](https://dl.acm.org/doi/10.5555/1349767). Springer, 2008.
- A. Valmari. [The State Explosion Problem](https://link.springer.com/chapter/10.1007/3-540-65306-6_21). Lectures on Petri Nets I: Basic Models, Lecture Notes in Computer Science 1491, Springer-Verlag 1998, pp. 429-528. (starší, ale stále zajímavé)

- F. Nielson, H.R. Nielson, C. Hankin. [Principles of Program Analysis](https://link.springer.com/book/9783540654100). Springer-Verlag, 2005.
- U. Khedker, A. Sanyal, B. Sathe. [Data Flow Analysis: Theory and Practice](https://www.cse.iitb.ac.in/~uday/dfaBook-web/). CRC Press, 2009. Na stránce jsou k dispozici také odpovídající slajdy.
- A.V. Aho, M.S. Lam, R. Sethi, J.D. Ullman. [Compilers: Principles, Techniques, and Tools](http://dragonbook.stanford.edu/). Addison Wesley, 2nd ed., 2006. Část věnovaná statické analýze.
- B. Chess, J. West. [Secure Programming with Static Analysis](https://dl.acm.org/doi/10.5555/1406221). Addison-Wesley Professional, 2007.

- A. Biere, M. Heule, H. Van Maaren, T. Walsh (Eds.). [Handbook of Satisfiability](https://www.iospress.com/catalog/books/handbook-of-satisfiability-2), 2nd edition. IOS Press, 2021.

- Y. Bertot, P. Castéran. [Interactive Theorem Proving and Program Development: Coq'Art: The Calculus of Inductive Constructions](https://www.labri.fr/perso/casteran/CoqArt/index.html). Springer, 2010.
- B.C. Pierce. [Types and Programming Languages](https://www.cis.upenn.edu/~bcpierce/tapl/). MIT Press, 2002.
- B.C. Pierce (Ed.). [Advanced Topics in Types and Programming Languages](https://www.cis.upenn.edu/~bcpierce/attapl/). MIT Press, 2004.

</details>

---

## Nástroje

*Upozornění: (1) Níže jsou uvedeny jen některé příklady existujících nástrojů, v žádném případě se nejedná o úplný seznam! (2) Uvedené krátké charakteristiky nebyly vždy získány na základě vlastní zkušenosti s příslušným nástrojem a nemusí být přesné -- naleznete-li nějakou nepřesnost či rozpor, prosím napište mi.*

Zajímavý "experience report": M. Dodds. [What Works (and Doesn't) Selling Formal Methods](https://www.galois.com/articles/what-works-and-doesnt-selling-formal-methods)

[Competition on Software Verification (SV-COMP)](http://sv-comp.sosy-lab.org/) -- mezinárodní soutěž ve verifikaci SW

### Model checking

- [Spin](http://spinroot.com/spin/whatispin.html) -- verifikace (nejen) distribuovaných SW systémů, vstupem je specializovaný modelovací jazyk Promela (existují překladače do Promely z některých dalších jazyků)

- [CPAchecker](http://cpachecker.sosy-lab.org/) -- konfigurovatelný nástroj pro verifikaci software, zahrnuje model checking založený na predikátové abstrakci a interpolaci
- [CBMC](http://www.cprover.org/cbmc/) -- omezený model checking C programů
- [ESBMC](https://github.com/esbmc/esbmc) -- omezený model checking C programů
- [Smack](http://smackers.github.io/) -- omezený model checking C programů v kombinaci s řadou dalších analýz
- [Blast](http://mtc.epfl.ch/software-tools/blast/index-epfl.php) -- verifikace C programů (již starší nástroj), základem je predikátová abstrakce a interpolace, nová verze je dostupná [zde](http://forge.ispras.ru/projects/blast/) v rámci projektu Linux Driver Verification
- [Divine](http://divine.fi.muni.cz/) -- model checking v paralelním a distribuovaném prostředí s využitím řady vstupních formátů (včetně C/C++)
- [2LS](https://github.com/diffblue/2ls) -- open source analyzátor spojující principy omezeného model checkingu, k-indukce a abstraktní interpretace vyvíjené i na **FIT VUT**
- [DiffBlue](http://www.diffblue.com/) -- firma stojící za komercionalizací a dalším rozvojem např. CBMC či 2LS
- [Ultimate Automizer](http://ultimate.informatik.uni-freiburg.de/automizer/) -- C model checker využívající predikátové abstrakce a teorie automatů

- [Java PathFinder -- JPF](https://github.com/javapathfinder) -- verifikace a testování Java programů (viz i dále zmíněné nástroje s ním spojené)
- [JBMC](http://www.cprover.org/jbmc/) -- omezený model checking Java programů
- [Lincheck](https://kotlinlang.org/docs/home.html) -- omezený model checking a stress testing paralelních Java/Scala/Kotlin programů

- [Kani](https://github.com/model-checking/kani) -- omezený model checking Rust programů (AWS)

- [JKind](http://loonwerks.com/tools/jkind.html) -- nekonečně stavový model checking synchronních systémů popsaných v jazyce Lustre

- [NuSMV a NuXMV](http://nusmv.fbk.eu/) -- symbolický model checking (nejen) HW
- [ABC](http://www.eecs.berkeley.edu/~alanmi/abc/) -- systém pro syntézu a verifikaci HW (zahrnuje omezený model checking, včetně různých pokročilých technik vycházejících ze základních myšlenek BMC)
- [Cadence Verification](http://www.cadence.com/products/fv/pages/default.aspx) -- komerční nástroj pro verifikaci hardware od Cadence
- [Questa Formal Verification Apps](https://www.mentor.com/products/fv/questa-formal-verification-apps) -- verifikace HW, Mentor Graphics
- [Static and Formal Verification at Synopsys](https://www.synopsys.com/verification/static-and-formal-verification.html) -- verifikace HW, Synopsys
- [Oski/NVIDIA](https://blogs.nvidia.com/blog/2021/10/08/oski-formal-verification/) -- společnost neprodukovala přímo nástroj, ale nabízela verifikaci s využitím model checkingu
- [EBMC](https://www.cprover.org/ebmc/web/) -- omezený model checking pro Verilog (vychází ze CBMC)

- [Uppaal](http://www.uppaal.com/) -- model checking RT systémů popsaných časovanými automaty

- [Prism](http://www.prismmodelchecker.org/) -- pravděpodobnostní model checker nad Markovskými systémy
- [Storm](http://www.stormchecker.org/) -- pravděpodobnostní model checker nad Markovskými systémy, syntéza pravděpodobnostních systémů (spolupráce i s **FIT VUT**)

- [ProB](https://prob.hhu.de/w/index.php?title=Main_Page) -- model checker podporující metodu B pro vývoj vestavěných kritických systémů (aplikace např. v oblasti vlaků, metra apod.: Alstom, ClearSy, Siemens, Thales)

- [TTool](https://ttool.telecom-paristech.fr/) -- simulační i formální verifikace spolehlivosti (safety), bezpečnosti (security) i výkonnosti vestavěných systémů modelovaných pomocí SysML/UML s využitím model checkingu i automatizovaného dokazování teorémů (security, kryptografie)

- [nidhugg](https://github.com/nidhugg/nidhugg) -- stateless model checking pro paralelní programy se slabými paměťovými modely
- [Concuerror](https://concuerror.com) -- stateless model checking pro paralelní programy v jazyce Erlang

- [TLA+](https://lamport.azurewebsites.net/tla/tla.html) -- jazyk pro modelování systémů a protokolů a prostředí s model checkerem pro jejich verifikaci
- [Apalache](https://github.com/apalache-mc/apalache) -- symbolický model checking TLA+ vysoko-úrovňových specifikací systémů ([Informal Systems](https://github.com/informalsystems))

- ...

### Statická analýza, analýza toku dat, abstraktní interpretace, symbolická exekuce, ...

- [Přehled nástrojů pro statickou/dynamickou analýzu C kódu](http://www.spinroot.com/static/)
- [Seznam nástrojů pro statickou analýzu na Wikipedii](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis)
- [Zajímavé srovnání některých nástrojů pro statickou analýzu](http://delab.csd.auth.gr/~katsaros/STPSA_2011.pdf)

- [Synopsys Static Analysis](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) -- komerční nástroje pro statickou analýzu C/C++/Java (chybové vzory, analýza toku dat, vylučování nereálných chyb), dříve Coverity
- [Klocwork](http://www.klocwork.com/products/insight/index.php) -- komerční nástroje pro statickou analýzu C/C++/Java/C# (chybové vzory, analýza toku dat, vylučování nereálných chyb)
- [CodeSonar](https://codesecure.com/our-products/codesonar/) -- komerční nástroje pro statickou analýzu C/C++ (chybové vzory, analýza toku dat, vylučování nereálných chyb)
- [Microsoft Code analysis for C/C++](https://docs.microsoft.com/en-us/visualstudio/code-quality/code-analysis-for-c-cpp-overview?view=vs-2017) -- statická analýza vestavěná do VisualStudia, (zřejmě) chybové vzory a symbolická exekuce založená na využití SMT (Z3), možnost anotací
- [Parfait](https://labs.oracle.com/pls/apex/f?p=LABS:project_details:0:13) -- interní nástroj v rámci Oracle, analýza toku dat, chybové vzory, ...
- [Frama-C](https://frama-c.com/) -- nástroj zahrnující abstraktní interpretaci pro C i deduktivní verifikaci C kódu anotovaného ACSL od francouzské agentury pro atomovou energii (CEA)
- [Facebook/Meta Infer](http://fbinfer.com/) -- komerční (ale open source) nástroj založený na abstraktní interpretaci zaměřený na vybrané typy chyb
- [Pluginy pro Facebook Infer a Frama-C](http://www.fit.vutbr.cz/research/groups/verifit/tools/sa-plugins/) vyvíjené na **FIT VUT**
- [MOPSA analyzer](https://gitlab.com/mopsa/mopsa-analyzer) -- akademický framework pro tvorbu statických analyzátorů, hodně modulární, postavený na abstraktní interpretaci a napsaný v OCamlu (verze v prohlížeči: [link](https://try-mopsa.rmonat.fr/))
- [Facebook SPARTA](https://code.fb.com/open-source/sparta/) -- komerční (ale open source) prostředí pro tvorbu abstraktních interpretací používané např. v optimalizátoru ReDex pro Android
- [PhASAR](https://phasar.org) -- prostředí pro tvorbu inter-procedurálních statických analýz nad C/C++ s důrazem na analýzu toku dat
- [SeaHorn](https://seahorn.github.io/) -- framework pro analýzu programů postavený nad LLVM využívající překladu programů do Hornových klauzulí a jejich následné řešení

- [Coderrect Scanner](https://coderrect.com) -- statická analýza (ukazatelová analýza, analýza toku dat) specializovaná pro detekci chyb typu "data race"

- [Slam](http://www.research.microsoft.com/slam/) a [Static Driver Verifier](https://docs.microsoft.com/en-us/windows-hardware/drivers/devtest/static-driver-verifier) -- verifikace driverů v MS Windows, dříve s využitím predikátové abstrakce, nyní s využitím symbolické exekuce založené na SMT
- [KLEE](http://klee.llvm.org/) -- kombinace statické analýzy založené na symbolickém provádění a testování
- [Symbiotic](https://github.com/staticafi/symbiotic) -- kombinuje instrumentaci kódu o monitory sledující verifikované vlastnosti, slicing a symbolickou exekuci (existuje i kombinace s nástrojem [Predator](http://www.fit.vutbr.cz/research/groups/verifit/tools/predator/))
- [SymbolicPathFinder (SPF)](https://github.com/SymbolicPathFinder/jpf-symbc) -- rozšíření výše uvedeného nástroje JPF pro symbolickou exekuci Java programů
- [Java Ranger](https://github.com/vaibhavbsharma/java-ranger) -- úprava výše uvedeného nástroje SPF s podporou slučování symbolických cest
- [JDart](https://github.com/tudo-aqua/jdart) -- úprava výše uvedeného nástroje JPF pro konkolické provádění
- [Gillian](https://gillianplatform.github.io) -- separační logika, symbolické provádění pro JavaScript a C
- [CrossHair](https://github.com/pschanely/CrossHair) -- statická i dynamická analýza pro Python, symbolická a konkolická exekuce, fuzzing, ...

- [Certora Prover](https://www.certora.com/prover) -- symbolická exekuce pro formální verifikaci smart kontraktů (Certora). K dispozici také další nástroje: fuzz testing.

- [FindBugs](http://findbugs.sourceforge.net) -- volně dostupný nástroj pro statickou analýzu Javy (chybové vzory, analýza toku dat)
- [SpotBugs](https://spotbugs.github.io/) -- nástupce FindBugs
- [Clang Static Analyzer](http://clang-analyzer.llvm.org/) -- statický analyzátor pro C a Objective C, využívá chybové vzory, analýzu toku dat
- [Statická analýza v GCC](https://gcc.gnu.org/wiki/StaticAnalyzer) -- statická analýza založená na chybových vzorech (např. double-free, use-after-free) v rámci gcc
- [SonarQube](https://www.sonarqube.org/) -- analýza toku dat a chybové vzory pro vybrané chyby v kódu i zranitelnosti z hlediska bezpečnosti nad řadou různých jazyků
- [Cppcheck](http://cppcheck.sourceforge.net/) -- statický analyzátor pro C/C++, relativně jednoduché vyhledávání chybových vzorů v toku řízení
- [cppclean](http://code.google.com/p/cppclean/) -- statická analýza programu v C++, vyhledávání chybových vzorů nad AST
- [Sparse](http://en.wikipedia.org/wiki/Sparse) -- statická analýza pro jádro Linuxu

- [PHPStan](https://phpstan.org) -- statická analýza php

- [Cobra](https://space-ros.github.io/docs/rolling/Related-Projects/Cobra.html) -- interaktivní lightweight statická analýza zaměřená na vyhledávání chybových vzorů ve velmi velkých programech (od G. Holzmanna, autora Spinu, použito mj. v NASA)
- [OpenScanHub](https://openscanhub.dev) -- lightweight statická analýza i dynamická analýza, obaluje řadu nástrojů jako cppcheck a zpřístupňuje je přátelsky vývojářům (použito mj. při vývoji RHEL)
- [DiffKemp](https://github.com/viktormalik/diffkemp) -- využití statické analýzy pro ověřování, zda při refaktoringu nedochází k nežádoucím změnám sémantiky, aplikováno např. na jádro RHEL či GNU Linux (spolupráce **Red Hat a FIT VUT**)

- [AbsInt](http://www.absint.com) a [Astrée](http://www.astree.ens.fr/) -- komerční nástroje pro statickou analýzu (abstraktní interpretaci) vestavěných systémů, zejména analýzu časování, práce se zásobníkem a ověřování absence runtime chyb (spolehlivá)
- [PolySpace](http://www.mathworks.com/products/polyspace/?s_cid=wiki_polyspace_2) -- komerční nástroje pro statickou analýzu vestavěných systémů reálného času v C, C++, Adě (abstraktní interpretace)

- [Daisy](https://github.com/malyzajko/daisy) -- analýza toku dat a analýza založená na optimalizačních problémech pro analýzu a optimalizaci numerických programů

- [TAJS](http://www.brics.dk/TAJS/) -- statická analýza pro JavaScript

- [gdfa: A Generic Data Flow Analyzer for GCC](http://www.cse.iitb.ac.in/grc/index.php?page=gdfa) -- jednoduché generické prostředí pro tvorbu analýz toku dat (demonstrující principy z knihy Uday P. Khedker, Amitabha Sanyal, Bageshri Karkare: Data Flow Analysis: Theory and Practice)

- [Predator](http://www.fit.vutbr.cz/research/groups/verifit/tools/predator/) -- nástroj pro verifikaci C programů zaměřený na manipulaci s dynamickými datovými strukturami z **FIT VUT** (využívá grafy, v principu založen na separační logice)
- [Forester](http://www.fit.vutbr.cz/research/groups/verifit/tools/forester/) -- starší, již nevyvíjený nástroj pro verifikaci C programů zaměřený na manipulaci s dynamickými datovými strukturami z **FIT VUT** (založen na stromových automatech)

- [AProVE](http://aprove.informatik.rwth-aachen.de) -- kombinace abstraktní interpretace pro ověření korektnosti práce s pamětí a vystavění abstraktního modelu, následovaná různými technikami pro dokazování konečnosti/složitosti běhu (s využitím SMT)

- [Loopus](http://forsyte.at/software/loopus/) -- statická analýza zaměřená na automatickou analýzu složitosti u celočíselných programů v C (viz i jeho reinkarnace v rámci prostředí Infer -- pluginy pro Infer z **FIT VUT**)

- ...

### Theorem proving, SAT solving, SMT solving, rozhodovací procedury

- [PVS](http://pvs.csl.sri.com/) -- interaktivní theorem prover
- [Coq](http://coq.inria.fr/) -- interaktivní theorem prover
- [HOL](http://www.cl.cam.ac.uk/research/hvg/HOL/) -- interaktivní theorem prover
- [ACL2](http://www.cs.utexas.edu/users/moore/acl2/) -- interaktivní theorem prover
- [Lean](https://leanprover.github.io/) -- interaktivní theorem prover

- [Vampire](https://vprover.github.io) -- plně automatický theorem prover pro predikátovou logiku s řadou dalších zajímavých funkcionalit (výpočet interpolantů apod.)

- [SAT Competition](http://www.satcompetition.org/) -- soutěž o nejlepší nástroj pro řešení SAT problému
- [MapleSAT](https://maplesat.github.io/solvers.html)
- [Kissat SAT Solver](http://fmv.jku.at/kissat/)
- [CaDiCaL](http://fmv.jku.at/cadical/)

- [SMT-Comp](http://www.smtcomp.org/) -- soutěž o nejlepší nástroj pro řešení problémů SMT (SAT modulo teorie)
- [Z3](https://github.com/Z3Prover/z3)
- [MathSAT](http://mathsat.fbk.eu/)
- [CVC5](https://cvc5.github.io/)
- [Yices2](http://yices.csl.sri.com/)
- [Boolector](http://fmv.jku.at/boolector/)
- [SMTInterpol](http://ultimate.informatik.uni-freiburg.de/smtinterpol/)
- [what4](https://galois.com/blog/2020/07/what4-new-library-to-help-devs-build-verification-program-tools/) -- knihovna pro tvorbu analyzátorů nad SMT

- [Z3str3RE](https://z3string.github.io/z3str3RE/readme.html) a [Z3str4](https://z3str4.github.io/) -- nástroje pro ověřování splnitelnosti formulí nad řetězci postavené nad SMT solverem Z3
- [Noodler](https://github.com/VeriFIT/Z3-Noodler) -- nástroj pro ověřování splnitelnosti formulí nad řetězci (vyvíjený na **FIT VUT**)
- [Retro](https://github.com/VeriFIT/retro) -- nástroj pro ověřování splnitelnosti formulí nad řetězci (vyvíjený na **FIT VUT**)
- [Z3-Trau](https://github.com/diepbp/z3-trau) -- nástroj pro ověřování splnitelnosti formulí nad řetězci (spolupráce s **FIT VUT**)
- [Sloth](https://github.com/uuverifiers/sloth) -- nástroj pro ověřování splnitelnosti formulí nad řetězci (spolupráce s **FIT VUT**)
- [Ostrich](https://github.com/uuverifiers/ostrich) -- nástroj pro ověřování splnitelnosti formulí nad řetězci

- [MONA](https://github.com/cs-au-dk/MONA) -- nástroj pro ověřování platnosti formulí logik WS1S a WS2S (jde o slabé monadické logiky druhého řádu, používáné často pro usuzování např. o stromových datových strukturách)

- [SL-COMP](https://sl-comp.github.io) -- soutěž o nejlepší nástroj pro splnitelnost/inkluze formulí separační logiky (vhodná pro popis konfigurací programů s ukazateli a dynamickými datovými strukturami)
- [Astral](https://github.com/TDacik) -- nástroj pro rozhodování silně-separační logiky (vyvíjený na **FIT VUT**)
- [Facebook/Meta Infer Biabduction](https://fbinfer.com/docs/checker-biabduction) -- nástroj založený na separační logice a tzv. bi-abdukci pro programy s ukazateli a seznamy
- [Broom](https://pajda.fit.vutbr.cz/rogalew/broom/-/tree/v0.0.1) -- první prototyp nástroje založený na separační logice a bi-abdukci pro programy s ukazateli, seznamy a nízko-úrovňovou manipulací s pamětí (vyvíjený na **FIT VUT**)

- [VCC](http://research.microsoft.com/en-us/projects/vcc/) -- verifikace anotovaných programů v C
- [Nagini](https://github.com/marcoeilers/nagini) -- verifikace anotovaných programů v Pythonu
- [ESC/Java2](http://kindsoftware.com/products/opensource/ESCJava2/) -- verifikace anotovaných programů v Javě

- ...

### Automaty nad nekonečnými slovy

- [Spot](https://spot.lrde.epita.fr/) -- knihovna a toolbox pro práci s automaty nad nekonečnými slovy, LTL formulemi, hrami, syntézu a model checking (včetně Jupyter bindingu pro interaktivní práci)
- [Ranker](https://github.com/vhavlena/ranker) -- nástroj pro rank-based komplementaci Büchiho automatů (vyvíjený na **FIT VUT**)
- [Kofola](https://github.com/VeriFIT/kofola) -- nástroj pro decomposition-based komplementaci Büchiho automatů (vyvíjený na **FIT VUT**)
- [GOAL](http://goal.im.ntu.edu.tw/wiki/doku.php) -- Java knihovna a GUI pro interaktivní práci s automaty nad nekonečnými slovy
- [Tempus Fugit](https://benkeks.itch.io/tempusfugit) -- počítačová hra učící základy temporální logiky LTL

### BDD

- [CUDD](https://github.com/ivmai/cudd) -- knihovna pro práci s BDD a jejich variantami
- [BuDDy](https://github.com/jgcoded/BuDDy) -- knihovna pro práci s BDD
- [Sylvan](https://github.com/trolando/sylvan) -- knihovna pro práci s BDD a jejich variantami zaměřená na vícevláknové zpracování

### Analýza a verifikace neuronových sítí

- [alpha-beta-CROWN](https://github.com/huanzhang12/alpha-beta-CROWN) -- založeno na aproximujících optimalizačních metodách s využitím efektivních výpočetních heuristik
- [Eran](https://github.com/eth-sri/eran) -- analýza robustnosti neuronových sítí s využitím abstraktní interpretace
- [DeepGame](https://github.com/TrustAI/DeepGame) -- verifikace neuronových sítí s využitím teorie her
- [Reluplex](https://github.com/guykatzz/ReluplexCav2017) -- verifikace neuronových sítí s využitím SMT

### Dynamická analýza, pokročilé testování

- [ANaConDA](http://www.fit.vutbr.cz/research/groups/verifit/tools/anaconda/) -- nástroj pro dynamickou analýzu paralelních C/C++ programů na binární úrovni vyvíjený na **FIT VUT**
- [Perun](https://github.com/tfiedor/perun) -- nástroj pro dynamickou analýzu výkonnosti programů (využívající i statickou analýzu z jiných nástrojů), automatická detekce výkonnostních regresí, optimalizovaný profiling -- vyvíjený na **FIT VUT**
- [RoadRunner](https://github.com/stephenfreund/RoadRunner) -- nástroj pro dynamickou analýzu paralelních Java programů
- [psharp-ql](https://github.com/suvamM/psharp-ql) -- testování paralelních programů řízené učením
- [Valgrind](http://valgrind.org/) -- dynamická analýza (založená na interpretaci) korektní práce s pamětí, vlákny, ...
- [Coyote](https://microsoft.github.io/coyote/) -- systematické testování (se snahou vybírat zajímavá proložení) paralelního kódu od firmy Microsoft, použito např. v rámci vývoje Microsoft Azure...

---

Připomínky k obsahu stránky posílejte na e-mail: [lengal@fit.vutbr.cz](mailto:lengal@fit.vutbr.cz)

© 2026 Ondřej Lengál, Tomáš Vojnar
{: .text-grey-dk-100 }
