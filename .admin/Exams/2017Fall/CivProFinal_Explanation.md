---
date: Fall 2017
title: Civil Procedure Final Exam
subtitle: 
shorttitle: Civil Procedure Final
author: Prof. Fink
affiliation: Elon Law School
mainfont: 'Cormorant Garamond'
scfont: 'Cormorant SC'
sansfont: 'Proza Libre'
monofont: Inconsolata
titlefont: 'Proza Libre Bold'
fontsize: 11pt
geometry: top=1.5in,bottom=1.5in,left=1.5in,right=1.5in
setspace: singlespacing
listmargin: 1.2em
itemsep: 1em
topsep: 0.5em
indent: true
numbersections: false
secnumdepth: 0
output: 
  pdf_document:
    latex_engine: xelatex
    template: emf-default.tex
    
---

# Answers and Explanations 

## Part 1: Joinder

### 1. Co-Plaintiffs

Rule 20(a) governs joinder of co-plaintiffs. There are two requirements: (1) each plaintiff must each assert a claim against the same defendant arising from the same transaction or occurrence (or series thereof), and (2) their claims must entail at least one common question of law or fact. Courts take a broad view of the first requirement, looking for some logical relationship among the claims (e.g. same wrongful conduct by the defendant, similar injuries to the plaintiffs, or some other connection such that it makes sense to treat the claims as being part of the same dispute). Joinder under Rule 20 is permissive, not compulsory.  

Here, Page & Plant are both suing Skidmore for defamation based on the same published statement. The publication of the statement is the common occurrence from which the claims arise. Common questions will include whether the statement was false and, if so, whether it was made with actual malice (assuming the plaintiffs are regarded as public figures for defamation purposes). This is enough to satisfy Rule 20(a).^[No credit was awarded for discussing subject matter jurisdiction on this question, because the problem stated that the court had jurisdiction based on diversity under sec. 1332.]

### 2. Additional Claims & Parties 

#### a. Counterclaim 

Rule 13 governs counterclaims, i.e. claims by a defendant against a plaintiff. The rule distinguishes between "compulsory" and "permissive" counterclaims. Under Rule 13(a), a counterclaim is compulsory if it arises from the same t/o as a claim by the plaintiff against the defendant, and if the counterclaim does not require joinder of a party over whom the court lacks jurisdiction. Compulsory means that the defendant must assert the counterclaim in the same action and may not bring it in a separate action. This is the functional equivalent of claim preclusion (which would not apply to a defendant who asserts no counterclaims at all). Under Rule 13(b), any counterclaim that is not compulsory—i.e. one that does not arise from the same t/o as the plaintiff's claim against the defendant—is permissive, meaning the defendant may opt to bring it in a separate action instead (and will have to do so if the court does not have subject matter jurisdiction over it). 

Skidmore's counterclaim is compulsory. It arises from Page's statement that Skidmore's comments about Page & Plant copying from Wolf are false, and that "he's just trying to pressure us into donating to his scam charity". Page made that statement in response to Skidmore's statement, which is the basis for the plaintiffs' underlying defamation claims, and both statements concern the same controversy over whether Page and Plant copied from Wolf's song. Under the broad "logical relationship" standard, the two statements taken together represent a common occurrence.^[Note that, even though (unlike Rule 20), Rule 13(a) does not explicitly include claims arising from the same *series* of transactions/occurrences, the broad logical relationship standard that courts typically apply has a similar effect of treating logically-related transactions/occurrences as the "same" for purposes of Rule 13(a).]

Because this is a compulsory counterclaim, the court may assert supplemental jurisdiction. It forms part of the same case or controversy as the plaintiff's underlying claims (i.e. the dispute over the alleged copying), which satisfies the requirement for supplemental jurisdiction under sec. 1367(a). The limitations under sec. 1367(b) don't apply. Although diversity is the sole underlying basis for subject matter jurisdiction here, sec. 1367(b) does not apply to any claims by a defendant.^[The court may also have diversity jurisdiction over the counterclaim, depending on whether Skidmore seeks more than $75,000 in damages. But regardless, the court will have supplemental jurisdiction.] 

#### b. Impleader of 3rd Party Defendant 

Rule 14(a)(1) governs the joinder of claims by a defendant against a third-party defendant (i.e. someone who is not already joined as a party). Joinder under Rule 14(a)(1) is limited to "derivative" claims: i.e. asserting that the 3rd party D is liable to the (original) D for all (indemnification) or part (contribution) of D's liability to the plaintiff. A defendant may not join a third-party under Rule 14(a)(1) to assert a claim for D's own injuries.

Here, the problem states that Skidmore seeks indemnification from the Trust. Whether he is really entitled to indemnification will depend on the substantive law governing their relationship. But assuming Skidmore has a plausible claim for indemnification, he may implead the Trust under Rule 14(a)(1) for that purpose.^[Rule 13(g) does not apply here, because Skidmore and the Trust are not co-parties, i.e. they are not both defendants on claims by a common plaintiff. Rule 18 does not apply here, because that rule does not allow joinder of a new party and only applies where a party has already asserted some claim, counterclaim, crossclaim, or third-party claim.]

The court may assert supplemental jurisdiction. A Rule 14(a)(1) impleader claim, by definition, forms part of the same case or controversy as the plaintiffs' underlying claim: it concerns the ultimate allocation of liability as between D and 3rd party D, arising from P's claim against D. Since this is a claim by a defendant, the limitations under 1367(b) (which apply only to certain claims by *a plaintiff*) don't apply, so the lack of diversity between Skidmore and the Trust doesn't matter. 

#### c. Additional Claim Against 3rd Party Defendant 

Rule 18 allows a party asserting a claim (including counterclaims, crossclaims, and third party claims) against another party to join any other claims it has against the same party. Joinder under Rule 18 is allowed even if the claims are completely unrelated. Rule 18 does not itself permit joinder of additional parties. Consequently, in the case of claims by a defendant against a third-party defendant, there must first be a proper claim for indemnification or contribution under Rule 14(a)(1). The defendant may then use Rule 18 to add other claims, either for D's own injuries arising from the same t/o as the underlying plaintiff's claim, or for unrelated claims against the 3rd party Defendant. 

Here, assuming Skidmore properly joins the Trust under Rule 14(a)(1), he may also assert his claim against the Trust for reimbursement. For purposes of joinder under Rule 18, it doesn't matter that this claim is unrelated to the underlying claims between the plaintiffs and Skidmore.^[Rule 13(g) does not apply here, because Skidmore and the Trust are opposing parties, not co-parties.]

But the lack of relationship between the reimbursement claim and the underlying claim by the plaintiffs means that the court may not assert supplemental jurisdiction over that claim (i.e. because they do not form part of the same case or controversy). An independent basis for subject matter jurisdiction is necessary. In this case, there is none. The reimbursement claim arises under state law. Since Skidmore and the Trust are both citizens of MA, there is no diversity jurisdiction, regardless of the amount in controversy between them.  

#### d. Plaintiffs' Claim Against 3rd Party Defendant 

Rule 14(a)(3) allows a plaintiff to assert a claim against a third-party defendant, if the claim arises from the same t/o as the plaintiff's underlying claim against the defendant/third-party-plaintiff. Joinder is permissive, i.e. the plaintiff may opt instead to bring the claim in a separate action (and will have to do so if there is no subject matter jurisdiction over the claim). 

Here, the plaintiffs' claims against the Trust arise from the same occurrence as their underlying claims against Skidmore, i.e. the publication of Skidmore's statement. So joinder is permitted under Rule 14(a)(3).^[Rule 20(b) does not apply here, because Page & Plant are not joining the Trust as an additional defendant on their initial claim, but rather adding this new claim after the Trust has been joined as a new party. While the "same t/o" requirement is the same under Rule 20(b) and Rule 14(a)(3), note that Rule 14(a)(3) does not include the "common question of law or fact" requirement that applies to joinder under Rule 20.]

The court will likely have subject matter jurisdiction over this claim. The claims against the Trust form part of the same case or controversy as the claims against Skidmore. The limitation under sec. 1367(b) does apply here: diversity is the sole underlying basis for original subject matter jurisdiction, and this is a claim by the plaintiffs against a party joined under Rule 14. But sec. 1367(b) disallows supplemental jurisdiction over such claims only if it would be "inconsistent with the jurisdictional requirements of section 1332." Here the requirements of sec. 1332 are still satisfied: there is complete diversity between the plaintiffs (both citizens of the UK) and the defendants (both citizens of MA), and (at least assuming Page & Plant seek to hold the Trust jointly liable with Skidmore) the amount in controversy between each plaintiff and each defendant exceeds $75,000.^[The language of sec. 1367(b) is at least arguably ambiguous as to whether supplemental jurisdiction would be allowed over a claim by a plaintiff against a third-party defendant (or a party joined under Rule 19, 20, or 24) if complete diversity is preserved but the plaintiff's claim against the third-party defendant (or the Rule 19, 20, or 24 party) doesn't exceed $75,000. The Supreme Court has not decided this question. Some lower courts have allowed supplemental jurisdiction where a plaintiff sued multiple defendants, joined under Rule 20, with claims exceeding $75,000 against at least one defendant but not all. E.g., Guidry & Begnaud Developments, LLC v. Houlihan Smith & Co. Inc., 2008 WL 2282619 (W.D. La. 2008); Corporate Resources, Inc. v. Southeast Suburban Ambulatory Surgical Ctr., Inc., 774 F. Supp. 503, 504 (N.D. Ill. 1991). But other courts have disagreed. E.g, State Farm Mut. Auto. Ins. Co. v. Greater Chiropractic Center Corp., 393 F. Supp. 2d 1317 (M.D. Fla. 2005); Pourchot v. Pourchot, 2008 WL 1944702 (W.D. Okla. 2008).]

#### e. 3rd Party Defendant's Claim Against Plaintiff 

Once a plaintiff asserts a claim against the 3rd party defendant under Rule 14(a)(3), the 3rd party defendant must assert any claim against the plaintiff that would be a compulsory counterclaim under Rule 13(a) and may assert any claim against the plaintiff that would be a permissive counterclaim under Rule 13(b). If the plaintiff has not asserted any claim under Rule 14(a)(3), Rule 14(a)(2)(D) permits (but does not require) the third-party defendant to assert a claim against the plaintiff only if it arises from the same t/o as the plaintiff's underlying claim against the original defendant/3rd party plaintiff. 

Here, the Trust's claim against Page to recover the guitar is unrelated to the plaintiffs' underlying defamation claims. If (contrary to the previous question) Page did not assert any claim against the Trust, Rule 14(a)(2)(D) would not permit the Trust to assert the replevin claim against Page, since it arises from a completely different t/o from Page's underlying defamation claim against Skidmore. But assuming (as in the previous question) Page & Plant have asserted defamation claims against the Trust under Rule 14(a)(3), the Trust's claim against Page would then be a permissive counterclaim. 

However, because the Trust's claim is unrelated to the underlying defamation claims, the court may not assert supplemental jurisdiction. Nor is there diversity jurisdiction, even though the Trust and Page are not citizens of the same state, because the amount in controversy is only $10,000. 

## Part 2: Preclusion 

### 1. Preclusion of Copyright Claim 

Claim preclusion prohibits the relitigation of identical claims by the same claimant against the same defending party. It applies where there is a valid, final judgment on the merits in a prior action between the same parties. A judgment is valid if the court in the prior action had jurisdiction over the parties and claim(s). It is final if it fully disposes of the claim(s) in favor of either party. It is on the merits if it is not based on a procedural ground. The claim must involve the same parties (or those in privity, i.e. a special relationship in which one person represents the same legal interests as the other) in the same posture (i.e. plaintiff and defendant, or more generally claimant and defending party in the case of counterclaims, crossclaims, or third party claims by a defendant in the prior action). 

Claim preclusion applies to all claims that were actually asserted in the prior action, as well as to claims that were not asserted but are sufficiently related, provided they could have been brought (i.e. that there was no jurisdictional limitation or other impediment to joinder). Under the modern approach, preclusion applies to all claims arising from the same transaction or occurrence. Some jurisdictions apply a narrower standard, based on whether claims involve the same injury/harm or the same evidence. 

The judgment in the prior suit was valid (the court had personal and subject matter jurisdiction) and final (the court decided both claims in favor of Skidmore). That judgment was also on the merits: the court granted summary judgment, not on any procedural ground, but based on findings that Skidmore was not liable for defamation but that Page and Plant were. 

In the prior suit, Skidmore asserted a counterclaim against Page. Accordingly, Skidmore would be precluded from asserting any additional claims against Page arising from the same t/o as his prior defamation counterclaim. The compulsory counterclaim rule would also preclude any claims by Skidmore against Page or Plant arising from the same t/o as their defamation claims against him. However, in the second suit, Skidmore is suing as a representative of the Trust, which was not a party to the prior suit. Page & Plant might argue that the Trust is in privity with Skidmore and therefore bound by the prior judgment. But the Trust would argue that the prior suit involved claims by and against Skidmore personally, not in his capacity as Trustee.^[See Freeman v. Lester Coggins Trucking (5th Cir. 1985) (holding claim by father suing as guardian for injured child not precluded by father's prior suit for his own injuries arising from same accident).]

Even assuming that claim preclusion could apply against the Trust based on privity with Skidmore, the copyright claim is not part of the same claim as the defamation claims decided in the prior suit. The copyright and defamation claims allege distinct injuries (harm to reputation v. infringement on intellectual property rights), arising from separate and independent conduct (the use of Wolf's work as part of *Stairway to Heaven* v. the publication of the statements by Skidmore and Page) that took place decades apart. The defendants' best argument for preclusion would be that the statements at issue in the defamation suit were about the alleged copying, and the same evidence about whether Page and Plant in fact copied Wolf's song would be relevant in both suits. But even under the broad modern approach, a court would almost certainly treat these as separate claims.^[This is particularly true because the federal Copyright Act broadly preempts state law claims based on unauthorized copying of protected work.] Accordingly, the copyright claim is most likely not precluded.

### 2. Preclusion of Extortion Counterclaim 

The extortion claim is part of the same claim as Page & Plant's defamation claims in the prior action.^[The analysis of the other requirements is the same as in the previous question. No additional credit was awarded for re-addressing those issues.] Page & Plant might argue that their extortion claim involves a distinct harm from the defamation claim (i.e. attempt to extort money v. injury to reputation). But, under the broad modern standard, the two claims are logically related, arising from the same occurrence (i.e. Skidmore's statement that Page & Plant copied Wolf's work and should donate their profits to the Trust) and turning on similar evidence. Page & Plant could have joined the extortion claim in the prior suit (Rule 18) and the court would have had diversity jurisdiction. Assuming the Trust and Skidmore are treated as the same party based on privity, the extortion claim would be precluded.^[Since Page and Plant were the plaintiffs in the first suit, their extortion claim would not have been a counterclaim (compulsory or otherwise) in that prior action.] 

### 3. Issue Preclusion 

Issue preclusion prohibits the relitigation of any factual or legal issue that was conclusively decided against the same party in a prior action. Issue preclusion may be asserted defensively (i.e. by a defending party, to defeat an element of a claim or establish an affirmative defense) or offensively (i.e. by a claimant, to establish an element of the claim). 

For issue preclusion to apply, there must have been a valid and final judgment in the prior action, but that judgment need not have been on the merits (i.e. issue preclusion may apply to a procedural or other non-merits issue). The issue must have been identical in both cases, it must have been actually litigated, and the decision on the issue must have been necessary to the judgment in the prior case. An issue is actually litigated when the parties present evidence and arguments on that issue, either on summary judgment or at trial. A decision on an issue is necessary to the judgment if a different decision would have meant a different result. But if the result would have been the same if the issue had been decided differently (or not at all), issue preclusion will not apply. 

The issues here—whether Page & Plant had access to *Taurus* before they wrote *Stairway to Heaven* and whether the two songs are similar—are the same in both cases. In the prior case, those issues arose because they were relevant to whether the allegedly defamatory statements were false. In the new case, they are relevant to the defendants' liability for copyright infringement. 

In the prior case, the court decided both issues against Page and Plant, making express findings of fact that, before . The parties presumably offered evidence and arguments on these issues as part of the summary judgment motion, which satisfies the "actually litigated" requirement. 

The court's disposition of these issues was necessary to the judgment. Based on its findings that Page & Plant were present at concerts when Spirit played *Taurus* before they wrote *Stairway to Heaven* and that the relevant passages of the two songs sound similar, the court determined that Skidmore had a good faith basis for his statement but Page knew or should have known that his statement was false. Absent those factual findings, Skidmore could not have prevailed on either claim.^[There might be some argument that the outcome in the prior case could have been the same even if the court had decided one or both issues differently. That argument would depend on nuances of defamation law that are beyond the scope of what I'd expect you to address here.] 

Unlike claim preclusion, issue preclusion does not necessarily require that both parties be the same in both actions. The party against whom preclusion is asserted must have been a party to the prior action (because a judgment is only binding against parties to the suit). But the party asserting preclusion may be a newcomer. Courts will generally allow non-mutual defensive issue preclusion as long as the repeat claimant had a full and fair opportunity to litigate the issue previously. In the case of non-mutual offensive issue preclusion, courts will consider such factors as whether the new claimant could readily have joined in the prior action but chose not to in an attempt to gain an unfair tactical advantage, whether there were equivalent procedural opportunities for the repeat party to litigate the issues in the prior action, whether the stakes in the prior suit were much lower (so the repeat party might have had less incentive to contest an issue), or whether there were multiple inconsistent prior decisions on the same issue. 

The Trust is asserting issue preclusion offensively, to establish an element of the copyright claim. Since the Trust was not a party to the prior suit (and assuming privity between the Trust and Skidmore does not apply), this would be non-mutual offensive issue preclusion. It would most likely be permitted, since none of the relevant factors indicate any unfairness in this case. 