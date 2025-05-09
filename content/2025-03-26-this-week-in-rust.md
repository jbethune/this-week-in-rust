Title: This Week in Rust 592
Number: 592
Date: 2025-03-26
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](https://www.rust-lang.org/) is a programming language empowering everyone to build reliable and efficient software.
This is a weekly summary of its progress and community.
Want something mentioned? Tag us at [@ThisWeekInRust](https://x.com/ThisWeekInRust) on X (formerly Twitter) or [@ThisWeekinRust](https://mastodon.social/@thisweekinrust) on mastodon.social, or [send us a pull request](https://github.com/rust-lang/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/rust-lang/this-week-in-rust) and archives can be viewed at [this-week-in-rust.org](https://this-week-in-rust.org/).
If you find any errors in this week's issue, [please submit a PR](https://github.com/rust-lang/this-week-in-rust/pulls).

Want TWIR in your inbox? [Subscribe here](https://this-week-in-rust.us11.list-manage.com/subscribe?u=fd84c1c757e02889a9b08d289&id=0ed8b72485).

## Updates from Rust Community

<!--

Dear community contributors:
Please read README.md for guidance on submissions.
Each submitted link should be of the form:

* [Title of the Linked Page](https://example.com/my_article)

If you don't know which category to use, feel free to submit a PR anyway
and just ask the editors to select the category.

-->

### Foundation
* [Ferrous Systems Donates Ferrocene Language Specification to Rust Project](https://rustfoundation.org/media/ferrous-systems-donates-ferrocene-language-specification-to-rust-project/)

### Project/Tooling Updates
* [Fastrace: A Modern Approach to Distributed Tracing in Rust](https://fast.github.io/blog/fastrace-a-modern-approach-to-distributed-tracing-in-rust/)
* [rust-analyzer changelog #278](https://rust-analyzer.github.io/thisweek/2025/03/24/changelog-278.html)
* [Introducing Cot v0.2: A new version of the Rust web framework for lazy developers](https://mackow.ski/blog/introducing-cot-v02/)

### Observations/Thoughts
* [Does unsafe undermine Rust's guarantees?](https://steveklabnik.com/writing/does-unsafe-undermine-rusts-guarantees/)
* [Notes on coreutils in Rust](https://alexgaynor.net/2025/mar/22/coreutils-in-rust/)
* [Rust in 2025: Language interop and the extensible compiler](https://smallcultfollowing.com/babysteps/blog/2025/03/18/lang-interop-extensibility/)
* [Dyn async traits, part 10: Box box box](https://smallcultfollowing.com/babysteps/blog/2025/03/24/box-box-box/)
* [Dyn you have idea for `dyn`?](https://smallcultfollowing.com/babysteps/blog/2025/03/25/dyn-you-have-idea-for-dyn/)
* [Safe Delayed Initialization for Lifetime Extension](https://paper.wf/binarycat/safe-delayed-initialization-for-lifetime-extension)
* [Just write a test for it](https://kobzol.github.io/rust/2025/03/25/just-write-a-test-for-it.html)
* [audio] [ExpressVPN with Pete Membrey](https://rustacean-station.org/episode/pete-membrey/)
* [Building a fast website with the MASH stack](https://emschwartz.me/building-a-fast-website-with-the-mash-stack-in-rust/)

### Rust Walkthroughs
* [A Daft proc-macro trick: How to Emit Partial-Code + Errors](https://schneems.com/2025/03/26/a-daft-procmacro-trick-how-to-emit-partialcode-errors/)
* [Vendoring C/C++ Dependencies in Rust](https://blog.veeso.dev/blog/en/vendoring-c-cpp-dependencies-in-rust/)
* [Fastest Vec Update on My Computer](https://jtjlehi.github.io/2024/03/13/fastest-vec-update-on-my-computer.html)
* [A 10x faster batch job by batching PostgreSQL inserts/updates with Rust and SQLx](https://kerkour.com/postgresql-batching)
* [Bridging the Efficiency Gap Between FromStr and String](https://lucumr.pocoo.org/2025/3/23/from-string/)
* [video] [Build with Naz : traits, subtyping, polymorphism in Rust](https://www.youtube.com/watch?v=K5SY-lc8nTE)
* [video] [Rust and embedded programming with Leon Vak](https://rust.code-maven.com/rust-and-embedded-programming-with-leon-vak)

## Crate of the Week

This week's crate is [jiff](https://crates.io/crates/jiff), a datetime library for Rust.

Thanks to [Filip T](https://users.rust-lang.org/t/crate-of-the-week/2704/1420) for the suggestion!

[Please submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

## Calls for Testing
An important step for RFC implementation is for people to experiment with the
implementation and give feedback, especially before stabilization.

If you are a feature implementer
and would like your RFC to appear in this list, add a `call-for-testing` label to your RFC along
with a comment providing testing instructions and/or guidance on which aspect(s) of the feature
need testing.

* *No calls for testing were issued this week by [Rust](https://github.com/rust-lang/rust/labels/call-for-testing),
  [Rust language RFCs](https://github.com/rust-lang/rfcs/issues?q=label%3Acall-for-testing) or
  [Rustup](https://github.com/rust-lang/rustup/labels/call-for-testing).*

[Let us know](https://github.com/rust-lang/this-week-in-rust/issues) if you would like your feature to be tracked as a part of this list.

## Call for Participation; projects and speakers

### CFP - Projects

Always wanted to contribute to open-source projects but did not know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

<!-- CFPs go here, use this format: * [project name - title of issue](URL to issue) -->
<!-- * [ - ]() -->
<!-- or if none - *No Calls for participation were submitted this week.* -->

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines] or through a [PR to TWiR](https://github.com/rust-lang/this-week-in-rust) or by reaching out on [X (formerly Twitter)](https://x.com/ThisWeekInRust) or [Mastodon](https://mastodon.social/@thisweekinrust)!

[guidelines]:https://github.com/rust-lang/this-week-in-rust?tab=readme-ov-file#call-for-participation-guidelines

### CFP - Events

Are you a new or experienced speaker looking for a place to share something cool? This section highlights events that are being planned and are accepting submissions to join their event as a speaker.

<!-- CFPs go here, use this format: * [**event name**](URL to CFP)| Date CFP closes in YYYY-MM-DD | city,state,country | Date of event in YYYY-MM-DD -->
<!-- or if none - *No Calls for papers or presentations were submitted this week.* -->

If you are an event organizer hoping to expand the reach of your event, please submit a link to the website through a [PR to TWiR](https://github.com/rust-lang/this-week-in-rust) or by reaching out on [X (formerly Twitter)](https://x.com/ThisWeekInRust) or [Mastodon](https://mastodon.social/@thisweekinrust)!

## Updates from the Rust Project

496 pull requests were [merged in the last week][merged]

[merged]: https://github.com/search?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2025-03-18..2025-03-25

#### Compiler

* [lower to a `memset(undef)` when `Rvalue::Repeat` repeats uninit](https://github.com/rust-lang/rust/pull/138634)

#### Library

* [`MaybeUninit` inherent slice methods part 2](https://github.com/rust-lang/rust/pull/135394)
* [core/slice: mark some `split_off` variants unstably const](https://github.com/rust-lang/rust/pull/138540)
* [core: optimize `RepeatN`](https://github.com/rust-lang/rust/pull/138833)
* [implement default methods for `io::Empty` and `io::Sink`](https://github.com/rust-lang/rust/pull/137051)
* [optimize `io::Write::write_fmt` for constant strings](https://github.com/rust-lang/rust/pull/138650)
* [simplify `PartialOrd` on tuples containing primitives](https://github.com/rust-lang/rust/pull/138135)
* [reduce `FormattingOptions` to 64 bits](https://github.com/rust-lang/rust/pull/136974)

#### Cargo

* [add custom completer for cargo `<TAB>` to complete aliases defined in config.toml](https://github.com/rust-lang/cargo/pull/15319)

#### Rustdoc

* [be more strict about "Methods from Deref"](https://github.com/rust-lang/rust/pull/138574)
* [gate unstable `doc(cfg())` predicates](https://github.com/rust-lang/rust/pull/138293)
* [use own logic to print `#[repr(..)]` attributes in JSON output](https://github.com/rust-lang/rust/pull/138018)

#### Clippy

* [`wildcard_imports`: lint on `pub use` if asked to](https://github.com/rust-lang/rust-clippy/pull/14182)
* [add MSRV check for `question_mark`](https://github.com/rust-lang/rust-clippy/pull/14436)
* [add `ignore_without_reason` lint](https://github.com/rust-lang/rust-clippy/pull/13931)
* [emit `collapsible_match` at the right node](https://github.com/rust-lang/rust-clippy/pull/14311)
* [expand `neg_multiply` to lint float numbers as well](https://github.com/rust-lang/rust-clippy/pull/14447)
* [fix suggestion for assignments have enclosing parentheses under `needless_late_init`](https://github.com/rust-lang/rust-clippy/pull/14169)
* [fix: `borrow_deref_ref` suggests wrongly when coerce to mut](https://github.com/rust-lang/rust-clippy/pull/14403)
* [fix: `filter_map_bool_then` suggest wrongly when the closure cannot be decompose directly](https://github.com/rust-lang/rust-clippy/pull/14370)
* [fix: `manual_find` suggests wrongly when early return](https://github.com/rust-lang/rust-clippy/pull/14405)
* [fix: `missing_const_for_fn` false positive on unstable const traits](https://github.com/rust-lang/rust-clippy/pull/14294)
* [fix: `nonminimal_bool` wrongly showed the macro definition](https://github.com/rust-lang/rust-clippy/pull/14424)
* [fix: `option_if_let_else` false positive when value partially moved](https://github.com/rust-lang/rust-clippy/pull/14209)
* [fix: `redundant_clone` false positive on `enum` cast](https://github.com/rust-lang/rust-clippy/pull/14395)
* [improve `string_to_string` lint in case it is in a map call](https://github.com/rust-lang/rust-clippy/pull/14396)
* [lint more cases in `collapsible_if`](https://github.com/rust-lang/rust-clippy/pull/14231)
* [make `never_loop` applicability more flexible](https://github.com/rust-lang/rust-clippy/pull/14203)
* [move `uninlined_format_args` back to `style`](https://github.com/rust-lang/rust-clippy/pull/14160)
* [reinstate `single_match`/`single_match_else` lints with comments](https://github.com/rust-lang/rust-clippy/pull/14420)
* [suggest `is_some_and` instead of `map_or` in `case_sensitive_file_extension_comparions`](https://github.com/rust-lang/rust-clippy/pull/14358)
* [unify `manual_unwrap_or` and `manual_unwrap_or_default` code](https://github.com/rust-lang/rust-clippy/pull/14332)
* [use `code` for references to other lints in `as_conversions` docs](https://github.com/rust-lang/rust-clippy/pull/14283)

#### Rust-Analyzer

* [fix ide-assist `let else` to `if let else`](https://github.com/rust-lang/rust-analyzer/pull/19433)
* [add diagnostic for missing ambiguity error for impl trait](https://github.com/rust-lang/rust-analyzer/pull/19347)
* [add postfix completion for const block](https://github.com/rust-lang/rust-analyzer/pull/19397)
* [add text edit support for return type hints on non-block body closures](https://github.com/rust-lang/rust-analyzer/pull/19348)
* [analysis-stats: emit lines of code and item tree counts for workspace; dependencies](https://github.com/rust-lang/rust-analyzer/pull/19359)
* [parse `unsafe` record fields](https://github.com/rust-lang/rust-analyzer/pull/19388)
* [fix missing syntax highlighting for `&raw const` / `&raw mut` in all files](https://github.com/rust-lang/rust-analyzer/pull/19400)
* [fix closure return inlayhints using macro ranges](https://github.com/rust-lang/rust-analyzer/pull/19435)
* [handle multiple `#[repr(..)]` attrs correctly](https://github.com/rust-lang/rust-analyzer/pull/19416)
* [properly calculate the layouts of tuple ptrs whose last fields are DST](https://github.com/rust-lang/rust-analyzer/pull/19413)
* [render layout and other extra information on hovering `Self`](https://github.com/rust-lang/rust-analyzer/pull/19419)
* [speed up resolving a "Generate delegate method" assist](https://github.com/rust-lang/rust-analyzer/pull/19362)

### Rust Compiler Performance Triage

A nearly noise-free week, which is exciting, with a number of fairly large
improvements landing for a cumulative average speed up 0.5%, possibly larger if
we ignore the likely to be fixed or reverted regressions from
[#138674](https://github.com/rust-lang/rust/pull/138674).

Triage done by **@simulacrum**.
Revision range: [493c38ba..4510e86a](https://perf.rust-lang.org/?start=493c38ba371929579fe136df26eccd9516347c7a&end=4510e86a41388733675465a8647d4235f3bf2023&absolute=false&stat=instructions%3Au)

3 Regressions, 4 Improvements, 2 Mixed; 3 of them in rollups
35 artifact comparisons made in total

Read the [full report](https://github.com/rust-lang/rustc-perf/blob/master/triage/2025-03-24.md) for more details.

### [Approved RFCs](https://github.com/rust-lang/rfcs/commits/master)

Changes to Rust follow the Rust [RFC (request for comments) process](https://github.com/rust-lang/rfcs#rust-rfcs). These
are the RFCs that were approved for implementation this week:

* *No RFCs were approved this week.*

### Final Comment Period

Every week, [the team](https://www.rust-lang.org/team.html) announces the 'final comment period' for RFCs and key PRs
which are reaching a decision. Express your opinions now.

#### Tracking Issues & PRs
##### [Rust](https://github.com/rust-lang/rust/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
* [Deprecate the unstable `concat_idents!`](https://github.com/rust-lang/rust/pull/137653)
* [Stabilize `#![feature(precise_capturing_in_traits)]`](https://github.com/rust-lang/rust/pull/138128)

##### [Rust RFCs](https://github.com/rust-lang/rfcs/labels/final-comment-period)
* [Tracking Issue for slice::array_chunks](https://github.com/rust-lang/rust/issues/74985)
* [stabilize const_cell](https://github.com/rust-lang/rust/pull/137928)
* [Remove backticks from `ShouldPanic::YesWithMessage`'s `TrFailedMsg`](https://github.com/rust-lang/rust/pull/136160)
* [Use `BinOp::Cmp` for `iNN::signum`](https://github.com/rust-lang/rust/pull/137835)
* [Prefer built-in sized impls (and only sized impls) for rigid types always](https://github.com/rust-lang/rust/pull/138176)

#### Other Areas
* *No Items entered Final Comment Period this week for
  [Cargo](https://github.com/rust-lang/cargo/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc),
  [Language Team](https://github.com/rust-lang/lang-team/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc+),
  [Language Reference](https://github.com/rust-lang/reference/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc) or
  [Unsafe Code Guidelines](https://github.com/rust-lang/unsafe-code-guidelines/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc).

Let us know if you would like your PRs, Tracking Issues or RFCs to be tracked as a part of this list.

#### [New and Updated RFCs](https://github.com/rust-lang/rfcs/pulls)
* *No New or Updated RFCs were created this week.*

## Upcoming Events

Rusty Events between 2025-03-26 - 2025-04-23 🦀

### Virtual
* 2025-03-27 | Virtual (Berlin, DE) | [Rust Berlin](https://www.meetup.com/rust-berlin/events/)
    * [**Rust Hack and Learn**](https://www.meetup.com/rust-berlin/events/300820297)
* 2025-04-01 | Virtual (Buffalo, NY, US) | [Buffalo Rust Meetup](https://www.meetup.com/buffalo-rust-meetup/events/)
    * [**Buffalo Rust User Group**](https://www.meetup.com/buffalo-rust-meetup/events/305304228)
* 2025-04-02 | Virtual (Indianapolis, IN, US) | [Indy Rust](https://www.meetup.com/indyrs/events/)
    * [**Indy.rs - with Social Distancing**](https://www.meetup.com/indyrs/events/302031661)
* 2025-04-03 | Virtual (Nürnberg, DE) | [Rust Nurnberg DE](https://www.meetup.com/rust-noris/)
    * [**Rust Nürnberg online**](https://www.meetup.com/rust-noris/events/300820282/)
* 2025-04-05 | Virtual | [Ardan Labs](https://www.eventbrite.com/o/ardan-labs-7092394651)
    * [**Communicate with Channels in Rust**](https://www.eventbrite.com/e/communicate-with-channels-in-rust-tickets-1278267335009)
* 2025-04-05 | Virtual (Kampala, UG) | [Rust Circle Meetup](https://www.eventbrite.com/o/rust-circle-kampala-65249289033)
    * [**Rust Circle Meetup**](https://www.eventbrite.com/e/rust-circle-meetup-tickets-628763176587)
* 2025-04-08 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust/events/)
    * [**Second Tuesday**](https://www.meetup.com/dallasrust/events/303522530)
* 2025-04-10 | Virtual (Berlin, DE) | [Rust Berlin](https://www.meetup.com/rust-berlin/events/)
    * [**Rust Hack and Learn**](https://www.meetup.com/rust-berlin/events/300820298)
* 2025-04-15 | Virtual (Washington, DC, US) | [Rust DC](https://www.meetup.com/rustdc/events/)
    * [**Mid-month Rustful**](https://www.meetup.com/rustdc/events/305170698)
* 2025-04-16 | Virtual (Vancouver, BC, CA) | [Vancouver Rust](https://www.meetup.com/vancouver-rust/events/)
    * [**Rust Study/Hack/Hang-out**](https://www.meetup.com/vancouver-rust/events/306231500)
* 2025-04-17 | Virtual and In-Person (Redmond, WA, US) | [Seattle Rust User Group](https://www.meetup.com/join-srug/events/)
    * [**April, 2025 SRUG (Seattle Rust User Group) Meetup**](https://www.meetup.com/seattle-rust-user-group/events/305658454)
* 2025-04-22 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust/events/)
    * [**Fourth Tuesday**](https://www.meetup.com/dallasrust/events/305361432)

### Asia
* 2025-03-28 | Kowloon Tong, HK | [Rust Asia](https://www.rustasiaconf.com/)
    * [**Rust Asia 2025**](https://www.rustasiaconf.com/)
* 2025-04-05 | Bangalore/Bengaluru, IN | [Rust Bangalore](https://hasgeek.com/rustbangalore)
    * [**April 2025 Rustacean meetup**](https://hasgeek.com/rustbangalore/april-2025-rustacean-meetup/)
* 2025-04-22 | Tel Aviv-Yafo, IL | [Rust 🦀 TLV](https://www.meetup.com/rust-tlv/events/)
    * [**In person Rust April 2025 at Braavos in Tel Aviv in collaboration with StarkWare**](https://www.meetup.com/rust-tlv/events/306530984)

### Europe
* 2025-03-26 | Frankfurt, DE | [Rust Rhein-Main](https://www.meetup.com/rust-rhein-main/events/)
    * [**“Beyond blazingly fast!” Performance Optimierungen in Rust**](https://www.meetup.com/rust-rhein-main/events/306659893)
* 2025-03-26 | Manchester, UK | [Rust Manchester](https://www.meetup.com/rust-manchester/events/)
    * [**Rust Manchester Talks March**](https://www.meetup.com/rust-manchester/events/305897029)
* 2025-03-26 | Warsaw, PL | [Rustikon](https://www.rustikon.dev/)
    * [**Rustikon**](https://www.rustikon.dev/)
* 2025-03-27 | Augsburg, DE | [Rust Meetup Augsburg](https://rust-augsburg.github.io/meetup)
    * [**Rust Meetup #12: Testing in Rust**](https://rust-augsburg.github.io/meetup/Meetup_12.html)
* 2025-03-27 | Copenhagen, DK | [Copenhagen Rust Community](https://www.meetup.com/copenhagen-rust-community/events/)
    * [**Rust meetup #56**](https://www.meetup.com/copenhagen-rust-community/events/306659637)
* 2025-03-29 | Stockholm, SE | [Stockholm Rust](https://www.meetup.com/stockholm-rust/events/)
    * [**Ferris' Fika Forum #10**](https://www.meetup.com/stockholm-rust/events/306770525)
* 2025-04-02 | Cambridge, UK | [Cambridge Rust Meetup](https://www.meetup.com/cambridge-rust-meetup/events/)
    * [**Monthly Rust Meetup**](https://www.meetup.com/cambridge-rust-meetup/events/306553077)
* 2025-04-02 | München, DE | [Rust Munich](https://www.meetup.com/rust-munich/events/)
    * [**Rust Munich 2025 / 1 - hybrid**](https://www.meetup.com/rust-munich/events/306097261)
* 2025-04-02 | Oxford, UK | [Oxford Rust Meetup Group](https://www.meetup.com/oxford-rust-meetup-group/events/)
    * [**Oxford Rust and C++ social**](https://www.meetup.com/oxford-rust-meetup-group/events/306541535)
* 2025-04-02 | Stockholm, SE | [Stockholm Rust](https://www.meetup.com/stockholm-rust/events/)
    * [**Rust Meetup @Funnel**](https://www.meetup.com/stockholm-rust/events/306627608)
* 2025-04-03 | Oslo, NO | [Rust Oslo](https://www.meetup.com/rust-oslo/events/)
    * [**Rust Hack'n'Learn at Kampen Bistro**](https://www.meetup.com/rust-oslo/events/305809680)
* 2025-04-08 | Olomouc, CZ | [Rust Moravia](https://www.meetup.com/rust-moravia/events/)
    * [**3. Rust Moravia Meetup (Real Embedded Rust)**](https://www.meetup.com/rust-moravia/events/306377283)
* 2025-04-09 | Girona, ES | [Rust Girona](https://lu.ma/rust-girona)
    * [**Rust Girona Hack & Learn 04 2025**](https://lu.ma/dlvfol30)
* 2025-04-09 | Reading, UK | [Reading Rust Workshop](https://www.meetup.com/reading-rust-workshop/events/)
    * [**Reading Rust Meetup**](https://www.meetup.com/reading-rust-workshop/events/305045446)
* 2025-04-10 | Karlsruhe, DE | [Rust Hack & Learn Karlsruhe](https://www.meetup.com/rust-hack-learn-karlsruhe/events/)
    * [**Karlsruhe Rust Hack and Learn Meetup bei BlueYonder**](https://www.meetup.com/rust-hack-learn-karlsruhe/events/306682264)
* 2025-04-15 | Leipzig, DE | [Rust - Modern Systems Programming in Leipzig](https://www.meetup.com/rust-modern-systems-programming-in-leipzig/events/)
    * [**Topic TBD**](https://www.meetup.com/rust-modern-systems-programming-in-leipzig/events/305741632)
* 2025-04-15 | London, UK | [Women in Rust](https://www.meetup.com/women-in-rust/events/)
    * [**WIR x WCC: Finding your voice in Tech**](https://www.meetup.com/women-in-rust/events/306774769)
* 2025-04-19 | Istanbul, TR | [Türkiye Rust Community](https://kommunity.com/turkiye-rust-community/events)
    * [**Rust Konf Türkiye**](https://kommunity.com/turkiye-rust-community/events/rust-konf-turkiye-91f7b3a6)
* 2025-04-23 | London, UK | [London Rust Project Group](https://www.meetup.com/london-rust-project-group/events/)
    * [**Fusing Python with Rust using raw C bindings**](https://www.meetup.com/london-rust-project-group/events/306644439)

### North America
* 2025-03-26 | Austin, TX, US | [Rust ATX](https://www.meetup.com/rust-atx/events/)
    * [**Rust Lunch - Fareground**](https://www.meetup.com/rust-atx/events/xvkdgtyhcfbjc)
* 2025-03-26 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust/events/)
    * [**Allston Rust Dinner, March 26th!**](https://www.meetup.com/bostonrust/events/306847057)
* 2025-03-26 | New York, NY, US | [Rust NYC](https://www.meetup.com/rust-nyc/events/)
    * [**Rust NYC: I can't believe that's legal Rust with Michael Gattozzi (NEW LOCATION)**](https://www.meetup.com/rust-nyc/events/306777565)
* 2025-03-27 | Atlanta, GA, US | [Rust Atlanta](https://www.meetup.com/rust-atl/events/)
    * [**We're going again!**](https://www.meetup.com/rust-atl/events/306470345)
* 2025-03-29 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust/events/)
    * [**North End Rust Lunch, Mar 29**](https://www.meetup.com/bostonrust/events/306844321)
* 2025-03-31 | Boulder, CO, US | [Solid State Depot](https://www.meetup.com/solidstatedepot/events/)
    * [**Boulder Rust: Bryan presents Rusted Hardware**](https://www.meetup.com/solidstatedepot/events/306573447)
* 2025-04-03 | Chicago, IL, US | [Chicago Rust Meetup](https://www.meetup.com/chicago-rust-meetup/events/)
    * [**Rust Happy Hour**](https://www.meetup.com/chicago-rust-meetup/events/306728493)
* 2025-04-03 | Montréal, QC, CA | [Rust Montréal](https://www.meetup.com/rust-montreal/events/)
    * [**April Monthly Social**](https://www.meetup.com/rust-montreal/events/306518514/)
* 2025-04-03 | Saint Louis, MO, US | [STL Rust](https://www.meetup.com/stl-rust/events/)
    * [**icu4x - resource-constrained internationalization (i18n)**](https://www.meetup.com/stl-rust/events/304890140)
* 2025-04-06 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust/events/)
    * [**Kendall Rust Lunch, Apr 6**](https://www.meetup.com/bostonrust/events/306844327)
* 2025-04-10 | Portland, OR, US | [PDXRust](https://www.meetup.com/pdxrust/events/)
    * [**TetaNES: A Vaccination for Rust—No Needle, Just the Borrow Checker**](https://www.meetup.com/pdxrust/events/306714209)
* 2025-04-14 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust/events/)
    * [**Coolidge Corner Brookline Rust Lunch, Apr 14**](https://www.meetup.com/bostonrust/events/306844334)
* 2025-04-17 | Nashville, TN, US | [Music City Rust Developers](https://www.meetup.com/music-city-rust-developers/events/)
    * [**Using Rust For Web Series 1 : Why HTMX Is Bad**](https://www.meetup.com/music-city-rust-developers/events/304333092)
* 2025-04-17 | Redmond, WA, US | [Seattle Rust User Group](https://www.meetup.com/join-srug/events/)
    * [**April, 2025 SRUG (Seattle Rust User Group) Meetup**](https://www.meetup.com/seattle-rust-user-group/events/305658454)
* 2025-04-23 | Austin, TX, US | [Rust ATX](https://www.meetup.com/rust-atx/events/)
    * [**Rust Lunch - Fareground**](https://www.meetup.com/rust-atx/events/xvkdgtyhcgbfc)

### Oceania
* 2025-04-14 | Christchurch, NZ | [Christchurch Rust Meetup Group](https://www.meetup.com/christchurch-rustlang-meetup-group/events/)
    * [**Christchurch Rust Meetup**](https://www.meetup.com/christchurch-rustlang-meetup-group/events/306841248)
* 2025-04-22 | Barton, AC, AU | [Canberra Rust User Group](https://www.meetup.com/rust-canberra/events/)
    * [**April Meetup**](https://www.meetup.com/rust-canberra/events/306425557)

### South America
* 2025-03-27 | Medellín, CO | [Rust Medellín](https://www.meetup.com/rust-medellin/events/)
    * [**Multithreading y Terminal User Interfaces con Rust**](https://www.meetup.com/rust-medellin/events/306836484)
* 2025-04-03 | Buenos Aires, AR | [Rust en Español](https://www.meetup.com/rust-argentina/events/)
    * [**Abril - Lambdas y más!**](https://www.meetup.com/rust-argentina/events/306671000)

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

## Jobs
<!--

Rust Jobs:

TWiR has stopped featuring individual job postings. You can read more about this change here:

https://github.com/rust-lang/this-week-in-rust/issues/3412

-->

Please see the latest [Who's Hiring thread on r/rust](https://www.reddit.com/r/rust/comments/1ivrkhs/official_rrust_whos_hiring_thread_for_jobseekers/)

# Quote of the Week

> Did it work? It’s Rust, so it worked on the first try!

– [James Calligeros on the Asahi progress report](https://asahilinux.org/2025/03/progress-report-6-14/)

Thanks to [yerke](https://users.rust-lang.org/t/twir-quote-of-the-week/328/1663) for the suggestion!

[Please submit quotes and vote for next week!](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

*This Week in Rust is edited by: [nellshamrell](https://github.com/nellshamrell), [llogiq](https://github.com/llogiq), [cdmistman](https://github.com/cdmistman), [ericseppanen](https://github.com/ericseppanen), [extrawurst](https://github.com/extrawurst), [U007D](https://github.com/U007D), [joelmarcey](https://github.com/joelmarcey), [mariannegoldin](https://github.com/mariannegoldin), [bennyvasquez](https://github.com/bennyvasquez), [bdillo](https://github.com/bdillo)*

*Email list hosting is sponsored by [The Rust Foundation](https://foundation.rust-lang.org/)*

<small>[Discuss on r/rust](https://www.reddit.com/r/rust/comments/1jkrugx/this_week_in_rust_592/)</small>
