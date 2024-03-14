# Install font from nerdfont.com .e.g. https://github.com/ryanoasis/nerd-fonts/releases/download/v3.1.1/JetBrainsMono.zip

# Install starship. See http://starship.rs
curl -sS https://starship.rs/install.sh | sh

# Add starship to .bashrc
echo "eval "\""\$(starship init bash)"\""" >> ~/.bashrc

# Download starship layout
starship.toml
