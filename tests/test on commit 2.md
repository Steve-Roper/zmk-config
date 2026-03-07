# Shorting pins

## LEFT uf2
031 - 020: n
031 - 022: h
031 - 024: y
031 - 100: space
031 - 011: n/a
031 - 017: 6

115 - 020: c
115 - 022: d
115 - 024: e
115 - 100: shift
115 - 011: n/a
115 - 017: 3

002 - 020: x
002 - 022: s
002 - 024: w
002 - 100: alt
002 - 011: n/a
002 - 017: 2

029 - 020: z
029 - 022: a
029 - 024: q
029 - 100: ctrl
029 - 011: n/a
029 - 017: 1

113 - 020: v
113 - 022: f
113 - 024: r
113 - 100: n/a
113 - 011: n/a
113 - 017: 4

## Right uf2
113 - 017: 0
113 - 020: dash
113 - 022: ö
113 - 024: p
113 - 100: n/a
113 - 011: n/a

115 - 017: 3
115 - 020: period
115 - 022: l
115 - 024: o
115 - 100: n/a
115 - 011: n/a

002 - 017: 8
002 - 020: comma
002 - 022: k
002 - 024: i
002 - 100: n/a
002 - 011: n/a

029 - 017: 7
029 - 020: m
029 - 022: j
029 - 024: u
029 - 100: enter
029 - 011: n/a

031 - 017: backtick
031 - 020: down
031 - 022: single quote
031 - 024: umlaut
031 - 100: n/a
031 - 011: n/a

# Shorting pads
Rows and columns are given left->right, top->bottom for button side up. 0-index.

(row, column) = key/can't test;

## right keyboard
(0, 0) = can't test, (0, 1) = can't test, (0, 2) = ö (expected 9),    (0, 3) = p (expected 0),     (0, 4) = n/a (expected dash), (0, 5) = n/a (expected equals),
(1, 0) = 9 (expected u),        (1, 1) = n/a (expected i),      (1, 2) = l (expected o),  (1, 3) = o (expected p),     (1, 4) = n/a (expected å), (1, 5) = n/a (expected umlaut),
(2, 0) = n/a (expected j),          (2, 1) = comma (expected k),     (2, 2) = n/a (expected l),    (2, 3) = i (expected ö),     (2, 4) = shift (expected ä), (2, 5) = n/a (expected single quote),
(3, 0) = 7 (expected m),        (3, 1) = n/a (expected comma),       (3, 2) = n/a (expected period),    (3, 3) = u (expected dash),   (3, 4) = enter (expected shift), (3, 5) = n/a (expected up),
(4, 0) = backtick (expected enter),                               (4, 3) = umlaut (expected right shift),  (4, 4) = ctrl (expected alt), (4, 5) = n/a (expected ctrl),


## left keyboard
(0, 0) = n (expected 1),    (0, 1) = h (expected 2), (0, 2) = y (expected 3),  (0, 3) = n/a (expected 4), (0, 4) = can't test (expected 5), (0, 5) = can't test (expected 6),
(1, 0) = n/a (expected q),    (1, 1) = d (expected w), (1, 2) = e (expected e),    (1, 3) = n/a (expected r),   (1, 4) = n/a (expected t),        (1, 5) = n/a (expected y),
(2, 0) = x (expected a),    (2, 1) = n/a (expected s), (2, 2) = w (expected d),  (2, 3) = n/a (expected f),   (2, 4) = n/a (expected g),        (2, 5) = 2 (expected h),
(3, 0) = z (expected z),  (3, 1) = a (expected x), (3, 2) = q (expected c),    (3, 3) = n/a (expected v),   (3, 4) = n/a (expected b),        (3, 5) = 1 (expected n),
(4, 0) = v (expected ctrl),    (4, 1) = f (expected alt), (4, 2) = r (expected shift),                                         (4, 5) = n/a (expected space),