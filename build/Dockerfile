FROM tailscale/tailscale
ENV SECRET_AUTH_KEY=tailscale_key_required
RUN systemctl start tailscaled
CMD tailscale up --authkey=$SECRET_AUTH_KEY
