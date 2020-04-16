FROM s2i-minimal-notebook:3.6

USER root

# --- Python Installation ---
RUN pip install requirements.txt

USER $NB_UID
