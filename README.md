# Gracecress 1.0 TEST
Native Android graceful tree-labeling puzzle. Android 8+ min26/target35. Package com.gg007.gracecress.

## Rules
Known graceful tree-labeling adaptation. Assign node digits 0-5 once each on a fixed six-node tree. Each of its five drawn edges takes the absolute difference of its endpoint digits, larger minus smaller. These five edge gaps must be 1,2,3,4,5 once each. Only drawn edges count, not every pair of nodes. Zero is a real node label. Gold fixed digits cannot change. Tap a node, then 0-5 or CLEAR. CHECK GAPS accepts any completion satisfying both digit and edge-gap sets. Twelve original uniquely completable clue boards on six fixed tree layouts, with 2-4 gold clues. Undo/reset, GG007 menu/site/privacy, saved palette and optional edge-gap display. Tap the title or Android Back for menu.

## Download and status
https://mega.co.nz/#!0JElDQ4K!qNzQunDJZWhC83UFwMd_XaSS0ZKsqVcl38Nlqo5Kxp8
APK 20974 bytes; SHA256 ec0751c25ea23a7dff37b17ff4df73e903b5e08645b5afbd73d28e3187a315a0. Original certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions, original GG007 icon unchanged. Anonymous downloaded bytes match.

## Checks
Seed 981111 produces twelve distinct clue boards, two on each of six tree layouts. An independent sorted-list oracle compares all 720 node-label permutations per board with the bitmask production evaluator,8640 comparisons and exactly one completion per board. Another 1440 malformed-value/clue comparisons cover invalid ranges, blanks, repeated labels and clue conflicts. Bounds, fixed locks, explicit CHECK, incomplete boards, undo/reset and solved locks pass. All 12 actual drawing-adapter node/digit/check tap-solves plus clear/replay/next/levels/title-menu/privacy/saved palette-edgegaps/completion pass. Twenty drawing previews, including all 12 tree boards, inspected; graphs shifted 20 pixels down after visual spacing check. Not phone screenshots. Phone runtime, performance, browser handoff QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
All 229 prior studio and 803 legacy functional descriptions compared. Live registry is byte-identical to all 803 descriptions personally reviewed last cycle; all 228 earlier studio cards unchanged plus Tokencress reviewed. Rankcress reconstructs permutation order from smaller-to-right counts; Gracecress assigns labels to fixed tree vertices so the edge-difference alphabet occurs once. Spancress reconstructs ruler positions from all 15 pairwise distances; here only five drawn edges count. Chromaring merely separates adjacent colors; Leafcress chooses topology from a Prufer code. No matching factory mechanic found. Known graceful labeling, not globally new. Original seeded clues, native code and tree illustrations. Six math-reference, university and research/game-paper sources inspected. The standard definition allows a subset of 0..mfor general graphs; these six-vertex/five-edge trees use all six values. The cited two-player graceful game is not this single-player clue puzzle. No claim that all trees are graceful, and no current conjecture-status or historical priority claim used.

## Build and tests
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/cycle-test src/com/gg007/gracecress/Board.java BoardTest.java then java -cp /tmp/cycle-test com.gg007.gracecress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret included. adapter/android is a Java2D drawing adapter used with GraceAdapterTest.java, not an Android runtime.

## Privacy and branding
Gracecress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, edge gaps and solved-puzzle marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon and studio https://ilanis-agent.github.io/gg-007-gaming/.

## Preservation and publishing
Complete source/APK, exact cumulative 230-card studio and publishing fragments privately preserved:
https://files.instinct.com/d7n5aeg5057u-gracecress-source-archive
https://github.com/iLanis-agent/gracecress holds README only, full Git source pending. Existing three studio includes and Pages settings untouched. Both live sites verified separately.

## Rule sources
https://mathworld.wolfram.com/GracefulLabeling.html
https://en.wikipedia.org/wiki/Graceful_labeling
https://cs.stanford.edu/~knuth/papers/amazing.pdf
https://journals-sol.sbc.org.br/index.php/reic/article/download/1745/1594/5181
https://www.combinatorics.org/files/Surveys/ds6/ds6v6-2001.pdf
https://actamath.savbb.sk/pdf/aumb2803.pdf
