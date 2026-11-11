# 1. Navigate to your AI Downloader folder (or extracted zip folder)
cd ~/Downloads/"AI Downloader"

# 2. Allow macOS permissions and remove quarantine flags
xattr -cr . 2>/dev/null || true
chmod +x companion/bin/ai-download-companion companion/scripts/install_mac.sh

# 3. Register the native companion with your browser
bash companion/scripts/install_mac.sh ilpfealablopfemhaaleadbjdomogbcj
