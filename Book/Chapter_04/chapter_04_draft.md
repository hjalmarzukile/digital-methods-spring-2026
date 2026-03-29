# Chapter 4: Collecting Digital Data

---

## 1. Two traditions, one dataset

For most of the twentieth century, empirical social science organized itself around two great data collection methods: the survey and the interview. The division was not merely practical. It reflected two fundamentally different philosophies about what social research is for and what kind of data it needs.

The survey was the instrument of the quantitative tradition. It produced data that could be aggregated, compared, and generalized. Its power lay in scale and standardization: by asking the same closed questions to many respondents drawn from a defined population, researchers could say something about that population as a whole. What percentage of people trust their government? How does social class predict educational attainment? These are questions that require distribution — many observations, measured consistently — and the survey was designed to provide exactly that. The unit of analysis was typically the individual, the mode of expression was the closed response category, and the analytical goal was to find patterns that held across cases.

The interview was the instrument of the qualitative tradition. It produced data that could be read, interpreted, and theorized. Its power lay in depth and openness: by engaging in sustained, open-ended conversation with a smaller number of people, researchers could enter their subjective worlds — understanding how they perceived their circumstances, what meanings they attached to their actions, and what motivated them. What does it feel like to distrust your government? What keeps someone from pursuing an education they want? These are questions that require interpretation — close engagement with how particular people understand their particular lives — and the in-depth interview was designed to provide that. The unit of analysis was often the individual account or narrative, and the analytical goal was to generate insight that could be extended theoretically, if not statistically.

These two traditions had their own methodological cultures, their own journals, and their own criteria for what counts as good evidence. They occasionally spoke to each other — often polemically — but they rarely needed to collaborate, because each tradition had data collection methods that matched its analytical ambitions. Qualitative researchers interviewed and observed. Quantitative researchers surveyed and measured. The methods were distinct, the data were distinct, and the researchers largely inhabited distinct worlds.

Digital data has made this division increasingly untenable, and increasingly beside the point.

---

## 2. The brave new world of found data

When social life leaves digital traces, both researchers walk into the same room. The posts, threads, comments, reactions, timestamps, and network structures that accumulate on online platforms are simultaneously available to the qualitative reader and the computational analyzer. There is no separate archive for each. The data are there, and they are available to whoever chooses to collect them.

This changes everything about the logic of data collection design — but not by resolving the old tension. If anything, it complicates it. As we argued in Chapter 1, digital data is abundant but partial. There is, in one sense, vastly more of it than any qualitative researcher could ever read, and it covers an astonishing range of human social life. But it is also systematically incomplete. It captures what people choose to post, in settings designed by platform engineers, subject to moderation and algorithmic curation, and reflecting the demographic biases of who has access and who chooses to participate. The abundance is real. The partiality is equally real.

The methodological response to this situation cannot simply be "collect more." More data does not fix the problem of partiality — it may simply give you more of a systematically skewed picture. Nor can it simply be "read carefully." Careful reading of a non-representative sample still produces findings that may not travel far. The response, as we have been arguing throughout this book, is to think carefully about *what* you are collecting, *why* you need it, and *how* different data types relate to one another in your overall research design.

This chapter is about that thinking. It is about data collection design in a digital mixed methods context: how to identify what kinds of digital data bear on your research question, how to construct a sampling strategy appropriate to your analytical purposes, and how to actually collect large-scale data in ways that are technically feasible, methodologically sound, and ethically defensible.

---

## 3. Degree of digitalization

Before we can talk about types of digital data, we need to confront a prior question: how digital is the phenomenon you are studying?

This sounds like an odd question. But it matters enormously for how you design your data collection. Consider two scenarios. In the first, you are studying a prepper community that exists primarily online — a Reddit forum, a dedicated website, or a Facebook group where members join specifically to share preparedness knowledge, discuss supplies, debate strategies, and build relationships with like-minded people. The digital setting is not a window onto some separate social phenomenon: it *is* the social phenomenon. The conversations in the forum are where community membership is enacted, identities are performed, norms are contested, and knowledge is produced.

In the second scenario, you are studying a local emergency preparedness organization — a neighborhood group that holds monthly meetings, organizes supply drives, and coordinates responses to local disasters. This group happens to have a Facebook page where it posts announcements and occasionally engages with members. The page is a digital trace of the organization, but the organization's core activities happen offline. Someone who only analyzed the Facebook data would miss most of what the group actually does.

The concept of *degree of digitalization* captures this difference (see also Venturini et al. 2018). In high-digitalization settings, the digital traces are a direct record of the social phenomenon itself — the online interaction is the phenomenon. In low-digitalization settings, the digital traces are partial indicators of a phenomenon that also, or primarily, unfolds offline. For mixed digital methods, this distinction matters for how much epistemic weight you can place on digital data alone, what questions it can and cannot answer, and what supplementary data collection might be needed.

For the research designs covered in this book — focused on communities and conversations that are substantially constituted online — degree of digitalization is typically high. But researchers should be explicit about this assessment. The netnographic site evaluation conducted in Chapter 3 is precisely where this judgment is formed: immersion in a site gives you a sense of how central the digital setting is to participants' social lives, and that judgment shapes everything that follows in data collection.

---

## 4. A typology of digital data

Once you have assessed the degree of digitalization of your research site, the next step is to identify *what kinds* of data the site produces. Digital platforms generate multiple types of data simultaneously, and these types have different analytical properties. Understanding those properties is essential for designing a collection strategy that matches your research question.

We can distinguish four main types of digital data, organized along two axes that we borrow from the data design literature (Grigoropoulou & Small 2022): whether data is *narrative* or *action*, and whether it is *open* or *closed*.

**Narrative data** captures what people say, write, or express — their accounts of themselves, their interpretations of events, their stated beliefs and evaluations. **Action data** captures what people *do* — their behaviors, interactions, and movements, independently of how they describe those behaviors. **Open data** is produced in formats that allow unconstrained expression — free text, video, audio. **Closed data** takes forms with a fixed structure — a like, a reaction, a follow, a membership category, a timestamp.

These axes generate a useful map of digital data types:

**Text data** (open, narrative): Posts, comments, threads, messages, articles — the substance of what people write. Text data is the richest and most interpretable type of digital data. It is what makes digital platforms legible to qualitative reading, and it is what natural language processing models are designed to analyze at scale. When we speak of "reading" digital data, we almost always mean reading text.

**Activity data** (closed, action): Likes, shares, reactions, votes, views, timestamps — the record of how people engage with content and one another. Activity data tells you *that* something happened and *when*, without telling you *why*. It is highly structured and therefore easy to aggregate and analyze quantitatively, but thin in interpretive content. In a prepper forum, activity data might include upvote counts on posts, reply frequencies, and the timing of posting activity around major news events.

**Relational data** (closed, action): Follows, friendships, memberships, co-participations, mentions, links — the structural record of who is connected to whom and in what way. Relational data is the raw material of network analysis. It captures the social architecture of a community — who are the central actors, what clusters form, which communities are linked. In a prepper community, relational data might capture which members participate in multiple forums, or which users regularly respond to each other's posts.

**Temporal data**: Timestamps, posting sequences, trends over time — data that tracks how a phenomenon evolves. Temporal data is in some sense a property of the other types rather than a standalone category, but it deserves separate mention because the temporal dimension is analytically distinctive. When did this community form? How did its discussions change after a major disaster? Do posting patterns vary by season? These questions require treating time as a variable in its own right.

These four types do not appear in isolation. Most digital platforms generate all of them simultaneously. When someone posts a comment in a prepper forum (text data), they are also generating relational data (a reply to a specific user), activity data (a timestamp, a vote count on their post), and temporal data (the post's position in the community's history). The platform generates this bundle of data automatically and continuously; the researcher's job is to decide which parts of it are relevant, and in what combination.

This is a key difference from classical social science data collection, where you generally collect one type of data by choosing one method. An interview produces narrative data; a survey produces structured response data. Found digital data hands you several types at once, and the question is not *how do I collect this* but *what do I need, and how much of what I don't need do I take along for the ride?*

---

## 5. The logic of data integration

Having a typology of data types is useful. But the deeper question is how different types of data relate to each other in your overall design. The data design literature identifies three main integration logics (Grigoropoulou & Small 2022; see also Chapter 2):

**Integrated design** uses different data types to answer the same question from different angles — each type casts a different light on the phenomenon, and the researcher uses the complementarity between them to build a more comprehensive picture. The Carlsen et al. (2020) study of refugee solidarity activists illustrates this well. Life-history interviews provided narrative data about how activists came to feel a personal responsibility toward specific refugees. Facebook activity data then provided evidence about whether this mechanism had behavioral consequences — specifically, whether activists who had interacted with a refugee were subsequently more active in the movement. Neither data type alone could have answered the question. The narrative data generated the mechanism; the action data provided evidence of its effects.

**Hierarchical/nested design** uses one type of data to structure or sample from another. A researcher might use relational data (the network structure of a forum) to identify the most central actors, then collect text data from those actors specifically. Or she might use activity data (posts that received the most responses) to identify high-salience moments in the community's history, then read those moments closely. The large-scale data provides the frame; the closer reading provides the substance.

**Transformation design** converts one type of data into another. In the sequential analysis design that runs through this course, text data is eventually transformed into quantitative variables through computational classification. But this transformation only makes sense downstream — it depends on qualitative work that establishes what categories are meaningful and how they map onto language in the corpus. We return to this in Chapters 5 and 6.

For the research designs developed in this book, the most common integration logic is sequential: netnographic immersion provides qualitative understanding of the research site; this understanding informs the construction of a sampling frame; large-scale data is collected within that frame; and the large-scale data in turn enables effective sampling for qualitative reading. This sequence will be familiar from Chapter 2, but it is worth emphasizing that the entire logic depends on moving *through* these stages in order, with each stage providing the foundation for the next. You cannot build a good sampling frame without netnographic understanding; you cannot do good computational analysis without good large-scale data; and you cannot do good large-scale analysis without understanding, first, what the data actually records.

---

## 6. Sampling frames: who, what, and where

Before you can collect data, you need a sampling frame — a principled specification of the population you are trying to reach. This is true in all empirical social science. A survey researcher specifies the population she wants to generalize to and draws a sample from it. A qualitative researcher identifies the social context she wants to understand and selects interviewees within it.

Digital data collection requires the same discipline, but the logic of the sampling frame takes three distinct forms depending on what you are trying to capture:

**Actor-based sampling** defines the sampling frame in terms of the actors — people, organizations, accounts — whose behavior you want to study. The frame specifies which actors are "in" and how to find them. When the actor population is well-defined and visible, this is relatively straightforward: if you want to study public health officials' Twitter communications, you can compile a list of verified official accounts. When the population is unknown — you want to study, say, all active participants in prepper communities, but you don't know in advance who those participants are — you need a different strategy.

One powerful tool for unknown actor populations is snowball sampling. Beginning with a set of known seed actors (prominent prepper accounts, well-known forum moderators), the researcher identifies additional actors by following the connections those seed actors make: who do they reply to, mention, follow, or link to? From those actors, further connections are identified, and so on. Snowball sampling is not random, and it has well-known limitations (communities that are not well-connected to the seed network will be underrepresented), but for exploratory mapping of a population whose boundaries are unclear, it is often the only tractable approach. It is a method shaped by what the data affords, not by an ideal sampling design conceived in advance.

Actor-based sampling is particularly appropriate when your research question is specifically about *who these people are* — their characteristics, their social positions, their relationships to each other. The refugee solidarity study illustrates this: the research question was about how different activists came to participate, which meant the unit of analysis was the individual activist, and the sampling frame had to specify how to identify all (or a principled subset of) those activists across multiple Facebook groups.

**Topic-based sampling** defines the sampling frame in terms of the content being discussed rather than the identity of the discussants. The researcher specifies a set of keywords, phrases, or topics, and collects all posts that match those criteria within a given platform or time window. This is the most natural sampling strategy for research questions about public discourse: if you want to understand how prepper communities discuss water storage, you search for posts containing "water storage" and related terms, without restricting yourself in advance to a specific set of actors.

Topic-based sampling is powerful but has an important limitation: it depends on the assumption that your keywords capture the relevant discourse well. Preppers discussing water storage may use a vocabulary you did not anticipate — they may talk about "blue barrels," "BPA-free containers," "gravity filters," or "well drilling" without any of these appearing in an initial keyword list. This is precisely where netnographic immersion pays off. Weeks of reading the prepper forum before you design your sampling strategy gives you the vocabulary of the community, which you can then use to build a keyword list that actually captures what people are talking about. The qualitative work does not follow the quantitative work; it grounds it.

**Location-based sampling** — or what we might call *forum-complete* sampling — defines the sampling frame not by actors or topics but by the site itself. The researcher collects everything produced within a defined digital location over a defined time period. Every post in a subreddit. Every thread on a forum. Every message in a Facebook group. The boundary is the location, and everything within that boundary goes in.

This approach is both the simplest to operationalize and the one with the most distinctive analytical logic. By collecting everything within a bounded space, the researcher gets a population-level view of activity in that setting. There is no sampling uncertainty about what got included or excluded within that space; the only question is how representative that space is of the broader phenomenon. For research questions focused on a specific community — what prepper forums discuss, how norms are enforced, what happens when consensus breaks down — forum-complete sampling is often ideal. You are not trying to generalize to "all prepper discourse everywhere." You are studying this particular community, and you want everything it produced.

Location-based sampling is the digital analogue of ethnographic site-specificity. Traditional ethnographers study a village, a hospital ward, a factory floor — a bounded social setting that they observe in its entirety. Forum-complete sampling replicates this logic digitally, with the added advantage that the traces are permanent and voluminous, and the added complication that platform affordances shape what gets recorded and what does not.

These three sampling logics are not mutually exclusive. A sophisticated study might use actor-based sampling to identify the key participants in a prepper network, location-based sampling to collect all content from the forums those participants inhabit, and topic-based sampling to draw out the subset of that content relevant to a specific debate. The art of data collection design lies in knowing which logic serves your research question at each stage, and in being explicit about the choices you have made.

---

## 7. Collecting large-scale digital data

Once you have a sampling frame, you need to actually collect the data. This involves technical choices that have methodological consequences.

The two main collection approaches are **application programming interfaces (APIs)** and **web scraping**. Understanding what each offers — and what each withholds — is as important as understanding any other methodological decision in your design.

An API is a formal interface provided by a platform that allows researchers (and developers) to request data programmatically. Platforms like Reddit, Twitter/X, Facebook, and many others have offered APIs at various points, though the terms of access have changed substantially in recent years. When an API is available, it is typically the preferred collection method: data is returned in a structured, machine-readable format; requests can be automated; and the data is generally cleaner and more complete than what can be obtained by scraping.

But APIs are curated windows. The platform decides what data is available through the API, in what volume, and at what rate. Reddit's API, for example, returns post data but may not include all historical posts, may limit the number of requests per unit time (rate limiting), and may exclude certain types of content or metadata. The researcher gets what the platform chooses to provide. When researchers built large-scale datasets from the Twitter API in the early 2010s, they were sampling from what Twitter's "firehose" made available — which was itself a curated subset of all activity. Changes to API terms of service can invalidate years of established practice overnight (as happened in 2023 when several major platforms sharply restricted API access).

Web scraping bypasses the API by automatically loading web pages and extracting data from the HTML structure. Scraping can reach data that the API does not expose — older posts, deleted content that remains cached, metadata not included in API responses, or platforms that do not offer APIs at all. It can also be more precarious. Web pages are designed for human viewing, not machine reading, and their structure changes without notice. A scraper that worked yesterday may fail today if the platform updated its layout. Scraping can also run into ethical and legal complications: terms of service for many platforms explicitly prohibit automated scraping, and researchers need to consider carefully whether their collection practices are compliant with both platform rules and applicable law.

For prepper communities, the collection options are relatively good. Reddit provides a public API, and large portions of Reddit's historical data have been archived by third parties (such as Pushshift, before its discontinuation) and are available for research purposes. Dedicated prepper forums built on standard web platforms are generally scrapeable. The practical decision for a prepper project would typically involve a combination: using the Reddit API for subreddit data where rate limits permit, and writing a targeted scraper for dedicated forum sites.

Whatever the technical approach, the methodological challenge is the same: documenting what you collected, why you collected it, and what the limitations of your collection approach are. How many posts exist in the sampling frame? How many did you successfully collect? What is the reason for any gap? Are there systematic patterns in what was not collected — for instance, deleted posts, rate-limited time periods, or content excluded by platform policy? These questions matter not as technical footnotes but as substantive methodological reflections that bear on what you can and cannot conclude from your data.

---

## 8. Data quality and validation

Large-scale digital data requires quality assessment before analysis begins. This is not unique to digital data — any empirical researcher who took her sampling design seriously would conduct such an assessment — but it takes specific forms in the digital context.

The first question is completeness. How much of your sampling frame did you successfully collect? If you aimed to collect all posts in a prepper subreddit over a three-year period, how does your actual collection compare? Discrepancies can arise from rate limits that cut off collection during high-activity periods, platform API restrictions that exclude certain content types, or technical failures in the collection pipeline. A well-documented collection process should be able to account for these discrepancies and assess whether they introduce systematic bias.

The second question is data integrity. Are the data you collected complete at the level of individual observations? Text posts should have their full text, not truncated excerpts. Timestamps should be present and parseable. Author identifiers should be consistent across posts by the same user. Activity data (vote counts, reply counts) should be interpreted carefully, since these may change after collection — a post's upvote count at the time of collection may differ from its count weeks later.

The third question is representativeness relative to your sampling frame. This sounds redundant — if you collected everything in the frame, representativeness is not an issue — but it matters for forum-complete sampling in a subtle way. A prepper subreddit is a complete population *of that subreddit*, but it may not represent the broader landscape of prepper communities. Subreddit members tend to be more tech-savvy and demographically younger than participants in dedicated forums or offline preparedness groups. The community that is easiest to collect is not necessarily the most theoretically representative.

This is where the netnographic site evaluation from Chapter 3 does important work retrospectively. The criteria introduced there — relevance, activity, interactivity, diversity, richness — are also data quality criteria. A site that is relevant to your topic, active with substantial historical content, characterized by genuine interactivity, diverse enough to surface variation, and rich enough to support interpretation is also a site whose data is likely to be adequate for the research design. The evaluation process is not merely about *finding* a suitable site but about building a defensible case for why the data from that site can bear the analytical weight you intend to place on it.

---

## 9. The data minimization tension

There is a tension in digital data collection that researchers working in this space need to confront honestly, and it concerns the ethics of data practice rather than the mechanics of collection.

Data minimization is a core principle in research ethics and, in Europe, a legal requirement under GDPR. It holds that you should collect only the personal data you actually need for your specified research purposes. The logic is clear: data that you collect but do not need creates unnecessary privacy risk for the individuals whose traces you are gathering. You should collect what you need, use it for the purpose you specified, and not stockpile more than is necessary.

The challenge is that large-scale qualitative exploration — one of the central analytical moves in the mixed digital methods workflow — requires collecting data before you know precisely what you will need. The logic of computational grounded theory (Carlsen & Ralund 2022) is explicitly exploratory: you collect a corpus, you use topic models or keyword searches to map its thematic landscape, and you use that map to identify where the most analytically interesting material lies. The mapping step is what tells you what to read closely. But the mapping step requires having the data first.

This tension is genuine. A researcher cannot truthfully tell a data protection authority "I know exactly what data I need" before she has done the exploratory analysis that would reveal which corners of the corpus are relevant. Strict data minimization, applied naively, would prohibit the exploratory work that mixed digital methods depends on.

The resolution is not to ignore the tension but to turn it into an advantage. The netnographic immersion documented in Chapter 3 is precisely the evidence that justifies exploratory collection. By spending weeks reading the prepper forum before constructing a sampling frame, the researcher can offer a specific and considered rationale for the data she is collecting: she knows what topics the community discusses, she understands which data types (text, activity, relational) are necessary for her analysis, and she can explain why the temporal scope she has chosen is the minimum needed to capture the phenomenon she is studying. The netnographic record — the immersion journal, the observational templates, the site evaluation — becomes the documentation that makes exploratory collection defensible.

This is an important reframe. Data minimization, properly understood, does not require that the researcher know every specific use of every data point before collection. It requires that she have well-considered reasons for why the scope of collection is necessary and proportionate to her research purposes. Netnographic immersion provides those reasons. It transforms what might otherwise look like "collecting everything in case it comes in handy" into "collecting what the netnographic evidence tells us we will need for a specific exploratory purpose."

Two further considerations help sharpen this argument. First, the data minimization principle applies to the large-scale data collection, not to the online observations that form the netnographic record. The ethnographic convention of note-taking and observation does not typically involve downloading bulk datasets; it involves a researcher visiting a site, reading its content, and recording observations in a journal. This mode of engagement generates no data minimization issues in the ordinary sense — the researcher is simply reading what is publicly posted, as any member of the public could. The ethical pressure arises specifically at the point of systematic, large-scale collection.

Second, being specific and transparent about what you collect and why — and being prepared to justify those choices to ethics review processes — is not a burden to be minimized but a discipline that improves the research design. Researchers who are forced to articulate why they need a particular data type, over a particular time window, from a particular set of actors or locations, often discover that they had not thought those questions through as carefully as they might. The ethics requirement and the methodological requirement converge: both push toward careful, intentional data collection design.

---

## 10. Putting it together: data collection design for the prepper project

Let us return to the prepper example and see how these principles work in practice.

The research group has completed the netnographic investigation described in Chapter 3. They have mapped the landscape of prepper communities, selected r/preppers as their primary research site on the basis of the RAIDR criteria, spent several weeks reading the forum and building an immersion journal, and developed an observational template that organizes what they have learned. They know the vocabulary of the community, its norms, its central themes, and the kinds of debates that animate it. They are ready to design a data collection.

The first step is specifying the sampling frame. Given their research question — how prepper communities construct and negotiate the concept of self-reliance — a forum-complete strategy for r/preppers is appropriate. They want all text posts (open, narrative data) and their associated replies from the past three years. They also want activity data (upvotes, reply counts) to help identify high-salience posts, and basic relational data (author identifiers, reply-to relationships) to enable a network view of who participates with whom.

The second step is identifying the collection approach. Reddit's API provides access to current and recent posts; for historical data beyond the API's standard window, they supplement with archived Reddit datasets (PushShift archives or community-maintained archives). They document the coverage of each source and note where gaps exist.

The third step is data quality assessment. After collection, they compare their corpus against the forum's own record of post counts to estimate completeness. They check for duplicate records, malformed timestamps, and incomplete text fields. They assess whether the temporal distribution of collected posts matches the forum's actual activity history, or whether there are suspicious gaps that might indicate collection failures.

The fourth step is articulating the data minimization justification. Drawing on their immersion journal and site evaluation, they document: why this subreddit (and not a more extensive cross-platform collection) is sufficient for their research question; why three years is the minimum temporal scope needed to capture meaningful variation in the community's discourse; and what specific analytical uses each data type will serve. This documentation goes into the methods section of their eventual write-up and, if required, into an ethics application.

The result is a dataset that is well-understood, well-documented, and purposefully assembled — not simply "all the data we could get." This is what data collection design in a digital mixed methods context looks like.

---

## Summary

Digital data has disrupted the classical divide between qualitative and quantitative data collection, but not by making the choice unnecessary. It has made the choice more complex. The researcher who works with digital found data must think simultaneously about what kind of data she is collecting (text, activity, relational, temporal), what analytical purpose each type serves, how different types integrate in the overall design, and how to construct a sampling frame that matches her research question.

Three sampling logics are available: actor-based sampling, which follows people; topic-based sampling, which follows content; and location-based sampling, which collects everything within a bounded site. Each has its own strengths and limitations, and sophisticated designs often combine them. Collection is implemented through APIs and web scraping — curated and raw access to platform data respectively — each with technical constraints that have methodological implications.

Throughout, the netnographic foundation laid in Chapter 3 does double duty: it provides the qualitative understanding that makes the sampling frame coherent, and it provides the documented justification that makes large-scale exploratory collection ethically defensible. Data minimization and mixed methods exploration are not opposed: when exploration is grounded in prior qualitative engagement, it can be articulated as a principled and proportionate research choice.

The next chapter turns to what happens once the data have been collected: how to move from a large, messy corpus of digital text to the qualitative reading that lies at the heart of the mixed methods analysis.

---

*Key concepts: degree of digitalization; text/activity/relational/temporal data; narrative vs. action data; open vs. closed data; actor-based sampling; topic-based sampling; location-based (forum-complete) sampling; snowball sampling; API; web scraping; data minimization; data integration (integrated, hierarchical/nested, transformation)*
