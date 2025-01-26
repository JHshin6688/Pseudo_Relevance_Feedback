# Pseudo_Relevance_Feedback

## Overview
This project explores the implementation and evaluation of pseudo relevance feedback (PRF) in a vector-space retrieval (VSR) system.

The goal is to assess the impact of pseudo relevance feedback on retrieval performance using the Cystic Fibrosis (CF) corpus.

## Key Objectives
### Extend the Feedback Class
Modify ir.vsr.Feedback to support pseudo relevance feedback (PRF).

Preserve existing interactive feedback capabilities while adding the PRF feature.

### Implement New Flags
**-pseudofeedback [m]**: Activates PRF mode with m as the number of top documents to use for feedback.

**-feedbackparams [ALPHA] [BETA] [GAMMA]**: Allows customization of feedback parameters (default: 1.0 for each).


### Experiment
Evaluate the effects of varying the number of feedback documents (m) on recall-precision and NDCG metrics.

Study the impact of different BETA values on PRF performance while keeping ALPHA and GAMMA constant.


### Visualization
Generate recall-precision and NDCG plots to analyze retrieval performance.

Combine results from multiple experiments into comprehensive performance graphs.


### Copyleft
This code supplies "miniature" pedagogical Java implementations of
information retrieval, spidering, and other IR and text-processing
software.  It is being released for educational and research purposes only under
the GNU General Public License (see http://www.gnu.org/copyleft/gpl.html).

It was developed for an introductory course on "Intelligent Information
Retrieval and Web Search".  See:

http://www.cs.utexas.edu/users/mooney/ir-course/ 

for more information and introductory documentation (especially see the Project
assignment descriptions).

Copyleft: Raymond J. Mooney, 2001

