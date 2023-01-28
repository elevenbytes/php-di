# 11bytes PHP DI fork

Removes types from get / has container functions because for some reason they trigger the following error:

`Declaration of DI\Container::get(string $id): mixed must be compatible with Psr\Container\ContainerInterface::get($id)`
