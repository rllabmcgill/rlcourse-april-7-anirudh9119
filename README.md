# rlcourse-april-7-anirudh911
IN this assignment, I experimented using open source implementation of DQN
whether we should backpropagate gradients through RHS of Bellman equation.
Also, I played around with Value Iteration Networks, in grid world 8 * 8.

The results are below!

Input or data, - Grid world 8 * 8
     Epoch | Train Cost |  Train Err | Epoch Time
         0 |    1.33315 |   0.462359 |    4.84918
         1 |   0.249069 |  0.0800026 |    4.77682
         2 |   0.192518 |   0.061394 |    4.85404
         3 |    0.15512 |  0.0478909 |    5.04523
         4 |   0.133514 |  0.0394933 |    5.15007
         5 |    0.12066 |  0.0347479 |     5.0348
         6 |   0.112098 |  0.0318416 |    5.05685
         7 |   0.105849 |  0.0299126 |     5.0097
         8 |   0.101142 |  0.0288194 |    4.86953
         9 |  0.0973033 |  0.0273791 |    4.85849
        10 |  0.0940387 |  0.0265947 |    4.79393
        11 |  0.0908461 |  0.0253729 |    4.96907
        12 |  0.0875334 |  0.0244599 |    4.75435
        13 |  0.0840778 |  0.0236883 |    4.87309
        14 |  0.0808989 |  0.0221708 |    4.90656
        15 |  0.0779749 |  0.0213092 |     5.1259
        16 |  0.0753745 |  0.0206404 |    4.85121
        17 |  0.0733105 |   0.020036 |     4.6639
        18 |  0.0714069 |  0.0194444 |    4.69347
        19 |  0.0695301 |  0.0189429 |    4.83463
        20 |  0.0680007 |  0.0185057 |    4.68921
        21 |  0.0666733 |  0.0180556 |    4.65474
        22 |  0.0654221 |  0.0178369 |    4.81634
        23 |   0.064164 |  0.0172968 |     4.7232
        24 |  0.0630475 |  0.0172068 |    4.64119
        25 |  0.0622611 |  0.0170782 |    4.70598
        26 |  0.0612102 |  0.0166795 |    4.72887
        27 |  0.0603496 |  0.0164609 |    4.83944
        28 |  0.0594351 |  0.0161908 |     4.6846
        29 |  0.0586781 |  0.0162294 |    4.75486
Finished training!
98.51851854479
