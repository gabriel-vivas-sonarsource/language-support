
// === NOT COMPLIANT ===
// comment ‪ comment
// comment ‫ comment
// comment ‭ comment
// comment ‮ comment
// comment ⁦ comment
// comment ⁧ comment
// comment ⁨ comment

// Wrong closing char
// comment ‪ comment ⁩ comment
// comment ⁦ comment ‬ comment

// More opening than closing
// comment ‪ comment ‬ comment ‫ comment
// comment ⁦ comment ⁩ comment ⁧ comment

// Different unclosed. We do report on the first
// comment ‪ comment ⁦ comment
// comment ⁦ comment ‪ comment

// === COMPLIANT ===

// comment 😀 comment

// Correctly closed formatting chars:
// comment ‪ comment ‬ comment
// comment ‫ comment ‬ comment
// comment ‭ comment ‬ comment
// comment ‮ comment ‬ comment
// comment ‮ ‪ comment ‬ ‬ comment

// Correctly close isolate chars:
// comment ⁦ comment ⁩ comment
// comment ⁧ comment ⁩ comment
// comment ⁨ comment ⁩ comment