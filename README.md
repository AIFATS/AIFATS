.spin{
    transform-box:fill-box;
    transform-origin:center;
    animation:spin 7s infinite linear;
}
.spin-counter{
    transform-box:fill-box;
    transform-origin:center;
    animation:spin-counter 7s infinite linear;
}
@keyframes spin{
    0%{transform:rotate(0deg)}
    100%{transform:rotate(359deg)}
}
@keyframes spin-counter{
    0%{transform:rotate(0deg)}
    100%{transform:rotate(-359deg)}
}

