## Reproduction Steps

Steps to reproduce issue:

1) Install the dioxus cli: `cargo install dioxus-cli`

2) Launch the Dioxus Fullstack app: `dx serve --platform fullstack`

3) Observe the page is not interactive and there is a panic in the console

## Enviorment
I reproduced this issue with:
- dioxus `0.5.0`
- Dioxus features `fullstack`
- rust version `1.77.1`
- OS `Linux 6.8.2-zen1-1-zen #1 ZEN SMP PREEMPT_DYNAMIC x86_64 GNU/Linux`
