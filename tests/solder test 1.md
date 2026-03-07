# Shorting pads
Rows and columns are given left->right, top->bottom for button side up. 0-index.

(row, column) = status; good/bad/can't test

## Left uf2, right keyboard
(0, 0) = can't test, (0, 1) = can't test, (0, 2) = good, (0, 3) = good, (0, 4) = bad, (0, 5) = bad,
(1, 0) = bad,        (1, 1) = good,       (1, 2) = bad,  (1, 3) = good, (1, 4) = bad, (1, 5) = bad,
(2, 0) = good,       (2, 1) = good,       (2, 2) = good, (2, 3) = good, (2, 4) = bad, (2, 5) = bad,
(3, 0) = bad,        (3, 1) = good,       (3, 2) = good, (3, 3) = bad,  (3, 4) = bad, (3, 5) = bad,
(4, 0) = good,                            (4, 3) = bad,  (4, 4) = good, (4, 5) = bad,


## Right uf2, left keyboard
(0, 0) = bad,  (0, 1) = good, (0, 2) = bad,  (0, 3) = good, (0, 4) = can't test, (0, 5) = can't test,
(1, 0) = good, (1, 1) = good, (1, 2) = good, (1, 3) = bad,  (1, 4) = bad,        (1, 5) = good,
(2, 0) = good, (2, 1) = good, (2, 2) = bad,  (2, 3) = bad,  (2, 4) = bad,        (2, 5) = good,
(3, 0) = bad,  (3, 1) = good, (3, 2) = good, (3, 3) = bad,  (3, 4) = bad,        (3, 5) = good,
(4, 0) = good, (4, 1) = good, (4, 2) = good,                                     (4, 5) = good,