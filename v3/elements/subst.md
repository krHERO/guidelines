---
layout: sidebar
sidebar: s1
version: "v3"
title: "subst"

---

<div class="elementSpec">
   <h3 id="subst">&lt;subst&gt;</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2"> (substitution) – Groups transcriptional elements when the combination is to be regarded
            as a single intervention in the text.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Module</span>
         </td>
         <td class="wovenodd-col2">MEI.edittrans</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Attributes</span>
         </td>
         <td class="wovenodd-col2">
            <div class="attributeDef">
               <span class="attribute">@cert</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Signifies the degree of certainty or precision associated with a feature.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.CERTAINTY">data.CERTAINTY</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.evidence">att.evidence</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@evidence</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates the nature of the evidence supporting the reliability or accuracy of the
                  intervention or interpretation. Suggested values include: 'internal', 'external',
                  'conjecture'.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">NMTOKEN</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.evidence">att.evidence</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@hand</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Signifies the hand responsible for an action. The value must be the ID of a
                  &lt;hand&gt; element declared in the header.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.handident">att.handident</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@label</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a name or label for an element. The value may be any string.</span>
               Value of datatype 
               <span style="font-weight: 500;">string</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.commonPart">att.commonPart</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@n</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a number-like designation for an element.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/token">token</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.common">att.common</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@resp</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Captures information regarding responsibility for some aspect of the text's
                  creation, transcription, editing, or encoding. Its value must point to one or more
                  identifiers declared in the document header.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.responsibility">att.responsibility</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@seq</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to assign a sequence number related to the order in which the encoded features
                  carrying this attribute are believed to have occurred.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">positiveInteger</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.sequence">att.sequence</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@source</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Contains a list of one or more pointers indicating the sources which attest to a
                  given reading. Each value should correspond to the ID of a &lt;source&gt; element
                  located in the document header.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.source">att.source</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@xml:base</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a base URI reference with which applications can resolve relative URI
                  references into absolute URI references.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.commonPart">att.commonPart</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@xml:id</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Regularizes the naming of an element and thus facilitates building links between it
                  and other resources. Each id attribute within a document must have a unique
                  value.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">ID</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.id">att.id</a>
               </span>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Member of</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <a class="link_odd_classSpec" href="/{{ page.version }}/model.editLike">model.editLike</a>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Contained by</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div class="specChildren">
                  <div class="specChild">
                     <span class="specChildModule">MEI.cmn</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/beam">beam</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/measure">measure</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/tuplet">tuplet</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.critapp</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/lem">lem</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/rdg">rdg</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.edittrans</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/abbr">abbr</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/add">add</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/choice">choice</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/corr">corr</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/cpMark">cpMark</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/damage">damage</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/del">del</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/expan">expan</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/orig">orig</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/reg">reg</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/restore">restore</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/sic">sic</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/subst">subst</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/supplied">supplied</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/unclear">unclear</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.figtable</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/td">td</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/th">th</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.fingering</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/fing">fing</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/fingGrp">fingGrp</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.harmony</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/f">f</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/fb">fb</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/harm">harm</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.header</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/contentItem">contentItem</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/inscription">inscription</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.namesdates</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/addName">addName</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/bloc">bloc</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/corpName">corpName</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/country">country</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/district">district</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/famName">famName</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/foreName">foreName</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/genName">genName</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/geogFeat">geogFeat</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/geogName">geogName</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/nameLink">nameLink</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/periodName">periodName</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/persName">persName</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/postBox">postBox</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/postCode">postCode</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/region">region</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/roleName">roleName</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/settlement">settlement</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/street">street</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/styleName">styleName</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.neumes</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/ineume">ineume</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/syllable">syllable</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/uneume">uneume</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.shared</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/addrLine">addrLine</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/annot">annot</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/caption">caption</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/chord">chord</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/desc">desc</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/dir">dir</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/dynam">dynam</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/ending">ending</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/head">head</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/identifier">identifier</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/label">label</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/layer">layer</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/name">name</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/note">note</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/num">num</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/ornam">ornam</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/p">p</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/part">part</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/pgFoot">pgFoot</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/pgFoot2">pgFoot2</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/pgHead">pgHead</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/pgHead2">pgHead2</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/rend">rend</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/rest">rest</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/score">score</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/section">section</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/staff">staff</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/syl">syl</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/tempo">tempo</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/title">title</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.text</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/l">l</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/li">li</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/quote">quote</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.usersymbols</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/anchoredText">anchoredText</a>
                     </span>
                  </div>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">May contain</span>
         </td>
         <td class="wovenodd-col2">
            <div class="specChildren">
               <div class="specChild">
                  <span class="specChildModule">MEI.edittrans</span>
                  <span class="specChildElements">
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/add">add</a> 
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/corr">corr</a> 
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/damage">damage</a> 
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/del">del</a> 
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/gap">gap</a> 
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/handShift">handShift</a> 
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/orig">orig</a> 
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/reg">reg</a> 
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/restore">restore</a> 
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/sic">sic</a> 
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/supplied">supplied</a> 
                     <a class="link_odd_elementSpec" href="/{{ page.version }}/unclear">unclear</a>
                  </span>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Declaration</span>
         </td>
         <td class="wovenodd-col2">
            <div xml:space="preserve" class="pre">
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;classes&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.common">att.common</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.edit">att.edit</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.trans">att.trans</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/model.editLike">model.editLike</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/classes&gt;</span>
               </div>
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;content&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;rng:ref 
                        <span class="attribute">name=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/model.transcriptionLike">model.transcriptionLike</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;rng:oneOrMore&gt;</span>
                     
                     <div class="indent3">
                        <span data-indentation="3" class="element">&lt;rng:ref 
                           <span class="attribute">name=</span>
                           <span class="attributevalue">"
                              <a class="link_odd" href="/model.transcriptionLike">model.transcriptionLike</a>"
                           </span>/&gt;
                        </span>
                     </div>
                     
                     <span data-indentation="2" class="element">&lt;/rng:oneOrMore&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/content&gt;</span>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Remarks</span>
         </td>
         <td class="wovenodd-col2">
            <p>This element is modelled on an element in the Text Encoding Initiative (TEI)
               standard.
            </p>
         </td>
      </tr>
   </table>
</div>