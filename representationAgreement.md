[//]: # "what is an advance directive and how it does differ from a representation agreement?"
[//]: # "what about this religious stuff?"

[BOLDCENTER]REPRESENTATION AGREEMENT

This agreement is dated for reference ${ agreement_reference_time } and is between ${ represented_name }, ${ alternate_represenative_name }, ${ second_alternate_representative_name }.

A. ${ represented.first.name } wishes to create this representation agreement, The Represented wished. Representation agreements provide a mechanism whereby adults may arrange in advance how, when and by whom, decisions about their health care or personal care, the routine management of their financial affairs, or other matters will be made if they become incapable of making decisions independently.

B.

The parties therefore agree as follows:

1. **DEFINITIONS**

   "**Act**" means _The Representation Agreement Act_ (British Columbia);

   "**Health Care**" has the meaning ascribed under the *Health Care (Consent) and Care Facility (Admission) Act* (British Columbia);

   "**Major Health Care**" has the meaning ascribed in the HEALTH CARE (CONSENT) AND CARE FACILITY (ADMISSION) ACT

   "**Minor Health Care**" means;

   <!-- Ordinarily when referencing a definition ascribed under legislation, the specific section of legislation is not necessary. Here the section is mentioned because monitor is not a defined term under the legislation. -->

   % if monitor_needed:

   "**Monitor**" has the meaning ascribed under section 12 of the Act;

   % endif

   "**Personal Care**" has the meaning ascribed in the Act;

   "**Representative**" means a person authorized in this agreement to make decisions, help [first name] make decisions, undertake any tasks or help [first name] undertake any tasks, and includes the Original Representative and any Alternate Representative, as may be acting from time to time under the authority of this Representation Agreement, and any reference to the Representative includes all genders and the singular or the plural as the context requires.

1. **REVOCATION OF ALL PRIOR REPRESENTATION AGREEMENTS**

<!--
The _Representation Agreement Act_ (British Columbia) uses the verbs "revocation" in Part 4. The Style Guide prefers the verb "terminate". The Representation Act has requirements to terminate a representation agreement (s. 27).
-->

1. ${ represented.name.first } hereby revokes and terminates all his or her prior representation agreements ${ represented.name.first } has entered into, effective immediately. ${ represented.name.first } shall use reasonable efforts to comply with the terms of termination under all prior representation agreements and under the Act. It is ${ represented.name.first }'s intention that each prior representation agreement is hereby revoked and terminated despite any failure of \${ represented.name.first } to comply with the terms of termination under the representation agreement or under the Act.

1. **APPOINTMENT OF REPRESENTATIVE**

   1. **Appointment.** ${ represented.name.first} hereby appoints the first listed Qualified person below, as his or her Representative (the "Representative"). If at any time the Representative ceases to be Qualified, the Represented appoints the next first listed Qualified person below as his or her Representative.

   ${ representative.name }
   ${ alternate_representative.name }
   ${ second_alternate_representative.name }

   <!--
   The _Representation Agreement Act_ (British Columbia), s. 29(1)(d) states that "A representation agreement ends... if the adult who made the agreement and the adult's representative are spouses, on the termination of their marriage or marriage-like relationship". Section 29(1.1) specifies that this can be overridden with specific language in the representation agreement. Sections 29(1.2) and 29(1.3) make clear the _Family Law Act_ (British Columbia) applies in respect of a determination under 29(1)(d) as to termination.
   -->

   % if survives_separation():

   1. **Decision-making By Multiple Representatives.** create language here

   1. **Appointment Survives Marriage.** create language here

   %endif

   <!-- 
   ? Is this right? This seems ripe for abuse by contentious parties.
   -->

   1. **Declaration of Evidence.** The statutory declaration of any party to this agreement, declaring that any other person named as the Representative is unwilling or unable to act or to continue to act is sufficient evidence of the unwillingness or inability of that person to act or continue to act as the Representative.

   1. **Resignation of Representative.** The Representative may resign by giving written notice to the Represented and to the individual who is next.

<!--  -->

% if monitor_needed():

1. **MONITOR**

   1. The ${ represented.name.first } names ${ monitor.name } to act as Monitor. If the Monitor resigns, dies, becomes incapable, or becomes unable to act as Monitor, the authority of the Representative is not affected. Appointment of new monitor.

% endif

1. **POWERS OF REPRESENTATIVE AS TO PERSONAL CARE OR HEALTH CARE**

   1. The Representative may do anything he or she considers necessary or desirable in relation to the Personal Care or Health Care of the Represented. Without limitating the foregoing, the Represenative may:

      1. decide where the Represented is to live and with whom, including whether the Represented should live in a care facility, and plan, arrange or manage supports and services for the Represented’s benefit;

      1. decide whether the Represented should work and, if so, the type of work, the employer, and any related matters;

      1. accept a facility care proposal for, or consent to, Represented's admission to a care facility under the _Health Care (Consent) and Care Facility (Admission) Act_ (British Columbia);

      1. decide whether the Represented should participate in any educational, social, fitness, vocational, or other activities;

      1. decide whether the Represented should have contact or associate with any other person;

      1. decide whether the Represented should apply for any licence, permit, approval, or other authorization required by law for the performance of an activity;

      1. make day to day decisions on behalf of the Represented, including decisions about the diet or dress;

      1. grant or deny consent, in any circumstances, to health care for [first name], including giving [, withdrawing] or refusing consent to health care necessary to preserve [first name’s] life, even though [first name] refuses to give consent at the time that health care is provided;

      1. grant or deny consent to personal care for [first name], including giving [, withdrawing] or refusing consent to personal care necessary to preserve [first name’s] life, even though [first name] refuses to give consent at the time that personal care is provided; and

      1. despite objection of the Represented, physically restrain, move, and manage the Represented and authorize another person to do these things, if necessary to provide personal care or health care to the Represented.

   1. The Representative may grant or deny consent on the Represented’s behalf to any Major Health Care or Minor Health Care, including without limitation:

1) **GENERAL POWERS OF REPRESENTATIVE**

   1. **Retaining Services**. The Representative may retain the services of a qualified person to assist the Representative to do anything the Representative is authorized to do, including to provide Health Care or Personal Care.

   1. **Expenses Incurred.** ${} shall indemnify ${} in respect of any expenses incurred on ${ represented.name.first }'s behalf, including services rendered under [paragraph 5.5 or paragraph 5.6 of section 5] of this Representation Agreement, arising out of the performance of the Representative’s duties are [first name]’s debts and will be paid by [first name].

   1. **Dependents**. The Representative may arrange for the temporary care and temporary education of ${ represented.name.first }'s minor children and any other person for whom the ${ represented.name.first } cares for or supports.

   1. **Health Records**. The Representative has the authority to do all of the following:

      1. request, review, and receive any information, oral or written, regarding the Represented's physical or mental health, including medical and hospital records;

      1. request, review, and receive any information, oral or written, regarding the Represented's circumstances, including financial information, pertinent to assisting the adult or the Representative in making informed health care and personal care decisions;

      1. execute on the Represented's behalf any documents that may be required in order to obtain this information; and

      1. consent to the disclosure of this information.

   1. **Representative Record Keeping.** The Representative need not keep records relating to:

      1. the Represented's instructions, wishes, beliefs, or values;

      1. decisions made by the Representative regarding the Represented's needs with respect to personal care or health care;

      1. decisions made by the Representative on [first name]’s behalf regarding major health care or [first name]’s admission to, or continued residence in, a care facility;

      1. decisions made by the Representative to restrict a person from contacting or associating with the Represented; or

      1. if the Represented was physically restrained, moved, or managed, who physically restrained, moved, or managed the Represented and why.



1. **INTENTIONS WITH RESPECT TO HEALTH**

   1. **Advance Directive.** The parties acknowledge this section is beliefs and wishes is intended to complement or supplement any specific directions or directives ${ represented.first.name } has expressed.

   1. **Consent of Representative Not Needed**. ${ represented.name.first } hereby authorizes each health care provider to act in accordance with health care instructions set out in any advance directive of ${ represented.name.first } without consent of the Representative.

   <!-- 
   TODO: This needs more research.
   -->

   1. **Life Support.** 
   
   If there is no reasonable expectation of ${}'s recovery from extreme physical or mental disability 
   [and [first name]’s death is otherwise imminent,] 
   [or if [first name] has a grievous and irremediable medical condition (including an illness, disease or disability) that is causing enduring suffering that is intolerable),]
   ${ represented.first.name } wishes to be allowed to die and not be kept alive by artificial means or heroic measures. In this circumstance, ${ represented.first.name } wishes care to be limited to support and comfort only and does not want active resuscitation.

   life support
   life-prolonging medical intervention

   <!-- 
   ? This seems to touch on assisted suicide. OK? 
   -->

   1. **Pain Medication**. ${ represented.name.first } intends that medication be administered to alleviate suffering, even if such medication may hasten or cause death.

If I am sedated and unable to communicate, I would like the sedation lifted so that
I can rationally consider my situation and decide for myself to accept or refuse a
particular therapy.

I specifically direct that my life be prolonged and that I be provided all life---sustaining treatments applicable to my medical condition.


% if donate_organs():

   <!--
   ? Is this sufficient to effect a donation of organs? What are the parameters of organ donation?
   * *Human Tissue Gift Act* (British Columbia)
   -->

% if donate_all_organs():

1. **Donation of Organs.** ${ represented.name.first } intends that before or after death, any tissue, organ, or other part of his or her body may be removed for implantation in another human body % if donate_for_research:, including for research purposes %endif .

% else:

1. **Donation of Organs.** ${ represented.name.first } intends that before or after death, the following parts of his or her body may be removed for implantation in another human body % if donate_for_research:, including for research purposes %endif :

% if donate_heart: heart % endif
% if donate_lungs: lungs % endif
% if donate_liver: liver %endif
% if donate_kidneys: kidneys %endif
% if donate_pancreas: pancreas %endif
% if donate_bowel: bowel %endif
% if donate_eyes: eyes %endif
% if donate_tissue: tissue %endif

% endif

% endif

<!-- 
! Note that if death occurs outside the Greater Vancouver Regional District, the deceased bears the expense of transporting the body to the University of British Columbia
? Consider adding provisions to address a donation outside of British Columbia
TODO: address the length of time UBC can keep the body
-->

% if donate_body:

1. **Donation of Body.** ${ represented.name.first } intends that after death his or her body be donated to the University of British Columbia, Faculty of Medicine, Body Donation Program or any such replacement program
% if donate_body_at_expense:
, provided that ${ represented.name.first } dies within the Greater Vancouver Regional District and thus will not bear the expense of transporting his or her body to the University of British Columbia
% endif
.

% endif

% if includes_power_of_attorney:

<!-- 
! The *Representation Agreement Act* (British Columbia) provides at s. 7(1)(b) that the representative may be authorized to perform "routine management of the adult's financial affairs". The CLEBC Practice Manual Wills and Personal Planning Precedents: An Annotated Guide s. 32.1 provides that a power of attorney is preferable to the representation agreement for financial matters. 
-->

1. **ROUTINE MANAGEMENT OF FINANCIAL AFFAIRS**

   1. **Routine Management of Financial Affairs** includes:

      1. paying bills;

      1. receiving income or other payment;

      1. depositing income or other payment;

      1. purchasing goods and services, consistent with \${represented.name.first}'s means and lifestyle;

      1. obtaining accomodation; and

      1. deferring property taxes.

      For greater clarity, it does not include:

      1. purchasing real property.

% endif

1. **AGREEMENT COMES INTO EFFECT; TERMINATION OF AGREEMENT**

   1. **Effectiveness.** This agreement is effective upon the first of:

      1. the Represented completes the endorsement set out in _Schedule A_;

      1. the Represented no is no longer capable of giving informed consent to one or more major health care decisions; or

      1. the Represented is incapable of managing himself or herself - will have occurred when [first name]’s incapability is confirmed, in writing, by two medical professionals who have each examined [first name] personally. One of the medical professionals must be [first name]’s family physician or one of [first name]’s treating physicians, and the second medical professional must be either:

         1. a physician licensed to practise in Canada; or

         1. a registered psychologist licensed to practise in Canada.

   1. **Termination.** This agreement terminates:

      1. immediately upon ${ represented.name.first }'s death;

      1. the Represented may revoke this agreement by delivering written notice of revocation to each Representative, Alternate Representative, and Second Alternate Representative. Such revocation is effective upon the later of (1) delivery of notice to the last required person, or (2) a date specified in the notice, if any.

      1. if there is no Representative with capacity and who consents to act as Reprsentative;

      1. on the happening of any other event listed in section 29 of the _Representation Agreement Act_ (British Columbia) that would have the effect of terminating this agreement.

1. **FINANCIAL**

   % if:

   1. the stuff goes here

   % else:

   1. The Representative is not entitled to be remunerated for acting as a Representative.

   % endif

   1. **Indemnity.** The Represented shall indemnify the Representative for any direct, out-of-pocket expense incurred by the Representative arising directly out of the performance of the Representative’s obligations under this agreement.

1. **GENERAL**

   1. **Amendment.** This agreement may be amended only by a written agreement signed by each of the Original Representative, the First Alternate Representative, and the Second Alternate Representative, [and the monitor,] other than any of those who have resigned pursuant to paragraph 3.7 or regarding whom a statutory declaration has been sworn declaring that that person is unwilling or unable to act or continue to act as the Representative.

   1. **Severability.** Any provision or part provision of this agreement determined to be invalid or unenforceable will be severed from this Representation Agreement, and the remaining part, if any, of that provision and all other provisions of this Representation Agreement will continue in full force and effect. The invalidity or unenforceability of any provision, or part provision, in any particular jurisdiction, will not affect its validity or enforceability in any other jurisdiction where it is valid or enforceable.

   1. **Counterparts.** This agreement may be executed in any number of counterparts and each executed counterpart will have the same force and effect as an original instrument. All executed counterparts taken together will constitute one agreement.

   1. **Signatories.** This agreement is effective when it is signed by the Represented and the Representative, even if not signed by any other party.

   1. **Legislation Changed or Repealed.** Text goes here.
