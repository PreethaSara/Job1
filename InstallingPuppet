wget https://apt.puppet.com/puppet7-release-focal.deb
dpkg -i puppet7-release-focal.deb
apt-get update
apt-get install -y puppet-agent
source /etc/profile.d/puppet-agent.sh
export PATH=/opt/puppetlabs/bin:$PATH
puppet config set server <puppetserver-fqdn> --section main
