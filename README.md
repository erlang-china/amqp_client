# Rebar-friendly fork of Erlang AMQP client

This is a fork of the [official RabbitMQ/AMQP Erlang client](https://github.com/rabbitmq/rabbitmq-erlang-client). 

It's meant to be included in your rebar projects in your rebar.config file:

		{deps, [
			{amqp_client, ".*", {git, "git://github.com/erlang-china/amqp_client.git", {tag, "rabbitmq-3.0.4"}}}
		]}.

The "master" branch of this port is a simple re-packaging of the rabbit_common AMQP client dependency.

### License 

This package, just like the the RabbitMQ server, is licensed under the MPL. For the MPL, please see LICENSE-MPL-RabbitMQ.
