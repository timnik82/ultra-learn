# Examples: applying Ultra-learn

## Continuing programme: interpreting A/B results

**Interviewer.** The user wants to read A/B results at work. Existing context supplies the goal and time budget. One question at a time establishes that they can calculate an average but have not studied variability or sampling. No exam is assumed. Grading in this example uses general knowledge, explicitly labelled; numerical claims are checked directly.

**Map Maker.** Propose spread → probability → distributions → sampling → A/B interpretation, with averages already demonstrated. Agree on the map. The current spread module requires the learner to (1) explain that equal averages can hide different variability and (2) compare the spread of two small datasets unaided. Sampling uncertainty and significance testing belong to later modules.

**Attempt.** "A = [4, 5, 6] and B = [0, 5, 10]. Both average 5. Do they vary equally? Explain your reasoning." The learner says yes because the averages match.

**Socratic.** "How far is each value in B from its average?" The learner calculates distances of 5, 0, and 5, but still treats the average as a measure of spread.

**Explainer.** Briefly distinguish center from spread, using distances from the center. Ask the learner to redo the original comparison from the beginning without re-showing the worked answer. They calculate distances of 1, 0, 1 for A and 5, 0, 5 for B, and correctly identify B as more spread out. Record this successful redo as repair evidence; it does not count toward the performance criterion because the explanation was just given.

**Examiner.** Give a fresh comparison: C = [8, 10, 12], D = [5, 10, 15]. The learner independently checks that both average 10 and identifies D as more spread out using the distances. The performance criterion is met. No claim is made about their knowledge of distributions or sampling.

**Listener.** Ask for an explanation of center versus spread in their own words. The learner initially says spread always shrinks when more observations are collected. Keep the module open: this is a misconception about spread itself. Explain that adding observations does not necessarily reduce the variability of individual observations; distinguish this from uncertainty about an estimated mean, which will be studied later. Ask for a new unaided explanation and counterexample. The learner correctly explains the distinction at the module's level and observes that adding 0 and 20 to [8, 10, 12] increases its range. Check the calculation. Both module criteria now pass.

**Clerk.** Record the evidence and mark spread "passed today." Save the learner's corrected explanation in the outline and create cards from their mistakes. Check that both required criteria have a card: the "spread always shrinks" misconception already covers the explain criterion, so add one recall card for the compare-two-datasets criterion. Confirm today's date from the system context, then schedule the first review for the next calendar day and set the topic's Next review date to that date. Next module: probability. Do not mark the module retained until a later review supplies evidence.

**Later review.** Show one card prompt without its answer. If the learner answers correctly without help, record which criterion was demonstrated and schedule the next interval from today; once both required criteria have been demonstrated after a delay, set the module to "retained." If they need help, record the failed review, set the module to "reopened," repair the gap, and schedule a one-day review after correction. Preserve the original pass evidence.

## Focused practice: check a proof

User: "I'm practising proofs. Check this argument, but don't solve it for me."

Enter Checker directly; no interview, curriculum, or topic file is required. Inspect the provided argument, identify the first unsupported step, and ask the learner to justify or repair it. If they are stuck, explain the relevant principle and request a redo without showing the fix. Report what the corrected argument demonstrates without declaring mastery of the entire subject.

## Task simulation: customer support

User: "Help me practise handling a frustrated customer in writing."

Establish any missing constraints, then provide a fictional complaint and a short fictional policy so the learner has enough information to respond. Agree on criteria such as acknowledging the problem, accurately applying the policy, and stating a clear next step. The learner writes the response. Grade it against those criteria, let them revise, then offer a new scenario to check unaided performance. Creating the mock complaint is the agent's job; writing the learner's response is not.
