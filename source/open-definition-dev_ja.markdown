# オープンの定義
Version 2.0dev?

## 1. イントロダクション

The Open Definition makes precise the meaning of "open" with respect to data and content, promoting a robust knowledge commons in which anyone may participate and innovate, and in which barriers to interoperability among pools of data and content are minimized.

要約: **Data or content is open if anyone is free to use, reuse, and redistribute it — subject only, at most, to the requirement to attribute and/or share-alike.**

This essential meaning is the same as that of "open" with respect to software, contained in the [Open Source Definition](http://www.opensource.org/docs/osd), and is synonymous with "free" or "libre"; see the [Definition of Free Cultural Works](http://freedomdefined.org). The Open Definition was initially derived from the Open Source Definition, which in turn was derived from the [Debian Free Software Guidelines](http://www.debian.org/social_contract).

## 2. 用語

The term **work** will be used to denote the item or piece of knowledge
which is being transferred.

The term **license** refers to the legal terms under which the work is
made available. Where no license has been made this should be interpreted
as referring to the resulting default legal conditions under which the
work is available (for example copyright).

## 3. オープンライセンス

A **license** is open if its terms satisfy the following conditions:

### 3.1. Required Permissions

The **license** *must* irrevocably grant the following permissions.

#### 1. 利用

The **license** must allow use of the licensed work for any purpose.

#### 2. 再頒布

The **license** must allow redistribution of the licensed work, 
including sale, either on its own or as part of a collection made from 
works from many different sources. The license must not require a 
royalty or other fee for such sale or distribution.

#### 3. 改変

The **license** must allow creation of derivatives of the licensed 
work, and must allow the derivatives to be distributed under the 
terms of the original licensed work.

*Comment: Conditions may be placed on this permission, as described 
below. Common conditions include 'copyleft' or share-alike requirements 
that require redistribution of modifications under the same terms as the original.*

#### 4. 分離Separation

The **license** must allow any part of the work, or the whole of it, 
to be used, distributed or modified separately from any other part 
of the work, or from any collection of works in which it was originally 
distributed. 

#### 5. 混合Compilation

The **license** must allow the licensed work to be distributed along 
with other distinct works, with no restrictions placed on these other works.

#### 6. あらゆる目的での利用Application to Any Purpose

The **license** must allow use, redistribution, modification and 
compilation, by any person or group of persons, for any purpose. These 
rights must apply independently of other legal agreements, without any 
obligation to agree to additional terms. 

    LV: On re-reading, I'm not sure the "independently of other legal agreements" 
    is quite right; it is broader than the old equivalent language and would 
    prohibit (say) CC 4.0, which reserves rights not explicitly included in the license. 

#### 7. プライバシー

    (kfogel added this as a suggestion, on 2013-12-03)

The **license** must allow private study, use, and modification in the absence
of any form of distribution.  The license may name certain requirements as
conditions for distribution, but the license must not compel distribution itself.

    In other words, if a license requires share-alike style redistribution, the sharealike
    terms must not compel distribution in the first place.  If someone distributes at all,
    it is reasonable to require that they not place obstacles in the way of downstream
    recipients, and even reasonable to require certain forms of active cooperation (e.g.,
    the AGPL's view that accessing functionality via a network is a form of distribution).
    However, if someone does *not* distribute at all, then the license must not compel it.
    The reasons for this are probably obvious, but if pressed for a reference about the
    importance of privacy, I guess I'd point to the first paragraph in which the word
    "privacy" is used in http://snowdenandthefuture.info/PartIII.html.

### 3.2. 受容可能な条件Acceptable Conditions
The **license** *may* condition the permissions granted in Section 3.1 on 
compliance with the following conditions. Other conditions are not generally 
permitted if they meaningfully limit or otherwise impact the permissions 
required in Section 3.1.

#### 1. 帰属

The **license** may require that contributors and creators of a licensed 
work be attributed in distributed versions of the work. If this condition 
is imposed it must not be onerous. 

    LV: "onerous" is vague.

    KM: Still maybe not quite there, but perhaps something along the 
    lines of "If this condition is imposed, it must not unnecessarily 
    burden the use of alternative formats or alternative means of distribution".

#### 2. 一貫性Integrity

The **license** may require that modified versions of a licensed work must 
carry a different name or version number from the original work, or 
otherwise indicate what changes have been made. 

    LV: We should consider broadening to cover everything related to 
    trademarks, in line with recent licenses. (Same issue was noted 
    by Stefano Zacchiroli in his email to us.)

#### 3. アクセスと制限Access and Restrictions

The **license** may require the work to be available in a conveniently 
modifiable form. The license may prohibit technological restrictions.


### 3.3. Recommendations for Open Licenses

    NB: This section is still completely a work in progress, and may or may not be adopted.
    
Licenses with the following characteristics help the open ecosystem by maintaining interoperability and avoiding high costs. (If AC and approval are mentioned in this document, might say we don't approve licenses not following these recommendations.)

#### 再利用性Reusable

Not specific to an organization or jurisdiction.

#### 互換性Compatible

With? Should some license(s) be baked in?

#### 網羅性Coverage

Something about granting rights to something substantial and clear? eg not only game rules

#### 理解可能Understandable

If AC has to debate what license really means, it isn't understandable. Is there some way to express this generally?


## 4. オープンな作品Open Works

A specific **work** is open if its manner of distribution satisfies the following
conditions:

### 4.1. 必須条件Mandatory Conditions

#### 1. ライセンス及びライセンシング情報License and Licensing Information

The **work** must be available under an open license, as defined above, and 
recipients of the work must be clearly and unambiguously notified of the 
license. Any additional terms accompanying the work (such as a terms
of use) must not contradict the terms of the license. Any additional 
information necessary for license compliance (such as names of contributors 
required for compliance with attribution requirements) should also accompany 
the work.

#### 2. アクセスAccess

The **work** shall be available as a whole and at no more than a
reasonable reproduction cost, preferably downloadable via the Internet
without charge. The **work** must also be available in a convenient and
modifiable form. The **license** may require the work to be available
in a convenient and modifiable form. The **work** must be clearly presented
as available under the **license**.

*Comment: This can be summarized as 'social' openness - not only are you
allowed to use, modify, and share the work but you can get it. 'As a whole'
prevents the limitation of access by indirect means, for example by only
allowing access to a few items of a database at a time. An example of
'reasonable reproduction cost' is the cost of blank media or bandwidth
required to distribute a complete database. 'Clearly presented as
available' means that both the license and the means of access are clear
and unambiguous on which works the rights attach to.*

#### 3. 技術的制約の排除Absence of Technological Restriction

The **work** must be provided in such a form that there are no
technological obstacles to the performance of the licensed rights. This
can be achieved by the provision of the work in an open data format,
i.e., one whose specification is publicly and freely available and which
places no restrictions monetary or otherwise upon its use. 

    LV: not clear that "open data formats" are necessarily technologically 
    unencumbered (I know of at least three "open" DRM standards).
    
    LV: It might make sense to link, at least in a comment, to an open 
    standard definition; e.g., http://opensource.org/osr

### 4.2. オープンな作品への推奨Recommendations for Open Works

    KM: We should have a discussion about this on-list, but I'm thinking
    it could be useful to have some softer **should** conditions regarding
    archiving, metadata, use of open standards, availability of APIs, etc.

## Other TODOs

* review http://opendefinition.org/licenses/process/ and make any necessary changes there
* should works section come first? it's shorter, less obscure, and contextualizes/motivates (or could/ought) licenses
    * LV: I think not; we're not ever going to be in the business of certifying works, and it will always have to refer to licenses. If it should be moved anywhere, I'd put it in a different document.
* most of the explanatory comments are gone. maybe the remaining ones should too, and each point be fully self-explanatory
    * LV: That should certainly be a goal.
* address non-revocability/perpetual license [explicitly](https://twitter.com/owenboswarva/status/409801832869797888)? added "irrevocably" before "grant the following permissions".
