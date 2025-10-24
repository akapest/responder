python -m nuitka \
--standalone \
--onefile \
--include-data-files=Responder.conf=. \
--python-flag=-u \
Responder.py