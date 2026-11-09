# Signet metarepo Tiltfile
# Discovers and includes nested service Tiltfiles for local development.
config.define_string_list("services")

for svc_dir in ["services/signet-api"]:
    tiltfile = os.path.join(svc_dir, "Tiltfile")
    if os.path.exists(tiltfile):
        include(tiltfile)
