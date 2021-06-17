# FAQs for Community Data License Agreement - Permissive - Version 2.0

Posted to main CDLA website at https://cdla.dev/faq/

## Why create a new data agreement?

With the ascent of machine learning and its reliance on high quality data, there is a need for data agreements which facilitate data sharing both for data providers and data recipients and create a predictable path for training ML models. Recent agreements, such as the CDLA-Permissive-1.0, CDLA-Sharing-1.0, and the O-UDA-1.0, have made good strides towards these goals, but we believe recent developments in the law and the evolving needs of machine learning make it desirable to have an even simpler, more streamlined approach.

This new agreement, the whose use of which we hope will supersede its predecessors, the CDLA-Permissive-1.0 and the O-UDA-1.0, has been crafted with the following objectives in mind:

* A short, straightforward data agreement which enables data sharing and data innovation in a responsible way;
* The use of data under the agreement carries no obligation;
* The sharing of data under the agreement is operationally simple and requires nothing more than making available the text of the agreement;
* Training an ML model based on data under the agreement, even copyrighted data, creates no obligation under the agreement for the use or the distribution of the trained model or for the insights it generates;
* A data provider-friendly agreement, as the sharing of data under the agreement is designed to limit the liability of the data provider(s).

## What are some anticipated typical use cases?

We envision that this agreement is suitable for situations where the original data provider created a data set, is reasonably confident in its ability to share the data set, and wants to be clear that the results from computational analysis of the data are not restricted. Some examples of typical use cases are provided below:

* Releasing corporate data that does not contain personal data;
* Training an AI model based on a dataset under CDLA-Permissive-2.0;
* Receiving a dataset under CDLA-Permissive-2.0, adding new features to it and sharing the augmented dataset under CDLA-Permissive-2.0;
* Merging a dataset under the CDLA-Permissive-2.0 with another dataset that might be under another license.

## What is the difference between Data and Results?

"Data" is what you receive under the agreement, which you might augmented with your own features.

If you train an ML model on it, that would typically be considered a Result. However, as ML models continue to evolve, some models may return parts of the underlying Data in response to certain inputs. We think that this should not count as sharing Data, and we want to make sure that the use of these models would not implicate even the modest obligations for sharing Data that is provided under the CDLA-Permissive-2.0.

## Is CDLA-Permissive-2.0 open?

We believe CDLA-Permissive-2.0 meets the [Open Definition](https://opendefinition.org/od/2.1/en/). It permits everything described in Section 2.1 of the Open Definition and only imposes conditions approved by Section 2.2, namely making available the license text, including a preservation of the disclaimers of warranties and liability.

## Does CDLA-Permissive-2.0 require retaining or reproducing attribution notices when sharing Data?

In [CDLA-Permissive-1.0](https://cdla.dev/permissive-1-0/), one of the requirements when sharing Data was to preserve all credit and attribution notices. Based on feedback from the community during the CDLA-Permissive-2.0 drafting process, it became clear that there was a desire to eliminate this as a _requirement_ in the license agreement itself.

Although "attribution-style" provisions may be common in permissive open source software licenses, they do add an additional process step that (even if minor) may introduce complexity into the resharing of open data sets. Additionally, as technologies continue to evolve beyond what the CDLA drafters might anticipate today, it is unclear whether typical ways of sharing attributions for open source software will analogize well to open data sharing.

That said, nothing about CDLA-Permissive-2.0 is meant to imply that recipients of Data under CDLA-Permissive-2.0 should not provide attribution about the sources of the data. Attribution will often be important for appropriate norms in communities, and understanding its origination source is often a key aspect of why an open data set will have value. The CDLA-Permissive-2.0 simply does not make it a condition of sharing Data that is received under the license agreement.

## I have shared datasets under CDLA-Permissive-1.0. Can I “upgrade” these agreements to CDLA-Permissive-2.0?

Yes. Pursuant to section 7.5 of CDLA-Permissive-1.0, Datasets previously shared under CDLA-Permissive-1.0 can be shared under future versions of CDLA Permissive published by the Community Data License Agreement workgroup under The Linux Foundation.

## If I receive Data under CDLA-Permissive-2.0, can I redistribute it under different terms?

Yes - just as you can distribute software under a permissive license in a proprietary software product (subject to retention of required notices), you can redistribute the permissively licensed data in a larger aggregation under any terms you desire.
