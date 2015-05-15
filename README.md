# blob
#
# "blOB" - a BunsenLabs Openbox Configuration Mnanager
#
# blob-config : a bash script to save or restore Openbox gui configurations
#
# Save options are for  Conky(s)    default or current running conkys
#                       Tint2(s)    default or current running tint2s
#                       Openbox theme
#                       GTK theme
#                       Background (uses Nitrogen or feh, depending which
#                                   has the newer saved bg config file)
#                       Screenshot (Windows are hidden briefly so the image
#                                   is the bare desktop, with any Tint2s 
#                                   or Conkys which are running)
#
# There is an option to view the details of any saved configurations 
#
# blob-config creates "~/.config/blob" to store saved configurations in
# individual directories.
# Screenshots are saved to "~/.config/blob" so they can be viewed collectively;
# the name is the same as the saved config.
#
